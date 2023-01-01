Elementary - Tested Hardware & Statistics
-----------------------------------------

A project to collect tested hardware configurations for Elementary.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Elementary/Desktop/README.md) and [notebooks](/Dist/Elementary/Notebook/README.md).

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

Total: 1883

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | System XPS L702X            | Notebook    | [7030c340cc](https://linux-hardware.org/?probe=7030c340cc) | Dec 31, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [e7ac43e8c3](https://linux-hardware.org/?probe=e7ac43e8c3) | Dec 31, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [4d613961a4](https://linux-hardware.org/?probe=4d613961a4) | Dec 31, 2022 |
| Chuwi         | HeroBook                    | Notebook    | [1664994b07](https://linux-hardware.org/?probe=1664994b07) | Dec 30, 2022 |
| HP            | ProBook 455R G6             | Notebook    | [71c9651ee2](https://linux-hardware.org/?probe=71c9651ee2) | Dec 30, 2022 |
| ASRock        | H110 Pro BTC+               | Desktop     | [a7ccef79ad](https://linux-hardware.org/?probe=a7ccef79ad) | Dec 30, 2022 |
| AMI           | F3C2                        | Notebook    | [ed7d4a2a13](https://linux-hardware.org/?probe=ed7d4a2a13) | Dec 30, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [1780cf9c13](https://linux-hardware.org/?probe=1780cf9c13) | Dec 29, 2022 |
| Lenovo        | V17 G2 ITL 82NX             | Notebook    | [5e094b34a5](https://linux-hardware.org/?probe=5e094b34a5) | Dec 29, 2022 |
| Acer          | Aspire A315-53              | Notebook    | [9c28036440](https://linux-hardware.org/?probe=9c28036440) | Dec 29, 2022 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [b3970a8e5a](https://linux-hardware.org/?probe=b3970a8e5a) | Dec 29, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [c93684da4d](https://linux-hardware.org/?probe=c93684da4d) | Dec 29, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [7b03f438db](https://linux-hardware.org/?probe=7b03f438db) | Dec 28, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [5c9cadd190](https://linux-hardware.org/?probe=5c9cadd190) | Dec 28, 2022 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | Notebook    | [f5c5147826](https://linux-hardware.org/?probe=f5c5147826) | Dec 28, 2022 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | Notebook    | [8dfcf5860f](https://linux-hardware.org/?probe=8dfcf5860f) | Dec 28, 2022 |
| Lenovo        | ThinkPad T430 23448AG       | Notebook    | [00ba06cfd1](https://linux-hardware.org/?probe=00ba06cfd1) | Dec 28, 2022 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [b6413f9cf2](https://linux-hardware.org/?probe=b6413f9cf2) | Dec 28, 2022 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [4ddf1fecb8](https://linux-hardware.org/?probe=4ddf1fecb8) | Dec 28, 2022 |
| Lenovo        | ThinkPad T430 23448AG       | Notebook    | [a570034bbc](https://linux-hardware.org/?probe=a570034bbc) | Dec 27, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [bc58be5546](https://linux-hardware.org/?probe=bc58be5546) | Dec 27, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [f9bde62142](https://linux-hardware.org/?probe=f9bde62142) | Dec 27, 2022 |
| Lenovo        | V310-14ISK 80SX             | Notebook    | [a1e4dd02b2](https://linux-hardware.org/?probe=a1e4dd02b2) | Dec 27, 2022 |
| Lenovo        | V310-14ISK 80SX             | Notebook    | [cedf39754e](https://linux-hardware.org/?probe=cedf39754e) | Dec 27, 2022 |
| Acer          | Aspire 7741                 | Notebook    | [5ef8e01957](https://linux-hardware.org/?probe=5ef8e01957) | Dec 27, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [e979df032a](https://linux-hardware.org/?probe=e979df032a) | Dec 26, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [5ea84f62cb](https://linux-hardware.org/?probe=5ea84f62cb) | Dec 25, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [c545cf1f08](https://linux-hardware.org/?probe=c545cf1f08) | Dec 25, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [3fc3ad1b46](https://linux-hardware.org/?probe=3fc3ad1b46) | Dec 25, 2022 |
| GMKtec        | NucBox8                     | Server      | [abc999a1a4](https://linux-hardware.org/?probe=abc999a1a4) | Dec 24, 2022 |
| Lenovo        | ThinkPad T495 20NKS01W02    | Notebook    | [cc7b02033a](https://linux-hardware.org/?probe=cc7b02033a) | Dec 24, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [6de981f1fc](https://linux-hardware.org/?probe=6de981f1fc) | Dec 24, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [afb738446f](https://linux-hardware.org/?probe=afb738446f) | Dec 24, 2022 |
| Avell High... | B.ON                        | Notebook    | [ea8a4babbf](https://linux-hardware.org/?probe=ea8a4babbf) | Dec 24, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [d1e21fd9ca](https://linux-hardware.org/?probe=d1e21fd9ca) | Dec 23, 2022 |
| Lenovo        | ThinkCentre M71e 3129C3G    | Desktop     | [cb9f99f1cf](https://linux-hardware.org/?probe=cb9f99f1cf) | Dec 23, 2022 |
| Microsoft     | Surface Pro 2               | Tablet      | [3237ff6784](https://linux-hardware.org/?probe=3237ff6784) | Dec 22, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [91a9d07c9f](https://linux-hardware.org/?probe=91a9d07c9f) | Dec 22, 2022 |
| Lenovo        | ThinkPad X201 3680HB1       | Notebook    | [41e1719d61](https://linux-hardware.org/?probe=41e1719d61) | Dec 22, 2022 |
| Lenovo        | ThinkPad X201 3680HB1       | Notebook    | [01e9dfa8b8](https://linux-hardware.org/?probe=01e9dfa8b8) | Dec 22, 2022 |
| Positivo      | S14SL01                     | Notebook    | [476e8a784c](https://linux-hardware.org/?probe=476e8a784c) | Dec 21, 2022 |
| Positivo      | S14SL01                     | Notebook    | [08e3a4d7f2](https://linux-hardware.org/?probe=08e3a4d7f2) | Dec 21, 2022 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [3d89cf5c71](https://linux-hardware.org/?probe=3d89cf5c71) | Dec 21, 2022 |
| Acidanther... | Mac-CFF7D910A743CAAF iMa... | All in one  | [4efe19137d](https://linux-hardware.org/?probe=4efe19137d) | Dec 21, 2022 |
| Lenovo        | V17 G2 ITL 82NX             | Notebook    | [a285792280](https://linux-hardware.org/?probe=a285792280) | Dec 20, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [660c9e5023](https://linux-hardware.org/?probe=660c9e5023) | Dec 20, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [d854f4c5ad](https://linux-hardware.org/?probe=d854f4c5ad) | Dec 20, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [54fbda3732](https://linux-hardware.org/?probe=54fbda3732) | Dec 20, 2022 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [6fdcb5b8b4](https://linux-hardware.org/?probe=6fdcb5b8b4) | Dec 20, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [2fa8510855](https://linux-hardware.org/?probe=2fa8510855) | Dec 19, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [da494e2be3](https://linux-hardware.org/?probe=da494e2be3) | Dec 19, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [10e579b77e](https://linux-hardware.org/?probe=10e579b77e) | Dec 18, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [1bd00059e2](https://linux-hardware.org/?probe=1bd00059e2) | Dec 17, 2022 |
| Lenovo        | V17 G2 ITL 82NX             | Notebook    | [f777de4f53](https://linux-hardware.org/?probe=f777de4f53) | Dec 17, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [7236ad8a5d](https://linux-hardware.org/?probe=7236ad8a5d) | Dec 17, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [2991f8736b](https://linux-hardware.org/?probe=2991f8736b) | Dec 16, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [69776fdb13](https://linux-hardware.org/?probe=69776fdb13) | Dec 16, 2022 |
| HP            | Pavilion g6                 | Notebook    | [d1bfb26644](https://linux-hardware.org/?probe=d1bfb26644) | Dec 16, 2022 |
| HUAWEI        | NBM-WXX9                    | Notebook    | [a9f5b0866f](https://linux-hardware.org/?probe=a9f5b0866f) | Dec 16, 2022 |
| Lenovo        | V17 G2 ITL 82NX             | Notebook    | [4f1aa7401d](https://linux-hardware.org/?probe=4f1aa7401d) | Dec 15, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [09c89a9bef](https://linux-hardware.org/?probe=09c89a9bef) | Dec 15, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [35d2e25287](https://linux-hardware.org/?probe=35d2e25287) | Dec 15, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [615d3e1599](https://linux-hardware.org/?probe=615d3e1599) | Dec 14, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [ed707b6698](https://linux-hardware.org/?probe=ed707b6698) | Dec 13, 2022 |
| Dell          | 08WKV3 A00                  | Desktop     | [f58a0ffbc3](https://linux-hardware.org/?probe=f58a0ffbc3) | Dec 13, 2022 |
| MSI           | GF63 Thin 10SC              | Notebook    | [ed86ad34cf](https://linux-hardware.org/?probe=ed86ad34cf) | Dec 13, 2022 |
| MSI           | GF63 Thin 10SC              | Notebook    | [18c3d0d050](https://linux-hardware.org/?probe=18c3d0d050) | Dec 13, 2022 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [0a7b9bd226](https://linux-hardware.org/?probe=0a7b9bd226) | Dec 12, 2022 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [e2d976c5f4](https://linux-hardware.org/?probe=e2d976c5f4) | Dec 11, 2022 |
| MSI           | B350 TOMAHAWK               | Desktop     | [0ce6563922](https://linux-hardware.org/?probe=0ce6563922) | Dec 11, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [c91212b8ed](https://linux-hardware.org/?probe=c91212b8ed) | Dec 11, 2022 |
| ASUSTek       | Zenbook UP5401EA_UP5401E... | Convertible | [6b999f972f](https://linux-hardware.org/?probe=6b999f972f) | Dec 10, 2022 |
| ASUSTek       | Zenbook UP5401EA_UP5401E... | Convertible | [c415ea37d7](https://linux-hardware.org/?probe=c415ea37d7) | Dec 10, 2022 |
| Lenovo        | ThinkPad X390 20Q0CTO1WW    | Notebook    | [52546b1dd0](https://linux-hardware.org/?probe=52546b1dd0) | Dec 10, 2022 |
| ASUSTek       | Z170-P                      | Desktop     | [5180b907e3](https://linux-hardware.org/?probe=5180b907e3) | Dec 10, 2022 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | Desktop     | [5ca8db90bb](https://linux-hardware.org/?probe=5ca8db90bb) | Dec 10, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [46d77ce0b4](https://linux-hardware.org/?probe=46d77ce0b4) | Dec 09, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [5d462a147a](https://linux-hardware.org/?probe=5d462a147a) | Dec 08, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [30457468d5](https://linux-hardware.org/?probe=30457468d5) | Dec 08, 2022 |
| Jumper        | EZpad                       | Tablet      | [68b8181601](https://linux-hardware.org/?probe=68b8181601) | Dec 07, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [88196a712d](https://linux-hardware.org/?probe=88196a712d) | Dec 07, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [906e4966a6](https://linux-hardware.org/?probe=906e4966a6) | Dec 07, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [1a1f2b375d](https://linux-hardware.org/?probe=1a1f2b375d) | Dec 05, 2022 |
| ASRock        | H55M-LE                     | Desktop     | [9d2066a479](https://linux-hardware.org/?probe=9d2066a479) | Dec 03, 2022 |
| Fujitsu       | D3602-A1 S26361-D3602-A1    | Desktop     | [6f57ed994c](https://linux-hardware.org/?probe=6f57ed994c) | Dec 03, 2022 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | Desktop     | [62b19626ce](https://linux-hardware.org/?probe=62b19626ce) | Dec 03, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [19d93a0122](https://linux-hardware.org/?probe=19d93a0122) | Dec 03, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [080e04d17d](https://linux-hardware.org/?probe=080e04d17d) | Dec 02, 2022 |
| Lenovo        | ThinkPad T470p 20J60018M... | Notebook    | [994d8e4b1d](https://linux-hardware.org/?probe=994d8e4b1d) | Dec 01, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [1002df8858](https://linux-hardware.org/?probe=1002df8858) | Dec 01, 2022 |
| Lenovo        | ThinkCentre M70e 0809D1Y    | Desktop     | [0cd85fa9f3](https://linux-hardware.org/?probe=0cd85fa9f3) | Nov 30, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [c4ae439087](https://linux-hardware.org/?probe=c4ae439087) | Nov 30, 2022 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [d95adc01a7](https://linux-hardware.org/?probe=d95adc01a7) | Nov 30, 2022 |
| Dell          | 0TP406                      | Desktop     | [3eceea61d2](https://linux-hardware.org/?probe=3eceea61d2) | Nov 30, 2022 |
| Dell          | 0TP406                      | Desktop     | [d22689331c](https://linux-hardware.org/?probe=d22689331c) | Nov 30, 2022 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [a74a067f14](https://linux-hardware.org/?probe=a74a067f14) | Nov 29, 2022 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [bb49870780](https://linux-hardware.org/?probe=bb49870780) | Nov 28, 2022 |
| Lenovo        | ThinkPad T470p 20J60018M... | Notebook    | [c5f7049b04](https://linux-hardware.org/?probe=c5f7049b04) | Nov 28, 2022 |
| MSI           | IONA                        | Desktop     | [255f7f8dc4](https://linux-hardware.org/?probe=255f7f8dc4) | Nov 28, 2022 |
| MSI           | IONA                        | Desktop     | [94841f2b61](https://linux-hardware.org/?probe=94841f2b61) | Nov 28, 2022 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [33e4e585ab](https://linux-hardware.org/?probe=33e4e585ab) | Nov 27, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [5c395ef8a4](https://linux-hardware.org/?probe=5c395ef8a4) | Nov 26, 2022 |
| Apple         | Mac-7DF2A3B5E5D671ED iMa... | All in one  | [ad4f43c154](https://linux-hardware.org/?probe=ad4f43c154) | Nov 26, 2022 |
| Apple         | Mac-7DF2A3B5E5D671ED iMa... | All in one  | [82059a1b51](https://linux-hardware.org/?probe=82059a1b51) | Nov 26, 2022 |
| LattePanda    | Alpha                       | Desktop     | [be819160d5](https://linux-hardware.org/?probe=be819160d5) | Nov 26, 2022 |
| LattePanda    | Alpha                       | Desktop     | [b3c831db4d](https://linux-hardware.org/?probe=b3c831db4d) | Nov 26, 2022 |
| Lenovo        | ThinkPad T430 2349IF8       | Notebook    | [4d8bd1760a](https://linux-hardware.org/?probe=4d8bd1760a) | Nov 25, 2022 |
| Apple         | MacBook3,1                  | Notebook    | [404821c7d6](https://linux-hardware.org/?probe=404821c7d6) | Nov 25, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [408158ed97](https://linux-hardware.org/?probe=408158ed97) | Nov 24, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [dce27f6d43](https://linux-hardware.org/?probe=dce27f6d43) | Nov 24, 2022 |
| ASUSTek       | 1001PX                      | Notebook    | [9626b2b4c5](https://linux-hardware.org/?probe=9626b2b4c5) | Nov 24, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [d12ab91769](https://linux-hardware.org/?probe=d12ab91769) | Nov 24, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [476415b4e4](https://linux-hardware.org/?probe=476415b4e4) | Nov 22, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [587e23a674](https://linux-hardware.org/?probe=587e23a674) | Nov 22, 2022 |
| MSI           | IONA                        | Desktop     | [280083cfa1](https://linux-hardware.org/?probe=280083cfa1) | Nov 22, 2022 |
| Dell          | Latitude E6520              | Notebook    | [1801edca03](https://linux-hardware.org/?probe=1801edca03) | Nov 22, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [3d8ef86616](https://linux-hardware.org/?probe=3d8ef86616) | Nov 21, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [680aac00bd](https://linux-hardware.org/?probe=680aac00bd) | Nov 21, 2022 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [1e74aa696f](https://linux-hardware.org/?probe=1e74aa696f) | Nov 20, 2022 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | Desktop     | [4f230635de](https://linux-hardware.org/?probe=4f230635de) | Nov 19, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [a4ac6dbf9b](https://linux-hardware.org/?probe=a4ac6dbf9b) | Nov 17, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [9e16721568](https://linux-hardware.org/?probe=9e16721568) | Nov 17, 2022 |
| Dell          | Inspiron 5584               | Notebook    | [f11ce2dd6c](https://linux-hardware.org/?probe=f11ce2dd6c) | Nov 16, 2022 |
| Dell          | 0RW199                      | Desktop     | [df40ccbcdb](https://linux-hardware.org/?probe=df40ccbcdb) | Nov 15, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [11dbbdfcc1](https://linux-hardware.org/?probe=11dbbdfcc1) | Nov 15, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [d07cacacde](https://linux-hardware.org/?probe=d07cacacde) | Nov 15, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [02aab6ab70](https://linux-hardware.org/?probe=02aab6ab70) | Nov 15, 2022 |
| Lenovo        | ThinkPad T430 2349IF8       | Notebook    | [b6e353af2b](https://linux-hardware.org/?probe=b6e353af2b) | Nov 14, 2022 |
| Lenovo        | ThinkPad T430 2349IF8       | Notebook    | [c642a76e3e](https://linux-hardware.org/?probe=c642a76e3e) | Nov 14, 2022 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [32e8c529f0](https://linux-hardware.org/?probe=32e8c529f0) | Nov 14, 2022 |
| Medion        | E7220                       | Notebook    | [7d3df30772](https://linux-hardware.org/?probe=7d3df30772) | Nov 13, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [fef97563a0](https://linux-hardware.org/?probe=fef97563a0) | Nov 13, 2022 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [4629fb5e08](https://linux-hardware.org/?probe=4629fb5e08) | Nov 13, 2022 |
| Apple         | MacBook3,1                  | Notebook    | [3bafc2796b](https://linux-hardware.org/?probe=3bafc2796b) | Nov 11, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [3c63d3fb1e](https://linux-hardware.org/?probe=3c63d3fb1e) | Nov 11, 2022 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [e0aaa027a0](https://linux-hardware.org/?probe=e0aaa027a0) | Nov 11, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [74a1e6875a](https://linux-hardware.org/?probe=74a1e6875a) | Nov 09, 2022 |
| Alienware     | m15 R6                      | Notebook    | [63b53e81ed](https://linux-hardware.org/?probe=63b53e81ed) | Nov 08, 2022 |
| Alienware     | m15 R6                      | Notebook    | [22b8b36df5](https://linux-hardware.org/?probe=22b8b36df5) | Nov 08, 2022 |
| Alienware     | m15 R6                      | Notebook    | [3e808157a3](https://linux-hardware.org/?probe=3e808157a3) | Nov 08, 2022 |
| Microsoft     | Surface Laptop 2            | Tablet      | [43bf170205](https://linux-hardware.org/?probe=43bf170205) | Nov 08, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [c03daa3621](https://linux-hardware.org/?probe=c03daa3621) | Nov 08, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [e9389bc87e](https://linux-hardware.org/?probe=e9389bc87e) | Nov 08, 2022 |
| Dell          | Studio 1558                 | Notebook    | [8be31a4335](https://linux-hardware.org/?probe=8be31a4335) | Nov 07, 2022 |
| Microsoft     | Surface Laptop 2            | Tablet      | [27acb96a8f](https://linux-hardware.org/?probe=27acb96a8f) | Nov 07, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [ddca3f4758](https://linux-hardware.org/?probe=ddca3f4758) | Nov 06, 2022 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [5e4f330840](https://linux-hardware.org/?probe=5e4f330840) | Nov 06, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [390f51010e](https://linux-hardware.org/?probe=390f51010e) | Nov 06, 2022 |
| Packard Be... | EasyNote LS44HR             | Notebook    | [375b78c3f3](https://linux-hardware.org/?probe=375b78c3f3) | Nov 06, 2022 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [c4f305b310](https://linux-hardware.org/?probe=c4f305b310) | Nov 06, 2022 |
| Wortmann      | 1220624_1470150             | Notebook    | [2782ad2c3e](https://linux-hardware.org/?probe=2782ad2c3e) | Nov 05, 2022 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [22bf532b1a](https://linux-hardware.org/?probe=22bf532b1a) | Nov 04, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [505b2c2b5d](https://linux-hardware.org/?probe=505b2c2b5d) | Nov 04, 2022 |
| Sony          | VPCEA1S1R                   | Notebook    | [9dfb83587b](https://linux-hardware.org/?probe=9dfb83587b) | Nov 04, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [f8685beefa](https://linux-hardware.org/?probe=f8685beefa) | Nov 04, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [7d6d6c3c3a](https://linux-hardware.org/?probe=7d6d6c3c3a) | Nov 04, 2022 |
| Gigabyte      | H310M S2H                   | Desktop     | [521297d21c](https://linux-hardware.org/?probe=521297d21c) | Nov 03, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [a5700bebdf](https://linux-hardware.org/?probe=a5700bebdf) | Nov 03, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [5d89464b05](https://linux-hardware.org/?probe=5d89464b05) | Nov 02, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [a4354f496c](https://linux-hardware.org/?probe=a4354f496c) | Nov 02, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [5cf615d5b2](https://linux-hardware.org/?probe=5cf615d5b2) | Nov 02, 2022 |
| Lenovo        | ThinkPad T495 20NKS01W02    | Notebook    | [e4d29df724](https://linux-hardware.org/?probe=e4d29df724) | Nov 02, 2022 |
| HP            | Pavilion dv5                | Notebook    | [fb23cec1a6](https://linux-hardware.org/?probe=fb23cec1a6) | Nov 01, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [f5060f0a8d](https://linux-hardware.org/?probe=f5060f0a8d) | Nov 01, 2022 |
| HP            | Laptop 17-ca3xxx            | Notebook    | [2c42913712](https://linux-hardware.org/?probe=2c42913712) | Oct 31, 2022 |
| MSI           | Modern 14 B10MW             | Notebook    | [cf2b620a60](https://linux-hardware.org/?probe=cf2b620a60) | Oct 31, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [919fad100f](https://linux-hardware.org/?probe=919fad100f) | Oct 31, 2022 |
| Toshiba       | TECRA A11                   | Notebook    | [10d2346f7c](https://linux-hardware.org/?probe=10d2346f7c) | Oct 30, 2022 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [f4c2d5224b](https://linux-hardware.org/?probe=f4c2d5224b) | Oct 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [512acddb70](https://linux-hardware.org/?probe=512acddb70) | Oct 30, 2022 |
| Toshiba       | TECRA A11                   | Notebook    | [1af8ca0ac9](https://linux-hardware.org/?probe=1af8ca0ac9) | Oct 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDC... | Notebook    | [9b90ea1d4d](https://linux-hardware.org/?probe=9b90ea1d4d) | Oct 27, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [6d4b1d0bb3](https://linux-hardware.org/?probe=6d4b1d0bb3) | Oct 25, 2022 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [13873c81b2](https://linux-hardware.org/?probe=13873c81b2) | Oct 24, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [cdd4d21000](https://linux-hardware.org/?probe=cdd4d21000) | Oct 24, 2022 |
| ASUSTek       | UX31A                       | Notebook    | [4b7e610e25](https://linux-hardware.org/?probe=4b7e610e25) | Oct 24, 2022 |
| Toshiba       | TECRA A11                   | Notebook    | [de0b3e96fa](https://linux-hardware.org/?probe=de0b3e96fa) | Oct 23, 2022 |
| Toshiba       | TECRA A11                   | Notebook    | [b91eedb26a](https://linux-hardware.org/?probe=b91eedb26a) | Oct 23, 2022 |
| HP            | 805D                        | Desktop     | [916b6f09ac](https://linux-hardware.org/?probe=916b6f09ac) | Oct 23, 2022 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [4a6e283158](https://linux-hardware.org/?probe=4a6e283158) | Oct 22, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [6354f13944](https://linux-hardware.org/?probe=6354f13944) | Oct 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [484cb84d6b](https://linux-hardware.org/?probe=484cb84d6b) | Oct 18, 2022 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [2dd84a41e8](https://linux-hardware.org/?probe=2dd84a41e8) | Oct 17, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [c5b6ba786e](https://linux-hardware.org/?probe=c5b6ba786e) | Oct 16, 2022 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [ce623178a2](https://linux-hardware.org/?probe=ce623178a2) | Oct 16, 2022 |
| Dell          | 0D28YY A00                  | Desktop     | [435831fd5b](https://linux-hardware.org/?probe=435831fd5b) | Oct 15, 2022 |
| Lenovo        | ThinkPad E14 20RA004VPH     | Notebook    | [23adba19e0](https://linux-hardware.org/?probe=23adba19e0) | Oct 15, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [2b00bd7a92](https://linux-hardware.org/?probe=2b00bd7a92) | Oct 15, 2022 |
| HP            | Pavilion dv7                | Notebook    | [44ae8ac465](https://linux-hardware.org/?probe=44ae8ac465) | Oct 14, 2022 |
| Lenovo        | ThinkPad T420 4236JY2       | Notebook    | [fd260f87a9](https://linux-hardware.org/?probe=fd260f87a9) | Oct 14, 2022 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [64cbdc6e2a](https://linux-hardware.org/?probe=64cbdc6e2a) | Oct 13, 2022 |
| Kraftway      | KWQ67                       | Desktop     | [8346fc15e3](https://linux-hardware.org/?probe=8346fc15e3) | Oct 13, 2022 |
| MSI           | GE70 2QE                    | Notebook    | [2825343a52](https://linux-hardware.org/?probe=2825343a52) | Oct 13, 2022 |
| Kraftway      | KWQ67                       | Desktop     | [d57d34be64](https://linux-hardware.org/?probe=d57d34be64) | Oct 13, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [88772ad191](https://linux-hardware.org/?probe=88772ad191) | Oct 11, 2022 |
| Lenovo        | ThinkPad T470 20JNS08H00    | Notebook    | [8926251d64](https://linux-hardware.org/?probe=8926251d64) | Oct 11, 2022 |
| ASUSTek       | Vivobook Slate T3300KA_T... | Tablet      | [cf1735bf9e](https://linux-hardware.org/?probe=cf1735bf9e) | Oct 11, 2022 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [db3419c5de](https://linux-hardware.org/?probe=db3419c5de) | Oct 09, 2022 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [d19b3b23b5](https://linux-hardware.org/?probe=d19b3b23b5) | Oct 08, 2022 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [7f59512d7b](https://linux-hardware.org/?probe=7f59512d7b) | Oct 08, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [f06f54475b](https://linux-hardware.org/?probe=f06f54475b) | Oct 08, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [84aa1dcbb2](https://linux-hardware.org/?probe=84aa1dcbb2) | Oct 07, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDC... | Notebook    | [20ea012e04](https://linux-hardware.org/?probe=20ea012e04) | Oct 06, 2022 |
| Toshiba       | Satellite C855-1WX          | Notebook    | [78c5bb7120](https://linux-hardware.org/?probe=78c5bb7120) | Oct 06, 2022 |
| Lenovo        | V130-15IKB 81HN             | Notebook    | [823a068620](https://linux-hardware.org/?probe=823a068620) | Oct 03, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | Notebook    | [c086a688f1](https://linux-hardware.org/?probe=c086a688f1) | Oct 02, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [4ce296ba38](https://linux-hardware.org/?probe=4ce296ba38) | Sep 30, 2022 |
| ASRock        | X370 Taichi                 | Desktop     | [d86c708401](https://linux-hardware.org/?probe=d86c708401) | Sep 30, 2022 |
| Dell          | Vostro 5402                 | Notebook    | [57995ec944](https://linux-hardware.org/?probe=57995ec944) | Sep 30, 2022 |
| Google        | Blooglet                    | Notebook    | [44a9c6559f](https://linux-hardware.org/?probe=44a9c6559f) | Sep 29, 2022 |
| Medion        | Akoya E6422 MD99680         | Notebook    | [52c1708200](https://linux-hardware.org/?probe=52c1708200) | Sep 28, 2022 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [18ee2cafd6](https://linux-hardware.org/?probe=18ee2cafd6) | Sep 27, 2022 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [ffc2811bfe](https://linux-hardware.org/?probe=ffc2811bfe) | Sep 27, 2022 |
| Gigabyte      | G41MT-S2                    | Desktop     | [c0b1c8ad8f](https://linux-hardware.org/?probe=c0b1c8ad8f) | Sep 27, 2022 |
| Dell          | Latitude E6540              | Notebook    | [b2abaca929](https://linux-hardware.org/?probe=b2abaca929) | Sep 26, 2022 |
| Dell          | Latitude E5450              | Notebook    | [8738ac7280](https://linux-hardware.org/?probe=8738ac7280) | Sep 26, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [8ee663c695](https://linux-hardware.org/?probe=8ee663c695) | Sep 26, 2022 |
| Dell          | Inspiron 3493               | Notebook    | [b1f8d22e3e](https://linux-hardware.org/?probe=b1f8d22e3e) | Sep 25, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [36a7fc8903](https://linux-hardware.org/?probe=36a7fc8903) | Sep 24, 2022 |
| Packard Be... | IMEDIA S1300                | Desktop     | [13b1f0e28e](https://linux-hardware.org/?probe=13b1f0e28e) | Sep 24, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [36c369745a](https://linux-hardware.org/?probe=36c369745a) | Sep 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [6a0c80f635](https://linux-hardware.org/?probe=6a0c80f635) | Sep 22, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [7cf2d6a810](https://linux-hardware.org/?probe=7cf2d6a810) | Sep 20, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [71339e0cfb](https://linux-hardware.org/?probe=71339e0cfb) | Sep 19, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [a0acb674df](https://linux-hardware.org/?probe=a0acb674df) | Sep 19, 2022 |
| Packard Be... | IMEDIA S1300                | Desktop     | [fae2bea6f3](https://linux-hardware.org/?probe=fae2bea6f3) | Sep 19, 2022 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [573e0dd8fd](https://linux-hardware.org/?probe=573e0dd8fd) | Sep 19, 2022 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [3f3cb3be79](https://linux-hardware.org/?probe=3f3cb3be79) | Sep 19, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [94baca564e](https://linux-hardware.org/?probe=94baca564e) | Sep 19, 2022 |
| ASUSTek       | X555DG                      | Notebook    | [c46c229dfb](https://linux-hardware.org/?probe=c46c229dfb) | Sep 16, 2022 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [db48d27324](https://linux-hardware.org/?probe=db48d27324) | Sep 16, 2022 |
| ASUSTek       | X555DG                      | Notebook    | [e39d4a8247](https://linux-hardware.org/?probe=e39d4a8247) | Sep 16, 2022 |
| Clevo         | W54xEU                      | Notebook    | [bd0c5962bd](https://linux-hardware.org/?probe=bd0c5962bd) | Sep 15, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [7861fa17bf](https://linux-hardware.org/?probe=7861fa17bf) | Sep 14, 2022 |
| MSI           | PS63 Modern 8RD             | Notebook    | [8fa2ea42ed](https://linux-hardware.org/?probe=8fa2ea42ed) | Sep 14, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [c54a63e1a3](https://linux-hardware.org/?probe=c54a63e1a3) | Sep 13, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [2b12cc11f2](https://linux-hardware.org/?probe=2b12cc11f2) | Sep 13, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [b5f851bd15](https://linux-hardware.org/?probe=b5f851bd15) | Sep 12, 2022 |
| Dell          | Inspiron 5458               | Notebook    | [bd26475724](https://linux-hardware.org/?probe=bd26475724) | Sep 12, 2022 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [4673830cd8](https://linux-hardware.org/?probe=4673830cd8) | Sep 12, 2022 |
| Toshiba       | PORTEGE Z30-B               | Notebook    | [6b1829aad1](https://linux-hardware.org/?probe=6b1829aad1) | Sep 12, 2022 |
| Toshiba       | PORTEGE Z30-B               | Notebook    | [9ef29f2258](https://linux-hardware.org/?probe=9ef29f2258) | Sep 12, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [335a8a059b](https://linux-hardware.org/?probe=335a8a059b) | Sep 12, 2022 |
| HP            | ENVY m6                     | Notebook    | [b9de3b6e35](https://linux-hardware.org/?probe=b9de3b6e35) | Sep 11, 2022 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [3d269171e7](https://linux-hardware.org/?probe=3d269171e7) | Sep 11, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [e2d13711aa](https://linux-hardware.org/?probe=e2d13711aa) | Sep 10, 2022 |
| Lenovo        | ThinkPad T460 20FMS271BR    | Notebook    | [f2f2786b99](https://linux-hardware.org/?probe=f2f2786b99) | Sep 10, 2022 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [1d9611ecf1](https://linux-hardware.org/?probe=1d9611ecf1) | Sep 09, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [d2ad94ce21](https://linux-hardware.org/?probe=d2ad94ce21) | Sep 09, 2022 |
| Apple         | MacBookPro11,2              | Notebook    | [47708e7772](https://linux-hardware.org/?probe=47708e7772) | Sep 09, 2022 |
| Apple         | MacBookPro11,4              | Notebook    | [c5d5b88740](https://linux-hardware.org/?probe=c5d5b88740) | Sep 09, 2022 |
| ASUSTek       | GL702VSK                    | Notebook    | [5001a76a0e](https://linux-hardware.org/?probe=5001a76a0e) | Sep 09, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [3932661b8e](https://linux-hardware.org/?probe=3932661b8e) | Sep 07, 2022 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [ae533c2bdf](https://linux-hardware.org/?probe=ae533c2bdf) | Sep 07, 2022 |
| Lenovo        | MIIX 510-12IKB 80XE         | Tablet      | [29b2041a5b](https://linux-hardware.org/?probe=29b2041a5b) | Sep 05, 2022 |
| Acer          | Aspire V5-552               | Notebook    | [031439a681](https://linux-hardware.org/?probe=031439a681) | Sep 04, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [b37d844ab3](https://linux-hardware.org/?probe=b37d844ab3) | Sep 04, 2022 |
| TUXEDO        | Book XP14 Gen12             | Notebook    | [cfb0fb9451](https://linux-hardware.org/?probe=cfb0fb9451) | Sep 04, 2022 |
| Acer          | Aspire X1420G               | Desktop     | [e48b081560](https://linux-hardware.org/?probe=e48b081560) | Sep 04, 2022 |
| Timi          | TM1701                      | Notebook    | [f23c551375](https://linux-hardware.org/?probe=f23c551375) | Sep 03, 2022 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [3a8803f198](https://linux-hardware.org/?probe=3a8803f198) | Sep 01, 2022 |
| Microsoft     | Surface Pro                 | Tablet      | [b6cc2513ff](https://linux-hardware.org/?probe=b6cc2513ff) | Aug 31, 2022 |
| Microsoft     | Surface Pro                 | Tablet      | [e8b26fc530](https://linux-hardware.org/?probe=e8b26fc530) | Aug 31, 2022 |
| Notebook      | NLx0MU                      | Notebook    | [90c9b01136](https://linux-hardware.org/?probe=90c9b01136) | Aug 31, 2022 |
| Notebook      | NLx0MU                      | Notebook    | [77d4b4ff99](https://linux-hardware.org/?probe=77d4b4ff99) | Aug 31, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [f65d685d05](https://linux-hardware.org/?probe=f65d685d05) | Aug 30, 2022 |
| Apple         | Mac-F2208EC8                | Mini pc     | [f262848655](https://linux-hardware.org/?probe=f262848655) | Aug 30, 2022 |
| Apple         | MacBookPro5,2               | Notebook    | [7f66ca2cc7](https://linux-hardware.org/?probe=7f66ca2cc7) | Aug 29, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [0da338038e](https://linux-hardware.org/?probe=0da338038e) | Aug 29, 2022 |
| Standard      | Unknown                     | Notebook    | [62e0164e5b](https://linux-hardware.org/?probe=62e0164e5b) | Aug 29, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | Desktop     | [413bd5a721](https://linux-hardware.org/?probe=413bd5a721) | Aug 29, 2022 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [9274f5e876](https://linux-hardware.org/?probe=9274f5e876) | Aug 29, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [155267063a](https://linux-hardware.org/?probe=155267063a) | Aug 28, 2022 |
| ASUSTek       | M2N68-AM SE2                | Desktop     | [0f71a52e11](https://linux-hardware.org/?probe=0f71a52e11) | Aug 28, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [d67f262815](https://linux-hardware.org/?probe=d67f262815) | Aug 28, 2022 |
| ASUSTek       | X542UA                      | Notebook    | [0bf776cdc1](https://linux-hardware.org/?probe=0bf776cdc1) | Aug 28, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [6bf1dafdbc](https://linux-hardware.org/?probe=6bf1dafdbc) | Aug 27, 2022 |
| HP            | 240 G7 Notebook PC          | Notebook    | [af418375d3](https://linux-hardware.org/?probe=af418375d3) | Aug 27, 2022 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [68248e8ec4](https://linux-hardware.org/?probe=68248e8ec4) | Aug 26, 2022 |
| Complet       | MY8312                      | Notebook    | [4db1527bde](https://linux-hardware.org/?probe=4db1527bde) | Aug 26, 2022 |
| Dell          | Inspiron 5537               | Notebook    | [d05888c5bc](https://linux-hardware.org/?probe=d05888c5bc) | Aug 25, 2022 |
| Dell          | Latitude E7250              | Notebook    | [98f4886ef7](https://linux-hardware.org/?probe=98f4886ef7) | Aug 25, 2022 |
| Lenovo        | ThinkPad T480 20L6S9WY00    | Notebook    | [dfb0ad63df](https://linux-hardware.org/?probe=dfb0ad63df) | Aug 25, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [9ffe8ee96e](https://linux-hardware.org/?probe=9ffe8ee96e) | Aug 24, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [4709584652](https://linux-hardware.org/?probe=4709584652) | Aug 24, 2022 |
| MSI           | MEG Z490I UNIFY             | Desktop     | [34d2d4f66e](https://linux-hardware.org/?probe=34d2d4f66e) | Aug 24, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [6d7ce1962d](https://linux-hardware.org/?probe=6d7ce1962d) | Aug 24, 2022 |
| ASRock        | N68-VGS3 FX                 | Desktop     | [1d2367ccf7](https://linux-hardware.org/?probe=1d2367ccf7) | Aug 23, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [595bf9c8a7](https://linux-hardware.org/?probe=595bf9c8a7) | Aug 23, 2022 |
| Apple         | MacBookAir7,1               | Notebook    | [079a951d65](https://linux-hardware.org/?probe=079a951d65) | Aug 23, 2022 |
| Apple         | Mac-F2208EC8                | Mini pc     | [364b450a4f](https://linux-hardware.org/?probe=364b450a4f) | Aug 23, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [b3fcba32bd](https://linux-hardware.org/?probe=b3fcba32bd) | Aug 22, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [7169cd34ab](https://linux-hardware.org/?probe=7169cd34ab) | Aug 22, 2022 |
| ASUSTek       | K52F                        | Notebook    | [cafd25a659](https://linux-hardware.org/?probe=cafd25a659) | Aug 21, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [08d6e2e6e8](https://linux-hardware.org/?probe=08d6e2e6e8) | Aug 21, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [b01d72c341](https://linux-hardware.org/?probe=b01d72c341) | Aug 20, 2022 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [b545a0cf4f](https://linux-hardware.org/?probe=b545a0cf4f) | Aug 19, 2022 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [f8675baa98](https://linux-hardware.org/?probe=f8675baa98) | Aug 18, 2022 |
| HP            | 240 G7 Notebook PC          | Notebook    | [ffa5707dc9](https://linux-hardware.org/?probe=ffa5707dc9) | Aug 17, 2022 |
| Lenovo        | ThinkPad T460 20FMS271BR    | Notebook    | [a2c5089e9a](https://linux-hardware.org/?probe=a2c5089e9a) | Aug 16, 2022 |
| Gigabyte      | H81M-DS2                    | Desktop     | [e0abb12052](https://linux-hardware.org/?probe=e0abb12052) | Aug 16, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [59456f2a25](https://linux-hardware.org/?probe=59456f2a25) | Aug 16, 2022 |
| HP            | 2AF7                        | Desktop     | [ca8820daa4](https://linux-hardware.org/?probe=ca8820daa4) | Aug 16, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [fb8a250b12](https://linux-hardware.org/?probe=fb8a250b12) | Aug 15, 2022 |
| ASUSTek       | P5B                         | Desktop     | [1c5cafd185](https://linux-hardware.org/?probe=1c5cafd185) | Aug 15, 2022 |
| Gigabyte      | H81M-DS2                    | Desktop     | [5ae2bc3c12](https://linux-hardware.org/?probe=5ae2bc3c12) | Aug 14, 2022 |
| Acer          | Aspire V5-552G              | Notebook    | [f51f3093d9](https://linux-hardware.org/?probe=f51f3093d9) | Aug 12, 2022 |
| ASUSTek       | K43E                        | Notebook    | [fc2d9e330c](https://linux-hardware.org/?probe=fc2d9e330c) | Aug 11, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [b94818059a](https://linux-hardware.org/?probe=b94818059a) | Aug 10, 2022 |
| Toshiba       | Satellite L875-11M          | Notebook    | [5a01928c94](https://linux-hardware.org/?probe=5a01928c94) | Aug 10, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [72cfcef1a6](https://linux-hardware.org/?probe=72cfcef1a6) | Aug 10, 2022 |
| Dell          | Latitude D630               | Notebook    | [5f682c6798](https://linux-hardware.org/?probe=5f682c6798) | Aug 09, 2022 |
| Toshiba       | Satellite L875-11M          | Notebook    | [1b423f639e](https://linux-hardware.org/?probe=1b423f639e) | Aug 09, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [b719fff96d](https://linux-hardware.org/?probe=b719fff96d) | Aug 08, 2022 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [0f4b093f48](https://linux-hardware.org/?probe=0f4b093f48) | Aug 07, 2022 |
| HP            | Pavilion 17                 | Notebook    | [f06bb8d9ab](https://linux-hardware.org/?probe=f06bb8d9ab) | Aug 07, 2022 |
| HP            | Pavilion 17                 | Notebook    | [9c47c2e4f4](https://linux-hardware.org/?probe=9c47c2e4f4) | Aug 07, 2022 |
| TrekStor      | Notebook Slim S130          | Notebook    | [ba73d094e7](https://linux-hardware.org/?probe=ba73d094e7) | Aug 06, 2022 |
| Sony          | VPCEB16FG                   | Notebook    | [6baf989163](https://linux-hardware.org/?probe=6baf989163) | Aug 06, 2022 |
| Sony          | SVS15117FLB                 | Notebook    | [2729210175](https://linux-hardware.org/?probe=2729210175) | Aug 06, 2022 |
| Lenovo        | ThinkPad E470 20H2A02NBR    | Notebook    | [6e4a76904c](https://linux-hardware.org/?probe=6e4a76904c) | Aug 06, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [7594659719](https://linux-hardware.org/?probe=7594659719) | Aug 05, 2022 |
| MSI           | Creator 15 A10SET           | Notebook    | [45d9d06fb8](https://linux-hardware.org/?probe=45d9d06fb8) | Aug 05, 2022 |
| Medion        | Akoya E6422 MD99680         | Notebook    | [86cd2f6a0a](https://linux-hardware.org/?probe=86cd2f6a0a) | Aug 05, 2022 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [fc8e3b6a3b](https://linux-hardware.org/?probe=fc8e3b6a3b) | Aug 05, 2022 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [73488d7a09](https://linux-hardware.org/?probe=73488d7a09) | Aug 05, 2022 |
| Sony          | SVS15117FLB                 | Notebook    | [1f64d30f2f](https://linux-hardware.org/?probe=1f64d30f2f) | Aug 05, 2022 |
| Dell          | Latitude 3190               | Notebook    | [7a0956e5f8](https://linux-hardware.org/?probe=7a0956e5f8) | Aug 04, 2022 |
| ASUSTek       | K43E                        | Notebook    | [373d77aec0](https://linux-hardware.org/?probe=373d77aec0) | Aug 04, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581LV_... | Notebook    | [764d4ebd1b](https://linux-hardware.org/?probe=764d4ebd1b) | Aug 04, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581LV_... | Notebook    | [5dab148c3e](https://linux-hardware.org/?probe=5dab148c3e) | Aug 04, 2022 |
| Dell          | Latitude E6400              | Notebook    | [54db9ae43d](https://linux-hardware.org/?probe=54db9ae43d) | Aug 04, 2022 |
| HP            | Pavilion dv6                | Notebook    | [b921b586f6](https://linux-hardware.org/?probe=b921b586f6) | Aug 02, 2022 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [e430a435bf](https://linux-hardware.org/?probe=e430a435bf) | Aug 02, 2022 |
| HP            | 431                         | Notebook    | [2f6caa3d47](https://linux-hardware.org/?probe=2f6caa3d47) | Aug 02, 2022 |
| HP            | 431                         | Notebook    | [68fa0d3ebc](https://linux-hardware.org/?probe=68fa0d3ebc) | Aug 02, 2022 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [4a6d0213a4](https://linux-hardware.org/?probe=4a6d0213a4) | Aug 02, 2022 |
| Acer          | Aspire X1420G               | Desktop     | [7be7ab2e7e](https://linux-hardware.org/?probe=7be7ab2e7e) | Jul 31, 2022 |
| Dell          | Latitude E6320              | Notebook    | [34270898c6](https://linux-hardware.org/?probe=34270898c6) | Jul 30, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [04487d99ff](https://linux-hardware.org/?probe=04487d99ff) | Jul 30, 2022 |
| Casper        | NIRVANA NOTEBOOK            | Notebook    | [c291b32941](https://linux-hardware.org/?probe=c291b32941) | Jul 29, 2022 |
| Apple         | Mac-F2238AC8                | All in one  | [dca4c898f8](https://linux-hardware.org/?probe=dca4c898f8) | Jul 29, 2022 |
| Lenovo        | ThinkPad T480 20L6S9WY00    | Notebook    | [af8fd9ae70](https://linux-hardware.org/?probe=af8fd9ae70) | Jul 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [e99805635f](https://linux-hardware.org/?probe=e99805635f) | Jul 29, 2022 |
| ASUSTek       | K43E                        | Notebook    | [f6d8225dd6](https://linux-hardware.org/?probe=f6d8225dd6) | Jul 28, 2022 |
| Dell          | Latitude D630               | Notebook    | [a14838d1ef](https://linux-hardware.org/?probe=a14838d1ef) | Jul 28, 2022 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [ab8af10726](https://linux-hardware.org/?probe=ab8af10726) | Jul 28, 2022 |
| Dell          | Latitude E6320              | Notebook    | [a5b77aa0e9](https://linux-hardware.org/?probe=a5b77aa0e9) | Jul 28, 2022 |
| Dell          | Latitude 3190               | Notebook    | [36027c80d2](https://linux-hardware.org/?probe=36027c80d2) | Jul 28, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [b72463cb79](https://linux-hardware.org/?probe=b72463cb79) | Jul 28, 2022 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [d9a5e0b7e6](https://linux-hardware.org/?probe=d9a5e0b7e6) | Jul 27, 2022 |
| HP            | Pavilion g4                 | Notebook    | [c9aa5e235c](https://linux-hardware.org/?probe=c9aa5e235c) | Jul 27, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [8173942fbb](https://linux-hardware.org/?probe=8173942fbb) | Jul 25, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [f4026901c2](https://linux-hardware.org/?probe=f4026901c2) | Jul 25, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [d0a69fba02](https://linux-hardware.org/?probe=d0a69fba02) | Jul 23, 2022 |
| HP            | Pavilion g6                 | Notebook    | [73061b2ed5](https://linux-hardware.org/?probe=73061b2ed5) | Jul 23, 2022 |
| Dell          | 0GM819                      | Desktop     | [373772e538](https://linux-hardware.org/?probe=373772e538) | Jul 21, 2022 |
| Dell          | 00V62H A01                  | Desktop     | [ae809bb317](https://linux-hardware.org/?probe=ae809bb317) | Jul 19, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [810b379dac](https://linux-hardware.org/?probe=810b379dac) | Jul 19, 2022 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [3831dd717e](https://linux-hardware.org/?probe=3831dd717e) | Jul 19, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [d5b50db42e](https://linux-hardware.org/?probe=d5b50db42e) | Jul 19, 2022 |
| Sony          | VPCYB20AL                   | Notebook    | [17169107a8](https://linux-hardware.org/?probe=17169107a8) | Jul 19, 2022 |
| Acer          | Aspire A315-32              | Notebook    | [ec022ec507](https://linux-hardware.org/?probe=ec022ec507) | Jul 18, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [54152fdf16](https://linux-hardware.org/?probe=54152fdf16) | Jul 18, 2022 |
| Sony          | SVF1521F6EW                 | Notebook    | [3f359d9763](https://linux-hardware.org/?probe=3f359d9763) | Jul 17, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [21c49763f5](https://linux-hardware.org/?probe=21c49763f5) | Jul 17, 2022 |
| HP            | ProBook 430 G2              | Notebook    | [0be149d703](https://linux-hardware.org/?probe=0be149d703) | Jul 16, 2022 |
| ASUSTek       | ROG STRIX B360-H GAMING     | Desktop     | [4cc1f4384c](https://linux-hardware.org/?probe=4cc1f4384c) | Jul 12, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [b1c5cb2096](https://linux-hardware.org/?probe=b1c5cb2096) | Jul 12, 2022 |
| Acer          | Aspire X1420G               | Desktop     | [0b7a9cbc2a](https://linux-hardware.org/?probe=0b7a9cbc2a) | Jul 12, 2022 |
| HP            | Notebook                    | Notebook    | [afaaed48c7](https://linux-hardware.org/?probe=afaaed48c7) | Jul 10, 2022 |
| Acer          | Aspire 1830T                | Notebook    | [d2ff08ade8](https://linux-hardware.org/?probe=d2ff08ade8) | Jul 10, 2022 |
| Acer          | Aspire AV15-51              | Notebook    | [1a880a89af](https://linux-hardware.org/?probe=1a880a89af) | Jul 09, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [3db9c636d0](https://linux-hardware.org/?probe=3db9c636d0) | Jul 09, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [b8c450d5fa](https://linux-hardware.org/?probe=b8c450d5fa) | Jul 08, 2022 |
| Acer          | Aspire V3-771               | Notebook    | [e8488fb0e2](https://linux-hardware.org/?probe=e8488fb0e2) | Jul 07, 2022 |
| Intel         | X79Turbo V1.x               | Desktop     | [e4b17550d0](https://linux-hardware.org/?probe=e4b17550d0) | Jul 06, 2022 |
| HP            | Notebook                    | Notebook    | [2bf65688ab](https://linux-hardware.org/?probe=2bf65688ab) | Jul 05, 2022 |
| Dell          | Inspiron 3593               | Notebook    | [d34d56c473](https://linux-hardware.org/?probe=d34d56c473) | Jul 05, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [2919feb689](https://linux-hardware.org/?probe=2919feb689) | Jul 05, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [2933dddc75](https://linux-hardware.org/?probe=2933dddc75) | Jul 04, 2022 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [3fcdd6c039](https://linux-hardware.org/?probe=3fcdd6c039) | Jul 03, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [7df8533350](https://linux-hardware.org/?probe=7df8533350) | Jul 03, 2022 |
| Gigabyte      | Z87X-OC-CF                  | Desktop     | [654459e245](https://linux-hardware.org/?probe=654459e245) | Jul 03, 2022 |
| ASUSTek       | N56VB                       | Notebook    | [88d34c06f3](https://linux-hardware.org/?probe=88d34c06f3) | Jul 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [1a03301817](https://linux-hardware.org/?probe=1a03301817) | Jul 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [859145be97](https://linux-hardware.org/?probe=859145be97) | Jul 02, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [e13cada6ae](https://linux-hardware.org/?probe=e13cada6ae) | Jul 02, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [80a981f992](https://linux-hardware.org/?probe=80a981f992) | Jul 01, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [804bbd8147](https://linux-hardware.org/?probe=804bbd8147) | Jun 30, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [9fe936cec8](https://linux-hardware.org/?probe=9fe936cec8) | Jun 30, 2022 |
| Dell          | Inspiron 5537               | Notebook    | [9758b4dcff](https://linux-hardware.org/?probe=9758b4dcff) | Jun 30, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [579410b791](https://linux-hardware.org/?probe=579410b791) | Jun 28, 2022 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [1023ca742e](https://linux-hardware.org/?probe=1023ca742e) | Jun 27, 2022 |
| Toshiba       | Satellite C870-1H2          | Notebook    | [edc5098a6f](https://linux-hardware.org/?probe=edc5098a6f) | Jun 27, 2022 |
| HP            | Pavilion dv5                | Notebook    | [4d0e23962a](https://linux-hardware.org/?probe=4d0e23962a) | Jun 27, 2022 |
| Apple         | MacBookPro14,2              | Notebook    | [7fe621e5a7](https://linux-hardware.org/?probe=7fe621e5a7) | Jun 27, 2022 |
| Compaq        | Presario CQ-23              | Notebook    | [f55fd14f61](https://linux-hardware.org/?probe=f55fd14f61) | Jun 26, 2022 |
| Gigabyte      | Z690 AORUS MASTER           | Desktop     | [a8073316f6](https://linux-hardware.org/?probe=a8073316f6) | Jun 26, 2022 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [90c166f77b](https://linux-hardware.org/?probe=90c166f77b) | Jun 25, 2022 |
| ASRock        | Z490 Pro4                   | Desktop     | [f84c8a756c](https://linux-hardware.org/?probe=f84c8a756c) | Jun 25, 2022 |
| MSI           | B85I                        | Desktop     | [886f971d22](https://linux-hardware.org/?probe=886f971d22) | Jun 25, 2022 |
| HP            | 339A                        | Desktop     | [822467af7f](https://linux-hardware.org/?probe=822467af7f) | Jun 25, 2022 |
| ASUSTek       | UX303LAB                    | Notebook    | [ae3becae01](https://linux-hardware.org/?probe=ae3becae01) | Jun 24, 2022 |
| HP            | Pavilion g4                 | Notebook    | [d0c8c06219](https://linux-hardware.org/?probe=d0c8c06219) | Jun 24, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [50e049e6fb](https://linux-hardware.org/?probe=50e049e6fb) | Jun 23, 2022 |
| Microsoft     | Surface Pro 2               | Tablet      | [07506542b5](https://linux-hardware.org/?probe=07506542b5) | Jun 21, 2022 |
| Alienware     | m17 R3                      | Notebook    | [ea3305a8af](https://linux-hardware.org/?probe=ea3305a8af) | Jun 20, 2022 |
| Dell          | Latitude E5510              | Notebook    | [1f6cc92f98](https://linux-hardware.org/?probe=1f6cc92f98) | Jun 18, 2022 |
| T-bao         | MINI PC                     | Desktop     | [6b18c66487](https://linux-hardware.org/?probe=6b18c66487) | Jun 18, 2022 |
| HP            | EliteBook 2170p             | Notebook    | [6c7391f201](https://linux-hardware.org/?probe=6c7391f201) | Jun 17, 2022 |
| HP            | ProBook 455R G6             | Notebook    | [31b94c71c7](https://linux-hardware.org/?probe=31b94c71c7) | Jun 16, 2022 |
| HP            | ProBook 455R G6             | Notebook    | [39d04d1188](https://linux-hardware.org/?probe=39d04d1188) | Jun 16, 2022 |
| Pegatron      | 2ACD                        | Desktop     | [8c8275099b](https://linux-hardware.org/?probe=8c8275099b) | Jun 16, 2022 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [c1efcc5411](https://linux-hardware.org/?probe=c1efcc5411) | Jun 16, 2022 |
| Samsung       | Lumpy                       | Notebook    | [50dad22fb3](https://linux-hardware.org/?probe=50dad22fb3) | Jun 15, 2022 |
| ASUSTek       | GR8                         | Notebook    | [3cdc341eda](https://linux-hardware.org/?probe=3cdc341eda) | Jun 15, 2022 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [47f52294bb](https://linux-hardware.org/?probe=47f52294bb) | Jun 14, 2022 |
| Samsung       | Lumpy                       | Notebook    | [4137bf9757](https://linux-hardware.org/?probe=4137bf9757) | Jun 14, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [5b8ae292bf](https://linux-hardware.org/?probe=5b8ae292bf) | Jun 14, 2022 |
| Acer          | TravelMate 5760             | Notebook    | [90e189c067](https://linux-hardware.org/?probe=90e189c067) | Jun 13, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [83cac56441](https://linux-hardware.org/?probe=83cac56441) | Jun 13, 2022 |
| HP            | ProBook 4540s               | Notebook    | [6688afd4f5](https://linux-hardware.org/?probe=6688afd4f5) | Jun 11, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [9840a70112](https://linux-hardware.org/?probe=9840a70112) | Jun 11, 2022 |
| ASUSTek       | SABERTOOTH X58              | Desktop     | [4cc4a7c1b3](https://linux-hardware.org/?probe=4cc4a7c1b3) | Jun 11, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [0ec841e188](https://linux-hardware.org/?probe=0ec841e188) | Jun 11, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [5768dfe23f](https://linux-hardware.org/?probe=5768dfe23f) | Jun 11, 2022 |
| HP            | 2B43                        | Desktop     | [6f36772b0c](https://linux-hardware.org/?probe=6f36772b0c) | Jun 10, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [c76f63fb68](https://linux-hardware.org/?probe=c76f63fb68) | Jun 10, 2022 |
| HP            | ProBook 4540s               | Notebook    | [d0a6dcaa92](https://linux-hardware.org/?probe=d0a6dcaa92) | Jun 09, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [224023dfd2](https://linux-hardware.org/?probe=224023dfd2) | Jun 08, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [9756188040](https://linux-hardware.org/?probe=9756188040) | Jun 07, 2022 |
| HP            | Notebook                    | Notebook    | [f07183fab5](https://linux-hardware.org/?probe=f07183fab5) | Jun 06, 2022 |
| Toshiba       | Satellite T130              | Notebook    | [b5ba2dac2a](https://linux-hardware.org/?probe=b5ba2dac2a) | Jun 06, 2022 |
| Toshiba       | Satellite T130              | Notebook    | [3fe154a2ce](https://linux-hardware.org/?probe=3fe154a2ce) | Jun 06, 2022 |
| MSI           | MPG X570S CARBON MAX WIF... | Desktop     | [0d57c069a8](https://linux-hardware.org/?probe=0d57c069a8) | Jun 05, 2022 |
| HP            | ProBook 4540s               | Notebook    | [b74c4304e9](https://linux-hardware.org/?probe=b74c4304e9) | Jun 05, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN 2625... | Desktop     | [16f3fff6ad](https://linux-hardware.org/?probe=16f3fff6ad) | Jun 05, 2022 |
| Dell          | 0T7D40 A01                  | Desktop     | [812b41fe55](https://linux-hardware.org/?probe=812b41fe55) | Jun 04, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN 2625... | Desktop     | [b3d970d061](https://linux-hardware.org/?probe=b3d970d061) | Jun 04, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [9de74ba486](https://linux-hardware.org/?probe=9de74ba486) | Jun 04, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [eb704f99ee](https://linux-hardware.org/?probe=eb704f99ee) | Jun 04, 2022 |
| MSI           | B85I                        | Desktop     | [5f29683d93](https://linux-hardware.org/?probe=5f29683d93) | Jun 03, 2022 |
| Apple         | MacBookAir4,2               | Notebook    | [86902cb11f](https://linux-hardware.org/?probe=86902cb11f) | Jun 02, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [9f4aa60f60](https://linux-hardware.org/?probe=9f4aa60f60) | Jun 02, 2022 |
| HP            | ProBook 4540s               | Notebook    | [da53c77e1a](https://linux-hardware.org/?probe=da53c77e1a) | Jun 02, 2022 |
| Samsung       | 300E5M/300E5L               | Notebook    | [baa12d722c](https://linux-hardware.org/?probe=baa12d722c) | Jun 01, 2022 |
| ASUSTek       | P5B                         | Desktop     | [12554af571](https://linux-hardware.org/?probe=12554af571) | May 31, 2022 |
| Dell          | XPS 13 9343                 | Notebook    | [5881b6ea1b](https://linux-hardware.org/?probe=5881b6ea1b) | May 28, 2022 |
| Lenovo        | ThinkPad T400 6474ES3       | Notebook    | [cf8b67714d](https://linux-hardware.org/?probe=cf8b67714d) | May 27, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [6cc36ec0ae](https://linux-hardware.org/?probe=6cc36ec0ae) | May 27, 2022 |
| MSI           | MPG X570S CARBON MAX WIF... | Desktop     | [a4f2a9b24b](https://linux-hardware.org/?probe=a4f2a9b24b) | May 27, 2022 |
| MSI           | MPG X570S CARBON MAX WIF... | Desktop     | [3143793e8f](https://linux-hardware.org/?probe=3143793e8f) | May 27, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [50f70bc9af](https://linux-hardware.org/?probe=50f70bc9af) | May 27, 2022 |
| Intel         | NUC6i7KYB H90766-405        | Mini pc     | [fc581d0fb4](https://linux-hardware.org/?probe=fc581d0fb4) | May 26, 2022 |
| Intel         | NUC8BEB J72692-303          | Mini pc     | [94796b9e96](https://linux-hardware.org/?probe=94796b9e96) | May 26, 2022 |
| ASUSTek       | X550CA                      | Notebook    | [6789d8dad5](https://linux-hardware.org/?probe=6789d8dad5) | May 26, 2022 |
| AMI           | Intel                       | Notebook    | [ee3b1abf63](https://linux-hardware.org/?probe=ee3b1abf63) | May 25, 2022 |
| ASUSTek       | P5KPL-VM/S                  | Desktop     | [66223d6ef0](https://linux-hardware.org/?probe=66223d6ef0) | May 25, 2022 |
| ASUSTek       | P5KPL-VM/S                  | Desktop     | [d44e9d6290](https://linux-hardware.org/?probe=d44e9d6290) | May 25, 2022 |
| ASUSTek       | P8H61                       | Desktop     | [5514e95c95](https://linux-hardware.org/?probe=5514e95c95) | May 24, 2022 |
| ASUSTek       | P8H61                       | Desktop     | [873dd31f8e](https://linux-hardware.org/?probe=873dd31f8e) | May 23, 2022 |
| Acer          | Swift SF114-32              | Notebook    | [601f82b2dd](https://linux-hardware.org/?probe=601f82b2dd) | May 23, 2022 |
| MSI           | H97M-P35                    | Desktop     | [2b5866b09d](https://linux-hardware.org/?probe=2b5866b09d) | May 23, 2022 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | Desktop     | [2e27b6fac9](https://linux-hardware.org/?probe=2e27b6fac9) | May 23, 2022 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [8cd4fba0ca](https://linux-hardware.org/?probe=8cd4fba0ca) | May 22, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [27f751618e](https://linux-hardware.org/?probe=27f751618e) | May 22, 2022 |
| HP            | ProBook 6550b               | Notebook    | [5a80f0ac5d](https://linux-hardware.org/?probe=5a80f0ac5d) | May 21, 2022 |
| Toshiba       | PORTEGE Z830                | Notebook    | [9a4ebfe8cf](https://linux-hardware.org/?probe=9a4ebfe8cf) | May 21, 2022 |
| Biostar       | GF8200C M2+                 | Desktop     | [b80588cbea](https://linux-hardware.org/?probe=b80588cbea) | May 21, 2022 |
| AMI           | Intel                       | Notebook    | [6c571e79d0](https://linux-hardware.org/?probe=6c571e79d0) | May 21, 2022 |
| eMachines     | E525                        | Notebook    | [ca296b06c9](https://linux-hardware.org/?probe=ca296b06c9) | May 21, 2022 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [6f6a104d35](https://linux-hardware.org/?probe=6f6a104d35) | May 21, 2022 |
| Toshiba       | PORTEGE Z830                | Notebook    | [8d4eb653b6](https://linux-hardware.org/?probe=8d4eb653b6) | May 19, 2022 |
| MSI           | B85I                        | Desktop     | [c822196290](https://linux-hardware.org/?probe=c822196290) | May 18, 2022 |
| Sony          | VPCEB23FM                   | Notebook    | [4d73e73cf8](https://linux-hardware.org/?probe=4d73e73cf8) | May 17, 2022 |
| Sony          | VPCEB23FM                   | Notebook    | [07d2cadefb](https://linux-hardware.org/?probe=07d2cadefb) | May 17, 2022 |
| Samsung       | Lumpy                       | Notebook    | [84a78226dd](https://linux-hardware.org/?probe=84a78226dd) | May 16, 2022 |
| HP            | ENVY 14                     | Notebook    | [9fe635b800](https://linux-hardware.org/?probe=9fe635b800) | May 15, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [4d00452dcb](https://linux-hardware.org/?probe=4d00452dcb) | May 15, 2022 |
| ASUSTek       | K55A                        | Notebook    | [3391d004a7](https://linux-hardware.org/?probe=3391d004a7) | May 15, 2022 |
| HP            | ENVY x360 Convertible       | Convertible | [4521ae6617](https://linux-hardware.org/?probe=4521ae6617) | May 14, 2022 |
| HP            | ENVY x360 Convertible       | Convertible | [513d1e2c73](https://linux-hardware.org/?probe=513d1e2c73) | May 14, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [c0e150d349](https://linux-hardware.org/?probe=c0e150d349) | May 13, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [919200b122](https://linux-hardware.org/?probe=919200b122) | May 13, 2022 |
| ASUSTek       | UX310UQK                    | Notebook    | [1af1efeb46](https://linux-hardware.org/?probe=1af1efeb46) | May 11, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [d5df500fa3](https://linux-hardware.org/?probe=d5df500fa3) | May 10, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [1b52e22774](https://linux-hardware.org/?probe=1b52e22774) | May 10, 2022 |
| HP            | ProBook 4510s               | Notebook    | [1464ea43d3](https://linux-hardware.org/?probe=1464ea43d3) | May 09, 2022 |
| ASUSTek       | SABERTOOTH X58              | Desktop     | [c276639676](https://linux-hardware.org/?probe=c276639676) | May 08, 2022 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | Notebook    | [b726ded078](https://linux-hardware.org/?probe=b726ded078) | May 08, 2022 |
| HP            | ZBook 15                    | Notebook    | [bd8e2ed626](https://linux-hardware.org/?probe=bd8e2ed626) | May 07, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [2eb968b190](https://linux-hardware.org/?probe=2eb968b190) | May 07, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [753c7be679](https://linux-hardware.org/?probe=753c7be679) | May 05, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [d7223d4b03](https://linux-hardware.org/?probe=d7223d4b03) | May 05, 2022 |
| ASRock        | X570 Extreme4               | Desktop     | [98e5f20999](https://linux-hardware.org/?probe=98e5f20999) | May 04, 2022 |
| eMachines     | E525                        | Notebook    | [dfc36c2ea0](https://linux-hardware.org/?probe=dfc36c2ea0) | May 04, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [0295d9e820](https://linux-hardware.org/?probe=0295d9e820) | May 04, 2022 |
| Gigabyte      | GA-880GMA-UD2H              | Desktop     | [09d9f58ee7](https://linux-hardware.org/?probe=09d9f58ee7) | May 02, 2022 |
| Dell          | Inspiron 7720               | Notebook    | [a2d8358964](https://linux-hardware.org/?probe=a2d8358964) | May 02, 2022 |
| HP            | Pavilion 17                 | Notebook    | [3958b61eff](https://linux-hardware.org/?probe=3958b61eff) | May 02, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [271a0aaed2](https://linux-hardware.org/?probe=271a0aaed2) | May 01, 2022 |
| ASUSTek       | X202E                       | Notebook    | [37ad2923f5](https://linux-hardware.org/?probe=37ad2923f5) | May 01, 2022 |
| HP            | 0B48h                       | Desktop     | [4c6e5824f2](https://linux-hardware.org/?probe=4c6e5824f2) | Apr 30, 2022 |
| Acer          | Aspire E5-411G              | Notebook    | [0629e76746](https://linux-hardware.org/?probe=0629e76746) | Apr 30, 2022 |
| Avell High... | B.ON                        | Notebook    | [eb3d4d0f78](https://linux-hardware.org/?probe=eb3d4d0f78) | Apr 29, 2022 |
| ASUSTek       | P8Z77-V                     | Desktop     | [b3506ef75d](https://linux-hardware.org/?probe=b3506ef75d) | Apr 29, 2022 |
| HP            | Pavilion 17                 | Notebook    | [6de5e5677f](https://linux-hardware.org/?probe=6de5e5677f) | Apr 29, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [c12f5ae663](https://linux-hardware.org/?probe=c12f5ae663) | Apr 28, 2022 |
| Dell          | 0J3C2F A00                  | Desktop     | [464c70eb8d](https://linux-hardware.org/?probe=464c70eb8d) | Apr 27, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [74c6e22c86](https://linux-hardware.org/?probe=74c6e22c86) | Apr 27, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [1f10d820f8](https://linux-hardware.org/?probe=1f10d820f8) | Apr 27, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [dfadead480](https://linux-hardware.org/?probe=dfadead480) | Apr 27, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [06a00cfce7](https://linux-hardware.org/?probe=06a00cfce7) | Apr 25, 2022 |
| Dell          | 05R2TK A01                  | All in one  | [317f2966c3](https://linux-hardware.org/?probe=317f2966c3) | Apr 25, 2022 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | Desktop     | [dbaaf867f6](https://linux-hardware.org/?probe=dbaaf867f6) | Apr 25, 2022 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [1b0a41c232](https://linux-hardware.org/?probe=1b0a41c232) | Apr 25, 2022 |
| Lenovo        | ThinkPad T420 41786VU       | Notebook    | [e2b4c2327b](https://linux-hardware.org/?probe=e2b4c2327b) | Apr 25, 2022 |
| AZW           | GTi                         | Desktop     | [e2d4a0da2e](https://linux-hardware.org/?probe=e2d4a0da2e) | Apr 23, 2022 |
| AZW           | GTi                         | Desktop     | [cde74551bf](https://linux-hardware.org/?probe=cde74551bf) | Apr 23, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [6162231453](https://linux-hardware.org/?probe=6162231453) | Apr 23, 2022 |
| Dell          | Latitude 3120               | Notebook    | [78f0703e75](https://linux-hardware.org/?probe=78f0703e75) | Apr 23, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [9146df4426](https://linux-hardware.org/?probe=9146df4426) | Apr 23, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [2f497982cd](https://linux-hardware.org/?probe=2f497982cd) | Apr 22, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [e7f7e1188e](https://linux-hardware.org/?probe=e7f7e1188e) | Apr 21, 2022 |
| HP            | Pavilion g6                 | Notebook    | [63f6b73d50](https://linux-hardware.org/?probe=63f6b73d50) | Apr 21, 2022 |
| ECS           | H61H2-MV                    | Desktop     | [939f87564f](https://linux-hardware.org/?probe=939f87564f) | Apr 21, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [b720cd5fc5](https://linux-hardware.org/?probe=b720cd5fc5) | Apr 20, 2022 |
| Samsung       | 950XDB/951XDB/950XDY        | Notebook    | [336a67fbee](https://linux-hardware.org/?probe=336a67fbee) | Apr 19, 2022 |
| MSI           | X99A SLI PLUS               | Desktop     | [0b935aadb3](https://linux-hardware.org/?probe=0b935aadb3) | Apr 19, 2022 |
| Inventec      | D CLASS A02                 | Desktop     | [d00d37285b](https://linux-hardware.org/?probe=d00d37285b) | Apr 19, 2022 |
| ASUSTek       | ZenBook UX325SA_UM325SA     | Notebook    | [d3d2e2fe8a](https://linux-hardware.org/?probe=d3d2e2fe8a) | Apr 18, 2022 |
| HP            | ProBook 6440b               | Notebook    | [54a85fc99d](https://linux-hardware.org/?probe=54a85fc99d) | Apr 18, 2022 |
| ASRock        | Z490 Pro4                   | Desktop     | [67071d11a1](https://linux-hardware.org/?probe=67071d11a1) | Apr 18, 2022 |
| Dell          | 0KV62T A01                  | Desktop     | [0c6e50ed20](https://linux-hardware.org/?probe=0c6e50ed20) | Apr 17, 2022 |
| Dell          | 0KV62T A01                  | Desktop     | [7bed7782c4](https://linux-hardware.org/?probe=7bed7782c4) | Apr 17, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [e28ee0bd42](https://linux-hardware.org/?probe=e28ee0bd42) | Apr 16, 2022 |
| HP            | 1494                        | Desktop     | [6ad3ca1745](https://linux-hardware.org/?probe=6ad3ca1745) | Apr 16, 2022 |
| Gigabyte      | H61M-D2H-USB3               | Desktop     | [016243a675](https://linux-hardware.org/?probe=016243a675) | Apr 15, 2022 |
| Lenovo        | ThinkPad X201 Tablet 311... | Notebook    | [e3ab162648](https://linux-hardware.org/?probe=e3ab162648) | Apr 15, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [0d7edf2aa9](https://linux-hardware.org/?probe=0d7edf2aa9) | Apr 15, 2022 |
| Lenovo        | ThinkPad W541 20EGS0UB03    | Notebook    | [f566cb7f4c](https://linux-hardware.org/?probe=f566cb7f4c) | Apr 14, 2022 |
| Fujitsu       | D3531-A1 S26361-D3531-A1    | Desktop     | [46dd533a5e](https://linux-hardware.org/?probe=46dd533a5e) | Apr 14, 2022 |
| Dell          | Latitude 3550               | Notebook    | [6947850074](https://linux-hardware.org/?probe=6947850074) | Apr 14, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [c6dd82e724](https://linux-hardware.org/?probe=c6dd82e724) | Apr 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [dff6de5032](https://linux-hardware.org/?probe=dff6de5032) | Apr 14, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [e525a26ca8](https://linux-hardware.org/?probe=e525a26ca8) | Apr 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [6a2c5f12fd](https://linux-hardware.org/?probe=6a2c5f12fd) | Apr 13, 2022 |
| Dell          | 0K240Y A01                  | Desktop     | [76d4fbf0a6](https://linux-hardware.org/?probe=76d4fbf0a6) | Apr 13, 2022 |
| HP            | ProBook 440 G7              | Notebook    | [7c6efad935](https://linux-hardware.org/?probe=7c6efad935) | Apr 13, 2022 |
| Panasonic     | CF-31SBLJGDM                | Notebook    | [60a1068658](https://linux-hardware.org/?probe=60a1068658) | Apr 13, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [3440d2dd8c](https://linux-hardware.org/?probe=3440d2dd8c) | Apr 12, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [07bdcd6978](https://linux-hardware.org/?probe=07bdcd6978) | Apr 12, 2022 |
| MSI           | Prestige 15 A11UC           | Notebook    | [20517e7efc](https://linux-hardware.org/?probe=20517e7efc) | Apr 11, 2022 |
| MSI           | Prestige 15 A11UC           | Notebook    | [3f8b7b11a5](https://linux-hardware.org/?probe=3f8b7b11a5) | Apr 11, 2022 |
| Lenovo        | 3178 SDK0J40700 WIN 3258... | Desktop     | [637023ab6d](https://linux-hardware.org/?probe=637023ab6d) | Apr 11, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [21767e12e4](https://linux-hardware.org/?probe=21767e12e4) | Apr 11, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [379db407c7](https://linux-hardware.org/?probe=379db407c7) | Apr 10, 2022 |
| Pegatron      | IPMH61P1                    | Desktop     | [1adcf74c4f](https://linux-hardware.org/?probe=1adcf74c4f) | Apr 10, 2022 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [e367ac99ce](https://linux-hardware.org/?probe=e367ac99ce) | Apr 10, 2022 |
| HP            | Pavilion 13 x360 PC         | Notebook    | [3abf9847e4](https://linux-hardware.org/?probe=3abf9847e4) | Apr 10, 2022 |
| ASUSTek       | N56DY                       | Notebook    | [aff377f6ed](https://linux-hardware.org/?probe=aff377f6ed) | Apr 09, 2022 |
| Lenovo        | IdeaPad-510-15IKB 80SV      | Notebook    | [840239190e](https://linux-hardware.org/?probe=840239190e) | Apr 09, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [84c694e881](https://linux-hardware.org/?probe=84c694e881) | Apr 08, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [1c357065cb](https://linux-hardware.org/?probe=1c357065cb) | Apr 07, 2022 |
| ASRock        | C226 WS                     | Desktop     | [7c11c1ec43](https://linux-hardware.org/?probe=7c11c1ec43) | Apr 07, 2022 |
| ASUSTek       | STRIKER II FORMULA          | Desktop     | [5dfea21930](https://linux-hardware.org/?probe=5dfea21930) | Apr 07, 2022 |
| ASUSTek       | STRIKER II FORMULA          | Desktop     | [040990b3fc](https://linux-hardware.org/?probe=040990b3fc) | Apr 07, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [0626d13541](https://linux-hardware.org/?probe=0626d13541) | Apr 07, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [0bc837ffef](https://linux-hardware.org/?probe=0bc837ffef) | Apr 06, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [fd62bf7f91](https://linux-hardware.org/?probe=fd62bf7f91) | Apr 05, 2022 |
| Dell          | Latitude 5410               | Notebook    | [9d03bb6cad](https://linux-hardware.org/?probe=9d03bb6cad) | Apr 05, 2022 |
| HP            | Stream Laptop 14-ax1xxx     | Notebook    | [a25b973df6](https://linux-hardware.org/?probe=a25b973df6) | Apr 05, 2022 |
| HP            | Stream Laptop 14-ax1xxx     | Notebook    | [4228c17983](https://linux-hardware.org/?probe=4228c17983) | Apr 05, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [656e7d1b73](https://linux-hardware.org/?probe=656e7d1b73) | Apr 04, 2022 |
| Lenovo        | ThinkPad X260 20F5S84400    | Notebook    | [69e1c25b4c](https://linux-hardware.org/?probe=69e1c25b4c) | Apr 03, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [d1c62a1f93](https://linux-hardware.org/?probe=d1c62a1f93) | Apr 03, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [7419ad6a76](https://linux-hardware.org/?probe=7419ad6a76) | Apr 02, 2022 |
| HP            | Notebook                    | Notebook    | [f46a05a044](https://linux-hardware.org/?probe=f46a05a044) | Apr 02, 2022 |
| Lenovo        | ThinkPad X201 Tablet 311... | Notebook    | [7f48dd5612](https://linux-hardware.org/?probe=7f48dd5612) | Apr 02, 2022 |
| Dell          | Inspiron 5481               | Convertible | [e364cee660](https://linux-hardware.org/?probe=e364cee660) | Apr 02, 2022 |
| Lenovo        | ThinkPad T410s 2912BR7      | Notebook    | [04098ae404](https://linux-hardware.org/?probe=04098ae404) | Apr 02, 2022 |
| Apple         | MacBookAir4,2               | Notebook    | [7fc2cd808d](https://linux-hardware.org/?probe=7fc2cd808d) | Apr 02, 2022 |
| Dell          | Vostro A860                 | Notebook    | [15ce9e1f63](https://linux-hardware.org/?probe=15ce9e1f63) | Apr 01, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [9375dd090a](https://linux-hardware.org/?probe=9375dd090a) | Apr 01, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [ab016f94d5](https://linux-hardware.org/?probe=ab016f94d5) | Apr 01, 2022 |
| HP            | EliteBook 8730w             | Notebook    | [caade8e7ff](https://linux-hardware.org/?probe=caade8e7ff) | Mar 31, 2022 |
| ASUSTek       | UL80VT                      | Notebook    | [bd7c5c01e6](https://linux-hardware.org/?probe=bd7c5c01e6) | Mar 31, 2022 |
| Lenovo        | ThinkCentre M58 6258D3G     | Desktop     | [b67f1750b8](https://linux-hardware.org/?probe=b67f1750b8) | Mar 31, 2022 |
| Lenovo        | ThinkCentre M58 6258D3G     | Desktop     | [1cd22c83f1](https://linux-hardware.org/?probe=1cd22c83f1) | Mar 31, 2022 |
| MSI           | H97 GAMING 3                | Desktop     | [97f38615e3](https://linux-hardware.org/?probe=97f38615e3) | Mar 31, 2022 |
| MSI           | MEG X570 ACE                | Desktop     | [55572b8a7e](https://linux-hardware.org/?probe=55572b8a7e) | Mar 31, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [513f01a83f](https://linux-hardware.org/?probe=513f01a83f) | Mar 30, 2022 |
| Acer          | Aspire ES1-531              | Notebook    | [e617f1e49b](https://linux-hardware.org/?probe=e617f1e49b) | Mar 30, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [5eb56f360e](https://linux-hardware.org/?probe=5eb56f360e) | Mar 29, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [01f1ca7f9d](https://linux-hardware.org/?probe=01f1ca7f9d) | Mar 29, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d299b01a23](https://linux-hardware.org/?probe=d299b01a23) | Mar 29, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [1b9e12b8fb](https://linux-hardware.org/?probe=1b9e12b8fb) | Mar 29, 2022 |
| HP            | 18E7                        | Desktop     | [ead4fcc358](https://linux-hardware.org/?probe=ead4fcc358) | Mar 29, 2022 |
| ASUSTek       | Rampage IV GENE             | Desktop     | [c067a4d0e7](https://linux-hardware.org/?probe=c067a4d0e7) | Mar 29, 2022 |
| Acer          | Aspire ES1-520              | Notebook    | [95df1e3190](https://linux-hardware.org/?probe=95df1e3190) | Mar 28, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [677a8dfae3](https://linux-hardware.org/?probe=677a8dfae3) | Mar 28, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [2f7a9a8ab0](https://linux-hardware.org/?probe=2f7a9a8ab0) | Mar 28, 2022 |
| LG Electro... | 17Z95P-K.AAE8U1             | Notebook    | [0a3f06a9e5](https://linux-hardware.org/?probe=0a3f06a9e5) | Mar 28, 2022 |
| Dell          | Latitude 5520               | Notebook    | [ca6e0db25d](https://linux-hardware.org/?probe=ca6e0db25d) | Mar 27, 2022 |
| LG Electro... | P1-JSUVT                    | Notebook    | [b0e2f9e53c](https://linux-hardware.org/?probe=b0e2f9e53c) | Mar 27, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [ac055e5e8a](https://linux-hardware.org/?probe=ac055e5e8a) | Mar 27, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [0521ab3bd7](https://linux-hardware.org/?probe=0521ab3bd7) | Mar 27, 2022 |
| Sony          | VPCCA4E1E                   | Notebook    | [95fc0956c8](https://linux-hardware.org/?probe=95fc0956c8) | Mar 27, 2022 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [9e39c749a1](https://linux-hardware.org/?probe=9e39c749a1) | Mar 27, 2022 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [1c30077d94](https://linux-hardware.org/?probe=1c30077d94) | Mar 26, 2022 |
| Toshiba       | Satellite C70D-A            | Notebook    | [c8b872d005](https://linux-hardware.org/?probe=c8b872d005) | Mar 26, 2022 |
| Dell          | 0C522T A00                  | Desktop     | [33ae998152](https://linux-hardware.org/?probe=33ae998152) | Mar 26, 2022 |
| Dell          | 0C522T A00                  | Desktop     | [90242bb090](https://linux-hardware.org/?probe=90242bb090) | Mar 26, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [7ca2f5d5cb](https://linux-hardware.org/?probe=7ca2f5d5cb) | Mar 26, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [7577679057](https://linux-hardware.org/?probe=7577679057) | Mar 25, 2022 |
| Toshiba       | Satellite L50D-C            | Notebook    | [2782b13510](https://linux-hardware.org/?probe=2782b13510) | Mar 25, 2022 |
| Toshiba       | Satellite L50D-C            | Notebook    | [a0c9b5a952](https://linux-hardware.org/?probe=a0c9b5a952) | Mar 25, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [744a69ec7d](https://linux-hardware.org/?probe=744a69ec7d) | Mar 25, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [a237859a86](https://linux-hardware.org/?probe=a237859a86) | Mar 24, 2022 |
| Intel         | X79Turbo V1.x               | Desktop     | [18b126a753](https://linux-hardware.org/?probe=18b126a753) | Mar 24, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [1535349482](https://linux-hardware.org/?probe=1535349482) | Mar 24, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [552f06718c](https://linux-hardware.org/?probe=552f06718c) | Mar 23, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [dd34f9d506](https://linux-hardware.org/?probe=dd34f9d506) | Mar 23, 2022 |
| AMI           | Cherry Trail CR             | Desktop     | [bbea34ce64](https://linux-hardware.org/?probe=bbea34ce64) | Mar 22, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [552d30ae49](https://linux-hardware.org/?probe=552d30ae49) | Mar 22, 2022 |
| Sony          | SVP1321B4E                  | Notebook    | [b539c23011](https://linux-hardware.org/?probe=b539c23011) | Mar 21, 2022 |
| Acer          | Swift SF314-52              | Notebook    | [2d8ab46eed](https://linux-hardware.org/?probe=2d8ab46eed) | Mar 21, 2022 |
| Acer          | Swift SF314-52              | Notebook    | [b1bdc8c7d4](https://linux-hardware.org/?probe=b1bdc8c7d4) | Mar 21, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [2b39b0fda2](https://linux-hardware.org/?probe=2b39b0fda2) | Mar 21, 2022 |
| LG Electro... | A410-G.BC51P1               | Notebook    | [9054ee5a3d](https://linux-hardware.org/?probe=9054ee5a3d) | Mar 20, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [78df63a35f](https://linux-hardware.org/?probe=78df63a35f) | Mar 20, 2022 |
| AMI           | Cherry Trail CR             | Desktop     | [bc5a34ef7e](https://linux-hardware.org/?probe=bc5a34ef7e) | Mar 20, 2022 |
| Dell          | Vostro 15 3515              | Notebook    | [6806f47a62](https://linux-hardware.org/?probe=6806f47a62) | Mar 19, 2022 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [1268effe7d](https://linux-hardware.org/?probe=1268effe7d) | Mar 17, 2022 |
| ASUSTek       | Rampage IV GENE             | Desktop     | [7f5053b061](https://linux-hardware.org/?probe=7f5053b061) | Mar 16, 2022 |
| Apple         | MacBookAir7,1               | Notebook    | [7b2fa4b8e8](https://linux-hardware.org/?probe=7b2fa4b8e8) | Mar 16, 2022 |
| ASUSTek       | Rampage IV GENE             | Desktop     | [7ff55a3ca6](https://linux-hardware.org/?probe=7ff55a3ca6) | Mar 16, 2022 |
| Dell          | Inspiron 5593               | Notebook    | [f4d49b97ec](https://linux-hardware.org/?probe=f4d49b97ec) | Mar 15, 2022 |
| Dell          | Latitude E6220              | Notebook    | [e2c9477eb3](https://linux-hardware.org/?probe=e2c9477eb3) | Mar 15, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [a10cf12536](https://linux-hardware.org/?probe=a10cf12536) | Mar 15, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [eda8848760](https://linux-hardware.org/?probe=eda8848760) | Mar 15, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [c95c5598af](https://linux-hardware.org/?probe=c95c5598af) | Mar 15, 2022 |
| AOpen         | D1009 A1A4                  | Desktop     | [a7375d4581](https://linux-hardware.org/?probe=a7375d4581) | Mar 13, 2022 |
| Dell          | Latitude 3550               | Notebook    | [947e147577](https://linux-hardware.org/?probe=947e147577) | Mar 13, 2022 |
| Dell          | Latitude 3550               | Notebook    | [afffe18667](https://linux-hardware.org/?probe=afffe18667) | Mar 13, 2022 |
| Acer          | Aspire A315-21G             | Notebook    | [4e85fcd677](https://linux-hardware.org/?probe=4e85fcd677) | Mar 13, 2022 |
| Apple         | Mac-F2218FC8                | All in one  | [9eb7577acd](https://linux-hardware.org/?probe=9eb7577acd) | Mar 12, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [7f9721781e](https://linux-hardware.org/?probe=7f9721781e) | Mar 12, 2022 |
| Lenovo        | ThinkPad T420 4236JY2       | Notebook    | [bc5d95b759](https://linux-hardware.org/?probe=bc5d95b759) | Mar 12, 2022 |
| MSI           | B85I                        | Desktop     | [d134c8451b](https://linux-hardware.org/?probe=d134c8451b) | Mar 12, 2022 |
| Teclast       | F15S                        | Notebook    | [a92a5510ef](https://linux-hardware.org/?probe=a92a5510ef) | Mar 11, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [12459fc7ea](https://linux-hardware.org/?probe=12459fc7ea) | Mar 11, 2022 |
| ASUSTek       | X200CA                      | Notebook    | [85c103c654](https://linux-hardware.org/?probe=85c103c654) | Mar 10, 2022 |
| ASUSTek       | X200CA                      | Notebook    | [25518274da](https://linux-hardware.org/?probe=25518274da) | Mar 10, 2022 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | Desktop     | [a64818ccea](https://linux-hardware.org/?probe=a64818ccea) | Mar 10, 2022 |
| Biostar       | N68S3B                      | Desktop     | [aa1e6a4c82](https://linux-hardware.org/?probe=aa1e6a4c82) | Mar 10, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [b950d195ce](https://linux-hardware.org/?probe=b950d195ce) | Mar 10, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [1064e67665](https://linux-hardware.org/?probe=1064e67665) | Mar 10, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [83dc415e28](https://linux-hardware.org/?probe=83dc415e28) | Mar 09, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [e6a6f71bb5](https://linux-hardware.org/?probe=e6a6f71bb5) | Mar 09, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | Notebook    | [ee3693d6a7](https://linux-hardware.org/?probe=ee3693d6a7) | Mar 09, 2022 |
| Dell          | 0HMX8D A01                  | Desktop     | [cfff92df80](https://linux-hardware.org/?probe=cfff92df80) | Mar 09, 2022 |
| ASUSTek       | M11AD                       | Desktop     | [8bb5baaa5a](https://linux-hardware.org/?probe=8bb5baaa5a) | Mar 09, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [fc064cce68](https://linux-hardware.org/?probe=fc064cce68) | Mar 09, 2022 |
| Microsoft     | Surface Laptop 3            | Tablet      | [d55f23484e](https://linux-hardware.org/?probe=d55f23484e) | Mar 09, 2022 |
| MSI           | Modern 14 B10MW             | Notebook    | [661d068b83](https://linux-hardware.org/?probe=661d068b83) | Mar 08, 2022 |
| Biostar       | H61MLV2                     | Desktop     | [d5c330bad8](https://linux-hardware.org/?probe=d5c330bad8) | Mar 08, 2022 |
| HP            | 2ADC                        | Desktop     | [ed0714a64a](https://linux-hardware.org/?probe=ed0714a64a) | Mar 07, 2022 |
| MSI           | B85I                        | Desktop     | [39926596b7](https://linux-hardware.org/?probe=39926596b7) | Mar 07, 2022 |
| Lenovo        | ThinkPad L470 20J4002FMX    | Notebook    | [c3e1baf45a](https://linux-hardware.org/?probe=c3e1baf45a) | Mar 06, 2022 |
| Lenovo        | ThinkPad T420 4236JY2       | Notebook    | [caa5c3eef1](https://linux-hardware.org/?probe=caa5c3eef1) | Mar 06, 2022 |
| Dell          | 0PU052                      | Desktop     | [766b0e4665](https://linux-hardware.org/?probe=766b0e4665) | Mar 06, 2022 |
| Dell          | 0PU052                      | Desktop     | [a8e19bd112](https://linux-hardware.org/?probe=a8e19bd112) | Mar 06, 2022 |
| Lenovo        | ThinkPad X230 2325ND9       | Notebook    | [02818352e0](https://linux-hardware.org/?probe=02818352e0) | Mar 06, 2022 |
| iOTA          | IOTA2320                    | Notebook    | [6cf7733a53](https://linux-hardware.org/?probe=6cf7733a53) | Mar 06, 2022 |
| Lenovo        | ThinkPad X230 2325ND9       | Notebook    | [24a601d3aa](https://linux-hardware.org/?probe=24a601d3aa) | Mar 06, 2022 |
| Lenovo        | IdeaPad Y580                | Notebook    | [26ea7d1cff](https://linux-hardware.org/?probe=26ea7d1cff) | Mar 06, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [7e967f4daa](https://linux-hardware.org/?probe=7e967f4daa) | Mar 06, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [db5f524190](https://linux-hardware.org/?probe=db5f524190) | Mar 06, 2022 |
| HP            | 1589                        | Desktop     | [88876808e9](https://linux-hardware.org/?probe=88876808e9) | Mar 05, 2022 |
| Acer          | Nitro AN517-52              | Notebook    | [4576110ce4](https://linux-hardware.org/?probe=4576110ce4) | Mar 05, 2022 |
| HP            | 802E                        | Desktop     | [14c73a40e0](https://linux-hardware.org/?probe=14c73a40e0) | Mar 05, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [a2f1d82d9c](https://linux-hardware.org/?probe=a2f1d82d9c) | Mar 05, 2022 |
| ASRock        | FM2A58M-DG3+                | Desktop     | [0b7875b1b5](https://linux-hardware.org/?probe=0b7875b1b5) | Mar 05, 2022 |
| Acer          | Aspire A315-42G             | Notebook    | [d08f8cbc35](https://linux-hardware.org/?probe=d08f8cbc35) | Mar 05, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [4fc1001606](https://linux-hardware.org/?probe=4fc1001606) | Mar 02, 2022 |
| Lenovo        | ThinkPad T400s 2808D9G      | Notebook    | [6a5d0584bd](https://linux-hardware.org/?probe=6a5d0584bd) | Mar 02, 2022 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [9cfd9c7142](https://linux-hardware.org/?probe=9cfd9c7142) | Mar 02, 2022 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [a93699018b](https://linux-hardware.org/?probe=a93699018b) | Mar 02, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [a73f7ae919](https://linux-hardware.org/?probe=a73f7ae919) | Feb 28, 2022 |
| ASUSTek       | M4N72-E                     | Desktop     | [c3fe570b4d](https://linux-hardware.org/?probe=c3fe570b4d) | Feb 28, 2022 |
| ASUSTek       | H81-PLUS                    | Desktop     | [e8956dc4ec](https://linux-hardware.org/?probe=e8956dc4ec) | Feb 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [d7b815d3d6](https://linux-hardware.org/?probe=d7b815d3d6) | Feb 27, 2022 |
| Samsung       | 870Z5E/880Z5E/680Z5E        | Notebook    | [d04715f0dc](https://linux-hardware.org/?probe=d04715f0dc) | Feb 26, 2022 |
| ASUSTek       | H81-PLUS                    | Desktop     | [9c68dfb511](https://linux-hardware.org/?probe=9c68dfb511) | Feb 26, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [a6d5cc0368](https://linux-hardware.org/?probe=a6d5cc0368) | Feb 26, 2022 |
| HP            | Laptop 17-by0xxx            | Notebook    | [745fa98d2e](https://linux-hardware.org/?probe=745fa98d2e) | Feb 26, 2022 |
| Acer          | Aspire A315-42G             | Notebook    | [75830af7ff](https://linux-hardware.org/?probe=75830af7ff) | Feb 25, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [97284dc322](https://linux-hardware.org/?probe=97284dc322) | Feb 25, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [a8b2cacac9](https://linux-hardware.org/?probe=a8b2cacac9) | Feb 25, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | Notebook    | [eeaed94df7](https://linux-hardware.org/?probe=eeaed94df7) | Feb 23, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [7ea66813f3](https://linux-hardware.org/?probe=7ea66813f3) | Feb 23, 2022 |
| Dell          | Inspiron N5050              | Notebook    | [88c13620a2](https://linux-hardware.org/?probe=88c13620a2) | Feb 23, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [7a8aaaa5a6](https://linux-hardware.org/?probe=7a8aaaa5a6) | Feb 23, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [849ceb3653](https://linux-hardware.org/?probe=849ceb3653) | Feb 23, 2022 |
| Microsoft     | Surface with Windows 8 P... | Tablet      | [1f32b0aa84](https://linux-hardware.org/?probe=1f32b0aa84) | Feb 23, 2022 |
| Microsoft     | Surface with Windows 8 P... | Tablet      | [ef94f0dd4d](https://linux-hardware.org/?probe=ef94f0dd4d) | Feb 23, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [1527f67c84](https://linux-hardware.org/?probe=1527f67c84) | Feb 23, 2022 |
| Samsung       | 500R4K/500R5H/5400RK/501... | Notebook    | [1391579931](https://linux-hardware.org/?probe=1391579931) | Feb 21, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [73b31ddab0](https://linux-hardware.org/?probe=73b31ddab0) | Feb 20, 2022 |
| ASUSTek       | GL753VE                     | Notebook    | [25f1ab36fc](https://linux-hardware.org/?probe=25f1ab36fc) | Feb 20, 2022 |
| Apple         | MacBookAir3,1               | Notebook    | [48dcaa8622](https://linux-hardware.org/?probe=48dcaa8622) | Feb 20, 2022 |
| ASUSTek       | E402SA                      | Notebook    | [b9796e46de](https://linux-hardware.org/?probe=b9796e46de) | Feb 20, 2022 |
| ASUSTek       | K75VJ                       | Notebook    | [e0c07cf9d2](https://linux-hardware.org/?probe=e0c07cf9d2) | Feb 20, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [3503d61993](https://linux-hardware.org/?probe=3503d61993) | Feb 19, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | Notebook    | [44210b95fe](https://linux-hardware.org/?probe=44210b95fe) | Feb 19, 2022 |
| Intel         | DH61BE AAG14062-210         | Desktop     | [00566bb73f](https://linux-hardware.org/?probe=00566bb73f) | Feb 19, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [da54df3fd4](https://linux-hardware.org/?probe=da54df3fd4) | Feb 19, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [05cb921db2](https://linux-hardware.org/?probe=05cb921db2) | Feb 19, 2022 |
| ASUSTek       | M11AD                       | Desktop     | [035887c4ab](https://linux-hardware.org/?probe=035887c4ab) | Feb 18, 2022 |
| MSI           | Modern 14 B10MW             | Notebook    | [beb5ff195a](https://linux-hardware.org/?probe=beb5ff195a) | Feb 18, 2022 |
| ASUSTek       | P5B                         | Desktop     | [fa4c095fd7](https://linux-hardware.org/?probe=fa4c095fd7) | Feb 17, 2022 |
| Intel         | H61                         | Desktop     | [a70c59ad0e](https://linux-hardware.org/?probe=a70c59ad0e) | Feb 17, 2022 |
| Packard Be... | EasyNote LS11HR             | Notebook    | [d8b9f8edb0](https://linux-hardware.org/?probe=d8b9f8edb0) | Feb 17, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [03dfc41744](https://linux-hardware.org/?probe=03dfc41744) | Feb 16, 2022 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [6beda6e2da](https://linux-hardware.org/?probe=6beda6e2da) | Feb 16, 2022 |
| Biostar       | A68MD PRO                   | Desktop     | [da42cc4da7](https://linux-hardware.org/?probe=da42cc4da7) | Feb 16, 2022 |
| Lenovo        | ThinkPad T470 20JNS08H00    | Notebook    | [f97643f94c](https://linux-hardware.org/?probe=f97643f94c) | Feb 16, 2022 |
| Acer          | Aspire A315-35              | Notebook    | [9986615814](https://linux-hardware.org/?probe=9986615814) | Feb 15, 2022 |
| Acer          | Swift SF314-56              | Notebook    | [a6c7102b14](https://linux-hardware.org/?probe=a6c7102b14) | Feb 14, 2022 |
| ASUSTek       | PRIME B250-PRO              | Desktop     | [be377c733e](https://linux-hardware.org/?probe=be377c733e) | Feb 14, 2022 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [825734953d](https://linux-hardware.org/?probe=825734953d) | Feb 13, 2022 |
| ASUSTek       | X540SA                      | Notebook    | [eba09c169c](https://linux-hardware.org/?probe=eba09c169c) | Feb 13, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [45c9189643](https://linux-hardware.org/?probe=45c9189643) | Feb 13, 2022 |
| ASUSTek       | E402NA                      | Notebook    | [ec217b7bd1](https://linux-hardware.org/?probe=ec217b7bd1) | Feb 13, 2022 |
| MSI           | B85I                        | Desktop     | [898dced271](https://linux-hardware.org/?probe=898dced271) | Feb 13, 2022 |
| Dell          | Precision 7720              | Notebook    | [e5c37c787f](https://linux-hardware.org/?probe=e5c37c787f) | Feb 13, 2022 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [a2a41e039c](https://linux-hardware.org/?probe=a2a41e039c) | Feb 13, 2022 |
| Google        | Lulu                        | Notebook    | [5b81b703ea](https://linux-hardware.org/?probe=5b81b703ea) | Feb 13, 2022 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [2f3941c9cb](https://linux-hardware.org/?probe=2f3941c9cb) | Feb 12, 2022 |
| Sony          | SVE15115EN                  | Notebook    | [facd08033e](https://linux-hardware.org/?probe=facd08033e) | Feb 12, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [5f4de1e2b0](https://linux-hardware.org/?probe=5f4de1e2b0) | Feb 12, 2022 |
| ASUSTek       | X550CA                      | Notebook    | [4fc3af48e2](https://linux-hardware.org/?probe=4fc3af48e2) | Feb 12, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [1aeb3957c5](https://linux-hardware.org/?probe=1aeb3957c5) | Feb 12, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [aac284c4db](https://linux-hardware.org/?probe=aac284c4db) | Feb 12, 2022 |
| Dell          | Inspiron 1764               | Notebook    | [3b22e2edbb](https://linux-hardware.org/?probe=3b22e2edbb) | Feb 11, 2022 |
| Apple         | MacBookAir7,1               | Notebook    | [39d4765770](https://linux-hardware.org/?probe=39d4765770) | Feb 11, 2022 |
| Apple         | MacBookAir4,2               | Notebook    | [113add3cba](https://linux-hardware.org/?probe=113add3cba) | Feb 10, 2022 |
| BANGHO        | Suma 1025                   | Tablet      | [585ea8c657](https://linux-hardware.org/?probe=585ea8c657) | Feb 10, 2022 |
| ASUSTek       | PRIME B360M-K               | Desktop     | [698e174402](https://linux-hardware.org/?probe=698e174402) | Feb 09, 2022 |
| Apple         | MacBookAir4,2               | Notebook    | [accb1d4232](https://linux-hardware.org/?probe=accb1d4232) | Feb 09, 2022 |
| ASUSTek       | H110M-C                     | Desktop     | [82f3d6edf9](https://linux-hardware.org/?probe=82f3d6edf9) | Feb 09, 2022 |
| Timi          | TM1613                      | Notebook    | [737c2fcb2f](https://linux-hardware.org/?probe=737c2fcb2f) | Feb 09, 2022 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [a2af859752](https://linux-hardware.org/?probe=a2af859752) | Feb 09, 2022 |
| Dell          | Inspiron 5481               | Convertible | [1f266a5183](https://linux-hardware.org/?probe=1f266a5183) | Feb 08, 2022 |
| ECS           | H55H-M                      | Desktop     | [856a42d74b](https://linux-hardware.org/?probe=856a42d74b) | Feb 07, 2022 |
| Lenovo        | ThinkPad T440p 20AN006NU... | Notebook    | [d4fccf53c8](https://linux-hardware.org/?probe=d4fccf53c8) | Feb 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [87954474ed](https://linux-hardware.org/?probe=87954474ed) | Feb 07, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [baa251b3db](https://linux-hardware.org/?probe=baa251b3db) | Feb 07, 2022 |
| Lenovo        | ThinkPad E550 20DF0040US    | Notebook    | [ca4c420e00](https://linux-hardware.org/?probe=ca4c420e00) | Feb 07, 2022 |
| Lenovo        | NO DPK                      | Desktop     | [4bb7cedbd8](https://linux-hardware.org/?probe=4bb7cedbd8) | Feb 06, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [b298d77ce8](https://linux-hardware.org/?probe=b298d77ce8) | Feb 06, 2022 |
| Timi          | TM1613                      | Notebook    | [8d16a0555c](https://linux-hardware.org/?probe=8d16a0555c) | Feb 06, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [f7500c309c](https://linux-hardware.org/?probe=f7500c309c) | Feb 06, 2022 |
| Acer          | Aspire V5-573PG             | Notebook    | [0edb115ff8](https://linux-hardware.org/?probe=0edb115ff8) | Feb 05, 2022 |
| Acer          | Aspire V5-573PG             | Notebook    | [68595aad84](https://linux-hardware.org/?probe=68595aad84) | Feb 05, 2022 |
| Lenovo        | G550 2958                   | Notebook    | [e23451d062](https://linux-hardware.org/?probe=e23451d062) | Feb 05, 2022 |
| HP            | 802E                        | Desktop     | [31e2fe159c](https://linux-hardware.org/?probe=31e2fe159c) | Feb 05, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [7b1b45a8ed](https://linux-hardware.org/?probe=7b1b45a8ed) | Feb 05, 2022 |
| HP            | 240 G4                      | Notebook    | [9e7ffa0cf2](https://linux-hardware.org/?probe=9e7ffa0cf2) | Feb 04, 2022 |
| ASUSTek       | H110M-C                     | Desktop     | [6ba127c715](https://linux-hardware.org/?probe=6ba127c715) | Feb 04, 2022 |
| ASUSTek       | P5B                         | Desktop     | [9b661f64dd](https://linux-hardware.org/?probe=9b661f64dd) | Feb 04, 2022 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [85d07f0cc8](https://linux-hardware.org/?probe=85d07f0cc8) | Feb 03, 2022 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [f3e2292b52](https://linux-hardware.org/?probe=f3e2292b52) | Feb 03, 2022 |
| Panasonic     | CF-31SBLJGDM                | Notebook    | [488b80a942](https://linux-hardware.org/?probe=488b80a942) | Feb 03, 2022 |
| Foxconn       | NETBOX nT-435/535 Ver       | Desktop     | [c7d50db62b](https://linux-hardware.org/?probe=c7d50db62b) | Feb 03, 2022 |
| Foxconn       | NETBOX nT-435/535 Ver       | Desktop     | [2ee2be7ccf](https://linux-hardware.org/?probe=2ee2be7ccf) | Feb 03, 2022 |
| HP            | 82A5                        | Mini pc     | [c47d9b3ae0](https://linux-hardware.org/?probe=c47d9b3ae0) | Feb 03, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [7e21d67fa5](https://linux-hardware.org/?probe=7e21d67fa5) | Feb 03, 2022 |
| HP            | ProLiant ML110 G7           | Desktop     | [2e1dcafe6c](https://linux-hardware.org/?probe=2e1dcafe6c) | Feb 03, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [1837325ca2](https://linux-hardware.org/?probe=1837325ca2) | Feb 03, 2022 |
| HP            | 339A                        | Desktop     | [cf9dca84ff](https://linux-hardware.org/?probe=cf9dca84ff) | Feb 02, 2022 |
| ASUSTek       | K95VJ                       | Notebook    | [ebff9950e3](https://linux-hardware.org/?probe=ebff9950e3) | Feb 02, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [7b7a2f85e0](https://linux-hardware.org/?probe=7b7a2f85e0) | Feb 02, 2022 |
| Acer          | Aspire S3-391               | Notebook    | [87788239d2](https://linux-hardware.org/?probe=87788239d2) | Feb 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [2a4563231b](https://linux-hardware.org/?probe=2a4563231b) | Feb 02, 2022 |
| Toshiba       | Satellite L850D-BJS         | Notebook    | [d3897cf605](https://linux-hardware.org/?probe=d3897cf605) | Feb 02, 2022 |
| HP            | Pavilion 13 x360 PC         | Notebook    | [d2bcb368c1](https://linux-hardware.org/?probe=d2bcb368c1) | Feb 02, 2022 |
| PIPO          | Cherry Trail CR             | Notebook    | [eb92e7ef7f](https://linux-hardware.org/?probe=eb92e7ef7f) | Feb 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [629972c689](https://linux-hardware.org/?probe=629972c689) | Feb 01, 2022 |
| Acer          | Swift SF114-32              | Notebook    | [1a0b7da0df](https://linux-hardware.org/?probe=1a0b7da0df) | Feb 01, 2022 |
| HP            | 805D                        | Desktop     | [19295e5827](https://linux-hardware.org/?probe=19295e5827) | Feb 01, 2022 |
| Acer          | Swift SF114-32              | Notebook    | [ce9e5f5d44](https://linux-hardware.org/?probe=ce9e5f5d44) | Feb 01, 2022 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [ebeaf681e3](https://linux-hardware.org/?probe=ebeaf681e3) | Feb 01, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [18717f0712](https://linux-hardware.org/?probe=18717f0712) | Feb 01, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [b86eb71aa1](https://linux-hardware.org/?probe=b86eb71aa1) | Jan 31, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [1f2faf4487](https://linux-hardware.org/?probe=1f2faf4487) | Jan 31, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [03cb9013e4](https://linux-hardware.org/?probe=03cb9013e4) | Jan 31, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [34a7deb292](https://linux-hardware.org/?probe=34a7deb292) | Jan 30, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [add488b5fe](https://linux-hardware.org/?probe=add488b5fe) | Jan 30, 2022 |
| HP            | Elite x2 1012 G1            | Notebook    | [13b478195a](https://linux-hardware.org/?probe=13b478195a) | Jan 30, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [ac78806c22](https://linux-hardware.org/?probe=ac78806c22) | Jan 30, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [657fbc0f6d](https://linux-hardware.org/?probe=657fbc0f6d) | Jan 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [479381fba6](https://linux-hardware.org/?probe=479381fba6) | Jan 29, 2022 |
| Acer          | Swift SF314-59              | Notebook    | [697f73bc7c](https://linux-hardware.org/?probe=697f73bc7c) | Jan 29, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [7ab82cc23a](https://linux-hardware.org/?probe=7ab82cc23a) | Jan 29, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [a015de4156](https://linux-hardware.org/?probe=a015de4156) | Jan 29, 2022 |
| Teclast       | X6 plus                     | Tablet      | [a84fba541b](https://linux-hardware.org/?probe=a84fba541b) | Jan 29, 2022 |
| Apple         | MacBookPro9,1               | Notebook    | [857a74feaa](https://linux-hardware.org/?probe=857a74feaa) | Jan 28, 2022 |
| ASUSTek       | X550CA                      | Notebook    | [81cfc7fba7](https://linux-hardware.org/?probe=81cfc7fba7) | Jan 28, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [61d5b0014e](https://linux-hardware.org/?probe=61d5b0014e) | Jan 28, 2022 |
| Acer          | Aspire E5-571G              | Notebook    | [a29ec0cc55](https://linux-hardware.org/?probe=a29ec0cc55) | Jan 28, 2022 |
| MSI           | Z270 KRAIT GAMING           | Desktop     | [17ccbf9c76](https://linux-hardware.org/?probe=17ccbf9c76) | Jan 28, 2022 |
| Razer         | Blade Stealth               | Notebook    | [6a4fbb1374](https://linux-hardware.org/?probe=6a4fbb1374) | Jan 27, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [e800b95c58](https://linux-hardware.org/?probe=e800b95c58) | Jan 26, 2022 |
| Microsoft     | Surface Go                  | Tablet      | [124dcb4c34](https://linux-hardware.org/?probe=124dcb4c34) | Jan 26, 2022 |
| HP            | Pavilion dv5                | Notebook    | [62a18fa26b](https://linux-hardware.org/?probe=62a18fa26b) | Jan 26, 2022 |
| Microsoft     | Surface Go                  | Tablet      | [804f9dbb94](https://linux-hardware.org/?probe=804f9dbb94) | Jan 26, 2022 |
| ASUSTek       | X555LN                      | Notebook    | [8c1e438e47](https://linux-hardware.org/?probe=8c1e438e47) | Jan 26, 2022 |
| Apple         | MacBookAir1,1               | Notebook    | [dfbdc8f20b](https://linux-hardware.org/?probe=dfbdc8f20b) | Jan 25, 2022 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [8394958e0e](https://linux-hardware.org/?probe=8394958e0e) | Jan 25, 2022 |
| ASRock        | H61M-HVS                    | Desktop     | [8fdf1980ee](https://linux-hardware.org/?probe=8fdf1980ee) | Jan 25, 2022 |
| ASRock        | H61M-HVS                    | Desktop     | [5d19dff1e4](https://linux-hardware.org/?probe=5d19dff1e4) | Jan 25, 2022 |
| Acer          | ConceptD CM100-51A V:1.1    | Desktop     | [663bbd709d](https://linux-hardware.org/?probe=663bbd709d) | Jan 24, 2022 |
| Dell          | Latitude 5420               | Notebook    | [3aad8f46c6](https://linux-hardware.org/?probe=3aad8f46c6) | Jan 24, 2022 |
| Lenovo        | G550 20023                  | Notebook    | [9432cdb859](https://linux-hardware.org/?probe=9432cdb859) | Jan 24, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [79cf3b66a3](https://linux-hardware.org/?probe=79cf3b66a3) | Jan 24, 2022 |
| Lenovo        | G550 2958                   | Notebook    | [fd2872d2d8](https://linux-hardware.org/?probe=fd2872d2d8) | Jan 24, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [d1e0923b7a](https://linux-hardware.org/?probe=d1e0923b7a) | Jan 24, 2022 |
| HP            | EliteBook Folio 1040 G2     | Notebook    | [4e3ef7a5a7](https://linux-hardware.org/?probe=4e3ef7a5a7) | Jan 23, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [37e7b98af1](https://linux-hardware.org/?probe=37e7b98af1) | Jan 23, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [a5a4652304](https://linux-hardware.org/?probe=a5a4652304) | Jan 23, 2022 |
| ASUSTek       | ZenBook UX425UG_Q408UG      | Notebook    | [92991c028e](https://linux-hardware.org/?probe=92991c028e) | Jan 22, 2022 |
| Apple         | MacBookPro8,3               | Notebook    | [fb5a640b14](https://linux-hardware.org/?probe=fb5a640b14) | Jan 22, 2022 |
| FIRICH        | J1900                       | Desktop     | [937e24af64](https://linux-hardware.org/?probe=937e24af64) | Jan 22, 2022 |
| Lenovo        | ThinkPad T470 20JNS08H00    | Notebook    | [5007cce576](https://linux-hardware.org/?probe=5007cce576) | Jan 21, 2022 |
| ASUSTek       | ROG STRIX B360-H GAMING     | Desktop     | [d1505fe489](https://linux-hardware.org/?probe=d1505fe489) | Jan 21, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [db0cc3978c](https://linux-hardware.org/?probe=db0cc3978c) | Jan 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [7fd85b85b8](https://linux-hardware.org/?probe=7fd85b85b8) | Jan 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [2c01bf53cb](https://linux-hardware.org/?probe=2c01bf53cb) | Jan 21, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [3bf6b408ee](https://linux-hardware.org/?probe=3bf6b408ee) | Jan 21, 2022 |
| Fujitsu       | LIFEBOOK S760               | Notebook    | [f2de9fb609](https://linux-hardware.org/?probe=f2de9fb609) | Jan 20, 2022 |
| Fujitsu       | LIFEBOOK S760               | Notebook    | [0fdf944115](https://linux-hardware.org/?probe=0fdf944115) | Jan 20, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [0a8fb964eb](https://linux-hardware.org/?probe=0a8fb964eb) | Jan 20, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [75d67cd8a4](https://linux-hardware.org/?probe=75d67cd8a4) | Jan 20, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [7a14d864d4](https://linux-hardware.org/?probe=7a14d864d4) | Jan 20, 2022 |
| HP            | ProBook 4540s               | Notebook    | [16794fee23](https://linux-hardware.org/?probe=16794fee23) | Jan 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [3dd4035494](https://linux-hardware.org/?probe=3dd4035494) | Jan 19, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [df4c38dba6](https://linux-hardware.org/?probe=df4c38dba6) | Jan 19, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [3088724103](https://linux-hardware.org/?probe=3088724103) | Jan 19, 2022 |
| ASUSTek       | TUF B365M-PLUS GAMING       | Desktop     | [ec51f5ca3e](https://linux-hardware.org/?probe=ec51f5ca3e) | Jan 19, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [488d339e77](https://linux-hardware.org/?probe=488d339e77) | Jan 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [377afa98c8](https://linux-hardware.org/?probe=377afa98c8) | Jan 19, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [744cfeb340](https://linux-hardware.org/?probe=744cfeb340) | Jan 17, 2022 |
| ASUSTek       | X555LN                      | Notebook    | [6fba3bb5aa](https://linux-hardware.org/?probe=6fba3bb5aa) | Jan 17, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [e7225dad8e](https://linux-hardware.org/?probe=e7225dad8e) | Jan 17, 2022 |
| Dell          | Latitude E5400              | Notebook    | [1303d72d3b](https://linux-hardware.org/?probe=1303d72d3b) | Jan 17, 2022 |
| Acer          | Swift SF315-52              | Notebook    | [1a6e0815fc](https://linux-hardware.org/?probe=1a6e0815fc) | Jan 16, 2022 |
| Lenovo        | ThinkPad T430 2347JC2       | Notebook    | [cac66153bc](https://linux-hardware.org/?probe=cac66153bc) | Jan 16, 2022 |
| ASUSTek       | X541NA                      | Notebook    | [89459685e9](https://linux-hardware.org/?probe=89459685e9) | Jan 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [5248d37c26](https://linux-hardware.org/?probe=5248d37c26) | Jan 15, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [ff75719a4e](https://linux-hardware.org/?probe=ff75719a4e) | Jan 15, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [a76b9e67bb](https://linux-hardware.org/?probe=a76b9e67bb) | Jan 14, 2022 |
| HP            | ProBook 4430s               | Notebook    | [e2103ef2d8](https://linux-hardware.org/?probe=e2103ef2d8) | Jan 14, 2022 |
| ASUSTek       | H61M-CS                     | Desktop     | [8855875fbd](https://linux-hardware.org/?probe=8855875fbd) | Jan 14, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [ebdb392f57](https://linux-hardware.org/?probe=ebdb392f57) | Jan 14, 2022 |
| Unknown       | T3 MRD                      | Desktop     | [33392a90ce](https://linux-hardware.org/?probe=33392a90ce) | Jan 13, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [00a00c3cac](https://linux-hardware.org/?probe=00a00c3cac) | Jan 13, 2022 |
| MSI           | GE60 2PE                    | Notebook    | [d74dcddae6](https://linux-hardware.org/?probe=d74dcddae6) | Jan 13, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [39f3687349](https://linux-hardware.org/?probe=39f3687349) | Jan 12, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [d8c919f740](https://linux-hardware.org/?probe=d8c919f740) | Jan 12, 2022 |
| ASUSTek       | GL502VS                     | Notebook    | [feb64c0933](https://linux-hardware.org/?probe=feb64c0933) | Jan 12, 2022 |
| Foxconn       | 2AB1                        | Desktop     | [07faf9a309](https://linux-hardware.org/?probe=07faf9a309) | Jan 12, 2022 |
| Apple         | MacBook3,1                  | Notebook    | [c670d007f3](https://linux-hardware.org/?probe=c670d007f3) | Jan 11, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [66d12682ac](https://linux-hardware.org/?probe=66d12682ac) | Jan 10, 2022 |
| ASUSTek       | H110M-C                     | Desktop     | [be4291793d](https://linux-hardware.org/?probe=be4291793d) | Jan 10, 2022 |
| ASUSTek       | UX31A                       | Notebook    | [afe25bb395](https://linux-hardware.org/?probe=afe25bb395) | Jan 10, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [6a8c354065](https://linux-hardware.org/?probe=6a8c354065) | Jan 10, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [7ce29e0c54](https://linux-hardware.org/?probe=7ce29e0c54) | Jan 09, 2022 |
| Lenovo        | ThinkPad E14 20RAS0EQ00     | Notebook    | [ea22270511](https://linux-hardware.org/?probe=ea22270511) | Jan 09, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [9d29b20f2d](https://linux-hardware.org/?probe=9d29b20f2d) | Jan 08, 2022 |
| HP            | 8597                        | Desktop     | [09ed815dd0](https://linux-hardware.org/?probe=09ed815dd0) | Jan 08, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [72b280602e](https://linux-hardware.org/?probe=72b280602e) | Jan 07, 2022 |
| Lenovo        | ThinkPad T460s 20F9CTO1W... | Notebook    | [7ba01d7327](https://linux-hardware.org/?probe=7ba01d7327) | Jan 07, 2022 |
| Sony          | VPCEA3S1E                   | Notebook    | [670b7a5d31](https://linux-hardware.org/?probe=670b7a5d31) | Jan 07, 2022 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [b1c9832ce6](https://linux-hardware.org/?probe=b1c9832ce6) | Jan 07, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [172b005a76](https://linux-hardware.org/?probe=172b005a76) | Jan 07, 2022 |
| Dell          | Latitude 5420               | Notebook    | [ab3973e74b](https://linux-hardware.org/?probe=ab3973e74b) | Jan 07, 2022 |
| Dell          | Latitude 5420               | Notebook    | [517adf10a8](https://linux-hardware.org/?probe=517adf10a8) | Jan 06, 2022 |
| ASRock        | Z370 Pro4                   | Desktop     | [51cba69624](https://linux-hardware.org/?probe=51cba69624) | Jan 06, 2022 |
| Star Labs     | StarBook                    | Notebook    | [bd2b8ba939](https://linux-hardware.org/?probe=bd2b8ba939) | Jan 06, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [864ecfe029](https://linux-hardware.org/?probe=864ecfe029) | Jan 06, 2022 |
| Notebook      | W65_67SJ                    | Notebook    | [606e2587dd](https://linux-hardware.org/?probe=606e2587dd) | Jan 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [590907f437](https://linux-hardware.org/?probe=590907f437) | Jan 06, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [20dfc25b62](https://linux-hardware.org/?probe=20dfc25b62) | Jan 05, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [a0a13869ab](https://linux-hardware.org/?probe=a0a13869ab) | Jan 05, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [27756cb751](https://linux-hardware.org/?probe=27756cb751) | Jan 05, 2022 |
| MSI           | GF63 Thin 9SCSR             | Notebook    | [21f2a5e1b9](https://linux-hardware.org/?probe=21f2a5e1b9) | Jan 05, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [a03baba93d](https://linux-hardware.org/?probe=a03baba93d) | Jan 05, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [fbb0e6d1d5](https://linux-hardware.org/?probe=fbb0e6d1d5) | Jan 05, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [6eab59bbbf](https://linux-hardware.org/?probe=6eab59bbbf) | Jan 05, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [5496b24a51](https://linux-hardware.org/?probe=5496b24a51) | Jan 05, 2022 |
| Samsung       | 900X3C/900X3D/900X3E/900... | Notebook    | [520ced18c4](https://linux-hardware.org/?probe=520ced18c4) | Jan 05, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [ae2f1bc63c](https://linux-hardware.org/?probe=ae2f1bc63c) | Jan 05, 2022 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [b0df1464a1](https://linux-hardware.org/?probe=b0df1464a1) | Jan 05, 2022 |
| ASRock        | H97M Pro4                   | Desktop     | [92a6f429b5](https://linux-hardware.org/?probe=92a6f429b5) | Jan 05, 2022 |
| Sony          | SVE14A390X                  | Notebook    | [3b11d123cf](https://linux-hardware.org/?probe=3b11d123cf) | Jan 04, 2022 |
| HP            | ProBook 4430s               | Notebook    | [aafb807fc2](https://linux-hardware.org/?probe=aafb807fc2) | Jan 04, 2022 |
| HP            | ProBook 4430s               | Notebook    | [f534b0dd91](https://linux-hardware.org/?probe=f534b0dd91) | Jan 04, 2022 |
| Lenovo        | ThinkPad W541 20EGS1VV00    | Notebook    | [5d88eb323c](https://linux-hardware.org/?probe=5d88eb323c) | Jan 04, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [a1c3f24aab](https://linux-hardware.org/?probe=a1c3f24aab) | Jan 04, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [71e992725f](https://linux-hardware.org/?probe=71e992725f) | Jan 04, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [8087320623](https://linux-hardware.org/?probe=8087320623) | Jan 04, 2022 |
| Acer          | Aspire XXXX                 | Notebook    | [d52d9dc2bd](https://linux-hardware.org/?probe=d52d9dc2bd) | Jan 04, 2022 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [b18501f890](https://linux-hardware.org/?probe=b18501f890) | Jan 04, 2022 |
| Star Labs     | LabTop                      | Notebook    | [043cd26c60](https://linux-hardware.org/?probe=043cd26c60) | Jan 04, 2022 |
| HP            | ProLiant DL380p Gen8        | Server      | [1172390e59](https://linux-hardware.org/?probe=1172390e59) | Jan 04, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [9d633f7bdb](https://linux-hardware.org/?probe=9d633f7bdb) | Jan 04, 2022 |
| Lenovo        | ThinkPad L390 Yoga 20NT0... | Convertible | [c91feb11a8](https://linux-hardware.org/?probe=c91feb11a8) | Jan 04, 2022 |
| Lenovo        | ThinkPad E495 20NE001RTX    | Notebook    | [79e95e3cb6](https://linux-hardware.org/?probe=79e95e3cb6) | Jan 04, 2022 |
| Dell          | Precision 5530              | Notebook    | [b385c0a16e](https://linux-hardware.org/?probe=b385c0a16e) | Jan 04, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [023df04f60](https://linux-hardware.org/?probe=023df04f60) | Jan 04, 2022 |
| Monster       | ABRA A5 V13.2               | Notebook    | [6d8d622050](https://linux-hardware.org/?probe=6d8d622050) | Jan 04, 2022 |
| Acer          | Aspire XXXX                 | Notebook    | [b5d8962bbc](https://linux-hardware.org/?probe=b5d8962bbc) | Jan 04, 2022 |
| MSI           | PS63 Modern 8RD             | Notebook    | [1cd435c54f](https://linux-hardware.org/?probe=1cd435c54f) | Jan 04, 2022 |
| Lenovo        | Legion Y530-15ICH 81GT      | Notebook    | [c694c358f9](https://linux-hardware.org/?probe=c694c358f9) | Jan 04, 2022 |
| Lenovo        | 371C No DPK                 | All in one  | [6c4714d241](https://linux-hardware.org/?probe=6c4714d241) | Jan 04, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFS... | Notebook    | [c61ed9ea15](https://linux-hardware.org/?probe=c61ed9ea15) | Jan 04, 2022 |
| ASRock        | AB350M Pro4                 | Desktop     | [2886b84cc0](https://linux-hardware.org/?probe=2886b84cc0) | Jan 04, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [1015862a37](https://linux-hardware.org/?probe=1015862a37) | Jan 04, 2022 |
| Acidanther... | Mac-42FD25EABCABB274 iMa... | All in one  | [545dd570a9](https://linux-hardware.org/?probe=545dd570a9) | Jan 04, 2022 |
| Timi          | TM1613                      | Notebook    | [6761bd1e12](https://linux-hardware.org/?probe=6761bd1e12) | Jan 04, 2022 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [cd6abb9f49](https://linux-hardware.org/?probe=cd6abb9f49) | Jan 03, 2022 |
| ASUSTek       | E202SA                      | Notebook    | [d721e131f4](https://linux-hardware.org/?probe=d721e131f4) | Jan 02, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [440d6a1b59](https://linux-hardware.org/?probe=440d6a1b59) | Jan 02, 2022 |
| Apple         | MacBookPro5,1               | Notebook    | [6c7a3affdb](https://linux-hardware.org/?probe=6c7a3affdb) | Jan 02, 2022 |
| Dell          | Vostro 15 3515              | Notebook    | [45b6bf0410](https://linux-hardware.org/?probe=45b6bf0410) | Jan 01, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [fb332a2529](https://linux-hardware.org/?probe=fb332a2529) | Jan 01, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [d44b06ec61](https://linux-hardware.org/?probe=d44b06ec61) | Jan 01, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [f215102713](https://linux-hardware.org/?probe=f215102713) | Dec 31, 2021 |
| MSI           | 2A9C                        | Desktop     | [8d08f7f383](https://linux-hardware.org/?probe=8d08f7f383) | Dec 31, 2021 |
| Notebook      | P65xHP                      | Notebook    | [37db5af302](https://linux-hardware.org/?probe=37db5af302) | Dec 31, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [e060f00ff8](https://linux-hardware.org/?probe=e060f00ff8) | Dec 31, 2021 |
| Notebook      | P65xHP                      | Notebook    | [fc81fedcf3](https://linux-hardware.org/?probe=fc81fedcf3) | Dec 31, 2021 |
| Teclast       | F7                          | Notebook    | [44bba02dee](https://linux-hardware.org/?probe=44bba02dee) | Dec 31, 2021 |
| HP            | 3397                        | Desktop     | [323dc8992b](https://linux-hardware.org/?probe=323dc8992b) | Dec 31, 2021 |
| ASUSTek       | X79-DELUXE                  | Desktop     | [00b9dd3788](https://linux-hardware.org/?probe=00b9dd3788) | Dec 30, 2021 |
| Wortmann      | 1220729_1470271             | Notebook    | [018071ac3e](https://linux-hardware.org/?probe=018071ac3e) | Dec 30, 2021 |
| HP            | 1589                        | Desktop     | [d123a8de64](https://linux-hardware.org/?probe=d123a8de64) | Dec 30, 2021 |
| Foxconn       | 2AB1                        | Desktop     | [bcd6fc46cc](https://linux-hardware.org/?probe=bcd6fc46cc) | Dec 30, 2021 |
| Acer          | Aspire 7750G                | Notebook    | [3a24dba335](https://linux-hardware.org/?probe=3a24dba335) | Dec 28, 2021 |
| Acer          | Aspire 7750G                | Notebook    | [516cb4e250](https://linux-hardware.org/?probe=516cb4e250) | Dec 28, 2021 |
| ASUSTek       | X555UB                      | Notebook    | [e0844450ac](https://linux-hardware.org/?probe=e0844450ac) | Dec 28, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [5f67c759fe](https://linux-hardware.org/?probe=5f67c759fe) | Dec 28, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [fa46d4f41a](https://linux-hardware.org/?probe=fa46d4f41a) | Dec 28, 2021 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [829dc5243a](https://linux-hardware.org/?probe=829dc5243a) | Dec 28, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [22fb358e03](https://linux-hardware.org/?probe=22fb358e03) | Dec 28, 2021 |
| Dell          | Latitude 3580               | Notebook    | [f243f4c09e](https://linux-hardware.org/?probe=f243f4c09e) | Dec 27, 2021 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [5d91acd13d](https://linux-hardware.org/?probe=5d91acd13d) | Dec 27, 2021 |
| Lenovo        | ThinkPad T430 23501M2       | Notebook    | [2645817d64](https://linux-hardware.org/?probe=2645817d64) | Dec 26, 2021 |
| Gigabyte      | Z390 UD                     | Desktop     | [2399fa64ba](https://linux-hardware.org/?probe=2399fa64ba) | Dec 26, 2021 |
| HP            | EliteBook 850 G2            | Notebook    | [a71c970cbf](https://linux-hardware.org/?probe=a71c970cbf) | Dec 25, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [99bea5df6c](https://linux-hardware.org/?probe=99bea5df6c) | Dec 25, 2021 |
| Lenovo        | IdeaPad 320-14AST 80XU      | Notebook    | [80c8feb8bf](https://linux-hardware.org/?probe=80c8feb8bf) | Dec 25, 2021 |
| Dell          | Inspiron N5050              | Notebook    | [211b723554](https://linux-hardware.org/?probe=211b723554) | Dec 24, 2021 |
| LG Electro... | A410-G.BC51P1               | Notebook    | [b231405a63](https://linux-hardware.org/?probe=b231405a63) | Dec 24, 2021 |
| ASRock        | Z590 Phantom Gaming 4/ac    | Desktop     | [b52ca671f7](https://linux-hardware.org/?probe=b52ca671f7) | Dec 24, 2021 |
| Microsoft     | Surface Book 2              | Tablet      | [730558c6bd](https://linux-hardware.org/?probe=730558c6bd) | Dec 24, 2021 |
| Acer          | TravelMate 5760             | Notebook    | [71526c7767](https://linux-hardware.org/?probe=71526c7767) | Dec 23, 2021 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [783618fe4b](https://linux-hardware.org/?probe=783618fe4b) | Dec 23, 2021 |
| Lenovo        | Flex 2-14D 20376            | Notebook    | [d950a63316](https://linux-hardware.org/?probe=d950a63316) | Dec 23, 2021 |
| Dell          | Inspiron 3542               | Notebook    | [277f97ef07](https://linux-hardware.org/?probe=277f97ef07) | Dec 23, 2021 |
| Dell          | XPS 13 9343                 | Notebook    | [dfbdb618f1](https://linux-hardware.org/?probe=dfbdb618f1) | Dec 23, 2021 |
| ASUSTek       | H97-PLUS                    | Desktop     | [cba91c2ad2](https://linux-hardware.org/?probe=cba91c2ad2) | Dec 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [f74c2da103](https://linux-hardware.org/?probe=f74c2da103) | Dec 22, 2021 |
| Dell          | Precision M3800             | Notebook    | [ed44d9ac8c](https://linux-hardware.org/?probe=ed44d9ac8c) | Dec 21, 2021 |
| Apple         | MacBook2,1                  | Notebook    | [82483b42e2](https://linux-hardware.org/?probe=82483b42e2) | Dec 21, 2021 |
| Apple         | MacBook2,1                  | Notebook    | [197a4e0280](https://linux-hardware.org/?probe=197a4e0280) | Dec 21, 2021 |
| Dell          | Inspiron 7405 2n1           | Convertible | [64d2a0328e](https://linux-hardware.org/?probe=64d2a0328e) | Dec 21, 2021 |
| Apple         | MacBookAir6,1               | Notebook    | [b2e3490378](https://linux-hardware.org/?probe=b2e3490378) | Dec 21, 2021 |
| Dell          | Precision M6500             | Notebook    | [931f365c60](https://linux-hardware.org/?probe=931f365c60) | Dec 20, 2021 |
| MSI           | B450-A PRO MAX              | Desktop     | [f14eef1ae6](https://linux-hardware.org/?probe=f14eef1ae6) | Dec 20, 2021 |
| Gigabyte      | H310M S2P                   | Desktop     | [a931eb10f0](https://linux-hardware.org/?probe=a931eb10f0) | Dec 19, 2021 |
| Dell          | Inspiron 5555               | Notebook    | [09d45f017d](https://linux-hardware.org/?probe=09d45f017d) | Dec 18, 2021 |
| Foxconn       | 2AB1                        | Desktop     | [b789981cc4](https://linux-hardware.org/?probe=b789981cc4) | Dec 17, 2021 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [a45f76da28](https://linux-hardware.org/?probe=a45f76da28) | Dec 17, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [5627f53d66](https://linux-hardware.org/?probe=5627f53d66) | Dec 17, 2021 |
| ASUSTek       | UX410UAK                    | Notebook    | [39dcbe0f57](https://linux-hardware.org/?probe=39dcbe0f57) | Dec 17, 2021 |
| Monster       | MARKUT M7 V1.x              | Notebook    | [2d2ed2143e](https://linux-hardware.org/?probe=2d2ed2143e) | Dec 17, 2021 |
| Gigabyte      | Z590 AORUS ELITE AX         | Desktop     | [c068e358e8](https://linux-hardware.org/?probe=c068e358e8) | Dec 16, 2021 |
| Intel         | NUC10i3FNB K61362-305       | Mini pc     | [3371572aa9](https://linux-hardware.org/?probe=3371572aa9) | Dec 16, 2021 |
| Monster       | MARKUT M7 V1.x              | Notebook    | [2390550c49](https://linux-hardware.org/?probe=2390550c49) | Dec 15, 2021 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [720cc7a45f](https://linux-hardware.org/?probe=720cc7a45f) | Dec 15, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [661e7dae0c](https://linux-hardware.org/?probe=661e7dae0c) | Dec 15, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [b682cee818](https://linux-hardware.org/?probe=b682cee818) | Dec 15, 2021 |
| Apple         | MacBook5,2                  | Notebook    | [5dcbdab7ca](https://linux-hardware.org/?probe=5dcbdab7ca) | Dec 15, 2021 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [7b3efc8cd8](https://linux-hardware.org/?probe=7b3efc8cd8) | Dec 14, 2021 |
| Pegatron      | IPMH61P1                    | Desktop     | [1ba6ea2ee9](https://linux-hardware.org/?probe=1ba6ea2ee9) | Dec 14, 2021 |
| Acer          | ConceptD CM100-51A V:1.1    | Desktop     | [0b3e5753fc](https://linux-hardware.org/?probe=0b3e5753fc) | Dec 13, 2021 |
| Dell          | Inspiron 1764               | Notebook    | [a8abf45979](https://linux-hardware.org/?probe=a8abf45979) | Dec 13, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Elementary/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Elementary 6.1   | 657       | 47.68%  |
| Elementary 6     | 233       | 16.91%  |
| Elementary 5.1.7 | 231       | 16.76%  |
| Elementary 5.0   | 55        | 3.99%   |
| Elementary 5.1   | 46        | 3.34%   |
| Elementary 5.1.6 | 35        | 2.54%   |
| Elementary 5.1.4 | 33        | 2.39%   |
| Elementary 5.1.2 | 29        | 2.1%    |
| Elementary 5.1.3 | 23        | 1.67%   |
| Elementary 0.4.1 | 17        | 1.23%   |
| Elementary 5.1.5 | 11        | 0.8%    |
| Elementary 6.0   | 7         | 0.51%   |
| Elementary 7     | 1         | 0.07%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Elementary | 1327      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.11.0-43-generic | 127       | 8.61%   |
| 5.11.0-40-generic | 57        | 3.86%   |
| 5.15.0-46-generic | 54        | 3.66%   |
| 5.13.0-28-generic | 53        | 3.59%   |
| 5.11.0-41-generic | 52        | 3.53%   |
| 5.11.0-27-generic | 40        | 2.71%   |
| 5.13.0-30-generic | 38        | 2.58%   |
| 5.13.0-27-generic | 36        | 2.44%   |
| 5.13.0-39-generic | 35        | 2.37%   |
| 5.15.0-56-generic | 33        | 2.24%   |
| 5.4.0-42-generic  | 32        | 2.17%   |
| 5.11.0-38-generic | 27        | 1.83%   |
| 5.15.0-52-generic | 26        | 1.76%   |
| 5.15.0-41-generic | 26        | 1.76%   |
| 5.13.0-40-generic | 26        | 1.76%   |
| 5.11.0-37-generic | 25        | 1.69%   |
| 5.0.0-37-generic  | 25        | 1.69%   |
| 5.15.0-48-generic | 23        | 1.56%   |
| 5.13.0-35-generic | 23        | 1.56%   |
| 5.3.0-62-generic  | 21        | 1.42%   |
| 5.15.0-53-generic | 20        | 1.36%   |
| 5.13.0-37-generic | 19        | 1.29%   |
| 5.11.0-44-generic | 18        | 1.22%   |
| 5.11.0-25-generic | 18        | 1.22%   |
| 5.4.0-65-generic  | 17        | 1.15%   |
| 5.3.0-53-generic  | 16        | 1.08%   |
| 5.13.0-52-generic | 16        | 1.08%   |
| 5.13.0-51-generic | 16        | 1.08%   |
| 5.4.0-58-generic  | 15        | 1.02%   |
| 5.3.0-51-generic  | 14        | 0.95%   |
| 5.15.0-43-generic | 14        | 0.95%   |
| 5.13.0-41-generic | 14        | 0.95%   |
| 5.11.0-34-generic | 14        | 0.95%   |
| 5.4.0-52-generic  | 13        | 0.88%   |
| 5.4.0-48-generic  | 13        | 0.88%   |
| 5.13.0-44-generic | 13        | 0.88%   |
| 5.3.0-46-generic  | 12        | 0.81%   |
| 5.3.0-40-generic  | 12        | 0.81%   |
| 5.11.0-46-generic | 12        | 0.81%   |
| 5.15.0-50-generic | 11        | 0.75%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11.0  | 380       | 27.52%  |
| 5.13.0  | 283       | 20.49%  |
| 5.4.0   | 214       | 15.5%   |
| 5.15.0  | 195       | 14.12%  |
| 5.3.0   | 111       | 8.04%   |
| 4.15.0  | 85        | 6.15%   |
| 5.0.0   | 32        | 2.32%   |
| 5.8.0   | 14        | 1.01%   |
| 5.14.0  | 4         | 0.29%   |
| 4.18.0  | 4         | 0.29%   |
| 4.13.0  | 4         | 0.29%   |
| 5.10.0  | 3         | 0.22%   |
| 4.4.0   | 3         | 0.22%   |
| 5.15.5  | 2         | 0.14%   |
| 5.15.36 | 2         | 0.14%   |
| 5.15.12 | 2         | 0.14%   |
| 4.10.0  | 2         | 0.14%   |
| 6.0.8   | 1         | 0.07%   |
| 6.0.0   | 1         | 0.07%   |
| 5.9.1   | 1         | 0.07%   |
| 5.8.5   | 1         | 0.07%   |
| 5.8.13  | 1         | 0.07%   |
| 5.7.0   | 1         | 0.07%   |
| 5.6.2   | 1         | 0.07%   |
| 5.6.19  | 1         | 0.07%   |
| 5.6.14  | 1         | 0.07%   |
| 5.5.8   | 1         | 0.07%   |
| 5.5.6   | 1         | 0.07%   |
| 5.4.78  | 1         | 0.07%   |
| 5.4.1   | 1         | 0.07%   |
| 5.3.6   | 1         | 0.07%   |
| 5.3.11  | 1         | 0.07%   |
| 5.2.11  | 1         | 0.07%   |
| 5.19.4  | 1         | 0.07%   |
| 5.19.3  | 1         | 0.07%   |
| 5.19.12 | 1         | 0.07%   |
| 5.19.11 | 1         | 0.07%   |
| 5.19.0  | 1         | 0.07%   |
| 5.18.3  | 1         | 0.07%   |
| 5.17.3  | 1         | 0.07%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 380       | 27.58%  |
| 5.13    | 283       | 20.54%  |
| 5.4     | 216       | 15.67%  |
| 5.15    | 208       | 15.09%  |
| 5.3     | 113       | 8.2%    |
| 4.15    | 85        | 6.17%   |
| 5.0     | 33        | 2.39%   |
| 5.8     | 16        | 1.16%   |
| 5.14    | 8         | 0.58%   |
| 5.19    | 5         | 0.36%   |
| 5.10    | 4         | 0.29%   |
| 4.18    | 4         | 0.29%   |
| 4.13    | 4         | 0.29%   |
| 5.16    | 3         | 0.22%   |
| 4.4     | 3         | 0.22%   |
| 6.0     | 2         | 0.15%   |
| 5.5     | 2         | 0.15%   |
| 5.17    | 2         | 0.15%   |
| 4.10    | 2         | 0.15%   |
| 5.9     | 1         | 0.07%   |
| 5.7     | 1         | 0.07%   |
| 5.6     | 1         | 0.07%   |
| 5.2     | 1         | 0.07%   |
| 5.18    | 1         | 0.07%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1326      | 99.92%  |
| aarch64 | 1         | 0.08%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Pantheon      | 1218      | 90.69%  |
| Unknown       | 102       | 7.59%   |
| GNOME         | 13        | 0.97%   |
| X-Cinnamon    | 4         | 0.3%    |
| XFCE          | 1         | 0.07%   |
| Unity         | 1         | 0.07%   |
| MATE          | 1         | 0.07%   |
| KDE5          | 1         | 0.07%   |
| GNOME Classic | 1         | 0.07%   |
| Budgie        | 1         | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1325      | 99.77%  |
| Unknown | 2         | 0.15%   |
| Tty     | 1         | 0.08%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1061      | 79.06%  |
| LightDM | 204       | 15.2%   |
| TDM     | 69        | 5.14%   |
| GDM     | 5         | 0.37%   |
| GDM3    | 2         | 0.15%   |
| SDDM    | 1         | 0.07%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 559       | 41.53%  |
| de_DE   | 130       | 9.66%   |
| es_ES   | 87        | 6.46%   |
| en_GB   | 68        | 5.05%   |
| Unknown | 64        | 4.75%   |
| ru_RU   | 62        | 4.61%   |
| pt_BR   | 58        | 4.31%   |
| fr_FR   | 50        | 3.71%   |
| it_IT   | 37        | 2.75%   |
| pl_PL   | 23        | 1.71%   |
| en_AU   | 23        | 1.71%   |
| en_CA   | 22        | 1.63%   |
| nl_NL   | 15        | 1.11%   |
| tr_TR   | 13        | 0.97%   |
| pt_PT   | 13        | 0.97%   |
| en_IN   | 11        | 0.82%   |
| es_MX   | 9         | 0.67%   |
| zh_CN   | 7         | 0.52%   |
| hu_HU   | 7         | 0.52%   |
| de_CH   | 7         | 0.52%   |
| cs_CZ   | 6         | 0.45%   |
| sv_SE   | 5         | 0.37%   |
| id_ID   | 4         | 0.3%    |
| es_EC   | 4         | 0.3%    |
| en_ZA   | 4         | 0.3%    |
| uk_UA   | 3         | 0.22%   |
| nb_NO   | 3         | 0.22%   |
| hr_HR   | 3         | 0.22%   |
| fi_FI   | 3         | 0.22%   |
| ca_ES   | 3         | 0.22%   |
| zh_TW   | 2         | 0.15%   |
| ja_JP   | 2         | 0.15%   |
| gl_ES   | 2         | 0.15%   |
| fr_CA   | 2         | 0.15%   |
| fr_BE   | 2         | 0.15%   |
| es_CL   | 2         | 0.15%   |
| es_AR   | 2         | 0.15%   |
| en_PH   | 2         | 0.15%   |
| el_GR   | 2         | 0.15%   |
| de_AT   | 2         | 0.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 826       | 61.46%  |
| BIOS | 518       | 38.54%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1257      | 94.37%  |
| Btrfs   | 28        | 2.1%    |
| Unknown | 21        | 1.58%   |
| Overlay | 20        | 1.5%    |
| Xfs     | 5         | 0.38%   |
| Ext3    | 1         | 0.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1106      | 82.78%  |
| GPT     | 182       | 13.62%  |
| MBR     | 48        | 3.59%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1261      | 94.88%  |
| Yes       | 68        | 5.12%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1165      | 87.4%   |
| Yes       | 168       | 12.6%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 200       | 15.07%  |
| Lenovo              | 197       | 14.85%  |
| ASUSTek Computer    | 186       | 14.02%  |
| Dell                | 141       | 10.63%  |
| Apple               | 122       | 9.19%   |
| Acer                | 80        | 6.03%   |
| Gigabyte Technology | 64        | 4.82%   |
| MSI                 | 55        | 4.14%   |
| ASRock              | 29        | 2.19%   |
| Toshiba             | 28        | 2.11%   |
| Samsung Electronics | 18        | 1.36%   |
| HUAWEI              | 17        | 1.28%   |
| Intel               | 16        | 1.21%   |
| Sony                | 14        | 1.06%   |
| Microsoft           | 11        | 0.83%   |
| Biostar             | 9         | 0.68%   |
| Fujitsu             | 8         | 0.6%    |
| Packard Bell        | 6         | 0.45%   |
| Google              | 6         | 0.45%   |
| Pegatron            | 5         | 0.38%   |
| Notebook            | 5         | 0.38%   |
| LG Electronics      | 5         | 0.38%   |
| Foxconn             | 5         | 0.38%   |
| Unknown             | 5         | 0.38%   |
| Star Labs           | 4         | 0.3%    |
| Medion              | 4         | 0.3%    |
| AMI                 | 4         | 0.3%    |
| TUXEDO              | 3         | 0.23%   |
| Timi                | 3         | 0.23%   |
| Teclast             | 3         | 0.23%   |
| eMachines           | 3         | 0.23%   |
| ECS                 | 3         | 0.23%   |
| Compaq              | 3         | 0.23%   |
| Chuwi               | 3         | 0.23%   |
| Alienware           | 3         | 0.23%   |
| Acidanthera         | 3         | 0.23%   |
| Wortmann AG         | 2         | 0.15%   |
| Wibtek              | 2         | 0.15%   |
| TrekStor            | 2         | 0.15%   |
| Razer               | 2         | 0.15%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| ASUS All Series                    | 8         | 0.6%    |
| Apple iMac8,1                      | 7         | 0.53%   |
| Unknown                            | 7         | 0.53%   |
| HP Notebook                        | 6         | 0.45%   |
| Lenovo G50-45 80E3                 | 5         | 0.38%   |
| Apple MacBookPro8,2                | 5         | 0.38%   |
| Apple MacBookPro8,1                | 5         | 0.38%   |
| Apple MacBookAir7,2                | 5         | 0.38%   |
| HP Pavilion g6                     | 4         | 0.3%    |
| HP Laptop 15-bs0xx                 | 4         | 0.3%    |
| Dell Inspiron 15-3567              | 4         | 0.3%    |
| ASUS ZenBook UX425EA_UX425EA       | 4         | 0.3%    |
| ASUS P8H61-M LX3 R2.0              | 4         | 0.3%    |
| Apple MacBookPro9,2                | 4         | 0.3%    |
| Apple MacBookAir6,2                | 4         | 0.3%    |
| Apple MacBookAir4,2                | 4         | 0.3%    |
| Apple MacBook5,1                   | 4         | 0.3%    |
| Apple iMac11,3                     | 4         | 0.3%    |
| Samsung 530U3C/530U4C/532U3C       | 3         | 0.23%   |
| MSI MS-7C02                        | 3         | 0.23%   |
| HUAWEI NBLK-WAX9X                  | 3         | 0.23%   |
| HUAWEI MACHD-WXX9                  | 3         | 0.23%   |
| HP ProBook 4540s                   | 3         | 0.23%   |
| HP Pavilion Notebook               | 3         | 0.23%   |
| HP Pavilion dv7                    | 3         | 0.23%   |
| HP Laptop 15-db0xxx                | 3         | 0.23%   |
| HP Laptop 15-bw0xx                 | 3         | 0.23%   |
| HP ENVY x360 Convertible 13-ay0xxx | 3         | 0.23%   |
| HP EliteBook 840 G3                | 3         | 0.23%   |
| HP 250 G7 Notebook PC              | 3         | 0.23%   |
| HP 15                              | 3         | 0.23%   |
| Dell Latitude E6400                | 3         | 0.23%   |
| Dell Inspiron N5110                | 3         | 0.23%   |
| Dell Inspiron 1545                 | 3         | 0.23%   |
| ASUS X550CA                        | 3         | 0.23%   |
| ASUS PRIME A320M-K                 | 3         | 0.23%   |
| Apple Macmini5,1                   | 3         | 0.23%   |
| Apple MacBookPro9,1                | 3         | 0.23%   |
| Apple MacBookPro6,2                | 3         | 0.23%   |
| Apple MacBookPro5,5                | 3         | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 88        | 6.63%   |
| Lenovo IdeaPad     | 56        | 4.22%   |
| Acer Aspire        | 56        | 4.22%   |
| Dell Inspiron      | 42        | 3.17%   |
| HP Pavilion        | 41        | 3.09%   |
| Dell Latitude      | 35        | 2.64%   |
| HP ProBook         | 28        | 2.11%   |
| HP Laptop          | 27        | 2.03%   |
| HP EliteBook       | 23        | 1.73%   |
| Toshiba Satellite  | 22        | 1.66%   |
| ASUS PRIME         | 18        | 1.36%   |
| Dell XPS           | 17        | 1.28%   |
| ASUS ROG           | 17        | 1.28%   |
| Dell OptiPlex      | 16        | 1.21%   |
| ASUS ZenBook       | 14        | 1.06%   |
| ASUS VivoBook      | 14        | 1.06%   |
| HP ENVY            | 13        | 0.98%   |
| Dell Precision     | 12        | 0.9%    |
| ASUS TUF           | 12        | 0.9%    |
| Microsoft Surface  | 11        | 0.83%   |
| Apple MacBookPro8  | 11        | 0.83%   |
| Acer Swift         | 11        | 0.83%   |
| Dell Vostro        | 10        | 0.75%   |
| Lenovo ThinkCentre | 8         | 0.6%    |
| HP Compaq          | 8         | 0.6%    |
| ASUS All           | 8         | 0.6%    |
| Apple MacBookPro9  | 7         | 0.53%   |
| Apple MacBookPro11 | 7         | 0.53%   |
| Apple MacBookAir7  | 7         | 0.53%   |
| Apple iMac8        | 7         | 0.53%   |
| Unknown            | 7         | 0.53%   |
| Lenovo Yoga        | 6         | 0.45%   |
| HP Notebook        | 6         | 0.45%   |
| ASUS P8H61-M       | 6         | 0.45%   |
| Apple MacBookAir6  | 6         | 0.45%   |
| Apple MacBook5     | 6         | 0.45%   |
| Apple iMac11       | 6         | 0.45%   |
| Lenovo Legion      | 5         | 0.38%   |
| Lenovo G50-45      | 5         | 0.38%   |
| HP 250             | 5         | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 137       | 10.32%  |
| 2019    | 119       | 8.97%   |
| 2012    | 119       | 8.97%   |
| 2020    | 115       | 8.67%   |
| 2013    | 105       | 7.91%   |
| 2011    | 100       | 7.54%   |
| 2015    | 93        | 7.01%   |
| 2017    | 92        | 6.93%   |
| 2010    | 85        | 6.41%   |
| 2016    | 79        | 5.95%   |
| 2014    | 76        | 5.73%   |
| 2021    | 72        | 5.43%   |
| 2008    | 50        | 3.77%   |
| 2009    | 49        | 3.69%   |
| 2007    | 17        | 1.28%   |
| 2022    | 11        | 0.83%   |
| 2006    | 5         | 0.38%   |
| Unknown | 2         | 0.15%   |
| 2005    | 1         | 0.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 845       | 63.68%  |
| Desktop        | 354       | 26.68%  |
| All in one     | 48        | 3.62%   |
| Convertible    | 33        | 2.49%   |
| Tablet         | 23        | 1.73%   |
| Mini pc        | 19        | 1.43%   |
| Server         | 4         | 0.3%    |
| System on chip | 1         | 0.08%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1180      | 88.52%  |
| Enabled  | 153       | 11.48%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1316      | 99.17%  |
| Yes  | 11        | 0.83%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 382       | 28.61%  |
| 3.01-4.0    | 276       | 20.67%  |
| 8.01-16.0   | 253       | 18.95%  |
| 16.01-24.0  | 234       | 17.53%  |
| 32.01-64.0  | 98        | 7.34%   |
| 1.01-2.0    | 49        | 3.67%   |
| 64.01-256.0 | 16        | 1.2%    |
| 2.01-3.0    | 13        | 0.97%   |
| 24.01-32.0  | 12        | 0.9%    |
| 0.51-1.0    | 2         | 0.15%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 556       | 38.75%  |
| 2.01-3.0   | 409       | 28.5%   |
| 3.01-4.0   | 217       | 15.12%  |
| 4.01-8.0   | 176       | 12.26%  |
| 0.51-1.0   | 42        | 2.93%   |
| 8.01-16.0  | 32        | 2.23%   |
| 32.01-64.0 | 1         | 0.07%   |
| 24.01-32.0 | 1         | 0.07%   |
| 16.01-24.0 | 1         | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 856       | 63.64%  |
| 2       | 351       | 26.1%   |
| 3       | 65        | 4.83%   |
| 4       | 34        | 2.53%   |
| 5       | 17        | 1.26%   |
| 0       | 9         | 0.67%   |
| 6       | 7         | 0.52%   |
| 7       | 4         | 0.3%    |
| 8       | 1         | 0.07%   |
| Unknown | 1         | 0.07%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 847       | 63.3%   |
| Yes       | 491       | 36.7%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1088      | 81.99%  |
| No        | 239       | 18.01%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1124      | 84.26%  |
| No        | 210       | 15.74%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 952       | 71.2%   |
| No        | 385       | 28.8%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 178       | 13.39%  |
| Germany      | 132       | 9.93%   |
| Brazil       | 89        | 6.7%    |
| Russia       | 73        | 5.49%   |
| UK           | 68        | 5.12%   |
| India        | 51        | 3.84%   |
| Italy        | 50        | 3.76%   |
| Spain        | 48        | 3.61%   |
| Canada       | 42        | 3.16%   |
| France       | 41        | 3.09%   |
| Indonesia    | 35        | 2.63%   |
| Mexico       | 34        | 2.56%   |
| Australia    | 32        | 2.41%   |
| Poland       | 28        | 2.11%   |
| Turkey       | 27        | 2.03%   |
| Netherlands  | 22        | 1.66%   |
| Argentina    | 22        | 1.66%   |
| Belgium      | 19        | 1.43%   |
| Austria      | 17        | 1.28%   |
| Portugal     | 15        | 1.13%   |
| Ukraine      | 14        | 1.05%   |
| Switzerland  | 14        | 1.05%   |
| Sweden       | 13        | 0.98%   |
| Czechia      | 12        | 0.9%    |
| Romania      | 10        | 0.75%   |
| Malaysia     | 10        | 0.75%   |
| Chile        | 10        | 0.75%   |
| Colombia     | 9         | 0.68%   |
| South Africa | 8         | 0.6%    |
| Norway       | 8         | 0.6%    |
| New Zealand  | 8         | 0.6%    |
| Ireland      | 8         | 0.6%    |
| Hungary      | 8         | 0.6%    |
| China        | 8         | 0.6%    |
| Greece       | 7         | 0.53%   |
| Finland      | 7         | 0.53%   |
| Philippines  | 6         | 0.45%   |
| Denmark      | 6         | 0.45%   |
| Croatia      | 6         | 0.45%   |
| Belarus      | 6         | 0.45%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 21        | 1.52%   |
| Sydney            | 13        | 0.94%   |
| Warsaw            | 11        | 0.79%   |
| Milan             | 11        | 0.79%   |
| Berlin            | 11        | 0.79%   |
| Sao Paulo         | 10        | 0.72%   |
| Istanbul          | 10        | 0.72%   |
| Hamburg           | 10        | 0.72%   |
| Vienna            | 9         | 0.65%   |
| Paris             | 9         | 0.65%   |
| Rio de Janeiro    | 8         | 0.58%   |
| Munich            | 8         | 0.58%   |
| Madrid            | 8         | 0.58%   |
| St Petersburg     | 7         | 0.51%   |
| Mexico City       | 7         | 0.51%   |
| Fortaleza         | 7         | 0.51%   |
| Rome              | 6         | 0.43%   |
| Perth             | 6         | 0.43%   |
| Montreal          | 6         | 0.43%   |
| Jakarta           | 6         | 0.43%   |
| Dublin            | 6         | 0.43%   |
| The Hague         | 5         | 0.36%   |
| Surabaya          | 5         | 0.36%   |
| Novosibirsk       | 5         | 0.36%   |
| Nairobi           | 5         | 0.36%   |
| Brisbane          | 5         | 0.36%   |
| Bogor             | 5         | 0.36%   |
| Zagreb            | 4         | 0.29%   |
| Valencia          | 4         | 0.29%   |
| Toronto           | 4         | 0.29%   |
| Stuttgart         | 4         | 0.29%   |
| Sofia             | 4         | 0.29%   |
| Santo André      | 4         | 0.29%   |
| Prague            | 4         | 0.29%   |
| Pozza di Fassa    | 4         | 0.29%   |
| Mumbai            | 4         | 0.29%   |
| Minsk             | 4         | 0.29%   |
| Kolkata           | 4         | 0.29%   |
| Frankfurt am Main | 4         | 0.29%   |
| Dresden           | 4         | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 253       | 347    | 13.81%  |
| WDC                       | 243       | 326    | 13.26%  |
| Seagate                   | 227       | 293    | 12.39%  |
| Toshiba                   | 141       | 176    | 7.7%    |
| SanDisk                   | 118       | 132    | 6.44%   |
| Kingston                  | 112       | 144    | 6.11%   |
| Unknown                   | 92        | 114    | 5.02%   |
| Crucial                   | 73        | 91     | 3.98%   |
| Hitachi                   | 57        | 60     | 3.11%   |
| HGST                      | 47        | 58     | 2.57%   |
| Apple                     | 46        | 50     | 2.51%   |
| Intel                     | 43        | 52     | 2.35%   |
| SK hynix                  | 37        | 40     | 2.02%   |
| A-DATA Technology         | 31        | 35     | 1.69%   |
| Micron Technology         | 23        | 26     | 1.26%   |
| Phison                    | 16        | 18     | 0.87%   |
| China                     | 16        | 18     | 0.87%   |
| KIOXIA                    | 14        | 20     | 0.76%   |
| PNY                       | 13        | 19     | 0.71%   |
| Fujitsu                   | 10        | 11     | 0.55%   |
| Transcend                 | 9         | 10     | 0.49%   |
| OCZ                       | 9         | 14     | 0.49%   |
| Micron/Crucial Technology | 9         | 14     | 0.49%   |
| LITEON                    | 8         | 8      | 0.44%   |
| Silicon Motion            | 7         | 8      | 0.38%   |
| JMicron Technology        | 7         | 7      | 0.38%   |
| SPCC                      | 6         | 6      | 0.33%   |
| Patriot                   | 6         | 8      | 0.33%   |
| Corsair                   | 6         | 6      | 0.33%   |
| Unknown                   | 6         | 8      | 0.33%   |
| Team                      | 5         | 6      | 0.27%   |
| Intenso                   | 5         | 5      | 0.27%   |
| Gigabyte Technology       | 5         | 5      | 0.27%   |
| Plextor                   | 4         | 5      | 0.22%   |
| Lite-On                   | 4         | 4      | 0.22%   |
| KingDian                  | 4         | 6      | 0.22%   |
| Hewlett-Packard           | 4         | 4      | 0.22%   |
| Apacer                    | 4         | 5      | 0.22%   |
| TO Exter                  | 3         | 3      | 0.16%   |
| Realtek Semiconductor     | 3         | 4      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 32        | 1.63%   |
| Toshiba MQ01ABD100 1TB                              | 24        | 1.22%   |
| Unknown MMC Card  32GB                              | 22        | 1.12%   |
| Samsung NVMe SSD Drive 512GB                        | 22        | 1.12%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 21        | 1.07%   |
| Samsung SSD 850 EVO 250GB                           | 17        | 0.87%   |
| Unknown MMC Card  64GB                              | 16        | 0.82%   |
| Seagate ST1000LM035-1RK172 1TB                      | 16        | 0.82%   |
| SanDisk NVMe SSD Drive 512GB                        | 16        | 0.82%   |
| Samsung NVMe SSD Drive 500GB                        | 16        | 0.82%   |
| Kingston SA400S37120G 120GB SSD                     | 16        | 0.82%   |
| Toshiba MQ04ABF100 1TB                              | 14        | 0.71%   |
| Seagate ST500LT012-1DG142 500GB                     | 14        | 0.71%   |
| Samsung SSD 860 EVO 250GB                           | 13        | 0.66%   |
| HGST HTS721010A9E630 1TB                            | 13        | 0.66%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 12        | 0.61%   |
| Unknown MMC Card  128GB                             | 12        | 0.61%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 12        | 0.61%   |
| Intel NVMe SSD Drive 512GB                          | 12        | 0.61%   |
| Samsung SSD 860 EVO 500GB                           | 11        | 0.56%   |
| Samsung NVMe SSD Drive 1TB                          | 11        | 0.56%   |
| Kingston SV300S37A120G 120GB SSD                    | 11        | 0.56%   |
| Toshiba MQ01ABF050 500GB                            | 10        | 0.51%   |
| SK hynix NVMe SSD Drive 512GB                       | 10        | 0.51%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 9         | 0.46%   |
| Toshiba NVMe SSD Drive 256GB                        | 9         | 0.46%   |
| Samsung SSD 860 EVO 1TB                             | 9         | 0.46%   |
| HGST HTS545050A7E680 500GB                          | 9         | 0.46%   |
| Crucial CT240BX500SSD1 240GB                        | 9         | 0.46%   |
| Unknown MMC Card  16GB                              | 8         | 0.41%   |
| SK hynix NVMe SSD Drive 256GB                       | 8         | 0.41%   |
| Seagate ST500DM002-1BD142 500GB                     | 8         | 0.41%   |
| SanDisk NVMe SSD Drive 256GB                        | 8         | 0.41%   |
| Samsung SSD 850 EVO 500GB                           | 8         | 0.41%   |
| Toshiba DT01ACA100 1TB                              | 7         | 0.36%   |
| Toshiba DT01ACA050 500GB                            | 7         | 0.36%   |
| Seagate ST3500418AS 500GB                           | 7         | 0.36%   |
| Seagate ST1000DM003-1ER162 1TB                      | 7         | 0.36%   |
| Samsung SSD 840 EVO 250GB                           | 7         | 0.36%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 7         | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 222       | 284    | 32.41%  |
| WDC                 | 189       | 250    | 27.59%  |
| Toshiba             | 110       | 140    | 16.06%  |
| Hitachi             | 57        | 60     | 8.32%   |
| HGST                | 47        | 58     | 6.86%   |
| Samsung Electronics | 25        | 29     | 3.65%   |
| Apple               | 13        | 14     | 1.9%    |
| Fujitsu             | 10        | 11     | 1.46%   |
| Unknown             | 4         | 5      | 0.58%   |
| Maxtor              | 2         | 2      | 0.29%   |
| ASMT                | 2         | 2      | 0.29%   |
| StoreJet            | 1         | 1      | 0.15%   |
| Hewlett-Packard     | 1         | 1      | 0.15%   |
| Generic-            | 1         | 1      | 0.15%   |
| Ext Hard            | 1         | 1      | 0.15%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 137       | 178    | 19.86%  |
| Kingston            | 94        | 108    | 13.62%  |
| Crucial             | 72        | 89     | 10.43%  |
| SanDisk             | 71        | 80     | 10.29%  |
| WDC                 | 40        | 50     | 5.8%    |
| Apple               | 31        | 32     | 4.49%   |
| A-DATA Technology   | 27        | 31     | 3.91%   |
| Intel               | 18        | 18     | 2.61%   |
| China               | 16        | 18     | 2.32%   |
| PNY                 | 13        | 19     | 1.88%   |
| Micron Technology   | 13        | 15     | 1.88%   |
| Toshiba             | 12        | 12     | 1.74%   |
| Transcend           | 9         | 10     | 1.3%    |
| OCZ                 | 9         | 14     | 1.3%    |
| LITEON              | 8         | 8      | 1.16%   |
| SK hynix            | 7         | 7      | 1.01%   |
| SPCC                | 6         | 6      | 0.87%   |
| Patriot             | 6         | 8      | 0.87%   |
| Corsair             | 6         | 6      | 0.87%   |
| Team                | 5         | 6      | 0.72%   |
| Intenso             | 5         | 5      | 0.72%   |
| Plextor             | 4         | 5      | 0.58%   |
| Apacer              | 4         | 5      | 0.58%   |
| TO Exter            | 3         | 3      | 0.43%   |
| Lexar               | 3         | 3      | 0.43%   |
| KingDian            | 3         | 5      | 0.43%   |
| JMicron Technology  | 3         | 3      | 0.43%   |
| Hewlett-Packard     | 3         | 3      | 0.43%   |
| GOODRAM             | 3         | 6      | 0.43%   |
| Gigabyte Technology | 3         | 3      | 0.43%   |
| FORESEE             | 3         | 3      | 0.43%   |
| Teclast             | 2         | 2      | 0.29%   |
| Star                | 2         | 2      | 0.29%   |
| NGFF                | 2         | 2      | 0.29%   |
| Netac               | 2         | 2      | 0.29%   |
| LITEONIT            | 2         | 2      | 0.29%   |
| Leven               | 2         | 2      | 0.29%   |
| KingSpec            | 2         | 2      | 0.29%   |
| HUSKY               | 2         | 2      | 0.29%   |
| Emtec               | 2         | 2      | 0.29%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 620       | 859    | 36.54%  |
| SSD     | 616       | 816    | 36.3%   |
| NVMe    | 338       | 456    | 19.92%  |
| MMC     | 83        | 96     | 4.89%   |
| Unknown | 40        | 53     | 2.36%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1044      | 1648   | 68.41%  |
| NVMe | 337       | 454    | 22.08%  |
| MMC  | 83        | 96     | 5.44%   |
| SAS  | 62        | 82     | 4.06%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 805       | 1116   | 65.71%  |
| 0.51-1.0   | 328       | 425    | 26.78%  |
| 1.01-2.0   | 49        | 67     | 4%      |
| 2.01-3.0   | 17        | 35     | 1.39%   |
| 4.01-10.0  | 13        | 17     | 1.06%   |
| 3.01-4.0   | 12        | 14     | 0.98%   |
| 10.01-20.0 | 1         | 1      | 0.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 505       | 37%     |
| 251-500        | 350       | 25.64%  |
| 501-1000       | 194       | 14.21%  |
| 51-100         | 102       | 7.47%   |
| 1001-2000      | 77        | 5.64%   |
| 21-50          | 68        | 4.98%   |
| More than 3000 | 26        | 1.9%    |
| 2001-3000      | 19        | 1.39%   |
| 1-20           | 19        | 1.39%   |
| Unknown        | 5         | 0.37%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 600       | 42.19%  |
| 21-50          | 334       | 23.49%  |
| 51-100         | 170       | 11.95%  |
| 101-250        | 150       | 10.55%  |
| 251-500        | 72        | 5.06%   |
| 501-1000       | 53        | 3.73%   |
| 1001-2000      | 23        | 1.62%   |
| 2001-3000      | 8         | 0.56%   |
| More than 3000 | 7         | 0.49%   |
| Unknown        | 5         | 0.35%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                   | Computers | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| WDC WDS240G2G0B-00EPW0 240GB SSD        | 1         | 1      | 2.08%   |
| WDC WD5000BPKT-75PK4T0 500GB            | 1         | 1      | 2.08%   |
| WDC WD5000AAKX-22ERMA0 500GB            | 1         | 1      | 2.08%   |
| WDC WD5000AAKX-221CA1 500GB             | 1         | 1      | 2.08%   |
| WDC WD5000AAKX-00ERMA0 500GB            | 1         | 1      | 2.08%   |
| WDC WD5000AAKS-00UU3A0 500GB            | 1         | 1      | 2.08%   |
| WDC WD3200AAJS-56B4A0 320GB             | 1         | 1      | 2.08%   |
| WDC WD10SPZX-24Z10 1TB                  | 1         | 1      | 2.08%   |
| WDC WD10EZEX-00KUWA0 1TB                | 1         | 1      | 2.08%   |
| WDC WD1003FZEX-00MK2A0 1TB              | 1         | 1      | 2.08%   |
| Toshiba MQ01ABD100 1TB                  | 1         | 1      | 2.08%   |
| Toshiba MK3259GSXP 320GB                | 1         | 1      | 2.08%   |
| Toshiba KBG30ZPZ128G 128GB              | 1         | 1      | 2.08%   |
| Seagate ST500LT012-9WS142 500GB         | 1         | 1      | 2.08%   |
| Seagate ST500LM030-2E717D 500GB         | 1         | 1      | 2.08%   |
| Seagate ST500DM002-1BD142 500GB         | 1         | 1      | 2.08%   |
| Seagate ST3500414CS 500GB               | 1         | 2      | 2.08%   |
| Seagate ST3500312CS 500GB               | 1         | 1      | 2.08%   |
| Seagate ST3320613AS 320GB               | 1         | 1      | 2.08%   |
| Seagate ST320LT020-9YG142 320GB         | 1         | 1      | 2.08%   |
| Seagate ST3160813AS 160GB               | 1         | 1      | 2.08%   |
| Seagate ST2000DM006-2DM164 2TB          | 1         | 1      | 2.08%   |
| Seagate ST1000LX015-1U7172-SSHD 1TB     | 1         | 1      | 2.08%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 1         | 1      | 2.08%   |
| SanDisk SSD PLUS 240GB                  | 1         | 1      | 2.08%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD     | 1         | 1      | 2.08%   |
| SanDisk SD7SB3Q256G1002 256GB SSD       | 1         | 1      | 2.08%   |
| Samsung Electronics HD322GJ 320GB       | 1         | 1      | 2.08%   |
| Samsung Electronics HD204UI 2TB         | 1         | 1      | 2.08%   |
| Samsung Electronics HD160JJ/ 160GB      | 1         | 1      | 2.08%   |
| Kingston SV300S37A240G 240GB SSD        | 1         | 1      | 2.08%   |
| Kingston SUV400S37480G 480GB SSD        | 1         | 1      | 2.08%   |
| Kingston SA400S37120G 120GB SSD         | 1         | 1      | 2.08%   |
| Kingston RBU-SNS8350DES3128GP 128GB SSD | 1         | 1      | 2.08%   |
| Hitachi HTS542525K9SA00 250GB           | 1         | 1      | 2.08%   |
| Hitachi HDT721064SLA360 640GB           | 1         | 1      | 2.08%   |
| Hitachi HDS721010CLA332 1TB             | 1         | 1      | 2.08%   |
| HGST HUS724030ALA640 3TB                | 1         | 1      | 2.08%   |
| HGST HTS725050A7E630 500GB              | 1         | 1      | 2.08%   |
| HGST HTS721010A9E630 1TB                | 1         | 1      | 2.08%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 12     | 22.92%  |
| WDC                 | 10        | 10     | 20.83%  |
| HGST                | 5         | 5      | 10.42%  |
| Kingston            | 4         | 4      | 8.33%   |
| Toshiba             | 3         | 3      | 6.25%   |
| SanDisk             | 3         | 3      | 6.25%   |
| Samsung Electronics | 3         | 3      | 6.25%   |
| Hitachi             | 3         | 3      | 6.25%   |
| Crucial             | 2         | 2      | 4.17%   |
| Apple               | 2         | 2      | 4.17%   |
| Fujitsu             | 1         | 2      | 2.08%   |
| A-DATA Technology   | 1         | 1      | 2.08%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 12     | 31.43%  |
| WDC                 | 9         | 9      | 25.71%  |
| HGST                | 5         | 5      | 14.29%  |
| Samsung Electronics | 3         | 3      | 8.57%   |
| Hitachi             | 3         | 3      | 8.57%   |
| Toshiba             | 2         | 2      | 5.71%   |
| Fujitsu             | 1         | 2      | 2.86%   |
| Apple               | 1         | 1      | 2.86%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 32        | 37     | 71.11%  |
| SSD  | 12        | 12     | 26.67%  |
| NVMe | 1         | 1      | 2.22%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                    | Computers | Drives | Percent |
|--------------------------|-----------|--------|---------|
| WDC WD10SPZX-75Z10T1 1TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1136      | 1938   | 82.5%   |
| Works    | 196       | 291    | 14.23%  |
| Malfunc  | 44        | 50     | 3.2%    |
| Failed   | 1         | 1      | 0.07%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 941       | 59.63%  |
| AMD                            | 193       | 12.23%  |
| Samsung Electronics            | 132       | 8.37%   |
| SanDisk                        | 64        | 4.06%   |
| Nvidia                         | 37        | 2.34%   |
| SK hynix                       | 30        | 1.9%    |
| Toshiba America Info Systems   | 21        | 1.33%   |
| Kingston Technology Company    | 21        | 1.33%   |
| Phison Electronics             | 20        | 1.27%   |
| Marvell Technology Group       | 16        | 1.01%   |
| ASMedia Technology             | 16        | 1.01%   |
| KIOXIA                         | 13        | 0.82%   |
| Micron/Crucial Technology      | 10        | 0.63%   |
| Micron Technology              | 10        | 0.63%   |
| JMicron Technology             | 9         | 0.57%   |
| ADATA Technology               | 8         | 0.51%   |
| Silicon Motion                 | 7         | 0.44%   |
| Realtek Semiconductor          | 5         | 0.32%   |
| Union Memory (Shenzhen)        | 4         | 0.25%   |
| Lite-On Technology             | 4         | 0.25%   |
| Seagate Technology             | 3         | 0.19%   |
| LSI Logic / Symbios Logic      | 3         | 0.19%   |
| Broadcom / LSI                 | 2         | 0.13%   |
| Apple                          | 2         | 0.13%   |
| Yangtze Memory Technologies    | 1         | 0.06%   |
| VIA Technologies               | 1         | 0.06%   |
| Solid State Storage Technology | 1         | 0.06%   |
| Silicon Image                  | 1         | 0.06%   |
| Shenzhen Longsys Electronics   | 1         | 0.06%   |
| Hewlett-Packard                | 1         | 0.06%   |
| Biwin Storage Technology       | 1         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 151       | 8.52%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 97        | 5.47%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 86        | 4.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 66        | 3.72%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 57        | 3.22%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 54        | 3.05%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 50        | 2.82%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 43        | 2.43%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 32        | 1.81%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 29        | 1.64%   |
| Samsung NVMe SSD Controller 980                                                         | 27        | 1.52%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 26        | 1.47%   |
| AMD 400 Series Chipset SATA Controller                                                  | 26        | 1.47%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 25        | 1.41%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 24        | 1.35%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 24        | 1.35%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 22        | 1.24%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 22        | 1.24%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 21        | 1.19%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 20        | 1.13%   |
| Intel SATA Controller [RAID mode]                                                       | 19        | 1.07%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 19        | 1.07%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 19        | 1.07%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 19        | 1.07%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 19        | 1.07%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 19        | 1.07%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 18        | 1.02%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 17        | 0.96%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 17        | 0.96%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 16        | 0.9%    |
| Nvidia MCP79 AHCI Controller                                                            | 15        | 0.85%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 15        | 0.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 14        | 0.79%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 14        | 0.79%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 13        | 0.73%   |
| Intel SSD 660P Series                                                                   | 13        | 0.73%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 12        | 0.68%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 12        | 0.68%   |
| KIOXIA NVMe SSD Controller BG4                                                          | 12        | 0.68%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 12        | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1000      | 62.66%  |
| NVMe | 338       | 21.18%  |
| IDE  | 149       | 9.34%   |
| RAID | 104       | 6.52%   |
| SAS  | 3         | 0.19%   |
| SCSI | 2         | 0.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 1080      | 81.39%  |
| AMD    | 246       | 18.54%  |
| ARM    | 1         | 0.08%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 22        | 1.66%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 19        | 1.43%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 17        | 1.28%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 14        | 1.06%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 14        | 1.06%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 13        | 0.98%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 12        | 0.9%    |
| Intel Core i5-4300U CPU @ 1.90GHz             | 12        | 0.9%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 12        | 0.9%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 12        | 0.9%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 11        | 0.83%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 11        | 0.83%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 10        | 0.75%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 10        | 0.75%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 10        | 0.75%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 10        | 0.75%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 9         | 0.68%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 9         | 0.68%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 9         | 0.68%   |
| AMD Ryzen 5 3600 6-Core Processor             | 9         | 0.68%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 9         | 0.68%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 8         | 0.6%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 8         | 0.6%    |
| Intel Core i3-6006U CPU @ 2.00GHz             | 8         | 0.6%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 8         | 0.6%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 7         | 0.53%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 7         | 0.53%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 7         | 0.53%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 7         | 0.53%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 7         | 0.53%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 7         | 0.53%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 7         | 0.53%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 6         | 0.45%   |
| Intel Core i9-9900K CPU @ 3.60GHz             | 6         | 0.45%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 6         | 0.45%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 6         | 0.45%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 6         | 0.45%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 6         | 0.45%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 6         | 0.45%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 6         | 0.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 335       | 25.24%  |
| Intel Core i7           | 271       | 20.42%  |
| Intel Core i3           | 132       | 9.95%   |
| Intel Celeron           | 76        | 5.73%   |
| AMD Ryzen 5             | 69        | 5.2%    |
| Intel Core 2 Duo        | 68        | 5.12%   |
| Other                   | 60        | 4.52%   |
| AMD Ryzen 7             | 37        | 2.79%   |
| Intel Pentium           | 30        | 2.26%   |
| Intel Xeon              | 26        | 1.96%   |
| Intel Atom              | 22        | 1.66%   |
| Intel Pentium Dual-Core | 16        | 1.21%   |
| AMD Ryzen 3             | 15        | 1.13%   |
| AMD A8                  | 14        | 1.06%   |
| Intel Core 2 Quad       | 11        | 0.83%   |
| AMD FX                  | 11        | 0.83%   |
| AMD A6                  | 11        | 0.83%   |
| AMD A10                 | 11        | 0.83%   |
| AMD Ryzen 9             | 10        | 0.75%   |
| Intel Pentium Silver    | 9         | 0.68%   |
| AMD Phenom II X4        | 8         | 0.6%    |
| AMD A4                  | 8         | 0.6%    |
| Intel Core i9           | 7         | 0.53%   |
| Intel Core 2            | 7         | 0.53%   |
| Intel Core m3           | 4         | 0.3%    |
| AMD Ryzen 7 PRO         | 4         | 0.3%    |
| AMD Ryzen 5 PRO         | 4         | 0.3%    |
| AMD E1                  | 4         | 0.3%    |
| AMD Athlon II X4        | 4         | 0.3%    |
| AMD Athlon II X2        | 4         | 0.3%    |
| AMD A12                 | 4         | 0.3%    |
| Intel Genuine           | 3         | 0.23%   |
| Intel Celeron Dual-Core | 3         | 0.23%   |
| AMD Athlon              | 3         | 0.23%   |
| Intel Pentium Dual      | 2         | 0.15%   |
| Intel Core m5           | 2         | 0.15%   |
| AMD Phenom II           | 2         | 0.15%   |
| AMD Phenom              | 2         | 0.15%   |
| AMD E                   | 2         | 0.15%   |
| AMD C-60                | 2         | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 638       | 48.01%  |
| 4      | 487       | 36.64%  |
| 6      | 96        | 7.22%   |
| 8      | 69        | 5.19%   |
| 1      | 15        | 1.13%   |
| 12     | 10        | 0.75%   |
| 3      | 8         | 0.6%    |
| 16     | 4         | 0.3%    |
| 10     | 2         | 0.15%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 1319      | 99.4%   |
| 2      | 8         | 0.6%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 893       | 67.19%  |
| 1      | 436       | 32.81%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1316      | 99.1%   |
| Unknown        | 11        | 0.83%   |
| 64-bit         | 1         | 0.08%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x206a7    | 124       | 9.19%   |
| Unknown    | 116       | 8.59%   |
| 0x306a9    | 101       | 7.48%   |
| 0x306c3    | 63        | 4.67%   |
| 0x1067a    | 57        | 4.22%   |
| 0x40651    | 49        | 3.63%   |
| 0x806e9    | 41        | 3.04%   |
| 0x406e3    | 40        | 2.96%   |
| 0x806c1    | 36        | 2.67%   |
| 0x806ea    | 35        | 2.59%   |
| 0x806ec    | 34        | 2.52%   |
| 0x306d4    | 34        | 2.52%   |
| 0x20655    | 30        | 2.22%   |
| 0x906ea    | 28        | 2.07%   |
| 0x906e9    | 25        | 1.85%   |
| 0x20652    | 22        | 1.63%   |
| 0x10676    | 21        | 1.56%   |
| 0x30678    | 19        | 1.41%   |
| 0x08108109 | 19        | 1.41%   |
| 0x706a1    | 17        | 1.26%   |
| 0x506e3    | 17        | 1.26%   |
| 0x08701021 | 16        | 1.19%   |
| 0x706e5    | 15        | 1.11%   |
| 0x806eb    | 14        | 1.04%   |
| 0x406c3    | 13        | 0.96%   |
| 0xa0652    | 12        | 0.89%   |
| 0x506c9    | 12        | 0.89%   |
| 0x106e5    | 12        | 0.89%   |
| 0x06006705 | 12        | 0.89%   |
| 0x906ed    | 11        | 0.81%   |
| 0x706a8    | 11        | 0.81%   |
| 0x6fb      | 11        | 0.81%   |
| 0x08600106 | 11        | 0.81%   |
| 0x406c4    | 10        | 0.74%   |
| 0x0800820d | 10        | 0.74%   |
| 0x06001119 | 10        | 0.74%   |
| 0x010000c8 | 10        | 0.74%   |
| 0x906eb    | 9         | 0.67%   |
| 0x08108102 | 9         | 0.67%   |
| 0x6fd      | 8         | 0.59%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 225       | 16.96%  |
| SandyBridge      | 136       | 10.25%  |
| Haswell          | 129       | 9.72%   |
| IvyBridge        | 109       | 8.21%   |
| Penryn           | 81        | 6.1%    |
| Skylake          | 64        | 4.82%   |
| Westmere         | 54        | 4.07%   |
| Silvermont       | 50        | 3.77%   |
| Zen 2            | 46        | 3.47%   |
| Zen+             | 44        | 3.32%   |
| TigerLake        | 42        | 3.17%   |
| Broadwell        | 38        | 2.86%   |
| Core             | 34        | 2.56%   |
| Goldmont plus    | 30        | 2.26%   |
| Excavator        | 28        | 2.11%   |
| Zen              | 27        | 2.03%   |
| IceLake          | 25        | 1.88%   |
| K10              | 22        | 1.66%   |
| CometLake        | 22        | 1.66%   |
| Piledriver       | 18        | 1.36%   |
| Nehalem          | 17        | 1.28%   |
| Zen 3            | 16        | 1.21%   |
| Unknown          | 13        | 0.98%   |
| Goldmont         | 12        | 0.9%    |
| Puma             | 10        | 0.75%   |
| Bobcat           | 7         | 0.53%   |
| Jaguar           | 6         | 0.45%   |
| Steamroller      | 4         | 0.3%    |
| Bulldozer        | 4         | 0.3%    |
| Bonnell          | 4         | 0.3%    |
| Tremont          | 3         | 0.23%   |
| NetBurst         | 2         | 0.15%   |
| K10 Llano        | 2         | 0.15%   |
| K8 Hammer        | 1         | 0.08%   |
| K8 & K10 hybrid  | 1         | 0.08%   |
| Alderlake Hybrid | 1         | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 851       | 54.69%  |
| AMD                        | 352       | 22.62%  |
| Nvidia                     | 349       | 22.43%  |
| ATI Technologies           | 2         | 0.13%   |
| Matrox Electronics Systems | 1         | 0.06%   |
| Conexant Systems           | 1         | 0.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 101       | 6.3%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 73        | 4.55%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 51        | 3.18%   |
| Intel HD Graphics 620                                                                    | 45        | 2.81%   |
| Intel Core Processor Integrated Graphics Controller                                      | 39        | 2.43%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 38        | 2.37%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 38        | 2.37%   |
| Intel UHD Graphics 620                                                                   | 37        | 2.31%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 31        | 1.93%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 30        | 1.87%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 28        | 1.75%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 28        | 1.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 27        | 1.68%   |
| Intel HD Graphics 5500                                                                   | 26        | 1.62%   |
| AMD Renoir                                                                               | 25        | 1.56%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 23        | 1.43%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 23        | 1.43%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 22        | 1.37%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 22        | 1.37%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 21        | 1.31%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 17        | 1.06%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 17        | 1.06%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 16        | 1%      |
| Intel HD Graphics 630                                                                    | 15        | 0.94%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 15        | 0.94%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 12        | 0.75%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 12        | 0.75%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 12        | 0.75%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 11        | 0.69%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 11        | 0.69%   |
| Nvidia C79 [GeForce 9400M]                                                               | 10        | 0.62%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 10        | 0.62%   |
| Intel HD Graphics 530                                                                    | 10        | 0.62%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 10        | 0.62%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 10        | 0.62%   |
| AMD Lucienne                                                                             | 10        | 0.62%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 9         | 0.56%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 9         | 0.56%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 9         | 0.56%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 9         | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| 1 x Intel                      | 634       | 47.67%  |
| 1 x AMD                        | 272       | 20.45%  |
| 1 x Nvidia                     | 180       | 13.53%  |
| Intel + Nvidia                 | 154       | 11.58%  |
| Intel + AMD                    | 47        | 3.53%   |
| 2 x AMD                        | 25        | 1.88%   |
| AMD + Nvidia                   | 8         | 0.6%    |
| 2 x Nvidia                     | 5         | 0.38%   |
| Other                          | 2         | 0.15%   |
| 2 x AMD + 1 x Conexant Systems | 1         | 0.08%   |
| 1 x Matrox                     | 1         | 0.08%   |
| Intel + 2 x AMD                | 1         | 0.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1128      | 84.43%  |
| Proprietary | 188       | 14.07%  |
| Unknown     | 20        | 1.5%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 693       | 51.45%  |
| 1.01-2.0   | 209       | 15.52%  |
| 0.01-0.5   | 153       | 11.36%  |
| 0.51-1.0   | 117       | 8.69%   |
| 3.01-4.0   | 86        | 6.38%   |
| 7.01-8.0   | 45        | 3.34%   |
| 5.01-6.0   | 27        | 2%      |
| 8.01-16.0  | 9         | 0.67%   |
| 2.01-3.0   | 8         | 0.59%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 185       | 12.74%  |
| Samsung Electronics     | 159       | 10.95%  |
| LG Display              | 141       | 9.71%   |
| Chimei Innolux          | 135       | 9.3%    |
| BOE                     | 133       | 9.16%   |
| Apple                   | 113       | 7.78%   |
| Dell                    | 69        | 4.75%   |
| Hewlett-Packard         | 51        | 3.51%   |
| Goldstar                | 51        | 3.51%   |
| Acer                    | 38        | 2.62%   |
| AOC                     | 35        | 2.41%   |
| Sharp                   | 32        | 2.2%    |
| Lenovo                  | 31        | 2.13%   |
| BenQ                    | 25        | 1.72%   |
| Ancor Communications    | 22        | 1.52%   |
| Philips                 | 21        | 1.45%   |
| Chi Mei Optoelectronics | 21        | 1.45%   |
| LG Electronics          | 17        | 1.17%   |
| PANDA                   | 14        | 0.96%   |
| ViewSonic               | 11        | 0.76%   |
| Unknown                 | 9         | 0.62%   |
| Sony                    | 8         | 0.55%   |
| InfoVision              | 8         | 0.55%   |
| Vizio                   | 7         | 0.48%   |
| Panasonic               | 7         | 0.48%   |
| CSO                     | 6         | 0.41%   |
| Fujitsu Siemens         | 5         | 0.34%   |
| Toshiba                 | 4         | 0.28%   |
| NEC Computers           | 4         | 0.28%   |
| Iiyama                  | 4         | 0.28%   |
| CPT                     | 4         | 0.28%   |
| ___                     | 3         | 0.21%   |
| LG Philips              | 3         | 0.21%   |
| HPN                     | 3         | 0.21%   |
| HannStar                | 3         | 0.21%   |
| Eizo                    | 3         | 0.21%   |
| AUS                     | 3         | 0.21%   |
| Unknown                 | 3         | 0.21%   |
| Vestel                  | 2         | 0.14%   |
| Onkyo                   | 2         | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 11        | 0.74%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 9         | 0.6%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 8         | 0.54%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 8         | 0.54%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 8         | 0.54%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                     | 8         | 0.54%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 7         | 0.47%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 7         | 0.47%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 6         | 0.4%    |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 6         | 0.4%    |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 6         | 0.4%    |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 6         | 0.4%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 5         | 0.34%   |
| Panasonic LCD Monitor MEI96A2 2880x1620 344x193mm 15.5-inch              | 5         | 0.34%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch             | 5         | 0.34%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 5         | 0.34%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 5         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 5         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 5         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15B7 1366x768 344x193mm 15.5-inch          | 5         | 0.34%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 5         | 0.34%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                    | 5         | 0.34%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 5         | 0.34%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                   | 5         | 0.34%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                     | 5         | 0.34%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                     | 5         | 0.34%   |
| Apple Color LCD APP9CA4 1440x900 331x207mm 15.4-inch                     | 5         | 0.34%   |
| Apple Color LCD APP9C6B 1680x1050 433x270mm 20.1-inch                    | 5         | 0.34%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch        | 4         | 0.27%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 4         | 0.27%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x189mm 14.1-inch                  | 4         | 0.27%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 4         | 0.27%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 4         | 0.27%   |
| Goldstar 20EN33 GSM4EE1 1600x900 443x249mm 20.0-inch                     | 4         | 0.27%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 4         | 0.27%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch          | 4         | 0.27%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch | 4         | 0.27%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 4         | 0.27%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 4         | 0.27%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 4         | 0.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 552       | 39.4%   |
| 1366x768 (WXGA)    | 329       | 23.48%  |
| 3840x2160 (4K)     | 77        | 5.5%    |
| 1600x900 (HD+)     | 73        | 5.21%   |
| 2560x1440 (QHD)    | 58        | 4.14%   |
| 1280x800 (WXGA)    | 52        | 3.71%   |
| 1680x1050 (WSXGA+) | 45        | 3.21%   |
| 1440x900 (WXGA+)   | 43        | 3.07%   |
| 1280x1024 (SXGA)   | 25        | 1.78%   |
| 1920x1200 (WUXGA)  | 22        | 1.57%   |
| Unknown            | 17        | 1.21%   |
| 2880x1800          | 12        | 0.86%   |
| 2560x1600          | 11        | 0.79%   |
| 3840x1080          | 10        | 0.71%   |
| 2560x1080          | 8         | 0.57%   |
| 1360x768           | 8         | 0.57%   |
| 3440x1440          | 5         | 0.36%   |
| 3000x2000          | 5         | 0.36%   |
| 1600x1200          | 4         | 0.29%   |
| 1024x600           | 4         | 0.29%   |
| 5120x1440          | 3         | 0.21%   |
| 3840x2400          | 3         | 0.21%   |
| 2736x1824          | 3         | 0.21%   |
| 1920x540           | 3         | 0.21%   |
| 1920x1280          | 3         | 0.21%   |
| 3200x1800 (QHD+)   | 2         | 0.14%   |
| 2160x1440          | 2         | 0.14%   |
| 7680x2160          | 1         | 0.07%   |
| 7680x1600          | 1         | 0.07%   |
| 5760x2160          | 1         | 0.07%   |
| 5760x1080          | 1         | 0.07%   |
| 4480x1440          | 1         | 0.07%   |
| 4240x1080          | 1         | 0.07%   |
| 3968x1280          | 1         | 0.07%   |
| 3840x1600          | 1         | 0.07%   |
| 3840x1200          | 1         | 0.07%   |
| 3840x1100          | 1         | 0.07%   |
| 3600x1080          | 1         | 0.07%   |
| 3072x1920          | 1         | 0.07%   |
| 2880x1920          | 1         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 367       | 25.33%  |
| 13      | 208       | 14.35%  |
| 14      | 137       | 9.45%   |
| Unknown | 99        | 6.83%   |
| 27      | 78        | 5.38%   |
| 17      | 74        | 5.11%   |
| 24      | 72        | 4.97%   |
| 23      | 65        | 4.49%   |
| 21      | 63        | 4.35%   |
| 11      | 31        | 2.14%   |
| 20      | 30        | 2.07%   |
| 19      | 29        | 2%      |
| 12      | 26        | 1.79%   |
| 31      | 24        | 1.66%   |
| 22      | 22        | 1.52%   |
| 18      | 20        | 1.38%   |
| 84      | 11        | 0.76%   |
| 10      | 10        | 0.69%   |
| 72      | 9         | 0.62%   |
| 34      | 9         | 0.62%   |
| 32      | 8         | 0.55%   |
| 16      | 8         | 0.55%   |
| 25      | 7         | 0.48%   |
| 54      | 4         | 0.28%   |
| 33      | 4         | 0.28%   |
| 48      | 3         | 0.21%   |
| 29      | 3         | 0.21%   |
| 26      | 3         | 0.21%   |
| 65      | 2         | 0.14%   |
| 52      | 2         | 0.14%   |
| 49      | 2         | 0.14%   |
| 43      | 2         | 0.14%   |
| 40      | 2         | 0.14%   |
| 38      | 2         | 0.14%   |
| 37      | 2         | 0.14%   |
| 36      | 2         | 0.14%   |
| 28      | 2         | 0.14%   |
| 74      | 1         | 0.07%   |
| 69      | 1         | 0.07%   |
| 60      | 1         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 597       | 41.95%  |
| 501-600     | 199       | 13.98%  |
| 201-300     | 185       | 13%     |
| 401-500     | 147       | 10.33%  |
| Unknown     | 99        | 6.96%   |
| 351-400     | 85        | 5.97%   |
| 601-700     | 40        | 2.81%   |
| 701-800     | 23        | 1.62%   |
| 1501-2000   | 22        | 1.55%   |
| 1001-1500   | 17        | 1.19%   |
| 801-900     | 7         | 0.49%   |
| 901-1000    | 2         | 0.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 969       | 73.8%   |
| 16/10   | 183       | 13.94%  |
| Unknown | 91        | 6.93%   |
| 3/2     | 24        | 1.83%   |
| 5/4     | 22        | 1.68%   |
| 21/9    | 12        | 0.91%   |
| 4/3     | 5         | 0.38%   |
| 32/9    | 3         | 0.23%   |
| 6/5     | 1         | 0.08%   |
| 3.73    | 1         | 0.08%   |
| 3.40    | 1         | 0.08%   |
| 1.96    | 1         | 0.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 367       | 25.57%  |
| 81-90          | 262       | 18.26%  |
| 201-250        | 169       | 11.78%  |
| Unknown        | 99        | 6.9%    |
| 71-80          | 84        | 5.85%   |
| 301-350        | 80        | 5.57%   |
| 151-200        | 75        | 5.23%   |
| 121-130        | 51        | 3.55%   |
| 351-500        | 47        | 3.28%   |
| 251-300        | 36        | 2.51%   |
| More than 1000 | 34        | 2.37%   |
| 51-60          | 32        | 2.23%   |
| 141-150        | 31        | 2.16%   |
| 61-70          | 24        | 1.67%   |
| 501-1000       | 16        | 1.11%   |
| 41-50          | 10        | 0.7%    |
| 131-140        | 10        | 0.7%    |
| 111-120        | 6         | 0.42%   |
| 91-100         | 2         | 0.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 433       | 30.93%  |
| 121-160       | 385       | 27.5%   |
| 51-100        | 336       | 24%     |
| Unknown       | 99        | 7.07%   |
| 161-240       | 85        | 6.07%   |
| More than 240 | 33        | 2.36%   |
| 1-50          | 29        | 2.07%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1136      | 84.15%  |
| 2     | 172       | 12.74%  |
| 3     | 22        | 1.63%   |
| 0     | 19        | 1.41%   |
| 4     | 1         | 0.07%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 679       | 33.6%   |
| Intel                             | 569       | 28.15%  |
| Qualcomm Atheros                  | 250       | 12.37%  |
| Broadcom                          | 198       | 9.8%    |
| Marvell Technology Group          | 39        | 1.93%   |
| Broadcom Limited                  | 38        | 1.88%   |
| Nvidia                            | 31        | 1.53%   |
| TP-Link                           | 28        | 1.39%   |
| Ralink Technology                 | 22        | 1.09%   |
| Ralink                            | 19        | 0.94%   |
| Samsung Electronics               | 12        | 0.59%   |
| Xiaomi                            | 11        | 0.54%   |
| MediaTek                          | 11        | 0.54%   |
| Huawei Technologies               | 9         | 0.45%   |
| D-Link                            | 9         | 0.45%   |
| Sierra Wireless                   | 8         | 0.4%    |
| ASIX Electronics                  | 8         | 0.4%    |
| Qualcomm Atheros Communications   | 5         | 0.25%   |
| OPPO Electronics                  | 5         | 0.25%   |
| Qualcomm                          | 4         | 0.2%    |
| Microsoft                         | 4         | 0.2%    |
| Linksys                           | 4         | 0.2%    |
| Hewlett-Packard                   | 4         | 0.2%    |
| Google                            | 4         | 0.2%    |
| Ericsson Business Mobile Networks | 4         | 0.2%    |
| D-Link System                     | 4         | 0.2%    |
| Lenovo                            | 3         | 0.15%   |
| TRENDnet                          | 2         | 0.1%    |
| LG Electronics                    | 2         | 0.1%    |
| JMicron Technology                | 2         | 0.1%    |
| Fibocom                           | 2         | 0.1%    |
| Edimax Technology                 | 2         | 0.1%    |
| ASUSTek Computer                  | 2         | 0.1%    |
| Apple                             | 2         | 0.1%    |
| ZyXEL Communications              | 1         | 0.05%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.05%   |
| vivo                              | 1         | 0.05%   |
| VIA Technologies                  | 1         | 0.05%   |
| Toshiba                           | 1         | 0.05%   |
| Sundance Technology Inc / IC Plus | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 448       | 18.81%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 104       | 4.37%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 49        | 2.06%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 48        | 2.02%   |
| Intel Wi-Fi 6 AX200                                               | 44        | 1.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 39        | 1.64%   |
| Intel Wireless 8260                                               | 38        | 1.6%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 37        | 1.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 33        | 1.39%   |
| Intel Wireless 8265 / 8275                                        | 31        | 1.3%    |
| Intel Wi-Fi 6 AX201                                               | 31        | 1.3%    |
| Intel Wireless 7260                                               | 29        | 1.22%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 27        | 1.13%   |
| Intel Wireless 7265                                               | 27        | 1.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 26        | 1.09%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 26        | 1.09%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 25        | 1.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 24        | 1.01%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 22        | 0.92%   |
| Intel I211 Gigabit Network Connection                             | 21        | 0.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 19        | 0.8%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 18        | 0.76%   |
| Intel Wireless 3165                                               | 18        | 0.76%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 18        | 0.76%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 17        | 0.71%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 17        | 0.71%   |
| Broadcom BCM4321 802.11a/b/g/n                                    | 17        | 0.71%   |
| Nvidia MCP79 Ethernet                                             | 16        | 0.67%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 16        | 0.67%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 16        | 0.67%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 15        | 0.63%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 15        | 0.63%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 15        | 0.63%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 15        | 0.63%   |
| Ralink MT7601U Wireless Adapter                                   | 14        | 0.59%   |
| Intel Ethernet Connection I217-LM                                 | 14        | 0.59%   |
| Intel Ethernet Connection (2) I219-V                              | 14        | 0.59%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 14        | 0.59%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 14        | 0.59%   |
| Broadcom BCM43142 802.11b/g/n                                     | 14        | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 457       | 38.34%  |
| Qualcomm Atheros                | 211       | 17.7%   |
| Realtek Semiconductor           | 200       | 16.78%  |
| Broadcom                        | 159       | 13.34%  |
| Broadcom Limited                | 34        | 2.85%   |
| TP-Link                         | 28        | 2.35%   |
| Ralink Technology               | 22        | 1.85%   |
| Ralink                          | 19        | 1.59%   |
| Sierra Wireless                 | 8         | 0.67%   |
| Marvell Technology Group        | 8         | 0.67%   |
| D-Link                          | 7         | 0.59%   |
| MediaTek                        | 6         | 0.5%    |
| Qualcomm Atheros Communications | 5         | 0.42%   |
| Microsoft                       | 4         | 0.34%   |
| Linksys                         | 3         | 0.25%   |
| D-Link System                   | 3         | 0.25%   |
| TRENDnet                        | 2         | 0.17%   |
| Fibocom                         | 2         | 0.17%   |
| Edimax Technology               | 2         | 0.17%   |
| ASUSTek Computer                | 2         | 0.17%   |
| ZyXEL Communications            | 1         | 0.08%   |
| Sitecom Europe                  | 1         | 0.08%   |
| Qualcomm                        | 1         | 0.08%   |
| NetGear                         | 1         | 0.08%   |
| Mercucys                        | 1         | 0.08%   |
| LG Electronics                  | 1         | 0.08%   |
| BUFFALO                         | 1         | 0.08%   |
| AVM                             | 1         | 0.08%   |
| AirTies Wireless Networks       | 1         | 0.08%   |
| AboCom Systems                  | 1         | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 49        | 4.08%   |
| Intel Wi-Fi 6 AX200                                            | 44        | 3.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 39        | 3.25%   |
| Intel Wireless 8260                                            | 38        | 3.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 37        | 3.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 33        | 2.75%   |
| Intel Wireless 8265 / 8275                                     | 31        | 2.58%   |
| Intel Wi-Fi 6 AX201                                            | 31        | 2.58%   |
| Intel Wireless 7260                                            | 29        | 2.42%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 27        | 2.25%   |
| Intel Wireless 7265                                            | 27        | 2.25%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 26        | 2.17%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 26        | 2.17%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 24        | 2%      |
| Broadcom BCM4331 802.11a/b/g/n                                 | 22        | 1.83%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 19        | 1.58%   |
| Intel Wireless 3165                                            | 18        | 1.5%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 18        | 1.5%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 17        | 1.42%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 17        | 1.42%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 17        | 1.42%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 16        | 1.33%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 16        | 1.33%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 15        | 1.25%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 15        | 1.25%   |
| Ralink MT7601U Wireless Adapter                                | 14        | 1.17%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 14        | 1.17%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 14        | 1.17%   |
| Broadcom BCM43142 802.11b/g/n                                  | 14        | 1.17%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 14        | 1.17%   |
| Intel Wireless 3160                                            | 13        | 1.08%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 13        | 1.08%   |
| Intel Centrino Advanced-N 6235                                 | 13        | 1.08%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 13        | 1.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 12        | 1%      |
| Realtek RTL8723DE Wireless Network Adapter                     | 11        | 0.92%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 11        | 0.92%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 11        | 0.92%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 11        | 0.92%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 10        | 0.83%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 595       | 51.74%  |
| Intel                             | 262       | 22.78%  |
| Broadcom                          | 84        | 7.3%    |
| Qualcomm Atheros                  | 63        | 5.48%   |
| Nvidia                            | 31        | 2.7%    |
| Marvell Technology Group          | 31        | 2.7%    |
| Samsung Electronics               | 12        | 1.04%   |
| Xiaomi                            | 11        | 0.96%   |
| ASIX Electronics                  | 8         | 0.7%    |
| Huawei Technologies               | 6         | 0.52%   |
| OPPO Electronics                  | 5         | 0.43%   |
| MediaTek                          | 5         | 0.43%   |
| Broadcom Limited                  | 5         | 0.43%   |
| Google                            | 4         | 0.35%   |
| Qualcomm                          | 3         | 0.26%   |
| Lenovo                            | 3         | 0.26%   |
| JMicron Technology                | 2         | 0.17%   |
| Hewlett-Packard                   | 2         | 0.17%   |
| D-Link                            | 2         | 0.17%   |
| Apple                             | 2         | 0.17%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.09%   |
| vivo                              | 1         | 0.09%   |
| VIA Technologies                  | 1         | 0.09%   |
| Sundance Technology Inc / IC Plus | 1         | 0.09%   |
| Motorola PCS                      | 1         | 0.09%   |
| LSI                               | 1         | 0.09%   |
| Linksys                           | 1         | 0.09%   |
| LG Electronics                    | 1         | 0.09%   |
| ICS Advent                        | 1         | 0.09%   |
| HMD Global                        | 1         | 0.09%   |
| DisplayLink                       | 1         | 0.09%   |
| D-Link System                     | 1         | 0.09%   |
| Attansic Technology               | 1         | 0.09%   |
| Aquantia                          | 1         | 0.09%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 448       | 38.39%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 104       | 8.91%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 48        | 4.11%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 25        | 2.14%   |
| Intel I211 Gigabit Network Connection                             | 21        | 1.8%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 18        | 1.54%   |
| Nvidia MCP79 Ethernet                                             | 16        | 1.37%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 15        | 1.29%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 15        | 1.29%   |
| Intel Ethernet Connection I217-LM                                 | 14        | 1.2%    |
| Intel Ethernet Connection (2) I219-V                              | 14        | 1.2%    |
| Realtek RTL8125 2.5GbE Controller                                 | 13        | 1.11%   |
| Intel 82577LM Gigabit Network Connection                          | 13        | 1.11%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 12        | 1.03%   |
| Intel Ethernet Connection I219-LM                                 | 11        | 0.94%   |
| Intel Ethernet Connection I218-LM                                 | 11        | 0.94%   |
| Intel Ethernet Connection (7) I219-V                              | 11        | 0.94%   |
| Intel 82579V Gigabit Network Connection                           | 11        | 0.94%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 11        | 0.94%   |
| Intel Ethernet Connection (4) I219-V                              | 10        | 0.86%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 9         | 0.77%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 8         | 0.69%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 8         | 0.69%   |
| Intel Ethernet Connection I217-V                                  | 8         | 0.69%   |
| Intel Ethernet Connection (3) I218-LM                             | 8         | 0.69%   |
| Intel 82574L Gigabit Network Connection                           | 8         | 0.69%   |
| Intel 82567LM Gigabit Network Connection                          | 8         | 0.69%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 7         | 0.6%    |
| Nvidia MCP61 Ethernet                                             | 7         | 0.6%    |
| Intel Ethernet Controller I225-V                                  | 7         | 0.6%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 6         | 0.51%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 6         | 0.51%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 6         | 0.51%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 5         | 0.43%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 5         | 0.43%   |
| OPPO RMX3263                                                      | 5         | 0.43%   |
| MediaTek Infinix NOTE 11                                          | 5         | 0.43%   |
| Intel Ethernet Connection I219-V                                  | 5         | 0.43%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 0.43%   |
| Intel Ethernet Connection (2) I219-LM                             | 5         | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1128      | 50.58%  |
| Ethernet | 1087      | 48.74%  |
| Modem    | 13        | 0.58%   |
| Unknown  | 2         | 0.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 902       | 67.36%  |
| Ethernet | 437       | 32.64%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 782       | 58.75%  |
| 1     | 497       | 37.34%  |
| 0     | 28        | 2.1%    |
| 3     | 21        | 1.58%   |
| 4     | 2         | 0.15%   |
| 5     | 1         | 0.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 1049      | 78.28%  |
| Yes     | 290       | 21.64%  |
| Unknown | 1         | 0.07%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 380       | 39.38%  |
| Apple                           | 122       | 12.64%  |
| Realtek Semiconductor           | 101       | 10.47%  |
| Qualcomm Atheros Communications | 81        | 8.39%   |
| Cambridge Silicon Radio         | 53        | 5.49%   |
| Broadcom                        | 52        | 5.39%   |
| Lite-On Technology              | 40        | 4.15%   |
| Foxconn / Hon Hai               | 29        | 3.01%   |
| IMC Networks                    | 25        | 2.59%   |
| Toshiba                         | 13        | 1.35%   |
| Ralink                          | 11        | 1.14%   |
| Dell                            | 11        | 1.14%   |
| Hewlett-Packard                 | 10        | 1.04%   |
| Marvell Semiconductor           | 9         | 0.93%   |
| ASUSTek Computer                | 9         | 0.93%   |
| Realtek                         | 8         | 0.83%   |
| Qcom                            | 3         | 0.31%   |
| Belkin Components               | 2         | 0.21%   |
| Unknown                         | 1         | 0.1%    |
| Taiyo Yuden                     | 1         | 0.1%    |
| Logitech                        | 1         | 0.1%    |
| Fujitsu                         | 1         | 0.1%    |
| Foxconn International           | 1         | 0.1%    |
| Edimax Technology               | 1         | 0.1%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 158       | 16.37%  |
| Intel AX201 Bluetooth                               | 67        | 6.94%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 63        | 6.53%   |
| Realtek Bluetooth Radio                             | 56        | 5.8%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 53        | 5.49%   |
| Apple Bluetooth Host Controller                     | 48        | 4.97%   |
| Qualcomm Atheros  Bluetooth Device                  | 45        | 4.66%   |
| Intel AX200 Bluetooth                               | 43        | 4.46%   |
| Apple Bluetooth USB Host Controller                 | 36        | 3.73%   |
| Realtek  Bluetooth 4.2 Adapter                      | 34        | 3.52%   |
| Apple Bluetooth HCI                                 | 20        | 2.07%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 18        | 1.87%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 17        | 1.76%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 17        | 1.76%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 14        | 1.45%   |
| Intel Wireless-AC 3168 Bluetooth                    | 12        | 1.24%   |
| Foxconn / Hon Hai Bluetooth Device                  | 12        | 1.24%   |
| Ralink RT3290 Bluetooth                             | 11        | 1.14%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 10        | 1.04%   |
| Broadcom BCM2045B (BDC-2.1)                         | 10        | 1.04%   |
| Lite-On Bluetooth Device                            | 9         | 0.93%   |
| Lite-On Atheros AR3012 Bluetooth                    | 9         | 0.93%   |
| HP Broadcom 2070 Bluetooth Combo                    | 9         | 0.93%   |
| Realtek Bluetooth Radio                             | 8         | 0.83%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 8         | 0.83%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 8         | 0.83%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 7         | 0.73%   |
| Intel AX210 Bluetooth                               | 7         | 0.73%   |
| IMC Networks Bluetooth Radio                        | 7         | 0.73%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 6         | 0.62%   |
| Marvell Bluetooth and Wireless LAN Composite        | 6         | 0.62%   |
| IMC Networks Bluetooth Device                       | 6         | 0.62%   |
| Dell DW375 Bluetooth Module                         | 6         | 0.62%   |
| Realtek RTL8821A Bluetooth                          | 5         | 0.52%   |
| Realtek RTL8723B Bluetooth                          | 5         | 0.52%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 5         | 0.52%   |
| Toshiba RT Bluetooth Radio                          | 4         | 0.41%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 4         | 0.41%   |
| Lite-On Atheros Bluetooth                           | 4         | 0.41%   |
| IMC Networks Wireless_Device                        | 4         | 0.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1026      | 58.76%  |
| AMD                                  | 338       | 19.36%  |
| Nvidia                               | 246       | 14.09%  |
| C-Media Electronics                  | 34        | 1.95%   |
| Logitech                             | 13        | 0.74%   |
| Creative Labs                        | 12        | 0.69%   |
| Generalplus Technology               | 8         | 0.46%   |
| JMTek                                | 5         | 0.29%   |
| Texas Instruments                    | 4         | 0.23%   |
| GN Netcom                            | 4         | 0.23%   |
| Creative Technology                  | 4         | 0.23%   |
| BEHRINGER International              | 4         | 0.23%   |
| Realtek Semiconductor                | 3         | 0.17%   |
| Razer USA                            | 3         | 0.17%   |
| Corsair                              | 3         | 0.17%   |
| Plantronics                          | 2         | 0.11%   |
| Native Instruments                   | 2         | 0.11%   |
| Focusrite-Novation                   | 2         | 0.11%   |
| ESS Technology                       | 2         | 0.11%   |
| Dell                                 | 2         | 0.11%   |
| ASUSTek Computer                     | 2         | 0.11%   |
| YUAN High-Tech Development           | 1         | 0.06%   |
| Unknown                              | 1         | 0.06%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.06%   |
| Tenx Technology                      | 1         | 0.06%   |
| TEAC                                 | 1         | 0.06%   |
| SteelSeries ApS                      | 1         | 0.06%   |
| Sony                                 | 1         | 0.06%   |
| Sennheiser Communications            | 1         | 0.06%   |
| PreSonus Audio Electronics           | 1         | 0.06%   |
| Philips Speech Processing            | 1         | 0.06%   |
| No brand                             | 1         | 0.06%   |
| Microsoft                            | 1         | 0.06%   |
| Micro Star International             | 1         | 0.06%   |
| iCreate Technologies                 | 1         | 0.06%   |
| Huawei Technologies                  | 1         | 0.06%   |
| Hewlett-Packard                      | 1         | 0.06%   |
| Goldvish                             | 1         | 0.06%   |
| Fry's Electronics                    | 1         | 0.06%   |
| Fortemedia                           | 1         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 133       | 6.38%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 126       | 6.04%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 108       | 5.18%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 89        | 4.27%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 66        | 3.16%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 64        | 3.07%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 52        | 2.49%   |
| Intel 8 Series HD Audio Controller                                                                | 52        | 2.49%   |
| Intel Cannon Lake PCH cAVS                                                                        | 45        | 2.16%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 44        | 2.11%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 43        | 2.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 42        | 2.01%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 42        | 2.01%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 42        | 2.01%   |
| Intel Broadwell-U Audio Controller                                                                | 38        | 1.82%   |
| AMD FCH Azalia Controller                                                                         | 36        | 1.73%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 35        | 1.68%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 30        | 1.44%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 30        | 1.44%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 29        | 1.39%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 27        | 1.29%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 26        | 1.25%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 26        | 1.25%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 25        | 1.2%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 25        | 1.2%    |
| AMD Kabini HDMI/DP Audio                                                                          | 25        | 1.2%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 22        | 1.05%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 22        | 1.05%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 21        | 1.01%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 21        | 1.01%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 20        | 0.96%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 18        | 0.86%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 18        | 0.86%   |
| Intel 200 Series PCH HD Audio                                                                     | 18        | 0.86%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 18        | 0.86%   |
| Intel Comet Lake PCH cAVS                                                                         | 17        | 0.81%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 17        | 0.81%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 17        | 0.81%   |
| AMD High Definition Audio Controller                                                              | 17        | 0.81%   |
| Nvidia MCP79 High Definition Audio                                                                | 16        | 0.77%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 112       | 24.4%   |
| SK hynix            | 84        | 18.3%   |
| Kingston            | 54        | 11.76%  |
| Micron Technology   | 48        | 10.46%  |
| Unknown             | 39        | 8.5%    |
| Crucial             | 20        | 4.36%   |
| Elpida              | 12        | 2.61%   |
| Corsair             | 12        | 2.61%   |
| G.Skill             | 11        | 2.4%    |
| A-DATA Technology   | 9         | 1.96%   |
| Unknown (ABCD)      | 8         | 1.74%   |
| Ramaxel Technology  | 7         | 1.53%   |
| Patriot             | 4         | 0.87%   |
| Nanya Technology    | 4         | 0.87%   |
| Transcend           | 3         | 0.65%   |
| Smart               | 3         | 0.65%   |
| Team                | 2         | 0.44%   |
| PNY                 | 2         | 0.44%   |
| Multilaser          | 2         | 0.44%   |
| GSkill              | 2         | 0.44%   |
| Apacer              | 2         | 0.44%   |
| Unknown             | 2         | 0.44%   |
| Unknown (82B5)      | 1         | 0.22%   |
| Unknown (0x198)     | 1         | 0.22%   |
| Unknown (0x038A)    | 1         | 0.22%   |
| Toshiba             | 1         | 0.22%   |
| Timetec             | 1         | 0.22%   |
| Smart Brazil        | 1         | 0.22%   |
| SHARETRONIC         | 1         | 0.22%   |
| Qimonda             | 1         | 0.22%   |
| Neo Forza           | 1         | 0.22%   |
| Melco               | 1         | 0.22%   |
| Magnum Tech         | 1         | 0.22%   |
| Kllisre             | 1         | 0.22%   |
| Hewlett-Packard     | 1         | 0.22%   |
| Avant               | 1         | 0.22%   |
| AMD                 | 1         | 0.22%   |
| Aeneon              | 1         | 0.22%   |
| A Force             | 1         | 0.22%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 9         | 1.85%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 6         | 1.23%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 6         | 1.23%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 5         | 1.03%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 5         | 1.03%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.82%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 0.82%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                   | 4         | 0.82%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 4         | 0.82%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 0.82%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 4         | 0.82%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1066MT/s                   | 3         | 0.62%   |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                  | 3         | 0.62%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 0.62%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 0.62%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 3         | 0.62%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 0.62%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.62%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 3         | 0.62%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s            | 3         | 0.62%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 3         | 0.62%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.62%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 3         | 0.62%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.62%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 3         | 0.62%   |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s            | 3         | 0.62%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 3         | 0.62%   |
| Micron RAM 4ATF51264HZ-2G3AZ 4GB SODIMM DDR4 2133MT/s            | 3         | 0.62%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                             | 2         | 0.41%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 2         | 0.41%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 2         | 0.41%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 2         | 0.41%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s                    | 2         | 0.41%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s                      | 2         | 0.41%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 2         | 0.41%   |
| Smart RAM SG564568FG8NWKF-Z1 2GB SODIMM DDR2 800MT/s             | 2         | 0.41%   |
| Smart RAM SG564283FG8NWKF-Z1 1024MB SODIMM DDR2 800MT/s          | 2         | 0.41%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.41%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 0.41%   |
| SK hynix RAM HMT31GR7BFR4C-H9 8GB DIMM DDR3 1333MT/s             | 2         | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 163       | 42.78%  |
| DDR4    | 145       | 38.06%  |
| DDR2    | 23        | 6.04%   |
| LPDDR4  | 22        | 5.77%   |
| LPDDR3  | 11        | 2.89%   |
| SDRAM   | 9         | 2.36%   |
| Unknown | 7         | 1.84%   |
| DDR     | 1         | 0.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 271       | 70.76%  |
| DIMM         | 81        | 21.15%  |
| Row Of Chips | 25        | 6.53%   |
| Chip         | 4         | 1.04%   |
| FB-DIMM      | 1         | 0.26%   |
| Unknown      | 1         | 0.26%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 163       | 37.3%   |
| 4096  | 140       | 32.04%  |
| 2048  | 70        | 16.02%  |
| 16384 | 44        | 10.07%  |
| 1024  | 14        | 3.2%    |
| 32768 | 5         | 1.14%   |
| 512   | 1         | 0.23%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 101       | 23.93%  |
| 2667    | 65        | 15.4%   |
| 3200    | 37        | 8.77%   |
| 1333    | 37        | 8.77%   |
| 2400    | 32        | 7.58%   |
| 2133    | 29        | 6.87%   |
| 1334    | 17        | 4.03%   |
| 667     | 13        | 3.08%   |
| 800     | 12        | 2.84%   |
| 1867    | 10        | 2.37%   |
| 1067    | 9         | 2.13%   |
| 1066    | 9         | 2.13%   |
| 4267    | 7         | 1.66%   |
| 3600    | 5         | 1.18%   |
| 3266    | 4         | 0.95%   |
| 8400    | 3         | 0.71%   |
| 4199    | 3         | 0.71%   |
| 3466    | 3         | 0.71%   |
| 1800    | 3         | 0.71%   |
| 4266    | 2         | 0.47%   |
| 3733    | 2         | 0.47%   |
| 3000    | 2         | 0.47%   |
| 1866    | 2         | 0.47%   |
| Unknown | 2         | 0.47%   |
| 4800    | 1         | 0.24%   |
| 3400    | 1         | 0.24%   |
| 3334    | 1         | 0.24%   |
| 3007    | 1         | 0.24%   |
| 2934    | 1         | 0.24%   |
| 2933    | 1         | 0.24%   |
| 2800    | 1         | 0.24%   |
| 2666    | 1         | 0.24%   |
| 2200    | 1         | 0.24%   |
| 2048    | 1         | 0.24%   |
| 1639    | 1         | 0.24%   |
| 975     | 1         | 0.24%   |
| 133     | 1         | 0.24%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Hewlett-Packard                 | 9         | 32.14%  |
| Brother Industries              | 6         | 21.43%  |
| Canon                           | 5         | 17.86%  |
| Seiko Epson                     | 2         | 7.14%   |
| Samsung Electronics             | 2         | 7.14%   |
| Xerox                           | 1         | 3.57%   |
| Prolific Technology             | 1         | 3.57%   |
| Dymo-CoStar                     | 1         | 3.57%   |
| cab Produkttechnik GmbH & Co KG | 1         | 3.57%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Samsung M2020 Series                     | 2         | 7.14%   |
| Xerox Phaser 3040                        | 1         | 3.57%   |
| Seiko Epson XP-200 Series                | 1         | 3.57%   |
| Seiko Epson ET-2600 Series               | 1         | 3.57%   |
| Prolific PL2305 Parallel Port            | 1         | 3.57%   |
| HP Printing Support                      | 1         | 3.57%   |
| HP OfficeJet 5200 series                 | 1         | 3.57%   |
| HP LaserJet Pro M202dw                   | 1         | 3.57%   |
| HP LaserJet M101-M106                    | 1         | 3.57%   |
| HP LaserJet 1320                         | 1         | 3.57%   |
| HP Ink Tank 110 series                   | 1         | 3.57%   |
| HP Deskjet F4500 series                  | 1         | 3.57%   |
| HP Deskjet 2050 J510                     | 1         | 3.57%   |
| HP Deskjet 1000 J110 series              | 1         | 3.57%   |
| Dymo-CoStar LabelWriter 450              | 1         | 3.57%   |
| Canon TR8500 series                      | 1         | 3.57%   |
| Canon PIXMA MX390 Series                 | 1         | 3.57%   |
| Canon PIXMA MG3600 Series                | 1         | 3.57%   |
| Canon PIXMA MG2500 Series                | 1         | 3.57%   |
| Canon G3000 series                       | 1         | 3.57%   |
| cab Produkttechnik GmbH & Co KG EOS2/300 | 1         | 3.57%   |
| Brother MFC-T910DW                       | 1         | 3.57%   |
| Brother MFC-T800W                        | 1         | 3.57%   |
| Brother MFC-L2750DW series               | 1         | 3.57%   |
| Brother MFC-J5335DW                      | 1         | 3.57%   |
| Brother HL-4140CN series                 | 1         | 3.57%   |
| Brother DCP-L2550DN series               | 1         | 3.57%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 2         | 66.67%  |
| Canon       | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1         | 33.33%  |
| Seiko Epson ES-H300 [GT-2500]                           | 1         | 33.33%  |
| Canon CanoScan LiDE 110                                 | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 205       | 22.04%  |
| Apple                                  | 93        | 10%     |
| Realtek Semiconductor                  | 84        | 9.03%   |
| IMC Networks                           | 76        | 8.17%   |
| Microdia                               | 58        | 6.24%   |
| Acer                                   | 57        | 6.13%   |
| Sunplus Innovation Technology          | 49        | 5.27%   |
| Quanta                                 | 44        | 4.73%   |
| Cheng Uei Precision Industry (Foxlink) | 37        | 3.98%   |
| Suyin                                  | 31        | 3.33%   |
| Logitech                               | 29        | 3.12%   |
| Syntek                                 | 25        | 2.69%   |
| Silicon Motion                         | 19        | 2.04%   |
| Alcor Micro                            | 19        | 2.04%   |
| Lite-On Technology                     | 17        | 1.83%   |
| Microsoft                              | 12        | 1.29%   |
| Lenovo                                 | 10        | 1.08%   |
| Ricoh                                  | 6         | 0.65%   |
| Luxvisions Innotech Limited            | 6         | 0.65%   |
| Importek                               | 5         | 0.54%   |
| Z-Star Microelectronics                | 4         | 0.43%   |
| LG Electronics                         | 4         | 0.43%   |
| Generalplus Technology                 | 4         | 0.43%   |
| Samsung Electronics                    | 3         | 0.32%   |
| Primax Electronics                     | 3         | 0.32%   |
| KYE Systems (Mouse Systems)            | 3         | 0.32%   |
| Cubeternet                             | 3         | 0.32%   |
| ALi                                    | 3         | 0.32%   |
| USB Camera                             | 2         | 0.22%   |
| Jieli Technology                       | 2         | 0.22%   |
| Foxconn / Hon Hai                      | 2         | 0.22%   |
| Y Media                                | 1         | 0.11%   |
| Unknown                                | 1         | 0.11%   |
| Teslong Camera                         | 1         | 0.11%   |
| SunplusIT                              | 1         | 0.11%   |
| Sony                                   | 1         | 0.11%   |
| Razer USA                              | 1         | 0.11%   |
| OmniVision Technologies                | 1         | 0.11%   |
| kingcome                               | 1         | 0.11%   |
| Hewlett-Packard                        | 1         | 0.11%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Chicony Integrated Camera             | 41        | 4.38%   |
| Apple Built-in iSight                 | 36        | 3.84%   |
| Realtek Integrated_Webcam_HD          | 27        | 2.88%   |
| Chicony HD Webcam                     | 24        | 2.56%   |
| IMC Networks USB2.0 HD UVC WebCam     | 23        | 2.45%   |
| IMC Networks Integrated Camera        | 20        | 2.13%   |
| Microdia Integrated_Webcam_HD         | 18        | 1.92%   |
| Apple FaceTime HD Camera              | 18        | 1.92%   |
| Apple FaceTime HD Camera (Built-in)   | 17        | 1.81%   |
| Acer Integrated Camera                | 14        | 1.49%   |
| Syntek Integrated Camera              | 13        | 1.39%   |
| Sunplus Integrated_Webcam_HD          | 13        | 1.39%   |
| Apple iPhone5/5C/5S/6                 | 13        | 1.39%   |
| Realtek USB Camera                    | 10        | 1.07%   |
| Realtek USB2.0 HD UVC WebCam          | 9         | 0.96%   |
| Lite-On Integrated Camera             | 9         | 0.96%   |
| Chicony HP HD Webcam [Fixed]          | 9         | 0.96%   |
| Acer Lenovo EasyCamera                | 9         | 0.96%   |
| Quanta HP Webcam                      | 8         | 0.85%   |
| Quanta HP TrueVision HD Camera        | 8         | 0.85%   |
| IMC Networks USB2.0 VGA UVC WebCam    | 8         | 0.85%   |
| Chicony USB 2.0 Camera                | 8         | 0.85%   |
| Chicony EasyCamera                    | 8         | 0.85%   |
| Sunplus HD WebCam                     | 7         | 0.75%   |
| Realtek Integrated Webcam             | 7         | 0.75%   |
| Logitech HD Pro Webcam C920           | 7         | 0.75%   |
| Chicony VGA WebCam                    | 7         | 0.75%   |
| Chicony HP HD Camera                  | 7         | 0.75%   |
| Syntek EasyCamera                     | 6         | 0.64%   |
| Sunplus Laptop_Integrated_Webcam_HD   | 6         | 0.64%   |
| Realtek HD WebCam                     | 6         | 0.64%   |
| Microdia USB 2.0 Camera               | 6         | 0.64%   |
| Microdia Integrated Webcam            | 6         | 0.64%   |
| Chicony TOSHIBA Web Camera - HD       | 6         | 0.64%   |
| Chicony HP Wide Vision HD Camera      | 6         | 0.64%   |
| Chicony HP Truevision HD              | 6         | 0.64%   |
| Chicony HP High Definition 1MP Webcam | 6         | 0.64%   |
| Chicony HP HD Webcam                  | 6         | 0.64%   |
| Alcor Micro USB 2.0 PC Camera         | 6         | 0.64%   |
| Acer EasyCamera                       | 6         | 0.64%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 56        | 35%     |
| Synaptics                  | 42        | 26.25%  |
| Shenzhen Goodix Technology | 22        | 13.75%  |
| LighTuning Technology      | 14        | 8.75%   |
| Upek                       | 10        | 6.25%   |
| Elan Microelectronics      | 7         | 4.38%   |
| AuthenTec                  | 6         | 3.75%   |
| STMicroelectronics         | 2         | 1.25%   |
| Focal-systems.Corp         | 1         | 0.63%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 15        | 9.38%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 13        | 8.13%   |
| Unknown                                                                    | 13        | 8.13%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 11        | 6.88%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 10        | 6.25%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 9         | 5.63%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 5%      |
| Validity Sensors VFS491                                                    | 6         | 3.75%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 6         | 3.75%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 5         | 3.13%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 3.13%   |
| Elan ELAN:Fingerprint                                                      | 5         | 3.13%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 2.5%    |
| Validity Sensors Synaptics WBDI                                            | 4         | 2.5%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 4         | 2.5%    |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 2.5%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 1.88%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 1.88%   |
| Synaptics  WBDI                                                            | 3         | 1.88%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 1.88%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 1.88%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 1.25%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 1.25%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 1.25%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 1.25%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 1.25%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 1.25%   |
| Elan ELAN:ARM-M4                                                           | 2         | 1.25%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.63%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.63%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.63%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 0.63%   |
| LighTuning Fingerprint Sensor                                              | 1         | 0.63%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 0.63%   |
| AuthenTec AES2810                                                          | 1         | 0.63%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 0.63%   |
| AuthenTec AES1600                                                          | 1         | 0.63%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 23        | 42.59%  |
| Alcor Micro                       | 15        | 27.78%  |
| O2 Micro                          | 5         | 9.26%   |
| Lenovo                            | 5         | 9.26%   |
| Upek                              | 3         | 5.56%   |
| VASCO Data Security International | 1         | 1.85%   |
| Gemalto (was Gemplus)             | 1         | 1.85%   |
| Chicony Electronics               | 1         | 1.85%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 15        | 27.78%  |
| Broadcom BCM5880 Secure Applications Processor                               | 11        | 20.37%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 6         | 11.11%  |
| Lenovo Integrated Smart Card Reader                                          | 5         | 9.26%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 7.41%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 5.56%   |
| Broadcom 5880                                                                | 3         | 5.56%   |
| Broadcom 58200                                                               | 3         | 5.56%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 1.85%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.85%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.85%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 1.85%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 982       | 72.96%  |
| 1     | 291       | 21.62%  |
| 2     | 63        | 4.68%   |
| 3     | 7         | 0.52%   |
| 4     | 2         | 0.15%   |
| 8     | 1         | 0.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 158       | 35.59%  |
| Net/wireless             | 77        | 17.34%  |
| Graphics card            | 57        | 12.84%  |
| Chipcard                 | 50        | 11.26%  |
| Multimedia controller    | 40        | 9.01%   |
| Bluetooth                | 13        | 2.93%   |
| Camera                   | 11        | 2.48%   |
| Sound                    | 8         | 1.8%    |
| Storage                  | 6         | 1.35%   |
| Net/ethernet             | 6         | 1.35%   |
| Communication controller | 5         | 1.13%   |
| Card reader              | 5         | 1.13%   |
| Unassigned class         | 3         | 0.68%   |
| Storage/raid             | 2         | 0.45%   |
| Network                  | 2         | 0.45%   |
| Storage/ide              | 1         | 0.23%   |

