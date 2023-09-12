Linux in Australia - Tested Hardware & Statistics
-------------------------------------------------

A project to collect tested hardware configurations for Linux in Australia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Australia/Desktop/README.md) and [notebooks](/Location/Australia/Notebook/README.md).

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

Total: 5623

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T410 2522PT3       | Notebook    | [da7303433d](https://linux-hardware.org/?probe=da7303433d) | Sep 07, 2023 |
| Gigabyte      | Z87X-UD3H-CF                | Desktop     | [43f205483a](https://linux-hardware.org/?probe=43f205483a) | Sep 07, 2023 |
| Valve         | Jupiter                     | Notebook    | [d4ca58e970](https://linux-hardware.org/?probe=d4ca58e970) | Sep 07, 2023 |
| Intel         | NUC8BEB J72692-306          | Mini pc     | [6cbfa96139](https://linux-hardware.org/?probe=6cbfa96139) | Sep 07, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [f0c3188082](https://linux-hardware.org/?probe=f0c3188082) | Sep 07, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [2285c5c493](https://linux-hardware.org/?probe=2285c5c493) | Sep 06, 2023 |
| Dell          | 0PC5F7 A00                  | Desktop     | [9ffb575d81](https://linux-hardware.org/?probe=9ffb575d81) | Sep 06, 2023 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | Desktop     | [c43f7a6e53](https://linux-hardware.org/?probe=c43f7a6e53) | Sep 06, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [f421de992d](https://linux-hardware.org/?probe=f421de992d) | Sep 06, 2023 |
| ASRock        | B650E PG-ITX WiFi           | Desktop     | [9dd5c2a861](https://linux-hardware.org/?probe=9dd5c2a861) | Sep 06, 2023 |
| Acer          | Aspire Z3-615               | All in one  | [10bb2b77f8](https://linux-hardware.org/?probe=10bb2b77f8) | Sep 06, 2023 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [7db6779b5c](https://linux-hardware.org/?probe=7db6779b5c) | Sep 06, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [424ab4dc3d](https://linux-hardware.org/?probe=424ab4dc3d) | Sep 05, 2023 |
| Dell          | Latitude 7280               | Notebook    | [3cf6ec76b5](https://linux-hardware.org/?probe=3cf6ec76b5) | Sep 05, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [51b40f3137](https://linux-hardware.org/?probe=51b40f3137) | Sep 05, 2023 |
| ASRock        | AD525PV3                    | Desktop     | [0fa982f7ad](https://linux-hardware.org/?probe=0fa982f7ad) | Sep 05, 2023 |
| ASRock        | AD525PV3                    | Desktop     | [9ab25d4913](https://linux-hardware.org/?probe=9ab25d4913) | Sep 05, 2023 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [d20cf2e835](https://linux-hardware.org/?probe=d20cf2e835) | Sep 05, 2023 |
| Gigabyte      | Z590 AORUS MASTER           | Desktop     | [40785211e9](https://linux-hardware.org/?probe=40785211e9) | Sep 05, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [318d03cfad](https://linux-hardware.org/?probe=318d03cfad) | Sep 04, 2023 |
| Intel         | NUC12WSBi5 M46425-302       | Mini pc     | [362e60bccc](https://linux-hardware.org/?probe=362e60bccc) | Sep 04, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [ae41ba8b62](https://linux-hardware.org/?probe=ae41ba8b62) | Sep 04, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [6cbaac077e](https://linux-hardware.org/?probe=6cbaac077e) | Sep 03, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [16b96480a2](https://linux-hardware.org/?probe=16b96480a2) | Sep 03, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [bf3a5838f0](https://linux-hardware.org/?probe=bf3a5838f0) | Sep 02, 2023 |
| Dell          | Latitude E6520              | Notebook    | [b53cd78958](https://linux-hardware.org/?probe=b53cd78958) | Sep 02, 2023 |
| Dell          | G15 5520                    | Notebook    | [796ae7cf79](https://linux-hardware.org/?probe=796ae7cf79) | Sep 02, 2023 |
| ASUSTek       | ROG Maximus XII EXTREME     | Desktop     | [7cfd1c36d1](https://linux-hardware.org/?probe=7cfd1c36d1) | Sep 02, 2023 |
| Intel         | NUC11PABi7 M68262-501       | Mini pc     | [59677d7116](https://linux-hardware.org/?probe=59677d7116) | Sep 02, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [da8d60051c](https://linux-hardware.org/?probe=da8d60051c) | Sep 02, 2023 |
| ASUSTek       | K53SD                       | Notebook    | [9a208331c5](https://linux-hardware.org/?probe=9a208331c5) | Sep 01, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [f3c99a0cc5](https://linux-hardware.org/?probe=f3c99a0cc5) | Sep 01, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [17e3dd86e8](https://linux-hardware.org/?probe=17e3dd86e8) | Sep 01, 2023 |
| Dell          | Latitude E7470              | Notebook    | [0580f1c293](https://linux-hardware.org/?probe=0580f1c293) | Sep 01, 2023 |
| HP            | EliteBook Folio 1040 G1     | Notebook    | [1c496aba4a](https://linux-hardware.org/?probe=1c496aba4a) | Sep 01, 2023 |
| Lenovo        | Legion Slim 7 16IRH8 82Y... | Notebook    | [ab14d9d9bb](https://linux-hardware.org/?probe=ab14d9d9bb) | Aug 31, 2023 |
| Dell          | Latitude 7340               | Notebook    | [d6d1df94f5](https://linux-hardware.org/?probe=d6d1df94f5) | Aug 31, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [a99931801d](https://linux-hardware.org/?probe=a99931801d) | Aug 31, 2023 |
| HP            | ENVY m6                     | Notebook    | [eea19d891e](https://linux-hardware.org/?probe=eea19d891e) | Aug 31, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [84ed05802d](https://linux-hardware.org/?probe=84ed05802d) | Aug 31, 2023 |
| Gigabyte      | D525TUD                     | Desktop     | [9a459d2372](https://linux-hardware.org/?probe=9a459d2372) | Aug 31, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [ffb1e72844](https://linux-hardware.org/?probe=ffb1e72844) | Aug 31, 2023 |
| Dell          | Latitude 7390               | Notebook    | [3aaefe5b81](https://linux-hardware.org/?probe=3aaefe5b81) | Aug 31, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [7741e9850b](https://linux-hardware.org/?probe=7741e9850b) | Aug 31, 2023 |
| Microsoft     | Surface Go 3                | Tablet      | [4f320554b6](https://linux-hardware.org/?probe=4f320554b6) | Aug 31, 2023 |
| HP            | 843B                        | Desktop     | [472228092a](https://linux-hardware.org/?probe=472228092a) | Aug 31, 2023 |
| Dell          | 0Y5DDC A00                  | Desktop     | [21ec7587ed](https://linux-hardware.org/?probe=21ec7587ed) | Aug 30, 2023 |
| Apple         | MacBookPro15,2              | Notebook    | [a93751de6d](https://linux-hardware.org/?probe=a93751de6d) | Aug 30, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [9782f69f43](https://linux-hardware.org/?probe=9782f69f43) | Aug 30, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [1964cb4738](https://linux-hardware.org/?probe=1964cb4738) | Aug 30, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [7176f2933c](https://linux-hardware.org/?probe=7176f2933c) | Aug 30, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [ea2ba90391](https://linux-hardware.org/?probe=ea2ba90391) | Aug 30, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [13b77d8273](https://linux-hardware.org/?probe=13b77d8273) | Aug 30, 2023 |
| Acer          | Aspire E1-572               | Notebook    | [77cdb6f4a4](https://linux-hardware.org/?probe=77cdb6f4a4) | Aug 30, 2023 |
| ASUSTek       | P552LA                      | Notebook    | [6eca0a231c](https://linux-hardware.org/?probe=6eca0a231c) | Aug 30, 2023 |
| Dell          | Latitude 3350               | Notebook    | [4fa556a69f](https://linux-hardware.org/?probe=4fa556a69f) | Aug 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [dc4910965c](https://linux-hardware.org/?probe=dc4910965c) | Aug 29, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [a2f594cf56](https://linux-hardware.org/?probe=a2f594cf56) | Aug 29, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [43db739186](https://linux-hardware.org/?probe=43db739186) | Aug 29, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [4cdf174574](https://linux-hardware.org/?probe=4cdf174574) | Aug 29, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [4c46f7ae80](https://linux-hardware.org/?probe=4c46f7ae80) | Aug 28, 2023 |
| Intel         | NUC11PABi7 K90104-302       | Mini pc     | [ee8ee6bf06](https://linux-hardware.org/?probe=ee8ee6bf06) | Aug 28, 2023 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [ed544a4405](https://linux-hardware.org/?probe=ed544a4405) | Aug 28, 2023 |
| Lenovo        | Yoga 310-11IAP 80U2         | Convertible | [5cd969711d](https://linux-hardware.org/?probe=5cd969711d) | Aug 28, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [714c46e2fd](https://linux-hardware.org/?probe=714c46e2fd) | Aug 28, 2023 |
| Dell          | Latitude 14 Rugged (5404... | Notebook    | [c96c172d03](https://linux-hardware.org/?probe=c96c172d03) | Aug 27, 2023 |
| Dell          | 03NVJ6 A01                  | Desktop     | [00a28522c2](https://linux-hardware.org/?probe=00a28522c2) | Aug 27, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [883d4fbfeb](https://linux-hardware.org/?probe=883d4fbfeb) | Aug 27, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [d80e4744e9](https://linux-hardware.org/?probe=d80e4744e9) | Aug 27, 2023 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [ea6d90ba09](https://linux-hardware.org/?probe=ea6d90ba09) | Aug 27, 2023 |
| HP            | Compaq 6710b (GE822PA#AB... | Notebook    | [134d0685ff](https://linux-hardware.org/?probe=134d0685ff) | Aug 26, 2023 |
| Gigabyte      | H97N-WIFI                   | Desktop     | [6edcb45992](https://linux-hardware.org/?probe=6edcb45992) | Aug 26, 2023 |
| ASUSTek       | P5K-E                       | Desktop     | [aa48da4e34](https://linux-hardware.org/?probe=aa48da4e34) | Aug 26, 2023 |
| HP            | ProLiant ML10 v2            | Desktop     | [86cb962a7d](https://linux-hardware.org/?probe=86cb962a7d) | Aug 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [e78b6b1077](https://linux-hardware.org/?probe=e78b6b1077) | Aug 26, 2023 |
| Acer          | Predator G9-793             | Notebook    | [531f857477](https://linux-hardware.org/?probe=531f857477) | Aug 26, 2023 |
| HP            | ProBook 450 15.6 inch G1... | Notebook    | [973d7867a4](https://linux-hardware.org/?probe=973d7867a4) | Aug 26, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [fc8e4dd4ff](https://linux-hardware.org/?probe=fc8e4dd4ff) | Aug 25, 2023 |
| Gigabyte      | Z68MX-UD2H-B3               | Desktop     | [93cce7551b](https://linux-hardware.org/?probe=93cce7551b) | Aug 25, 2023 |
| Dell          | 02C2CP A06                  | Server      | [dad6e7b74c](https://linux-hardware.org/?probe=dad6e7b74c) | Aug 25, 2023 |
| Dell          | XPS 17 9700                 | Notebook    | [93fec269da](https://linux-hardware.org/?probe=93fec269da) | Aug 25, 2023 |
| Gigabyte      | X79-UP4                     | Desktop     | [58ae6791f0](https://linux-hardware.org/?probe=58ae6791f0) | Aug 25, 2023 |
| Dell          | Vostro 2520                 | Notebook    | [96018ae096](https://linux-hardware.org/?probe=96018ae096) | Aug 24, 2023 |
| Dell          | 06D7TR A02                  | Desktop     | [d0b04a9056](https://linux-hardware.org/?probe=d0b04a9056) | Aug 24, 2023 |
| AZW           | SER                         | Mini pc     | [309bc27af7](https://linux-hardware.org/?probe=309bc27af7) | Aug 24, 2023 |
| Lenovo        | ThinkPad R61 7732NDG        | Notebook    | [b0d510a7ad](https://linux-hardware.org/?probe=b0d510a7ad) | Aug 24, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [a06cf8de37](https://linux-hardware.org/?probe=a06cf8de37) | Aug 24, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [b6591e9fd9](https://linux-hardware.org/?probe=b6591e9fd9) | Aug 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [5a6247f9b2](https://linux-hardware.org/?probe=5a6247f9b2) | Aug 24, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [a1bdeba9c8](https://linux-hardware.org/?probe=a1bdeba9c8) | Aug 23, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [c5484868fd](https://linux-hardware.org/?probe=c5484868fd) | Aug 23, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [68d3bc88e4](https://linux-hardware.org/?probe=68d3bc88e4) | Aug 23, 2023 |
| Gigabyte      | GA-A55M-S2V                 | Desktop     | [e9b32aa827](https://linux-hardware.org/?probe=e9b32aa827) | Aug 23, 2023 |
| HP            | Pavilion dv6                | Notebook    | [38fbd02f14](https://linux-hardware.org/?probe=38fbd02f14) | Aug 23, 2023 |
| HP            | 212B                        | Desktop     | [a186c2ccf3](https://linux-hardware.org/?probe=a186c2ccf3) | Aug 23, 2023 |
| Fujitsu       | S6420                       | Notebook    | [044d4185b7](https://linux-hardware.org/?probe=044d4185b7) | Aug 22, 2023 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [b40144bd93](https://linux-hardware.org/?probe=b40144bd93) | Aug 22, 2023 |
| Microsoft     | Surface Go 3                | Tablet      | [17d3cd9a3c](https://linux-hardware.org/?probe=17d3cd9a3c) | Aug 22, 2023 |
| ASUSTek       | P7P55-M                     | Desktop     | [0f5028d5fc](https://linux-hardware.org/?probe=0f5028d5fc) | Aug 22, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [a8a1e5df49](https://linux-hardware.org/?probe=a8a1e5df49) | Aug 21, 2023 |
| Kogan         | KAL14N360PA                 | Notebook    | [527a0d3cba](https://linux-hardware.org/?probe=527a0d3cba) | Aug 20, 2023 |
| Kogan         | KAL14N360PA                 | Notebook    | [b7cecb1518](https://linux-hardware.org/?probe=b7cecb1518) | Aug 20, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [158cc5fe6f](https://linux-hardware.org/?probe=158cc5fe6f) | Aug 20, 2023 |
| HP            | 158A                        | Desktop     | [ba0211611f](https://linux-hardware.org/?probe=ba0211611f) | Aug 19, 2023 |
| HP            | 158A                        | Desktop     | [25e8725a35](https://linux-hardware.org/?probe=25e8725a35) | Aug 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [c642878288](https://linux-hardware.org/?probe=c642878288) | Aug 19, 2023 |
| Lenovo        | Yoga 7 14IAL7 82QE          | Convertible | [dc5d42e6cb](https://linux-hardware.org/?probe=dc5d42e6cb) | Aug 19, 2023 |
| Intel         | NUC8BEB J72692-306          | Mini pc     | [6a155984af](https://linux-hardware.org/?probe=6a155984af) | Aug 19, 2023 |
| Lenovo        | Yoga Pro 9 14IRP8 83BU      | Notebook    | [b42f885e14](https://linux-hardware.org/?probe=b42f885e14) | Aug 18, 2023 |
| Toshiba       | Satellite L550              | Notebook    | [4c331017e2](https://linux-hardware.org/?probe=4c331017e2) | Aug 18, 2023 |
| Acer          | Aspire 5755G                | Notebook    | [720c3bfa88](https://linux-hardware.org/?probe=720c3bfa88) | Aug 18, 2023 |
| Intel         | D53427RKE G87971-402        | Desktop     | [433dcaffa6](https://linux-hardware.org/?probe=433dcaffa6) | Aug 17, 2023 |
| Acer          | Aspire E5-571               | Notebook    | [8a924c30e6](https://linux-hardware.org/?probe=8a924c30e6) | Aug 17, 2023 |
| MSI           | MAG Z390 TOMAHAWK           | Desktop     | [1d389611a3](https://linux-hardware.org/?probe=1d389611a3) | Aug 16, 2023 |
| HP            | Elite Dragonfly             | Convertible | [7419fe990e](https://linux-hardware.org/?probe=7419fe990e) | Aug 16, 2023 |
| Dell          | Latitude 7210 2-in-1        | Tablet      | [59b0f15b1d](https://linux-hardware.org/?probe=59b0f15b1d) | Aug 16, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO II     | Desktop     | [122b800eae](https://linux-hardware.org/?probe=122b800eae) | Aug 16, 2023 |
| MSI           | GS60 6QE                    | Notebook    | [3372d46d8c](https://linux-hardware.org/?probe=3372d46d8c) | Aug 16, 2023 |
| Google        | Phaser360                   | Notebook    | [3c248cc2c8](https://linux-hardware.org/?probe=3c248cc2c8) | Aug 16, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [881b50cb6f](https://linux-hardware.org/?probe=881b50cb6f) | Aug 16, 2023 |
| Dell          | Precision 5520              | Notebook    | [0516c33229](https://linux-hardware.org/?probe=0516c33229) | Aug 16, 2023 |
| Dell          | Precision 5520              | Notebook    | [b9a35fa791](https://linux-hardware.org/?probe=b9a35fa791) | Aug 16, 2023 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | Notebook    | [6242833326](https://linux-hardware.org/?probe=6242833326) | Aug 15, 2023 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | Notebook    | [22252eb1d9](https://linux-hardware.org/?probe=22252eb1d9) | Aug 15, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [290298fd99](https://linux-hardware.org/?probe=290298fd99) | Aug 15, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [bf2f7b52d1](https://linux-hardware.org/?probe=bf2f7b52d1) | Aug 15, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [7b94897e1a](https://linux-hardware.org/?probe=7b94897e1a) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [b62ff7f358](https://linux-hardware.org/?probe=b62ff7f358) | Aug 14, 2023 |
| HP            | Notebook                    | Notebook    | [f32b596c87](https://linux-hardware.org/?probe=f32b596c87) | Aug 14, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [fd93a82029](https://linux-hardware.org/?probe=fd93a82029) | Aug 14, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [b950177908](https://linux-hardware.org/?probe=b950177908) | Aug 14, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [dc696b572c](https://linux-hardware.org/?probe=dc696b572c) | Aug 14, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [d2ccdc066b](https://linux-hardware.org/?probe=d2ccdc066b) | Aug 14, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [11b8c16b30](https://linux-hardware.org/?probe=11b8c16b30) | Aug 14, 2023 |
| Gigabyte      | Z77M-D3H-MVP                | Desktop     | [c939a92f1d](https://linux-hardware.org/?probe=c939a92f1d) | Aug 14, 2023 |
| Apple         | Mac-F223BEC8                | Desktop     | [74a3be9a4a](https://linux-hardware.org/?probe=74a3be9a4a) | Aug 14, 2023 |
| Gigabyte      | Z77M-D3H-MVP                | Desktop     | [56efab026f](https://linux-hardware.org/?probe=56efab026f) | Aug 14, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | Desktop     | [9a8e4bc08d](https://linux-hardware.org/?probe=9a8e4bc08d) | Aug 14, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [5d7e68e3ae](https://linux-hardware.org/?probe=5d7e68e3ae) | Aug 14, 2023 |
| Dell          | Latitude E7470              | Notebook    | [99518b81f7](https://linux-hardware.org/?probe=99518b81f7) | Aug 13, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [6602bb3d0a](https://linux-hardware.org/?probe=6602bb3d0a) | Aug 13, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [5a809fe1c3](https://linux-hardware.org/?probe=5a809fe1c3) | Aug 13, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [1de4045fb5](https://linux-hardware.org/?probe=1de4045fb5) | Aug 13, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [3ac1be3b93](https://linux-hardware.org/?probe=3ac1be3b93) | Aug 13, 2023 |
| HP            | ProBook 6450b               | Notebook    | [8862a40143](https://linux-hardware.org/?probe=8862a40143) | Aug 13, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [c28cbbd2a1](https://linux-hardware.org/?probe=c28cbbd2a1) | Aug 13, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [6d1e3a24e8](https://linux-hardware.org/?probe=6d1e3a24e8) | Aug 13, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [551d8f3fc8](https://linux-hardware.org/?probe=551d8f3fc8) | Aug 13, 2023 |
| Dell          | Latitude E6410              | Notebook    | [8ed9952374](https://linux-hardware.org/?probe=8ed9952374) | Aug 13, 2023 |
| Dell          | Inspiron M5010              | Notebook    | [dd2538ba1a](https://linux-hardware.org/?probe=dd2538ba1a) | Aug 13, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [b6b99bf7bd](https://linux-hardware.org/?probe=b6b99bf7bd) | Aug 12, 2023 |
| Gigabyte      | G1.Sniper M3-CF             | Desktop     | [f4d0fd6811](https://linux-hardware.org/?probe=f4d0fd6811) | Aug 12, 2023 |
| Gigabyte      | G1.Sniper M3-CF             | Desktop     | [a5681e12d3](https://linux-hardware.org/?probe=a5681e12d3) | Aug 12, 2023 |
| Panasonic     | CF-19ADNAXDA                | Notebook    | [d96cf2b13c](https://linux-hardware.org/?probe=d96cf2b13c) | Aug 12, 2023 |
| Dell          | G7 7790                     | Notebook    | [b5062f0928](https://linux-hardware.org/?probe=b5062f0928) | Aug 12, 2023 |
| Intel         | NUC11PABi7 M68262-501       | Mini pc     | [422a91a4eb](https://linux-hardware.org/?probe=422a91a4eb) | Aug 12, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [359d84713c](https://linux-hardware.org/?probe=359d84713c) | Aug 11, 2023 |
| Acer          | TMP255-M                    | Notebook    | [0b1adaea4e](https://linux-hardware.org/?probe=0b1adaea4e) | Aug 11, 2023 |
| Microsoft     | Surface Go 3                | Tablet      | [75d63c7495](https://linux-hardware.org/?probe=75d63c7495) | Aug 11, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [93a61b62a5](https://linux-hardware.org/?probe=93a61b62a5) | Aug 11, 2023 |
| Leader        | SC404PRO                    | Notebook    | [6f24ee5e0c](https://linux-hardware.org/?probe=6f24ee5e0c) | Aug 11, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [025afcb20d](https://linux-hardware.org/?probe=025afcb20d) | Aug 10, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | Notebook    | [2f64f3ee9a](https://linux-hardware.org/?probe=2f64f3ee9a) | Aug 10, 2023 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | Desktop     | [5264c46571](https://linux-hardware.org/?probe=5264c46571) | Aug 10, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [c5491b8e9f](https://linux-hardware.org/?probe=c5491b8e9f) | Aug 10, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [2be2a9d5f4](https://linux-hardware.org/?probe=2be2a9d5f4) | Aug 09, 2023 |
| Dell          | Inspiron M5010              | Notebook    | [be4ad618b4](https://linux-hardware.org/?probe=be4ad618b4) | Aug 09, 2023 |
| Apple         | MacBookPro15,2              | Notebook    | [68e26bb5d3](https://linux-hardware.org/?probe=68e26bb5d3) | Aug 09, 2023 |
| Dell          | 0X2MKR A00                  | All in one  | [84c3eefc94](https://linux-hardware.org/?probe=84c3eefc94) | Aug 08, 2023 |
| Dell          | Vostro 5581                 | Notebook    | [b4495daa07](https://linux-hardware.org/?probe=b4495daa07) | Aug 08, 2023 |
| Dell          | Inspiron 5485 2n1           | Convertible | [f4c69a94e9](https://linux-hardware.org/?probe=f4c69a94e9) | Aug 08, 2023 |
| Dell          | Inspiron 5485 2n1           | Convertible | [e5efd1b16c](https://linux-hardware.org/?probe=e5efd1b16c) | Aug 08, 2023 |
| ASUSTek       | STRIX H270F GAMING          | Desktop     | [ab74b5c684](https://linux-hardware.org/?probe=ab74b5c684) | Aug 08, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [e8524b0045](https://linux-hardware.org/?probe=e8524b0045) | Aug 08, 2023 |
| ASUSTek       | STRIX H270F GAMING          | Desktop     | [85ffbedac4](https://linux-hardware.org/?probe=85ffbedac4) | Aug 08, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [ffd0be48c6](https://linux-hardware.org/?probe=ffd0be48c6) | Aug 08, 2023 |
| HP            | 212B                        | Desktop     | [b7de4a2b0a](https://linux-hardware.org/?probe=b7de4a2b0a) | Aug 07, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [51c3d4511a](https://linux-hardware.org/?probe=51c3d4511a) | Aug 07, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [fb1aaeae43](https://linux-hardware.org/?probe=fb1aaeae43) | Aug 07, 2023 |
| Dell          | Inspiron 5770               | Notebook    | [d6a978f124](https://linux-hardware.org/?probe=d6a978f124) | Aug 07, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [f2d72fe710](https://linux-hardware.org/?probe=f2d72fe710) | Aug 07, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [c003e20331](https://linux-hardware.org/?probe=c003e20331) | Aug 06, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [3b589d53bc](https://linux-hardware.org/?probe=3b589d53bc) | Aug 06, 2023 |
| Dell          | 08VT7V A01                  | Server      | [422a30cacf](https://linux-hardware.org/?probe=422a30cacf) | Aug 06, 2023 |
| MSI           | P65 Creator 8RE             | Notebook    | [853567f156](https://linux-hardware.org/?probe=853567f156) | Aug 06, 2023 |
| MSI           | P65 Creator 8RE             | Notebook    | [f26344a920](https://linux-hardware.org/?probe=f26344a920) | Aug 05, 2023 |
| Dell          | Latitude E6220              | Notebook    | [636392b4bf](https://linux-hardware.org/?probe=636392b4bf) | Aug 05, 2023 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [b9d8025a54](https://linux-hardware.org/?probe=b9d8025a54) | Aug 05, 2023 |
| Acer          | AS E5-523G                  | Notebook    | [b37e833d1e](https://linux-hardware.org/?probe=b37e833d1e) | Aug 05, 2023 |
| ASUSTek       | ROG Maximus XII EXTREME     | Desktop     | [f5ebaad3b1](https://linux-hardware.org/?probe=f5ebaad3b1) | Aug 05, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [dd1767aec1](https://linux-hardware.org/?probe=dd1767aec1) | Aug 04, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [15fb5d0baf](https://linux-hardware.org/?probe=15fb5d0baf) | Aug 04, 2023 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [a02f0405a3](https://linux-hardware.org/?probe=a02f0405a3) | Aug 04, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [fe0a1dbc45](https://linux-hardware.org/?probe=fe0a1dbc45) | Aug 04, 2023 |
| Acer          | Aspire 8943G                | Notebook    | [fedb43e298](https://linux-hardware.org/?probe=fedb43e298) | Aug 04, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [90aecb9ada](https://linux-hardware.org/?probe=90aecb9ada) | Aug 04, 2023 |
| Lenovo        | ThinkPad T480s 20L8S84H0... | Notebook    | [d64e9809fa](https://linux-hardware.org/?probe=d64e9809fa) | Aug 04, 2023 |
| Gigabyte      | Z490M GAMING X              | Desktop     | [ad51d2548b](https://linux-hardware.org/?probe=ad51d2548b) | Aug 03, 2023 |
| Dell          | 09M8Y8 A01                  | Desktop     | [e5649696d0](https://linux-hardware.org/?probe=e5649696d0) | Aug 03, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | Notebook    | [c96666b80d](https://linux-hardware.org/?probe=c96666b80d) | Aug 03, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [1eb6fd9620](https://linux-hardware.org/?probe=1eb6fd9620) | Aug 02, 2023 |
| HP            | 2B2C                        | Desktop     | [3f0b3f8811](https://linux-hardware.org/?probe=3f0b3f8811) | Aug 01, 2023 |
| Dell          | 06NWYK A00                  | Desktop     | [1c3a3db0ec](https://linux-hardware.org/?probe=1c3a3db0ec) | Aug 01, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [888c56f232](https://linux-hardware.org/?probe=888c56f232) | Aug 01, 2023 |
| Dell          | 0Y5DDC A00                  | Desktop     | [43624df7d4](https://linux-hardware.org/?probe=43624df7d4) | Jul 30, 2023 |
| Dell          | Inspiron M5010              | Notebook    | [8608f29a0f](https://linux-hardware.org/?probe=8608f29a0f) | Jul 30, 2023 |
| MSI           | Z87-G45 GAMING              | Desktop     | [6c5528a787](https://linux-hardware.org/?probe=6c5528a787) | Jul 30, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [4fb6a46f65](https://linux-hardware.org/?probe=4fb6a46f65) | Jul 30, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [60bf32a368](https://linux-hardware.org/?probe=60bf32a368) | Jul 29, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [580c4fb755](https://linux-hardware.org/?probe=580c4fb755) | Jul 29, 2023 |
| Lenovo        | ThinkBook 13x G2 IAP 21A... | Notebook    | [bc18b4b7ed](https://linux-hardware.org/?probe=bc18b4b7ed) | Jul 29, 2023 |
| Lenovo        | ThinkBook 13x G2 IAP 21A... | Notebook    | [9b4b9b9d59](https://linux-hardware.org/?probe=9b4b9b9d59) | Jul 29, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [e4efeb0276](https://linux-hardware.org/?probe=e4efeb0276) | Jul 29, 2023 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | Desktop     | [8c930cc5e4](https://linux-hardware.org/?probe=8c930cc5e4) | Jul 29, 2023 |
| ASUSTek       | WS C246 PRO                 | Desktop     | [cfffc2ba92](https://linux-hardware.org/?probe=cfffc2ba92) | Jul 28, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [7864dbf54c](https://linux-hardware.org/?probe=7864dbf54c) | Jul 28, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [abf0e5979c](https://linux-hardware.org/?probe=abf0e5979c) | Jul 27, 2023 |
| Toshiba       | PORTEGE X30-E               | Notebook    | [c610464fb5](https://linux-hardware.org/?probe=c610464fb5) | Jul 27, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [0b04075e09](https://linux-hardware.org/?probe=0b04075e09) | Jul 27, 2023 |
| Acer          | TMP255-M                    | Notebook    | [25d376a674](https://linux-hardware.org/?probe=25d376a674) | Jul 26, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [0059745bdf](https://linux-hardware.org/?probe=0059745bdf) | Jul 25, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [90beff8e65](https://linux-hardware.org/?probe=90beff8e65) | Jul 25, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [31b7924358](https://linux-hardware.org/?probe=31b7924358) | Jul 25, 2023 |
| Google        | Sumo                        | Desktop     | [71a7167d22](https://linux-hardware.org/?probe=71a7167d22) | Jul 25, 2023 |
| HP            | 1998                        | Desktop     | [ef5201611b](https://linux-hardware.org/?probe=ef5201611b) | Jul 24, 2023 |
| HP            | 1998                        | Desktop     | [5a95ac128d](https://linux-hardware.org/?probe=5a95ac128d) | Jul 24, 2023 |
| Acer          | TMP255-M                    | Notebook    | [c4bfc82a98](https://linux-hardware.org/?probe=c4bfc82a98) | Jul 24, 2023 |
| Acer          | TMP255-M                    | Notebook    | [7a57ee89af](https://linux-hardware.org/?probe=7a57ee89af) | Jul 24, 2023 |
| Acer          | Aspire A3SP14-31PT          | Convertible | [97f835b6ca](https://linux-hardware.org/?probe=97f835b6ca) | Jul 24, 2023 |
| Intel         | NUC11PABi7 M68262-501       | Mini pc     | [f3d1b0d511](https://linux-hardware.org/?probe=f3d1b0d511) | Jul 24, 2023 |
| ASUSTek       | PN61                        | Mini pc     | [78418a9a7f](https://linux-hardware.org/?probe=78418a9a7f) | Jul 24, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [579d5d5771](https://linux-hardware.org/?probe=579d5d5771) | Jul 24, 2023 |
| Dell          | Latitude 5410               | Notebook    | [29261ea2bb](https://linux-hardware.org/?probe=29261ea2bb) | Jul 24, 2023 |
| MSI           | Cyborg 15 A13VE             | Notebook    | [edf7b092ec](https://linux-hardware.org/?probe=edf7b092ec) | Jul 23, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [35d95135f4](https://linux-hardware.org/?probe=35d95135f4) | Jul 23, 2023 |
| MSI           | Cyborg 15 A13VE             | Notebook    | [421c2ff6b0](https://linux-hardware.org/?probe=421c2ff6b0) | Jul 23, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [a4b823b309](https://linux-hardware.org/?probe=a4b823b309) | Jul 23, 2023 |
| HP            | EliteBook 835 G8 Noteboo... | Notebook    | [a3350e1d80](https://linux-hardware.org/?probe=a3350e1d80) | Jul 23, 2023 |
| HP            | ZBook Studio G3             | Notebook    | [bcfc5b64f4](https://linux-hardware.org/?probe=bcfc5b64f4) | Jul 23, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [f525252834](https://linux-hardware.org/?probe=f525252834) | Jul 23, 2023 |
| MSI           | MEGA BOOK GX620             | Notebook    | [184ec8dfc2](https://linux-hardware.org/?probe=184ec8dfc2) | Jul 22, 2023 |
| Dell          | Latitude E6430s             | Notebook    | [8e74e2a524](https://linux-hardware.org/?probe=8e74e2a524) | Jul 22, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [25ab3b442b](https://linux-hardware.org/?probe=25ab3b442b) | Jul 22, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [20ec4f50dc](https://linux-hardware.org/?probe=20ec4f50dc) | Jul 22, 2023 |
| Lenovo        | ThinkPad Yoga 11e 5th Ge... | Convertible | [bcd5455f58](https://linux-hardware.org/?probe=bcd5455f58) | Jul 22, 2023 |
| MSI           | Z97 PC Mate                 | Desktop     | [f4cddb5e86](https://linux-hardware.org/?probe=f4cddb5e86) | Jul 22, 2023 |
| Intel         | NUC11PABi7 M68262-501       | Mini pc     | [39f954742c](https://linux-hardware.org/?probe=39f954742c) | Jul 21, 2023 |
| Intel         | DQ57TM AAE70931-402         | Desktop     | [01621f8578](https://linux-hardware.org/?probe=01621f8578) | Jul 21, 2023 |
| Gigabyte      | 945GCMX-S2                  | Desktop     | [46e297492f](https://linux-hardware.org/?probe=46e297492f) | Jul 21, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [fa4def4ece](https://linux-hardware.org/?probe=fa4def4ece) | Jul 21, 2023 |
| Apple         | MacBookPro14,3              | Notebook    | [e24c8a224e](https://linux-hardware.org/?probe=e24c8a224e) | Jul 21, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [044cf93e31](https://linux-hardware.org/?probe=044cf93e31) | Jul 20, 2023 |
| Toshiba       | Satellite L750              | Notebook    | [662f89dcc3](https://linux-hardware.org/?probe=662f89dcc3) | Jul 20, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [3da3da07e9](https://linux-hardware.org/?probe=3da3da07e9) | Jul 19, 2023 |
| ASUSTek       | ROG Maximus XII EXTREME     | Desktop     | [0f7fea54eb](https://linux-hardware.org/?probe=0f7fea54eb) | Jul 19, 2023 |
| Dell          | Latitude 5330               | Convertible | [45ca5a9872](https://linux-hardware.org/?probe=45ca5a9872) | Jul 19, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [572537c287](https://linux-hardware.org/?probe=572537c287) | Jul 19, 2023 |
| Microsoft     | Surface Pro 6               | Tablet      | [9a9670d446](https://linux-hardware.org/?probe=9a9670d446) | Jul 18, 2023 |
| ASUSTek       | PRIME Z370-A II             | Desktop     | [6ca4720242](https://linux-hardware.org/?probe=6ca4720242) | Jul 18, 2023 |
| ASRock        | Z77 Performance             | Notebook    | [585aaad9ad](https://linux-hardware.org/?probe=585aaad9ad) | Jul 18, 2023 |
| ASRock        | B660M-HDV                   | Desktop     | [3a0685bcf0](https://linux-hardware.org/?probe=3a0685bcf0) | Jul 18, 2023 |
| Toshiba       | Satellite L850              | Notebook    | [afdd53cd2f](https://linux-hardware.org/?probe=afdd53cd2f) | Jul 18, 2023 |
| Toshiba       | Satellite L850              | Notebook    | [23c31a7c87](https://linux-hardware.org/?probe=23c31a7c87) | Jul 17, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [553cbdb79d](https://linux-hardware.org/?probe=553cbdb79d) | Jul 17, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [60d7a077dc](https://linux-hardware.org/?probe=60d7a077dc) | Jul 17, 2023 |
| SONIQ Digi... | Soniq 11.6inch Convertib... | Convertible | [8e01cf8f1e](https://linux-hardware.org/?probe=8e01cf8f1e) | Jul 17, 2023 |
| Lenovo        | ThinkPad L390 Yoga 20NUS... | Convertible | [c9f052e7ff](https://linux-hardware.org/?probe=c9f052e7ff) | Jul 16, 2023 |
| Lenovo        | ThinkPad X13s Gen 1 21BY... | Notebook    | [1a0f8c842b](https://linux-hardware.org/?probe=1a0f8c842b) | Jul 16, 2023 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | Desktop     | [20ee7f8016](https://linux-hardware.org/?probe=20ee7f8016) | Jul 16, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [5bf40815d5](https://linux-hardware.org/?probe=5bf40815d5) | Jul 16, 2023 |
| Gigabyte      | Z490 AORUS PRO AX           | Desktop     | [1b32b611bf](https://linux-hardware.org/?probe=1b32b611bf) | Jul 16, 2023 |
| Acer          | TravelMate Spin B118-R      | Convertible | [c0ad7a539d](https://linux-hardware.org/?probe=c0ad7a539d) | Jul 15, 2023 |
| Dell          | G5 5505                     | Notebook    | [ba144013b3](https://linux-hardware.org/?probe=ba144013b3) | Jul 15, 2023 |
| ASUSTek       | X99-DELUXE II               | Desktop     | [d132761a85](https://linux-hardware.org/?probe=d132761a85) | Jul 14, 2023 |
| ASUSTek       | X99-DELUXE II               | Desktop     | [70345fff08](https://linux-hardware.org/?probe=70345fff08) | Jul 14, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [8ee665fb8f](https://linux-hardware.org/?probe=8ee665fb8f) | Jul 14, 2023 |
| Gigabyte      | GA-A55M-S2V                 | Desktop     | [fadd5eeba6](https://linux-hardware.org/?probe=fadd5eeba6) | Jul 13, 2023 |
| Dell          | 03NVJ6 A01                  | Desktop     | [b575153979](https://linux-hardware.org/?probe=b575153979) | Jul 13, 2023 |
| Dell          | 03NVJ6 A01                  | Desktop     | [05e8a2652e](https://linux-hardware.org/?probe=05e8a2652e) | Jul 13, 2023 |
| MSI           | Stealth 16Studio A13VG      | Notebook    | [ab3683571a](https://linux-hardware.org/?probe=ab3683571a) | Jul 13, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [706f24ffe5](https://linux-hardware.org/?probe=706f24ffe5) | Jul 12, 2023 |
| ASUSTek       | Zephyrus M GM501GM          | Notebook    | [72454f0f8e](https://linux-hardware.org/?probe=72454f0f8e) | Jul 11, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [5c12592f23](https://linux-hardware.org/?probe=5c12592f23) | Jul 11, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [38f91b870c](https://linux-hardware.org/?probe=38f91b870c) | Jul 11, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [e0c7ec0cbc](https://linux-hardware.org/?probe=e0c7ec0cbc) | Jul 11, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [e2023d0c6d](https://linux-hardware.org/?probe=e2023d0c6d) | Jul 11, 2023 |
| Inventec      | 0W63N3 A01                  | Mini pc     | [02a820f6b2](https://linux-hardware.org/?probe=02a820f6b2) | Jul 11, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [a9e19d3887](https://linux-hardware.org/?probe=a9e19d3887) | Jul 11, 2023 |
| MSI           | PRO H610M-G DDR4            | Desktop     | [4ff789de3b](https://linux-hardware.org/?probe=4ff789de3b) | Jul 11, 2023 |
| HP            | 250 G2                      | Notebook    | [7fd1832150](https://linux-hardware.org/?probe=7fd1832150) | Jul 11, 2023 |
| HP            | 250 G2                      | Notebook    | [738b04c947](https://linux-hardware.org/?probe=738b04c947) | Jul 11, 2023 |
| ASUSTek       | ZenBook UX431FA             | Notebook    | [09edc8f932](https://linux-hardware.org/?probe=09edc8f932) | Jul 11, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [ac8df9628d](https://linux-hardware.org/?probe=ac8df9628d) | Jul 10, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [f4f002c37a](https://linux-hardware.org/?probe=f4f002c37a) | Jul 10, 2023 |
| MSI           | MPG B650I EDGE WIFI         | Desktop     | [dcf418007d](https://linux-hardware.org/?probe=dcf418007d) | Jul 10, 2023 |
| MSI           | MPG B650I EDGE WIFI         | Desktop     | [b515a2980e](https://linux-hardware.org/?probe=b515a2980e) | Jul 10, 2023 |
| Avalue        | NUC-APL E9697JAI006R        | Desktop     | [8e289dc3f9](https://linux-hardware.org/?probe=8e289dc3f9) | Jul 10, 2023 |
| Avalue        | NUC-APL E9697JAI006R        | Desktop     | [8f7a02d8b5](https://linux-hardware.org/?probe=8f7a02d8b5) | Jul 10, 2023 |
| Acer          | ConceptD CN315-71P          | Notebook    | [a211dd78de](https://linux-hardware.org/?probe=a211dd78de) | Jul 09, 2023 |
| Gigabyte      | X570S AORUS ELITE           | Desktop     | [6381f6da84](https://linux-hardware.org/?probe=6381f6da84) | Jul 09, 2023 |
| Toshiba       | PORTEGE Z30-C               | Notebook    | [f9d1d19d05](https://linux-hardware.org/?probe=f9d1d19d05) | Jul 09, 2023 |
| MSI           | Stealth 16Studio A13VG      | Notebook    | [e16527e244](https://linux-hardware.org/?probe=e16527e244) | Jul 09, 2023 |
| HP            | 1791                        | Desktop     | [a2bf914a45](https://linux-hardware.org/?probe=a2bf914a45) | Jul 08, 2023 |
| ASRock        | X670E Pro RS                | Desktop     | [d41838c540](https://linux-hardware.org/?probe=d41838c540) | Jul 08, 2023 |
| Gigabyte      | GA-A55M-S2V                 | Desktop     | [6cac69cac1](https://linux-hardware.org/?probe=6cac69cac1) | Jul 08, 2023 |
| Acer          | Aspire One 753              | Notebook    | [f47888ce55](https://linux-hardware.org/?probe=f47888ce55) | Jul 08, 2023 |
| Acer          | Aspire One 753              | Notebook    | [9f56cc566d](https://linux-hardware.org/?probe=9f56cc566d) | Jul 08, 2023 |
| MSI           | MPG B650I EDGE WIFI         | Desktop     | [bdaa09e52c](https://linux-hardware.org/?probe=bdaa09e52c) | Jul 08, 2023 |
| Dell          | 09D2HH A00                  | Desktop     | [2885be7e12](https://linux-hardware.org/?probe=2885be7e12) | Jul 07, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [0d98ce8578](https://linux-hardware.org/?probe=0d98ce8578) | Jul 07, 2023 |
| MSI           | Z97S SLI Krait Edition      | Desktop     | [c353b62b15](https://linux-hardware.org/?probe=c353b62b15) | Jul 07, 2023 |
| MSI           | MS-7142                     | Desktop     | [3247a2f71c](https://linux-hardware.org/?probe=3247a2f71c) | Jul 06, 2023 |
| MSI           | B150 GAMING M3              | Desktop     | [a8018be55a](https://linux-hardware.org/?probe=a8018be55a) | Jul 06, 2023 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [3af1e33a01](https://linux-hardware.org/?probe=3af1e33a01) | Jul 06, 2023 |
| Toshiba       | PORTEGE X30-E               | Notebook    | [d68e9cd764](https://linux-hardware.org/?probe=d68e9cd764) | Jul 06, 2023 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [04d7534d9e](https://linux-hardware.org/?probe=04d7534d9e) | Jul 06, 2023 |
| ASUSTek       | G750JZA                     | Notebook    | [fb2477dd61](https://linux-hardware.org/?probe=fb2477dd61) | Jul 06, 2023 |
| MSI           | Z97 PC Mate                 | Desktop     | [495b6e6e4a](https://linux-hardware.org/?probe=495b6e6e4a) | Jul 06, 2023 |
| HP            | ProBook 4540s               | Notebook    | [cccf56865c](https://linux-hardware.org/?probe=cccf56865c) | Jul 06, 2023 |
| Acer          | TravelMate 8572T            | Notebook    | [67f4a2af7e](https://linux-hardware.org/?probe=67f4a2af7e) | Jul 05, 2023 |
| MSI           | Z97 PC Mate                 | Desktop     | [0d9ce2b3d2](https://linux-hardware.org/?probe=0d9ce2b3d2) | Jul 05, 2023 |
| Lenovo        | ThinkPad P50 20EQS48H00     | Notebook    | [7f64164b64](https://linux-hardware.org/?probe=7f64164b64) | Jul 04, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [407e00921f](https://linux-hardware.org/?probe=407e00921f) | Jul 04, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [da0ca66579](https://linux-hardware.org/?probe=da0ca66579) | Jul 04, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [f7a7db0702](https://linux-hardware.org/?probe=f7a7db0702) | Jul 04, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [464ff62eaf](https://linux-hardware.org/?probe=464ff62eaf) | Jul 04, 2023 |
| ASUSTek       | G750JZA                     | Notebook    | [72fc73822c](https://linux-hardware.org/?probe=72fc73822c) | Jul 04, 2023 |
| Dell          | Latitude 5420               | Notebook    | [dedd6c842c](https://linux-hardware.org/?probe=dedd6c842c) | Jul 04, 2023 |
| Dell          | Latitude 5420               | Notebook    | [dfe3274d7e](https://linux-hardware.org/?probe=dfe3274d7e) | Jul 03, 2023 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | Notebook    | [4586b855ca](https://linux-hardware.org/?probe=4586b855ca) | Jul 02, 2023 |
| Dell          | 0TY565                      | Desktop     | [98f290cadd](https://linux-hardware.org/?probe=98f290cadd) | Jul 02, 2023 |
| Gigabyte      | Q2532N                      | Notebook    | [4560685060](https://linux-hardware.org/?probe=4560685060) | Jul 02, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [b6b1cf5b68](https://linux-hardware.org/?probe=b6b1cf5b68) | Jul 02, 2023 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [49c764507c](https://linux-hardware.org/?probe=49c764507c) | Jul 01, 2023 |
| Gigabyte      | P67A-UD5-B3                 | Desktop     | [b763c860fa](https://linux-hardware.org/?probe=b763c860fa) | Jun 30, 2023 |
| Acer          | TravelMate 8572T            | Notebook    | [a73fd92e21](https://linux-hardware.org/?probe=a73fd92e21) | Jun 30, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [593512053f](https://linux-hardware.org/?probe=593512053f) | Jun 30, 2023 |
| Gigabyte      | H170-HD3-CF                 | Desktop     | [59d1be1c5d](https://linux-hardware.org/?probe=59d1be1c5d) | Jun 30, 2023 |
| ASRock        | Z690 Steel Legend WiFi 6... | Desktop     | [d09ee66df1](https://linux-hardware.org/?probe=d09ee66df1) | Jun 29, 2023 |
| ASRock        | Z77 Performance             | Notebook    | [a678dc9605](https://linux-hardware.org/?probe=a678dc9605) | Jun 29, 2023 |
| Acer          | TravelMate B113             | Notebook    | [04738ce824](https://linux-hardware.org/?probe=04738ce824) | Jun 29, 2023 |
| Acer          | TravelMate B113             | Notebook    | [9cfe4d5036](https://linux-hardware.org/?probe=9cfe4d5036) | Jun 29, 2023 |
| Unknown       | Unknown                     | Notebook    | [d358089f32](https://linux-hardware.org/?probe=d358089f32) | Jun 29, 2023 |
| Acer          | Aspire xxxx                 | Notebook    | [67e8606837](https://linux-hardware.org/?probe=67e8606837) | Jun 29, 2023 |
| HP            | Pavilion dv6                | Notebook    | [7fe9e439c0](https://linux-hardware.org/?probe=7fe9e439c0) | Jun 28, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [ba0db6c3e9](https://linux-hardware.org/?probe=ba0db6c3e9) | Jun 28, 2023 |
| ASUSTek       | ZenBook Pro 15 UX550GEX_... | Notebook    | [56eef68e89](https://linux-hardware.org/?probe=56eef68e89) | Jun 28, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [f4540c6370](https://linux-hardware.org/?probe=f4540c6370) | Jun 27, 2023 |
| Intel         | LADPNVMO AAE76523-300       | Desktop     | [76cc7bbb86](https://linux-hardware.org/?probe=76cc7bbb86) | Jun 27, 2023 |
| Lenovo        | ThinkPad X230 2325CW1       | Notebook    | [70cbf738e8](https://linux-hardware.org/?probe=70cbf738e8) | Jun 27, 2023 |
| ASRock        | X370 Gaming-ITX/ac          | Desktop     | [975e5164c6](https://linux-hardware.org/?probe=975e5164c6) | Jun 27, 2023 |
| Leader        | SC8-PRO                     | Stick pc    | [ad54f075f6](https://linux-hardware.org/?probe=ad54f075f6) | Jun 26, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [06a581d65d](https://linux-hardware.org/?probe=06a581d65d) | Jun 25, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [a105b6264f](https://linux-hardware.org/?probe=a105b6264f) | Jun 25, 2023 |
| Toshiba       | Satellite L550              | Notebook    | [321ec36f85](https://linux-hardware.org/?probe=321ec36f85) | Jun 25, 2023 |
| ASUSTek       | X550LA                      | Notebook    | [225516996c](https://linux-hardware.org/?probe=225516996c) | Jun 25, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [79979ceac7](https://linux-hardware.org/?probe=79979ceac7) | Jun 25, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [ac084eba06](https://linux-hardware.org/?probe=ac084eba06) | Jun 24, 2023 |
| Acer          | Aspire A315-22              | Notebook    | [5e2e395efd](https://linux-hardware.org/?probe=5e2e395efd) | Jun 24, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [54d0d54490](https://linux-hardware.org/?probe=54d0d54490) | Jun 24, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [2b61a56610](https://linux-hardware.org/?probe=2b61a56610) | Jun 24, 2023 |
| System76      | Oryx Pro                    | Notebook    | [eaa4d8e105](https://linux-hardware.org/?probe=eaa4d8e105) | Jun 24, 2023 |
| ASUSTek       | X550LC                      | Notebook    | [30369c12e1](https://linux-hardware.org/?probe=30369c12e1) | Jun 24, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [a3a840a283](https://linux-hardware.org/?probe=a3a840a283) | Jun 23, 2023 |
| Lenovo        | ThinkPad T460s 20FAS0NF0... | Notebook    | [f2e368a70d](https://linux-hardware.org/?probe=f2e368a70d) | Jun 23, 2023 |
| ASRock        | B365M Pro4-F                | Desktop     | [16a5102512](https://linux-hardware.org/?probe=16a5102512) | Jun 23, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [efc582d761](https://linux-hardware.org/?probe=efc582d761) | Jun 23, 2023 |
| HP            | Pavilion dv6                | Notebook    | [fa9045c36f](https://linux-hardware.org/?probe=fa9045c36f) | Jun 22, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [d3a63bb6aa](https://linux-hardware.org/?probe=d3a63bb6aa) | Jun 22, 2023 |
| Lenovo        | 30C0 SDK0J40697 WIN 3305... | Desktop     | [8c4bd347a7](https://linux-hardware.org/?probe=8c4bd347a7) | Jun 21, 2023 |
| HP            | 1588h                       | Desktop     | [abe5412cf6](https://linux-hardware.org/?probe=abe5412cf6) | Jun 21, 2023 |
| HP            | 1588h                       | Desktop     | [f08e230cd3](https://linux-hardware.org/?probe=f08e230cd3) | Jun 21, 2023 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [4131c0a5bb](https://linux-hardware.org/?probe=4131c0a5bb) | Jun 20, 2023 |
| ASUSTek       | X550LA                      | Notebook    | [9b58f1abd3](https://linux-hardware.org/?probe=9b58f1abd3) | Jun 20, 2023 |
| Microsoft     | Surface Laptop              | Tablet      | [401cb6a1f1](https://linux-hardware.org/?probe=401cb6a1f1) | Jun 20, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [c1aac2f0a4](https://linux-hardware.org/?probe=c1aac2f0a4) | Jun 19, 2023 |
| IBM           | FAB2 Controller Producti... | Server      | [daa3df0f31](https://linux-hardware.org/?probe=daa3df0f31) | Jun 19, 2023 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [e5740353af](https://linux-hardware.org/?probe=e5740353af) | Jun 19, 2023 |
| COM1          | NBINF-X5-9G5                | Notebook    | [fe2f1cfef6](https://linux-hardware.org/?probe=fe2f1cfef6) | Jun 19, 2023 |
| HP            | EliteBook 8760w             | Notebook    | [ac41230354](https://linux-hardware.org/?probe=ac41230354) | Jun 18, 2023 |
| Microsoft     | Surface Go                  | Tablet      | [f266551c9d](https://linux-hardware.org/?probe=f266551c9d) | Jun 18, 2023 |
| Dell          | 06NWYK A00                  | Desktop     | [5e065b17cf](https://linux-hardware.org/?probe=5e065b17cf) | Jun 18, 2023 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [fdbe50b1d6](https://linux-hardware.org/?probe=fdbe50b1d6) | Jun 18, 2023 |
| Gigabyte      | Z690 AORUS PRO              | Desktop     | [e9dd574827](https://linux-hardware.org/?probe=e9dd574827) | Jun 18, 2023 |
| Dell          | Latitude E7440              | Notebook    | [60d14fe6ab](https://linux-hardware.org/?probe=60d14fe6ab) | Jun 18, 2023 |
| Alienware     | M14xR2                      | Notebook    | [2eb0cc2d0e](https://linux-hardware.org/?probe=2eb0cc2d0e) | Jun 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [26b4c05332](https://linux-hardware.org/?probe=26b4c05332) | Jun 17, 2023 |
| Intel         | NUC12WSBi5 M46425-302       | Mini pc     | [79c0cd0257](https://linux-hardware.org/?probe=79c0cd0257) | Jun 17, 2023 |
| Apple         | Mac-F2238AC8                | All in one  | [7d9f25dc5f](https://linux-hardware.org/?probe=7d9f25dc5f) | Jun 17, 2023 |
| Acer          | Aspire A315-510P            | Notebook    | [d1be914db1](https://linux-hardware.org/?probe=d1be914db1) | Jun 17, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [852d16ee14](https://linux-hardware.org/?probe=852d16ee14) | Jun 16, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [b7faea4be3](https://linux-hardware.org/?probe=b7faea4be3) | Jun 16, 2023 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [29ff056f4a](https://linux-hardware.org/?probe=29ff056f4a) | Jun 16, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | Notebook    | [99cc4bf84b](https://linux-hardware.org/?probe=99cc4bf84b) | Jun 16, 2023 |
| HP            | Pavilion dv6                | Notebook    | [55c83ec890](https://linux-hardware.org/?probe=55c83ec890) | Jun 15, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | Notebook    | [f7049b2256](https://linux-hardware.org/?probe=f7049b2256) | Jun 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [613aa12940](https://linux-hardware.org/?probe=613aa12940) | Jun 14, 2023 |
| Dell          | Inspiron M5010              | Notebook    | [33541731e3](https://linux-hardware.org/?probe=33541731e3) | Jun 14, 2023 |
| Gigabyte      | D525TUD                     | Desktop     | [2d854be38a](https://linux-hardware.org/?probe=2d854be38a) | Jun 14, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [993f00eca6](https://linux-hardware.org/?probe=993f00eca6) | Jun 14, 2023 |
| Gigabyte      | D525TUD                     | Desktop     | [be2c796ab2](https://linux-hardware.org/?probe=be2c796ab2) | Jun 13, 2023 |
| ASRock        | X570 Phantom Gaming-ITX/... | Desktop     | [7689518326](https://linux-hardware.org/?probe=7689518326) | Jun 13, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [b2eb89c4fd](https://linux-hardware.org/?probe=b2eb89c4fd) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M58 7360PL9     | Desktop     | [da837e8612](https://linux-hardware.org/?probe=da837e8612) | Jun 13, 2023 |
| Seco          | C40 C                       | Desktop     | [37b8e950d0](https://linux-hardware.org/?probe=37b8e950d0) | Jun 12, 2023 |
| ASRock        | X570 Phantom Gaming-ITX/... | Desktop     | [e68b78c037](https://linux-hardware.org/?probe=e68b78c037) | Jun 12, 2023 |
| ASRock        | Z690 Steel Legend WiFi 6... | Desktop     | [0190531869](https://linux-hardware.org/?probe=0190531869) | Jun 12, 2023 |
| ASRock        | Z690 Steel Legend WiFi 6... | Desktop     | [648161a6ff](https://linux-hardware.org/?probe=648161a6ff) | Jun 12, 2023 |
| Acer          | Aspire A315-510P            | Notebook    | [705ad3c316](https://linux-hardware.org/?probe=705ad3c316) | Jun 12, 2023 |
| NEC Comput... | VERSA P91 series            | Notebook    | [7a4183e095](https://linux-hardware.org/?probe=7a4183e095) | Jun 12, 2023 |
| NEC Comput... | VERSA P91 series            | Notebook    | [2051db7014](https://linux-hardware.org/?probe=2051db7014) | Jun 12, 2023 |
| BESSTAR Te... | B550                        | Desktop     | [b74cc9dfff](https://linux-hardware.org/?probe=b74cc9dfff) | Jun 11, 2023 |
| COM1          | NBINF-X5-9G5                | Notebook    | [755841cee1](https://linux-hardware.org/?probe=755841cee1) | Jun 11, 2023 |
| Pegatron      | 2ACB                        | Desktop     | [61e759f7db](https://linux-hardware.org/?probe=61e759f7db) | Jun 11, 2023 |
| MSI           | GS60 6QE                    | Notebook    | [e04ff9df40](https://linux-hardware.org/?probe=e04ff9df40) | Jun 10, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [b599a55609](https://linux-hardware.org/?probe=b599a55609) | Jun 10, 2023 |
| Dell          | 0N4YC8 A00                  | Desktop     | [bc832400b4](https://linux-hardware.org/?probe=bc832400b4) | Jun 10, 2023 |
| Toshiba       | PORTEGE Z10t-A              | Notebook    | [4a0712b322](https://linux-hardware.org/?probe=4a0712b322) | Jun 10, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [5d21e64704](https://linux-hardware.org/?probe=5d21e64704) | Jun 10, 2023 |
| IT Channel... | N8xEJEK                     | Notebook    | [51a7e3f5b4](https://linux-hardware.org/?probe=51a7e3f5b4) | Jun 10, 2023 |
| ASRock        | X570 Phantom Gaming X       | Desktop     | [0c4db9b922](https://linux-hardware.org/?probe=0c4db9b922) | Jun 10, 2023 |
| IBM           | FAB2 Controller Producti... | Server      | [af396cb333](https://linux-hardware.org/?probe=af396cb333) | Jun 10, 2023 |
| Dell          | 0XCR8D A03                  | Desktop     | [e37bceb6fb](https://linux-hardware.org/?probe=e37bceb6fb) | Jun 09, 2023 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [f02bc23dd0](https://linux-hardware.org/?probe=f02bc23dd0) | Jun 09, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [8ab2ec8df4](https://linux-hardware.org/?probe=8ab2ec8df4) | Jun 09, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [c96be9f4cd](https://linux-hardware.org/?probe=c96be9f4cd) | Jun 08, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [65e06561cf](https://linux-hardware.org/?probe=65e06561cf) | Jun 08, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [e1fdfde650](https://linux-hardware.org/?probe=e1fdfde650) | Jun 08, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [9ea0a82205](https://linux-hardware.org/?probe=9ea0a82205) | Jun 07, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [1c8078b748](https://linux-hardware.org/?probe=1c8078b748) | Jun 07, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | Notebook    | [ee9c6252ae](https://linux-hardware.org/?probe=ee9c6252ae) | Jun 07, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [646e1db08d](https://linux-hardware.org/?probe=646e1db08d) | Jun 07, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [b0435761df](https://linux-hardware.org/?probe=b0435761df) | Jun 07, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [a76212cc40](https://linux-hardware.org/?probe=a76212cc40) | Jun 07, 2023 |
| Apple         | MacBookAir4,2               | Notebook    | [afc9f50009](https://linux-hardware.org/?probe=afc9f50009) | Jun 05, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [3a1c1daa3d](https://linux-hardware.org/?probe=3a1c1daa3d) | Jun 05, 2023 |
| HP            | 83E2                        | Desktop     | [522273fe60](https://linux-hardware.org/?probe=522273fe60) | Jun 05, 2023 |
| HP            | 83E2                        | Desktop     | [3684f8562d](https://linux-hardware.org/?probe=3684f8562d) | Jun 04, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [88fbd57dac](https://linux-hardware.org/?probe=88fbd57dac) | Jun 04, 2023 |
| Dell          | 0Y5DDC A00                  | Desktop     | [5713168678](https://linux-hardware.org/?probe=5713168678) | Jun 04, 2023 |
| ASUSTek       | ROG STRIX B360-I GAMING     | Desktop     | [0c8afa948b](https://linux-hardware.org/?probe=0c8afa948b) | Jun 04, 2023 |
| MSI           | GS60 6QE                    | Notebook    | [65ea70f7fa](https://linux-hardware.org/?probe=65ea70f7fa) | Jun 03, 2023 |
| Lenovo        | ThinkStation D30 42234T7    | Desktop     | [18cb6a946b](https://linux-hardware.org/?probe=18cb6a946b) | Jun 03, 2023 |
| Acer          | TravelMate 8572T            | Notebook    | [46920007ed](https://linux-hardware.org/?probe=46920007ed) | Jun 03, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [8e46a969c7](https://linux-hardware.org/?probe=8e46a969c7) | Jun 03, 2023 |
| Intel         | DB85FL AAG89861-202         | Desktop     | [8ededa47e6](https://linux-hardware.org/?probe=8ededa47e6) | Jun 02, 2023 |
| Intel         | DB85FL AAG89861-202         | Desktop     | [7bd893ebe1](https://linux-hardware.org/?probe=7bd893ebe1) | Jun 02, 2023 |
| Toshiba       | Satellite P870              | Notebook    | [559a48c91b](https://linux-hardware.org/?probe=559a48c91b) | Jun 01, 2023 |
| Supermicro    | X11SCD-F                    | Desktop     | [4646e2fe85](https://linux-hardware.org/?probe=4646e2fe85) | Jun 01, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [0e89db7255](https://linux-hardware.org/?probe=0e89db7255) | Jun 01, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [6d7803788d](https://linux-hardware.org/?probe=6d7803788d) | Jun 01, 2023 |
| Dell          | 03NVJ6 A00                  | Desktop     | [1f295f3ec2](https://linux-hardware.org/?probe=1f295f3ec2) | Jun 01, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX DDR4    | Desktop     | [5f1045564e](https://linux-hardware.org/?probe=5f1045564e) | Jun 01, 2023 |
| Intel Clie... | LAPRC710                    | Notebook    | [ef0d589f75](https://linux-hardware.org/?probe=ef0d589f75) | May 31, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [1383313bbb](https://linux-hardware.org/?probe=1383313bbb) | May 31, 2023 |
| Gigabyte      | H270-HD3-CF                 | Desktop     | [d2912dfb69](https://linux-hardware.org/?probe=d2912dfb69) | May 31, 2023 |
| Acer          | Predator G9-793             | Notebook    | [26ea66d872](https://linux-hardware.org/?probe=26ea66d872) | May 31, 2023 |
| HP            | 8648                        | Desktop     | [11e777087a](https://linux-hardware.org/?probe=11e777087a) | May 31, 2023 |
| Acer          | E5-551G-871W                | Notebook    | [8034a1ee0b](https://linux-hardware.org/?probe=8034a1ee0b) | May 30, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [c75d4298dc](https://linux-hardware.org/?probe=c75d4298dc) | May 30, 2023 |
| Toshiba       | Satellite C665              | Notebook    | [c6149a6430](https://linux-hardware.org/?probe=c6149a6430) | May 30, 2023 |
| ASRock        | AB350M Pro4                 | Desktop     | [4f23de2827](https://linux-hardware.org/?probe=4f23de2827) | May 30, 2023 |
| HP            | EliteBook x360 1030 G3      | Convertible | [f762140894](https://linux-hardware.org/?probe=f762140894) | May 30, 2023 |
| Toshiba       | Satellite P870              | Notebook    | [2b57ca6d62](https://linux-hardware.org/?probe=2b57ca6d62) | May 29, 2023 |
| Valve         | Jupiter                     | Notebook    | [e6e97426e3](https://linux-hardware.org/?probe=e6e97426e3) | May 29, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [528f7440b7](https://linux-hardware.org/?probe=528f7440b7) | May 29, 2023 |
| HP            | 83E2                        | Desktop     | [0db8dcbc23](https://linux-hardware.org/?probe=0db8dcbc23) | May 28, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [c256cd6942](https://linux-hardware.org/?probe=c256cd6942) | May 28, 2023 |
| Apple         | MacBookPro10,2              | Notebook    | [34d96aa1df](https://linux-hardware.org/?probe=34d96aa1df) | May 28, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [3c001962b0](https://linux-hardware.org/?probe=3c001962b0) | May 28, 2023 |
| Lenovo        | IdeaPad 3 14ABA7 82RM       | Notebook    | [d83ee3fda2](https://linux-hardware.org/?probe=d83ee3fda2) | May 28, 2023 |
| HP            | 83E2                        | Desktop     | [6eea8879ca](https://linux-hardware.org/?probe=6eea8879ca) | May 28, 2023 |
| ASUSTek       | ROG STRIX X399-E GAMING     | Desktop     | [4f1ff269d2](https://linux-hardware.org/?probe=4f1ff269d2) | May 28, 2023 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [5a39bd1d78](https://linux-hardware.org/?probe=5a39bd1d78) | May 28, 2023 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [a36d2b541a](https://linux-hardware.org/?probe=a36d2b541a) | May 28, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [0ff9159d89](https://linux-hardware.org/?probe=0ff9159d89) | May 27, 2023 |
| Acer          | Aspire A315-22              | Notebook    | [18a13174aa](https://linux-hardware.org/?probe=18a13174aa) | May 27, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [9cb2973f2f](https://linux-hardware.org/?probe=9cb2973f2f) | May 27, 2023 |
| HP            | 81B9 1000                   | All in one  | [55380f30ca](https://linux-hardware.org/?probe=55380f30ca) | May 27, 2023 |
| Lenovo        | ThinkPad W541 20EGS1AR00    | Notebook    | [b7f46e7180](https://linux-hardware.org/?probe=b7f46e7180) | May 27, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [2cea143017](https://linux-hardware.org/?probe=2cea143017) | May 26, 2023 |
| Dell          | Latitude 5430               | Notebook    | [e8b9199229](https://linux-hardware.org/?probe=e8b9199229) | May 26, 2023 |
| ASUSTek       | G20AJ                       | Desktop     | [92223e639f](https://linux-hardware.org/?probe=92223e639f) | May 26, 2023 |
| ASUSTek       | G20AJ                       | Desktop     | [9a58438669](https://linux-hardware.org/?probe=9a58438669) | May 26, 2023 |
| Apple         | Mac-7BA5B2794B2CDB12 Mac... | Mini pc     | [a3456d6048](https://linux-hardware.org/?probe=a3456d6048) | May 26, 2023 |
| Lenovo        | ThinkPad W541 20EGS1AR00    | Notebook    | [a5301f505d](https://linux-hardware.org/?probe=a5301f505d) | May 25, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [f0c2fede02](https://linux-hardware.org/?probe=f0c2fede02) | May 25, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [a167562cba](https://linux-hardware.org/?probe=a167562cba) | May 25, 2023 |
| Intel         | NUC11DBBi9 M17026-403       | Mini pc     | [61970448fa](https://linux-hardware.org/?probe=61970448fa) | May 24, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [585b85e476](https://linux-hardware.org/?probe=585b85e476) | May 23, 2023 |
| Dell          | Latitude 7280               | Notebook    | [215bef2144](https://linux-hardware.org/?probe=215bef2144) | May 23, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [ca5f5ee7bf](https://linux-hardware.org/?probe=ca5f5ee7bf) | May 23, 2023 |
| MSI           | X99A GAMING 7               | Desktop     | [ec94d173a7](https://linux-hardware.org/?probe=ec94d173a7) | May 23, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [dfb369a8d2](https://linux-hardware.org/?probe=dfb369a8d2) | May 22, 2023 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [e110548f6e](https://linux-hardware.org/?probe=e110548f6e) | May 22, 2023 |
| Lenovo        | ThinkCentre M58p 7220A72    | Desktop     | [c2965aff69](https://linux-hardware.org/?probe=c2965aff69) | May 22, 2023 |
| COM1          | NBINF-X5-9G5                | Notebook    | [33aa60eaa2](https://linux-hardware.org/?probe=33aa60eaa2) | May 22, 2023 |
| COM1          | NBINF-X5-9G5                | Notebook    | [8d8c13c10c](https://linux-hardware.org/?probe=8d8c13c10c) | May 22, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [b0fac119c2](https://linux-hardware.org/?probe=b0fac119c2) | May 22, 2023 |
| Microsoft     | Surface Go 3                | Tablet      | [83e639f8e7](https://linux-hardware.org/?probe=83e639f8e7) | May 22, 2023 |
| Microsoft     | Surface Go 3                | Tablet      | [749e013179](https://linux-hardware.org/?probe=749e013179) | May 21, 2023 |
| ASUSTek       | K56CA                       | Notebook    | [6ae76c1553](https://linux-hardware.org/?probe=6ae76c1553) | May 21, 2023 |
| ASUSTek       | P8H77-M LE                  | Desktop     | [e9b749f2ba](https://linux-hardware.org/?probe=e9b749f2ba) | May 21, 2023 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [8dcb326301](https://linux-hardware.org/?probe=8dcb326301) | May 21, 2023 |
| ASUSTek       | P5B                         | Desktop     | [3effc437bb](https://linux-hardware.org/?probe=3effc437bb) | May 20, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [b59b0160fb](https://linux-hardware.org/?probe=b59b0160fb) | May 19, 2023 |
| Dell          | Inspiron 7586               | Convertible | [f4aaec3fda](https://linux-hardware.org/?probe=f4aaec3fda) | May 19, 2023 |
| MSI           | VR601                       | Notebook    | [7f9381407d](https://linux-hardware.org/?probe=7f9381407d) | May 19, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [4a9869b7a6](https://linux-hardware.org/?probe=4a9869b7a6) | May 19, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [337509e694](https://linux-hardware.org/?probe=337509e694) | May 19, 2023 |
| ASRock        | Z390 Phantom Gaming 9       | Desktop     | [5ca1acbf9b](https://linux-hardware.org/?probe=5ca1acbf9b) | May 19, 2023 |
| Dell          | 0VNP2H A01                  | Desktop     | [6e51bd033e](https://linux-hardware.org/?probe=6e51bd033e) | May 19, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [64b9ba417c](https://linux-hardware.org/?probe=64b9ba417c) | May 19, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [5c07806ab1](https://linux-hardware.org/?probe=5c07806ab1) | May 19, 2023 |
| ASUSTek       | Zephyrus M GM501GM          | Notebook    | [bf1eed0e60](https://linux-hardware.org/?probe=bf1eed0e60) | May 18, 2023 |
| MSI           | MPG B650I EDGE WIFI         | Desktop     | [c15ff8f4c4](https://linux-hardware.org/?probe=c15ff8f4c4) | May 18, 2023 |
| HP            | Pavilion 15                 | Notebook    | [fd87e57fc3](https://linux-hardware.org/?probe=fd87e57fc3) | May 18, 2023 |
| Dell          | Vostro V131                 | Notebook    | [e20ddd5bca](https://linux-hardware.org/?probe=e20ddd5bca) | May 18, 2023 |
| Dell          | Vostro V131                 | Notebook    | [7714e1784a](https://linux-hardware.org/?probe=7714e1784a) | May 18, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [4bd367b4c7](https://linux-hardware.org/?probe=4bd367b4c7) | May 17, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [09e723be6f](https://linux-hardware.org/?probe=09e723be6f) | May 17, 2023 |
| Gigabyte      | X99-Gaming 5                | Desktop     | [81eee33114](https://linux-hardware.org/?probe=81eee33114) | May 17, 2023 |
| HP            | Notebook                    | Notebook    | [8d3bd6a690](https://linux-hardware.org/?probe=8d3bd6a690) | May 17, 2023 |
| Acer          | Predator G9-793             | Notebook    | [1739ea2f45](https://linux-hardware.org/?probe=1739ea2f45) | May 17, 2023 |
| Gigabyte      | H170-Gaming 3               | Desktop     | [ae5f06df99](https://linux-hardware.org/?probe=ae5f06df99) | May 16, 2023 |
| Google        | Sumo                        | Desktop     | [1455a81901](https://linux-hardware.org/?probe=1455a81901) | May 15, 2023 |
| MSI           | Summit E14FlipEvo A13MT     | Notebook    | [60e19220b9](https://linux-hardware.org/?probe=60e19220b9) | May 15, 2023 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [fe36fee27a](https://linux-hardware.org/?probe=fe36fee27a) | May 14, 2023 |
| ASRock        | AD2700-ITX                  | Desktop     | [fe80771d2e](https://linux-hardware.org/?probe=fe80771d2e) | May 14, 2023 |
| MSI           | MAG B560M MORTAR            | Desktop     | [1556b05d13](https://linux-hardware.org/?probe=1556b05d13) | May 14, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [07bf228811](https://linux-hardware.org/?probe=07bf228811) | May 14, 2023 |
| Acer          | Aspire ES1-531              | Notebook    | [56cdac831f](https://linux-hardware.org/?probe=56cdac831f) | May 13, 2023 |
| Gigabyte      | P34V7                       | Notebook    | [90e6e5d5d9](https://linux-hardware.org/?probe=90e6e5d5d9) | May 13, 2023 |
| Unknown       | Unknown                     | Notebook    | [3fbabd3df0](https://linux-hardware.org/?probe=3fbabd3df0) | May 11, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [393b2da4bc](https://linux-hardware.org/?probe=393b2da4bc) | May 11, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [3dc1af6df9](https://linux-hardware.org/?probe=3dc1af6df9) | May 11, 2023 |
| Acer          | Predator G9-793             | Notebook    | [95595808a8](https://linux-hardware.org/?probe=95595808a8) | May 11, 2023 |
| AOpen         | aA70Mx-VW R1.01 55DE8100... | Desktop     | [400b616f1c](https://linux-hardware.org/?probe=400b616f1c) | May 10, 2023 |
| Dell          | 03NVJ6 A02                  | Desktop     | [9f509a2647](https://linux-hardware.org/?probe=9f509a2647) | May 10, 2023 |
| Toshiba       | Satellite M60               | Notebook    | [91437556e8](https://linux-hardware.org/?probe=91437556e8) | May 09, 2023 |
| Toshiba       | Satellite M60               | Notebook    | [39b2bcd3a5](https://linux-hardware.org/?probe=39b2bcd3a5) | May 09, 2023 |
| Dell          | Inspiron N5010              | Notebook    | [5dd91a589b](https://linux-hardware.org/?probe=5dd91a589b) | May 09, 2023 |
| Lenovo        | ThinkPad 11e Yoga Gen 6 ... | Convertible | [2a7a243899](https://linux-hardware.org/?probe=2a7a243899) | May 09, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [503204d798](https://linux-hardware.org/?probe=503204d798) | May 09, 2023 |
| Lenovo        | ThinkPad 11e Yoga Gen 6 ... | Convertible | [c7a298018f](https://linux-hardware.org/?probe=c7a298018f) | May 08, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [def28849c6](https://linux-hardware.org/?probe=def28849c6) | May 08, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [f23fb5cca0](https://linux-hardware.org/?probe=f23fb5cca0) | May 08, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [36f1aa431d](https://linux-hardware.org/?probe=36f1aa431d) | May 08, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [3daf4fbc68](https://linux-hardware.org/?probe=3daf4fbc68) | May 07, 2023 |
| Lenovo        | 30C0 SDK0J40697 WIN 3305... | Desktop     | [94ab5e431c](https://linux-hardware.org/?probe=94ab5e431c) | May 07, 2023 |
| Dell          | Inspiron N5010              | Notebook    | [2a418b4e97](https://linux-hardware.org/?probe=2a418b4e97) | May 07, 2023 |
| MSI           | MAG B560M MORTAR            | Desktop     | [db1ad69341](https://linux-hardware.org/?probe=db1ad69341) | May 06, 2023 |
| Lenovo        | Mixx-700-12ISK 80QL         | Notebook    | [14bc666ec3](https://linux-hardware.org/?probe=14bc666ec3) | May 06, 2023 |
| MSI           | MAG B560M MORTAR            | Desktop     | [8c41580881](https://linux-hardware.org/?probe=8c41580881) | May 06, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [f743e9293e](https://linux-hardware.org/?probe=f743e9293e) | May 06, 2023 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [1515a37b97](https://linux-hardware.org/?probe=1515a37b97) | May 06, 2023 |
| Toshiba       | PORTEGE Z30t-A              | Notebook    | [18cc14eee0](https://linux-hardware.org/?probe=18cc14eee0) | May 05, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [fec056072d](https://linux-hardware.org/?probe=fec056072d) | May 05, 2023 |
| Gigabyte      | X99-Gaming 5                | Desktop     | [e1d1bdef81](https://linux-hardware.org/?probe=e1d1bdef81) | May 04, 2023 |
| System76      | Oryx Pro                    | Notebook    | [cae9fadc38](https://linux-hardware.org/?probe=cae9fadc38) | May 04, 2023 |
| Acer          | Predator G9-793             | Notebook    | [b3bd1a1031](https://linux-hardware.org/?probe=b3bd1a1031) | May 03, 2023 |
| Lenovo        | Yoga 510-14ISK 80S7         | Convertible | [47ff74d363](https://linux-hardware.org/?probe=47ff74d363) | May 03, 2023 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [a23cace014](https://linux-hardware.org/?probe=a23cace014) | May 02, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [3742def878](https://linux-hardware.org/?probe=3742def878) | May 02, 2023 |
| Intel Clie... | LAPRC510                    | Notebook    | [40c181b615](https://linux-hardware.org/?probe=40c181b615) | May 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [925b5748b9](https://linux-hardware.org/?probe=925b5748b9) | May 01, 2023 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [e812a255a4](https://linux-hardware.org/?probe=e812a255a4) | May 01, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [fa4e32fe2c](https://linux-hardware.org/?probe=fa4e32fe2c) | May 01, 2023 |
| ASRock        | B660M-HDV                   | Desktop     | [a137e6ab62](https://linux-hardware.org/?probe=a137e6ab62) | May 01, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [7fb1708706](https://linux-hardware.org/?probe=7fb1708706) | May 01, 2023 |
| Lenovo        | ThinkPad X260 20F5002NAU    | Notebook    | [7fcb72c132](https://linux-hardware.org/?probe=7fcb72c132) | May 01, 2023 |
| ASUSTek       | X501A1                      | Notebook    | [66b02cc148](https://linux-hardware.org/?probe=66b02cc148) | Apr 30, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [7a86bdd993](https://linux-hardware.org/?probe=7a86bdd993) | Apr 30, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [6206b317f2](https://linux-hardware.org/?probe=6206b317f2) | Apr 30, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [01311e320c](https://linux-hardware.org/?probe=01311e320c) | Apr 30, 2023 |
| MSI           | MPG B650I EDGE WIFI         | Desktop     | [eda4874295](https://linux-hardware.org/?probe=eda4874295) | Apr 30, 2023 |
| Apple         | Mac-F2208EC8                | Mini pc     | [6bad65ad2d](https://linux-hardware.org/?probe=6bad65ad2d) | Apr 29, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [081551c776](https://linux-hardware.org/?probe=081551c776) | Apr 29, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [ee288626f4](https://linux-hardware.org/?probe=ee288626f4) | Apr 29, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI D... | Desktop     | [c880b8dcdd](https://linux-hardware.org/?probe=c880b8dcdd) | Apr 29, 2023 |
| ASUSTek       | PRIME A520M-E               | Desktop     | [048fda2c60](https://linux-hardware.org/?probe=048fda2c60) | Apr 28, 2023 |
| MSI           | MPG X570S CARBON MAX WIF... | Desktop     | [d472fb0a32](https://linux-hardware.org/?probe=d472fb0a32) | Apr 28, 2023 |
| Intel         | DZ68DB AAG27985-101         | Desktop     | [b3323dcc11](https://linux-hardware.org/?probe=b3323dcc11) | Apr 28, 2023 |
| ASRock        | X470 Master SLI             | Desktop     | [cded55a936](https://linux-hardware.org/?probe=cded55a936) | Apr 28, 2023 |
| Lenovo        | ThinkPad L13 Yoga 20R6S1... | Convertible | [c01483e50f](https://linux-hardware.org/?probe=c01483e50f) | Apr 28, 2023 |
| Acer          | ConceptD CN315-71P          | Notebook    | [3cc902ff5c](https://linux-hardware.org/?probe=3cc902ff5c) | Apr 28, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | Notebook    | [73141c5006](https://linux-hardware.org/?probe=73141c5006) | Apr 27, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | Notebook    | [0cb164ac2f](https://linux-hardware.org/?probe=0cb164ac2f) | Apr 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [3f44947226](https://linux-hardware.org/?probe=3f44947226) | Apr 27, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [198fa6162e](https://linux-hardware.org/?probe=198fa6162e) | Apr 27, 2023 |
| ASUSTek       | X99-A                       | Desktop     | [6788eea8d2](https://linux-hardware.org/?probe=6788eea8d2) | Apr 26, 2023 |
| ASUSTek       | X550CA                      | Notebook    | [a63293fe36](https://linux-hardware.org/?probe=a63293fe36) | Apr 26, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [b8b51b29ef](https://linux-hardware.org/?probe=b8b51b29ef) | Apr 25, 2023 |
| Dell          | Inspiron 5548               | Notebook    | [42908a7ab7](https://linux-hardware.org/?probe=42908a7ab7) | Apr 25, 2023 |
| Dell          | System XPS L702X            | Notebook    | [d1aa167e90](https://linux-hardware.org/?probe=d1aa167e90) | Apr 25, 2023 |
| Acer          | E5-551G-871W                | Notebook    | [2730a30d89](https://linux-hardware.org/?probe=2730a30d89) | Apr 25, 2023 |
| MSI           | GE72VR 6RF                  | Notebook    | [89cb17ee72](https://linux-hardware.org/?probe=89cb17ee72) | Apr 25, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [373372bf75](https://linux-hardware.org/?probe=373372bf75) | Apr 25, 2023 |
| Dell          | 08WXMX A02                  | Desktop     | [5f68c6a285](https://linux-hardware.org/?probe=5f68c6a285) | Apr 24, 2023 |
| MSI           | Z97S SLI Krait Edition      | Desktop     | [6ed93f8338](https://linux-hardware.org/?probe=6ed93f8338) | Apr 24, 2023 |
| HP            | 0AA8h                       | Desktop     | [071191ddf3](https://linux-hardware.org/?probe=071191ddf3) | Apr 23, 2023 |
| Dell          | Precision 5520              | Notebook    | [4d1dd8b673](https://linux-hardware.org/?probe=4d1dd8b673) | Apr 23, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [ef59f5ff9b](https://linux-hardware.org/?probe=ef59f5ff9b) | Apr 23, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [5da3166132](https://linux-hardware.org/?probe=5da3166132) | Apr 22, 2023 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | Desktop     | [03a331aa44](https://linux-hardware.org/?probe=03a331aa44) | Apr 22, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [80312ab34c](https://linux-hardware.org/?probe=80312ab34c) | Apr 22, 2023 |
| Shuttle       | DS10U                       | Desktop     | [ffcce61d82](https://linux-hardware.org/?probe=ffcce61d82) | Apr 22, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [1dd1bcd00e](https://linux-hardware.org/?probe=1dd1bcd00e) | Apr 22, 2023 |
| Valve         | Jupiter                     | Notebook    | [b5be7aa6ff](https://linux-hardware.org/?probe=b5be7aa6ff) | Apr 21, 2023 |
| ASRock        | AD2700-ITX                  | Desktop     | [e688e656cd](https://linux-hardware.org/?probe=e688e656cd) | Apr 21, 2023 |
| Shuttle       | FS81                        | Desktop     | [051b7f4753](https://linux-hardware.org/?probe=051b7f4753) | Apr 20, 2023 |
| Acer          | Predator G9-793             | Notebook    | [664d6de816](https://linux-hardware.org/?probe=664d6de816) | Apr 20, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | Notebook    | [8daf9af9b5](https://linux-hardware.org/?probe=8daf9af9b5) | Apr 20, 2023 |
| Acer          | Aspire 5733Z                | Notebook    | [de205c8c62](https://linux-hardware.org/?probe=de205c8c62) | Apr 19, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [7da02a75b5](https://linux-hardware.org/?probe=7da02a75b5) | Apr 18, 2023 |
| ASRock        | Z170 Gaming K4              | Desktop     | [cbd09f0f67](https://linux-hardware.org/?probe=cbd09f0f67) | Apr 18, 2023 |
| Shuttle       | DS10U                       | Desktop     | [b25013d04f](https://linux-hardware.org/?probe=b25013d04f) | Apr 18, 2023 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [07a49303af](https://linux-hardware.org/?probe=07a49303af) | Apr 17, 2023 |
| Toshiba       | Satellite E45-B             | Notebook    | [ec0bb6bfc6](https://linux-hardware.org/?probe=ec0bb6bfc6) | Apr 17, 2023 |
| MSI           | MS-B0A41                    | Desktop     | [5950f6e73c](https://linux-hardware.org/?probe=5950f6e73c) | Apr 17, 2023 |
| Dell          | Inspiron 13-5378            | Notebook    | [bcb18ae818](https://linux-hardware.org/?probe=bcb18ae818) | Apr 17, 2023 |
| HP            | Pavilion dv6                | Notebook    | [fc41269cf8](https://linux-hardware.org/?probe=fc41269cf8) | Apr 16, 2023 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [1fa07cd218](https://linux-hardware.org/?probe=1fa07cd218) | Apr 16, 2023 |
| HP            | 212B                        | Desktop     | [343f1f5eba](https://linux-hardware.org/?probe=343f1f5eba) | Apr 16, 2023 |
| Dell          | Latitude 5420               | Notebook    | [03247dc98c](https://linux-hardware.org/?probe=03247dc98c) | Apr 16, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [71e03c5459](https://linux-hardware.org/?probe=71e03c5459) | Apr 15, 2023 |
| Gigabyte      | X79-UD5                     | Desktop     | [369c3cfdb2](https://linux-hardware.org/?probe=369c3cfdb2) | Apr 15, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [3470b35550](https://linux-hardware.org/?probe=3470b35550) | Apr 15, 2023 |
| Lenovo        | ThinkCentre M58p 7220A72    | Desktop     | [2be395131f](https://linux-hardware.org/?probe=2be395131f) | Apr 15, 2023 |
| Lenovo        | ThinkCentre M58p 7220A72    | Desktop     | [0ca4b7045e](https://linux-hardware.org/?probe=0ca4b7045e) | Apr 15, 2023 |
| Toshiba       | QOSMIO F750                 | Notebook    | [590801670a](https://linux-hardware.org/?probe=590801670a) | Apr 15, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [ffa823032e](https://linux-hardware.org/?probe=ffa823032e) | Apr 14, 2023 |
| Toshiba       | Satellite L850              | Notebook    | [dc9e77bd65](https://linux-hardware.org/?probe=dc9e77bd65) | Apr 14, 2023 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [fe75c98b15](https://linux-hardware.org/?probe=fe75c98b15) | Apr 14, 2023 |
| Lenovo        | ThinkStation D30 42234T7    | Desktop     | [7730eb04fa](https://linux-hardware.org/?probe=7730eb04fa) | Apr 14, 2023 |
| Dell          | Latitude E6540              | Notebook    | [61ab891b01](https://linux-hardware.org/?probe=61ab891b01) | Apr 13, 2023 |
| Dell          | Vostro 7590                 | Notebook    | [f759d8ab72](https://linux-hardware.org/?probe=f759d8ab72) | Apr 13, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [8e641b5fd5](https://linux-hardware.org/?probe=8e641b5fd5) | Apr 13, 2023 |
| Acer          | Aspire 5720Z                | Notebook    | [1ac7eb0d0c](https://linux-hardware.org/?probe=1ac7eb0d0c) | Apr 13, 2023 |
| ECS           | H61H2-MV                    | Desktop     | [5a3fbafb75](https://linux-hardware.org/?probe=5a3fbafb75) | Apr 12, 2023 |
| HP            | 843B                        | Desktop     | [90de5c4ff1](https://linux-hardware.org/?probe=90de5c4ff1) | Apr 12, 2023 |
| Gigabyte      | X79-UP4                     | Desktop     | [8f9b60caf3](https://linux-hardware.org/?probe=8f9b60caf3) | Apr 12, 2023 |
| HP            | 3646h                       | Desktop     | [c36653d824](https://linux-hardware.org/?probe=c36653d824) | Apr 12, 2023 |
| ASRock        | X370 Gaming-ITX/ac          | Desktop     | [29ed28536e](https://linux-hardware.org/?probe=29ed28536e) | Apr 12, 2023 |
| Acer          | TM6495T                     | Notebook    | [435ae018a2](https://linux-hardware.org/?probe=435ae018a2) | Apr 11, 2023 |
| Lenovo        | ThinkPad L13 Yoga 20R6S1... | Convertible | [8ca7e7c5ad](https://linux-hardware.org/?probe=8ca7e7c5ad) | Apr 10, 2023 |
| MSI           | H81M-P33                    | Desktop     | [129abe0b90](https://linux-hardware.org/?probe=129abe0b90) | Apr 10, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [f9382ece8e](https://linux-hardware.org/?probe=f9382ece8e) | Apr 10, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [6dd2d460aa](https://linux-hardware.org/?probe=6dd2d460aa) | Apr 10, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [7d5fb1a311](https://linux-hardware.org/?probe=7d5fb1a311) | Apr 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [2765290b8c](https://linux-hardware.org/?probe=2765290b8c) | Apr 09, 2023 |
| Lenovo        | ThinkPad E460 20ETA05KAU    | Notebook    | [a8090f51bc](https://linux-hardware.org/?probe=a8090f51bc) | Apr 09, 2023 |
| SYWZ          | S210H Series                | Desktop     | [5989537064](https://linux-hardware.org/?probe=5989537064) | Apr 09, 2023 |
| Dell          | Inspiron 1720               | Notebook    | [a2e3b07f6b](https://linux-hardware.org/?probe=a2e3b07f6b) | Apr 09, 2023 |
| ASUSTek       | PRIME Z590-P WIFI           | Desktop     | [e579aabfdb](https://linux-hardware.org/?probe=e579aabfdb) | Apr 09, 2023 |
| Samsung       | Galaxy Book 12 LTE          | Tablet      | [d866c03132](https://linux-hardware.org/?probe=d866c03132) | Apr 08, 2023 |
| Dell          | Latitude E5470              | Notebook    | [3e49e9c541](https://linux-hardware.org/?probe=3e49e9c541) | Apr 08, 2023 |
| MSI           | B550M-A PRO                 | Desktop     | [e3fcf877c0](https://linux-hardware.org/?probe=e3fcf877c0) | Apr 08, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [5aad90904c](https://linux-hardware.org/?probe=5aad90904c) | Apr 07, 2023 |
| Acer          | TravelMate 8572T            | Notebook    | [04f50662d8](https://linux-hardware.org/?probe=04f50662d8) | Apr 07, 2023 |
| Toshiba       | Satellite P70-A             | Notebook    | [6ffb7a79ef](https://linux-hardware.org/?probe=6ffb7a79ef) | Apr 06, 2023 |
| MSI           | MS-B1831                    | Desktop     | [9ea2ec4f47](https://linux-hardware.org/?probe=9ea2ec4f47) | Apr 06, 2023 |
| MSI           | A88XM-E35 V2                | Desktop     | [bf4c16404e](https://linux-hardware.org/?probe=bf4c16404e) | Apr 06, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [be741560b8](https://linux-hardware.org/?probe=be741560b8) | Apr 06, 2023 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [7644d4a8fa](https://linux-hardware.org/?probe=7644d4a8fa) | Apr 06, 2023 |
| HP            | Pavilion dv6                | Notebook    | [be695e2cd4](https://linux-hardware.org/?probe=be695e2cd4) | Apr 06, 2023 |
| ASUSTek       | H87-PRO                     | Desktop     | [085dc66a77](https://linux-hardware.org/?probe=085dc66a77) | Apr 05, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [258f32d502](https://linux-hardware.org/?probe=258f32d502) | Apr 05, 2023 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [7e5be74f0b](https://linux-hardware.org/?probe=7e5be74f0b) | Apr 05, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [473a8c1d7b](https://linux-hardware.org/?probe=473a8c1d7b) | Apr 05, 2023 |
| Shenzhen M... | F7BFD                       | Desktop     | [7f6103b394](https://linux-hardware.org/?probe=7f6103b394) | Apr 05, 2023 |
| Shenzhen M... | F7BFD                       | Desktop     | [ac039ed7e6](https://linux-hardware.org/?probe=ac039ed7e6) | Apr 05, 2023 |
| HP            | Notebook                    | Notebook    | [50c03e608d](https://linux-hardware.org/?probe=50c03e608d) | Apr 05, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [56079f49e3](https://linux-hardware.org/?probe=56079f49e3) | Apr 04, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [4ef5210167](https://linux-hardware.org/?probe=4ef5210167) | Apr 04, 2023 |
| HP            | 843B                        | Desktop     | [aa679005d3](https://linux-hardware.org/?probe=aa679005d3) | Apr 04, 2023 |
| HP            | 843B                        | Desktop     | [ba686ac542](https://linux-hardware.org/?probe=ba686ac542) | Apr 04, 2023 |
| Shuttle       | DS10U                       | Desktop     | [a35fd102f2](https://linux-hardware.org/?probe=a35fd102f2) | Apr 04, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [3a87280f55](https://linux-hardware.org/?probe=3a87280f55) | Apr 03, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [1cb5977d82](https://linux-hardware.org/?probe=1cb5977d82) | Apr 03, 2023 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [9e25dfd6bb](https://linux-hardware.org/?probe=9e25dfd6bb) | Apr 02, 2023 |
| ASRock        | FM2A55M-DGS                 | Desktop     | [250384a794](https://linux-hardware.org/?probe=250384a794) | Apr 02, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [d016e78eab](https://linux-hardware.org/?probe=d016e78eab) | Apr 02, 2023 |
| Acer          | EQ45LM                      | Desktop     | [5bafe47784](https://linux-hardware.org/?probe=5bafe47784) | Apr 02, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [89622c73d1](https://linux-hardware.org/?probe=89622c73d1) | Apr 02, 2023 |
| Gigabyte      | X99-UD3-CF                  | Desktop     | [82a3b55b60](https://linux-hardware.org/?probe=82a3b55b60) | Apr 02, 2023 |
| Dell          | 09M8Y8 A01                  | Desktop     | [17d5390549](https://linux-hardware.org/?probe=17d5390549) | Apr 01, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [7beef34820](https://linux-hardware.org/?probe=7beef34820) | Apr 01, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [8357ff8cf5](https://linux-hardware.org/?probe=8357ff8cf5) | Apr 01, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [89ca656f30](https://linux-hardware.org/?probe=89ca656f30) | Apr 01, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [2a881cc01e](https://linux-hardware.org/?probe=2a881cc01e) | Apr 01, 2023 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [2be0fa6524](https://linux-hardware.org/?probe=2be0fa6524) | Apr 01, 2023 |
| Lenovo        | ThinkStation D30 42234T7    | Desktop     | [47f6f4653b](https://linux-hardware.org/?probe=47f6f4653b) | Mar 31, 2023 |
| Unknown       | Unknown                     | Desktop     | [1f64d2db28](https://linux-hardware.org/?probe=1f64d2db28) | Mar 31, 2023 |
| ASRock        | FM2A55M-DGS                 | Desktop     | [3ab2e2c720](https://linux-hardware.org/?probe=3ab2e2c720) | Mar 31, 2023 |
| Gigabyte      | B85M-HD3                    | Desktop     | [3d24b75a10](https://linux-hardware.org/?probe=3d24b75a10) | Mar 31, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [05d42527df](https://linux-hardware.org/?probe=05d42527df) | Mar 31, 2023 |
| Dell          | 09M8Y8 A01                  | Desktop     | [2c13e40cd2](https://linux-hardware.org/?probe=2c13e40cd2) | Mar 30, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [92981c741d](https://linux-hardware.org/?probe=92981c741d) | Mar 30, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [af4901f141](https://linux-hardware.org/?probe=af4901f141) | Mar 30, 2023 |
| HP            | ProBook 450 G5              | Notebook    | [89dfecad7e](https://linux-hardware.org/?probe=89dfecad7e) | Mar 30, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [8d0c93e1a8](https://linux-hardware.org/?probe=8d0c93e1a8) | Mar 30, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [881f70cb12](https://linux-hardware.org/?probe=881f70cb12) | Mar 30, 2023 |
| Dell          | Precision 5550              | Notebook    | [c7244f1e31](https://linux-hardware.org/?probe=c7244f1e31) | Mar 30, 2023 |
| Dell          | G3 3590                     | Notebook    | [f61ce9bb82](https://linux-hardware.org/?probe=f61ce9bb82) | Mar 28, 2023 |
| Gigabyte      | H55M-USB3                   | Desktop     | [140b984b9f](https://linux-hardware.org/?probe=140b984b9f) | Mar 28, 2023 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [5064a5267e](https://linux-hardware.org/?probe=5064a5267e) | Mar 28, 2023 |
| MSI           | Delta 15 A5EFK              | Notebook    | [6f4e3ec28b](https://linux-hardware.org/?probe=6f4e3ec28b) | Mar 28, 2023 |
| MSI           | Delta 15 A5EFK              | Notebook    | [9dd1b67b2f](https://linux-hardware.org/?probe=9dd1b67b2f) | Mar 28, 2023 |
| Lenovo        | 0x36A017AA SDK0J40709 WI... | Desktop     | [562426633d](https://linux-hardware.org/?probe=562426633d) | Mar 28, 2023 |
| ASRock        | FM2A88X+ Killer             | Desktop     | [6180e562dd](https://linux-hardware.org/?probe=6180e562dd) | Mar 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [de6a63685a](https://linux-hardware.org/?probe=de6a63685a) | Mar 27, 2023 |
| Lenovo        | ThinkStation D30 42234T7    | Desktop     | [cfb8c9d396](https://linux-hardware.org/?probe=cfb8c9d396) | Mar 27, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [e67759f49b](https://linux-hardware.org/?probe=e67759f49b) | Mar 26, 2023 |
| HP            | 0B54h D                     | Desktop     | [540caaf04c](https://linux-hardware.org/?probe=540caaf04c) | Mar 26, 2023 |
| ASUSTek       | Maximus VIII HERO ALPHA     | Desktop     | [cc262bb41a](https://linux-hardware.org/?probe=cc262bb41a) | Mar 26, 2023 |
| ASRock        | AD525PV3                    | Desktop     | [84545fd0ea](https://linux-hardware.org/?probe=84545fd0ea) | Mar 25, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [8060aec150](https://linux-hardware.org/?probe=8060aec150) | Mar 25, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [5acd2b0492](https://linux-hardware.org/?probe=5acd2b0492) | Mar 25, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [5312ec3cc9](https://linux-hardware.org/?probe=5312ec3cc9) | Mar 25, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [1503a33123](https://linux-hardware.org/?probe=1503a33123) | Mar 24, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [9edd5002f0](https://linux-hardware.org/?probe=9edd5002f0) | Mar 24, 2023 |
| HP            | ProBook 470 G5              | Notebook    | [1672158957](https://linux-hardware.org/?probe=1672158957) | Mar 24, 2023 |
| HP            | ProBook 470 G5              | Notebook    | [383b333f72](https://linux-hardware.org/?probe=383b333f72) | Mar 24, 2023 |
| ReachingTe... | DreamQuest Pro 2022         | Mini pc     | [696a898cd2](https://linux-hardware.org/?probe=696a898cd2) | Mar 24, 2023 |
| ASRock        | AD525PV3                    | Desktop     | [0749ec7b44](https://linux-hardware.org/?probe=0749ec7b44) | Mar 23, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | Notebook    | [fc1c184c05](https://linux-hardware.org/?probe=fc1c184c05) | Mar 23, 2023 |
| AMI           | Intel                       | Desktop     | [5e7b21c227](https://linux-hardware.org/?probe=5e7b21c227) | Mar 23, 2023 |
| Acer          | ConceptD CN315-71P          | Notebook    | [14b71e7a26](https://linux-hardware.org/?probe=14b71e7a26) | Mar 22, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [10269c811b](https://linux-hardware.org/?probe=10269c811b) | Mar 22, 2023 |
| MSI           | MS-7142                     | Desktop     | [1cb67ac1ca](https://linux-hardware.org/?probe=1cb67ac1ca) | Mar 22, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [61025e6e8b](https://linux-hardware.org/?probe=61025e6e8b) | Mar 22, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [80d1a2d67d](https://linux-hardware.org/?probe=80d1a2d67d) | Mar 22, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [eb718edb23](https://linux-hardware.org/?probe=eb718edb23) | Mar 22, 2023 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [8c50d5ae87](https://linux-hardware.org/?probe=8c50d5ae87) | Mar 21, 2023 |
| Acer          | Spin SP314-54N              | Convertible | [4f2e83ab00](https://linux-hardware.org/?probe=4f2e83ab00) | Mar 21, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [a1e76aa5c1](https://linux-hardware.org/?probe=a1e76aa5c1) | Mar 21, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [16253cadcf](https://linux-hardware.org/?probe=16253cadcf) | Mar 21, 2023 |
| Dell          | Latitude E6520              | Notebook    | [857fdb4095](https://linux-hardware.org/?probe=857fdb4095) | Mar 21, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [c2191470c7](https://linux-hardware.org/?probe=c2191470c7) | Mar 21, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [6f98b39459](https://linux-hardware.org/?probe=6f98b39459) | Mar 21, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [c5c907b643](https://linux-hardware.org/?probe=c5c907b643) | Mar 21, 2023 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [ad4c43dd09](https://linux-hardware.org/?probe=ad4c43dd09) | Mar 21, 2023 |
| Apple         | Mac-F2208EC8                | Mini pc     | [4b47e3ed6c](https://linux-hardware.org/?probe=4b47e3ed6c) | Mar 20, 2023 |
| Gigabyte      | H610M H DDR4                | Desktop     | [b7cf9d91ee](https://linux-hardware.org/?probe=b7cf9d91ee) | Mar 20, 2023 |
| Acer          | Spin SP314-54N              | Convertible | [40d6f69489](https://linux-hardware.org/?probe=40d6f69489) | Mar 20, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [c63a27da32](https://linux-hardware.org/?probe=c63a27da32) | Mar 20, 2023 |
| ASUSTek       | Maximus Extreme             | Desktop     | [c6215ec2f3](https://linux-hardware.org/?probe=c6215ec2f3) | Mar 20, 2023 |
| ASUSTek       | PRIME B250M-K               | Desktop     | [99cb000a4e](https://linux-hardware.org/?probe=99cb000a4e) | Mar 19, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [67c8f562e5](https://linux-hardware.org/?probe=67c8f562e5) | Mar 18, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [dc411c9ce3](https://linux-hardware.org/?probe=dc411c9ce3) | Mar 18, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | Notebook    | [786fded1ce](https://linux-hardware.org/?probe=786fded1ce) | Mar 17, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [49bb337156](https://linux-hardware.org/?probe=49bb337156) | Mar 17, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [d762fe2bf3](https://linux-hardware.org/?probe=d762fe2bf3) | Mar 17, 2023 |
| Valve         | Jupiter                     | Notebook    | [8f51ab644e](https://linux-hardware.org/?probe=8f51ab644e) | Mar 17, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [b4483fd4e2](https://linux-hardware.org/?probe=b4483fd4e2) | Mar 16, 2023 |
| Dell          | G3 3590                     | Notebook    | [9ef42643d8](https://linux-hardware.org/?probe=9ef42643d8) | Mar 16, 2023 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [a4c449eef4](https://linux-hardware.org/?probe=a4c449eef4) | Mar 16, 2023 |
| HP            | ProBook 430 G8 Notebook ... | Notebook    | [ca6ab3c197](https://linux-hardware.org/?probe=ca6ab3c197) | Mar 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [684375b9a0](https://linux-hardware.org/?probe=684375b9a0) | Mar 16, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | Notebook    | [787dfaa7d4](https://linux-hardware.org/?probe=787dfaa7d4) | Mar 15, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [12e9972d5a](https://linux-hardware.org/?probe=12e9972d5a) | Mar 15, 2023 |
| Huanan        | X99-AD3 GAMING V2.0         | Desktop     | [0586633e29](https://linux-hardware.org/?probe=0586633e29) | Mar 15, 2023 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [b324afc6f8](https://linux-hardware.org/?probe=b324afc6f8) | Mar 14, 2023 |
| Intel         | DB85FL AAG89861-203         | Desktop     | [e17dae3447](https://linux-hardware.org/?probe=e17dae3447) | Mar 14, 2023 |
| Intel         | DB85FL AAG89861-203         | Desktop     | [f1004a32e1](https://linux-hardware.org/?probe=f1004a32e1) | Mar 14, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [59478f318e](https://linux-hardware.org/?probe=59478f318e) | Mar 14, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [954055245e](https://linux-hardware.org/?probe=954055245e) | Mar 14, 2023 |
| Dell          | Inspiron M5010              | Notebook    | [0a5d0c9169](https://linux-hardware.org/?probe=0a5d0c9169) | Mar 14, 2023 |
| QIYIDA        | X99-H9 V2.0                 | Desktop     | [0f440670f2](https://linux-hardware.org/?probe=0f440670f2) | Mar 14, 2023 |
| Acer          | Aspire E5-511               | Notebook    | [5343f73c67](https://linux-hardware.org/?probe=5343f73c67) | Mar 13, 2023 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [61af17e1cd](https://linux-hardware.org/?probe=61af17e1cd) | Mar 13, 2023 |
| Apple         | Mac-7BA5B2794B2CDB12 Mac... | Mini pc     | [cd75bab781](https://linux-hardware.org/?probe=cd75bab781) | Mar 13, 2023 |
| Fanless Mi... | Rev GMLR1                   | Mini pc     | [4ac1bccada](https://linux-hardware.org/?probe=4ac1bccada) | Mar 13, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | Notebook    | [b5d8bdc57d](https://linux-hardware.org/?probe=b5d8bdc57d) | Mar 12, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | Notebook    | [4525fa2931](https://linux-hardware.org/?probe=4525fa2931) | Mar 12, 2023 |
| Lenovo        | ThinkPad E590 20NBA000AU    | Notebook    | [47bfd44610](https://linux-hardware.org/?probe=47bfd44610) | Mar 12, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [e45386803e](https://linux-hardware.org/?probe=e45386803e) | Mar 12, 2023 |
| Gigabyte      | Z590I AORUS ULTRA           | Desktop     | [47ea9647d3](https://linux-hardware.org/?probe=47ea9647d3) | Mar 12, 2023 |
| Gigabyte      | X670E AORUS XTREME          | Desktop     | [83cb566647](https://linux-hardware.org/?probe=83cb566647) | Mar 12, 2023 |
| ASUSTek       | A88X-PLUS                   | Desktop     | [3624df5386](https://linux-hardware.org/?probe=3624df5386) | Mar 11, 2023 |
| Maibenben     | P748                        | Notebook    | [a44d1bb8e4](https://linux-hardware.org/?probe=a44d1bb8e4) | Mar 11, 2023 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [23b5dbe59d](https://linux-hardware.org/?probe=23b5dbe59d) | Mar 11, 2023 |
| ASRock        | 990FX Killer                | Desktop     | [23bd30e79e](https://linux-hardware.org/?probe=23bd30e79e) | Mar 11, 2023 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [46c1d399ac](https://linux-hardware.org/?probe=46c1d399ac) | Mar 11, 2023 |
| Gigabyte      | Z590 AORUS ELITE            | Desktop     | [790a51e99f](https://linux-hardware.org/?probe=790a51e99f) | Mar 11, 2023 |
| Acer          | Veriton X4640G V:1.1        | Desktop     | [dd3e15feee](https://linux-hardware.org/?probe=dd3e15feee) | Mar 10, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [35ab0f32c5](https://linux-hardware.org/?probe=35ab0f32c5) | Mar 10, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [9d14bee09f](https://linux-hardware.org/?probe=9d14bee09f) | Mar 10, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [e27d91ea6f](https://linux-hardware.org/?probe=e27d91ea6f) | Mar 09, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [790877da61](https://linux-hardware.org/?probe=790877da61) | Mar 09, 2023 |
| Lenovo        | ThinkPad L13 Yoga 20R6S1... | Convertible | [970e94ad07](https://linux-hardware.org/?probe=970e94ad07) | Mar 09, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [ded87de736](https://linux-hardware.org/?probe=ded87de736) | Mar 09, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [7413353e38](https://linux-hardware.org/?probe=7413353e38) | Mar 09, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [89647ee142](https://linux-hardware.org/?probe=89647ee142) | Mar 08, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [fd0eabacbf](https://linux-hardware.org/?probe=fd0eabacbf) | Mar 08, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [dfe7f75406](https://linux-hardware.org/?probe=dfe7f75406) | Mar 08, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [ffaa232ea2](https://linux-hardware.org/?probe=ffaa232ea2) | Mar 08, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [916862cd66](https://linux-hardware.org/?probe=916862cd66) | Mar 08, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | Notebook    | [54ad36532c](https://linux-hardware.org/?probe=54ad36532c) | Mar 07, 2023 |
| HP            | Stream Laptop 11-ah1XX      | Notebook    | [61e3840465](https://linux-hardware.org/?probe=61e3840465) | Mar 07, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [70eb1caef5](https://linux-hardware.org/?probe=70eb1caef5) | Mar 07, 2023 |
| HP            | Compaq Presario C700        | Notebook    | [fe1c136403](https://linux-hardware.org/?probe=fe1c136403) | Mar 06, 2023 |
| HP            | Compaq Presario C700        | Notebook    | [0b29805ec8](https://linux-hardware.org/?probe=0b29805ec8) | Mar 06, 2023 |
| HP            | ENVY 17                     | Notebook    | [ce2278a2e4](https://linux-hardware.org/?probe=ce2278a2e4) | Mar 05, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [dfc84acc1a](https://linux-hardware.org/?probe=dfc84acc1a) | Mar 05, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [3d1560d3d1](https://linux-hardware.org/?probe=3d1560d3d1) | Mar 05, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [7d1b3a73f9](https://linux-hardware.org/?probe=7d1b3a73f9) | Mar 05, 2023 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [9de6b65a45](https://linux-hardware.org/?probe=9de6b65a45) | Mar 04, 2023 |
| Google        | Ultima                      | Notebook    | [5e42f67839](https://linux-hardware.org/?probe=5e42f67839) | Mar 04, 2023 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [fca1ca2628](https://linux-hardware.org/?probe=fca1ca2628) | Mar 04, 2023 |
| SONIQ Digi... | Soniq 11.6inch Convertib... | Convertible | [e0b2fdc347](https://linux-hardware.org/?probe=e0b2fdc347) | Mar 04, 2023 |
| Valve         | Jupiter                     | Notebook    | [65a9e7ef52](https://linux-hardware.org/?probe=65a9e7ef52) | Mar 04, 2023 |
| Intel         | NUC12EDBi7 M27908-302       | Mini pc     | [bb51e864a7](https://linux-hardware.org/?probe=bb51e864a7) | Mar 03, 2023 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [3be3c8d79d](https://linux-hardware.org/?probe=3be3c8d79d) | Mar 03, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [906cb4b50a](https://linux-hardware.org/?probe=906cb4b50a) | Mar 03, 2023 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [f043beec18](https://linux-hardware.org/?probe=f043beec18) | Mar 03, 2023 |
| Dell          | 0KC9NP A00                  | Desktop     | [45397750b4](https://linux-hardware.org/?probe=45397750b4) | Mar 02, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [2173dea5df](https://linux-hardware.org/?probe=2173dea5df) | Mar 02, 2023 |
| Toshiba       | TECRA Z50-C                 | Notebook    | [c30ead38bd](https://linux-hardware.org/?probe=c30ead38bd) | Mar 02, 2023 |
| MSI           | PRO H610M-G DDR4            | Desktop     | [8ecbea06f8](https://linux-hardware.org/?probe=8ecbea06f8) | Mar 02, 2023 |
| Apple         | MacBookPro14,3              | Notebook    | [6f952b4c9b](https://linux-hardware.org/?probe=6f952b4c9b) | Mar 01, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [25c46b6f70](https://linux-hardware.org/?probe=25c46b6f70) | Mar 01, 2023 |
| Dell          | 09KPNV A01                  | Desktop     | [08346526f3](https://linux-hardware.org/?probe=08346526f3) | Mar 01, 2023 |
| Biostar       | B450MH                      | Desktop     | [aa05ee87d1](https://linux-hardware.org/?probe=aa05ee87d1) | Mar 01, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [131f94f213](https://linux-hardware.org/?probe=131f94f213) | Mar 01, 2023 |
| Intel Clie... | LAPRC510                    | Notebook    | [925c24b3db](https://linux-hardware.org/?probe=925c24b3db) | Feb 28, 2023 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [021853dafb](https://linux-hardware.org/?probe=021853dafb) | Feb 28, 2023 |
| Intel Clie... | LAPRC510                    | Notebook    | [6d9a8edb0c](https://linux-hardware.org/?probe=6d9a8edb0c) | Feb 28, 2023 |
| Dell          | 0XHGV1 A00                  | Desktop     | [75249be116](https://linux-hardware.org/?probe=75249be116) | Feb 27, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [816a4eb27e](https://linux-hardware.org/?probe=816a4eb27e) | Feb 26, 2023 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [b27fb5e204](https://linux-hardware.org/?probe=b27fb5e204) | Feb 26, 2023 |
| Pegatron      | 2ACB                        | Desktop     | [13355a7d07](https://linux-hardware.org/?probe=13355a7d07) | Feb 26, 2023 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [a2356a66ba](https://linux-hardware.org/?probe=a2356a66ba) | Feb 26, 2023 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [ce67684fdf](https://linux-hardware.org/?probe=ce67684fdf) | Feb 26, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [7f2823a756](https://linux-hardware.org/?probe=7f2823a756) | Feb 26, 2023 |
| HP            | 0AECh D                     | Desktop     | [5baf25e8af](https://linux-hardware.org/?probe=5baf25e8af) | Feb 26, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [0b1c4036b1](https://linux-hardware.org/?probe=0b1c4036b1) | Feb 26, 2023 |
| HP            | Notebook                    | Notebook    | [4a72575c17](https://linux-hardware.org/?probe=4a72575c17) | Feb 25, 2023 |
| Medion        | MAG Z390M MORTAR            | Desktop     | [e2445cf24c](https://linux-hardware.org/?probe=e2445cf24c) | Feb 25, 2023 |
| Toshiba       | Satellite C850              | Notebook    | [99d4efbb52](https://linux-hardware.org/?probe=99d4efbb52) | Feb 25, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [4a0d65f6b5](https://linux-hardware.org/?probe=4a0d65f6b5) | Feb 24, 2023 |
| Gigabyte      | Z77M-D3H-MVP                | Desktop     | [e27e1cd0e8](https://linux-hardware.org/?probe=e27e1cd0e8) | Feb 24, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [72e11db1c0](https://linux-hardware.org/?probe=72e11db1c0) | Feb 24, 2023 |
| MSI           | Vector GP66 12UEO           | Notebook    | [9b6bf9479e](https://linux-hardware.org/?probe=9b6bf9479e) | Feb 24, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [ea2663126f](https://linux-hardware.org/?probe=ea2663126f) | Feb 24, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [8a09d5e812](https://linux-hardware.org/?probe=8a09d5e812) | Feb 23, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [e386073c5d](https://linux-hardware.org/?probe=e386073c5d) | Feb 23, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [d65a9c975d](https://linux-hardware.org/?probe=d65a9c975d) | Feb 23, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | Notebook    | [fa9427d71f](https://linux-hardware.org/?probe=fa9427d71f) | Feb 22, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [2d36b57c9c](https://linux-hardware.org/?probe=2d36b57c9c) | Feb 22, 2023 |
| Lenovo        | ThinkPad X131e 3367AH5      | Notebook    | [3c1cec4c1c](https://linux-hardware.org/?probe=3c1cec4c1c) | Feb 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [8110c575e9](https://linux-hardware.org/?probe=8110c575e9) | Feb 22, 2023 |
| Acer          | TravelMate 8572T            | Notebook    | [20d7321f8f](https://linux-hardware.org/?probe=20d7321f8f) | Feb 21, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [e293e73518](https://linux-hardware.org/?probe=e293e73518) | Feb 21, 2023 |
| MSI           | B550 GAMING GEN3            | Desktop     | [d92a4239ee](https://linux-hardware.org/?probe=d92a4239ee) | Feb 21, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [edd5640ca7](https://linux-hardware.org/?probe=edd5640ca7) | Feb 21, 2023 |
| Dell          | Latitude 5430               | Notebook    | [69fd82c453](https://linux-hardware.org/?probe=69fd82c453) | Feb 21, 2023 |
| Acer          | Aspire X3950                | Desktop     | [f5b4a3baa3](https://linux-hardware.org/?probe=f5b4a3baa3) | Feb 20, 2023 |
| Dell          | Latitude E6430              | Notebook    | [42750c43b5](https://linux-hardware.org/?probe=42750c43b5) | Feb 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [2cc51656a5](https://linux-hardware.org/?probe=2cc51656a5) | Feb 20, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [f8a26128a4](https://linux-hardware.org/?probe=f8a26128a4) | Feb 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [d4663db4e0](https://linux-hardware.org/?probe=d4663db4e0) | Feb 19, 2023 |
| AZW           | GTi                         | Desktop     | [17bb698441](https://linux-hardware.org/?probe=17bb698441) | Feb 19, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [ca676dc566](https://linux-hardware.org/?probe=ca676dc566) | Feb 19, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [9b0ecbd3c7](https://linux-hardware.org/?probe=9b0ecbd3c7) | Feb 19, 2023 |
| Gigabyte      | Z590I AORUS ULTRA           | Desktop     | [9805ab5764](https://linux-hardware.org/?probe=9805ab5764) | Feb 19, 2023 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [aa49c18960](https://linux-hardware.org/?probe=aa49c18960) | Feb 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [0365a40dd4](https://linux-hardware.org/?probe=0365a40dd4) | Feb 18, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | Notebook    | [cc44156b99](https://linux-hardware.org/?probe=cc44156b99) | Feb 17, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | Notebook    | [bc234d0b32](https://linux-hardware.org/?probe=bc234d0b32) | Feb 17, 2023 |
| Toshiba       | Satellite P750              | Notebook    | [6f5f99b514](https://linux-hardware.org/?probe=6f5f99b514) | Feb 16, 2023 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [68f0415788](https://linux-hardware.org/?probe=68f0415788) | Feb 16, 2023 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [2560ba7644](https://linux-hardware.org/?probe=2560ba7644) | Feb 16, 2023 |
| Raspberry ... | Raspberry Pi Model B Plu... | Soc         | [65c778e356](https://linux-hardware.org/?probe=65c778e356) | Feb 16, 2023 |
| ASRock        | Z77 Extreme6                | Desktop     | [48328ab864](https://linux-hardware.org/?probe=48328ab864) | Feb 15, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [8f5697ea3a](https://linux-hardware.org/?probe=8f5697ea3a) | Feb 15, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [f12f20217b](https://linux-hardware.org/?probe=f12f20217b) | Feb 15, 2023 |
| ASUSTek       | V-P7H55E                    | Desktop     | [27ddce20a1](https://linux-hardware.org/?probe=27ddce20a1) | Feb 15, 2023 |
| Gigabyte      | H410M DS2V                  | Desktop     | [b2e8c15dc4](https://linux-hardware.org/?probe=b2e8c15dc4) | Feb 15, 2023 |
| Dell          | 09M8Y8 A01                  | Desktop     | [beabc46f67](https://linux-hardware.org/?probe=beabc46f67) | Feb 14, 2023 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [f298c1fc7e](https://linux-hardware.org/?probe=f298c1fc7e) | Feb 14, 2023 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [45cfd72091](https://linux-hardware.org/?probe=45cfd72091) | Feb 14, 2023 |
| Dell          | 09M8Y8 A01                  | Desktop     | [fb1ff4a6d9](https://linux-hardware.org/?probe=fb1ff4a6d9) | Feb 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [1a20fdd090](https://linux-hardware.org/?probe=1a20fdd090) | Feb 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [3384ced1ca](https://linux-hardware.org/?probe=3384ced1ca) | Feb 14, 2023 |
| MSI           | Vector GP66 12UEO           | Notebook    | [040bddeff8](https://linux-hardware.org/?probe=040bddeff8) | Feb 14, 2023 |
| Gigabyte      | Z68X-UD3H-B3                | Desktop     | [0ad0fe310f](https://linux-hardware.org/?probe=0ad0fe310f) | Feb 14, 2023 |
| HP            | Compaq nc6400 (RM741PA#A... | Notebook    | [d556bf453d](https://linux-hardware.org/?probe=d556bf453d) | Feb 13, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [b563d8f052](https://linux-hardware.org/?probe=b563d8f052) | Feb 13, 2023 |
| ASUSTek       | K45VS                       | Notebook    | [faf4fc0251](https://linux-hardware.org/?probe=faf4fc0251) | Feb 12, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [219157717b](https://linux-hardware.org/?probe=219157717b) | Feb 12, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [cdc63fb05e](https://linux-hardware.org/?probe=cdc63fb05e) | Feb 12, 2023 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [7fec987264](https://linux-hardware.org/?probe=7fec987264) | Feb 12, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [72b0ba099a](https://linux-hardware.org/?probe=72b0ba099a) | Feb 11, 2023 |
| Acer          | Aspire One 753              | Notebook    | [b3ef912b35](https://linux-hardware.org/?probe=b3ef912b35) | Feb 10, 2023 |
| Dell          | G15 5520                    | Notebook    | [121b06f3cc](https://linux-hardware.org/?probe=121b06f3cc) | Feb 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | Notebook    | [e3ea6ad8da](https://linux-hardware.org/?probe=e3ea6ad8da) | Feb 10, 2023 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [99dda6c06c](https://linux-hardware.org/?probe=99dda6c06c) | Feb 09, 2023 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [30363b3a5d](https://linux-hardware.org/?probe=30363b3a5d) | Feb 09, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [fff70a8d2c](https://linux-hardware.org/?probe=fff70a8d2c) | Feb 09, 2023 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | Notebook    | [b79b2f3f75](https://linux-hardware.org/?probe=b79b2f3f75) | Feb 09, 2023 |
| Intel         | LADPNVMO AAE76523-300       | Desktop     | [6ced92edc7](https://linux-hardware.org/?probe=6ced92edc7) | Feb 09, 2023 |
| ASUSTek       | ZenBook UX463FA_UX463FA     | Convertible | [e43aebc69d](https://linux-hardware.org/?probe=e43aebc69d) | Feb 08, 2023 |
| Dell          | G15 5520                    | Notebook    | [7f4d36cea1](https://linux-hardware.org/?probe=7f4d36cea1) | Feb 08, 2023 |
| ASUSTek       | P5Q3 DELUXE                 | Desktop     | [16c72d3532](https://linux-hardware.org/?probe=16c72d3532) | Feb 08, 2023 |
| Alienware     | m15 R7                      | Notebook    | [254ab40fcf](https://linux-hardware.org/?probe=254ab40fcf) | Feb 07, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [0f4be18646](https://linux-hardware.org/?probe=0f4be18646) | Feb 07, 2023 |
| HP            | 0AA0h                       | Desktop     | [921b7f0d0c](https://linux-hardware.org/?probe=921b7f0d0c) | Feb 07, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [4a647dd6b9](https://linux-hardware.org/?probe=4a647dd6b9) | Feb 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [8b26ec07a6](https://linux-hardware.org/?probe=8b26ec07a6) | Feb 07, 2023 |
| Acer          | Aspire E3-111               | Notebook    | [a7c14e51ff](https://linux-hardware.org/?probe=a7c14e51ff) | Feb 06, 2023 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [99d0ce5421](https://linux-hardware.org/?probe=99d0ce5421) | Feb 05, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [2f0810d441](https://linux-hardware.org/?probe=2f0810d441) | Feb 05, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [a0fc4f78ea](https://linux-hardware.org/?probe=a0fc4f78ea) | Feb 05, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [5a7ae4b151](https://linux-hardware.org/?probe=5a7ae4b151) | Feb 05, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [2b9cb5eea6](https://linux-hardware.org/?probe=2b9cb5eea6) | Feb 05, 2023 |
| Intel         | X99                         | Desktop     | [e8790caf8d](https://linux-hardware.org/?probe=e8790caf8d) | Feb 05, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [0eb4367fb4](https://linux-hardware.org/?probe=0eb4367fb4) | Feb 04, 2023 |
| ASUSTek       | X550LC                      | Notebook    | [f22682c35f](https://linux-hardware.org/?probe=f22682c35f) | Feb 04, 2023 |
| Toshiba       | Satellite P500              | Notebook    | [78ebd7c272](https://linux-hardware.org/?probe=78ebd7c272) | Feb 04, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [a17959ea9b](https://linux-hardware.org/?probe=a17959ea9b) | Feb 04, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [38625b9f02](https://linux-hardware.org/?probe=38625b9f02) | Feb 03, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [6ffe048ee2](https://linux-hardware.org/?probe=6ffe048ee2) | Feb 03, 2023 |
| Acer          | Aspire XC-603               | Desktop     | [fff64928e8](https://linux-hardware.org/?probe=fff64928e8) | Feb 03, 2023 |
| Acer          | Aspire XC-603               | Desktop     | [2cd1d2f51f](https://linux-hardware.org/?probe=2cd1d2f51f) | Feb 03, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [13bdc2b06c](https://linux-hardware.org/?probe=13bdc2b06c) | Feb 03, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [866e97ab12](https://linux-hardware.org/?probe=866e97ab12) | Feb 03, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [9cabffbc86](https://linux-hardware.org/?probe=9cabffbc86) | Feb 03, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [17b77b89e5](https://linux-hardware.org/?probe=17b77b89e5) | Feb 03, 2023 |
| Lenovo        | ThinkPad T420s 4173CTO      | Notebook    | [232ff7a382](https://linux-hardware.org/?probe=232ff7a382) | Feb 02, 2023 |
| HP            | 212B                        | Desktop     | [cb1e6fa666](https://linux-hardware.org/?probe=cb1e6fa666) | Feb 02, 2023 |
| HP            | 212B                        | Desktop     | [e3e8d72420](https://linux-hardware.org/?probe=e3e8d72420) | Feb 02, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [687b1ec2d7](https://linux-hardware.org/?probe=687b1ec2d7) | Feb 02, 2023 |
| Dell          | Latitude 7320 Detachable    | Tablet      | [7560429d05](https://linux-hardware.org/?probe=7560429d05) | Feb 02, 2023 |
| Gigabyte      | Z77M-D3H-MVP                | Desktop     | [9b2f47d039](https://linux-hardware.org/?probe=9b2f47d039) | Feb 02, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [c7b6222f08](https://linux-hardware.org/?probe=c7b6222f08) | Feb 02, 2023 |
| Dell          | Latitude E6520              | Notebook    | [548b13cd43](https://linux-hardware.org/?probe=548b13cd43) | Feb 02, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [465114aa14](https://linux-hardware.org/?probe=465114aa14) | Feb 01, 2023 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [b0697611f6](https://linux-hardware.org/?probe=b0697611f6) | Feb 01, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [99127d4bed](https://linux-hardware.org/?probe=99127d4bed) | Feb 01, 2023 |
| Acer          | Predator PH315-52           | Notebook    | [b1c77eb9c7](https://linux-hardware.org/?probe=b1c77eb9c7) | Jan 31, 2023 |
| ASRock        | AD2700-ITX                  | Desktop     | [2f14c18867](https://linux-hardware.org/?probe=2f14c18867) | Jan 31, 2023 |
| Acer          | MCP73VE NVIDIA MCP73        | Desktop     | [840102fa91](https://linux-hardware.org/?probe=840102fa91) | Jan 31, 2023 |
| ASUSTek       | X550LC                      | Notebook    | [4c50999862](https://linux-hardware.org/?probe=4c50999862) | Jan 30, 2023 |
| ASUSTek       | X550LC                      | Notebook    | [41d606bbe8](https://linux-hardware.org/?probe=41d606bbe8) | Jan 30, 2023 |
| Dell          | 0D6H9T A00                  | Desktop     | [2c34aba28a](https://linux-hardware.org/?probe=2c34aba28a) | Jan 30, 2023 |
| Dell          | Inspiron 5770               | Notebook    | [b5612c2501](https://linux-hardware.org/?probe=b5612c2501) | Jan 29, 2023 |
| Dell          | Latitude 5400               | Notebook    | [80651273e4](https://linux-hardware.org/?probe=80651273e4) | Jan 29, 2023 |
| Dell          | Latitude 5400               | Notebook    | [eb97e73f08](https://linux-hardware.org/?probe=eb97e73f08) | Jan 29, 2023 |
| ASUSTek       | PRIME B560M-K               | Desktop     | [c74b6b90f0](https://linux-hardware.org/?probe=c74b6b90f0) | Jan 28, 2023 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [684748c9b4](https://linux-hardware.org/?probe=684748c9b4) | Jan 28, 2023 |
| MSI           | TRX40 PRO WIFI              | Desktop     | [d9508d5b22](https://linux-hardware.org/?probe=d9508d5b22) | Jan 27, 2023 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [06086e6112](https://linux-hardware.org/?probe=06086e6112) | Jan 27, 2023 |
| Apple         | MacBook8,1                  | Notebook    | [02cd28549c](https://linux-hardware.org/?probe=02cd28549c) | Jan 27, 2023 |
| ASRock        | AD2700-ITX                  | Desktop     | [7b711bee4f](https://linux-hardware.org/?probe=7b711bee4f) | Jan 26, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [4213c95d3d](https://linux-hardware.org/?probe=4213c95d3d) | Jan 26, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [b44aa465bc](https://linux-hardware.org/?probe=b44aa465bc) | Jan 26, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [fab7cead8c](https://linux-hardware.org/?probe=fab7cead8c) | Jan 26, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 D... | Notebook    | [d2a46bd14a](https://linux-hardware.org/?probe=d2a46bd14a) | Jan 26, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [b7759508d9](https://linux-hardware.org/?probe=b7759508d9) | Jan 26, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [72f2c3fddc](https://linux-hardware.org/?probe=72f2c3fddc) | Jan 26, 2023 |
| Panasonic     | FZ55-2                      | Notebook    | [dd9ddb12b6](https://linux-hardware.org/?probe=dd9ddb12b6) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [26abf66da5](https://linux-hardware.org/?probe=26abf66da5) | Jan 25, 2023 |
| Acer          | Aspire A315-22              | Notebook    | [7c048a8058](https://linux-hardware.org/?probe=7c048a8058) | Jan 24, 2023 |
| MeLE          | Rev GMLR1                   | Mini pc     | [1f294d6a67](https://linux-hardware.org/?probe=1f294d6a67) | Jan 24, 2023 |
| Pegatron      | 2AEE                        | Desktop     | [1c59133176](https://linux-hardware.org/?probe=1c59133176) | Jan 24, 2023 |
| ASUSTek       | PRIME Z690-A                | Desktop     | [ea5c2d01c2](https://linux-hardware.org/?probe=ea5c2d01c2) | Jan 24, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [c2226035ce](https://linux-hardware.org/?probe=c2226035ce) | Jan 24, 2023 |
| Dell          | 0X2MKR A00                  | All in one  | [5b29ed7213](https://linux-hardware.org/?probe=5b29ed7213) | Jan 23, 2023 |
| HP            | 8860 A                      | Desktop     | [ffb17b2c42](https://linux-hardware.org/?probe=ffb17b2c42) | Jan 23, 2023 |
| Alienware     | 15 R4                       | Notebook    | [8833335118](https://linux-hardware.org/?probe=8833335118) | Jan 23, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [447e624609](https://linux-hardware.org/?probe=447e624609) | Jan 22, 2023 |
| ASUSTek       | Z87-EXPERT                  | Desktop     | [852add0d4b](https://linux-hardware.org/?probe=852add0d4b) | Jan 22, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [223ab1f016](https://linux-hardware.org/?probe=223ab1f016) | Jan 22, 2023 |
| Lenovo        | ThinkPad X250 20CLS2JV01    | Notebook    | [932148f478](https://linux-hardware.org/?probe=932148f478) | Jan 21, 2023 |
| Intel         | NUC11ATBPE M49844-202       | Mini pc     | [74d7964357](https://linux-hardware.org/?probe=74d7964357) | Jan 21, 2023 |
| Dell          | XPS 9315                    | Notebook    | [9dfb19b7c1](https://linux-hardware.org/?probe=9dfb19b7c1) | Jan 21, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [46a3691da9](https://linux-hardware.org/?probe=46a3691da9) | Jan 21, 2023 |
| Dell          | Latitude 5300               | Notebook    | [e8c4218110](https://linux-hardware.org/?probe=e8c4218110) | Jan 21, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [bd601f83d3](https://linux-hardware.org/?probe=bd601f83d3) | Jan 21, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [28b4d041ad](https://linux-hardware.org/?probe=28b4d041ad) | Jan 20, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [1b41330a7e](https://linux-hardware.org/?probe=1b41330a7e) | Jan 20, 2023 |
| ASUSTek       | Z87-EXPERT                  | Desktop     | [ff72c387c7](https://linux-hardware.org/?probe=ff72c387c7) | Jan 20, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [ead0a07135](https://linux-hardware.org/?probe=ead0a07135) | Jan 20, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [1a80b30106](https://linux-hardware.org/?probe=1a80b30106) | Jan 20, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [03e73c44b7](https://linux-hardware.org/?probe=03e73c44b7) | Jan 20, 2023 |
| Apple         | MacBookPro14,3              | Notebook    | [82a49878eb](https://linux-hardware.org/?probe=82a49878eb) | Jan 19, 2023 |
| ASUSTek       | Z87-EXPERT                  | Desktop     | [91a963e420](https://linux-hardware.org/?probe=91a963e420) | Jan 19, 2023 |
| AZW           | SER V01                     | Mini pc     | [b209807db5](https://linux-hardware.org/?probe=b209807db5) | Jan 19, 2023 |
| ASUSTek       | PRIME Z690-A                | Desktop     | [ed9e94399a](https://linux-hardware.org/?probe=ed9e94399a) | Jan 18, 2023 |
| Lenovo        | 0B98401 WIN                 | Desktop     | [8d4e5b4499](https://linux-hardware.org/?probe=8d4e5b4499) | Jan 18, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [9a7659a260](https://linux-hardware.org/?probe=9a7659a260) | Jan 18, 2023 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [c7f31be903](https://linux-hardware.org/?probe=c7f31be903) | Jan 18, 2023 |
| Gigabyte      | B650M GAMING X AX           | Desktop     | [fb01eafa41](https://linux-hardware.org/?probe=fb01eafa41) | Jan 18, 2023 |
| Dell          | Precision 3561              | Notebook    | [9528d74be6](https://linux-hardware.org/?probe=9528d74be6) | Jan 18, 2023 |
| Dell          | Precision 3561              | Notebook    | [5f23addbde](https://linux-hardware.org/?probe=5f23addbde) | Jan 18, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [16be0552b2](https://linux-hardware.org/?probe=16be0552b2) | Jan 17, 2023 |
| Lenovo        | ThinkPad X230 2325CW1       | Notebook    | [44a8ae0b56](https://linux-hardware.org/?probe=44a8ae0b56) | Jan 17, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [d87fb3cf65](https://linux-hardware.org/?probe=d87fb3cf65) | Jan 17, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [564482477e](https://linux-hardware.org/?probe=564482477e) | Jan 17, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Australia/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 438       | 11.65%  |
| Ubuntu 18.04       | 173       | 4.6%    |
| Ubuntu 22.04       | 171       | 4.55%   |
| Debian 11          | 106       | 2.82%   |
| Pop!_OS 22.04      | 103       | 2.74%   |
| Linux Mint 20.3    | 77        | 2.05%   |
| OpenMandriva 4.3   | 74        | 1.97%   |
| Arch Rolling       | 73        | 1.94%   |
| KDE neon 20.04     | 71        | 1.89%   |
| Zorin 16           | 70        | 1.86%   |
| Fedora 36          | 65        | 1.73%   |
| Pop!_OS 21.04      | 64        | 1.7%    |
| Fedora 38          | 63        | 1.68%   |
| OpenMandriva 4.2   | 56        | 1.49%   |
| Pop!_OS 20.04      | 51        | 1.36%   |
| Fedora 37          | 51        | 1.36%   |
| Linux Mint 21.1    | 50        | 1.33%   |
| Linux Mint 20.2    | 49        | 1.3%    |
| Pop!_OS 20.10      | 48        | 1.28%   |
| Manjaro            | 48        | 1.28%   |
| Ubuntu 21.10       | 46        | 1.22%   |
| ArcoLinux Rolling  | 46        | 1.22%   |
| Arch               | 44        | 1.17%   |
| Linux Mint 20.1    | 42        | 1.12%   |
| Fedora 35          | 42        | 1.12%   |
| Ubuntu 19.04       | 41        | 1.09%   |
| Fedora 33          | 41        | 1.09%   |
| Ubuntu 20.10       | 39        | 1.04%   |
| Fedora 34          | 38        | 1.01%   |
| Ubuntu 21.04       | 37        | 0.98%   |
| Ubuntu 19.10       | 37        | 0.98%   |
| Linux Mint 19.3    | 36        | 0.96%   |
| OpenMandriva 23.03 | 33        | 0.88%   |
| Linux Mint 20      | 33        | 0.88%   |
| OpenMandriva 23.01 | 31        | 0.82%   |
| Xubuntu 18.04      | 30        | 0.8%    |
| Pop!_OS 21.10      | 30        | 0.8%    |
| Xubuntu 20.04      | 29        | 0.77%   |
| Ubuntu 23.04       | 29        | 0.77%   |
| Ubuntu 22.10       | 29        | 0.77%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1016      | 29.02%  |
| Linux Mint    | 326       | 9.31%   |
| Pop!_OS       | 283       | 8.08%   |
| Fedora        | 282       | 8.05%   |
| OpenMandriva  | 229       | 6.54%   |
| Debian        | 172       | 4.91%   |
| Arch          | 116       | 3.31%   |
| Zorin         | 104       | 2.97%   |
| Manjaro       | 103       | 2.94%   |
| KDE neon      | 99        | 2.83%   |
| Xubuntu       | 86        | 2.46%   |
| Kubuntu       | 74        | 2.11%   |
| ArcoLinux     | 47        | 1.34%   |
| Elementary    | 39        | 1.11%   |
| openSUSE      | 36        | 1.03%   |
| Gentoo        | 34        | 0.97%   |
| Kali          | 32        | 0.91%   |
| ROSA          | 29        | 0.83%   |
| Ubuntu MATE   | 27        | 0.77%   |
| Clear Linux   | 25        | 0.71%   |
| Lubuntu       | 23        | 0.66%   |
| ClearOS       | 23        | 0.66%   |
| EndeavourOS   | 19        | 0.54%   |
| BlackPanther  | 19        | 0.54%   |
| MX            | 18        | 0.51%   |
| Endless       | 18        | 0.51%   |
| LMDE          | 16        | 0.46%   |
| Ubuntu Unity  | 15        | 0.43%   |
| SteamOS       | 13        | 0.37%   |
| Parrot        | 13        | 0.37%   |
| CentOS        | 12        | 0.34%   |
| Ubuntu Budgie | 11        | 0.31%   |
| Raspbian      | 10        | 0.29%   |
| Nobara        | 9         | 0.26%   |
| Feren OS      | 8         | 0.23%   |
| LinuxFX       | 7         | 0.2%    |
| Rocky Linux   | 6         | 0.17%   |
| Reborn OS     | 6         | 0.17%   |
| Xero          | 5         | 0.14%   |
| Solus         | 5         | 0.14%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 71        | 1.63%   |
| 5.4.0-42-generic         | 64        | 1.47%   |
| 5.10.14-desktop-1omv4002 | 52        | 1.19%   |
| 6.2.6-desktop-1omv2390   | 31        | 0.71%   |
| 5.4.0-40-generic         | 30        | 0.69%   |
| 5.15.0-56-generic        | 30        | 0.69%   |
| 5.11.0-7620-generic      | 30        | 0.69%   |
| 6.1.1-desktop-1omv2290   | 29        | 0.66%   |
| 5.4.0-58-generic         | 29        | 0.66%   |
| 5.4.0-48-generic         | 27        | 0.62%   |
| 5.15.0-58-generic        | 25        | 0.57%   |
| 5.15.0-52-generic        | 25        | 0.57%   |
| 5.4.0-26-generic         | 24        | 0.55%   |
| 5.3.0-46-generic         | 24        | 0.55%   |
| 6.2.6-76060206-generic   | 23        | 0.53%   |
| 5.4.0-52-generic         | 23        | 0.53%   |
| 5.11.0-37-generic        | 23        | 0.53%   |
| 5.4.0-29-generic         | 22        | 0.5%    |
| 5.3.0-40-generic         | 22        | 0.5%    |
| 5.3.0-28-generic         | 22        | 0.5%    |
| 5.17.5-76051705-generic  | 21        | 0.48%   |
| 5.15.0-48-generic        | 21        | 0.48%   |
| 6.2.0-20-generic         | 20        | 0.46%   |
| 5.11.0-27-generic        | 20        | 0.46%   |
| 5.4.0-7634-generic       | 19        | 0.44%   |
| 5.15.0-46-generic        | 19        | 0.44%   |
| 6.4.11-desktop-1omv2390  | 18        | 0.41%   |
| 5.4.0-74-generic         | 18        | 0.41%   |
| 5.4.0-47-generic         | 18        | 0.41%   |
| 5.19.0-38-generic        | 17        | 0.39%   |
| 5.13.0-7620-generic      | 17        | 0.39%   |
| 6.0.12-76060006-generic  | 16        | 0.37%   |
| 5.8.0-7630-generic       | 16        | 0.37%   |
| 5.8.0-44-generic         | 16        | 0.37%   |
| 5.4.0-91-generic         | 16        | 0.37%   |
| 5.4.0-65-generic         | 16        | 0.37%   |
| 5.15.0-41-generic        | 16        | 0.37%   |
| 5.13.0-40-generic        | 16        | 0.37%   |
| 4.15.0-99-generic        | 16        | 0.37%   |
| 5.8.0-7642-generic       | 15        | 0.34%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 574       | 14.21%  |
| 5.15.0  | 303       | 7.5%    |
| 5.11.0  | 228       | 5.65%   |
| 5.13.0  | 192       | 4.75%   |
| 5.8.0   | 181       | 4.48%   |
| 4.15.0  | 162       | 4.01%   |
| 5.19.0  | 134       | 3.32%   |
| 5.3.0   | 128       | 3.17%   |
| 5.10.0  | 109       | 2.7%    |
| 5.0.0   | 86        | 2.13%   |
| 5.16.7  | 72        | 1.78%   |
| 4.18.0  | 65        | 1.61%   |
| 6.2.6   | 56        | 1.39%   |
| 6.2.0   | 54        | 1.34%   |
| 5.10.14 | 52        | 1.29%   |
| 6.1.1   | 36        | 0.89%   |
| 4.19.0  | 36        | 0.89%   |
| 5.17.5  | 31        | 0.77%   |
| 3.10.0  | 30        | 0.74%   |
| 6.1.0   | 24        | 0.59%   |
| 6.4.11  | 23        | 0.57%   |
| 6.0.12  | 22        | 0.54%   |
| 6.0.0   | 21        | 0.52%   |
| 5.18.0  | 15        | 0.37%   |
| 5.14.0  | 15        | 0.37%   |
| 6.0.7   | 14        | 0.35%   |
| 5.16.11 | 14        | 0.35%   |
| 5.18.10 | 13        | 0.32%   |
| 5.16.0  | 13        | 0.32%   |
| 4.4.0   | 13        | 0.32%   |
| 6.4.6   | 12        | 0.3%    |
| 5.6.14  | 11        | 0.27%   |
| 5.17.0  | 11        | 0.27%   |
| 4.18.16 | 11        | 0.27%   |
| 6.4.10  | 10        | 0.25%   |
| 6.0.6   | 10        | 0.25%   |
| 5.9.16  | 10        | 0.25%   |
| 5.18.12 | 10        | 0.25%   |
| 5.15.11 | 10        | 0.25%   |
| 5.13.13 | 10        | 0.25%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 626       | 15.98%  |
| 5.15    | 414       | 10.57%  |
| 5.11    | 267       | 6.82%   |
| 5.13    | 238       | 6.08%   |
| 5.8     | 228       | 5.82%   |
| 5.10    | 223       | 5.69%   |
| 5.19    | 182       | 4.65%   |
| 4.15    | 162       | 4.14%   |
| 6.2     | 156       | 3.98%   |
| 5.16    | 154       | 3.93%   |
| 5.3     | 143       | 3.65%   |
| 6.1     | 129       | 3.29%   |
| 6.0     | 109       | 2.78%   |
| 5.0     | 95        | 2.43%   |
| 6.4     | 85        | 2.17%   |
| 5.17    | 83        | 2.12%   |
| 5.18    | 80        | 2.04%   |
| 4.18    | 78        | 1.99%   |
| 6.3     | 59        | 1.51%   |
| 5.14    | 50        | 1.28%   |
| 5.6     | 46        | 1.17%   |
| 5.12    | 46        | 1.17%   |
| 4.19    | 46        | 1.17%   |
| 5.9     | 38        | 0.97%   |
| 4.9     | 30        | 0.77%   |
| 3.10    | 30        | 0.77%   |
| 5.5     | 26        | 0.66%   |
| 5.7     | 25        | 0.64%   |
| 5.2     | 17        | 0.43%   |
| 4.4     | 14        | 0.36%   |
| 5.1     | 9         | 0.23%   |
| 6.5     | 6         | 0.15%   |
| 4.1     | 4         | 0.1%    |
| 4.20    | 3         | 0.08%   |
| 4.14    | 3         | 0.08%   |
| 4.13    | 3         | 0.08%   |
| 3.16    | 2         | 0.05%   |
| 5       | 1         | 0.03%   |
| 4.8     | 1         | 0.03%   |
| 4.17    | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 3227      | 97.05%  |
| i686    | 50        | 1.5%    |
| aarch64 | 29        | 0.87%   |
| armv7l  | 13        | 0.39%   |
| riscv64 | 2         | 0.06%   |
| i586    | 2         | 0.06%   |
| armv6l  | 1         | 0.03%   |
| Unknown | 1         | 0.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 1535      | 43.6%   |
| KDE5             | 577       | 16.39%  |
| Unknown          | 401       | 11.39%  |
| X-Cinnamon       | 279       | 7.92%   |
| XFCE             | 250       | 7.1%    |
| KDE              | 100       | 2.84%   |
| MATE             | 99        | 2.81%   |
| Cinnamon         | 63        | 1.79%   |
| Pantheon         | 37        | 1.05%   |
| LXQt             | 28        | 0.8%    |
| Unity            | 20        | 0.57%   |
| LXDE             | 19        | 0.54%   |
| Budgie           | 19        | 0.54%   |
| KDE4             | 18        | 0.51%   |
| i3               | 18        | 0.51%   |
| Deepin           | 8         | 0.23%   |
| awesome          | 8         | 0.23%   |
| GNOME Classic    | 7         | 0.2%    |
| Openbox          | 6         | 0.17%   |
| GNOME Flashback  | 4         | 0.11%   |
| xmonad           | 3         | 0.09%   |
| BunsenLabs       | 3         | 0.09%   |
| bspwm            | 3         | 0.09%   |
| qtile            | 2         | 0.06%   |
| Hyprland         | 2         | 0.06%   |
| DWM              | 2         | 0.06%   |
| Trinity          | 1         | 0.03%   |
| sway             | 1         | 0.03%   |
| pop              | 1         | 0.03%   |
| Phosh:GNOME      | 1         | 0.03%   |
| lightdm-xsession | 1         | 0.03%   |
| LeftWM           | 1         | 0.03%   |
| icewm            | 1         | 0.03%   |
| herbstluftwm     | 1         | 0.03%   |
| GNUstep          | 1         | 0.03%   |
| dusk             | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 2600      | 75.38%  |
| Wayland | 538       | 15.6%   |
| Unknown | 184       | 5.33%   |
| Tty     | 126       | 3.65%   |
| Web     | 1         | 0.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1820      | 52.37%  |
| SDDM    | 495       | 14.24%  |
| GDM     | 356       | 10.24%  |
| LightDM | 353       | 10.16%  |
| GDM3    | 331       | 9.53%   |
| TDM     | 85        | 2.45%   |
| KDM     | 17        | 0.49%   |
| SLiM    | 6         | 0.17%   |
| LXDM    | 5         | 0.14%   |
| XDM     | 4         | 0.12%   |
| Ly      | 2         | 0.06%   |
| GREETD  | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang         | Computers | Percent |
|--------------|-----------|---------|
| en_AU        | 2417      | 70.18%  |
| en_US        | 535       | 15.53%  |
| Unknown      | 327       | 9.49%   |
| C            | 74        | 2.15%   |
| en_GB        | 63        | 1.83%   |
| C.UTF8       | 6         | 0.17%   |
| POSIX        | 4         | 0.12%   |
| zh_CN        | 3         | 0.09%   |
| de_DE        | 3         | 0.09%   |
| en_CA        | 2         | 0.06%   |
| ru_RU        | 1         | 0.03%   |
| it_IT        | 1         | 0.03%   |
| fr_FR        | 1         | 0.03%   |
| es_ES        | 1         | 0.03%   |
| en_US.utf-8  | 1         | 0.03%   |
| en_IN        | 1         | 0.03%   |
| en_GB.UTF-12 | 1         | 0.03%   |
| en_BW        | 1         | 0.03%   |
| en_AU.UFT-8  | 1         | 0.03%   |
| en-AU        | 1         | 0.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 1753      | 51.38%  |
| EFI  | 1659      | 48.62%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 2501      | 73.04%  |
| Btrfs    | 345       | 10.08%  |
| Overlay  | 245       | 7.16%   |
| Unknown  | 100       | 2.92%   |
| Xfs      | 95        | 2.77%   |
| Tmpfs    | 62        | 1.81%   |
| Zfs      | 50        | 1.46%   |
| Ext2     | 10        | 0.29%   |
| Ext3     | 5         | 0.15%   |
| XXXXXXX  | 4         | 0.12%   |
| F2fs     | 4         | 0.12%   |
| Reiserfs | 1         | 0.03%   |
| Jfs      | 1         | 0.03%   |
| Aufs     | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1863      | 54.36%  |
| GPT     | 1228      | 35.83%  |
| MBR     | 336       | 9.8%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2877      | 84.47%  |
| Yes       | 529       | 15.53%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2513      | 73.87%  |
| Yes       | 889       | 26.13%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 484       | 14.58%  |
| Hewlett-Packard         | 430       | 12.96%  |
| Dell                    | 429       | 12.93%  |
| Gigabyte Technology     | 391       | 11.78%  |
| Lenovo                  | 351       | 10.58%  |
| MSI                     | 216       | 6.51%   |
| Apple                   | 166       | 5%      |
| Acer                    | 163       | 4.91%   |
| ASRock                  | 126       | 3.8%    |
| Toshiba                 | 108       | 3.25%   |
| Intel                   | 94        | 2.83%   |
| Microsoft               | 38        | 1.14%   |
| Raspberry Pi Foundation | 29        | 0.87%   |
| Alienware               | 21        | 0.63%   |
| Unknown                 | 21        | 0.63%   |
| Samsung Electronics     | 16        | 0.48%   |
| AMI                     | 11        | 0.33%   |
| Sony                    | 10        | 0.3%    |
| Pegatron                | 10        | 0.3%    |
| Notebook                | 10        | 0.3%    |
| Google                  | 9         | 0.27%   |
| Timi                    | 8         | 0.24%   |
| Panasonic               | 8         | 0.24%   |
| Medion                  | 8         | 0.24%   |
| IT Channel Pty          | 7         | 0.21%   |
| IBM                     | 7         | 0.21%   |
| HUAWEI                  | 7         | 0.21%   |
| Valve                   | 6         | 0.18%   |
| Supermicro              | 6         | 0.18%   |
| Razer                   | 6         | 0.18%   |
| Metabox                 | 6         | 0.18%   |
| Kogan                   | 6         | 0.18%   |
| ECS                     | 6         | 0.18%   |
| System76                | 5         | 0.15%   |
| Shuttle                 | 5         | 0.15%   |
| Pine Microsystems       | 5         | 0.15%   |
| Intel Client Systems    | 5         | 0.15%   |
| Fanless Mini PC         | 5         | 0.15%   |
| Hardkernel              | 4         | 0.12%   |
| ReachingTech            | 3         | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| ASUS All Series                        | 35        | 1.05%   |
| Dell OptiPlex 9020                     | 29        | 0.87%   |
| Unknown                                | 25        | 0.75%   |
| HP Pavilion dv6                        | 18        | 0.54%   |
| HP Notebook                            | 13        | 0.39%   |
| MSI MS-7B89                            | 11        | 0.33%   |
| HP Pavilion g6                         | 11        | 0.33%   |
| Dell OptiPlex 780                      | 11        | 0.33%   |
| RPi Raspberry Pi                       | 10        | 0.3%    |
| Gigabyte 970A-D3P                      | 10        | 0.3%    |
| MSI MS-7817                            | 9         | 0.27%   |
| HP Pavilion 15                         | 9         | 0.27%   |
| Apple MacBookPro9,2                    | 9         | 0.27%   |
| Apple MacBookPro8,1                    | 9         | 0.27%   |
| Apple MacBookPro10,1                   | 9         | 0.27%   |
| Apple iMac12,2                         | 9         | 0.27%   |
| MSI MS-7C37                            | 8         | 0.24%   |
| Apple MacBookAir7,2                    | 8         | 0.24%   |
| Gigabyte X58A-UD3R                     | 7         | 0.21%   |
| Gigabyte B75M-D3H                      | 7         | 0.21%   |
| Dell XPS 15 9570                       | 7         | 0.21%   |
| Dell OptiPlex 990                      | 7         | 0.21%   |
| Valve Jupiter                          | 6         | 0.18%   |
| Toshiba Satellite L850                 | 6         | 0.18%   |
| MSI MS-7C94                            | 6         | 0.18%   |
| MSI MS-7C84                            | 6         | 0.18%   |
| MSI MS-7C02                            | 6         | 0.18%   |
| MSI MS-7B86                            | 6         | 0.18%   |
| Microsoft Surface Laptop 3             | 6         | 0.18%   |
| Dell XPS 13 9360                       | 6         | 0.18%   |
| Dell OptiPlex 9010                     | 6         | 0.18%   |
| ASUS ROG CROSSHAIR VIII DARK HERO      | 6         | 0.18%   |
| Acer ConceptD CN315-71P                | 6         | 0.18%   |
| Toshiba Satellite P750                 | 5         | 0.15%   |
| MSI MS-7A38                            | 5         | 0.15%   |
| Microsoft Surface Pro 3                | 5         | 0.15%   |
| Lenovo ThinkPad T470s W10DG 20JTS0HT00 | 5         | 0.15%   |
| HP Pavilion x360 Convertible           | 5         | 0.15%   |
| HP Compaq 8200 Elite SFF PC            | 5         | 0.15%   |
| Gigabyte Z77MX-D3H                     | 5         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 161       | 4.85%   |
| Acer Aspire         | 110       | 3.31%   |
| Dell OptiPlex       | 102       | 3.07%   |
| Dell Latitude       | 90        | 2.71%   |
| HP Pavilion         | 85        | 2.56%   |
| Toshiba Satellite   | 84        | 2.53%   |
| Dell Inspiron       | 79        | 2.38%   |
| ASUS PRIME          | 70        | 2.11%   |
| ASUS ROG            | 67        | 2.02%   |
| Dell XPS            | 66        | 1.99%   |
| HP EliteBook        | 56        | 1.69%   |
| Lenovo IdeaPad      | 48        | 1.45%   |
| HP Compaq           | 43        | 1.3%    |
| Dell Precision      | 41        | 1.24%   |
| Microsoft Surface   | 38        | 1.14%   |
| Lenovo Yoga         | 37        | 1.11%   |
| Lenovo ThinkCentre  | 37        | 1.11%   |
| ASUS TUF            | 37        | 1.11%   |
| ASUS All            | 35        | 1.05%   |
| HP ProBook          | 34        | 1.02%   |
| RPi Raspberry       | 29        | 0.87%   |
| HP Laptop           | 26        | 0.78%   |
| Unknown             | 25        | 0.75%   |
| Gigabyte X570       | 23        | 0.69%   |
| HP ENVY             | 21        | 0.63%   |
| Gigabyte B450       | 18        | 0.54%   |
| Dell Vostro         | 18        | 0.54%   |
| ASUS Zenbook        | 18        | 0.54%   |
| ASUS VivoBook       | 14        | 0.42%   |
| Toshiba PORTEGE     | 13        | 0.39%   |
| HP Notebook         | 13        | 0.39%   |
| Gigabyte B450M      | 13        | 0.39%   |
| Apple MacBookPro10  | 13        | 0.39%   |
| HP Spectre          | 12        | 0.36%   |
| Apple iMac12        | 12        | 0.36%   |
| MSI MS-7B89         | 11        | 0.33%   |
| Lenovo ThinkStation | 11        | 0.33%   |
| Lenovo IdeaPadFlex  | 11        | 0.33%   |
| HP ProDesk          | 11        | 0.33%   |
| Acer Swift          | 11        | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 316       | 9.52%   |
| 2018    | 305       | 9.19%   |
| 2020    | 284       | 8.56%   |
| 2012    | 272       | 8.2%    |
| 2013    | 246       | 7.41%   |
| 2011    | 241       | 7.26%   |
| 2017    | 213       | 6.42%   |
| 2021    | 206       | 6.21%   |
| 2014    | 195       | 5.88%   |
| 2016    | 193       | 5.82%   |
| 2015    | 176       | 5.3%    |
| 2010    | 163       | 4.91%   |
| 2009    | 122       | 3.68%   |
| 2008    | 121       | 3.65%   |
| 2022    | 108       | 3.25%   |
| 2007    | 59        | 1.78%   |
| Unknown | 42        | 1.27%   |
| 2023    | 20        | 0.6%    |
| 2006    | 20        | 0.6%    |
| 2005    | 13        | 0.39%   |
| 2004    | 2         | 0.06%   |
| 2003    | 1         | 0.03%   |
| 2002    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 1478      | 44.53%  |
| Notebook       | 1425      | 42.93%  |
| Convertible    | 116       | 3.5%    |
| Mini pc        | 90        | 2.71%   |
| All in one     | 83        | 2.5%    |
| Tablet         | 56        | 1.69%   |
| System on chip | 36        | 1.08%   |
| Server         | 29        | 0.87%   |
| Phone          | 3         | 0.09%   |
| Stick pc       | 3         | 0.09%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 3083      | 92.22%  |
| Enabled  | 260       | 7.78%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3304      | 99.55%  |
| Yes  | 15        | 0.45%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 832       | 24.46%  |
| 4.01-8.0        | 702       | 20.64%  |
| 8.01-16.0       | 564       | 16.58%  |
| 3.01-4.0        | 521       | 15.32%  |
| 32.01-64.0      | 432       | 12.7%   |
| 64.01-256.0     | 136       | 4%      |
| 1.01-2.0        | 105       | 3.09%   |
| 24.01-32.0      | 61        | 1.79%   |
| 2.01-3.0        | 21        | 0.62%   |
| 0.51-1.0        | 14        | 0.41%   |
| 0.01-0.5        | 7         | 0.21%   |
| More than 256.0 | 5         | 0.15%   |
| Unknown         | 1         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 1249      | 32.59%  |
| 2.01-3.0    | 969       | 25.29%  |
| 4.01-8.0    | 582       | 15.19%  |
| 3.01-4.0    | 506       | 13.2%   |
| 0.51-1.0    | 228       | 5.95%   |
| 8.01-16.0   | 194       | 5.06%   |
| 0.01-0.5    | 50        | 1.3%    |
| 16.01-24.0  | 30        | 0.78%   |
| 24.01-32.0  | 13        | 0.34%   |
| 32.01-64.0  | 4         | 0.1%    |
| 64.01-256.0 | 3         | 0.08%   |
| 0           | 2         | 0.05%   |
| Unknown     | 2         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1873      | 53.51%  |
| 2       | 853       | 24.37%  |
| 3       | 336       | 9.6%    |
| 4       | 196       | 5.6%    |
| 5       | 92        | 2.63%   |
| 6       | 47        | 1.34%   |
| 0       | 35        | 1%      |
| 7       | 25        | 0.71%   |
| 8       | 21        | 0.6%    |
| 9       | 9         | 0.26%   |
| 10      | 5         | 0.14%   |
| 13      | 3         | 0.09%   |
| 36      | 1         | 0.03%   |
| 14      | 1         | 0.03%   |
| 12      | 1         | 0.03%   |
| 11      | 1         | 0.03%   |
| Unknown | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2043      | 60.79%  |
| Yes       | 1318      | 39.21%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2880      | 86.51%  |
| No        | 449       | 13.49%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2485      | 73.98%  |
| No        | 874       | 26.02%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1961      | 58.14%  |
| No        | 1412      | 41.86%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| Australia | 3319      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Sydney         | 927       | 25.98%  |
| Melbourne      | 728       | 20.4%   |
| Brisbane       | 508       | 14.24%  |
| Perth          | 302       | 8.46%   |
| Adelaide       | 211       | 5.91%   |
| Canberra       | 78        | 2.19%   |
| Wahroonga      | 39        | 1.09%   |
| Hobart         | 33        | 0.92%   |
| Launceston     | 27        | 0.76%   |
| Alexandria     | 21        | 0.59%   |
| Gold Coast     | 19        | 0.53%   |
| Surry Hills    | 17        | 0.48%   |
| Geelong        | 16        | 0.45%   |
| Richmond       | 12        | 0.34%   |
| Newcastle      | 12        | 0.34%   |
| Lane Cove      | 12        | 0.34%   |
| Central Coast  | 12        | 0.34%   |
| Woolloongabba  | 11        | 0.31%   |
| Mitcham        | 11        | 0.31%   |
| Southport      | 10        | 0.28%   |
| Brighton       | 9         | 0.25%   |
| Wollongong     | 8         | 0.22%   |
| Traralgon      | 8         | 0.22%   |
| Townsville     | 8         | 0.22%   |
| Parramatta     | 7         | 0.2%    |
| North Sydney   | 7         | 0.2%    |
| Mandurah       | 7         | 0.2%    |
| Macquarie Park | 7         | 0.2%    |
| Artarmon       | 7         | 0.2%    |
| West End       | 6         | 0.17%   |
| Point Cook     | 6         | 0.17%   |
| Nyngan         | 6         | 0.17%   |
| Mount Waverley | 6         | 0.17%   |
| Geraldton      | 6         | 0.17%   |
| Spring Field   | 5         | 0.14%   |
| Ringwood East  | 5         | 0.14%   |
| Northcote      | 5         | 0.14%   |
| Mascot         | 5         | 0.14%   |
| Leinster       | 5         | 0.14%   |
| Hawthorn       | 5         | 0.14%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 960       | 1733   | 18.63%  |
| Seagate                     | 833       | 1594   | 16.16%  |
| WDC                         | 770       | 1489   | 14.94%  |
| Crucial                     | 282       | 425    | 5.47%   |
| Toshiba                     | 259       | 369    | 5.03%   |
| Kingston                    | 232       | 302    | 4.5%    |
| SanDisk                     | 215       | 283    | 4.17%   |
| Unknown                     | 196       | 285    | 3.8%    |
| Intel                       | 186       | 340    | 3.61%   |
| Hitachi                     | 156       | 252    | 3.03%   |
| SK hynix                    | 106       | 131    | 2.06%   |
| Apple                       | 93        | 125    | 1.8%    |
| HGST                        | 79        | 118    | 1.53%   |
| Micron Technology           | 74        | 95     | 1.44%   |
| Micron/Crucial Technology   | 63        | 87     | 1.22%   |
| Phison                      | 37        | 56     | 0.72%   |
| OCZ                         | 37        | 54     | 0.72%   |
| SPCC                        | 34        | 42     | 0.66%   |
| KIOXIA                      | 33        | 36     | 0.64%   |
| A-DATA Technology           | 31        | 42     | 0.6%    |
| Phison Electronics          | 24        | 33     | 0.47%   |
| JMicron Technology          | 22        | 26     | 0.43%   |
| Corsair                     | 21        | 35     | 0.41%   |
| LITEONIT                    | 20        | 28     | 0.39%   |
| LITEON                      | 20        | 35     | 0.39%   |
| Kingston Technology Company | 17        | 21     | 0.33%   |
| KingSpec                    | 17        | 37     | 0.33%   |
| Fujitsu                     | 17        | 21     | 0.33%   |
| Unknown                     | 17        | 19     | 0.33%   |
| Transcend                   | 14        | 21     | 0.27%   |
| Patriot                     | 14        | 21     | 0.27%   |
| Gigabyte Technology         | 14        | 17     | 0.27%   |
| LaCie                       | 13        | 20     | 0.25%   |
| ASMT                        | 13        | 21     | 0.25%   |
| China                       | 12        | 14     | 0.23%   |
| Silicon Motion              | 11        | 22     | 0.21%   |
| Maxtor                      | 11        | 14     | 0.21%   |
| Hewlett-Packard             | 9         | 13     | 0.17%   |
| XPG                         | 8         | 9      | 0.16%   |
| Team                        | 8         | 12     | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB                           | 62        | 1.04%   |
| Samsung SSD 850 EVO 250GB                           | 51        | 0.86%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 50        | 0.84%   |
| Crucial CT500MX500SSD1 500GB                        | 40        | 0.67%   |
| Crucial CT240BX500SSD1 240GB                        | 38        | 0.64%   |
| Unknown MMC Card  64GB                              | 37        | 0.62%   |
| Unknown MMC Card  32GB                              | 37        | 0.62%   |
| Samsung SSD 850 EVO 500GB                           | 37        | 0.62%   |
| Seagate ST1000DM010-2EP102 1TB                      | 35        | 0.59%   |
| Seagate ST500DM002-1BD142 500GB                     | 34        | 0.57%   |
| Seagate Expansion Desk 2TB                          | 34        | 0.57%   |
| Seagate Expansion 2TB                               | 34        | 0.57%   |
| Seagate ST4000DM004-2CV104 4TB                      | 33        | 0.56%   |
| Seagate ST2000DM008-2FR102 2TB                      | 33        | 0.56%   |
| Kingston SA400S37240G 240GB SSD                     | 33        | 0.56%   |
| Samsung SSD 860 EVO 1TB                             | 32        | 0.54%   |
| Samsung NVMe SSD Drive 1TB                          | 32        | 0.54%   |
| Seagate ST2000DM001-1ER164 2TB                      | 31        | 0.52%   |
| Samsung NVMe SSD Drive 512GB                        | 28        | 0.47%   |
| Samsung NVMe SSD Drive 500GB                        | 28        | 0.47%   |
| Crucial CT480BX500SSD1 480GB                        | 27        | 0.45%   |
| Seagate ST2000DM001-1CH164 2TB                      | 26        | 0.44%   |
| Crucial CT1000MX500SSD1 1TB                         | 26        | 0.44%   |
| Seagate ST3500418AS 500GB                           | 25        | 0.42%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 24        | 0.4%    |
| Toshiba MQ01ABD100 1TB                              | 23        | 0.39%   |
| Seagate ST31000528AS 1TB                            | 23        | 0.39%   |
| Seagate ST2000DL003-9VT166 2TB                      | 23        | 0.39%   |
| Kingston SV300S37A120G 120GB SSD                    | 23        | 0.39%   |
| Crucial CT1000BX500SSD1 1TB                         | 23        | 0.39%   |
| Samsung SSD 860 QVO 1TB                             | 22        | 0.37%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 22        | 0.37%   |
| Kingston SA400S37480G 480GB SSD                     | 22        | 0.37%   |
| Kingston SA400S37120G 120GB SSD                     | 22        | 0.37%   |
| Unknown SD/MMC/MS PRO 1GB                           | 21        | 0.35%   |
| WDC WD20EARX-00PASB0 2TB                            | 20        | 0.34%   |
| Seagate ST2000DM006-2DM164 2TB                      | 20        | 0.34%   |
| Seagate ST1000LM035-1RK172 1TB                      | 20        | 0.34%   |
| Samsung SSD 970 EVO Plus 500GB                      | 20        | 0.34%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 19        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 818       | 1550   | 39.54%  |
| WDC                 | 628       | 1238   | 30.35%  |
| Toshiba             | 175       | 262    | 8.46%   |
| Hitachi             | 155       | 250    | 7.49%   |
| Samsung Electronics | 95        | 243    | 4.59%   |
| HGST                | 77        | 116    | 3.72%   |
| Apple               | 26        | 32     | 1.26%   |
| Unknown             | 23        | 34     | 1.11%   |
| Fujitsu             | 16        | 20     | 0.77%   |
| Maxtor              | 11        | 14     | 0.53%   |
| LaCie               | 10        | 16     | 0.48%   |
| ASMT                | 9         | 17     | 0.43%   |
| USB                 | 4         | 5      | 0.19%   |
| SABRENT             | 4         | 4      | 0.19%   |
| Hewlett-Packard     | 3         | 4      | 0.14%   |
| KESU                | 2         | 2      | 0.1%    |
| HGST HUS            | 2         | 2      | 0.1%    |
| External            | 2         | 2      | 0.1%    |
| USB3.0              | 1         | 2      | 0.05%   |
| QNAP                | 1         | 2      | 0.05%   |
| MaxDigital          | 1         | 1      | 0.05%   |
| IET                 | 1         | 1      | 0.05%   |
| IBM/Hitachi         | 1         | 1      | 0.05%   |
| HPE                 | 1         | 1      | 0.05%   |
| Hajaan              | 1         | 1      | 0.05%   |
| DAS                 | 1         | 1      | 0.05%   |
| AAPL                | 1         | 1      | 0.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 533       | 883    | 30.44%  |
| Crucial             | 245       | 378    | 13.99%  |
| Kingston            | 166       | 215    | 9.48%   |
| SanDisk             | 138       | 172    | 7.88%   |
| WDC                 | 125       | 172    | 7.14%   |
| Intel               | 93        | 196    | 5.31%   |
| Apple               | 48        | 53     | 2.74%   |
| OCZ                 | 37        | 54     | 2.11%   |
| SK hynix            | 36        | 43     | 2.06%   |
| SPCC                | 30        | 36     | 1.71%   |
| Micron Technology   | 29        | 34     | 1.66%   |
| Toshiba             | 27        | 38     | 1.54%   |
| LITEONIT            | 20        | 28     | 1.14%   |
| LITEON              | 18        | 33     | 1.03%   |
| A-DATA Technology   | 18        | 24     | 1.03%   |
| KingSpec            | 16        | 36     | 0.91%   |
| Transcend           | 14        | 21     | 0.8%    |
| Patriot             | 14        | 21     | 0.8%    |
| JMicron Technology  | 14        | 16     | 0.8%    |
| Corsair             | 14        | 28     | 0.8%    |
| Seagate             | 12        | 19     | 0.69%   |
| China               | 12        | 14     | 0.69%   |
| Gigabyte Technology | 8         | 8      | 0.46%   |
| TO Exter            | 7         | 7      | 0.4%    |
| Team                | 6         | 10     | 0.34%   |
| OWC                 | 6         | 17     | 0.34%   |
| Plextor             | 5         | 17     | 0.29%   |
| Lexar               | 4         | 4      | 0.23%   |
| KingFast            | 4         | 4      | 0.23%   |
| Vaseky              | 3         | 8      | 0.17%   |
| PNY                 | 3         | 3      | 0.17%   |
| ASMT                | 3         | 3      | 0.17%   |
| T-CREATE            | 2         | 2      | 0.11%   |
| NGFF                | 2         | 2      | 0.11%   |
| Hajaan              | 2         | 2      | 0.11%   |
| FORESEE             | 2         | 2      | 0.11%   |
| Apacer              | 2         | 3      | 0.11%   |
| 2.0TB               | 2         | 3      | 0.11%   |
| XPG                 | 1         | 1      | 0.06%   |
| WDC WDS2            | 1         | 1      | 0.06%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1674      | 3822   | 36.93%  |
| SSD     | 1511      | 2650   | 33.33%  |
| NVMe    | 1105      | 1733   | 24.38%  |
| MMC     | 174       | 243    | 3.84%   |
| Unknown | 69        | 97     | 1.52%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2483      | 6116   | 61.43%  |
| NVMe | 1105      | 1724   | 27.34%  |
| SAS  | 280       | 462    | 6.93%   |
| MMC  | 174       | 243    | 4.3%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1795      | 3410   | 51.42%  |
| 0.51-1.0   | 906       | 1592   | 25.95%  |
| 1.01-2.0   | 460       | 826    | 13.18%  |
| 3.01-4.0   | 133       | 278    | 3.81%   |
| 4.01-10.0  | 106       | 216    | 3.04%   |
| 2.01-3.0   | 84        | 141    | 2.41%   |
| 10.01-20.0 | 6         | 8      | 0.17%   |
| 0          | 1         | 1      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 804       | 22.3%   |
| 251-500        | 738       | 20.47%  |
| 501-1000       | 547       | 15.17%  |
| 1001-2000      | 333       | 9.24%   |
| More than 3000 | 303       | 8.4%    |
| 1-20           | 292       | 8.1%    |
| 51-100         | 241       | 6.69%   |
| 2001-3000      | 138       | 3.83%   |
| Unknown        | 108       | 3%      |
| 21-50          | 101       | 2.8%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1411      | 37.3%   |
| 21-50          | 630       | 16.65%  |
| 101-250        | 418       | 11.05%  |
| 51-100         | 385       | 10.18%  |
| 251-500        | 310       | 8.19%   |
| 501-1000       | 207       | 5.47%   |
| 1001-2000      | 139       | 3.67%   |
| More than 3000 | 117       | 3.09%   |
| Unknown        | 108       | 2.85%   |
| 2001-3000      | 56        | 1.48%   |
| 0              | 2         | 0.05%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Computers | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| Intel SSDSC2CT120A3 120GB               | 8         | 39     | 2.55%   |
| Seagate ST500DM002-1BD142 500GB         | 5         | 18     | 1.59%   |
| Seagate ST3500418AS 500GB               | 5         | 14     | 1.59%   |
| Hitachi HDS721010DLE630 1TB             | 5         | 7      | 1.59%   |
| Maxtor 6Y080L0 82GB                     | 4         | 6      | 1.27%   |
| Kingston SV300S37A120G 120GB SSD        | 4         | 4      | 1.27%   |
| WDC WD20EARX-00PASB0 2TB                | 3         | 3      | 0.96%   |
| WDC WD2002FAEX-007BA0 2TB               | 3         | 4      | 0.96%   |
| Seagate ST9500325AS 500GB               | 3         | 3      | 0.96%   |
| Seagate ST31000528AS 1TB                | 3         | 3      | 0.96%   |
| Seagate ST2000DM001-9YN164 2TB          | 3         | 3      | 0.96%   |
| Seagate ST2000DM001-1ER164 2TB          | 3         | 3      | 0.96%   |
| Seagate ST2000DM001-1CH164 2TB          | 3         | 3      | 0.96%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 3         | 4      | 0.96%   |
| Samsung Electronics HD501LJ 500GB       | 3         | 32     | 0.96%   |
| Maxtor 6L200M0 208GB                    | 3         | 4      | 0.96%   |
| Kingston RBU-SNS8350DES3128GP 128GB SSD | 3         | 3      | 0.96%   |
| HGST HTS725050A7E630 500GB              | 3         | 3      | 0.96%   |
| HGST HTS545050A7E680 500GB              | 3         | 4      | 0.96%   |
| Crucial CT525MX300SSD1 528GB            | 3         | 5      | 0.96%   |
| WDC WDS500G1X0E-00AFY0 500GB            | 2         | 2      | 0.64%   |
| WDC WD5000AVCS-632DY1 500GB             | 2         | 2      | 0.64%   |
| WDC WD30EZRX-00DC0B0 3TB                | 2         | 2      | 0.64%   |
| WDC WD20EFRX-68EUZN0 2TB                | 2         | 3      | 0.64%   |
| WDC WD20EARS-00J2GB0 2TB                | 2         | 3      | 0.64%   |
| WDC WD1600AVVS-63L2B0 160GB             | 2         | 5      | 0.64%   |
| WDC WD10EZEX-60ZF5A0 1TB                | 2         | 2      | 0.64%   |
| WDC WD10EZEX-60WN4A0 1TB                | 2         | 3      | 0.64%   |
| WDC WD10EFRX-68FYTN0 1TB                | 2         | 2      | 0.64%   |
| WDC WD10EARS-00Y5B1 1TB                 | 2         | 2      | 0.64%   |
| WDC WD10EADS-11M2B1 1TB                 | 2         | 2      | 0.64%   |
| WDC WD10EADS-00P8B0 1TB                 | 2         | 2      | 0.64%   |
| WDC WD1003FZEX-00K3CA0 1TB              | 2         | 3      | 0.64%   |
| Toshiba THNSNK128GCS8 SATA 128GB SSD    | 2         | 2      | 0.64%   |
| Toshiba MQ01ABF050 500GB                | 2         | 2      | 0.64%   |
| SK hynix HFS256G3AMNB-2200A 256GB SSD   | 2         | 2      | 0.64%   |
| Seagate ST9320423AS 320GB               | 2         | 3      | 0.64%   |
| Seagate ST500LT012-9WS142 500GB         | 2         | 4      | 0.64%   |
| Seagate ST500LT012-1DG142 500GB         | 2         | 2      | 0.64%   |
| Seagate ST500LM021-1KJ152 500GB         | 2         | 2      | 0.64%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                   | Computers | Drives | Percent |
|--------------------------|-----------|--------|---------|
| Seagate                  | 77        | 124    | 25.84%  |
| WDC                      | 59        | 99     | 19.8%   |
| Samsung Electronics      | 30        | 76     | 10.07%  |
| Hitachi                  | 23        | 27     | 7.72%   |
| Intel                    | 20        | 66     | 6.71%   |
| Toshiba                  | 14        | 18     | 4.7%    |
| Kingston                 | 12        | 12     | 4.03%   |
| HGST                     | 9         | 10     | 3.02%   |
| SanDisk                  | 7         | 7      | 2.35%   |
| Maxtor                   | 7         | 10     | 2.35%   |
| Crucial                  | 6         | 8      | 2.01%   |
| Fujitsu                  | 5         | 5      | 1.68%   |
| SK hynix                 | 4         | 4      | 1.34%   |
| Micron Technology        | 4         | 4      | 1.34%   |
| Corsair                  | 4         | 5      | 1.34%   |
| Apple                    | 3         | 3      | 1.01%   |
| Transcend                | 1         | 1      | 0.34%   |
| SPCC                     | 1         | 1      | 0.34%   |
| Realtek Semiconductor    | 1         | 2      | 0.34%   |
| OCZ                      | 1         | 1      | 0.34%   |
| Netac                    | 1         | 1      | 0.34%   |
| MaxDigital               | 1         | 1      | 0.34%   |
| KingSpec                 | 1         | 3      | 0.34%   |
| KingFast                 | 1         | 1      | 0.34%   |
| HPE                      | 1         | 1      | 0.34%   |
| Hewlett-Packard          | 1         | 2      | 0.34%   |
| Gigabyte Technology      | 1         | 1      | 0.34%   |
| Biwin Storage Technology | 1         | 1      | 0.34%   |
| ASMT                     | 1         | 1      | 0.34%   |
| A-DATA Technology        | 1         | 1      | 0.34%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 77        | 124    | 36.32%  |
| WDC                 | 58        | 96     | 27.36%  |
| Hitachi             | 23        | 27     | 10.85%  |
| Samsung Electronics | 15        | 60     | 7.08%   |
| Toshiba             | 12        | 16     | 5.66%   |
| HGST                | 9         | 10     | 4.25%   |
| Maxtor              | 7         | 10     | 3.3%    |
| Fujitsu             | 5         | 5      | 2.36%   |
| Apple               | 2         | 2      | 0.94%   |
| MaxDigital          | 1         | 1      | 0.47%   |
| HPE                 | 1         | 1      | 0.47%   |
| Hewlett-Packard     | 1         | 2      | 0.47%   |
| ASMT                | 1         | 1      | 0.47%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 188       | 355    | 68.61%  |
| SSD  | 72        | 123    | 26.28%  |
| NVMe | 14        | 18     | 5.11%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                         | Computers | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| WDC WD3200AAJS-40RYA0 320GB   | 1         | 1      | 33.33%  |
| Hitachi HDS721010DLE630 1TB   | 1         | 6      | 33.33%  |
| Apple HDD HTS541010A9E662 1TB | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 33.33%  |
| Hitachi | 1         | 6      | 33.33%  |
| Apple   | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2119      | 4901   | 58.39%  |
| Works    | 1242      | 3140   | 34.22%  |
| Malfunc  | 265       | 496    | 7.3%    |
| Failed   | 3         | 8      | 0.08%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2209      | 50.39%  |
| AMD                              | 643       | 14.67%  |
| Samsung Electronics              | 454       | 10.36%  |
| SanDisk                          | 124       | 2.83%   |
| Micron/Crucial Technology        | 101       | 2.3%    |
| Marvell Technology Group         | 99        | 2.26%   |
| ASMedia Technology               | 87        | 1.98%   |
| Kingston Technology Company      | 86        | 1.96%   |
| Phison Electronics               | 73        | 1.67%   |
| JMicron Technology               | 73        | 1.67%   |
| SK hynix                         | 71        | 1.62%   |
| Toshiba America Info Systems     | 58        | 1.32%   |
| Micron Technology                | 46        | 1.05%   |
| KIOXIA                           | 32        | 0.73%   |
| Nvidia                           | 29        | 0.66%   |
| ADATA Technology                 | 24        | 0.55%   |
| Silicon Motion                   | 21        | 0.48%   |
| LSI Logic / Symbios Logic        | 21        | 0.48%   |
| Apple                            | 19        | 0.43%   |
| Broadcom / LSI                   | 14        | 0.32%   |
| VIA Technologies                 | 12        | 0.27%   |
| Realtek Semiconductor            | 11        | 0.25%   |
| Seagate Technology               | 9         | 0.21%   |
| Integrated Technology Express    | 9         | 0.21%   |
| Solid State Storage Technology   | 7         | 0.16%   |
| Silicon Image                    | 6         | 0.14%   |
| Hewlett-Packard                  | 6         | 0.14%   |
| Lite-On Technology               | 5         | 0.11%   |
| Union Memory (Shenzhen)          | 4         | 0.09%   |
| MAXIO Technology (Hangzhou)      | 4         | 0.09%   |
| Adaptec                          | 4         | 0.09%   |
| ULi Electronics                  | 3         | 0.07%   |
| Silicon Integrated Systems [SiS] | 3         | 0.07%   |
| Shenzhen Longsys Electronics     | 3         | 0.07%   |
| Lenovo                           | 3         | 0.07%   |
| 3ware                            | 3         | 0.07%   |
| O2 Micro                         | 2         | 0.05%   |
| Biwin Storage Technology         | 2         | 0.05%   |
| Promise Technology               | 1         | 0.02%   |
| PMC-Sierra                       | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 447       | 8.78%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 229       | 4.5%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 173       | 3.4%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 132       | 2.59%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 124       | 2.44%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 110       | 2.16%   |
| AMD 400 Series Chipset SATA Controller                                                  | 107       | 2.1%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 99        | 1.95%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 90        | 1.77%   |
| Intel SATA Controller [RAID mode]                                                       | 87        | 1.71%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 79        | 1.55%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 76        | 1.49%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 72        | 1.41%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 72        | 1.41%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 69        | 1.36%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 69        | 1.36%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 66        | 1.3%    |
| AMD 500 Series Chipset SATA Controller                                                  | 65        | 1.28%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 62        | 1.22%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 62        | 1.22%   |
| Samsung NVMe SSD Controller 980                                                         | 60        | 1.18%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 59        | 1.16%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 57        | 1.12%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 57        | 1.12%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 53        | 1.04%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 51        | 1%      |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 48        | 0.94%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 42        | 0.83%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 38        | 0.75%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 37        | 0.73%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 37        | 0.73%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 36        | 0.71%   |
| Intel SSD 660P Series                                                                   | 35        | 0.69%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 35        | 0.69%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 34        | 0.67%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton2]                                              | 32        | 0.63%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 32        | 0.63%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 32        | 0.63%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 32        | 0.63%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 30        | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2372      | 55.15%  |
| NVMe | 1111      | 25.83%  |
| IDE  | 468       | 10.88%  |
| RAID | 317       | 7.37%   |
| SAS  | 23        | 0.53%   |
| SCSI | 10        | 0.23%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor        | Computers | Percent |
|---------------|-----------|---------|
| Intel         | 2530      | 76.23%  |
| AMD           | 743       | 22.39%  |
| ARM           | 43        | 1.3%    |
| sifive,u74-mc | 1         | 0.03%   |
| CentaurHauls  | 1         | 0.03%   |
| Unknown       | 1         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor       | 44        | 1.32%   |
| Intel Core i7-2600 CPU @ 3.40GHz        | 37        | 1.11%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 36        | 1.08%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 30        | 0.9%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 30        | 0.9%    |
| Intel Core i5-7200U CPU @ 2.50GHz       | 29        | 0.87%   |
| ARM Processor                           | 29        | 0.87%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 28        | 0.84%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 28        | 0.84%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 27        | 0.81%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 27        | 0.81%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 26        | 0.78%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 26        | 0.78%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 25        | 0.75%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 25        | 0.75%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 25        | 0.75%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 24        | 0.72%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 24        | 0.72%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 23        | 0.69%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 22        | 0.66%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 22        | 0.66%   |
| Intel Core i7-4770 CPU @ 3.40GHz        | 20        | 0.6%    |
| Intel Core i5-6300U CPU @ 2.40GHz       | 20        | 0.6%    |
| Intel Core i5-2520M CPU @ 2.50GHz       | 20        | 0.6%    |
| AMD Ryzen 9 5950X 16-Core Processor     | 20        | 0.6%    |
| AMD Ryzen 5 2600 Six-Core Processor     | 20        | 0.6%    |
| Intel Core i7-8750H CPU @ 2.20GHz       | 19        | 0.57%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 19        | 0.57%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 19        | 0.57%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 19        | 0.57%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 18        | 0.54%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 17        | 0.51%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 16        | 0.48%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 15        | 0.45%   |
| Intel Core i7-3770K CPU @ 3.50GHz       | 15        | 0.45%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 15        | 0.45%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 15        | 0.45%   |
| Intel Celeron CPU N3350 @ 1.10GHz       | 15        | 0.45%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 14        | 0.42%   |
| Intel Core i7-6700 CPU @ 3.40GHz        | 14        | 0.42%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 874       | 26.3%   |
| Intel Core i5           | 734       | 22.09%  |
| Other                   | 234       | 7.04%   |
| AMD Ryzen 5             | 193       | 5.81%   |
| AMD Ryzen 7             | 149       | 4.48%   |
| Intel Core i3           | 140       | 4.21%   |
| Intel Core 2 Duo        | 138       | 4.15%   |
| Intel Celeron           | 123       | 3.7%    |
| Intel Xeon              | 96        | 2.89%   |
| AMD Ryzen 9             | 79        | 2.38%   |
| Intel Pentium           | 50        | 1.5%    |
| AMD FX                  | 47        | 1.41%   |
| Intel Atom              | 32        | 0.96%   |
| AMD A6                  | 31        | 0.93%   |
| AMD A4                  | 28        | 0.84%   |
| AMD Ryzen 3             | 26        | 0.78%   |
| Intel Core 2 Quad       | 24        | 0.72%   |
| Intel Core 2            | 24        | 0.72%   |
| Intel Core i9           | 23        | 0.69%   |
| AMD A8                  | 22        | 0.66%   |
| Intel Pentium Dual-Core | 18        | 0.54%   |
| AMD E2                  | 16        | 0.48%   |
| AMD Phenom II X4        | 15        | 0.45%   |
| AMD A10                 | 15        | 0.45%   |
| ARM BCM                 | 12        | 0.36%   |
| AMD Ryzen Threadripper  | 12        | 0.36%   |
| Intel Core m3           | 10        | 0.3%    |
| AMD Ryzen 7 PRO         | 10        | 0.3%    |
| AMD Phenom II X6        | 10        | 0.3%    |
| AMD Athlon              | 9         | 0.27%   |
| Intel Pentium Dual      | 8         | 0.24%   |
| Intel Genuine           | 8         | 0.24%   |
| AMD E1                  | 8         | 0.24%   |
| Intel Pentium D         | 7         | 0.21%   |
| Intel Core M            | 6         | 0.18%   |
| Intel Pentium Silver    | 5         | 0.15%   |
| Intel Pentium 4         | 5         | 0.15%   |
| AMD Sempron             | 5         | 0.15%   |
| AMD Phenom II X2        | 5         | 0.15%   |
| AMD E                   | 5         | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 1300      | 39.06%  |
| 2       | 1101      | 33.08%  |
| 6       | 400       | 12.02%  |
| 8       | 255       | 7.66%   |
| 12      | 80        | 2.4%    |
| 1       | 60        | 1.8%    |
| 16      | 48        | 1.44%   |
| 10      | 26        | 0.78%   |
| 3       | 19        | 0.57%   |
| 14      | 18        | 0.54%   |
| 24      | 9         | 0.27%   |
| 32      | 4         | 0.12%   |
| Unknown | 4         | 0.12%   |
| 40      | 2         | 0.06%   |
| 128     | 1         | 0.03%   |
| 5       | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3267      | 98.4%   |
| 2       | 48        | 1.45%   |
| Unknown | 4         | 0.12%   |
| 4       | 1         | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2294      | 68.99%  |
| 1       | 1022      | 30.74%  |
| Unknown | 4         | 0.12%   |
| 4       | 3         | 0.09%   |
| 8       | 2         | 0.06%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3228      | 96.94%  |
| Unknown        | 72        | 2.16%   |
| 32-bit         | 23        | 0.69%   |
| 64-bit         | 7         | 0.21%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1064      | 30.58%  |
| 0x206a7    | 182       | 5.23%   |
| 0x306a9    | 167       | 4.8%    |
| 0x306c3    | 145       | 4.17%   |
| 0x1067a    | 95        | 2.73%   |
| 0x906ea    | 88        | 2.53%   |
| 0x506e3    | 70        | 2.01%   |
| 0x906e9    | 69        | 1.98%   |
| 0x806e9    | 65        | 1.87%   |
| 0x406e3    | 61        | 1.75%   |
| 0x08701021 | 59        | 1.7%    |
| 0x40651    | 58        | 1.67%   |
| 0x806ec    | 55        | 1.58%   |
| 0x806ea    | 55        | 1.58%   |
| 0x806c1    | 53        | 1.52%   |
| 0x20655    | 46        | 1.32%   |
| 0x306d4    | 45        | 1.29%   |
| 0x106e5    | 34        | 0.98%   |
| 0x08701013 | 34        | 0.98%   |
| 0x0800820d | 32        | 0.92%   |
| 0x10676    | 31        | 0.89%   |
| 0x30678    | 26        | 0.75%   |
| 0x0a50000c | 26        | 0.75%   |
| 0x20652    | 25        | 0.72%   |
| 0x06006705 | 23        | 0.66%   |
| 0xa0652    | 22        | 0.63%   |
| 0x706e5    | 22        | 0.63%   |
| 0x06000852 | 22        | 0.63%   |
| 0x906ed    | 21        | 0.6%    |
| 0x106a5    | 21        | 0.6%    |
| 0x806eb    | 20        | 0.57%   |
| 0x0a201016 | 20        | 0.57%   |
| 0x08108109 | 20        | 0.57%   |
| 0x6fb      | 19        | 0.55%   |
| 0x010000c8 | 19        | 0.55%   |
| 0x07030105 | 18        | 0.52%   |
| 0x06001119 | 18        | 0.52%   |
| 0x6fd      | 17        | 0.49%   |
| 0x306f2    | 17        | 0.49%   |
| 0x206c2    | 17        | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 528       | 15.87%  |
| Haswell          | 336       | 10.1%   |
| IvyBridge        | 258       | 7.75%   |
| SandyBridge      | 255       | 7.66%   |
| Skylake          | 197       | 5.92%   |
| Zen 2            | 171       | 5.14%   |
| Penryn           | 156       | 4.69%   |
| Unknown          | 129       | 3.88%   |
| Zen 3            | 126       | 3.79%   |
| Westmere         | 116       | 3.49%   |
| Zen+             | 83        | 2.49%   |
| Core             | 75        | 2.25%   |
| CometLake        | 74        | 2.22%   |
| TigerLake        | 70        | 2.1%    |
| Zen              | 69        | 2.07%   |
| Nehalem          | 69        | 2.07%   |
| Broadwell        | 69        | 2.07%   |
| Silvermont       | 66        | 1.98%   |
| Piledriver       | 58        | 1.74%   |
| Icelake          | 56        | 1.68%   |
| Alderlake Hybrid | 55        | 1.65%   |
| K10              | 52        | 1.56%   |
| Excavator        | 43        | 1.29%   |
| Goldmont plus    | 38        | 1.14%   |
| Puma             | 24        | 0.72%   |
| Goldmont         | 24        | 0.72%   |
| Steamroller      | 16        | 0.48%   |
| Bonnell          | 16        | 0.48%   |
| NetBurst         | 14        | 0.42%   |
| Jaguar           | 14        | 0.42%   |
| P6               | 13        | 0.39%   |
| K8 Hammer        | 13        | 0.39%   |
| Bulldozer        | 13        | 0.39%   |
| K10 Llano        | 12        | 0.36%   |
| Bobcat           | 9         | 0.27%   |
| Tremont          | 7         | 0.21%   |
| K8 & K10 hybrid  | 2         | 0.06%   |
| Gracemont        | 1         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1780      | 45.81%  |
| Nvidia                           | 1196      | 30.78%  |
| AMD                              | 874       | 22.49%  |
| Matrox Electronics Systems       | 23        | 0.59%   |
| VIA Technologies                 | 5         | 0.13%   |
| Silicon Integrated Systems [SiS] | 3         | 0.08%   |
| ASPEED Technology                | 3         | 0.08%   |
| Neomagic                         | 2         | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 171       | 4.27%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 121       | 3.02%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 91        | 2.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 86        | 2.15%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 85        | 2.12%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 80        | 2%      |
| Intel UHD Graphics 620                                                                   | 76        | 1.9%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 73        | 1.82%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 66        | 1.65%   |
| Intel HD Graphics 620                                                                    | 63        | 1.57%   |
| Intel HD Graphics 530                                                                    | 58        | 1.45%   |
| Intel Core Processor Integrated Graphics Controller                                      | 58        | 1.45%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 49        | 1.22%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 47        | 1.17%   |
| Intel HD Graphics 630                                                                    | 47        | 1.17%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 46        | 1.15%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 44        | 1.1%    |
| Intel HD Graphics 5500                                                                   | 39        | 0.97%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 39        | 0.97%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 38        | 0.95%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 36        | 0.9%    |
| AMD Renoir                                                                               | 36        | 0.9%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 35        | 0.87%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 34        | 0.85%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 34        | 0.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 31        | 0.77%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 31        | 0.77%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 30        | 0.75%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 30        | 0.75%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 29        | 0.72%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 28        | 0.7%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 27        | 0.67%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 26        | 0.65%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 25        | 0.62%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 23        | 0.57%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 23        | 0.57%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 23        | 0.57%   |
| Intel Iris Plus Graphics G7                                                              | 21        | 0.52%   |
| Intel HD Graphics 500                                                                    | 21        | 0.52%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 21        | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1244      | 36.98%  |
| 1 x Nvidia               | 752       | 22.35%  |
| 1 x AMD                  | 685       | 20.36%  |
| Intel + Nvidia           | 388       | 11.53%  |
| Intel + AMD              | 83        | 2.47%   |
| 2 x AMD                  | 61        | 1.81%   |
| AMD + Nvidia             | 48        | 1.43%   |
| Other                    | 46        | 1.37%   |
| 1 x Matrox               | 20        | 0.59%   |
| 2 x Nvidia               | 10        | 0.3%    |
| 2 x Intel                | 6         | 0.18%   |
| 1 x VIA                  | 5         | 0.15%   |
| 1 x SiS                  | 3         | 0.09%   |
| Nvidia + Matrox          | 3         | 0.09%   |
| Intel + AMD + 1 x Nvidia | 3         | 0.09%   |
| Nvidia + ASPEED          | 2         | 0.06%   |
| 1 x Neomagic             | 2         | 0.06%   |
| Intel + 2 x Nvidia       | 1         | 0.03%   |
| Intel + 2 x AMD          | 1         | 0.03%   |
| 1 x ASPEED               | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 2567      | 75.43%  |
| Proprietary | 667       | 19.6%   |
| Unknown     | 169       | 4.97%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1855      | 53.81%  |
| 1.01-2.0   | 419       | 12.16%  |
| 0.01-0.5   | 296       | 8.59%   |
| 0.51-1.0   | 257       | 7.46%   |
| 3.01-4.0   | 238       | 6.9%    |
| 7.01-8.0   | 195       | 5.66%   |
| 5.01-6.0   | 83        | 2.41%   |
| 8.01-16.0  | 56        | 1.62%   |
| 2.01-3.0   | 29        | 0.84%   |
| 16.01-24.0 | 16        | 0.46%   |
| 4.01-5.0   | 2         | 0.06%   |
| 32.01-64.0 | 1         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 446       | 11.91%  |
| AU Optronics            | 361       | 9.64%   |
| Dell                    | 283       | 7.56%   |
| LG Display              | 265       | 7.08%   |
| Chimei Innolux          | 207       | 5.53%   |
| Acer                    | 187       | 4.99%   |
| BOE                     | 177       | 4.73%   |
| Goldstar                | 158       | 4.22%   |
| Hewlett-Packard         | 146       | 3.9%    |
| Apple                   | 143       | 3.82%   |
| BenQ                    | 141       | 3.77%   |
| Philips                 | 122       | 3.26%   |
| AOC                     | 104       | 2.78%   |
| Ancor Communications    | 104       | 2.78%   |
| Sharp                   | 88        | 2.35%   |
| ViewSonic               | 80        | 2.14%   |
| Lenovo                  | 74        | 1.98%   |
| Unknown                 | 61        | 1.63%   |
| Chi Mei Optoelectronics | 48        | 1.28%   |
| ASUSTek Computer        | 40        | 1.07%   |
| Sony                    | 36        | 0.96%   |
| ___                     | 30        | 0.8%    |
| Panasonic               | 28        | 0.75%   |
| Kogan                   | 28        | 0.75%   |
| LG Electronics          | 26        | 0.69%   |
| PANDA                   | 23        | 0.61%   |
| GKK                     | 17        | 0.45%   |
| Toshiba                 | 16        | 0.43%   |
| Gigabyte Technology     | 16        | 0.43%   |
| MSI                     | 15        | 0.4%    |
| Hitachi                 | 13        | 0.35%   |
| MiTAC                   | 12        | 0.32%   |
| Unknown (XXX)           | 11        | 0.29%   |
| SAC                     | 11        | 0.29%   |
| InfoVision              | 11        | 0.29%   |
| CVT                     | 9         | 0.24%   |
| Unknown                 | 9         | 0.24%   |
| TCL                     | 8         | 0.21%   |
| MStar                   | 8         | 0.21%   |
| Eizo                    | 8         | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SyncMaster SAM01D3 1440x900 408x225mm 18.3-inch      | 21        | 0.53%   |
| ___ LCDTV16 ___0101 1920x1080                                            | 19        | 0.48%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 19        | 0.48%   |
| ___ LCDTV16 ___9000 1360x768                                             | 13        | 0.33%   |
| ViewSonic VA2226w-3 VSC2051 1680x1050 490x290mm 22.4-inch                | 13        | 0.33%   |
| Panasonic TDM13O56 MEI96A2 3000x2000 285x190mm 13.5-inch                 | 12        | 0.3%    |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 12        | 0.3%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 12        | 0.3%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 12        | 0.3%    |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 11        | 0.28%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                        | 11        | 0.28%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 11        | 0.28%   |
| Unknown LCDTV16 0101 1920x1080 1600x900mm 72.3-inch                      | 10        | 0.25%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                  | 10        | 0.25%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 10        | 0.25%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                       | 9         | 0.23%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x173mm 12.3-inch             | 9         | 0.23%   |
| BenQ G2420HD BNQ7840 1920x1080 531x299mm 24.0-inch                       | 9         | 0.23%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                     | 9         | 0.23%   |
| Unknown                                                                  | 9         | 0.23%   |
| Unknown (XXX) Beyond TV XXX2851 1920x1080 1209x680mm 54.6-inch           | 8         | 0.2%    |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch        | 8         | 0.2%    |
| Samsung Electronics LCD Monitor SAM2C35 1024x768 280x210mm 13.8-inch     | 8         | 0.2%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 8         | 0.2%    |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 8         | 0.2%    |
| Apple iMac APPA007 2560x1440 597x336mm 27.0-inch                         | 8         | 0.2%    |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                     | 8         | 0.2%    |
| Ancor Communications ASUS VP247 ACI24C7 1920x1080 521x293mm 23.5-inch    | 8         | 0.2%    |
| SAC LED MONITOR SAC952D 1920x1080 480x260mm 21.5-inch                    | 7         | 0.18%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                  | 7         | 0.18%   |
| Kogan KAMN341FQULA KGN3400 3440x1440 795x334mm 33.9-inch                 | 7         | 0.18%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 7         | 0.18%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 7         | 0.18%   |
| Dell S2721DGF DEL41D9 2560x1440 597x336mm 27.0-inch                      | 7         | 0.18%   |
| CVT CVTE TV CVT0003 1360x768 575x323mm 26.0-inch                         | 7         | 0.18%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 7         | 0.18%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch          | 7         | 0.18%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 7         | 0.18%   |
| Chimei Innolux LCD Monitor CMN1514 1920x1080 344x193mm 15.5-inch         | 7         | 0.18%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 7         | 0.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1504      | 42.15%  |
| 1366x768 (WXGA)    | 513       | 14.38%  |
| 3840x2160 (4K)     | 317       | 8.88%   |
| 2560x1440 (QHD)    | 203       | 5.69%   |
| 1680x1050 (WSXGA+) | 127       | 3.56%   |
| 1280x1024 (SXGA)   | 109       | 3.05%   |
| 1920x1200 (WUXGA)  | 100       | 2.8%    |
| 1440x900 (WXGA+)   | 100       | 2.8%    |
| 1600x900 (HD+)     | 76        | 2.13%   |
| 1280x800 (WXGA)    | 69        | 1.93%   |
| 3440x1440          | 61        | 1.71%   |
| Unknown            | 58        | 1.63%   |
| 2560x1600          | 36        | 1.01%   |
| 3840x1080          | 28        | 0.78%   |
| 1360x768           | 25        | 0.7%    |
| 2560x1080          | 24        | 0.67%   |
| 2880x1800          | 23        | 0.64%   |
| 3840x2400          | 16        | 0.45%   |
| 2736x1824          | 12        | 0.34%   |
| 1920x540           | 12        | 0.34%   |
| 3200x1800 (QHD+)   | 9         | 0.25%   |
| 2160x1440          | 9         | 0.25%   |
| 1280x768           | 9         | 0.25%   |
| 1920x1280          | 8         | 0.22%   |
| 1280x720 (HD)      | 7         | 0.2%    |
| 800x1280           | 6         | 0.17%   |
| 3840x1600          | 6         | 0.17%   |
| 2256x1504          | 6         | 0.17%   |
| 1024x768 (XGA)     | 6         | 0.17%   |
| 1024x600           | 6         | 0.17%   |
| 3072x1920          | 5         | 0.14%   |
| 5760x2160          | 4         | 0.11%   |
| 5120x1440          | 4         | 0.11%   |
| 4480x1440          | 4         | 0.11%   |
| 3600x1080          | 4         | 0.11%   |
| 3200x2000          | 4         | 0.11%   |
| 2288x1287          | 4         | 0.11%   |
| 2240x1400          | 4         | 0.11%   |
| 1600x1200          | 4         | 0.11%   |
| 3200x1080          | 3         | 0.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 689       | 18.47%  |
| 27      | 381       | 10.21%  |
| 13      | 319       | 8.55%   |
| 24      | 312       | 8.36%   |
| 23      | 272       | 7.29%   |
| Unknown | 234       | 6.27%   |
| 14      | 208       | 5.57%   |
| 21      | 203       | 5.44%   |
| 17      | 141       | 3.78%   |
| 19      | 133       | 3.56%   |
| 31      | 122       | 3.27%   |
| 22      | 93        | 2.49%   |
| 34      | 72        | 1.93%   |
| 12      | 66        | 1.77%   |
| 72      | 54        | 1.45%   |
| 11      | 54        | 1.45%   |
| 20      | 49        | 1.31%   |
| 18      | 39        | 1.05%   |
| 84      | 27        | 0.72%   |
| 32      | 25        | 0.67%   |
| 54      | 21        | 0.56%   |
| 26      | 21        | 0.56%   |
| 16      | 19        | 0.51%   |
| 52      | 17        | 0.46%   |
| 48      | 15        | 0.4%    |
| 42      | 15        | 0.4%    |
| 40      | 13        | 0.35%   |
| 35      | 12        | 0.32%   |
| 37      | 11        | 0.29%   |
| 25      | 10        | 0.27%   |
| 10      | 10        | 0.27%   |
| 29      | 8         | 0.21%   |
| 63      | 6         | 0.16%   |
| 55      | 6         | 0.16%   |
| 46      | 6         | 0.16%   |
| 7       | 6         | 0.16%   |
| 36      | 5         | 0.13%   |
| 28      | 4         | 0.11%   |
| 142     | 3         | 0.08%   |
| 65      | 3         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1026      | 28.15%  |
| 501-600        | 869       | 23.84%  |
| 401-500        | 423       | 11.6%   |
| 201-300        | 341       | 9.36%   |
| Unknown        | 234       | 6.42%   |
| 351-400        | 220       | 6.04%   |
| 601-700        | 193       | 5.29%   |
| 701-800        | 101       | 2.77%   |
| 1501-2000      | 86        | 2.36%   |
| 1001-1500      | 84        | 2.3%    |
| 801-900        | 40        | 1.1%    |
| 901-1000       | 17        | 0.47%   |
| 1-100          | 6         | 0.16%   |
| More than 2000 | 3         | 0.08%   |
| 101-200        | 2         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2364      | 71.18%  |
| 16/10   | 461       | 13.88%  |
| Unknown | 196       | 5.9%    |
| 5/4     | 97        | 2.92%   |
| 21/9    | 91        | 2.74%   |
| 3/2     | 48        | 1.45%   |
| 4/3     | 27        | 0.81%   |
| 32/9    | 16        | 0.48%   |
| 6/5     | 10        | 0.3%    |
| 0.67    | 6         | 0.18%   |
| 1.00    | 3         | 0.09%   |
| 3.40    | 1         | 0.03%   |
| 0.62    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 715       | 19.43%  |
| 101-110        | 683       | 18.56%  |
| 301-350        | 396       | 10.76%  |
| 81-90          | 366       | 9.95%   |
| 351-500        | 237       | 6.44%   |
| Unknown        | 234       | 6.36%   |
| 151-200        | 230       | 6.25%   |
| 71-80          | 164       | 4.46%   |
| More than 1000 | 149       | 4.05%   |
| 251-300        | 109       | 2.96%   |
| 121-130        | 97        | 2.64%   |
| 501-1000       | 69        | 1.88%   |
| 51-60          | 57        | 1.55%   |
| 61-70          | 53        | 1.44%   |
| 141-150        | 50        | 1.36%   |
| 111-120        | 24        | 0.65%   |
| 131-140        | 17        | 0.46%   |
| 91-100         | 12        | 0.33%   |
| 41-50          | 9         | 0.24%   |
| 1-40           | 8         | 0.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1274      | 36%     |
| 101-120       | 841       | 23.76%  |
| 121-160       | 708       | 20.01%  |
| 161-240       | 243       | 6.87%   |
| Unknown       | 234       | 6.61%   |
| 1-50          | 120       | 3.39%   |
| More than 240 | 119       | 3.36%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 2619      | 75.61%  |
| 2     | 589       | 17%     |
| 0     | 174       | 5.02%   |
| 3     | 70        | 2.02%   |
| 4     | 11        | 0.32%   |
| 5     | 1         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1746      | 34.07%  |
| Realtek Semiconductor           | 1666      | 32.51%  |
| Qualcomm Atheros                | 521       | 10.17%  |
| Broadcom                        | 359       | 7.01%   |
| Broadcom Limited                | 77        | 1.5%    |
| Marvell Technology Group        | 65        | 1.27%   |
| Ralink                          | 60        | 1.17%   |
| TP-Link                         | 49        | 0.96%   |
| Ralink Technology               | 48        | 0.94%   |
| MediaTek                        | 46        | 0.9%    |
| Samsung Electronics             | 36        | 0.7%    |
| DisplayLink                     | 27        | 0.53%   |
| Sierra Wireless                 | 26        | 0.51%   |
| NetGear                         | 25        | 0.49%   |
| Aquantia                        | 22        | 0.43%   |
| Huawei Technologies             | 21        | 0.41%   |
| Nvidia                          | 20        | 0.39%   |
| D-Link                          | 19        | 0.37%   |
| Microsoft                       | 17        | 0.33%   |
| Edimax Technology               | 17        | 0.33%   |
| D-Link System                   | 17        | 0.33%   |
| ASIX Electronics                | 17        | 0.33%   |
| Dell                            | 16        | 0.31%   |
| ZTE WCDMA Technologies MSM      | 13        | 0.25%   |
| Lenovo                          | 13        | 0.25%   |
| Apple                           | 13        | 0.25%   |
| ASUSTek Computer                | 12        | 0.23%   |
| Hewlett-Packard                 | 11        | 0.21%   |
| Motorola PCS                    | 10        | 0.2%    |
| Google                          | 10        | 0.2%    |
| OPPO Electronics                | 9         | 0.18%   |
| VIA Technologies                | 8         | 0.16%   |
| Qualcomm Atheros Communications | 7         | 0.14%   |
| Qualcomm                        | 7         | 0.14%   |
| ICS Advent                      | 6         | 0.12%   |
| Standard Microsystems           | 5         | 0.1%    |
| Mellanox Technologies           | 5         | 0.1%    |
| Arduino SA                      | 5         | 0.1%    |
| Xiaomi                          | 4         | 0.08%   |
| Microchip Technology            | 4         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1108      | 18.39%  |
| Intel Wi-Fi 6 AX200                                               | 170       | 2.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 136       | 2.26%   |
| Intel I211 Gigabit Network Connection                             | 132       | 2.19%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 130       | 2.16%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 122       | 2.02%   |
| Realtek RTL8125 2.5GbE Controller                                 | 95        | 1.58%   |
| Intel Wireless 8265 / 8275                                        | 89        | 1.48%   |
| Intel Wireless 8260                                               | 78        | 1.29%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 66        | 1.1%    |
| Intel Wireless 7260                                               | 66        | 1.1%    |
| Intel Ethernet Connection (2) I219-V                              | 64        | 1.06%   |
| Intel Ethernet Connection I217-LM                                 | 63        | 1.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 60        | 1%      |
| Intel Wireless 7265                                               | 60        | 1%      |
| Intel Wi-Fi 6 AX201                                               | 56        | 0.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 55        | 0.91%   |
| Intel Ethernet Controller I225-V                                  | 55        | 0.91%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 53        | 0.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 51        | 0.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 50        | 0.83%   |
| Intel Wireless 3165                                               | 47        | 0.78%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 47        | 0.78%   |
| Intel Ethernet Connection (7) I219-V                              | 47        | 0.78%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 47        | 0.78%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 43        | 0.71%   |
| Intel Wireless-AC 9260                                            | 43        | 0.71%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 43        | 0.71%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 40        | 0.66%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 40        | 0.66%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 39        | 0.65%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 39        | 0.65%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 38        | 0.63%   |
| Intel Ethernet Connection I219-LM                                 | 35        | 0.58%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 35        | 0.58%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 34        | 0.56%   |
| Intel Ethernet Connection (2) I219-LM                             | 34        | 0.56%   |
| Intel Centrino Ultimate-N 6300                                    | 34        | 0.56%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 34        | 0.56%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 34        | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1225      | 46.1%   |
| Qualcomm Atheros                | 389       | 14.64%  |
| Realtek Semiconductor           | 376       | 14.15%  |
| Broadcom                        | 240       | 9.03%   |
| Ralink                          | 60        | 2.26%   |
| Broadcom Limited                | 55        | 2.07%   |
| Ralink Technology               | 48        | 1.81%   |
| TP-Link                         | 47        | 1.77%   |
| MediaTek                        | 41        | 1.54%   |
| Sierra Wireless                 | 26        | 0.98%   |
| NetGear                         | 23        | 0.87%   |
| Marvell Technology Group        | 23        | 0.87%   |
| Edimax Technology               | 17        | 0.64%   |
| Microsoft                       | 12        | 0.45%   |
| D-Link System                   | 12        | 0.45%   |
| ASUSTek Computer                | 12        | 0.45%   |
| D-Link                          | 11        | 0.41%   |
| Dell                            | 9         | 0.34%   |
| Qualcomm Atheros Communications | 7         | 0.26%   |
| Belkin Components               | 4         | 0.15%   |
| Qualcomm                        | 3         | 0.11%   |
| Hewlett-Packard                 | 3         | 0.11%   |
| BUFFALO                         | 3         | 0.11%   |
| Wacom                           | 2         | 0.08%   |
| Linksys                         | 2         | 0.08%   |
| AVM                             | 2         | 0.08%   |
| Xiaomi                          | 1         | 0.04%   |
| Wilocity                        | 1         | 0.04%   |
| Toshiba                         | 1         | 0.04%   |
| IMC Networks                    | 1         | 0.04%   |
| AboCom Systems                  | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 170       | 6.36%   |
| Intel Wireless 8265 / 8275                                     | 89        | 3.33%   |
| Intel Wireless 8260                                            | 78        | 2.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 66        | 2.47%   |
| Intel Wireless 7260                                            | 66        | 2.47%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 60        | 2.25%   |
| Intel Wireless 7265                                            | 60        | 2.25%   |
| Intel Wi-Fi 6 AX201                                            | 56        | 2.1%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 55        | 2.06%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 53        | 1.98%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 51        | 1.91%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 50        | 1.87%   |
| Intel Wireless 3165                                            | 47        | 1.76%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 47        | 1.76%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 47        | 1.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 43        | 1.61%   |
| Intel Wireless-AC 9260                                         | 43        | 1.61%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 43        | 1.61%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 40        | 1.5%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 40        | 1.5%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 39        | 1.46%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 38        | 1.42%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 35        | 1.31%   |
| Intel Centrino Ultimate-N 6300                                 | 34        | 1.27%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 34        | 1.27%   |
| Realtek 802.11ac NIC                                           | 31        | 1.16%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 28        | 1.05%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 26        | 0.97%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 26        | 0.97%   |
| Intel Wireless 3160                                            | 26        | 0.97%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 26        | 0.97%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 25        | 0.94%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 25        | 0.94%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 23        | 0.86%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless              | 22        | 0.82%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 22        | 0.82%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 21        | 0.79%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 20        | 0.75%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 18        | 0.67%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 17        | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1473      | 46.28%  |
| Intel                            | 992       | 31.17%  |
| Qualcomm Atheros                 | 189       | 5.94%   |
| Broadcom                         | 184       | 5.78%   |
| Marvell Technology Group         | 42        | 1.32%   |
| Samsung Electronics              | 36        | 1.13%   |
| DisplayLink                      | 27        | 0.85%   |
| Broadcom Limited                 | 22        | 0.69%   |
| Aquantia                         | 22        | 0.69%   |
| Nvidia                           | 20        | 0.63%   |
| ASIX Electronics                 | 17        | 0.53%   |
| Huawei Technologies              | 16        | 0.5%    |
| ZTE WCDMA Technologies MSM       | 13        | 0.41%   |
| Lenovo                           | 13        | 0.41%   |
| Apple                            | 13        | 0.41%   |
| Google                           | 10        | 0.31%   |
| OPPO Electronics                 | 9         | 0.28%   |
| VIA Technologies                 | 8         | 0.25%   |
| D-Link                           | 8         | 0.25%   |
| Motorola PCS                     | 6         | 0.19%   |
| ICS Advent                       | 6         | 0.19%   |
| Standard Microsystems            | 5         | 0.16%   |
| D-Link System                    | 5         | 0.16%   |
| Microsoft                        | 4         | 0.13%   |
| Microchip Technology             | 4         | 0.13%   |
| MediaTek                         | 4         | 0.13%   |
| JMicron Technology               | 4         | 0.13%   |
| Xiaomi                           | 3         | 0.09%   |
| Qualcomm                         | 3         | 0.09%   |
| NetGear                          | 3         | 0.09%   |
| IBM                              | 3         | 0.09%   |
| Hewlett-Packard                  | 3         | 0.09%   |
| Silicon Integrated Systems [SiS] | 2         | 0.06%   |
| QLogic                           | 2         | 0.06%   |
| Mellanox Technologies            | 2         | 0.06%   |
| Dell                             | 2         | 0.06%   |
| vivo                             | 1         | 0.03%   |
| TP-Link                          | 1         | 0.03%   |
| T & A Mobile Phones              | 1         | 0.03%   |
| HMD Global                       | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1108      | 33.72%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 136       | 4.14%   |
| Intel I211 Gigabit Network Connection                             | 132       | 4.02%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 130       | 3.96%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 122       | 3.71%   |
| Realtek RTL8125 2.5GbE Controller                                 | 95        | 2.89%   |
| Intel Ethernet Connection (2) I219-V                              | 64        | 1.95%   |
| Intel Ethernet Connection I217-LM                                 | 63        | 1.92%   |
| Intel Ethernet Controller I225-V                                  | 55        | 1.67%   |
| Intel Ethernet Connection (7) I219-V                              | 47        | 1.43%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 39        | 1.19%   |
| Intel Ethernet Connection I219-LM                                 | 35        | 1.07%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 34        | 1.03%   |
| Intel Ethernet Connection (2) I219-LM                             | 34        | 1.03%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 34        | 1.03%   |
| Intel 82579V Gigabit Network Connection                           | 29        | 0.88%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 28        | 0.85%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 27        | 0.82%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 27        | 0.82%   |
| Intel Ethernet Connection I217-V                                  | 24        | 0.73%   |
| Intel 82574L Gigabit Network Connection                           | 24        | 0.73%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 23        | 0.7%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 23        | 0.7%    |
| Intel Ethernet Connection (4) I219-LM                             | 21        | 0.64%   |
| Intel Ethernet Connection (2) I218-V                              | 20        | 0.61%   |
| Intel 82577LM Gigabit Network Connection                          | 20        | 0.61%   |
| Intel I210 Gigabit Network Connection                             | 19        | 0.58%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 18        | 0.55%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 17        | 0.52%   |
| Intel Ethernet Connection I218-LM                                 | 17        | 0.52%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 16        | 0.49%   |
| Intel Ethernet Connection (4) I219-V                              | 15        | 0.46%   |
| Intel Ethernet Connection (6) I219-V                              | 14        | 0.43%   |
| ASIX AX88179 Gigabit Ethernet                                     | 14        | 0.43%   |
| Intel Ethernet Connection I219-V                                  | 13        | 0.4%    |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 13        | 0.4%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 12        | 0.37%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 12        | 0.37%   |
| Intel Ethernet Connection (3) I218-LM                             | 12        | 0.37%   |
| Intel Ethernet Connection (10) I219-V                             | 12        | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2869      | 52.99%  |
| WiFi     | 2478      | 45.77%  |
| Modem    | 53        | 0.98%   |
| Unknown  | 14        | 0.26%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1867      | 54.02%  |
| Ethernet | 1589      | 45.98%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1754      | 52.3%   |
| 1     | 1354      | 40.37%  |
| 3     | 128       | 3.82%   |
| 0     | 76        | 2.27%   |
| 4     | 27        | 0.81%   |
| 5     | 9         | 0.27%   |
| 6     | 4         | 0.12%   |
| 9     | 1         | 0.03%   |
| 8     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2926      | 86.57%  |
| Yes  | 454       | 13.43%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1001      | 50.13%  |
| Apple                           | 151       | 7.56%   |
| Broadcom                        | 131       | 6.56%   |
| Realtek Semiconductor           | 127       | 6.36%   |
| Qualcomm Atheros Communications | 124       | 6.21%   |
| Cambridge Silicon Radio         | 119       | 5.96%   |
| IMC Networks                    | 52        | 2.6%    |
| Lite-On Technology              | 51        | 2.55%   |
| Foxconn / Hon Hai               | 46        | 2.3%    |
| Toshiba                         | 39        | 1.95%   |
| ASUSTek Computer                | 27        | 1.35%   |
| Marvell Semiconductor           | 21        | 1.05%   |
| Hewlett-Packard                 | 20        | 1%      |
| Ralink                          | 17        | 0.85%   |
| Dell                            | 17        | 0.85%   |
| MediaTek                        | 12        | 0.6%    |
| TP-Link                         | 7         | 0.35%   |
| Alps Electric                   | 7         | 0.35%   |
| Realtek                         | 6         | 0.3%    |
| Edimax Technology               | 5         | 0.25%   |
| Ralink Technology               | 4         | 0.2%    |
| USI                             | 3         | 0.15%   |
| Micro Star International        | 2         | 0.1%    |
| Integrated System Solution      | 2         | 0.1%    |
| Belkin Components               | 2         | 0.1%    |
| Taiyo Yuden                     | 1         | 0.05%   |
| Opticis                         | 1         | 0.05%   |
| Logitech                        | 1         | 0.05%   |
| Creative Technology             | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 347       | 17.35%  |
| Intel AX201 Bluetooth                               | 173       | 8.65%   |
| Intel AX200 Bluetooth                               | 162       | 8.1%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 119       | 5.95%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 111       | 5.55%   |
| Intel Bluetooth Device                              | 90        | 4.5%    |
| Realtek Bluetooth Radio                             | 75        | 3.75%   |
| Apple Bluetooth Host Controller                     | 66        | 3.3%    |
| Qualcomm Atheros  Bluetooth Device                  | 53        | 2.65%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 51        | 2.55%   |
| Apple Bluetooth USB Host Controller                 | 42        | 2.1%    |
| Realtek  Bluetooth 4.2 Adapter                      | 41        | 2.05%   |
| Intel AX210 Bluetooth                               | 41        | 2.05%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 39        | 1.95%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 30        | 1.5%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 28        | 1.4%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 25        | 1.25%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 23        | 1.15%   |
| IMC Networks Bluetooth Radio                        | 21        | 1.05%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 19        | 0.95%   |
| Ralink RT3290 Bluetooth                             | 17        | 0.85%   |
| Marvell Bluetooth and Wireless LAN Composite        | 16        | 0.8%    |
| Broadcom BCM2045B (BDC-2.1)                         | 16        | 0.8%    |
| Lite-On Atheros AR3012 Bluetooth                    | 15        | 0.75%   |
| Foxconn / Hon Hai Bluetooth Device                  | 15        | 0.75%   |
| Apple Bluetooth HCI                                 | 15        | 0.75%   |
| Toshiba Bluetooth Device                            | 13        | 0.65%   |
| Lite-On Bluetooth Device                            | 13        | 0.65%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 13        | 0.65%   |
| MediaTek Wireless_Device                            | 12        | 0.6%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 11        | 0.55%   |
| HP Broadcom 2070 Bluetooth Combo                    | 11        | 0.55%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 11        | 0.55%   |
| Broadcom HP Portable Bumble Bee                     | 10        | 0.5%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 9         | 0.45%   |
| Toshiba Integrated Bluetooth HCI                    | 8         | 0.4%    |
| IMC Networks Wireless_Device                        | 8         | 0.4%    |
| Broadcom HP Portable SoftSailing                    | 8         | 0.4%    |
| TP-Link UB5A Adapter                                | 7         | 0.35%   |
| Realtek RTL8821A Bluetooth                          | 7         | 0.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 2418      | 49.25%  |
| AMD                                  | 984       | 20.04%  |
| Nvidia                               | 914       | 18.62%  |
| C-Media Electronics                  | 65        | 1.32%   |
| Logitech                             | 59        | 1.2%    |
| Creative Labs                        | 31        | 0.63%   |
| Realtek Semiconductor                | 27        | 0.55%   |
| Kingston Technology                  | 21        | 0.43%   |
| Texas Instruments                    | 20        | 0.41%   |
| Razer USA                            | 19        | 0.39%   |
| GN Netcom                            | 19        | 0.39%   |
| Creative Technology                  | 17        | 0.35%   |
| Plantronics                          | 16        | 0.33%   |
| Generalplus Technology               | 15        | 0.31%   |
| Apple                                | 15        | 0.31%   |
| RODE Microphones                     | 13        | 0.26%   |
| Corsair                              | 12        | 0.24%   |
| SteelSeries ApS                      | 11        | 0.22%   |
| Micro Star International             | 10        | 0.2%    |
| Lenovo                               | 10        | 0.2%    |
| JMTek                                | 9         | 0.18%   |
| VIA Technologies                     | 8         | 0.16%   |
| Hewlett-Packard                      | 8         | 0.16%   |
| Blue Microphones                     | 8         | 0.16%   |
| Astro Gaming                         | 8         | 0.16%   |
| DSEA A/S                             | 7         | 0.14%   |
| Dell                                 | 7         | 0.14%   |
| Audio-Technica                       | 7         | 0.14%   |
| ASUSTek Computer                     | 7         | 0.14%   |
| Thesycon Systemsoftware & Consulting | 6         | 0.12%   |
| M-Audio                              | 6         | 0.12%   |
| Focusrite-Novation                   | 6         | 0.12%   |
| Cambridge Silicon Radio              | 6         | 0.12%   |
| Sony                                 | 5         | 0.1%    |
| OPPO Electronics                     | 5         | 0.1%    |
| Microsoft                            | 5         | 0.1%    |
| Giga-Byte Technology                 | 5         | 0.1%    |
| Samson Technologies                  | 4         | 0.08%   |
| PreSonus Audio Electronics           | 4         | 0.08%   |
| Native Instruments                   | 4         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 252       | 4.41%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 245       | 4.29%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 230       | 4.02%   |
| AMD Starship/Matisse HD Audio Controller                                   | 206       | 3.6%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 196       | 3.43%   |
| AMD Family 17h/19h HD Audio Controller                                     | 187       | 3.27%   |
| Intel Cannon Lake PCH cAVS                                                 | 139       | 2.43%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 138       | 2.41%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 131       | 2.29%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 108       | 1.89%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 92        | 1.61%   |
| AMD FCH Azalia Controller                                                  | 92        | 1.61%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 92        | 1.61%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 90        | 1.57%   |
| Intel 8 Series HD Audio Controller                                         | 88        | 1.54%   |
| Intel Haswell-ULT HD Audio Controller                                      | 87        | 1.52%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 80        | 1.4%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 76        | 1.33%   |
| Intel 200 Series PCH HD Audio                                              | 76        | 1.33%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 69        | 1.21%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 69        | 1.21%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 59        | 1.03%   |
| Intel Broadwell-U Audio Controller                                         | 59        | 1.03%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 59        | 1.03%   |
| Nvidia TU116 High Definition Audio Controller                              | 58        | 1.01%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 58        | 1.01%   |
| Nvidia GP107GL High Definition Audio Controller                            | 57        | 1%      |
| Intel Cannon Point-LP High Definition Audio Controller                     | 57        | 1%      |
| Nvidia GP104 High Definition Audio Controller                              | 56        | 0.98%   |
| Nvidia TU106 High Definition Audio Controller                              | 52        | 0.91%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 51        | 0.89%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 51        | 0.89%   |
| Intel Comet Lake PCH-LP cAVS                                               | 49        | 0.86%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 49        | 0.86%   |
| Nvidia GF108 High Definition Audio Controller                              | 48        | 0.84%   |
| Intel Comet Lake PCH cAVS                                                  | 48        | 0.84%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 45        | 0.79%   |
| Nvidia GK107 HDMI Audio Controller                                         | 44        | 0.77%   |
| AMD Kabini HDMI/DP Audio                                                   | 44        | 0.77%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 43        | 0.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 385       | 20.71%  |
| SK hynix                                | 314       | 16.89%  |
| Kingston                                | 207       | 11.14%  |
| Micron Technology                       | 192       | 10.33%  |
| Corsair                                 | 169       | 9.09%   |
| Unknown                                 | 151       | 8.12%   |
| Crucial                                 | 117       | 6.29%   |
| G.Skill                                 | 99        | 5.33%   |
| Team                                    | 32        | 1.72%   |
| Elpida                                  | 29        | 1.56%   |
| Nanya Technology                        | 25        | 1.34%   |
| A-DATA Technology                       | 18        | 0.97%   |
| Patriot                                 | 17        | 0.91%   |
| Ramaxel Technology                      | 16        | 0.86%   |
| Apacer                                  | 12        | 0.65%   |
| Transcend                               | 10        | 0.54%   |
| Unknown                                 | 9         | 0.48%   |
| Unknown (ABCD)                          | 7         | 0.38%   |
| Strontium                               | 4         | 0.22%   |
| Silicon Power                           | 4         | 0.22%   |
| Neo Forza                               | 4         | 0.22%   |
| GeIL                                    | 4         | 0.22%   |
| Hewlett-Packard                         | 3         | 0.16%   |
| Unknown (0x873E)                        | 2         | 0.11%   |
| Toshiba                                 | 2         | 0.11%   |
| Smart                                   | 2         | 0.11%   |
| pqi                                     | 2         | 0.11%   |
| Goldenmars                              | 2         | 0.11%   |
| Avant                                   | 2         | 0.11%   |
| ASint Technology                        | 2         | 0.11%   |
| Unknown (0x89AD)                        | 1         | 0.05%   |
| Unknown (0x0562)                        | 1         | 0.05%   |
| Undefi                                  | 1         | 0.05%   |
| Timetec                                 | 1         | 0.05%   |
| Silicon Power Computer & Communications | 1         | 0.05%   |
| Qimonda                                 | 1         | 0.05%   |
| Princeton                               | 1         | 0.05%   |
| PNY                                     | 1         | 0.05%   |
| Netlist                                 | 1         | 0.05%   |
| Innodisk                                | 1         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s         | 19        | 0.95%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s         | 16        | 0.8%    |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s         | 14        | 0.7%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s        | 13        | 0.65%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s         | 13        | 0.65%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s         | 13        | 0.65%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s        | 11        | 0.55%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s         | 11        | 0.55%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s         | 11        | 0.55%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s        | 10        | 0.5%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s         | 10        | 0.5%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s         | 10        | 0.5%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s         | 10        | 0.5%    |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s        | 10        | 0.5%    |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s        | 9         | 0.45%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s         | 9         | 0.45%   |
| Unknown                                                       | 9         | 0.45%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                       | 8         | 0.4%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 8         | 0.4%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s        | 8         | 0.4%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s         | 8         | 0.4%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s         | 8         | 0.4%    |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s | 8         | 0.4%    |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s         | 8         | 0.4%    |
| Unknown RAM Module 2048MB DIMM 800MT/s                        | 7         | 0.35%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s     | 7         | 0.35%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s        | 7         | 0.35%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s       | 7         | 0.35%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s        | 7         | 0.35%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s         | 7         | 0.35%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s          | 7         | 0.35%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                          | 6         | 0.3%    |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s          | 6         | 0.3%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s        | 6         | 0.3%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s         | 6         | 0.3%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s         | 6         | 0.3%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s         | 6         | 0.3%    |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s         | 6         | 0.3%    |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s          | 6         | 0.3%    |
| Unknown RAM Module 8192MB DIMM 1333MT/s                       | 5         | 0.25%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 754       | 46.03%  |
| DDR3    | 546       | 33.33%  |
| LPDDR3  | 75        | 4.58%   |
| Unknown | 73        | 4.46%   |
| DDR2    | 61        | 3.72%   |
| LPDDR4  | 52        | 3.17%   |
| SDRAM   | 24        | 1.47%   |
| DDR5    | 23        | 1.4%    |
| LPDDR5  | 15        | 0.92%   |
| DDR     | 12        | 0.73%   |
| DRAM    | 3         | 0.18%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 806       | 49.48%  |
| DIMM         | 673       | 41.31%  |
| Row Of Chips | 133       | 8.16%   |
| Chip         | 11        | 0.68%   |
| FB-DIMM      | 3         | 0.18%   |
| Unknown      | 3         | 0.18%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 700       | 40.18%  |
| 4096  | 427       | 24.51%  |
| 16384 | 292       | 16.76%  |
| 2048  | 202       | 11.6%   |
| 32768 | 72        | 4.13%   |
| 1024  | 36        | 2.07%   |
| 512   | 8         | 0.46%   |
| 65536 | 2         | 0.11%   |
| 49152 | 1         | 0.06%   |
| 1536  | 1         | 0.06%   |
| 256   | 1         | 0.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 366       | 20.6%   |
| 2667    | 247       | 13.9%   |
| 3200    | 208       | 11.71%  |
| 1333    | 138       | 7.77%   |
| 2133    | 110       | 6.19%   |
| 2400    | 104       | 5.85%   |
| 3600    | 66        | 3.71%   |
| 1334    | 53        | 2.98%   |
| 800     | 46        | 2.59%   |
| 1867    | 42        | 2.36%   |
| 667     | 40        | 2.25%   |
| 4267    | 25        | 1.41%   |
| 1067    | 24        | 1.35%   |
| 4800    | 23        | 1.29%   |
| 3400    | 23        | 1.29%   |
| Unknown | 22        | 1.24%   |
| 3000    | 21        | 1.18%   |
| 6400    | 16        | 0.9%    |
| 3533    | 14        | 0.79%   |
| 1866    | 14        | 0.79%   |
| 1066    | 14        | 0.79%   |
| 3266    | 13        | 0.73%   |
| 3733    | 11        | 0.62%   |
| 2933    | 10        | 0.56%   |
| 2800    | 8         | 0.45%   |
| 1800    | 8         | 0.45%   |
| 8400    | 7         | 0.39%   |
| 3866    | 7         | 0.39%   |
| 2666    | 7         | 0.39%   |
| 4000    | 6         | 0.34%   |
| 3800    | 6         | 0.34%   |
| 4266    | 5         | 0.28%   |
| 3100    | 5         | 0.28%   |
| 2048    | 5         | 0.28%   |
| 533     | 5         | 0.28%   |
| 400     | 5         | 0.28%   |
| 5200    | 4         | 0.23%   |
| 3500    | 4         | 0.23%   |
| 4199    | 3         | 0.17%   |
| 4133    | 3         | 0.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Brother Industries     | 37        | 28.91%  |
| Hewlett-Packard        | 30        | 23.44%  |
| Canon                  | 22        | 17.19%  |
| Fuji Xerox             | 8         | 6.25%   |
| Seiko Epson            | 7         | 5.47%   |
| Samsung Electronics    | 6         | 4.69%   |
| Prolific Technology    | 6         | 4.69%   |
| Dymo-CoStar            | 3         | 2.34%   |
| Lexmark International  | 2         | 1.56%   |
| Kyocera                | 2         | 1.56%   |
| Zebra                  | 1         | 0.78%   |
| Xerox                  | 1         | 0.78%   |
| Ricoh                  | 1         | 0.78%   |
| Custom Engineering SPA | 1         | 0.78%   |
| BIXOLON                | 1         | 0.78%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| HP DeskJet 2600 series                       | 8         | 6.11%   |
| Prolific PL2305 Parallel Port                | 6         | 4.58%   |
| Brother HL-2130 series                       | 5         | 3.82%   |
| Brother HL-1110 series                       | 5         | 3.82%   |
| HP DeskJet 2130 series                       | 4         | 3.05%   |
| HP ENVY 5000 series                          | 3         | 2.29%   |
| HP DeskJet F2100 Printer series              | 3         | 2.29%   |
| Fuji Xerox DocuPrint CM215 fw                | 3         | 2.29%   |
| Canon TS3100 series                          | 3         | 2.29%   |
| Brother HL-L3230CDW series                   | 3         | 2.29%   |
| Brother HL-1210W series                      | 3         | 2.29%   |
| HP OfficeJet 5200 series                     | 2         | 1.53%   |
| HP DeskJet 3630 series                       | 2         | 1.53%   |
| Fuji Xerox DocuPrint P205 b                  | 2         | 1.53%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo       | 2         | 1.53%   |
| Canon TR8500 series                          | 2         | 1.53%   |
| Canon PIXMA MX920 Series                     | 2         | 1.53%   |
| Canon PIXMA MG2500 Series                    | 2         | 1.53%   |
| Canon MG5600 series                          | 2         | 1.53%   |
| Canon LiDE 400                               | 2         | 1.53%   |
| Brother QL-570 Label Printer                 | 2         | 1.53%   |
| Brother MFC-L8690CDW series                  | 2         | 1.53%   |
| Brother MFC-1810                             | 2         | 1.53%   |
| Brother HL-L2305 series                      | 2         | 1.53%   |
| Zebra ZTC LP2844-Z-200dpi                    | 1         | 0.76%   |
| Xerox Phaser 8400N                           | 1         | 0.76%   |
| Seiko Epson XP-4100 Series                   | 1         | 0.76%   |
| Seiko Epson XP-240 Series                    | 1         | 0.76%   |
| Seiko Epson WF-5190 Series                   | 1         | 0.76%   |
| Seiko Epson WF-4830 Series                   | 1         | 0.76%   |
| Seiko Epson Thermal Receipt Printer [TM-T20] | 1         | 0.76%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1         | 0.76%   |
| Seiko Epson ET-2820 Series                   | 1         | 0.76%   |
| Samsung ML-2010P Mono Laser Printer          | 1         | 0.76%   |
| Samsung ML-1865                              | 1         | 0.76%   |
| Samsung ML-1640 Series Laser Printer         | 1         | 0.76%   |
| Samsung ML-1450                              | 1         | 0.76%   |
| Samsung M267x 287x Series                    | 1         | 0.76%   |
| Samsung M2020 Series                         | 1         | 0.76%   |
| Ricoh Printer                                | 1         | 0.76%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Canon            | 10        | 58.82%  |
| Seiko Epson      | 4         | 23.53%  |
| Syscan           | 1         | 5.88%   |
| Salix Technology | 1         | 5.88%   |
| Mustek Systems   | 1         | 5.88%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Canon CanoScan LIDE 25                                  | 2         | 11.76%  |
| Canon CanoScan LiDE 210                                 | 2         | 11.76%  |
| Syscan TravelScan 460/464                               | 1         | 5.88%   |
| Seiko Epson Scanner                                     | 1         | 5.88%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]             | 1         | 5.88%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1         | 5.88%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]       | 1         | 5.88%   |
| Salix USB Scanner.                                      | 1         | 5.88%   |
| Mustek Systems BearPaw 2448 TA Plus                     | 1         | 5.88%   |
| Canon CanoScan N670U/N676U/LiDE 20                      | 1         | 5.88%   |
| Canon CanoScan N1240U/LiDE 30                           | 1         | 5.88%   |
| Canon CanoScan LiDE 220                                 | 1         | 5.88%   |
| Canon CanoScan LiDE 200                                 | 1         | 5.88%   |
| Canon CanoScan LiDE 110                                 | 1         | 5.88%   |
| Canon CanoScan 1220U                                    | 1         | 5.88%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 393       | 21.38%  |
| Logitech                               | 182       | 9.9%    |
| Microdia                               | 150       | 8.16%   |
| Apple                                  | 139       | 7.56%   |
| Realtek Semiconductor                  | 131       | 7.13%   |
| IMC Networks                           | 119       | 6.47%   |
| Sunplus Innovation Technology          | 116       | 6.31%   |
| Bison Electronics                      | 75        | 4.08%   |
| Quanta                                 | 67        | 3.65%   |
| Cheng Uei Precision Industry (Foxlink) | 61        | 3.32%   |
| Suyin                                  | 57        | 3.1%    |
| Microsoft                              | 51        | 2.77%   |
| Lite-On Technology                     | 29        | 1.58%   |
| Acer                                   | 27        | 1.47%   |
| Syntek                                 | 26        | 1.41%   |
| Samsung Electronics                    | 25        | 1.36%   |
| Luxvisions Innotech Limited            | 19        | 1.03%   |
| Silicon Motion                         | 12        | 0.65%   |
| Importek                               | 12        | 0.65%   |
| Alcor Micro                            | 12        | 0.65%   |
| Ricoh                                  | 10        | 0.54%   |
| Razer USA                              | 9         | 0.49%   |
| Lenovo                                 | 9         | 0.49%   |
| Primax Electronics                     | 7         | 0.38%   |
| GEMBIRD                                | 7         | 0.38%   |
| OPPO Electronics                       | 6         | 0.33%   |
| LG Electronics                         | 6         | 0.33%   |
| Generalplus Technology                 | 6         | 0.33%   |
| Sonix Technology                       | 5         | 0.27%   |
| OmniVision Technologies                | 5         | 0.27%   |
| Z-Star Microelectronics                | 4         | 0.22%   |
| Magic Control Technology               | 4         | 0.22%   |
| icSpring                               | 4         | 0.22%   |
| Genesys Logic                          | 4         | 0.22%   |
| DigiTech                               | 4         | 0.22%   |
| Cubeternet                             | 4         | 0.22%   |
| ALi                                    | 4         | 0.22%   |
| SunplusIT                              | 2         | 0.11%   |
| MacroSilicon                           | 2         | 0.11%   |
| Intel                                  | 2         | 0.11%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 73        | 3.89%   |
| Chicony Integrated Camera                               | 67        | 3.57%   |
| Apple FaceTime HD Camera (Built-in)                     | 46        | 2.45%   |
| Realtek Integrated_Webcam_HD                            | 39        | 2.08%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                         | 36        | 1.92%   |
| Apple Built-in iSight                                   | 33        | 1.76%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 31        | 1.65%   |
| Chicony HD WebCam                                       | 31        | 1.65%   |
| IMC Networks Integrated Camera                          | 30        | 1.6%    |
| Sunplus Integrated_Webcam_HD                            | 29        | 1.55%   |
| Chicony TOSHIBA Web Camera - HD                         | 28        | 1.49%   |
| Bison Integrated Camera                                 | 28        | 1.49%   |
| Logitech HD Pro Webcam C920                             | 26        | 1.39%   |
| Samsung Galaxy series, misc. (MTP mode)                 | 25        | 1.33%   |
| Logitech Webcam C270                                    | 25        | 1.33%   |
| Logitech C922 Pro Stream Webcam                         | 21        | 1.12%   |
| Syntek Integrated Camera                                | 18        | 0.96%   |
| Chicony HP TrueVision HD Camera                         | 18        | 0.96%   |
| Apple FaceTime HD Camera                                | 17        | 0.91%   |
| Sunplus HD WebCam                                       | 16        | 0.85%   |
| Chicony HP Truevision HD                                | 16        | 0.85%   |
| Chicony HP HD Camera                                    | 16        | 0.85%   |
| Chicony USB 2.0 Camera                                  | 14        | 0.75%   |
| Chicony HD User Facing                                  | 14        | 0.75%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 14        | 0.75%   |
| Quanta HD User Facing                                   | 13        | 0.69%   |
| Realtek USB Camera                                      | 12        | 0.64%   |
| Microsoft LifeCam HD-3000                               | 12        | 0.64%   |
| Logitech Webcam C930e                                   | 12        | 0.64%   |
| Chicony EasyCamera                                      | 12        | 0.64%   |
| Suyin HP Truevision HD                                  | 11        | 0.59%   |
| Logitech StreamCam                                      | 11        | 0.59%   |
| Logitech HD Webcam C615                                 | 11        | 0.59%   |
| Lite-On Integrated Camera                               | 11        | 0.59%   |
| Chicony USB2.0 Camera                                   | 11        | 0.59%   |
| Chicony CNF9055 Toshiba Webcam                          | 11        | 0.59%   |
| Microdia Integrated Webcam                              | 10        | 0.53%   |
| Logitech Webcam C170                                    | 10        | 0.53%   |
| Bison HD Webcam                                         | 10        | 0.53%   |
| Realtek Integrated Webcam HD                            | 9         | 0.48%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 143       | 41.94%  |
| Synaptics                  | 79        | 23.17%  |
| Shenzhen Goodix Technology | 42        | 12.32%  |
| LighTuning Technology      | 22        | 6.45%   |
| AuthenTec                  | 17        | 4.99%   |
| Elan Microelectronics      | 16        | 4.69%   |
| Upek                       | 14        | 4.11%   |
| STMicroelectronics         | 7         | 2.05%   |
| Focal-systems.Corp         | 1         | 0.29%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 25        | 7.33%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 23        | 6.74%   |
| Shenzhen Goodix Fingerprint Reader                                         | 19        | 5.57%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 14        | 4.11%   |
| Validity Sensors Synaptics WBDI                                            | 13        | 3.81%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 13        | 3.81%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 12        | 3.52%   |
| Validity Sensors Fingerprint scanner                                       | 12        | 3.52%   |
| Shenzhen Goodix  FingerPrint Device                                        | 12        | 3.52%   |
| Validity Sensors VFS491                                                    | 11        | 3.23%   |
| Shenzhen Goodix FingerPrint                                                | 11        | 3.23%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 10        | 2.93%   |
| Synaptics  WBDI                                                            | 10        | 2.93%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 9         | 2.64%   |
| Synaptics WBDI                                                             | 9         | 2.64%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 8         | 2.35%   |
| Validity Sensors VFS Fingerprint sensor                                    | 8         | 2.35%   |
| Synaptics UWP WBDI                                                         | 8         | 2.35%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 2.35%   |
| Elan ELAN:ARM-M4                                                           | 8         | 2.35%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 7         | 2.05%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 7         | 2.05%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 7         | 2.05%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 2.05%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 7         | 2.05%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 1.76%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 6         | 1.76%   |
| Synaptics WBDI Device                                                      | 5         | 1.47%   |
| Elan WBF Fingerprint Sensor                                                | 5         | 1.47%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 1.17%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 1.17%   |
| AuthenTec AES1600                                                          | 4         | 1.17%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 3         | 0.88%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 0.88%   |
| Synaptics Fingerprint reader [HP G6]                                       | 3         | 0.88%   |
| Elan ELAN:Fingerprint                                                      | 3         | 0.88%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 0.88%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 2         | 0.59%   |
| Synaptics UWP WBDI Device                                                  | 2         | 0.59%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.59%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 38        | 62.3%   |
| Alcor Micro           | 13        | 21.31%  |
| Upek                  | 4         | 6.56%   |
| Lenovo                | 3         | 4.92%   |
| O2 Micro              | 2         | 3.28%   |
| Advanced Card Systems | 1         | 1.64%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 17        | 27.87%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 13        | 21.31%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 8         | 13.11%  |
| Broadcom 58200                                                               | 7         | 11.48%  |
| Broadcom 5880                                                                | 6         | 9.84%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 6.56%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 4.92%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 3.28%   |
| Advanced Card Systems ACR122U                                                | 1         | 1.64%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2397      | 69.54%  |
| 1     | 857       | 24.86%  |
| 2     | 149       | 4.32%   |
| 3     | 31        | 0.9%    |
| 4     | 11        | 0.32%   |
| 7     | 1         | 0.03%   |
| 5     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 339       | 27.7%   |
| Graphics card            | 280       | 22.88%  |
| Net/wireless             | 182       | 14.87%  |
| Multimedia controller    | 80        | 6.54%   |
| Communication controller | 55        | 4.49%   |
| Chipcard                 | 55        | 4.49%   |
| Camera                   | 40        | 3.27%   |
| Bluetooth                | 40        | 3.27%   |
| Unassigned class         | 35        | 2.86%   |
| Net/ethernet             | 25        | 2.04%   |
| Sound                    | 22        | 1.8%    |
| Storage                  | 17        | 1.39%   |
| Modem                    | 11        | 0.9%    |
| Network                  | 9         | 0.74%   |
| Card reader              | 9         | 0.74%   |
| Dvb card                 | 8         | 0.65%   |
| Storage/raid             | 4         | 0.33%   |
| Video                    | 3         | 0.25%   |
| Firewire controller      | 3         | 0.25%   |
| Storage/ata              | 2         | 0.16%   |
| Unclassified device      | 1         | 0.08%   |
| Tv card                  | 1         | 0.08%   |
| Storage/nvme             | 1         | 0.08%   |
| Storage/ide              | 1         | 0.08%   |
| Flash memory             | 1         | 0.08%   |

