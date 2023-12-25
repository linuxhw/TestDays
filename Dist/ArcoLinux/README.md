ArcoLinux - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for ArcoLinux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/ArcoLinux/Desktop/README.md) and [notebooks](/Dist/ArcoLinux/Notebook/README.md).

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

Total: 3813

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | X670 GAMING X AX            | Desktop     | [4452cd4a25](https://linux-hardware.org/?probe=4452cd4a25) | Dec 24, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [2c88ade0b2](https://linux-hardware.org/?probe=2c88ade0b2) | Dec 23, 2023 |
| Lenovo        | ThinkPad T420 4178AFU       | Notebook    | [67caa6c117](https://linux-hardware.org/?probe=67caa6c117) | Dec 23, 2023 |
| System76      | Gazelle                     | Notebook    | [2b9bce59e7](https://linux-hardware.org/?probe=2b9bce59e7) | Dec 23, 2023 |
| Acer          | H81-M1                      | Desktop     | [e9fd2a5dc4](https://linux-hardware.org/?probe=e9fd2a5dc4) | Dec 23, 2023 |
| MSI           | PRO H410M-B                 | Desktop     | [28d6a6092b](https://linux-hardware.org/?probe=28d6a6092b) | Dec 23, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | Notebook    | [30446f4198](https://linux-hardware.org/?probe=30446f4198) | Dec 23, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [851dce0b14](https://linux-hardware.org/?probe=851dce0b14) | Dec 22, 2023 |
| Acer          | Aspire E5-576               | Notebook    | [e40f16f86b](https://linux-hardware.org/?probe=e40f16f86b) | Dec 22, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [7148cd104d](https://linux-hardware.org/?probe=7148cd104d) | Dec 22, 2023 |
| ASUSTek       | N551VW                      | Notebook    | [f73a190483](https://linux-hardware.org/?probe=f73a190483) | Dec 22, 2023 |
| ASUSTek       | N551VW                      | Notebook    | [467015083e](https://linux-hardware.org/?probe=467015083e) | Dec 22, 2023 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [e0cd6655cb](https://linux-hardware.org/?probe=e0cd6655cb) | Dec 22, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [119a1632aa](https://linux-hardware.org/?probe=119a1632aa) | Dec 21, 2023 |
| Lenovo        | ThinkPad T440 20B6005BUS    | Notebook    | [d699475273](https://linux-hardware.org/?probe=d699475273) | Dec 21, 2023 |
| Lenovo        | ThinkPad T440 20B70048US    | Notebook    | [f937778ee0](https://linux-hardware.org/?probe=f937778ee0) | Dec 21, 2023 |
| ASUSTek       | Z87-PRO                     | Desktop     | [1c5b8cb7de](https://linux-hardware.org/?probe=1c5b8cb7de) | Dec 21, 2023 |
| Razer         | Blade 15 (2022) - RZ09-0... | Notebook    | [4e4e1e2329](https://linux-hardware.org/?probe=4e4e1e2329) | Dec 21, 2023 |
| Lenovo        | ThinkPad T550 20CJS1MW00    | Notebook    | [f5bb1db361](https://linux-hardware.org/?probe=f5bb1db361) | Dec 21, 2023 |
| Lenovo        | ThinkPad T440 20B6005BUS    | Notebook    | [bf412b1477](https://linux-hardware.org/?probe=bf412b1477) | Dec 20, 2023 |
| Lenovo        | ThinkPad T440 20B70048US    | Notebook    | [d6a79599da](https://linux-hardware.org/?probe=d6a79599da) | Dec 20, 2023 |
| Gigabyte      | Z690 AORUS XTREME           | Desktop     | [c721656dbe](https://linux-hardware.org/?probe=c721656dbe) | Dec 20, 2023 |
| MSI           | A78M-E45                    | Desktop     | [6d11f72d41](https://linux-hardware.org/?probe=6d11f72d41) | Dec 20, 2023 |
| Lenovo        | ThinkBook 16 G4+ IAP 21C... | Notebook    | [adb83b1dca](https://linux-hardware.org/?probe=adb83b1dca) | Dec 20, 2023 |
| Lenovo        | ThinkPad T550 20CJS1MW00    | Notebook    | [e6bc9160c8](https://linux-hardware.org/?probe=e6bc9160c8) | Dec 20, 2023 |
| ASUSTek       | ROG Flow Z13 GZ301ZE_GZ3... | Tablet      | [b89f7b2b47](https://linux-hardware.org/?probe=b89f7b2b47) | Dec 20, 2023 |
| MSI           | Alpha 17 C7VF               | Notebook    | [34b3014f66](https://linux-hardware.org/?probe=34b3014f66) | Dec 19, 2023 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | Desktop     | [4ea2f3364d](https://linux-hardware.org/?probe=4ea2f3364d) | Dec 19, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | Desktop     | [3dee3cb4bf](https://linux-hardware.org/?probe=3dee3cb4bf) | Dec 19, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [2b7ff14fc2](https://linux-hardware.org/?probe=2b7ff14fc2) | Dec 19, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [18cb796b47](https://linux-hardware.org/?probe=18cb796b47) | Dec 19, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [552bc11608](https://linux-hardware.org/?probe=552bc11608) | Dec 19, 2023 |
| Win elemen... | M600                        | Desktop     | [0d0f7a6719](https://linux-hardware.org/?probe=0d0f7a6719) | Dec 19, 2023 |
| Unknown       | HX90                        | Desktop     | [2bf61c79c6](https://linux-hardware.org/?probe=2bf61c79c6) | Dec 18, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [38b0463b4a](https://linux-hardware.org/?probe=38b0463b4a) | Dec 18, 2023 |
| ASUSTek       | WS X299 SAGE                | Desktop     | [cc5a70ea88](https://linux-hardware.org/?probe=cc5a70ea88) | Dec 18, 2023 |
| Lenovo        | Legion 5 15IMH6 82NL        | Notebook    | [e54630a5d8](https://linux-hardware.org/?probe=e54630a5d8) | Dec 18, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | Notebook    | [8596edc762](https://linux-hardware.org/?probe=8596edc762) | Dec 18, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [ce269919cd](https://linux-hardware.org/?probe=ce269919cd) | Dec 18, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [bd0bcd2eba](https://linux-hardware.org/?probe=bd0bcd2eba) | Dec 18, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [a62323f9e3](https://linux-hardware.org/?probe=a62323f9e3) | Dec 18, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [474668dbec](https://linux-hardware.org/?probe=474668dbec) | Dec 18, 2023 |
| ASUSTek       | WS X299 SAGE                | Desktop     | [6e76ff78f6](https://linux-hardware.org/?probe=6e76ff78f6) | Dec 18, 2023 |
| MSI           | X470 GAMING PRO             | Desktop     | [64d4715e81](https://linux-hardware.org/?probe=64d4715e81) | Dec 18, 2023 |
| AZW           | SER                         | Mini pc     | [2768e13f4c](https://linux-hardware.org/?probe=2768e13f4c) | Dec 18, 2023 |
| ASUSTek       | X99-WS/IPMI                 | Desktop     | [d6ddc6fdde](https://linux-hardware.org/?probe=d6ddc6fdde) | Dec 18, 2023 |
| HP            | 18E7                        | Desktop     | [20a3bd6bee](https://linux-hardware.org/?probe=20a3bd6bee) | Dec 17, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [cb94175bab](https://linux-hardware.org/?probe=cb94175bab) | Dec 17, 2023 |
| ASRock        | X670E Taichi Carrara        | Desktop     | [2d0eb33a7a](https://linux-hardware.org/?probe=2d0eb33a7a) | Dec 17, 2023 |
| Dell          | Inspiron 3580               | Notebook    | [1daafa6278](https://linux-hardware.org/?probe=1daafa6278) | Dec 17, 2023 |
| Lenovo        | ThinkPad X220 4286AQ7       | Notebook    | [ffea6e3dbe](https://linux-hardware.org/?probe=ffea6e3dbe) | Dec 17, 2023 |
| Lenovo        | ThinkPad X220 4286AQ7       | Notebook    | [a09d44706c](https://linux-hardware.org/?probe=a09d44706c) | Dec 17, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [1c2f8035bb](https://linux-hardware.org/?probe=1c2f8035bb) | Dec 17, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [316b12645c](https://linux-hardware.org/?probe=316b12645c) | Dec 17, 2023 |
| Toshiba       | Satellite C50-A-1HF         | Notebook    | [ac7985ff69](https://linux-hardware.org/?probe=ac7985ff69) | Dec 17, 2023 |
| Dell          | Inspiron 3580               | Notebook    | [16097eb9c4](https://linux-hardware.org/?probe=16097eb9c4) | Dec 17, 2023 |
| Lenovo        | ThinkPad P43s 20RH0021MX    | Notebook    | [c95903375b](https://linux-hardware.org/?probe=c95903375b) | Dec 17, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [9105f33be2](https://linux-hardware.org/?probe=9105f33be2) | Dec 16, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [f64fa9a501](https://linux-hardware.org/?probe=f64fa9a501) | Dec 16, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [36f9f51f5d](https://linux-hardware.org/?probe=36f9f51f5d) | Dec 16, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [d1d3bc7a1c](https://linux-hardware.org/?probe=d1d3bc7a1c) | Dec 16, 2023 |
| ASUSTek       | Zenbook UM6702RC_RM6702R... | Notebook    | [c3c947f23f](https://linux-hardware.org/?probe=c3c947f23f) | Dec 16, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [f210e0dd64](https://linux-hardware.org/?probe=f210e0dd64) | Dec 16, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [890cf9cc41](https://linux-hardware.org/?probe=890cf9cc41) | Dec 16, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | Desktop     | [7866cd7449](https://linux-hardware.org/?probe=7866cd7449) | Dec 16, 2023 |
| HP            | G60                         | Notebook    | [9fabfc936c](https://linux-hardware.org/?probe=9fabfc936c) | Dec 16, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [ec182b1b52](https://linux-hardware.org/?probe=ec182b1b52) | Dec 16, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [b761d5e550](https://linux-hardware.org/?probe=b761d5e550) | Dec 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [6d72d7366b](https://linux-hardware.org/?probe=6d72d7366b) | Dec 15, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | Notebook    | [de6ccbb0bc](https://linux-hardware.org/?probe=de6ccbb0bc) | Dec 15, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [f4af1a07e3](https://linux-hardware.org/?probe=f4af1a07e3) | Dec 15, 2023 |
| HP            | 18E7                        | Desktop     | [5923f47c4b](https://linux-hardware.org/?probe=5923f47c4b) | Dec 15, 2023 |
| Unknown       | Unknown                     | Notebook    | [071d7464d1](https://linux-hardware.org/?probe=071d7464d1) | Dec 15, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [9caa48ce75](https://linux-hardware.org/?probe=9caa48ce75) | Dec 14, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [39f4b40998](https://linux-hardware.org/?probe=39f4b40998) | Dec 14, 2023 |
| Dell          | 0TTDMJ A00                  | Desktop     | [66477630d7](https://linux-hardware.org/?probe=66477630d7) | Dec 14, 2023 |
| MSI           | GS66 Stealth 10SE           | Notebook    | [7f045bdc89](https://linux-hardware.org/?probe=7f045bdc89) | Dec 14, 2023 |
| ASUSTek       | Z87-PRO                     | Desktop     | [5ea78096f6](https://linux-hardware.org/?probe=5ea78096f6) | Dec 14, 2023 |
| HP            | 1495                        | Desktop     | [e187132e56](https://linux-hardware.org/?probe=e187132e56) | Dec 14, 2023 |
| ASRock        | A300M-STX                   | Desktop     | [f6f4e86ea3](https://linux-hardware.org/?probe=f6f4e86ea3) | Dec 13, 2023 |
| HP            | 1495                        | Desktop     | [7c74116b39](https://linux-hardware.org/?probe=7c74116b39) | Dec 13, 2023 |
| AZW           | SER                         | Mini pc     | [e114084bcd](https://linux-hardware.org/?probe=e114084bcd) | Dec 13, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [656732b40e](https://linux-hardware.org/?probe=656732b40e) | Dec 12, 2023 |
| Lenovo        | IdeaPad 320-14IKB 80XK      | Notebook    | [df2900565f](https://linux-hardware.org/?probe=df2900565f) | Dec 12, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [f34c061189](https://linux-hardware.org/?probe=f34c061189) | Dec 12, 2023 |
| Lenovo        | ThinkPad T480s 20L8S5LK0... | Notebook    | [e8ebbc8111](https://linux-hardware.org/?probe=e8ebbc8111) | Dec 12, 2023 |
| Gigabyte      | Z97X-UD5H                   | Desktop     | [b42f33ca53](https://linux-hardware.org/?probe=b42f33ca53) | Dec 12, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [11ae906f6f](https://linux-hardware.org/?probe=11ae906f6f) | Dec 11, 2023 |
| Acer          | H81-M1                      | Desktop     | [c6f5b1d841](https://linux-hardware.org/?probe=c6f5b1d841) | Dec 11, 2023 |
| NVN-ED01      | Unknown                     | Notebook    | [3705f36f2b](https://linux-hardware.org/?probe=3705f36f2b) | Dec 11, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [4afc28a0da](https://linux-hardware.org/?probe=4afc28a0da) | Dec 11, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [fc475e4cd3](https://linux-hardware.org/?probe=fc475e4cd3) | Dec 11, 2023 |
| Apple         | MacBookAir7,1               | Notebook    | [b6d0160123](https://linux-hardware.org/?probe=b6d0160123) | Dec 11, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | Notebook    | [f24c11f324](https://linux-hardware.org/?probe=f24c11f324) | Dec 11, 2023 |
| ASUSTek       | Q304UAK                     | Convertible | [7c98d7ffe7](https://linux-hardware.org/?probe=7c98d7ffe7) | Dec 11, 2023 |
| HP            | 1850                        | Desktop     | [903e4b5eb1](https://linux-hardware.org/?probe=903e4b5eb1) | Dec 11, 2023 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [43516f3ae9](https://linux-hardware.org/?probe=43516f3ae9) | Dec 10, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [66edf53f93](https://linux-hardware.org/?probe=66edf53f93) | Dec 10, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [0e463b364d](https://linux-hardware.org/?probe=0e463b364d) | Dec 10, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [367489ed4f](https://linux-hardware.org/?probe=367489ed4f) | Dec 10, 2023 |
| Dell          | Inspiron 15-3552            | Notebook    | [39d34daca5](https://linux-hardware.org/?probe=39d34daca5) | Dec 10, 2023 |
| Acer          | Spin SP513-51               | Convertible | [654c8b4199](https://linux-hardware.org/?probe=654c8b4199) | Dec 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [60b75920a4](https://linux-hardware.org/?probe=60b75920a4) | Dec 10, 2023 |
| MSI           | CR610M                      | Notebook    | [f182f4595a](https://linux-hardware.org/?probe=f182f4595a) | Dec 10, 2023 |
| Dell          | Inspiron 3580               | Notebook    | [47f1e44c7d](https://linux-hardware.org/?probe=47f1e44c7d) | Dec 09, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [72c0c4e3a0](https://linux-hardware.org/?probe=72c0c4e3a0) | Dec 09, 2023 |
| Dell          | 0F373D A00                  | Desktop     | [cf693d5429](https://linux-hardware.org/?probe=cf693d5429) | Dec 09, 2023 |
| MSI           | A520M PRO-VH                | Desktop     | [96475c0e77](https://linux-hardware.org/?probe=96475c0e77) | Dec 08, 2023 |
| ASRock        | X670E Taichi Carrara        | Desktop     | [9050f85bc9](https://linux-hardware.org/?probe=9050f85bc9) | Dec 08, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [69e785cddb](https://linux-hardware.org/?probe=69e785cddb) | Dec 07, 2023 |
| Acer          | H81-M1                      | Desktop     | [76ff7a29ae](https://linux-hardware.org/?probe=76ff7a29ae) | Dec 07, 2023 |
| MSI           | Z97 PC Mate                 | Desktop     | [23a0828c28](https://linux-hardware.org/?probe=23a0828c28) | Dec 07, 2023 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [a6f429594d](https://linux-hardware.org/?probe=a6f429594d) | Dec 07, 2023 |
| Lenovo        | Win8 Pro DPK TPG            | Desktop     | [5183612439](https://linux-hardware.org/?probe=5183612439) | Dec 07, 2023 |
| HP            | Laptop 15-fd0xxx            | Notebook    | [6bdc66013b](https://linux-hardware.org/?probe=6bdc66013b) | Dec 07, 2023 |
| Positivo B... | VJFE59F11X-B1011H           | Notebook    | [2f497e2103](https://linux-hardware.org/?probe=2f497e2103) | Dec 06, 2023 |
| HP            | 2AFB                        | Desktop     | [a91d9cd265](https://linux-hardware.org/?probe=a91d9cd265) | Dec 06, 2023 |
| ASUSTek       | PRIME B550M-A AC            | Desktop     | [9b36560b08](https://linux-hardware.org/?probe=9b36560b08) | Dec 06, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [20c7a1d11b](https://linux-hardware.org/?probe=20c7a1d11b) | Dec 06, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [e36be09527](https://linux-hardware.org/?probe=e36be09527) | Dec 06, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [3c1c6e89b6](https://linux-hardware.org/?probe=3c1c6e89b6) | Dec 06, 2023 |
| Gigabyte      | B550 AORUS MASTER           | Desktop     | [d52d7379c3](https://linux-hardware.org/?probe=d52d7379c3) | Dec 06, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [54d3b585e6](https://linux-hardware.org/?probe=54d3b585e6) | Dec 05, 2023 |
| Gigabyte      | Z390 UD V2                  | Desktop     | [2d85fb4799](https://linux-hardware.org/?probe=2d85fb4799) | Dec 05, 2023 |
| Gigabyte      | H370M DS3H-CF               | Desktop     | [332f084cba](https://linux-hardware.org/?probe=332f084cba) | Dec 05, 2023 |
| HP            | EliteBook 2740p             | Notebook    | [796859e80e](https://linux-hardware.org/?probe=796859e80e) | Dec 05, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | Notebook    | [c0cd3f5ac1](https://linux-hardware.org/?probe=c0cd3f5ac1) | Dec 05, 2023 |
| HP            | 2B0D A01                    | All in one  | [6e5c0e0326](https://linux-hardware.org/?probe=6e5c0e0326) | Dec 05, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [a635fe86e0](https://linux-hardware.org/?probe=a635fe86e0) | Dec 04, 2023 |
| Dell          | Inspiron 5584               | Notebook    | [d077f362ea](https://linux-hardware.org/?probe=d077f362ea) | Dec 04, 2023 |
| MSI           | Z590-A PRO                  | Desktop     | [4298ef81a3](https://linux-hardware.org/?probe=4298ef81a3) | Dec 04, 2023 |
| Dell          | Latitude E6230              | Notebook    | [c1e6d37718](https://linux-hardware.org/?probe=c1e6d37718) | Dec 04, 2023 |
| ASUSTek       | Z87-PRO                     | Desktop     | [a6cce7762e](https://linux-hardware.org/?probe=a6cce7762e) | Dec 04, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [2bd5efd212](https://linux-hardware.org/?probe=2bd5efd212) | Dec 04, 2023 |
| Unknown       | Unknown                     | Notebook    | [a74febcadd](https://linux-hardware.org/?probe=a74febcadd) | Dec 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [1c72ad4560](https://linux-hardware.org/?probe=1c72ad4560) | Dec 04, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [4c8abee905](https://linux-hardware.org/?probe=4c8abee905) | Dec 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [8463f6c28f](https://linux-hardware.org/?probe=8463f6c28f) | Dec 03, 2023 |
| MSI           | B450M MORTAR                | Desktop     | [5e8bdafa0a](https://linux-hardware.org/?probe=5e8bdafa0a) | Dec 03, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [3753de5af1](https://linux-hardware.org/?probe=3753de5af1) | Dec 03, 2023 |
| Lenovo        | ThinkPad E585 20KV0010US    | Notebook    | [521b65ac7a](https://linux-hardware.org/?probe=521b65ac7a) | Dec 03, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [931c17aeb7](https://linux-hardware.org/?probe=931c17aeb7) | Dec 02, 2023 |
| ASUSTek       | Zenbook UM6702RC_RM6702R... | Notebook    | [54bfb4d865](https://linux-hardware.org/?probe=54bfb4d865) | Dec 02, 2023 |
| MSI           | B460M PRO-VDH WIFI          | Desktop     | [d2ec06fb3c](https://linux-hardware.org/?probe=d2ec06fb3c) | Dec 02, 2023 |
| HP            | EliteBook 2740p             | Notebook    | [d6e3212623](https://linux-hardware.org/?probe=d6e3212623) | Dec 02, 2023 |
| ASUSTek       | ROG STRIX Z790-F GAMING ... | Desktop     | [305a40c9b7](https://linux-hardware.org/?probe=305a40c9b7) | Dec 02, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [6d97271c61](https://linux-hardware.org/?probe=6d97271c61) | Dec 02, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [0cff3cecd5](https://linux-hardware.org/?probe=0cff3cecd5) | Dec 02, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [bb033837d5](https://linux-hardware.org/?probe=bb033837d5) | Dec 02, 2023 |
| Dell          | Inspiron 7591 2n1           | Convertible | [7ed25c67ba](https://linux-hardware.org/?probe=7ed25c67ba) | Dec 01, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [3c418227c7](https://linux-hardware.org/?probe=3c418227c7) | Dec 01, 2023 |
| MSI           | Modern 14 B4MW              | Notebook    | [487fe9610f](https://linux-hardware.org/?probe=487fe9610f) | Nov 30, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [9fee8c35c3](https://linux-hardware.org/?probe=9fee8c35c3) | Nov 30, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [a27577cb3a](https://linux-hardware.org/?probe=a27577cb3a) | Nov 30, 2023 |
| ASUSTek       | TUF Gaming FX705DU_FX705... | Notebook    | [c781f63b2a](https://linux-hardware.org/?probe=c781f63b2a) | Nov 30, 2023 |
| MSI           | CR610M                      | Notebook    | [35d23c9d26](https://linux-hardware.org/?probe=35d23c9d26) | Nov 30, 2023 |
| Lenovo        | ThinkPad T480s 20L8SA3Q0... | Notebook    | [94a4aacf4f](https://linux-hardware.org/?probe=94a4aacf4f) | Nov 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K540... | Notebook    | [fc00682f42](https://linux-hardware.org/?probe=fc00682f42) | Nov 29, 2023 |
| Intel         | NUC11PHBi7 M26151-405       | Mini pc     | [ae68cd33fb](https://linux-hardware.org/?probe=ae68cd33fb) | Nov 29, 2023 |
| Lenovo        | Legion 7 16ITHg6 82K6       | Notebook    | [ce91016387](https://linux-hardware.org/?probe=ce91016387) | Nov 29, 2023 |
| ASUSTek       | ROG STRIX Z790-F GAMING ... | Desktop     | [fc8b74d0f9](https://linux-hardware.org/?probe=fc8b74d0f9) | Nov 29, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [a638d25ff0](https://linux-hardware.org/?probe=a638d25ff0) | Nov 28, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [64b58279b2](https://linux-hardware.org/?probe=64b58279b2) | Nov 28, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [5030903de4](https://linux-hardware.org/?probe=5030903de4) | Nov 28, 2023 |
| MSI           | Prestige 14H B12UCX         | Notebook    | [d7c4903da6](https://linux-hardware.org/?probe=d7c4903da6) | Nov 28, 2023 |
| ASUSTek       | K55VD                       | Notebook    | [711f565945](https://linux-hardware.org/?probe=711f565945) | Nov 28, 2023 |
| Lenovo        | ThinkPad T540p 20BE00AKZ... | Notebook    | [16a605c091](https://linux-hardware.org/?probe=16a605c091) | Nov 28, 2023 |
| Dell          | Latitude 7490               | Notebook    | [4d59532412](https://linux-hardware.org/?probe=4d59532412) | Nov 27, 2023 |
| Acer          | Aspire M5400                | Desktop     | [f0e15f3802](https://linux-hardware.org/?probe=f0e15f3802) | Nov 27, 2023 |
| ASUSTek       | X79-DELUXE                  | Desktop     | [b89bce359a](https://linux-hardware.org/?probe=b89bce359a) | Nov 27, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [22a88185d6](https://linux-hardware.org/?probe=22a88185d6) | Nov 26, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [7406ad3cc2](https://linux-hardware.org/?probe=7406ad3cc2) | Nov 26, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [b0f55cc692](https://linux-hardware.org/?probe=b0f55cc692) | Nov 26, 2023 |
| Dell          | 0V8WGR A01                  | Desktop     | [b44e627796](https://linux-hardware.org/?probe=b44e627796) | Nov 26, 2023 |
| ASUSTek       | GL552VX                     | Notebook    | [42271c5724](https://linux-hardware.org/?probe=42271c5724) | Nov 26, 2023 |
| HP            | 2000                        | Notebook    | [a9e55a3aac](https://linux-hardware.org/?probe=a9e55a3aac) | Nov 26, 2023 |
| HP            | 1497                        | Desktop     | [1cbc2dbbc9](https://linux-hardware.org/?probe=1cbc2dbbc9) | Nov 26, 2023 |
| Google        | Droid                       | Notebook    | [f0bc6c8af1](https://linux-hardware.org/?probe=f0bc6c8af1) | Nov 25, 2023 |
| MSI           | Prestige 14H B12UCX         | Notebook    | [6034c0b26d](https://linux-hardware.org/?probe=6034c0b26d) | Nov 25, 2023 |
| Lenovo        | ThinkPad T470p 20J6000TA... | Notebook    | [0bccb463ab](https://linux-hardware.org/?probe=0bccb463ab) | Nov 25, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [be0df0a38d](https://linux-hardware.org/?probe=be0df0a38d) | Nov 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [e39da12205](https://linux-hardware.org/?probe=e39da12205) | Nov 24, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [a2313adb82](https://linux-hardware.org/?probe=a2313adb82) | Nov 24, 2023 |
| Dell          | Latitude E5450              | Notebook    | [1a04febc14](https://linux-hardware.org/?probe=1a04febc14) | Nov 24, 2023 |
| Intel         | NUC11PHBi7 M26151-405       | Mini pc     | [cb4bc04f74](https://linux-hardware.org/?probe=cb4bc04f74) | Nov 24, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [d1462624ea](https://linux-hardware.org/?probe=d1462624ea) | Nov 24, 2023 |
| NZXT          | N7 B550                     | Desktop     | [eda34615ff](https://linux-hardware.org/?probe=eda34615ff) | Nov 24, 2023 |
| MSI           | GF65 Thin 10UE              | Notebook    | [1eb750acac](https://linux-hardware.org/?probe=1eb750acac) | Nov 23, 2023 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [cb6301a778](https://linux-hardware.org/?probe=cb6301a778) | Nov 23, 2023 |
| BESSTAR Te... | UM700                       | Desktop     | [2be2b94342](https://linux-hardware.org/?probe=2be2b94342) | Nov 23, 2023 |
| MSI           | Prestige 15 A10SC           | Notebook    | [3b9404eda4](https://linux-hardware.org/?probe=3b9404eda4) | Nov 23, 2023 |
| Dell          | Latitude E5450              | Notebook    | [173c3b97bb](https://linux-hardware.org/?probe=173c3b97bb) | Nov 23, 2023 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [8470d1677a](https://linux-hardware.org/?probe=8470d1677a) | Nov 22, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [abb0181b70](https://linux-hardware.org/?probe=abb0181b70) | Nov 22, 2023 |
| ASUSTek       | X542URR                     | Notebook    | [7fb275b8f2](https://linux-hardware.org/?probe=7fb275b8f2) | Nov 22, 2023 |
| HP            | 18E7                        | Desktop     | [594059fee8](https://linux-hardware.org/?probe=594059fee8) | Nov 21, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [3b815bebf3](https://linux-hardware.org/?probe=3b815bebf3) | Nov 21, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | Desktop     | [420d9baddf](https://linux-hardware.org/?probe=420d9baddf) | Nov 21, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [42064a20b4](https://linux-hardware.org/?probe=42064a20b4) | Nov 21, 2023 |
| Shenzhen M... | F7BFC                       | Desktop     | [bd7cd76d26](https://linux-hardware.org/?probe=bd7cd76d26) | Nov 20, 2023 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [6e05364421](https://linux-hardware.org/?probe=6e05364421) | Nov 20, 2023 |
| Lenovo        | ThinkPad T540p 20BFS5DV0... | Notebook    | [99ea5fbbc2](https://linux-hardware.org/?probe=99ea5fbbc2) | Nov 20, 2023 |
| Dell          | 0KV62T A00                  | Desktop     | [72b1a867da](https://linux-hardware.org/?probe=72b1a867da) | Nov 20, 2023 |
| Dell          | Inspiron 5584               | Notebook    | [9e43d7f684](https://linux-hardware.org/?probe=9e43d7f684) | Nov 20, 2023 |
| Acer          | Predator PO3-630            | Desktop     | [8919926380](https://linux-hardware.org/?probe=8919926380) | Nov 20, 2023 |
| MSI           | CR610M                      | Notebook    | [66ca456fa1](https://linux-hardware.org/?probe=66ca456fa1) | Nov 19, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [2018ab1ad9](https://linux-hardware.org/?probe=2018ab1ad9) | Nov 19, 2023 |
| MACHENIKE     | L16W                        | Notebook    | [7c881a79a6](https://linux-hardware.org/?probe=7c881a79a6) | Nov 19, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [cfc45028e8](https://linux-hardware.org/?probe=cfc45028e8) | Nov 19, 2023 |
| Lenovo        | ThinkPad T510 4314RBS       | Notebook    | [883b10d260](https://linux-hardware.org/?probe=883b10d260) | Nov 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [9073144bc1](https://linux-hardware.org/?probe=9073144bc1) | Nov 19, 2023 |
| Acer          | Aspire E1-532G              | Notebook    | [986077984e](https://linux-hardware.org/?probe=986077984e) | Nov 18, 2023 |
| Dell          | Precision M6800             | Notebook    | [14dc3b5711](https://linux-hardware.org/?probe=14dc3b5711) | Nov 18, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [41a350bfbd](https://linux-hardware.org/?probe=41a350bfbd) | Nov 18, 2023 |
| ASUSTek       | H110M-A                     | Desktop     | [79a1012336](https://linux-hardware.org/?probe=79a1012336) | Nov 18, 2023 |
| Lenovo        | ThinkPad T550 20CJS1MW00    | Notebook    | [ea53f8ef4f](https://linux-hardware.org/?probe=ea53f8ef4f) | Nov 18, 2023 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [eeef8f244c](https://linux-hardware.org/?probe=eeef8f244c) | Nov 18, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [60a416739f](https://linux-hardware.org/?probe=60a416739f) | Nov 17, 2023 |
| Monster       | ABRA A5 V17.2               | Notebook    | [130ef88703](https://linux-hardware.org/?probe=130ef88703) | Nov 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [55df37c5d0](https://linux-hardware.org/?probe=55df37c5d0) | Nov 17, 2023 |
| Monster       | ABRA A5 V17.2               | Notebook    | [76653a926b](https://linux-hardware.org/?probe=76653a926b) | Nov 17, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [a7467830d5](https://linux-hardware.org/?probe=a7467830d5) | Nov 17, 2023 |
| Acer          | Nitro N50-610               | Desktop     | [648f624587](https://linux-hardware.org/?probe=648f624587) | Nov 16, 2023 |
| Dell          | 500                         | Notebook    | [9a40219351](https://linux-hardware.org/?probe=9a40219351) | Nov 16, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [b33b5da196](https://linux-hardware.org/?probe=b33b5da196) | Nov 16, 2023 |
| Lenovo        | Legion R9000P2021H 82JQ     | Notebook    | [6de33389c6](https://linux-hardware.org/?probe=6de33389c6) | Nov 16, 2023 |
| Apple         | MacBookAir5,1               | Notebook    | [c431e70be5](https://linux-hardware.org/?probe=c431e70be5) | Nov 16, 2023 |
| Dell          | Vostro 16 5630              | Notebook    | [5716490407](https://linux-hardware.org/?probe=5716490407) | Nov 16, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [adaa2215c6](https://linux-hardware.org/?probe=adaa2215c6) | Nov 15, 2023 |
| Intel         | B75                         | Desktop     | [b05bcd24eb](https://linux-hardware.org/?probe=b05bcd24eb) | Nov 15, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | Desktop     | [9d8548f39a](https://linux-hardware.org/?probe=9d8548f39a) | Nov 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [4e7f0bb4bc](https://linux-hardware.org/?probe=4e7f0bb4bc) | Nov 14, 2023 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [551661ff00](https://linux-hardware.org/?probe=551661ff00) | Nov 14, 2023 |
| MSI           | GS66 Stealth 10SF           | Notebook    | [99b8a18021](https://linux-hardware.org/?probe=99b8a18021) | Nov 14, 2023 |
| HP            | Pavilion g6                 | Notebook    | [1598948ed4](https://linux-hardware.org/?probe=1598948ed4) | Nov 14, 2023 |
| Dell          | Latitude 5490               | Notebook    | [ed244b0d48](https://linux-hardware.org/?probe=ed244b0d48) | Nov 13, 2023 |
| HP            | 2000                        | Notebook    | [70a37e88d6](https://linux-hardware.org/?probe=70a37e88d6) | Nov 13, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | Desktop     | [36763f453f](https://linux-hardware.org/?probe=36763f453f) | Nov 13, 2023 |
| Lenovo        | ThinkPad T550 20CJS1MW00    | Notebook    | [ac6e58c0eb](https://linux-hardware.org/?probe=ac6e58c0eb) | Nov 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [6b6cc6823a](https://linux-hardware.org/?probe=6b6cc6823a) | Nov 13, 2023 |
| Fujitsu       | LIFEBOOK U759               | Notebook    | [5b992613d3](https://linux-hardware.org/?probe=5b992613d3) | Nov 13, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [c7be71a544](https://linux-hardware.org/?probe=c7be71a544) | Nov 13, 2023 |
| COM1          | NBINF-X5-9G5                | Notebook    | [4e24a48715](https://linux-hardware.org/?probe=4e24a48715) | Nov 13, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [6a15b4fb46](https://linux-hardware.org/?probe=6a15b4fb46) | Nov 13, 2023 |
| Shenzhen M... | F7BFC                       | Desktop     | [b375ae991a](https://linux-hardware.org/?probe=b375ae991a) | Nov 12, 2023 |
| Lenovo        | ThinkPad L540 20AUS11P00    | Notebook    | [593d2114d9](https://linux-hardware.org/?probe=593d2114d9) | Nov 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [d9dde0a949](https://linux-hardware.org/?probe=d9dde0a949) | Nov 12, 2023 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [269c0ca349](https://linux-hardware.org/?probe=269c0ca349) | Nov 12, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [64b6fe3b3a](https://linux-hardware.org/?probe=64b6fe3b3a) | Nov 11, 2023 |
| Dell          | 09KPNV A00                  | Desktop     | [231b7871d0](https://linux-hardware.org/?probe=231b7871d0) | Nov 11, 2023 |
| Dell          | Latitude E6230              | Notebook    | [b497378ab3](https://linux-hardware.org/?probe=b497378ab3) | Nov 11, 2023 |
| Lenovo        | Legion Y545 81Q6            | Notebook    | [f254d9deef](https://linux-hardware.org/?probe=f254d9deef) | Nov 11, 2023 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [8e450b21e1](https://linux-hardware.org/?probe=8e450b21e1) | Nov 10, 2023 |
| MSI           | Prestige 15 A10SC           | Notebook    | [e2f423f938](https://linux-hardware.org/?probe=e2f423f938) | Nov 10, 2023 |
| Gigabyte      | Z390 UD V2                  | Desktop     | [2106c14823](https://linux-hardware.org/?probe=2106c14823) | Nov 10, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [1f65a38863](https://linux-hardware.org/?probe=1f65a38863) | Nov 09, 2023 |
| HP            | ProBook 450 G7              | Notebook    | [32fe1a3fd3](https://linux-hardware.org/?probe=32fe1a3fd3) | Nov 09, 2023 |
| HUAWEI        | KPL-W0X                     | Notebook    | [2e06b9e7ff](https://linux-hardware.org/?probe=2e06b9e7ff) | Nov 09, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [f107797037](https://linux-hardware.org/?probe=f107797037) | Nov 09, 2023 |
| Gigabyte      | Z390 UD V2                  | Desktop     | [7cdb83cd7a](https://linux-hardware.org/?probe=7cdb83cd7a) | Nov 09, 2023 |
| HP            | 802F                        | Desktop     | [e5d90a5987](https://linux-hardware.org/?probe=e5d90a5987) | Nov 09, 2023 |
| ASRock        | Z77 Extreme4                | Desktop     | [ebe40897c3](https://linux-hardware.org/?probe=ebe40897c3) | Nov 08, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [27fda59de0](https://linux-hardware.org/?probe=27fda59de0) | Nov 08, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [6970492955](https://linux-hardware.org/?probe=6970492955) | Nov 08, 2023 |
| ASRock        | Z690 Extreme                | Desktop     | [6377c6ca79](https://linux-hardware.org/?probe=6377c6ca79) | Nov 08, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [6bc6e8bb07](https://linux-hardware.org/?probe=6bc6e8bb07) | Nov 08, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [c019f410aa](https://linux-hardware.org/?probe=c019f410aa) | Nov 08, 2023 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [ef9e91fdbf](https://linux-hardware.org/?probe=ef9e91fdbf) | Nov 08, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [7e3747e291](https://linux-hardware.org/?probe=7e3747e291) | Nov 07, 2023 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [84527b43d1](https://linux-hardware.org/?probe=84527b43d1) | Nov 07, 2023 |
| ASUSTek       | G750JS                      | Notebook    | [b64eb3798d](https://linux-hardware.org/?probe=b64eb3798d) | Nov 07, 2023 |
| MSI           | A78M-E45                    | Desktop     | [920763b803](https://linux-hardware.org/?probe=920763b803) | Nov 07, 2023 |
| Dell          | G3 3779                     | Notebook    | [74ef4d1941](https://linux-hardware.org/?probe=74ef4d1941) | Nov 06, 2023 |
| Lenovo        | 310B SDK0J40700 WIN 3258... | Mini pc     | [cf7e8006d1](https://linux-hardware.org/?probe=cf7e8006d1) | Nov 06, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [b63a038c08](https://linux-hardware.org/?probe=b63a038c08) | Nov 06, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [e56fc59b28](https://linux-hardware.org/?probe=e56fc59b28) | Nov 06, 2023 |
| Lenovo        | 3743 SDK0T76463 WIN 3422... | Desktop     | [ce42858c1f](https://linux-hardware.org/?probe=ce42858c1f) | Nov 06, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [99a6c38b5d](https://linux-hardware.org/?probe=99a6c38b5d) | Nov 05, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [8ee603dbfc](https://linux-hardware.org/?probe=8ee603dbfc) | Nov 05, 2023 |
| Dell          | 048DY8 A01                  | Desktop     | [2ef39546ef](https://linux-hardware.org/?probe=2ef39546ef) | Nov 05, 2023 |
| Unknown       | Unknown                     | Notebook    | [f90d872043](https://linux-hardware.org/?probe=f90d872043) | Nov 05, 2023 |
| Lenovo        | ThinkPad X250 20CM001UUK    | Notebook    | [b0fd9fa3c0](https://linux-hardware.org/?probe=b0fd9fa3c0) | Nov 05, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [c520e5a3b2](https://linux-hardware.org/?probe=c520e5a3b2) | Nov 05, 2023 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [907a7f6dd8](https://linux-hardware.org/?probe=907a7f6dd8) | Nov 05, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [20ffbbc165](https://linux-hardware.org/?probe=20ffbbc165) | Nov 04, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [6fcd2a768b](https://linux-hardware.org/?probe=6fcd2a768b) | Nov 04, 2023 |
| Lenovo        | Legion Y545 81Q6            | Notebook    | [c2fa613f00](https://linux-hardware.org/?probe=c2fa613f00) | Nov 04, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [afbfce6e52](https://linux-hardware.org/?probe=afbfce6e52) | Nov 04, 2023 |
| MSI           | GF75 Thin 9SC               | Notebook    | [2aceaf7016](https://linux-hardware.org/?probe=2aceaf7016) | Nov 03, 2023 |
| Acer          | Aspire 5750                 | Notebook    | [429b14ee32](https://linux-hardware.org/?probe=429b14ee32) | Nov 03, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [8ee912a147](https://linux-hardware.org/?probe=8ee912a147) | Nov 02, 2023 |
| HP            | EliteBook 860 16 inch G9... | Notebook    | [5c564324e2](https://linux-hardware.org/?probe=5c564324e2) | Nov 02, 2023 |
| Acer          | Swift SF314-55G             | Notebook    | [fee0e3c809](https://linux-hardware.org/?probe=fee0e3c809) | Nov 02, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [59d963de5b](https://linux-hardware.org/?probe=59d963de5b) | Nov 02, 2023 |
| Dell          | Latitude 5480               | Notebook    | [a88b4082b9](https://linux-hardware.org/?probe=a88b4082b9) | Nov 02, 2023 |
| Dell          | XPS L521X                   | Notebook    | [d3df01b854](https://linux-hardware.org/?probe=d3df01b854) | Nov 02, 2023 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [a60f1d4a52](https://linux-hardware.org/?probe=a60f1d4a52) | Nov 01, 2023 |
| Razer         | Blade                       | Notebook    | [e9ad529ed4](https://linux-hardware.org/?probe=e9ad529ed4) | Nov 01, 2023 |
| ASUSTek       | X541UAK                     | Notebook    | [d4630a5c8b](https://linux-hardware.org/?probe=d4630a5c8b) | Nov 01, 2023 |
| Dell          | Latitude E6420              | Notebook    | [e5581c3920](https://linux-hardware.org/?probe=e5581c3920) | Nov 01, 2023 |
| ASRock        | B250M Pro4                  | Desktop     | [399fe59760](https://linux-hardware.org/?probe=399fe59760) | Nov 01, 2023 |
| Fujitsu       | D4017-A1 S26361-D4017-A1... | Desktop     | [939aebfa68](https://linux-hardware.org/?probe=939aebfa68) | Nov 01, 2023 |
| HP            | 2B01                        | Desktop     | [a345333330](https://linux-hardware.org/?probe=a345333330) | Oct 31, 2023 |
| Gigabyte      | B450M DS3H WIFI V2-CF       | Desktop     | [ac2f19109e](https://linux-hardware.org/?probe=ac2f19109e) | Oct 31, 2023 |
| HP            | 2B01                        | Desktop     | [b3a75824f5](https://linux-hardware.org/?probe=b3a75824f5) | Oct 31, 2023 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [d735ec288c](https://linux-hardware.org/?probe=d735ec288c) | Oct 31, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [517f8861a6](https://linux-hardware.org/?probe=517f8861a6) | Oct 31, 2023 |
| Toshiba       | Satellite C55-C             | Notebook    | [859d23eed0](https://linux-hardware.org/?probe=859d23eed0) | Oct 31, 2023 |
| ASUSTek       | ROG STRIX B560-G GAMING ... | Desktop     | [4e5ba58b35](https://linux-hardware.org/?probe=4e5ba58b35) | Oct 30, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [23fdd2c31d](https://linux-hardware.org/?probe=23fdd2c31d) | Oct 30, 2023 |
| Dell          | XPS L521X                   | Notebook    | [959fc8cb2d](https://linux-hardware.org/?probe=959fc8cb2d) | Oct 29, 2023 |
| ASUSTek       | Vivobook ASUSLaptop TP34... | Convertible | [74a1a56aff](https://linux-hardware.org/?probe=74a1a56aff) | Oct 29, 2023 |
| Lenovo        | ThinkPad P53 20QN0050RT     | Notebook    | [179f2c7971](https://linux-hardware.org/?probe=179f2c7971) | Oct 29, 2023 |
| ASUSTek       | G750JM                      | Notebook    | [01e0620386](https://linux-hardware.org/?probe=01e0620386) | Oct 29, 2023 |
| Dell          | 0T1D10 A01                  | Desktop     | [1b0a34d774](https://linux-hardware.org/?probe=1b0a34d774) | Oct 29, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [8ec254a9a6](https://linux-hardware.org/?probe=8ec254a9a6) | Oct 29, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [b6f56d4f6c](https://linux-hardware.org/?probe=b6f56d4f6c) | Oct 29, 2023 |
| HP            | Laptop 17-by2xxx            | Notebook    | [573a17cea0](https://linux-hardware.org/?probe=573a17cea0) | Oct 28, 2023 |
| Intel         | B75                         | Desktop     | [7b6b287377](https://linux-hardware.org/?probe=7b6b287377) | Oct 28, 2023 |
| Dell          | XPS L412Z                   | Notebook    | [3c2afbb9c4](https://linux-hardware.org/?probe=3c2afbb9c4) | Oct 28, 2023 |
| Lenovo        | ThinkPad T480 20L5000AIX    | Notebook    | [65b2874cbb](https://linux-hardware.org/?probe=65b2874cbb) | Oct 28, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [69a0449eee](https://linux-hardware.org/?probe=69a0449eee) | Oct 28, 2023 |
| Win elemen... | M600                        | Desktop     | [6a027c490c](https://linux-hardware.org/?probe=6a027c490c) | Oct 28, 2023 |
| ASRock        | X670E Taichi Carrara        | Desktop     | [2ff3541961](https://linux-hardware.org/?probe=2ff3541961) | Oct 28, 2023 |
| Lenovo        | ThinkPad E490 20N80006UE    | Notebook    | [4bb8e497d3](https://linux-hardware.org/?probe=4bb8e497d3) | Oct 28, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c25324c2a2](https://linux-hardware.org/?probe=c25324c2a2) | Oct 28, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [220dddac59](https://linux-hardware.org/?probe=220dddac59) | Oct 28, 2023 |
| Lenovo        | ThinkPad L540 20AUS11P00    | Notebook    | [d59d45eb50](https://linux-hardware.org/?probe=d59d45eb50) | Oct 27, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [bc710e10c6](https://linux-hardware.org/?probe=bc710e10c6) | Oct 27, 2023 |
| HP            | 2B0A                        | All in one  | [e60260d9b2](https://linux-hardware.org/?probe=e60260d9b2) | Oct 26, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [b65f692868](https://linux-hardware.org/?probe=b65f692868) | Oct 26, 2023 |
| HP            | Pavilion g7                 | Notebook    | [aca57140b6](https://linux-hardware.org/?probe=aca57140b6) | Oct 26, 2023 |
| HP            | Presario CQ56               | Notebook    | [10dbf7856b](https://linux-hardware.org/?probe=10dbf7856b) | Oct 26, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [6c18f4a4ef](https://linux-hardware.org/?probe=6c18f4a4ef) | Oct 25, 2023 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [f4f26b1c2a](https://linux-hardware.org/?probe=f4f26b1c2a) | Oct 25, 2023 |
| ASUSTek       | X555UB                      | Notebook    | [f501faa5ac](https://linux-hardware.org/?probe=f501faa5ac) | Oct 25, 2023 |
| MSI           | Prestige 15 A10SC           | Notebook    | [796a2f6a53](https://linux-hardware.org/?probe=796a2f6a53) | Oct 25, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [a70d4b8a0d](https://linux-hardware.org/?probe=a70d4b8a0d) | Oct 25, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [4e7be30b13](https://linux-hardware.org/?probe=4e7be30b13) | Oct 25, 2023 |
| ASUSTek       | ZenBook Pro Duo UX582ZM_... | Notebook    | [1ce9a81d10](https://linux-hardware.org/?probe=1ce9a81d10) | Oct 25, 2023 |
| Samsung       | 270E5J/2570EJ               | Notebook    | [94f358053d](https://linux-hardware.org/?probe=94f358053d) | Oct 24, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [5d05be46df](https://linux-hardware.org/?probe=5d05be46df) | Oct 24, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [a71b3ca73a](https://linux-hardware.org/?probe=a71b3ca73a) | Oct 24, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | Notebook    | [8764daeeab](https://linux-hardware.org/?probe=8764daeeab) | Oct 24, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [f99b06d89a](https://linux-hardware.org/?probe=f99b06d89a) | Oct 24, 2023 |
| Acer          | Veriton N4640G              | Desktop     | [ccba40d7a9](https://linux-hardware.org/?probe=ccba40d7a9) | Oct 24, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [3daca4912e](https://linux-hardware.org/?probe=3daca4912e) | Oct 24, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [b838b1d016](https://linux-hardware.org/?probe=b838b1d016) | Oct 23, 2023 |
| Gigabyte      | B550 AORUS MASTER           | Desktop     | [a9dd51be33](https://linux-hardware.org/?probe=a9dd51be33) | Oct 23, 2023 |
| Intel         | HM570                       | Desktop     | [5dba972342](https://linux-hardware.org/?probe=5dba972342) | Oct 23, 2023 |
| AMI           | Intel                       | Desktop     | [5e579268b6](https://linux-hardware.org/?probe=5e579268b6) | Oct 23, 2023 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [f134292e10](https://linux-hardware.org/?probe=f134292e10) | Oct 23, 2023 |
| HP            | Folio 13                    | Notebook    | [b7ed500d93](https://linux-hardware.org/?probe=b7ed500d93) | Oct 22, 2023 |
| Intel         | B75                         | Desktop     | [96f9a95f89](https://linux-hardware.org/?probe=96f9a95f89) | Oct 22, 2023 |
| ASUSTek       | X550JX                      | Notebook    | [b1a9053ac6](https://linux-hardware.org/?probe=b1a9053ac6) | Oct 22, 2023 |
| Gigabyte      | B85N PHOENIX-CF             | Desktop     | [a64a820d24](https://linux-hardware.org/?probe=a64a820d24) | Oct 22, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [38d48bd5b5](https://linux-hardware.org/?probe=38d48bd5b5) | Oct 22, 2023 |
| Acer          | Veriton S2680G              | Desktop     | [da6ff1f2f3](https://linux-hardware.org/?probe=da6ff1f2f3) | Oct 22, 2023 |
| ASUSTek       | N552VW                      | Notebook    | [dd755eb3a0](https://linux-hardware.org/?probe=dd755eb3a0) | Oct 22, 2023 |
| ASUSTek       | N552VW                      | Notebook    | [c511cce283](https://linux-hardware.org/?probe=c511cce283) | Oct 22, 2023 |
| ASRock        | B650M PG Riptide            | Desktop     | [218908299a](https://linux-hardware.org/?probe=218908299a) | Oct 21, 2023 |
| ASUSTek       | PRIME H270-PRO              | Desktop     | [3b1d62c873](https://linux-hardware.org/?probe=3b1d62c873) | Oct 21, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | Notebook    | [943199c6c3](https://linux-hardware.org/?probe=943199c6c3) | Oct 21, 2023 |
| Dell          | Precision 7530              | Notebook    | [9cdabb5579](https://linux-hardware.org/?probe=9cdabb5579) | Oct 21, 2023 |
| ASUSTek       | P8Z68-V GEN3                | Desktop     | [3216d9052a](https://linux-hardware.org/?probe=3216d9052a) | Oct 21, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [0b9affbbb3](https://linux-hardware.org/?probe=0b9affbbb3) | Oct 21, 2023 |
| HP            | Folio 13                    | Notebook    | [99ff48ac3f](https://linux-hardware.org/?probe=99ff48ac3f) | Oct 20, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [150e0ba56b](https://linux-hardware.org/?probe=150e0ba56b) | Oct 20, 2023 |
| HP            | 3397                        | Desktop     | [d826d02943](https://linux-hardware.org/?probe=d826d02943) | Oct 20, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [fe4a9ec4d0](https://linux-hardware.org/?probe=fe4a9ec4d0) | Oct 20, 2023 |
| Dell          | Latitude E6430s             | Notebook    | [ce1c3a6c86](https://linux-hardware.org/?probe=ce1c3a6c86) | Oct 20, 2023 |
| ASUSTek       | T101HA                      | Tablet      | [2315267395](https://linux-hardware.org/?probe=2315267395) | Oct 20, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [43a57d26c9](https://linux-hardware.org/?probe=43a57d26c9) | Oct 20, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [6a3e8e996e](https://linux-hardware.org/?probe=6a3e8e996e) | Oct 20, 2023 |
| Lenovo        | XiaoXin Air 15IKBR 81GY     | Notebook    | [755849af68](https://linux-hardware.org/?probe=755849af68) | Oct 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [7e7c4e7110](https://linux-hardware.org/?probe=7e7c4e7110) | Oct 19, 2023 |
| Acer          | Predator PO3-620            | Desktop     | [db0c739e61](https://linux-hardware.org/?probe=db0c739e61) | Oct 19, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [231faaeea5](https://linux-hardware.org/?probe=231faaeea5) | Oct 19, 2023 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [d906262d01](https://linux-hardware.org/?probe=d906262d01) | Oct 18, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [5bf3d1073e](https://linux-hardware.org/?probe=5bf3d1073e) | Oct 18, 2023 |
| ASUSTek       | ROG STRIX X370-F GAMING     | Desktop     | [3e5a5380d7](https://linux-hardware.org/?probe=3e5a5380d7) | Oct 18, 2023 |
| ASUSTek       | G750JM                      | Notebook    | [0f5885bc27](https://linux-hardware.org/?probe=0f5885bc27) | Oct 17, 2023 |
| ASUSTek       | T101HA                      | Tablet      | [4e07ff33bd](https://linux-hardware.org/?probe=4e07ff33bd) | Oct 17, 2023 |
| ASUSTek       | X556UQK                     | Notebook    | [c430358d6a](https://linux-hardware.org/?probe=c430358d6a) | Oct 17, 2023 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [8dcfce6520](https://linux-hardware.org/?probe=8dcfce6520) | Oct 17, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [25ba718720](https://linux-hardware.org/?probe=25ba718720) | Oct 16, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [83cb446c19](https://linux-hardware.org/?probe=83cb446c19) | Oct 16, 2023 |
| BANGHO        | MAX G0101                   | Notebook    | [b0adb13b97](https://linux-hardware.org/?probe=b0adb13b97) | Oct 16, 2023 |
| Razer         | Book 13 - RZ09-0357         | Notebook    | [0a1c9e7aae](https://linux-hardware.org/?probe=0a1c9e7aae) | Oct 15, 2023 |
| Dell          | 00F82W A00                  | Desktop     | [410900bf0d](https://linux-hardware.org/?probe=410900bf0d) | Oct 15, 2023 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [9065a343c2](https://linux-hardware.org/?probe=9065a343c2) | Oct 15, 2023 |
| Lenovo        | ThinkPad X230 232578G       | Notebook    | [80bd4e2684](https://linux-hardware.org/?probe=80bd4e2684) | Oct 15, 2023 |
| Lenovo        | ThinkPad T480 20L5000AIX    | Notebook    | [c7b57a58b7](https://linux-hardware.org/?probe=c7b57a58b7) | Oct 15, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [cdd65525cc](https://linux-hardware.org/?probe=cdd65525cc) | Oct 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [23768d9009](https://linux-hardware.org/?probe=23768d9009) | Oct 15, 2023 |
| Dell          | G3 3579                     | Notebook    | [20cb75e8b8](https://linux-hardware.org/?probe=20cb75e8b8) | Oct 15, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [c12987d53a](https://linux-hardware.org/?probe=c12987d53a) | Oct 15, 2023 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [79a68614cb](https://linux-hardware.org/?probe=79a68614cb) | Oct 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [73f73df16b](https://linux-hardware.org/?probe=73f73df16b) | Oct 14, 2023 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [42e5a09fe2](https://linux-hardware.org/?probe=42e5a09fe2) | Oct 14, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [e3a01650f1](https://linux-hardware.org/?probe=e3a01650f1) | Oct 14, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [c46d5e3dfd](https://linux-hardware.org/?probe=c46d5e3dfd) | Oct 13, 2023 |
| HP            | 18E7                        | Desktop     | [855ab006c1](https://linux-hardware.org/?probe=855ab006c1) | Oct 13, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [8d41cb80bf](https://linux-hardware.org/?probe=8d41cb80bf) | Oct 13, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [339d1c4a25](https://linux-hardware.org/?probe=339d1c4a25) | Oct 13, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [4d434ee41b](https://linux-hardware.org/?probe=4d434ee41b) | Oct 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [f767f8dd4d](https://linux-hardware.org/?probe=f767f8dd4d) | Oct 12, 2023 |
| Lenovo        | IdeaPad 320-14IKB 80XK      | Notebook    | [ae56dcb316](https://linux-hardware.org/?probe=ae56dcb316) | Oct 12, 2023 |
| Apple         | MacBookPro10,2              | Notebook    | [3c84d02367](https://linux-hardware.org/?probe=3c84d02367) | Oct 12, 2023 |
| Dell          | 03NVJ6 A02                  | Desktop     | [0f40b40836](https://linux-hardware.org/?probe=0f40b40836) | Oct 11, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [c6eeac6337](https://linux-hardware.org/?probe=c6eeac6337) | Oct 11, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [89ae9695ef](https://linux-hardware.org/?probe=89ae9695ef) | Oct 11, 2023 |
| HP            | Notebook                    | Notebook    | [bb5bc1259a](https://linux-hardware.org/?probe=bb5bc1259a) | Oct 11, 2023 |
| BESSTAR Te... | X400                        | Notebook    | [c955c44ef3](https://linux-hardware.org/?probe=c955c44ef3) | Oct 10, 2023 |
| Dell          | 00F82W A00                  | Desktop     | [75fd02b856](https://linux-hardware.org/?probe=75fd02b856) | Oct 10, 2023 |
| Dell          | 03NVJ6 A02                  | Desktop     | [8f7a44301e](https://linux-hardware.org/?probe=8f7a44301e) | Oct 10, 2023 |
| Lenovo        | ThinkPad L540 20AUS11P00    | Notebook    | [ec64651cec](https://linux-hardware.org/?probe=ec64651cec) | Oct 10, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [be8f18157d](https://linux-hardware.org/?probe=be8f18157d) | Oct 10, 2023 |
| HP            | Presario CQ56               | Notebook    | [d554bda407](https://linux-hardware.org/?probe=d554bda407) | Oct 09, 2023 |
| ASUSTek       | K52JB                       | Notebook    | [a2a5c14c8a](https://linux-hardware.org/?probe=a2a5c14c8a) | Oct 09, 2023 |
| ASUSTek       | K52JB                       | Notebook    | [b3fd22ad8e](https://linux-hardware.org/?probe=b3fd22ad8e) | Oct 08, 2023 |
| Lenovo        | ThinkPad T490 20N3SDGJ02    | Notebook    | [43f05c011e](https://linux-hardware.org/?probe=43f05c011e) | Oct 08, 2023 |
| Extra Terr... | Unknown                     | Notebook    | [505b2e0823](https://linux-hardware.org/?probe=505b2e0823) | Oct 08, 2023 |
| Gigabyte      | H87N-WIFI                   | Desktop     | [f010d626da](https://linux-hardware.org/?probe=f010d626da) | Oct 08, 2023 |
| HP            | Folio 13                    | Notebook    | [f4ed29d660](https://linux-hardware.org/?probe=f4ed29d660) | Oct 08, 2023 |
| Unknown       | Unknown                     | Notebook    | [3f4a876b18](https://linux-hardware.org/?probe=3f4a876b18) | Oct 08, 2023 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [d036c55336](https://linux-hardware.org/?probe=d036c55336) | Oct 07, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [c9d4efa819](https://linux-hardware.org/?probe=c9d4efa819) | Oct 07, 2023 |
| Samsung       | 950QED                      | Convertible | [739568d199](https://linux-hardware.org/?probe=739568d199) | Oct 07, 2023 |
| ASUSTek       | ROG Strix G513QY            | Notebook    | [084087e7bb](https://linux-hardware.org/?probe=084087e7bb) | Oct 07, 2023 |
| Intel         | NUC7i5BNB J31144-310        | Mini pc     | [67df4157ef](https://linux-hardware.org/?probe=67df4157ef) | Oct 06, 2023 |
| Dell          | 0WWJRX A00                  | Desktop     | [331ecd3ee8](https://linux-hardware.org/?probe=331ecd3ee8) | Oct 06, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [a716f2a182](https://linux-hardware.org/?probe=a716f2a182) | Oct 06, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [97dca67f82](https://linux-hardware.org/?probe=97dca67f82) | Oct 06, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [8619f7e43e](https://linux-hardware.org/?probe=8619f7e43e) | Oct 06, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [0a18c0ff5d](https://linux-hardware.org/?probe=0a18c0ff5d) | Oct 06, 2023 |
| Lenovo        | ThinkPad 3354DSG            | Notebook    | [4eb8d1761d](https://linux-hardware.org/?probe=4eb8d1761d) | Oct 06, 2023 |
| Lenovo        | 3135 SDK0J40697 WIN 3305... | Mini pc     | [096ea265ea](https://linux-hardware.org/?probe=096ea265ea) | Oct 05, 2023 |
| Lenovo        | ThinkPad T430 2349IF8       | Notebook    | [0b0a1ecd08](https://linux-hardware.org/?probe=0b0a1ecd08) | Oct 05, 2023 |
| Lenovo        | 3135 SDK0J40697 WIN 3305... | Mini pc     | [e9195a4ac8](https://linux-hardware.org/?probe=e9195a4ac8) | Oct 05, 2023 |
| Lenovo        | ThinkPad T480 20L50010US    | Notebook    | [e7940adc14](https://linux-hardware.org/?probe=e7940adc14) | Oct 05, 2023 |
| Lenovo        | ThinkPad X220 4291C84       | Notebook    | [92cc269d09](https://linux-hardware.org/?probe=92cc269d09) | Oct 05, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [dbb516ab07](https://linux-hardware.org/?probe=dbb516ab07) | Oct 05, 2023 |
| HP            | 2B0D A01                    | All in one  | [28b1dc9b84](https://linux-hardware.org/?probe=28b1dc9b84) | Oct 05, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [381be666c0](https://linux-hardware.org/?probe=381be666c0) | Oct 04, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO II     | Desktop     | [1deaeb248b](https://linux-hardware.org/?probe=1deaeb248b) | Oct 04, 2023 |
| Lenovo        | ThinkPad L380 Yoga 20M70... | Convertible | [0c33815641](https://linux-hardware.org/?probe=0c33815641) | Oct 04, 2023 |
| ASUSTek       | N551JW                      | Notebook    | [680e68d0c8](https://linux-hardware.org/?probe=680e68d0c8) | Oct 04, 2023 |
| Samsung       | 550P5C/550P7C               | Notebook    | [edbf3959ab](https://linux-hardware.org/?probe=edbf3959ab) | Oct 04, 2023 |
| Acer          | Nitro N50-600 V:1.1         | Desktop     | [8959fc9294](https://linux-hardware.org/?probe=8959fc9294) | Oct 03, 2023 |
| Unknown       | Unknown                     | Notebook    | [b3a1f027db](https://linux-hardware.org/?probe=b3a1f027db) | Oct 03, 2023 |
| MSI           | Z590-A PRO                  | Desktop     | [373685317f](https://linux-hardware.org/?probe=373685317f) | Oct 03, 2023 |
| Lenovo        | ThinkPad T490 20N3SDGJ02    | Notebook    | [57b94fa258](https://linux-hardware.org/?probe=57b94fa258) | Oct 02, 2023 |
| HP            | 87D6 SMVB                   | Desktop     | [ac72ba77a1](https://linux-hardware.org/?probe=ac72ba77a1) | Oct 02, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [7d748e38fb](https://linux-hardware.org/?probe=7d748e38fb) | Oct 02, 2023 |
| Samsung       | 750XED                      | Notebook    | [33e2bf8845](https://linux-hardware.org/?probe=33e2bf8845) | Oct 02, 2023 |
| EXPER         | H61H2-MV                    | Desktop     | [5cd287a613](https://linux-hardware.org/?probe=5cd287a613) | Oct 01, 2023 |
| EXPER         | H61H2-MV                    | Desktop     | [7b50b9b997](https://linux-hardware.org/?probe=7b50b9b997) | Oct 01, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [25211e6ce1](https://linux-hardware.org/?probe=25211e6ce1) | Oct 01, 2023 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [27e61d282f](https://linux-hardware.org/?probe=27e61d282f) | Oct 01, 2023 |
| Acer          | Aspire SW5-173              | Notebook    | [b990067acf](https://linux-hardware.org/?probe=b990067acf) | Oct 01, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [5d6364a866](https://linux-hardware.org/?probe=5d6364a866) | Oct 01, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [085fbda5a6](https://linux-hardware.org/?probe=085fbda5a6) | Sep 30, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [4575deef12](https://linux-hardware.org/?probe=4575deef12) | Sep 30, 2023 |
| Lenovo        | ThinkPad T440 20B7S1K400    | Notebook    | [fd03530876](https://linux-hardware.org/?probe=fd03530876) | Sep 30, 2023 |
| ASRock        | A320M-DGS                   | Desktop     | [63aafe31f1](https://linux-hardware.org/?probe=63aafe31f1) | Sep 30, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [80ac43658d](https://linux-hardware.org/?probe=80ac43658d) | Sep 30, 2023 |
| Dell          | 0YXT71 A02                  | Desktop     | [6bc3385414](https://linux-hardware.org/?probe=6bc3385414) | Sep 30, 2023 |
| Gigabyte      | Z87X-UD3H-CF                | Desktop     | [7f47d1f656](https://linux-hardware.org/?probe=7f47d1f656) | Sep 30, 2023 |
| Medion        | MS-7667                     | Desktop     | [a91527e825](https://linux-hardware.org/?probe=a91527e825) | Sep 30, 2023 |
| Gigabyte      | X399 DESIGNARE EX-CF        | Desktop     | [4835df59b1](https://linux-hardware.org/?probe=4835df59b1) | Sep 30, 2023 |
| Dell          | Latitude 3301               | Notebook    | [3859ed5445](https://linux-hardware.org/?probe=3859ed5445) | Sep 29, 2023 |
| ASRock        | Z490 Phantom Gaming 4       | Desktop     | [6fc3fe7a63](https://linux-hardware.org/?probe=6fc3fe7a63) | Sep 29, 2023 |
| Lenovo        | ThinkPad X260 20F5S2WY00    | Notebook    | [6a18fb9b21](https://linux-hardware.org/?probe=6a18fb9b21) | Sep 29, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [e6d8dfa4a1](https://linux-hardware.org/?probe=e6d8dfa4a1) | Sep 29, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [cb2cbda84d](https://linux-hardware.org/?probe=cb2cbda84d) | Sep 28, 2023 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [51272b2713](https://linux-hardware.org/?probe=51272b2713) | Sep 28, 2023 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [1509f60079](https://linux-hardware.org/?probe=1509f60079) | Sep 28, 2023 |
| Apple         | MacBookPro9,1               | Notebook    | [555dfa4f2e](https://linux-hardware.org/?probe=555dfa4f2e) | Sep 28, 2023 |
| HP            | EliteBook 850 G1            | Notebook    | [35f0e18f04](https://linux-hardware.org/?probe=35f0e18f04) | Sep 28, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [eeb582da25](https://linux-hardware.org/?probe=eeb582da25) | Sep 28, 2023 |
| ASUSTek       | K45VM                       | Notebook    | [6c167e69a4](https://linux-hardware.org/?probe=6c167e69a4) | Sep 28, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [797275028d](https://linux-hardware.org/?probe=797275028d) | Sep 28, 2023 |
| HP            | ElitePad 1000 G2            | Notebook    | [a53de5d0bd](https://linux-hardware.org/?probe=a53de5d0bd) | Sep 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [8c585051a3](https://linux-hardware.org/?probe=8c585051a3) | Sep 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [fb82c6e942](https://linux-hardware.org/?probe=fb82c6e942) | Sep 27, 2023 |
| HP            | EliteBook x360 1020 G2      | Convertible | [7b6ee612cf](https://linux-hardware.org/?probe=7b6ee612cf) | Sep 27, 2023 |
| ASUSTek       | N551JW                      | Notebook    | [8c38084e7e](https://linux-hardware.org/?probe=8c38084e7e) | Sep 27, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [d14e65fadf](https://linux-hardware.org/?probe=d14e65fadf) | Sep 26, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [1c764be0e3](https://linux-hardware.org/?probe=1c764be0e3) | Sep 26, 2023 |
| ASUSTek       | X555UB                      | Notebook    | [8496a9f79f](https://linux-hardware.org/?probe=8496a9f79f) | Sep 26, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [1476ba44bb](https://linux-hardware.org/?probe=1476ba44bb) | Sep 26, 2023 |
| HP            | Folio 13                    | Notebook    | [a5a1ae29a7](https://linux-hardware.org/?probe=a5a1ae29a7) | Sep 26, 2023 |
| ASUSTek       | K52JB                       | Notebook    | [7524eea19f](https://linux-hardware.org/?probe=7524eea19f) | Sep 26, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [3420c7e013](https://linux-hardware.org/?probe=3420c7e013) | Sep 25, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [48fb2a7ee3](https://linux-hardware.org/?probe=48fb2a7ee3) | Sep 25, 2023 |
| HP            | ElitePad 1000 G2            | Notebook    | [5e1dcb7163](https://linux-hardware.org/?probe=5e1dcb7163) | Sep 24, 2023 |
| Razer         | Blade                       | Notebook    | [b3b2eb7db8](https://linux-hardware.org/?probe=b3b2eb7db8) | Sep 24, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [e6bd73a6e1](https://linux-hardware.org/?probe=e6bd73a6e1) | Sep 24, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [575df2588e](https://linux-hardware.org/?probe=575df2588e) | Sep 23, 2023 |
| Lenovo        | IdeaPadFlex 5-1570 81CA     | Convertible | [6514ebc367](https://linux-hardware.org/?probe=6514ebc367) | Sep 23, 2023 |
| Unknown       | Unknown                     | Notebook    | [539887ee9a](https://linux-hardware.org/?probe=539887ee9a) | Sep 23, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [d6943b89de](https://linux-hardware.org/?probe=d6943b89de) | Sep 23, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [1af364233f](https://linux-hardware.org/?probe=1af364233f) | Sep 23, 2023 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | Desktop     | [1f76bcf230](https://linux-hardware.org/?probe=1f76bcf230) | Sep 23, 2023 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | Desktop     | [0fb4baf82b](https://linux-hardware.org/?probe=0fb4baf82b) | Sep 23, 2023 |
| HP            | ProBook 450 G1              | Notebook    | [feffc725af](https://linux-hardware.org/?probe=feffc725af) | Sep 23, 2023 |
| MSI           | CR610M                      | Notebook    | [5a9d9ba5ae](https://linux-hardware.org/?probe=5a9d9ba5ae) | Sep 22, 2023 |
| HP            | Folio 13                    | Notebook    | [66f8752b64](https://linux-hardware.org/?probe=66f8752b64) | Sep 22, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [a437fe8bcf](https://linux-hardware.org/?probe=a437fe8bcf) | Sep 21, 2023 |
| Lenovo        | ThinkPad T420 4178AFU       | Notebook    | [adee486a15](https://linux-hardware.org/?probe=adee486a15) | Sep 21, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | Notebook    | [65044021bd](https://linux-hardware.org/?probe=65044021bd) | Sep 21, 2023 |
| Monster       | ABRA A7 V11.3               | Notebook    | [7d1ed0e1c5](https://linux-hardware.org/?probe=7d1ed0e1c5) | Sep 21, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [a085f48523](https://linux-hardware.org/?probe=a085f48523) | Sep 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [4d1743c405](https://linux-hardware.org/?probe=4d1743c405) | Sep 20, 2023 |
| MSI           | Z270 GAMING M5              | Desktop     | [005d3394c9](https://linux-hardware.org/?probe=005d3394c9) | Sep 20, 2023 |
| ASUSTek       | Q170M2                      | Desktop     | [962ed87784](https://linux-hardware.org/?probe=962ed87784) | Sep 20, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [96a7016b7e](https://linux-hardware.org/?probe=96a7016b7e) | Sep 19, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [20eef756df](https://linux-hardware.org/?probe=20eef756df) | Sep 19, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [1f26ced12d](https://linux-hardware.org/?probe=1f26ced12d) | Sep 19, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [bf29b07e79](https://linux-hardware.org/?probe=bf29b07e79) | Sep 19, 2023 |
| Lenovo        | ThinkPad T420 4178AFU       | Notebook    | [65da9aa0c6](https://linux-hardware.org/?probe=65da9aa0c6) | Sep 19, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [28d0c94948](https://linux-hardware.org/?probe=28d0c94948) | Sep 19, 2023 |
| Lenovo        | E41-25 81FS                 | Notebook    | [6233a0f825](https://linux-hardware.org/?probe=6233a0f825) | Sep 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [987e4c193b](https://linux-hardware.org/?probe=987e4c193b) | Sep 19, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [9d59b2b43d](https://linux-hardware.org/?probe=9d59b2b43d) | Sep 19, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [0f0607d7e4](https://linux-hardware.org/?probe=0f0607d7e4) | Sep 18, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [87f5275af6](https://linux-hardware.org/?probe=87f5275af6) | Sep 18, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [5701fbde3e](https://linux-hardware.org/?probe=5701fbde3e) | Sep 18, 2023 |
| Gigabyte      | H310M S2                    | Desktop     | [f6a841ea3d](https://linux-hardware.org/?probe=f6a841ea3d) | Sep 18, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [514a5308f2](https://linux-hardware.org/?probe=514a5308f2) | Sep 18, 2023 |
| Gigabyte      | Z270-Gaming 3               | Desktop     | [9e795a05f1](https://linux-hardware.org/?probe=9e795a05f1) | Sep 18, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [9f3bdc24af](https://linux-hardware.org/?probe=9f3bdc24af) | Sep 18, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [178981670d](https://linux-hardware.org/?probe=178981670d) | Sep 17, 2023 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [1875fb96e5](https://linux-hardware.org/?probe=1875fb96e5) | Sep 17, 2023 |
| Dell          | Latitude 5421               | Notebook    | [a42c87b953](https://linux-hardware.org/?probe=a42c87b953) | Sep 17, 2023 |
| Acer          | Nitro AN515-51              | Notebook    | [09a7651061](https://linux-hardware.org/?probe=09a7651061) | Sep 17, 2023 |
| Unknown       | Unknown                     | Notebook    | [5e399c56a0](https://linux-hardware.org/?probe=5e399c56a0) | Sep 16, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [add3c0be93](https://linux-hardware.org/?probe=add3c0be93) | Sep 15, 2023 |
| Dell          | 0VTJVC A00                  | Desktop     | [8a404c05c2](https://linux-hardware.org/?probe=8a404c05c2) | Sep 15, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [1a4ae657dd](https://linux-hardware.org/?probe=1a4ae657dd) | Sep 15, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [f15272f431](https://linux-hardware.org/?probe=f15272f431) | Sep 15, 2023 |
| Positivo      | POS-RIB360EE 11144907       | Desktop     | [8c1887fa93](https://linux-hardware.org/?probe=8c1887fa93) | Sep 15, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [c1f02dd477](https://linux-hardware.org/?probe=c1f02dd477) | Sep 15, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [2d0ccc33ef](https://linux-hardware.org/?probe=2d0ccc33ef) | Sep 15, 2023 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | Desktop     | [c3e468a36f](https://linux-hardware.org/?probe=c3e468a36f) | Sep 15, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [5e93e7c587](https://linux-hardware.org/?probe=5e93e7c587) | Sep 14, 2023 |
| Dell          | Inspiron 3593               | Notebook    | [04d9ccd10f](https://linux-hardware.org/?probe=04d9ccd10f) | Sep 14, 2023 |
| HP            | EliteBook x360 1040 G7 N... | Convertible | [7baf2aedfc](https://linux-hardware.org/?probe=7baf2aedfc) | Sep 14, 2023 |
| A-DATA Tec... | XENIAXe15TI5G11GXELX        | Notebook    | [6c2fdbd791](https://linux-hardware.org/?probe=6c2fdbd791) | Sep 14, 2023 |
| HP            | Folio 13                    | Notebook    | [9ed048b9e4](https://linux-hardware.org/?probe=9ed048b9e4) | Sep 14, 2023 |
| Lenovo        | ThinkPad T480 20L6S1FU00    | Notebook    | [d0e8034434](https://linux-hardware.org/?probe=d0e8034434) | Sep 14, 2023 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [8b7e93cd9d](https://linux-hardware.org/?probe=8b7e93cd9d) | Sep 14, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [9b982600ce](https://linux-hardware.org/?probe=9b982600ce) | Sep 14, 2023 |
| ASUSTek       | GL753VD                     | Notebook    | [7bf98a1052](https://linux-hardware.org/?probe=7bf98a1052) | Sep 13, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [28116ad85d](https://linux-hardware.org/?probe=28116ad85d) | Sep 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [675582a822](https://linux-hardware.org/?probe=675582a822) | Sep 12, 2023 |
| Gigabyte      | EP45-UD3LR                  | Desktop     | [7dc196091d](https://linux-hardware.org/?probe=7dc196091d) | Sep 12, 2023 |
| Dell          | Precision 7520              | Notebook    | [803e67f286](https://linux-hardware.org/?probe=803e67f286) | Sep 12, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [e12c2067df](https://linux-hardware.org/?probe=e12c2067df) | Sep 11, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [aabd401f54](https://linux-hardware.org/?probe=aabd401f54) | Sep 11, 2023 |
| MSI           | B450M BAZOOKA V2            | Desktop     | [a98de00f8f](https://linux-hardware.org/?probe=a98de00f8f) | Sep 11, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [7809da04f1](https://linux-hardware.org/?probe=7809da04f1) | Sep 10, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [16c285bb07](https://linux-hardware.org/?probe=16c285bb07) | Sep 10, 2023 |
| Acer          | Predator PH315-54           | Notebook    | [2088909e8a](https://linux-hardware.org/?probe=2088909e8a) | Sep 10, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [b52a6f9b59](https://linux-hardware.org/?probe=b52a6f9b59) | Sep 10, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [1285b4583d](https://linux-hardware.org/?probe=1285b4583d) | Sep 10, 2023 |
| Intel         | NUC8CYB J69922-405          | Mini pc     | [00ad48fba7](https://linux-hardware.org/?probe=00ad48fba7) | Sep 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [36c9a9e4d4](https://linux-hardware.org/?probe=36c9a9e4d4) | Sep 10, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [8e988d79b7](https://linux-hardware.org/?probe=8e988d79b7) | Sep 09, 2023 |
| BESSTAR Te... | UM700                       | Desktop     | [a93bb80cb8](https://linux-hardware.org/?probe=a93bb80cb8) | Sep 09, 2023 |
| Samsung       | RV413/RV513                 | Notebook    | [c59551fc6f](https://linux-hardware.org/?probe=c59551fc6f) | Sep 09, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [c0bbe7d2b4](https://linux-hardware.org/?probe=c0bbe7d2b4) | Sep 09, 2023 |
| ASUSTek       | G750JW                      | Notebook    | [2e81baa143](https://linux-hardware.org/?probe=2e81baa143) | Sep 09, 2023 |
| ASUSTek       | P8H61-M LX2 R2.0            | Desktop     | [9d0bacfabd](https://linux-hardware.org/?probe=9d0bacfabd) | Sep 09, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [6ed0b47516](https://linux-hardware.org/?probe=6ed0b47516) | Sep 08, 2023 |
| BESSTAR Te... | HX90                        | Desktop     | [f8c66085b0](https://linux-hardware.org/?probe=f8c66085b0) | Sep 08, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [d6cfec3d58](https://linux-hardware.org/?probe=d6cfec3d58) | Sep 08, 2023 |
| Gigabyte      | Z390 UD V2                  | Desktop     | [598ed8c100](https://linux-hardware.org/?probe=598ed8c100) | Sep 08, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | Desktop     | [6dbe579385](https://linux-hardware.org/?probe=6dbe579385) | Sep 08, 2023 |
| ASUSTek       | X541UVK                     | Notebook    | [425b748769](https://linux-hardware.org/?probe=425b748769) | Sep 08, 2023 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [8fc5475fd3](https://linux-hardware.org/?probe=8fc5475fd3) | Sep 08, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [8d183a9972](https://linux-hardware.org/?probe=8d183a9972) | Sep 08, 2023 |
| ASUSTek       | PRIME H270-PLUS             | Desktop     | [721c2adc46](https://linux-hardware.org/?probe=721c2adc46) | Sep 07, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [654a62e050](https://linux-hardware.org/?probe=654a62e050) | Sep 07, 2023 |
| BESSTAR Te... | UM700                       | Desktop     | [d635105967](https://linux-hardware.org/?probe=d635105967) | Sep 07, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [bedbf331b0](https://linux-hardware.org/?probe=bedbf331b0) | Sep 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [4fd02051b6](https://linux-hardware.org/?probe=4fd02051b6) | Sep 07, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [2385447c50](https://linux-hardware.org/?probe=2385447c50) | Sep 07, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | Desktop     | [a4624a95da](https://linux-hardware.org/?probe=a4624a95da) | Sep 07, 2023 |
| Dell          | Latitude E5450              | Notebook    | [a705913b6e](https://linux-hardware.org/?probe=a705913b6e) | Sep 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [8c22ca23f2](https://linux-hardware.org/?probe=8c22ca23f2) | Sep 07, 2023 |
| Lenovo        | ThinkPad T480 20L6S1FU00    | Notebook    | [f24dc99222](https://linux-hardware.org/?probe=f24dc99222) | Sep 06, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [c890510220](https://linux-hardware.org/?probe=c890510220) | Sep 06, 2023 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | Desktop     | [e47f10b579](https://linux-hardware.org/?probe=e47f10b579) | Sep 06, 2023 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | Desktop     | [d1cf42c68c](https://linux-hardware.org/?probe=d1cf42c68c) | Sep 06, 2023 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | Desktop     | [4d1ca2eb79](https://linux-hardware.org/?probe=4d1ca2eb79) | Sep 06, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [995b1f100d](https://linux-hardware.org/?probe=995b1f100d) | Sep 06, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [a1c2c12b6f](https://linux-hardware.org/?probe=a1c2c12b6f) | Sep 06, 2023 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [99dd75f86a](https://linux-hardware.org/?probe=99dd75f86a) | Sep 05, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [cdabed6210](https://linux-hardware.org/?probe=cdabed6210) | Sep 05, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [054c5e3dc5](https://linux-hardware.org/?probe=054c5e3dc5) | Sep 05, 2023 |
| Dynabook      | Satellite Pro L50-G-193     | Notebook    | [6ab6bec7be](https://linux-hardware.org/?probe=6ab6bec7be) | Sep 05, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [8bca1f8244](https://linux-hardware.org/?probe=8bca1f8244) | Sep 05, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [e48cab52a7](https://linux-hardware.org/?probe=e48cab52a7) | Sep 05, 2023 |
| Dell          | Inspiron 7560               | Notebook    | [dc22012520](https://linux-hardware.org/?probe=dc22012520) | Sep 05, 2023 |
| Gigabyte      | X299 AORUS Ultra Gaming-... | Desktop     | [77c07d0f70](https://linux-hardware.org/?probe=77c07d0f70) | Sep 05, 2023 |
| Gigabyte      | X299 AORUS Ultra Gaming-... | Desktop     | [a0aaf4be5d](https://linux-hardware.org/?probe=a0aaf4be5d) | Sep 05, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [e65692f205](https://linux-hardware.org/?probe=e65692f205) | Sep 05, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [106e2d1e98](https://linux-hardware.org/?probe=106e2d1e98) | Sep 04, 2023 |
| HP            | ProBook x360 435 G8 Note... | Convertible | [5a9932b3b8](https://linux-hardware.org/?probe=5a9932b3b8) | Sep 04, 2023 |
| HP            | ProBook x360 435 G8 Note... | Convertible | [def3f0d266](https://linux-hardware.org/?probe=def3f0d266) | Sep 04, 2023 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [a28ca9b2fb](https://linux-hardware.org/?probe=a28ca9b2fb) | Sep 04, 2023 |
| HP            | Pavilion g7                 | Notebook    | [a2a69279d6](https://linux-hardware.org/?probe=a2a69279d6) | Sep 04, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [8a8a236a44](https://linux-hardware.org/?probe=8a8a236a44) | Sep 04, 2023 |
| AZW           | MINI S                      | Desktop     | [331702f893](https://linux-hardware.org/?probe=331702f893) | Sep 04, 2023 |
| Lenovo        | ThinkPad W541 20EGS24300    | Notebook    | [a28d4357d8](https://linux-hardware.org/?probe=a28d4357d8) | Sep 03, 2023 |
| HP            | Folio 13                    | Notebook    | [d5844cc9e8](https://linux-hardware.org/?probe=d5844cc9e8) | Sep 03, 2023 |
| Lenovo        | ThinkPad E490 20N9001RBR    | Notebook    | [b9de538f7e](https://linux-hardware.org/?probe=b9de538f7e) | Sep 03, 2023 |
| HP            | OMEN by Laptop 17-an0xx     | Notebook    | [884eaad43c](https://linux-hardware.org/?probe=884eaad43c) | Sep 03, 2023 |
| IP3 Tech      | rev1.0                      | All in one  | [d2c6f51ff8](https://linux-hardware.org/?probe=d2c6f51ff8) | Sep 03, 2023 |
| Acer          | Nitro N50-600 V:1.1         | Desktop     | [d15e4d0045](https://linux-hardware.org/?probe=d15e4d0045) | Sep 03, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [e05acf231c](https://linux-hardware.org/?probe=e05acf231c) | Sep 03, 2023 |
| Lenovo        | ThinkPad X230 23252SG       | Notebook    | [78c449e398](https://linux-hardware.org/?probe=78c449e398) | Sep 03, 2023 |
| Lenovo        | ThinkPad X230 23252SG       | Notebook    | [7f25cc995d](https://linux-hardware.org/?probe=7f25cc995d) | Sep 03, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [47ef8122dc](https://linux-hardware.org/?probe=47ef8122dc) | Sep 03, 2023 |
| Dell          | G3 3779                     | Notebook    | [56fa43078f](https://linux-hardware.org/?probe=56fa43078f) | Sep 02, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [9f8e38af3e](https://linux-hardware.org/?probe=9f8e38af3e) | Sep 02, 2023 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [59014a9e20](https://linux-hardware.org/?probe=59014a9e20) | Sep 02, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [19e076e3e1](https://linux-hardware.org/?probe=19e076e3e1) | Sep 01, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [4b8aead223](https://linux-hardware.org/?probe=4b8aead223) | Sep 01, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [773143cf61](https://linux-hardware.org/?probe=773143cf61) | Sep 01, 2023 |
| Lenovo        | ThinkPad T430 2349IF8       | Notebook    | [b52faa8776](https://linux-hardware.org/?probe=b52faa8776) | Sep 01, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [5f50ef24fe](https://linux-hardware.org/?probe=5f50ef24fe) | Sep 01, 2023 |
| Intel         | NUC7i3BNB J22859-310        | Mini pc     | [cd552285b0](https://linux-hardware.org/?probe=cd552285b0) | Sep 01, 2023 |
| HP            | ZBook Firefly 15 G7 Mobi... | Notebook    | [ad4df3d293](https://linux-hardware.org/?probe=ad4df3d293) | Aug 31, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [cef6754cd9](https://linux-hardware.org/?probe=cef6754cd9) | Aug 31, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [13ec5c53cf](https://linux-hardware.org/?probe=13ec5c53cf) | Aug 31, 2023 |
| Lenovo        | Legion Y920-17IKB Laptop... | Notebook    | [5976d2d9e9](https://linux-hardware.org/?probe=5976d2d9e9) | Aug 31, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [a829cc0dce](https://linux-hardware.org/?probe=a829cc0dce) | Aug 31, 2023 |
| ASUSTek       | X541UAK                     | Notebook    | [c75a044974](https://linux-hardware.org/?probe=c75a044974) | Aug 30, 2023 |
| Positivo      | POS-RIB360EE 11144907       | Desktop     | [ebcd50f639](https://linux-hardware.org/?probe=ebcd50f639) | Aug 30, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [885c22f859](https://linux-hardware.org/?probe=885c22f859) | Aug 30, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [a31df2b8fe](https://linux-hardware.org/?probe=a31df2b8fe) | Aug 30, 2023 |
| HP            | 802F                        | Desktop     | [7d065f8fd1](https://linux-hardware.org/?probe=7d065f8fd1) | Aug 30, 2023 |
| Lenovo        | ThinkPad A475 20KMS0K20S    | Notebook    | [2685098cd9](https://linux-hardware.org/?probe=2685098cd9) | Aug 29, 2023 |
| ASUSTek       | G750JM                      | Notebook    | [ca4dd5a11e](https://linux-hardware.org/?probe=ca4dd5a11e) | Aug 29, 2023 |
| Positivo      | POS-RIB360EE 11144907       | Desktop     | [c392d83e8e](https://linux-hardware.org/?probe=c392d83e8e) | Aug 29, 2023 |
| Dell          | 0V8WGR A01                  | Desktop     | [9e5ed52b45](https://linux-hardware.org/?probe=9e5ed52b45) | Aug 29, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [5a20b8cd20](https://linux-hardware.org/?probe=5a20b8cd20) | Aug 29, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [708fc220a9](https://linux-hardware.org/?probe=708fc220a9) | Aug 29, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [0789880eae](https://linux-hardware.org/?probe=0789880eae) | Aug 29, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [265430a40c](https://linux-hardware.org/?probe=265430a40c) | Aug 29, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [6bd291c8b0](https://linux-hardware.org/?probe=6bd291c8b0) | Aug 29, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [0f3d530e12](https://linux-hardware.org/?probe=0f3d530e12) | Aug 29, 2023 |
| AMI           | Cherry Trail CR             | Mini pc     | [e27639a1f9](https://linux-hardware.org/?probe=e27639a1f9) | Aug 29, 2023 |
| HP            | 8061                        | Desktop     | [31a0fa50a3](https://linux-hardware.org/?probe=31a0fa50a3) | Aug 29, 2023 |
| Lenovo        | Legion 5 Pro 16ITH6 82JF    | Notebook    | [0ccccd5c9d](https://linux-hardware.org/?probe=0ccccd5c9d) | Aug 28, 2023 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | Desktop     | [5df3abe62e](https://linux-hardware.org/?probe=5df3abe62e) | Aug 28, 2023 |
| ASUSTek       | Vivobook ASUSLaptop TP34... | Convertible | [3c5aa8e05a](https://linux-hardware.org/?probe=3c5aa8e05a) | Aug 28, 2023 |
| Dell          | Inspiron 3580               | Notebook    | [0cda85fdd1](https://linux-hardware.org/?probe=0cda85fdd1) | Aug 28, 2023 |
| Acer          | Aspire M3470                | Desktop     | [60d18d6d6e](https://linux-hardware.org/?probe=60d18d6d6e) | Aug 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [269a4ac17d](https://linux-hardware.org/?probe=269a4ac17d) | Aug 28, 2023 |
| Lenovo        | ThinkPad X220 4291C84       | Notebook    | [623b0f76d1](https://linux-hardware.org/?probe=623b0f76d1) | Aug 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [8b82375189](https://linux-hardware.org/?probe=8b82375189) | Aug 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [90474aa183](https://linux-hardware.org/?probe=90474aa183) | Aug 27, 2023 |
| Samsung       | R530/R730/R540              | Notebook    | [1112486ef3](https://linux-hardware.org/?probe=1112486ef3) | Aug 27, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [f1422f4092](https://linux-hardware.org/?probe=f1422f4092) | Aug 27, 2023 |
| Samsung       | R530/R730/R540              | Notebook    | [99e5a7a753](https://linux-hardware.org/?probe=99e5a7a753) | Aug 27, 2023 |
| Lenovo        | ThinkPad T430 2349IF8       | Notebook    | [8c616e6421](https://linux-hardware.org/?probe=8c616e6421) | Aug 27, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [8ee512db27](https://linux-hardware.org/?probe=8ee512db27) | Aug 27, 2023 |
| Acer          | Aspire M3470                | Desktop     | [7e6d230bf5](https://linux-hardware.org/?probe=7e6d230bf5) | Aug 27, 2023 |
| ASRock        | X570 Phantom Gaming 4S      | Desktop     | [1be18fe99f](https://linux-hardware.org/?probe=1be18fe99f) | Aug 27, 2023 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | Desktop     | [512429f429](https://linux-hardware.org/?probe=512429f429) | Aug 27, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [bf1d0a62ed](https://linux-hardware.org/?probe=bf1d0a62ed) | Aug 26, 2023 |
| MSI           | GL73 8RC                    | Notebook    | [5ca33a6111](https://linux-hardware.org/?probe=5ca33a6111) | Aug 26, 2023 |
| Acer          | Predator G9-793             | Notebook    | [531f857477](https://linux-hardware.org/?probe=531f857477) | Aug 26, 2023 |
| HP            | 802F                        | Desktop     | [6759058353](https://linux-hardware.org/?probe=6759058353) | Aug 25, 2023 |
| Dell          | 0658N7 A01                  | Server      | [0b0ac21b18](https://linux-hardware.org/?probe=0b0ac21b18) | Aug 25, 2023 |
| ASUSTek       | ROG Strix G532LWS_G532LW... | Notebook    | [d28f06dcc5](https://linux-hardware.org/?probe=d28f06dcc5) | Aug 25, 2023 |
| System76      | Gazelle                     | Notebook    | [ee67365e0c](https://linux-hardware.org/?probe=ee67365e0c) | Aug 24, 2023 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | Notebook    | [aa3157f519](https://linux-hardware.org/?probe=aa3157f519) | Aug 24, 2023 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | Notebook    | [8d3738c790](https://linux-hardware.org/?probe=8d3738c790) | Aug 24, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [7fdfaacf03](https://linux-hardware.org/?probe=7fdfaacf03) | Aug 24, 2023 |
| AZW           | SER                         | Mini pc     | [309bc27af7](https://linux-hardware.org/?probe=309bc27af7) | Aug 24, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [3898bac5d4](https://linux-hardware.org/?probe=3898bac5d4) | Aug 24, 2023 |
| Intel         | NUC7i7DNB J83500-204        | Mini pc     | [de9c4fce3c](https://linux-hardware.org/?probe=de9c4fce3c) | Aug 24, 2023 |
| ASUSTek       | Q170M2                      | Desktop     | [a3de2e9813](https://linux-hardware.org/?probe=a3de2e9813) | Aug 23, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [68d3bc88e4](https://linux-hardware.org/?probe=68d3bc88e4) | Aug 23, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [6fa7d1e35d](https://linux-hardware.org/?probe=6fa7d1e35d) | Aug 23, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [799390e547](https://linux-hardware.org/?probe=799390e547) | Aug 23, 2023 |
| Dell          | 0D6H9T A00                  | Desktop     | [81b8c378f7](https://linux-hardware.org/?probe=81b8c378f7) | Aug 23, 2023 |
| Dell          | G3 3579                     | Notebook    | [49b4227da5](https://linux-hardware.org/?probe=49b4227da5) | Aug 22, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [353c7bca5a](https://linux-hardware.org/?probe=353c7bca5a) | Aug 22, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [39fa23e4b7](https://linux-hardware.org/?probe=39fa23e4b7) | Aug 22, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [b4133748fc](https://linux-hardware.org/?probe=b4133748fc) | Aug 21, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [2e06223da9](https://linux-hardware.org/?probe=2e06223da9) | Aug 21, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [9d07a3d5c7](https://linux-hardware.org/?probe=9d07a3d5c7) | Aug 21, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [2a468a2183](https://linux-hardware.org/?probe=2a468a2183) | Aug 21, 2023 |
| ASUSTek       | K53E                        | Notebook    | [9cce7a150e](https://linux-hardware.org/?probe=9cce7a150e) | Aug 21, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | Notebook    | [e6dceda4bc](https://linux-hardware.org/?probe=e6dceda4bc) | Aug 21, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [8be90f267b](https://linux-hardware.org/?probe=8be90f267b) | Aug 20, 2023 |
| ASUSTek       | X541UAK                     | Notebook    | [048ca1ce02](https://linux-hardware.org/?probe=048ca1ce02) | Aug 20, 2023 |
| Dell          | System XPS L502X            | Notebook    | [e85150614a](https://linux-hardware.org/?probe=e85150614a) | Aug 20, 2023 |
| Acer          | TravelMate P645-S           | Notebook    | [658d88e2a5](https://linux-hardware.org/?probe=658d88e2a5) | Aug 20, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Desktop     | [dedf0b23a3](https://linux-hardware.org/?probe=dedf0b23a3) | Aug 19, 2023 |
| Lenovo        | ThinkPad T440p 20AN007BI... | Notebook    | [498c86055c](https://linux-hardware.org/?probe=498c86055c) | Aug 19, 2023 |
| Dell          | G15 5511                    | Notebook    | [8032cca2b5](https://linux-hardware.org/?probe=8032cca2b5) | Aug 19, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [d7805c8232](https://linux-hardware.org/?probe=d7805c8232) | Aug 19, 2023 |
| Lenovo        | ThinkPad T440p 20AN007BI... | Notebook    | [7a389ac976](https://linux-hardware.org/?probe=7a389ac976) | Aug 19, 2023 |
| Gigabyte      | Z390 UD V2                  | Desktop     | [9f5242decc](https://linux-hardware.org/?probe=9f5242decc) | Aug 19, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [d8de59f346](https://linux-hardware.org/?probe=d8de59f346) | Aug 19, 2023 |
| Dell          | XPS L521X                   | Notebook    | [fdd6adb89a](https://linux-hardware.org/?probe=fdd6adb89a) | Aug 18, 2023 |
| Toshiba       | Satellite L55-B             | Notebook    | [4b2bcc2231](https://linux-hardware.org/?probe=4b2bcc2231) | Aug 18, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [3c8853c045](https://linux-hardware.org/?probe=3c8853c045) | Aug 18, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [beddeba8b6](https://linux-hardware.org/?probe=beddeba8b6) | Aug 18, 2023 |
| MSI           | Indio                       | Desktop     | [162ed509d4](https://linux-hardware.org/?probe=162ed509d4) | Aug 18, 2023 |
| MSI           | Z97 PC Mate                 | Desktop     | [bee6142eee](https://linux-hardware.org/?probe=bee6142eee) | Aug 17, 2023 |
| MSI           | Z77A-G45                    | Desktop     | [b72192373b](https://linux-hardware.org/?probe=b72192373b) | Aug 17, 2023 |
| Dell          | G3 3579                     | Notebook    | [567acf505b](https://linux-hardware.org/?probe=567acf505b) | Aug 17, 2023 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [8478931432](https://linux-hardware.org/?probe=8478931432) | Aug 17, 2023 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [3f0a5a32cf](https://linux-hardware.org/?probe=3f0a5a32cf) | Aug 17, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [6a2e05ff64](https://linux-hardware.org/?probe=6a2e05ff64) | Aug 17, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [0ba07cce6b](https://linux-hardware.org/?probe=0ba07cce6b) | Aug 17, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [06aebc0204](https://linux-hardware.org/?probe=06aebc0204) | Aug 17, 2023 |
| Gigabyte      | Z390 UD V2                  | Desktop     | [79d8f79efe](https://linux-hardware.org/?probe=79d8f79efe) | Aug 17, 2023 |
| ASUSTek       | GL552JX                     | Notebook    | [9594a231bd](https://linux-hardware.org/?probe=9594a231bd) | Aug 16, 2023 |
| Dell          | Inspiron 7370               | Notebook    | [2676762739](https://linux-hardware.org/?probe=2676762739) | Aug 16, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [bf65b5fe16](https://linux-hardware.org/?probe=bf65b5fe16) | Aug 16, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO II     | Desktop     | [122b800eae](https://linux-hardware.org/?probe=122b800eae) | Aug 16, 2023 |
| HP            | EliteBook 2740p             | Notebook    | [b288a65e53](https://linux-hardware.org/?probe=b288a65e53) | Aug 16, 2023 |
| ASRock        | B360M Pro4                  | Desktop     | [948ab98a6f](https://linux-hardware.org/?probe=948ab98a6f) | Aug 15, 2023 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [fc92556049](https://linux-hardware.org/?probe=fc92556049) | Aug 15, 2023 |
| Lenovo        | ThinkPad T490 20N2004EGE    | Notebook    | [11552492c0](https://linux-hardware.org/?probe=11552492c0) | Aug 15, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [2ac8f6838a](https://linux-hardware.org/?probe=2ac8f6838a) | Aug 15, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [b53cba2654](https://linux-hardware.org/?probe=b53cba2654) | Aug 15, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [64a1b8ad5d](https://linux-hardware.org/?probe=64a1b8ad5d) | Aug 14, 2023 |
| HP            | ZBook Firefly 14 inch G8... | Notebook    | [65f7a020fe](https://linux-hardware.org/?probe=65f7a020fe) | Aug 14, 2023 |
| Toshiba       | Satellite Pro C50-A-1E6     | Notebook    | [fe4612b027](https://linux-hardware.org/?probe=fe4612b027) | Aug 14, 2023 |
| Gigabyte      | X299 AORUS Ultra Gaming ... | Desktop     | [5a3c9080d8](https://linux-hardware.org/?probe=5a3c9080d8) | Aug 14, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [9d7d216fc0](https://linux-hardware.org/?probe=9d7d216fc0) | Aug 14, 2023 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | Desktop     | [da00873a9d](https://linux-hardware.org/?probe=da00873a9d) | Aug 14, 2023 |
| ASUSTek       | H110M-C/BR                  | Desktop     | [e6da28e1fb](https://linux-hardware.org/?probe=e6da28e1fb) | Aug 14, 2023 |
| Sony          | SVE1712W1EB                 | Notebook    | [a65f824e07](https://linux-hardware.org/?probe=a65f824e07) | Aug 14, 2023 |
| Sony          | SVE1712W1EB                 | Notebook    | [2da924ecb2](https://linux-hardware.org/?probe=2da924ecb2) | Aug 13, 2023 |
| Notebook      | N141CU                      | Notebook    | [06c2f33fb5](https://linux-hardware.org/?probe=06c2f33fb5) | Aug 13, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [c28cbbd2a1](https://linux-hardware.org/?probe=c28cbbd2a1) | Aug 13, 2023 |
| Monster       | ABRA A5 V17.2               | Notebook    | [0049202ca7](https://linux-hardware.org/?probe=0049202ca7) | Aug 13, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [6d1e3a24e8](https://linux-hardware.org/?probe=6d1e3a24e8) | Aug 13, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [2461c78ff0](https://linux-hardware.org/?probe=2461c78ff0) | Aug 13, 2023 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [3d99363ed5](https://linux-hardware.org/?probe=3d99363ed5) | Aug 13, 2023 |
| HP            | Folio 13                    | Notebook    | [62fcebde8c](https://linux-hardware.org/?probe=62fcebde8c) | Aug 13, 2023 |
| Lenovo        | ThinkPad P53s 20N6S00B00    | Notebook    | [3170e56ed1](https://linux-hardware.org/?probe=3170e56ed1) | Aug 13, 2023 |
| MSI           | Z97 GAMING 7                | Desktop     | [8414f16824](https://linux-hardware.org/?probe=8414f16824) | Aug 12, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [b6b99bf7bd](https://linux-hardware.org/?probe=b6b99bf7bd) | Aug 12, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [3ea3856297](https://linux-hardware.org/?probe=3ea3856297) | Aug 12, 2023 |
| Sony          | SVE1712W1EB                 | Notebook    | [e65db8d147](https://linux-hardware.org/?probe=e65db8d147) | Aug 12, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [72899a615b](https://linux-hardware.org/?probe=72899a615b) | Aug 12, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [d387c8fec5](https://linux-hardware.org/?probe=d387c8fec5) | Aug 11, 2023 |
| Unknown       | Unknown                     | Notebook    | [c90f282238](https://linux-hardware.org/?probe=c90f282238) | Aug 11, 2023 |
| Sony          | SVE1712W1EB                 | Notebook    | [6f323e0954](https://linux-hardware.org/?probe=6f323e0954) | Aug 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [a9f30f8dd0](https://linux-hardware.org/?probe=a9f30f8dd0) | Aug 11, 2023 |
| HP            | 158A                        | Desktop     | [96e7fa3b8f](https://linux-hardware.org/?probe=96e7fa3b8f) | Aug 11, 2023 |
| ASUSTek       | ROG Strix G513QY            | Notebook    | [eacd0cc54d](https://linux-hardware.org/?probe=eacd0cc54d) | Aug 11, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [c083cb5f2f](https://linux-hardware.org/?probe=c083cb5f2f) | Aug 11, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [980f6773f8](https://linux-hardware.org/?probe=980f6773f8) | Aug 10, 2023 |
| Lenovo        | ThinkPad P53s 20N6S00B00    | Notebook    | [c76e31ff8e](https://linux-hardware.org/?probe=c76e31ff8e) | Aug 10, 2023 |
| HP            | Folio 13                    | Notebook    | [67121fc711](https://linux-hardware.org/?probe=67121fc711) | Aug 10, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [025afcb20d](https://linux-hardware.org/?probe=025afcb20d) | Aug 10, 2023 |
| Lenovo        | ThinkPad T410 2522AC1       | Notebook    | [6f422f386f](https://linux-hardware.org/?probe=6f422f386f) | Aug 10, 2023 |
| HP            | 829A                        | Mini pc     | [ae08c868cf](https://linux-hardware.org/?probe=ae08c868cf) | Aug 10, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [e703bb179f](https://linux-hardware.org/?probe=e703bb179f) | Aug 10, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [60cfdb5283](https://linux-hardware.org/?probe=60cfdb5283) | Aug 10, 2023 |
| HP            | Folio 13                    | Notebook    | [889aae1772](https://linux-hardware.org/?probe=889aae1772) | Aug 10, 2023 |
| ASUSTek       | H87-PRO                     | Desktop     | [817c5f9f93](https://linux-hardware.org/?probe=817c5f9f93) | Aug 09, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [12e0dbd72c](https://linux-hardware.org/?probe=12e0dbd72c) | Aug 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [0cf2ab49c0](https://linux-hardware.org/?probe=0cf2ab49c0) | Aug 09, 2023 |
| HP            | Compaq 15                   | Notebook    | [387a3b8af2](https://linux-hardware.org/?probe=387a3b8af2) | Aug 09, 2023 |
| SZMZ          | X99M-G2                     | Desktop     | [e22cd6fdac](https://linux-hardware.org/?probe=e22cd6fdac) | Aug 09, 2023 |
| SZMZ          | X99M-G2                     | Desktop     | [2242417727](https://linux-hardware.org/?probe=2242417727) | Aug 09, 2023 |
| Lenovo        | ThinkPad X240 20AL00C6UK    | Notebook    | [d33c586eab](https://linux-hardware.org/?probe=d33c586eab) | Aug 09, 2023 |
| Dell          | 073Y7Y A00                  | Desktop     | [cbf4153713](https://linux-hardware.org/?probe=cbf4153713) | Aug 09, 2023 |
| AMI           | Cherry Trail CR             | Mini pc     | [ccb4eadbca](https://linux-hardware.org/?probe=ccb4eadbca) | Aug 08, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [d79ab70370](https://linux-hardware.org/?probe=d79ab70370) | Aug 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [5babb790d3](https://linux-hardware.org/?probe=5babb790d3) | Aug 08, 2023 |
| Gigabyte      | H610M S2H DDR4              | Desktop     | [ff4ead4bd3](https://linux-hardware.org/?probe=ff4ead4bd3) | Aug 08, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [e5a8c891d0](https://linux-hardware.org/?probe=e5a8c891d0) | Aug 08, 2023 |
| Toshiba       | Satellite C50-A510          | Notebook    | [335af4e25a](https://linux-hardware.org/?probe=335af4e25a) | Aug 08, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [3ff7f02af7](https://linux-hardware.org/?probe=3ff7f02af7) | Aug 08, 2023 |
| Insyde        | BayTrail                    | Notebook    | [df18553ec6](https://linux-hardware.org/?probe=df18553ec6) | Aug 07, 2023 |
| HP            | 8876 11                     | Desktop     | [059d4c2db2](https://linux-hardware.org/?probe=059d4c2db2) | Aug 07, 2023 |
| HP            | 158A                        | Desktop     | [657812fbbf](https://linux-hardware.org/?probe=657812fbbf) | Aug 07, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [51c3d4511a](https://linux-hardware.org/?probe=51c3d4511a) | Aug 07, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [5e64d2b59e](https://linux-hardware.org/?probe=5e64d2b59e) | Aug 06, 2023 |
| ASUSTek       | PRIME H310T R2.0            | Desktop     | [458a26f70c](https://linux-hardware.org/?probe=458a26f70c) | Aug 06, 2023 |
| ASRock        | B460 Phantom Gaming 4       | Desktop     | [5a254fe1d6](https://linux-hardware.org/?probe=5a254fe1d6) | Aug 06, 2023 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | Desktop     | [f670b492a9](https://linux-hardware.org/?probe=f670b492a9) | Aug 06, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [35bb5f3e65](https://linux-hardware.org/?probe=35bb5f3e65) | Aug 06, 2023 |
| Lenovo        | ThinkPad T420 4180AP3       | Notebook    | [bd989967e7](https://linux-hardware.org/?probe=bd989967e7) | Aug 06, 2023 |
| ASRock        | Z75 Pro3                    | Desktop     | [597461a5ac](https://linux-hardware.org/?probe=597461a5ac) | Aug 06, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [48cf16e31d](https://linux-hardware.org/?probe=48cf16e31d) | Aug 06, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [e815f65a97](https://linux-hardware.org/?probe=e815f65a97) | Aug 05, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [dfc4d46266](https://linux-hardware.org/?probe=dfc4d46266) | Aug 05, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [eb92759c2a](https://linux-hardware.org/?probe=eb92759c2a) | Aug 05, 2023 |
| Dell          | G15 5520                    | Notebook    | [baca0d14f5](https://linux-hardware.org/?probe=baca0d14f5) | Aug 05, 2023 |
| HP            | Pavilion g6                 | Notebook    | [fafbd706de](https://linux-hardware.org/?probe=fafbd706de) | Aug 05, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [dd1767aec1](https://linux-hardware.org/?probe=dd1767aec1) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [af4f153b11](https://linux-hardware.org/?probe=af4f153b11) | Aug 04, 2023 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [c163ae3710](https://linux-hardware.org/?probe=c163ae3710) | Aug 04, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [656e917b79](https://linux-hardware.org/?probe=656e917b79) | Aug 04, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [363bee1696](https://linux-hardware.org/?probe=363bee1696) | Aug 03, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | Desktop     | [31d1c3bfbc](https://linux-hardware.org/?probe=31d1c3bfbc) | Aug 03, 2023 |
| HP            | 21D0                        | Desktop     | [44e0cbb52e](https://linux-hardware.org/?probe=44e0cbb52e) | Aug 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [7f601fe313](https://linux-hardware.org/?probe=7f601fe313) | Aug 03, 2023 |
| HP            | 21D0                        | Desktop     | [099fea9193](https://linux-hardware.org/?probe=099fea9193) | Aug 02, 2023 |
| HP            | Pavilion g7                 | Notebook    | [882d2d9a16](https://linux-hardware.org/?probe=882d2d9a16) | Aug 02, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [75c36d43c3](https://linux-hardware.org/?probe=75c36d43c3) | Aug 02, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [e391326d89](https://linux-hardware.org/?probe=e391326d89) | Aug 02, 2023 |
| Dell          | Inspiron 14 Plus 7420       | Notebook    | [251b811e9b](https://linux-hardware.org/?probe=251b811e9b) | Aug 02, 2023 |
| HP            | Notebook                    | Notebook    | [258f6a82ad](https://linux-hardware.org/?probe=258f6a82ad) | Aug 02, 2023 |
| MSI           | H170M PRO-DH                | Desktop     | [e0b553c4dd](https://linux-hardware.org/?probe=e0b553c4dd) | Aug 02, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [eb2554dce9](https://linux-hardware.org/?probe=eb2554dce9) | Aug 02, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [451bfcf27d](https://linux-hardware.org/?probe=451bfcf27d) | Aug 02, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [79c3c3612b](https://linux-hardware.org/?probe=79c3c3612b) | Aug 02, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [19aa30337f](https://linux-hardware.org/?probe=19aa30337f) | Aug 02, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [589f0a8599](https://linux-hardware.org/?probe=589f0a8599) | Aug 01, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [8da287a76b](https://linux-hardware.org/?probe=8da287a76b) | Aug 01, 2023 |
| Gigabyte      | B650I AORUS ULTRA           | Desktop     | [26cca552dd](https://linux-hardware.org/?probe=26cca552dd) | Aug 01, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [93d193bdbc](https://linux-hardware.org/?probe=93d193bdbc) | Aug 01, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [8aaca0803f](https://linux-hardware.org/?probe=8aaca0803f) | Jul 31, 2023 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [18924cfab7](https://linux-hardware.org/?probe=18924cfab7) | Jul 31, 2023 |
| Samsung       | 535U3C                      | Notebook    | [8d0ebb957a](https://linux-hardware.org/?probe=8d0ebb957a) | Jul 31, 2023 |
| Samsung       | 535U3C                      | Notebook    | [030fc15fac](https://linux-hardware.org/?probe=030fc15fac) | Jul 31, 2023 |
| BESSTAR Te... | DMAF5 V1.0                  | Desktop     | [93c8724c91](https://linux-hardware.org/?probe=93c8724c91) | Jul 31, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [8559f3826b](https://linux-hardware.org/?probe=8559f3826b) | Jul 31, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [04b1a06dbd](https://linux-hardware.org/?probe=04b1a06dbd) | Jul 30, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [e66bd4564e](https://linux-hardware.org/?probe=e66bd4564e) | Jul 30, 2023 |
| Apple         | MacBookAir1,1               | Notebook    | [ac140cf8c4](https://linux-hardware.org/?probe=ac140cf8c4) | Jul 30, 2023 |
| Unknown       | HX90                        | Desktop     | [2eba30b5be](https://linux-hardware.org/?probe=2eba30b5be) | Jul 30, 2023 |
| HP            | Folio 13                    | Notebook    | [baaa648a4b](https://linux-hardware.org/?probe=baaa648a4b) | Jul 29, 2023 |
| Dell          | Latitude E6230              | Notebook    | [462496c6db](https://linux-hardware.org/?probe=462496c6db) | Jul 29, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [60bf32a368](https://linux-hardware.org/?probe=60bf32a368) | Jul 29, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [fb2ba2d3eb](https://linux-hardware.org/?probe=fb2ba2d3eb) | Jul 29, 2023 |
| Dell          | 0KV62T A00                  | Desktop     | [1b9bb7c266](https://linux-hardware.org/?probe=1b9bb7c266) | Jul 29, 2023 |
| ASRock        | B450M/ac                    | Desktop     | [51d9b57967](https://linux-hardware.org/?probe=51d9b57967) | Jul 29, 2023 |
| MSI           | B360M BAZOOKA               | Desktop     | [081608e70c](https://linux-hardware.org/?probe=081608e70c) | Jul 28, 2023 |
| Unknown       | Unknown                     | Notebook    | [e8368bcae8](https://linux-hardware.org/?probe=e8368bcae8) | Jul 28, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [32fcc0f81f](https://linux-hardware.org/?probe=32fcc0f81f) | Jul 28, 2023 |
| Intel         | HM570                       | Desktop     | [c969a88e87](https://linux-hardware.org/?probe=c969a88e87) | Jul 28, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [3c0f7ba188](https://linux-hardware.org/?probe=3c0f7ba188) | Jul 27, 2023 |
| ASUSTek       | ROG STRIX B560-G GAMING ... | Desktop     | [d32fa8840b](https://linux-hardware.org/?probe=d32fa8840b) | Jul 27, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [1a6962dc65](https://linux-hardware.org/?probe=1a6962dc65) | Jul 27, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [0b04075e09](https://linux-hardware.org/?probe=0b04075e09) | Jul 27, 2023 |
| ASRock        | B360M Pro4                  | Desktop     | [20221ed288](https://linux-hardware.org/?probe=20221ed288) | Jul 27, 2023 |
| Lenovo        | 3743 SDK0J40700 WIN 3258... | Desktop     | [546f011b1a](https://linux-hardware.org/?probe=546f011b1a) | Jul 27, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [ba305b3271](https://linux-hardware.org/?probe=ba305b3271) | Jul 26, 2023 |
| HP            | Folio 13                    | Notebook    | [a3269c0930](https://linux-hardware.org/?probe=a3269c0930) | Jul 26, 2023 |
| Dell          | G3 3579                     | Notebook    | [b6b50ffa46](https://linux-hardware.org/?probe=b6b50ffa46) | Jul 26, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [aa34907e3a](https://linux-hardware.org/?probe=aa34907e3a) | Jul 26, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [24c092f0b0](https://linux-hardware.org/?probe=24c092f0b0) | Jul 26, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [a5933aa510](https://linux-hardware.org/?probe=a5933aa510) | Jul 26, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [74adf4cb3d](https://linux-hardware.org/?probe=74adf4cb3d) | Jul 26, 2023 |
| Lenovo        | Legion R9000X 2021 82HN     | Notebook    | [0079a4e7a0](https://linux-hardware.org/?probe=0079a4e7a0) | Jul 25, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [7cd1c7cdf2](https://linux-hardware.org/?probe=7cd1c7cdf2) | Jul 25, 2023 |
| Gigabyte      | 970A-D3P                    | Desktop     | [fcb6317c1b](https://linux-hardware.org/?probe=fcb6317c1b) | Jul 25, 2023 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [7da659326d](https://linux-hardware.org/?probe=7da659326d) | Jul 24, 2023 |
| Dell          | Latitude E6230              | Notebook    | [6f832e0bb3](https://linux-hardware.org/?probe=6f832e0bb3) | Jul 24, 2023 |
| SiS Techno... | 760                         | Desktop     | [1c5bd52522](https://linux-hardware.org/?probe=1c5bd52522) | Jul 24, 2023 |
| AZW           | SER V2.0                    | Mini pc     | [176adf0a2b](https://linux-hardware.org/?probe=176adf0a2b) | Jul 24, 2023 |
| Acidanther... | Mac-CFF7D910A743CAAF iMa... | All in one  | [4a262a2a2d](https://linux-hardware.org/?probe=4a262a2a2d) | Jul 24, 2023 |
| ASUSTek       | PN61                        | Mini pc     | [78418a9a7f](https://linux-hardware.org/?probe=78418a9a7f) | Jul 24, 2023 |
| MSI           | B460M PRO-VDH WIFI          | Desktop     | [df1a812c11](https://linux-hardware.org/?probe=df1a812c11) | Jul 24, 2023 |
| Gigabyte      | 970A-D3P                    | Desktop     | [bd66a96c97](https://linux-hardware.org/?probe=bd66a96c97) | Jul 24, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [579d5d5771](https://linux-hardware.org/?probe=579d5d5771) | Jul 24, 2023 |
| Dell          | Latitude 5410               | Notebook    | [29261ea2bb](https://linux-hardware.org/?probe=29261ea2bb) | Jul 24, 2023 |
| Lenovo        | ThinkPad T480 20L5000BGE    | Notebook    | [f9bd193456](https://linux-hardware.org/?probe=f9bd193456) | Jul 23, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [1e169f0ba8](https://linux-hardware.org/?probe=1e169f0ba8) | Jul 23, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [ae4343c245](https://linux-hardware.org/?probe=ae4343c245) | Jul 23, 2023 |
| ASUSTek       | TUF Z270 MARK 2             | Desktop     | [b844b9a353](https://linux-hardware.org/?probe=b844b9a353) | Jul 23, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [f2f1f87d0c](https://linux-hardware.org/?probe=f2f1f87d0c) | Jul 23, 2023 |
| Dell          | Latitude 5480               | Notebook    | [0595e16f65](https://linux-hardware.org/?probe=0595e16f65) | Jul 23, 2023 |
| Dell          | 0KV62T A00                  | Desktop     | [f291f72d81](https://linux-hardware.org/?probe=f291f72d81) | Jul 23, 2023 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | Desktop     | [c4890b8f34](https://linux-hardware.org/?probe=c4890b8f34) | Jul 23, 2023 |
| ASRock        | B250M Pro4                  | Desktop     | [23d73ededd](https://linux-hardware.org/?probe=23d73ededd) | Jul 23, 2023 |
| ASRock        | B550M-HDV                   | Desktop     | [af255054c3](https://linux-hardware.org/?probe=af255054c3) | Jul 22, 2023 |
| ASUSTek       | X99-DELUXE II               | Desktop     | [afc4d3c307](https://linux-hardware.org/?probe=afc4d3c307) | Jul 22, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [be58f943df](https://linux-hardware.org/?probe=be58f943df) | Jul 22, 2023 |
| HP            | 21D0                        | Desktop     | [774375de1f](https://linux-hardware.org/?probe=774375de1f) | Jul 22, 2023 |
| Dell          | Latitude E7440              | Notebook    | [ffa2aad2b5](https://linux-hardware.org/?probe=ffa2aad2b5) | Jul 21, 2023 |
| ASUSTek       | Q170M2                      | Desktop     | [f3435d221b](https://linux-hardware.org/?probe=f3435d221b) | Jul 21, 2023 |
| Unknown       | Unknown                     | Notebook    | [516853cca9](https://linux-hardware.org/?probe=516853cca9) | Jul 21, 2023 |
| Biostar       | A320MH                      | Desktop     | [5fd84925fd](https://linux-hardware.org/?probe=5fd84925fd) | Jul 20, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [874f8dff98](https://linux-hardware.org/?probe=874f8dff98) | Jul 20, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [d1dee26c33](https://linux-hardware.org/?probe=d1dee26c33) | Jul 20, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [dc0a2fb7ef](https://linux-hardware.org/?probe=dc0a2fb7ef) | Jul 20, 2023 |
| Lenovo        | 330B SDK0T76530 WIN 3556... | Mini pc     | [f7218e4043](https://linux-hardware.org/?probe=f7218e4043) | Jul 20, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [13a6f964eb](https://linux-hardware.org/?probe=13a6f964eb) | Jul 19, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c8fa0f7219](https://linux-hardware.org/?probe=c8fa0f7219) | Jul 19, 2023 |
| Dell          | Latitude 5580               | Notebook    | [6efcf73621](https://linux-hardware.org/?probe=6efcf73621) | Jul 19, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [d79851836e](https://linux-hardware.org/?probe=d79851836e) | Jul 19, 2023 |
| HP            | G62                         | Notebook    | [c36d4392da](https://linux-hardware.org/?probe=c36d4392da) | Jul 19, 2023 |
| Lenovo        | ThinkPad T430 2349IF8       | Notebook    | [56e1ff54a3](https://linux-hardware.org/?probe=56e1ff54a3) | Jul 19, 2023 |
| ASUSTek       | ProArt StudioBook W730G5... | Notebook    | [dc091872ec](https://linux-hardware.org/?probe=dc091872ec) | Jul 18, 2023 |
| Acer          | One S1003                   | Tablet      | [380ae70fb2](https://linux-hardware.org/?probe=380ae70fb2) | Jul 18, 2023 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [ef3c6c941e](https://linux-hardware.org/?probe=ef3c6c941e) | Jul 18, 2023 |
| Google        | Kip                         | Notebook    | [00dd9a1c67](https://linux-hardware.org/?probe=00dd9a1c67) | Jul 18, 2023 |
| Acer          | Aspire E1-531               | Notebook    | [5797e88a56](https://linux-hardware.org/?probe=5797e88a56) | Jul 18, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [322db1cde6](https://linux-hardware.org/?probe=322db1cde6) | Jul 18, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [f0ecaa209e](https://linux-hardware.org/?probe=f0ecaa209e) | Jul 18, 2023 |
| Dell          | Latitude 5580               | Notebook    | [16f62b67d3](https://linux-hardware.org/?probe=16f62b67d3) | Jul 17, 2023 |
| Google        | Dragonair                   | Notebook    | [11d9394545](https://linux-hardware.org/?probe=11d9394545) | Jul 17, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [a83e3b42b3](https://linux-hardware.org/?probe=a83e3b42b3) | Jul 17, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [553cbdb79d](https://linux-hardware.org/?probe=553cbdb79d) | Jul 17, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [56a9ce9630](https://linux-hardware.org/?probe=56a9ce9630) | Jul 17, 2023 |
| Dell          | Inspiron 3580               | Notebook    | [e46543841d](https://linux-hardware.org/?probe=e46543841d) | Jul 16, 2023 |
| Dell          | G15 5520                    | Notebook    | [ed22e67151](https://linux-hardware.org/?probe=ed22e67151) | Jul 16, 2023 |
| Toshiba       | Satellite Pro C50-A-1E6     | Notebook    | [8977d2e0a3](https://linux-hardware.org/?probe=8977d2e0a3) | Jul 16, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [19b39ef686](https://linux-hardware.org/?probe=19b39ef686) | Jul 16, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [61ed023e0c](https://linux-hardware.org/?probe=61ed023e0c) | Jul 16, 2023 |
| HP            | 8053                        | Desktop     | [bcdddcb036](https://linux-hardware.org/?probe=bcdddcb036) | Jul 15, 2023 |
| Dell          | G3 3779                     | Notebook    | [87b8ecffa4](https://linux-hardware.org/?probe=87b8ecffa4) | Jul 15, 2023 |
| Acer          | One S1003                   | Tablet      | [0e200bc1a5](https://linux-hardware.org/?probe=0e200bc1a5) | Jul 15, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [56448b6dd8](https://linux-hardware.org/?probe=56448b6dd8) | Jul 15, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [10946f1220](https://linux-hardware.org/?probe=10946f1220) | Jul 15, 2023 |
| Fujitsu       | LIFEBOOK T902               | Notebook    | [064a46bc1d](https://linux-hardware.org/?probe=064a46bc1d) | Jul 14, 2023 |
| AZW           | SER V2.0                    | Mini pc     | [c56d5e4e7b](https://linux-hardware.org/?probe=c56d5e4e7b) | Jul 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [f1bbc61bb6](https://linux-hardware.org/?probe=f1bbc61bb6) | Jul 14, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [0ac2423aa2](https://linux-hardware.org/?probe=0ac2423aa2) | Jul 14, 2023 |
| Dell          | Latitude E6230              | Notebook    | [1577fae8ee](https://linux-hardware.org/?probe=1577fae8ee) | Jul 14, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [76513f6a7d](https://linux-hardware.org/?probe=76513f6a7d) | Jul 14, 2023 |
| Lenovo        | Slim 7 16IAH7 82VB          | Notebook    | [7816d37e02](https://linux-hardware.org/?probe=7816d37e02) | Jul 14, 2023 |
| Gigabyte      | B550 GAMING X               | Desktop     | [67b2bb6155](https://linux-hardware.org/?probe=67b2bb6155) | Jul 14, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [91145d3929](https://linux-hardware.org/?probe=91145d3929) | Jul 13, 2023 |
| Lenovo        | ThinkPad X280 20KES73S06    | Notebook    | [b301164e01](https://linux-hardware.org/?probe=b301164e01) | Jul 13, 2023 |
| ASUSTek       | N61Jv                       | Notebook    | [fa3485dbc6](https://linux-hardware.org/?probe=fa3485dbc6) | Jul 13, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [2f943c811e](https://linux-hardware.org/?probe=2f943c811e) | Jul 13, 2023 |
| Unknown       | Unknown                     | Notebook    | [9430a42f8b](https://linux-hardware.org/?probe=9430a42f8b) | Jul 13, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [f73994358d](https://linux-hardware.org/?probe=f73994358d) | Jul 13, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [b189eebd1c](https://linux-hardware.org/?probe=b189eebd1c) | Jul 13, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [99c9883e16](https://linux-hardware.org/?probe=99c9883e16) | Jul 12, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [85d4919b9c](https://linux-hardware.org/?probe=85d4919b9c) | Jul 12, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a167d41a74](https://linux-hardware.org/?probe=a167d41a74) | Jul 12, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [6e7ff15b27](https://linux-hardware.org/?probe=6e7ff15b27) | Jul 11, 2023 |
| ASUSTek       | Zephyrus M GM501GM          | Notebook    | [72454f0f8e](https://linux-hardware.org/?probe=72454f0f8e) | Jul 11, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [ea833bb195](https://linux-hardware.org/?probe=ea833bb195) | Jul 11, 2023 |
| HP            | Folio 13                    | Notebook    | [864b74d611](https://linux-hardware.org/?probe=864b74d611) | Jul 11, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [cc4f862316](https://linux-hardware.org/?probe=cc4f862316) | Jul 11, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [0549d09ceb](https://linux-hardware.org/?probe=0549d09ceb) | Jul 11, 2023 |
| HP            | 21D0                        | Desktop     | [a6d51a414c](https://linux-hardware.org/?probe=a6d51a414c) | Jul 11, 2023 |
| HP            | Folio 13                    | Notebook    | [35d5a3c2a3](https://linux-hardware.org/?probe=35d5a3c2a3) | Jul 11, 2023 |
| Dell          | Inspiron 7573               | Notebook    | [7cc0dc9187](https://linux-hardware.org/?probe=7cc0dc9187) | Jul 11, 2023 |
| Lenovo        | ThinkPad L380 Yoga 20M70... | Convertible | [cf79171424](https://linux-hardware.org/?probe=cf79171424) | Jul 10, 2023 |
| MSI           | MS-7309                     | Desktop     | [16f6545b66](https://linux-hardware.org/?probe=16f6545b66) | Jul 10, 2023 |
| ASUSTek       | H87-PRO                     | Desktop     | [ef2ca9e804](https://linux-hardware.org/?probe=ef2ca9e804) | Jul 10, 2023 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [3924343595](https://linux-hardware.org/?probe=3924343595) | Jul 10, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [61ac758cca](https://linux-hardware.org/?probe=61ac758cca) | Jul 10, 2023 |
| ASRock        | B460M-HDV                   | Desktop     | [7790bc9f7b](https://linux-hardware.org/?probe=7790bc9f7b) | Jul 09, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [ea2102a05b](https://linux-hardware.org/?probe=ea2102a05b) | Jul 09, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [655b6ba155](https://linux-hardware.org/?probe=655b6ba155) | Jul 09, 2023 |
| Intel         | H61                         | Desktop     | [11e024727c](https://linux-hardware.org/?probe=11e024727c) | Jul 09, 2023 |
| HP            | ZBook Studio x360 G5        | Convertible | [e01e0e6f7e](https://linux-hardware.org/?probe=e01e0e6f7e) | Jul 09, 2023 |
| Dell          | Inspiron 7415 2-in-1        | Convertible | [db2be54a62](https://linux-hardware.org/?probe=db2be54a62) | Jul 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [ee4b75fe8e](https://linux-hardware.org/?probe=ee4b75fe8e) | Jul 09, 2023 |
| Notebook      | N141CU                      | Notebook    | [6d98546fa9](https://linux-hardware.org/?probe=6d98546fa9) | Jul 09, 2023 |
| Fujitsu       | LIFEBOOK T902               | Notebook    | [e23beb2c2a](https://linux-hardware.org/?probe=e23beb2c2a) | Jul 08, 2023 |
| ATOPNUC       | MA90                        | Mini pc     | [8ef192f620](https://linux-hardware.org/?probe=8ef192f620) | Jul 08, 2023 |
| HP            | 83E2                        | Desktop     | [7764034dad](https://linux-hardware.org/?probe=7764034dad) | Jul 08, 2023 |
| Dell          | Latitude 3380               | Notebook    | [b4403e7b15](https://linux-hardware.org/?probe=b4403e7b15) | Jul 07, 2023 |
| HP            | Folio 13                    | Notebook    | [dd1a09fa9d](https://linux-hardware.org/?probe=dd1a09fa9d) | Jul 07, 2023 |
| ASUSTek       | PRIME H310T R2.0            | Desktop     | [28b2f72ea7](https://linux-hardware.org/?probe=28b2f72ea7) | Jul 07, 2023 |
| Acer          | Predator G3600              | Desktop     | [79f515acf1](https://linux-hardware.org/?probe=79f515acf1) | Jul 07, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [1327d1ff3b](https://linux-hardware.org/?probe=1327d1ff3b) | Jul 07, 2023 |
| Fujitsu       | LIFEBOOK T902               | Notebook    | [dd071cd632](https://linux-hardware.org/?probe=dd071cd632) | Jul 07, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | Notebook    | [fdb4fd8cb4](https://linux-hardware.org/?probe=fdb4fd8cb4) | Jul 07, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [e7a7107e85](https://linux-hardware.org/?probe=e7a7107e85) | Jul 07, 2023 |
| Dell          | 0K240Y A02                  | Desktop     | [7d1d71b0fe](https://linux-hardware.org/?probe=7d1d71b0fe) | Jul 06, 2023 |
| HP            | 8053                        | Desktop     | [66ee68d1ba](https://linux-hardware.org/?probe=66ee68d1ba) | Jul 05, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [56609b5da2](https://linux-hardware.org/?probe=56609b5da2) | Jul 05, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [e6d6494e7a](https://linux-hardware.org/?probe=e6d6494e7a) | Jul 05, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [cd2c46c45c](https://linux-hardware.org/?probe=cd2c46c45c) | Jul 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [54a88e79d1](https://linux-hardware.org/?probe=54a88e79d1) | Jul 04, 2023 |
| ASUSTek       | PRIME H310M-E/BR            | Desktop     | [941c70d512](https://linux-hardware.org/?probe=941c70d512) | Jul 04, 2023 |
| CompuLab      | fitlet                      | Mini pc     | [41b26129b6](https://linux-hardware.org/?probe=41b26129b6) | Jul 04, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [075cc6eb8a](https://linux-hardware.org/?probe=075cc6eb8a) | Jul 04, 2023 |
| Dell          | Inspiron 5765               | Notebook    | [7d34d64627](https://linux-hardware.org/?probe=7d34d64627) | Jul 04, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [bba1bf2655](https://linux-hardware.org/?probe=bba1bf2655) | Jul 04, 2023 |
| Foxconn       | H81MXV/H81MXV-D             | Desktop     | [5920f3fec9](https://linux-hardware.org/?probe=5920f3fec9) | Jul 04, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [5d1b3596c1](https://linux-hardware.org/?probe=5d1b3596c1) | Jul 03, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [3290dd955a](https://linux-hardware.org/?probe=3290dd955a) | Jul 03, 2023 |
| Chuwi         | RZBOX                       | Desktop     | [78bdc20fe8](https://linux-hardware.org/?probe=78bdc20fe8) | Jul 03, 2023 |
| HP            | 886C                        | Desktop     | [735b488512](https://linux-hardware.org/?probe=735b488512) | Jul 03, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [b7222ef19f](https://linux-hardware.org/?probe=b7222ef19f) | Jul 03, 2023 |
| HP            | Folio 13                    | Notebook    | [faf3cb7d1f](https://linux-hardware.org/?probe=faf3cb7d1f) | Jul 03, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | Notebook    | [f78f6977d9](https://linux-hardware.org/?probe=f78f6977d9) | Jul 03, 2023 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | Desktop     | [6ce7d33591](https://linux-hardware.org/?probe=6ce7d33591) | Jul 03, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | Notebook    | [8120591fdf](https://linux-hardware.org/?probe=8120591fdf) | Jul 02, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [e3285ce484](https://linux-hardware.org/?probe=e3285ce484) | Jul 02, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [4f24850748](https://linux-hardware.org/?probe=4f24850748) | Jul 02, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [f341618e19](https://linux-hardware.org/?probe=f341618e19) | Jul 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [5a84f67b67](https://linux-hardware.org/?probe=5a84f67b67) | Jul 02, 2023 |
| Lenovo        | ThinkPad X230 232578G       | Notebook    | [80810e133e](https://linux-hardware.org/?probe=80810e133e) | Jul 02, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/ArcoLinux/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| ArcoLinux Rolling     | 2256      | 91.86%  |
| ArcoLinux             | 152       | 6.19%   |
| ArcoLinux 20.6.5      | 11        | 0.45%   |
| ArcoLinux 20.7.5      | 8         | 0.33%   |
| ArcoLinux 20.3.4      | 4         | 0.16%   |
| ArcoLinux 20.3.3      | 3         | 0.12%   |
| ArcoLinux 20.2.12     | 3         | 0.12%   |
| ArcoLinux 19.12.15    | 3         | 0.12%   |
| ArcoLinux 19.07.11    | 3         | 0.12%   |
| ArcoLinux 20.1.4      | 2         | 0.08%   |
| ArcoLinux 19.02.4     | 2         | 0.08%   |
| ArcoLinux I3-v19.02.4 | 1         | 0.04%   |
| ArcoLinux 6.9.2       | 1         | 0.04%   |
| ArcoLinux 6.9.1       | 1         | 0.04%   |
| ArcoLinux 20.5.7      | 1         | 0.04%   |
| ArcoLinux 20.5.2      | 1         | 0.04%   |
| ArcoLinux 20.4.11     | 1         | 0.04%   |
| ArcoLinux 20.2.9      | 1         | 0.04%   |
| ArcoLinux 19.11.3     | 1         | 0.04%   |
| ArcoLinux 19.03.3     | 1         | 0.04%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| ArcoLinux | 2431      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.15.7-arch1-1    | 48        | 1.56%   |
| 6.4.12-arch1-1    | 45        | 1.47%   |
| 6.3.8-arch1-1     | 40        | 1.3%    |
| 5.15.10-arch1-1   | 39        | 1.27%   |
| 5.13.13-arch1-1   | 38        | 1.24%   |
| 6.6.1-arch1-1     | 36        | 1.17%   |
| 6.4.11-arch1-1    | 30        | 0.98%   |
| 6.3.9-arch1-1     | 30        | 0.98%   |
| 6.5.9-arch2-1     | 29        | 0.94%   |
| 6.5.8-arch1-1     | 29        | 0.94%   |
| 6.2.11-arch1-1    | 29        | 0.94%   |
| 6.3.2-arch1-1     | 26        | 0.85%   |
| 5.16.11-arch1-1   | 26        | 0.85%   |
| 5.14.14-arch1-1   | 26        | 0.85%   |
| 6.5.3-arch1-1     | 25        | 0.81%   |
| 6.2.8-arch1-1     | 23        | 0.75%   |
| 6.5.5-arch1-1     | 22        | 0.72%   |
| 5.13.12-arch1-1   | 22        | 0.72%   |
| 6.6.7-arch1-1     | 21        | 0.68%   |
| 5.14.12-arch1-1   | 21        | 0.68%   |
| 6.5.7-arch1-1     | 20        | 0.65%   |
| 6.4.10-arch1-1    | 20        | 0.65%   |
| 6.3.3-arch1-1     | 20        | 0.65%   |
| 6.1.12-arch1-1    | 20        | 0.65%   |
| 6.4.11-arch2-1    | 19        | 0.62%   |
| 6.3.7-arch1-1     | 19        | 0.62%   |
| 6.6.3-arch1-1     | 18        | 0.59%   |
| 5.17.1-arch1-1    | 18        | 0.59%   |
| 6.3.5-arch1-1     | 17        | 0.55%   |
| 6.6.2-arch1-1     | 16        | 0.52%   |
| 5.8.14-arch1-1    | 16        | 0.52%   |
| 5.12.13-arch1-2   | 16        | 0.52%   |
| 6.4.12-zen1-1-zen | 15        | 0.49%   |
| 6.3.6-arch1-1     | 15        | 0.49%   |
| 6.3.4-arch1-1     | 15        | 0.49%   |
| 5.9.14-arch1-1    | 15        | 0.49%   |
| 5.19.13-arch1-1   | 15        | 0.49%   |
| 5.16.2-arch1-1    | 15        | 0.49%   |
| 5.12.15-arch1-1   | 15        | 0.49%   |
| 6.4.8-arch1-1     | 14        | 0.46%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.4.12  | 60        | 1.95%   |
| 5.15.7  | 59        | 1.92%   |
| 6.3.8   | 56        | 1.82%   |
| 6.4.11  | 54        | 1.76%   |
| 5.15.10 | 41        | 1.34%   |
| 6.6.1   | 39        | 1.27%   |
| 5.13.13 | 38        | 1.24%   |
| 6.5.3   | 37        | 1.21%   |
| 6.3.2   | 35        | 1.14%   |
| 6.5.9   | 34        | 1.11%   |
| 6.3.9   | 34        | 1.11%   |
| 6.5.5   | 33        | 1.07%   |
| 6.3.1   | 33        | 1.07%   |
| 6.2.11  | 33        | 1.07%   |
| 6.6.7   | 31        | 1.01%   |
| 6.5.8   | 31        | 1.01%   |
| 5.16.11 | 29        | 0.94%   |
| 6.3.3   | 28        | 0.91%   |
| 6.1.12  | 28        | 0.91%   |
| 6.5.7   | 26        | 0.85%   |
| 6.2.8   | 26        | 0.85%   |
| 5.14.14 | 26        | 0.85%   |
| 6.3.5   | 25        | 0.81%   |
| 6.0.2   | 25        | 0.81%   |
| 5.17.1  | 25        | 0.81%   |
| 6.4.2   | 24        | 0.78%   |
| 5.14.12 | 24        | 0.78%   |
| 5.13.12 | 24        | 0.78%   |
| 6.4.3   | 23        | 0.75%   |
| 6.4.10  | 22        | 0.72%   |
| 6.3.7   | 22        | 0.72%   |
| 6.3.4   | 22        | 0.72%   |
| 6.2.10  | 22        | 0.72%   |
| 6.4.7   | 20        | 0.65%   |
| 6.0.8   | 19        | 0.62%   |
| 5.9.14  | 19        | 0.62%   |
| 5.16.2  | 19        | 0.62%   |
| 6.6.3   | 18        | 0.59%   |
| 6.4.8   | 18        | 0.59%   |
| 6.4.1   | 18        | 0.59%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.15     | 301       | 10.3%   |
| 6.1      | 263       | 9%      |
| 6.3      | 261       | 8.93%   |
| 6.4      | 247       | 8.45%   |
| 5.10     | 214       | 7.32%   |
| 6.5      | 187       | 6.4%    |
| 6.2      | 150       | 5.13%   |
| 5.16     | 133       | 4.55%   |
| 5.14     | 131       | 4.48%   |
| 6.6      | 128       | 4.38%   |
| 6.0      | 122       | 4.17%   |
| 5.13     | 110       | 3.76%   |
| 5.9      | 109       | 3.73%   |
| 5.12     | 107       | 3.66%   |
| 5.17     | 92        | 3.15%   |
| 5.18     | 87        | 2.98%   |
| 5.11     | 77        | 2.63%   |
| 5.19     | 72        | 2.46%   |
| 5.4      | 60        | 2.05%   |
| 5.8      | 34        | 1.16%   |
| 5.6      | 7         | 0.24%   |
| 5.7      | 6         | 0.21%   |
| 5.5      | 5         | 0.17%   |
| 5.3      | 3         | 0.1%    |
| 5.0      | 3         | 0.1%    |
| 6.3.3    | 2         | 0.07%   |
| 5.15.96  | 2         | 0.07%   |
| 4.19     | 2         | 0.07%   |
| 6.5.2    | 1         | 0.03%   |
| 6.3.0    | 1         | 0.03%   |
| 6.2.0    | 1         | 0.03%   |
| 5.2      | 1         | 0.03%   |
| 5.15.107 | 1         | 0.03%   |
| 4.20     | 1         | 0.03%   |
| 4.18     | 1         | 0.03%   |
| 4.17     | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 2431      | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| XFCE           | 872       | 33.11%  |
| KDE5           | 543       | 20.62%  |
| GNOME          | 187       | 7.1%    |
| i3             | 185       | 7.02%   |
| awesome        | 119       | 4.52%   |
| qtile          | 82        | 3.11%   |
| Cinnamon       | 71        | 2.7%    |
| X-Cinnamon     | 69        | 2.62%   |
| bspwm          | 67        | 2.54%   |
| Hyprland       | 59        | 2.24%   |
| xmonad         | 53        | 2.01%   |
| dwm            | 45        | 1.71%   |
| Deepin         | 39        | 1.48%   |
| LeftWM         | 33        | 1.25%   |
| Budgie         | 30        | 1.14%   |
| Unknown        | 30        | 1.14%   |
| KDE            | 25        | 0.95%   |
| LXQt           | 21        | 0.8%    |
| chadwm         | 20        | 0.76%   |
| MATE           | 19        | 0.72%   |
| i3-with-shmlog | 12        | 0.46%   |
| herbstluftwm   | 12        | 0.46%   |
| sway           | 8         | 0.3%    |
| Cutefish       | 5         | 0.19%   |
| ICEWM          | 4         | 0.15%   |
| Unity          | 3         | 0.11%   |
| spectrwm       | 3         | 0.11%   |
| openbox        | 3         | 0.11%   |
| Hypr           | 3         | 0.11%   |
| cwm            | 3         | 0.11%   |
| GNOME Classic  | 2         | 0.08%   |
| dusk           | 2         | 0.08%   |
| XFCE:GNOME:    | 1         | 0.04%   |
| river          | 1         | 0.04%   |
| Pantheon       | 1         | 0.04%   |
| jwm            | 1         | 0.04%   |
| dwm-sc         | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 2185      | 87.86%  |
| Wayland | 168       | 6.76%   |
| Tty     | 103       | 4.14%   |
| Unknown | 31        | 1.25%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 1574      | 61.01%  |
| LightDM | 434       | 16.82%  |
| TDM     | 295       | 11.43%  |
| Unknown | 194       | 7.52%   |
| GDM     | 64        | 2.48%   |
| Ly      | 9         | 0.35%   |
| LXDM    | 8         | 0.31%   |
| XDM     | 1         | 0.04%   |
| SLiM    | 1         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1343      | 54.42%  |
| en_GB   | 202       | 8.18%   |
| de_DE   | 114       | 4.62%   |
| en_CA   | 82        | 3.32%   |
| C       | 66        | 2.67%   |
| en_IN   | 58        | 2.35%   |
| fr_FR   | 49        | 1.99%   |
| en_AU   | 49        | 1.99%   |
| ru_RU   | 48        | 1.94%   |
| pt_BR   | 45        | 1.82%   |
| es_ES   | 40        | 1.62%   |
| it_IT   | 34        | 1.38%   |
| es_MX   | 23        | 0.93%   |
| pl_PL   | 22        | 0.89%   |
| en_ZA   | 20        | 0.81%   |
| hu_HU   | 17        | 0.69%   |
| tr_TR   | 16        | 0.65%   |
| es_AR   | 15        | 0.61%   |
| sv_SE   | 14        | 0.57%   |
| Unknown | 14        | 0.57%   |
| zh_CN   | 12        | 0.49%   |
| nl_NL   | 11        | 0.45%   |
| en_PH   | 9         | 0.36%   |
| en_IE   | 9         | 0.36%   |
| fr_CA   | 8         | 0.32%   |
| en_DK   | 8         | 0.32%   |
| pt_PT   | 7         | 0.28%   |
| nl_BE   | 7         | 0.28%   |
| fi_FI   | 7         | 0.28%   |
| en_IL   | 7         | 0.28%   |
| ru_UA   | 6         | 0.24%   |
| ja_JP   | 6         | 0.24%   |
| en_SG   | 6         | 0.24%   |
| de_CH   | 5         | 0.2%    |
| de_AT   | 5         | 0.2%    |
| da_DK   | 5         | 0.2%    |
| uk_UA   | 4         | 0.16%   |
| nb_NO   | 4         | 0.16%   |
| fr_BE   | 4         | 0.16%   |
| es_CO   | 4         | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1839      | 74.63%  |
| BIOS | 625       | 25.37%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 1766      | 70.67%  |
| Btrfs    | 540       | 21.61%  |
| Overlay  | 131       | 5.24%   |
| Xfs      | 28        | 1.12%   |
| F2fs     | 21        | 0.84%   |
| Unknown  | 8         | 0.32%   |
| Reiserfs | 2         | 0.08%   |
| Jfs      | 2         | 0.08%   |
| Tmpfs    | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 1958      | 79.18%  |
| MBR     | 333       | 13.47%  |
| Unknown | 182       | 7.36%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1853      | 73.36%  |
| Yes       | 673       | 26.64%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1454      | 58.77%  |
| Yes       | 1020      | 41.23%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 497       | 20.44%  |
| Lenovo              | 413       | 16.99%  |
| Hewlett-Packard     | 273       | 11.23%  |
| Dell                | 261       | 10.74%  |
| Gigabyte Technology | 197       | 8.1%    |
| MSI                 | 186       | 7.65%   |
| Acer                | 101       | 4.15%   |
| ASRock              | 95        | 3.91%   |
| Apple               | 59        | 2.43%   |
| Intel               | 27        | 1.11%   |
| Toshiba             | 26        | 1.07%   |
| Unknown             | 22        | 0.9%    |
| Supermicro          | 18        | 0.74%   |
| Samsung Electronics | 18        | 0.74%   |
| HUAWEI              | 14        | 0.58%   |
| System76            | 12        | 0.49%   |
| Sony                | 12        | 0.49%   |
| Razer               | 12        | 0.49%   |
| Fujitsu             | 12        | 0.49%   |
| Medion              | 11        | 0.45%   |
| AZW                 | 10        | 0.41%   |
| Alienware           | 9         | 0.37%   |
| TUXEDO              | 7         | 0.29%   |
| Timi                | 7         | 0.29%   |
| Notebook            | 7         | 0.29%   |
| Chuwi               | 7         | 0.29%   |
| BESSTAR Tech        | 6         | 0.25%   |
| Packard Bell        | 5         | 0.21%   |
| Google              | 5         | 0.21%   |
| Pegatron            | 4         | 0.16%   |
| Monster             | 4         | 0.16%   |
| Microsoft           | 4         | 0.16%   |
| Foxconn             | 4         | 0.16%   |
| Biostar             | 4         | 0.16%   |
| ZOTAC               | 3         | 0.12%   |
| Schenker            | 3         | 0.12%   |
| LG Electronics      | 3         | 0.12%   |
| Huanan              | 3         | 0.12%   |
| Casper              | 3         | 0.12%   |
| Teclast             | 2         | 0.08%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Unknown                      | 29        | 1.19%   |
| ASUS All Series              | 21        | 0.86%   |
| ASUS TUF Gaming X570-PLUS    | 19        | 0.78%   |
| ASUS ROG STRIX B550-F GAMING | 13        | 0.53%   |
| MSI MS-7C37                  | 11        | 0.45%   |
| Supermicro SYS-5019A-FTN4    | 10        | 0.41%   |
| ASUS PRIME X570-P            | 10        | 0.41%   |
| MSI MS-7C91                  | 9         | 0.37%   |
| MSI MS-7B79                  | 9         | 0.37%   |
| HP Pavilion Notebook         | 9         | 0.37%   |
| MSI MS-7B89                  | 8         | 0.33%   |
| ASUS PRIME X470-PRO          | 8         | 0.33%   |
| MSI MS-7C02                  | 7         | 0.29%   |
| MSI MS-7A38                  | 7         | 0.29%   |
| HP Notebook                  | 7         | 0.29%   |
| Gigabyte X570 AORUS MASTER   | 7         | 0.29%   |
| Dell OptiPlex 7010           | 7         | 0.29%   |
| ASUS PRIME A320M-K           | 7         | 0.29%   |
| HP Laptop 15s-eq2xxx         | 6         | 0.25%   |
| Gigabyte X570 AORUS ELITE    | 6         | 0.25%   |
| Dell OptiPlex 9010           | 6         | 0.25%   |
| AZW SER                      | 6         | 0.25%   |
| ASUS ROG CROSSHAIR VIII HERO | 6         | 0.25%   |
| ASUS PRIME B450M-A           | 6         | 0.25%   |
| ASRock B450M Pro4            | 6         | 0.25%   |
| Razer Blade                  | 5         | 0.21%   |
| MSI MS-7C95                  | 5         | 0.21%   |
| MSI MS-7C56                  | 5         | 0.21%   |
| MSI MS-7971                  | 5         | 0.21%   |
| HP ProDesk 600 G1 SFF        | 5         | 0.21%   |
| HP Laptop 15-da0xxx          | 5         | 0.21%   |
| Gigabyte X570 GAMING X       | 5         | 0.21%   |
| Gigabyte X570 AORUS PRO WIFI | 5         | 0.21%   |
| Gigabyte B450M DS3H V2       | 5         | 0.21%   |
| Gigabyte B450 AORUS ELITE    | 5         | 0.21%   |
| Dell XPS 15 9560             | 5         | 0.21%   |
| Dell OptiPlex 9020           | 5         | 0.21%   |
| ASUS Z170 PRO GAMING         | 5         | 0.21%   |
| ASUS ROG STRIX X570-E GAMING | 5         | 0.21%   |
| ASUS M5A78L-M/USB3           | 5         | 0.21%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                      | Computers | Percent |
|---------------------------|-----------|---------|
| Lenovo ThinkPad           | 195       | 8.02%   |
| ASUS ROG                  | 92        | 3.78%   |
| ASUS PRIME                | 86        | 3.54%   |
| Lenovo IdeaPad            | 83        | 3.41%   |
| Dell Inspiron             | 75        | 3.09%   |
| Dell Latitude             | 58        | 2.39%   |
| ASUS TUF                  | 56        | 2.3%    |
| Acer Aspire               | 56        | 2.3%    |
| HP Pavilion               | 51        | 2.1%    |
| ASUS Vivobook             | 42        | 1.73%   |
| Dell OptiPlex             | 41        | 1.69%   |
| Lenovo Legion             | 37        | 1.52%   |
| HP Laptop                 | 37        | 1.52%   |
| Dell XPS                  | 34        | 1.4%    |
| HP EliteBook              | 31        | 1.28%   |
| Unknown                   | 29        | 1.19%   |
| Gigabyte X570             | 26        | 1.07%   |
| Dell Precision            | 23        | 0.95%   |
| Toshiba Satellite         | 22        | 0.9%    |
| HP ENVY                   | 21        | 0.86%   |
| ASUS All                  | 21        | 0.86%   |
| Lenovo ThinkCentre        | 19        | 0.78%   |
| Lenovo Yoga               | 16        | 0.66%   |
| Acer Nitro                | 16        | 0.66%   |
| Gigabyte B450M            | 15        | 0.62%   |
| Dell Vostro               | 14        | 0.58%   |
| HP OMEN                   | 13        | 0.53%   |
| HP Compaq                 | 13        | 0.53%   |
| ASUS ASUS                 | 12        | 0.49%   |
| ASRock B450M              | 12        | 0.49%   |
| Razer Blade               | 11        | 0.45%   |
| MSI MS-7C37               | 11        | 0.45%   |
| HP ProDesk                | 11        | 0.45%   |
| HP ProBook                | 11        | 0.45%   |
| HP EliteDesk              | 11        | 0.45%   |
| Gigabyte B450             | 11        | 0.45%   |
| ASUS ZenBook              | 11        | 0.45%   |
| Apple MacBookPro11        | 11        | 0.45%   |
| Acer Predator             | 11        | 0.45%   |
| Supermicro SYS-5019A-FTN4 | 10        | 0.41%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 310       | 12.75%  |
| 2019    | 308       | 12.67%  |
| 2018    | 304       | 12.51%  |
| 2021    | 219       | 9.01%   |
| 2017    | 202       | 8.31%   |
| 2013    | 153       | 6.29%   |
| 2012    | 141       | 5.8%    |
| 2016    | 140       | 5.76%   |
| 2011    | 125       | 5.14%   |
| 2015    | 120       | 4.94%   |
| 2014    | 120       | 4.94%   |
| 2022    | 102       | 4.2%    |
| 2010    | 76        | 3.13%   |
| 2023    | 31        | 1.28%   |
| 2009    | 29        | 1.19%   |
| 2008    | 29        | 1.19%   |
| 2007    | 13        | 0.53%   |
| 2006    | 6         | 0.25%   |
| 2005    | 1         | 0.04%   |
| 2004    | 1         | 0.04%   |
| Unknown | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 1260      | 51.83%  |
| Desktop     | 1037      | 42.66%  |
| Convertible | 55        | 2.26%   |
| Mini pc     | 39        | 1.6%    |
| All in one  | 23        | 0.95%   |
| Tablet      | 10        | 0.41%   |
| Server      | 6         | 0.25%   |
| Stick pc    | 1         | 0.04%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 2428      | 99.88%  |
| Enabled  | 3         | 0.12%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2420      | 99.55%  |
| Yes  | 11        | 0.45%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 657       | 26.66%  |
| 4.01-8.0        | 555       | 22.52%  |
| 8.01-16.0       | 416       | 16.88%  |
| 32.01-64.0      | 406       | 16.48%  |
| 3.01-4.0        | 213       | 8.64%   |
| 64.01-256.0     | 112       | 4.55%   |
| 24.01-32.0      | 68        | 2.76%   |
| 1.01-2.0        | 24        | 0.97%   |
| 2.01-3.0        | 11        | 0.45%   |
| More than 256.0 | 1         | 0.04%   |
| Unknown         | 1         | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 876       | 31.52%  |
| 2.01-3.0   | 690       | 24.83%  |
| 4.01-8.0   | 435       | 15.65%  |
| 3.01-4.0   | 401       | 14.43%  |
| 0.51-1.0   | 202       | 7.27%   |
| 8.01-16.0  | 131       | 4.71%   |
| 0.01-0.5   | 28        | 1.01%   |
| 16.01-24.0 | 12        | 0.43%   |
| 24.01-32.0 | 2         | 0.07%   |
| 32.01-64.0 | 1         | 0.04%   |
| Unknown    | 1         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1161      | 45.87%  |
| 2      | 744       | 29.4%   |
| 3      | 300       | 11.85%  |
| 4      | 161       | 6.36%   |
| 5      | 85        | 3.36%   |
| 6      | 39        | 1.54%   |
| 7      | 17        | 0.67%   |
| 0      | 7         | 0.28%   |
| 9      | 5         | 0.2%    |
| 8      | 4         | 0.16%   |
| 11     | 3         | 0.12%   |
| 10     | 2         | 0.08%   |
| 21     | 1         | 0.04%   |
| 19     | 1         | 0.04%   |
| 13     | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1812      | 73.93%  |
| Yes       | 639       | 26.07%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2131      | 87.26%  |
| No        | 311       | 12.74%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1865      | 76.37%  |
| No        | 577       | 23.63%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1709      | 69.25%  |
| No        | 759       | 30.75%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 536       | 21.91%  |
| Germany      | 184       | 7.52%   |
| UK           | 144       | 5.89%   |
| Canada       | 112       | 4.58%   |
| India        | 91        | 3.72%   |
| Brazil       | 90        | 3.68%   |
| France       | 72        | 2.94%   |
| Spain        | 66        | 2.7%    |
| Russia       | 62        | 2.53%   |
| Italy        | 58        | 2.37%   |
| Australia    | 56        | 2.29%   |
| Belgium      | 52        | 2.13%   |
| Netherlands  | 49        | 2%      |
| Turkey       | 46        | 1.88%   |
| Sweden       | 44        | 1.8%    |
| Poland       | 44        | 1.8%    |
| Mexico       | 38        | 1.55%   |
| Romania      | 30        | 1.23%   |
| Hungary      | 28        | 1.14%   |
| Argentina    | 27        | 1.1%    |
| Norway       | 25        | 1.02%   |
| Switzerland  | 24        | 0.98%   |
| Portugal     | 22        | 0.9%    |
| Indonesia    | 22        | 0.9%    |
| Finland      | 22        | 0.9%    |
| Ukraine      | 21        | 0.86%   |
| South Africa | 21        | 0.86%   |
| Greece       | 19        | 0.78%   |
| Bulgaria     | 19        | 0.78%   |
| Austria      | 19        | 0.78%   |
| Czechia      | 17        | 0.7%    |
| China        | 17        | 0.7%    |
| Denmark      | 15        | 0.61%   |
| Philippines  | 14        | 0.57%   |
| Colombia     | 14        | 0.57%   |
| Japan        | 13        | 0.53%   |
| Malaysia     | 12        | 0.49%   |
| Ireland      | 12        | 0.49%   |
| Egypt        | 12        | 0.49%   |
| Bangladesh   | 12        | 0.49%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Sydney            | 25        | 0.96%   |
| Berlin            | 24        | 0.92%   |
| Istanbul          | 19        | 0.73%   |
| Toronto           | 17        | 0.65%   |
| Madrid            | 17        | 0.65%   |
| Durham            | 17        | 0.65%   |
| Warsaw            | 14        | 0.53%   |
| Paris             | 14        | 0.53%   |
| Helsinki          | 14        | 0.53%   |
| Vienna            | 13        | 0.5%    |
| Sao Paulo         | 13        | 0.5%    |
| Moscow            | 13        | 0.5%    |
| Amsterdam         | 13        | 0.5%    |
| New York          | 12        | 0.46%   |
| Stockholm         | 11        | 0.42%   |
| Pune              | 11        | 0.42%   |
| Lier              | 11        | 0.42%   |
| Houston           | 11        | 0.42%   |
| Budapest          | 11        | 0.42%   |
| Atlanta           | 11        | 0.42%   |
| Sofia             | 10        | 0.38%   |
| Rio de Janeiro    | 10        | 0.38%   |
| Oslo              | 10        | 0.38%   |
| Los Angeles       | 10        | 0.38%   |
| London            | 10        | 0.38%   |
| Bucharest         | 10        | 0.38%   |
| Bengaluru         | 10        | 0.38%   |
| Zurich            | 9         | 0.34%   |
| Singapore         | 9         | 0.34%   |
| Portland          | 9         | 0.34%   |
| Melbourne         | 9         | 0.34%   |
| Frankfurt am Main | 9         | 0.34%   |
| Brisbane          | 9         | 0.34%   |
| Barcelona         | 9         | 0.34%   |
| Tehran            | 8         | 0.31%   |
| St Petersburg     | 8         | 0.31%   |
| Prague            | 8         | 0.31%   |
| Milan             | 8         | 0.31%   |
| Chicago           | 8         | 0.31%   |
| Charlotte         | 8         | 0.31%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 783       | 1381   | 18.5%   |
| WDC                         | 605       | 1031   | 14.3%   |
| Seagate                     | 525       | 813    | 12.41%  |
| Sandisk                     | 247       | 318    | 5.84%   |
| Toshiba                     | 237       | 309    | 5.6%    |
| Kingston                    | 223       | 343    | 5.27%   |
| Crucial                     | 170       | 243    | 4.02%   |
| SK hynix                    | 113       | 147    | 2.67%   |
| Intel                       | 108       | 160    | 2.55%   |
| Unknown                     | 86        | 122    | 2.03%   |
| Hitachi                     | 83        | 102    | 1.96%   |
| A-DATA Technology           | 67        | 86     | 1.58%   |
| Micron Technology           | 63        | 72     | 1.49%   |
| Phison Electronics          | 62        | 94     | 1.47%   |
| HGST                        | 57        | 83     | 1.35%   |
| Micron/Crucial Technology   | 44        | 59     | 1.04%   |
| Silicon Motion              | 39        | 50     | 0.92%   |
| Apple                       | 38        | 55     | 0.9%    |
| PNY                         | 36        | 51     | 0.85%   |
| China                       | 35        | 52     | 0.83%   |
| Kingston Technology Company | 34        | 48     | 0.8%    |
| KIOXIA                      | 33        | 40     | 0.78%   |
| Phison                      | 28        | 45     | 0.66%   |
| JMicron Technology          | 27        | 30     | 0.64%   |
| SPCC                        | 25        | 31     | 0.59%   |
| Corsair                     | 19        | 37     | 0.45%   |
| LITEON                      | 17        | 22     | 0.4%    |
| Hewlett-Packard             | 17        | 22     | 0.4%    |
| ADATA Technology            | 17        | 19     | 0.4%    |
| Realtek Semiconductor       | 16        | 20     | 0.38%   |
| Transcend                   | 14        | 18     | 0.33%   |
| SABRENT                     | 14        | 18     | 0.33%   |
| Patriot                     | 14        | 24     | 0.33%   |
| Gigabyte Technology         | 13        | 17     | 0.31%   |
| Plextor                     | 12        | 13     | 0.28%   |
| OCZ                         | 12        | 15     | 0.28%   |
| Intenso                     | 12        | 19     | 0.28%   |
| XPG                         | 11        | 14     | 0.26%   |
| LITEONIT                    | 11        | 11     | 0.26%   |
| MAXIO Technology (Hangzhou) | 10        | 14     | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB   | 117       | 2.43%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB    | 65        | 1.35%   |
| Samsung SSD 860 EVO 500GB                             | 60        | 1.25%   |
| Kingston SA400S37240G 240GB SSD                       | 53        | 1.1%    |
| Seagate ST1000LM035-1RK172 1TB                        | 50        | 1.04%   |
| Samsung SSD 850 EVO 250GB                             | 44        | 0.91%   |
| Crucial CT1000MX500SSD1 1TB                           | 37        | 0.77%   |
| Toshiba MQ01ABD100 1TB                                | 35        | 0.73%   |
| Samsung SSD 860 EVO 1TB                               | 35        | 0.73%   |
| Kingston SA400S37480G 480GB SSD                       | 34        | 0.71%   |
| Seagate ST1000DM010-2EP102 1TB                        | 32        | 0.66%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                   | 32        | 0.66%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 29        | 0.6%    |
| Seagate ST2000DM008-2FR102 2TB                        | 29        | 0.6%    |
| Samsung SSD 850 EVO 500GB                             | 29        | 0.6%    |
| Sandisk WD Blue SN550 NVMe SSD 512GB                  | 27        | 0.56%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB   | 25        | 0.52%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 24        | 0.5%    |
| Samsung SSD 860 EVO 250GB                             | 24        | 0.5%    |
| Samsung SSD 970 EVO Plus 500GB                        | 23        | 0.48%   |
| Samsung SSD 970 EVO Plus 1TB                          | 23        | 0.48%   |
| Toshiba MQ04ABF100 1TB                                | 22        | 0.46%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 22        | 0.46%   |
| Kingston SA400S37120G 120GB SSD                       | 22        | 0.46%   |
| Crucial CT500MX500SSD1 500GB                          | 22        | 0.46%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB      | 21        | 0.44%   |
| Samsung SSD 870 EVO 1TB                               | 21        | 0.44%   |
| Phison E12 NVMe Controller 512GB                      | 21        | 0.44%   |
| Unknown SD/MMC/MS PRO 128GB                           | 20        | 0.42%   |
| Toshiba DT01ACA100 1TB                                | 20        | 0.42%   |
| Seagate ST2000DM001-1ER164 2TB                        | 19        | 0.39%   |
| Phison E16 PCIe4 NVMe Controller 500GB                | 19        | 0.39%   |
| JMicron Generic 250GB                                 | 18        | 0.37%   |
| HGST HTS721010A9E630 1TB                              | 18        | 0.37%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 17        | 0.35%   |
| Samsung SSD 980 1TB                                   | 17        | 0.35%   |
| Crucial CT240BX500SSD1 240GB                          | 17        | 0.35%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                      | 16        | 0.33%   |
| Toshiba HDWD110 1TB                                   | 16        | 0.33%   |
| Seagate Expansion 1TB                                 | 16        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 510       | 778    | 36.53%  |
| WDC                 | 439       | 755    | 31.45%  |
| Toshiba             | 171       | 224    | 12.25%  |
| Hitachi             | 83        | 102    | 5.95%   |
| HGST                | 56        | 81     | 4.01%   |
| Samsung Electronics | 48        | 74     | 3.44%   |
| Unknown             | 22        | 30     | 1.58%   |
| Apple               | 11        | 19     | 0.79%   |
| TO Exter            | 6         | 6      | 0.43%   |
| Maxtor              | 6         | 9      | 0.43%   |
| ASMT                | 6         | 10     | 0.43%   |
| External            | 5         | 9      | 0.36%   |
| SSK                 | 4         | 4      | 0.29%   |
| Hewlett-Packard     | 4         | 5      | 0.29%   |
| Fujitsu             | 3         | 3      | 0.21%   |
| USB3.0              | 2         | 3      | 0.14%   |
| LaCie               | 2         | 2      | 0.14%   |
| Intenso             | 2         | 2      | 0.14%   |
| Fantom              | 2         | 5      | 0.14%   |
| ASMedia             | 2         | 3      | 0.14%   |
| WD MediaMax         | 1         | 1      | 0.07%   |
| StoreJet            | 1         | 1      | 0.07%   |
| RSH-319             | 1         | 1      | 0.07%   |
| Maxone              | 1         | 1      | 0.07%   |
| KESU                | 1         | 1      | 0.07%   |
| JMicron Technology  | 1         | 3      | 0.07%   |
| Inateck             | 1         | 1      | 0.07%   |
| HGST HUS            | 1         | 1      | 0.07%   |
| HGST HTS            | 1         | 1      | 0.07%   |
| H/W                 | 1         | 12     | 0.07%   |
| ExcelStor           | 1         | 2      | 0.07%   |
| Unknown             | 1         | 1      | 0.07%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 405       | 680    | 26.33%  |
| Kingston            | 176       | 254    | 11.44%  |
| Crucial             | 153       | 212    | 9.95%   |
| WDC                 | 125       | 182    | 8.13%   |
| SanDisk             | 121       | 149    | 7.87%   |
| A-DATA Technology   | 49        | 66     | 3.19%   |
| PNY                 | 35        | 47     | 2.28%   |
| China               | 35        | 52     | 2.28%   |
| SK hynix            | 32        | 50     | 2.08%   |
| Intel               | 27        | 36     | 1.76%   |
| Toshiba             | 25        | 34     | 1.63%   |
| Micron Technology   | 25        | 29     | 1.63%   |
| Apple               | 24        | 27     | 1.56%   |
| SPCC                | 21        | 25     | 1.37%   |
| JMicron Technology  | 18        | 18     | 1.17%   |
| Patriot             | 14        | 24     | 0.91%   |
| LITEON              | 14        | 19     | 0.91%   |
| Transcend           | 13        | 17     | 0.85%   |
| OCZ                 | 12        | 15     | 0.78%   |
| LITEONIT            | 11        | 11     | 0.72%   |
| Plextor             | 10        | 11     | 0.65%   |
| Intenso             | 10        | 17     | 0.65%   |
| Hewlett-Packard     | 10        | 14     | 0.65%   |
| Team                | 9         | 10     | 0.59%   |
| Lexar               | 8         | 8      | 0.52%   |
| Corsair             | 8         | 18     | 0.52%   |
| Gigabyte Technology | 7         | 8      | 0.46%   |
| Seagate             | 6         | 9      | 0.39%   |
| KingSpec            | 6         | 6      | 0.39%   |
| GOODRAM             | 6         | 10     | 0.39%   |
| Mushkin             | 5         | 8      | 0.33%   |
| Apacer              | 5         | 5      | 0.33%   |
| Verbatim            | 4         | 5      | 0.26%   |
| HS-SSD-C100         | 4         | 5      | 0.26%   |
| Acer                | 4         | 4      | 0.26%   |
| Unknown             | 4         | 4      | 0.26%   |
| XrayDisk            | 3         | 4      | 0.2%    |
| Unknown             | 3         | 3      | 0.2%    |
| T-FORCE             | 3         | 3      | 0.2%    |
| Leven               | 3         | 3      | 0.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 1245      | 2219   | 34.07%  |
| NVMe    | 1159      | 1885   | 31.72%  |
| HDD     | 1152      | 2150   | 31.53%  |
| MMC     | 61        | 84     | 1.67%   |
| Unknown | 37        | 52     | 1.01%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1783      | 4082   | 55.2%   |
| NVMe | 1155      | 1861   | 35.76%  |
| SAS  | 231       | 363    | 7.15%   |
| MMC  | 61        | 84     | 1.89%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1260      | 2213   | 48.59%  |
| 0.51-1.0   | 873       | 1342   | 33.67%  |
| 1.01-2.0   | 279       | 493    | 10.76%  |
| 3.01-4.0   | 79        | 130    | 3.05%   |
| 4.01-10.0  | 51        | 109    | 1.97%   |
| 2.01-3.0   | 45        | 72     | 1.74%   |
| 10.01-20.0 | 6         | 10     | 0.23%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 535       | 20.41%  |
| 251-500        | 530       | 20.22%  |
| 501-1000       | 416       | 15.87%  |
| More than 3000 | 329       | 12.55%  |
| 1001-2000      | 322       | 12.29%  |
| 2001-3000      | 117       | 4.46%   |
| Unknown        | 114       | 4.35%   |
| 1-20           | 111       | 4.24%   |
| 51-100         | 103       | 3.93%   |
| 21-50          | 44        | 1.68%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 697       | 25.34%  |
| 21-50          | 489       | 17.78%  |
| 101-250        | 411       | 14.94%  |
| 51-100         | 302       | 10.98%  |
| 251-500        | 263       | 9.56%   |
| 501-1000       | 218       | 7.92%   |
| 1001-2000      | 130       | 4.73%   |
| Unknown        | 114       | 4.14%   |
| More than 3000 | 75        | 2.73%   |
| 2001-3000      | 50        | 1.82%   |
| 0              | 2         | 0.07%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                                           | Computers | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                                          | 12        | 16     | 2.3%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                              | 12        | 12     | 2.3%    |
| Seagate ST1000LM035-1RK172 1TB                                  | 9         | 10     | 1.73%   |
| Samsung Electronics SSD 870 EVO 1TB                             | 8         | 12     | 1.54%   |
| Toshiba MQ01ABF050 500GB                                        | 7         | 9      | 1.34%   |
| Seagate ST9320325AS 320GB                                       | 6         | 8      | 1.15%   |
| Seagate ST500LT012-1DG142 500GB                                 | 6         | 7      | 1.15%   |
| Seagate ST3500413AS 500GB                                       | 6         | 7      | 1.15%   |
| Seagate ST1000DM003-1CH162 1TB                                  | 6         | 8      | 1.15%   |
| Seagate ST31000528AS 1TB                                        | 5         | 5      | 0.96%   |
| Seagate ST1000DM003-9YN162 1TB                                  | 5         | 5      | 0.96%   |
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 250GB | 5         | 6      | 0.96%   |
| Hitachi HTS547575A9E384 752GB                                   | 5         | 5      | 0.96%   |
| HGST HTS721010A9E630 1TB                                        | 5         | 6      | 0.96%   |
| WDC WD20EARS-00MVWB0 2TB                                        | 4         | 9      | 0.77%   |
| Seagate ST9500325AS 500GB                                       | 4         | 6      | 0.77%   |
| Seagate ST3500312CS 500GB                                       | 4         | 6      | 0.77%   |
| Seagate ST2000DM001-1ER164 2TB                                  | 4         | 10     | 0.77%   |
| SanDisk SSD PLUS 1000GB                                         | 4         | 5      | 0.77%   |
| Hitachi HDS721010CLA332 1TB                                     | 4         | 6      | 0.77%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                                | 3         | 3      | 0.58%   |
| Toshiba DT01ACA100 1TB                                          | 3         | 5      | 0.58%   |
| SK hynix PC711 HFS512GDE9X073N 512GB                            | 3         | 3      | 0.58%   |
| Seagate ST500LM021-1KJ152 500GB                                 | 3         | 3      | 0.58%   |
| Seagate ST500DM002-1BD142 500GB                                 | 3         | 3      | 0.58%   |
| Seagate ST31000524AS 1TB                                        | 3         | 3      | 0.58%   |
| Seagate ST2000DM008-2FR102 2TB                                  | 3         | 6      | 0.58%   |
| Seagate ST1000LM014-1EJ164 1TB                                  | 3         | 3      | 0.58%   |
| Seagate ST1000DM010-2EP102 1TB                                  | 3         | 4      | 0.58%   |
| Samsung Electronics SSD 850 EVO 250GB                           | 3         | 4      | 0.58%   |
| Maxtor STM3250310AS 250GB                                       | 3         | 5      | 0.58%   |
| Hitachi HDS721050CLA662 500GB                                   | 3         | 4      | 0.58%   |
| HGST HTS725050A7E630 500GB                                      | 3         | 4      | 0.58%   |
| HGST HTS541010A9E680 1TB                                        | 3         | 4      | 0.58%   |
| Apple HDD HTS545050A7E362 500GB                                 | 3         | 3      | 0.58%   |
| WDC WDS500G1X0E-00AFY0 500GB                                    | 2         | 2      | 0.38%   |
| WDC WD6400AAKS-22A7B2 640GB                                     | 2         | 4      | 0.38%   |
| WDC WD5000AAKX-75U6AA0 500GB                                    | 2         | 3      | 0.38%   |
| WDC WD5000AAKX-603CA0 500GB                                     | 2         | 6      | 0.38%   |
| WDC WD5000AAKX-00ERMA0 500GB                                    | 2         | 2      | 0.38%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 131       | 169    | 26.36%  |
| WDC                         | 113       | 180    | 22.74%  |
| Samsung Electronics         | 43        | 61     | 8.65%   |
| Toshiba                     | 39        | 51     | 7.85%   |
| Hitachi                     | 31        | 38     | 6.24%   |
| HGST                        | 20        | 32     | 4.02%   |
| SanDisk                     | 13        | 15     | 2.62%   |
| Intel                       | 13        | 20     | 2.62%   |
| Kingston                    | 11        | 16     | 2.21%   |
| SK hynix                    | 9         | 10     | 1.81%   |
| Crucial                     | 9         | 10     | 1.81%   |
| Micron Technology           | 5         | 8      | 1.01%   |
| Maxtor                      | 5         | 8      | 1.01%   |
| A-DATA Technology           | 5         | 8      | 1.01%   |
| Hewlett-Packard             | 4         | 4      | 0.8%    |
| Corsair                     | 4         | 14     | 0.8%    |
| Transcend                   | 3         | 3      | 0.6%    |
| China                       | 3         | 4      | 0.6%    |
| Apple                       | 3         | 3      | 0.6%    |
| Realtek Semiconductor       | 2         | 2      | 0.4%    |
| Micron/Crucial Technology   | 2         | 4      | 0.4%    |
| LITEONIT                    | 2         | 2      | 0.4%    |
| Drevo                       | 2         | 2      | 0.4%    |
| Colorful                    | 2         | 3      | 0.4%    |
| ASMedia                     | 2         | 3      | 0.4%    |
| Unknown                     | 2         | 2      | 0.4%    |
| XPG                         | 1         | 1      | 0.2%    |
| USB3.0                      | 1         | 2      | 0.2%    |
| Team                        | 1         | 1      | 0.2%    |
| Super Talent                | 1         | 1      | 0.2%    |
| SSSTC                       | 1         | 1      | 0.2%    |
| SPCC                        | 1         | 1      | 0.2%    |
| Silicon Motion              | 1         | 1      | 0.2%    |
| Ramsta                      | 1         | 1      | 0.2%    |
| Plextor                     | 1         | 1      | 0.2%    |
| Patriot                     | 1         | 1      | 0.2%    |
| Mushkin                     | 1         | 1      | 0.2%    |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.2%    |
| Lenovo                      | 1         | 1      | 0.2%    |
| LaCie                       | 1         | 1      | 0.2%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 131       | 169    | 36.59%  |
| WDC                 | 108       | 172    | 30.17%  |
| Toshiba             | 36        | 47     | 10.06%  |
| Hitachi             | 31        | 38     | 8.66%   |
| HGST                | 20        | 32     | 5.59%   |
| Samsung Electronics | 14        | 18     | 3.91%   |
| Maxtor              | 5         | 8      | 1.4%    |
| Apple               | 3         | 3      | 0.84%   |
| Hewlett-Packard     | 2         | 2      | 0.56%   |
| ASMedia             | 2         | 3      | 0.56%   |
| USB3.0              | 1         | 2      | 0.28%   |
| LaCie               | 1         | 1      | 0.28%   |
| Inateck             | 1         | 1      | 0.28%   |
| HGST HTS            | 1         | 1      | 0.28%   |
| Fujitsu             | 1         | 1      | 0.28%   |
| Unknown             | 1         | 1      | 0.28%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 330       | 499    | 70.51%  |
| SSD  | 106       | 150    | 22.65%  |
| NVMe | 32        | 43     | 6.84%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 980 1TB                  | 2         | 2      | 16.67%  |
| WDC WD5000AAKX-001CA0 500GB                      | 1         | 1      | 8.33%   |
| WDC WD10SPZX-21Z10T0 1TB                         | 1         | 1      | 8.33%   |
| Seagate ST9320325AS 320GB                        | 1         | 1      | 8.33%   |
| Seagate ST32000641AS 2TB                         | 1         | 2      | 8.33%   |
| Seagate ST2000DL001-9VT156 2TB                   | 1         | 1      | 8.33%   |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 1         | 1      | 8.33%   |
| Samsung Electronics SSD 980 500GB                | 1         | 1      | 8.33%   |
| Samsung Electronics MZ7TY128HDHP-000L1 128GB SSD | 1         | 1      | 8.33%   |
| HGST HTS721010A9E630 1TB                         | 1         | 1      | 8.33%   |
| HGST HTS545050A7E680 500GB                       | 1         | 1      | 8.33%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 5      | 33.33%  |
| Samsung Electronics | 4         | 4      | 33.33%  |
| WDC                 | 2         | 2      | 16.67%  |
| HGST                | 2         | 2      | 16.67%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 2045      | 4850   | 69.18%  |
| Malfunc  | 452       | 692    | 15.29%  |
| Detected | 447       | 835    | 15.12%  |
| Failed   | 12        | 13     | 0.41%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1504      | 42.51%  |
| AMD                              | 636       | 17.98%  |
| Samsung Electronics              | 443       | 12.52%  |
| SanDisk                          | 195       | 5.51%   |
| Phison Electronics               | 107       | 3.02%   |
| Kingston Technology Company      | 87        | 2.46%   |
| SK hynix                         | 82        | 2.32%   |
| Micron/Crucial Technology        | 63        | 1.78%   |
| ASMedia Technology               | 63        | 1.78%   |
| Silicon Motion                   | 45        | 1.27%   |
| Micron Technology                | 40        | 1.13%   |
| Toshiba America Info Systems     | 38        | 1.07%   |
| KIOXIA                           | 38        | 1.07%   |
| Marvell Technology Group         | 36        | 1.02%   |
| ADATA Technology                 | 35        | 0.99%   |
| Realtek Semiconductor            | 23        | 0.65%   |
| Nvidia                           | 16        | 0.45%   |
| Seagate Technology               | 11        | 0.31%   |
| JMicron Technology               | 11        | 0.31%   |
| MAXIO Technology (Hangzhou)      | 10        | 0.28%   |
| Union Memory (Shenzhen)          | 9         | 0.25%   |
| Lite-On Technology               | 7         | 0.2%    |
| INNOGRIT                         | 5         | 0.14%   |
| Shenzhen Longsys Electronics     | 4         | 0.11%   |
| Apple                            | 4         | 0.11%   |
| Solid State Storage Technology   | 3         | 0.08%   |
| LSI Logic / Symbios Logic        | 3         | 0.08%   |
| Lenovo                           | 3         | 0.08%   |
| VIA Technologies                 | 2         | 0.06%   |
| Silicon Image                    | 2         | 0.06%   |
| Netac Technology                 | 2         | 0.06%   |
| Broadcom / LSI                   | 2         | 0.06%   |
| Biwin Storage Technology         | 2         | 0.06%   |
| Adaptec                          | 2         | 0.06%   |
| Yangtze Memory Technologies      | 1         | 0.03%   |
| TenaFe                           | 1         | 0.03%   |
| Silicon Integrated Systems [SiS] | 1         | 0.03%   |
| Hewlett-Packard                  | 1         | 0.03%   |
| Beijing Starblaze Technology     | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 460       | 11.7%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 230       | 5.85%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 136       | 3.46%   |
| AMD 400 Series Chipset SATA Controller                                         | 135       | 3.43%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 110       | 2.8%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 99        | 2.52%   |
| AMD 500 Series Chipset SATA Controller                                         | 86        | 2.19%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 79        | 2.01%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 78        | 1.98%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 76        | 1.93%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 75        | 1.91%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 75        | 1.91%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 68        | 1.73%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 61        | 1.55%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 59        | 1.5%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 58        | 1.48%   |
| Phison E12 NVMe Controller                                                     | 51        | 1.3%    |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 50        | 1.27%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 50        | 1.27%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 49        | 1.25%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 45        | 1.14%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 45        | 1.14%   |
| Intel Volume Management Device NVMe RAID Controller                            | 44        | 1.12%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 41        | 1.04%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 40        | 1.02%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 38        | 0.97%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 37        | 0.94%   |
| Intel SATA Controller [RAID mode]                                              | 36        | 0.92%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 36        | 0.92%   |
| Phison E16 PCIe4 NVMe Controller                                               | 34        | 0.86%   |
| Intel SSD 660P Series                                                          | 34        | 0.86%   |
| Intel Comet Lake SATA AHCI Controller                                          | 34        | 0.86%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 33        | 0.84%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 32        | 0.81%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 30        | 0.76%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 29        | 0.74%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 27        | 0.69%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 26        | 0.66%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 26        | 0.66%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                       | 25        | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1896      | 55.98%  |
| NVMe | 1156      | 34.13%  |
| RAID | 204       | 6.02%   |
| IDE  | 124       | 3.66%   |
| SAS  | 5         | 0.15%   |
| SCSI | 2         | 0.06%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 1680      | 69.11%  |
| AMD     | 750       | 30.85%  |
| Unknown | 1         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor             | 44        | 1.81%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 33        | 1.35%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 30        | 1.23%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 29        | 1.19%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 29        | 1.19%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 28        | 1.15%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 27        | 1.11%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 26        | 1.07%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 25        | 1.03%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 24        | 0.98%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 23        | 0.94%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 23        | 0.94%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 22        | 0.9%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 21        | 0.86%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 21        | 0.86%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 21        | 0.86%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 19        | 0.78%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 19        | 0.78%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 19        | 0.78%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 18        | 0.74%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 18        | 0.74%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 17        | 0.7%    |
| AMD Ryzen 5 2600 Six-Core Processor           | 17        | 0.7%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 16        | 0.66%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 16        | 0.66%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 16        | 0.66%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 15        | 0.62%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 15        | 0.62%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 15        | 0.62%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 14        | 0.57%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 14        | 0.57%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 13        | 0.53%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 13        | 0.53%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 13        | 0.53%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 13        | 0.53%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 13        | 0.53%   |
| AMD Ryzen 5 3600X 6-Core Processor            | 13        | 0.53%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 13        | 0.53%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 12        | 0.49%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 12        | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 573       | 23.52%  |
| Intel Core i7           | 542       | 22.25%  |
| AMD Ryzen 5             | 243       | 9.98%   |
| AMD Ryzen 7             | 209       | 8.58%   |
| Other                   | 160       | 6.57%   |
| Intel Core i3           | 136       | 5.58%   |
| AMD Ryzen 9             | 101       | 4.15%   |
| Intel Celeron           | 55        | 2.26%   |
| Intel Xeon              | 54        | 2.22%   |
| Intel Pentium           | 51        | 2.09%   |
| AMD Ryzen 3             | 47        | 1.93%   |
| Intel Core 2 Duo        | 31        | 1.27%   |
| Intel Core i9           | 28        | 1.15%   |
| Intel Atom              | 25        | 1.03%   |
| AMD FX                  | 25        | 1.03%   |
| AMD A6                  | 17        | 0.7%    |
| AMD A10                 | 13        | 0.53%   |
| AMD Ryzen 7 PRO         | 10        | 0.41%   |
| AMD A8                  | 9         | 0.37%   |
| Intel Pentium Dual-Core | 8         | 0.33%   |
| AMD Ryzen Threadripper  | 8         | 0.33%   |
| AMD Phenom II X4        | 7         | 0.29%   |
| AMD A4                  | 7         | 0.29%   |
| AMD A12                 | 6         | 0.25%   |
| Intel Pentium Silver    | 5         | 0.21%   |
| Intel Pentium Dual      | 5         | 0.21%   |
| Intel Core 2 Quad       | 5         | 0.21%   |
| AMD Ryzen 5 PRO         | 5         | 0.21%   |
| AMD E2                  | 5         | 0.21%   |
| AMD E1                  | 5         | 0.21%   |
| Intel Core 2            | 4         | 0.16%   |
| AMD Athlon 64 X2        | 4         | 0.16%   |
| AMD Athlon              | 4         | 0.16%   |
| Intel Xeon Silver       | 3         | 0.12%   |
| Intel Core m3           | 3         | 0.12%   |
| AMD Phenom II X6        | 3         | 0.12%   |
| AMD Athlon II X2        | 3         | 0.12%   |
| Intel Pentium Gold      | 2         | 0.08%   |
| Intel Genuine           | 2         | 0.08%   |
| Intel Pentium 4         | 1         | 0.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 854       | 35.04%  |
| 2       | 691       | 28.35%  |
| 6       | 398       | 16.33%  |
| 8       | 308       | 12.64%  |
| 12      | 75        | 3.08%   |
| 16      | 36        | 1.48%   |
| 10      | 22        | 0.9%    |
| 14      | 16        | 0.66%   |
| 1       | 15        | 0.62%   |
| 3       | 12        | 0.49%   |
| 24      | 5         | 0.21%   |
| 18      | 2         | 0.08%   |
| 40      | 1         | 0.04%   |
| 32      | 1         | 0.04%   |
| Unknown | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2426      | 99.75%  |
| 2       | 5         | 0.21%   |
| Unknown | 1         | 0.04%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1933      | 79.45%  |
| 1       | 499       | 20.51%  |
| Unknown | 1         | 0.04%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2424      | 99.71%  |
| Unknown        | 7         | 0.29%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 755       | 29.69%  |
| 0x306c3    | 96        | 3.78%   |
| 0x906ea    | 91        | 3.58%   |
| 0x306a9    | 90        | 3.54%   |
| 0x08701021 | 84        | 3.3%    |
| 0x206a7    | 82        | 3.22%   |
| 0x906e9    | 65        | 2.56%   |
| 0x806ea    | 53        | 2.08%   |
| 0x806e9    | 51        | 2.01%   |
| 0x0a50000c | 50        | 1.97%   |
| 0x506e3    | 48        | 1.89%   |
| 0x0800820d | 48        | 1.89%   |
| 0x406e3    | 43        | 1.69%   |
| 0x08108109 | 40        | 1.57%   |
| 0x0a201016 | 39        | 1.53%   |
| 0x806c1    | 37        | 1.45%   |
| 0x08600106 | 36        | 1.42%   |
| 0x806ec    | 35        | 1.38%   |
| 0x40651    | 34        | 1.34%   |
| 0x306d4    | 29        | 1.14%   |
| 0x08108102 | 27        | 1.06%   |
| 0x08701013 | 26        | 1.02%   |
| 0xa0652    | 25        | 0.98%   |
| 0x20655    | 24        | 0.94%   |
| 0x08608103 | 24        | 0.94%   |
| 0x0a50000d | 23        | 0.9%    |
| 0x1067a    | 22        | 0.87%   |
| 0x0a201009 | 22        | 0.87%   |
| 0x0a20120a | 19        | 0.75%   |
| 0x706e5    | 16        | 0.63%   |
| 0xa0655    | 15        | 0.59%   |
| 0x08600104 | 15        | 0.59%   |
| 0x0810100b | 14        | 0.55%   |
| 0x806d1    | 13        | 0.51%   |
| 0x0a601203 | 13        | 0.51%   |
| 0x08101016 | 13        | 0.51%   |
| 0x06006705 | 13        | 0.51%   |
| 0xa0653    | 12        | 0.47%   |
| 0x806eb    | 12        | 0.47%   |
| 0x106e5    | 12        | 0.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 508       | 20.84%  |
| Haswell          | 221       | 9.06%   |
| Zen 2            | 195       | 8%      |
| Zen 3            | 184       | 7.55%   |
| IvyBridge        | 160       | 6.56%   |
| Skylake          | 147       | 6.03%   |
| Zen+             | 129       | 5.29%   |
| SandyBridge      | 125       | 5.13%   |
| CometLake        | 84        | 3.45%   |
| Unknown          | 71        | 2.91%   |
| TigerLake        | 59        | 2.42%   |
| Alderlake Hybrid | 57        | 2.34%   |
| Zen              | 55        | 2.26%   |
| Broadwell        | 52        | 2.13%   |
| Westmere         | 48        | 1.97%   |
| IceLake          | 48        | 1.97%   |
| Penryn           | 40        | 1.64%   |
| Silvermont       | 38        | 1.56%   |
| Excavator        | 35        | 1.44%   |
| Piledriver       | 33        | 1.35%   |
| Goldmont plus    | 24        | 0.98%   |
| Goldmont         | 19        | 0.78%   |
| Nehalem          | 18        | 0.74%   |
| K10              | 18        | 0.74%   |
| Core             | 17        | 0.7%    |
| Steamroller      | 10        | 0.41%   |
| Puma             | 7         | 0.29%   |
| K8 Hammer        | 6         | 0.25%   |
| Jaguar           | 6         | 0.25%   |
| Tremont          | 5         | 0.21%   |
| Bobcat           | 5         | 0.21%   |
| K10 Llano        | 3         | 0.12%   |
| Bulldozer        | 3         | 0.12%   |
| Bonnell          | 3         | 0.12%   |
| Gracemont        | 2         | 0.08%   |
| NetBurst         | 1         | 0.04%   |
| K8 & K10 hybrid  | 1         | 0.04%   |
| CannonLake       | 1         | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 1284      | 42.99%  |
| Nvidia                     | 972       | 32.54%  |
| AMD                        | 712       | 23.84%  |
| ASPEED Technology          | 16        | 0.54%   |
| Matrox Electronics Systems | 2         | 0.07%   |
| ATI Technologies           | 1         | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 96        | 3.14%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 87        | 2.84%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 76        | 2.48%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 75        | 2.45%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 73        | 2.38%   |
| Intel UHD Graphics 620                                                                   | 71        | 2.32%   |
| Intel HD Graphics 620                                                                    | 70        | 2.29%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 67        | 2.19%   |
| Intel HD Graphics 630                                                                    | 59        | 1.93%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 59        | 1.93%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 57        | 1.86%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 54        | 1.76%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 52        | 1.7%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 50        | 1.63%   |
| Intel HD Graphics 530                                                                    | 48        | 1.57%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 44        | 1.44%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 42        | 1.37%   |
| Intel HD Graphics 5500                                                                   | 40        | 1.31%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 37        | 1.21%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 37        | 1.21%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 36        | 1.18%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 35        | 1.14%   |
| Intel Core Processor Integrated Graphics Controller                                      | 34        | 1.11%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 33        | 1.08%   |
| AMD Lucienne                                                                             | 31        | 1.01%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 30        | 0.98%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 28        | 0.91%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 28        | 0.91%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 27        | 0.88%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 22        | 0.72%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 22        | 0.72%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 21        | 0.69%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 21        | 0.69%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 21        | 0.69%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 19        | 0.62%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 19        | 0.62%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 19        | 0.62%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 19        | 0.62%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 19        | 0.62%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 18        | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 794       | 32.36%  |
| 1 x AMD        | 551       | 22.45%  |
| 1 x Nvidia     | 505       | 20.58%  |
| Intel + Nvidia | 401       | 16.34%  |
| AMD + Nvidia   | 64        | 2.61%   |
| Intel + AMD    | 54        | 2.2%    |
| 2 x AMD        | 45        | 1.83%   |
| 1 x ASPEED     | 14        | 0.57%   |
| 2 x Intel      | 13        | 0.53%   |
| 2 x Nvidia     | 6         | 0.24%   |
| Other          | 3         | 0.12%   |
| 1 x Matrox     | 2         | 0.08%   |
| AMD + ASPEED   | 2         | 0.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1730      | 70.1%   |
| Proprietary | 685       | 27.76%  |
| Unknown     | 53        | 2.15%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1255      | 50.24%  |
| 7.01-8.0   | 234       | 9.37%   |
| 1.01-2.0   | 233       | 9.33%   |
| 0.01-0.5   | 217       | 8.69%   |
| 3.01-4.0   | 188       | 7.53%   |
| 5.01-6.0   | 112       | 4.48%   |
| 0.51-1.0   | 108       | 4.32%   |
| 8.01-16.0  | 106       | 4.24%   |
| 2.01-3.0   | 28        | 1.12%   |
| 16.01-24.0 | 14        | 0.56%   |
| 4.01-5.0   | 3         | 0.12%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 327       | 11.33%  |
| AU Optronics            | 282       | 9.77%   |
| LG Display              | 249       | 8.62%   |
| BOE                     | 235       | 8.14%   |
| Chimei Innolux          | 220       | 7.62%   |
| Dell                    | 201       | 6.96%   |
| Goldstar                | 197       | 6.82%   |
| Acer                    | 108       | 3.74%   |
| AOC                     | 92        | 3.19%   |
| Hewlett-Packard         | 87        | 3.01%   |
| Ancor Communications    | 83        | 2.87%   |
| BenQ                    | 80        | 2.77%   |
| Sharp                   | 54        | 1.87%   |
| Philips                 | 50        | 1.73%   |
| Apple                   | 48        | 1.66%   |
| Lenovo                  | 43        | 1.49%   |
| ASUSTek Computer        | 42        | 1.45%   |
| ViewSonic               | 33        | 1.14%   |
| PANDA                   | 31        | 1.07%   |
| Sony                    | 28        | 0.97%   |
| Unknown                 | 26        | 0.9%    |
| Iiyama                  | 25        | 0.87%   |
| MSI                     | 24        | 0.83%   |
| Chi Mei Optoelectronics | 20        | 0.69%   |
| CSO                     | 19        | 0.66%   |
| Eizo                    | 16        | 0.55%   |
| Sceptre Tech            | 14        | 0.48%   |
| Vizio                   | 13        | 0.45%   |
| LG Electronics          | 13        | 0.45%   |
| InfoVision              | 13        | 0.45%   |
| Gigabyte Technology     | 13        | 0.45%   |
| Toshiba                 | 10        | 0.35%   |
| Panasonic               | 10        | 0.35%   |
| HannStar                | 9         | 0.31%   |
| Unknown                 | 9         | 0.31%   |
| Vestel Elektronik       | 6         | 0.21%   |
| MStar                   | 5         | 0.17%   |
| VIE                     | 4         | 0.14%   |
| MiTAC                   | 4         | 0.14%   |
| Microstep               | 4         | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 16        | 0.53%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 15        | 0.5%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 14        | 0.46%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 13        | 0.43%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch              | 12        | 0.4%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 10        | 0.33%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 10        | 0.33%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 10        | 0.33%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 9         | 0.3%    |
| Dell SE2416H DELD081 1920x1080 527x296mm 23.8-inch                    | 9         | 0.3%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 9         | 0.3%    |
| Unknown                                                               | 9         | 0.3%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch  | 8         | 0.27%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 8         | 0.27%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 8         | 0.27%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 8         | 0.27%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch          | 8         | 0.27%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch      | 8         | 0.27%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 8         | 0.27%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 8         | 0.27%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 8         | 0.27%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch         | 8         | 0.27%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 8         | 0.27%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch          | 7         | 0.23%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 7         | 0.23%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 7         | 0.23%   |
| BOE LCD Monitor BOE0747 1920x1080 345x195mm 15.6-inch                 | 7         | 0.23%   |
| AOC 24G2W1G4 AOC2402 1920x1080 527x296mm 23.8-inch                    | 7         | 0.23%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch | 7         | 0.23%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 706x398mm 31.9-inch    | 6         | 0.2%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 6         | 0.2%    |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 6         | 0.2%    |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch            | 6         | 0.2%    |
| Goldstar LG TV SSCR2 GSMC0C8 3840x2160                                | 6         | 0.2%    |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch       | 6         | 0.2%    |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 6         | 0.2%    |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 6         | 0.2%    |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                  | 6         | 0.2%    |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch         | 6         | 0.2%    |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 6         | 0.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1334      | 48.95%  |
| 1366x768 (WXGA)    | 369       | 13.54%  |
| 2560x1440 (QHD)    | 231       | 8.48%   |
| 3840x2160 (4K)     | 202       | 7.41%   |
| 1600x900 (HD+)     | 79        | 2.9%    |
| 2560x1080          | 54        | 1.98%   |
| 1920x1200 (WUXGA)  | 52        | 1.91%   |
| 1680x1050 (WSXGA+) | 47        | 1.72%   |
| 1440x900 (WXGA+)   | 47        | 1.72%   |
| 3440x1440          | 37        | 1.36%   |
| 1280x1024 (SXGA)   | 37        | 1.36%   |
| 1280x800 (WXGA)    | 29        | 1.06%   |
| Unknown            | 24        | 0.88%   |
| 2560x1600          | 23        | 0.84%   |
| 3840x1080          | 21        | 0.77%   |
| 2880x1800          | 20        | 0.73%   |
| 2288x1287          | 17        | 0.62%   |
| 1360x768           | 17        | 0.62%   |
| 2160x1440          | 11        | 0.4%    |
| 1920x540           | 11        | 0.4%    |
| 3840x2400          | 7         | 0.26%   |
| 1600x1200          | 7         | 0.26%   |
| 3200x1800 (QHD+)   | 6         | 0.22%   |
| 3840x1600          | 5         | 0.18%   |
| 2944x1080          | 2         | 0.07%   |
| 2160x1350          | 2         | 0.07%   |
| 2048x1152          | 2         | 0.07%   |
| 1024x768 (XGA)     | 2         | 0.07%   |
| 1024x600           | 2         | 0.07%   |
| 7280x1440          | 1         | 0.04%   |
| 6400x1440          | 1         | 0.04%   |
| 5760x2160          | 1         | 0.04%   |
| 5520x1080          | 1         | 0.04%   |
| 5360x1440          | 1         | 0.04%   |
| 5120x1440          | 1         | 0.04%   |
| 480x1920           | 1         | 0.04%   |
| 4480x1440          | 1         | 0.04%   |
| 4480x1080          | 1         | 0.04%   |
| 4096x2160          | 1         | 0.04%   |
| 3840x2524          | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 678       | 23.54%  |
| 27      | 291       | 10.1%   |
| 24      | 260       | 9.03%   |
| 14      | 204       | 7.08%   |
| 13      | 196       | 6.81%   |
| 23      | 179       | 6.22%   |
| 21      | 171       | 5.94%   |
| 17      | 140       | 4.86%   |
| 31      | 112       | 3.89%   |
| Unknown | 92        | 3.19%   |
| 34      | 75        | 2.6%    |
| 19      | 51        | 1.77%   |
| 12      | 48        | 1.67%   |
| 18      | 42        | 1.46%   |
| 22      | 35        | 1.22%   |
| 40      | 27        | 0.94%   |
| 20      | 26        | 0.9%    |
| 84      | 24        | 0.83%   |
| 32      | 22        | 0.76%   |
| 16      | 22        | 0.76%   |
| 72      | 21        | 0.73%   |
| 54      | 21        | 0.73%   |
| 142     | 16        | 0.56%   |
| 25      | 13        | 0.45%   |
| 28      | 12        | 0.42%   |
| 11      | 12        | 0.42%   |
| 49      | 8         | 0.28%   |
| 48      | 8         | 0.28%   |
| 26      | 8         | 0.28%   |
| 52      | 7         | 0.24%   |
| 42      | 7         | 0.24%   |
| 29      | 6         | 0.21%   |
| 10      | 6         | 0.21%   |
| 65      | 5         | 0.17%   |
| 39      | 5         | 0.17%   |
| 37      | 4         | 0.14%   |
| 74      | 3         | 0.1%    |
| 46      | 3         | 0.1%    |
| 35      | 3         | 0.1%    |
| 86      | 2         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 997       | 35.48%  |
| 501-600        | 665       | 23.67%  |
| 401-500        | 298       | 10.6%   |
| 201-300        | 172       | 6.12%   |
| 601-700        | 160       | 5.69%   |
| 351-400        | 151       | 5.37%   |
| 701-800        | 100       | 3.56%   |
| Unknown        | 92        | 3.27%   |
| 1001-1500      | 58        | 2.06%   |
| 1501-2000      | 49        | 1.74%   |
| 801-900        | 41        | 1.46%   |
| More than 2000 | 16        | 0.57%   |
| 901-1000       | 11        | 0.39%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2009      | 79.31%  |
| 16/10   | 242       | 9.55%   |
| 21/9    | 94        | 3.71%   |
| Unknown | 73        | 2.88%   |
| 5/4     | 35        | 1.38%   |
| 3/2     | 25        | 0.99%   |
| 1.00    | 16        | 0.63%   |
| 4/3     | 15        | 0.59%   |
| 32/9    | 13        | 0.51%   |
| 6/5     | 5         | 0.2%    |
| 0.56    | 2         | 0.08%   |
| 3.40    | 1         | 0.04%   |
| 2.00    | 1         | 0.04%   |
| 0.80    | 1         | 0.04%   |
| 0.25    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 669       | 23.57%  |
| 201-250        | 526       | 18.53%  |
| 81-90          | 321       | 11.31%  |
| 301-350        | 296       | 10.43%  |
| 351-500        | 219       | 7.72%   |
| 121-130        | 114       | 4.02%   |
| 151-200        | 113       | 3.98%   |
| More than 1000 | 102       | 3.59%   |
| Unknown        | 92        | 3.24%   |
| 251-300        | 88        | 3.1%    |
| 71-80          | 77        | 2.71%   |
| 501-1000       | 62        | 2.18%   |
| 141-150        | 56        | 1.97%   |
| 61-70          | 44        | 1.55%   |
| 111-120        | 19        | 0.67%   |
| 51-60          | 14        | 0.49%   |
| 91-100         | 11        | 0.39%   |
| 131-140        | 10        | 0.35%   |
| 41-50          | 5         | 0.18%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 895       | 32.92%  |
| 121-160       | 789       | 29.02%  |
| 101-120       | 646       | 23.76%  |
| 161-240       | 157       | 5.77%   |
| Unknown       | 92        | 3.38%   |
| 1-50          | 82        | 3.02%   |
| More than 240 | 58        | 2.13%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1828      | 73.12%  |
| 2     | 534       | 21.36%  |
| 3     | 68        | 2.72%   |
| 0     | 66        | 2.64%   |
| 4     | 4         | 0.16%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1376      | 38.12%  |
| Intel                             | 1363      | 37.76%  |
| Qualcomm Atheros                  | 343       | 9.5%    |
| Broadcom                          | 130       | 3.6%    |
| MediaTek                          | 62        | 1.72%   |
| TP-Link                           | 35        | 0.97%   |
| Ralink Technology                 | 34        | 0.94%   |
| Broadcom Limited                  | 32        | 0.89%   |
| ASIX Electronics                  | 17        | 0.47%   |
| Marvell Technology Group          | 15        | 0.42%   |
| Nvidia                            | 13        | 0.36%   |
| Sierra Wireless                   | 12        | 0.33%   |
| Ralink                            | 12        | 0.33%   |
| Microsoft                         | 12        | 0.33%   |
| Samsung Electronics               | 10        | 0.28%   |
| Aquantia                          | 10        | 0.28%   |
| DisplayLink                       | 9         | 0.25%   |
| Dell                              | 9         | 0.25%   |
| Ericsson Business Mobile Networks | 8         | 0.22%   |
| Qualcomm                          | 7         | 0.19%   |
| NetGear                           | 7         | 0.19%   |
| D-Link System                     | 7         | 0.19%   |
| Xiaomi                            | 6         | 0.17%   |
| Lenovo                            | 6         | 0.17%   |
| Qualcomm Atheros Communications   | 5         | 0.14%   |
| Huawei Technologies               | 5         | 0.14%   |
| JMicron Technology                | 4         | 0.11%   |
| Insyde Software                   | 4         | 0.11%   |
| Hewlett-Packard                   | 4         | 0.11%   |
| Fibocom                           | 4         | 0.11%   |
| D-Link                            | 4         | 0.11%   |
| T & A Mobile Phones               | 3         | 0.08%   |
| Edimax Technology                 | 3         | 0.08%   |
| ASUSTek Computer                  | 3         | 0.08%   |
| Tenda                             | 2         | 0.06%   |
| Oculus VR                         | 2         | 0.06%   |
| Motorola PCS                      | 2         | 0.06%   |
| Microchip Technology              | 2         | 0.06%   |
| InterBiometrics                   | 2         | 0.06%   |
| Emulex                            | 2         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 998       | 23.13%  |
| Intel Wi-Fi 6 AX200                                               | 192       | 4.45%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 114       | 2.64%   |
| Intel I211 Gigabit Network Connection                             | 109       | 2.53%   |
| Intel Wireless 8265 / 8275                                        | 90        | 2.09%   |
| Realtek RTL8125 2.5GbE Controller                                 | 89        | 2.06%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 83        | 1.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 80        | 1.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 67        | 1.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 65        | 1.51%   |
| Intel Wireless 7260                                               | 63        | 1.46%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 62        | 1.44%   |
| Intel Ethernet Connection (2) I219-V                              | 58        | 1.34%   |
| Intel Ethernet Controller I225-V                                  | 54        | 1.25%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 51        | 1.18%   |
| Intel Wireless 7265                                               | 51        | 1.18%   |
| Intel Wireless 8260                                               | 50        | 1.16%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 50        | 1.16%   |
| Intel Ethernet Connection I217-LM                                 | 48        | 1.11%   |
| Intel Wi-Fi 6 AX201                                               | 44        | 1.02%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 44        | 1.02%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 42        | 0.97%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 41        | 0.95%   |
| Intel Wireless-AC 9260                                            | 41        | 0.95%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 40        | 0.93%   |
| Intel Ethernet Connection (7) I219-V                              | 40        | 0.93%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 39        | 0.9%    |
| Intel Wireless 3165                                               | 36        | 0.83%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 29        | 0.67%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 28        | 0.65%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 27        | 0.63%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 26        | 0.6%    |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 24        | 0.56%   |
| Intel Ethernet Connection (2) I219-LM                             | 22        | 0.51%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 21        | 0.49%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 21        | 0.49%   |
| Intel Wireless 3160                                               | 21        | 0.49%   |
| Intel Ethernet Connection I218-LM                                 | 21        | 0.49%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter      | 21        | 0.49%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 20        | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1049      | 53.66%  |
| Realtek Semiconductor                 | 307       | 15.7%   |
| Qualcomm Atheros                      | 270       | 13.81%  |
| Broadcom                              | 94        | 4.81%   |
| MediaTek                              | 59        | 3.02%   |
| Ralink Technology                     | 34        | 1.74%   |
| TP-Link                               | 32        | 1.64%   |
| Broadcom Limited                      | 24        | 1.23%   |
| Sierra Wireless                       | 12        | 0.61%   |
| Ralink                                | 12        | 0.61%   |
| Microsoft                             | 12        | 0.61%   |
| NetGear                               | 7         | 0.36%   |
| Dell                                  | 6         | 0.31%   |
| Qualcomm Atheros Communications       | 5         | 0.26%   |
| Fibocom                               | 4         | 0.2%    |
| D-Link System                         | 4         | 0.2%    |
| D-Link                                | 4         | 0.2%    |
| Marvell Technology Group              | 3         | 0.15%   |
| Edimax Technology                     | 3         | 0.15%   |
| ASUSTek Computer                      | 3         | 0.15%   |
| Tenda                                 | 2         | 0.1%    |
| Hewlett-Packard                       | 2         | 0.1%    |
| Ericsson Business Mobile Networks     | 2         | 0.1%    |
| Xiaomi                                | 1         | 0.05%   |
| Ovislink                              | 1         | 0.05%   |
| IMC Networks                          | 1         | 0.05%   |
| CyberTAN Technology                   | 1         | 0.05%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 192       | 9.77%   |
| Intel Wireless 8265 / 8275                                           | 90        | 4.58%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 80        | 4.07%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 67        | 3.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 65        | 3.31%   |
| Intel Wireless 7260                                                  | 63        | 3.21%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 51        | 2.6%    |
| Intel Wireless 7265                                                  | 51        | 2.6%    |
| Intel Wireless 8260                                                  | 50        | 2.54%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 50        | 2.54%   |
| Intel Wi-Fi 6 AX201                                                  | 44        | 2.24%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 44        | 2.24%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 42        | 2.14%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 41        | 2.09%   |
| Intel Wireless-AC 9260                                               | 41        | 2.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 40        | 2.04%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 39        | 1.98%   |
| Intel Wireless 3165                                                  | 36        | 1.83%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 29        | 1.48%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 28        | 1.42%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 27        | 1.37%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 26        | 1.32%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 24        | 1.22%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 21        | 1.07%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 21        | 1.07%   |
| Intel Wireless 3160                                                  | 21        | 1.07%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter         | 21        | 1.07%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 20        | 1.02%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 19        | 0.97%   |
| Ralink MT7601U Wireless Adapter                                      | 18        | 0.92%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 17        | 0.87%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 17        | 0.87%   |
| Intel Centrino Ultimate-N 6300                                       | 16        | 0.81%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 15        | 0.76%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 15        | 0.76%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 15        | 0.76%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                              | 15        | 0.76%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 15        | 0.76%   |
| Intel Centrino Advanced-N 6200                                       | 15        | 0.76%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 14        | 0.71%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1263      | 55.98%  |
| Intel                                  | 703       | 31.16%  |
| Qualcomm Atheros                       | 101       | 4.48%   |
| Broadcom                               | 58        | 2.57%   |
| ASIX Electronics                       | 17        | 0.75%   |
| Nvidia                                 | 13        | 0.58%   |
| Marvell Technology Group               | 12        | 0.53%   |
| Aquantia                               | 10        | 0.44%   |
| DisplayLink                            | 9         | 0.4%    |
| Broadcom Limited                       | 8         | 0.35%   |
| Qualcomm                               | 7         | 0.31%   |
| Samsung Electronics                    | 6         | 0.27%   |
| Xiaomi                                 | 5         | 0.22%   |
| Lenovo                                 | 5         | 0.22%   |
| JMicron Technology                     | 4         | 0.18%   |
| Insyde Software                        | 4         | 0.18%   |
| TP-Link                                | 3         | 0.13%   |
| T & A Mobile Phones                    | 3         | 0.13%   |
| MediaTek                               | 3         | 0.13%   |
| Huawei Technologies                    | 3         | 0.13%   |
| D-Link System                          | 3         | 0.13%   |
| Motorola PCS                           | 2         | 0.09%   |
| Emulex                                 | 2         | 0.09%   |
| VIA Technologies                       | 1         | 0.04%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.04%   |
| Solarflare Communications              | 1         | 0.04%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.04%   |
| QLogic                                 | 1         | 0.04%   |
| Novatel Wireless                       | 1         | 0.04%   |
| Microchip Technology                   | 1         | 0.04%   |
| Mellanox Technologies                  | 1         | 0.04%   |
| ICS Advent                             | 1         | 0.04%   |
| Google                                 | 1         | 0.04%   |
| Apple                                  | 1         | 0.04%   |
| 3Com                                   | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 998       | 43.07%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 114       | 4.92%   |
| Intel I211 Gigabit Network Connection                             | 109       | 4.7%    |
| Realtek RTL8125 2.5GbE Controller                                 | 89        | 3.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 83        | 3.58%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 62        | 2.68%   |
| Intel Ethernet Connection (2) I219-V                              | 58        | 2.5%    |
| Intel Ethernet Controller I225-V                                  | 54        | 2.33%   |
| Intel Ethernet Connection I217-LM                                 | 48        | 2.07%   |
| Intel Ethernet Connection (7) I219-V                              | 40        | 1.73%   |
| Intel Ethernet Connection (2) I219-LM                             | 22        | 0.95%   |
| Intel Ethernet Connection I218-LM                                 | 21        | 0.91%   |
| Intel Ethernet Connection I217-V                                  | 20        | 0.86%   |
| Intel Ethernet Connection (4) I219-LM                             | 20        | 0.86%   |
| Intel Ethernet Connection I219-LM                                 | 18        | 0.78%   |
| Intel Ethernet Connection (4) I219-V                              | 18        | 0.78%   |
| Intel Ethernet Connection (3) I218-LM                             | 18        | 0.78%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 16        | 0.69%   |
| Intel 82579V Gigabit Network Connection                           | 16        | 0.69%   |
| Intel 82577LM Gigabit Network Connection                          | 16        | 0.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 15        | 0.65%   |
| ASIX AX88179 Gigabit Ethernet                                     | 15        | 0.65%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 14        | 0.6%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 14        | 0.6%    |
| Intel I210 Gigabit Network Connection                             | 14        | 0.6%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 12        | 0.52%   |
| Intel Ethernet Connection (7) I219-LM                             | 11        | 0.47%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 10        | 0.43%   |
| Intel Ethernet Connection X553 1GbE                               | 10        | 0.43%   |
| Intel Ethernet Connection (6) I219-V                              | 10        | 0.43%   |
| Intel Ethernet Connection (5) I219-LM                             | 10        | 0.43%   |
| Intel Ethernet Connection (2) I218-V                              | 10        | 0.43%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 10        | 0.43%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 9         | 0.39%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 8         | 0.35%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 8         | 0.35%   |
| Intel Ethernet Connection I219-V                                  | 8         | 0.35%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 7         | 0.3%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 7         | 0.3%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 6         | 0.26%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2126      | 52.82%  |
| WiFi     | 1866      | 46.36%  |
| Modem    | 30        | 0.75%   |
| Unknown  | 3         | 0.07%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1401      | 54.64%  |
| Ethernet | 1163      | 45.36%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1370      | 56.1%   |
| 1     | 957       | 39.19%  |
| 3     | 77        | 3.15%   |
| 4     | 21        | 0.86%   |
| 0     | 13        | 0.53%   |
| 5     | 2         | 0.08%   |
| 9     | 1         | 0.04%   |
| 6     | 1         | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1832      | 73.63%  |
| Yes  | 656       | 26.37%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 914       | 52.8%   |
| Realtek Semiconductor           | 174       | 10.05%  |
| Qualcomm Atheros Communications | 120       | 6.93%   |
| Cambridge Silicon Radio         | 102       | 5.89%   |
| IMC Networks                    | 83        | 4.79%   |
| Broadcom                        | 65        | 3.76%   |
| Apple                           | 60        | 3.47%   |
| ASUSTek Computer                | 44        | 2.54%   |
| Lite-On Technology              | 43        | 2.48%   |
| Foxconn / Hon Hai               | 40        | 2.31%   |
| MediaTek                        | 22        | 1.27%   |
| Dell                            | 12        | 0.69%   |
| TP-Link                         | 7         | 0.4%    |
| Toshiba                         | 7         | 0.4%    |
| Realtek                         | 7         | 0.4%    |
| Hewlett-Packard                 | 4         | 0.23%   |
| Belkin Components               | 4         | 0.23%   |
| Ralink                          | 3         | 0.17%   |
| Edimax Technology               | 3         | 0.17%   |
| Dynex                           | 3         | 0.17%   |
| Ralink Technology               | 2         | 0.12%   |
| Marvell Semiconductor           | 2         | 0.12%   |
| HTC (High Tech Computer)        | 2         | 0.12%   |
| Actions                         | 2         | 0.12%   |
| SINO WEALTH                     | 1         | 0.06%   |
| Opticis                         | 1         | 0.06%   |
| Integrated System Solution      | 1         | 0.06%   |
| Foxconn International           | 1         | 0.06%   |
| Creative Technology             | 1         | 0.06%   |
| Chicony Electronics             | 1         | 0.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 300       | 17.31%  |
| Intel AX200 Bluetooth                               | 186       | 10.73%  |
| Intel AX201 Bluetooth                               | 135       | 7.79%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 123       | 7.1%    |
| Realtek Bluetooth Radio                             | 105       | 6.06%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 102       | 5.89%   |
| Qualcomm Atheros  Bluetooth Device                  | 77        | 4.44%   |
| Intel Wireless-AC 3168 Bluetooth                    | 49        | 2.83%   |
| Realtek  Bluetooth 4.2 Adapter                      | 42        | 2.42%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 42        | 2.42%   |
| Apple Bluetooth Host Controller                     | 33        | 1.9%    |
| IMC Networks Bluetooth Radio                        | 30        | 1.73%   |
| Intel AX210 Bluetooth                               | 24        | 1.38%   |
| Intel Bluetooth Device                              | 23        | 1.33%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 22        | 1.27%   |
| MediaTek Wireless_Device                            | 21        | 1.21%   |
| IMC Networks Bluetooth Device                       | 21        | 1.21%   |
| Broadcom BCM2045B (BDC-2.1)                         | 20        | 1.15%   |
| Apple Bluetooth USB Host Controller                 | 20        | 1.15%   |
| IMC Networks Wireless_Device                        | 19        | 1.1%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 15        | 0.87%   |
| Lite-On Bluetooth Device                            | 15        | 0.87%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 15        | 0.87%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 15        | 0.87%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 14        | 0.81%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 14        | 0.81%   |
| ASUS ASUS USB-BT500                                 | 14        | 0.81%   |
| Realtek 802.11ac WLAN Adapter                       | 12        | 0.69%   |
| Foxconn / Hon Hai Bluetooth Device                  | 11        | 0.63%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 10        | 0.58%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 8         | 0.46%   |
| TP-Link TP-Cdj+ UB5A Adapter                        | 7         | 0.4%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 7         | 0.4%    |
| Foxconn / Hon Hai Wireless_Device                   | 7         | 0.4%    |
| Dell BCM20702A0 Bluetooth Module                    | 7         | 0.4%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 7         | 0.4%    |
| Realtek 802.11ac WLAN Adapter                       | 6         | 0.35%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 6         | 0.35%   |
| Realtek RTL8723B Bluetooth                          | 5         | 0.29%   |
| IMC Networks BCM20702A0                             | 5         | 0.29%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1634      | 42.57%  |
| AMD                                  | 872       | 22.72%  |
| Nvidia                               | 769       | 20.04%  |
| C-Media Electronics                  | 79        | 2.06%   |
| Logitech                             | 55        | 1.43%   |
| Texas Instruments                    | 33        | 0.86%   |
| Kingston Technology                  | 28        | 0.73%   |
| JMTek                                | 25        | 0.65%   |
| Razer USA                            | 21        | 0.55%   |
| Focusrite-Novation                   | 21        | 0.55%   |
| Corsair                              | 17        | 0.44%   |
| ASUSTek Computer                     | 16        | 0.42%   |
| SteelSeries ApS                      | 14        | 0.36%   |
| Realtek Semiconductor                | 14        | 0.36%   |
| Creative Technology                  | 13        | 0.34%   |
| Creative Labs                        | 12        | 0.31%   |
| Generalplus Technology               | 11        | 0.29%   |
| DSEA A/S                             | 10        | 0.26%   |
| GN Netcom                            | 9         | 0.23%   |
| BEHRINGER International              | 9         | 0.23%   |
| Lenovo                               | 8         | 0.21%   |
| Samson Technologies                  | 7         | 0.18%   |
| RODE Microphones                     | 7         | 0.18%   |
| Sony                                 | 6         | 0.16%   |
| SAVITECH                             | 6         | 0.16%   |
| PreSonus Audio Electronics           | 6         | 0.16%   |
| Blue Microphones                     | 6         | 0.16%   |
| Yamaha                               | 5         | 0.13%   |
| XMOS                                 | 5         | 0.13%   |
| Thesycon Systemsoftware & Consulting | 5         | 0.13%   |
| Plantronics                          | 4         | 0.1%    |
| Hewlett-Packard                      | 4         | 0.1%    |
| VIA Technologies                     | 3         | 0.08%   |
| Native Instruments                   | 3         | 0.08%   |
| Mark of the Unicorn                  | 3         | 0.08%   |
| Giga-Byte Technology                 | 3         | 0.08%   |
| FiiO Electronics Technology          | 3         | 0.08%   |
| FIFINE Microphones                   | 3         | 0.08%   |
| Dell                                 | 3         | 0.08%   |
| BR25                                 | 3         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 315       | 6.87%   |
| AMD Starship/Matisse HD Audio Controller                                   | 219       | 4.78%   |
| Intel Sunrise Point-LP HD Audio                                            | 209       | 4.56%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 148       | 3.23%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 148       | 3.23%   |
| Intel Cannon Lake PCH cAVS                                                 | 147       | 3.21%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 131       | 2.86%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 127       | 2.77%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 96        | 2.09%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 92        | 2.01%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 91        | 1.99%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 87        | 1.9%    |
| Intel 200 Series PCH HD Audio                                              | 76        | 1.66%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 71        | 1.55%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 66        | 1.44%   |
| Nvidia TU116 High Definition Audio Controller                              | 65        | 1.42%   |
| Nvidia TU106 High Definition Audio Controller                              | 63        | 1.37%   |
| Nvidia GP107GL High Definition Audio Controller                            | 62        | 1.35%   |
| Nvidia GP106 High Definition Audio Controller                              | 61        | 1.33%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 59        | 1.29%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 57        | 1.24%   |
| Intel Haswell-ULT HD Audio Controller                                      | 57        | 1.24%   |
| Intel 8 Series HD Audio Controller                                         | 57        | 1.24%   |
| Intel Comet Lake PCH cAVS                                                  | 55        | 1.2%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 55        | 1.2%    |
| Nvidia GP104 High Definition Audio Controller                              | 52        | 1.13%   |
| Nvidia GA104 High Definition Audio Controller                              | 51        | 1.11%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 49        | 1.07%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 48        | 1.05%   |
| Intel Broadwell-U Audio Controller                                         | 48        | 1.05%   |
| Intel CM238 HD Audio Controller                                            | 44        | 0.96%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 40        | 0.87%   |
| Intel Comet Lake PCH-LP cAVS                                               | 39        | 0.85%   |
| AMD FCH Azalia Controller                                                  | 39        | 0.85%   |
| AMD Navi 10 HDMI Audio                                                     | 38        | 0.83%   |
| Nvidia TU104 HD Audio Controller                                           | 37        | 0.81%   |
| Nvidia GA106 High Definition Audio Controller                              | 37        | 0.81%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 35        | 0.76%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 31        | 0.68%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 27        | 0.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 561       | 21%     |
| SK hynix            | 448       | 16.77%  |
| Kingston            | 295       | 11.04%  |
| Micron Technology   | 257       | 9.62%   |
| Corsair             | 242       | 9.06%   |
| Crucial             | 197       | 7.37%   |
| G.Skill             | 155       | 5.8%    |
| Unknown             | 133       | 4.98%   |
| A-DATA Technology   | 61        | 2.28%   |
| Ramaxel Technology  | 40        | 1.5%    |
| Team                | 36        | 1.35%   |
| Nanya Technology    | 26        | 0.97%   |
| Elpida              | 23        | 0.86%   |
| Patriot             | 19        | 0.71%   |
| Unknown             | 16        | 0.6%    |
| Unknown (ABCD)      | 13        | 0.49%   |
| GOODRAM             | 10        | 0.37%   |
| Apacer              | 9         | 0.34%   |
| Neo Forza           | 7         | 0.26%   |
| Avant               | 7         | 0.26%   |
| Silicon Power       | 6         | 0.22%   |
| PNY                 | 6         | 0.22%   |
| ASint Technology    | 6         | 0.22%   |
| Transcend           | 5         | 0.19%   |
| Timetec             | 5         | 0.19%   |
| Smart               | 5         | 0.19%   |
| Goldkey             | 5         | 0.19%   |
| Sesame              | 4         | 0.15%   |
| AMD                 | 4         | 0.15%   |
| Kingmax             | 3         | 0.11%   |
| CSX                 | 3         | 0.11%   |
| Unknown (0x0B5E)    | 2         | 0.07%   |
| Unifosa             | 2         | 0.07%   |
| Teikon              | 2         | 0.07%   |
| Smart Brazil        | 2         | 0.07%   |
| Lexar               | 2         | 0.07%   |
| Kllisre             | 2         | 0.07%   |
| Juhor               | 2         | 0.07%   |
| Golden Empire       | 2         | 0.07%   |
| GeIL                | 2         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 26        | 0.9%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 25        | 0.87%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 24        | 0.83%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 23        | 0.8%    |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 23        | 0.8%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 21        | 0.73%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 21        | 0.73%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 21        | 0.73%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 21        | 0.73%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 20        | 0.69%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 19        | 0.66%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 17        | 0.59%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s            | 17        | 0.59%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 16        | 0.56%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 16        | 0.56%   |
| Unknown                                                          | 16        | 0.56%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 15        | 0.52%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 14        | 0.49%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 14        | 0.49%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 13        | 0.45%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 12        | 0.42%   |
| SK hynix RAM HMA82GR7DJR8N-XN 16384MB DIMM DDR4 3200MT/s         | 12        | 0.42%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 12        | 0.42%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 12        | 0.42%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 12        | 0.42%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 12        | 0.42%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s           | 12        | 0.42%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 11        | 0.38%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 11        | 0.38%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 11        | 0.38%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 10        | 0.35%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 3200MT/s            | 10        | 0.35%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 10        | 0.35%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 10        | 0.35%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 9         | 0.31%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 9         | 0.31%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 9         | 0.31%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 9         | 0.31%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 9         | 0.31%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 9         | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1361      | 59.8%   |
| DDR3    | 662       | 29.09%  |
| DDR5    | 52        | 2.28%   |
| LPDDR4  | 51        | 2.24%   |
| LPDDR3  | 42        | 1.85%   |
| Unknown | 33        | 1.45%   |
| DDR2    | 28        | 1.23%   |
| SDRAM   | 27        | 1.19%   |
| LPDDR5  | 16        | 0.7%    |
| DDR     | 3         | 0.13%   |
| DRAM    | 1         | 0.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1220      | 53.32%  |
| DIMM         | 928       | 40.56%  |
| Row Of Chips | 124       | 5.42%   |
| Chip         | 11        | 0.48%   |
| RIMM         | 3         | 0.13%   |
| Unknown      | 2         | 0.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 1121      | 44.57%  |
| 4096  | 617       | 24.53%  |
| 16384 | 470       | 18.69%  |
| 2048  | 161       | 6.4%    |
| 32768 | 116       | 4.61%   |
| 1024  | 23        | 0.91%   |
| 49152 | 2         | 0.08%   |
| 512   | 2         | 0.08%   |
| 12288 | 1         | 0.04%   |
| 64    | 1         | 0.04%   |
| 16    | 1         | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 473       | 18.69%  |
| 3200    | 457       | 18.06%  |
| 2667    | 406       | 16.04%  |
| 2400    | 201       | 7.94%   |
| 2133    | 115       | 4.54%   |
| 1333    | 112       | 4.43%   |
| 3600    | 110       | 4.35%   |
| 1334    | 46        | 1.82%   |
| 3733    | 41        | 1.62%   |
| 1867    | 38        | 1.5%    |
| 3400    | 36        | 1.42%   |
| 4800    | 33        | 1.3%    |
| 3000    | 31        | 1.22%   |
| 3266    | 25        | 0.99%   |
| 3800    | 22        | 0.87%   |
| 1067    | 22        | 0.87%   |
| 2666    | 21        | 0.83%   |
| 1866    | 20        | 0.79%   |
| 800     | 19        | 0.75%   |
| 667     | 19        | 0.75%   |
| 4267    | 18        | 0.71%   |
| Unknown | 18        | 0.71%   |
| 3533    | 17        | 0.67%   |
| 1800    | 17        | 0.67%   |
| 6400    | 16        | 0.63%   |
| 2933    | 16        | 0.63%   |
| 3866    | 15        | 0.59%   |
| 2800    | 13        | 0.51%   |
| 3466    | 12        | 0.47%   |
| 3666    | 10        | 0.4%    |
| 4199    | 8         | 0.32%   |
| 8400    | 7         | 0.28%   |
| 2000    | 7         | 0.28%   |
| 5200    | 6         | 0.24%   |
| 3534    | 6         | 0.24%   |
| 3334    | 6         | 0.24%   |
| 2048    | 6         | 0.24%   |
| 1648    | 6         | 0.24%   |
| 6000    | 5         | 0.2%    |
| 4266    | 5         | 0.2%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 20        | 35.71%  |
| Brother Industries    | 18        | 32.14%  |
| Canon                 | 6         | 10.71%  |
| Seiko Epson           | 5         | 8.93%   |
| Samsung Electronics   | 2         | 3.57%   |
| MIIIW                 | 1         | 1.79%   |
| Lexmark International | 1         | 1.79%   |
| Kyocera               | 1         | 1.79%   |
| Gprinter              | 1         | 1.79%   |
| Dymo-CoStar           | 1         | 1.79%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Canon PIXMA MG3600 Series              | 3         | 5.26%   |
| Seiko Epson ET-4700 Series             | 2         | 3.51%   |
| HP DeskJet F4100 Printer series        | 2         | 3.51%   |
| HP DeskJet 2620 All-in-One Printer     | 2         | 3.51%   |
| Brother Printer                        | 2         | 3.51%   |
| Brother DCP-7055 scanner/printer       | 2         | 3.51%   |
| Seiko Epson XP-240 Series              | 1         | 1.75%   |
| Seiko Epson XP-2100 Series             | 1         | 1.75%   |
| Seiko Epson L3150 Series               | 1         | 1.75%   |
| Samsung SCX-3400 Series                | 1         | 1.75%   |
| Samsung SCX-3200 Series                | 1         | 1.75%   |
| MIIIW MW Keyboard Air Mini             | 1         | 1.75%   |
| Lexmark International B2236dw          | 1         | 1.75%   |
| Kyocera UTAX_TA LP 3240_LP 4240        | 1         | 1.75%   |
| HP PSC 1400                            | 1         | 1.75%   |
| HP OfficeJet Pro 6960                  | 1         | 1.75%   |
| HP OfficeJet 5200 series               | 1         | 1.75%   |
| HP OfficeJet 4650 series               | 1         | 1.75%   |
| HP LaserJet Professional P1102w        | 1         | 1.75%   |
| HP LaserJet P1005                      | 1         | 1.75%   |
| HP LaserJet M203-M206                  | 1         | 1.75%   |
| HP LaserJet 3050                       | 1         | 1.75%   |
| HP LaserJet 1015                       | 1         | 1.75%   |
| HP HP OfficeJet Pro 8020 series        | 1         | 1.75%   |
| HP ENVY 6400 series                    | 1         | 1.75%   |
| HP ENVY 4500 series                    | 1         | 1.75%   |
| HP DeskJet F2492 All-in-One            | 1         | 1.75%   |
| HP Deskjet 4640 series                 | 1         | 1.75%   |
| HP DeskJet 3700 series                 | 1         | 1.75%   |
| HP DeskJet 2700 series                 | 1         | 1.75%   |
| HP Deskjet 1050 J410                   | 1         | 1.75%   |
| Gprinter GP-58                         | 1         | 1.75%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo | 1         | 1.75%   |
| Canon TS5100 series                    | 1         | 1.75%   |
| Canon G2000 series                     | 1         | 1.75%   |
| Canon CanoScan LiDE 300                | 1         | 1.75%   |
| Brother MFC-L3770CDW series            | 1         | 1.75%   |
| Brother MFC-L3750CDW                   | 1         | 1.75%   |
| Brother MFC-J6545DW                    | 1         | 1.75%   |
| Brother MFC-J497DW                     | 1         | 1.75%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Seiko Epson     | 2         | 40%     |
| Hewlett-Packard | 2         | 40%     |
| Canon           | 1         | 20%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1         | 20%     |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]           | 1         | 20%     |
| HP ScanJet 2400c                                        | 1         | 20%     |
| HP ScanJet 2200c                                        | 1         | 20%     |
| Canon CanoScan LiDE 200                                 | 1         | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 328       | 21.95%  |
| IMC Networks                           | 174       | 11.65%  |
| Logitech                               | 119       | 7.97%   |
| Microdia                               | 118       | 7.9%    |
| Bison Electronics                      | 109       | 7.3%    |
| Realtek Semiconductor                  | 104       | 6.96%   |
| Sunplus Innovation Technology          | 77        | 5.15%   |
| Quanta                                 | 65        | 4.35%   |
| Apple                                  | 47        | 3.15%   |
| Cheng Uei Precision Industry (Foxlink) | 42        | 2.81%   |
| Syntek                                 | 33        | 2.21%   |
| Lite-On Technology                     | 29        | 1.94%   |
| Suyin                                  | 24        | 1.61%   |
| Acer                                   | 22        | 1.47%   |
| Sonix Technology                       | 17        | 1.14%   |
| Luxvisions Innotech Limited            | 17        | 1.14%   |
| Samsung Electronics                    | 15        | 1%      |
| Microsoft                              | 14        | 0.94%   |
| Silicon Motion                         | 13        | 0.87%   |
| Lenovo                                 | 12        | 0.8%    |
| Generalplus Technology                 | 8         | 0.54%   |
| Alcor Micro                            | 8         | 0.54%   |
| Primax Electronics                     | 6         | 0.4%    |
| Razer USA                              | 5         | 0.33%   |
| KYE Systems (Mouse Systems)            | 5         | 0.33%   |
| Hewlett-Packard                        | 5         | 0.33%   |
| GEMBIRD                                | 5         | 0.33%   |
| Creative Technology                    | 5         | 0.33%   |
| Z-Star Microelectronics                | 3         | 0.2%    |
| WaveRider Communications               | 3         | 0.2%    |
| Ricoh                                  | 3         | 0.2%    |
| MacroSilicon                           | 3         | 0.2%    |
| Importek                               | 3         | 0.2%    |
| Google                                 | 3         | 0.2%    |
| ARC International                      | 3         | 0.2%    |
| SunplusIT                              | 2         | 0.13%   |
| Sunplus Technology                     | 2         | 0.13%   |
| Ruision                                | 2         | 0.13%   |
| OPPO Electronics                       | 2         | 0.13%   |
| Jieli Technology                       | 2         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Chicony integrated camera               | 86        | 5.73%   |
| IMC Networks Integrated Camera          | 53        | 3.53%   |
| Microdia Integrated_Webcam_HD           | 46        | 3.06%   |
| IMC Networks USB2.0 HD UVC WebCam       | 45        | 3%      |
| Realtek Integrated_Webcam_HD            | 39        | 2.6%    |
| Bison Integrated Camera                 | 36        | 2.4%    |
| Chicony HD WebCam                       | 35        | 2.33%   |
| Logitech HD Pro Webcam C920             | 26        | 1.73%   |
| IMC Networks USB2.0 VGA UVC WebCam      | 26        | 1.73%   |
| Logitech Webcam C270                    | 25        | 1.66%   |
| Sunplus Integrated_Webcam_HD            | 22        | 1.46%   |
| Syntek Integrated Camera                | 21        | 1.4%    |
| Lite-On Integrated Camera               | 19        | 1.26%   |
| Logitech C922 Pro Stream Webcam         | 17        | 1.13%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR      | 17        | 1.13%   |
| Bison EasyCamera                        | 16        | 1.07%   |
| Samsung Galaxy series, misc. (MTP mode) | 15        | 1%      |
| Quanta HP TrueVision HD Camera          | 13        | 0.87%   |
| Chicony USB2.0 VGA UVC WebCam           | 13        | 0.87%   |
| Chicony HP Wide Vision HD Camera        | 13        | 0.87%   |
| Quanta HD User Facing                   | 12        | 0.8%    |
| Chicony USB2.0 Camera                   | 12        | 0.8%    |
| Chicony Integrated Camera (1280x720@30) | 12        | 0.8%    |
| Bison HD Webcam                         | 12        | 0.8%    |
| Apple Built-in iSight                   | 12        | 0.8%    |
| Microdia Integrated Webcam              | 11        | 0.73%   |
| Chicony HP Truevision HD                | 11        | 0.73%   |
| Chicony EasyCamera                      | 11        | 0.73%   |
| Quanta HD Webcam                        | 10        | 0.67%   |
| Chicony HP TrueVision HD Camera         | 10        | 0.67%   |
| Chicony HP HD Camera                    | 10        | 0.67%   |
| Acer BisonCam,NB Pro                    | 10        | 0.67%   |
| Sonix USB2.0 HD UVC WebCam              | 9         | 0.6%    |
| Chicony USB2.0 HD UVC WebCam            | 9         | 0.6%    |
| Chicony HD User Facing                  | 9         | 0.6%    |
| Bison SunplusIT Integrated Camera       | 9         | 0.6%    |
| Bison Lenovo EasyCamera                 | 9         | 0.6%    |
| Apple FaceTime HD Camera (Built-in)     | 9         | 0.6%    |
| Realtek USB Camera                      | 8         | 0.53%   |
| Microdia Webcam Vitade AF               | 8         | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 90        | 36.44%  |
| Synaptics                          | 70        | 28.34%  |
| Shenzhen Goodix Technology         | 35        | 14.17%  |
| Elan Microelectronics              | 17        | 6.88%   |
| Upek                               | 13        | 5.26%   |
| LighTuning Technology              | 12        | 4.86%   |
| AuthenTec                          | 6         | 2.43%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.81%   |
| STMicroelectronics                 | 1         | 0.4%    |
| DigitalPersona                     | 1         | 0.4%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                               | 23        | 9.31%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 23        | 9.31%   |
| Shenzhen Goodix  FingerPrint Device                                        | 18        | 7.29%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 15        | 6.07%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 13        | 5.26%   |
| Validity Sensors Synaptics WBDI                                            | 13        | 5.26%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 13        | 5.26%   |
| Shenzhen Goodix Fingerprint Reader                                         | 10        | 4.05%   |
| Elan ELAN:Fingerprint                                                      | 10        | 4.05%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 8         | 3.24%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 7         | 2.83%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 7         | 2.83%   |
| Synaptics  WBDI                                                            | 7         | 2.83%   |
| Shenzhen Goodix FingerPrint                                                | 7         | 2.83%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 6         | 2.43%   |
| Validity Sensors Fingerprint scanner                                       | 5         | 2.02%   |
| Elan ELAN:ARM-M4                                                           | 5         | 2.02%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 1.62%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 1.21%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 1.21%   |
| Synaptics WBDI                                                             | 3         | 1.21%   |
| Synaptics UWP WBDI                                                         | 3         | 1.21%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 1.21%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 3         | 1.21%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.81%   |
| Validity Sensors VFS491                                                    | 2         | 0.81%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 0.81%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.81%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 2         | 0.81%   |
| Synaptics WBDI Device                                                      | 2         | 0.81%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 0.81%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 0.81%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 2         | 0.81%   |
| AuthenTec AES1600                                                          | 2         | 0.81%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.4%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.4%    |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 0.4%    |
| Synaptics UWP WBDI Device                                                  | 1         | 0.4%    |
| Synaptics TouchPad                                                         | 1         | 0.4%    |
| Synaptics Fingerprint scanner                                              | 1         | 0.4%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 50        | 44.64%  |
| Broadcom              | 39        | 34.82%  |
| O2 Micro              | 6         | 5.36%   |
| Upek                  | 5         | 4.46%   |
| Lenovo                | 4         | 3.57%   |
| Gemalto (was Gemplus) | 2         | 1.79%   |
| Yubico.com            | 1         | 0.89%   |
| SCM Microsystems      | 1         | 0.89%   |
| OmniKey               | 1         | 0.89%   |
| Clay Logic            | 1         | 0.89%   |
| Cherry                | 1         | 0.89%   |
| Aladdin R.D.          | 1         | 0.89%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 50        | 44.64%  |
| Broadcom 5880                                                                | 16        | 14.29%  |
| Broadcom BCM5880 Secure Applications Processor                               | 9         | 8.04%   |
| Broadcom 58200                                                               | 7         | 6.25%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 6         | 5.36%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 4.46%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 5         | 4.46%   |
| Lenovo Integrated Smart Card Reader                                          | 4         | 3.57%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 1.79%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                          | 1         | 0.89%   |
| SCM Microsystems SCR3500 A Contact Reader                                    | 1         | 0.89%   |
| OmniKey CardMan 1021                                                         | 1         | 0.89%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.89%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.89%   |
| Cherry Smart Card Reader USB                                                 | 1         | 0.89%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.89%   |
| Aladdin R.D. JaCarta LT                                                      | 1         | 0.89%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1833      | 73.79%  |
| 1     | 529       | 21.3%   |
| 2     | 112       | 4.51%   |
| 4     | 5         | 0.2%    |
| 3     | 5         | 0.2%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 247       | 32.67%  |
| Graphics card            | 192       | 25.4%   |
| Chipcard                 | 107       | 14.15%  |
| Net/wireless             | 64        | 8.47%   |
| Multimedia controller    | 36        | 4.76%   |
| Camera                   | 32        | 4.23%   |
| Unassigned class         | 19        | 2.51%   |
| Communication controller | 17        | 2.25%   |
| Bluetooth                | 12        | 1.59%   |
| Network                  | 6         | 0.79%   |
| Card reader              | 6         | 0.79%   |
| Net/ethernet             | 5         | 0.66%   |
| Sound                    | 3         | 0.4%    |
| Storage/nvme             | 2         | 0.26%   |
| Storage                  | 2         | 0.26%   |
| Modem                    | 2         | 0.26%   |
| Dvb card                 | 2         | 0.26%   |
| Wireless                 | 1         | 0.13%   |
| Storage/raid             | 1         | 0.13%   |

