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

Total: 284

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | 312F SDK0J40697 WIN 3305... | Mini pc     | [646b14da1e](https://linux-hardware.org/?probe=646b14da1e) | Dec 30, 2024 |
| ONE-NETBOO... | ONE XPLAYER                 | Tablet      | [f51b8777e8](https://linux-hardware.org/?probe=f51b8777e8) | Dec 14, 2024 |
| Shenzhen M... | DRBAA                       | Desktop     | [fa3ca24355](https://linux-hardware.org/?probe=fa3ca24355) | Dec 07, 2024 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [638c1123d0](https://linux-hardware.org/?probe=638c1123d0) | Dec 05, 2024 |
| Biostar       | H81MLV3                     | Desktop     | [0b38f93635](https://linux-hardware.org/?probe=0b38f93635) | Nov 29, 2024 |
| AYANEO        | AB05-AMD                    | Notebook    | [60390b6f89](https://linux-hardware.org/?probe=60390b6f89) | Nov 16, 2024 |
| AYANEO        | AIR 1S                      | Tablet      | [58f0c948e1](https://linux-hardware.org/?probe=58f0c948e1) | Nov 16, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [a1d36dc841](https://linux-hardware.org/?probe=a1d36dc841) | Nov 04, 2024 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [8659fd177c](https://linux-hardware.org/?probe=8659fd177c) | Oct 31, 2024 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [82ab276d55](https://linux-hardware.org/?probe=82ab276d55) | Oct 31, 2024 |
| Gigabyte      | Z790 AORUS MASTER X         | Desktop     | [f86e1fe5ee](https://linux-hardware.org/?probe=f86e1fe5ee) | Oct 23, 2024 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [353cba650d](https://linux-hardware.org/?probe=353cba650d) | Oct 19, 2024 |
| Gigabyte      | Z790 AORUS MASTER X         | Desktop     | [31611b8c3f](https://linux-hardware.org/?probe=31611b8c3f) | Oct 17, 2024 |
| ASRock        | X570 Taichi                 | Desktop     | [e2c762be95](https://linux-hardware.org/?probe=e2c762be95) | Oct 16, 2024 |
| AYANEO        | AB05-AMD                    | Notebook    | [a9f0ebcf7c](https://linux-hardware.org/?probe=a9f0ebcf7c) | Oct 07, 2024 |
| Gigabyte      | A520I AC                    | Desktop     | [c6a5317149](https://linux-hardware.org/?probe=c6a5317149) | Sep 21, 2024 |
| Dell          | Latitude 7420               | Notebook    | [7eb7fea444](https://linux-hardware.org/?probe=7eb7fea444) | Sep 20, 2024 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [109404b71a](https://linux-hardware.org/?probe=109404b71a) | Sep 19, 2024 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [54ce0b3d34](https://linux-hardware.org/?probe=54ce0b3d34) | Sep 16, 2024 |
| Lenovo        | ThinkPad X230 23255J6       | Notebook    | [e754879569](https://linux-hardware.org/?probe=e754879569) | Sep 15, 2024 |
| HUAWEI        | NBM-WXX9                    | Notebook    | [4445b6689d](https://linux-hardware.org/?probe=4445b6689d) | Sep 08, 2024 |
| ONE-NETBOO... | ONEXPLAYER X1 mini          | Notebook    | [6b39950dc6](https://linux-hardware.org/?probe=6b39950dc6) | Aug 28, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [ed06f1be24](https://linux-hardware.org/?probe=ed06f1be24) | Aug 17, 2024 |
| Apple         | MacBookPro11,4              | Notebook    | [dfede07c9d](https://linux-hardware.org/?probe=dfede07c9d) | Aug 16, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [a7190fb979](https://linux-hardware.org/?probe=a7190fb979) | Jul 31, 2024 |
| ASRock        | A520M-ITX/ac                | Desktop     | [85947c736b](https://linux-hardware.org/?probe=85947c736b) | Jul 29, 2024 |
| ASRock        | 970A-G                      | Desktop     | [7d66332210](https://linux-hardware.org/?probe=7d66332210) | Jul 26, 2024 |
| ASRock        | B450M Pro4                  | Desktop     | [f5ce4a9f35](https://linux-hardware.org/?probe=f5ce4a9f35) | Jul 25, 2024 |
| ASUSTek       | ROG Ally RC71L_RC71L        | Tablet      | [b1e7ff3985](https://linux-hardware.org/?probe=b1e7ff3985) | Jul 13, 2024 |
| Intel         | X99-P4 V8.2                 | Desktop     | [b02cd106bf](https://linux-hardware.org/?probe=b02cd106bf) | Jul 05, 2024 |
| ASRock        | B550M Pro4                  | Notebook    | [71d8153a82](https://linux-hardware.org/?probe=71d8153a82) | Jun 29, 2024 |
| MSI           | PRO B650M-B                 | Desktop     | [624bc9d85a](https://linux-hardware.org/?probe=624bc9d85a) | Jun 29, 2024 |
| MSI           | PRO B650M-B                 | Desktop     | [814e12e091](https://linux-hardware.org/?probe=814e12e091) | Jun 29, 2024 |
| MSI           | A520M-A PRO                 | Notebook    | [3df6b0c991](https://linux-hardware.org/?probe=3df6b0c991) | Jun 25, 2024 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [f24f6c287a](https://linux-hardware.org/?probe=f24f6c287a) | Jun 13, 2024 |
| MSI           | GP60 2QF                    | Notebook    | [40ac6a147a](https://linux-hardware.org/?probe=40ac6a147a) | Jun 13, 2024 |
| ONE-NETBOO... | ONEXPLAYER 2 PRO ARP23P     | Notebook    | [326ee7fd03](https://linux-hardware.org/?probe=326ee7fd03) | Jun 08, 2024 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [deab23a295](https://linux-hardware.org/?probe=deab23a295) | Jun 08, 2024 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [178ff3ba92](https://linux-hardware.org/?probe=178ff3ba92) | Jun 06, 2024 |
| HP            | 212A                        | Desktop     | [14d0c6a707](https://linux-hardware.org/?probe=14d0c6a707) | Jun 05, 2024 |
| Lenovo        | 3130 SDK0J40697 WIN 3305... | Mini pc     | [495e163b58](https://linux-hardware.org/?probe=495e163b58) | Jun 01, 2024 |
| Gigabyte      | A520I AC                    | Desktop     | [f043ddb98c](https://linux-hardware.org/?probe=f043ddb98c) | May 27, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ARH7 ... | Notebook    | [1886617675](https://linux-hardware.org/?probe=1886617675) | May 27, 2024 |
| Gigabyte      | A520I AC                    | Desktop     | [d818c81141](https://linux-hardware.org/?probe=d818c81141) | May 23, 2024 |
| HP            | 83E9                        | Desktop     | [0854536f3e](https://linux-hardware.org/?probe=0854536f3e) | May 19, 2024 |
| Micro Comp... | Uranus Series               | Notebook    | [e1a6fe56df](https://linux-hardware.org/?probe=e1a6fe56df) | May 19, 2024 |
| AZW           | GTR V02                     | Desktop     | [8ecb74cbb8](https://linux-hardware.org/?probe=8ecb74cbb8) | May 19, 2024 |
| GPD           | G1618-03                    | Notebook    | [9e3bd9bdf5](https://linux-hardware.org/?probe=9e3bd9bdf5) | May 16, 2024 |
| Lenovo        | Legion Go 8APU1 83E1        | Tablet      | [6582da7bda](https://linux-hardware.org/?probe=6582da7bda) | May 11, 2024 |
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
| Micro Comp... | HX100G                      | Desktop     | [30d14495d2](https://linux-hardware.org/?probe=30d14495d2) | Feb 15, 2024 |
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

![OS](./All/images/pie_chart/os_name.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| ChimeraOS 44-1 | 62        | 25.83%  |
| ChimeraOS 45-1 | 31        | 12.92%  |
| ChimeraOS 45   | 26        | 10.83%  |
| ChimeraOS 43-1 | 25        | 10.42%  |
| ChimeraOS 42   | 18        | 7.5%    |
| ChimeraOS 39   | 15        | 6.25%   |
| ChimeraOS 46-2 | 14        | 5.83%   |
| ChimeraOS 41   | 11        | 4.58%   |
| ChimeraOS 43   | 8         | 3.33%   |
| ChimeraOS 38   | 6         | 2.5%    |
| ChimeraOS 46   | 5         | 2.08%   |
| ChimeraOS 44   | 5         | 2.08%   |
| ChimeraOS      | 5         | 2.08%   |
| ChimeraOS 37   | 4         | 1.67%   |
| ChimeraOS 47-7 | 1         | 0.42%   |
| ChimeraOS 47-4 | 1         | 0.42%   |
| ChimeraOS 47-1 | 1         | 0.42%   |
| ChimeraOS 46-8 | 1         | 0.42%   |
| ChimeraOS 35   | 1         | 0.42%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| ChimeraOS | 236       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                     | Computers | Percent |
|-----------------------------|-----------|---------|
| 6.5.6-chos1-chimeraos-1     | 61        | 25.21%  |
| 6.6.10-chos1-chimeraos-2    | 54        | 22.31%  |
| 6.3.9-chimeraos-1           | 32        | 13.22%  |
| 6.1.27-1-lts                | 18        | 7.44%   |
| 6.1.11-arch1-1              | 15        | 6.2%    |
| 6.9.12-chos7-chimeraos-1    | 14        | 5.79%   |
| 6.1.21-1-lts                | 11        | 4.55%   |
| 6.1.1-arch1-1               | 6         | 2.48%   |
| 6.5.3-chos1-chimeraos-1     | 5         | 2.07%   |
| 6.9.9-chos1-chimeraos-1     | 4         | 1.65%   |
| 6.0.8-arch1-1               | 4         | 1.65%   |
| 6.9.3-sk-chos3-chimeraos-1  | 1         | 0.41%   |
| 6.8.2-0-generic             | 1         | 0.41%   |
| 6.8.0-rc2-chos1-chimeraos-1 | 1         | 0.41%   |
| 6.6.7-chos4-chimeraos-1     | 1         | 0.41%   |
| 6.6.6-arch1-1               | 1         | 0.41%   |
| 6.6.56-0-generic            | 1         | 0.41%   |
| 6.6.51-0-generic            | 1         | 0.41%   |
| 6.6.37-0-generic            | 1         | 0.41%   |
| 6.6.1-chos3-chimeraos-3     | 1         | 0.41%   |
| 6.6.1-chos3-chimeraos-1     | 1         | 0.41%   |
| 6.4.9-0-generic             | 1         | 0.41%   |
| 6.3.3-arch1-1               | 1         | 0.41%   |
| 6.3.1-arch2-1               | 1         | 0.41%   |
| 6.11.4-0-generic            | 1         | 0.41%   |
| 6.11.1-sk-chos1-chimeraos-1 | 1         | 0.41%   |
| 6.10.8-sk-chos1-chimeraos-1 | 1         | 0.41%   |
| 6.10.3-arch1-chimeraos-1    | 1         | 0.41%   |
| 5.19.6-arch1-1              | 1         | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.5.6   | 61        | 25.21%  |
| 6.6.10  | 54        | 22.31%  |
| 6.3.9   | 32        | 13.22%  |
| 6.1.27  | 18        | 7.44%   |
| 6.1.11  | 15        | 6.2%    |
| 6.9.12  | 14        | 5.79%   |
| 6.1.21  | 11        | 4.55%   |
| 6.1.1   | 6         | 2.48%   |
| 6.5.3   | 5         | 2.07%   |
| 6.9.9   | 4         | 1.65%   |
| 6.0.8   | 4         | 1.65%   |
| 6.6.1   | 2         | 0.83%   |
| 6.9.3   | 1         | 0.41%   |
| 6.8.2   | 1         | 0.41%   |
| 6.8.0   | 1         | 0.41%   |
| 6.6.7   | 1         | 0.41%   |
| 6.6.6   | 1         | 0.41%   |
| 6.6.56  | 1         | 0.41%   |
| 6.6.51  | 1         | 0.41%   |
| 6.6.37  | 1         | 0.41%   |
| 6.4.9   | 1         | 0.41%   |
| 6.3.3   | 1         | 0.41%   |
| 6.3.1   | 1         | 0.41%   |
| 6.11.4  | 1         | 0.41%   |
| 6.11.1  | 1         | 0.41%   |
| 6.10.8  | 1         | 0.41%   |
| 6.10.3  | 1         | 0.41%   |
| 5.19.6  | 1         | 0.41%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.5     | 66        | 27.5%   |
| 6.6     | 61        | 25.42%  |
| 6.1     | 49        | 20.42%  |
| 6.3     | 33        | 13.75%  |
| 6.9     | 19        | 7.92%   |
| 6.0     | 4         | 1.67%   |
| 6.8     | 2         | 0.83%   |
| 6.11    | 2         | 0.83%   |
| 6.10    | 2         | 0.83%   |
| 6.4     | 1         | 0.42%   |
| 5.19    | 1         | 0.42%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 236       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GNOME   | 229       | 97.03%  |
| Unknown | 4         | 1.69%   |
| KDE6    | 2         | 0.85%   |
| steamos | 1         | 0.42%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 223       | 94.49%  |
| X11     | 10        | 4.24%   |
| Unknown | 3         | 1.27%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 236       | 100%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 190       | 80.51%  |
| fr_FR   | 7         | 2.97%   |
| es_ES   | 7         | 2.97%   |
| zh_CN   | 6         | 2.54%   |
| pt_BR   | 6         | 2.54%   |
| de_DE   | 6         | 2.54%   |
| Unknown | 4         | 1.69%   |
| it_IT   | 3         | 1.27%   |
| es_AR   | 2         | 0.85%   |
| ko_KR   | 1         | 0.42%   |
| ja_JP   | 1         | 0.42%   |
| fr_CA   | 1         | 0.42%   |
| en_GB   | 1         | 0.42%   |
| C       | 1         | 0.42%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 236       | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Btrfs | 231       | 97.88%  |
| Xfs   | 2         | 0.85%   |
| Ext4  | 2         | 0.85%   |
| Tmpfs | 1         | 0.42%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 232       | 98.31%  |
| GPT     | 4         | 1.69%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 235       | 99.58%  |
| Yes       | 1         | 0.42%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 234       | 99.15%  |
| Yes       | 2         | 0.85%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| ASUSTek Computer                     | 49        | 20.76%  |
| Gigabyte Technology                  | 31        | 13.14%  |
| Dell                                 | 25        | 10.59%  |
| Hewlett-Packard                      | 19        | 8.05%   |
| MSI                                  | 14        | 5.93%   |
| Lenovo                               | 13        | 5.51%   |
| ASRock                               | 13        | 5.51%   |
| Acer                                 | 11        | 4.66%   |
| AYANEO                               | 7         | 2.97%   |
| Shenzhen Meigao Electronic Equipment | 6         | 2.54%   |
| ONE-NETBOOK                          | 6         | 2.54%   |
| Intel                                | 5         | 2.12%   |
| ONE-NETBOOK TECHNOLOGY               | 3         | 1.27%   |
| GPD                                  | 3         | 1.27%   |
| AZW                                  | 3         | 1.27%   |
| Apple                                | 3         | 1.27%   |
| Razer                                | 2         | 0.85%   |
| Micro Computer (HK) Tech Limited     | 2         | 0.85%   |
| HUAWEI                               | 2         | 0.85%   |
| HC Technology.                       | 2         | 0.85%   |
| ZOTAC                                | 1         | 0.42%   |
| Valve                                | 1         | 0.42%   |
| Soyo                                 | 1         | 0.42%   |
| Sony                                 | 1         | 0.42%   |
| Notebook                             | 1         | 0.42%   |
| Microsoft                            | 1         | 0.42%   |
| Micro Electronics                    | 1         | 0.42%   |
| MACHINIST                            | 1         | 0.42%   |
| Google                               | 1         | 0.42%   |
| GMKtec                               | 1         | 0.42%   |
| Gateway                              | 1         | 0.42%   |
| Fujitsu                              | 1         | 0.42%   |
| Biostar                              | 1         | 0.42%   |
| Anbernic                             | 1         | 0.42%   |
| AMI                                  | 1         | 0.42%   |
| Alienware                            | 1         | 0.42%   |
| Acidanthera                          | 1         | 0.42%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                                  | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Gigabyte A520I AC                                     | 6         | 2.54%   |
| Gigabyte B550I AORUS PRO AX                           | 5         | 2.12%   |
| Shenzhen Meigao Electronic Equipment Venus series     | 4         | 1.69%   |
| ASUS ROG Ally RC71L_RC71L                             | 4         | 1.69%   |
| ONE-NETBOOK TECHNOLOGY ONE XPLAYER                    | 3         | 1.27%   |
| Dell OptiPlex 3060                                    | 3         | 1.27%   |
| AYANEO 2                                              | 3         | 1.27%   |
| ONE-NETBOOK ONEXPLAYER 2 PRO ARP23P                   | 2         | 0.85%   |
| ONE-NETBOOK ONEXPLAYER 2 ARP23                        | 2         | 0.85%   |
| MSI MS-7A38                                           | 2         | 0.85%   |
| HP Victus by 15L Gaming Desktop TG02-0xxx             | 2         | 0.85%   |
| HP EliteDesk 800 G1 SFF                               | 2         | 0.85%   |
| Dell OptiPlex 7020                                    | 2         | 0.85%   |
| Dell OptiPlex 5055 Ryzen APU                          | 2         | 0.85%   |
| Dell OptiPlex 3070                                    | 2         | 0.85%   |
| AZW SER                                               | 2         | 0.85%   |
| AYANEO AIR Plus                                       | 2         | 0.85%   |
| ASUS ROG STRIX B550-F GAMING                          | 2         | 0.85%   |
| Acer Aspire V3-772G                                   | 2         | 0.85%   |
| Unknown                                               | 2         | 0.85%   |
| ZOTAC ZBOX-ECM73070C/53060C                           | 1         | 0.42%   |
| Valve Galileo                                         | 1         | 0.42%   |
| Soyo SY-Classic B450M                                 | 1         | 0.42%   |
| Sony SVS13A25PLB                                      | 1         | 0.42%   |
| Shenzhen Meigao Electronic Equipment Uranus Series    | 1         | 0.42%   |
| Shenzhen Meigao Electronic Equipment AtomMan G Series | 1         | 0.42%   |
| Razer Blade Pro 17 (Early 2020) - RZ09-0329           | 1         | 0.42%   |
| Razer Blade 14 - RZ09-0370                            | 1         | 0.42%   |
| ONE-NETBOOK ONEXPLAYER X1 mini                        | 1         | 0.42%   |
| ONE-NETBOOK ONEXPLAYER F1                             | 1         | 0.42%   |
| Notebook P15SM-A/SM1-A                                | 1         | 0.42%   |
| MSI MS-7E28                                           | 1         | 0.42%   |
| MSI MS-7D78                                           | 1         | 0.42%   |
| MSI MS-7D73                                           | 1         | 0.42%   |
| MSI MS-7C96                                           | 1         | 0.42%   |
| MSI MS-7C91                                           | 1         | 0.42%   |
| MSI MS-7C56                                           | 1         | 0.42%   |
| MSI MS-7C02                                           | 1         | 0.42%   |
| MSI MS-7B86                                           | 1         | 0.42%   |
| MSI MS-7850                                           | 1         | 0.42%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                                         | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Dell OptiPlex                                | 14        | 5.93%   |
| ASUS ROG                                     | 14        | 5.93%   |
| ASUS PRIME                                   | 8         | 3.39%   |
| Acer Aspire                                  | 8         | 3.39%   |
| ASUS TUF                                     | 7         | 2.97%   |
| ONE-NETBOOK ONEXPLAYER                       | 6         | 2.54%   |
| Gigabyte A520I                               | 6         | 2.54%   |
| HP Victus                                    | 5         | 2.12%   |
| Gigabyte B550I                               | 5         | 2.12%   |
| Shenzhen Meigao Electronic Equipment Venus   | 4         | 1.69%   |
| Lenovo ThinkCentre                           | 4         | 1.69%   |
| Lenovo IdeaPad                               | 4         | 1.69%   |
| HP EliteDesk                                 | 4         | 1.69%   |
| Dell Latitude                                | 4         | 1.69%   |
| AYANEO AIR                                   | 4         | 1.69%   |
| ASUS ASUS                                    | 4         | 1.69%   |
| ONE-NETBOOK TECHNOLOGY ONE                   | 3         | 1.27%   |
| Dell Precision                               | 3         | 1.27%   |
| Dell Inspiron                                | 3         | 1.27%   |
| AYANEO 2                                     | 3         | 1.27%   |
| Razer Blade                                  | 2         | 0.85%   |
| MSI MS-7A38                                  | 2         | 0.85%   |
| Lenovo ThinkPad                              | 2         | 0.85%   |
| Lenovo Legion                                | 2         | 0.85%   |
| HP Pavilion                                  | 2         | 0.85%   |
| Gigabyte X570                                | 2         | 0.85%   |
| Gigabyte B450                                | 2         | 0.85%   |
| AZW SER                                      | 2         | 0.85%   |
| Acer Nitro                                   | 2         | 0.85%   |
| Unknown                                      | 2         | 0.85%   |
| ZOTAC ZBOX-ECM73070C                         | 1         | 0.42%   |
| Valve Galileo                                | 1         | 0.42%   |
| Soyo SY-Classic                              | 1         | 0.42%   |
| Sony SVS13A25PLB                             | 1         | 0.42%   |
| Shenzhen Meigao Electronic Equipment Uranus  | 1         | 0.42%   |
| Shenzhen Meigao Electronic Equipment AtomMan | 1         | 0.42%   |
| Notebook P15SM-A                             | 1         | 0.42%   |
| MSI MS-7E28                                  | 1         | 0.42%   |
| MSI MS-7D78                                  | 1         | 0.42%   |
| MSI MS-7D73                                  | 1         | 0.42%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2023 | 36        | 15.25%  |
| 2021 | 34        | 14.41%  |
| 2020 | 32        | 13.56%  |
| 2022 | 20        | 8.47%   |
| 2019 | 19        | 8.05%   |
| 2017 | 14        | 5.93%   |
| 2013 | 14        | 5.93%   |
| 2015 | 13        | 5.51%   |
| 2012 | 13        | 5.51%   |
| 2018 | 12        | 5.08%   |
| 2016 | 7         | 2.97%   |
| 2014 | 7         | 2.97%   |
| 2011 | 7         | 2.97%   |
| 2024 | 5         | 2.12%   |
| 2010 | 2         | 0.85%   |
| 2008 | 1         | 0.42%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 124       | 52.54%  |
| Notebook    | 80        | 33.9%   |
| Tablet      | 15        | 6.36%   |
| Mini pc     | 11        | 4.66%   |
| All in one  | 5         | 2.12%   |
| Convertible | 1         | 0.42%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 236       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 234       | 99.15%  |
| Yes  | 2         | 0.85%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 65        | 27.43%  |
| 32.01-64.0  | 50        | 21.1%   |
| 8.01-16.0   | 48        | 20.25%  |
| 4.01-8.0    | 31        | 13.08%  |
| 24.01-32.0  | 26        | 10.97%  |
| 64.01-256.0 | 10        | 4.22%   |
| 3.01-4.0    | 7         | 2.95%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 93        | 38.75%  |
| 1.01-2.0   | 50        | 20.83%  |
| 3.01-4.0   | 48        | 20%     |
| 4.01-8.0   | 46        | 19.17%  |
| 8.01-16.0  | 2         | 0.83%   |
| 16.01-24.0 | 1         | 0.42%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 129       | 53.75%  |
| 2      | 70        | 29.17%  |
| 3      | 26        | 10.83%  |
| 4      | 6         | 2.5%    |
| 5      | 3         | 1.25%   |
| 6      | 2         | 0.83%   |
| 11     | 1         | 0.42%   |
| 8      | 1         | 0.42%   |
| 7      | 1         | 0.42%   |
| 0      | 1         | 0.42%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 199       | 84.32%  |
| Yes       | 37        | 15.68%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 207       | 87.71%  |
| No        | 29        | 12.29%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 187       | 79.24%  |
| No        | 49        | 20.76%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 175       | 74.15%  |
| No        | 61        | 25.85%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country       | Computers | Percent |
|---------------|-----------|---------|
| USA           | 91        | 38.56%  |
| Germany       | 16        | 6.78%   |
| Brazil        | 13        | 5.51%   |
| UK            | 12        | 5.08%   |
| France        | 10        | 4.24%   |
| Canada        | 9         | 3.81%   |
| Russia        | 7         | 2.97%   |
| Spain         | 6         | 2.54%   |
| Australia     | 6         | 2.54%   |
| Poland        | 5         | 2.12%   |
| Vietnam       | 4         | 1.69%   |
| Italy         | 4         | 1.69%   |
| China         | 4         | 1.69%   |
| Saudi Arabia  | 3         | 1.27%   |
| Peru          | 3         | 1.27%   |
| Netherlands   | 3         | 1.27%   |
| Mexico        | 3         | 1.27%   |
| Turkey        | 2         | 0.85%   |
| Switzerland   | 2         | 0.85%   |
| South Korea   | 2         | 0.85%   |
| Norway        | 2         | 0.85%   |
| Malaysia      | 2         | 0.85%   |
| Japan         | 2         | 0.85%   |
| Hungary       | 2         | 0.85%   |
| Honduras      | 2         | 0.85%   |
| Estonia       | 2         | 0.85%   |
| Colombia      | 2         | 0.85%   |
| Argentina     | 2         | 0.85%   |
| South Africa  | 1         | 0.42%   |
| Romania       | 1         | 0.42%   |
| Philippines   | 1         | 0.42%   |
| New Zealand   | 1         | 0.42%   |
| Macao         | 1         | 0.42%   |
| Indonesia     | 1         | 0.42%   |
| Iceland       | 1         | 0.42%   |
| French Guiana | 1         | 0.42%   |
| Finland       | 1         | 0.42%   |
| Czechia       | 1         | 0.42%   |
| Costa Rica    | 1         | 0.42%   |
| Chile         | 1         | 0.42%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Sao Paulo      | 3         | 1.27%   |
| London         | 3         | 1.27%   |
| Wroclaw        | 2         | 0.84%   |
| Vancouver      | 2         | 0.84%   |
| Tegucigalpa    | 2         | 0.84%   |
| Sydney         | 2         | 0.84%   |
| Stuttgart      | 2         | 0.84%   |
| Springfield    | 2         | 0.84%   |
| Seattle        | 2         | 0.84%   |
| Sanford        | 2         | 0.84%   |
| San Jose       | 2         | 0.84%   |
| Salvador       | 2         | 0.84%   |
| Portland       | 2         | 0.84%   |
| Phoenix        | 2         | 0.84%   |
| Philadelphia   | 2         | 0.84%   |
| Moscow         | 2         | 0.84%   |
| Melbourne      | 2         | 0.84%   |
| Lima           | 2         | 0.84%   |
| Las Vegas      | 2         | 0.84%   |
| Kuala Lumpur   | 2         | 0.84%   |
| Istanbul       | 2         | 0.84%   |
| Guangzhou      | 2         | 0.84%   |
| Gelsenkirchen  | 2         | 0.84%   |
| Fortaleza      | 2         | 0.84%   |
| Dammam         | 2         | 0.84%   |
| Cincinnati     | 2         | 0.84%   |
| Chattanooga    | 2         | 0.84%   |
| Bellevue       | 2         | 0.84%   |
| Yekaterinburg  | 1         | 0.42%   |
| Yaroslavl      | 1         | 0.42%   |
| Wilmington     | 1         | 0.42%   |
| Wiesbaden      | 1         | 0.42%   |
| Wiehl          | 1         | 0.42%   |
| Watsonville    | 1         | 0.42%   |
| Warsaw         | 1         | 0.42%   |
| Vũng Tàu     | 1         | 0.42%   |
| Volosovo       | 1         | 0.42%   |
| Virginia Beach | 1         | 0.42%   |
| Vincennes      | 1         | 0.42%   |
| Vila-seca      | 1         | 0.42%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 50        | 71     | 13.23%  |
| Seagate                      | 36        | 41     | 9.52%   |
| WDC                          | 35        | 45     | 9.26%   |
| Sandisk                      | 25        | 33     | 6.61%   |
| Kingston                     | 21        | 21     | 5.56%   |
| Unknown                      | 17        | 17     | 4.5%    |
| Micron/Crucial Technology    | 16        | 17     | 4.23%   |
| SK hynix                     | 15        | 15     | 3.97%   |
| Micron Technology            | 14        | 20     | 3.7%    |
| Toshiba                      | 13        | 16     | 3.44%   |
| Crucial                      | 12        | 16     | 3.17%   |
| Phison Electronics           | 11        | 12     | 2.91%   |
| Intel                        | 10        | 12     | 2.65%   |
| Realtek Semiconductor        | 9         | 9      | 2.38%   |
| MAXIO Technology (Hangzhou)  | 8         | 9      | 2.12%   |
| Kingston Technology Company  | 7         | 7      | 1.85%   |
| Shenzhen Longsys Electronics | 6         | 7      | 1.59%   |
| KIOXIA                       | 6         | 6      | 1.59%   |
| China                        | 5         | 5      | 1.32%   |
| ADATA Technology             | 5         | 7      | 1.32%   |
| A-DATA Technology            | 5         | 5      | 1.32%   |
| Silicon Motion               | 4         | 4      | 1.06%   |
| Hitachi                      | 4         | 4      | 1.06%   |
| HGST                         | 4         | 4      | 1.06%   |
| PNY                          | 3         | 3      | 0.79%   |
| Unknown                      | 3         | 3      | 0.79%   |
| Team                         | 2         | 2      | 0.53%   |
| SPCC                         | 2         | 2      | 0.53%   |
| Fanxiang                     | 2         | 2      | 0.53%   |
| Biwin Storage Technology     | 2         | 2      | 0.53%   |
| Apple                        | 2         | 2      | 0.53%   |
| AMD                          | 2         | 2      | 0.53%   |
| WDC PC S                     | 1         | 1      | 0.26%   |
| TO Exter                     | 1         | 1      | 0.26%   |
| Timetec                      | 1         | 1      | 0.26%   |
| SSSTC                        | 1         | 1      | 0.26%   |
| SSK                          | 1         | 1      | 0.26%   |
| SABRENT                      | 1         | 1      | 0.26%   |
| RZX                          | 1         | 1      | 0.26%   |
| Realtek                      | 1         | 1      | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB               | 15        | 3.76%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB                             | 13        | 3.26%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB              | 7         | 1.75%   |
| Seagate ST1000DM010-2EP102 1TB                                    | 5         | 1.25%   |
| Phison PS5013 E13 NVMe Controller 512GB                           | 5         | 1.25%   |
| Seagate ST1000LM035-1RK172 1TB                                    | 4         | 1%      |
| Micron 2400_MTFDKBK512QFM 512GB                                   | 4         | 1%      |
| Kingston Company SNV2S1000G 1TB                                   | 4         | 1%      |
| Unknown NVMe SSD Drive 512GB                                      | 3         | 0.75%   |
| Unknown MMC Card  512GB                                           | 3         | 0.75%   |
| Seagate ST500DM002-1BD142 500GB                                   | 3         | 0.75%   |
| Sandisk WD_BLACK SN770 2TB                                        | 3         | 0.75%   |
| Sandisk WD Blue SN550 NVMe SSD 256GB                              | 3         | 0.75%   |
| Samsung SSD 980 1TB                                               | 3         | 0.75%   |
| Samsung SSD 860 EVO 1TB                                           | 3         | 0.75%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB               | 3         | 0.75%   |
| Realtek RTS5763DL NVMe SSD Controller 256GB                       | 3         | 0.75%   |
| Phison E12 NVMe Controller 480GB                                  | 3         | 0.75%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 512GB                | 3         | 0.75%   |
| Kingston SA400S37480G 480GB SSD                                   | 3         | 0.75%   |
| Kingston SA400S37120G 120GB SSD                                   | 3         | 0.75%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 256GB | 3         | 0.75%   |
| Unknown                                                           | 3         | 0.75%   |
| WDC WDBNCE5000PNC 500GB SSD                                       | 2         | 0.5%    |
| WDC WD20EZRZ-00Z5HB0 2TB                                          | 2         | 0.5%    |
| WDC WD1600AAJS-00B4A0 160GB                                       | 2         | 0.5%    |
| WDC WD10JPVX-22JC3T0 1TB                                          | 2         | 0.5%    |
| WDC WD10EZEX-00BN5A0 1TB                                          | 2         | 0.5%    |
| Unknown SD/MMC/MS PRO 128GB                                       | 2         | 0.5%    |
| Unknown NVMe SSD Drive 2TB                                        | 2         | 0.5%    |
| Unknown MMC Card  64GB                                            | 2         | 0.5%    |
| Unknown MMC Card  1TB                                             | 2         | 0.5%    |
| Toshiba MQ04ABF100 1TB                                            | 2         | 0.5%    |
| SPCC Solid State Disk 1024GB                                      | 2         | 0.5%    |
| SK hynix HFM512GD3JX016N 512GB                                    | 2         | 0.5%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB             | 2         | 0.5%    |
| Shenzhen Longsys Lexar SSD NM7A1 2TB                              | 2         | 0.5%    |
| Seagate ST1000LX015-1U7172 1TB                                    | 2         | 0.5%    |
| Seagate ST1000LM048-2E7172 1TB                                    | 2         | 0.5%    |
| Sandisk WD_BLACK SN770 500GB                                      | 2         | 0.5%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 35        | 39     | 40.23%  |
| WDC                 | 29        | 33     | 33.33%  |
| Toshiba             | 9         | 12     | 10.34%  |
| Hitachi             | 4         | 4      | 4.6%    |
| HGST                | 4         | 4      | 4.6%    |
| Unknown             | 2         | 2      | 2.3%    |
| TO Exter            | 1         | 1      | 1.15%   |
| Samsung Electronics | 1         | 1      | 1.15%   |
| SABRENT             | 1         | 1      | 1.15%   |
| Apple               | 1         | 1      | 1.15%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 20        | 28     | 18.52%  |
| Kingston            | 14        | 14     | 12.96%  |
| Crucial             | 12        | 16     | 11.11%  |
| WDC                 | 9         | 12     | 8.33%   |
| SanDisk             | 9         | 14     | 8.33%   |
| Micron Technology   | 6         | 12     | 5.56%   |
| China               | 5         | 5      | 4.63%   |
| A-DATA Technology   | 5         | 5      | 4.63%   |
| Intel               | 4         | 5      | 3.7%    |
| PNY                 | 3         | 3      | 2.78%   |
| SPCC                | 2         | 2      | 1.85%   |
| SK hynix            | 2         | 2      | 1.85%   |
| Fanxiang            | 2         | 2      | 1.85%   |
| Team                | 1         | 1      | 0.93%   |
| SSSTC               | 1         | 1      | 0.93%   |
| Seagate             | 1         | 1      | 0.93%   |
| RZX                 | 1         | 1      | 0.93%   |
| NT-1TB              | 1         | 1      | 0.93%   |
| Netac               | 1         | 1      | 0.93%   |
| KingDian            | 1         | 5      | 0.93%   |
| Intenso             | 1         | 1      | 0.93%   |
| Hewlett-Packard     | 1         | 1      | 0.93%   |
| GOODRAM             | 1         | 1      | 0.93%   |
| GALAX               | 1         | 1      | 0.93%   |
| Corsair             | 1         | 1      | 0.93%   |
| ASMedia             | 1         | 1      | 0.93%   |
| Apple               | 1         | 1      | 0.93%   |
| AMD                 | 1         | 1      | 0.93%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 158       | 192    | 46.88%  |
| SSD     | 88        | 139    | 26.11%  |
| HDD     | 73        | 98     | 21.66%  |
| MMC     | 11        | 11     | 3.26%   |
| Unknown | 7         | 7      | 2.08%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 158       | 190    | 50.8%   |
| SATA | 129       | 232    | 41.48%  |
| SAS  | 13        | 14     | 4.18%   |
| MMC  | 11        | 11     | 3.54%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 77        | 132    | 46.67%  |
| 0.51-1.0   | 57        | 67     | 34.55%  |
| 1.01-2.0   | 21        | 24     | 12.73%  |
| 3.01-4.0   | 4         | 8      | 2.42%   |
| 4.01-10.0  | 3         | 3      | 1.82%   |
| 10.01-20.0 | 2         | 2      | 1.21%   |
| 2.01-3.0   | 1         | 1      | 0.61%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| More than 3000 | 101       | 42.62%  |
| 1001-2000      | 69        | 29.11%  |
| 501-1000       | 31        | 13.08%  |
| 2001-3000      | 18        | 7.59%   |
| 251-500        | 13        | 5.49%   |
| 101-250        | 2         | 0.84%   |
| 21-50          | 1         | 0.42%   |
| 1-20           | 1         | 0.42%   |
| 51-100         | 1         | 0.42%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 61        | 25.42%  |
| 501-1000       | 35        | 14.58%  |
| 51-100         | 32        | 13.33%  |
| 101-250        | 31        | 12.92%  |
| 251-500        | 28        | 11.67%  |
| 1001-2000      | 25        | 10.42%  |
| 2001-3000      | 13        | 5.42%   |
| More than 3000 | 12        | 5%      |
| 1-20           | 3         | 1.25%   |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 235       | 446    | 99.58%  |
| Works    | 1         | 1      | 0.42%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 105       | 29.25%  |
| AMD                          | 80        | 22.28%  |
| Samsung Electronics          | 34        | 9.47%   |
| SanDisk                      | 17        | 4.74%   |
| Micron/Crucial Technology    | 16        | 4.46%   |
| Kingston Technology Company  | 14        | 3.9%    |
| SK hynix                     | 13        | 3.62%   |
| Phison Electronics           | 11        | 3.06%   |
| Realtek Semiconductor        | 9         | 2.51%   |
| Micron Technology            | 8         | 2.23%   |
| MAXIO Technology (Hangzhou)  | 8         | 2.23%   |
| Shenzhen Longsys Electronics | 6         | 1.67%   |
| KIOXIA                       | 6         | 1.67%   |
| ADATA Technology             | 5         | 1.39%   |
| Toshiba America Info Systems | 4         | 1.11%   |
| Silicon Motion               | 4         | 1.11%   |
| ASMedia Technology           | 4         | 1.11%   |
| Biwin Storage Technology     | 3         | 0.84%   |
| Solidigm                     | 2         | 0.56%   |
| Marvell Technology Group     | 2         | 0.56%   |
| INNOGRIT                     | 2         | 0.56%   |
| VIA Technologies             | 1         | 0.28%   |
| TenaFe                       | 1         | 0.28%   |
| O2 Micro                     | 1         | 0.28%   |
| Lenovo                       | 1         | 0.28%   |
| Hosin Global Electronics     | 1         | 0.28%   |
| Unknown                      | 1         | 0.28%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 36        | 9.16%   |
| AMD 500 Series Chipset SATA Controller                                         | 26        | 6.62%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 16        | 4.07%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 15        | 3.82%   |
| AMD 400 Series Chipset SATA Controller                                         | 14        | 3.56%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 13        | 3.31%   |
| Intel Volume Management Device NVMe RAID Controller                            | 10        | 2.54%   |
| Intel SATA Controller [RAID mode]                                              | 8         | 2.04%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 7         | 1.78%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 7         | 1.78%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 7         | 1.78%   |
| AMD 600 Series Chipset SATA Controller                                         | 7         | 1.78%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 6         | 1.53%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 6         | 1.53%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 5         | 1.27%   |
| Shenzhen Longsys Lexar NM790 NVME SSD (DRAM-less)                              | 5         | 1.27%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 5         | 1.27%   |
| Micron 2400 NVMe SSD (DRAM-less)                                               | 5         | 1.27%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1602 (DRAM-less)                       | 5         | 1.27%   |
| Intel Comet Lake SATA AHCI Controller                                          | 5         | 1.27%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 5         | 1.27%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 4         | 1.02%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                           | 4         | 1.02%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 4         | 1.02%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 4         | 1.02%   |
| AMD 300 Series Chipset SATA Controller                                         | 4         | 1.02%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 3         | 0.76%   |
| SK hynix PC601 NVMe Solid State Drive                                          | 3         | 0.76%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 3         | 0.76%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 0.76%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                              | 3         | 0.76%   |
| Realtek RTS5762 NVMe SSD Controller                                            | 3         | 0.76%   |
| Phison E12 NVMe Controller                                                     | 3         | 0.76%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                       | 3         | 0.76%   |
| Kingston Company NV1 NVMe SSD [SM2263XT] (DRAM-less)                           | 3         | 0.76%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 3         | 0.76%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 3         | 0.76%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3         | 0.76%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 3         | 0.76%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 3         | 0.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 158       | 45.01%  |
| SATA | 157       | 44.73%  |
| RAID | 27        | 7.69%   |
| IDE  | 9         | 2.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| AMD    | 120       | 50.85%  |
| Intel  | 116       | 49.15%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor               | 9         | 3.8%    |
| AMD Ryzen 7 6800U with Radeon Graphics          | 7         | 2.95%   |
| AMD Ryzen 7 5800X 8-Core Processor              | 6         | 2.53%   |
| AMD Ryzen 5 5600X 6-Core Processor              | 6         | 2.53%   |
| AMD Ryzen 5 5600G with Radeon Graphics          | 5         | 2.11%   |
| AMD Ryzen Z1 Extreme                            | 4         | 1.69%   |
| AMD Ryzen 7 7840U w/ Radeon 780M Graphics       | 4         | 1.69%   |
| AMD Ryzen 7 7840HS w/ Radeon 780M Graphics      | 4         | 1.69%   |
| Intel Core i7-7700K CPU @ 4.20GHz               | 3         | 1.27%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz              | 3         | 1.27%   |
| Intel 11th Gen Core i5-11400H @ 2.70GHz         | 3         | 1.27%   |
| AMD Ryzen 9 7945HX with Radeon Graphics         | 3         | 1.27%   |
| AMD Ryzen 9 7940HS w/ Radeon 780M Graphics      | 3         | 1.27%   |
| AMD Ryzen 9 5950X 16-Core Processor             | 3         | 1.27%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx   | 3         | 1.27%   |
| AMD Ryzen 5 PRO 2400G with Radeon Vega Graphics | 3         | 1.27%   |
| AMD Ryzen 5 5600 6-Core Processor               | 3         | 1.27%   |
| AMD Ryzen 5 5500U with Radeon Graphics          | 3         | 1.27%   |
| AMD Ryzen 5 5500                                | 3         | 1.27%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 3         | 1.27%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 2         | 0.84%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz              | 2         | 0.84%   |
| Intel Core i5-8500 CPU @ 3.00GHz                | 2         | 0.84%   |
| Intel Core i5-7500 CPU @ 3.40GHz                | 2         | 0.84%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz              | 2         | 0.84%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 2         | 0.84%   |
| Intel Core i5-4570 CPU @ 3.20GHz                | 2         | 0.84%   |
| Intel Core i5-4440 CPU @ 3.10GHz                | 2         | 0.84%   |
| Intel Core i5-2400 CPU @ 3.10GHz                | 2         | 0.84%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz         | 2         | 0.84%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz         | 2         | 0.84%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 2         | 0.84%   |
| AMD Ryzen 9 5900X 12-Core Processor             | 2         | 0.84%   |
| AMD Ryzen 7 8840U w/ Radeon 780M Graphics       | 2         | 0.84%   |
| AMD Ryzen 7 7800X3D 8-Core Processor            | 2         | 0.84%   |
| AMD Ryzen 7 7700X 8-Core Processor              | 2         | 0.84%   |
| AMD Ryzen 7 5800X3D 8-Core Processor            | 2         | 0.84%   |
| AMD Ryzen 7 5800U with Radeon Graphics          | 2         | 0.84%   |
| AMD Ryzen 7 5700U with Radeon Graphics          | 2         | 0.84%   |
| AMD Ryzen 5 5560U with Radeon Graphics          | 2         | 0.84%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| AMD Ryzen 5       | 45        | 18.99%  |
| Intel Core i5     | 42        | 17.72%  |
| AMD Ryzen 7       | 40        | 16.88%  |
| Intel Core i7     | 29        | 12.24%  |
| Other             | 27        | 11.39%  |
| AMD Ryzen 9       | 17        | 7.17%   |
| Intel Core i3     | 10        | 4.22%   |
| Intel Xeon        | 7         | 2.95%   |
| AMD Ryzen 5 PRO   | 4         | 1.69%   |
| AMD FX            | 3         | 1.27%   |
| Intel Pentium     | 2         | 0.84%   |
| Intel Celeron     | 2         | 0.84%   |
| AMD PRO A10       | 2         | 0.84%   |
| AMD Athlon        | 2         | 0.84%   |
| Intel Core m3     | 1         | 0.42%   |
| Intel Core i9     | 1         | 0.42%   |
| Intel Core 2 Quad | 1         | 0.42%   |
| Intel Atom        | 1         | 0.42%   |
| AMD A10           | 1         | 0.42%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 79        | 33.33%  |
| 6      | 57        | 24.05%  |
| 8      | 51        | 21.52%  |
| 2      | 28        | 11.81%  |
| 16     | 8         | 3.38%   |
| 12     | 5         | 2.11%   |
| 24     | 3         | 1.27%   |
| 10     | 3         | 1.27%   |
| 14     | 2         | 0.84%   |
| 3      | 1         | 0.42%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 234       | 99.15%  |
| 2      | 2         | 0.85%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 195       | 82.63%  |
| 1      | 41        | 17.37%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 236       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 236       | 100%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Unknown     | 57        | 24.15%  |
| Zen 3       | 37        | 15.68%  |
| KabyLake    | 25        | 10.59%  |
| Haswell     | 25        | 10.59%  |
| Zen 2       | 13        | 5.51%   |
| CometLake   | 12        | 5.08%   |
| Zen+        | 11        | 4.66%   |
| Skylake     | 9         | 3.81%   |
| SandyBridge | 9         | 3.81%   |
| IvyBridge   | 9         | 3.81%   |
| Zen         | 8         | 3.39%   |
| TigerLake   | 7         | 2.97%   |
| Piledriver  | 4         | 1.69%   |
| Excavator   | 3         | 1.27%   |
| Broadwell   | 2         | 0.85%   |
| Silvermont  | 1         | 0.42%   |
| Penryn      | 1         | 0.42%   |
| Nehalem     | 1         | 0.42%   |
| Jaguar      | 1         | 0.42%   |
| Goldmont    | 1         | 0.42%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| AMD    | 135       | 45.92%  |
| Nvidia | 84        | 28.57%  |
| Intel  | 75        | 25.51%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| AMD Phoenix1                                                                | 15        | 4.95%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 10        | 3.3%    |
| AMD Rembrandt [Radeon 680M]                                                 | 9         | 2.97%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 9         | 2.97%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 7         | 2.31%   |
| AMD Raphael                                                                 | 7         | 2.31%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 7         | 2.31%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 7         | 2.31%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 6         | 1.98%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 6         | 1.98%   |
| AMD Navi 32 [Radeon RX 7700 XT / 7800 XT]                                   | 6         | 1.98%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 6         | 1.98%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 5         | 1.65%   |
| Intel HD Graphics 630                                                       | 5         | 1.65%   |
| Intel HD Graphics 530                                                       | 5         | 1.65%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5         | 1.65%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 5         | 1.65%   |
| AMD Polaris 20 XL [Radeon RX 580 2048SP]                                    | 5         | 1.65%   |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                                  | 5         | 1.65%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 5         | 1.65%   |
| AMD Lucienne                                                                | 5         | 1.65%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 4         | 1.32%   |
| Nvidia GM107M [GeForce GTX 950M]                                            | 4         | 1.32%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 4         | 1.32%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 4         | 1.32%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX/7900 GRE/7900M]                     | 4         | 1.32%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 4         | 1.32%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 3         | 0.99%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 3         | 0.99%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                          | 3         | 0.99%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 3         | 0.99%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 3         | 0.99%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3         | 0.99%   |
| AMD Navi 23 [Radeon RX 6650 XT / 6700S / 6800S]                             | 3         | 0.99%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 3         | 0.99%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 2         | 0.66%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 2         | 0.66%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 2         | 0.66%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2         | 0.66%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2         | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x AMD        | 112       | 47.26%  |
| 1 x Nvidia     | 39        | 16.46%  |
| Intel + Nvidia | 34        | 14.35%  |
| 1 x Intel      | 28        | 11.81%  |
| AMD + Nvidia   | 9         | 3.8%    |
| 2 x AMD        | 8         | 3.38%   |
| Intel + AMD    | 6         | 2.53%   |
| Other          | 1         | 0.42%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 180       | 76.27%  |
| Proprietary | 36        | 15.25%  |
| Unknown     | 20        | 8.47%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 233       | 98.73%  |
| 3.01-4.0   | 2         | 0.85%   |
| 8.01-16.0  | 1         | 0.42%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 26        | 11.87%  |
| BOE                  | 17        | 7.76%   |
| Chimei Innolux       | 15        | 6.85%   |
| LG Display           | 12        | 5.48%   |
| Goldstar             | 11        | 5.02%   |
| AU Optronics         | 11        | 5.02%   |
| Dell                 | 9         | 4.11%   |
| TMX                  | 6         | 2.74%   |
| Hewlett-Packard      | 6         | 2.74%   |
| Vizio                | 5         | 2.28%   |
| PANDA                | 5         | 2.28%   |
| AYANEO               | 5         | 2.28%   |
| Unknown (XXX)        | 4         | 1.83%   |
| Toshiba              | 4         | 1.83%   |
| Sony                 | 4         | 1.83%   |
| Sharp                | 4         | 1.83%   |
| Philips              | 4         | 1.83%   |
| Panasonic            | 4         | 1.83%   |
| BenQ                 | 4         | 1.83%   |
| AOC                  | 4         | 1.83%   |
| Acer                 | 4         | 1.83%   |
| SANYO                | 3         | 1.37%   |
| MSI                  | 3         | 1.37%   |
| Lenovo               | 3         | 1.37%   |
| Insignia             | 3         | 1.37%   |
| ASUSTek Computer     | 3         | 1.37%   |
| Ancor Communications | 3         | 1.37%   |
| MSF                  | 2         | 0.91%   |
| ITE                  | 2         | 0.91%   |
| Gigabyte Technology  | 2         | 0.91%   |
| DENON                | 2         | 0.91%   |
| Apple                | 2         | 0.91%   |
| Xiaomi               | 1         | 0.46%   |
| ViewSonic            | 1         | 0.46%   |
| VIE                  | 1         | 0.46%   |
| Valve                | 1         | 0.46%   |
| STD                  | 1         | 0.46%   |
| Sceptre Tech         | 1         | 0.46%   |
| SAC                  | 1         | 0.46%   |
| RTK                  | 1         | 0.46%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| TMX TL070FVXS01-0 TMX0002 1920x1080 160x100mm 7.4-inch                | 5         | 2.26%   |
| BOE FLQ8423-24L0 BOE1003 1600x2560 113x181mm 8.4-inch                 | 4         | 1.81%   |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1210x680mm 54.6-inch        | 3         | 1.36%   |
| Samsung Electronics LCD Monitor SAM0DF6 3840x2160 890x500mm 40.2-inch | 3         | 1.36%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 3         | 1.36%   |
| Toshiba TV TSB2017 3840x2160                                          | 2         | 0.9%    |
| SANYO TV SAN0206 1920x1080                                            | 2         | 0.9%    |
| Samsung Electronics LC27T55 SAM701F 1920x1080 609x349mm 27.6-inch     | 2         | 0.9%    |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                    | 2         | 0.9%    |
| MSF TV080WUM-NL0 MSF1003 1600x2560 113x181mm 8.4-inch                 | 2         | 0.9%    |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 677x290mm 29.0-inch              | 2         | 0.9%    |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch      | 2         | 0.9%    |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 2         | 0.9%    |
| AYANEO AYANEOWUXGA AYA0105 1200x1920                                  | 2         | 0.9%    |
| AYANEO AYANEOHD AYA6108 1080x1920                                     | 2         | 0.9%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.9%    |
| AOC U2790B AOC2790 3840x2160 597x336mm 27.0-inch                      | 2         | 0.9%    |
| Xiaomi Mi TV XMD00E2 1920x1080 950x540mm 43.0-inch                    | 1         | 0.45%   |
| Vizio V435-H1 VIZ1039 3840x2160 941x529mm 42.5-inch                   | 1         | 0.45%   |
| Vizio OLED55-H1 VIZ1040 3840x2160 1209x680mm 54.6-inch                | 1         | 0.45%   |
| Vizio D48-D0 VIZ1004 1920x1080 1070x610mm 48.5-inch                   | 1         | 0.45%   |
| Vizio D32x-D1 VIZ1005 1920x1080 698x392mm 31.5-inch                   | 1         | 0.45%   |
| Vizio D32f-E1 VIZ1027 1920x1080 698x392mm 31.5-inch                   | 1         | 0.45%   |
| ViewSonic VA2702w VSCE727 1920x1080 598x336mm 27.0-inch               | 1         | 0.45%   |
| VIE HORIZON Z24 VIE2380 1920x1080 527x296mm 23.8-inch                 | 1         | 0.45%   |
| Valve ANX7530 U VLV3003 800x1280 100x160mm 7.4-inch                   | 1         | 0.45%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch         | 1         | 0.45%   |
| Toshiba TV TSB0206 1920x1080 1600x1000mm 74.3-inch                    | 1         | 0.45%   |
| Toshiba TV TSB002F 3840x2160 1095x616mm 49.5-inch                     | 1         | 0.45%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch               | 1         | 0.45%   |
| STD Monitor STD2023 1920x1080 600x330mm 27.0-inch                     | 1         | 0.45%   |
| Sony TV SNYEE01 1920x1080                                             | 1         | 0.45%   |
| Sony TV SNY7502 1920x1080 1018x573mm 46.0-inch                        | 1         | 0.45%   |
| Sony TV SNY3002 1920x1080 886x498mm 40.0-inch                         | 1         | 0.45%   |
| Sony TV *30 SNY0406 3840x2160 1439x809mm 65.0-inch                    | 1         | 0.45%   |
| Sharp LQ173M1JW02 SHP14DB 1920x1080 382x215mm 17.3-inch               | 1         | 0.45%   |
| Sharp LCD Monitor SHP1515 1920x1200 336x210mm 15.6-inch               | 1         | 0.45%   |
| Sharp HDMI SHP101E 1920x1080 820x460mm 37.0-inch                      | 1         | 0.45%   |
| Sharp HDMI SHP0FE8 1920x1080 1152x648mm 52.0-inch                     | 1         | 0.45%   |
| Sceptre Tech Sceptre C35 SPT0DB7 3440x1440 819x346mm 35.0-inch        | 1         | 0.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 104       | 48.83%  |
| 3840x2160 (4K)     | 37        | 17.37%  |
| 2560x1440 (QHD)    | 14        | 6.57%   |
| 1366x768 (WXGA)    | 11        | 5.16%   |
| 1600x2560          | 7         | 3.29%   |
| 3440x1440          | 4         | 1.88%   |
| 2560x1080          | 4         | 1.88%   |
| 1600x900 (HD+)     | 4         | 1.88%   |
| 1200x1920          | 4         | 1.88%   |
| 1080x1920          | 4         | 1.88%   |
| 1920x540           | 3         | 1.41%   |
| 800x1280           | 2         | 0.94%   |
| 1920x1200 (WUXGA)  | 2         | 0.94%   |
| 1680x1050 (WSXGA+) | 2         | 0.94%   |
| 3840x2560          | 1         | 0.47%   |
| 3840x1600          | 1         | 0.47%   |
| 3840x1080          | 1         | 0.47%   |
| 2880x1800          | 1         | 0.47%   |
| 1600x1200          | 1         | 0.47%   |
| 1440x900 (WXGA+)   | 1         | 0.47%   |
| 1360x768           | 1         | 0.47%   |
| 1280x960           | 1         | 0.47%   |
| 1280x768           | 1         | 0.47%   |
| 1280x720 (HD)      | 1         | 0.47%   |
| Unknown            | 1         | 0.47%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 40        | 18.26%  |
| 27      | 29        | 13.24%  |
| Unknown | 15        | 6.85%   |
| 31      | 13        | 5.94%   |
| 84      | 11        | 5.02%   |
| 24      | 9         | 4.11%   |
| 23      | 8         | 3.65%   |
| 34      | 7         | 3.2%    |
| 17      | 7         | 3.2%    |
| 8       | 7         | 3.2%    |
| 72      | 6         | 2.74%   |
| 13      | 6         | 2.74%   |
| 7       | 6         | 2.74%   |
| 54      | 5         | 2.28%   |
| 21      | 5         | 2.28%   |
| 14      | 4         | 1.83%   |
| 48      | 3         | 1.37%   |
| 46      | 3         | 1.37%   |
| 20      | 3         | 1.37%   |
| 16      | 3         | 1.37%   |
| 65      | 2         | 0.91%   |
| 49      | 2         | 0.91%   |
| 40      | 2         | 0.91%   |
| 28      | 2         | 0.91%   |
| 22      | 2         | 0.91%   |
| 12      | 2         | 0.91%   |
| 74      | 1         | 0.46%   |
| 69      | 1         | 0.46%   |
| 64      | 1         | 0.46%   |
| 57      | 1         | 0.46%   |
| 52      | 1         | 0.46%   |
| 47      | 1         | 0.46%   |
| 43      | 1         | 0.46%   |
| 38      | 1         | 0.46%   |
| 37      | 1         | 0.46%   |
| 36      | 1         | 0.46%   |
| 35      | 1         | 0.46%   |
| 32      | 1         | 0.46%   |
| 29      | 1         | 0.46%   |
| 26      | 1         | 0.46%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 48        | 22.22%  |
| 501-600     | 43        | 19.91%  |
| 601-700     | 18        | 8.33%   |
| 1501-2000   | 18        | 8.33%   |
| 1001-1500   | 18        | 8.33%   |
| Unknown     | 15        | 6.94%   |
| 401-500     | 12        | 5.56%   |
| 101-200     | 12        | 5.56%   |
| 701-800     | 10        | 4.63%   |
| 351-400     | 10        | 4.63%   |
| 801-900     | 5         | 2.31%   |
| 201-300     | 5         | 2.31%   |
| 901-1000    | 1         | 0.46%   |
| 1-100       | 1         | 0.46%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 159       | 76.81%  |
| 16/10   | 13        | 6.28%   |
| 0.62    | 10        | 4.83%   |
| 21/9    | 9         | 4.35%   |
| 0.56    | 5         | 2.42%   |
| 32/9    | 3         | 1.45%   |
| 4/3     | 2         | 0.97%   |
| 0.58    | 2         | 0.97%   |
| 3/2     | 1         | 0.48%   |
| 1.96    | 1         | 0.48%   |
| 0.63    | 1         | 0.48%   |
| Unknown | 1         | 0.48%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 41        | 19.16%  |
| 301-350        | 31        | 14.49%  |
| More than 1000 | 30        | 14.02%  |
| 351-500        | 21        | 9.81%   |
| 201-250        | 20        | 9.35%   |
| Unknown        | 15        | 7.01%   |
| 1-40           | 13        | 6.07%   |
| 501-1000       | 13        | 6.07%   |
| 81-90          | 8         | 3.74%   |
| 121-130        | 7         | 3.27%   |
| 151-200        | 5         | 2.34%   |
| 71-80          | 3         | 1.4%    |
| 251-300        | 2         | 0.93%   |
| 111-120        | 2         | 0.93%   |
| 61-70          | 1         | 0.47%   |
| 51-60          | 1         | 0.47%   |
| 141-150        | 1         | 0.47%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 85        | 39.72%  |
| 121-160       | 54        | 25.23%  |
| 101-120       | 22        | 10.28%  |
| 1-50          | 15        | 7.01%   |
| Unknown       | 15        | 7.01%   |
| 161-240       | 13        | 6.07%   |
| More than 240 | 10        | 4.67%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 188       | 79.32%  |
| 0     | 24        | 10.13%  |
| 2     | 23        | 9.7%    |
| 3     | 2         | 0.84%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 148       | 39.47%  |
| Intel                           | 120       | 32%     |
| Qualcomm Atheros                | 29        | 7.73%   |
| MediaTek                        | 25        | 6.67%   |
| Broadcom                        | 10        | 2.67%   |
| TP-Link                         | 8         | 2.13%   |
| Microsoft                       | 6         | 1.6%    |
| ASIX Electronics                | 4         | 1.07%   |
| Broadcom Limited                | 3         | 0.8%    |
| Samsung Electronics             | 2         | 0.53%   |
| Ralink Technology               | 2         | 0.53%   |
| Ralink                          | 2         | 0.53%   |
| Qualcomm Atheros Communications | 2         | 0.53%   |
| Qualcomm                        | 2         | 0.53%   |
| Marvell Technology Group        | 2         | 0.53%   |
| DisplayLink                     | 2         | 0.53%   |
| Aquantia                        | 2         | 0.53%   |
| ZTE WCDMA Technologies MSM      | 1         | 0.27%   |
| Qualcomm Technologies           | 1         | 0.27%   |
| QNAP System                     | 1         | 0.27%   |
| OnePlus Technology (Shenzhen)   | 1         | 0.27%   |
| Google                          | 1         | 0.27%   |
| Edimax Technology               | 1         | 0.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 98        | 22.79%  |
| Realtek RTL8125 2.5GbE Controller                                      | 29        | 6.74%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 27        | 6.28%   |
| Intel Wi-Fi 6 AX200                                                    | 12        | 2.79%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 9         | 2.09%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 9         | 2.09%   |
| Intel I211 Gigabit Network Connection                                  | 9         | 2.09%   |
| Intel Ethernet Controller I225-V                                       | 9         | 2.09%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 8         | 1.86%   |
| Intel Ethernet Connection I217-LM                                      | 7         | 1.63%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 6         | 1.4%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 6         | 1.4%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 6         | 1.4%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 6         | 1.4%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 6         | 1.4%    |
| Intel Wi-Fi 6 AX201                                                    | 6         | 1.4%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 6         | 1.4%    |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller            | 5         | 1.16%   |
| Microsoft Xbox Wireless Adapter for Windows                            | 5         | 1.16%   |
| Intel Ethernet Connection (2) I219-V                                   | 5         | 1.16%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 4         | 0.93%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 4         | 0.93%   |
| Intel Wireless 8265 / 8275                                             | 4         | 0.93%   |
| Intel Wireless 7265                                                    | 4         | 0.93%   |
| Intel Wireless 3165                                                    | 4         | 0.93%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 4         | 0.93%   |
| Intel Ethernet Controller I226-V                                       | 4         | 0.93%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 4         | 0.93%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4         | 0.93%   |
| ASIX AX88179 Gigabit Ethernet                                          | 4         | 0.93%   |
| TP-Link Archer T4U ver.3                                               | 3         | 0.7%    |
| TP-Link 802.11ac NIC                                                   | 3         | 0.7%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 3         | 0.7%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 3         | 0.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 3         | 0.7%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 3         | 0.7%    |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 3         | 0.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                        | 3         | 0.7%    |
| Intel 82579V Gigabit Network Connection                                | 3         | 0.7%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 2         | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 88        | 44.22%  |
| Realtek Semiconductor           | 34        | 17.09%  |
| Qualcomm Atheros                | 24        | 12.06%  |
| MediaTek                        | 22        | 11.06%  |
| TP-Link                         | 8         | 4.02%   |
| Microsoft                       | 6         | 3.02%   |
| Broadcom                        | 6         | 3.02%   |
| Ralink Technology               | 2         | 1.01%   |
| Ralink                          | 2         | 1.01%   |
| Qualcomm Atheros Communications | 2         | 1.01%   |
| Qualcomm Technologies           | 1         | 0.5%    |
| Qualcomm                        | 1         | 0.5%    |
| Marvell Technology Group        | 1         | 0.5%    |
| Edimax Technology               | 1         | 0.5%    |
| Broadcom Limited                | 1         | 0.5%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]     | 27        | 13.24%  |
| Intel Wi-Fi 6 AX200                                           | 12        | 5.88%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 9         | 4.41%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 8         | 3.92%   |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 6         | 2.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 6         | 2.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 6         | 2.94%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 6         | 2.94%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 6         | 2.94%   |
| Intel Wi-Fi 6 AX201                                           | 6         | 2.94%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 6         | 2.94%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller   | 5         | 2.45%   |
| Microsoft Xbox Wireless Adapter for Windows                   | 5         | 2.45%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller   | 4         | 1.96%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 4         | 1.96%   |
| Intel Wireless 8265 / 8275                                    | 4         | 1.96%   |
| Intel Wireless 7265                                           | 4         | 1.96%   |
| Intel Wireless 3165                                           | 4         | 1.96%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 4         | 1.96%   |
| Intel Comet Lake PCH CNVi WiFi                                | 4         | 1.96%   |
| TP-Link Archer T4U ver.3                                      | 3         | 1.47%   |
| TP-Link 802.11ac NIC                                          | 3         | 1.47%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 3         | 1.47%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter              | 3         | 1.47%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]       | 3         | 1.47%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 3         | 1.47%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 2         | 0.98%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                     | 2         | 0.98%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 2         | 0.98%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 2         | 0.98%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                   | 2         | 0.98%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter  | 2         | 0.98%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                        | 1         | 0.49%   |
| TP-Link 802.11ac WLAN Adapter                                 | 1         | 0.49%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 1         | 0.49%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                    | 1         | 0.49%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 1         | 0.49%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter               | 1         | 0.49%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                        | 1         | 0.49%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter               | 1         | 0.49%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 139       | 63.18%  |
| Intel                    | 52        | 23.64%  |
| Qualcomm Atheros         | 6         | 2.73%   |
| Broadcom                 | 5         | 2.27%   |
| ASIX Electronics         | 4         | 1.82%   |
| MediaTek                 | 3         | 1.36%   |
| DisplayLink              | 2         | 0.91%   |
| Broadcom Limited         | 2         | 0.91%   |
| Aquantia                 | 2         | 0.91%   |
| Samsung Electronics      | 1         | 0.45%   |
| Qualcomm                 | 1         | 0.45%   |
| QNAP System              | 1         | 0.45%   |
| Marvell Technology Group | 1         | 0.45%   |
| Google                   | 1         | 0.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 98        | 43.95%  |
| Realtek RTL8125 2.5GbE Controller                                      | 29        | 13%     |
| Intel I211 Gigabit Network Connection                                  | 9         | 4.04%   |
| Intel Ethernet Controller I225-V                                       | 9         | 4.04%   |
| Intel Ethernet Connection I217-LM                                      | 7         | 3.14%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 6         | 2.69%   |
| Intel Ethernet Connection (2) I219-V                                   | 5         | 2.24%   |
| Intel Ethernet Controller I226-V                                       | 4         | 1.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4         | 1.79%   |
| ASIX AX88179 Gigabit Ethernet                                          | 4         | 1.79%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 3         | 1.35%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 3         | 1.35%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 3         | 1.35%   |
| Intel 82579V Gigabit Network Connection                                | 3         | 1.35%   |
| Realtek PCIe GbE Family Controller                                     | 2         | 0.9%    |
| Intel Ethernet Connection (5) I219-LM                                  | 2         | 0.9%    |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 0.9%    |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                       | 2         | 0.9%    |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                | 2         | 0.9%    |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 0.45%   |
| Realtek USB 10/100/1G/2.5G LAN                                         | 1         | 0.45%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 1         | 0.45%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 0.45%   |
| Qualcomm MDM9207-MTP _SN:01E0290C                                      | 1         | 0.45%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 0.45%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 0.45%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 0.45%   |
| QNAP System Pacific                                                    | 1         | 0.45%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                | 1         | 0.45%   |
| Intel I210 Gigabit Network Connection                                  | 1         | 0.45%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 0.45%   |
| Intel Ethernet Connection I217-V                                       | 1         | 0.45%   |
| Intel Ethernet Connection (2) I218-LM                                  | 1         | 0.45%   |
| Intel Ethernet Connection (14) I219-V                                  | 1         | 0.45%   |
| Intel Ethernet Connection (12) I219-V                                  | 1         | 0.45%   |
| Intel Ethernet Connection (11) I219-V                                  | 1         | 0.45%   |
| Intel Ethernet Connection (11) I219-LM                                 | 1         | 0.45%   |
| Google Pixel 6                                                         | 1         | 0.45%   |
| DisplayLink HP Port Replicator (Composite Device)                      | 1         | 0.45%   |
| DisplayLink Dell Universal Dock D6000                                  | 1         | 0.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 206       | 52.15%  |
| WiFi     | 186       | 47.09%  |
| Modem    | 2         | 0.51%   |
| Unknown  | 1         | 0.25%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 142       | 58.92%  |
| Ethernet | 99        | 41.08%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 126       | 53.39%  |
| 1     | 101       | 42.8%   |
| 3     | 9         | 3.81%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 155       | 65.4%   |
| Yes  | 82        | 34.6%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 84        | 46.93%  |
| Realtek Semiconductor           | 16        | 8.94%   |
| IMC Networks                    | 16        | 8.94%   |
| Cambridge Silicon Radio         | 14        | 7.82%   |
| MediaTek                        | 12        | 6.7%    |
| Qualcomm Atheros Communications | 9         | 5.03%   |
| Foxconn / Hon Hai               | 8         | 4.47%   |
| Lite-On Technology              | 6         | 3.35%   |
| Apple                           | 5         | 2.79%   |
| ASUSTek Computer                | 3         | 1.68%   |
| TP-Link                         | 2         | 1.12%   |
| Realtek                         | 2         | 1.12%   |
| Dynex                           | 1         | 0.56%   |
| Actions                         | 1         | 0.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel AX210 Bluetooth                                    | 26        | 14.44%  |
| Intel AX201 Bluetooth                                    | 16        | 8.89%   |
| Realtek Bluetooth Radio                                  | 14        | 7.78%   |
| Intel Bluetooth wireless interface                       | 14        | 7.78%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 14        | 7.78%   |
| MediaTek Wireless_Device                                 | 12        | 6.67%   |
| Intel AX200 Bluetooth                                    | 11        | 6.11%   |
| IMC Networks Bluetooth Radio                             | 9         | 5%      |
| Intel Wireless-AC 3168 Bluetooth                         | 6         | 3.33%   |
| Foxconn / Hon Hai Wireless_Device                        | 6         | 3.33%   |
| IMC Networks Wireless_Device                             | 5         | 2.78%   |
| Qualcomm Atheros  Bluetooth Device                       | 4         | 2.22%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 4         | 2.22%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                   | 3         | 1.67%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth               | 3         | 1.67%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 3         | 1.67%   |
| Intel AX211 Bluetooth                                    | 3         | 1.67%   |
| Apple Bluetooth Host Controller                          | 3         | 1.67%   |
| TP-Link TP-Link Bluetooth USB Adapter                    | 2         | 1.11%   |
| Realtek Bluetooth Radio                                  | 2         | 1.11%   |
| Lite-On Bluetooth Device                                 | 2         | 1.11%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 2         | 1.11%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                  | 1         | 0.56%   |
| Realtek  Bluetooth 4.2 Adapter                           | 1         | 0.56%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                    | 1         | 0.56%   |
| Qualcomm Atheros AR3012 Bluetooth                        | 1         | 0.56%   |
| Lite-On Wireless_Device                                  | 1         | 0.56%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 1         | 0.56%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter         | 1         | 0.56%   |
| IMC Networks Bluetooth Device                            | 1         | 0.56%   |
| IMC Networks Atheros AR3012 Bluetooth                    | 1         | 0.56%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth          | 1         | 0.56%   |
| Foxconn / Hon Hai Bluetooth Device                       | 1         | 0.56%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 1         | 0.56%   |
| ASUS Qualcomm Bluetooth 4.1                              | 1         | 0.56%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                     | 1         | 0.56%   |
| Apple Bluetooth USB Host Controller                      | 1         | 0.56%   |
| Actions general adapter                                  | 1         | 0.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| AMD                      | 148       | 39.36%  |
| Intel                    | 112       | 29.79%  |
| Nvidia                   | 66        | 17.55%  |
| Sony                     | 8         | 2.13%   |
| Logitech                 | 7         | 1.86%   |
| Kingston Technology      | 6         | 1.6%    |
| C-Media Electronics      | 5         | 1.33%   |
| Hewlett-Packard          | 3         | 0.8%    |
| SteelSeries ApS          | 2         | 0.53%   |
| Realtek Semiconductor    | 2         | 0.53%   |
| Razer USA                | 2         | 0.53%   |
| ASUSTek Computer         | 2         | 0.53%   |
| Astro Gaming             | 2         | 0.53%   |
| Texas Instruments        | 1         | 0.27%   |
| Micro Star International | 1         | 0.27%   |
| JMTek                    | 1         | 0.27%   |
| Jieli Technology         | 1         | 0.27%   |
| Google                   | 1         | 0.27%   |
| Generalplus Technology   | 1         | 0.27%   |
| Focusrite-Novation       | 1         | 0.27%   |
| Creative Labs            | 1         | 0.27%   |
| Comtrue                  | 1         | 0.27%   |
| Blue Microphones         | 1         | 0.27%   |
| Arturia                  | 1         | 0.27%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 68        | 13.49%  |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 35        | 6.94%   |
| AMD Starship/Matisse HD Audio Controller                                   | 33        | 6.55%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 24        | 4.76%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 20        | 3.97%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 19        | 3.77%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 14        | 2.78%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 14        | 2.78%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 12        | 2.38%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 10        | 1.98%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 9         | 1.79%   |
| AMD Navi 10 HDMI Audio                                                     | 9         | 1.79%   |
| Intel Cannon Lake PCH cAVS                                                 | 8         | 1.59%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 7         | 1.39%   |
| Nvidia GA104 High Definition Audio Controller                              | 7         | 1.39%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 7         | 1.39%   |
| Intel Sunrise Point-LP HD Audio                                            | 7         | 1.39%   |
| Intel Comet Lake PCH cAVS                                                  | 7         | 1.39%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7         | 1.39%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 7         | 1.39%   |
| Nvidia GA106 High Definition Audio Controller                              | 6         | 1.19%   |
| Sony DualShock 4 [CUH-ZCT2x]                                               | 5         | 0.99%   |
| Nvidia TU106 High Definition Audio Controller                              | 5         | 0.99%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5         | 0.99%   |
| Nvidia GP104 High Definition Audio Controller                              | 5         | 0.99%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 5         | 0.99%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 5         | 0.99%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 5         | 0.99%   |
| Nvidia TU116 High Definition Audio Controller                              | 4         | 0.79%   |
| Nvidia TU104 HD Audio Controller                                           | 4         | 0.79%   |
| Nvidia GA107 High Definition Audio Controller                              | 4         | 0.79%   |
| Nvidia GA102 High Definition Audio Controller                              | 4         | 0.79%   |
| Intel CM238 HD Audio Controller                                            | 4         | 0.79%   |
| Intel 200 Series PCH HD Audio                                              | 4         | 0.79%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4         | 0.79%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 3         | 0.6%    |
| Intel Raptor Lake High Definition Audio Controller                         | 3         | 0.6%    |
| Intel Alder Lake-S HD Audio Controller                                     | 3         | 0.6%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 3         | 0.6%    |
| AMD Kabini HDMI/DP Audio                                                   | 3         | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 1         | 25%     |
| Samsung Electronics | 1         | 25%     |
| G.Skill             | 1         | 25%     |
| ChangXin Memory     | 1         | 25%     |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM H9HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s | 1         | 20%     |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 20%     |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 20%     |
| G.Skill RAM F5-6800J3445G32G 32GB DIMM DDR5 4800MT/s             | 1         | 20%     |
| ChangXin Memory RAM DB4ABAM-MK 1GB Row Of Chips LPDDR4 3733MT/s  | 1         | 20%     |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| LPDDR4 | 2         | 50%     |
| DDR5   | 1         | 25%     |
| DDR3   | 1         | 25%     |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Row Of Chips | 2         | 50%     |
| SODIMM       | 1         | 25%     |
| DIMM         | 1         | 25%     |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 32768 | 1         | 25%     |
| 8192  | 1         | 25%     |
| 4096  | 1         | 25%     |
| 1024  | 1         | 25%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 4800  | 1         | 25%     |
| 4267  | 1         | 25%     |
| 3733  | 1         | 25%     |
| 1600  | 1         | 25%     |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Brother Industries | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                      | Computers | Percent |
|----------------------------|-----------|---------|
| Brother HL-L3220CDW series | 1         | 100%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo] | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 14        | 19.44%  |
| Microdia                               | 10        | 13.89%  |
| IMC Networks                           | 9         | 12.5%   |
| Sunplus Innovation Technology          | 7         | 9.72%   |
| Logitech                               | 6         | 8.33%   |
| Quanta                                 | 4         | 5.56%   |
| Realtek Semiconductor                  | 3         | 4.17%   |
| Apple                                  | 3         | 4.17%   |
| Sonix Technology                       | 2         | 2.78%   |
| Bison Electronics                      | 2         | 2.78%   |
| Acer                                   | 2         | 2.78%   |
| Syntek                                 | 1         | 1.39%   |
| Suyin                                  | 1         | 1.39%   |
| Silicon Motion                         | 1         | 1.39%   |
| SHENZHEN EMEET TECHNOLOGY              | 1         | 1.39%   |
| Samsung Electronics                    | 1         | 1.39%   |
| MacroSilicon                           | 1         | 1.39%   |
| Linux Foundation                       | 1         | 1.39%   |
| Huawei Technologies                    | 1         | 1.39%   |
| Goodong                                | 1         | 1.39%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.39%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam       | 4         | 5.56%   |
| Sunplus HD WebCam                       | 3         | 4.17%   |
| IMC Networks Integrated Camera          | 3         | 4.17%   |
| Sonix USB2.0 HD UVC WebCam              | 2         | 2.78%   |
| Quanta HP Wide Vision HD Camera         | 2         | 2.78%   |
| Microdia Integrated_Webcam_HD           | 2         | 2.78%   |
| Microdia Integrated_Webcam_FHD          | 2         | 2.78%   |
| Logitech Webcam C930e                   | 2         | 2.78%   |
| IMC Networks ov9734_azurewave_camera    | 2         | 2.78%   |
| Chicony Integrated Camera               | 2         | 2.78%   |
| Chicony HD WebCam                       | 2         | 2.78%   |
| Chicony HD User Facing                  | 2         | 2.78%   |
| Syntek USB2.0 Camera                    | 1         | 1.39%   |
| Suyin HP Truevision HD                  | 1         | 1.39%   |
| Sunplus Integrated_Webcam_HD            | 1         | 1.39%   |
| Sunplus Integrated_Webcam_FHD           | 1         | 1.39%   |
| Sunplus HD 720P webcam                  | 1         | 1.39%   |
| Sunplus ASUS Webcam                     | 1         | 1.39%   |
| Silicon Motion 300k Pixel Camera        | 1         | 1.39%   |
| SHENZHEN EMEET TECHNOLOGY eMeet Nova    | 1         | 1.39%   |
| Samsung Galaxy series, misc. (MTP mode) | 1         | 1.39%   |
| Realtek Integrated_Webcam_HD            | 1         | 1.39%   |
| Realtek Integrated_Webcam_FHD           | 1         | 1.39%   |
| Realtek Integrated Webcam               | 1         | 1.39%   |
| Quanta HP HD Camera                     | 1         | 1.39%   |
| Quanta HD User Facing                   | 1         | 1.39%   |
| Microdia Webcam Vitade AF               | 1         | 1.39%   |
| Microdia USB Camera                     | 1         | 1.39%   |
| Microdia USB 2.0 Camera                 | 1         | 1.39%   |
| Microdia Laptop_Integrated_Webcam_HD    | 1         | 1.39%   |
| Microdia HP Webcam                      | 1         | 1.39%   |
| Microdia Camera                         | 1         | 1.39%   |
| MacroSilicon USB Video                  | 1         | 1.39%   |
| Logitech Webcam C270                    | 1         | 1.39%   |
| Logitech Webcam C200                    | 1         | 1.39%   |
| Logitech Logi Webcam C920e              | 1         | 1.39%   |
| Logitech HD Pro Webcam C920             | 1         | 1.39%   |
| Linux Foundation EEM Gadget             | 1         | 1.39%   |
| Huawei HiCamera                         | 1         | 1.39%   |
| Goodong USB Camera                      | 1         | 1.39%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 3         | 30%     |
| Synaptics                  | 2         | 20%     |
| LighTuning Technology      | 2         | 20%     |
| FocalTech                  | 1         | 10%     |
| Focal-systems.Corp         | 1         | 10%     |
| AuthenTec                  | 1         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                      | 3         | 30%     |
| Synaptics WBDI                                           | 1         | 10%     |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 10%     |
| LighTuning Fingerprint Sensor                            | 1         | 10%     |
| LighTuning ES603 Swipe Fingerprint Sensor                | 1         | 10%     |
| FocalTech FocalTech Fingerprint Device                   | 1         | 10%     |
| Focal-systems.Corp FT9201Fingerprint.Ì                | 1         | 10%     |
| AuthenTec AES1660 Fingerprint Sensor                     | 1         | 10%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 3         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model          | Computers | Percent |
|----------------|-----------|---------|
| Broadcom 58200 | 2         | 66.67%  |
| Broadcom 5880  | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 143       | 60.59%  |
| 1     | 85        | 36.02%  |
| 2     | 8         | 3.39%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 51        | 50%     |
| Multimedia controller | 10        | 9.8%    |
| Fingerprint reader    | 10        | 9.8%    |
| Net/wireless          | 9         | 8.82%   |
| Network               | 8         | 7.84%   |
| Net/ethernet          | 7         | 6.86%   |
| Chipcard              | 3         | 2.94%   |
| Unassigned class      | 1         | 0.98%   |
| Storage/raid          | 1         | 0.98%   |
| Storage/nvme          | 1         | 0.98%   |
| Bluetooth             | 1         | 0.98%   |

