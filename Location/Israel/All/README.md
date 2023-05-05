Linux in Israel - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Israel.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Israel/Desktop/README.md) and [notebooks](/Location/Israel/Notebook/README.md).

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

Total: 923

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [0aa17c06c5](https://linux-hardware.org/?probe=0aa17c06c5) | Apr 30, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [3586d79ce4](https://linux-hardware.org/?probe=3586d79ce4) | Apr 29, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [d8af950fd8](https://linux-hardware.org/?probe=d8af950fd8) | Apr 28, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [854cf327d8](https://linux-hardware.org/?probe=854cf327d8) | Apr 27, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [d805c85a12](https://linux-hardware.org/?probe=d805c85a12) | Apr 24, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [b80d03be6d](https://linux-hardware.org/?probe=b80d03be6d) | Apr 23, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [09d116d762](https://linux-hardware.org/?probe=09d116d762) | Apr 23, 2023 |
| Gigabyte      | B660M GAMING DDR4           | Desktop     | [2afc5398b8](https://linux-hardware.org/?probe=2afc5398b8) | Apr 22, 2023 |
| Gigabyte      | Z97X-UD5H                   | Desktop     | [1cb8a5dfb4](https://linux-hardware.org/?probe=1cb8a5dfb4) | Apr 20, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [0853728b34](https://linux-hardware.org/?probe=0853728b34) | Apr 16, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [6d206f88cb](https://linux-hardware.org/?probe=6d206f88cb) | Apr 16, 2023 |
| Lenovo        | ThinkPad T410 2522WZN       | Notebook    | [0baff3522f](https://linux-hardware.org/?probe=0baff3522f) | Apr 15, 2023 |
| Valve         | Jupiter                     | Notebook    | [56768ba5a6](https://linux-hardware.org/?probe=56768ba5a6) | Apr 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X432... | Notebook    | [5a17f65715](https://linux-hardware.org/?probe=5a17f65715) | Apr 14, 2023 |
| Gigabyte      | B560M H                     | Desktop     | [c59729f9d2](https://linux-hardware.org/?probe=c59729f9d2) | Apr 14, 2023 |
| Dell          | Latitude 5491               | Notebook    | [ef97e6890a](https://linux-hardware.org/?probe=ef97e6890a) | Apr 13, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [c47d5d79fd](https://linux-hardware.org/?probe=c47d5d79fd) | Apr 13, 2023 |
| Intel         | D945GCCR AAD78647-301       | Desktop     | [fac1992089](https://linux-hardware.org/?probe=fac1992089) | Apr 13, 2023 |
| Acer          | Aspire 5755G                | Notebook    | [917791ff47](https://linux-hardware.org/?probe=917791ff47) | Apr 12, 2023 |
| HP            | ZBook Firefly 14 inch G9... | Notebook    | [e9790ea3b6](https://linux-hardware.org/?probe=e9790ea3b6) | Apr 11, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [fc28f6d3f0](https://linux-hardware.org/?probe=fc28f6d3f0) | Apr 08, 2023 |
| HP            | ZBook 15 G5                 | Notebook    | [1927fa08d1](https://linux-hardware.org/?probe=1927fa08d1) | Apr 07, 2023 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [c871e7c68b](https://linux-hardware.org/?probe=c871e7c68b) | Apr 07, 2023 |
| Gigabyte      | B560M H                     | Desktop     | [7e3ef5fa45](https://linux-hardware.org/?probe=7e3ef5fa45) | Apr 06, 2023 |
| HP            | 8455                        | Desktop     | [a52e3d086a](https://linux-hardware.org/?probe=a52e3d086a) | Apr 04, 2023 |
| Dell          | 0GDG8Y A02                  | Desktop     | [83110b2400](https://linux-hardware.org/?probe=83110b2400) | Apr 02, 2023 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [f0d73d9284](https://linux-hardware.org/?probe=f0d73d9284) | Apr 01, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [c1a0385d07](https://linux-hardware.org/?probe=c1a0385d07) | Apr 01, 2023 |
| ASUSTek       | PN51-S1                     | Mini pc     | [2b534dd0fa](https://linux-hardware.org/?probe=2b534dd0fa) | Mar 31, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [4cfac9a162](https://linux-hardware.org/?probe=4cfac9a162) | Mar 30, 2023 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [507f441bfc](https://linux-hardware.org/?probe=507f441bfc) | Mar 30, 2023 |
| Acer          | Aspire 5820                 | Notebook    | [3e0e45bc17](https://linux-hardware.org/?probe=3e0e45bc17) | Mar 26, 2023 |
| ASUSTek       | PN62                        | Mini pc     | [9cd806cb31](https://linux-hardware.org/?probe=9cd806cb31) | Mar 20, 2023 |
| ASUSTek       | PRIME Z690-P                | Desktop     | [923aa59ad5](https://linux-hardware.org/?probe=923aa59ad5) | Mar 19, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [5667e8416e](https://linux-hardware.org/?probe=5667e8416e) | Mar 16, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D60... | Notebook    | [2c2920d462](https://linux-hardware.org/?probe=2c2920d462) | Mar 14, 2023 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | Notebook    | [fd6d58db15](https://linux-hardware.org/?probe=fd6d58db15) | Mar 12, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [28769bd85b](https://linux-hardware.org/?probe=28769bd85b) | Mar 12, 2023 |
| ASUSTek       | PRIME Z690-P                | Desktop     | [76054930ac](https://linux-hardware.org/?probe=76054930ac) | Mar 12, 2023 |
| ASUSTek       | PRIME Z690-P                | Desktop     | [a925c8a320](https://linux-hardware.org/?probe=a925c8a320) | Mar 12, 2023 |
| Gigabyte      | AORUS 17G XC                | Notebook    | [fb998b9957](https://linux-hardware.org/?probe=fb998b9957) | Mar 12, 2023 |
| Acer          | Aspire A715-72G             | Notebook    | [32b2d1b194](https://linux-hardware.org/?probe=32b2d1b194) | Mar 11, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [ac772ea51f](https://linux-hardware.org/?probe=ac772ea51f) | Mar 08, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [35a78f2cf1](https://linux-hardware.org/?probe=35a78f2cf1) | Mar 08, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [4e05d0a0e9](https://linux-hardware.org/?probe=4e05d0a0e9) | Mar 06, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [aa0e36b22e](https://linux-hardware.org/?probe=aa0e36b22e) | Mar 02, 2023 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [c0e9304de5](https://linux-hardware.org/?probe=c0e9304de5) | Mar 01, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [3db8300147](https://linux-hardware.org/?probe=3db8300147) | Mar 01, 2023 |
| Timi          | RedmiBook 16                | Notebook    | [2d713931d2](https://linux-hardware.org/?probe=2d713931d2) | Feb 28, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [dd5ce2c6db](https://linux-hardware.org/?probe=dd5ce2c6db) | Feb 27, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [4630f9a67c](https://linux-hardware.org/?probe=4630f9a67c) | Feb 27, 2023 |
| Gigabyte      | Z270XP-SLI-CF               | Desktop     | [677e93841e](https://linux-hardware.org/?probe=677e93841e) | Feb 27, 2023 |
| HP            | Pavilion TS 14              | Notebook    | [37296c42c3](https://linux-hardware.org/?probe=37296c42c3) | Feb 27, 2023 |
| Gigabyte      | B360M HD3                   | Desktop     | [d3821bdbab](https://linux-hardware.org/?probe=d3821bdbab) | Feb 26, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [d3b6621252](https://linux-hardware.org/?probe=d3b6621252) | Feb 26, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [323b6463a9](https://linux-hardware.org/?probe=323b6463a9) | Feb 24, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [4b0436b55d](https://linux-hardware.org/?probe=4b0436b55d) | Feb 23, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [a4c4313238](https://linux-hardware.org/?probe=a4c4313238) | Feb 23, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [a459216464](https://linux-hardware.org/?probe=a459216464) | Feb 21, 2023 |
| Alienware     | 15 R2                       | Notebook    | [96aa09ae59](https://linux-hardware.org/?probe=96aa09ae59) | Feb 21, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [d1f67d5e08](https://linux-hardware.org/?probe=d1f67d5e08) | Feb 21, 2023 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [7415192b86](https://linux-hardware.org/?probe=7415192b86) | Feb 20, 2023 |
| Lenovo        | IdeaPad S12 20021,2959      | Notebook    | [4a9dcac308](https://linux-hardware.org/?probe=4a9dcac308) | Feb 19, 2023 |
| Lenovo        | IdeaPad S12 20021,2959      | Notebook    | [d808827823](https://linux-hardware.org/?probe=d808827823) | Feb 19, 2023 |
| Gigabyte      | Z270-HD3-CF                 | Desktop     | [e958da375f](https://linux-hardware.org/?probe=e958da375f) | Feb 19, 2023 |
| Gigabyte      | Z270-HD3-CF                 | Desktop     | [e47bb0ee84](https://linux-hardware.org/?probe=e47bb0ee84) | Feb 19, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [6f8fadfe19](https://linux-hardware.org/?probe=6f8fadfe19) | Feb 15, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [390686f5f6](https://linux-hardware.org/?probe=390686f5f6) | Feb 14, 2023 |
| HP            | ZBook Firefly 14 inch G9... | Notebook    | [26ea96167c](https://linux-hardware.org/?probe=26ea96167c) | Feb 12, 2023 |
| Dell          | Vostro 3558                 | Notebook    | [bb53ff2532](https://linux-hardware.org/?probe=bb53ff2532) | Feb 12, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | Notebook    | [a1133b56be](https://linux-hardware.org/?probe=a1133b56be) | Feb 11, 2023 |
| HP            | ZBook Firefly 14 inch G9... | Notebook    | [ab928273ba](https://linux-hardware.org/?probe=ab928273ba) | Feb 11, 2023 |
| HP            | ZBook Firefly 14 inch G9... | Notebook    | [5995e0b36b](https://linux-hardware.org/?probe=5995e0b36b) | Feb 11, 2023 |
| Heptagon S... | HQ-BOX2 Server              | Notebook    | [476197a287](https://linux-hardware.org/?probe=476197a287) | Feb 09, 2023 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [d33be0bc3f](https://linux-hardware.org/?probe=d33be0bc3f) | Feb 05, 2023 |
| ASUSTek       | X556UV                      | Notebook    | [ae90dba4ca](https://linux-hardware.org/?probe=ae90dba4ca) | Feb 04, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [513dd8e40b](https://linux-hardware.org/?probe=513dd8e40b) | Feb 03, 2023 |
| Gigabyte      | G1.Sniper 3                 | Desktop     | [f7f587188e](https://linux-hardware.org/?probe=f7f587188e) | Feb 03, 2023 |
| HUAWEI        | HN-WX9X                     | Notebook    | [4b8ddf5d09](https://linux-hardware.org/?probe=4b8ddf5d09) | Jan 31, 2023 |
| Fujitsu       | LIFEBOOK U554               | Notebook    | [22bf4111de](https://linux-hardware.org/?probe=22bf4111de) | Jan 23, 2023 |
| Acer          | TravelMate P257-M           | Notebook    | [1345fa56c4](https://linux-hardware.org/?probe=1345fa56c4) | Jan 22, 2023 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [79a45b9ea0](https://linux-hardware.org/?probe=79a45b9ea0) | Jan 19, 2023 |
| Gigabyte      | Z270XP-SLI-CF               | Desktop     | [b6a8598370](https://linux-hardware.org/?probe=b6a8598370) | Jan 19, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [61c432b134](https://linux-hardware.org/?probe=61c432b134) | Jan 13, 2023 |
| Dell          | Vostro 14 5401              | Notebook    | [b56e81d82d](https://linux-hardware.org/?probe=b56e81d82d) | Jan 11, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [3965f2f9f4](https://linux-hardware.org/?probe=3965f2f9f4) | Jan 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [78a20b41ee](https://linux-hardware.org/?probe=78a20b41ee) | Jan 11, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [abe344877a](https://linux-hardware.org/?probe=abe344877a) | Jan 09, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [6a5da8e502](https://linux-hardware.org/?probe=6a5da8e502) | Jan 08, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [9767004b24](https://linux-hardware.org/?probe=9767004b24) | Jan 07, 2023 |
| ASUSTek       | ROG STRIX B660-A GAMING ... | Desktop     | [87c4201895](https://linux-hardware.org/?probe=87c4201895) | Jan 07, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [874b25fc88](https://linux-hardware.org/?probe=874b25fc88) | Jan 06, 2023 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | Notebook    | [9776545fc4](https://linux-hardware.org/?probe=9776545fc4) | Jan 06, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [4641833cab](https://linux-hardware.org/?probe=4641833cab) | Jan 06, 2023 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [43f6676d9d](https://linux-hardware.org/?probe=43f6676d9d) | Jan 06, 2023 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [9b828358df](https://linux-hardware.org/?probe=9b828358df) | Jan 05, 2023 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [7cf92f3f43](https://linux-hardware.org/?probe=7cf92f3f43) | Jan 05, 2023 |
| Dell          | 0PV9DG A01                  | Server      | [7f408923fa](https://linux-hardware.org/?probe=7f408923fa) | Dec 27, 2022 |
| GPD           | G1621-02                    | Notebook    | [10a7e912f8](https://linux-hardware.org/?probe=10a7e912f8) | Dec 25, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [10f4ac5e13](https://linux-hardware.org/?probe=10f4ac5e13) | Dec 24, 2022 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [1a9f9ac05f](https://linux-hardware.org/?probe=1a9f9ac05f) | Dec 22, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [b9b1f8140b](https://linux-hardware.org/?probe=b9b1f8140b) | Dec 18, 2022 |
| MSI           | Summit E16FlipEvo A12MT     | Notebook    | [426289da4e](https://linux-hardware.org/?probe=426289da4e) | Dec 11, 2022 |
| Dell          | Latitude E6420              | Notebook    | [011df4cb7f](https://linux-hardware.org/?probe=011df4cb7f) | Dec 02, 2022 |
| Lenovo        | ThinkPad T580 20L9001YIV    | Notebook    | [dc13dde66a](https://linux-hardware.org/?probe=dc13dde66a) | Nov 29, 2022 |
| Lenovo        | 32E9 SDK0T76465 WIN 3422... | Desktop     | [ec30826806](https://linux-hardware.org/?probe=ec30826806) | Nov 21, 2022 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [504222de34](https://linux-hardware.org/?probe=504222de34) | Nov 20, 2022 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [f685fd9050](https://linux-hardware.org/?probe=f685fd9050) | Nov 20, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [ade5f58f0e](https://linux-hardware.org/?probe=ade5f58f0e) | Nov 20, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [58c63522a4](https://linux-hardware.org/?probe=58c63522a4) | Nov 20, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [dc9ddea189](https://linux-hardware.org/?probe=dc9ddea189) | Nov 17, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [8b63918780](https://linux-hardware.org/?probe=8b63918780) | Nov 16, 2022 |
| Dell          | Vostro 3300                 | Notebook    | [ae100dd7e2](https://linux-hardware.org/?probe=ae100dd7e2) | Nov 16, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [c22dce3d23](https://linux-hardware.org/?probe=c22dce3d23) | Nov 16, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [75c1d24fcd](https://linux-hardware.org/?probe=75c1d24fcd) | Nov 13, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [189dd51cc3](https://linux-hardware.org/?probe=189dd51cc3) | Nov 13, 2022 |
| HP            | 88BE                        | Desktop     | [1c03e5957d](https://linux-hardware.org/?probe=1c03e5957d) | Nov 13, 2022 |
| ASUSTek       | UX430UNR                    | Notebook    | [f04bf95806](https://linux-hardware.org/?probe=f04bf95806) | Nov 08, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [da03d56b4e](https://linux-hardware.org/?probe=da03d56b4e) | Nov 07, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [4099d3c69b](https://linux-hardware.org/?probe=4099d3c69b) | Nov 05, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [c35a514fe5](https://linux-hardware.org/?probe=c35a514fe5) | Nov 05, 2022 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [be2ceae6ca](https://linux-hardware.org/?probe=be2ceae6ca) | Nov 05, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [578d48ac0c](https://linux-hardware.org/?probe=578d48ac0c) | Nov 04, 2022 |
| Gigabyte      | H97-HD3                     | Desktop     | [22214c7851](https://linux-hardware.org/?probe=22214c7851) | Nov 02, 2022 |
| Gigabyte      | H77-DS3H                    | Desktop     | [4457c6182e](https://linux-hardware.org/?probe=4457c6182e) | Oct 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [99152f7783](https://linux-hardware.org/?probe=99152f7783) | Oct 27, 2022 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [66b04ff6f8](https://linux-hardware.org/?probe=66b04ff6f8) | Oct 20, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [a43f7f6601](https://linux-hardware.org/?probe=a43f7f6601) | Oct 19, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [e09755f495](https://linux-hardware.org/?probe=e09755f495) | Oct 18, 2022 |
| Gigabyte      | X79-UP4                     | Desktop     | [f1e08df02d](https://linux-hardware.org/?probe=f1e08df02d) | Oct 16, 2022 |
| Gigabyte      | X79-UP4                     | Desktop     | [6ccc41cf96](https://linux-hardware.org/?probe=6ccc41cf96) | Oct 15, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | Desktop     | [d1a5c91196](https://linux-hardware.org/?probe=d1a5c91196) | Oct 14, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | Desktop     | [b69b373cc1](https://linux-hardware.org/?probe=b69b373cc1) | Oct 14, 2022 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [989fe39fa7](https://linux-hardware.org/?probe=989fe39fa7) | Oct 10, 2022 |
| Gigabyte      | GA-990FXA-UD3               | Desktop     | [dc262edc58](https://linux-hardware.org/?probe=dc262edc58) | Oct 09, 2022 |
| ASUSTek       | PRIME H270-PRO              | Desktop     | [b98f2dc115](https://linux-hardware.org/?probe=b98f2dc115) | Oct 08, 2022 |
| Dell          | 014GRG A01                  | Desktop     | [05a023826f](https://linux-hardware.org/?probe=05a023826f) | Oct 06, 2022 |
| AYANEO        | AIR                         | Tablet      | [a5e36506b9](https://linux-hardware.org/?probe=a5e36506b9) | Oct 04, 2022 |
| ASUSTek       | PRIME B365-PLUS             | Desktop     | [7e41cd4a30](https://linux-hardware.org/?probe=7e41cd4a30) | Oct 03, 2022 |
| ASUSTek       | PRIME B365-PLUS             | Desktop     | [9d811f43d3](https://linux-hardware.org/?probe=9d811f43d3) | Oct 03, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [47a7282318](https://linux-hardware.org/?probe=47a7282318) | Oct 02, 2022 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [b372f8126f](https://linux-hardware.org/?probe=b372f8126f) | Sep 29, 2022 |
| HP            | ProBook 430 G6              | Notebook    | [5c133ac35b](https://linux-hardware.org/?probe=5c133ac35b) | Sep 29, 2022 |
| Dell          | 06D7TR A02                  | Desktop     | [a0d832ff6a](https://linux-hardware.org/?probe=a0d832ff6a) | Sep 28, 2022 |
| Lenovo        | ThinkPad T580 20L9001YIV    | Notebook    | [bc43cff31b](https://linux-hardware.org/?probe=bc43cff31b) | Sep 23, 2022 |
| Dell          | 0WCJNT A06                  | Server      | [4cc4b2f914](https://linux-hardware.org/?probe=4cc4b2f914) | Sep 22, 2022 |
| ASUSTek       | Rampage II Extreme          | Desktop     | [c996a3c4dd](https://linux-hardware.org/?probe=c996a3c4dd) | Sep 19, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [cc3af3e194](https://linux-hardware.org/?probe=cc3af3e194) | Sep 16, 2022 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [4d7948b375](https://linux-hardware.org/?probe=4d7948b375) | Sep 16, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [598341495c](https://linux-hardware.org/?probe=598341495c) | Sep 16, 2022 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [1e4d0a6189](https://linux-hardware.org/?probe=1e4d0a6189) | Sep 15, 2022 |
| Dell          | Inspiron 3576               | Notebook    | [02023473b8](https://linux-hardware.org/?probe=02023473b8) | Sep 15, 2022 |
| Acer          | Aspire 5820                 | Notebook    | [1820ffa037](https://linux-hardware.org/?probe=1820ffa037) | Sep 09, 2022 |
| Acer          | Aspire 5820                 | Notebook    | [3f0d8d8ff5](https://linux-hardware.org/?probe=3f0d8d8ff5) | Sep 09, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [0796b79ff6](https://linux-hardware.org/?probe=0796b79ff6) | Sep 08, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [557860ffbd](https://linux-hardware.org/?probe=557860ffbd) | Sep 07, 2022 |
| Dell          | Latitude E4300              | Notebook    | [4589ef4489](https://linux-hardware.org/?probe=4589ef4489) | Sep 06, 2022 |
| Dell          | 0CRH6C A01                  | Desktop     | [d4a37f016b](https://linux-hardware.org/?probe=d4a37f016b) | Sep 03, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [63e2adf3a9](https://linux-hardware.org/?probe=63e2adf3a9) | Sep 02, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [f65d685d05](https://linux-hardware.org/?probe=f65d685d05) | Aug 30, 2022 |
| ASUSTek       | G75VX                       | Notebook    | [e249508d61](https://linux-hardware.org/?probe=e249508d61) | Aug 30, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [9158baf2c0](https://linux-hardware.org/?probe=9158baf2c0) | Aug 28, 2022 |
| Samsung       | Galaxy Book 12 LTE          | Tablet      | [e7f6559a38](https://linux-hardware.org/?probe=e7f6559a38) | Aug 21, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | Notebook    | [4f711bf806](https://linux-hardware.org/?probe=4f711bf806) | Aug 20, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [eb37729065](https://linux-hardware.org/?probe=eb37729065) | Aug 16, 2022 |
| HP            | 18E7                        | Desktop     | [f1c1f9c891](https://linux-hardware.org/?probe=f1c1f9c891) | Aug 12, 2022 |
| ASUSTek       | ROG Flow X13 GV301RA_GV3... | Convertible | [b9f6292104](https://linux-hardware.org/?probe=b9f6292104) | Aug 07, 2022 |
| Lenovo        | G50-80 80L0                 | Notebook    | [eb58813044](https://linux-hardware.org/?probe=eb58813044) | Aug 06, 2022 |
| Lenovo        | ThinkPad X250 20CLS3UW00    | Notebook    | [ddefadf8f1](https://linux-hardware.org/?probe=ddefadf8f1) | Aug 06, 2022 |
| Gigabyte      | Z690 AORUS ULTRA            | Desktop     | [06d2014c22](https://linux-hardware.org/?probe=06d2014c22) | Aug 05, 2022 |
| Gigabyte      | GA-990FXA-UD3               | Desktop     | [7893ade7cb](https://linux-hardware.org/?probe=7893ade7cb) | Aug 04, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [d1ca5eafe5](https://linux-hardware.org/?probe=d1ca5eafe5) | Aug 03, 2022 |
| Lenovo        | 3000 G530 4151/200          | Notebook    | [8e9bf5b1f9](https://linux-hardware.org/?probe=8e9bf5b1f9) | Aug 03, 2022 |
| ASUSTek       | PN51-S1                     | Mini pc     | [6362df4235](https://linux-hardware.org/?probe=6362df4235) | Jul 27, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [1512e3bf4d](https://linux-hardware.org/?probe=1512e3bf4d) | Jul 22, 2022 |
| Dell          | G7 7500                     | Notebook    | [f5e6475121](https://linux-hardware.org/?probe=f5e6475121) | Jul 22, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [56e3efd7bc](https://linux-hardware.org/?probe=56e3efd7bc) | Jul 19, 2022 |
| ASUSTek       | ROG Flow X13 GV301RA_GV3... | Convertible | [e52633f694](https://linux-hardware.org/?probe=e52633f694) | Jul 17, 2022 |
| HP            | ZBook Firefly 15 G7 Mobi... | Notebook    | [8f556b89fc](https://linux-hardware.org/?probe=8f556b89fc) | Jul 16, 2022 |
| ASUSTek       | G53JW                       | Notebook    | [2090800f5c](https://linux-hardware.org/?probe=2090800f5c) | Jul 06, 2022 |
| HP            | ProBook 430 G6              | Notebook    | [4281fab7fd](https://linux-hardware.org/?probe=4281fab7fd) | Jul 05, 2022 |
| ASUSTek       | ROG Flow X13 GV301RA_GV3... | Convertible | [c186124284](https://linux-hardware.org/?probe=c186124284) | Jul 03, 2022 |
| ASUSTek       | ROG Flow X13 GV301RA_GV3... | Convertible | [fce4d4547c](https://linux-hardware.org/?probe=fce4d4547c) | Jul 03, 2022 |
| HP            | Mini 210-1100               | Notebook    | [72289b7641](https://linux-hardware.org/?probe=72289b7641) | Jul 03, 2022 |
| HP            | Mini 210-1100               | Notebook    | [aaa9b86216](https://linux-hardware.org/?probe=aaa9b86216) | Jul 02, 2022 |
| Lenovo        | 3102 SDK0K13476 WIN 3306... | Desktop     | [ac6fde7f04](https://linux-hardware.org/?probe=ac6fde7f04) | Jul 02, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [4b04ded505](https://linux-hardware.org/?probe=4b04ded505) | Jun 30, 2022 |
| TYAN Compu... | S7010                       | Server      | [af4d333445](https://linux-hardware.org/?probe=af4d333445) | Jun 28, 2022 |
| Gigabyte      | Z690 AORUS MASTER           | Desktop     | [a8073316f6](https://linux-hardware.org/?probe=a8073316f6) | Jun 26, 2022 |
| Dell          | Latitude 7300               | Notebook    | [a7939aeb9e](https://linux-hardware.org/?probe=a7939aeb9e) | Jun 26, 2022 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [5708a69dc1](https://linux-hardware.org/?probe=5708a69dc1) | Jun 26, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [150ea72986](https://linux-hardware.org/?probe=150ea72986) | Jun 23, 2022 |
| MSI           | Z170A KRAIT GAMING          | Desktop     | [7f2adf56e4](https://linux-hardware.org/?probe=7f2adf56e4) | Jun 21, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [755c2fc534](https://linux-hardware.org/?probe=755c2fc534) | Jun 20, 2022 |
| Lenovo        | ThinkPad P50 20EQS31G00     | Notebook    | [2e98922741](https://linux-hardware.org/?probe=2e98922741) | Jun 17, 2022 |
| Lenovo        | ThinkPad P50 20EQS31G00     | Notebook    | [51042aca4a](https://linux-hardware.org/?probe=51042aca4a) | Jun 15, 2022 |
| Purism        | Librem 14                   | Notebook    | [89d920a7d2](https://linux-hardware.org/?probe=89d920a7d2) | Jun 11, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [f37ad0aba6](https://linux-hardware.org/?probe=f37ad0aba6) | Jun 10, 2022 |
| Lenovo        | Unknown                     | Notebook    | [2921bcaa1c](https://linux-hardware.org/?probe=2921bcaa1c) | Jun 09, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [1c8e5b49d3](https://linux-hardware.org/?probe=1c8e5b49d3) | Jun 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [00d3a71a00](https://linux-hardware.org/?probe=00d3a71a00) | Jun 06, 2022 |
| Foxconn       | H81MXV FAB A                | Desktop     | [1f880ea008](https://linux-hardware.org/?probe=1f880ea008) | Jun 05, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [606c1d3f8e](https://linux-hardware.org/?probe=606c1d3f8e) | May 31, 2022 |
| ASUSTek       | N550JV                      | Notebook    | [37af34e2e7](https://linux-hardware.org/?probe=37af34e2e7) | May 31, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [e308c653b2](https://linux-hardware.org/?probe=e308c653b2) | May 30, 2022 |
| Lenovo        | ThinkCentre M81 5049W15     | Desktop     | [df4917e32f](https://linux-hardware.org/?probe=df4917e32f) | May 28, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [c01e0f9ac4](https://linux-hardware.org/?probe=c01e0f9ac4) | May 25, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [24c2ad0798](https://linux-hardware.org/?probe=24c2ad0798) | May 24, 2022 |
| ASUSTek       | N550JV                      | Notebook    | [7b3acdb5ac](https://linux-hardware.org/?probe=7b3acdb5ac) | May 23, 2022 |
| Gigabyte      | Z690 AORUS ELITE AX DDR4    | Desktop     | [7ba08ba4b5](https://linux-hardware.org/?probe=7ba08ba4b5) | May 21, 2022 |
| Gigabyte      | Z690 AORUS ELITE AX DDR4    | Desktop     | [81aa40219e](https://linux-hardware.org/?probe=81aa40219e) | May 21, 2022 |
| ASUSTek       | N550JV                      | Notebook    | [286611f4de](https://linux-hardware.org/?probe=286611f4de) | May 20, 2022 |
| HP            | 8298                        | Desktop     | [3f45b43adb](https://linux-hardware.org/?probe=3f45b43adb) | May 19, 2022 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [dc2f9f56a5](https://linux-hardware.org/?probe=dc2f9f56a5) | May 18, 2022 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [813349f89b](https://linux-hardware.org/?probe=813349f89b) | May 17, 2022 |
| Dell          | Inspiron 5577               | Notebook    | [d14ee897f2](https://linux-hardware.org/?probe=d14ee897f2) | May 17, 2022 |
| Dell          | 0R4CNN A01                  | Server      | [b12db2e5d7](https://linux-hardware.org/?probe=b12db2e5d7) | May 16, 2022 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [22f5a0269f](https://linux-hardware.org/?probe=22f5a0269f) | May 15, 2022 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [8b8bd9dead](https://linux-hardware.org/?probe=8b8bd9dead) | May 15, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [b95acee640](https://linux-hardware.org/?probe=b95acee640) | May 15, 2022 |
| Dell          | Latitude 5421               | Notebook    | [3b2e352ea9](https://linux-hardware.org/?probe=3b2e352ea9) | May 11, 2022 |
| Dell          | Latitude 5421               | Notebook    | [105382c79b](https://linux-hardware.org/?probe=105382c79b) | May 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | Notebook    | [f48ef1adaf](https://linux-hardware.org/?probe=f48ef1adaf) | May 09, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [48fa5d3b93](https://linux-hardware.org/?probe=48fa5d3b93) | May 04, 2022 |
| Dell          | Vostro 5402                 | Notebook    | [ff11e148fd](https://linux-hardware.org/?probe=ff11e148fd) | May 04, 2022 |
| Lenovo        | 3102 NOK                    | Desktop     | [8ef837bdb4](https://linux-hardware.org/?probe=8ef837bdb4) | May 04, 2022 |
| Lenovo        | ThinkPad 10 2nd 20E30035... | Tablet      | [f51fab0e09](https://linux-hardware.org/?probe=f51fab0e09) | Apr 30, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [a7fe3cb0f6](https://linux-hardware.org/?probe=a7fe3cb0f6) | Apr 30, 2022 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [5c9e5fc14c](https://linux-hardware.org/?probe=5c9e5fc14c) | Apr 29, 2022 |
| Dell          | Latitude 7400               | Notebook    | [7f20623ac0](https://linux-hardware.org/?probe=7f20623ac0) | Apr 28, 2022 |
| ASUSTek       | UX32VD                      | Notebook    | [6f956cd55c](https://linux-hardware.org/?probe=6f956cd55c) | Apr 23, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [3a052b2111](https://linux-hardware.org/?probe=3a052b2111) | Apr 21, 2022 |
| Acer          | Aspire V7-482PG             | Notebook    | [40eb526de9](https://linux-hardware.org/?probe=40eb526de9) | Apr 18, 2022 |
| ASUSTek       | D540MA-C                    | Desktop     | [f8639b84f5](https://linux-hardware.org/?probe=f8639b84f5) | Apr 16, 2022 |
| Acer          | Aspire 5755G                | Notebook    | [e13fc569ce](https://linux-hardware.org/?probe=e13fc569ce) | Apr 13, 2022 |
| Lenovo        | Legion Y730-15ICH 81HD      | Notebook    | [9ad8e2f080](https://linux-hardware.org/?probe=9ad8e2f080) | Apr 13, 2022 |
| HP            | 250 G4 Notebook PC          | Notebook    | [7f35e9e656](https://linux-hardware.org/?probe=7f35e9e656) | Apr 09, 2022 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [f242f094a9](https://linux-hardware.org/?probe=f242f094a9) | Apr 09, 2022 |
| Lenovo        | ThinkPad 10 2nd 20E30035... | Tablet      | [76ddd6a6bc](https://linux-hardware.org/?probe=76ddd6a6bc) | Apr 07, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [05569f49ca](https://linux-hardware.org/?probe=05569f49ca) | Apr 04, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [a94e9d5553](https://linux-hardware.org/?probe=a94e9d5553) | Apr 01, 2022 |
| Lenovo        | NO DPK                      | Desktop     | [7cff95afcb](https://linux-hardware.org/?probe=7cff95afcb) | Mar 27, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [22e95f050f](https://linux-hardware.org/?probe=22e95f050f) | Mar 26, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [4599ef9d23](https://linux-hardware.org/?probe=4599ef9d23) | Mar 26, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [b0cf6455ae](https://linux-hardware.org/?probe=b0cf6455ae) | Mar 24, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [552d30ae49](https://linux-hardware.org/?probe=552d30ae49) | Mar 22, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [16b2681039](https://linux-hardware.org/?probe=16b2681039) | Mar 19, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [9e98e995e7](https://linux-hardware.org/?probe=9e98e995e7) | Mar 18, 2022 |
| MSI           | H61M-E22                    | Desktop     | [1ce895a81c](https://linux-hardware.org/?probe=1ce895a81c) | Mar 17, 2022 |
| Acer          | Aspire 5820                 | Notebook    | [5288ae7fc8](https://linux-hardware.org/?probe=5288ae7fc8) | Mar 17, 2022 |
| ASUSTek       | PRIME Z690M-PLUS D4         | Desktop     | [a6560af3a5](https://linux-hardware.org/?probe=a6560af3a5) | Mar 11, 2022 |
| ASUSTek       | N550JV                      | Notebook    | [0d64cbab8e](https://linux-hardware.org/?probe=0d64cbab8e) | Mar 08, 2022 |
| ASUSTek       | Z97-DELUXE                  | Desktop     | [8b2771b584](https://linux-hardware.org/?probe=8b2771b584) | Mar 07, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZW... | Notebook    | [9fd12bdd29](https://linux-hardware.org/?probe=9fd12bdd29) | Mar 06, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [48c1285eec](https://linux-hardware.org/?probe=48c1285eec) | Mar 02, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZW... | Notebook    | [206f3a7c01](https://linux-hardware.org/?probe=206f3a7c01) | Mar 02, 2022 |
| Dell          | Latitude 5411               | Notebook    | [c6e4b5cf11](https://linux-hardware.org/?probe=c6e4b5cf11) | Mar 02, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [f1d191a15c](https://linux-hardware.org/?probe=f1d191a15c) | Mar 02, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [46656cb5cc](https://linux-hardware.org/?probe=46656cb5cc) | Mar 02, 2022 |
| Samsung       | Galaxy Book 12 LTE          | Tablet      | [63caa45089](https://linux-hardware.org/?probe=63caa45089) | Mar 01, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [376b49560d](https://linux-hardware.org/?probe=376b49560d) | Feb 28, 2022 |
| ASUSTek       | H97M-E                      | Desktop     | [e55893075e](https://linux-hardware.org/?probe=e55893075e) | Feb 28, 2022 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [1398ef93be](https://linux-hardware.org/?probe=1398ef93be) | Feb 22, 2022 |
| Dell          | 0WN7Y6 A01                  | Desktop     | [ef36ccb6ab](https://linux-hardware.org/?probe=ef36ccb6ab) | Feb 22, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [cf906c0ca1](https://linux-hardware.org/?probe=cf906c0ca1) | Feb 20, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [807790386b](https://linux-hardware.org/?probe=807790386b) | Feb 20, 2022 |
| Dell          | Studio 1555                 | Notebook    | [19d02a6eb8](https://linux-hardware.org/?probe=19d02a6eb8) | Feb 20, 2022 |
| ASUSTek       | S400CA                      | Notebook    | [56c75c35b6](https://linux-hardware.org/?probe=56c75c35b6) | Feb 19, 2022 |
| Dell          | Latitude E6330              | Notebook    | [4d2f890592](https://linux-hardware.org/?probe=4d2f890592) | Feb 17, 2022 |
| ASUSTek       | M5A78L-M LX3 PLUS           | Desktop     | [9295ca6d10](https://linux-hardware.org/?probe=9295ca6d10) | Feb 13, 2022 |
| Gigabyte      | H55M-D2H                    | Desktop     | [f85ece5bf7](https://linux-hardware.org/?probe=f85ece5bf7) | Feb 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [331b62c0e9](https://linux-hardware.org/?probe=331b62c0e9) | Feb 11, 2022 |
| Gigabyte      | B460M DS3H                  | Desktop     | [136ea58ce8](https://linux-hardware.org/?probe=136ea58ce8) | Feb 11, 2022 |
| Shuttle       | FH87                        | Desktop     | [1588ed0352](https://linux-hardware.org/?probe=1588ed0352) | Feb 09, 2022 |
| Lenovo        | ThinkCentre M91p 4518NR8    | Desktop     | [cc2ea0bba2](https://linux-hardware.org/?probe=cc2ea0bba2) | Feb 08, 2022 |
| HP            | 2B34                        | Desktop     | [a44a14f358](https://linux-hardware.org/?probe=a44a14f358) | Feb 08, 2022 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [52699a1847](https://linux-hardware.org/?probe=52699a1847) | Feb 07, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [081fe975ce](https://linux-hardware.org/?probe=081fe975ce) | Feb 07, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [310e0596c7](https://linux-hardware.org/?probe=310e0596c7) | Feb 05, 2022 |
| ASUSTek       | WS-C621E-SAGE Series        | Server      | [3035fdad91](https://linux-hardware.org/?probe=3035fdad91) | Feb 03, 2022 |
| ASUSTek       | WS-C621E-SAGE Series        | Server      | [46a851b841](https://linux-hardware.org/?probe=46a851b841) | Feb 02, 2022 |
| Alienware     | 07W25T A00                  | Desktop     | [0bd0a24a20](https://linux-hardware.org/?probe=0bd0a24a20) | Feb 02, 2022 |
| Alienware     | 07W25T A00                  | Desktop     | [852eb2b367](https://linux-hardware.org/?probe=852eb2b367) | Feb 02, 2022 |
| Lenovo        | ThinkCentre M91p 4524B96    | Desktop     | [5a90acd016](https://linux-hardware.org/?probe=5a90acd016) | Jan 31, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [1dfd5b5461](https://linux-hardware.org/?probe=1dfd5b5461) | Jan 23, 2022 |
| Lenovo        | Yoga 710-15IKB 80V5         | Convertible | [3d5fe9fc42](https://linux-hardware.org/?probe=3d5fe9fc42) | Jan 22, 2022 |
| Gigabyte      | Z97X-Gaming 5               | Desktop     | [80213a278f](https://linux-hardware.org/?probe=80213a278f) | Jan 20, 2022 |
| Dell          | Latitude 3350               | Notebook    | [682af42b93](https://linux-hardware.org/?probe=682af42b93) | Jan 18, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [8ab84f13d3](https://linux-hardware.org/?probe=8ab84f13d3) | Jan 14, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [50669a06d2](https://linux-hardware.org/?probe=50669a06d2) | Jan 14, 2022 |
| Gigabyte      | B460 HD3                    | Desktop     | [48e8e52d84](https://linux-hardware.org/?probe=48e8e52d84) | Jan 13, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [8fd207e668](https://linux-hardware.org/?probe=8fd207e668) | Jan 10, 2022 |
| ASUSTek       | PRIME B560M-K               | Desktop     | [b44e84f8a6](https://linux-hardware.org/?probe=b44e84f8a6) | Jan 06, 2022 |
| Supermicro    | X9DAi                       | Desktop     | [0f78e87ab1](https://linux-hardware.org/?probe=0f78e87ab1) | Jan 03, 2022 |
| Supermicro    | X9DAi                       | Desktop     | [a86bdc7f4d](https://linux-hardware.org/?probe=a86bdc7f4d) | Jan 03, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [7dcf51eb69](https://linux-hardware.org/?probe=7dcf51eb69) | Jan 01, 2022 |
| Dell          | Vostro 3560                 | Notebook    | [ffc754462f](https://linux-hardware.org/?probe=ffc754462f) | Dec 30, 2021 |
| Dell          | Vostro 3560                 | Notebook    | [cd630222d7](https://linux-hardware.org/?probe=cd630222d7) | Dec 30, 2021 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [195c9a8567](https://linux-hardware.org/?probe=195c9a8567) | Dec 29, 2021 |
| Acer          | Aspire 5755G                | Notebook    | [14f60e1eef](https://linux-hardware.org/?probe=14f60e1eef) | Dec 28, 2021 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [b525e5f8c0](https://linux-hardware.org/?probe=b525e5f8c0) | Dec 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [23db048750](https://linux-hardware.org/?probe=23db048750) | Dec 27, 2021 |
| Gigabyte      | B75M-D3V                    | Desktop     | [0f43701ca4](https://linux-hardware.org/?probe=0f43701ca4) | Dec 20, 2021 |
| Gigabyte      | P55-UD3L                    | Desktop     | [6d2be9add8](https://linux-hardware.org/?probe=6d2be9add8) | Dec 17, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [39491139d5](https://linux-hardware.org/?probe=39491139d5) | Dec 15, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [615d071a26](https://linux-hardware.org/?probe=615d071a26) | Dec 15, 2021 |
| AZW           | U59                         | Desktop     | [021639604a](https://linux-hardware.org/?probe=021639604a) | Dec 15, 2021 |
| HP            | 240 G6 Notebook PC          | Notebook    | [0eee85762e](https://linux-hardware.org/?probe=0eee85762e) | Dec 14, 2021 |
| Dell          | Inspiron 3793               | Notebook    | [f986757d36](https://linux-hardware.org/?probe=f986757d36) | Dec 14, 2021 |
| Dell          | Inspiron 3793               | Notebook    | [8462457866](https://linux-hardware.org/?probe=8462457866) | Dec 14, 2021 |
| Gigabyte      | Z270XP-SLI-CF               | Desktop     | [2f4124145a](https://linux-hardware.org/?probe=2f4124145a) | Dec 01, 2021 |
| Intel         | NUC8BEB J72692-303          | Mini pc     | [d4f31ef495](https://linux-hardware.org/?probe=d4f31ef495) | Dec 01, 2021 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [a5e249d28f](https://linux-hardware.org/?probe=a5e249d28f) | Nov 30, 2021 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [df4d55c39b](https://linux-hardware.org/?probe=df4d55c39b) | Nov 26, 2021 |
| ASUSTek       | UX331UA                     | Notebook    | [7aee71ceed](https://linux-hardware.org/?probe=7aee71ceed) | Nov 24, 2021 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | Notebook    | [540612a510](https://linux-hardware.org/?probe=540612a510) | Nov 23, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [840d920fb2](https://linux-hardware.org/?probe=840d920fb2) | Nov 22, 2021 |
| Intel         | NUC8BEB J72693-304          | Mini pc     | [8d8d873287](https://linux-hardware.org/?probe=8d8d873287) | Nov 20, 2021 |
| ASUSTek       | PRIME B560M-K               | Desktop     | [571e7e5de4](https://linux-hardware.org/?probe=571e7e5de4) | Nov 19, 2021 |
| Gigabyte      | H87-D3H-CF                  | Desktop     | [72fdde33b3](https://linux-hardware.org/?probe=72fdde33b3) | Nov 19, 2021 |
| Gigabyte      | B460 HD3                    | Desktop     | [19bfb20536](https://linux-hardware.org/?probe=19bfb20536) | Nov 19, 2021 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | Notebook    | [ba96dd251c](https://linux-hardware.org/?probe=ba96dd251c) | Nov 17, 2021 |
| ASRock        | H370M Pro4                  | Desktop     | [63042f539f](https://linux-hardware.org/?probe=63042f539f) | Nov 17, 2021 |
| Dell          | Inspiron 3581               | Notebook    | [7025bc6055](https://linux-hardware.org/?probe=7025bc6055) | Nov 16, 2021 |
| ASUSTek       | BU403UAV                    | Notebook    | [cb7fcf5c15](https://linux-hardware.org/?probe=cb7fcf5c15) | Nov 15, 2021 |
| Gigabyte      | B560M H                     | Desktop     | [358ab5a9fe](https://linux-hardware.org/?probe=358ab5a9fe) | Nov 15, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [eb3074bfdc](https://linux-hardware.org/?probe=eb3074bfdc) | Nov 14, 2021 |
| ASUSTek       | GL502VMK                    | Notebook    | [78bc4b00c0](https://linux-hardware.org/?probe=78bc4b00c0) | Nov 12, 2021 |
| Intel         | NUC8BEB J72693-304          | Mini pc     | [55b02178a3](https://linux-hardware.org/?probe=55b02178a3) | Nov 11, 2021 |
| Dell          | XPS 15 9510                 | Notebook    | [b95625ab23](https://linux-hardware.org/?probe=b95625ab23) | Nov 10, 2021 |
| Gigabyte      | B560M DS3H                  | Desktop     | [05314e56c8](https://linux-hardware.org/?probe=05314e56c8) | Nov 07, 2021 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [b6127e027b](https://linux-hardware.org/?probe=b6127e027b) | Nov 06, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [cab956de97](https://linux-hardware.org/?probe=cab956de97) | Nov 06, 2021 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [4be9b40ea1](https://linux-hardware.org/?probe=4be9b40ea1) | Nov 05, 2021 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [173116149c](https://linux-hardware.org/?probe=173116149c) | Nov 05, 2021 |
| Dell          | Latitude 5410               | Notebook    | [35fd3a8949](https://linux-hardware.org/?probe=35fd3a8949) | Nov 04, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [28366fcde0](https://linux-hardware.org/?probe=28366fcde0) | Nov 04, 2021 |
| Fujitsu       | LIFEBOOK AH532              | Notebook    | [c5e111be13](https://linux-hardware.org/?probe=c5e111be13) | Nov 04, 2021 |
| Fujitsu       | LIFEBOOK AH532              | Notebook    | [6cc81555db](https://linux-hardware.org/?probe=6cc81555db) | Nov 04, 2021 |
| Dell          | 0XHGV1 A00                  | Desktop     | [e221c43af2](https://linux-hardware.org/?probe=e221c43af2) | Oct 27, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [ed20604458](https://linux-hardware.org/?probe=ed20604458) | Oct 26, 2021 |
| Dell          | System Inspiron N7110       | Notebook    | [3f5d6aaab8](https://linux-hardware.org/?probe=3f5d6aaab8) | Oct 26, 2021 |
| Dell          | 0V8F20 A01                  | Desktop     | [8e371fe4cb](https://linux-hardware.org/?probe=8e371fe4cb) | Oct 24, 2021 |
| MSI           | G41TM-P33                   | Desktop     | [8216f8bfae](https://linux-hardware.org/?probe=8216f8bfae) | Oct 24, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [b792457755](https://linux-hardware.org/?probe=b792457755) | Oct 21, 2021 |
| Foxconn       | H81MXV FAB A                | Desktop     | [b030daf542](https://linux-hardware.org/?probe=b030daf542) | Oct 20, 2021 |
| Lenovo        | G40-70 20369                | Notebook    | [c8606a3a2a](https://linux-hardware.org/?probe=c8606a3a2a) | Oct 20, 2021 |
| ASUSTek       | Z170-K                      | Desktop     | [b39ed56cc9](https://linux-hardware.org/?probe=b39ed56cc9) | Oct 19, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [aa3b1b645e](https://linux-hardware.org/?probe=aa3b1b645e) | Oct 16, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [b8d00b123f](https://linux-hardware.org/?probe=b8d00b123f) | Oct 16, 2021 |
| ASUSTek       | Rampage II Extreme          | Desktop     | [e3149252a0](https://linux-hardware.org/?probe=e3149252a0) | Oct 16, 2021 |
| ASUSTek       | Rampage II Extreme          | Desktop     | [b78fec94ab](https://linux-hardware.org/?probe=b78fec94ab) | Oct 16, 2021 |
| Dell          | 0XHGV1 A00                  | Desktop     | [853a82796c](https://linux-hardware.org/?probe=853a82796c) | Oct 15, 2021 |
| Dell          | Inspiron 3593               | Notebook    | [28136dcca0](https://linux-hardware.org/?probe=28136dcca0) | Oct 13, 2021 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [f86adc0f8d](https://linux-hardware.org/?probe=f86adc0f8d) | Oct 12, 2021 |
| ASUSTek       | ROG Strix G512LI_G512LI     | Notebook    | [267712392b](https://linux-hardware.org/?probe=267712392b) | Oct 11, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [f850c51db9](https://linux-hardware.org/?probe=f850c51db9) | Oct 10, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c9ef1c033f](https://linux-hardware.org/?probe=c9ef1c033f) | Oct 09, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [688258aedb](https://linux-hardware.org/?probe=688258aedb) | Oct 01, 2021 |
| Notebook      | N2x0WU                      | Notebook    | [410a2dab96](https://linux-hardware.org/?probe=410a2dab96) | Sep 28, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [3e85c5d96f](https://linux-hardware.org/?probe=3e85c5d96f) | Sep 27, 2021 |
| HP            | 1497                        | Desktop     | [fcfd0c8e49](https://linux-hardware.org/?probe=fcfd0c8e49) | Sep 27, 2021 |
| Dell          | Latitude 5420               | Notebook    | [a31b3507c4](https://linux-hardware.org/?probe=a31b3507c4) | Sep 26, 2021 |
| Dell          | Latitude 5420               | Notebook    | [a077664ed2](https://linux-hardware.org/?probe=a077664ed2) | Sep 26, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [ab36263477](https://linux-hardware.org/?probe=ab36263477) | Sep 25, 2021 |
| ASUSTek       | H81M-E R2.0                 | Desktop     | [18852b576b](https://linux-hardware.org/?probe=18852b576b) | Sep 24, 2021 |
| Lenovo        | G40-70 20369                | Notebook    | [e79a9eb09d](https://linux-hardware.org/?probe=e79a9eb09d) | Sep 22, 2021 |
| HP            | EliteBook x360 1040 G6      | Convertible | [7e2118517f](https://linux-hardware.org/?probe=7e2118517f) | Sep 17, 2021 |
| Lenovo        | G50-80 80L0                 | Notebook    | [b818d8d0f6](https://linux-hardware.org/?probe=b818d8d0f6) | Sep 17, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [229830926d](https://linux-hardware.org/?probe=229830926d) | Sep 13, 2021 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [28ce3a6f8d](https://linux-hardware.org/?probe=28ce3a6f8d) | Sep 13, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [41894dc479](https://linux-hardware.org/?probe=41894dc479) | Sep 10, 2021 |
| Dell          | Vostro 7590                 | Notebook    | [8f4e694845](https://linux-hardware.org/?probe=8f4e694845) | Sep 10, 2021 |
| Lenovo        | G50-80 80L0                 | Notebook    | [46e1004405](https://linux-hardware.org/?probe=46e1004405) | Sep 10, 2021 |
| ITI LIMITE... | SMAASH XU3i                 | Desktop     | [10c0154577](https://linux-hardware.org/?probe=10c0154577) | Sep 10, 2021 |
| Dell          | Vostro 3580                 | Notebook    | [38098784dd](https://linux-hardware.org/?probe=38098784dd) | Sep 09, 2021 |
| Lenovo        | ThinkPad T410 2522WZN       | Notebook    | [b6c19325a4](https://linux-hardware.org/?probe=b6c19325a4) | Sep 09, 2021 |
| Dell          | Vostro 3580                 | Notebook    | [e480169372](https://linux-hardware.org/?probe=e480169372) | Sep 09, 2021 |
| HP            | ProBook 4520s               | Notebook    | [4f947f1b22](https://linux-hardware.org/?probe=4f947f1b22) | Sep 06, 2021 |
| HP            | ProBook 4520s               | Notebook    | [fac0dbdf09](https://linux-hardware.org/?probe=fac0dbdf09) | Sep 06, 2021 |
| ASUSTek       | Z170-K                      | Desktop     | [e5e1953ed8](https://linux-hardware.org/?probe=e5e1953ed8) | Sep 05, 2021 |
| HP            | 158A                        | Desktop     | [6c22e51bfc](https://linux-hardware.org/?probe=6c22e51bfc) | Sep 04, 2021 |
| HP            | Spectre Notebook            | Notebook    | [6a3406a77f](https://linux-hardware.org/?probe=6a3406a77f) | Sep 02, 2021 |
| HP            | Spectre Notebook            | Notebook    | [9966ff0b8f](https://linux-hardware.org/?probe=9966ff0b8f) | Sep 02, 2021 |
| Apple         | MacBookPro12,1              | Notebook    | [79010f7e30](https://linux-hardware.org/?probe=79010f7e30) | Aug 31, 2021 |
| Dell          | 06X1TJ A00                  | Desktop     | [f2e7416585](https://linux-hardware.org/?probe=f2e7416585) | Aug 25, 2021 |
| HP            | Compaq Presario CQ61        | Notebook    | [c7c1d06954](https://linux-hardware.org/?probe=c7c1d06954) | Aug 21, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [17afc04962](https://linux-hardware.org/?probe=17afc04962) | Aug 16, 2021 |
| ASUSTek       | PRIME Z370-P II             | Desktop     | [68213450a7](https://linux-hardware.org/?probe=68213450a7) | Aug 14, 2021 |
| Lenovo        | 3102 SDK0K13476 WIN 3306... | Desktop     | [594b4ac16a](https://linux-hardware.org/?probe=594b4ac16a) | Aug 14, 2021 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [0ca5c5faa2](https://linux-hardware.org/?probe=0ca5c5faa2) | Aug 11, 2021 |
| IP3 Tech      | AP1                         | Notebook    | [b27a94c64c](https://linux-hardware.org/?probe=b27a94c64c) | Aug 08, 2021 |
| Dell          | Latitude 5410               | Notebook    | [4f2e0ccb9f](https://linux-hardware.org/?probe=4f2e0ccb9f) | Aug 04, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [eaa9723b34](https://linux-hardware.org/?probe=eaa9723b34) | Aug 03, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [37cbdcae11](https://linux-hardware.org/?probe=37cbdcae11) | Aug 03, 2021 |
| Apple         | Mac-F2268CC8                | All in one  | [cab34266f1](https://linux-hardware.org/?probe=cab34266f1) | Aug 02, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [6c6c327314](https://linux-hardware.org/?probe=6c6c327314) | Aug 02, 2021 |
| Dell          | Latitude 5410               | Notebook    | [73c46f7a65](https://linux-hardware.org/?probe=73c46f7a65) | Aug 01, 2021 |
| Dell          | Latitude 5410               | Notebook    | [8357a0ce64](https://linux-hardware.org/?probe=8357a0ce64) | Aug 01, 2021 |
| Gigabyte      | X58-USB3                    | Desktop     | [8a48f8d2bc](https://linux-hardware.org/?probe=8a48f8d2bc) | Jul 31, 2021 |
| Gigabyte      | Z270XP-SLI-CF               | Desktop     | [10ca0bf6bd](https://linux-hardware.org/?probe=10ca0bf6bd) | Jul 30, 2021 |
| ASUSTek       | P8P67 DELUXE                | Desktop     | [fef6712b2e](https://linux-hardware.org/?probe=fef6712b2e) | Jul 27, 2021 |
| HP            | Unknown                     | Notebook    | [f048334d4b](https://linux-hardware.org/?probe=f048334d4b) | Jul 21, 2021 |
| Dell          | Latitude E4300              | Notebook    | [3310bfe342](https://linux-hardware.org/?probe=3310bfe342) | Jul 20, 2021 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [1c9f5ba40f](https://linux-hardware.org/?probe=1c9f5ba40f) | Jul 20, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c74efec985](https://linux-hardware.org/?probe=c74efec985) | Jul 19, 2021 |
| Dell          | 06X1TJ A00                  | Desktop     | [942e69cf0e](https://linux-hardware.org/?probe=942e69cf0e) | Jul 11, 2021 |
| Dell          | 06X1TJ A00                  | Desktop     | [bdd432febf](https://linux-hardware.org/?probe=bdd432febf) | Jul 04, 2021 |
| Dell          | 06X1TJ A00                  | Desktop     | [49b9a37043](https://linux-hardware.org/?probe=49b9a37043) | Jul 03, 2021 |
| Dell          | 0GMM0G A00                  | Desktop     | [2c9050ccd9](https://linux-hardware.org/?probe=2c9050ccd9) | Jul 03, 2021 |
| Gigabyte      | Z270XP-SLI-CF               | Desktop     | [1ef68fcd87](https://linux-hardware.org/?probe=1ef68fcd87) | Jul 02, 2021 |
| Apple         | MacBookAir4,2               | Notebook    | [d479a6fd61](https://linux-hardware.org/?probe=d479a6fd61) | Jun 29, 2021 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | Notebook    | [d96ffce12a](https://linux-hardware.org/?probe=d96ffce12a) | Jun 27, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [13ed380099](https://linux-hardware.org/?probe=13ed380099) | Jun 24, 2021 |
| HP            | Notebook                    | Notebook    | [c3f23110da](https://linux-hardware.org/?probe=c3f23110da) | Jun 24, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [79f64eaadf](https://linux-hardware.org/?probe=79f64eaadf) | Jun 19, 2021 |
| HP            | Notebook                    | Notebook    | [daae35477b](https://linux-hardware.org/?probe=daae35477b) | Jun 19, 2021 |
| Pegatron      | 2A94h                       | Desktop     | [5475faba11](https://linux-hardware.org/?probe=5475faba11) | Jun 19, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [988cd2f5ee](https://linux-hardware.org/?probe=988cd2f5ee) | Jun 15, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [232ecea688](https://linux-hardware.org/?probe=232ecea688) | Jun 15, 2021 |
| Gigabyte      | B360M HD3                   | Desktop     | [666afe018d](https://linux-hardware.org/?probe=666afe018d) | Jun 14, 2021 |
| Gigabyte      | B360M HD3                   | Desktop     | [bed714271e](https://linux-hardware.org/?probe=bed714271e) | Jun 14, 2021 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [59cf3396c0](https://linux-hardware.org/?probe=59cf3396c0) | Jun 13, 2021 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [ecec039fdb](https://linux-hardware.org/?probe=ecec039fdb) | Jun 13, 2021 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [276793666d](https://linux-hardware.org/?probe=276793666d) | Jun 13, 2021 |
| ASRock        | H370M Pro4                  | Desktop     | [5d36394bec](https://linux-hardware.org/?probe=5d36394bec) | Jun 08, 2021 |
| Dell          | Vostro 5590                 | Notebook    | [debb5f4ac5](https://linux-hardware.org/?probe=debb5f4ac5) | Jun 07, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [aea7394e24](https://linux-hardware.org/?probe=aea7394e24) | Jun 01, 2021 |
| Intel         | NUC7i5BNB J31144-311        | Mini pc     | [38d5c55bd7](https://linux-hardware.org/?probe=38d5c55bd7) | May 31, 2021 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [e334fad2cc](https://linux-hardware.org/?probe=e334fad2cc) | May 30, 2021 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [f17aef391a](https://linux-hardware.org/?probe=f17aef391a) | May 28, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [ee70288bc8](https://linux-hardware.org/?probe=ee70288bc8) | May 27, 2021 |
| Intel         | DP55WB AAE64798-205         | Desktop     | [a760607f4e](https://linux-hardware.org/?probe=a760607f4e) | May 27, 2021 |
| Gigabyte      | B450 AORUS M                | Desktop     | [a7a67287a3](https://linux-hardware.org/?probe=a7a67287a3) | May 26, 2021 |
| Acer          | Aspire 4333                 | Notebook    | [9f3738469d](https://linux-hardware.org/?probe=9f3738469d) | May 24, 2021 |
| Intel         | DP55WB AAE64798-205         | Desktop     | [7070bcfa9a](https://linux-hardware.org/?probe=7070bcfa9a) | May 24, 2021 |
| Gigabyte      | H61M-S1                     | Desktop     | [2f7da43eb2](https://linux-hardware.org/?probe=2f7da43eb2) | May 23, 2021 |
| ASUSTek       | PRIME Z590M-PLUS            | Desktop     | [a1b3c9d405](https://linux-hardware.org/?probe=a1b3c9d405) | May 19, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [c2267f8dd1](https://linux-hardware.org/?probe=c2267f8dd1) | May 19, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [d139816804](https://linux-hardware.org/?probe=d139816804) | May 16, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [6fe368312c](https://linux-hardware.org/?probe=6fe368312c) | May 15, 2021 |
| Lenovo        | G510 20238                  | Notebook    | [9497cc9d85](https://linux-hardware.org/?probe=9497cc9d85) | May 15, 2021 |
| Dell          | Latitude E4300              | Notebook    | [7ed9015fd5](https://linux-hardware.org/?probe=7ed9015fd5) | May 10, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [ab559fd00d](https://linux-hardware.org/?probe=ab559fd00d) | May 09, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [8bf60ca353](https://linux-hardware.org/?probe=8bf60ca353) | May 08, 2021 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [c72aec456a](https://linux-hardware.org/?probe=c72aec456a) | May 06, 2021 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [c8a2e1e897](https://linux-hardware.org/?probe=c8a2e1e897) | May 06, 2021 |
| LG Electro... | 15Z980-A.AAS8U1             | Notebook    | [2a68dcd848](https://linux-hardware.org/?probe=2a68dcd848) | May 03, 2021 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [e0e3552e96](https://linux-hardware.org/?probe=e0e3552e96) | Apr 28, 2021 |
| Apple         | Mac-F22C86C8                | Mini pc     | [f8b00a2f85](https://linux-hardware.org/?probe=f8b00a2f85) | Apr 27, 2021 |
| ASRock        | H370M Pro4                  | Desktop     | [be75ff3da4](https://linux-hardware.org/?probe=be75ff3da4) | Apr 25, 2021 |
| HP            | 3397                        | Desktop     | [08ea9bb12b](https://linux-hardware.org/?probe=08ea9bb12b) | Apr 22, 2021 |
| Gigabyte      | G41MT-S2                    | Desktop     | [0752e29519](https://linux-hardware.org/?probe=0752e29519) | Apr 21, 2021 |
| Gigabyte      | G41MT-S2                    | Desktop     | [6dd3daccc6](https://linux-hardware.org/?probe=6dd3daccc6) | Apr 21, 2021 |
| Dell          | 0J37VM A01                  | Desktop     | [1e2ec488ee](https://linux-hardware.org/?probe=1e2ec488ee) | Apr 21, 2021 |
| Dell          | 0J37VM A01                  | Desktop     | [171825e444](https://linux-hardware.org/?probe=171825e444) | Apr 21, 2021 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [c5109bab9c](https://linux-hardware.org/?probe=c5109bab9c) | Apr 17, 2021 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [95f2d11b2e](https://linux-hardware.org/?probe=95f2d11b2e) | Apr 16, 2021 |
| ASUSTek       | D540MA-C                    | Desktop     | [945b05bee8](https://linux-hardware.org/?probe=945b05bee8) | Apr 16, 2021 |
| ASRock        | H370M Pro4                  | Desktop     | [e6b5c6b72b](https://linux-hardware.org/?probe=e6b5c6b72b) | Apr 11, 2021 |
| Intel         | NUC8BEB J72692-303          | Mini pc     | [23fd0be92f](https://linux-hardware.org/?probe=23fd0be92f) | Apr 10, 2021 |
| ASUSTek       | H97M-E                      | Desktop     | [9881ce611d](https://linux-hardware.org/?probe=9881ce611d) | Apr 09, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [ca15c642d7](https://linux-hardware.org/?probe=ca15c642d7) | Apr 08, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [a5823c243c](https://linux-hardware.org/?probe=a5823c243c) | Apr 02, 2021 |
| Unknown       | Unknown                     | All in one  | [a8185511a2](https://linux-hardware.org/?probe=a8185511a2) | Apr 01, 2021 |
| Unknown       | Unknown                     | All in one  | [f07c298443](https://linux-hardware.org/?probe=f07c298443) | Apr 01, 2021 |
| Dell          | Inspiron 5755               | Notebook    | [fefe0c7d71](https://linux-hardware.org/?probe=fefe0c7d71) | Apr 01, 2021 |
| MSI           | H87-G43 GAMING              | Desktop     | [5bd49fbcea](https://linux-hardware.org/?probe=5bd49fbcea) | Mar 28, 2021 |
| Gigabyte      | G31M-S2C                    | Desktop     | [8d84b967f2](https://linux-hardware.org/?probe=8d84b967f2) | Mar 25, 2021 |
| Gigabyte      | G31M-S2C                    | Desktop     | [91a8d56cfd](https://linux-hardware.org/?probe=91a8d56cfd) | Mar 25, 2021 |
| Dell          | Inspiron 3593               | Notebook    | [4cc755d1c2](https://linux-hardware.org/?probe=4cc755d1c2) | Mar 25, 2021 |
| HP            | Compaq Presario CQ61        | Notebook    | [58db0eef1f](https://linux-hardware.org/?probe=58db0eef1f) | Mar 25, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [f71120521c](https://linux-hardware.org/?probe=f71120521c) | Mar 23, 2021 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | Notebook    | [edf6ab636e](https://linux-hardware.org/?probe=edf6ab636e) | Mar 19, 2021 |
| Gigabyte      | G41M-Combo                  | Desktop     | [feb8706c98](https://linux-hardware.org/?probe=feb8706c98) | Mar 18, 2021 |
| ASRock        | H71M-DGS                    | Desktop     | [30424c4317](https://linux-hardware.org/?probe=30424c4317) | Mar 18, 2021 |
| MSI           | H170A GAMING PRO            | Desktop     | [dd38d014bd](https://linux-hardware.org/?probe=dd38d014bd) | Mar 17, 2021 |
| HP            | ZBook 15 G3                 | Notebook    | [fa7b8613f2](https://linux-hardware.org/?probe=fa7b8613f2) | Mar 16, 2021 |
| Gigabyte      | Z490M                       | Desktop     | [6eecc1d3cc](https://linux-hardware.org/?probe=6eecc1d3cc) | Mar 15, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [ff15d5b8ad](https://linux-hardware.org/?probe=ff15d5b8ad) | Mar 12, 2021 |
| Lenovo        | ThinkCentre M81 5049PA4     | Desktop     | [0fbdab8514](https://linux-hardware.org/?probe=0fbdab8514) | Mar 11, 2021 |
| Gigabyte      | G31M-S2C                    | Desktop     | [7140c5ee85](https://linux-hardware.org/?probe=7140c5ee85) | Mar 11, 2021 |
| Gigabyte      | G31M-S2C                    | Desktop     | [93a598b2c2](https://linux-hardware.org/?probe=93a598b2c2) | Mar 11, 2021 |
| Intel         | DG43RK AAE78175-403         | Desktop     | [942660dca5](https://linux-hardware.org/?probe=942660dca5) | Mar 11, 2021 |
| Gigabyte      | G41M-Combo                  | Desktop     | [2d19cc5e17](https://linux-hardware.org/?probe=2d19cc5e17) | Mar 11, 2021 |
| Lenovo        | ThinkCentre M81 5049PA4     | Desktop     | [99082a91ac](https://linux-hardware.org/?probe=99082a91ac) | Mar 11, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [a50f9abd26](https://linux-hardware.org/?probe=a50f9abd26) | Mar 11, 2021 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [1e4054e9fe](https://linux-hardware.org/?probe=1e4054e9fe) | Mar 09, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [77a787d158](https://linux-hardware.org/?probe=77a787d158) | Mar 08, 2021 |
| Supermicro    | X8DAL                       | Server      | [ef1b6d7f7e](https://linux-hardware.org/?probe=ef1b6d7f7e) | Mar 08, 2021 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [a55964d5d9](https://linux-hardware.org/?probe=a55964d5d9) | Mar 06, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [4336742334](https://linux-hardware.org/?probe=4336742334) | Mar 04, 2021 |
| HUAWEI        | HN-WX9X                     | Notebook    | [fb3d2fc3e9](https://linux-hardware.org/?probe=fb3d2fc3e9) | Mar 03, 2021 |
| HP            | ZBook 15 G6                 | Notebook    | [061392ad81](https://linux-hardware.org/?probe=061392ad81) | Mar 01, 2021 |
| ASUSTek       | GL503VD                     | Notebook    | [d03b00803b](https://linux-hardware.org/?probe=d03b00803b) | Feb 27, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [618d47c042](https://linux-hardware.org/?probe=618d47c042) | Feb 27, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [2fff8b3674](https://linux-hardware.org/?probe=2fff8b3674) | Feb 24, 2021 |
| Gigabyte      | H81-D3                      | Desktop     | [d05b1b3efc](https://linux-hardware.org/?probe=d05b1b3efc) | Feb 22, 2021 |
| ASRock        | H77M                        | Desktop     | [eb7af012c2](https://linux-hardware.org/?probe=eb7af012c2) | Feb 19, 2021 |
| Gigabyte      | G31M-S2C                    | Desktop     | [c2bd3800b7](https://linux-hardware.org/?probe=c2bd3800b7) | Feb 18, 2021 |
| ASUSTek       | PRIME Z370-P II             | Desktop     | [95fc52db78](https://linux-hardware.org/?probe=95fc52db78) | Feb 17, 2021 |
| HUAWEI        | HN-WX9X                     | Notebook    | [2b4a74a520](https://linux-hardware.org/?probe=2b4a74a520) | Feb 16, 2021 |
| HUAWEI        | HN-WX9X                     | Notebook    | [f4c77fc7dc](https://linux-hardware.org/?probe=f4c77fc7dc) | Feb 16, 2021 |
| Dell          | 0M9KCM A02                  | Desktop     | [802f6994df](https://linux-hardware.org/?probe=802f6994df) | Feb 16, 2021 |
| HP            | Compaq Presario CQ61        | Notebook    | [e72ebb6663](https://linux-hardware.org/?probe=e72ebb6663) | Feb 14, 2021 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [aead87bf38](https://linux-hardware.org/?probe=aead87bf38) | Feb 14, 2021 |
| Lenovo        | 3176 NOK                    | Desktop     | [c5216ce396](https://linux-hardware.org/?probe=c5216ce396) | Feb 14, 2021 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | Notebook    | [a2ab510560](https://linux-hardware.org/?probe=a2ab510560) | Feb 14, 2021 |
| MSI           | B150M BAZOOKA               | Desktop     | [66af036f49](https://linux-hardware.org/?probe=66af036f49) | Feb 13, 2021 |
| MSI           | B150M BAZOOKA               | Desktop     | [749beaf127](https://linux-hardware.org/?probe=749beaf127) | Feb 13, 2021 |
| Gigabyte      | B460M D3H                   | Desktop     | [8cdafac5a3](https://linux-hardware.org/?probe=8cdafac5a3) | Feb 13, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [8711f89b6b](https://linux-hardware.org/?probe=8711f89b6b) | Feb 13, 2021 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [351477b72b](https://linux-hardware.org/?probe=351477b72b) | Feb 13, 2021 |
| HP            | Compaq Presario CQ61        | Notebook    | [bcf179fa51](https://linux-hardware.org/?probe=bcf179fa51) | Feb 12, 2021 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [3e8ad6be09](https://linux-hardware.org/?probe=3e8ad6be09) | Feb 10, 2021 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [655d6c5817](https://linux-hardware.org/?probe=655d6c5817) | Feb 06, 2021 |
| Supermicro    | X10DRD-iNT                  | Server      | [21124e85cc](https://linux-hardware.org/?probe=21124e85cc) | Feb 05, 2021 |
| Lenovo        | ThinkPad T580 20L9001YIV    | Notebook    | [799c676c40](https://linux-hardware.org/?probe=799c676c40) | Feb 04, 2021 |
| ASRock        | Z490M-ITX/ac                | Desktop     | [586d4a5a82](https://linux-hardware.org/?probe=586d4a5a82) | Feb 04, 2021 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [017e9abf15](https://linux-hardware.org/?probe=017e9abf15) | Feb 04, 2021 |
| Lenovo        | ThinkPad E550 20DF004RIV    | Notebook    | [23140cf3f9](https://linux-hardware.org/?probe=23140cf3f9) | Jan 29, 2021 |
| Lenovo        | G40-70 20369                | Notebook    | [1763668816](https://linux-hardware.org/?probe=1763668816) | Jan 29, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [e6be0abafb](https://linux-hardware.org/?probe=e6be0abafb) | Jan 28, 2021 |
| Dell          | Latitude E6420              | Notebook    | [9aa53da922](https://linux-hardware.org/?probe=9aa53da922) | Jan 19, 2021 |
| Dell          | Latitude E6420              | Notebook    | [20a4b3769d](https://linux-hardware.org/?probe=20a4b3769d) | Jan 19, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [4df2203870](https://linux-hardware.org/?probe=4df2203870) | Jan 19, 2021 |
| Lenovo        | ThinkPad X61 Tablet 7767... | Notebook    | [65724a4aa6](https://linux-hardware.org/?probe=65724a4aa6) | Jan 18, 2021 |
| Gigabyte      | H97M-D3H                    | Desktop     | [cc4593764d](https://linux-hardware.org/?probe=cc4593764d) | Jan 18, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [1883634f7b](https://linux-hardware.org/?probe=1883634f7b) | Jan 18, 2021 |
| ASUSTek       | ROG Strix G512LW_G512LW     | Notebook    | [23a9e9c5f6](https://linux-hardware.org/?probe=23a9e9c5f6) | Jan 17, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [750413cc61](https://linux-hardware.org/?probe=750413cc61) | Jan 16, 2021 |
| HP            | EliteBook 840 G5            | Notebook    | [71b67a3764](https://linux-hardware.org/?probe=71b67a3764) | Jan 14, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [725729e04e](https://linux-hardware.org/?probe=725729e04e) | Jan 13, 2021 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [9c40fd9781](https://linux-hardware.org/?probe=9c40fd9781) | Jan 13, 2021 |
| Dell          | Inspiron 13-5378            | Notebook    | [94b70d7578](https://linux-hardware.org/?probe=94b70d7578) | Jan 12, 2021 |
| Gigabyte      | Z370 AORUS Gaming K3-CF     | Desktop     | [4723903be4](https://linux-hardware.org/?probe=4723903be4) | Jan 11, 2021 |
| Gigabyte      | P55-UD3L                    | Desktop     | [8c6a5c5e60](https://linux-hardware.org/?probe=8c6a5c5e60) | Jan 10, 2021 |
| ASRock        | H97M Anniversary            | Desktop     | [b630702ecc](https://linux-hardware.org/?probe=b630702ecc) | Jan 10, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [c1eeffc9d8](https://linux-hardware.org/?probe=c1eeffc9d8) | Jan 08, 2021 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [2583ebac59](https://linux-hardware.org/?probe=2583ebac59) | Jan 08, 2021 |
| Gigabyte      | H81M-D2V                    | Desktop     | [b7c82c53b6](https://linux-hardware.org/?probe=b7c82c53b6) | Jan 07, 2021 |
| Dell          | Inspiron 5567               | Notebook    | [0d62d918c5](https://linux-hardware.org/?probe=0d62d918c5) | Jan 07, 2021 |
| HP            | EliteBook 8560p             | Notebook    | [5a3a67e5c3](https://linux-hardware.org/?probe=5a3a67e5c3) | Jan 07, 2021 |
| HP            | EliteBook 8560p             | Notebook    | [f37800ed52](https://linux-hardware.org/?probe=f37800ed52) | Jan 07, 2021 |
| Lenovo        | IdeaPad 720S-14IKB 81BD     | Notebook    | [b8bab31c57](https://linux-hardware.org/?probe=b8bab31c57) | Jan 06, 2021 |
| Dell          | Inspiron 13-5378            | Notebook    | [d55bf78096](https://linux-hardware.org/?probe=d55bf78096) | Jan 06, 2021 |
| Unknown       | G41 Series                  | Desktop     | [578bc526ef](https://linux-hardware.org/?probe=578bc526ef) | Jan 06, 2021 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [0efe5f5a7e](https://linux-hardware.org/?probe=0efe5f5a7e) | Jan 04, 2021 |
| Unknown       | G41 Series                  | Desktop     | [5a6543b6f1](https://linux-hardware.org/?probe=5a6543b6f1) | Jan 03, 2021 |
| Unknown       | Unknown                     | Notebook    | [b364724e53](https://linux-hardware.org/?probe=b364724e53) | Jan 02, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [8d338ea73c](https://linux-hardware.org/?probe=8d338ea73c) | Dec 31, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [ef84edb346](https://linux-hardware.org/?probe=ef84edb346) | Dec 31, 2020 |
| HP            | EliteBook 2570p             | Notebook    | [2ed921327b](https://linux-hardware.org/?probe=2ed921327b) | Dec 30, 2020 |
| ASUSTek       | ROG Strix G531GW_G531GW     | Notebook    | [9448ec4439](https://linux-hardware.org/?probe=9448ec4439) | Dec 30, 2020 |
| ASUSTek       | ROG Strix G531GW_G531GW     | Notebook    | [7cd92f4564](https://linux-hardware.org/?probe=7cd92f4564) | Dec 30, 2020 |
| Unknown       | Unknown                     | Notebook    | [749c45e229](https://linux-hardware.org/?probe=749c45e229) | Dec 29, 2020 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [01024cf86e](https://linux-hardware.org/?probe=01024cf86e) | Dec 27, 2020 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [66fd37cef4](https://linux-hardware.org/?probe=66fd37cef4) | Dec 27, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [c79668f190](https://linux-hardware.org/?probe=c79668f190) | Dec 24, 2020 |
| Lenovo        | IdeaPad Y700 Touch-15ISK... | Notebook    | [56b69fe95e](https://linux-hardware.org/?probe=56b69fe95e) | Dec 23, 2020 |
| Lenovo        | IdeaPad Y700 Touch-15ISK... | Notebook    | [ddc1a4457d](https://linux-hardware.org/?probe=ddc1a4457d) | Dec 22, 2020 |
| Gigabyte      | Z390 UD                     | Desktop     | [b4ebedb0e2](https://linux-hardware.org/?probe=b4ebedb0e2) | Dec 18, 2020 |
| HP            | Pavilion g6                 | Notebook    | [8d41f37972](https://linux-hardware.org/?probe=8d41f37972) | Dec 18, 2020 |
| Nvidia        | Tegra                       | Soc         | [eb55f6a449](https://linux-hardware.org/?probe=eb55f6a449) | Dec 16, 2020 |
| Unknown       | Unknown                     | Notebook    | [e42b0f86e0](https://linux-hardware.org/?probe=e42b0f86e0) | Dec 14, 2020 |
| HUAWEI        | HN-WX9X                     | Notebook    | [5c1982b26c](https://linux-hardware.org/?probe=5c1982b26c) | Dec 08, 2020 |
| HUAWEI        | HN-WX9X                     | Notebook    | [5b58c4ff46](https://linux-hardware.org/?probe=5b58c4ff46) | Dec 08, 2020 |
| HP            | Laptop 15-da1xxx            | Notebook    | [df5f3d5a4d](https://linux-hardware.org/?probe=df5f3d5a4d) | Dec 07, 2020 |
| ASUSTek       | H97M-E                      | Desktop     | [4f0b22ee7f](https://linux-hardware.org/?probe=4f0b22ee7f) | Nov 30, 2020 |
| Dell          | XPS 13 9370                 | Notebook    | [4cbbe5b21a](https://linux-hardware.org/?probe=4cbbe5b21a) | Nov 26, 2020 |
| Lenovo        | Unknown                     | Notebook    | [40c892a262](https://linux-hardware.org/?probe=40c892a262) | Nov 26, 2020 |
| MSI           | X470 GAMING PLUS            | Desktop     | [b5d6fe9f9c](https://linux-hardware.org/?probe=b5d6fe9f9c) | Nov 24, 2020 |
| Gigabyte      | Z270X-UD5-CF                | Desktop     | [f65b9a326b](https://linux-hardware.org/?probe=f65b9a326b) | Nov 21, 2020 |
| Gigabyte      | Z270X-UD5-CF                | Desktop     | [8f674b7608](https://linux-hardware.org/?probe=8f674b7608) | Nov 21, 2020 |
| Lenovo        | Legion 5P 15IMH05H 82AW     | Notebook    | [46d30ce200](https://linux-hardware.org/?probe=46d30ce200) | Nov 20, 2020 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [c42752eed3](https://linux-hardware.org/?probe=c42752eed3) | Nov 19, 2020 |
| Toshiba       | Satellite L755              | Notebook    | [a6e2af6e5b](https://linux-hardware.org/?probe=a6e2af6e5b) | Nov 18, 2020 |
| ASUSTek       | P9X79 LE                    | Desktop     | [1674d3318e](https://linux-hardware.org/?probe=1674d3318e) | Nov 18, 2020 |
| ASUSTek       | P9X79 LE                    | Desktop     | [0ae9d90f3f](https://linux-hardware.org/?probe=0ae9d90f3f) | Nov 18, 2020 |
| Neousys Te... | NVS-8208 Rev. A1            | Server      | [375ec8881d](https://linux-hardware.org/?probe=375ec8881d) | Nov 17, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [2f9457bf32](https://linux-hardware.org/?probe=2f9457bf32) | Nov 17, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [f2e24821f4](https://linux-hardware.org/?probe=f2e24821f4) | Nov 17, 2020 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [accc9c10e5](https://linux-hardware.org/?probe=accc9c10e5) | Nov 16, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e13999e22a](https://linux-hardware.org/?probe=e13999e22a) | Nov 11, 2020 |
| Toshiba       | PORTEGE R700                | Notebook    | [e04b97eabe](https://linux-hardware.org/?probe=e04b97eabe) | Nov 11, 2020 |
| Acer          | Aspire A715-72G             | Notebook    | [90ef23a01c](https://linux-hardware.org/?probe=90ef23a01c) | Nov 11, 2020 |
| Toshiba       | PORTEGE R700                | Notebook    | [4572167747](https://linux-hardware.org/?probe=4572167747) | Nov 10, 2020 |
| Lenovo        | Legion 5P 15IMH05H 82AW     | Notebook    | [21105809e4](https://linux-hardware.org/?probe=21105809e4) | Nov 08, 2020 |
| Neousys Te... | NVS-8208 Rev. A1            | Server      | [22a316e31b](https://linux-hardware.org/?probe=22a316e31b) | Nov 08, 2020 |
| Neousys Te... | NVS-8208 Rev. A1            | Server      | [a1662fff6f](https://linux-hardware.org/?probe=a1662fff6f) | Nov 08, 2020 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [1c3bd52baa](https://linux-hardware.org/?probe=1c3bd52baa) | Nov 05, 2020 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [1b6972fae9](https://linux-hardware.org/?probe=1b6972fae9) | Nov 05, 2020 |
| Dell          | 0CU409                      | Desktop     | [6adb83b2e0](https://linux-hardware.org/?probe=6adb83b2e0) | Nov 04, 2020 |
| Lenovo        | Yoga 3 11 80J8              | Notebook    | [b4f083536f](https://linux-hardware.org/?probe=b4f083536f) | Nov 04, 2020 |
| Lenovo        | ThinkCentre A58 751581G     | Desktop     | [987ed81d7d](https://linux-hardware.org/?probe=987ed81d7d) | Nov 03, 2020 |
| Neousys Te... | NVS-8208 Rev. A1            | Server      | [b0a2e83351](https://linux-hardware.org/?probe=b0a2e83351) | Nov 03, 2020 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [b94cef8d24](https://linux-hardware.org/?probe=b94cef8d24) | Nov 03, 2020 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [c872f1d76f](https://linux-hardware.org/?probe=c872f1d76f) | Nov 03, 2020 |
| Dell          | 0KWVT8 A02                  | Desktop     | [2403e6e21e](https://linux-hardware.org/?probe=2403e6e21e) | Nov 03, 2020 |
| Dell          | Latitude E6330              | Notebook    | [f7e530a8c2](https://linux-hardware.org/?probe=f7e530a8c2) | Nov 02, 2020 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | Notebook    | [e8426a064f](https://linux-hardware.org/?probe=e8426a064f) | Nov 01, 2020 |
| Dell          | 0DR845                      | Desktop     | [c59e7b1e56](https://linux-hardware.org/?probe=c59e7b1e56) | Nov 01, 2020 |
| ASUSTek       | H110M-A                     | Desktop     | [f8fa4c9c31](https://linux-hardware.org/?probe=f8fa4c9c31) | Nov 01, 2020 |
| Dell          | 0KP561                      | Desktop     | [da357993dd](https://linux-hardware.org/?probe=da357993dd) | Oct 31, 2020 |
| Dell          | 0KP561                      | Desktop     | [b14be76868](https://linux-hardware.org/?probe=b14be76868) | Oct 31, 2020 |
| Lenovo        | ThinkPad E480 20KN0062IV    | Notebook    | [fba2fb0e45](https://linux-hardware.org/?probe=fba2fb0e45) | Oct 30, 2020 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | Notebook    | [1a691f72dc](https://linux-hardware.org/?probe=1a691f72dc) | Oct 29, 2020 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | Notebook    | [990f9bb22f](https://linux-hardware.org/?probe=990f9bb22f) | Oct 29, 2020 |
| Dell          | Latitude 7490               | Notebook    | [2d61d426d5](https://linux-hardware.org/?probe=2d61d426d5) | Oct 28, 2020 |
| HP            | 158A                        | Desktop     | [f83412f912](https://linux-hardware.org/?probe=f83412f912) | Oct 27, 2020 |
| Dell          | Latitude 7300               | Notebook    | [ebf99bafc8](https://linux-hardware.org/?probe=ebf99bafc8) | Oct 27, 2020 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [5bd58e33be](https://linux-hardware.org/?probe=5bd58e33be) | Oct 27, 2020 |
| Neousys Te... | NVS-8208 Rev. A1            | Server      | [156543a1d2](https://linux-hardware.org/?probe=156543a1d2) | Oct 26, 2020 |
| HP            | 82B4                        | Desktop     | [d98d676e9c](https://linux-hardware.org/?probe=d98d676e9c) | Oct 26, 2020 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [7c9e9b741c](https://linux-hardware.org/?probe=7c9e9b741c) | Oct 25, 2020 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [d3f4deffa5](https://linux-hardware.org/?probe=d3f4deffa5) | Oct 25, 2020 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [36d289ce92](https://linux-hardware.org/?probe=36d289ce92) | Oct 20, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [e360fd1fa2](https://linux-hardware.org/?probe=e360fd1fa2) | Oct 18, 2020 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [6ba76947d7](https://linux-hardware.org/?probe=6ba76947d7) | Oct 18, 2020 |
| Dell          | Vostro 14 5401              | Notebook    | [89826d13da](https://linux-hardware.org/?probe=89826d13da) | Oct 13, 2020 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [44d70b326c](https://linux-hardware.org/?probe=44d70b326c) | Oct 13, 2020 |
| ASUSTek       | UX430UNR                    | Notebook    | [03dd6f184c](https://linux-hardware.org/?probe=03dd6f184c) | Oct 12, 2020 |
| Dell          | Vostro 14 5401              | Notebook    | [d3f66acd1b](https://linux-hardware.org/?probe=d3f66acd1b) | Oct 12, 2020 |
| HP            | Laptop 15-bs1xx             | Notebook    | [cab83dd9ff](https://linux-hardware.org/?probe=cab83dd9ff) | Oct 12, 2020 |
| Dell          | Vostro 5490                 | Notebook    | [b998e489c5](https://linux-hardware.org/?probe=b998e489c5) | Oct 07, 2020 |
| Intel         | NUC7JYB J67969-403          | Mini pc     | [ba633c064d](https://linux-hardware.org/?probe=ba633c064d) | Oct 05, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [a9d940dd83](https://linux-hardware.org/?probe=a9d940dd83) | Oct 04, 2020 |
| Lenovo        | Legion Y530-15ICH-1060 8... | Notebook    | [c7e2a6001a](https://linux-hardware.org/?probe=c7e2a6001a) | Oct 04, 2020 |
| Dell          | Latitude 7400               | Notebook    | [6eac6cfa15](https://linux-hardware.org/?probe=6eac6cfa15) | Oct 04, 2020 |
| Gigabyte      | B360M HD3                   | Desktop     | [e0aadcb07c](https://linux-hardware.org/?probe=e0aadcb07c) | Oct 04, 2020 |
| Lenovo        | ThinkCentre M81 5049W15     | Desktop     | [986a5e604f](https://linux-hardware.org/?probe=986a5e604f) | Oct 03, 2020 |
| Lenovo        | ThinkPad X230 23247S0       | Notebook    | [f313b0bf1b](https://linux-hardware.org/?probe=f313b0bf1b) | Oct 01, 2020 |
| ASRock        | X399 Taichi                 | Desktop     | [268a9d5625](https://linux-hardware.org/?probe=268a9d5625) | Oct 01, 2020 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [353229fd96](https://linux-hardware.org/?probe=353229fd96) | Sep 29, 2020 |
| Unknown       | Unknown                     | Desktop     | [4ebc73788d](https://linux-hardware.org/?probe=4ebc73788d) | Sep 29, 2020 |
| ASRock        | H97M Anniversary            | Desktop     | [cc0e0f5c04](https://linux-hardware.org/?probe=cc0e0f5c04) | Sep 29, 2020 |
| MSI           | G41M-E43                    | Desktop     | [5a567b1f97](https://linux-hardware.org/?probe=5a567b1f97) | Sep 28, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [c4d11b04b5](https://linux-hardware.org/?probe=c4d11b04b5) | Sep 28, 2020 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [b8c1686e69](https://linux-hardware.org/?probe=b8c1686e69) | Sep 28, 2020 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [33801ffba1](https://linux-hardware.org/?probe=33801ffba1) | Sep 28, 2020 |
| Lenovo        | ThinkCentre M81 5049W15     | Desktop     | [5d73c67b98](https://linux-hardware.org/?probe=5d73c67b98) | Sep 28, 2020 |
| Lenovo        | ThinkPad E14 20RA0036IV     | Notebook    | [d53e57ac10](https://linux-hardware.org/?probe=d53e57ac10) | Sep 25, 2020 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | Notebook    | [9b2604c2e1](https://linux-hardware.org/?probe=9b2604c2e1) | Sep 21, 2020 |
| Lenovo        | ThinkCentre M81 5049W15     | Desktop     | [9c9f5b4cfa](https://linux-hardware.org/?probe=9c9f5b4cfa) | Sep 10, 2020 |
| Gigabyte      | B360M HD3                   | Desktop     | [7521b3b6e2](https://linux-hardware.org/?probe=7521b3b6e2) | Sep 07, 2020 |
| HP            | 339A                        | Desktop     | [109949681c](https://linux-hardware.org/?probe=109949681c) | Sep 06, 2020 |
| Intel         | NUC7JYB J67969-403          | Mini pc     | [24b00b8ca8](https://linux-hardware.org/?probe=24b00b8ca8) | Sep 04, 2020 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [42deb7cee5](https://linux-hardware.org/?probe=42deb7cee5) | Sep 03, 2020 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [5bfd2a1403](https://linux-hardware.org/?probe=5bfd2a1403) | Sep 03, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [f8631e5f4a](https://linux-hardware.org/?probe=f8631e5f4a) | Sep 03, 2020 |
| Dell          | Latitude E5270              | Notebook    | [745e05ba12](https://linux-hardware.org/?probe=745e05ba12) | Aug 31, 2020 |
| MSI           | 2A9Ch                       | Desktop     | [aa629696b3](https://linux-hardware.org/?probe=aa629696b3) | Aug 28, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [eee9972fdf](https://linux-hardware.org/?probe=eee9972fdf) | Aug 28, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [cb7fda5c3f](https://linux-hardware.org/?probe=cb7fda5c3f) | Aug 27, 2020 |
| MSI           | 2A9Ch                       | Desktop     | [0ece5d52d2](https://linux-hardware.org/?probe=0ece5d52d2) | Aug 27, 2020 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [56afe1e282](https://linux-hardware.org/?probe=56afe1e282) | Aug 27, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [99c5924655](https://linux-hardware.org/?probe=99c5924655) | Aug 23, 2020 |
| ASRock        | H97M Anniversary            | Desktop     | [613aba4134](https://linux-hardware.org/?probe=613aba4134) | Aug 23, 2020 |
| Lenovo        | ThinkPad L390 20NR001LIV    | Notebook    | [9fef5634b2](https://linux-hardware.org/?probe=9fef5634b2) | Aug 22, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [ee5213ce49](https://linux-hardware.org/?probe=ee5213ce49) | Aug 19, 2020 |
| Lenovo        | Legion 7 15IMHg05 81YU      | Notebook    | [5f1ce912be](https://linux-hardware.org/?probe=5f1ce912be) | Aug 19, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [635a148f20](https://linux-hardware.org/?probe=635a148f20) | Aug 19, 2020 |
| Toshiba       | Satellite P50t-B-10T        | Notebook    | [0f41a5b6ec](https://linux-hardware.org/?probe=0f41a5b6ec) | Aug 13, 2020 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [a114ae9c9c](https://linux-hardware.org/?probe=a114ae9c9c) | Aug 12, 2020 |
| Lenovo        | SHARKBAY SDK0E50519 WIN     | Desktop     | [1828dedb7f](https://linux-hardware.org/?probe=1828dedb7f) | Aug 10, 2020 |
| Lenovo        | ThinkPad T490 20N20073IV    | Notebook    | [3878e27014](https://linux-hardware.org/?probe=3878e27014) | Aug 10, 2020 |
| ASUSTek       | TUF Gaming B460-PLUS        | Desktop     | [0d864b4feb](https://linux-hardware.org/?probe=0d864b4feb) | Aug 08, 2020 |
| ASUSTek       | TUF Gaming B460-PLUS        | Desktop     | [69e782093d](https://linux-hardware.org/?probe=69e782093d) | Aug 08, 2020 |
| Gigabyte      | Z270-HD3P-CF                | Desktop     | [3fe0ec39fc](https://linux-hardware.org/?probe=3fe0ec39fc) | Aug 07, 2020 |
| ASRock        | H55M                        | Desktop     | [f2d0fa78ac](https://linux-hardware.org/?probe=f2d0fa78ac) | Aug 06, 2020 |
| Apple         | Mac-F22C86C8                | Mini pc     | [6d92297671](https://linux-hardware.org/?probe=6d92297671) | Aug 05, 2020 |
| Nvidia        | Tegra                       | Soc         | [273bc677cd](https://linux-hardware.org/?probe=273bc677cd) | Aug 05, 2020 |
| Supermicro    | X8DAL                       | Server      | [03a282558d](https://linux-hardware.org/?probe=03a282558d) | Aug 05, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [5c3dc530c3](https://linux-hardware.org/?probe=5c3dc530c3) | Aug 04, 2020 |
| Supermicro    | X8DAL                       | Server      | [08cd245e63](https://linux-hardware.org/?probe=08cd245e63) | Aug 03, 2020 |
| Dell          | Latitude 7390 2-in-1        | Notebook    | [fb785080a3](https://linux-hardware.org/?probe=fb785080a3) | Aug 02, 2020 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [38442a922b](https://linux-hardware.org/?probe=38442a922b) | Aug 01, 2020 |
| HP            | ProBook 450 G4              | Notebook    | [e934fab850](https://linux-hardware.org/?probe=e934fab850) | Aug 01, 2020 |
| HP            | ProBook 450 G4              | Notebook    | [38feef34d4](https://linux-hardware.org/?probe=38feef34d4) | Aug 01, 2020 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [6156b4dec2](https://linux-hardware.org/?probe=6156b4dec2) | Aug 01, 2020 |
| Gigabyte      | Z97-HD3                     | Desktop     | [2e41ce3f03](https://linux-hardware.org/?probe=2e41ce3f03) | Jul 31, 2020 |
| Gigabyte      | Z97-HD3                     | Desktop     | [50888e0851](https://linux-hardware.org/?probe=50888e0851) | Jul 31, 2020 |
| ASRock        | H55M                        | Desktop     | [dcbc0735f5](https://linux-hardware.org/?probe=dcbc0735f5) | Jul 30, 2020 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [a7e0318966](https://linux-hardware.org/?probe=a7e0318966) | Jul 30, 2020 |
| ASUSTek       | AT3N7A-I                    | Desktop     | [57c3ce82b7](https://linux-hardware.org/?probe=57c3ce82b7) | Jul 29, 2020 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [ef4f365d92](https://linux-hardware.org/?probe=ef4f365d92) | Jul 24, 2020 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [6126a00ffc](https://linux-hardware.org/?probe=6126a00ffc) | Jul 24, 2020 |
| Dell          | Latitude E6530              | Notebook    | [6e1b2fb388](https://linux-hardware.org/?probe=6e1b2fb388) | Jul 24, 2020 |
| Hardkernel    | ODROID-H2                   | Desktop     | [c86e7dc968](https://linux-hardware.org/?probe=c86e7dc968) | Jul 23, 2020 |
| Lenovo        | V510-15IKB 80WQ             | Notebook    | [3944aa1028](https://linux-hardware.org/?probe=3944aa1028) | Jul 20, 2020 |
| HP            | ProBook 640 G2              | Notebook    | [53ba25afcd](https://linux-hardware.org/?probe=53ba25afcd) | Jul 14, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [6e6f80378d](https://linux-hardware.org/?probe=6e6f80378d) | Jul 11, 2020 |
| Lenovo        | ThinkPad X260 20F60041IV    | Notebook    | [d0aacf7693](https://linux-hardware.org/?probe=d0aacf7693) | Jul 09, 2020 |
| Lenovo        | ThinkPad X260 20F60041IV    | Notebook    | [868953dc99](https://linux-hardware.org/?probe=868953dc99) | Jul 09, 2020 |
| Dell          | Latitude 5400               | Notebook    | [ae1c2d9825](https://linux-hardware.org/?probe=ae1c2d9825) | Jul 08, 2020 |
| Gigabyte      | H61M-S1                     | Desktop     | [2a63a11959](https://linux-hardware.org/?probe=2a63a11959) | Jul 08, 2020 |
| ASUSTek       | UX461UA                     | Convertible | [a294adac80](https://linux-hardware.org/?probe=a294adac80) | Jul 02, 2020 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [52fad4367c](https://linux-hardware.org/?probe=52fad4367c) | Jul 01, 2020 |
| HP            | Pavilion dv6                | Notebook    | [39df31f4c6](https://linux-hardware.org/?probe=39df31f4c6) | Jun 27, 2020 |
| Lenovo        | ThinkPad E14 20RA0016IV     | Notebook    | [2878e88064](https://linux-hardware.org/?probe=2878e88064) | Jun 24, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [866c72927a](https://linux-hardware.org/?probe=866c72927a) | Jun 22, 2020 |
| Dell          | Inspiron 5379               | Notebook    | [f7fe8744d9](https://linux-hardware.org/?probe=f7fe8744d9) | Jun 21, 2020 |
| ASUSTek       | P8Z68-V PRO GEN3            | Desktop     | [311c0852f2](https://linux-hardware.org/?probe=311c0852f2) | Jun 18, 2020 |
| Gigabyte      | G31M-S2C                    | Desktop     | [da847897f9](https://linux-hardware.org/?probe=da847897f9) | Jun 15, 2020 |
| ASUSTek       | UX331UA                     | Notebook    | [064e95c086](https://linux-hardware.org/?probe=064e95c086) | Jun 10, 2020 |
| MSI           | G41M-E43                    | Desktop     | [4c72170ef6](https://linux-hardware.org/?probe=4c72170ef6) | Jun 06, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [2605330e8c](https://linux-hardware.org/?probe=2605330e8c) | Jun 04, 2020 |
| ASUSTek       | UX331UA                     | Notebook    | [8ca766622f](https://linux-hardware.org/?probe=8ca766622f) | Jun 02, 2020 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [1ce6e06069](https://linux-hardware.org/?probe=1ce6e06069) | May 30, 2020 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [48f5173ede](https://linux-hardware.org/?probe=48f5173ede) | May 27, 2020 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [72b226183e](https://linux-hardware.org/?probe=72b226183e) | May 27, 2020 |
| ASUSTek       | F2A85-M PRO                 | Desktop     | [680a98718a](https://linux-hardware.org/?probe=680a98718a) | May 19, 2020 |
| Dell          | Latitude 5490               | Notebook    | [2afe6adf1b](https://linux-hardware.org/?probe=2afe6adf1b) | May 18, 2020 |
| Dell          | Latitude 5490               | Notebook    | [c2b1c12105](https://linux-hardware.org/?probe=c2b1c12105) | May 17, 2020 |
| ASUSTek       | UX331UA                     | Notebook    | [0a0319493d](https://linux-hardware.org/?probe=0a0319493d) | May 15, 2020 |
| Gigabyte      | F2A88XM-DS2                 | Desktop     | [bd5ec5436e](https://linux-hardware.org/?probe=bd5ec5436e) | May 15, 2020 |
| Gigabyte      | F2A88XM-DS2                 | Desktop     | [355e03bb68](https://linux-hardware.org/?probe=355e03bb68) | May 15, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [912c44b0ac](https://linux-hardware.org/?probe=912c44b0ac) | May 15, 2020 |
| HP            | 339A                        | Desktop     | [ab1afaacc9](https://linux-hardware.org/?probe=ab1afaacc9) | May 14, 2020 |
| HP            | G42                         | Notebook    | [6d45062a76](https://linux-hardware.org/?probe=6d45062a76) | May 14, 2020 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [c815568345](https://linux-hardware.org/?probe=c815568345) | May 14, 2020 |
| ASUSTek       | F2A85-M PRO                 | Desktop     | [3edebf56b2](https://linux-hardware.org/?probe=3edebf56b2) | May 13, 2020 |
| Lenovo        | ThinkPad X200 74587DU       | Notebook    | [ba354beaa9](https://linux-hardware.org/?probe=ba354beaa9) | May 10, 2020 |
| ASUSTek       | K54C                        | Notebook    | [c2656ceae6](https://linux-hardware.org/?probe=c2656ceae6) | May 07, 2020 |
| HP            | Pavilion Laptop 14-bf1xx    | Notebook    | [6f86c55589](https://linux-hardware.org/?probe=6f86c55589) | May 04, 2020 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [fc58b96f3e](https://linux-hardware.org/?probe=fc58b96f3e) | May 01, 2020 |
| Gigabyte      | B450M S2H                   | Desktop     | [0fe3c99d58](https://linux-hardware.org/?probe=0fe3c99d58) | Apr 30, 2020 |
| MSI           | G41TM-P33                   | Desktop     | [d1078cd496](https://linux-hardware.org/?probe=d1078cd496) | Apr 29, 2020 |
| Gigabyte      | B450M S2H                   | Desktop     | [d575d16183](https://linux-hardware.org/?probe=d575d16183) | Apr 29, 2020 |
| Gigabyte      | B450M S2H                   | Desktop     | [b5e521462a](https://linux-hardware.org/?probe=b5e521462a) | Apr 29, 2020 |
| Gigabyte      | B450M S2H                   | Desktop     | [fcf5dd997f](https://linux-hardware.org/?probe=fcf5dd997f) | Apr 28, 2020 |
| MSI           | G41TM-P33                   | Desktop     | [3512230c03](https://linux-hardware.org/?probe=3512230c03) | Apr 28, 2020 |
| MSI           | G41TM-P33                   | Desktop     | [a648a57d33](https://linux-hardware.org/?probe=a648a57d33) | Apr 28, 2020 |
| Gigabyte      | Z270XP-SLI-CF               | Desktop     | [20f18f18b8](https://linux-hardware.org/?probe=20f18f18b8) | Apr 27, 2020 |
| Acer          | Swift SF314-54G             | Notebook    | [e93143c6fd](https://linux-hardware.org/?probe=e93143c6fd) | Apr 27, 2020 |
| Dell          | 097YXY A00                  | Desktop     | [baa8d3b29f](https://linux-hardware.org/?probe=baa8d3b29f) | Apr 27, 2020 |
| Acer          | Swift SF314-54G             | Notebook    | [4cc7a86795](https://linux-hardware.org/?probe=4cc7a86795) | Apr 26, 2020 |
| Toshiba       | Satellite A200              | Notebook    | [d9a55aeca2](https://linux-hardware.org/?probe=d9a55aeca2) | Apr 25, 2020 |
| Toshiba       | Satellite A200              | Notebook    | [1e6ea00cd0](https://linux-hardware.org/?probe=1e6ea00cd0) | Apr 25, 2020 |
| ASUSTek       | UX331UA                     | Notebook    | [634f000249](https://linux-hardware.org/?probe=634f000249) | Apr 24, 2020 |
| ASUSTek       | UX331UA                     | Notebook    | [94be2c2ea7](https://linux-hardware.org/?probe=94be2c2ea7) | Apr 24, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [2516b70573](https://linux-hardware.org/?probe=2516b70573) | Apr 23, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [cdcce3c09c](https://linux-hardware.org/?probe=cdcce3c09c) | Apr 23, 2020 |
| MSI           | G41TM-P33                   | Desktop     | [d99b7f2578](https://linux-hardware.org/?probe=d99b7f2578) | Apr 22, 2020 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [434a4a46f9](https://linux-hardware.org/?probe=434a4a46f9) | Apr 19, 2020 |
| Dell          | XPS 13 9350                 | Notebook    | [d718b985ec](https://linux-hardware.org/?probe=d718b985ec) | Apr 18, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [cd641ec5c7](https://linux-hardware.org/?probe=cd641ec5c7) | Apr 17, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [28e6c33fec](https://linux-hardware.org/?probe=28e6c33fec) | Apr 17, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [7e17ce97e9](https://linux-hardware.org/?probe=7e17ce97e9) | Apr 17, 2020 |
| Intel         | NUC8BEB J72688-305          | Mini pc     | [189e02e90e](https://linux-hardware.org/?probe=189e02e90e) | Apr 12, 2020 |
| ASUSTek       | X550CA                      | Notebook    | [d23cc368bb](https://linux-hardware.org/?probe=d23cc368bb) | Apr 10, 2020 |
| Dell          | Latitude 5490               | Notebook    | [6759b030d2](https://linux-hardware.org/?probe=6759b030d2) | Apr 10, 2020 |
| Dell          | Latitude 7300               | Notebook    | [4c263fc2d0](https://linux-hardware.org/?probe=4c263fc2d0) | Apr 01, 2020 |
| HP            | ZBook 15 G3                 | Notebook    | [254c1f48da](https://linux-hardware.org/?probe=254c1f48da) | Mar 31, 2020 |
| Dell          | Latitude 5490               | Notebook    | [03873fa787](https://linux-hardware.org/?probe=03873fa787) | Mar 30, 2020 |
| Dell          | Latitude 5490               | Notebook    | [d71d69d129](https://linux-hardware.org/?probe=d71d69d129) | Mar 30, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [2aab729aee](https://linux-hardware.org/?probe=2aab729aee) | Mar 30, 2020 |
| Gigabyte      | H61M-S1                     | Desktop     | [ade023408c](https://linux-hardware.org/?probe=ade023408c) | Mar 26, 2020 |
| MSI           | B450-A PRO                  | Desktop     | [f9c1a4dd5d](https://linux-hardware.org/?probe=f9c1a4dd5d) | Mar 25, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [9c1238b041](https://linux-hardware.org/?probe=9c1238b041) | Mar 22, 2020 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [e02dd36f39](https://linux-hardware.org/?probe=e02dd36f39) | Mar 22, 2020 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [5c3ecb2c5b](https://linux-hardware.org/?probe=5c3ecb2c5b) | Mar 22, 2020 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [1004ffcce5](https://linux-hardware.org/?probe=1004ffcce5) | Mar 22, 2020 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [e0f2c8f133](https://linux-hardware.org/?probe=e0f2c8f133) | Mar 22, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [b5765e1a9f](https://linux-hardware.org/?probe=b5765e1a9f) | Mar 22, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [3c36d4bdc9](https://linux-hardware.org/?probe=3c36d4bdc9) | Mar 21, 2020 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [03d86fb8e8](https://linux-hardware.org/?probe=03d86fb8e8) | Mar 21, 2020 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [a53152418d](https://linux-hardware.org/?probe=a53152418d) | Mar 14, 2020 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [32428dda92](https://linux-hardware.org/?probe=32428dda92) | Mar 14, 2020 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [5d56415e4c](https://linux-hardware.org/?probe=5d56415e4c) | Mar 14, 2020 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [48afe5fac3](https://linux-hardware.org/?probe=48afe5fac3) | Mar 08, 2020 |
| Lenovo        | ThinkPad T480 20L5A063CD    | Notebook    | [ccd24104da](https://linux-hardware.org/?probe=ccd24104da) | Mar 08, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [d13a02aacb](https://linux-hardware.org/?probe=d13a02aacb) | Mar 08, 2020 |
| ASUSTek       | H81M-K                      | Desktop     | [08d45d3162](https://linux-hardware.org/?probe=08d45d3162) | Mar 07, 2020 |
| Microsoft     | Surface 3                   | Tablet      | [76a25407de](https://linux-hardware.org/?probe=76a25407de) | Feb 26, 2020 |
| HP            | 1495                        | Desktop     | [ff4447983a](https://linux-hardware.org/?probe=ff4447983a) | Feb 22, 2020 |
| Dell          | Inspiron 7548               | Notebook    | [ebce14c87e](https://linux-hardware.org/?probe=ebce14c87e) | Feb 22, 2020 |
| Dell          | Inspiron 7548               | Notebook    | [d4b3df5729](https://linux-hardware.org/?probe=d4b3df5729) | Feb 22, 2020 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [72475e5edb](https://linux-hardware.org/?probe=72475e5edb) | Feb 22, 2020 |
| HP            | 1495                        | Desktop     | [e1d927d5ce](https://linux-hardware.org/?probe=e1d927d5ce) | Feb 16, 2020 |
| HP            | 1495                        | Desktop     | [c9e7f762e4](https://linux-hardware.org/?probe=c9e7f762e4) | Feb 16, 2020 |
| ASUSTek       | X201EP                      | Notebook    | [75d7523e83](https://linux-hardware.org/?probe=75d7523e83) | Feb 13, 2020 |
| Gigabyte      | H110M-DS2 DDR3-CF           | Desktop     | [e2a558c35b](https://linux-hardware.org/?probe=e2a558c35b) | Feb 11, 2020 |
| Lenovo        | ThinkPad L490 20Q5CTO1WW    | Notebook    | [239b2eba6d](https://linux-hardware.org/?probe=239b2eba6d) | Feb 08, 2020 |
| Lenovo        | ThinkPad L490 20Q5CTO1WW    | Notebook    | [a3e9ca6d37](https://linux-hardware.org/?probe=a3e9ca6d37) | Feb 08, 2020 |
| Lenovo        | ThinkPad L490 20Q5CTO1WW    | Notebook    | [60ba0e3d0f](https://linux-hardware.org/?probe=60ba0e3d0f) | Feb 08, 2020 |
| Dell          | Inspiron 13-5378            | Notebook    | [30e38a1812](https://linux-hardware.org/?probe=30e38a1812) | Feb 03, 2020 |
| MSI           | G41TM-P33                   | Desktop     | [524089d286](https://linux-hardware.org/?probe=524089d286) | Jan 29, 2020 |
| HP            | Laptop 15-da1xxx            | Notebook    | [b4ef2a52c5](https://linux-hardware.org/?probe=b4ef2a52c5) | Jan 21, 2020 |
| HP            | Laptop 15-da1xxx            | Notebook    | [33d23400b4](https://linux-hardware.org/?probe=33d23400b4) | Jan 20, 2020 |
| Pegatron      | NARRA5                      | Desktop     | [f0bd8ead24](https://linux-hardware.org/?probe=f0bd8ead24) | Jan 17, 2020 |
| LG Electro... | 15Z990-A.AAS7U1             | Notebook    | [afd7d4caf9](https://linux-hardware.org/?probe=afd7d4caf9) | Jan 15, 2020 |
| Lenovo        | G570 4334                   | Notebook    | [7bf153f618](https://linux-hardware.org/?probe=7bf153f618) | Jan 13, 2020 |
| Lenovo        | ThinkPad E595 20NF0018US    | Notebook    | [00d8e5ba33](https://linux-hardware.org/?probe=00d8e5ba33) | Jan 13, 2020 |
| Lenovo        | G570 4334                   | Notebook    | [a423e910c6](https://linux-hardware.org/?probe=a423e910c6) | Jan 13, 2020 |
| ASRock        | H97M Anniversary            | Desktop     | [221a2cfac8](https://linux-hardware.org/?probe=221a2cfac8) | Jan 13, 2020 |
| Lenovo        | G570 4334                   | Notebook    | [84fcfb4be2](https://linux-hardware.org/?probe=84fcfb4be2) | Jan 07, 2020 |
| Lenovo        | G570 4334                   | Notebook    | [903ab151c8](https://linux-hardware.org/?probe=903ab151c8) | Jan 07, 2020 |
| Lenovo        | G570 4334                   | Notebook    | [495c89d842](https://linux-hardware.org/?probe=495c89d842) | Jan 07, 2020 |
| Dell          | Latitude E7270              | Notebook    | [83f77407ab](https://linux-hardware.org/?probe=83f77407ab) | Jan 06, 2020 |
| Dell          | Latitude E7270              | Notebook    | [dc87d2cdee](https://linux-hardware.org/?probe=dc87d2cdee) | Jan 06, 2020 |
| Dell          | 0GM819                      | Desktop     | [d99391a30c](https://linux-hardware.org/?probe=d99391a30c) | Jan 06, 2020 |
| Dell          | Inspiron MM061              | Notebook    | [3da92e4cab](https://linux-hardware.org/?probe=3da92e4cab) | Jan 02, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [992e2074ff](https://linux-hardware.org/?probe=992e2074ff) | Dec 25, 2019 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [f3b22a675a](https://linux-hardware.org/?probe=f3b22a675a) | Dec 20, 2019 |
| ASUSTek       | UL30A                       | Notebook    | [b7f84b8da0](https://linux-hardware.org/?probe=b7f84b8da0) | Dec 20, 2019 |
| ASUSTek       | X501A                       | Notebook    | [ce99670ceb](https://linux-hardware.org/?probe=ce99670ceb) | Dec 20, 2019 |
| ASUSTek       | X501A                       | Notebook    | [f7a367e32c](https://linux-hardware.org/?probe=f7a367e32c) | Dec 20, 2019 |
| ASUSTek       | A88XM-A/USB                 | Desktop     | [8f93bf715a](https://linux-hardware.org/?probe=8f93bf715a) | Dec 11, 2019 |
| Intel         | NUC7i5BNB J31144-311        | Mini pc     | [145dff2b67](https://linux-hardware.org/?probe=145dff2b67) | Dec 11, 2019 |
| ASRock        | H97M Anniversary            | Desktop     | [831ff4b7fc](https://linux-hardware.org/?probe=831ff4b7fc) | Dec 10, 2019 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [8fbc16ebfa](https://linux-hardware.org/?probe=8fbc16ebfa) | Dec 03, 2019 |
| Gigabyte      | H170-HD3-CF                 | Desktop     | [338994bd66](https://linux-hardware.org/?probe=338994bd66) | Dec 02, 2019 |
| LG Electro... | A310                        | Notebook    | [d2599d1470](https://linux-hardware.org/?probe=d2599d1470) | Nov 26, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [52db21c094](https://linux-hardware.org/?probe=52db21c094) | Nov 24, 2019 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | Notebook    | [831c001466](https://linux-hardware.org/?probe=831c001466) | Nov 23, 2019 |
| HP            | G7000                       | Notebook    | [cb550f69f7](https://linux-hardware.org/?probe=cb550f69f7) | Nov 12, 2019 |
| HP            | G7000                       | Notebook    | [97ada3d9cf](https://linux-hardware.org/?probe=97ada3d9cf) | Nov 12, 2019 |
| HP            | G7000                       | Notebook    | [ca985e708a](https://linux-hardware.org/?probe=ca985e708a) | Nov 12, 2019 |
| ASRock        | G41C-GS                     | Desktop     | [920a88f615](https://linux-hardware.org/?probe=920a88f615) | Nov 08, 2019 |
| HP            | 2B38                        | Desktop     | [8a919fff76](https://linux-hardware.org/?probe=8a919fff76) | Oct 26, 2019 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | Desktop     | [6d5ea39af4](https://linux-hardware.org/?probe=6d5ea39af4) | Oct 26, 2019 |
| Dell          | 0GM819                      | Desktop     | [4468e2e57e](https://linux-hardware.org/?probe=4468e2e57e) | Oct 21, 2019 |
| Lenovo        | ThinkPad T440s 20AQ005TU... | Notebook    | [39c33a8d85](https://linux-hardware.org/?probe=39c33a8d85) | Oct 21, 2019 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [a5e61f3a1a](https://linux-hardware.org/?probe=a5e61f3a1a) | Oct 18, 2019 |
| Dell          | Latitude E6320              | Notebook    | [276041713d](https://linux-hardware.org/?probe=276041713d) | Oct 18, 2019 |
| Dell          | Latitude E6320              | Notebook    | [a2002798ac](https://linux-hardware.org/?probe=a2002798ac) | Oct 18, 2019 |
| Lenovo        | E31-80 80MX                 | Notebook    | [4f5d1ae105](https://linux-hardware.org/?probe=4f5d1ae105) | Oct 17, 2019 |
| Gigabyte      | Z87MX-D3H-CF                | Desktop     | [8a9e5f7293](https://linux-hardware.org/?probe=8a9e5f7293) | Oct 14, 2019 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | Desktop     | [cafdeb1b3a](https://linux-hardware.org/?probe=cafdeb1b3a) | Oct 06, 2019 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [6bc1a600ee](https://linux-hardware.org/?probe=6bc1a600ee) | Oct 06, 2019 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [32944602dd](https://linux-hardware.org/?probe=32944602dd) | Oct 06, 2019 |
| Lenovo        | ThinkPad T440s 20AQ005TU... | Notebook    | [60e8599708](https://linux-hardware.org/?probe=60e8599708) | Sep 30, 2019 |
| HP            | 2B38                        | Desktop     | [f690313ecf](https://linux-hardware.org/?probe=f690313ecf) | Sep 30, 2019 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [2ad6f6b23d](https://linux-hardware.org/?probe=2ad6f6b23d) | Sep 25, 2019 |
| Lenovo        | G560 0679                   | Notebook    | [403cb2c831](https://linux-hardware.org/?probe=403cb2c831) | Sep 19, 2019 |
| Lenovo        | G560 0679                   | Notebook    | [0552d32d91](https://linux-hardware.org/?probe=0552d32d91) | Sep 18, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [77a3bc0e11](https://linux-hardware.org/?probe=77a3bc0e11) | Sep 17, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [eeaadaa0a3](https://linux-hardware.org/?probe=eeaadaa0a3) | Sep 17, 2019 |
| AMI           | Cherry Trail CR             | Desktop     | [0398059e29](https://linux-hardware.org/?probe=0398059e29) | Sep 16, 2019 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | Desktop     | [3bfc472643](https://linux-hardware.org/?probe=3bfc472643) | Sep 15, 2019 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | Desktop     | [d90225cad7](https://linux-hardware.org/?probe=d90225cad7) | Sep 15, 2019 |
| HP            | EliteBook 840 G6            | Notebook    | [4ada1a54ef](https://linux-hardware.org/?probe=4ada1a54ef) | Sep 13, 2019 |
| Lenovo        | Yoga 500-14ISK 80R5         | Notebook    | [b4f1b9249a](https://linux-hardware.org/?probe=b4f1b9249a) | Sep 10, 2019 |
| Dell          | Latitude E7450              | Notebook    | [cb374fcaff](https://linux-hardware.org/?probe=cb374fcaff) | Sep 05, 2019 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [c090add0c0](https://linux-hardware.org/?probe=c090add0c0) | Sep 04, 2019 |
| Dell          | XPS 13 9343                 | Notebook    | [ecb0cffd7b](https://linux-hardware.org/?probe=ecb0cffd7b) | Sep 04, 2019 |
| Dell          | 0GM819                      | Desktop     | [863ec2a484](https://linux-hardware.org/?probe=863ec2a484) | Sep 02, 2019 |
| Dell          | 0GM819                      | Desktop     | [7bf21b409d](https://linux-hardware.org/?probe=7bf21b409d) | Sep 02, 2019 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [f6c7aa7735](https://linux-hardware.org/?probe=f6c7aa7735) | Sep 02, 2019 |
| Gigabyte      | X299 UD4 Pro-CF             | Desktop     | [b1fb625f3d](https://linux-hardware.org/?probe=b1fb625f3d) | Aug 26, 2019 |
| ASUSTek       | X302UJ                      | Notebook    | [d467007887](https://linux-hardware.org/?probe=d467007887) | Aug 24, 2019 |
| Dell          | 0CKCXH A04                  | Desktop     | [2679a50fe1](https://linux-hardware.org/?probe=2679a50fe1) | Aug 24, 2019 |
| Gigabyte      | H55M-S2H                    | Desktop     | [2479a0b0c9](https://linux-hardware.org/?probe=2479a0b0c9) | Aug 24, 2019 |
| Acer          | Aspire 5730                 | Notebook    | [6e8c846d9b](https://linux-hardware.org/?probe=6e8c846d9b) | Aug 24, 2019 |
| Gigabyte      | J1800N-D2H                  | Desktop     | [616bb81d97](https://linux-hardware.org/?probe=616bb81d97) | Aug 17, 2019 |
| Dell          | Latitude E5470              | Notebook    | [d01c149d9c](https://linux-hardware.org/?probe=d01c149d9c) | Aug 17, 2019 |
| Dell          | Latitude E5470              | Notebook    | [b0b32067b9](https://linux-hardware.org/?probe=b0b32067b9) | Aug 17, 2019 |
| Dell          | Inspiron 13-5378            | Notebook    | [afa245a5c3](https://linux-hardware.org/?probe=afa245a5c3) | Aug 13, 2019 |
| HP            | 255 G5 Notebook PC          | Notebook    | [2043a9b3c9](https://linux-hardware.org/?probe=2043a9b3c9) | Jul 18, 2019 |
| Foxconn       | 2A8C                        | Desktop     | [54cbeed66e](https://linux-hardware.org/?probe=54cbeed66e) | Jul 10, 2019 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [10a2ff392a](https://linux-hardware.org/?probe=10a2ff392a) | Jul 09, 2019 |
| ASUSTek       | K54C                        | Notebook    | [4a89c5d895](https://linux-hardware.org/?probe=4a89c5d895) | Jul 06, 2019 |
| Gigabyte      | H57M-USB3                   | Desktop     | [10ba468b45](https://linux-hardware.org/?probe=10ba468b45) | Jul 01, 2019 |
| Dell          | 03NVJ6 A02                  | Desktop     | [0b6b3550b5](https://linux-hardware.org/?probe=0b6b3550b5) | Jul 01, 2019 |
| Dell          | 03NVJ6 A02                  | Desktop     | [a920b40c9f](https://linux-hardware.org/?probe=a920b40c9f) | Jul 01, 2019 |
| Dell          | 0GDG8Y A00                  | Desktop     | [4f0fb75146](https://linux-hardware.org/?probe=4f0fb75146) | Jun 20, 2019 |
| ASRock        | H110M-ITX/ac                | Desktop     | [6f2ecbf51c](https://linux-hardware.org/?probe=6f2ecbf51c) | Jun 04, 2019 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [93c1102eae](https://linux-hardware.org/?probe=93c1102eae) | May 30, 2019 |
| Gigabyte      | H97-HD3                     | Desktop     | [64e47e9922](https://linux-hardware.org/?probe=64e47e9922) | May 28, 2019 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [0e16d3f886](https://linux-hardware.org/?probe=0e16d3f886) | May 23, 2019 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [112dc8e71a](https://linux-hardware.org/?probe=112dc8e71a) | May 23, 2019 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [89e100d874](https://linux-hardware.org/?probe=89e100d874) | May 17, 2019 |
| HP            | Pavilion dv6500             | Notebook    | [b185023357](https://linux-hardware.org/?probe=b185023357) | May 13, 2019 |
| ASUSTek       | K54C                        | Notebook    | [653d157e1a](https://linux-hardware.org/?probe=653d157e1a) | May 04, 2019 |
| Lenovo        | 36F4 SDK0R32862 WIN 3258... | All in one  | [6543f3c4af](https://linux-hardware.org/?probe=6543f3c4af) | May 03, 2019 |
| ASUSTek       | H110M-K                     | Desktop     | [c736db6599](https://linux-hardware.org/?probe=c736db6599) | May 01, 2019 |
| ASUSTek       | H110M-K                     | Desktop     | [109947ebc6](https://linux-hardware.org/?probe=109947ebc6) | May 01, 2019 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [05fcc6199e](https://linux-hardware.org/?probe=05fcc6199e) | Apr 21, 2019 |
| Lenovo        | ThinkPad X380 Yoga 20LJ0... | Convertible | [0818236221](https://linux-hardware.org/?probe=0818236221) | Apr 16, 2019 |
| Lenovo        | ThinkPad T440p 20AN00E3I... | Notebook    | [a803a8593b](https://linux-hardware.org/?probe=a803a8593b) | Apr 11, 2019 |
| Lenovo        | ThinkPad T440p 20AN00E3I... | Notebook    | [6be3c466e0](https://linux-hardware.org/?probe=6be3c466e0) | Apr 10, 2019 |
| HP            | 82A5                        | Mini pc     | [2350ea995c](https://linux-hardware.org/?probe=2350ea995c) | Apr 07, 2019 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [f8a69693bc](https://linux-hardware.org/?probe=f8a69693bc) | Mar 30, 2019 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [f49f4bf7e3](https://linux-hardware.org/?probe=f49f4bf7e3) | Mar 30, 2019 |
| Biostar       | H61MLV2                     | Desktop     | [19146b787b](https://linux-hardware.org/?probe=19146b787b) | Mar 28, 2019 |
| Fujitsu Si... | AMILO Li 2727               | Notebook    | [606743f06e](https://linux-hardware.org/?probe=606743f06e) | Mar 22, 2019 |
| Gigabyte      | H97M-HD3                    | Desktop     | [a6818d6761](https://linux-hardware.org/?probe=a6818d6761) | Mar 20, 2019 |
| System76      | Gazelle                     | Notebook    | [03387dc427](https://linux-hardware.org/?probe=03387dc427) | Mar 12, 2019 |
| Gigabyte      | F2A88XM-HD3                 | Desktop     | [b1e21a522f](https://linux-hardware.org/?probe=b1e21a522f) | Feb 26, 2019 |
| HP            | G70                         | Notebook    | [d4f5ef99c5](https://linux-hardware.org/?probe=d4f5ef99c5) | Feb 14, 2019 |
| ASUSTek       | S551LN                      | Notebook    | [572227fb77](https://linux-hardware.org/?probe=572227fb77) | Jan 19, 2019 |
| ASUSTek       | S551LN                      | Notebook    | [f624b3c2eb](https://linux-hardware.org/?probe=f624b3c2eb) | Jan 18, 2019 |
| ASUSTek       | S551LN                      | Notebook    | [084947886f](https://linux-hardware.org/?probe=084947886f) | Jan 03, 2019 |
| Timi          | TM1701                      | Notebook    | [19f0b77769](https://linux-hardware.org/?probe=19f0b77769) | Dec 21, 2018 |
| Timi          | TM1701                      | Notebook    | [e0c4ee1fcb](https://linux-hardware.org/?probe=e0c4ee1fcb) | Dec 21, 2018 |
| ASUSTek       | S551LN                      | Notebook    | [4fef5b511a](https://linux-hardware.org/?probe=4fef5b511a) | Dec 15, 2018 |
| ASUSTek       | S551LN                      | Notebook    | [735db3cd91](https://linux-hardware.org/?probe=735db3cd91) | Dec 14, 2018 |
| ASUSTek       | H81M-K                      | Desktop     | [569fd85150](https://linux-hardware.org/?probe=569fd85150) | Dec 05, 2018 |
| Intel         | NUC8BEB J72688-303          | Mini pc     | [01310a1064](https://linux-hardware.org/?probe=01310a1064) | Dec 01, 2018 |
| Gigabyte      | H370 HD3-CF                 | Desktop     | [ac7a7dc15b](https://linux-hardware.org/?probe=ac7a7dc15b) | Nov 13, 2018 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [120d843ed3](https://linux-hardware.org/?probe=120d843ed3) | Nov 07, 2018 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [d21daddd24](https://linux-hardware.org/?probe=d21daddd24) | Nov 07, 2018 |
| ASUSTek       | Z87-K                       | Desktop     | [1d8a707c72](https://linux-hardware.org/?probe=1d8a707c72) | Sep 11, 2018 |
| ASUSTek       | 1001PXD                     | Notebook    | [00e7c9c5fc](https://linux-hardware.org/?probe=00e7c9c5fc) | Aug 18, 2018 |
| ASUSTek       | 1001PXD                     | Notebook    | [80227a12a8](https://linux-hardware.org/?probe=80227a12a8) | Aug 18, 2018 |
| Gigabyte      | Z170MX-Gaming 5             | Desktop     | [935991dc2b](https://linux-hardware.org/?probe=935991dc2b) | May 04, 2018 |
| Lenovo        | ThinkPad T60 2613CTO        | Notebook    | [35edbff8b9](https://linux-hardware.org/?probe=35edbff8b9) | Feb 25, 2018 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [d147cce967](https://linux-hardware.org/?probe=d147cce967) | Dec 06, 2017 |
| Samsung       | N248P                       | Notebook    | [2b7782d6cb](https://linux-hardware.org/?probe=2b7782d6cb) | Aug 10, 2017 |
| HP            | Unknown                     | Notebook    | [551457fd6d](https://linux-hardware.org/?probe=551457fd6d) | Jul 10, 2017 |
| ASUSTek       | M5A87                       | Desktop     | [242554d0b3](https://linux-hardware.org/?probe=242554d0b3) | Apr 27, 2017 |
| ASRock        | G41C-GS                     | Desktop     | [ff9333f313](https://linux-hardware.org/?probe=ff9333f313) | Apr 13, 2017 |
| ASUSTek       | M5A87                       | Desktop     | [bbe4de9927](https://linux-hardware.org/?probe=bbe4de9927) | Apr 07, 2017 |
| Gigabyte      | Z170MX-Gaming 5             | Desktop     | [10108844b5](https://linux-hardware.org/?probe=10108844b5) | Mar 17, 2017 |
| ASUSTek       | M5A87                       | Desktop     | [653cce33bd](https://linux-hardware.org/?probe=653cce33bd) | Mar 17, 2017 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [c869336270](https://linux-hardware.org/?probe=c869336270) | Jan 17, 2017 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [c7554e6e05](https://linux-hardware.org/?probe=c7554e6e05) | Jan 14, 2017 |
| MSI           | G41TM-P33                   | Desktop     | [dd04fa411c](https://linux-hardware.org/?probe=dd04fa411c) | Dec 12, 2016 |
| Acer          | Aspire 7520                 | Notebook    | [9132eeefdd](https://linux-hardware.org/?probe=9132eeefdd) | Nov 21, 2016 |
| ASUSTek       | 1001PXD                     | Notebook    | [6de0cbb74c](https://linux-hardware.org/?probe=6de0cbb74c) | Oct 29, 2016 |
| ASUSTek       | 1001PXD                     | Notebook    | [439684c718](https://linux-hardware.org/?probe=439684c718) | Oct 29, 2016 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [0a729a3728](https://linux-hardware.org/?probe=0a729a3728) | Oct 07, 2016 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Israel/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 131       | 19.35%  |
| Ubuntu 18.04                 | 62        | 9.16%   |
| Ubuntu 22.04                 | 21        | 3.1%    |
| OpenMandriva 4.3             | 17        | 2.51%   |
| OpenMandriva 4.2             | 16        | 2.36%   |
| ROSA R11                     | 14        | 2.07%   |
| Manjaro                      | 12        | 1.77%   |
| Fedora 37                    | 12        | 1.77%   |
| Ubuntu 21.04                 | 11        | 1.62%   |
| Ubuntu 19.04                 | 11        | 1.62%   |
| Fedora 36                    | 11        | 1.62%   |
| Linux Mint 20.1              | 10        | 1.48%   |
| Fedora 35                    | 10        | 1.48%   |
| Linux Mint 20.3              | 9         | 1.33%   |
| Arch Rolling                 | 9         | 1.33%   |
| Ubuntu 20.10                 | 8         | 1.18%   |
| Ubuntu 19.10                 | 8         | 1.18%   |
| ROSA R11.1                   | 8         | 1.18%   |
| Pop!_OS 21.04                | 8         | 1.18%   |
| Arch                         | 8         | 1.18%   |
| Zorin 16                     | 7         | 1.03%   |
| ROSA R10                     | 7         | 1.03%   |
| Linux Mint 19.3              | 7         | 1.03%   |
| Kubuntu 20.04                | 7         | 1.03%   |
| Fedora 34                    | 7         | 1.03%   |
| Fedora 33                    | 7         | 1.03%   |
| Zorin 15                     | 6         | 0.89%   |
| Pop!_OS 21.10                | 6         | 0.89%   |
| Pop!_OS 20.04                | 6         | 0.89%   |
| openSUSE Tumbleweed-XXXXXXXX | 6         | 0.89%   |
| Linux Mint 21                | 6         | 0.89%   |
| Linux Mint 20                | 6         | 0.89%   |
| Debian 11                    | 6         | 0.89%   |
| ArcoLinux Rolling            | 6         | 0.89%   |
| Ubuntu 21.10                 | 5         | 0.74%   |
| ROSA R8                      | 5         | 0.74%   |
| Pop!_OS 22.04                | 5         | 0.74%   |
| OpenMandriva 23.03           | 5         | 0.74%   |
| Linux Mint 21.1              | 5         | 0.74%   |
| Linux Mint 20.2              | 5         | 0.74%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 256       | 40.96%  |
| Linux Mint    | 49        | 7.84%   |
| Fedora        | 47        | 7.52%   |
| OpenMandriva  | 41        | 6.56%   |
| ROSA          | 35        | 5.6%    |
| Pop!_OS       | 28        | 4.48%   |
| Manjaro       | 25        | 4%      |
| Arch          | 17        | 2.72%   |
| Zorin         | 14        | 2.24%   |
| Xubuntu       | 13        | 2.08%   |
| Kubuntu       | 13        | 2.08%   |
| Debian        | 13        | 2.08%   |
| Endless       | 8         | 1.28%   |
| openSUSE      | 6         | 0.96%   |
| CentOS        | 6         | 0.96%   |
| ArcoLinux     | 6         | 0.96%   |
| KDE neon      | 5         | 0.8%    |
| Ubuntu MATE   | 4         | 0.64%   |
| Elementary    | 4         | 0.64%   |
| Ubuntu Unity  | 3         | 0.48%   |
| Rocky Linux   | 3         | 0.48%   |
| Kali          | 3         | 0.48%   |
| Clear Linux   | 3         | 0.48%   |
| BlackPanther  | 3         | 0.48%   |
| SteamOS       | 2         | 0.32%   |
| Devuan        | 2         | 0.32%   |
| Xero          | 1         | 0.16%   |
| UbuntuDDE     | 1         | 0.16%   |
| Ubuntu Budgie | 1         | 0.16%   |
| Siduction     | 1         | 0.16%   |
| RHEL          | 1         | 0.16%   |
| Raspbian      | 1         | 0.16%   |
| PureOS        | 1         | 0.16%   |
| Nobara        | 1         | 0.16%   |
| Neptune OS    | 1         | 0.16%   |
| Lubuntu       | 1         | 0.16%   |
| Gentoo        | 1         | 0.16%   |
| Garuda Linux  | 1         | 0.16%   |
| EndeavourOS   | 1         | 0.16%   |
| BunsenLabs    | 1         | 0.16%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Computers | Percent |
|-------------------------------------|-----------|---------|
| 5.4.0-42-generic                    | 26        | 3.54%   |
| 5.16.7-desktop-1omv4003             | 17        | 2.31%   |
| 5.10.14-desktop-1omv4002            | 15        | 2.04%   |
| 5.4.0-48-generic                    | 13        | 1.77%   |
| 5.4.0-52-generic                    | 10        | 1.36%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 7         | 0.95%   |
| 5.4.0-72-generic                    | 6         | 0.82%   |
| 5.4.0-65-generic                    | 6         | 0.82%   |
| 5.4.0-26-generic                    | 6         | 0.82%   |
| 5.15.0-56-generic                   | 6         | 0.82%   |
| 5.11.0-37-generic                   | 6         | 0.82%   |
| 6.2.6-desktop-1omv2390              | 5         | 0.68%   |
| 5.4.0-58-generic                    | 5         | 0.68%   |
| 5.3.0-46-generic                    | 5         | 0.68%   |
| 5.15.0-47-generic                   | 5         | 0.68%   |
| 5.13.0-30-generic                   | 5         | 0.68%   |
| 5.11.0-40-generic                   | 5         | 0.68%   |
| 5.11.0-27-generic                   | 5         | 0.68%   |
| 5.0.0-23-generic                    | 5         | 0.68%   |
| 4.9.60-nrj-desktop-1rosa-x86_64     | 5         | 0.68%   |
| 6.1.1-desktop-1omv2290              | 4         | 0.54%   |
| 5.4.0-70-generic                    | 4         | 0.54%   |
| 5.4.0-40-generic                    | 4         | 0.54%   |
| 5.4.0-37-generic                    | 4         | 0.54%   |
| 5.3.0-42-generic                    | 4         | 0.54%   |
| 5.3.0-28-generic                    | 4         | 0.54%   |
| 5.15.0-57-generic                   | 4         | 0.54%   |
| 5.15.0-50-generic                   | 4         | 0.54%   |
| 5.15.0-41-generic                   | 4         | 0.54%   |
| 5.13.0-7620-generic                 | 4         | 0.54%   |
| 5.11.0-38-generic                   | 4         | 0.54%   |
| 5.11.0-34-generic                   | 4         | 0.54%   |
| 4.15.0-desktop-94.1rosa-x86_64      | 4         | 0.54%   |
| 4.15.0-desktop-122.124.1rosa-x86_64 | 4         | 0.54%   |
| 4.15.0-58-generic                   | 4         | 0.54%   |
| 4.15.0-50-generic                   | 4         | 0.54%   |
| 5.8.0-7642-generic                  | 3         | 0.41%   |
| 5.8.0-59-generic                    | 3         | 0.41%   |
| 5.8.0-55-generic                    | 3         | 0.41%   |
| 5.8.0-53-generic                    | 3         | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 133       | 19.16%  |
| 4.15.0  | 49        | 7.06%   |
| 5.8.0   | 43        | 6.2%    |
| 5.15.0  | 42        | 6.05%   |
| 5.11.0  | 38        | 5.48%   |
| 5.3.0   | 31        | 4.47%   |
| 5.13.0  | 31        | 4.47%   |
| 5.0.0   | 25        | 3.6%    |
| 5.16.7  | 17        | 2.45%   |
| 5.10.14 | 15        | 2.16%   |
| 4.18.0  | 13        | 1.87%   |
| 5.19.0  | 10        | 1.44%   |
| 5.10.0  | 9         | 1.3%    |
| 4.9.60  | 6         | 0.86%   |
| 6.2.6   | 5         | 0.72%   |
| 6.1.12  | 4         | 0.58%   |
| 6.1.1   | 4         | 0.58%   |
| 5.9.16  | 4         | 0.58%   |
| 4.19.0  | 4         | 0.58%   |
| 4.1.34  | 4         | 0.58%   |
| 6.1.14  | 3         | 0.43%   |
| 6.1.0   | 3         | 0.43%   |
| 6.0.8   | 3         | 0.43%   |
| 6.0.7   | 3         | 0.43%   |
| 6.0.0   | 3         | 0.43%   |
| 5.8.5   | 3         | 0.43%   |
| 5.14.10 | 3         | 0.43%   |
| 5.10.74 | 3         | 0.43%   |
| 4.9.20  | 3         | 0.43%   |
| 4.18.16 | 3         | 0.43%   |
| 6.2.9   | 2         | 0.29%   |
| 6.2.11  | 2         | 0.29%   |
| 6.2.0   | 2         | 0.29%   |
| 6.1.7   | 2         | 0.29%   |
| 6.1.18  | 2         | 0.29%   |
| 6.1.10  | 2         | 0.29%   |
| 6.0.2   | 2         | 0.29%   |
| 5.9.9   | 2         | 0.29%   |
| 5.8.16  | 2         | 0.29%   |
| 5.7.10  | 2         | 0.29%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 138       | 20.41%  |
| 5.15    | 59        | 8.73%   |
| 5.8     | 50        | 7.4%    |
| 4.15    | 49        | 7.25%   |
| 5.11    | 45        | 6.66%   |
| 5.10    | 39        | 5.77%   |
| 5.13    | 35        | 5.18%   |
| 5.3     | 33        | 4.88%   |
| 5.16    | 30        | 4.44%   |
| 5.0     | 26        | 3.85%   |
| 6.1     | 23        | 3.4%    |
| 5.19    | 17        | 2.51%   |
| 4.18    | 16        | 2.37%   |
| 6.0     | 14        | 2.07%   |
| 4.9     | 14        | 2.07%   |
| 6.2     | 13        | 1.92%   |
| 5.9     | 11        | 1.63%   |
| 5.14    | 10        | 1.48%   |
| 5.18    | 9         | 1.33%   |
| 5.17    | 8         | 1.18%   |
| 4.19    | 8         | 1.18%   |
| 5.12    | 6         | 0.89%   |
| 4.1     | 6         | 0.89%   |
| 5.7     | 5         | 0.74%   |
| 5.6     | 4         | 0.59%   |
| 5.5     | 2         | 0.3%    |
| 4.4     | 2         | 0.3%    |
| 3.10    | 2         | 0.3%    |
| 4.7     | 1         | 0.15%   |
| 2.6     | 1         | 0.15%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 591       | 97.2%   |
| i686    | 13        | 2.14%   |
| aarch64 | 4         | 0.66%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| GNOME          | 294       | 46.45%  |
| KDE5           | 108       | 17.06%  |
| Unknown        | 79        | 12.48%  |
| X-Cinnamon     | 43        | 6.79%   |
| XFCE           | 33        | 5.21%   |
| KDE4           | 28        | 4.42%   |
| KDE            | 12        | 1.9%    |
| MATE           | 8         | 1.26%   |
| Cinnamon       | 7         | 1.11%   |
| i3             | 5         | 0.79%   |
| Unity          | 4         | 0.63%   |
| Pantheon       | 4         | 0.63%   |
| LXQt           | 3         | 0.47%   |
| Trinity        | 1         | 0.16%   |
| LXDE           | 1         | 0.16%   |
| i3-with-shmlog | 1         | 0.16%   |
| Deepin         | 1         | 0.16%   |
| Budgie         | 1         | 0.16%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 494       | 79.04%  |
| Wayland | 75        | 12%     |
| Unknown | 46        | 7.36%   |
| Tty     | 10        | 1.6%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 305       | 48.34%  |
| GDM     | 96        | 15.21%  |
| SDDM    | 88        | 13.95%  |
| GDM3    | 55        | 8.72%   |
| LightDM | 41        | 6.5%    |
| KDM     | 28        | 4.44%   |
| TDM     | 17        | 2.69%   |
| XDM     | 1         | 0.16%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_IL      | 237       | 37.62%  |
| en_US      | 199       | 31.59%  |
| Unknown    | 91        | 14.44%  |
| ru_RU      | 40        | 6.35%   |
| he_IL      | 31        | 4.92%   |
| C          | 7         | 1.11%   |
| fr_FR      | 4         | 0.63%   |
| en_GB      | 4         | 0.63%   |
| en_AG      | 4         | 0.63%   |
| POSIX      | 2         | 0.32%   |
| ru_UA      | 1         | 0.16%   |
| pt_BR      | 1         | 0.16%   |
| it_IT      | 1         | 0.16%   |
| es_ES      | 1         | 0.16%   |
| en_US.UTF8 | 1         | 0.16%   |
| en_NZ      | 1         | 0.16%   |
| en_DK      | 1         | 0.16%   |
| en_CA      | 1         | 0.16%   |
| en_AU      | 1         | 0.16%   |
| C.UTF8     | 1         | 0.16%   |
| aa_DJ      | 1         | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 335       | 53.34%  |
| BIOS | 293       | 46.66%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 475       | 76.49%  |
| Btrfs   | 52        | 8.37%   |
| Overlay | 48        | 7.73%   |
| Unknown | 24        | 3.86%   |
| Xfs     | 14        | 2.25%   |
| Zfs     | 2         | 0.32%   |
| Tmpfs   | 2         | 0.32%   |
| Ext3    | 2         | 0.32%   |
| F2fs    | 1         | 0.16%   |
| Ext2    | 1         | 0.16%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 322       | 51.6%   |
| GPT     | 239       | 38.3%   |
| MBR     | 63        | 10.1%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 532       | 86.36%  |
| Yes       | 84        | 13.64%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 434       | 70%     |
| Yes       | 186       | 30%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 138       | 22.73%  |
| Lenovo                  | 112       | 18.45%  |
| Dell                    | 91        | 14.99%  |
| Gigabyte Technology     | 87        | 14.33%  |
| Hewlett-Packard         | 65        | 10.71%  |
| Intel                   | 14        | 2.31%   |
| MSI                     | 13        | 2.14%   |
| ASRock                  | 10        | 1.65%   |
| Apple                   | 10        | 1.65%   |
| Acer                    | 10        | 1.65%   |
| Samsung Electronics     | 6         | 0.99%   |
| Unknown                 | 5         | 0.82%   |
| Toshiba                 | 4         | 0.66%   |
| Fujitsu                 | 4         | 0.66%   |
| Supermicro              | 3         | 0.49%   |
| LG Electronics          | 3         | 0.49%   |
| Timi                    | 2         | 0.33%   |
| Raspberry Pi Foundation | 2         | 0.33%   |
| Pegatron                | 2         | 0.33%   |
| Nvidia                  | 2         | 0.33%   |
| Fujitsu Siemens         | 2         | 0.33%   |
| Foxconn                 | 2         | 0.33%   |
| Alienware               | 2         | 0.33%   |
| Valve                   | 1         | 0.16%   |
| TYAN Computer           | 1         | 0.16%   |
| System76                | 1         | 0.16%   |
| Shuttle                 | 1         | 0.16%   |
| Purism                  | 1         | 0.16%   |
| Notebook                | 1         | 0.16%   |
| Neousys Technology      | 1         | 0.16%   |
| Microsoft               | 1         | 0.16%   |
| ITI LIMITED             | 1         | 0.16%   |
| IP3 Tech                | 1         | 0.16%   |
| HUAWEI                  | 1         | 0.16%   |
| Heptagon Systems        | 1         | 0.16%   |
| Hardkernel              | 1         | 0.16%   |
| GPD                     | 1         | 0.16%   |
| Biostar                 | 1         | 0.16%   |
| AZW                     | 1         | 0.16%   |
| AYANEO                  | 1         | 0.16%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| ASUS All Series                       | 9         | 1.48%   |
| Unknown                               | 9         | 1.48%   |
| MSI MS-7592                           | 3         | 0.49%   |
| Lenovo IdeaPad 5 14ITL05 82FE         | 3         | 0.49%   |
| HP Pavilion Notebook                  | 3         | 0.49%   |
| HP Compaq Presario CQ61               | 3         | 0.49%   |
| Gigabyte H61M-S1                      | 3         | 0.49%   |
| Gigabyte G31M-ES2L                    | 3         | 0.49%   |
| ASUS UX331UA                          | 3         | 0.49%   |
| ASUS P8H61-M LX R2.0                  | 3         | 0.49%   |
| ASUS H110M-A/M.2                      | 3         | 0.49%   |
| RPi Raspberry Pi 4 Model B Rev 1.4    | 2         | 0.33%   |
| Nvidia Tegra                          | 2         | 0.33%   |
| Lenovo V14-IIL 82C4                   | 2         | 0.33%   |
| Lenovo IdeaPad Y700-15ISK 80NV        | 2         | 0.33%   |
| Lenovo IdeaPad L340-15IWL 81LG        | 2         | 0.33%   |
| Lenovo G50-80 80L0                    | 2         | 0.33%   |
| Intel NUC8i7BEH                       | 2         | 0.33%   |
| Intel NUC8i3BEH                       | 2         | 0.33%   |
| Intel DH77EB AAG39073-304             | 2         | 0.33%   |
| HP ZBook 15 G3                        | 2         | 0.33%   |
| HP Spectre x360 Convertible 13-aw0xxx | 2         | 0.33%   |
| HP ProBook 430 G6                     | 2         | 0.33%   |
| HP EliteBook 840 G5                   | 2         | 0.33%   |
| Gigabyte Z390 GAMING X                | 2         | 0.33%   |
| Gigabyte X570 AORUS ULTRA             | 2         | 0.33%   |
| Gigabyte P55-UD3L                     | 2         | 0.33%   |
| Gigabyte H97-HD3                      | 2         | 0.33%   |
| Gigabyte H61M-S2PV                    | 2         | 0.33%   |
| Gigabyte H55M-D2H                     | 2         | 0.33%   |
| Gigabyte B460HD3                      | 2         | 0.33%   |
| Gigabyte B450M DS3H                   | 2         | 0.33%   |
| Fujitsu LIFEBOOK AH530                | 2         | 0.33%   |
| Dell XPS 15 9570                      | 2         | 0.33%   |
| Dell OptiPlex 9020                    | 2         | 0.33%   |
| Dell OptiPlex 755                     | 2         | 0.33%   |
| Dell OptiPlex 7050                    | 2         | 0.33%   |
| Dell Latitude E6420                   | 2         | 0.33%   |
| Dell Latitude E6330                   | 2         | 0.33%   |
| Dell Latitude E4300                   | 2         | 0.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 47        | 7.74%   |
| ASUS PRIME         | 28        | 4.61%   |
| Dell Latitude      | 26        | 4.28%   |
| Lenovo IdeaPad     | 21        | 3.46%   |
| Dell Inspiron      | 20        | 3.29%   |
| ASUS ROG           | 19        | 3.13%   |
| Dell Vostro        | 14        | 2.31%   |
| Dell OptiPlex      | 12        | 1.98%   |
| ASUS VivoBook      | 12        | 1.98%   |
| HP Pavilion        | 10        | 1.65%   |
| Dell XPS           | 10        | 1.65%   |
| ASUS All           | 9         | 1.48%   |
| Unknown            | 9         | 1.48%   |
| Acer Aspire        | 8         | 1.32%   |
| Lenovo ThinkCentre | 7         | 1.15%   |
| HP ZBook           | 7         | 1.15%   |
| HP Compaq          | 7         | 1.15%   |
| ASUS TUF           | 7         | 1.15%   |
| Lenovo Legion      | 6         | 0.99%   |
| HP ProBook         | 6         | 0.99%   |
| HP EliteBook       | 6         | 0.99%   |
| ASUS ZenBook       | 5         | 0.82%   |
| Lenovo Yoga        | 4         | 0.66%   |
| HP Laptop          | 4         | 0.66%   |
| Gigabyte Z690      | 4         | 0.66%   |
| Fujitsu LIFEBOOK   | 4         | 0.66%   |
| ASUS H110M-A       | 4         | 0.66%   |
| Toshiba Satellite  | 3         | 0.49%   |
| MSI MS-7592        | 3         | 0.49%   |
| Lenovo V520-15IKL  | 3         | 0.49%   |
| Lenovo IdeaPadFlex | 3         | 0.49%   |
| Lenovo G50-80      | 3         | 0.49%   |
| HP Spectre         | 3         | 0.49%   |
| HP ProDesk         | 3         | 0.49%   |
| HP ENVY            | 3         | 0.49%   |
| Gigabyte Z390      | 3         | 0.49%   |
| Gigabyte X570      | 3         | 0.49%   |
| Gigabyte H61M-S1   | 3         | 0.49%   |
| Gigabyte G31M-ES2L | 3         | 0.49%   |
| Gigabyte B450M     | 3         | 0.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 72        | 11.86%  |
| 2019    | 71        | 11.7%   |
| 2020    | 64        | 10.54%  |
| 2012    | 47        | 7.74%   |
| 2021    | 44        | 7.25%   |
| 2017    | 44        | 7.25%   |
| 2015    | 39        | 6.43%   |
| 2016    | 38        | 6.26%   |
| 2014    | 31        | 5.11%   |
| 2011    | 30        | 4.94%   |
| 2010    | 29        | 4.78%   |
| 2013    | 27        | 4.45%   |
| 2009    | 21        | 3.46%   |
| 2008    | 17        | 2.8%    |
| 2022    | 12        | 1.98%   |
| 2007    | 12        | 1.98%   |
| Unknown | 4         | 0.66%   |
| 2006    | 3         | 0.49%   |
| 2023    | 2         | 0.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 302       | 49.75%  |
| Desktop        | 255       | 42.01%  |
| Mini pc        | 14        | 2.31%   |
| Convertible    | 13        | 2.14%   |
| Server         | 8         | 1.32%   |
| Tablet         | 6         | 0.99%   |
| All in one     | 5         | 0.82%   |
| System on chip | 4         | 0.66%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 561       | 91.67%  |
| Enabled  | 51        | 8.33%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 606       | 99.84%  |
| Yes  | 1         | 0.16%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 148       | 24.03%  |
| 4.01-8.0        | 118       | 19.16%  |
| 32.01-64.0      | 105       | 17.05%  |
| 8.01-16.0       | 98        | 15.91%  |
| 3.01-4.0        | 77        | 12.5%   |
| 1.01-2.0        | 27        | 4.38%   |
| 64.01-256.0     | 26        | 4.22%   |
| 24.01-32.0      | 7         | 1.14%   |
| 2.01-3.0        | 7         | 1.14%   |
| 0.51-1.0        | 2         | 0.32%   |
| More than 256.0 | 1         | 0.16%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 201       | 29.96%  |
| 2.01-3.0    | 151       | 22.5%   |
| 4.01-8.0    | 109       | 16.24%  |
| 3.01-4.0    | 91        | 13.56%  |
| 8.01-16.0   | 61        | 9.09%   |
| 0.51-1.0    | 40        | 5.96%   |
| 0.01-0.5    | 8         | 1.19%   |
| 16.01-24.0  | 6         | 0.89%   |
| 24.01-32.0  | 2         | 0.3%    |
| 64.01-256.0 | 1         | 0.15%   |
| Unknown     | 1         | 0.15%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 389       | 62.44%  |
| 2      | 134       | 21.51%  |
| 3      | 56        | 8.99%   |
| 4      | 20        | 3.21%   |
| 5      | 11        | 1.77%   |
| 6      | 4         | 0.64%   |
| 0      | 4         | 0.64%   |
| 8      | 2         | 0.32%   |
| 7      | 2         | 0.32%   |
| 10     | 1         | 0.16%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 418       | 68.19%  |
| Yes       | 195       | 31.81%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 529       | 86.86%  |
| No        | 80        | 13.14%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 439       | 71.85%  |
| No        | 172       | 28.15%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 349       | 56.75%  |
| No        | 266       | 43.25%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Israel  | 607       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Tel Aviv            | 263       | 39.67%  |
| Ramat Gan           | 53        | 7.99%   |
| Haifa               | 33        | 4.98%   |
| Petaẖ Tiqwa       | 27        | 4.07%   |
| Jerusalem           | 23        | 3.47%   |
| Rishon LeZiyyon     | 18        | 2.71%   |
| Herzliya            | 18        | 2.71%   |
| Netanya             | 15        | 2.26%   |
| Holon               | 13        | 1.96%   |
| Givatayim           | 11        | 1.66%   |
| Rehovot             | 10        | 1.51%   |
| Ramat HaSharon      | 10        | 1.51%   |
| Nahariya            | 8         | 1.21%   |
| Rishon LeTsiyyon    | 7         | 1.06%   |
| Qiryat Ata          | 7         | 1.06%   |
| Kfar Saba           | 7         | 1.06%   |
| Ashquelon           | 7         | 1.06%   |
| Beersheba           | 6         | 0.9%    |
| Raanana             | 5         | 0.75%   |
| Kiryat Ono          | 5         | 0.75%   |
| Hadera              | 5         | 0.75%   |
| Bat Yam             | 5         | 0.75%   |
| Ashdod              | 5         | 0.75%   |
| Yehud               | 4         | 0.6%    |
| Yaqum               | 4         | 0.6%    |
| Sderot              | 4         | 0.6%    |
| Ness Ziona          | 4         | 0.6%    |
| Hod HaSharon        | 4         | 0.6%    |
| Givat Shmuel        | 4         | 0.6%    |
| Bet Shemesh         | 4         | 0.6%    |
| Ramla               | 3         | 0.45%   |
| Petah Tikva         | 3         | 0.45%   |
| Pardes Hanna Karkur | 3         | 0.45%   |
| Karmi’el          | 3         | 0.45%   |
| Ganei Tikva         | 3         | 0.45%   |
| Be'er Ya'aqov       | 3         | 0.45%   |
| Afula               | 3         | 0.45%   |
| Yavne               | 2         | 0.3%    |
| Tiberias            | 2         | 0.3%    |
| Tel Mond            | 2         | 0.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 154       | 251    | 17.32%  |
| Samsung Electronics       | 131       | 191    | 14.74%  |
| Seagate                   | 97        | 148    | 10.91%  |
| SanDisk                   | 66        | 82     | 7.42%   |
| Kingston                  | 55        | 70     | 6.19%   |
| Toshiba                   | 52        | 61     | 5.85%   |
| Hitachi                   | 45        | 70     | 5.06%   |
| SK hynix                  | 35        | 47     | 3.94%   |
| Intel                     | 34        | 47     | 3.82%   |
| Crucial                   | 26        | 47     | 2.92%   |
| HGST                      | 22        | 25     | 2.47%   |
| Micron Technology         | 21        | 27     | 2.36%   |
| Transcend                 | 16        | 21     | 1.8%    |
| Unknown                   | 15        | 18     | 1.69%   |
| Corsair                   | 12        | 19     | 1.35%   |
| A-DATA Technology         | 10        | 13     | 1.12%   |
| KIOXIA                    | 8         | 8      | 0.9%    |
| StoreJet                  | 7         | 7      | 0.79%   |
| XPG                       | 6         | 12     | 0.67%   |
| Phison                    | 6         | 7      | 0.67%   |
| Apple                     | 6         | 6      | 0.67%   |
| Silicon Motion            | 5         | 5      | 0.56%   |
| China                     | 5         | 7      | 0.56%   |
| SPCC                      | 4         | 4      | 0.45%   |
| LITEON                    | 4         | 4      | 0.45%   |
| JMicron Technology        | 4         | 4      | 0.45%   |
| Fujitsu                   | 4         | 5      | 0.45%   |
| Micron/Crucial Technology | 3         | 3      | 0.34%   |
| Apacer                    | 3         | 3      | 0.34%   |
| Phison Electronics        | 2         | 3      | 0.22%   |
| OCZ                       | 2         | 2      | 0.22%   |
| Netac                     | 2         | 2      | 0.22%   |
| KIOXIA-EXCERIA            | 2         | 3      | 0.22%   |
| faspeed                   | 2         | 3      | 0.22%   |
| ADATA Technology          | 2         | 2      | 0.22%   |
| XrayDisk                  | 1         | 1      | 0.11%   |
| Verbatim                  | 1         | 1      | 0.11%   |
| USB3.0                    | 1         | 1      | 0.11%   |
| UMIS                      | 1         | 1      | 0.11%   |
| TPH01204000GB             | 1         | 1      | 0.11%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| SanDisk SSD PLUS 240GB                            | 14        | 1.41%   |
| Kingston SA400S37240G 240GB SSD                   | 12        | 1.21%   |
| Samsung NVMe SSD Drive 512GB                      | 10        | 1.01%   |
| Samsung SSD 860 EVO 500GB                         | 9         | 0.91%   |
| Hitachi HDS721050CLA362 500GB                     | 9         | 0.91%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 8         | 0.81%   |
| Seagate ST500LT012-1DG142 500GB                   | 7         | 0.71%   |
| Seagate ST500DM002-1BD142 500GB                   | 7         | 0.71%   |
| Kingston SV300S37A120G 120GB SSD                  | 7         | 0.71%   |
| Intel NVMe SSD Drive 512GB                        | 7         | 0.71%   |
| Toshiba DT01ACA100 1TB                            | 6         | 0.61%   |
| SK hynix NVMe SSD Drive 256GB                     | 6         | 0.61%   |
| Samsung SSD 850 EVO 250GB                         | 6         | 0.61%   |
| Samsung NVMe SSD Drive 500GB                      | 6         | 0.61%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 6         | 0.61%   |
| HGST HTS545050A7E680 500GB                        | 6         | 0.61%   |
| Crucial CT500MX500SSD1 500GB                      | 6         | 0.61%   |
| WDC WD20PURX-64P6ZY0 2TB                          | 5         | 0.51%   |
| Unknown MMC Card  64GB                            | 5         | 0.51%   |
| Toshiba MQ01ABF050 500GB                          | 5         | 0.51%   |
| SK hynix NVMe SSD Drive 512GB                     | 5         | 0.51%   |
| Seagate ST2000DM008-2FR102 2TB                    | 5         | 0.51%   |
| Seagate ST2000DM001-1ER164 2TB                    | 5         | 0.51%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 5         | 0.51%   |
| SanDisk Extreme SSD 500GB                         | 5         | 0.51%   |
| Samsung SSD 860 EVO 250GB                         | 5         | 0.51%   |
| Intel SSDPEKNW512G8 512GB                         | 5         | 0.51%   |
| HGST HTS721010A9E630 1TB                          | 5         | 0.51%   |
| WDC WD5000AAKX-08U6AA0 500GB                      | 4         | 0.4%    |
| WDC WD10EZEX-00BN5A0 1TB                          | 4         | 0.4%    |
| Toshiba NVMe SSD Drive 512GB                      | 4         | 0.4%    |
| Seagate ST1000DM003-1SB102 1TB                    | 4         | 0.4%    |
| Seagate ST1000DM003-1CH162 1TB                    | 4         | 0.4%    |
| SanDisk NVMe SSD Drive 512GB                      | 4         | 0.4%    |
| Samsung SSD 970 EVO Plus 500GB                    | 4         | 0.4%    |
| Samsung SSD 850 EVO 500GB                         | 4         | 0.4%    |
| Samsung SM963 2.5" NVMe PCIe SSD 250GB            | 4         | 0.4%    |
| Samsung NVMe SSD Drive 256GB                      | 4         | 0.4%    |
| Samsung NVMe SSD Drive 1TB                        | 4         | 0.4%    |
| Kingston SUV400S37120G 120GB SSD                  | 4         | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 126       | 214    | 36.1%   |
| Seagate             | 97        | 147    | 27.79%  |
| Hitachi             | 45        | 70     | 12.89%  |
| Toshiba             | 38        | 45     | 10.89%  |
| HGST                | 22        | 25     | 6.3%    |
| Samsung Electronics | 7         | 13     | 2.01%   |
| Fujitsu             | 4         | 5      | 1.15%   |
| Apple               | 3         | 3      | 0.86%   |
| JMicron Technology  | 2         | 2      | 0.57%   |
| USB3.0              | 1         | 1      | 0.29%   |
| Unknown             | 1         | 1      | 0.29%   |
| TPH01204000GB       | 1         | 1      | 0.29%   |
| StoreJet            | 1         | 1      | 0.29%   |
| IBM/Hitachi         | 1         | 1      | 0.29%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 54        | 70     | 19.15%  |
| SanDisk             | 44        | 56     | 15.6%   |
| Kingston            | 44        | 55     | 15.6%   |
| Crucial             | 20        | 39     | 7.09%   |
| Transcend           | 15        | 20     | 5.32%   |
| Micron Technology   | 12        | 14     | 4.26%   |
| Intel               | 12        | 14     | 4.26%   |
| WDC                 | 10        | 10     | 3.55%   |
| Corsair             | 10        | 16     | 3.55%   |
| SK hynix            | 9         | 19     | 3.19%   |
| A-DATA Technology   | 9         | 11     | 3.19%   |
| China               | 5         | 7      | 1.77%   |
| Toshiba             | 4         | 4      | 1.42%   |
| LITEON              | 4         | 4      | 1.42%   |
| StoreJet            | 3         | 3      | 1.06%   |
| Apple               | 3         | 3      | 1.06%   |
| Apacer              | 3         | 3      | 1.06%   |
| SPCC                | 2         | 2      | 0.71%   |
| OCZ                 | 2         | 2      | 0.71%   |
| Netac               | 2         | 2      | 0.71%   |
| KIOXIA-EXCERIA      | 2         | 2      | 0.71%   |
| Verbatim            | 1         | 1      | 0.35%   |
| Seagate             | 1         | 1      | 0.35%   |
| PNY                 | 1         | 1      | 0.35%   |
| Plextor             | 1         | 1      | 0.35%   |
| Patriot             | 1         | 1      | 0.35%   |
| OCZ-VERTEX3         | 1         | 1      | 0.35%   |
| NGFF                | 1         | 1      | 0.35%   |
| LS600               | 1         | 1      | 0.35%   |
| LITEONIT            | 1         | 1      | 0.35%   |
| KingSpec            | 1         | 1      | 0.35%   |
| KingDian            | 1         | 2      | 0.35%   |
| faspeed             | 1         | 1      | 0.35%   |
| External            | 1         | 1      | 0.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 288       | 529    | 36.32%  |
| SSD     | 248       | 370    | 31.27%  |
| NVMe    | 235       | 321    | 29.63%  |
| MMC     | 13        | 19     | 1.64%   |
| Unknown | 9         | 11     | 1.13%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 418       | 867    | 59.63%  |
| NVMe | 235       | 321    | 33.52%  |
| SAS  | 35        | 43     | 4.99%   |
| MMC  | 13        | 19     | 1.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 326       | 544    | 58.84%  |
| 0.51-1.0   | 143       | 206    | 25.81%  |
| 1.01-2.0   | 53        | 84     | 9.57%   |
| 3.01-4.0   | 13        | 34     | 2.35%   |
| 2.01-3.0   | 12        | 18     | 2.17%   |
| 4.01-10.0  | 6         | 8      | 1.08%   |
| 10.01-20.0 | 1         | 5      | 0.18%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 165       | 25.98%  |
| 251-500        | 153       | 24.09%  |
| 501-1000       | 95        | 14.96%  |
| 1001-2000      | 46        | 7.24%   |
| 1-20           | 45        | 7.09%   |
| 51-100         | 34        | 5.35%   |
| 2001-3000      | 31        | 4.88%   |
| More than 3000 | 29        | 4.57%   |
| 21-50          | 21        | 3.31%   |
| Unknown        | 16        | 2.52%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 253       | 38.33%  |
| 21-50          | 117       | 17.73%  |
| 101-250        | 88        | 13.33%  |
| 51-100         | 65        | 9.85%   |
| 251-500        | 46        | 6.97%   |
| 1001-2000      | 27        | 4.09%   |
| 501-1000       | 25        | 3.79%   |
| Unknown        | 16        | 2.42%   |
| 2001-3000      | 14        | 2.12%   |
| More than 3000 | 9         | 1.36%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| HGST HTS545050A7E680 500GB            | 5         | 7      | 6.94%   |
| WDC WD10EARS-00Y5B1 1TB               | 2         | 4      | 2.78%   |
| WDC WD10EADS-00L5B1 1TB               | 2         | 2      | 2.78%   |
| Hitachi HDS721050DLE630 500GB         | 2         | 2      | 2.78%   |
| Hitachi HDS721050CLA362 500GB         | 2         | 3      | 2.78%   |
| HGST HTS545050A7E380 500GB            | 2         | 2      | 2.78%   |
| WDC WDS240G1G0B-00RC30 240GB SSD      | 1         | 1      | 1.39%   |
| WDC WD6400BPVT-75HXZT1 640GB          | 1         | 1      | 1.39%   |
| WDC WD5001AALS-00LWTA0 500GB          | 1         | 1      | 1.39%   |
| WDC WD5000AAKX-60U6AA0 500GB          | 1         | 1      | 1.39%   |
| WDC WD5000AAKX-221CA1 500GB           | 1         | 1      | 1.39%   |
| WDC WD5000AADS-00S9B0 500GB           | 1         | 1      | 1.39%   |
| WDC WD3200AAKS-00L9A0 320GB           | 1         | 1      | 1.39%   |
| WDC WD30PURX-64P6ZY0 3TB              | 1         | 1      | 1.39%   |
| WDC WD2500BEVT-24A23T0 250GB          | 1         | 1      | 1.39%   |
| WDC WD2500AAJS-00VTA0 250GB           | 1         | 1      | 1.39%   |
| WDC WD20EARS-00MVWB0 2TB              | 1         | 2      | 1.39%   |
| WDC WD1600BJKT-75F4T0 160GB           | 1         | 1      | 1.39%   |
| WDC WD1600BEVT-22ZCT0 160GB           | 1         | 1      | 1.39%   |
| WDC WD10EZEX-00ZF5A0 1TB              | 1         | 1      | 1.39%   |
| WDC WD10EZEX-00RKKA0 1TB              | 1         | 1      | 1.39%   |
| WDC WD10EZEX-00BN5A0 1TB              | 1         | 1      | 1.39%   |
| WDC WD1001FALS-00J7B1 1TB             | 1         | 1      | 1.39%   |
| Toshiba MQ04ABF100 1TB                | 1         | 1      | 1.39%   |
| Toshiba MK6475GSX 640GB               | 1         | 1      | 1.39%   |
| Toshiba MK5075GSX 500GB               | 1         | 1      | 1.39%   |
| Toshiba MK3252GSX 320GB               | 1         | 1      | 1.39%   |
| Toshiba MK1646GSX 160GB               | 1         | 1      | 1.39%   |
| SK hynix HFS256G3BTND-N210A 256GB SSD | 1         | 5      | 1.39%   |
| SK hynix HFS256G39TND-N210A 256GB SSD | 1         | 1      | 1.39%   |
| Seagate ST9500420AS 500GB             | 1         | 1      | 1.39%   |
| Seagate ST9120817AS 120GB             | 1         | 1      | 1.39%   |
| Seagate ST500LT012-9WS142 500GB       | 1         | 1      | 1.39%   |
| Seagate ST500LM021-1KJ152 500GB       | 1         | 1      | 1.39%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1         | 1      | 1.39%   |
| Seagate ST3750528AS 752GB             | 1         | 1      | 1.39%   |
| Seagate ST3500418AS 500GB             | 1         | 1      | 1.39%   |
| Seagate ST3250318AS 250GB             | 1         | 1      | 1.39%   |
| Seagate ST31000528AS 1TB              | 1         | 1      | 1.39%   |
| Seagate ST3000DM001-9YN166 3TB        | 1         | 1      | 1.39%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 20        | 24     | 28.57%  |
| Seagate             | 14        | 18     | 20%     |
| Hitachi             | 12        | 15     | 17.14%  |
| HGST                | 9         | 11     | 12.86%  |
| Toshiba             | 5         | 5      | 7.14%   |
| SK hynix            | 2         | 6      | 2.86%   |
| SanDisk             | 2         | 3      | 2.86%   |
| Corsair             | 2         | 3      | 2.86%   |
| Samsung Electronics | 1         | 2      | 1.43%   |
| Intel               | 1         | 1      | 1.43%   |
| Gigabyte Technology | 1         | 1      | 1.43%   |
| Fujitsu             | 1         | 1      | 1.43%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 19        | 23     | 31.15%  |
| Seagate             | 14        | 18     | 22.95%  |
| Hitachi             | 12        | 15     | 19.67%  |
| HGST                | 9         | 11     | 14.75%  |
| Toshiba             | 5         | 5      | 8.2%    |
| Samsung Electronics | 1         | 2      | 1.64%   |
| Fujitsu             | 1         | 1      | 1.64%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 50        | 75     | 84.75%  |
| SSD  | 8         | 14     | 13.56%  |
| NVMe | 1         | 1      | 1.69%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Toshiba MK3256GSY 320GB         | 1         | 1      | 33.33%  |
| Samsung Electronics HD103SJ 1TB | 1         | 1      | 33.33%  |
| Hitachi HTS547550A9E384 500GB   | 1         | 2      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 1         | 1      | 33.33%  |
| Samsung Electronics | 1         | 1      | 33.33%  |
| Hitachi             | 1         | 2      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 346       | 743    | 52.99%  |
| Works    | 248       | 413    | 37.98%  |
| Malfunc  | 57        | 90     | 8.73%   |
| Failed   | 2         | 4      | 0.31%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 467       | 59.41%  |
| Samsung Electronics          | 81        | 10.31%  |
| AMD                          | 54        | 6.87%   |
| SanDisk                      | 40        | 5.09%   |
| SK hynix                     | 26        | 3.31%   |
| Kingston Technology Company  | 13        | 1.65%   |
| Toshiba America Info Systems | 11        | 1.4%    |
| Phison Electronics           | 9         | 1.15%   |
| Micron/Crucial Technology    | 9         | 1.15%   |
| Micron Technology            | 9         | 1.15%   |
| Marvell Technology Group     | 9         | 1.15%   |
| JMicron Technology           | 9         | 1.15%   |
| ADATA Technology             | 9         | 1.15%   |
| KIOXIA                       | 8         | 1.02%   |
| Nvidia                       | 7         | 0.89%   |
| ASMedia Technology           | 7         | 0.89%   |
| Silicon Motion               | 6         | 0.76%   |
| LSI Logic / Symbios Logic    | 3         | 0.38%   |
| VIA Technologies             | 2         | 0.25%   |
| Union Memory (Shenzhen)      | 2         | 0.25%   |
| Realtek Semiconductor        | 2         | 0.25%   |
| Transcend                    | 1         | 0.13%   |
| Shenzhen Longsys Electronics | 1         | 0.13%   |
| O2 Micro                     | 1         | 0.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 47        | 5.3%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 45        | 5.08%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 42        | 4.74%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 24        | 2.71%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 24        | 2.71%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 23        | 2.6%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 23        | 2.6%    |
| Intel Volume Management Device NVMe RAID Controller                                     | 18        | 2.03%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 17        | 1.92%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 16        | 1.81%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 15        | 1.69%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 15        | 1.69%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 15        | 1.69%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 14        | 1.58%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 14        | 1.58%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 14        | 1.58%   |
| AMD 400 Series Chipset SATA Controller                                                  | 14        | 1.58%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 13        | 1.47%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 13        | 1.47%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 13        | 1.47%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 12        | 1.35%   |
| Intel SATA Controller [RAID mode]                                                       | 12        | 1.35%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 12        | 1.35%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 12        | 1.35%   |
| Samsung NVMe SSD Controller 980                                                         | 11        | 1.24%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 10        | 1.13%   |
| Intel SSD 660P Series                                                                   | 10        | 1.13%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 10        | 1.13%   |
| Micron NVMe Storage Controller                                                          | 9         | 1.02%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                           | 9         | 1.02%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 9         | 1.02%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 9         | 1.02%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 9         | 1.02%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 9         | 1.02%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 9         | 1.02%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 8         | 0.9%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 8         | 0.9%    |
| SK hynix Non-Volatile memory controller                                                 | 7         | 0.79%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 7         | 0.79%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 7         | 0.79%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 426       | 53.99%  |
| NVMe | 236       | 29.91%  |
| IDE  | 67        | 8.49%   |
| RAID | 58        | 7.35%   |
| SAS  | 2         | 0.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 534       | 87.97%  |
| AMD          | 68        | 11.2%   |
| ARM          | 3         | 0.49%   |
| CentaurHauls | 1         | 0.16%   |
| Unknown      | 1         | 0.16%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz           | 19        | 3.11%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 13        | 2.13%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 10        | 1.64%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 9         | 1.48%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 8         | 1.31%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 8         | 1.31%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 8         | 1.31%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 8         | 1.31%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 8         | 1.31%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 8         | 1.31%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 7         | 1.15%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 7         | 1.15%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 6         | 0.98%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 6         | 0.98%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 5         | 0.82%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 5         | 0.82%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 5         | 0.82%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 5         | 0.82%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 5         | 0.82%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 4         | 0.66%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 4         | 0.66%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 4         | 0.66%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 4         | 0.66%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 4         | 0.66%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 4         | 0.66%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 4         | 0.66%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 4         | 0.66%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 4         | 0.66%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 4         | 0.66%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 4         | 0.66%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 4         | 0.66%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 4         | 0.66%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 4         | 0.66%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 4         | 0.66%   |
| Intel Core i3-7020U CPU @ 2.30GHz           | 4         | 0.66%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 4         | 0.66%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 4         | 0.66%   |
| Intel Core i9-10885H CPU @ 2.40GHz          | 3         | 0.49%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 3         | 0.49%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 3         | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 183       | 30.1%   |
| Intel Core i5           | 135       | 22.2%   |
| Other                   | 60        | 9.87%   |
| Intel Core i3           | 51        | 8.39%   |
| AMD Ryzen 5             | 19        | 3.13%   |
| Intel Core 2 Duo        | 18        | 2.96%   |
| Intel Pentium Dual-Core | 17        | 2.8%    |
| Intel Xeon              | 16        | 2.63%   |
| AMD Ryzen 7             | 14        | 2.3%    |
| Intel Pentium           | 13        | 2.14%   |
| Intel Atom              | 10        | 1.64%   |
| AMD Ryzen 9             | 10        | 1.64%   |
| Intel Celeron           | 9         | 1.48%   |
| Intel Pentium Dual      | 7         | 1.15%   |
| Intel Core i9           | 7         | 1.15%   |
| Intel Genuine           | 4         | 0.66%   |
| AMD A8                  | 4         | 0.66%   |
| AMD FX                  | 3         | 0.49%   |
| AMD A6                  | 3         | 0.49%   |
| Intel Pentium Gold      | 2         | 0.33%   |
| AMD Ryzen 7 PRO         | 2         | 0.33%   |
| AMD Ryzen 3             | 2         | 0.33%   |
| AMD A10                 | 2         | 0.33%   |
| Intel Xeon Gold         | 1         | 0.16%   |
| Intel Pentium Silver    | 1         | 0.16%   |
| Intel Pentium 4         | 1         | 0.16%   |
| Intel Core M            | 1         | 0.16%   |
| Intel Core 2 Quad       | 1         | 0.16%   |
| Intel Core 2            | 1         | 0.16%   |
| Intel Celeron Dual-Core | 1         | 0.16%   |
| CentaurHauls VIA C7     | 1         | 0.16%   |
| ARM BCM                 | 1         | 0.16%   |
| AMD Turion 64 X2 Mobile | 1         | 0.16%   |
| AMD Ryzen Threadripper  | 1         | 0.16%   |
| AMD Ryzen 3 PRO         | 1         | 0.16%   |
| AMD Phenom II X4        | 1         | 0.16%   |
| AMD Phenom              | 1         | 0.16%   |
| AMD EPYC                | 1         | 0.16%   |
| AMD Athlon II X3        | 1         | 0.16%   |
| AMD Athlon 64 X2        | 1         | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 258       | 42.43%  |
| 2       | 192       | 31.58%  |
| 6       | 62        | 10.2%   |
| 8       | 51        | 8.39%   |
| 12      | 15        | 2.47%   |
| 16      | 9         | 1.48%   |
| 1       | 9         | 1.48%   |
| 10      | 4         | 0.66%   |
| 14      | 3         | 0.49%   |
| 3       | 2         | 0.33%   |
| 32      | 1         | 0.16%   |
| 20      | 1         | 0.16%   |
| Unknown | 1         | 0.16%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 598       | 98.52%  |
| 2       | 7         | 1.15%   |
| 4       | 1         | 0.16%   |
| Unknown | 1         | 0.16%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 452       | 74.22%  |
| 1       | 156       | 25.62%  |
| Unknown | 1         | 0.16%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 593       | 97.69%  |
| Unknown        | 12        | 1.98%   |
| 32-bit         | 2         | 0.33%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 150       | 23.47%  |
| 0x806ea    | 30        | 4.69%   |
| 0x306c3    | 30        | 4.69%   |
| 0x306a9    | 27        | 4.23%   |
| 0x206a7    | 27        | 4.23%   |
| 0x1067a    | 26        | 4.07%   |
| 0x506e3    | 23        | 3.6%    |
| 0x806ec    | 22        | 3.44%   |
| 0x806c1    | 22        | 3.44%   |
| 0x906e9    | 21        | 3.29%   |
| 0x906ea    | 19        | 2.97%   |
| 0x406e3    | 16        | 2.5%    |
| 0x806e9    | 12        | 1.88%   |
| 0x706e5    | 12        | 1.88%   |
| 0x306d4    | 12        | 1.88%   |
| 0x906ed    | 10        | 1.56%   |
| 0xa0652    | 9         | 1.41%   |
| 0x90672    | 9         | 1.41%   |
| 0x6fd      | 9         | 1.41%   |
| 0x40651    | 8         | 1.25%   |
| 0x20655    | 8         | 1.25%   |
| 0x08108109 | 7         | 1.1%    |
| 0xa0671    | 6         | 0.94%   |
| 0x806eb    | 6         | 0.94%   |
| 0x106e5    | 6         | 0.94%   |
| 0xa0655    | 5         | 0.78%   |
| 0xa0653    | 5         | 0.78%   |
| 0x306e4    | 5         | 0.78%   |
| 0x08701021 | 5         | 0.78%   |
| 0x906a3    | 4         | 0.63%   |
| 0x706a1    | 4         | 0.63%   |
| 0x10676    | 4         | 0.63%   |
| 0x0a50000c | 4         | 0.63%   |
| 0x806d1    | 3         | 0.47%   |
| 0x406c4    | 3         | 0.47%   |
| 0x106ca    | 3         | 0.47%   |
| 0x106a5    | 3         | 0.47%   |
| 0x0a201009 | 3         | 0.47%   |
| 0x08701013 | 3         | 0.47%   |
| 0x0800820d | 3         | 0.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 155       | 25.45%  |
| Haswell          | 51        | 8.37%   |
| Skylake          | 47        | 7.72%   |
| IvyBridge        | 39        | 6.4%    |
| Penryn           | 35        | 5.75%   |
| SandyBridge      | 32        | 5.25%   |
| TigerLake        | 28        | 4.6%    |
| CometLake        | 26        | 4.27%   |
| IceLake          | 24        | 3.94%   |
| Unknown          | 23        | 3.78%   |
| Broadwell        | 17        | 2.79%   |
| Westmere         | 16        | 2.63%   |
| Zen 2            | 15        | 2.46%   |
| Core             | 14        | 2.3%    |
| Zen+             | 13        | 2.13%   |
| Alderlake Hybrid | 12        | 1.97%   |
| Nehalem          | 11        | 1.81%   |
| Zen 3            | 10        | 1.64%   |
| Silvermont       | 7         | 1.15%   |
| Zen              | 6         | 0.99%   |
| Piledriver       | 6         | 0.99%   |
| Goldmont plus    | 4         | 0.66%   |
| Bonnell          | 4         | 0.66%   |
| Steamroller      | 3         | 0.49%   |
| K10              | 3         | 0.49%   |
| Puma             | 2         | 0.33%   |
| K8 Hammer        | 2         | 0.33%   |
| Tremont          | 1         | 0.16%   |
| NetBurst         | 1         | 0.16%   |
| Goldmont         | 1         | 0.16%   |
| Bulldozer        | 1         | 0.16%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 414       | 55.72%  |
| Nvidia                     | 238       | 32.03%  |
| AMD                        | 86        | 11.57%  |
| Matrox Electronics Systems | 2         | 0.27%   |
| ASPEED Technology          | 2         | 0.27%   |
| VIA Technologies           | 1         | 0.13%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 33        | 4.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 25        | 3.32%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 25        | 3.32%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 21        | 2.79%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 20        | 2.66%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 17        | 2.26%   |
| Intel HD Graphics 530                                                                    | 16        | 2.12%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 16        | 2.12%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 14        | 1.86%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 14        | 1.86%   |
| Intel HD Graphics 630                                                                    | 14        | 1.86%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 14        | 1.86%   |
| Intel HD Graphics 5500                                                                   | 13        | 1.73%   |
| Intel HD Graphics 620                                                                    | 12        | 1.59%   |
| Intel Core Processor Integrated Graphics Controller                                      | 12        | 1.59%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 12        | 1.59%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 1.46%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 10        | 1.33%   |
| Intel Iris Plus Graphics G7                                                              | 10        | 1.33%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 10        | 1.33%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 10        | 1.33%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 9         | 1.2%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 8         | 1.06%   |
| Nvidia GT218 [GeForce 210]                                                               | 7         | 0.93%   |
| Nvidia GP108M [GeForce MX150]                                                            | 7         | 0.93%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 7         | 0.93%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 6         | 0.8%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 0.8%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 6         | 0.8%    |
| Nvidia GP107GL [Quadro P400]                                                             | 5         | 0.66%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 5         | 0.66%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 5         | 0.66%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 5         | 0.66%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 5         | 0.66%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 5         | 0.66%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 5         | 0.66%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                                         | 5         | 0.66%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 5         | 0.66%   |
| Nvidia GP108M [GeForce MX230]                                                            | 4         | 0.53%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 4         | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 288       | 46.98%  |
| 1 x Nvidia      | 124       | 20.23%  |
| Intel + Nvidia  | 105       | 17.13%  |
| 1 x AMD         | 61        | 9.95%   |
| Intel + AMD     | 13        | 2.12%   |
| AMD + Nvidia    | 9         | 1.47%   |
| Other           | 4         | 0.65%   |
| 2 x AMD         | 3         | 0.49%   |
| 1 x ASPEED      | 2         | 0.33%   |
| 2 x Intel       | 1         | 0.16%   |
| 1 x VIA         | 1         | 0.16%   |
| Nvidia + Matrox | 1         | 0.16%   |
| 1 x Matrox      | 1         | 0.16%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 448       | 72.49%  |
| Proprietary | 140       | 22.65%  |
| Unknown     | 30        | 4.85%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 371       | 59.65%  |
| 1.01-2.0   | 77        | 12.38%  |
| 3.01-4.0   | 55        | 8.84%   |
| 0.01-0.5   | 32        | 5.14%   |
| 7.01-8.0   | 30        | 4.82%   |
| 0.51-1.0   | 30        | 4.82%   |
| 5.01-6.0   | 13        | 2.09%   |
| 2.01-3.0   | 6         | 0.96%   |
| 8.01-16.0  | 6         | 0.96%   |
| 24.01-32.0 | 1         | 0.16%   |
| 16.01-24.0 | 1         | 0.16%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 110       | 16.06%  |
| Dell                    | 79        | 11.53%  |
| AU Optronics            | 71        | 10.36%  |
| Chimei Innolux          | 54        | 7.88%   |
| LG Display              | 51        | 7.45%   |
| BOE                     | 49        | 7.15%   |
| Goldstar                | 30        | 4.38%   |
| Philips                 | 29        | 4.23%   |
| Lenovo                  | 26        | 3.8%    |
| AOC                     | 16        | 2.34%   |
| Sharp                   | 15        | 2.19%   |
| Hewlett-Packard         | 14        | 2.04%   |
| Ancor Communications    | 12        | 1.75%   |
| ASUSTek Computer        | 9         | 1.31%   |
| ViewSonic               | 8         | 1.17%   |
| Chi Mei Optoelectronics | 8         | 1.17%   |
| InfoVision              | 7         | 1.02%   |
| Unknown                 | 6         | 0.88%   |
| Apple                   | 6         | 0.88%   |
| LG Philips              | 5         | 0.73%   |
| BenQ                    | 5         | 0.73%   |
| Acer                    | 5         | 0.73%   |
| Toshiba                 | 4         | 0.58%   |
| Lenovo Group Limited    | 4         | 0.58%   |
| SANYO                   | 3         | 0.44%   |
| Panasonic               | 3         | 0.44%   |
| LG Electronics          | 3         | 0.44%   |
| CSO                     | 3         | 0.44%   |
| Unknown                 | 3         | 0.44%   |
| VIE                     | 2         | 0.29%   |
| Sony                    | 2         | 0.29%   |
| PANDA                   | 2         | 0.29%   |
| NEX                     | 2         | 0.29%   |
| Iiyama                  | 2         | 0.29%   |
| Hyundai ImageQuest      | 2         | 0.29%   |
| HKC                     | 2         | 0.29%   |
| Hitachi                 | 2         | 0.29%   |
| Gigabyte Technology     | 2         | 0.29%   |
| Eizo                    | 2         | 0.29%   |
| CVT                     | 2         | 0.29%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                     | 7         | 0.98%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 7         | 0.98%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 6         | 0.84%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 6         | 0.84%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 5         | 0.7%    |
| Philips PHL 273V5 PHLC0D2 1920x1080 598x336mm 27.0-inch               | 4         | 0.56%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 4         | 0.56%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 4         | 0.56%   |
| Philips 222EL PHLC052 1920x1080 476x268mm 21.5-inch                   | 4         | 0.56%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 4         | 0.56%   |
| Goldstar W2243 GSM56FF 1920x1080 477x269mm 21.6-inch                  | 4         | 0.56%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                     | 4         | 0.56%   |
| Dell P2219H DELA115 1920x1080 476x267mm 21.5-inch                     | 4         | 0.56%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 4         | 0.56%   |
| Samsung Electronics SyncMaster SAM044B 1680x1050 474x296mm 22.0-inch  | 3         | 0.42%   |
| Samsung Electronics SyncMaster SAM034D 1280x1024 376x301mm 19.0-inch  | 3         | 0.42%   |
| Samsung Electronics LF27T450F SAM7099 1920x1080 597x336mm 27.0-inch   | 3         | 0.42%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 3         | 0.42%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 3         | 0.42%   |
| Dell U2415 DELA0B9 1920x1080 518x324mm 24.1-inch                      | 3         | 0.42%   |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                 | 3         | 0.42%   |
| AU Optronics LCD Monitor AUO492D 1920x1080 293x165mm 13.2-inch        | 3         | 0.42%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 3         | 0.42%   |
| AU Optronics LCD Monitor AUO102D 1920x1080 293x165mm 13.2-inch        | 3         | 0.42%   |
| Unknown                                                               | 3         | 0.42%   |
| ViewSonic VX2237 SERIES VSC2C24 1680x1050 474x296mm 22.0-inch         | 2         | 0.28%   |
| Unknown LCD Monitor RIS RD24L 1920x1080                               | 2         | 0.28%   |
| Toshiba LCD Monitor LCD2207 1280x800 287x180mm 13.3-inch              | 2         | 0.28%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 2         | 0.28%   |
| SANYO LCD MONITOR SAN07BE 1280x1024 350x270mm 17.4-inch               | 2         | 0.28%   |
| Samsung Electronics SyncMaster SAM041D 1920x1200 459x296mm 21.5-inch  | 2         | 0.28%   |
| Samsung Electronics SA300/SA350 SAM078E 1920x1080 477x268mm 21.5-inch | 2         | 0.28%   |
| Samsung Electronics S24R65x SAM1023 1920x1080 527x296mm 23.8-inch     | 2         | 0.28%   |
| Samsung Electronics S22D390 SAM0B63 1920x1080 477x268mm 21.5-inch     | 2         | 0.28%   |
| Samsung Electronics LS27A80 SAM7184 3840x2160 597x336mm 27.0-inch     | 2         | 0.28%   |
| Samsung Electronics LCD Monitor SMBX2450 1920x1080                    | 2         | 0.28%   |
| Samsung Electronics LCD Monitor SDC4142 3840x2160 294x165mm 13.3-inch | 2         | 0.28%   |
| Samsung Electronics LC34G55T SAM7119 3440x1440 798x334mm 34.1-inch    | 2         | 0.28%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 2         | 0.28%   |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 521x293mm 23.5-inch     | 2         | 0.28%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 336       | 52.5%   |
| 1366x768 (WXGA)    | 74        | 11.56%  |
| 3840x2160 (4K)     | 52        | 8.13%   |
| 2560x1440 (QHD)    | 34        | 5.31%   |
| 1680x1050 (WSXGA+) | 21        | 3.28%   |
| 1280x1024 (SXGA)   | 20        | 3.13%   |
| 1920x1200 (WUXGA)  | 19        | 2.97%   |
| 1280x800 (WXGA)    | 13        | 2.03%   |
| Unknown            | 11        | 1.72%   |
| 1600x900 (HD+)     | 9         | 1.41%   |
| 1440x900 (WXGA+)   | 9         | 1.41%   |
| 3440x1440          | 7         | 1.09%   |
| 2560x1080          | 7         | 1.09%   |
| 2560x1600          | 4         | 0.63%   |
| 3840x1080          | 3         | 0.47%   |
| 1024x768 (XGA)     | 3         | 0.47%   |
| 3200x1800 (QHD+)   | 2         | 0.31%   |
| 1920x540           | 2         | 0.31%   |
| 1280x768           | 2         | 0.31%   |
| 5360x1440          | 1         | 0.16%   |
| 5120x1440          | 1         | 0.16%   |
| 4480x1440          | 1         | 0.16%   |
| 3520x1080          | 1         | 0.16%   |
| 3456x2160          | 1         | 0.16%   |
| 3200x1200          | 1         | 0.16%   |
| 2880x1800          | 1         | 0.16%   |
| 2304x1024          | 1         | 0.16%   |
| 2160x1440          | 1         | 0.16%   |
| 1600x2560          | 1         | 0.16%   |
| 1360x768           | 1         | 0.16%   |
| 1024x600           | 1         | 0.16%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 149       | 21.98%  |
| 13      | 75        | 11.06%  |
| 24      | 70        | 10.32%  |
| 27      | 60        | 8.85%   |
| 21      | 57        | 8.41%   |
| 23      | 53        | 7.82%   |
| 14      | 47        | 6.93%   |
| Unknown | 34        | 5.01%   |
| 22      | 19        | 2.8%    |
| 17      | 17        | 2.51%   |
| 19      | 14        | 2.06%   |
| 34      | 11        | 1.62%   |
| 12      | 8         | 1.18%   |
| 31      | 7         | 1.03%   |
| 20      | 6         | 0.88%   |
| 84      | 5         | 0.74%   |
| 72      | 5         | 0.74%   |
| 40      | 5         | 0.74%   |
| 33      | 5         | 0.74%   |
| 16      | 5         | 0.74%   |
| 18      | 4         | 0.59%   |
| 11      | 3         | 0.44%   |
| 65      | 2         | 0.29%   |
| 32      | 2         | 0.29%   |
| 26      | 2         | 0.29%   |
| 25      | 2         | 0.29%   |
| 8       | 2         | 0.29%   |
| 60      | 1         | 0.15%   |
| 54      | 1         | 0.15%   |
| 52      | 1         | 0.15%   |
| 49      | 1         | 0.15%   |
| 48      | 1         | 0.15%   |
| 43      | 1         | 0.15%   |
| 42      | 1         | 0.15%   |
| 29      | 1         | 0.15%   |
| 10      | 1         | 0.15%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 239       | 35.94%  |
| 501-600     | 172       | 25.86%  |
| 401-500     | 86        | 12.93%  |
| 201-300     | 52        | 7.82%   |
| Unknown     | 34        | 5.11%   |
| 351-400     | 25        | 3.76%   |
| 701-800     | 18        | 2.71%   |
| 601-700     | 13        | 1.95%   |
| 1501-2000   | 10        | 1.5%    |
| 1001-1500   | 7         | 1.05%   |
| 801-900     | 5         | 0.75%   |
| 101-200     | 2         | 0.3%    |
| 901-1000    | 2         | 0.3%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 454       | 75.79%  |
| 16/10   | 73        | 12.19%  |
| Unknown | 33        | 5.51%   |
| 5/4     | 15        | 2.5%    |
| 21/9    | 11        | 1.84%   |
| 4/3     | 7         | 1.17%   |
| 3/2     | 4         | 0.67%   |
| 1.96    | 1         | 0.17%   |
| 0.58    | 1         | 0.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 164       | 24.48%  |
| 101-110        | 149       | 22.24%  |
| 81-90          | 85        | 12.69%  |
| 301-350        | 62        | 9.25%   |
| 71-80          | 36        | 5.37%   |
| Unknown        | 34        | 5.07%   |
| 151-200        | 33        | 4.93%   |
| 351-500        | 26        | 3.88%   |
| 251-300        | 20        | 2.99%   |
| More than 1000 | 16        | 2.39%   |
| 61-70          | 8         | 1.19%   |
| 121-130        | 8         | 1.19%   |
| 501-1000       | 8         | 1.19%   |
| 141-150        | 7         | 1.04%   |
| 111-120        | 4         | 0.6%    |
| 51-60          | 3         | 0.45%   |
| 131-140        | 3         | 0.45%   |
| 1-40           | 2         | 0.3%    |
| 41-50          | 1         | 0.15%   |
| 91-100         | 1         | 0.15%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 227       | 34.71%  |
| 121-160       | 165       | 25.23%  |
| 101-120       | 154       | 23.55%  |
| 161-240       | 36        | 5.5%    |
| Unknown       | 34        | 5.2%    |
| More than 240 | 27        | 4.13%   |
| 1-50          | 11        | 1.68%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 465       | 74.64%  |
| 2     | 113       | 18.14%  |
| 0     | 30        | 4.82%   |
| 3     | 13        | 2.09%   |
| 4     | 2         | 0.32%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 326       | 35.67%  |
| Realtek Semiconductor           | 318       | 34.79%  |
| Qualcomm Atheros                | 88        | 9.63%   |
| Broadcom                        | 34        | 3.72%   |
| Ralink Technology               | 17        | 1.86%   |
| Broadcom Limited                | 14        | 1.53%   |
| TP-Link                         | 12        | 1.31%   |
| Lenovo                          | 12        | 1.31%   |
| MediaTek                        | 9         | 0.98%   |
| Edimax Technology               | 9         | 0.98%   |
| Marvell Technology Group        | 7         | 0.77%   |
| ASIX Electronics                | 6         | 0.66%   |
| Xiaomi                          | 5         | 0.55%   |
| Nvidia                          | 5         | 0.55%   |
| DisplayLink                     | 5         | 0.55%   |
| Samsung Electronics             | 4         | 0.44%   |
| Qualcomm Atheros Communications | 4         | 0.44%   |
| Ralink                          | 3         | 0.33%   |
| Huawei Technologies             | 3         | 0.33%   |
| Texas Instruments               | 2         | 0.22%   |
| Microsoft                       | 2         | 0.22%   |
| Google                          | 2         | 0.22%   |
| D-Link                          | 2         | 0.22%   |
| Aquantia                        | 2         | 0.22%   |
| VIA Technologies                | 1         | 0.11%   |
| U.S. Robotics                   | 1         | 0.11%   |
| U-Blox                          | 1         | 0.11%   |
| Toshiba                         | 1         | 0.11%   |
| STMicroelectronics              | 1         | 0.11%   |
| ROCCAT                          | 1         | 0.11%   |
| Qualcomm                        | 1         | 0.11%   |
| PEAK-System Technik             | 1         | 0.11%   |
| Nokia Mobile Phones             | 1         | 0.11%   |
| Mellanox Technologies           | 1         | 0.11%   |
| Linksys                         | 1         | 0.11%   |
| LG Electronics                  | 1         | 0.11%   |
| ICS Advent                      | 1         | 0.11%   |
| HMD Global                      | 1         | 0.11%   |
| Hewlett-Packard                 | 1         | 0.11%   |
| GDMicroelectronics              | 1         | 0.11%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 214       | 19.85%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 36        | 3.34%   |
| Intel Wireless 8265 / 8275                                        | 24        | 2.23%   |
| Intel Wi-Fi 6 AX201                                               | 23        | 2.13%   |
| Intel Wi-Fi 6 AX200                                               | 22        | 2.04%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 22        | 2.04%   |
| Realtek RTL8125 2.5GbE Controller                                 | 21        | 1.95%   |
| Intel Ethernet Connection (2) I219-V                              | 19        | 1.76%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 17        | 1.58%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 16        | 1.48%   |
| Intel I211 Gigabit Network Connection                             | 15        | 1.39%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 14        | 1.3%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 14        | 1.3%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 11        | 1.02%   |
| Intel Wireless 3165                                               | 11        | 1.02%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 11        | 1.02%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 10        | 0.93%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 10        | 0.93%   |
| Intel Wireless 8260                                               | 10        | 0.93%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 10        | 0.93%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 9         | 0.83%   |
| Intel Wireless 3160                                               | 9         | 0.83%   |
| Intel Ethernet Connection (6) I219-V                              | 9         | 0.83%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 8         | 0.74%   |
| Intel Ethernet Connection I217-LM                                 | 8         | 0.74%   |
| Intel Ethernet Connection (7) I219-V                              | 8         | 0.74%   |
| Intel Ethernet Connection (7) I219-LM                             | 8         | 0.74%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 8         | 0.74%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 7         | 0.65%   |
| Realtek 802.11ac NIC                                              | 7         | 0.65%   |
| Intel Wireless 7265                                               | 7         | 0.65%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 7         | 0.65%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 7         | 0.65%   |
| Intel Ethernet Connection (10) I219-V                             | 7         | 0.65%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 7         | 0.65%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 6         | 0.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 6         | 0.56%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 6         | 0.56%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 6         | 0.56%   |
| Intel I210 Gigabit Network Connection                             | 6         | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 228       | 49.35%  |
| Qualcomm Atheros                | 69        | 14.94%  |
| Realtek Semiconductor           | 65        | 14.07%  |
| Broadcom                        | 29        | 6.28%   |
| Ralink Technology               | 17        | 3.68%   |
| TP-Link                         | 11        | 2.38%   |
| MediaTek                        | 9         | 1.95%   |
| Edimax Technology               | 9         | 1.95%   |
| Broadcom Limited                | 9         | 1.95%   |
| Qualcomm Atheros Communications | 4         | 0.87%   |
| Ralink                          | 3         | 0.65%   |
| Microsoft                       | 2         | 0.43%   |
| D-Link                          | 2         | 0.43%   |
| Qualcomm                        | 1         | 0.22%   |
| Marvell Technology Group        | 1         | 0.22%   |
| Dell                            | 1         | 0.22%   |
| BUFFALO                         | 1         | 0.22%   |
| ASUSTek Computer                | 1         | 0.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 24        | 5.15%   |
| Intel Wi-Fi 6 AX201                                                     | 23        | 4.94%   |
| Intel Wi-Fi 6 AX200                                                     | 22        | 4.72%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 17        | 3.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 14        | 3%      |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 14        | 3%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 11        | 2.36%   |
| Intel Wireless 3165                                                     | 11        | 2.36%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 11        | 2.36%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 10        | 2.15%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 10        | 2.15%   |
| Intel Wireless 8260                                                     | 10        | 2.15%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 10        | 2.15%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 1.93%   |
| Intel Wireless 3160                                                     | 9         | 1.93%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 8         | 1.72%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 8         | 1.72%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 7         | 1.5%    |
| Realtek 802.11ac NIC                                                    | 7         | 1.5%    |
| Intel Wireless 7265                                                     | 7         | 1.5%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 7         | 1.5%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 7         | 1.5%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 7         | 1.5%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 6         | 1.29%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 1.29%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 1.29%   |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 6         | 1.29%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 6         | 1.29%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 1.07%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 5         | 1.07%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 5         | 1.07%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 5         | 1.07%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 1.07%   |
| Intel Wireless-AC 9260                                                  | 5         | 1.07%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 5         | 1.07%   |
| Ralink MT7601U Wireless Adapter                                         | 4         | 0.86%   |
| Qualcomm Atheros AR9271 802.11n                                         | 4         | 0.86%   |
| Intel Wireless 7260                                                     | 4         | 0.86%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 0.86%   |
| Edimax RTL8192S WLAN Adapter                                            | 4         | 0.86%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 292       | 50.17%  |
| Intel                    | 188       | 32.3%   |
| Qualcomm Atheros         | 27        | 4.64%   |
| Lenovo                   | 12        | 2.06%   |
| Broadcom                 | 12        | 2.06%   |
| Marvell Technology Group | 6         | 1.03%   |
| Broadcom Limited         | 6         | 1.03%   |
| ASIX Electronics         | 6         | 1.03%   |
| Xiaomi                   | 5         | 0.86%   |
| Nvidia                   | 5         | 0.86%   |
| DisplayLink              | 5         | 0.86%   |
| Samsung Electronics      | 3         | 0.52%   |
| Huawei Technologies      | 2         | 0.34%   |
| Google                   | 2         | 0.34%   |
| Aquantia                 | 2         | 0.34%   |
| VIA Technologies         | 1         | 0.17%   |
| TP-Link                  | 1         | 0.17%   |
| Mellanox Technologies    | 1         | 0.17%   |
| Linksys                  | 1         | 0.17%   |
| ICS Advent               | 1         | 0.17%   |
| HMD Global               | 1         | 0.17%   |
| Davicom Semiconductor    | 1         | 0.17%   |
| Attansic Technology      | 1         | 0.17%   |
| Accton Technology        | 1         | 0.17%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 214       | 35.85%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 36        | 6.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 22        | 3.69%   |
| Realtek RTL8125 2.5GbE Controller                                 | 21        | 3.52%   |
| Intel Ethernet Connection (2) I219-V                              | 19        | 3.18%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 16        | 2.68%   |
| Intel I211 Gigabit Network Connection                             | 15        | 2.51%   |
| Intel Ethernet Connection (6) I219-V                              | 9         | 1.51%   |
| Intel Ethernet Connection I217-LM                                 | 8         | 1.34%   |
| Intel Ethernet Connection (7) I219-V                              | 8         | 1.34%   |
| Intel Ethernet Connection (7) I219-LM                             | 8         | 1.34%   |
| Intel Ethernet Connection (10) I219-V                             | 7         | 1.17%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 6         | 1.01%   |
| Intel I210 Gigabit Network Connection                             | 6         | 1.01%   |
| Intel Ethernet Connection (4) I219-LM                             | 6         | 1.01%   |
| Intel Ethernet Connection (13) I219-V                             | 6         | 1.01%   |
| ASIX AX88179 Gigabit Ethernet                                     | 6         | 1.01%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 5         | 0.84%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 5         | 0.84%   |
| Intel Ethernet Controller I225-V                                  | 5         | 0.84%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 0.84%   |
| Intel Ethernet Connection (14) I219-V                             | 5         | 0.84%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 4         | 0.67%   |
| Lenovo USB-C Dock Ethernet                                        | 4         | 0.67%   |
| Intel Ethernet Connection I217-V                                  | 4         | 0.67%   |
| Intel Ethernet Connection (5) I219-LM                             | 4         | 0.67%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 0.67%   |
| Intel Ethernet Connection (2) I219-LM                             | 4         | 0.67%   |
| Intel Ethernet Connection (11) I219-LM                            | 4         | 0.67%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 0.67%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 0.5%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 0.5%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 0.5%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 0.5%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 0.5%    |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 3         | 0.5%    |
| Intel Ethernet Connection (14) I219-LM                            | 3         | 0.5%    |
| Intel Ethernet Connection (11) I219-V                             | 3         | 0.5%    |
| Intel 82574L Gigabit Network Connection                           | 3         | 0.5%    |
| Intel 82567LM Gigabit Network Connection                          | 3         | 0.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 528       | 53.77%  |
| WiFi     | 439       | 44.7%   |
| Modem    | 13        | 1.32%   |
| Unknown  | 2         | 0.2%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 324       | 50.78%  |
| Ethernet | 313       | 49.06%  |
| Modem    | 1         | 0.16%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 299       | 48.94%  |
| 1     | 287       | 46.97%  |
| 3     | 16        | 2.62%   |
| 0     | 6         | 0.98%   |
| 7     | 1         | 0.16%   |
| 6     | 1         | 0.16%   |
| 4     | 1         | 0.16%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 519       | 83.17%  |
| Yes  | 105       | 16.83%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 200       | 56.5%   |
| Qualcomm Atheros Communications | 28        | 7.91%   |
| Realtek Semiconductor           | 26        | 7.34%   |
| Cambridge Silicon Radio         | 25        | 7.06%   |
| IMC Networks                    | 18        | 5.08%   |
| Broadcom                        | 12        | 3.39%   |
| Apple                           | 11        | 3.11%   |
| Lite-On Technology              | 7         | 1.98%   |
| Foxconn / Hon Hai               | 6         | 1.69%   |
| Dell                            | 4         | 1.13%   |
| ASUSTek Computer                | 4         | 1.13%   |
| TP-Link                         | 2         | 0.56%   |
| Realtek                         | 2         | 0.56%   |
| MediaTek                        | 2         | 0.56%   |
| Hewlett-Packard                 | 2         | 0.56%   |
| Askey Computer                  | 2         | 0.56%   |
| Toshiba                         | 1         | 0.28%   |
| Marvell Semiconductor           | 1         | 0.28%   |
| Actions                         | 1         | 0.28%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 69        | 19.49%  |
| Intel AX201 Bluetooth                               | 55        | 15.54%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 32        | 9.04%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 25        | 7.06%   |
| Qualcomm Atheros  Bluetooth Device                  | 19        | 5.37%   |
| Intel AX200 Bluetooth                               | 19        | 5.37%   |
| Realtek Bluetooth Radio                             | 14        | 3.95%   |
| Realtek  Bluetooth 4.2 Adapter                      | 7         | 1.98%   |
| Lite-On Bluetooth Device                            | 6         | 1.69%   |
| Intel Bluetooth Device                              | 6         | 1.69%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 5         | 1.41%   |
| Intel AX210 Bluetooth                               | 5         | 1.41%   |
| IMC Networks Wireless_Device                        | 5         | 1.41%   |
| IMC Networks Bluetooth Device                       | 5         | 1.41%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 4         | 1.13%   |
| Intel Wireless-AC 3168 Bluetooth                    | 4         | 1.13%   |
| IMC Networks Bluetooth Radio                        | 4         | 1.13%   |
| Apple Bluetooth USB Host Controller                 | 4         | 1.13%   |
| Apple Bluetooth Host Controller                     | 4         | 1.13%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 3         | 0.85%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 0.85%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 3         | 0.85%   |
| TP-Link UB500 Adapter                               | 2         | 0.56%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 0.56%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 0.56%   |
| IMC Networks Bluetooth USB Host Controller          | 2         | 0.56%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 0.56%   |
| Foxconn / Hon Hai BT                                | 2         | 0.56%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 0.56%   |
| Dell DW375 Bluetooth Module                         | 2         | 0.56%   |
| Dell BCM20702A0 Bluetooth Module                    | 2         | 0.56%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 0.56%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 2         | 0.56%   |
| ASUS Bluetooth Adapter                              | 2         | 0.56%   |
| Askey Bluetooth Device                              | 2         | 0.56%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2         | 0.56%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.28%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.28%   |
| Realtek Bluetooth Radio                             | 1         | 0.28%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 0.28%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 514       | 58.88%  |
| Nvidia                                       | 173       | 19.82%  |
| AMD                                          | 91        | 10.42%  |
| Lenovo                                       | 13        | 1.49%   |
| C-Media Electronics                          | 10        | 1.15%   |
| Creative Labs                                | 7         | 0.8%    |
| Logitech                                     | 6         | 0.69%   |
| XMOS                                         | 5         | 0.57%   |
| Creative Technology                          | 5         | 0.57%   |
| Texas Instruments                            | 4         | 0.46%   |
| Realtek Semiconductor                        | 4         | 0.46%   |
| GN Netcom                                    | 4         | 0.46%   |
| Focusrite-Novation                           | 4         | 0.46%   |
| Microsoft                                    | 3         | 0.34%   |
| JMTek                                        | 3         | 0.34%   |
| VIA Technologies                             | 2         | 0.23%   |
| SteelSeries ApS                              | 2         | 0.23%   |
| Razer USA                                    | 2         | 0.23%   |
| Kingston Technology                          | 2         | 0.23%   |
| Generalplus Technology                       | 2         | 0.23%   |
| FIFINE Microphones                           | 2         | 0.23%   |
| Cambridge Silicon Radio                      | 2         | 0.23%   |
| Unknown                                      | 2         | 0.23%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.11%   |
| Sennheiser Communications                    | 1         | 0.11%   |
| Samson Technologies                          | 1         | 0.11%   |
| PreSonus Audio Electronics                   | 1         | 0.11%   |
| Plantronics                                  | 1         | 0.11%   |
| Meridian                                     | 1         | 0.11%   |
| iCreate Technologies                         | 1         | 0.11%   |
| Giga-Byte Technology                         | 1         | 0.11%   |
| EGO SYStems                                  | 1         | 0.11%   |
| Dell                                         | 1         | 0.11%   |
| ASUSTek Computer                             | 1         | 0.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 64        | 6.56%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 38        | 3.89%   |
| Intel Cannon Lake PCH cAVS                                                 | 33        | 3.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 28        | 2.87%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 28        | 2.87%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 28        | 2.87%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 28        | 2.87%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 27        | 2.77%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 26        | 2.66%   |
| Intel 200 Series PCH HD Audio                                              | 25        | 2.56%   |
| AMD Family 17h/19h HD Audio Controller                                     | 24        | 2.46%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 23        | 2.36%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 19        | 1.95%   |
| Nvidia GP107GL High Definition Audio Controller                            | 18        | 1.84%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 18        | 1.84%   |
| AMD Starship/Matisse HD Audio Controller                                   | 17        | 1.74%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 16        | 1.64%   |
| Intel Comet Lake PCH-LP cAVS                                               | 16        | 1.64%   |
| Intel Comet Lake PCH cAVS                                                  | 16        | 1.64%   |
| Intel Broadwell-U Audio Controller                                         | 16        | 1.64%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 15        | 1.54%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 15        | 1.54%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 13        | 1.33%   |
| Intel Alder Lake-S HD Audio Controller                                     | 12        | 1.23%   |
| Nvidia GP104 High Definition Audio Controller                              | 11        | 1.13%   |
| Intel Haswell-ULT HD Audio Controller                                      | 11        | 1.13%   |
| Intel 8 Series HD Audio Controller                                         | 11        | 1.13%   |
| Nvidia GP106 High Definition Audio Controller                              | 10        | 1.02%   |
| Nvidia GA104 High Definition Audio Controller                              | 10        | 1.02%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 10        | 1.02%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 10        | 1.02%   |
| Nvidia TU116 High Definition Audio Controller                              | 9         | 0.92%   |
| Nvidia TU106 High Definition Audio Controller                              | 9         | 0.92%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 9         | 0.92%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 9         | 0.92%   |
| AMD FCH Azalia Controller                                                  | 9         | 0.92%   |
| Nvidia High Definition Audio Controller                                    | 8         | 0.82%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 8         | 0.82%   |
| Nvidia GF108 High Definition Audio Controller                              | 8         | 0.82%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 8         | 0.82%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 78        | 19.7%   |
| SK hynix            | 66        | 16.67%  |
| Kingston            | 56        | 14.14%  |
| Micron Technology   | 47        | 11.87%  |
| Unknown             | 38        | 9.6%    |
| Crucial             | 29        | 7.32%   |
| Corsair             | 21        | 5.3%    |
| G.Skill             | 20        | 5.05%   |
| Ramaxel Technology  | 13        | 3.28%   |
| Transcend           | 6         | 1.52%   |
| Elpida              | 4         | 1.01%   |
| Team                | 3         | 0.76%   |
| Nanya Technology    | 3         | 0.76%   |
| A-DATA Technology   | 3         | 0.76%   |
| GeIL                | 2         | 0.51%   |
| V-Color             | 1         | 0.25%   |
| Unknown (09D5)      | 1         | 0.25%   |
| Patriot             | 1         | 0.25%   |
| KETECH              | 1         | 0.25%   |
| Avant               | 1         | 0.25%   |
| ASint Technology    | 1         | 0.25%   |
| 48spaces            | 1         | 0.25%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s        | 5         | 1.2%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 4         | 0.96%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s       | 4         | 0.96%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 4         | 0.96%   |
| Unknown RAM Module 2GB DIMM 800MT/s                          | 3         | 0.72%   |
| SK hynix RAM HMT451U6AFR8C-PB 4096MB DIMM DDR3 1600MT/s      | 3         | 0.72%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 3         | 0.72%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 3         | 0.72%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s       | 3         | 0.72%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 3         | 0.72%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s       | 3         | 0.72%   |
| Samsung RAM K4E6E304EB-EGCG 4GB Row Of Chips LPDDR3 2133MT/s | 3         | 0.72%   |
| Micron RAM MTC8C1084S1SC48BA1 16GB SODIMM DDR5 4800MT/s      | 3         | 0.72%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s        | 3         | 0.72%   |
| Kingston RAM 9905622-058.A00G 8GB DIMM DDR4 2133MT/s         | 3         | 0.72%   |
| Unknown RAM Module 2048MB SODIMM DDR2                        | 2         | 0.48%   |
| Unknown RAM Module 2048MB DIMM SDRAM                         | 2         | 0.48%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                  | 2         | 0.48%   |
| Unknown RAM Module 1GB DIMM 800MT/s                          | 2         | 0.48%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                | 2         | 0.48%   |
| Unknown RAM Module 1024MB SODIMM DDR2                        | 2         | 0.48%   |
| Unknown RAM MEM-DOWN 8192MB SODIMM DDR4 2400MT/s             | 2         | 0.48%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.48%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s         | 2         | 0.48%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s      | 2         | 0.48%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s      | 2         | 0.48%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s       | 2         | 0.48%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s       | 2         | 0.48%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s      | 2         | 0.48%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s       | 2         | 0.48%   |
| Samsung RAM Module 8GB SODIMM DDR4 2667MT/s                  | 2         | 0.48%   |
| Samsung RAM M471B5673DZ1-CF8 2048MB SODIMM 1067MT/s          | 2         | 0.48%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 2         | 0.48%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s       | 2         | 0.48%   |
| Samsung RAM M471A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s       | 2         | 0.48%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 2         | 0.48%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s        | 2         | 0.48%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s  | 2         | 0.48%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2400MT/s        | 2         | 0.48%   |
| Samsung RAM M425R2GA3BB0-CQKOD 16GB SODIMM DDR5 4800MT/s     | 2         | 0.48%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 198       | 58.06%  |
| DDR3    | 74        | 21.7%   |
| Unknown | 19        | 5.57%   |
| DDR2    | 18        | 5.28%   |
| LPDDR3  | 11        | 3.23%   |
| DDR5    | 7         | 2.05%   |
| SDRAM   | 4         | 1.17%   |
| LPDDR4  | 4         | 1.17%   |
| DDR     | 4         | 1.17%   |
| LPDDR5  | 2         | 0.59%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 177       | 52.06%  |
| DIMM         | 142       | 41.76%  |
| Row Of Chips | 20        | 5.88%   |
| Chip         | 1         | 0.29%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 117       | 32.05%  |
| 16384 | 89        | 24.38%  |
| 4096  | 86        | 23.56%  |
| 2048  | 40        | 10.96%  |
| 32768 | 17        | 4.66%   |
| 1024  | 16        | 4.38%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 62        | 16.71%  |
| 2667    | 60        | 16.17%  |
| 1600    | 53        | 14.29%  |
| 2400    | 32        | 8.63%   |
| 2133    | 31        | 8.36%   |
| 800     | 15        | 4.04%   |
| 1333    | 14        | 3.77%   |
| 667     | 12        | 3.23%   |
| 4800    | 8         | 2.16%   |
| 3600    | 7         | 1.89%   |
| Unknown | 7         | 1.89%   |
| 3266    | 6         | 1.62%   |
| 3466    | 5         | 1.35%   |
| 1867    | 5         | 1.35%   |
| 1334    | 5         | 1.35%   |
| 1067    | 5         | 1.35%   |
| 4267    | 4         | 1.08%   |
| 3800    | 3         | 0.81%   |
| 533     | 3         | 0.81%   |
| 6400    | 2         | 0.54%   |
| 3933    | 2         | 0.54%   |
| 3666    | 2         | 0.54%   |
| 3534    | 2         | 0.54%   |
| 3151    | 2         | 0.54%   |
| 2933    | 2         | 0.54%   |
| 2000    | 2         | 0.54%   |
| 1866    | 2         | 0.54%   |
| 1800    | 2         | 0.54%   |
| 49926   | 1         | 0.27%   |
| 8400    | 1         | 0.27%   |
| 5600    | 1         | 0.27%   |
| 4400    | 1         | 0.27%   |
| 3733    | 1         | 0.27%   |
| 3400    | 1         | 0.27%   |
| 3334    | 1         | 0.27%   |
| 3066    | 1         | 0.27%   |
| 3000    | 1         | 0.27%   |
| 2800    | 1         | 0.27%   |
| 2666    | 1         | 0.27%   |
| 2134    | 1         | 0.27%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 10        | 45.45%  |
| Samsung Electronics   | 5         | 22.73%  |
| Canon                 | 2         | 9.09%   |
| Brother Industries    | 2         | 9.09%   |
| Lexmark International | 1         | 4.55%   |
| GODEX INTERNATIONAL   | 1         | 4.55%   |
| BIXOLON               | 1         | 4.55%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| HP Officejet 4500 G510g-m          | 3         | 13.64%  |
| HP DeskJet 4670 series             | 3         | 13.64%  |
| Samsung M2070 Series               | 2         | 9.09%   |
| Samsung SCX-4623 Series            | 1         | 4.55%   |
| Samsung ML-1610 Mono Laser Printer | 1         | 4.55%   |
| Samsung M288x Series               | 1         | 4.55%   |
| Lexmark International CS417dn      | 1         | 4.55%   |
| HP Printing Support                | 1         | 4.55%   |
| HP LaserJet M14-M17                | 1         | 4.55%   |
| HP Deskjet 4640 series             | 1         | 4.55%   |
| HP DeskJet 2700 series             | 1         | 4.55%   |
| GODEX INTERNATIONAL DT2            | 1         | 4.55%   |
| Canon TR7500 series                | 1         | 4.55%   |
| Canon PIXMA MX490 Series           | 1         | 4.55%   |
| Brother Printer                    | 1         | 4.55%   |
| Brother MFC-J497DW                 | 1         | 4.55%   |
| BIXOLON BIXOLON_SLP-T400           | 1         | 4.55%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 3         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 100 | 2         | 66.67%  |
| Canon CanoScan LiDE 220 | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| IMC Networks                           | 56        | 15.22%  |
| Chicony Electronics                    | 56        | 15.22%  |
| Realtek Semiconductor                  | 44        | 11.96%  |
| Logitech                               | 30        | 8.15%   |
| Microdia                               | 24        | 6.52%   |
| Sunplus Innovation Technology          | 22        | 5.98%   |
| Microsoft                              | 20        | 5.43%   |
| Acer                                   | 16        | 4.35%   |
| Apple                                  | 14        | 3.8%    |
| Bison Electronics                      | 10        | 2.72%   |
| Quanta                                 | 8         | 2.17%   |
| Lite-On Technology                     | 8         | 2.17%   |
| Cheng Uei Precision Industry (Foxlink) | 8         | 2.17%   |
| Suyin                                  | 7         | 1.9%    |
| Syntek                                 | 6         | 1.63%   |
| Generalplus Technology                 | 6         | 1.63%   |
| Samsung Electronics                    | 5         | 1.36%   |
| Luxvisions Innotech Limited            | 5         | 1.36%   |
| Silicon Motion                         | 4         | 1.09%   |
| Lenovo                                 | 3         | 0.82%   |
| Alcor Micro                            | 3         | 0.82%   |
| Jieli Technology                       | 2         | 0.54%   |
| Cubeternet                             | 2         | 0.54%   |
| ALi                                    | 2         | 0.54%   |
| Z-Star Microelectronics                | 1         | 0.27%   |
| Yealink Network Technology             | 1         | 0.27%   |
| Xiaomi                                 | 1         | 0.27%   |
| Primax Electronics                     | 1         | 0.27%   |
| Hewlett-Packard                        | 1         | 0.27%   |
| eMPIA Technology                       | 1         | 0.27%   |
| Aveo Technology                        | 1         | 0.27%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD            | 22        | 5.96%   |
| Chicony Integrated Camera               | 20        | 5.42%   |
| IMC Networks USB2.0 HD UVC WebCam       | 16        | 4.34%   |
| IMC Networks Integrated Camera          | 15        | 4.07%   |
| Microsoft LifeCam HD-3000               | 14        | 3.79%   |
| IMC Networks USB2.0 VGA UVC WebCam      | 13        | 3.52%   |
| Microdia Integrated_Webcam_HD           | 10        | 2.71%   |
| Acer Integrated Camera                  | 8         | 2.17%   |
| Logitech Webcam C270                    | 6         | 1.63%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X         | 6         | 1.63%   |
| Syntek Integrated Camera                | 5         | 1.36%   |
| Samsung Galaxy series, misc. (MTP mode) | 5         | 1.36%   |
| Sunplus Integrated_Webcam_HD            | 4         | 1.08%   |
| Logitech Webcam C310                    | 4         | 1.08%   |
| Lite-On HP HD Camera                    | 4         | 1.08%   |
| Generalplus GENERAL WEBCAM              | 4         | 1.08%   |
| Chicony HP HD Camera                    | 4         | 1.08%   |
| Chicony EasyCamera                      | 4         | 1.08%   |
| Bison SunplusIT Integrated Camera       | 4         | 1.08%   |
| Sunplus FHD Camera Microphone           | 3         | 0.81%   |
| Realtek Lenovo EasyCamera               | 3         | 0.81%   |
| Realtek Integrated Webcam HD            | 3         | 0.81%   |
| Logitech HD Pro Webcam C920             | 3         | 0.81%   |
| IMC Networks USB2.0 UVC HD Webcam       | 3         | 0.81%   |
| IMC Networks USB2.0 HD IR UVC WebCam    | 3         | 0.81%   |
| Chicony Lenovo EasyCamera               | 3         | 0.81%   |
| Chicony Integrated Camera (1280x720@30) | 3         | 0.81%   |
| Acer Lenovo EasyCamera                  | 3         | 0.81%   |
| Acer BisonCam, NB Pro                   | 3         | 0.81%   |
| Suyin Integrated_Webcam_HD              | 2         | 0.54%   |
| Sunplus Laptop_Integrated_Webcam_FHD    | 2         | 0.54%   |
| Sunplus ASUS Webcam                     | 2         | 0.54%   |
| Realtek USB2.0 HD UVC WebCam            | 2         | 0.54%   |
| Realtek USB Camera                      | 2         | 0.54%   |
| Realtek HP Wide Vision HD Camera        | 2         | 0.54%   |
| Quanta USB Webcam                       | 2         | 0.54%   |
| Quanta HP TrueVision HD Camera          | 2         | 0.54%   |
| Microsoft LifeCam NX-6000               | 2         | 0.54%   |
| Microdia Integrated Webcam              | 2         | 0.54%   |
| Microdia Dell Integrated HD Webcam      | 2         | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 35        | 47.95%  |
| Validity Sensors           | 20        | 27.4%   |
| Shenzhen Goodix Technology | 8         | 10.96%  |
| Elan Microelectronics      | 4         | 5.48%   |
| STMicroelectronics         | 2         | 2.74%   |
| AuthenTec                  | 2         | 2.74%   |
| Upek                       | 1         | 1.37%   |
| LighTuning Technology      | 1         | 1.37%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 16        | 21.92%  |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 6.85%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 5.48%   |
| Shenzhen Goodix  FingerPrint Device                                        | 4         | 5.48%   |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 5.48%   |
| Elan ELAN:Fingerprint                                                      | 4         | 5.48%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 4.11%   |
| Synaptics WBDI                                                             | 3         | 4.11%   |
| Synaptics UWP WBDI                                                         | 3         | 4.11%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 3         | 4.11%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 4.11%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 2.74%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 2.74%   |
| Synaptics  WBDI                                                            | 2         | 2.74%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 2         | 2.74%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 2.74%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 1.37%   |
| Validity Sensors VFS491                                                    | 1         | 1.37%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 1.37%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 1.37%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 1.37%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 1.37%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 1.37%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.37%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 1.37%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 1.37%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 1.37%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 24        | 63.16%  |
| Alcor Micro | 14        | 36.84%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 14        | 36.84%  |
| Broadcom 58200                                                               | 8         | 21.05%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 7         | 18.42%  |
| Broadcom 5880                                                                | 7         | 18.42%  |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 5.26%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 423       | 67.57%  |
| 1     | 154       | 24.6%   |
| 2     | 38        | 6.07%   |
| 3     | 8         | 1.28%   |
| 7     | 1         | 0.16%   |
| 5     | 1         | 0.16%   |
| 4     | 1         | 0.16%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 72        | 28.02%  |
| Graphics card            | 68        | 26.46%  |
| Net/wireless             | 34        | 13.23%  |
| Chipcard                 | 34        | 13.23%  |
| Communication controller | 11        | 4.28%   |
| Camera                   | 11        | 4.28%   |
| Multimedia controller    | 9         | 3.5%    |
| Unassigned class         | 5         | 1.95%   |
| Card reader              | 3         | 1.17%   |
| Bluetooth                | 3         | 1.17%   |
| Storage                  | 2         | 0.78%   |
| Sound                    | 2         | 0.78%   |
| Net/ethernet             | 2         | 0.78%   |
| Network                  | 1         | 0.39%   |

