Xero - Tested Hardware & Statistics
-----------------------------------

A project to collect tested hardware configurations for Xero.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Xero/Desktop/README.md) and [notebooks](/Dist/Xero/Notebook/README.md).

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

Total: 400

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | Bravo 15 B5DD               | Notebook    | [1df2dc7261](https://linux-hardware.org/?probe=1df2dc7261) | Oct 01, 2023 |
| Lenovo        | MAHOBAY                     | Desktop     | [9ced54f630](https://linux-hardware.org/?probe=9ced54f630) | Oct 01, 2023 |
| Dell          | 0MN1TX A02                  | Desktop     | [3f0eee5de0](https://linux-hardware.org/?probe=3f0eee5de0) | Oct 01, 2023 |
| Lenovo        | ThinkPad X200 745536T       | Notebook    | [62740874ab](https://linux-hardware.org/?probe=62740874ab) | Sep 30, 2023 |
| Juana Mans... | SF20GM7                     | Notebook    | [b4a58da74c](https://linux-hardware.org/?probe=b4a58da74c) | Sep 30, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [e26d1b1ae4](https://linux-hardware.org/?probe=e26d1b1ae4) | Sep 30, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [074ab86d60](https://linux-hardware.org/?probe=074ab86d60) | Sep 29, 2023 |
| Lenovo        | ThinkPad X200 745536T       | Notebook    | [618cd9dd90](https://linux-hardware.org/?probe=618cd9dd90) | Sep 29, 2023 |
| ASUSTek       | X505BA                      | Notebook    | [1caa3c5c7e](https://linux-hardware.org/?probe=1caa3c5c7e) | Sep 28, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [cf0c9cc177](https://linux-hardware.org/?probe=cf0c9cc177) | Sep 28, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [0c9b2c687a](https://linux-hardware.org/?probe=0c9b2c687a) | Sep 28, 2023 |
| ASUSTek       | X555LN                      | Notebook    | [773691291a](https://linux-hardware.org/?probe=773691291a) | Sep 28, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [243f89703d](https://linux-hardware.org/?probe=243f89703d) | Sep 26, 2023 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [8142da7d40](https://linux-hardware.org/?probe=8142da7d40) | Sep 25, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [fee2fdb49a](https://linux-hardware.org/?probe=fee2fdb49a) | Sep 25, 2023 |
| Huanan        | X99-TF V1.1                 | Desktop     | [694b4ab1f2](https://linux-hardware.org/?probe=694b4ab1f2) | Sep 24, 2023 |
| ASUSTek       | G750JX                      | Notebook    | [dc6cea804c](https://linux-hardware.org/?probe=dc6cea804c) | Sep 24, 2023 |
| ASUSTek       | X541UAK                     | Notebook    | [b063bf9f1e](https://linux-hardware.org/?probe=b063bf9f1e) | Sep 24, 2023 |
| ASUSTek       | X542UN                      | Notebook    | [76f91b9954](https://linux-hardware.org/?probe=76f91b9954) | Sep 24, 2023 |
| HP            | 2B2C                        | Desktop     | [79ccf62c55](https://linux-hardware.org/?probe=79ccf62c55) | Sep 23, 2023 |
| Lenovo        | ThinkPad T440 20B6006DUS    | Notebook    | [4428a91f65](https://linux-hardware.org/?probe=4428a91f65) | Sep 23, 2023 |
| ASRock        | A300M-STX                   | Desktop     | [2fc60c03c3](https://linux-hardware.org/?probe=2fc60c03c3) | Sep 22, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [fc49b16c1c](https://linux-hardware.org/?probe=fc49b16c1c) | Sep 22, 2023 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [ee0a21be07](https://linux-hardware.org/?probe=ee0a21be07) | Sep 21, 2023 |
| Apple         | MacBookPro9,1               | Notebook    | [27f3ee04f8](https://linux-hardware.org/?probe=27f3ee04f8) | Sep 21, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [5e059c90e1](https://linux-hardware.org/?probe=5e059c90e1) | Sep 21, 2023 |
| ASUSTek       | GL503VMF                    | Notebook    | [0e43a1da82](https://linux-hardware.org/?probe=0e43a1da82) | Sep 21, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [c1ca0a1d1c](https://linux-hardware.org/?probe=c1ca0a1d1c) | Sep 19, 2023 |
| ECS           | H61H2-M2                    | Desktop     | [fe16b7a5a1](https://linux-hardware.org/?probe=fe16b7a5a1) | Sep 19, 2023 |
| Intel         | NUC13SBBi9 M58736-303       | Mini pc     | [a2a7eacfe6](https://linux-hardware.org/?probe=a2a7eacfe6) | Sep 18, 2023 |
| Lenovo        | IdeaPad N585 20179          | Notebook    | [e80d14f9e4](https://linux-hardware.org/?probe=e80d14f9e4) | Sep 18, 2023 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [8368825071](https://linux-hardware.org/?probe=8368825071) | Sep 17, 2023 |
| Dell          | 0T568R A00                  | Desktop     | [675cec7d95](https://linux-hardware.org/?probe=675cec7d95) | Sep 17, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [eb2fcff0f3](https://linux-hardware.org/?probe=eb2fcff0f3) | Sep 16, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [c95eedf70e](https://linux-hardware.org/?probe=c95eedf70e) | Sep 16, 2023 |
| Acer          | Aspire 5742                 | Notebook    | [603e2a55fb](https://linux-hardware.org/?probe=603e2a55fb) | Sep 15, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Desktop     | [966d90cbc8](https://linux-hardware.org/?probe=966d90cbc8) | Sep 14, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [04bf6410bd](https://linux-hardware.org/?probe=04bf6410bd) | Sep 14, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [0c62999a52](https://linux-hardware.org/?probe=0c62999a52) | Sep 14, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [cad3ce176d](https://linux-hardware.org/?probe=cad3ce176d) | Sep 14, 2023 |
| Huanan        | X99-TF V1.1                 | Desktop     | [a5acc6026f](https://linux-hardware.org/?probe=a5acc6026f) | Sep 14, 2023 |
| ASUSTek       | UX305FA                     | Notebook    | [e4ade39a1c](https://linux-hardware.org/?probe=e4ade39a1c) | Sep 14, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [a68551130a](https://linux-hardware.org/?probe=a68551130a) | Sep 13, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [3edc89267d](https://linux-hardware.org/?probe=3edc89267d) | Sep 13, 2023 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [82125c27c9](https://linux-hardware.org/?probe=82125c27c9) | Sep 12, 2023 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | Notebook    | [e793b9e3d9](https://linux-hardware.org/?probe=e793b9e3d9) | Sep 12, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [79d77d78be](https://linux-hardware.org/?probe=79d77d78be) | Sep 12, 2023 |
| MSI           | GE62 7RD                    | Notebook    | [ff590de77d](https://linux-hardware.org/?probe=ff590de77d) | Sep 11, 2023 |
| ASUSTek       | X510UAR                     | Notebook    | [671415f9ca](https://linux-hardware.org/?probe=671415f9ca) | Sep 11, 2023 |
| Gigabyte      | Z790 UD                     | Desktop     | [bcfc38f6da](https://linux-hardware.org/?probe=bcfc38f6da) | Sep 11, 2023 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [86f844f512](https://linux-hardware.org/?probe=86f844f512) | Sep 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [1ff3e228da](https://linux-hardware.org/?probe=1ff3e228da) | Sep 10, 2023 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [3bc292a4ce](https://linux-hardware.org/?probe=3bc292a4ce) | Sep 10, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [75ca1d0c52](https://linux-hardware.org/?probe=75ca1d0c52) | Sep 10, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [f01636c129](https://linux-hardware.org/?probe=f01636c129) | Sep 09, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [83b997b3ab](https://linux-hardware.org/?probe=83b997b3ab) | Sep 09, 2023 |
| Pegatron      | 2AB6                        | Desktop     | [5b2fda7ad6](https://linux-hardware.org/?probe=5b2fda7ad6) | Sep 09, 2023 |
| HP            | 2B18                        | Desktop     | [9c8753a19e](https://linux-hardware.org/?probe=9c8753a19e) | Sep 09, 2023 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [edb578f198](https://linux-hardware.org/?probe=edb578f198) | Sep 09, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [bb02ef5cc7](https://linux-hardware.org/?probe=bb02ef5cc7) | Sep 08, 2023 |
| Google        | Pirika                      | Notebook    | [fc27e22f1c](https://linux-hardware.org/?probe=fc27e22f1c) | Sep 08, 2023 |
| Dell          | Inspiron 7460               | Notebook    | [03726302da](https://linux-hardware.org/?probe=03726302da) | Sep 07, 2023 |
| HP            | 2B3C                        | Desktop     | [471f0f283b](https://linux-hardware.org/?probe=471f0f283b) | Sep 06, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [55c623e23d](https://linux-hardware.org/?probe=55c623e23d) | Sep 06, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [db0c457b51](https://linux-hardware.org/?probe=db0c457b51) | Sep 06, 2023 |
| HP            | ProBook 455 15.6 inch G9... | Notebook    | [5b7ab92e89](https://linux-hardware.org/?probe=5b7ab92e89) | Sep 06, 2023 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | Desktop     | [b1329d0cc1](https://linux-hardware.org/?probe=b1329d0cc1) | Sep 05, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [7263435dde](https://linux-hardware.org/?probe=7263435dde) | Sep 05, 2023 |
| Acer          | Aspire 5742                 | Notebook    | [ff917b0920](https://linux-hardware.org/?probe=ff917b0920) | Sep 02, 2023 |
| HUAWEI        | HN-WX9X                     | Notebook    | [efd67d7c17](https://linux-hardware.org/?probe=efd67d7c17) | Sep 02, 2023 |
| Dell          | Latitude 5420               | Notebook    | [2acb1da32c](https://linux-hardware.org/?probe=2acb1da32c) | Sep 02, 2023 |
| ASUSTek       | PRIME X299-A II             | Desktop     | [80a93a9457](https://linux-hardware.org/?probe=80a93a9457) | Sep 02, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [9de67aa419](https://linux-hardware.org/?probe=9de67aa419) | Sep 01, 2023 |
| HP            | 18E9                        | Desktop     | [fd1f6decb2](https://linux-hardware.org/?probe=fd1f6decb2) | Sep 01, 2023 |
| Dell          | G15 5530                    | Notebook    | [ababfa6c5e](https://linux-hardware.org/?probe=ababfa6c5e) | Aug 31, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [92552fa038](https://linux-hardware.org/?probe=92552fa038) | Aug 30, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [75ef08524c](https://linux-hardware.org/?probe=75ef08524c) | Aug 30, 2023 |
| Dell          | Latitude E6520              | Notebook    | [4918e66ad8](https://linux-hardware.org/?probe=4918e66ad8) | Aug 29, 2023 |
| MSI           | Z97 GAMING 7                | Desktop     | [ea78ba2d46](https://linux-hardware.org/?probe=ea78ba2d46) | Aug 29, 2023 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [176ad353fa](https://linux-hardware.org/?probe=176ad353fa) | Aug 29, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [fc7834595f](https://linux-hardware.org/?probe=fc7834595f) | Aug 29, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | Desktop     | [5b896ea45c](https://linux-hardware.org/?probe=5b896ea45c) | Aug 29, 2023 |
| Acer          | Aspire V5-471               | Notebook    | [c5d2dabe27](https://linux-hardware.org/?probe=c5d2dabe27) | Aug 28, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [6b6ec006aa](https://linux-hardware.org/?probe=6b6ec006aa) | Aug 28, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [cc89933ff1](https://linux-hardware.org/?probe=cc89933ff1) | Aug 28, 2023 |
| Intel         | NUC11PABi7 K90104-302       | Mini pc     | [ee8ee6bf06](https://linux-hardware.org/?probe=ee8ee6bf06) | Aug 28, 2023 |
| ASUSTek       | PRIME H510M-R               | Desktop     | [c6614846b5](https://linux-hardware.org/?probe=c6614846b5) | Aug 28, 2023 |
| HP            | 2B18                        | Desktop     | [891ce74167](https://linux-hardware.org/?probe=891ce74167) | Aug 27, 2023 |
| Dell          | 06X1TJ A00                  | Desktop     | [450512bee1](https://linux-hardware.org/?probe=450512bee1) | Aug 27, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [7423f83594](https://linux-hardware.org/?probe=7423f83594) | Aug 27, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [dd4626de1b](https://linux-hardware.org/?probe=dd4626de1b) | Aug 27, 2023 |
| Gigabyte      | Z370M DS3H-CF               | Desktop     | [6ae200367f](https://linux-hardware.org/?probe=6ae200367f) | Aug 27, 2023 |
| Gigabyte      | Z490 GAMING X               | Desktop     | [ee07c69165](https://linux-hardware.org/?probe=ee07c69165) | Aug 27, 2023 |
| Timi          | Redmi Book Pro 14 2022      | Notebook    | [8f85c500ec](https://linux-hardware.org/?probe=8f85c500ec) | Aug 27, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [17a7fc84be](https://linux-hardware.org/?probe=17a7fc84be) | Aug 26, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Desktop     | [d4cf1916d2](https://linux-hardware.org/?probe=d4cf1916d2) | Aug 26, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [211472aacc](https://linux-hardware.org/?probe=211472aacc) | Aug 26, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [16790cbb5f](https://linux-hardware.org/?probe=16790cbb5f) | Aug 26, 2023 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [0c46e2d419](https://linux-hardware.org/?probe=0c46e2d419) | Aug 26, 2023 |
| HP            | Laptop 15-da2xxx            | Notebook    | [01636af413](https://linux-hardware.org/?probe=01636af413) | Aug 25, 2023 |
| BESSTAR Te... | UM700                       | Desktop     | [bca12d1c12](https://linux-hardware.org/?probe=bca12d1c12) | Aug 24, 2023 |
| Gigabyte      | Z790 AORUS MASTER           | Desktop     | [202017a190](https://linux-hardware.org/?probe=202017a190) | Aug 23, 2023 |
| Google        | Pirika                      | Notebook    | [f0937aba65](https://linux-hardware.org/?probe=f0937aba65) | Aug 23, 2023 |
| Lenovo        | ThinkPad P50 20EQS4XN00     | Notebook    | [a517cc57b8](https://linux-hardware.org/?probe=a517cc57b8) | Aug 23, 2023 |
| VIT           | P2402                       | Notebook    | [fa87ae71d4](https://linux-hardware.org/?probe=fa87ae71d4) | Aug 22, 2023 |
| VIT           | P2402                       | Notebook    | [7b83628f3c](https://linux-hardware.org/?probe=7b83628f3c) | Aug 22, 2023 |
| ASUSTek       | X510UAR                     | Notebook    | [cdef569014](https://linux-hardware.org/?probe=cdef569014) | Aug 22, 2023 |
| Win Elemen... | M9                          | Desktop     | [f161447dfc](https://linux-hardware.org/?probe=f161447dfc) | Aug 22, 2023 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [e00521ec88](https://linux-hardware.org/?probe=e00521ec88) | Aug 22, 2023 |
| Acer          | Predator PO3-630            | Desktop     | [b7c9c3e0c4](https://linux-hardware.org/?probe=b7c9c3e0c4) | Aug 22, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [d63bd363bc](https://linux-hardware.org/?probe=d63bd363bc) | Aug 22, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [882234a7b8](https://linux-hardware.org/?probe=882234a7b8) | Aug 22, 2023 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [5a9badb376](https://linux-hardware.org/?probe=5a9badb376) | Aug 22, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [ee47d4b6a7](https://linux-hardware.org/?probe=ee47d4b6a7) | Aug 20, 2023 |
| HONOR         | BBR-WAX9                    | Notebook    | [1d013fbf4b](https://linux-hardware.org/?probe=1d013fbf4b) | Aug 20, 2023 |
| Lenovo        | Yoga 920-13IKB 80Y7         | Convertible | [4456ccbc85](https://linux-hardware.org/?probe=4456ccbc85) | Aug 20, 2023 |
| MSI           | MEG Z390 ACE                | Desktop     | [5ab219fbd1](https://linux-hardware.org/?probe=5ab219fbd1) | Aug 20, 2023 |
| MSI           | H270M BAZOOKA               | Desktop     | [f51f1ce129](https://linux-hardware.org/?probe=f51f1ce129) | Aug 19, 2023 |
| Lenovo        | Rev B 82KU                  | Notebook    | [114345f952](https://linux-hardware.org/?probe=114345f952) | Aug 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [faaba537ca](https://linux-hardware.org/?probe=faaba537ca) | Aug 18, 2023 |
| MSI           | Z87 MPOWER MAX              | Desktop     | [6bda9908df](https://linux-hardware.org/?probe=6bda9908df) | Aug 16, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [d7ec063f46](https://linux-hardware.org/?probe=d7ec063f46) | Aug 16, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [11dafc79e8](https://linux-hardware.org/?probe=11dafc79e8) | Aug 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [c078e667a4](https://linux-hardware.org/?probe=c078e667a4) | Aug 15, 2023 |
| Sony          | VAIO                        | All in one  | [a134fd35ac](https://linux-hardware.org/?probe=a134fd35ac) | Aug 13, 2023 |
| MSI           | 760GM-P33                   | Desktop     | [878209b83a](https://linux-hardware.org/?probe=878209b83a) | Aug 13, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [1c643cc90f](https://linux-hardware.org/?probe=1c643cc90f) | Aug 13, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [551d8f3fc8](https://linux-hardware.org/?probe=551d8f3fc8) | Aug 13, 2023 |
| Fujitsu       | LIFEBOOK A3510              | Notebook    | [3e830ffabc](https://linux-hardware.org/?probe=3e830ffabc) | Aug 12, 2023 |
| Dell          | G3 3590                     | Notebook    | [084d659110](https://linux-hardware.org/?probe=084d659110) | Aug 11, 2023 |
| LNV           | L40-70                      | Notebook    | [66fe107447](https://linux-hardware.org/?probe=66fe107447) | Aug 11, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [93a61b62a5](https://linux-hardware.org/?probe=93a61b62a5) | Aug 11, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [eee160a070](https://linux-hardware.org/?probe=eee160a070) | Aug 10, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [284cfb0f6d](https://linux-hardware.org/?probe=284cfb0f6d) | Aug 08, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [c9c978701a](https://linux-hardware.org/?probe=c9c978701a) | Aug 08, 2023 |
| ASUSTek       | PRIME H510M-R               | Desktop     | [38ab435feb](https://linux-hardware.org/?probe=38ab435feb) | Aug 08, 2023 |
| MSI           | B350 GAMING PLUS            | Desktop     | [951597859a](https://linux-hardware.org/?probe=951597859a) | Aug 08, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [e642e8e489](https://linux-hardware.org/?probe=e642e8e489) | Aug 08, 2023 |
| Sony          | VAIO                        | All in one  | [e924df8ac8](https://linux-hardware.org/?probe=e924df8ac8) | Aug 07, 2023 |
| Sony          | VAIO                        | All in one  | [8349b185e4](https://linux-hardware.org/?probe=8349b185e4) | Aug 07, 2023 |
| ECS           | H61H2-CM                    | Desktop     | [e2b9ff65d7](https://linux-hardware.org/?probe=e2b9ff65d7) | Aug 06, 2023 |
| WEIGO         | CDA-141AU                   | Notebook    | [35c705bd70](https://linux-hardware.org/?probe=35c705bd70) | Aug 05, 2023 |
| Dell          | Inspiron 3558               | Notebook    | [5331913f13](https://linux-hardware.org/?probe=5331913f13) | Aug 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [8b84e48f4c](https://linux-hardware.org/?probe=8b84e48f4c) | Aug 04, 2023 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [6dbeaa5f27](https://linux-hardware.org/?probe=6dbeaa5f27) | Aug 04, 2023 |
| Acer          | Aspire V3-371               | Notebook    | [5d5a4b489b](https://linux-hardware.org/?probe=5d5a4b489b) | Aug 03, 2023 |
| ASRock        | Z77 Professional            | Desktop     | [2f0bc369b4](https://linux-hardware.org/?probe=2f0bc369b4) | Aug 03, 2023 |
| Fujitsu       | LIFEBOOK A3510              | Notebook    | [7281304bf0](https://linux-hardware.org/?probe=7281304bf0) | Aug 02, 2023 |
| Dell          | G3 3590                     | Notebook    | [78aeeb1aa3](https://linux-hardware.org/?probe=78aeeb1aa3) | Aug 02, 2023 |
| Dell          | G3 3590                     | Notebook    | [47d3c9b9fe](https://linux-hardware.org/?probe=47d3c9b9fe) | Aug 02, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [b0d7ab05f0](https://linux-hardware.org/?probe=b0d7ab05f0) | Aug 02, 2023 |
| AZW           | SER                         | Mini pc     | [de1abb2584](https://linux-hardware.org/?probe=de1abb2584) | Aug 02, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [39216c08ff](https://linux-hardware.org/?probe=39216c08ff) | Aug 01, 2023 |
| Microsoft     | Surface Pro 6               | Tablet      | [70a56ad26d](https://linux-hardware.org/?probe=70a56ad26d) | Aug 01, 2023 |
| Gigabyte      | Z490 GAMING X               | Desktop     | [f710ad8b96](https://linux-hardware.org/?probe=f710ad8b96) | Jul 31, 2023 |
| Lenovo        | ThinkPad T480 20L6S2CE00    | Notebook    | [eb14620792](https://linux-hardware.org/?probe=eb14620792) | Jul 30, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [2c6149347b](https://linux-hardware.org/?probe=2c6149347b) | Jul 30, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [20d5d0a3ad](https://linux-hardware.org/?probe=20d5d0a3ad) | Jul 30, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [3fb2cba3db](https://linux-hardware.org/?probe=3fb2cba3db) | Jul 29, 2023 |
| HP            | 82DD 0001                   | All in one  | [e6da7743f0](https://linux-hardware.org/?probe=e6da7743f0) | Jul 28, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [37440e19b5](https://linux-hardware.org/?probe=37440e19b5) | Jul 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [a467ce5440](https://linux-hardware.org/?probe=a467ce5440) | Jul 28, 2023 |
| Acer          | Aspire A315-42              | Notebook    | [3afa5a3034](https://linux-hardware.org/?probe=3afa5a3034) | Jul 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [dc632de3b5](https://linux-hardware.org/?probe=dc632de3b5) | Jul 27, 2023 |
| HP            | Laptop 14-fq1xxx            | Notebook    | [5de59d7736](https://linux-hardware.org/?probe=5de59d7736) | Jul 27, 2023 |
| Apple         | MacBook7,1                  | Notebook    | [762861205a](https://linux-hardware.org/?probe=762861205a) | Jul 26, 2023 |
| Intel         | B75                         | Desktop     | [492fa4fc25](https://linux-hardware.org/?probe=492fa4fc25) | Jul 26, 2023 |
| Lenovo        | ThinkCentre M58 3231W2Y     | Desktop     | [72f09cd320](https://linux-hardware.org/?probe=72f09cd320) | Jul 26, 2023 |
| Lenovo        | ThinkPad T470p 20J6003DG... | Notebook    | [5693ac5e4c](https://linux-hardware.org/?probe=5693ac5e4c) | Jul 25, 2023 |
| ASUSTek       | ROG Flow X13 GV301RC_GV3... | Convertible | [676bfc8484](https://linux-hardware.org/?probe=676bfc8484) | Jul 25, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [032db75736](https://linux-hardware.org/?probe=032db75736) | Jul 23, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [f5174240a7](https://linux-hardware.org/?probe=f5174240a7) | Jul 23, 2023 |
| Dell          | Inspiron 3476               | Notebook    | [eb12521a96](https://linux-hardware.org/?probe=eb12521a96) | Jul 23, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [c95c0b0730](https://linux-hardware.org/?probe=c95c0b0730) | Jul 22, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [96f5f9ffdc](https://linux-hardware.org/?probe=96f5f9ffdc) | Jul 19, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [c10ecff0f6](https://linux-hardware.org/?probe=c10ecff0f6) | Jul 19, 2023 |
| ASUSTek       | PRIME X299-A II             | Desktop     | [54f9bd2050](https://linux-hardware.org/?probe=54f9bd2050) | Jul 18, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [d688be2c92](https://linux-hardware.org/?probe=d688be2c92) | Jul 18, 2023 |
| Gigabyte      | Z490 GAMING X               | Desktop     | [866bc45d05](https://linux-hardware.org/?probe=866bc45d05) | Jul 18, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [4c8b8b5a8a](https://linux-hardware.org/?probe=4c8b8b5a8a) | Jul 18, 2023 |
| ASUSTek       | TUF Z270 MARK 2             | Desktop     | [d23b7166b1](https://linux-hardware.org/?probe=d23b7166b1) | Jul 18, 2023 |
| Lenovo        | ThinkPad T420 4236C92       | Notebook    | [a7b56f640a](https://linux-hardware.org/?probe=a7b56f640a) | Jul 18, 2023 |
| Gigabyte      | Z490 GAMING X               | Desktop     | [3c5ef629e4](https://linux-hardware.org/?probe=3c5ef629e4) | Jul 18, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [4d00148664](https://linux-hardware.org/?probe=4d00148664) | Jul 16, 2023 |
| Lenovo        | ThinkPad T480 20L6S2CE00    | Notebook    | [e88c64ac3c](https://linux-hardware.org/?probe=e88c64ac3c) | Jul 16, 2023 |
| Gigabyte      | X399 AORUS XTREME-CF        | Desktop     | [59bf614ae2](https://linux-hardware.org/?probe=59bf614ae2) | Jul 14, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [9ec51bc7eb](https://linux-hardware.org/?probe=9ec51bc7eb) | Jul 14, 2023 |
| Lenovo        | ThinkPad T450 20BUS1BW01    | Notebook    | [db28c39c19](https://linux-hardware.org/?probe=db28c39c19) | Jul 14, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [75d40e5a2b](https://linux-hardware.org/?probe=75d40e5a2b) | Jul 14, 2023 |
| Intel         | NUC7i5BNB J31144-305        | Mini pc     | [d477369e7e](https://linux-hardware.org/?probe=d477369e7e) | Jul 14, 2023 |
| Lenovo        | ThinkPad T460s 20F90057M... | Notebook    | [698c4a8958](https://linux-hardware.org/?probe=698c4a8958) | Jul 14, 2023 |
| ASUSTek       | GL553VW                     | Notebook    | [9946c63986](https://linux-hardware.org/?probe=9946c63986) | Jul 12, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [06f4243bee](https://linux-hardware.org/?probe=06f4243bee) | Jul 12, 2023 |
| Lenovo        | ThinkPad T450 20BUS1BW01    | Notebook    | [91d748c376](https://linux-hardware.org/?probe=91d748c376) | Jul 11, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [995e13dee9](https://linux-hardware.org/?probe=995e13dee9) | Jul 11, 2023 |
| Lenovo        | ThinkPad P72 20MCS0EU00     | Notebook    | [394bdbc596](https://linux-hardware.org/?probe=394bdbc596) | Jul 11, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [a5d9143c99](https://linux-hardware.org/?probe=a5d9143c99) | Jul 10, 2023 |
| Lenovo        | ThinkPad T480 20L6S2CE00    | Notebook    | [bbc78272ea](https://linux-hardware.org/?probe=bbc78272ea) | Jul 10, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [b5ddf3381c](https://linux-hardware.org/?probe=b5ddf3381c) | Jul 10, 2023 |
| Lenovo        | ThinkPad T470p 20J6003DG... | Notebook    | [a7632f8c4b](https://linux-hardware.org/?probe=a7632f8c4b) | Jul 09, 2023 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [8fcda3580f](https://linux-hardware.org/?probe=8fcda3580f) | Jul 08, 2023 |
| Alienware     | 17                          | Notebook    | [b8b8032da9](https://linux-hardware.org/?probe=b8b8032da9) | Jul 08, 2023 |
| Lenovo        | ThinkPad T460s 20F90057M... | Notebook    | [cd45163d47](https://linux-hardware.org/?probe=cd45163d47) | Jul 08, 2023 |
| Gigabyte      | Z490 GAMING X               | Desktop     | [27e600a93b](https://linux-hardware.org/?probe=27e600a93b) | Jul 07, 2023 |
| Dell          | Latitude 7480               | Notebook    | [4c07c7b04a](https://linux-hardware.org/?probe=4c07c7b04a) | Jul 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [b23ba37244](https://linux-hardware.org/?probe=b23ba37244) | Jul 06, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [d25474786c](https://linux-hardware.org/?probe=d25474786c) | Jul 05, 2023 |
| Acer          | TravelMate 8572T            | Notebook    | [67f4a2af7e](https://linux-hardware.org/?probe=67f4a2af7e) | Jul 05, 2023 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [c945bae843](https://linux-hardware.org/?probe=c945bae843) | Jul 05, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [ca637a5884](https://linux-hardware.org/?probe=ca637a5884) | Jul 05, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [407e00921f](https://linux-hardware.org/?probe=407e00921f) | Jul 04, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [fc70411ea4](https://linux-hardware.org/?probe=fc70411ea4) | Jul 03, 2023 |
| Gigabyte      | Z490 GAMING X               | Desktop     | [107fe61a53](https://linux-hardware.org/?probe=107fe61a53) | Jul 02, 2023 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [7fee63007e](https://linux-hardware.org/?probe=7fee63007e) | Jul 02, 2023 |
| Acer          | Aspire 7715Z                | Notebook    | [b288a09d6e](https://linux-hardware.org/?probe=b288a09d6e) | Jul 01, 2023 |
| Lenovo        | ThinkPad T460s 20F90057M... | Notebook    | [a78e2b4096](https://linux-hardware.org/?probe=a78e2b4096) | Jun 29, 2023 |
| Medion        | Akoya P7818                 | Notebook    | [cfe9ae82fa](https://linux-hardware.org/?probe=cfe9ae82fa) | Jun 29, 2023 |
| ASUSTek       | H110M-A                     | Desktop     | [c3118a3d89](https://linux-hardware.org/?probe=c3118a3d89) | Jun 29, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [895760e7db](https://linux-hardware.org/?probe=895760e7db) | Jun 27, 2023 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [fa162784e0](https://linux-hardware.org/?probe=fa162784e0) | Jun 24, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [b67f86bedc](https://linux-hardware.org/?probe=b67f86bedc) | Jun 21, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [5314aeb7e0](https://linux-hardware.org/?probe=5314aeb7e0) | Jun 21, 2023 |
| MSI           | Z77A-G41                    | Desktop     | [e7e4924bda](https://linux-hardware.org/?probe=e7e4924bda) | Jun 20, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [284344e775](https://linux-hardware.org/?probe=284344e775) | Jun 14, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [859f1b3a88](https://linux-hardware.org/?probe=859f1b3a88) | Jun 13, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [95bc101c80](https://linux-hardware.org/?probe=95bc101c80) | Jun 09, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [277ddf45b4](https://linux-hardware.org/?probe=277ddf45b4) | Jun 08, 2023 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [1d8b78cbdc](https://linux-hardware.org/?probe=1d8b78cbdc) | May 29, 2023 |
| Acer          | Aspire E1-572               | Notebook    | [6dc6a9d6f5](https://linux-hardware.org/?probe=6dc6a9d6f5) | May 29, 2023 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [2cdf1c9e61](https://linux-hardware.org/?probe=2cdf1c9e61) | May 23, 2023 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [cca41e18cb](https://linux-hardware.org/?probe=cca41e18cb) | May 23, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [89d6a4edd2](https://linux-hardware.org/?probe=89d6a4edd2) | May 13, 2023 |
| Lenovo        | Yoga 730-15IKB 81CU         | Convertible | [5cfbeb30e0](https://linux-hardware.org/?probe=5cfbeb30e0) | May 10, 2023 |
| Unknown       | Intel X79                   | Desktop     | [6b1ddbd923](https://linux-hardware.org/?probe=6b1ddbd923) | May 03, 2023 |
| Biostar       | H110MHV3                    | Desktop     | [95b25ba480](https://linux-hardware.org/?probe=95b25ba480) | Apr 29, 2023 |
| Samsung       | 950QED                      | Convertible | [f2568c7949](https://linux-hardware.org/?probe=f2568c7949) | Apr 07, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [ba6e80b2b7](https://linux-hardware.org/?probe=ba6e80b2b7) | Apr 02, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [195ab3d907](https://linux-hardware.org/?probe=195ab3d907) | Apr 02, 2023 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [520ad2ca86](https://linux-hardware.org/?probe=520ad2ca86) | Mar 31, 2023 |
| Lenovo        | ThinkPad T440 20B7A0CYMH    | Notebook    | [428491a9d5](https://linux-hardware.org/?probe=428491a9d5) | Mar 29, 2023 |
| HP            | 8437                        | Desktop     | [cdc32d8d8b](https://linux-hardware.org/?probe=cdc32d8d8b) | Mar 25, 2023 |
| HP            | 8437                        | Desktop     | [6fbb459a03](https://linux-hardware.org/?probe=6fbb459a03) | Mar 25, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [f8cd7d94b2](https://linux-hardware.org/?probe=f8cd7d94b2) | Mar 23, 2023 |
| Dell          | G5 5500                     | Notebook    | [f9b3b5d852](https://linux-hardware.org/?probe=f9b3b5d852) | Mar 19, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [90ef6ca2b7](https://linux-hardware.org/?probe=90ef6ca2b7) | Mar 18, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [b769745990](https://linux-hardware.org/?probe=b769745990) | Mar 18, 2023 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [5d307f2d26](https://linux-hardware.org/?probe=5d307f2d26) | Mar 18, 2023 |
| Dell          | Latitude 5420               | Notebook    | [318da7f6c0](https://linux-hardware.org/?probe=318da7f6c0) | Mar 18, 2023 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [d1bf2f0a8b](https://linux-hardware.org/?probe=d1bf2f0a8b) | Mar 12, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [bccc889328](https://linux-hardware.org/?probe=bccc889328) | Mar 10, 2023 |
| Lenovo        | ThinkPad P51 20HJS11Y00     | Notebook    | [0843074b87](https://linux-hardware.org/?probe=0843074b87) | Mar 09, 2023 |
| Lenovo        | IdeaPad S540-15IML D 81N... | Notebook    | [31e144de96](https://linux-hardware.org/?probe=31e144de96) | Mar 08, 2023 |
| Acer          | Aspire GX-281               | Desktop     | [d318df6931](https://linux-hardware.org/?probe=d318df6931) | Mar 04, 2023 |
| JINGSHA       | Unknown                     | Desktop     | [c8bd846b63](https://linux-hardware.org/?probe=c8bd846b63) | Feb 26, 2023 |
| Dell          | 0G3HR7 A00                  | Desktop     | [33723c8b80](https://linux-hardware.org/?probe=33723c8b80) | Feb 25, 2023 |
| Dell          | Inspiron 3505               | Notebook    | [324020ca8b](https://linux-hardware.org/?probe=324020ca8b) | Feb 24, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [503fe663b4](https://linux-hardware.org/?probe=503fe663b4) | Feb 20, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [d76b048134](https://linux-hardware.org/?probe=d76b048134) | Feb 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [efd9f878d2](https://linux-hardware.org/?probe=efd9f878d2) | Feb 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [3c2d4cf289](https://linux-hardware.org/?probe=3c2d4cf289) | Feb 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [0de8121880](https://linux-hardware.org/?probe=0de8121880) | Feb 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [f39ab69b74](https://linux-hardware.org/?probe=f39ab69b74) | Feb 01, 2023 |
| HP            | ProBook 6565b               | Notebook    | [0ef00f6bcc](https://linux-hardware.org/?probe=0ef00f6bcc) | Jan 25, 2023 |
| HP            | 828A                        | Desktop     | [5f430ba8d1](https://linux-hardware.org/?probe=5f430ba8d1) | Jan 19, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [5661d09dd0](https://linux-hardware.org/?probe=5661d09dd0) | Jan 15, 2023 |
| HP            | 245 G7 Notebook PC          | Notebook    | [3997d98a9a](https://linux-hardware.org/?probe=3997d98a9a) | Jan 11, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [21fcd391f1](https://linux-hardware.org/?probe=21fcd391f1) | Jan 08, 2023 |
| HP            | 86EE                        | All in one  | [1fc671302e](https://linux-hardware.org/?probe=1fc671302e) | Jan 06, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | Notebook    | [86cf09380a](https://linux-hardware.org/?probe=86cf09380a) | Jan 02, 2023 |
| Pegatron      | 2AF0                        | Desktop     | [77768feff6](https://linux-hardware.org/?probe=77768feff6) | Jan 01, 2023 |
| ASUSTek       | X540LA                      | Notebook    | [65f5548781](https://linux-hardware.org/?probe=65f5548781) | Dec 30, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [fb1d454bc2](https://linux-hardware.org/?probe=fb1d454bc2) | Dec 29, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [62010fe267](https://linux-hardware.org/?probe=62010fe267) | Dec 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6b34107dcf](https://linux-hardware.org/?probe=6b34107dcf) | Dec 21, 2022 |
| HP            | ZBook 15 G4                 | Notebook    | [669d7e74a2](https://linux-hardware.org/?probe=669d7e74a2) | Dec 19, 2022 |
| HP            | ZBook 15 G4                 | Notebook    | [91391127d1](https://linux-hardware.org/?probe=91391127d1) | Dec 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3111a63a09](https://linux-hardware.org/?probe=3111a63a09) | Dec 16, 2022 |
| Lenovo        | ThinkPad T490s 20NX001KM... | Notebook    | [49f30d3eee](https://linux-hardware.org/?probe=49f30d3eee) | Dec 06, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [16f086de33](https://linux-hardware.org/?probe=16f086de33) | Nov 25, 2022 |
| Medion        | P6816                       | Notebook    | [3aadacefe7](https://linux-hardware.org/?probe=3aadacefe7) | Nov 17, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [f074ef2e7c](https://linux-hardware.org/?probe=f074ef2e7c) | Nov 15, 2022 |
| Dell          | Latitude E6530              | Notebook    | [c87c9abe22](https://linux-hardware.org/?probe=c87c9abe22) | Nov 14, 2022 |
| Toshiba       | TECRA A11                   | Notebook    | [ba91b9d331](https://linux-hardware.org/?probe=ba91b9d331) | Nov 09, 2022 |
| Lenovo        | ThinkPad L450 20DT0000GE    | Notebook    | [1a925e0302](https://linux-hardware.org/?probe=1a925e0302) | Nov 06, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [711e95b72e](https://linux-hardware.org/?probe=711e95b72e) | Nov 02, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [ff0c19c661](https://linux-hardware.org/?probe=ff0c19c661) | Nov 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [4cd7aa6350](https://linux-hardware.org/?probe=4cd7aa6350) | Nov 01, 2022 |
| ASUSTek       | K53SJ                       | Notebook    | [8c85e545f2](https://linux-hardware.org/?probe=8c85e545f2) | Oct 23, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [bcf4fa1baf](https://linux-hardware.org/?probe=bcf4fa1baf) | Oct 18, 2022 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [07b256f333](https://linux-hardware.org/?probe=07b256f333) | Oct 17, 2022 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [fc1ec464bf](https://linux-hardware.org/?probe=fc1ec464bf) | Oct 17, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [bf0e112f9a](https://linux-hardware.org/?probe=bf0e112f9a) | Oct 16, 2022 |
| ASUSTek       | PRIME B250-PLUS             | Desktop     | [00ab764924](https://linux-hardware.org/?probe=00ab764924) | Oct 15, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [e037086b30](https://linux-hardware.org/?probe=e037086b30) | Oct 14, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [ef1974cfc8](https://linux-hardware.org/?probe=ef1974cfc8) | Oct 10, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [69e60dfe44](https://linux-hardware.org/?probe=69e60dfe44) | Oct 07, 2022 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [a11de13c4f](https://linux-hardware.org/?probe=a11de13c4f) | Oct 04, 2022 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [6de76ddb0e](https://linux-hardware.org/?probe=6de76ddb0e) | Oct 04, 2022 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | Notebook    | [a7764ad0f6](https://linux-hardware.org/?probe=a7764ad0f6) | Oct 03, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [9931b35717](https://linux-hardware.org/?probe=9931b35717) | Sep 24, 2022 |
| MSI           | Katana GF66 11UE            | Notebook    | [36b2cba297](https://linux-hardware.org/?probe=36b2cba297) | Sep 05, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [b28edd3886](https://linux-hardware.org/?probe=b28edd3886) | Aug 26, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [97770c5716](https://linux-hardware.org/?probe=97770c5716) | Aug 26, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [4c95b1bccf](https://linux-hardware.org/?probe=4c95b1bccf) | Aug 22, 2022 |
| Lenovo        | ThinkPad T430s 2356FG9      | Notebook    | [9a10c152af](https://linux-hardware.org/?probe=9a10c152af) | Aug 17, 2022 |
| Aquarius      | NS585                       | Notebook    | [db9cbd5688](https://linux-hardware.org/?probe=db9cbd5688) | Aug 17, 2022 |
| Gigabyte      | B460M DS3H V2               | Desktop     | [2522ff1530](https://linux-hardware.org/?probe=2522ff1530) | Aug 13, 2022 |
| ASUSTek       | P7P55 LX                    | Desktop     | [8211ccc6cc](https://linux-hardware.org/?probe=8211ccc6cc) | Aug 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [b73e5f9cbf](https://linux-hardware.org/?probe=b73e5f9cbf) | Aug 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [f483092edf](https://linux-hardware.org/?probe=f483092edf) | Aug 07, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a0507fae02](https://linux-hardware.org/?probe=a0507fae02) | Jul 31, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [7c46c8f737](https://linux-hardware.org/?probe=7c46c8f737) | Jul 15, 2022 |
| ASUSTek       | G551JM                      | Notebook    | [599c7b9eae](https://linux-hardware.org/?probe=599c7b9eae) | Jul 14, 2022 |
| ASUSTek       | G551JM                      | Notebook    | [9f4536df1c](https://linux-hardware.org/?probe=9f4536df1c) | Jul 14, 2022 |
| ASRock        | AB350 Pro4                  | Desktop     | [7049f819f0](https://linux-hardware.org/?probe=7049f819f0) | Jun 30, 2022 |
| HP            | 3396                        | Desktop     | [00782afa06](https://linux-hardware.org/?probe=00782afa06) | Jun 22, 2022 |
| ASUSTek       | UX303LN                     | Notebook    | [9ce42e1b01](https://linux-hardware.org/?probe=9ce42e1b01) | Jun 12, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [8109a04ffa](https://linux-hardware.org/?probe=8109a04ffa) | Jun 12, 2022 |
| BESSTAR Te... | ATB15                       | Server      | [d6e47a7c18](https://linux-hardware.org/?probe=d6e47a7c18) | Jun 12, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [8a7401e54a](https://linux-hardware.org/?probe=8a7401e54a) | Jun 11, 2022 |
| Acer          | Aspire XC-886 V:2.0         | Desktop     | [2fe8cdaf93](https://linux-hardware.org/?probe=2fe8cdaf93) | May 31, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [ce0e24a314](https://linux-hardware.org/?probe=ce0e24a314) | May 28, 2022 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [53475a6004](https://linux-hardware.org/?probe=53475a6004) | May 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [80d32848bf](https://linux-hardware.org/?probe=80d32848bf) | May 21, 2022 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [3ddad532a9](https://linux-hardware.org/?probe=3ddad532a9) | May 08, 2022 |
| Dell          | Inspiron 7786               | Convertible | [0ef12447d9](https://linux-hardware.org/?probe=0ef12447d9) | May 02, 2022 |
| Dell          | Precision M3800             | Notebook    | [7b63874768](https://linux-hardware.org/?probe=7b63874768) | Apr 25, 2022 |
| Dell          | Precision M3800             | Notebook    | [fbabacd835](https://linux-hardware.org/?probe=fbabacd835) | Apr 24, 2022 |
| Lenovo        | ThinkPad X230 2325HR9       | Notebook    | [a9d9d3fbb2](https://linux-hardware.org/?probe=a9d9d3fbb2) | Apr 21, 2022 |
| MSI           | Z170-A PRO                  | Desktop     | [db5ab86328](https://linux-hardware.org/?probe=db5ab86328) | Apr 11, 2022 |
| Acer          | Aspire A515-54G             | Notebook    | [52b660d8fb](https://linux-hardware.org/?probe=52b660d8fb) | Apr 11, 2022 |
| MSI           | Z170-A PRO                  | Desktop     | [3bd5bb8d08](https://linux-hardware.org/?probe=3bd5bb8d08) | Apr 10, 2022 |
| Dell          | Precision M3800             | Notebook    | [1ef57b39a7](https://linux-hardware.org/?probe=1ef57b39a7) | Apr 10, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [8d251b1b2a](https://linux-hardware.org/?probe=8d251b1b2a) | Apr 03, 2022 |
| Dell          | Precision M3800             | Notebook    | [9fc15d1ae6](https://linux-hardware.org/?probe=9fc15d1ae6) | Mar 31, 2022 |
| HP            | 843B                        | Desktop     | [a88ff7cf5c](https://linux-hardware.org/?probe=a88ff7cf5c) | Mar 27, 2022 |
| Pegatron      | 2AC2                        | Desktop     | [d3c82e973b](https://linux-hardware.org/?probe=d3c82e973b) | Mar 25, 2022 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [745cc1d638](https://linux-hardware.org/?probe=745cc1d638) | Mar 25, 2022 |
| MSI           | GF63 Thin 9SCX              | Notebook    | [4501fa1556](https://linux-hardware.org/?probe=4501fa1556) | Mar 25, 2022 |
| Dell          | Latitude 7480               | Notebook    | [bf00ec6a76](https://linux-hardware.org/?probe=bf00ec6a76) | Mar 23, 2022 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [8eb98db533](https://linux-hardware.org/?probe=8eb98db533) | Mar 22, 2022 |
| HUAWEI        | WRT-WX9                     | Notebook    | [70ec26bed6](https://linux-hardware.org/?probe=70ec26bed6) | Mar 22, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [13cdf54c81](https://linux-hardware.org/?probe=13cdf54c81) | Mar 21, 2022 |
| Dell          | Latitude 7480               | Notebook    | [faddba28a8](https://linux-hardware.org/?probe=faddba28a8) | Mar 19, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [b71110144d](https://linux-hardware.org/?probe=b71110144d) | Mar 19, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [bb9074ccdf](https://linux-hardware.org/?probe=bb9074ccdf) | Mar 18, 2022 |
| Lenovo        | IdeaPad 3 15IML05 81WR      | Notebook    | [918c951cd1](https://linux-hardware.org/?probe=918c951cd1) | Mar 12, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [639e7361ef](https://linux-hardware.org/?probe=639e7361ef) | Mar 12, 2022 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [e251c9f079](https://linux-hardware.org/?probe=e251c9f079) | Mar 11, 2022 |
| MSI           | Z170A PC MATE               | Desktop     | [181e014823](https://linux-hardware.org/?probe=181e014823) | Mar 08, 2022 |
| Gigabyte      | Z170X-UD3-CF                | Desktop     | [3ec7a7f643](https://linux-hardware.org/?probe=3ec7a7f643) | Mar 06, 2022 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [57b302b119](https://linux-hardware.org/?probe=57b302b119) | Mar 05, 2022 |
| Lenovo        | ThinkPad T460 20FMS1XX00    | Notebook    | [78e82c6674](https://linux-hardware.org/?probe=78e82c6674) | Feb 24, 2022 |
| Dell          | Latitude E6430              | Notebook    | [e1de4e80fe](https://linux-hardware.org/?probe=e1de4e80fe) | Feb 15, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [a3c5f00a2a](https://linux-hardware.org/?probe=a3c5f00a2a) | Feb 10, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [e53fb31614](https://linux-hardware.org/?probe=e53fb31614) | Feb 10, 2022 |
| Lenovo        | Legion Y740-15IRHg 81UH     | Notebook    | [b0cc5e0cbc](https://linux-hardware.org/?probe=b0cc5e0cbc) | Jan 29, 2022 |
| ASUSTek       | P5Q PRO TURBO               | Desktop     | [83ca29c9c8](https://linux-hardware.org/?probe=83ca29c9c8) | Jan 28, 2022 |
| Acer          | Aspire A315-58G             | Notebook    | [cb4f253c1c](https://linux-hardware.org/?probe=cb4f253c1c) | Jan 28, 2022 |
| Dell          | Latitude E6520              | Notebook    | [ee96960cec](https://linux-hardware.org/?probe=ee96960cec) | Jan 25, 2022 |
| Lenovo        | Yoga 710-15IKB 80V5         | Convertible | [3d5fe9fc42](https://linux-hardware.org/?probe=3d5fe9fc42) | Jan 22, 2022 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [0df160c245](https://linux-hardware.org/?probe=0df160c245) | Jan 21, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [230373b3ff](https://linux-hardware.org/?probe=230373b3ff) | Jan 09, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [3df8a1c560](https://linux-hardware.org/?probe=3df8a1c560) | Jan 08, 2022 |
| HP            | 1906                        | Desktop     | [5f8fe7cb20](https://linux-hardware.org/?probe=5f8fe7cb20) | Jan 06, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [793bfa4f40](https://linux-hardware.org/?probe=793bfa4f40) | Jan 04, 2022 |
| HP            | 2179                        | Desktop     | [79bac7ce1b](https://linux-hardware.org/?probe=79bac7ce1b) | Jan 01, 2022 |
| ASUSTek       | TUF B360M-PLUS GAMING/BR    | Desktop     | [512091cd1c](https://linux-hardware.org/?probe=512091cd1c) | Dec 30, 2021 |
| Dell          | Vostro 3590                 | Notebook    | [9e77a2584c](https://linux-hardware.org/?probe=9e77a2584c) | Dec 30, 2021 |
| HP            | 2179                        | Desktop     | [9b6358ce37](https://linux-hardware.org/?probe=9b6358ce37) | Dec 30, 2021 |
| ASUSTek       | ASUS EXPERTBOOK B9400CEA... | Notebook    | [78e3fbdf6a](https://linux-hardware.org/?probe=78e3fbdf6a) | Dec 28, 2021 |
| HP            | Notebook                    | Notebook    | [c14ea64659](https://linux-hardware.org/?probe=c14ea64659) | Dec 23, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [5c2c86f287](https://linux-hardware.org/?probe=5c2c86f287) | Dec 23, 2021 |
| ASUSTek       | X510UNR                     | Notebook    | [0733a05806](https://linux-hardware.org/?probe=0733a05806) | Dec 21, 2021 |
| ASUSTek       | ASUS EXPERTBOOK B9400CEA... | Notebook    | [b4425de4a6](https://linux-hardware.org/?probe=b4425de4a6) | Dec 17, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [6f3bd18b3f](https://linux-hardware.org/?probe=6f3bd18b3f) | Dec 06, 2021 |
| Pegatron      | D15K                        | Notebook    | [eaeaad8d39](https://linux-hardware.org/?probe=eaeaad8d39) | Nov 29, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [728b23aa46](https://linux-hardware.org/?probe=728b23aa46) | Nov 26, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [9e9b6fd944](https://linux-hardware.org/?probe=9e9b6fd944) | Nov 21, 2021 |
| MSI           | GP73 Leopard 8RD            | Notebook    | [5bafb43f78](https://linux-hardware.org/?probe=5bafb43f78) | Nov 21, 2021 |
| Acer          | Aspire A315-58G             | Notebook    | [911895fcf2](https://linux-hardware.org/?probe=911895fcf2) | Nov 19, 2021 |
| Acer          | Aspire A315-58G             | Notebook    | [5748b3cd05](https://linux-hardware.org/?probe=5748b3cd05) | Nov 12, 2021 |
| Lenovo        | ThinkPad W530 24384CU       | Notebook    | [d18d3495e0](https://linux-hardware.org/?probe=d18d3495e0) | Nov 05, 2021 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [4877535f8b](https://linux-hardware.org/?probe=4877535f8b) | Nov 03, 2021 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [8dd5924480](https://linux-hardware.org/?probe=8dd5924480) | Oct 31, 2021 |
| Acer          | Aspire A315-58G             | Notebook    | [905fce5118](https://linux-hardware.org/?probe=905fce5118) | Oct 29, 2021 |
| HP            | ENVY Sleekbook 4            | Notebook    | [ebea056239](https://linux-hardware.org/?probe=ebea056239) | Oct 29, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [2a54689fb3](https://linux-hardware.org/?probe=2a54689fb3) | Oct 24, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [fb95cbb063](https://linux-hardware.org/?probe=fb95cbb063) | Oct 19, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [6cd76dfa2a](https://linux-hardware.org/?probe=6cd76dfa2a) | Oct 13, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [e3a8d1ca32](https://linux-hardware.org/?probe=e3a8d1ca32) | Oct 11, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [c7c4a74bb8](https://linux-hardware.org/?probe=c7c4a74bb8) | Oct 11, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [68865693c7](https://linux-hardware.org/?probe=68865693c7) | Oct 09, 2021 |
| Dell          | 0XC7MM A01                  | Desktop     | [390c5408b2](https://linux-hardware.org/?probe=390c5408b2) | Oct 05, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [e804a59920](https://linux-hardware.org/?probe=e804a59920) | Oct 02, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [a198e8517a](https://linux-hardware.org/?probe=a198e8517a) | Oct 01, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [50fd919991](https://linux-hardware.org/?probe=50fd919991) | Aug 29, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [a3c6fe4037](https://linux-hardware.org/?probe=a3c6fe4037) | Jul 24, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [57d19e2c3a](https://linux-hardware.org/?probe=57d19e2c3a) | May 19, 2021 |
| Acer          | FIH57                       | Desktop     | [9c3e383ea5](https://linux-hardware.org/?probe=9c3e383ea5) | Apr 30, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Xero Rolling | 293       | 95.75%  |
| Xero         | 13        | 4.25%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| Xero | 305       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version          | Computers | Percent |
|------------------|-----------|---------|
| 6.4.12-arch1-1   | 49        | 15.03%  |
| 6.4.3-arch1-2    | 27        | 8.28%   |
| 6.4.9-arch1-1    | 25        | 7.67%   |
| 6.4.2-arch1-1    | 6         | 1.84%   |
| 6.4.10-arch1-1   | 6         | 1.84%   |
| 5.16.15-arch1-1  | 6         | 1.84%   |
| 6.5.3-arch1-1    | 5         | 1.53%   |
| 6.4.1-arch2-1    | 5         | 1.53%   |
| 6.1.12-arch1-1   | 5         | 1.53%   |
| 6.4.4-arch1-1    | 4         | 1.23%   |
| 6.3.9-arch1-1    | 4         | 1.23%   |
| 6.2.6-arch1-1    | 4         | 1.23%   |
| 6.0.12-arch1-1   | 4         | 1.23%   |
| 5.18.16-arch1-1  | 4         | 1.23%   |
| 6.5.5-arch1-1    | 3         | 0.92%   |
| 6.5.2-arch1-1    | 3         | 0.92%   |
| 6.4.8-arch1-1    | 3         | 0.92%   |
| 6.4.3-arch1-1    | 3         | 0.92%   |
| 6.4.11-arch2-1   | 3         | 0.92%   |
| 6.1.1-arch1-1    | 3         | 0.92%   |
| 5.17.9-arch1-1   | 3         | 0.92%   |
| 5.16.2-arch1-1   | 3         | 0.92%   |
| 5.16.1-arch1-1   | 3         | 0.92%   |
| 5.15.33-1-lts    | 3         | 0.92%   |
| 5.14.14-arch1-1  | 3         | 0.92%   |
| 6.5.4-arch2-1    | 2         | 0.61%   |
| 6.4.7-zen1-1-zen | 2         | 0.61%   |
| 6.4.7-arch1-2    | 2         | 0.61%   |
| 6.4.7-arch1-1    | 2         | 0.61%   |
| 6.4.2-zen1-1-zen | 2         | 0.61%   |
| 6.4.1-arch1-1    | 2         | 0.61%   |
| 6.3.8-arch1-1    | 2         | 0.61%   |
| 6.3.6-arch1-1    | 2         | 0.61%   |
| 6.2.8-arch1-1    | 2         | 0.61%   |
| 6.2.7-arch1-1    | 2         | 0.61%   |
| 6.2.12-arch1-1   | 2         | 0.61%   |
| 6.0.7-arch1-1    | 2         | 0.61%   |
| 5.19.9-arch1-1   | 2         | 0.61%   |
| 5.19.13-arch1-1  | 2         | 0.61%   |
| 5.19.12-arch1-1  | 2         | 0.61%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.4.12  | 50        | 15.34%  |
| 6.4.3   | 31        | 9.51%   |
| 6.4.9   | 25        | 7.67%   |
| 6.4.7   | 8         | 2.45%   |
| 6.4.2   | 8         | 2.45%   |
| 6.4.10  | 8         | 2.45%   |
| 6.4.1   | 7         | 2.15%   |
| 6.3.9   | 6         | 1.84%   |
| 5.16.15 | 6         | 1.84%   |
| 6.5.3   | 5         | 1.53%   |
| 6.5.2   | 5         | 1.53%   |
| 6.4.4   | 5         | 1.53%   |
| 6.4.11  | 5         | 1.53%   |
| 6.1.12  | 5         | 1.53%   |
| 6.2.6   | 4         | 1.23%   |
| 6.0.12  | 4         | 1.23%   |
| 5.18.16 | 4         | 1.23%   |
| 5.14.14 | 4         | 1.23%   |
| 6.5.5   | 3         | 0.92%   |
| 6.5.4   | 3         | 0.92%   |
| 6.4.8   | 3         | 0.92%   |
| 6.3.8   | 3         | 0.92%   |
| 6.1.1   | 3         | 0.92%   |
| 5.19.13 | 3         | 0.92%   |
| 5.17.9  | 3         | 0.92%   |
| 5.16.2  | 3         | 0.92%   |
| 5.16.16 | 3         | 0.92%   |
| 5.16.1  | 3         | 0.92%   |
| 5.15.33 | 3         | 0.92%   |
| 5.15.12 | 3         | 0.92%   |
| 5.14.8  | 3         | 0.92%   |
| 5.14.16 | 3         | 0.92%   |
| 6.3.6   | 2         | 0.61%   |
| 6.2.8   | 2         | 0.61%   |
| 6.2.7   | 2         | 0.61%   |
| 6.2.12  | 2         | 0.61%   |
| 6.1.6   | 2         | 0.61%   |
| 6.1.38  | 2         | 0.61%   |
| 6.0.8   | 2         | 0.61%   |
| 6.0.7   | 2         | 0.61%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.4     | 146       | 46.06%  |
| 5.16    | 23        | 7.26%   |
| 6.1     | 19        | 5.99%   |
| 5.15    | 18        | 5.68%   |
| 6.5     | 17        | 5.36%   |
| 6.3     | 15        | 4.73%   |
| 6.0     | 15        | 4.73%   |
| 6.2     | 14        | 4.42%   |
| 5.14    | 13        | 4.1%    |
| 5.19    | 11        | 3.47%   |
| 5.18    | 11        | 3.47%   |
| 5.17    | 8         | 2.52%   |
| 5.10    | 3         | 0.95%   |
| 5.13    | 2         | 0.63%   |
| 5.12    | 1         | 0.32%   |
| 5.11    | 1         | 0.32%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 305       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| KDE5     | 292       | 94.81%  |
| XFCE     | 8         | 2.6%    |
| GNOME    | 4         | 1.3%    |
| Hyprland | 2         | 0.65%   |
| LeftWM   | 1         | 0.32%   |
| KDE      | 1         | 0.32%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 283       | 92.48%  |
| Wayland | 19        | 6.21%   |
| Tty     | 3         | 0.98%   |
| Unknown | 1         | 0.33%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 255       | 81.99%  |
| Unknown | 30        | 9.65%   |
| LightDM | 23        | 7.4%    |
| GDM     | 2         | 0.64%   |
| TDM     | 1         | 0.32%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 136       | 44.3%   |
| de_DE | 26        | 8.47%   |
| es_MX | 15        | 4.89%   |
| en_IN | 15        | 4.89%   |
| en_GB | 11        | 3.58%   |
| pl_PL | 10        | 3.26%   |
| ru_RU | 8         | 2.61%   |
| pt_BR | 8         | 2.61%   |
| en_CA | 8         | 2.61%   |
| C     | 8         | 2.61%   |
| it_IT | 7         | 2.28%   |
| fr_FR | 7         | 2.28%   |
| tr_TR | 6         | 1.95%   |
| en_AU | 6         | 1.95%   |
| es_ES | 4         | 1.3%    |
| es_AR | 4         | 1.3%    |
| hu_HU | 3         | 0.98%   |
| vi_VN | 2         | 0.65%   |
| nb_NO | 2         | 0.65%   |
| en_ZA | 2         | 0.65%   |
| en_DK | 2         | 0.65%   |
| zh_CN | 1         | 0.33%   |
| sv_SE | 1         | 0.33%   |
| nl_NL | 1         | 0.33%   |
| ko_KR | 1         | 0.33%   |
| es_VE | 1         | 0.33%   |
| es_SV | 1         | 0.33%   |
| es_CL | 1         | 0.33%   |
| en_PH | 1         | 0.33%   |
| en_IL | 1         | 0.33%   |
| en_AG | 1         | 0.33%   |
| el_GR | 1         | 0.33%   |
| de_CH | 1         | 0.33%   |
| de_AT | 1         | 0.33%   |
| da_DK | 1         | 0.33%   |
| cs_CZ | 1         | 0.33%   |
| ca_ES | 1         | 0.33%   |
| ba_RU | 1         | 0.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 228       | 74.27%  |
| BIOS | 79        | 25.73%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 103       | 33.33%  |
| Btrfs   | 102       | 33.01%  |
| Xfs     | 94        | 30.42%  |
| Overlay | 9         | 2.91%   |
| Nilfs2  | 1         | 0.32%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 243       | 79.15%  |
| MBR     | 34        | 11.07%  |
| Unknown | 30        | 9.77%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 232       | 74.84%  |
| Yes       | 78        | 25.16%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 186       | 60.59%  |
| Yes       | 121       | 39.41%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 70        | 22.95%  |
| Lenovo              | 56        | 18.36%  |
| Hewlett-Packard     | 35        | 11.48%  |
| Dell                | 33        | 10.82%  |
| MSI                 | 22        | 7.21%   |
| Acer                | 16        | 5.25%   |
| Gigabyte Technology | 13        | 4.26%   |
| Apple               | 11        | 3.61%   |
| ASRock              | 8         | 2.62%   |
| Pegatron            | 4         | 1.31%   |
| Intel               | 4         | 1.31%   |
| HUAWEI              | 4         | 1.31%   |
| Timi                | 2         | 0.66%   |
| Microsoft           | 2         | 0.66%   |
| Medion              | 2         | 0.66%   |
| ECS                 | 2         | 0.66%   |
| BESSTAR Tech        | 2         | 0.66%   |
| Unknown             | 2         | 0.66%   |
| Win Element         | 1         | 0.33%   |
| WEIGO               | 1         | 0.33%   |
| VIT                 | 1         | 0.33%   |
| Toshiba             | 1         | 0.33%   |
| Sony                | 1         | 0.33%   |
| Samsung Electronics | 1         | 0.33%   |
| LNV                 | 1         | 0.33%   |
| Juana Manso         | 1         | 0.33%   |
| JINGSHA             | 1         | 0.33%   |
| Huanan              | 1         | 0.33%   |
| HONOR               | 1         | 0.33%   |
| Google              | 1         | 0.33%   |
| Fujitsu             | 1         | 0.33%   |
| Biostar             | 1         | 0.33%   |
| AZW                 | 1         | 0.33%   |
| Aquarius            | 1         | 0.33%   |
| Alienware           | 1         | 0.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Dell Precision M3800                | 3         | 0.98%   |
| Dell OptiPlex 7010                  | 3         | 0.98%   |
| Unknown                             | 3         | 0.98%   |
| MSI MS-7971                         | 2         | 0.66%   |
| Lenovo IdeaPad Gaming 3 15IHU6 82K1 | 2         | 0.66%   |
| Dell Studio XPS 8100                | 2         | 0.66%   |
| Dell OptiPlex 9020                  | 2         | 0.66%   |
| Dell Latitude E6520                 | 2         | 0.66%   |
| Dell Latitude 7480                  | 2         | 0.66%   |
| Dell Latitude 5420                  | 2         | 0.66%   |
| ASUS TUF Gaming X570-PLUS           | 2         | 0.66%   |
| ASUS PRIME A320M-K                  | 2         | 0.66%   |
| Apple MacBookPro8,1                 | 2         | 0.66%   |
| Win Element M9                      | 1         | 0.33%   |
| WEIGO CDA-141AU                     | 1         | 0.33%   |
| VIT P2402                           | 1         | 0.33%   |
| Toshiba TECRA A11                   | 1         | 0.33%   |
| Timi Redmi Book Pro 15 2022         | 1         | 0.33%   |
| Timi Redmi Book Pro 14 2022         | 1         | 0.33%   |
| Sony VGC-LV180ME                    | 1         | 0.33%   |
| Samsung 950QED                      | 1         | 0.33%   |
| Pegatron p7-1010a                   | 1         | 0.33%   |
| Pegatron p6-2026                    | 1         | 0.33%   |
| Pegatron D15K                       | 1         | 0.33%   |
| Pegatron 20-b010                    | 1         | 0.33%   |
| MSI MS-7D22                         | 1         | 0.33%   |
| MSI MS-7C96                         | 1         | 0.33%   |
| MSI MS-7C94                         | 1         | 0.33%   |
| MSI MS-7C91                         | 1         | 0.33%   |
| MSI MS-7C52                         | 1         | 0.33%   |
| MSI MS-7C37                         | 1         | 0.33%   |
| MSI MS-7B61                         | 1         | 0.33%   |
| MSI MS-7B12                         | 1         | 0.33%   |
| MSI MS-7A70                         | 1         | 0.33%   |
| MSI MS-7A34                         | 1         | 0.33%   |
| MSI MS-7916                         | 1         | 0.33%   |
| MSI MS-7815                         | 1         | 0.33%   |
| MSI MS-7758                         | 1         | 0.33%   |
| MSI MS-7623                         | 1         | 0.33%   |
| MSI Katana GF66 11UE                | 1         | 0.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 20        | 6.56%   |
| Lenovo IdeaPad     | 19        | 6.23%   |
| ASUS ROG           | 16        | 5.25%   |
| Acer Aspire        | 13        | 4.26%   |
| HP Laptop          | 10        | 3.28%   |
| ASUS TUF           | 10        | 3.28%   |
| ASUS VivoBook      | 9         | 2.95%   |
| Dell Latitude      | 8         | 2.62%   |
| Dell Inspiron      | 8         | 2.62%   |
| ASUS PRIME         | 8         | 2.62%   |
| Lenovo Legion      | 6         | 1.97%   |
| Dell OptiPlex      | 5         | 1.64%   |
| Lenovo Yoga        | 4         | 1.31%   |
| HP Pavilion        | 4         | 1.31%   |
| Dell Precision     | 4         | 1.31%   |
| ASUS ASUS          | 4         | 1.31%   |
| Apple MacBookPro11 | 3         | 0.98%   |
| Unknown            | 3         | 0.98%   |
| Timi Redmi         | 2         | 0.66%   |
| MSI MS-7971        | 2         | 0.66%   |
| Microsoft Surface  | 2         | 0.66%   |
| HP ProBook         | 2         | 0.66%   |
| HP ENVY            | 2         | 0.66%   |
| Gigabyte Z790      | 2         | 0.66%   |
| Dell Studio        | 2         | 0.66%   |
| ASUS M5A99X        | 2         | 0.66%   |
| Apple MacBookPro8  | 2         | 0.66%   |
| Win Element M9     | 1         | 0.33%   |
| WEIGO CDA-141AU    | 1         | 0.33%   |
| VIT P2402          | 1         | 0.33%   |
| Toshiba TECRA      | 1         | 0.33%   |
| Sony VGC-LV180ME   | 1         | 0.33%   |
| Samsung 950QED     | 1         | 0.33%   |
| Pegatron p7-1010a  | 1         | 0.33%   |
| Pegatron p6-2026   | 1         | 0.33%   |
| Pegatron D15K      | 1         | 0.33%   |
| Pegatron 20-b010   | 1         | 0.33%   |
| MSI MS-7D22        | 1         | 0.33%   |
| MSI MS-7C96        | 1         | 0.33%   |
| MSI MS-7C94        | 1         | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 42        | 13.77%  |
| 2019 | 40        | 13.11%  |
| 2021 | 36        | 11.8%   |
| 2017 | 30        | 9.84%   |
| 2018 | 25        | 8.2%    |
| 2014 | 18        | 5.9%    |
| 2022 | 16        | 5.25%   |
| 2015 | 16        | 5.25%   |
| 2013 | 16        | 5.25%   |
| 2012 | 16        | 5.25%   |
| 2011 | 15        | 4.92%   |
| 2016 | 11        | 3.61%   |
| 2010 | 8         | 2.62%   |
| 2023 | 7         | 2.3%    |
| 2009 | 6         | 1.97%   |
| 2008 | 3         | 0.98%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 173       | 56.72%  |
| Desktop     | 112       | 36.72%  |
| Convertible | 10        | 3.28%   |
| Mini pc     | 4         | 1.31%   |
| All in one  | 3         | 0.98%   |
| Tablet      | 2         | 0.66%   |
| Server      | 1         | 0.33%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 304       | 99.35%  |
| Enabled  | 2         | 0.65%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 304       | 99.67%  |
| Yes  | 1         | 0.33%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 81        | 26.56%  |
| 16.01-24.0  | 78        | 25.57%  |
| 8.01-16.0   | 63        | 20.66%  |
| 32.01-64.0  | 37        | 12.13%  |
| 3.01-4.0    | 33        | 10.82%  |
| 64.01-256.0 | 7         | 2.3%    |
| 24.01-32.0  | 6         | 1.97%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 109       | 33.85%  |
| 2.01-3.0   | 92        | 28.57%  |
| 4.01-8.0   | 58        | 18.01%  |
| 3.01-4.0   | 41        | 12.73%  |
| 8.01-16.0  | 10        | 3.11%   |
| 16.01-24.0 | 7         | 2.17%   |
| 0.51-1.0   | 3         | 0.93%   |
| 0.01-0.5   | 2         | 0.62%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 162       | 52.26%  |
| 2      | 89        | 28.71%  |
| 3      | 33        | 10.65%  |
| 4      | 10        | 3.23%   |
| 5      | 8         | 2.58%   |
| 6      | 4         | 1.29%   |
| 8      | 2         | 0.65%   |
| 7      | 2         | 0.65%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 237       | 77.45%  |
| Yes       | 69        | 22.55%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 250       | 81.7%   |
| No        | 56        | 18.3%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 251       | 81.76%  |
| No        | 56        | 18.24%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 233       | 75.9%   |
| No        | 74        | 24.1%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 58        | 18.95%  |
| Germany      | 29        | 9.48%   |
| India        | 20        | 6.54%   |
| Poland       | 12        | 3.92%   |
| Canada       | 12        | 3.92%   |
| Turkey       | 11        | 3.59%   |
| Russia       | 11        | 3.59%   |
| Italy        | 11        | 3.59%   |
| Mexico       | 9         | 2.94%   |
| France       | 9         | 2.94%   |
| Brazil       | 8         | 2.61%   |
| Argentina    | 8         | 2.61%   |
| Vietnam      | 6         | 1.96%   |
| Australia    | 6         | 1.96%   |
| UK           | 5         | 1.63%   |
| Spain        | 5         | 1.63%   |
| Netherlands  | 5         | 1.63%   |
| Romania      | 4         | 1.31%   |
| Norway       | 4         | 1.31%   |
| Hungary      | 4         | 1.31%   |
| Greece       | 4         | 1.31%   |
| Chile        | 4         | 1.31%   |
| Switzerland  | 3         | 0.98%   |
| Pakistan     | 3         | 0.98%   |
| Denmark      | 3         | 0.98%   |
| Colombia     | 3         | 0.98%   |
| Venezuela    | 2         | 0.65%   |
| Thailand     | 2         | 0.65%   |
| Sweden       | 2         | 0.65%   |
| South Africa | 2         | 0.65%   |
| Portugal     | 2         | 0.65%   |
| Philippines  | 2         | 0.65%   |
| Morocco      | 2         | 0.65%   |
| Lebanon      | 2         | 0.65%   |
| Indonesia    | 2         | 0.65%   |
| Egypt        | 2         | 0.65%   |
| Czechia      | 2         | 0.65%   |
| Bahrain      | 2         | 0.65%   |
| Zambia       | 1         | 0.33%   |
| Tunisia      | 1         | 0.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Istanbul         | 6         | 1.95%   |
| Warsaw           | 4         | 1.3%    |
| Red Lake         | 4         | 1.3%    |
| Longmont         | 4         | 1.3%    |
| Berlin           | 4         | 1.3%    |
| Mexico City      | 3         | 0.97%   |
| Hanoi            | 3         | 0.97%   |
| Hamburg          | 3         | 0.97%   |
| Buenos Aires     | 3         | 0.97%   |
| Tangerang        | 2         | 0.65%   |
| Stuttgart        | 2         | 0.65%   |
| St Petersburg    | 2         | 0.65%   |
| Santa Rosa       | 2         | 0.65%   |
| Salt Lake City   | 2         | 0.65%   |
| Pune             | 2         | 0.65%   |
| Poznan           | 2         | 0.65%   |
| Phoenix          | 2         | 0.65%   |
| Norfolk          | 2         | 0.65%   |
| Niterói         | 2         | 0.65%   |
| Moscow           | 2         | 0.65%   |
| Melbourne        | 2         | 0.65%   |
| Medellín        | 2         | 0.65%   |
| Madurai          | 2         | 0.65%   |
| Iasi             | 2         | 0.65%   |
| Ho Chi Minh City | 2         | 0.65%   |
| Gdansk           | 2         | 0.65%   |
| Denver           | 2         | 0.65%   |
| Cumming          | 2         | 0.65%   |
| Chicago          | 2         | 0.65%   |
| Chennai          | 2         | 0.65%   |
| Cairo            | 2         | 0.65%   |
| Cagayan de Oro   | 2         | 0.65%   |
| Brisbane         | 2         | 0.65%   |
| Bremen           | 2         | 0.65%   |
| Bengaluru        | 2         | 0.65%   |
| Beirut           | 2         | 0.65%   |
| Zurich           | 1         | 0.32%   |
| Zenica           | 1         | 0.32%   |
| Zell am See      | 1         | 0.32%   |
| Zeeland          | 1         | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 86        | 124    | 17.27%  |
| Seagate                      | 63        | 83     | 12.65%  |
| WDC                          | 55        | 75     | 11.04%  |
| Kingston                     | 35        | 41     | 7.03%   |
| Sandisk                      | 31        | 38     | 6.22%   |
| Toshiba                      | 25        | 28     | 5.02%   |
| Crucial                      | 17        | 21     | 3.41%   |
| Intel                        | 16        | 23     | 3.21%   |
| Unknown                      | 13        | 17     | 2.61%   |
| SK hynix                     | 13        | 14     | 2.61%   |
| Micron Technology            | 10        | 12     | 2.01%   |
| HGST                         | 9         | 9      | 1.81%   |
| Micron/Crucial Technology    | 7         | 8      | 1.41%   |
| KIOXIA                       | 7         | 8      | 1.41%   |
| Hitachi                      | 6         | 6      | 1.2%    |
| China                        | 6         | 6      | 1.2%    |
| Apple                        | 5         | 5      | 1%      |
| A-DATA Technology            | 5         | 5      | 1%      |
| Transcend                    | 4         | 4      | 0.8%    |
| Realtek Semiconductor        | 4         | 4      | 0.8%    |
| Phison Electronics           | 4         | 6      | 0.8%    |
| LITEONIT                     | 4         | 4      | 0.8%    |
| Intenso                      | 4         | 5      | 0.8%    |
| ADATA Technology             | 4         | 4      | 0.8%    |
| PNY                          | 3         | 3      | 0.6%    |
| Phison                       | 3         | 3      | 0.6%    |
| MAXIO Technology (Hangzhou)  | 3         | 3      | 0.6%    |
| Kingston Technology Company  | 3         | 4      | 0.6%    |
| Apacer                       | 3         | 3      | 0.6%    |
| Shenzhen Longsys Electronics | 2         | 2      | 0.4%    |
| SAGE                         | 2         | 2      | 0.4%    |
| OWC                          | 2         | 2      | 0.4%    |
| LITEON                       | 2         | 2      | 0.4%    |
| JMicron Technology           | 2         | 2      | 0.4%    |
| Hewlett-Packard              | 2         | 2      | 0.4%    |
| Emtec                        | 2         | 2      | 0.4%    |
| XPG                          | 1         | 1      | 0.2%    |
| Vaseky                       | 1         | 1      | 0.2%    |
| tecmiyo                      | 1         | 1      | 0.2%    |
| Team                         | 1         | 1      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB               | 14        | 2.56%   |
| Toshiba MQ04ABF100 1TB                                            | 7         | 1.28%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB                | 7         | 1.28%   |
| Kingston SA400S37240G 240GB SSD                                   | 7         | 1.28%   |
| Unknown SD/MMC/MS PRO 128GB                                       | 6         | 1.1%    |
| Kingston SA400S37960G 960GB SSD                                   | 6         | 1.1%    |
| Crucial CT500MX500SSD1 500GB                                      | 6         | 1.1%    |
| Seagate ST1000LM035-1RK172 1TB                                    | 5         | 0.91%   |
| Seagate ST1000DM003-1SB102 1TB                                    | 5         | 0.91%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 500GB               | 5         | 0.91%   |
| Kingston SA400S37480G 480GB SSD                                   | 5         | 0.91%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB                  | 4         | 0.73%   |
| Samsung SSD 860 EVO 500GB                                         | 4         | 0.73%   |
| Samsung SSD 850 EVO 250GB                                         | 4         | 0.73%   |
| WDC WD20EZBX-00AYRA0 2TB                                          | 3         | 0.55%   |
| WDC WD10SPZX-24Z10 1TB                                            | 3         | 0.55%   |
| Unknown MMC Card  64GB                                            | 3         | 0.55%   |
| Seagate ST1000LM049-2GH172 1TB                                    | 3         | 0.55%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                                | 3         | 0.55%   |
| Seagate ST1000DM010-2EP102 1TB                                    | 3         | 0.55%   |
| Seagate One Touch HDD 2TB                                         | 3         | 0.55%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB                              | 3         | 0.55%   |
| Samsung SSD 980 1TB                                               | 3         | 0.55%   |
| Samsung SSD 860 EVO 1TB                                           | 3         | 0.55%   |
| Realtek RTS5763DL NVMe SSD Controller 256GB                       | 3         | 0.55%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                               | 3         | 0.55%   |
| Micron/Crucial CT2000P5PSSD8 2TB                                  | 3         | 0.55%   |
| Micron 2210_MTFDHBA512QFD 512GB                                   | 3         | 0.55%   |
| Kingston SNVS500G 500GB                                           | 3         | 0.55%   |
| HGST HTS545050A7E680 500GB                                        | 3         | 0.55%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 256GB | 3         | 0.55%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                                  | 2         | 0.37%   |
| WDC WD10SPZX-60Z10T0 1TB                                          | 2         | 0.37%   |
| WDC WD10EZEX-60WN4A0 1TB                                          | 2         | 0.37%   |
| WDC WD10EZEX-60M2NA0 1TB                                          | 2         | 0.37%   |
| WDC WD10EZEX-22MFCA0 1TB                                          | 2         | 0.37%   |
| Unknown MMC Card  128GB                                           | 2         | 0.37%   |
| Toshiba XG6 NVMe SSD Controller 512GB                             | 2         | 0.37%   |
| Toshiba DT01ACA300 3TB                                            | 2         | 0.37%   |
| SK hynix SHPP41-2000GM 2TB                                        | 2         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 62        | 81     | 39.49%  |
| WDC                 | 41        | 55     | 26.11%  |
| Toshiba             | 19        | 21     | 12.1%   |
| HGST                | 9         | 9      | 5.73%   |
| Unknown             | 6         | 6      | 3.82%   |
| Hitachi             | 6         | 6      | 3.82%   |
| Samsung Electronics | 4         | 4      | 2.55%   |
| Intenso             | 3         | 4      | 1.91%   |
| SAGE                | 2         | 2      | 1.27%   |
| SSK                 | 1         | 1      | 0.64%   |
| SABRENT             | 1         | 1      | 0.64%   |
| Maxtor              | 1         | 1      | 0.64%   |
| Maxone              | 1         | 1      | 0.64%   |
| ASMedia             | 1         | 1      | 0.64%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 34        | 42     | 20.12%  |
| Kingston            | 26        | 31     | 15.38%  |
| Crucial             | 17        | 21     | 10.06%  |
| SanDisk             | 12        | 12     | 7.1%    |
| WDC                 | 10        | 11     | 5.92%   |
| China               | 6         | 6      | 3.55%   |
| Apple               | 5         | 5      | 2.96%   |
| Transcend           | 4         | 4      | 2.37%   |
| LITEONIT            | 4         | 4      | 2.37%   |
| PNY                 | 3         | 3      | 1.78%   |
| Apacer              | 3         | 3      | 1.78%   |
| A-DATA Technology   | 3         | 3      | 1.78%   |
| SK hynix            | 2         | 2      | 1.18%   |
| OWC                 | 2         | 2      | 1.18%   |
| Micron Technology   | 2         | 2      | 1.18%   |
| LITEON              | 2         | 2      | 1.18%   |
| JMicron Technology  | 2         | 2      | 1.18%   |
| Intel               | 2         | 2      | 1.18%   |
| Hewlett-Packard     | 2         | 2      | 1.18%   |
| Emtec               | 2         | 2      | 1.18%   |
| Vaseky              | 1         | 1      | 0.59%   |
| tecmiyo             | 1         | 1      | 0.59%   |
| Team                | 1         | 1      | 0.59%   |
| TARGET              | 1         | 1      | 0.59%   |
| SPCC                | 1         | 1      | 0.59%   |
| S3+                 | 1         | 1      | 0.59%   |
| Plextor             | 1         | 1      | 0.59%   |
| Patriot             | 1         | 1      | 0.59%   |
| OSCOO               | 1         | 1      | 0.59%   |
| NT-1TB              | 1         | 1      | 0.59%   |
| Mushkin             | 1         | 1      | 0.59%   |
| Lexar               | 1         | 1      | 0.59%   |
| Leven               | 1         | 1      | 0.59%   |
| KingSpec            | 1         | 1      | 0.59%   |
| Kingmax             | 1         | 1      | 0.59%   |
| KingFast            | 1         | 1      | 0.59%   |
| Intenso             | 1         | 1      | 0.59%   |
| Imation             | 1         | 1      | 0.59%   |
| Hikvision           | 1         | 1      | 0.59%   |
| GOODRAM             | 1         | 1      | 0.59%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 155       | 221    | 35.71%  |
| SSD     | 139       | 187    | 32.03%  |
| HDD     | 129       | 193    | 29.72%  |
| MMC     | 8         | 12     | 1.84%   |
| Unknown | 3         | 3      | 0.69%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 208       | 347    | 51.87%  |
| NVMe | 155       | 220    | 38.65%  |
| SAS  | 30        | 37     | 7.48%   |
| MMC  | 8         | 12     | 2%      |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 147       | 195    | 50.87%  |
| 0.51-1.0   | 103       | 129    | 35.64%  |
| 1.01-2.0   | 22        | 28     | 7.61%   |
| 4.01-10.0  | 6         | 11     | 2.08%   |
| 3.01-4.0   | 5         | 7      | 1.73%   |
| 2.01-3.0   | 5         | 6      | 1.73%   |
| 10.01-20.0 | 1         | 4      | 0.35%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 73        | 23.32%  |
| 251-500        | 64        | 20.45%  |
| More than 3000 | 44        | 14.06%  |
| 501-1000       | 38        | 12.14%  |
| 1001-2000      | 34        | 10.86%  |
| 51-100         | 15        | 4.79%   |
| Unknown        | 13        | 4.15%   |
| 21-50          | 12        | 3.83%   |
| 2001-3000      | 12        | 3.83%   |
| 1-20           | 8         | 2.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 122       | 38.61%  |
| 21-50          | 54        | 17.09%  |
| 101-250        | 39        | 12.34%  |
| 51-100         | 36        | 11.39%  |
| 251-500        | 19        | 6.01%   |
| Unknown        | 13        | 4.11%   |
| 501-1000       | 12        | 3.8%    |
| 1001-2000      | 8         | 2.53%   |
| 2001-3000      | 7         | 2.22%   |
| More than 3000 | 6         | 1.9%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB             | 2         | 2      | 3.08%   |
| Seagate ST320LT012-9WS14C 320GB       | 2         | 3      | 3.08%   |
| WDC WD5000AAKX-60U6AA0 500GB          | 1         | 1      | 1.54%   |
| WDC WD3200AAJS-08L7A0 320GB           | 1         | 1      | 1.54%   |
| WDC WD10SPZX-60Z10T0 1TB              | 1         | 1      | 1.54%   |
| WDC WD10SPZX-24Z10 1TB                | 1         | 1      | 1.54%   |
| WDC WD10JPVX-60JC3T0 1TB              | 1         | 1      | 1.54%   |
| WDC WD10EZEX-60M2NA0 1TB              | 1         | 1      | 1.54%   |
| WDC WD10EZEX-08WN4A0 1TB              | 1         | 1      | 1.54%   |
| WDC WD10EADS-00M2B0 1TB               | 1         | 1      | 1.54%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 1         | 2      | 1.54%   |
| WDC WD Blue SA510 2.5 500GB           | 1         | 2      | 1.54%   |
| Toshiba MQ04ABF100 1TB                | 1         | 1      | 1.54%   |
| Toshiba MQ01ABF050M 500GB             | 1         | 1      | 1.54%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 1.54%   |
| Toshiba MQ01ABD100 1TB                | 1         | 1      | 1.54%   |
| Toshiba MK6465GSX 640GB               | 1         | 1      | 1.54%   |
| Toshiba MK4058GSX 400GB               | 1         | 1      | 1.54%   |
| Toshiba MK3261GSY 320GB               | 1         | 1      | 1.54%   |
| Toshiba MK2555GSX 250GB               | 1         | 1      | 1.54%   |
| TARGET SSD 128G                       | 1         | 1      | 1.54%   |
| SK hynix HFS128G3BTND-N210A 128GB SSD | 1         | 1      | 1.54%   |
| SK hynix HFS128G3AMNB-2200A 128GB SSD | 1         | 1      | 1.54%   |
| SK hynix BC711 HFM512GD3JX013N 512GB  | 1         | 1      | 1.54%   |
| Seagate ST9500420AS 500GB             | 1         | 1      | 1.54%   |
| Seagate ST9320423AS 320GB             | 1         | 1      | 1.54%   |
| Seagate ST500LT012-1DG142 500GB       | 1         | 1      | 1.54%   |
| Seagate ST500LM000-SSHD-8GB           | 1         | 1      | 1.54%   |
| Seagate ST500DM009-2F110A 500GB       | 1         | 1      | 1.54%   |
| Seagate ST3500820AS 500GB             | 1         | 1      | 1.54%   |
| Seagate ST31000524AS 1TB              | 1         | 1      | 1.54%   |
| Seagate ST2000VX000-1CU164 2TB        | 1         | 1      | 1.54%   |
| Seagate ST2000DM006-2DM164 2TB        | 1         | 1      | 1.54%   |
| Seagate ST2000DL003-9VT166 2TB        | 1         | 1      | 1.54%   |
| Seagate ST1000LM049-2GH172 1TB        | 1         | 1      | 1.54%   |
| Seagate ST1000LM048-2E7172 1TB        | 1         | 1      | 1.54%   |
| Seagate ST1000LM035-1RK172 1TB        | 1         | 1      | 1.54%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1         | 1      | 1.54%   |
| Seagate ST1000LM014-SSHD-8GB          | 1         | 1      | 1.54%   |
| Seagate ST1000DM010-2EP102 1TB        | 1         | 1      | 1.54%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 23        | 24     | 35.94%  |
| WDC                 | 10        | 12     | 15.63%  |
| Toshiba             | 7         | 8      | 10.94%  |
| Hitachi             | 4         | 4      | 6.25%   |
| SK hynix            | 3         | 3      | 4.69%   |
| Samsung Electronics | 2         | 2      | 3.13%   |
| Kingston            | 2         | 2      | 3.13%   |
| HGST                | 2         | 2      | 3.13%   |
| Crucial             | 2         | 2      | 3.13%   |
| TARGET              | 1         | 1      | 1.56%   |
| SAGE                | 1         | 1      | 1.56%   |
| SABRENT             | 1         | 1      | 1.56%   |
| Maxtor              | 1         | 1      | 1.56%   |
| LITEONIT            | 1         | 1      | 1.56%   |
| China               | 1         | 1      | 1.56%   |
| ASMedia             | 1         | 1      | 1.56%   |
| Apple               | 1         | 1      | 1.56%   |
| ADATA Technology    | 1         | 1      | 1.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 23        | 24     | 46%     |
| WDC                 | 9         | 10     | 18%     |
| Toshiba             | 7         | 8      | 14%     |
| Hitachi             | 4         | 4      | 8%      |
| HGST                | 2         | 2      | 4%      |
| Samsung Electronics | 1         | 1      | 2%      |
| SAGE                | 1         | 1      | 2%      |
| SABRENT             | 1         | 1      | 2%      |
| Maxtor              | 1         | 1      | 2%      |
| ASMedia             | 1         | 1      | 2%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 49        | 53     | 77.78%  |
| SSD  | 11        | 12     | 17.46%  |
| NVMe | 3         | 3      | 4.76%   |

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
| Works    | 246       | 440    | 67.96%  |
| Malfunc  | 61        | 68     | 16.85%  |
| Detected | 55        | 108    | 15.19%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 204       | 46.47%  |
| AMD                          | 62        | 14.12%  |
| Samsung Electronics          | 54        | 12.3%   |
| SanDisk                      | 27        | 6.15%   |
| Kingston Technology Company  | 12        | 2.73%   |
| SK hynix                     | 11        | 2.51%   |
| Micron Technology            | 9         | 2.05%   |
| ASMedia Technology           | 9         | 2.05%   |
| Phison Electronics           | 7         | 1.59%   |
| Micron/Crucial Technology    | 7         | 1.59%   |
| KIOXIA                       | 7         | 1.59%   |
| Toshiba America Info Systems | 6         | 1.37%   |
| ADATA Technology             | 6         | 1.37%   |
| Realtek Semiconductor        | 5         | 1.14%   |
| MAXIO Technology (Hangzhou)  | 3         | 0.68%   |
| Shenzhen Longsys Electronics | 2         | 0.46%   |
| Nvidia                       | 2         | 0.46%   |
| Marvell Technology Group     | 2         | 0.46%   |
| VIA Technologies             | 1         | 0.23%   |
| Silicon Motion               | 1         | 0.23%   |
| Seagate Technology           | 1         | 0.23%   |
| JMicron Technology           | 1         | 0.23%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 47        | 9.73%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 19        | 3.93%   |
| Intel Volume Management Device NVMe RAID Controller                            | 18        | 3.73%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 17        | 3.52%   |
| Samsung NVMe SSD Controller 980                                                | 16        | 3.31%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 12        | 2.48%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 12        | 2.48%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 10        | 2.07%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 10        | 2.07%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 10        | 2.07%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 9         | 1.86%   |
| Intel Tiger Lake-LP SATA Controller                                            | 9         | 1.86%   |
| Intel SATA Controller [RAID mode]                                              | 9         | 1.86%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 9         | 1.86%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 9         | 1.86%   |
| AMD 500 Series Chipset SATA Controller                                         | 9         | 1.86%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 8         | 1.66%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 8         | 1.66%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 8         | 1.66%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 8         | 1.66%   |
| AMD 400 Series Chipset SATA Controller                                         | 8         | 1.66%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 6         | 1.24%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 5         | 1.04%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 5         | 1.04%   |
| Intel Optane NVME SSD H10 with Solid State Storage [Teton Glacier]             | 5         | 1.04%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 5         | 1.04%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 5         | 1.04%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 5         | 1.04%   |
| AMD FCH SATA Controller D                                                      | 5         | 1.04%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 4         | 0.83%   |
| Phison E12 NVMe Controller                                                     | 4         | 0.83%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 4         | 0.83%   |
| Intel SSD 660P Series                                                          | 4         | 0.83%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 4         | 0.83%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4         | 0.83%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 4         | 0.83%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4         | 0.83%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 4         | 0.83%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 3         | 0.62%   |
| SanDisk WD Green SN350 NVMe SSD 240GB (DRAM-less)                              | 3         | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 233       | 53.56%  |
| NVMe | 155       | 35.63%  |
| RAID | 40        | 9.2%    |
| IDE  | 7         | 1.61%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 226       | 74.1%   |
| AMD    | 79        | 25.9%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz | 7         | 2.29%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 6         | 1.96%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 5         | 1.63%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 5         | 1.63%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 5         | 1.63%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 5         | 1.63%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 4         | 1.31%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 4         | 1.31%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 4         | 1.31%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 4         | 1.31%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 4         | 1.31%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 4         | 1.31%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 4         | 1.31%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 4         | 1.31%   |
| Intel Core i7-8700K CPU @ 3.70GHz       | 3         | 0.98%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz      | 3         | 0.98%   |
| Intel Core i7-7700K CPU @ 4.20GHz       | 3         | 0.98%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 3         | 0.98%   |
| Intel Core i5-9300H CPU @ 2.40GHz       | 3         | 0.98%   |
| Intel Core i3-5005U CPU @ 2.00GHz       | 3         | 0.98%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 3         | 0.98%   |
| AMD Ryzen 7 5800X 8-Core Processor      | 3         | 0.98%   |
| AMD Ryzen 5 5600H with Radeon Graphics  | 3         | 0.98%   |
| AMD Ryzen 5 5600G with Radeon Graphics  | 3         | 0.98%   |
| AMD Ryzen 5 3600X 6-Core Processor      | 3         | 0.98%   |
| AMD Ryzen 5 3600 6-Core Processor       | 3         | 0.98%   |
| Intel Pentium CPU 4415U @ 2.30GHz       | 2         | 0.65%   |
| Intel Core i7-7600U CPU @ 2.80GHz       | 2         | 0.65%   |
| Intel Core i7-4790K CPU @ 4.00GHz       | 2         | 0.65%   |
| Intel Core i7-4712HQ CPU @ 2.30GHz      | 2         | 0.65%   |
| Intel Core i7-3720QM CPU @ 2.60GHz      | 2         | 0.65%   |
| Intel Core i7 CPU 870 @ 2.93GHz         | 2         | 0.65%   |
| Intel Core i7 CPU 860 @ 2.80GHz         | 2         | 0.65%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 2         | 0.65%   |
| Intel Core i5-6500 CPU @ 3.20GHz        | 2         | 0.65%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 2         | 0.65%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 2         | 0.65%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 2         | 0.65%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 2         | 0.65%   |
| Intel Core i3-8100 CPU @ 3.60GHz        | 2         | 0.65%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 71        | 23.2%   |
| Intel Core i7           | 66        | 21.57%  |
| Other                   | 37        | 12.09%  |
| AMD Ryzen 5             | 37        | 12.09%  |
| Intel Core i3           | 25        | 8.17%   |
| AMD Ryzen 7             | 20        | 6.54%   |
| Intel Xeon              | 6         | 1.96%   |
| Intel Core 2 Duo        | 6         | 1.96%   |
| AMD Ryzen 3             | 6         | 1.96%   |
| Intel Pentium           | 5         | 1.63%   |
| Intel Celeron           | 5         | 1.63%   |
| AMD Ryzen 9             | 2         | 0.65%   |
| AMD FX                  | 2         | 0.65%   |
| AMD E1                  | 2         | 0.65%   |
| AMD Athlon              | 2         | 0.65%   |
| AMD A8                  | 2         | 0.65%   |
| AMD A4                  | 2         | 0.65%   |
| Intel Pentium Silver    | 1         | 0.33%   |
| Intel Pentium Dual-Core | 1         | 0.33%   |
| Intel Genuine           | 1         | 0.33%   |
| Intel Core M            | 1         | 0.33%   |
| Intel Core i9           | 1         | 0.33%   |
| Intel Core 2 Quad       | 1         | 0.33%   |
| AMD Ryzen Threadripper  | 1         | 0.33%   |
| AMD Athlon II X3        | 1         | 0.33%   |
| AMD A6                  | 1         | 0.33%   |
| AMD A12                 | 1         | 0.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 115       | 37.58%  |
| 2      | 98        | 32.03%  |
| 6      | 49        | 16.01%  |
| 8      | 26        | 8.5%    |
| 16     | 5         | 1.63%   |
| 12     | 5         | 1.63%   |
| 10     | 3         | 0.98%   |
| 24     | 2         | 0.65%   |
| 3      | 2         | 0.65%   |
| 14     | 1         | 0.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 304       | 99.67%  |
| 2      | 1         | 0.33%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 252       | 82.35%  |
| 1      | 54        | 17.65%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 305       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 166       | 53.38%  |
| 0x906ea    | 8         | 2.57%   |
| 0x08108109 | 8         | 2.57%   |
| 0x806c1    | 7         | 2.25%   |
| 0x806ec    | 6         | 1.93%   |
| 0x506e3    | 6         | 1.93%   |
| 0x306a9    | 6         | 1.93%   |
| 0x08701021 | 6         | 1.93%   |
| 0x806e9    | 5         | 1.61%   |
| 0x906e9    | 4         | 1.29%   |
| 0x306c3    | 4         | 1.29%   |
| 0x0a50000c | 4         | 1.29%   |
| 0x0a201016 | 4         | 1.29%   |
| 0x806eb    | 3         | 0.96%   |
| 0x206a7    | 3         | 0.96%   |
| 0x0a50000d | 3         | 0.96%   |
| 0x0a404102 | 3         | 0.96%   |
| 0x0a20120a | 3         | 0.96%   |
| 0x0a201025 | 3         | 0.96%   |
| 0x08701030 | 3         | 0.96%   |
| 0x08608103 | 3         | 0.96%   |
| 0x08600106 | 3         | 0.96%   |
| 0x0810100b | 3         | 0.96%   |
| 0x906ed    | 2         | 0.64%   |
| 0x906eb    | 2         | 0.64%   |
| 0x706a8    | 2         | 0.64%   |
| 0x40651    | 2         | 0.64%   |
| 0x106e5    | 2         | 0.64%   |
| 0x1067a    | 2         | 0.64%   |
| 0x08108102 | 2         | 0.64%   |
| 0x06006705 | 2         | 0.64%   |
| 0x0600611a | 2         | 0.64%   |
| 0x0500010d | 2         | 0.64%   |
| 0xb0671    | 1         | 0.32%   |
| 0xa0653    | 1         | 0.32%   |
| 0xa0652    | 1         | 0.32%   |
| 0x906a3    | 1         | 0.32%   |
| 0x806d1    | 1         | 0.32%   |
| 0x706e5    | 1         | 0.32%   |
| 0x406e3    | 1         | 0.32%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 65        | 21.24%  |
| Haswell          | 29        | 9.48%   |
| Zen 3            | 22        | 7.19%   |
| TigerLake        | 19        | 6.21%   |
| IvyBridge        | 18        | 5.88%   |
| Zen 2            | 17        | 5.56%   |
| SandyBridge      | 15        | 4.9%    |
| Zen+             | 14        | 4.58%   |
| Skylake          | 14        | 4.58%   |
| Broadwell        | 14        | 4.58%   |
| IceLake          | 12        | 3.92%   |
| Alderlake Hybrid | 10        | 3.27%   |
| Unknown          | 10        | 3.27%   |
| Penryn           | 8         | 2.61%   |
| Zen              | 6         | 1.96%   |
| CometLake        | 6         | 1.96%   |
| Goldmont plus    | 5         | 1.63%   |
| Westmere         | 4         | 1.31%   |
| Nehalem          | 4         | 1.31%   |
| Excavator        | 4         | 1.31%   |
| Piledriver       | 3         | 0.98%   |
| Bobcat           | 2         | 0.65%   |
| Tremont          | 1         | 0.33%   |
| K10 Llano        | 1         | 0.33%   |
| K10              | 1         | 0.33%   |
| Jaguar           | 1         | 0.33%   |
| Gracemont        | 1         | 0.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 176       | 45.95%  |
| Nvidia            | 127       | 33.16%  |
| AMD               | 79        | 20.63%  |
| ASPEED Technology | 1         | 0.26%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 12        | 3.1%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 12        | 3.1%    |
| Intel UHD Graphics 620                                                      | 11        | 2.84%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 11        | 2.84%   |
| Intel HD Graphics 620                                                       | 9         | 2.33%   |
| Intel HD Graphics 5500                                                      | 9         | 2.33%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 9         | 2.33%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 8         | 2.07%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 8         | 2.07%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 7         | 1.81%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 7         | 1.81%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                   | 7         | 1.81%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                      | 7         | 1.81%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 7         | 1.81%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 6         | 1.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 6         | 1.55%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 6         | 1.55%   |
| AMD Renoir                                                                  | 6         | 1.55%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 6         | 1.55%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 5         | 1.29%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 5         | 1.29%   |
| Intel HD Graphics 630                                                       | 5         | 1.29%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 5         | 1.29%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 5         | 1.29%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 5         | 1.29%   |
| Nvidia GP108M [GeForce MX150]                                               | 4         | 1.03%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 4         | 1.03%   |
| Nvidia GM108M [GeForce 940MX]                                               | 4         | 1.03%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 4         | 1.03%   |
| Intel Core Processor Integrated Graphics Controller                         | 4         | 1.03%   |
| AMD Rembrandt [Radeon 680M]                                                 | 4         | 1.03%   |
| AMD Polaris 20 XL [Radeon RX 580 2048SP]                                    | 4         | 1.03%   |
| AMD Lucienne                                                                | 4         | 1.03%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 3         | 0.78%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 3         | 0.78%   |
| Nvidia GP108M [GeForce MX250]                                               | 3         | 0.78%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 3         | 0.78%   |
| Nvidia GK107GLM [Quadro K1100M]                                             | 3         | 0.78%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 3         | 0.78%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 3         | 0.78%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 105       | 34.31%  |
| 1 x AMD         | 62        | 20.26%  |
| Intel + Nvidia  | 60        | 19.61%  |
| 1 x Nvidia      | 56        | 18.3%   |
| AMD + Nvidia    | 9         | 2.94%   |
| Intel + AMD     | 6         | 1.96%   |
| 2 x Intel       | 4         | 1.31%   |
| 2 x AMD         | 2         | 0.65%   |
| 2 x Nvidia      | 1         | 0.33%   |
| Nvidia + ASPEED | 1         | 0.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 241       | 78.25%  |
| Proprietary | 64        | 20.78%  |
| Unknown     | 3         | 0.97%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 164       | 53.25%  |
| 1.01-2.0   | 38        | 12.34%  |
| 7.01-8.0   | 28        | 9.09%   |
| 0.01-0.5   | 24        | 7.79%   |
| 3.01-4.0   | 23        | 7.47%   |
| 5.01-6.0   | 13        | 4.22%   |
| 2.01-3.0   | 6         | 1.95%   |
| 8.01-16.0  | 6         | 1.95%   |
| 0.51-1.0   | 4         | 1.3%    |
| 16.01-24.0 | 2         | 0.65%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 48        | 14.2%   |
| Samsung Electronics     | 45        | 13.31%  |
| AU Optronics            | 39        | 11.54%  |
| Chimei Innolux          | 35        | 10.36%  |
| LG Display              | 24        | 7.1%    |
| Hewlett-Packard         | 16        | 4.73%   |
| Goldstar                | 16        | 4.73%   |
| Apple                   | 12        | 3.55%   |
| Acer                    | 9         | 2.66%   |
| Dell                    | 8         | 2.37%   |
| BenQ                    | 8         | 2.37%   |
| Sharp                   | 6         | 1.78%   |
| Lenovo                  | 5         | 1.48%   |
| AOC                     | 5         | 1.48%   |
| Ancor Communications    | 5         | 1.48%   |
| Philips                 | 4         | 1.18%   |
| PANDA                   | 4         | 1.18%   |
| Iiyama                  | 4         | 1.18%   |
| ASUSTek Computer        | 4         | 1.18%   |
| Unknown                 | 3         | 0.89%   |
| Sony                    | 3         | 0.89%   |
| MSI                     | 3         | 0.89%   |
| Chi Mei Optoelectronics | 3         | 0.89%   |
| TMX                     | 2         | 0.59%   |
| HKC                     | 2         | 0.59%   |
| Gigabyte Technology     | 2         | 0.59%   |
| Unknown                 | 2         | 0.59%   |
| Yeyian                  | 1         | 0.3%    |
| Yamaha                  | 1         | 0.3%    |
| Westinghouse            | 1         | 0.3%    |
| Vizio                   | 1         | 0.3%    |
| UTV                     | 1         | 0.3%    |
| Toshiba                 | 1         | 0.3%    |
| Sceptre Tech            | 1         | 0.3%    |
| QIA                     | 1         | 0.3%    |
| LGD                     | 1         | 0.3%    |
| Konka                   | 1         | 0.3%    |
| Kogan                   | 1         | 0.3%    |
| KOC                     | 1         | 0.3%    |
| KDB                     | 1         | 0.3%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 4         | 1.15%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                       | 3         | 0.86%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch         | 3         | 0.86%   |
| BOE LCD Monitor BOE084E 1920x1080 382x215mm 17.3-inch                   | 3         | 0.86%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch               | 2         | 0.58%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch       | 2         | 0.58%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 2         | 0.58%   |
| Samsung Electronics LCD Monitor SAM0F14 3840x2160 1872x1053mm 84.6-inch | 2         | 0.58%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 2         | 0.58%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch            | 2         | 0.58%   |
| Goldstar ULTRAGEAR GSM7766 2560x1440 697x392mm 31.5-inch                | 2         | 0.58%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                   | 2         | 0.58%   |
| Goldstar FULL HD GSM5BDE 1920x1080 480x270mm 21.7-inch                  | 2         | 0.58%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 2         | 0.58%   |
| Dell S3221QS DELD107 3840x2160 697x392mm 31.5-inch                      | 2         | 0.58%   |
| Chimei Innolux P130ZDZ-EF1 CMN8201 2160x1440 275x183mm 13.0-inch        | 2         | 0.58%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch         | 2         | 0.58%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch        | 2         | 0.58%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch        | 2         | 0.58%   |
| BOE LCD Monitor BOE0A81 1920x1080 344x194mm 15.5-inch                   | 2         | 0.58%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                   | 2         | 0.58%   |
| BOE LCD Monitor BOE0816 1366x768 344x193mm 15.5-inch                    | 2         | 0.58%   |
| BOE LCD Monitor BOE0704 1366x768 344x194mm 15.5-inch                    | 2         | 0.58%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                   | 2         | 0.58%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch          | 2         | 0.58%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch           | 2         | 0.58%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch           | 2         | 0.58%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch          | 2         | 0.58%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch           | 2         | 0.58%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch          | 2         | 0.58%   |
| Apple Color LCD APPA022 2880x1800 331x207mm 15.4-inch                   | 2         | 0.58%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                    | 2         | 0.58%   |
| Unknown                                                                 | 2         | 0.58%   |
| Yeyian YMC-70102 YEY2700 1920x1080 698x393mm 31.5-inch                  | 1         | 0.29%   |
| Yamaha RX-V473 YMH3171 1920x540                                         | 1         | 0.29%   |
| Westinghouse SK-32H640G WDE6040 1366x768 709x399mm 32.0-inch            | 1         | 0.29%   |
| Vizio E320-A0 VIZ0095 1366x768 697x392mm 31.5-inch                      | 1         | 0.29%   |
| UTV Monitor UTV002F 3840x2160 1872x1053mm 84.6-inch                     | 1         | 0.29%   |
| Unknown LCD Monitor SAMSUNG 1360x768                                    | 1         | 0.29%   |
| Toshiba TV TSB0205 1360x768 886x498mm 40.0-inch                         | 1         | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 169       | 52%     |
| 1366x768 (WXGA)    | 52        | 16%     |
| 3840x2160 (4K)     | 25        | 7.69%   |
| 2560x1440 (QHD)    | 15        | 4.62%   |
| 3440x1440          | 9         | 2.77%   |
| 1600x900 (HD+)     | 8         | 2.46%   |
| 1680x1050 (WSXGA+) | 5         | 1.54%   |
| 1280x800 (WXGA)    | 5         | 1.54%   |
| 2560x1600          | 4         | 1.23%   |
| 2560x1080          | 4         | 1.23%   |
| 2160x1440          | 3         | 0.92%   |
| 1920x1200 (WUXGA)  | 3         | 0.92%   |
| 1440x900 (WXGA+)   | 3         | 0.92%   |
| 1360x768           | 3         | 0.92%   |
| 3840x1080          | 2         | 0.62%   |
| 3200x1800 (QHD+)   | 2         | 0.62%   |
| 2880x1800          | 2         | 0.62%   |
| 2288x1287          | 2         | 0.62%   |
| 1920x540           | 2         | 0.62%   |
| 1280x1024 (SXGA)   | 2         | 0.62%   |
| 3840x2400          | 1         | 0.31%   |
| 3200x2000          | 1         | 0.31%   |
| 2736x1824          | 1         | 0.31%   |
| 1280x720 (HD)      | 1         | 0.31%   |
| Unknown            | 1         | 0.31%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 100       | 29.33%  |
| 13      | 35        | 10.26%  |
| 14      | 27        | 7.92%   |
| 27      | 26        | 7.62%   |
| 24      | 23        | 6.74%   |
| 23      | 21        | 6.16%   |
| 21      | 21        | 6.16%   |
| 31      | 14        | 4.11%   |
| 17      | 12        | 3.52%   |
| 34      | 10        | 2.93%   |
| Unknown | 9         | 2.64%   |
| 84      | 6         | 1.76%   |
| 16      | 4         | 1.17%   |
| 28      | 3         | 0.88%   |
| 18      | 3         | 0.88%   |
| 12      | 3         | 0.88%   |
| 142     | 2         | 0.59%   |
| 72      | 2         | 0.59%   |
| 54      | 2         | 0.59%   |
| 32      | 2         | 0.59%   |
| 20      | 2         | 0.59%   |
| 19      | 2         | 0.59%   |
| 58      | 1         | 0.29%   |
| 52      | 1         | 0.29%   |
| 48      | 1         | 0.29%   |
| 46      | 1         | 0.29%   |
| 41      | 1         | 0.29%   |
| 40      | 1         | 0.29%   |
| 35      | 1         | 0.29%   |
| 33      | 1         | 0.29%   |
| 29      | 1         | 0.29%   |
| 26      | 1         | 0.29%   |
| 22      | 1         | 0.29%   |
| 11      | 1         | 0.29%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 146       | 43.32%  |
| 501-600        | 64        | 18.99%  |
| 401-500        | 29        | 8.61%   |
| 201-300        | 21        | 6.23%   |
| 601-700        | 19        | 5.64%   |
| 351-400        | 17        | 5.04%   |
| 701-800        | 13        | 3.86%   |
| Unknown        | 9         | 2.67%   |
| 1501-2000      | 8         | 2.37%   |
| 1001-1500      | 6         | 1.78%   |
| More than 2000 | 2         | 0.59%   |
| 801-900        | 2         | 0.59%   |
| 901-1000       | 1         | 0.3%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 254       | 83.01%  |
| 16/10   | 23        | 7.52%   |
| 21/9    | 13        | 4.25%   |
| Unknown | 6         | 1.96%   |
| 3/2     | 4         | 1.31%   |
| 5/4     | 2         | 0.65%   |
| 32/9    | 2         | 0.65%   |
| 1.00    | 2         | 0.65%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 102       | 30.18%  |
| 201-250        | 55        | 16.27%  |
| 81-90          | 51        | 15.09%  |
| 351-500        | 30        | 8.88%   |
| 301-350        | 26        | 7.69%   |
| More than 1000 | 14        | 4.14%   |
| 71-80          | 12        | 3.55%   |
| 121-130        | 12        | 3.55%   |
| 151-200        | 10        | 2.96%   |
| Unknown        | 9         | 2.66%   |
| 251-300        | 6         | 1.78%   |
| 501-1000       | 4         | 1.18%   |
| 61-70          | 2         | 0.59%   |
| 141-150        | 2         | 0.59%   |
| 111-120        | 2         | 0.59%   |
| 51-60          | 1         | 0.3%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 112       | 33.94%  |
| 101-120       | 85        | 25.76%  |
| 51-100        | 85        | 25.76%  |
| 161-240       | 18        | 5.45%   |
| 1-50          | 12        | 3.64%   |
| More than 240 | 9         | 2.73%   |
| Unknown       | 9         | 2.73%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 253       | 82.41%  |
| 2     | 47        | 15.31%  |
| 3     | 4         | 1.3%    |
| 0     | 3         | 0.98%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 170       | 37.69%  |
| Intel                             | 159       | 35.25%  |
| Qualcomm Atheros                  | 39        | 8.65%   |
| Broadcom                          | 19        | 4.21%   |
| MediaTek                          | 11        | 2.44%   |
| Broadcom Limited                  | 10        | 2.22%   |
| TP-Link                           | 4         | 0.89%   |
| Ralink Technology                 | 4         | 0.89%   |
| Ralink                            | 4         | 0.89%   |
| Qualcomm                          | 3         | 0.67%   |
| Marvell Technology Group          | 3         | 0.67%   |
| ASIX Electronics                  | 3         | 0.67%   |
| Aquantia                          | 3         | 0.67%   |
| Sierra Wireless                   | 2         | 0.44%   |
| Samsung Electronics               | 2         | 0.44%   |
| OPPO Electronics                  | 2         | 0.44%   |
| Nvidia                            | 2         | 0.44%   |
| Ericsson Business Mobile Networks | 2         | 0.44%   |
| T & A Mobile Phones               | 1         | 0.22%   |
| Qualcomm Atheros Communications   | 1         | 0.22%   |
| QinHeng Electronics               | 1         | 0.22%   |
| NetGear                           | 1         | 0.22%   |
| Microsoft                         | 1         | 0.22%   |
| Huawei Technologies               | 1         | 0.22%   |
| DisplayLink                       | 1         | 0.22%   |
| Dell                              | 1         | 0.22%   |
| ASUSTek Computer                  | 1         | 0.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 116       | 21.52%  |
| Intel Wi-Fi 6 AX201                                               | 15        | 2.78%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 14        | 2.6%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 13        | 2.41%   |
| Realtek RTL8125 2.5GbE Controller                                 | 13        | 2.41%   |
| Intel Wi-Fi 6 AX200                                               | 13        | 2.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 13        | 2.41%   |
| Intel Wireless 8265 / 8275                                        | 12        | 2.23%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 1.86%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 9         | 1.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 9         | 1.67%   |
| Intel Wireless 7265                                               | 9         | 1.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 9         | 1.67%   |
| Intel I211 Gigabit Network Connection                             | 8         | 1.48%   |
| Intel Ethernet Controller I225-V                                  | 8         | 1.48%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 7         | 1.3%    |
| Intel Wireless 7260                                               | 7         | 1.3%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 7         | 1.3%    |
| Intel Ethernet Connection (2) I219-V                              | 7         | 1.3%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 6         | 1.11%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 6         | 1.11%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 6         | 1.11%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 5         | 0.93%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 4         | 0.74%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 0.74%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 4         | 0.74%   |
| Intel Centrino Wireless-N 2230                                    | 4         | 0.74%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 0.74%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 4         | 0.74%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 0.74%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 4         | 0.74%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 4         | 0.74%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 4         | 0.74%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 3         | 0.56%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.56%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 0.56%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 0.56%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 3         | 0.56%   |
| Intel Wireless 8260                                               | 3         | 0.56%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 132       | 50.19%  |
| Realtek Semiconductor           | 46        | 17.49%  |
| Qualcomm Atheros                | 30        | 11.41%  |
| Broadcom                        | 14        | 5.32%   |
| MediaTek                        | 11        | 4.18%   |
| Broadcom Limited                | 9         | 3.42%   |
| TP-Link                         | 4         | 1.52%   |
| Ralink Technology               | 4         | 1.52%   |
| Ralink                          | 4         | 1.52%   |
| Sierra Wireless                 | 2         | 0.76%   |
| Marvell Technology Group        | 2         | 0.76%   |
| Qualcomm Atheros Communications | 1         | 0.38%   |
| NetGear                         | 1         | 0.38%   |
| Microsoft                       | 1         | 0.38%   |
| Dell                            | 1         | 0.38%   |
| ASUSTek Computer                | 1         | 0.38%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                            | 15        | 5.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 14        | 5.32%   |
| Intel Wi-Fi 6 AX200                                            | 13        | 4.94%   |
| Intel Wireless 8265 / 8275                                     | 12        | 4.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 9         | 3.42%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 9         | 3.42%   |
| Intel Wireless 7265                                            | 9         | 3.42%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 9         | 3.42%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 7         | 2.66%   |
| Intel Wireless 7260                                            | 7         | 2.66%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 7         | 2.66%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 6         | 2.28%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 6         | 2.28%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 6         | 2.28%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 5         | 1.9%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 4         | 1.52%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 4         | 1.52%   |
| Intel Centrino Wireless-N 2230                                 | 4         | 1.52%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 1.52%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 4         | 1.52%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 4         | 1.52%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 4         | 1.52%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 3         | 1.14%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 3         | 1.14%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 3         | 1.14%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 3         | 1.14%   |
| Intel Wireless 8260                                            | 3         | 1.14%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter     | 3         | 1.14%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 3         | 1.14%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 2         | 0.76%   |
| Sierra Wireless EM7455                                         | 2         | 0.76%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 2         | 0.76%   |
| Realtek 802.11ac NIC                                           | 2         | 0.76%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 2         | 0.76%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 2         | 0.76%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 0.76%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 2         | 0.76%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 0.76%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 2         | 0.76%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 0.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 150       | 56.39%  |
| Intel                    | 74        | 27.82%  |
| Qualcomm Atheros         | 13        | 4.89%   |
| Broadcom                 | 10        | 3.76%   |
| Qualcomm                 | 3         | 1.13%   |
| ASIX Electronics         | 3         | 1.13%   |
| Aquantia                 | 3         | 1.13%   |
| Samsung Electronics      | 2         | 0.75%   |
| OPPO Electronics         | 2         | 0.75%   |
| Nvidia                   | 2         | 0.75%   |
| Marvell Technology Group | 1         | 0.38%   |
| Huawei Technologies      | 1         | 0.38%   |
| DisplayLink              | 1         | 0.38%   |
| Broadcom Limited         | 1         | 0.38%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                              | Computers | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller  | 116       | 42.65%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                           | 13        | 4.78%   |
| Realtek RTL8125 2.5GbE Controller                                  | 13        | 4.78%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)              | 13        | 4.78%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller              | 10        | 3.68%   |
| Intel I211 Gigabit Network Connection                              | 8         | 2.94%   |
| Intel Ethernet Controller I225-V                                   | 8         | 2.94%   |
| Intel Ethernet Connection (2) I219-V                               | 7         | 2.57%   |
| Intel Ethernet Connection (4) I219-LM                              | 4         | 1.47%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                  | 4         | 1.47%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                    | 4         | 1.47%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller          | 3         | 1.1%    |
| Intel Ethernet Connection I217-LM                                  | 3         | 1.1%    |
| ASIX AX88179 Gigabit Ethernet                                      | 3         | 1.1%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)        | 2         | 0.74%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                   | 2         | 0.74%   |
| Qualcomm POCO M2 Pro                                               | 2         | 0.74%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller          | 2         | 0.74%   |
| OPPO 8                                                             | 2         | 0.74%   |
| Intel Ethernet Connection I218-LM                                  | 2         | 0.74%   |
| Intel Ethernet Connection (7) I219-V                               | 2         | 0.74%   |
| Intel Ethernet Connection (5) I219-LM                              | 2         | 0.74%   |
| Intel Ethernet Connection (3) I218-V                               | 2         | 0.74%   |
| Intel Ethernet Connection (2) I219-LM                              | 2         | 0.74%   |
| Intel Ethernet Connection (13) I219-V                              | 2         | 0.74%   |
| Intel Ethernet Connection (11) I219-V                              | 2         | 0.74%   |
| Aquantia AQC113C NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2         | 0.74%   |
| Realtek RTL8152 Fast Ethernet Adapter                              | 1         | 0.37%   |
| Qualcomm Redmi Note 8                                              | 1         | 0.37%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                          | 1         | 0.37%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller          | 1         | 0.37%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                           | 1         | 0.37%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                         | 1         | 0.37%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                      | 1         | 0.37%   |
| Qualcomm Atheros AR8132 Fast Ethernet                              | 1         | 0.37%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                           | 1         | 0.37%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet     | 1         | 0.37%   |
| Nvidia MCP89 Ethernet                                              | 1         | 0.37%   |
| Nvidia MCP79 Ethernet                                              | 1         | 0.37%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller               | 1         | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 251       | 49.9%   |
| Ethernet | 248       | 49.3%   |
| Modem    | 4         | 0.8%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 175       | 57%     |
| Ethernet | 132       | 43%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 162       | 52.77%  |
| 1     | 134       | 43.65%  |
| 3     | 8         | 2.61%   |
| 8     | 1         | 0.33%   |
| 4     | 1         | 0.33%   |
| 0     | 1         | 0.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 206       | 67.32%  |
| Yes  | 100       | 32.68%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 118       | 49.79%  |
| Realtek Semiconductor           | 27        | 11.39%  |
| IMC Networks                    | 14        | 5.91%   |
| Qualcomm Atheros Communications | 13        | 5.49%   |
| Cambridge Silicon Radio         | 12        | 5.06%   |
| Apple                           | 12        | 5.06%   |
| Broadcom                        | 9         | 3.8%    |
| Lite-On Technology              | 7         | 2.95%   |
| Foxconn / Hon Hai               | 6         | 2.53%   |
| ASUSTek Computer                | 5         | 2.11%   |
| TP-Link                         | 3         | 1.27%   |
| Realtek                         | 3         | 1.27%   |
| MediaTek                        | 3         | 1.27%   |
| Marvell Semiconductor           | 2         | 0.84%   |
| Toshiba                         | 1         | 0.42%   |
| Dell                            | 1         | 0.42%   |
| Alps Electric                   | 1         | 0.42%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 32        | 13.5%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 28        | 11.81%  |
| Intel AX201 Bluetooth                               | 22        | 9.28%   |
| Realtek Bluetooth Radio                             | 17        | 7.17%   |
| Intel AX200 Bluetooth                               | 13        | 5.49%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 12        | 5.06%   |
| Qualcomm Atheros  Bluetooth Device                  | 10        | 4.22%   |
| Realtek  Bluetooth 4.2 Adapter                      | 8         | 3.38%   |
| Intel AX210 Bluetooth                               | 7         | 2.95%   |
| Apple Bluetooth Host Controller                     | 7         | 2.95%   |
| Intel Wireless-AC 3168 Bluetooth                    | 6         | 2.53%   |
| IMC Networks Wireless_Device                        | 6         | 2.53%   |
| IMC Networks Bluetooth Radio                        | 5         | 2.11%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 1.69%   |
| Intel Bluetooth Device                              | 4         | 1.69%   |
| Apple Bluetooth USB Host Controller                 | 4         | 1.69%   |
| TP-Link UB5A Adapter                                | 3         | 1.27%   |
| Realtek Bluetooth Radio                             | 3         | 1.27%   |
| MediaTek Wireless_Device                            | 3         | 1.27%   |
| Lite-On Bluetooth Device                            | 3         | 1.27%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 0.84%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 0.84%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 0.84%   |
| IMC Networks BCM20702A0                             | 2         | 0.84%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 2         | 0.84%   |
| Broadcom BCM20702A0 Bluetooth                       | 2         | 0.84%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 0.84%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2         | 0.84%   |
| ASUS Bluetooth Radio                                | 2         | 0.84%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 0.42%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.42%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.42%   |
| Qualcomm Atheros Bluetooth (AR3011)                 | 1         | 0.42%   |
| Marvell Bluetooth and Wireless LAN Composite Device | 1         | 0.42%   |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 0.42%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 0.42%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.42%   |
| IMC Networks Bluetooth Device                       | 1         | 0.42%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 0.42%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth     | 1         | 0.42%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 224       | 48.91%  |
| Nvidia                                       | 90        | 19.65%  |
| AMD                                          | 89        | 19.43%  |
| C-Media Electronics                          | 8         | 1.75%   |
| Corsair                                      | 4         | 0.87%   |
| ASUSTek Computer                             | 4         | 0.87%   |
| Kingston Technology                          | 3         | 0.66%   |
| GN Netcom                                    | 3         | 0.66%   |
| Generalplus Technology                       | 3         | 0.66%   |
| Realtek Semiconductor                        | 2         | 0.44%   |
| Razer USA                                    | 2         | 0.44%   |
| PreSonus Audio Electronics                   | 2         | 0.44%   |
| Logitech                                     | 2         | 0.44%   |
| JMTek                                        | 2         | 0.44%   |
| Elgato Systems                               | 2         | 0.44%   |
| Barco Display Systems                        | 2         | 0.44%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.22%   |
| Trust                                        | 1         | 0.22%   |
| Tenx Technology                              | 1         | 0.22%   |
| TC Electronic                                | 1         | 0.22%   |
| Soundprese                                   | 1         | 0.22%   |
| Samsung Electronics                          | 1         | 0.22%   |
| Plantronics                                  | 1         | 0.22%   |
| Lenovo                                       | 1         | 0.22%   |
| JBL                                          | 1         | 0.22%   |
| Hewlett-Packard                              | 1         | 0.22%   |
| fifine Microphone                            | 1         | 0.22%   |
| ELMCU                                        | 1         | 0.22%   |
| Digidesign                                   | 1         | 0.22%   |
| BR23                                         | 1         | 0.22%   |
| Astro Gaming                                 | 1         | 0.22%   |
| Arturia                                      | 1         | 0.22%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 39        | 7.05%   |
| Intel Sunrise Point-LP HD Audio                                            | 26        | 4.7%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 19        | 3.44%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 19        | 3.44%   |
| AMD Starship/Matisse HD Audio Controller                                   | 19        | 3.44%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 19        | 3.44%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 16        | 2.89%   |
| Intel Cannon Lake PCH cAVS                                                 | 14        | 2.53%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 13        | 2.35%   |
| Intel Broadwell-U Audio Controller                                         | 13        | 2.35%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 13        | 2.35%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 12        | 2.17%   |
| Intel 200 Series PCH HD Audio                                              | 11        | 1.99%   |
| Nvidia GP104 High Definition Audio Controller                              | 10        | 1.81%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 10        | 1.81%   |
| Intel Haswell-ULT HD Audio Controller                                      | 10        | 1.81%   |
| Intel 8 Series HD Audio Controller                                         | 10        | 1.81%   |
| Nvidia GP107GL High Definition Audio Controller                            | 9         | 1.63%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 9         | 1.63%   |
| Nvidia TU116 High Definition Audio Controller                              | 8         | 1.45%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 8         | 1.45%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 8         | 1.45%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 8         | 1.45%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 7         | 1.27%   |
| Nvidia TU106 High Definition Audio Controller                              | 7         | 1.27%   |
| AMD Navi 10 HDMI Audio                                                     | 7         | 1.27%   |
| Intel Comet Lake PCH-LP cAVS                                               | 6         | 1.08%   |
| Intel CM238 HD Audio Controller                                            | 6         | 1.08%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 6         | 1.08%   |
| Nvidia GA106 High Definition Audio Controller                              | 5         | 0.9%    |
| Nvidia GA104 High Definition Audio Controller                              | 5         | 0.9%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 5         | 0.9%    |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 5         | 0.9%    |
| AMD FCH Azalia Controller                                                  | 5         | 0.9%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 5         | 0.9%    |
| Nvidia GP106 High Definition Audio Controller                              | 4         | 0.72%   |
| Nvidia GK107 HDMI Audio Controller                                         | 4         | 0.72%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 0.72%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 0.72%   |
| Intel Alder Lake-S HD Audio Controller                                     | 4         | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 72        | 21.36%  |
| SK hynix                     | 71        | 21.07%  |
| Micron Technology            | 36        | 10.68%  |
| Kingston                     | 29        | 8.61%   |
| Crucial                      | 25        | 7.42%   |
| G.Skill                      | 21        | 6.23%   |
| Corsair                      | 19        | 5.64%   |
| Unknown                      | 12        | 3.56%   |
| Ramaxel Technology           | 11        | 3.26%   |
| Team                         | 6         | 1.78%   |
| Elpida                       | 6         | 1.78%   |
| A-DATA Technology            | 6         | 1.78%   |
| Timetec                      | 2         | 0.59%   |
| PNY                          | 2         | 0.59%   |
| Patriot Memory (PDP Systems) | 2         | 0.59%   |
| KingFast                     | 2         | 0.59%   |
| GOODRAM                      | 2         | 0.59%   |
| Unifosa                      | 1         | 0.3%    |
| Transcend                    | 1         | 0.3%    |
| Smart Brazil                 | 1         | 0.3%    |
| Smart                        | 1         | 0.3%    |
| Silicon Power                | 1         | 0.3%    |
| Patriot                      | 1         | 0.3%    |
| Nanya Technology             | 1         | 0.3%    |
| Kllisre                      | 1         | 0.3%    |
| Kimtigo                      | 1         | 0.3%    |
| Juhor                        | 1         | 0.3%    |
| Heoriady                     | 1         | 0.3%    |
| Goldkey                      | 1         | 0.3%    |
| GeIL                         | 1         | 0.3%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 7         | 1.97%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 6         | 1.69%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 6         | 1.69%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 5         | 1.41%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 5         | 1.41%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 4         | 1.13%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s      | 4         | 1.13%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.85%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 0.85%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.85%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.85%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.85%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 0.85%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.85%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.85%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s               | 2         | 0.56%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 2         | 0.56%   |
| SK hynix RAM HMT451S6MFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 0.56%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.56%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.56%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.56%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 0.56%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 0.56%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 2         | 0.56%   |
| SK hynix RAM HMA81GS6DJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.56%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.56%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s | 2         | 0.56%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.56%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 2         | 0.56%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.56%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.56%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.56%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s              | 2         | 0.56%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s              | 2         | 0.56%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s              | 2         | 0.56%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 2         | 0.56%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 2         | 0.56%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s              | 2         | 0.56%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.56%   |
| Micron RAM 4ATF51264HZ-2G3E1 4GB SODIMM DDR4 2667MT/s            | 2         | 0.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 167       | 59.22%  |
| DDR3    | 79        | 28.01%  |
| DDR5    | 10        | 3.55%   |
| LPDDR4  | 6         | 2.13%   |
| LPDDR3  | 6         | 2.13%   |
| LPDDR5  | 4         | 1.42%   |
| DDR2    | 4         | 1.42%   |
| SDRAM   | 3         | 1.06%   |
| DDR     | 2         | 0.71%   |
| Unknown | 1         | 0.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 165       | 57.69%  |
| DIMM         | 95        | 33.22%  |
| Row Of Chips | 23        | 8.04%   |
| Chip         | 3         | 1.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 132       | 42.31%  |
| 4096  | 97        | 31.09%  |
| 16384 | 54        | 17.31%  |
| 2048  | 20        | 6.41%   |
| 32768 | 8         | 2.56%   |
| 1024  | 1         | 0.32%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 63        | 20.13%  |
| 3200    | 60        | 19.17%  |
| 1600    | 52        | 16.61%  |
| 2400    | 20        | 6.39%   |
| 1333    | 16        | 5.11%   |
| 3600    | 14        | 4.47%   |
| 2133    | 13        | 4.15%   |
| 3266    | 6         | 1.92%   |
| 6400    | 5         | 1.6%    |
| 4800    | 5         | 1.6%    |
| 2933    | 5         | 1.6%    |
| 1067    | 5         | 1.6%    |
| 1866    | 4         | 1.28%   |
| 3733    | 3         | 0.96%   |
| 1867    | 3         | 0.96%   |
| 1800    | 3         | 0.96%   |
| 1334    | 3         | 0.96%   |
| 800     | 3         | 0.96%   |
| 4267    | 2         | 0.64%   |
| 4199    | 2         | 0.64%   |
| 3800    | 2         | 0.64%   |
| 3400    | 2         | 0.64%   |
| 2666    | 2         | 0.64%   |
| 2176    | 2         | 0.64%   |
| 1066    | 2         | 0.64%   |
| Unknown | 2         | 0.64%   |
| 8400    | 1         | 0.32%   |
| 7000    | 1         | 0.32%   |
| 6000    | 1         | 0.32%   |
| 5800    | 1         | 0.32%   |
| 5600    | 1         | 0.32%   |
| 4400    | 1         | 0.32%   |
| 4133    | 1         | 0.32%   |
| 3467    | 1         | 0.32%   |
| 3000    | 1         | 0.32%   |
| 2747    | 1         | 0.32%   |
| 2134    | 1         | 0.32%   |
| 1648    | 1         | 0.32%   |
| 1450    | 1         | 0.32%   |
| 1400    | 1         | 0.32%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 2         | 50%     |
| Samsung Electronics | 1         | 25%     |
| Brother Industries  | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung ML-1640 Series Laser Printer | 1         | 25%     |
| HP DeskJet 2700 series               | 1         | 25%     |
| HP Deskjet 2050 J510                 | 1         | 25%     |
| Brother HL-5250DN Printer            | 1         | 25%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 200 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| IMC Networks                           | 39        | 19.6%   |
| Chicony Electronics                    | 37        | 18.59%  |
| Realtek Semiconductor                  | 16        | 8.04%   |
| Microdia                               | 15        | 7.54%   |
| Bison Electronics                      | 13        | 6.53%   |
| Sunplus Innovation Technology          | 11        | 5.53%   |
| Quanta                                 | 9         | 4.52%   |
| Apple                                  | 9         | 4.52%   |
| Syntek                                 | 7         | 3.52%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 3.02%   |
| Logitech                               | 5         | 2.51%   |
| Luxvisions Innotech Limited            | 4         | 2.01%   |
| Lite-On Technology                     | 4         | 2.01%   |
| Suyin                                  | 3         | 1.51%   |
| Acer                                   | 3         | 1.51%   |
| SunplusIT                              | 2         | 1.01%   |
| Ricoh                                  | 2         | 1.01%   |
| Generalplus Technology                 | 2         | 1.01%   |
| Creative Technology                    | 2         | 1.01%   |
| Sonix Technology                       | 1         | 0.5%    |
| Samsung Electronics                    | 1         | 0.5%    |
| Panasonic (Matsushita)                 | 1         | 0.5%    |
| OPPO Electronics                       | 1         | 0.5%    |
| Microsoft                              | 1         | 0.5%    |
| Intel                                  | 1         | 0.5%    |
| Aveo Technology                        | 1         | 0.5%    |
| Alpha Imaging Technology               | 1         | 0.5%    |
| ALi                                    | 1         | 0.5%    |
| Alcor Micro                            | 1         | 0.5%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                              | 12        | 5.97%   |
| Chicony Integrated Camera                                      | 10        | 4.98%   |
| IMC Networks Integrated Camera                                 | 9         | 4.48%   |
| Syntek Integrated Camera                                       | 7         | 3.48%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 7         | 3.48%   |
| Realtek Integrated_Webcam_HD                                   | 6         | 2.99%   |
| Quanta HP TrueVision HD Camera                                 | 5         | 2.49%   |
| Microdia Integrated_Webcam_HD                                  | 5         | 2.49%   |
| Lite-On Integrated Camera                                      | 4         | 1.99%   |
| IMC Networks HD Camera                                         | 4         | 1.99%   |
| Sunplus Integrated_Webcam_HD                                   | 3         | 1.49%   |
| Microdia Webcam Vitade AF                                      | 3         | 1.49%   |
| Chicony HP TrueVision HD Camera                                | 3         | 1.49%   |
| Chicony EasyCamera                                             | 3         | 1.49%   |
| Bison Lenovo Integrated Webcam                                 | 3         | 1.49%   |
| Bison HD Webcam                                                | 3         | 1.49%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                             | 3         | 1.49%   |
| Apple FaceTime HD Camera                                       | 3         | 1.49%   |
| Sunplus Laptop Integrated Webcam FHD                           | 2         | 1%      |
| Realtek USB2.0 HD UVC WebCam                                   | 2         | 1%      |
| Realtek Integrated Webcam_HD                                   | 2         | 1%      |
| Quanta HD User Facing                                          | 2         | 1%      |
| Microdia USB 2.0 Camera                                        | 2         | 1%      |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 2         | 1%      |
| Logitech BRIO                                                  | 2         | 1%      |
| IMC Networks VGA UVC WebCam                                    | 2         | 1%      |
| Creative Live! Cam Sync 1080p V2                               | 2         | 1%      |
| Chicony HP Webcam                                              | 2         | 1%      |
| Chicony HP High Definition 1MP Webcam                          | 2         | 1%      |
| Chicony HD WebCam                                              | 2         | 1%      |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 2         | 1%      |
| Bison ThinkPad Integrated Camera                               | 2         | 1%      |
| Bison SunplusIT Integrated Camera                              | 2         | 1%      |
| Apple Built-in iSight                                          | 2         | 1%      |
| Suyin Integrated_Webcam_HD                                     | 1         | 0.5%    |
| Suyin HD WebCam                                                | 1         | 0.5%    |
| Suyin Asus Integrated Webcam                                   | 1         | 0.5%    |
| SunplusIT XiaoMi USB 2.0 Webcam                                | 1         | 0.5%    |
| SunplusIT USB 2M Camera                                        | 1         | 0.5%    |
| Sunplus XiaoMi USB 2.0 Webcam                                  | 1         | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 10        | 33.33%  |
| Synaptics                  | 8         | 26.67%  |
| Shenzhen Goodix Technology | 6         | 20%     |
| Elan Microelectronics      | 3         | 10%     |
| AuthenTec                  | 2         | 6.67%   |
| LighTuning Technology      | 1         | 3.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                      | 4         | 13.33%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor        | 3         | 10%     |
| Validity Sensors Synaptics WBDI                          | 3         | 10%     |
| Synaptics  WBDI                                          | 3         | 10%     |
| Validity Sensors VFS 5011 fingerprint sensor             | 2         | 6.67%   |
| Shenzhen Goodix Fingerprint Reader                       | 2         | 6.67%   |
| Validity Sensors VFS5011 Fingerprint Reader              | 1         | 3.33%   |
| Validity Sensors VFS495 Fingerprint Reader               | 1         | 3.33%   |
| Synaptics WBDI                                           | 1         | 3.33%   |
| Synaptics UWP WBDI                                       | 1         | 3.33%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 1         | 3.33%   |
| Synaptics Metallica MIS Touch Fingerprint Reader         | 1         | 3.33%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 3.33%   |
| LighTuning Fingerprint Reader                            | 1         | 3.33%   |
| Elan WBF Fingerprint Sensor                              | 1         | 3.33%   |
| Elan fingerprint sensor [FeinTech FPS00200]              | 1         | 3.33%   |
| Elan ELAN:ARM-M4                                         | 1         | 3.33%   |
| AuthenTec Fingerprint Sensor                             | 1         | 3.33%   |
| AuthenTec AES2810                                        | 1         | 3.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 5         | 35.71%  |
| Alcor Micro | 5         | 35.71%  |
| Upek        | 2         | 14.29%  |
| Yubico.com  | 1         | 7.14%   |
| Clay Logic  | 1         | 7.14%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 5         | 35.71%  |
| Broadcom BCM5880 Secure Applications Processor             | 3         | 21.43%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 2         | 14.29%  |
| Yubico.com Yubikey NEO(-N) OTP+CCID                        | 1         | 7.14%   |
| Clay Logic Nitrokey Pro                                    | 1         | 7.14%   |
| Broadcom 5880                                              | 1         | 7.14%   |
| Broadcom 58200                                             | 1         | 7.14%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 235       | 76.55%  |
| 1     | 60        | 19.54%  |
| 2     | 11        | 3.58%   |
| 3     | 1         | 0.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 30        | 36.14%  |
| Graphics card         | 16        | 19.28%  |
| Chipcard              | 12        | 14.46%  |
| Multimedia controller | 7         | 8.43%   |
| Camera                | 5         | 6.02%   |
| Net/wireless          | 4         | 4.82%   |
| Unassigned class      | 3         | 3.61%   |
| Bluetooth             | 3         | 3.61%   |
| Storage               | 2         | 2.41%   |
| Network               | 1         | 1.2%    |

