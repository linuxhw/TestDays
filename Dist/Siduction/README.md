Siduction - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Siduction.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Siduction/Desktop/README.md) and [notebooks](/Dist/Siduction/Notebook/README.md).

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

Total: 124

| Vendor    | Model                       | Form-Factor | Probe                                                      | Date         |
|-----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell      | XPS 15 9530                 | Notebook    | [229fa2334e](https://linux-hardware.org/?probe=229fa2334e) | Dec 26, 2025 |
| TUXEDO    | Sirius 16 Gen1              | Notebook    | [d223301e3d](https://linux-hardware.org/?probe=d223301e3d) | Nov 14, 2025 |
| Framework | Laptop 13 (AMD Ryzen AI ... | Notebook    | [110a3ac514](https://linux-hardware.org/?probe=110a3ac514) | Nov 05, 2025 |
| Framework | Laptop 13 (AMD Ryzen AI ... | Notebook    | [6fc9ef0f2f](https://linux-hardware.org/?probe=6fc9ef0f2f) | Nov 05, 2025 |
| Dell      | Inspiron 7706 2n1           | Convertible | [573142d6ef](https://linux-hardware.org/?probe=573142d6ef) | Sep 09, 2025 |
| AWOW      | AK41                        | Notebook    | [3a5d47f28b](https://linux-hardware.org/?probe=3a5d47f28b) | Aug 21, 2025 |
| Acer      | Aspire A315-42              | Notebook    | [09f9cb0e93](https://linux-hardware.org/?probe=09f9cb0e93) | Aug 15, 2025 |
| AWOW      | AK41                        | Notebook    | [a21d56b682](https://linux-hardware.org/?probe=a21d56b682) | Aug 09, 2025 |
| Lenovo    | ThinkPad E14 Gen 4 21ECS... | Notebook    | [5003876656](https://linux-hardware.org/?probe=5003876656) | Jul 02, 2025 |
| MSI       | MPG B550 GAMING PLUS        | Desktop     | [cef3238f6a](https://linux-hardware.org/?probe=cef3238f6a) | Jun 16, 2025 |
| Dell      | 0VHXCD A01                  | Desktop     | [1081e3b3bf](https://linux-hardware.org/?probe=1081e3b3bf) | Mar 29, 2025 |
| ASUSTek   | ROG STRIX Z370-F GAMING     | Desktop     | [f817a23756](https://linux-hardware.org/?probe=f817a23756) | Feb 20, 2025 |
| MSI       | MPG B550 GAMING PLUS        | Desktop     | [aa6abc01e8](https://linux-hardware.org/?probe=aa6abc01e8) | Feb 18, 2025 |
| MSI       | X99A GODLIKE GAMING CARB... | Desktop     | [9eb4e174e0](https://linux-hardware.org/?probe=9eb4e174e0) | Feb 03, 2025 |
| HP        | ProBook 4540s               | Notebook    | [0646f227a6](https://linux-hardware.org/?probe=0646f227a6) | Jan 02, 2025 |
| ASUSTek   | VivoBook_ASUSLaptop X150... | Notebook    | [2c4e1abbf9](https://linux-hardware.org/?probe=2c4e1abbf9) | Nov 09, 2024 |
| Lenovo    | ThinkPad L590 20Q7001HGE    | Notebook    | [ec2225a1f3](https://linux-hardware.org/?probe=ec2225a1f3) | Oct 12, 2024 |
| Lenovo    | G50-30 80G0                 | Notebook    | [53798578b1](https://linux-hardware.org/?probe=53798578b1) | Jun 19, 2024 |
| HP        | 250 G7 Notebook PC          | Notebook    | [637ffca44b](https://linux-hardware.org/?probe=637ffca44b) | Jun 16, 2024 |
| Lenovo    | ThinkPad T14s Gen 1 20T1... | Notebook    | [3936c99d1e](https://linux-hardware.org/?probe=3936c99d1e) | Mar 25, 2024 |
| Lenovo    | ThinkPad T470 W10DG 20JN... | Notebook    | [df52747427](https://linux-hardware.org/?probe=df52747427) | Jan 22, 2024 |
| HP        | 250 G7 Notebook PC          | Notebook    | [3b58774e8d](https://linux-hardware.org/?probe=3b58774e8d) | Jan 15, 2024 |
| Lenovo    | ThinkPad T470 W10DG 20JN... | Notebook    | [d17724d57c](https://linux-hardware.org/?probe=d17724d57c) | Jan 11, 2024 |
| ASUSTek   | BU201LA                     | Notebook    | [2985f7a222](https://linux-hardware.org/?probe=2985f7a222) | Dec 22, 2023 |
| Lenovo    | ThinkPad T580 20LAS1GG00    | Notebook    | [c592d82494](https://linux-hardware.org/?probe=c592d82494) | Dec 05, 2023 |
| Lenovo    | ThinkPad L540 20AUS01H00    | Notebook    | [6bdb162853](https://linux-hardware.org/?probe=6bdb162853) | Nov 29, 2023 |
| Lenovo    | ThinkPad T490 20N3SFKX00    | Notebook    | [9d5bc38102](https://linux-hardware.org/?probe=9d5bc38102) | Nov 29, 2023 |
| HP        | 250 G7 Notebook PC          | Notebook    | [64d7d103a5](https://linux-hardware.org/?probe=64d7d103a5) | Oct 24, 2023 |
| HP        | 250 G7 Notebook PC          | Notebook    | [91d0aa5397](https://linux-hardware.org/?probe=91d0aa5397) | Oct 10, 2023 |
| HP        | 250 G7 Notebook PC          | Notebook    | [c2123c4f21](https://linux-hardware.org/?probe=c2123c4f21) | Oct 10, 2023 |
| Dell      | 0KC9NP A01                  | Desktop     | [15e1733eb4](https://linux-hardware.org/?probe=15e1733eb4) | Sep 20, 2023 |
| HP        | 250 G7 Notebook PC          | Notebook    | [428177914f](https://linux-hardware.org/?probe=428177914f) | Sep 17, 2023 |
| HP        | 250 G7 Notebook PC          | Notebook    | [f2b0e180d4](https://linux-hardware.org/?probe=f2b0e180d4) | Aug 27, 2023 |
| Dell      | 0T7D40 A01                  | Desktop     | [19c877cd88](https://linux-hardware.org/?probe=19c877cd88) | Jul 31, 2023 |
| Intel     | NUC7i5DNB J57626-509        | Mini pc     | [fdc2de43bb](https://linux-hardware.org/?probe=fdc2de43bb) | Jul 31, 2023 |
| Dell      | 0T7D40 A01                  | Desktop     | [c1b5a5f99b](https://linux-hardware.org/?probe=c1b5a5f99b) | Jul 08, 2023 |
| Intel     | NUC7i5DNB J57626-509        | Mini pc     | [a8ee980594](https://linux-hardware.org/?probe=a8ee980594) | Jun 28, 2023 |
| HP        | ZBook 15 G6                 | Notebook    | [eb23ebb0b8](https://linux-hardware.org/?probe=eb23ebb0b8) | Jun 10, 2023 |
| Apple     | MacBookPro9,2               | Notebook    | [baf92c8b36](https://linux-hardware.org/?probe=baf92c8b36) | Jun 08, 2023 |
| Dell      | 0T7D40 A01                  | Desktop     | [0c0dc06847](https://linux-hardware.org/?probe=0c0dc06847) | May 31, 2023 |
| HP        | 250 G7 Notebook PC          | Notebook    | [2f0f83bda2](https://linux-hardware.org/?probe=2f0f83bda2) | May 25, 2023 |
| HP        | ProBook 640 G1              | Notebook    | [5dceebaf6c](https://linux-hardware.org/?probe=5dceebaf6c) | May 13, 2023 |
| Dell      | Vostro 15 3510              | Notebook    | [fc82fe9907](https://linux-hardware.org/?probe=fc82fe9907) | May 11, 2023 |
| Dell      | 0JP3NX A00                  | Desktop     | [974cb924d5](https://linux-hardware.org/?probe=974cb924d5) | May 08, 2023 |
| Dell      | 0T7D40 A01                  | Desktop     | [7ce0658b0f](https://linux-hardware.org/?probe=7ce0658b0f) | Apr 29, 2023 |
| Dell      | Latitude 5491               | Notebook    | [ef97e6890a](https://linux-hardware.org/?probe=ef97e6890a) | Apr 13, 2023 |
| Lenovo    | 36F7 SDK0J40700 WIN 3258... | Desktop     | [ea50bc5d28](https://linux-hardware.org/?probe=ea50bc5d28) | Apr 13, 2023 |
| Dell      | Inspiron 7415 2-in-1        | Convertible | [b65f6a101f](https://linux-hardware.org/?probe=b65f6a101f) | Apr 12, 2023 |
| Dell      | 0T7D40 A01                  | Desktop     | [11aee4ed7b](https://linux-hardware.org/?probe=11aee4ed7b) | Apr 08, 2023 |
| ASUSTek   | X751LAB                     | Notebook    | [03465bed03](https://linux-hardware.org/?probe=03465bed03) | Apr 06, 2023 |
| HP        | ProBook 640 G1              | Notebook    | [5aa6a42aa2](https://linux-hardware.org/?probe=5aa6a42aa2) | Mar 29, 2023 |
| Acer      | Swift SF314-51              | Notebook    | [5a73818024](https://linux-hardware.org/?probe=5a73818024) | Mar 27, 2023 |
| Dell      | 0T7D40 A01                  | Desktop     | [9320ecf2b2](https://linux-hardware.org/?probe=9320ecf2b2) | Mar 25, 2023 |
| Lenovo    | 3746 WIN SDK0T76463 3422... | All in one  | [ec07bb84cf](https://linux-hardware.org/?probe=ec07bb84cf) | Mar 25, 2023 |
| Lenovo    | ThinkPad X1 Carbon 5th 2... | Notebook    | [0c7e919608](https://linux-hardware.org/?probe=0c7e919608) | Mar 20, 2023 |
| NEWSMAY   | Unknown                     | Desktop     | [c4cab7022b](https://linux-hardware.org/?probe=c4cab7022b) | Mar 15, 2023 |
| Acer      | Aspire E5-551G              | Notebook    | [58703e3260](https://linux-hardware.org/?probe=58703e3260) | Mar 15, 2023 |
| ASUSTek   | ROG STRIX B550-A GAMING     | Desktop     | [c215f0cf02](https://linux-hardware.org/?probe=c215f0cf02) | Mar 14, 2023 |
| Lenovo    | ThinkPad X1 Tablet Gen 2... | Tablet      | [149c782883](https://linux-hardware.org/?probe=149c782883) | Mar 08, 2023 |
| Intel     | NUC7i5DNB J57626-509        | Mini pc     | [f38b8db522](https://linux-hardware.org/?probe=f38b8db522) | Mar 06, 2023 |
| ASRock    | B550 Steel Legend           | Desktop     | [d533a64cb9](https://linux-hardware.org/?probe=d533a64cb9) | Mar 04, 2023 |
| Lenovo    | ThinkPad X1 Carbon 5th 2... | Notebook    | [5c39a363d8](https://linux-hardware.org/?probe=5c39a363d8) | Feb 28, 2023 |
| ASUSTek   | ROG STRIX B550-A GAMING     | Desktop     | [eeafe897ae](https://linux-hardware.org/?probe=eeafe897ae) | Feb 09, 2023 |
| HP        | EliteBook 865 16 inch G9... | Notebook    | [49a4e66cd0](https://linux-hardware.org/?probe=49a4e66cd0) | Feb 05, 2023 |
| Dell      | 0T7D40 A01                  | Desktop     | [74207a9fec](https://linux-hardware.org/?probe=74207a9fec) | Dec 19, 2022 |
| HP        | 212B                        | Desktop     | [55f34c27ec](https://linux-hardware.org/?probe=55f34c27ec) | Oct 08, 2022 |
| ASUSTek   | ROG STRIX B550-A GAMING     | Desktop     | [b1514ab047](https://linux-hardware.org/?probe=b1514ab047) | Oct 02, 2022 |
| Acer      | Aspire V5-471               | Notebook    | [fe551b92a5](https://linux-hardware.org/?probe=fe551b92a5) | Oct 02, 2022 |
| ASUSTek   | ET2411_W8                   | All in one  | [e0ef691738](https://linux-hardware.org/?probe=e0ef691738) | Oct 02, 2022 |
| Dell      | 0T7D40 A01                  | Desktop     | [9eba047248](https://linux-hardware.org/?probe=9eba047248) | Sep 18, 2022 |
| Dell      | 0T7D40 A01                  | Desktop     | [0968e0629e](https://linux-hardware.org/?probe=0968e0629e) | Aug 31, 2022 |
| Acer      | Aspire A515-55              | Notebook    | [bed4db4cf3](https://linux-hardware.org/?probe=bed4db4cf3) | Jul 16, 2022 |
| Dell      | 0T7D40 A01                  | Desktop     | [42b1694c97](https://linux-hardware.org/?probe=42b1694c97) | Jul 01, 2022 |
| Dell      | Inspiron 7415 2-in-1        | Convertible | [2521a61389](https://linux-hardware.org/?probe=2521a61389) | Jun 11, 2022 |
| ASUSTek   | ROG STRIX B450-F GAMING     | Desktop     | [3766ac4bad](https://linux-hardware.org/?probe=3766ac4bad) | May 27, 2022 |
| MSI       | MPG B550 GAMING PLUS        | Desktop     | [5600c7649a](https://linux-hardware.org/?probe=5600c7649a) | Apr 05, 2022 |
| Acer      | Aspire E5-771G              | Notebook    | [a765f92826](https://linux-hardware.org/?probe=a765f92826) | Mar 28, 2022 |
| ASUSTek   | B150M-A/M.2                 | Desktop     | [3098c1fdf3](https://linux-hardware.org/?probe=3098c1fdf3) | Feb 09, 2022 |
| HP        | 8703                        | Desktop     | [11bdfccc66](https://linux-hardware.org/?probe=11bdfccc66) | Feb 04, 2022 |
| Lenovo    | ThinkPad T410 253725G       | Notebook    | [3e1c463980](https://linux-hardware.org/?probe=3e1c463980) | Jan 16, 2022 |
| Lenovo    | IdeaPad 3 15IIL05 81WE      | Notebook    | [7fa0610547](https://linux-hardware.org/?probe=7fa0610547) | Jan 02, 2022 |
| ASUSTek   | ROG STRIX B550-A GAMING     | Desktop     | [80bb463c02](https://linux-hardware.org/?probe=80bb463c02) | Dec 30, 2021 |
| Dell      | 0T7D40 A01                  | Desktop     | [065636c444](https://linux-hardware.org/?probe=065636c444) | Nov 25, 2021 |
| MSI       | MPG B550 GAMING PLUS        | Desktop     | [e3b8f92aa4](https://linux-hardware.org/?probe=e3b8f92aa4) | Sep 27, 2021 |
| Lenovo    | ThinkPad E590 20NB001AIX    | Notebook    | [436614e885](https://linux-hardware.org/?probe=436614e885) | Sep 26, 2021 |
| ASUSTek   | B150M-A/M.2                 | Desktop     | [8c936491c0](https://linux-hardware.org/?probe=8c936491c0) | Sep 23, 2021 |
| ASUSTek   | B150M-A/M.2                 | Desktop     | [1c6a203e2f](https://linux-hardware.org/?probe=1c6a203e2f) | Sep 16, 2021 |
| ASUSTek   | ROG STRIX Z370-F GAMING     | Desktop     | [cdf90072fd](https://linux-hardware.org/?probe=cdf90072fd) | Aug 21, 2021 |
| Dell      | 0T7D40 A01                  | Desktop     | [0728097100](https://linux-hardware.org/?probe=0728097100) | Aug 06, 2021 |
| Lenovo    | ThinkPad T410 253725G       | Notebook    | [65b842202c](https://linux-hardware.org/?probe=65b842202c) | Aug 06, 2021 |
| ASUSTek   | B150M-A/M.2                 | Desktop     | [8b033c463e](https://linux-hardware.org/?probe=8b033c463e) | Aug 06, 2021 |
| ASRock    | B450 Pro4                   | Desktop     | [68f4f90fd0](https://linux-hardware.org/?probe=68f4f90fd0) | Aug 05, 2021 |
| MSI       | MPG B550 GAMING PLUS        | Desktop     | [0ce1757e83](https://linux-hardware.org/?probe=0ce1757e83) | Aug 05, 2021 |
| ASUSTek   | ROG STRIX B450-F GAMING     | Desktop     | [78924b9791](https://linux-hardware.org/?probe=78924b9791) | Aug 05, 2021 |
| ASUSTek   | ROG STRIX B450-F GAMING     | Desktop     | [cc17fc0f36](https://linux-hardware.org/?probe=cc17fc0f36) | Aug 05, 2021 |
| ASUSTek   | ZenBook UX325JA_UX325JA     | Notebook    | [70ddebc8cc](https://linux-hardware.org/?probe=70ddebc8cc) | Jul 25, 2021 |
| ASUSTek   | ZenBook UX325JA_UX325JA     | Notebook    | [455c830431](https://linux-hardware.org/?probe=455c830431) | Jul 25, 2021 |
| TUXEDO    | Book BA1510                 | Notebook    | [80b8c9719c](https://linux-hardware.org/?probe=80b8c9719c) | Jul 11, 2021 |
| HP        | ProBook 4520s               | Notebook    | [50b007f51d](https://linux-hardware.org/?probe=50b007f51d) | Jun 26, 2021 |
| MSI       | MPG B550 GAMING PLUS        | Desktop     | [fcd7305b92](https://linux-hardware.org/?probe=fcd7305b92) | Jun 25, 2021 |
| Dell      | 0T7D40 A01                  | Desktop     | [5ee785eb32](https://linux-hardware.org/?probe=5ee785eb32) | Jun 24, 2021 |
| HP        | ProBook 4520s               | Notebook    | [261b02ab53](https://linux-hardware.org/?probe=261b02ab53) | Jun 20, 2021 |
| MSI       | MPG B550 GAMING PLUS        | Desktop     | [681bafbc6a](https://linux-hardware.org/?probe=681bafbc6a) | May 13, 2021 |
| HP        | Laptop 17-ca1xxx            | Notebook    | [99f175055d](https://linux-hardware.org/?probe=99f175055d) | May 05, 2021 |
| ASUSTek   | ROG STRIX Z370-F GAMING     | Desktop     | [9fa9842ec9](https://linux-hardware.org/?probe=9fa9842ec9) | May 01, 2021 |
| HP        | Laptop 17-ca1xxx            | Notebook    | [e21ac181a5](https://linux-hardware.org/?probe=e21ac181a5) | Apr 03, 2021 |
| HP        | Laptop 17-ca1xxx            | Notebook    | [a8a82ba1b9](https://linux-hardware.org/?probe=a8a82ba1b9) | Mar 01, 2021 |
| HP        | Laptop 17-ca1xxx            | Notebook    | [a3ea535d80](https://linux-hardware.org/?probe=a3ea535d80) | Feb 04, 2021 |
| HP        | Laptop 17-ca1xxx            | Notebook    | [d88b363f5e](https://linux-hardware.org/?probe=d88b363f5e) | Jan 19, 2021 |
| HP        | Laptop 17-ca1xxx            | Notebook    | [5e6eb88969](https://linux-hardware.org/?probe=5e6eb88969) | Jan 02, 2021 |
| HP        | Laptop 17-ca1xxx            | Notebook    | [09675fa9a5](https://linux-hardware.org/?probe=09675fa9a5) | Dec 09, 2020 |
| HP        | Laptop 17-ca1xxx            | Notebook    | [0779e6ce28](https://linux-hardware.org/?probe=0779e6ce28) | Nov 18, 2020 |
| ASUSTek   | PRIME Z270-A                | Desktop     | [894f4ade05](https://linux-hardware.org/?probe=894f4ade05) | Oct 02, 2020 |
| HP        | Laptop 17-ca1xxx            | Notebook    | [386583ebea](https://linux-hardware.org/?probe=386583ebea) | Sep 02, 2020 |
| HP        | 250 G7 Notebook PC          | Notebook    | [52a48bdcb8](https://linux-hardware.org/?probe=52a48bdcb8) | Aug 02, 2020 |
| ASUSTek   | ROG STRIX Z370-F GAMING     | Desktop     | [7db0b1474d](https://linux-hardware.org/?probe=7db0b1474d) | Jun 18, 2020 |
| ASUSTek   | ROG STRIX B450-F GAMING     | Desktop     | [70ab783420](https://linux-hardware.org/?probe=70ab783420) | Apr 07, 2020 |
| Lenovo    | ThinkPad E590 20NB001AIX    | Notebook    | [bc066bdf30](https://linux-hardware.org/?probe=bc066bdf30) | Feb 11, 2020 |
| HP        | Laptop 15-db0xxx            | Notebook    | [f6d4378d90](https://linux-hardware.org/?probe=f6d4378d90) | Jan 03, 2020 |
| Compal    | NBLBX                       | Notebook    | [865da8f6a9](https://linux-hardware.org/?probe=865da8f6a9) | Dec 05, 2019 |
| Lenovo    | ThinkPad Edge E540 20C60... | Notebook    | [552827c68a](https://linux-hardware.org/?probe=552827c68a) | Nov 20, 2019 |
| Lenovo    | ThinkPad Edge E540 20C60... | Notebook    | [d942b46e5b](https://linux-hardware.org/?probe=d942b46e5b) | Nov 20, 2019 |
| Lenovo    | ThinkPad Edge E540 20C60... | Notebook    | [17f6c8b364](https://linux-hardware.org/?probe=17f6c8b364) | Nov 20, 2019 |
| Acer      | Aspire 5750                 | Notebook    | [62afcd020e](https://linux-hardware.org/?probe=62afcd020e) | Feb 26, 2019 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Siduction          | 23        | 31.08%  |
| Siduction 12       | 19        | 25.68%  |
| Siduction 11       | 14        | 18.92%  |
| Siduction Unstable | 11        | 14.86%  |
| Siduction 10       | 5         | 6.76%   |
| Siduction 21       | 1         | 1.35%   |
| Siduction 13       | 1         | 1.35%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| Siduction | 58        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                   | Computers | Percent |
|---------------------------|-----------|---------|
| 6.2.6-1-siduction-amd64   | 4         | 3.92%   |
| 6.2.8-1-siduction-amd64   | 3         | 2.94%   |
| 5.13.8-1-siduction-amd64  | 3         | 2.94%   |
| 6.5.3-1-siduction-amd64   | 2         | 1.96%   |
| 6.5.2-1-siduction-amd64   | 2         | 1.96%   |
| 6.2.2-6-siduction-amd64   | 2         | 1.96%   |
| 6.2.15-1-siduction-amd64  | 2         | 1.96%   |
| 6.2.13-1-siduction-amd64  | 2         | 1.96%   |
| 6.2.10-1-siduction-amd64  | 2         | 1.96%   |
| 6.1.14-1-siduction-amd64  | 2         | 1.96%   |
| 5.13.6-1-siduction-amd64  | 2         | 1.96%   |
| 5.12.12-1-siduction-amd64 | 2         | 1.96%   |
| 6.9.4-1-siduction-amd64   | 1         | 0.98%   |
| 6.8.10-1-siduction-amd64  | 1         | 0.98%   |
| 6.7.10-1-siduction-amd64  | 1         | 0.98%   |
| 6.6.8-1-siduction-amd64   | 1         | 0.98%   |
| 6.6.4-1-siduction-amd64   | 1         | 0.98%   |
| 6.6.2-1-siduction-amd64   | 1         | 0.98%   |
| 6.6.10-1-siduction-amd64  | 1         | 0.98%   |
| 6.5.6-1-siduction-amd64   | 1         | 0.98%   |
| 6.4.9-1-siduction-amd64   | 1         | 0.98%   |
| 6.4.12-1-siduction-amd64  | 1         | 0.98%   |
| 6.3.7-1-siduction-amd64   | 1         | 0.98%   |
| 6.3.3-1-siduction-amd64   | 1         | 0.98%   |
| 6.3.10-1-siduction-amd64  | 1         | 0.98%   |
| 6.2.2-3-siduction-amd64   | 1         | 0.98%   |
| 6.2.11-1-siduction-amd64  | 1         | 0.98%   |
| 6.2.0-rc6-siduction-amd64 | 1         | 0.98%   |
| 6.18.2-1-siduction-amd64  | 1         | 0.98%   |
| 6.17.8-1-siduction-amd64  | 1         | 0.98%   |
| 6.17.5-1-siduction-amd64  | 1         | 0.98%   |
| 6.16.5-1-siduction-amd64  | 1         | 0.98%   |
| 6.15.9-1-siduction-amd64  | 1         | 0.98%   |
| 6.15.10-1-siduction-amd64 | 1         | 0.98%   |
| 6.14.10-1-siduction-amd64 | 1         | 0.98%   |
| 6.13.8-1-siduction-amd64  | 1         | 0.98%   |
| 6.13.2-1-siduction-amd64  | 1         | 0.98%   |
| 6.12.7-1-siduction-amd64  | 1         | 0.98%   |
| 6.12.6-1-siduction-amd64  | 1         | 0.98%   |
| 6.12.13-1-siduction-amd64 | 1         | 0.98%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2.6   | 4         | 3.92%   |
| 6.2.8   | 3         | 2.94%   |
| 6.2.2   | 3         | 2.94%   |
| 5.13.8  | 3         | 2.94%   |
| 6.5.3   | 2         | 1.96%   |
| 6.5.2   | 2         | 1.96%   |
| 6.2.15  | 2         | 1.96%   |
| 6.2.13  | 2         | 1.96%   |
| 6.2.10  | 2         | 1.96%   |
| 6.1.14  | 2         | 1.96%   |
| 5.14.0  | 2         | 1.96%   |
| 5.13.6  | 2         | 1.96%   |
| 5.12.12 | 2         | 1.96%   |
| 6.9.4   | 1         | 0.98%   |
| 6.8.10  | 1         | 0.98%   |
| 6.7.10  | 1         | 0.98%   |
| 6.6.8   | 1         | 0.98%   |
| 6.6.4   | 1         | 0.98%   |
| 6.6.2   | 1         | 0.98%   |
| 6.6.10  | 1         | 0.98%   |
| 6.5.6   | 1         | 0.98%   |
| 6.4.9   | 1         | 0.98%   |
| 6.4.12  | 1         | 0.98%   |
| 6.3.7   | 1         | 0.98%   |
| 6.3.3   | 1         | 0.98%   |
| 6.3.10  | 1         | 0.98%   |
| 6.2.11  | 1         | 0.98%   |
| 6.2.0   | 1         | 0.98%   |
| 6.18.2  | 1         | 0.98%   |
| 6.17.8  | 1         | 0.98%   |
| 6.17.5  | 1         | 0.98%   |
| 6.16.5  | 1         | 0.98%   |
| 6.15.9  | 1         | 0.98%   |
| 6.15.10 | 1         | 0.98%   |
| 6.14.10 | 1         | 0.98%   |
| 6.13.8  | 1         | 0.98%   |
| 6.13.2  | 1         | 0.98%   |
| 6.12.7  | 1         | 0.98%   |
| 6.12.6  | 1         | 0.98%   |
| 6.12.13 | 1         | 0.98%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2     | 16        | 17.39%  |
| 5.13    | 8         | 8.7%    |
| 6.6     | 4         | 4.35%   |
| 6.5     | 4         | 4.35%   |
| 6.1     | 4         | 4.35%   |
| 5.16    | 4         | 4.35%   |
| 5.12    | 4         | 4.35%   |
| 6.3     | 3         | 3.26%   |
| 6.12    | 3         | 3.26%   |
| 5.19    | 3         | 3.26%   |
| 5.18    | 3         | 3.26%   |
| 5.15    | 3         | 3.26%   |
| 5.14    | 3         | 3.26%   |
| 6.4     | 2         | 2.17%   |
| 6.17    | 2         | 2.17%   |
| 6.15    | 2         | 2.17%   |
| 6.13    | 2         | 2.17%   |
| 5.8     | 2         | 2.17%   |
| 5.7     | 2         | 2.17%   |
| 5.4     | 2         | 2.17%   |
| 5.3     | 2         | 2.17%   |
| 5.10    | 2         | 2.17%   |
| 6.9     | 1         | 1.09%   |
| 6.8     | 1         | 1.09%   |
| 6.7     | 1         | 1.09%   |
| 6.18    | 1         | 1.09%   |
| 6.16    | 1         | 1.09%   |
| 6.14    | 1         | 1.09%   |
| 6.10    | 1         | 1.09%   |
| 6.0     | 1         | 1.09%   |
| 5.9     | 1         | 1.09%   |
| 5.6     | 1         | 1.09%   |
| 5.11    | 1         | 1.09%   |
| 4.20    | 1         | 1.09%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 58        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KDE5            | 33        | 50%     |
| XFCE            | 8         | 12.12%  |
| KDE6            | 7         | 10.61%  |
| Unknown         | 7         | 10.61%  |
| X-Cinnamon      | 4         | 6.06%   |
| LXQt            | 3         | 4.55%   |
| Budgie          | 2         | 3.03%   |
| GNOME Flashback | 1         | 1.52%   |
| Cinnamon        | 1         | 1.52%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 42        | 66.67%  |
| Wayland | 19        | 30.16%  |
| Tty     | 2         | 3.17%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 42        | 67.74%  |
| Unknown | 14        | 22.58%  |
| LightDM | 3         | 4.84%   |
| TDM     | 1         | 1.61%   |
| GDM3    | 1         | 1.61%   |
| GDM     | 1         | 1.61%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| de_DE   | 25        | 40.98%  |
| en_US   | 19        | 31.15%  |
| Unknown | 4         | 6.56%   |
| en_GB   | 3         | 4.92%   |
| it_IT   | 2         | 3.28%   |
| fr_FR   | 2         | 3.28%   |
| de_AT   | 2         | 3.28%   |
| en_ZA   | 1         | 1.64%   |
| en_CA   | 1         | 1.64%   |
| de_CH   | 1         | 1.64%   |
| C       | 1         | 1.64%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 43        | 71.67%  |
| BIOS | 17        | 28.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 45        | 75%     |
| Btrfs   | 11        | 18.33%  |
| Overlay | 2         | 3.33%   |
| Tmpfs   | 1         | 1.67%   |
| Unknown | 1         | 1.67%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 40        | 67.8%   |
| Unknown | 12        | 20.34%  |
| MBR     | 7         | 11.86%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 52        | 88.14%  |
| Yes       | 7         | 11.86%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 45        | 76.27%  |
| Yes       | 14        | 23.73%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Lenovo           | 15        | 25.86%  |
| Hewlett-Packard  | 10        | 17.24%  |
| Dell             | 9         | 15.52%  |
| ASUSTek Computer | 8         | 13.79%  |
| Acer             | 5         | 8.62%   |
| TUXEDO           | 2         | 3.45%   |
| MSI              | 2         | 3.45%   |
| ASRock           | 2         | 3.45%   |
| NEWSMAY          | 1         | 1.72%   |
| Intel            | 1         | 1.72%   |
| Framework        | 1         | 1.72%   |
| Compal           | 1         | 1.72%   |
| AWOW             | 1         | 1.72%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                          | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| TUXEDO Sirius 16 Gen1                         | 1         | 1.72%   |
| TUXEDO Book BA1510                            | 1         | 1.72%   |
| MSI MS-7C56                                   | 1         | 1.72%   |
| MSI MS-7883                                   | 1         | 1.72%   |
| Lenovo ThinkPad X1 Tablet Gen 2 20JCA016JP    | 1         | 1.72%   |
| Lenovo ThinkPad X1 Carbon 5th 20HRCTO1WW      | 1         | 1.72%   |
| Lenovo ThinkPad T580 20LAS1GG00               | 1         | 1.72%   |
| Lenovo ThinkPad T490 20N3SFKX00               | 1         | 1.72%   |
| Lenovo ThinkPad T410 253725G                  | 1         | 1.72%   |
| Lenovo ThinkPad T14s Gen 1 20T1S15N00         | 1         | 1.72%   |
| Lenovo ThinkPad L590 20Q7001HGE               | 1         | 1.72%   |
| Lenovo ThinkPad L540 20AUS01H00               | 1         | 1.72%   |
| Lenovo ThinkPad Edge E540 20C6003AGE          | 1         | 1.72%   |
| Lenovo ThinkPad E590 20NB001AIX               | 1         | 1.72%   |
| Lenovo ThinkPad E14 Gen 4 21ECS0WD00          | 1         | 1.72%   |
| Lenovo IdeaPad 3 15IIL05 81WE                 | 1         | 1.72%   |
| Lenovo IdeaCentre AIO 3 27ALC6 F0FY0055GE     | 1         | 1.72%   |
| Lenovo IdeaCentre 310S-08ASR 90G9006DIX       | 1         | 1.72%   |
| Lenovo G50-30 80G0                            | 1         | 1.72%   |
| Intel NUC7i5DNKE                              | 1         | 1.72%   |
| HP ZBook 15 G6                                | 1         | 1.72%   |
| HP Z440 Workstation                           | 1         | 1.72%   |
| HP ProBook 640 G1                             | 1         | 1.72%   |
| HP ProBook 4540s                              | 1         | 1.72%   |
| HP ProBook 4520s                              | 1         | 1.72%   |
| HP OMEN 30L Desktop GT13-0xxx                 | 1         | 1.72%   |
| HP Laptop 17-ca1xxx                           | 1         | 1.72%   |
| HP Laptop 15-db0xxx                           | 1         | 1.72%   |
| HP EliteBook 865 16 inch G9 Notebook PC       | 1         | 1.72%   |
| HP 250 G7 Notebook PC                         | 1         | 1.72%   |
| Framework Laptop 13 (AMD Ryzen AI 300 Series) | 1         | 1.72%   |
| Dell XPS 8920                                 | 1         | 1.72%   |
| Dell XPS 15 9530                              | 1         | 1.72%   |
| Dell Vostro 15 3510                           | 1         | 1.72%   |
| Dell OptiPlex 9020                            | 1         | 1.72%   |
| Dell OptiPlex 5040                            | 1         | 1.72%   |
| Dell OptiPlex 3050                            | 1         | 1.72%   |
| Dell Latitude 5491                            | 1         | 1.72%   |
| Dell Inspiron 7706 2n1                        | 1         | 1.72%   |
| Dell Inspiron 7415 2-in-1                     | 1         | 1.72%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 11        | 18.97%  |
| Acer Aspire       | 4         | 6.9%    |
| HP ProBook        | 3         | 5.17%   |
| Dell OptiPlex     | 3         | 5.17%   |
| Lenovo IdeaCentre | 2         | 3.45%   |
| HP Laptop         | 2         | 3.45%   |
| Dell XPS          | 2         | 3.45%   |
| Dell Inspiron     | 2         | 3.45%   |
| ASUS ROG          | 2         | 3.45%   |
| TUXEDO Sirius     | 1         | 1.72%   |
| TUXEDO Book       | 1         | 1.72%   |
| MSI MS-7C56       | 1         | 1.72%   |
| MSI MS-7883       | 1         | 1.72%   |
| Lenovo IdeaPad    | 1         | 1.72%   |
| Lenovo G50-30     | 1         | 1.72%   |
| Intel NUC7i5DNKE  | 1         | 1.72%   |
| HP ZBook          | 1         | 1.72%   |
| HP Z440           | 1         | 1.72%   |
| HP OMEN           | 1         | 1.72%   |
| HP EliteBook      | 1         | 1.72%   |
| HP 250            | 1         | 1.72%   |
| Framework Laptop  | 1         | 1.72%   |
| Dell Vostro       | 1         | 1.72%   |
| Dell Latitude     | 1         | 1.72%   |
| Compal NBLBX      | 1         | 1.72%   |
| AWOW AK41         | 1         | 1.72%   |
| ASUS ZenBook      | 1         | 1.72%   |
| ASUS VivoBook     | 1         | 1.72%   |
| ASUS PRIME        | 1         | 1.72%   |
| ASUS BU201LA      | 1         | 1.72%   |
| ASUS B150M-A      | 1         | 1.72%   |
| ASUS A0000001     | 1         | 1.72%   |
| ASRock B550       | 1         | 1.72%   |
| ASRock B450       | 1         | 1.72%   |
| Acer Swift        | 1         | 1.72%   |
| Unknown           | 1         | 1.72%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 9         | 15.52%  |
| 2019 | 8         | 13.79%  |
| 2014 | 7         | 12.07%  |
| 2018 | 6         | 10.34%  |
| 2017 | 5         | 8.62%   |
| 2022 | 4         | 6.9%    |
| 2021 | 4         | 6.9%    |
| 2016 | 4         | 6.9%    |
| 2013 | 3         | 5.17%   |
| 2010 | 2         | 3.45%   |
| 2024 | 1         | 1.72%   |
| 2023 | 1         | 1.72%   |
| 2015 | 1         | 1.72%   |
| 2012 | 1         | 1.72%   |
| 2011 | 1         | 1.72%   |
| 2009 | 1         | 1.72%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 36        | 62.07%  |
| Desktop     | 17        | 29.31%  |
| Convertible | 2         | 3.45%   |
| Tablet      | 1         | 1.72%   |
| Mini pc     | 1         | 1.72%   |
| All in one  | 1         | 1.72%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 58        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 58        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 15        | 25.42%  |
| 4.01-8.0    | 14        | 23.73%  |
| 32.01-64.0  | 14        | 23.73%  |
| 8.01-16.0   | 11        | 18.64%  |
| 3.01-4.0    | 2         | 3.39%   |
| 64.01-256.0 | 2         | 3.39%   |
| Unknown     | 1         | 1.69%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 19        | 25.68%  |
| 2.01-3.0   | 18        | 24.32%  |
| 3.01-4.0   | 17        | 22.97%  |
| 1.01-2.0   | 9         | 12.16%  |
| 8.01-16.0  | 4         | 5.41%   |
| 0.51-1.0   | 3         | 4.05%   |
| 32.01-64.0 | 1         | 1.35%   |
| 16.01-24.0 | 1         | 1.35%   |
| 0.01-0.5   | 1         | 1.35%   |
| Unknown    | 1         | 1.35%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 34        | 55.74%  |
| 2      | 14        | 22.95%  |
| 4      | 6         | 9.84%   |
| 3      | 5         | 8.2%    |
| 6      | 1         | 1.64%   |
| 5      | 1         | 1.64%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 41        | 68.33%  |
| Yes       | 19        | 31.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 49        | 84.48%  |
| No        | 9         | 15.52%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 48        | 82.76%  |
| No        | 10        | 17.24%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 42        | 68.85%  |
| No        | 19        | 31.15%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| Germany      | 26        | 43.33%  |
| USA          | 9         | 15%     |
| Austria      | 5         | 8.33%   |
| UK           | 3         | 5%      |
| Italy        | 3         | 5%      |
| Canada       | 3         | 5%      |
| Sweden       | 2         | 3.33%   |
| France       | 2         | 3.33%   |
| Switzerland  | 1         | 1.67%   |
| South Africa | 1         | 1.67%   |
| Poland       | 1         | 1.67%   |
| Nigeria      | 1         | 1.67%   |
| Netherlands  | 1         | 1.67%   |
| Japan        | 1         | 1.67%   |
| Israel       | 1         | 1.67%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Munich            | 5         | 6.41%   |
| Vienna            | 3         | 3.85%   |
| Berlin            | 3         | 3.85%   |
| Suisun            | 2         | 2.56%   |
| Stuttgart         | 2         | 2.56%   |
| Stockholm         | 2         | 2.56%   |
| Schrobenhausen    | 2         | 2.56%   |
| Hamburg           | 2         | 2.56%   |
| Frankfurt am Main | 2         | 2.56%   |
| Zurich            | 1         | 1.28%   |
| Wiener Neustadt   | 1         | 1.28%   |
| Unterlochen       | 1         | 1.28%   |
| Unterbergla       | 1         | 1.28%   |
| Tuttlingen        | 1         | 1.28%   |
| Turin             | 1         | 1.28%   |
| Trier             | 1         | 1.28%   |
| Tourcoing         | 1         | 1.28%   |
| Toronto           | 1         | 1.28%   |
| Tokyo             | 1         | 1.28%   |
| Sidney            | 1         | 1.28%   |
| Savannah          | 1         | 1.28%   |
| Sanford           | 1         | 1.28%   |
| San Francisco     | 1         | 1.28%   |
| Salzburg          | 1         | 1.28%   |
| Rostock           | 1         | 1.28%   |
| Regensburg        | 1         | 1.28%   |
| Reading           | 1         | 1.28%   |
| Portland          | 1         | 1.28%   |
| Piea              | 1         | 1.28%   |
| Paris             | 1         | 1.28%   |
| Papenburg         | 1         | 1.28%   |
| Oranienburg       | 1         | 1.28%   |
| Oberboihingen     | 1         | 1.28%   |
| Mittenwald        | 1         | 1.28%   |
| Milan             | 1         | 1.28%   |
| Merseburg         | 1         | 1.28%   |
| Marion            | 1         | 1.28%   |
| Mannheim          | 1         | 1.28%   |
| Malmo             | 1         | 1.28%   |
| Leipzig           | 1         | 1.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 20        | 30     | 20.2%   |
| WDC                         | 16        | 37     | 16.16%  |
| Seagate                     | 10        | 19     | 10.1%   |
| Toshiba                     | 8         | 17     | 8.08%   |
| Crucial                     | 7         | 19     | 7.07%   |
| SK hynix                    | 6         | 15     | 6.06%   |
| Sandisk                     | 6         | 13     | 6.06%   |
| Kingston                    | 6         | 6      | 6.06%   |
| Intel                       | 4         | 9      | 4.04%   |
| Silicon Motion              | 2         | 2      | 2.02%   |
| Lexar                       | 2         | 2      | 2.02%   |
| Corsair                     | 2         | 5      | 2.02%   |
| Unknown                     | 1         | 1      | 1.01%   |
| SSSTC                       | 1         | 1      | 1.01%   |
| OCZ                         | 1         | 3      | 1.01%   |
| Mushkin                     | 1         | 3      | 1.01%   |
| Micron Technology           | 1         | 1      | 1.01%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 1.01%   |
| Lenovo                      | 1         | 1      | 1.01%   |
| Hitachi                     | 1         | 1      | 1.01%   |
| HGST                        | 1         | 11     | 1.01%   |
| GRITRONIX                   | 1         | 1      | 1.01%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| WDC WD10JPVX-22JC3T0 1TB                              | 3         | 2.75%   |
| Toshiba MQ04ABF100 1TB                                | 2         | 1.83%   |
| SK hynix BC711 NVMe 1TB                               | 2         | 1.83%   |
| SanDisk NVMe SSD Drive 1TB                            | 2         | 1.83%   |
| Samsung SSD 850 EVO 500GB                             | 2         | 1.83%   |
| Samsung SSD 850 EVO 250GB                             | 2         | 1.83%   |
| Kingston SA400S37240G 240GB SSD                       | 2         | 1.83%   |
| Crucial CT500MX500SSD1 500GB                          | 2         | 1.83%   |
| Crucial CT2000MX500SSD1 2TB                           | 2         | 1.83%   |
| Crucial CT1000MX500SSD1 1TB                           | 2         | 1.83%   |
| WDC WDS500G2B0B-00YS70 500GB SSD                      | 1         | 0.92%   |
| WDC WDS400T2B0A-00SM50 4TB SSD                        | 1         | 0.92%   |
| WDC WDS200T2B0B-00YS70 2TB SSD                        | 1         | 0.92%   |
| WDC WDS100T2B0C-00PXH0 1TB                            | 1         | 0.92%   |
| WDC WD60EZAZ-00SF3B0 6TB                              | 1         | 0.92%   |
| WDC WD40EZAZ-00SF3B0 4TB                              | 1         | 0.92%   |
| WDC WD40EFRX-68WT0N0 4TB                              | 1         | 0.92%   |
| WDC WD3200BPVT-22JJ5T0 320GB                          | 1         | 0.92%   |
| WDC WD20EZRZ-00Z5HB0 2TB                              | 1         | 0.92%   |
| WDC WD20EFRX-68EUZN0 2TB                              | 1         | 0.92%   |
| WDC WD10SPZX-60Z10T0 1TB                              | 1         | 0.92%   |
| WDC WD10JPVX-60JC3T1 1TB                              | 1         | 0.92%   |
| WDC WD10EADX-00TDHB0 1TB                              | 1         | 0.92%   |
| WDC WD BLACK SDBPNTY-512G-1106 512GB                  | 1         | 0.92%   |
| WDC PC SN810 NVMe 1024GB                              | 1         | 0.92%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB                  | 1         | 0.92%   |
| Unknown MMC Card  64GB                                | 1         | 0.92%   |
| Toshiba XG4 NVMe SSD Controller 256GB                 | 1         | 0.92%   |
| Toshiba THNSNK256GVN8 256GB SSD                       | 1         | 0.92%   |
| Toshiba THNSF5512GPUK 512GB                           | 1         | 0.92%   |
| Toshiba RD400 256GB                                   | 1         | 0.92%   |
| Toshiba MQ01ACF032 320GB                              | 1         | 0.92%   |
| Toshiba KBG30ZMT256G 256GB                            | 1         | 0.92%   |
| SSSTC CL4-3D256-Q11 NVMe 256GB                        | 1         | 0.92%   |
| SK hynix SKHynix_HFS256GD9TNG-L5B0B 256GB             | 1         | 0.92%   |
| SK hynix SC308 SATA 128GB SSD                         | 1         | 0.92%   |
| SK hynix NVMe SSD Drive 512GB                         | 1         | 0.92%   |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB               | 1         | 0.92%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 512GB | 1         | 0.92%   |
| Silicon Motion SM2262/SM2262EN SSD Controller 960GB   | 1         | 0.92%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 11        | 24     | 40.74%  |
| Seagate             | 10        | 19     | 37.04%  |
| Toshiba             | 3         | 11     | 11.11%  |
| Samsung Electronics | 1         | 1      | 3.7%    |
| Hitachi             | 1         | 1      | 3.7%    |
| HGST                | 1         | 11     | 3.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 19     | 34.48%  |
| Crucial             | 6         | 17     | 20.69%  |
| Kingston            | 4         | 4      | 13.79%  |
| WDC                 | 3         | 3      | 10.34%  |
| SanDisk             | 2         | 4      | 6.9%    |
| Toshiba             | 1         | 1      | 3.45%   |
| SK hynix            | 1         | 9      | 3.45%   |
| OCZ                 | 1         | 3      | 3.45%   |
| GRITRONIX           | 1         | 1      | 3.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 37        | 69     | 44.05%  |
| SSD  | 24        | 61     | 28.57%  |
| HDD  | 22        | 67     | 26.19%  |
| MMC  | 1         | 1      | 1.19%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 37        | 69     | 50%     |
| SATA | 36        | 128    | 48.65%  |
| MMC  | 1         | 1      | 1.35%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 23        | 52     | 46%     |
| 0.51-1.0   | 11        | 32     | 22%     |
| 1.01-2.0   | 8         | 21     | 16%     |
| 3.01-4.0   | 4         | 17     | 8%      |
| 4.01-10.0  | 3         | 3      | 6%      |
| 2.01-3.0   | 1         | 3      | 2%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 15        | 23.08%  |
| More than 3000 | 9         | 13.85%  |
| 101-250        | 9         | 13.85%  |
| 501-1000       | 9         | 13.85%  |
| 1001-2000      | 7         | 10.77%  |
| Unknown        | 5         | 7.69%   |
| 2001-3000      | 4         | 6.15%   |
| 1-20           | 4         | 6.15%   |
| 21-50          | 2         | 3.08%   |
| 51-100         | 1         | 1.54%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 20        | 27.03%  |
| 101-250        | 10        | 13.51%  |
| 51-100         | 8         | 10.81%  |
| 501-1000       | 7         | 9.46%   |
| 251-500        | 6         | 8.11%   |
| 21-50          | 6         | 8.11%   |
| 1001-2000      | 6         | 8.11%   |
| Unknown        | 5         | 6.76%   |
| More than 3000 | 4         | 5.41%   |
| 2001-3000      | 2         | 2.7%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                   | Computers | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| WDC WD20EZRZ-00Z5HB0 2TB                | 1         | 6      | 9.09%   |
| SK hynix SC308 SATA 128GB SSD           | 1         | 9      | 9.09%   |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB | 1         | 1      | 9.09%   |
| Seagate ST32000542AS 2TB                | 1         | 3      | 9.09%   |
| Samsung Electronics SSD 970 EVO 1TB     | 1         | 1      | 9.09%   |
| Samsung Electronics SSD 870 EVO 4TB     | 1         | 1      | 9.09%   |
| OCZ VERTEX3 120GB SSD                   | 1         | 3      | 9.09%   |
| Kingston SA400S37240G 240GB SSD         | 1         | 1      | 9.09%   |
| Hitachi HTS725025A9A364 250GB           | 1         | 1      | 9.09%   |
| HGST HTS725050A7E630 500GB              | 1         | 11     | 9.09%   |
| Crucial CT500MX500SSD1 500GB            | 1         | 1      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| SK hynix            | 2         | 10     | 18.18%  |
| Samsung Electronics | 2         | 2      | 18.18%  |
| WDC                 | 1         | 6      | 9.09%   |
| Seagate             | 1         | 3      | 9.09%   |
| OCZ                 | 1         | 3      | 9.09%   |
| Kingston            | 1         | 1      | 9.09%   |
| Hitachi             | 1         | 1      | 9.09%   |
| HGST                | 1         | 11     | 9.09%   |
| Crucial             | 1         | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 6      | 25%     |
| Seagate | 1         | 3      | 25%     |
| Hitachi | 1         | 1      | 25%     |
| HGST    | 1         | 11     | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 5         | 15     | 45.45%  |
| HDD  | 4         | 21     | 36.36%  |
| NVMe | 2         | 2      | 18.18%  |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 46        | 128    | 66.67%  |
| Detected | 14        | 32     | 20.29%  |
| Malfunc  | 9         | 38     | 13.04%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 35        | 39.77%  |
| AMD                            | 13        | 14.77%  |
| Samsung Electronics            | 8         | 9.09%   |
| SanDisk                        | 7         | 7.95%   |
| SK hynix                       | 5         | 5.68%   |
| Toshiba America Info Systems   | 4         | 4.55%   |
| Silicon Motion                 | 2         | 2.27%   |
| Shenzhen Longsys Electronics   | 2         | 2.27%   |
| Phison Electronics             | 2         | 2.27%   |
| Micron/Crucial Technology      | 2         | 2.27%   |
| Kingston Technology Company    | 2         | 2.27%   |
| Solid State Storage Technology | 1         | 1.14%   |
| OCZ Technology Group           | 1         | 1.14%   |
| Micron Technology              | 1         | 1.14%   |
| MAXIO Technology (Hangzhou)    | 1         | 1.14%   |
| Lenovo                         | 1         | 1.14%   |
| ASMedia Technology             | 1         | 1.14%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 10        | 10.53%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 4.21%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4         | 4.21%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3         | 3.16%   |
| AMD 500 Series Chipset SATA Controller                                         | 3         | 3.16%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 2         | 2.11%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)            | 2         | 2.11%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 2         | 2.11%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 2         | 2.11%   |
| Shenzhen Longsys Lexar NM790 / Patriot Viper VP4300 Lite NVMe SSD (DRAM-less)  | 2         | 2.11%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 2         | 2.11%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 2.11%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 2.11%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 2.11%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 2         | 2.11%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 2.11%   |
| AMD 400 Series Chipset SATA Controller                                         | 2         | 2.11%   |
| Solid State Storage CL4-8D512 NVMe SSD M.2 (DRAM-less)                         | 1         | 1.05%   |
| SK hynix PC601 NVMe Solid State Drive                                          | 1         | 1.05%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 1         | 1.05%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1         | 1.05%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 1.05%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 1         | 1.05%   |
| SanDisk PC SN735 / WD_BLACK SN750 SE NVMe SSD (DRAM-less)                      | 1         | 1.05%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 1         | 1.05%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 1         | 1.05%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1         | 1.05%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 1         | 1.05%   |
| Samsung NVMe SSD Controller PM9C1a (DRAM-less)                                 | 1         | 1.05%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                  | 1         | 1.05%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 1.05%   |
| Phison PS5021-E21 PCIe4 NVMe Controller (DRAM-less)                            | 1         | 1.05%   |
| Phison E7 NVMe Controller                                                      | 1         | 1.05%   |
| OCZ Group RD400/400A SSD                                                       | 1         | 1.05%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                           | 1         | 1.05%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton]                                      | 1         | 1.05%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 1         | 1.05%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                       | 1         | 1.05%   |
| Lenovo LENSE20256GMSP34MEAT2TA                                                 | 1         | 1.05%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                  | 1         | 1.05%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 40        | 48.78%  |
| NVMe | 36        | 43.9%   |
| RAID | 4         | 4.88%   |
| IDE  | 2         | 2.44%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 41        | 70.69%  |
| AMD    | 17        | 29.31%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 3.45%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 3.45%   |
| AMD Ryzen 5 3600 6-Core Processor             | 2         | 3.45%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 3.45%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz           | 1         | 1.72%   |
| Intel Pentium Silver N6005 @ 2.00GHz          | 1         | 1.72%   |
| Intel Pentium CPU G4400T @ 2.90GHz            | 1         | 1.72%   |
| Intel Core i7-9850H CPU @ 2.60GHz             | 1         | 1.72%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 1.72%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 1         | 1.72%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 1.72%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 1         | 1.72%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 1.72%   |
| Intel Core i7-6850K CPU @ 3.60GHz             | 1         | 1.72%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz            | 1         | 1.72%   |
| Intel Core i7-10700K CPU @ 3.80GHz            | 1         | 1.72%   |
| Intel Core i7-10610U CPU @ 1.80GHz            | 1         | 1.72%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 1         | 1.72%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 1         | 1.72%   |
| Intel Core i5-7Y54 CPU @ 1.20GHz              | 1         | 1.72%   |
| Intel Core i5-7600K CPU @ 3.80GHz             | 1         | 1.72%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 1         | 1.72%   |
| Intel Core i5-6600K CPU @ 3.50GHz             | 1         | 1.72%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 1         | 1.72%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 1.72%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 1.72%   |
| Intel Core i5-4590S CPU @ 3.00GHz             | 1         | 1.72%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 1.72%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 1         | 1.72%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 1         | 1.72%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 1         | 1.72%   |
| Intel Core i5 CPU M 430 @ 2.27GHz             | 1         | 1.72%   |
| Intel Core i3-4000M CPU @ 2.40GHz             | 1         | 1.72%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 1         | 1.72%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 1         | 1.72%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 1         | 1.72%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 1         | 1.72%   |
| Intel 13th Gen Core i7-13700H                 | 1         | 1.72%   |
| Intel 12th Gen Core i3-1215U                  | 1         | 1.72%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 1.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 17        | 29.31%  |
| Intel Core i7        | 12        | 20.69%  |
| AMD Ryzen 5          | 8         | 13.79%  |
| Other                | 6         | 10.34%  |
| AMD Ryzen 7          | 4         | 6.9%    |
| Intel Core i3        | 3         | 5.17%   |
| Intel Celeron        | 2         | 3.45%   |
| AMD Ryzen 9          | 2         | 3.45%   |
| Intel Xeon           | 1         | 1.72%   |
| Intel Pentium Silver | 1         | 1.72%   |
| Intel Pentium        | 1         | 1.72%   |
| AMD FX               | 1         | 1.72%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 23        | 39.66%  |
| 2      | 17        | 29.31%  |
| 6      | 10        | 17.24%  |
| 8      | 6         | 10.34%  |
| 14     | 1         | 1.72%   |
| 12     | 1         | 1.72%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 58        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 49        | 84.48%  |
| 1      | 9         | 15.52%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 57        | 98.28%  |
| Unknown        | 1         | 1.72%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 35        | 53.03%  |
| 0x08701021 | 3         | 4.55%   |
| 0x806ec    | 2         | 3.03%   |
| 0x706e5    | 2         | 3.03%   |
| 0x506e3    | 2         | 3.03%   |
| 0x20655    | 2         | 3.03%   |
| 0x08108102 | 2         | 3.03%   |
| 0x0800820d | 2         | 3.03%   |
| 0xa0655    | 1         | 1.52%   |
| 0x906ea    | 1         | 1.52%   |
| 0x906e9    | 1         | 1.52%   |
| 0x806eb    | 1         | 1.52%   |
| 0x806e9    | 1         | 1.52%   |
| 0x306f2    | 1         | 1.52%   |
| 0x306d4    | 1         | 1.52%   |
| 0x306c3    | 1         | 1.52%   |
| 0x206a7    | 1         | 1.52%   |
| 0x20652    | 1         | 1.52%   |
| 0x0a404102 | 1         | 1.52%   |
| 0x08608103 | 1         | 1.52%   |
| 0x08108109 | 1         | 1.52%   |
| 0x0810100b | 1         | 1.52%   |
| 0x06006705 | 1         | 1.52%   |
| 0x06003106 | 1         | 1.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 14        | 24.14%  |
| Haswell          | 6         | 10.34%  |
| Zen+             | 5         | 8.62%   |
| Unknown          | 5         | 8.62%   |
| Skylake          | 4         | 6.9%    |
| Zen 2            | 3         | 5.17%   |
| Westmere         | 3         | 5.17%   |
| TigerLake        | 2         | 3.45%   |
| IceLake          | 2         | 3.45%   |
| Broadwell        | 2         | 3.45%   |
| Alderlake Hybrid | 2         | 3.45%   |
| Zen 3            | 1         | 1.72%   |
| Zen              | 1         | 1.72%   |
| Tremont          | 1         | 1.72%   |
| Steamroller      | 1         | 1.72%   |
| Silvermont       | 1         | 1.72%   |
| SandyBridge      | 1         | 1.72%   |
| IvyBridge        | 1         | 1.72%   |
| Goldmont plus    | 1         | 1.72%   |
| Excavator        | 1         | 1.72%   |
| CometLake        | 1         | 1.72%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 33        | 50%     |
| AMD    | 22        | 33.33%  |
| Nvidia | 11        | 16.67%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 4         | 5.8%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 3         | 4.35%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3         | 4.35%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 3         | 4.35%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 2         | 2.9%    |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                     | 2         | 2.9%    |
| Intel Iris Plus Graphics G7                                                 | 2         | 2.9%    |
| Intel Core Processor Integrated Graphics Controller                         | 2         | 2.9%    |
| AMD Navi 33 [Radeon RX 7600/7600 XT/7600M XT/7600S/7700S / PRO W7600]       | 2         | 2.9%    |
| AMD Lucienne                                                                | 2         | 2.9%    |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                               | 1         | 1.45%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1         | 1.45%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1         | 1.45%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1         | 1.45%   |
| Nvidia GM108M [GeForce MX130]                                               | 1         | 1.45%   |
| Nvidia GK208M [GeForce GT 740M]                                             | 1         | 1.45%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 1         | 1.45%   |
| Nvidia GF119 [NVS 310]                                                      | 1         | 1.45%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]        | 1         | 1.45%   |
| Nvidia GA106 [Geforce RTX 3050]                                             | 1         | 1.45%   |
| Nvidia AD107M [GeForce RTX 4050 Max-Q / Mobile]                             | 1         | 1.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1         | 1.45%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                       | 1         | 1.45%   |
| Intel Skylake-S GT2 [HD Graphics 530]                                       | 1         | 1.45%   |
| Intel Skylake-S GT1 [HD Graphics 510]                                       | 1         | 1.45%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                      | 1         | 1.45%   |
| Intel Kaby Lake-Y GT2 [HD Graphics 615]                                     | 1         | 1.45%   |
| Intel Kaby Lake-S GT2 [HD Graphics 630]                                     | 1         | 1.45%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                    | 1         | 1.45%   |
| Intel JasperLake [UHD Graphics]                                             | 1         | 1.45%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 1         | 1.45%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1         | 1.45%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 1         | 1.45%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 1         | 1.45%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                    | 1         | 1.45%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 1         | 1.45%   |
| Intel Alder Lake-UP3 GT1 [UHD Graphics]                                     | 1         | 1.45%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 1         | 1.45%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1         | 1.45%   |
| AMD Vega 20 [Radeon VII]                                                    | 1         | 1.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 27        | 45%     |
| 1 x AMD        | 19        | 31.67%  |
| 1 x Nvidia     | 7         | 11.67%  |
| Intel + Nvidia | 4         | 6.67%   |
| 2 x AMD        | 2         | 3.33%   |
| Intel + AMD    | 1         | 1.67%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 52        | 86.67%  |
| Proprietary | 6         | 10%     |
| Unknown     | 2         | 3.33%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 36        | 58.06%  |
| 0.01-0.5   | 8         | 12.9%   |
| 7.01-8.0   | 5         | 8.06%   |
| 1.01-2.0   | 5         | 8.06%   |
| 3.01-4.0   | 2         | 3.23%   |
| 8.01-16.0  | 2         | 3.23%   |
| 0.51-1.0   | 2         | 3.23%   |
| 5.01-6.0   | 1         | 1.61%   |
| 2.01-3.0   | 1         | 1.61%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Chimei Innolux      | 11        | 15.07%  |
| LG Display          | 9         | 12.33%  |
| BOE                 | 8         | 10.96%  |
| AU Optronics        | 7         | 9.59%   |
| Acer                | 7         | 9.59%   |
| Samsung Electronics | 6         | 8.22%   |
| Hewlett-Packard     | 4         | 5.48%   |
| Dell                | 4         | 5.48%   |
| Lenovo              | 3         | 4.11%   |
| Goldstar            | 3         | 4.11%   |
| Philips             | 2         | 2.74%   |
| AOC                 | 2         | 2.74%   |
| ViewSonic           | 1         | 1.37%   |
| STD                 | 1         | 1.37%   |
| Sony                | 1         | 1.37%   |
| MSI                 | 1         | 1.37%   |
| Eizo                | 1         | 1.37%   |
| BenQ                | 1         | 1.37%   |
| ASUSTek Computer    | 1         | 1.37%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SyncMaster SAM021E 1680x1050 433x271mm 20.1-inch  | 2         | 2.63%   |
| ViewSonic VX3418-2KPC VSC613B 3440x1440 797x334mm 34.0-inch           | 1         | 1.32%   |
| STD HDMI TV STD00C7 1920x1080 698x392mm 31.5-inch                     | 1         | 1.32%   |
| Sony SAMSUNG SNY5203 1920x540                                         | 1         | 1.32%   |
| Samsung Electronics SMB2240W SAM0699 1680x1050 459x296mm 21.5-inch    | 1         | 1.32%   |
| Samsung Electronics S27E590 SAM0C5D 1920x1080 598x336mm 27.0-inch     | 1         | 1.32%   |
| Samsung Electronics S27E391 SAM0C15 1920x1080 598x336mm 27.0-inch     | 1         | 1.32%   |
| Samsung Electronics LCD Monitor SDC4244 2160x1440 254x169mm 12.0-inch | 1         | 1.32%   |
| Samsung Electronics LCD Monitor SDC414D 3456x2160 336x210mm 15.6-inch | 1         | 1.32%   |
| Philips PHL 241P6E PHL08F7 1920x1080 527x296mm 23.8-inch              | 1         | 1.32%   |
| Philips 200V4 PHLC0BF 1600x900 432x240mm 19.5-inch                    | 1         | 1.32%   |
| MSI G241 MSI3BA4 1920x1080 527x296mm 23.8-inch                        | 1         | 1.32%   |
| LG Display LCD Monitor LGD06FF 1920x1080 344x194mm 15.5-inch          | 1         | 1.32%   |
| LG Display LCD Monitor LGD065E 2560x1600 366x229mm 17.0-inch          | 1         | 1.32%   |
| LG Display LCD Monitor LGD059D 1920x1080 309x174mm 14.0-inch          | 1         | 1.32%   |
| LG Display LCD Monitor LGD051D 1920x1080 309x174mm 14.0-inch          | 1         | 1.32%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch           | 1         | 1.32%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch          | 1         | 1.32%   |
| LG Display LCD Monitor LGD03DE 1600x900 382x215mm 17.3-inch           | 1         | 1.32%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch           | 1         | 1.32%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch           | 1         | 1.32%   |
| Lenovo LEN-A-A LENF918 1920x1080 596x335mm 26.9-inch                  | 1         | 1.32%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 1         | 1.32%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch               | 1         | 1.32%   |
| Hewlett-Packard X27i HPN3678 2560x1440 597x336mm 27.0-inch            | 1         | 1.32%   |
| Hewlett-Packard E243i HPN3463 1920x1200 518x324mm 24.1-inch           | 1         | 1.32%   |
| Hewlett-Packard 27fh HPN354A 1920x1080 598x336mm 27.0-inch            | 1         | 1.32%   |
| Hewlett-Packard 27f HPN354B 1920x1080 598x336mm 27.0-inch             | 1         | 1.32%   |
| Hewlett-Packard 23xw HWP318C 1920x1080 509x286mm 23.0-inch            | 1         | 1.32%   |
| Hewlett-Packard 23cw HWP3187 1920x1080 509x286mm 23.0-inch            | 1         | 1.32%   |
| Goldstar W1946 GSM4BCD 1360x768 406x229mm 18.4-inch                   | 1         | 1.32%   |
| Goldstar ULTRAGEAR GSM5BB4 2560x1440 597x336mm 27.0-inch              | 1         | 1.32%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch               | 1         | 1.32%   |
| Eizo EV3285 ENC2979 3840x2160 698x393mm 31.5-inch                     | 1         | 1.32%   |
| Dell UP3216Q DEL40C2 3840x2160 698x393mm 31.5-inch                    | 1         | 1.32%   |
| Dell U2415 DELA0BC 1920x1200 518x324mm 24.1-inch                      | 1         | 1.32%   |
| Dell U2414H DELA0B2 1920x1080 527x296mm 23.8-inch                     | 1         | 1.32%   |
| Dell AW3423DWF DELA212 3440x1440 800x337mm 34.2-inch                  | 1         | 1.32%   |
| Chimei Innolux LCD Monitor CMN175A 1920x1080 381x214mm 17.2-inch      | 1         | 1.32%   |
| Chimei Innolux LCD Monitor CMN1610 1920x1200 344x215mm 16.0-inch      | 1         | 1.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 36        | 53.73%  |
| 1366x768 (WXGA)    | 7         | 10.45%  |
| 3840x2160 (4K)     | 4         | 5.97%   |
| 2560x1440 (QHD)    | 4         | 5.97%   |
| 1680x1050 (WSXGA+) | 3         | 4.48%   |
| 3440x1440          | 2         | 2.99%   |
| 1600x900 (HD+)     | 2         | 2.99%   |
| 3840x1080          | 1         | 1.49%   |
| 3456x2160          | 1         | 1.49%   |
| 2560x1600          | 1         | 1.49%   |
| 2256x1504          | 1         | 1.49%   |
| 2160x1440          | 1         | 1.49%   |
| 1920x540           | 1         | 1.49%   |
| 1920x1200 (WUXGA)  | 1         | 1.49%   |
| 1440x900 (WXGA+)   | 1         | 1.49%   |
| 1360x768           | 1         | 1.49%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 20        | 28.17%  |
| 27      | 10        | 14.08%  |
| 14      | 8         | 11.27%  |
| 23      | 4         | 5.63%   |
| 31      | 3         | 4.23%   |
| 24      | 3         | 4.23%   |
| 17      | 3         | 4.23%   |
| 13      | 3         | 4.23%   |
| 34      | 2         | 2.82%   |
| 20      | 2         | 2.82%   |
| 16      | 2         | 2.82%   |
| 12      | 2         | 2.82%   |
| 49      | 1         | 1.41%   |
| 40      | 1         | 1.41%   |
| 32      | 1         | 1.41%   |
| 26      | 1         | 1.41%   |
| 22      | 1         | 1.41%   |
| 21      | 1         | 1.41%   |
| 19      | 1         | 1.41%   |
| 18      | 1         | 1.41%   |
| Unknown | 1         | 1.41%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 30        | 44.78%  |
| 501-600     | 16        | 23.88%  |
| 401-500     | 4         | 5.97%   |
| 351-400     | 4         | 5.97%   |
| 201-300     | 4         | 5.97%   |
| 701-800     | 3         | 4.48%   |
| 601-700     | 3         | 4.48%   |
| 801-900     | 1         | 1.49%   |
| 1001-1500   | 1         | 1.49%   |
| Unknown     | 1         | 1.49%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 49        | 77.78%  |
| 16/10 | 8         | 12.7%   |
| 32/9  | 2         | 3.17%   |
| 3/2   | 2         | 3.17%   |
| 21/9  | 2         | 3.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 21        | 30.43%  |
| 301-350        | 11        | 15.94%  |
| 81-90          | 10        | 14.49%  |
| 201-250        | 7         | 10.14%  |
| 351-500        | 5         | 7.25%   |
| 151-200        | 3         | 4.35%   |
| 121-130        | 3         | 4.35%   |
| 61-70          | 2         | 2.9%    |
| 501-1000       | 2         | 2.9%    |
| 71-80          | 1         | 1.45%   |
| 251-300        | 1         | 1.45%   |
| 141-150        | 1         | 1.45%   |
| 111-120        | 1         | 1.45%   |
| Unknown        | 1         | 1.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 25        | 37.88%  |
| 51-100        | 18        | 27.27%  |
| 101-120       | 13        | 19.7%   |
| 161-240       | 8         | 12.12%  |
| More than 240 | 1         | 1.52%   |
| Unknown       | 1         | 1.52%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 48        | 78.69%  |
| 2     | 10        | 16.39%  |
| 3     | 3         | 4.92%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 36        | 42.86%  |
| Realtek Semiconductor | 29        | 34.52%  |
| Qualcomm Atheros      | 8         | 9.52%   |
| Broadcom              | 3         | 3.57%   |
| Sierra Wireless       | 1         | 1.19%   |
| Ralink                | 1         | 1.19%   |
| Qualcomm              | 1         | 1.19%   |
| NetGear               | 1         | 1.19%   |
| MediaTek              | 1         | 1.19%   |
| HMD Global            | 1         | 1.19%   |
| Fibocom               | 1         | 1.19%   |
| ELATEC                | 1         | 1.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 24        | 22.86%  |
| Intel Wi-Fi 6 AX200                                                    | 4         | 3.81%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 3         | 2.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 3         | 2.86%   |
| Intel Wireless 8265 / 8275                                             | 3         | 2.86%   |
| Intel Ethernet Connection (2) I219-V                                   | 3         | 2.86%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 2         | 1.9%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 2         | 1.9%    |
| Intel Wireless 7260                                                    | 2         | 1.9%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 2         | 1.9%    |
| Intel Wi-Fi 6 AX201                                                    | 2         | 1.9%    |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 2         | 1.9%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 2         | 1.9%    |
| Intel Ethernet Connection I217-V                                       | 2         | 1.9%    |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 1.9%    |
| Sierra Wireless EM7430 Qualcomm Snapdragon X7 LTE-A                    | 1         | 0.95%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 1         | 0.95%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 1         | 0.95%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 1         | 0.95%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 1         | 0.95%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 0.95%   |
| Realtek 802.11ac WLAN Adapter                                          | 1         | 0.95%   |
| Ralink RT5390R PCIe 802.11b/g/n Wireless Network Adapter               | 1         | 0.95%   |
| Qualcomm QCNFA765 Wireless Network Adapter                             | 1         | 0.95%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 1         | 0.95%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 1         | 0.95%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 0.95%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1         | 0.95%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)         | 1         | 0.95%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 1         | 0.95%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 1         | 0.95%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]            | 1         | 0.95%   |
| MediaTek MT7925 (RZ717) Wi-Fi 7 160MHz                                 | 1         | 0.95%   |
| Intel Wireless 7265                                                    | 1         | 0.95%   |
| Intel Wireless 3165                                                    | 1         | 0.95%   |
| Intel Wireless 3160                                                    | 1         | 0.95%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 1         | 0.95%   |
| Intel I211 Gigabit Network Connection                                  | 1         | 0.95%   |
| Intel Ethernet Controller I225-V                                       | 1         | 0.95%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 0.95%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 29        | 55.77%  |
| Realtek Semiconductor | 8         | 15.38%  |
| Qualcomm Atheros      | 7         | 13.46%  |
| Broadcom              | 2         | 3.85%   |
| Sierra Wireless       | 1         | 1.92%   |
| Ralink                | 1         | 1.92%   |
| Qualcomm              | 1         | 1.92%   |
| NetGear               | 1         | 1.92%   |
| MediaTek              | 1         | 1.92%   |
| Fibocom               | 1         | 1.92%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 4         | 7.41%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 3         | 5.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 3         | 5.56%   |
| Intel Wireless 8265 / 8275                                     | 3         | 5.56%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 3.7%    |
| Intel Wireless 7260                                            | 2         | 3.7%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 2         | 3.7%    |
| Intel Wi-Fi 6 AX201                                            | 2         | 3.7%    |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 2         | 3.7%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 3.7%    |
| Sierra Wireless EM7430 Qualcomm Snapdragon X7 LTE-A            | 1         | 1.85%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 1.85%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 1.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 1.85%   |
| Realtek 802.11ac WLAN Adapter                                  | 1         | 1.85%   |
| Ralink RT5390R PCIe 802.11b/g/n Wireless Network Adapter       | 1         | 1.85%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 1         | 1.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 1.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 1.85%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 1.85%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 1.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 1.85%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]    | 1         | 1.85%   |
| MediaTek MT7925 (RZ717) Wi-Fi 7 160MHz                         | 1         | 1.85%   |
| Intel Wireless 7265                                            | 1         | 1.85%   |
| Intel Wireless 3165                                            | 1         | 1.85%   |
| Intel Wireless 3160                                            | 1         | 1.85%   |
| Intel Raptor Lake PCH CNVi WiFi                                | 1         | 1.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 1.85%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 1.85%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 1         | 1.85%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 1.85%   |
| Intel Centrino Advanced-N 6235                                 | 1         | 1.85%   |
| Intel Centrino Advanced-N 6200                                 | 1         | 1.85%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 1.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 1.85%   |
| Fibocom L830-EB-00 LTE WWAN Modem                              | 1         | 1.85%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 1         | 1.85%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 1         | 1.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 27        | 55.1%   |
| Intel                 | 18        | 36.73%  |
| Qualcomm Atheros      | 2         | 4.08%   |
| HMD Global            | 1         | 2.04%   |
| Broadcom              | 1         | 2.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 24        | 48%     |
| Intel Ethernet Connection (2) I219-V                                   | 3         | 6%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 2         | 4%      |
| Intel Ethernet Connection I217-V                                       | 2         | 4%      |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 4%      |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 1         | 2%      |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 2%      |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 2%      |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1         | 2%      |
| Intel I211 Gigabit Network Connection                                  | 1         | 2%      |
| Intel Ethernet Controller I225-V                                       | 1         | 2%      |
| Intel Ethernet Connection I219-LM                                      | 1         | 2%      |
| Intel Ethernet Connection I218-V                                       | 1         | 2%      |
| Intel Ethernet Connection I217-LM                                      | 1         | 2%      |
| Intel Ethernet Connection (7) I219-LM                                  | 1         | 2%      |
| Intel Ethernet Connection (6) I219-V                                   | 1         | 2%      |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 2%      |
| Intel Ethernet Connection (2) I218-LM                                  | 1         | 2%      |
| Intel Ethernet Connection (10) I219-LM                                 | 1         | 2%      |
| Intel 82577LM Gigabit Network Connection                               | 1         | 2%      |
| HMD Global Nokia7.2                                                    | 1         | 2%      |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 1         | 2%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 49        | 50.52%  |
| WiFi     | 47        | 48.45%  |
| Modem    | 1         | 1.03%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 40        | 71.43%  |
| Ethernet | 16        | 28.57%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 33        | 56.9%   |
| 1     | 21        | 36.21%  |
| 3     | 2         | 3.45%   |
| 0     | 2         | 3.45%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 42        | 67.74%  |
| Yes  | 20        | 32.26%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 25        | 55.56%  |
| Realtek Semiconductor           | 7         | 15.56%  |
| Lite-On Technology              | 3         | 6.67%   |
| Qualcomm Atheros Communications | 2         | 4.44%   |
| Edimax Technology               | 2         | 4.44%   |
| Cambridge Silicon Radio         | 2         | 4.44%   |
| MediaTek                        | 1         | 2.22%   |
| IMC Networks                    | 1         | 2.22%   |
| Foxconn / Hon Hai               | 1         | 2.22%   |
| Broadcom                        | 1         | 2.22%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                      | 7         | 15.56%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)          | 4         | 8.89%   |
| Intel AX201 Bluetooth                                   | 4         | 8.89%   |
| Intel AX200 Bluetooth                                   | 4         | 8.89%   |
| Realtek  Bluetooth 4.2 Adapter                          | 3         | 6.67%   |
| Realtek Bluetooth Radio                                 | 3         | 6.67%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                | 2         | 4.44%   |
| Intel AX210 Bluetooth                                   | 2         | 4.44%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)     | 2         | 4.44%   |
| Realtek RTL8723B Bluetooth                              | 1         | 2.22%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                  | 1         | 2.22%   |
| Qualcomm Atheros AR3011 Bluetooth                       | 1         | 2.22%   |
| MediaTek Wireless_Device                                | 1         | 2.22%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth              | 1         | 2.22%   |
| Lite-On Bluetooth Device                                | 1         | 2.22%   |
| Lite-On Atheros AR3012 Bluetooth                        | 1         | 2.22%   |
| Intel Centrino Bluetooth Wireless Transceiver           | 1         | 2.22%   |
| Intel Bluetooth Device                                  | 1         | 2.22%   |
| IMC Networks Wireless_Device                            | 1         | 2.22%   |
| Foxconn / Hon Hai Bluetooth Device                      | 1         | 2.22%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter | 1         | 2.22%   |
| Edimax Bluetooth Device                                 | 1         | 2.22%   |
| Broadcom HP Portable Bumble Bee                         | 1         | 2.22%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 41        | 50.62%  |
| AMD                     | 22        | 27.16%  |
| Nvidia                  | 6         | 7.41%   |
| C-Media Electronics     | 2         | 2.47%   |
| Astro Gaming            | 2         | 2.47%   |
| SAVITECH                | 1         | 1.23%   |
| Realtek Semiconductor   | 1         | 1.23%   |
| Logitech                | 1         | 1.23%   |
| Lenovo                  | 1         | 1.23%   |
| Kingston Technology     | 1         | 1.23%   |
| Hewlett-Packard         | 1         | 1.23%   |
| GN Netcom               | 1         | 1.23%   |
| Cambridge Silicon Radio | 1         | 1.23%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                              | 10        | 9.43%   |
| Intel Sunrise Point-LP HD Audio                                            | 5         | 4.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 3.77%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 3.77%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 3.77%   |
| Intel 200 Series PCH HD Audio                                              | 4         | 3.77%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 3.77%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 2.83%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3         | 2.83%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 3         | 2.83%   |
| AMD Radeon High Definition Audio Controller                                | 3         | 2.83%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 3         | 2.83%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3         | 2.83%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 1.89%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 1.89%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 1.89%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 1.89%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 2         | 1.89%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 1.89%   |
| Astro Gaming Astro A50                                                     | 2         | 1.89%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 2         | 1.89%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2         | 1.89%   |
| SAVITECH MX3                                                               | 1         | 0.94%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.94%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 0.94%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.94%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 0.94%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.94%   |
| Logitech Blue Microphones                                                  | 1         | 0.94%   |
| Lenovo ThinkPad Dock USB Audio                                             | 1         | 0.94%   |
| Kingston Technology HyperX 7.1 Audio                                       | 1         | 0.94%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 0.94%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 1         | 0.94%   |
| Intel Jasper Lake HD Audio                                                 | 1         | 0.94%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 0.94%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 0.94%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 0.94%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 0.94%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 0.94%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 0.94%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 13        | 22.03%  |
| Samsung Electronics | 13        | 22.03%  |
| Crucial             | 7         | 11.86%  |
| Kingston            | 6         | 10.17%  |
| G.Skill             | 6         | 10.17%  |
| Micron Technology   | 5         | 8.47%   |
| Corsair             | 3         | 5.08%   |
| Nanya Technology    | 2         | 3.39%   |
| Unknown             | 1         | 1.69%   |
| Ramsta              | 1         | 1.69%   |
| Elpida              | 1         | 1.69%   |
| A-DATA Technology   | 1         | 1.69%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 3.33%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 2         | 3.33%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 3.33%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 3.33%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                        | 1         | 1.67%   |
| SK hynix RAM HMT451U6DFR8A-PB 4GB DIMM DDR3 1600MT/s             | 1         | 1.67%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.67%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.67%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 1         | 1.67%   |
| SK hynix RAM HMA81GU6CJR8N-VK 8GB DIMM DDR4 2400MT/s             | 1         | 1.67%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.67%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.67%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 1.67%   |
| SK hynix RAM H9CCNNNCLGALAR-NUD 8GB Row Of Chips LPDDR3 1867MT/s | 1         | 1.67%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 1         | 1.67%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 1         | 1.67%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.67%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 1         | 1.67%   |
| Samsung RAM M471A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s           | 1         | 1.67%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.67%   |
| Samsung RAM M471A1G44AB0-CWE 8GiB SODIMM DDR4 3200MT/s           | 1         | 1.67%   |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s         | 1         | 1.67%   |
| Samsung RAM K4UBE3D4AA-MGCL 8GB Row Of Chips LPDDR4 4267MT/s     | 1         | 1.67%   |
| Ramsta RAM 3200MHz-16G 16GB SODIMM DDR4 3200MT/s                 | 1         | 1.67%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s             | 1         | 1.67%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s             | 1         | 1.67%   |
| Micron RAM Module 16GB SODIMM DDR4 3200MT/s                      | 1         | 1.67%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 1         | 1.67%   |
| Micron RAM 4ATF25664HZ-2G3B1 2GB SODIMM DDR4 2400MT/s            | 1         | 1.67%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 1         | 1.67%   |
| Micron RAM ...d 4096MB SODIMM DDR3 1067MT/s                      | 1         | 1.67%   |
| Kingston RAM Module 8GB DIMM DDR4 3200MT/s                       | 1         | 1.67%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s             | 1         | 1.67%   |
| Kingston RAM KHX3000C15D4/8GX 8GB DIMM DDR4 3400MT/s             | 1         | 1.67%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s            | 1         | 1.67%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s           | 1         | 1.67%   |
| Kingston RAM 99U5663-007.A00G 16GB SODIMM DDR4 2667MT/s          | 1         | 1.67%   |
| G.Skill RAM F4-3600C16-8GTZR 8GB DIMM DDR4 3600MT/s              | 1         | 1.67%   |
| G.Skill RAM F4-3200C16-16GTZN 16GB DIMM DDR4 3200MT/s            | 1         | 1.67%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s              | 1         | 1.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 33        | 67.35%  |
| DDR3   | 10        | 20.41%  |
| DDR5   | 3         | 6.12%   |
| SDRAM  | 1         | 2.04%   |
| LPDDR4 | 1         | 2.04%   |
| LPDDR3 | 1         | 2.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 33        | 67.35%  |
| DIMM         | 13        | 26.53%  |
| Row Of Chips | 3         | 6.12%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 26        | 48.15%  |
| 16384 | 13        | 24.07%  |
| 4096  | 12        | 22.22%  |
| 32768 | 2         | 3.7%    |
| 2048  | 1         | 1.85%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 13        | 24.07%  |
| 2667  | 13        | 24.07%  |
| 1600  | 7         | 12.96%  |
| 2400  | 5         | 9.26%   |
| 4800  | 2         | 3.7%    |
| 3600  | 2         | 3.7%    |
| 3000  | 2         | 3.7%    |
| 1067  | 2         | 3.7%    |
| 5600  | 1         | 1.85%   |
| 4267  | 1         | 1.85%   |
| 4199  | 1         | 1.85%   |
| 3400  | 1         | 1.85%   |
| 3266  | 1         | 1.85%   |
| 2666  | 1         | 1.85%   |
| 1867  | 1         | 1.85%   |
| 1334  | 1         | 1.85%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 25%     |
| Hewlett-Packard     | 1         | 25%     |
| Canon               | 1         | 25%     |
| Brother Industries  | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Samsung M2070 Series   | 1         | 25%     |
| HP DeskJet 3630 series | 1         | 25%     |
| Canon TS8000 series    | 1         | 25%     |
| Brother MFC-J1010DW    | 1         | 25%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| Mustek Systems | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Mustek Systems ScanExpress 600 CU | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 13        | 29.55%  |
| Logitech                               | 5         | 11.36%  |
| IMC Networks                           | 5         | 11.36%  |
| Realtek Semiconductor                  | 4         | 9.09%   |
| Microdia                               | 3         | 6.82%   |
| Bison Electronics                      | 3         | 6.82%   |
| WaveRider Communications               | 1         | 2.27%   |
| Suyin                                  | 1         | 2.27%   |
| Silicon Motion                         | 1         | 2.27%   |
| Quanta                                 | 1         | 2.27%   |
| Primax Electronics                     | 1         | 2.27%   |
| Microsoft                              | 1         | 2.27%   |
| Luxvisions Innotech Limited            | 1         | 2.27%   |
| Lite-On Technology                     | 1         | 2.27%   |
| Framework                              | 1         | 2.27%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.27%   |
| A4Tech                                 | 1         | 2.27%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony HD WebCam                                              | 4         | 8.89%   |
| Realtek Integrated_Webcam_HD                                   | 3         | 6.67%   |
| Microdia Integrated_Webcam_HD                                  | 2         | 4.44%   |
| Logitech Webcam C270                                           | 2         | 4.44%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 2         | 4.44%   |
| Chicony Integrated Camera                                      | 2         | 4.44%   |
| Bison Integrated Camera                                        | 2         | 4.44%   |
| WaveRider USB Live camera                                      | 1         | 2.22%   |
| Suyin 1.3M HD WebCam                                           | 1         | 2.22%   |
| Silicon Motion USB 2.0 PC Cam                                  | 1         | 2.22%   |
| Realtek FULL HD 1080P Webcam                                   | 1         | 2.22%   |
| Quanta HP Webcam                                               | 1         | 2.22%   |
| Primax Villem                                                  | 1         | 2.22%   |
| Microsoft LifeCam Cinema                                       | 1         | 2.22%   |
| Microdia HDE Webcam USB                                        | 1         | 2.22%   |
| Luxvisions Innotech Limited Integrated Camera                  | 1         | 2.22%   |
| Logitech QuickCam Pro 9000                                     | 1         | 2.22%   |
| Logitech HD Webcam C615                                        | 1         | 2.22%   |
| Logitech HD Pro Webcam C920                                    | 1         | 2.22%   |
| Lite-On Integrated Camera                                      | 1         | 2.22%   |
| IMC Networks SunplusIT Integrated Camera                       | 1         | 2.22%   |
| IMC Networks Lenovo EasyCamera                                 | 1         | 2.22%   |
| IMC Networks Integrated Camera                                 | 1         | 2.22%   |
| Framework Laptop Webcam Module (2nd Gen)                       | 1         | 2.22%   |
| Chicony VGA WebCam                                             | 1         | 2.22%   |
| Chicony USB2.0 HD UVC WebCam                                   | 1         | 2.22%   |
| Chicony ThinkPad T490 Webcam                                   | 1         | 2.22%   |
| Chicony HP Webcam                                              | 1         | 2.22%   |
| Chicony HP HD Webcam [Fixed]                                   | 1         | 2.22%   |
| Chicony HP HD Camera                                           | 1         | 2.22%   |
| Chicony HP 5MP Camera                                          | 1         | 2.22%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 2.22%   |
| Bison SunplusIT Integrated Camera                              | 1         | 2.22%   |
| Bison Integrated IR Camera                                     | 1         | 2.22%   |
| A4Tech PK-635G                                                 | 1         | 2.22%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 40%     |
| Synaptics                  | 4         | 40%     |
| Shenzhen Goodix Technology | 1         | 10%     |
| LighTuning Technology      | 1         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader              | 1         | 10%     |
| Validity Sensors VFS451 Fingerprint Reader               | 1         | 10%     |
| Validity Sensors VFS Fingerprint sensor                  | 1         | 10%     |
| Validity Sensors Synaptics WBDI                          | 1         | 10%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 1         | 10%     |
| Synaptics Metallica MOH Touch Fingerprint Reader         | 1         | 10%     |
| Synaptics Metallica MIS Touch Fingerprint Reader         | 1         | 10%     |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 10%     |
| Shenzhen Goodix Fingerprint Reader                       | 1         | 10%     |
| LighTuning EgisTec Touch Fingerprint Sensor              | 1         | 10%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 2         | 66.67%  |
| Broadcom    | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 2         | 66.67%  |
| Broadcom 5880                       | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 43        | 72.88%  |
| 1     | 13        | 22.03%  |
| 2     | 3         | 5.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 10        | 52.63%  |
| Unassigned class         | 2         | 10.53%  |
| Chipcard                 | 2         | 10.53%  |
| Sound                    | 1         | 5.26%   |
| Net/wireless             | 1         | 5.26%   |
| Graphics card            | 1         | 5.26%   |
| Communication controller | 1         | 5.26%   |
| Card reader              | 1         | 5.26%   |

