Linux in Germany - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Germany.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Germany/Desktop/README.md) and [notebooks](/Location/Germany/Notebook/README.md).

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

Total: 34175

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [700ae279ed](https://linux-hardware.org/?probe=700ae279ed) | Jan 02, 2024 |
| ASRock        | J5005-ITX                   | Desktop     | [5373e7f16c](https://linux-hardware.org/?probe=5373e7f16c) | Jan 02, 2024 |
| Lenovo        | ThinkPad P16s Gen 1 21BT... | Notebook    | [e15430e53e](https://linux-hardware.org/?probe=e15430e53e) | Jan 02, 2024 |
| Dell          | 0XJ8C4 A00                  | Desktop     | [e902f5396d](https://linux-hardware.org/?probe=e902f5396d) | Jan 02, 2024 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [502ebc99c3](https://linux-hardware.org/?probe=502ebc99c3) | Jan 02, 2024 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [435dc251c1](https://linux-hardware.org/?probe=435dc251c1) | Jan 02, 2024 |
| Fujitsu       | LIFEBOOK E780               | Notebook    | [6606e3d150](https://linux-hardware.org/?probe=6606e3d150) | Jan 01, 2024 |
| TUXEDO        | N8xxEZ                      | Notebook    | [4eb785f281](https://linux-hardware.org/?probe=4eb785f281) | Jan 01, 2024 |
| Gigabyte      | X670 GAMING X AX            | Desktop     | [6b4b87c927](https://linux-hardware.org/?probe=6b4b87c927) | Jan 01, 2024 |
| MSI           | N6105                       | Notebook    | [0b934bf922](https://linux-hardware.org/?probe=0b934bf922) | Jan 01, 2024 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [8dab3905db](https://linux-hardware.org/?probe=8dab3905db) | Jan 01, 2024 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | Notebook    | [8a14ad7cc9](https://linux-hardware.org/?probe=8a14ad7cc9) | Jan 01, 2024 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | Notebook    | [a2acc5bb5f](https://linux-hardware.org/?probe=a2acc5bb5f) | Jan 01, 2024 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [148f8c250f](https://linux-hardware.org/?probe=148f8c250f) | Jan 01, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [685d971973](https://linux-hardware.org/?probe=685d971973) | Jan 01, 2024 |
| Lenovo        | ThinkPad T460 20FMS2291P    | Notebook    | [1a86f2a3d4](https://linux-hardware.org/?probe=1a86f2a3d4) | Jan 01, 2024 |
| ASRock        | B550M-ITX/ac                | Desktop     | [2ae0bbe734](https://linux-hardware.org/?probe=2ae0bbe734) | Jan 01, 2024 |
| MSI           | N6105                       | Notebook    | [24f1343e04](https://linux-hardware.org/?probe=24f1343e04) | Jan 01, 2024 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [7cb99217f7](https://linux-hardware.org/?probe=7cb99217f7) | Jan 01, 2024 |
| Medion        | H110H4-EM                   | Desktop     | [da3367c80e](https://linux-hardware.org/?probe=da3367c80e) | Jan 01, 2024 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [1934632c28](https://linux-hardware.org/?probe=1934632c28) | Jan 01, 2024 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [7df50c6495](https://linux-hardware.org/?probe=7df50c6495) | Jan 01, 2024 |
| TUXEDO        | Polaris AMD Gen5            | Notebook    | [aa5447c317](https://linux-hardware.org/?probe=aa5447c317) | Jan 01, 2024 |
| Packard Be... | EasyNote LJ65               | Notebook    | [52bbda495f](https://linux-hardware.org/?probe=52bbda495f) | Jan 01, 2024 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | Notebook    | [a70caacf5a](https://linux-hardware.org/?probe=a70caacf5a) | Jan 01, 2024 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [cd5e5dff22](https://linux-hardware.org/?probe=cd5e5dff22) | Jan 01, 2024 |
| Microsoft     | Surface Pro 8               | Tablet      | [eca0b8e39a](https://linux-hardware.org/?probe=eca0b8e39a) | Jan 01, 2024 |
| Sony          | VPCSB1V9E                   | Notebook    | [31cb181036](https://linux-hardware.org/?probe=31cb181036) | Jan 01, 2024 |
| Valve         | Jupiter                     | Notebook    | [e714aab1f3](https://linux-hardware.org/?probe=e714aab1f3) | Jan 01, 2024 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [8fdfce9fb8](https://linux-hardware.org/?probe=8fdfce9fb8) | Dec 31, 2023 |
| Dell          | Latitude E6220              | Notebook    | [11568cda87](https://linux-hardware.org/?probe=11568cda87) | Dec 31, 2023 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [b3568ff9cb](https://linux-hardware.org/?probe=b3568ff9cb) | Dec 31, 2023 |
| ASRock        | B650E PG Riptide WiFi       | Desktop     | [9c99c1bf71](https://linux-hardware.org/?probe=9c99c1bf71) | Dec 31, 2023 |
| Fujitsu Si... | LIFEBOOK E8410              | Notebook    | [eeba7c76f2](https://linux-hardware.org/?probe=eeba7c76f2) | Dec 31, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [109efb840b](https://linux-hardware.org/?probe=109efb840b) | Dec 31, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [0f440edfb5](https://linux-hardware.org/?probe=0f440edfb5) | Dec 31, 2023 |
| ASUSTek       | ROG Ally RC71L_RC71L        | Tablet      | [d492f561d9](https://linux-hardware.org/?probe=d492f561d9) | Dec 31, 2023 |
| HP            | 84F5                        | Mini pc     | [b4c20746bb](https://linux-hardware.org/?probe=b4c20746bb) | Dec 31, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [e1c9fdb53b](https://linux-hardware.org/?probe=e1c9fdb53b) | Dec 31, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [bb0f439fbe](https://linux-hardware.org/?probe=bb0f439fbe) | Dec 31, 2023 |
| HP            | 872E                        | Mini pc     | [5791679f5b](https://linux-hardware.org/?probe=5791679f5b) | Dec 31, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [aa028d5af2](https://linux-hardware.org/?probe=aa028d5af2) | Dec 31, 2023 |
| Intel         | NUC7JYB M37329-600          | Mini pc     | [7237a0a423](https://linux-hardware.org/?probe=7237a0a423) | Dec 31, 2023 |
| Gigabyte      | GA-MA790GPT-UD3H            | Desktop     | [0ff4f2cb79](https://linux-hardware.org/?probe=0ff4f2cb79) | Dec 31, 2023 |
| ZOTAC         | NM10                        | Desktop     | [c0f4135bd0](https://linux-hardware.org/?probe=c0f4135bd0) | Dec 31, 2023 |
| Valve         | Jupiter                     | Notebook    | [ca7a54408f](https://linux-hardware.org/?probe=ca7a54408f) | Dec 31, 2023 |
| HP            | 3047h                       | Desktop     | [b7a000586f](https://linux-hardware.org/?probe=b7a000586f) | Dec 31, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [edbe61f4fa](https://linux-hardware.org/?probe=edbe61f4fa) | Dec 31, 2023 |
| Shenzhen M... | F7BSC                       | Mini pc     | [0961855530](https://linux-hardware.org/?probe=0961855530) | Dec 31, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [f70bdb7fa5](https://linux-hardware.org/?probe=f70bdb7fa5) | Dec 31, 2023 |
| Lenovo        | ThinkPad T480s 20L8S35G0... | Notebook    | [f2357e961c](https://linux-hardware.org/?probe=f2357e961c) | Dec 31, 2023 |
| HC Technol... | HCAR5000-MI2                | Desktop     | [907ca49963](https://linux-hardware.org/?probe=907ca49963) | Dec 31, 2023 |
| Lenovo        | ThinkPad T430 2349SVA       | Notebook    | [1a897f9fbd](https://linux-hardware.org/?probe=1a897f9fbd) | Dec 31, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | Desktop     | [5d368c5304](https://linux-hardware.org/?probe=5d368c5304) | Dec 31, 2023 |
| Valve         | Jupiter                     | Notebook    | [c459051f01](https://linux-hardware.org/?probe=c459051f01) | Dec 31, 2023 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [eb25c26beb](https://linux-hardware.org/?probe=eb25c26beb) | Dec 30, 2023 |
| Dell          | 0GN6JF A01                  | Desktop     | [19456ad0cb](https://linux-hardware.org/?probe=19456ad0cb) | Dec 30, 2023 |
| Dell          | Inspiron 3505               | Notebook    | [bbcd14000a](https://linux-hardware.org/?probe=bbcd14000a) | Dec 30, 2023 |
| Dell          | Latitude 5540               | Notebook    | [604aab0481](https://linux-hardware.org/?probe=604aab0481) | Dec 30, 2023 |
| ASUSTek       | P11C-I Series               | Desktop     | [b38bcf215d](https://linux-hardware.org/?probe=b38bcf215d) | Dec 30, 2023 |
| Dell          | 0GN6JF A01                  | Desktop     | [fcf352f5e9](https://linux-hardware.org/?probe=fcf352f5e9) | Dec 30, 2023 |
| ASRockRack    | E3C256D4U-2L2T              | Server      | [b599abfcfe](https://linux-hardware.org/?probe=b599abfcfe) | Dec 30, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [0b8c1c9e17](https://linux-hardware.org/?probe=0b8c1c9e17) | Dec 30, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [7cd1d9d16c](https://linux-hardware.org/?probe=7cd1d9d16c) | Dec 30, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [ca0a0fe5cf](https://linux-hardware.org/?probe=ca0a0fe5cf) | Dec 30, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [5fa6e9f755](https://linux-hardware.org/?probe=5fa6e9f755) | Dec 30, 2023 |
| Medion        | Akoya E6240T                | Notebook    | [f23e5a29d5](https://linux-hardware.org/?probe=f23e5a29d5) | Dec 30, 2023 |
| ASRock        | H170M Pro4                  | Desktop     | [27e24a6ef3](https://linux-hardware.org/?probe=27e24a6ef3) | Dec 30, 2023 |
| MSI           | B350 KRAIT GAMING           | Desktop     | [a4582db0da](https://linux-hardware.org/?probe=a4582db0da) | Dec 30, 2023 |
| ASUSTek       | TUF Gaming H670-PRO WIFI... | Desktop     | [3b26c92d22](https://linux-hardware.org/?probe=3b26c92d22) | Dec 30, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [2f69bdfbc7](https://linux-hardware.org/?probe=2f69bdfbc7) | Dec 30, 2023 |
| MSI           | MS-B9311                    | Desktop     | [47bab5481d](https://linux-hardware.org/?probe=47bab5481d) | Dec 30, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [d3bb35f033](https://linux-hardware.org/?probe=d3bb35f033) | Dec 30, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [b94c50cb10](https://linux-hardware.org/?probe=b94c50cb10) | Dec 30, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [52ed3f7e82](https://linux-hardware.org/?probe=52ed3f7e82) | Dec 30, 2023 |
| Medion        | DEFENDER E10                | Notebook    | [811e5b34cd](https://linux-hardware.org/?probe=811e5b34cd) | Dec 30, 2023 |
| Medion        | DEFENDER E10                | Notebook    | [2e99d46be8](https://linux-hardware.org/?probe=2e99d46be8) | Dec 30, 2023 |
| Lenovo        | ThinkPad E16 Gen 1 21JNC... | Notebook    | [6410cef098](https://linux-hardware.org/?probe=6410cef098) | Dec 30, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [e14a6e4044](https://linux-hardware.org/?probe=e14a6e4044) | Dec 30, 2023 |
| Samsung       | 730QFG                      | Convertible | [3cb8ce6daf](https://linux-hardware.org/?probe=3cb8ce6daf) | Dec 30, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [80604ec459](https://linux-hardware.org/?probe=80604ec459) | Dec 30, 2023 |
| HC Technol... | HCAR5000-MI2                | Desktop     | [44a9ba60e7](https://linux-hardware.org/?probe=44a9ba60e7) | Dec 29, 2023 |
| Acer          | WMCP78M                     | Desktop     | [1384395472](https://linux-hardware.org/?probe=1384395472) | Dec 29, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [3729a3492e](https://linux-hardware.org/?probe=3729a3492e) | Dec 29, 2023 |
| MSI           | 760GMA-P34                  | Desktop     | [4d6001354b](https://linux-hardware.org/?probe=4d6001354b) | Dec 29, 2023 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [658dc99555](https://linux-hardware.org/?probe=658dc99555) | Dec 29, 2023 |
| LG Electro... | P420-N.AE21G                | Notebook    | [3fdf04ae52](https://linux-hardware.org/?probe=3fdf04ae52) | Dec 29, 2023 |
| Gigabyte      | P55A-UD4                    | Desktop     | [c1694a8923](https://linux-hardware.org/?probe=c1694a8923) | Dec 29, 2023 |
| Apple         | MacBookPro5,2               | Notebook    | [b6269d662d](https://linux-hardware.org/?probe=b6269d662d) | Dec 29, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [7108d28aab](https://linux-hardware.org/?probe=7108d28aab) | Dec 29, 2023 |
| Apple         | MacBookPro14,3              | Notebook    | [83399f5e60](https://linux-hardware.org/?probe=83399f5e60) | Dec 29, 2023 |
| ASUSTek       | K53SV                       | Notebook    | [c285275ef1](https://linux-hardware.org/?probe=c285275ef1) | Dec 29, 2023 |
| MSI           | 760GMA-P34                  | Desktop     | [0e59657bca](https://linux-hardware.org/?probe=0e59657bca) | Dec 29, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [1229449c91](https://linux-hardware.org/?probe=1229449c91) | Dec 29, 2023 |
| Lenovo        | ThinkPad T450 20BUS2VK00    | Notebook    | [15de64acfb](https://linux-hardware.org/?probe=15de64acfb) | Dec 29, 2023 |
| Gigabyte      | P55A-UD4                    | Desktop     | [580efd7b07](https://linux-hardware.org/?probe=580efd7b07) | Dec 29, 2023 |
| Lenovo        | Annapurna CRB NOK           | Desktop     | [1e5fb94730](https://linux-hardware.org/?probe=1e5fb94730) | Dec 29, 2023 |
| MSI           | H510M PRO                   | Desktop     | [642f22170e](https://linux-hardware.org/?probe=642f22170e) | Dec 29, 2023 |
| HP            | ProLiant DL360p Gen8        | Server      | [01d5a057b5](https://linux-hardware.org/?probe=01d5a057b5) | Dec 29, 2023 |
| Inventec      | VXC Class A02               | Desktop     | [0575404de8](https://linux-hardware.org/?probe=0575404de8) | Dec 29, 2023 |
| MSI           | MS-168B                     | Notebook    | [cd9dc4eadd](https://linux-hardware.org/?probe=cd9dc4eadd) | Dec 29, 2023 |
| ASUSTek       | PN53                        | Mini pc     | [e648f1abef](https://linux-hardware.org/?probe=e648f1abef) | Dec 29, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [9f85581cdb](https://linux-hardware.org/?probe=9f85581cdb) | Dec 29, 2023 |
| HP            | Compaq Presario A900        | Notebook    | [e22eed28b4](https://linux-hardware.org/?probe=e22eed28b4) | Dec 29, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [656b1b3ae1](https://linux-hardware.org/?probe=656b1b3ae1) | Dec 29, 2023 |
| Monster       | TULPAR T5 V23.2             | Notebook    | [9592c22858](https://linux-hardware.org/?probe=9592c22858) | Dec 29, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [6de199d009](https://linux-hardware.org/?probe=6de199d009) | Dec 29, 2023 |
| Lenovo        | Unknown                     | Notebook    | [71b939033d](https://linux-hardware.org/?probe=71b939033d) | Dec 28, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [990d141701](https://linux-hardware.org/?probe=990d141701) | Dec 28, 2023 |
| Lenovo        | G700 20251                  | Notebook    | [3426bbc85d](https://linux-hardware.org/?probe=3426bbc85d) | Dec 28, 2023 |
| TUXEDO        | Polaris AMD Gen5            | Notebook    | [46ad5a6b29](https://linux-hardware.org/?probe=46ad5a6b29) | Dec 28, 2023 |
| Lenovo        | G700 20251                  | Notebook    | [78b29bb9e8](https://linux-hardware.org/?probe=78b29bb9e8) | Dec 28, 2023 |
| Dell          | Latitude E7450              | Notebook    | [50b3989c19](https://linux-hardware.org/?probe=50b3989c19) | Dec 28, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [62aa46f354](https://linux-hardware.org/?probe=62aa46f354) | Dec 28, 2023 |
| Lenovo        | ThinkPad T420 4180ED3       | Notebook    | [0c9cecfac4](https://linux-hardware.org/?probe=0c9cecfac4) | Dec 28, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [6f277a8c3f](https://linux-hardware.org/?probe=6f277a8c3f) | Dec 28, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [42c62dac0e](https://linux-hardware.org/?probe=42c62dac0e) | Dec 28, 2023 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [e65000c3c2](https://linux-hardware.org/?probe=e65000c3c2) | Dec 28, 2023 |
| ASRock        | B650E PG Riptide WiFi       | Desktop     | [3bf93539f3](https://linux-hardware.org/?probe=3bf93539f3) | Dec 28, 2023 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [5bd82e2331](https://linux-hardware.org/?probe=5bd82e2331) | Dec 28, 2023 |
| Gigabyte      | H61M-D2H-USB3               | Desktop     | [018e344b4d](https://linux-hardware.org/?probe=018e344b4d) | Dec 28, 2023 |
| ASRock        | AMCP7A-ION                  | Desktop     | [8358bb2fb8](https://linux-hardware.org/?probe=8358bb2fb8) | Dec 28, 2023 |
| HP            | EliteBook 8560p             | Notebook    | [16a5247446](https://linux-hardware.org/?probe=16a5247446) | Dec 28, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [5d86cb3268](https://linux-hardware.org/?probe=5d86cb3268) | Dec 28, 2023 |
| LG Electro... | S510-X.CBCKG                | Notebook    | [41f03f323d](https://linux-hardware.org/?probe=41f03f323d) | Dec 28, 2023 |
| LG Electro... | S510-X.CBCKG                | Notebook    | [1348f972c2](https://linux-hardware.org/?probe=1348f972c2) | Dec 28, 2023 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | Notebook    | [08fc99186e](https://linux-hardware.org/?probe=08fc99186e) | Dec 28, 2023 |
| HP            | EliteBook 8560p             | Notebook    | [82f94ea967](https://linux-hardware.org/?probe=82f94ea967) | Dec 28, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [c68ea76b65](https://linux-hardware.org/?probe=c68ea76b65) | Dec 28, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [48d04b219b](https://linux-hardware.org/?probe=48d04b219b) | Dec 28, 2023 |
| Lenovo        | ThinkPad T440s 20ARS0J60... | Notebook    | [0f46c7112d](https://linux-hardware.org/?probe=0f46c7112d) | Dec 28, 2023 |
| Medion        | E3223                       | Convertible | [f7839c2e8b](https://linux-hardware.org/?probe=f7839c2e8b) | Dec 28, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [020ea108b0](https://linux-hardware.org/?probe=020ea108b0) | Dec 28, 2023 |
| ASRock        | X570 Steel Legend           | Desktop     | [a2a45575d5](https://linux-hardware.org/?probe=a2a45575d5) | Dec 28, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [4118aee355](https://linux-hardware.org/?probe=4118aee355) | Dec 28, 2023 |
| ASRock        | X570 Steel Legend           | Desktop     | [836a55f0b6](https://linux-hardware.org/?probe=836a55f0b6) | Dec 28, 2023 |
| Dell          | 0F642F A00                  | Desktop     | [6adfd04a7e](https://linux-hardware.org/?probe=6adfd04a7e) | Dec 27, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [313a669de8](https://linux-hardware.org/?probe=313a669de8) | Dec 27, 2023 |
| Panasonic     | FZ-M1CCA17E3                | Notebook    | [c55632d60a](https://linux-hardware.org/?probe=c55632d60a) | Dec 27, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [99dfa98b06](https://linux-hardware.org/?probe=99dfa98b06) | Dec 27, 2023 |
| Lenovo        | Legion Y540-17IRH-PG0 81... | Notebook    | [8ec110334b](https://linux-hardware.org/?probe=8ec110334b) | Dec 27, 2023 |
| HP            | Elite x2 G4                 | Tablet      | [cb6bd15ff8](https://linux-hardware.org/?probe=cb6bd15ff8) | Dec 27, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [a6041ee7fc](https://linux-hardware.org/?probe=a6041ee7fc) | Dec 27, 2023 |
| Valve         | Jupiter                     | Notebook    | [73a4d3fcfd](https://linux-hardware.org/?probe=73a4d3fcfd) | Dec 27, 2023 |
| HP            | Elite x2 G4                 | Tablet      | [3a105d883b](https://linux-hardware.org/?probe=3a105d883b) | Dec 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [3fd67d4da9](https://linux-hardware.org/?probe=3fd67d4da9) | Dec 27, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [7b5e390f00](https://linux-hardware.org/?probe=7b5e390f00) | Dec 27, 2023 |
| MSI           | MPG B650 CARBON WIFI        | Desktop     | [6a0970bd24](https://linux-hardware.org/?probe=6a0970bd24) | Dec 27, 2023 |
| Gigabyte      | H61M-D2H-USB3               | Desktop     | [64a4b468b6](https://linux-hardware.org/?probe=64a4b468b6) | Dec 27, 2023 |
| Biostar       | A68N-5000                   | Desktop     | [19f4961efd](https://linux-hardware.org/?probe=19f4961efd) | Dec 27, 2023 |
| TUXEDO        | Pulse 14 Gen3               | Notebook    | [7873276f27](https://linux-hardware.org/?probe=7873276f27) | Dec 27, 2023 |
| Inter Sale... | NID-11125DE                 | Notebook    | [b3e9e05ed1](https://linux-hardware.org/?probe=b3e9e05ed1) | Dec 27, 2023 |
| Acer          | Nitro AN517-41              | Notebook    | [ab7e890030](https://linux-hardware.org/?probe=ab7e890030) | Dec 27, 2023 |
| HP            | Laptop 17-bs0xx             | Notebook    | [07f0d2eb99](https://linux-hardware.org/?probe=07f0d2eb99) | Dec 27, 2023 |
| ASRock        | H61M-DGS R2.0               | Desktop     | [fd5af25b3b](https://linux-hardware.org/?probe=fd5af25b3b) | Dec 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [10918ac964](https://linux-hardware.org/?probe=10918ac964) | Dec 27, 2023 |
| ASUSTek       | H97-PLUS                    | Desktop     | [b1e081701a](https://linux-hardware.org/?probe=b1e081701a) | Dec 27, 2023 |
| ShangMai      | H                           | Notebook    | [aab28ab3ea](https://linux-hardware.org/?probe=aab28ab3ea) | Dec 27, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [45f0a0ac2d](https://linux-hardware.org/?probe=45f0a0ac2d) | Dec 27, 2023 |
| Alienware     | 15 R4                       | Notebook    | [b0bc2ccb53](https://linux-hardware.org/?probe=b0bc2ccb53) | Dec 27, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [a74968ee9c](https://linux-hardware.org/?probe=a74968ee9c) | Dec 27, 2023 |
| Gigabyte      | Z370M D3H-CF                | Desktop     | [d73ec66a3a](https://linux-hardware.org/?probe=d73ec66a3a) | Dec 26, 2023 |
| Gigabyte      | A320M-DS2-CF                | Desktop     | [a0ef6497e0](https://linux-hardware.org/?probe=a0ef6497e0) | Dec 26, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [38b1c283b4](https://linux-hardware.org/?probe=38b1c283b4) | Dec 26, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [d1cd9acaf0](https://linux-hardware.org/?probe=d1cd9acaf0) | Dec 26, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [ab795ed232](https://linux-hardware.org/?probe=ab795ed232) | Dec 26, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [3673afc1cd](https://linux-hardware.org/?probe=3673afc1cd) | Dec 26, 2023 |
| GPD           | G1619-04                    | Notebook    | [f77175c08b](https://linux-hardware.org/?probe=f77175c08b) | Dec 26, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [9b570f14f6](https://linux-hardware.org/?probe=9b570f14f6) | Dec 26, 2023 |
| Acer          | Predator G9-793             | Notebook    | [cd39cff277](https://linux-hardware.org/?probe=cd39cff277) | Dec 26, 2023 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [743bed087b](https://linux-hardware.org/?probe=743bed087b) | Dec 26, 2023 |
| TUXEDO        | N24_25JU                    | Notebook    | [3c7a5feb48](https://linux-hardware.org/?probe=3c7a5feb48) | Dec 26, 2023 |
| Lenovo        | ThinkPad T520 4243ED3       | Notebook    | [6fd4832f12](https://linux-hardware.org/?probe=6fd4832f12) | Dec 26, 2023 |
| HUAWEI        | MRGFG-XX                    | Notebook    | [8ac7316911](https://linux-hardware.org/?probe=8ac7316911) | Dec 26, 2023 |
| Biostar       | A68N-5000                   | Desktop     | [39703ac1bc](https://linux-hardware.org/?probe=39703ac1bc) | Dec 26, 2023 |
| Gigabyte      | Z270-HD3P-CF                | Desktop     | [6bf30b2ec5](https://linux-hardware.org/?probe=6bf30b2ec5) | Dec 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [4a481ca830](https://linux-hardware.org/?probe=4a481ca830) | Dec 26, 2023 |
| Lenovo        | IdeaPad Slim 5 14IAH8 83... | Notebook    | [e514863c67](https://linux-hardware.org/?probe=e514863c67) | Dec 26, 2023 |
| Dell          | Inspiron 5391               | Notebook    | [a97f2efb6f](https://linux-hardware.org/?probe=a97f2efb6f) | Dec 26, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [e1bbb2ee71](https://linux-hardware.org/?probe=e1bbb2ee71) | Dec 26, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [17304074a6](https://linux-hardware.org/?probe=17304074a6) | Dec 26, 2023 |
| Schenker      | N13xWU                      | Notebook    | [c94ab912c7](https://linux-hardware.org/?probe=c94ab912c7) | Dec 26, 2023 |
| Gigabyte      | B75M-D3V                    | Desktop     | [a58934ade1](https://linux-hardware.org/?probe=a58934ade1) | Dec 26, 2023 |
| Schenker      | N13xWU                      | Notebook    | [b2ff4375a0](https://linux-hardware.org/?probe=b2ff4375a0) | Dec 26, 2023 |
| Gigabyte      | B75M-D3V                    | Desktop     | [8616b021c1](https://linux-hardware.org/?probe=8616b021c1) | Dec 26, 2023 |
| Dell          | Precision 7520              | Notebook    | [e4390e22b6](https://linux-hardware.org/?probe=e4390e22b6) | Dec 26, 2023 |
| Gigabyte      | Z390 UD                     | Desktop     | [82333229d6](https://linux-hardware.org/?probe=82333229d6) | Dec 26, 2023 |
| Lenovo        | ThinkPad T61 7663DL1        | Notebook    | [b01632df81](https://linux-hardware.org/?probe=b01632df81) | Dec 26, 2023 |
| Gigabyte      | Z390 UD                     | Desktop     | [a87c271e68](https://linux-hardware.org/?probe=a87c271e68) | Dec 26, 2023 |
| Gigabyte      | Z390 UD                     | Desktop     | [30780ea209](https://linux-hardware.org/?probe=30780ea209) | Dec 26, 2023 |
| Shenzhen M... | F7BSD                       | Mini pc     | [7ef8b526bf](https://linux-hardware.org/?probe=7ef8b526bf) | Dec 26, 2023 |
| Medion        | E6228                       | Notebook    | [827fcc5d4b](https://linux-hardware.org/?probe=827fcc5d4b) | Dec 26, 2023 |
| Fujitsu       | LIFEBOOK U7412              | Notebook    | [a2797ec36b](https://linux-hardware.org/?probe=a2797ec36b) | Dec 26, 2023 |
| Dell          | 0K240Y A02                  | Desktop     | [c9ace2ba93](https://linux-hardware.org/?probe=c9ace2ba93) | Dec 26, 2023 |
| Medion        | S6445 MD61281               | Notebook    | [b7db1404b6](https://linux-hardware.org/?probe=b7db1404b6) | Dec 26, 2023 |
| Lenovo        | ThinkPad P51 20HH0016GE     | Notebook    | [27f368f0df](https://linux-hardware.org/?probe=27f368f0df) | Dec 26, 2023 |
| Acer          | Aspire V5-123               | Notebook    | [1a5a81980b](https://linux-hardware.org/?probe=1a5a81980b) | Dec 26, 2023 |
| ASUSTek       | PN53                        | Mini pc     | [475a32b16d](https://linux-hardware.org/?probe=475a32b16d) | Dec 25, 2023 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [f6df6fc800](https://linux-hardware.org/?probe=f6df6fc800) | Dec 25, 2023 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [2f1d5396df](https://linux-hardware.org/?probe=2f1d5396df) | Dec 25, 2023 |
| HP            | 82FE 11                     | Desktop     | [e9d77b121e](https://linux-hardware.org/?probe=e9d77b121e) | Dec 25, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [96aa7493e0](https://linux-hardware.org/?probe=96aa7493e0) | Dec 25, 2023 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [f6f41d95dc](https://linux-hardware.org/?probe=f6f41d95dc) | Dec 25, 2023 |
| Acer          | Predator PH18-71            | Notebook    | [d1434eb282](https://linux-hardware.org/?probe=d1434eb282) | Dec 25, 2023 |
| Microsoft     | Surface Pro 8               | Tablet      | [751e8a9cc9](https://linux-hardware.org/?probe=751e8a9cc9) | Dec 25, 2023 |
| Valve         | Jupiter                     | Notebook    | [509364a4ac](https://linux-hardware.org/?probe=509364a4ac) | Dec 25, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [41f592a596](https://linux-hardware.org/?probe=41f592a596) | Dec 25, 2023 |
| MSI           | GP60 2OD                    | Notebook    | [496ea3ab9c](https://linux-hardware.org/?probe=496ea3ab9c) | Dec 25, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [5cc2120efc](https://linux-hardware.org/?probe=5cc2120efc) | Dec 25, 2023 |
| ASRock        | H61M-DGS R2.0               | Desktop     | [de35c0b58a](https://linux-hardware.org/?probe=de35c0b58a) | Dec 25, 2023 |
| Gigabyte      | 990FXA-UD7                  | Desktop     | [9bc8844164](https://linux-hardware.org/?probe=9bc8844164) | Dec 25, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [9a82f5d4ae](https://linux-hardware.org/?probe=9a82f5d4ae) | Dec 25, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [6233bad3b5](https://linux-hardware.org/?probe=6233bad3b5) | Dec 25, 2023 |
| Acer          | Extensa 2540                | Notebook    | [353ebde365](https://linux-hardware.org/?probe=353ebde365) | Dec 25, 2023 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | Notebook    | [a82bef9300](https://linux-hardware.org/?probe=a82bef9300) | Dec 25, 2023 |
| Medion        | H81H3-EM2 H81EM2W08.309     | Desktop     | [a8025e429f](https://linux-hardware.org/?probe=a8025e429f) | Dec 25, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [6bcc868ad6](https://linux-hardware.org/?probe=6bcc868ad6) | Dec 25, 2023 |
| Lenovo        | Annapurna CRB NOK           | Desktop     | [2cf0a3c6b7](https://linux-hardware.org/?probe=2cf0a3c6b7) | Dec 25, 2023 |
| ASUSTek       | X201EP                      | Notebook    | [944a54b7f4](https://linux-hardware.org/?probe=944a54b7f4) | Dec 25, 2023 |
| ASUSTek       | ROG Maximus Z790 HERO       | Desktop     | [61d0f60cae](https://linux-hardware.org/?probe=61d0f60cae) | Dec 25, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [7f06a26b50](https://linux-hardware.org/?probe=7f06a26b50) | Dec 25, 2023 |
| Toshiba       | Satellite L70-A             | Notebook    | [e5ed4a0805](https://linux-hardware.org/?probe=e5ed4a0805) | Dec 25, 2023 |
| Toshiba       | Satellite L70-A             | Notebook    | [7f05fe91ae](https://linux-hardware.org/?probe=7f05fe91ae) | Dec 25, 2023 |
| TUXEDO        | N24_25JU                    | Notebook    | [26beeaeefa](https://linux-hardware.org/?probe=26beeaeefa) | Dec 25, 2023 |
| Razer         | Blade Pro 17 (2019)         | Notebook    | [25b1af1536](https://linux-hardware.org/?probe=25b1af1536) | Dec 25, 2023 |
| ASUSTek       | K50AF                       | Notebook    | [88415099d0](https://linux-hardware.org/?probe=88415099d0) | Dec 25, 2023 |
| ASUSTek       | ROG Strix G713RW_G713RW     | Notebook    | [7a7f4ca17a](https://linux-hardware.org/?probe=7a7f4ca17a) | Dec 25, 2023 |
| HP            | 625                         | Notebook    | [c826402085](https://linux-hardware.org/?probe=c826402085) | Dec 24, 2023 |
| HP            | 625                         | Notebook    | [3d8a288af1](https://linux-hardware.org/?probe=3d8a288af1) | Dec 24, 2023 |
| ASUSTek       | PN53                        | Mini pc     | [e94cee527d](https://linux-hardware.org/?probe=e94cee527d) | Dec 24, 2023 |
| Acer          | Aspire 5749                 | Notebook    | [e70e0eae25](https://linux-hardware.org/?probe=e70e0eae25) | Dec 24, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [d37994124a](https://linux-hardware.org/?probe=d37994124a) | Dec 24, 2023 |
| Acer          | Aspire 1810TZ               | Notebook    | [0b4e0e5e2b](https://linux-hardware.org/?probe=0b4e0e5e2b) | Dec 24, 2023 |
| Acer          | Aspire 1810TZ               | Notebook    | [3ba98d8db9](https://linux-hardware.org/?probe=3ba98d8db9) | Dec 24, 2023 |
| Gigabyte      | Z87X-UD3H-CF                | Desktop     | [736c52940a](https://linux-hardware.org/?probe=736c52940a) | Dec 24, 2023 |
| Intel         | D34010WYK H14771-304        | Desktop     | [95ab790a9c](https://linux-hardware.org/?probe=95ab790a9c) | Dec 24, 2023 |
| Valve         | Jupiter                     | Notebook    | [c0b15b216d](https://linux-hardware.org/?probe=c0b15b216d) | Dec 24, 2023 |
| Lenovo        | ThinkPad X280 20KES4TD0T    | Notebook    | [978819464c](https://linux-hardware.org/?probe=978819464c) | Dec 24, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [d330d1d9f9](https://linux-hardware.org/?probe=d330d1d9f9) | Dec 24, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | Desktop     | [6c327c054f](https://linux-hardware.org/?probe=6c327c054f) | Dec 24, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [d8ae24af2b](https://linux-hardware.org/?probe=d8ae24af2b) | Dec 24, 2023 |
| TUXEDO        | Polaris AMD Gen5            | Notebook    | [f63c59d851](https://linux-hardware.org/?probe=f63c59d851) | Dec 24, 2023 |
| Lenovo        | ThinkPad T520 4242CW5       | Notebook    | [0bd929d735](https://linux-hardware.org/?probe=0bd929d735) | Dec 24, 2023 |
| MSI           | H97 PC Mate                 | Desktop     | [f1c5d0d405](https://linux-hardware.org/?probe=f1c5d0d405) | Dec 24, 2023 |
| Intel         | NUC13ANBi7 M89645-203       | Mini pc     | [27124f064a](https://linux-hardware.org/?probe=27124f064a) | Dec 24, 2023 |
| Intel         | NUC13ANBi7 M89645-203       | Mini pc     | [e12710e5bd](https://linux-hardware.org/?probe=e12710e5bd) | Dec 24, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [a12f3e5ce6](https://linux-hardware.org/?probe=a12f3e5ce6) | Dec 24, 2023 |
| Intel         | NUC13ANBi7 M89645-203       | Mini pc     | [1fe8e8f18d](https://linux-hardware.org/?probe=1fe8e8f18d) | Dec 24, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [1a31482d70](https://linux-hardware.org/?probe=1a31482d70) | Dec 24, 2023 |
| Notebook      | NL5xNU                      | Notebook    | [1cb09f63f9](https://linux-hardware.org/?probe=1cb09f63f9) | Dec 24, 2023 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | Desktop     | [646b9af5a9](https://linux-hardware.org/?probe=646b9af5a9) | Dec 24, 2023 |
| Intel         | NUC13ANBi7 M89645-203       | Mini pc     | [381955efac](https://linux-hardware.org/?probe=381955efac) | Dec 24, 2023 |
| MSI           | B350M PRO-VDH               | Desktop     | [d845a3492b](https://linux-hardware.org/?probe=d845a3492b) | Dec 24, 2023 |
| MSI           | B350M PRO-VDH               | Desktop     | [a6e1fc3b29](https://linux-hardware.org/?probe=a6e1fc3b29) | Dec 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [1297c97e04](https://linux-hardware.org/?probe=1297c97e04) | Dec 24, 2023 |
| HP            | Presario CQ61               | Notebook    | [249a217a7c](https://linux-hardware.org/?probe=249a217a7c) | Dec 24, 2023 |
| Teclast       | F6 Plus                     | Notebook    | [a8fee53f37](https://linux-hardware.org/?probe=a8fee53f37) | Dec 24, 2023 |
| Acer          | TDPS05                      | Desktop     | [ce9b5d0c48](https://linux-hardware.org/?probe=ce9b5d0c48) | Dec 23, 2023 |
| ASUSTek       | M2V                         | Desktop     | [67c7bc43ed](https://linux-hardware.org/?probe=67c7bc43ed) | Dec 23, 2023 |
| ASUSTek       | M2V                         | Desktop     | [1d6970f290](https://linux-hardware.org/?probe=1d6970f290) | Dec 23, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [275aa2eb92](https://linux-hardware.org/?probe=275aa2eb92) | Dec 23, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [4b2ed8b976](https://linux-hardware.org/?probe=4b2ed8b976) | Dec 23, 2023 |
| AZW           | EQ                          | Desktop     | [a04c9735a7](https://linux-hardware.org/?probe=a04c9735a7) | Dec 23, 2023 |
| AZW           | EQ                          | Desktop     | [9b3d265cd1](https://linux-hardware.org/?probe=9b3d265cd1) | Dec 23, 2023 |
| Dell          | 0J1C3P A01                  | Desktop     | [faea7a3006](https://linux-hardware.org/?probe=faea7a3006) | Dec 23, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [0b0beeca3a](https://linux-hardware.org/?probe=0b0beeca3a) | Dec 23, 2023 |
| System76      | Gazelle                     | Notebook    | [2b9bce59e7](https://linux-hardware.org/?probe=2b9bce59e7) | Dec 23, 2023 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [3625c673e4](https://linux-hardware.org/?probe=3625c673e4) | Dec 23, 2023 |
| TUXEDO        | N24_25JU                    | Notebook    | [8a1a153723](https://linux-hardware.org/?probe=8a1a153723) | Dec 23, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [c8bab56547](https://linux-hardware.org/?probe=c8bab56547) | Dec 23, 2023 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [6f36390142](https://linux-hardware.org/?probe=6f36390142) | Dec 23, 2023 |
| Lenovo        | IdeaPad Y500 9541           | Notebook    | [a85ec375f5](https://linux-hardware.org/?probe=a85ec375f5) | Dec 23, 2023 |
| ASRock        | AMCP7A-ION                  | Desktop     | [fb0acc2d50](https://linux-hardware.org/?probe=fb0acc2d50) | Dec 23, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [64a00841b2](https://linux-hardware.org/?probe=64a00841b2) | Dec 23, 2023 |
| Acer          | TDPS05                      | Desktop     | [d0260b1327](https://linux-hardware.org/?probe=d0260b1327) | Dec 23, 2023 |
| ASUSTek       | X99-A II                    | Desktop     | [37e4430c0e](https://linux-hardware.org/?probe=37e4430c0e) | Dec 23, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [d12d3a2f21](https://linux-hardware.org/?probe=d12d3a2f21) | Dec 23, 2023 |
| Lenovo        | ThinkCentre M58 7373AJ5     | Desktop     | [201981bc3f](https://linux-hardware.org/?probe=201981bc3f) | Dec 23, 2023 |
| Intel         | NUC6CAYB J23203-403         | Mini pc     | [83e47fa893](https://linux-hardware.org/?probe=83e47fa893) | Dec 23, 2023 |
| HP            | EliteBook 8570w             | Notebook    | [4b6025ed6e](https://linux-hardware.org/?probe=4b6025ed6e) | Dec 23, 2023 |
| Gigabyte      | B85-HD3                     | Desktop     | [79fbb89592](https://linux-hardware.org/?probe=79fbb89592) | Dec 23, 2023 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [4cd7d986cd](https://linux-hardware.org/?probe=4cd7d986cd) | Dec 23, 2023 |
| T-bao Tian... | GOD78                       | Desktop     | [cd28753d06](https://linux-hardware.org/?probe=cd28753d06) | Dec 23, 2023 |
| ASRock        | AMCP7A-ION                  | Desktop     | [7d19dec574](https://linux-hardware.org/?probe=7d19dec574) | Dec 23, 2023 |
| Lenovo        | ThinkPad T480 20L5000BGE    | Notebook    | [8753b04999](https://linux-hardware.org/?probe=8753b04999) | Dec 23, 2023 |
| Dell          | 0VHWTR A02                  | Desktop     | [86e89b6ffd](https://linux-hardware.org/?probe=86e89b6ffd) | Dec 23, 2023 |
| Microsoft     | Surface Go 2                | Tablet      | [0e05c29504](https://linux-hardware.org/?probe=0e05c29504) | Dec 23, 2023 |
| Lenovo        | ThinkBook 15 G4 ABA 21DL    | Notebook    | [5aae7c7b5c](https://linux-hardware.org/?probe=5aae7c7b5c) | Dec 23, 2023 |
| Lenovo        | ThinkBook 16 G6 IRL 21KH    | Notebook    | [c197684b37](https://linux-hardware.org/?probe=c197684b37) | Dec 23, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [d3dabca767](https://linux-hardware.org/?probe=d3dabca767) | Dec 23, 2023 |
| Toshiba       | Satellite Pro R50-C         | Notebook    | [b4d280ac6a](https://linux-hardware.org/?probe=b4d280ac6a) | Dec 23, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [26673c372e](https://linux-hardware.org/?probe=26673c372e) | Dec 23, 2023 |
| Toshiba       | Satellite Pro R50-C         | Notebook    | [421d62894b](https://linux-hardware.org/?probe=421d62894b) | Dec 23, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [391ef34135](https://linux-hardware.org/?probe=391ef34135) | Dec 23, 2023 |
| HP            | Laptop 17-bs1xx             | Notebook    | [984a979a7b](https://linux-hardware.org/?probe=984a979a7b) | Dec 23, 2023 |
| Gigabyte      | Z390 UD                     | Desktop     | [cd36fc0dc1](https://linux-hardware.org/?probe=cd36fc0dc1) | Dec 23, 2023 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [f189893dcb](https://linux-hardware.org/?probe=f189893dcb) | Dec 23, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [0f291ca562](https://linux-hardware.org/?probe=0f291ca562) | Dec 23, 2023 |
| Dell          | Latitude E6540              | Notebook    | [9e3371b6b2](https://linux-hardware.org/?probe=9e3371b6b2) | Dec 23, 2023 |
| MSI           | B560M PRO                   | Desktop     | [3885df62ab](https://linux-hardware.org/?probe=3885df62ab) | Dec 23, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [87b9f04878](https://linux-hardware.org/?probe=87b9f04878) | Dec 23, 2023 |
| ASUSTek       | P6T                         | Desktop     | [d90adb3a12](https://linux-hardware.org/?probe=d90adb3a12) | Dec 23, 2023 |
| Lenovo        | ThinkPad T480 20L6S69B00    | Notebook    | [16b6aaa173](https://linux-hardware.org/?probe=16b6aaa173) | Dec 23, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [5b7a85e9fc](https://linux-hardware.org/?probe=5b7a85e9fc) | Dec 23, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [b9b670d3c0](https://linux-hardware.org/?probe=b9b670d3c0) | Dec 23, 2023 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | Notebook    | [569ce717aa](https://linux-hardware.org/?probe=569ce717aa) | Dec 23, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | Notebook    | [8dad235090](https://linux-hardware.org/?probe=8dad235090) | Dec 23, 2023 |
| Lenovo        | Legion 5 15IAH7H 82RB       | Notebook    | [2ca58f3eb8](https://linux-hardware.org/?probe=2ca58f3eb8) | Dec 23, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [8a36394313](https://linux-hardware.org/?probe=8a36394313) | Dec 23, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [eb035a95fa](https://linux-hardware.org/?probe=eb035a95fa) | Dec 22, 2023 |
| AZW           | SER V1                      | Desktop     | [73cc7b7f87](https://linux-hardware.org/?probe=73cc7b7f87) | Dec 22, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [4adc5f3f81](https://linux-hardware.org/?probe=4adc5f3f81) | Dec 22, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K6... | Notebook    | [d53640436b](https://linux-hardware.org/?probe=d53640436b) | Dec 22, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [42c72b303d](https://linux-hardware.org/?probe=42c72b303d) | Dec 22, 2023 |
| Dell          | Precision M4800             | Notebook    | [ce7a9239f4](https://linux-hardware.org/?probe=ce7a9239f4) | Dec 22, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [7afecc25eb](https://linux-hardware.org/?probe=7afecc25eb) | Dec 22, 2023 |
| Medion        | X682X                       | Notebook    | [c0deb0e748](https://linux-hardware.org/?probe=c0deb0e748) | Dec 22, 2023 |
| Apple         | MacBookPro13,1              | Notebook    | [89ef1fa23c](https://linux-hardware.org/?probe=89ef1fa23c) | Dec 22, 2023 |
| ASUSTek       | X555LD                      | Notebook    | [c81a75e686](https://linux-hardware.org/?probe=c81a75e686) | Dec 22, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [db8c00daf3](https://linux-hardware.org/?probe=db8c00daf3) | Dec 22, 2023 |
| HP            | 84F5                        | Mini pc     | [e91c19712f](https://linux-hardware.org/?probe=e91c19712f) | Dec 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [3f903fafe6](https://linux-hardware.org/?probe=3f903fafe6) | Dec 22, 2023 |
| ASUSTek       | K50AF                       | Notebook    | [367c28d17a](https://linux-hardware.org/?probe=367c28d17a) | Dec 22, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [a11f0a948c](https://linux-hardware.org/?probe=a11f0a948c) | Dec 22, 2023 |
| Lenovo        | ThinkPad T440p 20AWS0280... | Notebook    | [239bc0b85a](https://linux-hardware.org/?probe=239bc0b85a) | Dec 22, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [f71924e3e4](https://linux-hardware.org/?probe=f71924e3e4) | Dec 22, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [75c61bce6d](https://linux-hardware.org/?probe=75c61bce6d) | Dec 22, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [94462e79e4](https://linux-hardware.org/?probe=94462e79e4) | Dec 22, 2023 |
| Acer          | Aspire E5-576               | Notebook    | [e40f16f86b](https://linux-hardware.org/?probe=e40f16f86b) | Dec 22, 2023 |
| ASUSTek       | Maximus VI GENE             | Desktop     | [178aab1062](https://linux-hardware.org/?probe=178aab1062) | Dec 22, 2023 |
| ASUSTek       | PN53                        | Mini pc     | [1310ad15a9](https://linux-hardware.org/?probe=1310ad15a9) | Dec 22, 2023 |
| ASUSTek       | X555LD                      | Notebook    | [30e988edc9](https://linux-hardware.org/?probe=30e988edc9) | Dec 22, 2023 |
| Apple         | Mac-CFF7D910A743CAAF iMa... | All in one  | [61154d87f0](https://linux-hardware.org/?probe=61154d87f0) | Dec 22, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [dfc1d4289e](https://linux-hardware.org/?probe=dfc1d4289e) | Dec 22, 2023 |
| Medion        | S17403                      | Notebook    | [167acdd156](https://linux-hardware.org/?probe=167acdd156) | Dec 22, 2023 |
| Toshiba       | Satellite Pro L850-1L2      | Notebook    | [c3bfd150bc](https://linux-hardware.org/?probe=c3bfd150bc) | Dec 22, 2023 |
| Fujitsu       | LIFEBOOK T939               | Convertible | [2f5eddacdb](https://linux-hardware.org/?probe=2f5eddacdb) | Dec 22, 2023 |
| Lenovo        | Flex 2-15D 20377            | Notebook    | [a22602448b](https://linux-hardware.org/?probe=a22602448b) | Dec 22, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [3ff2f289b9](https://linux-hardware.org/?probe=3ff2f289b9) | Dec 22, 2023 |
| Acer          | Aspire A515-44              | Notebook    | [874744ee1f](https://linux-hardware.org/?probe=874744ee1f) | Dec 22, 2023 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [dbc2e93666](https://linux-hardware.org/?probe=dbc2e93666) | Dec 21, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS       | Desktop     | [0dc09851b1](https://linux-hardware.org/?probe=0dc09851b1) | Dec 21, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [084e48827c](https://linux-hardware.org/?probe=084e48827c) | Dec 21, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [37e175c7a2](https://linux-hardware.org/?probe=37e175c7a2) | Dec 21, 2023 |
| Gigabyte      | GA-990XA-UD3                | Desktop     | [f8215b7e03](https://linux-hardware.org/?probe=f8215b7e03) | Dec 21, 2023 |
| Dell          | Precision 5480              | Notebook    | [382626cfb5](https://linux-hardware.org/?probe=382626cfb5) | Dec 21, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [13b303a58b](https://linux-hardware.org/?probe=13b303a58b) | Dec 21, 2023 |
| ASRock        | A520M-HDV                   | Desktop     | [918677a1da](https://linux-hardware.org/?probe=918677a1da) | Dec 21, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [628ca02992](https://linux-hardware.org/?probe=628ca02992) | Dec 21, 2023 |
| ASRock        | A520M-HDV                   | Desktop     | [7136ba3916](https://linux-hardware.org/?probe=7136ba3916) | Dec 21, 2023 |
| Fujitsu       | LIFEBOOK T939               | Convertible | [b9c3b5a089](https://linux-hardware.org/?probe=b9c3b5a089) | Dec 21, 2023 |
| Alienware     | 14                          | Notebook    | [ee2678a24f](https://linux-hardware.org/?probe=ee2678a24f) | Dec 21, 2023 |
| HP            | ProBook 445 14 inch G10 ... | Notebook    | [0e95b32d0b](https://linux-hardware.org/?probe=0e95b32d0b) | Dec 21, 2023 |
| Fujitsu       | LIFEBOOK U749               | Notebook    | [75a3ef28b0](https://linux-hardware.org/?probe=75a3ef28b0) | Dec 21, 2023 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [b87a575222](https://linux-hardware.org/?probe=b87a575222) | Dec 21, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [f95bb7d27c](https://linux-hardware.org/?probe=f95bb7d27c) | Dec 21, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [5c0166e1f8](https://linux-hardware.org/?probe=5c0166e1f8) | Dec 21, 2023 |
| Lenovo        | Yoga 9 15IMH5 82DE          | Convertible | [d0d0568d9d](https://linux-hardware.org/?probe=d0d0568d9d) | Dec 21, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [1b8100314e](https://linux-hardware.org/?probe=1b8100314e) | Dec 21, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [e3a45d6095](https://linux-hardware.org/?probe=e3a45d6095) | Dec 21, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | Notebook    | [d178358ee1](https://linux-hardware.org/?probe=d178358ee1) | Dec 21, 2023 |
| ASRock        | H61M-DGS R2.0               | Desktop     | [5693d09326](https://linux-hardware.org/?probe=5693d09326) | Dec 21, 2023 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [8b094a74c9](https://linux-hardware.org/?probe=8b094a74c9) | Dec 21, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [030e411799](https://linux-hardware.org/?probe=030e411799) | Dec 21, 2023 |
| HUAWEI        | MRGFG-XX                    | Notebook    | [747de8fa3c](https://linux-hardware.org/?probe=747de8fa3c) | Dec 21, 2023 |
| Inter Sale... | NID-11125DE                 | Notebook    | [d65538541d](https://linux-hardware.org/?probe=d65538541d) | Dec 21, 2023 |
| ASUSTek       | X550LD                      | Notebook    | [bc65f1d620](https://linux-hardware.org/?probe=bc65f1d620) | Dec 21, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [93a7029d22](https://linux-hardware.org/?probe=93a7029d22) | Dec 21, 2023 |
| Lenovo        | ThinkPad L580 20LW0010GE    | Notebook    | [4bd3fc58a8](https://linux-hardware.org/?probe=4bd3fc58a8) | Dec 21, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [e221a6befb](https://linux-hardware.org/?probe=e221a6befb) | Dec 21, 2023 |
| In-S          | C116A                       | Notebook    | [ba252bb452](https://linux-hardware.org/?probe=ba252bb452) | Dec 20, 2023 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [fb91eaef3b](https://linux-hardware.org/?probe=fb91eaef3b) | Dec 20, 2023 |
| ASUSTek       | P5G41-M                     | Desktop     | [cbab9e248d](https://linux-hardware.org/?probe=cbab9e248d) | Dec 20, 2023 |
| Lenovo        | ThinkPad T480 20L6S01W00    | Notebook    | [c38a7a8ad4](https://linux-hardware.org/?probe=c38a7a8ad4) | Dec 20, 2023 |
| Gigabyte      | B560M H                     | Desktop     | [6e7f8b2300](https://linux-hardware.org/?probe=6e7f8b2300) | Dec 20, 2023 |
| Lenovo        | ThinkPad W520 42844DG       | Notebook    | [52cd813233](https://linux-hardware.org/?probe=52cd813233) | Dec 20, 2023 |
| Wortmann      | TERRA_MOBILE_1529H          | Notebook    | [49f1bedb5a](https://linux-hardware.org/?probe=49f1bedb5a) | Dec 20, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [74136911a0](https://linux-hardware.org/?probe=74136911a0) | Dec 20, 2023 |
| Dell          | Latitude 7480               | Notebook    | [f080cc67aa](https://linux-hardware.org/?probe=f080cc67aa) | Dec 20, 2023 |
| Pegatron      | TRUCKEE                     | Desktop     | [dbf9508eef](https://linux-hardware.org/?probe=dbf9508eef) | Dec 20, 2023 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | Notebook    | [2dcde776ad](https://linux-hardware.org/?probe=2dcde776ad) | Dec 20, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | Notebook    | [393c13e870](https://linux-hardware.org/?probe=393c13e870) | Dec 20, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | Notebook    | [09af8afa56](https://linux-hardware.org/?probe=09af8afa56) | Dec 20, 2023 |
| HP            | 3047h                       | Desktop     | [8f868cea54](https://linux-hardware.org/?probe=8f868cea54) | Dec 20, 2023 |
| Dell          | Latitude 7490               | Notebook    | [058142d276](https://linux-hardware.org/?probe=058142d276) | Dec 20, 2023 |
| HP            | EliteBook 8560p             | Notebook    | [b9e00df8b5](https://linux-hardware.org/?probe=b9e00df8b5) | Dec 20, 2023 |
| HP            | 3047h                       | Desktop     | [6e6ab07000](https://linux-hardware.org/?probe=6e6ab07000) | Dec 20, 2023 |
| HP            | EliteBook 8560p             | Notebook    | [334bc9d94f](https://linux-hardware.org/?probe=334bc9d94f) | Dec 20, 2023 |
| HP            | 3047h                       | Desktop     | [a1f3ed3f68](https://linux-hardware.org/?probe=a1f3ed3f68) | Dec 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | Notebook    | [2e42798435](https://linux-hardware.org/?probe=2e42798435) | Dec 20, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS       | Desktop     | [088b57605f](https://linux-hardware.org/?probe=088b57605f) | Dec 20, 2023 |
| Micro Comp... | Venus series                | Notebook    | [e01ac2dc02](https://linux-hardware.org/?probe=e01ac2dc02) | Dec 20, 2023 |
| MSI           | H61M-E33                    | Desktop     | [ab39035cef](https://linux-hardware.org/?probe=ab39035cef) | Dec 20, 2023 |
| MSI           | A78M-E45                    | Desktop     | [6d11f72d41](https://linux-hardware.org/?probe=6d11f72d41) | Dec 20, 2023 |
| Inter Sale... | NID-11125DE                 | Notebook    | [17af2fca66](https://linux-hardware.org/?probe=17af2fca66) | Dec 20, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [b14bdf4602](https://linux-hardware.org/?probe=b14bdf4602) | Dec 20, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [b362feddfa](https://linux-hardware.org/?probe=b362feddfa) | Dec 20, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [a641f9b41d](https://linux-hardware.org/?probe=a641f9b41d) | Dec 20, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [b6b4165e86](https://linux-hardware.org/?probe=b6b4165e86) | Dec 20, 2023 |
| Medion        | TJ4125                      | Desktop     | [8fce958467](https://linux-hardware.org/?probe=8fce958467) | Dec 20, 2023 |
| Valve         | Jupiter                     | Notebook    | [1265867fcf](https://linux-hardware.org/?probe=1265867fcf) | Dec 19, 2023 |
| MSI           | 970A-G46                    | Desktop     | [078bef5c72](https://linux-hardware.org/?probe=078bef5c72) | Dec 19, 2023 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [af88f0d2da](https://linux-hardware.org/?probe=af88f0d2da) | Dec 19, 2023 |
| HUAWEI        | MRGFG-XX                    | Notebook    | [6a10eb945c](https://linux-hardware.org/?probe=6a10eb945c) | Dec 19, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [e66c224547](https://linux-hardware.org/?probe=e66c224547) | Dec 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [da74c3a382](https://linux-hardware.org/?probe=da74c3a382) | Dec 19, 2023 |
| MSI           | Z77A-G45                    | Desktop     | [047feb8e76](https://linux-hardware.org/?probe=047feb8e76) | Dec 19, 2023 |
| TUXEDO        | Aura 14 Gen3                | Notebook    | [bdc38bf0fd](https://linux-hardware.org/?probe=bdc38bf0fd) | Dec 19, 2023 |
| HP            | 83E0                        | Desktop     | [8f41483d26](https://linux-hardware.org/?probe=8f41483d26) | Dec 19, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [2b7ff14fc2](https://linux-hardware.org/?probe=2b7ff14fc2) | Dec 19, 2023 |
| Wortmann      | TERRA_MOBILE_1542           | Notebook    | [f09218ee8f](https://linux-hardware.org/?probe=f09218ee8f) | Dec 19, 2023 |
| Lenovo        | 3704 SDK0K17763 WIN 1801... | Desktop     | [9a2472e628](https://linux-hardware.org/?probe=9a2472e628) | Dec 19, 2023 |
| HP            | ElitePad 1000 G2            | Notebook    | [533ccb0c41](https://linux-hardware.org/?probe=533ccb0c41) | Dec 19, 2023 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [492194d1fc](https://linux-hardware.org/?probe=492194d1fc) | Dec 19, 2023 |
| Lenovo        | IdeaPadFlex 15 20309        | Notebook    | [81dbec4f1a](https://linux-hardware.org/?probe=81dbec4f1a) | Dec 19, 2023 |
| TUXEDO        | Pulse 14 Gen1               | Notebook    | [031f8b45bd](https://linux-hardware.org/?probe=031f8b45bd) | Dec 19, 2023 |
| Sony          | SVE1511A1EW                 | Notebook    | [2f0fde3487](https://linux-hardware.org/?probe=2f0fde3487) | Dec 19, 2023 |
| HP            | 81B3                        | Desktop     | [86d9fc12a5](https://linux-hardware.org/?probe=86d9fc12a5) | Dec 19, 2023 |
| HP            | 655                         | Notebook    | [c0bd13830f](https://linux-hardware.org/?probe=c0bd13830f) | Dec 19, 2023 |
| Sony          | SVE1511A1EW                 | Notebook    | [e5531ecc00](https://linux-hardware.org/?probe=e5531ecc00) | Dec 19, 2023 |
| Shenzhen M... | F7BSC                       | Mini pc     | [8939d0afc4](https://linux-hardware.org/?probe=8939d0afc4) | Dec 19, 2023 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [6eb0111ee8](https://linux-hardware.org/?probe=6eb0111ee8) | Dec 19, 2023 |
| Gigabyte      | B550 AORUS MASTER           | Desktop     | [7bd446ee65](https://linux-hardware.org/?probe=7bd446ee65) | Dec 18, 2023 |
| Unknown       | HX90                        | Desktop     | [2bf61c79c6](https://linux-hardware.org/?probe=2bf61c79c6) | Dec 18, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | Desktop     | [5255e11641](https://linux-hardware.org/?probe=5255e11641) | Dec 18, 2023 |
| Acer          | Swift SF315-52G             | Notebook    | [26f06e876d](https://linux-hardware.org/?probe=26f06e876d) | Dec 18, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [985b139723](https://linux-hardware.org/?probe=985b139723) | Dec 18, 2023 |
| MSI           | Z77A-GD65                   | Desktop     | [a6d9b065a7](https://linux-hardware.org/?probe=a6d9b065a7) | Dec 18, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [229df442f5](https://linux-hardware.org/?probe=229df442f5) | Dec 18, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [d333f0b082](https://linux-hardware.org/?probe=d333f0b082) | Dec 18, 2023 |
| Acer          | Aspire E1-731               | Notebook    | [e5312bdd49](https://linux-hardware.org/?probe=e5312bdd49) | Dec 18, 2023 |
| HP            | ProBook 430 G4              | Notebook    | [c2b96a9e0f](https://linux-hardware.org/?probe=c2b96a9e0f) | Dec 18, 2023 |
| Medion        | TJ4125                      | Desktop     | [c7eeb77279](https://linux-hardware.org/?probe=c7eeb77279) | Dec 18, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [95d29a0474](https://linux-hardware.org/?probe=95d29a0474) | Dec 18, 2023 |
| Medion        | E6246 MD63200               | Notebook    | [eda979df79](https://linux-hardware.org/?probe=eda979df79) | Dec 18, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [1f03d33b22](https://linux-hardware.org/?probe=1f03d33b22) | Dec 18, 2023 |
| Packard Be... | EasyNote TE69BM             | Notebook    | [6a4bc96f4b](https://linux-hardware.org/?probe=6a4bc96f4b) | Dec 18, 2023 |
| ASRock        | H61M-DGS R2.0               | Desktop     | [dc6e7e06c3](https://linux-hardware.org/?probe=dc6e7e06c3) | Dec 18, 2023 |
| ASUSTek       | Zenbook UM5302LA_UM5302L... | Notebook    | [29ee1d8ad5](https://linux-hardware.org/?probe=29ee1d8ad5) | Dec 18, 2023 |
| Lenovo        | IdeaPad 1 11ADA05 82GV      | Notebook    | [980280224f](https://linux-hardware.org/?probe=980280224f) | Dec 18, 2023 |
| Lenovo        | IdeaPad 1 11ADA05 82GV      | Notebook    | [41f03f0699](https://linux-hardware.org/?probe=41f03f0699) | Dec 18, 2023 |
| Wortmann      | TERRA_MOBILE_1542           | Notebook    | [054ed4fad9](https://linux-hardware.org/?probe=054ed4fad9) | Dec 18, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [85358f7505](https://linux-hardware.org/?probe=85358f7505) | Dec 18, 2023 |
| MSI           | A75MA-G55                   | Desktop     | [6af3c61744](https://linux-hardware.org/?probe=6af3c61744) | Dec 18, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [9133031c56](https://linux-hardware.org/?probe=9133031c56) | Dec 18, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [b1d44e2673](https://linux-hardware.org/?probe=b1d44e2673) | Dec 17, 2023 |
| Panasonic     | FZ-M1CCA17E3                | Notebook    | [87024c17b5](https://linux-hardware.org/?probe=87024c17b5) | Dec 17, 2023 |
| Panasonic     | FZ-M1CCA17E3                | Notebook    | [8f2a76eb09](https://linux-hardware.org/?probe=8f2a76eb09) | Dec 17, 2023 |
| Medion        | BEAST X30                   | Notebook    | [cec06735ba](https://linux-hardware.org/?probe=cec06735ba) | Dec 17, 2023 |
| ASRock        | Z390 Extreme4               | Desktop     | [4067f8d4cb](https://linux-hardware.org/?probe=4067f8d4cb) | Dec 17, 2023 |
| Acer          | Swift SF315-41              | Notebook    | [300b426183](https://linux-hardware.org/?probe=300b426183) | Dec 17, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [a411802ac6](https://linux-hardware.org/?probe=a411802ac6) | Dec 17, 2023 |
| Acer          | Aspire 4820TG               | Notebook    | [a9bc29a915](https://linux-hardware.org/?probe=a9bc29a915) | Dec 17, 2023 |
| HP            | ENVY Laptop 17-ch0xxx       | Notebook    | [43602a664e](https://linux-hardware.org/?probe=43602a664e) | Dec 17, 2023 |
| Lenovo        | ThinkPad W550s 20E2CTO1W... | Notebook    | [17b157ef44](https://linux-hardware.org/?probe=17b157ef44) | Dec 17, 2023 |
| ASUSTek       | M5A78L-M LE                 | Desktop     | [d70deaa140](https://linux-hardware.org/?probe=d70deaa140) | Dec 17, 2023 |
| Dell          | 0J1C3P A01                  | Desktop     | [99eb1f88a4](https://linux-hardware.org/?probe=99eb1f88a4) | Dec 17, 2023 |
| ASRock        | Z77 Extreme4                | Desktop     | [ead1dfb3ae](https://linux-hardware.org/?probe=ead1dfb3ae) | Dec 17, 2023 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | Notebook    | [73693b1a91](https://linux-hardware.org/?probe=73693b1a91) | Dec 17, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [16ebb489d4](https://linux-hardware.org/?probe=16ebb489d4) | Dec 17, 2023 |
| Dell          | 02K9CR A02                  | Desktop     | [aeb868db71](https://linux-hardware.org/?probe=aeb868db71) | Dec 17, 2023 |
| HP            | ProBook 4535s               | Notebook    | [80aa5bd12b](https://linux-hardware.org/?probe=80aa5bd12b) | Dec 17, 2023 |
| Medion        | E6214                       | Notebook    | [1bc5839854](https://linux-hardware.org/?probe=1bc5839854) | Dec 17, 2023 |
| ASRock        | Z390 Extreme4               | Desktop     | [5db549dd99](https://linux-hardware.org/?probe=5db549dd99) | Dec 17, 2023 |
| Medion        | E6214                       | Notebook    | [5269b6e576](https://linux-hardware.org/?probe=5269b6e576) | Dec 17, 2023 |
| MSI           | MAG X570S TORPEDO MAX       | Desktop     | [3a10e23529](https://linux-hardware.org/?probe=3a10e23529) | Dec 17, 2023 |
| Medion        | B660H7-M20                  | Desktop     | [749b3e49ca](https://linux-hardware.org/?probe=749b3e49ca) | Dec 17, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [378b82ce2f](https://linux-hardware.org/?probe=378b82ce2f) | Dec 17, 2023 |
| ASRock        | H61M-DGS R2.0               | Desktop     | [b8bef59357](https://linux-hardware.org/?probe=b8bef59357) | Dec 17, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [02fb9a3f3b](https://linux-hardware.org/?probe=02fb9a3f3b) | Dec 17, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [d3e1291358](https://linux-hardware.org/?probe=d3e1291358) | Dec 17, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [e7f9b37ee3](https://linux-hardware.org/?probe=e7f9b37ee3) | Dec 17, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [935f688c90](https://linux-hardware.org/?probe=935f688c90) | Dec 17, 2023 |
| ASRock        | H61M-DGS R2.0               | Desktop     | [d60c1bd23e](https://linux-hardware.org/?probe=d60c1bd23e) | Dec 17, 2023 |
| ASRock        | H61M-DGS R2.0               | Desktop     | [f627f950ab](https://linux-hardware.org/?probe=f627f950ab) | Dec 17, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [f53d129b3d](https://linux-hardware.org/?probe=f53d129b3d) | Dec 17, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [ce0e0e1bc1](https://linux-hardware.org/?probe=ce0e0e1bc1) | Dec 17, 2023 |
| HP            | 2B5B                        | Desktop     | [fb3877b170](https://linux-hardware.org/?probe=fb3877b170) | Dec 17, 2023 |
| Lenovo        | ThinkPad W530 24491D1       | Notebook    | [bab70d44b1](https://linux-hardware.org/?probe=bab70d44b1) | Dec 17, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [a5e443e89c](https://linux-hardware.org/?probe=a5e443e89c) | Dec 17, 2023 |
| Medion        | TJ4125                      | Desktop     | [7556d73046](https://linux-hardware.org/?probe=7556d73046) | Dec 17, 2023 |
| HP            | ProBook 430 G4              | Notebook    | [253da93459](https://linux-hardware.org/?probe=253da93459) | Dec 17, 2023 |
| Apple         | Mac-F42787C8 PVT            | All in one  | [ef50f10d1f](https://linux-hardware.org/?probe=ef50f10d1f) | Dec 17, 2023 |
| Fujitsu       | LIFEBOOK U749               | Notebook    | [4ede8e182e](https://linux-hardware.org/?probe=4ede8e182e) | Dec 17, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [4d81e6300c](https://linux-hardware.org/?probe=4d81e6300c) | Dec 17, 2023 |
| ASUSTek       | X550LD                      | Notebook    | [f46b47b272](https://linux-hardware.org/?probe=f46b47b272) | Dec 16, 2023 |
| Lenovo        | ThinkPad X230 2325BA3       | Notebook    | [1c573f00c0](https://linux-hardware.org/?probe=1c573f00c0) | Dec 16, 2023 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [8bb410ae42](https://linux-hardware.org/?probe=8bb410ae42) | Dec 16, 2023 |
| Acer          | Aspire V5-573G              | Notebook    | [723eb61284](https://linux-hardware.org/?probe=723eb61284) | Dec 16, 2023 |
| MSI           | Z97-G43                     | Desktop     | [84486f678f](https://linux-hardware.org/?probe=84486f678f) | Dec 16, 2023 |
| HP            | ProBook 455 15.6 inch G1... | Notebook    | [56e1b0ed26](https://linux-hardware.org/?probe=56e1b0ed26) | Dec 16, 2023 |
| Lenovo        | ThinkPad T14 Gen 4 21K3C... | Notebook    | [66a8c2ad4c](https://linux-hardware.org/?probe=66a8c2ad4c) | Dec 16, 2023 |
| Medion        | E6214                       | Notebook    | [806be57bd5](https://linux-hardware.org/?probe=806be57bd5) | Dec 16, 2023 |
| Dell          | 08WKV3 A00                  | Desktop     | [75274d24c0](https://linux-hardware.org/?probe=75274d24c0) | Dec 16, 2023 |
| HP            | ProBook 430 G4              | Notebook    | [30f8fe050c](https://linux-hardware.org/?probe=30f8fe050c) | Dec 16, 2023 |
| AWOW          | Unknown                     | Notebook    | [7061726896](https://linux-hardware.org/?probe=7061726896) | Dec 16, 2023 |
| Acer          | Aspire 6920                 | Notebook    | [716c31a854](https://linux-hardware.org/?probe=716c31a854) | Dec 16, 2023 |
| Sony          | VGN-FW51MF_H                | Notebook    | [5cb2ea3418](https://linux-hardware.org/?probe=5cb2ea3418) | Dec 16, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [0aa5382212](https://linux-hardware.org/?probe=0aa5382212) | Dec 16, 2023 |
| ASUSTek       | X555LD                      | Notebook    | [109311067f](https://linux-hardware.org/?probe=109311067f) | Dec 16, 2023 |
| Dell          | Inspiron 7520               | Notebook    | [5614a9077e](https://linux-hardware.org/?probe=5614a9077e) | Dec 16, 2023 |
| MSI           | MPG Z490 GAMING PLUS        | Desktop     | [faf62fd1be](https://linux-hardware.org/?probe=faf62fd1be) | Dec 16, 2023 |
| Lenovo        | V17 G3 IAP 82U1             | Notebook    | [2598a81fd9](https://linux-hardware.org/?probe=2598a81fd9) | Dec 16, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [72b7f2d771](https://linux-hardware.org/?probe=72b7f2d771) | Dec 16, 2023 |
| Apple         | MacBookPro10,2              | Notebook    | [01713ad0b4](https://linux-hardware.org/?probe=01713ad0b4) | Dec 16, 2023 |
| ASUSTek       | K50AF                       | Notebook    | [2d4a3c6859](https://linux-hardware.org/?probe=2d4a3c6859) | Dec 16, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [32af19e996](https://linux-hardware.org/?probe=32af19e996) | Dec 16, 2023 |
| Fujitsu       | D3513-A1 S26361-D3513-A1    | Desktop     | [6f4f0f65bb](https://linux-hardware.org/?probe=6f4f0f65bb) | Dec 15, 2023 |
| Medion        | E6417 MD99252               | Notebook    | [26e9c2ba0c](https://linux-hardware.org/?probe=26e9c2ba0c) | Dec 15, 2023 |
| Lenovo        | IdeaPad 320-17IKB 81BJ      | Notebook    | [2d3b97c04a](https://linux-hardware.org/?probe=2d3b97c04a) | Dec 15, 2023 |
| Lenovo        | ThinkPad P1 20MDS02BGE      | Notebook    | [65eb962233](https://linux-hardware.org/?probe=65eb962233) | Dec 15, 2023 |
| VIA Techno... | AMOS-3005                   | Desktop     | [10cf5bf932](https://linux-hardware.org/?probe=10cf5bf932) | Dec 15, 2023 |
| VIA Techno... | AMOS-3005                   | Desktop     | [0af62d144a](https://linux-hardware.org/?probe=0af62d144a) | Dec 15, 2023 |
| ASUSTek       | X705UAR                     | Notebook    | [0ab56df890](https://linux-hardware.org/?probe=0ab56df890) | Dec 15, 2023 |
| MSI           | Z77A-GD65                   | Desktop     | [61b10e308f](https://linux-hardware.org/?probe=61b10e308f) | Dec 15, 2023 |
| ASUSTek       | X705UAR                     | Notebook    | [9f0e2069b1](https://linux-hardware.org/?probe=9f0e2069b1) | Dec 15, 2023 |
| Shenzhen M... | AHBNB OEM                   | Desktop     | [1fae1d3423](https://linux-hardware.org/?probe=1fae1d3423) | Dec 15, 2023 |
| HP            | Pavilion g6                 | Notebook    | [7863fae702](https://linux-hardware.org/?probe=7863fae702) | Dec 15, 2023 |
| Shenzhen M... | AHBNB OEM                   | Desktop     | [1a70a13ff4](https://linux-hardware.org/?probe=1a70a13ff4) | Dec 15, 2023 |
| Shenzhen M... | AHBNB OEM                   | Desktop     | [8be30808ec](https://linux-hardware.org/?probe=8be30808ec) | Dec 15, 2023 |
| Shenzhen M... | AHBNB OEM                   | Desktop     | [1e0ba866f7](https://linux-hardware.org/?probe=1e0ba866f7) | Dec 15, 2023 |
| Shenzhen M... | F7BSC                       | Mini pc     | [1b9fdf3844](https://linux-hardware.org/?probe=1b9fdf3844) | Dec 15, 2023 |
| Toshiba       | Satellite C70D-A            | Notebook    | [88b5dab876](https://linux-hardware.org/?probe=88b5dab876) | Dec 15, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 6 2... | Convertible | [2b72d3f4a1](https://linux-hardware.org/?probe=2b72d3f4a1) | Dec 15, 2023 |
| Intel         | NUC7i5BNB J31144-310        | Mini pc     | [035b37d481](https://linux-hardware.org/?probe=035b37d481) | Dec 15, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [618978da16](https://linux-hardware.org/?probe=618978da16) | Dec 15, 2023 |
| TUXEDO        | Pulse 15 Gen2               | Notebook    | [93fea0297b](https://linux-hardware.org/?probe=93fea0297b) | Dec 15, 2023 |
| Valve         | Galileo                     | Notebook    | [cd8b629d23](https://linux-hardware.org/?probe=cd8b629d23) | Dec 15, 2023 |
| HP            | Laptop 17-bs1xx             | Notebook    | [ef29718fd5](https://linux-hardware.org/?probe=ef29718fd5) | Dec 15, 2023 |
| Gigabyte      | MZAPLBP-00                  | Desktop     | [3935358dce](https://linux-hardware.org/?probe=3935358dce) | Dec 15, 2023 |
| Lenovo        | 312D NOK                    | Mini pc     | [fb32a1a82e](https://linux-hardware.org/?probe=fb32a1a82e) | Dec 15, 2023 |
| Razer         | Blade 17 (2022) - RZ09-0... | Notebook    | [88ffce598c](https://linux-hardware.org/?probe=88ffce598c) | Dec 15, 2023 |
| Medion        | Akoya E7226                 | Notebook    | [a8677e8420](https://linux-hardware.org/?probe=a8677e8420) | Dec 15, 2023 |
| Medion        | Akoya E7226                 | Notebook    | [059918d809](https://linux-hardware.org/?probe=059918d809) | Dec 15, 2023 |
| Acer          | Aspire 5741G                | Notebook    | [2c456f017e](https://linux-hardware.org/?probe=2c456f017e) | Dec 15, 2023 |
| Acer          | Aspire 5741G                | Notebook    | [6aed980ba9](https://linux-hardware.org/?probe=6aed980ba9) | Dec 15, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [47f91c735f](https://linux-hardware.org/?probe=47f91c735f) | Dec 15, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U30... | Notebook    | [9fa07d2004](https://linux-hardware.org/?probe=9fa07d2004) | Dec 14, 2023 |
| Dell          | Precision M6800             | Notebook    | [c3ff8fa4c5](https://linux-hardware.org/?probe=c3ff8fa4c5) | Dec 14, 2023 |
| Dell          | Inspiron 3793               | Notebook    | [90804693a6](https://linux-hardware.org/?probe=90804693a6) | Dec 14, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | Notebook    | [cf35bfbdf4](https://linux-hardware.org/?probe=cf35bfbdf4) | Dec 14, 2023 |
| Lenovo        | ThinkPad SL510 28477MG      | Notebook    | [7a1dc9b889](https://linux-hardware.org/?probe=7a1dc9b889) | Dec 14, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [69e37f3d93](https://linux-hardware.org/?probe=69e37f3d93) | Dec 14, 2023 |
| ASUSTek       | ROG Strix G713QE_G713QE     | Notebook    | [de24d459c5](https://linux-hardware.org/?probe=de24d459c5) | Dec 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [9fb745d9fe](https://linux-hardware.org/?probe=9fb745d9fe) | Dec 14, 2023 |
| Lenovo        | SDK0J40700 WIN              | Desktop     | [48c963a11d](https://linux-hardware.org/?probe=48c963a11d) | Dec 14, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | Notebook    | [0b08ee22d8](https://linux-hardware.org/?probe=0b08ee22d8) | Dec 14, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING       | Desktop     | [2982c2a2c6](https://linux-hardware.org/?probe=2982c2a2c6) | Dec 14, 2023 |
| Lenovo        | ThinkPad T440s 20ARS0HC0... | Notebook    | [3aa9eb82fb](https://linux-hardware.org/?probe=3aa9eb82fb) | Dec 14, 2023 |
| ASUSTek       | X555LD                      | Notebook    | [9609ed5138](https://linux-hardware.org/?probe=9609ed5138) | Dec 14, 2023 |
| Fujitsu       | LIFEBOOK A357               | Notebook    | [b537ee14db](https://linux-hardware.org/?probe=b537ee14db) | Dec 14, 2023 |
| Acidanther... | Mac-63001698E7A34814 iMa... | All in one  | [7b96685bff](https://linux-hardware.org/?probe=7b96685bff) | Dec 14, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [0d0165957f](https://linux-hardware.org/?probe=0d0165957f) | Dec 14, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [ba4e95a15e](https://linux-hardware.org/?probe=ba4e95a15e) | Dec 13, 2023 |
| Acer          | TMP645-M                    | Notebook    | [bd22eef09b](https://linux-hardware.org/?probe=bd22eef09b) | Dec 13, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [9c3e8b880d](https://linux-hardware.org/?probe=9c3e8b880d) | Dec 13, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [e101fc39e2](https://linux-hardware.org/?probe=e101fc39e2) | Dec 13, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [c132a249e4](https://linux-hardware.org/?probe=c132a249e4) | Dec 13, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [5d1e9e6d47](https://linux-hardware.org/?probe=5d1e9e6d47) | Dec 13, 2023 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [7762e5b295](https://linux-hardware.org/?probe=7762e5b295) | Dec 13, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [913708c3f0](https://linux-hardware.org/?probe=913708c3f0) | Dec 13, 2023 |
| ASUSTek       | X55C                        | Notebook    | [13f3dbcb5f](https://linux-hardware.org/?probe=13f3dbcb5f) | Dec 13, 2023 |
| Fujitsu       | LIFEBOOK S762               | Notebook    | [9d192a95d8](https://linux-hardware.org/?probe=9d192a95d8) | Dec 13, 2023 |
| Fujitsu       | LIFEBOOK S762               | Notebook    | [19e6b5a871](https://linux-hardware.org/?probe=19e6b5a871) | Dec 13, 2023 |
| ASUSTek       | K50AF                       | Notebook    | [00e0b6dc86](https://linux-hardware.org/?probe=00e0b6dc86) | Dec 13, 2023 |
| Lenovo        | ThinkBook 14s Yoga G3 IR... | Convertible | [9849663265](https://linux-hardware.org/?probe=9849663265) | Dec 13, 2023 |
| LG Electro... | 16Z90R-G.AA76G              | Notebook    | [1e83ee89e2](https://linux-hardware.org/?probe=1e83ee89e2) | Dec 13, 2023 |
| HP            | 18E9                        | Desktop     | [ab47a5d40b](https://linux-hardware.org/?probe=ab47a5d40b) | Dec 13, 2023 |
| ASRock        | A620M Pro RS WiFi           | Desktop     | [069de62879](https://linux-hardware.org/?probe=069de62879) | Dec 13, 2023 |
| HP            | 18E5                        | Desktop     | [8195da7520](https://linux-hardware.org/?probe=8195da7520) | Dec 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [4a5e5bbe29](https://linux-hardware.org/?probe=4a5e5bbe29) | Dec 13, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [edab90dec9](https://linux-hardware.org/?probe=edab90dec9) | Dec 13, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [f9933769ef](https://linux-hardware.org/?probe=f9933769ef) | Dec 13, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [963ff854d9](https://linux-hardware.org/?probe=963ff854d9) | Dec 13, 2023 |
| Fujitsu       | LIFEBOOK S792               | Notebook    | [811be0cce0](https://linux-hardware.org/?probe=811be0cce0) | Dec 13, 2023 |
| MSI           | Z77A-GD65                   | Desktop     | [ce6556590b](https://linux-hardware.org/?probe=ce6556590b) | Dec 13, 2023 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [60461068e8](https://linux-hardware.org/?probe=60461068e8) | Dec 13, 2023 |
| ASUSTek       | X556UQK                     | Notebook    | [1ac3287ee1](https://linux-hardware.org/?probe=1ac3287ee1) | Dec 13, 2023 |
| HP            | 8169                        | Desktop     | [e0549dcc03](https://linux-hardware.org/?probe=e0549dcc03) | Dec 12, 2023 |
| Gigabyte      | MZAPLBP-00                  | Desktop     | [fdb303e7e6](https://linux-hardware.org/?probe=fdb303e7e6) | Dec 12, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [5d09e206ea](https://linux-hardware.org/?probe=5d09e206ea) | Dec 12, 2023 |
| Lenovo        | Annapurna CRB NOK           | Desktop     | [2207f3a9a1](https://linux-hardware.org/?probe=2207f3a9a1) | Dec 12, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [8151ecbeef](https://linux-hardware.org/?probe=8151ecbeef) | Dec 12, 2023 |
| Lenovo        | ThinkPad P1 20MD0001GE      | Notebook    | [e4c9202751](https://linux-hardware.org/?probe=e4c9202751) | Dec 12, 2023 |
| Lenovo        | ThinkPad P1 20MD0001GE      | Notebook    | [5662ef46db](https://linux-hardware.org/?probe=5662ef46db) | Dec 12, 2023 |
| Lenovo        | 30BB SDK0J40709 WIN 3259... | All in one  | [9d9d96201b](https://linux-hardware.org/?probe=9d9d96201b) | Dec 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [27b99be924](https://linux-hardware.org/?probe=27b99be924) | Dec 12, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [97ca767d40](https://linux-hardware.org/?probe=97ca767d40) | Dec 12, 2023 |
| Lenovo        | NO DPK                      | Desktop     | [2204183295](https://linux-hardware.org/?probe=2204183295) | Dec 12, 2023 |
| Intel         | NUC7i7DNB J83500-205        | Mini pc     | [1ef755944c](https://linux-hardware.org/?probe=1ef755944c) | Dec 12, 2023 |
| Intel         | NUC7i7DNB J83500-205        | Mini pc     | [e4fcf233c5](https://linux-hardware.org/?probe=e4fcf233c5) | Dec 12, 2023 |
| Fujitsu       | LIFEBOOK T902               | Notebook    | [da78a4dd31](https://linux-hardware.org/?probe=da78a4dd31) | Dec 12, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [8f2db425db](https://linux-hardware.org/?probe=8f2db425db) | Dec 12, 2023 |
| Sony          | SVE1713A1EW                 | Notebook    | [64b473222e](https://linux-hardware.org/?probe=64b473222e) | Dec 12, 2023 |
| Foxconn       | TPS01                       | Desktop     | [a417ff19ae](https://linux-hardware.org/?probe=a417ff19ae) | Dec 12, 2023 |
| Lenovo        | ThinkPad X250 20CM001PGE    | Notebook    | [920f198d61](https://linux-hardware.org/?probe=920f198d61) | Dec 12, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [e33caa2659](https://linux-hardware.org/?probe=e33caa2659) | Dec 12, 2023 |
| Acer          | Extensa 215-55              | Notebook    | [40eaa33887](https://linux-hardware.org/?probe=40eaa33887) | Dec 12, 2023 |
| Fujitsu       | LIFEBOOK T902               | Notebook    | [dff662b36c](https://linux-hardware.org/?probe=dff662b36c) | Dec 12, 2023 |
| MSI           | A320M PRO-VD/S              | Desktop     | [c2a6947086](https://linux-hardware.org/?probe=c2a6947086) | Dec 12, 2023 |
| Inter Sale... | NID-11125DE                 | Notebook    | [373498e89a](https://linux-hardware.org/?probe=373498e89a) | Dec 12, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [9936eed724](https://linux-hardware.org/?probe=9936eed724) | Dec 12, 2023 |
| Fujitsu       | LIFEBOOK E548               | Notebook    | [235ca8a477](https://linux-hardware.org/?probe=235ca8a477) | Dec 12, 2023 |
| Acer          | Aspire XC-705               | Desktop     | [c9193baaf8](https://linux-hardware.org/?probe=c9193baaf8) | Dec 12, 2023 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | Desktop     | [0720cbce6b](https://linux-hardware.org/?probe=0720cbce6b) | Dec 12, 2023 |
| Lenovo        | ThinkPad T480s 20L8S5LK0... | Notebook    | [e8ebbc8111](https://linux-hardware.org/?probe=e8ebbc8111) | Dec 12, 2023 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [f779186ae7](https://linux-hardware.org/?probe=f779186ae7) | Dec 11, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [8b80683b06](https://linux-hardware.org/?probe=8b80683b06) | Dec 11, 2023 |
| ASRock        | B85M Pro4                   | Desktop     | [8a11fe8107](https://linux-hardware.org/?probe=8a11fe8107) | Dec 11, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [627ee4cb32](https://linux-hardware.org/?probe=627ee4cb32) | Dec 11, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [c832a59f37](https://linux-hardware.org/?probe=c832a59f37) | Dec 11, 2023 |
| MSI           | Z170-A PRO                  | Desktop     | [8d77ff0fe8](https://linux-hardware.org/?probe=8d77ff0fe8) | Dec 11, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [8a8dc0ce48](https://linux-hardware.org/?probe=8a8dc0ce48) | Dec 11, 2023 |
| Acer          | Aspire A515-52G             | Notebook    | [c6ac91a53c](https://linux-hardware.org/?probe=c6ac91a53c) | Dec 11, 2023 |
| ASUSTek       | ZenBook UX482EG_UX482EG     | Notebook    | [a644fcc63e](https://linux-hardware.org/?probe=a644fcc63e) | Dec 11, 2023 |
| Gigabyte      | Z790 GAMING X AX            | Desktop     | [8617acecda](https://linux-hardware.org/?probe=8617acecda) | Dec 11, 2023 |
| Lenovo        | ThinkPad X201 3626GWG       | Notebook    | [023f7dd390](https://linux-hardware.org/?probe=023f7dd390) | Dec 11, 2023 |
| Acer          | Aspire 7520                 | Notebook    | [70405c9fa1](https://linux-hardware.org/?probe=70405c9fa1) | Dec 10, 2023 |
| Lenovo        | 312D NOK                    | Mini pc     | [0c0de57a07](https://linux-hardware.org/?probe=0c0de57a07) | Dec 10, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [ee7a9f7ba7](https://linux-hardware.org/?probe=ee7a9f7ba7) | Dec 10, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [1e3585333b](https://linux-hardware.org/?probe=1e3585333b) | Dec 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [4c6cd4453d](https://linux-hardware.org/?probe=4c6cd4453d) | Dec 10, 2023 |
| Dell          | Latitude E6410              | Notebook    | [0b8db8ccee](https://linux-hardware.org/?probe=0b8db8ccee) | Dec 10, 2023 |
| Sony          | VGN-AR51M                   | Notebook    | [d1c67ac651](https://linux-hardware.org/?probe=d1c67ac651) | Dec 10, 2023 |
| Lenovo        | ThinkPad T530 2429W1E       | Notebook    | [02a4811e8d](https://linux-hardware.org/?probe=02a4811e8d) | Dec 10, 2023 |
| ASRock        | A520M-HVS                   | Desktop     | [5d07d03602](https://linux-hardware.org/?probe=5d07d03602) | Dec 10, 2023 |
| HP            | Laptop 14-bs0xx             | Notebook    | [f096c75cf9](https://linux-hardware.org/?probe=f096c75cf9) | Dec 10, 2023 |
| HP            | Laptop 17-cn3xxx            | Notebook    | [7a93c4b54c](https://linux-hardware.org/?probe=7a93c4b54c) | Dec 10, 2023 |
| Acer          | Nitro AN517-41              | Notebook    | [6e5abc0ea5](https://linux-hardware.org/?probe=6e5abc0ea5) | Dec 10, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | Notebook    | [2ba6a00229](https://linux-hardware.org/?probe=2ba6a00229) | Dec 10, 2023 |
| MSI           | MS-7516                     | Desktop     | [bafee6f86e](https://linux-hardware.org/?probe=bafee6f86e) | Dec 10, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [5522722e53](https://linux-hardware.org/?probe=5522722e53) | Dec 10, 2023 |
| Lenovo        | Bantry CRB SDK0J40709 WI... | All in one  | [1acdbb1c74](https://linux-hardware.org/?probe=1acdbb1c74) | Dec 10, 2023 |
| Lenovo        | ThinkPad T440p 20ANCTO1W... | Notebook    | [070ba5c3c1](https://linux-hardware.org/?probe=070ba5c3c1) | Dec 10, 2023 |
| Lenovo        | Bantry CRB SDK0J40709 WI... | All in one  | [def1d2da47](https://linux-hardware.org/?probe=def1d2da47) | Dec 10, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [6c3916c3fa](https://linux-hardware.org/?probe=6c3916c3fa) | Dec 10, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [1e96233f59](https://linux-hardware.org/?probe=1e96233f59) | Dec 10, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [52e1cb6958](https://linux-hardware.org/?probe=52e1cb6958) | Dec 10, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [530b8a868e](https://linux-hardware.org/?probe=530b8a868e) | Dec 10, 2023 |
| Acer          | Spin SP513-51               | Convertible | [654c8b4199](https://linux-hardware.org/?probe=654c8b4199) | Dec 10, 2023 |
| HP            | 2AF7                        | Desktop     | [e7a6fd7a82](https://linux-hardware.org/?probe=e7a6fd7a82) | Dec 10, 2023 |
| Dell          | Latitude E6400              | Notebook    | [c23aa9b02a](https://linux-hardware.org/?probe=c23aa9b02a) | Dec 10, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [3cfc2b72b4](https://linux-hardware.org/?probe=3cfc2b72b4) | Dec 10, 2023 |
| BESSTAR Te... | HM90                        | Desktop     | [6d805d9e86](https://linux-hardware.org/?probe=6d805d9e86) | Dec 10, 2023 |
| ASUSTek       | M4N68T-M-LE-V2              | Desktop     | [e126cdbf4b](https://linux-hardware.org/?probe=e126cdbf4b) | Dec 10, 2023 |
| ASRock        | B760M PG Riptide            | Desktop     | [ef47cf6d30](https://linux-hardware.org/?probe=ef47cf6d30) | Dec 10, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | Notebook    | [d906394ed7](https://linux-hardware.org/?probe=d906394ed7) | Dec 10, 2023 |
| ASUSTek       | P8Z77-V DELUXE              | Desktop     | [6e57197ce6](https://linux-hardware.org/?probe=6e57197ce6) | Dec 10, 2023 |
| Intel         | NUC10i5FNB K61361-305       | Mini pc     | [87b9071f4a](https://linux-hardware.org/?probe=87b9071f4a) | Dec 10, 2023 |
| Dell          | Inspiron 7559               | Notebook    | [3f4af9bbdd](https://linux-hardware.org/?probe=3f4af9bbdd) | Dec 10, 2023 |
| Lenovo        | ThinkPad T480 20L6S4G700    | Notebook    | [a1ebdec411](https://linux-hardware.org/?probe=a1ebdec411) | Dec 10, 2023 |
| Inventec      | DQ Class A02                | Desktop     | [8e1c466924](https://linux-hardware.org/?probe=8e1c466924) | Dec 09, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | Notebook    | [2bc305a065](https://linux-hardware.org/?probe=2bc305a065) | Dec 09, 2023 |
| MSI           | Katana GF66 11UE            | Notebook    | [451c5731ae](https://linux-hardware.org/?probe=451c5731ae) | Dec 09, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [296e90c442](https://linux-hardware.org/?probe=296e90c442) | Dec 09, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [cea0431bcb](https://linux-hardware.org/?probe=cea0431bcb) | Dec 09, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [3bca387137](https://linux-hardware.org/?probe=3bca387137) | Dec 09, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [09e302c4ab](https://linux-hardware.org/?probe=09e302c4ab) | Dec 09, 2023 |
| ASRock        | A520M-HDV                   | Desktop     | [c274f291c4](https://linux-hardware.org/?probe=c274f291c4) | Dec 09, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [be35efa2be](https://linux-hardware.org/?probe=be35efa2be) | Dec 09, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [d129c3b01f](https://linux-hardware.org/?probe=d129c3b01f) | Dec 09, 2023 |
| Razer         | Blade                       | Notebook    | [bf9ad5f7df](https://linux-hardware.org/?probe=bf9ad5f7df) | Dec 09, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [140789380e](https://linux-hardware.org/?probe=140789380e) | Dec 09, 2023 |
| Gigabyte      | G5 GE                       | Notebook    | [e63d83327b](https://linux-hardware.org/?probe=e63d83327b) | Dec 09, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [c02997fc15](https://linux-hardware.org/?probe=c02997fc15) | Dec 09, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [f4033fbe79](https://linux-hardware.org/?probe=f4033fbe79) | Dec 09, 2023 |
| Medion        | P8614                       | Notebook    | [a7689ec115](https://linux-hardware.org/?probe=a7689ec115) | Dec 09, 2023 |
| Biostar       | A10N-8800E                  | Desktop     | [283ae39c42](https://linux-hardware.org/?probe=283ae39c42) | Dec 09, 2023 |
| Samsung       | 90X3A                       | Notebook    | [45697431c1](https://linux-hardware.org/?probe=45697431c1) | Dec 09, 2023 |
| Wortmann      | 1220561_1470059             | Tablet      | [dd7d907141](https://linux-hardware.org/?probe=dd7d907141) | Dec 09, 2023 |
| HP            | Pavilion 15                 | Notebook    | [8041cb2da6](https://linux-hardware.org/?probe=8041cb2da6) | Dec 09, 2023 |
| Fujitsu Si... | LIFEBOOK T5010              | Notebook    | [7a66cc4016](https://linux-hardware.org/?probe=7a66cc4016) | Dec 09, 2023 |
| AZW           | GTR V02                     | Desktop     | [ece705bc91](https://linux-hardware.org/?probe=ece705bc91) | Dec 09, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [d4958d9e5e](https://linux-hardware.org/?probe=d4958d9e5e) | Dec 09, 2023 |
| ASRock        | A620M Pro RS WiFi           | Desktop     | [3bbc394b2e](https://linux-hardware.org/?probe=3bbc394b2e) | Dec 08, 2023 |
| MSI           | Katana 17 B13VGK            | Notebook    | [e91a23fa88](https://linux-hardware.org/?probe=e91a23fa88) | Dec 08, 2023 |
| TUXEDO        | U931                        | Notebook    | [a73533a163](https://linux-hardware.org/?probe=a73533a163) | Dec 08, 2023 |
| Intel         | DH67CL AAG10212-206         | Desktop     | [957289310d](https://linux-hardware.org/?probe=957289310d) | Dec 08, 2023 |
| ASUSTek       | TUF Gaming B760M-PLUS       | Desktop     | [a6d71c281f](https://linux-hardware.org/?probe=a6d71c281f) | Dec 08, 2023 |
| Acer          | Aspire A517-53G             | Notebook    | [11208976d5](https://linux-hardware.org/?probe=11208976d5) | Dec 08, 2023 |
| Sony          | SVE1713Q1EB                 | Notebook    | [482c83143b](https://linux-hardware.org/?probe=482c83143b) | Dec 08, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [beb5466523](https://linux-hardware.org/?probe=beb5466523) | Dec 08, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [7267af3f34](https://linux-hardware.org/?probe=7267af3f34) | Dec 08, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [8d7f7aebab](https://linux-hardware.org/?probe=8d7f7aebab) | Dec 08, 2023 |
| Intel         | NUC7JYB J67969-405          | Mini pc     | [4f2070eb15](https://linux-hardware.org/?probe=4f2070eb15) | Dec 08, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [69df0251d9](https://linux-hardware.org/?probe=69df0251d9) | Dec 08, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [07f1a6b2f7](https://linux-hardware.org/?probe=07f1a6b2f7) | Dec 08, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [e3b462d63d](https://linux-hardware.org/?probe=e3b462d63d) | Dec 08, 2023 |
| ASRock        | A520M-HDV                   | Desktop     | [8c7f7f9b91](https://linux-hardware.org/?probe=8c7f7f9b91) | Dec 08, 2023 |
| Dell          | Inspiron MM061              | Notebook    | [213b775f8b](https://linux-hardware.org/?probe=213b775f8b) | Dec 08, 2023 |
| Gigabyte      | AB350M-DS3H-CF              | Desktop     | [307525b07f](https://linux-hardware.org/?probe=307525b07f) | Dec 08, 2023 |
| Dell          | Inspiron MM061              | Notebook    | [d4c43fe4f4](https://linux-hardware.org/?probe=d4c43fe4f4) | Dec 08, 2023 |
| Hardkernel    | ODROID-M1                   | Soc         | [39d65538cb](https://linux-hardware.org/?probe=39d65538cb) | Dec 08, 2023 |
| MSI           | GF615M-P33                  | Desktop     | [577b12bc67](https://linux-hardware.org/?probe=577b12bc67) | Dec 08, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [d20dcc81df](https://linux-hardware.org/?probe=d20dcc81df) | Dec 08, 2023 |
| HP            | Compaq 6730b (NB034ET#UU... | Notebook    | [88c39cda86](https://linux-hardware.org/?probe=88c39cda86) | Dec 08, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [0677dbe5ce](https://linux-hardware.org/?probe=0677dbe5ce) | Dec 08, 2023 |
| HP            | ZBook 15v G5                | Notebook    | [96133249d0](https://linux-hardware.org/?probe=96133249d0) | Dec 08, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [dfd1f871b8](https://linux-hardware.org/?probe=dfd1f871b8) | Dec 08, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [3cdaec0eab](https://linux-hardware.org/?probe=3cdaec0eab) | Dec 07, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [4efdc6d768](https://linux-hardware.org/?probe=4efdc6d768) | Dec 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | Notebook    | [2eb0717bf1](https://linux-hardware.org/?probe=2eb0717bf1) | Dec 07, 2023 |
| Biostar       | A10N-8800E                  | Desktop     | [b56d3e163b](https://linux-hardware.org/?probe=b56d3e163b) | Dec 07, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e0f14fb199](https://linux-hardware.org/?probe=e0f14fb199) | Dec 07, 2023 |
| HP            | 18E9                        | Desktop     | [80f4acdcfd](https://linux-hardware.org/?probe=80f4acdcfd) | Dec 07, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [9da65cd80e](https://linux-hardware.org/?probe=9da65cd80e) | Dec 07, 2023 |
| Dell          | Latitude E5540              | Notebook    | [208d70d734](https://linux-hardware.org/?probe=208d70d734) | Dec 07, 2023 |
| Acer          | Aspire 7730G                | Notebook    | [c98f96bcc1](https://linux-hardware.org/?probe=c98f96bcc1) | Dec 07, 2023 |
| MSI           | Z270 GAMING M3              | Desktop     | [68bd979ae6](https://linux-hardware.org/?probe=68bd979ae6) | Dec 07, 2023 |
| Lenovo        | ThinkPad T460s 20FAS30D0... | Notebook    | [87477ed836](https://linux-hardware.org/?probe=87477ed836) | Dec 07, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [04dd7cde77](https://linux-hardware.org/?probe=04dd7cde77) | Dec 07, 2023 |
| ASUSTek       | Z170-P                      | Desktop     | [d15f2a367c](https://linux-hardware.org/?probe=d15f2a367c) | Dec 07, 2023 |
| Fujitsu       | LIFEBOOK T938               | Convertible | [f89566b3c7](https://linux-hardware.org/?probe=f89566b3c7) | Dec 07, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [f85ac7ef66](https://linux-hardware.org/?probe=f85ac7ef66) | Dec 07, 2023 |
| Lenovo        | ThinkPad T480s 20L7001LM... | Notebook    | [37c62fe0ba](https://linux-hardware.org/?probe=37c62fe0ba) | Dec 07, 2023 |
| HONOR         | HGF-WX6                     | Notebook    | [0ba74f97d0](https://linux-hardware.org/?probe=0ba74f97d0) | Dec 07, 2023 |
| Lenovo        | ThinkPad T540p 20BFS2600... | Notebook    | [b6ec0a5c30](https://linux-hardware.org/?probe=b6ec0a5c30) | Dec 07, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [13080ba71b](https://linux-hardware.org/?probe=13080ba71b) | Dec 07, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [3939d82727](https://linux-hardware.org/?probe=3939d82727) | Dec 07, 2023 |
| HP            | ZBook Power 15.6 inch G1... | Notebook    | [c58925365b](https://linux-hardware.org/?probe=c58925365b) | Dec 07, 2023 |
| Valve         | Jupiter                     | Notebook    | [1a0ea506dc](https://linux-hardware.org/?probe=1a0ea506dc) | Dec 07, 2023 |
| Medion        | Unknown                     | Notebook    | [58a27e1f8f](https://linux-hardware.org/?probe=58a27e1f8f) | Dec 07, 2023 |
| HP            | 21B4 A01                    | Desktop     | [a8f5a67f32](https://linux-hardware.org/?probe=a8f5a67f32) | Dec 07, 2023 |
| MSI           | MEG X570 ACE                | Desktop     | [18c7fcf897](https://linux-hardware.org/?probe=18c7fcf897) | Dec 06, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [dcb3b62f73](https://linux-hardware.org/?probe=dcb3b62f73) | Dec 06, 2023 |
| ASUSTek       | M4A87TD EVO                 | Desktop     | [58a4befaf3](https://linux-hardware.org/?probe=58a4befaf3) | Dec 06, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [600935b467](https://linux-hardware.org/?probe=600935b467) | Dec 06, 2023 |
| HP            | 83E0                        | Desktop     | [a4266f2a5e](https://linux-hardware.org/?probe=a4266f2a5e) | Dec 06, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [6623cb7bdc](https://linux-hardware.org/?probe=6623cb7bdc) | Dec 06, 2023 |
| ASUSTek       | UX510UWK                    | Notebook    | [30a7e501ad](https://linux-hardware.org/?probe=30a7e501ad) | Dec 06, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [38d0f75f20](https://linux-hardware.org/?probe=38d0f75f20) | Dec 06, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [21c49766ca](https://linux-hardware.org/?probe=21c49766ca) | Dec 06, 2023 |
| MSI           | MAG X570S TORPEDO MAX       | Desktop     | [0ab3c62102](https://linux-hardware.org/?probe=0ab3c62102) | Dec 06, 2023 |
| Acer          | Aspire E1-731               | Notebook    | [c9e518b7b9](https://linux-hardware.org/?probe=c9e518b7b9) | Dec 06, 2023 |
| Packard Be... | DOT S                       | Notebook    | [131c38200b](https://linux-hardware.org/?probe=131c38200b) | Dec 06, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | Notebook    | [280a9a93e6](https://linux-hardware.org/?probe=280a9a93e6) | Dec 06, 2023 |
| Dell          | 0F642F A00                  | Desktop     | [72a8f53afa](https://linux-hardware.org/?probe=72a8f53afa) | Dec 06, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [20c7a1d11b](https://linux-hardware.org/?probe=20c7a1d11b) | Dec 06, 2023 |
| Acer          | Aspire A517-51G             | Notebook    | [68f538dbc9](https://linux-hardware.org/?probe=68f538dbc9) | Dec 06, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [b62b670195](https://linux-hardware.org/?probe=b62b670195) | Dec 06, 2023 |
| Intel         | X79M-S                      | Desktop     | [2cec7d970f](https://linux-hardware.org/?probe=2cec7d970f) | Dec 06, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [3c1c6e89b6](https://linux-hardware.org/?probe=3c1c6e89b6) | Dec 06, 2023 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | Notebook    | [1f68b6b7c7](https://linux-hardware.org/?probe=1f68b6b7c7) | Dec 06, 2023 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [f15eca360f](https://linux-hardware.org/?probe=f15eca360f) | Dec 06, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [7d7cf8fd3d](https://linux-hardware.org/?probe=7d7cf8fd3d) | Dec 06, 2023 |
| ASUSTek       | K52Je                       | Notebook    | [3d8e6840bf](https://linux-hardware.org/?probe=3d8e6840bf) | Dec 05, 2023 |
| LG Electro... | 16Z90R-G.AA76G              | Notebook    | [5ac1d1605a](https://linux-hardware.org/?probe=5ac1d1605a) | Dec 05, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [9d4a4790f4](https://linux-hardware.org/?probe=9d4a4790f4) | Dec 05, 2023 |
| Fujitsu       | D3164-C2 S26361-D3164-C2    | Desktop     | [2c7e824ceb](https://linux-hardware.org/?probe=2c7e824ceb) | Dec 05, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [757356c6f7](https://linux-hardware.org/?probe=757356c6f7) | Dec 05, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [b886333167](https://linux-hardware.org/?probe=b886333167) | Dec 05, 2023 |
| Schenker      | XMG NEO 15(E20, RTX 20xx... | Notebook    | [e238c1edb9](https://linux-hardware.org/?probe=e238c1edb9) | Dec 05, 2023 |
| Micro Comp... | Venus series                | Notebook    | [fab7ae9a17](https://linux-hardware.org/?probe=fab7ae9a17) | Dec 05, 2023 |
| SDZ           | X133                        | Notebook    | [6e7c008a6a](https://linux-hardware.org/?probe=6e7c008a6a) | Dec 05, 2023 |
| HP            | 3047h                       | Desktop     | [4e580a9467](https://linux-hardware.org/?probe=4e580a9467) | Dec 05, 2023 |
| Unknown       | NISB 3500                   | Desktop     | [454871dab4](https://linux-hardware.org/?probe=454871dab4) | Dec 05, 2023 |
| Alienware     | 17                          | Notebook    | [77103bfec3](https://linux-hardware.org/?probe=77103bfec3) | Dec 05, 2023 |
| ASUSTek       | ROG STRIX Z490-G GAMING     | Desktop     | [fca34ce9bc](https://linux-hardware.org/?probe=fca34ce9bc) | Dec 05, 2023 |
| Hardkernel    | Odroid XU4                  | Soc         | [8ce2d62401](https://linux-hardware.org/?probe=8ce2d62401) | Dec 05, 2023 |
| Dell          | XPS 13 9343                 | Notebook    | [d5ee40d605](https://linux-hardware.org/?probe=d5ee40d605) | Dec 05, 2023 |
| Gigabyte      | H370M DS3H-CF               | Desktop     | [332f084cba](https://linux-hardware.org/?probe=332f084cba) | Dec 05, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [53dbcd2c87](https://linux-hardware.org/?probe=53dbcd2c87) | Dec 05, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [1d99a563c9](https://linux-hardware.org/?probe=1d99a563c9) | Dec 05, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [5ec26a4bca](https://linux-hardware.org/?probe=5ec26a4bca) | Dec 05, 2023 |
| ASUSTek       | ROG Strix G814JV_G814JV     | Notebook    | [6cd3d66979](https://linux-hardware.org/?probe=6cd3d66979) | Dec 05, 2023 |
| Lenovo        | ThinkPad T580 20LAS1GG00    | Notebook    | [c592d82494](https://linux-hardware.org/?probe=c592d82494) | Dec 05, 2023 |
| MSI           | MAG B550M MORTAR            | Desktop     | [d6edae5cc8](https://linux-hardware.org/?probe=d6edae5cc8) | Dec 05, 2023 |
| Fujitsu       | LIFEBOOK A357               | Notebook    | [8725242a43](https://linux-hardware.org/?probe=8725242a43) | Dec 04, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [599d20e4ef](https://linux-hardware.org/?probe=599d20e4ef) | Dec 04, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [82dedf4be4](https://linux-hardware.org/?probe=82dedf4be4) | Dec 04, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [cfc7698579](https://linux-hardware.org/?probe=cfc7698579) | Dec 04, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [54b2e1f4f1](https://linux-hardware.org/?probe=54b2e1f4f1) | Dec 04, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [4d938aed80](https://linux-hardware.org/?probe=4d938aed80) | Dec 04, 2023 |
| Dell          | Inspiron 16 Plus 7620       | Notebook    | [969efab4b8](https://linux-hardware.org/?probe=969efab4b8) | Dec 04, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [efedef5a13](https://linux-hardware.org/?probe=efedef5a13) | Dec 04, 2023 |
| Dell          | 0RN474                      | Desktop     | [17392605bb](https://linux-hardware.org/?probe=17392605bb) | Dec 04, 2023 |
| Wortmann      | 1220657_1470295             | Notebook    | [74bac21281](https://linux-hardware.org/?probe=74bac21281) | Dec 04, 2023 |
| Valve         | Jupiter                     | Notebook    | [ea1ae6a495](https://linux-hardware.org/?probe=ea1ae6a495) | Dec 04, 2023 |
| MSI           | Z97 GAMING 7                | Desktop     | [887cbb52f3](https://linux-hardware.org/?probe=887cbb52f3) | Dec 04, 2023 |
| Dell          | XPS 13 9343                 | Notebook    | [aca11b8b22](https://linux-hardware.org/?probe=aca11b8b22) | Dec 04, 2023 |
| Lenovo        | ThinkPad L460 20FVS07C00    | Notebook    | [fd5a4dbeb9](https://linux-hardware.org/?probe=fd5a4dbeb9) | Dec 04, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [cea029e467](https://linux-hardware.org/?probe=cea029e467) | Dec 04, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [db6f924b29](https://linux-hardware.org/?probe=db6f924b29) | Dec 04, 2023 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [362161fd73](https://linux-hardware.org/?probe=362161fd73) | Dec 04, 2023 |
| Lenovo        | ThinkPad L590 20Q7001CGE    | Notebook    | [03b128fbc9](https://linux-hardware.org/?probe=03b128fbc9) | Dec 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [dcb521e9aa](https://linux-hardware.org/?probe=dcb521e9aa) | Dec 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [4800fa6c99](https://linux-hardware.org/?probe=4800fa6c99) | Dec 04, 2023 |
| HP            | Laptop 14-ma0xxx            | Notebook    | [7581ae1b5c](https://linux-hardware.org/?probe=7581ae1b5c) | Dec 04, 2023 |
| HP            | Laptop 14-ma0xxx            | Notebook    | [f42d1b765a](https://linux-hardware.org/?probe=f42d1b765a) | Dec 04, 2023 |
| ZOTAC         | NM10                        | Desktop     | [a567bbf0a7](https://linux-hardware.org/?probe=a567bbf0a7) | Dec 04, 2023 |
| Dell          | Latitude E6230              | Notebook    | [c1e6d37718](https://linux-hardware.org/?probe=c1e6d37718) | Dec 04, 2023 |
| Microsoft     | Surface Go                  | Tablet      | [3658acadc3](https://linux-hardware.org/?probe=3658acadc3) | Dec 04, 2023 |
| HP            | 255 G6 Notebook PC          | Notebook    | [626135b546](https://linux-hardware.org/?probe=626135b546) | Dec 04, 2023 |
| Lenovo        | Yoga Pro 9 14IRP8 83BU      | Notebook    | [ff7bf1a3cc](https://linux-hardware.org/?probe=ff7bf1a3cc) | Dec 04, 2023 |
| Lenovo        | Yoga Pro 9 14IRP8 83BU      | Notebook    | [1e1ea2cc1d](https://linux-hardware.org/?probe=1e1ea2cc1d) | Dec 04, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [748534900a](https://linux-hardware.org/?probe=748534900a) | Dec 04, 2023 |
| Acer          | Aspire V3-771               | Notebook    | [81184ba727](https://linux-hardware.org/?probe=81184ba727) | Dec 04, 2023 |
| HP            | 625                         | Notebook    | [b2a08fa60e](https://linux-hardware.org/?probe=b2a08fa60e) | Dec 04, 2023 |
| MSI           | H270 PC MATE                | Desktop     | [d1f25d8eb8](https://linux-hardware.org/?probe=d1f25d8eb8) | Dec 03, 2023 |
| BESSTAR Te... | UM350                       | Desktop     | [28b627c64a](https://linux-hardware.org/?probe=28b627c64a) | Dec 03, 2023 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [830b83bf5c](https://linux-hardware.org/?probe=830b83bf5c) | Dec 03, 2023 |
| ASRock        | H570 Steel Legend           | Desktop     | [e1478d8694](https://linux-hardware.org/?probe=e1478d8694) | Dec 03, 2023 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [83b954a1cd](https://linux-hardware.org/?probe=83b954a1cd) | Dec 03, 2023 |
| ASRock        | H570 Steel Legend           | Desktop     | [f1d29c75a0](https://linux-hardware.org/?probe=f1d29c75a0) | Dec 03, 2023 |
| Lenovo        | 3178 SDK0J40700 WIN 3258... | Desktop     | [e215f304c3](https://linux-hardware.org/?probe=e215f304c3) | Dec 03, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [c093780dc5](https://linux-hardware.org/?probe=c093780dc5) | Dec 03, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [b1b80bfd4e](https://linux-hardware.org/?probe=b1b80bfd4e) | Dec 03, 2023 |
| MSI           | A75MA-G55                   | Desktop     | [02a8179117](https://linux-hardware.org/?probe=02a8179117) | Dec 03, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [b052f32ef5](https://linux-hardware.org/?probe=b052f32ef5) | Dec 03, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [0ae6e0f882](https://linux-hardware.org/?probe=0ae6e0f882) | Dec 03, 2023 |
| HP            | ENVY Laptop 17-ch1xxx       | Notebook    | [595fc0137d](https://linux-hardware.org/?probe=595fc0137d) | Dec 03, 2023 |
| ASUSTek       | A88XM-PLUS                  | Desktop     | [f9a74ad44f](https://linux-hardware.org/?probe=f9a74ad44f) | Dec 03, 2023 |
| HP            | 8265                        | Desktop     | [1faa811cf0](https://linux-hardware.org/?probe=1faa811cf0) | Dec 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [e9e31f8aaa](https://linux-hardware.org/?probe=e9e31f8aaa) | Dec 03, 2023 |
| Dell          | 0HY9JP A00                  | Desktop     | [c5bdb91907](https://linux-hardware.org/?probe=c5bdb91907) | Dec 03, 2023 |
| Packard Be... | EasyNote LS11HR             | Notebook    | [c3d34dfe3a](https://linux-hardware.org/?probe=c3d34dfe3a) | Dec 03, 2023 |
| Dell          | Precision M4800             | Notebook    | [ff01ff15f9](https://linux-hardware.org/?probe=ff01ff15f9) | Dec 03, 2023 |
| ASUSTek       | X555LJ                      | Notebook    | [e8ed47af34](https://linux-hardware.org/?probe=e8ed47af34) | Dec 03, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [6fca6c7335](https://linux-hardware.org/?probe=6fca6c7335) | Dec 03, 2023 |
| ASUSTek       | STRIX Z270E GAMING          | Desktop     | [e3950352ba](https://linux-hardware.org/?probe=e3950352ba) | Dec 03, 2023 |
| HP            | Laptop 17-by0xxx            | Notebook    | [d27ace68bb](https://linux-hardware.org/?probe=d27ace68bb) | Dec 03, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [29d9e5aa67](https://linux-hardware.org/?probe=29d9e5aa67) | Dec 03, 2023 |
| Razer         | Blade 17 (2022) - RZ09-0... | Notebook    | [f4c7fc7890](https://linux-hardware.org/?probe=f4c7fc7890) | Dec 03, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [136f4b6903](https://linux-hardware.org/?probe=136f4b6903) | Dec 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [dca543f661](https://linux-hardware.org/?probe=dca543f661) | Dec 03, 2023 |
| Medion        | Unknown                     | Notebook    | [8fce2ae281](https://linux-hardware.org/?probe=8fce2ae281) | Dec 03, 2023 |
| Medion        | Unknown                     | Notebook    | [c99fd8f0b0](https://linux-hardware.org/?probe=c99fd8f0b0) | Dec 03, 2023 |
| Gigabyte      | Z390 UD                     | Desktop     | [694abd409f](https://linux-hardware.org/?probe=694abd409f) | Dec 03, 2023 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [a86f7ce9cc](https://linux-hardware.org/?probe=a86f7ce9cc) | Dec 03, 2023 |
| Gigabyte      | H81M-D2W                    | Desktop     | [98567fb8e0](https://linux-hardware.org/?probe=98567fb8e0) | Dec 03, 2023 |
| Gigabyte      | H81M-D2W                    | Desktop     | [00da9d31bd](https://linux-hardware.org/?probe=00da9d31bd) | Dec 03, 2023 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [bc2256e5f6](https://linux-hardware.org/?probe=bc2256e5f6) | Dec 03, 2023 |
| HP            | 8169                        | Desktop     | [6bdddabb7f](https://linux-hardware.org/?probe=6bdddabb7f) | Dec 03, 2023 |
| Lenovo        | IdeaPad Slim 5 16ABR8 82... | Notebook    | [5f96e00c00](https://linux-hardware.org/?probe=5f96e00c00) | Dec 03, 2023 |
| Dell          | Latitude 7370               | Notebook    | [30fc1de681](https://linux-hardware.org/?probe=30fc1de681) | Dec 03, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [1d3323974f](https://linux-hardware.org/?probe=1d3323974f) | Dec 03, 2023 |
| Acer          | Aspire V3-771               | Notebook    | [28345ccbfb](https://linux-hardware.org/?probe=28345ccbfb) | Dec 02, 2023 |
| Gigabyte      | B75M-D3V                    | Desktop     | [62a3456f1c](https://linux-hardware.org/?probe=62a3456f1c) | Dec 02, 2023 |
| ASUSTek       | K56CB                       | Notebook    | [97e892b8ef](https://linux-hardware.org/?probe=97e892b8ef) | Dec 02, 2023 |
| ASUSTek       | A8N-SLI Premium             | Desktop     | [79f209d7a3](https://linux-hardware.org/?probe=79f209d7a3) | Dec 02, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [daa56bab51](https://linux-hardware.org/?probe=daa56bab51) | Dec 02, 2023 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [7a932c5570](https://linux-hardware.org/?probe=7a932c5570) | Dec 02, 2023 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [9b46bc6583](https://linux-hardware.org/?probe=9b46bc6583) | Dec 02, 2023 |
| MSI           | Z370 GAMING PRO CARBON      | Desktop     | [4b1c01f9b4](https://linux-hardware.org/?probe=4b1c01f9b4) | Dec 02, 2023 |
| Apple         | MacBookPro13,1              | Notebook    | [165571d0a3](https://linux-hardware.org/?probe=165571d0a3) | Dec 02, 2023 |
| Dell          | Latitude E6430              | Notebook    | [fedc3b8a8d](https://linux-hardware.org/?probe=fedc3b8a8d) | Dec 02, 2023 |
| ASUSTek       | CROSSHAIR                   | Desktop     | [2b2a87350b](https://linux-hardware.org/?probe=2b2a87350b) | Dec 02, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [05b5607e47](https://linux-hardware.org/?probe=05b5607e47) | Dec 02, 2023 |
| ASUSTek       | K54C                        | Notebook    | [e9694ebc98](https://linux-hardware.org/?probe=e9694ebc98) | Dec 02, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [f2a9f68180](https://linux-hardware.org/?probe=f2a9f68180) | Dec 02, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [e6d3755007](https://linux-hardware.org/?probe=e6d3755007) | Dec 02, 2023 |
| Medion        | E3223                       | Convertible | [1c5d81c584](https://linux-hardware.org/?probe=1c5d81c584) | Dec 02, 2023 |
| Toshiba       | Satellite C650D             | Notebook    | [704507bfd5](https://linux-hardware.org/?probe=704507bfd5) | Dec 02, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [9aa3882678](https://linux-hardware.org/?probe=9aa3882678) | Dec 02, 2023 |
| MSI           | GE72 6QD                    | Notebook    | [2e250b81a4](https://linux-hardware.org/?probe=2e250b81a4) | Dec 02, 2023 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [d01b48eb39](https://linux-hardware.org/?probe=d01b48eb39) | Dec 02, 2023 |
| HP            | 3047h                       | Desktop     | [754e0de21d](https://linux-hardware.org/?probe=754e0de21d) | Dec 02, 2023 |
| Dell          | Latitude E6430              | Notebook    | [980a0b89b5](https://linux-hardware.org/?probe=980a0b89b5) | Dec 02, 2023 |
| MSI           | PRO B660M-A WIFI            | Desktop     | [d3a2fc2cb0](https://linux-hardware.org/?probe=d3a2fc2cb0) | Dec 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | Notebook    | [7ddcba051c](https://linux-hardware.org/?probe=7ddcba051c) | Dec 02, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [881e6d6c8d](https://linux-hardware.org/?probe=881e6d6c8d) | Dec 02, 2023 |
| Dell          | 0HY9JP A00                  | Desktop     | [0714d912db](https://linux-hardware.org/?probe=0714d912db) | Dec 02, 2023 |
| Sony          | VPCEB1S1E                   | Notebook    | [d240ac5f41](https://linux-hardware.org/?probe=d240ac5f41) | Dec 02, 2023 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | Notebook    | [5d98fa1470](https://linux-hardware.org/?probe=5d98fa1470) | Dec 02, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [13c49517db](https://linux-hardware.org/?probe=13c49517db) | Dec 02, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [9dea837056](https://linux-hardware.org/?probe=9dea837056) | Dec 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [ff37eb859a](https://linux-hardware.org/?probe=ff37eb859a) | Dec 02, 2023 |
| Lenovo        | IdeaPad S20-30              | Notebook    | [ae69cb9115](https://linux-hardware.org/?probe=ae69cb9115) | Dec 01, 2023 |
| Fujitsu       | LIFEBOOK E780               | Notebook    | [f1e82db736](https://linux-hardware.org/?probe=f1e82db736) | Dec 01, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [997f545600](https://linux-hardware.org/?probe=997f545600) | Dec 01, 2023 |
| VALE          | Notebook Classic C140       | Notebook    | [3c14d641ec](https://linux-hardware.org/?probe=3c14d641ec) | Dec 01, 2023 |
| Valve         | Galileo                     | Notebook    | [3239203d03](https://linux-hardware.org/?probe=3239203d03) | Dec 01, 2023 |
| Lenovo        | ThinkPad W550s 20E2CTO1W... | Notebook    | [1645df2234](https://linux-hardware.org/?probe=1645df2234) | Dec 01, 2023 |
| Lenovo        | ThinkPad W550s 20E2CTO1W... | Notebook    | [570da1b5b2](https://linux-hardware.org/?probe=570da1b5b2) | Dec 01, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [ed158c0464](https://linux-hardware.org/?probe=ed158c0464) | Dec 01, 2023 |
| Packard Be... | EasyNote LJ75               | Notebook    | [0f21e6cb39](https://linux-hardware.org/?probe=0f21e6cb39) | Dec 01, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [eb3b0a6afb](https://linux-hardware.org/?probe=eb3b0a6afb) | Dec 01, 2023 |
| HP            | 3397                        | Desktop     | [a858c3e80b](https://linux-hardware.org/?probe=a858c3e80b) | Dec 01, 2023 |
| MSI           | MPG Z590M GAMING EDGE WI... | Desktop     | [a8495b2209](https://linux-hardware.org/?probe=a8495b2209) | Dec 01, 2023 |
| Acer          | Aspire A114-31              | Notebook    | [1eb938404f](https://linux-hardware.org/?probe=1eb938404f) | Dec 01, 2023 |
| Acer          | Aspire E5-773G              | Notebook    | [9ca60df165](https://linux-hardware.org/?probe=9ca60df165) | Dec 01, 2023 |
| Medion        | MS-7501                     | Desktop     | [4380c6e022](https://linux-hardware.org/?probe=4380c6e022) | Dec 01, 2023 |
| Fujitsu       | LIFEBOOK A555/G             | Notebook    | [5b088fb31f](https://linux-hardware.org/?probe=5b088fb31f) | Dec 01, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [fd46463395](https://linux-hardware.org/?probe=fd46463395) | Dec 01, 2023 |
| Fujitsu       | LIFEBOOK A555/G             | Notebook    | [c0f107065e](https://linux-hardware.org/?probe=c0f107065e) | Dec 01, 2023 |
| Samsung       | R530/R730                   | Notebook    | [d307e11a95](https://linux-hardware.org/?probe=d307e11a95) | Dec 01, 2023 |
| Dell          | Precision 7520              | Notebook    | [3651203e23](https://linux-hardware.org/?probe=3651203e23) | Dec 01, 2023 |
| Acer          | Aspire A517-52G             | Notebook    | [72702ceb3f](https://linux-hardware.org/?probe=72702ceb3f) | Dec 01, 2023 |
| Dell          | Latitude E6530              | Notebook    | [a9b4f4fa6c](https://linux-hardware.org/?probe=a9b4f4fa6c) | Dec 01, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [0a9f2b8eae](https://linux-hardware.org/?probe=0a9f2b8eae) | Dec 01, 2023 |
| ASUSTek       | ROG STRIX B460-G GAMING     | Desktop     | [320fdec41d](https://linux-hardware.org/?probe=320fdec41d) | Dec 01, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [a29e779e6e](https://linux-hardware.org/?probe=a29e779e6e) | Dec 01, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [06f49be71d](https://linux-hardware.org/?probe=06f49be71d) | Dec 01, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [d18d77b15f](https://linux-hardware.org/?probe=d18d77b15f) | Dec 01, 2023 |
| Medion        | E6226                       | Notebook    | [8422a61bf7](https://linux-hardware.org/?probe=8422a61bf7) | Dec 01, 2023 |
| Lenovo        | Annapurna CRB NOK           | Desktop     | [9fe0854829](https://linux-hardware.org/?probe=9fe0854829) | Dec 01, 2023 |
| Lenovo        | ThinkPad T490s 20NYS02A0... | Notebook    | [a23499d148](https://linux-hardware.org/?probe=a23499d148) | Nov 30, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | Notebook    | [6a029b4d87](https://linux-hardware.org/?probe=6a029b4d87) | Nov 30, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [bb6640572b](https://linux-hardware.org/?probe=bb6640572b) | Nov 30, 2023 |
| HP            | 15                          | Notebook    | [df51360bdd](https://linux-hardware.org/?probe=df51360bdd) | Nov 30, 2023 |
| Acer          | Aspire A315-35              | Notebook    | [dad806dd8b](https://linux-hardware.org/?probe=dad806dd8b) | Nov 30, 2023 |
| Acer          | Aspire A517-52G             | Notebook    | [33126bb441](https://linux-hardware.org/?probe=33126bb441) | Nov 30, 2023 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [f38c73783f](https://linux-hardware.org/?probe=f38c73783f) | Nov 30, 2023 |
| Intel         | S1200RP G62251-407          | Server      | [806a2b0d98](https://linux-hardware.org/?probe=806a2b0d98) | Nov 30, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [a8532d8b7b](https://linux-hardware.org/?probe=a8532d8b7b) | Nov 30, 2023 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [e7fab4df3b](https://linux-hardware.org/?probe=e7fab4df3b) | Nov 30, 2023 |
| HP            | Compaq CQ58                 | Notebook    | [d50dd381c3](https://linux-hardware.org/?probe=d50dd381c3) | Nov 30, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [499e463561](https://linux-hardware.org/?probe=499e463561) | Nov 30, 2023 |
| HP            | Pavilion g6                 | Notebook    | [f36afef418](https://linux-hardware.org/?probe=f36afef418) | Nov 30, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [1999f34fd0](https://linux-hardware.org/?probe=1999f34fd0) | Nov 30, 2023 |
| Dell          | Latitude 7370               | Notebook    | [356b2e9e31](https://linux-hardware.org/?probe=356b2e9e31) | Nov 30, 2023 |
| Acer          | TravelMate Spin B118-G2-... | Convertible | [013c0f7207](https://linux-hardware.org/?probe=013c0f7207) | Nov 30, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [fa8d37e46b](https://linux-hardware.org/?probe=fa8d37e46b) | Nov 30, 2023 |
| Toshiba       | Satellite C850-19D          | Notebook    | [cd9dbac72b](https://linux-hardware.org/?probe=cd9dbac72b) | Nov 30, 2023 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [0ab91a2ff5](https://linux-hardware.org/?probe=0ab91a2ff5) | Nov 30, 2023 |
| Lenovo        | ThinkPad T590 20N5S56P00    | Notebook    | [352fffb7a9](https://linux-hardware.org/?probe=352fffb7a9) | Nov 30, 2023 |
| Valve         | Jupiter                     | Notebook    | [da673c17c8](https://linux-hardware.org/?probe=da673c17c8) | Nov 29, 2023 |
| Lenovo        | ThinkPad X13 Gen 3 21BNC... | Notebook    | [6596326097](https://linux-hardware.org/?probe=6596326097) | Nov 29, 2023 |
| Acer          | Aspire A317-32              | Notebook    | [02b205724a](https://linux-hardware.org/?probe=02b205724a) | Nov 29, 2023 |
| Unknown       | N15                         | Desktop     | [a968ec315f](https://linux-hardware.org/?probe=a968ec315f) | Nov 29, 2023 |
| Acer          | Aspire one                  | Notebook    | [5bf09e9b79](https://linux-hardware.org/?probe=5bf09e9b79) | Nov 29, 2023 |
| Fujitsu       | D3222-B1 S26361-D3222-B1    | Desktop     | [7e2d79a521](https://linux-hardware.org/?probe=7e2d79a521) | Nov 29, 2023 |
| Acer          | Aspire 7741                 | Notebook    | [21dd4594fd](https://linux-hardware.org/?probe=21dd4594fd) | Nov 29, 2023 |
| Dell          | Latitude 5420               | Notebook    | [56ad64e87a](https://linux-hardware.org/?probe=56ad64e87a) | Nov 29, 2023 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [cd63a4710a](https://linux-hardware.org/?probe=cd63a4710a) | Nov 29, 2023 |
| Lenovo        | 317E SDK0K17763 WIN 1801... | Desktop     | [8bc25c47be](https://linux-hardware.org/?probe=8bc25c47be) | Nov 29, 2023 |
| Lenovo        | IdeaPad 3 17ALC6 82KV       | Notebook    | [1b7f8a15dd](https://linux-hardware.org/?probe=1b7f8a15dd) | Nov 29, 2023 |
| Lenovo        | ThinkPad W530 24412S6       | Notebook    | [35077333e3](https://linux-hardware.org/?probe=35077333e3) | Nov 29, 2023 |
| Supermicro    | X13SAE-F                    | Server      | [6fa7511431](https://linux-hardware.org/?probe=6fa7511431) | Nov 29, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | Notebook    | [4fb92d7fe0](https://linux-hardware.org/?probe=4fb92d7fe0) | Nov 29, 2023 |
| Acer          | AOD260                      | Notebook    | [20594f9a03](https://linux-hardware.org/?probe=20594f9a03) | Nov 29, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [1537766927](https://linux-hardware.org/?probe=1537766927) | Nov 29, 2023 |
| Acer          | AOD260                      | Notebook    | [de50f2993e](https://linux-hardware.org/?probe=de50f2993e) | Nov 29, 2023 |
| HP            | 805D                        | Desktop     | [997f828456](https://linux-hardware.org/?probe=997f828456) | Nov 29, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [e47384c541](https://linux-hardware.org/?probe=e47384c541) | Nov 29, 2023 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [062cd64553](https://linux-hardware.org/?probe=062cd64553) | Nov 29, 2023 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [4446f12e33](https://linux-hardware.org/?probe=4446f12e33) | Nov 29, 2023 |
| Lenovo        | ThinkPad W530 244723G       | Notebook    | [30e3d22482](https://linux-hardware.org/?probe=30e3d22482) | Nov 29, 2023 |
| Gigabyte      | F2A88X-D3H                  | Desktop     | [15c78cff63](https://linux-hardware.org/?probe=15c78cff63) | Nov 29, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [1b2c06817f](https://linux-hardware.org/?probe=1b2c06817f) | Nov 29, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [423e8001ab](https://linux-hardware.org/?probe=423e8001ab) | Nov 29, 2023 |
| HP            | 1589                        | Desktop     | [4130285e5d](https://linux-hardware.org/?probe=4130285e5d) | Nov 29, 2023 |
| Unknown       | Unknown                     | Notebook    | [b6ebeab524](https://linux-hardware.org/?probe=b6ebeab524) | Nov 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [d385ea9309](https://linux-hardware.org/?probe=d385ea9309) | Nov 29, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [066daf7cac](https://linux-hardware.org/?probe=066daf7cac) | Nov 29, 2023 |
| Lenovo        | ThinkPad T490 20N3SFKX00    | Notebook    | [9d5bc38102](https://linux-hardware.org/?probe=9d5bc38102) | Nov 29, 2023 |
| Lenovo        | ThinkPad T520 4243VU3       | Notebook    | [6cbaf1893d](https://linux-hardware.org/?probe=6cbaf1893d) | Nov 29, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [66847c493b](https://linux-hardware.org/?probe=66847c493b) | Nov 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [2b2bb98701](https://linux-hardware.org/?probe=2b2bb98701) | Nov 29, 2023 |
| MSI           | KA790GX                     | Desktop     | [5bc35f82f6](https://linux-hardware.org/?probe=5bc35f82f6) | Nov 28, 2023 |
| Fujitsu       | LIFEBOOK S762               | Notebook    | [a7b0f7fe30](https://linux-hardware.org/?probe=a7b0f7fe30) | Nov 28, 2023 |
| ASRock        | X370 Pro4                   | Desktop     | [c4f19bc722](https://linux-hardware.org/?probe=c4f19bc722) | Nov 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [577a8fa908](https://linux-hardware.org/?probe=577a8fa908) | Nov 28, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [7c53518c08](https://linux-hardware.org/?probe=7c53518c08) | Nov 28, 2023 |
| Google        | Lindar                      | Notebook    | [6dcdf626fc](https://linux-hardware.org/?probe=6dcdf626fc) | Nov 28, 2023 |
| HP            | Elite x2 G4                 | Tablet      | [457690ea99](https://linux-hardware.org/?probe=457690ea99) | Nov 28, 2023 |
| ASUSTek       | X200CA                      | Notebook    | [d0ea54e4fa](https://linux-hardware.org/?probe=d0ea54e4fa) | Nov 28, 2023 |
| Lenovo        | SDK0F82993 WIN              | Desktop     | [d9bc93a89f](https://linux-hardware.org/?probe=d9bc93a89f) | Nov 28, 2023 |
| HP            | Elite x2 G4                 | Tablet      | [968499c693](https://linux-hardware.org/?probe=968499c693) | Nov 28, 2023 |
| ASUSTek       | K93SV                       | Notebook    | [f85fb01be1](https://linux-hardware.org/?probe=f85fb01be1) | Nov 28, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [416a759973](https://linux-hardware.org/?probe=416a759973) | Nov 28, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [5030903de4](https://linux-hardware.org/?probe=5030903de4) | Nov 28, 2023 |
| Lenovo        | ThinkPad X13 Gen 3 21BNC... | Notebook    | [97719198b9](https://linux-hardware.org/?probe=97719198b9) | Nov 28, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [0bf3c142b3](https://linux-hardware.org/?probe=0bf3c142b3) | Nov 28, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [4fbfde63e3](https://linux-hardware.org/?probe=4fbfde63e3) | Nov 28, 2023 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [6b10244910](https://linux-hardware.org/?probe=6b10244910) | Nov 28, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [f9512696d3](https://linux-hardware.org/?probe=f9512696d3) | Nov 28, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [ff997b6ca3](https://linux-hardware.org/?probe=ff997b6ca3) | Nov 28, 2023 |
| MSI           | GE60 0NC\0ND                | Notebook    | [f1285ee8a7](https://linux-hardware.org/?probe=f1285ee8a7) | Nov 28, 2023 |
| HP            | 18E5                        | Desktop     | [a078eaa1d4](https://linux-hardware.org/?probe=a078eaa1d4) | Nov 28, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [39cd133974](https://linux-hardware.org/?probe=39cd133974) | Nov 28, 2023 |
| ASRock        | 960GM-GS3 FX                | Desktop     | [312461ed56](https://linux-hardware.org/?probe=312461ed56) | Nov 28, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [0c4dcfe90c](https://linux-hardware.org/?probe=0c4dcfe90c) | Nov 28, 2023 |
| Unknown       | Unknown                     | Notebook    | [d7d0f11ab2](https://linux-hardware.org/?probe=d7d0f11ab2) | Nov 28, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [5474258ca4](https://linux-hardware.org/?probe=5474258ca4) | Nov 28, 2023 |
| ASUSTek       | K55VD                       | Notebook    | [711f565945](https://linux-hardware.org/?probe=711f565945) | Nov 28, 2023 |
| Dell          | Latitude E6540              | Notebook    | [0346e7ea11](https://linux-hardware.org/?probe=0346e7ea11) | Nov 28, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [aca3298198](https://linux-hardware.org/?probe=aca3298198) | Nov 28, 2023 |
| HP            | 355 G2                      | Notebook    | [bb79df3643](https://linux-hardware.org/?probe=bb79df3643) | Nov 28, 2023 |
| Valve         | Jupiter                     | Notebook    | [ebc4731c68](https://linux-hardware.org/?probe=ebc4731c68) | Nov 28, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [f2dae5468d](https://linux-hardware.org/?probe=f2dae5468d) | Nov 27, 2023 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [ad30ce41a1](https://linux-hardware.org/?probe=ad30ce41a1) | Nov 27, 2023 |
| HP            | Pavilion g7                 | Notebook    | [10f5b71d45](https://linux-hardware.org/?probe=10f5b71d45) | Nov 27, 2023 |
| ZOTAC         | ZBOX-CI527/CI547NANO        | Mini pc     | [79a0fbae44](https://linux-hardware.org/?probe=79a0fbae44) | Nov 27, 2023 |
| MSI           | Z97 PC Mate                 | Desktop     | [3bc66597b8](https://linux-hardware.org/?probe=3bc66597b8) | Nov 27, 2023 |
| Packard Be... | EasyNote TK85               | Notebook    | [3beded6cde](https://linux-hardware.org/?probe=3beded6cde) | Nov 27, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [36fb8bfcab](https://linux-hardware.org/?probe=36fb8bfcab) | Nov 27, 2023 |
| ASUSTek       | P53E                        | Notebook    | [4ae691e974](https://linux-hardware.org/?probe=4ae691e974) | Nov 27, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [b46ec04a69](https://linux-hardware.org/?probe=b46ec04a69) | Nov 27, 2023 |
| Dell          | Precision M4700             | Notebook    | [e63ddd94ec](https://linux-hardware.org/?probe=e63ddd94ec) | Nov 27, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [d3122d678f](https://linux-hardware.org/?probe=d3122d678f) | Nov 27, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [fccb07c19e](https://linux-hardware.org/?probe=fccb07c19e) | Nov 27, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [a82d950345](https://linux-hardware.org/?probe=a82d950345) | Nov 27, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [e38428746a](https://linux-hardware.org/?probe=e38428746a) | Nov 27, 2023 |
| Biostar       | A78MD                       | Desktop     | [c7e8dd6939](https://linux-hardware.org/?probe=c7e8dd6939) | Nov 27, 2023 |
| Dell          | Precision M4600             | Notebook    | [487510b166](https://linux-hardware.org/?probe=487510b166) | Nov 27, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [4c071e2ab0](https://linux-hardware.org/?probe=4c071e2ab0) | Nov 27, 2023 |
| LETSUNG       | Unknown                     | Notebook    | [bfbf7dfeaa](https://linux-hardware.org/?probe=bfbf7dfeaa) | Nov 27, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [7a4bbea6d5](https://linux-hardware.org/?probe=7a4bbea6d5) | Nov 27, 2023 |
| MSI           | MPG B650I EDGE WIFI         | Desktop     | [e1e2845536](https://linux-hardware.org/?probe=e1e2845536) | Nov 27, 2023 |
| HP            | Pavilion dv6                | Notebook    | [5887d4ee16](https://linux-hardware.org/?probe=5887d4ee16) | Nov 27, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Germany/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 2866      | 11.93%  |
| Ubuntu 22.04                 | 1456      | 6.06%   |
| Ubuntu 18.04                 | 1247      | 5.19%   |
| Debian 11                    | 647       | 2.69%   |
| Linux Mint 20.3              | 598       | 2.49%   |
| OpenMandriva 4.2             | 573       | 2.38%   |
| Linux Mint 20.2              | 568       | 2.36%   |
| OpenMandriva 4.3             | 553       | 2.3%    |
| Linux Mint 21.1              | 484       | 2.01%   |
| Arch Rolling                 | 457       | 1.9%    |
| Zorin 16                     | 412       | 1.71%   |
| Manjaro                      | 412       | 1.71%   |
| Linux Mint 21.2              | 372       | 1.55%   |
| Linux Mint 20.1              | 365       | 1.52%   |
| Ubuntu 20.10                 | 346       | 1.44%   |
| Ubuntu 21.10                 | 342       | 1.42%   |
| Linux Mint 20                | 297       | 1.24%   |
| Arch                         | 287       | 1.19%   |
| Linux Mint 19.3              | 286       | 1.19%   |
| Pop!_OS 22.04                | 275       | 1.14%   |
| openSUSE Tumbleweed-XXXXXXXX | 264       | 1.1%    |
| Xubuntu 20.04                | 263       | 1.09%   |
| KDE neon 20.04               | 253       | 1.05%   |
| Debian 12                    | 245       | 1.02%   |
| Ubuntu 21.04                 | 238       | 0.99%   |
| Fedora 38                    | 229       | 0.95%   |
| Ubuntu 22.10                 | 219       | 0.91%   |
| Ubuntu 19.10                 | 216       | 0.9%    |
| Linux Mint 21                | 210       | 0.87%   |
| Ubuntu 23.04                 | 208       | 0.87%   |
| Ubuntu 19.04                 | 203       | 0.84%   |
| OpenMandriva 23.03           | 198       | 0.82%   |
| OpenMandriva 23.01           | 188       | 0.78%   |
| Debian 10                    | 173       | 0.72%   |
| ArcoLinux Rolling            | 171       | 0.71%   |
| Fedora 37                    | 167       | 0.69%   |
| Fedora 36                    | 159       | 0.66%   |
| OpenMandriva 23.08           | 156       | 0.65%   |
| BlackPanther 18.1            | 149       | 0.62%   |
| Kubuntu 20.04                | 142       | 0.59%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 7084      | 31.62%  |
| Linux Mint    | 3132      | 13.98%  |
| OpenMandriva  | 1793      | 8%      |
| Debian        | 1252      | 5.59%   |
| Fedora        | 1055      | 4.71%   |
| Manjaro       | 872       | 3.89%   |
| Arch          | 723       | 3.23%   |
| Pop!_OS       | 695       | 3.1%    |
| Zorin         | 559       | 2.5%    |
| Xubuntu       | 537       | 2.4%    |
| Kubuntu       | 509       | 2.27%   |
| openSUSE      | 478       | 2.13%   |
| ROSA          | 369       | 1.65%   |
| KDE neon      | 336       | 1.5%    |
| Gentoo        | 233       | 1.04%   |
| ArcoLinux     | 188       | 0.84%   |
| Elementary    | 183       | 0.82%   |
| Ubuntu MATE   | 165       | 0.74%   |
| BlackPanther  | 160       | 0.71%   |
| LMDE          | 144       | 0.64%   |
| Endless       | 144       | 0.64%   |
| Kali          | 134       | 0.6%    |
| EndeavourOS   | 127       | 0.57%   |
| SteamOS       | 125       | 0.56%   |
| Ubuntu Unity  | 120       | 0.54%   |
| Lubuntu       | 113       | 0.5%    |
| Ubuntu Budgie | 98        | 0.44%   |
| MX            | 78        | 0.35%   |
| Nobara        | 71        | 0.32%   |
| Garuda Linux  | 63        | 0.28%   |
| TUXEDO OS     | 61        | 0.27%   |
| Raspbian      | 55        | 0.25%   |
| CentOS        | 55        | 0.25%   |
| Clear Linux   | 51        | 0.23%   |
| Xero          | 43        | 0.19%   |
| Parrot        | 35        | 0.16%   |
| NixOS         | 28        | 0.12%   |
| LinuxFX       | 27        | 0.12%   |
| Peppermint    | 26        | 0.12%   |
| Ubuntu Studio | 21        | 0.09%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 547       | 2.03%   |
| 5.16.7-desktop-1omv4003  | 519       | 1.92%   |
| 5.4.0-42-generic         | 301       | 1.11%   |
| 5.15.0-56-generic        | 274       | 1.01%   |
| 5.4.0-58-generic         | 229       | 0.85%   |
| 5.15.0-58-generic        | 197       | 0.73%   |
| 6.2.6-desktop-1omv2390   | 194       | 0.72%   |
| 5.4.0-91-generic         | 179       | 0.66%   |
| 6.1.1-desktop-1omv2290   | 178       | 0.66%   |
| 5.4.0-52-generic         | 178       | 0.66%   |
| 5.4.0-48-generic         | 175       | 0.65%   |
| 5.15.0-52-generic        | 145       | 0.54%   |
| 5.15.0-48-generic        | 143       | 0.53%   |
| 5.15.0-60-generic        | 141       | 0.52%   |
| 5.4.0-26-generic         | 140       | 0.52%   |
| 5.19.0-35-generic        | 140       | 0.52%   |
| 5.15.0-46-generic        | 139       | 0.51%   |
| 6.4.11-desktop-1omv2390  | 137       | 0.51%   |
| 5.8.0-43-generic         | 119       | 0.44%   |
| 5.15.0-67-generic        | 119       | 0.44%   |
| 5.4.0-65-generic         | 118       | 0.44%   |
| 5.11.0-27-generic        | 116       | 0.43%   |
| 5.13.0-39-generic        | 115       | 0.43%   |
| 5.4.0-54-generic         | 113       | 0.42%   |
| 5.4.0-40-generic         | 113       | 0.42%   |
| 5.11.0-37-generic        | 112       | 0.41%   |
| 5.11.0-38-generic        | 111       | 0.41%   |
| 5.13.0-28-generic        | 110       | 0.41%   |
| 5.4.0-29-generic         | 109       | 0.4%    |
| 5.15.0-76-generic        | 108       | 0.4%    |
| 6.2.0-26-generic         | 107       | 0.4%    |
| 5.3.0-40-generic         | 107       | 0.4%    |
| 5.11.0-40-generic        | 107       | 0.4%    |
| 5.15.0-53-generic        | 106       | 0.39%   |
| 5.15.0-47-generic        | 105       | 0.39%   |
| 4.18.16-desktop-1bP      | 103       | 0.38%   |
| 5.4.0-72-generic         | 102       | 0.38%   |
| 5.13.0-30-generic        | 99        | 0.37%   |
| 5.4.0-33-generic         | 98        | 0.36%   |
| 5.4.0-37-generic         | 96        | 0.36%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 4063      | 16.34%  |
| 5.15.0  | 2574      | 10.35%  |
| 5.8.0   | 1204      | 4.84%   |
| 4.15.0  | 1183      | 4.76%   |
| 5.11.0  | 1136      | 4.57%   |
| 5.13.0  | 1126      | 4.53%   |
| 5.19.0  | 814       | 3.27%   |
| 6.2.0   | 747       | 3%      |
| 5.3.0   | 701       | 2.82%   |
| 5.10.0  | 672       | 2.7%    |
| 5.10.14 | 552       | 2.22%   |
| 5.16.7  | 528       | 2.12%   |
| 5.0.0   | 486       | 1.96%   |
| 4.18.0  | 371       | 1.49%   |
| 6.1.0   | 352       | 1.42%   |
| 6.2.6   | 271       | 1.09%   |
| 6.1.1   | 200       | 0.8%    |
| 4.19.0  | 178       | 0.72%   |
| 6.5.0   | 176       | 0.71%   |
| 6.4.11  | 159       | 0.64%   |
| 4.18.16 | 112       | 0.45%   |
| 5.14.21 | 91        | 0.37%   |
| 6.6.2   | 90        | 0.36%   |
| 6.0.0   | 85        | 0.34%   |
| 5.14.0  | 81        | 0.33%   |
| 5.3.18  | 74        | 0.3%    |
| 6.5.6   | 63        | 0.25%   |
| 4.9.20  | 63        | 0.25%   |
| 4.4.0   | 62        | 0.25%   |
| 5.18.0  | 58        | 0.23%   |
| 4.9.60  | 58        | 0.23%   |
| 6.4.6   | 52        | 0.21%   |
| 6.0.12  | 52        | 0.21%   |
| 5.6.14  | 52        | 0.21%   |
| 5.17.5  | 52        | 0.21%   |
| 6.5.5   | 51        | 0.21%   |
| 5.17.1  | 50        | 0.2%    |
| 5.11.12 | 50        | 0.2%    |
| 5.9.16  | 48        | 0.19%   |
| 6.5.9   | 47        | 0.19%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 4312      | 17.59%  |
| 5.15    | 3083      | 12.57%  |
| 5.10    | 1583      | 6.46%   |
| 5.8     | 1436      | 5.86%   |
| 5.11    | 1360      | 5.55%   |
| 5.13    | 1288      | 5.25%   |
| 6.2     | 1233      | 5.03%   |
| 4.15    | 1192      | 4.86%   |
| 6.1     | 1025      | 4.18%   |
| 5.19    | 1016      | 4.14%   |
| 5.3     | 840       | 3.43%   |
| 5.16    | 785       | 3.2%    |
| 5.0     | 509       | 2.08%   |
| 4.18    | 497       | 2.03%   |
| 6.5     | 492       | 2.01%   |
| 6.4     | 446       | 1.82%   |
| 6.0     | 360       | 1.47%   |
| 5.14    | 298       | 1.22%   |
| 5.9     | 274       | 1.12%   |
| 6.3     | 258       | 1.05%   |
| 5.18    | 247       | 1.01%   |
| 6.6     | 243       | 0.99%   |
| 4.9     | 241       | 0.98%   |
| 5.6     | 239       | 0.97%   |
| 4.19    | 229       | 0.93%   |
| 5.17    | 221       | 0.9%    |
| 5.12    | 170       | 0.69%   |
| 5.7     | 151       | 0.62%   |
| 5.5     | 100       | 0.41%   |
| 4.4     | 72        | 0.29%   |
| 5.2     | 43        | 0.18%   |
| 5.1     | 43        | 0.18%   |
| 4.1     | 39        | 0.16%   |
| 4.14    | 37        | 0.15%   |
| 4.12    | 36        | 0.15%   |
| 3.10    | 28        | 0.11%   |
| 4.13    | 27        | 0.11%   |
| 4.20    | 14        | 0.06%   |
| 4.17    | 11        | 0.04%   |
| 5       | 6         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| x86_64   | 20804     | 96.31%  |
| i686     | 505       | 2.34%   |
| aarch64  | 212       | 0.98%   |
| armv7l   | 58        | 0.27%   |
| armv6l   | 10        | 0.05%   |
| ppc      | 5         | 0.02%   |
| riscv64  | 3         | 0.01%   |
| armv8l   | 2         | 0.01%   |
| armv5tel | 2         | 0.01%   |
| mips     | 1         | 0.005%  |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| GNOME             | 8926      | 39.45%  |
| KDE5              | 4186      | 18.5%   |
| X-Cinnamon        | 2543      | 11.24%  |
| Unknown           | 2434      | 10.76%  |
| XFCE              | 1668      | 7.37%   |
| MATE              | 637       | 2.82%   |
| KDE               | 496       | 2.19%   |
| Cinnamon          | 320       | 1.41%   |
| KDE4              | 203       | 0.9%    |
| Pantheon          | 180       | 0.8%    |
| LXQt              | 177       | 0.78%   |
| i3                | 132       | 0.58%   |
| Budgie            | 132       | 0.58%   |
| Unity             | 124       | 0.55%   |
| LXDE              | 116       | 0.51%   |
| GNOME Flashback   | 42        | 0.19%   |
| Deepin            | 41        | 0.18%   |
| GNOME Classic     | 31        | 0.14%   |
| sway              | 29        | 0.13%   |
| Hyprland          | 29        | 0.13%   |
| awesome           | 26        | 0.11%   |
| lightdm-xsession  | 20        | 0.09%   |
| openbox           | 19        | 0.08%   |
| bspwm             | 12        | 0.05%   |
| xmonad            | 9         | 0.04%   |
| trinity           | 9         | 0.04%   |
| qtile             | 9         | 0.04%   |
| DWM               | 9         | 0.04%   |
| herbstluftwm      | 8         | 0.04%   |
| chadwm            | 7         | 0.03%   |
| enlightenment     | 6         | 0.03%   |
| ICEWM             | 5         | 0.02%   |
| LeftWM            | 4         | 0.02%   |
| Yaru:ubuntu:GNOME | 3         | 0.01%   |
| fluxbox           | 3         | 0.01%   |
| x-session-manager | 2         | 0.01%   |
| Phosh:GNOME       | 2         | 0.01%   |
| i3-with-shmlog    | 2         | 0.01%   |
| GNOME-Classic     | 2         | 0.01%   |
| Endless:GNOME     | 2         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 16686     | 74.64%  |
| Wayland     | 3877      | 17.34%  |
| Unknown     | 1233      | 5.52%   |
| Tty         | 553       | 2.47%   |
| Web         | 3         | 0.01%   |
| Unspecified | 3         | 0.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 10689     | 47.37%  |
| SDDM    | 3555      | 15.76%  |
| GDM3    | 2929      | 12.98%  |
| LightDM | 2649      | 11.74%  |
| GDM     | 1776      | 7.87%   |
| TDM     | 643       | 2.85%   |
| KDM     | 205       | 0.91%   |
| XDM     | 38        | 0.17%   |
| SLiM    | 31        | 0.14%   |
| LXDM    | 16        | 0.07%   |
| NODM    | 11        | 0.05%   |
| GREETD  | 8         | 0.04%   |
| MDM     | 6         | 0.03%   |
| Ly      | 5         | 0.02%   |
| WDM     | 1         | 0.004%  |
| LY-DM   | 1         | 0.004%  |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| de_DE      | 14317     | 64.75%  |
| en_US      | 4128      | 18.67%  |
| Unknown    | 2154      | 9.74%   |
| en_GB      | 423       | 1.91%   |
| C          | 360       | 1.63%   |
| ru_RU      | 102       | 0.46%   |
| en_DE      | 62        | 0.28%   |
| POSIX      | 55        | 0.25%   |
| pl_PL      | 55        | 0.25%   |
| it_IT      | 41        | 0.19%   |
| fr_FR      | 37        | 0.17%   |
| de_AT      | 33        | 0.15%   |
| es_ES      | 30        | 0.14%   |
| C.UTF8     | 24        | 0.11%   |
| de_CH      | 21        | 0.09%   |
| hu_HU      | 20        | 0.09%   |
| en_IE      | 18        | 0.08%   |
| en_DK      | 18        | 0.08%   |
| nl_NL      | 16        | 0.07%   |
| ro_RO      | 14        | 0.06%   |
| en_CA      | 13        | 0.06%   |
| ru_UA      | 11        | 0.05%   |
| de_BE      | 10        | 0.05%   |
| tr_TR      | 8         | 0.04%   |
| en_IN      | 8         | 0.04%   |
| en_AU      | 8         | 0.04%   |
| uk_UA      | 7         | 0.03%   |
| pt_BR      | 6         | 0.03%   |
| en_AG      | 6         | 0.03%   |
| bg_BG      | 6         | 0.03%   |
| sk_SK      | 5         | 0.02%   |
| el_GR      | 5         | 0.02%   |
| de_IT      | 5         | 0.02%   |
| de_DE.UTF8 | 5         | 0.02%   |
| pt_PT      | 4         | 0.02%   |
| hr_HR      | 4         | 0.02%   |
| de_LI      | 4         | 0.02%   |
| de_DE@euro | 4         | 0.02%   |
| cs_CZ      | 4         | 0.02%   |
| aa_DJ      | 4         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 11612     | 52.43%  |
| EFI  | 10534     | 47.57%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type          | Computers | Percent |
|---------------|-----------|---------|
| Ext4          | 16413     | 73.67%  |
| Btrfs         | 2039      | 9.15%   |
| Overlay       | 1840      | 8.26%   |
| Tmpfs         | 736       | 3.3%    |
| Unknown       | 624       | 2.8%    |
| Xfs           | 260       | 1.17%   |
| Zfs           | 164       | 0.74%   |
| Ext2          | 75        | 0.34%   |
| Ext3          | 58        | 0.26%   |
| F2fs          | 40        | 0.18%   |
| Reiserfs      | 7         | 0.03%   |
| Rootfs        | 4         | 0.02%   |
| Aufs          | 4         | 0.02%   |
| XXXXXXX       | 3         | 0.01%   |
| Jfs           | 3         | 0.01%   |
| XXX4          | 2         | 0.01%   |
| XXXXX         | 1         | 0.004%  |
| XXXX          | 1         | 0.004%  |
| XXXfs         | 1         | 0.004%  |
| OveXlay       | 1         | 0.004%  |
| Ntfs          | 1         | 0.004%  |
| Fuse.snapfuse | 1         | 0.004%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 11256     | 50.51%  |
| GPT     | 8486      | 38.08%  |
| MBR     | 2543      | 11.41%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 18397     | 83.18%  |
| Yes       | 3719      | 16.82%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 15692     | 71.19%  |
| Yes       | 6351      | 28.81%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 3526      | 16.33%  |
| ASUSTek Computer        | 3080      | 14.26%  |
| Hewlett-Packard         | 2437      | 11.29%  |
| Dell                    | 1789      | 8.29%   |
| MSI                     | 1448      | 6.71%   |
| Acer                    | 1428      | 6.61%   |
| Gigabyte Technology     | 1413      | 6.54%   |
| ASRock                  | 1041      | 4.82%   |
| Fujitsu                 | 680       | 3.15%   |
| Medion                  | 568       | 2.63%   |
| Apple                   | 431       | 2%      |
| Toshiba                 | 284       | 1.32%   |
| Intel                   | 251       | 1.16%   |
| Samsung Electronics     | 242       | 1.12%   |
| TUXEDO                  | 234       | 1.08%   |
| Raspberry Pi Foundation | 194       | 0.9%    |
| Sony                    | 181       | 0.84%   |
| Fujitsu Siemens         | 171       | 0.79%   |
| Unknown                 | 169       | 0.78%   |
| HUAWEI                  | 144       | 0.67%   |
| Packard Bell            | 125       | 0.58%   |
| Valve                   | 124       | 0.57%   |
| Notebook                | 103       | 0.48%   |
| Biostar                 | 87        | 0.4%    |
| Schenker                | 83        | 0.38%   |
| Microsoft               | 75        | 0.35%   |
| Supermicro              | 74        | 0.34%   |
| Wortmann AG             | 64        | 0.3%    |
| Foxconn                 | 63        | 0.29%   |
| BESSTAR Tech            | 55        | 0.25%   |
| ZOTAC                   | 45        | 0.21%   |
| Shuttle                 | 45        | 0.21%   |
| Pegatron                | 42        | 0.19%   |
| TrekStor                | 40        | 0.19%   |
| AMI                     | 39        | 0.18%   |
| Chuwi                   | 30        | 0.14%   |
| IBM                     | 29        | 0.13%   |
| Google                  | 29        | 0.13%   |
| Alienware               | 28        | 0.13%   |
| AZW                     | 27        | 0.13%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                          | Computers | Percent |
|-------------------------------|-----------|---------|
| Unknown                       | 265       | 1.23%   |
| ASUS All Series               | 143       | 0.66%   |
| Valve Jupiter                 | 122       | 0.56%   |
| MSI MS-7C37                   | 76        | 0.35%   |
| RPi Raspberry Pi              | 71        | 0.33%   |
| MSI MS-7B86                   | 68        | 0.31%   |
| HP Notebook                   | 53        | 0.25%   |
| MSI MS-7A38                   | 51        | 0.24%   |
| ASUS PRIME A320M-K            | 48        | 0.22%   |
| MSI MS-7B79                   | 40        | 0.19%   |
| ASUS PRIME B350-PLUS          | 38        | 0.18%   |
| ASRock B450M Pro4             | 38        | 0.18%   |
| MSI MS-7C56                   | 37        | 0.17%   |
| MSI MS-7C02                   | 36        | 0.17%   |
| MSI MS-7B89                   | 36        | 0.17%   |
| ASUS PRIME X370-PRO           | 36        | 0.17%   |
| ASUS M5A78L-M/USB3            | 36        | 0.17%   |
| Gigabyte X570 AORUS ELITE     | 34        | 0.16%   |
| Dell OptiPlex 7010            | 33        | 0.15%   |
| Lenovo IdeaPad 5 15ARE05 81YQ | 32        | 0.15%   |
| Dell OptiPlex 790             | 31        | 0.14%   |
| ASUS A0000001                 | 30        | 0.14%   |
| Gigabyte 970A-DS3P            | 29        | 0.13%   |
| ASUS P50IJ                    | 29        | 0.13%   |
| MSI MS-7C91                   | 28        | 0.13%   |
| MSI MS-7C52                   | 27        | 0.13%   |
| HP 255 G7 Notebook PC         | 27        | 0.13%   |
| MSI MS-7693                   | 26        | 0.12%   |
| HP Laptop 15s-eq2xxx          | 26        | 0.12%   |
| Dell Latitude E6420           | 26        | 0.12%   |
| ASUS A68HM-PLUS               | 26        | 0.12%   |
| Supermicro Super Server       | 25        | 0.12%   |
| ASUS TUF Gaming X570-PLUS     | 25        | 0.12%   |
| ASUS ROG STRIX B550-F GAMING  | 25        | 0.12%   |
| ASUS M5A97 R2.0               | 25        | 0.12%   |
| ASRock B450 Pro4              | 25        | 0.12%   |
| Acer Aspire 7750G             | 25        | 0.12%   |
| Dell Latitude E6430           | 24        | 0.11%   |
| Dell Latitude E6410           | 24        | 0.11%   |
| ASUS TUF Gaming B550-PLUS     | 24        | 0.11%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 2034      | 9.42%   |
| Acer Aspire           | 950       | 4.4%    |
| Dell Latitude         | 613       | 2.84%   |
| Lenovo IdeaPad        | 462       | 2.14%   |
| ASUS PRIME            | 384       | 1.78%   |
| HP EliteBook          | 380       | 1.76%   |
| ASUS ROG              | 309       | 1.43%   |
| HP Pavilion           | 304       | 1.41%   |
| HP Laptop             | 284       | 1.32%   |
| Fujitsu LIFEBOOK      | 278       | 1.29%   |
| Fujitsu ESPRIMO       | 270       | 1.25%   |
| Unknown               | 265       | 1.23%   |
| Dell OptiPlex         | 262       | 1.21%   |
| HP Compaq             | 253       | 1.17%   |
| Dell XPS              | 242       | 1.12%   |
| Dell Precision        | 236       | 1.09%   |
| Toshiba Satellite     | 232       | 1.07%   |
| HP ProBook            | 229       | 1.06%   |
| Dell Inspiron         | 227       | 1.05%   |
| RPi Raspberry         | 192       | 0.89%   |
| Lenovo ThinkCentre    | 181       | 0.84%   |
| ASUS TUF              | 145       | 0.67%   |
| ASUS All              | 143       | 0.66%   |
| Lenovo Yoga           | 141       | 0.65%   |
| ASUS VivoBook         | 127       | 0.59%   |
| Valve Jupiter         | 122       | 0.56%   |
| HP ENVY               | 120       | 0.56%   |
| Acer Swift            | 112       | 0.52%   |
| Acer TravelMate       | 93        | 0.43%   |
| ASUS M5A78L-M         | 92        | 0.43%   |
| Medion Akoya          | 89        | 0.41%   |
| Packard Bell EasyNote | 83        | 0.38%   |
| ASUS Zenbook          | 83        | 0.38%   |
| HP EliteDesk          | 79        | 0.37%   |
| MSI MS-7C37           | 76        | 0.35%   |
| Gigabyte X570         | 76        | 0.35%   |
| Microsoft Surface     | 75        | 0.35%   |
| HP 255                | 75        | 0.35%   |
| Dell Vostro           | 74        | 0.34%   |
| HP ZBook              | 71        | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 1928      | 8.93%   |
| 2020    | 1903      | 8.81%   |
| 2019    | 1820      | 8.43%   |
| 2012    | 1812      | 8.39%   |
| 2011    | 1555      | 7.2%    |
| 2013    | 1464      | 6.78%   |
| 2017    | 1396      | 6.47%   |
| 2021    | 1334      | 6.18%   |
| 2014    | 1251      | 5.79%   |
| 2010    | 1171      | 5.42%   |
| 2015    | 1034      | 4.79%   |
| 2016    | 1011      | 4.68%   |
| 2009    | 913       | 4.23%   |
| 2008    | 823       | 3.81%   |
| 2022    | 798       | 3.7%    |
| 2007    | 481       | 2.23%   |
| Unknown | 280       | 1.3%    |
| 2023    | 261       | 1.21%   |
| 2006    | 219       | 1.01%   |
| 2005    | 86        | 0.4%    |
| 2004    | 27        | 0.13%   |
| 2003    | 14        | 0.06%   |
| 2002    | 5         | 0.02%   |
| 2000    | 5         | 0.02%   |
| 2001    | 1         | 0.005%  |
| 1999    | 1         | 0.005%  |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 11206     | 51.9%   |
| Desktop        | 8525      | 39.48%  |
| Convertible    | 614       | 2.84%   |
| Mini pc        | 377       | 1.75%   |
| System on chip | 259       | 1.2%    |
| Tablet         | 256       | 1.19%   |
| All in one     | 195       | 0.9%    |
| Server         | 145       | 0.67%   |
| Phone          | 12        | 0.06%   |
| Stick pc       | 2         | 0.01%   |
| Other          | 1         | 0.005%  |
| Firewall       | 1         | 0.005%  |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 20173     | 92.69%  |
| Enabled  | 1591      | 7.31%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 21534     | 99.73%  |
| Yes  | 59        | 0.27%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 4867      | 22.14%  |
| 16.01-24.0      | 4383      | 19.94%  |
| 8.01-16.0       | 4012      | 18.25%  |
| 3.01-4.0        | 3993      | 18.17%  |
| 32.01-64.0      | 2356      | 10.72%  |
| 1.01-2.0        | 709       | 3.23%   |
| 64.01-256.0     | 698       | 3.18%   |
| 24.01-32.0      | 452       | 2.06%   |
| 2.01-3.0        | 290       | 1.32%   |
| 0.51-1.0        | 157       | 0.71%   |
| More than 256.0 | 32        | 0.15%   |
| 0.01-0.5        | 27        | 0.12%   |
| Unknown         | 4         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 9286      | 38.28%  |
| 2.01-3.0    | 5797      | 23.9%   |
| 4.01-8.0    | 3211      | 13.24%  |
| 3.01-4.0    | 2777      | 11.45%  |
| 0.51-1.0    | 1638      | 6.75%   |
| 8.01-16.0   | 905       | 3.73%   |
| 0.01-0.5    | 375       | 1.55%   |
| 16.01-24.0  | 149       | 0.61%   |
| 24.01-32.0  | 53        | 0.22%   |
| 32.01-64.0  | 44        | 0.18%   |
| 64.01-256.0 | 11        | 0.05%   |
| Unknown     | 8         | 0.03%   |
| 0           | 5         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 12790     | 57.02%  |
| 2       | 5601      | 24.97%  |
| 3       | 1926      | 8.59%   |
| 4       | 973       | 4.34%   |
| 5       | 455       | 2.03%   |
| 0       | 224       | 1%      |
| 6       | 218       | 0.97%   |
| 7       | 104       | 0.46%   |
| 8       | 48        | 0.21%   |
| 9       | 29        | 0.13%   |
| 10      | 16        | 0.07%   |
| Unknown | 11        | 0.05%   |
| 13      | 9         | 0.04%   |
| 17      | 6         | 0.03%   |
| 12      | 5         | 0.02%   |
| 11      | 5         | 0.02%   |
| 14      | 2         | 0.01%   |
| 79      | 1         | 0.004%  |
| 32      | 1         | 0.004%  |
| 29      | 1         | 0.004%  |
| 23      | 1         | 0.004%  |
| 22      | 1         | 0.004%  |
| 20      | 1         | 0.004%  |
| 16      | 1         | 0.004%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 11853     | 54.35%  |
| Yes       | 9954      | 45.65%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 18942     | 87.44%  |
| No        | 2722      | 12.56%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 15503     | 71.26%  |
| No        | 6254      | 28.74%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 12174     | 55.45%  |
| No        | 9780      | 44.55%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Germany | 21593     | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Berlin               | 1964      | 8.33%   |
| Munich               | 987       | 4.19%   |
| Hamburg              | 902       | 3.83%   |
| Frankfurt am Main    | 723       | 3.07%   |
| Cologne              | 529       | 2.24%   |
| Stuttgart            | 454       | 1.93%   |
| Leipzig              | 367       | 1.56%   |
| Nuremberg            | 272       | 1.15%   |
| Dresden              | 269       | 1.14%   |
| Düsseldorf          | 265       | 1.12%   |
| Essen                | 254       | 1.08%   |
| Mannheim             | 228       | 0.97%   |
| Karlsruhe            | 222       | 0.94%   |
| Dortmund             | 189       | 0.8%    |
| Hanover              | 165       | 0.7%    |
| Duisburg             | 162       | 0.69%   |
| Bonn                 | 159       | 0.67%   |
| Bremen               | 150       | 0.64%   |
| Wuppertal            | 137       | 0.58%   |
| Augsburg             | 134       | 0.57%   |
| Darmstadt            | 129       | 0.55%   |
| Bochum               | 125       | 0.53%   |
| Bielefeld            | 123       | 0.52%   |
| Braunschweig         | 119       | 0.5%    |
| Münster             | 115       | 0.49%   |
| Mainz                | 108       | 0.46%   |
| Wiesbaden            | 106       | 0.45%   |
| Chemnitz             | 102       | 0.43%   |
| Kiel                 | 99        | 0.42%   |
| Aachen               | 95        | 0.4%    |
| Regensburg           | 91        | 0.39%   |
| Halle                | 91        | 0.39%   |
| Falkenstein          | 88        | 0.37%   |
| Krefeld              | 79        | 0.34%   |
| Reutlingen           | 75        | 0.32%   |
| Freiburg im Breisgau | 75        | 0.32%   |
| Erfurt               | 75        | 0.32%   |
| Bamberg              | 75        | 0.32%   |
| Mönchengladbach     | 74        | 0.31%   |
| Heilbronn            | 73        | 0.31%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 6882      | 11198  | 21.3%   |
| WDC                         | 4196      | 6866   | 12.99%  |
| Seagate                     | 3761      | 6044   | 11.64%  |
| SanDisk                     | 2529      | 3680   | 7.83%   |
| Toshiba                     | 1978      | 2807   | 6.12%   |
| Crucial                     | 1571      | 2251   | 4.86%   |
| Unknown                     | 1476      | 2119   | 4.57%   |
| Kingston                    | 1048      | 1413   | 3.24%   |
| Intenso                     | 933       | 1289   | 2.89%   |
| Hitachi                     | 918       | 1226   | 2.84%   |
| SK hynix                    | 737       | 921    | 2.28%   |
| Intel                       | 670       | 938    | 2.07%   |
| Micron Technology           | 541       | 716    | 1.67%   |
| HGST                        | 430       | 633    | 1.33%   |
| A-DATA Technology           | 240       | 315    | 0.74%   |
| Phison                      | 239       | 340    | 0.74%   |
| KIOXIA                      | 202       | 252    | 0.63%   |
| Micron/Crucial Technology   | 187       | 258    | 0.58%   |
| Transcend                   | 178       | 226    | 0.55%   |
| Apple                       | 177       | 229    | 0.55%   |
| OCZ                         | 166       | 218    | 0.51%   |
| Phison Electronics          | 150       | 189    | 0.46%   |
| Fujitsu                     | 137       | 176    | 0.42%   |
| China                       | 133       | 161    | 0.41%   |
| Unknown                     | 127       | 148    | 0.39%   |
| LITEON                      | 110       | 123    | 0.34%   |
| Patriot                     | 109       | 153    | 0.34%   |
| Silicon Motion              | 106       | 148    | 0.33%   |
| SPCC                        | 104       | 142    | 0.32%   |
| Kingston Technology Company | 102       | 132    | 0.32%   |
| JMicron Technology          | 97        | 108    | 0.3%    |
| Corsair                     | 86        | 110    | 0.27%   |
| Maxtor                      | 84        | 125    | 0.26%   |
| ASMT                        | 84        | 107    | 0.26%   |
| LITEONIT                    | 64        | 77     | 0.2%    |
| Leven                       | 63        | 85     | 0.2%    |
| PNY                         | 58        | 94     | 0.18%   |
| Netac                       | 54        | 70     | 0.17%   |
| SABRENT                     | 52        | 63     | 0.16%   |
| Verbatim                    | 49        | 78     | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB                           | 420       | 1.16%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 375       | 1.03%   |
| Samsung SSD 860 EVO 500GB                           | 356       | 0.98%   |
| Samsung SSD 850 EVO 500GB                           | 323       | 0.89%   |
| Crucial CT1000MX500SSD1 1TB                         | 256       | 0.71%   |
| Unknown MMC Card  64GB                              | 244       | 0.67%   |
| Unknown MMC Card  32GB                              | 241       | 0.66%   |
| Crucial CT500MX500SSD1 500GB                        | 238       | 0.66%   |
| Samsung SSD 860 EVO 1TB                             | 234       | 0.64%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 188       | 0.52%   |
| Samsung NVMe SSD Drive 500GB                        | 180       | 0.5%    |
| Samsung SSD 860 EVO 250GB                           | 179       | 0.49%   |
| SanDisk SSD PLUS 240GB                              | 178       | 0.49%   |
| Toshiba MQ01ABD100 1TB                              | 177       | 0.49%   |
| SanDisk SSD PLUS 1000GB                             | 171       | 0.47%   |
| Samsung SSD 840 EVO 250GB                           | 167       | 0.46%   |
| Toshiba DT01ACA100 1TB                              | 160       | 0.44%   |
| Seagate ST500DM002-1BD142 500GB                     | 160       | 0.44%   |
| Samsung NVMe SSD Drive 512GB                        | 160       | 0.44%   |
| Samsung SSD 970 EVO Plus 1TB                        | 159       | 0.44%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 153       | 0.42%   |
| Samsung NVMe SSD Drive 1TB                          | 153       | 0.42%   |
| Crucial CT240BX500SSD1 240GB                        | 149       | 0.41%   |
| Unknown SD/MMC/MS PRO 512GB                         | 142       | 0.39%   |
| Unknown MMC Card  128GB                             | 135       | 0.37%   |
| SanDisk SSD PLUS 480GB                              | 134       | 0.37%   |
| SanDisk NVMe SSD Drive 512GB                        | 127       | 0.35%   |
| Unknown                                             | 127       | 0.35%   |
| Seagate ST1000LM035-1RK172 1TB                      | 122       | 0.34%   |
| Kingston SA400S37240G 240GB SSD                     | 121       | 0.33%   |
| Samsung SSD 840 EVO 120GB                           | 119       | 0.33%   |
| Toshiba HDWD110 1TB                                 | 118       | 0.33%   |
| Seagate ST2000DM008-2FR102 2TB                      | 117       | 0.32%   |
| Samsung SSD 870 QVO 1TB                             | 115       | 0.32%   |
| Seagate ST9500325AS 500GB                           | 112       | 0.31%   |
| Intenso SSD SATAIII 512GB                           | 111       | 0.31%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 110       | 0.3%    |
| Samsung SSD 970 EVO Plus 500GB                      | 108       | 0.3%    |
| Samsung SSD 860 QVO 1TB                             | 107       | 0.29%   |
| Seagate ST1000DM010-2EP102 1TB                      | 106       | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3676      | 5914   | 32.1%   |
| WDC                 | 3415      | 5714   | 29.82%  |
| Toshiba             | 1417      | 2044   | 12.37%  |
| Hitachi             | 918       | 1226   | 8.02%   |
| Samsung Electronics | 844       | 1286   | 7.37%   |
| HGST                | 430       | 633    | 3.76%   |
| Unknown             | 150       | 226    | 1.31%   |
| Fujitsu             | 137       | 176    | 1.2%    |
| Intenso             | 88        | 135    | 0.77%   |
| Maxtor              | 80        | 118    | 0.7%    |
| Apple               | 43        | 48     | 0.38%   |
| SABRENT             | 42        | 51     | 0.37%   |
| ASMT                | 20        | 25     | 0.17%   |
| USB3.0              | 18        | 19     | 0.16%   |
| WD MediaMax         | 14        | 20     | 0.12%   |
| TO Exter            | 14        | 19     | 0.12%   |
| ExcelStor           | 12        | 14     | 0.1%    |
| IBM/Hitachi         | 11        | 11     | 0.1%    |
| USB                 | 10        | 11     | 0.09%   |
| Inateck             | 8         | 8      | 0.07%   |
| SSK                 | 7         | 9      | 0.06%   |
| HGST HTS            | 7         | 7      | 0.06%   |
| Hewlett-Packard     | 7         | 26     | 0.06%   |
| External            | 7         | 7      | 0.06%   |
| StoreJet            | 5         | 7      | 0.04%   |
| IBM                 | 5         | 6      | 0.04%   |
| Dell                | 5         | 9      | 0.04%   |
| ASMedia             | 5         | 5      | 0.04%   |
| HPE                 | 4         | 13     | 0.03%   |
| MDT                 | 3         | 3      | 0.03%   |
| Maxone              | 3         | 4      | 0.03%   |
| LIO-ORG             | 3         | 14     | 0.03%   |
| IB-377U3            | 3         | 3      | 0.03%   |
| Unknown             | 3         | 3      | 0.03%   |
| SILICONMOTION       | 2         | 3      | 0.02%   |
| Quantum             | 2         | 2      | 0.02%   |
| MARVELL             | 2         | 2      | 0.02%   |
| Magnetic Data       | 2         | 3      | 0.02%   |
| LaCie               | 2         | 2      | 0.02%   |
| KESU                | 2         | 2      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3807      | 5680   | 31.29%  |
| SanDisk             | 1839      | 2743   | 15.11%  |
| Crucial             | 1439      | 2059   | 11.83%  |
| Intenso             | 712       | 957    | 5.85%   |
| Kingston            | 684       | 933    | 5.62%   |
| WDC                 | 472       | 624    | 3.88%   |
| Intel               | 263       | 364    | 2.16%   |
| Micron Technology   | 244       | 334    | 2.01%   |
| Toshiba             | 237       | 295    | 1.95%   |
| A-DATA Technology   | 199       | 260    | 1.64%   |
| Transcend           | 162       | 201    | 1.33%   |
| OCZ                 | 162       | 210    | 1.33%   |
| SK hynix            | 159       | 192    | 1.31%   |
| China               | 129       | 156    | 1.06%   |
| LITEON              | 101       | 114    | 0.83%   |
| Apple               | 98        | 115    | 0.81%   |
| Patriot             | 97        | 137    | 0.8%    |
| SPCC                | 88        | 118    | 0.72%   |
| JMicron Technology  | 65        | 72     | 0.53%   |
| LITEONIT            | 64        | 77     | 0.53%   |
| Leven               | 61        | 83     | 0.5%    |
| ASMT                | 59        | 75     | 0.48%   |
| Netac               | 49        | 64     | 0.4%    |
| Corsair             | 47        | 65     | 0.39%   |
| Verbatim            | 46        | 75     | 0.38%   |
| INNOVATION IT       | 46        | 61     | 0.38%   |
| Unknown             | 45        | 54     | 0.37%   |
| PNY                 | 44        | 76     | 0.36%   |
| Apacer              | 44        | 51     | 0.36%   |
| Phison              | 41        | 72     | 0.34%   |
| Emtec               | 38        | 42     | 0.31%   |
| Unknown             | 34        | 36     | 0.28%   |
| Hewlett-Packard     | 29        | 36     | 0.24%   |
| ASMedia             | 27        | 30     | 0.22%   |
| Seagate             | 26        | 33     | 0.21%   |
| Fanxiang            | 25        | 33     | 0.21%   |
| KingDian            | 24        | 31     | 0.2%    |
| Team                | 22        | 30     | 0.18%   |
| Plextor             | 22        | 23     | 0.18%   |
| Mushkin             | 22        | 36     | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 10376     | 17166  | 36.08%  |
| HDD     | 9443      | 17859  | 32.84%  |
| NVMe    | 7072      | 10506  | 24.59%  |
| MMC     | 1322      | 1776   | 4.6%    |
| Unknown | 542       | 826    | 1.88%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 15841     | 33546  | 61.67%  |
| NVMe | 7064      | 10469  | 27.5%   |
| SAS  | 1460      | 2342   | 5.68%   |
| MMC  | 1322      | 1776   | 5.15%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 11855     | 19327  | 56.11%  |
| 0.51-1.0        | 5835      | 9377   | 27.61%  |
| 1.01-2.0        | 1957      | 3333   | 9.26%   |
| 3.01-4.0        | 648       | 1265   | 3.07%   |
| 2.01-3.0        | 386       | 714    | 1.83%   |
| 4.01-10.0       | 359       | 839    | 1.7%    |
| 10.01-20.0      | 81        | 154    | 0.38%   |
| 20.01-50.0      | 5         | 9      | 0.02%   |
| 0               | 2         | 2      | 0.01%   |
| More than 100.0 | 1         | 1      | 0.005%  |
| 50.01-100.0     | 1         | 4      | 0.005%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 5874      | 25.26%  |
| 251-500        | 4985      | 21.44%  |
| 501-1000       | 3471      | 14.93%  |
| 1001-2000      | 1906      | 8.2%    |
| 1-20           | 1759      | 7.57%   |
| 51-100         | 1425      | 6.13%   |
| More than 3000 | 1350      | 5.81%   |
| Unknown        | 899       | 3.87%   |
| 21-50          | 828       | 3.56%   |
| 2001-3000      | 753       | 3.24%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 8816      | 36.41%  |
| 21-50          | 3995      | 16.5%   |
| 101-250        | 2981      | 12.31%  |
| 51-100         | 2658      | 10.98%  |
| 251-500        | 1910      | 7.89%   |
| 501-1000       | 1316      | 5.44%   |
| Unknown        | 899       | 3.71%   |
| 1001-2000      | 846       | 3.49%   |
| More than 3000 | 465       | 1.92%   |
| 2001-3000      | 316       | 1.31%   |
| 0              | 9         | 0.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 23        | 34     | 1.43%   |
| Toshiba MQ01ABD100 1TB                | 15        | 20     | 0.93%   |
| Crucial CT525MX300SSD1 528GB          | 15        | 17     | 0.93%   |
| Seagate ST9500325AS 500GB             | 14        | 20     | 0.87%   |
| SanDisk SSD PLUS 480GB                | 14        | 16     | 0.87%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 13        | 17     | 0.81%   |
| Samsung Electronics HD103UJ 1TB       | 13        | 13     | 0.81%   |
| Seagate ST9320325AS 320GB             | 12        | 13     | 0.74%   |
| SanDisk SSD PLUS 1000GB               | 12        | 13     | 0.74%   |
| WDC WD20EFRX-68EUZN0 2TB              | 10        | 15     | 0.62%   |
| WDC WD20EARS-00MVWB0 2TB              | 10        | 13     | 0.62%   |
| Seagate ST500LT012-1DG142 500GB       | 10        | 10     | 0.62%   |
| Seagate ST1000LM035-1RK172 1TB        | 10        | 10     | 0.62%   |
| SanDisk SSD PLUS 240GB                | 10        | 12     | 0.62%   |
| Samsung Electronics HD103SI 1TB       | 10        | 11     | 0.62%   |
| HGST HTS725050A7E630 500GB            | 10        | 10     | 0.62%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 9         | 10     | 0.56%   |
| WDC WD10EARS-00Y5B1 1TB               | 9         | 11     | 0.56%   |
| Seagate ST3500418AS 500GB             | 9         | 10     | 0.56%   |
| Seagate ST31000528AS 1TB              | 9         | 10     | 0.56%   |
| Samsung Electronics SP2504C 250GB     | 9         | 10     | 0.56%   |
| Samsung Electronics HD501LJ 500GB     | 9         | 23     | 0.56%   |
| HGST HTS541010A9E680 1TB              | 9         | 9      | 0.56%   |
| WDC WD20EARX-00PASB0 2TB              | 8         | 8      | 0.5%    |
| Seagate ST500LT012-9WS142 500GB       | 8         | 10     | 0.5%    |
| Seagate ST500LM000-1EJ162 500GB       | 8         | 11     | 0.5%    |
| HGST HTS545050A7E680 500GB            | 8         | 12     | 0.5%    |
| WDC WD30EFRX-68EUZN0 3TB              | 7         | 10     | 0.43%   |
| WDC WD10JPVX-22JC3T0 1TB              | 7         | 9      | 0.43%   |
| SK hynix BC711 HFM512GD3JX013N 512GB  | 7         | 7      | 0.43%   |
| Seagate ST9250315AS 250GB             | 7         | 8      | 0.43%   |
| Seagate ST500LM000-SSHD-8GB           | 7         | 7      | 0.43%   |
| Seagate ST2000DL003-9VT166 2TB        | 7         | 7      | 0.43%   |
| Seagate ST1000DM003-9YN162 1TB        | 7         | 11     | 0.43%   |
| Samsung Electronics SSD 970 EVO 500GB | 7         | 8      | 0.43%   |
| Kingston SV300S37A120G 120GB SSD      | 7         | 8      | 0.43%   |
| HGST HTS721010A9E630 1TB              | 7         | 8      | 0.43%   |
| WDC WD5000AAKS-007AA0 500GB           | 6         | 22     | 0.37%   |
| WDC WD5000AADS-00S9B0 500GB           | 6         | 7      | 0.37%   |
| Toshiba DT01ACA100 1TB                | 6         | 8      | 0.37%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 375       | 475    | 23.72%  |
| WDC                   | 329       | 461    | 20.81%  |
| Samsung Electronics   | 210       | 265    | 13.28%  |
| Hitachi               | 115       | 140    | 7.27%   |
| Toshiba               | 96        | 109    | 6.07%   |
| SanDisk               | 87        | 101    | 5.5%    |
| Crucial               | 52        | 63     | 3.29%   |
| HGST                  | 48        | 58     | 3.04%   |
| SK hynix              | 35        | 38     | 2.21%   |
| Intel                 | 34        | 36     | 2.15%   |
| Micron Technology     | 26        | 36     | 1.64%   |
| Kingston              | 21        | 23     | 1.33%   |
| Intenso               | 20        | 22     | 1.27%   |
| Fujitsu               | 19        | 22     | 1.2%    |
| Maxtor                | 15        | 24     | 0.95%   |
| A-DATA Technology     | 14        | 15     | 0.89%   |
| Transcend             | 9         | 10     | 0.57%   |
| Apple                 | 9         | 10     | 0.57%   |
| OCZ                   | 5         | 7      | 0.32%   |
| ASMedia               | 5         | 5      | 0.32%   |
| WD MediaMax           | 4         | 4      | 0.25%   |
| IBM                   | 4         | 4      | 0.25%   |
| Unknown               | 3         | 3      | 0.19%   |
| MDT                   | 3         | 3      | 0.19%   |
| LITEONIT              | 3         | 6      | 0.19%   |
| China                 | 3         | 3      | 0.19%   |
| XPG                   | 2         | 2      | 0.13%   |
| PNY                   | 2         | 3      | 0.13%   |
| Plextor               | 2         | 2      | 0.13%   |
| LITEON                | 2         | 2      | 0.13%   |
| IBM/Hitachi           | 2         | 2      | 0.13%   |
| Corsair               | 2         | 2      | 0.13%   |
| ASMT                  | 2         | 3      | 0.13%   |
| Unknown               | 2         | 2      | 0.13%   |
| USB3.0                | 1         | 1      | 0.06%   |
| TO Exter              | 1         | 1      | 0.06%   |
| SSSTC                 | 1         | 1      | 0.06%   |
| SPCC                  | 1         | 1      | 0.06%   |
| Silicon Motion        | 1         | 1      | 0.06%   |
| Realtek Semiconductor | 1         | 1      | 0.06%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 374       | 474    | 33.36%  |
| WDC                 | 305       | 435    | 27.21%  |
| Samsung Electronics | 124       | 162    | 11.06%  |
| Hitachi             | 115       | 140    | 10.26%  |
| Toshiba             | 90        | 101    | 8.03%   |
| HGST                | 48        | 58     | 4.28%   |
| Fujitsu             | 19        | 22     | 1.69%   |
| Maxtor              | 15        | 24     | 1.34%   |
| Apple               | 7         | 8      | 0.62%   |
| WD MediaMax         | 4         | 4      | 0.36%   |
| IBM                 | 4         | 4      | 0.36%   |
| MDT                 | 3         | 3      | 0.27%   |
| Intenso             | 2         | 2      | 0.18%   |
| IBM/Hitachi         | 2         | 2      | 0.18%   |
| ASMT                | 2         | 3      | 0.18%   |
| USB3.0              | 1         | 1      | 0.09%   |
| Unknown             | 1         | 1      | 0.09%   |
| TO Exter            | 1         | 1      | 0.09%   |
| IB                  | 1         | 1      | 0.09%   |
| Hewlett-Packard     | 1         | 1      | 0.09%   |
| ExcelStor           | 1         | 1      | 0.09%   |
| ASMedia             | 1         | 1      | 0.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 1054      | 1449   | 69.99%  |
| SSD  | 380       | 450    | 25.23%  |
| NVMe | 72        | 84     | 4.78%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Samsung Electronics HD103UJ 1TB                  | 3         | 5      | 8.82%   |
| Samsung Electronics SSD 980 1TB                  | 2         | 2      | 5.88%   |
| Samsung Electronics HD252HJ 250GB                | 2         | 2      | 5.88%   |
| WDC WD5000BEVT-00A0RT0 500GB                     | 1         | 1      | 2.94%   |
| WDC WD40EZRZ-00GXCB0 4TB                         | 1         | 2      | 2.94%   |
| WDC WD30EZRS-00J99B0 3TB                         | 1         | 1      | 2.94%   |
| WDC WD1600YS-23SHB0 160GB                        | 1         | 1      | 2.94%   |
| WDC PC SN520 SDAPMUW-512G-1001 512GB             | 1         | 1      | 2.94%   |
| TPH00800640GB 640GB                              | 1         | 1      | 2.94%   |
| Toshiba MK5065GSX 500GB                          | 1         | 1      | 2.94%   |
| Toshiba MK3265GSX 320GB                          | 1         | 1      | 2.94%   |
| Toshiba MK1059GSM 1TB                            | 1         | 1      | 2.94%   |
| Toshiba MG03ACA300 3TB                           | 1         | 1      | 2.94%   |
| Seagate ST9500325AS 500GB                        | 1         | 1      | 2.94%   |
| Seagate ST9320325AS 320GB                        | 1         | 1      | 2.94%   |
| Seagate ST3640323AS 640GB                        | 1         | 1      | 2.94%   |
| Samsung Electronics SSD 980 500GB                | 1         | 1      | 2.94%   |
| Samsung Electronics SSD 850 250GB                | 1         | 1      | 2.94%   |
| Samsung Electronics MZVLB1T0HALR-00000 1TB       | 1         | 2      | 2.94%   |
| Samsung Electronics MZNTY128HDHP-00000 128GB SSD | 1         | 1      | 2.94%   |
| Samsung Electronics MZ7LN256HCHP-00000 256GB SSD | 1         | 2      | 2.94%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD   | 1         | 1      | 2.94%   |
| Maxtor STM3500320AS 500GB                        | 1         | 1      | 2.94%   |
| JMicron Technology Tech 250GB                    | 1         | 1      | 2.94%   |
| Intenso SSD SATAIII 512GB                        | 1         | 1      | 2.94%   |
| Intel SSDSCKGF256A5 SATA 256GB                   | 1         | 1      | 2.94%   |
| Intel SSDSA2BW160G3 160GB                        | 1         | 1      | 2.94%   |
| Hitachi HTS541010G9SA00 100GB                    | 1         | 1      | 2.94%   |
| Hitachi HDP725040GLA360 400GB                    | 1         | 1      | 2.94%   |
| HGST HTS721010A9E630 1TB                         | 1         | 1      | 2.94%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 16     | 35.29%  |
| WDC                 | 5         | 6      | 14.71%  |
| Toshiba             | 4         | 4      | 11.76%  |
| Seagate             | 3         | 3      | 8.82%   |
| Intel               | 2         | 2      | 5.88%   |
| Hitachi             | 2         | 2      | 5.88%   |
| TPH00800640GB       | 1         | 1      | 2.94%   |
| Micron Technology   | 1         | 1      | 2.94%   |
| Maxtor              | 1         | 1      | 2.94%   |
| JMicron Technology  | 1         | 1      | 2.94%   |
| Intenso             | 1         | 1      | 2.94%   |
| HGST                | 1         | 1      | 2.94%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 13355     | 29615  | 57.04%  |
| Works    | 8559      | 16495  | 36.55%  |
| Malfunc  | 1466      | 1983   | 6.26%   |
| Failed   | 34        | 39     | 0.15%   |
| Limited  | 1         | 1      | 0.004%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 13310     | 48.42%  |
| AMD                              | 4766      | 17.34%  |
| Samsung Electronics              | 3040      | 11.06%  |
| SanDisk                          | 1082      | 3.94%   |
| ASMedia Technology               | 552       | 2.01%   |
| SK hynix                         | 547       | 1.99%   |
| Kingston Technology Company      | 459       | 1.67%   |
| Phison Electronics               | 414       | 1.51%   |
| Nvidia                           | 408       | 1.48%   |
| Toshiba America Info Systems     | 344       | 1.25%   |
| Micron/Crucial Technology        | 337       | 1.23%   |
| Marvell Technology Group         | 337       | 1.23%   |
| JMicron Technology               | 335       | 1.22%   |
| Micron Technology                | 301       | 1.09%   |
| KIOXIA                           | 216       | 0.79%   |
| Silicon Motion                   | 141       | 0.51%   |
| VIA Technologies                 | 92        | 0.33%   |
| ADATA Technology                 | 89        | 0.32%   |
| LSI Logic / Symbios Logic        | 67        | 0.24%   |
| Union Memory (Shenzhen)          | 66        | 0.24%   |
| Silicon Image                    | 66        | 0.24%   |
| Broadcom / LSI                   | 63        | 0.23%   |
| Adaptec                          | 59        | 0.21%   |
| MAXIO Technology (Hangzhou)      | 43        | 0.16%   |
| Seagate Technology               | 42        | 0.15%   |
| Silicon Integrated Systems [SiS] | 36        | 0.13%   |
| Realtek Semiconductor            | 32        | 0.12%   |
| Solid State Storage Technology   | 30        | 0.11%   |
| Lenovo                           | 29        | 0.11%   |
| Apple                            | 29        | 0.11%   |
| Shenzhen Longsys Electronics     | 27        | 0.1%    |
| Lite-On Technology               | 22        | 0.08%   |
| Hewlett-Packard                  | 16        | 0.06%   |
| O2 Micro                         | 15        | 0.05%   |
| Integrated Technology Express    | 11        | 0.04%   |
| 3ware                            | 11        | 0.04%   |
| OCZ Technology Group             | 10        | 0.04%   |
| INNOGRIT                         | 7         | 0.03%   |
| Transcend                        | 5         | 0.02%   |
| ULi Electronics                  | 4         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 2954      | 9.26%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1673      | 5.24%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 973       | 3.05%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 959       | 3.01%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 955       | 2.99%   |
| AMD 400 Series Chipset SATA Controller                                         | 727       | 2.28%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 707       | 2.22%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 686       | 2.15%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 678       | 2.12%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 580       | 1.82%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 517       | 1.62%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 512       | 1.6%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 510       | 1.6%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 481       | 1.51%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 454       | 1.42%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 441       | 1.38%   |
| AMD 500 Series Chipset SATA Controller                                         | 433       | 1.36%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 431       | 1.35%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 427       | 1.34%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 388       | 1.22%   |
| Intel Volume Management Device NVMe RAID Controller                            | 361       | 1.13%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 354       | 1.11%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 348       | 1.09%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 347       | 1.09%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 336       | 1.05%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 332       | 1.04%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 329       | 1.03%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 285       | 0.89%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 274       | 0.86%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 271       | 0.85%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 269       | 0.84%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 248       | 0.78%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 236       | 0.74%   |
| Intel SATA Controller [RAID mode]                                              | 227       | 0.71%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 214       | 0.67%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 212       | 0.66%   |
| JMicron JMB363 SATA/IDE Controller                                             | 207       | 0.65%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 203       | 0.64%   |
| Intel SSD 660P Series                                                          | 199       | 0.62%   |
| Intel Comet Lake SATA AHCI Controller                                          | 199       | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 15932     | 57.43%  |
| NVMe | 7130      | 25.7%   |
| IDE  | 3090      | 11.14%  |
| RAID | 1417      | 5.11%   |
| SAS  | 95        | 0.34%   |
| SCSI | 78        | 0.28%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 15256     | 70.65%  |
| AMD                   | 6039      | 27.97%  |
| ARM                   | 271       | 1.25%   |
| Unknown               | 7         | 0.03%   |
| QUALCOMM              | 6         | 0.03%   |
| CentaurHauls          | 4         | 0.02%   |
| thead,c906            | 2         | 0.01%   |
| Marvell Semiconductor | 2         | 0.01%   |
| sifive,u74-mc         | 1         | 0.005%  |
| PowerMac3,6           | 1         | 0.005%  |
| PowerMac10,2          | 1         | 0.005%  |
| PowerBook5,6          | 1         | 0.005%  |
| PowerBook5,4          | 1         | 0.005%  |
| PowerBook3,4          | 1         | 0.005%  |
| MIPS                  | 1         | 0.005%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor             | 220       | 1.02%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 209       | 0.96%   |
| ARM Processor                                 | 192       | 0.89%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 186       | 0.86%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 182       | 0.84%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 179       | 0.83%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 174       | 0.8%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 170       | 0.78%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 169       | 0.78%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 167       | 0.77%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 148       | 0.68%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 147       | 0.68%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 146       | 0.67%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 143       | 0.66%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 139       | 0.64%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 134       | 0.62%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 133       | 0.61%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 129       | 0.6%    |
| AMD Ryzen 7 2700X Eight-Core Processor        | 124       | 0.57%   |
| AMD Custom APU 0405                           | 124       | 0.57%   |
| AMD FX-8350 Eight-Core Processor              | 117       | 0.54%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 114       | 0.53%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 112       | 0.52%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 111       | 0.51%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 110       | 0.51%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 108       | 0.5%    |
| AMD Ryzen 7 4700U with Radeon Graphics        | 99        | 0.46%   |
| AMD FX-6300 Six-Core Processor                | 95        | 0.44%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 91        | 0.42%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 90        | 0.42%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 88        | 0.41%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 88        | 0.41%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 87        | 0.4%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 87        | 0.4%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 84        | 0.39%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 84        | 0.39%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 84        | 0.39%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 83        | 0.38%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 80        | 0.37%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 80        | 0.37%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 4684      | 21.65%  |
| Intel Core i7           | 3606      | 16.67%  |
| Other                   | 1517      | 7.01%   |
| AMD Ryzen 5             | 1448      | 6.69%   |
| AMD Ryzen 7             | 1278      | 5.91%   |
| Intel Core i3           | 1219      | 5.63%   |
| Intel Core 2 Duo        | 964       | 4.46%   |
| Intel Celeron           | 895       | 4.14%   |
| Intel Pentium           | 591       | 2.73%   |
| Intel Xeon              | 471       | 2.18%   |
| AMD FX                  | 459       | 2.12%   |
| Intel Atom              | 435       | 2.01%   |
| AMD Ryzen 9             | 334       | 1.54%   |
| Intel Pentium Dual-Core | 239       | 1.1%    |
| AMD Ryzen 3             | 232       | 1.07%   |
| Intel Core 2 Quad       | 218       | 1.01%   |
| AMD A8                  | 190       | 0.88%   |
| AMD Phenom II X4        | 181       | 0.84%   |
| AMD Ryzen 7 PRO         | 168       | 0.78%   |
| Intel Pentium Silver    | 144       | 0.67%   |
| AMD A10                 | 144       | 0.67%   |
| AMD A4                  | 139       | 0.64%   |
| AMD Athlon II X2        | 131       | 0.61%   |
| AMD A6                  | 126       | 0.58%   |
| Intel Core 2            | 125       | 0.58%   |
| Intel Core i9           | 111       | 0.51%   |
| AMD E                   | 99        | 0.46%   |
| AMD Ryzen 5 PRO         | 95        | 0.44%   |
| Intel Pentium Dual      | 88        | 0.41%   |
| AMD Athlon 64 X2        | 80        | 0.37%   |
| AMD Athlon              | 74        | 0.34%   |
| Intel Genuine           | 71        | 0.33%   |
| AMD Athlon II X4        | 65        | 0.3%    |
| ARM BCM                 | 64        | 0.3%    |
| Intel Pentium 4         | 57        | 0.26%   |
| AMD Phenom II X6        | 51        | 0.24%   |
| AMD E2                  | 50        | 0.23%   |
| AMD Ryzen Threadripper  | 49        | 0.23%   |
| Intel Pentium M         | 46        | 0.21%   |
| AMD Turion 64 X2 Mobile | 46        | 0.21%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 8099      | 37.4%   |
| 4       | 8032      | 37.09%  |
| 6       | 2103      | 9.71%   |
| 8       | 1794      | 8.28%   |
| 1       | 512       | 2.36%   |
| 12      | 348       | 1.61%   |
| 16      | 184       | 0.85%   |
| 3       | 165       | 0.76%   |
| 10      | 139       | 0.64%   |
| 14      | 119       | 0.55%   |
| Unknown | 64        | 0.3%    |
| 24      | 37        | 0.17%   |
| 32      | 16        | 0.07%   |
| 18      | 11        | 0.05%   |
| 5       | 10        | 0.05%   |
| 20      | 7         | 0.03%   |
| 64      | 4         | 0.02%   |
| 40      | 4         | 0.02%   |
| 36      | 3         | 0.01%   |
| 80      | 2         | 0.01%   |
| 68      | 1         | 0.005%  |
| 52      | 1         | 0.005%  |
| 28      | 1         | 0.005%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 21402     | 99.11%  |
| 2       | 153       | 0.71%   |
| Unknown | 31        | 0.14%   |
| 4       | 7         | 0.03%   |
| 3       | 2         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 14047     | 64.91%  |
| 1       | 7522      | 34.76%  |
| Unknown | 64        | 0.3%    |
| 4       | 6         | 0.03%   |
| 8       | 2         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 20942     | 96.78%  |
| Unknown        | 452       | 2.09%   |
| 32-bit         | 219       | 1.01%   |
| 64-bit         | 26        | 0.12%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 6383      | 28.25%  |
| 0x206a7    | 1120      | 4.96%   |
| 0x306a9    | 1092      | 4.83%   |
| 0x306c3    | 899       | 3.98%   |
| 0x1067a    | 729       | 3.23%   |
| 0x506e3    | 433       | 1.92%   |
| 0x906ea    | 416       | 1.84%   |
| 0x806ea    | 410       | 1.81%   |
| 0x806ec    | 380       | 1.68%   |
| 0x806c1    | 379       | 1.68%   |
| 0x406e3    | 367       | 1.62%   |
| 0x40651    | 367       | 1.62%   |
| 0x20655    | 345       | 1.53%   |
| 0x08701021 | 339       | 1.5%    |
| 0x806e9    | 324       | 1.43%   |
| 0x906e9    | 279       | 1.23%   |
| 0x306d4    | 279       | 1.23%   |
| 0x010000c8 | 258       | 1.14%   |
| 0x0800820d | 256       | 1.13%   |
| 0x06000852 | 245       | 1.08%   |
| 0x08108109 | 234       | 1.04%   |
| 0x0a50000c | 224       | 0.99%   |
| 0x08600106 | 212       | 0.94%   |
| 0x6fd      | 211       | 0.93%   |
| 0x10676    | 210       | 0.93%   |
| 0x406c4    | 199       | 0.88%   |
| 0x30678    | 179       | 0.79%   |
| 0x08608103 | 173       | 0.77%   |
| 0x06001119 | 170       | 0.75%   |
| 0x08108102 | 168       | 0.74%   |
| 0x20652    | 164       | 0.73%   |
| 0x706a1    | 157       | 0.69%   |
| 0x6fb      | 145       | 0.64%   |
| 0x08701013 | 138       | 0.61%   |
| 0x506c9    | 135       | 0.6%    |
| 0x806eb    | 130       | 0.58%   |
| 0x106e5    | 125       | 0.55%   |
| 0x706a8    | 118       | 0.52%   |
| 0x706e5    | 114       | 0.5%    |
| 0xa0652    | 107       | 0.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 2872      | 13.26%  |
| Haswell          | 1759      | 8.12%   |
| SandyBridge      | 1531      | 7.07%   |
| IvyBridge        | 1481      | 6.84%   |
| Skylake          | 1193      | 5.51%   |
| Penryn           | 1168      | 5.39%   |
| Zen 2            | 1155      | 5.33%   |
| Unknown          | 1119      | 5.17%   |
| Zen+             | 847       | 3.91%   |
| Zen 3            | 759       | 3.5%    |
| Westmere         | 711       | 3.28%   |
| Silvermont       | 634       | 2.93%   |
| Core             | 605       | 2.79%   |
| Piledriver       | 575       | 2.66%   |
| K10              | 573       | 2.65%   |
| TigerLake        | 515       | 2.38%   |
| Zen              | 487       | 2.25%   |
| Broadwell        | 418       | 1.93%   |
| Goldmont plus    | 367       | 1.69%   |
| CometLake        | 324       | 1.5%    |
| Alderlake Hybrid | 311       | 1.44%   |
| Icelake          | 264       | 1.22%   |
| Nehalem          | 230       | 1.06%   |
| Excavator        | 212       | 0.98%   |
| K8 Hammer        | 204       | 0.94%   |
| Goldmont         | 186       | 0.86%   |
| Bonnell          | 185       | 0.85%   |
| Bobcat           | 171       | 0.79%   |
| Puma             | 128       | 0.59%   |
| P6               | 117       | 0.54%   |
| NetBurst         | 97        | 0.45%   |
| Bulldozer        | 92        | 0.42%   |
| Jaguar           | 89        | 0.41%   |
| Steamroller      | 84        | 0.39%   |
| K10 Llano        | 68        | 0.31%   |
| Tremont          | 65        | 0.3%    |
| K8 & K10 hybrid  | 39        | 0.18%   |
| Gracemont        | 12        | 0.06%   |
| K6               | 7         | 0.03%   |
| CannonLake       | 1         | 0.005%  |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 11402     | 46.4%   |
| Nvidia                                       | 6589      | 26.81%  |
| AMD                                          | 6325      | 25.74%  |
| ASPEED Technology                            | 101       | 0.41%   |
| Matrox Electronics Systems                   | 98        | 0.4%    |
| Silicon Integrated Systems [SiS]             | 18        | 0.07%   |
| VIA Technologies                             | 17        | 0.07%   |
| ATI Technologies                             | 10        | 0.04%   |
| S3 Graphics                                  | 8         | 0.03%   |
| XGI Technology (eXtreme Graphics Innovation) | 3         | 0.01%   |
| Silicon Motion                               | 1         | 0.004%  |
| Neomagic                                     | 1         | 0.004%  |
| Huawei Technologies                          | 1         | 0.004%  |
| Dome Imaging Systems                         | 1         | 0.004%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1059      | 4.18%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 881       | 3.48%   |
| Intel UHD Graphics 620                                                                   | 497       | 1.96%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 489       | 1.93%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 473       | 1.87%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 462       | 1.82%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 453       | 1.79%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 450       | 1.78%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 418       | 1.65%   |
| Intel HD Graphics 620                                                                    | 395       | 1.56%   |
| Intel Core Processor Integrated Graphics Controller                                      | 390       | 1.54%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 385       | 1.52%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 368       | 1.45%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 358       | 1.41%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 354       | 1.4%    |
| Intel HD Graphics 530                                                                    | 348       | 1.37%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 346       | 1.37%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 314       | 1.24%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 302       | 1.19%   |
| Intel HD Graphics 5500                                                                   | 296       | 1.17%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 286       | 1.13%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 284       | 1.12%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 272       | 1.07%   |
| AMD Lucienne                                                                             | 253       | 1%      |
| Intel HD Graphics 630                                                                    | 241       | 0.95%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 230       | 0.91%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 204       | 0.81%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 192       | 0.76%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 179       | 0.71%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 178       | 0.7%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 162       | 0.64%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 161       | 0.64%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 151       | 0.6%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 142       | 0.56%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 142       | 0.56%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 140       | 0.55%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 135       | 0.53%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 135       | 0.53%   |
| Intel HD Graphics 500                                                                    | 129       | 0.51%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 122       | 0.48%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| 1 x Intel                         | 8518      | 39.12%  |
| 1 x AMD                           | 5321      | 24.44%  |
| 1 x Nvidia                        | 4043      | 18.57%  |
| Intel + Nvidia                    | 2190      | 10.06%  |
| Intel + AMD                       | 457       | 2.1%    |
| Other                             | 309       | 1.42%   |
| 2 x AMD                           | 291       | 1.34%   |
| AMD + Nvidia                      | 261       | 1.2%    |
| 1 x Matrox                        | 86        | 0.39%   |
| 2 x Nvidia                        | 82        | 0.38%   |
| 1 x ASPEED                        | 75        | 0.34%   |
| 2 x Intel                         | 44        | 0.2%    |
| 1 x SiS                           | 18        | 0.08%   |
| 1 x VIA                           | 17        | 0.08%   |
| Nvidia + ASPEED                   | 15        | 0.07%   |
| AMD + ASPEED                      | 9         | 0.04%   |
| 1 x S3 Graphics                   | 8         | 0.04%   |
| Nvidia + Matrox                   | 7         | 0.03%   |
| AMD + Matrox                      | 4         | 0.02%   |
| Nvidia + XGI                      | 2         | 0.01%   |
| Intel + 2 x Nvidia                | 2         | 0.01%   |
| Intel + AMD + 1 x Nvidia          | 2         | 0.01%   |
| 5 x AMD                           | 1         | 0.005%  |
| 4 x Nvidia                        | 1         | 0.005%  |
| 2 x Nvidia + 1 x Matrox           | 1         | 0.005%  |
| 2 x Nvidia + 1 x ASPEED           | 1         | 0.005%  |
| 2 x Intel + 1 x Nvidia            | 1         | 0.005%  |
| 2 x AMD + 1 x Nvidia + 1 x ASPEED | 1         | 0.005%  |
| 1 x Silicon Motion                | 1         | 0.005%  |
| Nvidia + Dome Imaging Systems     | 1         | 0.005%  |
| 1 x Neomagic                      | 1         | 0.005%  |
| 1 x Intel + 4 x AMD               | 1         | 0.005%  |
| Intel + ASPEED                    | 1         | 0.005%  |
| 1 x Huawei Technologies           | 1         | 0.005%  |
| AMD + XGI                         | 1         | 0.005%  |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 17414     | 79.22%  |
| Proprietary | 3412      | 15.52%  |
| Unknown     | 1157      | 5.26%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 12255     | 54.74%  |
| 1.01-2.0       | 2619      | 11.7%   |
| 0.01-0.5       | 2582      | 11.53%  |
| 0.51-1.0       | 1726      | 7.71%   |
| 3.01-4.0       | 1333      | 5.95%   |
| 7.01-8.0       | 990       | 4.42%   |
| 5.01-6.0       | 412       | 1.84%   |
| 8.01-16.0      | 307       | 1.37%   |
| 2.01-3.0       | 112       | 0.5%    |
| 16.01-24.0     | 41        | 0.18%   |
| 4.01-5.0       | 10        | 0.04%   |
| More than 64.0 | 1         | 0.004%  |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 2940      | 12.58%  |
| AU Optronics            | 2633      | 11.26%  |
| LG Display              | 2064      | 8.83%   |
| Chimei Innolux          | 1623      | 6.94%   |
| BOE                     | 1468      | 6.28%   |
| Dell                    | 1128      | 4.83%   |
| Goldstar                | 1110      | 4.75%   |
| Acer                    | 923       | 3.95%   |
| BenQ                    | 829       | 3.55%   |
| Hewlett-Packard         | 607       | 2.6%    |
| Ancor Communications    | 595       | 2.55%   |
| Lenovo                  | 583       | 2.49%   |
| AOC                     | 481       | 2.06%   |
| Philips                 | 465       | 1.99%   |
| Apple                   | 388       | 1.66%   |
| Iiyama                  | 384       | 1.64%   |
| Sharp                   | 366       | 1.57%   |
| Fujitsu Siemens         | 364       | 1.56%   |
| Chi Mei Optoelectronics | 327       | 1.4%    |
| Eizo                    | 311       | 1.33%   |
| Medion                  | 217       | 0.93%   |
| PANDA                   | 181       | 0.77%   |
| ASUSTek Computer        | 175       | 0.75%   |
| Sony                    | 163       | 0.7%    |
| InfoVision              | 158       | 0.68%   |
| HannStar                | 142       | 0.61%   |
| Unknown                 | 140       | 0.6%    |
| ViewSonic               | 137       | 0.59%   |
| LG Philips              | 136       | 0.58%   |
| NEC Computers           | 132       | 0.56%   |
| Panasonic               | 128       | 0.55%   |
| LG Electronics          | 125       | 0.53%   |
| CSO                     | 105       | 0.45%   |
| Valve                   | 95        | 0.41%   |
| Vestel Elektronik       | 85        | 0.36%   |
| Compal                  | 81        | 0.35%   |
| Belinea                 | 79        | 0.34%   |
| Toshiba                 | 68        | 0.29%   |
| CPT                     | 61        | 0.26%   |
| MSI                     | 59        | 0.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch    | 85        | 0.35%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                       | 85        | 0.35%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch             | 85        | 0.35%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 83        | 0.34%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 81        | 0.33%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 72        | 0.3%    |
| BenQ GL2450H BNQ78A7 1920x1080 530x300mm 24.0-inch                        | 67        | 0.28%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 65        | 0.27%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 63        | 0.26%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch         | 62        | 0.25%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch                   | 61        | 0.25%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch              | 59        | 0.24%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                     | 57        | 0.23%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch         | 56        | 0.23%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 55        | 0.23%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 54        | 0.22%   |
| Grundig WUXGA GRU4448 1920x1080                                           | 53        | 0.22%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch          | 53        | 0.22%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch          | 52        | 0.21%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 52        | 0.21%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch               | 50        | 0.21%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch          | 49        | 0.2%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch         | 48        | 0.2%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 48        | 0.2%    |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                        | 47        | 0.19%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch               | 47        | 0.19%   |
| Dell U2412M DELA07A 1920x1200 520x320mm 24.0-inch                         | 47        | 0.19%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch            | 47        | 0.19%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch           | 46        | 0.19%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 45        | 0.19%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 45        | 0.19%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 380x210mm 17.1-inch | 44        | 0.18%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch             | 44        | 0.18%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch     | 44        | 0.18%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                  | 43        | 0.18%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 43        | 0.18%   |
| BOE LCD Monitor BOE0660 1600x900 382x215mm 17.3-inch                      | 43        | 0.18%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch             | 43        | 0.18%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch            | 43        | 0.18%   |
| AU Optronics LCD Monitor AUO219E 1600x900 382x214mm 17.2-inch             | 40        | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 9800      | 43.65%  |
| 1366x768 (WXGA)    | 2614      | 11.64%  |
| 3840x2160 (4K)     | 1621      | 7.22%   |
| 2560x1440 (QHD)    | 1271      | 5.66%   |
| 1600x900 (HD+)     | 1230      | 5.48%   |
| 1680x1050 (WSXGA+) | 904       | 4.03%   |
| 1280x1024 (SXGA)   | 850       | 3.79%   |
| 1920x1200 (WUXGA)  | 773       | 3.44%   |
| 1280x800 (WXGA)    | 542       | 2.41%   |
| 1440x900 (WXGA+)   | 416       | 1.85%   |
| Unknown            | 326       | 1.45%   |
| 3440x1440          | 283       | 1.26%   |
| 2560x1600          | 173       | 0.77%   |
| 3840x1080          | 169       | 0.75%   |
| 2560x1080          | 116       | 0.52%   |
| 2880x1800          | 106       | 0.47%   |
| 800x1280           | 105       | 0.47%   |
| 1024x600           | 88        | 0.39%   |
| 1600x1200          | 84        | 0.37%   |
| 1920x540           | 82        | 0.37%   |
| 1024x768 (XGA)     | 77        | 0.34%   |
| 1360x768           | 72        | 0.32%   |
| 3840x2400          | 66        | 0.29%   |
| 2160x1440          | 59        | 0.26%   |
| 3200x1800 (QHD+)   | 40        | 0.18%   |
| 2736x1824          | 39        | 0.17%   |
| 3840x1600          | 38        | 0.17%   |
| 1920x1280          | 36        | 0.16%   |
| 2256x1504          | 30        | 0.13%   |
| 3840x1200          | 26        | 0.12%   |
| 1280x720 (HD)      | 25        | 0.11%   |
| 2288x1287          | 23        | 0.1%    |
| 4480x1440          | 22        | 0.1%    |
| 1680x945           | 22        | 0.1%    |
| 3000x2000          | 21        | 0.09%   |
| 1400x1050          | 19        | 0.08%   |
| 2048x1152          | 18        | 0.08%   |
| 5760x2160          | 16        | 0.07%   |
| 3200x1080          | 14        | 0.06%   |
| 3072x1920          | 12        | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 4820      | 20.72%  |
| 24      | 2163      | 9.3%    |
| 27      | 2161      | 9.29%   |
| 17      | 1851      | 7.96%   |
| 13      | 1772      | 7.62%   |
| 14      | 1586      | 6.82%   |
| 23      | 1403      | 6.03%   |
| Unknown | 1295      | 5.57%   |
| 21      | 952       | 4.09%   |
| 19      | 699       | 3%      |
| 22      | 646       | 2.78%   |
| 12      | 485       | 2.08%   |
| 31      | 475       | 2.04%   |
| 34      | 306       | 1.32%   |
| 84      | 259       | 1.11%   |
| 11      | 238       | 1.02%   |
| 20      | 215       | 0.92%   |
| 16      | 215       | 0.92%   |
| 18      | 192       | 0.83%   |
| 10      | 143       | 0.61%   |
| 40      | 142       | 0.61%   |
| 72      | 138       | 0.59%   |
| 54      | 135       | 0.58%   |
| 25      | 116       | 0.5%    |
| 32      | 113       | 0.49%   |
| 7       | 93        | 0.4%    |
| 28      | 69        | 0.3%    |
| 26      | 53        | 0.23%   |
| 65      | 51        | 0.22%   |
| 48      | 48        | 0.21%   |
| 37      | 42        | 0.18%   |
| 33      | 39        | 0.17%   |
| 52      | 33        | 0.14%   |
| 35      | 33        | 0.14%   |
| 42      | 27        | 0.12%   |
| 36      | 26        | 0.11%   |
| 49      | 24        | 0.1%    |
| 3       | 23        | 0.1%    |
| 142     | 21        | 0.09%   |
| 55      | 21        | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 7365      | 32.23%  |
| 501-600        | 5255      | 23%     |
| 351-400        | 2386      | 10.44%  |
| 401-500        | 2142      | 9.37%   |
| 201-300        | 1925      | 8.42%   |
| Unknown        | 1295      | 5.67%   |
| 601-700        | 802       | 3.51%   |
| 701-800        | 483       | 2.11%   |
| 1501-2000      | 403       | 1.76%   |
| 1001-1500      | 370       | 1.62%   |
| 801-900        | 234       | 1.02%   |
| 1-100          | 105       | 0.46%   |
| 901-1000       | 45        | 0.2%    |
| More than 2000 | 22        | 0.1%    |
| 101-200        | 18        | 0.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 15059     | 71.1%   |
| 16/10   | 2995      | 14.14%  |
| Unknown | 1107      | 5.23%   |
| 5/4     | 781       | 3.69%   |
| 21/9    | 400       | 1.89%   |
| 3/2     | 316       | 1.49%   |
| 4/3     | 218       | 1.03%   |
| 0.67    | 85        | 0.4%    |
| 32/9    | 83        | 0.39%   |
| 6/5     | 79        | 0.37%   |
| 1.00    | 23        | 0.11%   |
| 0.56    | 9         | 0.04%   |
| 3.20    | 5         | 0.02%   |
| 0.62    | 5         | 0.02%   |
| 3.73    | 4         | 0.02%   |
| 0.89    | 2         | 0.01%   |
| 3.40    | 1         | 0.005%  |
| 2.00    | 1         | 0.005%  |
| 1.96    | 1         | 0.005%  |
| 0.75    | 1         | 0.005%  |
| 0.65    | 1         | 0.005%  |
| 0.63    | 1         | 0.005%  |
| 0.45    | 1         | 0.005%  |
| 0.25    | 1         | 0.005%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 4816      | 20.89%  |
| 201-250        | 3962      | 17.18%  |
| 81-90          | 2489      | 10.8%   |
| 301-350        | 2204      | 9.56%   |
| 121-130        | 1404      | 6.09%   |
| Unknown        | 1295      | 5.62%   |
| 151-200        | 1201      | 5.21%   |
| 351-500        | 1036      | 4.49%   |
| 251-300        | 923       | 4%      |
| 71-80          | 864       | 3.75%   |
| More than 1000 | 705       | 3.06%   |
| 61-70          | 454       | 1.97%   |
| 141-150        | 381       | 1.65%   |
| 501-1000       | 349       | 1.51%   |
| 131-140        | 255       | 1.11%   |
| 51-60          | 247       | 1.07%   |
| 111-120        | 157       | 0.68%   |
| 41-50          | 134       | 0.58%   |
| 1-40           | 123       | 0.53%   |
| 91-100         | 57        | 0.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 7742      | 34.62%  |
| 121-160       | 5746      | 25.7%   |
| 101-120       | 5093      | 22.78%  |
| 161-240       | 1567      | 7.01%   |
| Unknown       | 1295      | 5.79%   |
| More than 240 | 498       | 2.23%   |
| 1-50          | 419       | 1.87%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 17216     | 77.63%  |
| 2     | 3262      | 14.71%  |
| 0     | 1200      | 5.41%   |
| 3     | 452       | 2.04%   |
| 4     | 45        | 0.2%    |
| 5     | 3         | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 10995     | 34.53%  |
| Intel                             | 10894     | 34.22%  |
| Qualcomm Atheros                  | 3122      | 9.81%   |
| Broadcom                          | 1680      | 5.28%   |
| MediaTek                          | 405       | 1.27%   |
| Marvell Technology Group          | 370       | 1.16%   |
| Broadcom Limited                  | 363       | 1.14%   |
| Nvidia                            | 328       | 1.03%   |
| Ralink Technology                 | 268       | 0.84%   |
| Sierra Wireless                   | 261       | 0.82%   |
| TP-Link                           | 249       | 0.78%   |
| ASIX Electronics                  | 201       | 0.63%   |
| Ralink                            | 194       | 0.61%   |
| Ericsson Business Mobile Networks | 194       | 0.61%   |
| Dell                              | 181       | 0.57%   |
| Lenovo                            | 144       | 0.45%   |
| AVM                               | 139       | 0.44%   |
| Microsoft                         | 135       | 0.42%   |
| DisplayLink                       | 103       | 0.32%   |
| Samsung Electronics               | 101       | 0.32%   |
| Hewlett-Packard                   | 92        | 0.29%   |
| Edimax Technology                 | 92        | 0.29%   |
| Huawei Technologies               | 90        | 0.28%   |
| D-Link System                     | 77        | 0.24%   |
| Aquantia                          | 67        | 0.21%   |
| Fibocom                           | 66        | 0.21%   |
| IMC Networks                      | 64        | 0.2%    |
| ASUSTek Computer                  | 64        | 0.2%    |
| D-Link                            | 58        | 0.18%   |
| Qualcomm Atheros Communications   | 50        | 0.16%   |
| Qualcomm                          | 49        | 0.15%   |
| VIA Technologies                  | 42        | 0.13%   |
| Microchip Technology              | 42        | 0.13%   |
| NetGear                           | 41        | 0.13%   |
| JMicron Technology                | 37        | 0.12%   |
| Xiaomi                            | 34        | 0.11%   |
| Belkin Components                 | 28        | 0.09%   |
| Silicon Integrated Systems [SiS]  | 27        | 0.08%   |
| Mellanox Technologies             | 25        | 0.08%   |
| Sitecom Europe                    | 22        | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7888      | 20.83%  |
| Intel Wi-Fi 6 AX200                                               | 988       | 2.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 945       | 2.5%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 739       | 1.95%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 713       | 1.88%   |
| Intel Wireless 8265 / 8275                                        | 697       | 1.84%   |
| Intel I211 Gigabit Network Connection                             | 584       | 1.54%   |
| Realtek RTL8125 2.5GbE Controller                                 | 534       | 1.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 479       | 1.26%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 463       | 1.22%   |
| Intel Wireless 7260                                               | 462       | 1.22%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 458       | 1.21%   |
| Intel Wireless 8260                                               | 443       | 1.17%   |
| Intel Wireless 7265                                               | 388       | 1.02%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 385       | 1.02%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 378       | 1%      |
| Intel Wi-Fi 6 AX201                                               | 378       | 1%      |
| Intel Ethernet Connection (2) I219-V                              | 353       | 0.93%   |
| Intel Ethernet Connection I217-LM                                 | 331       | 0.87%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 311       | 0.82%   |
| Intel Wireless 3165                                               | 300       | 0.79%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 268       | 0.71%   |
| Intel Wireless-AC 9260                                            | 262       | 0.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 257       | 0.68%   |
| Intel 82579V Gigabit Network Connection                           | 249       | 0.66%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 246       | 0.65%   |
| Intel Ethernet Controller I225-V                                  | 246       | 0.65%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 239       | 0.63%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 238       | 0.63%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 231       | 0.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 212       | 0.56%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 201       | 0.53%   |
| Intel Ethernet Connection I219-LM                                 | 198       | 0.52%   |
| Intel Wireless 3160                                               | 196       | 0.52%   |
| Intel Centrino Ultimate-N 6300                                    | 195       | 0.51%   |
| Intel 82577LM Gigabit Network Connection                          | 190       | 0.5%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 185       | 0.49%   |
| Intel Ethernet Connection I217-V                                  | 185       | 0.49%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 183       | 0.48%   |
| Intel Ethernet Connection (2) I219-LM                             | 182       | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 7957      | 47.91%  |
| Realtek Semiconductor                 | 2598      | 15.64%  |
| Qualcomm Atheros                      | 2376      | 14.31%  |
| Broadcom                              | 1022      | 6.15%   |
| MediaTek                              | 393       | 2.37%   |
| Ralink Technology                     | 268       | 1.61%   |
| Sierra Wireless                       | 261       | 1.57%   |
| TP-Link                               | 237       | 1.43%   |
| Ralink                                | 194       | 1.17%   |
| Broadcom Limited                      | 175       | 1.05%   |
| AVM                                   | 139       | 0.84%   |
| Microsoft                             | 125       | 0.75%   |
| Dell                                  | 117       | 0.7%    |
| Edimax Technology                     | 89        | 0.54%   |
| Fibocom                               | 66        | 0.4%    |
| IMC Networks                          | 64        | 0.39%   |
| D-Link System                         | 64        | 0.39%   |
| ASUSTek Computer                      | 63        | 0.38%   |
| D-Link                                | 53        | 0.32%   |
| Qualcomm Atheros Communications       | 50        | 0.3%    |
| Marvell Technology Group              | 43        | 0.26%   |
| NetGear                               | 40        | 0.24%   |
| Qualcomm                              | 38        | 0.23%   |
| Ericsson Business Mobile Networks     | 27        | 0.16%   |
| Belkin Components                     | 25        | 0.15%   |
| Sitecom Europe                        | 21        | 0.13%   |
| Hewlett-Packard                       | 19        | 0.11%   |
| ZyXEL Communications                  | 11        | 0.07%   |
| ZyDAS                                 | 10        | 0.06%   |
| Wacom                                 | 7         | 0.04%   |
| Linksys                               | 7         | 0.04%   |
| Philips (or NXP)                      | 4         | 0.02%   |
| Fujitsu Siemens Computers             | 4         | 0.02%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 4         | 0.02%   |
| Winbond Electronics                   | 3         | 0.02%   |
| Texas Instruments                     | 3         | 0.02%   |
| Quectel Wireless Solutions            | 3         | 0.02%   |
| Gemtek                                | 3         | 0.02%   |
| Tenda                                 | 2         | 0.01%   |
| Sweex                                 | 2         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 988       | 5.91%   |
| Intel Wireless 8265 / 8275                                              | 697       | 4.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 479       | 2.86%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 463       | 2.77%   |
| Intel Wireless 7260                                                     | 462       | 2.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 458       | 2.74%   |
| Intel Wireless 8260                                                     | 443       | 2.65%   |
| Intel Wireless 7265                                                     | 388       | 2.32%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 385       | 2.3%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 378       | 2.26%   |
| Intel Wi-Fi 6 AX201                                                     | 378       | 2.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 311       | 1.86%   |
| Intel Wireless 3165                                                     | 300       | 1.79%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 268       | 1.6%    |
| Intel Wireless-AC 9260                                                  | 262       | 1.57%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 246       | 1.47%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 239       | 1.43%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 238       | 1.42%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 231       | 1.38%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 212       | 1.27%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 201       | 1.2%    |
| Intel Wireless 3160                                                     | 196       | 1.17%   |
| Intel Centrino Ultimate-N 6300                                          | 195       | 1.17%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 185       | 1.11%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 183       | 1.09%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 178       | 1.06%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 178       | 1.06%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 169       | 1.01%   |
| Broadcom BCM43142 802.11b/g/n                                           | 167       | 1%      |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 160       | 0.96%   |
| Intel WiFi Link 5100                                                    | 157       | 0.94%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 153       | 0.91%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 148       | 0.88%   |
| Intel Centrino Advanced-N 6200                                          | 141       | 0.84%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 140       | 0.84%   |
| Intel Centrino Wireless-N 2230                                          | 136       | 0.81%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 132       | 0.79%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 126       | 0.75%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 123       | 0.74%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 121       | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 9956      | 49.6%   |
| Intel                            | 6155      | 30.66%  |
| Qualcomm Atheros                 | 1115      | 5.55%   |
| Broadcom                         | 882       | 4.39%   |
| Nvidia                           | 328       | 1.63%   |
| Marvell Technology Group         | 327       | 1.63%   |
| ASIX Electronics                 | 201       | 1%      |
| Broadcom Limited                 | 195       | 0.97%   |
| Lenovo                           | 142       | 0.71%   |
| DisplayLink                      | 103       | 0.51%   |
| Samsung Electronics              | 68        | 0.34%   |
| Aquantia                         | 67        | 0.33%   |
| Huawei Technologies              | 42        | 0.21%   |
| VIA Technologies                 | 41        | 0.2%    |
| Microchip Technology             | 37        | 0.18%   |
| JMicron Technology               | 37        | 0.18%   |
| Xiaomi                           | 34        | 0.17%   |
| Hewlett-Packard                  | 29        | 0.14%   |
| Silicon Integrated Systems [SiS] | 25        | 0.12%   |
| Mellanox Technologies            | 21        | 0.1%    |
| Google                           | 20        | 0.1%    |
| 3Com                             | 18        | 0.09%   |
| Apple                            | 16        | 0.08%   |
| American Megatrends              | 16        | 0.08%   |
| D-Link System                    | 13        | 0.06%   |
| TP-Link                          | 12        | 0.06%   |
| Standard Microsystems            | 11        | 0.05%   |
| Qualcomm                         | 11        | 0.05%   |
| MediaTek                         | 11        | 0.05%   |
| Attansic Technology              | 11        | 0.05%   |
| Microsoft                        | 10        | 0.05%   |
| ICS Advent                       | 7         | 0.03%   |
| ZTE WCDMA Technologies MSM       | 6         | 0.03%   |
| OPPO Electronics                 | 6         | 0.03%   |
| HMD Global                       | 6         | 0.03%   |
| Emulex                           | 6         | 0.03%   |
| OnePlus Technology (Shenzhen)    | 5         | 0.02%   |
| D-Link                           | 5         | 0.02%   |
| ADMtek                           | 5         | 0.02%   |
| Motorola PCS                     | 4         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7888      | 38.37%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 945       | 4.6%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 739       | 3.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 713       | 3.47%   |
| Intel I211 Gigabit Network Connection                             | 584       | 2.84%   |
| Realtek RTL8125 2.5GbE Controller                                 | 534       | 2.6%    |
| Intel Ethernet Connection (2) I219-V                              | 353       | 1.72%   |
| Intel Ethernet Connection I217-LM                                 | 331       | 1.61%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 257       | 1.25%   |
| Intel 82579V Gigabit Network Connection                           | 249       | 1.21%   |
| Intel Ethernet Controller I225-V                                  | 246       | 1.2%    |
| Intel Ethernet Connection I219-LM                                 | 198       | 0.96%   |
| Intel 82577LM Gigabit Network Connection                          | 190       | 0.92%   |
| Intel Ethernet Connection I217-V                                  | 185       | 0.9%    |
| Intel Ethernet Connection (2) I219-LM                             | 182       | 0.89%   |
| Intel Ethernet Connection (4) I219-V                              | 171       | 0.83%   |
| Intel Ethernet Connection (4) I219-LM                             | 170       | 0.83%   |
| Intel I210 Gigabit Network Connection                             | 166       | 0.81%   |
| ASIX AX88179 Gigabit Ethernet                                     | 164       | 0.8%    |
| Intel Ethernet Connection (7) I219-V                              | 163       | 0.79%   |
| Intel 82567LM Gigabit Network Connection                          | 138       | 0.67%   |
| Intel Ethernet Connection I218-LM                                 | 137       | 0.67%   |
| Intel Ethernet Connection (3) I218-LM                             | 129       | 0.63%   |
| Intel Ethernet Connection (6) I219-V                              | 127       | 0.62%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 124       | 0.6%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 114       | 0.55%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 114       | 0.55%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 111       | 0.54%   |
| Nvidia MCP61 Ethernet                                             | 108       | 0.53%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 107       | 0.52%   |
| Intel Ethernet Connection (7) I219-LM                             | 103       | 0.5%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 103       | 0.5%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 102       | 0.5%    |
| Intel Ethernet Connection (2) I218-V                              | 97        | 0.47%   |
| Intel Ethernet Connection I219-V                                  | 94        | 0.46%   |
| Intel 82574L Gigabit Network Connection                           | 93        | 0.45%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 87        | 0.42%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 86        | 0.42%   |
| Intel Ethernet Connection (10) I219-V                             | 85        | 0.41%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 80        | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 18923     | 54.1%   |
| WiFi     | 15474     | 44.24%  |
| Modem    | 532       | 1.52%   |
| Unknown  | 49        | 0.14%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 11359     | 50.48%  |
| Ethernet | 11136     | 49.48%  |
| Unknown  | 5         | 0.02%   |
| Modem    | 4         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 11437     | 52.77%  |
| 1     | 9137      | 42.16%  |
| 0     | 506       | 2.33%   |
| 3     | 448       | 2.07%   |
| 4     | 81        | 0.37%   |
| 5     | 26        | 0.12%   |
| 6     | 18        | 0.08%   |
| 8     | 9         | 0.04%   |
| 7     | 6         | 0.03%   |
| 18    | 2         | 0.01%   |
| 10    | 2         | 0.01%   |
| 12    | 1         | 0.005%  |
| 9     | 1         | 0.005%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 13844     | 61.9%   |
| Yes  | 8522      | 38.1%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 5937      | 48.07%  |
| Realtek Semiconductor           | 1287      | 10.42%  |
| Cambridge Silicon Radio         | 862       | 6.98%   |
| Broadcom                        | 722       | 5.85%   |
| Qualcomm Atheros Communications | 570       | 4.62%   |
| Foxconn / Hon Hai               | 479       | 3.88%   |
| IMC Networks                    | 468       | 3.79%   |
| Lite-On Technology              | 432       | 3.5%    |
| Apple                           | 397       | 3.21%   |
| ASUSTek Computer                | 206       | 1.67%   |
| Dell                            | 205       | 1.66%   |
| MediaTek                        | 113       | 0.91%   |
| Hewlett-Packard                 | 108       | 0.87%   |
| Toshiba                         | 81        | 0.66%   |
| Realtek                         | 71        | 0.57%   |
| Foxconn International           | 48        | 0.39%   |
| Marvell Semiconductor           | 40        | 0.32%   |
| Askey Computer                  | 36        | 0.29%   |
| Alps Electric                   | 35        | 0.28%   |
| TP-Link                         | 31        | 0.25%   |
| Integrated System Solution      | 27        | 0.22%   |
| Ralink                          | 26        | 0.21%   |
| Belkin Components               | 24        | 0.19%   |
| Edimax Technology               | 21        | 0.17%   |
| USI                             | 19        | 0.15%   |
| Taiyo Yuden                     | 19        | 0.15%   |
| Chicony Electronics             | 13        | 0.11%   |
| Qcom                            | 12        | 0.1%    |
| Ralink Technology               | 9         | 0.07%   |
| Logitech                        | 8         | 0.06%   |
| HTC (High Tech Computer)        | 7         | 0.06%   |
| Fujitsu                         | 7         | 0.06%   |
| Unknown                         | 5         | 0.04%   |
| Micro Star International        | 4         | 0.03%   |
| Actions                         | 4         | 0.03%   |
| SINO WEALTH                     | 2         | 0.02%   |
| Motorola PCS                    | 2         | 0.02%   |
| Fujitsu Siemens Computers       | 2         | 0.02%   |
| Conwise Technology              | 2         | 0.02%   |
| AVM                             | 2         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 2322      | 18.78%  |
| Intel Bluetooth Device                              | 1101      | 8.91%   |
| Intel AX200 Bluetooth                               | 930       | 7.52%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 861       | 6.97%   |
| Realtek Bluetooth Radio                             | 838       | 6.78%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 669       | 5.41%   |
| Realtek  Bluetooth 4.2 Adapter                      | 309       | 2.5%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 248       | 2.01%   |
| Intel Wireless-AC 3168 Bluetooth                    | 230       | 1.86%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 219       | 1.77%   |
| Qualcomm Atheros  Bluetooth Device                  | 206       | 1.67%   |
| Apple Bluetooth Host Controller                     | 160       | 1.29%   |
| Intel AX210 Bluetooth                               | 155       | 1.25%   |
| Broadcom BCM2045B (BDC-2.1)                         | 152       | 1.23%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 136       | 1.1%    |
| Lite-On Bluetooth Device                            | 132       | 1.07%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 131       | 1.06%   |
| Foxconn / Hon Hai Bluetooth Device                  | 128       | 1.04%   |
| IMC Networks 802.11ac WLAN Adapter                  | 123       | 1%      |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 115       | 0.93%   |
| Apple Bluetooth USB Host Controller                 | 113       | 0.91%   |
| MediaTek Wireless_Device                            | 111       | 0.9%    |
| IMC Networks Bluetooth Radio                        | 109       | 0.88%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 104       | 0.84%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 98        | 0.79%   |
| IMC Networks Bluetooth Device                       | 97        | 0.78%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 88        | 0.71%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 84        | 0.68%   |
| Dell DW375 Bluetooth Module                         | 84        | 0.68%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 83        | 0.67%   |
| Lite-On Atheros AR3012 Bluetooth                    | 78        | 0.63%   |
| Realtek Bluetooth Radio                             | 71        | 0.57%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 71        | 0.57%   |
| IMC Networks Wireless_Device                        | 68        | 0.55%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 67        | 0.54%   |
| HP Broadcom 2070 Bluetooth Combo                    | 66        | 0.53%   |
| Foxconn / Hon Hai BCM20702A0                        | 56        | 0.45%   |
| Broadcom BCM2045 Bluetooth                          | 53        | 0.43%   |
| Realtek RTL8723B Bluetooth                          | 52        | 0.42%   |
| Dell BCM20702A0 Bluetooth Module                    | 51        | 0.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 14396     | 48.12%  |
| AMD                              | 6995      | 23.38%  |
| Nvidia                           | 4897      | 16.37%  |
| C-Media Electronics              | 576       | 1.93%   |
| Logitech                         | 254       | 0.85%   |
| Creative Labs                    | 241       | 0.81%   |
| GN Netcom                        | 195       | 0.65%   |
| Lenovo                           | 164       | 0.55%   |
| Texas Instruments                | 143       | 0.48%   |
| Realtek Semiconductor            | 122       | 0.41%   |
| JMTek                            | 96        | 0.32%   |
| Focusrite-Novation               | 95        | 0.32%   |
| Plantronics                      | 92        | 0.31%   |
| Kingston Technology              | 89        | 0.3%    |
| Creative Technology              | 85        | 0.28%   |
| VIA Technologies                 | 75        | 0.25%   |
| Razer USA                        | 72        | 0.24%   |
| ASUSTek Computer                 | 71        | 0.24%   |
| Generalplus Technology           | 64        | 0.21%   |
| DSEA A/S                         | 64        | 0.21%   |
| SteelSeries ApS                  | 53        | 0.18%   |
| Hewlett-Packard                  | 47        | 0.16%   |
| Yamaha                           | 42        | 0.14%   |
| Corsair                          | 41        | 0.14%   |
| RODE Microphones                 | 40        | 0.13%   |
| Micro Star International         | 35        | 0.12%   |
| Silicon Integrated Systems [SiS] | 34        | 0.11%   |
| BEHRINGER International          | 33        | 0.11%   |
| Dell                             | 29        | 0.1%    |
| TerraTec Electronic              | 28        | 0.09%   |
| Samson Technologies              | 27        | 0.09%   |
| Sennheiser Communications        | 21        | 0.07%   |
| ROCCAT                           | 21        | 0.07%   |
| Native Instruments               | 21        | 0.07%   |
| M-Audio                          | 21        | 0.07%   |
| Blue Microphones                 | 21        | 0.07%   |
| Apple                            | 19        | 0.06%   |
| GYROCOM C&C                      | 18        | 0.06%   |
| Conexant Systems                 | 17        | 0.06%   |
| Sony                             | 16        | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 2020      | 5.63%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1518      | 4.23%   |
| Intel Sunrise Point-LP HD Audio                                            | 1508      | 4.2%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1329      | 3.7%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 1101      | 3.07%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1084      | 3.02%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1017      | 2.83%   |
| AMD Starship/Matisse HD Audio Controller                                   | 896       | 2.5%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 799       | 2.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 751       | 2.09%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 737       | 2.05%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 653       | 1.82%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 616       | 1.72%   |
| AMD FCH Azalia Controller                                                  | 610       | 1.7%    |
| Intel Cannon Lake PCH cAVS                                                 | 601       | 1.67%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 596       | 1.66%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 514       | 1.43%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 497       | 1.39%   |
| Intel Haswell-ULT HD Audio Controller                                      | 470       | 1.31%   |
| Intel 8 Series HD Audio Controller                                         | 468       | 1.3%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 420       | 1.17%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 405       | 1.13%   |
| Nvidia GP107GL High Definition Audio Controller                            | 385       | 1.07%   |
| Intel Broadwell-U Audio Controller                                         | 381       | 1.06%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 372       | 1.04%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 363       | 1.01%   |
| Intel 200 Series PCH HD Audio                                              | 344       | 0.96%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 327       | 0.91%   |
| Nvidia GF108 High Definition Audio Controller                              | 326       | 0.91%   |
| Intel Comet Lake PCH-LP cAVS                                               | 320       | 0.89%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 311       | 0.87%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 292       | 0.81%   |
| AMD Kabini HDMI/DP Audio                                                   | 269       | 0.75%   |
| Nvidia GP106 High Definition Audio Controller                              | 254       | 0.71%   |
| Nvidia GP104 High Definition Audio Controller                              | 250       | 0.7%    |
| Nvidia High Definition Audio Controller                                    | 249       | 0.69%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 248       | 0.69%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 246       | 0.69%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 237       | 0.66%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 229       | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 2996      | 23.78%  |
| SK hynix            | 2121      | 16.84%  |
| Unknown             | 1240      | 9.84%   |
| Micron Technology   | 1180      | 9.37%   |
| Kingston            | 1169      | 9.28%   |
| Crucial             | 939       | 7.45%   |
| G.Skill             | 767       | 6.09%   |
| Corsair             | 675       | 5.36%   |
| Ramaxel Technology  | 233       | 1.85%   |
| Elpida              | 178       | 1.41%   |
| A-DATA Technology   | 177       | 1.41%   |
| Nanya Technology    | 165       | 1.31%   |
| Unknown (ABCD)      | 161       | 1.28%   |
| Unknown             | 82        | 0.65%   |
| Team                | 65        | 0.52%   |
| Transcend           | 49        | 0.39%   |
| Patriot             | 35        | 0.28%   |
| GOODRAM             | 25        | 0.2%    |
| Avant               | 22        | 0.17%   |
| ASint Technology    | 21        | 0.17%   |
| Toshiba             | 17        | 0.13%   |
| GeIL                | 16        | 0.13%   |
| 48spaces            | 15        | 0.12%   |
| CSX                 | 12        | 0.1%    |
| Unifosa             | 11        | 0.09%   |
| Lexar               | 11        | 0.09%   |
| Hewlett-Packard     | 10        | 0.08%   |
| Qimonda             | 9         | 0.07%   |
| SHARETRONIC         | 8         | 0.06%   |
| PNY                 | 8         | 0.06%   |
| Apacer              | 8         | 0.06%   |
| Timetec             | 7         | 0.06%   |
| Mushkin             | 6         | 0.05%   |
| Neo Forza           | 5         | 0.04%   |
| Goldkey             | 5         | 0.04%   |
| Aeneon              | 5         | 0.04%   |
| Unknown (AB)        | 4         | 0.03%   |
| Patriot Memory      | 4         | 0.03%   |
| INNOVATION PC       | 4         | 0.03%   |
| Unknown (0x0E9D)    | 3         | 0.02%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 116       | 0.86%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 109       | 0.81%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 106       | 0.78%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 99        | 0.73%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 93        | 0.69%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 89        | 0.66%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s           | 89        | 0.66%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 86        | 0.64%   |
| Unknown                                                          | 82        | 0.61%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 81        | 0.6%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 80        | 0.59%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 74        | 0.55%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 68        | 0.5%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 68        | 0.5%    |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 65        | 0.48%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 65        | 0.48%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 63        | 0.47%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 62        | 0.46%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s              | 59        | 0.44%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 58        | 0.43%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 58        | 0.43%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 57        | 0.42%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 56        | 0.41%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 56        | 0.41%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s               | 56        | 0.41%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 54        | 0.4%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 53        | 0.39%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 52        | 0.38%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 51        | 0.38%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 49        | 0.36%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 49        | 0.36%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 48        | 0.35%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 47        | 0.35%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 46        | 0.34%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 45        | 0.33%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 45        | 0.33%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 45        | 0.33%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s             | 44        | 0.33%   |
| G.Skill RAM F4-3200C16-16GIS 16GB DIMM DDR4 3600MT/s             | 43        | 0.32%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 41        | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind            | Computers | Percent |
|-----------------|-----------|---------|
| DDR4            | 5264      | 47.35%  |
| DDR3            | 3627      | 32.62%  |
| DDR2            | 493       | 4.43%   |
| LPDDR4          | 460       | 4.14%   |
| Unknown         | 349       | 3.14%   |
| SDRAM           | 292       | 2.63%   |
| LPDDR3          | 254       | 2.28%   |
| DDR5            | 164       | 1.48%   |
| LPDDR5          | 104       | 0.94%   |
| DDR             | 73        | 0.66%   |
| DRAM            | 36        | 0.32%   |
| Logical non-vol | 1         | 0.01%   |
| EEPROM          | 1         | 0.01%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| SODIMM          | 6208      | 55.97%  |
| DIMM            | 4007      | 36.13%  |
| Row Of Chips    | 747       | 6.74%   |
| Chip            | 91        | 0.82%   |
| Unknown         | 16        | 0.14%   |
| RIMM            | 10        | 0.09%   |
| FB-DIMM         | 10        | 0.09%   |
| Proprietary Car | 2         | 0.02%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size   | Computers | Percent |
|--------|-----------|---------|
| 8192   | 4716      | 39.38%  |
| 4096   | 3053      | 25.49%  |
| 16384  | 1915      | 15.99%  |
| 2048   | 1405      | 11.73%  |
| 32768  | 464       | 3.87%   |
| 1024   | 357       | 2.98%   |
| 512    | 47        | 0.39%   |
| 65536  | 5         | 0.04%   |
| 256    | 5         | 0.04%   |
| 128    | 4         | 0.03%   |
| 129408 | 1         | 0.01%   |
| 49152  | 1         | 0.01%   |
| 3072   | 1         | 0.01%   |
| 384    | 1         | 0.01%   |
| 16     | 1         | 0.01%   |
| 1      | 1         | 0.01%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 2280      | 19.01%  |
| 3200    | 1882      | 15.69%  |
| 2667    | 1619      | 13.5%   |
| 1333    | 856       | 7.14%   |
| 2400    | 851       | 7.1%    |
| 2133    | 581       | 4.84%   |
| 1334    | 381       | 3.18%   |
| 3600    | 308       | 2.57%   |
| 667     | 268       | 2.23%   |
| 800     | 261       | 2.18%   |
| Unknown | 241       | 2.01%   |
| 1867    | 222       | 1.85%   |
| 4267    | 175       | 1.46%   |
| 1067    | 167       | 1.39%   |
| 3266    | 111       | 0.93%   |
| 1866    | 111       | 0.93%   |
| 1066    | 109       | 0.91%   |
| 3733    | 102       | 0.85%   |
| 6400    | 97        | 0.81%   |
| 4800    | 97        | 0.81%   |
| 1800    | 89        | 0.74%   |
| 3000    | 84        | 0.7%    |
| 2933    | 84        | 0.7%    |
| 2666    | 81        | 0.68%   |
| 3400    | 69        | 0.58%   |
| 4199    | 67        | 0.56%   |
| 3866    | 64        | 0.53%   |
| 3800    | 51        | 0.43%   |
| 4266    | 45        | 0.38%   |
| 2048    | 45        | 0.38%   |
| 533     | 42        | 0.35%   |
| 8400    | 40        | 0.33%   |
| 400     | 39        | 0.33%   |
| 5600    | 36        | 0.3%    |
| 975     | 31        | 0.26%   |
| 3533    | 29        | 0.24%   |
| 3666    | 28        | 0.23%   |
| 2800    | 23        | 0.19%   |
| 333     | 23        | 0.19%   |
| 6000    | 20        | 0.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Hewlett-Packard          | 236       | 28.71%  |
| Brother Industries       | 160       | 19.46%  |
| Canon                    | 150       | 18.25%  |
| Samsung Electronics      | 101       | 12.29%  |
| Seiko Epson              | 63        | 7.66%   |
| Kyocera                  | 23        | 2.8%    |
| Dymo-CoStar              | 19        | 2.31%   |
| Prolific Technology      | 18        | 2.19%   |
| QinHeng Electronics      | 13        | 1.58%   |
| Lexmark International    | 13        | 1.58%   |
| Dell                     | 4         | 0.49%   |
| Xerox                    | 3         | 0.36%   |
| Ricoh                    | 3         | 0.36%   |
| Oki Data                 | 3         | 0.36%   |
| STMicroelectronics       | 2         | 0.24%   |
| Magic Control Technology | 2         | 0.24%   |
| Seiko Instruments        | 1         | 0.12%   |
| Pantum                   | 1         | 0.12%   |
| Panasonic (Matsushita)   | 1         | 0.12%   |
| Minolta                  | 1         | 0.12%   |
| MIIIW                    | 1         | 0.12%   |
| GG IMAGE                 | 1         | 0.12%   |
| ATEN International       | 1         | 0.12%   |
| Agere Systems (Lucent)   | 1         | 0.12%   |
| Unknown                  | 1         | 0.12%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung M2020 Series                 | 18        | 2.17%   |
| Prolific PL2305 Parallel Port        | 18        | 2.17%   |
| Brother HL-2030 Laser Printer        | 14        | 1.69%   |
| QinHeng CH340S                       | 13        | 1.57%   |
| Canon PIXMA MX920 Series             | 12        | 1.45%   |
| Canon LiDE 400                       | 12        | 1.45%   |
| Canon CanoScan LiDE 300              | 12        | 1.45%   |
| Samsung C48x Series                  | 10        | 1.21%   |
| HP ENVY 4520 series                  | 10        | 1.21%   |
| Canon iP7200 series                  | 9         | 1.09%   |
| Canon PIXMA MG3600 Series            | 8         | 0.97%   |
| Seiko Epson L3150 Series             | 7         | 0.85%   |
| HP DeskJet 2700 series               | 7         | 0.85%   |
| HP Deskjet 2540 series               | 7         | 0.85%   |
| Canon TR8500 series                  | 7         | 0.85%   |
| Brother MFC-L2710DW series           | 7         | 0.85%   |
| Seiko Epson XP-2100 Series           | 6         | 0.72%   |
| Samsung SCX-472x Series              | 6         | 0.72%   |
| Samsung M2070 Series                 | 6         | 0.72%   |
| HP OfficeJet 3830 series             | 6         | 0.72%   |
| HP ENVY 4500 series                  | 6         | 0.72%   |
| Dymo-CoStar LabelWriter 450          | 6         | 0.72%   |
| Dymo-CoStar LabelWriter 400          | 6         | 0.72%   |
| Brother HL-3142CW series             | 6         | 0.72%   |
| Samsung ML-1640 Series Laser Printer | 5         | 0.6%    |
| HP OfficeJet 5200 series             | 5         | 0.6%    |
| HP Officejet 4620 series             | 5         | 0.6%    |
| HP DeskJet F4200 series              | 5         | 0.6%    |
| HP DeskJet 4100 series               | 5         | 0.6%    |
| HP DeskJet 3700 series               | 5         | 0.6%    |
| HP Deskjet 3520 series               | 5         | 0.6%    |
| HP DeskJet 2600 series               | 5         | 0.6%    |
| HP Deskjet 2050 J510                 | 5         | 0.6%    |
| HP DeskJet 1110 series               | 5         | 0.6%    |
| Canon TS700 series                   | 5         | 0.6%    |
| Canon TR4500 series                  | 5         | 0.6%    |
| Canon PIXMA MX490 Series             | 5         | 0.6%    |
| Canon Pixma iP4500 Printer           | 5         | 0.6%    |
| Brother MFC-L3750CDW                 | 5         | 0.6%    |
| Brother MFC-L2710DN series           | 5         | 0.6%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor                                         | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Canon                                          | 205       | 72.95%  |
| Seiko Epson                                    | 42        | 14.95%  |
| Hewlett-Packard                                | 14        | 4.98%   |
| AGFA-Gevaert NV                                | 8         | 2.85%   |
| Mustek Systems                                 | 6         | 2.14%   |
| Plustek                                        | 2         | 0.71%   |
| Ultima Electronics                             | 1         | 0.36%   |
| Siemens Information and Communication Products | 1         | 0.36%   |
| Nikon                                          | 1         | 0.36%   |
| Microtek International                         | 1         | 0.36%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 220                                                               | 33        | 11.7%   |
| Canon CanoScan LiDE 210                                                               | 28        | 9.93%   |
| Canon CanoScan LiDE 110                                                               | 24        | 8.51%   |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 19        | 6.74%   |
| Canon CanoScan LIDE 25                                                                | 18        | 6.38%   |
| Canon CanoScan LiDE 100                                                               | 14        | 4.96%   |
| Canon CanoScan LiDE 120                                                               | 13        | 4.61%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                                                | 9         | 3.19%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                   | 8         | 2.84%   |
| Canon CanoScan LiDE 90                                                                | 8         | 2.84%   |
| Canon CanoScan LiDE 200                                                               | 6         | 2.13%   |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 5         | 1.77%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 5         | 1.77%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                                         | 5         | 1.77%   |
| Canon CanoScan LiDE 60                                                                | 5         | 1.77%   |
| Canon CanoScan 9000F Mark II                                                          | 4         | 1.42%   |
| Canon CanoScan 8800F                                                                  | 4         | 1.42%   |
| AGFA-Gevaert NV SnapScan 1212U (?)                                                    | 4         | 1.42%   |
| HP ScanJet 3970c                                                                      | 3         | 1.06%   |
| Canon CanoScan N1240U/LiDE 30                                                         | 3         | 1.06%   |
| Canon CanoScan LiDE 600F                                                              | 3         | 1.06%   |
| Canon CanoScan LiDE 500F                                                              | 3         | 1.06%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 2         | 0.71%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                                    | 2         | 0.71%   |
| Seiko Epson GT-8200U/GT-8200UF [Perfection 1650/1650 PHOTO]                           | 2         | 0.71%   |
| Seiko Epson GT-6600U [Perfection 610]                                                 | 2         | 0.71%   |
| Mustek Systems ScanExpress 1200 CU                                                    | 2         | 0.71%   |
| HP HP4470C                                                                            | 2         | 0.71%   |
| Canon CanoScan LiDE 700F                                                              | 2         | 0.71%   |
| Canon CanoScan 4400F                                                                  | 2         | 0.71%   |
| Canon CanoScan 3200F                                                                  | 2         | 0.71%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1         | 0.35%   |
| Siemens Information and Communication Products ID-Mouse with Fingerprint Reader       | 1         | 0.35%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                                           | 1         | 0.35%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo]                               | 1         | 0.35%   |
| Seiko Epson GT-F700 [Perfection V350]                                                 | 1         | 0.35%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 1         | 0.35%   |
| Seiko Epson GT-9700F [Perfection 2450 PHOTO]                                          | 1         | 0.35%   |
| Seiko Epson GT-9400UF [Perfection 3170]                                               | 1         | 0.35%   |
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO]                         | 1         | 0.35%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 3084      | 25.47%  |
| IMC Networks                           | 975       | 8.05%   |
| Logitech                               | 833       | 6.88%   |
| Microdia                               | 827       | 6.83%   |
| Realtek Semiconductor                  | 741       | 6.12%   |
| Bison Electronics                      | 727       | 6%      |
| Quanta                                 | 529       | 4.37%   |
| Sunplus Innovation Technology          | 520       | 4.29%   |
| Cheng Uei Precision Industry (Foxlink) | 405       | 3.34%   |
| Suyin                                  | 376       | 3.11%   |
| Apple                                  | 322       | 2.66%   |
| Syntek                                 | 278       | 2.3%    |
| Lite-On Technology                     | 274       | 2.26%   |
| Acer                                   | 231       | 1.91%   |
| Microsoft                              | 176       | 1.45%   |
| Alcor Micro                            | 173       | 1.43%   |
| Luxvisions Innotech Limited            | 141       | 1.16%   |
| Silicon Motion                         | 131       | 1.08%   |
| Ricoh                                  | 120       | 0.99%   |
| Lenovo                                 | 106       | 0.88%   |
| Samsung Electronics                    | 96        | 0.79%   |
| Z-Star Microelectronics                | 83        | 0.69%   |
| ALi                                    | 61        | 0.5%    |
| Generalplus Technology                 | 57        | 0.47%   |
| Creative Technology                    | 48        | 0.4%    |
| ARC International                      | 46        | 0.38%   |
| Sonix Technology                       | 44        | 0.36%   |
| Primax Electronics                     | 38        | 0.31%   |
| SunplusIT                              | 34        | 0.28%   |
| DigiTech                               | 33        | 0.27%   |
| Importek                               | 31        | 0.26%   |
| Sunplus Technology                     | 28        | 0.23%   |
| Cubeternet                             | 26        | 0.21%   |
| Trust                                  | 24        | 0.2%    |
| Jieli Technology                       | 23        | 0.19%   |
| MacroSilicon                           | 21        | 0.17%   |
| Genesys Logic                          | 19        | 0.16%   |
| GEMBIRD                                | 19        | 0.16%   |
| KYE Systems (Mouse Systems)            | 16        | 0.13%   |
| Creality 3D Technology                 | 16        | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 676       | 5.53%   |
| IMC Networks Integrated Camera                   | 364       | 2.98%   |
| Chicony HD WebCam                                | 311       | 2.54%   |
| Microdia Integrated_Webcam_HD                    | 238       | 1.95%   |
| Bison Integrated Camera                          | 220       | 1.8%    |
| IMC Networks USB2.0 HD UVC WebCam                | 192       | 1.57%   |
| Realtek Integrated_Webcam_HD                     | 188       | 1.54%   |
| Logitech Webcam C270                             | 173       | 1.42%   |
| Syntek Integrated Camera                         | 170       | 1.39%   |
| Chicony FJ Camera                                | 160       | 1.31%   |
| Chicony USB2.0 Camera                            | 139       | 1.14%   |
| Sunplus Integrated_Webcam_HD                     | 136       | 1.11%   |
| Logitech HD Pro Webcam C920                      | 122       | 1%      |
| Lite-On Integrated Camera                        | 120       | 0.98%   |
| Apple Built-in iSight                            | 107       | 0.88%   |
| Chicony HP HD Camera                             | 105       | 0.86%   |
| Microdia Integrated Webcam                       | 98        | 0.8%    |
| Chicony USB 2.0 Camera                           | 97        | 0.79%   |
| Sunplus HD WebCam                                | 95        | 0.78%   |
| Samsung Galaxy series, misc. (MTP mode)          | 93        | 0.76%   |
| Quanta HD User Facing                            | 90        | 0.74%   |
| Bison SunplusIT Integrated Camera                | 86        | 0.7%    |
| Realtek USB Camera                               | 85        | 0.7%    |
| Chicony USB2.0 HD UVC WebCam                     | 85        | 0.7%    |
| Chicony HD User Facing                           | 82        | 0.67%   |
| Chicony Integrated Camera (1280x720@30)          | 81        | 0.66%   |
| Alcor Micro USB 2.0 Camera                       | 74        | 0.61%   |
| Microsoft LifeCam HD-3000                        | 73        | 0.6%    |
| Chicony Integrated IR Camera                     | 73        | 0.6%    |
| Apple FaceTime HD Camera (Built-in)              | 73        | 0.6%    |
| Microdia USB 2.0 Camera                          | 72        | 0.59%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 71        | 0.58%   |
| Quanta HP Webcam                                 | 69        | 0.56%   |
| Quanta HP HD Camera                              | 69        | 0.56%   |
| Chicony TOSHIBA Web Camera - HD                  | 68        | 0.56%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 68        | 0.56%   |
| Chicony HP Webcam                                | 65        | 0.53%   |
| Bison Lenovo EasyCamera                          | 65        | 0.53%   |
| Apple iPhone 5/5C/5S/6/SE                        | 63        | 0.52%   |
| Suyin Acer/HP Integrated Webcam [CN0314]         | 61        | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 813       | 30.67%  |
| Synaptics                          | 781       | 29.46%  |
| Shenzhen Goodix Technology         | 341       | 12.86%  |
| AuthenTec                          | 215       | 8.11%   |
| Upek                               | 172       | 6.49%   |
| LighTuning Technology              | 146       | 5.51%   |
| Elan Microelectronics              | 109       | 4.11%   |
| STMicroelectronics                 | 41        | 1.55%   |
| HOLTEK                             | 11        | 0.41%   |
| Realtek USB2.0 Finger Print Bridge | 8         | 0.3%    |
| Samsung Electronics                | 7         | 0.26%   |
| Focal-systems.Corp                 | 2         | 0.08%   |
| DigitalPersona                     | 2         | 0.08%   |
| Dell                               | 2         | 0.08%   |
| Next Biometrics                    | 1         | 0.04%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 273       | 10.29%  |
| Shenzhen Goodix  FingerPrint Device                                        | 194       | 7.32%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 161       | 6.07%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 150       | 5.66%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 126       | 4.75%   |
| Validity Sensors Synaptics WBDI                                            | 115       | 4.34%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 102       | 3.85%   |
| Shenzhen Goodix Fingerprint Reader                                         | 102       | 3.85%   |
| AuthenTec AES2810                                                          | 74        | 2.79%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 72        | 2.71%   |
| Elan ELAN:Fingerprint                                                      | 63        | 2.38%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 60        | 2.26%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 60        | 2.26%   |
| Synaptics WBDI                                                             | 59        | 2.22%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 52        | 1.96%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 50        | 1.89%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 48        | 1.81%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 48        | 1.81%   |
| Synaptics UWP WBDI                                                         | 46        | 1.73%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 46        | 1.73%   |
| Shenzhen Goodix FingerPrint                                                | 45        | 1.7%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 44        | 1.66%   |
| STMicroelectronics Fingerprint Reader                                      | 41        | 1.55%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 40        | 1.51%   |
| Synaptics Fingerprint reader [HP G6]                                       | 39        | 1.47%   |
| Validity Sensors VFS491                                                    | 37        | 1.4%    |
| Elan ELAN:ARM-M4                                                           | 36        | 1.36%   |
| Synaptics  WBDI                                                            | 35        | 1.32%   |
| AuthenTec Fingerprint Sensor                                               | 34        | 1.28%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 33        | 1.24%   |
| AuthenTec AES1600                                                          | 33        | 1.24%   |
| LighTuning Fingerprint Reader                                              | 30        | 1.13%   |
| Synaptics UWP WBDI Device                                                  | 29        | 1.09%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 27        | 1.02%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 24        | 0.9%    |
| Unknown                                                                    | 22        | 0.83%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 21        | 0.79%   |
| Validity Sensors Fingerprint scanner                                       | 20        | 0.75%   |
| Synaptics TouchPad                                                         | 20        | 0.75%   |
| Synaptics WBDI Device                                                      | 15        | 0.57%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 614       | 39.97%  |
| Broadcom                  | 452       | 29.43%  |
| O2 Micro                  | 129       | 8.4%    |
| Lenovo                    | 123       | 8.01%   |
| Upek                      | 80        | 5.21%   |
| Reiner SCT Kartensysteme  | 29        | 1.89%   |
| Gemalto (was Gemplus)     | 19        | 1.24%   |
| Yubico.com                | 17        | 1.11%   |
| OmniKey                   | 14        | 0.91%   |
| Clay Logic                | 12        | 0.78%   |
| Cherry                    | 11        | 0.72%   |
| SCM Microsystems          | 9         | 0.59%   |
| Fujitsu Siemens Computers | 5         | 0.33%   |
| Advanced Card Systems     | 5         | 0.33%   |
| Realtek Semiconductor     | 4         | 0.26%   |
| Kobil Systems             | 4         | 0.26%   |
| NXP Semiconductors        | 2         | 0.13%   |
| In Focus Systems          | 2         | 0.13%   |
| Chicony Electronics       | 2         | 0.13%   |
| Purism, SPC               | 1         | 0.07%   |
| Microchip Technology      | 1         | 0.07%   |
| Aladdin Knowledge Systems | 1         | 0.07%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 612       | 39.84%  |
| Broadcom BCM5880 Secure Applications Processor                               | 171       | 11.13%  |
| Lenovo Integrated Smart Card Reader                                          | 122       | 7.94%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 116       | 7.55%   |
| Broadcom 5880                                                                | 99        | 6.45%   |
| Broadcom 58200                                                               | 87        | 5.66%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 85        | 5.53%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 80        | 5.21%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 16        | 1.04%   |
| O2 Micro Oz776 SmartCard Reader                                              | 13        | 0.85%   |
| Clay Logic Nitrokey Pro                                                      | 12        | 0.78%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 10        | 0.65%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 10        | 0.65%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                          | 9         | 0.59%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 9         | 0.59%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 9         | 0.59%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 8         | 0.52%   |
| Reiner SCT Kartensysteme cyberJack one                                       | 7         | 0.46%   |
| OmniKey CardMan 3021 / 3121                                                  | 6         | 0.39%   |
| Reiner SCT Kartensysteme tanJack USB                                         | 4         | 0.26%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 4         | 0.26%   |
| SCM Microsystems SCR335 SmartCard Reader                                     | 3         | 0.2%    |
| OmniKey CardMan 4321                                                         | 3         | 0.2%    |
| OmniKey CardMan 3121 (HID Technologies)                                      | 3         | 0.2%    |
| Advanced Card Systems ACR122U                                                | 3         | 0.2%    |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 0.13%   |
| Reiner SCT Kartensysteme cyberJack e-com/pinpad                              | 2         | 0.13%   |
| NXP Semiconductors PR533                                                     | 2         | 0.13%   |
| Kobil Systems Smart Token                                                    | 2         | 0.13%   |
| Kobil Systems KOBIL Class 3 Reader                                           | 2         | 0.13%   |
| In Focus Systems EMV Smartcard Reader                                        | 2         | 0.13%   |
| Fujitsu Siemens Computers Keyboard KB SCR                                    | 2         | 0.13%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 2         | 0.13%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 0.13%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 2         | 0.13%   |
| SCM Microsystems uTrust 3700 F CL Reader                                     | 1         | 0.07%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 0.07%   |
| SCM Microsystems SCR3500 A Contact Reader                                    | 1         | 0.07%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 0.07%   |
| Purism, SPC Librem Key                                                       | 1         | 0.07%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 15122     | 68.1%   |
| 1     | 5333      | 24.02%  |
| 2     | 1364      | 6.14%   |
| 3     | 264       | 1.19%   |
| 4     | 74        | 0.33%   |
| 5     | 32        | 0.14%   |
| 6     | 7         | 0.03%   |
| 7     | 5         | 0.02%   |
| 8     | 2         | 0.01%   |
| 9     | 1         | 0.005%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 2615      | 29.23%  |
| Graphics card            | 1824      | 20.39%  |
| Chipcard                 | 1335      | 14.92%  |
| Net/wireless             | 994       | 11.11%  |
| Multimedia controller    | 534       | 5.97%   |
| Communication controller | 378       | 4.23%   |
| Camera                   | 215       | 2.4%    |
| Card reader              | 170       | 1.9%    |
| Storage                  | 166       | 1.86%   |
| Unassigned class         | 157       | 1.75%   |
| Bluetooth                | 146       | 1.63%   |
| Sound                    | 144       | 1.61%   |
| Net/ethernet             | 62        | 0.69%   |
| Modem                    | 53        | 0.59%   |
| Network                  | 45        | 0.5%    |
| Storage/raid             | 25        | 0.28%   |
| Storage/ide              | 20        | 0.22%   |
| Dvb card                 | 20        | 0.22%   |
| Flash memory             | 11        | 0.12%   |
| Firewire controller      | 11        | 0.12%   |
| Tv card                  | 6         | 0.07%   |
| Storage/nvme             | 5         | 0.06%   |
| Unclassified device      | 4         | 0.04%   |
| Storage/ata              | 4         | 0.04%   |
| Video                    | 2         | 0.02%   |

