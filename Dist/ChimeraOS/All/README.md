ChimeraOS - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for ChimeraOS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/ChimeraOS/Desktop/README.md) and [notebooks](/Dist/ChimeraOS/Notebook/README.md).

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

Total: 235

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Apple         | Mac-F2268DAE                | All in one  | [9e279775ed](https://linux-hardware.org/?probe=9e279775ed) | May 07, 2024 |
| Soyo          | SY-Classic B450M            | Desktop     | [e82641ba3c](https://linux-hardware.org/?probe=e82641ba3c) | May 02, 2024 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | Notebook    | [eefd534cd5](https://linux-hardware.org/?probe=eefd534cd5) | May 01, 2024 |
| GPD           | G1618-04                    | Notebook    | [2c1da6a68d](https://linux-hardware.org/?probe=2c1da6a68d) | Apr 26, 2024 |
| Shenzhen M... | DRFXI                       | Desktop     | [951a976cb0](https://linux-hardware.org/?probe=951a976cb0) | Apr 18, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [c0a20b5a39](https://linux-hardware.org/?probe=c0a20b5a39) | Apr 14, 2024 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [635072047d](https://linux-hardware.org/?probe=635072047d) | Apr 14, 2024 |
| HP            | 1905                        | Desktop     | [64d13b2833](https://linux-hardware.org/?probe=64d13b2833) | Apr 12, 2024 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [f939a8ab03](https://linux-hardware.org/?probe=f939a8ab03) | Apr 04, 2024 |
| GPD           | P2 MAX                      | Notebook    | [8e53b3ed39](https://linux-hardware.org/?probe=8e53b3ed39) | Apr 01, 2024 |
| ASUSTek       | PRIME B550M-A               | Notebook    | [e5fc501332](https://linux-hardware.org/?probe=e5fc501332) | Mar 31, 2024 |
| Dell          | 0Y7WYT A00                  | Desktop     | [5843a8bea7](https://linux-hardware.org/?probe=5843a8bea7) | Mar 25, 2024 |
| ASUSTek       | ROG Ally RC71L_RC71L        | Tablet      | [47b8c30a82](https://linux-hardware.org/?probe=47b8c30a82) | Mar 21, 2024 |
| Acer          | Aspire E5-575G              | Notebook    | [83b5323b19](https://linux-hardware.org/?probe=83b5323b19) | Mar 18, 2024 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | Desktop     | [4811d76465](https://linux-hardware.org/?probe=4811d76465) | Mar 18, 2024 |
| ONE-NETBOO... | ONEXPLAYER F1               | Tablet      | [2b4990129d](https://linux-hardware.org/?probe=2b4990129d) | Mar 16, 2024 |
| Dell          | Precision 5570              | Notebook    | [65270db170](https://linux-hardware.org/?probe=65270db170) | Mar 13, 2024 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [ff4ef16193](https://linux-hardware.org/?probe=ff4ef16193) | Mar 11, 2024 |
| ASUSTek       | PRIME B550M-A               | Notebook    | [ed405fd8da](https://linux-hardware.org/?probe=ed405fd8da) | Mar 11, 2024 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [75db640e66](https://linux-hardware.org/?probe=75db640e66) | Mar 10, 2024 |
| AYANEO        | AIR Pro                     | Tablet      | [6caf615aeb](https://linux-hardware.org/?probe=6caf615aeb) | Mar 09, 2024 |
| ASUSTek       | G551JX                      | Notebook    | [8a875afd94](https://linux-hardware.org/?probe=8a875afd94) | Mar 08, 2024 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [9fc35ed4b6](https://linux-hardware.org/?probe=9fc35ed4b6) | Mar 08, 2024 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [d9770af085](https://linux-hardware.org/?probe=d9770af085) | Mar 06, 2024 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | Desktop     | [964e9fc189](https://linux-hardware.org/?probe=964e9fc189) | Mar 06, 2024 |
| HC Technol... | HCAR6000-MI2                | Desktop     | [e84a5cbddb](https://linux-hardware.org/?probe=e84a5cbddb) | Mar 04, 2024 |
| Dell          | 02YYK5 A01                  | Desktop     | [fa518467ad](https://linux-hardware.org/?probe=fa518467ad) | Mar 04, 2024 |
| Gigabyte      | A520I AC                    | Desktop     | [6623b5eb34](https://linux-hardware.org/?probe=6623b5eb34) | Mar 04, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [df560f1f39](https://linux-hardware.org/?probe=df560f1f39) | Mar 03, 2024 |
| Acidanther... | Mac-7BA5B2D9E42DDD94 iMa... | All in one  | [d05a394fc8](https://linux-hardware.org/?probe=d05a394fc8) | Mar 02, 2024 |
| HC Technol... | HCAR5000-MI                 | Desktop     | [4db4f0aa29](https://linux-hardware.org/?probe=4db4f0aa29) | Mar 02, 2024 |
| Gigabyte      | A620I AX                    | Desktop     | [684be66545](https://linux-hardware.org/?probe=684be66545) | Feb 29, 2024 |
| Intel         | DH61WW AAG23116-302         | Desktop     | [eda91e0749](https://linux-hardware.org/?probe=eda91e0749) | Feb 26, 2024 |
| Dell          | 0NKW6Y A02                  | Desktop     | [59a10b16df](https://linux-hardware.org/?probe=59a10b16df) | Feb 17, 2024 |
| Lenovo        | 3130 SDK0J40697 WIN 3305... | Mini pc     | [0deaf8efb4](https://linux-hardware.org/?probe=0deaf8efb4) | Feb 17, 2024 |
| Micro Comp... | HX100G                      | Notebook    | [30d14495d2](https://linux-hardware.org/?probe=30d14495d2) | Feb 15, 2024 |
| ASRock        | 970M Pro3                   | Desktop     | [3fdb7d7227](https://linux-hardware.org/?probe=3fdb7d7227) | Feb 12, 2024 |
| HP            | 89D8 SMVB                   | Desktop     | [2130b12c50](https://linux-hardware.org/?probe=2130b12c50) | Feb 09, 2024 |
| ASUSTek       | ROG Ally RC71L_RC71L        | Tablet      | [72f1930494](https://linux-hardware.org/?probe=72f1930494) | Feb 08, 2024 |
| ASUSTek       | ROG Ally RC71L_RC71L        | Tablet      | [26aa825b43](https://linux-hardware.org/?probe=26aa825b43) | Feb 08, 2024 |
| Gigabyte      | A520I AC                    | Desktop     | [914c716ebc](https://linux-hardware.org/?probe=914c716ebc) | Feb 05, 2024 |
| Acidanther... | Mac-7BA5B2D9E42DDD94 iMa... | All in one  | [59fa8206eb](https://linux-hardware.org/?probe=59fa8206eb) | Feb 04, 2024 |
| Shenzhen M... | F7BSC                       | Mini pc     | [37b70e517a](https://linux-hardware.org/?probe=37b70e517a) | Feb 03, 2024 |
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [f39c1ef04f](https://linux-hardware.org/?probe=f39c1ef04f) | Jan 27, 2024 |
| Gateway       | IPISB-VR                    | Desktop     | [31d92a1fe6](https://linux-hardware.org/?probe=31d92a1fe6) | Jan 25, 2024 |
| Intel         | H61                         | Desktop     | [d3895696ad](https://linux-hardware.org/?probe=d3895696ad) | Jan 23, 2024 |
| ASUSTek       | AM1M-A                      | Desktop     | [6b24e4acaf](https://linux-hardware.org/?probe=6b24e4acaf) | Jan 22, 2024 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [0a04043949](https://linux-hardware.org/?probe=0a04043949) | Jan 22, 2024 |
| Acer          | Aspire V3-772G              | Notebook    | [e9bc1c5d68](https://linux-hardware.org/?probe=e9bc1c5d68) | Jan 19, 2024 |
| Dell          | Latitude 7310               | Notebook    | [664667c69b](https://linux-hardware.org/?probe=664667c69b) | Jan 19, 2024 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [85f96ac567](https://linux-hardware.org/?probe=85f96ac567) | Jan 14, 2024 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [3885b0cee8](https://linux-hardware.org/?probe=3885b0cee8) | Jan 12, 2024 |
| HP            | Pavilion 15                 | Notebook    | [dad46e573f](https://linux-hardware.org/?probe=dad46e573f) | Jan 07, 2024 |
| HP            | 885F A                      | Desktop     | [3050f4d975](https://linux-hardware.org/?probe=3050f4d975) | Jan 05, 2024 |
| HP            | 885F A                      | Desktop     | [7f484d8166](https://linux-hardware.org/?probe=7f484d8166) | Jan 05, 2024 |
| MSI           | Z87-G41 PC Mate             | Desktop     | [36d3fe7f0a](https://linux-hardware.org/?probe=36d3fe7f0a) | Jan 03, 2024 |
| MSI           | PRO B650-P WIFI             | Desktop     | [544a799ce8](https://linux-hardware.org/?probe=544a799ce8) | Jan 02, 2024 |
| ASRock        | Z77 Professional            | Desktop     | [d1d9fce85d](https://linux-hardware.org/?probe=d1d9fce85d) | Jan 01, 2024 |
| ASUSTek       | ROG Ally RC71L_RC71L        | Tablet      | [d492f561d9](https://linux-hardware.org/?probe=d492f561d9) | Dec 31, 2023 |
| ASUSTek       | G74Sx                       | Notebook    | [0933c174aa](https://linux-hardware.org/?probe=0933c174aa) | Dec 30, 2023 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | Desktop     | [dffaa09f84](https://linux-hardware.org/?probe=dffaa09f84) | Dec 29, 2023 |
| Sony          | SVS13A25PLB                 | Notebook    | [9b32de2519](https://linux-hardware.org/?probe=9b32de2519) | Dec 27, 2023 |
| HP            | ProBook 4540s               | Notebook    | [fbed208acc](https://linux-hardware.org/?probe=fbed208acc) | Dec 23, 2023 |
| HP            | ProBook 4540s               | Notebook    | [27155e8350](https://linux-hardware.org/?probe=27155e8350) | Dec 22, 2023 |
| Valve         | Galileo                     | Notebook    | [355d2e1a38](https://linux-hardware.org/?probe=355d2e1a38) | Dec 17, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [0018284858](https://linux-hardware.org/?probe=0018284858) | Dec 17, 2023 |
| AYANEO        | 2                           | Tablet      | [78a21ff7fb](https://linux-hardware.org/?probe=78a21ff7fb) | Dec 16, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [f65efa02b6](https://linux-hardware.org/?probe=f65efa02b6) | Dec 16, 2023 |
| Shenzhen M... | F7BSD                       | Mini pc     | [10527fec61](https://linux-hardware.org/?probe=10527fec61) | Dec 16, 2023 |
| Shenzhen M... | F7BSC                       | Mini pc     | [69de9d26c7](https://linux-hardware.org/?probe=69de9d26c7) | Dec 15, 2023 |
| Dell          | 07WP95 A02                  | Desktop     | [b5d957b7ec](https://linux-hardware.org/?probe=b5d957b7ec) | Dec 12, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [ea510ad39c](https://linux-hardware.org/?probe=ea510ad39c) | Dec 09, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [108ddf7f8e](https://linux-hardware.org/?probe=108ddf7f8e) | Dec 07, 2023 |
| ZOTAC         | ZBOX-ECM73070C/53060C       | Mini pc     | [34d2104b8a](https://linux-hardware.org/?probe=34d2104b8a) | Dec 06, 2023 |
| Notebook      | P15SM-A/SM1-A               | Notebook    | [f7c8033eef](https://linux-hardware.org/?probe=f7c8033eef) | Dec 06, 2023 |
| Dell          | 07HXY6 A01                  | Desktop     | [37ba613bd3](https://linux-hardware.org/?probe=37ba613bd3) | Dec 01, 2023 |
| Dell          | 0T0MHW A03                  | Desktop     | [91cd726063](https://linux-hardware.org/?probe=91cd726063) | Nov 30, 2023 |
| ASUSTek       | PRIME X370-A                | Desktop     | [491dd5c51b](https://linux-hardware.org/?probe=491dd5c51b) | Nov 28, 2023 |
| Gigabyte      | A520I AC                    | Desktop     | [9672d50090](https://linux-hardware.org/?probe=9672d50090) | Nov 28, 2023 |
| Dell          | Latitude E5540              | Notebook    | [33e3a21810](https://linux-hardware.org/?probe=33e3a21810) | Nov 25, 2023 |
| ASUSTek       | Unknown                     | Notebook    | [7cb8811992](https://linux-hardware.org/?probe=7cb8811992) | Nov 25, 2023 |
| ASUSTek       | Unknown                     | Notebook    | [9d2fdb067c](https://linux-hardware.org/?probe=9d2fdb067c) | Nov 25, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO S      | Desktop     | [606a157eb4](https://linux-hardware.org/?probe=606a157eb4) | Nov 24, 2023 |
| Dell          | 03KWTV A00                  | Desktop     | [f641738a49](https://linux-hardware.org/?probe=f641738a49) | Nov 23, 2023 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [4048fd2631](https://linux-hardware.org/?probe=4048fd2631) | Nov 22, 2023 |
| Acer          | Aspire V3-772G              | Notebook    | [742d987926](https://linux-hardware.org/?probe=742d987926) | Nov 21, 2023 |
| Gigabyte      | B550M AORUS ELITE AX        | Notebook    | [4e71e8e7b7](https://linux-hardware.org/?probe=4e71e8e7b7) | Nov 20, 2023 |
| Dell          | 0H1TR9 A00                  | All in one  | [d4fe05dcab](https://linux-hardware.org/?probe=d4fe05dcab) | Nov 20, 2023 |
| Gigabyte      | A520M H                     | Desktop     | [abba035964](https://linux-hardware.org/?probe=abba035964) | Nov 19, 2023 |
| ASRock        | Z87 Extreme4                | Desktop     | [84a46af7ee](https://linux-hardware.org/?probe=84a46af7ee) | Nov 19, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [694b0754fa](https://linux-hardware.org/?probe=694b0754fa) | Nov 18, 2023 |
| Dell          | 0DY62R A01                  | Desktop     | [03f9c7a1f2](https://linux-hardware.org/?probe=03f9c7a1f2) | Nov 17, 2023 |
| HP            | 8464                        | Desktop     | [2eae0556b2](https://linux-hardware.org/?probe=2eae0556b2) | Nov 16, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [7db396afcd](https://linux-hardware.org/?probe=7db396afcd) | Nov 16, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 PRO ARP23P     | Notebook    | [669eb1edcb](https://linux-hardware.org/?probe=669eb1edcb) | Nov 16, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [10e26870d7](https://linux-hardware.org/?probe=10e26870d7) | Nov 13, 2023 |
| Shenzhen M... | F7BSC                       | Mini pc     | [aff29d99aa](https://linux-hardware.org/?probe=aff29d99aa) | Nov 12, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [b15037e662](https://linux-hardware.org/?probe=b15037e662) | Nov 11, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [2c921ede59](https://linux-hardware.org/?probe=2c921ede59) | Nov 08, 2023 |
| ASRock        | B550M-HDV                   | Desktop     | [6f0980a8f2](https://linux-hardware.org/?probe=6f0980a8f2) | Nov 07, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [3333de3c07](https://linux-hardware.org/?probe=3333de3c07) | Nov 06, 2023 |
| ASRock        | B550M-HDV                   | Desktop     | [e005a7da3a](https://linux-hardware.org/?probe=e005a7da3a) | Nov 06, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [b40c43c829](https://linux-hardware.org/?probe=b40c43c829) | Nov 05, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [67a1ec0ae8](https://linux-hardware.org/?probe=67a1ec0ae8) | Nov 05, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [9f47c70860](https://linux-hardware.org/?probe=9f47c70860) | Nov 04, 2023 |
| Dell          | 01NP3N A00                  | Desktop     | [2332805279](https://linux-hardware.org/?probe=2332805279) | Nov 04, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [e073d8c90a](https://linux-hardware.org/?probe=e073d8c90a) | Nov 03, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [877ab8782b](https://linux-hardware.org/?probe=877ab8782b) | Nov 01, 2023 |
| Dell          | G15 5510                    | Notebook    | [12bd3f99da](https://linux-hardware.org/?probe=12bd3f99da) | Oct 31, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [d7fb2de5a7](https://linux-hardware.org/?probe=d7fb2de5a7) | Oct 30, 2023 |
| ASUSTek       | H110M-A                     | Desktop     | [a58f65d857](https://linux-hardware.org/?probe=a58f65d857) | Oct 27, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [480f22e1b7](https://linux-hardware.org/?probe=480f22e1b7) | Oct 24, 2023 |
| Dell          | Precision 7520              | Notebook    | [ab5ec5ba37](https://linux-hardware.org/?probe=ab5ec5ba37) | Oct 22, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [6d454c05e2](https://linux-hardware.org/?probe=6d454c05e2) | Oct 21, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [6cc2145e11](https://linux-hardware.org/?probe=6cc2145e11) | Oct 21, 2023 |
| GMKtec        | NucBox K4                   | Desktop     | [b0f8dc54f3](https://linux-hardware.org/?probe=b0f8dc54f3) | Oct 20, 2023 |
| AZW           | SER V1                      | Desktop     | [eca53f2271](https://linux-hardware.org/?probe=eca53f2271) | Oct 18, 2023 |
| Acer          | Aspire VX5-591G             | Notebook    | [586d280ca5](https://linux-hardware.org/?probe=586d280ca5) | Oct 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [11820fb443](https://linux-hardware.org/?probe=11820fb443) | Oct 10, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [257a13e71a](https://linux-hardware.org/?probe=257a13e71a) | Oct 02, 2023 |
| Gigabyte      | A520I AC                    | Desktop     | [48f4eb15cc](https://linux-hardware.org/?probe=48f4eb15cc) | Oct 02, 2023 |
| ASRock        | A320M-HDV                   | Desktop     | [2beb623746](https://linux-hardware.org/?probe=2beb623746) | Sep 26, 2023 |
| Alienware     | 17 R2                       | Notebook    | [6ad5704e29](https://linux-hardware.org/?probe=6ad5704e29) | Sep 21, 2023 |
| Alienware     | 17 R2                       | Notebook    | [76bf895d62](https://linux-hardware.org/?probe=76bf895d62) | Sep 21, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Notebook    | [4298a1ab82](https://linux-hardware.org/?probe=4298a1ab82) | Sep 16, 2023 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | Desktop     | [27d1633bc3](https://linux-hardware.org/?probe=27d1633bc3) | Sep 11, 2023 |
| HP            | 18E7                        | Desktop     | [1b966d0110](https://linux-hardware.org/?probe=1b966d0110) | Sep 11, 2023 |
| HP            | 89B5 A                      | Desktop     | [4934bfa1a8](https://linux-hardware.org/?probe=4934bfa1a8) | Sep 09, 2023 |
| Gigabyte      | Z97X-Gaming 5               | Notebook    | [a3cdc2345d](https://linux-hardware.org/?probe=a3cdc2345d) | Sep 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [584a31e54e](https://linux-hardware.org/?probe=584a31e54e) | Sep 07, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [6192c839f5](https://linux-hardware.org/?probe=6192c839f5) | Sep 06, 2023 |
| ASUSTek       | Zephyrus S GX502GV_GX502... | Notebook    | [3429c55014](https://linux-hardware.org/?probe=3429c55014) | Sep 06, 2023 |
| ASUSTek       | Zephyrus S GX502GV_GX502... | Notebook    | [72fb0f052e](https://linux-hardware.org/?probe=72fb0f052e) | Sep 06, 2023 |
| ASUSTek       | GD30CI                      | Desktop     | [f1c877be0e](https://linux-hardware.org/?probe=f1c877be0e) | Sep 05, 2023 |
| Dell          | Latitude 3590               | Notebook    | [9406fe5cf7](https://linux-hardware.org/?probe=9406fe5cf7) | Sep 02, 2023 |
| Gigabyte      | Z490 GAMING X AX y.y        | Desktop     | [94a6d62c4b](https://linux-hardware.org/?probe=94a6d62c4b) | Aug 28, 2023 |
| Dell          | 04Y8V0 A02                  | Desktop     | [5afb05e780](https://linux-hardware.org/?probe=5afb05e780) | Aug 27, 2023 |
| ASUSTek       | PN51-E1                     | Mini pc     | [64b9dbafae](https://linux-hardware.org/?probe=64b9dbafae) | Aug 16, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [ad8a62ee1d](https://linux-hardware.org/?probe=ad8a62ee1d) | Aug 14, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [64aa93e41b](https://linux-hardware.org/?probe=64aa93e41b) | Aug 14, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [3ac1be3b93](https://linux-hardware.org/?probe=3ac1be3b93) | Aug 13, 2023 |
| Anbernic      | Win600                      | Notebook    | [32213b8d3b](https://linux-hardware.org/?probe=32213b8d3b) | Aug 13, 2023 |
| Dell          | 05YDCW A01                  | Desktop     | [3f3195be63](https://linux-hardware.org/?probe=3f3195be63) | Aug 12, 2023 |
| Dell          | 05YDCW A01                  | Desktop     | [80c27f0ac1](https://linux-hardware.org/?probe=80c27f0ac1) | Aug 12, 2023 |
| GPD           | P2 MAX                      | Notebook    | [064bc78973](https://linux-hardware.org/?probe=064bc78973) | Aug 09, 2023 |
| HP            | Victus by Laptop 16-d1xx... | Notebook    | [74c80ca51b](https://linux-hardware.org/?probe=74c80ca51b) | Aug 06, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [b1b6854522](https://linux-hardware.org/?probe=b1b6854522) | Jul 29, 2023 |
| AZW           | SER V01                     | Mini pc     | [a3b4c40b6e](https://linux-hardware.org/?probe=a3b4c40b6e) | Jul 28, 2023 |
| ASRock        | H97M Anniversary            | Desktop     | [f8a02ab68e](https://linux-hardware.org/?probe=f8a02ab68e) | Jul 27, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [d3e22fde36](https://linux-hardware.org/?probe=d3e22fde36) | Jul 25, 2023 |
| Lenovo        | ThinkPad E15 20RD0011IX     | Notebook    | [c7a1caa230](https://linux-hardware.org/?probe=c7a1caa230) | Jul 25, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [c8a41127a9](https://linux-hardware.org/?probe=c8a41127a9) | Jul 23, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [9186fec300](https://linux-hardware.org/?probe=9186fec300) | Jul 23, 2023 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [80e44d8594](https://linux-hardware.org/?probe=80e44d8594) | Jul 22, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [f747d5537e](https://linux-hardware.org/?probe=f747d5537e) | Jul 15, 2023 |
| Acer          | Veriton X6610G              | Desktop     | [e1189e3406](https://linux-hardware.org/?probe=e1189e3406) | Jul 13, 2023 |
| Acer          | Aspire A715-42G             | Notebook    | [ac10700edb](https://linux-hardware.org/?probe=ac10700edb) | Jul 13, 2023 |
| Dell          | 0KC9NP A01                  | Desktop     | [570f59305c](https://linux-hardware.org/?probe=570f59305c) | Jul 08, 2023 |
| Dell          | 0KC9NP A01                  | Desktop     | [6d62d0cdbf](https://linux-hardware.org/?probe=6d62d0cdbf) | Jul 08, 2023 |
| HP            | 1791                        | Desktop     | [a2bf914a45](https://linux-hardware.org/?probe=a2bf914a45) | Jul 08, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [13195d7ff3](https://linux-hardware.org/?probe=13195d7ff3) | Jul 02, 2023 |
| HP            | 1998                        | Desktop     | [91f6e54877](https://linux-hardware.org/?probe=91f6e54877) | Jun 30, 2023 |
| AMI           | Unknown                     | Notebook    | [88da6b0232](https://linux-hardware.org/?probe=88da6b0232) | Jun 25, 2023 |
| Acer          | Aspire A315-58G             | Notebook    | [ea2b8a58b1](https://linux-hardware.org/?probe=ea2b8a58b1) | Jun 22, 2023 |
| Gigabyte      | G1.Sniper A88X-CF           | Desktop     | [d4470db5d3](https://linux-hardware.org/?probe=d4470db5d3) | Jun 20, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [50efda9604](https://linux-hardware.org/?probe=50efda9604) | Jun 19, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [299db094f8](https://linux-hardware.org/?probe=299db094f8) | Jun 18, 2023 |
| Dell          | 07HXY6 A01                  | Desktop     | [ec3adcbe42](https://linux-hardware.org/?probe=ec3adcbe42) | Jun 16, 2023 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [4932ae40b6](https://linux-hardware.org/?probe=4932ae40b6) | Jun 13, 2023 |
| Acidanther... | Mac-7BA5B2D9E42DDD94 iMa... | All in one  | [c6401638dd](https://linux-hardware.org/?probe=c6401638dd) | Jun 11, 2023 |
| Google        | Snappy                      | Notebook    | [737988d62e](https://linux-hardware.org/?probe=737988d62e) | Jun 11, 2023 |
| Google        | Snappy                      | Notebook    | [f228dabe46](https://linux-hardware.org/?probe=f228dabe46) | Jun 11, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [798d8e8914](https://linux-hardware.org/?probe=798d8e8914) | Jun 11, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [5e060b53c2](https://linux-hardware.org/?probe=5e060b53c2) | Jun 10, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [0d548e314b](https://linux-hardware.org/?probe=0d548e314b) | Jun 10, 2023 |
| Dell          | Inspiron 14 7420 2-in-1     | Convertible | [d7b5162532](https://linux-hardware.org/?probe=d7b5162532) | Jun 09, 2023 |
| MSI           | MPG B650I EDGE WIFI         | Desktop     | [d43ce99616](https://linux-hardware.org/?probe=d43ce99616) | Jun 07, 2023 |
| Acidanther... | Mac-7BA5B2D9E42DDD94 iMa... | All in one  | [8c6370ac0d](https://linux-hardware.org/?probe=8c6370ac0d) | May 23, 2023 |
| Acer          | Nitro AN515-51              | Notebook    | [4bbf7dc69e](https://linux-hardware.org/?probe=4bbf7dc69e) | May 21, 2023 |
| Microsoft     | Surface Book                | Tablet      | [7bb9611a98](https://linux-hardware.org/?probe=7bb9611a98) | May 21, 2023 |
| Micro Elec... | MG-VCP17I-3070              | Notebook    | [8ba5bb4bc7](https://linux-hardware.org/?probe=8ba5bb4bc7) | May 19, 2023 |
| Acer          | Aspire Z3-705               | All in one  | [95fcf79dd4](https://linux-hardware.org/?probe=95fcf79dd4) | May 18, 2023 |
| Acidanther... | Mac-7BA5B2D9E42DDD94 iMa... | All in one  | [41b69ae4db](https://linux-hardware.org/?probe=41b69ae4db) | May 12, 2023 |
| ASUSTek       | PRIME B760-PLUS D4          | Desktop     | [bb01d9e92b](https://linux-hardware.org/?probe=bb01d9e92b) | May 12, 2023 |
| ASUSTek       | ROG STRIX B460-I GAMING     | Desktop     | [3a9528f661](https://linux-hardware.org/?probe=3a9528f661) | May 10, 2023 |
| Acidanther... | Mac-7BA5B2D9E42DDD94 iMa... | All in one  | [bf3fee03d2](https://linux-hardware.org/?probe=bf3fee03d2) | May 09, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | Notebook    | [79bdb284fe](https://linux-hardware.org/?probe=79bdb284fe) | May 09, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [ad66608cf0](https://linux-hardware.org/?probe=ad66608cf0) | May 08, 2023 |
| Acidanther... | Mac-7BA5B2D9E42DDD94 iMa... | All in one  | [101ec0a833](https://linux-hardware.org/?probe=101ec0a833) | May 05, 2023 |
| AYANEO        | 2                           | Tablet      | [672b480b96](https://linux-hardware.org/?probe=672b480b96) | May 05, 2023 |
| ASUSTek       | PRIME B760-PLUS D4          | Desktop     | [4ec161ab9b](https://linux-hardware.org/?probe=4ec161ab9b) | May 04, 2023 |
| MSI           | CX62 6QD                    | Notebook    | [9c6b781beb](https://linux-hardware.org/?probe=9c6b781beb) | May 02, 2023 |
| AYANEO        | 2                           | Tablet      | [4db5d91519](https://linux-hardware.org/?probe=4db5d91519) | Apr 21, 2023 |
| Dell          | 0FDY5C A00                  | Desktop     | [a6865b8591](https://linux-hardware.org/?probe=a6865b8591) | Apr 16, 2023 |
| HP            | 250 G4 Notebook PC          | Notebook    | [08036de728](https://linux-hardware.org/?probe=08036de728) | Apr 15, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [a34f2e065b](https://linux-hardware.org/?probe=a34f2e065b) | Apr 14, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | Notebook    | [cacab44211](https://linux-hardware.org/?probe=cacab44211) | Apr 13, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | Notebook    | [2a4894bdc0](https://linux-hardware.org/?probe=2a4894bdc0) | Apr 13, 2023 |
| MSI           | MS-7C91                     | Notebook    | [663c6729cb](https://linux-hardware.org/?probe=663c6729cb) | Apr 12, 2023 |
| ASUSTek       | ROG STRIX B460-I GAMING     | Desktop     | [14db4e6f1d](https://linux-hardware.org/?probe=14db4e6f1d) | Apr 11, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [03db223af4](https://linux-hardware.org/?probe=03db223af4) | Apr 06, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [f8c2ffcd09](https://linux-hardware.org/?probe=f8c2ffcd09) | Apr 06, 2023 |
| Razer         | Blade Pro 17 (Early 2020... | Notebook    | [36d75e1d7f](https://linux-hardware.org/?probe=36d75e1d7f) | Mar 26, 2023 |
| Razer         | Blade Pro 17 (Early 2020... | Notebook    | [244b228a30](https://linux-hardware.org/?probe=244b228a30) | Mar 26, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [8a92687be7](https://linux-hardware.org/?probe=8a92687be7) | Mar 26, 2023 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [f383688a79](https://linux-hardware.org/?probe=f383688a79) | Mar 23, 2023 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [ad4c43dd09](https://linux-hardware.org/?probe=ad4c43dd09) | Mar 21, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [de9712600d](https://linux-hardware.org/?probe=de9712600d) | Mar 20, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [1ee17b12bd](https://linux-hardware.org/?probe=1ee17b12bd) | Mar 19, 2023 |
| Gigabyte      | B460M DS3H AC V2-Y1         | Desktop     | [b21cd49226](https://linux-hardware.org/?probe=b21cd49226) | Mar 16, 2023 |
| MSI           | MPG B650I EDGE WIFI         | Desktop     | [9f40b861a5](https://linux-hardware.org/?probe=9f40b861a5) | Mar 12, 2023 |
| Gigabyte      | B460M DS3H AC V2-Y1         | Desktop     | [7f8fc2ba96](https://linux-hardware.org/?probe=7f8fc2ba96) | Mar 10, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [b8ea458df5](https://linux-hardware.org/?probe=b8ea458df5) | Mar 08, 2023 |
| Dell          | 0XHGV1 A00                  | Desktop     | [8fa504e81f](https://linux-hardware.org/?probe=8fa504e81f) | Mar 07, 2023 |
| Intel         | DB75EN AAG39650-400         | Desktop     | [4a0feca3f5](https://linux-hardware.org/?probe=4a0feca3f5) | Mar 02, 2023 |
| Acer          | Aspire A515-51G             | Notebook    | [432235c684](https://linux-hardware.org/?probe=432235c684) | Feb 25, 2023 |
| Gigabyte      | H77M-D3H                    | Desktop     | [01eb743492](https://linux-hardware.org/?probe=01eb743492) | Feb 25, 2023 |
| Gigabyte      | H77M-D3H                    | Desktop     | [766790f373](https://linux-hardware.org/?probe=766790f373) | Feb 25, 2023 |
| ASUSTek       | B150I PRO GAMING/WIFI/AU... | Desktop     | [eb1e211b0f](https://linux-hardware.org/?probe=eb1e211b0f) | Feb 25, 2023 |
| MSI           | GE75 Raider 10SF            | Notebook    | [cc21335206](https://linux-hardware.org/?probe=cc21335206) | Feb 24, 2023 |
| HP            | 1998                        | Desktop     | [dbb952f3f6](https://linux-hardware.org/?probe=dbb952f3f6) | Feb 13, 2023 |
| HP            | 1998                        | Desktop     | [0171575a1d](https://linux-hardware.org/?probe=0171575a1d) | Feb 13, 2023 |
| ASUSTek       | K45VM                       | Notebook    | [06af577a0c](https://linux-hardware.org/?probe=06af577a0c) | Feb 04, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [69d2cb7e14](https://linux-hardware.org/?probe=69d2cb7e14) | Jan 11, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [f5ff2f8568](https://linux-hardware.org/?probe=f5ff2f8568) | Jan 06, 2023 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [3e4b14919e](https://linux-hardware.org/?probe=3e4b14919e) | Jan 05, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [02b3cbc8c6](https://linux-hardware.org/?probe=02b3cbc8c6) | Jan 04, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [13ae6c7e25](https://linux-hardware.org/?probe=13ae6c7e25) | Jan 01, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [49ca01435b](https://linux-hardware.org/?probe=49ca01435b) | Dec 27, 2022 |
| ONE-NETBOO... | ONE XPLAYER                 | Tablet      | [d721c7ae17](https://linux-hardware.org/?probe=d721c7ae17) | Dec 27, 2022 |
| Lenovo        | ThinkCentre M70e 0832B1U    | Desktop     | [d95663a632](https://linux-hardware.org/?probe=d95663a632) | Dec 07, 2022 |
| Acidanther... | Mac-7BA5B2D9E42DDD94 iMa... | All in one  | [2a7b6d570f](https://linux-hardware.org/?probe=2a7b6d570f) | Nov 26, 2022 |
| Acidanther... | Mac-7BA5B2D9E42DDD94 iMa... | All in one  | [58b3db6784](https://linux-hardware.org/?probe=58b3db6784) | Nov 23, 2022 |
| ONE-NETBOO... | ONE XPLAYER                 | Tablet      | [9bec9e1625](https://linux-hardware.org/?probe=9bec9e1625) | Oct 01, 2022 |
| ONE-NETBOO... | ONE XPLAYER                 | Tablet      | [501a588f11](https://linux-hardware.org/?probe=501a588f11) | Oct 01, 2022 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| ChimeraOS 44-1 | 62        | 31.63%  |
| ChimeraOS 45   | 25        | 12.76%  |
| ChimeraOS 43-1 | 25        | 12.76%  |
| ChimeraOS 42   | 18        | 9.18%   |
| ChimeraOS 39   | 15        | 7.65%   |
| ChimeraOS 45-1 | 14        | 7.14%   |
| ChimeraOS 41   | 11        | 5.61%   |
| ChimeraOS 43   | 8         | 4.08%   |
| ChimeraOS 38   | 6         | 3.06%   |
| ChimeraOS 44   | 5         | 2.55%   |
| ChimeraOS 37   | 4         | 2.04%   |
| ChimeraOS 46   | 1         | 0.51%   |
| ChimeraOS 35   | 1         | 0.51%   |
| ChimeraOS      | 1         | 0.51%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| ChimeraOS | 192       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Computers | Percent |
|-----------------------------|-----------|---------|
| 6.5.6-chos1-chimeraos-1     | 61        | 30.81%  |
| 6.6.10-chos1-chimeraos-2    | 37        | 18.69%  |
| 6.3.9-chimeraos-1           | 32        | 16.16%  |
| 6.1.27-1-lts                | 18        | 9.09%   |
| 6.1.11-arch1-1              | 15        | 7.58%   |
| 6.1.21-1-lts                | 11        | 5.56%   |
| 6.1.1-arch1-1               | 6         | 3.03%   |
| 6.5.3-chos1-chimeraos-1     | 5         | 2.53%   |
| 6.0.8-arch1-1               | 4         | 2.02%   |
| 6.8.2-0-generic             | 1         | 0.51%   |
| 6.8.0-rc2-chos1-chimeraos-1 | 1         | 0.51%   |
| 6.6.7-chos4-chimeraos-1     | 1         | 0.51%   |
| 6.6.6-arch1-1               | 1         | 0.51%   |
| 6.6.1-chos3-chimeraos-1     | 1         | 0.51%   |
| 6.4.9-0-generic             | 1         | 0.51%   |
| 6.3.3-arch1-1               | 1         | 0.51%   |
| 6.3.1-arch2-1               | 1         | 0.51%   |
| 5.19.6-arch1-1              | 1         | 0.51%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.5.6   | 61        | 30.81%  |
| 6.6.10  | 37        | 18.69%  |
| 6.3.9   | 32        | 16.16%  |
| 6.1.27  | 18        | 9.09%   |
| 6.1.11  | 15        | 7.58%   |
| 6.1.21  | 11        | 5.56%   |
| 6.1.1   | 6         | 3.03%   |
| 6.5.3   | 5         | 2.53%   |
| 6.0.8   | 4         | 2.02%   |
| 6.8.2   | 1         | 0.51%   |
| 6.8.0   | 1         | 0.51%   |
| 6.6.7   | 1         | 0.51%   |
| 6.6.6   | 1         | 0.51%   |
| 6.6.1   | 1         | 0.51%   |
| 6.4.9   | 1         | 0.51%   |
| 6.3.3   | 1         | 0.51%   |
| 6.3.1   | 1         | 0.51%   |
| 5.19.6  | 1         | 0.51%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.5     | 66        | 33.67%  |
| 6.1     | 49        | 25%     |
| 6.6     | 40        | 20.41%  |
| 6.3     | 33        | 16.84%  |
| 6.0     | 4         | 2.04%   |
| 6.8     | 2         | 1.02%   |
| 6.4     | 1         | 0.51%   |
| 5.19    | 1         | 0.51%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 192       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GNOME   | 191       | 99.48%  |
| steamos | 1         | 0.52%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 186       | 96.88%  |
| X11     | 6         | 3.13%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 192       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 167       | 86.98%  |
| pt_BR | 5         | 2.6%    |
| es_ES | 5         | 2.6%    |
| de_DE | 4         | 2.08%   |
| fr_FR | 3         | 1.56%   |
| it_IT | 2         | 1.04%   |
| zh_CN | 1         | 0.52%   |
| ja_JP | 1         | 0.52%   |
| fr_CA | 1         | 0.52%   |
| es_AR | 1         | 0.52%   |
| en_GB | 1         | 0.52%   |
| C     | 1         | 0.52%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 192       | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Btrfs | 191       | 99.48%  |
| Ext4  | 1         | 0.52%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 192       | 100%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 192       | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 192       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| ASUSTek Computer                     | 42        | 21.88%  |
| Gigabyte Technology                  | 27        | 14.06%  |
| Dell                                 | 24        | 12.5%   |
| Hewlett-Packard                      | 15        | 7.81%   |
| Acer                                 | 11        | 5.73%   |
| MSI                                  | 10        | 5.21%   |
| Lenovo                               | 9         | 4.69%   |
| ASRock                               | 8         | 4.17%   |
| Shenzhen Meigao Electronic Equipment | 5         | 2.6%    |
| ONE-NETBOOK                          | 4         | 2.08%   |
| Intel                                | 4         | 2.08%   |
| AYANEO                               | 4         | 2.08%   |
| Razer                                | 2         | 1.04%   |
| ONE-NETBOOK TECHNOLOGY               | 2         | 1.04%   |
| HC Technology.                       | 2         | 1.04%   |
| GPD                                  | 2         | 1.04%   |
| AZW                                  | 2         | 1.04%   |
| Apple                                | 2         | 1.04%   |
| ZOTAC                                | 1         | 0.52%   |
| Valve                                | 1         | 0.52%   |
| Soyo                                 | 1         | 0.52%   |
| Sony                                 | 1         | 0.52%   |
| Notebook                             | 1         | 0.52%   |
| Microsoft                            | 1         | 0.52%   |
| Micro Electronics                    | 1         | 0.52%   |
| Micro Computer (HK) Tech Limited     | 1         | 0.52%   |
| MACHINIST                            | 1         | 0.52%   |
| Google                               | 1         | 0.52%   |
| GMKtec                               | 1         | 0.52%   |
| Gateway                              | 1         | 0.52%   |
| Fujitsu                              | 1         | 0.52%   |
| Anbernic                             | 1         | 0.52%   |
| AMI                                  | 1         | 0.52%   |
| Alienware                            | 1         | 0.52%   |
| Acidanthera                          | 1         | 0.52%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                               | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Shenzhen Meigao Electronic Equipment Venus series  | 4         | 2.08%   |
| Gigabyte B550I AORUS PRO AX                        | 4         | 2.08%   |
| Gigabyte A520I AC                                  | 4         | 2.08%   |
| Dell OptiPlex 3060                                 | 3         | 1.56%   |
| AYANEO 2                                           | 3         | 1.56%   |
| ASUS ROG Ally RC71L_RC71L                          | 3         | 1.56%   |
| ONE-NETBOOK TECHNOLOGY ONE XPLAYER                 | 2         | 1.04%   |
| ONE-NETBOOK ONEXPLAYER 2 ARP23                     | 2         | 1.04%   |
| HP Victus by 15L Gaming Desktop TG02-0xxx          | 2         | 1.04%   |
| HP EliteDesk 800 G1 SFF                            | 2         | 1.04%   |
| Dell OptiPlex 7020                                 | 2         | 1.04%   |
| Dell OptiPlex 5055 Ryzen APU                       | 2         | 1.04%   |
| Dell OptiPlex 3070                                 | 2         | 1.04%   |
| AZW SER                                            | 2         | 1.04%   |
| ASUS ROG STRIX B550-F GAMING                       | 2         | 1.04%   |
| Acer Aspire V3-772G                                | 2         | 1.04%   |
| Unknown                                            | 2         | 1.04%   |
| ZOTAC ZBOX-ECM73070C/53060C                        | 1         | 0.52%   |
| Valve Galileo                                      | 1         | 0.52%   |
| Soyo SY-Classic B450M                              | 1         | 0.52%   |
| Sony SVS13A25PLB                                   | 1         | 0.52%   |
| Shenzhen Meigao Electronic Equipment Uranus Series | 1         | 0.52%   |
| Razer Blade Pro 17 (Early 2020) - RZ09-0329        | 1         | 0.52%   |
| Razer Blade 14 - RZ09-0370                         | 1         | 0.52%   |
| ONE-NETBOOK ONEXPLAYER F1                          | 1         | 0.52%   |
| ONE-NETBOOK ONEXPLAYER 2 PRO ARP23P                | 1         | 0.52%   |
| Notebook P15SM-A/SM1-A                             | 1         | 0.52%   |
| MSI MS-7D78                                        | 1         | 0.52%   |
| MSI MS-7D73                                        | 1         | 0.52%   |
| MSI MS-7C91                                        | 1         | 0.52%   |
| MSI MS-7C56                                        | 1         | 0.52%   |
| MSI MS-7C02                                        | 1         | 0.52%   |
| MSI MS-7B86                                        | 1         | 0.52%   |
| MSI MS-7A38                                        | 1         | 0.52%   |
| MSI MS-7850                                        | 1         | 0.52%   |
| MSI GE75 Raider 10SF                               | 1         | 0.52%   |
| MSI CX62 6QD                                       | 1         | 0.52%   |
| Microsoft Surface Book                             | 1         | 0.52%   |
| Micro MG-VCP17I-3070                               | 1         | 0.52%   |
| Micro (HK) Tech Limited HX100G                     | 1         | 0.52%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Dell OptiPlex                               | 14        | 7.29%   |
| ASUS ROG                                    | 12        | 6.25%   |
| Acer Aspire                                 | 8         | 4.17%   |
| ASUS TUF                                    | 6         | 3.13%   |
| ASUS PRIME                                  | 6         | 3.13%   |
| Shenzhen Meigao Electronic Equipment Venus  | 4         | 2.08%   |
| ONE-NETBOOK ONEXPLAYER                      | 4         | 2.08%   |
| Lenovo IdeaPad                              | 4         | 2.08%   |
| Gigabyte B550I                              | 4         | 2.08%   |
| Gigabyte A520I                              | 4         | 2.08%   |
| HP Victus                                   | 3         | 1.56%   |
| HP EliteDesk                                | 3         | 1.56%   |
| Dell Precision                              | 3         | 1.56%   |
| Dell Latitude                               | 3         | 1.56%   |
| Dell Inspiron                               | 3         | 1.56%   |
| AYANEO 2                                    | 3         | 1.56%   |
| Razer Blade                                 | 2         | 1.04%   |
| ONE-NETBOOK TECHNOLOGY ONE                  | 2         | 1.04%   |
| Lenovo ThinkCentre                          | 2         | 1.04%   |
| HP Pavilion                                 | 2         | 1.04%   |
| Gigabyte X570                               | 2         | 1.04%   |
| Gigabyte B450                               | 2         | 1.04%   |
| AZW SER                                     | 2         | 1.04%   |
| ASUS ASUS                                   | 2         | 1.04%   |
| Acer Nitro                                  | 2         | 1.04%   |
| Unknown                                     | 2         | 1.04%   |
| ZOTAC ZBOX-ECM73070C                        | 1         | 0.52%   |
| Valve Galileo                               | 1         | 0.52%   |
| Soyo SY-Classic                             | 1         | 0.52%   |
| Sony SVS13A25PLB                            | 1         | 0.52%   |
| Shenzhen Meigao Electronic Equipment Uranus | 1         | 0.52%   |
| Notebook P15SM-A                            | 1         | 0.52%   |
| MSI MS-7D78                                 | 1         | 0.52%   |
| MSI MS-7D73                                 | 1         | 0.52%   |
| MSI MS-7C91                                 | 1         | 0.52%   |
| MSI MS-7C56                                 | 1         | 0.52%   |
| MSI MS-7C02                                 | 1         | 0.52%   |
| MSI MS-7B86                                 | 1         | 0.52%   |
| MSI MS-7A38                                 | 1         | 0.52%   |
| MSI MS-7850                                 | 1         | 0.52%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 26        | 13.54%  |
| 2021 | 25        | 13.02%  |
| 2023 | 24        | 12.5%   |
| 2022 | 19        | 9.9%    |
| 2019 | 15        | 7.81%   |
| 2013 | 13        | 6.77%   |
| 2017 | 12        | 6.25%   |
| 2012 | 12        | 6.25%   |
| 2018 | 11        | 5.73%   |
| 2015 | 11        | 5.73%   |
| 2016 | 7         | 3.65%   |
| 2011 | 7         | 3.65%   |
| 2014 | 6         | 3.13%   |
| 2024 | 2         | 1.04%   |
| 2010 | 2         | 1.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 104       | 54.17%  |
| Notebook    | 62        | 32.29%  |
| Tablet      | 11        | 5.73%   |
| Mini pc     | 9         | 4.69%   |
| All in one  | 5         | 2.6%    |
| Convertible | 1         | 0.52%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 192       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 191       | 99.48%  |
| Yes  | 1         | 0.52%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 50        | 25.91%  |
| 32.01-64.0  | 43        | 22.28%  |
| 8.01-16.0   | 39        | 20.21%  |
| 4.01-8.0    | 26        | 13.47%  |
| 24.01-32.0  | 22        | 11.4%   |
| 3.01-4.0    | 7         | 3.63%   |
| 64.01-256.0 | 6         | 3.11%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 79        | 40.31%  |
| 1.01-2.0   | 47        | 23.98%  |
| 3.01-4.0   | 37        | 18.88%  |
| 4.01-8.0   | 31        | 15.82%  |
| 16.01-24.0 | 1         | 0.51%   |
| 8.01-16.0  | 1         | 0.51%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 102       | 52.04%  |
| 2      | 58        | 29.59%  |
| 3      | 22        | 11.22%  |
| 4      | 6         | 3.06%   |
| 5      | 3         | 1.53%   |
| 6      | 2         | 1.02%   |
| 11     | 1         | 0.51%   |
| 8      | 1         | 0.51%   |
| 7      | 1         | 0.51%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 157       | 81.77%  |
| Yes       | 35        | 18.23%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 172       | 89.58%  |
| No        | 20        | 10.42%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 154       | 80.21%  |
| No        | 38        | 19.79%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 140       | 72.92%  |
| No        | 52        | 27.08%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 83        | 43.23%  |
| Germany      | 12        | 6.25%   |
| Brazil       | 11        | 5.73%   |
| UK           | 10        | 5.21%   |
| France       | 6         | 3.13%   |
| Canada       | 6         | 3.13%   |
| Spain        | 5         | 2.6%    |
| Russia       | 5         | 2.6%    |
| Vietnam      | 4         | 2.08%   |
| Poland       | 4         | 2.08%   |
| Australia    | 4         | 2.08%   |
| Saudi Arabia | 3         | 1.56%   |
| Netherlands  | 3         | 1.56%   |
| Italy        | 3         | 1.56%   |
| Turkey       | 2         | 1.04%   |
| Switzerland  | 2         | 1.04%   |
| Norway       | 2         | 1.04%   |
| Japan        | 2         | 1.04%   |
| Hungary      | 2         | 1.04%   |
| Estonia      | 2         | 1.04%   |
| Argentina    | 2         | 1.04%   |
| South Africa | 1         | 0.52%   |
| Romania      | 1         | 0.52%   |
| Peru         | 1         | 0.52%   |
| New Zealand  | 1         | 0.52%   |
| Mexico       | 1         | 0.52%   |
| Malaysia     | 1         | 0.52%   |
| Macao        | 1         | 0.52%   |
| Indonesia    | 1         | 0.52%   |
| Iceland      | 1         | 0.52%   |
| Honduras     | 1         | 0.52%   |
| Finland      | 1         | 0.52%   |
| Czechia      | 1         | 0.52%   |
| Costa Rica   | 1         | 0.52%   |
| Colombia     | 1         | 0.52%   |
| China        | 1         | 0.52%   |
| Chile        | 1         | 0.52%   |
| Belgium      | 1         | 0.52%   |
| Austria      | 1         | 0.52%   |
| Algeria      | 1         | 0.52%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Springfield    | 2         | 1.04%   |
| Seattle        | 2         | 1.04%   |
| Sanford        | 2         | 1.04%   |
| San Jose       | 2         | 1.04%   |
| Salvador       | 2         | 1.04%   |
| Portland       | 2         | 1.04%   |
| Philadelphia   | 2         | 1.04%   |
| Melbourne      | 2         | 1.04%   |
| London         | 2         | 1.04%   |
| Las Vegas      | 2         | 1.04%   |
| Istanbul       | 2         | 1.04%   |
| Gelsenkirchen  | 2         | 1.04%   |
| Fortaleza      | 2         | 1.04%   |
| Dammam         | 2         | 1.04%   |
| Cincinnati     | 2         | 1.04%   |
| Chattanooga    | 2         | 1.04%   |
| Bellevue       | 2         | 1.04%   |
| Yekaterinburg  | 1         | 0.52%   |
| Yaroslavl      | 1         | 0.52%   |
| Wroclaw        | 1         | 0.52%   |
| Wilmington     | 1         | 0.52%   |
| Wiesbaden      | 1         | 0.52%   |
| Wiehl          | 1         | 0.52%   |
| Watsonville    | 1         | 0.52%   |
| Warsaw         | 1         | 0.52%   |
| Vũng Tàu     | 1         | 0.52%   |
| Virginia Beach | 1         | 0.52%   |
| Vincennes      | 1         | 0.52%   |
| Vila-seca      | 1         | 0.52%   |
| Vienna         | 1         | 0.52%   |
| Valence        | 1         | 0.52%   |
| Umeda          | 1         | 0.52%   |
| Tulcea         | 1         | 0.52%   |
| Tucson         | 1         | 0.52%   |
| Toronto        | 1         | 0.52%   |
| Theodore       | 1         | 0.52%   |
| The Hague      | 1         | 0.52%   |
| Tegucigalpa    | 1         | 0.52%   |
| Tampa          | 1         | 0.52%   |
| Tallinn        | 1         | 0.52%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 43        | 62     | 13.52%  |
| Seagate                      | 35        | 40     | 11.01%  |
| WDC                          | 32        | 42     | 10.06%  |
| SanDisk                      | 22        | 30     | 6.92%   |
| Kingston                     | 19        | 19     | 5.97%   |
| Unknown                      | 13        | 13     | 4.09%   |
| Micron/Crucial Technology    | 13        | 14     | 4.09%   |
| SK hynix                     | 11        | 11     | 3.46%   |
| Micron Technology            | 11        | 17     | 3.46%   |
| Toshiba                      | 10        | 13     | 3.14%   |
| Intel                        | 10        | 12     | 3.14%   |
| Crucial                      | 10        | 14     | 3.14%   |
| Phison Electronics           | 9         | 10     | 2.83%   |
| Realtek Semiconductor        | 8         | 8      | 2.52%   |
| KIOXIA                       | 6         | 6      | 1.89%   |
| Kingston Technology Company  | 6         | 6      | 1.89%   |
| China                        | 5         | 5      | 1.57%   |
| ADATA Technology             | 5         | 7      | 1.57%   |
| Hitachi                      | 4         | 4      | 1.26%   |
| Silicon Motion               | 3         | 3      | 0.94%   |
| Shenzhen Longsys Electronics | 3         | 3      | 0.94%   |
| PNY                          | 3         | 3      | 0.94%   |
| MAXIO Technology (Hangzhou)  | 3         | 3      | 0.94%   |
| HGST                         | 3         | 3      | 0.94%   |
| A-DATA Technology            | 3         | 3      | 0.94%   |
| Team                         | 2         | 2      | 0.63%   |
| Fanxiang                     | 2         | 2      | 0.63%   |
| Unknown                      | 2         | 2      | 0.63%   |
| WDC PC S                     | 1         | 1      | 0.31%   |
| TO Exter                     | 1         | 1      | 0.31%   |
| SSSTC                        | 1         | 1      | 0.31%   |
| SPCC                         | 1         | 1      | 0.31%   |
| SABRENT                      | 1         | 1      | 0.31%   |
| Realtek                      | 1         | 1      | 0.31%   |
| O2 Micro                     | 1         | 1      | 0.31%   |
| NT-1TB                       | 1         | 1      | 0.31%   |
| Netac                        | 1         | 1      | 0.31%   |
| Lenovo                       | 1         | 1      | 0.31%   |
| KingFast                     | 1         | 1      | 0.31%   |
| KingDian                     | 1         | 5      | 0.31%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB               | 12        | 3.55%   |
| Micron/Crucial P2 NVMe PCIe SSD 4TB                             | 11        | 3.25%   |
| Seagate ST1000DM010-2EP102 1TB                                  | 5         | 1.48%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB              | 5         | 1.48%   |
| Seagate ST1000LM035-1RK172 1TB                                  | 4         | 1.18%   |
| Unknown MMC Card  512GB                                         | 3         | 0.89%   |
| Seagate ST500DM002-1BD142 500GB                                 | 3         | 0.89%   |
| Sandisk WD_BLACK SN770 2TB                                      | 3         | 0.89%   |
| Samsung SSD 860 EVO 1TB                                         | 3         | 0.89%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1TB               | 3         | 0.89%   |
| Realtek RTS5763DL NVMe SSD Controller 256GB                     | 3         | 0.89%   |
| Phison PS5013 E13 NVMe Controller 512GB                         | 3         | 0.89%   |
| Phison E12 NVMe Controller 2TB                                  | 3         | 0.89%   |
| Kingston Company SNV2S1000G 1TB                                 | 3         | 0.89%   |
| Kingston SA400S37480G 480GB SSD                                 | 3         | 0.89%   |
| Kingston SA400S37120G 120GB SSD                                 | 3         | 0.89%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 1TB | 3         | 0.89%   |
| WDC WDBNCE5000PNC 500GB SSD                                     | 2         | 0.59%   |
| WDC WD20EZRZ-00Z5HB0 2TB                                        | 2         | 0.59%   |
| WDC WD1600AAJS-00B4A0 160GB                                     | 2         | 0.59%   |
| WDC WD10JPVX-22JC3T0 1TB                                        | 2         | 0.59%   |
| WDC WD10EZEX-00BN5A0 1TB                                        | 2         | 0.59%   |
| Unknown SD/MMC/MS PRO 128GB                                     | 2         | 0.59%   |
| Unknown NVMe SSD Drive 512GB                                    | 2         | 0.59%   |
| Unknown NVMe SSD Drive 2TB                                      | 2         | 0.59%   |
| Unknown MMC Card  64GB                                          | 2         | 0.59%   |
| Toshiba MQ04ABF100 1TB                                          | 2         | 0.59%   |
| SK hynix HFM512GD3JX016N 512GB                                  | 2         | 0.59%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB           | 2         | 0.59%   |
| Seagate ST1000LM048-2E7172 1TB                                  | 2         | 0.59%   |
| Sandisk WD_BLACK SN770 500GB                                    | 2         | 0.59%   |
| Sandisk WD Blue SN550 NVMe SSD 2TB                              | 2         | 0.59%   |
| Samsung SSD 980 1TB                                             | 2         | 0.59%   |
| Samsung SSD 870 QVO 2TB                                         | 2         | 0.59%   |
| Samsung SSD 870 EVO 1TB                                         | 2         | 0.59%   |
| Samsung SSD 850 EVO 250GB                                       | 2         | 0.59%   |
| Micron/Crucial CT1000P5PSSD8 1TB                                | 2         | 0.59%   |
| Micron 2400_MTFDKBK512QFM 512GB                                 | 2         | 0.59%   |
| Micron 1100 SATA 256GB SSD                                      | 2         | 0.59%   |
| KIOXIA KBG40ZNS256G NVMe 256GB                                  | 2         | 0.59%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 34        | 38     | 42.5%   |
| WDC                 | 26        | 30     | 32.5%   |
| Toshiba             | 7         | 10     | 8.75%   |
| Hitachi             | 4         | 4      | 5%      |
| HGST                | 3         | 3      | 3.75%   |
| Unknown             | 2         | 2      | 2.5%    |
| TO Exter            | 1         | 1      | 1.25%   |
| Samsung Electronics | 1         | 1      | 1.25%   |
| SABRENT             | 1         | 1      | 1.25%   |
| Apple               | 1         | 1      | 1.25%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 18        | 26     | 18.37%  |
| Kingston            | 13        | 13     | 13.27%  |
| Crucial             | 10        | 14     | 10.2%   |
| WDC                 | 9         | 12     | 9.18%   |
| SanDisk             | 9         | 14     | 9.18%   |
| Micron Technology   | 6         | 12     | 6.12%   |
| China               | 5         | 5      | 5.1%    |
| Intel               | 4         | 5      | 4.08%   |
| PNY                 | 3         | 3      | 3.06%   |
| A-DATA Technology   | 3         | 3      | 3.06%   |
| SK hynix            | 2         | 2      | 2.04%   |
| Fanxiang            | 2         | 2      | 2.04%   |
| Team                | 1         | 1      | 1.02%   |
| SSSTC               | 1         | 1      | 1.02%   |
| SPCC                | 1         | 1      | 1.02%   |
| Seagate             | 1         | 1      | 1.02%   |
| NT-1TB              | 1         | 1      | 1.02%   |
| Netac               | 1         | 1      | 1.02%   |
| KingDian            | 1         | 5      | 1.02%   |
| Intenso             | 1         | 1      | 1.02%   |
| Hewlett-Packard     | 1         | 1      | 1.02%   |
| GOODRAM             | 1         | 1      | 1.02%   |
| GALAX               | 1         | 1      | 1.02%   |
| Corsair             | 1         | 1      | 1.02%   |
| ASMedia             | 1         | 1      | 1.02%   |
| AMD                 | 1         | 1      | 1.02%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 122       | 151    | 43.57%  |
| SSD     | 80        | 129    | 28.57%  |
| HDD     | 66        | 91     | 23.57%  |
| MMC     | 7         | 7      | 2.5%    |
| Unknown | 5         | 5      | 1.79%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 122       | 150    | 47.47%  |
| SATA | 116       | 213    | 45.14%  |
| SAS  | 12        | 13     | 4.67%   |
| MMC  | 7         | 7      | 2.72%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 70        | 124    | 46.98%  |
| 0.51-1.0   | 53        | 64     | 35.57%  |
| 1.01-2.0   | 16        | 18     | 10.74%  |
| 3.01-4.0   | 4         | 8      | 2.68%   |
| 10.01-20.0 | 3         | 3      | 2.01%   |
| 4.01-10.0  | 2         | 2      | 1.34%   |
| 2.01-3.0   | 1         | 1      | 0.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| More than 3000 | 79        | 40.93%  |
| 1001-2000      | 56        | 29.02%  |
| 501-1000       | 28        | 14.51%  |
| 2001-3000      | 16        | 8.29%   |
| 251-500        | 11        | 5.7%    |
| 101-250        | 2         | 1.04%   |
| 51-100         | 1         | 0.52%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 57        | 29.08%  |
| 51-100         | 28        | 14.29%  |
| 501-1000       | 27        | 13.78%  |
| 101-250        | 24        | 12.24%  |
| 251-500        | 21        | 10.71%  |
| 1001-2000      | 18        | 9.18%   |
| More than 3000 | 10        | 5.1%    |
| 2001-3000      | 10        | 5.1%    |
| 1-20           | 1         | 0.51%   |

Malfunc. Drives
---------------

Drive models with a malfunction

Zero info for selected period =(

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

Zero info for selected period =(

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

Zero info for selected period =(

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
| Detected | 193       | 383    | 100%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 96        | 32.54%  |
| AMD                          | 62        | 21.02%  |
| Samsung Electronics          | 27        | 9.15%   |
| Sandisk                      | 14        | 4.75%   |
| Micron/Crucial Technology    | 13        | 4.41%   |
| Kingston Technology Company  | 12        | 4.07%   |
| SK hynix                     | 9         | 3.05%   |
| Phison Electronics           | 9         | 3.05%   |
| Realtek Semiconductor        | 8         | 2.71%   |
| KIOXIA                       | 6         | 2.03%   |
| Micron Technology            | 5         | 1.69%   |
| ADATA Technology             | 5         | 1.69%   |
| ASMedia Technology           | 4         | 1.36%   |
| Toshiba America Info Systems | 3         | 1.02%   |
| Silicon Motion               | 3         | 1.02%   |
| Shenzhen Longsys Electronics | 3         | 1.02%   |
| MAXIO Technology (Hangzhou)  | 3         | 1.02%   |
| Solidigm                     | 2         | 0.68%   |
| Marvell Technology Group     | 2         | 0.68%   |
| Biwin Storage Technology     | 2         | 0.68%   |
| VIA Technologies             | 1         | 0.34%   |
| TenaFe                       | 1         | 0.34%   |
| O2 Micro                     | 1         | 0.34%   |
| Lenovo                       | 1         | 0.34%   |
| INNOGRIT                     | 1         | 0.34%   |
| Hosin Global Electronics     | 1         | 0.34%   |
| Unknown                      | 1         | 0.34%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 29        | 8.95%   |
| AMD 500 Series Chipset SATA Controller                                         | 20        | 6.17%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 14        | 4.32%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 12        | 3.7%    |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 11        | 3.4%    |
| AMD 400 Series Chipset SATA Controller                                         | 11        | 3.4%    |
| Intel Volume Management Device NVMe RAID Controller                            | 9         | 2.78%   |
| Intel SATA Controller [RAID mode]                                              | 8         | 2.47%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 7         | 2.16%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 6         | 1.85%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 6         | 1.85%   |
| AMD 600 Series Chipset SATA Controller                                         | 6         | 1.85%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 5         | 1.54%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 5         | 1.54%   |
| Intel Comet Lake SATA AHCI Controller                                          | 5         | 1.54%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 5         | 1.54%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 4         | 1.23%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 4         | 1.23%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 4         | 1.23%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 4         | 1.23%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 3         | 0.93%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 0.93%   |
| Realtek RTS5762 NVMe SSD Controller                                            | 3         | 0.93%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 3         | 0.93%   |
| Phison E12 NVMe Controller                                                     | 3         | 0.93%   |
| Kingston Company NV2 NVMe SSD SM2267XT (DRAM-less)                             | 3         | 0.93%   |
| Kingston Company NV1 NVMe SSD SM2263XT (DRAM-less)                             | 3         | 0.93%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 3         | 0.93%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 3         | 0.93%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3         | 0.93%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 3         | 0.93%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 3         | 0.93%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 3         | 0.93%   |
| AMD 300 Series Chipset SATA Controller                                         | 3         | 0.93%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 3         | 0.93%   |
| Solidigm P41 Plus NVMe SSD (DRAM-less) [Echo Harbor]                           | 2         | 0.62%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 2         | 0.62%   |
| Shenzhen Longsys Lexar NM790 NVME SSD (DRAM-less)                              | 2         | 0.62%   |
| SanDisk WD Green SN350 240GB (DRAM-less) / SN560E NVMe SSD                     | 2         | 0.62%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 2         | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 132       | 46.15%  |
| NVMe | 122       | 42.66%  |
| RAID | 24        | 8.39%   |
| IDE  | 8         | 2.8%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 102       | 53.13%  |
| AMD    | 90        | 46.88%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| AMD Ryzen 7 5800X 8-Core Processor              | 6         | 3.11%   |
| AMD Ryzen 5 3600 6-Core Processor               | 6         | 3.11%   |
| AMD Ryzen 7 6800U with Radeon Graphics          | 5         | 2.59%   |
| AMD Ryzen 7 7840HS w/ Radeon 780M Graphics      | 4         | 2.07%   |
| AMD Ryzen 5 5600X 6-Core Processor              | 4         | 2.07%   |
| AMD Ryzen 5 5600G with Radeon Graphics          | 4         | 2.07%   |
| Intel Core i7-7700K CPU @ 4.20GHz               | 3         | 1.55%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz              | 3         | 1.55%   |
| AMD Ryzen Z1 Extreme                            | 3         | 1.55%   |
| AMD Ryzen 9 7940HS w/ Radeon 780M Graphics      | 3         | 1.55%   |
| AMD Ryzen 9 5950X 16-Core Processor             | 3         | 1.55%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 3         | 1.55%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 2         | 1.04%   |
| Intel Core i5-8500 CPU @ 3.00GHz                | 2         | 1.04%   |
| Intel Core i5-7500 CPU @ 3.40GHz                | 2         | 1.04%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz              | 2         | 1.04%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 2         | 1.04%   |
| Intel Core i5-4570 CPU @ 3.20GHz                | 2         | 1.04%   |
| Intel Core i5-4440 CPU @ 3.10GHz                | 2         | 1.04%   |
| Intel Core i5-2400 CPU @ 3.10GHz                | 2         | 1.04%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz         | 2         | 1.04%   |
| Intel 11th Gen Core i5-11400H @ 2.70GHz         | 2         | 1.04%   |
| AMD Ryzen 9 5900X 12-Core Processor             | 2         | 1.04%   |
| AMD Ryzen 7 7840U w/ Radeon 780M Graphics       | 2         | 1.04%   |
| AMD Ryzen 7 7800X3D 8-Core Processor            | 2         | 1.04%   |
| AMD Ryzen 7 7700X 8-Core Processor              | 2         | 1.04%   |
| AMD Ryzen 7 5800U with Radeon Graphics          | 2         | 1.04%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx   | 2         | 1.04%   |
| AMD Ryzen 5 PRO 2400G with Radeon Vega Graphics | 2         | 1.04%   |
| AMD Ryzen 5 5560U with Radeon Graphics          | 2         | 1.04%   |
| AMD Ryzen 5 5500U with Radeon Graphics          | 2         | 1.04%   |
| AMD Ryzen 5 5500                                | 2         | 1.04%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics     | 2         | 1.04%   |
| AMD Ryzen 5 2600X Six-Core Processor            | 2         | 1.04%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz             | 1         | 0.52%   |
| Intel Xeon CPU E3-1271 v3 @ 3.60GHz             | 1         | 0.52%   |
| Intel Xeon CPU E3-1245 V2 @ 3.40GHz             | 1         | 0.52%   |
| Intel Xeon CPU E3-1231 v3 @ 3.40GHz             | 1         | 0.52%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz             | 1         | 0.52%   |
| Intel Pentium CPU G2030 @ 3.00GHz               | 1         | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Core i5     | 40        | 20.73%  |
| AMD Ryzen 5       | 33        | 17.1%   |
| AMD Ryzen 7       | 32        | 16.58%  |
| Intel Core i7     | 26        | 13.47%  |
| Other             | 18        | 9.33%   |
| AMD Ryzen 9       | 13        | 6.74%   |
| Intel Core i3     | 10        | 5.18%   |
| Intel Xeon        | 5         | 2.59%   |
| AMD Ryzen 5 PRO   | 3         | 1.55%   |
| Intel Pentium     | 2         | 1.04%   |
| Intel Celeron     | 2         | 1.04%   |
| AMD FX            | 2         | 1.04%   |
| AMD Athlon        | 2         | 1.04%   |
| Intel Core m3     | 1         | 0.52%   |
| Intel Core 2 Quad | 1         | 0.52%   |
| Intel Atom        | 1         | 0.52%   |
| AMD PRO A10       | 1         | 0.52%   |
| AMD A10           | 1         | 0.52%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 69        | 35.75%  |
| 8      | 42        | 21.76%  |
| 6      | 42        | 21.76%  |
| 2      | 25        | 12.95%  |
| 16     | 5         | 2.59%   |
| 12     | 3         | 1.55%   |
| 10     | 3         | 1.55%   |
| 14     | 2         | 1.04%   |
| 24     | 1         | 0.52%   |
| 3      | 1         | 0.52%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 192       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 155       | 80.73%  |
| 1      | 37        | 19.27%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 192       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 192       | 100%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Unknown     | 41        | 21.35%  |
| Zen 3       | 29        | 15.1%   |
| KabyLake    | 24        | 12.5%   |
| Haswell     | 21        | 10.94%  |
| CometLake   | 12        | 6.25%   |
| Zen+        | 10        | 5.21%   |
| Zen 2       | 9         | 4.69%   |
| Skylake     | 9         | 4.69%   |
| SandyBridge | 9         | 4.69%   |
| IvyBridge   | 8         | 4.17%   |
| Zen         | 7         | 3.65%   |
| TigerLake   | 3         | 1.56%   |
| Piledriver  | 3         | 1.56%   |
| Silvermont  | 1         | 0.52%   |
| Penryn      | 1         | 0.52%   |
| Nehalem     | 1         | 0.52%   |
| Jaguar      | 1         | 0.52%   |
| Goldmont    | 1         | 0.52%   |
| Excavator   | 1         | 0.52%   |
| Broadwell   | 1         | 0.52%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| AMD    | 101       | 41.56%  |
| Nvidia | 76        | 31.28%  |
| Intel  | 66        | 27.16%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| AMD Phoenix1                                                                | 12        | 4.8%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 8         | 3.2%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 7         | 2.8%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 6         | 2.4%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 6         | 2.4%    |
| AMD Rembrandt [Radeon 680M]                                                 | 6         | 2.4%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 6         | 2.4%    |
| Intel HD Graphics 630                                                       | 5         | 2%      |
| Intel HD Graphics 530                                                       | 5         | 2%      |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5         | 2%      |
| AMD Raphael                                                                 | 5         | 2%      |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 5         | 2%      |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 5         | 2%      |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 4         | 1.6%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 4         | 1.6%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 4         | 1.6%    |
| AMD Polaris 20 XL [Radeon RX 580 2048SP]                                    | 4         | 1.6%    |
| AMD Navi 32 [Radeon RX 7700 XT / 7800 XT]                                   | 4         | 1.6%    |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX/7900M]                              | 4         | 1.6%    |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                                  | 4         | 1.6%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 4         | 1.6%    |
| Nvidia TU117 [GeForce GTX 1650]                                             | 3         | 1.2%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 3         | 1.2%    |
| Nvidia GM107M [GeForce GTX 950M]                                            | 3         | 1.2%    |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                          | 3         | 1.2%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 3         | 1.2%    |
| Intel Skylake GT2 [HD Graphics 520]                                         | 3         | 1.2%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3         | 1.2%    |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 3         | 1.2%    |
| AMD Lucienne                                                                | 3         | 1.2%    |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 3         | 1.2%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 2         | 0.8%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 2         | 0.8%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 2         | 0.8%    |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2         | 0.8%    |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2         | 0.8%    |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 2         | 0.8%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 2         | 0.8%    |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                             | 2         | 0.8%    |
| Nvidia GA104 [GeForce RTX 3070 Ti]                                          | 2         | 0.8%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x AMD        | 83        | 43.01%  |
| 1 x Nvidia     | 38        | 19.69%  |
| Intel + Nvidia | 30        | 15.54%  |
| 1 x Intel      | 23        | 11.92%  |
| 2 x AMD        | 6         | 3.11%   |
| Intel + AMD    | 6         | 3.11%   |
| AMD + Nvidia   | 6         | 3.11%   |
| Other          | 1         | 0.52%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 137       | 71.35%  |
| Proprietary | 36        | 18.75%  |
| Unknown     | 19        | 9.9%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 189       | 98.44%  |
| 3.01-4.0   | 2         | 1.04%   |
| 8.01-16.0  | 1         | 0.52%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 23        | 13.14%  |
| Chimei Innolux       | 13        | 7.43%   |
| BOE                  | 13        | 7.43%   |
| LG Display           | 11        | 6.29%   |
| Goldstar             | 10        | 5.71%   |
| AU Optronics         | 10        | 5.71%   |
| Dell                 | 8         | 4.57%   |
| Vizio                | 5         | 2.86%   |
| Unknown (XXX)        | 4         | 2.29%   |
| Toshiba              | 4         | 2.29%   |
| TMX                  | 4         | 2.29%   |
| Sharp                | 4         | 2.29%   |
| Hewlett-Packard      | 4         | 2.29%   |
| BenQ                 | 4         | 2.29%   |
| AOC                  | 4         | 2.29%   |
| Philips              | 3         | 1.71%   |
| Panasonic            | 3         | 1.71%   |
| MSI                  | 3         | 1.71%   |
| Insignia             | 3         | 1.71%   |
| ASUSTek Computer     | 3         | 1.71%   |
| Ancor Communications | 3         | 1.71%   |
| Acer                 | 3         | 1.71%   |
| Sony                 | 2         | 1.14%   |
| SANYO                | 2         | 1.14%   |
| PANDA                | 2         | 1.14%   |
| Lenovo               | 2         | 1.14%   |
| DENON                | 2         | 1.14%   |
| AYANEO               | 2         | 1.14%   |
| ViewSonic            | 1         | 0.57%   |
| VIE                  | 1         | 0.57%   |
| Valve                | 1         | 0.57%   |
| Sceptre Tech         | 1         | 0.57%   |
| RTK                  | 1         | 0.57%   |
| PXO                  | 1         | 0.57%   |
| PEP                  | 1         | 0.57%   |
| Onkyo                | 1         | 0.57%   |
| MSF                  | 1         | 0.57%   |
| ITE                  | 1         | 0.57%   |
| HJW                  | 1         | 0.57%   |
| Hitachi              | 1         | 0.57%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1209x680mm 54.6-inch         | 3         | 1.7%    |
| TMX TL070FVXS01-0 TMX0002 1920x1080 160x100mm 7.4-inch                 | 3         | 1.7%    |
| BOE TV080WUM-NL0 BOE1003 1600x2560 113x181mm 8.4-inch                  | 3         | 1.7%    |
| Toshiba TV TSB2017 3840x2160                                           | 2         | 1.14%   |
| Samsung Electronics LCD Monitor SAM0DF6 3840x2160 1210x680mm 54.6-inch | 2         | 1.14%   |
| Samsung Electronics LC27T55 SAM701F 1920x1080 609x349mm 27.6-inch      | 2         | 1.14%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                     | 2         | 1.14%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch               | 2         | 1.14%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch       | 2         | 1.14%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch       | 2         | 1.14%   |
| AYANEO AYANEOWUXGA AYA0105 1200x1920                                   | 2         | 1.14%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch         | 2         | 1.14%   |
| AOC 2790WG5 AOC2790 1920x1080 598x336mm 27.0-inch                      | 2         | 1.14%   |
| Vizio V555-J01 VIZ1039 3840x2160 1209x680mm 54.6-inch                  | 1         | 0.57%   |
| Vizio OLED65-H1 VIZ1040 3840x2160 1428x803mm 64.5-inch                 | 1         | 0.57%   |
| Vizio M322i-B1 VIZ1005 1920x1080 698x392mm 31.5-inch                   | 1         | 0.57%   |
| Vizio E500i-A1 VIZ1004 1920x1080 1095x616mm 49.5-inch                  | 1         | 0.57%   |
| Vizio D40f-G9 VIZ1027 1920x1080 477x268mm 21.5-inch                    | 1         | 0.57%   |
| ViewSonic VA2702w VSCE727 1920x1080 598x336mm 27.0-inch                | 1         | 0.57%   |
| VIE ATHEN U2L 24 VIE2380 1920x1080 527x296mm 23.8-inch                 | 1         | 0.57%   |
| Valve ANX7530 U VLV3003 800x1280 100x160mm 7.4-inch                    | 1         | 0.57%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch          | 1         | 0.57%   |
| Toshiba TV TSB0206 1920x1080                                           | 1         | 0.57%   |
| Toshiba TV TSB002F 3840x2160 1095x616mm 49.5-inch                      | 1         | 0.57%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch                | 1         | 0.57%   |
| Sony TV SNYEE01 1920x1080                                              | 1         | 0.57%   |
| Sony TV SNY3002 1920x1080 531x299mm 24.0-inch                          | 1         | 0.57%   |
| Sharp LQ173M1JW02 SHP14DB 1920x1080 382x215mm 17.3-inch                | 1         | 0.57%   |
| Sharp LCD Monitor SHP1515 1920x1200 336x210mm 15.6-inch                | 1         | 0.57%   |
| Sharp HDMI SHP101E 1920x1080 820x460mm 37.0-inch                       | 1         | 0.57%   |
| Sharp HDMI SHP0FE8 1920x1080 1152x648mm 52.0-inch                      | 1         | 0.57%   |
| Sceptre Tech Sceptre C35 SPT0DB7 3440x1440 819x346mm 35.0-inch         | 1         | 0.57%   |
| SANYO TV SAN0206 1920x1080 886x498mm 40.0-inch                         | 1         | 0.57%   |
| SANYO LED MONITOR SAN3219 1360x768 304x228mm 15.0-inch                 | 1         | 0.57%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch      | 1         | 0.57%   |
| Samsung Electronics SyncMaster SAM030F 1680x1050 474x296mm 22.0-inch   | 1         | 0.57%   |
| Samsung Electronics SyncMaster SAM01AC 1600x1200 312x234mm 15.4-inch   | 1         | 0.57%   |
| Samsung Electronics S24R35xFZ SAM71A8 1920x1080 521x293mm 23.5-inch    | 1         | 0.57%   |
| Samsung Electronics S24C650 SAM09E8 1920x1080 521x293mm 23.5-inch      | 1         | 0.57%   |
| Samsung Electronics S24C300 SAM0A24 1920x1080 531x299mm 24.0-inch      | 1         | 0.57%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 84        | 49.12%  |
| 3840x2160 (4K)     | 30        | 17.54%  |
| 2560x1440 (QHD)    | 13        | 7.6%    |
| 1366x768 (WXGA)    | 10        | 5.85%   |
| 3440x1440          | 4         | 2.34%   |
| 2560x1080          | 4         | 2.34%   |
| 1600x2560          | 4         | 2.34%   |
| 1200x1920          | 4         | 2.34%   |
| 1600x900 (HD+)     | 3         | 1.75%   |
| 800x1280           | 2         | 1.17%   |
| 1920x540           | 2         | 1.17%   |
| 1920x1200 (WUXGA)  | 2         | 1.17%   |
| 1680x1050 (WSXGA+) | 2         | 1.17%   |
| 3840x1600          | 1         | 0.58%   |
| 3840x1080          | 1         | 0.58%   |
| 1600x1200          | 1         | 0.58%   |
| 1360x768           | 1         | 0.58%   |
| 1280x960           | 1         | 0.58%   |
| 1280x768           | 1         | 0.58%   |
| 1080x1920          | 1         | 0.58%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 33        | 18.86%  |
| 27      | 25        | 14.29%  |
| 84      | 10        | 5.71%   |
| Unknown | 10        | 5.71%   |
| 23      | 8         | 4.57%   |
| 17      | 8         | 4.57%   |
| 34      | 7         | 4%      |
| 31      | 7         | 4%      |
| 24      | 7         | 4%      |
| 72      | 5         | 2.86%   |
| 54      | 5         | 2.86%   |
| 21      | 5         | 2.86%   |
| 14      | 4         | 2.29%   |
| 13      | 4         | 2.29%   |
| 8       | 4         | 2.29%   |
| 7       | 4         | 2.29%   |
| 48      | 3         | 1.71%   |
| 49      | 2         | 1.14%   |
| 46      | 2         | 1.14%   |
| 40      | 2         | 1.14%   |
| 22      | 2         | 1.14%   |
| 20      | 2         | 1.14%   |
| 74      | 1         | 0.57%   |
| 69      | 1         | 0.57%   |
| 64      | 1         | 0.57%   |
| 57      | 1         | 0.57%   |
| 52      | 1         | 0.57%   |
| 47      | 1         | 0.57%   |
| 38      | 1         | 0.57%   |
| 37      | 1         | 0.57%   |
| 35      | 1         | 0.57%   |
| 29      | 1         | 0.57%   |
| 28      | 1         | 0.57%   |
| 26      | 1         | 0.57%   |
| 18      | 1         | 0.57%   |
| 16      | 1         | 0.57%   |
| 12      | 1         | 0.57%   |
| 11      | 1         | 0.57%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 39        | 22.54%  |
| 501-600     | 37        | 21.39%  |
| 1501-2000   | 16        | 9.25%   |
| 1001-1500   | 15        | 8.67%   |
| 601-700     | 12        | 6.94%   |
| 401-500     | 10        | 5.78%   |
| Unknown     | 10        | 5.78%   |
| 351-400     | 9         | 5.2%    |
| 701-800     | 8         | 4.62%   |
| 101-200     | 7         | 4.05%   |
| 801-900     | 5         | 2.89%   |
| 201-300     | 4         | 2.31%   |
| 1-100       | 1         | 0.58%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 130       | 78.79%  |
| 21/9  | 9         | 5.45%   |
| 16/10 | 9         | 5.45%   |
| 0.62  | 9         | 5.45%   |
| 4/3   | 2         | 1.21%   |
| 32/9  | 2         | 1.21%   |
| 0.56  | 2         | 1.21%   |
| 1.96  | 1         | 0.61%   |
| 0.58  | 1         | 0.61%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 32        | 18.71%  |
| 301-350        | 27        | 15.79%  |
| More than 1000 | 26        | 15.2%   |
| 201-250        | 19        | 11.11%  |
| 351-500        | 14        | 8.19%   |
| 501-1000       | 10        | 5.85%   |
| Unknown        | 10        | 5.85%   |
| 1-40           | 8         | 4.68%   |
| 121-130        | 8         | 4.68%   |
| 81-90          | 6         | 3.51%   |
| 71-80          | 3         | 1.75%   |
| 151-200        | 3         | 1.75%   |
| 111-120        | 2         | 1.17%   |
| 51-60          | 1         | 0.58%   |
| 251-300        | 1         | 0.58%   |
| 141-150        | 1         | 0.58%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 71        | 41.52%  |
| 121-160       | 41        | 23.98%  |
| 101-120       | 20        | 11.7%   |
| 1-50          | 12        | 7.02%   |
| 161-240       | 10        | 5.85%   |
| Unknown       | 10        | 5.85%   |
| More than 240 | 7         | 4.09%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 148       | 76.68%  |
| 0     | 24        | 12.44%  |
| 2     | 19        | 9.84%   |
| 3     | 2         | 1.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 123       | 39.68%  |
| Intel                           | 98        | 31.61%  |
| Qualcomm Atheros                | 25        | 8.06%   |
| MediaTek                        | 20        | 6.45%   |
| Broadcom                        | 8         | 2.58%   |
| TP-Link                         | 7         | 2.26%   |
| Microsoft                       | 6         | 1.94%   |
| Broadcom Limited                | 3         | 0.97%   |
| ASIX Electronics                | 3         | 0.97%   |
| Samsung Electronics             | 2         | 0.65%   |
| Ralink Technology               | 2         | 0.65%   |
| Ralink                          | 2         | 0.65%   |
| Qualcomm Atheros Communications | 2         | 0.65%   |
| Qualcomm                        | 2         | 0.65%   |
| Marvell Technology Group        | 2         | 0.65%   |
| DisplayLink                     | 2         | 0.65%   |
| OnePlus Technology (Shenzhen)   | 1         | 0.32%   |
| Edimax Technology               | 1         | 0.32%   |
| Aquantia                        | 1         | 0.32%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 80        | 22.41%  |
| Realtek RTL8125 2.5GbE Controller                                      | 26        | 7.28%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 20        | 5.6%    |
| Intel Wi-Fi 6 AX200                                                    | 9         | 2.52%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 8         | 2.24%   |
| Intel I211 Gigabit Network Connection                                  | 8         | 2.24%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 7         | 1.96%   |
| Intel Ethernet Controller I225-V                                       | 7         | 1.96%   |
| Intel Ethernet Connection I217-LM                                      | 7         | 1.96%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 6         | 1.68%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 6         | 1.68%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 6         | 1.68%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 6         | 1.68%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 5         | 1.4%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 5         | 1.4%    |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller            | 4         | 1.12%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 4         | 1.12%   |
| Microsoft XBOX ACC                                                     | 4         | 1.12%   |
| Intel Wireless 8265 / 8275                                             | 4         | 1.12%   |
| Intel Wireless 7265                                                    | 4         | 1.12%   |
| Intel Wireless 3165                                                    | 4         | 1.12%   |
| Intel Ethernet Connection (2) I219-V                                   | 4         | 1.12%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 4         | 1.12%   |
| TP-Link Archer T4U ver.3                                               | 3         | 0.84%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 3         | 0.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 3         | 0.84%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 3         | 0.84%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 3         | 0.84%   |
| Intel Wi-Fi 6 AX201                                                    | 3         | 0.84%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 3         | 0.84%   |
| Intel Ethernet Controller I226-V                                       | 3         | 0.84%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 3         | 0.84%   |
| Intel 82579V Gigabit Network Connection                                | 3         | 0.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3         | 0.84%   |
| ASIX AX88179 Gigabit Ethernet                                          | 3         | 0.84%   |
| TP-Link 802.11ac NIC                                                   | 2         | 0.56%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 2         | 0.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2         | 0.56%   |
| Realtek PCIe GbE Family Controller                                     | 2         | 0.56%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                              | 2         | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 71        | 42.77%  |
| Realtek Semiconductor           | 27        | 16.27%  |
| Qualcomm Atheros                | 21        | 12.65%  |
| MediaTek                        | 20        | 12.05%  |
| TP-Link                         | 7         | 4.22%   |
| Microsoft                       | 6         | 3.61%   |
| Broadcom                        | 4         | 2.41%   |
| Ralink Technology               | 2         | 1.2%    |
| Ralink                          | 2         | 1.2%    |
| Qualcomm Atheros Communications | 2         | 1.2%    |
| Qualcomm                        | 1         | 0.6%    |
| Marvell Technology Group        | 1         | 0.6%    |
| Edimax Technology               | 1         | 0.6%    |
| Broadcom Limited                | 1         | 0.6%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]     | 20        | 11.7%   |
| Intel Wi-Fi 6 AX200                                           | 9         | 5.26%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 8         | 4.68%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 7         | 4.09%   |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 6         | 3.51%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 6         | 3.51%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 6         | 3.51%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 6         | 3.51%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 5         | 2.92%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller   | 4         | 2.34%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 4         | 2.34%   |
| Microsoft XBOX ACC                                            | 4         | 2.34%   |
| Intel Wireless 8265 / 8275                                    | 4         | 2.34%   |
| Intel Wireless 7265                                           | 4         | 2.34%   |
| Intel Wireless 3165                                           | 4         | 2.34%   |
| Intel Comet Lake PCH CNVi WiFi                                | 4         | 2.34%   |
| TP-Link Archer T4U ver.3                                      | 3         | 1.75%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller   | 3         | 1.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 3         | 1.75%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 3         | 1.75%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter              | 3         | 1.75%   |
| Intel Wi-Fi 6 AX201                                           | 3         | 1.75%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 3         | 1.75%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 3         | 1.75%   |
| TP-Link 802.11ac NIC                                          | 2         | 1.17%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 2         | 1.17%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                     | 2         | 1.17%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]       | 2         | 1.17%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 2         | 1.17%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 2         | 1.17%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                        | 1         | 0.58%   |
| TP-Link 802.11ac WLAN Adapter                                 | 1         | 0.58%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 1         | 0.58%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                    | 1         | 0.58%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 1         | 0.58%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                        | 1         | 0.58%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter               | 1         | 0.58%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 1         | 0.58%   |
| Realtek RTL8187 Wireless Adapter                              | 1         | 0.58%   |
| Realtek 802.11ac NIC                                          | 1         | 0.58%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 115       | 63.19%  |
| Intel                    | 45        | 24.73%  |
| Qualcomm Atheros         | 5         | 2.75%   |
| Broadcom                 | 5         | 2.75%   |
| ASIX Electronics         | 3         | 1.65%   |
| Samsung Electronics      | 2         | 1.1%    |
| DisplayLink              | 2         | 1.1%    |
| Broadcom Limited         | 2         | 1.1%    |
| Qualcomm                 | 1         | 0.55%   |
| Marvell Technology Group | 1         | 0.55%   |
| Aquantia                 | 1         | 0.55%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                           | Computers | Percent |
|---------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller          | 80        | 43.24%  |
| Realtek RTL8125 2.5GbE Controller                                               | 26        | 14.05%  |
| Intel I211 Gigabit Network Connection                                           | 8         | 4.32%   |
| Intel Ethernet Controller I225-V                                                | 7         | 3.78%   |
| Intel Ethernet Connection I217-LM                                               | 7         | 3.78%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                        | 5         | 2.7%    |
| Intel Ethernet Connection (2) I219-V                                            | 4         | 2.16%   |
| Intel Ethernet Controller I226-V                                                | 3         | 1.62%   |
| Intel 82579V Gigabit Network Connection                                         | 3         | 1.62%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                           | 3         | 1.62%   |
| ASIX AX88179 Gigabit Ethernet                                                   | 3         | 1.62%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                           | 2         | 1.08%   |
| Realtek PCIe GbE Family Controller                                              | 2         | 1.08%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                       | 2         | 1.08%   |
| Intel Ethernet Connection (5) I219-LM                                           | 2         | 1.08%   |
| Intel Ethernet Connection (2) I219-LM                                           | 2         | 1.08%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                                | 2         | 1.08%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                         | 2         | 1.08%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                     | 1         | 0.54%   |
| Samsung Galaxy series, misc. (tethering mode)                                   | 1         | 0.54%   |
| Realtek Killer E3000 2.5GbE Controller                                          | 1         | 0.54%   |
| Realtek Killer E2600 GbE Controller                                             | 1         | 0.54%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                       | 1         | 0.54%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                       | 1         | 0.54%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                   | 1         | 0.54%   |
| Qualcomm Android                                                                | 1         | 0.54%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                         | 1         | 0.54%   |
| Intel I210 Gigabit Network Connection                                           | 1         | 0.54%   |
| Intel Ethernet Connection I218-LM                                               | 1         | 0.54%   |
| Intel Ethernet Connection I217-V                                                | 1         | 0.54%   |
| Intel Ethernet Connection (14) I219-V                                           | 1         | 0.54%   |
| Intel Ethernet Connection (12) I219-V                                           | 1         | 0.54%   |
| Intel Ethernet Connection (11) I219-V                                           | 1         | 0.54%   |
| Intel Ethernet Connection (11) I219-LM                                          | 1         | 0.54%   |
| DisplayLink HP Port Replicator (Composite Device)                               | 1         | 0.54%   |
| DisplayLink Dell Universal Dock D6000                                           | 1         | 0.54%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                               | 1         | 0.54%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                               | 1         | 0.54%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                                 | 1         | 0.54%   |
| Aquantia AQtion AQC113CS NBase-T/IEEE 802.3an Ethernet Controller [Antigua 10G] | 1         | 0.54%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 171       | 52.62%  |
| WiFi     | 153       | 47.08%  |
| Unknown  | 1         | 0.31%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 117       | 59.69%  |
| Ethernet | 79        | 40.31%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 105       | 54.69%  |
| 1     | 78        | 40.63%  |
| 3     | 9         | 4.69%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 120       | 62.18%  |
| Yes  | 73        | 37.82%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 67        | 46.85%  |
| Realtek Semiconductor           | 15        | 10.49%  |
| Cambridge Silicon Radio         | 12        | 8.39%   |
| MediaTek                        | 11        | 7.69%   |
| IMC Networks                    | 11        | 7.69%   |
| Qualcomm Atheros Communications | 7         | 4.9%    |
| Lite-On Technology              | 6         | 4.2%    |
| Foxconn / Hon Hai               | 5         | 3.5%    |
| Apple                           | 3         | 2.1%    |
| TP-Link                         | 2         | 1.4%    |
| ASUSTek Computer                | 2         | 1.4%    |
| Realtek                         | 1         | 0.7%    |
| Actions                         | 1         | 0.7%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX210 Bluetooth                               | 19        | 13.19%  |
| Realtek Bluetooth Radio                             | 12        | 8.33%   |
| Intel AX201 Bluetooth                               | 12        | 8.33%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 12        | 8.33%   |
| MediaTek Wireless_Device                            | 11        | 7.64%   |
| Intel Bluetooth wireless interface                  | 10        | 6.94%   |
| Intel AX200 Bluetooth                               | 8         | 5.56%   |
| Intel Wireless-AC 3168 Bluetooth                    | 6         | 4.17%   |
| IMC Networks Bluetooth Radio                        | 6         | 4.17%   |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 2.78%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 2.78%   |
| Foxconn / Hon Hai Wireless_Device                   | 4         | 2.78%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 2.08%   |
| Intel Bluetooth Device                              | 3         | 2.08%   |
| IMC Networks Wireless_Device                        | 3         | 2.08%   |
| TP-Link UB500 Adapter                               | 2         | 1.39%   |
| Realtek 802.11ac WLAN Adapter                       | 2         | 1.39%   |
| Lite-On Bluetooth Device                            | 2         | 1.39%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 1.39%   |
| Intel AX211 Bluetooth                               | 2         | 1.39%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.69%   |
| Realtek Bluetooth Radio                             | 1         | 0.69%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.69%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.69%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.69%   |
| Lite-On Wireless_Device                             | 1         | 0.69%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 0.69%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.69%   |
| IMC Networks Bluetooth Device                       | 1         | 0.69%   |
| IMC Networks Atheros AR3012 Bluetooth               | 1         | 0.69%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth     | 1         | 0.69%   |
| ASUS Qualcomm Bluetooth 4.1                         | 1         | 0.69%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 0.69%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 0.69%   |
| Apple Bluetooth USB Host Controller                 | 1         | 0.69%   |
| Apple Bluetooth Host Controller                     | 1         | 0.69%   |
| Actions general adapter                             | 1         | 0.69%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| AMD                      | 114       | 35.85%  |
| Intel                    | 98        | 30.82%  |
| Nvidia                   | 59        | 18.55%  |
| Logitech                 | 7         | 2.2%    |
| Sony                     | 6         | 1.89%   |
| Kingston Technology      | 6         | 1.89%   |
| C-Media Electronics      | 5         | 1.57%   |
| Hewlett-Packard          | 3         | 0.94%   |
| SteelSeries ApS          | 2         | 0.63%   |
| Realtek Semiconductor    | 2         | 0.63%   |
| Razer USA                | 2         | 0.63%   |
| ASUSTek Computer         | 2         | 0.63%   |
| Astro Gaming             | 2         | 0.63%   |
| Texas Instruments        | 1         | 0.31%   |
| Micro Star International | 1         | 0.31%   |
| JMTek                    | 1         | 0.31%   |
| Google                   | 1         | 0.31%   |
| Generalplus Technology   | 1         | 0.31%   |
| Focusrite-Novation       | 1         | 0.31%   |
| Creative Labs            | 1         | 0.31%   |
| Comtrue                  | 1         | 0.31%   |
| BR25                     | 1         | 0.31%   |
| Blue Microphones         | 1         | 0.31%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 50        | 12.11%  |
| AMD Starship/Matisse HD Audio Controller                                   | 25        | 6.05%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 25        | 6.05%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 19        | 4.6%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 17        | 4.12%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 14        | 3.39%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 13        | 3.15%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 11        | 2.66%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 10        | 2.42%   |
| Intel Cannon Lake PCH cAVS                                                 | 8         | 1.94%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 8         | 1.94%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 8         | 1.94%   |
| Nvidia GA104 High Definition Audio Controller                              | 7         | 1.69%   |
| Intel Sunrise Point-LP HD Audio                                            | 7         | 1.69%   |
| Intel Comet Lake PCH cAVS                                                  | 7         | 1.69%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 7         | 1.69%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 6         | 1.45%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 6         | 1.45%   |
| AMD Navi 10 HDMI Audio                                                     | 6         | 1.45%   |
| Nvidia TU106 High Definition Audio Controller                              | 5         | 1.21%   |
| Nvidia GP104 High Definition Audio Controller                              | 5         | 1.21%   |
| Nvidia GA106 High Definition Audio Controller                              | 5         | 1.21%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 5         | 1.21%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 5         | 1.21%   |
| Nvidia TU116 High Definition Audio Controller                              | 4         | 0.97%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4         | 0.97%   |
| Nvidia GA102 High Definition Audio Controller                              | 4         | 0.97%   |
| Nvidia Audio device                                                        | 4         | 0.97%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 0.97%   |
| Intel CM238 HD Audio Controller                                            | 4         | 0.97%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4         | 0.97%   |
| Sony DualShock 4 [CUH-ZCT2x]                                               | 3         | 0.73%   |
| Nvidia TU104 HD Audio Controller                                           | 3         | 0.73%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 0.73%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 3         | 0.73%   |
| Intel Alder Lake-S HD Audio Controller                                     | 3         | 0.73%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 3         | 0.73%   |
| Intel 200 Series PCH HD Audio                                              | 3         | 0.73%   |
| SteelSeries ApS SteelSeries Arctis 1 Wireless                              | 2         | 0.48%   |
| Sony DualSense wireless controller (PS5)                                   | 2         | 0.48%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

Zero info for selected period =(

Memory Model
------------

Memory module models

Zero info for selected period =(

Memory Kind
-----------

Memory module kinds

Zero info for selected period =(

Memory Form Factor
------------------

Physical design of the memory module

Zero info for selected period =(

Memory Size
-----------

Memory module size

Zero info for selected period =(

Memory Speed
------------

Memory module speed

Zero info for selected period =(

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo] | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 14        | 22.95%  |
| Microdia                      | 10        | 16.39%  |
| Sunplus Innovation Technology | 6         | 9.84%   |
| Logitech                      | 6         | 9.84%   |
| IMC Networks                  | 6         | 9.84%   |
| Realtek Semiconductor         | 3         | 4.92%   |
| Quanta                        | 3         | 4.92%   |
| Bison Electronics             | 3         | 4.92%   |
| Apple                         | 3         | 4.92%   |
| YT-221117-J                   | 1         | 1.64%   |
| Syntek                        | 1         | 1.64%   |
| Suyin                         | 1         | 1.64%   |
| Sonix Technology              | 1         | 1.64%   |
| Silicon Motion                | 1         | 1.64%   |
| Samsung Electronics           | 1         | 1.64%   |
| Acer                          | 1         | 1.64%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Sunplus HD WebCam                       | 3         | 4.92%   |
| IMC Networks USB2.0 HD UVC WebCam       | 3         | 4.92%   |
| IMC Networks Integrated Camera          | 3         | 4.92%   |
| Microdia Integrated_Webcam_HD           | 2         | 3.28%   |
| Microdia Integrated_Webcam_FHD          | 2         | 3.28%   |
| Logitech Webcam C930e                   | 2         | 3.28%   |
| Chicony Integrated Camera               | 2         | 3.28%   |
| Chicony HD WebCam                       | 2         | 3.28%   |
| Chicony HD User Facing                  | 2         | 3.28%   |
| Bison Lenovo EasyCamera                 | 2         | 3.28%   |
| YT-221117-J USB2.0 Camera               | 1         | 1.64%   |
| Syntek USB2.0 Camera                    | 1         | 1.64%   |
| Suyin HP Truevision HD                  | 1         | 1.64%   |
| Sunplus Integrated_Webcam_HD            | 1         | 1.64%   |
| Sunplus HD 720P webcam                  | 1         | 1.64%   |
| Sunplus ASUS Webcam                     | 1         | 1.64%   |
| Sonix USB2.0 HD UVC WebCam              | 1         | 1.64%   |
| Silicon Motion 300k Pixel Camera        | 1         | 1.64%   |
| Samsung Galaxy series, misc. (MTP mode) | 1         | 1.64%   |
| Realtek Integrated_Webcam_HD            | 1         | 1.64%   |
| Realtek Integrated_Webcam_FHD           | 1         | 1.64%   |
| Realtek Integrated Webcam               | 1         | 1.64%   |
| Quanta HP Wide Vision HD Camera         | 1         | 1.64%   |
| Quanta HP HD Camera                     | 1         | 1.64%   |
| Quanta HD User Facing                   | 1         | 1.64%   |
| Microdia Webcam Vitade AF               | 1         | 1.64%   |
| Microdia USB Camera                     | 1         | 1.64%   |
| Microdia USB 2.0 Camera                 | 1         | 1.64%   |
| Microdia Laptop_Integrated_Webcam_HD    | 1         | 1.64%   |
| Microdia HP Webcam                      | 1         | 1.64%   |
| Microdia Camera                         | 1         | 1.64%   |
| Logitech Webcam C270                    | 1         | 1.64%   |
| Logitech Webcam C200                    | 1         | 1.64%   |
| Logitech Logi Webcam C920e              | 1         | 1.64%   |
| Logitech HD Pro Webcam C920             | 1         | 1.64%   |
| Chicony USB2.0 FHD Camera               | 1         | 1.64%   |
| Chicony USB2.0 0.3M UVC WebCam          | 1         | 1.64%   |
| Chicony Integrated IR Camera            | 1         | 1.64%   |
| Chicony HP Wide Vision HD Camera        | 1         | 1.64%   |
| Chicony HP Truevision HD                | 1         | 1.64%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 2         | 33.33%  |
| Shenzhen Goodix Technology | 1         | 16.67%  |
| LighTuning Technology      | 1         | 16.67%  |
| Focal-systems.Corp         | 1         | 16.67%  |
| AuthenTec                  | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Synaptics WBDI                                           | 1         | 16.67%  |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 16.67%  |
| Shenzhen Goodix  FingerPrint Device                      | 1         | 16.67%  |
| LighTuning ES603 Swipe Fingerprint Sensor                | 1         | 16.67%  |
| Focal-systems.Corp FT9201Fingerprint.                    | 1         | 16.67%  |
| AuthenTec AES1660 Fingerprint Sensor                     | 1         | 16.67%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 2         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model          | Computers | Percent |
|----------------|-----------|---------|
| Broadcom 5880  | 1         | 50%     |
| Broadcom 58200 | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 114       | 59.38%  |
| 1     | 73        | 38.02%  |
| 2     | 5         | 2.6%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 44        | 53.01%  |
| Network               | 9         | 10.84%  |
| Multimedia controller | 8         | 9.64%   |
| Net/ethernet          | 7         | 8.43%   |
| Net/wireless          | 6         | 7.23%   |
| Fingerprint reader    | 6         | 7.23%   |
| Chipcard              | 2         | 2.41%   |
| Storage/nvme          | 1         | 1.2%    |

