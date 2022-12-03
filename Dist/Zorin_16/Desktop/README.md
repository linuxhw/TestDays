Zorin 16 - Tested Hardware & Statistics (Desktops)
--------------------------------------------------

A project to collect tested hardware configurations for Zorin 16.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 1217

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | G41M-S03                    | [763decb5d5](https://linux-hardware.org/?probe=763decb5d5) | Dec 01, 2022 |
| Apple         | Mac-F221BEC8                | [7f91a09589](https://linux-hardware.org/?probe=7f91a09589) | Dec 01, 2022 |
| HP            | 8433 11                     | [01f9a28da3](https://linux-hardware.org/?probe=01f9a28da3) | Dec 01, 2022 |
| OEM           | H110 Ver:2.21               | [ad7fffd9e3](https://linux-hardware.org/?probe=ad7fffd9e3) | Nov 30, 2022 |
| ASRock        | B450M Steel Legend          | [9d6aeff37c](https://linux-hardware.org/?probe=9d6aeff37c) | Nov 30, 2022 |
| OEM           | H110 Ver:2.21               | [2e7e420f42](https://linux-hardware.org/?probe=2e7e420f42) | Nov 29, 2022 |
| Gateway       | SX2851                      | [b408695def](https://linux-hardware.org/?probe=b408695def) | Nov 28, 2022 |
| ASUSTek       | M5A88-M                     | [f4b2035429](https://linux-hardware.org/?probe=f4b2035429) | Nov 28, 2022 |
| BESSTAR Te... | HM90                        | [eda49557ae](https://linux-hardware.org/?probe=eda49557ae) | Nov 27, 2022 |
| BESSTAR Te... | HM90                        | [6867d8eeaf](https://linux-hardware.org/?probe=6867d8eeaf) | Nov 27, 2022 |
| Megaware      | MW-NM70HD-MI 01/13/2013 ... | [95b48709fd](https://linux-hardware.org/?probe=95b48709fd) | Nov 26, 2022 |
| Huanan        | X99-8M-F V1.1               | [88db74df98](https://linux-hardware.org/?probe=88db74df98) | Nov 26, 2022 |
| Gigabyte      | GA-890GPA-UD3H              | [5b531b7b41](https://linux-hardware.org/?probe=5b531b7b41) | Nov 26, 2022 |
| ASRock        | B450M Pro4                  | [def104dd7d](https://linux-hardware.org/?probe=def104dd7d) | Nov 26, 2022 |
| Huanan        | X99-8M-F V1.1               | [3ca25803b5](https://linux-hardware.org/?probe=3ca25803b5) | Nov 25, 2022 |
| Pegatron      | 2ACF                        | [dc9d24ac01](https://linux-hardware.org/?probe=dc9d24ac01) | Nov 25, 2022 |
| Pegatron      | 2ACF                        | [037b47ab43](https://linux-hardware.org/?probe=037b47ab43) | Nov 25, 2022 |
| HP            | 18E7                        | [048d4bd3ae](https://linux-hardware.org/?probe=048d4bd3ae) | Nov 25, 2022 |
| Dell          | 0T10XW A02                  | [83daa0cf15](https://linux-hardware.org/?probe=83daa0cf15) | Nov 25, 2022 |
| Gigabyte      | H110M-H-CF                  | [c43b60c09b](https://linux-hardware.org/?probe=c43b60c09b) | Nov 25, 2022 |
| Gigabyte      | B560 DS3H AC-Y1             | [6bcefa911d](https://linux-hardware.org/?probe=6bcefa911d) | Nov 24, 2022 |
| Gigabyte      | EG41MF-US2H                 | [07ac3ace2c](https://linux-hardware.org/?probe=07ac3ace2c) | Nov 24, 2022 |
| ASRock        | FP6D4-P1                    | [5e52f1b520](https://linux-hardware.org/?probe=5e52f1b520) | Nov 24, 2022 |
| MSI           | Z490-A PRO                  | [9154fdbc9e](https://linux-hardware.org/?probe=9154fdbc9e) | Nov 24, 2022 |
| ASRock        | Z170 Pro4                   | [ac6ad8d54d](https://linux-hardware.org/?probe=ac6ad8d54d) | Nov 24, 2022 |
| Dell          | 0HN7XN A01                  | [5357d43f13](https://linux-hardware.org/?probe=5357d43f13) | Nov 23, 2022 |
| ASRock        | B450M-HDV R4.0              | [9dbd34c7bd](https://linux-hardware.org/?probe=9dbd34c7bd) | Nov 23, 2022 |
| ASRock        | B450M-HDV R4.0              | [5786af4776](https://linux-hardware.org/?probe=5786af4776) | Nov 23, 2022 |
| Intel         | D946GZAB AAD66610-302       | [5433ee5bc1](https://linux-hardware.org/?probe=5433ee5bc1) | Nov 22, 2022 |
| HP            | 8184 X4                     | [f38ad9d963](https://linux-hardware.org/?probe=f38ad9d963) | Nov 21, 2022 |
| HP            | 822A                        | [b464dc4cf0](https://linux-hardware.org/?probe=b464dc4cf0) | Nov 21, 2022 |
| Acer          | Veriton N4640G              | [a7984c4a95](https://linux-hardware.org/?probe=a7984c4a95) | Nov 20, 2022 |
| Gigabyte      | Z68X-UD3H-B3                | [cd0f904ca4](https://linux-hardware.org/?probe=cd0f904ca4) | Nov 20, 2022 |
| Gigabyte      | Z68X-UD3H-B3                | [c4bd142690](https://linux-hardware.org/?probe=c4bd142690) | Nov 20, 2022 |
| Gigabyte      | GA-890GPA-UD3H              | [41cca3d850](https://linux-hardware.org/?probe=41cca3d850) | Nov 20, 2022 |
| MSI           | Z77A-G43                    | [2033b97419](https://linux-hardware.org/?probe=2033b97419) | Nov 19, 2022 |
| Acer          | FX58M                       | [837da7d885](https://linux-hardware.org/?probe=837da7d885) | Nov 19, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | [b40e651ff2](https://linux-hardware.org/?probe=b40e651ff2) | Nov 18, 2022 |
| Dell          | 0HN7XN A00                  | [3e217adbf8](https://linux-hardware.org/?probe=3e217adbf8) | Nov 18, 2022 |
| ASUSTek       | PRIME H370-A                | [0c4442c160](https://linux-hardware.org/?probe=0c4442c160) | Nov 18, 2022 |
| Dell          | 0C27VV A02                  | [5f4b4b8571](https://linux-hardware.org/?probe=5f4b4b8571) | Nov 18, 2022 |
| MSI           | H81M-P33                    | [a535339292](https://linux-hardware.org/?probe=a535339292) | Nov 17, 2022 |
| MSI           | 2AE0                        | [c0d9e23faa](https://linux-hardware.org/?probe=c0d9e23faa) | Nov 16, 2022 |
| MSI           | H81M-P33                    | [246d594268](https://linux-hardware.org/?probe=246d594268) | Nov 16, 2022 |
| HP            | 0AA4h                       | [328259669b](https://linux-hardware.org/?probe=328259669b) | Nov 16, 2022 |
| ASUSTek       | PRIME H370-A                | [9a93c5f349](https://linux-hardware.org/?probe=9a93c5f349) | Nov 15, 2022 |
| ASUSTek       | H110M-A                     | [d1e60135e1](https://linux-hardware.org/?probe=d1e60135e1) | Nov 15, 2022 |
| HP            | 18E7                        | [7ecd6a2f37](https://linux-hardware.org/?probe=7ecd6a2f37) | Nov 15, 2022 |
| Dell          | 0478VN A00                  | [5d1cf4ca11](https://linux-hardware.org/?probe=5d1cf4ca11) | Nov 14, 2022 |
| Gigabyte      | H510M H                     | [97b0a5f239](https://linux-hardware.org/?probe=97b0a5f239) | Nov 14, 2022 |
| HP            | 1850                        | [0b5e36c27b](https://linux-hardware.org/?probe=0b5e36c27b) | Nov 13, 2022 |
| Mediacom      | M-AO241/64                  | [8c577b3d8f](https://linux-hardware.org/?probe=8c577b3d8f) | Nov 13, 2022 |
| ASUSTek       | H110M-A                     | [1c7b3f934d](https://linux-hardware.org/?probe=1c7b3f934d) | Nov 12, 2022 |
| Fujitsu Si... | MS-7304VP-A13               | [69b1471202](https://linux-hardware.org/?probe=69b1471202) | Nov 12, 2022 |
| JGINYUE       | X79M-PLUS V2.3              | [8dac2a9292](https://linux-hardware.org/?probe=8dac2a9292) | Nov 12, 2022 |
| Dell          | 018D1Y A00                  | [16247a3667](https://linux-hardware.org/?probe=16247a3667) | Nov 12, 2022 |
| Dell          | 018D1Y A00                  | [bc5562e288](https://linux-hardware.org/?probe=bc5562e288) | Nov 12, 2022 |
| Biostar       | TPower X58                  | [8662697d27](https://linux-hardware.org/?probe=8662697d27) | Nov 11, 2022 |
| Mediacom      | M-AO241/64                  | [d0cac7ee7b](https://linux-hardware.org/?probe=d0cac7ee7b) | Nov 10, 2022 |
| Mediacom      | M-AO241/64                  | [cf0ed7acab](https://linux-hardware.org/?probe=cf0ed7acab) | Nov 10, 2022 |
| Dell          | 0HN7XN A01                  | [bb4dff706b](https://linux-hardware.org/?probe=bb4dff706b) | Nov 10, 2022 |
| Gigabyte      | B75M-D3H                    | [b7619dbd72](https://linux-hardware.org/?probe=b7619dbd72) | Nov 10, 2022 |
| MSI           | A320M-A PRO MAX             | [c3aaf6eed2](https://linux-hardware.org/?probe=c3aaf6eed2) | Nov 09, 2022 |
| MSI           | A320M-A PRO MAX             | [5030ff83c2](https://linux-hardware.org/?probe=5030ff83c2) | Nov 08, 2022 |
| MSI           | H81M-P33                    | [2ef23ed4ac](https://linux-hardware.org/?probe=2ef23ed4ac) | Nov 07, 2022 |
| Acer          | H81H3-M4                    | [40c67913d8](https://linux-hardware.org/?probe=40c67913d8) | Nov 06, 2022 |
| ASRock        | B660M Steel Legend          | [708d98bf92](https://linux-hardware.org/?probe=708d98bf92) | Nov 06, 2022 |
| ASRock        | B660M Steel Legend          | [2fce0b247c](https://linux-hardware.org/?probe=2fce0b247c) | Nov 06, 2022 |
| Gigabyte      | 990XA-UD3                   | [a06275a0f2](https://linux-hardware.org/?probe=a06275a0f2) | Nov 05, 2022 |
| HP            | 1790                        | [8916928344](https://linux-hardware.org/?probe=8916928344) | Nov 05, 2022 |
| HP            | 1790                        | [1de8a8af0d](https://linux-hardware.org/?probe=1de8a8af0d) | Nov 05, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [507697b22f](https://linux-hardware.org/?probe=507697b22f) | Nov 04, 2022 |
| Dell          | 0C27VV A02                  | [fb4c1f85a2](https://linux-hardware.org/?probe=fb4c1f85a2) | Nov 04, 2022 |
| Dell          | 0HN7XN A01                  | [baf6b79b85](https://linux-hardware.org/?probe=baf6b79b85) | Nov 03, 2022 |
| MSI           | A320M PRO-VD/S              | [920c4567d3](https://linux-hardware.org/?probe=920c4567d3) | Nov 03, 2022 |
| ASUSTek       | P7H55-M LE                  | [383066ca1c](https://linux-hardware.org/?probe=383066ca1c) | Nov 02, 2022 |
| ASUSTek       | P7H55-M LE                  | [66acf8991e](https://linux-hardware.org/?probe=66acf8991e) | Nov 02, 2022 |
| Dell          | 0GDG8Y A00                  | [609ccd3204](https://linux-hardware.org/?probe=609ccd3204) | Nov 02, 2022 |
| Gigabyte      | P55-UD6                     | [2898ec20b3](https://linux-hardware.org/?probe=2898ec20b3) | Nov 01, 2022 |
| Lenovo        | ThinkCentre M55E 898578G    | [d025c115d8](https://linux-hardware.org/?probe=d025c115d8) | Nov 01, 2022 |
| ASUSTek       | PRIME Z690-P D4             | [21213fdeec](https://linux-hardware.org/?probe=21213fdeec) | Oct 31, 2022 |
| HP            | 1790                        | [6dc2cef5ea](https://linux-hardware.org/?probe=6dc2cef5ea) | Oct 31, 2022 |
| Seco          | C40 C                       | [08509c30b6](https://linux-hardware.org/?probe=08509c30b6) | Oct 31, 2022 |
| ASUSTek       | PRIME H370-A                | [f7dd154c47](https://linux-hardware.org/?probe=f7dd154c47) | Oct 30, 2022 |
| Gigabyte      | B450M DS3H V2               | [97d7d8c2d9](https://linux-hardware.org/?probe=97d7d8c2d9) | Oct 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [ae6fd2de89](https://linux-hardware.org/?probe=ae6fd2de89) | Oct 29, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [068d4ec2e6](https://linux-hardware.org/?probe=068d4ec2e6) | Oct 29, 2022 |
| Dell          | 0T2HR0 A02                  | [e4b1137777](https://linux-hardware.org/?probe=e4b1137777) | Oct 29, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [2c57f9b6a3](https://linux-hardware.org/?probe=2c57f9b6a3) | Oct 29, 2022 |
| ASUSTek       | STRIX X99 GAMING            | [f111078004](https://linux-hardware.org/?probe=f111078004) | Oct 29, 2022 |
| MSI           | B560M PRO                   | [a84dc6f9cb](https://linux-hardware.org/?probe=a84dc6f9cb) | Oct 29, 2022 |
| ASUSTek       | STRIX X99 GAMING            | [b683357ec4](https://linux-hardware.org/?probe=b683357ec4) | Oct 28, 2022 |
| Gateway       | SX2851                      | [500b4bb8ec](https://linux-hardware.org/?probe=500b4bb8ec) | Oct 27, 2022 |
| ASUSTek       | P8H61/USB3                  | [c20c97e43e](https://linux-hardware.org/?probe=c20c97e43e) | Oct 27, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [7a0f5285f2](https://linux-hardware.org/?probe=7a0f5285f2) | Oct 26, 2022 |
| ASUSTek       | PRIME Z690-P D4             | [5bc9d4bdc8](https://linux-hardware.org/?probe=5bc9d4bdc8) | Oct 26, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [bb655d6ea7](https://linux-hardware.org/?probe=bb655d6ea7) | Oct 25, 2022 |
| Lenovo        | MAHOBAY NOK                 | [91437ee9a7](https://linux-hardware.org/?probe=91437ee9a7) | Oct 25, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [aa82a1f3c9](https://linux-hardware.org/?probe=aa82a1f3c9) | Oct 24, 2022 |
| Gigabyte      | Z77-DS3H                    | [e894ec1b8d](https://linux-hardware.org/?probe=e894ec1b8d) | Oct 24, 2022 |
| Gigabyte      | Z390 UD                     | [17adb9ee1e](https://linux-hardware.org/?probe=17adb9ee1e) | Oct 23, 2022 |
| Gigabyte      | GA-78LMT-S2                 | [dad9e03a82](https://linux-hardware.org/?probe=dad9e03a82) | Oct 23, 2022 |
| OEM           | G41 775 ICH7 8712           | [1f3d807ceb](https://linux-hardware.org/?probe=1f3d807ceb) | Oct 23, 2022 |
| Dell          | 0JP3NX A01                  | [86365f2c05](https://linux-hardware.org/?probe=86365f2c05) | Oct 23, 2022 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | [6a42097b41](https://linux-hardware.org/?probe=6a42097b41) | Oct 23, 2022 |
| ASUSTek       | PRIME X570-PRO              | [9035fff7ea](https://linux-hardware.org/?probe=9035fff7ea) | Oct 23, 2022 |
| Dell          | 0200DY A02                  | [8fd4b48b80](https://linux-hardware.org/?probe=8fd4b48b80) | Oct 23, 2022 |
| ASUSTek       | PRIME X570-PRO              | [3d2171b17e](https://linux-hardware.org/?probe=3d2171b17e) | Oct 23, 2022 |
| Dell          | 0HN7XN A01                  | [4e75c878a3](https://linux-hardware.org/?probe=4e75c878a3) | Oct 22, 2022 |
| OEM           | G41 775 ICH7 8712           | [f43a04f63f](https://linux-hardware.org/?probe=f43a04f63f) | Oct 21, 2022 |
| Gigabyte      | GA-78LMT-S2 sex             | [95ddb7c758](https://linux-hardware.org/?probe=95ddb7c758) | Oct 21, 2022 |
| OEM           | G41 775 ICH7 8712           | [354afbd4d8](https://linux-hardware.org/?probe=354afbd4d8) | Oct 20, 2022 |
| OEM           | G41 775 ICH7 8712           | [2991e146ce](https://linux-hardware.org/?probe=2991e146ce) | Oct 19, 2022 |
| ASRock        | 970 Extreme3                | [23f7ae20e3](https://linux-hardware.org/?probe=23f7ae20e3) | Oct 19, 2022 |
| Dell          | 0GTK4K A02                  | [f92314f74b](https://linux-hardware.org/?probe=f92314f74b) | Oct 18, 2022 |
| ASUSTek       | H97-PLUS                    | [0c025c3b68](https://linux-hardware.org/?probe=0c025c3b68) | Oct 16, 2022 |
| Gigabyte      | A320M-S2H-CF                | [c4a0f6af56](https://linux-hardware.org/?probe=c4a0f6af56) | Oct 16, 2022 |
| Gigabyte      | A320M-S2H-CF                | [cde8c87a3a](https://linux-hardware.org/?probe=cde8c87a3a) | Oct 16, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | [732c7afd4c](https://linux-hardware.org/?probe=732c7afd4c) | Oct 16, 2022 |
| HP            | 1790                        | [5b9b2357c5](https://linux-hardware.org/?probe=5b9b2357c5) | Oct 16, 2022 |
| Intel         | H55                         | [ab27a6c8d9](https://linux-hardware.org/?probe=ab27a6c8d9) | Oct 15, 2022 |
| HP            | 18E7                        | [98b59ebfce](https://linux-hardware.org/?probe=98b59ebfce) | Oct 13, 2022 |
| HP            | 0AA0h                       | [f4a69ac6f5](https://linux-hardware.org/?probe=f4a69ac6f5) | Oct 13, 2022 |
| HP            | 2AF3                        | [f59df65c18](https://linux-hardware.org/?probe=f59df65c18) | Oct 12, 2022 |
| Unknown       | Unknown                     | [bfd4bad69d](https://linux-hardware.org/?probe=bfd4bad69d) | Oct 11, 2022 |
| HP            | 304Ah                       | [69f11e2008](https://linux-hardware.org/?probe=69f11e2008) | Oct 11, 2022 |
| MSI           | B550-A PRO                  | [5c2dd967f9](https://linux-hardware.org/?probe=5c2dd967f9) | Oct 11, 2022 |
| Alienware     | 0NWN7M A00                  | [a7c3e67810](https://linux-hardware.org/?probe=a7c3e67810) | Oct 10, 2022 |
| Dell          | 0X9M3X A01                  | [b729cadad8](https://linux-hardware.org/?probe=b729cadad8) | Oct 10, 2022 |
| ASUSTek       | H81M-P                      | [907b7761d0](https://linux-hardware.org/?probe=907b7761d0) | Oct 09, 2022 |
| ASUSTek       | H81M-P                      | [f2d9df375d](https://linux-hardware.org/?probe=f2d9df375d) | Oct 09, 2022 |
| Unknown       | Unknown                     | [fef2c17618](https://linux-hardware.org/?probe=fef2c17618) | Oct 09, 2022 |
| Acer          | EM61SM/EM61PM               | [58d2cda88f](https://linux-hardware.org/?probe=58d2cda88f) | Oct 08, 2022 |
| ASUSTek       | CM1630                      | [dc63e03d48](https://linux-hardware.org/?probe=dc63e03d48) | Oct 08, 2022 |
| Gateway       | SX2851                      | [2cc7e399b2](https://linux-hardware.org/?probe=2cc7e399b2) | Oct 08, 2022 |
| HP            | 822A                        | [c893a1b314](https://linux-hardware.org/?probe=c893a1b314) | Oct 07, 2022 |
| Dell          | 0YP696 A00                  | [588d3a6132](https://linux-hardware.org/?probe=588d3a6132) | Oct 07, 2022 |
| HP            | 8265                        | [ddf5f03d86](https://linux-hardware.org/?probe=ddf5f03d86) | Oct 07, 2022 |
| HP            | 843B                        | [5a744e115f](https://linux-hardware.org/?probe=5a744e115f) | Oct 06, 2022 |
| Gigabyte      | B250M-D3H-CF                | [2e57f97484](https://linux-hardware.org/?probe=2e57f97484) | Oct 06, 2022 |
| HP            | 2B60 MVB                    | [092e063471](https://linux-hardware.org/?probe=092e063471) | Oct 05, 2022 |
| HP            | 3397                        | [eb6f8b5a56](https://linux-hardware.org/?probe=eb6f8b5a56) | Oct 03, 2022 |
| ASUSTek       | P7H55-USB3                  | [9f15eece8f](https://linux-hardware.org/?probe=9f15eece8f) | Oct 03, 2022 |
| ASUSTek       | M3A78-EM                    | [0c58d8b873](https://linux-hardware.org/?probe=0c58d8b873) | Oct 03, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | [b8d65ced41](https://linux-hardware.org/?probe=b8d65ced41) | Oct 02, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | [b5b057439d](https://linux-hardware.org/?probe=b5b057439d) | Oct 02, 2022 |
| ASRock        | 970 Pro3 R2.0               | [592adc6c9b](https://linux-hardware.org/?probe=592adc6c9b) | Oct 01, 2022 |
| HP            | 843B                        | [b683039e3b](https://linux-hardware.org/?probe=b683039e3b) | Oct 01, 2022 |
| Biostar       | B350ET2                     | [d7c5b1ad40](https://linux-hardware.org/?probe=d7c5b1ad40) | Oct 01, 2022 |
| Biostar       | B350ET2                     | [2b7bea0eda](https://linux-hardware.org/?probe=2b7bea0eda) | Sep 30, 2022 |
| MSI           | Z97 MPOWER                  | [f16a15a5b7](https://linux-hardware.org/?probe=f16a15a5b7) | Sep 30, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [8c116d30f9](https://linux-hardware.org/?probe=8c116d30f9) | Sep 30, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [7bffcb84c2](https://linux-hardware.org/?probe=7bffcb84c2) | Sep 29, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [e3e6ad5c35](https://linux-hardware.org/?probe=e3e6ad5c35) | Sep 29, 2022 |
| HP            | 8055                        | [aa3bd09485](https://linux-hardware.org/?probe=aa3bd09485) | Sep 29, 2022 |
| HP            | 843C                        | [e27595d303](https://linux-hardware.org/?probe=e27595d303) | Sep 29, 2022 |
| ASUSTek       | P5K                         | [2d278ddcdf](https://linux-hardware.org/?probe=2d278ddcdf) | Sep 28, 2022 |
| ASUSTek       | B85M-E/BR                   | [5116d1cae9](https://linux-hardware.org/?probe=5116d1cae9) | Sep 27, 2022 |
| Dell          | XPS 8700                    | [19fff8b508](https://linux-hardware.org/?probe=19fff8b508) | Sep 27, 2022 |
| Dell          | 0WN7Y6 A01                  | [356dc77824](https://linux-hardware.org/?probe=356dc77824) | Sep 27, 2022 |
| ASUSTek       | M3A78-EM                    | [34287ac52a](https://linux-hardware.org/?probe=34287ac52a) | Sep 27, 2022 |
| ASRock        | A75M-HVS                    | [75d51e6237](https://linux-hardware.org/?probe=75d51e6237) | Sep 26, 2022 |
| Gateway       | FMCP7AM                     | [0cb51f3e6f](https://linux-hardware.org/?probe=0cb51f3e6f) | Sep 25, 2022 |
| ASUSTek       | PRO A320M-R WI-FI           | [e760f06cef](https://linux-hardware.org/?probe=e760f06cef) | Sep 25, 2022 |
| Gigabyte      | GA-870A-UD3                 | [33a0b663ea](https://linux-hardware.org/?probe=33a0b663ea) | Sep 25, 2022 |
| ASRock        | QC5000M-ITX/PH              | [571b95c201](https://linux-hardware.org/?probe=571b95c201) | Sep 25, 2022 |
| HP            | 18E7                        | [71a12280de](https://linux-hardware.org/?probe=71a12280de) | Sep 24, 2022 |
| ASRock        | B85M Pro4                   | [cd75d968d7](https://linux-hardware.org/?probe=cd75d968d7) | Sep 23, 2022 |
| ASUSTek       | P5K                         | [0ddf0a48dd](https://linux-hardware.org/?probe=0ddf0a48dd) | Sep 22, 2022 |
| Pegatron      | 2ACD                        | [d6270f88cc](https://linux-hardware.org/?probe=d6270f88cc) | Sep 22, 2022 |
| HP            | 8055                        | [c72e0ed04b](https://linux-hardware.org/?probe=c72e0ed04b) | Sep 22, 2022 |
| ASUSTek       | Benicia                     | [22bf75699c](https://linux-hardware.org/?probe=22bf75699c) | Sep 21, 2022 |
| ASRock        | A75M-HVS                    | [0f81852612](https://linux-hardware.org/?probe=0f81852612) | Sep 21, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [f49e8d08ef](https://linux-hardware.org/?probe=f49e8d08ef) | Sep 20, 2022 |
| Dell          | 0D441T A01                  | [c315329853](https://linux-hardware.org/?probe=c315329853) | Sep 20, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [37dbdb48dd](https://linux-hardware.org/?probe=37dbdb48dd) | Sep 20, 2022 |
| Lenovo        | ThinkCentre M71e 3157AE2    | [9022058466](https://linux-hardware.org/?probe=9022058466) | Sep 19, 2022 |
| HP            | 0AA8h                       | [c79bdb21ed](https://linux-hardware.org/?probe=c79bdb21ed) | Sep 18, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [a5d838868a](https://linux-hardware.org/?probe=a5d838868a) | Sep 18, 2022 |
| Lenovo        | ThinkCentre M58e 7298A76    | [4775ccd67f](https://linux-hardware.org/?probe=4775ccd67f) | Sep 18, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [875435f3f0](https://linux-hardware.org/?probe=875435f3f0) | Sep 15, 2022 |
| ASRock        | H61M-DGS                    | [aeac7cfb74](https://linux-hardware.org/?probe=aeac7cfb74) | Sep 14, 2022 |
| Dell          | 0TW904 A01                  | [141188a631](https://linux-hardware.org/?probe=141188a631) | Sep 14, 2022 |
| Gigabyte      | Z77-D3H                     | [b1b929517d](https://linux-hardware.org/?probe=b1b929517d) | Sep 13, 2022 |
| ASUSTek       | PRIME Z270-A                | [b404f51fbe](https://linux-hardware.org/?probe=b404f51fbe) | Sep 12, 2022 |
| Lenovo        | SDK0J40700 WIN              | [b8f3a58a03](https://linux-hardware.org/?probe=b8f3a58a03) | Sep 11, 2022 |
| Gigabyte      | G1.Sniper Z97               | [445e54016b](https://linux-hardware.org/?probe=445e54016b) | Sep 11, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [0701918099](https://linux-hardware.org/?probe=0701918099) | Sep 11, 2022 |
| HP            | 0A54h                       | [2c88c7fd30](https://linux-hardware.org/?probe=2c88c7fd30) | Sep 10, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | [d13cf99728](https://linux-hardware.org/?probe=d13cf99728) | Sep 10, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [1e43753d7a](https://linux-hardware.org/?probe=1e43753d7a) | Sep 10, 2022 |
| MSI           | 2AE0                        | [a2b046dd4e](https://linux-hardware.org/?probe=a2b046dd4e) | Sep 10, 2022 |
| HP            | 3031h                       | [ea434d67b5](https://linux-hardware.org/?probe=ea434d67b5) | Sep 10, 2022 |
| HP            | 3031h                       | [feddf42c9f](https://linux-hardware.org/?probe=feddf42c9f) | Sep 10, 2022 |
| HP            | 0AA8h                       | [4e9a1e883c](https://linux-hardware.org/?probe=4e9a1e883c) | Sep 09, 2022 |
| Lenovo        | MAHOBAY                     | [2619e261d1](https://linux-hardware.org/?probe=2619e261d1) | Sep 07, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [dd20f0351c](https://linux-hardware.org/?probe=dd20f0351c) | Sep 06, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [3aca46f88b](https://linux-hardware.org/?probe=3aca46f88b) | Sep 06, 2022 |
| ASUSTek       | A88X-GAMER                  | [15fe45edd7](https://linux-hardware.org/?probe=15fe45edd7) | Sep 06, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | [92ff48d462](https://linux-hardware.org/?probe=92ff48d462) | Sep 06, 2022 |
| HP            | 2AF7                        | [9b7ccd5aa0](https://linux-hardware.org/?probe=9b7ccd5aa0) | Sep 06, 2022 |
| Dell          | 0HY9JP A02                  | [7cbf141461](https://linux-hardware.org/?probe=7cbf141461) | Sep 05, 2022 |
| ASRock        | B550M/ac                    | [b8ccaa27ef](https://linux-hardware.org/?probe=b8ccaa27ef) | Sep 04, 2022 |
| HP            | 821D                        | [459bdd177e](https://linux-hardware.org/?probe=459bdd177e) | Sep 03, 2022 |
| ASUSTek       | P8B75-V                     | [2ae6d7c950](https://linux-hardware.org/?probe=2ae6d7c950) | Sep 03, 2022 |
| HP            | 87D6 SMVB                   | [e597d54472](https://linux-hardware.org/?probe=e597d54472) | Sep 03, 2022 |
| MSI           | H97 GAMING 3                | [a5fb8d7651](https://linux-hardware.org/?probe=a5fb8d7651) | Sep 02, 2022 |
| ASUSTek       | PRIME B450M-A II            | [63e2adf3a9](https://linux-hardware.org/?probe=63e2adf3a9) | Sep 02, 2022 |
| MSI           | MS-B9201                    | [7bbae05d63](https://linux-hardware.org/?probe=7bbae05d63) | Sep 01, 2022 |
| MSI           | MS-B9201                    | [0d04798699](https://linux-hardware.org/?probe=0d04798699) | Sep 01, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [f4d5b9fc69](https://linux-hardware.org/?probe=f4d5b9fc69) | Aug 31, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [82cda7dfe9](https://linux-hardware.org/?probe=82cda7dfe9) | Aug 31, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [194290f42c](https://linux-hardware.org/?probe=194290f42c) | Aug 31, 2022 |
| MSI           | H410M PRO                   | [e1184c4522](https://linux-hardware.org/?probe=e1184c4522) | Aug 31, 2022 |
| ASUSTek       | Benicia                     | [13454a57f9](https://linux-hardware.org/?probe=13454a57f9) | Aug 31, 2022 |
| Dell          | 0GXM1W A00                  | [b358b1d32b](https://linux-hardware.org/?probe=b358b1d32b) | Aug 31, 2022 |
| HP            | 2B38                        | [9170225d70](https://linux-hardware.org/?probe=9170225d70) | Aug 30, 2022 |
| JGINYUE       | B85M VH PLUS V1.0           | [8712171422](https://linux-hardware.org/?probe=8712171422) | Aug 30, 2022 |
| Gigabyte      | H61M-D2H-USB3               | [eb74fdbbbc](https://linux-hardware.org/?probe=eb74fdbbbc) | Aug 30, 2022 |
| Dell          | 0R092H                      | [85871600b3](https://linux-hardware.org/?probe=85871600b3) | Aug 30, 2022 |
| JGINYUE       | B85M VH PLUS V1.0           | [f065870080](https://linux-hardware.org/?probe=f065870080) | Aug 30, 2022 |
| MSI           | B250M PRO-VD                | [d462e3b9d0](https://linux-hardware.org/?probe=d462e3b9d0) | Aug 29, 2022 |
| ASRock        | Z170 Pro4                   | [eaa574481f](https://linux-hardware.org/?probe=eaa574481f) | Aug 29, 2022 |
| HP            | 339A                        | [7338bebb05](https://linux-hardware.org/?probe=7338bebb05) | Aug 28, 2022 |
| ASRock        | H61M-DGS                    | [023204fa1f](https://linux-hardware.org/?probe=023204fa1f) | Aug 28, 2022 |
| WIPRO         | G31T-M                      | [51cea718eb](https://linux-hardware.org/?probe=51cea718eb) | Aug 28, 2022 |
| BESSTAR Te... | HM90                        | [134adccc85](https://linux-hardware.org/?probe=134adccc85) | Aug 27, 2022 |
| ASRock        | B550M Pro4                  | [9a05044c38](https://linux-hardware.org/?probe=9a05044c38) | Aug 27, 2022 |
| Dell          | 0T656F A01                  | [d1bb410d06](https://linux-hardware.org/?probe=d1bb410d06) | Aug 26, 2022 |
| ASUSTek       | SABERTOOTH Z87              | [02072aee33](https://linux-hardware.org/?probe=02072aee33) | Aug 25, 2022 |
| Gigabyte      | 970-GAMING                  | [dad1ede2be](https://linux-hardware.org/?probe=dad1ede2be) | Aug 25, 2022 |
| BESSTAR Te... | HM90                        | [8f13ff6ebd](https://linux-hardware.org/?probe=8f13ff6ebd) | Aug 24, 2022 |
| Gigabyte      | 970-GAMING                  | [faa79b7d62](https://linux-hardware.org/?probe=faa79b7d62) | Aug 24, 2022 |
| HP            | 2AFB                        | [ea3ce3f8dd](https://linux-hardware.org/?probe=ea3ce3f8dd) | Aug 24, 2022 |
| ASUSTek       | H81M-A/BR                   | [b9ac5d4051](https://linux-hardware.org/?probe=b9ac5d4051) | Aug 23, 2022 |
| Gigabyte      | H61M-D2H-USB3               | [eae2c82e26](https://linux-hardware.org/?probe=eae2c82e26) | Aug 23, 2022 |
| HP            | 2AF7                        | [fbc1710ad8](https://linux-hardware.org/?probe=fbc1710ad8) | Aug 22, 2022 |
| MSI           | X99S GAMING 7               | [f729654c4a](https://linux-hardware.org/?probe=f729654c4a) | Aug 22, 2022 |
| ASUSTek       | J1800I-C/BR                 | [f2f76737ad](https://linux-hardware.org/?probe=f2f76737ad) | Aug 22, 2022 |
| Dell          | 0C27VV A03                  | [4e894e1897](https://linux-hardware.org/?probe=4e894e1897) | Aug 21, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [4dc3a452d9](https://linux-hardware.org/?probe=4dc3a452d9) | Aug 19, 2022 |
| ASUSTek       | ProArt B660-CREATOR D4      | [0b9e6d6ad9](https://linux-hardware.org/?probe=0b9e6d6ad9) | Aug 19, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [6865f5ed0b](https://linux-hardware.org/?probe=6865f5ed0b) | Aug 19, 2022 |
| BESSTAR Te... | UM350                       | [c7bb6b56fb](https://linux-hardware.org/?probe=c7bb6b56fb) | Aug 18, 2022 |
| ASUSTek       | PRIME Z390-A                | [e03daeba5f](https://linux-hardware.org/?probe=e03daeba5f) | Aug 18, 2022 |
| ASRock        | B550M Pro4                  | [ab3425dd99](https://linux-hardware.org/?probe=ab3425dd99) | Aug 17, 2022 |
| ASUSTek       | PRIME H370-A                | [da477254e7](https://linux-hardware.org/?probe=da477254e7) | Aug 16, 2022 |
| Gigabyte      | M4HM87P-00                  | [5bb7e42eae](https://linux-hardware.org/?probe=5bb7e42eae) | Aug 16, 2022 |
| ASUSTek       | J1800I-C/BR                 | [01beed2be8](https://linux-hardware.org/?probe=01beed2be8) | Aug 15, 2022 |
| HP            | 339A                        | [c3e5458c9a](https://linux-hardware.org/?probe=c3e5458c9a) | Aug 15, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [08fa90340d](https://linux-hardware.org/?probe=08fa90340d) | Aug 14, 2022 |
| MAXSUN        | MS-TZZ A520M                | [aa844d0dce](https://linux-hardware.org/?probe=aa844d0dce) | Aug 14, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [58d97fbc16](https://linux-hardware.org/?probe=58d97fbc16) | Aug 14, 2022 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | [0c80c167e4](https://linux-hardware.org/?probe=0c80c167e4) | Aug 13, 2022 |
| ASUSTek       | A88X-PRO                    | [399f7ec1da](https://linux-hardware.org/?probe=399f7ec1da) | Aug 12, 2022 |
| ASUSTek       | P5GC-MX                     | [346a48750b](https://linux-hardware.org/?probe=346a48750b) | Aug 12, 2022 |
| ASUSTek       | J1800I-C/BR                 | [41cd4b02f1](https://linux-hardware.org/?probe=41cd4b02f1) | Aug 11, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [687375ec7c](https://linux-hardware.org/?probe=687375ec7c) | Aug 11, 2022 |
| HP            | 1589                        | [0519e046d2](https://linux-hardware.org/?probe=0519e046d2) | Aug 08, 2022 |
| HP            | 18E7                        | [7dd119f85e](https://linux-hardware.org/?probe=7dd119f85e) | Aug 08, 2022 |
| MSI           | Z97 GAMING 5                | [7f1e38b57b](https://linux-hardware.org/?probe=7f1e38b57b) | Aug 07, 2022 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [ab0da3a7ec](https://linux-hardware.org/?probe=ab0da3a7ec) | Aug 07, 2022 |
| ASUSTek       | P9X79 LE                    | [f8a36826db](https://linux-hardware.org/?probe=f8a36826db) | Aug 07, 2022 |
| ASUSTek       | ET2701I-W8                  | [5f9c4b50db](https://linux-hardware.org/?probe=5f9c4b50db) | Aug 07, 2022 |
| MP            | MS-7848                     | [8d4402905d](https://linux-hardware.org/?probe=8d4402905d) | Aug 06, 2022 |
| Lenovo        | ThinkCentre M57 6087YD2     | [9ad2c07771](https://linux-hardware.org/?probe=9ad2c07771) | Aug 06, 2022 |
| Pegatron      | Benicia                     | [d67d37efce](https://linux-hardware.org/?probe=d67d37efce) | Aug 05, 2022 |
| HP            | 339A                        | [53a3b6e834](https://linux-hardware.org/?probe=53a3b6e834) | Aug 05, 2022 |
| HP            | 339A                        | [8883c2cb6c](https://linux-hardware.org/?probe=8883c2cb6c) | Aug 05, 2022 |
| LORD ELECT... | GM965 Series                | [b60dce21e7](https://linux-hardware.org/?probe=b60dce21e7) | Aug 03, 2022 |
| Lenovo        | SDK0J40700 WIN              | [299ac7a8ff](https://linux-hardware.org/?probe=299ac7a8ff) | Aug 03, 2022 |
| HP            | 1589                        | [738de77596](https://linux-hardware.org/?probe=738de77596) | Aug 03, 2022 |
| MSI           | Boston                      | [32021cecf7](https://linux-hardware.org/?probe=32021cecf7) | Aug 03, 2022 |
| ASUSTek       | P7H55-M LX                  | [ad8af5c718](https://linux-hardware.org/?probe=ad8af5c718) | Aug 02, 2022 |
| ASUSTek       | P7H55-M LX                  | [b4e172e88b](https://linux-hardware.org/?probe=b4e172e88b) | Aug 02, 2022 |
| ASRock        | B450 Pro4                   | [aacc138812](https://linux-hardware.org/?probe=aacc138812) | Aug 02, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [cc8b9aa8f6](https://linux-hardware.org/?probe=cc8b9aa8f6) | Aug 01, 2022 |
| ASUSTek       | PRIME X570-P                | [405a75cb1d](https://linux-hardware.org/?probe=405a75cb1d) | Aug 01, 2022 |
| Gigabyte      | B450M DS3H-CF               | [7c68dbe47e](https://linux-hardware.org/?probe=7c68dbe47e) | Aug 01, 2022 |
| Gigabyte      | B450M DS3H-CF               | [6532751d00](https://linux-hardware.org/?probe=6532751d00) | Aug 01, 2022 |
| Dell          | 0T656F A01                  | [02ae993867](https://linux-hardware.org/?probe=02ae993867) | Jul 31, 2022 |
| ASRock        | Z170 Pro4                   | [e8dba6ab7e](https://linux-hardware.org/?probe=e8dba6ab7e) | Jul 31, 2022 |
| HP            | 82F2                        | [0c2d091c2e](https://linux-hardware.org/?probe=0c2d091c2e) | Jul 31, 2022 |
| Supermicro    | C7Q67 V1.01                 | [15508d1eff](https://linux-hardware.org/?probe=15508d1eff) | Jul 30, 2022 |
| Lenovo        | SDK0J40700 WIN              | [f50872e350](https://linux-hardware.org/?probe=f50872e350) | Jul 29, 2022 |
| Packard Be... | H57M01                      | [55e1536ab6](https://linux-hardware.org/?probe=55e1536ab6) | Jul 29, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [2bc22894c8](https://linux-hardware.org/?probe=2bc22894c8) | Jul 29, 2022 |
| Packard Be... | H57M01                      | [4789405230](https://linux-hardware.org/?probe=4789405230) | Jul 29, 2022 |
| Lenovo        | SDK0J40700 WIN              | [6d95a05ee7](https://linux-hardware.org/?probe=6d95a05ee7) | Jul 28, 2022 |
| ASRock        | Z170 Pro4                   | [73c8bc2ae1](https://linux-hardware.org/?probe=73c8bc2ae1) | Jul 28, 2022 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | [e214df8838](https://linux-hardware.org/?probe=e214df8838) | Jul 27, 2022 |
| Gigabyte      | B450 AORUS M                | [f9b0fe48d6](https://linux-hardware.org/?probe=f9b0fe48d6) | Jul 27, 2022 |
| ASUSTek       | PRIME A520M-K               | [cea12b9c9c](https://linux-hardware.org/?probe=cea12b9c9c) | Jul 27, 2022 |
| ASRock        | Z170 Pro4                   | [876c60188f](https://linux-hardware.org/?probe=876c60188f) | Jul 26, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [e33f8c0a93](https://linux-hardware.org/?probe=e33f8c0a93) | Jul 26, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [a059cf305d](https://linux-hardware.org/?probe=a059cf305d) | Jul 25, 2022 |
| Lenovo        | SDK0J40700 WIN              | [96d6480781](https://linux-hardware.org/?probe=96d6480781) | Jul 25, 2022 |
| ASUSTek       | A88X-PRO                    | [48e39039fc](https://linux-hardware.org/?probe=48e39039fc) | Jul 24, 2022 |
| Fujitsu       | D2901-A1 S26361-D2901-A1    | [aa952e11aa](https://linux-hardware.org/?probe=aa952e11aa) | Jul 24, 2022 |
| Dell          | 03NVJ6 A03                  | [9c0bb64bd9](https://linux-hardware.org/?probe=9c0bb64bd9) | Jul 24, 2022 |
| ASUSTek       | CROSSHAIR II FORMULA        | [aa2242c51f](https://linux-hardware.org/?probe=aa2242c51f) | Jul 23, 2022 |
| Gigabyte      | Z97X-SLI-CF                 | [177a181771](https://linux-hardware.org/?probe=177a181771) | Jul 23, 2022 |
| Supermicro    | C7Q67 V1.01                 | [722f3df811](https://linux-hardware.org/?probe=722f3df811) | Jul 23, 2022 |
| Dell          | 0FDY5C A00                  | [f5d81fb635](https://linux-hardware.org/?probe=f5d81fb635) | Jul 23, 2022 |
| Dell          | 0FDY5C A00                  | [83cf5f7085](https://linux-hardware.org/?probe=83cf5f7085) | Jul 23, 2022 |
| Gigabyte      | M68M-S2P                    | [7d4ba4168a](https://linux-hardware.org/?probe=7d4ba4168a) | Jul 22, 2022 |
| MSI           | Z97 GAMING 5                | [89e0889e94](https://linux-hardware.org/?probe=89e0889e94) | Jul 21, 2022 |
| Dell          | 09KPNV A00                  | [711546ab63](https://linux-hardware.org/?probe=711546ab63) | Jul 21, 2022 |
| Foxconn       | 2AAF                        | [b97dc9fd47](https://linux-hardware.org/?probe=b97dc9fd47) | Jul 20, 2022 |
| MSI           | B75MA-P45                   | [89af63cf6f](https://linux-hardware.org/?probe=89af63cf6f) | Jul 19, 2022 |
| Dell          | 09KPNV A00                  | [c47ecbd03f](https://linux-hardware.org/?probe=c47ecbd03f) | Jul 16, 2022 |
| Gigabyte      | GA-78LMT-S2P                | [0cf64c41f0](https://linux-hardware.org/?probe=0cf64c41f0) | Jul 16, 2022 |
| ASUSTek       | PRIME Z690-P D4             | [e5fed36e22](https://linux-hardware.org/?probe=e5fed36e22) | Jul 15, 2022 |
| Dell          | 0C27VV A01                  | [56bd2a162b](https://linux-hardware.org/?probe=56bd2a162b) | Jul 15, 2022 |
| Dell          | 0C27VV A01                  | [ccc3bc2a39](https://linux-hardware.org/?probe=ccc3bc2a39) | Jul 15, 2022 |
| Intel         | X79 V2.72B                  | [f244f6157b](https://linux-hardware.org/?probe=f244f6157b) | Jul 15, 2022 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [66efd060ca](https://linux-hardware.org/?probe=66efd060ca) | Jul 14, 2022 |
| Unknown       | Intel X79                   | [b0bb64b9ea](https://linux-hardware.org/?probe=b0bb64b9ea) | Jul 13, 2022 |
| Gigabyte      | H87M-D3H                    | [5056c4f640](https://linux-hardware.org/?probe=5056c4f640) | Jul 13, 2022 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | [c90a0cbab7](https://linux-hardware.org/?probe=c90a0cbab7) | Jul 13, 2022 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | [87fa08ea59](https://linux-hardware.org/?probe=87fa08ea59) | Jul 13, 2022 |
| System76      | Thelio thelio-r2            | [2d990d7afe](https://linux-hardware.org/?probe=2d990d7afe) | Jul 12, 2022 |
| HP            | 3398                        | [1b964004d9](https://linux-hardware.org/?probe=1b964004d9) | Jul 12, 2022 |
| ASUSTek       | V-P8H61E                    | [f8e5b72d1c](https://linux-hardware.org/?probe=f8e5b72d1c) | Jul 12, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | [42b248f049](https://linux-hardware.org/?probe=42b248f049) | Jul 11, 2022 |
| Lenovo        | ThinkCentre M91 7516AD1     | [19660ae71a](https://linux-hardware.org/?probe=19660ae71a) | Jul 11, 2022 |
| OEM_MB        | NARRA3                      | [845bdfd72c](https://linux-hardware.org/?probe=845bdfd72c) | Jul 11, 2022 |
| Dell          | 0J3C2F A00                  | [36252f70d6](https://linux-hardware.org/?probe=36252f70d6) | Jul 10, 2022 |
| Dell          | 0J3C2F A00                  | [e3197762a9](https://linux-hardware.org/?probe=e3197762a9) | Jul 10, 2022 |
| Pegatron      | Benicia                     | [2360476ad3](https://linux-hardware.org/?probe=2360476ad3) | Jul 09, 2022 |
| Gigabyte      | H110M-A-CF                  | [42335e5c5c](https://linux-hardware.org/?probe=42335e5c5c) | Jul 09, 2022 |
| HP            | 18E4                        | [bf615fe0ae](https://linux-hardware.org/?probe=bf615fe0ae) | Jul 08, 2022 |
| Gigabyte      | Z97X-UD3H-CF                | [b7ed1ecdf2](https://linux-hardware.org/?probe=b7ed1ecdf2) | Jul 08, 2022 |
| Gigabyte      | EP45-UD3P                   | [9118f548bb](https://linux-hardware.org/?probe=9118f548bb) | Jul 08, 2022 |
| Acer          | E91M                        | [4e55aacdd7](https://linux-hardware.org/?probe=4e55aacdd7) | Jul 06, 2022 |
| MSI           | Boston                      | [3dfcd01115](https://linux-hardware.org/?probe=3dfcd01115) | Jul 06, 2022 |
| Gigabyte      | H77N-WIFI                   | [dc12f11117](https://linux-hardware.org/?probe=dc12f11117) | Jul 05, 2022 |
| Biostar       | P4M90-M7A Ver:1.0           | [0567d5e337](https://linux-hardware.org/?probe=0567d5e337) | Jul 05, 2022 |
| OEM           | G41 775 ICH7 8712           | [4f82c838cb](https://linux-hardware.org/?probe=4f82c838cb) | Jul 04, 2022 |
| HP            | 8350                        | [39a8a75ebe](https://linux-hardware.org/?probe=39a8a75ebe) | Jul 03, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [31a8bd72d6](https://linux-hardware.org/?probe=31a8bd72d6) | Jul 02, 2022 |
| Foxconn       | 2AB1                        | [83a3a5794d](https://linux-hardware.org/?probe=83a3a5794d) | Jul 02, 2022 |
| Foxconn       | 2AB1                        | [7b7c8244af](https://linux-hardware.org/?probe=7b7c8244af) | Jul 02, 2022 |
| Gigabyte      | B360M HD3                   | [b35e9f3e5c](https://linux-hardware.org/?probe=b35e9f3e5c) | Jun 28, 2022 |
| Dell          | 0U880P A00                  | [e14832f09c](https://linux-hardware.org/?probe=e14832f09c) | Jun 26, 2022 |
| Gigabyte      | B450 AORUS M                | [6262e08c1f](https://linux-hardware.org/?probe=6262e08c1f) | Jun 26, 2022 |
| Pegatron      | IPPSB-DB                    | [a63cdffc5b](https://linux-hardware.org/?probe=a63cdffc5b) | Jun 26, 2022 |
| Dell          | 08NPPY A00                  | [3dc935ecb1](https://linux-hardware.org/?probe=3dc935ecb1) | Jun 26, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [c78b132d02](https://linux-hardware.org/?probe=c78b132d02) | Jun 26, 2022 |
| ASUSTek       | TUF Gaming X570-PRO WIFI... | [b232a434fd](https://linux-hardware.org/?probe=b232a434fd) | Jun 26, 2022 |
| Gigabyte      | B450 AORUS M                | [0297d9c8c1](https://linux-hardware.org/?probe=0297d9c8c1) | Jun 25, 2022 |
| Gigabyte      | Z77-DS3H                    | [fbde5d214f](https://linux-hardware.org/?probe=fbde5d214f) | Jun 24, 2022 |
| Gigabyte      | EP45-UD3P                   | [05449d9e5c](https://linux-hardware.org/?probe=05449d9e5c) | Jun 24, 2022 |
| MSI           | A75A-G35                    | [9e3dd8051c](https://linux-hardware.org/?probe=9e3dd8051c) | Jun 23, 2022 |
| ASUSTek       | PRIME X570-PRO              | [a24305d670](https://linux-hardware.org/?probe=a24305d670) | Jun 23, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [b21a0caebf](https://linux-hardware.org/?probe=b21a0caebf) | Jun 22, 2022 |
| ASUSTek       | PRIME X570-PRO              | [ecea2bb4ad](https://linux-hardware.org/?probe=ecea2bb4ad) | Jun 22, 2022 |
| Gigabyte      | EX58-UD3R                   | [4014366c8a](https://linux-hardware.org/?probe=4014366c8a) | Jun 21, 2022 |
| Lenovo        | SDK0J40700 WIN              | [82be38e941](https://linux-hardware.org/?probe=82be38e941) | Jun 17, 2022 |
| MSI           | B85M-E45                    | [58c2ff96e3](https://linux-hardware.org/?probe=58c2ff96e3) | Jun 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [85a022001e](https://linux-hardware.org/?probe=85a022001e) | Jun 16, 2022 |
| Dell          | 0X501H A02                  | [b9cb2a1e48](https://linux-hardware.org/?probe=b9cb2a1e48) | Jun 15, 2022 |
| Acer          | Aspire M3970                | [b966120966](https://linux-hardware.org/?probe=b966120966) | Jun 14, 2022 |
| Lenovo        | 3717 SDK0J40709 WIN 3259... | [aa63e13a60](https://linux-hardware.org/?probe=aa63e13a60) | Jun 13, 2022 |
| Lenovo        | 3717 SDK0J40709 WIN 3259... | [ba6786bbe8](https://linux-hardware.org/?probe=ba6786bbe8) | Jun 13, 2022 |
| ASUSTek       | P5GC-MX/1333                | [428eebd42f](https://linux-hardware.org/?probe=428eebd42f) | Jun 13, 2022 |
| MSI           | MEG Z690 UNIFY              | [4e227cff8b](https://linux-hardware.org/?probe=4e227cff8b) | Jun 12, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [2a772cecf4](https://linux-hardware.org/?probe=2a772cecf4) | Jun 12, 2022 |
| ASUSTek       | PRIME B550M-A               | [14b9e721b7](https://linux-hardware.org/?probe=14b9e721b7) | Jun 11, 2022 |
| Dell          | 0XFWHV A00                  | [4102e98034](https://linux-hardware.org/?probe=4102e98034) | Jun 09, 2022 |
| Dell          | 0WR7PY A03                  | [902546cb45](https://linux-hardware.org/?probe=902546cb45) | Jun 06, 2022 |
| ASUSTek       | TUF Z270 MARK 2             | [e993e32a56](https://linux-hardware.org/?probe=e993e32a56) | Jun 06, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [07808a7cbf](https://linux-hardware.org/?probe=07808a7cbf) | Jun 05, 2022 |
| Biostar       | A68N-2100K                  | [480a4c12b1](https://linux-hardware.org/?probe=480a4c12b1) | Jun 05, 2022 |
| ASRock        | 970 Extreme3                | [d5648a1a95](https://linux-hardware.org/?probe=d5648a1a95) | Jun 04, 2022 |
| MSI           | B85M-G43                    | [097b308b60](https://linux-hardware.org/?probe=097b308b60) | Jun 04, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [9404638832](https://linux-hardware.org/?probe=9404638832) | Jun 03, 2022 |
| BESSTAR Te... | TL50                        | [0455aba8a3](https://linux-hardware.org/?probe=0455aba8a3) | Jun 03, 2022 |
| HP            | 3029h                       | [d536fb8e36](https://linux-hardware.org/?probe=d536fb8e36) | Jun 03, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [61b90c102c](https://linux-hardware.org/?probe=61b90c102c) | Jun 03, 2022 |
| ASUSTek       | P5E-VM DO                   | [935c03cd63](https://linux-hardware.org/?probe=935c03cd63) | Jun 03, 2022 |
| Biostar       | A78MD                       | [206b04b6d8](https://linux-hardware.org/?probe=206b04b6d8) | Jun 02, 2022 |
| ASUSTek       | P5QL-ASUS-SE                | [5c9f7b1ab9](https://linux-hardware.org/?probe=5c9f7b1ab9) | Jun 02, 2022 |
| ASUSTek       | P5QL-ASUS-SE                | [0e1e2765fc](https://linux-hardware.org/?probe=0e1e2765fc) | Jun 01, 2022 |
| Biostar       | A78MD                       | [49ea0bd0e4](https://linux-hardware.org/?probe=49ea0bd0e4) | Jun 01, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [951bd2ea8d](https://linux-hardware.org/?probe=951bd2ea8d) | May 31, 2022 |
| Positivo      | POS-PIG41BAG                | [7bfeaeb75b](https://linux-hardware.org/?probe=7bfeaeb75b) | May 31, 2022 |
| Positivo      | POS-PIG41BAG                | [3ca7484fcf](https://linux-hardware.org/?probe=3ca7484fcf) | May 31, 2022 |
| ASUSTek       | PRIME A320M-K               | [d078b8d5dd](https://linux-hardware.org/?probe=d078b8d5dd) | May 30, 2022 |
| Gigabyte      | H410M H V3                  | [1dbf357f4f](https://linux-hardware.org/?probe=1dbf357f4f) | May 30, 2022 |
| ASUSTek       | P7P55D DELUXE               | [ba2d55d308](https://linux-hardware.org/?probe=ba2d55d308) | May 29, 2022 |
| ASRock        | B450 Pro4                   | [fa0b4c98df](https://linux-hardware.org/?probe=fa0b4c98df) | May 29, 2022 |
| Dell          | 0HN7XN A01                  | [9ebd09a280](https://linux-hardware.org/?probe=9ebd09a280) | May 29, 2022 |
| Gigabyte      | F2A58M-DS2                  | [3b95da87e9](https://linux-hardware.org/?probe=3b95da87e9) | May 28, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [4e77d22694](https://linux-hardware.org/?probe=4e77d22694) | May 27, 2022 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [1137f80fcd](https://linux-hardware.org/?probe=1137f80fcd) | May 27, 2022 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [57dbc86807](https://linux-hardware.org/?probe=57dbc86807) | May 27, 2022 |
| ASUSTek       | H81M-A/BR                   | [5df43d2ecd](https://linux-hardware.org/?probe=5df43d2ecd) | May 26, 2022 |
| Dell          | 088DT1 A01                  | [19d760099e](https://linux-hardware.org/?probe=19d760099e) | May 25, 2022 |
| Dell          | 088DT1 A01                  | [3334efe1e7](https://linux-hardware.org/?probe=3334efe1e7) | May 25, 2022 |
| Intel         | D946GZIS AAD66165-301       | [24c058da74](https://linux-hardware.org/?probe=24c058da74) | May 25, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [6e45ae9f7c](https://linux-hardware.org/?probe=6e45ae9f7c) | May 24, 2022 |
| MSI           | MEG Z390 GODLIKE            | [4249d49f41](https://linux-hardware.org/?probe=4249d49f41) | May 22, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [dffc3ea80a](https://linux-hardware.org/?probe=dffc3ea80a) | May 21, 2022 |
| ASUSTek       | Z97-DELUXE                  | [084bacdad3](https://linux-hardware.org/?probe=084bacdad3) | May 21, 2022 |
| MSI           | Z170A GAMING PRO            | [3a9789ed8a](https://linux-hardware.org/?probe=3a9789ed8a) | May 20, 2022 |
| ASUSTek       | PRIME B550M-A               | [1d5fec86a8](https://linux-hardware.org/?probe=1d5fec86a8) | May 20, 2022 |
| MSI           | 760GM-P21                   | [b6b5e0738c](https://linux-hardware.org/?probe=b6b5e0738c) | May 19, 2022 |
| MSI           | B85M-G43                    | [ef33bf347c](https://linux-hardware.org/?probe=ef33bf347c) | May 18, 2022 |
| Foxconn       | 2AAF                        | [dd1193f7ab](https://linux-hardware.org/?probe=dd1193f7ab) | May 18, 2022 |
| ASUSTek       | H81M-K                      | [c5cdf9ba52](https://linux-hardware.org/?probe=c5cdf9ba52) | May 18, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [2b889fc85b](https://linux-hardware.org/?probe=2b889fc85b) | May 17, 2022 |
| ASUSTek       | G15DK                       | [1df44e40e2](https://linux-hardware.org/?probe=1df44e40e2) | May 17, 2022 |
| Gigabyte      | M61PME-S2P                  | [7ab57b617f](https://linux-hardware.org/?probe=7ab57b617f) | May 17, 2022 |
| Dell          | 0C27VV A01                  | [aea8e14bff](https://linux-hardware.org/?probe=aea8e14bff) | May 17, 2022 |
| Dell          | 0GTK4K A02                  | [fba6de28d9](https://linux-hardware.org/?probe=fba6de28d9) | May 16, 2022 |
| ASUSTek       | P5KPL-AM SE                 | [ebbd363703](https://linux-hardware.org/?probe=ebbd363703) | May 16, 2022 |
| Intel         | D946GZIS AAD66165-301       | [4555cff448](https://linux-hardware.org/?probe=4555cff448) | May 16, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [7fcd8503ab](https://linux-hardware.org/?probe=7fcd8503ab) | May 16, 2022 |
| ASRock        | A88M-G                      | [81d094b2ec](https://linux-hardware.org/?probe=81d094b2ec) | May 15, 2022 |
| ASRock        | A88M-G                      | [8883591354](https://linux-hardware.org/?probe=8883591354) | May 15, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [0d9d6b919b](https://linux-hardware.org/?probe=0d9d6b919b) | May 15, 2022 |
| ASUSTek       | PRIME H310-PLUS             | [770fbfefd3](https://linux-hardware.org/?probe=770fbfefd3) | May 15, 2022 |
| ASUSTek       | PRIME H310-PLUS             | [8baee6f2e6](https://linux-hardware.org/?probe=8baee6f2e6) | May 14, 2022 |
| MSI           | MPG B560I GAMING EDGE WI... | [08ba1e652c](https://linux-hardware.org/?probe=08ba1e652c) | May 14, 2022 |
| Intel         | DH77EB AAG39073-304         | [f45bf21321](https://linux-hardware.org/?probe=f45bf21321) | May 12, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [86d60d0227](https://linux-hardware.org/?probe=86d60d0227) | May 12, 2022 |
| Pegatron      | 2A99h                       | [6a47713af6](https://linux-hardware.org/?probe=6a47713af6) | May 12, 2022 |
| AOpen         | i67QMx-DV R1.00BC1 55MP6... | [151db99970](https://linux-hardware.org/?probe=151db99970) | May 11, 2022 |
| Acer          | Aspire X3990                | [c6753ff37f](https://linux-hardware.org/?probe=c6753ff37f) | May 11, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | [8f62053ddd](https://linux-hardware.org/?probe=8f62053ddd) | May 11, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | [018c90008f](https://linux-hardware.org/?probe=018c90008f) | May 11, 2022 |
| MSI           | X370 GAMING PRO CARBON      | [b1d977cd69](https://linux-hardware.org/?probe=b1d977cd69) | May 11, 2022 |
| Gigabyte      | EX58-EXTREME                | [b558000bcc](https://linux-hardware.org/?probe=b558000bcc) | May 10, 2022 |
| Dell          | 0DR845                      | [ab501b0efe](https://linux-hardware.org/?probe=ab501b0efe) | May 10, 2022 |
| Gigabyte      | X58A-UD3R                   | [838a99f17a](https://linux-hardware.org/?probe=838a99f17a) | May 10, 2022 |
| Gigabyte      | B365M GAMING HD             | [5590d9a0f3](https://linux-hardware.org/?probe=5590d9a0f3) | May 10, 2022 |
| Dell          | 0GXM1W A02                  | [1606b44e03](https://linux-hardware.org/?probe=1606b44e03) | May 09, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [485a4916ed](https://linux-hardware.org/?probe=485a4916ed) | May 09, 2022 |
| ASRock        | H87M                        | [9c031f1e71](https://linux-hardware.org/?probe=9c031f1e71) | May 09, 2022 |
| Dell          | 0GXM1W A02                  | [bf028580b1](https://linux-hardware.org/?probe=bf028580b1) | May 09, 2022 |
| Gateway       | SX2185                      | [ddb64bc283](https://linux-hardware.org/?probe=ddb64bc283) | May 09, 2022 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [be0cecd40a](https://linux-hardware.org/?probe=be0cecd40a) | May 09, 2022 |
| ASUSTek       | P8H61-M LX                  | [9a00d24f58](https://linux-hardware.org/?probe=9a00d24f58) | May 09, 2022 |
| ASUSTek       | P8H61-M LX                  | [3f3089216f](https://linux-hardware.org/?probe=3f3089216f) | May 09, 2022 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [5c2fec5833](https://linux-hardware.org/?probe=5c2fec5833) | May 08, 2022 |
| Gigabyte      | H410M H V3                  | [c401229392](https://linux-hardware.org/?probe=c401229392) | May 08, 2022 |
| Gigabyte      | X570 GAMING X               | [ffc6dac164](https://linux-hardware.org/?probe=ffc6dac164) | May 07, 2022 |
| Gigabyte      | H410M H V3                  | [4c6f4d04bb](https://linux-hardware.org/?probe=4c6f4d04bb) | May 07, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [79c87fe48c](https://linux-hardware.org/?probe=79c87fe48c) | May 07, 2022 |
| Gigabyte      | X570 GAMING X               | [816a78b4cd](https://linux-hardware.org/?probe=816a78b4cd) | May 06, 2022 |
| ASUSTek       | 2A73h                       | [458bf998ee](https://linux-hardware.org/?probe=458bf998ee) | May 06, 2022 |
| Intel         | H55                         | [138637d12c](https://linux-hardware.org/?probe=138637d12c) | May 06, 2022 |
| Gigabyte      | G41M-Combo                  | [9940073216](https://linux-hardware.org/?probe=9940073216) | May 05, 2022 |
| Gigabyte      | G41MT-S2                    | [fd9ed9a035](https://linux-hardware.org/?probe=fd9ed9a035) | May 05, 2022 |
| HP            | 1906                        | [6f7f0536a9](https://linux-hardware.org/?probe=6f7f0536a9) | May 05, 2022 |
| Fujitsu       | D3128-A1 S26361-D3128-A1    | [31eaff1b28](https://linux-hardware.org/?probe=31eaff1b28) | May 04, 2022 |
| MSI           | B85M-G43                    | [f5deeb2d19](https://linux-hardware.org/?probe=f5deeb2d19) | May 04, 2022 |
| MSI           | Z590 PRO WIFI               | [17aad0bb78](https://linux-hardware.org/?probe=17aad0bb78) | May 03, 2022 |
| HP            | 1906                        | [60ce09d82e](https://linux-hardware.org/?probe=60ce09d82e) | May 03, 2022 |
| Gigabyte      | B365M GAMING HD             | [637890bd75](https://linux-hardware.org/?probe=637890bd75) | May 03, 2022 |
| Gigabyte      | G1.Sniper A88X-CF           | [7f9e8dd9f6](https://linux-hardware.org/?probe=7f9e8dd9f6) | May 02, 2022 |
| ASUSTek       | H97I-PLUS                   | [c8e857524b](https://linux-hardware.org/?probe=c8e857524b) | May 01, 2022 |
| ASRock        | B365M-HDV                   | [51b0e7e57f](https://linux-hardware.org/?probe=51b0e7e57f) | May 01, 2022 |
| Dell          | 0M017G A01                  | [653212f53c](https://linux-hardware.org/?probe=653212f53c) | May 01, 2022 |
| HP            | 1791                        | [877270ede6](https://linux-hardware.org/?probe=877270ede6) | Apr 30, 2022 |
| Intel         | DCP847SKE G80890-105        | [45dc47c8aa](https://linux-hardware.org/?probe=45dc47c8aa) | Apr 30, 2022 |
| Gigabyte      | G1.Sniper A88X-CF           | [89323fb22d](https://linux-hardware.org/?probe=89323fb22d) | Apr 30, 2022 |
| Foxconn       | 2A92                        | [298326d530](https://linux-hardware.org/?probe=298326d530) | Apr 30, 2022 |
| Foxconn       | 2A92                        | [a710d4a58f](https://linux-hardware.org/?probe=a710d4a58f) | Apr 30, 2022 |
| Gigabyte      | Z68AP-D3                    | [af8b52acd3](https://linux-hardware.org/?probe=af8b52acd3) | Apr 29, 2022 |
| Gigabyte      | P31-ES3G                    | [dc8419dcb3](https://linux-hardware.org/?probe=dc8419dcb3) | Apr 29, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [965985d6f4](https://linux-hardware.org/?probe=965985d6f4) | Apr 29, 2022 |
| Lenovo        | ThinkCentre M91p 7052A9G    | [277754d8c1](https://linux-hardware.org/?probe=277754d8c1) | Apr 29, 2022 |
| BESSTAR Te... | HM90                        | [814f90b822](https://linux-hardware.org/?probe=814f90b822) | Apr 28, 2022 |
| Gigabyte      | P31-ES3G                    | [c3df637d15](https://linux-hardware.org/?probe=c3df637d15) | Apr 27, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [97a2717eb9](https://linux-hardware.org/?probe=97a2717eb9) | Apr 27, 2022 |
| Gigabyte      | G1.Sniper A88X-CF           | [68fdd1e81a](https://linux-hardware.org/?probe=68fdd1e81a) | Apr 27, 2022 |
| ASUSTek       | Hematite                    | [a6eec927f0](https://linux-hardware.org/?probe=a6eec927f0) | Apr 26, 2022 |
| MSI           | B450 TOMAHAWK               | [148f1cc5e8](https://linux-hardware.org/?probe=148f1cc5e8) | Apr 25, 2022 |
| Dell          | 0HN7XN A01                  | [a282e15540](https://linux-hardware.org/?probe=a282e15540) | Apr 25, 2022 |
| Gigabyte      | G1.Sniper A88X-CF           | [392c7e4d0d](https://linux-hardware.org/?probe=392c7e4d0d) | Apr 25, 2022 |
| MSI           | 760GM-P21                   | [3582362347](https://linux-hardware.org/?probe=3582362347) | Apr 24, 2022 |
| ASUSTek       | H97I-PLUS                   | [1b392b96c3](https://linux-hardware.org/?probe=1b392b96c3) | Apr 24, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | [b36aa38e8a](https://linux-hardware.org/?probe=b36aa38e8a) | Apr 24, 2022 |
| Gigabyte      | A320M-H-CF                  | [da2e3a603d](https://linux-hardware.org/?probe=da2e3a603d) | Apr 23, 2022 |
| Dell          | 0GDG8Y A00                  | [a0ab7e8078](https://linux-hardware.org/?probe=a0ab7e8078) | Apr 22, 2022 |
| Acer          | Nitro N50-600 V:1.1         | [15332404e6](https://linux-hardware.org/?probe=15332404e6) | Apr 21, 2022 |
| Acer          | Nitro N50-600 V:1.1         | [b272388aa6](https://linux-hardware.org/?probe=b272388aa6) | Apr 21, 2022 |
| ASUSTek       | P5GC-MX                     | [810607b312](https://linux-hardware.org/?probe=810607b312) | Apr 20, 2022 |
| ASUSTek       | M5A78L-M LX V2              | [f830e867e5](https://linux-hardware.org/?probe=f830e867e5) | Apr 20, 2022 |
| Gigabyte      | Z68AP-D3                    | [76d25fd5c1](https://linux-hardware.org/?probe=76d25fd5c1) | Apr 20, 2022 |
| MSI           | B450M PRO-VDH MAX           | [73dbb7e52a](https://linux-hardware.org/?probe=73dbb7e52a) | Apr 19, 2022 |
| HP            | 8265                        | [6a7abd0db8](https://linux-hardware.org/?probe=6a7abd0db8) | Apr 19, 2022 |
| Huanan        | X79 249PC V2.2              | [209e881793](https://linux-hardware.org/?probe=209e881793) | Apr 18, 2022 |
| ASRock        | X570 Taichi Razer Editio... | [b3f2a146ea](https://linux-hardware.org/?probe=b3f2a146ea) | Apr 18, 2022 |
| ASRock        | X570 Taichi Razer Editio... | [d597e4df9c](https://linux-hardware.org/?probe=d597e4df9c) | Apr 18, 2022 |
| Acer          | Aspire TC-115               | [16d5411ae8](https://linux-hardware.org/?probe=16d5411ae8) | Apr 18, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [f20c2c3665](https://linux-hardware.org/?probe=f20c2c3665) | Apr 16, 2022 |
| HP            | 845A                        | [cc8c320581](https://linux-hardware.org/?probe=cc8c320581) | Apr 16, 2022 |
| MSI           | 2AE0                        | [b1059198e0](https://linux-hardware.org/?probe=b1059198e0) | Apr 15, 2022 |
| ASRock        | H170M Pro4                  | [0dd1b326c0](https://linux-hardware.org/?probe=0dd1b326c0) | Apr 15, 2022 |
| MSI           | MAG B460M MORTAR            | [eeccee9c29](https://linux-hardware.org/?probe=eeccee9c29) | Apr 15, 2022 |
| ASUSTek       | F2A85-V                     | [6200a8f946](https://linux-hardware.org/?probe=6200a8f946) | Apr 14, 2022 |
| Gigabyte      | Z77-D3H                     | [2ddb0d0765](https://linux-hardware.org/?probe=2ddb0d0765) | Apr 13, 2022 |
| ASRock        | B460M-ITX/ac                | [7e6604d785](https://linux-hardware.org/?probe=7e6604d785) | Apr 12, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [ba5d8c783b](https://linux-hardware.org/?probe=ba5d8c783b) | Apr 12, 2022 |
| Gigabyte      | A520 AORUS ELITE            | [a0ff638057](https://linux-hardware.org/?probe=a0ff638057) | Apr 11, 2022 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | [cadff96ec0](https://linux-hardware.org/?probe=cadff96ec0) | Apr 11, 2022 |
| ASUSTek       | H81M-A                      | [89dfde5c28](https://linux-hardware.org/?probe=89dfde5c28) | Apr 11, 2022 |
| Lenovo        | ThinkCentre A62 7057A77     | [a751b63d6b](https://linux-hardware.org/?probe=a751b63d6b) | Apr 11, 2022 |
| Dell          | 0JP3NX A01                  | [266d7d3a62](https://linux-hardware.org/?probe=266d7d3a62) | Apr 11, 2022 |
| ASRock        | B450 Steel Legend           | [b9b9565fae](https://linux-hardware.org/?probe=b9b9565fae) | Apr 10, 2022 |
| ASUSTek       | P8B75-V                     | [218db09adf](https://linux-hardware.org/?probe=218db09adf) | Apr 10, 2022 |
| Medion        | MS-7366                     | [206ab01c63](https://linux-hardware.org/?probe=206ab01c63) | Apr 10, 2022 |
| Foxconn       | 2A92                        | [d7dc8e0a2b](https://linux-hardware.org/?probe=d7dc8e0a2b) | Apr 10, 2022 |
| ASUSTek       | PRIME Z390-A                | [9f3f45d840](https://linux-hardware.org/?probe=9f3f45d840) | Apr 09, 2022 |
| ASRock        | Z87 Pro4                    | [03ee27c2ea](https://linux-hardware.org/?probe=03ee27c2ea) | Apr 09, 2022 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [73628a9025](https://linux-hardware.org/?probe=73628a9025) | Apr 09, 2022 |
| Medion        | MS-7366                     | [86884e1cf1](https://linux-hardware.org/?probe=86884e1cf1) | Apr 09, 2022 |
| ASRock        | H61M-DGS                    | [1d08a53545](https://linux-hardware.org/?probe=1d08a53545) | Apr 08, 2022 |
| ASRock        | X399 Taichi                 | [2e37b66578](https://linux-hardware.org/?probe=2e37b66578) | Apr 08, 2022 |
| ASRock        | X399 Taichi                 | [e7b1a0df67](https://linux-hardware.org/?probe=e7b1a0df67) | Apr 08, 2022 |
| Lenovo        | ThinkCentre A62 7057A77     | [fe36e7827a](https://linux-hardware.org/?probe=fe36e7827a) | Apr 08, 2022 |
| ASUSTek       | PRIME Z390-A                | [8ac05d8917](https://linux-hardware.org/?probe=8ac05d8917) | Apr 07, 2022 |
| Gigabyte      | B365M GAMING HD             | [94b6fc5131](https://linux-hardware.org/?probe=94b6fc5131) | Apr 07, 2022 |
| Alienware     | 0H869M A00                  | [f6a1c02c3e](https://linux-hardware.org/?probe=f6a1c02c3e) | Apr 07, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [1592895310](https://linux-hardware.org/?probe=1592895310) | Apr 07, 2022 |
| ASUSTek       | ROG Maximus XIII HERO       | [f76a15be2a](https://linux-hardware.org/?probe=f76a15be2a) | Apr 06, 2022 |
| Gigabyte      | Z77-DS3H                    | [a3d3ff5ac5](https://linux-hardware.org/?probe=a3d3ff5ac5) | Apr 06, 2022 |
| Unknown       | Unknown                     | [c8049ac14a](https://linux-hardware.org/?probe=c8049ac14a) | Apr 06, 2022 |
| ASUSTek       | P5GC-MX                     | [ce2aaa12ab](https://linux-hardware.org/?probe=ce2aaa12ab) | Apr 06, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [55eda86e20](https://linux-hardware.org/?probe=55eda86e20) | Apr 05, 2022 |
| Dell          | 09KPNV A00                  | [0a06779a5a](https://linux-hardware.org/?probe=0a06779a5a) | Apr 05, 2022 |
| Foxconn       | 2A92                        | [dd802e925f](https://linux-hardware.org/?probe=dd802e925f) | Apr 05, 2022 |
| MSI           | MS-7204                     | [e04077c3ac](https://linux-hardware.org/?probe=e04077c3ac) | Apr 05, 2022 |
| MSI           | MS-7204                     | [817c6f06bf](https://linux-hardware.org/?probe=817c6f06bf) | Apr 05, 2022 |
| Dell          | 0DR845                      | [26a919fc82](https://linux-hardware.org/?probe=26a919fc82) | Apr 04, 2022 |
| MSI           | Z170A GAMING M5             | [26032ef606](https://linux-hardware.org/?probe=26032ef606) | Apr 04, 2022 |
| MSI           | Z170A GAMING M5             | [fed309fdf1](https://linux-hardware.org/?probe=fed309fdf1) | Apr 04, 2022 |
| MSI           | B75A-G41                    | [80ec6aed14](https://linux-hardware.org/?probe=80ec6aed14) | Apr 04, 2022 |
| Unknown       | Unknown                     | [f6bc1c6219](https://linux-hardware.org/?probe=f6bc1c6219) | Apr 03, 2022 |
| ASUSTek       | PRIME X570-P                | [e237e56d72](https://linux-hardware.org/?probe=e237e56d72) | Apr 02, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [2315db07e2](https://linux-hardware.org/?probe=2315db07e2) | Apr 02, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [448e59a9a6](https://linux-hardware.org/?probe=448e59a9a6) | Apr 02, 2022 |
| ASUSTek       | F2A85-V                     | [6056351804](https://linux-hardware.org/?probe=6056351804) | Apr 02, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | [0d1d941941](https://linux-hardware.org/?probe=0d1d941941) | Apr 02, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [fc477a4cb4](https://linux-hardware.org/?probe=fc477a4cb4) | Apr 02, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [23b384fa80](https://linux-hardware.org/?probe=23b384fa80) | Apr 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | [e94a772f2b](https://linux-hardware.org/?probe=e94a772f2b) | Apr 02, 2022 |
| Biostar       | X370GT5                     | [efe58d6ab1](https://linux-hardware.org/?probe=efe58d6ab1) | Mar 31, 2022 |
| MSI           | P45 Neo2-FR                 | [23fa0ec187](https://linux-hardware.org/?probe=23fa0ec187) | Mar 31, 2022 |
| Google        | Panther                     | [b1af725b7c](https://linux-hardware.org/?probe=b1af725b7c) | Mar 30, 2022 |
| Google        | Panther                     | [98185ea5bc](https://linux-hardware.org/?probe=98185ea5bc) | Mar 30, 2022 |
| Gigabyte      | G1.Sniper B6-CF             | [17ea484809](https://linux-hardware.org/?probe=17ea484809) | Mar 29, 2022 |
| MSI           | MAG B660 TOMAHAWK WIFI D... | [99acee5d56](https://linux-hardware.org/?probe=99acee5d56) | Mar 29, 2022 |
| Intel         | DH55HC AAE70933-505         | [0a58762fd9](https://linux-hardware.org/?probe=0a58762fd9) | Mar 29, 2022 |
| HP            | 18E5                        | [39cb47db55](https://linux-hardware.org/?probe=39cb47db55) | Mar 28, 2022 |
| Dell          | 0JP3NX A01                  | [a50c8cdd0d](https://linux-hardware.org/?probe=a50c8cdd0d) | Mar 28, 2022 |
| Dell          | 0JP3NX A01                  | [5f779f4af0](https://linux-hardware.org/?probe=5f779f4af0) | Mar 27, 2022 |
| Pegatron      | Benicia                     | [cd70e5d6f6](https://linux-hardware.org/?probe=cd70e5d6f6) | Mar 27, 2022 |
| HP            | 18E5                        | [061d716ce1](https://linux-hardware.org/?probe=061d716ce1) | Mar 27, 2022 |
| ASRock        | H61M-HVS                    | [7ebb094ad8](https://linux-hardware.org/?probe=7ebb094ad8) | Mar 25, 2022 |
| Dell          | 0P096C A01                  | [fff71ec7de](https://linux-hardware.org/?probe=fff71ec7de) | Mar 24, 2022 |
| Gigabyte      | H67MA-USB3-B3               | [c5ad9a2c99](https://linux-hardware.org/?probe=c5ad9a2c99) | Mar 24, 2022 |
| ASUSTek       | H81M-A                      | [1c1b20796d](https://linux-hardware.org/?probe=1c1b20796d) | Mar 24, 2022 |
| ASUSTek       | H81M-CS/BR                  | [17a0a5394e](https://linux-hardware.org/?probe=17a0a5394e) | Mar 24, 2022 |
| Dell          | 0KWVT8 A00                  | [5e2b36f808](https://linux-hardware.org/?probe=5e2b36f808) | Mar 24, 2022 |
| ASRock        | B550 Steel Legend           | [5c1495ecf1](https://linux-hardware.org/?probe=5c1495ecf1) | Mar 21, 2022 |
| ASRock        | B550 Steel Legend           | [00ea7017ff](https://linux-hardware.org/?probe=00ea7017ff) | Mar 20, 2022 |
| Gigabyte      | Z690 UD DDR4                | [03bfb9a66b](https://linux-hardware.org/?probe=03bfb9a66b) | Mar 20, 2022 |
| ASUSTek       | NODUSM3                     | [14c35dc52c](https://linux-hardware.org/?probe=14c35dc52c) | Mar 20, 2022 |
| Dell          | 0GDG8Y A00                  | [1deed3b4bb](https://linux-hardware.org/?probe=1deed3b4bb) | Mar 20, 2022 |
| Biostar       | B460GTQ                     | [7c912f57c6](https://linux-hardware.org/?probe=7c912f57c6) | Mar 20, 2022 |
| HP            | 1497                        | [2aac5eaf08](https://linux-hardware.org/?probe=2aac5eaf08) | Mar 19, 2022 |
| HP            | 1497                        | [ec392b9979](https://linux-hardware.org/?probe=ec392b9979) | Mar 19, 2022 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [3ba6de8cdd](https://linux-hardware.org/?probe=3ba6de8cdd) | Mar 19, 2022 |
| Dell          | 09KPNV A00                  | [f71ac898a8](https://linux-hardware.org/?probe=f71ac898a8) | Mar 19, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [34fb0ae26f](https://linux-hardware.org/?probe=34fb0ae26f) | Mar 19, 2022 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | [7cafe0766c](https://linux-hardware.org/?probe=7cafe0766c) | Mar 18, 2022 |
| ASUSTek       | Hematite                    | [e4258e3376](https://linux-hardware.org/?probe=e4258e3376) | Mar 17, 2022 |
| ASUSTek       | M2A-VM HDMI                 | [ea35877485](https://linux-hardware.org/?probe=ea35877485) | Mar 17, 2022 |
| ASRock        | H510M-HVS R2.0              | [0af153934b](https://linux-hardware.org/?probe=0af153934b) | Mar 17, 2022 |
| ASRock        | H510M-HVS R2.0              | [2071129adb](https://linux-hardware.org/?probe=2071129adb) | Mar 17, 2022 |
| Shuttle       | X50V2PLUS V1.00             | [0bd650dfff](https://linux-hardware.org/?probe=0bd650dfff) | Mar 16, 2022 |
| Dell          | 0WMJ54 A01                  | [fe21b2c644](https://linux-hardware.org/?probe=fe21b2c644) | Mar 15, 2022 |
| HP            | 1791                        | [f183c3d0f0](https://linux-hardware.org/?probe=f183c3d0f0) | Mar 15, 2022 |
| HP            | 1497                        | [0aaa7bf906](https://linux-hardware.org/?probe=0aaa7bf906) | Mar 15, 2022 |
| TYAN Compu... | D2568 S26361-D2568-A11      | [fd7cbc2300](https://linux-hardware.org/?probe=fd7cbc2300) | Mar 15, 2022 |
| Dell          | 0CU409                      | [2e684afab9](https://linux-hardware.org/?probe=2e684afab9) | Mar 14, 2022 |
| MSI           | B85M-G43                    | [3869d4fdc0](https://linux-hardware.org/?probe=3869d4fdc0) | Mar 14, 2022 |
| ASUSTek       | Maximus VIII GENE           | [f264de34b1](https://linux-hardware.org/?probe=f264de34b1) | Mar 13, 2022 |
| ASUSTek       | Crosshair IV Formula        | [fd7e52fdd3](https://linux-hardware.org/?probe=fd7e52fdd3) | Mar 13, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [a90ce91192](https://linux-hardware.org/?probe=a90ce91192) | Mar 12, 2022 |
| ASUSTek       | P8P67                       | [33bf33cb8d](https://linux-hardware.org/?probe=33bf33cb8d) | Mar 10, 2022 |
| ASUSTek       | M5A97 R2.0                  | [67ead34e9e](https://linux-hardware.org/?probe=67ead34e9e) | Mar 10, 2022 |
| Google        | Buddy                       | [848034437d](https://linux-hardware.org/?probe=848034437d) | Mar 09, 2022 |
| Google        | Buddy                       | [db18fd0c96](https://linux-hardware.org/?probe=db18fd0c96) | Mar 09, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | [798e5f6c43](https://linux-hardware.org/?probe=798e5f6c43) | Mar 09, 2022 |
| MSI           | H110M PRO-VH PLUS           | [fc3707d356](https://linux-hardware.org/?probe=fc3707d356) | Mar 09, 2022 |
| ASUSTek       | P5E-VM DO                   | [876e876df1](https://linux-hardware.org/?probe=876e876df1) | Mar 09, 2022 |
| MSI           | A75A-G35                    | [8dfa30cef5](https://linux-hardware.org/?probe=8dfa30cef5) | Mar 07, 2022 |
| ASUSTek       | Z97-DELUXE                  | [7ea271a455](https://linux-hardware.org/?probe=7ea271a455) | Mar 05, 2022 |
| MSI           | B85M-G43                    | [d5e3087569](https://linux-hardware.org/?probe=d5e3087569) | Mar 04, 2022 |
| Intel         | H61                         | [86f2038ab2](https://linux-hardware.org/?probe=86f2038ab2) | Mar 03, 2022 |
| ASUSTek       | PRIME X370-PRO              | [78089f6e8c](https://linux-hardware.org/?probe=78089f6e8c) | Mar 03, 2022 |
| Gigabyte      | Z77-DS3H                    | [16268a74aa](https://linux-hardware.org/?probe=16268a74aa) | Mar 03, 2022 |
| MSI           | A68HM-E33 V2                | [53dd60c906](https://linux-hardware.org/?probe=53dd60c906) | Mar 02, 2022 |
| ASUSTek       | PRIME X370-PRO              | [b74317d80e](https://linux-hardware.org/?probe=b74317d80e) | Mar 02, 2022 |
| ASRock        | H110M-DGS R3.0              | [d7b8815296](https://linux-hardware.org/?probe=d7b8815296) | Feb 28, 2022 |
| Gigabyte      | AX370-Gaming K5-CF          | [61f8410abd](https://linux-hardware.org/?probe=61f8410abd) | Feb 28, 2022 |
| BESSTAR Te... | TL50                        | [54383b0005](https://linux-hardware.org/?probe=54383b0005) | Feb 28, 2022 |
| HP            | 821D                        | [fdfcbe172a](https://linux-hardware.org/?probe=fdfcbe172a) | Feb 28, 2022 |
| Acer          | Aspire TC-875 V:1.0         | [47018f3ae4](https://linux-hardware.org/?probe=47018f3ae4) | Feb 28, 2022 |
| Gigabyte      | GA-790XTA-UD4               | [f455a7b7a5](https://linux-hardware.org/?probe=f455a7b7a5) | Feb 28, 2022 |
| ASRock        | H77M                        | [e49dce2077](https://linux-hardware.org/?probe=e49dce2077) | Feb 28, 2022 |
| ASUSTek       | M4A87TD/USB3                | [ac9099b0e4](https://linux-hardware.org/?probe=ac9099b0e4) | Feb 28, 2022 |
| ASUSTek       | PRIME X370-PRO              | [52c633564d](https://linux-hardware.org/?probe=52c633564d) | Feb 27, 2022 |
| Gigabyte      | GA-790XTA-UD4               | [74461b0659](https://linux-hardware.org/?probe=74461b0659) | Feb 27, 2022 |
| MSI           | B85M-E45                    | [42fba9424e](https://linux-hardware.org/?probe=42fba9424e) | Feb 27, 2022 |
| Gigabyte      | EP43T-UD3L                  | [e1ba37c64a](https://linux-hardware.org/?probe=e1ba37c64a) | Feb 27, 2022 |
| Gigabyte      | EP43T-UD3L                  | [5d56069677](https://linux-hardware.org/?probe=5d56069677) | Feb 27, 2022 |
| Gigabyte      | N3160TN                     | [f080ac90fa](https://linux-hardware.org/?probe=f080ac90fa) | Feb 26, 2022 |
| ASUSTek       | PRIME H510M-D               | [5e8e80fa4c](https://linux-hardware.org/?probe=5e8e80fa4c) | Feb 25, 2022 |
| Intel         | X79M-S                      | [a175e713d6](https://linux-hardware.org/?probe=a175e713d6) | Feb 25, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [c9447d244f](https://linux-hardware.org/?probe=c9447d244f) | Feb 24, 2022 |
| Gigabyte      | Z87-HD3                     | [d1fd917c74](https://linux-hardware.org/?probe=d1fd917c74) | Feb 24, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | [40de7f3fd4](https://linux-hardware.org/?probe=40de7f3fd4) | Feb 23, 2022 |
| Medion        | MS-7707                     | [563fc4ee5a](https://linux-hardware.org/?probe=563fc4ee5a) | Feb 23, 2022 |
| Medion        | MS-7707                     | [f3b9e8796b](https://linux-hardware.org/?probe=f3b9e8796b) | Feb 23, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [8efe63496f](https://linux-hardware.org/?probe=8efe63496f) | Feb 22, 2022 |
| ASUSTek       | P5KPL-AM EPU                | [979289afcb](https://linux-hardware.org/?probe=979289afcb) | Feb 21, 2022 |
| MSI           | MPG B560I GAMING EDGE WI... | [62fc974ec7](https://linux-hardware.org/?probe=62fc974ec7) | Feb 21, 2022 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [435006f81f](https://linux-hardware.org/?probe=435006f81f) | Feb 20, 2022 |
| Gigabyte      | B560M AORUS ELITE           | [9264e93f98](https://linux-hardware.org/?probe=9264e93f98) | Feb 20, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [1990e2040f](https://linux-hardware.org/?probe=1990e2040f) | Feb 19, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [c545739154](https://linux-hardware.org/?probe=c545739154) | Feb 18, 2022 |
| ASUSTek       | P5E-VM DO                   | [c204579cc4](https://linux-hardware.org/?probe=c204579cc4) | Feb 18, 2022 |
| Gigabyte      | H270M-DS3H-CF               | [bccc2f8988](https://linux-hardware.org/?probe=bccc2f8988) | Feb 18, 2022 |
| MSI           | B360M PRO-VDH               | [dfb03c38d4](https://linux-hardware.org/?probe=dfb03c38d4) | Feb 18, 2022 |
| Gigabyte      | GA-790XTA-UD4               | [b06467c5df](https://linux-hardware.org/?probe=b06467c5df) | Feb 16, 2022 |
| ASUSTek       | P8P67                       | [e52f9b0748](https://linux-hardware.org/?probe=e52f9b0748) | Feb 15, 2022 |
| HP            | 2B15A                       | [ca58e13d8f](https://linux-hardware.org/?probe=ca58e13d8f) | Feb 15, 2022 |
| Pegatron      | 2AC2                        | [092df404d4](https://linux-hardware.org/?probe=092df404d4) | Feb 15, 2022 |
| ASUSTek       | PRIME X370-PRO              | [54a56f3b09](https://linux-hardware.org/?probe=54a56f3b09) | Feb 15, 2022 |
| Intel         | X79M-S                      | [b655865606](https://linux-hardware.org/?probe=b655865606) | Feb 14, 2022 |
| IBM           | 81077AG                     | [934878ed63](https://linux-hardware.org/?probe=934878ed63) | Feb 14, 2022 |
| ASUSTek       | P8H61-M EVO                 | [40ed7abcc5](https://linux-hardware.org/?probe=40ed7abcc5) | Feb 14, 2022 |
| ASRock        | X299 Taichi                 | [cb4047cf07](https://linux-hardware.org/?probe=cb4047cf07) | Feb 13, 2022 |
| ASUSTek       | P8H61-M EVO                 | [94bcb91d02](https://linux-hardware.org/?probe=94bcb91d02) | Feb 13, 2022 |
| ASRock        | 970A-G                      | [7b3694013f](https://linux-hardware.org/?probe=7b3694013f) | Feb 13, 2022 |
| HP            | 0B54h D                     | [c9f9611ea4](https://linux-hardware.org/?probe=c9f9611ea4) | Feb 12, 2022 |
| ASUSTek       | M5A97 R2.0                  | [d97414cfe4](https://linux-hardware.org/?probe=d97414cfe4) | Feb 12, 2022 |
| Dell          | 0T10XW A01                  | [a9034f065e](https://linux-hardware.org/?probe=a9034f065e) | Feb 11, 2022 |
| Dell          | 0T10XW A01                  | [c0cce21524](https://linux-hardware.org/?probe=c0cce21524) | Feb 11, 2022 |
| Intel         | H61                         | [e06357425a](https://linux-hardware.org/?probe=e06357425a) | Feb 11, 2022 |
| ASUSTek       | ROG STRIX B365-F GAMING     | [b79b4aaf10](https://linux-hardware.org/?probe=b79b4aaf10) | Feb 11, 2022 |
| HP            | 198E                        | [f4781dd683](https://linux-hardware.org/?probe=f4781dd683) | Feb 10, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [0c13bfa27b](https://linux-hardware.org/?probe=0c13bfa27b) | Feb 10, 2022 |
| Dell          | 096JG8 A01                  | [c56c62ab01](https://linux-hardware.org/?probe=c56c62ab01) | Feb 10, 2022 |
| Gigabyte      | Z87N-WIFI                   | [e86fa9ee02](https://linux-hardware.org/?probe=e86fa9ee02) | Feb 09, 2022 |
| Gigabyte      | Z87N-WIFI                   | [1b6aa0ce08](https://linux-hardware.org/?probe=1b6aa0ce08) | Feb 09, 2022 |
| MSI           | MPG Z590 GAMING FORCE       | [961be2a608](https://linux-hardware.org/?probe=961be2a608) | Feb 09, 2022 |
| MSI           | MPG Z590 GAMING FORCE       | [4ab26645c2](https://linux-hardware.org/?probe=4ab26645c2) | Feb 09, 2022 |
| HP            | 8350                        | [31f2f10b25](https://linux-hardware.org/?probe=31f2f10b25) | Feb 08, 2022 |
| HP            | 1906                        | [c2107ad290](https://linux-hardware.org/?probe=c2107ad290) | Feb 08, 2022 |
| HP            | 1906                        | [9f08673e43](https://linux-hardware.org/?probe=9f08673e43) | Feb 08, 2022 |
| MSI           | 2AE0                        | [7026cf0c86](https://linux-hardware.org/?probe=7026cf0c86) | Feb 07, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [cec6148a23](https://linux-hardware.org/?probe=cec6148a23) | Feb 07, 2022 |
| MSI           | B85M-E45                    | [3653d29a0a](https://linux-hardware.org/?probe=3653d29a0a) | Feb 07, 2022 |
| Lenovo        | ThinkCentre M91p 4480B2G    | [c5db8c7811](https://linux-hardware.org/?probe=c5db8c7811) | Feb 06, 2022 |
| Lenovo        | ThinkCentre M91p 4480B2G    | [96e92c90a5](https://linux-hardware.org/?probe=96e92c90a5) | Feb 06, 2022 |
| Gigabyte      | G1.Sniper Z97               | [5ef683a8ed](https://linux-hardware.org/?probe=5ef683a8ed) | Feb 06, 2022 |
| Acer          | Aspire TC-115               | [03188d20fc](https://linux-hardware.org/?probe=03188d20fc) | Feb 05, 2022 |
| Gigabyte      | GA-78LMT-S2                 | [80cf2c4065](https://linux-hardware.org/?probe=80cf2c4065) | Feb 04, 2022 |
| ASUSTek       | Maximus V GENE              | [749946734b](https://linux-hardware.org/?probe=749946734b) | Feb 03, 2022 |
| Dell          | 0HN7XN A01                  | [5bb62c21b7](https://linux-hardware.org/?probe=5bb62c21b7) | Feb 03, 2022 |
| ASUSTek       | M4A785-M                    | [421c016644](https://linux-hardware.org/?probe=421c016644) | Feb 02, 2022 |
| Gigabyte      | B450 AORUS M                | [b76b53bf53](https://linux-hardware.org/?probe=b76b53bf53) | Feb 01, 2022 |
| Gigabyte      | B450 AORUS M                | [45f03f7991](https://linux-hardware.org/?probe=45f03f7991) | Jan 31, 2022 |
| Gigabyte      | B450 AORUS M                | [690eba21e0](https://linux-hardware.org/?probe=690eba21e0) | Jan 30, 2022 |
| Dell          | 0HN7XN A01                  | [af1d1e8c47](https://linux-hardware.org/?probe=af1d1e8c47) | Jan 30, 2022 |
| ASUSTek       | ROG STRIX B365-F GAMING     | [7450ea2cad](https://linux-hardware.org/?probe=7450ea2cad) | Jan 30, 2022 |
| ASRock        | H81M-DGS                    | [05fc3bd63b](https://linux-hardware.org/?probe=05fc3bd63b) | Jan 29, 2022 |
| HP            | 3047h                       | [48f624cbea](https://linux-hardware.org/?probe=48f624cbea) | Jan 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [bcdcd2eeb6](https://linux-hardware.org/?probe=bcdcd2eeb6) | Jan 29, 2022 |
| ASUSTek       | M2A74-AM SE                 | [1a2d6520d3](https://linux-hardware.org/?probe=1a2d6520d3) | Jan 29, 2022 |
| MSI           | 2AE0                        | [1a55336eb9](https://linux-hardware.org/?probe=1a55336eb9) | Jan 28, 2022 |
| Gigabyte      | GA-MA790GP-DS4H             | [ef8894e69d](https://linux-hardware.org/?probe=ef8894e69d) | Jan 28, 2022 |
| Wortmann      | TERRA_PC                    | [4fea20e2bf](https://linux-hardware.org/?probe=4fea20e2bf) | Jan 28, 2022 |
| Dell          | 0Y2MRG A00                  | [1a1b794c06](https://linux-hardware.org/?probe=1a1b794c06) | Jan 28, 2022 |
| Gigabyte      | Z270N-WIFI-CF               | [78f310c42a](https://linux-hardware.org/?probe=78f310c42a) | Jan 27, 2022 |
| ASRock        | G31M-S                      | [e579ce1757](https://linux-hardware.org/?probe=e579ce1757) | Jan 26, 2022 |
| Intel         | DH55PJ AAE93812-303         | [2c70e74055](https://linux-hardware.org/?probe=2c70e74055) | Jan 26, 2022 |
| Intel         | DH55PJ AAE93812-303         | [6a692a4e11](https://linux-hardware.org/?probe=6a692a4e11) | Jan 26, 2022 |
| Foxconn       | nT-i1000 Series PCB         | [72374dc22c](https://linux-hardware.org/?probe=72374dc22c) | Jan 26, 2022 |
| Foxconn       | nT-i1000 Series PCB         | [78cdf0490a](https://linux-hardware.org/?probe=78cdf0490a) | Jan 26, 2022 |
| Dell          | 07KY25 A00                  | [102d10e806](https://linux-hardware.org/?probe=102d10e806) | Jan 26, 2022 |
| MSI           | H97 GAMING 3                | [75f4b47111](https://linux-hardware.org/?probe=75f4b47111) | Jan 26, 2022 |
| Dell          | 06NWYK A01                  | [dbc44c9f4a](https://linux-hardware.org/?probe=dbc44c9f4a) | Jan 25, 2022 |
| HP            | 1497                        | [a32eadf3ab](https://linux-hardware.org/?probe=a32eadf3ab) | Jan 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [e521380180](https://linux-hardware.org/?probe=e521380180) | Jan 25, 2022 |
| ASUSTek       | Q87T                        | [1bcaa6dedf](https://linux-hardware.org/?probe=1bcaa6dedf) | Jan 24, 2022 |
| Foxconn       | 2ABF                        | [e5723eaa42](https://linux-hardware.org/?probe=e5723eaa42) | Jan 23, 2022 |
| Gigabyte      | B450M DS3H-CF               | [a0034083eb](https://linux-hardware.org/?probe=a0034083eb) | Jan 22, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | [2a8b893eb6](https://linux-hardware.org/?probe=2a8b893eb6) | Jan 22, 2022 |
| Foxconn       | 2ABF                        | [af38735785](https://linux-hardware.org/?probe=af38735785) | Jan 22, 2022 |
| MSI           | A75A-G35                    | [e2148dff19](https://linux-hardware.org/?probe=e2148dff19) | Jan 22, 2022 |
| Dell          | 0CU409                      | [8fc6c3decf](https://linux-hardware.org/?probe=8fc6c3decf) | Jan 21, 2022 |
| Dell          | 0CU409                      | [953718318f](https://linux-hardware.org/?probe=953718318f) | Jan 21, 2022 |
| Gigabyte      | F2A58M-DS2                  | [a89dd04d3a](https://linux-hardware.org/?probe=a89dd04d3a) | Jan 20, 2022 |
| Fujitsu       | D2901-A1 S26361-D2901-A1    | [586012f45e](https://linux-hardware.org/?probe=586012f45e) | Jan 20, 2022 |
| Dell          | 09NY2R A00                  | [2ab8f0375c](https://linux-hardware.org/?probe=2ab8f0375c) | Jan 20, 2022 |
| Dell          | 09NY2R A00                  | [5308c77880](https://linux-hardware.org/?probe=5308c77880) | Jan 19, 2022 |
| ASUSTek       | H81M-K                      | [637ad5d9e4](https://linux-hardware.org/?probe=637ad5d9e4) | Jan 18, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [ffaca9cabf](https://linux-hardware.org/?probe=ffaca9cabf) | Jan 18, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [940b702411](https://linux-hardware.org/?probe=940b702411) | Jan 16, 2022 |
| MSI           | H61M-P25                    | [3433cb58a1](https://linux-hardware.org/?probe=3433cb58a1) | Jan 14, 2022 |
| MSI           | MS-7053                     | [8844db2984](https://linux-hardware.org/?probe=8844db2984) | Jan 13, 2022 |
| EVGA          | 152-HR-E979                 | [669c7a3ef6](https://linux-hardware.org/?probe=669c7a3ef6) | Jan 12, 2022 |
| EVGA          | 152-HR-E979                 | [075a31a3c5](https://linux-hardware.org/?probe=075a31a3c5) | Jan 12, 2022 |
| Lenovo        | SKYBAY SDK0J40697 WIN 33... | [368df270dc](https://linux-hardware.org/?probe=368df270dc) | Jan 11, 2022 |
| Gigabyte      | F2A58M-DS2                  | [b7ee3c3e93](https://linux-hardware.org/?probe=b7ee3c3e93) | Jan 11, 2022 |
| ASUSTek       | P8H61-I R2.0                | [5b08de311b](https://linux-hardware.org/?probe=5b08de311b) | Jan 10, 2022 |
| Dell          | 06NWYK A01                  | [98c10ce544](https://linux-hardware.org/?probe=98c10ce544) | Jan 10, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [6759388aa1](https://linux-hardware.org/?probe=6759388aa1) | Jan 09, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [6a368aefbd](https://linux-hardware.org/?probe=6a368aefbd) | Jan 09, 2022 |
| ASUSTek       | PRIME H310M-K               | [3b4d6e5abd](https://linux-hardware.org/?probe=3b4d6e5abd) | Jan 08, 2022 |
| ASRock        | G31M-S                      | [b33a983889](https://linux-hardware.org/?probe=b33a983889) | Jan 08, 2022 |
| MSI           | H61M-P25                    | [5f095c2bf8](https://linux-hardware.org/?probe=5f095c2bf8) | Jan 08, 2022 |
| Dell          | 042P49 A02                  | [b2a3538121](https://linux-hardware.org/?probe=b2a3538121) | Jan 08, 2022 |
| ASRock        | AM1B-ITX                    | [c374329271](https://linux-hardware.org/?probe=c374329271) | Jan 07, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | [e51ad2ec06](https://linux-hardware.org/?probe=e51ad2ec06) | Jan 07, 2022 |
| Dell          | 0YXT71 A02                  | [682c40786b](https://linux-hardware.org/?probe=682c40786b) | Jan 07, 2022 |
| Gigabyte      | H61M-S2PV                   | [398f9ebe03](https://linux-hardware.org/?probe=398f9ebe03) | Jan 06, 2022 |
| Dell          | 0GDG8Y A00                  | [e89e415451](https://linux-hardware.org/?probe=e89e415451) | Jan 05, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | [fc860fdb7a](https://linux-hardware.org/?probe=fc860fdb7a) | Jan 05, 2022 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [dad1a9143d](https://linux-hardware.org/?probe=dad1a9143d) | Jan 05, 2022 |
| MSI           | H61MU-E35                   | [5694489e55](https://linux-hardware.org/?probe=5694489e55) | Jan 05, 2022 |
| Gigabyte      | H370M D3H-CF                | [ab12119d4f](https://linux-hardware.org/?probe=ab12119d4f) | Jan 05, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [32d0fda197](https://linux-hardware.org/?probe=32d0fda197) | Jan 05, 2022 |
| MSI           | H61MU-E35                   | [2c3f24c851](https://linux-hardware.org/?probe=2c3f24c851) | Jan 04, 2022 |
| MSI           | H61M-P25                    | [3679d16bdb](https://linux-hardware.org/?probe=3679d16bdb) | Jan 04, 2022 |
| HP            | 3047h                       | [8faa43060a](https://linux-hardware.org/?probe=8faa43060a) | Jan 04, 2022 |
| MSI           | H61M-P25                    | [004392f0ef](https://linux-hardware.org/?probe=004392f0ef) | Jan 04, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [b838b1e1cc](https://linux-hardware.org/?probe=b838b1e1cc) | Jan 04, 2022 |
| MSI           | MPG Z390 GAMING PLUS        | [d2a528221c](https://linux-hardware.org/?probe=d2a528221c) | Jan 03, 2022 |
| ASRock        | B450M Steel Legend          | [81a98f588a](https://linux-hardware.org/?probe=81a98f588a) | Jan 02, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [a769ac4242](https://linux-hardware.org/?probe=a769ac4242) | Jan 01, 2022 |
| Gigabyte      | H110M-H-CF                  | [4754d83d04](https://linux-hardware.org/?probe=4754d83d04) | Jan 01, 2022 |
| Acer          | Aspire M3970                | [e10ce7d132](https://linux-hardware.org/?probe=e10ce7d132) | Dec 31, 2021 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [5b97adba13](https://linux-hardware.org/?probe=5b97adba13) | Dec 31, 2021 |
| ECS           | G31T-M7                     | [8cd5d79924](https://linux-hardware.org/?probe=8cd5d79924) | Dec 31, 2021 |
| ECS           | G31T-M7                     | [9ebfb53472](https://linux-hardware.org/?probe=9ebfb53472) | Dec 31, 2021 |
| HP            | 1998                        | [07bdd01c09](https://linux-hardware.org/?probe=07bdd01c09) | Dec 31, 2021 |
| Dell          | 088DT1 A01                  | [2599126547](https://linux-hardware.org/?probe=2599126547) | Dec 30, 2021 |
| Foxconn       | 2AB1                        | [1c32c6a027](https://linux-hardware.org/?probe=1c32c6a027) | Dec 30, 2021 |
| MSI           | H81M-P33                    | [0fb1d25a7d](https://linux-hardware.org/?probe=0fb1d25a7d) | Dec 30, 2021 |
| ASRock        | Z87 Pro4                    | [2a8588f61e](https://linux-hardware.org/?probe=2a8588f61e) | Dec 29, 2021 |
| Gigabyte      | Z97-HD3                     | [5536599b58](https://linux-hardware.org/?probe=5536599b58) | Dec 28, 2021 |
| Gigabyte      | H270M-DS3H-CF               | [127916f66f](https://linux-hardware.org/?probe=127916f66f) | Dec 28, 2021 |
| ASUSTek       | H81-PLUS                    | [60ba71333c](https://linux-hardware.org/?probe=60ba71333c) | Dec 27, 2021 |
| Intel         | Cherry Trail CR H91596-3... | [cb83ad3d6c](https://linux-hardware.org/?probe=cb83ad3d6c) | Dec 27, 2021 |
| Intel         | Cherry Trail CR H91596-3... | [76e7cab82a](https://linux-hardware.org/?probe=76e7cab82a) | Dec 26, 2021 |
| MSI           | MPG Z390 GAMING PLUS        | [39f562f189](https://linux-hardware.org/?probe=39f562f189) | Dec 25, 2021 |
| Dell          | 0VNP2H A00                  | [e64f51e52a](https://linux-hardware.org/?probe=e64f51e52a) | Dec 24, 2021 |
| Gigabyte      | H57M-USB3                   | [ee70d6b4b4](https://linux-hardware.org/?probe=ee70d6b4b4) | Dec 24, 2021 |
| Gigabyte      | Z170X-Gaming 7              | [5c4ae9536f](https://linux-hardware.org/?probe=5c4ae9536f) | Dec 24, 2021 |
| Gigabyte      | EG41MFT-US2H                | [2bfb4702c3](https://linux-hardware.org/?probe=2bfb4702c3) | Dec 23, 2021 |
| Gigabyte      | EG41MFT-US2H                | [b29d64341c](https://linux-hardware.org/?probe=b29d64341c) | Dec 23, 2021 |
| ASUSTek       | TUF Gaming X570-PRO WIFI... | [69d74c89b4](https://linux-hardware.org/?probe=69d74c89b4) | Dec 23, 2021 |
| Gigabyte      | B450M DS3H-CF               | [4453e33b88](https://linux-hardware.org/?probe=4453e33b88) | Dec 22, 2021 |
| ASRock        | B450 Pro4                   | [0832f6d0fd](https://linux-hardware.org/?probe=0832f6d0fd) | Dec 22, 2021 |
| ASUSTek       | P8Z77-M                     | [667e676c78](https://linux-hardware.org/?probe=667e676c78) | Dec 21, 2021 |
| ASRock        | A320M-DVS R4.0              | [c38dcdb848](https://linux-hardware.org/?probe=c38dcdb848) | Dec 21, 2021 |
| Dell          | 03NVJ6 A02                  | [685819bc74](https://linux-hardware.org/?probe=685819bc74) | Dec 20, 2021 |
| ASRock        | B450M-HDV R4.0              | [210f1589c4](https://linux-hardware.org/?probe=210f1589c4) | Dec 20, 2021 |
| ASRock        | B450M Pro4                  | [b40c57df26](https://linux-hardware.org/?probe=b40c57df26) | Dec 20, 2021 |
| ASUSTek       | PRIME B350M-A               | [09d76b803c](https://linux-hardware.org/?probe=09d76b803c) | Dec 20, 2021 |
| Intel         | B75                         | [9178fa9053](https://linux-hardware.org/?probe=9178fa9053) | Dec 19, 2021 |
| ASRock        | B450M-HDV R4.0              | [35182a65bb](https://linux-hardware.org/?probe=35182a65bb) | Dec 19, 2021 |
| Lenovo        | SHARKBAY 31900058 STD       | [717b852409](https://linux-hardware.org/?probe=717b852409) | Dec 19, 2021 |
| Apple         | Mac-F4208DC8 PVT            | [38a4bbf8d3](https://linux-hardware.org/?probe=38a4bbf8d3) | Dec 19, 2021 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [f86ed2049c](https://linux-hardware.org/?probe=f86ed2049c) | Dec 19, 2021 |
| Dell          | 0HY9JP A02                  | [063c3ec5d2](https://linux-hardware.org/?probe=063c3ec5d2) | Dec 19, 2021 |
| ASUSTek       | P5Q PRO TURBO               | [4c845a464c](https://linux-hardware.org/?probe=4c845a464c) | Dec 19, 2021 |
| Acer          | Aspire XC-330               | [1803a4622c](https://linux-hardware.org/?probe=1803a4622c) | Dec 19, 2021 |
| ASUSTek       | Benicia                     | [e572d5ceff](https://linux-hardware.org/?probe=e572d5ceff) | Dec 19, 2021 |
| Shuttle       | FH61V                       | [39d341d8be](https://linux-hardware.org/?probe=39d341d8be) | Dec 19, 2021 |
| MSI           | MS-7053                     | [3e9330e811](https://linux-hardware.org/?probe=3e9330e811) | Dec 18, 2021 |
| MSI           | MS-7053                     | [b32db3cd18](https://linux-hardware.org/?probe=b32db3cd18) | Dec 18, 2021 |
| Unknown       | C51GM-M                     | [91386c4f7c](https://linux-hardware.org/?probe=91386c4f7c) | Dec 17, 2021 |
| Lenovo        | ThinkCentre M57e 9489W1U    | [ba5156ef68](https://linux-hardware.org/?probe=ba5156ef68) | Dec 17, 2021 |
| Dell          | 0Y2K8N A01                  | [2e29930670](https://linux-hardware.org/?probe=2e29930670) | Dec 17, 2021 |
| Gigabyte      | H270M-DS3H-CF               | [dfbadf6708](https://linux-hardware.org/?probe=dfbadf6708) | Dec 17, 2021 |
| Unknown       | C51GM-M                     | [cd4d96fefa](https://linux-hardware.org/?probe=cd4d96fefa) | Dec 17, 2021 |
| Acer          | Aspire XC-330               | [61dd8de51b](https://linux-hardware.org/?probe=61dd8de51b) | Dec 16, 2021 |
| Dell          | 0D24M8 A01                  | [a306863279](https://linux-hardware.org/?probe=a306863279) | Dec 16, 2021 |
| Lenovo        | SHARKBAY NOK                | [2acaeac0de](https://linux-hardware.org/?probe=2acaeac0de) | Dec 14, 2021 |
| Lenovo        | SHARKBAY NOK                | [2c39bc3721](https://linux-hardware.org/?probe=2c39bc3721) | Dec 14, 2021 |
| HP            | 18E5                        | [88f87a7a1b](https://linux-hardware.org/?probe=88f87a7a1b) | Dec 14, 2021 |
| ASUSTek       | AM1M-A                      | [5113655631](https://linux-hardware.org/?probe=5113655631) | Dec 14, 2021 |
| HP            | 2179                        | [c2dd79384a](https://linux-hardware.org/?probe=c2dd79384a) | Dec 14, 2021 |
| ASUSTek       | VM40B                       | [c53952beab](https://linux-hardware.org/?probe=c53952beab) | Dec 14, 2021 |
| MSI           | MPG B550 GAMING PLUS        | [788c6b0550](https://linux-hardware.org/?probe=788c6b0550) | Dec 13, 2021 |
| ASUSTek       | P5QC                        | [b471a79340](https://linux-hardware.org/?probe=b471a79340) | Dec 13, 2021 |
| Dell          | 0M5DCD A00                  | [447bffefc3](https://linux-hardware.org/?probe=447bffefc3) | Dec 13, 2021 |
| Intel         | DQ87PG AAG74154-403         | [e2a6d57861](https://linux-hardware.org/?probe=e2a6d57861) | Dec 13, 2021 |
| Intel         | B75                         | [652828f7b9](https://linux-hardware.org/?probe=652828f7b9) | Dec 13, 2021 |
| MSI           | MPG Z390 GAMING PLUS        | [6b33adaacf](https://linux-hardware.org/?probe=6b33adaacf) | Dec 13, 2021 |
| ASUSTek       | PRIME B350M-A               | [aa92a82326](https://linux-hardware.org/?probe=aa92a82326) | Dec 13, 2021 |
| ASUSTek       | P5QC                        | [8e659f2b89](https://linux-hardware.org/?probe=8e659f2b89) | Dec 12, 2021 |
| ASUSTek       | PRIME B360M-K               | [abb6a94373](https://linux-hardware.org/?probe=abb6a94373) | Dec 12, 2021 |
| Gigabyte      | H97M-D3H                    | [d9e04ee743](https://linux-hardware.org/?probe=d9e04ee743) | Dec 12, 2021 |
| Gigabyte      | H97M-D3H                    | [1d768c3c63](https://linux-hardware.org/?probe=1d768c3c63) | Dec 12, 2021 |
| ASRock        | B450M Pro4                  | [6a8480268d](https://linux-hardware.org/?probe=6a8480268d) | Dec 12, 2021 |
| Dell          | 02YYK5 A01                  | [1301218290](https://linux-hardware.org/?probe=1301218290) | Dec 11, 2021 |
| HP            | 339A                        | [7081fc45a3](https://linux-hardware.org/?probe=7081fc45a3) | Dec 11, 2021 |
| HP            | 304Ah                       | [6d87535158](https://linux-hardware.org/?probe=6d87535158) | Dec 10, 2021 |
| eMachines     | EL1850G                     | [ccd7758cbe](https://linux-hardware.org/?probe=ccd7758cbe) | Dec 10, 2021 |
| ASUSTek       | NARRA3                      | [028ad01454](https://linux-hardware.org/?probe=028ad01454) | Dec 09, 2021 |
| Biostar       | A320MH                      | [fbbe7a436a](https://linux-hardware.org/?probe=fbbe7a436a) | Dec 09, 2021 |
| Biostar       | A320MH                      | [3870a17dfe](https://linux-hardware.org/?probe=3870a17dfe) | Dec 09, 2021 |
| MSI           | MAG B560M MORTAR WIFI       | [0e19f8e2ae](https://linux-hardware.org/?probe=0e19f8e2ae) | Dec 09, 2021 |
| MSI           | MAG B560M MORTAR WIFI       | [a37d2cc42f](https://linux-hardware.org/?probe=a37d2cc42f) | Dec 09, 2021 |
| MSI           | 970 GAMING                  | [1a5b0a8d39](https://linux-hardware.org/?probe=1a5b0a8d39) | Dec 09, 2021 |
| MSI           | 970 GAMING                  | [f4d8f580dc](https://linux-hardware.org/?probe=f4d8f580dc) | Dec 09, 2021 |
| ASUSTek       | NARRA3                      | [c64aed90a9](https://linux-hardware.org/?probe=c64aed90a9) | Dec 08, 2021 |
| ASUSTek       | M3A78-EM                    | [b041919f38](https://linux-hardware.org/?probe=b041919f38) | Dec 08, 2021 |
| HP            | 87C3                        | [16cc7e0bcb](https://linux-hardware.org/?probe=16cc7e0bcb) | Dec 07, 2021 |
| HP            | 81B4 01                     | [1477bd5a44](https://linux-hardware.org/?probe=1477bd5a44) | Dec 07, 2021 |
| Dell          | 0T656F A01                  | [552210319c](https://linux-hardware.org/?probe=552210319c) | Dec 06, 2021 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [2ce114a1c7](https://linux-hardware.org/?probe=2ce114a1c7) | Dec 06, 2021 |
| ASRock        | M3A770DE                    | [1a03b6e5c7](https://linux-hardware.org/?probe=1a03b6e5c7) | Dec 05, 2021 |
| ASRock        | M3A770DE                    | [bdf4260678](https://linux-hardware.org/?probe=bdf4260678) | Dec 05, 2021 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | [ce3d88a2a2](https://linux-hardware.org/?probe=ce3d88a2a2) | Dec 05, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [49fe509dd2](https://linux-hardware.org/?probe=49fe509dd2) | Dec 04, 2021 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [e6b7b57ea7](https://linux-hardware.org/?probe=e6b7b57ea7) | Dec 04, 2021 |
| Dell          | 0G254H A00                  | [11897b38da](https://linux-hardware.org/?probe=11897b38da) | Dec 03, 2021 |
| HP            | 2B44                        | [b62df43777](https://linux-hardware.org/?probe=b62df43777) | Dec 03, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 PRO ... | [e39465a63b](https://linux-hardware.org/?probe=e39465a63b) | Dec 03, 2021 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [ad90caf60d](https://linux-hardware.org/?probe=ad90caf60d) | Dec 03, 2021 |
| Pegatron      | JESSE                       | [9091bacc33](https://linux-hardware.org/?probe=9091bacc33) | Dec 03, 2021 |
| ASUSTek       | LEONITE                     | [704345be69](https://linux-hardware.org/?probe=704345be69) | Dec 03, 2021 |
| Biostar       | A780L3C                     | [a50e3d0532](https://linux-hardware.org/?probe=a50e3d0532) | Dec 02, 2021 |
| Foxconn       | 2A8C                        | [8d24862bd6](https://linux-hardware.org/?probe=8d24862bd6) | Dec 02, 2021 |
| Biostar       | A780L3C                     | [497f29a343](https://linux-hardware.org/?probe=497f29a343) | Dec 02, 2021 |
| Dell          | 0WR7PY A02                  | [1255f30eea](https://linux-hardware.org/?probe=1255f30eea) | Dec 01, 2021 |
| Gigabyte      | GA-MA74GM-S2H               | [bd33efb6f7](https://linux-hardware.org/?probe=bd33efb6f7) | Dec 01, 2021 |
| HP            | 339A                        | [4a377796cf](https://linux-hardware.org/?probe=4a377796cf) | Dec 01, 2021 |
| Dell          | 0PU052                      | [a943d9f217](https://linux-hardware.org/?probe=a943d9f217) | Dec 01, 2021 |
| Dell          | 0WR7PY A02                  | [d51c794107](https://linux-hardware.org/?probe=d51c794107) | Nov 30, 2021 |
| Dell          | 0WMJ54 A01                  | [5fa96d5863](https://linux-hardware.org/?probe=5fa96d5863) | Nov 30, 2021 |
| HP            | 8299                        | [6eb5c6d54a](https://linux-hardware.org/?probe=6eb5c6d54a) | Nov 30, 2021 |
| Medion        | MS-7707                     | [3d0a46f2ef](https://linux-hardware.org/?probe=3d0a46f2ef) | Nov 30, 2021 |
| ASRock        | H67DE3                      | [d710784470](https://linux-hardware.org/?probe=d710784470) | Nov 30, 2021 |
| HP            | 8299                        | [7bd1df0e4d](https://linux-hardware.org/?probe=7bd1df0e4d) | Nov 29, 2021 |
| Gigabyte      | B450 AORUS PRO-CF           | [24b15affa6](https://linux-hardware.org/?probe=24b15affa6) | Nov 29, 2021 |
| ASUSTek       | P8Z77-V LX                  | [b153db375f](https://linux-hardware.org/?probe=b153db375f) | Nov 29, 2021 |
| ECS           | GeForce6100PM-M2            | [032a2baaca](https://linux-hardware.org/?probe=032a2baaca) | Nov 28, 2021 |
| Lenovo        | 36E7 SDK0J40700 WIN 3258... | [382bfc4a86](https://linux-hardware.org/?probe=382bfc4a86) | Nov 28, 2021 |
| Gigabyte      | G31M-ES2L                   | [cd296f933b](https://linux-hardware.org/?probe=cd296f933b) | Nov 28, 2021 |
| Gigabyte      | G31M-ES2L                   | [44c0cf428f](https://linux-hardware.org/?probe=44c0cf428f) | Nov 28, 2021 |
| MSI           | X370 GAMING PLUS            | [0b71d2652d](https://linux-hardware.org/?probe=0b71d2652d) | Nov 27, 2021 |
| Dell          | 0VNP2H A00                  | [803e55fd86](https://linux-hardware.org/?probe=803e55fd86) | Nov 27, 2021 |
| ASUSTek       | M4A78T-E                    | [df3010e1b8](https://linux-hardware.org/?probe=df3010e1b8) | Nov 27, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [ae57475767](https://linux-hardware.org/?probe=ae57475767) | Nov 27, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [3925ce16ae](https://linux-hardware.org/?probe=3925ce16ae) | Nov 27, 2021 |
| Lenovo        | 36E7 SDK0J40700 WIN 3258... | [cd58d98b6a](https://linux-hardware.org/?probe=cd58d98b6a) | Nov 27, 2021 |
| ASRock        | B450M Pro4                  | [bb642022a6](https://linux-hardware.org/?probe=bb642022a6) | Nov 27, 2021 |
| ASRock        | ALiveNF6G-DVI               | [2761f434e8](https://linux-hardware.org/?probe=2761f434e8) | Nov 26, 2021 |
| HP            | 2179                        | [121210497a](https://linux-hardware.org/?probe=121210497a) | Nov 25, 2021 |
| Dell          | 0VNP2H A00                  | [fe9de9a896](https://linux-hardware.org/?probe=fe9de9a896) | Nov 25, 2021 |
| HP            | 18E7                        | [7385ca30d4](https://linux-hardware.org/?probe=7385ca30d4) | Nov 23, 2021 |
| Pegatron      | 2A86E01                     | [b57d9ec4a4](https://linux-hardware.org/?probe=b57d9ec4a4) | Nov 23, 2021 |
| Gigabyte      | H61N-USB3                   | [83e388363c](https://linux-hardware.org/?probe=83e388363c) | Nov 23, 2021 |
| Dell          | 0PU052                      | [a41541bab5](https://linux-hardware.org/?probe=a41541bab5) | Nov 23, 2021 |
| Gigabyte      | G41MT-S2                    | [8031417427](https://linux-hardware.org/?probe=8031417427) | Nov 23, 2021 |
| Intel         | DB65AL AAG12530-309         | [44c8025eee](https://linux-hardware.org/?probe=44c8025eee) | Nov 23, 2021 |
| MSI           | B360M PRO-VD                | [e1f68c6698](https://linux-hardware.org/?probe=e1f68c6698) | Nov 22, 2021 |
| Gigabyte      | H77M-D3H                    | [2819a870a8](https://linux-hardware.org/?probe=2819a870a8) | Nov 22, 2021 |
| HP            | 0AA4h                       | [22c6e4fffd](https://linux-hardware.org/?probe=22c6e4fffd) | Nov 22, 2021 |
| ASRock        | P67 Extreme6                | [54cd91039c](https://linux-hardware.org/?probe=54cd91039c) | Nov 22, 2021 |
| ASUSTek       | PRIME Z590M-PLUS            | [fa922e6e20](https://linux-hardware.org/?probe=fa922e6e20) | Nov 22, 2021 |
| ASRock        | 775i945GZ                   | [8d3cfee95d](https://linux-hardware.org/?probe=8d3cfee95d) | Nov 22, 2021 |
| ASRock        | ALiveNF6G-DVI               | [23a839f917](https://linux-hardware.org/?probe=23a839f917) | Nov 21, 2021 |
| ASUSTek       | PRIME Z590M-PLUS            | [ae91e01910](https://linux-hardware.org/?probe=ae91e01910) | Nov 21, 2021 |
| Dell          | 03NVJ6 A02                  | [00a8a0ab87](https://linux-hardware.org/?probe=00a8a0ab87) | Nov 21, 2021 |
| Gigabyte      | B450M GAMING                | [2355c29da1](https://linux-hardware.org/?probe=2355c29da1) | Nov 21, 2021 |
| Gigabyte      | H55M-UD2H                   | [16e0d2d71a](https://linux-hardware.org/?probe=16e0d2d71a) | Nov 21, 2021 |
| Dell          | 0KWVT8 A00                  | [a6f003d198](https://linux-hardware.org/?probe=a6f003d198) | Nov 20, 2021 |
| LattePanda    | Alpha                       | [24c2fc6f7b](https://linux-hardware.org/?probe=24c2fc6f7b) | Nov 20, 2021 |
| LattePanda    | Alpha                       | [4aa879f7ac](https://linux-hardware.org/?probe=4aa879f7ac) | Nov 20, 2021 |
| ASRock        | B450M Pro4 R2.0             | [8a53d67102](https://linux-hardware.org/?probe=8a53d67102) | Nov 19, 2021 |
| MSI           | 970 GAMING                  | [ac8f38525e](https://linux-hardware.org/?probe=ac8f38525e) | Nov 19, 2021 |
| ASUSTek       | P8Z77-V LX                  | [6807e3fa8c](https://linux-hardware.org/?probe=6807e3fa8c) | Nov 18, 2021 |
| Dell          | 0KWVT8 A00                  | [93b90c3da4](https://linux-hardware.org/?probe=93b90c3da4) | Nov 18, 2021 |
| ASRock        | G31M-VS2                    | [8bc6042d3f](https://linux-hardware.org/?probe=8bc6042d3f) | Nov 17, 2021 |
| ASRock        | X370M-HDV                   | [a991fee412](https://linux-hardware.org/?probe=a991fee412) | Nov 17, 2021 |
| Dell          | 0GXM1W A01                  | [7e9f638277](https://linux-hardware.org/?probe=7e9f638277) | Nov 17, 2021 |
| ASUSTek       | P5KPL-AM                    | [0cae2ebf49](https://linux-hardware.org/?probe=0cae2ebf49) | Nov 16, 2021 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | [bb50b7d97c](https://linux-hardware.org/?probe=bb50b7d97c) | Nov 16, 2021 |
| MSI           | 2A9C                        | [80ef0caf18](https://linux-hardware.org/?probe=80ef0caf18) | Nov 15, 2021 |
| MSI           | 2A9C                        | [44e1dcea05](https://linux-hardware.org/?probe=44e1dcea05) | Nov 15, 2021 |
| Gigabyte      | H170-D3HP-CF                | [e90a1881c7](https://linux-hardware.org/?probe=e90a1881c7) | Nov 14, 2021 |
| Fujitsu       | D2950-A1 S26361-D2950-A1    | [a92c32b60a](https://linux-hardware.org/?probe=a92c32b60a) | Nov 14, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [542b1538bf](https://linux-hardware.org/?probe=542b1538bf) | Nov 14, 2021 |
| HP            | 8653 A                      | [88b53507c9](https://linux-hardware.org/?probe=88b53507c9) | Nov 13, 2021 |
| HP            | 3048h                       | [200317605d](https://linux-hardware.org/?probe=200317605d) | Nov 13, 2021 |
| Dell          | 0GXM1W A02                  | [d446993ec9](https://linux-hardware.org/?probe=d446993ec9) | Nov 13, 2021 |
| ASUSTek       | P5G41T-M LX3                | [8977322809](https://linux-hardware.org/?probe=8977322809) | Nov 13, 2021 |
| HP            | 1790                        | [e86cdf904a](https://linux-hardware.org/?probe=e86cdf904a) | Nov 12, 2021 |
| ASUSTek       | M5A78L LE                   | [d342b54224](https://linux-hardware.org/?probe=d342b54224) | Nov 12, 2021 |
| HP            | 339A                        | [6dc037bf1f](https://linux-hardware.org/?probe=6dc037bf1f) | Nov 11, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [d0eae9ef10](https://linux-hardware.org/?probe=d0eae9ef10) | Nov 11, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | [7a2464824d](https://linux-hardware.org/?probe=7a2464824d) | Nov 11, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | [c8e4265515](https://linux-hardware.org/?probe=c8e4265515) | Nov 11, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [eece1d5528](https://linux-hardware.org/?probe=eece1d5528) | Nov 11, 2021 |
| ASUSTek       | H81M-P PLUS                 | [1841ab2aff](https://linux-hardware.org/?probe=1841ab2aff) | Nov 10, 2021 |
| ASUSTek       | A68HM-PLUS                  | [0e688f660f](https://linux-hardware.org/?probe=0e688f660f) | Nov 10, 2021 |
| ASUSTek       | M5A97                       | [20a705fd56](https://linux-hardware.org/?probe=20a705fd56) | Nov 10, 2021 |
| HP            | 8653 A                      | [f84c67582a](https://linux-hardware.org/?probe=f84c67582a) | Nov 09, 2021 |
| Gigabyte      | B450 AORUS PRO-CF           | [e7579f2fcf](https://linux-hardware.org/?probe=e7579f2fcf) | Nov 09, 2021 |
| HP            | 1790                        | [6030cabe49](https://linux-hardware.org/?probe=6030cabe49) | Nov 09, 2021 |
| HP            | 1825                        | [7cf6c3590a](https://linux-hardware.org/?probe=7cf6c3590a) | Nov 09, 2021 |
| Dell          | 0HD5W2 A00                  | [d4c15ae33a](https://linux-hardware.org/?probe=d4c15ae33a) | Nov 08, 2021 |
| MSI           | B450M MORTAR MAX            | [84c316ee57](https://linux-hardware.org/?probe=84c316ee57) | Nov 08, 2021 |
| Gigabyte      | B75M-D3H                    | [886c08185e](https://linux-hardware.org/?probe=886c08185e) | Nov 08, 2021 |
| Gigabyte      | B75M-D3H                    | [e141b2d36a](https://linux-hardware.org/?probe=e141b2d36a) | Nov 08, 2021 |
| Foxconn       | H61M/H61M-S                 | [62ae26dca0](https://linux-hardware.org/?probe=62ae26dca0) | Nov 07, 2021 |
| Dell          | 0HY9JP A00                  | [05c38bf92c](https://linux-hardware.org/?probe=05c38bf92c) | Nov 07, 2021 |
| ASUSTek       | A68HM-PLUS                  | [384fb31833](https://linux-hardware.org/?probe=384fb31833) | Nov 06, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [f57575ffaf](https://linux-hardware.org/?probe=f57575ffaf) | Nov 06, 2021 |
| Dell          | 0VNP2H A02                  | [5402226d98](https://linux-hardware.org/?probe=5402226d98) | Nov 06, 2021 |
| ASUSTek       | M5A78L-M LX                 | [e6e813115f](https://linux-hardware.org/?probe=e6e813115f) | Nov 06, 2021 |
| HP            | 0A98h                       | [110c37e799](https://linux-hardware.org/?probe=110c37e799) | Nov 06, 2021 |
| ASUSTek       | A68HM-PLUS                  | [7b21a0bc71](https://linux-hardware.org/?probe=7b21a0bc71) | Nov 06, 2021 |
| Dell          | 0NKW6Y A00                  | [82a09e132d](https://linux-hardware.org/?probe=82a09e132d) | Nov 05, 2021 |
| ASUSTek       | PRIME H410M-A               | [4be9b40ea1](https://linux-hardware.org/?probe=4be9b40ea1) | Nov 05, 2021 |
| ASUSTek       | PRIME H410M-A               | [173116149c](https://linux-hardware.org/?probe=173116149c) | Nov 05, 2021 |
| Gigabyte      | F2A78M-D3H                  | [43e09b8e80](https://linux-hardware.org/?probe=43e09b8e80) | Nov 05, 2021 |
| Gigabyte      | Z97X-UD7 TH-CF              | [1383828428](https://linux-hardware.org/?probe=1383828428) | Nov 05, 2021 |
| Gigabyte      | Z97X-UD7 TH-CF              | [f5ee7a26d5](https://linux-hardware.org/?probe=f5ee7a26d5) | Nov 05, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [3e4d5dd09d](https://linux-hardware.org/?probe=3e4d5dd09d) | Nov 05, 2021 |
| Foxconn       | H61M/H61M-S                 | [7f3894059d](https://linux-hardware.org/?probe=7f3894059d) | Nov 04, 2021 |
| HP            | 18E4                        | [3069846b25](https://linux-hardware.org/?probe=3069846b25) | Nov 04, 2021 |
| MSI           | G41M-P23                    | [82e51e3f78](https://linux-hardware.org/?probe=82e51e3f78) | Nov 04, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | [d7a405763d](https://linux-hardware.org/?probe=d7a405763d) | Nov 04, 2021 |
| ASUSTek       | P8Z77-V LX                  | [d59cc9fead](https://linux-hardware.org/?probe=d59cc9fead) | Nov 04, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [2d26d5b578](https://linux-hardware.org/?probe=2d26d5b578) | Nov 02, 2021 |
| ASUSTek       | P8Z77-V LX                  | [903ec63ceb](https://linux-hardware.org/?probe=903ec63ceb) | Nov 02, 2021 |
| ASUSTek       | M11AD                       | [0cb5032c53](https://linux-hardware.org/?probe=0cb5032c53) | Nov 02, 2021 |
| Gigabyte      | GA-E6010N                   | [3c81474040](https://linux-hardware.org/?probe=3c81474040) | Nov 01, 2021 |
| Gigabyte      | GA-E6010N                   | [2a2aaffd43](https://linux-hardware.org/?probe=2a2aaffd43) | Nov 01, 2021 |
| ASRock        | FM2A55M-HD+                 | [42cd4d28bd](https://linux-hardware.org/?probe=42cd4d28bd) | Nov 01, 2021 |
| eMachines     | EL1850G                     | [01dbf1b5ec](https://linux-hardware.org/?probe=01dbf1b5ec) | Oct 31, 2021 |
| MSI           | P55-CD53                    | [860bde5935](https://linux-hardware.org/?probe=860bde5935) | Oct 31, 2021 |
| Unknown       | Unknown                     | [75cc8a67e9](https://linux-hardware.org/?probe=75cc8a67e9) | Oct 31, 2021 |
| ASRock        | B85M-HDS                    | [111e98ddef](https://linux-hardware.org/?probe=111e98ddef) | Oct 31, 2021 |
| ASUSTek       | P8H61-M LE/CSM R2.0         | [6cee757cf0](https://linux-hardware.org/?probe=6cee757cf0) | Oct 31, 2021 |
| ASUSTek       | P8H61-M LE/CSM R2.0         | [96c9053284](https://linux-hardware.org/?probe=96c9053284) | Oct 31, 2021 |
| Dell          | 06NWYK A01                  | [497c824fd5](https://linux-hardware.org/?probe=497c824fd5) | Oct 31, 2021 |
| ASRock        | B85M-HDS                    | [69dd0cf598](https://linux-hardware.org/?probe=69dd0cf598) | Oct 30, 2021 |
| Dell          | 06NWYK A01                  | [1d0625eb89](https://linux-hardware.org/?probe=1d0625eb89) | Oct 30, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [867e533368](https://linux-hardware.org/?probe=867e533368) | Oct 30, 2021 |
| ASUSTek       | P5K SE/EPU                  | [80adff7646](https://linux-hardware.org/?probe=80adff7646) | Oct 30, 2021 |
| Dell          | 0GY6Y8 A02                  | [1a267b14d3](https://linux-hardware.org/?probe=1a267b14d3) | Oct 29, 2021 |
| Dell          | 0GY6Y8 A02                  | [5b4cea000b](https://linux-hardware.org/?probe=5b4cea000b) | Oct 29, 2021 |
| ASRock        | B450 Gaming K4              | [b67ec8af25](https://linux-hardware.org/?probe=b67ec8af25) | Oct 29, 2021 |
| Dell          | 0VNP2H A02                  | [4e19df8e3c](https://linux-hardware.org/?probe=4e19df8e3c) | Oct 29, 2021 |
| Dell          | 0VNP2H A02                  | [c220480b4c](https://linux-hardware.org/?probe=c220480b4c) | Oct 29, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [a73fabcd4c](https://linux-hardware.org/?probe=a73fabcd4c) | Oct 28, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [528cec41bc](https://linux-hardware.org/?probe=528cec41bc) | Oct 28, 2021 |
| Alienware     | 08PG26 A00                  | [bb2fd997ab](https://linux-hardware.org/?probe=bb2fd997ab) | Oct 28, 2021 |
| ASRock        | FM2A88X Extreme6+           | [b676d9030a](https://linux-hardware.org/?probe=b676d9030a) | Oct 28, 2021 |
| MSI           | MAG B550M MORTAR            | [08819513f2](https://linux-hardware.org/?probe=08819513f2) | Oct 27, 2021 |
| MSI           | MAG B550M MORTAR            | [4207c6eaac](https://linux-hardware.org/?probe=4207c6eaac) | Oct 27, 2021 |
| ASUSTek       | PRIME Z270-P                | [dfb2070b53](https://linux-hardware.org/?probe=dfb2070b53) | Oct 26, 2021 |
| Alienware     | 08PG26 A00                  | [7d6b559bf8](https://linux-hardware.org/?probe=7d6b559bf8) | Oct 26, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [3862cf57e0](https://linux-hardware.org/?probe=3862cf57e0) | Oct 25, 2021 |
| ASRock        | FM2A55M-HD+                 | [a1cf5282ba](https://linux-hardware.org/?probe=a1cf5282ba) | Oct 25, 2021 |
| ASRock        | H110M-HDS R3.0              | [718ad346b7](https://linux-hardware.org/?probe=718ad346b7) | Oct 25, 2021 |
| MSI           | 2AE0                        | [64a3b3ae41](https://linux-hardware.org/?probe=64a3b3ae41) | Oct 24, 2021 |
| Fujitsu       | D2950-A1 S26361-D2950-A1    | [cc46a59d6c](https://linux-hardware.org/?probe=cc46a59d6c) | Oct 24, 2021 |
| MSI           | P55-CD53                    | [c1c364dbc1](https://linux-hardware.org/?probe=c1c364dbc1) | Oct 24, 2021 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | [fca2aa4310](https://linux-hardware.org/?probe=fca2aa4310) | Oct 23, 2021 |
| Dell          | 0VHXCD A00                  | [7c99a6ed29](https://linux-hardware.org/?probe=7c99a6ed29) | Oct 22, 2021 |
| ASRock        | 970 Pro3 R2.0               | [915961c057](https://linux-hardware.org/?probe=915961c057) | Oct 22, 2021 |
| Biostar       | A68N-5100                   | [bc5b7a2417](https://linux-hardware.org/?probe=bc5b7a2417) | Oct 22, 2021 |
| MSI           | Z68A-G43                    | [b781916d8e](https://linux-hardware.org/?probe=b781916d8e) | Oct 22, 2021 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [baee5192b6](https://linux-hardware.org/?probe=baee5192b6) | Oct 22, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [666f084a0f](https://linux-hardware.org/?probe=666f084a0f) | Oct 21, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [395d19ae36](https://linux-hardware.org/?probe=395d19ae36) | Oct 21, 2021 |
| HP            | 1589                        | [49c747efad](https://linux-hardware.org/?probe=49c747efad) | Oct 21, 2021 |
| Unknown       | Phitronics G41-M3           | [a6ccedb5bd](https://linux-hardware.org/?probe=a6ccedb5bd) | Oct 20, 2021 |
| Unknown       | Phitronics G41-M3           | [fbe886aee7](https://linux-hardware.org/?probe=fbe886aee7) | Oct 20, 2021 |
| Unknown       | Unknown                     | [8c412b3b5b](https://linux-hardware.org/?probe=8c412b3b5b) | Oct 20, 2021 |
| Gigabyte      | B75M-D2V                    | [9fc60b0ba8](https://linux-hardware.org/?probe=9fc60b0ba8) | Oct 19, 2021 |
| HP            | 2B38                        | [2cf327f158](https://linux-hardware.org/?probe=2cf327f158) | Oct 18, 2021 |
| ASUSTek       | M5A97 LE R2.0               | [2f5f509752](https://linux-hardware.org/?probe=2f5f509752) | Oct 18, 2021 |
| Gigabyte      | Z490 AORUS ELITE            | [a7ea75f7c5](https://linux-hardware.org/?probe=a7ea75f7c5) | Oct 18, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Zorin_16/Desktop/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Desktops | Percent |
|----------------------|----------|---------|
| 5.11.0-38-generic    | 62       | 6.78%   |
| 5.11.0-27-generic    | 56       | 6.12%   |
| 5.15.0-46-generic    | 54       | 5.9%    |
| 5.11.0-40-generic    | 50       | 5.46%   |
| 5.13.0-39-generic    | 48       | 5.25%   |
| 5.15.0-52-generic    | 45       | 4.92%   |
| 5.11.0-41-generic    | 41       | 4.48%   |
| 5.15.0-48-generic    | 40       | 4.37%   |
| 5.13.0-40-generic    | 38       | 4.15%   |
| 5.13.0-30-generic    | 38       | 4.15%   |
| 5.11.0-43-generic    | 36       | 3.93%   |
| 5.15.0-41-generic    | 35       | 3.83%   |
| 5.11.0-37-generic    | 35       | 3.83%   |
| 5.11.0-34-generic    | 31       | 3.39%   |
| 5.13.0-28-generic    | 30       | 3.28%   |
| 5.13.0-35-generic    | 28       | 3.06%   |
| 5.13.0-27-generic    | 26       | 2.84%   |
| 5.13.0-41-generic    | 25       | 2.73%   |
| 5.13.0-52-generic    | 24       | 2.62%   |
| 5.15.0-53-generic    | 23       | 2.51%   |
| 5.13.0-44-generic    | 21       | 2.3%    |
| 5.13.0-51-generic    | 17       | 1.86%   |
| 5.11.0-44-generic    | 13       | 1.42%   |
| 5.15.0-43-generic    | 12       | 1.31%   |
| 5.11.0-36-generic    | 12       | 1.31%   |
| 5.13.0-37-generic    | 11       | 1.2%    |
| 5.8.0-53-generic     | 7        | 0.77%   |
| 5.15.0-50-generic    | 7        | 0.77%   |
| 5.13.0-48-generic    | 7        | 0.77%   |
| 5.8.0-50-generic     | 5        | 0.55%   |
| 5.11.0-46-generic    | 5        | 0.55%   |
| 5.8.0-59-generic     | 4        | 0.44%   |
| 5.8.0-55-generic     | 4        | 0.44%   |
| 5.11.0-25-generic    | 4        | 0.44%   |
| 5.8.0-49-generic     | 3        | 0.33%   |
| 5.8.0-63-generic     | 2        | 0.22%   |
| 5.13.0-25-generic    | 2        | 0.22%   |
| 6.0.8-060008-generic | 1        | 0.11%   |
| 5.8.0-45-generic     | 1        | 0.11%   |
| 5.4.0-58-generic     | 1        | 0.11%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11.0  | 333      | 38.5%   |
| 5.13.0  | 288      | 33.29%  |
| 5.15.0  | 209      | 24.16%  |
| 5.8.0   | 25       | 2.89%   |
| 6.0.8   | 1        | 0.12%   |
| 5.4.0   | 1        | 0.12%   |
| 5.19.6  | 1        | 0.12%   |
| 5.19.2  | 1        | 0.12%   |
| 5.19.12 | 1        | 0.12%   |
| 5.17.9  | 1        | 0.12%   |
| 5.17.5  | 1        | 0.12%   |
| 5.17.1  | 1        | 0.12%   |
| 5.15.13 | 1        | 0.12%   |
| 5.14.0  | 1        | 0.12%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11    | 333      | 38.5%   |
| 5.13    | 288      | 33.29%  |
| 5.15    | 210      | 24.28%  |
| 5.8     | 25       | 2.89%   |
| 5.19    | 3        | 0.35%   |
| 5.17    | 3        | 0.35%   |
| 6.0     | 1        | 0.12%   |
| 5.4     | 1        | 0.12%   |
| 5.14    | 1        | 0.12%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 825      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 737      | 88.9%   |
| XFCE       | 84       | 10.13%  |
| Unknown    | 5        | 0.6%    |
| X-Cinnamon | 1        | 0.12%   |
| MATE       | 1        | 0.12%   |
| Cinnamon   | 1        | 0.12%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 821      | 99.15%  |
| Wayland | 5        | 0.6%    |
| Tty     | 1        | 0.12%   |
| Unknown | 1        | 0.12%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 694      | 83.51%  |
| GDM3    | 67       | 8.06%   |
| GDM     | 56       | 6.74%   |
| LightDM | 13       | 1.56%   |
| TDM     | 1        | 0.12%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| en_US       | 331      | 40.02%  |
| de_DE       | 87       | 10.52%  |
| en_GB       | 66       | 7.98%   |
| pt_BR       | 59       | 7.13%   |
| fr_FR       | 22       | 2.66%   |
| pl_PL       | 21       | 2.54%   |
| it_IT       | 20       | 2.42%   |
| en_IN       | 19       | 2.3%    |
| en_AU       | 19       | 2.3%    |
| nl_NL       | 18       | 2.18%   |
| es_ES       | 18       | 2.18%   |
| en_CA       | 18       | 2.18%   |
| ru_RU       | 12       | 1.45%   |
| es_MX       | 10       | 1.21%   |
| es_AR       | 10       | 1.21%   |
| hu_HU       | 7        | 0.85%   |
| fr_CA       | 7        | 0.85%   |
| en_ZA       | 6        | 0.73%   |
| cs_CZ       | 6        | 0.73%   |
| tr_TR       | 4        | 0.48%   |
| pt_PT       | 4        | 0.48%   |
| nl_BE       | 4        | 0.48%   |
| el_GR       | 4        | 0.48%   |
| sv_SE       | 3        | 0.36%   |
| nb_NO       | 3        | 0.36%   |
| es_CL       | 3        | 0.36%   |
| en_NZ       | 3        | 0.36%   |
| da_DK       | 3        | 0.36%   |
| sl_SI       | 2        | 0.24%   |
| sk_SK       | 2        | 0.24%   |
| ja_JP       | 2        | 0.24%   |
| es_VE       | 2        | 0.24%   |
| es_US       | 2        | 0.24%   |
| es_EC       | 2        | 0.24%   |
| en_PH       | 2        | 0.24%   |
| de_CH       | 2        | 0.24%   |
| ar_EG       | 2        | 0.24%   |
| zh_TW       | 1        | 0.12%   |
| zh_CN       | 1        | 0.12%   |
| sr_RS@latin | 1        | 0.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 462      | 55.53%  |
| EFI  | 370      | 44.47%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 780      | 94.43%  |
| Zfs      | 19       | 2.3%    |
| Overlay  | 11       | 1.33%   |
| Btrfs    | 8        | 0.97%   |
| Xfs      | 3        | 0.36%   |
| Ext3     | 2        | 0.24%   |
| Ext2     | 2        | 0.24%   |
| Reiserfs | 1        | 0.12%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 746      | 90.21%  |
| GPT     | 56       | 6.77%   |
| MBR     | 25       | 3.02%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 799      | 96.73%  |
| Yes       | 27       | 3.27%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 735      | 88.98%  |
| Yes       | 91       | 11.02%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 202      | 24.48%  |
| Gigabyte Technology | 135      | 16.36%  |
| Dell                | 89       | 10.79%  |
| MSI                 | 83       | 10.06%  |
| Hewlett-Packard     | 81       | 9.82%   |
| ASRock              | 65       | 7.88%   |
| Lenovo              | 37       | 4.48%   |
| Intel               | 22       | 2.67%   |
| Biostar             | 13       | 1.58%   |
| Fujitsu             | 11       | 1.33%   |
| Acer                | 11       | 1.33%   |
| Foxconn             | 10       | 1.21%   |
| Pegatron            | 8        | 0.97%   |
| Unknown             | 7        | 0.85%   |
| OEM                 | 4        | 0.48%   |
| BESSTAR Tech        | 4        | 0.48%   |
| Gateway             | 3        | 0.36%   |
| Apple               | 3        | 0.36%   |
| Alienware           | 3        | 0.36%   |
| Shuttle             | 2        | 0.24%   |
| Positivo            | 2        | 0.24%   |
| Medion              | 2        | 0.24%   |
| JGINYUE             | 2        | 0.24%   |
| Huanan              | 2        | 0.24%   |
| Google              | 2        | 0.24%   |
| ECS                 | 2        | 0.24%   |
| Wortmann AG         | 1        | 0.12%   |
| WIPRO               | 1        | 0.12%   |
| TYAN Computer       | 1        | 0.12%   |
| System76            | 1        | 0.12%   |
| Supermicro          | 1        | 0.12%   |
| Seco                | 1        | 0.12%   |
| Sapphire            | 1        | 0.12%   |
| Packard Bell        | 1        | 0.12%   |
| OEM_MB              | 1        | 0.12%   |
| NCR                 | 1        | 0.12%   |
| MP                  | 1        | 0.12%   |
| Megaware            | 1        | 0.12%   |
| MAXSUN              | 1        | 0.12%   |
| LORD ELECTRONICS    | 1        | 0.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| ASUS All Series                  | 22       | 2.67%   |
| Dell OptiPlex 7010               | 8        | 0.97%   |
| Unknown                          | 8        | 0.97%   |
| Dell OptiPlex 790                | 7        | 0.85%   |
| Dell OptiPlex 780                | 6        | 0.73%   |
| MSI MS-7C02                      | 5        | 0.61%   |
| MSI MS-7817                      | 5        | 0.61%   |
| Dell OptiPlex 990                | 5        | 0.61%   |
| Dell OptiPlex 380                | 5        | 0.61%   |
| ASUS M5A78L-M/USB3               | 5        | 0.61%   |
| HP ProDesk 600 G1 SFF            | 4        | 0.48%   |
| HP Compaq Pro 6300 SFF           | 4        | 0.48%   |
| Gigabyte B450 AORUS M            | 4        | 0.48%   |
| Gigabyte A320M-S2H               | 4        | 0.48%   |
| Dell Precision WorkStation T3500 | 4        | 0.48%   |
| ASUS TUF Gaming X570-PLUS        | 4        | 0.48%   |
| ASRock B450 Pro4                 | 4        | 0.48%   |
| OEM G41 775 ICH7 8712            | 3        | 0.36%   |
| Intel X79M-S                     | 3        | 0.36%   |
| HP ProDesk 600 G1 TWR            | 3        | 0.36%   |
| HP Compaq 6200 Pro SFF PC        | 3        | 0.36%   |
| Gigabyte X570 AORUS ELITE        | 3        | 0.36%   |
| Gigabyte GA-78LMT-S2             | 3        | 0.36%   |
| Dell OptiPlex 360                | 3        | 0.36%   |
| Dell OptiPlex 3010               | 3        | 0.36%   |
| Dell Inspiron 3847               | 3        | 0.36%   |
| ASUS ROG STRIX B450-F GAMING     | 3        | 0.36%   |
| ASUS ROG CROSSHAIR VIII HERO     | 3        | 0.36%   |
| ASUS PRIME X570-PRO              | 3        | 0.36%   |
| ASUS PRIME X570-P                | 3        | 0.36%   |
| ASUS PRIME B450M-GAMING/BR       | 3        | 0.36%   |
| ASUS P8Z77-V LX                  | 3        | 0.36%   |
| ASUS M5A97 R2.0                  | 3        | 0.36%   |
| ASRock B450M Pro4                | 3        | 0.36%   |
| Pegatron NE502AV-ABA a6750t      | 2        | 0.24%   |
| MSI MS-7D19                      | 2        | 0.24%   |
| MSI MS-7C94                      | 2        | 0.24%   |
| MSI MS-7C56                      | 2        | 0.24%   |
| MSI MS-7C37                      | 2        | 0.24%   |
| MSI MS-7B89                      | 2        | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 54       | 6.55%   |
| ASUS PRIME             | 32       | 3.88%   |
| ASUS ROG               | 25       | 3.03%   |
| Lenovo ThinkCentre     | 23       | 2.79%   |
| HP Compaq              | 22       | 2.67%   |
| ASUS All               | 22       | 2.67%   |
| ASUS TUF               | 15       | 1.82%   |
| HP EliteDesk           | 11       | 1.33%   |
| Gigabyte B450          | 9        | 1.09%   |
| Dell Precision         | 9        | 1.09%   |
| HP ProDesk             | 8        | 0.97%   |
| Fujitsu ESPRIMO        | 8        | 0.97%   |
| Dell Inspiron          | 8        | 0.97%   |
| ASUS M5A78L-M          | 8        | 0.97%   |
| Unknown                | 8        | 0.97%   |
| Gigabyte X570          | 7        | 0.85%   |
| ASRock B450            | 7        | 0.85%   |
| Acer Aspire            | 7        | 0.85%   |
| ASUS M5A97             | 6        | 0.73%   |
| ASRock B450M           | 6        | 0.73%   |
| MSI MS-7C02            | 5        | 0.61%   |
| MSI MS-7817            | 5        | 0.61%   |
| Lenovo IdeaCentre      | 5        | 0.61%   |
| HP Pavilion            | 5        | 0.61%   |
| Gigabyte GA-78LMT-USB3 | 5        | 0.61%   |
| Gigabyte B450M         | 5        | 0.61%   |
| Gigabyte A320M-S2H     | 5        | 0.61%   |
| Dell XPS               | 5        | 0.61%   |
| Dell Vostro            | 5        | 0.61%   |
| ASUS P8H61-M           | 5        | 0.61%   |
| ASUS P8Z77-V           | 4        | 0.48%   |
| OEM G41                | 3        | 0.36%   |
| Intel X79M-S           | 3        | 0.36%   |
| HP Z220                | 3        | 0.36%   |
| HP 290                 | 3        | 0.36%   |
| Gigabyte Z390          | 3        | 0.36%   |
| Gigabyte GA-78LMT-S2   | 3        | 0.36%   |
| Gigabyte G1.Sniper     | 3        | 0.36%   |
| Dell Studio            | 3        | 0.36%   |
| ASUS P7H55-M           | 3        | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2013    | 82       | 9.94%   |
| 2012    | 82       | 9.94%   |
| 2018    | 80       | 9.7%    |
| 2011    | 71       | 8.61%   |
| 2014    | 67       | 8.12%   |
| 2019    | 61       | 7.39%   |
| 2020    | 56       | 6.79%   |
| 2021    | 50       | 6.06%   |
| 2010    | 49       | 5.94%   |
| 2016    | 41       | 4.97%   |
| 2009    | 41       | 4.97%   |
| 2008    | 40       | 4.85%   |
| 2017    | 36       | 4.36%   |
| 2007    | 24       | 2.91%   |
| 2015    | 22       | 2.67%   |
| 2006    | 9        | 1.09%   |
| 2022    | 8        | 0.97%   |
| 2005    | 4        | 0.48%   |
| Unknown | 2        | 0.24%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 825      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 780      | 94.2%   |
| Enabled  | 48       | 5.8%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 823      | 99.76%  |
| Yes  | 2        | 0.24%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 208      | 24.97%  |
| 8.01-16.0   | 199      | 23.89%  |
| 4.01-8.0    | 123      | 14.77%  |
| 3.01-4.0    | 120      | 14.41%  |
| 32.01-64.0  | 113      | 13.57%  |
| 64.01-256.0 | 25       | 3%      |
| 1.01-2.0    | 20       | 2.4%    |
| 24.01-32.0  | 13       | 1.56%   |
| 2.01-3.0    | 11       | 1.32%   |
| 0.51-1.0    | 1        | 0.12%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 350      | 39.86%  |
| 2.01-3.0   | 273      | 31.09%  |
| 4.01-8.0   | 110      | 12.53%  |
| 3.01-4.0   | 110      | 12.53%  |
| 8.01-16.0  | 20       | 2.28%   |
| 0.51-1.0   | 10       | 1.14%   |
| 16.01-24.0 | 4        | 0.46%   |
| 0.01-0.5   | 1        | 0.11%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 364      | 43.13%  |
| 2      | 242      | 28.67%  |
| 3      | 107      | 12.68%  |
| 4      | 54       | 6.4%    |
| 5      | 34       | 4.03%   |
| 6      | 22       | 2.61%   |
| 7      | 7        | 0.83%   |
| 8      | 6        | 0.71%   |
| 0      | 6        | 0.71%   |
| 51     | 1        | 0.12%   |
| 11     | 1        | 0.12%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 436      | 52.59%  |
| No        | 393      | 47.41%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 815      | 98.79%  |
| No        | 10       | 1.21%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 415      | 50.06%  |
| No        | 414      | 49.94%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 560      | 67.23%  |
| Yes       | 273      | 32.77%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 208      | 25.15%  |
| Germany      | 90       | 10.88%  |
| UK           | 61       | 7.38%   |
| Brazil       | 61       | 7.38%   |
| Canada       | 29       | 3.51%   |
| Netherlands  | 28       | 3.39%   |
| Italy        | 26       | 3.14%   |
| Poland       | 23       | 2.78%   |
| France       | 21       | 2.54%   |
| Spain        | 20       | 2.42%   |
| Australia    | 20       | 2.42%   |
| India        | 19       | 2.3%    |
| Argentina    | 12       | 1.45%   |
| Mexico       | 11       | 1.33%   |
| Hungary      | 11       | 1.33%   |
| Denmark      | 11       | 1.33%   |
| Russia       | 10       | 1.21%   |
| Norway       | 9        | 1.09%   |
| Sweden       | 8        | 0.97%   |
| Greece       | 8        | 0.97%   |
| Egypt        | 8        | 0.97%   |
| Switzerland  | 6        | 0.73%   |
| South Africa | 6        | 0.73%   |
| Serbia       | 6        | 0.73%   |
| Malaysia     | 6        | 0.73%   |
| Czechia      | 6        | 0.73%   |
| Turkey       | 5        | 0.6%    |
| Slovenia     | 5        | 0.6%    |
| Romania      | 5        | 0.6%    |
| Portugal     | 5        | 0.6%    |
| Chile        | 5        | 0.6%    |
| Belgium      | 5        | 0.6%    |
| Croatia      | 4        | 0.48%   |
| Venezuela    | 3        | 0.36%   |
| Ukraine      | 3        | 0.36%   |
| Slovakia     | 3        | 0.36%   |
| New Zealand  | 3        | 0.36%   |
| Japan        | 3        | 0.36%   |
| Austria      | 3        | 0.36%   |
| Vietnam      | 2        | 0.24%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Berlin         | 8        | 0.95%   |
| Munich         | 7        | 0.83%   |
| Athens         | 7        | 0.83%   |
| Sao Paulo      | 5        | 0.6%    |
| Rio de Janeiro | 5        | 0.6%    |
| Dallas         | 5        | 0.6%    |
| Buenos Aires   | 5        | 0.6%    |
| Portland       | 4        | 0.48%   |
| Milan          | 4        | 0.48%   |
| Houston        | 4        | 0.48%   |
| Denver         | 4        | 0.48%   |
| Copenhagen     | 4        | 0.48%   |
| Adelaide       | 4        | 0.48%   |
| Vienna         | 3        | 0.36%   |
| Sydney         | 3        | 0.36%   |
| Stuttgart      | 3        | 0.36%   |
| Richmond       | 3        | 0.36%   |
| Prague         | 3        | 0.36%   |
| Phoenix        | 3        | 0.36%   |
| Milwaukee      | 3        | 0.36%   |
| Mentor         | 3        | 0.36%   |
| Los Angeles    | 3        | 0.36%   |
| Laval          | 3        | 0.36%   |
| Hamburg        | 3        | 0.36%   |
| Fortaleza      | 3        | 0.36%   |
| Dayton         | 3        | 0.36%   |
| Cape Town      | 3        | 0.36%   |
| Cairo          | 3        | 0.36%   |
| Budapest       | 3        | 0.36%   |
| Brisbane       | 3        | 0.36%   |
| Brasília      | 3        | 0.36%   |
| Bengaluru      | 3        | 0.36%   |
| Belgrade       | 3        | 0.36%   |
| Almería       | 3        | 0.36%   |
| Zurich         | 2        | 0.24%   |
| Zagreb         | 2        | 0.24%   |
| Wylie          | 2        | 0.24%   |
| Wuppertal      | 2        | 0.24%   |
| Warsaw         | 2        | 0.24%   |
| Vrhnika        | 2        | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 307      | 465    | 20.9%   |
| WDC                       | 239      | 346    | 16.27%  |
| Samsung Electronics       | 185      | 287    | 12.59%  |
| Kingston                  | 97       | 130    | 6.6%    |
| Toshiba                   | 80       | 135    | 5.45%   |
| SanDisk                   | 78       | 91     | 5.31%   |
| Hitachi                   | 64       | 80     | 4.36%   |
| Crucial                   | 60       | 73     | 4.08%   |
| A-DATA Technology         | 22       | 27     | 1.5%    |
| Unknown                   | 19       | 34     | 1.29%   |
| Phison                    | 19       | 21     | 1.29%   |
| Silicon Motion            | 18       | 25     | 1.23%   |
| China                     | 17       | 19     | 1.16%   |
| Intel                     | 15       | 18     | 1.02%   |
| HGST                      | 12       | 20     | 0.82%   |
| SK hynix                  | 11       | 15     | 0.75%   |
| PNY                       | 10       | 14     | 0.68%   |
| Patriot                   | 10       | 12     | 0.68%   |
| Intenso                   | 10       | 11     | 0.68%   |
| OCZ                       | 9        | 11     | 0.61%   |
| Micron Technology         | 8        | 8      | 0.54%   |
| Lexar                     | 8        | 8      | 0.54%   |
| Hewlett-Packard           | 8        | 12     | 0.54%   |
| SPCC                      | 7        | 8      | 0.48%   |
| Maxtor                    | 7        | 8      | 0.48%   |
| GOODRAM                   | 7        | 7      | 0.48%   |
| Gigabyte Technology       | 7        | 9      | 0.48%   |
| XPG                       | 6        | 7      | 0.41%   |
| KingSpec                  | 6        | 8      | 0.41%   |
| JMicron Technology        | 6        | 8      | 0.41%   |
| Realtek Semiconductor     | 5        | 5      | 0.34%   |
| Micron/Crucial Technology | 5        | 5      | 0.34%   |
| Leven                     | 5        | 6      | 0.34%   |
| Apacer                    | 5        | 6      | 0.34%   |
| Team                      | 4        | 6      | 0.27%   |
| Super Talent              | 4        | 5      | 0.27%   |
| SABRENT                   | 4        | 4      | 0.27%   |
| Netac                     | 4        | 5      | 0.27%   |
| HS-SSD-C100               | 4        | 4      | 0.27%   |
| Corsair                   | 4        | 4      | 0.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 35       | 2.04%   |
| Kingston SA400S37240G 240GB SSD  | 26       | 1.52%   |
| Seagate ST1000DM010-2EP102 1TB   | 22       | 1.28%   |
| Samsung SSD 860 EVO 500GB        | 18       | 1.05%   |
| Samsung NVMe SSD Drive 1TB       | 17       | 0.99%   |
| Crucial CT240BX500SSD1 240GB     | 17       | 0.99%   |
| WDC WD10EZEX-08WN4A0 1TB         | 15       | 0.88%   |
| Samsung SSD 850 EVO 250GB        | 14       | 0.82%   |
| Samsung NVMe SSD Drive 500GB     | 14       | 0.82%   |
| Seagate ST3500418AS 500GB        | 12       | 0.7%    |
| Seagate ST2000DM008-2FR102 2TB   | 12       | 0.7%    |
| Seagate ST1000DM003-1SB102 1TB   | 12       | 0.7%    |
| Seagate ST1000DM003-1CH162 1TB   | 12       | 0.7%    |
| Toshiba HDWD110 1TB              | 11       | 0.64%   |
| Kingston SA400S37480G 480GB SSD  | 11       | 0.64%   |
| Kingston SA400S37120G 120GB SSD  | 11       | 0.64%   |
| Toshiba DT01ACA100 1TB           | 10       | 0.58%   |
| Seagate ST3500413AS 500GB        | 10       | 0.58%   |
| Seagate ST3500312CS 500GB        | 10       | 0.58%   |
| SanDisk NVMe SSD Drive 500GB     | 10       | 0.58%   |
| SanDisk NVMe SSD Drive 1TB       | 10       | 0.58%   |
| Toshiba DT01ACA050 500GB         | 9        | 0.53%   |
| Samsung HD103SJ 1TB              | 9        | 0.53%   |
| Kingston SV300S37A120G 120GB SSD | 9        | 0.53%   |
| Crucial CT1000MX500SSD1 1TB      | 9        | 0.53%   |
| Unknown SD/MMC/MS PRO 8GB        | 8        | 0.47%   |
| Seagate ST2000DM001-1ER164 2TB   | 8        | 0.47%   |
| Seagate ST2000DM001-1CH164 2TB   | 8        | 0.47%   |
| SanDisk SSD PLUS 240GB           | 8        | 0.47%   |
| Samsung SSD 840 EVO 250GB        | 8        | 0.47%   |
| WDC WD10EZEX-00WN4A0 1TB         | 7        | 0.41%   |
| Seagate ST1000DM003-1ER162 1TB   | 7        | 0.41%   |
| Seagate Expansion Desk 8TB       | 7        | 0.41%   |
| Samsung SSD 870 EVO 1TB          | 7        | 0.41%   |
| Samsung SSD 850 EVO 500GB        | 7        | 0.41%   |
| Samsung SSD 840 EVO 120GB        | 7        | 0.41%   |
| Crucial CT500MX500SSD1 500GB     | 7        | 0.41%   |
| Seagate ST4000DM004-2CV104 4TB   | 6        | 0.35%   |
| Seagate ST4000DM000-1F2168 4TB   | 6        | 0.35%   |
| Seagate Expansion 1TB            | 6        | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 303      | 450    | 41.56%  |
| WDC                 | 221      | 311    | 30.32%  |
| Toshiba             | 69       | 123    | 9.47%   |
| Hitachi             | 64       | 80     | 8.78%   |
| Samsung Electronics | 39       | 52     | 5.35%   |
| HGST                | 12       | 20     | 1.65%   |
| Unknown             | 8        | 11     | 1.1%    |
| Maxtor              | 7        | 8      | 0.96%   |
| Hewlett-Packard     | 3        | 6      | 0.41%   |
| Apple               | 2        | 2      | 0.27%   |
| USB3.0              | 1        | 2      | 0.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 105      | 149    | 19.77%  |
| Kingston            | 80       | 102    | 15.07%  |
| Crucial             | 59       | 72     | 11.11%  |
| SanDisk             | 54       | 64     | 10.17%  |
| WDC                 | 24       | 29     | 4.52%   |
| A-DATA Technology   | 21       | 26     | 3.95%   |
| China               | 16       | 18     | 3.01%   |
| PNY                 | 10       | 14     | 1.88%   |
| Intel               | 10       | 12     | 1.88%   |
| Patriot             | 9        | 11     | 1.69%   |
| OCZ                 | 9        | 11     | 1.69%   |
| Lexar               | 8        | 8      | 1.51%   |
| SPCC                | 7        | 8      | 1.32%   |
| Intenso             | 7        | 8      | 1.32%   |
| Toshiba             | 6        | 6      | 1.13%   |
| Micron Technology   | 6        | 6      | 1.13%   |
| KingSpec            | 6        | 8      | 1.13%   |
| GOODRAM             | 6        | 6      | 1.13%   |
| Gigabyte Technology | 6        | 7      | 1.13%   |
| SK hynix            | 5        | 5      | 0.94%   |
| Leven               | 5        | 6      | 0.94%   |
| Hewlett-Packard     | 5        | 6      | 0.94%   |
| Apacer              | 5        | 6      | 0.94%   |
| Team                | 4        | 6      | 0.75%   |
| Super Talent        | 4        | 5      | 0.75%   |
| Netac               | 4        | 5      | 0.75%   |
| Seagate             | 3        | 5      | 0.56%   |
| JMicron Technology  | 3        | 4      | 0.56%   |
| Transcend           | 2        | 2      | 0.38%   |
| Plextor             | 2        | 3      | 0.38%   |
| Pioneer             | 2        | 2      | 0.38%   |
| KIOXIA-EXCERIA      | 2        | 5      | 0.38%   |
| Drevo               | 2        | 3      | 0.38%   |
| Dogfish             | 2        | 3      | 0.38%   |
| Corsair             | 2        | 2      | 0.38%   |
| Acer                | 2        | 3      | 0.38%   |
| Unknown             | 2        | 2      | 0.38%   |
| Zheino              | 1        | 1      | 0.19%   |
| XPG                 | 1        | 1      | 0.19%   |
| Verbatim            | 1        | 1      | 0.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 558      | 1065   | 45.26%  |
| SSD     | 444      | 666    | 36.01%  |
| NVMe    | 182      | 257    | 14.76%  |
| Unknown | 44       | 61     | 3.57%   |
| MMC     | 5        | 6      | 0.41%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 771      | 1695   | 75.29%  |
| NVMe | 180      | 251    | 17.58%  |
| SAS  | 68       | 103    | 6.64%   |
| MMC  | 5        | 6      | 0.49%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 583      | 952    | 54.03%  |
| 0.51-1.0   | 294      | 440    | 27.25%  |
| 1.01-2.0   | 111      | 159    | 10.29%  |
| 3.01-4.0   | 36       | 90     | 3.34%   |
| 4.01-10.0  | 32       | 49     | 2.97%   |
| 2.01-3.0   | 20       | 30     | 1.85%   |
| 10.01-20.0 | 3        | 11     | 0.28%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 252      | 29.58%  |
| 251-500        | 193      | 22.65%  |
| 501-1000       | 138      | 16.2%   |
| 1001-2000      | 71       | 8.33%   |
| More than 3000 | 67       | 7.86%   |
| 51-100         | 53       | 6.22%   |
| 2001-3000      | 28       | 3.29%   |
| 21-50          | 20       | 2.35%   |
| 1-20           | 18       | 2.11%   |
| Unknown        | 12       | 1.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 318      | 35.65%  |
| 21-50          | 223      | 25%     |
| 51-100         | 110      | 12.33%  |
| 101-250        | 68       | 7.62%   |
| 251-500        | 49       | 5.49%   |
| 501-1000       | 39       | 4.37%   |
| More than 3000 | 38       | 4.26%   |
| 1001-2000      | 27       | 3.03%   |
| Unknown        | 12       | 1.35%   |
| 2001-3000      | 8        | 0.9%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Desktops | Drives | Percent |
|--------------------------------------|----------|--------|---------|
| WDC WD3200AAKS-22B3A0 320GB          | 1        | 1      | 4.17%   |
| WDC WD30EFRX-68EUZN0 3TB             | 1        | 1      | 4.17%   |
| WDC WD10EZEX-21M2NA0 1TB             | 1        | 2      | 4.17%   |
| WDC WD10EURX-63FH1Y0 1TB             | 1        | 1      | 4.17%   |
| Toshiba MK8046GSX 80GB               | 1        | 1      | 4.17%   |
| Toshiba MK3265GSX 320GB              | 1        | 1      | 4.17%   |
| Toshiba MG03ACA200 2TB               | 1        | 1      | 4.17%   |
| Silicon Motion Inland NVMe SSD 256GB | 1        | 1      | 4.17%   |
| Seagate ST9500420AS 500GB            | 1        | 1      | 4.17%   |
| Seagate ST500DM002-1BD142 500GB      | 1        | 1      | 4.17%   |
| Seagate ST4000DM004-2CV104 4TB       | 1        | 1      | 4.17%   |
| Seagate ST3500514NS 500GB            | 1        | 1      | 4.17%   |
| Seagate ST3500413AS 500GB            | 1        | 1      | 4.17%   |
| Seagate ST3320620AS 320GB            | 1        | 1      | 4.17%   |
| Seagate ST3250318AS 250GB            | 1        | 1      | 4.17%   |
| Seagate ST320LT012-1DG14C 320GB      | 1        | 1      | 4.17%   |
| Seagate ST2000LM003 HN-M201RAD 2TB   | 1        | 1      | 4.17%   |
| Seagate ST2000DM008-2FR102 2TB       | 1        | 1      | 4.17%   |
| Seagate ST2000DM001-9YN164 2TB       | 1        | 1      | 4.17%   |
| Seagate ST2000DL003-9VT166 2TB       | 1        | 1      | 4.17%   |
| OCZ VERTEX3 120GB SSD                | 1        | 1      | 4.17%   |
| Kingston SNS4151S316GD 16GB SSD      | 1        | 1      | 4.17%   |
| Intel SSDSC2CW060A3 64GB             | 1        | 1      | 4.17%   |
| A-DATA Technology SX8200PNP 256GB    | 1        | 1      | 4.17%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Desktops | Drives | Percent |
|-------------------|----------|--------|---------|
| Seagate           | 11       | 12     | 47.83%  |
| WDC               | 4        | 5      | 17.39%  |
| Toshiba           | 3        | 3      | 13.04%  |
| Silicon Motion    | 1        | 1      | 4.35%   |
| OCZ               | 1        | 1      | 4.35%   |
| Kingston          | 1        | 1      | 4.35%   |
| Intel             | 1        | 1      | 4.35%   |
| A-DATA Technology | 1        | 1      | 4.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 11       | 12     | 61.11%  |
| WDC     | 4        | 5      | 22.22%  |
| Toshiba | 3        | 3      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 17       | 20     | 77.27%  |
| SSD  | 3        | 3      | 13.64%  |
| NVMe | 2        | 2      | 9.09%   |

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
| Detected | 759      | 1826   | 89.29%  |
| Works    | 69       | 204    | 8.12%   |
| Malfunc  | 22       | 25     | 2.59%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 547      | 49.77%  |
| AMD                          | 259      | 23.57%  |
| Samsung Electronics          | 60       | 5.46%   |
| ASMedia Technology           | 33       | 3%      |
| SanDisk                      | 27       | 2.46%   |
| JMicron Technology           | 23       | 2.09%   |
| Phison Electronics           | 22       | 2%      |
| Kingston Technology Company  | 20       | 1.82%   |
| Silicon Motion               | 19       | 1.73%   |
| Nvidia                       | 17       | 1.55%   |
| Marvell Technology Group     | 14       | 1.27%   |
| ADATA Technology             | 8        | 0.73%   |
| Silicon Image                | 7        | 0.64%   |
| SK hynix                     | 6        | 0.55%   |
| Micron/Crucial Technology    | 6        | 0.55%   |
| VIA Technologies             | 5        | 0.45%   |
| Realtek Semiconductor        | 5        | 0.45%   |
| Toshiba America Info Systems | 4        | 0.36%   |
| Seagate Technology           | 4        | 0.36%   |
| Micron Technology            | 2        | 0.18%   |
| MAXIO Technology (Hangzhou)  | 2        | 0.18%   |
| KIOXIA                       | 2        | 0.18%   |
| INNOGRIT                     | 2        | 0.18%   |
| Broadcom / LSI               | 2        | 0.18%   |
| OCZ Technology Group         | 1        | 0.09%   |
| Lite-On Technology           | 1        | 0.09%   |
| Apple                        | 1        | 0.09%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 142      | 10.13%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 82       | 5.85%   |
| AMD 400 Series Chipset SATA Controller                                                  | 55       | 3.92%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 53       | 3.78%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 50       | 3.57%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 48       | 3.42%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 47       | 3.35%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 41       | 2.92%   |
| Intel SATA Controller [RAID mode]                                                       | 39       | 2.78%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 37       | 2.64%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 34       | 2.43%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 32       | 2.28%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 30       | 2.14%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 29       | 2.07%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 26       | 1.85%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 24       | 1.71%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 22       | 1.57%   |
| AMD 500 Series Chipset SATA Controller                                                  | 22       | 1.57%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 21       | 1.5%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 19       | 1.36%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 16       | 1.14%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 16       | 1.14%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 15       | 1.07%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 15       | 1.07%   |
| AMD FCH SATA Controller D                                                               | 13       | 0.93%   |
| Phison E12 NVMe Controller                                                              | 12       | 0.86%   |
| Kingston Company A2000 NVMe SSD                                                         | 11       | 0.78%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 11       | 0.78%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 10       | 0.71%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 10       | 0.71%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 9        | 0.64%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 9        | 0.64%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 9        | 0.64%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 9        | 0.64%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 9        | 0.64%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 9        | 0.64%   |
| AMD 300 Series Chipset SATA Controller                                                  | 9        | 0.64%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 8        | 0.57%   |
| Nvidia MCP61 SATA Controller                                                            | 8        | 0.57%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 8        | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 654      | 58.08%  |
| IDE  | 222      | 19.72%  |
| NVMe | 179      | 15.9%   |
| RAID | 65       | 5.77%   |
| SAS  | 3        | 0.27%   |
| SCSI | 3        | 0.27%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 552      | 66.91%  |
| AMD    | 273      | 33.09%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-2400 CPU @ 3.10GHz            | 19       | 2.3%    |
| AMD Ryzen 5 3600 6-Core Processor           | 17       | 2.06%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 16       | 1.93%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 12       | 1.45%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 11       | 1.33%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 10       | 1.21%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 10       | 1.21%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 10       | 1.21%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 9        | 1.09%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 9        | 1.09%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 8        | 0.97%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 8        | 0.97%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 8        | 0.97%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 7        | 0.85%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 7        | 0.85%   |
| Intel Core i5-4690K CPU @ 3.50GHz           | 7        | 0.85%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 7        | 0.85%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 7        | 0.85%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 7        | 0.85%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 7        | 0.85%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 7        | 0.85%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 6        | 0.73%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 6        | 0.73%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 6        | 0.73%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 6        | 0.73%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 6        | 0.73%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 6        | 0.73%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 6        | 0.73%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 6        | 0.73%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 6        | 0.73%   |
| AMD FX-8350 Eight-Core Processor            | 6        | 0.73%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 5        | 0.6%    |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 5        | 0.6%    |
| Intel Pentium Dual CPU E2140 @ 1.60GHz      | 5        | 0.6%    |
| Intel Core i7 CPU 920 @ 2.67GHz             | 5        | 0.6%    |
| Intel Core i5-7400 CPU @ 3.00GHz            | 5        | 0.6%    |
| Intel Core i5-10400 CPU @ 2.90GHz           | 5        | 0.6%    |
| Intel Core i3-3240 CPU @ 3.40GHz            | 5        | 0.6%    |
| Intel Core i3-2100 CPU @ 3.10GHz            | 5        | 0.6%    |
| Intel Core i3 CPU 540 @ 3.07GHz             | 5        | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 168      | 20.31%  |
| Intel Core i7           | 89       | 10.76%  |
| Intel Core i3           | 78       | 9.43%   |
| AMD Ryzen 5             | 64       | 7.74%   |
| Intel Xeon              | 43       | 5.2%    |
| AMD FX                  | 37       | 4.47%   |
| AMD Ryzen 7             | 36       | 4.35%   |
| Intel Core 2 Duo        | 31       | 3.75%   |
| Intel Core 2 Quad       | 25       | 3.02%   |
| Other                   | 21       | 2.54%   |
| Intel Celeron           | 21       | 2.54%   |
| AMD Ryzen 9             | 21       | 2.54%   |
| Intel Pentium Dual-Core | 19       | 2.3%    |
| Intel Pentium           | 19       | 2.3%    |
| AMD Ryzen 3             | 15       | 1.81%   |
| Intel Pentium Dual      | 13       | 1.57%   |
| AMD Phenom II X4        | 10       | 1.21%   |
| AMD Athlon II X2        | 9        | 1.09%   |
| AMD A8                  | 9        | 1.09%   |
| AMD A6                  | 9        | 1.09%   |
| AMD A10                 | 9        | 1.09%   |
| Intel Core i9           | 8        | 0.97%   |
| AMD Phenom II X6        | 7        | 0.85%   |
| AMD Athlon II X4        | 7        | 0.85%   |
| AMD Athlon 64 X2        | 7        | 0.85%   |
| Intel Core 2            | 5        | 0.6%    |
| AMD Athlon              | 5        | 0.6%    |
| Intel Pentium 4         | 4        | 0.48%   |
| Intel Pentium Gold      | 3        | 0.36%   |
| Intel Atom              | 3        | 0.36%   |
| AMD PRO A10             | 3        | 0.36%   |
| AMD E1                  | 3        | 0.36%   |
| AMD Athlon II X3        | 3        | 0.36%   |
| Intel Pentium D         | 2        | 0.24%   |
| AMD Ryzen 5 PRO         | 2        | 0.24%   |
| AMD Phenom              | 2        | 0.24%   |
| AMD GX                  | 2        | 0.24%   |
| AMD Athlon X4           | 2        | 0.24%   |
| AMD Athlon 64           | 2        | 0.24%   |
| AMD A4                  | 2        | 0.24%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 353      | 42.68%  |
| 2      | 237      | 28.66%  |
| 6      | 109      | 13.18%  |
| 8      | 65       | 7.86%   |
| 12     | 17       | 2.06%   |
| 3      | 15       | 1.81%   |
| 1      | 15       | 1.81%   |
| 16     | 10       | 1.21%   |
| 10     | 6        | 0.73%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 819      | 99.27%  |
| 2      | 6        | 0.73%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 421      | 50.97%  |
| 1      | 405      | 49.03%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 825      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 94       | 11.27%  |
| 0x306a9    | 73       | 8.75%   |
| 0x206a7    | 60       | 7.19%   |
| Unknown    | 60       | 7.19%   |
| 0x1067a    | 57       | 6.83%   |
| 0x08701021 | 35       | 4.2%    |
| 0x506e3    | 31       | 3.72%   |
| 0x06000852 | 27       | 3.24%   |
| 0x906ea    | 18       | 2.16%   |
| 0x0a201016 | 18       | 2.16%   |
| 0x0800820d | 17       | 2.04%   |
| 0x906e9    | 16       | 1.92%   |
| 0xa0653    | 15       | 1.8%    |
| 0x6fd      | 15       | 1.8%    |
| 0x6fb      | 14       | 1.68%   |
| 0x906ed    | 12       | 1.44%   |
| 0x06001119 | 12       | 1.44%   |
| 0x010000c8 | 11       | 1.32%   |
| 0xa0671    | 9        | 1.08%   |
| 0xa0655    | 9        | 1.08%   |
| 0x08108109 | 9        | 1.08%   |
| 0x0600063e | 9        | 1.08%   |
| 0x010000dc | 9        | 1.08%   |
| 0x906eb    | 8        | 0.96%   |
| 0x08701013 | 8        | 0.96%   |
| 0x010000db | 8        | 0.96%   |
| 0x206d7    | 7        | 0.84%   |
| 0x08101016 | 7        | 0.84%   |
| 0x06003106 | 7        | 0.84%   |
| 0x90672    | 6        | 0.72%   |
| 0x20655    | 6        | 0.72%   |
| 0x106e5    | 6        | 0.72%   |
| 0x106a5    | 6        | 0.72%   |
| 0x10676    | 6        | 0.72%   |
| 0x0700010f | 6        | 0.72%   |
| 0x306e4    | 5        | 0.6%    |
| 0x20652    | 5        | 0.6%    |
| 0x0a201009 | 5        | 0.6%    |
| 0x08001137 | 5        | 0.6%    |
| 0x6f6      | 4        | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 107      | 12.95%  |
| IvyBridge        | 78       | 9.44%   |
| SandyBridge      | 70       | 8.47%   |
| Penryn           | 67       | 8.11%   |
| KabyLake         | 61       | 7.38%   |
| Zen 2            | 52       | 6.3%    |
| Piledriver       | 42       | 5.08%   |
| Zen 3            | 38       | 4.6%    |
| K10              | 38       | 4.6%    |
| Core             | 36       | 4.36%   |
| Skylake          | 33       | 4%      |
| Zen+             | 28       | 3.39%   |
| Zen              | 26       | 3.15%   |
| CometLake        | 25       | 3.03%   |
| Nehalem          | 17       | 2.06%   |
| Westmere         | 14       | 1.69%   |
| K8 Hammer        | 11       | 1.33%   |
| Silvermont       | 9        | 1.09%   |
| Icelake          | 9        | 1.09%   |
| Bulldozer        | 9        | 1.09%   |
| Excavator        | 8        | 0.97%   |
| Steamroller      | 7        | 0.85%   |
| NetBurst         | 7        | 0.85%   |
| Jaguar           | 7        | 0.85%   |
| Alderlake Hybrid | 7        | 0.85%   |
| Puma             | 5        | 0.61%   |
| K10 Llano        | 3        | 0.36%   |
| Broadwell        | 3        | 0.36%   |
| Unknown          | 3        | 0.36%   |
| Goldmont plus    | 2        | 0.24%   |
| Bonnell          | 2        | 0.24%   |
| TigerLake        | 1        | 0.12%   |
| Goldmont         | 1        | 0.12%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Nvidia           | 342      | 38.86%  |
| Intel            | 281      | 31.93%  |
| AMD              | 255      | 28.98%  |
| VIA Technologies | 2        | 0.23%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 47       | 5.28%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 39       | 4.38%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 29       | 3.26%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 26       | 2.92%   |
| Nvidia GK208B [GeForce GT 710]                                              | 24       | 2.7%    |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 22       | 2.47%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 18       | 2.02%   |
| Nvidia GK208B [GeForce GT 730]                                              | 16       | 1.8%    |
| Intel HD Graphics 530                                                       | 16       | 1.8%    |
| Nvidia GF119 [GeForce GT 610]                                               | 15       | 1.69%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 15       | 1.69%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 14       | 1.57%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 13       | 1.46%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 12       | 1.35%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 12       | 1.35%   |
| Intel HD Graphics 630                                                       | 11       | 1.24%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 11       | 1.24%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 11       | 1.24%   |
| AMD RS780L [Radeon 3000]                                                    | 10       | 1.12%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 8        | 0.9%    |
| Nvidia GM204 [GeForce GTX 970]                                              | 8        | 0.9%    |
| Intel Core Processor Integrated Graphics Controller                         | 8        | 0.9%    |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 8        | 0.9%    |
| Nvidia TU117 [GeForce GTX 1650]                                             | 7        | 0.79%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 7        | 0.79%   |
| Nvidia GT218 [GeForce 210]                                                  | 7        | 0.79%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 7        | 0.79%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 7        | 0.79%   |
| Nvidia GF108 [GeForce GT 630]                                               | 7        | 0.79%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 7        | 0.79%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 7        | 0.79%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 7        | 0.79%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 6        | 0.67%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 6        | 0.67%   |
| Nvidia GF108 [GeForce GT 730]                                               | 6        | 0.67%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 6        | 0.67%   |
| Intel AlderLake-S GT1                                                       | 6        | 0.67%   |
| AMD RS880 [Radeon HD 4200]                                                  | 6        | 0.67%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 6        | 0.67%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 6        | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 323      | 38.87%  |
| 1 x Intel      | 242      | 29.12%  |
| 1 x AMD        | 238      | 28.64%  |
| Intel + Nvidia | 8        | 0.96%   |
| Intel + AMD    | 6        | 0.72%   |
| 2 x AMD        | 5        | 0.6%    |
| AMD + Nvidia   | 5        | 0.6%    |
| 2 x Nvidia     | 2        | 0.24%   |
| 1 x VIA        | 2        | 0.24%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 555      | 66.79%  |
| Proprietary | 226      | 27.2%   |
| Unknown     | 50       | 6.02%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 348      | 41.53%  |
| 1.01-2.0   | 114      | 13.6%   |
| 0.51-1.0   | 106      | 12.65%  |
| 0.01-0.5   | 83       | 9.9%    |
| 3.01-4.0   | 73       | 8.71%   |
| 7.01-8.0   | 56       | 6.68%   |
| 8.01-16.0  | 23       | 2.74%   |
| 5.01-6.0   | 22       | 2.63%   |
| 2.01-3.0   | 9        | 1.07%   |
| 16.01-24.0 | 4        | 0.48%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 124      | 15.1%   |
| Dell                 | 81       | 9.87%   |
| Goldstar             | 79       | 9.62%   |
| Hewlett-Packard      | 61       | 7.43%   |
| Acer                 | 50       | 6.09%   |
| AOC                  | 49       | 5.97%   |
| Philips              | 47       | 5.72%   |
| BenQ                 | 31       | 3.78%   |
| Ancor Communications | 31       | 3.78%   |
| LG Electronics       | 22       | 2.68%   |
| ViewSonic            | 17       | 2.07%   |
| Unknown              | 16       | 1.95%   |
| Unknown              | 15       | 1.83%   |
| Iiyama               | 12       | 1.46%   |
| Sony                 | 11       | 1.34%   |
| Sceptre Tech         | 10       | 1.22%   |
| Lenovo               | 10       | 1.22%   |
| HPN                  | 10       | 1.22%   |
| NEC Computers        | 9        | 1.1%    |
| ASUSTek Computer     | 8        | 0.97%   |
| Fujitsu Siemens      | 7        | 0.85%   |
| Eizo                 | 6        | 0.73%   |
| AUS                  | 6        | 0.73%   |
| Vizio                | 5        | 0.61%   |
| Microstep            | 5        | 0.61%   |
| Panasonic            | 4        | 0.49%   |
| Medion               | 4        | 0.49%   |
| FUS                  | 4        | 0.49%   |
| Vestel               | 3        | 0.37%   |
| Sharp                | 3        | 0.37%   |
| PKB                  | 3        | 0.37%   |
| MSI                  | 3        | 0.37%   |
| Lenovo Group Limited | 3        | 0.37%   |
| HannStar             | 3        | 0.37%   |
| ___                  | 2        | 0.24%   |
| Xiaomi               | 2        | 0.24%   |
| Toshiba              | 2        | 0.24%   |
| STD                  | 2        | 0.24%   |
| OOO                  | 2        | 0.24%   |
| ONN                  | 2        | 0.24%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Unknown                                                                 | 15       | 1.74%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 6        | 0.7%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch       | 4        | 0.46%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch             | 4        | 0.46%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                        | 4        | 0.46%   |
| Vestel LCD Monitor 48UHD_LCD_TV 3840x2160                               | 3        | 0.35%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                   | 3        | 0.35%   |
| Samsung Electronics U28D590 SAM0B81 3840x2160 608x345mm 27.5-inch       | 3        | 0.35%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 480x270mm 21.7-inch   | 3        | 0.35%   |
| Philips PHL 277E6 PHLC0E6 1920x1080 598x336mm 27.0-inch                 | 3        | 0.35%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                 | 3        | 0.35%   |
| Philips LCD Monitor FTV 1920x1080                                       | 3        | 0.35%   |
| LG Electronics LCD Monitor LG TV SSCR2 3840x2160                        | 3        | 0.35%   |
| Goldstar W1942 GSM4B6F 1440x900 408x255mm 18.9-inch                     | 3        | 0.35%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch               | 3        | 0.35%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch   | 3        | 0.35%   |
| Xiaomi Mi TV XMD00E2 3840x2160 800x450mm 36.1-inch                      | 2        | 0.23%   |
| Vizio VO42LFHDTV10A VIZ0043 1920x1080 930x520mm 41.9-inch               | 2        | 0.23%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                   | 2        | 0.23%   |
| Sceptre Tech H32 SPT0CB8 1920x1080 575x323mm 26.0-inch                  | 2        | 0.23%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch       | 2        | 0.23%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch    | 2        | 0.23%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch       | 2        | 0.23%   |
| Samsung Electronics S24B350 SAM08DA 1920x1080 531x299mm 24.0-inch       | 2        | 0.23%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                    | 2        | 0.23%   |
| Samsung Electronics LCD Monitor SyncMaster                              | 2        | 0.23%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 950x540mm 43.0-inch   | 2        | 0.23%   |
| Samsung Electronics LCD Monitor SAM0F9F 3840x2160 1872x1053mm 84.6-inch | 2        | 0.23%   |
| Samsung Electronics LCD Monitor SAM0D4F 1920x1080 1210x680mm 54.6-inch  | 2        | 0.23%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch    | 2        | 0.23%   |
| Samsung Electronics LCD Monitor SAM07BC 1360x768 700x390mm 31.5-inch    | 2        | 0.23%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                 | 2        | 0.23%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                 | 2        | 0.23%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                      | 2        | 0.23%   |
| OEM 19W_LCD_TV OEM3700 1920x540                                         | 2        | 0.23%   |
| NEC Computers LCD1715 NEC6618 1280x1024 338x270mm 17.0-inch             | 2        | 0.23%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                         | 2        | 0.23%   |
| Iiyama PLE2483H IVM6113 1920x1080 531x299mm 24.0-inch                   | 2        | 0.23%   |
| Hewlett-Packard W2072a HWP3000 1600x900 443x249mm 20.0-inch             | 2        | 0.23%   |
| Hewlett-Packard P202 HWP322A 1600x900 443x249mm 20.0-inch               | 2        | 0.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 344      | 42.68%  |
| 3840x2160 (4K)     | 74       | 9.18%   |
| 1680x1050 (WSXGA+) | 47       | 5.83%   |
| 1280x1024 (SXGA)   | 46       | 5.71%   |
| 1600x900 (HD+)     | 40       | 4.96%   |
| Unknown            | 40       | 4.96%   |
| 1366x768 (WXGA)    | 33       | 4.09%   |
| 2560x1440 (QHD)    | 31       | 3.85%   |
| 1440x900 (WXGA+)   | 26       | 3.23%   |
| 1360x768           | 21       | 2.61%   |
| 1920x1200 (WUXGA)  | 19       | 2.36%   |
| 3840x1080          | 16       | 1.99%   |
| 3440x1440          | 13       | 1.61%   |
| 2560x1080          | 8        | 0.99%   |
| 1920x540           | 6        | 0.74%   |
| 1024x768 (XGA)     | 6        | 0.74%   |
| 4480x1440          | 3        | 0.37%   |
| 3840x1600          | 3        | 0.37%   |
| 1600x1200          | 3        | 0.37%   |
| 5760x2160          | 2        | 0.25%   |
| 3360x1080          | 2        | 0.25%   |
| 3200x1200          | 2        | 0.25%   |
| 3120x1050          | 2        | 0.25%   |
| 2944x1080          | 2        | 0.25%   |
| 2560x1600          | 2        | 0.25%   |
| 1280x720 (HD)      | 2        | 0.25%   |
| 6400x1440          | 1        | 0.12%   |
| 5760x1080          | 1        | 0.12%   |
| 5440x1080          | 1        | 0.12%   |
| 5040x1050          | 1        | 0.12%   |
| 4160x1440          | 1        | 0.12%   |
| 3780x2160          | 1        | 0.12%   |
| 3600x1080          | 1        | 0.12%   |
| 3360x1050          | 1        | 0.12%   |
| 3040x1050          | 1        | 0.12%   |
| 2720x1024          | 1        | 0.12%   |
| 2464x900           | 1        | 0.12%   |
| 1850x1030          | 1        | 0.12%   |
| 1834x1031          | 1        | 0.12%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 171      | 21.35%  |
| 27      | 81       | 10.11%  |
| 24      | 81       | 10.11%  |
| 21      | 72       | 8.99%   |
| 23      | 70       | 8.74%   |
| 19      | 52       | 6.49%   |
| 31      | 39       | 4.87%   |
| 20      | 38       | 4.74%   |
| 22      | 35       | 4.37%   |
| 18      | 33       | 4.12%   |
| 17      | 22       | 2.75%   |
| 34      | 14       | 1.75%   |
| 84      | 11       | 1.37%   |
| 54      | 9        | 1.12%   |
| 72      | 8        | 1%      |
| 40      | 8        | 1%      |
| 32      | 8        | 1%      |
| 15      | 7        | 0.87%   |
| 26      | 6        | 0.75%   |
| 25      | 6        | 0.75%   |
| 36      | 4        | 0.5%    |
| 52      | 3        | 0.37%   |
| 33      | 3        | 0.37%   |
| 65      | 2        | 0.25%   |
| 48      | 2        | 0.25%   |
| 41      | 2        | 0.25%   |
| 37      | 2        | 0.25%   |
| 35      | 2        | 0.25%   |
| 29      | 2        | 0.25%   |
| 28      | 2        | 0.25%   |
| 86      | 1        | 0.12%   |
| 75      | 1        | 0.12%   |
| 74      | 1        | 0.12%   |
| 57      | 1        | 0.12%   |
| 43      | 1        | 0.12%   |
| 42      | 1        | 0.12%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 214      | 27.68%  |
| 401-500     | 200      | 25.87%  |
| Unknown     | 171      | 22.12%  |
| 601-700     | 52       | 6.73%   |
| 701-800     | 29       | 3.75%   |
| 301-350     | 27       | 3.49%   |
| 351-400     | 25       | 3.23%   |
| 1501-2000   | 22       | 2.85%   |
| 1001-1500   | 17       | 2.2%    |
| 801-900     | 12       | 1.55%   |
| 901-1000    | 4        | 0.52%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 422      | 56.64%  |
| Unknown | 161      | 21.61%  |
| 16/10   | 87       | 11.68%  |
| 5/4     | 41       | 5.5%    |
| 21/9    | 19       | 2.55%   |
| 4/3     | 9        | 1.21%   |
| 32/9    | 3        | 0.4%    |
| 6/5     | 2        | 0.27%   |
| 3/2     | 1        | 0.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 208      | 26.3%   |
| Unknown        | 171      | 21.62%  |
| 151-200        | 117      | 14.79%  |
| 301-350        | 82       | 10.37%  |
| 351-500        | 70       | 8.85%   |
| 141-150        | 46       | 5.82%   |
| More than 1000 | 37       | 4.68%   |
| 251-300        | 33       | 4.17%   |
| 501-1000       | 18       | 2.28%   |
| 101-110        | 7        | 0.88%   |
| 131-140        | 1        | 0.13%   |
| 121-130        | 1        | 0.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 409      | 54.32%  |
| Unknown | 171      | 22.71%  |
| 101-120 | 103      | 13.68%  |
| 1-50    | 35       | 4.65%   |
| 121-160 | 24       | 3.19%   |
| 161-240 | 11       | 1.46%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 666      | 79.67%  |
| 2     | 108      | 12.92%  |
| 0     | 50       | 5.98%   |
| 3     | 11       | 1.32%   |
| 4     | 1        | 0.12%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 525      | 42.82%  |
| Intel                             | 325      | 26.51%  |
| Qualcomm Atheros                  | 76       | 6.2%    |
| Broadcom                          | 46       | 3.75%   |
| Ralink Technology                 | 37       | 3.02%   |
| TP-Link                           | 34       | 2.77%   |
| Ralink                            | 20       | 1.63%   |
| Nvidia                            | 15       | 1.22%   |
| MediaTek                          | 13       | 1.06%   |
| NetGear                           | 11       | 0.9%    |
| Samsung Electronics               | 9        | 0.73%   |
| Broadcom Limited                  | 9        | 0.73%   |
| Qualcomm Atheros Communications   | 8        | 0.65%   |
| Microsoft                         | 8        | 0.65%   |
| Marvell Technology Group          | 7        | 0.57%   |
| D-Link                            | 7        | 0.57%   |
| Xiaomi                            | 6        | 0.49%   |
| D-Link System                     | 6        | 0.49%   |
| Huawei Technologies               | 5        | 0.41%   |
| Edimax Technology                 | 5        | 0.41%   |
| ASUSTek Computer                  | 5        | 0.41%   |
| Motorola PCS                      | 4        | 0.33%   |
| ASIX Electronics                  | 4        | 0.33%   |
| Aquantia                          | 4        | 0.33%   |
| Linksys                           | 3        | 0.24%   |
| DisplayLink                       | 3        | 0.24%   |
| Gemtek                            | 2        | 0.16%   |
| Belkin Components                 | 2        | 0.16%   |
| AVM                               | 2        | 0.16%   |
| ZyDAS                             | 1        | 0.08%   |
| VIA Technologies                  | 1        | 0.08%   |
| U-Blox                            | 1        | 0.08%   |
| TRENDnet                          | 1        | 0.08%   |
| T & A Mobile Phones               | 1        | 0.08%   |
| Sundance Technology Inc / IC Plus | 1        | 0.08%   |
| Sigma Sport                       | 1        | 0.08%   |
| Research In Motion                | 1        | 0.08%   |
| QinHeng Electronics               | 1        | 0.08%   |
| Panasonic (Matsushita)            | 1        | 0.08%   |
| Padix (Rockfire)                  | 1        | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 402      | 28.86%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 56       | 4.02%   |
| Intel I211 Gigabit Network Connection                             | 40       | 2.87%   |
| Realtek RTL8125 2.5GbE Controller                                 | 38       | 2.73%   |
| Intel Wi-Fi 6 AX200                                               | 38       | 2.73%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 30       | 2.15%   |
| Intel Ethernet Connection I217-LM                                 | 26       | 1.87%   |
| Intel Ethernet Connection (2) I219-V                              | 25       | 1.79%   |
| Realtek 802.11ac NIC                                              | 21       | 1.51%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 20       | 1.44%   |
| Intel Ethernet Controller I225-V                                  | 17       | 1.22%   |
| Ralink MT7601U Wireless Adapter                                   | 15       | 1.08%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 14       | 1.01%   |
| Intel Ethernet Connection I217-V                                  | 13       | 0.93%   |
| Intel Wireless 7265                                               | 12       | 0.86%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 12       | 0.86%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 11       | 0.79%   |
| Intel Ethernet Connection (7) I219-V                              | 11       | 0.79%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 10       | 0.72%   |
| TP-Link 802.11ac WLAN Adapter                                     | 9        | 0.65%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 9        | 0.65%   |
| Ralink RT5370 Wireless Adapter                                    | 9        | 0.65%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 9        | 0.65%   |
| Intel Wireless-AC 9260                                            | 9        | 0.65%   |
| Intel Ethernet Connection (2) I218-V                              | 9        | 0.65%   |
| Intel 82579V Gigabit Network Connection                           | 9        | 0.65%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 9        | 0.65%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 9        | 0.65%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 8        | 0.57%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 8        | 0.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 8        | 0.57%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 8        | 0.57%   |
| Nvidia MCP61 Ethernet                                             | 8        | 0.57%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 7        | 0.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7        | 0.5%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 7        | 0.5%    |
| Qualcomm Atheros AR9271 802.11n                                   | 7        | 0.5%    |
| Intel 82566DM-2 Gigabit Network Connection                        | 7        | 0.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6        | 0.43%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 6        | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 123      | 26.34%  |
| Intel                                 | 117      | 25.05%  |
| Ralink Technology                     | 37       | 7.92%   |
| Qualcomm Atheros                      | 37       | 7.92%   |
| TP-Link                               | 32       | 6.85%   |
| Broadcom                              | 22       | 4.71%   |
| Ralink                                | 20       | 4.28%   |
| NetGear                               | 11       | 2.36%   |
| MediaTek                              | 9        | 1.93%   |
| Qualcomm Atheros Communications       | 8        | 1.71%   |
| Microsoft                             | 8        | 1.71%   |
| D-Link                                | 7        | 1.5%    |
| Edimax Technology                     | 5        | 1.07%   |
| Broadcom Limited                      | 5        | 1.07%   |
| ASUSTek Computer                      | 5        | 1.07%   |
| D-Link System                         | 4        | 0.86%   |
| Linksys                               | 3        | 0.64%   |
| Gemtek                                | 2        | 0.43%   |
| Belkin Components                     | 2        | 0.43%   |
| AVM                                   | 2        | 0.43%   |
| ZyDAS                                 | 1        | 0.21%   |
| Xiaomi                                | 1        | 0.21%   |
| TRENDnet                              | 1        | 0.21%   |
| Panasonic (Matsushita)                | 1        | 0.21%   |
| Ovislink                              | 1        | 0.21%   |
| Marvell Technology Group              | 1        | 0.21%   |
| ADMtek                                | 1        | 0.21%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.21%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 38       | 8.03%   |
| Realtek 802.11ac NIC                                                 | 21       | 4.44%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 20       | 4.23%   |
| Ralink MT7601U Wireless Adapter                                      | 15       | 3.17%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 14       | 2.96%   |
| Intel Wireless 7265                                                  | 12       | 2.54%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 12       | 2.54%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                      | 11       | 2.33%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 10       | 2.11%   |
| TP-Link 802.11ac WLAN Adapter                                        | 9        | 1.9%    |
| Ralink RT5370 Wireless Adapter                                       | 9        | 1.9%    |
| Ralink RT2870/RT3070 Wireless Adapter                                | 9        | 1.9%    |
| Intel Wireless-AC 9260                                               | 9        | 1.9%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                   | 9        | 1.9%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 8        | 1.69%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 8        | 1.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 8        | 1.69%   |
| Qualcomm Atheros AR9271 802.11n                                      | 7        | 1.48%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 6        | 1.27%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 6        | 1.27%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 5        | 1.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 5        | 1.06%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 5        | 1.06%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 5        | 1.06%   |
| Realtek 802.11n                                                      | 5        | 1.06%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 5        | 1.06%   |
| NetGear A6210                                                        | 5        | 1.06%   |
| Intel Alder Lake-S PCH CNVi WiFi                                     | 5        | 1.06%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                               | 4        | 0.85%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                               | 4        | 0.85%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 4        | 0.85%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                     | 4        | 0.85%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]          | 4        | 0.85%   |
| Microsoft XBOX ACC                                                   | 4        | 0.85%   |
| MediaTek WiFi                                                        | 4        | 0.85%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                              | 4        | 0.85%   |
| Intel Wireless 8260                                                  | 4        | 0.85%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU] | 4        | 0.85%   |
| Broadcom BCM43142 802.11b/g/n                                        | 4        | 0.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 3        | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 484      | 54.88%  |
| Intel                             | 262      | 29.71%  |
| Qualcomm Atheros                  | 41       | 4.65%   |
| Broadcom                          | 24       | 2.72%   |
| Nvidia                            | 15       | 1.7%    |
| Samsung Electronics               | 9        | 1.02%   |
| Marvell Technology Group          | 6        | 0.68%   |
| Xiaomi                            | 5        | 0.57%   |
| MediaTek                          | 4        | 0.45%   |
| Huawei Technologies               | 4        | 0.45%   |
| Broadcom Limited                  | 4        | 0.45%   |
| ASIX Electronics                  | 4        | 0.45%   |
| Aquantia                          | 4        | 0.45%   |
| DisplayLink                       | 3        | 0.34%   |
| TP-Link                           | 2        | 0.23%   |
| Motorola PCS                      | 2        | 0.23%   |
| D-Link System                     | 2        | 0.23%   |
| VIA Technologies                  | 1        | 0.11%   |
| Sundance Technology Inc / IC Plus | 1        | 0.11%   |
| Research In Motion                | 1        | 0.11%   |
| OPPO Electronics                  | 1        | 0.11%   |
| JMicron Technology                | 1        | 0.11%   |
| HMD Global                        | 1        | 0.11%   |
| Google                            | 1        | 0.11%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 402      | 44.42%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 56       | 6.19%   |
| Intel I211 Gigabit Network Connection                             | 40       | 4.42%   |
| Realtek RTL8125 2.5GbE Controller                                 | 38       | 4.2%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 30       | 3.31%   |
| Intel Ethernet Connection I217-LM                                 | 26       | 2.87%   |
| Intel Ethernet Connection (2) I219-V                              | 25       | 2.76%   |
| Intel Ethernet Controller I225-V                                  | 17       | 1.88%   |
| Intel Ethernet Connection I217-V                                  | 13       | 1.44%   |
| Intel Ethernet Connection (7) I219-V                              | 11       | 1.22%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 9        | 0.99%   |
| Intel Ethernet Connection (2) I218-V                              | 9        | 0.99%   |
| Intel 82579V Gigabit Network Connection                           | 9        | 0.99%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 9        | 0.99%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 8        | 0.88%   |
| Nvidia MCP61 Ethernet                                             | 8        | 0.88%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 7        | 0.77%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7        | 0.77%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 7        | 0.77%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 7        | 0.77%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 6        | 0.66%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 5        | 0.55%   |
| Intel 82574L Gigabit Network Connection                           | 5        | 0.55%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 5        | 0.55%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 5        | 0.55%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 4        | 0.44%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 4        | 0.44%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 4        | 0.44%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 4        | 0.44%   |
| Intel Ethernet Connection (7) I219-LM                             | 4        | 0.44%   |
| Intel Ethernet Connection (2) I219-LM                             | 4        | 0.44%   |
| Intel Ethernet Connection (14) I219-V                             | 4        | 0.44%   |
| Intel Ethernet Connection (12) I219-V                             | 4        | 0.44%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 4        | 0.44%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3        | 0.33%   |
| Nvidia MCP51 Ethernet Controller                                  | 3        | 0.33%   |
| MediaTek N152DL                                                   | 3        | 0.33%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 3        | 0.33%   |
| Intel 82578DC Gigabit Network Connection                          | 3        | 0.33%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 3        | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 815      | 65.46%  |
| WiFi     | 416      | 33.41%  |
| Modem    | 10       | 0.8%    |
| Unknown  | 4        | 0.32%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 612      | 71.16%  |
| WiFi     | 246      | 28.6%   |
| Modem    | 1        | 0.12%   |
| Unknown  | 1        | 0.12%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 539      | 64.86%  |
| 2     | 249      | 29.96%  |
| 3     | 31       | 3.73%   |
| 0     | 8        | 0.96%   |
| 5     | 2        | 0.24%   |
| 7     | 1        | 0.12%   |
| 4     | 1        | 0.12%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 560      | 66.83%  |
| Yes  | 278      | 33.17%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 95       | 34.05%  |
| Cambridge Silicon Radio         | 64       | 22.94%  |
| Realtek Semiconductor           | 40       | 14.34%  |
| Broadcom                        | 18       | 6.45%   |
| ASUSTek Computer                | 17       | 6.09%   |
| Qualcomm Atheros Communications | 11       | 3.94%   |
| IMC Networks                    | 7        | 2.51%   |
| Apple                           | 6        | 2.15%   |
| MediaTek                        | 4        | 1.43%   |
| TP-Link                         | 3        | 1.08%   |
| Dynex                           | 3        | 1.08%   |
| Dell                            | 2        | 0.72%   |
| Sitecom Europe                  | 1        | 0.36%   |
| National Semiconductor          | 1        | 0.36%   |
| Micro Star International        | 1        | 0.36%   |
| Lite-On Technology              | 1        | 0.36%   |
| Integrated System Solution      | 1        | 0.36%   |
| Foxconn / Hon Hai               | 1        | 0.36%   |
| Edimax Technology               | 1        | 0.36%   |
| D-Link System                   | 1        | 0.36%   |
| Belkin Components               | 1        | 0.36%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)       | 64       | 22.94%  |
| Realtek Bluetooth Radio                                   | 33       | 11.83%  |
| Intel AX200 Bluetooth                                     | 28       | 10.04%  |
| Intel Bluetooth wireless interface                        | 22       | 7.89%   |
| Intel AX210 Bluetooth                                     | 12       | 4.3%    |
| Intel Wireless-AC 3168 Bluetooth                          | 11       | 3.94%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                  | 10       | 3.58%   |
| ASUS Broadcom BCM20702A0 Bluetooth                        | 8        | 2.87%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)            | 6        | 2.15%   |
| Broadcom BCM20702A0 Bluetooth 4.0                         | 6        | 2.15%   |
| IMC Networks Bluetooth Radio                              | 5        | 1.79%   |
| MediaTek Wireless_Device                                  | 4        | 1.43%   |
| Intel AX201 Bluetooth                                     | 4        | 1.43%   |
| TP-Link UB500 Adapter                                     | 3        | 1.08%   |
| Realtek  Bluetooth 4.2 Adapter                            | 3        | 1.08%   |
| Qualcomm Atheros AR9462 Bluetooth                         | 3        | 1.08%   |
| Qualcomm Atheros AR3011 Bluetooth                         | 3        | 1.08%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]  | 3        | 1.08%   |
| Broadcom HP Portable Bumble Bee                           | 3        | 1.08%   |
| Broadcom BCM43142A0 Bluetooth 4.0                         | 3        | 1.08%   |
| ASUS Qualcomm Bluetooth 4.1                               | 3        | 1.08%   |
| ASUS Bluetooth Radio                                      | 3        | 1.08%   |
| Apple Bluetooth USB Host Controller                       | 3        | 1.08%   |
| Realtek RTL8821A Bluetooth                                | 2        | 0.72%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                     | 2        | 0.72%   |
| Intel Centrino Bluetooth Wireless Transceiver             | 2        | 0.72%   |
| Dell BT Mini-Receiver                                     | 2        | 0.72%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter          | 2        | 0.72%   |
| ASUS ASUS USB-BT500                                       | 2        | 0.72%   |
| Sitecom Europe Sitecom bluetooth2.0 class 2 dongle CN-512 | 1        | 0.36%   |
| Realtek RTL8723B Bluetooth                                | 1        | 0.36%   |
| Realtek Bluetooth 5.1 Radio                               | 1        | 0.36%   |
| Qualcomm Atheros  Bluetooth Device                        | 1        | 0.36%   |
| Qualcomm Atheros Bluetooth USB Host Controller            | 1        | 0.36%   |
| Qualcomm Atheros Bluetooth                                | 1        | 0.36%   |
| National Bluetooth Dongle                                 | 1        | 0.36%   |
| Micro Star International Bluetooth Device                 | 1        | 0.36%   |
| Lite-On Bluetooth Device                                  | 1        | 0.36%   |
| Integrated System Solution Bluetooth Device               | 1        | 0.36%   |
| IMC Networks Bluetooth Module                             | 1        | 0.36%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 537      | 39%     |
| AMD                                  | 350      | 25.42%  |
| Nvidia                               | 321      | 23.31%  |
| C-Media Electronics                  | 34       | 2.47%   |
| Creative Labs                        | 15       | 1.09%   |
| Logitech                             | 10       | 0.73%   |
| Kingston Technology                  | 9        | 0.65%   |
| JMTek                                | 8        | 0.58%   |
| Texas Instruments                    | 7        | 0.51%   |
| Razer USA                            | 6        | 0.44%   |
| Plantronics                          | 6        | 0.44%   |
| ASUSTek Computer                     | 6        | 0.44%   |
| VIA Technologies                     | 5        | 0.36%   |
| GN Netcom                            | 5        | 0.36%   |
| Realtek Semiconductor                | 4        | 0.29%   |
| SteelSeries ApS                      | 3        | 0.22%   |
| Creative Technology                  | 3        | 0.22%   |
| RODE Microphones                     | 2        | 0.15%   |
| Micro Star International             | 2        | 0.15%   |
| Generalplus Technology               | 2        | 0.15%   |
| DSEA A/S                             | 2        | 0.15%   |
| Astro Gaming                         | 2        | 0.15%   |
| XMOS                                 | 1        | 0.07%   |
| WL80                                 | 1        | 0.07%   |
| Valve Software                       | 1        | 0.07%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.07%   |
| Tenx Technology                      | 1        | 0.07%   |
| Swissonic                            | 1        | 0.07%   |
| Silicon Labs                         | 1        | 0.07%   |
| Schiit Audio                         | 1        | 0.07%   |
| SAVITECH                             | 1        | 0.07%   |
| Samsung Electronics                  | 1        | 0.07%   |
| ROCCAT                               | 1        | 0.07%   |
| Qualcomm                             | 1        | 0.07%   |
| Philips (or NXP)                     | 1        | 0.07%   |
| Oculus                               | 1        | 0.07%   |
| Numark                               | 1        | 0.07%   |
| Microsoft                            | 1        | 0.07%   |
| Micronas                             | 1        | 0.07%   |
| Medeli Electronics                   | 1        | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 83       | 5.26%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 82       | 5.19%   |
| AMD Starship/Matisse HD Audio Controller                                          | 76       | 4.81%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 70       | 4.43%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 58       | 3.67%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 53       | 3.36%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 51       | 3.23%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 43       | 2.72%   |
| AMD FCH Azalia Controller                                                         | 35       | 2.22%   |
| AMD Family 17h/19h HD Audio Controller                                            | 35       | 2.22%   |
| Intel Cannon Lake PCH cAVS                                                        | 33       | 2.09%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 31       | 1.96%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 28       | 1.77%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 27       | 1.71%   |
| Intel 200 Series PCH HD Audio                                                     | 25       | 1.58%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 23       | 1.46%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 22       | 1.39%   |
| Nvidia TU116 High Definition Audio Controller                                     | 21       | 1.33%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 21       | 1.33%   |
| Nvidia GF119 HDMI Audio Controller                                                | 20       | 1.27%   |
| Nvidia GF108 High Definition Audio Controller                                     | 20       | 1.27%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 20       | 1.27%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 18       | 1.14%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 18       | 1.14%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 18       | 1.14%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 16       | 1.01%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 16       | 1.01%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 15       | 0.95%   |
| AMD Navi 10 HDMI Audio                                                            | 15       | 0.95%   |
| Nvidia TU106 High Definition Audio Controller                                     | 14       | 0.89%   |
| Intel Audio device                                                                | 14       | 0.89%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 14       | 0.89%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 14       | 0.89%   |
| Nvidia High Definition Audio Controller                                           | 13       | 0.82%   |
| Nvidia GK107 HDMI Audio Controller                                                | 13       | 0.82%   |
| AMD Kabini HDMI/DP Audio                                                          | 13       | 0.82%   |
| Nvidia GP106 High Definition Audio Controller                                     | 12       | 0.76%   |
| Nvidia GP104 High Definition Audio Controller                                     | 12       | 0.76%   |
| Nvidia GM204 High Definition Audio Controller                                     | 11       | 0.7%    |
| AMD Renoir Radeon High Definition Audio Controller                                | 11       | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 19       | 15.7%   |
| Kingston            | 18       | 14.88%  |
| Samsung Electronics | 14       | 11.57%  |
| G.Skill             | 14       | 11.57%  |
| Corsair             | 14       | 11.57%  |
| SK hynix            | 9        | 7.44%   |
| Crucial             | 8        | 6.61%   |
| Micron Technology   | 5        | 4.13%   |
| Team                | 4        | 3.31%   |
| Ramaxel Technology  | 2        | 1.65%   |
| Nanya Technology    | 2        | 1.65%   |
| Avant               | 2        | 1.65%   |
| Unknown             | 2        | 1.65%   |
| Wilk                | 1        | 0.83%   |
| Unifosa             | 1        | 0.83%   |
| Qimonda             | 1        | 0.83%   |
| Patriot             | 1        | 0.83%   |
| Goldkey             | 1        | 0.83%   |
| F7852C80            | 1        | 0.83%   |
| Elpida              | 1        | 0.83%   |
| A-DATA Technology   | 1        | 0.83%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s            | 2        | 1.5%    |
| Team RAM TEAMGROUP-UD4-2666 32GB DIMM DDR4 3000MT/s     | 2        | 1.5%    |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s    | 2        | 1.5%    |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s | 2        | 1.5%    |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s    | 2        | 1.5%    |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s     | 2        | 1.5%    |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s     | 2        | 1.5%    |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s       | 2        | 1.5%    |
| Kingston RAM KHX1600C10D3/8G 8192MB DIMM DDR3 1600MT/s  | 2        | 1.5%    |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s   | 2        | 1.5%    |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s     | 2        | 1.5%    |
| G.Skill RAM F4-3200C16-16GTZR 16GB DIMM DDR4 3333MT/s   | 2        | 1.5%    |
| Unknown                                                 | 2        | 1.5%    |
| Wilk RAM IRX3200D464L16A/16G 16GB DIMM DDR4 3200MT/s    | 1        | 0.75%   |
| Unknown RAM TM44D18UD04MU-NUK 4096MB DIMM DDR4 2400MT/s | 1        | 0.75%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s               | 1        | 0.75%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                    | 1        | 0.75%   |
| Unknown RAM Module 8192MB DIMM DDR4 2400MT/s            | 1        | 0.75%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s            | 1        | 0.75%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s            | 1        | 0.75%   |
| Unknown RAM Module 4GB DIMM SDRAM 1066MT/s              | 1        | 0.75%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                | 1        | 0.75%   |
| Unknown RAM Module 4GB DIMM 400MT/s                     | 1        | 0.75%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                    | 1        | 0.75%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                    | 1        | 0.75%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s            | 1        | 0.75%   |
| Unknown RAM Module 4096MB DIMM DDR 1600MT/s             | 1        | 0.75%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                  | 1        | 0.75%   |
| Unknown RAM Module 2GB DIMM DDR2                        | 1        | 0.75%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s          | 1        | 0.75%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s            | 1        | 0.75%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s            | 1        | 0.75%   |
| Unknown RAM Module 2048MB DIMM DDR2 1333MT/s            | 1        | 0.75%   |
| Unknown RAM Module 1GB DIMM DDR2 333MT/s                | 1        | 0.75%   |
| Unknown RAM Module 1GB DIMM 400MT/s                     | 1        | 0.75%   |
| Unknown RAM Module 1024MB DIMM SDRAM 800MT/s            | 1        | 0.75%   |
| Unknown RAM 04S2400CL17A 4096MB DIMM DDR4 2400MT/s      | 1        | 0.75%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s       | 1        | 0.75%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3733MT/s      | 1        | 0.75%   |
| Team RAM TEAMGROUP-UD3-1600 2GB DIMM DDR3 1600MT/s      | 1        | 0.75%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 45       | 41.67%  |
| DDR3    | 43       | 39.81%  |
| Unknown | 7        | 6.48%   |
| DDR2    | 6        | 5.56%   |
| SDRAM   | 4        | 3.7%    |
| DDR     | 2        | 1.85%   |
| LPDDR4  | 1        | 0.93%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 102      | 96.23%  |
| SODIMM       | 2        | 1.89%   |
| Row Of Chips | 1        | 0.94%   |
| FB-DIMM      | 1        | 0.94%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 47       | 39.5%   |
| 4096  | 34       | 28.57%  |
| 2048  | 15       | 12.61%  |
| 16384 | 13       | 10.92%  |
| 32768 | 6        | 5.04%   |
| 1024  | 4        | 3.36%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 24       | 20.34%  |
| 1333    | 17       | 14.41%  |
| 3200    | 12       | 10.17%  |
| 3600    | 10       | 8.47%   |
| 2133    | 6        | 5.08%   |
| 3000    | 4        | 3.39%   |
| 2667    | 4        | 3.39%   |
| 2400    | 4        | 3.39%   |
| 1866    | 4        | 3.39%   |
| 1800    | 4        | 3.39%   |
| 800     | 4        | 3.39%   |
| 2666    | 3        | 2.54%   |
| 3866    | 2        | 1.69%   |
| 3466    | 2        | 1.69%   |
| 3333    | 2        | 1.69%   |
| 1867    | 2        | 1.69%   |
| 4000    | 1        | 0.85%   |
| 3800    | 1        | 0.85%   |
| 3733    | 1        | 0.85%   |
| 3666    | 1        | 0.85%   |
| 2933    | 1        | 0.85%   |
| 2800    | 1        | 0.85%   |
| 2200    | 1        | 0.85%   |
| 1400    | 1        | 0.85%   |
| 1066    | 1        | 0.85%   |
| 976     | 1        | 0.85%   |
| 667     | 1        | 0.85%   |
| 400     | 1        | 0.85%   |
| 333     | 1        | 0.85%   |
| Unknown | 1        | 0.85%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 9        | 25.71%  |
| Canon               | 7        | 20%     |
| Brother Industries  | 7        | 20%     |
| Samsung Electronics | 6        | 17.14%  |
| Seiko Epson         | 5        | 14.29%  |
| QinHeng Electronics | 1        | 2.86%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Seiko Epson L3110 Series             | 2        | 5.71%   |
| HP DeskJet 2130 series               | 2        | 5.71%   |
| Seiko Epson XP-7100 Series           | 1        | 2.86%   |
| Seiko Epson XP-200 Series            | 1        | 2.86%   |
| Seiko Epson ET-2820 Series           | 1        | 2.86%   |
| Samsung SCX-483x 5x3x Series         | 1        | 2.86%   |
| Samsung SCX-4200 series              | 1        | 2.86%   |
| Samsung SCX-3400 Series              | 1        | 2.86%   |
| Samsung ML-2950 Series               | 1        | 2.86%   |
| Samsung ML-216x Series Laser Printer | 1        | 2.86%   |
| Samsung C460 Series                  | 1        | 2.86%   |
| QinHeng CH340S                       | 1        | 2.86%   |
| HP Smart Tank 510 series             | 1        | 2.86%   |
| HP PSC 1100 series                   | 1        | 2.86%   |
| HP Officejet 6600                    | 1        | 2.86%   |
| HP OfficeJet 4650 series             | 1        | 2.86%   |
| HP LaserJet Professional P1102w      | 1        | 2.86%   |
| HP ENVY 4520 series                  | 1        | 2.86%   |
| HP DeskJet 2700 series               | 1        | 2.86%   |
| Canon TS3100 series                  | 1        | 2.86%   |
| Canon TR4500 series                  | 1        | 2.86%   |
| Canon PIXMA MG2500 Series            | 1        | 2.86%   |
| Canon LiDE 400                       | 1        | 2.86%   |
| Canon iP4200                         | 1        | 2.86%   |
| Canon G3010 series                   | 1        | 2.86%   |
| Canon E410 series                    | 1        | 2.86%   |
| Brother QL-500 label printer         | 1        | 2.86%   |
| Brother MFC-J1010DW                  | 1        | 2.86%   |
| Brother MFC-9140CDN                  | 1        | 2.86%   |
| Brother MFC-1810                     | 1        | 2.86%   |
| Brother HL-3142CW series             | 1        | 2.86%   |
| Brother HL-2140 series               | 1        | 2.86%   |
| Brother DCP-L2540DW                  | 1        | 2.86%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 5        | 71.43%  |
| Hewlett-Packard | 2        | 28.57%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| HP ScanJet 2400c        | 1        | 14.29%  |
| HP PSC 1200             | 1        | 14.29%  |
| Canon CanoScan LiDE 60  | 1        | 14.29%  |
| Canon CanoScan LiDE 110 | 1        | 14.29%  |
| Canon CanoScan LiDE 100 | 1        | 14.29%  |
| Canon CanoScan D660U    | 1        | 14.29%  |
| Canon CanoScan 8800F    | 1        | 14.29%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 38       | 28.57%  |
| Microdia                      | 15       | 11.28%  |
| Microsoft                     | 9        | 6.77%   |
| Sunplus Innovation Technology | 7        | 5.26%   |
| Samsung Electronics           | 7        | 5.26%   |
| Generalplus Technology        | 6        | 4.51%   |
| ARC International             | 6        | 4.51%   |
| Apple                         | 6        | 4.51%   |
| Chicony Electronics           | 4        | 3.01%   |
| Razer USA                     | 3        | 2.26%   |
| Jieli Technology              | 3        | 2.26%   |
| Xiongmai                      | 2        | 1.5%    |
| Realtek Semiconductor         | 2        | 1.5%    |
| Guillemot                     | 2        | 1.5%    |
| Creative Technology           | 2        | 1.5%    |
| 2M UVC CAMERA                 | 2        | 1.5%    |
| Unknown                       | 1        | 0.75%   |
| Tobii Technology AB           | 1        | 0.75%   |
| Teslong Camera                | 1        | 0.75%   |
| Suyin                         | 1        | 0.75%   |
| Sunplus Technology            | 1        | 0.75%   |
| Sonix Technology              | 1        | 0.75%   |
| Pixart Imaging                | 1        | 0.75%   |
| lihappe8                      | 1        | 0.75%   |
| INOGENI                       | 1        | 0.75%   |
| IMC Networks                  | 1        | 0.75%   |
| Huawei Technologies           | 1        | 0.75%   |
| Hewlett-Packard               | 1        | 0.75%   |
| Genesys Logic                 | 1        | 0.75%   |
| EC2U200                       | 1        | 0.75%   |
| Cubeternet                    | 1        | 0.75%   |
| AVerMedia Technologies        | 1        | 0.75%   |
| Arkmicro Technologies         | 1        | 0.75%   |
| Alcor Micro                   | 1        | 0.75%   |
| A4Tech                        | 1        | 0.75%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech Webcam C270                    | 11       | 8.15%   |
| Samsung Galaxy series, misc. (MTP mode) | 7        | 5.19%   |
| Logitech HD Pro Webcam C920             | 6        | 4.44%   |
| ARC International Camera                | 6        | 4.44%   |
| Microsoft LifeCam HD-3000               | 5        | 3.7%    |
| Apple iPhone 5/5C/5S/6/SE               | 5        | 3.7%    |
| Microdia USB 2.0 Camera                 | 4        | 2.96%   |
| Logitech HD Webcam C615                 | 4        | 2.96%   |
| Generalplus GENERAL WEBCAM              | 4        | 2.96%   |
| Sunplus HD 720P webcam                  | 3        | 2.22%   |
| Razer USA Gaming Webcam [Kiyo]          | 3        | 2.22%   |
| Microdia Integrated Camera              | 3        | 2.22%   |
| Logitech C920 PRO HD Webcam             | 3        | 2.22%   |
| Jieli USB PHY 2.0                       | 3        | 2.22%   |
| Chicony HP High Definition 1MP Webcam   | 3        | 2.22%   |
| Xiongmai web camera                     | 2        | 1.48%   |
| Sunplus FHD Camera Microphone           | 2        | 1.48%   |
| Microdia Webcam Vitade AF               | 2        | 1.48%   |
| Microdia USB Live camera                | 2        | 1.48%   |
| Microdia Hy-HD-Camera                   | 2        | 1.48%   |
| Logitech HD Webcam C910                 | 2        | 1.48%   |
| Logitech HD Webcam C525                 | 2        | 1.48%   |
| Logitech C922 Pro Stream Webcam         | 2        | 1.48%   |
| 2M UVC CAMERA NexiGo N60 FHD Webcam     | 2        | 1.48%   |
| Unknown HD camera                       | 1        | 0.74%   |
| Tobii AB EyeChip                        | 1        | 0.74%   |
| Teslong Camera Teslong Camera           | 1        | 0.74%   |
| Suyin HD WebCam                         | 1        | 0.74%   |
| Sunplus General Image Device            | 1        | 0.74%   |
| Sunplus Integrated Camera               | 1        | 0.74%   |
| Sunplus Aukey-PC-LM1E Camera            | 1        | 0.74%   |
| Sonix USB 2.0 Camera                    | 1        | 0.74%   |
| Realtek WEB CAMERA M9 Pro               | 1        | 0.74%   |
| Realtek HP High Definition 1MP Webcam   | 1        | 0.74%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro    | 1        | 0.74%   |
| Microsoft MicrosoftÂ LifeCam Cinema    | 1        | 0.74%   |
| Microsoft LifeCam VX-500 [1357]         | 1        | 0.74%   |
| Microsoft LifeCam VX-2000               | 1        | 0.74%   |
| Microsoft LifeCam HD-5000               | 1        | 0.74%   |
| Microdia PC Camera (SN9C110)            | 1        | 0.74%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Realtek Semiconductor     | 2        | 25%     |
| Advanced Card Systems     | 2        | 25%     |
| SCM Microsystems          | 1        | 12.5%   |
| Reiner SCT Kartensysteme  | 1        | 12.5%   |
| Fujitsu Siemens Computers | 1        | 12.5%   |
| Alcor Micro               | 1        | 12.5%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Realtek Semiconductor Smart Card Reader Interface      | 2        | 25%     |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 1        | 12.5%   |
| Reiner SCT Kartensysteme cyberJack e-com/pinpad        | 1        | 12.5%   |
| Fujitsu Siemens Computers SmartCard Reader 2A          | 1        | 12.5%   |
| Alcor Micro AU9540 Smartcard Reader                    | 1        | 12.5%   |
| Advanced Card Systems ACR39U                           | 1        | 12.5%   |
| Advanced Card Systems ACR1281 1S Dual Reader           | 1        | 12.5%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 681      | 81.36%  |
| 1     | 143      | 17.08%  |
| 2     | 12       | 1.43%   |
| 3     | 1        | 0.12%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 70       | 42.17%  |
| Graphics card            | 62       | 37.35%  |
| Communication controller | 9        | 5.42%   |
| Multimedia controller    | 6        | 3.61%   |
| Chipcard                 | 6        | 3.61%   |
| Unassigned class         | 4        | 2.41%   |
| Modem                    | 2        | 1.2%    |
| Camera                   | 2        | 1.2%    |
| Storage/raid             | 1        | 0.6%    |
| Storage/ide              | 1        | 0.6%    |
| Sound                    | 1        | 0.6%    |
| Dvb card                 | 1        | 0.6%    |
| Card reader              | 1        | 0.6%    |

