BunsenLabs - Tested Hardware & Statistics
-----------------------------------------

A project to collect tested hardware configurations for BunsenLabs.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/BunsenLabs/Desktop/README.md) and [notebooks](/Dist/BunsenLabs/Notebook/README.md).

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

Total: 164

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T470p 20J6003KU... | Notebook    | [624bca4c57](https://linux-hardware.org/?probe=624bca4c57) | Dec 23, 2024 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [79f63e6159](https://linux-hardware.org/?probe=79f63e6159) | Dec 06, 2024 |
| ASUSTek       | X99-E WS/USB                | Desktop     | [227a25d82a](https://linux-hardware.org/?probe=227a25d82a) | Nov 09, 2024 |
| Dell          | 02K9CR A02                  | Desktop     | [9ff0a28a93](https://linux-hardware.org/?probe=9ff0a28a93) | Nov 02, 2024 |
| ASUSTek       | N501VW                      | Notebook    | [c80d222867](https://linux-hardware.org/?probe=c80d222867) | Sep 07, 2024 |
| Lenovo        | IdeaPad S410p 20296         | Notebook    | [442752ea3a](https://linux-hardware.org/?probe=442752ea3a) | Jul 28, 2024 |
| Acer          | Aspire A315-35              | Notebook    | [b0dd66f64e](https://linux-hardware.org/?probe=b0dd66f64e) | Jul 19, 2024 |
| Dell          | Vostro 3500                 | Notebook    | [ec7ac57ad8](https://linux-hardware.org/?probe=ec7ac57ad8) | Jun 13, 2024 |
| Matsushita... | CF-74GCDADBM                | Notebook    | [f353aa5d7c](https://linux-hardware.org/?probe=f353aa5d7c) | May 08, 2024 |
| MSI           | A55M-P33                    | Desktop     | [0f6fc5a77e](https://linux-hardware.org/?probe=0f6fc5a77e) | Apr 17, 2024 |
| Acer          | Aspire E5-475               | Notebook    | [31e70b6cc1](https://linux-hardware.org/?probe=31e70b6cc1) | Apr 08, 2024 |
| Lenovo        | ThinkPad R400 7440WWQ       | Notebook    | [7c62efd0a5](https://linux-hardware.org/?probe=7c62efd0a5) | Mar 29, 2024 |
| Acer          | Aspire E5-575G              | Notebook    | [97fc633522](https://linux-hardware.org/?probe=97fc633522) | Mar 01, 2024 |
| IBM           | ThinkPad T43 18714AG        | Notebook    | [ac4a5c44a6](https://linux-hardware.org/?probe=ac4a5c44a6) | Feb 28, 2024 |
| ASUSTek       | K53SJ                       | Notebook    | [cb9c23cca6](https://linux-hardware.org/?probe=cb9c23cca6) | Feb 16, 2024 |
| Lenovo        | ThinkPad X60 Tablet 6365... | Notebook    | [f2277d87a7](https://linux-hardware.org/?probe=f2277d87a7) | Feb 04, 2024 |
| MSI           | 760GMA-P34                  | Desktop     | [0c0fde4ed3](https://linux-hardware.org/?probe=0c0fde4ed3) | Jan 28, 2024 |
| Toshiba       | Satellite P50T-A-114        | Notebook    | [5286decec5](https://linux-hardware.org/?probe=5286decec5) | Jan 26, 2024 |
| ASUSTek       | X75VCP                      | Notebook    | [63c2472460](https://linux-hardware.org/?probe=63c2472460) | Jan 21, 2024 |
| Gateway       | MT6707                      | Notebook    | [581410ddec](https://linux-hardware.org/?probe=581410ddec) | Jan 21, 2024 |
| HP            | 255 G3                      | Notebook    | [7f8af802a0](https://linux-hardware.org/?probe=7f8af802a0) | Jan 15, 2024 |
| Sony          | VPCEH2J1E                   | Notebook    | [39cd4a0364](https://linux-hardware.org/?probe=39cd4a0364) | Jan 08, 2024 |
| Apple         | Mac-F2268DAE                | All in one  | [913b232ab9](https://linux-hardware.org/?probe=913b232ab9) | Jan 03, 2024 |
| IBM           | ThinkPad X41 2525WB1        | Notebook    | [fe73b9a704](https://linux-hardware.org/?probe=fe73b9a704) | Jan 02, 2024 |
| Gateway       | MT6707                      | Notebook    | [a2a87f6e95](https://linux-hardware.org/?probe=a2a87f6e95) | Jan 02, 2024 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | Notebook    | [d178358ee1](https://linux-hardware.org/?probe=d178358ee1) | Dec 21, 2023 |
| Fujitsu       | LIFEBOOK U745               | Notebook    | [a2f7b09b87](https://linux-hardware.org/?probe=a2f7b09b87) | Dec 20, 2023 |
| HP            | Mini 2102                   | Notebook    | [33a330f96d](https://linux-hardware.org/?probe=33a330f96d) | Dec 16, 2023 |
| Sony          | VPCEG18FG                   | Notebook    | [e1b5fa6cac](https://linux-hardware.org/?probe=e1b5fa6cac) | Dec 15, 2023 |
| Lenovo        | V110-14IAP 80TF             | Notebook    | [e7bbe1d5e7](https://linux-hardware.org/?probe=e7bbe1d5e7) | Dec 10, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [34a16ab09d](https://linux-hardware.org/?probe=34a16ab09d) | Dec 06, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [9388f41e11](https://linux-hardware.org/?probe=9388f41e11) | Nov 25, 2023 |
| Google        | Kefka                       | Notebook    | [7522f0b2f5](https://linux-hardware.org/?probe=7522f0b2f5) | Nov 20, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [f91d973bab](https://linux-hardware.org/?probe=f91d973bab) | Nov 19, 2023 |
| Google        | Peppy                       | Notebook    | [8276e5d349](https://linux-hardware.org/?probe=8276e5d349) | Oct 26, 2023 |
| Acer          | AOA110                      | Notebook    | [e263461ae3](https://linux-hardware.org/?probe=e263461ae3) | Oct 21, 2023 |
| Sony          | VPCSB2L1R                   | Notebook    | [153440d631](https://linux-hardware.org/?probe=153440d631) | Oct 20, 2023 |
| Dell          | 05DN3X A00                  | Desktop     | [7bb927bf32](https://linux-hardware.org/?probe=7bb927bf32) | Oct 10, 2023 |
| Lenovo        | G700 20251                  | Notebook    | [7988ecce03](https://linux-hardware.org/?probe=7988ecce03) | Oct 06, 2023 |
| Matsushita... | CF-74GCDADBM                | Notebook    | [81dda6dc09](https://linux-hardware.org/?probe=81dda6dc09) | Oct 05, 2023 |
| Google        | Caroline                    | Notebook    | [f4fba894c3](https://linux-hardware.org/?probe=f4fba894c3) | Oct 02, 2023 |
| Lenovo        | ThinkPad P53 20QNS00X00     | Notebook    | [d8a932e703](https://linux-hardware.org/?probe=d8a932e703) | Oct 02, 2023 |
| HP            | Compaq nc6320 (EN368UT#A... | Notebook    | [71ba4fd9e9](https://linux-hardware.org/?probe=71ba4fd9e9) | Sep 30, 2023 |
| Sony          | VPCSB2L1R                   | Notebook    | [9395b9347e](https://linux-hardware.org/?probe=9395b9347e) | Sep 26, 2023 |
| Dell          | Latitude E4300              | Notebook    | [ed27d2d51c](https://linux-hardware.org/?probe=ed27d2d51c) | Sep 13, 2023 |
| Google        | Droid                       | Notebook    | [7b7eb437c6](https://linux-hardware.org/?probe=7b7eb437c6) | Sep 12, 2023 |
| Compaq Pre... | DC477A-ABA S3100NX NA110    | Desktop     | [8998682eb4](https://linux-hardware.org/?probe=8998682eb4) | Sep 08, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | Notebook    | [b065e9bda2](https://linux-hardware.org/?probe=b065e9bda2) | Aug 31, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [bb8b8a594d](https://linux-hardware.org/?probe=bb8b8a594d) | Aug 27, 2023 |
| Lenovo        | ThinkPad T440s 20AR003RM... | Notebook    | [f8f097e135](https://linux-hardware.org/?probe=f8f097e135) | Aug 24, 2023 |
| HP            | 18E7                        | Desktop     | [7c200916bf](https://linux-hardware.org/?probe=7c200916bf) | Aug 22, 2023 |
| HP            | 18E7                        | Desktop     | [6cd6ef6396](https://linux-hardware.org/?probe=6cd6ef6396) | Aug 22, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [c62fc8773a](https://linux-hardware.org/?probe=c62fc8773a) | Aug 21, 2023 |
| Lenovo        | ThinkPad T440s 20AR003RM... | Notebook    | [d989b68c65](https://linux-hardware.org/?probe=d989b68c65) | Aug 19, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [418fc8664d](https://linux-hardware.org/?probe=418fc8664d) | Aug 16, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | Notebook    | [8b2a34a407](https://linux-hardware.org/?probe=8b2a34a407) | Aug 11, 2023 |
| Sony          | VPCSB2L1R                   | Notebook    | [582f50ea25](https://linux-hardware.org/?probe=582f50ea25) | Aug 02, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [875ac8e861](https://linux-hardware.org/?probe=875ac8e861) | Jul 31, 2023 |
| Lenovo        | ThinkPad P53 20QNS00X00     | Notebook    | [c196e05843](https://linux-hardware.org/?probe=c196e05843) | Jul 19, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | Notebook    | [5561d22542](https://linux-hardware.org/?probe=5561d22542) | Jul 13, 2023 |
| Lenovo        | ThinkPad P53 20QNS00X00     | Notebook    | [1e9dbff4e1](https://linux-hardware.org/?probe=1e9dbff4e1) | Jul 12, 2023 |
| IBM           | ThinkPad T43 18714AG        | Notebook    | [c7d3e6a151](https://linux-hardware.org/?probe=c7d3e6a151) | Jul 09, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | Notebook    | [5de59f9db1](https://linux-hardware.org/?probe=5de59f9db1) | Jul 04, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | Notebook    | [d8bf0be74c](https://linux-hardware.org/?probe=d8bf0be74c) | Jul 02, 2023 |
| Lenovo        | ThinkPad P53 20QNS00X00     | Notebook    | [696e673b71](https://linux-hardware.org/?probe=696e673b71) | Jun 19, 2023 |
| Google        | Ampton                      | Notebook    | [294fa26d20](https://linux-hardware.org/?probe=294fa26d20) | Jun 14, 2023 |
| Lenovo        | ThinkPad P53 20QNS00X00     | Notebook    | [aa551ee6d7](https://linux-hardware.org/?probe=aa551ee6d7) | Jun 12, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [5473496916](https://linux-hardware.org/?probe=5473496916) | May 30, 2023 |
| HP            | ZBook 15                    | Notebook    | [def4482b86](https://linux-hardware.org/?probe=def4482b86) | May 25, 2023 |
| Google        | Snappy                      | Notebook    | [8e9ad9e9d3](https://linux-hardware.org/?probe=8e9ad9e9d3) | May 24, 2023 |
| Advent        | Roma                        | Notebook    | [f6ca4c331a](https://linux-hardware.org/?probe=f6ca4c331a) | May 19, 2023 |
| Google        | Banon                       | Notebook    | [c610295744](https://linux-hardware.org/?probe=c610295744) | May 16, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | Notebook    | [53a5e2e7d7](https://linux-hardware.org/?probe=53a5e2e7d7) | May 16, 2023 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [81711fd069](https://linux-hardware.org/?probe=81711fd069) | May 11, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [26740c6d26](https://linux-hardware.org/?probe=26740c6d26) | May 10, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | Notebook    | [4c3f70e8d3](https://linux-hardware.org/?probe=4c3f70e8d3) | May 08, 2023 |
| Chuwi         | HeroBook Air                | Notebook    | [872196fb37](https://linux-hardware.org/?probe=872196fb37) | May 06, 2023 |
| Advent        | Roma                        | Notebook    | [ec7568545d](https://linux-hardware.org/?probe=ec7568545d) | May 02, 2023 |
| Google        | Bobba                       | Notebook    | [5eb10d8965](https://linux-hardware.org/?probe=5eb10d8965) | Apr 26, 2023 |
| Dell          | System XPS L321X            | Notebook    | [cd2af9d26f](https://linux-hardware.org/?probe=cd2af9d26f) | Apr 24, 2023 |
| EVERCOM NE... | Unknown                     | Desktop     | [d36803f05d](https://linux-hardware.org/?probe=d36803f05d) | Apr 21, 2023 |
| Google        | Helios                      | Notebook    | [89b0a06d70](https://linux-hardware.org/?probe=89b0a06d70) | Apr 20, 2023 |
| LG Electro... | X120-G.C7VPG                | Notebook    | [2ba90d32b2](https://linux-hardware.org/?probe=2ba90d32b2) | Apr 16, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [e35ed3cb0d](https://linux-hardware.org/?probe=e35ed3cb0d) | Apr 10, 2023 |
| Google        | Ampton                      | Notebook    | [e3945d7727](https://linux-hardware.org/?probe=e3945d7727) | Apr 08, 2023 |
| Advent        | Roma                        | Notebook    | [e1bd64e5b5](https://linux-hardware.org/?probe=e1bd64e5b5) | Apr 03, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [c32ab093ae](https://linux-hardware.org/?probe=c32ab093ae) | Apr 01, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [aaeb2f2269](https://linux-hardware.org/?probe=aaeb2f2269) | Mar 29, 2023 |
| ASUSTek       | PN62                        | Mini pc     | [9cd806cb31](https://linux-hardware.org/?probe=9cd806cb31) | Mar 20, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [3bc67b4224](https://linux-hardware.org/?probe=3bc67b4224) | Mar 06, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [61e07fdff6](https://linux-hardware.org/?probe=61e07fdff6) | Mar 06, 2023 |
| HP            | Presario CQ62               | Notebook    | [560330ba8e](https://linux-hardware.org/?probe=560330ba8e) | Mar 03, 2023 |
| Toshiba       | QOSMIO X505                 | Notebook    | [ba222e690b](https://linux-hardware.org/?probe=ba222e690b) | Feb 25, 2023 |
| Toshiba       | QOSMIO X505                 | Notebook    | [8dd3063004](https://linux-hardware.org/?probe=8dd3063004) | Feb 25, 2023 |
| Acer          | AOD255                      | Notebook    | [f5f5ed9b36](https://linux-hardware.org/?probe=f5f5ed9b36) | Feb 24, 2023 |
| Acer          | AOD255                      | Notebook    | [b4ccf00506](https://linux-hardware.org/?probe=b4ccf00506) | Feb 23, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [381d9832ae](https://linux-hardware.org/?probe=381d9832ae) | Feb 19, 2023 |
| Dell          | Latitude 5480               | Notebook    | [e288a18f9d](https://linux-hardware.org/?probe=e288a18f9d) | Feb 18, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [7360e6e667](https://linux-hardware.org/?probe=7360e6e667) | Feb 17, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [28ac8fee12](https://linux-hardware.org/?probe=28ac8fee12) | Feb 14, 2023 |
| Intel         | D525MW AAE93082-401         | Desktop     | [6ab285c781](https://linux-hardware.org/?probe=6ab285c781) | Feb 13, 2023 |
| Google        | Candy                       | Notebook    | [b2f2862759](https://linux-hardware.org/?probe=b2f2862759) | Feb 13, 2023 |
| Dell          | Precision M4700             | Notebook    | [6c3746d120](https://linux-hardware.org/?probe=6c3746d120) | Feb 12, 2023 |
| Acer          | Aspire V3-572G              | Notebook    | [7b48d97053](https://linux-hardware.org/?probe=7b48d97053) | Feb 07, 2023 |
| Dell          | Precision M4700             | Notebook    | [c2075893d4](https://linux-hardware.org/?probe=c2075893d4) | Feb 05, 2023 |
| WinPAD 110... | I102A                       | Notebook    | [0619bb5a8d](https://linux-hardware.org/?probe=0619bb5a8d) | Feb 04, 2023 |
| Acer          | AOD255                      | Notebook    | [1b65896663](https://linux-hardware.org/?probe=1b65896663) | Feb 03, 2023 |
| Dell          | Latitude D630C              | Notebook    | [401357bc99](https://linux-hardware.org/?probe=401357bc99) | Jan 30, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [cb00a3e89d](https://linux-hardware.org/?probe=cb00a3e89d) | Jan 24, 2023 |
| ASUSTek       | K53SJ                       | Notebook    | [267ce15a0c](https://linux-hardware.org/?probe=267ce15a0c) | Jan 17, 2023 |
| ASUSTek       | E200HA                      | Notebook    | [4d9f4512a6](https://linux-hardware.org/?probe=4d9f4512a6) | Jan 13, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [2a71b87b09](https://linux-hardware.org/?probe=2a71b87b09) | Jan 11, 2023 |
| HP            | Compaq nc6320 (EN368UT#A... | Notebook    | [0a86f694f4](https://linux-hardware.org/?probe=0a86f694f4) | Jan 10, 2023 |
| Dell          | Inspiron 3543               | Notebook    | [c7c7419fd5](https://linux-hardware.org/?probe=c7c7419fd5) | Jan 10, 2023 |
| HP            | Compaq nc6320 (EN368UT#A... | Notebook    | [abd3d3cea6](https://linux-hardware.org/?probe=abd3d3cea6) | Jan 09, 2023 |
| Dell          | 0C3YXR A01                  | Desktop     | [01c2e9db45](https://linux-hardware.org/?probe=01c2e9db45) | Jan 06, 2023 |
| HP            | Mini 110-3100               | Notebook    | [fb7810e1f3](https://linux-hardware.org/?probe=fb7810e1f3) | Jan 02, 2023 |
| Dell          | Inspiron MM061              | Notebook    | [34804f8a34](https://linux-hardware.org/?probe=34804f8a34) | Dec 29, 2022 |
| MSI           | Summit E13FlipEvo A12MT     | Notebook    | [19d3221410](https://linux-hardware.org/?probe=19d3221410) | Dec 27, 2022 |
| HP            | 18E7                        | Desktop     | [260119e159](https://linux-hardware.org/?probe=260119e159) | Dec 25, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [ba03b3fbf5](https://linux-hardware.org/?probe=ba03b3fbf5) | Dec 24, 2022 |
| Acer          | Aspire ES1-111M             | Notebook    | [3b15bcfd88](https://linux-hardware.org/?probe=3b15bcfd88) | Nov 19, 2022 |
| ASUSTek       | P5SD2-VM                    | Desktop     | [6b5082a45c](https://linux-hardware.org/?probe=6b5082a45c) | Aug 12, 2022 |
| ASUSTek       | P5SD2-VM                    | Desktop     | [d77caddb55](https://linux-hardware.org/?probe=d77caddb55) | Aug 12, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [bcd53f4be6](https://linux-hardware.org/?probe=bcd53f4be6) | Apr 22, 2022 |
| Lenovo        | IdeaPad Z580                | Notebook    | [80a27aca02](https://linux-hardware.org/?probe=80a27aca02) | Mar 17, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [caf1f719f4](https://linux-hardware.org/?probe=caf1f719f4) | Mar 10, 2022 |
| Lenovo        | IdeaPad Z580                | Notebook    | [bfdd2f78ce](https://linux-hardware.org/?probe=bfdd2f78ce) | Feb 10, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [35772aa50a](https://linux-hardware.org/?probe=35772aa50a) | Dec 25, 2021 |
| Apple         | MacBookAir6,2               | Notebook    | [41d30a91a2](https://linux-hardware.org/?probe=41d30a91a2) | Dec 24, 2021 |
| ASUSTek       | Crosshair V Formula         | Desktop     | [44da1ea889](https://linux-hardware.org/?probe=44da1ea889) | Oct 13, 2021 |
| ASUSTek       | Crosshair V Formula         | Desktop     | [e693a453b1](https://linux-hardware.org/?probe=e693a453b1) | Oct 13, 2021 |
| Lenovo        | ThinkPad T430 23473T1       | Notebook    | [4c297ab486](https://linux-hardware.org/?probe=4c297ab486) | May 18, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [b866ec6925](https://linux-hardware.org/?probe=b866ec6925) | Apr 20, 2021 |
| Lenovo        | ThinkPad T440s 20AR003RM... | Notebook    | [286287736b](https://linux-hardware.org/?probe=286287736b) | Mar 31, 2021 |
| Lenovo        | ThinkPad T490 20N2000CMC    | Notebook    | [b23d98dd6a](https://linux-hardware.org/?probe=b23d98dd6a) | Feb 22, 2021 |
| ASRock        | H470M-ITX/ac                | Desktop     | [a5ffbca106](https://linux-hardware.org/?probe=a5ffbca106) | Feb 19, 2021 |
| ASUSTek       | T102HA                      | Notebook    | [781a13f986](https://linux-hardware.org/?probe=781a13f986) | Feb 19, 2021 |
| Lenovo        | ThinkPad T440s 20AR003RM... | Notebook    | [afdde38feb](https://linux-hardware.org/?probe=afdde38feb) | Jan 08, 2021 |
| Sony          | VGN-FW11L                   | Notebook    | [e99fe042af](https://linux-hardware.org/?probe=e99fe042af) | Jan 06, 2021 |
| Lenovo        | ThinkPad T440s 20AR003RM... | Notebook    | [435ab3dc8c](https://linux-hardware.org/?probe=435ab3dc8c) | Dec 15, 2020 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [c15b5deb6b](https://linux-hardware.org/?probe=c15b5deb6b) | Nov 23, 2020 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [a741e92e02](https://linux-hardware.org/?probe=a741e92e02) | Nov 09, 2020 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [0132b2328a](https://linux-hardware.org/?probe=0132b2328a) | Nov 09, 2020 |
| Lenovo        | ThinkPad L440 20ASS34900    | Notebook    | [0320af5232](https://linux-hardware.org/?probe=0320af5232) | Nov 08, 2020 |
| Lenovo        | ThinkPad T440s 20AR003RM... | Notebook    | [fbb029244c](https://linux-hardware.org/?probe=fbb029244c) | Nov 07, 2020 |
| Acer          | Aspire 3000                 | Notebook    | [7346c396c1](https://linux-hardware.org/?probe=7346c396c1) | Oct 26, 2020 |
| Lenovo        | ThinkPad T440s 20AR003RM... | Notebook    | [1726e5904b](https://linux-hardware.org/?probe=1726e5904b) | Sep 13, 2020 |
| ASUSTek       | P5K                         | Desktop     | [31dfecdf4a](https://linux-hardware.org/?probe=31dfecdf4a) | Aug 22, 2020 |
| ASUSTek       | P5K                         | Desktop     | [84d4137932](https://linux-hardware.org/?probe=84d4137932) | Aug 22, 2020 |
| Lenovo        | ThinkPad E570 20H50070IX    | Notebook    | [be328f1909](https://linux-hardware.org/?probe=be328f1909) | Aug 07, 2020 |
| Lenovo        | ThinkPad E570 20H50070IX    | Notebook    | [5faf3a72e0](https://linux-hardware.org/?probe=5faf3a72e0) | Aug 07, 2020 |
| Intel         | D946GZIS AAD66165-302       | Desktop     | [0fd4742ed7](https://linux-hardware.org/?probe=0fd4742ed7) | Jul 24, 2020 |
| Intel         | DB85FL AAG89861-201         | Desktop     | [337d604d5f](https://linux-hardware.org/?probe=337d604d5f) | Jul 14, 2020 |
| MSI           | MS-7093                     | Desktop     | [2adf367265](https://linux-hardware.org/?probe=2adf367265) | May 25, 2020 |
| MSI           | MS-7093                     | Desktop     | [306d3dc974](https://linux-hardware.org/?probe=306d3dc974) | May 25, 2020 |
| ASRock        | H81M-ITX                    | Desktop     | [c51735ee45](https://linux-hardware.org/?probe=c51735ee45) | Dec 21, 2019 |
| Samsung       | 275E4E/275E5E               | Notebook    | [b9b37f4a61](https://linux-hardware.org/?probe=b9b37f4a61) | Jul 01, 2019 |
| Samsung       | 275E4E/275E5E               | Notebook    | [26ec3bf654](https://linux-hardware.org/?probe=26ec3bf654) | Jun 29, 2019 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [cd9600fb67](https://linux-hardware.org/?probe=cd9600fb67) | Aug 28, 2017 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [18379ebd5c](https://linux-hardware.org/?probe=18379ebd5c) | Jun 30, 2017 |
| eMachines     | eME732Z                     | Notebook    | [684e63b609](https://linux-hardware.org/?probe=684e63b609) | May 26, 2017 |
| eMachines     | eME732Z                     | Notebook    | [bdc6400fbe](https://linux-hardware.org/?probe=bdc6400fbe) | May 25, 2017 |
| eMachines     | eME732Z                     | Notebook    | [2d931a211b](https://linux-hardware.org/?probe=2d931a211b) | May 02, 2016 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| BunsenLabs 11   | 75        | 61.98%  |
| BunsenLabs 10.5 | 20        | 16.53%  |
| BunsenLabs 12   | 15        | 12.4%   |
| BunsenLabs 9.8  | 5         | 4.13%   |
| BunsenLabs 8.7  | 2         | 1.65%   |
| BunsenLabs 10.0 | 2         | 1.65%   |
| BunsenLabs 8.4  | 1         | 0.83%   |
| BunsenLabs 10.4 | 1         | 0.83%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| BunsenLabs | 117       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                    | Computers | Percent |
|----------------------------|-----------|---------|
| 5.10.0-21-amd64            | 17        | 12.78%  |
| 5.10.0-20-amd64            | 17        | 12.78%  |
| 5.10.0-26-amd64            | 8         | 6.02%   |
| 5.10.0-23-amd64            | 8         | 6.02%   |
| 5.10.0-25-amd64            | 7         | 5.26%   |
| 5.10.0-21-686-pae          | 5         | 3.76%   |
| 6.1.0-18-amd64             | 4         | 3.01%   |
| 4.19.0-18-amd64            | 4         | 3.01%   |
| 5.10.0-27-amd64            | 3         | 2.26%   |
| 5.10.0-22-amd64            | 3         | 2.26%   |
| 6.1.0-26-amd64             | 2         | 1.5%    |
| 5.10.0-3-amd64             | 2         | 1.5%    |
| 5.10.0-26-686-pae          | 2         | 1.5%    |
| 5.10.0-20-686              | 2         | 1.5%    |
| 5.10.0-19-amd64            | 2         | 1.5%    |
| 4.9.0-9-amd64              | 2         | 1.5%    |
| 4.19.0-23-amd64            | 2         | 1.5%    |
| 3.16.0-4-amd64             | 2         | 1.5%    |
| 6.9.7+bpo-amd64            | 1         | 0.75%   |
| 6.6.7-zen1KernelZenv2-1    | 1         | 0.75%   |
| 6.11.11-x64v3-xanmod1      | 1         | 0.75%   |
| 6.1.0-7-amd64              | 1         | 0.75%   |
| 6.1.0-28-amd64             | 1         | 0.75%   |
| 6.1.0-23-amd64             | 1         | 0.75%   |
| 6.1.0-21-amd64             | 1         | 0.75%   |
| 6.1.0-16-amd64             | 1         | 0.75%   |
| 6.1.0-13-amd64             | 1         | 0.75%   |
| 6.1.0-13-686               | 1         | 0.75%   |
| 6.1.0-10-686               | 1         | 0.75%   |
| 5.9.0-3-amd64              | 1         | 0.75%   |
| 5.9.0-0.bpo.2-amd64        | 1         | 0.75%   |
| 5.8.0-0.bpo.2-amd64        | 1         | 0.75%   |
| 5.7.0-2-amd64              | 1         | 0.75%   |
| 5.7.0-0.bpo.2-amd64        | 1         | 0.75%   |
| 5.4.0-0.bpo.4-amd64        | 1         | 0.75%   |
| 5.4.0-0.bpo.3-amd64        | 1         | 0.75%   |
| 5.16.0-8.1-liquorix-amd64  | 1         | 0.75%   |
| 5.16.0-11.1-liquorix-amd64 | 1         | 0.75%   |
| 5.10.0-5-amd64             | 1         | 0.75%   |
| 5.10.0-27-686-pae          | 1         | 0.75%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 78        | 62.9%   |
| 4.19.0  | 15        | 12.1%   |
| 6.1.0   | 13        | 10.48%  |
| 4.9.0   | 5         | 4.03%   |
| 5.9.0   | 2         | 1.61%   |
| 5.7.0   | 2         | 1.61%   |
| 5.4.0   | 2         | 1.61%   |
| 3.16.0  | 2         | 1.61%   |
| 6.9.7   | 1         | 0.81%   |
| 6.6.7   | 1         | 0.81%   |
| 6.11.11 | 1         | 0.81%   |
| 5.8.0   | 1         | 0.81%   |
| 5.16.0  | 1         | 0.81%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 78        | 62.9%   |
| 4.19    | 15        | 12.1%   |
| 6.1     | 13        | 10.48%  |
| 4.9     | 5         | 4.03%   |
| 5.9     | 2         | 1.61%   |
| 5.7     | 2         | 1.61%   |
| 5.4     | 2         | 1.61%   |
| 3.16    | 2         | 1.61%   |
| 6.9     | 1         | 0.81%   |
| 6.6     | 1         | 0.81%   |
| 6.11    | 1         | 0.81%   |
| 5.8     | 1         | 0.81%   |
| 5.16    | 1         | 0.81%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 101       | 84.87%  |
| i686   | 18        | 15.13%  |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 56        | 45.16%  |
| BunsenLabs | 40        | 32.26%  |
| XFCE       | 19        | 15.32%  |
| i3         | 3         | 2.42%   |
| GNOME      | 2         | 1.61%   |
| X-Cinnamon | 1         | 0.81%   |
| openbox    | 1         | 0.81%   |
| MATE       | 1         | 0.81%   |
| KDE5       | 1         | 0.81%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 114       | 96.61%  |
| Tty     | 3         | 2.54%   |
| Wayland | 1         | 0.85%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 89        | 74.17%  |
| TDM     | 14        | 11.67%  |
| Unknown | 13        | 10.83%  |
| XDM     | 1         | 0.83%   |
| SDDM    | 1         | 0.83%   |
| LXDM    | 1         | 0.83%   |
| GDM3    | 1         | 0.83%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 55        | 47.01%  |
| en_GB      | 10        | 8.55%   |
| de_DE      | 7         | 5.98%   |
| fr_FR      | 5         | 4.27%   |
| it_IT      | 4         | 3.42%   |
| Unknown    | 4         | 3.42%   |
| sv_SE      | 3         | 2.56%   |
| pt_BR      | 3         | 2.56%   |
| en_CA      | 3         | 2.56%   |
| tr_TR      | 2         | 1.71%   |
| pl_PL      | 2         | 1.71%   |
| es_SV      | 2         | 1.71%   |
| en_PH      | 2         | 1.71%   |
| en_AU      | 2         | 1.71%   |
| ca_ES      | 2         | 1.71%   |
| ru_UA      | 1         | 0.85%   |
| ru_RU      | 1         | 0.85%   |
| nl_NL      | 1         | 0.85%   |
| hu_HU      | 1         | 0.85%   |
| es_US      | 1         | 0.85%   |
| es_ES      | 1         | 0.85%   |
| es_CO      | 1         | 0.85%   |
| es_AR      | 1         | 0.85%   |
| en_IE      | 1         | 0.85%   |
| de_DE.UTF8 | 1         | 0.85%   |
| bg_BG      | 1         | 0.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 60        | 51.28%  |
| EFI  | 57        | 48.72%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 109       | 92.37%  |
| Unknown | 3         | 2.54%   |
| Overlay | 2         | 1.69%   |
| Btrfs   | 2         | 1.69%   |
| XXXXXXX | 1         | 0.85%   |
| Aufs    | 1         | 0.85%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 62        | 51.67%  |
| MBR     | 46        | 38.33%  |
| Unknown | 12        | 10%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 91        | 77.12%  |
| Yes       | 27        | 22.88%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 90        | 75%     |
| Yes       | 30        | 25%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 21        | 17.95%  |
| Hewlett-Packard                | 15        | 12.82%  |
| ASUSTek Computer               | 12        | 10.26%  |
| Dell                           | 11        | 9.4%    |
| Google                         | 10        | 8.55%   |
| Acer                           | 8         | 6.84%   |
| Apple                          | 7         | 5.98%   |
| MSI                            | 5         | 4.27%   |
| Sony                           | 4         | 3.42%   |
| ASRock                         | 4         | 3.42%   |
| Intel                          | 3         | 2.56%   |
| Toshiba                        | 2         | 1.71%   |
| IBM                            | 2         | 1.71%   |
| Fujitsu                        | 2         | 1.71%   |
| WinPAD 110W                    | 1         | 0.85%   |
| Samsung Electronics            | 1         | 0.85%   |
| Matsushita Electric Industrial | 1         | 0.85%   |
| LG Electronics                 | 1         | 0.85%   |
| HUAWEI                         | 1         | 0.85%   |
| Gateway                        | 1         | 0.85%   |
| EVERCOM NETWORK                | 1         | 0.85%   |
| eMachines                      | 1         | 0.85%   |
| Compaq Presario 06             | 1         | 0.85%   |
| Chuwi                          | 1         | 0.85%   |
| Advent                         | 1         | 0.85%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Apple MacBookAir6,2                         | 2         | 1.71%   |
| Apple iMac11,1                              | 2         | 1.71%   |
| WinPAD 110W WinPAD 110W                     | 1         | 0.85%   |
| Toshiba Satellite P50T-A-114                | 1         | 0.85%   |
| Toshiba QOSMIO X505                         | 1         | 0.85%   |
| Sony VPCSB2L1R                              | 1         | 0.85%   |
| Sony VPCEH2J1E                              | 1         | 0.85%   |
| Sony VPCEG18FG                              | 1         | 0.85%   |
| Sony VGN-FW11L                              | 1         | 0.85%   |
| Samsung 275E4E/275E5E                       | 1         | 0.85%   |
| MSI Summit E13FlipEvo A12MT                 | 1         | 0.85%   |
| MSI MS-7C95                                 | 1         | 0.85%   |
| MSI MS-7786                                 | 1         | 0.85%   |
| MSI MS-7641                                 | 1         | 0.85%   |
| MSI MS-7093                                 | 1         | 0.85%   |
| Matsushita Electric Industrial CF-74GCDADBM | 1         | 0.85%   |
| LG X120-G.C7VPG                             | 1         | 0.85%   |
| Lenovo V110-14IAP 80TF                      | 1         | 0.85%   |
| Lenovo ThinkPad X60 Tablet 6365CTO          | 1         | 0.85%   |
| Lenovo ThinkPad X1 Nano Gen 1 20UN0064GE    | 1         | 0.85%   |
| Lenovo ThinkPad T490 20N2000CMC             | 1         | 0.85%   |
| Lenovo ThinkPad T480s 20L70028US            | 1         | 0.85%   |
| Lenovo ThinkPad T470p 20J6003KUS            | 1         | 0.85%   |
| Lenovo ThinkPad T440s 20AR003RMS            | 1         | 0.85%   |
| Lenovo ThinkPad T430 23473T1                | 1         | 0.85%   |
| Lenovo ThinkPad R400 7440WWQ                | 1         | 0.85%   |
| Lenovo ThinkPad P53 20QNS00X00              | 1         | 0.85%   |
| Lenovo ThinkPad L440 20ASS34900             | 1         | 0.85%   |
| Lenovo ThinkPad E570 20H50070IX             | 1         | 0.85%   |
| Lenovo ThinkCentre M73z 10BC002CUS          | 1         | 0.85%   |
| Lenovo IdeaPad Z580                         | 1         | 0.85%   |
| Lenovo IdeaPad S410p 20296                  | 1         | 0.85%   |
| Lenovo IdeaPad 320-15ABR 80XS               | 1         | 0.85%   |
| Lenovo IdeaPad 3 15IGL05 81WQ               | 1         | 0.85%   |
| Lenovo IdeaPad 110S-11IBR 80WG              | 1         | 0.85%   |
| Lenovo IdeaPad 110-15ISK 80UD               | 1         | 0.85%   |
| Lenovo IdeaPad 1 15IGL7 82V7                | 1         | 0.85%   |
| Lenovo G700 20251                           | 1         | 0.85%   |
| Intel DB85FL AAG89861-201                   | 1         | 0.85%   |
| Intel D946GZIS AAD66165-302                 | 1         | 0.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Lenovo ThinkPad                             | 11        | 9.4%    |
| Lenovo IdeaPad                              | 7         | 5.98%   |
| Acer Aspire                                 | 6         | 5.13%   |
| HP Laptop                                   | 3         | 2.56%   |
| HP EliteBook                                | 3         | 2.56%   |
| Dell Precision                              | 3         | 2.56%   |
| Dell Latitude                               | 3         | 2.56%   |
| IBM ThinkPad                                | 2         | 1.71%   |
| HP Mini                                     | 2         | 1.71%   |
| Dell Inspiron                               | 2         | 1.71%   |
| Apple MacBookAir6                           | 2         | 1.71%   |
| Apple iMac11                                | 2         | 1.71%   |
| WinPAD 110W WinPAD                          | 1         | 0.85%   |
| Toshiba Satellite                           | 1         | 0.85%   |
| Toshiba QOSMIO                              | 1         | 0.85%   |
| Sony VPCSB2L1R                              | 1         | 0.85%   |
| Sony VPCEH2J1E                              | 1         | 0.85%   |
| Sony VPCEG18FG                              | 1         | 0.85%   |
| Sony VGN-FW11L                              | 1         | 0.85%   |
| Samsung 275E4E                              | 1         | 0.85%   |
| MSI Summit                                  | 1         | 0.85%   |
| MSI MS-7C95                                 | 1         | 0.85%   |
| MSI MS-7786                                 | 1         | 0.85%   |
| MSI MS-7641                                 | 1         | 0.85%   |
| MSI MS-7093                                 | 1         | 0.85%   |
| Matsushita Electric Industrial CF-74GCDADBM | 1         | 0.85%   |
| LG X120-G.C7VPG                             | 1         | 0.85%   |
| Lenovo V110-14IAP                           | 1         | 0.85%   |
| Lenovo ThinkCentre                          | 1         | 0.85%   |
| Lenovo G700                                 | 1         | 0.85%   |
| Intel DB85FL                                | 1         | 0.85%   |
| Intel D946GZIS                              | 1         | 0.85%   |
| Intel D525MW                                | 1         | 0.85%   |
| HUAWEI BOM-WXX9                             | 1         | 0.85%   |
| HP ZBook                                    | 1         | 0.85%   |
| HP Stream                                   | 1         | 0.85%   |
| HP ProDesk                                  | 1         | 0.85%   |
| HP Presario                                 | 1         | 0.85%   |
| HP Compaq                                   | 1         | 0.85%   |
| HP 255                                      | 1         | 0.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2013    | 13        | 11.11%  |
| 2010    | 11        | 9.4%    |
| 2014    | 9         | 7.69%   |
| 2016    | 8         | 6.84%   |
| 2012    | 8         | 6.84%   |
| 2011    | 7         | 5.98%   |
| 2023    | 6         | 5.13%   |
| 2022    | 6         | 5.13%   |
| 2020    | 6         | 5.13%   |
| 2019    | 6         | 5.13%   |
| 2017    | 6         | 5.13%   |
| 2007    | 6         | 5.13%   |
| 2008    | 5         | 4.27%   |
| 2018    | 4         | 3.42%   |
| 2005    | 4         | 3.42%   |
| 2009    | 3         | 2.56%   |
| 2006    | 3         | 2.56%   |
| 2015    | 2         | 1.71%   |
| 2021    | 1         | 0.85%   |
| 2003    | 1         | 0.85%   |
| 2002    | 1         | 0.85%   |
| Unknown | 1         | 0.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 88        | 75.21%  |
| Desktop    | 25        | 21.37%  |
| Mini pc    | 2         | 1.71%   |
| All in one | 2         | 1.71%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 112       | 95.73%  |
| Enabled  | 5         | 4.27%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 107       | 91.45%  |
| Yes  | 10        | 8.55%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 37        | 30.83%  |
| 4.01-8.0    | 21        | 17.5%   |
| 8.01-16.0   | 21        | 17.5%   |
| 1.01-2.0    | 12        | 10%     |
| 16.01-24.0  | 10        | 8.33%   |
| 0.51-1.0    | 9         | 7.5%    |
| 2.01-3.0    | 5         | 4.17%   |
| 32.01-64.0  | 2         | 1.67%   |
| 24.01-32.0  | 2         | 1.67%   |
| 64.01-256.0 | 1         | 0.83%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 52        | 40.63%  |
| 0.51-1.0  | 29        | 22.66%  |
| 2.01-3.0  | 22        | 17.19%  |
| 4.01-8.0  | 9         | 7.03%   |
| 0.01-0.5  | 8         | 6.25%   |
| 3.01-4.0  | 7         | 5.47%   |
| 8.01-16.0 | 1         | 0.78%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 82        | 68.91%  |
| 2      | 29        | 24.37%  |
| 3      | 6         | 5.04%   |
| 7      | 1         | 0.84%   |
| 0      | 1         | 0.84%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 67        | 57.26%  |
| Yes       | 50        | 42.74%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 95        | 81.2%   |
| No        | 22        | 18.8%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 99        | 84.62%  |
| No        | 18        | 15.38%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 76        | 64.96%  |
| No        | 41        | 35.04%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country                | Computers | Percent |
|------------------------|-----------|---------|
| USA                    | 30        | 25.64%  |
| Sweden                 | 8         | 6.84%   |
| Germany                | 8         | 6.84%   |
| France                 | 6         | 5.13%   |
| Spain                  | 5         | 4.27%   |
| Brazil                 | 5         | 4.27%   |
| UK                     | 4         | 3.42%   |
| Turkey                 | 4         | 3.42%   |
| Italy                  | 4         | 3.42%   |
| Canada                 | 4         | 3.42%   |
| Poland                 | 3         | 2.56%   |
| Russia                 | 2         | 1.71%   |
| Philippines            | 2         | 1.71%   |
| Netherlands            | 2         | 1.71%   |
| Japan                  | 2         | 1.71%   |
| India                  | 2         | 1.71%   |
| El Salvador            | 2         | 1.71%   |
| Bulgaria               | 2         | 1.71%   |
| Australia              | 2         | 1.71%   |
| Argentina              | 2         | 1.71%   |
| Venezuela              | 1         | 0.85%   |
| Ukraine                | 1         | 0.85%   |
| Slovakia               | 1         | 0.85%   |
| Serbia                 | 1         | 0.85%   |
| Portugal               | 1         | 0.85%   |
| Morocco                | 1         | 0.85%   |
| Mexico                 | 1         | 0.85%   |
| Malaysia               | 1         | 0.85%   |
| Jamaica                | 1         | 0.85%   |
| Israel                 | 1         | 0.85%   |
| Ireland                | 1         | 0.85%   |
| Indonesia              | 1         | 0.85%   |
| Hungary                | 1         | 0.85%   |
| Guatemala              | 1         | 0.85%   |
| Greece                 | 1         | 0.85%   |
| Czechia                | 1         | 0.85%   |
| Colombia               | 1         | 0.85%   |
| Bosnia and Herzegovina | 1         | 0.85%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                       | Computers | Percent |
|----------------------------|-----------|---------|
| Västerås                 | 2         | 1.55%   |
| Tremestieri Etneo          | 2         | 1.55%   |
| Toulouse                   | 2         | 1.55%   |
| Stockholm                  | 2         | 1.55%   |
| San Salvador               | 2         | 1.55%   |
| Saint Paul                 | 2         | 1.55%   |
| Mumbai                     | 2         | 1.55%   |
| Istanbul                   | 2         | 1.55%   |
| Harrisonburg               | 2         | 1.55%   |
| Falun                      | 2         | 1.55%   |
| Barcelona                  | 2         | 1.55%   |
| Wroclaw                    | 1         | 0.78%   |
| Wilsonville                | 1         | 0.78%   |
| Walsall                    | 1         | 0.78%   |
| Vigo                       | 1         | 0.78%   |
| Victoria                   | 1         | 0.78%   |
| Uppsala                    | 1         | 0.78%   |
| Turin                      | 1         | 0.78%   |
| Truckee                    | 1         | 0.78%   |
| Thessaloniki               | 1         | 0.78%   |
| The Hague                  | 1         | 0.78%   |
| Telde                      | 1         | 0.78%   |
| Syracuse                   | 1         | 0.78%   |
| Surabaya                   | 1         | 0.78%   |
| Strasburg                  | 1         | 0.78%   |
| Springfield                | 1         | 0.78%   |
| South Shields              | 1         | 0.78%   |
| Södertälje               | 1         | 0.78%   |
| Sloviansk                  | 1         | 0.78%   |
| Skövde                    | 1         | 0.78%   |
| Shinjuku                   | 1         | 0.78%   |
| Shakopee                   | 1         | 0.78%   |
| Seville                    | 1         | 0.78%   |
| Secaucus                   | 1         | 0.78%   |
| Scranton                   | 1         | 0.78%   |
| Sarajevo                   | 1         | 0.78%   |
| Sao Bernardo do Campo      | 1         | 0.78%   |
| San Juan                   | 1         | 0.78%   |
| Saint-Bruno-de-Montarville | 1         | 0.78%   |
| Saint Joseph               | 1         | 0.78%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives  | Percent |
|---------------------|-----------|---------|---------|
| Seagate             | 27        | 35      | 17.31%  |
| WDC                 | 18        | 22      | 11.54%  |
| Samsung Electronics | 18        | 20      | 11.54%  |
| Unknown             | 17        | 24      | 10.9%   |
| Toshiba             | 13        | 22      | 8.33%   |
| Kingston            | 6         | 6       | 3.85%   |
| Intel               | 6         | 7       | 3.85%   |
| SK hynix            | 5         | 5       | 3.21%   |
| Crucial             | 5         | 5       | 3.21%   |
| SanDisk             | 4         | 4       | 2.56%   |
| Apple               | 4         | 4       | 2.56%   |
| Micron Technology   | 3         | 3       | 1.92%   |
| Hitachi             | 3         | 3       | 1.92%   |
| KingSpec            | 2         | 2       | 1.28%   |
| Fujitsu             | 2         | 2       | 1.28%   |
| walram              | 1         | 1       | 0.64%   |
| USB2.0              | 1         | 1       | 0.64%   |
| Timetec             | 1         | 1       | 0.64%   |
| Silicon Motion      | 1         | 1       | 0.64%   |
| OWC                 | 1         | 1       | 0.64%   |
| Mushkin             | 1         | 1       | 0.64%   |
| LITEONIT            | 1         | 1       | 0.64%   |
| LITEON              | 1         | 1       | 0.64%   |
| LDLC                | 1         | 2       | 0.64%   |
| KIOXIA-EXCERIA      | 1         | 3       | 0.64%   |
| KIOXIA              | 1         | 2       | 0.64%   |
| JMicron Technology  | 1         | 1       | 0.64%   |
| HUAWEI              | 1         | 1       | 0.64%   |
| HL-DT-ST            | 1         | Unknown | 0.64%   |
| HGST                | 1         | 1       | 0.64%   |
| Hewlett-Packard     | 1         | 1       | 0.64%   |
| HAGIWARA            | 1         | 1       | 0.64%   |
| Fanxiang            | 1         | 1       | 0.64%   |
| Corsair             | 1         | 1       | 0.64%   |
| China               | 1         | 1       | 0.64%   |
| BIWIN               | 1         | 1       | 0.64%   |
| BHT                 | 1         | 1       | 0.64%   |
| A-DATA Technology   | 1         | 1       | 0.64%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown SD32G  32GB                                 | 2         | 1.19%   |
| Unknown DF4016  16GB                                | 2         | 1.19%   |
| Unknown DA4032  32GB                                | 2         | 1.19%   |
| Seagate ST500LM000-1EJ162 500GB                     | 2         | 1.19%   |
| Seagate ST3250820AS 250GB                           | 2         | 1.19%   |
| Seagate ST320LT012-9WS14C 320GB                     | 2         | 1.19%   |
| Seagate ST2000DM001-1CH164 2TB                      | 2         | 1.19%   |
| Seagate ST1000LM035-1RK172 1TB                      | 2         | 1.19%   |
| SanDisk DF4064  64GB                                | 2         | 1.19%   |
| Samsung SSD 850 EVO 250GB                           | 2         | 1.19%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 2         | 1.19%   |
| Kingston SA400S37240G 240GB SSD                     | 2         | 1.19%   |
| Apple SSD SD0128F 121GB                             | 2         | 1.19%   |
| WDC WDS500G3X0C-00SJG0 500GB                        | 1         | 0.6%    |
| WDC WD800JB-00JJC0 80GB                             | 1         | 0.6%    |
| WDC WD50NPZZ-00A9JT0 5TB                            | 1         | 0.6%    |
| WDC WD5000LPVX-75V0TT0 500GB                        | 1         | 0.6%    |
| WDC WD5000LPVX-22V0TT0 500GB                        | 1         | 0.6%    |
| WDC WD5000AAKX-001CA0 500GB                         | 1         | 0.6%    |
| WDC WD3200BEVT-22ZCT0 320GB                         | 1         | 0.6%    |
| WDC WD3200BEVT-08A23T1 320GB                        | 1         | 0.6%    |
| WDC WD20EZRX-00D8PB0 2TB                            | 1         | 0.6%    |
| WDC WD20EARX-00PASB0 2TB                            | 1         | 0.6%    |
| WDC WD1600AAJS-75B4A0 160GB                         | 1         | 0.6%    |
| WDC WD1600AABS-52PRA0 160GB                         | 1         | 0.6%    |
| WDC WD10JPVX-22JC3T0 1TB                            | 1         | 0.6%    |
| WDC WD10JPVX-08JC3T6 1TB                            | 1         | 0.6%    |
| WDC WD10EZEX-60M2NA0 1TB                            | 1         | 0.6%    |
| WDC WD10EFRX-68FYTN0 1TB                            | 1         | 0.6%    |
| WDC WD10EARX-32N0YB0 1TB                            | 1         | 0.6%    |
| WDC WD10EADS-00L5B1 1TB                             | 1         | 0.6%    |
| WDC PC SN520 NVMe 256GB                             | 1         | 0.6%    |
| walram 60G                                          | 1         | 0.6%    |
| USB2.0 CardReader                                   | 1         | 0.6%    |
| Unknown SDC  8GB                                    | 1         | 0.6%    |
| Unknown SD08G  8GB                                  | 1         | 0.6%    |
| Unknown NVMe SSD Drive 128GB                        | 1         | 0.6%    |
| Unknown MMC128  128GB                               | 1         | 0.6%    |
| Unknown MMC Card  64GB                              | 1         | 0.6%    |
| Unknown MMC Card  32GB                              | 1         | 0.6%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 27        | 35     | 42.19%  |
| WDC                 | 16        | 20     | 25%     |
| Toshiba             | 10        | 12     | 15.63%  |
| Samsung Electronics | 3         | 3      | 4.69%   |
| Hitachi             | 3         | 3      | 4.69%   |
| Fujitsu             | 2         | 2      | 3.13%   |
| JMicron Technology  | 1         | 1      | 1.56%   |
| HGST                | 1         | 1      | 1.56%   |
| Apple               | 1         | 1      | 1.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 10     | 18.37%  |
| Kingston            | 5         | 5      | 10.2%   |
| Crucial             | 5         | 5      | 10.2%   |
| Toshiba             | 3         | 10     | 6.12%   |
| Intel               | 3         | 3      | 6.12%   |
| Apple               | 3         | 3      | 6.12%   |
| SK hynix            | 2         | 2      | 4.08%   |
| SanDisk             | 2         | 2      | 4.08%   |
| Micron Technology   | 2         | 2      | 4.08%   |
| KingSpec            | 2         | 2      | 4.08%   |
| Timetec             | 1         | 1      | 2.04%   |
| OWC                 | 1         | 1      | 2.04%   |
| Mushkin             | 1         | 1      | 2.04%   |
| LITEONIT            | 1         | 1      | 2.04%   |
| LITEON              | 1         | 1      | 2.04%   |
| LDLC                | 1         | 1      | 2.04%   |
| KIOXIA-EXCERIA      | 1         | 3      | 2.04%   |
| HAGIWARA            | 1         | 1      | 2.04%   |
| Corsair             | 1         | 1      | 2.04%   |
| China               | 1         | 1      | 2.04%   |
| BIWIN               | 1         | 1      | 2.04%   |
| BHT                 | 1         | 1      | 2.04%   |
| A-DATA Technology   | 1         | 1      | 2.04%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 56        | 78     | 38.36%  |
| SSD     | 47        | 59     | 32.19%  |
| NVMe    | 20        | 24     | 13.7%   |
| MMC     | 19        | 26     | 13.01%  |
| Unknown | 4         | 3      | 2.74%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 90        | 134    | 66.18%  |
| NVMe | 20        | 24     | 14.71%  |
| MMC  | 19        | 26     | 13.97%  |
| SAS  | 7         | 6      | 5.15%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 74        | 105    | 72.55%  |
| 0.51-1.0   | 15        | 17     | 14.71%  |
| 1.01-2.0   | 10        | 12     | 9.8%    |
| 4.01-10.0  | 2         | 2      | 1.96%   |
| 3.01-4.0   | 1         | 1      | 0.98%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 37        | 30.33%  |
| 251-500        | 25        | 20.49%  |
| 21-50          | 14        | 11.48%  |
| 51-100         | 14        | 11.48%  |
| 501-1000       | 11        | 9.02%   |
| 1-20           | 9         | 7.38%   |
| 1001-2000      | 7         | 5.74%   |
| 2001-3000      | 3         | 2.46%   |
| More than 3000 | 2         | 1.64%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 70        | 56.91%  |
| 101-250        | 15        | 12.2%   |
| 21-50          | 13        | 10.57%  |
| 51-100         | 9         | 7.32%   |
| 251-500        | 8         | 6.5%    |
| 501-1000       | 4         | 3.25%   |
| More than 3000 | 2         | 1.63%   |
| 1001-2000      | 2         | 1.63%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST320LT012-9WS14C 320GB                | 2         | 2      | 6.9%    |
| WDC WD5000LPVX-22V0TT0 500GB                   | 1         | 1      | 3.45%   |
| WDC WD5000AAKX-001CA0 500GB                    | 1         | 1      | 3.45%   |
| WDC WD3200BEVT-08A23T1 320GB                   | 1         | 2      | 3.45%   |
| WDC WD10EARX-32N0YB0 1TB                       | 1         | 1      | 3.45%   |
| Toshiba MQ01ABF050 500GB                       | 1         | 1      | 3.45%   |
| Toshiba MQ01ABD075 752GB                       | 1         | 1      | 3.45%   |
| Toshiba MQ01ABD032 320GB                       | 1         | 1      | 3.45%   |
| Toshiba MK7575GSX 752GB                        | 1         | 1      | 3.45%   |
| Toshiba MK5059GSXP 500GB                       | 1         | 1      | 3.45%   |
| Toshiba MK4026GAX RoHS 40GB                    | 1         | 2      | 3.45%   |
| Toshiba MK2552GSX 250GB                        | 1         | 1      | 3.45%   |
| Toshiba MK1652GSX 160GB                        | 1         | 1      | 3.45%   |
| Seagate ST500LM021-1KJ152 500GB                | 1         | 2      | 3.45%   |
| Seagate ST3250820AS 250GB                      | 1         | 1      | 3.45%   |
| Seagate ST2000LM003 HN-M201RAD 2TB             | 1         | 1      | 3.45%   |
| Seagate ST2000DM001-1CH164 2TB                 | 1         | 1      | 3.45%   |
| Samsung Electronics HM641JI 640GB              | 1         | 1      | 3.45%   |
| Samsung Electronics HM160HI 160GB              | 1         | 1      | 3.45%   |
| Micron Technology MTFDDAK256MAM-1K12 256GB SSD | 1         | 1      | 3.45%   |
| LDLC SSD 120GB                                 | 1         | 1      | 3.45%   |
| KingSpec KSD-PA18.6-064MS 64GB SSD             | 1         | 1      | 3.45%   |
| Hitachi HTS723232L9A360 320GB                  | 1         | 1      | 3.45%   |
| Hitachi HTS421260H9AT00 64GB                   | 1         | 1      | 3.45%   |
| Hewlett-Packard SSD EX900 250GB                | 1         | 1      | 3.45%   |
| Crucial C300-CTFDDAC128MAG 128GB SSD           | 1         | 1      | 3.45%   |
| China SSD 120GB                                | 1         | 1      | 3.45%   |
| Apple HDD HTS547575A9E384 752GB                | 1         | 1      | 3.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 8         | 9      | 27.59%  |
| Seagate             | 6         | 7      | 20.69%  |
| WDC                 | 4         | 5      | 13.79%  |
| Samsung Electronics | 2         | 2      | 6.9%    |
| Hitachi             | 2         | 2      | 6.9%    |
| Micron Technology   | 1         | 1      | 3.45%   |
| LDLC                | 1         | 1      | 3.45%   |
| KingSpec            | 1         | 1      | 3.45%   |
| Hewlett-Packard     | 1         | 1      | 3.45%   |
| Crucial             | 1         | 1      | 3.45%   |
| China               | 1         | 1      | 3.45%   |
| Apple               | 1         | 1      | 3.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 8         | 9      | 34.78%  |
| Seagate             | 6         | 7      | 26.09%  |
| WDC                 | 4         | 5      | 17.39%  |
| Samsung Electronics | 2         | 2      | 8.7%    |
| Hitachi             | 2         | 2      | 8.7%    |
| Apple               | 1         | 1      | 4.35%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 23        | 26     | 79.31%  |
| SSD  | 5         | 5      | 17.24%  |
| NVMe | 1         | 1      | 3.45%   |

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
| Works    | 74        | 98     | 54.41%  |
| Detected | 33        | 60     | 24.26%  |
| Malfunc  | 29        | 32     | 21.32%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 78        | 64.46%  |
| AMD                              | 12        | 9.92%   |
| Samsung Electronics              | 7         | 5.79%   |
| Silicon Motion                   | 3         | 2.48%   |
| ASMedia Technology               | 3         | 2.48%   |
| VIA Technologies                 | 2         | 1.65%   |
| SK hynix                         | 2         | 1.65%   |
| Silicon Integrated Systems [SiS] | 2         | 1.65%   |
| SanDisk                          | 2         | 1.65%   |
| Marvell Technology Group         | 2         | 1.65%   |
| Silicon Image                    | 1         | 0.83%   |
| Nvidia                           | 1         | 0.83%   |
| Micron Technology                | 1         | 0.83%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.83%   |
| KIOXIA                           | 1         | 0.83%   |
| Kingston Technology Company      | 1         | 0.83%   |
| JMicron Technology               | 1         | 0.83%   |
| Apacer Technology                | 1         | 0.83%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 7         | 5.11%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 7         | 5.11%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 7         | 5.11%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 6         | 4.38%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 5         | 3.65%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 5         | 3.65%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 5         | 3.65%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3         | 2.19%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 2.19%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 3         | 2.19%   |
| Intel Comet Lake SATA AHCI Controller                                          | 3         | 2.19%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 2.19%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 3         | 2.19%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 3         | 2.19%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 3         | 2.19%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 2.19%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 2         | 1.46%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 2         | 1.46%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                     | 2         | 1.46%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 2         | 1.46%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 1.46%   |
| Intel 82801FBM (ICH6M) SATA Controller                                         | 2         | 1.46%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 2         | 1.46%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 1.46%   |
| AMD 400 Series Chipset SATA Controller                                         | 2         | 1.46%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 1         | 0.73%   |
| VIA VT6415 PATA IDE Host Controller                                            | 1         | 0.73%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 1         | 0.73%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 0.73%   |
| Silicon Motion Non-Volatile memory controller                                  | 1         | 0.73%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 1         | 0.73%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller               | 1         | 0.73%   |
| SanDisk PC SN520 x2 M.2 2230 NVMe SSD                                          | 1         | 0.73%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 1         | 0.73%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 1         | 0.73%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 0.73%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1         | 0.73%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 1         | 0.73%   |
| Nvidia MCP79 SATA Controller                                                   | 1         | 0.73%   |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 1         | 0.73%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 78        | 63.41%  |
| IDE  | 21        | 17.07%  |
| NVMe | 20        | 16.26%  |
| RAID | 4         | 3.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 101       | 86.32%  |
| AMD    | 16        | 13.68%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel Celeron N4020 CPU @ 1.10GHz      | 4         | 3.42%   |
| Intel Core i5-5200U CPU @ 2.20GHz      | 3         | 2.56%   |
| Intel Celeron CPU N3060 @ 1.60GHz      | 3         | 2.56%   |
| Intel Pentium CPU G3240 @ 3.10GHz      | 2         | 1.71%   |
| Intel Pentium CPU 2020M @ 2.40GHz      | 2         | 1.71%   |
| Intel Core i7-7500U CPU @ 2.70GHz      | 2         | 1.71%   |
| Intel Core i5-4250U CPU @ 1.30GHz      | 2         | 1.71%   |
| Intel Core i5-3210M CPU @ 2.50GHz      | 2         | 1.71%   |
| Intel Core i5 CPU 750 @ 2.67GHz        | 2         | 1.71%   |
| Intel Core i3-6006U CPU @ 2.00GHz      | 2         | 1.71%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz   | 2         | 1.71%   |
| Intel Celeron N4000 CPU @ 1.10GHz      | 2         | 1.71%   |
| Intel Celeron CPU N3350 @ 1.10GHz      | 2         | 1.71%   |
| Intel Celeron CPU N2840 @ 2.16GHz      | 2         | 1.71%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz      | 2         | 1.71%   |
| Intel Atom CPU N455 @ 1.66GHz          | 2         | 1.71%   |
| Intel Atom CPU N270 @ 1.60GHz          | 2         | 1.71%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz    | 1         | 0.85%   |
| Intel Pentium M processor 1.86GHz      | 1         | 0.85%   |
| Intel Pentium M processor 1.60GHz      | 1         | 0.85%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz | 1         | 0.85%   |
| Intel Pentium CPU P6100 @ 2.00GHz      | 1         | 0.85%   |
| Intel Pentium 4 CPU 2.40GHz            | 1         | 0.85%   |
| Intel Genuine CPU T2060 @ 1.60GHz      | 1         | 0.85%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz       | 1         | 0.85%   |
| Intel Core i7-9750H CPU @ 2.60GHz      | 1         | 0.85%   |
| Intel Core i7-8650U CPU @ 1.90GHz      | 1         | 0.85%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz     | 1         | 0.85%   |
| Intel Core i7-7700 CPU @ 3.60GHz       | 1         | 0.85%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz     | 1         | 0.85%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz     | 1         | 0.85%   |
| Intel Core i7-4770 CPU @ 3.40GHz       | 1         | 0.85%   |
| Intel Core i7-3840QM CPU @ 2.80GHz     | 1         | 0.85%   |
| Intel Core i7-3630QM CPU @ 2.40GHz     | 1         | 0.85%   |
| Intel Core i7-2640M CPU @ 2.80GHz      | 1         | 0.85%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz      | 1         | 0.85%   |
| Intel Core i7 CPU M 620 @ 2.67GHz      | 1         | 0.85%   |
| Intel Core i7 CPU 930 @ 2.80GHz        | 1         | 0.85%   |
| Intel Core i5-8350U CPU @ 1.70GHz      | 1         | 0.85%   |
| Intel Core i5-8265U CPU @ 1.60GHz      | 1         | 0.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 27        | 23.08%  |
| Intel Celeron      | 17        | 14.53%  |
| Intel Core i7      | 15        | 12.82%  |
| Intel Atom         | 9         | 7.69%   |
| Intel Core 2 Duo   | 7         | 5.98%   |
| Intel Core i3      | 6         | 5.13%   |
| Intel Pentium      | 5         | 4.27%   |
| Other              | 3         | 2.56%   |
| Intel Pentium M    | 2         | 1.71%   |
| Intel Core Duo     | 2         | 1.71%   |
| Intel Core 2       | 2         | 1.71%   |
| AMD Ryzen 7        | 2         | 1.71%   |
| AMD Ryzen 3        | 2         | 1.71%   |
| AMD FX             | 2         | 1.71%   |
| AMD A4             | 2         | 1.71%   |
| Intel Xeon         | 1         | 0.85%   |
| Intel Pentium Dual | 1         | 0.85%   |
| Intel Pentium 4    | 1         | 0.85%   |
| Intel Genuine      | 1         | 0.85%   |
| Intel Core m3      | 1         | 0.85%   |
| Intel Core 2 Quad  | 1         | 0.85%   |
| AMD Ryzen 5        | 1         | 0.85%   |
| AMD Mobile Sempron | 1         | 0.85%   |
| AMD E2             | 1         | 0.85%   |
| AMD E1             | 1         | 0.85%   |
| AMD Athlon XP      | 1         | 0.85%   |
| AMD Athlon II X4   | 1         | 0.85%   |
| AMD Athlon 64      | 1         | 0.85%   |
| AMD A12            | 1         | 0.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 66        | 56.41%  |
| 4      | 30        | 25.64%  |
| 1      | 13        | 11.11%  |
| 6      | 4         | 3.42%   |
| 8      | 2         | 1.71%   |
| 12     | 1         | 0.85%   |
| 3      | 1         | 0.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 117       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 59        | 50.43%  |
| 2      | 58        | 49.57%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 106       | 90.6%   |
| 32-bit         | 10        | 8.55%   |
| Unknown        | 1         | 0.85%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 19        | 15.97%  |
| 0x306a9    | 9         | 7.56%   |
| 0x306c3    | 7         | 5.88%   |
| 0x706a8    | 5         | 4.2%    |
| 0x1067a    | 5         | 4.2%    |
| 0x406e3    | 4         | 3.36%   |
| 0x406c4    | 4         | 3.36%   |
| 0x306d4    | 4         | 3.36%   |
| 0x206a7    | 4         | 3.36%   |
| 0x806ec    | 3         | 2.52%   |
| 0x806e9    | 3         | 2.52%   |
| 0x6ec      | 3         | 2.52%   |
| 0x40651    | 3         | 2.52%   |
| 0x30678    | 3         | 2.52%   |
| 0x106e5    | 3         | 2.52%   |
| 0x106ca    | 3         | 2.52%   |
| 0x906e9    | 2         | 1.68%   |
| 0x806c1    | 2         | 1.68%   |
| 0x706a1    | 2         | 1.68%   |
| 0x506c9    | 2         | 1.68%   |
| 0x20655    | 2         | 1.68%   |
| 0x106c2    | 2         | 1.68%   |
| 0x10676    | 2         | 1.68%   |
| 0x06000852 | 2         | 1.68%   |
| 0xf27      | 1         | 0.84%   |
| 0x906a3    | 1         | 0.84%   |
| 0x806ea    | 1         | 0.84%   |
| 0x6fd      | 1         | 0.84%   |
| 0x6fb      | 1         | 0.84%   |
| 0x6fa      | 1         | 0.84%   |
| 0x6f6      | 1         | 0.84%   |
| 0x6f2      | 1         | 0.84%   |
| 0x6d8      | 1         | 0.84%   |
| 0x506e3    | 1         | 0.84%   |
| 0x306f2    | 1         | 0.84%   |
| 0x106a5    | 1         | 0.84%   |
| 0x0a50000d | 1         | 0.84%   |
| 0x08108109 | 1         | 0.84%   |
| 0x08108102 | 1         | 0.84%   |
| 0x0800820d | 1         | 0.84%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Haswell       | 13        | 11.11%  |
| KabyLake      | 11        | 9.4%    |
| IvyBridge     | 10        | 8.55%   |
| Silvermont    | 8         | 6.84%   |
| Penryn        | 7         | 5.98%   |
| Goldmont plus | 7         | 5.98%   |
| Bonnell       | 6         | 5.13%   |
| Skylake       | 5         | 4.27%   |
| SandyBridge   | 5         | 4.27%   |
| P6            | 5         | 4.27%   |
| Core          | 5         | 4.27%   |
| Nehalem       | 4         | 3.42%   |
| Broadwell     | 4         | 3.42%   |
| Zen+          | 3         | 2.56%   |
| Westmere      | 3         | 2.56%   |
| TigerLake     | 2         | 1.71%   |
| Piledriver    | 2         | 1.71%   |
| K8 Hammer     | 2         | 1.71%   |
| Goldmont      | 2         | 1.71%   |
| Excavator     | 2         | 1.71%   |
| Unknown       | 2         | 1.71%   |
| Zen 3         | 1         | 0.85%   |
| Tremont       | 1         | 0.85%   |
| NetBurst      | 1         | 0.85%   |
| K6            | 1         | 0.85%   |
| K10 Llano     | 1         | 0.85%   |
| K10           | 1         | 0.85%   |
| Jaguar        | 1         | 0.85%   |
| CometLake     | 1         | 0.85%   |
| Bobcat        | 1         | 0.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 83        | 62.41%  |
| Nvidia                           | 32        | 24.06%  |
| AMD                              | 17        | 12.78%  |
| Silicon Integrated Systems [SiS] | 1         | 0.75%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                      | Computers | Percent |
|--------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                           | 8         | 5.63%   |
| Intel GeminiLake [UHD Graphics 600]                                                        | 7         | 4.93%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller              | 6         | 4.23%   |
| Intel Haswell-ULT Integrated Graphics Controller                                           | 5         | 3.52%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller   | 5         | 3.52%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                  | 4         | 2.82%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                               | 4         | 2.82%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                    | 4         | 2.82%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                       | 3         | 2.11%   |
| Intel Skylake GT2 [HD Graphics 520]                                                        | 3         | 2.11%   |
| Intel HD Graphics 620                                                                      | 3         | 2.11%   |
| Intel HD Graphics 5500                                                                     | 3         | 2.11%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                               | 3         | 2.11%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                  | 3         | 2.11%   |
| Nvidia GF119M [GeForce 410M]                                                               | 2         | 1.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller                | 2         | 1.41%   |
| Intel UHD Graphics 620                                                                     | 2         | 1.41%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                                 | 2         | 1.41%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                  | 2         | 1.41%   |
| Intel HD Graphics 630                                                                      | 2         | 1.41%   |
| Intel HD Graphics 500                                                                      | 2         | 1.41%   |
| Intel Core Processor Integrated Graphics Controller                                        | 2         | 1.41%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                       | 2         | 1.41%   |
| AMD RV770/M98L [Mobility Radeon HD 4850]                                                   | 2         | 1.41%   |
| Silicon Integrated Systems [SiS] 661/741/760 PCI/AGP or 662/761Gx PCIE VGA Display Adapter | 1         | 0.7%    |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                              | 1         | 0.7%    |
| Nvidia TU116 [GeForce GTX 1660]                                                            | 1         | 0.7%    |
| Nvidia TU104GL [Tesla T4]                                                                  | 1         | 0.7%    |
| Nvidia NV34 [GeForce FX 5500]                                                              | 1         | 0.7%    |
| Nvidia NV34 [GeForce FX 5200]                                                              | 1         | 0.7%    |
| Nvidia GT218M [NVS 3100M]                                                                  | 1         | 0.7%    |
| Nvidia GT218M [GeForce 310M]                                                               | 1         | 0.7%    |
| Nvidia GT218 [GeForce 310]                                                                 | 1         | 0.7%    |
| Nvidia GT215M [GeForce GTS 250M]                                                           | 1         | 0.7%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                        | 1         | 0.7%    |
| Nvidia GM204 [GeForce GTX 980]                                                             | 1         | 0.7%    |
| Nvidia GM200 [GeForce GTX 980 Ti]                                                          | 1         | 0.7%    |
| Nvidia GM108M [GeForce 940MX]                                                              | 1         | 0.7%    |
| Nvidia GM108M [GeForce 840M]                                                               | 1         | 0.7%    |
| Nvidia GM107M [GeForce GTX 960M]                                                           | 1         | 0.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 61        | 52.14%  |
| 1 x Nvidia     | 17        | 14.53%  |
| Intel + Nvidia | 14        | 11.97%  |
| 1 x AMD        | 13        | 11.11%  |
| Other          | 4         | 3.42%   |
| 2 x Intel      | 2         | 1.71%   |
| 2 x AMD        | 2         | 1.71%   |
| Intel + AMD    | 2         | 1.71%   |
| 2 x Nvidia     | 1         | 0.85%   |
| 1 x SiS        | 1         | 0.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 105       | 88.98%  |
| Proprietary | 8         | 6.78%   |
| Unknown     | 5         | 4.24%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 77        | 65.25%  |
| 0.01-0.5   | 19        | 16.1%   |
| 1.01-2.0   | 10        | 8.47%   |
| 0.51-1.0   | 6         | 5.08%   |
| 5.01-6.0   | 3         | 2.54%   |
| 3.01-4.0   | 3         | 2.54%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 18        | 15.13%  |
| BOE                  | 16        | 13.45%  |
| Chimei Innolux       | 15        | 12.61%  |
| LG Display           | 12        | 10.08%  |
| Dell                 | 7         | 5.88%   |
| Samsung Electronics  | 6         | 5.04%   |
| Apple                | 6         | 5.04%   |
| Lenovo               | 5         | 4.2%    |
| Hewlett-Packard      | 4         | 3.36%   |
| Goldstar             | 4         | 3.36%   |
| Sony                 | 3         | 2.52%   |
| LG Philips           | 3         | 2.52%   |
| Acer                 | 3         | 2.52%   |
| Quanta Display       | 2         | 1.68%   |
| Philips              | 2         | 1.68%   |
| InfoVision           | 2         | 1.68%   |
| ViewSonic            | 1         | 0.84%   |
| Toshiba              | 1         | 0.84%   |
| Sharp                | 1         | 0.84%   |
| Seiko/Epson          | 1         | 0.84%   |
| Insignia             | 1         | 0.84%   |
| HUAWEI               | 1         | 0.84%   |
| Fujitsu Siemens      | 1         | 0.84%   |
| CPT                  | 1         | 0.84%   |
| BenQ                 | 1         | 0.84%   |
| ASUSTek Computer     | 1         | 0.84%   |
| Ancor Communications | 1         | 0.84%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Sony TV SNYF301 1920x1080                                            | 2         | 1.63%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                 | 2         | 1.63%   |
| Apple Color LCD APP9CB5 2560x1440 600x340mm 27.2-inch                | 2         | 1.63%   |
| ViewSonic LCD Monitor VSCC826 1920x1080 510x290mm 23.1-inch          | 1         | 0.81%   |
| Toshiba TSB-TV TSB0205 1920x1080 708x398mm 32.0-inch                 | 1         | 0.81%   |
| Sony TV SNY5703 1920x1080                                            | 1         | 0.81%   |
| Sharp LQ123P1JX31 SHP1471 2400x1600 259x173mm 12.3-inch              | 1         | 0.81%   |
| Seiko/Epson LCD Monitor 1920x1080                                    | 1         | 0.81%   |
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch | 1         | 0.81%   |
| Samsung Electronics SMS24A650 SAM0864 1920x1080 531x299mm 24.0-inch  | 1         | 0.81%   |
| Samsung Electronics SMS24A650 SAM082A 1920x1080 531x299mm 24.0-inch  | 1         | 0.81%   |
| Samsung Electronics SMB2330HD SAM070E 1920x1080 510x290mm 23.1-inch  | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SEC434E 1600x900 310x174mm 14.0-inch | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch | 1         | 0.81%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 1         | 0.81%   |
| Quanta Display LCD Monitor QDS0025 1024x768 304x228mm 15.0-inch      | 1         | 0.81%   |
| Quanta Display LCD Monitor QDS001D 1280x800 331x207mm 15.4-inch      | 1         | 0.81%   |
| Philips PHL 240B7QPJ PHL0903 1920x1200 518x324mm 24.1-inch           | 1         | 0.81%   |
| Philips 226VL PHLC081 1920x1080 480x268mm 21.6-inch                  | 1         | 0.81%   |
| LG Philips LCD Monitor LPLCF00 1280x800 331x207mm 15.4-inch          | 1         | 0.81%   |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch          | 1         | 0.81%   |
| LG Philips LCD Monitor LPL00E5 1440x900 304x190mm 14.1-inch          | 1         | 0.81%   |
| LG Display LP156WH2-TLQ1 LGD021B 1366x768 344x194mm 15.5-inch        | 1         | 0.81%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 1         | 0.81%   |
| LG Display LCD Monitor LGD04D4 3840x2160 344x194mm 15.5-inch         | 1         | 0.81%   |
| LG Display LCD Monitor LGD03FC 1600x900 309x174mm 14.0-inch          | 1         | 0.81%   |
| LG Display LCD Monitor LGD03B8 1366x768 310x174mm 14.0-inch          | 1         | 0.81%   |
| LG Display LCD Monitor LGD0390 1600x900 382x215mm 17.3-inch          | 1         | 0.81%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch          | 1         | 0.81%   |
| LG Display LCD Monitor LGD032C 1920x1080 344x194mm 15.5-inch         | 1         | 0.81%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch          | 1         | 0.81%   |
| LG Display LCD Monitor LGD02AC 1366x768 344x194mm 15.5-inch          | 1         | 0.81%   |
| LG Display LCD Monitor LGD029F 1024x600 224x126mm 10.1-inch          | 1         | 0.81%   |
| LG Display LCD Monitor LGD0250 1366x768 345x194mm 15.6-inch          | 1         | 0.81%   |
| Lenovo LEN-M73Z-D LEN00A0 1600x900 442x249mm 20.0-inch               | 1         | 0.81%   |
| Lenovo LEN L24q-30 LEN65FB 2560x1440 527x296mm 23.8-inch             | 1         | 0.81%   |
| Lenovo LEN E2323swA LEN60B0 1920x1080 477x268mm 21.5-inch            | 1         | 0.81%   |
| Lenovo LCD Monitor LEN4035 1280x800 304x190mm 14.1-inch              | 1         | 0.81%   |
| Lenovo LCD Monitor LEN4002 1024x768 245x184mm 12.1-inch              | 1         | 0.81%   |
| Insignia NS-32D220NA18 BBY0050 1680x1050 708x398mm 32.0-inch         | 1         | 0.81%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 39        | 33.62%  |
| 1920x1080 (FHD)    | 33        | 28.45%  |
| 1600x900 (HD+)     | 11        | 9.48%   |
| 1440x900 (WXGA+)   | 6         | 5.17%   |
| 1280x800 (WXGA)    | 6         | 5.17%   |
| 2560x1440 (QHD)    | 4         | 3.45%   |
| 1680x1050 (WSXGA+) | 3         | 2.59%   |
| 1024x768 (XGA)     | 3         | 2.59%   |
| 1024x600           | 3         | 2.59%   |
| 1280x1024 (SXGA)   | 2         | 1.72%   |
| 3840x2160 (4K)     | 1         | 0.86%   |
| 2400x1600          | 1         | 0.86%   |
| 2160x1350          | 1         | 0.86%   |
| 1920x1200 (WUXGA)  | 1         | 0.86%   |
| 1600x1200          | 1         | 0.86%   |
| 1360x768           | 1         | 0.86%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 33        | 27.73%  |
| 13      | 16        | 13.45%  |
| 14      | 12        | 10.08%  |
| 11      | 11        | 9.24%   |
| 24      | 8         | 6.72%   |
| 23      | 8         | 6.72%   |
| 72      | 4         | 3.36%   |
| 19      | 4         | 3.36%   |
| 27      | 3         | 2.52%   |
| 21      | 3         | 2.52%   |
| 20      | 3         | 2.52%   |
| 22      | 2         | 1.68%   |
| 18      | 2         | 1.68%   |
| 17      | 2         | 1.68%   |
| 12      | 2         | 1.68%   |
| 10      | 2         | 1.68%   |
| 34      | 1         | 0.84%   |
| 31      | 1         | 0.84%   |
| 8       | 1         | 0.84%   |
| Unknown | 1         | 0.84%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 54        | 46.15%  |
| 201-300     | 22        | 18.8%   |
| 501-600     | 18        | 15.38%  |
| 401-500     | 11        | 9.4%    |
| 351-400     | 4         | 3.42%   |
| 1501-2000   | 4         | 3.42%   |
| 701-800     | 1         | 0.85%   |
| 601-700     | 1         | 0.85%   |
| 101-200     | 1         | 0.85%   |
| Unknown     | 1         | 0.85%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 86        | 78.18%  |
| 16/10   | 15        | 13.64%  |
| 4/3     | 4         | 3.64%   |
| 3/2     | 2         | 1.82%   |
| 6/5     | 1         | 0.91%   |
| 5/4     | 1         | 0.91%   |
| Unknown | 1         | 0.91%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 32        | 26.89%  |
| 81-90          | 23        | 19.33%  |
| 201-250        | 18        | 15.13%  |
| 51-60          | 11        | 9.24%   |
| 151-200        | 8         | 6.72%   |
| 71-80          | 5         | 4.2%    |
| More than 1000 | 4         | 3.36%   |
| 301-350        | 3         | 2.52%   |
| 251-300        | 3         | 2.52%   |
| 61-70          | 2         | 1.68%   |
| 41-50          | 2         | 1.68%   |
| 351-500        | 1         | 0.84%   |
| 1-40           | 1         | 0.84%   |
| 141-150        | 1         | 0.84%   |
| 131-140        | 1         | 0.84%   |
| 121-130        | 1         | 0.84%   |
| 501-1000       | 1         | 0.84%   |
| 91-100         | 1         | 0.84%   |
| Unknown        | 1         | 0.84%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 39        | 33.33%  |
| 121-160       | 36        | 30.77%  |
| 51-100        | 33        | 28.21%  |
| 1-50          | 5         | 4.27%   |
| 161-240       | 2         | 1.71%   |
| More than 240 | 1         | 0.85%   |
| Unknown       | 1         | 0.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 102       | 86.44%  |
| 2     | 11        | 9.32%   |
| 4     | 2         | 1.69%   |
| 0     | 2         | 1.69%   |
| 3     | 1         | 0.85%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 53        | 30.64%  |
| Realtek Semiconductor                 | 46        | 26.59%  |
| Qualcomm Atheros                      | 27        | 15.61%  |
| Broadcom                              | 15        | 8.67%   |
| Broadcom Limited                      | 8         | 4.62%   |
| Marvell Technology Group              | 3         | 1.73%   |
| Silicon Integrated Systems [SiS]      | 2         | 1.16%   |
| Ralink                                | 2         | 1.16%   |
| Qualcomm                              | 2         | 1.16%   |
| ASIX Electronics                      | 2         | 1.16%   |
| Xiaomi                                | 1         | 0.58%   |
| TP-Link                               | 1         | 0.58%   |
| Ralink Technology                     | 1         | 0.58%   |
| Qualcomm Atheros Communications       | 1         | 0.58%   |
| Nvidia                                | 1         | 0.58%   |
| MediaTek                              | 1         | 0.58%   |
| Lenovo                                | 1         | 0.58%   |
| Huawei Technologies                   | 1         | 0.58%   |
| Ericsson Business Mobile Networks     | 1         | 0.58%   |
| Dell                                  | 1         | 0.58%   |
| ASUSTek Computer                      | 1         | 0.58%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.58%   |
| 3Com                                  | 1         | 0.58%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller                | 25        | 12.25%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 10        | 4.9%    |
| Intel Wireless 7265                                                                   | 6         | 2.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 5         | 2.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 4         | 1.96%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 4         | 1.96%   |
| Intel Wireless 8265 / 8275                                                            | 4         | 1.96%   |
| Intel Wireless 7260                                                                   | 4         | 1.96%   |
| Intel Gemini Lake PCH CNVi WiFi                                                       | 4         | 1.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 4         | 1.96%   |
| Intel Ethernet Connection I217-V                                                      | 3         | 1.47%   |
| Intel Ethernet Connection (4) I219-LM                                                 | 3         | 1.47%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 3         | 1.47%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter                  | 3         | 1.47%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 3         | 1.47%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 3         | 1.47%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 2         | 0.98%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                              | 2         | 0.98%   |
| Realtek RTL8187SE Wireless LAN Controller                                             | 2         | 0.98%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                 | 2         | 0.98%   |
| Qualcomm POCO F3                                                                      | 2         | 0.98%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 2         | 0.98%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                             | 2         | 0.98%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 2         | 0.98%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 2         | 0.98%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                               | 2         | 0.98%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                         | 2         | 0.98%   |
| Intel Ethernet Connection I217-LM                                                     | 2         | 0.98%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 2         | 0.98%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 2         | 0.98%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                                         | 2         | 0.98%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                                     | 2         | 0.98%   |
| Broadcom Limited BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller           | 2         | 0.98%   |
| ASIX AX88179 Gigabit Ethernet                                                         | 2         | 0.98%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                        | 1         | 0.49%   |
| TP-Link 802.11ac WLAN Adapter                                                         | 1         | 0.49%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                             | 1         | 0.49%   |
| Silicon Integrated Systems [SiS] AC'97 Modem Controller                               | 1         | 0.49%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                         | 1         | 0.49%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                           | 1         | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 42        | 41.18%  |
| Qualcomm Atheros                      | 20        | 19.61%  |
| Realtek Semiconductor                 | 14        | 13.73%  |
| Broadcom                              | 11        | 10.78%  |
| Broadcom Limited                      | 6         | 5.88%   |
| Ralink                                | 2         | 1.96%   |
| TP-Link                               | 1         | 0.98%   |
| Ralink Technology                     | 1         | 0.98%   |
| Qualcomm Atheros Communications       | 1         | 0.98%   |
| MediaTek                              | 1         | 0.98%   |
| Dell                                  | 1         | 0.98%   |
| ASUSTek Computer                      | 1         | 0.98%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.98%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                                                   | 6         | 5.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 5         | 4.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 4         | 3.92%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 4         | 3.92%   |
| Intel Wireless 8265 / 8275                                                            | 4         | 3.92%   |
| Intel Wireless 7260                                                                   | 4         | 3.92%   |
| Intel Gemini Lake PCH CNVi WiFi                                                       | 4         | 3.92%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 3         | 2.94%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter                  | 3         | 2.94%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 3         | 2.94%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 3         | 2.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 2         | 1.96%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                              | 2         | 1.96%   |
| Realtek RTL8187SE Wireless LAN Controller                                             | 2         | 1.96%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 2         | 1.96%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 2         | 1.96%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 2         | 1.96%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                         | 2         | 1.96%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 2         | 1.96%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 2         | 1.96%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                                         | 2         | 1.96%   |
| Broadcom Limited BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller           | 2         | 1.96%   |
| TP-Link 802.11ac WLAN Adapter                                                         | 1         | 0.98%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                           | 1         | 0.98%   |
| Realtek RTL8191SEvA Wireless LAN Controller                                           | 1         | 0.98%   |
| Realtek RTL8187 Wireless Adapter                                                      | 1         | 0.98%   |
| Realtek 802.11n WLAN Adapter                                                          | 1         | 0.98%   |
| Ralink RT5370 Wireless Adapter                                                        | 1         | 0.98%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                             | 1         | 0.98%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                                  | 1         | 0.98%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 1         | 0.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 1         | 0.98%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 1         | 0.98%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                                 | 1         | 0.98%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1         | 0.98%   |
| Qualcomm Atheros AR2427 802.11bg Wireless Network Adapter (PCI-Express)               | 1         | 0.98%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                                     | 1         | 0.98%   |
| Intel WiFi Link 5100                                                                  | 1         | 0.98%   |
| Intel Wi-Fi 6 AX201                                                                   | 1         | 0.98%   |
| Intel Wi-Fi 6 AX200                                                                   | 1         | 0.98%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 40        | 40.82%  |
| Intel                            | 29        | 29.59%  |
| Qualcomm Atheros                 | 9         | 9.18%   |
| Broadcom                         | 5         | 5.1%    |
| Marvell Technology Group         | 3         | 3.06%   |
| Silicon Integrated Systems [SiS] | 2         | 2.04%   |
| Qualcomm                         | 2         | 2.04%   |
| Broadcom Limited                 | 2         | 2.04%   |
| ASIX Electronics                 | 2         | 2.04%   |
| Xiaomi                           | 1         | 1.02%   |
| Nvidia                           | 1         | 1.02%   |
| Lenovo                           | 1         | 1.02%   |
| 3Com                             | 1         | 1.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 25        | 25.25%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 10        | 10.1%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4         | 4.04%   |
| Intel Ethernet Connection I217-V                                       | 3         | 3.03%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 3.03%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2         | 2.02%   |
| Qualcomm POCO F3                                                       | 2         | 2.02%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 2         | 2.02%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 2         | 2.02%   |
| Intel Ethernet Connection I217-LM                                      | 2         | 2.02%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 2         | 2.02%   |
| ASIX AX88179 Gigabit Ethernet                                          | 2         | 2.02%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 1.01%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet              | 1         | 1.01%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 1         | 1.01%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 1         | 1.01%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1         | 1.01%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1         | 1.01%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 1.01%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 1         | 1.01%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 1.01%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 1.01%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 1         | 1.01%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 1.01%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1         | 1.01%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 1.01%   |
| Marvell Group 88E8038 PCI-E Fast Ethernet Controller                   | 1         | 1.01%   |
| Lenovo ThinkPad TBT 3 Dock                                             | 1         | 1.01%   |
| Intel PRO/100 VE Network Connection                                    | 1         | 1.01%   |
| Intel I210 Gigabit Network Connection                                  | 1         | 1.01%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 1.01%   |
| Intel Ethernet Connection (7) I219-V                                   | 1         | 1.01%   |
| Intel Ethernet Connection (6) I219-V                                   | 1         | 1.01%   |
| Intel Ethernet Connection (5) I219-LM                                  | 1         | 1.01%   |
| Intel Ethernet Connection (3) I218-LM                                  | 1         | 1.01%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 1.01%   |
| Intel Ethernet Connection (2) I218-LM                                  | 1         | 1.01%   |
| Intel Ethernet Connection (11) I219-V                                  | 1         | 1.01%   |
| Intel Ethernet Connection (10) I219-V                                  | 1         | 1.01%   |
| Intel 82583V Gigabit Network Connection                                | 1         | 1.01%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 99        | 50.25%  |
| Ethernet | 95        | 48.22%  |
| Modem    | 3         | 1.52%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 83        | 66.4%   |
| Ethernet | 42        | 33.6%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 70        | 59.83%  |
| 1     | 45        | 38.46%  |
| 0     | 2         | 1.71%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 90        | 76.27%  |
| Yes  | 28        | 23.73%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 32        | 42.11%  |
| Qualcomm Atheros Communications | 8         | 10.53%  |
| Realtek Semiconductor           | 7         | 9.21%   |
| Apple                           | 7         | 9.21%   |
| Broadcom                        | 5         | 6.58%   |
| IMC Networks                    | 3         | 3.95%   |
| Foxconn / Hon Hai               | 3         | 3.95%   |
| Lite-On Technology              | 2         | 2.63%   |
| Toshiba                         | 1         | 1.32%   |
| Taiyo Yuden                     | 1         | 1.32%   |
| Realtek                         | 1         | 1.32%   |
| Qcom                            | 1         | 1.32%   |
| Foxconn International           | 1         | 1.32%   |
| Dell                            | 1         | 1.32%   |
| Cambridge Silicon Radio         | 1         | 1.32%   |
| Alps Electric                   | 1         | 1.32%   |
| Unknown                         | 1         | 1.32%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 16        | 21.05%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 5         | 6.58%   |
| Apple Bluetooth USB Host Controller                 | 5         | 6.58%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 4         | 5.26%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 3.95%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 3.95%   |
| Intel AX201 Bluetooth                               | 3         | 3.95%   |
| Realtek RTL8821A Bluetooth                          | 2         | 2.63%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 2.63%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 2.63%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 2.63%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 2.63%   |
| IMC Networks Bluetooth Device                       | 2         | 2.63%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2         | 2.63%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2         | 2.63%   |
| Toshiba Askey for                                   | 1         | 1.32%   |
| Taiyo Yuden Bluetooth Device(BC04-External)         | 1         | 1.32%   |
| Realtek Bluetooth Radio                             | 1         | 1.32%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 1.32%   |
| Realtek Bluetooth Radio                             | 1         | 1.32%   |
| Qcom Broadcom Bluetooth USB                         | 1         | 1.32%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.32%   |
| Intel AX211 Bluetooth                               | 1         | 1.32%   |
| Intel AX200 Bluetooth                               | 1         | 1.32%   |
| IMC Networks Wireless_Device                        | 1         | 1.32%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 1.32%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 1.32%   |
| Foxconn / Hon Hai BCM43142A0 broadcom bluetooth     | 1         | 1.32%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 1.32%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 1.32%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 1.32%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.32%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 1.32%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.32%   |
| Alps Electric BCM2046 Bluetooth Device              | 1         | 1.32%   |
| Unknown                                             | 1         | 1.32%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 97        | 65.99%  |
| AMD                              | 21        | 14.29%  |
| Nvidia                           | 19        | 12.93%  |
| Silicon Integrated Systems [SiS] | 2         | 1.36%   |
| Generalplus Technology           | 2         | 1.36%   |
| VIA Technologies                 | 1         | 0.68%   |
| Tenx Technology                  | 1         | 0.68%   |
| Logitech                         | 1         | 0.68%   |
| Lenovo                           | 1         | 0.68%   |
| GYROCOM C&C                      | 1         | 0.68%   |
| GN Netcom                        | 1         | 0.68%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 11        | 6.63%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 10        | 6.02%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 9         | 5.42%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 7         | 4.22%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7         | 4.22%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 3.61%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 3.61%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 3.01%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 3.01%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 5         | 3.01%   |
| Nvidia High Definition Audio Controller                                                           | 4         | 2.41%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 2.41%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 2.41%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.81%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 1.81%   |
| AMD FCH Azalia Controller                                                                         | 3         | 1.81%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 3         | 1.81%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 1.2%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 1.2%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 1.2%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.2%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.2%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 1.2%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 1.2%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.2%    |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 2         | 1.2%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.2%    |
| Generalplus Technology USB Audio Device                                                           | 2         | 1.2%    |
| AMD RV770 HDMI Audio [Radeon HD 4850/4870]                                                        | 2         | 1.2%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 1.2%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 1.2%    |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.2%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1.2%    |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                                         | 1         | 0.6%    |
| Tenx Technology USB AUDIO                                                                         | 1         | 0.6%    |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                                   | 1         | 0.6%    |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.6%    |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.6%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.6%    |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 34        | 26.36%  |
| Unknown             | 24        | 18.6%   |
| SK hynix            | 21        | 16.28%  |
| Kingston            | 14        | 10.85%  |
| Micron Technology   | 9         | 6.98%   |
| Crucial             | 6         | 4.65%   |
| Corsair             | 4         | 3.1%    |
| Ramaxel Technology  | 2         | 1.55%   |
| ff                  | 2         | 1.55%   |
| Elpida              | 2         | 1.55%   |
| A-DATA Technology   | 2         | 1.55%   |
| 4ea5                | 2         | 1.55%   |
| Unknown             | 2         | 1.55%   |
| Unknown (ABCD)      | 1         | 0.78%   |
| Qimonda             | 1         | 0.78%   |
| G.Skill             | 1         | 0.78%   |
| fef5                | 1         | 0.78%   |
| CSX                 | 1         | 0.78%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 3         | 2.13%   |
| Samsung RAM K4E8E324EB-EGCF 2GB LPDDR3 1867MT/s                  | 3         | 2.13%   |
| Unknown RAM Module 512MB SODIMM DDR                              | 2         | 1.42%   |
| Unknown RAM Module 512MB DIMM                                    | 2         | 1.42%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 2         | 1.42%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 2         | 1.42%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 1.42%   |
| SK hynix RAM H9HCNNN8KUMLHR-NME 1GB LPDDR4 2400MT/s              | 2         | 1.42%   |
| Samsung RAM Module 4GB Row Of Chips DDR4 2400MT/s                | 2         | 1.42%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.42%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 2         | 1.42%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 1.42%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 1.42%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s          | 2         | 1.42%   |
| Kingston RAM 99U5428-063.A00LF 8GB SODIMM DDR3 2667MT/s          | 2         | 1.42%   |
| Unknown                                                          | 2         | 1.42%   |
| Unknown RAM Module 8GB SODIMM DDR3                               | 1         | 0.71%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                     | 1         | 0.71%   |
| Unknown RAM Module 512MB DIMM SDRAM                              | 1         | 0.71%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 0.71%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                             | 1         | 0.71%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1067MT/s                   | 1         | 0.71%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                       | 1         | 0.71%   |
| Unknown RAM Module 2GB SODIMM DDR                                | 1         | 0.71%   |
| Unknown RAM Module 2GB DIMM DDR3 800MT/s                         | 1         | 0.71%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 1         | 0.71%   |
| Unknown RAM Module 256MB DIMM                                    | 1         | 0.71%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 1         | 0.71%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 1         | 0.71%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s                      | 1         | 0.71%   |
| Unknown RAM Module 2048MB DIMM DDR2 333MT/s                      | 1         | 0.71%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                       | 1         | 0.71%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 1         | 0.71%   |
| Unknown RAM Module 1024MB SODIMM DDR                             | 1         | 0.71%   |
| Unknown RAM 3733 C17 Series 8192MB DIMM DDR4 2133MT/s            | 1         | 0.71%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 1         | 0.71%   |
| SK hynix RAM Module 512MB SODIMM DDR2 533MT/s                    | 1         | 0.71%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.71%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 1         | 0.71%   |
| SK hynix RAM HYMP112S64CP6-Y5 1GB SODIMM DDR2 667MT/s            | 1         | 0.71%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 45        | 40.18%  |
| DDR4    | 29        | 25.89%  |
| DDR2    | 14        | 12.5%   |
| LPDDR4  | 7         | 6.25%   |
| DDR     | 5         | 4.46%   |
| Unknown | 5         | 4.46%   |
| LPDDR3  | 4         | 3.57%   |
| SDRAM   | 2         | 1.79%   |
| LPDDR5  | 1         | 0.89%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 68        | 62.96%  |
| DIMM         | 25        | 23.15%  |
| Row Of Chips | 7         | 6.48%   |
| Unknown      | 7         | 6.48%   |
| Chip         | 1         | 0.93%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 38        | 31.4%   |
| 2048  | 27        | 22.31%  |
| 8192  | 26        | 21.49%  |
| 1024  | 15        | 12.4%   |
| 16384 | 8         | 6.61%   |
| 512   | 6         | 4.96%   |
| 256   | 1         | 0.83%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 22        | 18.49%  |
| 2400    | 15        | 12.61%  |
| 2667    | 13        | 10.92%  |
| Unknown | 10        | 8.4%    |
| 3200    | 8         | 6.72%   |
| 1333    | 7         | 5.88%   |
| 1067    | 5         | 4.2%    |
| 667     | 5         | 4.2%    |
| 1867    | 4         | 3.36%   |
| 800     | 4         | 3.36%   |
| 533     | 4         | 3.36%   |
| 2133    | 3         | 2.52%   |
| 1334    | 3         | 2.52%   |
| 3266    | 2         | 1.68%   |
| 1866    | 2         | 1.68%   |
| 1066    | 2         | 1.68%   |
| 6400    | 1         | 0.84%   |
| 4267    | 1         | 0.84%   |
| 4199    | 1         | 0.84%   |
| 4000    | 1         | 0.84%   |
| 3800    | 1         | 0.84%   |
| 3733    | 1         | 0.84%   |
| 3000    | 1         | 0.84%   |
| 2000    | 1         | 0.84%   |
| 1632    | 1         | 0.84%   |
| 333     | 1         | 0.84%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 1         | 33.33%  |
| Canon              | 1         | 33.33%  |
| Brother Industries | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| HP DeskJet 2700 series        | 1         | 33.33%  |
| Canon iP2800 series           | 1         | 33.33%  |
| Brother HL-2030 Laser Printer | 1         | 33.33%  |

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 23        | 31.94%  |
| Realtek Semiconductor                  | 8         | 11.11%  |
| IMC Networks                           | 8         | 11.11%  |
| Microdia                               | 4         | 5.56%   |
| Bison Electronics                      | 4         | 5.56%   |
| Suyin                                  | 3         | 4.17%   |
| Sunplus Innovation Technology          | 3         | 4.17%   |
| Silicon Motion                         | 3         | 4.17%   |
| Quanta                                 | 3         | 4.17%   |
| Apple                                  | 3         | 4.17%   |
| Z-Star Microelectronics                | 1         | 1.39%   |
| Syntek                                 | 1         | 1.39%   |
| Ricoh                                  | 1         | 1.39%   |
| Logitech                               | 1         | 1.39%   |
| Lite-On Technology                     | 1         | 1.39%   |
| icSpring                               | 1         | 1.39%   |
| Hewlett-Packard                        | 1         | 1.39%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.39%   |
| ALi                                    | 1         | 1.39%   |
| Acer                                   | 1         | 1.39%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Chicony HD WebCam                        | 5         | 6.76%   |
| Chicony Integrated Camera                | 3         | 4.05%   |
| Realtek Lenovo EasyCamera                | 2         | 2.7%    |
| Realtek Integrated Camera                | 2         | 2.7%    |
| IMC Networks USB2.0 HD UVC WebCam        | 2         | 2.7%    |
| IMC Networks Integrated Camera           | 2         | 2.7%    |
| Chicony Sony Visual Communication Camera | 2         | 2.7%    |
| Chicony HP TrueVision HD Camera          | 2         | 2.7%    |
| Bison Lenovo Integrated Webcam           | 2         | 2.7%    |
| Apple Built-in iSight                    | 2         | 2.7%    |
| Z-Star Integrated Camera                 | 1         | 1.35%   |
| Syntek HP Webcam                         | 1         | 1.35%   |
| Suyin Integrated_Webcam_HD               | 1         | 1.35%   |
| Suyin HP Webcam                          | 1         | 1.35%   |
| Suyin Acer CrystalEye Webcam             | 1         | 1.35%   |
| Sunplus Laptop_Integrated_Webcam_1.3M    | 1         | 1.35%   |
| Sunplus Full HD webcam                   | 1         | 1.35%   |
| Sunplus Dell Integrated Webcam           | 1         | 1.35%   |
| Silicon Motion WebCam SC-10HDD12636N     | 1         | 1.35%   |
| Silicon Motion HP Webcam-50              | 1         | 1.35%   |
| Silicon Motion 720p HD Camera            | 1         | 1.35%   |
| Ricoh Sony Vaio Integrated Webcam        | 1         | 1.35%   |
| Realtek Integrated_Webcam_HD             | 1         | 1.35%   |
| Realtek HP Webcam                        | 1         | 1.35%   |
| Realtek HD WebCam                        | 1         | 1.35%   |
| Realtek FJ Camera                        | 1         | 1.35%   |
| Quanta VGA User Facing                   | 1         | 1.35%   |
| Quanta HP Webcam                         | 1         | 1.35%   |
| Quanta HD WebCam                         | 1         | 1.35%   |
| Microdia USB 2.0 Camera                  | 1         | 1.35%   |
| Microdia Laptop_Integrated_Webcam_2M     | 1         | 1.35%   |
| Microdia Integrated_Webcam_HD            | 1         | 1.35%   |
| Microdia Camera                          | 1         | 1.35%   |
| Logitech Webcam C930e                    | 1         | 1.35%   |
| Logitech BCC950 ConferenceCam            | 1         | 1.35%   |
| Lite-On Integrated Camera                | 1         | 1.35%   |
| IMC Networks USB2.0 5M AF UVC WebCam     | 1         | 1.35%   |
| IMC Networks USB 2.0 Camera              | 1         | 1.35%   |
| IMC Networks ov9734_azurewave_camera     | 1         | 1.35%   |
| IMC Networks HP TrueVision HD Camera     | 1         | 1.35%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 37.5%   |
| Synaptics                  | 4         | 25%     |
| Elan Microelectronics      | 2         | 12.5%   |
| AuthenTec                  | 2         | 12.5%   |
| STMicroelectronics         | 1         | 6.25%   |
| Shenzhen Goodix Technology | 1         | 6.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 18.75%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 6.25%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 6.25%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 6.25%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 6.25%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 6.25%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 6.25%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 6.25%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 6.25%   |
| Shenzhen Goodix  Fingerprint Device                                        | 1         | 6.25%   |
| Elan WBF Fingerprint Sensor                                                | 1         | 6.25%   |
| Elan ELAN:Fingerprint                                                      | 1         | 6.25%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 6.25%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 6.25%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 2         | 40%     |
| Alcor Micro | 2         | 40%     |
| O2 Micro    | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 40%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 20%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 20%     |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 72        | 60.5%   |
| 1     | 37        | 31.09%  |
| 2     | 8         | 6.72%   |
| 3     | 2         | 1.68%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 19        | 33.33%  |
| Fingerprint reader       | 16        | 28.07%  |
| Net/wireless             | 5         | 8.77%   |
| Communication controller | 5         | 8.77%   |
| Chipcard                 | 5         | 8.77%   |
| Multimedia controller    | 4         | 7.02%   |
| Unassigned class         | 1         | 1.75%   |
| Card reader              | 1         | 1.75%   |
| Camera                   | 1         | 1.75%   |

