Elementary - Tested Hardware & Statistics (Desktops)
----------------------------------------------------

A project to collect tested hardware configurations for Elementary.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 1017

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| IceWhale T... | ZBB001-BK30032 ZMB          | [89a72c23bf](https://linux-hardware.org/?probe=89a72c23bf) | Dec 29, 2025 |
| Dell          | 0773VG A00                  | [04673177d3](https://linux-hardware.org/?probe=04673177d3) | Dec 24, 2025 |
| Lenovo        | MAHOBAY NO DPK              | [479ecf2419](https://linux-hardware.org/?probe=479ecf2419) | Dec 06, 2025 |
| Biostar       | H61MLV2                     | [d6a9c79bdd](https://linux-hardware.org/?probe=d6a9c79bdd) | Dec 05, 2025 |
| ASUSTek       | PRIME B450M-A II            | [9e77f10d86](https://linux-hardware.org/?probe=9e77f10d86) | Dec 02, 2025 |
| ASUSTek       | PRIME B450M-A II            | [a110c5abe4](https://linux-hardware.org/?probe=a110c5abe4) | Dec 02, 2025 |
| Intel         | Unknown                     | [8a2554c6a8](https://linux-hardware.org/?probe=8a2554c6a8) | Nov 30, 2025 |
| ASUSTek       | CM6870                      | [c626fb7e6a](https://linux-hardware.org/?probe=c626fb7e6a) | Nov 29, 2025 |
| Intel         | H55                         | [64547cb270](https://linux-hardware.org/?probe=64547cb270) | Nov 24, 2025 |
| Intel         | H55                         | [03919b1a0c](https://linux-hardware.org/?probe=03919b1a0c) | Nov 22, 2025 |
| ASUSTek       | ROG STRIX X870E-E GAMING... | [715c8abc74](https://linux-hardware.org/?probe=715c8abc74) | Nov 18, 2025 |
| ASUSTek       | ROG STRIX X870E-E GAMING... | [e757512b85](https://linux-hardware.org/?probe=e757512b85) | Nov 18, 2025 |
| ASRock        | M3A UCC                     | [731a345406](https://linux-hardware.org/?probe=731a345406) | Nov 13, 2025 |
| ASUSTek       | K30BF_M32BF                 | [9c576d9df2](https://linux-hardware.org/?probe=9c576d9df2) | Nov 10, 2025 |
| Apple         | Mac-F42C88C8 Proto1         | [aac0546a3d](https://linux-hardware.org/?probe=aac0546a3d) | Nov 08, 2025 |
| ASRock        | B650 LiveMixer              | [4c9c02fe5f](https://linux-hardware.org/?probe=4c9c02fe5f) | Oct 31, 2025 |
| ASUSTek       | TUF B450-PLUS GAMING        | [0bce74370a](https://linux-hardware.org/?probe=0bce74370a) | Oct 24, 2025 |
| Gigabyte      | B760M DS3H DDR4             | [d47e2c04ff](https://linux-hardware.org/?probe=d47e2c04ff) | Oct 20, 2025 |
| Huanan        | X79-4MT (INTEL Xeon E5/C... | [0835c7c585](https://linux-hardware.org/?probe=0835c7c585) | Oct 20, 2025 |
| Dell          | 0XHGV1 A00                  | [d0fff0ec6e](https://linux-hardware.org/?probe=d0fff0ec6e) | Oct 19, 2025 |
| HP            | 198E                        | [8dfae8405a](https://linux-hardware.org/?probe=8dfae8405a) | Oct 19, 2025 |
| MSI           | H170A GAMING PRO            | [54178d60d8](https://linux-hardware.org/?probe=54178d60d8) | Oct 16, 2025 |
| ASRock        | B850I Lightning WiFi        | [05ba465541](https://linux-hardware.org/?probe=05ba465541) | Oct 15, 2025 |
| OEM           | Unknown                     | [7cf476e7d5](https://linux-hardware.org/?probe=7cf476e7d5) | Oct 13, 2025 |
| MSI           | H170A GAMING PRO            | [714ce241a1](https://linux-hardware.org/?probe=714ce241a1) | Oct 13, 2025 |
| ASRock        | B450M Steel Legend          | [f0520b7456](https://linux-hardware.org/?probe=f0520b7456) | Oct 02, 2025 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | [de64494634](https://linux-hardware.org/?probe=de64494634) | Sep 27, 2025 |
| Gigabyte      | 945GCM-S2C                  | [58f87f9fe5](https://linux-hardware.org/?probe=58f87f9fe5) | Sep 27, 2025 |
| MSI           | PRO B650M-A WIFI            | [b813af4e2c](https://linux-hardware.org/?probe=b813af4e2c) | Sep 24, 2025 |
| MSI           | PRO B650M-A WIFI            | [9e761287ba](https://linux-hardware.org/?probe=9e761287ba) | Sep 24, 2025 |
| ASUSTek       | P8B75-V                     | [55a17b8069](https://linux-hardware.org/?probe=55a17b8069) | Sep 22, 2025 |
| ASUSTek       | P8B75-V                     | [5017ed6516](https://linux-hardware.org/?probe=5017ed6516) | Sep 22, 2025 |
| Gigabyte      | 945GCM-S2C                  | [9f6dce5f59](https://linux-hardware.org/?probe=9f6dce5f59) | Sep 21, 2025 |
| HP            | 198E                        | [cfe7648075](https://linux-hardware.org/?probe=cfe7648075) | Sep 20, 2025 |
| Dell          | 0YJMC0 A02                  | [cbdc17bf9f](https://linux-hardware.org/?probe=cbdc17bf9f) | Sep 14, 2025 |
| Dell          | 0YJMC0 A02                  | [e9f6bbf8b4](https://linux-hardware.org/?probe=e9f6bbf8b4) | Sep 01, 2025 |
| MAXSUN        | MS-MoDT 12450H ITX WIFI ... | [e5fc66ced9](https://linux-hardware.org/?probe=e5fc66ced9) | Sep 01, 2025 |
| ASRock        | Z390 Phantom Gaming-ITX/... | [711f7fd312](https://linux-hardware.org/?probe=711f7fd312) | Aug 29, 2025 |
| HP            | 1497                        | [e80f663d27](https://linux-hardware.org/?probe=e80f663d27) | Aug 24, 2025 |
| HP            | 1497                        | [6a610b0d64](https://linux-hardware.org/?probe=6a610b0d64) | Aug 24, 2025 |
| Pegatron      | IPM41-D3                    | [d411498552](https://linux-hardware.org/?probe=d411498552) | Aug 23, 2025 |
| ASUSTek       | ProArt B760-CREATOR D4      | [7e96a291c7](https://linux-hardware.org/?probe=7e96a291c7) | Aug 23, 2025 |
| Pegatron      | IPM41-D3                    | [422732bfd6](https://linux-hardware.org/?probe=422732bfd6) | Aug 21, 2025 |
| Unknown       | Unknown                     | [1c3d5ce606](https://linux-hardware.org/?probe=1c3d5ce606) | Aug 17, 2025 |
| Intel         | DH55HC AAE70933-504         | [0fdf5fa883](https://linux-hardware.org/?probe=0fdf5fa883) | Aug 15, 2025 |
| HP            | 83EC                        | [e31cc86909](https://linux-hardware.org/?probe=e31cc86909) | Aug 14, 2025 |
| HP            | 83EC                        | [5cbe94892f](https://linux-hardware.org/?probe=5cbe94892f) | Aug 14, 2025 |
| MAXSUN        | MS-MoDT 12450H ITX WIFI ... | [4b97e2df68](https://linux-hardware.org/?probe=4b97e2df68) | Aug 13, 2025 |
| ASUSTek       | PRIME H110M2/FPT            | [9dff3c78bb](https://linux-hardware.org/?probe=9dff3c78bb) | Aug 12, 2025 |
| HP            | 1495                        | [870edad545](https://linux-hardware.org/?probe=870edad545) | Aug 12, 2025 |
| ASRock        | B450M Pro4 R2.0             | [0e45e523e2](https://linux-hardware.org/?probe=0e45e523e2) | Aug 08, 2025 |
| BOSCH         | CCTV APP AEL1 1             | [d6029846a9](https://linux-hardware.org/?probe=d6029846a9) | Aug 07, 2025 |
| MSI           | B450M PRO-M2 MAX            | [0ea8cc0ee0](https://linux-hardware.org/?probe=0ea8cc0ee0) | Aug 06, 2025 |
| BOSCH         | CCTV APP AEL1 1             | [fc70f237b5](https://linux-hardware.org/?probe=fc70f237b5) | Aug 06, 2025 |
| Gigabyte      | X570 AORUS ELITE            | [77e60f03ef](https://linux-hardware.org/?probe=77e60f03ef) | Aug 04, 2025 |
| ASUSTek       | CM6870                      | [02973bf4ae](https://linux-hardware.org/?probe=02973bf4ae) | Jul 31, 2025 |
| HP            | 1495                        | [d40b21b085](https://linux-hardware.org/?probe=d40b21b085) | Jul 30, 2025 |
| ASUSTek       | TUF Gaming Z790-PLUS D4     | [6cd807c3c7](https://linux-hardware.org/?probe=6cd807c3c7) | Jul 27, 2025 |
| ASUSTek       | PRIME B550M-K               | [e78bc0db73](https://linux-hardware.org/?probe=e78bc0db73) | Jul 27, 2025 |
| Biostar       | G41-M7                      | [1f6d011ff4](https://linux-hardware.org/?probe=1f6d011ff4) | Jul 26, 2025 |
| HP            | 0B4Ch D                     | [3ab2a33cab](https://linux-hardware.org/?probe=3ab2a33cab) | Jul 25, 2025 |
| Unknown       | Unknown                     | [a298dd6726](https://linux-hardware.org/?probe=a298dd6726) | Jul 24, 2025 |
| Dell          | 00V62H A01                  | [5a65caa05f](https://linux-hardware.org/?probe=5a65caa05f) | Jul 21, 2025 |
| HP            | 8169                        | [0d335d8068](https://linux-hardware.org/?probe=0d335d8068) | Jul 19, 2025 |
| Intel         | H81                         | [05f057c7d1](https://linux-hardware.org/?probe=05f057c7d1) | Jul 14, 2025 |
| ASRock        | B450M Steel Legend          | [834b575ff6](https://linux-hardware.org/?probe=834b575ff6) | Jul 13, 2025 |
| Positivo      | POS-PIH81DL                 | [4837b80079](https://linux-hardware.org/?probe=4837b80079) | Jul 12, 2025 |
| Gigabyte      | X79-UD3                     | [059ea5dfe8](https://linux-hardware.org/?probe=059ea5dfe8) | Jul 12, 2025 |
| Intel         | H81                         | [338632b69c](https://linux-hardware.org/?probe=338632b69c) | Jul 11, 2025 |
| MSI           | MPG Z790 EDGE TI MAX WIF... | [77d77a702d](https://linux-hardware.org/?probe=77d77a702d) | Jul 10, 2025 |
| Dell          | 0M9KCM A02                  | [c05464dda3](https://linux-hardware.org/?probe=c05464dda3) | Jul 08, 2025 |
| HP            | 0B4Ch D                     | [459fae43ed](https://linux-hardware.org/?probe=459fae43ed) | Jul 06, 2025 |
| HP            | 0B4Ch D                     | [36e98b328d](https://linux-hardware.org/?probe=36e98b328d) | Jul 06, 2025 |
| HP            | 0AECh D                     | [957baad019](https://linux-hardware.org/?probe=957baad019) | Jul 05, 2025 |
| MSI           | X470 GAMING PLUS MAX        | [06e7cc2c95](https://linux-hardware.org/?probe=06e7cc2c95) | Jul 01, 2025 |
| Gigabyte      | B450M GAMING                | [78e88aacc8](https://linux-hardware.org/?probe=78e88aacc8) | Jun 27, 2025 |
| Gigabyte      | EX58-UD3R                   | [11cd8d00eb](https://linux-hardware.org/?probe=11cd8d00eb) | Jun 22, 2025 |
| MSI           | X299 GAMING PRO CARBON      | [624e16050d](https://linux-hardware.org/?probe=624e16050d) | Jun 18, 2025 |
| ASUSTek       | PRIME B550M-A WIFI II       | [b045f74b75](https://linux-hardware.org/?probe=b045f74b75) | Jun 15, 2025 |
| HP            | 8265                        | [330c6a4a61](https://linux-hardware.org/?probe=330c6a4a61) | Jun 13, 2025 |
| ASUSTek       | PRIME Z590-P                | [4cd3dc7b78](https://linux-hardware.org/?probe=4cd3dc7b78) | Jun 01, 2025 |
| MSI           | Z390-A PRO                  | [6353bbffb5](https://linux-hardware.org/?probe=6353bbffb5) | Jun 01, 2025 |
| HP            | 8184 X4                     | [2902fda187](https://linux-hardware.org/?probe=2902fda187) | Jun 01, 2025 |
| MSI           | Z77A-G43                    | [bb580382c5](https://linux-hardware.org/?probe=bb580382c5) | May 30, 2025 |
| ASRock        | B450M Steel Legend          | [11e8c05339](https://linux-hardware.org/?probe=11e8c05339) | May 27, 2025 |
| ASRock        | B760M-ITX/D4 WiFi           | [19fb1a3c33](https://linux-hardware.org/?probe=19fb1a3c33) | May 27, 2025 |
| ASUSTek       | M5A78L-M/USB3               | [17f1322f85](https://linux-hardware.org/?probe=17f1322f85) | May 24, 2025 |
| ASRock        | B850M-X WiFi                | [b33d0756d7](https://linux-hardware.org/?probe=b33d0756d7) | May 24, 2025 |
| ASRock        | B850M-X WiFi                | [8ea3eb0e6a](https://linux-hardware.org/?probe=8ea3eb0e6a) | May 24, 2025 |
| Gigabyte      | X58-USB3                    | [704b2100ab](https://linux-hardware.org/?probe=704b2100ab) | May 24, 2025 |
| Gigabyte      | X58-USB3                    | [27786c7b04](https://linux-hardware.org/?probe=27786c7b04) | May 24, 2025 |
| ASUSTek       | M5A78L-M/USB3               | [7a99f1fc83](https://linux-hardware.org/?probe=7a99f1fc83) | May 24, 2025 |
| ASUSTek       | PRIME B760M-A WIFI D4       | [9f67585ccd](https://linux-hardware.org/?probe=9f67585ccd) | May 23, 2025 |
| ASUSTek       | PRIME B550M-A               | [96bbce6853](https://linux-hardware.org/?probe=96bbce6853) | May 22, 2025 |
| Gigabyte      | G31M-ES2L                   | [f53bf88296](https://linux-hardware.org/?probe=f53bf88296) | May 18, 2025 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | [a01996b9ce](https://linux-hardware.org/?probe=a01996b9ce) | May 10, 2025 |
| Lenovo        | SDK0J40705 WIN 342503991... | [566728e595](https://linux-hardware.org/?probe=566728e595) | May 10, 2025 |
| HP            | 83E2                        | [45ae65d295](https://linux-hardware.org/?probe=45ae65d295) | May 06, 2025 |
| Daten Tecn... | DB85PRO                     | [16ac21b0b7](https://linux-hardware.org/?probe=16ac21b0b7) | May 02, 2025 |
| NEC Comput... | MS-7479MH                   | [2263a0ef49](https://linux-hardware.org/?probe=2263a0ef49) | Apr 26, 2025 |
| ASRock        | X58 Extreme6                | [24161c8dff](https://linux-hardware.org/?probe=24161c8dff) | Apr 25, 2025 |
| Gigabyte      | H97-HD3                     | [95ef8ff863](https://linux-hardware.org/?probe=95ef8ff863) | Apr 23, 2025 |
| ASUSTek       | PRIME B760M-AJ D4           | [e9f4177ebc](https://linux-hardware.org/?probe=e9f4177ebc) | Apr 21, 2025 |
| ASRock        | H81M-HDS R2.0               | [f305fbfa16](https://linux-hardware.org/?probe=f305fbfa16) | Apr 19, 2025 |
| MSI           | H510M PLUS V3               | [dce1906518](https://linux-hardware.org/?probe=dce1906518) | Apr 18, 2025 |
| HP            | 3397                        | [a98b71652e](https://linux-hardware.org/?probe=a98b71652e) | Apr 18, 2025 |
| Gigabyte      | Z390 UD                     | [1753f52781](https://linux-hardware.org/?probe=1753f52781) | Apr 15, 2025 |
| ECS           | A790GXM-AD3                 | [791013e3d7](https://linux-hardware.org/?probe=791013e3d7) | Apr 12, 2025 |
| ASUSTek       | B85M-E                      | [40978b1318](https://linux-hardware.org/?probe=40978b1318) | Apr 12, 2025 |
| ASUSTek       | D320MT-K                    | [00fa5036d1](https://linux-hardware.org/?probe=00fa5036d1) | Apr 09, 2025 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [36fbf4f170](https://linux-hardware.org/?probe=36fbf4f170) | Apr 06, 2025 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [4c6474d7fa](https://linux-hardware.org/?probe=4c6474d7fa) | Apr 06, 2025 |
| Dell          | 0C96W1 A03                  | [0105def95d](https://linux-hardware.org/?probe=0105def95d) | Apr 02, 2025 |
| Lenovo        | 32CB NOK                    | [c485697e16](https://linux-hardware.org/?probe=c485697e16) | Mar 31, 2025 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [ed4a144bef](https://linux-hardware.org/?probe=ed4a144bef) | Mar 24, 2025 |
| Gigabyte      | H110M-S2H-CF                | [01d7534529](https://linux-hardware.org/?probe=01d7534529) | Mar 18, 2025 |
| HP            | 3031h                       | [cf6acd606f](https://linux-hardware.org/?probe=cf6acd606f) | Mar 16, 2025 |
| ASUSTek       | P8H61-MX R2.0               | [cc93e40505](https://linux-hardware.org/?probe=cc93e40505) | Mar 13, 2025 |
| Dell          | 00V62H A01                  | [d8823e749c](https://linux-hardware.org/?probe=d8823e749c) | Mar 07, 2025 |
| Dell          | 0WR7PY A01                  | [bc78df3255](https://linux-hardware.org/?probe=bc78df3255) | Mar 01, 2025 |
| MSI           | PRO A620M-E                 | [bd6c9835d7](https://linux-hardware.org/?probe=bd6c9835d7) | Feb 28, 2025 |
| ASUSTek       | H110M-A                     | [87343af499](https://linux-hardware.org/?probe=87343af499) | Feb 27, 2025 |
| Dell          | 00V62H A01                  | [3ac96a7d81](https://linux-hardware.org/?probe=3ac96a7d81) | Feb 26, 2025 |
| Lenovo        | 0x30F617AA NOK              | [3ecccff26d](https://linux-hardware.org/?probe=3ecccff26d) | Feb 25, 2025 |
| Dell          | 0WR7PY A01                  | [fe278f1e68](https://linux-hardware.org/?probe=fe278f1e68) | Feb 24, 2025 |
| Biostar       | A58MD                       | [79d6ec6b7a](https://linux-hardware.org/?probe=79d6ec6b7a) | Feb 22, 2025 |
| Gigabyte      | Z77MX-D3H                   | [6a27bc1436](https://linux-hardware.org/?probe=6a27bc1436) | Feb 13, 2025 |
| Lenovo        | SDK0E50510 WIN              | [809dfbac41](https://linux-hardware.org/?probe=809dfbac41) | Feb 07, 2025 |
| Intel         | D946GZIS AAD66165-502       | [d3539a4af6](https://linux-hardware.org/?probe=d3539a4af6) | Feb 04, 2025 |
| ASUSTek       | M5A78L-M/USB3               | [52786de2ac](https://linux-hardware.org/?probe=52786de2ac) | Feb 03, 2025 |
| ASUSTek       | M5A78L-M/USB3               | [7f6ddaaa50](https://linux-hardware.org/?probe=7f6ddaaa50) | Jan 25, 2025 |
| Acer          | Veriton N4640G              | [d6ef6686cb](https://linux-hardware.org/?probe=d6ef6686cb) | Jan 24, 2025 |
| OEM           | X79-Turbo                   | [15b2eded0d](https://linux-hardware.org/?probe=15b2eded0d) | Jan 23, 2025 |
| ASRock        | H67M-ITX                    | [c651095205](https://linux-hardware.org/?probe=c651095205) | Jan 19, 2025 |
| ASRock        | H67M-ITX                    | [420a17a67a](https://linux-hardware.org/?probe=420a17a67a) | Jan 18, 2025 |
| MSI           | PRO B650M-A WIFI            | [5c60cb5bbf](https://linux-hardware.org/?probe=5c60cb5bbf) | Jan 17, 2025 |
| Dell          | 09M8Y8 A01                  | [fb46c2e3a4](https://linux-hardware.org/?probe=fb46c2e3a4) | Jan 14, 2025 |
| Dell          | 09M8Y8 A01                  | [e9d0c75a0c](https://linux-hardware.org/?probe=e9d0c75a0c) | Jan 14, 2025 |
| HP            | 83E8                        | [c6edbdb9e8](https://linux-hardware.org/?probe=c6edbdb9e8) | Jan 10, 2025 |
| ASRock        | B650M-H/M.2+                | [44990dc3cf](https://linux-hardware.org/?probe=44990dc3cf) | Jan 09, 2025 |
| Gigabyte      | MRHM3AP                     | [38c0271497](https://linux-hardware.org/?probe=38c0271497) | Jan 08, 2025 |
| MSI           | G31TM-P21                   | [7f868dd6f9](https://linux-hardware.org/?probe=7f868dd6f9) | Jan 06, 2025 |
| ASUSTek       | PRIME H310M-E R2.0          | [79752b904b](https://linux-hardware.org/?probe=79752b904b) | Jan 04, 2025 |
| Intel         | H61                         | [0f76193421](https://linux-hardware.org/?probe=0f76193421) | Jan 02, 2025 |
| MSI           | A88XM-E35 V2                | [d3df8a394a](https://linux-hardware.org/?probe=d3df8a394a) | Dec 30, 2024 |
| ASUSTek       | H110M-D                     | [a61b42dd42](https://linux-hardware.org/?probe=a61b42dd42) | Dec 29, 2024 |
| ASRock        | X570 Extreme4               | [65cad1da61](https://linux-hardware.org/?probe=65cad1da61) | Dec 26, 2024 |
| Gigabyte      | B85M-HD3                    | [83d5947a2c](https://linux-hardware.org/?probe=83d5947a2c) | Dec 24, 2024 |
| Gigabyte      | B560 DS3H AC-Y1             | [4e79bebde8](https://linux-hardware.org/?probe=4e79bebde8) | Dec 24, 2024 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [89e8e5ad41](https://linux-hardware.org/?probe=89e8e5ad41) | Dec 24, 2024 |
| MSI           | PRO B760M-P DDR4            | [a649caaa82](https://linux-hardware.org/?probe=a649caaa82) | Dec 23, 2024 |
| MSI           | PRO B760-P WIFI DDR4        | [59c289d5b9](https://linux-hardware.org/?probe=59c289d5b9) | Dec 22, 2024 |
| Dell          | 0MWYPT A00                  | [98cc5ad973](https://linux-hardware.org/?probe=98cc5ad973) | Dec 22, 2024 |
| Dell          | 0MWYPT A00                  | [dd73af7555](https://linux-hardware.org/?probe=dd73af7555) | Dec 22, 2024 |
| Gigabyte      | B560 DS3H AC-Y1             | [4c934647d2](https://linux-hardware.org/?probe=4c934647d2) | Dec 21, 2024 |
| Dell          | 00V62H A01                  | [8e8317c6a6](https://linux-hardware.org/?probe=8e8317c6a6) | Dec 19, 2024 |
| Gigabyte      | Z77-D3H                     | [9a64691207](https://linux-hardware.org/?probe=9a64691207) | Dec 17, 2024 |
| ASUSTek       | P8H67-M PRO                 | [987844d0b8](https://linux-hardware.org/?probe=987844d0b8) | Dec 17, 2024 |
| HP            | 8266                        | [ccd7d6b235](https://linux-hardware.org/?probe=ccd7d6b235) | Dec 17, 2024 |
| GEEKOM        | A8                          | [821fae98e5](https://linux-hardware.org/?probe=821fae98e5) | Dec 17, 2024 |
| Huanan        | X99-F8 GAMING V5.0          | [28d3412139](https://linux-hardware.org/?probe=28d3412139) | Dec 17, 2024 |
| HP            | 83E8                        | [77d40d025a](https://linux-hardware.org/?probe=77d40d025a) | Dec 16, 2024 |
| Intel         | Unknown                     | [fcbbdc5c06](https://linux-hardware.org/?probe=fcbbdc5c06) | Dec 16, 2024 |
| Dell          | 0F6X5P A00                  | [059cf0cd47](https://linux-hardware.org/?probe=059cf0cd47) | Dec 15, 2024 |
| Dell          | 0F6X5P A00                  | [f9eae65d13](https://linux-hardware.org/?probe=f9eae65d13) | Dec 14, 2024 |
| HP            | 8299                        | [44a762b74e](https://linux-hardware.org/?probe=44a762b74e) | Dec 14, 2024 |
| HP            | 8299                        | [f0c7982d81](https://linux-hardware.org/?probe=f0c7982d81) | Dec 14, 2024 |
| ASUSTek       | PRIME B450M-A               | [262a2aa975](https://linux-hardware.org/?probe=262a2aa975) | Dec 13, 2024 |
| Intel         | B75 V1.1                    | [d6aad9d651](https://linux-hardware.org/?probe=d6aad9d651) | Dec 03, 2024 |
| Dell          | 00V62H A01                  | [a12ee189e3](https://linux-hardware.org/?probe=a12ee189e3) | Dec 02, 2024 |
| Intel         | X99-P4 V5.11                | [b5079a1a8d](https://linux-hardware.org/?probe=b5079a1a8d) | Dec 02, 2024 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | [ffa565d696](https://linux-hardware.org/?probe=ffa565d696) | Dec 02, 2024 |
| Intel         | D945GCL AAD75361-301        | [f04b1a58c2](https://linux-hardware.org/?probe=f04b1a58c2) | Dec 01, 2024 |
| Intel         | D945GCL AAD75361-301        | [fc715bb336](https://linux-hardware.org/?probe=fc715bb336) | Dec 01, 2024 |
| ASRock        | H310CM-HG4                  | [86f4d79f62](https://linux-hardware.org/?probe=86f4d79f62) | Dec 01, 2024 |
| Huanan        | X99-F8 GAMING V5.0          | [dbc6940414](https://linux-hardware.org/?probe=dbc6940414) | Nov 29, 2024 |
| HP            | 3647h                       | [de1eb15f76](https://linux-hardware.org/?probe=de1eb15f76) | Nov 28, 2024 |
| Lenovo        | ThinkCentre M81 7517A2F     | [51de0395d0](https://linux-hardware.org/?probe=51de0395d0) | Nov 27, 2024 |
| Lenovo        | ThinkCentre M81 7517A2F     | [6ae2f479e0](https://linux-hardware.org/?probe=6ae2f479e0) | Nov 26, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [0b3205081d](https://linux-hardware.org/?probe=0b3205081d) | Nov 22, 2024 |
| ASRock        | 945GCM-S                    | [c1060979e3](https://linux-hardware.org/?probe=c1060979e3) | Nov 21, 2024 |
| ASRock        | X570 Phantom Gaming 4       | [b5f2062c2c](https://linux-hardware.org/?probe=b5f2062c2c) | Nov 18, 2024 |
| HP            | 1998                        | [021e8262ce](https://linux-hardware.org/?probe=021e8262ce) | Nov 16, 2024 |
| HP            | 212B                        | [35097b8ab0](https://linux-hardware.org/?probe=35097b8ab0) | Nov 15, 2024 |
| ASUSTek       | PRIME B365M-A               | [fc06ee6598](https://linux-hardware.org/?probe=fc06ee6598) | Nov 10, 2024 |
| MSI           | Z390-A PRO                  | [68c27eb24c](https://linux-hardware.org/?probe=68c27eb24c) | Nov 10, 2024 |
| MSI           | Z390-A PRO                  | [a6930afc53](https://linux-hardware.org/?probe=a6930afc53) | Nov 10, 2024 |
| ASRock        | B450M Pro4                  | [41cbe4313e](https://linux-hardware.org/?probe=41cbe4313e) | Nov 06, 2024 |
| Lenovo        | SHARKBAY NOK                | [f37b129292](https://linux-hardware.org/?probe=f37b129292) | Nov 05, 2024 |
| Gigabyte      | B550 UD AC-Y1               | [f146362156](https://linux-hardware.org/?probe=f146362156) | Nov 04, 2024 |
| ASRock        | Z390 Phantom Gaming-ITX/... | [0e0a0fd3c5](https://linux-hardware.org/?probe=0e0a0fd3c5) | Oct 30, 2024 |
| ASRock        | B450M Steel Legend          | [ee7a3727e4](https://linux-hardware.org/?probe=ee7a3727e4) | Oct 23, 2024 |
| ASUSTek       | PRIME B365M-A               | [25dc97604a](https://linux-hardware.org/?probe=25dc97604a) | Oct 22, 2024 |
| ASUSTek       | PRIME B460-PLUS             | [c16cede43b](https://linux-hardware.org/?probe=c16cede43b) | Oct 18, 2024 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [043f4904ae](https://linux-hardware.org/?probe=043f4904ae) | Oct 15, 2024 |
| ASRock        | B450M Steel Legend          | [0615e499e7](https://linux-hardware.org/?probe=0615e499e7) | Oct 13, 2024 |
| Dell          | 0P096C A00                  | [29a648fa32](https://linux-hardware.org/?probe=29a648fa32) | Oct 05, 2024 |
| Dell          | 0P096C A00                  | [5a4a3dac5c](https://linux-hardware.org/?probe=5a4a3dac5c) | Oct 05, 2024 |
| Intel         | JSL MRD                     | [6be233c711](https://linux-hardware.org/?probe=6be233c711) | Oct 02, 2024 |
| MSI           | Z270 GAMING PRO CARBON      | [add5dd6115](https://linux-hardware.org/?probe=add5dd6115) | Sep 29, 2024 |
| Intel         | IPC-ADN2L                   | [7aaa04ef0f](https://linux-hardware.org/?probe=7aaa04ef0f) | Sep 27, 2024 |
| MSI           | Z97S SLI Krait Edition      | [a44bd15d85](https://linux-hardware.org/?probe=a44bd15d85) | Sep 17, 2024 |
| MSI           | Z97S SLI Krait Edition      | [f73ff9c739](https://linux-hardware.org/?probe=f73ff9c739) | Sep 16, 2024 |
| Lenovo        | SHARKBAY NOK                | [7a6f092e7a](https://linux-hardware.org/?probe=7a6f092e7a) | Sep 13, 2024 |
| ASUSTek       | ET2700I                     | [0faf2541ce](https://linux-hardware.org/?probe=0faf2541ce) | Sep 11, 2024 |
| Intel         | IPC-ADN2L                   | [274c57803d](https://linux-hardware.org/?probe=274c57803d) | Sep 09, 2024 |
| Pegatron      | 2A94h                       | [5a721a5edc](https://linux-hardware.org/?probe=5a721a5edc) | Sep 08, 2024 |
| Gigabyte      | H81M-S2H                    | [8c3768316c](https://linux-hardware.org/?probe=8c3768316c) | Sep 05, 2024 |
| Lenovo        | ThinkCentre Edge71 1607R... | [29cdb0e2f5](https://linux-hardware.org/?probe=29cdb0e2f5) | Sep 02, 2024 |
| ASRock        | J5040-ITX                   | [fcfa738334](https://linux-hardware.org/?probe=fcfa738334) | Sep 01, 2024 |
| MSI           | H77MA-G43                   | [73df0e9be3](https://linux-hardware.org/?probe=73df0e9be3) | Aug 28, 2024 |
| MSI           | H77MA-G43                   | [c3687b0959](https://linux-hardware.org/?probe=c3687b0959) | Aug 28, 2024 |
| Gigabyte      | Z790 UD                     | [fd328d5314](https://linux-hardware.org/?probe=fd328d5314) | Aug 28, 2024 |
| Gigabyte      | Z790 UD                     | [01f402c213](https://linux-hardware.org/?probe=01f402c213) | Aug 28, 2024 |
| ASUSTek       | ET2700I                     | [46b00a17dd](https://linux-hardware.org/?probe=46b00a17dd) | Aug 28, 2024 |
| ASUSTek       | ET2700I                     | [69b47ec3cd](https://linux-hardware.org/?probe=69b47ec3cd) | Aug 28, 2024 |
| ASRock        | B450M/ac R2.0               | [0946b4faad](https://linux-hardware.org/?probe=0946b4faad) | Aug 28, 2024 |
| HP            | 0B54h D                     | [3e361ce6dd](https://linux-hardware.org/?probe=3e361ce6dd) | Aug 27, 2024 |
| Pegatron      | 2A94h                       | [6ec199373b](https://linux-hardware.org/?probe=6ec199373b) | Aug 25, 2024 |
| ASRock        | B450M/ac R2.0               | [0026cbe5e3](https://linux-hardware.org/?probe=0026cbe5e3) | Aug 25, 2024 |
| HP            | 1495                        | [76595d0137](https://linux-hardware.org/?probe=76595d0137) | Aug 24, 2024 |
| HP            | 1495                        | [d7f96fb46e](https://linux-hardware.org/?probe=d7f96fb46e) | Aug 24, 2024 |
| Dell          | 0PU052                      | [95f1504d6a](https://linux-hardware.org/?probe=95f1504d6a) | Aug 22, 2024 |
| Dell          | 0VG93V A00                  | [b81443c816](https://linux-hardware.org/?probe=b81443c816) | Aug 18, 2024 |
| ASRock        | H61M-VG3                    | [a377e590da](https://linux-hardware.org/?probe=a377e590da) | Aug 18, 2024 |
| Dell          | 0VG93V A00                  | [c6be5f6727](https://linux-hardware.org/?probe=c6be5f6727) | Aug 17, 2024 |
| ASUSTek       | B85M-E/BR                   | [9b3874ab72](https://linux-hardware.org/?probe=9b3874ab72) | Aug 13, 2024 |
| ASRock        | B450M Steel Legend          | [48b9938f65](https://linux-hardware.org/?probe=48b9938f65) | Aug 08, 2024 |
| ASRock        | H81M-DGS R2.0               | [d3e0797e5b](https://linux-hardware.org/?probe=d3e0797e5b) | Aug 07, 2024 |
| ASRock        | H81M-DGS R2.0               | [2b569bdccd](https://linux-hardware.org/?probe=2b569bdccd) | Aug 07, 2024 |
| Gigabyte      | H81M-S2H                    | [66bcb40057](https://linux-hardware.org/?probe=66bcb40057) | Aug 05, 2024 |
| Gigabyte      | H81M-S2H                    | [dcf87ade71](https://linux-hardware.org/?probe=dcf87ade71) | Aug 03, 2024 |
| ASUSTek       | P5G41-M LX                  | [b3b334d874](https://linux-hardware.org/?probe=b3b334d874) | Aug 01, 2024 |
| Dell          | 0MG3PY A00                  | [558c13f467](https://linux-hardware.org/?probe=558c13f467) | Aug 01, 2024 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [1d828595b9](https://linux-hardware.org/?probe=1d828595b9) | Jul 30, 2024 |
| AZW           | MINI S                      | [d8754c0201](https://linux-hardware.org/?probe=d8754c0201) | Jul 25, 2024 |
| Gigabyte      | H310M H x.x                 | [c89938fbbb](https://linux-hardware.org/?probe=c89938fbbb) | Jul 25, 2024 |
| ASRock        | B360M-HDV                   | [94cbafc49e](https://linux-hardware.org/?probe=94cbafc49e) | Jul 24, 2024 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [2c279e3d69](https://linux-hardware.org/?probe=2c279e3d69) | Jul 22, 2024 |
| Gigabyte      | B550 AORUS ELITE            | [8f90dcefce](https://linux-hardware.org/?probe=8f90dcefce) | Jul 19, 2024 |
| ASUSTek       | P8B75-M LX                  | [7c793c4a04](https://linux-hardware.org/?probe=7c793c4a04) | Jul 18, 2024 |
| ASUSTek       | P8B75-M LX                  | [64685a555f](https://linux-hardware.org/?probe=64685a555f) | Jul 18, 2024 |
| AMI           | Intel                       | [461763ad20](https://linux-hardware.org/?probe=461763ad20) | Jul 17, 2024 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [a675a84975](https://linux-hardware.org/?probe=a675a84975) | Jul 12, 2024 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [d7d8b022c8](https://linux-hardware.org/?probe=d7d8b022c8) | Jul 12, 2024 |
| ASRock        | A320M-HDV R4.0              | [be9af5afe2](https://linux-hardware.org/?probe=be9af5afe2) | Jul 08, 2024 |
| Dell          | 0K240Y A03                  | [fd2e6133c8](https://linux-hardware.org/?probe=fd2e6133c8) | Jul 07, 2024 |
| Dell          | 0K240Y A03                  | [7409d9aee8](https://linux-hardware.org/?probe=7409d9aee8) | Jul 07, 2024 |
| Dell          | 0K240Y A03                  | [25538a3377](https://linux-hardware.org/?probe=25538a3377) | Jul 06, 2024 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [605b774f63](https://linux-hardware.org/?probe=605b774f63) | Jul 02, 2024 |
| ASUSTek       | H110M-A/M.2                 | [ef55e011c4](https://linux-hardware.org/?probe=ef55e011c4) | Jun 28, 2024 |
| HP            | 0B54h D                     | [a1df6af082](https://linux-hardware.org/?probe=a1df6af082) | Jun 27, 2024 |
| MSI           | B365M PRO-VDH               | [bf340a8641](https://linux-hardware.org/?probe=bf340a8641) | Jun 25, 2024 |
| ECS           | H110M-C3D/C3V               | [0029341c8c](https://linux-hardware.org/?probe=0029341c8c) | Jun 18, 2024 |
| MSI           | MS-7267                     | [59fc27aa13](https://linux-hardware.org/?probe=59fc27aa13) | Jun 17, 2024 |
| MSI           | MS-7267                     | [02fc0d7625](https://linux-hardware.org/?probe=02fc0d7625) | Jun 17, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [f5a682fbe7](https://linux-hardware.org/?probe=f5a682fbe7) | Jun 16, 2024 |
| ASUSTek       | 970 PRO GAMING/AURA         | [8d51939a60](https://linux-hardware.org/?probe=8d51939a60) | Jun 16, 2024 |
| ASUSTek       | 970 PRO GAMING/AURA         | [8eac8a90fb](https://linux-hardware.org/?probe=8eac8a90fb) | Jun 15, 2024 |
| Gigabyte      | B760M DS3H AX DDR4          | [b1067e137b](https://linux-hardware.org/?probe=b1067e137b) | Jun 11, 2024 |
| Gigabyte      | GA-990FX-GAMING             | [af3d2280af](https://linux-hardware.org/?probe=af3d2280af) | Jun 10, 2024 |
| Dell          | 00V62H A01                  | [6cc3abff8f](https://linux-hardware.org/?probe=6cc3abff8f) | Jun 06, 2024 |
| ASUSTek       | PRIME H510M-K R2.0          | [2f2a24345a](https://linux-hardware.org/?probe=2f2a24345a) | Jun 05, 2024 |
| ASUSTek       | PRIME H510M-K R2.0          | [a15ecb15f8](https://linux-hardware.org/?probe=a15ecb15f8) | Jun 05, 2024 |
| ASUSTek       | H110M-A/M.2                 | [0e706f4bcd](https://linux-hardware.org/?probe=0e706f4bcd) | May 30, 2024 |
| Gigabyte      | H310M H x.x                 | [6c986e95fa](https://linux-hardware.org/?probe=6c986e95fa) | May 17, 2024 |
| Lenovo        | ThinkCentre A58 761179G     | [0f92c56231](https://linux-hardware.org/?probe=0f92c56231) | May 17, 2024 |
| Dell          | 08VX12 A00                  | [da62c2beb8](https://linux-hardware.org/?probe=da62c2beb8) | May 14, 2024 |
| ASUSTek       | STRIX Z270F GAMING          | [2fadb82e07](https://linux-hardware.org/?probe=2fadb82e07) | May 14, 2024 |
| Dell          | 0GY6Y8 A02                  | [7982277925](https://linux-hardware.org/?probe=7982277925) | May 13, 2024 |
| ASUSTek       | PRIME B460M-K               | [fea6956058](https://linux-hardware.org/?probe=fea6956058) | May 08, 2024 |
| ASUSTek       | PRIME H510M-A               | [e475e36ab0](https://linux-hardware.org/?probe=e475e36ab0) | May 06, 2024 |
| ASUSTek       | PRIME A320M-K               | [0f43840d58](https://linux-hardware.org/?probe=0f43840d58) | May 06, 2024 |
| HP            | 0B4Ch D                     | [29d73efd4a](https://linux-hardware.org/?probe=29d73efd4a) | Apr 30, 2024 |
| ASUSTek       | PRIME A320M-K               | [022ece0282](https://linux-hardware.org/?probe=022ece0282) | Apr 30, 2024 |
| Medion        | MS-7797                     | [a72c95890e](https://linux-hardware.org/?probe=a72c95890e) | Apr 28, 2024 |
| Gigabyte      | B250M-D2VX-SI-CF            | [5c277491cf](https://linux-hardware.org/?probe=5c277491cf) | Apr 27, 2024 |
| ASUSTek       | TUF X470-PLUS GAMING        | [6609c77480](https://linux-hardware.org/?probe=6609c77480) | Apr 26, 2024 |
| ASUSTek       | P8H77-M PRO                 | [ee55351883](https://linux-hardware.org/?probe=ee55351883) | Apr 25, 2024 |
| ASUSTek       | PRIME H510M-A               | [c12789125b](https://linux-hardware.org/?probe=c12789125b) | Apr 24, 2024 |
| Medion        | MS-7797                     | [810a7d7810](https://linux-hardware.org/?probe=810a7d7810) | Apr 22, 2024 |
| ECS           | H110M-C3D/C3V               | [7fffccead5](https://linux-hardware.org/?probe=7fffccead5) | Apr 17, 2024 |
| Dell          | 0D24M8 A02                  | [96b0ae2f86](https://linux-hardware.org/?probe=96b0ae2f86) | Apr 16, 2024 |
| Gigabyte      | F2A68HM-S1                  | [32237e05f1](https://linux-hardware.org/?probe=32237e05f1) | Apr 15, 2024 |
| Medion        | Z370H4-EM                   | [39cb6c0afb](https://linux-hardware.org/?probe=39cb6c0afb) | Apr 13, 2024 |
| MSI           | MEG Z590 UNIFY              | [88f634c670](https://linux-hardware.org/?probe=88f634c670) | Apr 11, 2024 |
| MSI           | MEG Z590 UNIFY              | [2336b3cd38](https://linux-hardware.org/?probe=2336b3cd38) | Apr 11, 2024 |
| HP            | 18E7                        | [467ac72efe](https://linux-hardware.org/?probe=467ac72efe) | Apr 07, 2024 |
| Gigabyte      | 945GME-DS2                  | [37085a5c3f](https://linux-hardware.org/?probe=37085a5c3f) | Apr 06, 2024 |
| HP            | 18E7                        | [9dadc64d70](https://linux-hardware.org/?probe=9dadc64d70) | Apr 03, 2024 |
| ASUSTek       | EX-B150M-V3                 | [0c643b047e](https://linux-hardware.org/?probe=0c643b047e) | Apr 01, 2024 |
| ASUSTek       | EX-B150M-V3                 | [c6772f244f](https://linux-hardware.org/?probe=c6772f244f) | Apr 01, 2024 |
| ASUSTek       | P8H77-M PRO                 | [f30dd46998](https://linux-hardware.org/?probe=f30dd46998) | Mar 29, 2024 |
| MSI           | MAG B660M MORTAR WIFI DD... | [a87aa51bf9](https://linux-hardware.org/?probe=a87aa51bf9) | Mar 29, 2024 |
| MSI           | A68HM-E33 V2                | [22b44252e3](https://linux-hardware.org/?probe=22b44252e3) | Mar 28, 2024 |
| Lenovo        | ThinkCentre Edge91 1895B... | [991944129e](https://linux-hardware.org/?probe=991944129e) | Mar 26, 2024 |
| Gigabyte      | A320M-S2H-CF                | [30717fbd15](https://linux-hardware.org/?probe=30717fbd15) | Mar 25, 2024 |
| ASUSTek       | M4A87TD/USB3                | [9a817cbe67](https://linux-hardware.org/?probe=9a817cbe67) | Mar 24, 2024 |
| ASUSTek       | H81M-P PLUS                 | [92aa3b7c70](https://linux-hardware.org/?probe=92aa3b7c70) | Mar 24, 2024 |
| ASUSTek       | H81M-P PLUS                 | [57ee067ff2](https://linux-hardware.org/?probe=57ee067ff2) | Mar 24, 2024 |
| HP            | 0B54h D                     | [7b38927e17](https://linux-hardware.org/?probe=7b38927e17) | Mar 23, 2024 |
| Unknown       | Unknown                     | [5af36d3a4e](https://linux-hardware.org/?probe=5af36d3a4e) | Mar 22, 2024 |
| HP            | 0B54h D                     | [0af537dbcd](https://linux-hardware.org/?probe=0af537dbcd) | Mar 22, 2024 |
| ASRock        | X570 Extreme4               | [f7bd9e9cce](https://linux-hardware.org/?probe=f7bd9e9cce) | Mar 21, 2024 |
| MSI           | A68HM-E33 V2                | [52b29bf885](https://linux-hardware.org/?probe=52b29bf885) | Mar 12, 2024 |
| ASRock        | H110M-HDS                   | [0b9ca9c2ca](https://linux-hardware.org/?probe=0b9ca9c2ca) | Mar 12, 2024 |
| ASRock        | H110M-HDS                   | [0d754901a3](https://linux-hardware.org/?probe=0d754901a3) | Mar 12, 2024 |
| Dell          | 0D24M8 A02                  | [70a8364913](https://linux-hardware.org/?probe=70a8364913) | Mar 11, 2024 |
| Dell          | 0M6C7G A00                  | [666c6ad495](https://linux-hardware.org/?probe=666c6ad495) | Mar 10, 2024 |
| Biostar       | B350GT5                     | [61f8cce525](https://linux-hardware.org/?probe=61f8cce525) | Mar 08, 2024 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [16b3359307](https://linux-hardware.org/?probe=16b3359307) | Mar 07, 2024 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [4d569e557d](https://linux-hardware.org/?probe=4d569e557d) | Mar 07, 2024 |
| Acer          | FIH57                       | [4b9a9a43f3](https://linux-hardware.org/?probe=4b9a9a43f3) | Mar 02, 2024 |
| HP            | 8434 11                     | [aa98b6327d](https://linux-hardware.org/?probe=aa98b6327d) | Mar 02, 2024 |
| HP            | 8434 11                     | [5b25b65016](https://linux-hardware.org/?probe=5b25b65016) | Mar 01, 2024 |
| Apple         | Mac-F221BEC8                | [10c92b676a](https://linux-hardware.org/?probe=10c92b676a) | Feb 29, 2024 |
| Dell          | 0D24M8 A02                  | [d67f57356b](https://linux-hardware.org/?probe=d67f57356b) | Feb 28, 2024 |
| Intel         | X79Turbo V1.x               | [09f942e7f4](https://linux-hardware.org/?probe=09f942e7f4) | Feb 26, 2024 |
| Gigabyte      | AB350-Gaming 3-CF           | [082b9f50ab](https://linux-hardware.org/?probe=082b9f50ab) | Feb 23, 2024 |
| Gigabyte      | H110N-CF                    | [c6a69fce12](https://linux-hardware.org/?probe=c6a69fce12) | Feb 10, 2024 |
| ASUSTek       | P5G41T-M LX3                | [fd10cd8983](https://linux-hardware.org/?probe=fd10cd8983) | Feb 09, 2024 |
| ASUSTek       | P5G41T-M LX3                | [ae6f0a23e2](https://linux-hardware.org/?probe=ae6f0a23e2) | Feb 09, 2024 |
| ASUSTek       | P8Z68-V PRO GEN3            | [d099546e70](https://linux-hardware.org/?probe=d099546e70) | Feb 07, 2024 |
| Intel         | X79Turbo V1.x               | [35c4b20053](https://linux-hardware.org/?probe=35c4b20053) | Feb 07, 2024 |
| Dell          | 0GDG8Y A00                  | [2cca1daa38](https://linux-hardware.org/?probe=2cca1daa38) | Feb 01, 2024 |
| ASRock        | B75M-DGS R2.0               | [cff86cc0d9](https://linux-hardware.org/?probe=cff86cc0d9) | Jan 27, 2024 |
| Dell          | 00V62H A01                  | [83f7e8b344](https://linux-hardware.org/?probe=83f7e8b344) | Jan 24, 2024 |
| Gigabyte      | EP43-UD3L                   | [6a2153a6b9](https://linux-hardware.org/?probe=6a2153a6b9) | Jan 21, 2024 |
| Dell          | 00V62H A01                  | [7104f7e7cf](https://linux-hardware.org/?probe=7104f7e7cf) | Jan 21, 2024 |
| Gigabyte      | B560M DS3H                  | [8ffb8f68ca](https://linux-hardware.org/?probe=8ffb8f68ca) | Jan 19, 2024 |
| Gigabyte      | EP43-UD3L                   | [8dc280e4fc](https://linux-hardware.org/?probe=8dc280e4fc) | Jan 13, 2024 |
| ASRock        | Z390 Phantom Gaming-ITX/... | [62374d5cbd](https://linux-hardware.org/?probe=62374d5cbd) | Jan 11, 2024 |
| ASRock        | Z390 Phantom Gaming-ITX/... | [f24b7483b8](https://linux-hardware.org/?probe=f24b7483b8) | Jan 11, 2024 |
| HP            | 3397                        | [3339eb00ce](https://linux-hardware.org/?probe=3339eb00ce) | Jan 03, 2024 |
| HP            | 0AA8h                       | [49435a98d1](https://linux-hardware.org/?probe=49435a98d1) | Dec 19, 2023 |
| HP            | 3397                        | [7b379848f1](https://linux-hardware.org/?probe=7b379848f1) | Dec 16, 2023 |
| HP            | 0AA8h                       | [5264c3d3e1](https://linux-hardware.org/?probe=5264c3d3e1) | Dec 16, 2023 |
| HP            | 0AA8h                       | [e20c0fc21b](https://linux-hardware.org/?probe=e20c0fc21b) | Dec 16, 2023 |
| ECS           | G41T-M                      | [a0017f196c](https://linux-hardware.org/?probe=a0017f196c) | Dec 14, 2023 |
| ASUSTek       | Z97-AR                      | [70936627e8](https://linux-hardware.org/?probe=70936627e8) | Dec 05, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [cfc7698579](https://linux-hardware.org/?probe=cfc7698579) | Dec 04, 2023 |
| ASUSTek       | PRIME A320M-K               | [5bbcf82cf2](https://linux-hardware.org/?probe=5bbcf82cf2) | Nov 30, 2023 |
| Jetway        | TI61M5                      | [dff0fcc796](https://linux-hardware.org/?probe=dff0fcc796) | Nov 25, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [541efb8e16](https://linux-hardware.org/?probe=541efb8e16) | Nov 24, 2023 |
| Jetway        | TI61M5                      | [968d83ba14](https://linux-hardware.org/?probe=968d83ba14) | Nov 21, 2023 |
| Dell          | 0XPDFK A01                  | [8b3abafe9b](https://linux-hardware.org/?probe=8b3abafe9b) | Nov 19, 2023 |
| Gigabyte      | B550M DS3H                  | [8def310709](https://linux-hardware.org/?probe=8def310709) | Nov 16, 2023 |
| Dell          | 03KWTV A00                  | [794f73f426](https://linux-hardware.org/?probe=794f73f426) | Nov 16, 2023 |
| ASUSTek       | PRIME A320M-K               | [5ddcb0cf64](https://linux-hardware.org/?probe=5ddcb0cf64) | Nov 15, 2023 |
| Intel         | DH67BL AAG10189-206         | [334569cac2](https://linux-hardware.org/?probe=334569cac2) | Nov 15, 2023 |
| MSI           | H77MA-G43                   | [f191f17f2a](https://linux-hardware.org/?probe=f191f17f2a) | Nov 14, 2023 |
| Gigabyte      | B550M DS3H                  | [882de5a591](https://linux-hardware.org/?probe=882de5a591) | Nov 13, 2023 |
| MSI           | H77MA-G43                   | [a814c93afe](https://linux-hardware.org/?probe=a814c93afe) | Nov 09, 2023 |
| HC Technol... | HCAR5000-MI                 | [ab41e88ca3](https://linux-hardware.org/?probe=ab41e88ca3) | Nov 07, 2023 |
| ASUSTek       | PRIME A320M-K               | [99b0c9edcf](https://linux-hardware.org/?probe=99b0c9edcf) | Nov 06, 2023 |
| ASUSTek       | H110M-A/M.2                 | [2cc662a279](https://linux-hardware.org/?probe=2cc662a279) | Nov 05, 2023 |
| Dell          | 0T7D40 A00                  | [2053de6443](https://linux-hardware.org/?probe=2053de6443) | Nov 05, 2023 |
| Dell          | 0T7D40 A00                  | [a81d5bbd02](https://linux-hardware.org/?probe=a81d5bbd02) | Nov 03, 2023 |
| HP            | 0B54h D                     | [4ec7776a76](https://linux-hardware.org/?probe=4ec7776a76) | Nov 02, 2023 |
| ASUSTek       | ROG STRIX B360-F GAMING     | [72a5b8f06a](https://linux-hardware.org/?probe=72a5b8f06a) | Nov 02, 2023 |
| Dell          | 0J3C2F A00                  | [a9ed160c1c](https://linux-hardware.org/?probe=a9ed160c1c) | Nov 01, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | [b5e0b9a020](https://linux-hardware.org/?probe=b5e0b9a020) | Oct 27, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | [38ed4f25af](https://linux-hardware.org/?probe=38ed4f25af) | Oct 27, 2023 |
| MACHINIST     | H81M-PRO S1 V2.0            | [b9ec438e43](https://linux-hardware.org/?probe=b9ec438e43) | Oct 27, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [3b82b142b1](https://linux-hardware.org/?probe=3b82b142b1) | Oct 26, 2023 |
| ASUSTek       | P5G41-M LX2/GB              | [ffc0782186](https://linux-hardware.org/?probe=ffc0782186) | Oct 23, 2023 |
| Gigabyte      | B560M DS3H                  | [2100dab18e](https://linux-hardware.org/?probe=2100dab18e) | Oct 23, 2023 |
| Acer          | G33T-AM                     | [7b42f4db1d](https://linux-hardware.org/?probe=7b42f4db1d) | Oct 23, 2023 |
| Acer          | G33T-AM                     | [70f67a6f11](https://linux-hardware.org/?probe=70f67a6f11) | Oct 22, 2023 |
| MACHINIST     | X79 Z9-D7 V1.2              | [7ad6760006](https://linux-hardware.org/?probe=7ad6760006) | Oct 19, 2023 |
| Dell          | 0GDG8Y A00                  | [78164f9bcc](https://linux-hardware.org/?probe=78164f9bcc) | Oct 18, 2023 |
| MACHINIST     | X79 Z9-D7 V1.2              | [bc7e7d2817](https://linux-hardware.org/?probe=bc7e7d2817) | Oct 17, 2023 |
| MSI           | Z270 GAMING PRO CARBON      | [47f6f3760d](https://linux-hardware.org/?probe=47f6f3760d) | Oct 17, 2023 |
| MSI           | Z270 GAMING PRO CARBON      | [23c3f61285](https://linux-hardware.org/?probe=23c3f61285) | Oct 14, 2023 |
| ASUSTek       | P8H61-MX R2.0               | [a654820b23](https://linux-hardware.org/?probe=a654820b23) | Oct 13, 2023 |
| ASUSTek       | P8H61-MX R2.0               | [b756b81d33](https://linux-hardware.org/?probe=b756b81d33) | Oct 12, 2023 |
| Dell          | 0GTK4K A02                  | [05d87a2b59](https://linux-hardware.org/?probe=05d87a2b59) | Oct 08, 2023 |
| Dell          | 0GTK4K A02                  | [7480d29d9f](https://linux-hardware.org/?probe=7480d29d9f) | Oct 07, 2023 |
| ASUSTek       | P5G41T-M LX                 | [21ec0f4129](https://linux-hardware.org/?probe=21ec0f4129) | Oct 06, 2023 |
| Gigabyte      | H110M-S2H-CF                | [3513d5bcf3](https://linux-hardware.org/?probe=3513d5bcf3) | Sep 28, 2023 |
| Gigabyte      | GA-MA790XT-UD4P             | [945e2bc260](https://linux-hardware.org/?probe=945e2bc260) | Sep 24, 2023 |
| HP            | 2ADC                        | [b4794f247b](https://linux-hardware.org/?probe=b4794f247b) | Sep 21, 2023 |
| HP            | 2ADC                        | [7e9eb06b31](https://linux-hardware.org/?probe=7e9eb06b31) | Sep 21, 2023 |
| ASUSTek       | PRIME X370-PRO              | [603ddfc4cf](https://linux-hardware.org/?probe=603ddfc4cf) | Sep 18, 2023 |
| ASUSTek       | VM42                        | [ca9a3b42d0](https://linux-hardware.org/?probe=ca9a3b42d0) | Sep 17, 2023 |
| ASUSTek       | M3A78-CM                    | [5a47ad5c25](https://linux-hardware.org/?probe=5a47ad5c25) | Sep 15, 2023 |
| ASUSTek       | M3A78-CM                    | [876175ae24](https://linux-hardware.org/?probe=876175ae24) | Sep 15, 2023 |
| HP            | 339A                        | [a9eaaaeeb0](https://linux-hardware.org/?probe=a9eaaaeeb0) | Sep 12, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | [b4c93a8e2e](https://linux-hardware.org/?probe=b4c93a8e2e) | Sep 12, 2023 |
| Lenovo        | NO DPK                      | [0a25a3d2af](https://linux-hardware.org/?probe=0a25a3d2af) | Sep 12, 2023 |
| HP            | 339A                        | [18bb44efa6](https://linux-hardware.org/?probe=18bb44efa6) | Sep 10, 2023 |
| Gigabyte      | 970A-DS3P                   | [ef1d9bfdab](https://linux-hardware.org/?probe=ef1d9bfdab) | Sep 08, 2023 |
| Gigabyte      | 970A-DS3P                   | [2ce7b78a76](https://linux-hardware.org/?probe=2ce7b78a76) | Sep 06, 2023 |
| Dell          | 0J3C2F A00                  | [9374424bbd](https://linux-hardware.org/?probe=9374424bbd) | Aug 30, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [2a2adfdc2e](https://linux-hardware.org/?probe=2a2adfdc2e) | Aug 30, 2023 |
| Unknown       | IPMSB-H61                   | [c104b6462e](https://linux-hardware.org/?probe=c104b6462e) | Aug 26, 2023 |
| ASRock        | X370 Pro4                   | [190a0f1eee](https://linux-hardware.org/?probe=190a0f1eee) | Aug 23, 2023 |
| HP            | 18E7                        | [0bd07157fb](https://linux-hardware.org/?probe=0bd07157fb) | Aug 20, 2023 |
| ASUSTek       | P8Z68-V PRO GEN3            | [d05585906d](https://linux-hardware.org/?probe=d05585906d) | Aug 18, 2023 |
| Dell          | 0KP561                      | [2b6a6b6139](https://linux-hardware.org/?probe=2b6a6b6139) | Aug 17, 2023 |
| Gigabyte      | B560M H                     | [663f9e62db](https://linux-hardware.org/?probe=663f9e62db) | Aug 08, 2023 |
| Acer          | Aspire TC-710 V:1.1         | [f6af1382fd](https://linux-hardware.org/?probe=f6af1382fd) | Aug 08, 2023 |
| Dell          | 0NKW6Y A02                  | [09ae57bb9a](https://linux-hardware.org/?probe=09ae57bb9a) | Aug 05, 2023 |
| Dell          | 0NKW6Y A02                  | [21460cac53](https://linux-hardware.org/?probe=21460cac53) | Aug 05, 2023 |
| Pegatron      | 2A94h                       | [9d5490fb82](https://linux-hardware.org/?probe=9d5490fb82) | Aug 04, 2023 |
| MSI           | A320M-A PRO MAX             | [36dda4bbfa](https://linux-hardware.org/?probe=36dda4bbfa) | Jul 28, 2023 |
| MSI           | A320M-A PRO MAX             | [10fa87c167](https://linux-hardware.org/?probe=10fa87c167) | Jul 28, 2023 |
| ASRock        | X570 Extreme4               | [5b1a74fc68](https://linux-hardware.org/?probe=5b1a74fc68) | Jul 27, 2023 |
| Acer          | Aspire TC-380               | [94f5f10ff2](https://linux-hardware.org/?probe=94f5f10ff2) | Jul 14, 2023 |
| Wortmann      | TERRA_PC                    | [60ece53188](https://linux-hardware.org/?probe=60ece53188) | Jul 13, 2023 |
| ASRock        | X370 Pro4                   | [4e8926a95b](https://linux-hardware.org/?probe=4e8926a95b) | Jul 11, 2023 |
| Apple         | Mac-F221BEC8                | [881754a433](https://linux-hardware.org/?probe=881754a433) | Jul 09, 2023 |
| Alienware     | 07HV66 A00                  | [41d4d9ae84](https://linux-hardware.org/?probe=41d4d9ae84) | Jul 05, 2023 |
| Alienware     | 07HV66 A00                  | [2712110727](https://linux-hardware.org/?probe=2712110727) | Jul 05, 2023 |
| HP            | 0B54h D                     | [c13f21ea22](https://linux-hardware.org/?probe=c13f21ea22) | Jun 29, 2023 |
| Gigabyte      | H81M-S2V                    | [38ae545c1c](https://linux-hardware.org/?probe=38ae545c1c) | Jun 23, 2023 |
| MSI           | B450M PRO-M2 V2             | [4f5e2f9201](https://linux-hardware.org/?probe=4f5e2f9201) | Jun 21, 2023 |
| Pegatron      | IPMIP-GS                    | [fb51893272](https://linux-hardware.org/?probe=fb51893272) | Jun 15, 2023 |
| ECS           | G41T-M                      | [2c148573fc](https://linux-hardware.org/?probe=2c148573fc) | Jun 11, 2023 |
| Acer          | Veriton X2631G V:1.0        | [99f3070065](https://linux-hardware.org/?probe=99f3070065) | Jun 11, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [08114e8a97](https://linux-hardware.org/?probe=08114e8a97) | Jun 10, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [93555cfd25](https://linux-hardware.org/?probe=93555cfd25) | Jun 10, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [2e6d82c14f](https://linux-hardware.org/?probe=2e6d82c14f) | Jun 10, 2023 |
| Gigabyte      | B450M GAMING                | [8ab2ec8df4](https://linux-hardware.org/?probe=8ab2ec8df4) | Jun 09, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | [ddefeff960](https://linux-hardware.org/?probe=ddefeff960) | Jun 08, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | [77fe6db865](https://linux-hardware.org/?probe=77fe6db865) | Jun 06, 2023 |
| Gigabyte      | GA-E6010N                   | [563074319d](https://linux-hardware.org/?probe=563074319d) | May 31, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [16b9dfbbe0](https://linux-hardware.org/?probe=16b9dfbbe0) | May 29, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [e29fb14e81](https://linux-hardware.org/?probe=e29fb14e81) | May 26, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [84d0d9807f](https://linux-hardware.org/?probe=84d0d9807f) | May 26, 2023 |
| ASUSTek       | P8H61-MX R2.0               | [3776285fc1](https://linux-hardware.org/?probe=3776285fc1) | May 16, 2023 |
| HP            | 1998                        | [b806151d9f](https://linux-hardware.org/?probe=b806151d9f) | May 12, 2023 |
| HP            | 225E                        | [06c72d2ecd](https://linux-hardware.org/?probe=06c72d2ecd) | May 10, 2023 |
| Intel         | JSL MRD                     | [76ff5c3bd7](https://linux-hardware.org/?probe=76ff5c3bd7) | May 05, 2023 |
| Dell          | 02N3WF A02                  | [3f10b3ca43](https://linux-hardware.org/?probe=3f10b3ca43) | May 04, 2023 |
| HP            | 1998                        | [6f816ac95a](https://linux-hardware.org/?probe=6f816ac95a) | Apr 29, 2023 |
| HP            | 8055                        | [a897208085](https://linux-hardware.org/?probe=a897208085) | Apr 26, 2023 |
| ASRock        | B660M-C                     | [849fc5d462](https://linux-hardware.org/?probe=849fc5d462) | Apr 25, 2023 |
| Gigabyte      | H410M H V3                  | [8fd18554d1](https://linux-hardware.org/?probe=8fd18554d1) | Apr 24, 2023 |
| MACHINIST     | E5-MR9A PRO V1.1            | [eebce73217](https://linux-hardware.org/?probe=eebce73217) | Apr 23, 2023 |
| ASUSTek       | PRIME Z390-A                | [50a18b5e94](https://linux-hardware.org/?probe=50a18b5e94) | Apr 19, 2023 |
| Foxconn       | A76GMV                      | [bafa62c759](https://linux-hardware.org/?probe=bafa62c759) | Apr 18, 2023 |
| Foxconn       | A76GMV                      | [f129cb2de1](https://linux-hardware.org/?probe=f129cb2de1) | Apr 18, 2023 |
| ASUSTek       | PRIME Z390-A                | [e311d21def](https://linux-hardware.org/?probe=e311d21def) | Apr 13, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | [8e05a5e529](https://linux-hardware.org/?probe=8e05a5e529) | Apr 13, 2023 |
| Gigabyte      | Z270-Gaming K3              | [0c03014734](https://linux-hardware.org/?probe=0c03014734) | Apr 12, 2023 |
| HP            | 0B54h D                     | [59e9cd0741](https://linux-hardware.org/?probe=59e9cd0741) | Apr 06, 2023 |
| MSI           | B450M PRO-M2 MAX            | [5a83c18a3e](https://linux-hardware.org/?probe=5a83c18a3e) | Apr 01, 2023 |
| MSI           | B450M PRO-M2 MAX            | [94f75ee798](https://linux-hardware.org/?probe=94f75ee798) | Apr 01, 2023 |
| Unknown       | Unknown                     | [fb22157f03](https://linux-hardware.org/?probe=fb22157f03) | Mar 28, 2023 |
| AZW           | U59                         | [7674bb8dc9](https://linux-hardware.org/?probe=7674bb8dc9) | Mar 27, 2023 |
| ASUSTek       | M4A785TD-V EVO              | [1674c37cf9](https://linux-hardware.org/?probe=1674c37cf9) | Mar 16, 2023 |
| HP            | 805A                        | [5401e12606](https://linux-hardware.org/?probe=5401e12606) | Mar 14, 2023 |
| HP            | 3033h                       | [ab5e388ea9](https://linux-hardware.org/?probe=ab5e388ea9) | Mar 14, 2023 |
| HP            | 3033h                       | [38ac77726b](https://linux-hardware.org/?probe=38ac77726b) | Mar 13, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [39d0e8595c](https://linux-hardware.org/?probe=39d0e8595c) | Mar 12, 2023 |
| Dell          | 0T7D40 A01                  | [c2174a1837](https://linux-hardware.org/?probe=c2174a1837) | Mar 12, 2023 |
| MSI           | B365M PRO-VH                | [023f42d6d1](https://linux-hardware.org/?probe=023f42d6d1) | Mar 12, 2023 |
| Acer          | Aspire TC-380               | [563bd52487](https://linux-hardware.org/?probe=563bd52487) | Mar 10, 2023 |
| Inventec      | Z CLASS A02                 | [c45e770987](https://linux-hardware.org/?probe=c45e770987) | Mar 06, 2023 |
| ASUSTek       | BT6130                      | [dabd3e0232](https://linux-hardware.org/?probe=dabd3e0232) | Mar 01, 2023 |
| Unknown       | Unknown                     | [1c5f8fef49](https://linux-hardware.org/?probe=1c5f8fef49) | Feb 28, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [216ad20179](https://linux-hardware.org/?probe=216ad20179) | Feb 28, 2023 |
| Acer          | Predator G3620              | [72f3382b60](https://linux-hardware.org/?probe=72f3382b60) | Feb 27, 2023 |
| Gigabyte      | Z77X-UD5H                   | [2071bc50ce](https://linux-hardware.org/?probe=2071bc50ce) | Feb 27, 2023 |
| Gigabyte      | Z77X-UD5H                   | [472c035387](https://linux-hardware.org/?probe=472c035387) | Feb 27, 2023 |
| Dell          | 0J584C                      | [5f16a97f99](https://linux-hardware.org/?probe=5f16a97f99) | Feb 27, 2023 |
| Dell          | 07PR60 A01                  | [c071b7ef1c](https://linux-hardware.org/?probe=c071b7ef1c) | Feb 27, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | [ce9dda227f](https://linux-hardware.org/?probe=ce9dda227f) | Feb 25, 2023 |
| Gigabyte      | Z77MX-D3H                   | [bfd1042a82](https://linux-hardware.org/?probe=bfd1042a82) | Feb 25, 2023 |
| Dell          | 0J584C                      | [f0c7703e3c](https://linux-hardware.org/?probe=f0c7703e3c) | Feb 23, 2023 |
| Dell          | 0J584C                      | [003da08b72](https://linux-hardware.org/?probe=003da08b72) | Feb 22, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | [c1936488f5](https://linux-hardware.org/?probe=c1936488f5) | Feb 20, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [13a132516b](https://linux-hardware.org/?probe=13a132516b) | Feb 18, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | [76ab936a75](https://linux-hardware.org/?probe=76ab936a75) | Feb 16, 2023 |
| ASUSTek       | H110M-A/M.2                 | [68f0415788](https://linux-hardware.org/?probe=68f0415788) | Feb 16, 2023 |
| ASUSTek       | H110M-A/M.2                 | [2560ba7644](https://linux-hardware.org/?probe=2560ba7644) | Feb 16, 2023 |
| Foxconn       | 2ADA                        | [e0f89bbca1](https://linux-hardware.org/?probe=e0f89bbca1) | Feb 16, 2023 |
| HP            | 805D                        | [217784712c](https://linux-hardware.org/?probe=217784712c) | Feb 14, 2023 |
| MSI           | B85-G43 GAMING              | [b2b66e40e1](https://linux-hardware.org/?probe=b2b66e40e1) | Feb 14, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | [f0899499e5](https://linux-hardware.org/?probe=f0899499e5) | Feb 13, 2023 |
| ASUSTek       | H110M-A/M.2                 | [76711a4e32](https://linux-hardware.org/?probe=76711a4e32) | Feb 10, 2023 |
| ASUSTek       | M4A785TD-V EVO              | [aaa509fed7](https://linux-hardware.org/?probe=aaa509fed7) | Feb 09, 2023 |
| ASUSTek       | H110M-A/M.2                 | [73b3c1c661](https://linux-hardware.org/?probe=73b3c1c661) | Feb 06, 2023 |
| Gigabyte      | F2A88XM-DS2                 | [d9313ff1c1](https://linux-hardware.org/?probe=d9313ff1c1) | Feb 05, 2023 |
| ASUSTek       | P7P55 LX                    | [3786e7a211](https://linux-hardware.org/?probe=3786e7a211) | Feb 04, 2023 |
| Unknown       | IPMSB-H61                   | [7e13c996bd](https://linux-hardware.org/?probe=7e13c996bd) | Feb 02, 2023 |
| BESSTAR Te... | UM350                       | [ee1ba0e588](https://linux-hardware.org/?probe=ee1ba0e588) | Jan 30, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [c2a4529e33](https://linux-hardware.org/?probe=c2a4529e33) | Jan 30, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [e5f6f546d4](https://linux-hardware.org/?probe=e5f6f546d4) | Jan 29, 2023 |
| EVGA          | E689 $                      | [9d4b1aeaa9](https://linux-hardware.org/?probe=9d4b1aeaa9) | Jan 29, 2023 |
| EVGA          | E689 $                      | [be99ae882b](https://linux-hardware.org/?probe=be99ae882b) | Jan 28, 2023 |
| Gigabyte      | GA-990FXA-UD3               | [6e5884ec0c](https://linux-hardware.org/?probe=6e5884ec0c) | Jan 26, 2023 |
| ASUSTek       | Z87-A                       | [755bed02ff](https://linux-hardware.org/?probe=755bed02ff) | Jan 25, 2023 |
| ASUSTek       | Z87-A                       | [6ccfafe0d6](https://linux-hardware.org/?probe=6ccfafe0d6) | Jan 24, 2023 |
| Dell          | 0G261D A00                  | [ac4e94394e](https://linux-hardware.org/?probe=ac4e94394e) | Jan 24, 2023 |
| Unknown       | G41T-M7                     | [026810c423](https://linux-hardware.org/?probe=026810c423) | Jan 22, 2023 |
| Gigabyte      | Z77MX-D3H                   | [2142d5e771](https://linux-hardware.org/?probe=2142d5e771) | Jan 22, 2023 |
| Gigabyte      | Z77MX-D3H                   | [80d8c352b9](https://linux-hardware.org/?probe=80d8c352b9) | Jan 22, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [b8df2d6479](https://linux-hardware.org/?probe=b8df2d6479) | Jan 11, 2023 |
| Intel         | JSL MRD                     | [d1b9dbaae0](https://linux-hardware.org/?probe=d1b9dbaae0) | Jan 11, 2023 |
| HP            | 8643 SMVB                   | [5187413460](https://linux-hardware.org/?probe=5187413460) | Jan 07, 2023 |
| Acer          | Veriton M2631G V:1.0        | [ebbcc0dda8](https://linux-hardware.org/?probe=ebbcc0dda8) | Jan 07, 2023 |
| Unknown       | HX90                        | [af144f98b6](https://linux-hardware.org/?probe=af144f98b6) | Jan 05, 2023 |
| ASRock        | H110 Pro BTC+               | [a7ccef79ad](https://linux-hardware.org/?probe=a7ccef79ad) | Dec 30, 2022 |
| Gigabyte      | H61M-S2V-B3                 | [b3970a8e5a](https://linux-hardware.org/?probe=b3970a8e5a) | Dec 29, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [bc58be5546](https://linux-hardware.org/?probe=bc58be5546) | Dec 27, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [f9bde62142](https://linux-hardware.org/?probe=f9bde62142) | Dec 27, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [c545cf1f08](https://linux-hardware.org/?probe=c545cf1f08) | Dec 25, 2022 |
| Lenovo        | ThinkCentre M71e 3129C3G    | [cb9f99f1cf](https://linux-hardware.org/?probe=cb9f99f1cf) | Dec 23, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [2fa8510855](https://linux-hardware.org/?probe=2fa8510855) | Dec 19, 2022 |
| Foxconn       | 2ABF                        | [10e579b77e](https://linux-hardware.org/?probe=10e579b77e) | Dec 18, 2022 |
| Dell          | 08WKV3 A00                  | [f58a0ffbc3](https://linux-hardware.org/?probe=f58a0ffbc3) | Dec 13, 2022 |
| MSI           | B350 TOMAHAWK               | [0ce6563922](https://linux-hardware.org/?probe=0ce6563922) | Dec 11, 2022 |
| ASUSTek       | Z170-P                      | [5180b907e3](https://linux-hardware.org/?probe=5180b907e3) | Dec 10, 2022 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | [5ca8db90bb](https://linux-hardware.org/?probe=5ca8db90bb) | Dec 10, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [906e4966a6](https://linux-hardware.org/?probe=906e4966a6) | Dec 07, 2022 |
| ASRock        | H55M-LE                     | [9d2066a479](https://linux-hardware.org/?probe=9d2066a479) | Dec 03, 2022 |
| Fujitsu       | D3602-A1 S26361-D3602-A1    | [6f57ed994c](https://linux-hardware.org/?probe=6f57ed994c) | Dec 03, 2022 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | [62b19626ce](https://linux-hardware.org/?probe=62b19626ce) | Dec 03, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [19d93a0122](https://linux-hardware.org/?probe=19d93a0122) | Dec 03, 2022 |
| Lenovo        | ThinkCentre M70e 0809D1Y    | [0cd85fa9f3](https://linux-hardware.org/?probe=0cd85fa9f3) | Nov 30, 2022 |
| Dell          | 0TP406                      | [3eceea61d2](https://linux-hardware.org/?probe=3eceea61d2) | Nov 30, 2022 |
| Dell          | 0TP406                      | [d22689331c](https://linux-hardware.org/?probe=d22689331c) | Nov 30, 2022 |
| MSI           | IONA                        | [255f7f8dc4](https://linux-hardware.org/?probe=255f7f8dc4) | Nov 28, 2022 |
| MSI           | IONA                        | [94841f2b61](https://linux-hardware.org/?probe=94841f2b61) | Nov 28, 2022 |
| LattePanda    | Alpha                       | [be819160d5](https://linux-hardware.org/?probe=be819160d5) | Nov 26, 2022 |
| LattePanda    | Alpha                       | [b3c831db4d](https://linux-hardware.org/?probe=b3c831db4d) | Nov 26, 2022 |
| MSI           | IONA                        | [280083cfa1](https://linux-hardware.org/?probe=280083cfa1) | Nov 22, 2022 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | [4f230635de](https://linux-hardware.org/?probe=4f230635de) | Nov 19, 2022 |
| Dell          | 0RW199                      | [df40ccbcdb](https://linux-hardware.org/?probe=df40ccbcdb) | Nov 15, 2022 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [4629fb5e08](https://linux-hardware.org/?probe=4629fb5e08) | Nov 13, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | [ddca3f4758](https://linux-hardware.org/?probe=ddca3f4758) | Nov 06, 2022 |
| Gigabyte      | H310M S2H                   | [521297d21c](https://linux-hardware.org/?probe=521297d21c) | Nov 03, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [919fad100f](https://linux-hardware.org/?probe=919fad100f) | Oct 31, 2022 |
| ASUSTek       | PRIME X570-PRO              | [6d4b1d0bb3](https://linux-hardware.org/?probe=6d4b1d0bb3) | Oct 25, 2022 |
| HP            | 805D                        | [916b6f09ac](https://linux-hardware.org/?probe=916b6f09ac) | Oct 23, 2022 |
| MSI           | Z370 GAMING PLUS            | [ce623178a2](https://linux-hardware.org/?probe=ce623178a2) | Oct 16, 2022 |
| Dell          | 0D28YY A00                  | [435831fd5b](https://linux-hardware.org/?probe=435831fd5b) | Oct 15, 2022 |
| Kraftway      | KWQ67                       | [8346fc15e3](https://linux-hardware.org/?probe=8346fc15e3) | Oct 13, 2022 |
| Kraftway      | KWQ67                       | [d57d34be64](https://linux-hardware.org/?probe=d57d34be64) | Oct 13, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [88772ad191](https://linux-hardware.org/?probe=88772ad191) | Oct 11, 2022 |
| ASRock        | X370 Taichi                 | [d86c708401](https://linux-hardware.org/?probe=d86c708401) | Sep 30, 2022 |
| Gigabyte      | G41MT-S2                    | [c0b1c8ad8f](https://linux-hardware.org/?probe=c0b1c8ad8f) | Sep 27, 2022 |
| Packard Be... | IMEDIA S1300                | [13b1f0e28e](https://linux-hardware.org/?probe=13b1f0e28e) | Sep 24, 2022 |
| Packard Be... | IMEDIA S1300                | [fae2bea6f3](https://linux-hardware.org/?probe=fae2bea6f3) | Sep 19, 2022 |
| Apple         | Mac-F221BEC8                | [b5f851bd15](https://linux-hardware.org/?probe=b5f851bd15) | Sep 12, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | [335a8a059b](https://linux-hardware.org/?probe=335a8a059b) | Sep 12, 2022 |
| Gigabyte      | F2A88XM-D3HP                | [3d269171e7](https://linux-hardware.org/?probe=3d269171e7) | Sep 11, 2022 |
| ASUSTek       | P8H77-V LE                  | [ae533c2bdf](https://linux-hardware.org/?probe=ae533c2bdf) | Sep 07, 2022 |
| Acer          | Aspire X1420G               | [e48b081560](https://linux-hardware.org/?probe=e48b081560) | Sep 04, 2022 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [3a8803f198](https://linux-hardware.org/?probe=3a8803f198) | Sep 01, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | [413bd5a721](https://linux-hardware.org/?probe=413bd5a721) | Aug 29, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [9274f5e876](https://linux-hardware.org/?probe=9274f5e876) | Aug 29, 2022 |
| ASUSTek       | M2N68-AM SE2                | [0f71a52e11](https://linux-hardware.org/?probe=0f71a52e11) | Aug 28, 2022 |
| Gigabyte      | H61M-S1                     | [6bf1dafdbc](https://linux-hardware.org/?probe=6bf1dafdbc) | Aug 27, 2022 |
| Apple         | Mac-F221BEC8                | [9ffe8ee96e](https://linux-hardware.org/?probe=9ffe8ee96e) | Aug 24, 2022 |
| Apple         | Mac-F221BEC8                | [4709584652](https://linux-hardware.org/?probe=4709584652) | Aug 24, 2022 |
| MSI           | MEG Z490I UNIFY             | [34d2d4f66e](https://linux-hardware.org/?probe=34d2d4f66e) | Aug 24, 2022 |
| Foxconn       | 2ABF                        | [6d7ce1962d](https://linux-hardware.org/?probe=6d7ce1962d) | Aug 24, 2022 |
| ASRock        | N68-VGS3 FX                 | [1d2367ccf7](https://linux-hardware.org/?probe=1d2367ccf7) | Aug 23, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [595bf9c8a7](https://linux-hardware.org/?probe=595bf9c8a7) | Aug 23, 2022 |
| ASUSTek       | P7H55-M LX                  | [b545a0cf4f](https://linux-hardware.org/?probe=b545a0cf4f) | Aug 19, 2022 |
| Gigabyte      | H81M-DS2                    | [e0abb12052](https://linux-hardware.org/?probe=e0abb12052) | Aug 16, 2022 |
| HP            | 2AF7                        | [ca8820daa4](https://linux-hardware.org/?probe=ca8820daa4) | Aug 16, 2022 |
| ASUSTek       | P5B                         | [1c5cafd185](https://linux-hardware.org/?probe=1c5cafd185) | Aug 15, 2022 |
| Gigabyte      | H81M-DS2                    | [5ae2bc3c12](https://linux-hardware.org/?probe=5ae2bc3c12) | Aug 14, 2022 |
| Acer          | Aspire X1420G               | [7be7ab2e7e](https://linux-hardware.org/?probe=7be7ab2e7e) | Jul 31, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [e99805635f](https://linux-hardware.org/?probe=e99805635f) | Jul 29, 2022 |
| MSI           | B450M PRO-M2 MAX            | [ab8af10726](https://linux-hardware.org/?probe=ab8af10726) | Jul 28, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [d0a69fba02](https://linux-hardware.org/?probe=d0a69fba02) | Jul 23, 2022 |
| Dell          | 0GM819                      | [373772e538](https://linux-hardware.org/?probe=373772e538) | Jul 21, 2022 |
| Dell          | 00V62H A01                  | [ae809bb317](https://linux-hardware.org/?probe=ae809bb317) | Jul 19, 2022 |
| ASUSTek       | ROG STRIX B360-H GAMING     | [4cc1f4384c](https://linux-hardware.org/?probe=4cc1f4384c) | Jul 12, 2022 |
| Acer          | Aspire X1420G               | [0b7a9cbc2a](https://linux-hardware.org/?probe=0b7a9cbc2a) | Jul 12, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | [3db9c636d0](https://linux-hardware.org/?probe=3db9c636d0) | Jul 09, 2022 |
| MSI           | B450M PRO-VDH MAX           | [b8c450d5fa](https://linux-hardware.org/?probe=b8c450d5fa) | Jul 08, 2022 |
| Intel         | X79Turbo V1.x               | [e4b17550d0](https://linux-hardware.org/?probe=e4b17550d0) | Jul 06, 2022 |
| Gigabyte      | Z87X-OC-CF                  | [654459e245](https://linux-hardware.org/?probe=654459e245) | Jul 03, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | [80a981f992](https://linux-hardware.org/?probe=80a981f992) | Jul 01, 2022 |
| Gigabyte      | Z690 AORUS MASTER           | [a8073316f6](https://linux-hardware.org/?probe=a8073316f6) | Jun 26, 2022 |
| ASRock        | Z490 Pro4                   | [f84c8a756c](https://linux-hardware.org/?probe=f84c8a756c) | Jun 25, 2022 |
| MSI           | B85I                        | [886f971d22](https://linux-hardware.org/?probe=886f971d22) | Jun 25, 2022 |
| HP            | 339A                        | [822467af7f](https://linux-hardware.org/?probe=822467af7f) | Jun 25, 2022 |
| T-bao         | MINI PC                     | [6b18c66487](https://linux-hardware.org/?probe=6b18c66487) | Jun 18, 2022 |
| Pegatron      | 2ACD                        | [8c8275099b](https://linux-hardware.org/?probe=8c8275099b) | Jun 16, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [5b8ae292bf](https://linux-hardware.org/?probe=5b8ae292bf) | Jun 14, 2022 |
| ASUSTek       | SABERTOOTH X58              | [4cc4a7c1b3](https://linux-hardware.org/?probe=4cc4a7c1b3) | Jun 11, 2022 |
| HP            | 2B43                        | [6f36772b0c](https://linux-hardware.org/?probe=6f36772b0c) | Jun 10, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [9756188040](https://linux-hardware.org/?probe=9756188040) | Jun 07, 2022 |
| MSI           | MPG X570S CARBON MAX WIF... | [0d57c069a8](https://linux-hardware.org/?probe=0d57c069a8) | Jun 05, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN 2625... | [16f3fff6ad](https://linux-hardware.org/?probe=16f3fff6ad) | Jun 05, 2022 |
| Dell          | 0T7D40 A01                  | [812b41fe55](https://linux-hardware.org/?probe=812b41fe55) | Jun 04, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN 2625... | [b3d970d061](https://linux-hardware.org/?probe=b3d970d061) | Jun 04, 2022 |
| MSI           | B85I                        | [5f29683d93](https://linux-hardware.org/?probe=5f29683d93) | Jun 03, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | [9f4aa60f60](https://linux-hardware.org/?probe=9f4aa60f60) | Jun 02, 2022 |
| ASUSTek       | P5B                         | [12554af571](https://linux-hardware.org/?probe=12554af571) | May 31, 2022 |
| MSI           | MPG X570S CARBON MAX WIF... | [a4f2a9b24b](https://linux-hardware.org/?probe=a4f2a9b24b) | May 27, 2022 |
| MSI           | MPG X570S CARBON MAX WIF... | [3143793e8f](https://linux-hardware.org/?probe=3143793e8f) | May 27, 2022 |
| ASUSTek       | P5KPL-VM/S                  | [66223d6ef0](https://linux-hardware.org/?probe=66223d6ef0) | May 25, 2022 |
| ASUSTek       | P5KPL-VM/S                  | [d44e9d6290](https://linux-hardware.org/?probe=d44e9d6290) | May 25, 2022 |
| ASUSTek       | P8H61                       | [5514e95c95](https://linux-hardware.org/?probe=5514e95c95) | May 24, 2022 |
| ASUSTek       | P8H61                       | [873dd31f8e](https://linux-hardware.org/?probe=873dd31f8e) | May 23, 2022 |
| MSI           | H97M-P35                    | [2b5866b09d](https://linux-hardware.org/?probe=2b5866b09d) | May 23, 2022 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | [2e27b6fac9](https://linux-hardware.org/?probe=2e27b6fac9) | May 23, 2022 |
| Biostar       | GF8200C M2+                 | [b80588cbea](https://linux-hardware.org/?probe=b80588cbea) | May 21, 2022 |
| ASUSTek       | P8H61-M LE/USB3             | [6f6a104d35](https://linux-hardware.org/?probe=6f6a104d35) | May 21, 2022 |
| MSI           | B85I                        | [c822196290](https://linux-hardware.org/?probe=c822196290) | May 18, 2022 |
| MSI           | MEG X570 UNIFY              | [4d00452dcb](https://linux-hardware.org/?probe=4d00452dcb) | May 15, 2022 |
| ASUSTek       | SABERTOOTH X58              | [c276639676](https://linux-hardware.org/?probe=c276639676) | May 08, 2022 |
| ASUSTek       | H81M-K                      | [753c7be679](https://linux-hardware.org/?probe=753c7be679) | May 05, 2022 |
| ASRock        | X570 Extreme4               | [98e5f20999](https://linux-hardware.org/?probe=98e5f20999) | May 04, 2022 |
| Gigabyte      | GA-880GMA-UD2H              | [09d9f58ee7](https://linux-hardware.org/?probe=09d9f58ee7) | May 02, 2022 |
| HP            | 0B48h                       | [4c6e5824f2](https://linux-hardware.org/?probe=4c6e5824f2) | Apr 30, 2022 |
| ASUSTek       | P8Z77-V                     | [b3506ef75d](https://linux-hardware.org/?probe=b3506ef75d) | Apr 29, 2022 |
| Dell          | 0J3C2F A00                  | [464c70eb8d](https://linux-hardware.org/?probe=464c70eb8d) | Apr 27, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [1f10d820f8](https://linux-hardware.org/?probe=1f10d820f8) | Apr 27, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [dfadead480](https://linux-hardware.org/?probe=dfadead480) | Apr 27, 2022 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | [dbaaf867f6](https://linux-hardware.org/?probe=dbaaf867f6) | Apr 25, 2022 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [1b0a41c232](https://linux-hardware.org/?probe=1b0a41c232) | Apr 25, 2022 |
| AZW           | GTi                         | [e2d4a0da2e](https://linux-hardware.org/?probe=e2d4a0da2e) | Apr 23, 2022 |
| AZW           | GTi                         | [cde74551bf](https://linux-hardware.org/?probe=cde74551bf) | Apr 23, 2022 |
| ECS           | H61H2-MV                    | [939f87564f](https://linux-hardware.org/?probe=939f87564f) | Apr 21, 2022 |
| MSI           | X99A SLI PLUS               | [0b935aadb3](https://linux-hardware.org/?probe=0b935aadb3) | Apr 19, 2022 |
| Inventec      | D CLASS A02                 | [d00d37285b](https://linux-hardware.org/?probe=d00d37285b) | Apr 19, 2022 |
| ASRock        | Z490 Pro4                   | [67071d11a1](https://linux-hardware.org/?probe=67071d11a1) | Apr 18, 2022 |
| Dell          | 0KV62T A01                  | [0c6e50ed20](https://linux-hardware.org/?probe=0c6e50ed20) | Apr 17, 2022 |
| Dell          | 0KV62T A01                  | [7bed7782c4](https://linux-hardware.org/?probe=7bed7782c4) | Apr 17, 2022 |
| MSI           | B450M PRO-VDH MAX           | [e28ee0bd42](https://linux-hardware.org/?probe=e28ee0bd42) | Apr 16, 2022 |
| HP            | 1494                        | [6ad3ca1745](https://linux-hardware.org/?probe=6ad3ca1745) | Apr 16, 2022 |
| Gigabyte      | H61M-D2H-USB3               | [016243a675](https://linux-hardware.org/?probe=016243a675) | Apr 15, 2022 |
| Fujitsu       | D3531-A1 S26361-D3531-A1    | [46dd533a5e](https://linux-hardware.org/?probe=46dd533a5e) | Apr 14, 2022 |
| ASUSTek       | B85M-G                      | [c6dd82e724](https://linux-hardware.org/?probe=c6dd82e724) | Apr 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [dff6de5032](https://linux-hardware.org/?probe=dff6de5032) | Apr 14, 2022 |
| ASUSTek       | B85M-G                      | [e525a26ca8](https://linux-hardware.org/?probe=e525a26ca8) | Apr 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [6a2c5f12fd](https://linux-hardware.org/?probe=6a2c5f12fd) | Apr 13, 2022 |
| Dell          | 0K240Y A01                  | [76d4fbf0a6](https://linux-hardware.org/?probe=76d4fbf0a6) | Apr 13, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | [3440d2dd8c](https://linux-hardware.org/?probe=3440d2dd8c) | Apr 12, 2022 |
| Lenovo        | 3178 SDK0J40700 WIN 3258... | [637023ab6d](https://linux-hardware.org/?probe=637023ab6d) | Apr 11, 2022 |
| ASUSTek       | PRIME Z390-A                | [21767e12e4](https://linux-hardware.org/?probe=21767e12e4) | Apr 11, 2022 |
| Pegatron      | IPMH61P1                    | [1adcf74c4f](https://linux-hardware.org/?probe=1adcf74c4f) | Apr 10, 2022 |
| ASUSTek       | H110I-PLUS                  | [e367ac99ce](https://linux-hardware.org/?probe=e367ac99ce) | Apr 10, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [1c357065cb](https://linux-hardware.org/?probe=1c357065cb) | Apr 07, 2022 |
| ASRock        | C226 WS                     | [7c11c1ec43](https://linux-hardware.org/?probe=7c11c1ec43) | Apr 07, 2022 |
| ASUSTek       | STRIKER II FORMULA          | [5dfea21930](https://linux-hardware.org/?probe=5dfea21930) | Apr 07, 2022 |
| ASUSTek       | STRIKER II FORMULA          | [040990b3fc](https://linux-hardware.org/?probe=040990b3fc) | Apr 07, 2022 |
| Gigabyte      | B450M DS3H-CF               | [0bc837ffef](https://linux-hardware.org/?probe=0bc837ffef) | Apr 06, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [7419ad6a76](https://linux-hardware.org/?probe=7419ad6a76) | Apr 02, 2022 |
| Lenovo        | ThinkCentre M58 6258D3G     | [b67f1750b8](https://linux-hardware.org/?probe=b67f1750b8) | Mar 31, 2022 |
| Lenovo        | ThinkCentre M58 6258D3G     | [1cd22c83f1](https://linux-hardware.org/?probe=1cd22c83f1) | Mar 31, 2022 |
| MSI           | H97 GAMING 3                | [97f38615e3](https://linux-hardware.org/?probe=97f38615e3) | Mar 31, 2022 |
| MSI           | MEG X570 ACE                | [55572b8a7e](https://linux-hardware.org/?probe=55572b8a7e) | Mar 31, 2022 |
| HP            | 18E7                        | [ead4fcc358](https://linux-hardware.org/?probe=ead4fcc358) | Mar 29, 2022 |
| ASUSTek       | Rampage IV GENE             | [c067a4d0e7](https://linux-hardware.org/?probe=c067a4d0e7) | Mar 29, 2022 |
| Dell          | 0C522T A00                  | [33ae998152](https://linux-hardware.org/?probe=33ae998152) | Mar 26, 2022 |
| Dell          | 0C522T A00                  | [90242bb090](https://linux-hardware.org/?probe=90242bb090) | Mar 26, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [7577679057](https://linux-hardware.org/?probe=7577679057) | Mar 25, 2022 |
| Gigabyte      | A320M-S2H-CF                | [a237859a86](https://linux-hardware.org/?probe=a237859a86) | Mar 24, 2022 |
| Intel         | X79Turbo V1.x               | [18b126a753](https://linux-hardware.org/?probe=18b126a753) | Mar 24, 2022 |
| AMI           | Cherry Trail CR             | [bbea34ce64](https://linux-hardware.org/?probe=bbea34ce64) | Mar 22, 2022 |
| AMI           | Cherry Trail CR             | [bc5a34ef7e](https://linux-hardware.org/?probe=bc5a34ef7e) | Mar 20, 2022 |
| ASUSTek       | Rampage IV GENE             | [7f5053b061](https://linux-hardware.org/?probe=7f5053b061) | Mar 16, 2022 |
| ASUSTek       | Rampage IV GENE             | [7ff55a3ca6](https://linux-hardware.org/?probe=7ff55a3ca6) | Mar 16, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [eda8848760](https://linux-hardware.org/?probe=eda8848760) | Mar 15, 2022 |
| AOpen         | D1009 A1A4                  | [a7375d4581](https://linux-hardware.org/?probe=a7375d4581) | Mar 13, 2022 |
| MSI           | B85I                        | [d134c8451b](https://linux-hardware.org/?probe=d134c8451b) | Mar 12, 2022 |
| ASRock        | B450M Pro4                  | [12459fc7ea](https://linux-hardware.org/?probe=12459fc7ea) | Mar 11, 2022 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | [a64818ccea](https://linux-hardware.org/?probe=a64818ccea) | Mar 10, 2022 |
| Biostar       | N68S3B                      | [aa1e6a4c82](https://linux-hardware.org/?probe=aa1e6a4c82) | Mar 10, 2022 |
| Dell          | 0HMX8D A01                  | [cfff92df80](https://linux-hardware.org/?probe=cfff92df80) | Mar 09, 2022 |
| ASUSTek       | M11AD                       | [8bb5baaa5a](https://linux-hardware.org/?probe=8bb5baaa5a) | Mar 09, 2022 |
| Biostar       | H61MLV2                     | [d5c330bad8](https://linux-hardware.org/?probe=d5c330bad8) | Mar 08, 2022 |
| HP            | 2ADC                        | [ed0714a64a](https://linux-hardware.org/?probe=ed0714a64a) | Mar 07, 2022 |
| MSI           | B85I                        | [39926596b7](https://linux-hardware.org/?probe=39926596b7) | Mar 07, 2022 |
| Dell          | 0PU052                      | [766b0e4665](https://linux-hardware.org/?probe=766b0e4665) | Mar 06, 2022 |
| Dell          | 0PU052                      | [a8e19bd112](https://linux-hardware.org/?probe=a8e19bd112) | Mar 06, 2022 |
| HP            | 1589                        | [88876808e9](https://linux-hardware.org/?probe=88876808e9) | Mar 05, 2022 |
| HP            | 802E                        | [14c73a40e0](https://linux-hardware.org/?probe=14c73a40e0) | Mar 05, 2022 |
| ASRock        | FM2A58M-DG3+                | [0b7875b1b5](https://linux-hardware.org/?probe=0b7875b1b5) | Mar 05, 2022 |
| ASUSTek       | M4N72-E                     | [c3fe570b4d](https://linux-hardware.org/?probe=c3fe570b4d) | Feb 28, 2022 |
| ASUSTek       | H81-PLUS                    | [e8956dc4ec](https://linux-hardware.org/?probe=e8956dc4ec) | Feb 27, 2022 |
| ASUSTek       | H81-PLUS                    | [9c68dfb511](https://linux-hardware.org/?probe=9c68dfb511) | Feb 26, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [a6d5cc0368](https://linux-hardware.org/?probe=a6d5cc0368) | Feb 26, 2022 |
| Gigabyte      | Z390 UD                     | [7ea66813f3](https://linux-hardware.org/?probe=7ea66813f3) | Feb 23, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [73b31ddab0](https://linux-hardware.org/?probe=73b31ddab0) | Feb 20, 2022 |
| Intel         | DH61BE AAG14062-210         | [00566bb73f](https://linux-hardware.org/?probe=00566bb73f) | Feb 19, 2022 |
| ASUSTek       | M11AD                       | [035887c4ab](https://linux-hardware.org/?probe=035887c4ab) | Feb 18, 2022 |
| ASUSTek       | P5B                         | [fa4c095fd7](https://linux-hardware.org/?probe=fa4c095fd7) | Feb 17, 2022 |
| Intel         | H61                         | [a70c59ad0e](https://linux-hardware.org/?probe=a70c59ad0e) | Feb 17, 2022 |
| ASUSTek       | PRIME Z590-A                | [6beda6e2da](https://linux-hardware.org/?probe=6beda6e2da) | Feb 16, 2022 |
| Biostar       | A68MD PRO                   | [da42cc4da7](https://linux-hardware.org/?probe=da42cc4da7) | Feb 16, 2022 |
| ASUSTek       | PRIME B250-PRO              | [be377c733e](https://linux-hardware.org/?probe=be377c733e) | Feb 14, 2022 |
| ASUSTek       | PRIME Z590-A                | [825734953d](https://linux-hardware.org/?probe=825734953d) | Feb 13, 2022 |
| MSI           | B85I                        | [898dced271](https://linux-hardware.org/?probe=898dced271) | Feb 13, 2022 |
| Gigabyte      | F2A68HM-H                   | [a2a41e039c](https://linux-hardware.org/?probe=a2a41e039c) | Feb 13, 2022 |
| Gigabyte      | F2A68HM-H                   | [2f3941c9cb](https://linux-hardware.org/?probe=2f3941c9cb) | Feb 12, 2022 |
| ASUSTek       | PRIME A320M-K               | [5f4de1e2b0](https://linux-hardware.org/?probe=5f4de1e2b0) | Feb 12, 2022 |
| ASUSTek       | PRIME B360M-K               | [698e174402](https://linux-hardware.org/?probe=698e174402) | Feb 09, 2022 |
| ASUSTek       | H110M-C                     | [82f3d6edf9](https://linux-hardware.org/?probe=82f3d6edf9) | Feb 09, 2022 |
| MSI           | B450I GAMING PLUS AC        | [a2af859752](https://linux-hardware.org/?probe=a2af859752) | Feb 09, 2022 |
| ECS           | H55H-M                      | [856a42d74b](https://linux-hardware.org/?probe=856a42d74b) | Feb 07, 2022 |
| Lenovo        | NO DPK                      | [4bb7cedbd8](https://linux-hardware.org/?probe=4bb7cedbd8) | Feb 06, 2022 |
| HP            | 802E                        | [31e2fe159c](https://linux-hardware.org/?probe=31e2fe159c) | Feb 05, 2022 |
| ASUSTek       | H110M-C                     | [6ba127c715](https://linux-hardware.org/?probe=6ba127c715) | Feb 04, 2022 |
| ASUSTek       | P5B                         | [9b661f64dd](https://linux-hardware.org/?probe=9b661f64dd) | Feb 04, 2022 |
| Foxconn       | NETBOX nT-435/535 Ver       | [c7d50db62b](https://linux-hardware.org/?probe=c7d50db62b) | Feb 03, 2022 |
| Foxconn       | NETBOX nT-435/535 Ver       | [2ee2be7ccf](https://linux-hardware.org/?probe=2ee2be7ccf) | Feb 03, 2022 |
| HP            | ProLiant ML110 G7           | [2e1dcafe6c](https://linux-hardware.org/?probe=2e1dcafe6c) | Feb 03, 2022 |
| HP            | 339A                        | [cf9dca84ff](https://linux-hardware.org/?probe=cf9dca84ff) | Feb 02, 2022 |
| Unknown       | Unknown                     | [629972c689](https://linux-hardware.org/?probe=629972c689) | Feb 01, 2022 |
| HP            | 805D                        | [19295e5827](https://linux-hardware.org/?probe=19295e5827) | Feb 01, 2022 |
| ASUSTek       | H110I-PLUS                  | [ebeaf681e3](https://linux-hardware.org/?probe=ebeaf681e3) | Feb 01, 2022 |
| Gigabyte      | B75M-D3H                    | [18717f0712](https://linux-hardware.org/?probe=18717f0712) | Feb 01, 2022 |
| MSI           | Z270 KRAIT GAMING           | [17ccbf9c76](https://linux-hardware.org/?probe=17ccbf9c76) | Jan 28, 2022 |
| Gigabyte      | H61M-DS2                    | [e800b95c58](https://linux-hardware.org/?probe=e800b95c58) | Jan 26, 2022 |
| ASRock        | H61M-HVS                    | [8fdf1980ee](https://linux-hardware.org/?probe=8fdf1980ee) | Jan 25, 2022 |
| ASRock        | H61M-HVS                    | [5d19dff1e4](https://linux-hardware.org/?probe=5d19dff1e4) | Jan 25, 2022 |
| Acer          | ConceptD CM100-51A V:1.1    | [663bbd709d](https://linux-hardware.org/?probe=663bbd709d) | Jan 24, 2022 |
| FIRICH        | J1900                       | [937e24af64](https://linux-hardware.org/?probe=937e24af64) | Jan 22, 2022 |
| ASUSTek       | ROG STRIX B360-H GAMING     | [d1505fe489](https://linux-hardware.org/?probe=d1505fe489) | Jan 21, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [75d67cd8a4](https://linux-hardware.org/?probe=75d67cd8a4) | Jan 20, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [7a14d864d4](https://linux-hardware.org/?probe=7a14d864d4) | Jan 20, 2022 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [ec51f5ca3e](https://linux-hardware.org/?probe=ec51f5ca3e) | Jan 19, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [488d339e77](https://linux-hardware.org/?probe=488d339e77) | Jan 19, 2022 |
| MSI           | B450M-A PRO MAX             | [e7225dad8e](https://linux-hardware.org/?probe=e7225dad8e) | Jan 17, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [a76b9e67bb](https://linux-hardware.org/?probe=a76b9e67bb) | Jan 14, 2022 |
| ASUSTek       | H61M-CS                     | [8855875fbd](https://linux-hardware.org/?probe=8855875fbd) | Jan 14, 2022 |
| Unknown       | T3 MRD                      | [33392a90ce](https://linux-hardware.org/?probe=33392a90ce) | Jan 13, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [00a00c3cac](https://linux-hardware.org/?probe=00a00c3cac) | Jan 13, 2022 |
| ASUSTek       | M5A78L-M LX3                | [39f3687349](https://linux-hardware.org/?probe=39f3687349) | Jan 12, 2022 |
| Foxconn       | 2AB1                        | [07faf9a309](https://linux-hardware.org/?probe=07faf9a309) | Jan 12, 2022 |
| ASUSTek       | H110M-C                     | [be4291793d](https://linux-hardware.org/?probe=be4291793d) | Jan 10, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [7ce29e0c54](https://linux-hardware.org/?probe=7ce29e0c54) | Jan 09, 2022 |
| HP            | 8597                        | [09ed815dd0](https://linux-hardware.org/?probe=09ed815dd0) | Jan 08, 2022 |
| Gigabyte      | GA-970A-D3                  | [b1c9832ce6](https://linux-hardware.org/?probe=b1c9832ce6) | Jan 07, 2022 |
| ASRock        | Z370 Pro4                   | [51cba69624](https://linux-hardware.org/?probe=51cba69624) | Jan 06, 2022 |
| ASRock        | B450M-HDV R4.0              | [20dfc25b62](https://linux-hardware.org/?probe=20dfc25b62) | Jan 05, 2022 |
| ASRock        | H97M Pro4                   | [92a6f429b5](https://linux-hardware.org/?probe=92a6f429b5) | Jan 05, 2022 |
| ASRock        | AB350M Pro4                 | [2886b84cc0](https://linux-hardware.org/?probe=2886b84cc0) | Jan 04, 2022 |
| Gigabyte      | B85M-DS3H-A                 | [cd6abb9f49](https://linux-hardware.org/?probe=cd6abb9f49) | Jan 03, 2022 |
| MSI           | 2A9C                        | [8d08f7f383](https://linux-hardware.org/?probe=8d08f7f383) | Dec 31, 2021 |
| HP            | 3397                        | [323dc8992b](https://linux-hardware.org/?probe=323dc8992b) | Dec 31, 2021 |
| ASUSTek       | X79-DELUXE                  | [00b9dd3788](https://linux-hardware.org/?probe=00b9dd3788) | Dec 30, 2021 |
| HP            | 1589                        | [d123a8de64](https://linux-hardware.org/?probe=d123a8de64) | Dec 30, 2021 |
| Foxconn       | 2AB1                        | [bcd6fc46cc](https://linux-hardware.org/?probe=bcd6fc46cc) | Dec 30, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [5f67c759fe](https://linux-hardware.org/?probe=5f67c759fe) | Dec 28, 2021 |
| Gigabyte      | Z390 UD                     | [2399fa64ba](https://linux-hardware.org/?probe=2399fa64ba) | Dec 26, 2021 |
| ASRock        | Z590 Phantom Gaming 4/ac    | [b52ca671f7](https://linux-hardware.org/?probe=b52ca671f7) | Dec 24, 2021 |
| Apple         | Mac-F42C88C8 Proto1         | [783618fe4b](https://linux-hardware.org/?probe=783618fe4b) | Dec 23, 2021 |
| ASUSTek       | H97-PLUS                    | [cba91c2ad2](https://linux-hardware.org/?probe=cba91c2ad2) | Dec 22, 2021 |
| MSI           | B450-A PRO MAX              | [f14eef1ae6](https://linux-hardware.org/?probe=f14eef1ae6) | Dec 20, 2021 |
| Gigabyte      | H310M S2P                   | [a931eb10f0](https://linux-hardware.org/?probe=a931eb10f0) | Dec 19, 2021 |
| Foxconn       | 2AB1                        | [b789981cc4](https://linux-hardware.org/?probe=b789981cc4) | Dec 17, 2021 |
| Gigabyte      | Z590 AORUS ELITE AX         | [c068e358e8](https://linux-hardware.org/?probe=c068e358e8) | Dec 16, 2021 |
| ASUSTek       | M5A78L-M LX3                | [720cc7a45f](https://linux-hardware.org/?probe=720cc7a45f) | Dec 15, 2021 |
| Pegatron      | IPMH61P1                    | [1ba6ea2ee9](https://linux-hardware.org/?probe=1ba6ea2ee9) | Dec 14, 2021 |
| Acer          | ConceptD CM100-51A V:1.1    | [0b3e5753fc](https://linux-hardware.org/?probe=0b3e5753fc) | Dec 13, 2021 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [5c0550c1e8](https://linux-hardware.org/?probe=5c0550c1e8) | Dec 09, 2021 |
| ASUSTek       | PRIME A320M-K               | [fc49eed81d](https://linux-hardware.org/?probe=fc49eed81d) | Dec 09, 2021 |
| ASUSTek       | H81M-C                      | [0b0241baf7](https://linux-hardware.org/?probe=0b0241baf7) | Dec 08, 2021 |
| Dell          | 0MGK50 A02                  | [df4bb96e67](https://linux-hardware.org/?probe=df4bb96e67) | Dec 08, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | [5c46f5e832](https://linux-hardware.org/?probe=5c46f5e832) | Dec 07, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | [a8e4016566](https://linux-hardware.org/?probe=a8e4016566) | Dec 06, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | [ebfed157e7](https://linux-hardware.org/?probe=ebfed157e7) | Dec 06, 2021 |
| Acer          | Aspire X3990                | [e291d06394](https://linux-hardware.org/?probe=e291d06394) | Dec 05, 2021 |
| MSI           | Z370 KRAIT GAMING           | [b213dc07b8](https://linux-hardware.org/?probe=b213dc07b8) | Dec 04, 2021 |
| MSI           | Z370 KRAIT GAMING           | [b562e90f75](https://linux-hardware.org/?probe=b562e90f75) | Dec 04, 2021 |
| ASRock        | Z370 Pro4                   | [4ada22b406](https://linux-hardware.org/?probe=4ada22b406) | Dec 04, 2021 |
| Pegatron      | Benicia                     | [51dae15bcd](https://linux-hardware.org/?probe=51dae15bcd) | Dec 03, 2021 |
| HP            | 8653 A                      | [85d1730019](https://linux-hardware.org/?probe=85d1730019) | Dec 01, 2021 |
| Gigabyte      | B85M-DS3H-A                 | [fbe4820444](https://linux-hardware.org/?probe=fbe4820444) | Dec 01, 2021 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | [500f9c8851](https://linux-hardware.org/?probe=500f9c8851) | Dec 01, 2021 |
| ASUSTek       | PRIME B365M-A               | [c7cbb50843](https://linux-hardware.org/?probe=c7cbb50843) | Nov 30, 2021 |
| Biostar       | TH55XE                      | [9e420cc495](https://linux-hardware.org/?probe=9e420cc495) | Nov 28, 2021 |
| MSI           | H81M-P33                    | [8812103632](https://linux-hardware.org/?probe=8812103632) | Nov 28, 2021 |
| HP            | 1497                        | [6f042fb99c](https://linux-hardware.org/?probe=6f042fb99c) | Nov 28, 2021 |
| ASUSTek       | PRIME X470-PRO              | [2845eaa223](https://linux-hardware.org/?probe=2845eaa223) | Nov 27, 2021 |
| Acer          | Aspire X3990                | [5559b2d988](https://linux-hardware.org/?probe=5559b2d988) | Nov 27, 2021 |
| Foxconn       | 2AB1                        | [09a8a91f9e](https://linux-hardware.org/?probe=09a8a91f9e) | Nov 26, 2021 |
| HP            | 1825                        | [3648c360a9](https://linux-hardware.org/?probe=3648c360a9) | Nov 26, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [ee1387e206](https://linux-hardware.org/?probe=ee1387e206) | Nov 26, 2021 |
| Gigabyte      | Z390 GAMING X-CF            | [34e71f1e27](https://linux-hardware.org/?probe=34e71f1e27) | Nov 25, 2021 |
| Gigabyte      | B450M DS3H-CF               | [0fccfea38c](https://linux-hardware.org/?probe=0fccfea38c) | Nov 25, 2021 |
| ASUSTek       | P8H61-MX R2.0               | [1e15277ce2](https://linux-hardware.org/?probe=1e15277ce2) | Nov 22, 2021 |
| Biostar       | TA790GXE 128M               | [93ff10a9c2](https://linux-hardware.org/?probe=93ff10a9c2) | Nov 21, 2021 |
| Gigabyte      | B85M-D3V-A                  | [12bcc06e6e](https://linux-hardware.org/?probe=12bcc06e6e) | Nov 21, 2021 |
| MSI           | X470 GAMING PLUS MAX        | [9e7d926319](https://linux-hardware.org/?probe=9e7d926319) | Nov 19, 2021 |
| HP            | 0AECh D                     | [c81bcc92ca](https://linux-hardware.org/?probe=c81bcc92ca) | Nov 19, 2021 |
| Foxconn       | 2AB1                        | [f965bf0bd8](https://linux-hardware.org/?probe=f965bf0bd8) | Nov 18, 2021 |
| Apple         | Mac-F4208DC8 PVT            | [3369764322](https://linux-hardware.org/?probe=3369764322) | Nov 17, 2021 |
| Gigabyte      | EP43T-USB3                  | [a24bb09910](https://linux-hardware.org/?probe=a24bb09910) | Nov 15, 2021 |
| Gigabyte      | H81M-H                      | [a895ed29e0](https://linux-hardware.org/?probe=a895ed29e0) | Nov 14, 2021 |
| ASRock        | X570 Extreme4               | [e49fdf2db4](https://linux-hardware.org/?probe=e49fdf2db4) | Nov 13, 2021 |
| MSI           | 970A-G43                    | [19714dd1a0](https://linux-hardware.org/?probe=19714dd1a0) | Nov 08, 2021 |
| Gigabyte      | Z270X-Gaming 5              | [5244244701](https://linux-hardware.org/?probe=5244244701) | Nov 08, 2021 |
| Intel         | DG35EC AAE29266-205         | [89c665e43d](https://linux-hardware.org/?probe=89c665e43d) | Nov 02, 2021 |
| Intel         | DG35EC AAE29266-205         | [1046b28a41](https://linux-hardware.org/?probe=1046b28a41) | Nov 02, 2021 |
| ASRock        | P67 Extreme4                | [a70eb2d3f8](https://linux-hardware.org/?probe=a70eb2d3f8) | Oct 29, 2021 |
| ASRock        | P67 Extreme4                | [0a07f4c735](https://linux-hardware.org/?probe=0a07f4c735) | Oct 29, 2021 |
| MSI           | 2A9Ch                       | [2f752a1a3e](https://linux-hardware.org/?probe=2f752a1a3e) | Oct 28, 2021 |
| Foxconn       | 2AB1                        | [49aef5b72e](https://linux-hardware.org/?probe=49aef5b72e) | Oct 26, 2021 |
| HP            | 158B                        | [24399f4e69](https://linux-hardware.org/?probe=24399f4e69) | Oct 20, 2021 |
| HP            | 339A                        | [d9c6208191](https://linux-hardware.org/?probe=d9c6208191) | Oct 16, 2021 |
| Dell          | 0M9KCM A02                  | [a925b0f3d1](https://linux-hardware.org/?probe=a925b0f3d1) | Oct 12, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | [f6e75d0258](https://linux-hardware.org/?probe=f6e75d0258) | Oct 09, 2021 |
| MSI           | B460M PRO-VDH WIFI          | [05711b548f](https://linux-hardware.org/?probe=05711b548f) | Oct 03, 2021 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [de0f051658](https://linux-hardware.org/?probe=de0f051658) | Oct 02, 2021 |
| Shuttle       | FS61                        | [b25047a516](https://linux-hardware.org/?probe=b25047a516) | Oct 01, 2021 |
| Gigabyte      | H67A-USB3-B3                | [9440c234ae](https://linux-hardware.org/?probe=9440c234ae) | Sep 28, 2021 |
| Apple         | Mac-F221BEC8                | [1754c64091](https://linux-hardware.org/?probe=1754c64091) | Sep 27, 2021 |
| ASUSTek       | P7H55-M                     | [3367bc011a](https://linux-hardware.org/?probe=3367bc011a) | Sep 25, 2021 |
| Dell          | 0Y5DDC A00                  | [df95ea94b8](https://linux-hardware.org/?probe=df95ea94b8) | Sep 25, 2021 |
| Dell          | 0Y5DDC A00                  | [10ee1abc07](https://linux-hardware.org/?probe=10ee1abc07) | Sep 25, 2021 |
| ASRock        | M3A790GXH/128M              | [818ec10ec8](https://linux-hardware.org/?probe=818ec10ec8) | Sep 24, 2021 |
| Gigabyte      | H67A-USB3-B3                | [0aab60dbc8](https://linux-hardware.org/?probe=0aab60dbc8) | Sep 24, 2021 |
| Intel         | X79 V1.x                    | [19223e911c](https://linux-hardware.org/?probe=19223e911c) | Sep 22, 2021 |
| Gigabyte      | H67A-USB3-B3                | [772b49f342](https://linux-hardware.org/?probe=772b49f342) | Sep 21, 2021 |
| ASUSTek       | M4N78-AM                    | [3d8e0efc00](https://linux-hardware.org/?probe=3d8e0efc00) | Sep 21, 2021 |
| ASRock        | A320M-HDV                   | [24bb7c7d18](https://linux-hardware.org/?probe=24bb7c7d18) | Sep 17, 2021 |
| Gigabyte      | Z68P-DS3                    | [1ddd2fcf1d](https://linux-hardware.org/?probe=1ddd2fcf1d) | Sep 14, 2021 |
| Intel         | H61                         | [0010dbcb5e](https://linux-hardware.org/?probe=0010dbcb5e) | Sep 10, 2021 |
| HP            | 8767 A                      | [7f022c67ac](https://linux-hardware.org/?probe=7f022c67ac) | Sep 09, 2021 |
| Gigabyte      | B450M DS3H V2               | [633441bc2b](https://linux-hardware.org/?probe=633441bc2b) | Sep 05, 2021 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [c9476d5d06](https://linux-hardware.org/?probe=c9476d5d06) | Sep 02, 2021 |
| Gigabyte      | F2A55M-HD2                  | [0c05ab5b21](https://linux-hardware.org/?probe=0c05ab5b21) | Aug 30, 2021 |
| ASRock        | H81TM-ITX R2.0              | [4f04e7309e](https://linux-hardware.org/?probe=4f04e7309e) | Aug 30, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | [d0ff1c6977](https://linux-hardware.org/?probe=d0ff1c6977) | Aug 25, 2021 |
| ASUSTek       | P6X58D-E                    | [db1ef28e92](https://linux-hardware.org/?probe=db1ef28e92) | Aug 20, 2021 |
| MSI           | X470 GAMING PLUS MAX        | [1176a287c7](https://linux-hardware.org/?probe=1176a287c7) | Aug 19, 2021 |
| ASUSTek       | TUF Gaming B450M-PRO II     | [73beb900ea](https://linux-hardware.org/?probe=73beb900ea) | Aug 15, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [e302074e5e](https://linux-hardware.org/?probe=e302074e5e) | Aug 14, 2021 |
| Gigabyte      | H310M M.2 x.x               | [69e2e83b95](https://linux-hardware.org/?probe=69e2e83b95) | Aug 10, 2021 |
| Gigabyte      | H310M M.2 x.x               | [86d69a15b9](https://linux-hardware.org/?probe=86d69a15b9) | Aug 10, 2021 |
| Acer          | Aspire XC-603G              | [8a37f28ecc](https://linux-hardware.org/?probe=8a37f28ecc) | Jul 31, 2021 |
| ASUSTek       | P5KPL-AM SE                 | [a97fc63d3d](https://linux-hardware.org/?probe=a97fc63d3d) | Jul 23, 2021 |
| Biostar       | H61MH                       | [adca68749a](https://linux-hardware.org/?probe=adca68749a) | Jul 23, 2021 |
| Biostar       | H61MH                       | [2c690e433f](https://linux-hardware.org/?probe=2c690e433f) | Jul 23, 2021 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | [9e27318e84](https://linux-hardware.org/?probe=9e27318e84) | Jul 14, 2021 |
| ASRock        | B450 Pro4                   | [c5d0611f79](https://linux-hardware.org/?probe=c5d0611f79) | Jun 13, 2021 |
| ASUSTek       | PRIME A320M-K               | [5e0580b431](https://linux-hardware.org/?probe=5e0580b431) | Jun 08, 2021 |
| ASUSTek       | H81M-K                      | [52fa7c5a31](https://linux-hardware.org/?probe=52fa7c5a31) | May 30, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [63da02a979](https://linux-hardware.org/?probe=63da02a979) | May 19, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [223234378e](https://linux-hardware.org/?probe=223234378e) | May 04, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [a208e8a358](https://linux-hardware.org/?probe=a208e8a358) | May 01, 2021 |
| Gigabyte      | AB350M-DS3H V2-CF           | [98d6e8f2d2](https://linux-hardware.org/?probe=98d6e8f2d2) | Apr 15, 2021 |
| ASUSTek       | SABERTOOTH Z87              | [542d0b7163](https://linux-hardware.org/?probe=542d0b7163) | Apr 13, 2021 |
| Dell          | 06NWYK A01                  | [304541ce36](https://linux-hardware.org/?probe=304541ce36) | Apr 08, 2021 |
| Dell          | 06NWYK A01                  | [47766de8d9](https://linux-hardware.org/?probe=47766de8d9) | Apr 07, 2021 |
| MSI           | H61M-P31                    | [867b109a0b](https://linux-hardware.org/?probe=867b109a0b) | Apr 07, 2021 |
| HP            | 843F                        | [d5b68ba3fb](https://linux-hardware.org/?probe=d5b68ba3fb) | Apr 07, 2021 |
| MSI           | B450M PRO-VDH MAX           | [9a1463fd59](https://linux-hardware.org/?probe=9a1463fd59) | Mar 22, 2021 |
| Gigabyte      | H61M-S2PV                   | [bbe4962b33](https://linux-hardware.org/?probe=bbe4962b33) | Mar 22, 2021 |
| HP            | 843F                        | [a4fc49c430](https://linux-hardware.org/?probe=a4fc49c430) | Mar 09, 2021 |
| MSI           | B450M PRO-VDH MAX           | [65c7806bad](https://linux-hardware.org/?probe=65c7806bad) | Mar 09, 2021 |
| MSI           | B450M PRO-VDH MAX           | [e1289a40a1](https://linux-hardware.org/?probe=e1289a40a1) | Feb 28, 2021 |
| Lenovo        | MAHOBAY NOK                 | [e3c14a6397](https://linux-hardware.org/?probe=e3c14a6397) | Feb 25, 2021 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [268b9f895a](https://linux-hardware.org/?probe=268b9f895a) | Feb 10, 2021 |
| Gigabyte      | Z77-DS3H                    | [a5a556b691](https://linux-hardware.org/?probe=a5a556b691) | Feb 09, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | [ea93e4d3cd](https://linux-hardware.org/?probe=ea93e4d3cd) | Feb 09, 2021 |
| MSI           | B450M PRO-VDH MAX           | [895ec88c20](https://linux-hardware.org/?probe=895ec88c20) | Feb 08, 2021 |
| ASRock        | Z75 Pro3                    | [f2d919b5c5](https://linux-hardware.org/?probe=f2d919b5c5) | Feb 03, 2021 |
| Biostar       | Hi-Fi A70U3P                | [c2727e98b9](https://linux-hardware.org/?probe=c2727e98b9) | Feb 02, 2021 |
| Biostar       | Hi-Fi A70U3P                | [2c11d020c7](https://linux-hardware.org/?probe=2c11d020c7) | Feb 02, 2021 |
| MSI           | B450M PRO-VDH MAX           | [98cc7a4bca](https://linux-hardware.org/?probe=98cc7a4bca) | Jan 15, 2021 |
| Gigabyte      | GA-MA78GM-S2H               | [d40272076d](https://linux-hardware.org/?probe=d40272076d) | Jan 13, 2021 |
| Gigabyte      | GA-MA78GM-S2H               | [d31c109973](https://linux-hardware.org/?probe=d31c109973) | Jan 13, 2021 |
| EVGA          | 132-CK-NF79 2               | [44c54ae3df](https://linux-hardware.org/?probe=44c54ae3df) | Jan 09, 2021 |
| MSI           | P35 Platinum                | [105ebcfc8d](https://linux-hardware.org/?probe=105ebcfc8d) | Jan 08, 2021 |
| Gigabyte      | G31M-ES2L                   | [4e7d5b4879](https://linux-hardware.org/?probe=4e7d5b4879) | Jan 07, 2021 |
| ASUSTek       | M5A97                       | [0f975cd5e6](https://linux-hardware.org/?probe=0f975cd5e6) | Jan 03, 2021 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [721dd0a694](https://linux-hardware.org/?probe=721dd0a694) | Jan 03, 2021 |
| MSI           | B450M PRO-VDH MAX           | [7197a45b8a](https://linux-hardware.org/?probe=7197a45b8a) | Dec 30, 2020 |
| Dell          | 0T656F A02                  | [1830ce642b](https://linux-hardware.org/?probe=1830ce642b) | Dec 29, 2020 |
| ASUSTek       | M5A97                       | [800aa16703](https://linux-hardware.org/?probe=800aa16703) | Dec 29, 2020 |
| HP            | 18EA                        | [67e2e927b6](https://linux-hardware.org/?probe=67e2e927b6) | Dec 27, 2020 |
| MSI           | B450M PRO-VDH MAX           | [803e6b6194](https://linux-hardware.org/?probe=803e6b6194) | Dec 25, 2020 |
| ASUSTek       | M5A99X EVO R2.0             | [f7d949f5a7](https://linux-hardware.org/?probe=f7d949f5a7) | Dec 23, 2020 |
| Biostar       | TA785G3 HD                  | [ed91ded9e9](https://linux-hardware.org/?probe=ed91ded9e9) | Dec 23, 2020 |
| ASRock        | Z87E-ITX                    | [861b40ea1d](https://linux-hardware.org/?probe=861b40ea1d) | Dec 21, 2020 |
| Dell          | 0GN723                      | [a952bf5fa6](https://linux-hardware.org/?probe=a952bf5fa6) | Dec 20, 2020 |
| HP            | 8433 11                     | [691ef58a05](https://linux-hardware.org/?probe=691ef58a05) | Dec 09, 2020 |
| ASUSTek       | PRIME H310M-E R2.0          | [3070faaf5e](https://linux-hardware.org/?probe=3070faaf5e) | Dec 03, 2020 |
| Gigabyte      | H61M-DS2                    | [49263df7ee](https://linux-hardware.org/?probe=49263df7ee) | Dec 02, 2020 |
| HP            | 304Bh                       | [d30d065810](https://linux-hardware.org/?probe=d30d065810) | Nov 30, 2020 |
| Gigabyte      | Z77M-D3H                    | [47c75561ac](https://linux-hardware.org/?probe=47c75561ac) | Nov 21, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [10e9d31bdb](https://linux-hardware.org/?probe=10e9d31bdb) | Nov 20, 2020 |
| ASUSTek       | PRIME Z270-A                | [d47493ecae](https://linux-hardware.org/?probe=d47493ecae) | Nov 16, 2020 |
| Gigabyte      | H81M-S2H                    | [54fd3c5678](https://linux-hardware.org/?probe=54fd3c5678) | Nov 15, 2020 |
| MSI           | B450M PRO-M2 MAX            | [f2face0a01](https://linux-hardware.org/?probe=f2face0a01) | Nov 07, 2020 |
| ASUSTek       | PRIME A320I-K               | [6bfc04099a](https://linux-hardware.org/?probe=6bfc04099a) | Nov 06, 2020 |
| eMachines     | EL1358G                     | [9aabea4465](https://linux-hardware.org/?probe=9aabea4465) | Oct 28, 2020 |
| HP            | 8433 11                     | [670028bf54](https://linux-hardware.org/?probe=670028bf54) | Oct 16, 2020 |
| MSI           | P35 Platinum                | [232a14759f](https://linux-hardware.org/?probe=232a14759f) | Oct 14, 2020 |
| MSI           | MAG B550M MORTAR            | [653a4a9f6e](https://linux-hardware.org/?probe=653a4a9f6e) | Oct 11, 2020 |
| HP            | 304Ah                       | [5143880fd9](https://linux-hardware.org/?probe=5143880fd9) | Oct 09, 2020 |
| ASUSTek       | PRIME A320M-K               | [55e4fca971](https://linux-hardware.org/?probe=55e4fca971) | Oct 08, 2020 |
| ASUSTek       | TUF B360-PLUS GAMING        | [1779589a19](https://linux-hardware.org/?probe=1779589a19) | Oct 08, 2020 |
| Gigabyte      | Z390 DESIGNARE-CF           | [f304a2629f](https://linux-hardware.org/?probe=f304a2629f) | Oct 04, 2020 |
| Acer          | WMCP78M                     | [2510b2bc49](https://linux-hardware.org/?probe=2510b2bc49) | Oct 02, 2020 |
| Intel         | DG41RQ AAE54511-204         | [651cef3c94](https://linux-hardware.org/?probe=651cef3c94) | Sep 29, 2020 |
| MSI           | FM2-A55M-E33                | [50d8cc3e2d](https://linux-hardware.org/?probe=50d8cc3e2d) | Sep 28, 2020 |
| ASUSTek       | Z170-DELUXE                 | [8eef95cd00](https://linux-hardware.org/?probe=8eef95cd00) | Sep 12, 2020 |
| MSI           | B450 TOMAHAWK MAX           | [73d7e76e09](https://linux-hardware.org/?probe=73d7e76e09) | Sep 11, 2020 |
| Dell          | 0Y958C A00                  | [253e97e06c](https://linux-hardware.org/?probe=253e97e06c) | Sep 10, 2020 |
| Gigabyte      | F2A88XN-WIFI                | [3b51467541](https://linux-hardware.org/?probe=3b51467541) | Sep 06, 2020 |
| Lenovo        | MAHOBAY NOK                 | [d95b985658](https://linux-hardware.org/?probe=d95b985658) | Sep 01, 2020 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [78ec970ee1](https://linux-hardware.org/?probe=78ec970ee1) | Aug 29, 2020 |
| ASUSTek       | STRIX Z270H GAMING          | [ce54993f5d](https://linux-hardware.org/?probe=ce54993f5d) | Aug 29, 2020 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [40f5f91c4e](https://linux-hardware.org/?probe=40f5f91c4e) | Aug 26, 2020 |
| HP            | 81B4                        | [6747078a67](https://linux-hardware.org/?probe=6747078a67) | Aug 24, 2020 |
| HP            | 81B4                        | [ff66e031e4](https://linux-hardware.org/?probe=ff66e031e4) | Aug 18, 2020 |
| ASUSTek       | SABERTOOTH Z87              | [86ff4005e2](https://linux-hardware.org/?probe=86ff4005e2) | Aug 15, 2020 |
| MSI           | B450M PRO-VDH MAX           | [ae51610784](https://linux-hardware.org/?probe=ae51610784) | Aug 09, 2020 |
| ASUSTek       | H81I-PLUS                   | [7259e07174](https://linux-hardware.org/?probe=7259e07174) | Aug 07, 2020 |
| SYS           | H310CH5-TI2                 | [fb33742784](https://linux-hardware.org/?probe=fb33742784) | Aug 06, 2020 |
| Gigabyte      | Z97-D3H-CF                  | [fd308ae7e8](https://linux-hardware.org/?probe=fd308ae7e8) | Aug 03, 2020 |
| ASUSTek       | P8H61-M LX3 R2.0            | [6cf9ba1da5](https://linux-hardware.org/?probe=6cf9ba1da5) | Jul 24, 2020 |
| ASUSTek       | P8H61-M LX3 R2.0            | [9372988884](https://linux-hardware.org/?probe=9372988884) | Jul 24, 2020 |
| Dell          | 08NPPY A00                  | [ca6080756b](https://linux-hardware.org/?probe=ca6080756b) | Jul 24, 2020 |
| Dell          | 08NPPY A00                  | [41e1632a84](https://linux-hardware.org/?probe=41e1632a84) | Jul 24, 2020 |
| HP            | 2ADC                        | [2faf91f855](https://linux-hardware.org/?probe=2faf91f855) | Jul 02, 2020 |
| MSI           | B450M PRO-VDH MAX           | [9159f538a0](https://linux-hardware.org/?probe=9159f538a0) | Jun 28, 2020 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [f7a297ae2c](https://linux-hardware.org/?probe=f7a297ae2c) | Jun 23, 2020 |
| Gigabyte      | G31M-ES2L                   | [f9f7ec4c96](https://linux-hardware.org/?probe=f9f7ec4c96) | May 27, 2020 |
| ASUSTek       | P8Z77-V LX                  | [aa53a3eba5](https://linux-hardware.org/?probe=aa53a3eba5) | May 26, 2020 |
| MSI           | B450M PRO-VDH MAX           | [0e7c8d0cdc](https://linux-hardware.org/?probe=0e7c8d0cdc) | May 25, 2020 |
| Acer          | EQ45M                       | [a682473a39](https://linux-hardware.org/?probe=a682473a39) | May 23, 2020 |
| ASUSTek       | PRIME A320M-K               | [14dfb9eb8c](https://linux-hardware.org/?probe=14dfb9eb8c) | May 22, 2020 |
| ASUSTek       | PRIME A320M-K               | [299eb96cce](https://linux-hardware.org/?probe=299eb96cce) | May 22, 2020 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [cb10b79124](https://linux-hardware.org/?probe=cb10b79124) | May 16, 2020 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [592e93d734](https://linux-hardware.org/?probe=592e93d734) | May 16, 2020 |
| MSI           | GF615M-P33 V2               | [e6c02461aa](https://linux-hardware.org/?probe=e6c02461aa) | May 14, 2020 |
| ASRock        | B450M-HDV R4.0              | [484cc8fd5a](https://linux-hardware.org/?probe=484cc8fd5a) | May 07, 2020 |
| ASRock        | B450M-HDV R4.0              | [dbbea9cdaf](https://linux-hardware.org/?probe=dbbea9cdaf) | May 07, 2020 |
| Intel         | DG33FB AAD81072-306         | [2c0b3102ba](https://linux-hardware.org/?probe=2c0b3102ba) | May 01, 2020 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [7a18707ff5](https://linux-hardware.org/?probe=7a18707ff5) | Apr 26, 2020 |
| Acer          | EQ45M                       | [03e154e2dc](https://linux-hardware.org/?probe=03e154e2dc) | Apr 21, 2020 |
| eMachines     | EL1358G                     | [0ec6f0c0df](https://linux-hardware.org/?probe=0ec6f0c0df) | Apr 20, 2020 |
| ASUSTek       | ROG STRIX B360-I GAMING     | [7fa6504e44](https://linux-hardware.org/?probe=7fa6504e44) | Apr 18, 2020 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [21eac3f5ab](https://linux-hardware.org/?probe=21eac3f5ab) | Apr 14, 2020 |
| MSI           | H110M PRO-VD                | [a69e76d844](https://linux-hardware.org/?probe=a69e76d844) | Apr 11, 2020 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [fb24b9471a](https://linux-hardware.org/?probe=fb24b9471a) | Apr 08, 2020 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [9ba07d6518](https://linux-hardware.org/?probe=9ba07d6518) | Apr 08, 2020 |
| ASUSTek       | P5K                         | [60860911b6](https://linux-hardware.org/?probe=60860911b6) | Apr 03, 2020 |
| MSI           | MPG Z390 GAMING PRO CARB... | [d69e7b9642](https://linux-hardware.org/?probe=d69e7b9642) | Apr 02, 2020 |
| ECS           | H55H-M                      | [1673d5808e](https://linux-hardware.org/?probe=1673d5808e) | Mar 31, 2020 |
| ASRock        | Z77 Extreme4                | [1ea076e57b](https://linux-hardware.org/?probe=1ea076e57b) | Mar 19, 2020 |
| MSI           | B450 GAMING PLUS MAX        | [642694d59f](https://linux-hardware.org/?probe=642694d59f) | Mar 19, 2020 |
| ASUSTek       | P5K                         | [64c435a307](https://linux-hardware.org/?probe=64c435a307) | Mar 17, 2020 |
| ASUSTek       | P5K                         | [d532983f25](https://linux-hardware.org/?probe=d532983f25) | Mar 17, 2020 |
| MSI           | B450 GAMING PLUS MAX        | [86896f4c65](https://linux-hardware.org/?probe=86896f4c65) | Mar 17, 2020 |
| ASRock        | Z77 Extreme4                | [847badc92c](https://linux-hardware.org/?probe=847badc92c) | Mar 17, 2020 |
| ASRock        | B85M Pro3                   | [765094a989](https://linux-hardware.org/?probe=765094a989) | Mar 10, 2020 |
| MSI           | Z170A PC MATE               | [201d14e45c](https://linux-hardware.org/?probe=201d14e45c) | Mar 09, 2020 |
| ASUSTek       | P8B75-M                     | [56ae5142e3](https://linux-hardware.org/?probe=56ae5142e3) | Feb 24, 2020 |
| ASUSTek       | SABERTOOTH 990FX/GEN3 R2... | [9c21c6ca8e](https://linux-hardware.org/?probe=9c21c6ca8e) | Feb 17, 2020 |
| ASUSTek       | SABERTOOTH 990FX/GEN3 R2... | [8eb7f19502](https://linux-hardware.org/?probe=8eb7f19502) | Feb 17, 2020 |
| ASUSTek       | Maximus V FORMULA           | [713f5c5aaf](https://linux-hardware.org/?probe=713f5c5aaf) | Feb 14, 2020 |
| Gigabyte      | H67M-D2-B3                  | [8b9d4bcb86](https://linux-hardware.org/?probe=8b9d4bcb86) | Feb 01, 2020 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [03eef2b7d3](https://linux-hardware.org/?probe=03eef2b7d3) | Feb 01, 2020 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [cd4d0236ad](https://linux-hardware.org/?probe=cd4d0236ad) | Jan 30, 2020 |
| MSI           | FM2-A55M-E33                | [4587ab8edd](https://linux-hardware.org/?probe=4587ab8edd) | Jan 25, 2020 |
| MSI           | FM2-A55M-E33                | [93fb1697b5](https://linux-hardware.org/?probe=93fb1697b5) | Jan 25, 2020 |
| Gigabyte      | H97-HD3                     | [80245136bd](https://linux-hardware.org/?probe=80245136bd) | Jan 18, 2020 |
| ASRock        | Z87 Extreme6                | [ffb3f65bcd](https://linux-hardware.org/?probe=ffb3f65bcd) | Jan 18, 2020 |
| Dell          | 0KWVT8 A00                  | [55b5255c24](https://linux-hardware.org/?probe=55b5255c24) | Jan 18, 2020 |
| ASRock        | N68-GS4/USB3 FX R2.0        | [1a903c9d61](https://linux-hardware.org/?probe=1a903c9d61) | Jan 14, 2020 |
| Pegatron      | IPMH61P1                    | [2a47818e18](https://linux-hardware.org/?probe=2a47818e18) | Jan 06, 2020 |
| ASRock        | H87M Pro4                   | [40dee920a9](https://linux-hardware.org/?probe=40dee920a9) | Dec 25, 2019 |
| Gigabyte      | Z390 GAMING SLI-CF          | [41795f04de](https://linux-hardware.org/?probe=41795f04de) | Dec 24, 2019 |
| MSI           | A320M PRO-VD PLUS           | [805e960aa9](https://linux-hardware.org/?probe=805e960aa9) | Dec 18, 2019 |
| ASRock        | X399 Phantom Gaming 6       | [b89b031eb9](https://linux-hardware.org/?probe=b89b031eb9) | Dec 14, 2019 |
| MSI           | B150M BAZOOKA               | [3afe42946d](https://linux-hardware.org/?probe=3afe42946d) | Dec 12, 2019 |
| Gigabyte      | H61M-S1                     | [2302b497cc](https://linux-hardware.org/?probe=2302b497cc) | Dec 11, 2019 |
| Intel         | DH67BL AAG10189-208         | [c9400c1fcb](https://linux-hardware.org/?probe=c9400c1fcb) | Dec 11, 2019 |
| Intel         | DH67BL AAG10189-208         | [18d758491c](https://linux-hardware.org/?probe=18d758491c) | Dec 11, 2019 |
| Gigabyte      | H61M-S1                     | [cfbe6b0f33](https://linux-hardware.org/?probe=cfbe6b0f33) | Dec 11, 2019 |
| Gigabyte      | H61M-S1                     | [c5b3e3f258](https://linux-hardware.org/?probe=c5b3e3f258) | Dec 11, 2019 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [a548b448e7](https://linux-hardware.org/?probe=a548b448e7) | Dec 09, 2019 |
| MSI           | PH67A-C43                   | [35ffc61791](https://linux-hardware.org/?probe=35ffc61791) | Dec 06, 2019 |
| MSI           | PH67A-C43                   | [1a5faa8a98](https://linux-hardware.org/?probe=1a5faa8a98) | Dec 05, 2019 |
| Lenovo        | ThinkCentre M55E 9632BU8    | [209a9171b1](https://linux-hardware.org/?probe=209a9171b1) | Dec 04, 2019 |
| HP            | 18EA                        | [101b838d0e](https://linux-hardware.org/?probe=101b838d0e) | Nov 10, 2019 |
| ASUSTek       | SABERTOOTH Z77              | [889648300b](https://linux-hardware.org/?probe=889648300b) | Oct 04, 2019 |
| ASUSTek       | SABERTOOTH Z77              | [28d0871f17](https://linux-hardware.org/?probe=28d0871f17) | Oct 02, 2019 |
| ASUSTek       | SABERTOOTH Z77              | [22a74597d5](https://linux-hardware.org/?probe=22a74597d5) | Oct 02, 2019 |
| ASUSTek       | SABERTOOTH Z77              | [31f72c0672](https://linux-hardware.org/?probe=31f72c0672) | Oct 02, 2019 |
| Dell          | 048DY8 A00                  | [500dc4f9f5](https://linux-hardware.org/?probe=500dc4f9f5) | Sep 11, 2019 |
| ASRock        | H97M Pro4                   | [168644ddd0](https://linux-hardware.org/?probe=168644ddd0) | Sep 04, 2019 |
| Gigabyte      | H310M S2P                   | [6fffbe0439](https://linux-hardware.org/?probe=6fffbe0439) | Sep 02, 2019 |
| MSI           | Z97A GAMING 6               | [6a9086bf86](https://linux-hardware.org/?probe=6a9086bf86) | Jul 06, 2019 |
| ASUSTek       | PRIME A320M-K               | [0f2ef33214](https://linux-hardware.org/?probe=0f2ef33214) | Jun 27, 2019 |
| Dell          | 09KPNV A00                  | [b1769092a2](https://linux-hardware.org/?probe=b1769092a2) | Jun 22, 2019 |
| Dell          | 01TKCC A01                  | [c133935d4f](https://linux-hardware.org/?probe=c133935d4f) | Jun 19, 2019 |
| ASUSTek       | STRIKER II NSE              | [13d6ead175](https://linux-hardware.org/?probe=13d6ead175) | May 22, 2019 |
| ASRock        | H97M Pro4                   | [410a594809](https://linux-hardware.org/?probe=410a594809) | May 21, 2019 |
| ASUSTek       | ROG Maximus X HERO          | [d7d3d4f56b](https://linux-hardware.org/?probe=d7d3d4f56b) | May 19, 2019 |
| MSI           | B450 TOMAHAWK               | [336d0df071](https://linux-hardware.org/?probe=336d0df071) | May 03, 2019 |
| Intel         | DG35EC AAE29266-205         | [1ddb0e459f](https://linux-hardware.org/?probe=1ddb0e459f) | Apr 26, 2019 |
| Intel         | SHARKBAY                    | [d411643b19](https://linux-hardware.org/?probe=d411643b19) | Apr 23, 2019 |
| Dell          | 01TKCC A01                  | [3cfa230457](https://linux-hardware.org/?probe=3cfa230457) | Apr 12, 2019 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Elementary/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Elementary 6.1   | 187      | 25.97%  |
| Elementary 7.1   | 138      | 19.17%  |
| Elementary 8     | 114      | 15.83%  |
| Elementary 5.1.7 | 72       | 10%     |
| Elementary 7     | 68       | 9.44%   |
| Elementary 6     | 66       | 9.17%   |
| Elementary 5.1   | 17       | 2.36%   |
| Elementary 5.0   | 17       | 2.36%   |
| Elementary 5.1.2 | 10       | 1.39%   |
| Elementary 5.1.4 | 7        | 0.97%   |
| Elementary 5.1.3 | 7        | 0.97%   |
| Elementary 0.4.1 | 7        | 0.97%   |
| Elementary 5.1.6 | 6        | 0.83%   |
| Elementary 6.0   | 2        | 0.28%   |
| Elementary 5.1.5 | 2        | 0.28%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Elementary | 684      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.11.0-43-generic | 36       | 4.55%   |
| 5.15.0-58-generic | 24       | 3.03%   |
| 6.8.0-49-generic  | 23       | 2.91%   |
| 6.2.0-33-generic  | 20       | 2.53%   |
| 5.11.0-41-generic | 19       | 2.4%    |
| 6.11.0-19-generic | 18       | 2.28%   |
| 5.11.0-40-generic | 17       | 2.15%   |
| 5.13.0-39-generic | 16       | 2.02%   |
| 5.13.0-28-generic | 16       | 2.02%   |
| 6.8.0-51-generic  | 15       | 1.9%    |
| 5.15.0-46-generic | 13       | 1.64%   |
| 6.5.0-26-generic  | 12       | 1.52%   |
| 6.8.0-40-generic  | 11       | 1.39%   |
| 5.0.0-37-generic  | 11       | 1.39%   |
| 6.5.0-35-generic  | 10       | 1.26%   |
| 5.13.0-27-generic | 10       | 1.26%   |
| 5.11.0-27-generic | 10       | 1.26%   |
| 6.14.0-29-generic | 9        | 1.14%   |
| 6.11.0-26-generic | 9        | 1.14%   |
| 5.4.0-42-generic  | 9        | 1.14%   |
| 5.19.0-32-generic | 9        | 1.14%   |
| 5.15.0-56-generic | 9        | 1.14%   |
| 5.13.0-40-generic | 9        | 1.14%   |
| 5.13.0-30-generic | 9        | 1.14%   |
| 6.2.0-36-generic  | 8        | 1.01%   |
| 5.4.0-48-generic  | 8        | 1.01%   |
| 6.5.0-41-generic  | 7        | 0.88%   |
| 6.5.0-28-generic  | 7        | 0.88%   |
| 6.11.0-29-generic | 7        | 0.88%   |
| 5.13.0-35-generic | 7        | 0.88%   |
| 5.11.0-37-generic | 7        | 0.88%   |
| 6.8.0-50-generic  | 6        | 0.76%   |
| 6.8.0-48-generic  | 6        | 0.76%   |
| 6.2.0-35-generic  | 6        | 0.76%   |
| 6.11.0-24-generic | 6        | 0.76%   |
| 5.4.0-65-generic  | 6        | 0.76%   |
| 5.4.0-58-generic  | 6        | 0.76%   |
| 5.19.0-38-generic | 6        | 0.76%   |
| 5.19.0-35-generic | 6        | 0.76%   |
| 5.13.0-37-generic | 6        | 0.76%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11.0  | 105      | 14.44%  |
| 5.13.0  | 86       | 11.83%  |
| 5.15.0  | 79       | 10.87%  |
| 6.8.0   | 73       | 10.04%  |
| 5.4.0   | 68       | 9.35%   |
| 6.5.0   | 59       | 8.12%   |
| 6.2.0   | 54       | 7.43%   |
| 6.11.0  | 53       | 7.29%   |
| 5.19.0  | 35       | 4.81%   |
| 6.14.0  | 27       | 3.71%   |
| 5.3.0   | 24       | 3.3%    |
| 4.15.0  | 24       | 3.3%    |
| 5.0.0   | 15       | 2.06%   |
| 5.8.0   | 5        | 0.69%   |
| 4.18.0  | 3        | 0.41%   |
| 4.4.0   | 2        | 0.28%   |
| 6.7.10  | 1        | 0.14%   |
| 6.4.5   | 1        | 0.14%   |
| 6.12.6  | 1        | 0.14%   |
| 6.11.5  | 1        | 0.14%   |
| 6.1.8   | 1        | 0.14%   |
| 5.2.11  | 1        | 0.14%   |
| 5.17.3  | 1        | 0.14%   |
| 5.17.0  | 1        | 0.14%   |
| 5.16.15 | 1        | 0.14%   |
| 5.15.36 | 1        | 0.14%   |
| 5.15.12 | 1        | 0.14%   |
| 5.15.1  | 1        | 0.14%   |
| 5.14.0  | 1        | 0.14%   |
| 5.0.11  | 1        | 0.14%   |
| 4.10.0  | 1        | 0.14%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11    | 105      | 14.44%  |
| 5.13    | 86       | 11.83%  |
| 5.15    | 82       | 11.28%  |
| 6.8     | 73       | 10.04%  |
| 5.4     | 68       | 9.35%   |
| 6.5     | 59       | 8.12%   |
| 6.2     | 54       | 7.43%   |
| 6.11    | 54       | 7.43%   |
| 5.19    | 35       | 4.81%   |
| 6.14    | 27       | 3.71%   |
| 5.3     | 24       | 3.3%    |
| 4.15    | 24       | 3.3%    |
| 5.0     | 16       | 2.2%    |
| 5.8     | 5        | 0.69%   |
| 4.18    | 3        | 0.41%   |
| 5.17    | 2        | 0.28%   |
| 4.4     | 2        | 0.28%   |
| 6.7     | 1        | 0.14%   |
| 6.4     | 1        | 0.14%   |
| 6.12    | 1        | 0.14%   |
| 6.1     | 1        | 0.14%   |
| 5.2     | 1        | 0.14%   |
| 5.16    | 1        | 0.14%   |
| 5.14    | 1        | 0.14%   |
| 4.10    | 1        | 0.14%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 684      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| Pantheon | 661      | 95.66%  |
| Unknown  | 26       | 3.76%   |
| GNOME    | 3        | 0.43%   |
| MATE     | 1        | 0.14%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 670      | 97.95%  |
| Wayland | 13       | 1.9%    |
| Unknown | 1        | 0.15%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 595      | 85.61%  |
| LightDM | 82       | 11.8%   |
| TDM     | 16       | 2.3%    |
| SDDM    | 1        | 0.14%   |
| GDM     | 1        | 0.14%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 266      | 38.22%  |
| de_DE   | 79       | 11.35%  |
| es_ES   | 61       | 8.76%   |
| ru_RU   | 39       | 5.6%    |
| pt_BR   | 34       | 4.89%   |
| fr_FR   | 27       | 3.88%   |
| en_GB   | 24       | 3.45%   |
| Unknown | 24       | 3.45%   |
| it_IT   | 22       | 3.16%   |
| pl_PL   | 17       | 2.44%   |
| en_CA   | 14       | 2.01%   |
| hu_HU   | 9        | 1.29%   |
| pt_PT   | 8        | 1.15%   |
| tr_TR   | 7        | 1.01%   |
| ja_JP   | 7        | 1.01%   |
| en_AU   | 7        | 1.01%   |
| sv_SE   | 5        | 0.72%   |
| nl_NL   | 4        | 0.57%   |
| es_MX   | 3        | 0.43%   |
| el_GR   | 3        | 0.43%   |
| de_CH   | 3        | 0.43%   |
| cs_CZ   | 3        | 0.43%   |
| zh_CN   | 2        | 0.29%   |
| fr_CA   | 2        | 0.29%   |
| fi_FI   | 2        | 0.29%   |
| en_IN   | 2        | 0.29%   |
| C       | 2        | 0.29%   |
| zh_TW   | 1        | 0.14%   |
| uk_UA   | 1        | 0.14%   |
| sr_RS   | 1        | 0.14%   |
| nb_NO   | 1        | 0.14%   |
| id_ID   | 1        | 0.14%   |
| hr_HR   | 1        | 0.14%   |
| gl_ES   | 1        | 0.14%   |
| fr_BE   | 1        | 0.14%   |
| es_VE   | 1        | 0.14%   |
| es_SV   | 1        | 0.14%   |
| es_PA   | 1        | 0.14%   |
| es_EC   | 1        | 0.14%   |
| en_ZA   | 1        | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 492      | 70.69%  |
| EFI  | 204      | 29.31%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 651      | 94.35%  |
| Btrfs    | 17       | 2.46%   |
| Xfs      | 7        | 1.01%   |
| Tmpfs    | 6        | 0.87%   |
| Unknown  | 6        | 0.87%   |
| Overlay  | 2        | 0.29%   |
| Reiserfs | 1        | 0.14%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 607      | 87.59%  |
| GPT     | 59       | 8.51%   |
| MBR     | 27       | 3.9%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 657      | 95.63%  |
| Yes       | 30       | 4.37%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 620      | 89.86%  |
| Yes       | 70       | 10.14%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 166      | 24.27%  |
| Gigabyte Technology | 108      | 15.79%  |
| MSI                 | 75       | 10.96%  |
| Hewlett-Packard     | 63       | 9.21%   |
| Dell                | 57       | 8.33%   |
| ASRock              | 54       | 7.89%   |
| Intel               | 25       | 3.65%   |
| Lenovo              | 24       | 3.51%   |
| Acer                | 14       | 2.05%   |
| Biostar             | 13       | 1.9%    |
| Apple               | 8        | 1.17%   |
| Unknown             | 8        | 1.17%   |
| Pegatron            | 7        | 1.02%   |
| Foxconn             | 7        | 1.02%   |
| ECS                 | 6        | 0.88%   |
| Fujitsu             | 5        | 0.73%   |
| MACHINIST           | 3        | 0.44%   |
| AZW                 | 3        | 0.44%   |
| Wibtek              | 2        | 0.29%   |
| OEM                 | 2        | 0.29%   |
| Medion              | 2        | 0.29%   |
| Inventec            | 2        | 0.29%   |
| IceWhale Technology | 2        | 0.29%   |
| Huanan              | 2        | 0.29%   |
| EVGA                | 2        | 0.29%   |
| AMI                 | 2        | 0.29%   |
| Wortmann AG         | 1        | 0.15%   |
| T-bao               | 1        | 0.15%   |
| SYS                 | 1        | 0.15%   |
| Shuttle             | 1        | 0.15%   |
| Positivo            | 1        | 0.15%   |
| Packard Bell        | 1        | 0.15%   |
| NEC Computers       | 1        | 0.15%   |
| MAXSUN              | 1        | 0.15%   |
| LORD ELECTRONICS    | 1        | 0.15%   |
| LattePanda          | 1        | 0.15%   |
| Kraftway            | 1        | 0.15%   |
| Jetway              | 1        | 0.15%   |
| HC Technology.      | 1        | 0.15%   |
| GEEKOM              | 1        | 0.15%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| ASUS All Series                   | 13       | 1.9%    |
| Unknown                           | 10       | 1.46%   |
| ASUS PRIME A320M-K                | 6        | 0.88%   |
| MSI MS-7C02                       | 4        | 0.58%   |
| MSI MS-7B84                       | 4        | 0.58%   |
| MSI MS-7721                       | 4        | 0.58%   |
| HP ProDesk 600 G1 SFF             | 4        | 0.58%   |
| Dell OptiPlex 9020                | 4        | 0.58%   |
| Dell OptiPlex 790                 | 4        | 0.58%   |
| ASUS P8H61-M LX3 R2.0             | 4        | 0.58%   |
| Intel Jasper Lake Client Platform | 3        | 0.44%   |
| Intel H61                         | 3        | 0.44%   |
| HP Compaq Elite 8300 SFF          | 3        | 0.44%   |
| Gigabyte Z390 UD                  | 3        | 0.44%   |
| Gigabyte AB350-Gaming 3           | 3        | 0.44%   |
| Dell OptiPlex 9010                | 3        | 0.44%   |
| Dell OptiPlex 7010                | 3        | 0.44%   |
| ASUS ROG STRIX B350-F GAMING      | 3        | 0.44%   |
| ASUS PRIME H310M-E R2.0           | 3        | 0.44%   |
| ASUS M5A78L-M/USB3                | 3        | 0.44%   |
| Apple MacPro5,1                   | 3        | 0.44%   |
| Wibtek H61-M HDMI2                | 2        | 0.29%   |
| Pegatron IPMH61P1                 | 2        | 0.29%   |
| MSI MS-7D77                       | 2        | 0.29%   |
| MSI MS-7C52                       | 2        | 0.29%   |
| MSI MS-7C35                       | 2        | 0.29%   |
| MSI MS-7B98                       | 2        | 0.29%   |
| MSI MS-7B86                       | 2        | 0.29%   |
| MSI MS-7B79                       | 2        | 0.29%   |
| MSI MS-7B17                       | 2        | 0.29%   |
| MSI MS-7A63                       | 2        | 0.29%   |
| MSI MS-7817                       | 2        | 0.29%   |
| Intel X79                         | 2        | 0.29%   |
| HP Z800 Workstation               | 2        | 0.29%   |
| HP Z400 Workstation               | 2        | 0.29%   |
| HP Compaq Pro 6300 MT             | 2        | 0.29%   |
| HP Compaq 8200 Elite SFF PC       | 2        | 0.29%   |
| Gigabyte X570 AORUS ELITE         | 2        | 0.29%   |
| Gigabyte H97-HD3                  | 2        | 0.29%   |
| Gigabyte H61M-S1                  | 2        | 0.29%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| ASUS PRIME            | 39       | 5.7%    |
| Dell OptiPlex         | 37       | 5.41%   |
| ASUS ROG              | 21       | 3.07%   |
| Lenovo ThinkCentre    | 20       | 2.92%   |
| HP Compaq             | 16       | 2.34%   |
| ASUS TUF              | 15       | 2.19%   |
| ASUS All              | 13       | 1.9%    |
| HP EliteDesk          | 10       | 1.46%   |
| Unknown               | 10       | 1.46%   |
| HP ProDesk            | 9        | 1.32%   |
| Dell Precision        | 9        | 1.32%   |
| Acer Aspire           | 8        | 1.17%   |
| Gigabyte Z390         | 6        | 0.88%   |
| ASUS P8H61-M          | 6        | 0.88%   |
| ASUS M5A78L-M         | 6        | 0.88%   |
| Fujitsu ESPRIMO       | 5        | 0.73%   |
| ASUS SABERTOOTH       | 5        | 0.73%   |
| ASRock B450M          | 5        | 0.73%   |
| MSI MS-7C02           | 4        | 0.58%   |
| MSI MS-7B84           | 4        | 0.58%   |
| MSI MS-7721           | 4        | 0.58%   |
| Gigabyte X570         | 4        | 0.58%   |
| Gigabyte H310M        | 4        | 0.58%   |
| Gigabyte A320M-S2H    | 4        | 0.58%   |
| Acer Veriton          | 4        | 0.58%   |
| Intel Jasper          | 3        | 0.44%   |
| Intel H61             | 3        | 0.44%   |
| HP Pavilion           | 3        | 0.44%   |
| Gigabyte B550         | 3        | 0.44%   |
| Gigabyte B450M        | 3        | 0.44%   |
| Gigabyte AB350-Gaming | 3        | 0.44%   |
| Dell Vostro           | 3        | 0.44%   |
| Dell Inspiron         | 3        | 0.44%   |
| ASUS H110M-A          | 3        | 0.44%   |
| Apple MacPro5         | 3        | 0.44%   |
| Wibtek H61-M          | 2        | 0.29%   |
| Pegatron IPMH61P1     | 2        | 0.29%   |
| MSI MS-7D77           | 2        | 0.29%   |
| MSI MS-7C52           | 2        | 0.29%   |
| MSI MS-7C35           | 2        | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 78       | 11.4%   |
| 2012 | 74       | 10.82%  |
| 2013 | 65       | 9.5%    |
| 2011 | 51       | 7.46%   |
| 2010 | 46       | 6.73%   |
| 2019 | 41       | 5.99%   |
| 2014 | 39       | 5.7%    |
| 2017 | 36       | 5.26%   |
| 2009 | 36       | 5.26%   |
| 2020 | 35       | 5.12%   |
| 2015 | 35       | 5.12%   |
| 2016 | 32       | 4.68%   |
| 2021 | 28       | 4.09%   |
| 2022 | 26       | 3.8%    |
| 2008 | 22       | 3.22%   |
| 2023 | 15       | 2.19%   |
| 2007 | 12       | 1.75%   |
| 2024 | 7        | 1.02%   |
| 2006 | 3        | 0.44%   |
| 2025 | 2        | 0.29%   |
| 2005 | 1        | 0.15%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 684      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 668      | 97.66%  |
| Enabled  | 16       | 2.34%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 684      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 167      | 24.17%  |
| 8.01-16.0   | 136      | 19.68%  |
| 4.01-8.0    | 121      | 17.51%  |
| 32.01-64.0  | 114      | 16.5%   |
| 3.01-4.0    | 83       | 12.01%  |
| 64.01-256.0 | 27       | 3.91%   |
| 24.01-32.0  | 24       | 3.47%   |
| 1.01-2.0    | 12       | 1.74%   |
| 2.01-3.0    | 7        | 1.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 244      | 31.77%  |
| 2.01-3.0   | 239      | 31.12%  |
| 4.01-8.0   | 128      | 16.67%  |
| 3.01-4.0   | 124      | 16.15%  |
| 8.01-16.0  | 20       | 2.6%    |
| 0.51-1.0   | 12       | 1.56%   |
| 32.01-64.0 | 1        | 0.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 270      | 38.19%  |
| 2      | 244      | 34.51%  |
| 3      | 98       | 13.86%  |
| 4      | 45       | 6.36%   |
| 5      | 27       | 3.82%   |
| 6      | 12       | 1.7%    |
| 7      | 6        | 0.85%   |
| 9      | 2        | 0.28%   |
| 0      | 2        | 0.28%   |
| 8      | 1        | 0.14%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 409      | 58.51%  |
| Yes       | 290      | 41.49%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 676      | 98.83%  |
| No        | 8        | 1.17%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 358      | 51.51%  |
| No        | 337      | 48.49%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 436      | 62.91%  |
| Yes       | 257      | 37.09%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 98       | 14.24%  |
| Germany     | 75       | 10.9%   |
| Brazil      | 51       | 7.41%   |
| Russia      | 40       | 5.81%   |
| Spain       | 31       | 4.51%   |
| UK          | 30       | 4.36%   |
| Canada      | 28       | 4.07%   |
| Italy       | 25       | 3.63%   |
| France      | 24       | 3.49%   |
| Poland      | 21       | 3.05%   |
| Mexico      | 18       | 2.62%   |
| Netherlands | 14       | 2.03%   |
| Argentina   | 14       | 2.03%   |
| Indonesia   | 13       | 1.89%   |
| Australia   | 12       | 1.74%   |
| India       | 11       | 1.6%    |
| Austria     | 11       | 1.6%    |
| Turkey      | 9        | 1.31%   |
| Hungary     | 9        | 1.31%   |
| Portugal    | 8        | 1.16%   |
| Japan       | 8        | 1.16%   |
| Greece      | 8        | 1.16%   |
| Switzerland | 7        | 1.02%   |
| Sweden      | 7        | 1.02%   |
| Czechia     | 6        | 0.87%   |
| Venezuela   | 5        | 0.73%   |
| Israel      | 5        | 0.73%   |
| Finland     | 5        | 0.73%   |
| Egypt       | 5        | 0.73%   |
| Colombia    | 5        | 0.73%   |
| Ukraine     | 4        | 0.58%   |
| Malaysia    | 4        | 0.58%   |
| Belgium     | 4        | 0.58%   |
| Vietnam     | 3        | 0.44%   |
| Thailand    | 3        | 0.44%   |
| Romania     | 3        | 0.44%   |
| Philippines | 3        | 0.44%   |
| Hong Kong   | 3        | 0.44%   |
| Denmark     | 3        | 0.44%   |
| China       | 3        | 0.44%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Moscow         | 12       | 1.64%   |
| Warsaw         | 8        | 1.09%   |
| Berlin         | 8        | 1.09%   |
| Vienna         | 5        | 0.68%   |
| St Petersburg  | 5        | 0.68%   |
| Sao Paulo      | 5        | 0.68%   |
| Rio de Janeiro | 5        | 0.68%   |
| Paris          | 5        | 0.68%   |
| Munich         | 5        | 0.68%   |
| Melbourne      | 5        | 0.68%   |
| Toronto        | 4        | 0.55%   |
| Nuremberg      | 4        | 0.55%   |
| Milan          | 4        | 0.55%   |
| Madrid         | 4        | 0.55%   |
| Los Angeles    | 4        | 0.55%   |
| Hamburg        | 4        | 0.55%   |
| Fortaleza      | 4        | 0.55%   |
| Athens         | 4        | 0.55%   |
| Tel Aviv       | 3        | 0.41%   |
| Sydney         | 3        | 0.41%   |
| Spokane        | 3        | 0.41%   |
| Sofia          | 3        | 0.41%   |
| Santiago       | 3        | 0.41%   |
| Petah Tikva    | 3        | 0.41%   |
| Novosibirsk    | 3        | 0.41%   |
| Montreal       | 3        | 0.41%   |
| Krakow         | 3        | 0.41%   |
| Istanbul       | 3        | 0.41%   |
| Innsbruck      | 3        | 0.41%   |
| Caslano        | 3        | 0.41%   |
| Brisbane       | 3        | 0.41%   |
| Bandung        | 3        | 0.41%   |
| Amsterdam      | 3        | 0.41%   |
| Valencia       | 2        | 0.27%   |
| Tucson         | 2        | 0.27%   |
| Teresina       | 2        | 0.27%   |
| Tangerang      | 2        | 0.27%   |
| Tampere        | 2        | 0.27%   |
| Stuttgart      | 2        | 0.27%   |
| Saskatoon      | 2        | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 205      | 304    | 16.6%   |
| Seagate                     | 196      | 290    | 15.87%  |
| Samsung Electronics         | 154      | 264    | 12.47%  |
| Kingston                    | 87       | 122    | 7.04%   |
| SanDisk                     | 66       | 77     | 5.34%   |
| Toshiba                     | 60       | 92     | 4.86%   |
| Crucial                     | 53       | 71     | 4.29%   |
| Hitachi                     | 32       | 36     | 2.59%   |
| China                       | 26       | 41     | 2.11%   |
| A-DATA Technology           | 20       | 22     | 1.62%   |
| Intel                       | 19       | 24     | 1.54%   |
| Micron/Crucial Technology   | 18       | 26     | 1.46%   |
| Unknown                     | 16       | 34     | 1.3%    |
| PNY                         | 16       | 24     | 1.3%    |
| HGST                        | 13       | 17     | 1.05%   |
| Silicon Motion              | 12       | 17     | 0.97%   |
| Micron Technology           | 12       | 13     | 0.97%   |
| MAXIO Technology (Hangzhou) | 10       | 13     | 0.81%   |
| Team                        | 9        | 12     | 0.73%   |
| Transcend                   | 8        | 9      | 0.65%   |
| Patriot                     | 8        | 9      | 0.65%   |
| OCZ                         | 8        | 15     | 0.65%   |
| Corsair                     | 8        | 9      | 0.65%   |
| Realtek Semiconductor       | 7        | 8      | 0.57%   |
| Phison                      | 7        | 8      | 0.57%   |
| Maxtor                      | 7        | 7      | 0.57%   |
| Intenso                     | 7        | 9      | 0.57%   |
| SPCC                        | 6        | 6      | 0.49%   |
| JMicron Technology          | 6        | 6      | 0.49%   |
| Unknown                     | 6        | 6      | 0.49%   |
| Netac                       | 5        | 6      | 0.4%    |
| KingFast                    | 5        | 7      | 0.4%    |
| Hewlett-Packard             | 5        | 5      | 0.4%    |
| Gigabyte Technology         | 5        | 5      | 0.4%    |
| SK hynix                    | 4        | 4      | 0.32%   |
| Plextor                     | 4        | 6      | 0.32%   |
| LITEON                      | 4        | 4      | 0.32%   |
| Kingston Technology Company | 4        | 4      | 0.32%   |
| HUSKY                       | 4        | 9      | 0.32%   |
| GOODRAM                     | 4        | 7      | 0.32%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD                       | 29       | 2.07%   |
| Seagate ST500DM002-1BD142 500GB                       | 16       | 1.14%   |
| Samsung SSD 850 EVO 250GB                             | 16       | 1.14%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 14       | 1%      |
| Samsung NVMe SSD Drive 500GB                          | 12       | 0.86%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB     | 12       | 0.86%   |
| Kingston SA400S37120G 120GB SSD                       | 12       | 0.86%   |
| Toshiba DT01ACA100 1TB                                | 11       | 0.79%   |
| Toshiba DT01ACA050 500GB                              | 11       | 0.79%   |
| Seagate ST1000DM010-2EP102 1TB                        | 11       | 0.79%   |
| Crucial CT240BX500SSD1 240GB                          | 11       | 0.79%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 512GB | 10       | 0.72%   |
| Samsung SSD 860 EVO 500GB                             | 10       | 0.72%   |
| Seagate ST1000DM003-1ER162 1TB                        | 9        | 0.64%   |
| Samsung SSD 860 EVO 1TB                               | 9        | 0.64%   |
| Kingston SV300S37A120G 120GB SSD                      | 9        | 0.64%   |
| Toshiba HDWD110 1TB                                   | 8        | 0.57%   |
| Seagate ST31000528AS 1TB                              | 8        | 0.57%   |
| Samsung SSD 840 EVO 250GB                             | 8        | 0.57%   |
| Kingston SA400S37480G 480GB SSD                       | 8        | 0.57%   |
| Seagate ST3500418AS 500GB                             | 7        | 0.5%    |
| SanDisk NVMe SSD Drive 500GB                          | 7        | 0.5%    |
| Samsung SSD 860 EVO 250GB                             | 7        | 0.5%    |
| Samsung SSD 850 EVO 500GB                             | 7        | 0.5%    |
| Samsung NVMe SSD Drive 1TB                            | 7        | 0.5%    |
| Micron/Crucial P2 NVMe PCIe SSD 2TB                   | 7        | 0.5%    |
| Crucial CT500MX500SSD1 500GB                          | 7        | 0.5%    |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 6        | 0.43%   |
| WDC WD10EZEX-60WN4A0 1TB                              | 6        | 0.43%   |
| WDC WD10EZEX-22MFCA0 1TB                              | 6        | 0.43%   |
| WDC WD10EZEX-00BN5A0 1TB                              | 6        | 0.43%   |
| Seagate ST2000DM008-2FR102 2TB                        | 6        | 0.43%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB    | 6        | 0.43%   |
| Unknown                                               | 6        | 0.43%   |
| WDC WD5000AAKX-60U6AA0 500GB                          | 5        | 0.36%   |
| WDC WD5000AAKX-00ERMA0 500GB                          | 5        | 0.36%   |
| Unknown SD/MMC 16GB                                   | 5        | 0.36%   |
| Unknown M.S./M.S.Pro/HG 16GB                          | 5        | 0.36%   |
| Unknown Compact Flash 977MB                           | 5        | 0.36%   |
| Toshiba MQ01ABD100 1TB                                | 5        | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 193      | 281    | 36.62%  |
| WDC                 | 180      | 257    | 34.16%  |
| Toshiba             | 57       | 87     | 10.82%  |
| Hitachi             | 32       | 36     | 6.07%   |
| Samsung Electronics | 31       | 35     | 5.88%   |
| HGST                | 13       | 17     | 2.47%   |
| Maxtor              | 6        | 6      | 1.14%   |
| Unknown             | 3        | 4      | 0.57%   |
| JMicron Technology  | 2        | 2      | 0.38%   |
| Hewlett-Packard     | 2        | 2      | 0.38%   |
| ASMT                | 2        | 2      | 0.38%   |
| PRO Z               | 1        | 2      | 0.19%   |
| Fujitsu             | 1        | 1      | 0.19%   |
| FC-1307             | 1        | 1      | 0.19%   |
| ExcelStor           | 1        | 1      | 0.19%   |
| Apple               | 1        | 1      | 0.19%   |
| Unknown             | 1        | 1      | 0.19%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 92       | 145    | 18.4%   |
| Kingston            | 78       | 98     | 15.6%   |
| Crucial             | 51       | 68     | 10.2%   |
| SanDisk             | 39       | 44     | 7.8%    |
| WDC                 | 27       | 38     | 5.4%    |
| China               | 25       | 40     | 5%      |
| A-DATA Technology   | 19       | 21     | 3.8%    |
| PNY                 | 16       | 24     | 3.2%    |
| Intel               | 10       | 13     | 2%      |
| Team                | 9        | 12     | 1.8%    |
| Transcend           | 8        | 9      | 1.6%    |
| Patriot             | 8        | 9      | 1.6%    |
| OCZ                 | 8        | 15     | 1.6%    |
| Intenso             | 7        | 9      | 1.4%    |
| Corsair             | 7        | 8      | 1.4%    |
| SPCC                | 6        | 6      | 1.2%    |
| Netac               | 5        | 6      | 1%      |
| Micron Technology   | 5        | 5      | 1%      |
| Plextor             | 4        | 6      | 0.8%    |
| LITEON              | 4        | 4      | 0.8%    |
| HUSKY               | 4        | 9      | 0.8%    |
| GOODRAM             | 4        | 7      | 0.8%    |
| Unknown             | 4        | 4      | 0.8%    |
| Toshiba             | 3        | 3      | 0.6%    |
| Hewlett-Packard     | 3        | 3      | 0.6%    |
| Gigabyte Technology | 3        | 3      | 0.6%    |
| Apacer              | 3        | 3      | 0.6%    |
| Verbatim            | 2        | 2      | 0.4%    |
| SK hynix            | 2        | 2      | 0.4%    |
| Seagate             | 2        | 4      | 0.4%    |
| Lexar               | 2        | 3      | 0.4%    |
| KingSpec            | 2        | 2      | 0.4%    |
| GeIL                | 2        | 2      | 0.4%    |
| AGI                 | 2        | 3      | 0.4%    |
| Zheino              | 1        | 1      | 0.2%    |
| XrayDisk            | 1        | 3      | 0.2%    |
| WDC WDS             | 1        | 1      | 0.2%    |
| WALRAM              | 1        | 1      | 0.2%    |
| tigo                | 1        | 1      | 0.2%    |
| SD                  | 1        | 1      | 0.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 417      | 736    | 39.75%  |
| SSD     | 412      | 673    | 39.28%  |
| NVMe    | 173      | 273    | 16.49%  |
| Unknown | 43       | 73     | 4.1%    |
| MMC     | 4        | 4      | 0.38%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 622      | 1413   | 73.78%  |
| NVMe | 173      | 273    | 20.52%  |
| SAS  | 44       | 69     | 5.22%   |
| MMC  | 4        | 4      | 0.47%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 496      | 877    | 59.19%  |
| 0.51-1.0   | 217      | 352    | 25.89%  |
| 1.01-2.0   | 65       | 93     | 7.76%   |
| 2.01-3.0   | 24       | 42     | 2.86%   |
| 3.01-4.0   | 21       | 24     | 2.51%   |
| 4.01-10.0  | 14       | 20     | 1.67%   |
| 10.01-20.0 | 1        | 1      | 0.12%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 245      | 34.27%  |
| 251-500        | 166      | 23.22%  |
| 501-1000       | 121      | 16.92%  |
| 1001-2000      | 64       | 8.95%   |
| 51-100         | 39       | 5.45%   |
| More than 3000 | 31       | 4.34%   |
| 21-50          | 23       | 3.22%   |
| 2001-3000      | 22       | 3.08%   |
| 1-20           | 4        | 0.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 283      | 37.14%  |
| 21-50          | 177      | 23.23%  |
| 51-100         | 88       | 11.55%  |
| 101-250        | 82       | 10.76%  |
| 251-500        | 45       | 5.91%   |
| 501-1000       | 43       | 5.64%   |
| 1001-2000      | 28       | 3.67%   |
| More than 3000 | 8        | 1.05%   |
| 2001-3000      | 8        | 1.05%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WDS120G2G0A-00JH30 120GB SSD  | 1        | 1      | 3.13%   |
| WDC WD5000AAKX-22ERMA0 500GB      | 1        | 1      | 3.13%   |
| WDC WD5000AAKX-221CA1 500GB       | 1        | 1      | 3.13%   |
| WDC WD5000AAKX-00ERMA0 500GB      | 1        | 1      | 3.13%   |
| WDC WD5000AAKS-00UU3A0 500GB      | 1        | 1      | 3.13%   |
| WDC WD3200AAJS-56B4A0 320GB       | 1        | 1      | 3.13%   |
| WDC WD3000HLFS-01G6U0 304GB       | 1        | 1      | 3.13%   |
| WDC WD2002FFSX-68PF8N0 2TB        | 1        | 1      | 3.13%   |
| WDC WD10EZEX-00KUWA0 1TB          | 1        | 1      | 3.13%   |
| WDC WD1003FZEX-00MK2A0 1TB        | 1        | 1      | 3.13%   |
| Seagate ST500DM002-1BD142 500GB   | 1        | 1      | 3.13%   |
| Seagate ST3500414CS 500GB         | 1        | 2      | 3.13%   |
| Seagate ST3500312CS 500GB         | 1        | 1      | 3.13%   |
| Seagate ST3320613AS 320GB         | 1        | 1      | 3.13%   |
| Seagate ST3250820AS 250GB         | 1        | 1      | 3.13%   |
| Seagate ST3250312AS 250GB         | 1        | 1      | 3.13%   |
| Seagate ST3160813AS 160GB         | 1        | 1      | 3.13%   |
| Seagate ST3160318AS 160GB         | 1        | 1      | 3.13%   |
| Seagate ST2000DM006-2DM164 2TB    | 1        | 1      | 3.13%   |
| SanDisk SSD PLUS 240GB            | 1        | 1      | 3.13%   |
| Samsung Electronics HD322GJ 320GB | 1        | 1      | 3.13%   |
| Samsung Electronics HD204UI 2TB   | 1        | 1      | 3.13%   |
| Samsung Electronics HD160JJ 160GB | 1        | 1      | 3.13%   |
| Samsung Electronics HD103UJ 1TB   | 1        | 1      | 3.13%   |
| OCZ VECTOR150 240GB SSD           | 1        | 2      | 3.13%   |
| Kingston SA400S37120G 120GB SSD   | 1        | 1      | 3.13%   |
| Hitachi HTS725050A7E630 500GB     | 1        | 1      | 3.13%   |
| Hitachi HTS542525K9SA00 250GB     | 1        | 1      | 3.13%   |
| Hitachi HDT721064SLA360 640GB     | 1        | 1      | 3.13%   |
| Hitachi HDS721010CLA332 1TB       | 1        | 1      | 3.13%   |
| HGST HUS724030ALA640 3TB          | 1        | 1      | 3.13%   |
| Crucial CT256M550SSD1 256GB       | 1        | 1      | 3.13%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 10       | 10     | 31.25%  |
| Seagate             | 9        | 10     | 28.13%  |
| Samsung Electronics | 4        | 4      | 12.5%   |
| Hitachi             | 4        | 4      | 12.5%   |
| SanDisk             | 1        | 1      | 3.13%   |
| OCZ                 | 1        | 2      | 3.13%   |
| Kingston            | 1        | 1      | 3.13%   |
| HGST                | 1        | 1      | 3.13%   |
| Crucial             | 1        | 1      | 3.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 9        | 9      | 33.33%  |
| Seagate             | 9        | 10     | 33.33%  |
| Samsung Electronics | 4        | 4      | 14.81%  |
| Hitachi             | 4        | 4      | 14.81%  |
| HGST                | 1        | 1      | 3.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 23       | 28     | 82.14%  |
| SSD  | 5        | 6      | 17.86%  |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 626      | 1579   | 87.31%  |
| Works    | 64       | 146    | 8.93%   |
| Malfunc  | 27       | 34     | 3.77%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 490      | 52.41%  |
| AMD                          | 174      | 18.61%  |
| Samsung Electronics          | 60       | 6.42%   |
| SanDisk                      | 32       | 3.42%   |
| ASMedia Technology           | 24       | 2.57%   |
| Micron/Crucial Technology    | 20       | 2.14%   |
| Nvidia                       | 15       | 1.6%    |
| Marvell Technology Group     | 15       | 1.6%    |
| JMicron Technology           | 15       | 1.6%    |
| Kingston Technology Company  | 14       | 1.5%    |
| Silicon Motion               | 12       | 1.28%   |
| MAXIO Technology (Hangzhou)  | 11       | 1.18%   |
| Phison Electronics           | 10       | 1.07%   |
| Realtek Semiconductor        | 8        | 0.86%   |
| Micron Technology            | 7        | 0.75%   |
| ADATA Technology             | 6        | 0.64%   |
| LSI Logic / Symbios Logic    | 4        | 0.43%   |
| Shenzhen Longsys Electronics | 3        | 0.32%   |
| VIA Technologies             | 2        | 0.21%   |
| Toshiba America Info Systems | 2        | 0.21%   |
| SK hynix                     | 2        | 0.21%   |
| Silicon Image                | 2        | 0.21%   |
| Seagate Technology           | 2        | 0.21%   |
| INNOGRIT                     | 2        | 0.21%   |
| KIOXIA                       | 1        | 0.11%   |
| Hosin Global Electronics     | 1        | 0.11%   |
| Broadcom / LSI               | 1        | 0.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 96       | 8.23%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 58       | 4.97%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 54       | 4.63%   |
| AMD 400 Series Chipset SATA Controller                                                  | 41       | 3.52%   |
| Intel SATA Controller [RAID mode]                                                       | 40       | 3.43%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 34       | 2.92%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 33       | 2.83%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 33       | 2.83%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 32       | 2.74%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 30       | 2.57%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 28       | 2.4%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 26       | 2.23%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 26       | 2.23%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 23       | 1.97%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 22       | 1.89%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 20       | 1.72%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 17       | 1.46%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 17       | 1.46%   |
| AMD 300 Series Chipset SATA Controller                                                  | 17       | 1.46%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                            | 14       | 1.2%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 13       | 1.11%   |
| AMD 500 Series Chipset SATA Controller                                                  | 13       | 1.11%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 11       | 0.94%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 11       | 0.94%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 11       | 0.94%   |
| Intel Raptor Lake SATA AHCI Controller                                                  | 11       | 0.94%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 10       | 0.86%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 10       | 0.86%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 10       | 0.86%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 9        | 0.77%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 9        | 0.77%   |
| AMD 600 Series Chipset SATA Controller                                                  | 9        | 0.77%   |
| Nvidia MCP61 SATA Controller                                                            | 8        | 0.69%   |
| JMicron JMB368 IDE controller                                                           | 8        | 0.69%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 8        | 0.69%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 8        | 0.69%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 8        | 0.69%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 7        | 0.6%    |
| Intel Volume Management Device NVMe RAID Controller                                     | 7        | 0.6%    |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                                   | 6        | 0.51%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 533      | 57.75%  |
| NVMe | 174      | 18.85%  |
| IDE  | 153      | 16.58%  |
| RAID | 57       | 6.18%   |
| SAS  | 3        | 0.33%   |
| SCSI | 3        | 0.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 496      | 72.51%  |
| AMD    | 188      | 27.49%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-2400 CPU @ 3.10GHz            | 15       | 2.19%   |
| AMD Ryzen 5 3600 6-Core Processor           | 13       | 1.9%    |
| AMD Ryzen 5 2600 Six-Core Processor         | 9        | 1.31%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 8        | 1.17%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 8        | 1.17%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 7        | 1.02%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 7        | 1.02%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 7        | 1.02%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 7        | 1.02%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 6        | 0.87%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 6        | 0.87%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 6        | 0.87%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 6        | 0.87%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 6        | 0.87%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 6        | 0.87%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 6        | 0.87%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 6        | 0.87%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 5        | 0.73%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 5        | 0.73%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 5        | 0.73%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 5        | 0.73%   |
| Intel Core i7-3770S CPU @ 3.10GHz           | 5        | 0.73%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 5        | 0.73%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 5        | 0.73%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 5        | 0.73%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 5        | 0.73%   |
| Intel Core i3 CPU 530 @ 2.93GHz             | 5        | 0.73%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 5        | 0.73%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 5        | 0.73%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 4        | 0.58%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 4        | 0.58%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 4        | 0.58%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 4        | 0.58%   |
| Intel Core i7 CPU 950 @ 3.07GHz             | 4        | 0.58%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 4        | 0.58%   |
| Intel Core i5-8500 CPU @ 3.00GHz            | 4        | 0.58%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 4        | 0.58%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 4        | 0.58%   |
| Intel Core i5-3330S CPU @ 2.70GHz           | 4        | 0.58%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 4        | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 147      | 21.43%  |
| Intel Core i7           | 103      | 15.01%  |
| Intel Core i3           | 59       | 8.6%    |
| AMD Ryzen 5             | 51       | 7.43%   |
| Intel Xeon              | 46       | 6.71%   |
| Other                   | 34       | 4.96%   |
| AMD Ryzen 7             | 28       | 4.08%   |
| Intel Celeron           | 23       | 3.35%   |
| Intel Core 2 Duo        | 22       | 3.21%   |
| AMD FX                  | 20       | 2.92%   |
| AMD Ryzen 9             | 18       | 2.62%   |
| Intel Core 2 Quad       | 15       | 2.19%   |
| Intel Pentium           | 13       | 1.9%    |
| Intel Pentium Dual-Core | 12       | 1.75%   |
| AMD Ryzen 3             | 12       | 1.75%   |
| AMD Phenom II X4        | 12       | 1.75%   |
| Intel Core i9           | 10       | 1.46%   |
| AMD A8                  | 9        | 1.31%   |
| AMD A10                 | 5        | 0.73%   |
| Intel Atom              | 4        | 0.58%   |
| AMD Athlon II X4        | 4        | 0.58%   |
| AMD Athlon II X2        | 4        | 0.58%   |
| Intel Pentium Dual      | 3        | 0.44%   |
| AMD Athlon              | 3        | 0.44%   |
| AMD A4                  | 3        | 0.44%   |
| Intel Pentium Gold      | 2        | 0.29%   |
| Intel Pentium D         | 2        | 0.29%   |
| AMD Ryzen 5 PRO         | 2        | 0.29%   |
| AMD PRO A10             | 2        | 0.29%   |
| AMD Phenom              | 2        | 0.29%   |
| AMD G                   | 2        | 0.29%   |
| AMD A6                  | 2        | 0.29%   |
| Intel Pentium Silver    | 1        | 0.15%   |
| Intel Pentium 4         | 1        | 0.15%   |
| Intel Core m3           | 1        | 0.15%   |
| Intel Core 2            | 1        | 0.15%   |
| AMD Sempron             | 1        | 0.15%   |
| AMD Ryzen Threadripper  | 1        | 0.15%   |
| AMD PRO A8              | 1        | 0.15%   |
| AMD Phenom II X6        | 1        | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 309      | 44.91%  |
| 2      | 151      | 21.95%  |
| 6      | 95       | 13.81%  |
| 8      | 68       | 9.88%   |
| 12     | 23       | 3.34%   |
| 1      | 12       | 1.74%   |
| 16     | 9        | 1.31%   |
| 3      | 9        | 1.31%   |
| 10     | 7        | 1.02%   |
| 24     | 1        | 0.15%   |
| 20     | 1        | 0.15%   |
| 18     | 1        | 0.15%   |
| 14     | 1        | 0.15%   |
| 5      | 1        | 0.15%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 674      | 98.54%  |
| 2      | 10       | 1.46%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 376      | 54.73%  |
| 1      | 311      | 45.27%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 680      | 99.27%  |
| Unknown        | 5        | 0.73%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 329      | 46.93%  |
| 0x206a7    | 44       | 6.28%   |
| 0x306c3    | 43       | 6.13%   |
| 0x306a9    | 30       | 4.28%   |
| 0x08701021 | 18       | 2.57%   |
| 0x1067a    | 14       | 2%      |
| 0x906ea    | 13       | 1.85%   |
| 0x906e9    | 12       | 1.71%   |
| 0x506e3    | 11       | 1.57%   |
| 0x0800820d | 10       | 1.43%   |
| 0x906ed    | 9        | 1.28%   |
| 0x08108109 | 9        | 1.28%   |
| 0x906eb    | 8        | 1.14%   |
| 0x06000852 | 8        | 1.14%   |
| 0x010000c8 | 8        | 1.14%   |
| 0x6fb      | 7        | 1%      |
| 0x106e5    | 6        | 0.86%   |
| 0x206d7    | 5        | 0.71%   |
| 0x20652    | 5        | 0.71%   |
| 0x10676    | 5        | 0.71%   |
| 0x0a201016 | 5        | 0.71%   |
| 0x08701013 | 5        | 0.71%   |
| 0x06003106 | 5        | 0.71%   |
| 0xa0671    | 4        | 0.57%   |
| 0xa0655    | 4        | 0.57%   |
| 0x106a5    | 4        | 0.57%   |
| 0x08001138 | 4        | 0.57%   |
| 0x06001119 | 4        | 0.57%   |
| 0x0600063e | 4        | 0.57%   |
| 0x010000db | 4        | 0.57%   |
| 0xa0653    | 3        | 0.43%   |
| 0x306e4    | 3        | 0.43%   |
| 0x206c2    | 3        | 0.43%   |
| 0x20655    | 3        | 0.43%   |
| 0x0810100b | 3        | 0.43%   |
| 0x0600611a | 3        | 0.43%   |
| 0x906ec    | 2        | 0.29%   |
| 0x906c0    | 2        | 0.29%   |
| 0x6fd      | 2        | 0.29%   |
| 0x406c4    | 2        | 0.29%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 83       | 12.12%  |
| KabyLake         | 80       | 11.68%  |
| SandyBridge      | 70       | 10.22%  |
| IvyBridge        | 66       | 9.64%   |
| Unknown          | 40       | 5.84%   |
| Penryn           | 36       | 5.26%   |
| Skylake          | 33       | 4.82%   |
| Zen 2            | 32       | 4.67%   |
| Zen+             | 28       | 4.09%   |
| K10              | 25       | 3.65%   |
| Zen 3            | 23       | 3.36%   |
| Zen              | 21       | 3.07%   |
| Piledriver       | 21       | 3.07%   |
| Core             | 21       | 3.07%   |
| Nehalem          | 20       | 2.92%   |
| Westmere         | 16       | 2.34%   |
| CometLake        | 16       | 2.34%   |
| Steamroller      | 9        | 1.31%   |
| Excavator        | 8        | 1.17%   |
| Bulldozer        | 6        | 0.88%   |
| Icelake          | 5        | 0.73%   |
| Silvermont       | 4        | 0.58%   |
| Goldmont plus    | 4        | 0.58%   |
| NetBurst         | 3        | 0.44%   |
| Tremont          | 2        | 0.29%   |
| Goldmont         | 2        | 0.29%   |
| Broadwell        | 2        | 0.29%   |
| Bobcat           | 2        | 0.29%   |
| Alderlake Hybrid | 2        | 0.29%   |
| TigerLake        | 1        | 0.15%   |
| Puma             | 1        | 0.15%   |
| K8 Hammer        | 1        | 0.15%   |
| K10 Llano        | 1        | 0.15%   |
| Bonnell          | 1        | 0.15%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Nvidia           | 276      | 37%     |
| Intel            | 247      | 33.11%  |
| AMD              | 221      | 29.62%  |
| Conexant Systems | 1        | 0.13%   |
| ATI Technologies | 1        | 0.13%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 37       | 4.8%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 36       | 4.67%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 34       | 4.41%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 25       | 3.24%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 17       | 2.2%    |
| Intel Skylake-S GT2 [HD Graphics 530]                                       | 17       | 2.2%    |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 15       | 1.95%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 13       | 1.69%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 13       | 1.69%   |
| Nvidia GK208B [GeForce GT 710]                                              | 11       | 1.43%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 10       | 1.3%    |
| Nvidia GP107 [GeForce GTX 1050]                                             | 9        | 1.17%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 9        | 1.17%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 9        | 1.17%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 9        | 1.17%   |
| Intel Kaby Lake-S GT2 [HD Graphics 630]                                     | 9        | 1.17%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 9        | 1.17%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 9        | 1.17%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 9        | 1.17%   |
| Nvidia GT218 [GeForce 210]                                                  | 8        | 1.04%   |
| Nvidia GK208B [GeForce GT 730]                                              | 8        | 1.04%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 8        | 1.04%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 8        | 1.04%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 8        | 1.04%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 7        | 0.91%   |
| Nvidia GF119 [GeForce GT 610]                                               | 7        | 0.91%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 7        | 0.91%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 7        | 0.91%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 6        | 0.78%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 6        | 0.78%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 6        | 0.78%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 6        | 0.78%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 6        | 0.78%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 6        | 0.78%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 6        | 0.78%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 6        | 0.78%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 5        | 0.65%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 5        | 0.65%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 5        | 0.65%   |
| Nvidia GF108 [GeForce GT 730]                                               | 5        | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| 1 x Nvidia                     | 249      | 36.03%  |
| 1 x Intel                      | 203      | 29.38%  |
| 1 x AMD                        | 195      | 28.22%  |
| Intel + Nvidia                 | 13       | 1.88%   |
| 2 x AMD                        | 10       | 1.45%   |
| AMD + Nvidia                   | 9        | 1.3%    |
| Intel + AMD                    | 5        | 0.72%   |
| 2 x Nvidia                     | 4        | 0.58%   |
| Intel + 2 x AMD                | 2        | 0.29%   |
| 2 x AMD + 1 x Conexant Systems | 1        | 0.14%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 542      | 78.55%  |
| Proprietary | 126      | 18.26%  |
| Unknown     | 22       | 3.19%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 382      | 54.42%  |
| 1.01-2.0   | 84       | 11.97%  |
| 0.51-1.0   | 59       | 8.4%    |
| 3.01-4.0   | 53       | 7.55%   |
| 7.01-8.0   | 47       | 6.7%    |
| 0.01-0.5   | 33       | 4.7%    |
| 5.01-6.0   | 20       | 2.85%   |
| 8.01-16.0  | 16       | 2.28%   |
| 2.01-3.0   | 7        | 1%      |
| 16.01-24.0 | 1        | 0.14%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 111      | 15.61%  |
| Goldstar             | 81       | 11.39%  |
| Dell                 | 64       | 9%      |
| Hewlett-Packard      | 56       | 7.88%   |
| Acer                 | 52       | 7.31%   |
| AOC                  | 47       | 6.61%   |
| Philips              | 32       | 4.5%    |
| BenQ                 | 28       | 3.94%   |
| Ancor Communications | 24       | 3.38%   |
| LG Electronics       | 17       | 2.39%   |
| ViewSonic            | 15       | 2.11%   |
| Lenovo               | 15       | 2.11%   |
| Vizio                | 9        | 1.27%   |
| Unknown              | 9        | 1.27%   |
| NEC Computers        | 8        | 1.13%   |
| MSI                  | 8        | 1.13%   |
| Iiyama               | 8        | 1.13%   |
| ASUSTek Computer     | 7        | 0.98%   |
| Sony                 | 6        | 0.84%   |
| Fujitsu Siemens      | 6        | 0.84%   |
| Sharp                | 5        | 0.7%    |
| Sceptre Tech         | 4        | 0.56%   |
| HKC                  | 4        | 0.56%   |
| Eizo                 | 4        | 0.56%   |
| Denver               | 4        | 0.56%   |
| ___                  | 3        | 0.42%   |
| SAC                  | 3        | 0.42%   |
| Panasonic            | 3        | 0.42%   |
| ITE                  | 3        | 0.42%   |
| HPN                  | 3        | 0.42%   |
| HannStar             | 3        | 0.42%   |
| AUS                  | 3        | 0.42%   |
| Apple                | 3        | 0.42%   |
| Unknown              | 3        | 0.42%   |
| Vestel               | 2        | 0.28%   |
| Unknown (XXX)        | 2        | 0.28%   |
| Onkyo                | 2        | 0.28%   |
| Mi                   | 2        | 0.28%   |
| Hitachi              | 2        | 0.28%   |
| Grundig              | 2        | 0.28%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                      | 6        | 0.8%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 5        | 0.66%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 4        | 0.53%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 4        | 0.53%   |
| Goldstar 20EN33 GSM4EE1 1600x900 443x249mm 20.0-inch                  | 4        | 0.53%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch  | 3        | 0.4%    |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch     | 3        | 0.4%    |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                   | 3        | 0.4%    |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch          | 3        | 0.4%    |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 3        | 0.4%    |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                      | 3        | 0.4%    |
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                       | 3        | 0.4%    |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 3        | 0.4%    |
| Unknown                                                               | 3        | 0.4%    |
| Vizio E280i-B1 VIZ1002 1360x768 607x345mm 27.5-inch                   | 2        | 0.27%   |
| Vizio E220VA VIZ0070 1920x1080 476x268mm 21.5-inch                    | 2        | 0.27%   |
| ViewSonic VA2719 Series VSCC132 1920x1080 598x336mm 27.0-inch         | 2        | 0.27%   |
| ViewSonic VA1931 Series VSCAC25 1366x768 410x230mm 18.5-inch          | 2        | 0.27%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 2        | 0.27%   |
| Sharp HDMI SHP1048 1920x1080 890x500mm 40.2-inch                      | 2        | 0.27%   |
| Samsung Electronics SyncMaster SAM0423 1920x1080                      | 2        | 0.27%   |
| Samsung Electronics SA300/SA350 SAM078B 1600x900 443x249mm 20.0-inch  | 2        | 0.27%   |
| Samsung Electronics S24E390 SAM0C1A 1920x1080 521x293mm 23.5-inch     | 2        | 0.27%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch     | 2        | 0.27%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 580x320mm 26.1-inch  | 2        | 0.27%   |
| Samsung Electronics LCD Monitor C32F391 1920x1080                     | 2        | 0.27%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch     | 2        | 0.27%   |
| Philips PHL 241V8 PHLC212 1920x1080 527x296mm 23.8-inch               | 2        | 0.27%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 2        | 0.27%   |
| Philips LCD Monitor PHL 276E8V 3840x2160                              | 2        | 0.27%   |
| MSI G27C7 MSI3CC6 1920x1080 597x336mm 27.0-inch                       | 2        | 0.27%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                       | 2        | 0.27%   |
| Lenovo LT2252p Wide LEN0A0C 1680x1050 474x296mm 22.0-inch             | 2        | 0.27%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1080 518x324mm 24.1-inch            | 2        | 0.27%   |
| ITE DP2VGA V226 ITE6516 1920x1080 600x340mm 27.2-inch                 | 2        | 0.27%   |
| HKC 22N1 HKCB215 1920x1080 476x268mm 21.5-inch                        | 2        | 0.27%   |
| Hewlett-Packard w2207 HWP26A9 1680x1050 473x296mm 22.0-inch           | 2        | 0.27%   |
| Hewlett-Packard V194 HWP3346 1366x768 410x230mm 18.5-inch             | 2        | 0.27%   |
| Hewlett-Packard TouchSmart HWP4211 1920x1080 509x286mm 23.0-inch      | 2        | 0.27%   |
| Hewlett-Packard 27fw HPN354C 1920x1080 598x336mm 27.0-inch            | 2        | 0.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 325      | 46.56%  |
| 3840x2160 (4K)     | 65       | 9.31%   |
| 2560x1440 (QHD)    | 50       | 7.16%   |
| 1680x1050 (WSXGA+) | 43       | 6.16%   |
| 1366x768 (WXGA)    | 37       | 5.3%    |
| 1280x1024 (SXGA)   | 32       | 4.58%   |
| 1600x900 (HD+)     | 26       | 3.72%   |
| Unknown            | 16       | 2.29%   |
| 1440x900 (WXGA+)   | 15       | 2.15%   |
| 3440x1440          | 13       | 1.86%   |
| 2560x1080          | 13       | 1.86%   |
| 1920x1200 (WUXGA)  | 13       | 1.86%   |
| 1360x768           | 11       | 1.58%   |
| 3840x1080          | 9        | 1.29%   |
| 5120x1440          | 3        | 0.43%   |
| 2560x1600          | 3        | 0.43%   |
| 1600x1200          | 3        | 0.43%   |
| 3840x1200          | 2        | 0.29%   |
| 2288x1287          | 2        | 0.29%   |
| 2048x1152          | 2        | 0.29%   |
| 1920x540           | 2        | 0.29%   |
| 1280x720 (HD)      | 2        | 0.29%   |
| 7680x2160          | 1        | 0.14%   |
| 7680x1600          | 1        | 0.14%   |
| 5760x2160          | 1        | 0.14%   |
| 5760x1080          | 1        | 0.14%   |
| 4480x1440          | 1        | 0.14%   |
| 3968x1280          | 1        | 0.14%   |
| 3840x1600          | 1        | 0.14%   |
| 3600x1080          | 1        | 0.14%   |
| 3280x1080          | 1        | 0.14%   |
| 2048x1536          | 1        | 0.14%   |
| 1024x768 (XGA)     | 1        | 0.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 93       | 13.14%  |
| Unknown | 89       | 12.57%  |
| 24      | 83       | 11.72%  |
| 23      | 74       | 10.45%  |
| 21      | 62       | 8.76%   |
| 31      | 38       | 5.37%   |
| 22      | 34       | 4.8%    |
| 19      | 32       | 4.52%   |
| 18      | 29       | 4.1%    |
| 20      | 22       | 3.11%   |
| 17      | 20       | 2.82%   |
| 34      | 17       | 2.4%    |
| 32      | 13       | 1.84%   |
| 54      | 11       | 1.55%   |
| 84      | 8        | 1.13%   |
| 72      | 7        | 0.99%   |
| 40      | 7        | 0.99%   |
| 26      | 7        | 0.99%   |
| 15      | 7        | 0.99%   |
| 36      | 6        | 0.85%   |
| 49      | 4        | 0.56%   |
| 42      | 4        | 0.56%   |
| 29      | 4        | 0.56%   |
| 65      | 3        | 0.42%   |
| 63      | 3        | 0.42%   |
| 48      | 3        | 0.42%   |
| 28      | 3        | 0.42%   |
| 25      | 3        | 0.42%   |
| 64      | 2        | 0.28%   |
| 60      | 2        | 0.28%   |
| 57      | 2        | 0.28%   |
| 55      | 2        | 0.28%   |
| 43      | 2        | 0.28%   |
| 39      | 2        | 0.28%   |
| 38      | 2        | 0.28%   |
| 33      | 2        | 0.28%   |
| 142     | 1        | 0.14%   |
| 74      | 1        | 0.14%   |
| 46      | 1        | 0.14%   |
| 37      | 1        | 0.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 239      | 34.74%  |
| 401-500        | 164      | 23.84%  |
| Unknown        | 89       | 12.94%  |
| 601-700        | 51       | 7.41%   |
| 701-800        | 37       | 5.38%   |
| 1001-1500      | 33       | 4.8%    |
| 301-350        | 25       | 3.63%   |
| 1501-2000      | 16       | 2.33%   |
| 351-400        | 14       | 2.03%   |
| 801-900        | 12       | 1.74%   |
| 901-1000       | 6        | 0.87%   |
| More than 2000 | 1        | 0.15%   |
| 201-300        | 1        | 0.15%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 431      | 66%     |
| Unknown | 81       | 12.4%   |
| 16/10   | 74       | 11.33%  |
| 5/4     | 28       | 4.29%   |
| 21/9    | 22       | 3.37%   |
| 4/3     | 5        | 0.77%   |
| 32/9    | 4        | 0.61%   |
| 3/2     | 4        | 0.61%   |
| 6/5     | 2        | 0.31%   |
| 3.20    | 1        | 0.15%   |
| 1.00    | 1        | 0.15%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 205      | 29.37%  |
| 301-350        | 96       | 13.75%  |
| Unknown        | 89       | 12.75%  |
| 351-500        | 75       | 10.74%  |
| 151-200        | 70       | 10.03%  |
| More than 1000 | 44       | 6.3%    |
| 141-150        | 44       | 6.3%    |
| 251-300        | 36       | 5.16%   |
| 501-1000       | 29       | 4.15%   |
| 101-110        | 6        | 0.86%   |
| 131-140        | 2        | 0.29%   |
| 111-120        | 1        | 0.14%   |
| 91-100         | 1        | 0.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 392      | 59.13%  |
| 101-120 | 110      | 16.59%  |
| Unknown | 89       | 13.42%  |
| 1-50    | 43       | 6.49%   |
| 121-160 | 24       | 3.62%   |
| 161-240 | 5        | 0.75%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 569      | 81.75%  |
| 2     | 100      | 14.37%  |
| 0     | 15       | 2.16%   |
| 3     | 12       | 1.72%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 448      | 43.84%  |
| Intel                             | 271      | 26.52%  |
| Qualcomm Atheros                  | 45       | 4.4%    |
| Broadcom                          | 42       | 4.11%   |
| TP-Link                           | 41       | 4.01%   |
| Ralink Technology                 | 28       | 2.74%   |
| Samsung Electronics               | 14       | 1.37%   |
| MediaTek                          | 13       | 1.27%   |
| Nvidia                            | 12       | 1.17%   |
| Xiaomi                            | 10       | 0.98%   |
| Ralink                            | 9        | 0.88%   |
| Marvell Technology Group          | 9        | 0.88%   |
| Broadcom Limited                  | 7        | 0.68%   |
| Qualcomm Atheros Communications   | 6        | 0.59%   |
| D-Link System                     | 6        | 0.59%   |
| NetGear                           | 5        | 0.49%   |
| Microsoft                         | 5        | 0.49%   |
| Linksys                           | 4        | 0.39%   |
| Huawei Technologies               | 3        | 0.29%   |
| ASUSTek Computer                  | 3        | 0.29%   |
| ASIX Electronics                  | 3        | 0.29%   |
| Aquantia                          | 3        | 0.29%   |
| Qualcomm                          | 2        | 0.2%    |
| OPPO Electronics                  | 2        | 0.2%    |
| Mercucys                          | 2        | 0.2%    |
| Edimax Technology                 | 2        | 0.2%    |
| D-Link                            | 2        | 0.2%    |
| BUFFALO                           | 2        | 0.2%    |
| Belkin Components                 | 2        | 0.2%    |
| ZyXEL Communications              | 1        | 0.1%    |
| vivo                              | 1        | 0.1%    |
| VIA Technologies                  | 1        | 0.1%    |
| TRENDnet                          | 1        | 0.1%    |
| Sundance Technology Inc / IC Plus | 1        | 0.1%    |
| Realtek                           | 1        | 0.1%    |
| Qualcomm Technologies             | 1        | 0.1%    |
| Oculus VR                         | 1        | 0.1%    |
| Motorola PCS                      | 1        | 0.1%    |
| LG Electronics                    | 1        | 0.1%    |
| Input Club                        | 1        | 0.1%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 340      | 29.29%  |
| Realtek RTL8125 2.5GbE Controller                                      | 37       | 3.19%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 35       | 3.01%   |
| Intel I211 Gigabit Network Connection                                  | 28       | 2.41%   |
| Intel Ethernet Connection (2) I219-V                                   | 25       | 2.15%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 21       | 1.81%   |
| Intel Wi-Fi 6 AX200                                                    | 20       | 1.72%   |
| Intel Ethernet Connection (7) I219-V                                   | 20       | 1.72%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 18       | 1.55%   |
| Realtek 802.11ac NIC                                                   | 17       | 1.46%   |
| Ralink MT7601U Wireless Adapter                                        | 17       | 1.46%   |
| Intel Ethernet Connection I217-LM                                      | 17       | 1.46%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 16       | 1.38%   |
| Intel Ethernet Controller I225-V                                       | 15       | 1.29%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 13       | 1.12%   |
| Intel 82579V Gigabit Network Connection                                | 13       | 1.12%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 12       | 1.03%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 10       | 0.86%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 9        | 0.78%   |
| Intel 82574L Gigabit Network Connection                                | 9        | 0.78%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 9        | 0.78%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 8        | 0.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 8        | 0.69%   |
| Intel Ethernet Connection I217-V                                       | 8        | 0.69%   |
| Nvidia MCP61 Ethernet                                                  | 7        | 0.6%    |
| Intel Cannon Lake PCH CNVi WiFi                                        | 7        | 0.6%    |
| Intel 82567LM-3 Gigabit Network Connection                             | 7        | 0.6%    |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                    | 6        | 0.52%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 6        | 0.52%   |
| TP-Link 802.11ac NIC                                                   | 6        | 0.52%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 6        | 0.52%   |
| Qualcomm Atheros AR9271 802.11n                                        | 6        | 0.52%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 6        | 0.52%   |
| Intel Wireless 7265                                                    | 6        | 0.52%   |
| Intel Wireless 3165                                                    | 6        | 0.52%   |
| Intel Ethernet Connection (7) I219-LM                                  | 6        | 0.52%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 5        | 0.43%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 5        | 0.43%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 5        | 0.43%   |
| Intel Wireless 7260                                                    | 5        | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 111      | 28.68%  |
| Intel                                 | 89       | 23%     |
| TP-Link                               | 40       | 10.34%  |
| Ralink Technology                     | 28       | 7.24%   |
| Broadcom                              | 23       | 5.94%   |
| Qualcomm Atheros                      | 21       | 5.43%   |
| MediaTek                              | 10       | 2.58%   |
| Ralink                                | 9        | 2.33%   |
| Qualcomm Atheros Communications       | 6        | 1.55%   |
| Broadcom Limited                      | 6        | 1.55%   |
| NetGear                               | 5        | 1.29%   |
| Microsoft                             | 5        | 1.29%   |
| D-Link System                         | 5        | 1.29%   |
| Linksys                               | 4        | 1.03%   |
| Marvell Technology Group              | 3        | 0.78%   |
| ASUSTek Computer                      | 3        | 0.78%   |
| Mercucys                              | 2        | 0.52%   |
| Edimax Technology                     | 2        | 0.52%   |
| D-Link                                | 2        | 0.52%   |
| BUFFALO                               | 2        | 0.52%   |
| Belkin Components                     | 2        | 0.52%   |
| ZyXEL Communications                  | 1        | 0.26%   |
| TRENDnet                              | 1        | 0.26%   |
| Realtek                               | 1        | 0.26%   |
| LG Electronics                        | 1        | 0.26%   |
| AVM                                   | 1        | 0.26%   |
| AirTies Wireless Networks             | 1        | 0.26%   |
| Accton Technology                     | 1        | 0.26%   |
| AboCom Systems                        | 1        | 0.26%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.26%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                           | 20       | 5.08%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 18       | 4.57%   |
| Realtek 802.11ac NIC                                          | 17       | 4.31%   |
| Ralink MT7601U Wireless Adapter                               | 17       | 4.31%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 16       | 4.06%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]     | 13       | 3.3%    |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 12       | 3.05%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter         | 10       | 2.54%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter  | 9        | 2.28%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 8        | 2.03%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 7        | 1.78%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                           | 6        | 1.52%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]    | 6        | 1.52%   |
| TP-Link 802.11ac NIC                                          | 6        | 1.52%   |
| Qualcomm Atheros AR9271 802.11n                               | 6        | 1.52%   |
| Intel Wireless 7265                                           | 6        | 1.52%   |
| Intel Wireless 3165                                           | 6        | 1.52%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                   | 5        | 1.27%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 5        | 1.27%   |
| Intel Wireless 7260                                           | 5        | 1.27%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]       | 5        | 1.27%   |
| Broadcom BCM43228 802.11a/b/g/n                               | 5        | 1.27%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                    | 4        | 1.02%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                    | 4        | 1.02%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 4        | 1.02%   |
| Intel Comet Lake PCH CNVi WiFi                                | 4        | 1.02%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter  | 4        | 1.02%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                  | 3        | 0.76%   |
| TP-Link Archer T4U ver.3                                      | 3        | 0.76%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                     | 3        | 0.76%   |
| TP-Link 802.11ac WLAN Adapter                                 | 3        | 0.76%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter      | 3        | 0.76%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter      | 3        | 0.76%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter               | 3        | 0.76%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                       | 3        | 0.76%   |
| Realtek RTL8187 Wireless Adapter                              | 3        | 0.76%   |
| Ralink RT2870/RT3070 Wireless Adapter                         | 3        | 0.76%   |
| Microsoft Xbox 360 Wireless Adapter                           | 3        | 0.76%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 3        | 0.76%   |
| Intel Wireless 8260                                           | 3        | 0.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 406      | 54.42%  |
| Intel                             | 225      | 30.16%  |
| Qualcomm Atheros                  | 26       | 3.49%   |
| Broadcom                          | 20       | 2.68%   |
| Samsung Electronics               | 14       | 1.88%   |
| Nvidia                            | 12       | 1.61%   |
| Xiaomi                            | 10       | 1.34%   |
| Marvell Technology Group          | 6        | 0.8%    |
| MediaTek                          | 3        | 0.4%    |
| Huawei Technologies               | 3        | 0.4%    |
| ASIX Electronics                  | 3        | 0.4%    |
| Aquantia                          | 3        | 0.4%    |
| Qualcomm                          | 2        | 0.27%   |
| OPPO Electronics                  | 2        | 0.27%   |
| vivo                              | 1        | 0.13%   |
| VIA Technologies                  | 1        | 0.13%   |
| TP-Link                           | 1        | 0.13%   |
| Sundance Technology Inc / IC Plus | 1        | 0.13%   |
| Qualcomm Technologies             | 1        | 0.13%   |
| Motorola PCS                      | 1        | 0.13%   |
| ICS Advent                        | 1        | 0.13%   |
| Google                            | 1        | 0.13%   |
| D-Link System                     | 1        | 0.13%   |
| Broadcom Limited                  | 1        | 0.13%   |
| Unknown                           | 1        | 0.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 340      | 44.56%  |
| Realtek RTL8125 2.5GbE Controller                                      | 37       | 4.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 35       | 4.59%   |
| Intel I211 Gigabit Network Connection                                  | 28       | 3.67%   |
| Intel Ethernet Connection (2) I219-V                                   | 25       | 3.28%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 21       | 2.75%   |
| Intel Ethernet Connection (7) I219-V                                   | 20       | 2.62%   |
| Intel Ethernet Connection I217-LM                                      | 17       | 2.23%   |
| Intel Ethernet Controller I225-V                                       | 15       | 1.97%   |
| Intel 82579V Gigabit Network Connection                                | 13       | 1.7%    |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 9        | 1.18%   |
| Intel 82574L Gigabit Network Connection                                | 9        | 1.18%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 8        | 1.05%   |
| Intel Ethernet Connection I217-V                                       | 8        | 1.05%   |
| Nvidia MCP61 Ethernet                                                  | 7        | 0.92%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 7        | 0.92%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 6        | 0.79%   |
| Intel Ethernet Connection (7) I219-LM                                  | 6        | 0.79%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 5        | 0.66%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 5        | 0.66%   |
| Intel Ethernet Connection (2) I219-LM                                  | 5        | 0.66%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 5        | 0.66%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 4        | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 4        | 0.52%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 4        | 0.52%   |
| Intel Ethernet Connection (2) I218-V                                   | 4        | 0.52%   |
| Intel 82578DM Gigabit Network Connection                               | 4        | 0.52%   |
| Intel 82578DC Gigabit Network Connection                               | 4        | 0.52%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                       | 4        | 0.52%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 3        | 0.39%   |
| Nvidia MCP77 Ethernet                                                  | 3        | 0.39%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                | 3        | 0.39%   |
| Intel Ethernet Connection (5) I219-LM                                  | 3        | 0.39%   |
| Intel Ethernet Connection (14) I219-V                                  | 3        | 0.39%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 3        | 0.39%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)                 | 3        | 0.39%   |
| Huawei FOA-LX9                                                         | 3        | 0.39%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 2        | 0.26%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 2        | 0.26%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 2        | 0.26%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 677      | 65.03%  |
| WiFi     | 360      | 34.58%  |
| Modem    | 3        | 0.29%   |
| Unknown  | 1        | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 498      | 70.24%  |
| WiFi     | 211      | 29.76%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 446      | 64.83%  |
| 2     | 206      | 29.94%  |
| 3     | 27       | 3.92%   |
| 0     | 7        | 1.02%   |
| 4     | 2        | 0.29%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 499      | 71.7%   |
| Yes  | 197      | 28.3%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 89       | 33.33%  |
| Cambridge Silicon Radio         | 69       | 25.84%  |
| Realtek Semiconductor           | 32       | 11.99%  |
| Broadcom                        | 14       | 5.24%   |
| ASUSTek Computer                | 13       | 4.87%   |
| Apple                           | 10       | 3.75%   |
| MediaTek                        | 7        | 2.62%   |
| IMC Networks                    | 7        | 2.62%   |
| Unknown                         | 6        | 2.25%   |
| TP-Link                         | 5        | 1.87%   |
| Qualcomm Atheros Communications | 4        | 1.5%    |
| Foxconn / Hon Hai               | 3        | 1.12%   |
| Belkin Components               | 2        | 0.75%   |
| Actions                         | 2        | 0.75%   |
| Ralink                          | 1        | 0.37%   |
| Qcom                            | 1        | 0.37%   |
| Edimax Technology               | 1        | 0.37%   |
| 3Com                            | 1        | 0.37%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 69       | 25.84%  |
| Intel Bluetooth wireless interface                  | 25       | 9.36%   |
| Realtek Bluetooth Radio                             | 24       | 8.99%   |
| Intel AX200 Bluetooth                               | 19       | 7.12%   |
| Intel AX210 Bluetooth                               | 14       | 5.24%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 10       | 3.75%   |
| Intel AX201 Bluetooth                               | 9        | 3.37%   |
| MediaTek Wireless_Device                            | 7        | 2.62%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 7        | 2.62%   |
| Unknown                                             | 6        | 2.25%   |
| TP-Link TP-T@- UB500 Adapter                        | 5        | 1.87%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4        | 1.5%    |
| Intel Wireless-AC 3168 Bluetooth                    | 4        | 1.5%    |
| Intel Bluetooth Device                              | 4        | 1.5%    |
| IMC Networks Bluetooth Radio                        | 4        | 1.5%    |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 4        | 1.5%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 4        | 1.5%    |
| Realtek  Bluetooth 4.2 Adapter                      | 3        | 1.12%   |
| Realtek Bluetooth 5.3 Radio                         | 3        | 1.12%   |
| Broadcom HP Portable Bumble Bee                     | 3        | 1.12%   |
| Realtek Bluetooth 5.4 Radio                         | 2        | 0.75%   |
| Qualcomm Atheros  Bluetooth Device                  | 2        | 0.75%   |
| IMC Networks BCM20702A0                             | 2        | 0.75%   |
| Foxconn / Hon Hai Wireless_Device                   | 2        | 0.75%   |
| Broadcom Bluetooth 3.0 USB Dongle                   | 2        | 0.75%   |
| Belkin Components Bluetooth Mini Dongle             | 2        | 0.75%   |
| ASUS Bluetooth Radio                                | 2        | 0.75%   |
| ASUS BCM20702A0                                     | 2        | 0.75%   |
| Apple Bluetooth USB Host Controller                 | 2        | 0.75%   |
| Apple Bluetooth Host Controller                     | 2        | 0.75%   |
| Apple Bluetooth HCI                                 | 2        | 0.75%   |
| Actions general adapter                             | 2        | 0.75%   |
| Ralink RT3290 Bluetooth                             | 1        | 0.37%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1        | 0.37%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1        | 0.37%   |
| Qcom Bluetooth USB                                  | 1        | 0.37%   |
| IMC Networks Wireless_Device                        | 1        | 0.37%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1        | 0.37%   |
| Edimax Bluetooth Device                             | 1        | 0.37%   |
| Broadcom Bluetooth dongle                           | 1        | 0.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 477      | 40.05%  |
| AMD                                          | 273      | 22.92%  |
| Nvidia                                       | 267      | 22.42%  |
| C-Media Electronics                          | 43       | 3.61%   |
| Logitech                                     | 17       | 1.43%   |
| Creative Labs                                | 17       | 1.43%   |
| Generalplus Technology                       | 9        | 0.76%   |
| JMTek                                        | 8        | 0.67%   |
| Texas Instruments                            | 6        | 0.5%    |
| Razer USA                                    | 5        | 0.42%   |
| Creative Technology                          | 5        | 0.42%   |
| Micro Star International                     | 4        | 0.34%   |
| GN Netcom                                    | 4        | 0.34%   |
| Corsair                                      | 4        | 0.34%   |
| BEHRINGER International                      | 4        | 0.34%   |
| ASUSTek Computer                             | 4        | 0.34%   |
| Plantronics                                  | 3        | 0.25%   |
| Zoran Co. Personal Media Division (Nogatech) | 2        | 0.17%   |
| VIA Technologies                             | 2        | 0.17%   |
| Thesycon Systemsoftware & Consulting         | 2        | 0.17%   |
| M-Audio                                      | 2        | 0.17%   |
| KTMicro                                      | 2        | 0.17%   |
| Jieli Technology                             | 2        | 0.17%   |
| Hewlett-Packard                              | 2        | 0.17%   |
| Focusrite-Novation                           | 2        | 0.17%   |
| Cambridge Silicon Radio                      | 2        | 0.17%   |
| Tenx Technology                              | 1        | 0.08%   |
| Sony                                         | 1        | 0.08%   |
| Samson Technologies                          | 1        | 0.08%   |
| Realtek Semiconductor                        | 1        | 0.08%   |
| PreSonus Audio Electronics                   | 1        | 0.08%   |
| Philips Speech Processing                    | 1        | 0.08%   |
| Nordic Semiconductor ASA                     | 1        | 0.08%   |
| Native Instruments                           | 1        | 0.08%   |
| Microsoft                                    | 1        | 0.08%   |
| Kingston Technology                          | 1        | 0.08%   |
| iCreate Technologies                         | 1        | 0.08%   |
| Goldvish                                     | 1        | 0.08%   |
| Fortemedia                                   | 1        | 0.08%   |
| fifine Microphones                           | 1        | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 81       | 5.9%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 64       | 4.66%   |
| AMD Starship/Matisse HD Audio Controller                                          | 45       | 3.28%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 42       | 3.06%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 42       | 3.06%   |
| Intel Cannon Lake PCH cAVS                                                        | 38       | 2.77%   |
| AMD Ryzen HD Audio Controller                                                     | 38       | 2.77%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 37       | 2.69%   |
| Intel 200 Series PCH HD Audio                                                     | 36       | 2.62%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 35       | 2.55%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 33       | 2.4%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 29       | 2.11%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 25       | 1.82%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 24       | 1.75%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 23       | 1.68%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 21       | 1.53%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 20       | 1.46%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 20       | 1.46%   |
| AMD FCH Azalia Controller                                                         | 19       | 1.38%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 18       | 1.31%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 18       | 1.31%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 18       | 1.31%   |
| Nvidia GP106 High Definition Audio Controller                                     | 16       | 1.17%   |
| Nvidia GF108 High Definition Audio Controller                                     | 15       | 1.09%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 14       | 1.02%   |
| Nvidia TU116 High Definition Audio Controller                                     | 13       | 0.95%   |
| Nvidia GP104 High Definition Audio Controller                                     | 13       | 0.95%   |
| Nvidia GA104 High Definition Audio Controller                                     | 12       | 0.87%   |
| Nvidia High Definition Audio Controller                                           | 11       | 0.8%    |
| Intel Raptor Lake High Definition Audio Controller                                | 11       | 0.8%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 11       | 0.8%    |
| Nvidia GP108 High Definition Audio Controller                                     | 10       | 0.73%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 10       | 0.73%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 10       | 0.73%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 10       | 0.73%   |
| AMD Radeon High Definition Audio Controller                                       | 10       | 0.73%   |
| Nvidia TU106 High Definition Audio Controller                                     | 9        | 0.66%   |
| Nvidia TU104 HD Audio Controller                                                  | 9        | 0.66%   |
| Nvidia GM204 High Definition Audio Controller                                     | 9        | 0.66%   |
| Nvidia GF119 HDMI Audio Controller                                                | 9        | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 38       | 24.84%  |
| Samsung Electronics          | 19       | 12.42%  |
| Unknown                      | 16       | 10.46%  |
| Corsair                      | 14       | 9.15%   |
| SK hynix                     | 11       | 7.19%   |
| Crucial                      | 10       | 6.54%   |
| G.Skill                      | 9        | 5.88%   |
| Micron Technology            | 6        | 3.92%   |
| Nanya Technology             | 4        | 2.61%   |
| Ramaxel Technology           | 3        | 1.96%   |
| Patriot                      | 3        | 1.96%   |
| A-DATA Technology            | 3        | 1.96%   |
| Unknown                      | 3        | 1.96%   |
| Transcend                    | 2        | 1.31%   |
| Team                         | 2        | 1.31%   |
| Apacer                       | 2        | 1.31%   |
| Unknown (82B5)               | 1        | 0.65%   |
| Unknown (0x5846)             | 1        | 0.65%   |
| Unknown (0x038A)             | 1        | 0.65%   |
| Timetec                      | 1        | 0.65%   |
| PNY                          | 1        | 0.65%   |
| Patriot Memory (PDP Systems) | 1        | 0.65%   |
| Neo Forza                    | 1        | 0.65%   |
| CSX                          | 1        | 0.65%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Unknown                                                         | 3        | 1.88%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                            | 2        | 1.25%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                            | 2        | 1.25%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                    | 2        | 1.25%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s                     | 2        | 1.25%   |
| SK hynix RAM HMT31GR7BFR4C-H9 8GB DIMM DDR3 1333MT/s            | 2        | 1.25%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s           | 2        | 1.25%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s             | 2        | 1.25%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s             | 2        | 1.25%   |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 3066MT/s            | 2        | 1.25%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3600MT/s           | 2        | 1.25%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                       | 1        | 0.63%   |
| Unknown RAM Module 8GB DIMM DDR3 1066MT/s                       | 1        | 0.63%   |
| Unknown RAM Module 8192MB DIMM DDR3 1066MT/s                    | 1        | 0.63%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                         | 1        | 0.63%   |
| Unknown RAM Module 8192MB DIMM 1066MT/s                         | 1        | 0.63%   |
| Unknown RAM Module 512MB DIMM SDRAM                             | 1        | 0.63%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                       | 1        | 0.63%   |
| Unknown RAM Module 2GB DIMM SDRAM 800MT/s                       | 1        | 0.63%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                            | 1        | 0.63%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                     | 1        | 0.63%   |
| Unknown RAM Module 2048MB DIMM DDR 133MT/s                      | 1        | 0.63%   |
| Unknown RAM Module 16GB DIMM DDR4 2667MT/s                      | 1        | 0.63%   |
| Unknown RAM Module 1024MB DIMM SDRAM                            | 1        | 0.63%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s                     | 1        | 0.63%   |
| Unknown (82B5) RAM OP 117100 05/14 2M 4096MB DIMM DDR3 1333MT/s | 1        | 0.63%   |
| Unknown (0x5846) RAM DDR4 NB 8G 2666 8GB SODIMM DDR4 2667MT/s   | 1        | 0.63%   |
| Unknown (0x038A) RAM Module 4GB DIMM DDR3 1066MT/s              | 1        | 0.63%   |
| Transcend RAM JM800QSU-2G 2GB SODIMM DDR2 975MT/s               | 1        | 0.63%   |
| Transcend RAM JM1333KLN-2G 2GB DIMM DDR3 1333MT/s               | 1        | 0.63%   |
| Timetec RAM U8G-1333 8GB DIMM DDR3 1333MT/s                     | 1        | 0.63%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1866MT/s              | 1        | 0.63%   |
| Team RAM TEAMGROUP-UD3 8GB DIMM DDR3 1600MT/s                   | 1        | 0.63%   |
| SK hynix RAM Module 8GB DIMM DDR4 2667MT/s                      | 1        | 0.63%   |
| SK hynix RAM HYMP112U64CP8-Y5 1GB DIMM 1639MT/s                 | 1        | 0.63%   |
| SK hynix RAM HMT42GR7BMR4C 16GB DIMM DDR3 1066MT/s              | 1        | 0.63%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s            | 1        | 0.63%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s            | 1        | 0.63%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s            | 1        | 0.63%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s          | 1        | 0.63%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 52       | 43.33%  |
| DDR4    | 42       | 35%     |
| SDRAM   | 8        | 6.67%   |
| DDR2    | 8        | 6.67%   |
| Unknown | 7        | 5.83%   |
| LPDDR4  | 1        | 0.83%   |
| DDR5    | 1        | 0.83%   |
| DDR     | 1        | 0.83%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 108      | 91.53%  |
| SODIMM       | 8        | 6.78%   |
| Row Of Chips | 1        | 0.85%   |
| FB-DIMM      | 1        | 0.85%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 53       | 39.26%  |
| 4096  | 33       | 24.44%  |
| 2048  | 20       | 14.81%  |
| 16384 | 19       | 14.07%  |
| 1024  | 6        | 4.44%   |
| 32768 | 3        | 2.22%   |
| 512   | 1        | 0.74%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1333    | 25       | 17.86%  |
| 1600    | 24       | 17.14%  |
| 2400    | 9        | 6.43%   |
| 3600    | 8        | 5.71%   |
| 3200    | 8        | 5.71%   |
| 2667    | 6        | 4.29%   |
| 667     | 6        | 4.29%   |
| 2133    | 5        | 3.57%   |
| 800     | 5        | 3.57%   |
| 1866    | 4        | 2.86%   |
| 1066    | 4        | 2.86%   |
| 3733    | 3        | 2.14%   |
| 1867    | 3        | 2.14%   |
| 1800    | 3        | 2.14%   |
| 3466    | 2        | 1.43%   |
| 3066    | 2        | 1.43%   |
| 2933    | 2        | 1.43%   |
| 1639    | 2        | 1.43%   |
| 7200    | 1        | 0.71%   |
| 4800    | 1        | 0.71%   |
| 4000    | 1        | 0.71%   |
| 3866    | 1        | 0.71%   |
| 3400    | 1        | 0.71%   |
| 3334    | 1        | 0.71%   |
| 3266    | 1        | 0.71%   |
| 3007    | 1        | 0.71%   |
| 3000    | 1        | 0.71%   |
| 2934    | 1        | 0.71%   |
| 2800    | 1        | 0.71%   |
| 2733    | 1        | 0.71%   |
| 2666    | 1        | 0.71%   |
| 2200    | 1        | 0.71%   |
| 2000    | 1        | 0.71%   |
| 975     | 1        | 0.71%   |
| 533     | 1        | 0.71%   |
| 133     | 1        | 0.71%   |
| Unknown | 1        | 0.71%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 13       | 40.63%  |
| Brother Industries    | 6        | 18.75%  |
| Canon                 | 5        | 15.63%  |
| Samsung Electronics   | 3        | 9.38%   |
| Lexmark International | 2        | 6.25%   |
| Seiko Epson           | 1        | 3.13%   |
| PM                    | 1        | 3.13%   |
| Dymo-CoStar           | 1        | 3.13%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Seiko Epson XP-4100 Series                 | 1        | 3.13%   |
| Samsung M288x Series                       | 1        | 3.13%   |
| Samsung M2070 Series                       | 1        | 3.13%   |
| Samsung M2020 Series                       | 1        | 3.13%   |
| PM PM241-BT                                | 1        | 3.13%   |
| Lexmark International Laser Printer E210   | 1        | 3.13%   |
| Lexmark International InkJet Color Printer | 1        | 3.13%   |
| HP Smart Tank 580-590 series               | 1        | 3.13%   |
| HP Printing Support                        | 1        | 3.13%   |
| HP OfficeJet 5200 series                   | 1        | 3.13%   |
| HP LaserJet Pro M201dw                     | 1        | 3.13%   |
| HP LaserJet 1320                           | 1        | 3.13%   |
| HP LaserJet 1300                           | 1        | 3.13%   |
| HP LaserJet 1020                           | 1        | 3.13%   |
| HP Ink Tank 110 series                     | 1        | 3.13%   |
| HP HP LaserJet M101-M106                   | 1        | 3.13%   |
| HP Deskjet 3520 series                     | 1        | 3.13%   |
| HP DeskJet 2700 series                     | 1        | 3.13%   |
| HP Deskjet 2050 J510                       | 1        | 3.13%   |
| HP Deskjet 1000 J110 series                | 1        | 3.13%   |
| Dymo-CoStar LabelWriter 450                | 1        | 3.13%   |
| Canon TR8500 series                        | 1        | 3.13%   |
| Canon PIXMA MX390 Series                   | 1        | 3.13%   |
| Canon PIXMA MG3600 Series                  | 1        | 3.13%   |
| Canon MF4320-4350                          | 1        | 3.13%   |
| Canon LiDE 300                             | 1        | 3.13%   |
| Brother MFC-T910DW                         | 1        | 3.13%   |
| Brother MFC-J5335DW                        | 1        | 3.13%   |
| Brother MFC-J5330DW                        | 1        | 3.13%   |
| Brother HL-5450DN series                   | 1        | 3.13%   |
| Brother HL-4140CN series                   | 1        | 3.13%   |
| Brother DCP-L2550DN series                 | 1        | 3.13%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 2        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20 | 1        | 50%     |
| Canon CanoScan LIDE 25             | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 37       | 30.58%  |
| Microsoft                     | 10       | 8.26%   |
| Microdia                      | 10       | 8.26%   |
| Apple                         | 7        | 5.79%   |
| Z-Star Microelectronics       | 5        | 4.13%   |
| Chicony Electronics           | 5        | 4.13%   |
| Sunplus Innovation Technology | 4        | 3.31%   |
| Samsung Electronics           | 4        | 3.31%   |
| Generalplus Technology        | 4        | 3.31%   |
| Alcor Micro                   | 3        | 2.48%   |
| SunplusIT                     | 2        | 1.65%   |
| Realtek Semiconductor         | 2        | 1.65%   |
| KYE Systems (Mouse Systems)   | 2        | 1.65%   |
| GEMBIRD                       | 2        | 1.65%   |
| Cubeternet                    | 2        | 1.65%   |
| WaveRider Communications      | 1        | 0.83%   |
| USB 4K Camera                 | 1        | 0.83%   |
| Trust                         | 1        | 0.83%   |
| Teslong Camera                | 1        | 0.83%   |
| Syntek                        | 1        | 0.83%   |
| Sunplus IT                    | 1        | 0.83%   |
| Silicon Motion                | 1        | 0.83%   |
| Razer USA                     | 1        | 0.83%   |
| Pixart Imaging                | 1        | 0.83%   |
| Philips (or NXP)              | 1        | 0.83%   |
| OmniVision Technologies       | 1        | 0.83%   |
| MacroSilicon                  | 1        | 0.83%   |
| LG Electronics                | 1        | 0.83%   |
| Lenovo                        | 1        | 0.83%   |
| Jieli Technology              | 1        | 0.83%   |
| Hewlett-Packard               | 1        | 0.83%   |
| HD USB Camera                 | 1        | 0.83%   |
| Guillemot                     | 1        | 0.83%   |
| Creative Technology           | 1        | 0.83%   |
| AVerMedia Technologies        | 1        | 0.83%   |
| Arkmicro Technologies         | 1        | 0.83%   |
| ANYKA                         | 1        | 0.83%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920             | 10       | 8.26%   |
| Microsoft LifeCam HD-3000               | 5        | 4.13%   |
| Logitech Webcam C270                    | 5        | 4.13%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X         | 5        | 4.13%   |
| Samsung Galaxy series, misc. (MTP mode) | 4        | 3.31%   |
| Microdia USB 2.0 Camera                 | 3        | 2.48%   |
| Microdia Integrated Camera              | 3        | 2.48%   |
| Logitech HD Webcam C615                 | 3        | 2.48%   |
| Logitech C922 Pro Stream Webcam         | 3        | 2.48%   |
| Chicony HP High Definition 1MP Webcam   | 3        | 2.48%   |
| Z-Star Venus USB2.0 Camera              | 2        | 1.65%   |
| Microsoft LifeCam VX-800                | 2        | 1.65%   |
| Logitech Webcam C600                    | 2        | 1.65%   |
| Logitech Logitech Webcam C925e          | 2        | 1.65%   |
| Logitech BRIO 4K Stream Edition         | 2        | 1.65%   |
| Logitech B525 HD Webcam                 | 2        | 1.65%   |
| Generalplus WEB CAM                     | 2        | 1.65%   |
| Generalplus GENERAL WEBCAM              | 2        | 1.65%   |
| GEMBIRD USB2.0 PC CAMERA                | 2        | 1.65%   |
| Cubeternet GL-UPC822 UVC WebCam         | 2        | 1.65%   |
| Z-Star Vega USB 2.0 Camera              | 1        | 0.83%   |
| Z-Star Sirius USB2.0 Camera             | 1        | 0.83%   |
| Z-Star Integrated Camera                | 1        | 0.83%   |
| WaveRider USB 2.0 Camera                | 1        | 0.83%   |
| USB 4K Camera                           | 1        | 0.83%   |
| Trust USB Camera                        | 1        | 0.83%   |
| Teslong Camera                          | 1        | 0.83%   |
| Syntek USB Video Device                 | 1        | 0.83%   |
| SunplusIT USB IR Camera                 | 1        | 0.83%   |
| SunplusIT SPCA2650 AV Camera            | 1        | 0.83%   |
| Sunplus IT PC Camera                    | 1        | 0.83%   |
| Sunplus USB 2.0 Camera                  | 1        | 0.83%   |
| Sunplus Integrated Camera               | 1        | 0.83%   |
| Sunplus HK 5M WebCAM                    | 1        | 0.83%   |
| Sunplus Aukey-PC-LM1E Camera            | 1        | 0.83%   |
| Silicon Motion Silicon Motion Camera    | 1        | 0.83%   |
| Realtek USB 2.0 Camera                  | 1        | 0.83%   |
| Realtek FULL HD 1080P Webcam            | 1        | 0.83%   |
| Razer USA Razer Kiyo Pro                | 1        | 0.83%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro    | 1        | 0.83%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| LighTuning Technology | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| LighTuning Fingerprint Sensor | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Alcor Micro          | 3        | 42.86%  |
| OmniKey              | 1        | 14.29%  |
| Jing-Mold Enterprise | 1        | 14.29%  |
| Feitian Technologies | 1        | 14.29%  |
| Chicony Electronics  | 1        | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Alcor Micro AU9540 Smartcard Reader                               | 3        | 42.86%  |
| OmniKey CardMan 3121 (HID Technologies)                           | 1        | 14.29%  |
| Jing-Mold Enterprise HP USB Business Slim Smartcard CCID Keyboard | 1        | 14.29%  |
| Feitian Technologies SCR301                                       | 1        | 14.29%  |
| Chicony Electronics HP Skylab USB Smartcard Keyboard              | 1        | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 584      | 83.55%  |
| 1     | 97       | 13.88%  |
| 2     | 15       | 2.15%   |
| 4     | 2        | 0.29%   |
| 3     | 1        | 0.14%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 55       | 42.31%  |
| Graphics card            | 32       | 24.62%  |
| Sound                    | 7        | 5.38%   |
| Unassigned class         | 6        | 4.62%   |
| Chipcard                 | 5        | 3.85%   |
| Network                  | 4        | 3.08%   |
| Multimedia controller    | 4        | 3.08%   |
| Net/ethernet             | 3        | 2.31%   |
| Communication controller | 3        | 2.31%   |
| Card reader              | 3        | 2.31%   |
| Bluetooth                | 3        | 2.31%   |
| Camera                   | 2        | 1.54%   |
| Storage/raid             | 1        | 0.77%   |
| Storage/ide              | 1        | 0.77%   |
| Fingerprint reader       | 1        | 0.77%   |

