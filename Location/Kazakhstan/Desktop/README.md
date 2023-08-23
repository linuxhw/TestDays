Linux in Kazakhstan - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Kazakhstan.

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

Total: 288

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock        | Z68 Pro3 Gen3               | [7d262746c9](https://linux-hardware.org/?probe=7d262746c9) | Jul 30, 2023 |
| ECS           | P43T-A2                     | [a25280247b](https://linux-hardware.org/?probe=a25280247b) | Jul 25, 2023 |
| MSI           | MAG B560 TORPEDO            | [4b611c264e](https://linux-hardware.org/?probe=4b611c264e) | Jul 08, 2023 |
| MSI           | MAG B560 TORPEDO            | [1327fb98ac](https://linux-hardware.org/?probe=1327fb98ac) | Jul 04, 2023 |
| ECS           | P67H2-A3                    | [d23f1fda24](https://linux-hardware.org/?probe=d23f1fda24) | Jul 02, 2023 |
| ECS           | P67H2-A3                    | [f35a6b0a66](https://linux-hardware.org/?probe=f35a6b0a66) | Jun 25, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | [a1b8584d65](https://linux-hardware.org/?probe=a1b8584d65) | May 01, 2023 |
| ASRock        | H110M-DGS R3.0              | [88e7444fa5](https://linux-hardware.org/?probe=88e7444fa5) | Apr 30, 2023 |
| ASRock        | H110M-DGS R3.0              | [763e7fa1b6](https://linux-hardware.org/?probe=763e7fa1b6) | Apr 30, 2023 |
| ASUSTek       | GR6                         | [9cccf46449](https://linux-hardware.org/?probe=9cccf46449) | Apr 15, 2023 |
| Gigabyte      | A320M-H-CF                  | [99f214269f](https://linux-hardware.org/?probe=99f214269f) | Apr 13, 2023 |
| Gigabyte      | A320M-H-CF                  | [c961550658](https://linux-hardware.org/?probe=c961550658) | Apr 13, 2023 |
| Biostar       | H61MLV                      | [db9714357e](https://linux-hardware.org/?probe=db9714357e) | Apr 01, 2023 |
| GoWin Solu... | R86S                        | [495614211e](https://linux-hardware.org/?probe=495614211e) | Mar 09, 2023 |
| Gigabyte      | P35-DS3L                    | [31aeecfcb9](https://linux-hardware.org/?probe=31aeecfcb9) | Mar 06, 2023 |
| Intel         | H61                         | [7bc298c53d](https://linux-hardware.org/?probe=7bc298c53d) | Mar 02, 2023 |
| HP            | 1497                        | [bd24913452](https://linux-hardware.org/?probe=bd24913452) | Feb 24, 2023 |
| Gigabyte      | B450M S2H                   | [20bcead0e8](https://linux-hardware.org/?probe=20bcead0e8) | Feb 11, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | [96847498e3](https://linux-hardware.org/?probe=96847498e3) | Feb 02, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | [21ce876854](https://linux-hardware.org/?probe=21ce876854) | Feb 01, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | [de7f0840d1](https://linux-hardware.org/?probe=de7f0840d1) | Feb 01, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | [f2636de53b](https://linux-hardware.org/?probe=f2636de53b) | Jan 31, 2023 |
| Dell          | 03KWTV A02                  | [8512c1d0cc](https://linux-hardware.org/?probe=8512c1d0cc) | Jan 31, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | [6bf8eb9c73](https://linux-hardware.org/?probe=6bf8eb9c73) | Jan 30, 2023 |
| Gigabyte      | GA-73PVM-S2                 | [fcf91f09b4](https://linux-hardware.org/?probe=fcf91f09b4) | Jan 28, 2023 |
| ECS           | G41T-M7                     | [e6be57e3c3](https://linux-hardware.org/?probe=e6be57e3c3) | Jan 20, 2023 |
| ECS           | G41T-M7                     | [51a45a431a](https://linux-hardware.org/?probe=51a45a431a) | Jan 16, 2023 |
| ASRock        | Z68 Pro3 Gen3               | [242329daf8](https://linux-hardware.org/?probe=242329daf8) | Jan 15, 2023 |
| Gigabyte      | B460M DS3H                  | [8a381fe525](https://linux-hardware.org/?probe=8a381fe525) | Dec 14, 2022 |
| Gigabyte      | B460M DS3H                  | [90b4e5f1b2](https://linux-hardware.org/?probe=90b4e5f1b2) | Dec 14, 2022 |
| Gigabyte      | H370M DS3H-CF               | [8c1901e5d6](https://linux-hardware.org/?probe=8c1901e5d6) | Dec 11, 2022 |
| ASRock        | B450M Pro4                  | [36ef5b0deb](https://linux-hardware.org/?probe=36ef5b0deb) | Dec 04, 2022 |
| ASRock        | N68-S3 UCC                  | [1d20e4ba6d](https://linux-hardware.org/?probe=1d20e4ba6d) | Nov 30, 2022 |
| ASUSTek       | PRIME X570-PRO              | [c218724cb4](https://linux-hardware.org/?probe=c218724cb4) | Nov 27, 2022 |
| MSI           | Z77MA-G45                   | [feb165c344](https://linux-hardware.org/?probe=feb165c344) | Nov 27, 2022 |
| ASUSTek       | Z97M-PLUS                   | [7ad1a412ae](https://linux-hardware.org/?probe=7ad1a412ae) | Nov 20, 2022 |
| ASUSTek       | Z97M-PLUS                   | [be2b867450](https://linux-hardware.org/?probe=be2b867450) | Nov 20, 2022 |
| ASUSTek       | H81M-K                      | [d7ae86ad73](https://linux-hardware.org/?probe=d7ae86ad73) | Nov 13, 2022 |
| Foxconn       | H77M/H77M-S                 | [bebf7f53f8](https://linux-hardware.org/?probe=bebf7f53f8) | Nov 12, 2022 |
| ASUSTek       | P8B75-M LE                  | [65ac5d12c7](https://linux-hardware.org/?probe=65ac5d12c7) | Nov 06, 2022 |
| ASUSTek       | P8B75-M LE                  | [3ffeb18e56](https://linux-hardware.org/?probe=3ffeb18e56) | Nov 06, 2022 |
| ASRock        | B85M Pro4                   | [55da31d807](https://linux-hardware.org/?probe=55da31d807) | Nov 04, 2022 |
| ASUSTek       | H61M-K                      | [f6d2b67f4a](https://linux-hardware.org/?probe=f6d2b67f4a) | Oct 10, 2022 |
| Gigabyte      | A320M-H-CF                  | [a3e30957c7](https://linux-hardware.org/?probe=a3e30957c7) | Sep 19, 2022 |
| ASRock        | Z68 Pro3 Gen3               | [186a63fa9e](https://linux-hardware.org/?probe=186a63fa9e) | Aug 27, 2022 |
| MSI           | H81M-P33                    | [d47bac5d9d](https://linux-hardware.org/?probe=d47bac5d9d) | Jul 26, 2022 |
| Foxconn       | 2ABF                        | [46876a159f](https://linux-hardware.org/?probe=46876a159f) | Jul 26, 2022 |
| Gigabyte      | Z68P-DS3                    | [b03f1fee53](https://linux-hardware.org/?probe=b03f1fee53) | Jul 24, 2022 |
| Gigabyte      | G31M-ES2L                   | [3e417753cb](https://linux-hardware.org/?probe=3e417753cb) | Jul 16, 2022 |
| Gigabyte      | G31M-ES2L                   | [24b5ba412b](https://linux-hardware.org/?probe=24b5ba412b) | Jul 16, 2022 |
| Gigabyte      | P35-DS3L                    | [67182580cc](https://linux-hardware.org/?probe=67182580cc) | Jul 10, 2022 |
| ASRock        | H310CM-HDV                  | [4e6539bf57](https://linux-hardware.org/?probe=4e6539bf57) | Jul 01, 2022 |
| ASRock        | H110M-HDV R3.0              | [6b7dd54165](https://linux-hardware.org/?probe=6b7dd54165) | Jun 13, 2022 |
| Gigabyte      | Z68P-DS3                    | [03554389d5](https://linux-hardware.org/?probe=03554389d5) | Jun 11, 2022 |
| MSI           | G41M-SP20                   | [214a83fb6b](https://linux-hardware.org/?probe=214a83fb6b) | Jun 04, 2022 |
| Foxconn       | H77M/H77M-S                 | [eb5f9f873a](https://linux-hardware.org/?probe=eb5f9f873a) | Jun 03, 2022 |
| ASUSTek       | H110M-K                     | [58566ab4b6](https://linux-hardware.org/?probe=58566ab4b6) | May 30, 2022 |
| ASRock        | H110M-HDV R3.0              | [2540080e55](https://linux-hardware.org/?probe=2540080e55) | May 28, 2022 |
| ASUSTek       | H110M-K                     | [9c2c8025ed](https://linux-hardware.org/?probe=9c2c8025ed) | May 26, 2022 |
| ASUSTek       | H110M-K                     | [d0d6870830](https://linux-hardware.org/?probe=d0d6870830) | May 23, 2022 |
| ASUSTek       | PRIME B450M-K II            | [f115d870eb](https://linux-hardware.org/?probe=f115d870eb) | May 07, 2022 |
| Gigabyte      | Z390 UD                     | [f7290e5680](https://linux-hardware.org/?probe=f7290e5680) | Apr 25, 2022 |
| Gigabyte      | H61M-S1                     | [0ca4241f02](https://linux-hardware.org/?probe=0ca4241f02) | Apr 23, 2022 |
| Gigabyte      | Z390 UD                     | [5f4832051e](https://linux-hardware.org/?probe=5f4832051e) | Apr 14, 2022 |
| ASRock        | B250 Pro4                   | [cb77fb75b5](https://linux-hardware.org/?probe=cb77fb75b5) | Apr 14, 2022 |
| Gigabyte      | Z390 UD                     | [ef0b36db62](https://linux-hardware.org/?probe=ef0b36db62) | Apr 11, 2022 |
| MSI           | MS-7365                     | [8948dea4de](https://linux-hardware.org/?probe=8948dea4de) | Apr 07, 2022 |
| Unknown       | X79-P3                      | [40e38e9a8d](https://linux-hardware.org/?probe=40e38e9a8d) | Apr 07, 2022 |
| HP            | 0A08h                       | [4df5b0832f](https://linux-hardware.org/?probe=4df5b0832f) | Apr 06, 2022 |
| ASRock        | H61M-VS                     | [609849a9e7](https://linux-hardware.org/?probe=609849a9e7) | Apr 02, 2022 |
| MSI           | MS-7346                     | [207eda5f34](https://linux-hardware.org/?probe=207eda5f34) | Mar 30, 2022 |
| ASUSTek       | PRIME B450M-K II            | [27b65f8212](https://linux-hardware.org/?probe=27b65f8212) | Mar 23, 2022 |
| ASRock        | 890GX Extreme4              | [3c57e1ac31](https://linux-hardware.org/?probe=3c57e1ac31) | Mar 20, 2022 |
| ASRock        | 890GX Extreme4              | [8c38c582bf](https://linux-hardware.org/?probe=8c38c582bf) | Mar 20, 2022 |
| ASUSTek       | PRIME B450M-K II            | [406c69d7cd](https://linux-hardware.org/?probe=406c69d7cd) | Mar 18, 2022 |
| MSI           | MS-7346                     | [2c94f0863d](https://linux-hardware.org/?probe=2c94f0863d) | Mar 16, 2022 |
| Dell          | 0V6XGW A01                  | [7b091c2035](https://linux-hardware.org/?probe=7b091c2035) | Mar 13, 2022 |
| MSI           | MS-7346                     | [0be963d491](https://linux-hardware.org/?probe=0be963d491) | Mar 13, 2022 |
| ASUSTek       | P5Q                         | [59a21d0aa2](https://linux-hardware.org/?probe=59a21d0aa2) | Mar 11, 2022 |
| MSI           | MS-7346                     | [369821f3f9](https://linux-hardware.org/?probe=369821f3f9) | Feb 26, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [38d5887ae2](https://linux-hardware.org/?probe=38d5887ae2) | Feb 19, 2022 |
| ECS           | G41T-R3                     | [ad4ba21957](https://linux-hardware.org/?probe=ad4ba21957) | Feb 13, 2022 |
| Biostar       | H61MLV                      | [675b0c3faf](https://linux-hardware.org/?probe=675b0c3faf) | Feb 07, 2022 |
| ASUSTek       | P8H77-V LE                  | [cd91d445e6](https://linux-hardware.org/?probe=cd91d445e6) | Jan 30, 2022 |
| ASUSTek       | P8H77-V LE                  | [c1703ee8ee](https://linux-hardware.org/?probe=c1703ee8ee) | Jan 30, 2022 |
| ASRock        | G31M-VS                     | [d456869dd7](https://linux-hardware.org/?probe=d456869dd7) | Jan 14, 2022 |
| Acer          | Predator PO3-620            | [d33f608e2e](https://linux-hardware.org/?probe=d33f608e2e) | Dec 27, 2021 |
| eMachines     | ET1850                      | [cffccff919](https://linux-hardware.org/?probe=cffccff919) | Dec 20, 2021 |
| Gigabyte      | H370M DS3H-CF               | [c69f79e654](https://linux-hardware.org/?probe=c69f79e654) | Nov 17, 2021 |
| Gigabyte      | B460M DS3H V2               | [83857e3215](https://linux-hardware.org/?probe=83857e3215) | Oct 29, 2021 |
| Biostar       | H61MLV2                     | [118f61b356](https://linux-hardware.org/?probe=118f61b356) | Oct 23, 2021 |
| Gigabyte      | H370M DS3H-CF               | [1c2a383c4f](https://linux-hardware.org/?probe=1c2a383c4f) | Oct 20, 2021 |
| Gigabyte      | EP45-DS3L                   | [e7abad8af5](https://linux-hardware.org/?probe=e7abad8af5) | Oct 20, 2021 |
| Athermiter... | X99 Beta vk.com/@2485616    | [6006da0a12](https://linux-hardware.org/?probe=6006da0a12) | Oct 01, 2021 |
| ASRock        | G31M-VS                     | [79a5ef3dad](https://linux-hardware.org/?probe=79a5ef3dad) | Sep 22, 2021 |
| ASRock        | G31M-VS                     | [ea71d93f96](https://linux-hardware.org/?probe=ea71d93f96) | Aug 26, 2021 |
| Unknown       | Unknown                     | [d35224de9f](https://linux-hardware.org/?probe=d35224de9f) | Aug 07, 2021 |
| ASUSTek       | H61M-E                      | [d312398917](https://linux-hardware.org/?probe=d312398917) | Jul 29, 2021 |
| ASUSTek       | P8B75-M LE                  | [ad17a21f6e](https://linux-hardware.org/?probe=ad17a21f6e) | Jun 16, 2021 |
| Biostar       | H81MHV3                     | [0a593d3966](https://linux-hardware.org/?probe=0a593d3966) | Jun 01, 2021 |
| ASUSTek       | PRIME B450M-K II            | [1b292e7e77](https://linux-hardware.org/?probe=1b292e7e77) | May 21, 2021 |
| Intel         | DB65AL AAG12530-306         | [8cf2183901](https://linux-hardware.org/?probe=8cf2183901) | May 03, 2021 |
| MSI           | P55-GD65                    | [773fc40103](https://linux-hardware.org/?probe=773fc40103) | Apr 24, 2021 |
| ASUSTek       | TUF Z270 MARK 1             | [003b473b29](https://linux-hardware.org/?probe=003b473b29) | Mar 17, 2021 |
| ASUSTek       | PRIME B250-PRO              | [c62af0239b](https://linux-hardware.org/?probe=c62af0239b) | Mar 17, 2021 |
| Intel         | DG965RY AAD41691-301        | [d08f840a09](https://linux-hardware.org/?probe=d08f840a09) | Mar 07, 2021 |
| Gigabyte      | B450M S2H                   | [676848c0ea](https://linux-hardware.org/?probe=676848c0ea) | Mar 01, 2021 |
| Gigabyte      | G41MT-S2PT                  | [7b39e6bd46](https://linux-hardware.org/?probe=7b39e6bd46) | Feb 15, 2021 |
| ASUSTek       | PRIME A320M-K               | [19b6410050](https://linux-hardware.org/?probe=19b6410050) | Feb 12, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | [5a8bae0bc9](https://linux-hardware.org/?probe=5a8bae0bc9) | Jan 17, 2021 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [80552a83cd](https://linux-hardware.org/?probe=80552a83cd) | Jan 11, 2021 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [e99dbcff3b](https://linux-hardware.org/?probe=e99dbcff3b) | Jan 11, 2021 |
| ASRock        | H110M-DVS R3.0              | [07ee20e1ca](https://linux-hardware.org/?probe=07ee20e1ca) | Jan 02, 2021 |
| ASUSTek       | M5A99X EVO R2.0             | [a673d3a8c7](https://linux-hardware.org/?probe=a673d3a8c7) | Dec 23, 2020 |
| eMachines     | ET1850                      | [c50ea84e0d](https://linux-hardware.org/?probe=c50ea84e0d) | Dec 18, 2020 |
| ASRock        | N68-S                       | [3533e8dac5](https://linux-hardware.org/?probe=3533e8dac5) | Dec 16, 2020 |
| Gigabyte      | Z87M-HD3                    | [42b04fe8bb](https://linux-hardware.org/?probe=42b04fe8bb) | Dec 06, 2020 |
| ASUSTek       | P5P43TD PRO                 | [874d67029b](https://linux-hardware.org/?probe=874d67029b) | Dec 02, 2020 |
| MSI           | X58 Pro-E                   | [d85b89db2e](https://linux-hardware.org/?probe=d85b89db2e) | Nov 11, 2020 |
| MSI           | MS-7346                     | [b297f8721b](https://linux-hardware.org/?probe=b297f8721b) | Oct 31, 2020 |
| ASUSTek       | P5P43TD PRO                 | [2c2ff12670](https://linux-hardware.org/?probe=2c2ff12670) | Oct 31, 2020 |
| ASRock        | B450 Gaming K4              | [42aa2abab3](https://linux-hardware.org/?probe=42aa2abab3) | Oct 26, 2020 |
| ASRock        | H61iCafe                    | [a44ad4ab39](https://linux-hardware.org/?probe=a44ad4ab39) | Oct 08, 2020 |
| Gigabyte      | P55A-UD3R                   | [be3a1d8c92](https://linux-hardware.org/?probe=be3a1d8c92) | Oct 05, 2020 |
| ASUSTek       | PRIME Z370-A                | [1ad6b7a819](https://linux-hardware.org/?probe=1ad6b7a819) | Oct 01, 2020 |
| Gigabyte      | Z370 HD3P-CF                | [5c317250db](https://linux-hardware.org/?probe=5c317250db) | Sep 27, 2020 |
| Biostar       | G41-M7                      | [a50a75af2a](https://linux-hardware.org/?probe=a50a75af2a) | Aug 11, 2020 |
| Intel         | DB65AL AAG12530-306         | [03daa1b244](https://linux-hardware.org/?probe=03daa1b244) | Jul 09, 2020 |
| Intel         | DB65AL AAG12530-306         | [c64ad86725](https://linux-hardware.org/?probe=c64ad86725) | Jul 07, 2020 |
| Intel         | DB65AL AAG12530-306         | [c2c3f83b11](https://linux-hardware.org/?probe=c2c3f83b11) | Jul 07, 2020 |
| ASUSTek       | H61M-K                      | [955b5a5e27](https://linux-hardware.org/?probe=955b5a5e27) | Jun 08, 2020 |
| Intel         | DH61WW AAG23116-204         | [c0fc07b2e3](https://linux-hardware.org/?probe=c0fc07b2e3) | May 27, 2020 |
| Intel         | DH61WW AAG23116-204         | [a34ec38bca](https://linux-hardware.org/?probe=a34ec38bca) | May 22, 2020 |
| ASRock        | Q1900M                      | [5998519fca](https://linux-hardware.org/?probe=5998519fca) | May 18, 2020 |
| Gigabyte      | EP43-S3L                    | [ce53a132ad](https://linux-hardware.org/?probe=ce53a132ad) | Apr 22, 2020 |
| ASUSTek       | PRIME B250-PRO              | [8dddac7046](https://linux-hardware.org/?probe=8dddac7046) | Mar 25, 2020 |
| Intel         | DB65AL AAG12530-306         | [37eadd87d7](https://linux-hardware.org/?probe=37eadd87d7) | Mar 24, 2020 |
| ASRock        | H61M-VG3                    | [13be5c5114](https://linux-hardware.org/?probe=13be5c5114) | Mar 14, 2020 |
| Foxconn       | G31MXP/G31MXP-K FAB:1.0     | [bdd6336c5c](https://linux-hardware.org/?probe=bdd6336c5c) | Feb 10, 2020 |
| ASUSTek       | H81-GAMER                   | [d8091352aa](https://linux-hardware.org/?probe=d8091352aa) | Feb 09, 2020 |
| Biostar       | B75MU3B                     | [78def272e2](https://linux-hardware.org/?probe=78def272e2) | Feb 06, 2020 |
| Biostar       | B75MU3B                     | [41f7bff636](https://linux-hardware.org/?probe=41f7bff636) | Feb 04, 2020 |
| Biostar       | B75MU3B                     | [9f8d0c9af4](https://linux-hardware.org/?probe=9f8d0c9af4) | Feb 04, 2020 |
| Gigabyte      | B360M D3H-CF                | [4d8aed3739](https://linux-hardware.org/?probe=4d8aed3739) | Jan 31, 2020 |
| Gigabyte      | H61M-DS2 DVI                | [016eb3ca52](https://linux-hardware.org/?probe=016eb3ca52) | Jan 22, 2020 |
| OEM           | Unknown                     | [0df2000649](https://linux-hardware.org/?probe=0df2000649) | Jan 12, 2020 |
| Intel         | DH55PJ AAE93812-302         | [a57dcf32aa](https://linux-hardware.org/?probe=a57dcf32aa) | Dec 20, 2019 |
| ASRock        | Q1900M                      | [5eb2001292](https://linux-hardware.org/?probe=5eb2001292) | Dec 20, 2019 |
| ASRock        | Q1900M                      | [aa067c312b](https://linux-hardware.org/?probe=aa067c312b) | Dec 08, 2019 |
| ASRock        | Q1900M                      | [d0137a63e9](https://linux-hardware.org/?probe=d0137a63e9) | Dec 08, 2019 |
| MSI           | B75A-G43                    | [6dd3e491f5](https://linux-hardware.org/?probe=6dd3e491f5) | Dec 04, 2019 |
| Gigabyte      | Z68P-DS3                    | [8444d1b8a5](https://linux-hardware.org/?probe=8444d1b8a5) | Dec 02, 2019 |
| ASUSTek       | PRIME Z390M-PLUS            | [c8c1a01026](https://linux-hardware.org/?probe=c8c1a01026) | Sep 04, 2019 |
| ASUSTek       | P8Z77-M                     | [988203ee61](https://linux-hardware.org/?probe=988203ee61) | Aug 31, 2019 |
| EPoX Compu... | nForce4 DDR: 8NPA7I / 8N... | [3912cd3c3a](https://linux-hardware.org/?probe=3912cd3c3a) | Aug 15, 2019 |
| Dell          | 0GDG8Y A00                  | [201fe8de92](https://linux-hardware.org/?probe=201fe8de92) | Aug 10, 2019 |
| MSI           | X470 GAMING PRO             | [01eb97a943](https://linux-hardware.org/?probe=01eb97a943) | Jul 26, 2019 |
| MSI           | X470 GAMING PRO             | [868720add8](https://linux-hardware.org/?probe=868720add8) | Jul 26, 2019 |
| Gigabyte      | P35-DS3L                    | [54231260ff](https://linux-hardware.org/?probe=54231260ff) | Jul 26, 2019 |
| Gigabyte      | P35-DS3L                    | [6db0f0b43c](https://linux-hardware.org/?probe=6db0f0b43c) | Jul 26, 2019 |
| MSI           | G31M3-F V2                  | [3f04b83dfd](https://linux-hardware.org/?probe=3f04b83dfd) | Jun 25, 2019 |
| MSI           | G31M3-F V2                  | [70820eed2b](https://linux-hardware.org/?probe=70820eed2b) | Jun 23, 2019 |
| HP            | 09F0h                       | [59817a0992](https://linux-hardware.org/?probe=59817a0992) | Jun 09, 2019 |
| ASUSTek       | H97-PLUS                    | [f72a33f2be](https://linux-hardware.org/?probe=f72a33f2be) | May 17, 2019 |
| Gigabyte      | H77-DS3H                    | [5cecb224c0](https://linux-hardware.org/?probe=5cecb224c0) | May 13, 2019 |
| MSI           | MS-7346                     | [f9012833e0](https://linux-hardware.org/?probe=f9012833e0) | May 05, 2019 |
| Gigabyte      | H110-D3-CF                  | [e3e358c6c5](https://linux-hardware.org/?probe=e3e358c6c5) | May 02, 2019 |
| Gigabyte      | H110-D3-CF                  | [0f667174d7](https://linux-hardware.org/?probe=0f667174d7) | May 02, 2019 |
| ASUSTek       | P5B-VM SE                   | [5ac945fc44](https://linux-hardware.org/?probe=5ac945fc44) | Apr 24, 2019 |
| Biostar       | B75MU3B                     | [263bae9f6d](https://linux-hardware.org/?probe=263bae9f6d) | Apr 21, 2019 |
| ASUSTek       | P8B75-M LX                  | [0fc0eb1dfe](https://linux-hardware.org/?probe=0fc0eb1dfe) | Apr 14, 2019 |
| ASUSTek       | P8B75-M LX                  | [a8c17634fa](https://linux-hardware.org/?probe=a8c17634fa) | Apr 13, 2019 |
| Biostar       | H81MLC                      | [21b0c1af4d](https://linux-hardware.org/?probe=21b0c1af4d) | Mar 26, 2019 |
| Gigabyte      | H61M-S1                     | [1471f5c744](https://linux-hardware.org/?probe=1471f5c744) | Mar 26, 2019 |
| Gigabyte      | G1.Sniper 3                 | [700fc16ac3](https://linux-hardware.org/?probe=700fc16ac3) | Mar 23, 2019 |
| Gigabyte      | G1.Sniper 3                 | [98718d3ebc](https://linux-hardware.org/?probe=98718d3ebc) | Mar 20, 2019 |
| Gigabyte      | G1.Sniper 3                 | [7302d607c3](https://linux-hardware.org/?probe=7302d607c3) | Mar 19, 2019 |
| ASRock        | B85 Pro4                    | [8c2f28bdd7](https://linux-hardware.org/?probe=8c2f28bdd7) | Mar 14, 2019 |
| ASRock        | B85 Pro4                    | [9cf5db3af5](https://linux-hardware.org/?probe=9cf5db3af5) | Mar 11, 2019 |
| ASRock        | B85 Pro4                    | [6193a4e4db](https://linux-hardware.org/?probe=6193a4e4db) | Mar 02, 2019 |
| Intel         | DG965RY AAD41691-205        | [9e17250cd3](https://linux-hardware.org/?probe=9e17250cd3) | Feb 25, 2019 |
| ASUSTek       | H170 PRO GAMING             | [7de51a6093](https://linux-hardware.org/?probe=7de51a6093) | Feb 18, 2019 |
| HP            | 21D0                        | [e12ecb452a](https://linux-hardware.org/?probe=e12ecb452a) | Feb 15, 2019 |
| ECS           | P4M800PRO-M                 | [9b79e448af](https://linux-hardware.org/?probe=9b79e448af) | Feb 10, 2019 |
| eMachines     | ET1850                      | [49d2d34eb5](https://linux-hardware.org/?probe=49d2d34eb5) | Feb 09, 2019 |
| ECS           | P4M800PRO-M                 | [4fa72ec332](https://linux-hardware.org/?probe=4fa72ec332) | Jan 22, 2019 |
| ASRock        | B75M R2.0                   | [6e1297e003](https://linux-hardware.org/?probe=6e1297e003) | Dec 19, 2018 |
| ASRock        | B75M-DGS R2.0               | [b54d9c9c47](https://linux-hardware.org/?probe=b54d9c9c47) | Dec 19, 2018 |
| Biostar       | B75MU3B                     | [aebd92ed4e](https://linux-hardware.org/?probe=aebd92ed4e) | Dec 18, 2018 |
| Biostar       | B75MU3B                     | [76612a774a](https://linux-hardware.org/?probe=76612a774a) | Dec 16, 2018 |
| Biostar       | P4M89-M7A Ver:1.0           | [cfcedc1f4f](https://linux-hardware.org/?probe=cfcedc1f4f) | Dec 15, 2018 |
| MSI           | H61M-P20                    | [805bef206c](https://linux-hardware.org/?probe=805bef206c) | Dec 06, 2018 |
| ASUSTek       | P8H61-M LX3 R2.0            | [17cd747f59](https://linux-hardware.org/?probe=17cd747f59) | Nov 27, 2018 |
| Gigabyte      | Z68P-DS3                    | [d6841f0c9f](https://linux-hardware.org/?probe=d6841f0c9f) | Oct 24, 2018 |
| Gigabyte      | EP45-DS3L                   | [120f3b30db](https://linux-hardware.org/?probe=120f3b30db) | Oct 13, 2018 |
| Gigabyte      | EX58-UD3R                   | [ad2e1e8a9c](https://linux-hardware.org/?probe=ad2e1e8a9c) | Oct 12, 2018 |
| Gigabyte      | H97-HD3                     | [57811990c6](https://linux-hardware.org/?probe=57811990c6) | Oct 09, 2018 |
| ECS           | G31T-M7                     | [9524260856](https://linux-hardware.org/?probe=9524260856) | Sep 11, 2018 |
| ASUSTek       | P5K-E                       | [2bf1f5cd4d](https://linux-hardware.org/?probe=2bf1f5cd4d) | Sep 02, 2018 |
| Foxconn       | 45CMX/45GMX/45CMX-K         | [91a4bc2623](https://linux-hardware.org/?probe=91a4bc2623) | Jul 23, 2018 |
| Lenovo        | ThinkCentre M58p 6138A89    | [5dabc0431a](https://linux-hardware.org/?probe=5dabc0431a) | Jul 08, 2018 |
| Lenovo        | ThinkCentre M58p 6138A89    | [b40472e4ff](https://linux-hardware.org/?probe=b40472e4ff) | Jul 08, 2018 |
| AMI           | Cherry Trail CR             | [f8d107c1d6](https://linux-hardware.org/?probe=f8d107c1d6) | Jul 05, 2018 |
| ASRock        | G31M-GS                     | [e7ad4e06b0](https://linux-hardware.org/?probe=e7ad4e06b0) | May 21, 2018 |
| Gigabyte      | H97-HD3                     | [bc90c9abeb](https://linux-hardware.org/?probe=bc90c9abeb) | May 19, 2018 |
| ASRock        | G31M-GS                     | [33e42cb4a1](https://linux-hardware.org/?probe=33e42cb4a1) | May 17, 2018 |
| ASUSTek       | P5K SE                      | [758aa13be2](https://linux-hardware.org/?probe=758aa13be2) | May 15, 2018 |
| Gigabyte      | H110M-S2V-CF                | [258a87c77e](https://linux-hardware.org/?probe=258a87c77e) | Apr 18, 2018 |
| Colorful T... | C.G31T Ver2.3               | [fa66706236](https://linux-hardware.org/?probe=fa66706236) | Apr 05, 2018 |
| MSI           | D2415 S26361-D2415-A21      | [4252f362f3](https://linux-hardware.org/?probe=4252f362f3) | Apr 04, 2018 |
| MSI           | D2415 S26361-D2415-A21      | [5b42126fde](https://linux-hardware.org/?probe=5b42126fde) | Apr 04, 2018 |
| MSI           | D2415 S26361-D2415-A21      | [12aefd0226](https://linux-hardware.org/?probe=12aefd0226) | Mar 08, 2018 |
| ECS           | H61H2-M12                   | [9245ae30a0](https://linux-hardware.org/?probe=9245ae30a0) | Mar 05, 2018 |
| Gigabyte      | Z68XP-UD5                   | [5fed078696](https://linux-hardware.org/?probe=5fed078696) | Mar 02, 2018 |
| Gigabyte      | Z68XP-UD5                   | [a5edee18e6](https://linux-hardware.org/?probe=a5edee18e6) | Mar 02, 2018 |
| Gigabyte      | 965G-DS3                    | [a18c3642c1](https://linux-hardware.org/?probe=a18c3642c1) | Feb 27, 2018 |
| Intel         | DP45SG AAE27733-407         | [a12c16610a](https://linux-hardware.org/?probe=a12c16610a) | Feb 21, 2018 |
| Intel         | DP45SG AAE27733-407         | [01f1eb1b43](https://linux-hardware.org/?probe=01f1eb1b43) | Feb 21, 2018 |
| Gigabyte      | P35-DS3L                    | [b53697cdde](https://linux-hardware.org/?probe=b53697cdde) | Feb 17, 2018 |
| Foxconn       | G31MXP FAB:1.1              | [7e932c8df9](https://linux-hardware.org/?probe=7e932c8df9) | Feb 14, 2018 |
| Gigabyte      | EG45M-DS2H                  | [5765dec2f5](https://linux-hardware.org/?probe=5765dec2f5) | Feb 07, 2018 |
| ASRock        | N68-S                       | [938b758f5d](https://linux-hardware.org/?probe=938b758f5d) | Feb 05, 2018 |
| ECS           | H61H2-M12                   | [ccb76d8296](https://linux-hardware.org/?probe=ccb76d8296) | Feb 04, 2018 |
| ASRock        | N68-S                       | [64632c3151](https://linux-hardware.org/?probe=64632c3151) | Feb 03, 2018 |
| ASRock        | G31M-GS                     | [8b178b91b5](https://linux-hardware.org/?probe=8b178b91b5) | Jan 16, 2018 |
| ASRock        | B150M Pro4S/D3              | [3d61c8f1b1](https://linux-hardware.org/?probe=3d61c8f1b1) | Jan 16, 2018 |
| Gigabyte      | P55-US3L                    | [31d2b07ed0](https://linux-hardware.org/?probe=31d2b07ed0) | Jan 09, 2018 |
| Gigabyte      | P55-US3L                    | [557edddbbb](https://linux-hardware.org/?probe=557edddbbb) | Jan 09, 2018 |
| ECS           | G31T-M7                     | [a3440d0458](https://linux-hardware.org/?probe=a3440d0458) | Jan 09, 2018 |
| Fujitsu Si... | D2750-A1 S26361-D2750-A1    | [e3d1272ce6](https://linux-hardware.org/?probe=e3d1272ce6) | Jan 08, 2018 |
| Lenovo        | IdeaCentre B320             | [f744394a1c](https://linux-hardware.org/?probe=f744394a1c) | Dec 29, 2017 |
| ASUSTek       | Crosshair III Formula       | [dc9bba3d36](https://linux-hardware.org/?probe=dc9bba3d36) | Dec 23, 2017 |
| MSI           | H61M-P20                    | [98d085f592](https://linux-hardware.org/?probe=98d085f592) | Dec 17, 2017 |
| Biostar       | G31-M7 TE                   | [6b7be109df](https://linux-hardware.org/?probe=6b7be109df) | Dec 10, 2017 |
| Biostar       | G31-M7 TE                   | [ff359217e3](https://linux-hardware.org/?probe=ff359217e3) | Dec 10, 2017 |
| MSI           | H61M-P20                    | [b9e07ffbc6](https://linux-hardware.org/?probe=b9e07ffbc6) | Dec 07, 2017 |
| ECS           | G31T-M7                     | [ab2cc3b591](https://linux-hardware.org/?probe=ab2cc3b591) | Dec 05, 2017 |
| MSI           | H61M-P20                    | [c8f3683dd7](https://linux-hardware.org/?probe=c8f3683dd7) | Dec 03, 2017 |
| ASUSTek       | H170 PRO GAMING             | [2930095950](https://linux-hardware.org/?probe=2930095950) | Nov 26, 2017 |
| MSI           | G41M4                       | [5b263ddccb](https://linux-hardware.org/?probe=5b263ddccb) | Oct 26, 2017 |
| MSI           | MS-7360                     | [74b442872c](https://linux-hardware.org/?probe=74b442872c) | Oct 14, 2017 |
| MSI           | MS-7360                     | [e3fea5c9f7](https://linux-hardware.org/?probe=e3fea5c9f7) | Oct 13, 2017 |
| ASRock        | G31M-S                      | [d686d9a6b4](https://linux-hardware.org/?probe=d686d9a6b4) | Oct 09, 2017 |
| ASRock        | G31M-S                      | [a6c7d89da8](https://linux-hardware.org/?probe=a6c7d89da8) | Oct 09, 2017 |
| ECS           | P33T-A                      | [b333446a6e](https://linux-hardware.org/?probe=b333446a6e) | Oct 07, 2017 |
| ASUSTek       | P8H61-M LX2                 | [3bf184ba53](https://linux-hardware.org/?probe=3bf184ba53) | Oct 01, 2017 |
| ECS           | P33T-A                      | [370e48dea3](https://linux-hardware.org/?probe=370e48dea3) | Sep 02, 2017 |
| MSI           | P45-C51                     | [3c7abe4dbb](https://linux-hardware.org/?probe=3c7abe4dbb) | Sep 01, 2017 |
| Unknown       | Unknown                     | [5593f71ea9](https://linux-hardware.org/?probe=5593f71ea9) | Aug 31, 2017 |
| MSI           | P45-C51                     | [3605717bc8](https://linux-hardware.org/?probe=3605717bc8) | Aug 24, 2017 |
| Gigabyte      | G41MT-S2                    | [60027a3248](https://linux-hardware.org/?probe=60027a3248) | Aug 24, 2017 |
| Unknown       | Unknown                     | [729dbae58e](https://linux-hardware.org/?probe=729dbae58e) | Aug 18, 2017 |
| MSI           | P45-C51                     | [f19a281f67](https://linux-hardware.org/?probe=f19a281f67) | Aug 17, 2017 |
| Gigabyte      | P55-UD3L                    | [b3c7478840](https://linux-hardware.org/?probe=b3c7478840) | Aug 17, 2017 |
| Gigabyte      | G41M-Combo                  | [46eadd3692](https://linux-hardware.org/?probe=46eadd3692) | Aug 14, 2017 |
| MSI           | P45-C51                     | [55eb7a334a](https://linux-hardware.org/?probe=55eb7a334a) | Jul 26, 2017 |
| Gigabyte      | EP45-DS3L                   | [bdc06eff0a](https://linux-hardware.org/?probe=bdc06eff0a) | Jul 18, 2017 |
| MSI           | G41M4                       | [42ac99dafe](https://linux-hardware.org/?probe=42ac99dafe) | Jul 12, 2017 |
| MSI           | G41M4                       | [95c6901677](https://linux-hardware.org/?probe=95c6901677) | Jul 12, 2017 |
| Foxconn       | G41MX/G41MX-K 2.0 1.0       | [bf8c80ba08](https://linux-hardware.org/?probe=bf8c80ba08) | Jul 09, 2017 |
| ASUSTek       | H81M-R                      | [1ab9b8b9b0](https://linux-hardware.org/?probe=1ab9b8b9b0) | Jul 01, 2017 |
| ECS           | H61H2-MV                    | [5e3381ae2b](https://linux-hardware.org/?probe=5e3381ae2b) | Jul 01, 2017 |
| Foxconn       | G43M01                      | [5baa8deeea](https://linux-hardware.org/?probe=5baa8deeea) | Jun 17, 2017 |
| Gigabyte      | P31-S3G                     | [7db5b169da](https://linux-hardware.org/?probe=7db5b169da) | Jun 12, 2017 |
| ECS           | P33T-A                      | [a226d451b0](https://linux-hardware.org/?probe=a226d451b0) | May 29, 2017 |
| ECS           | P33T-A                      | [17dbb18609](https://linux-hardware.org/?probe=17dbb18609) | May 26, 2017 |
| Gigabyte      | P35-DS3L                    | [ed899cd88b](https://linux-hardware.org/?probe=ed899cd88b) | May 25, 2017 |
| Foxconn       | G31MXP FAB:1.1              | [06e5d46798](https://linux-hardware.org/?probe=06e5d46798) | May 21, 2017 |
| Gigabyte      | EP35-DS3L                   | [fdbccdc938](https://linux-hardware.org/?probe=fdbccdc938) | May 13, 2017 |
| Intel         | DN2820FYK H24582-201        | [ff2477ab47](https://linux-hardware.org/?probe=ff2477ab47) | May 11, 2017 |
| Gigabyte      | M57SLI-S4                   | [43e1a4811a](https://linux-hardware.org/?probe=43e1a4811a) | May 01, 2017 |
| ASUSTek       | M4N98TD EVO                 | [97b83f48df](https://linux-hardware.org/?probe=97b83f48df) | Apr 26, 2017 |
| ASRock        | G31M-VS                     | [a3dd026e80](https://linux-hardware.org/?probe=a3dd026e80) | Apr 18, 2017 |
| ASUSTek       | M2N4-SLI                    | [1699021b8f](https://linux-hardware.org/?probe=1699021b8f) | Mar 31, 2017 |
| ASUSTek       | M2N4-SLI                    | [a712e10b97](https://linux-hardware.org/?probe=a712e10b97) | Mar 28, 2017 |
| ASUSTek       | P8Z77-V LX                  | [fb7fc9c78e](https://linux-hardware.org/?probe=fb7fc9c78e) | Mar 13, 2017 |
| Biostar       | Hi-Fi Z87W                  | [8e13c3fba7](https://linux-hardware.org/?probe=8e13c3fba7) | Mar 11, 2017 |
| MSI           | MS-7346                     | [1f97ef92e1](https://linux-hardware.org/?probe=1f97ef92e1) | Mar 11, 2017 |
| ASUSTek       | H81M-K                      | [0f9345171a](https://linux-hardware.org/?probe=0f9345171a) | Mar 10, 2017 |
| MSI           | MS-7346                     | [b83af770d0](https://linux-hardware.org/?probe=b83af770d0) | Mar 09, 2017 |
| ASRock        | H61M-HVS                    | [bab5245e0a](https://linux-hardware.org/?probe=bab5245e0a) | Feb 17, 2017 |
| ASUSTek       | H61M-K                      | [6c7cca8bcd](https://linux-hardware.org/?probe=6c7cca8bcd) | Feb 05, 2017 |
| Intel         | DN2820FYK H24582-201        | [0756a69391](https://linux-hardware.org/?probe=0756a69391) | Jan 07, 2017 |
| Fujitsu Si... | D2156-A1 S26361-D2156-A1    | [2313e5ca24](https://linux-hardware.org/?probe=2313e5ca24) | Dec 19, 2016 |
| ASUSTek       | P5P43TD                     | [6455128f71](https://linux-hardware.org/?probe=6455128f71) | Dec 05, 2016 |
| ASUSTek       | H81-PLUS                    | [35990fe890](https://linux-hardware.org/?probe=35990fe890) | Nov 01, 2016 |
| Gigabyte      | G31M-S2L                    | [9b1ec63eb3](https://linux-hardware.org/?probe=9b1ec63eb3) | Oct 28, 2016 |
| ASRock        | H170M Pro4                  | [c5125f0040](https://linux-hardware.org/?probe=c5125f0040) | Sep 30, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| ROSA R8.1          | 31       | 14.29%  |
| ROSA R10           | 30       | 13.82%  |
| ROSA R11           | 23       | 10.6%   |
| ROSA R9            | 15       | 6.91%   |
| ROSA R11.1         | 15       | 6.91%   |
| ROSA 12.2          | 11       | 5.07%   |
| ROSA R8            | 8        | 3.69%   |
| OpenMandriva 4.3   | 6        | 2.76%   |
| Ubuntu 20.04       | 5        | 2.3%    |
| ROSA 12.3          | 5        | 2.3%    |
| Debian 11          | 5        | 2.3%    |
| OpenMandriva 4.2   | 4        | 1.84%   |
| Slackware 15.0     | 3        | 1.38%   |
| Ubuntu 22.04       | 2        | 0.92%   |
| Ubuntu 18.04       | 2        | 0.92%   |
| OpenMandriva 23.06 | 2        | 0.92%   |
| OpenMandriva 23.03 | 2        | 0.92%   |
| OpenMandriva 23.01 | 2        | 0.92%   |
| Manjaro            | 2        | 0.92%   |
| Linux Mint 19.3    | 2        | 0.92%   |
| Linux Mint 18.3    | 2        | 0.92%   |
| KDE neon 20.04     | 2        | 0.92%   |
| Arch               | 2        | 0.92%   |
| Ubuntu 21.10       | 1        | 0.46%   |
| Ubuntu 19.04       | 1        | 0.46%   |
| Ubuntu 18.10       | 1        | 0.46%   |
| Solus 4.3          | 1        | 0.46%   |
| ROSA 12.1          | 1        | 0.46%   |
| ROSA 12            | 1        | 0.46%   |
| openSUSE Leap-15.4 | 1        | 0.46%   |
| openSUSE Leap-15.1 | 1        | 0.46%   |
| OpenMandriva 4.90  | 1        | 0.46%   |
| OpenMandriva 23.07 | 1        | 0.46%   |
| Manjaro 22.1.0     | 1        | 0.46%   |
| Manjaro 22.0.0     | 1        | 0.46%   |
| Manjaro 21.0.7     | 1        | 0.46%   |
| Manjaro 20.1       | 1        | 0.46%   |
| Manjaro 18.1.3     | 1        | 0.46%   |
| Manjaro 18.0.0-rc  | 1        | 0.46%   |
| Lubuntu 18.04      | 1        | 0.46%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| ROSA         | 125      | 64.1%   |
| OpenMandriva | 16       | 8.21%   |
| Ubuntu       | 12       | 6.15%   |
| Manjaro      | 6        | 3.08%   |
| Linux Mint   | 6        | 3.08%   |
| Debian       | 5        | 2.56%   |
| Slackware    | 3        | 1.54%   |
| KDE neon     | 3        | 1.54%   |
| Fedora       | 3        | 1.54%   |
| Arch         | 3        | 1.54%   |
| openSUSE     | 2        | 1.03%   |
| Kubuntu      | 2        | 1.03%   |
| Gentoo       | 2        | 1.03%   |
| Solus        | 1        | 0.51%   |
| Lubuntu      | 1        | 0.51%   |
| LMDE         | 1        | 0.51%   |
| Clear Linux  | 1        | 0.51%   |
| BlackPanther | 1        | 0.51%   |
| ALT Linux    | 1        | 0.51%   |
| AlmaLinux    | 1        | 0.51%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Desktops | Percent |
|-------------------------------------|----------|---------|
| 4.9.60-nrj-desktop-1rosa-x86_64     | 13       | 5.78%   |
| 5.10.74-generic-2rosa2021.1-x86_64  | 11       | 4.89%   |
| 4.9.20-nrj-desktop-1rosa-x86_64     | 11       | 4.89%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 11       | 4.89%   |
| 4.1.38-nrj-desktop-2rosa-x86_64     | 9        | 4%      |
| 4.9.60-nrj-desktop-1rosa-i586       | 7        | 3.11%   |
| 4.15.0-desktop-122.124.1rosa-x86_64 | 7        | 3.11%   |
| 5.16.7-desktop-1omv4003             | 6        | 2.67%   |
| 4.9.9-nrj-desktop-1rosa-x86_64      | 6        | 2.67%   |
| 4.9.9-nrj-desktop-1rosa-i586        | 5        | 2.22%   |
| 4.9.20-nrj-desktop-1rosa-i586       | 5        | 2.22%   |
| 4.9.155-nrj-desktop-1rosa-x86_64    | 5        | 2.22%   |
| 5.4.32-generic-2rosa-x86_64         | 4        | 1.78%   |
| 5.10.14-desktop-1omv4002            | 4        | 1.78%   |
| 4.9.76-nrj-desktop-1rosa-x86_64     | 4        | 1.78%   |
| 4.15.0-desktop-68.5rosa-x86_64      | 4        | 1.78%   |
| 4.15.0-desktop-45.1rosa-i586        | 4        | 1.78%   |
| 6.3.5-desktop-3omv2390              | 3        | 1.33%   |
| 5.15.79-generic-1rosa2021.1-x86_64  | 3        | 1.33%   |
| 4.1.34-nrj-desktop-2rosa-x86_64     | 3        | 1.33%   |
| 6.2.6-desktop-1omv2390              | 2        | 0.89%   |
| 6.1.1-desktop-1omv2290              | 2        | 0.89%   |
| 5.8.6-1-MANJARO                     | 2        | 0.89%   |
| 5.4.0-52-generic                    | 2        | 0.89%   |
| 5.15.75-generic-1rosa2021.1-x86_64  | 2        | 0.89%   |
| 5.15.19                             | 2        | 0.89%   |
| 5.14.21-150400.24.41-default        | 2        | 0.89%   |
| 5.10.118-generic-2rosa2021.1-x86_64 | 2        | 0.89%   |
| 4.9.41-nrj-desktop-1rosa-x86_64     | 2        | 0.89%   |
| 4.9.124-nrj-desktop-1rosa-x86_64    | 2        | 0.89%   |
| 4.9.111-nrj-desktop-2rosa-x86_64    | 2        | 0.89%   |
| 4.1.38-nrj-desktop-2rosa-i586       | 2        | 0.89%   |
| 4.1.34-nrj-desktop-2rosa-i586       | 2        | 0.89%   |
| 6.2.13-300.fc38.x86_64              | 1        | 0.44%   |
| 6.1.23-1-MANJARO                    | 1        | 0.44%   |
| 6.0.11-300.fc37.x86_64              | 1        | 0.44%   |
| 5.8.13-21-tkg-upds                  | 1        | 0.44%   |
| 5.4.87-gentoo-x86_64                | 1        | 0.44%   |
| 5.4.85-std-def-alt1                 | 1        | 0.44%   |
| 5.4.32-generic-2rosa-i586           | 1        | 0.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 4.15.0   | 32       | 14.35%  |
| 4.9.60   | 20       | 8.97%   |
| 4.9.20   | 16       | 7.17%   |
| 5.10.74  | 11       | 4.93%   |
| 4.9.9    | 11       | 4.93%   |
| 4.1.38   | 11       | 4.93%   |
| 5.16.7   | 6        | 2.69%   |
| 4.9.155  | 6        | 2.69%   |
| 5.4.32   | 5        | 2.24%   |
| 4.9.76   | 5        | 2.24%   |
| 4.1.34   | 5        | 2.24%   |
| 5.4.0    | 4        | 1.79%   |
| 5.13.0   | 4        | 1.79%   |
| 5.10.14  | 4        | 1.79%   |
| 5.10.0   | 4        | 1.79%   |
| 6.3.5    | 3        | 1.35%   |
| 5.15.79  | 3        | 1.35%   |
| 5.15.0   | 3        | 1.35%   |
| 4.9.41   | 3        | 1.35%   |
| 4.9.124  | 3        | 1.35%   |
| 4.9.111  | 3        | 1.35%   |
| 6.2.6    | 2        | 0.9%    |
| 6.1.1    | 2        | 0.9%    |
| 5.8.6    | 2        | 0.9%    |
| 5.19.0   | 2        | 0.9%    |
| 5.18.12  | 2        | 0.9%    |
| 5.15.75  | 2        | 0.9%    |
| 5.15.19  | 2        | 0.9%    |
| 5.14.21  | 2        | 0.9%    |
| 5.10.118 | 2        | 0.9%    |
| 5.0.0    | 2        | 0.9%    |
| 4.9.34   | 2        | 0.9%    |
| 4.18.16  | 2        | 0.9%    |
| 4.1.25   | 2        | 0.9%    |
| 6.2.13   | 1        | 0.45%   |
| 6.1.23   | 1        | 0.45%   |
| 6.0.11   | 1        | 0.45%   |
| 5.8.13   | 1        | 0.45%   |
| 5.4.87   | 1        | 0.45%   |
| 5.4.85   | 1        | 0.45%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.9     | 63       | 29.72%  |
| 4.15    | 32       | 15.09%  |
| 5.10    | 24       | 11.32%  |
| 4.1     | 17       | 8.02%   |
| 5.15    | 12       | 5.66%   |
| 5.4     | 11       | 5.19%   |
| 5.16    | 6        | 2.83%   |
| 5.13    | 5        | 2.36%   |
| 4.18    | 5        | 2.36%   |
| 5.14    | 4        | 1.89%   |
| 6.3     | 3        | 1.42%   |
| 6.2     | 3        | 1.42%   |
| 6.1     | 3        | 1.42%   |
| 5.8     | 3        | 1.42%   |
| 5.19    | 3        | 1.42%   |
| 5.0     | 3        | 1.42%   |
| 5.3     | 2        | 0.94%   |
| 5.18    | 2        | 0.94%   |
| 5.17    | 2        | 0.94%   |
| 4.12    | 2        | 0.94%   |
| 6.0     | 1        | 0.47%   |
| 4.4     | 1        | 0.47%   |
| 4.19    | 1        | 0.47%   |
| 4.17    | 1        | 0.47%   |
| 4.14    | 1        | 0.47%   |
| 4.13    | 1        | 0.47%   |
| 3.14    | 1        | 0.47%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 163      | 83.16%  |
| i686   | 33       | 16.84%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| KDE4          | 85       | 42.29%  |
| KDE5          | 64       | 31.84%  |
| GNOME         | 17       | 8.46%   |
| Unknown       | 10       | 4.98%   |
| XFCE          | 6        | 2.99%   |
| Cinnamon      | 5        | 2.49%   |
| KDE           | 4        | 1.99%   |
| X-Cinnamon    | 3        | 1.49%   |
| MATE          | 3        | 1.49%   |
| LXDE          | 2        | 1%      |
| LXQt          | 1        | 0.5%    |
| GNOME Classic | 1        | 0.5%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 170      | 86.73%  |
| Wayland | 21       | 10.71%  |
| Unknown | 3        | 1.53%   |
| Tty     | 2        | 1.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| KDM     | 87       | 43.28%  |
| SDDM    | 68       | 33.83%  |
| Unknown | 18       | 8.96%   |
| GDM     | 12       | 5.97%   |
| LightDM | 8        | 3.98%   |
| TDM     | 5        | 2.49%   |
| GDM3    | 3        | 1.49%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 113      | 55.94%  |
| ru_RU   | 60       | 29.7%   |
| en_US   | 26       | 12.87%  |
| ru_KZ   | 1        | 0.5%    |
| en_GB   | 1        | 0.5%    |
| C       | 1        | 0.5%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 150      | 77.32%  |
| EFI  | 44       | 22.68%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 102      | 50.25%  |
| Unknown | 70       | 34.48%  |
| Overlay | 16       | 7.88%   |
| Btrfs   | 11       | 5.42%   |
| Xfs     | 2        | 0.99%   |
| Zfs     | 1        | 0.49%   |
| Tmpfs   | 1        | 0.49%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| MBR     | 91       | 45.96%  |
| GPT     | 54       | 27.27%  |
| Unknown | 53       | 26.77%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 161      | 82.14%  |
| Yes       | 35       | 17.86%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 123      | 61.81%  |
| Yes       | 76       | 38.19%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 42       | 22.11%  |
| ASUSTek Computer    | 41       | 21.58%  |
| ASRock              | 28       | 14.74%  |
| MSI                 | 17       | 8.95%   |
| ECS                 | 12       | 6.32%   |
| Biostar             | 10       | 5.26%   |
| Intel               | 8        | 4.21%   |
| Foxconn             | 8        | 4.21%   |
| Hewlett-Packard     | 4        | 2.11%   |
| Unknown             | 4        | 2.11%   |
| Dell                | 3        | 1.58%   |
| Lenovo              | 2        | 1.05%   |
| Fujitsu Siemens     | 2        | 1.05%   |
| OEM                 | 1        | 0.53%   |
| GoWin Solution      | 1        | 0.53%   |
| Fujitsu             | 1        | 0.53%   |
| EPoX Computer       | 1        | 0.53%   |
| eMachines           | 1        | 0.53%   |
| Colorful Technology | 1        | 0.53%   |
| Athermiter/PlexHD   | 1        | 0.53%   |
| AMI                 | 1        | 0.53%   |
| Acer                | 1        | 0.53%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| ASUS All Series                 | 7        | 3.68%   |
| Unknown                         | 5        | 2.63%   |
| Gigabyte P35-DS3L               | 3        | 1.58%   |
| ASUS H61M-K                     | 3        | 1.58%   |
| MSI MS-7788                     | 2        | 1.05%   |
| MSI MS-7592                     | 2        | 1.05%   |
| Gigabyte EP45-DS3L              | 2        | 1.05%   |
| Gigabyte B450M S2H              | 2        | 1.05%   |
| Gigabyte A320M-H                | 2        | 1.05%   |
| Foxconn G31MXP FAB:1.1          | 2        | 1.05%   |
| ECS P67H2-A3                    | 2        | 1.05%   |
| ECS H61H2-M12                   | 2        | 1.05%   |
| ECS G31T-M7                     | 2        | 1.05%   |
| Biostar B75MU3B                 | 2        | 1.05%   |
| ASRock Q1900M                   | 2        | 1.05%   |
| ASRock G31M-VS                  | 2        | 1.05%   |
| ASRock G31M-GS                  | 2        | 1.05%   |
| MSI MS-7D15                     | 1        | 0.53%   |
| MSI MS-7B79                     | 1        | 0.53%   |
| MSI MS-7817                     | 1        | 0.53%   |
| MSI MS-7759                     | 1        | 0.53%   |
| MSI MS-7758                     | 1        | 0.53%   |
| MSI MS-7583                     | 1        | 0.53%   |
| MSI MS-7529                     | 1        | 0.53%   |
| MSI MS-7522                     | 1        | 0.53%   |
| MSI MS-7519                     | 1        | 0.53%   |
| MSI MS-7365                     | 1        | 0.53%   |
| MSI MS-7360                     | 1        | 0.53%   |
| MSI MS-7346                     | 1        | 0.53%   |
| MSI ESPRIMO P1510               | 1        | 0.53%   |
| Lenovo ThinkCentre M58p 6138A89 | 1        | 0.53%   |
| Lenovo IdeaCentre B320          | 1        | 0.53%   |
| Intel H61                       | 1        | 0.53%   |
| Intel DP45SG AAE27733-407       | 1        | 0.53%   |
| Intel DN2820FYK H24582-201      | 1        | 0.53%   |
| Intel DH61WW AAG23116-204       | 1        | 0.53%   |
| Intel DH55PJ AAE93812-302       | 1        | 0.53%   |
| Intel DG965RY AAD41691-301      | 1        | 0.53%   |
| Intel DG965RY AAD41691-205      | 1        | 0.53%   |
| Intel DB65AL AAG12530-306       | 1        | 0.53%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| ASUS All           | 7        | 3.68%   |
| ASUS PRIME         | 6        | 3.16%   |
| Unknown            | 5        | 2.63%   |
| Gigabyte P35-DS3L  | 3        | 1.58%   |
| Foxconn G31MXP     | 3        | 1.58%   |
| ASUS H61M-K        | 3        | 1.58%   |
| MSI MS-7788        | 2        | 1.05%   |
| MSI MS-7592        | 2        | 1.05%   |
| Intel DG965RY      | 2        | 1.05%   |
| HP Compaq          | 2        | 1.05%   |
| Gigabyte EP45-DS3L | 2        | 1.05%   |
| Gigabyte B450M     | 2        | 1.05%   |
| Gigabyte A320M-H   | 2        | 1.05%   |
| ECS P67H2-A3       | 2        | 1.05%   |
| ECS H61H2-M12      | 2        | 1.05%   |
| ECS G31T-M7        | 2        | 1.05%   |
| Biostar B75MU3B    | 2        | 1.05%   |
| ASUS TUF           | 2        | 1.05%   |
| ASUS ROG           | 2        | 1.05%   |
| ASUS P8H61-M       | 2        | 1.05%   |
| ASUS P8B75-M       | 2        | 1.05%   |
| ASUS P5P43TD       | 2        | 1.05%   |
| ASRock Q1900M      | 2        | 1.05%   |
| ASRock G31M-VS     | 2        | 1.05%   |
| ASRock G31M-GS     | 2        | 1.05%   |
| MSI MS-7D15        | 1        | 0.53%   |
| MSI MS-7B79        | 1        | 0.53%   |
| MSI MS-7817        | 1        | 0.53%   |
| MSI MS-7759        | 1        | 0.53%   |
| MSI MS-7758        | 1        | 0.53%   |
| MSI MS-7583        | 1        | 0.53%   |
| MSI MS-7529        | 1        | 0.53%   |
| MSI MS-7522        | 1        | 0.53%   |
| MSI MS-7519        | 1        | 0.53%   |
| MSI MS-7365        | 1        | 0.53%   |
| MSI MS-7360        | 1        | 0.53%   |
| MSI MS-7346        | 1        | 0.53%   |
| MSI ESPRIMO        | 1        | 0.53%   |
| Lenovo ThinkCentre | 1        | 0.53%   |
| Lenovo IdeaCentre  | 1        | 0.53%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2012    | 26       | 13.68%  |
| 2011    | 23       | 12.11%  |
| 2009    | 20       | 10.53%  |
| 2008    | 20       | 10.53%  |
| 2007    | 16       | 8.42%   |
| 2018    | 12       | 6.32%   |
| 2013    | 12       | 6.32%   |
| 2014    | 11       | 5.79%   |
| 2010    | 10       | 5.26%   |
| 2017    | 7        | 3.68%   |
| 2016    | 6        | 3.16%   |
| 2020    | 5        | 2.63%   |
| 2019    | 5        | 2.63%   |
| 2015    | 5        | 2.63%   |
| 2006    | 5        | 2.63%   |
| 2005    | 3        | 1.58%   |
| 2022    | 2        | 1.05%   |
| 2021    | 1        | 0.53%   |
| Unknown | 1        | 0.53%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 190      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 190      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 190      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 3.01-4.0    | 56       | 27.86%  |
| 8.01-16.0   | 40       | 19.9%   |
| 4.01-8.0    | 28       | 13.93%  |
| 16.01-24.0  | 28       | 13.93%  |
| 1.01-2.0    | 18       | 8.96%   |
| 2.01-3.0    | 11       | 5.47%   |
| 32.01-64.0  | 10       | 4.98%   |
| 24.01-32.0  | 4        | 1.99%   |
| 0.51-1.0    | 4        | 1.99%   |
| 64.01-256.0 | 2        | 1%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 94       | 44.13%  |
| 0.51-1.0   | 71       | 33.33%  |
| 2.01-3.0   | 27       | 12.68%  |
| 4.01-8.0   | 8        | 3.76%   |
| 3.01-4.0   | 5        | 2.35%   |
| 8.01-16.0  | 3        | 1.41%   |
| 0.01-0.5   | 3        | 1.41%   |
| 32.01-64.0 | 1        | 0.47%   |
| 16.01-24.0 | 1        | 0.47%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 89       | 43.84%  |
| 2      | 62       | 30.54%  |
| 3      | 31       | 15.27%  |
| 4      | 12       | 5.91%   |
| 5      | 4        | 1.97%   |
| 6      | 3        | 1.48%   |
| 8      | 1        | 0.49%   |
| 0      | 1        | 0.49%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 106      | 54.08%  |
| No        | 90       | 45.92%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 190      | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 145      | 75.13%  |
| Yes       | 48       | 24.87%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 173      | 90.1%   |
| Yes       | 19       | 9.9%    |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Desktops | Percent |
|------------|----------|---------|
| Kazakhstan | 190      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Desktops | Percent |
|-----------------|----------|---------|
| Almaty          | 55       | 26.57%  |
| Nur-Sultan      | 24       | 11.59%  |
| Kostanay        | 17       | 8.21%   |
| Taraz           | 12       | 5.8%    |
| Karaganda       | 12       | 5.8%    |
| Ust-Kamenogorsk | 10       | 4.83%   |
| Pavlodar        | 10       | 4.83%   |
| Semey           | 7        | 3.38%   |
| Rudnyy          | 6        | 2.9%    |
| Petropavl       | 6        | 2.9%    |
| Atyrau          | 6        | 2.9%    |
| Aktobe          | 6        | 2.9%    |
| Temirtau        | 4        | 1.93%   |
| Ridder          | 4        | 1.93%   |
| Shymkent        | 3        | 1.45%   |
| Oral            | 3        | 1.45%   |
| Astana          | 3        | 1.45%   |
| Tekeli          | 2        | 0.97%   |
| Sarkand         | 2        | 0.97%   |
| Makhambet       | 2        | 0.97%   |
| Aktau           | 2        | 0.97%   |
| Tobol           | 1        | 0.48%   |
| Taldykorgan     | 1        | 0.48%   |
| Soran           | 1        | 0.48%   |
| Shchūchīnsk   | 1        | 0.48%   |
| Kokshetau       | 1        | 0.48%   |
| Karatau         | 1        | 0.48%   |
| Ekibastuz       | 1        | 0.48%   |
| Dzhezkazgan     | 1        | 0.48%   |
| Balqash         | 1        | 0.48%   |
| Amankaragay     | 1        | 0.48%   |
| Altay           | 1        | 0.48%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 101      | 160    | 30.79%  |
| WDC                 | 49       | 65     | 14.94%  |
| Samsung Electronics | 47       | 78     | 14.33%  |
| Toshiba             | 32       | 40     | 9.76%   |
| Kingston            | 22       | 32     | 6.71%   |
| Hitachi             | 11       | 12     | 3.35%   |
| Apacer              | 7        | 10     | 2.13%   |
| Transcend           | 6        | 7      | 1.83%   |
| Team                | 5        | 7      | 1.52%   |
| Gigabyte Technology | 5        | 6      | 1.52%   |
| A-DATA Technology   | 5        | 7      | 1.52%   |
| SanDisk             | 3        | 3      | 0.91%   |
| HGST                | 3        | 3      | 0.91%   |
| Plextor             | 2        | 2      | 0.61%   |
| Patriot             | 2        | 2      | 0.61%   |
| KingSpec            | 2        | 2      | 0.61%   |
| Intel               | 2        | 5      | 0.61%   |
| HUAWEI              | 2        | 2      | 0.61%   |
| Hewlett-Packard     | 2        | 2      | 0.61%   |
| GeIL                | 2        | 2      | 0.61%   |
| AMD                 | 2        | 2      | 0.61%   |
| Unknown             | 2        | 2      | 0.61%   |
| TEKET               | 1        | 2      | 0.3%    |
| SPCC                | 1        | 1      | 0.3%    |
| Smartbuy            | 1        | 1      | 0.3%    |
| SK hynix            | 1        | 1      | 0.3%    |
| Silicon Motion      | 1        | 1      | 0.3%    |
| Netac               | 1        | 1      | 0.3%    |
| Maxtor              | 1        | 1      | 0.3%    |
| LVCARDS             | 1        | 1      | 0.3%    |
| Kingmax             | 1        | 1      | 0.3%    |
| KingFast            | 1        | 1      | 0.3%    |
| HS-SSD-C100         | 1        | 1      | 0.3%    |
| Hikvision           | 1        | 1      | 0.3%    |
| Crucial             | 1        | 1      | 0.3%    |
| AFOX                | 1        | 1      | 0.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 12       | 3.23%   |
| Toshiba DT01ACA050 500GB         | 11       | 2.96%   |
| Seagate ST3500418AS 500GB        | 8        | 2.16%   |
| WDC WD5000AAKX-001CA0 500GB      | 6        | 1.62%   |
| Seagate ST3500413AS 500GB        | 6        | 1.62%   |
| Seagate ST3250310AS 250GB        | 6        | 1.62%   |
| Toshiba HDWD110 1TB              | 5        | 1.35%   |
| Toshiba DT01ACA100 1TB           | 5        | 1.35%   |
| Seagate ST3320620AS 320GB        | 5        | 1.35%   |
| Samsung HD502HJ 500GB            | 5        | 1.35%   |
| Seagate ST380011A 80GB           | 4        | 1.08%   |
| Seagate ST3250820AS 250GB        | 4        | 1.08%   |
| Seagate ST3160815AS 160GB        | 4        | 1.08%   |
| Seagate ST1000DM003-1CH162 1TB   | 4        | 1.08%   |
| Samsung SSD 860 EVO 250GB        | 4        | 1.08%   |
| Samsung HD322HJ 320GB            | 4        | 1.08%   |
| Gigabyte GP-GSTFS31120GNTD 120GB | 4        | 1.08%   |
| Toshiba HDWD105 500GB            | 3        | 0.81%   |
| Toshiba DT01ACA200 2TB           | 3        | 0.81%   |
| Seagate ST380215AS 80GB          | 3        | 0.81%   |
| Seagate ST3802110A 80GB          | 3        | 0.81%   |
| Seagate ST3500320AS 500GB        | 3        | 0.81%   |
| Seagate ST340014A 40GB           | 3        | 0.81%   |
| Seagate ST3320613AS 320GB        | 3        | 0.81%   |
| Seagate ST3320418AS 320GB        | 3        | 0.81%   |
| Seagate ST3250318AS 250GB        | 3        | 0.81%   |
| Seagate ST31000524AS 1TB         | 3        | 0.81%   |
| Seagate ST1000DM010-2EP102 1TB   | 3        | 0.81%   |
| Samsung HD502HI 500GB            | 3        | 0.81%   |
| Samsung HD103SJ 1TB              | 3        | 0.81%   |
| Kingston SUV500240G 240GB SSD    | 3        | 0.81%   |
| Kingston SA400S37240G 240GB SSD  | 3        | 0.81%   |
| Kingston SA400S37120G 120GB SSD  | 3        | 0.81%   |
| Apacer AS350 128GB SSD           | 3        | 0.81%   |
| WDC WD800JD-60LSA0 80GB          | 2        | 0.54%   |
| WDC WD5000LPVX-00V0TT0 500GB     | 2        | 0.54%   |
| WDC WD2000JS-60NCB1 200GB        | 2        | 0.54%   |
| Transcend TS240GSSD220S 240GB    | 2        | 0.54%   |
| Team T253X2256G 256GB SSD        | 2        | 0.54%   |
| Seagate ST3500630AS 500GB        | 2        | 0.54%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 99       | 158    | 43.04%  |
| WDC                 | 49       | 65     | 21.3%   |
| Samsung Electronics | 33       | 54     | 14.35%  |
| Toshiba             | 32       | 40     | 13.91%  |
| Hitachi             | 11       | 12     | 4.78%   |
| HGST                | 3        | 3      | 1.3%    |
| Hewlett-Packard     | 2        | 2      | 0.87%   |
| Maxtor              | 1        | 1      | 0.43%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 21       | 28     | 26.58%  |
| Samsung Electronics | 12       | 16     | 15.19%  |
| Apacer              | 7        | 10     | 8.86%   |
| Transcend           | 6        | 7      | 7.59%   |
| Team                | 5        | 7      | 6.33%   |
| Gigabyte Technology | 5        | 6      | 6.33%   |
| Plextor             | 2        | 2      | 2.53%   |
| Patriot             | 2        | 2      | 2.53%   |
| KingSpec            | 2        | 2      | 2.53%   |
| GeIL                | 2        | 2      | 2.53%   |
| AMD                 | 2        | 2      | 2.53%   |
| TEKET               | 1        | 2      | 1.27%   |
| SPCC                | 1        | 1      | 1.27%   |
| Smartbuy            | 1        | 1      | 1.27%   |
| SK hynix            | 1        | 1      | 1.27%   |
| SanDisk             | 1        | 1      | 1.27%   |
| Netac               | 1        | 1      | 1.27%   |
| LVCARDS             | 1        | 1      | 1.27%   |
| Kingmax             | 1        | 1      | 1.27%   |
| KingFast            | 1        | 1      | 1.27%   |
| Intel               | 1        | 4      | 1.27%   |
| Crucial             | 1        | 1      | 1.27%   |
| AFOX                | 1        | 1      | 1.27%   |
| Unknown             | 1        | 1      | 1.27%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 174      | 335    | 66.92%  |
| SSD     | 64       | 101    | 24.62%  |
| NVMe    | 15       | 23     | 5.77%   |
| Unknown | 5        | 5      | 1.92%   |
| MMC     | 2        | 2      | 0.77%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 184      | 431    | 88.46%  |
| NVMe | 15       | 23     | 7.21%   |
| SAS  | 7        | 10     | 3.37%   |
| MMC  | 2        | 2      | 0.96%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 171      | 321    | 70.08%  |
| 0.51-1.0   | 53       | 91     | 21.72%  |
| 1.01-2.0   | 14       | 18     | 5.74%   |
| 3.01-4.0   | 2        | 2      | 0.82%   |
| 2.01-3.0   | 2        | 2      | 0.82%   |
| 4.01-10.0  | 2        | 2      | 0.82%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 49       | 23%     |
| 251-500        | 39       | 18.31%  |
| 1-20           | 30       | 14.08%  |
| 51-100         | 26       | 12.21%  |
| 501-1000       | 24       | 11.27%  |
| 21-50          | 20       | 9.39%   |
| 1001-2000      | 16       | 7.51%   |
| 2001-3000      | 4        | 1.88%   |
| Unknown        | 3        | 1.41%   |
| More than 3000 | 2        | 0.94%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 129      | 60.56%  |
| 21-50     | 20       | 9.39%   |
| 101-250   | 16       | 7.51%   |
| 51-100    | 14       | 6.57%   |
| 501-1000  | 12       | 5.63%   |
| 251-500   | 10       | 4.69%   |
| 1001-2000 | 7        | 3.29%   |
| Unknown   | 3        | 1.41%   |
| 2001-3000 | 2        | 0.94%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 6        | 8      | 5.5%    |
| WDC WD5000AAKX-001CA0 500GB       | 5        | 5      | 4.59%   |
| Seagate ST3250310AS 250GB         | 5        | 5      | 4.59%   |
| Toshiba DT01ACA050 500GB          | 3        | 4      | 2.75%   |
| Seagate ST3802110A 80GB           | 3        | 4      | 2.75%   |
| Seagate ST3500413AS 500GB         | 3        | 3      | 2.75%   |
| Seagate ST3500320AS 500GB         | 3        | 3      | 2.75%   |
| Seagate ST3320613AS 320GB         | 3        | 3      | 2.75%   |
| Seagate ST3250820AS 250GB         | 3        | 3      | 2.75%   |
| WDC WD800JD-60LSA0 80GB           | 2        | 2      | 1.83%   |
| WDC WD5000LPVX-00V0TT0 500GB      | 2        | 4      | 1.83%   |
| WDC WD2000JS-60NCB1 200GB         | 2        | 3      | 1.83%   |
| Seagate ST380215AS 80GB           | 2        | 2      | 1.83%   |
| Seagate ST3500418AS 500GB         | 2        | 4      | 1.83%   |
| Seagate ST340014A 40GB            | 2        | 2      | 1.83%   |
| Seagate ST3320620AS 320GB         | 2        | 4      | 1.83%   |
| Seagate ST3320418AS 320GB         | 2        | 2      | 1.83%   |
| Seagate ST3160815AS 160GB         | 2        | 2      | 1.83%   |
| Seagate ST3160215AS 160GB         | 2        | 2      | 1.83%   |
| Samsung Electronics HD642JJ 640GB | 2        | 4      | 1.83%   |
| Samsung Electronics HD502HI 500GB | 2        | 3      | 1.83%   |
| Hewlett-Packard FB160C4081 160GB  | 2        | 2      | 1.83%   |
| WDC WD7500BPVT-24HXZT3 752GB      | 1        | 2      | 0.92%   |
| WDC WD5000AVDS-73U7B1 500GB       | 1        | 1      | 0.92%   |
| WDC WD5000AVDS-63U7B1 500GB       | 1        | 1      | 0.92%   |
| WDC WD5000AAKX-003CA0 500GB       | 1        | 1      | 0.92%   |
| WDC WD5000AAKS-00A7B2 500GB       | 1        | 1      | 0.92%   |
| WDC WD3200BPVT-22JJ5T0 320GB      | 1        | 1      | 0.92%   |
| WDC WD3200AAJS-60Z0A0 320GB       | 1        | 1      | 0.92%   |
| WDC WD3200AAJS-00L7A0 320GB       | 1        | 2      | 0.92%   |
| WDC WD2500AVJS-63B6A0 250GB       | 1        | 1      | 0.92%   |
| WDC WD2500AAKX-001CA0 250GB       | 1        | 1      | 0.92%   |
| WDC WD15EARS-00MVWB0 1TB          | 1        | 1      | 0.92%   |
| WDC WD10PURX-64E5EY0 1TB          | 1        | 1      | 0.92%   |
| WDC WD10EALX-009BA0 1TB           | 1        | 1      | 0.92%   |
| WDC WD10EADS-00M2B0 1TB           | 1        | 2      | 0.92%   |
| Seagate ST9500325AS 500GB         | 1        | 1      | 0.92%   |
| Seagate ST380817AS 80GB           | 1        | 1      | 0.92%   |
| Seagate ST380815AS 80GB           | 1        | 1      | 0.92%   |
| Seagate ST380013AS 80GB           | 1        | 1      | 0.92%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 54       | 69     | 53.47%  |
| WDC                 | 25       | 31     | 24.75%  |
| Samsung Electronics | 9        | 13     | 8.91%   |
| Hitachi             | 4        | 5      | 3.96%   |
| Toshiba             | 3        | 4      | 2.97%   |
| Hewlett-Packard     | 2        | 2      | 1.98%   |
| Maxtor              | 1        | 1      | 0.99%   |
| Kingston            | 1        | 1      | 0.99%   |
| HGST                | 1        | 1      | 0.99%   |
| AFOX                | 1        | 1      | 0.99%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 54       | 69     | 54.55%  |
| WDC                 | 25       | 31     | 25.25%  |
| Samsung Electronics | 9        | 13     | 9.09%   |
| Hitachi             | 4        | 5      | 4.04%   |
| Toshiba             | 3        | 4      | 3.03%   |
| Hewlett-Packard     | 2        | 2      | 2.02%   |
| Maxtor              | 1        | 1      | 1.01%   |
| HGST                | 1        | 1      | 1.01%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 87       | 126    | 97.75%  |
| SSD  | 2        | 2      | 2.25%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Samsung Electronics HD322GJ 320GB | 2        | 2      | 50%     |
| WDC WD3200BPVT-24ZEST0 320GB      | 1        | 1      | 25%     |
| Seagate ST3250318AS 250GB         | 1        | 2      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 2        | 2      | 50%     |
| WDC                 | 1        | 1      | 25%     |
| Seagate             | 1        | 2      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 122      | 275    | 50%     |
| Malfunc  | 89       | 128    | 36.48%  |
| Detected | 29       | 58     | 11.89%  |
| Failed   | 4        | 5      | 1.64%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 162      | 66.94%  |
| JMicron Technology            | 21       | 8.68%   |
| AMD                           | 16       | 6.61%   |
| Marvell Technology Group      | 9        | 3.72%   |
| Nvidia                        | 8        | 3.31%   |
| Samsung Electronics           | 6        | 2.48%   |
| ASMedia Technology            | 4        | 1.65%   |
| Realtek Semiconductor         | 3        | 1.24%   |
| Kingston Technology Company   | 3        | 1.24%   |
| VIA Technologies              | 2        | 0.83%   |
| Integrated Technology Express | 2        | 0.83%   |
| ADATA Technology              | 2        | 0.83%   |
| ULi Electronics               | 1        | 0.41%   |
| Silicon Motion                | 1        | 0.41%   |
| SanDisk                       | 1        | 0.41%   |
| MAXIO Technology (Hangzhou)   | 1        | 0.41%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 31       | 9.01%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 24       | 6.98%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 17       | 4.94%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 15       | 4.36%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 15       | 4.36%   |
| JMicron JMB368 IDE controller                                                           | 12       | 3.49%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 12       | 3.49%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 11       | 3.2%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 11       | 3.2%    |
| AMD FCH SATA Controller [AHCI mode]                                                     | 10       | 2.91%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 9        | 2.62%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 8        | 2.33%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 8        | 2.33%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 7        | 2.03%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 7        | 2.03%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 7        | 2.03%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 7        | 2.03%   |
| AMD 400 Series Chipset SATA Controller                                                  | 7        | 2.03%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 6        | 1.74%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 5        | 1.45%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4        | 1.16%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 4        | 1.16%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 4        | 1.16%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 4        | 1.16%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 4        | 1.16%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 4        | 1.16%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 4        | 1.16%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 4        | 1.16%   |
| Kingston Company KC3000/Renegade NVMe SSD                                               | 3        | 0.87%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 3        | 0.87%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3        | 0.87%   |
| AMD FCH SATA Controller D                                                               | 3        | 0.87%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 2        | 0.58%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2        | 0.58%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                                       | 2        | 0.58%   |
| Nvidia MCP61 SATA Controller                                                            | 2        | 0.58%   |
| Nvidia MCP61 IDE                                                                        | 2        | 0.58%   |
| Nvidia CK804 Serial ATA Controller                                                      | 2        | 0.58%   |
| Nvidia CK804 IDE                                                                        | 2        | 0.58%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                               | 2        | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| IDE  | 99       | 46.48%  |
| SATA | 95       | 44.6%   |
| NVMe | 15       | 7.04%   |
| RAID | 3        | 1.41%   |
| SAS  | 1        | 0.47%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 168      | 88.42%  |
| AMD    | 22       | 11.58%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Pentium CPU G630 @ 2.70GHz            | 5        | 2.6%    |
| Intel Core i5-4460 CPU @ 3.20GHz            | 4        | 2.08%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 4        | 2.08%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 3        | 1.56%   |
| Intel Pentium 4 CPU 3.00GHz                 | 3        | 1.56%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 3        | 1.56%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 3        | 1.56%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 3        | 1.56%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 3        | 1.56%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz       | 3        | 1.56%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 3        | 1.56%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 3        | 1.56%   |
| Intel Core 2 Duo CPU E6750 @ 2.66GHz        | 3        | 1.56%   |
| Intel Celeron CPU G530 @ 2.40GHz            | 3        | 1.56%   |
| Intel Celeron CPU G1610 @ 2.60GHz           | 3        | 1.56%   |
| Intel Xeon CPU E5450 @ 3.00GHz              | 2        | 1.04%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 2        | 1.04%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 2        | 1.04%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 2        | 1.04%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 2        | 1.04%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 2        | 1.04%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 1.04%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 2        | 1.04%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2        | 1.04%   |
| Intel Core i5-8600K CPU @ 3.60GHz           | 2        | 1.04%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 2        | 1.04%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 1.04%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2        | 1.04%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 2        | 1.04%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 2        | 1.04%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 2        | 1.04%   |
| Intel Core i3 CPU 540 @ 3.07GHz             | 2        | 1.04%   |
| Intel Core 2 Duo CPU E7600 @ 3.06GHz        | 2        | 1.04%   |
| Intel Core 2 Duo CPU E4600 @ 2.40GHz        | 2        | 1.04%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 2        | 1.04%   |
| Intel 12th Gen Core i7-12700KF              | 2        | 1.04%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 2        | 1.04%   |
| Intel Xeon CPU X5450 @ 3.00GHz              | 1        | 0.52%   |
| Intel Xeon CPU X3440 @ 2.53GHz              | 1        | 0.52%   |
| Intel Xeon CPU E5440 @ 2.83GHz              | 1        | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 31       | 16.15%  |
| Intel Core i3           | 22       | 11.46%  |
| Intel Core 2 Duo        | 21       | 10.94%  |
| Intel Core i7           | 19       | 9.9%    |
| Intel Pentium           | 14       | 7.29%   |
| Intel Celeron           | 14       | 7.29%   |
| Intel Pentium Dual-Core | 13       | 6.77%   |
| Intel Xeon              | 9        | 4.69%   |
| Intel Core 2 Quad       | 8        | 4.17%   |
| Intel Pentium 4         | 6        | 3.13%   |
| AMD Ryzen 7             | 6        | 3.13%   |
| AMD Ryzen 5             | 5        | 2.6%    |
| Intel Pentium Dual      | 3        | 1.56%   |
| Other                   | 2        | 1.04%   |
| Intel Core 2            | 2        | 1.04%   |
| AMD Phenom II X4        | 2        | 1.04%   |
| AMD Athlon II X2        | 2        | 1.04%   |
| AMD Athlon 64 X2        | 2        | 1.04%   |
| Intel Pentium Silver    | 1        | 0.52%   |
| Intel Pentium Gold      | 1        | 0.52%   |
| Intel Genuine           | 1        | 0.52%   |
| Intel Core i9           | 1        | 0.52%   |
| Intel Core 2 Extreme    | 1        | 0.52%   |
| Intel Atom              | 1        | 0.52%   |
| AMD Ryzen 9             | 1        | 0.52%   |
| AMD Ryzen 3             | 1        | 0.52%   |
| AMD Phenom II X6        | 1        | 0.52%   |
| AMD FX                  | 1        | 0.52%   |
| AMD Athlon 64           | 1        | 0.52%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 81       | 41.97%  |
| 4       | 61       | 31.61%  |
| Unknown | 18       | 9.33%   |
| 8       | 12       | 6.22%   |
| 6       | 9        | 4.66%   |
| 1       | 7        | 3.63%   |
| 12      | 3        | 1.55%   |
| 16      | 1        | 0.52%   |
| 3       | 1        | 0.52%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 187      | 98.42%  |
| 2      | 3        | 1.58%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 105      | 54.97%  |
| 2       | 68       | 35.6%   |
| Unknown | 18       | 9.42%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 189      | 99.47%  |
| Unknown        | 1        | 0.53%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x1067a    | 34       | 17.44%  |
| 0x206a7    | 23       | 11.79%  |
| 0x306a9    | 21       | 10.77%  |
| Unknown    | 21       | 10.77%  |
| 0x306c3    | 14       | 7.18%   |
| 0x906e9    | 8        | 4.1%    |
| 0x6fd      | 7        | 3.59%   |
| 0x10676    | 6        | 3.08%   |
| 0x6fb      | 5        | 2.56%   |
| 0x20652    | 4        | 2.05%   |
| 0xf49      | 3        | 1.54%   |
| 0x906ea    | 3        | 1.54%   |
| 0x506e3    | 3        | 1.54%   |
| 0x08701021 | 3        | 1.54%   |
| 0xa0653    | 2        | 1.03%   |
| 0x906ed    | 2        | 1.03%   |
| 0x6f2      | 2        | 1.03%   |
| 0x30678    | 2        | 1.03%   |
| 0x106a5    | 2        | 1.03%   |
| 0x0800820d | 2        | 1.03%   |
| 0xf65      | 1        | 0.51%   |
| 0xf4a      | 1        | 0.51%   |
| 0xf43      | 1        | 0.51%   |
| 0xa0655    | 1        | 0.51%   |
| 0x906ec    | 1        | 0.51%   |
| 0x906c0    | 1        | 0.51%   |
| 0x90672    | 1        | 0.51%   |
| 0x6f6      | 1        | 0.51%   |
| 0x406c4    | 1        | 0.51%   |
| 0x306e4    | 1        | 0.51%   |
| 0x306d4    | 1        | 0.51%   |
| 0x30673    | 1        | 0.51%   |
| 0x206d7    | 1        | 0.51%   |
| 0x20655    | 1        | 0.51%   |
| 0x106e5    | 1        | 0.51%   |
| 0x10677    | 1        | 0.51%   |
| 0x10661    | 1        | 0.51%   |
| 0x0a601203 | 1        | 0.51%   |
| 0x08108109 | 1        | 0.51%   |
| 0x0800820b | 1        | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Penryn           | 41       | 21.35%  |
| IvyBridge        | 25       | 13.02%  |
| SandyBridge      | 24       | 12.5%   |
| Core             | 18       | 9.38%   |
| Haswell          | 17       | 8.85%   |
| KabyLake         | 15       | 7.81%   |
| NetBurst         | 6        | 3.13%   |
| Zen+             | 5        | 2.6%    |
| Westmere         | 5        | 2.6%    |
| K10              | 5        | 2.6%    |
| Skylake          | 4        | 2.08%   |
| Silvermont       | 4        | 2.08%   |
| CometLake        | 4        | 2.08%   |
| Zen 2            | 3        | 1.56%   |
| Nehalem          | 3        | 1.56%   |
| K8 Hammer        | 3        | 1.56%   |
| Zen 3            | 2        | 1.04%   |
| Zen              | 2        | 1.04%   |
| Unknown          | 2        | 1.04%   |
| Tremont          | 1        | 0.52%   |
| Piledriver       | 1        | 0.52%   |
| Broadwell        | 1        | 0.52%   |
| Alderlake Hybrid | 1        | 0.52%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 130      | 64.04%  |
| Intel  | 46       | 22.66%  |
| AMD    | 27       | 13.3%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 10       | 4.74%   |
| Nvidia GT218 [GeForce 210]                                                  | 8        | 3.79%   |
| Nvidia GF108 [GeForce GT 440]                                               | 7        | 3.32%   |
| Nvidia GF114 [GeForce GTX 560 Ti]                                           | 6        | 2.84%   |
| Nvidia GF108 [GeForce GT 730]                                               | 6        | 2.84%   |
| Nvidia G94 [GeForce 9600 GT]                                                | 6        | 2.84%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 5        | 2.37%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5        | 2.37%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 4        | 1.9%    |
| Nvidia GF108 [GeForce GT 430]                                               | 4        | 1.9%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 4        | 1.9%    |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 4        | 1.9%    |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 4        | 1.9%    |
| AMD Juniper PRO [Radeon HD 5750]                                            | 4        | 1.9%    |
| Nvidia GT215 [GeForce GT 240]                                               | 3        | 1.42%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 1.42%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 3        | 1.42%   |
| Nvidia GK208B [GeForce GT 730]                                              | 3        | 1.42%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 3        | 1.42%   |
| Nvidia GF119 [GeForce GT 520]                                               | 3        | 1.42%   |
| Nvidia GF108 [GeForce GT 630]                                               | 3        | 1.42%   |
| Nvidia G92 [GeForce 9800 GT]                                                | 3        | 1.42%   |
| Nvidia G84 [GeForce 8600 GT]                                                | 3        | 1.42%   |
| Intel HD Graphics 630                                                       | 3        | 1.42%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 1.42%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 3        | 1.42%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 3        | 1.42%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 2        | 0.95%   |
| Nvidia GT216 [GeForce 210]                                                  | 2        | 0.95%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 0.95%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 0.95%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 2        | 0.95%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 0.95%   |
| Nvidia GK208 [GeForce GT 630 Rev. 2]                                        | 2        | 0.95%   |
| Nvidia GK107 [GeForce GT 640]                                               | 2        | 0.95%   |
| Nvidia GK107 [GeForce GT 630 OEM]                                           | 2        | 0.95%   |
| Nvidia GF119 [GeForce GT 610]                                               | 2        | 0.95%   |
| Nvidia GA106 [Geforce RTX 3050]                                             | 2        | 0.95%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 2        | 0.95%   |
| Nvidia G96C [GeForce 9400 GT]                                               | 2        | 0.95%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 127      | 65.46%  |
| 1 x Intel      | 37       | 19.07%  |
| 1 x AMD        | 24       | 12.37%  |
| Intel + Nvidia | 4        | 2.06%   |
| 2 x AMD        | 2        | 1.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 134      | 67.34%  |
| Proprietary | 56       | 28.14%  |
| Unknown     | 9        | 4.52%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 0.51-1.0   | 59       | 29.95%  |
| 1.01-2.0   | 48       | 24.37%  |
| Unknown    | 39       | 19.8%   |
| 0.01-0.5   | 25       | 12.69%  |
| 3.01-4.0   | 11       | 5.58%   |
| 7.01-8.0   | 8        | 4.06%   |
| 5.01-6.0   | 3        | 1.52%   |
| 8.01-16.0  | 2        | 1.02%   |
| 2.01-3.0   | 1        | 0.51%   |
| 16.01-24.0 | 1        | 0.51%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 53       | 28.19%  |
| Goldstar             | 29       | 15.43%  |
| Philips              | 16       | 8.51%   |
| BenQ                 | 15       | 7.98%   |
| Acer                 | 15       | 7.98%   |
| Hewlett-Packard      | 14       | 7.45%   |
| AOC                  | 8        | 4.26%   |
| Dell                 | 6        | 3.19%   |
| ViewSonic            | 3        | 1.6%    |
| Lenovo               | 3        | 1.6%    |
| Arnos Instruments    | 3        | 1.6%    |
| Panasonic            | 2        | 1.06%   |
| LG Electronics       | 2        | 1.06%   |
| Iiyama               | 2        | 1.06%   |
| Gigabyte Technology  | 2        | 1.06%   |
| Fujitsu Siemens      | 2        | 1.06%   |
| WY@                  | 1        | 0.53%   |
| VIE                  | 1        | 0.53%   |
| Unknown (XXX)        | 1        | 0.53%   |
| TPU                  | 1        | 0.53%   |
| Toshiba              | 1        | 0.53%   |
| Sony                 | 1        | 0.53%   |
| SKY                  | 1        | 0.53%   |
| SAC                  | 1        | 0.53%   |
| Packard Bell         | 1        | 0.53%   |
| HPN                  | 1        | 0.53%   |
| HJW                  | 1        | 0.53%   |
| CTX                  | 1        | 0.53%   |
| Ancor Communications | 1        | 0.53%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM018F 1280x1024 338x270mm 17.0-inch   | 4        | 2.03%   |
| Samsung Electronics SyncMaster SAM0285 1440x900 410x257mm 19.1-inch    | 3        | 1.52%   |
| Hewlett-Packard L1740 HWP2648 1280x1024 338x270mm 17.0-inch            | 3        | 1.52%   |
| Hewlett-Packard 2011 HWP2934 1600x900 443x250mm 20.0-inch              | 3        | 1.52%   |
| BenQ E900W BNQ7905 1440x900 410x256mm 19.0-inch                        | 3        | 1.52%   |
| Arnos Instruments '' AIC0400 1280x1024                                 | 3        | 1.52%   |
| Acer V193HQ ACR006D 1366x768 410x230mm 18.5-inch                       | 3        | 1.52%   |
| Samsung Electronics SyncMaster SAM0564 1360x768 410x230mm 18.5-inch    | 2        | 1.02%   |
| Samsung Electronics SyncMaster SAM037C 1680x1050 470x300mm 22.0-inch   | 2        | 1.02%   |
| Samsung Electronics SyncMaster SAM0248 1280x1024 376x301mm 19.0-inch   | 2        | 1.02%   |
| Samsung Electronics SMS19A100 SAM0867 1366x768 410x230mm 18.5-inch     | 2        | 1.02%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch      | 2        | 1.02%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch      | 2        | 1.02%   |
| Samsung Electronics S22C150 SAM0AE5 1920x1080 477x268mm 21.5-inch      | 2        | 1.02%   |
| Samsung Electronics S20B300 SAM08A7 1600x900 443x249mm 20.0-inch       | 2        | 1.02%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 1060x626mm 48.5-inch | 2        | 1.02%   |
| Samsung Electronics F27G3xTF SAM710D 1920x1080 600x330mm 27.0-inch     | 2        | 1.02%   |
| Philips 226VL PHLC081 1920x1080 480x268mm 21.6-inch                    | 2        | 1.02%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                     | 2        | 1.02%   |
| Goldstar W2242 GSM5677 1680x1050 474x296mm 22.0-inch                   | 2        | 1.02%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                    | 2        | 1.02%   |
| Goldstar W1942 GSM4B6F 1440x900 408x255mm 18.9-inch                    | 2        | 1.02%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch              | 2        | 1.02%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 2        | 1.02%   |
| Goldstar E1941 GSM4BF0 1366x768 410x230mm 18.5-inch                    | 2        | 1.02%   |
| Dell E190S DELA04B 1280x1024 376x301mm 19.0-inch                       | 2        | 1.02%   |
| BenQ G700 BNQ7801 1280x1024 340x270mm 17.1-inch                        | 2        | 1.02%   |
| BenQ E900 BNQ7903 1280x1024 376x301mm 19.0-inch                        | 2        | 1.02%   |
| WY@ Monitor WY@0170 1280x1024                                          | 1        | 0.51%   |
| ViewSonic VX715 VSC4319 1280x1024 338x270mm 17.0-inch                  | 1        | 0.51%   |
| ViewSonic VX2268wm VSC0E23 1680x1050 474x296mm 22.0-inch               | 1        | 0.51%   |
| ViewSonic LCD Monitor VSC5E1E 1440x900 410x260mm 19.1-inch             | 1        | 0.51%   |
| VIE A/G2356 VIE2300 1920x1080 500x300mm 23.0-inch                      | 1        | 0.51%   |
| Unknown (XXX) HDMI XXX0088 1920x540                                    | 1        | 0.51%   |
| TPU HDMI TPU2150 1920x1080 376x301mm 19.0-inch                         | 1        | 0.51%   |
| Toshiba TV TSB010B 1920x1080 706x398mm 31.9-inch                       | 1        | 0.51%   |
| Sony TV SNYAB03 1920x1080                                              | 1        | 0.51%   |
| SKY TV SKY1502 3840x2160 708x398mm 32.0-inch                           | 1        | 0.51%   |
| Samsung Electronics SyncMaster SAM05C5 1920x1080                       | 1        | 0.51%   |
| Samsung Electronics SyncMaster SAM0594 1680x1050 459x296mm 21.5-inch   | 1        | 0.51%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 67       | 35.64%  |
| 1280x1024 (SXGA)   | 40       | 21.28%  |
| 1366x768 (WXGA)    | 19       | 10.11%  |
| 1600x900 (HD+)     | 13       | 6.91%   |
| 1440x900 (WXGA+)   | 12       | 6.38%   |
| 1680x1050 (WSXGA+) | 10       | 5.32%   |
| 3840x2160 (4K)     | 7        | 3.72%   |
| 2560x1440 (QHD)    | 4        | 2.13%   |
| 1360x768           | 4        | 2.13%   |
| Unknown            | 3        | 1.6%    |
| 2560x1080          | 2        | 1.06%   |
| 3840x1080          | 1        | 0.53%   |
| 3600x1080          | 1        | 0.53%   |
| 3520x1080          | 1        | 0.53%   |
| 3200x1080          | 1        | 0.53%   |
| 1920x540           | 1        | 0.53%   |
| 1280x960           | 1        | 0.53%   |
| 1280x720 (HD)      | 1        | 0.53%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 19      | 28       | 14.81%  |
| 21      | 27       | 14.29%  |
| 17      | 25       | 13.23%  |
| 18      | 24       | 12.7%   |
| 23      | 14       | 7.41%   |
| Unknown | 13       | 6.88%   |
| 27      | 12       | 6.35%   |
| 20      | 12       | 6.35%   |
| 24      | 8        | 4.23%   |
| 22      | 7        | 3.7%    |
| 48      | 3        | 1.59%   |
| 84      | 2        | 1.06%   |
| 72      | 2        | 1.06%   |
| 34      | 2        | 1.06%   |
| 31      | 2        | 1.06%   |
| 64      | 1        | 0.53%   |
| 54      | 1        | 0.53%   |
| 47      | 1        | 0.53%   |
| 46      | 1        | 0.53%   |
| 43      | 1        | 0.53%   |
| 40      | 1        | 0.53%   |
| 32      | 1        | 0.53%   |
| 16      | 1        | 0.53%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 82       | 44.09%  |
| 501-600     | 30       | 16.13%  |
| 301-350     | 26       | 13.98%  |
| 351-400     | 17       | 9.14%   |
| Unknown     | 13       | 6.99%   |
| 1001-1500   | 7        | 3.76%   |
| 1501-2000   | 4        | 2.15%   |
| 701-800     | 3        | 1.61%   |
| 601-700     | 2        | 1.08%   |
| 801-900     | 1        | 0.54%   |
| 901-1000    | 1        | 0.54%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 107      | 58.15%  |
| 5/4     | 41       | 22.28%  |
| 16/10   | 20       | 10.87%  |
| Unknown | 10       | 5.43%   |
| 3/2     | 2        | 1.09%   |
| 21/9    | 2        | 1.09%   |
| 4/3     | 1        | 0.54%   |
| 32/9    | 1        | 0.54%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 49       | 26.2%   |
| 141-150        | 47       | 25.13%  |
| 151-200        | 45       | 24.06%  |
| Unknown        | 13       | 6.95%   |
| 301-350        | 12       | 6.42%   |
| More than 1000 | 9        | 4.81%   |
| 351-500        | 5        | 2.67%   |
| 501-1000       | 4        | 2.14%   |
| 251-300        | 2        | 1.07%   |
| 121-130        | 1        | 0.53%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 132      | 71.35%  |
| 101-120 | 28       | 15.14%  |
| Unknown | 13       | 7.03%   |
| 1-50    | 10       | 5.41%   |
| 121-160 | 2        | 1.08%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 170      | 87.18%  |
| 2     | 12       | 6.15%   |
| 0     | 11       | 5.64%   |
| 3     | 2        | 1.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 130      | 52.42%  |
| Intel                           | 40       | 16.13%  |
| Qualcomm Atheros                | 25       | 10.08%  |
| Ralink Technology               | 10       | 4.03%   |
| Nvidia                          | 7        | 2.82%   |
| Qualcomm Atheros Communications | 5        | 2.02%   |
| VIA Technologies                | 4        | 1.61%   |
| Huawei Technologies             | 4        | 1.61%   |
| Marvell Technology Group        | 3        | 1.21%   |
| D-Link                          | 3        | 1.21%   |
| Samsung Electronics             | 2        | 0.81%   |
| MediaTek                        | 2        | 0.81%   |
| Broadcom Limited                | 2        | 0.81%   |
| ZTE WCDMA Technologies MSM      | 1        | 0.4%    |
| Xiaomi                          | 1        | 0.4%    |
| TP-Link                         | 1        | 0.4%    |
| STMicroelectronics              | 1        | 0.4%    |
| Ralink                          | 1        | 0.4%    |
| Philips (or NXP)                | 1        | 0.4%    |
| Mellanox Technologies           | 1        | 0.4%    |
| JMicron Technology              | 1        | 0.4%    |
| HTC (High Tech Computer)        | 1        | 0.4%    |
| Broadcom                        | 1        | 0.4%    |
| Accton Technology               | 1        | 0.4%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 97       | 37.02%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 17       | 6.49%   |
| Intel Ethernet Connection (2) I219-V                              | 7        | 2.67%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 5        | 1.91%   |
| Ralink RT5370 Wireless Adapter                                    | 5        | 1.91%   |
| Qualcomm Atheros AR9271 802.11n                                   | 5        | 1.91%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 4        | 1.53%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4        | 1.53%   |
| Ralink MT7601U Wireless Adapter                                   | 4        | 1.53%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 4        | 1.53%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 4        | 1.53%   |
| Intel 82579V Gigabit Network Connection                           | 4        | 1.53%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 3        | 1.15%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 1.15%   |
| Intel Ethernet Controller I225-V                                  | 3        | 1.15%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 1.15%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 1.15%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 3        | 1.15%   |
| Huawei E353/E3131                                                 | 3        | 1.15%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 2        | 0.76%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 2        | 0.76%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2        | 0.76%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 2        | 0.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 0.76%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter        | 2        | 0.76%   |
| Nvidia CK804 Ethernet Controller                                  | 2        | 0.76%   |
| Intel I211 Gigabit Network Connection                             | 2        | 0.76%   |
| Intel Ethernet Connection I217-V                                  | 2        | 0.76%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 0.76%   |
| Intel 82566DC Gigabit Network Connection                          | 2        | 0.76%   |
| ZTE WCDMA MSM USB SCSI CD-ROM                                     | 1        | 0.38%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.38%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1        | 0.38%   |
| STMicroelectronics USB Watchdog                                   | 1        | 0.38%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 0.38%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.38%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 1        | 0.38%   |
| Realtek RTL8187 Wireless Adapter                                  | 1        | 0.38%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller         | 1        | 0.38%   |
| Realtek RTL-8129                                                  | 1        | 0.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 11       | 22%     |
| Ralink Technology               | 10       | 20%     |
| Qualcomm Atheros                | 10       | 20%     |
| Intel                           | 6        | 12%     |
| Qualcomm Atheros Communications | 5        | 10%     |
| D-Link                          | 3        | 6%      |
| TP-Link                         | 1        | 2%      |
| Ralink                          | 1        | 2%      |
| Philips (or NXP)                | 1        | 2%      |
| MediaTek                        | 1        | 2%      |
| Accton Technology               | 1        | 2%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 5        | 10%     |
| Ralink RT5370 Wireless Adapter                                                | 5        | 10%     |
| Qualcomm Atheros AR9271 802.11n                                               | 5        | 10%     |
| Ralink MT7601U Wireless Adapter                                               | 4        | 8%      |
| Realtek RTL8188EE Wireless Network Adapter                                    | 3        | 6%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 2        | 4%      |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 2        | 4%      |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                    | 2        | 4%      |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 1        | 2%      |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                               | 1        | 2%      |
| Realtek RTL8187 Wireless Adapter                                              | 1        | 2%      |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                     | 1        | 2%      |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1        | 2%      |
| Ralink RT3062 Wireless 802.11n 2T/2R                                          | 1        | 2%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1        | 2%      |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1        | 2%      |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 1        | 2%      |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1        | 2%      |
| Philips (or NXP) PTA-128                                                      | 1        | 2%      |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                 | 1        | 2%      |
| Intel Wireless 8260                                                           | 1        | 2%      |
| Intel Wireless 7265                                                           | 1        | 2%      |
| Intel Wi-Fi 6 AX201 160MHz                                                    | 1        | 2%      |
| Intel Wi-Fi 6 AX200                                                           | 1        | 2%      |
| Intel Comet Lake PCH CNVi WiFi                                                | 1        | 2%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 1        | 2%      |
| D-Link DWA-137 Wireless N High-Gain Adapter [Ralink RT5372]                   | 1        | 2%      |
| D-Link AirPlus G DWL-G122 Wireless Adapter(rev.B1) [Ralink RT2571]            | 1        | 2%      |
| D-Link 802.11 n WLAN                                                          | 1        | 2%      |
| Accton WN7512BEP Wireless LAN adapter                                         | 1        | 2%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Realtek Semiconductor      | 126      | 61.76%  |
| Intel                      | 37       | 18.14%  |
| Qualcomm Atheros           | 15       | 7.35%   |
| Nvidia                     | 7        | 3.43%   |
| VIA Technologies           | 4        | 1.96%   |
| Marvell Technology Group   | 3        | 1.47%   |
| Huawei Technologies        | 3        | 1.47%   |
| Broadcom Limited           | 2        | 0.98%   |
| ZTE WCDMA Technologies MSM | 1        | 0.49%   |
| Xiaomi                     | 1        | 0.49%   |
| Samsung Electronics        | 1        | 0.49%   |
| MediaTek                   | 1        | 0.49%   |
| JMicron Technology         | 1        | 0.49%   |
| HTC (High Tech Computer)   | 1        | 0.49%   |
| Broadcom                   | 1        | 0.49%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 97       | 46.63%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 17       | 8.17%   |
| Intel Ethernet Connection (2) I219-V                              | 7        | 3.37%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 4        | 1.92%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4        | 1.92%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 4        | 1.92%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 4        | 1.92%   |
| Intel 82579V Gigabit Network Connection                           | 4        | 1.92%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 1.44%   |
| Intel Ethernet Controller I225-V                                  | 3        | 1.44%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 1.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 1.44%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 3        | 1.44%   |
| Huawei E353/E3131                                                 | 3        | 1.44%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 2        | 0.96%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 2        | 0.96%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 0.96%   |
| Nvidia CK804 Ethernet Controller                                  | 2        | 0.96%   |
| Intel I211 Gigabit Network Connection                             | 2        | 0.96%   |
| Intel Ethernet Connection I217-V                                  | 2        | 0.96%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 0.96%   |
| Intel 82566DC Gigabit Network Connection                          | 2        | 0.96%   |
| ZTE WCDMA MSM USB SCSI CD-ROM                                     | 1        | 0.48%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.48%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.48%   |
| Realtek RTL-8129                                                  | 1        | 0.48%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.48%   |
| Realtek RTL-8029(AS)                                              | 1        | 0.48%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1        | 0.48%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 0.48%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 0.48%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.48%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1        | 0.48%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.48%   |
| Nvidia MCP77 Ethernet                                             | 1        | 0.48%   |
| Nvidia MCP73 Ethernet                                             | 1        | 0.48%   |
| Nvidia MCP61 Ethernet                                             | 1        | 0.48%   |
| Nvidia MCP55 Ethernet                                             | 1        | 0.48%   |
| Nvidia MCP51 Ethernet Controller                                  | 1        | 0.48%   |
| MediaTek Titan pocket                                             | 1        | 0.48%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 190      | 78.84%  |
| WiFi     | 48       | 19.92%  |
| Modem    | 2        | 0.83%   |
| Unknown  | 1        | 0.41%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 152      | 81.72%  |
| WiFi     | 34       | 18.28%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 159      | 83.68%  |
| 2     | 28       | 14.74%  |
| 5     | 1        | 0.53%   |
| 4     | 1        | 0.53%   |
| 3     | 1        | 0.53%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 190      | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Cambridge Silicon Radio    | 8        | 42.11%  |
| Intel                      | 5        | 26.32%  |
| Realtek Semiconductor      | 2        | 10.53%  |
| Integrated System Solution | 2        | 10.53%  |
| Logitech                   | 1        | 5.26%   |
| Foxconn / Hon Hai          | 1        | 5.26%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 8        | 42.11%  |
| Realtek Bluetooth Radio                             | 2        | 10.53%  |
| Intel Bluetooth wireless interface                  | 2        | 10.53%  |
| Intel AX201 Bluetooth                               | 2        | 10.53%  |
| Integrated System Solution Bluetooth Device         | 2        | 10.53%  |
| Logitech BT Mini-Receiver (HCI mode)                | 1        | 5.26%   |
| Intel AX200 Bluetooth                               | 1        | 5.26%   |
| Foxconn / Hon Hai Wireless_Device                   | 1        | 5.26%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 161      | 48.94%  |
| Nvidia                   | 103      | 31.31%  |
| AMD                      | 34       | 10.33%  |
| C-Media Electronics      | 8        | 2.43%   |
| ASUSTek Computer         | 3        | 0.91%   |
| VIA Technologies         | 2        | 0.61%   |
| Sony                     | 2        | 0.61%   |
| Creative Labs            | 2        | 0.61%   |
| Xilinx                   | 1        | 0.3%    |
| ULi Electronics          | 1        | 0.3%    |
| SAVITECH                 | 1        | 0.3%    |
| Realtek Semiconductor    | 1        | 0.3%    |
| Razer USA                | 1        | 0.3%    |
| Plantronics              | 1        | 0.3%    |
| Logitech                 | 1        | 0.3%    |
| JMTek                    | 1        | 0.3%    |
| Hewlett-Packard          | 1        | 0.3%    |
| Generalplus Technology   | 1        | 0.3%    |
| Focusrite-Novation       | 1        | 0.3%    |
| Blue Microphones         | 1        | 0.3%    |
| BEHRINGER International  | 1        | 0.3%    |
| Asahi Kasei Microsystems | 1        | 0.3%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 32       | 9.2%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 31       | 8.91%   |
| Nvidia GF108 High Definition Audio Controller                              | 21       | 6.03%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 15       | 4.31%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 14       | 4.02%   |
| Nvidia High Definition Audio Controller                                    | 13       | 3.74%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 13       | 3.74%   |
| Nvidia GK107 HDMI Audio Controller                                         | 10       | 2.87%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 9        | 2.59%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 8        | 2.3%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 7        | 2.01%   |
| Nvidia GF114 HDMI Audio Controller                                         | 7        | 2.01%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6        | 1.72%   |
| Intel 200 Series PCH HD Audio                                              | 6        | 1.72%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 6        | 1.72%   |
| Nvidia GF116 High Definition Audio Controller                              | 5        | 1.44%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                             | 5        | 1.44%   |
| Nvidia GP104 High Definition Audio Controller                              | 4        | 1.15%   |
| Nvidia GF119 HDMI Audio Controller                                         | 4        | 1.15%   |
| Intel Cannon Lake PCH cAVS                                                 | 4        | 1.15%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 4        | 1.15%   |
| AMD Starship/Matisse HD Audio Controller                                   | 4        | 1.15%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4        | 1.15%   |
| Nvidia TU106 High Definition Audio Controller                              | 3        | 0.86%   |
| Nvidia GT216 HDMI Audio Controller                                         | 3        | 0.86%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3        | 0.86%   |
| Nvidia GM206 High Definition Audio Controller                              | 3        | 0.86%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3        | 0.86%   |
| Nvidia GK104 HDMI Audio Controller                                         | 3        | 0.86%   |
| Nvidia GA106 High Definition Audio Controller                              | 3        | 0.86%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3        | 0.86%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3        | 0.86%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 3        | 0.86%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 3        | 0.86%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3        | 0.86%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3        | 0.86%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3        | 0.86%   |
| Sony DualShock 4 [CUH-ZCT2x]                                               | 2        | 0.57%   |
| Nvidia TU116 High Definition Audio Controller                              | 2        | 0.57%   |
| Nvidia MCP61 High Definition Audio                                         | 2        | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 93       | 46.5%   |
| Kingston            | 26       | 13%     |
| Transcend           | 13       | 6.5%    |
| Silicon Power       | 6        | 3%      |
| GeIL                | 6        | 3%      |
| Crucial             | 6        | 3%      |
| Apacer              | 6        | 3%      |
| Team                | 5        | 2.5%    |
| SK hynix            | 5        | 2.5%    |
| Samsung Electronics | 5        | 2.5%    |
| G.Skill             | 5        | 2.5%    |
| A-DATA Technology   | 5        | 2.5%    |
| Patriot             | 4        | 2%      |
| Micron Technology   | 3        | 1.5%    |
| Super Talent        | 2        | 1%      |
| SUPER KINGSTEK      | 2        | 1%      |
| Goodram             | 2        | 1%      |
| Kllisre             | 1        | 0.5%    |
| Kingmax             | 1        | 0.5%    |
| KANMEIQi            | 1        | 0.5%    |
| Goldkey             | 1        | 0.5%    |
| Corsair             | 1        | 0.5%    |
| Unknown             | 1        | 0.5%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                  | 12       | 5.36%   |
| Unknown RAM Module 1024MB DIMM SDRAM                  | 10       | 4.46%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                | 7        | 3.13%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s          | 6        | 2.68%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                | 5        | 2.23%   |
| Unknown RAM Module 2GB DIMM 800MT/s                   | 4        | 1.79%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s           | 4        | 1.79%   |
| Transcend RAM JM1333KLU-2G 2GB DIMM DDR3 1333MT/s     | 4        | 1.79%   |
| GeIL RAM CL9-9-9 D3-1333 8GB DIMM DDR3 1333MT/s       | 4        | 1.79%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s              | 3        | 1.34%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s               | 3        | 1.34%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                | 3        | 1.34%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s             | 2        | 0.89%   |
| Unknown RAM Module 4096MB DIMM DDR3 1067MT/s          | 2        | 0.89%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s               | 2        | 0.89%   |
| Unknown RAM Module 2GB DIMM 400MT/s                   | 2        | 0.89%   |
| Unknown RAM Module 2048MB DIMM DDR3 1067MT/s          | 2        | 0.89%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s           | 2        | 0.89%   |
| Unknown RAM Module 2048MB DIMM DDR 667MT/s            | 2        | 0.89%   |
| Unknown RAM Module 2048MB DIMM DDR 1333MT/s           | 2        | 0.89%   |
| Unknown RAM Module 2048MB DIMM 5354MT/s               | 2        | 0.89%   |
| Unknown RAM Module 1024MB DIMM DDR2                   | 2        | 0.89%   |
| Transcend RAM JM1333KLN-4G 4096MB DIMM SDRAM 1600MT/s | 2        | 0.89%   |
| Super Talent RAM SUPERTALENT02 4GB DIMM DDR3 1600MT/s | 2        | 0.89%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s  | 2        | 0.89%   |
| Silicon Power RAM DBLT2GN568S 2GB DIMM DDR3 1333MT/s  | 2        | 0.89%   |
| A-DATA RAM Module 4096MB DIMM DDR3 1333MT/s           | 2        | 0.89%   |
| Unknown RAM Module 8192MB DIMM 1600MT/s               | 1        | 0.45%   |
| Unknown RAM Module 512MB DIMM SDRAM                   | 1        | 0.45%   |
| Unknown RAM Module 512MB DIMM DDR2                    | 1        | 0.45%   |
| Unknown RAM Module 512MB DIMM DDR                     | 1        | 0.45%   |
| Unknown RAM Module 512MB DIMM 667MT/s                 | 1        | 0.45%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s             | 1        | 0.45%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s          | 1        | 0.45%   |
| Unknown RAM Module 4096MB DIMM DDR3 1400MT/s          | 1        | 0.45%   |
| Unknown RAM Module 4096MB DIMM 400MT/s                | 1        | 0.45%   |
| Unknown RAM Module 4096MB DIMM 2020MT/s               | 1        | 0.45%   |
| Unknown RAM Module 4096MB DIMM 1066MT/s               | 1        | 0.45%   |
| Unknown RAM Module 2GB DIMM SDRAM                     | 1        | 0.45%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s             | 1        | 0.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 64       | 37.21%  |
| Unknown | 35       | 20.35%  |
| DDR4    | 27       | 15.7%   |
| SDRAM   | 24       | 13.95%  |
| DDR2    | 15       | 8.72%   |
| DDR     | 5        | 2.91%   |
| LPDDR4  | 1        | 0.58%   |
| DDR5    | 1        | 0.58%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 164      | 97.04%  |
| SODIMM       | 3        | 1.78%   |
| Row Of Chips | 1        | 0.59%   |
| FB-DIMM      | 1        | 0.59%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 72       | 35.12%  |
| 4096  | 46       | 22.44%  |
| 8192  | 37       | 18.05%  |
| 1024  | 32       | 15.61%  |
| 16384 | 8        | 3.9%    |
| 512   | 5        | 2.44%   |
| 32768 | 4        | 1.95%   |
| 256   | 1        | 0.49%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1333    | 40       | 21.28%  |
| 1600    | 29       | 15.43%  |
| Unknown | 28       | 14.89%  |
| 800     | 21       | 11.17%  |
| 667     | 10       | 5.32%   |
| 2400    | 7        | 3.72%   |
| 3200    | 5        | 2.66%   |
| 2667    | 5        | 2.66%   |
| 1067    | 4        | 2.13%   |
| 533     | 4        | 2.13%   |
| 400     | 4        | 2.13%   |
| 3600    | 3        | 1.6%    |
| 2666    | 3        | 1.6%    |
| 2133    | 3        | 1.6%    |
| 1066    | 3        | 1.6%    |
| 5354    | 2        | 1.06%   |
| 3800    | 2        | 1.06%   |
| 5200    | 1        | 0.53%   |
| 3733    | 1        | 0.53%   |
| 3334    | 1        | 0.53%   |
| 3266    | 1        | 0.53%   |
| 3000    | 1        | 0.53%   |
| 2933    | 1        | 0.53%   |
| 2448    | 1        | 0.53%   |
| 2020    | 1        | 0.53%   |
| 1867    | 1        | 0.53%   |
| 1800    | 1        | 0.53%   |
| 1666    | 1        | 0.53%   |
| 1400    | 1        | 0.53%   |
| 1334    | 1        | 0.53%   |
| 1258    | 1        | 0.53%   |
| 66      | 1        | 0.53%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 5        | 41.67%  |
| Canon               | 3        | 25%     |
| Xerox               | 2        | 16.67%  |
| Samsung Electronics | 2        | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Xerox Phaser 3160                       | 1        | 8.33%   |
| Xerox Phaser 3020                       | 1        | 8.33%   |
| Samsung Xerox Phaser 3117 Laser Printer | 1        | 8.33%   |
| Samsung CLX-3180 Series                 | 1        | 8.33%   |
| HP LaserJet P1102                       | 1        | 8.33%   |
| HP LaserJet 1018                        | 1        | 8.33%   |
| HP LaserJet 1010                        | 1        | 8.33%   |
| HP DeskJet 5650c                        | 1        | 8.33%   |
| HP Deskjet 2520 series                  | 1        | 8.33%   |
| Canon LBP810                            | 1        | 8.33%   |
| Canon LBP6000                           | 1        | 8.33%   |
| Canon LBP2900                           | 1        | 8.33%   |

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Logitech                    | 11       | 21.15%  |
| Z-Star Microelectronics     | 9        | 17.31%  |
| KYE Systems (Mouse Systems) | 9        | 17.31%  |
| Microdia                    | 4        | 7.69%   |
| Pixart Imaging              | 3        | 5.77%   |
| SiGma Micro                 | 2        | 3.85%   |
| Samsung Electronics         | 2        | 3.85%   |
| Hewlett-Packard             | 2        | 3.85%   |
| GEMBIRD                     | 2        | 3.85%   |
| OPPO Electronics            | 1        | 1.92%   |
| Generalplus Technology      | 1        | 1.92%   |
| Creative Technology         | 1        | 1.92%   |
| Chicony Electronics         | 1        | 1.92%   |
| Aveo Technology             | 1        | 1.92%   |
| Apple                       | 1        | 1.92%   |
| Alcor Micro                 | 1        | 1.92%   |
| A4Tech                      | 1        | 1.92%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Z-Star Venus USB2.0 Camera                     | 6        | 11.54%  |
| Logitech Webcam C270                           | 4        | 7.69%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro           | 3        | 5.77%   |
| Logitech Webcam C170                           | 3        | 5.77%   |
| KYE Systems (Mouse Systems) Genius iSlim 330   | 3        | 5.77%   |
| SiGma Micro WebCam SiGma Micro                 | 2        | 3.85%   |
| Samsung Galaxy series, misc. (MTP mode)        | 2        | 3.85%   |
| Microdia Sonix USB 2.0 Camera                  | 2        | 3.85%   |
| GEMBIRD USB2.0 PC CAMERA                       | 2        | 3.85%   |
| Z-Star Vimicro USB Camera (Altair)             | 1        | 1.92%   |
| Z-Star Sirius USB2.0 Camera                    | 1        | 1.92%   |
| Z-Star Lenovo IdeaCentre Web Camera            | 1        | 1.92%   |
| OPPO Oppo N1                                   | 1        | 1.92%   |
| Microdia MSI Starcam Racer                     | 1        | 1.92%   |
| Microdia Camera                                | 1        | 1.92%   |
| Logitech Webcam C310                           | 1        | 1.92%   |
| Logitech Webcam C210                           | 1        | 1.92%   |
| Logitech Webcam C200                           | 1        | 1.92%   |
| Logitech HD Webcam C510                        | 1        | 1.92%   |
| KYE Systems (Mouse Systems) USB20 Camera       | 1        | 1.92%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera     | 1        | 1.92%   |
| KYE Systems (Mouse Systems) iSlim 1300 V2      | 1        | 1.92%   |
| KYE Systems (Mouse Systems) Genius Webcam      | 1        | 1.92%   |
| KYE Systems (Mouse Systems) Genius FaceCam 312 | 1        | 1.92%   |
| KYE Systems (Mouse Systems) FaceCam 315        | 1        | 1.92%   |
| HP Webcam HD-2200                              | 1        | 1.92%   |
| HP Webcam HD 2300                              | 1        | 1.92%   |
| Generalplus 808 Camera #9 (web-cam mode)       | 1        | 1.92%   |
| Creative Live! Cam Chat HD [VF0700]            | 1        | 1.92%   |
| Chicony HP High Definition 1MP Webcam          | 1        | 1.92%   |
| Aveo USB2.0 Camera                             | 1        | 1.92%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                | 1        | 1.92%   |
| Alcor Micro USB 2.0 PC Camera                  | 1        | 1.92%   |
| A4Tech FHD 1080P PC Camera                     | 1        | 1.92%   |

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


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Aktiv                 | 1        | 50%     |
| Advanced Card Systems | 1        | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Aktiv KAZTOKEN                               | 1        | 50%     |
| Advanced Card Systems ACR38 SmartCard Reader | 1        | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 177      | 90.31%  |
| 1     | 15       | 7.65%   |
| 2     | 3        | 1.53%   |
| 3     | 1        | 0.51%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 11       | 47.83%  |
| Communication controller | 5        | 21.74%  |
| Camera                   | 3        | 13.04%  |
| Unassigned class         | 1        | 4.35%   |
| Net/ethernet             | 1        | 4.35%   |
| Multimedia controller    | 1        | 4.35%   |
| Chipcard                 | 1        | 4.35%   |

