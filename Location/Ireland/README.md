Linux in Ireland - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Ireland.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Ireland/Desktop/README.md) and [notebooks](/Location/Ireland/Notebook/README.md).

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

Total: 691

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Apple         | Mac-F226BEC8 PVT            | All in one  | [a4354f496c](https://linux-hardware.org/?probe=a4354f496c) | Nov 02, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [5cf615d5b2](https://linux-hardware.org/?probe=5cf615d5b2) | Nov 02, 2022 |
| MSI           | Z170M MORTAR                | Desktop     | [041dbc2c18](https://linux-hardware.org/?probe=041dbc2c18) | Oct 31, 2022 |
| ASUSTek       | Zephyrus S GX502GW_GX502... | Notebook    | [c3f344809a](https://linux-hardware.org/?probe=c3f344809a) | Oct 30, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [1d4a6dc6dc](https://linux-hardware.org/?probe=1d4a6dc6dc) | Oct 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [a1694d3adc](https://linux-hardware.org/?probe=a1694d3adc) | Oct 29, 2022 |
| Dell          | Inspiron 15-7568            | Notebook    | [ae536fa220](https://linux-hardware.org/?probe=ae536fa220) | Oct 27, 2022 |
| Fujitsu Si... | AMILO Li 2727               | Notebook    | [084149046b](https://linux-hardware.org/?probe=084149046b) | Oct 25, 2022 |
| Fujitsu Si... | AMILO Li 2727               | Notebook    | [c9811709ec](https://linux-hardware.org/?probe=c9811709ec) | Oct 25, 2022 |
| Dell          | 0JP3NX A00                  | Desktop     | [8b457c11e8](https://linux-hardware.org/?probe=8b457c11e8) | Oct 23, 2022 |
| Dell          | Latitude E6440              | Notebook    | [692b716621](https://linux-hardware.org/?probe=692b716621) | Oct 23, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | Notebook    | [e03569f758](https://linux-hardware.org/?probe=e03569f758) | Oct 20, 2022 |
| Lenovo        | ThinkPad P52 20MAS17205     | Notebook    | [be48cfe3be](https://linux-hardware.org/?probe=be48cfe3be) | Oct 20, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [ac2c9383c0](https://linux-hardware.org/?probe=ac2c9383c0) | Oct 18, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [2e1434c4ff](https://linux-hardware.org/?probe=2e1434c4ff) | Oct 14, 2022 |
| Dell          | Latitude 7400               | Notebook    | [3b340aa7d4](https://linux-hardware.org/?probe=3b340aa7d4) | Oct 12, 2022 |
| Dell          | Latitude 7400               | Notebook    | [159021ed29](https://linux-hardware.org/?probe=159021ed29) | Oct 12, 2022 |
| Dell          | 0WR7PY A02                  | Desktop     | [e464adc2d9](https://linux-hardware.org/?probe=e464adc2d9) | Oct 11, 2022 |
| Toshiba       | PORTEGE R830                | Notebook    | [ffda659565](https://linux-hardware.org/?probe=ffda659565) | Oct 11, 2022 |
| MSI           | MS-7A34                     | Notebook    | [9850074c97](https://linux-hardware.org/?probe=9850074c97) | Oct 10, 2022 |
| Lenovo        | ThinkPad T440 20B7A0S200    | Notebook    | [1be1f8f36e](https://linux-hardware.org/?probe=1be1f8f36e) | Oct 09, 2022 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [fee12e32e5](https://linux-hardware.org/?probe=fee12e32e5) | Oct 07, 2022 |
| HP            | 21D0                        | Desktop     | [6815e2bba2](https://linux-hardware.org/?probe=6815e2bba2) | Oct 04, 2022 |
| HP            | ProBook 455 G6              | Notebook    | [acae78b85a](https://linux-hardware.org/?probe=acae78b85a) | Oct 03, 2022 |
| HP            | ProBook 455 G6              | Notebook    | [3697a412bd](https://linux-hardware.org/?probe=3697a412bd) | Oct 03, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [26df10ca7d](https://linux-hardware.org/?probe=26df10ca7d) | Oct 02, 2022 |
| Timi          | TM1709                      | Notebook    | [33022811a8](https://linux-hardware.org/?probe=33022811a8) | Oct 01, 2022 |
| Dell          | Latitude 7420               | Notebook    | [0834411088](https://linux-hardware.org/?probe=0834411088) | Sep 26, 2022 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [59d0400171](https://linux-hardware.org/?probe=59d0400171) | Sep 24, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [172fd1874d](https://linux-hardware.org/?probe=172fd1874d) | Sep 20, 2022 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [da0b586e04](https://linux-hardware.org/?probe=da0b586e04) | Sep 20, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [b404f51fbe](https://linux-hardware.org/?probe=b404f51fbe) | Sep 12, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [b389a760a8](https://linux-hardware.org/?probe=b389a760a8) | Sep 12, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [099ffbf0bc](https://linux-hardware.org/?probe=099ffbf0bc) | Sep 10, 2022 |
| Lenovo        | SDK0J40705 WIN 342504154... | Desktop     | [4feb69184d](https://linux-hardware.org/?probe=4feb69184d) | Sep 02, 2022 |
| Lenovo        | SDK0J40705 WIN 342504154... | Desktop     | [bfee1a862f](https://linux-hardware.org/?probe=bfee1a862f) | Sep 02, 2022 |
| Dell          | 0TP412                      | Desktop     | [73ec9dcd98](https://linux-hardware.org/?probe=73ec9dcd98) | Sep 02, 2022 |
| HP            | Pavilion m6                 | Notebook    | [83b6eb0119](https://linux-hardware.org/?probe=83b6eb0119) | Sep 01, 2022 |
| Medion        | E6227                       | Notebook    | [e6ca2257e7](https://linux-hardware.org/?probe=e6ca2257e7) | Sep 01, 2022 |
| Dell          | XPS 9320                    | Notebook    | [7fe70d3907](https://linux-hardware.org/?probe=7fe70d3907) | Aug 30, 2022 |
| Apple         | Mac-F2218FA9                | All in one  | [296fc14c83](https://linux-hardware.org/?probe=296fc14c83) | Aug 26, 2022 |
| Framework     | Laptop                      | Notebook    | [87e09551b3](https://linux-hardware.org/?probe=87e09551b3) | Aug 25, 2022 |
| Framework     | Laptop                      | Notebook    | [3c4bab3769](https://linux-hardware.org/?probe=3c4bab3769) | Aug 24, 2022 |
| MSI           | MEG Z490I UNIFY             | Desktop     | [34d2d4f66e](https://linux-hardware.org/?probe=34d2d4f66e) | Aug 24, 2022 |
| HP            | Pavilion g6                 | Notebook    | [ae65121050](https://linux-hardware.org/?probe=ae65121050) | Aug 23, 2022 |
| Apple         | MacBook6,1                  | Notebook    | [f7703b1b38](https://linux-hardware.org/?probe=f7703b1b38) | Aug 19, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U2S... | Notebook    | [ff64bb7593](https://linux-hardware.org/?probe=ff64bb7593) | Aug 17, 2022 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [caf9167ca7](https://linux-hardware.org/?probe=caf9167ca7) | Aug 16, 2022 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [6d1b561c11](https://linux-hardware.org/?probe=6d1b561c11) | Aug 16, 2022 |
| HP            | EliteBook 755 G5            | Notebook    | [795c2046ba](https://linux-hardware.org/?probe=795c2046ba) | Aug 16, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [d333f2698e](https://linux-hardware.org/?probe=d333f2698e) | Aug 15, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [7af785fc65](https://linux-hardware.org/?probe=7af785fc65) | Aug 13, 2022 |
| Dell          | XPS 9320                    | Notebook    | [bdb29b0481](https://linux-hardware.org/?probe=bdb29b0481) | Aug 11, 2022 |
| Dell          | XPS 9320                    | Notebook    | [1d0ef5711d](https://linux-hardware.org/?probe=1d0ef5711d) | Aug 11, 2022 |
| HP            | Pavilion g6                 | Notebook    | [3f462439ed](https://linux-hardware.org/?probe=3f462439ed) | Aug 11, 2022 |
| Samsung       | 935XDB                      | Notebook    | [fcfe8368c6](https://linux-hardware.org/?probe=fcfe8368c6) | Aug 08, 2022 |
| Dell          | 0JP3NX A00                  | Desktop     | [531e4340a6](https://linux-hardware.org/?probe=531e4340a6) | Aug 07, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [bd2dbeaa0e](https://linux-hardware.org/?probe=bd2dbeaa0e) | Aug 02, 2022 |
| Lenovo        | ThinkPad T470s 20HF0047U... | Notebook    | [dfe7ba57b8](https://linux-hardware.org/?probe=dfe7ba57b8) | Jul 31, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [d83f785b08](https://linux-hardware.org/?probe=d83f785b08) | Jul 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [5ed19c54a9](https://linux-hardware.org/?probe=5ed19c54a9) | Jul 27, 2022 |
| MSI           | AMETHYST-M                  | Desktop     | [d5fb610246](https://linux-hardware.org/?probe=d5fb610246) | Jul 26, 2022 |
| Samsung       | 935XDB                      | Notebook    | [d6149a337b](https://linux-hardware.org/?probe=d6149a337b) | Jul 26, 2022 |
| Dell          | 0V8WGR A01                  | Desktop     | [76ddff41fc](https://linux-hardware.org/?probe=76ddff41fc) | Jul 25, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [f70ea66873](https://linux-hardware.org/?probe=f70ea66873) | Jul 21, 2022 |
| Samsung       | 935XDB                      | Notebook    | [e01b518899](https://linux-hardware.org/?probe=e01b518899) | Jul 21, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [033c284273](https://linux-hardware.org/?probe=033c284273) | Jul 19, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [8d0399bc8d](https://linux-hardware.org/?probe=8d0399bc8d) | Jul 17, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [ef61582503](https://linux-hardware.org/?probe=ef61582503) | Jul 16, 2022 |
| Dell          | 0J3C2F A00                  | Desktop     | [e9be99b44d](https://linux-hardware.org/?probe=e9be99b44d) | Jul 14, 2022 |
| Jumper        | EZbook                      | Notebook    | [5e7336ee93](https://linux-hardware.org/?probe=5e7336ee93) | Jul 02, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [ca7efa311a](https://linux-hardware.org/?probe=ca7efa311a) | Jul 01, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [282d2ad16b](https://linux-hardware.org/?probe=282d2ad16b) | Jun 29, 2022 |
| ASUSTek       | X411UN                      | Notebook    | [d4543f64dc](https://linux-hardware.org/?probe=d4543f64dc) | Jun 24, 2022 |
| ASUSTek       | X411UN                      | Notebook    | [57e0198d3a](https://linux-hardware.org/?probe=57e0198d3a) | Jun 23, 2022 |
| Samsung       | 935XDB                      | Notebook    | [7089a0f6bc](https://linux-hardware.org/?probe=7089a0f6bc) | Jun 20, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [5caa4002f1](https://linux-hardware.org/?probe=5caa4002f1) | Jun 17, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [028b64776a](https://linux-hardware.org/?probe=028b64776a) | Jun 15, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [eef8a87283](https://linux-hardware.org/?probe=eef8a87283) | Jun 15, 2022 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [674cb88747](https://linux-hardware.org/?probe=674cb88747) | Jun 13, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [c1bde29740](https://linux-hardware.org/?probe=c1bde29740) | Jun 11, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [d9ac2ec5c8](https://linux-hardware.org/?probe=d9ac2ec5c8) | Jun 08, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [a38fb61dfb](https://linux-hardware.org/?probe=a38fb61dfb) | Jun 08, 2022 |
| Samsung       | 935XDB                      | Notebook    | [497a2424e0](https://linux-hardware.org/?probe=497a2424e0) | Jun 07, 2022 |
| Samsung       | 935XDB                      | Notebook    | [3cde44fcf1](https://linux-hardware.org/?probe=3cde44fcf1) | Jun 07, 2022 |
| Dell          | Precision M4800             | Notebook    | [3bd843466c](https://linux-hardware.org/?probe=3bd843466c) | Jun 04, 2022 |
| Dell          | Latitude 9420               | Notebook    | [28ba6de10d](https://linux-hardware.org/?probe=28ba6de10d) | Jun 01, 2022 |
| Samsung       | RC420/RC520/RC720           | Notebook    | [0a87c33624](https://linux-hardware.org/?probe=0a87c33624) | Jun 01, 2022 |
| ASUSTek       | Maximus VII IMPACT          | Desktop     | [8b0844f325](https://linux-hardware.org/?probe=8b0844f325) | Jun 01, 2022 |
| ASRock        | B365M Pro4-F                | Desktop     | [afc161c6fb](https://linux-hardware.org/?probe=afc161c6fb) | May 30, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [522da9476b](https://linux-hardware.org/?probe=522da9476b) | May 29, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [07b116767e](https://linux-hardware.org/?probe=07b116767e) | May 27, 2022 |
| Dell          | Latitude D520               | Notebook    | [55364bfdc0](https://linux-hardware.org/?probe=55364bfdc0) | May 24, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [39f9e9e717](https://linux-hardware.org/?probe=39f9e9e717) | May 22, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [342929d56c](https://linux-hardware.org/?probe=342929d56c) | May 19, 2022 |
| ASUSTek       | UX330UAK                    | Notebook    | [7b50efe523](https://linux-hardware.org/?probe=7b50efe523) | May 19, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [8471800bb3](https://linux-hardware.org/?probe=8471800bb3) | May 16, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [0d7682cb61](https://linux-hardware.org/?probe=0d7682cb61) | May 14, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [f71977d1fa](https://linux-hardware.org/?probe=f71977d1fa) | May 11, 2022 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [6cacb1c49c](https://linux-hardware.org/?probe=6cacb1c49c) | May 11, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [373e009d3b](https://linux-hardware.org/?probe=373e009d3b) | May 09, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [cd1aff125e](https://linux-hardware.org/?probe=cd1aff125e) | May 09, 2022 |
| ASRock        | AB350 Gaming-ITX/ac         | Desktop     | [6836f79bdf](https://linux-hardware.org/?probe=6836f79bdf) | May 08, 2022 |
| ASRock        | AB350 Gaming-ITX/ac         | Desktop     | [41cc4d30d4](https://linux-hardware.org/?probe=41cc4d30d4) | May 08, 2022 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [01369642f4](https://linux-hardware.org/?probe=01369642f4) | May 03, 2022 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [0d006e41fc](https://linux-hardware.org/?probe=0d006e41fc) | May 01, 2022 |
| MSI           | H55M-E23                    | Desktop     | [4ab5f58470](https://linux-hardware.org/?probe=4ab5f58470) | Apr 28, 2022 |
| MSI           | Stealth GS66 12UGS          | Notebook    | [bf36d72c14](https://linux-hardware.org/?probe=bf36d72c14) | Apr 26, 2022 |
| MSI           | Stealth GS66 12UGS          | Notebook    | [273526bab2](https://linux-hardware.org/?probe=273526bab2) | Apr 26, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [5e1b40c8b5](https://linux-hardware.org/?probe=5e1b40c8b5) | Apr 25, 2022 |
| Lenovo        | ThinkPad T440 20B7A0S200    | Notebook    | [0ef99a6615](https://linux-hardware.org/?probe=0ef99a6615) | Apr 24, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [ea4f513eb9](https://linux-hardware.org/?probe=ea4f513eb9) | Apr 22, 2022 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [02dd52b3b5](https://linux-hardware.org/?probe=02dd52b3b5) | Apr 21, 2022 |
| Dell          | Latitude E6230              | Notebook    | [617c507040](https://linux-hardware.org/?probe=617c507040) | Apr 19, 2022 |
| Dell          | Latitude E6230              | Notebook    | [98f4014ead](https://linux-hardware.org/?probe=98f4014ead) | Apr 19, 2022 |
| Packard Be... | EasyNote TK85               | Notebook    | [c20035dfb3](https://linux-hardware.org/?probe=c20035dfb3) | Apr 16, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [346c9b6c59](https://linux-hardware.org/?probe=346c9b6c59) | Apr 14, 2022 |
| Dell          | Latitude E6520              | Notebook    | [b10c0f8457](https://linux-hardware.org/?probe=b10c0f8457) | Apr 14, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [92e810b1dd](https://linux-hardware.org/?probe=92e810b1dd) | Apr 13, 2022 |
| Packard Be... | EasyNote TK85               | Notebook    | [c0eb727f3c](https://linux-hardware.org/?probe=c0eb727f3c) | Apr 12, 2022 |
| Packard Be... | EasyNote TK85               | Notebook    | [13d6da4ad9](https://linux-hardware.org/?probe=13d6da4ad9) | Apr 12, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [714baddf6f](https://linux-hardware.org/?probe=714baddf6f) | Apr 06, 2022 |
| Lenovo        | 312A SDK0J40700 WIN 3258... | Desktop     | [a645768047](https://linux-hardware.org/?probe=a645768047) | Apr 05, 2022 |
| Lenovo        | IdeaPadFlex 14 20308        | Notebook    | [9ecbc31fc2](https://linux-hardware.org/?probe=9ecbc31fc2) | Apr 04, 2022 |
| Notebook      | P65_P67RGRERA               | Notebook    | [654f1700c4](https://linux-hardware.org/?probe=654f1700c4) | Apr 04, 2022 |
| Dell          | Latitude 5420               | Notebook    | [75963e8b7d](https://linux-hardware.org/?probe=75963e8b7d) | Apr 01, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [3e5267891f](https://linux-hardware.org/?probe=3e5267891f) | Apr 01, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [0f98a36a43](https://linux-hardware.org/?probe=0f98a36a43) | Mar 30, 2022 |
| Dell          | Latitude E5440              | Notebook    | [82d2c39d98](https://linux-hardware.org/?probe=82d2c39d98) | Mar 30, 2022 |
| ASUSTek       | P8H61-MX USB3               | Desktop     | [949d5ffcf5](https://linux-hardware.org/?probe=949d5ffcf5) | Mar 26, 2022 |
| Intel         | DG45ID AAE46743-302         | Desktop     | [c185ef78b1](https://linux-hardware.org/?probe=c185ef78b1) | Mar 22, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [45c6461d6c](https://linux-hardware.org/?probe=45c6461d6c) | Mar 22, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [e117237c38](https://linux-hardware.org/?probe=e117237c38) | Mar 21, 2022 |
| Rockchip      | Unknown                     | Soc         | [fcef507e8e](https://linux-hardware.org/?probe=fcef507e8e) | Mar 18, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [f5723ec8b7](https://linux-hardware.org/?probe=f5723ec8b7) | Mar 15, 2022 |
| Dell          | Latitude E6430              | Notebook    | [bc21cb0e8b](https://linux-hardware.org/?probe=bc21cb0e8b) | Mar 13, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [27548876c6](https://linux-hardware.org/?probe=27548876c6) | Mar 11, 2022 |
| PC Special... | NH5xAx                      | Notebook    | [ebf60d959f](https://linux-hardware.org/?probe=ebf60d959f) | Mar 11, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [e7c5306c00](https://linux-hardware.org/?probe=e7c5306c00) | Mar 10, 2022 |
| ASRock        | Z68 Pro3                    | Desktop     | [4c4afb883e](https://linux-hardware.org/?probe=4c4afb883e) | Mar 09, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [0eaf02ff7d](https://linux-hardware.org/?probe=0eaf02ff7d) | Mar 07, 2022 |
| Dell          | Latitude 9420               | Notebook    | [355f64f6a7](https://linux-hardware.org/?probe=355f64f6a7) | Mar 03, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [44656b1bd4](https://linux-hardware.org/?probe=44656b1bd4) | Mar 03, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [34b97f062b](https://linux-hardware.org/?probe=34b97f062b) | Mar 01, 2022 |
| HP            | 21D0                        | Desktop     | [448912eeb9](https://linux-hardware.org/?probe=448912eeb9) | Feb 24, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [6dd3795cad](https://linux-hardware.org/?probe=6dd3795cad) | Feb 24, 2022 |
| ASUSTek       | GL753VE                     | Notebook    | [25f1ab36fc](https://linux-hardware.org/?probe=25f1ab36fc) | Feb 20, 2022 |
| Dell          | Precision M4600             | Notebook    | [9f1f4fcf9c](https://linux-hardware.org/?probe=9f1f4fcf9c) | Feb 18, 2022 |
| Acer          | Predator PH317-54           | Notebook    | [8fb9ac25be](https://linux-hardware.org/?probe=8fb9ac25be) | Feb 11, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [ace22bd471](https://linux-hardware.org/?probe=ace22bd471) | Feb 11, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [bb5bd32928](https://linux-hardware.org/?probe=bb5bd32928) | Feb 10, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [2c93e69093](https://linux-hardware.org/?probe=2c93e69093) | Feb 07, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [7f24cf6cc9](https://linux-hardware.org/?probe=7f24cf6cc9) | Feb 07, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [45922e4586](https://linux-hardware.org/?probe=45922e4586) | Feb 04, 2022 |
| Dell          | 0X4H68 A00                  | Desktop     | [3ecad8d7e4](https://linux-hardware.org/?probe=3ecad8d7e4) | Feb 02, 2022 |
| Lenovo        | ThinkPad T480s 20L7S0VJ0... | Notebook    | [7535369bb0](https://linux-hardware.org/?probe=7535369bb0) | Jan 31, 2022 |
| Dell          | 0X4H68 A00                  | Desktop     | [0e6a0c4725](https://linux-hardware.org/?probe=0e6a0c4725) | Jan 29, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [311e85f0cb](https://linux-hardware.org/?probe=311e85f0cb) | Jan 27, 2022 |
| ASRock        | Z68 Pro3                    | Desktop     | [4cdd6daf44](https://linux-hardware.org/?probe=4cdd6daf44) | Jan 19, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [c8932dbfd0](https://linux-hardware.org/?probe=c8932dbfd0) | Jan 15, 2022 |
| Intel         | DG45ID AAE46743-302         | Desktop     | [ab40e8dd7d](https://linux-hardware.org/?probe=ab40e8dd7d) | Jan 14, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [8c319cd6fc](https://linux-hardware.org/?probe=8c319cd6fc) | Jan 11, 2022 |
| Notebook      | P15SM                       | Notebook    | [3b7c794008](https://linux-hardware.org/?probe=3b7c794008) | Jan 08, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [4fad903d2a](https://linux-hardware.org/?probe=4fad903d2a) | Jan 06, 2022 |
| Toshiba       | PORTEGE R830                | Notebook    | [097edea6f9](https://linux-hardware.org/?probe=097edea6f9) | Jan 06, 2022 |
| Toshiba       | PORTEGE R830                | Notebook    | [41ed435a4f](https://linux-hardware.org/?probe=41ed435a4f) | Jan 04, 2022 |
| Dell          | Latitude 5411               | Notebook    | [2064d78411](https://linux-hardware.org/?probe=2064d78411) | Jan 03, 2022 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [4894e2c956](https://linux-hardware.org/?probe=4894e2c956) | Jan 02, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [aea80bda1f](https://linux-hardware.org/?probe=aea80bda1f) | Jan 01, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [4161b37157](https://linux-hardware.org/?probe=4161b37157) | Dec 30, 2021 |
| Lenovo        | ThinkPad X220 4291W99       | Notebook    | [ead56def80](https://linux-hardware.org/?probe=ead56def80) | Dec 26, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [296af779e4](https://linux-hardware.org/?probe=296af779e4) | Dec 20, 2021 |
| Lenovo        | ThinkPad E560 20EV000TUK    | Notebook    | [609264397b](https://linux-hardware.org/?probe=609264397b) | Dec 19, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [7230ad27b7](https://linux-hardware.org/?probe=7230ad27b7) | Dec 19, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [7b6327d329](https://linux-hardware.org/?probe=7b6327d329) | Dec 19, 2021 |
| Acer          | Aspire E5-575G              | Notebook    | [342ba009be](https://linux-hardware.org/?probe=342ba009be) | Dec 19, 2021 |
| Lenovo        | ThinkPad E560 20EV000TUK    | Notebook    | [eefaa1b951](https://linux-hardware.org/?probe=eefaa1b951) | Dec 18, 2021 |
| AVITA         | NS14A8                      | Notebook    | [0ae2523309](https://linux-hardware.org/?probe=0ae2523309) | Dec 18, 2021 |
| Nvidia        | Tegra                       | Soc         | [30c09e0585](https://linux-hardware.org/?probe=30c09e0585) | Dec 17, 2021 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | Notebook    | [ece425bcfc](https://linux-hardware.org/?probe=ece425bcfc) | Dec 12, 2021 |
| HP            | 1495                        | Desktop     | [489e740957](https://linux-hardware.org/?probe=489e740957) | Dec 12, 2021 |
| Dell          | XPS 15 9510                 | Notebook    | [da1818e0c5](https://linux-hardware.org/?probe=da1818e0c5) | Dec 12, 2021 |
| Lenovo        | ThinkPad P52 20MAS17205     | Notebook    | [86d1d49f33](https://linux-hardware.org/?probe=86d1d49f33) | Dec 09, 2021 |
| MSI           | B450 GAMING PLUS            | Desktop     | [69b4695e8d](https://linux-hardware.org/?probe=69b4695e8d) | Dec 04, 2021 |
| Dell          | 0J3C2F A00                  | Desktop     | [bfead2c865](https://linux-hardware.org/?probe=bfead2c865) | Dec 04, 2021 |
| Acer          | AOD255                      | Notebook    | [eae98753db](https://linux-hardware.org/?probe=eae98753db) | Dec 03, 2021 |
| Acer          | AOD255                      | Notebook    | [d2e31c1441](https://linux-hardware.org/?probe=d2e31c1441) | Dec 02, 2021 |
| Acer          | Aspire A315-51              | Notebook    | [397f62191b](https://linux-hardware.org/?probe=397f62191b) | Nov 28, 2021 |
| Sony          | VPCCB35FG                   | Notebook    | [6e46b79e09](https://linux-hardware.org/?probe=6e46b79e09) | Nov 27, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [6c08986736](https://linux-hardware.org/?probe=6c08986736) | Nov 24, 2021 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [291a2a17e2](https://linux-hardware.org/?probe=291a2a17e2) | Nov 21, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [bb51358294](https://linux-hardware.org/?probe=bb51358294) | Nov 18, 2021 |
| Dell          | Inspiron MM061              | Notebook    | [0424bd331e](https://linux-hardware.org/?probe=0424bd331e) | Nov 10, 2021 |
| HP            | Notebook                    | Notebook    | [65c122fe69](https://linux-hardware.org/?probe=65c122fe69) | Oct 31, 2021 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [00ac329183](https://linux-hardware.org/?probe=00ac329183) | Oct 30, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [22bc284f45](https://linux-hardware.org/?probe=22bc284f45) | Oct 27, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [3e574fa012](https://linux-hardware.org/?probe=3e574fa012) | Oct 25, 2021 |
| Toshiba       | PORTEGE R830                | Notebook    | [7105829e72](https://linux-hardware.org/?probe=7105829e72) | Oct 25, 2021 |
| Dell          | Inspiron 3583               | Notebook    | [8f25043c64](https://linux-hardware.org/?probe=8f25043c64) | Oct 24, 2021 |
| Lenovo        | G550 2958                   | Notebook    | [b9412e1ab2](https://linux-hardware.org/?probe=b9412e1ab2) | Oct 23, 2021 |
| Lenovo        | G550 2958                   | Notebook    | [a0ff38d606](https://linux-hardware.org/?probe=a0ff38d606) | Oct 22, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [4add26ac8c](https://linux-hardware.org/?probe=4add26ac8c) | Oct 21, 2021 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [cbff9b4baf](https://linux-hardware.org/?probe=cbff9b4baf) | Oct 21, 2021 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [1e6b01d3bd](https://linux-hardware.org/?probe=1e6b01d3bd) | Oct 21, 2021 |
| HP            | 21D0                        | Desktop     | [1dbb2b4a2d](https://linux-hardware.org/?probe=1dbb2b4a2d) | Oct 20, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [c11c89f0d4](https://linux-hardware.org/?probe=c11c89f0d4) | Oct 19, 2021 |
| ASUSTek       | X501A1                      | Notebook    | [0494cb6f11](https://linux-hardware.org/?probe=0494cb6f11) | Oct 13, 2021 |
| Toshiba       | PORTEGE R830                | Notebook    | [b22927e36e](https://linux-hardware.org/?probe=b22927e36e) | Oct 12, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [74cbbcac9f](https://linux-hardware.org/?probe=74cbbcac9f) | Oct 07, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [f564d05797](https://linux-hardware.org/?probe=f564d05797) | Oct 05, 2021 |
| MSI           | MS-7270                     | Desktop     | [4281e009bb](https://linux-hardware.org/?probe=4281e009bb) | Oct 05, 2021 |
| HP            | 1998                        | Desktop     | [74a28b051a](https://linux-hardware.org/?probe=74a28b051a) | Oct 03, 2021 |
| Apple         | MacBookPro5,3               | Notebook    | [b0ea83da4d](https://linux-hardware.org/?probe=b0ea83da4d) | Oct 02, 2021 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [ddcd85bbe5](https://linux-hardware.org/?probe=ddcd85bbe5) | Oct 02, 2021 |
| Timi          | TM1607                      | Notebook    | [aa8b5d346a](https://linux-hardware.org/?probe=aa8b5d346a) | Sep 26, 2021 |
| ASUSTek       | Maximus VIII FORMULA        | Desktop     | [5acbf68626](https://linux-hardware.org/?probe=5acbf68626) | Sep 25, 2021 |
| Apple         | MacBook6,1                  | Notebook    | [4fbbe3d05b](https://linux-hardware.org/?probe=4fbbe3d05b) | Sep 19, 2021 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [9710e6ad6f](https://linux-hardware.org/?probe=9710e6ad6f) | Sep 19, 2021 |
| HP            | Notebook                    | Notebook    | [9c7d616423](https://linux-hardware.org/?probe=9c7d616423) | Sep 12, 2021 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [7500e17316](https://linux-hardware.org/?probe=7500e17316) | Sep 11, 2021 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [64a2841581](https://linux-hardware.org/?probe=64a2841581) | Sep 11, 2021 |
| Schenker      | XMG NEO (TGL/M21)           | Notebook    | [de8f619f3c](https://linux-hardware.org/?probe=de8f619f3c) | Sep 10, 2021 |
| Dell          | Inspiron 3585               | Notebook    | [3a55618aee](https://linux-hardware.org/?probe=3a55618aee) | Sep 10, 2021 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [feec038877](https://linux-hardware.org/?probe=feec038877) | Sep 06, 2021 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [c5fbf3298a](https://linux-hardware.org/?probe=c5fbf3298a) | Sep 06, 2021 |
| Lenovo        | ThinkPad E15 20RD0015FR     | Notebook    | [8a229968ef](https://linux-hardware.org/?probe=8a229968ef) | Sep 06, 2021 |
| Samsung       | 550P5C/550P7C               | Notebook    | [c483c45fc4](https://linux-hardware.org/?probe=c483c45fc4) | Sep 03, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [f1b601400c](https://linux-hardware.org/?probe=f1b601400c) | Sep 01, 2021 |
| TUXEDO        | InfinityBook Pro 15 v5      | Notebook    | [e0a78bb2e5](https://linux-hardware.org/?probe=e0a78bb2e5) | Aug 30, 2021 |
| Dell          | 0J37VM A01                  | Desktop     | [88012fdf33](https://linux-hardware.org/?probe=88012fdf33) | Aug 30, 2021 |
| Toshiba       | Satellite A300              | Notebook    | [c5391fae24](https://linux-hardware.org/?probe=c5391fae24) | Aug 27, 2021 |
| Dell          | Precision 5550              | Notebook    | [705dbe4068](https://linux-hardware.org/?probe=705dbe4068) | Aug 21, 2021 |
| Medion        | Akoya E6239                 | Notebook    | [e22d5c4b21](https://linux-hardware.org/?probe=e22d5c4b21) | Aug 20, 2021 |
| MSI           | B450 GAMING PLUS            | Desktop     | [f5d2b51d19](https://linux-hardware.org/?probe=f5d2b51d19) | Aug 16, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [92d57d3ea8](https://linux-hardware.org/?probe=92d57d3ea8) | Aug 15, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [3edbab6d15](https://linux-hardware.org/?probe=3edbab6d15) | Aug 15, 2021 |
| Dell          | 0X9M3X A01                  | Desktop     | [b5b9c80c53](https://linux-hardware.org/?probe=b5b9c80c53) | Aug 14, 2021 |
| Sony          | VPCCB35FG                   | Notebook    | [6550f39d03](https://linux-hardware.org/?probe=6550f39d03) | Aug 10, 2021 |
| Dell          | Inspiron 3583               | Notebook    | [17b5565505](https://linux-hardware.org/?probe=17b5565505) | Aug 08, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [1ea279df08](https://linux-hardware.org/?probe=1ea279df08) | Aug 08, 2021 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [5ba990c425](https://linux-hardware.org/?probe=5ba990c425) | Aug 04, 2021 |
| Acer          | Swift SF313-53              | Notebook    | [f16feed16c](https://linux-hardware.org/?probe=f16feed16c) | Aug 03, 2021 |
| ASUSTek       | PRIME A320M-C R2.0          | Desktop     | [32e0ae8af0](https://linux-hardware.org/?probe=32e0ae8af0) | Aug 03, 2021 |
| Dell          | 0KRC95 A00                  | Desktop     | [f8c48b22e6](https://linux-hardware.org/?probe=f8c48b22e6) | Aug 02, 2021 |
| Lenovo        | ThinkPad P50 20EN0007MS     | Notebook    | [73902de0d8](https://linux-hardware.org/?probe=73902de0d8) | Jul 31, 2021 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [69869dec40](https://linux-hardware.org/?probe=69869dec40) | Jul 27, 2021 |
| Dell          | Studio XPS 1640             | Notebook    | [00d5936a25](https://linux-hardware.org/?probe=00d5936a25) | Jul 22, 2021 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [1046a771fd](https://linux-hardware.org/?probe=1046a771fd) | Jul 19, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | Notebook    | [77ab0c578d](https://linux-hardware.org/?probe=77ab0c578d) | Jul 17, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | Notebook    | [06ba47ee9a](https://linux-hardware.org/?probe=06ba47ee9a) | Jul 17, 2021 |
| ASRock        | J4105M                      | Desktop     | [b732da09a3](https://linux-hardware.org/?probe=b732da09a3) | Jul 04, 2021 |
| ASRock        | J4105M                      | Desktop     | [a2d5afa1d6](https://linux-hardware.org/?probe=a2d5afa1d6) | Jul 04, 2021 |
| Dell          | Latitude 7370               | Notebook    | [4fc6100966](https://linux-hardware.org/?probe=4fc6100966) | Jul 03, 2021 |
| Dell          | Latitude 7370               | Notebook    | [2acd089f78](https://linux-hardware.org/?probe=2acd089f78) | Jul 03, 2021 |
| ASRock        | Z77 Extreme3                | Desktop     | [ecd7ec8f36](https://linux-hardware.org/?probe=ecd7ec8f36) | Jul 02, 2021 |
| Entroware     | Apollo                      | Notebook    | [3cbf412b11](https://linux-hardware.org/?probe=3cbf412b11) | Jul 01, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [fff9c1a758](https://linux-hardware.org/?probe=fff9c1a758) | Jun 22, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | Notebook    | [3980434b64](https://linux-hardware.org/?probe=3980434b64) | Jun 19, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [27fea5c8cb](https://linux-hardware.org/?probe=27fea5c8cb) | Jun 12, 2021 |
| Dell          | Inspiron 1525               | Notebook    | [511a525213](https://linux-hardware.org/?probe=511a525213) | Jun 11, 2021 |
| ASUSTek       | P6X58D-E                    | Desktop     | [1ccc05a479](https://linux-hardware.org/?probe=1ccc05a479) | Jun 09, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f8241fa3ce](https://linux-hardware.org/?probe=f8241fa3ce) | Jun 08, 2021 |
| Dell          | XPS 13 9300                 | Notebook    | [63f094943a](https://linux-hardware.org/?probe=63f094943a) | Jun 07, 2021 |
| Dell          | Latitude C810               | Notebook    | [f379321c88](https://linux-hardware.org/?probe=f379321c88) | Jun 05, 2021 |
| Dell          | Inspiron MM061              | Notebook    | [62b30f282d](https://linux-hardware.org/?probe=62b30f282d) | Jun 04, 2021 |
| Dell          | Latitude C810               | Notebook    | [23e6f5572a](https://linux-hardware.org/?probe=23e6f5572a) | Jun 04, 2021 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [6c770833c9](https://linux-hardware.org/?probe=6c770833c9) | Jun 04, 2021 |
| Toshiba       | TECRA M4                    | Notebook    | [3ac511cc5f](https://linux-hardware.org/?probe=3ac511cc5f) | Jun 03, 2021 |
| Lenovo        | B50-30 80ES                 | Notebook    | [6fff0f3407](https://linux-hardware.org/?probe=6fff0f3407) | Jun 03, 2021 |
| Lenovo        | B50-30 80ES                 | Notebook    | [cfa1b1a4fd](https://linux-hardware.org/?probe=cfa1b1a4fd) | Jun 03, 2021 |
| Dell          | 07F37C A01                  | Desktop     | [baba8a29ac](https://linux-hardware.org/?probe=baba8a29ac) | Jun 02, 2021 |
| Dell          | Inspiron 1764               | Notebook    | [a41c941365](https://linux-hardware.org/?probe=a41c941365) | Jun 02, 2021 |
| Entroware     | Proteus                     | Notebook    | [0ecc547a14](https://linux-hardware.org/?probe=0ecc547a14) | May 31, 2021 |
| MSI           | MS-7270                     | Desktop     | [7cc66e3a90](https://linux-hardware.org/?probe=7cc66e3a90) | May 29, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [3c83289b45](https://linux-hardware.org/?probe=3c83289b45) | May 28, 2021 |
| HP            | Pavilion 15                 | Notebook    | [14128860c2](https://linux-hardware.org/?probe=14128860c2) | May 27, 2021 |
| HP            | ProBook 6550b               | Notebook    | [523c397ab6](https://linux-hardware.org/?probe=523c397ab6) | May 27, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [e7292a5491](https://linux-hardware.org/?probe=e7292a5491) | May 26, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [bb6ab823e7](https://linux-hardware.org/?probe=bb6ab823e7) | May 23, 2021 |
| HP            | 3397                        | Desktop     | [ae9a8581c5](https://linux-hardware.org/?probe=ae9a8581c5) | May 23, 2021 |
| MSI           | X470 GAMING PRO             | Desktop     | [f7c5833c2a](https://linux-hardware.org/?probe=f7c5833c2a) | May 23, 2021 |
| HP            | 15                          | Notebook    | [ab211b6ad8](https://linux-hardware.org/?probe=ab211b6ad8) | May 21, 2021 |
| HP            | 15                          | Notebook    | [d285154a2b](https://linux-hardware.org/?probe=d285154a2b) | May 21, 2021 |
| Shuttle       | FS35V4                      | Desktop     | [6f9a85a086](https://linux-hardware.org/?probe=6f9a85a086) | May 21, 2021 |
| Shuttle       | FS35V4                      | Desktop     | [acd3144c20](https://linux-hardware.org/?probe=acd3144c20) | May 21, 2021 |
| HP            | 18E5                        | Desktop     | [6cbae0f799](https://linux-hardware.org/?probe=6cbae0f799) | May 20, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ea97f7d05d](https://linux-hardware.org/?probe=ea97f7d05d) | May 20, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [824ec14630](https://linux-hardware.org/?probe=824ec14630) | May 20, 2021 |
| Entroware     | Proteus                     | Notebook    | [98be1903c4](https://linux-hardware.org/?probe=98be1903c4) | May 17, 2021 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [80f0e0228b](https://linux-hardware.org/?probe=80f0e0228b) | May 16, 2021 |
| Dell          | Latitude 5520               | Notebook    | [34c3dc01e9](https://linux-hardware.org/?probe=34c3dc01e9) | May 07, 2021 |
| Lenovo        | 3140 SDK0J40700 WIN 3258... | Desktop     | [452f706571](https://linux-hardware.org/?probe=452f706571) | May 07, 2021 |
| HP            | HDX 18                      | Notebook    | [dead2b5b56](https://linux-hardware.org/?probe=dead2b5b56) | May 07, 2021 |
| ASRock        | Z490M Pro4                  | Desktop     | [d1d4f84e0a](https://linux-hardware.org/?probe=d1d4f84e0a) | May 03, 2021 |
| HP            | EliteBook Folio G1          | Notebook    | [f3bdc3e991](https://linux-hardware.org/?probe=f3bdc3e991) | Apr 24, 2021 |
| Acer          | Aspire 5333                 | Notebook    | [c6227d5004](https://linux-hardware.org/?probe=c6227d5004) | Apr 23, 2021 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [fe576d54b4](https://linux-hardware.org/?probe=fe576d54b4) | Apr 23, 2021 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [e651f5da2c](https://linux-hardware.org/?probe=e651f5da2c) | Apr 23, 2021 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [be651d63a0](https://linux-hardware.org/?probe=be651d63a0) | Apr 19, 2021 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [9c0bbd0e0c](https://linux-hardware.org/?probe=9c0bbd0e0c) | Apr 18, 2021 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [0ceacbca21](https://linux-hardware.org/?probe=0ceacbca21) | Apr 17, 2021 |
| Acer          | Aspire 5333                 | Notebook    | [2171d74173](https://linux-hardware.org/?probe=2171d74173) | Apr 15, 2021 |
| Acer          | Aspire 5333                 | Notebook    | [dd4fee2ece](https://linux-hardware.org/?probe=dd4fee2ece) | Apr 15, 2021 |
| Dell          | 0NNNCT A01                  | Desktop     | [8253ac8502](https://linux-hardware.org/?probe=8253ac8502) | Apr 10, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [2e946e600e](https://linux-hardware.org/?probe=2e946e600e) | Apr 08, 2021 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [51b67b480d](https://linux-hardware.org/?probe=51b67b480d) | Apr 05, 2021 |
| Intel         | NUC11PABi5 K90634-302       | Mini pc     | [93033ed87e](https://linux-hardware.org/?probe=93033ed87e) | Apr 04, 2021 |
| Intel         | NUC11PABi5 K90634-302       | Mini pc     | [6b926d1195](https://linux-hardware.org/?probe=6b926d1195) | Apr 04, 2021 |
| HP            | Pavilion g6                 | Notebook    | [726040b78b](https://linux-hardware.org/?probe=726040b78b) | Apr 03, 2021 |
| Gigabyte      | TRX40 DESIGNARE             | Desktop     | [6917221b5b](https://linux-hardware.org/?probe=6917221b5b) | Apr 02, 2021 |
| ASUSTek       | P8Z77-V                     | Desktop     | [9e21f67ab7](https://linux-hardware.org/?probe=9e21f67ab7) | Mar 28, 2021 |
| Acer          | Aspire 5920G                | Notebook    | [9976792f0f](https://linux-hardware.org/?probe=9976792f0f) | Mar 26, 2021 |
| Lenovo        | ThinkPad W530 24491D1       | Notebook    | [31a4336d63](https://linux-hardware.org/?probe=31a4336d63) | Mar 25, 2021 |
| Microtech     | e-book Lite                 | Notebook    | [85b6d19466](https://linux-hardware.org/?probe=85b6d19466) | Mar 23, 2021 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | Notebook    | [488904f6d8](https://linux-hardware.org/?probe=488904f6d8) | Mar 18, 2021 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | Notebook    | [7fbf31af63](https://linux-hardware.org/?probe=7fbf31af63) | Mar 18, 2021 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [1b571fd1c4](https://linux-hardware.org/?probe=1b571fd1c4) | Mar 18, 2021 |
| Dell          | 0NNNCT A01                  | Desktop     | [e5a6c9dcb9](https://linux-hardware.org/?probe=e5a6c9dcb9) | Mar 17, 2021 |
| ASUSTek       | X540LA                      | Notebook    | [8b0145ff0c](https://linux-hardware.org/?probe=8b0145ff0c) | Mar 13, 2021 |
| Lenovo        | ThinkPad T430 2349G7G       | Notebook    | [d2ff3aaec4](https://linux-hardware.org/?probe=d2ff3aaec4) | Mar 12, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [f2f15e9ef1](https://linux-hardware.org/?probe=f2f15e9ef1) | Mar 10, 2021 |
| Pegatron      | 2A94h                       | Desktop     | [b035a149a3](https://linux-hardware.org/?probe=b035a149a3) | Mar 02, 2021 |
| Medion        | MS-7646                     | Desktop     | [5ca2e128b6](https://linux-hardware.org/?probe=5ca2e128b6) | Feb 24, 2021 |
| HP            | Pavilion m6                 | Notebook    | [578aad5ad5](https://linux-hardware.org/?probe=578aad5ad5) | Feb 24, 2021 |
| HP            | Notebook                    | Notebook    | [21ead6ec52](https://linux-hardware.org/?probe=21ead6ec52) | Feb 22, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [7dbba6ee59](https://linux-hardware.org/?probe=7dbba6ee59) | Feb 21, 2021 |
| Dell          | 0GDG8Y A00                  | Desktop     | [8f2450a3b0](https://linux-hardware.org/?probe=8f2450a3b0) | Feb 20, 2021 |
| HP            | Compaq 6530b (GW688AV)      | Notebook    | [2812d098fd](https://linux-hardware.org/?probe=2812d098fd) | Feb 20, 2021 |
| HP            | Stream Laptop 11-y0XX       | Notebook    | [ce0aecd52b](https://linux-hardware.org/?probe=ce0aecd52b) | Feb 20, 2021 |
| Dell          | 0WR7PY A03                  | Desktop     | [878e82f1a3](https://linux-hardware.org/?probe=878e82f1a3) | Feb 19, 2021 |
| HP            | EliteBook 745 G6            | Notebook    | [3bf39bac3e](https://linux-hardware.org/?probe=3bf39bac3e) | Feb 19, 2021 |
| Apple         | MacBookPro2,2               | Notebook    | [52f24b3228](https://linux-hardware.org/?probe=52f24b3228) | Feb 19, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [6fad2f0ade](https://linux-hardware.org/?probe=6fad2f0ade) | Feb 14, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [46556ad380](https://linux-hardware.org/?probe=46556ad380) | Feb 14, 2021 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [78c7860103](https://linux-hardware.org/?probe=78c7860103) | Feb 10, 2021 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [8647ccdbef](https://linux-hardware.org/?probe=8647ccdbef) | Feb 10, 2021 |
| MSI           | 2AE0                        | Desktop     | [374ff27ab8](https://linux-hardware.org/?probe=374ff27ab8) | Feb 09, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [6ef4606f95](https://linux-hardware.org/?probe=6ef4606f95) | Feb 09, 2021 |
| HP            | 1495                        | Desktop     | [d8d36f4b2b](https://linux-hardware.org/?probe=d8d36f4b2b) | Feb 08, 2021 |
| Dell          | 0HY9JP A02                  | Desktop     | [51ede3687a](https://linux-hardware.org/?probe=51ede3687a) | Feb 05, 2021 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [ec083139fc](https://linux-hardware.org/?probe=ec083139fc) | Feb 05, 2021 |
| Samsung       | Galaxy TabPro S             | Tablet      | [4e4ef907a0](https://linux-hardware.org/?probe=4e4ef907a0) | Feb 05, 2021 |
| Dell          | 0HY9JP A02                  | Desktop     | [6c4261b08f](https://linux-hardware.org/?probe=6c4261b08f) | Feb 05, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [b1ed72b941](https://linux-hardware.org/?probe=b1ed72b941) | Feb 04, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [d4502d7365](https://linux-hardware.org/?probe=d4502d7365) | Jan 28, 2021 |
| Lenovo        | ThinkPad P52 20MAS17205     | Notebook    | [0a2ca85ddc](https://linux-hardware.org/?probe=0a2ca85ddc) | Jan 22, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [2c59be484e](https://linux-hardware.org/?probe=2c59be484e) | Jan 22, 2021 |
| Dell          | 0P4T42 A00                  | All in one  | [1dbf9cced7](https://linux-hardware.org/?probe=1dbf9cced7) | Jan 22, 2021 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [9f3cf476f3](https://linux-hardware.org/?probe=9f3cf476f3) | Jan 19, 2021 |
| ASUSTek       | Maximus IV Extreme          | Desktop     | [9ce5eab595](https://linux-hardware.org/?probe=9ce5eab595) | Jan 16, 2021 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [192f01dd70](https://linux-hardware.org/?probe=192f01dd70) | Jan 16, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [e8cd5368b0](https://linux-hardware.org/?probe=e8cd5368b0) | Jan 14, 2021 |
| Lenovo        | ThinkPad T430 2349G7G       | Notebook    | [a6e84d99aa](https://linux-hardware.org/?probe=a6e84d99aa) | Jan 14, 2021 |
| Dell          | System XPS L502X            | Notebook    | [8b67c2132b](https://linux-hardware.org/?probe=8b67c2132b) | Jan 13, 2021 |
| Dell          | Precision 5550              | Notebook    | [ba201aad9e](https://linux-hardware.org/?probe=ba201aad9e) | Jan 11, 2021 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [54b2f4c522](https://linux-hardware.org/?probe=54b2f4c522) | Jan 11, 2021 |
| MSI           | X470 GAMING PRO             | Desktop     | [d7528e4806](https://linux-hardware.org/?probe=d7528e4806) | Jan 09, 2021 |
| HUAWEI        | BOHL-WXX9                   | Notebook    | [5845d9565c](https://linux-hardware.org/?probe=5845d9565c) | Jan 05, 2021 |
| ASUSTek       | X550CC                      | Notebook    | [40ae1409a4](https://linux-hardware.org/?probe=40ae1409a4) | Jan 05, 2021 |
| Entroware     | Proteus                     | Notebook    | [7d71ef8a53](https://linux-hardware.org/?probe=7d71ef8a53) | Jan 05, 2021 |
| Samsung       | N150/N210/N220              | Notebook    | [e556ab958b](https://linux-hardware.org/?probe=e556ab958b) | Jan 02, 2021 |
| Intel         | NUC10i3FNB K61362-302       | Mini pc     | [59440917d2](https://linux-hardware.org/?probe=59440917d2) | Jan 01, 2021 |
| Samsung       | N150/N210/N220              | Notebook    | [adc4530996](https://linux-hardware.org/?probe=adc4530996) | Jan 01, 2021 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [b34a40d6b3](https://linux-hardware.org/?probe=b34a40d6b3) | Dec 31, 2020 |
| Lenovo        | ThinkPad E560 20EV000UUK    | Notebook    | [c38d67b61b](https://linux-hardware.org/?probe=c38d67b61b) | Dec 30, 2020 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [8740e02802](https://linux-hardware.org/?probe=8740e02802) | Dec 29, 2020 |
| ASUSTek       | F2A55-M LK2                 | Desktop     | [b6ffae8f7a](https://linux-hardware.org/?probe=b6ffae8f7a) | Dec 27, 2020 |
| HP            | 3032h                       | Desktop     | [c71be55264](https://linux-hardware.org/?probe=c71be55264) | Dec 24, 2020 |
| Dell          | System XPS L502X            | Notebook    | [dda884ab5b](https://linux-hardware.org/?probe=dda884ab5b) | Dec 20, 2020 |
| MSI           | MEG X399 CREATION           | Desktop     | [d1e772d769](https://linux-hardware.org/?probe=d1e772d769) | Dec 11, 2020 |
| Acer          | Aspire 5551                 | Notebook    | [cb35dac70b](https://linux-hardware.org/?probe=cb35dac70b) | Dec 09, 2020 |
| HP            | Notebook                    | Notebook    | [2564f14d0b](https://linux-hardware.org/?probe=2564f14d0b) | Dec 06, 2020 |
| Lenovo        | G580 20157                  | Notebook    | [325dd21da3](https://linux-hardware.org/?probe=325dd21da3) | Nov 27, 2020 |
| MSI           | MS-7270                     | Desktop     | [b4e45eae99](https://linux-hardware.org/?probe=b4e45eae99) | Nov 26, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [703167df7b](https://linux-hardware.org/?probe=703167df7b) | Nov 24, 2020 |
| Dell          | Inspiron 15-3567            | Notebook    | [04e06f0e3b](https://linux-hardware.org/?probe=04e06f0e3b) | Nov 23, 2020 |
| HP            | Presario V6500              | Notebook    | [6950f2532b](https://linux-hardware.org/?probe=6950f2532b) | Nov 23, 2020 |
| HP            | Presario V6500              | Notebook    | [f4f30c83df](https://linux-hardware.org/?probe=f4f30c83df) | Nov 23, 2020 |
| HP            | EliteBook 8740w             | Notebook    | [f30611840c](https://linux-hardware.org/?probe=f30611840c) | Nov 23, 2020 |
| PC Special... | PCX0DX                      | Notebook    | [b4498047ef](https://linux-hardware.org/?probe=b4498047ef) | Nov 22, 2020 |
| Apple         | MacBookPro5,4               | Notebook    | [a7492067f0](https://linux-hardware.org/?probe=a7492067f0) | Nov 21, 2020 |
| HP            | EliteBook 820 G1            | Notebook    | [4db5c39f50](https://linux-hardware.org/?probe=4db5c39f50) | Nov 21, 2020 |
| Lenovo        | ThinkPad T400 64754G7       | Notebook    | [770660037c](https://linux-hardware.org/?probe=770660037c) | Nov 21, 2020 |
| HP            | EliteBook 8740w             | Notebook    | [072b557a79](https://linux-hardware.org/?probe=072b557a79) | Nov 20, 2020 |
| Lenovo        | G580 20157                  | Notebook    | [58fc01c757](https://linux-hardware.org/?probe=58fc01c757) | Nov 19, 2020 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [d8379e8abb](https://linux-hardware.org/?probe=d8379e8abb) | Nov 18, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3443C... | Notebook    | [578d1badca](https://linux-hardware.org/?probe=578d1badca) | Nov 18, 2020 |
| Alienware     | 17 R4                       | Notebook    | [8b7402a4e7](https://linux-hardware.org/?probe=8b7402a4e7) | Nov 16, 2020 |
| Alienware     | 17 R4                       | Notebook    | [62e5ac4fd3](https://linux-hardware.org/?probe=62e5ac4fd3) | Nov 16, 2020 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [7132bcc66d](https://linux-hardware.org/?probe=7132bcc66d) | Nov 15, 2020 |
| MSI           | MS-7270                     | Desktop     | [c70e52b025](https://linux-hardware.org/?probe=c70e52b025) | Nov 13, 2020 |
| Dell          | Latitude E6420              | Notebook    | [f542aafd19](https://linux-hardware.org/?probe=f542aafd19) | Nov 13, 2020 |
| HP            | 1495                        | Desktop     | [a250ea93d5](https://linux-hardware.org/?probe=a250ea93d5) | Nov 10, 2020 |
| Notebook      | NL40_50CU                   | Notebook    | [893477956d](https://linux-hardware.org/?probe=893477956d) | Nov 10, 2020 |
| Toshiba       | Satellite Pro R50-B         | Notebook    | [418e9ce805](https://linux-hardware.org/?probe=418e9ce805) | Nov 06, 2020 |
| Toshiba       | Satellite Pro R50-B         | Notebook    | [7780f8f320](https://linux-hardware.org/?probe=7780f8f320) | Nov 06, 2020 |
| MSI           | MS-7270                     | Desktop     | [97556dedc3](https://linux-hardware.org/?probe=97556dedc3) | Nov 05, 2020 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [eac2b32ee0](https://linux-hardware.org/?probe=eac2b32ee0) | Nov 04, 2020 |
| System76      | Galago Pro                  | Notebook    | [79822a5348](https://linux-hardware.org/?probe=79822a5348) | Nov 04, 2020 |
| Dell          | XPS M1530                   | Notebook    | [bc52d9b9a4](https://linux-hardware.org/?probe=bc52d9b9a4) | Nov 03, 2020 |
| Dell          | Dimension 5100              | Desktop     | [f18393d9aa](https://linux-hardware.org/?probe=f18393d9aa) | Nov 03, 2020 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [3be1cd15b1](https://linux-hardware.org/?probe=3be1cd15b1) | Oct 30, 2020 |
| Medion        | E6239 MD99452               | Notebook    | [2496b738ac](https://linux-hardware.org/?probe=2496b738ac) | Oct 29, 2020 |
| Medion        | E6239 MD99452               | Notebook    | [f875a122f9](https://linux-hardware.org/?probe=f875a122f9) | Oct 29, 2020 |
| PC Special... | TF                          | Notebook    | [e651ccb88e](https://linux-hardware.org/?probe=e651ccb88e) | Oct 29, 2020 |
| HP            | ZBook 15 G2                 | Notebook    | [0b113f8315](https://linux-hardware.org/?probe=0b113f8315) | Oct 29, 2020 |
| PC Special... | TF                          | Notebook    | [ba278ca133](https://linux-hardware.org/?probe=ba278ca133) | Oct 29, 2020 |
| Apple         | Mac-F2238AC8                | All in one  | [e9e4822309](https://linux-hardware.org/?probe=e9e4822309) | Oct 28, 2020 |
| HP            | Laptop 14-bs0xx             | Notebook    | [0e16f54971](https://linux-hardware.org/?probe=0e16f54971) | Oct 28, 2020 |
| Toshiba       | Satellite C50-B             | Notebook    | [0edec7c57f](https://linux-hardware.org/?probe=0edec7c57f) | Oct 27, 2020 |
| Toshiba       | Satellite C50-B             | Notebook    | [21e26c80bc](https://linux-hardware.org/?probe=21e26c80bc) | Oct 27, 2020 |
| Dell          | Vostro 3700                 | Notebook    | [5493bcf45a](https://linux-hardware.org/?probe=5493bcf45a) | Oct 26, 2020 |
| ASUSTek       | E200HA                      | Notebook    | [2db5bc3b28](https://linux-hardware.org/?probe=2db5bc3b28) | Oct 23, 2020 |
| ASUSTek       | E200HA                      | Notebook    | [acc7a651ac](https://linux-hardware.org/?probe=acc7a651ac) | Oct 23, 2020 |
| TUXEDO        | InfinityBook Pro 15 v5      | Notebook    | [6aea9a482c](https://linux-hardware.org/?probe=6aea9a482c) | Oct 20, 2020 |
| HP            | 1497                        | Desktop     | [dea5079fad](https://linux-hardware.org/?probe=dea5079fad) | Oct 19, 2020 |
| Dell          | 0RY206                      | Desktop     | [4e0283b4c8](https://linux-hardware.org/?probe=4e0283b4c8) | Oct 18, 2020 |
| Dell          | 0RY206                      | Desktop     | [5d45dd253e](https://linux-hardware.org/?probe=5d45dd253e) | Oct 18, 2020 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [96ff229c4c](https://linux-hardware.org/?probe=96ff229c4c) | Oct 17, 2020 |
| HP            | 1497                        | Desktop     | [8dd5fc52bd](https://linux-hardware.org/?probe=8dd5fc52bd) | Oct 15, 2020 |
| Nvidia        | Tegra                       | Soc         | [9b157b83a5](https://linux-hardware.org/?probe=9b157b83a5) | Oct 15, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [bd7a8f0f96](https://linux-hardware.org/?probe=bd7a8f0f96) | Oct 15, 2020 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | Notebook    | [a0292a1315](https://linux-hardware.org/?probe=a0292a1315) | Oct 15, 2020 |
| Dell          | Dimension 5100              | Desktop     | [5b80714363](https://linux-hardware.org/?probe=5b80714363) | Oct 14, 2020 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [ab8c149b9f](https://linux-hardware.org/?probe=ab8c149b9f) | Oct 14, 2020 |
| Lenovo        | ThinkStation D20 415892G    | Desktop     | [08619ece44](https://linux-hardware.org/?probe=08619ece44) | Oct 14, 2020 |
| Apple         | MacBook5,1                  | Notebook    | [598a9af3a1](https://linux-hardware.org/?probe=598a9af3a1) | Oct 12, 2020 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [d245d1c5a5](https://linux-hardware.org/?probe=d245d1c5a5) | Oct 06, 2020 |
| Dell          | XPS 13 9360                 | Notebook    | [1554f3d77d](https://linux-hardware.org/?probe=1554f3d77d) | Oct 05, 2020 |
| HP            | 1495                        | Desktop     | [d1cf757d40](https://linux-hardware.org/?probe=d1cf757d40) | Oct 05, 2020 |
| HP            | 1495                        | Desktop     | [2389a49dc0](https://linux-hardware.org/?probe=2389a49dc0) | Oct 05, 2020 |
| Lenovo        | ThinkStation D20 415892G    | Desktop     | [1e8497692d](https://linux-hardware.org/?probe=1e8497692d) | Oct 02, 2020 |
| ASRock        | H97M Pro4                   | Desktop     | [c2148ec054](https://linux-hardware.org/?probe=c2148ec054) | Oct 01, 2020 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [c22330bac3](https://linux-hardware.org/?probe=c22330bac3) | Sep 26, 2020 |
| Toshiba       | Satellite L50-B             | Notebook    | [58ce88778b](https://linux-hardware.org/?probe=58ce88778b) | Sep 23, 2020 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [a2c5c1ea67](https://linux-hardware.org/?probe=a2c5c1ea67) | Sep 18, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [3eba500997](https://linux-hardware.org/?probe=3eba500997) | Sep 15, 2020 |
| HP            | G70                         | Notebook    | [198fd94bda](https://linux-hardware.org/?probe=198fd94bda) | Sep 13, 2020 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [20c0d6785b](https://linux-hardware.org/?probe=20c0d6785b) | Sep 11, 2020 |
| Dell          | 0Y958C A00                  | Desktop     | [253e97e06c](https://linux-hardware.org/?probe=253e97e06c) | Sep 10, 2020 |
| Apple         | MacBookPro12,1              | Notebook    | [daceea1b39](https://linux-hardware.org/?probe=daceea1b39) | Sep 08, 2020 |
| HP            | 255 G2                      | Notebook    | [5d06b6eeff](https://linux-hardware.org/?probe=5d06b6eeff) | Sep 04, 2020 |
| Lenovo        | U410                        | Notebook    | [ad05692bf0](https://linux-hardware.org/?probe=ad05692bf0) | Sep 02, 2020 |
| Unknown       | RS780-SB700 Unknox          | Desktop     | [a084e40027](https://linux-hardware.org/?probe=a084e40027) | Aug 30, 2020 |
| Gigabyte      | GA-MA790X-UD3P              | Desktop     | [f5a642ebbb](https://linux-hardware.org/?probe=f5a642ebbb) | Aug 28, 2020 |
| ASRock        | Z77 Extreme4                | Desktop     | [f710d270fe](https://linux-hardware.org/?probe=f710d270fe) | Aug 19, 2020 |
| Gigabyte      | G1.Sniper                   | Desktop     | [f25aa5934e](https://linux-hardware.org/?probe=f25aa5934e) | Aug 19, 2020 |
| Gigabyte      | G1.Sniper                   | Desktop     | [ebb3d9d7aa](https://linux-hardware.org/?probe=ebb3d9d7aa) | Aug 15, 2020 |
| Gigabyte      | G1.Sniper                   | Desktop     | [8d1bc7ce18](https://linux-hardware.org/?probe=8d1bc7ce18) | Aug 15, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [e1529e585d](https://linux-hardware.org/?probe=e1529e585d) | Aug 14, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [a20482ea67](https://linux-hardware.org/?probe=a20482ea67) | Aug 12, 2020 |
| ASUSTek       | ZN241IC                     | All in one  | [46c001d058](https://linux-hardware.org/?probe=46c001d058) | Aug 10, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [92a135b7d2](https://linux-hardware.org/?probe=92a135b7d2) | Aug 09, 2020 |
| HP            | Laptop 14-bs0xx             | Notebook    | [0eaa4ae12f](https://linux-hardware.org/?probe=0eaa4ae12f) | Aug 09, 2020 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [c3fbdc22c8](https://linux-hardware.org/?probe=c3fbdc22c8) | Aug 09, 2020 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [4a551e8c6b](https://linux-hardware.org/?probe=4a551e8c6b) | Aug 09, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [0c80b9688e](https://linux-hardware.org/?probe=0c80b9688e) | Aug 08, 2020 |
| Lenovo        | ThinkPad T430 2349G4G       | Notebook    | [db1ba375f2](https://linux-hardware.org/?probe=db1ba375f2) | Aug 08, 2020 |
| Dell          | 0T568R A00                  | Desktop     | [fb620a31fc](https://linux-hardware.org/?probe=fb620a31fc) | Aug 07, 2020 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [5101109869](https://linux-hardware.org/?probe=5101109869) | Aug 07, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [cb782efc58](https://linux-hardware.org/?probe=cb782efc58) | Aug 07, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [28a4ff7761](https://linux-hardware.org/?probe=28a4ff7761) | Aug 07, 2020 |
| Acer          | Aspire 5349                 | Notebook    | [fdae61b8d4](https://linux-hardware.org/?probe=fdae61b8d4) | Aug 07, 2020 |
| ASUSTek       | E200HA                      | Notebook    | [d702543fbb](https://linux-hardware.org/?probe=d702543fbb) | Aug 06, 2020 |
| HP            | 8648                        | Desktop     | [e034f483fc](https://linux-hardware.org/?probe=e034f483fc) | Aug 06, 2020 |
| Dell          | 0P4T42 A00                  | All in one  | [4924eefd27](https://linux-hardware.org/?probe=4924eefd27) | Aug 03, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [b5911c66d7](https://linux-hardware.org/?probe=b5911c66d7) | Aug 02, 2020 |
| Dell          | Latitude E7450              | Notebook    | [e0eee5c0fc](https://linux-hardware.org/?probe=e0eee5c0fc) | Aug 01, 2020 |
| Dell          | Latitude E7450              | Notebook    | [a8695dbee5](https://linux-hardware.org/?probe=a8695dbee5) | Aug 01, 2020 |
| PC Special... | N150CU                      | Notebook    | [6d19fc4569](https://linux-hardware.org/?probe=6d19fc4569) | Aug 01, 2020 |
| Lenovo        | ThinkPad T430 2349KB4       | Notebook    | [291151dae1](https://linux-hardware.org/?probe=291151dae1) | Jul 31, 2020 |
| Apple         | Mac-42FD25EABCABB274 iMa... | All in one  | [0e300aa2a8](https://linux-hardware.org/?probe=0e300aa2a8) | Jul 30, 2020 |
| MSI           | WS65 9TK                    | Notebook    | [e9feed814f](https://linux-hardware.org/?probe=e9feed814f) | Jul 29, 2020 |
| MSI           | WS65 9TK                    | Notebook    | [b296acb26a](https://linux-hardware.org/?probe=b296acb26a) | Jul 29, 2020 |
| HP            | Pavilion dm1                | Notebook    | [cc8ed632dc](https://linux-hardware.org/?probe=cc8ed632dc) | Jul 25, 2020 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [9b5d494924](https://linux-hardware.org/?probe=9b5d494924) | Jul 25, 2020 |
| Dell          | Latitude 5480               | Notebook    | [e06096d959](https://linux-hardware.org/?probe=e06096d959) | Jul 24, 2020 |
| Apple         | Mac-42FD25EABCABB274 iMa... | All in one  | [4615574555](https://linux-hardware.org/?probe=4615574555) | Jul 24, 2020 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [a8709e5362](https://linux-hardware.org/?probe=a8709e5362) | Jul 23, 2020 |
| Lenovo        | IdeaPad Y500 9541           | Notebook    | [bdf2ff973b](https://linux-hardware.org/?probe=bdf2ff973b) | Jul 20, 2020 |
| Dell          | Latitude 5400               | Notebook    | [11473792e0](https://linux-hardware.org/?probe=11473792e0) | Jul 19, 2020 |
| HP            | 8425                        | Desktop     | [25fd18c4f7](https://linux-hardware.org/?probe=25fd18c4f7) | Jul 19, 2020 |
| HP            | 255 G2                      | Notebook    | [6801725bae](https://linux-hardware.org/?probe=6801725bae) | Jul 17, 2020 |
| HP            | 255 G2                      | Notebook    | [7319f8f1b3](https://linux-hardware.org/?probe=7319f8f1b3) | Jul 17, 2020 |
| HP            | 255 G2                      | Notebook    | [d1dea15553](https://linux-hardware.org/?probe=d1dea15553) | Jul 16, 2020 |
| Lenovo        | G500 VIWGP                  | Notebook    | [37286d3145](https://linux-hardware.org/?probe=37286d3145) | Jul 08, 2020 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [f504426c40](https://linux-hardware.org/?probe=f504426c40) | Jul 04, 2020 |
| Lenovo        | ThinkCentre M91p 7052A9G    | Desktop     | [332ba4769f](https://linux-hardware.org/?probe=332ba4769f) | Jul 01, 2020 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [561adcd20d](https://linux-hardware.org/?probe=561adcd20d) | Jun 30, 2020 |
| Apple         | MacBookPro8,3               | Notebook    | [2a16561ffa](https://linux-hardware.org/?probe=2a16561ffa) | Jun 28, 2020 |
| Apple         | MacBookPro8,3               | Notebook    | [8ba0fcfe7c](https://linux-hardware.org/?probe=8ba0fcfe7c) | Jun 28, 2020 |
| Lenovo        | ThinkCentre M91p 7052A9G    | Desktop     | [0c0f90ba39](https://linux-hardware.org/?probe=0c0f90ba39) | Jun 27, 2020 |
| Intel         | NUC8BEB J72693-306          | Mini pc     | [124cdbcc52](https://linux-hardware.org/?probe=124cdbcc52) | Jun 27, 2020 |
| Lenovo        | ThinkCentre M91p 7052A9G    | Desktop     | [92adc3c517](https://linux-hardware.org/?probe=92adc3c517) | Jun 25, 2020 |
| MSI           | X570-A PRO                  | Desktop     | [60c99711b8](https://linux-hardware.org/?probe=60c99711b8) | Jun 23, 2020 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [a36f83366b](https://linux-hardware.org/?probe=a36f83366b) | Jun 21, 2020 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [d79300ba76](https://linux-hardware.org/?probe=d79300ba76) | Jun 18, 2020 |
| Dell          | Inspiron 15-3552            | Notebook    | [168dcc66c7](https://linux-hardware.org/?probe=168dcc66c7) | Jun 17, 2020 |
| Timi          | TM1703                      | Notebook    | [d3d89dc21d](https://linux-hardware.org/?probe=d3d89dc21d) | Jun 16, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3443C... | Notebook    | [1cfb078c4e](https://linux-hardware.org/?probe=1cfb078c4e) | Jun 13, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3443C... | Notebook    | [18230e354a](https://linux-hardware.org/?probe=18230e354a) | Jun 13, 2020 |
| MSI           | MEG X399 CREATION           | Desktop     | [89214de087](https://linux-hardware.org/?probe=89214de087) | Jun 12, 2020 |
| SLIMBOOK      | PROX15                      | Notebook    | [a4e6b0723d](https://linux-hardware.org/?probe=a4e6b0723d) | Jun 12, 2020 |
| ASUSTek       | G750JW                      | Notebook    | [cc02e1e15c](https://linux-hardware.org/?probe=cc02e1e15c) | Jun 10, 2020 |
| Lenovo        | ThinkCentre M58 7373BVU     | Desktop     | [5c40e26f41](https://linux-hardware.org/?probe=5c40e26f41) | Jun 09, 2020 |
| Dell          | Latitude E5420              | Notebook    | [eb3a4e918a](https://linux-hardware.org/?probe=eb3a4e918a) | Jun 08, 2020 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [a1615f709d](https://linux-hardware.org/?probe=a1615f709d) | Jun 07, 2020 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [7b570e8172](https://linux-hardware.org/?probe=7b570e8172) | Jun 01, 2020 |
| Lenovo        | ThinkPad X1 Carbon 34431... | Notebook    | [c5d45645b7](https://linux-hardware.org/?probe=c5d45645b7) | Jun 01, 2020 |
| Acer          | Aspire V3-571G              | Notebook    | [fbef0c90d4](https://linux-hardware.org/?probe=fbef0c90d4) | May 28, 2020 |
| Lenovo        | ThinkPad T410s 2904HDU      | Notebook    | [b1eb7716ed](https://linux-hardware.org/?probe=b1eb7716ed) | May 26, 2020 |
| Lenovo        | SDK0J40705 WIN 342504154... | Desktop     | [1538853c0c](https://linux-hardware.org/?probe=1538853c0c) | May 26, 2020 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [4a1413e289](https://linux-hardware.org/?probe=4a1413e289) | May 26, 2020 |
| HP            | Presario CQ61               | Notebook    | [28b3078708](https://linux-hardware.org/?probe=28b3078708) | May 25, 2020 |
| Lenovo        | ThinkPad P52 20MAS17205     | Notebook    | [4547e0d6fe](https://linux-hardware.org/?probe=4547e0d6fe) | May 25, 2020 |
| Chuwi         | LapBook SE                  | Notebook    | [c144d3a1bc](https://linux-hardware.org/?probe=c144d3a1bc) | May 24, 2020 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [206613fa48](https://linux-hardware.org/?probe=206613fa48) | May 22, 2020 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [6570cd4d9d](https://linux-hardware.org/?probe=6570cd4d9d) | May 22, 2020 |
| Lenovo        | SDK0J40705 WIN 342504154... | Desktop     | [cdcb59b3fb](https://linux-hardware.org/?probe=cdcb59b3fb) | May 22, 2020 |
| Packard Be... | P5N-E SLI                   | Desktop     | [495a29d64c](https://linux-hardware.org/?probe=495a29d64c) | May 22, 2020 |
| Packard Be... | P5N-E SLI                   | Desktop     | [1c2ca9c7de](https://linux-hardware.org/?probe=1c2ca9c7de) | May 22, 2020 |
| Dell          | Vostro 5490                 | Notebook    | [9000fa541e](https://linux-hardware.org/?probe=9000fa541e) | May 18, 2020 |
| Dell          | Latitude E5420              | Notebook    | [5519dbffbc](https://linux-hardware.org/?probe=5519dbffbc) | May 18, 2020 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [932b22c52a](https://linux-hardware.org/?probe=932b22c52a) | May 16, 2020 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [02b85cc578](https://linux-hardware.org/?probe=02b85cc578) | May 16, 2020 |
| Lenovo        | ThinkPad T520 424329U       | Notebook    | [bf1c52908b](https://linux-hardware.org/?probe=bf1c52908b) | May 16, 2020 |
| System76      | Galago Pro                  | Notebook    | [3ae6d02922](https://linux-hardware.org/?probe=3ae6d02922) | May 14, 2020 |
| ASRock        | H97M Pro4                   | Desktop     | [deca13654e](https://linux-hardware.org/?probe=deca13654e) | May 13, 2020 |
| Intel         | DQ57TM AAE92694-401         | Desktop     | [c2abb26814](https://linux-hardware.org/?probe=c2abb26814) | May 11, 2020 |
| HP            | EliteBook 8560w             | Notebook    | [f05f9404d0](https://linux-hardware.org/?probe=f05f9404d0) | May 11, 2020 |
| Gigabyte      | P15FV7                      | Notebook    | [a7031c2684](https://linux-hardware.org/?probe=a7031c2684) | May 09, 2020 |
| Fujitsu Si... | AMILO Pi 2530               | Notebook    | [702d00f33c](https://linux-hardware.org/?probe=702d00f33c) | May 07, 2020 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [db25140369](https://linux-hardware.org/?probe=db25140369) | May 06, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [6f82171699](https://linux-hardware.org/?probe=6f82171699) | May 06, 2020 |
| Sony UK       | Raspberry Pi 3 Model B      | Soc         | [52f0b7d3fa](https://linux-hardware.org/?probe=52f0b7d3fa) | May 06, 2020 |
| Dell          | Latitude E7240              | Notebook    | [6f9d4efc51](https://linux-hardware.org/?probe=6f9d4efc51) | May 06, 2020 |
| Dell          | Latitude E7240              | Notebook    | [9e5819a0bc](https://linux-hardware.org/?probe=9e5819a0bc) | May 06, 2020 |
| Acer          | Okinawa                     | Notebook    | [9e22849a3a](https://linux-hardware.org/?probe=9e22849a3a) | May 03, 2020 |
| Lenovo        | ThinkPad L380 20M50013UK    | Notebook    | [e356fece67](https://linux-hardware.org/?probe=e356fece67) | May 01, 2020 |
| Dell          | 0FH884                      | Desktop     | [1f7976ed89](https://linux-hardware.org/?probe=1f7976ed89) | Apr 30, 2020 |
| Dell          | 0200DY A03                  | Desktop     | [473467f488](https://linux-hardware.org/?probe=473467f488) | Apr 29, 2020 |
| Dell          | XPS M1530                   | Notebook    | [ef2ddf50e9](https://linux-hardware.org/?probe=ef2ddf50e9) | Apr 28, 2020 |
| Dell          | XPS M1530                   | Notebook    | [9d8053a9f5](https://linux-hardware.org/?probe=9d8053a9f5) | Apr 28, 2020 |
| Lenovo        | ThinkPad X260 20F5S13K00    | Notebook    | [e6010acabe](https://linux-hardware.org/?probe=e6010acabe) | Apr 28, 2020 |
| Dell          | Precision 7510              | Notebook    | [40e5c33fd8](https://linux-hardware.org/?probe=40e5c33fd8) | Apr 27, 2020 |
| Dell          | Latitude E5570              | Notebook    | [4c46b3c18d](https://linux-hardware.org/?probe=4c46b3c18d) | Apr 27, 2020 |
| Dell          | 0FH884                      | Desktop     | [306c5d73fb](https://linux-hardware.org/?probe=306c5d73fb) | Apr 27, 2020 |
| Dell          | 0FH884                      | Desktop     | [9fd393aab9](https://linux-hardware.org/?probe=9fd393aab9) | Apr 27, 2020 |
| Dell          | XPS 13 9300                 | Notebook    | [9b6c98e396](https://linux-hardware.org/?probe=9b6c98e396) | Apr 26, 2020 |
| Dell          | XPS 13 7390                 | Notebook    | [0d9716a2e8](https://linux-hardware.org/?probe=0d9716a2e8) | Apr 26, 2020 |
| ABIT          | KN9                         | Desktop     | [6254e80aba](https://linux-hardware.org/?probe=6254e80aba) | Apr 26, 2020 |
| Dell          | XPS 13 7390                 | Notebook    | [951197ee19](https://linux-hardware.org/?probe=951197ee19) | Apr 25, 2020 |
| Dell          | Inspiron 15-3552            | Notebook    | [64015bca38](https://linux-hardware.org/?probe=64015bca38) | Apr 24, 2020 |
| Acer          | Aspire 7741                 | Notebook    | [85a10d5a0c](https://linux-hardware.org/?probe=85a10d5a0c) | Apr 24, 2020 |
| Dell          | XPS M1530                   | Notebook    | [0d21d60816](https://linux-hardware.org/?probe=0d21d60816) | Apr 22, 2020 |
| HP            | Presario F500 (GH835EA#A... | Notebook    | [9e0244765a](https://linux-hardware.org/?probe=9e0244765a) | Apr 21, 2020 |
| Medion        | Erazer X7843 MD99945        | Notebook    | [f63ebecfac](https://linux-hardware.org/?probe=f63ebecfac) | Apr 20, 2020 |
| Medion        | Erazer X7843 MD99945        | Notebook    | [caa46f1899](https://linux-hardware.org/?probe=caa46f1899) | Apr 20, 2020 |
| ABIT          | KN9                         | Desktop     | [be7c3f4dc9](https://linux-hardware.org/?probe=be7c3f4dc9) | Apr 14, 2020 |
| Dell          | Latitude E5450              | Notebook    | [a0de4692f3](https://linux-hardware.org/?probe=a0de4692f3) | Apr 12, 2020 |
| Dell          | Latitude E5450              | Notebook    | [b934bac9f3](https://linux-hardware.org/?probe=b934bac9f3) | Apr 12, 2020 |
| Apple         | MacBook6,1                  | Notebook    | [7eae555356](https://linux-hardware.org/?probe=7eae555356) | Apr 11, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d882ce78cd](https://linux-hardware.org/?probe=d882ce78cd) | Apr 09, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [75cee4eeef](https://linux-hardware.org/?probe=75cee4eeef) | Apr 08, 2020 |
| eMachines     | E627                        | Notebook    | [395c0dace2](https://linux-hardware.org/?probe=395c0dace2) | Apr 07, 2020 |
| Dell          | XPS M1530                   | Notebook    | [daf947b1f0](https://linux-hardware.org/?probe=daf947b1f0) | Apr 07, 2020 |
| Lenovo        | ThinkStation D20 415892G    | Desktop     | [79ceb06042](https://linux-hardware.org/?probe=79ceb06042) | Apr 05, 2020 |
| HP            | Pavilion dv6                | Notebook    | [5ae586911d](https://linux-hardware.org/?probe=5ae586911d) | Apr 05, 2020 |
| ASUSTek       | Z87-K                       | Desktop     | [2ccf545fb8](https://linux-hardware.org/?probe=2ccf545fb8) | Apr 03, 2020 |
| Dell          | 0P301D A00                  | Desktop     | [5996aa0d7b](https://linux-hardware.org/?probe=5996aa0d7b) | Apr 02, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [4151ed01a0](https://linux-hardware.org/?probe=4151ed01a0) | Apr 01, 2020 |
| HP            | EliteBook 2560p             | Notebook    | [1b7dfeda09](https://linux-hardware.org/?probe=1b7dfeda09) | Mar 30, 2020 |
| HP            | EliteBook 2560p             | Notebook    | [c32ad7e810](https://linux-hardware.org/?probe=c32ad7e810) | Mar 30, 2020 |
| ASUSTek       | X550CC                      | Notebook    | [9d50122997](https://linux-hardware.org/?probe=9d50122997) | Mar 30, 2020 |
| Lenovo        | ThinkPad X260 20F5S13K00    | Notebook    | [b2b7dfbc87](https://linux-hardware.org/?probe=b2b7dfbc87) | Mar 29, 2020 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [ec4f08053a](https://linux-hardware.org/?probe=ec4f08053a) | Mar 23, 2020 |
| ASUSTek       | Z87-PRO                     | Desktop     | [cf7a7cb442](https://linux-hardware.org/?probe=cf7a7cb442) | Mar 21, 2020 |
| Dell          | Inspiron 13-5378            | Notebook    | [087223b15f](https://linux-hardware.org/?probe=087223b15f) | Mar 20, 2020 |
| Lenovo        | ThinkCentre A70 7844Q2G     | Desktop     | [7a3df56f82](https://linux-hardware.org/?probe=7a3df56f82) | Mar 20, 2020 |
| Dell          | Inspiron 13-5378            | Notebook    | [9225b58c75](https://linux-hardware.org/?probe=9225b58c75) | Mar 18, 2020 |
| HP            | EliteBook 840 G6            | Notebook    | [1287493f4e](https://linux-hardware.org/?probe=1287493f4e) | Mar 18, 2020 |
| Gigabyte      | F2A58M-DS2                  | Desktop     | [b5c9d31ae9](https://linux-hardware.org/?probe=b5c9d31ae9) | Mar 18, 2020 |
| HP            | EliteBook 840 G6            | Notebook    | [989982faa3](https://linux-hardware.org/?probe=989982faa3) | Mar 18, 2020 |
| Dell          | 0J3C2F A00                  | Desktop     | [3a37c7a548](https://linux-hardware.org/?probe=3a37c7a548) | Mar 11, 2020 |
| Lenovo        | ThinkStation D20 415892G    | Desktop     | [6672072cc5](https://linux-hardware.org/?probe=6672072cc5) | Mar 03, 2020 |
| ABIT          | KN9                         | Desktop     | [dafc30ae16](https://linux-hardware.org/?probe=dafc30ae16) | Mar 02, 2020 |
| ABIT          | KN9                         | Desktop     | [e26e7f08ca](https://linux-hardware.org/?probe=e26e7f08ca) | Feb 23, 2020 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [11d467ac47](https://linux-hardware.org/?probe=11d467ac47) | Feb 22, 2020 |
| ASUSTek       | P8Z68 DELUXE/GEN3           | Desktop     | [e53a35010c](https://linux-hardware.org/?probe=e53a35010c) | Feb 22, 2020 |
| Dell          | Precision M6300             | Notebook    | [6e9681a74e](https://linux-hardware.org/?probe=6e9681a74e) | Feb 18, 2020 |
| Dell          | Precision M6300             | Notebook    | [e45c0c7fc9](https://linux-hardware.org/?probe=e45c0c7fc9) | Feb 18, 2020 |
| Dell          | Inspiron 13-5378            | Notebook    | [46dd15e54f](https://linux-hardware.org/?probe=46dd15e54f) | Feb 18, 2020 |
| Lenovo        | ThinkPad X250 20CLS3ST01    | Notebook    | [b7a710c050](https://linux-hardware.org/?probe=b7a710c050) | Feb 10, 2020 |
| Lenovo        | ThinkPad L380 20M50013UK    | Notebook    | [e5b58a2f40](https://linux-hardware.org/?probe=e5b58a2f40) | Feb 08, 2020 |
| ASUSTek       | E402BA                      | Notebook    | [ef0178479b](https://linux-hardware.org/?probe=ef0178479b) | Feb 08, 2020 |
| Lenovo        | ThinkPad X250 20CLS3ST01    | Notebook    | [51d20a3d12](https://linux-hardware.org/?probe=51d20a3d12) | Feb 06, 2020 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [917f6c18a4](https://linux-hardware.org/?probe=917f6c18a4) | Feb 05, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [ec722fbbfe](https://linux-hardware.org/?probe=ec722fbbfe) | Feb 01, 2020 |
| HP            | 1998                        | Desktop     | [edb9bba986](https://linux-hardware.org/?probe=edb9bba986) | Jan 19, 2020 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [8143d2c859](https://linux-hardware.org/?probe=8143d2c859) | Dec 23, 2019 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [efc1ac12c7](https://linux-hardware.org/?probe=efc1ac12c7) | Dec 21, 2019 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [0f6f830f1b](https://linux-hardware.org/?probe=0f6f830f1b) | Dec 21, 2019 |
| Acer          | Aspire 8930                 | Notebook    | [3bd04b5cd7](https://linux-hardware.org/?probe=3bd04b5cd7) | Dec 09, 2019 |
| Lenovo        | ThinkPad T410 2539W4Y       | Notebook    | [009c5c142e](https://linux-hardware.org/?probe=009c5c142e) | Dec 06, 2019 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [0c3d1fcefe](https://linux-hardware.org/?probe=0c3d1fcefe) | Dec 05, 2019 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | Notebook    | [706aee4776](https://linux-hardware.org/?probe=706aee4776) | Dec 04, 2019 |
| Apple         | MacBookPro5,2               | Notebook    | [3b3fd20d67](https://linux-hardware.org/?probe=3b3fd20d67) | Dec 01, 2019 |
| Apple         | MacBookPro5,2               | Notebook    | [4918587a5c](https://linux-hardware.org/?probe=4918587a5c) | Dec 01, 2019 |
| Apple         | MacBookPro5,2               | Notebook    | [0ef52aaec2](https://linux-hardware.org/?probe=0ef52aaec2) | Dec 01, 2019 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [187a7265f0](https://linux-hardware.org/?probe=187a7265f0) | Dec 01, 2019 |
| MSI           | Z77 MPower                  | Desktop     | [ab7afebfb6](https://linux-hardware.org/?probe=ab7afebfb6) | Nov 26, 2019 |
| MSI           | Z77 MPower                  | Desktop     | [77c87b6b71](https://linux-hardware.org/?probe=77c87b6b71) | Nov 26, 2019 |
| System76      | Galago Pro                  | Notebook    | [15393d43e8](https://linux-hardware.org/?probe=15393d43e8) | Nov 25, 2019 |
| Dell          | Latitude 7490               | Notebook    | [4c5f40f7f3](https://linux-hardware.org/?probe=4c5f40f7f3) | Oct 18, 2019 |
| System76      | Galago Pro                  | Notebook    | [463dd28c7d](https://linux-hardware.org/?probe=463dd28c7d) | Oct 17, 2019 |
| Acer          | Aspire 5736Z                | Notebook    | [5ba5b7d13a](https://linux-hardware.org/?probe=5ba5b7d13a) | Oct 17, 2019 |
| Lenovo        | IdeaPad 310-15ABR 80ST      | Notebook    | [a2da44ce3d](https://linux-hardware.org/?probe=a2da44ce3d) | Oct 15, 2019 |
| Alienware     | 17 R4                       | Notebook    | [fa39f4bdb4](https://linux-hardware.org/?probe=fa39f4bdb4) | Oct 04, 2019 |
| Lenovo        | IdeaPad Y700-15ACZ 80NY     | Notebook    | [b17cca251b](https://linux-hardware.org/?probe=b17cca251b) | Sep 30, 2019 |
| System76      | Galago Pro                  | Notebook    | [8122dc5996](https://linux-hardware.org/?probe=8122dc5996) | Sep 25, 2019 |
| Seco          | C40 C                       | Desktop     | [a3f6f85e6a](https://linux-hardware.org/?probe=a3f6f85e6a) | Sep 15, 2019 |
| Alienware     | 17 R4                       | Notebook    | [5287c00902](https://linux-hardware.org/?probe=5287c00902) | Sep 15, 2019 |
| System76      | Galago Pro                  | Notebook    | [7c1dbad22c](https://linux-hardware.org/?probe=7c1dbad22c) | Sep 11, 2019 |
| Acer          | Aspire ES1-512              | Notebook    | [6b82a86df6](https://linux-hardware.org/?probe=6b82a86df6) | Sep 08, 2019 |
| Seco          | C40 C                       | Desktop     | [16208d3700](https://linux-hardware.org/?probe=16208d3700) | Sep 04, 2019 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [e5fc9849a0](https://linux-hardware.org/?probe=e5fc9849a0) | Aug 30, 2019 |
| Seco          | C40 C                       | Desktop     | [3a7afd413f](https://linux-hardware.org/?probe=3a7afd413f) | Aug 28, 2019 |
| Acer          | Aspire ES1-512              | Notebook    | [11727f9491](https://linux-hardware.org/?probe=11727f9491) | Aug 19, 2019 |
| Acer          | Aspire ES1-512              | Notebook    | [6a08c4afd1](https://linux-hardware.org/?probe=6a08c4afd1) | Aug 17, 2019 |
| Toshiba       | Satellite L500              | Notebook    | [5819f81be3](https://linux-hardware.org/?probe=5819f81be3) | Aug 16, 2019 |
| ASUSTek       | K5130                       | Desktop     | [72b7a5b445](https://linux-hardware.org/?probe=72b7a5b445) | Aug 08, 2019 |
| Acer          | Aspire E1-572               | Notebook    | [96bf232f30](https://linux-hardware.org/?probe=96bf232f30) | Aug 03, 2019 |
| DFI           | INF P35                     | Desktop     | [7987560cdc](https://linux-hardware.org/?probe=7987560cdc) | Aug 02, 2019 |
| DFI           | INF P35                     | Desktop     | [0379ced795](https://linux-hardware.org/?probe=0379ced795) | Aug 02, 2019 |
| MiTAC         | PD14TI AAPD14TI-101         | Desktop     | [b7db1f6d08](https://linux-hardware.org/?probe=b7db1f6d08) | Jul 27, 2019 |
| MiTAC         | PD14TI AAPD14TI-101         | Desktop     | [bf4c96625e](https://linux-hardware.org/?probe=bf4c96625e) | Jul 27, 2019 |
| Advent        | Roma                        | Notebook    | [a7ec10f5ee](https://linux-hardware.org/?probe=a7ec10f5ee) | Jul 21, 2019 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [649ff143ad](https://linux-hardware.org/?probe=649ff143ad) | Jul 08, 2019 |
| System76      | Bonobo Extreme              | Notebook    | [aa49d07bb2](https://linux-hardware.org/?probe=aa49d07bb2) | Jul 05, 2019 |
| System76      | Bonobo Extreme              | Notebook    | [f867ec3a39](https://linux-hardware.org/?probe=f867ec3a39) | Jul 05, 2019 |
| Toshiba       | TECRA R850                  | Notebook    | [4398e73607](https://linux-hardware.org/?probe=4398e73607) | Jul 04, 2019 |
| ASUSTek       | F2A55-M LK2                 | Desktop     | [93d8ad05a1](https://linux-hardware.org/?probe=93d8ad05a1) | Jun 30, 2019 |
| AMI           | Aptio CRB                   | Mini pc     | [8f87769d12](https://linux-hardware.org/?probe=8f87769d12) | Jun 19, 2019 |
| HP            | Pavilion dv6                | Notebook    | [6cfff2060e](https://linux-hardware.org/?probe=6cfff2060e) | Jun 16, 2019 |
| HP            | Pavilion dv6                | Notebook    | [90df3b230e](https://linux-hardware.org/?probe=90df3b230e) | Jun 16, 2019 |
| HP            | Pavilion dv6                | Notebook    | [694239801c](https://linux-hardware.org/?probe=694239801c) | Jun 16, 2019 |
| Shuttle       | XS35V3                      | Desktop     | [de0cc0ab6f](https://linux-hardware.org/?probe=de0cc0ab6f) | Jun 16, 2019 |
| Toshiba       | Satellite L500              | Notebook    | [7fcd49c923](https://linux-hardware.org/?probe=7fcd49c923) | Jun 08, 2019 |
| Dell          | 0FJ030                      | Desktop     | [c3dfb2bea5](https://linux-hardware.org/?probe=c3dfb2bea5) | Jun 05, 2019 |
| Lenovo        | MAHOBAY                     | Desktop     | [71dd964fb5](https://linux-hardware.org/?probe=71dd964fb5) | Jun 04, 2019 |
| ASUSTek       | S550CA                      | Notebook    | [469e04e0d5](https://linux-hardware.org/?probe=469e04e0d5) | May 26, 2019 |
| ASRock        | G31M-S                      | Desktop     | [213f2f20b6](https://linux-hardware.org/?probe=213f2f20b6) | May 24, 2019 |
| Dell          | 0Y2MRG A00                  | Desktop     | [f32755062c](https://linux-hardware.org/?probe=f32755062c) | May 23, 2019 |
| Lenovo        | ThinkPad T420 4236RN1       | Notebook    | [a151a65fee](https://linux-hardware.org/?probe=a151a65fee) | May 21, 2019 |
| Lenovo        | ThinkPad T420 4236RN1       | Notebook    | [ba564750a2](https://linux-hardware.org/?probe=ba564750a2) | May 21, 2019 |
| ASUSTek       | K53U                        | Notebook    | [24a0045ecc](https://linux-hardware.org/?probe=24a0045ecc) | May 18, 2019 |
| ASUSTek       | K53U                        | Notebook    | [0f7bf61a9d](https://linux-hardware.org/?probe=0f7bf61a9d) | May 17, 2019 |
| Dell          | 03NVJ6 A02                  | Desktop     | [915e0bab53](https://linux-hardware.org/?probe=915e0bab53) | May 12, 2019 |
| ASUSTek       | S550CA                      | Notebook    | [afe6d9bfe2](https://linux-hardware.org/?probe=afe6d9bfe2) | Apr 28, 2019 |
| ASUSTek       | T100TA                      | Notebook    | [5025b4af94](https://linux-hardware.org/?probe=5025b4af94) | Apr 26, 2019 |
| Lenovo        | ThinkPad T440 20B7S1G40L    | Notebook    | [47b05c165f](https://linux-hardware.org/?probe=47b05c165f) | Apr 24, 2019 |
| Toshiba       | Satellite L50-C             | Notebook    | [ffca1399e5](https://linux-hardware.org/?probe=ffca1399e5) | Apr 17, 2019 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [b0dcc92563](https://linux-hardware.org/?probe=b0dcc92563) | Apr 03, 2019 |
| Dell          | Inspiron ME051              | Notebook    | [6d096d9aa6](https://linux-hardware.org/?probe=6d096d9aa6) | Mar 30, 2019 |
| Dell          | Inspiron ME051              | Notebook    | [a41940bc7f](https://linux-hardware.org/?probe=a41940bc7f) | Mar 30, 2019 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [6bae84797a](https://linux-hardware.org/?probe=6bae84797a) | Mar 22, 2019 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [9e86bfbcc2](https://linux-hardware.org/?probe=9e86bfbcc2) | Mar 22, 2019 |
| Shuttle       | FS35V4                      | Desktop     | [03af7dbe17](https://linux-hardware.org/?probe=03af7dbe17) | Mar 20, 2019 |
| Dell          | 0P7V82 A00                  | All in one  | [2bf103dd36](https://linux-hardware.org/?probe=2bf103dd36) | Feb 23, 2019 |
| Dell          | 0P7V82 A00                  | All in one  | [2907768caa](https://linux-hardware.org/?probe=2907768caa) | Feb 23, 2019 |
| Dell          | 0CRH6C A00                  | Desktop     | [300a99b1d0](https://linux-hardware.org/?probe=300a99b1d0) | Feb 10, 2019 |
| eMachines     | eM350                       | Notebook    | [e42feb9612](https://linux-hardware.org/?probe=e42feb9612) | Feb 06, 2019 |
| eMachines     | eM350                       | Notebook    | [f19d2e4452](https://linux-hardware.org/?probe=f19d2e4452) | Feb 06, 2019 |
| Dell          | Latitude E6400              | Notebook    | [75df21c3fd](https://linux-hardware.org/?probe=75df21c3fd) | Jan 25, 2019 |
| Shuttle       | XS35V3                      | Desktop     | [ae76390fb4](https://linux-hardware.org/?probe=ae76390fb4) | Jan 18, 2019 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [1cfe678b48](https://linux-hardware.org/?probe=1cfe678b48) | Jan 16, 2019 |
| Toshiba       | Satellite Pro C660          | Notebook    | [9b641633c5](https://linux-hardware.org/?probe=9b641633c5) | Nov 17, 2018 |
| Acer          | Swift SF114-31              | Notebook    | [96142e3044](https://linux-hardware.org/?probe=96142e3044) | Nov 01, 2018 |
| ASRock        | X370 Gaming-ITX/ac          | Desktop     | [2311962133](https://linux-hardware.org/?probe=2311962133) | Sep 30, 2018 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [6a91010c14](https://linux-hardware.org/?probe=6a91010c14) | Jul 07, 2018 |
| ASUSTek       | T102HA                      | Tablet      | [7c47ab2fd4](https://linux-hardware.org/?probe=7c47ab2fd4) | Jun 14, 2018 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [e5e3ed1c7c](https://linux-hardware.org/?probe=e5e3ed1c7c) | Jun 01, 2018 |
| Dell          | Latitude E6230              | Notebook    | [889c4720de](https://linux-hardware.org/?probe=889c4720de) | Mar 31, 2018 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [1d52b52b65](https://linux-hardware.org/?probe=1d52b52b65) | Feb 28, 2018 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [1b14483855](https://linux-hardware.org/?probe=1b14483855) | Feb 23, 2018 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [bbe4f7f994](https://linux-hardware.org/?probe=bbe4f7f994) | Feb 11, 2018 |
| Acer          | Aspire E5-575G              | Notebook    | [5d4b293327](https://linux-hardware.org/?probe=5d4b293327) | Feb 07, 2018 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [b32d7f9bc2](https://linux-hardware.org/?probe=b32d7f9bc2) | Jan 12, 2018 |
| Dell          | Latitude E6230              | Notebook    | [70a07251da](https://linux-hardware.org/?probe=70a07251da) | Oct 21, 2017 |
| Dell          | Latitude D620               | Notebook    | [6652d3973b](https://linux-hardware.org/?probe=6652d3973b) | Sep 28, 2017 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [7cf734ce05](https://linux-hardware.org/?probe=7cf734ce05) | Nov 04, 2016 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Ireland/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 80        | 15.87%  |
| Ubuntu 18.04       | 44        | 8.73%   |
| Debian 11          | 16        | 3.17%   |
| OpenMandriva 4.2   | 12        | 2.38%   |
| Manjaro            | 11        | 2.18%   |
| ArcoLinux Rolling  | 11        | 2.18%   |
| Arch               | 11        | 2.18%   |
| Ubuntu 22.04       | 10        | 1.98%   |
| Debian 10          | 10        | 1.98%   |
| Ubuntu 19.04       | 9         | 1.79%   |
| Pop!_OS 22.04      | 9         | 1.79%   |
| Pop!_OS 21.10      | 9         | 1.79%   |
| Linux Mint 20.2    | 9         | 1.79%   |
| Linux Mint 20      | 9         | 1.79%   |
| Pop!_OS 20.10      | 8         | 1.59%   |
| Fedora 36          | 8         | 1.59%   |
| Arch Rolling       | 8         | 1.59%   |
| Zorin 16           | 7         | 1.39%   |
| Pop!_OS 20.04      | 7         | 1.39%   |
| KDE neon 20.04     | 7         | 1.39%   |
| BlackPanther 18.1  | 7         | 1.39%   |
| Ubuntu 19.10       | 6         | 1.19%   |
| Linux Mint 20.3    | 6         | 1.19%   |
| Ubuntu 21.10       | 5         | 0.99%   |
| ROSA R11           | 5         | 0.99%   |
| ROSA R10           | 5         | 0.99%   |
| OpenMandriva 4.3   | 5         | 0.99%   |
| Lubuntu 20.04      | 5         | 0.99%   |
| Linux Mint 20.1    | 5         | 0.99%   |
| Linux Mint 19.3    | 5         | 0.99%   |
| Fedora 35          | 5         | 0.99%   |
| Fedora 33          | 5         | 0.99%   |
| Fedora 32          | 5         | 0.99%   |
| Zorin 15           | 4         | 0.79%   |
| Ubuntu 20.10       | 4         | 0.79%   |
| Fedora 34          | 4         | 0.79%   |
| Debian Unstable    | 4         | 0.79%   |
| Ubuntu Unity 18.04 | 3         | 0.6%    |
| Pop!_OS 21.04      | 3         | 0.6%    |
| OpenMandriva 4.50  | 3         | 0.6%    |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 159       | 33.26%  |
| Linux Mint    | 44        | 9.21%   |
| Pop!_OS       | 34        | 7.11%   |
| Debian        | 32        | 6.69%   |
| Fedora        | 26        | 5.44%   |
| Manjaro       | 24        | 5.02%   |
| OpenMandriva  | 20        | 4.18%   |
| Arch          | 19        | 3.97%   |
| ROSA          | 12        | 2.51%   |
| Kubuntu       | 12        | 2.51%   |
| Zorin         | 11        | 2.3%    |
| ArcoLinux     | 11        | 2.3%    |
| KDE neon      | 8         | 1.67%   |
| Elementary    | 8         | 1.67%   |
| Lubuntu       | 7         | 1.46%   |
| BlackPanther  | 7         | 1.46%   |
| Ubuntu Unity  | 5         | 1.05%   |
| Endless       | 5         | 1.05%   |
| openSUSE      | 4         | 0.84%   |
| Xubuntu       | 3         | 0.63%   |
| Ubuntu Budgie | 3         | 0.63%   |
| Gentoo        | 3         | 0.63%   |
| Clear Linux   | 3         | 0.63%   |
| Ubuntu MATE   | 2         | 0.42%   |
| Peppermint    | 2         | 0.42%   |
| LMDE          | 2         | 0.42%   |
| Kali          | 2         | 0.42%   |
| CentOS        | 2         | 0.42%   |
| Trisquel      | 1         | 0.21%   |
| SteamOS       | 1         | 0.21%   |
| Solus         | 1         | 0.21%   |
| RHEL          | 1         | 0.21%   |
| MX            | 1         | 0.21%   |
| Linux Lite    | 1         | 0.21%   |
| Feren OS      | 1         | 0.21%   |
| Chrome OS     | 1         | 0.21%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 15        | 2.71%   |
| 5.10.14-desktop-1omv4002 | 12        | 2.17%   |
| 5.3.0-46-generic         | 10        | 1.81%   |
| 5.15.0-46-generic        | 8         | 1.44%   |
| 5.4.0-52-generic         | 6         | 1.08%   |
| 4.18.16-desktop-1bP      | 6         | 1.08%   |
| 5.4.0-91-generic         | 5         | 0.9%    |
| 5.4.0-48-generic         | 5         | 0.9%    |
| 5.16.7-desktop-1omv4003  | 5         | 0.9%    |
| 5.11.0-27-generic        | 5         | 0.9%    |
| 5.8.0-7630-generic       | 4         | 0.72%   |
| 5.8.0-43-generic         | 4         | 0.72%   |
| 5.4.0-72-generic         | 4         | 0.72%   |
| 5.4.0-47-generic         | 4         | 0.72%   |
| 5.4.0-31-generic         | 4         | 0.72%   |
| 5.4.0-29-generic         | 4         | 0.72%   |
| 5.4.0-26-generic         | 4         | 0.72%   |
| 5.3.0-28-generic         | 4         | 0.72%   |
| 5.15.0-52-generic        | 4         | 0.72%   |
| 5.15.0-48-generic        | 4         | 0.72%   |
| 4.18.0-15-generic        | 4         | 0.72%   |
| 5.8.0-53-generic         | 3         | 0.54%   |
| 5.8.0-41-generic         | 3         | 0.54%   |
| 5.4.0-77-generic         | 3         | 0.54%   |
| 5.4.0-7634-generic       | 3         | 0.54%   |
| 5.4.0-58-generic         | 3         | 0.54%   |
| 5.4.0-54-generic         | 3         | 0.54%   |
| 5.4.0-40-generic         | 3         | 0.54%   |
| 5.4.0-39-generic         | 3         | 0.54%   |
| 5.4.0-37-generic         | 3         | 0.54%   |
| 5.3.0-45-generic         | 3         | 0.54%   |
| 5.3.0-40-generic         | 3         | 0.54%   |
| 5.19.0-76051900-generic  | 3         | 0.54%   |
| 5.17.5-arch1-1           | 3         | 0.54%   |
| 5.17.5-76051705-generic  | 3         | 0.54%   |
| 5.16.15-76051615-generic | 3         | 0.54%   |
| 5.15.11-76051511-generic | 3         | 0.54%   |
| 5.15.0-40-generic        | 3         | 0.54%   |
| 5.12.4-desktop-1omv4050  | 3         | 0.54%   |
| 5.11.0-43-generic        | 3         | 0.54%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 109       | 21%     |
| 4.15.0  | 36        | 6.94%   |
| 5.8.0   | 28        | 5.39%   |
| 5.11.0  | 27        | 5.2%    |
| 5.3.0   | 26        | 5.01%   |
| 5.15.0  | 26        | 5.01%   |
| 5.10.0  | 17        | 3.28%   |
| 5.13.0  | 15        | 2.89%   |
| 5.0.0   | 15        | 2.89%   |
| 5.10.14 | 12        | 2.31%   |
| 4.19.0  | 11        | 2.12%   |
| 4.18.0  | 11        | 2.12%   |
| 5.17.5  | 8         | 1.54%   |
| 4.18.16 | 6         | 1.16%   |
| 5.16.7  | 5         | 0.96%   |
| 5.16.11 | 4         | 0.77%   |
| 4.9.60  | 4         | 0.77%   |
| 5.8.14  | 3         | 0.58%   |
| 5.6.0   | 3         | 0.58%   |
| 5.19.0  | 3         | 0.58%   |
| 5.18.0  | 3         | 0.58%   |
| 5.16.15 | 3         | 0.58%   |
| 5.15.12 | 3         | 0.58%   |
| 5.15.11 | 3         | 0.58%   |
| 5.12.4  | 3         | 0.58%   |
| 4.9.155 | 3         | 0.58%   |
| 4.10.0  | 3         | 0.58%   |
| 5.7.9   | 2         | 0.39%   |
| 5.7.12  | 2         | 0.39%   |
| 5.6.7   | 2         | 0.39%   |
| 5.6.15  | 2         | 0.39%   |
| 5.19.1  | 2         | 0.39%   |
| 5.18.17 | 2         | 0.39%   |
| 5.18.10 | 2         | 0.39%   |
| 5.17.6  | 2         | 0.39%   |
| 5.15.7  | 2         | 0.39%   |
| 5.15.6  | 2         | 0.39%   |
| 5.15.5  | 2         | 0.39%   |
| 5.13.19 | 2         | 0.39%   |
| 5.13.13 | 2         | 0.39%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 114       | 22.44%  |
| 5.15    | 42        | 8.27%   |
| 5.10    | 42        | 8.27%   |
| 4.15    | 36        | 7.09%   |
| 5.8     | 35        | 6.89%   |
| 5.11    | 33        | 6.5%    |
| 5.3     | 27        | 5.31%   |
| 5.13    | 21        | 4.13%   |
| 4.18    | 17        | 3.35%   |
| 5.17    | 15        | 2.95%   |
| 5.0     | 15        | 2.95%   |
| 5.16    | 14        | 2.76%   |
| 4.19    | 12        | 2.36%   |
| 4.9     | 11        | 2.17%   |
| 5.6     | 10        | 1.97%   |
| 5.19    | 10        | 1.97%   |
| 5.18    | 10        | 1.97%   |
| 5.12    | 9         | 1.77%   |
| 5.7     | 7         | 1.38%   |
| 5.9     | 5         | 0.98%   |
| 5.14    | 5         | 0.98%   |
| 4.10    | 3         | 0.59%   |
| 6.0     | 2         | 0.39%   |
| 4.4     | 2         | 0.39%   |
| 4.13    | 2         | 0.39%   |
| 4.12    | 2         | 0.39%   |
| 3.10    | 2         | 0.39%   |
| 5.5     | 1         | 0.2%    |
| 5.2     | 1         | 0.2%    |
| 5       | 1         | 0.2%    |
| 4.14    | 1         | 0.2%    |
| 4.1     | 1         | 0.2%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 439       | 95.23%  |
| i686    | 15        | 3.25%   |
| aarch64 | 7         | 1.52%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 208       | 42.71%  |
| KDE5            | 73        | 14.99%  |
| Unknown         | 69        | 14.17%  |
| XFCE            | 31        | 6.37%   |
| X-Cinnamon      | 28        | 5.75%   |
| KDE             | 18        | 3.7%    |
| MATE            | 11        | 2.26%   |
| LXQt            | 8         | 1.64%   |
| Cinnamon        | 8         | 1.64%   |
| Pantheon        | 7         | 1.44%   |
| KDE4            | 6         | 1.23%   |
| Unity           | 5         | 1.03%   |
| i3              | 4         | 0.82%   |
| GNOME Flashback | 3         | 0.62%   |
| Budgie          | 3         | 0.62%   |
| GNOME Classic   | 2         | 0.41%   |
| LXDE            | 1         | 0.21%   |
| LeftWM          | 1         | 0.21%   |
| Enlightenment   | 1         | 0.21%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 379       | 80.81%  |
| Wayland | 43        | 9.17%   |
| Unknown | 39        | 8.32%   |
| Tty     | 8         | 1.71%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 263       | 55.25%  |
| SDDM    | 70        | 14.71%  |
| GDM     | 61        | 12.82%  |
| LightDM | 32        | 6.72%   |
| GDM3    | 23        | 4.83%   |
| TDM     | 19        | 3.99%   |
| KDM     | 6         | 1.26%   |
| LXDM    | 2         | 0.42%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_IE   | 227       | 47.59%  |
| en_US   | 79        | 16.56%  |
| en_GB   | 72        | 15.09%  |
| Unknown | 66        | 13.84%  |
| pl_PL   | 11        | 2.31%   |
| es_ES   | 3         | 0.63%   |
| C       | 3         | 0.63%   |
| en_CA   | 2         | 0.42%   |
| bg_BG   | 2         | 0.42%   |
| zh_CN   | 1         | 0.21%   |
| ru_RU   | 1         | 0.21%   |
| pt_PT   | 1         | 0.21%   |
| pt_BR   | 1         | 0.21%   |
| it_IT   | 1         | 0.21%   |
| ga_IE   | 1         | 0.21%   |
| fr_FR   | 1         | 0.21%   |
| fr_BE   | 1         | 0.21%   |
| en_ZA   | 1         | 0.21%   |
| en_IN   | 1         | 0.21%   |
| en_DE   | 1         | 0.21%   |
| de_DE   | 1         | 0.21%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 250       | 53.42%  |
| EFI  | 218       | 46.58%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type                | Computers | Percent |
|---------------------|-----------|---------|
| Ext4                | 367       | 78.92%  |
| Overlay             | 32        | 6.88%   |
| Btrfs               | 31        | 6.67%   |
| Unknown             | 23        | 4.95%   |
| Xfs                 | 6         | 1.29%   |
| Zfs                 | 4         | 0.86%   |
| Fuse.fuse-overlayfs | 1         | 0.22%   |
| F2fs                | 1         | 0.22%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 271       | 57.42%  |
| GPT     | 150       | 31.78%  |
| MBR     | 51        | 10.81%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 397       | 85.01%  |
| Yes       | 70        | 14.99%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 345       | 73.72%  |
| Yes       | 123       | 26.28%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 92        | 20.04%  |
| Lenovo                  | 80        | 17.43%  |
| ASUSTek Computer        | 58        | 12.64%  |
| Hewlett-Packard         | 51        | 11.11%  |
| Gigabyte Technology     | 23        | 5.01%   |
| MSI                     | 19        | 4.14%   |
| Apple                   | 19        | 4.14%   |
| Acer                    | 19        | 4.14%   |
| ASRock                  | 12        | 2.61%   |
| Toshiba                 | 10        | 2.18%   |
| Samsung Electronics     | 6         | 1.31%   |
| Intel                   | 6         | 1.31%   |
| Medion                  | 5         | 1.09%   |
| TUXEDO                  | 4         | 0.87%   |
| PC Specialist           | 4         | 0.87%   |
| Foxconn                 | 4         | 0.87%   |
| Timi                    | 3         | 0.65%   |
| Notebook                | 3         | 0.65%   |
| System76                | 2         | 0.44%   |
| Shuttle                 | 2         | 0.44%   |
| Seco                    | 2         | 0.44%   |
| Raspberry Pi Foundation | 2         | 0.44%   |
| Packard Bell            | 2         | 0.44%   |
| Nvidia                  | 2         | 0.44%   |
| HUAWEI                  | 2         | 0.44%   |
| Fujitsu Siemens         | 2         | 0.44%   |
| Entroware               | 2         | 0.44%   |
| eMachines               | 2         | 0.44%   |
| Chuwi                   | 2         | 0.44%   |
| Sony UK                 | 1         | 0.22%   |
| Sony                    | 1         | 0.22%   |
| SLIMBOOK                | 1         | 0.22%   |
| Schenker                | 1         | 0.22%   |
| Rockchip                | 1         | 0.22%   |
| Pine Microsystems       | 1         | 0.22%   |
| Pegatron                | 1         | 0.22%   |
| MiTAC                   | 1         | 0.22%   |
| Microtech               | 1         | 0.22%   |
| Jumper                  | 1         | 0.22%   |
| IP3 Tech                | 1         | 0.22%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| Dell OptiPlex 7010                | 6         | 1.31%   |
| ASUS All Series                   | 6         | 1.31%   |
| Gigabyte B450M DS3H               | 4         | 0.87%   |
| Lenovo V145-15AST 81MT            | 3         | 0.65%   |
| HP Compaq 8200 Elite SFF PC       | 3         | 0.65%   |
| Dell OptiPlex 790                 | 3         | 0.65%   |
| ASUS ROG STRIX B450-F GAMING      | 3         | 0.65%   |
| TUXEDO Pulse 15 Gen1              | 2         | 0.44%   |
| Seco C40                          | 2         | 0.44%   |
| RPi Raspberry Pi                  | 2         | 0.44%   |
| Nvidia Tegra                      | 2         | 0.44%   |
| MSI MS-7B79                       | 2         | 0.44%   |
| Lenovo ThinkStation D20 415892G   | 2         | 0.44%   |
| Lenovo ThinkPad X1 Carbon 3443CTO | 2         | 0.44%   |
| Lenovo IdeaPad 510-15ISK 80SR     | 2         | 0.44%   |
| HP Pavilion g6                    | 2         | 0.44%   |
| HP Notebook                       | 2         | 0.44%   |
| HP EliteDesk 800 G1 SFF           | 2         | 0.44%   |
| Gigabyte X570 AORUS ULTRA         | 2         | 0.44%   |
| Foxconn Pro 3500 Series           | 2         | 0.44%   |
| Dell XPS 9320                     | 2         | 0.44%   |
| Dell XPS 13 9310                  | 2         | 0.44%   |
| Dell XPS 13 9300                  | 2         | 0.44%   |
| Dell XPS 13 7390                  | 2         | 0.44%   |
| Dell Precision 5550               | 2         | 0.44%   |
| Dell OptiPlex 780                 | 2         | 0.44%   |
| Dell OptiPlex 7020                | 2         | 0.44%   |
| Dell Latitude E6230               | 2         | 0.44%   |
| Dell Inspiron 13-5378             | 2         | 0.44%   |
| ASUS TUF Gaming X570-PLUS         | 2         | 0.44%   |
| ASUS P8P67 PRO                    | 2         | 0.44%   |
| ASUS M5A78L/USB3                  | 2         | 0.44%   |
| Apple MacBook6,1                  | 2         | 0.44%   |
| Apple iMac8,1                     | 2         | 0.44%   |
| Acer Aspire E5-575G               | 2         | 0.44%   |
| Unknown                           | 2         | 0.44%   |
| TUXEDO InfinityBook Pro 15 v5     | 1         | 0.22%   |
| TUXEDO InfinityBook Pro 14 Gen6   | 1         | 0.22%   |
| Toshiba TECRA R850                | 1         | 0.22%   |
| Toshiba TECRA M4                  | 1         | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 37        | 8.06%   |
| Dell Latitude         | 26        | 5.66%   |
| Dell OptiPlex         | 19        | 4.14%   |
| Dell Inspiron         | 15        | 3.27%   |
| Lenovo IdeaPad        | 14        | 3.05%   |
| Acer Aspire           | 14        | 3.05%   |
| Dell XPS              | 13        | 2.83%   |
| HP Pavilion           | 10        | 2.18%   |
| HP EliteBook          | 10        | 2.18%   |
| Dell Precision        | 10        | 2.18%   |
| Toshiba Satellite     | 7         | 1.53%   |
| Lenovo ThinkCentre    | 7         | 1.53%   |
| HP Compaq             | 7         | 1.53%   |
| ASUS TUF              | 7         | 1.53%   |
| ASUS PRIME            | 7         | 1.53%   |
| ASUS All              | 6         | 1.31%   |
| ASUS ROG              | 5         | 1.09%   |
| Gigabyte B450M        | 4         | 0.87%   |
| Dell Vostro           | 4         | 0.87%   |
| Lenovo Yoga           | 3         | 0.65%   |
| Lenovo V145-15AST     | 3         | 0.65%   |
| HP Presario           | 3         | 0.65%   |
| HP Laptop             | 3         | 0.65%   |
| HP EliteDesk          | 3         | 0.65%   |
| Foxconn Pro           | 3         | 0.65%   |
| Apple MacBookPro5     | 3         | 0.65%   |
| TUXEDO Pulse          | 2         | 0.44%   |
| TUXEDO InfinityBook   | 2         | 0.44%   |
| Toshiba TECRA         | 2         | 0.44%   |
| Seco C40              | 2         | 0.44%   |
| RPi Raspberry         | 2         | 0.44%   |
| Nvidia Tegra          | 2         | 0.44%   |
| MSI MS-7B79           | 2         | 0.44%   |
| Lenovo ThinkStation   | 2         | 0.44%   |
| Lenovo ThinkBook      | 2         | 0.44%   |
| HP ProBook            | 2         | 0.44%   |
| HP Notebook           | 2         | 0.44%   |
| Gigabyte X570         | 2         | 0.44%   |
| Gigabyte B450         | 2         | 0.44%   |
| Fujitsu Siemens AMILO | 2         | 0.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 50        | 10.89%  |
| 2018    | 44        | 9.59%   |
| 2013    | 42        | 9.15%   |
| 2020    | 40        | 8.71%   |
| 2012    | 38        | 8.28%   |
| 2011    | 36        | 7.84%   |
| 2017    | 35        | 7.63%   |
| 2010    | 25        | 5.45%   |
| 2008    | 25        | 5.45%   |
| 2015    | 22        | 4.79%   |
| 2021    | 20        | 4.36%   |
| 2016    | 20        | 4.36%   |
| 2009    | 18        | 3.92%   |
| 2014    | 15        | 3.27%   |
| 2007    | 10        | 2.18%   |
| 2006    | 7         | 1.53%   |
| Unknown | 6         | 1.31%   |
| 2022    | 3         | 0.65%   |
| 2005    | 2         | 0.44%   |
| 2003    | 1         | 0.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 267       | 58.17%  |
| Desktop        | 158       | 34.42%  |
| All in one     | 10        | 2.18%   |
| Convertible    | 7         | 1.53%   |
| Mini pc        | 7         | 1.53%   |
| System on chip | 6         | 1.31%   |
| Tablet         | 3         | 0.65%   |
| Phone          | 1         | 0.22%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 421       | 91.13%  |
| Enabled  | 41        | 8.87%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 459       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 110       | 23.45%  |
| 16.01-24.0  | 97        | 20.68%  |
| 3.01-4.0    | 88        | 18.76%  |
| 8.01-16.0   | 81        | 17.27%  |
| 32.01-64.0  | 49        | 10.45%  |
| 1.01-2.0    | 17        | 3.62%   |
| 64.01-256.0 | 12        | 2.56%   |
| 24.01-32.0  | 6         | 1.28%   |
| 2.01-3.0    | 5         | 1.07%   |
| 0.51-1.0    | 3         | 0.64%   |
| 0.01-0.5    | 1         | 0.21%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 180       | 35.5%   |
| 2.01-3.0   | 118       | 23.27%  |
| 3.01-4.0   | 76        | 14.99%  |
| 4.01-8.0   | 66        | 13.02%  |
| 0.51-1.0   | 38        | 7.5%    |
| 8.01-16.0  | 20        | 3.94%   |
| 0.01-0.5   | 5         | 0.99%   |
| 16.01-24.0 | 3         | 0.59%   |
| 32.01-64.0 | 1         | 0.2%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 288       | 59.5%   |
| 2      | 111       | 22.93%  |
| 3      | 38        | 7.85%   |
| 4      | 20        | 4.13%   |
| 5      | 11        | 2.27%   |
| 7      | 5         | 1.03%   |
| 6      | 4         | 0.83%   |
| 0      | 4         | 0.83%   |
| 10     | 2         | 0.41%   |
| 9      | 1         | 0.21%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 277       | 59.44%  |
| Yes       | 189       | 40.56%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 398       | 86.52%  |
| No        | 62        | 13.48%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 382       | 82.33%  |
| No        | 82        | 17.67%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 291       | 62.45%  |
| No        | 175       | 37.55%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Ireland | 459       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Dublin         | 269       | 56.39%  |
| Cork           | 29        | 6.08%   |
| Limerick       | 15        | 3.14%   |
| Galway         | 13        | 2.73%   |
| Naas           | 12        | 2.52%   |
| Portlaoise     | 6         | 1.26%   |
| Ennis          | 6         | 1.26%   |
| Drogheda       | 6         | 1.26%   |
| Sligo          | 5         | 1.05%   |
| Navan          | 5         | 1.05%   |
| Gorey          | 5         | 1.05%   |
| Athlone        | 5         | 1.05%   |
| Nenagh         | 4         | 0.84%   |
| Kilkenny       | 4         | 0.84%   |
| Kenmare        | 4         | 0.84%   |
| Wexford        | 3         | 0.63%   |
| Tuam           | 3         | 0.63%   |
| Enniscorthy    | 3         | 0.63%   |
| Dún Laoghaire | 3         | 0.63%   |
| Westport       | 2         | 0.42%   |
| Waterford      | 2         | 0.42%   |
| Tullamore      | 2         | 0.42%   |
| Oranmore       | 2         | 0.42%   |
| Maynooth       | 2         | 0.42%   |
| Mallow         | 2         | 0.42%   |
| Loughrea       | 2         | 0.42%   |
| Letterkenny    | 2         | 0.42%   |
| Cobh           | 2         | 0.42%   |
| Clonakilty     | 2         | 0.42%   |
| Clane          | 2         | 0.42%   |
| Cavan          | 2         | 0.42%   |
| Carrigaline    | 2         | 0.42%   |
| Bray           | 2         | 0.42%   |
| Ballina        | 2         | 0.42%   |
| Balbriggan     | 2         | 0.42%   |
| Youghal        | 1         | 0.21%   |
| Wicklow        | 1         | 0.21%   |
| Tullow         | 1         | 0.21%   |
| Tralee         | 1         | 0.21%   |
| Tobercurry     | 1         | 0.21%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 122       | 204    | 17.76%  |
| Samsung Electronics       | 120       | 172    | 17.47%  |
| Seagate                   | 87        | 145    | 12.66%  |
| Toshiba                   | 42        | 54     | 6.11%   |
| SanDisk                   | 38        | 47     | 5.53%   |
| Crucial                   | 38        | 48     | 5.53%   |
| Unknown                   | 34        | 45     | 4.95%   |
| Hitachi                   | 32        | 45     | 4.66%   |
| Kingston                  | 20        | 27     | 2.91%   |
| Intel                     | 14        | 17     | 2.04%   |
| Micron Technology         | 11        | 12     | 1.6%    |
| HGST                      | 10        | 11     | 1.46%   |
| A-DATA Technology         | 10        | 15     | 1.46%   |
| SK hynix                  | 8         | 8      | 1.16%   |
| Phison                    | 7         | 12     | 1.02%   |
| Fujitsu                   | 7         | 8      | 1.02%   |
| Apple                     | 6         | 7      | 0.87%   |
| Verbatim                  | 5         | 5      | 0.73%   |
| Silicon Motion            | 4         | 7      | 0.58%   |
| PNY                       | 4         | 4      | 0.58%   |
| LITEON                    | 4         | 4      | 0.58%   |
| KIOXIA                    | 4         | 5      | 0.58%   |
| China                     | 4         | 8      | 0.58%   |
| OCZ                       | 3         | 3      | 0.44%   |
| Micron/Crucial Technology | 3         | 4      | 0.44%   |
| KingSpec                  | 3         | 3      | 0.44%   |
| KingDian                  | 3         | 8      | 0.44%   |
| ASMT                      | 3         | 5      | 0.44%   |
| Union Memory              | 2         | 2      | 0.29%   |
| Transcend                 | 2         | 2      | 0.29%   |
| Team                      | 2         | 2      | 0.29%   |
| Netac                     | 2         | 2      | 0.29%   |
| Maxtor                    | 2         | 2      | 0.29%   |
| LITEONIT                  | 2         | 2      | 0.29%   |
| Integral                  | 2         | 2      | 0.29%   |
| Zheino                    | 1         | 1      | 0.15%   |
| WDS100T1                  | 1         | 1      | 0.15%   |
| W800S                     | 1         | 2      | 0.15%   |
| USB3.0                    | 1         | 1      | 0.15%   |
| Union Memory (Shenzhen)   | 1         | 1      | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB         | 7         | 0.91%   |
| Crucial CT1000MX500SSD1 1TB            | 7         | 0.91%   |
| Unknown MMC Card  64GB                 | 6         | 0.78%   |
| Toshiba MQ01ABD100 1TB                 | 6         | 0.78%   |
| Seagate ST8000DM004-2CX188 8TB         | 6         | 0.78%   |
| Seagate ST1000DM010-2EP102 1TB         | 6         | 0.78%   |
| Samsung SSD 860 EVO 500GB              | 6         | 0.78%   |
| Samsung SSD 850 EVO 250GB              | 6         | 0.78%   |
| Samsung SSD 840 EVO 250GB              | 6         | 0.78%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 6         | 0.78%   |
| Samsung NVMe SSD Drive 500GB           | 6         | 0.78%   |
| Verbatim Vi550 S3 SSD 512GB            | 5         | 0.65%   |
| Unknown MMC Card  32GB                 | 5         | 0.65%   |
| SanDisk NVMe SSD Drive 512GB           | 5         | 0.65%   |
| Samsung SSD 970 EVO Plus 500GB         | 5         | 0.65%   |
| WDC WDS500G2B0B-00YS70 500GB SSD       | 4         | 0.52%   |
| WDC WD10EZEX-08WN4A0 1TB               | 4         | 0.52%   |
| WDC WD10EURX-83UY4Y0 1TB               | 4         | 0.52%   |
| Seagate ST500DM002-1BD142 500GB        | 4         | 0.52%   |
| Seagate ST2000DL003-9VT166 2TB         | 4         | 0.52%   |
| Seagate Expansion Desk 8TB             | 4         | 0.52%   |
| Samsung SSD 850 EVO 500GB              | 4         | 0.52%   |
| Kingston SV300S37A120G 120GB SSD       | 4         | 0.52%   |
| Kingston SA400S37480G 480GB SSD        | 4         | 0.52%   |
| Kingston SA400S37240G 240GB SSD        | 4         | 0.52%   |
| Crucial M4-CT128M4SSD2 128GB           | 4         | 0.52%   |
| Crucial CT500MX500SSD1 500GB           | 4         | 0.52%   |
| WDC WD5000AAKX-60U6AA0 500GB           | 3         | 0.39%   |
| WDC WD3200AAJS-60Z0A0 320GB            | 3         | 0.39%   |
| WDC WD20EZRX-00D8PB0 2TB               | 3         | 0.39%   |
| WDC WD10EALX-009BA0 1TB                | 3         | 0.39%   |
| Toshiba DT01ACA100 1TB                 | 3         | 0.39%   |
| Seagate ST3500418AS 500GB              | 3         | 0.39%   |
| Seagate ST3500312CS 500GB              | 3         | 0.39%   |
| Seagate ST31000528AS 1TB               | 3         | 0.39%   |
| Seagate ST2000DM006-2DM164 2TB         | 3         | 0.39%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 3         | 0.39%   |
| SanDisk SSD PLUS 240GB                 | 3         | 0.39%   |
| SanDisk NVMe SSD Drive 500GB           | 3         | 0.39%   |
| SanDisk NVMe SSD Drive 256GB           | 3         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 97        | 170    | 33.68%  |
| Seagate             | 86        | 144    | 29.86%  |
| Hitachi             | 32        | 45     | 11.11%  |
| Toshiba             | 30        | 38     | 10.42%  |
| Samsung Electronics | 11        | 13     | 3.82%   |
| HGST                | 10        | 11     | 3.47%   |
| Fujitsu             | 7         | 8      | 2.43%   |
| Apple               | 4         | 4      | 1.39%   |
| Maxtor              | 2         | 2      | 0.69%   |
| USB3.0              | 1         | 1      | 0.35%   |
| Unknown             | 1         | 1      | 0.35%   |
| SABRENT             | 1         | 2      | 0.35%   |
| QNAP                | 1         | 1      | 0.35%   |
| LaCie               | 1         | 1      | 0.35%   |
| KESU                | 1         | 1      | 0.35%   |
| Inateck             | 1         | 1      | 0.35%   |
| ExcelStor           | 1         | 2      | 0.35%   |
| ASMT                | 1         | 1      | 0.35%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 64        | 83     | 28.32%  |
| Crucial             | 35        | 45     | 15.49%  |
| SanDisk             | 22        | 25     | 9.73%   |
| Kingston            | 19        | 25     | 8.41%   |
| WDC                 | 11        | 17     | 4.87%   |
| A-DATA Technology   | 7         | 11     | 3.1%    |
| Intel               | 6         | 6      | 2.65%   |
| Verbatim            | 5         | 5      | 2.21%   |
| PNY                 | 4         | 4      | 1.77%   |
| LITEON              | 4         | 4      | 1.77%   |
| China               | 4         | 8      | 1.77%   |
| Toshiba             | 3         | 5      | 1.33%   |
| OCZ                 | 3         | 3      | 1.33%   |
| Micron Technology   | 3         | 3      | 1.33%   |
| KingSpec            | 3         | 3      | 1.33%   |
| KingDian            | 3         | 8      | 1.33%   |
| Apple               | 3         | 3      | 1.33%   |
| Transcend           | 2         | 2      | 0.88%   |
| Team                | 2         | 2      | 0.88%   |
| Netac               | 2         | 2      | 0.88%   |
| LITEONIT            | 2         | 2      | 0.88%   |
| Integral            | 2         | 2      | 0.88%   |
| ASMT                | 2         | 4      | 0.88%   |
| Zheino              | 1         | 1      | 0.44%   |
| W800S               | 1         | 2      | 0.44%   |
| TCSUNBOW            | 1         | 1      | 0.44%   |
| SK hynix            | 1         | 1      | 0.44%   |
| Plextor             | 1         | 1      | 0.44%   |
| Palit               | 1         | 1      | 0.44%   |
| Hikvision           | 1         | 1      | 0.44%   |
| Hewlett-Packard     | 1         | 2      | 0.44%   |
| GOODRAM             | 1         | 1      | 0.44%   |
| FORESEE             | 1         | 1      | 0.44%   |
| faspeed             | 1         | 1      | 0.44%   |
| Emtec               | 1         | 2      | 0.44%   |
| DRVEO               | 1         | 1      | 0.44%   |
| Dogfish             | 1         | 1      | 0.44%   |
| Corsair             | 1         | 2      | 0.44%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 230       | 446    | 38.33%  |
| SSD     | 199       | 291    | 33.17%  |
| NVMe    | 132       | 190    | 22%     |
| MMC     | 32        | 46     | 5.33%   |
| Unknown | 7         | 7      | 1.17%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 352       | 714    | 65.43%  |
| NVMe | 132       | 190    | 24.54%  |
| MMC  | 32        | 46     | 5.95%   |
| SAS  | 22        | 30     | 4.09%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 258       | 414    | 55.6%   |
| 0.51-1.0   | 141       | 206    | 30.39%  |
| 1.01-2.0   | 31        | 46     | 6.68%   |
| 4.01-10.0  | 13        | 32     | 2.8%    |
| 3.01-4.0   | 12        | 27     | 2.59%   |
| 2.01-3.0   | 8         | 11     | 1.72%   |
| 20.01-50.0 | 1         | 1      | 0.22%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 123       | 25.31%  |
| 251-500        | 110       | 22.63%  |
| 501-1000       | 65        | 13.37%  |
| 51-100         | 42        | 8.64%   |
| 1-20           | 39        | 8.02%   |
| 1001-2000      | 33        | 6.79%   |
| More than 3000 | 29        | 5.97%   |
| Unknown        | 18        | 3.7%    |
| 21-50          | 15        | 3.09%   |
| 2001-3000      | 12        | 2.47%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 191       | 37.6%   |
| 101-250        | 71        | 13.98%  |
| 21-50          | 68        | 13.39%  |
| 51-100         | 61        | 12.01%  |
| 251-500        | 34        | 6.69%   |
| 501-1000       | 33        | 6.5%    |
| Unknown        | 18        | 3.54%   |
| More than 3000 | 15        | 2.95%   |
| 1001-2000      | 10        | 1.97%   |
| 2001-3000      | 7         | 1.38%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD10EALX-009BA0 1TB                        | 3         | 8      | 5.17%   |
| Seagate ST2000DL003-9VT166 2TB                 | 3         | 5      | 5.17%   |
| WDC WD2500AAKX-753CA1 250GB                    | 2         | 3      | 3.45%   |
| Hitachi HTS723232A7A364 320GB                  | 2         | 2      | 3.45%   |
| WDC WD7500BPKX-00HPJT0 752GB                   | 1         | 1      | 1.72%   |
| WDC WD5000BEVT-35A0RT0 500GB                   | 1         | 1      | 1.72%   |
| WDC WD5000AAKX-001CA0 500GB                    | 1         | 1      | 1.72%   |
| WDC WD400JB-00FMA0 40GB                        | 1         | 2      | 1.72%   |
| WDC WD3200AVJS-63B6A0 320GB                    | 1         | 1      | 1.72%   |
| WDC WD2500BEVT-22A23T0 250GB                   | 1         | 1      | 1.72%   |
| WDC WD2500BEKT-75A25T0 250GB                   | 1         | 1      | 1.72%   |
| WDC WD2500AAKX-603CA0 250GB                    | 1         | 1      | 1.72%   |
| WDC WD20EZRZ-00Z5HB0 2TB                       | 1         | 1      | 1.72%   |
| WDC WD10EZEX-00BN5A0 1TB                       | 1         | 1      | 1.72%   |
| WDC WD1001FALS-00E8B0 1TB                      | 1         | 2      | 1.72%   |
| Toshiba MQ01ABF050H 500GB                      | 1         | 1      | 1.72%   |
| Toshiba MQ01ABD050 500GB                       | 1         | 1      | 1.72%   |
| Toshiba MK1652GSX 160GB                        | 1         | 1      | 1.72%   |
| Toshiba MK1059GSM 1TB                          | 1         | 1      | 1.72%   |
| Toshiba DT01ACA050 500GB                       | 1         | 2      | 1.72%   |
| Seagate ST910021AS 100GB                       | 1         | 1      | 1.72%   |
| Seagate ST500LM012 HN-M500MBB 500GB            | 1         | 1      | 1.72%   |
| Seagate ST4000DX001-1CE168 4TB                 | 1         | 1      | 1.72%   |
| Seagate ST3500418AS 500GB                      | 1         | 2      | 1.72%   |
| Seagate ST31500541AS 1TB                       | 1         | 1      | 1.72%   |
| Seagate ST3120026A 120GB                       | 1         | 1      | 1.72%   |
| Seagate ST31000333AS 1TB                       | 1         | 2      | 1.72%   |
| Seagate ST3000DM001-1ER166 3TB                 | 1         | 1      | 1.72%   |
| SanDisk SSD PLUS 240GB                         | 1         | 1      | 1.72%   |
| Samsung Electronics SSD 970 EVO Plus 2TB       | 1         | 1      | 1.72%   |
| Samsung Electronics HM120JC 120GB              | 1         | 1      | 1.72%   |
| Samsung Electronics HD103SI 1TB                | 1         | 1      | 1.72%   |
| Netac SSD 128GB                                | 1         | 1      | 1.72%   |
| Micron Technology 2300 NVMe 512GB              | 1         | 1      | 1.72%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 1.72%   |
| Maxtor STM3250310AS 250GB                      | 1         | 1      | 1.72%   |
| Intel SSDSA2M080G2GC 80GB                      | 1         | 1      | 1.72%   |
| Inateck ASM1153E 256GB                         | 1         | 1      | 1.72%   |
| Hitachi HUS724030ALA640 3TB                    | 1         | 2      | 1.72%   |
| Hitachi HTS545050B9A300 500GB                  | 1         | 1      | 1.72%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 13        | 24     | 23.64%  |
| Seagate             | 11        | 15     | 20%     |
| Hitachi             | 9         | 12     | 16.36%  |
| Toshiba             | 5         | 6      | 9.09%   |
| Samsung Electronics | 3         | 3      | 5.45%   |
| Micron Technology   | 2         | 2      | 3.64%   |
| HGST                | 2         | 2      | 3.64%   |
| SanDisk             | 1         | 1      | 1.82%   |
| Netac               | 1         | 1      | 1.82%   |
| Maxtor              | 1         | 1      | 1.82%   |
| Intel               | 1         | 1      | 1.82%   |
| Inateck             | 1         | 1      | 1.82%   |
| Fujitsu             | 1         | 1      | 1.82%   |
| DRVEO               | 1         | 1      | 1.82%   |
| China               | 1         | 1      | 1.82%   |
| Apple               | 1         | 1      | 1.82%   |
| A-DATA Technology   | 1         | 1      | 1.82%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 13        | 24     | 28.26%  |
| Seagate             | 11        | 15     | 23.91%  |
| Hitachi             | 9         | 12     | 19.57%  |
| Toshiba             | 5         | 6      | 10.87%  |
| Samsung Electronics | 2         | 2      | 4.35%   |
| HGST                | 2         | 2      | 4.35%   |
| Maxtor              | 1         | 1      | 2.17%   |
| Inateck             | 1         | 1      | 2.17%   |
| Fujitsu             | 1         | 1      | 2.17%   |
| Apple               | 1         | 1      | 2.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 36        | 65     | 80%     |
| SSD  | 7         | 7      | 15.56%  |
| NVMe | 2         | 2      | 4.44%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                       | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC WD1200BEVS-22UST0 120GB | 1         | 1      | 50%     |
| KingDian S400 120GB         | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| WDC      | 1         | 1      | 50%     |
| KingDian | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 287       | 572    | 56.61%  |
| Works    | 174       | 332    | 34.32%  |
| Malfunc  | 44        | 74     | 8.68%   |
| Failed   | 2         | 2      | 0.39%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 300       | 53.1%   |
| AMD                          | 85        | 15.04%  |
| Samsung Electronics          | 54        | 9.56%   |
| SanDisk                      | 29        | 5.13%   |
| Nvidia                       | 13        | 2.3%    |
| Toshiba America Info Systems | 10        | 1.77%   |
| Marvell Technology Group     | 9         | 1.59%   |
| Micron Technology            | 8         | 1.42%   |
| ASMedia Technology           | 8         | 1.42%   |
| SK hynix                     | 7         | 1.24%   |
| Phison Electronics           | 7         | 1.24%   |
| Micron/Crucial Technology    | 6         | 1.06%   |
| JMicron Technology           | 5         | 0.88%   |
| Union Memory (Shenzhen)      | 4         | 0.71%   |
| Silicon Motion               | 4         | 0.71%   |
| KIOXIA                       | 4         | 0.71%   |
| LSI Logic / Symbios Logic    | 3         | 0.53%   |
| Realtek Semiconductor        | 2         | 0.35%   |
| ULi Electronics              | 1         | 0.18%   |
| Silicon Image                | 1         | 0.18%   |
| Seagate Technology           | 1         | 0.18%   |
| Kingston Technology Company  | 1         | 0.18%   |
| Broadcom / LSI               | 1         | 0.18%   |
| ADATA Technology             | 1         | 0.18%   |
| Adaptec                      | 1         | 0.18%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 63        | 9.57%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 32        | 4.86%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 31        | 4.71%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 20        | 3.04%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 18        | 2.74%   |
| AMD 400 Series Chipset SATA Controller                                                  | 17        | 2.58%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 16        | 2.43%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 15        | 2.28%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 13        | 1.98%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 13        | 1.98%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 12        | 1.82%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 11        | 1.67%   |
| Samsung NVMe SSD Controller 980                                                         | 11        | 1.67%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 11        | 1.67%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 10        | 1.52%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 10        | 1.52%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 9         | 1.37%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 9         | 1.37%   |
| Micron Non-Volatile memory controller                                                   | 8         | 1.22%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 8         | 1.22%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 8         | 1.22%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 8         | 1.22%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 8         | 1.22%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 7         | 1.06%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 7         | 1.06%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 6         | 0.91%   |
| Nvidia MCP79 AHCI Controller                                                            | 6         | 0.91%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 6         | 0.91%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 6         | 0.91%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 6         | 0.91%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 6         | 0.91%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 6         | 0.91%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 6         | 0.91%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 6         | 0.91%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 6         | 0.91%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 5         | 0.76%   |
| Intel SATA Controller [RAID mode]                                                       | 5         | 0.76%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5         | 0.76%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 5         | 0.76%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 5         | 0.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 336       | 59.05%  |
| NVMe | 133       | 23.37%  |
| IDE  | 67        | 11.78%  |
| RAID | 30        | 5.27%   |
| SCSI | 3         | 0.53%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 348       | 75.82%  |
| AMD    | 104       | 22.66%  |
| ARM    | 7         | 1.53%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 7         | 1.52%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 7         | 1.52%   |
| ARM Processor                                 | 7         | 1.52%   |
| AMD Ryzen 5 3600 6-Core Processor             | 7         | 1.52%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 6         | 1.3%    |
| Intel Core i7-3770 CPU @ 3.40GHz              | 6         | 1.3%    |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 6         | 1.3%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 1.08%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 5         | 1.08%   |
| Intel Core i7-2600K CPU @ 3.40GHz             | 5         | 1.08%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 5         | 1.08%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 5         | 1.08%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 5         | 1.08%   |
| Intel Core i7-3770K CPU @ 3.50GHz             | 4         | 0.87%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 0.87%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 4         | 0.87%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 4         | 0.87%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 4         | 0.87%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 0.87%   |
| AMD Ryzen 5 2600X Six-Core Processor          | 4         | 0.87%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 0.65%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 3         | 0.65%   |
| Intel Core i5-3340M CPU @ 2.70GHz             | 3         | 0.65%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 3         | 0.65%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 0.65%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 3         | 0.65%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 3         | 0.65%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 3         | 0.65%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 3         | 0.65%   |
| Intel Core 2 Duo CPU T5800 @ 2.00GHz          | 3         | 0.65%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 3         | 0.65%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 3         | 0.65%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 3         | 0.65%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 3         | 0.65%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 0.65%   |
| AMD Athlon II X4 620 Processor                | 3         | 0.65%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G  | 3         | 0.65%   |
| Intel Xeon CPU X5690 @ 3.47GHz                | 2         | 0.43%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 2         | 0.43%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 98        | 21.21%  |
| Intel Core i7           | 96        | 20.78%  |
| Other                   | 34        | 7.36%   |
| Intel Core i3           | 34        | 7.36%   |
| AMD Ryzen 5             | 28        | 6.06%   |
| Intel Core 2 Duo        | 24        | 5.19%   |
| Intel Celeron           | 22        | 4.76%   |
| AMD Ryzen 7             | 11        | 2.38%   |
| Intel Atom              | 10        | 2.16%   |
| Intel Core 2 Quad       | 8         | 1.73%   |
| AMD Ryzen 9             | 8         | 1.73%   |
| Intel Pentium           | 7         | 1.52%   |
| Intel Xeon              | 6         | 1.3%    |
| AMD FX                  | 6         | 1.3%    |
| AMD Athlon 64 X2        | 6         | 1.3%    |
| Intel Pentium Dual-Core | 4         | 0.87%   |
| AMD Ryzen 3             | 4         | 0.87%   |
| AMD A8                  | 4         | 0.87%   |
| Intel Core 2            | 3         | 0.65%   |
| AMD Athlon II X4        | 3         | 0.65%   |
| AMD A6                  | 3         | 0.65%   |
| Intel Pentium 4         | 2         | 0.43%   |
| Intel Core m3           | 2         | 0.43%   |
| Intel Core i9           | 2         | 0.43%   |
| Intel Celeron Dual-Core | 2         | 0.43%   |
| AMD Ryzen Threadripper  | 2         | 0.43%   |
| AMD Ryzen Embedded      | 2         | 0.43%   |
| AMD Ryzen 7 PRO         | 2         | 0.43%   |
| AMD Ryzen 5 PRO         | 2         | 0.43%   |
| AMD Phenom II X6        | 2         | 0.43%   |
| AMD E2                  | 2         | 0.43%   |
| AMD A4                  | 2         | 0.43%   |
| Intel Pentium Silver    | 1         | 0.22%   |
| Intel Pentium M         | 1         | 0.22%   |
| Intel Pentium III       | 1         | 0.22%   |
| Intel Pentium D         | 1         | 0.22%   |
| Intel Genuine           | 1         | 0.22%   |
| Intel Core m7           | 1         | 0.22%   |
| Intel Core m5           | 1         | 0.22%   |
| Intel Core 2 Extreme    | 1         | 0.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 189       | 41.09%  |
| 2       | 179       | 38.91%  |
| 6       | 37        | 8.04%   |
| 8       | 20        | 4.35%   |
| 1       | 16        | 3.48%   |
| 12      | 10        | 2.17%   |
| 14      | 4         | 0.87%   |
| 3       | 3         | 0.65%   |
| 32      | 1         | 0.22%   |
| Unknown | 1         | 0.22%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 456       | 99.35%  |
| 2      | 3         | 0.65%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 296       | 64.07%  |
| 1       | 165       | 35.71%  |
| Unknown | 1         | 0.22%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 441       | 95.66%  |
| Unknown        | 17        | 3.69%   |
| 32-bit         | 3         | 0.65%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 117       | 24.84%  |
| 0x306a9    | 31        | 6.58%   |
| 0x206a7    | 25        | 5.31%   |
| 0x1067a    | 21        | 4.46%   |
| 0x306c3    | 20        | 4.25%   |
| 0x806ec    | 15        | 3.18%   |
| 0x806e9    | 15        | 3.18%   |
| 0x806c1    | 12        | 2.55%   |
| 0x806ea    | 9         | 1.91%   |
| 0x406e3    | 9         | 1.91%   |
| 0x40651    | 9         | 1.91%   |
| 0x906ea    | 8         | 1.7%    |
| 0x906e9    | 8         | 1.7%    |
| 0x10676    | 8         | 1.7%    |
| 0x08701021 | 7         | 1.49%   |
| 0xa0652    | 6         | 1.27%   |
| 0x406c4    | 6         | 1.27%   |
| 0x306d4    | 6         | 1.27%   |
| 0x30678    | 6         | 1.27%   |
| 0x08108109 | 6         | 1.27%   |
| 0x20655    | 5         | 1.06%   |
| 0x08108102 | 5         | 1.06%   |
| 0x0810100b | 5         | 1.06%   |
| 0x06006705 | 5         | 1.06%   |
| 0x6fd      | 4         | 0.85%   |
| 0x6fb      | 4         | 0.85%   |
| 0x506e3    | 4         | 0.85%   |
| 0x0800820d | 4         | 0.85%   |
| 0xa0653    | 3         | 0.64%   |
| 0x806d1    | 3         | 0.64%   |
| 0x706e5    | 3         | 0.64%   |
| 0x206c2    | 3         | 0.64%   |
| 0x106ca    | 3         | 0.64%   |
| 0x08701013 | 3         | 0.64%   |
| 0x06001119 | 3         | 0.64%   |
| 0x06000852 | 3         | 0.64%   |
| 0x010000c8 | 3         | 0.64%   |
| 0x906ed    | 2         | 0.42%   |
| 0x906a3    | 2         | 0.42%   |
| 0x706a8    | 2         | 0.42%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 69        | 15%     |
| IvyBridge        | 43        | 9.35%   |
| SandyBridge      | 36        | 7.83%   |
| Haswell          | 35        | 7.61%   |
| Penryn           | 30        | 6.52%   |
| Zen 2            | 22        | 4.78%   |
| Zen+             | 21        | 4.57%   |
| Skylake          | 21        | 4.57%   |
| Silvermont       | 17        | 3.7%    |
| TigerLake        | 15        | 3.26%   |
| Westmere         | 14        | 3.04%   |
| Core             | 14        | 3.04%   |
| Zen              | 11        | 2.39%   |
| CometLake        | 11        | 2.39%   |
| Unknown          | 10        | 2.17%   |
| K8 Hammer        | 9         | 1.96%   |
| K10              | 9         | 1.96%   |
| Excavator        | 9         | 1.96%   |
| Piledriver       | 8         | 1.74%   |
| IceLake          | 7         | 1.52%   |
| Broadwell        | 7         | 1.52%   |
| Nehalem          | 6         | 1.3%    |
| Goldmont plus    | 6         | 1.3%    |
| Zen 3            | 5         | 1.09%   |
| Bonnell          | 5         | 1.09%   |
| P6               | 4         | 0.87%   |
| Puma             | 3         | 0.65%   |
| NetBurst         | 3         | 0.65%   |
| Bobcat           | 3         | 0.65%   |
| Goldmont         | 2         | 0.43%   |
| Alderlake Hybrid | 2         | 0.43%   |
| Steamroller      | 1         | 0.22%   |
| Jaguar           | 1         | 0.22%   |
| Bulldozer        | 1         | 0.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 259       | 48.96%  |
| Nvidia | 145       | 27.41%  |
| AMD    | 125       | 23.63%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 23        | 4.19%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 21        | 3.83%   |
| Intel HD Graphics 620                                                                    | 15        | 2.73%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 14        | 2.55%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 13        | 2.37%   |
| Intel UHD Graphics 620                                                                   | 10        | 1.82%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 10        | 1.82%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 10        | 1.82%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 10        | 1.82%   |
| Intel HD Graphics 630                                                                    | 9         | 1.64%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 9         | 1.64%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 9         | 1.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 8         | 1.46%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 8         | 1.46%   |
| Intel Core Processor Integrated Graphics Controller                                      | 8         | 1.46%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 1.46%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 8         | 1.46%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 8         | 1.46%   |
| AMD Renoir                                                                               | 7         | 1.28%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 6         | 1.09%   |
| Intel HD Graphics 5500                                                                   | 6         | 1.09%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 6         | 1.09%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 6         | 1.09%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 5         | 0.91%   |
| Nvidia C79 [GeForce 9400M]                                                               | 5         | 0.91%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 0.91%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 5         | 0.91%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 0.91%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 5         | 0.91%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 0.91%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 5         | 0.91%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 0.73%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 4         | 0.73%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 4         | 0.73%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 4         | 0.73%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 4         | 0.73%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 4         | 0.73%   |
| AMD Caicos PRO [Radeon HD 7450]                                                          | 4         | 0.73%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 3         | 0.55%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 3         | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 195       | 41.94%  |
| 1 x AMD        | 104       | 22.37%  |
| 1 x Nvidia     | 85        | 18.28%  |
| Intel + Nvidia | 52        | 11.18%  |
| 2 x AMD        | 11        | 2.37%   |
| Other          | 7         | 1.51%   |
| AMD + Nvidia   | 7         | 1.51%   |
| Intel + AMD    | 3         | 0.65%   |
| 2 x Nvidia     | 1         | 0.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 370       | 79.23%  |
| Proprietary | 73        | 15.63%  |
| Unknown     | 24        | 5.14%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 256       | 53.67%  |
| 0.01-0.5   | 56        | 11.74%  |
| 1.01-2.0   | 48        | 10.06%  |
| 3.01-4.0   | 40        | 8.39%   |
| 0.51-1.0   | 38        | 7.97%   |
| 7.01-8.0   | 20        | 4.19%   |
| 5.01-6.0   | 12        | 2.52%   |
| 2.01-3.0   | 4         | 0.84%   |
| 8.01-16.0  | 2         | 0.42%   |
| 16.01-24.0 | 1         | 0.21%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 56        | 11.31%  |
| Dell                    | 54        | 10.91%  |
| LG Display              | 51        | 10.3%   |
| Samsung Electronics     | 46        | 9.29%   |
| BOE                     | 38        | 7.68%   |
| Chimei Innolux          | 32        | 6.46%   |
| Acer                    | 20        | 4.04%   |
| Sharp                   | 19        | 3.84%   |
| Hewlett-Packard         | 17        | 3.43%   |
| Apple                   | 17        | 3.43%   |
| Goldstar                | 14        | 2.83%   |
| BenQ                    | 14        | 2.83%   |
| Philips                 | 13        | 2.63%   |
| Iiyama                  | 11        | 2.22%   |
| AOC                     | 11        | 2.22%   |
| Lenovo                  | 9         | 1.82%   |
| Chi Mei Optoelectronics | 7         | 1.41%   |
| PANDA                   | 6         | 1.21%   |
| ViewSonic               | 4         | 0.81%   |
| Ancor Communications    | 4         | 0.81%   |
| ___                     | 3         | 0.61%   |
| Vestel Elektronik       | 3         | 0.61%   |
| Unknown                 | 3         | 0.61%   |
| Sony                    | 3         | 0.61%   |
| LG Philips              | 3         | 0.61%   |
| InfoVision              | 3         | 0.61%   |
| HannStar                | 3         | 0.61%   |
| Toshiba                 | 2         | 0.4%    |
| MSI                     | 2         | 0.4%    |
| MiTAC                   | 2         | 0.4%    |
| HKC                     | 2         | 0.4%    |
| CSO                     | 2         | 0.4%    |
| CPT                     | 2         | 0.4%    |
| BOE Technology Group    | 2         | 0.4%    |
| ASUSTek Computer        | 2         | 0.4%    |
| Unknown                 | 2         | 0.4%    |
| Targa Visionary         | 1         | 0.2%    |
| Targa                   | 1         | 0.2%    |
| RTK                     | 1         | 0.2%    |
| Quanta Display          | 1         | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Iiyama PLT2336 IVM5628 1920x1080 509x286mm 23.0-inch                   | 5         | 0.96%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 700x390mm 31.5-inch   | 4         | 0.77%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch         | 4         | 0.77%   |
| ___ LCD TV ___9000 1360x768                                            | 3         | 0.57%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 3         | 0.57%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                     | 3         | 0.57%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch   | 3         | 0.57%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch           | 3         | 0.57%   |
| LG Display LCD Monitor LGD0382 1600x900 309x174mm 14.0-inch            | 3         | 0.57%   |
| Dell P2014H DEL4097 1600x900 434x236mm 19.4-inch                       | 3         | 0.57%   |
| Chimei Innolux LCD Monitor CMN15D7 1920x1080 344x193mm 15.5-inch       | 3         | 0.57%   |
| BenQ BenQG2222HDL BNQ7859 1920x1080 478x269mm 21.6-inch                | 3         | 0.57%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch         | 3         | 0.57%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                | 2         | 0.38%   |
| Sharp LCD Monitor SHP1547 1920x1200 288x180mm 13.4-inch                | 2         | 0.38%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                | 2         | 0.38%   |
| Sharp LCD Monitor SHP14CC 3840x2400 288x180mm 13.4-inch                | 2         | 0.38%   |
| Sharp LCD Monitor SHP14AE 1920x1080 294x165mm 13.3-inch                | 2         | 0.38%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch      | 2         | 0.38%   |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 518x324mm 24.1-inch    | 2         | 0.38%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch      | 2         | 0.38%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                | 2         | 0.38%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                | 2         | 0.38%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 520x290mm 23.4-inch                | 2         | 0.38%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                | 2         | 0.38%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch          | 2         | 0.38%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch           | 2         | 0.38%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch           | 2         | 0.38%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch           | 2         | 0.38%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch            | 2         | 0.38%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch            | 2         | 0.38%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch                | 2         | 0.38%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch           | 2         | 0.38%   |
| Hewlett-Packard Z34c HWP3201 3440x1440 797x333mm 34.0-inch             | 2         | 0.38%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 597x336mm 27.0-inch                 | 2         | 0.38%   |
| Dell U2715H DELD069 2560x1440 597x336mm 27.0-inch                      | 2         | 0.38%   |
| Dell U2518D DEL413C 2560x1440 553x311mm 25.0-inch                      | 2         | 0.38%   |
| Dell U2518D DEL413A 2560x1440 553x311mm 25.0-inch                      | 2         | 0.38%   |
| Dell P2417H DELA0DB 1920x1080 527x296mm 23.8-inch                      | 2         | 0.38%   |
| Dell P2317H DEL40F3 1920x1080 510x290mm 23.1-inch                      | 2         | 0.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 210       | 43.75%  |
| 1366x768 (WXGA)    | 85        | 17.71%  |
| 3840x2160 (4K)     | 32        | 6.67%   |
| 2560x1440 (QHD)    | 22        | 4.58%   |
| 1600x900 (HD+)     | 19        | 3.96%   |
| 1920x1200 (WUXGA)  | 16        | 3.33%   |
| 1440x900 (WXGA+)   | 15        | 3.13%   |
| 1280x800 (WXGA)    | 13        | 2.71%   |
| 1280x1024 (SXGA)   | 12        | 2.5%    |
| 3440x1440          | 9         | 1.88%   |
| 1360x768           | 7         | 1.46%   |
| Unknown            | 7         | 1.46%   |
| 1680x1050 (WSXGA+) | 6         | 1.25%   |
| 3840x2400          | 3         | 0.63%   |
| 3840x1080          | 3         | 0.63%   |
| 1600x1200          | 3         | 0.63%   |
| 1024x600           | 3         | 0.63%   |
| 3200x1800 (QHD+)   | 2         | 0.42%   |
| 2560x1600          | 2         | 0.42%   |
| 1024x768 (XGA)     | 2         | 0.42%   |
| 6400x2160          | 1         | 0.21%   |
| 5280x2560          | 1         | 0.21%   |
| 4480x1440          | 1         | 0.21%   |
| 3600x1080          | 1         | 0.21%   |
| 3456x2160          | 1         | 0.21%   |
| 2560x1080          | 1         | 0.21%   |
| 2256x1504          | 1         | 0.21%   |
| 2160x1440          | 1         | 0.21%   |
| 1920x540           | 1         | 0.21%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 131       | 26.41%  |
| 14      | 50        | 10.08%  |
| 27      | 47        | 9.48%   |
| 13      | 40        | 8.06%   |
| 24      | 35        | 7.06%   |
| 23      | 32        | 6.45%   |
| 21      | 27        | 5.44%   |
| Unknown | 24        | 4.84%   |
| 17      | 20        | 4.03%   |
| 19      | 13        | 2.62%   |
| 12      | 12        | 2.42%   |
| 34      | 10        | 2.02%   |
| 31      | 9         | 1.81%   |
| 18      | 8         | 1.61%   |
| 20      | 5         | 1.01%   |
| 84      | 4         | 0.81%   |
| 72      | 4         | 0.81%   |
| 32      | 4         | 0.81%   |
| 11      | 4         | 0.81%   |
| 25      | 3         | 0.6%    |
| 22      | 3         | 0.6%    |
| 10      | 3         | 0.6%    |
| 40      | 2         | 0.4%    |
| 65      | 1         | 0.2%    |
| 49      | 1         | 0.2%    |
| 46      | 1         | 0.2%    |
| 35      | 1         | 0.2%    |
| 33      | 1         | 0.2%    |
| 29      | 1         | 0.2%    |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 194       | 39.75%  |
| 501-600     | 103       | 21.11%  |
| 401-500     | 51        | 10.45%  |
| 201-300     | 46        | 9.43%   |
| 351-400     | 24        | 4.92%   |
| Unknown     | 24        | 4.92%   |
| 601-700     | 17        | 3.48%   |
| 701-800     | 15        | 3.07%   |
| 1501-2000   | 8         | 1.64%   |
| 801-900     | 3         | 0.61%   |
| 1001-1500   | 3         | 0.61%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 337       | 76.24%  |
| 16/10   | 53        | 11.99%  |
| Unknown | 19        | 4.3%    |
| 5/4     | 12        | 2.71%   |
| 21/9    | 11        | 2.49%   |
| 4/3     | 5         | 1.13%   |
| 3/2     | 4         | 0.9%    |
| 32/9    | 1         | 0.23%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 130       | 26.1%   |
| 201-250        | 76        | 15.26%  |
| 81-90          | 67        | 13.45%  |
| 301-350        | 47        | 9.44%   |
| 151-200        | 27        | 5.42%   |
| 351-500        | 26        | 5.22%   |
| 71-80          | 24        | 4.82%   |
| Unknown        | 24        | 4.82%   |
| 251-300        | 18        | 3.61%   |
| 141-150        | 13        | 2.61%   |
| 61-70          | 11        | 2.21%   |
| 121-130        | 11        | 2.21%   |
| More than 1000 | 9         | 1.81%   |
| 51-60          | 4         | 0.8%    |
| 501-1000       | 4         | 0.8%    |
| 41-50          | 3         | 0.6%    |
| 131-140        | 3         | 0.6%    |
| 111-120        | 1         | 0.2%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 144       | 29.94%  |
| 121-160       | 133       | 27.65%  |
| 101-120       | 126       | 26.2%   |
| 161-240       | 31        | 6.44%   |
| Unknown       | 24        | 4.99%   |
| More than 240 | 12        | 2.49%   |
| 1-50          | 11        | 2.29%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 363       | 76.91%  |
| 2     | 77        | 16.31%  |
| 0     | 22        | 4.66%   |
| 3     | 9         | 1.91%   |
| 4     | 1         | 0.21%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 250       | 34.97%  |
| Realtek Semiconductor             | 217       | 30.35%  |
| Qualcomm Atheros                  | 68        | 9.51%   |
| Broadcom                          | 54        | 7.55%   |
| Ralink Technology                 | 14        | 1.96%   |
| Nvidia                            | 12        | 1.68%   |
| Broadcom Limited                  | 12        | 1.68%   |
| TP-Link                           | 10        | 1.4%    |
| Ralink                            | 10        | 1.4%    |
| Marvell Technology Group          | 10        | 1.4%    |
| Microsoft                         | 6         | 0.84%   |
| Samsung Electronics               | 5         | 0.7%    |
| Ericsson Business Mobile Networks | 5         | 0.7%    |
| Lenovo                            | 4         | 0.56%   |
| MediaTek                          | 3         | 0.42%   |
| Qualcomm Atheros Communications   | 2         | 0.28%   |
| NetGear                           | 2         | 0.28%   |
| Microchip Technology              | 2         | 0.28%   |
| ICS Advent                        | 2         | 0.28%   |
| DisplayLink                       | 2         | 0.28%   |
| Belkin Components                 | 2         | 0.28%   |
| Xilinx                            | 1         | 0.14%   |
| Xiaomi                            | 1         | 0.14%   |
| Van Ooijen Technische Informatica | 1         | 0.14%   |
| ULi Electronics                   | 1         | 0.14%   |
| Toshiba                           | 1         | 0.14%   |
| T & A Mobile Phones               | 1         | 0.14%   |
| Qualcomm                          | 1         | 0.14%   |
| OnePlus                           | 1         | 0.14%   |
| NetXen Incorporated               | 1         | 0.14%   |
| LSI                               | 1         | 0.14%   |
| LG Electronics                    | 1         | 0.14%   |
| JMicron Technology                | 1         | 0.14%   |
| IMC Networks                      | 1         | 0.14%   |
| Huawei Technologies               | 1         | 0.14%   |
| HMD Global                        | 1         | 0.14%   |
| Hewlett-Packard                   | 1         | 0.14%   |
| Dell                              | 1         | 0.14%   |
| Bose                              | 1         | 0.14%   |
| ASUSTek Computer                  | 1         | 0.14%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 146       | 17.12%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 36        | 4.22%   |
| Intel Wi-Fi 6 AX200                                               | 34        | 3.99%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 29        | 3.4%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 15        | 1.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 15        | 1.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 15        | 1.76%   |
| Intel Wireless 8265 / 8275                                        | 13        | 1.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 12        | 1.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 11        | 1.29%   |
| Intel Wireless 7260                                               | 11        | 1.29%   |
| Realtek 802.11ac NIC                                              | 10        | 1.17%   |
| Intel I211 Gigabit Network Connection                             | 10        | 1.17%   |
| Intel Wireless-AC 9260                                            | 9         | 1.06%   |
| Intel Wireless 7265                                               | 9         | 1.06%   |
| Intel Wi-Fi 6 AX201                                               | 9         | 1.06%   |
| Intel Ethernet Connection I217-LM                                 | 9         | 1.06%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 9         | 1.06%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 8         | 0.94%   |
| Intel Wireless 8260                                               | 8         | 0.94%   |
| Ralink MT7601U Wireless Adapter                                   | 7         | 0.82%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 7         | 0.82%   |
| Nvidia MCP79 Ethernet                                             | 7         | 0.82%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 7         | 0.82%   |
| Intel Wireless 3165                                               | 6         | 0.7%    |
| Intel Ethernet Connection I218-LM                                 | 6         | 0.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 6         | 0.7%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 6         | 0.7%    |
| Broadcom BCM43142 802.11b/g/n                                     | 6         | 0.7%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 5         | 0.59%   |
| Microsoft Xbox 360 Wireless Adapter                               | 5         | 0.59%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 5         | 0.59%   |
| Intel Ethernet Connection (4) I219-V                              | 5         | 0.59%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 0.59%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 5         | 0.59%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 5         | 0.59%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 0.47%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 4         | 0.47%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 0.47%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 192       | 47.41%  |
| Qualcomm Atheros                | 60        | 14.81%  |
| Realtek Semiconductor           | 56        | 13.83%  |
| Broadcom                        | 39        | 9.63%   |
| Ralink Technology               | 14        | 3.46%   |
| TP-Link                         | 10        | 2.47%   |
| Ralink                          | 10        | 2.47%   |
| Microsoft                       | 5         | 1.23%   |
| Broadcom Limited                | 4         | 0.99%   |
| MediaTek                        | 3         | 0.74%   |
| Qualcomm Atheros Communications | 2         | 0.49%   |
| NetGear                         | 2         | 0.49%   |
| Belkin Components               | 2         | 0.49%   |
| Qualcomm                        | 1         | 0.25%   |
| LG Electronics                  | 1         | 0.25%   |
| IMC Networks                    | 1         | 0.25%   |
| Dell                            | 1         | 0.25%   |
| ASUSTek Computer                | 1         | 0.25%   |
| Apple                           | 1         | 0.25%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 34        | 8.31%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 15        | 3.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 15        | 3.67%   |
| Intel Wireless 8265 / 8275                                     | 13        | 3.18%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 12        | 2.93%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 11        | 2.69%   |
| Intel Wireless 7260                                            | 11        | 2.69%   |
| Realtek 802.11ac NIC                                           | 10        | 2.44%   |
| Intel Wireless-AC 9260                                         | 9         | 2.2%    |
| Intel Wireless 7265                                            | 9         | 2.2%    |
| Intel Wi-Fi 6 AX201                                            | 9         | 2.2%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 9         | 2.2%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 8         | 1.96%   |
| Intel Wireless 8260                                            | 8         | 1.96%   |
| Ralink MT7601U Wireless Adapter                                | 7         | 1.71%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 7         | 1.71%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 7         | 1.71%   |
| Intel Wireless 3165                                            | 6         | 1.47%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 6         | 1.47%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 6         | 1.47%   |
| Broadcom BCM43142 802.11b/g/n                                  | 6         | 1.47%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 5         | 1.22%   |
| Microsoft Xbox 360 Wireless Adapter                            | 5         | 1.22%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 5         | 1.22%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 5         | 1.22%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 5         | 1.22%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 4         | 0.98%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 4         | 0.98%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 0.98%   |
| Ralink RT5370 Wireless Adapter                                 | 4         | 0.98%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 4         | 0.98%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 4         | 0.98%   |
| Intel Centrino Ultimate-N 6300                                 | 4         | 0.98%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 4         | 0.98%   |
| TP-Link 802.11ac WLAN Adapter                                  | 3         | 0.73%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 3         | 0.73%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 3         | 0.73%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 3         | 0.73%   |
| Ralink RT2561/RT61 802.11g PCI                                 | 3         | 0.73%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 3         | 0.73%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 194       | 45.97%  |
| Intel                    | 132       | 31.28%  |
| Broadcom                 | 23        | 5.45%   |
| Qualcomm Atheros         | 15        | 3.55%   |
| Nvidia                   | 12        | 2.84%   |
| Marvell Technology Group | 10        | 2.37%   |
| Broadcom Limited         | 9         | 2.13%   |
| Samsung Electronics      | 5         | 1.18%   |
| Lenovo                   | 4         | 0.95%   |
| ICS Advent               | 2         | 0.47%   |
| DisplayLink              | 2         | 0.47%   |
| Xilinx                   | 1         | 0.24%   |
| Xiaomi                   | 1         | 0.24%   |
| ULi Electronics          | 1         | 0.24%   |
| T & A Mobile Phones      | 1         | 0.24%   |
| OnePlus                  | 1         | 0.24%   |
| NetXen Incorporated      | 1         | 0.24%   |
| Microsoft                | 1         | 0.24%   |
| Microchip Technology     | 1         | 0.24%   |
| JMicron Technology       | 1         | 0.24%   |
| Huawei Technologies      | 1         | 0.24%   |
| HMD Global               | 1         | 0.24%   |
| ASIX Electronics         | 1         | 0.24%   |
| ADMtek                   | 1         | 0.24%   |
| 3Com                     | 1         | 0.24%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 146       | 33.87%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 36        | 8.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 29        | 6.73%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 15        | 3.48%   |
| Intel I211 Gigabit Network Connection                             | 10        | 2.32%   |
| Intel Ethernet Connection I217-LM                                 | 9         | 2.09%   |
| Nvidia MCP79 Ethernet                                             | 7         | 1.62%   |
| Intel Ethernet Connection I218-LM                                 | 6         | 1.39%   |
| Intel Ethernet Connection (4) I219-V                              | 5         | 1.16%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 5         | 1.16%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 0.93%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 0.93%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 4         | 0.93%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 0.7%    |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 3         | 0.7%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 3         | 0.7%    |
| Intel I210 Gigabit Network Connection                             | 3         | 0.7%    |
| Intel Ethernet Controller I225-V                                  | 3         | 0.7%    |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.7%    |
| Intel Ethernet Connection I217-V                                  | 3         | 0.7%    |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 0.7%    |
| Intel Ethernet Connection (2) I219-V                              | 3         | 0.7%    |
| Intel Ethernet Connection (2) I218-V                              | 3         | 0.7%    |
| Intel Ethernet Connection (10) I219-V                             | 3         | 0.7%    |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.7%    |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 3         | 0.7%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3         | 0.7%    |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 3         | 0.7%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 0.46%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.46%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.46%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.46%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.46%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.46%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.46%   |
| Nvidia MCP51 Ethernet Controller                                  | 2         | 0.46%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 0.46%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                  | 2         | 0.46%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.46%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.46%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 398       | 50.32%  |
| WiFi     | 380       | 48.04%  |
| Modem    | 13        | 1.64%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 281       | 58.18%  |
| Ethernet | 202       | 41.82%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 268       | 57.88%  |
| 1     | 173       | 37.37%  |
| 3     | 11        | 2.38%   |
| 0     | 9         | 1.94%   |
| 6     | 1         | 0.22%   |
| 4     | 1         | 0.22%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 418       | 89.7%   |
| Yes  | 48        | 10.3%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 149       | 50.51%  |
| Broadcom                        | 22        | 7.46%   |
| Realtek Semiconductor           | 21        | 7.12%   |
| Cambridge Silicon Radio         | 20        | 6.78%   |
| Apple                           | 17        | 5.76%   |
| Qualcomm Atheros Communications | 15        | 5.08%   |
| IMC Networks                    | 14        | 4.75%   |
| Lite-On Technology              | 10        | 3.39%   |
| Dell                            | 7         | 2.37%   |
| Hewlett-Packard                 | 5         | 1.69%   |
| ASUSTek Computer                | 5         | 1.69%   |
| Toshiba                         | 2         | 0.68%   |
| Realtek                         | 2         | 0.68%   |
| Ralink                          | 1         | 0.34%   |
| Foxconn International           | 1         | 0.34%   |
| Foxconn / Hon Hai               | 1         | 0.34%   |
| Edimax Technology               | 1         | 0.34%   |
| Conwise Technology              | 1         | 0.34%   |
| Belkin Components               | 1         | 0.34%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 56        | 18.92%  |
| Intel AX200 Bluetooth                               | 31        | 10.47%  |
| Intel AX201 Bluetooth                               | 25        | 8.45%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 20        | 6.76%   |
| Realtek Bluetooth Radio                             | 13        | 4.39%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 12        | 4.05%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 8         | 2.7%    |
| Qualcomm Atheros  Bluetooth Device                  | 7         | 2.36%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 6         | 2.03%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 6         | 2.03%   |
| Apple Bluetooth USB Host Controller                 | 6         | 2.03%   |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 1.69%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 5         | 1.69%   |
| Intel AX210 Bluetooth                               | 5         | 1.69%   |
| IMC Networks Bluetooth Radio                        | 5         | 1.69%   |
| IMC Networks Bluetooth Device                       | 5         | 1.69%   |
| Apple Bluetooth Host Controller                     | 5         | 1.69%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 4         | 1.35%   |
| Intel Wireless-AC 3168 Bluetooth                    | 4         | 1.35%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 1.35%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 1.35%   |
| Apple Bluetooth HCI                                 | 4         | 1.35%   |
| Realtek RTL8821A Bluetooth                          | 3         | 1.01%   |
| Intel Bluetooth Device                              | 3         | 1.01%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 1.01%   |
| Realtek Bluetooth Radio                             | 2         | 0.68%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 0.68%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 0.68%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 0.68%   |
| IMC Networks Wireless_Device                        | 2         | 0.68%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 0.68%   |
| Dell Wireless 355 Bluetooth                         | 2         | 0.68%   |
| Dell DW375 Bluetooth Module                         | 2         | 0.68%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 0.68%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2         | 0.68%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2         | 0.68%   |
| Toshiba Bluetooth Device                            | 1         | 0.34%   |
| Toshiba BCM43142A0                                  | 1         | 0.34%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.34%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.34%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 331       | 51.16%  |
| AMD                                             | 138       | 21.33%  |
| Nvidia                                          | 112       | 17.31%  |
| C-Media Electronics                             | 6         | 0.93%   |
| Creative Technology                             | 5         | 0.77%   |
| Creative Labs                                   | 5         | 0.77%   |
| Plantronics                                     | 4         | 0.62%   |
| Logitech                                        | 4         | 0.62%   |
| GN Netcom                                       | 4         | 0.62%   |
| Realtek Semiconductor                           | 3         | 0.46%   |
| Lenovo                                          | 3         | 0.46%   |
| Texas Instruments                               | 2         | 0.31%   |
| RODE Microphones                                | 2         | 0.31%   |
| JMTek                                           | 2         | 0.31%   |
| Ensoniq                                         | 2         | 0.31%   |
| VIA Technologies                                | 1         | 0.15%   |
| ULi Electronics                                 | 1         | 0.15%   |
| Turtle Beach                                    | 1         | 0.15%   |
| Thesycon Systemsoftware & Consulting            | 1         | 0.15%   |
| Sony                                            | 1         | 0.15%   |
| SAVITECH                                        | 1         | 0.15%   |
| Razer USA                                       | 1         | 0.15%   |
| No brand                                        | 1         | 0.15%   |
| Native Instruments                              | 1         | 0.15%   |
| Micronas                                        | 1         | 0.15%   |
| M-Audio                                         | 1         | 0.15%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.15%   |
| Kingston Technology                             | 1         | 0.15%   |
| Giga-Byte Technology                            | 1         | 0.15%   |
| Focusrite-Novation                              | 1         | 0.15%   |
| FiiO Electronics Technology                     | 1         | 0.15%   |
| ESS Technology                                  | 1         | 0.15%   |
| Corsair                                         | 1         | 0.15%   |
| Blue Microphones                                | 1         | 0.15%   |
| BEHRINGER International                         | 1         | 0.15%   |
| AudioQuest                                      | 1         | 0.15%   |
| AUDIOLAB                                        | 1         | 0.15%   |
| Audio-Technica                                  | 1         | 0.15%   |
| Audient                                         | 1         | 0.15%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                   | 41        | 5.41%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 39        | 5.15%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 38        | 5.01%   |
| AMD Family 17h/19h HD Audio Controller                                            | 32        | 4.22%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 21        | 2.77%   |
| AMD Starship/Matisse HD Audio Controller                                          | 17        | 2.24%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 17        | 2.24%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 16        | 2.11%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 16        | 2.11%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 15        | 1.98%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 15        | 1.98%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 14        | 1.85%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 14        | 1.85%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 14        | 1.85%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 12        | 1.58%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 12        | 1.58%   |
| Intel Cannon Lake PCH cAVS                                                        | 11        | 1.45%   |
| AMD FCH Azalia Controller                                                         | 11        | 1.45%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 11        | 1.45%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 10        | 1.32%   |
| Intel Haswell-ULT HD Audio Controller                                             | 10        | 1.32%   |
| Intel 8 Series HD Audio Controller                                                | 10        | 1.32%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 10        | 1.32%   |
| Nvidia TU106 High Definition Audio Controller                                     | 9         | 1.19%   |
| Nvidia GF108 High Definition Audio Controller                                     | 9         | 1.19%   |
| Intel Comet Lake PCH cAVS                                                         | 9         | 1.19%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 9         | 1.19%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                  | 9         | 1.19%   |
| Nvidia GP106 High Definition Audio Controller                                     | 8         | 1.06%   |
| Nvidia GM204 High Definition Audio Controller                                     | 8         | 1.06%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 8         | 1.06%   |
| AMD Kabini HDMI/DP Audio                                                          | 8         | 1.06%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 8         | 1.06%   |
| Nvidia MCP79 High Definition Audio                                                | 7         | 0.92%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 7         | 0.92%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 7         | 0.92%   |
| Intel Broadwell-U Audio Controller                                                | 7         | 0.92%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 7         | 0.92%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 7         | 0.92%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 6         | 0.79%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 55        | 20%     |
| SK hynix            | 42        | 15.27%  |
| Unknown             | 30        | 10.91%  |
| Micron Technology   | 28        | 10.18%  |
| Crucial             | 28        | 10.18%  |
| Corsair             | 27        | 9.82%   |
| Kingston            | 22        | 8%      |
| Ramaxel Technology  | 7         | 2.55%   |
| G.Skill             | 7         | 2.55%   |
| Elpida              | 5         | 1.82%   |
| Unknown (ABCD)      | 3         | 1.09%   |
| Team                | 3         | 1.09%   |
| Patriot             | 3         | 1.09%   |
| Nanya Technology    | 3         | 1.09%   |
| Apacer              | 2         | 0.73%   |
| A-DATA Technology   | 2         | 0.73%   |
| A Force             | 2         | 0.73%   |
| Transcend           | 1         | 0.36%   |
| Toshiba             | 1         | 0.36%   |
| SHARETRONIC         | 1         | 0.36%   |
| OSV                 | 1         | 0.36%   |
| Infineon            | 1         | 0.36%   |
| CSX                 | 1         | 0.36%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 5         | 1.67%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 5         | 1.67%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s         | 5         | 1.67%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 1%      |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 1%      |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 1%      |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 3         | 1%      |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s            | 3         | 1%      |
| Corsair RAM CM4X16GE2666C18S4 16GB SODIMM DDR4 2667MT/s          | 3         | 1%      |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 2         | 0.67%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                          | 2         | 0.67%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 2         | 0.67%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                           | 2         | 0.67%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 0.67%   |
| Team RAM Elite-1333 4GB DIMM DDR3 1333MT/s                       | 2         | 0.67%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s             | 2         | 0.67%   |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s          | 2         | 0.67%   |
| SK hynix RAM HMT351U6CFR8C-H9 4096MB DIMM DDR3 1600MT/s          | 2         | 0.67%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 0.67%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 2         | 0.67%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.67%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.67%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.67%   |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s            | 2         | 0.67%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 2         | 0.67%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.67%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.67%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.67%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 2         | 0.67%   |
| Micron RAM 8ATF1G64HZ-2G3E1 8GB SODIMM DDR4 2400MT/s             | 2         | 0.67%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 2         | 0.67%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 2         | 0.67%   |
| G.Skill RAM F3-12800CL9-4GBXL 4GB DIMM DDR3 1867MT/s             | 2         | 0.67%   |
| Elpida RAM EBJ41UF8BDU0-DJ-F 4GB Chip DDR3 1333MT/s              | 2         | 0.67%   |
| Crucial RAM CT51264BD160B.C16F 4GB DIMM DDR3 1600MT/s            | 2         | 0.67%   |
| Crucial RAM CT16G4SFRA32A.M16FRS 16GB SODIMM DDR4 3200MT/s       | 2         | 0.67%   |
| Corsair RAM CMK16GX4M2D3000C16 8GB DIMM DDR4 3200MT/s            | 2         | 0.67%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.33%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                             | 1         | 0.33%   |
| Unknown RAM Module 8192MB Row Of Chips LPDDR4 4267MT/s           | 1         | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 108       | 44.26%  |
| DDR3    | 76        | 31.15%  |
| DDR2    | 14        | 5.74%   |
| Unknown | 12        | 4.92%   |
| LPDDR4  | 11        | 4.51%   |
| SDRAM   | 10        | 4.1%    |
| LPDDR3  | 7         | 2.87%   |
| DDR     | 3         | 1.23%   |
| DRAM    | 2         | 0.82%   |
| DDR5    | 1         | 0.41%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 137       | 56.15%  |
| DIMM         | 83        | 34.02%  |
| Row Of Chips | 18        | 7.38%   |
| Chip         | 4         | 1.64%   |
| Unknown      | 2         | 0.82%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 90        | 33.96%  |
| 4096  | 74        | 27.92%  |
| 16384 | 39        | 14.72%  |
| 2048  | 36        | 13.58%  |
| 1024  | 12        | 4.53%   |
| 32768 | 10        | 3.77%   |
| 128   | 2         | 0.75%   |
| 512   | 1         | 0.38%   |
| 256   | 1         | 0.38%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 51        | 19.1%   |
| 2667    | 35        | 13.11%  |
| 3200    | 28        | 10.49%  |
| 2400    | 23        | 8.61%   |
| 2133    | 17        | 6.37%   |
| 1333    | 14        | 5.24%   |
| 800     | 12        | 4.49%   |
| 667     | 10        | 3.75%   |
| 1334    | 8         | 3%      |
| 4267    | 7         | 2.62%   |
| 3600    | 7         | 2.62%   |
| 3266    | 6         | 2.25%   |
| 1867    | 6         | 2.25%   |
| 1067    | 5         | 1.87%   |
| Unknown | 5         | 1.87%   |
| 3466    | 3         | 1.12%   |
| 1800    | 3         | 1.12%   |
| 533     | 3         | 1.12%   |
| 8400    | 2         | 0.75%   |
| 4800    | 2         | 0.75%   |
| 4199    | 2         | 0.75%   |
| 3400    | 2         | 0.75%   |
| 1866    | 2         | 0.75%   |
| 1066    | 2         | 0.75%   |
| 975     | 2         | 0.75%   |
| 3800    | 1         | 0.37%   |
| 3733    | 1         | 0.37%   |
| 3000    | 1         | 0.37%   |
| 2933    | 1         | 0.37%   |
| 2733    | 1         | 0.37%   |
| 2666    | 1         | 0.37%   |
| 2267    | 1         | 0.37%   |
| 2048    | 1         | 0.37%   |
| 1639    | 1         | 0.37%   |
| 400     | 1         | 0.37%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 2         | 40%     |
| STMicroelectronics  | 1         | 20%     |
| Samsung Electronics | 1         | 20%     |
| Canon               | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 20%     |
| Samsung M2070 Series                                      | 1         | 20%     |
| Canon PIXMA MG2500 Series                                 | 1         | 20%     |
| Brother MFC-L2700DW                                       | 1         | 20%     |
| Brother HL-L2340D series                                  | 1         | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 220 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 64        | 22.46%  |
| Realtek Semiconductor                  | 34        | 11.93%  |
| IMC Networks                           | 25        | 8.77%   |
| Acer                                   | 24        | 8.42%   |
| Microdia                               | 23        | 8.07%   |
| Logitech                               | 20        | 7.02%   |
| Apple                                  | 15        | 5.26%   |
| Sunplus Innovation Technology          | 11        | 3.86%   |
| Quanta                                 | 9         | 3.16%   |
| Cheng Uei Precision Industry (Foxlink) | 8         | 2.81%   |
| Suyin                                  | 6         | 2.11%   |
| Samsung Electronics                    | 6         | 2.11%   |
| ALi                                    | 5         | 1.75%   |
| Syntek                                 | 4         | 1.4%    |
| Microsoft                              | 4         | 1.4%    |
| Lite-On Technology                     | 4         | 1.4%    |
| Silicon Motion                         | 3         | 1.05%   |
| Ricoh                                  | 3         | 1.05%   |
| Generalplus Technology                 | 2         | 0.7%    |
| Creative Technology                    | 2         | 0.7%    |
| Z-Star Microelectronics                | 1         | 0.35%   |
| Y Media                                | 1         | 0.35%   |
| USB3.0 HD Audio Capture                | 1         | 0.35%   |
| Unknown                                | 1         | 0.35%   |
| Trust                                  | 1         | 0.35%   |
| SunplusIT                              | 1         | 0.35%   |
| Razer USA                              | 1         | 0.35%   |
| Nikon                                  | 1         | 0.35%   |
| Lenovo                                 | 1         | 0.35%   |
| GenesysLogic Technology                | 1         | 0.35%   |
| GEMBIRD                                | 1         | 0.35%   |
| DigiTech                               | 1         | 0.35%   |
| Alcor Micro                            | 1         | 0.35%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD               | 13        | 4.51%   |
| Chicony Integrated Camera                  | 11        | 3.82%   |
| Microdia Integrated_Webcam_HD              | 10        | 3.47%   |
| IMC Networks Integrated Camera             | 10        | 3.47%   |
| Apple Built-in iSight                      | 10        | 3.47%   |
| Acer Integrated Camera                     | 8         | 2.78%   |
| Chicony USB2.0 Camera                      | 7         | 2.43%   |
| Chicony HD Webcam                          | 7         | 2.43%   |
| Samsung Galaxy series, misc. (MTP mode)    | 6         | 2.08%   |
| Logitech HD Pro Webcam C920                | 6         | 2.08%   |
| Microdia Integrated Webcam                 | 4         | 1.39%   |
| IMC Networks USB2.0 HD UVC WebCam          | 4         | 1.39%   |
| Acer EasyCamera                            | 4         | 1.39%   |
| Sunplus Integrated_Webcam_HD               | 3         | 1.04%   |
| Realtek Integrated Webcam HD               | 3         | 1.04%   |
| Microsoft LifeCam HD-3000                  | 3         | 1.04%   |
| Logitech Webcam C270                       | 3         | 1.04%   |
| Lite-On HP HD Camera                       | 3         | 1.04%   |
| Chicony USB2.0 HD UVC WebCam               | 3         | 1.04%   |
| Chicony Lenovo EasyCamera                  | 3         | 1.04%   |
| Chicony EasyCamera                         | 3         | 1.04%   |
| Apple FaceTime HD Camera (Built-in)        | 3         | 1.04%   |
| ALi WebCam                                 | 3         | 1.04%   |
| Acer BisonCam, NB Pro                      | 3         | 1.04%   |
| Syntek Integrated Camera                   | 2         | 0.69%   |
| Syntek EasyCamera                          | 2         | 0.69%   |
| Suyin HP Truevision HD                     | 2         | 0.69%   |
| Realtek USB2.0 HD UVC WebCam               | 2         | 0.69%   |
| Realtek HP Truevision HD integrated webcam | 2         | 0.69%   |
| Realtek HD WebCam                          | 2         | 0.69%   |
| Quanta HP Wide Vision HD Camera            | 2         | 0.69%   |
| Quanta HP Webcam                           | 2         | 0.69%   |
| Logitech Webcam C925e                      | 2         | 0.69%   |
| Logitech C922 Pro Stream Webcam            | 2         | 0.69%   |
| Logitech B525 HD Webcam                    | 2         | 0.69%   |
| IMC Networks USB2.0 VGA UVC WebCam         | 2         | 0.69%   |
| IMC Networks TOSHIBA Web Camera - HD       | 2         | 0.69%   |
| IMC Networks EasyCamera                    | 2         | 0.69%   |
| Creative Live! Cam Sync HD [VF0770]        | 2         | 0.69%   |
| Chicony USB 2.0 Camera                     | 2         | 0.69%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 22        | 34.92%  |
| Validity Sensors           | 18        | 28.57%  |
| Shenzhen Goodix Technology | 11        | 17.46%  |
| Upek                       | 4         | 6.35%   |
| LighTuning Technology      | 2         | 3.17%   |
| Elan Microelectronics      | 2         | 3.17%   |
| AuthenTec                  | 2         | 3.17%   |
| STMicroelectronics         | 1         | 1.59%   |
| Focal-systems.Corp         | 1         | 1.59%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Unknown                                                    | 9         | 14.29%  |
| Shenzhen Goodix FingerPrint                                | 6         | 9.52%   |
| Validity Sensors VFS495 Fingerprint Reader                 | 4         | 6.35%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 4         | 6.35%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 4         | 6.35%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 4.76%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 3         | 4.76%   |
| Shenzhen Goodix  FingerPrint Device                        | 3         | 4.76%   |
| Validity Sensors VFS5011 Fingerprint Reader                | 2         | 3.17%   |
| Validity Sensors VFS451 Fingerprint Reader                 | 2         | 3.17%   |
| Validity Sensors VFS101 Fingerprint Reader                 | 2         | 3.17%   |
| Validity Sensors Synaptics WBDI                            | 2         | 3.17%   |
| Synaptics  WBDI                                            | 2         | 3.17%   |
| Shenzhen Goodix Fingerprint Reader                         | 2         | 3.17%   |
| LighTuning EgisTec_ES603                                   | 2         | 3.17%   |
| Elan ELAN:Fingerprint                                      | 2         | 3.17%   |
| AuthenTec Fingerprint Sensor                               | 2         | 3.17%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 1         | 1.59%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 1         | 1.59%   |
| Validity Sensors VFS301 Fingerprint Reader                 | 1         | 1.59%   |
| Validity Sensors VFS300 Fingerprint Reader                 | 1         | 1.59%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 1         | 1.59%   |
| Validity Sensors Fingerprint scanner                       | 1         | 1.59%   |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 1         | 1.59%   |
| STMicroelectronics Fingerprint Reader                      | 1         | 1.59%   |
| Focal-systems.Corp FT9201Fingerprint.                      | 1         | 1.59%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 19        | 52.78%  |
| Alcor Micro | 7         | 19.44%  |
| Upek        | 5         | 13.89%  |
| O2 Micro    | 4         | 11.11%  |
| Lenovo      | 1         | 2.78%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 58200                                                               | 7         | 19.44%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 7         | 19.44%  |
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 16.67%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 13.89%  |
| Broadcom 5880                                                                | 4         | 11.11%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 8.33%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 5.56%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 2.78%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 2.78%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 310       | 65.82%  |
| 1     | 130       | 27.6%   |
| 2     | 24        | 5.1%    |
| 3     | 7         | 1.49%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 62        | 33.33%  |
| Net/wireless             | 36        | 19.35%  |
| Chipcard                 | 31        | 16.67%  |
| Graphics card            | 27        | 14.52%  |
| Multimedia controller    | 10        | 5.38%   |
| Communication controller | 5         | 2.69%   |
| Storage                  | 4         | 2.15%   |
| Camera                   | 4         | 2.15%   |
| Card reader              | 3         | 1.61%   |
| Bluetooth                | 2         | 1.08%   |
| Net/ethernet             | 1         | 0.54%   |
| Modem                    | 1         | 0.54%   |

