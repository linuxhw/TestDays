Linux Mint - Tested Hardware & Statistics
-----------------------------------------

A project to collect tested hardware configurations for Linux Mint.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Linux_Mint/Desktop/README.md) and [notebooks](/Dist/Linux_Mint/Notebook/README.md).

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

Total: 27885

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gateway       | IPISB-VR                    | Desktop     | [4bed351eee](https://linux-hardware.org/?probe=4bed351eee) | Sep 07, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [e207539e68](https://linux-hardware.org/?probe=e207539e68) | Sep 07, 2023 |
| ASRock        | 775Dual-VSTA                | Desktop     | [05af667eb0](https://linux-hardware.org/?probe=05af667eb0) | Sep 07, 2023 |
| Sony          | SVF1521V6EB                 | Notebook    | [1d08716b2c](https://linux-hardware.org/?probe=1d08716b2c) | Sep 07, 2023 |
| Dell          | Latitude E7240              | Notebook    | [79a666783a](https://linux-hardware.org/?probe=79a666783a) | Sep 07, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [67934ce24a](https://linux-hardware.org/?probe=67934ce24a) | Sep 07, 2023 |
| Lenovo        | NOK                         | Desktop     | [30f2c89249](https://linux-hardware.org/?probe=30f2c89249) | Sep 07, 2023 |
| Dell          | 0Y2MRG A00                  | Desktop     | [34ae665da1](https://linux-hardware.org/?probe=34ae665da1) | Sep 07, 2023 |
| Lenovo        | 3704 SDK0R32862 WIN 3258... | Desktop     | [907edde95a](https://linux-hardware.org/?probe=907edde95a) | Sep 07, 2023 |
| HP            | 18E5                        | Desktop     | [b0210e782a](https://linux-hardware.org/?probe=b0210e782a) | Sep 07, 2023 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [ef99cba7a5](https://linux-hardware.org/?probe=ef99cba7a5) | Sep 06, 2023 |
| ASRock        | Z87 Pro4                    | Desktop     | [89b861e771](https://linux-hardware.org/?probe=89b861e771) | Sep 06, 2023 |
| Unknown       | Unknown                     | Notebook    | [16cb5e0d5b](https://linux-hardware.org/?probe=16cb5e0d5b) | Sep 06, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [29e1f84537](https://linux-hardware.org/?probe=29e1f84537) | Sep 06, 2023 |
| HP            | 81B3                        | Desktop     | [b04c59ca3e](https://linux-hardware.org/?probe=b04c59ca3e) | Sep 06, 2023 |
| Lenovo        | ThinkPad T580 20LAS01H00    | Notebook    | [129e989480](https://linux-hardware.org/?probe=129e989480) | Sep 06, 2023 |
| Dell          | 0HMX8D A01                  | Desktop     | [48fa151690](https://linux-hardware.org/?probe=48fa151690) | Sep 06, 2023 |
| Timi          | Xiaomi Book Pro 14 2022     | Notebook    | [32c34f0aa2](https://linux-hardware.org/?probe=32c34f0aa2) | Sep 06, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [8d4c48dd2f](https://linux-hardware.org/?probe=8d4c48dd2f) | Sep 06, 2023 |
| Standard      | MB45II/MB45IN               | Notebook    | [1e46c6aa81](https://linux-hardware.org/?probe=1e46c6aa81) | Sep 06, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [ba05ae3ca2](https://linux-hardware.org/?probe=ba05ae3ca2) | Sep 06, 2023 |
| HP            | 21F5                        | Desktop     | [af9bc6bde6](https://linux-hardware.org/?probe=af9bc6bde6) | Sep 06, 2023 |
| Biostar       | G31-M7 TE                   | Desktop     | [2ef74da3f9](https://linux-hardware.org/?probe=2ef74da3f9) | Sep 06, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [299a459ec5](https://linux-hardware.org/?probe=299a459ec5) | Sep 06, 2023 |
| ASUSTek       | X75VC                       | Notebook    | [ba211ae5ca](https://linux-hardware.org/?probe=ba211ae5ca) | Sep 06, 2023 |
| Dell          | 0F3KHR A00                  | Desktop     | [21a1983dcc](https://linux-hardware.org/?probe=21a1983dcc) | Sep 06, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [f421de992d](https://linux-hardware.org/?probe=f421de992d) | Sep 06, 2023 |
| ASUSTek       | K70IO                       | Notebook    | [bb32d5e30c](https://linux-hardware.org/?probe=bb32d5e30c) | Sep 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [7fd153d869](https://linux-hardware.org/?probe=7fd153d869) | Sep 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [6508e8eeb8](https://linux-hardware.org/?probe=6508e8eeb8) | Sep 06, 2023 |
| ASRock        | H61M-DGS R2.0               | Desktop     | [69a1288adb](https://linux-hardware.org/?probe=69a1288adb) | Sep 06, 2023 |
| ASRock        | H61M-DGS R2.0               | Desktop     | [f00617a2cf](https://linux-hardware.org/?probe=f00617a2cf) | Sep 06, 2023 |
| Dell          | 0Y2MRG A00                  | Desktop     | [ad6d3dd867](https://linux-hardware.org/?probe=ad6d3dd867) | Sep 06, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [c7bdf1cee6](https://linux-hardware.org/?probe=c7bdf1cee6) | Sep 06, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [1d1c8e33ff](https://linux-hardware.org/?probe=1d1c8e33ff) | Sep 06, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [4ed976d4ba](https://linux-hardware.org/?probe=4ed976d4ba) | Sep 06, 2023 |
| Notebook      | W230SS                      | Notebook    | [3d9af4f57a](https://linux-hardware.org/?probe=3d9af4f57a) | Sep 06, 2023 |
| AZW           | U59                         | Desktop     | [0971b3ceb2](https://linux-hardware.org/?probe=0971b3ceb2) | Sep 06, 2023 |
| ASUSTek       | K70IO                       | Notebook    | [e4f165224f](https://linux-hardware.org/?probe=e4f165224f) | Sep 06, 2023 |
| Foxconn       | 2AB1                        | Desktop     | [bf3a43c945](https://linux-hardware.org/?probe=bf3a43c945) | Sep 06, 2023 |
| Lenovo        | ThinkPad E580 20KS001JUK    | Notebook    | [8b44f9cbdc](https://linux-hardware.org/?probe=8b44f9cbdc) | Sep 06, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [56c33713a8](https://linux-hardware.org/?probe=56c33713a8) | Sep 06, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | Notebook    | [dccf0aaf61](https://linux-hardware.org/?probe=dccf0aaf61) | Sep 06, 2023 |
| Fujitsu       | D3501-A1 S26361-D3501-A1    | Desktop     | [7c51242294](https://linux-hardware.org/?probe=7c51242294) | Sep 06, 2023 |
| HP            | 81C9                        | Desktop     | [e80c7bf9d5](https://linux-hardware.org/?probe=e80c7bf9d5) | Sep 05, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | Notebook    | [51e417460a](https://linux-hardware.org/?probe=51e417460a) | Sep 05, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS1... | Convertible | [814beb2b0c](https://linux-hardware.org/?probe=814beb2b0c) | Sep 05, 2023 |
| ASUSTek       | M3N78-VM                    | Desktop     | [0e8a4a2220](https://linux-hardware.org/?probe=0e8a4a2220) | Sep 05, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS1... | Convertible | [ceee64c16c](https://linux-hardware.org/?probe=ceee64c16c) | Sep 05, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [4322b8da26](https://linux-hardware.org/?probe=4322b8da26) | Sep 05, 2023 |
| Lenovo        | G570 4334                   | Notebook    | [ce571e2d16](https://linux-hardware.org/?probe=ce571e2d16) | Sep 05, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [326d057e96](https://linux-hardware.org/?probe=326d057e96) | Sep 05, 2023 |
| HP            | 1497                        | Desktop     | [66bc78bedb](https://linux-hardware.org/?probe=66bc78bedb) | Sep 05, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [7b717719f5](https://linux-hardware.org/?probe=7b717719f5) | Sep 05, 2023 |
| Notebook      | N9x0TC                      | Notebook    | [ea9c38200b](https://linux-hardware.org/?probe=ea9c38200b) | Sep 05, 2023 |
| MSI           | Prestige 14H B12UCX         | Notebook    | [75d602c66f](https://linux-hardware.org/?probe=75d602c66f) | Sep 05, 2023 |
| Acer          | Aspire 5750Z                | Notebook    | [5bec99a137](https://linux-hardware.org/?probe=5bec99a137) | Sep 05, 2023 |
| Apple         | MacBook8,1                  | Notebook    | [f2d8d7ffbb](https://linux-hardware.org/?probe=f2d8d7ffbb) | Sep 05, 2023 |
| MSI           | Z270 GAMING PRO CARBON      | Desktop     | [6644f7f91e](https://linux-hardware.org/?probe=6644f7f91e) | Sep 05, 2023 |
| MSI           | P55-GD65                    | Desktop     | [2b514a72b1](https://linux-hardware.org/?probe=2b514a72b1) | Sep 05, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [8c0e6613ee](https://linux-hardware.org/?probe=8c0e6613ee) | Sep 05, 2023 |
| MSI           | PRO B760M-G DDR4            | Desktop     | [a8f42a3c96](https://linux-hardware.org/?probe=a8f42a3c96) | Sep 05, 2023 |
| HP            | Pavilion dv7                | Notebook    | [2d6aa7667d](https://linux-hardware.org/?probe=2d6aa7667d) | Sep 05, 2023 |
| Foxconn       | 2AB1                        | Desktop     | [5c43d49876](https://linux-hardware.org/?probe=5c43d49876) | Sep 05, 2023 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | Notebook    | [1a1c5e43bc](https://linux-hardware.org/?probe=1a1c5e43bc) | Sep 05, 2023 |
| Gigabyte      | H310M H                     | Desktop     | [47b2450a3e](https://linux-hardware.org/?probe=47b2450a3e) | Sep 05, 2023 |
| Google        | Treeya                      | Notebook    | [fcc8d7d8a1](https://linux-hardware.org/?probe=fcc8d7d8a1) | Sep 05, 2023 |
| Inter Sale... | NID-11125DE                 | Notebook    | [2c94bcc096](https://linux-hardware.org/?probe=2c94bcc096) | Sep 05, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [8a98029595](https://linux-hardware.org/?probe=8a98029595) | Sep 05, 2023 |
| Apple         | Mac-F2218EA9                | All in one  | [db9fa6ee49](https://linux-hardware.org/?probe=db9fa6ee49) | Sep 04, 2023 |
| ASUSTek       | TALAS                       | Desktop     | [094153c6f4](https://linux-hardware.org/?probe=094153c6f4) | Sep 04, 2023 |
| Dell          | Precision 5570              | Notebook    | [abddf843dd](https://linux-hardware.org/?probe=abddf843dd) | Sep 04, 2023 |
| Dell          | 06D7TR A02                  | Desktop     | [a99e7ffcb1](https://linux-hardware.org/?probe=a99e7ffcb1) | Sep 04, 2023 |
| TUXEDO        | Unknown                     | Notebook    | [c6b62e2a29](https://linux-hardware.org/?probe=c6b62e2a29) | Sep 04, 2023 |
| HP            | Pavilion dv9000 (RP249UA... | Notebook    | [ea5e3bac5f](https://linux-hardware.org/?probe=ea5e3bac5f) | Sep 04, 2023 |
| ASUSTek       | X75VC                       | Notebook    | [0830aad0cc](https://linux-hardware.org/?probe=0830aad0cc) | Sep 04, 2023 |
| HP            | 2ADE                        | Desktop     | [f7b01f93c4](https://linux-hardware.org/?probe=f7b01f93c4) | Sep 04, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [39c78902f1](https://linux-hardware.org/?probe=39c78902f1) | Sep 04, 2023 |
| HP            | 8158 A01                    | Mini pc     | [de8c371188](https://linux-hardware.org/?probe=de8c371188) | Sep 04, 2023 |
| Dell          | Inspiron 7580               | Notebook    | [b021fe57a6](https://linux-hardware.org/?probe=b021fe57a6) | Sep 04, 2023 |
| Lenovo        | ThinkPad E520 11433FU       | Notebook    | [ecc10a1197](https://linux-hardware.org/?probe=ecc10a1197) | Sep 04, 2023 |
| MACHINIST     | X99-K9 V2.0                 | Desktop     | [3462791aa1](https://linux-hardware.org/?probe=3462791aa1) | Sep 04, 2023 |
| Dell          | 0773VG A00                  | Desktop     | [426a2f4142](https://linux-hardware.org/?probe=426a2f4142) | Sep 04, 2023 |
| Lenovo        | IdeaPad S400 Touch VIUS3    | Notebook    | [d2ac233994](https://linux-hardware.org/?probe=d2ac233994) | Sep 04, 2023 |
| Acer          | Aspire 8930                 | Notebook    | [9901032e2b](https://linux-hardware.org/?probe=9901032e2b) | Sep 04, 2023 |
| Prestigio     | Smartbook PSB116A           | Notebook    | [d70df77a35](https://linux-hardware.org/?probe=d70df77a35) | Sep 04, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [37e16bb39c](https://linux-hardware.org/?probe=37e16bb39c) | Sep 04, 2023 |
| Monster       | Huma H5 V3.2                | Notebook    | [75d95e264e](https://linux-hardware.org/?probe=75d95e264e) | Sep 04, 2023 |
| ASRock        | H61M-DGS R2.0               | Desktop     | [3edb7718df](https://linux-hardware.org/?probe=3edb7718df) | Sep 04, 2023 |
| Dell          | 0M6C7G A00                  | Desktop     | [8645b925c9](https://linux-hardware.org/?probe=8645b925c9) | Sep 04, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [30f66c7581](https://linux-hardware.org/?probe=30f66c7581) | Sep 04, 2023 |
| MSI           | B360M BAZOOKA               | Desktop     | [bdb68056ae](https://linux-hardware.org/?probe=bdb68056ae) | Sep 04, 2023 |
| Acer          | Aspire 7741                 | Notebook    | [0b3868c6bc](https://linux-hardware.org/?probe=0b3868c6bc) | Sep 04, 2023 |
| Lenovo        | ThinkCentre M58p 7484AEF    | Desktop     | [ccffd7e998](https://linux-hardware.org/?probe=ccffd7e998) | Sep 04, 2023 |
| Apple         | MacBookAir5,1               | Notebook    | [e24382ee44](https://linux-hardware.org/?probe=e24382ee44) | Sep 04, 2023 |
| Dell          | Latitude E5570              | Notebook    | [b4ca89038c](https://linux-hardware.org/?probe=b4ca89038c) | Sep 03, 2023 |
| Lenovo        | ThinkPad X220 42902WG       | Notebook    | [2326c36d78](https://linux-hardware.org/?probe=2326c36d78) | Sep 03, 2023 |
| Star Labs     | StarBook                    | Notebook    | [ac568bfcd4](https://linux-hardware.org/?probe=ac568bfcd4) | Sep 03, 2023 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [522a10f139](https://linux-hardware.org/?probe=522a10f139) | Sep 03, 2023 |
| Acer          | Aspire 5750Z                | Notebook    | [f0b466e572](https://linux-hardware.org/?probe=f0b466e572) | Sep 03, 2023 |
| Medion        | Akoya E4214 MD99570         | Notebook    | [1454b9c6a8](https://linux-hardware.org/?probe=1454b9c6a8) | Sep 03, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [d8b388ed5f](https://linux-hardware.org/?probe=d8b388ed5f) | Sep 03, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [94da12d8d8](https://linux-hardware.org/?probe=94da12d8d8) | Sep 03, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [a724d32006](https://linux-hardware.org/?probe=a724d32006) | Sep 03, 2023 |
| Dell          | Latitude E6400              | Notebook    | [9903b0fbea](https://linux-hardware.org/?probe=9903b0fbea) | Sep 03, 2023 |
| MSI           | Delta 15 A5EFK              | Notebook    | [8d2e359aec](https://linux-hardware.org/?probe=8d2e359aec) | Sep 03, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [024e3beca4](https://linux-hardware.org/?probe=024e3beca4) | Sep 03, 2023 |
| Thomson       | N14C4WH64                   | Notebook    | [3a5fd5b62b](https://linux-hardware.org/?probe=3a5fd5b62b) | Sep 03, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [88673d4088](https://linux-hardware.org/?probe=88673d4088) | Sep 03, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [6ed47558ae](https://linux-hardware.org/?probe=6ed47558ae) | Sep 03, 2023 |
| Dell          | 0VHWTR A02                  | Desktop     | [be2e4d0e02](https://linux-hardware.org/?probe=be2e4d0e02) | Sep 03, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [439817c540](https://linux-hardware.org/?probe=439817c540) | Sep 03, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [ca5351b378](https://linux-hardware.org/?probe=ca5351b378) | Sep 03, 2023 |
| Gigabyte      | H310M H                     | Desktop     | [ab3739f4e8](https://linux-hardware.org/?probe=ab3739f4e8) | Sep 03, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [eaac06d18a](https://linux-hardware.org/?probe=eaac06d18a) | Sep 03, 2023 |
| Thomson       | N14C4WH64                   | Notebook    | [cdfa5060e6](https://linux-hardware.org/?probe=cdfa5060e6) | Sep 03, 2023 |
| HP            | Pavilion dv5                | Notebook    | [977c253ff5](https://linux-hardware.org/?probe=977c253ff5) | Sep 02, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | Notebook    | [806eed53dc](https://linux-hardware.org/?probe=806eed53dc) | Sep 02, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | Notebook    | [377d5352d8](https://linux-hardware.org/?probe=377d5352d8) | Sep 02, 2023 |
| Dell          | Latitude E6540              | Notebook    | [f9e2147255](https://linux-hardware.org/?probe=f9e2147255) | Sep 02, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [fdb735b431](https://linux-hardware.org/?probe=fdb735b431) | Sep 02, 2023 |
| Dell          | Latitude 5285               | Notebook    | [f1f48163f3](https://linux-hardware.org/?probe=f1f48163f3) | Sep 02, 2023 |
| Microsoft     | Surface Pro 8               | Tablet      | [219bfdb3a5](https://linux-hardware.org/?probe=219bfdb3a5) | Sep 02, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [bf3a5838f0](https://linux-hardware.org/?probe=bf3a5838f0) | Sep 02, 2023 |
| MSI           | Z270 GAMING PRO CARBON      | Desktop     | [43a2fbe118](https://linux-hardware.org/?probe=43a2fbe118) | Sep 02, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [70f99195d8](https://linux-hardware.org/?probe=70f99195d8) | Sep 02, 2023 |
| HP            | Pavilion dv6                | Notebook    | [9190ad12c2](https://linux-hardware.org/?probe=9190ad12c2) | Sep 02, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [c612e70205](https://linux-hardware.org/?probe=c612e70205) | Sep 02, 2023 |
| ASUSTek       | P5P43TD                     | Desktop     | [f21550a5b3](https://linux-hardware.org/?probe=f21550a5b3) | Sep 02, 2023 |
| Gigabyte      | X299 UD4 Pro-CF             | Desktop     | [48c352470d](https://linux-hardware.org/?probe=48c352470d) | Sep 02, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [3143c94134](https://linux-hardware.org/?probe=3143c94134) | Sep 02, 2023 |
| Dell          | Precision 5540              | Notebook    | [3d800b12e0](https://linux-hardware.org/?probe=3d800b12e0) | Sep 02, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [b9765f73b1](https://linux-hardware.org/?probe=b9765f73b1) | Sep 02, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [affa07b412](https://linux-hardware.org/?probe=affa07b412) | Sep 02, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [33a04d3a73](https://linux-hardware.org/?probe=33a04d3a73) | Sep 02, 2023 |
| HP            | ProBook 470 G3              | Notebook    | [f6996b2905](https://linux-hardware.org/?probe=f6996b2905) | Sep 02, 2023 |
| Dell          | 0VNGWR A00                  | All in one  | [56445f0197](https://linux-hardware.org/?probe=56445f0197) | Sep 02, 2023 |
| Positivo      | POS-EIH610EX 11189814       | Desktop     | [e6a9006a72](https://linux-hardware.org/?probe=e6a9006a72) | Sep 01, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [0cfb9de0cf](https://linux-hardware.org/?probe=0cfb9de0cf) | Sep 01, 2023 |
| Lenovo        | ThinkPad L570 20J9S07N00    | Notebook    | [88d1350771](https://linux-hardware.org/?probe=88d1350771) | Sep 01, 2023 |
| HP            | 3397                        | Desktop     | [181c80a502](https://linux-hardware.org/?probe=181c80a502) | Sep 01, 2023 |
| ASUSTek       | X555LJ                      | Notebook    | [571cdd8ecf](https://linux-hardware.org/?probe=571cdd8ecf) | Sep 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [de36e26c21](https://linux-hardware.org/?probe=de36e26c21) | Sep 01, 2023 |
| Lenovo        | ThinkPad L570 20J9S07N00    | Notebook    | [fe660fb390](https://linux-hardware.org/?probe=fe660fb390) | Sep 01, 2023 |
| Fujitsu       | D3501-A1 S26361-D3501-A1    | Desktop     | [e7a06bde4e](https://linux-hardware.org/?probe=e7a06bde4e) | Sep 01, 2023 |
| Dell          | G15 5520                    | Notebook    | [9cfb8ce55a](https://linux-hardware.org/?probe=9cfb8ce55a) | Sep 01, 2023 |
| Positivo      | POS-EIH610EX 11189814       | Desktop     | [e222369e70](https://linux-hardware.org/?probe=e222369e70) | Sep 01, 2023 |
| Lenovo        | IdeaPad 1 14ADA7 82R0       | Notebook    | [d70ba1aaf4](https://linux-hardware.org/?probe=d70ba1aaf4) | Sep 01, 2023 |
| eMachines     | eME442                      | Notebook    | [7b765f910c](https://linux-hardware.org/?probe=7b765f910c) | Sep 01, 2023 |
| HP            | 339A                        | Desktop     | [e4423b3eb7](https://linux-hardware.org/?probe=e4423b3eb7) | Sep 01, 2023 |
| Gigabyte      | B560M AORUS PRO AX          | Desktop     | [2180bc1b72](https://linux-hardware.org/?probe=2180bc1b72) | Sep 01, 2023 |
| Apple         | MacBookPro5,2               | Notebook    | [35df364c39](https://linux-hardware.org/?probe=35df364c39) | Sep 01, 2023 |
| Acer          | Aspire V3-771               | Notebook    | [67082ec830](https://linux-hardware.org/?probe=67082ec830) | Sep 01, 2023 |
| HP            | Pavilion 13                 | Notebook    | [ccf98e410b](https://linux-hardware.org/?probe=ccf98e410b) | Sep 01, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [0a715ba5aa](https://linux-hardware.org/?probe=0a715ba5aa) | Sep 01, 2023 |
| HP            | Pavilion 13                 | Notebook    | [b3e756ad21](https://linux-hardware.org/?probe=b3e756ad21) | Sep 01, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [183c66be85](https://linux-hardware.org/?probe=183c66be85) | Sep 01, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | Desktop     | [6434195348](https://linux-hardware.org/?probe=6434195348) | Sep 01, 2023 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [6f84a1d68f](https://linux-hardware.org/?probe=6f84a1d68f) | Sep 01, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [17e3dd86e8](https://linux-hardware.org/?probe=17e3dd86e8) | Sep 01, 2023 |
| Google        | Barla                       | Notebook    | [1beaca005d](https://linux-hardware.org/?probe=1beaca005d) | Sep 01, 2023 |
| HP            | 1489                        | All in one  | [c53e87bce8](https://linux-hardware.org/?probe=c53e87bce8) | Sep 01, 2023 |
| HP            | Presario CQ43               | Notebook    | [9a02828a68](https://linux-hardware.org/?probe=9a02828a68) | Sep 01, 2023 |
| Foxconn       | 2AB1                        | Desktop     | [c140c2b911](https://linux-hardware.org/?probe=c140c2b911) | Sep 01, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [0265cb5d01](https://linux-hardware.org/?probe=0265cb5d01) | Aug 31, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [5cb3aa2368](https://linux-hardware.org/?probe=5cb3aa2368) | Aug 31, 2023 |
| HP            | Laptop 14-bw0xx             | Notebook    | [38db2f9e44](https://linux-hardware.org/?probe=38db2f9e44) | Aug 31, 2023 |
| Acer          | Aspire E5-475G              | Notebook    | [55542f9b89](https://linux-hardware.org/?probe=55542f9b89) | Aug 31, 2023 |
| Notebook      | N9x0TC                      | Notebook    | [f37b35c8dc](https://linux-hardware.org/?probe=f37b35c8dc) | Aug 31, 2023 |
| Dell          | 0P01GV A03                  | Desktop     | [ef4d28f614](https://linux-hardware.org/?probe=ef4d28f614) | Aug 31, 2023 |
| MSI           | X299 SLI PLUS               | Desktop     | [572982299a](https://linux-hardware.org/?probe=572982299a) | Aug 31, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | Notebook    | [ed4fafcabd](https://linux-hardware.org/?probe=ed4fafcabd) | Aug 31, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [4b7cee7673](https://linux-hardware.org/?probe=4b7cee7673) | Aug 31, 2023 |
| Lenovo        | ThinkPad X200 7458AL7       | Notebook    | [763d0f46f4](https://linux-hardware.org/?probe=763d0f46f4) | Aug 31, 2023 |
| ASUSTek       | K53SD                       | Notebook    | [05b083817c](https://linux-hardware.org/?probe=05b083817c) | Aug 31, 2023 |
| MSI           | B360M BAZOOKA               | Desktop     | [7d7d03eb25](https://linux-hardware.org/?probe=7d7d03eb25) | Aug 31, 2023 |
| Dell          | G3 3590                     | Notebook    | [810c7d1698](https://linux-hardware.org/?probe=810c7d1698) | Aug 31, 2023 |
| Lenovo        | 3716 SDK0R32862 WIN 3258... | Desktop     | [0464aa909a](https://linux-hardware.org/?probe=0464aa909a) | Aug 31, 2023 |
| HP            | 843B                        | Desktop     | [472228092a](https://linux-hardware.org/?probe=472228092a) | Aug 31, 2023 |
| Notebook      | W230SS                      | Notebook    | [97cc6cc17f](https://linux-hardware.org/?probe=97cc6cc17f) | Aug 31, 2023 |
| Dell          | Latitude 7230 Rugged Ext... | Convertible | [eedd1f9605](https://linux-hardware.org/?probe=eedd1f9605) | Aug 31, 2023 |
| MSI           | X470 GAMING PRO             | Desktop     | [408707e9e6](https://linux-hardware.org/?probe=408707e9e6) | Aug 31, 2023 |
| MSI           | X470 GAMING PRO             | Desktop     | [b00577f6ea](https://linux-hardware.org/?probe=b00577f6ea) | Aug 31, 2023 |
| ASUSTek       | X555LJ                      | Notebook    | [49b0bd793d](https://linux-hardware.org/?probe=49b0bd793d) | Aug 31, 2023 |
| MSI           | GS70 2OD                    | Notebook    | [1bc4bba326](https://linux-hardware.org/?probe=1bc4bba326) | Aug 31, 2023 |
| Dell          | 08WKV3 A00                  | Desktop     | [31138e2c0a](https://linux-hardware.org/?probe=31138e2c0a) | Aug 31, 2023 |
| ASUSTek       | P6T6 WS REVOLUTION          | Desktop     | [cff4daa814](https://linux-hardware.org/?probe=cff4daa814) | Aug 30, 2023 |
| Acer          | Predator PH517-51           | Notebook    | [294343383a](https://linux-hardware.org/?probe=294343383a) | Aug 30, 2023 |
| Acer          | Predator PH517-51           | Notebook    | [adba295596](https://linux-hardware.org/?probe=adba295596) | Aug 30, 2023 |
| ASUSTek       | K53SD                       | Notebook    | [f6f76a2e9d](https://linux-hardware.org/?probe=f6f76a2e9d) | Aug 30, 2023 |
| Acer          | Aspire V3-112P              | Notebook    | [d0d0600273](https://linux-hardware.org/?probe=d0d0600273) | Aug 30, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [c5469a2eaf](https://linux-hardware.org/?probe=c5469a2eaf) | Aug 30, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [3977e85dce](https://linux-hardware.org/?probe=3977e85dce) | Aug 30, 2023 |
| Lenovo        | 3716 SDK0T76463 WIN 3422... | Desktop     | [3aefc3000a](https://linux-hardware.org/?probe=3aefc3000a) | Aug 30, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [afb724c8da](https://linux-hardware.org/?probe=afb724c8da) | Aug 30, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [4ac0615cbb](https://linux-hardware.org/?probe=4ac0615cbb) | Aug 30, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [4bedf20d35](https://linux-hardware.org/?probe=4bedf20d35) | Aug 30, 2023 |
| Acidanther... | Mac-7BA5B2D9E42DDD94 iMa... | All in one  | [abfe7c3f74](https://linux-hardware.org/?probe=abfe7c3f74) | Aug 30, 2023 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [a7b83b57e0](https://linux-hardware.org/?probe=a7b83b57e0) | Aug 30, 2023 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [d7860c1c92](https://linux-hardware.org/?probe=d7860c1c92) | Aug 30, 2023 |
| Lenovo        | ThinkPad T420 4236MBG       | Notebook    | [dc28b42a00](https://linux-hardware.org/?probe=dc28b42a00) | Aug 30, 2023 |
| Gigabyte      | H410M H V2                  | Desktop     | [3240f39404](https://linux-hardware.org/?probe=3240f39404) | Aug 30, 2023 |
| Google        | Liara                       | Notebook    | [e92684405f](https://linux-hardware.org/?probe=e92684405f) | Aug 30, 2023 |
| Gigabyte      | H410M H V2                  | Desktop     | [14fce9ff7f](https://linux-hardware.org/?probe=14fce9ff7f) | Aug 30, 2023 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | Notebook    | [d37f105f74](https://linux-hardware.org/?probe=d37f105f74) | Aug 30, 2023 |
| Gigabyte      | Z77-D3H                     | Desktop     | [b61285544c](https://linux-hardware.org/?probe=b61285544c) | Aug 30, 2023 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | Notebook    | [de34a44939](https://linux-hardware.org/?probe=de34a44939) | Aug 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [abdd8929db](https://linux-hardware.org/?probe=abdd8929db) | Aug 29, 2023 |
| Gigabyte      | B650M DS3H                  | Desktop     | [bd11422cd5](https://linux-hardware.org/?probe=bd11422cd5) | Aug 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [48450e1a26](https://linux-hardware.org/?probe=48450e1a26) | Aug 29, 2023 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | Notebook    | [776efe803f](https://linux-hardware.org/?probe=776efe803f) | Aug 29, 2023 |
| Lenovo        | ThinkCentre M57 6087D44     | Desktop     | [0b30efa677](https://linux-hardware.org/?probe=0b30efa677) | Aug 29, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [78d168c88e](https://linux-hardware.org/?probe=78d168c88e) | Aug 29, 2023 |
| Dell          | Latitude 7440               | Convertible | [3021c76410](https://linux-hardware.org/?probe=3021c76410) | Aug 29, 2023 |
| Gigabyte      | H81M-D2V                    | Desktop     | [079adcbbe9](https://linux-hardware.org/?probe=079adcbbe9) | Aug 29, 2023 |
| HP            | 8953                        | Desktop     | [7f0a271e35](https://linux-hardware.org/?probe=7f0a271e35) | Aug 29, 2023 |
| Dell          | 0JCTF8 A00                  | Desktop     | [c76c74b017](https://linux-hardware.org/?probe=c76c74b017) | Aug 29, 2023 |
| HP            | Pavilion TS Sleekbook 14    | Notebook    | [c7108a7a23](https://linux-hardware.org/?probe=c7108a7a23) | Aug 29, 2023 |
| Gigabyte      | GA-880GA-UD3H               | Desktop     | [183437f6de](https://linux-hardware.org/?probe=183437f6de) | Aug 29, 2023 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [599a95cff7](https://linux-hardware.org/?probe=599a95cff7) | Aug 29, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [0af7d6ee0b](https://linux-hardware.org/?probe=0af7d6ee0b) | Aug 28, 2023 |
| HP            | Split 13 x2 PC              | Notebook    | [ab71a69e7e](https://linux-hardware.org/?probe=ab71a69e7e) | Aug 28, 2023 |
| MSI           | H310M PRO-VD                | Desktop     | [ebcf95d8ae](https://linux-hardware.org/?probe=ebcf95d8ae) | Aug 28, 2023 |
| MSI           | H310M PRO-VD                | Desktop     | [ef8ecfcb2e](https://linux-hardware.org/?probe=ef8ecfcb2e) | Aug 28, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [8c1bc17ecf](https://linux-hardware.org/?probe=8c1bc17ecf) | Aug 28, 2023 |
| Google        | Treeya                      | Notebook    | [396f71a402](https://linux-hardware.org/?probe=396f71a402) | Aug 28, 2023 |
| ASUSTek       | P5Q                         | Desktop     | [8b814da79a](https://linux-hardware.org/?probe=8b814da79a) | Aug 28, 2023 |
| Dell          | 0TTDMJ A00                  | Desktop     | [3dc47e2b77](https://linux-hardware.org/?probe=3dc47e2b77) | Aug 28, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [4c46f7ae80](https://linux-hardware.org/?probe=4c46f7ae80) | Aug 28, 2023 |
| HP            | 1791                        | Desktop     | [09c2abafde](https://linux-hardware.org/?probe=09c2abafde) | Aug 28, 2023 |
| HP            | Split 13 x2 PC              | Notebook    | [3df006557e](https://linux-hardware.org/?probe=3df006557e) | Aug 28, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [a102cdc504](https://linux-hardware.org/?probe=a102cdc504) | Aug 28, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CBA... | Notebook    | [8cbbb0c64a](https://linux-hardware.org/?probe=8cbbb0c64a) | Aug 28, 2023 |
| Dell          | 0J3C2F A02                  | Desktop     | [fcc6b1f4f5](https://linux-hardware.org/?probe=fcc6b1f4f5) | Aug 28, 2023 |
| Dell          | Inspiron 7786               | Convertible | [7c0752795f](https://linux-hardware.org/?probe=7c0752795f) | Aug 28, 2023 |
| ASRock        | B450M-HDV                   | Desktop     | [8ed8031a41](https://linux-hardware.org/?probe=8ed8031a41) | Aug 28, 2023 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [60fddabe34](https://linux-hardware.org/?probe=60fddabe34) | Aug 28, 2023 |
| HP            | 0AACh                       | Desktop     | [3522f0be02](https://linux-hardware.org/?probe=3522f0be02) | Aug 28, 2023 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [cbf222bbf8](https://linux-hardware.org/?probe=cbf222bbf8) | Aug 28, 2023 |
| Dell          | Inspiron 1501               | Notebook    | [a021a98920](https://linux-hardware.org/?probe=a021a98920) | Aug 27, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [8db29b3719](https://linux-hardware.org/?probe=8db29b3719) | Aug 27, 2023 |
| Gateway       | RS780                       | Desktop     | [aecf72fc15](https://linux-hardware.org/?probe=aecf72fc15) | Aug 27, 2023 |
| NSX           | SB142G                      | Notebook    | [43b576c576](https://linux-hardware.org/?probe=43b576c576) | Aug 27, 2023 |
| ASRock        | B450M-HDV                   | Desktop     | [3d2effa8c5](https://linux-hardware.org/?probe=3d2effa8c5) | Aug 27, 2023 |
| HP            | 21D0                        | Desktop     | [c6cd8d13bc](https://linux-hardware.org/?probe=c6cd8d13bc) | Aug 27, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [a1caab6466](https://linux-hardware.org/?probe=a1caab6466) | Aug 27, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [215ff35620](https://linux-hardware.org/?probe=215ff35620) | Aug 27, 2023 |
| Lenovo        | ThinkPad X250 20CLS0MN0A    | Notebook    | [4cfb3bf1b1](https://linux-hardware.org/?probe=4cfb3bf1b1) | Aug 27, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [a27df9649c](https://linux-hardware.org/?probe=a27df9649c) | Aug 27, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [a83bd371c4](https://linux-hardware.org/?probe=a83bd371c4) | Aug 27, 2023 |
| Samsung       | 300E4M/300E4S/300E4L        | Notebook    | [633ddecba0](https://linux-hardware.org/?probe=633ddecba0) | Aug 27, 2023 |
| Toshiba       | Satellite Pro NB10-A-110    | Notebook    | [ce30f81084](https://linux-hardware.org/?probe=ce30f81084) | Aug 27, 2023 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [e58ca6a781](https://linux-hardware.org/?probe=e58ca6a781) | Aug 27, 2023 |
| Lenovo        | ThinkPad L590 20Q70019GE    | Notebook    | [7df198a7b4](https://linux-hardware.org/?probe=7df198a7b4) | Aug 27, 2023 |
| Dell          | 03NVJ6 A01                  | Desktop     | [00a28522c2](https://linux-hardware.org/?probe=00a28522c2) | Aug 27, 2023 |
| ASUSTek       | Z97-PRO                     | Desktop     | [033aa63d16](https://linux-hardware.org/?probe=033aa63d16) | Aug 27, 2023 |
| ASUSTek       | Z97-PRO                     | Desktop     | [e5600a4d2f](https://linux-hardware.org/?probe=e5600a4d2f) | Aug 27, 2023 |
| HP            | 1905                        | Desktop     | [f680d1c561](https://linux-hardware.org/?probe=f680d1c561) | Aug 27, 2023 |
| ASUSTek       | TP300LA                     | Notebook    | [7588e955e3](https://linux-hardware.org/?probe=7588e955e3) | Aug 27, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [f8a316e74c](https://linux-hardware.org/?probe=f8a316e74c) | Aug 27, 2023 |
| Apple         | MacBookPro9,1               | Notebook    | [20eda7fab5](https://linux-hardware.org/?probe=20eda7fab5) | Aug 26, 2023 |
| Dell          | 0782GW A00                  | Desktop     | [038c293f3b](https://linux-hardware.org/?probe=038c293f3b) | Aug 26, 2023 |
| Dell          | 0782GW A00                  | Desktop     | [4b8fa7c22e](https://linux-hardware.org/?probe=4b8fa7c22e) | Aug 26, 2023 |
| HP            | 3397                        | Desktop     | [59d80acf6f](https://linux-hardware.org/?probe=59d80acf6f) | Aug 26, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [6f81752b36](https://linux-hardware.org/?probe=6f81752b36) | Aug 26, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [c859974eed](https://linux-hardware.org/?probe=c859974eed) | Aug 26, 2023 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [d8bb515dfb](https://linux-hardware.org/?probe=d8bb515dfb) | Aug 26, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 82BU      | Notebook    | [c0957b3538](https://linux-hardware.org/?probe=c0957b3538) | Aug 26, 2023 |
| Dell          | Precision M4800             | Notebook    | [89b88a1d3a](https://linux-hardware.org/?probe=89b88a1d3a) | Aug 26, 2023 |
| HP            | Notebook                    | Notebook    | [b27d20b450](https://linux-hardware.org/?probe=b27d20b450) | Aug 26, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS1... | Convertible | [6fee57bbb1](https://linux-hardware.org/?probe=6fee57bbb1) | Aug 26, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [5b1ded5f9e](https://linux-hardware.org/?probe=5b1ded5f9e) | Aug 26, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [a29a9ddeb6](https://linux-hardware.org/?probe=a29a9ddeb6) | Aug 26, 2023 |
| Fujitsu Si... | MS-7275-VB                  | Desktop     | [2b7a6dab27](https://linux-hardware.org/?probe=2b7a6dab27) | Aug 26, 2023 |
| Wortmann      | TERRA_MOBILE_1749           | Notebook    | [d58f29d427](https://linux-hardware.org/?probe=d58f29d427) | Aug 26, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [228c4e2d02](https://linux-hardware.org/?probe=228c4e2d02) | Aug 26, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [d494dfa98f](https://linux-hardware.org/?probe=d494dfa98f) | Aug 26, 2023 |
| MSI           | MAG B550 TORPEDO            | Desktop     | [01062889f6](https://linux-hardware.org/?probe=01062889f6) | Aug 26, 2023 |
| HP            | 1589                        | Desktop     | [3c19bc74f7](https://linux-hardware.org/?probe=3c19bc74f7) | Aug 26, 2023 |
| Samsung       | RV419/RV420                 | Notebook    | [77e9d34f16](https://linux-hardware.org/?probe=77e9d34f16) | Aug 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [b7cd2c007f](https://linux-hardware.org/?probe=b7cd2c007f) | Aug 26, 2023 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [eab204cfc9](https://linux-hardware.org/?probe=eab204cfc9) | Aug 26, 2023 |
| HP            | 84F5                        | Mini pc     | [2ba73e7bda](https://linux-hardware.org/?probe=2ba73e7bda) | Aug 26, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [b031f8f693](https://linux-hardware.org/?probe=b031f8f693) | Aug 25, 2023 |
| ZOTAC         | ZBOX-MI531/MI551/MI571 R... | Mini pc     | [aec073fccb](https://linux-hardware.org/?probe=aec073fccb) | Aug 25, 2023 |
| HP            | 84F5                        | Mini pc     | [314beb9d40](https://linux-hardware.org/?probe=314beb9d40) | Aug 25, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [fc8e4dd4ff](https://linux-hardware.org/?probe=fc8e4dd4ff) | Aug 25, 2023 |
| Fujitsu Si... | MS-7275-VB                  | Desktop     | [2a67da7ab4](https://linux-hardware.org/?probe=2a67da7ab4) | Aug 25, 2023 |
| HUAWEI        | MACHR-WX9                   | Notebook    | [a8c4ca7aee](https://linux-hardware.org/?probe=a8c4ca7aee) | Aug 25, 2023 |
| HP            | 15                          | Notebook    | [76decc7899](https://linux-hardware.org/?probe=76decc7899) | Aug 25, 2023 |
| Samsung       | RV419/RV420                 | Notebook    | [275cd1500e](https://linux-hardware.org/?probe=275cd1500e) | Aug 25, 2023 |
| Dell          | 0T656F A01                  | Desktop     | [fe9ddfe6d0](https://linux-hardware.org/?probe=fe9ddfe6d0) | Aug 25, 2023 |
| Gigabyte      | Z68MX-UD2H-B3               | Desktop     | [93cce7551b](https://linux-hardware.org/?probe=93cce7551b) | Aug 25, 2023 |
| Fujitsu       | LIFEBOOK A530               | Notebook    | [01c6935221](https://linux-hardware.org/?probe=01c6935221) | Aug 25, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | Notebook    | [14805d08fd](https://linux-hardware.org/?probe=14805d08fd) | Aug 25, 2023 |
| Fujitsu       | D3501-A1 S26361-D3501-A1    | Desktop     | [43686cdaa0](https://linux-hardware.org/?probe=43686cdaa0) | Aug 25, 2023 |
| ASRock        | 775Dual-VSTA                | Desktop     | [8d36dd0fbb](https://linux-hardware.org/?probe=8d36dd0fbb) | Aug 25, 2023 |
| TUXEDO        | Unknown                     | Notebook    | [13bb5e57f4](https://linux-hardware.org/?probe=13bb5e57f4) | Aug 25, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [49769c9b38](https://linux-hardware.org/?probe=49769c9b38) | Aug 25, 2023 |
| Unknown       | HX90                        | Desktop     | [305cd9a7ed](https://linux-hardware.org/?probe=305cd9a7ed) | Aug 25, 2023 |
| Dell          | Inspiron 5547               | Notebook    | [1fde0105bf](https://linux-hardware.org/?probe=1fde0105bf) | Aug 25, 2023 |
| AZW           | SER V2.0                    | Mini pc     | [be2b9dc5de](https://linux-hardware.org/?probe=be2b9dc5de) | Aug 25, 2023 |
| Notebook      | W230SS                      | Notebook    | [a479847abb](https://linux-hardware.org/?probe=a479847abb) | Aug 25, 2023 |
| ASUSTek       | M11AD                       | Desktop     | [a107c7eb20](https://linux-hardware.org/?probe=a107c7eb20) | Aug 25, 2023 |
| Gigabyte      | Z690 AORUS ELITE AX         | Desktop     | [a36ead7d8d](https://linux-hardware.org/?probe=a36ead7d8d) | Aug 25, 2023 |
| PC Special... | Ionico 16                   | Notebook    | [78125c34b4](https://linux-hardware.org/?probe=78125c34b4) | Aug 25, 2023 |
| HP            | 3047h                       | Desktop     | [d5b03c1a66](https://linux-hardware.org/?probe=d5b03c1a66) | Aug 24, 2023 |
| Lenovo        | ThinkPad X12 Detachable ... | Tablet      | [0d42a5e51d](https://linux-hardware.org/?probe=0d42a5e51d) | Aug 24, 2023 |
| Dell          | 0M017G A00                  | Desktop     | [f5e52dc9f9](https://linux-hardware.org/?probe=f5e52dc9f9) | Aug 24, 2023 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [fbe986e246](https://linux-hardware.org/?probe=fbe986e246) | Aug 24, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [6788c79a8b](https://linux-hardware.org/?probe=6788c79a8b) | Aug 24, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [b490084efc](https://linux-hardware.org/?probe=b490084efc) | Aug 24, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [e75a175580](https://linux-hardware.org/?probe=e75a175580) | Aug 24, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [ff1bdfd1e3](https://linux-hardware.org/?probe=ff1bdfd1e3) | Aug 24, 2023 |
| Dell          | Vostro 2520                 | Notebook    | [96018ae096](https://linux-hardware.org/?probe=96018ae096) | Aug 24, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [12ac0bf5ed](https://linux-hardware.org/?probe=12ac0bf5ed) | Aug 24, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [f4af40c36f](https://linux-hardware.org/?probe=f4af40c36f) | Aug 24, 2023 |
| Google        | Rammus                      | Notebook    | [57b3596f63](https://linux-hardware.org/?probe=57b3596f63) | Aug 24, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [5f108773ec](https://linux-hardware.org/?probe=5f108773ec) | Aug 24, 2023 |
| Acer          | Aspire VN7-571G             | Notebook    | [c35939bf03](https://linux-hardware.org/?probe=c35939bf03) | Aug 24, 2023 |
| Acer          | Aspire VN7-571G             | Notebook    | [de43925ba1](https://linux-hardware.org/?probe=de43925ba1) | Aug 24, 2023 |
| Timi          | A35                         | Notebook    | [50e380e876](https://linux-hardware.org/?probe=50e380e876) | Aug 24, 2023 |
| Gateway       | ZX4800                      | All in one  | [8d9b55b788](https://linux-hardware.org/?probe=8d9b55b788) | Aug 24, 2023 |
| MSI           | PRO B660-A DDR4             | Desktop     | [8cab090504](https://linux-hardware.org/?probe=8cab090504) | Aug 24, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [3746b277b6](https://linux-hardware.org/?probe=3746b277b6) | Aug 24, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [3e241db8f7](https://linux-hardware.org/?probe=3e241db8f7) | Aug 24, 2023 |
| Gigabyte      | P67A-UD7-B3                 | Desktop     | [912d956729](https://linux-hardware.org/?probe=912d956729) | Aug 24, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | Desktop     | [c15e2ed529](https://linux-hardware.org/?probe=c15e2ed529) | Aug 24, 2023 |
| Lenovo        | ThinkPad T460 20FMA00F00    | Notebook    | [370de86ed7](https://linux-hardware.org/?probe=370de86ed7) | Aug 24, 2023 |
| MSI           | MAG Z390M MORTAR            | Desktop     | [91de6baf4d](https://linux-hardware.org/?probe=91de6baf4d) | Aug 24, 2023 |
| Dell          | Precision M4500             | Notebook    | [98b37ce3a4](https://linux-hardware.org/?probe=98b37ce3a4) | Aug 24, 2023 |
| Gigabyte      | G5 GE                       | Notebook    | [357d34e951](https://linux-hardware.org/?probe=357d34e951) | Aug 23, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [fae1a274d9](https://linux-hardware.org/?probe=fae1a274d9) | Aug 23, 2023 |
| HP            | EliteBook 8530w             | Notebook    | [3ee1fe77ce](https://linux-hardware.org/?probe=3ee1fe77ce) | Aug 23, 2023 |
| Apple         | MacBookPro8,3               | Notebook    | [3fa6f3e446](https://linux-hardware.org/?probe=3fa6f3e446) | Aug 23, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [38573350a3](https://linux-hardware.org/?probe=38573350a3) | Aug 23, 2023 |
| Gigabyte      | M68M-S2P                    | Desktop     | [25729bd4f8](https://linux-hardware.org/?probe=25729bd4f8) | Aug 23, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [5247fcf1af](https://linux-hardware.org/?probe=5247fcf1af) | Aug 23, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [210fe127bf](https://linux-hardware.org/?probe=210fe127bf) | Aug 23, 2023 |
| Dell          | 0F896N A02                  | Desktop     | [3c1e848d33](https://linux-hardware.org/?probe=3c1e848d33) | Aug 23, 2023 |
| HP            | 212B                        | Desktop     | [a186c2ccf3](https://linux-hardware.org/?probe=a186c2ccf3) | Aug 23, 2023 |
| ASUSTek       | SABERTOOTH Z87              | Desktop     | [62ac8a7715](https://linux-hardware.org/?probe=62ac8a7715) | Aug 23, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [f79de96905](https://linux-hardware.org/?probe=f79de96905) | Aug 23, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [38849e44bb](https://linux-hardware.org/?probe=38849e44bb) | Aug 23, 2023 |
| HP            | x2 210 G2                   | Tablet      | [a1ffe6462e](https://linux-hardware.org/?probe=a1ffe6462e) | Aug 23, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [7ef5fc5f0c](https://linux-hardware.org/?probe=7ef5fc5f0c) | Aug 23, 2023 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | Desktop     | [d094cbc19c](https://linux-hardware.org/?probe=d094cbc19c) | Aug 23, 2023 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [ab538d0486](https://linux-hardware.org/?probe=ab538d0486) | Aug 23, 2023 |
| Samsung       | 370E4K                      | Notebook    | [074e0669c7](https://linux-hardware.org/?probe=074e0669c7) | Aug 22, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [e751db6fd4](https://linux-hardware.org/?probe=e751db6fd4) | Aug 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [131e36d487](https://linux-hardware.org/?probe=131e36d487) | Aug 22, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [06b5fb7c7f](https://linux-hardware.org/?probe=06b5fb7c7f) | Aug 22, 2023 |
| Dell          | Vostro 5471                 | Notebook    | [342ccb8530](https://linux-hardware.org/?probe=342ccb8530) | Aug 22, 2023 |
| HP            | Laptop 17-by0xxx            | Notebook    | [5de161ca2f](https://linux-hardware.org/?probe=5de161ca2f) | Aug 22, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [df5037fab5](https://linux-hardware.org/?probe=df5037fab5) | Aug 22, 2023 |
| HP            | Victus by Laptop 16-d0xx... | Notebook    | [845b1d4d76](https://linux-hardware.org/?probe=845b1d4d76) | Aug 22, 2023 |
| Dell          | Precision M4500             | Notebook    | [71b77267fd](https://linux-hardware.org/?probe=71b77267fd) | Aug 22, 2023 |
| Acer          | Aspire 5250                 | Notebook    | [8812e20762](https://linux-hardware.org/?probe=8812e20762) | Aug 22, 2023 |
| Apple         | MacBookPro13,1              | Notebook    | [73c6fa6546](https://linux-hardware.org/?probe=73c6fa6546) | Aug 22, 2023 |
| HP            | x2 210 G2                   | Tablet      | [c0b004af0e](https://linux-hardware.org/?probe=c0b004af0e) | Aug 22, 2023 |
| Acer          | Aspire V3-771               | Notebook    | [0a5af3a07b](https://linux-hardware.org/?probe=0a5af3a07b) | Aug 22, 2023 |
| Toshiba       | Satellite P500              | Notebook    | [41efb0cb7b](https://linux-hardware.org/?probe=41efb0cb7b) | Aug 22, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | Notebook    | [e8ac7d1737](https://linux-hardware.org/?probe=e8ac7d1737) | Aug 22, 2023 |
| HP            | 255 G5                      | Notebook    | [d7087d2b8f](https://linux-hardware.org/?probe=d7087d2b8f) | Aug 22, 2023 |
| HP            | 255 G5                      | Notebook    | [b16f43457c](https://linux-hardware.org/?probe=b16f43457c) | Aug 22, 2023 |
| Lenovo        | 3190 SDK0J40697 WIN 3305... | Mini pc     | [4945bd0d6d](https://linux-hardware.org/?probe=4945bd0d6d) | Aug 22, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [443006ec08](https://linux-hardware.org/?probe=443006ec08) | Aug 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [60c353baa1](https://linux-hardware.org/?probe=60c353baa1) | Aug 22, 2023 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [fcc49817bc](https://linux-hardware.org/?probe=fcc49817bc) | Aug 22, 2023 |
| Dell          | Inspiron 3537               | Notebook    | [1ad6c0c6d3](https://linux-hardware.org/?probe=1ad6c0c6d3) | Aug 22, 2023 |
| ASUSTek       | ROG Maximus Z790 HERO       | Desktop     | [b4aa1b8daa](https://linux-hardware.org/?probe=b4aa1b8daa) | Aug 22, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [272e3307fe](https://linux-hardware.org/?probe=272e3307fe) | Aug 21, 2023 |
| Acer          | Aspire 5750Z                | Notebook    | [8c15b251a7](https://linux-hardware.org/?probe=8c15b251a7) | Aug 21, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [352d5c780f](https://linux-hardware.org/?probe=352d5c780f) | Aug 21, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [fa1f2a4b75](https://linux-hardware.org/?probe=fa1f2a4b75) | Aug 21, 2023 |
| Toshiba       | Satellite C55-A             | Notebook    | [ef61a3ae6a](https://linux-hardware.org/?probe=ef61a3ae6a) | Aug 21, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [156c7f4eae](https://linux-hardware.org/?probe=156c7f4eae) | Aug 21, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [c0e3693248](https://linux-hardware.org/?probe=c0e3693248) | Aug 21, 2023 |
| ASRock        | H61M-HVGS                   | Desktop     | [1d023bc980](https://linux-hardware.org/?probe=1d023bc980) | Aug 21, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | Notebook    | [feeca36aa9](https://linux-hardware.org/?probe=feeca36aa9) | Aug 21, 2023 |
| Dell          | Studio 1558                 | Notebook    | [cbc26edae2](https://linux-hardware.org/?probe=cbc26edae2) | Aug 21, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [c47971e406](https://linux-hardware.org/?probe=c47971e406) | Aug 21, 2023 |
| HP            | 8054                        | Desktop     | [d5582dbf37](https://linux-hardware.org/?probe=d5582dbf37) | Aug 21, 2023 |
| Dell          | Inspiron 5737               | Notebook    | [665dbda021](https://linux-hardware.org/?probe=665dbda021) | Aug 21, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [88f3fb7f10](https://linux-hardware.org/?probe=88f3fb7f10) | Aug 20, 2023 |
| Lenovo        | ThinkPad X230 2325H50       | Notebook    | [65dd59e7d2](https://linux-hardware.org/?probe=65dd59e7d2) | Aug 20, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [19a3daf111](https://linux-hardware.org/?probe=19a3daf111) | Aug 20, 2023 |
| Dell          | Inspiron 5447               | Notebook    | [811b2451ba](https://linux-hardware.org/?probe=811b2451ba) | Aug 20, 2023 |
| Acer          | Aspire 5750                 | Notebook    | [5b7f4b5a45](https://linux-hardware.org/?probe=5b7f4b5a45) | Aug 20, 2023 |
| Medion        | DEFENDER E10                | Notebook    | [8434727e07](https://linux-hardware.org/?probe=8434727e07) | Aug 20, 2023 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [a38d849208](https://linux-hardware.org/?probe=a38d849208) | Aug 20, 2023 |
| Kogan         | KAL14N360PA                 | Notebook    | [527a0d3cba](https://linux-hardware.org/?probe=527a0d3cba) | Aug 20, 2023 |
| ASUSTek       | K55A                        | Notebook    | [090e4d0a73](https://linux-hardware.org/?probe=090e4d0a73) | Aug 20, 2023 |
| Kogan         | KAL14N360PA                 | Notebook    | [b7cecb1518](https://linux-hardware.org/?probe=b7cecb1518) | Aug 20, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [04efd4ddec](https://linux-hardware.org/?probe=04efd4ddec) | Aug 20, 2023 |
| HP            | Laptop 17-by1xxx            | Notebook    | [658e65bba8](https://linux-hardware.org/?probe=658e65bba8) | Aug 20, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [30b645c7f4](https://linux-hardware.org/?probe=30b645c7f4) | Aug 20, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [47ed3b6bc8](https://linux-hardware.org/?probe=47ed3b6bc8) | Aug 20, 2023 |
| ASUSTek       | X540NA                      | Notebook    | [2f3758945b](https://linux-hardware.org/?probe=2f3758945b) | Aug 20, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [b2e1bdd7a8](https://linux-hardware.org/?probe=b2e1bdd7a8) | Aug 20, 2023 |
| HP            | Pavilion 15                 | Notebook    | [63e1b9e62c](https://linux-hardware.org/?probe=63e1b9e62c) | Aug 20, 2023 |
| Megaware      | MW-G31T-M7                  | Desktop     | [3bed885307](https://linux-hardware.org/?probe=3bed885307) | Aug 20, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [a435538cb2](https://linux-hardware.org/?probe=a435538cb2) | Aug 20, 2023 |
| HP            | 18E4                        | Desktop     | [e7d94d93c6](https://linux-hardware.org/?probe=e7d94d93c6) | Aug 20, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [3803f61627](https://linux-hardware.org/?probe=3803f61627) | Aug 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [4bd818cb75](https://linux-hardware.org/?probe=4bd818cb75) | Aug 20, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [86f9b36e03](https://linux-hardware.org/?probe=86f9b36e03) | Aug 20, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [dc96aa9cee](https://linux-hardware.org/?probe=dc96aa9cee) | Aug 19, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [54c2ded452](https://linux-hardware.org/?probe=54c2ded452) | Aug 19, 2023 |
| Intel         | NUC7i7BNB J31145-310        | Mini pc     | [5d5c525bd4](https://linux-hardware.org/?probe=5d5c525bd4) | Aug 19, 2023 |
| Megaware      | MW-G31T-M7                  | Desktop     | [774ca523db](https://linux-hardware.org/?probe=774ca523db) | Aug 19, 2023 |
| Chuwi         | LapBook SE                  | Notebook    | [8c338913ab](https://linux-hardware.org/?probe=8c338913ab) | Aug 19, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [a5af576c52](https://linux-hardware.org/?probe=a5af576c52) | Aug 19, 2023 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [66c64c5da8](https://linux-hardware.org/?probe=66c64c5da8) | Aug 19, 2023 |
| Dell          | 0200DY A02                  | Desktop     | [0182dad759](https://linux-hardware.org/?probe=0182dad759) | Aug 19, 2023 |
| Dell          | Inspiron 1501               | Notebook    | [48f17500e2](https://linux-hardware.org/?probe=48f17500e2) | Aug 19, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [030cbe1086](https://linux-hardware.org/?probe=030cbe1086) | Aug 19, 2023 |
| ASUSTek       | B250 MINING EXPERT          | Desktop     | [676140f030](https://linux-hardware.org/?probe=676140f030) | Aug 19, 2023 |
| Dell          | Latitude E7440              | Notebook    | [7a5bd0f1a6](https://linux-hardware.org/?probe=7a5bd0f1a6) | Aug 19, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [637bd422c5](https://linux-hardware.org/?probe=637bd422c5) | Aug 19, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [825225e1c4](https://linux-hardware.org/?probe=825225e1c4) | Aug 19, 2023 |
| HP            | 630                         | Notebook    | [ad9f585249](https://linux-hardware.org/?probe=ad9f585249) | Aug 19, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [68df495196](https://linux-hardware.org/?probe=68df495196) | Aug 19, 2023 |
| HP            | Pavilion g7                 | Notebook    | [05c25f464a](https://linux-hardware.org/?probe=05c25f464a) | Aug 19, 2023 |
| ASUSTek       | UX410UQK                    | Notebook    | [cf7a7946dc](https://linux-hardware.org/?probe=cf7a7946dc) | Aug 19, 2023 |
| Dell          | Latitude E6410              | Notebook    | [5ae66b0d4a](https://linux-hardware.org/?probe=5ae66b0d4a) | Aug 18, 2023 |
| Dell          | Latitude 5540               | Notebook    | [d1f00897b3](https://linux-hardware.org/?probe=d1f00897b3) | Aug 18, 2023 |
| Dell          | 0M017G A00                  | Desktop     | [d480387600](https://linux-hardware.org/?probe=d480387600) | Aug 18, 2023 |
| ASRock        | B660M Steel Legend          | Desktop     | [31c15ac9dd](https://linux-hardware.org/?probe=31c15ac9dd) | Aug 18, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [bb62633b47](https://linux-hardware.org/?probe=bb62633b47) | Aug 18, 2023 |
| Intel         | NUC11TNBv7 K87766-404       | Mini pc     | [a991f1ebf3](https://linux-hardware.org/?probe=a991f1ebf3) | Aug 18, 2023 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | Notebook    | [0dc75dae26](https://linux-hardware.org/?probe=0dc75dae26) | Aug 18, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [6947635a16](https://linux-hardware.org/?probe=6947635a16) | Aug 18, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [73867661a3](https://linux-hardware.org/?probe=73867661a3) | Aug 18, 2023 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | Desktop     | [e9b5fbc6ba](https://linux-hardware.org/?probe=e9b5fbc6ba) | Aug 18, 2023 |
| Biostar       | A68MHE                      | Desktop     | [9295c879b8](https://linux-hardware.org/?probe=9295c879b8) | Aug 18, 2023 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [82923ee337](https://linux-hardware.org/?probe=82923ee337) | Aug 18, 2023 |
| Lenovo        | ThinkCentre M90z 5205CTO    | All in one  | [7f7f077fda](https://linux-hardware.org/?probe=7f7f077fda) | Aug 18, 2023 |
| Lenovo        | ThinkCentre M90z 5205CTO    | All in one  | [2c4ded9440](https://linux-hardware.org/?probe=2c4ded9440) | Aug 18, 2023 |
| HP            | Pavilion dv5                | Notebook    | [edaeac5770](https://linux-hardware.org/?probe=edaeac5770) | Aug 18, 2023 |
| Acer          | Aspire 5534                 | Notebook    | [f007a289ff](https://linux-hardware.org/?probe=f007a289ff) | Aug 18, 2023 |
| Acer          | Aspire 5534                 | Notebook    | [a26436f976](https://linux-hardware.org/?probe=a26436f976) | Aug 18, 2023 |
| Acer          | Aspire M5-583P              | Notebook    | [9af5e802dc](https://linux-hardware.org/?probe=9af5e802dc) | Aug 18, 2023 |
| Acer          | Predator PH317-52           | Notebook    | [c942508cf0](https://linux-hardware.org/?probe=c942508cf0) | Aug 18, 2023 |
| HP            | 0B40h                       | Desktop     | [27ee0e32c4](https://linux-hardware.org/?probe=27ee0e32c4) | Aug 17, 2023 |
| Dell          | Latitude D630               | Notebook    | [e8f61a39e7](https://linux-hardware.org/?probe=e8f61a39e7) | Aug 17, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [4368fbfada](https://linux-hardware.org/?probe=4368fbfada) | Aug 17, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [6c31be997f](https://linux-hardware.org/?probe=6c31be997f) | Aug 17, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [e2078f93dd](https://linux-hardware.org/?probe=e2078f93dd) | Aug 17, 2023 |
| Dell          | Precision 5540              | Notebook    | [a0a36884a0](https://linux-hardware.org/?probe=a0a36884a0) | Aug 17, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [1739e9ff2d](https://linux-hardware.org/?probe=1739e9ff2d) | Aug 17, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [93f7041d2f](https://linux-hardware.org/?probe=93f7041d2f) | Aug 17, 2023 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [58afba6baf](https://linux-hardware.org/?probe=58afba6baf) | Aug 17, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [af0ba5f26c](https://linux-hardware.org/?probe=af0ba5f26c) | Aug 17, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [db86583c86](https://linux-hardware.org/?probe=db86583c86) | Aug 17, 2023 |
| Google        | Reef                        | Notebook    | [39c0a2d33c](https://linux-hardware.org/?probe=39c0a2d33c) | Aug 17, 2023 |
| Google        | Reef                        | Notebook    | [67909b7748](https://linux-hardware.org/?probe=67909b7748) | Aug 17, 2023 |
| Daten Tecn... | DV3N-4                      | Notebook    | [7a95cb94da](https://linux-hardware.org/?probe=7a95cb94da) | Aug 17, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [0438f450f4](https://linux-hardware.org/?probe=0438f450f4) | Aug 17, 2023 |
| HP            | 2B43                        | Desktop     | [2c3ffc174e](https://linux-hardware.org/?probe=2c3ffc174e) | Aug 17, 2023 |
| ASUSTek       | P5QL-ASUS-SE                | Desktop     | [3135a88431](https://linux-hardware.org/?probe=3135a88431) | Aug 17, 2023 |
| Lenovo        | ThinkPad X200 7459Y8Y       | Notebook    | [3a707993c2](https://linux-hardware.org/?probe=3a707993c2) | Aug 16, 2023 |
| Lenovo        | ThinkPad X200 7459Y8Y       | Notebook    | [2f98dd0ac1](https://linux-hardware.org/?probe=2f98dd0ac1) | Aug 16, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [f2209034c0](https://linux-hardware.org/?probe=f2209034c0) | Aug 16, 2023 |
| ASUSTek       | PRIME B360M-D               | Desktop     | [cf1c4e8c82](https://linux-hardware.org/?probe=cf1c4e8c82) | Aug 16, 2023 |
| ASRock        | H61M-DGS R2.0               | Desktop     | [ccd21d7858](https://linux-hardware.org/?probe=ccd21d7858) | Aug 16, 2023 |
| HP            | 1998                        | Desktop     | [b44d5aaf94](https://linux-hardware.org/?probe=b44d5aaf94) | Aug 16, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [bc22beda8a](https://linux-hardware.org/?probe=bc22beda8a) | Aug 16, 2023 |
| Lenovo        | ThinkPad X240 20AMS0J003    | Notebook    | [c60cb88cbc](https://linux-hardware.org/?probe=c60cb88cbc) | Aug 16, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D7S... | Notebook    | [6ada69d4d4](https://linux-hardware.org/?probe=6ada69d4d4) | Aug 16, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [6738589baa](https://linux-hardware.org/?probe=6738589baa) | Aug 16, 2023 |
| Gigabyte      | F2A88X-D3H                  | Desktop     | [0b6b39fa2d](https://linux-hardware.org/?probe=0b6b39fa2d) | Aug 16, 2023 |
| Acer          | Predator PT515-51           | Notebook    | [3eede93299](https://linux-hardware.org/?probe=3eede93299) | Aug 16, 2023 |
| Gigabyte      | GA-990FXA-UD3               | Desktop     | [0daae7dcb4](https://linux-hardware.org/?probe=0daae7dcb4) | Aug 16, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [52c59bb799](https://linux-hardware.org/?probe=52c59bb799) | Aug 16, 2023 |
| Lenovo        | 3716 SDK0R32862 WIN 3258... | Desktop     | [c3b704f3f0](https://linux-hardware.org/?probe=c3b704f3f0) | Aug 16, 2023 |
| HP            | 8054                        | Desktop     | [7a1fbf5ac4](https://linux-hardware.org/?probe=7a1fbf5ac4) | Aug 16, 2023 |
| Lenovo        | 3716 SDK0R32862 WIN 3258... | Desktop     | [016846c4b8](https://linux-hardware.org/?probe=016846c4b8) | Aug 16, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [6aa6913c91](https://linux-hardware.org/?probe=6aa6913c91) | Aug 16, 2023 |
| PC Special... | Ionico 16                   | Notebook    | [9f04bd8095](https://linux-hardware.org/?probe=9f04bd8095) | Aug 16, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [fc9b14b9cb](https://linux-hardware.org/?probe=fc9b14b9cb) | Aug 15, 2023 |
| ASUSTek       | Leonite2                    | Desktop     | [439a4ee1fb](https://linux-hardware.org/?probe=439a4ee1fb) | Aug 15, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [6c07b9bb4b](https://linux-hardware.org/?probe=6c07b9bb4b) | Aug 15, 2023 |
| Gigabyte      | X99-Designare EX-CF         | Desktop     | [41452cd53d](https://linux-hardware.org/?probe=41452cd53d) | Aug 15, 2023 |
| HP            | Pavilion Laptop 15-ck0xx    | Notebook    | [97ced089bf](https://linux-hardware.org/?probe=97ced089bf) | Aug 15, 2023 |
| Dell          | Inspiron 7590               | Notebook    | [4438df6adb](https://linux-hardware.org/?probe=4438df6adb) | Aug 15, 2023 |
| Intel         | S3420GP E51976-405          | Server      | [b14cc4b52a](https://linux-hardware.org/?probe=b14cc4b52a) | Aug 15, 2023 |
| Lenovo        | IdeaPad Slim 5 14ABR8 82... | Notebook    | [1fcc89106f](https://linux-hardware.org/?probe=1fcc89106f) | Aug 15, 2023 |
| Chuwi         | HeroBook Pro                | Notebook    | [0122fef8fd](https://linux-hardware.org/?probe=0122fef8fd) | Aug 15, 2023 |
| MSI           | 970A-G46                    | Desktop     | [d1b6347c9a](https://linux-hardware.org/?probe=d1b6347c9a) | Aug 15, 2023 |
| HP            | Elite x2 1012 G1            | Notebook    | [07f71a9888](https://linux-hardware.org/?probe=07f71a9888) | Aug 15, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [32a347b989](https://linux-hardware.org/?probe=32a347b989) | Aug 15, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [26a0de5b36](https://linux-hardware.org/?probe=26a0de5b36) | Aug 15, 2023 |
| ASUSTek       | PRIME B250M-K               | Desktop     | [e54e05ccb1](https://linux-hardware.org/?probe=e54e05ccb1) | Aug 15, 2023 |
| Lenovo        | 3307 SDK0J40700 WIN 3258... | Mini pc     | [8f8507e0a9](https://linux-hardware.org/?probe=8f8507e0a9) | Aug 15, 2023 |
| Mini PC       | Rev JSL5 DDR4               | Mini pc     | [891e757894](https://linux-hardware.org/?probe=891e757894) | Aug 15, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [290298fd99](https://linux-hardware.org/?probe=290298fd99) | Aug 15, 2023 |
| Dell          | 0J3C2F A02                  | Desktop     | [3fdd81216b](https://linux-hardware.org/?probe=3fdd81216b) | Aug 15, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [daed613536](https://linux-hardware.org/?probe=daed613536) | Aug 15, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [78e1dba498](https://linux-hardware.org/?probe=78e1dba498) | Aug 15, 2023 |
| Lenovo        | G580                        | Notebook    | [ceeee3c405](https://linux-hardware.org/?probe=ceeee3c405) | Aug 15, 2023 |
| Positivo      | S14CT01                     | Notebook    | [e865565207](https://linux-hardware.org/?probe=e865565207) | Aug 15, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [bf753b0310](https://linux-hardware.org/?probe=bf753b0310) | Aug 14, 2023 |
| ASUSTek       | H110T                       | Desktop     | [48d641f85c](https://linux-hardware.org/?probe=48d641f85c) | Aug 14, 2023 |
| MSI           | MS-B1831                    | Desktop     | [25e33380e5](https://linux-hardware.org/?probe=25e33380e5) | Aug 14, 2023 |
| Dynabook      | Satellite Pro C50-E-11H     | Notebook    | [589af795e9](https://linux-hardware.org/?probe=589af795e9) | Aug 14, 2023 |
| Dell          | Latitude E6420              | Notebook    | [176a9c4f6d](https://linux-hardware.org/?probe=176a9c4f6d) | Aug 14, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [b950177908](https://linux-hardware.org/?probe=b950177908) | Aug 14, 2023 |
| Gigabyte      | GA-990FXA-UD3               | Desktop     | [a8f732a826](https://linux-hardware.org/?probe=a8f732a826) | Aug 14, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [18d3d9a7c1](https://linux-hardware.org/?probe=18d3d9a7c1) | Aug 14, 2023 |
| Dell          | Inspiron 3537               | Notebook    | [0cd8f644e2](https://linux-hardware.org/?probe=0cd8f644e2) | Aug 14, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [0be611b499](https://linux-hardware.org/?probe=0be611b499) | Aug 14, 2023 |
| HP            | 225E                        | Desktop     | [293a079528](https://linux-hardware.org/?probe=293a079528) | Aug 14, 2023 |
| HP            | 225E                        | Desktop     | [0a353f94ec](https://linux-hardware.org/?probe=0a353f94ec) | Aug 14, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | Notebook    | [cfc638b4b2](https://linux-hardware.org/?probe=cfc638b4b2) | Aug 14, 2023 |
| Positivo      | Mobile                      | Notebook    | [4111fa6520](https://linux-hardware.org/?probe=4111fa6520) | Aug 14, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [c342e06960](https://linux-hardware.org/?probe=c342e06960) | Aug 14, 2023 |
| Toshiba       | Satellite C55-A             | Notebook    | [8db92e82f6](https://linux-hardware.org/?probe=8db92e82f6) | Aug 14, 2023 |
| Gigabyte      | B760 GAMING X AX            | Desktop     | [fd4109923b](https://linux-hardware.org/?probe=fd4109923b) | Aug 14, 2023 |
| Gigabyte      | B760 GAMING X AX            | Desktop     | [c2d8da14dd](https://linux-hardware.org/?probe=c2d8da14dd) | Aug 14, 2023 |
| MSI           | Z170A XPOWER GAMING TITA... | Desktop     | [b6e0b821b8](https://linux-hardware.org/?probe=b6e0b821b8) | Aug 14, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [aadb9e5aab](https://linux-hardware.org/?probe=aadb9e5aab) | Aug 14, 2023 |
| GPU Compan... | GWTN156-5                   | Notebook    | [a1d052746a](https://linux-hardware.org/?probe=a1d052746a) | Aug 13, 2023 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [7decc8ad48](https://linux-hardware.org/?probe=7decc8ad48) | Aug 13, 2023 |
| Acer          | Extensa 5635Z               | Notebook    | [e1a35ce655](https://linux-hardware.org/?probe=e1a35ce655) | Aug 13, 2023 |
| BANGHO        | MOV                         | Notebook    | [db4769bd96](https://linux-hardware.org/?probe=db4769bd96) | Aug 13, 2023 |
| Samsung       | 300E4A/300E5A/300E7A        | Notebook    | [3bb3eaed7b](https://linux-hardware.org/?probe=3bb3eaed7b) | Aug 13, 2023 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [498a7e3ab4](https://linux-hardware.org/?probe=498a7e3ab4) | Aug 13, 2023 |
| Gigabyte      | B450 GAMING X               | Desktop     | [d6cfe894c9](https://linux-hardware.org/?probe=d6cfe894c9) | Aug 13, 2023 |
| Intel         | H61                         | Desktop     | [0f81745861](https://linux-hardware.org/?probe=0f81745861) | Aug 13, 2023 |
| HP            | 450                         | Notebook    | [242d41f5e9](https://linux-hardware.org/?probe=242d41f5e9) | Aug 13, 2023 |
| ASUSTek       | H170I-PRO                   | Desktop     | [c88cafa2a4](https://linux-hardware.org/?probe=c88cafa2a4) | Aug 13, 2023 |
| Intel         | H61                         | Desktop     | [cbf83ef64b](https://linux-hardware.org/?probe=cbf83ef64b) | Aug 13, 2023 |
| Dell          | Latitude E6410              | Notebook    | [8ed9952374](https://linux-hardware.org/?probe=8ed9952374) | Aug 13, 2023 |
| Dell          | Inspiron 5584               | Notebook    | [9fb83333a5](https://linux-hardware.org/?probe=9fb83333a5) | Aug 13, 2023 |
| Dell          | Precision M4500             | Notebook    | [a19e0d5977](https://linux-hardware.org/?probe=a19e0d5977) | Aug 13, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [837cbb2cf1](https://linux-hardware.org/?probe=837cbb2cf1) | Aug 13, 2023 |
| Foxconn       | 2AB1                        | Desktop     | [fdff550fcd](https://linux-hardware.org/?probe=fdff550fcd) | Aug 13, 2023 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [df9fab1b5b](https://linux-hardware.org/?probe=df9fab1b5b) | Aug 13, 2023 |
| Gigabyte      | GA-990FXA-UD3               | Desktop     | [eedc2f2406](https://linux-hardware.org/?probe=eedc2f2406) | Aug 13, 2023 |
| Thomson       | X6-4.32GR                   | Notebook    | [454fdb4295](https://linux-hardware.org/?probe=454fdb4295) | Aug 13, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [4eeea4cc95](https://linux-hardware.org/?probe=4eeea4cc95) | Aug 13, 2023 |
| Sony          | VPCEH14FM                   | Notebook    | [4709dcb41d](https://linux-hardware.org/?probe=4709dcb41d) | Aug 13, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [5f03e49c03](https://linux-hardware.org/?probe=5f03e49c03) | Aug 13, 2023 |
| Unknown       | Unknown                     | Notebook    | [920fb19700](https://linux-hardware.org/?probe=920fb19700) | Aug 12, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [b296a33ab3](https://linux-hardware.org/?probe=b296a33ab3) | Aug 12, 2023 |
| BESSTAR Te... | TH50                        | Desktop     | [dd2c1243af](https://linux-hardware.org/?probe=dd2c1243af) | Aug 12, 2023 |
| Unknown       | Unknown                     | Notebook    | [21abd7288e](https://linux-hardware.org/?probe=21abd7288e) | Aug 12, 2023 |
| ASRock        | H61M-DGS R2.0               | Desktop     | [6af1365446](https://linux-hardware.org/?probe=6af1365446) | Aug 12, 2023 |
| ASRock        | H61M-DGS R2.0               | Desktop     | [70e9fe8cdb](https://linux-hardware.org/?probe=70e9fe8cdb) | Aug 12, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [cec4c72ebb](https://linux-hardware.org/?probe=cec4c72ebb) | Aug 12, 2023 |
| Gigabyte      | F2A88XN-WIFI                | Desktop     | [8ba1a47cc3](https://linux-hardware.org/?probe=8ba1a47cc3) | Aug 12, 2023 |
| Gigabyte      | F2A88XN-WIFI                | Desktop     | [adb95a05c5](https://linux-hardware.org/?probe=adb95a05c5) | Aug 12, 2023 |
| Multilaser    | PC024                       | Notebook    | [3311e26ac5](https://linux-hardware.org/?probe=3311e26ac5) | Aug 12, 2023 |
| HP            | ProLiant ML350 G5           | Desktop     | [e9e8c3e5a7](https://linux-hardware.org/?probe=e9e8c3e5a7) | Aug 12, 2023 |
| Mini PC       | Rev JSL5 DDR4               | Mini pc     | [ec7b05c868](https://linux-hardware.org/?probe=ec7b05c868) | Aug 12, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [5bb31ccda3](https://linux-hardware.org/?probe=5bb31ccda3) | Aug 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [53c81d6d36](https://linux-hardware.org/?probe=53c81d6d36) | Aug 12, 2023 |
| HP            | Notebook                    | Notebook    | [de8a0230c4](https://linux-hardware.org/?probe=de8a0230c4) | Aug 11, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [f3e1bb3812](https://linux-hardware.org/?probe=f3e1bb3812) | Aug 11, 2023 |
| Apple         | MacBookPro14,2              | Notebook    | [8b0d028b37](https://linux-hardware.org/?probe=8b0d028b37) | Aug 11, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [f4a323eb82](https://linux-hardware.org/?probe=f4a323eb82) | Aug 11, 2023 |
| Dell          | 0KV3RP A00                  | Desktop     | [47c45a45e5](https://linux-hardware.org/?probe=47c45a45e5) | Aug 11, 2023 |
| Gigabyte      | A520M DS3H AC               | Desktop     | [c53eeb4caf](https://linux-hardware.org/?probe=c53eeb4caf) | Aug 11, 2023 |
| HP            | 339A                        | Desktop     | [2ecbd957da](https://linux-hardware.org/?probe=2ecbd957da) | Aug 11, 2023 |
| Gigabyte      | P67A-UD3P-B3                | Desktop     | [a1c6469145](https://linux-hardware.org/?probe=a1c6469145) | Aug 11, 2023 |
| HP            | 250 G3                      | Notebook    | [6ba303bc6b](https://linux-hardware.org/?probe=6ba303bc6b) | Aug 11, 2023 |
| HP            | Laptop 17-cp1xxx            | Notebook    | [ac523f4e3b](https://linux-hardware.org/?probe=ac523f4e3b) | Aug 11, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | Notebook    | [0a1e2a7f23](https://linux-hardware.org/?probe=0a1e2a7f23) | Aug 11, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | Notebook    | [742b085257](https://linux-hardware.org/?probe=742b085257) | Aug 11, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [f711709f3f](https://linux-hardware.org/?probe=f711709f3f) | Aug 11, 2023 |
| HP            | Pavilion dv6                | Notebook    | [1689b3fd44](https://linux-hardware.org/?probe=1689b3fd44) | Aug 11, 2023 |
| Leader        | SC404PRO                    | Notebook    | [6f24ee5e0c](https://linux-hardware.org/?probe=6f24ee5e0c) | Aug 11, 2023 |
| HP            | 84DE                        | All in one  | [bdd2e74d54](https://linux-hardware.org/?probe=bdd2e74d54) | Aug 11, 2023 |
| MSI           | H310M PRO-VD                | Desktop     | [f542bb8447](https://linux-hardware.org/?probe=f542bb8447) | Aug 10, 2023 |
| Acer          | Aspire E1-731               | Notebook    | [b75a766ee9](https://linux-hardware.org/?probe=b75a766ee9) | Aug 10, 2023 |
| ASUSTek       | P8Z68-V                     | Desktop     | [cff11cda6f](https://linux-hardware.org/?probe=cff11cda6f) | Aug 10, 2023 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [07e0bad7da](https://linux-hardware.org/?probe=07e0bad7da) | Aug 10, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [67414922e3](https://linux-hardware.org/?probe=67414922e3) | Aug 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [24629e2553](https://linux-hardware.org/?probe=24629e2553) | Aug 10, 2023 |
| ASRock        | H61M-DGS R2.0               | Desktop     | [4f05b77547](https://linux-hardware.org/?probe=4f05b77547) | Aug 10, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [82dde7d058](https://linux-hardware.org/?probe=82dde7d058) | Aug 10, 2023 |
| Gigabyte      | B365M H                     | Desktop     | [b23c1e6e73](https://linux-hardware.org/?probe=b23c1e6e73) | Aug 10, 2023 |
| Fujitsu       | LIFEBOOK A530               | Notebook    | [05e64e3a0a](https://linux-hardware.org/?probe=05e64e3a0a) | Aug 10, 2023 |
| HP            | ZBook Studio 16 inch G9 ... | Notebook    | [e1462f1e3a](https://linux-hardware.org/?probe=e1462f1e3a) | Aug 10, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [26597d8a51](https://linux-hardware.org/?probe=26597d8a51) | Aug 10, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [0caf17e079](https://linux-hardware.org/?probe=0caf17e079) | Aug 10, 2023 |
| AMI           | T3 MRD                      | Desktop     | [7a77a54bfd](https://linux-hardware.org/?probe=7a77a54bfd) | Aug 10, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | Notebook    | [a3b9be2f56](https://linux-hardware.org/?probe=a3b9be2f56) | Aug 10, 2023 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [0638b1c2dd](https://linux-hardware.org/?probe=0638b1c2dd) | Aug 10, 2023 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [ff98e5f807](https://linux-hardware.org/?probe=ff98e5f807) | Aug 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | Notebook    | [75b55100a9](https://linux-hardware.org/?probe=75b55100a9) | Aug 10, 2023 |
| Dell          | Precision 5540              | Notebook    | [e68fee1e24](https://linux-hardware.org/?probe=e68fee1e24) | Aug 10, 2023 |
| HP            | EliteBook 8740w             | Notebook    | [69a5fc6981](https://linux-hardware.org/?probe=69a5fc6981) | Aug 10, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [cec1060cd6](https://linux-hardware.org/?probe=cec1060cd6) | Aug 10, 2023 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [1e856f651d](https://linux-hardware.org/?probe=1e856f651d) | Aug 09, 2023 |
| Gigabyte      | B560M AORUS ELITE           | Desktop     | [e315608a65](https://linux-hardware.org/?probe=e315608a65) | Aug 09, 2023 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | Notebook    | [26b98e8740](https://linux-hardware.org/?probe=26b98e8740) | Aug 09, 2023 |
| ASRock        | Z77 Extreme4                | Desktop     | [aadaab77db](https://linux-hardware.org/?probe=aadaab77db) | Aug 09, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [8b57037d50](https://linux-hardware.org/?probe=8b57037d50) | Aug 09, 2023 |
| Dell          | 06FW8M A06                  | Server      | [aa643edf66](https://linux-hardware.org/?probe=aa643edf66) | Aug 09, 2023 |
| Apple         | MacBookPro15,4              | Notebook    | [f63c9ffab9](https://linux-hardware.org/?probe=f63c9ffab9) | Aug 09, 2023 |
| Wortmann      | TERRA_MOBILE_1749           | Notebook    | [3986ff4298](https://linux-hardware.org/?probe=3986ff4298) | Aug 09, 2023 |
| HP            | EliteBook 830 G8 Noteboo... | Notebook    | [2f7f77225a](https://linux-hardware.org/?probe=2f7f77225a) | Aug 09, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [90291816a0](https://linux-hardware.org/?probe=90291816a0) | Aug 09, 2023 |
| Lenovo        | IdeaPadFlex 5 16ALC7 82R... | Convertible | [11cf6b0c98](https://linux-hardware.org/?probe=11cf6b0c98) | Aug 09, 2023 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | Notebook    | [68eb21c824](https://linux-hardware.org/?probe=68eb21c824) | Aug 09, 2023 |
| Lenovo        | IdeaPadFlex 5 16ALC7 82R... | Convertible | [1e3f49e3a0](https://linux-hardware.org/?probe=1e3f49e3a0) | Aug 09, 2023 |
| Lenovo        | IdeaPadFlex 5 16ALC7 82R... | Convertible | [2f32ca43ee](https://linux-hardware.org/?probe=2f32ca43ee) | Aug 09, 2023 |
| HP            | ProBook 4740s               | Notebook    | [1c56daf13e](https://linux-hardware.org/?probe=1c56daf13e) | Aug 09, 2023 |
| MSI           | Z97-G43                     | Desktop     | [b6edd8931f](https://linux-hardware.org/?probe=b6edd8931f) | Aug 09, 2023 |
| MSI           | B350 GAMING PLUS            | Desktop     | [4d7fbea818](https://linux-hardware.org/?probe=4d7fbea818) | Aug 09, 2023 |
| Gigabyte      | Z370M D3H-CF                | Desktop     | [9326dd9736](https://linux-hardware.org/?probe=9326dd9736) | Aug 09, 2023 |
| HP            | 2000                        | Notebook    | [fa62a90143](https://linux-hardware.org/?probe=fa62a90143) | Aug 09, 2023 |
| HP            | 255 G5                      | Notebook    | [d4adfe0ead](https://linux-hardware.org/?probe=d4adfe0ead) | Aug 09, 2023 |
| ASUSTek       | P8H67-M LX                  | Desktop     | [62d3166469](https://linux-hardware.org/?probe=62d3166469) | Aug 09, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | Notebook    | [5a4c9f0e5a](https://linux-hardware.org/?probe=5a4c9f0e5a) | Aug 09, 2023 |
| Gigabyte      | F2A88X-D3H                  | Desktop     | [7b0c19a9a2](https://linux-hardware.org/?probe=7b0c19a9a2) | Aug 09, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [0b1144add1](https://linux-hardware.org/?probe=0b1144add1) | Aug 09, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [f23d951287](https://linux-hardware.org/?probe=f23d951287) | Aug 09, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [ff36238822](https://linux-hardware.org/?probe=ff36238822) | Aug 09, 2023 |
| Dell          | Inspiron 15-7568            | Notebook    | [745ebb5475](https://linux-hardware.org/?probe=745ebb5475) | Aug 09, 2023 |
| Gigabyte      | F2A88X-D3H                  | Desktop     | [f0d580edb4](https://linux-hardware.org/?probe=f0d580edb4) | Aug 09, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [33beb40ea6](https://linux-hardware.org/?probe=33beb40ea6) | Aug 09, 2023 |
| Exo           | Smart Serie LT              | Notebook    | [08d7c1d923](https://linux-hardware.org/?probe=08d7c1d923) | Aug 09, 2023 |
| Sony          | VJF151                      | Notebook    | [b2768a0abf](https://linux-hardware.org/?probe=b2768a0abf) | Aug 09, 2023 |
| Biostar       | X370GT3                     | Desktop     | [6c4e484a34](https://linux-hardware.org/?probe=6c4e484a34) | Aug 09, 2023 |
| ASRock        | Z77 Extreme4                | Desktop     | [dace48c9ec](https://linux-hardware.org/?probe=dace48c9ec) | Aug 09, 2023 |
| ASRock        | Z77 Extreme4                | Desktop     | [e4c0e430b2](https://linux-hardware.org/?probe=e4c0e430b2) | Aug 09, 2023 |
| Lenovo        | ThinkPad T460 20FMA00F00    | Notebook    | [4bd13ae71d](https://linux-hardware.org/?probe=4bd13ae71d) | Aug 09, 2023 |
| Gigabyte      | B85M-DS3H                   | Desktop     | [950bc73be5](https://linux-hardware.org/?probe=950bc73be5) | Aug 09, 2023 |
| Itautec       | ST 4273 ST-4273 Custom 0... | Desktop     | [2e2f861c7c](https://linux-hardware.org/?probe=2e2f861c7c) | Aug 09, 2023 |
| Dell          | Inspiron 5584               | Notebook    | [33e964d1d6](https://linux-hardware.org/?probe=33e964d1d6) | Aug 09, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [691838cd8c](https://linux-hardware.org/?probe=691838cd8c) | Aug 09, 2023 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | Notebook    | [4f4c3a2b96](https://linux-hardware.org/?probe=4f4c3a2b96) | Aug 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | Notebook    | [f48f680274](https://linux-hardware.org/?probe=f48f680274) | Aug 08, 2023 |
| Acer          | Aspire 8930                 | Notebook    | [1a39769fb2](https://linux-hardware.org/?probe=1a39769fb2) | Aug 08, 2023 |
| HP            | 255 G5                      | Notebook    | [b38a912e23](https://linux-hardware.org/?probe=b38a912e23) | Aug 08, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [cb340460b6](https://linux-hardware.org/?probe=cb340460b6) | Aug 08, 2023 |
| ASRock        | H61M-HVGS                   | Desktop     | [f78ce03ad4](https://linux-hardware.org/?probe=f78ce03ad4) | Aug 08, 2023 |
| ASRock        | H61M-HVGS                   | Desktop     | [60d9dcfa89](https://linux-hardware.org/?probe=60d9dcfa89) | Aug 08, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | Notebook    | [f6b63d9967](https://linux-hardware.org/?probe=f6b63d9967) | Aug 08, 2023 |
| ASUSTek       | 1001P                       | Notebook    | [b4326c3c45](https://linux-hardware.org/?probe=b4326c3c45) | Aug 08, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | Notebook    | [179beade50](https://linux-hardware.org/?probe=179beade50) | Aug 08, 2023 |
| HP            | Unknown                     | Notebook    | [567a10ceb2](https://linux-hardware.org/?probe=567a10ceb2) | Aug 08, 2023 |
| Lenovo        | 3136 SDK0J40700 WIN 3258... | Mini pc     | [1a0f72e2d0](https://linux-hardware.org/?probe=1a0f72e2d0) | Aug 08, 2023 |
| MSI           | MAG B550M MORTAR            | Desktop     | [6c50235cbc](https://linux-hardware.org/?probe=6c50235cbc) | Aug 08, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [2a7e23b825](https://linux-hardware.org/?probe=2a7e23b825) | Aug 08, 2023 |
| MSI           | Z270 PC MATE                | Desktop     | [aa107173a1](https://linux-hardware.org/?probe=aa107173a1) | Aug 08, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [f03a19e65b](https://linux-hardware.org/?probe=f03a19e65b) | Aug 08, 2023 |
| ASUSTek       | P5G41T-M                    | Desktop     | [9eccce625b](https://linux-hardware.org/?probe=9eccce625b) | Aug 08, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [1ad6abed83](https://linux-hardware.org/?probe=1ad6abed83) | Aug 08, 2023 |
| Dell          | XPS L501X                   | Notebook    | [60a937133c](https://linux-hardware.org/?probe=60a937133c) | Aug 08, 2023 |
| HP            | Pavilion 17                 | Notebook    | [4833cfdbd8](https://linux-hardware.org/?probe=4833cfdbd8) | Aug 08, 2023 |
| MSI           | PRO Z790-P WIFI DDR4        | Desktop     | [a79335e604](https://linux-hardware.org/?probe=a79335e604) | Aug 07, 2023 |
| ASRock        | Z97 Extreme4                | Desktop     | [27c70b528b](https://linux-hardware.org/?probe=27c70b528b) | Aug 07, 2023 |
| Dell          | 0X2MKR A00                  | All in one  | [101fc74a47](https://linux-hardware.org/?probe=101fc74a47) | Aug 07, 2023 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [c1062b9705](https://linux-hardware.org/?probe=c1062b9705) | Aug 07, 2023 |
| HP            | Elite x2 1012 G1            | Notebook    | [fea0f58ed5](https://linux-hardware.org/?probe=fea0f58ed5) | Aug 07, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [e703e9ae63](https://linux-hardware.org/?probe=e703e9ae63) | Aug 07, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [ef73e2e520](https://linux-hardware.org/?probe=ef73e2e520) | Aug 07, 2023 |
| Dell          | Latitude 7490               | Notebook    | [e7738263f7](https://linux-hardware.org/?probe=e7738263f7) | Aug 07, 2023 |
| Dell          | Latitude 7490               | Notebook    | [a3b95f2fc2](https://linux-hardware.org/?probe=a3b95f2fc2) | Aug 07, 2023 |
| Dell          | Vostro 1700                 | Notebook    | [009c767dae](https://linux-hardware.org/?probe=009c767dae) | Aug 07, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [009a1819fa](https://linux-hardware.org/?probe=009a1819fa) | Aug 07, 2023 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [46a7513850](https://linux-hardware.org/?probe=46a7513850) | Aug 07, 2023 |
| Wortmann      | TERRA_MOBILE_1749           | Notebook    | [22624fbda5](https://linux-hardware.org/?probe=22624fbda5) | Aug 07, 2023 |
| Acer          | Aspire V3-771               | Notebook    | [ebdbffb7da](https://linux-hardware.org/?probe=ebdbffb7da) | Aug 07, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [6601d0d136](https://linux-hardware.org/?probe=6601d0d136) | Aug 07, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [62d3a8d08d](https://linux-hardware.org/?probe=62d3a8d08d) | Aug 07, 2023 |
| Acer          | Aspire 5734Z                | Notebook    | [158671d9c9](https://linux-hardware.org/?probe=158671d9c9) | Aug 07, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [cb5a99b4fb](https://linux-hardware.org/?probe=cb5a99b4fb) | Aug 07, 2023 |
| HP            | 3397                        | Desktop     | [3cf9a90333](https://linux-hardware.org/?probe=3cf9a90333) | Aug 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | Notebook    | [bd036e1e65](https://linux-hardware.org/?probe=bd036e1e65) | Aug 07, 2023 |
| Supermicro    | X10DRiB                     | Server      | [aeb76679f7](https://linux-hardware.org/?probe=aeb76679f7) | Aug 07, 2023 |
| ASUSTek       | N552VX                      | Notebook    | [1c616233ca](https://linux-hardware.org/?probe=1c616233ca) | Aug 07, 2023 |
| Medion        | M14L-256                    | Notebook    | [7d0a8921dc](https://linux-hardware.org/?probe=7d0a8921dc) | Aug 07, 2023 |
| ASUSTek       | N76VM                       | Notebook    | [083980d0fb](https://linux-hardware.org/?probe=083980d0fb) | Aug 07, 2023 |
| HP            | 212B                        | Desktop     | [b7de4a2b0a](https://linux-hardware.org/?probe=b7de4a2b0a) | Aug 07, 2023 |
| Gigabyte      | AB350M-DS3H-CF              | Desktop     | [db512d60d0](https://linux-hardware.org/?probe=db512d60d0) | Aug 07, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [31c3da5150](https://linux-hardware.org/?probe=31c3da5150) | Aug 07, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | Notebook    | [804851c490](https://linux-hardware.org/?probe=804851c490) | Aug 07, 2023 |
| Acer          | Predator PT515-51           | Notebook    | [e08b7b4cd8](https://linux-hardware.org/?probe=e08b7b4cd8) | Aug 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [e2427beca2](https://linux-hardware.org/?probe=e2427beca2) | Aug 07, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [f8511d64fc](https://linux-hardware.org/?probe=f8511d64fc) | Aug 07, 2023 |
| MSI           | 970A-G43                    | Desktop     | [68384da884](https://linux-hardware.org/?probe=68384da884) | Aug 06, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [99635bf61d](https://linux-hardware.org/?probe=99635bf61d) | Aug 06, 2023 |
| Gigabyte      | EP35-DS4                    | Desktop     | [761d545a1e](https://linux-hardware.org/?probe=761d545a1e) | Aug 06, 2023 |
| ASRock        | H61M-DGS R2.0               | Desktop     | [032b99ac4f](https://linux-hardware.org/?probe=032b99ac4f) | Aug 06, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [570d622bb5](https://linux-hardware.org/?probe=570d622bb5) | Aug 06, 2023 |
| Lenovo        | ThinkCentre M57 6072BJU     | Desktop     | [9c0231c0f3](https://linux-hardware.org/?probe=9c0231c0f3) | Aug 06, 2023 |
| Dell          | Latitude E7270              | Notebook    | [e7209c4bb7](https://linux-hardware.org/?probe=e7209c4bb7) | Aug 06, 2023 |
| Dell          | Latitude E5520              | Notebook    | [132e7834f7](https://linux-hardware.org/?probe=132e7834f7) | Aug 06, 2023 |
| ASUSTek       | N76VM                       | Notebook    | [80d45ff242](https://linux-hardware.org/?probe=80d45ff242) | Aug 06, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [247f361473](https://linux-hardware.org/?probe=247f361473) | Aug 06, 2023 |
| MSI           | Z490-A PRO                  | Desktop     | [151339db32](https://linux-hardware.org/?probe=151339db32) | Aug 06, 2023 |
| Unknown       | Unknown                     | Notebook    | [66dd893ce8](https://linux-hardware.org/?probe=66dd893ce8) | Aug 06, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | Notebook    | [3d49205e68](https://linux-hardware.org/?probe=3d49205e68) | Aug 06, 2023 |
| Gigabyte      | AB350M-DS3H-CF              | Desktop     | [4a97a86dd8](https://linux-hardware.org/?probe=4a97a86dd8) | Aug 06, 2023 |
| Acer          | AO756                       | Notebook    | [60475c9d52](https://linux-hardware.org/?probe=60475c9d52) | Aug 06, 2023 |
| Teclast       | F7S                         | Notebook    | [a844443394](https://linux-hardware.org/?probe=a844443394) | Aug 06, 2023 |
| Gigabyte      | Z590 GAMING X               | Desktop     | [a8c865c9bb](https://linux-hardware.org/?probe=a8c865c9bb) | Aug 06, 2023 |
| Dell          | XPS 15 9575                 | Convertible | [4b72b07cd1](https://linux-hardware.org/?probe=4b72b07cd1) | Aug 06, 2023 |
| Lenovo        | ThinkPad T430 2349DS5       | Notebook    | [763d98ad86](https://linux-hardware.org/?probe=763d98ad86) | Aug 06, 2023 |
| Dell          | Inspiron 5584               | Notebook    | [7a4e005f77](https://linux-hardware.org/?probe=7a4e005f77) | Aug 06, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [7eb29a371d](https://linux-hardware.org/?probe=7eb29a371d) | Aug 06, 2023 |
| ASUSTek       | S301LA                      | Notebook    | [cc5477fc6b](https://linux-hardware.org/?probe=cc5477fc6b) | Aug 05, 2023 |
| ASUSTek       | Z87-PRO                     | Desktop     | [9d39447e43](https://linux-hardware.org/?probe=9d39447e43) | Aug 05, 2023 |
| HP            | 1588h                       | Desktop     | [1e041c2365](https://linux-hardware.org/?probe=1e041c2365) | Aug 05, 2023 |
| MSI           | Z490-A PRO                  | Desktop     | [0698c83c6e](https://linux-hardware.org/?probe=0698c83c6e) | Aug 05, 2023 |
| MSI           | PRO B550M-VC WIFI           | Desktop     | [f1727289ea](https://linux-hardware.org/?probe=f1727289ea) | Aug 05, 2023 |
| Acer          | Aspire E5-572G              | Notebook    | [846dce7b1b](https://linux-hardware.org/?probe=846dce7b1b) | Aug 05, 2023 |
| Multilaser    | PC024                       | Notebook    | [85a4bdd497](https://linux-hardware.org/?probe=85a4bdd497) | Aug 05, 2023 |
| Mediacom      | SmartBook 130 FullHD - M... | Notebook    | [3aa51361ae](https://linux-hardware.org/?probe=3aa51361ae) | Aug 05, 2023 |
| Gigabyte      | Z590 GAMING X               | Desktop     | [231ad3947e](https://linux-hardware.org/?probe=231ad3947e) | Aug 05, 2023 |
| Acer          | Aspire TC-895 V:1.0         | Desktop     | [85d2740423](https://linux-hardware.org/?probe=85d2740423) | Aug 05, 2023 |
| Lenovo        | 100w Gen 3 82HY             | Notebook    | [3feb7899d2](https://linux-hardware.org/?probe=3feb7899d2) | Aug 05, 2023 |
| MSI           | A68HM GRENADE               | Desktop     | [a186d8863f](https://linux-hardware.org/?probe=a186d8863f) | Aug 05, 2023 |
| Acer          | Aspire A715-72G             | Notebook    | [c95d1a55cd](https://linux-hardware.org/?probe=c95d1a55cd) | Aug 05, 2023 |
| Teclast       | F7S                         | Notebook    | [71ab18cda5](https://linux-hardware.org/?probe=71ab18cda5) | Aug 05, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [9f813efccc](https://linux-hardware.org/?probe=9f813efccc) | Aug 05, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [349326315f](https://linux-hardware.org/?probe=349326315f) | Aug 05, 2023 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | Notebook    | [a089f6ff62](https://linux-hardware.org/?probe=a089f6ff62) | Aug 05, 2023 |
| Notebook      | NP5x_NP6x_NP7xRNJ_RNH       | Notebook    | [f4f8099774](https://linux-hardware.org/?probe=f4f8099774) | Aug 05, 2023 |
| Acer          | AS E5-523G                  | Notebook    | [b37e833d1e](https://linux-hardware.org/?probe=b37e833d1e) | Aug 05, 2023 |
| Dell          | Latitude E5500              | Notebook    | [95ddcb321c](https://linux-hardware.org/?probe=95ddcb321c) | Aug 05, 2023 |
| Dell          | 0K83V0 A00                  | Desktop     | [e8fbfe7be1](https://linux-hardware.org/?probe=e8fbfe7be1) | Aug 05, 2023 |
| Acer          | Swift SF514-54GT            | Notebook    | [12ee4ed8f6](https://linux-hardware.org/?probe=12ee4ed8f6) | Aug 05, 2023 |
| Acer          | Swift SF514-54GT            | Notebook    | [5a2ed78e49](https://linux-hardware.org/?probe=5a2ed78e49) | Aug 05, 2023 |
| Apple         | Mac-F2218EA9                | All in one  | [bbbbdcdcb6](https://linux-hardware.org/?probe=bbbbdcdcb6) | Aug 05, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | Desktop     | [9ffeb0adcd](https://linux-hardware.org/?probe=9ffeb0adcd) | Aug 04, 2023 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [4a2c7a9f15](https://linux-hardware.org/?probe=4a2c7a9f15) | Aug 04, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | Desktop     | [2886f9202b](https://linux-hardware.org/?probe=2886f9202b) | Aug 04, 2023 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | Desktop     | [e3fd0f4808](https://linux-hardware.org/?probe=e3fd0f4808) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [15826fe271](https://linux-hardware.org/?probe=15826fe271) | Aug 04, 2023 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [2a54f1c8ce](https://linux-hardware.org/?probe=2a54f1c8ce) | Aug 04, 2023 |
| Gigabyte      | RC14UD                      | Notebook    | [6ad0758102](https://linux-hardware.org/?probe=6ad0758102) | Aug 04, 2023 |
| ASRock        | 4CoreDual-SATA2             | Desktop     | [6495cadf19](https://linux-hardware.org/?probe=6495cadf19) | Aug 04, 2023 |
| MSI           | Z490-A PRO                  | Desktop     | [71e97069b6](https://linux-hardware.org/?probe=71e97069b6) | Aug 04, 2023 |
| Lenovo        | ThinkPad L450 20DSS00M00    | Notebook    | [e9f9c0e216](https://linux-hardware.org/?probe=e9f9c0e216) | Aug 04, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [f74b524df1](https://linux-hardware.org/?probe=f74b524df1) | Aug 04, 2023 |
| Fujitsu       | FMVS75MWP                   | Notebook    | [506a18b94f](https://linux-hardware.org/?probe=506a18b94f) | Aug 04, 2023 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [f82f03bf86](https://linux-hardware.org/?probe=f82f03bf86) | Aug 04, 2023 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [d4bb94e07e](https://linux-hardware.org/?probe=d4bb94e07e) | Aug 04, 2023 |
| ASRock        | Z97 Extreme4                | Desktop     | [4252e9a028](https://linux-hardware.org/?probe=4252e9a028) | Aug 04, 2023 |
| Gigabyte      | AB350M-DS3H-CF              | Desktop     | [2b5c5c52e8](https://linux-hardware.org/?probe=2b5c5c52e8) | Aug 04, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [3cd247313d](https://linux-hardware.org/?probe=3cd247313d) | Aug 04, 2023 |
| Acer          | Aspire V5-572P              | Notebook    | [1d27d25f8d](https://linux-hardware.org/?probe=1d27d25f8d) | Aug 03, 2023 |
| PC Special... | Ionico 16                   | Notebook    | [0839bbc721](https://linux-hardware.org/?probe=0839bbc721) | Aug 03, 2023 |
| ASUSTek       | H97M-E                      | Desktop     | [5636598221](https://linux-hardware.org/?probe=5636598221) | Aug 03, 2023 |
| Sony          | SVF1521G1EW                 | Notebook    | [b46b664a9e](https://linux-hardware.org/?probe=b46b664a9e) | Aug 03, 2023 |
| Dell          | Latitude 5480               | Notebook    | [c52baac4e0](https://linux-hardware.org/?probe=c52baac4e0) | Aug 03, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [f29d0b0571](https://linux-hardware.org/?probe=f29d0b0571) | Aug 03, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [1db8a01118](https://linux-hardware.org/?probe=1db8a01118) | Aug 03, 2023 |
| Lenovo        | ThinkPad T400 6475R1G       | Notebook    | [481e1aa044](https://linux-hardware.org/?probe=481e1aa044) | Aug 03, 2023 |
| OEM           | B75 Ver:1.44                | Desktop     | [6dcf79b752](https://linux-hardware.org/?probe=6dcf79b752) | Aug 03, 2023 |
| Apple         | Mac-F2218EA9                | All in one  | [8799099410](https://linux-hardware.org/?probe=8799099410) | Aug 03, 2023 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [e888742592](https://linux-hardware.org/?probe=e888742592) | Aug 03, 2023 |
| Fujitsu       | D3501-A1 S26361-D3501-A1    | Desktop     | [38f7c8653b](https://linux-hardware.org/?probe=38f7c8653b) | Aug 03, 2023 |
| Gigabyte      | B450 GAMING X               | Desktop     | [bb292f568a](https://linux-hardware.org/?probe=bb292f568a) | Aug 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | Notebook    | [7d86876920](https://linux-hardware.org/?probe=7d86876920) | Aug 03, 2023 |
| Lenovo        | ThinkPad P51s 20HCS0660Y    | Notebook    | [6e8234ed89](https://linux-hardware.org/?probe=6e8234ed89) | Aug 03, 2023 |
| Panasonic     | CF-31WBLAXLM                | Notebook    | [580b017d88](https://linux-hardware.org/?probe=580b017d88) | Aug 03, 2023 |
| Acer          | Aspire 5733                 | Notebook    | [f09853c0ed](https://linux-hardware.org/?probe=f09853c0ed) | Aug 03, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [9171e8e6b9](https://linux-hardware.org/?probe=9171e8e6b9) | Aug 03, 2023 |
| HP            | ENVY 17                     | Notebook    | [ef244ad969](https://linux-hardware.org/?probe=ef244ad969) | Aug 02, 2023 |
| Lenovo        | ThinkCentre M91p 4518A4M    | Desktop     | [04f8c42dba](https://linux-hardware.org/?probe=04f8c42dba) | Aug 02, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [101e2e7e7e](https://linux-hardware.org/?probe=101e2e7e7e) | Aug 02, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [16cafd9d32](https://linux-hardware.org/?probe=16cafd9d32) | Aug 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [cf7cad0e02](https://linux-hardware.org/?probe=cf7cad0e02) | Aug 02, 2023 |
| ASRock        | 775Dual-VSTA                | Desktop     | [7241233996](https://linux-hardware.org/?probe=7241233996) | Aug 02, 2023 |
| Medion        | X681X                       | Notebook    | [8209a37737](https://linux-hardware.org/?probe=8209a37737) | Aug 02, 2023 |
| Positivo      | Q232B                       | Notebook    | [006d77a18c](https://linux-hardware.org/?probe=006d77a18c) | Aug 02, 2023 |
| Gigabyte      | GA-990FXA-UD3               | Desktop     | [8395f61392](https://linux-hardware.org/?probe=8395f61392) | Aug 02, 2023 |
| ASUSTek       | P5B-VM SE                   | Desktop     | [d5bb32f2de](https://linux-hardware.org/?probe=d5bb32f2de) | Aug 02, 2023 |
| Dell          | 0NKW6Y A01                  | Desktop     | [6bae407930](https://linux-hardware.org/?probe=6bae407930) | Aug 02, 2023 |
| Lenovo        | ThinkPad T480 20L5001BUS    | Notebook    | [b340a9e075](https://linux-hardware.org/?probe=b340a9e075) | Aug 02, 2023 |
| Dell          | Latitude 7280               | Notebook    | [40a53f89cf](https://linux-hardware.org/?probe=40a53f89cf) | Aug 02, 2023 |
| HP            | Pavilion dv5                | Notebook    | [58b4ce4ff9](https://linux-hardware.org/?probe=58b4ce4ff9) | Aug 02, 2023 |
| ASUSTek       | P5B                         | Desktop     | [a918b28119](https://linux-hardware.org/?probe=a918b28119) | Aug 02, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [8c4c50cef9](https://linux-hardware.org/?probe=8c4c50cef9) | Aug 02, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [5e74aca4e7](https://linux-hardware.org/?probe=5e74aca4e7) | Aug 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [4a6b173235](https://linux-hardware.org/?probe=4a6b173235) | Aug 01, 2023 |
| Acer          | Aspire ES1-521              | Notebook    | [127d7abd32](https://linux-hardware.org/?probe=127d7abd32) | Aug 01, 2023 |
| Gateway       | DX4840                      | Desktop     | [7268035f51](https://linux-hardware.org/?probe=7268035f51) | Aug 01, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [0e5d30b504](https://linux-hardware.org/?probe=0e5d30b504) | Aug 01, 2023 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [00311486d2](https://linux-hardware.org/?probe=00311486d2) | Aug 01, 2023 |
| Lenovo        | ThinkPad X250 20CM001PGE    | Notebook    | [9c5503cd84](https://linux-hardware.org/?probe=9c5503cd84) | Aug 01, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [6f59479d87](https://linux-hardware.org/?probe=6f59479d87) | Aug 01, 2023 |
| HP            | Pavilion 15                 | Notebook    | [c66316cd62](https://linux-hardware.org/?probe=c66316cd62) | Aug 01, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [c74f4bde19](https://linux-hardware.org/?probe=c74f4bde19) | Aug 01, 2023 |
| Dell          | Latitude E6440              | Notebook    | [57ce920c06](https://linux-hardware.org/?probe=57ce920c06) | Aug 01, 2023 |
| HP            | 339A                        | Desktop     | [782fefbccd](https://linux-hardware.org/?probe=782fefbccd) | Aug 01, 2023 |
| Medion        | E5214                       | Notebook    | [98cb0db418](https://linux-hardware.org/?probe=98cb0db418) | Aug 01, 2023 |
| Lenovo        | 3188 SDK0J40709 WIN 3259... | Desktop     | [59e7f97f2d](https://linux-hardware.org/?probe=59e7f97f2d) | Aug 01, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [22e8927934](https://linux-hardware.org/?probe=22e8927934) | Aug 01, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [046b3ffe68](https://linux-hardware.org/?probe=046b3ffe68) | Aug 01, 2023 |
| HP            | Pavilion 15                 | Notebook    | [1ad3dc2f1b](https://linux-hardware.org/?probe=1ad3dc2f1b) | Aug 01, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [244a32825d](https://linux-hardware.org/?probe=244a32825d) | Aug 01, 2023 |
| Teclast       | Tbolt 10 DG                 | Notebook    | [cd75496056](https://linux-hardware.org/?probe=cd75496056) | Aug 01, 2023 |
| HP            | Unknown                     | Notebook    | [a4d8377dfa](https://linux-hardware.org/?probe=a4d8377dfa) | Aug 01, 2023 |
| Itautec       | Infoway a7420               | Notebook    | [da7459a0ea](https://linux-hardware.org/?probe=da7459a0ea) | Aug 01, 2023 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [1090d19a71](https://linux-hardware.org/?probe=1090d19a71) | Aug 01, 2023 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [49e503da8e](https://linux-hardware.org/?probe=49e503da8e) | Aug 01, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [39774f9f5d](https://linux-hardware.org/?probe=39774f9f5d) | Aug 01, 2023 |
| HP            | Compaq 6910p                | Notebook    | [6720872cd9](https://linux-hardware.org/?probe=6720872cd9) | Aug 01, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [567efcf41e](https://linux-hardware.org/?probe=567efcf41e) | Aug 01, 2023 |
| Gigabyte      | B650 AORUS PRO AX           | Desktop     | [a8627dac81](https://linux-hardware.org/?probe=a8627dac81) | Aug 01, 2023 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [08e1a2a1e1](https://linux-hardware.org/?probe=08e1a2a1e1) | Aug 01, 2023 |
| ASUSTek       | P8H67-M                     | Desktop     | [7bebd786bd](https://linux-hardware.org/?probe=7bebd786bd) | Aug 01, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [7486c0a60b](https://linux-hardware.org/?probe=7486c0a60b) | Jul 31, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [d58cf2a585](https://linux-hardware.org/?probe=d58cf2a585) | Jul 31, 2023 |
| Dell          | Latitude 7640               | Notebook    | [ddb87f6cdb](https://linux-hardware.org/?probe=ddb87f6cdb) | Jul 31, 2023 |
| Dell          | 0D8M0M A00                  | Desktop     | [3ac6740883](https://linux-hardware.org/?probe=3ac6740883) | Jul 31, 2023 |
| Acer          | Aspire R5-471T              | Notebook    | [443869016d](https://linux-hardware.org/?probe=443869016d) | Jul 31, 2023 |
| HP            | Pavilion 14                 | Notebook    | [313aedd888](https://linux-hardware.org/?probe=313aedd888) | Jul 31, 2023 |
| Wortmann      | CR700                       | Notebook    | [2f3379e14e](https://linux-hardware.org/?probe=2f3379e14e) | Jul 31, 2023 |
| Toshiba       | Satellite S855              | Notebook    | [d7d26e7de3](https://linux-hardware.org/?probe=d7d26e7de3) | Jul 31, 2023 |
| HP            | Laptop 17-bs0xx             | Notebook    | [49dac3f2d9](https://linux-hardware.org/?probe=49dac3f2d9) | Jul 31, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [c7f6e64888](https://linux-hardware.org/?probe=c7f6e64888) | Jul 31, 2023 |
| HP            | Laptop 17-bs0xx             | Notebook    | [aca7e14a0e](https://linux-hardware.org/?probe=aca7e14a0e) | Jul 31, 2023 |
| Apple         | Mac-DB15BD556843C820 iMa... | All in one  | [ec04257798](https://linux-hardware.org/?probe=ec04257798) | Jul 31, 2023 |
| System76      | Thelio Mira thelio-mira-... | Desktop     | [685230003a](https://linux-hardware.org/?probe=685230003a) | Jul 31, 2023 |
| HP            | ProBook 4720s               | Notebook    | [f1e4220c67](https://linux-hardware.org/?probe=f1e4220c67) | Jul 31, 2023 |
| Lenovo        | V15-IGL 82C3                | Notebook    | [6c0a6fff0a](https://linux-hardware.org/?probe=6c0a6fff0a) | Jul 31, 2023 |
| ASRock        | ALiveSATA2-GLAN             | Desktop     | [3c4fbfa426](https://linux-hardware.org/?probe=3c4fbfa426) | Jul 31, 2023 |
| HP            | 8924 0101                   | All in one  | [e2fa4d7d10](https://linux-hardware.org/?probe=e2fa4d7d10) | Jul 31, 2023 |
| HP            | Pavilion g7                 | Notebook    | [51997a6e91](https://linux-hardware.org/?probe=51997a6e91) | Jul 31, 2023 |
| Unknown       | Phitronics N68C-M           | Desktop     | [0c596c95da](https://linux-hardware.org/?probe=0c596c95da) | Jul 31, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [0b157cd8f7](https://linux-hardware.org/?probe=0b157cd8f7) | Jul 31, 2023 |
| Dell          | Vostro 1510                 | Notebook    | [8e49dde20d](https://linux-hardware.org/?probe=8e49dde20d) | Jul 31, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [e8b1218a57](https://linux-hardware.org/?probe=e8b1218a57) | Jul 31, 2023 |
| Dell          | Vostro 1510                 | Notebook    | [8d6d8b9243](https://linux-hardware.org/?probe=8d6d8b9243) | Jul 31, 2023 |
| Dell          | Vostro 1510                 | Notebook    | [13e9f3fa3c](https://linux-hardware.org/?probe=13e9f3fa3c) | Jul 31, 2023 |
| Lenovo        | ThinkPad T460 20FMA00F00    | Notebook    | [9268d1c4f9](https://linux-hardware.org/?probe=9268d1c4f9) | Jul 30, 2023 |
| I-Life Dig... | ZED Air CX7                 | Notebook    | [2c897f0413](https://linux-hardware.org/?probe=2c897f0413) | Jul 30, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [8de1f944a7](https://linux-hardware.org/?probe=8de1f944a7) | Jul 30, 2023 |
| Intel         | DG41WV AAE90316-102         | Desktop     | [fa7d425224](https://linux-hardware.org/?probe=fa7d425224) | Jul 30, 2023 |
| Acer          | Aspire 5741G                | Notebook    | [3c56ffebcb](https://linux-hardware.org/?probe=3c56ffebcb) | Jul 30, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [80ab0f5cd2](https://linux-hardware.org/?probe=80ab0f5cd2) | Jul 30, 2023 |
| Dell          | 0M863N A00                  | Desktop     | [3c403d83cc](https://linux-hardware.org/?probe=3c403d83cc) | Jul 30, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [63017a7eb1](https://linux-hardware.org/?probe=63017a7eb1) | Jul 30, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [4070a9350d](https://linux-hardware.org/?probe=4070a9350d) | Jul 30, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | Notebook    | [6ec734b217](https://linux-hardware.org/?probe=6ec734b217) | Jul 30, 2023 |
| Acer          | Aspire A315-56              | Notebook    | [522c7e4381](https://linux-hardware.org/?probe=522c7e4381) | Jul 30, 2023 |
| ASUSTek       | PN40                        | Mini pc     | [9336495f4e](https://linux-hardware.org/?probe=9336495f4e) | Jul 30, 2023 |
| Lenovo        | ThinkPad T470s 20HGS0DT0... | Notebook    | [bd0d0f2888](https://linux-hardware.org/?probe=bd0d0f2888) | Jul 30, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [583bc42f4e](https://linux-hardware.org/?probe=583bc42f4e) | Jul 30, 2023 |
| Lenovo        | 36EB SDK0J40700 WIN 3258... | Desktop     | [2c1deb7640](https://linux-hardware.org/?probe=2c1deb7640) | Jul 30, 2023 |
| Dell          | Latitude 3510               | Notebook    | [8bfe0fe5fb](https://linux-hardware.org/?probe=8bfe0fe5fb) | Jul 30, 2023 |
| Unknown       | Unknown                     | Notebook    | [b5f5ef27a8](https://linux-hardware.org/?probe=b5f5ef27a8) | Jul 30, 2023 |
| Medion        | E5214                       | Notebook    | [d1c634ee07](https://linux-hardware.org/?probe=d1c634ee07) | Jul 30, 2023 |
| Dell          | Latitude E5570              | Notebook    | [1f9be76313](https://linux-hardware.org/?probe=1f9be76313) | Jul 30, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [3daec696c7](https://linux-hardware.org/?probe=3daec696c7) | Jul 30, 2023 |
| Intel         | NUC11TNBv7 K87766-404       | Mini pc     | [9a5567fb0b](https://linux-hardware.org/?probe=9a5567fb0b) | Jul 30, 2023 |
| Dell          | Latitude E5520              | Notebook    | [09aa4e35c4](https://linux-hardware.org/?probe=09aa4e35c4) | Jul 30, 2023 |
| ASRock        | 4CoreDual-SATA2             | Desktop     | [44438ab71e](https://linux-hardware.org/?probe=44438ab71e) | Jul 30, 2023 |
| Lenovo        | ThinkPad T430 2344BZU       | Notebook    | [f7f737c592](https://linux-hardware.org/?probe=f7f737c592) | Jul 30, 2023 |
| Lenovo        | ThinkPad T430 2344BZU       | Notebook    | [d9c960b2b7](https://linux-hardware.org/?probe=d9c960b2b7) | Jul 30, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [c3101b6a76](https://linux-hardware.org/?probe=c3101b6a76) | Jul 30, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [915938d446](https://linux-hardware.org/?probe=915938d446) | Jul 30, 2023 |
| Acer          | Aspire A315-42              | Notebook    | [3d1aebd069](https://linux-hardware.org/?probe=3d1aebd069) | Jul 30, 2023 |
| Lenovo        | ThinkCentre M91p 4518A4M    | Desktop     | [2ba45b1cfa](https://linux-hardware.org/?probe=2ba45b1cfa) | Jul 30, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [1d7b13f2e9](https://linux-hardware.org/?probe=1d7b13f2e9) | Jul 30, 2023 |
| Unknown       | GSUO H61V10C                | Desktop     | [9fd25cd0ba](https://linux-hardware.org/?probe=9fd25cd0ba) | Jul 29, 2023 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [fde88e808d](https://linux-hardware.org/?probe=fde88e808d) | Jul 29, 2023 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [c980146db6](https://linux-hardware.org/?probe=c980146db6) | Jul 29, 2023 |
| Dell          | G5 5590                     | Notebook    | [2745b35776](https://linux-hardware.org/?probe=2745b35776) | Jul 29, 2023 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [a9a2ac74bc](https://linux-hardware.org/?probe=a9a2ac74bc) | Jul 29, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [eff9350e7f](https://linux-hardware.org/?probe=eff9350e7f) | Jul 29, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [2b50e2b375](https://linux-hardware.org/?probe=2b50e2b375) | Jul 29, 2023 |
| Acer          | Swift SF314-56              | Notebook    | [f4d6e0b148](https://linux-hardware.org/?probe=f4d6e0b148) | Jul 29, 2023 |
| MSI           | GT70 2PE                    | Notebook    | [d0ef2177c3](https://linux-hardware.org/?probe=d0ef2177c3) | Jul 29, 2023 |
| MSI           | GT70 2PE                    | Notebook    | [bc059e2204](https://linux-hardware.org/?probe=bc059e2204) | Jul 29, 2023 |
| ASRock        | H61M-DGS R2.0               | Desktop     | [9d6da42aec](https://linux-hardware.org/?probe=9d6da42aec) | Jul 29, 2023 |
| Acer          | Swift SF315-52G             | Notebook    | [413fcf8114](https://linux-hardware.org/?probe=413fcf8114) | Jul 29, 2023 |
| VANT          | MOOVE15_2023                | Notebook    | [6943d341c4](https://linux-hardware.org/?probe=6943d341c4) | Jul 29, 2023 |
| Lenovo        | C205                        | All in one  | [e0a01bba61](https://linux-hardware.org/?probe=e0a01bba61) | Jul 29, 2023 |
| Acer          | Swift SF314-56              | Notebook    | [63a49ff6dd](https://linux-hardware.org/?probe=63a49ff6dd) | Jul 29, 2023 |
| Gigabyte      | H97-D3H-CF                  | Desktop     | [a294c01e5d](https://linux-hardware.org/?probe=a294c01e5d) | Jul 29, 2023 |
| HP            | Pavilion dv5                | Notebook    | [d52d0f879a](https://linux-hardware.org/?probe=d52d0f879a) | Jul 29, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [fecdf7e593](https://linux-hardware.org/?probe=fecdf7e593) | Jul 29, 2023 |
| Acer          | Aspire A315-42              | Notebook    | [02d2d041f8](https://linux-hardware.org/?probe=02d2d041f8) | Jul 29, 2023 |
| Gigabyte      | F2A88X-D3H                  | Desktop     | [8e5c19146b](https://linux-hardware.org/?probe=8e5c19146b) | Jul 29, 2023 |
| Lenovo        | ThinkPad T520 4243JA1       | Notebook    | [410cebaba3](https://linux-hardware.org/?probe=410cebaba3) | Jul 28, 2023 |
| ASUSTek       | X555LJ                      | Notebook    | [690e49362b](https://linux-hardware.org/?probe=690e49362b) | Jul 28, 2023 |
| HP            | EliteBook 820 G4            | Notebook    | [63a72ed445](https://linux-hardware.org/?probe=63a72ed445) | Jul 28, 2023 |
| HP            | 1825                        | Desktop     | [7bd4e99efa](https://linux-hardware.org/?probe=7bd4e99efa) | Jul 28, 2023 |
| Acer          | Aspire 5810T                | Notebook    | [2d141d703d](https://linux-hardware.org/?probe=2d141d703d) | Jul 28, 2023 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [356e8a0637](https://linux-hardware.org/?probe=356e8a0637) | Jul 28, 2023 |
| Acer          | Aspire A515-52G             | Notebook    | [2ba77ece3b](https://linux-hardware.org/?probe=2ba77ece3b) | Jul 28, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | Notebook    | [b9b1a625ee](https://linux-hardware.org/?probe=b9b1a625ee) | Jul 28, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [8fee6296fe](https://linux-hardware.org/?probe=8fee6296fe) | Jul 28, 2023 |
| Chuwi         | Hi10 X                      | Tablet      | [dac7c62216](https://linux-hardware.org/?probe=dac7c62216) | Jul 28, 2023 |
| Digitron      | G31T-M7                     | Desktop     | [7b926165d9](https://linux-hardware.org/?probe=7b926165d9) | Jul 28, 2023 |
| Acer          | Aspire V3-771               | Notebook    | [4abc91d2fb](https://linux-hardware.org/?probe=4abc91d2fb) | Jul 28, 2023 |
| Lenovo        | ThinkPad W541 20EFS00N00    | Notebook    | [c9f80b56fc](https://linux-hardware.org/?probe=c9f80b56fc) | Jul 28, 2023 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | Notebook    | [79acef5aba](https://linux-hardware.org/?probe=79acef5aba) | Jul 28, 2023 |
| HP            | 829D                        | Desktop     | [35b5c3a375](https://linux-hardware.org/?probe=35b5c3a375) | Jul 28, 2023 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [ffb2276d18](https://linux-hardware.org/?probe=ffb2276d18) | Jul 28, 2023 |
| Lenovo        | G40-45 80E1                 | Notebook    | [27af99ec54](https://linux-hardware.org/?probe=27af99ec54) | Jul 28, 2023 |
| TUXEDO        | Unknown                     | Notebook    | [9c46ee9f93](https://linux-hardware.org/?probe=9c46ee9f93) | Jul 28, 2023 |
| Lenovo        | No DPK                      | Desktop     | [c6af16725d](https://linux-hardware.org/?probe=c6af16725d) | Jul 28, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [dc2835b589](https://linux-hardware.org/?probe=dc2835b589) | Jul 28, 2023 |
| Lenovo        | ThinkPad T460 20FMS22905    | Notebook    | [f95fe4ced5](https://linux-hardware.org/?probe=f95fe4ced5) | Jul 28, 2023 |
| HP            | Laptop 17-cp1xxx            | Notebook    | [29a0a48515](https://linux-hardware.org/?probe=29a0a48515) | Jul 28, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [8ca0357bf1](https://linux-hardware.org/?probe=8ca0357bf1) | Jul 28, 2023 |
| Google        | Reef                        | Notebook    | [96774077fc](https://linux-hardware.org/?probe=96774077fc) | Jul 28, 2023 |
| PC Special... | Ionico 16                   | Notebook    | [86d9ab8b73](https://linux-hardware.org/?probe=86d9ab8b73) | Jul 28, 2023 |
| PC Special... | Ionico 16                   | Notebook    | [6ea424234a](https://linux-hardware.org/?probe=6ea424234a) | Jul 28, 2023 |
| HP            | Pavilion 17                 | Notebook    | [eb4d13c329](https://linux-hardware.org/?probe=eb4d13c329) | Jul 28, 2023 |
| Intel         | NUC12WSBi5 M46425-303       | Mini pc     | [59465fec90](https://linux-hardware.org/?probe=59465fec90) | Jul 28, 2023 |
| Alienware     | m17 R4                      | Notebook    | [eece2da9ed](https://linux-hardware.org/?probe=eece2da9ed) | Jul 27, 2023 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [04fcfe86e9](https://linux-hardware.org/?probe=04fcfe86e9) | Jul 27, 2023 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [01110b1f21](https://linux-hardware.org/?probe=01110b1f21) | Jul 27, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [b464dbd11c](https://linux-hardware.org/?probe=b464dbd11c) | Jul 27, 2023 |
| Acer          | Aspire 5810T                | Notebook    | [9b7b328324](https://linux-hardware.org/?probe=9b7b328324) | Jul 27, 2023 |
| Acer          | Spin SP111-31               | Convertible | [003fa350a2](https://linux-hardware.org/?probe=003fa350a2) | Jul 27, 2023 |
| Lenovo        | ThinkPad T480 20L6S55L00    | Notebook    | [5b3742984b](https://linux-hardware.org/?probe=5b3742984b) | Jul 27, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [9c8b9571d9](https://linux-hardware.org/?probe=9c8b9571d9) | Jul 27, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [ac68775946](https://linux-hardware.org/?probe=ac68775946) | Jul 27, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [d91f2ff8ba](https://linux-hardware.org/?probe=d91f2ff8ba) | Jul 27, 2023 |
| Gigabyte      | H110-D3A-CF                 | Desktop     | [87a06556a6](https://linux-hardware.org/?probe=87a06556a6) | Jul 27, 2023 |
| ASUSTek       | M5A78L-M LE                 | Desktop     | [b7c8e3ad22](https://linux-hardware.org/?probe=b7c8e3ad22) | Jul 27, 2023 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [a9c6664e68](https://linux-hardware.org/?probe=a9c6664e68) | Jul 27, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | Notebook    | [9970afb7db](https://linux-hardware.org/?probe=9970afb7db) | Jul 27, 2023 |
| Dell          | 0W7JN5 A01                  | Server      | [8f86e6220c](https://linux-hardware.org/?probe=8f86e6220c) | Jul 27, 2023 |
| Dell          | 0W7JN5 A01                  | Server      | [568da91aee](https://linux-hardware.org/?probe=568da91aee) | Jul 27, 2023 |
| ASRock        | H61M-DGS R2.0               | Desktop     | [0a92529b68](https://linux-hardware.org/?probe=0a92529b68) | Jul 27, 2023 |
| Gigabyte      | GA-MA790XT-UD4P             | Desktop     | [63e4d8c8d4](https://linux-hardware.org/?probe=63e4d8c8d4) | Jul 27, 2023 |
| ASRock        | A320M-HD                    | Desktop     | [26e141980a](https://linux-hardware.org/?probe=26e141980a) | Jul 27, 2023 |
| Intel         | H55                         | Desktop     | [83f249e836](https://linux-hardware.org/?probe=83f249e836) | Jul 27, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [7c716b6ab0](https://linux-hardware.org/?probe=7c716b6ab0) | Jul 27, 2023 |
| Multilaser    | PC024                       | Notebook    | [fa5b5a3146](https://linux-hardware.org/?probe=fa5b5a3146) | Jul 27, 2023 |
| HP            | 1497                        | Desktop     | [370799b635](https://linux-hardware.org/?probe=370799b635) | Jul 26, 2023 |
| ASRock        | H61M-HVS                    | Desktop     | [ac730fa4ed](https://linux-hardware.org/?probe=ac730fa4ed) | Jul 26, 2023 |
| ASRock        | H61M-HVS                    | Desktop     | [57d93857f1](https://linux-hardware.org/?probe=57d93857f1) | Jul 26, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [79ea58e0d1](https://linux-hardware.org/?probe=79ea58e0d1) | Jul 26, 2023 |
| HP            | 806A                        | Desktop     | [e188cb594c](https://linux-hardware.org/?probe=e188cb594c) | Jul 26, 2023 |
| HP            | 87A4 10100                  | All in one  | [99d5e60209](https://linux-hardware.org/?probe=99d5e60209) | Jul 26, 2023 |
| PC Special... | Ionico 16                   | Notebook    | [5c91300246](https://linux-hardware.org/?probe=5c91300246) | Jul 26, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [4b0210f463](https://linux-hardware.org/?probe=4b0210f463) | Jul 26, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [5d7532050c](https://linux-hardware.org/?probe=5d7532050c) | Jul 26, 2023 |
| ASUSTek       | P5G41T-M                    | Desktop     | [355fadbc12](https://linux-hardware.org/?probe=355fadbc12) | Jul 26, 2023 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [cf57b5785a](https://linux-hardware.org/?probe=cf57b5785a) | Jul 26, 2023 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [80c9076b8b](https://linux-hardware.org/?probe=80c9076b8b) | Jul 25, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [865eacc7bb](https://linux-hardware.org/?probe=865eacc7bb) | Jul 25, 2023 |
| ASUSTek       | H61M-E                      | Desktop     | [849a99d897](https://linux-hardware.org/?probe=849a99d897) | Jul 25, 2023 |
| Unknown       | HX90                        | Desktop     | [ba2a06600a](https://linux-hardware.org/?probe=ba2a06600a) | Jul 25, 2023 |
| Apple         | MacBookPro5,2               | Notebook    | [e367e06cac](https://linux-hardware.org/?probe=e367e06cac) | Jul 25, 2023 |
| Acer          | Aspire 5560                 | Notebook    | [edd90996c4](https://linux-hardware.org/?probe=edd90996c4) | Jul 25, 2023 |
| MSI           | GL75 Leopard 10SFR          | Notebook    | [8b976f0d08](https://linux-hardware.org/?probe=8b976f0d08) | Jul 25, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [fb125d5fcb](https://linux-hardware.org/?probe=fb125d5fcb) | Jul 25, 2023 |
| ECT           | ONE GAMING Laptop Carry ... | Notebook    | [335aad489c](https://linux-hardware.org/?probe=335aad489c) | Jul 25, 2023 |
| Positivo      | S14SL01                     | Notebook    | [7ee0f7e8d1](https://linux-hardware.org/?probe=7ee0f7e8d1) | Jul 25, 2023 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [e46d04faa8](https://linux-hardware.org/?probe=e46d04faa8) | Jul 25, 2023 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [0b7f69aaf6](https://linux-hardware.org/?probe=0b7f69aaf6) | Jul 25, 2023 |
| ASUSTek       | X540LJ                      | Notebook    | [798cadd754](https://linux-hardware.org/?probe=798cadd754) | Jul 25, 2023 |
| Lenovo        | ThinkPad T430 2347H91       | Notebook    | [0ed3c4bc6a](https://linux-hardware.org/?probe=0ed3c4bc6a) | Jul 25, 2023 |
| Compaq        | Presario CQ-23              | Notebook    | [b78363eeaf](https://linux-hardware.org/?probe=b78363eeaf) | Jul 25, 2023 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [b30f6c221b](https://linux-hardware.org/?probe=b30f6c221b) | Jul 25, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [562e6e1026](https://linux-hardware.org/?probe=562e6e1026) | Jul 25, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [8d712af013](https://linux-hardware.org/?probe=8d712af013) | Jul 25, 2023 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [ac63d4a30c](https://linux-hardware.org/?probe=ac63d4a30c) | Jul 25, 2023 |
| Dell          | 0X501H A00                  | Desktop     | [407c19b590](https://linux-hardware.org/?probe=407c19b590) | Jul 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2ca3c71f4a](https://linux-hardware.org/?probe=2ca3c71f4a) | Jul 24, 2023 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [5be0e1a212](https://linux-hardware.org/?probe=5be0e1a212) | Jul 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [f4f494d289](https://linux-hardware.org/?probe=f4f494d289) | Jul 24, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [24b5ed47e3](https://linux-hardware.org/?probe=24b5ed47e3) | Jul 24, 2023 |
| Gigabyte      | B560M AORUS ELITE           | Desktop     | [8f1677af63](https://linux-hardware.org/?probe=8f1677af63) | Jul 24, 2023 |
| Gigabyte      | Z690 AORUS ELITE AX         | Desktop     | [a3284cc458](https://linux-hardware.org/?probe=a3284cc458) | Jul 24, 2023 |
| Teclast       | F15Plus 2                   | Notebook    | [53d02a90b1](https://linux-hardware.org/?probe=53d02a90b1) | Jul 24, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [ffb1e25ac0](https://linux-hardware.org/?probe=ffb1e25ac0) | Jul 24, 2023 |
| ASRock        | B550M-C                     | Desktop     | [faf557738b](https://linux-hardware.org/?probe=faf557738b) | Jul 24, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [fe7c41d88a](https://linux-hardware.org/?probe=fe7c41d88a) | Jul 24, 2023 |
| ASRock        | B550M-C                     | Desktop     | [fb855f74ff](https://linux-hardware.org/?probe=fb855f74ff) | Jul 24, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [156d74ec26](https://linux-hardware.org/?probe=156d74ec26) | Jul 24, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [3d08e59ce3](https://linux-hardware.org/?probe=3d08e59ce3) | Jul 24, 2023 |
| Dell          | Latitude 2110               | Notebook    | [05a7868709](https://linux-hardware.org/?probe=05a7868709) | Jul 24, 2023 |
| Intel         | NUC11TNBv7 K87766-404       | Mini pc     | [48ac49a195](https://linux-hardware.org/?probe=48ac49a195) | Jul 24, 2023 |
| Acer          | Aspire V5-572P              | Notebook    | [2033b22202](https://linux-hardware.org/?probe=2033b22202) | Jul 24, 2023 |
| Acer          | Aspire V5-572P              | Notebook    | [47b219049e](https://linux-hardware.org/?probe=47b219049e) | Jul 24, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [73886dba95](https://linux-hardware.org/?probe=73886dba95) | Jul 24, 2023 |
| Samsung       | DeskTop System              | Desktop     | [c1d4c8efb2](https://linux-hardware.org/?probe=c1d4c8efb2) | Jul 24, 2023 |
| Fujitsu       | LIFEBOOK A530               | Notebook    | [8c0fa80a0e](https://linux-hardware.org/?probe=8c0fa80a0e) | Jul 24, 2023 |
| Acer          | Aspire A715-74G             | Notebook    | [b27862dc34](https://linux-hardware.org/?probe=b27862dc34) | Jul 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | Notebook    | [9fa1cd70a3](https://linux-hardware.org/?probe=9fa1cd70a3) | Jul 24, 2023 |
| ASRock        | H61M-DGS R2.0               | Desktop     | [d78b20715a](https://linux-hardware.org/?probe=d78b20715a) | Jul 24, 2023 |
| LG Electro... | R490-G.BR51P1               | Notebook    | [eecedbc045](https://linux-hardware.org/?probe=eecedbc045) | Jul 24, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [5d16b13584](https://linux-hardware.org/?probe=5d16b13584) | Jul 24, 2023 |
| Dell          | Inspiron 5481               | Convertible | [f3a416bc4b](https://linux-hardware.org/?probe=f3a416bc4b) | Jul 23, 2023 |
| Gigabyte      | Z170X-UD5-CF                | Desktop     | [83ac887605](https://linux-hardware.org/?probe=83ac887605) | Jul 23, 2023 |
| HP            | ProBook 635 Aero G8 Note... | Notebook    | [ff5392a180](https://linux-hardware.org/?probe=ff5392a180) | Jul 23, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [fc09bdf7bb](https://linux-hardware.org/?probe=fc09bdf7bb) | Jul 23, 2023 |
| Unknown       | HX90                        | Desktop     | [25aeb91b82](https://linux-hardware.org/?probe=25aeb91b82) | Jul 23, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [42d8ff9a34](https://linux-hardware.org/?probe=42d8ff9a34) | Jul 23, 2023 |
| Toshiba       | Satellite S55-A             | Notebook    | [af52c268cd](https://linux-hardware.org/?probe=af52c268cd) | Jul 23, 2023 |
| Dell          | 0F373D A00                  | Desktop     | [fd337bb7ab](https://linux-hardware.org/?probe=fd337bb7ab) | Jul 23, 2023 |
| Dell          | 0F373D A00                  | Desktop     | [026854a02c](https://linux-hardware.org/?probe=026854a02c) | Jul 23, 2023 |
| ASUSTek       | X555LAB                     | Notebook    | [0e40daefd2](https://linux-hardware.org/?probe=0e40daefd2) | Jul 23, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [06eca9873d](https://linux-hardware.org/?probe=06eca9873d) | Jul 23, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Linux_Mint/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Linux Mint 20.3   | 3123      | 16.36%  |
| Linux Mint 21.1   | 2630      | 13.78%  |
| Linux Mint 20.2   | 2414      | 12.64%  |
| Linux Mint 20.1   | 2256      | 11.82%  |
| Linux Mint 19.3   | 2192      | 11.48%  |
| Linux Mint 20     | 2016      | 10.56%  |
| Linux Mint 21     | 1426      | 7.47%   |
| Linux Mint 19.1   | 911       | 4.77%   |
| Linux Mint 19.2   | 776       | 4.06%   |
| Linux Mint 21.2   | 580       | 3.04%   |
| Linux Mint 19     | 355       | 1.86%   |
| Linux Mint 18.3   | 294       | 1.54%   |
| Linux Mint 18.2   | 55        | 0.29%   |
| Linux Mint 18.1   | 24        | 0.13%   |
| Linux Mint 18     | 21        | 0.11%   |
| Linux Mint 17.3   | 9         | 0.05%   |
| Linux Mint 21.2.0 | 2         | 0.01%   |
| Linux Mint 17.1   | 2         | 0.01%   |
| Linux Mint 17     | 2         | 0.01%   |
| Linux Mint 13     | 2         | 0.01%   |
| Linux Mint 17.2   | 1         | 0.01%   |
| Linux Mint 15     | 1         | 0.01%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Linux Mint | 17636     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.4.0-91-generic  | 688       | 3.22%   |
| 5.15.0-56-generic | 666       | 3.12%   |
| 5.4.0-58-generic  | 521       | 2.44%   |
| 5.4.0-74-generic  | 437       | 2.04%   |
| 5.4.0-42-generic  | 382       | 1.79%   |
| 5.15.0-58-generic | 371       | 1.74%   |
| 5.15.0-76-generic | 349       | 1.63%   |
| 5.0.0-32-generic  | 346       | 1.62%   |
| 5.4.0-65-generic  | 332       | 1.55%   |
| 5.15.0-67-generic | 311       | 1.46%   |
| 5.4.0-77-generic  | 299       | 1.4%    |
| 5.15.0-60-generic | 289       | 1.35%   |
| 5.4.0-81-generic  | 284       | 1.33%   |
| 5.4.0-66-generic  | 281       | 1.31%   |
| 5.4.0-80-generic  | 273       | 1.28%   |
| 5.4.0-72-generic  | 266       | 1.24%   |
| 5.4.0-73-generic  | 255       | 1.19%   |
| 5.15.0-69-generic | 253       | 1.18%   |
| 5.4.0-100-generic | 250       | 1.17%   |
| 5.4.0-122-generic | 247       | 1.16%   |
| 4.15.0-54-generic | 247       | 1.16%   |
| 5.4.0-90-generic  | 245       | 1.15%   |
| 5.4.0-70-generic  | 244       | 1.14%   |
| 4.15.0-20-generic | 243       | 1.14%   |
| 5.4.0-88-generic  | 240       | 1.12%   |
| 5.4.0-107-generic | 233       | 1.09%   |
| 5.15.0-78-generic | 233       | 1.09%   |
| 5.15.0-52-generic | 233       | 1.09%   |
| 5.4.0-89-generic  | 230       | 1.08%   |
| 5.4.0-26-generic  | 226       | 1.06%   |
| 5.15.0-71-generic | 222       | 1.04%   |
| 5.15.0-41-generic | 215       | 1.01%   |
| 5.4.0-109-generic | 206       | 0.96%   |
| 5.4.0-48-generic  | 190       | 0.89%   |
| 5.15.0-73-generic | 175       | 0.82%   |
| 5.4.0-121-generic | 172       | 0.8%    |
| 5.4.0-96-generic  | 165       | 0.77%   |
| 5.15.0-48-generic | 164       | 0.77%   |
| 5.15.0-47-generic | 164       | 0.77%   |
| 5.15.0-72-generic | 161       | 0.75%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 8786      | 46.89%  |
| 5.15.0  | 4278      | 22.83%  |
| 4.15.0  | 2050      | 10.94%  |
| 5.3.0   | 901       | 4.81%   |
| 5.0.0   | 539       | 2.88%   |
| 5.13.0  | 347       | 1.85%   |
| 5.8.0   | 298       | 1.59%   |
| 5.11.0  | 252       | 1.34%   |
| 5.19.0  | 212       | 1.13%   |
| 4.10.0  | 90        | 0.48%   |
| 6.2.0   | 80        | 0.43%   |
| 4.4.0   | 70        | 0.37%   |
| 4.18.0  | 63        | 0.34%   |
| 5.14.0  | 60        | 0.32%   |
| 4.13.0  | 59        | 0.31%   |
| 6.1.0   | 35        | 0.19%   |
| 5.10.0  | 34        | 0.18%   |
| 6.0.0   | 27        | 0.14%   |
| 4.8.0   | 27        | 0.14%   |
| 5.17.0  | 19        | 0.1%    |
| 5.6.0   | 15        | 0.08%   |
| 5.7.1   | 10        | 0.05%   |
| 5.9.0   | 9         | 0.05%   |
| 6.3.7   | 7         | 0.04%   |
| 6.4.3   | 6         | 0.03%   |
| 6.3.4   | 6         | 0.03%   |
| 5.3.6   | 6         | 0.03%   |
| 6.0.9   | 5         | 0.03%   |
| 5.8.18  | 5         | 0.03%   |
| 5.7.0   | 5         | 0.03%   |
| 5.18.12 | 5         | 0.03%   |
| 5.16.0  | 5         | 0.03%   |
| Unknown | 5         | 0.03%   |
| 6.4.11  | 4         | 0.02%   |
| 6.2.8   | 4         | 0.02%   |
| 6.2.2   | 4         | 0.02%   |
| 6.1.4   | 4         | 0.02%   |
| 5.9.8   | 4         | 0.02%   |
| 5.9.1   | 4         | 0.02%   |
| 5.5.0   | 4         | 0.02%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 8802      | 47.01%  |
| 5.15    | 4309      | 23.02%  |
| 4.15    | 2053      | 10.97%  |
| 5.3     | 918       | 4.9%    |
| 5.0     | 554       | 2.96%   |
| 5.13    | 357       | 1.91%   |
| 5.8     | 315       | 1.68%   |
| 5.11    | 262       | 1.4%    |
| 5.19    | 219       | 1.17%   |
| 6.2     | 107       | 0.57%   |
| 4.10    | 90        | 0.48%   |
| 4.4     | 70        | 0.37%   |
| 5.14    | 67        | 0.36%   |
| 4.18    | 66        | 0.35%   |
| 4.13    | 61        | 0.33%   |
| 5.10    | 58        | 0.31%   |
| 6.1     | 55        | 0.29%   |
| 6.0     | 41        | 0.22%   |
| 5.17    | 34        | 0.18%   |
| 5.9     | 27        | 0.14%   |
| 4.8     | 27        | 0.14%   |
| 6.4     | 26        | 0.14%   |
| 5.7     | 26        | 0.14%   |
| 6.3     | 25        | 0.13%   |
| 5.6     | 23        | 0.12%   |
| 5.18    | 17        | 0.09%   |
| 5.12    | 17        | 0.09%   |
| 5.16    | 16        | 0.09%   |
| 4.20    | 11        | 0.06%   |
| 5.5     | 9         | 0.05%   |
| 5.2     | 8         | 0.04%   |
| 5.1     | 8         | 0.04%   |
| 4.19    | 7         | 0.04%   |
| Unknown | 5         | 0.03%   |
| 4.16    | 4         | 0.02%   |
| 4.11    | 4         | 0.02%   |
| 3.13    | 4         | 0.02%   |
| 6.5     | 3         | 0.02%   |
| 4.14    | 3         | 0.02%   |
| 4.12    | 3         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 17033     | 96.53%  |
| i686   | 613       | 3.47%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| X-Cinnamon      | 10833     | 59.82%  |
| MATE            | 2066      | 11.41%  |
| XFCE            | 1802      | 9.95%   |
| Cinnamon        | 1587      | 8.76%   |
| Unknown         | 1290      | 7.12%   |
| GNOME           | 362       | 2%      |
| KDE5            | 69        | 0.38%   |
| KDE             | 41        | 0.23%   |
| i3              | 14        | 0.08%   |
| LXDE            | 11        | 0.06%   |
| Budgie          | 5         | 0.03%   |
| Pantheon        | 4         | 0.02%   |
| KDE4            | 3         | 0.02%   |
| Deepin          | 3         | 0.02%   |
| Trinity         | 2         | 0.01%   |
| qtile           | 2         | 0.01%   |
| LXQt            | 2         | 0.01%   |
| GNOME Classic   | 2         | 0.01%   |
| sway            | 1         | 0.01%   |
| openbox         | 1         | 0.01%   |
| Jwm             | 1         | 0.01%   |
| ICEWM           | 1         | 0.01%   |
| i3-with-shmlog  | 1         | 0.01%   |
| GNUstep         | 1         | 0.01%   |
| GNOME Flashback | 1         | 0.01%   |
| fluxbox         | 1         | 0.01%   |
| enlightenment   | 1         | 0.01%   |
| awesome         | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 17552     | 99.37%  |
| Tty     | 60        | 0.34%   |
| Wayland | 42        | 0.24%   |
| Unknown | 9         | 0.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 10532     | 58.59%  |
| LightDM | 5032      | 27.99%  |
| TDM     | 2213      | 12.31%  |
| MDM     | 82        | 0.46%   |
| SDDM    | 52        | 0.29%   |
| GDM     | 40        | 0.22%   |
| GDM3    | 21        | 0.12%   |
| LXDM    | 4         | 0.02%   |
| Ly      | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 4804      | 26.86%  |
| de_DE   | 2505      | 14.01%  |
| Unknown | 1682      | 9.4%    |
| pt_BR   | 1340      | 7.49%   |
| fr_FR   | 774       | 4.33%   |
| ru_RU   | 760       | 4.25%   |
| en_GB   | 740       | 4.14%   |
| C       | 603       | 3.37%   |
| it_IT   | 480       | 2.68%   |
| en_CA   | 406       | 2.27%   |
| es_ES   | 378       | 2.11%   |
| pl_PL   | 334       | 1.87%   |
| en_AU   | 288       | 1.61%   |
| nl_NL   | 199       | 1.11%   |
| en_IN   | 176       | 0.98%   |
| es_AR   | 147       | 0.82%   |
| cs_CZ   | 134       | 0.75%   |
| es_MX   | 133       | 0.74%   |
| hu_HU   | 118       | 0.66%   |
| de_AT   | 115       | 0.64%   |
| en_ZA   | 114       | 0.64%   |
| pt_PT   | 108       | 0.6%    |
| de_CH   | 94        | 0.53%   |
| ru_UA   | 88        | 0.49%   |
| sv_SE   | 73        | 0.41%   |
| fi_FI   | 73        | 0.41%   |
| tr_TR   | 72        | 0.4%    |
| fr_CA   | 70        | 0.39%   |
| sk_SK   | 61        | 0.34%   |
| en_NZ   | 61        | 0.34%   |
| es_CL   | 56        | 0.31%   |
| es_CO   | 54        | 0.3%    |
| fr_BE   | 51        | 0.29%   |
| en_IE   | 50        | 0.28%   |
| el_GR   | 50        | 0.28%   |
| zh_CN   | 42        | 0.23%   |
| uk_UA   | 42        | 0.23%   |
| nl_BE   | 39        | 0.22%   |
| en_PH   | 39        | 0.22%   |
| bg_BG   | 35        | 0.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 9167      | 51.22%  |
| BIOS | 8731      | 48.78%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 15586     | 87.27%  |
| Unknown  | 1193      | 6.68%   |
| Overlay  | 532       | 2.98%   |
| Btrfs    | 288       | 1.61%   |
| Zfs      | 79        | 0.44%   |
| Xfs      | 50        | 0.28%   |
| Tmpfs    | 49        | 0.27%   |
| Ext3     | 37        | 0.21%   |
| Ext2     | 35        | 0.2%    |
| Aufs     | 4         | 0.02%   |
| Jfs      | 3         | 0.02%   |
| XXXXX    | 1         | 0.01%   |
| XXXX     | 1         | 0.01%   |
| Reiserfs | 1         | 0.01%   |
| ExX4     | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 10683     | 59.66%  |
| GPT     | 5241      | 29.27%  |
| MBR     | 1982      | 11.07%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 16447     | 92.5%   |
| Yes       | 1333      | 7.5%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 14336     | 80.52%  |
| Yes       | 3469      | 19.48%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 2710      | 15.37%  |
| Hewlett-Packard     | 2679      | 15.19%  |
| Lenovo              | 2209      | 12.53%  |
| Dell                | 2076      | 11.77%  |
| Gigabyte Technology | 1198      | 6.79%   |
| Acer                | 1189      | 6.74%   |
| MSI                 | 886       | 5.02%   |
| ASRock              | 629       | 3.57%   |
| Apple               | 394       | 2.23%   |
| Toshiba             | 338       | 1.92%   |
| Intel               | 307       | 1.74%   |
| Samsung Electronics | 302       | 1.71%   |
| Sony                | 172       | 0.98%   |
| Unknown             | 165       | 0.94%   |
| Medion              | 157       | 0.89%   |
| Fujitsu             | 151       | 0.86%   |
| Positivo            | 123       | 0.7%    |
| Pegatron            | 110       | 0.62%   |
| Google              | 91        | 0.52%   |
| Foxconn             | 82        | 0.46%   |
| Fujitsu Siemens     | 79        | 0.45%   |
| Biostar             | 78        | 0.44%   |
| HUAWEI              | 74        | 0.42%   |
| Packard Bell        | 65        | 0.37%   |
| ECS                 | 64        | 0.36%   |
| Notebook            | 59        | 0.33%   |
| Microsoft           | 46        | 0.26%   |
| Gateway             | 44        | 0.25%   |
| AMI                 | 42        | 0.24%   |
| Alienware           | 39        | 0.22%   |
| eMachines           | 35        | 0.2%    |
| LG Electronics      | 34        | 0.19%   |
| Itautec             | 30        | 0.17%   |
| AZW                 | 29        | 0.16%   |
| Semp Toshiba        | 27        | 0.15%   |
| GPU Company         | 27        | 0.15%   |
| Chuwi               | 27        | 0.15%   |
| Timi                | 26        | 0.15%   |
| OEM                 | 24        | 0.14%   |
| Supermicro          | 22        | 0.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                      | Computers | Percent |
|---------------------------|-----------|---------|
| Unknown                   | 220       | 1.25%   |
| ASUS All Series           | 146       | 0.83%   |
| HP Notebook               | 73        | 0.41%   |
| HP Pavilion g6            | 49        | 0.28%   |
| HP Pavilion dv6           | 46        | 0.26%   |
| HP Pavilion 15            | 42        | 0.24%   |
| HP Pavilion dv7           | 37        | 0.21%   |
| Dell OptiPlex 790         | 34        | 0.19%   |
| Dell OptiPlex 7010        | 33        | 0.19%   |
| MSI MS-7693               | 32        | 0.18%   |
| Gigabyte B450M DS3H       | 32        | 0.18%   |
| Dell OptiPlex 780         | 32        | 0.18%   |
| ASUS M5A78L-M/USB3        | 31        | 0.18%   |
| HP Laptop 15-bw0xx        | 30        | 0.17%   |
| ASUS TUF Gaming X570-PLUS | 30        | 0.17%   |
| ASUS PRIME A320M-K        | 30        | 0.17%   |
| ASUS P50IJ                | 30        | 0.17%   |
| Dell Inspiron 15-3567     | 27        | 0.15%   |
| Positivo Mobile           | 26        | 0.15%   |
| MSI MS-7C56               | 26        | 0.15%   |
| MSI MS-7C02               | 26        | 0.15%   |
| Dell Latitude E6410       | 26        | 0.15%   |
| MSI MS-7C37               | 25        | 0.14%   |
| Dell OptiPlex 3020        | 25        | 0.14%   |
| MSI MS-7B86               | 24        | 0.14%   |
| MSI MS-7817               | 24        | 0.14%   |
| HP Laptop 15-bs0xx        | 24        | 0.14%   |
| HP Compaq Elite 8300 SFF  | 23        | 0.13%   |
| HP 15                     | 23        | 0.13%   |
| MSI MS-7721               | 22        | 0.12%   |
| HP Pavilion Notebook      | 22        | 0.12%   |
| Gigabyte 970A-DS3P        | 22        | 0.12%   |
| Dell Latitude E6430       | 22        | 0.12%   |
| Dell Latitude E6420       | 22        | 0.12%   |
| HP Pavilion g7            | 21        | 0.12%   |
| Dell OptiPlex 9020        | 21        | 0.12%   |
| Dell OptiPlex 755         | 21        | 0.12%   |
| Dell Latitude E6540       | 21        | 0.12%   |
| Apple MacBookPro9,2       | 21        | 0.12%   |
| HP EliteBook 840 G1       | 20        | 0.11%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 874       | 4.96%   |
| Lenovo ThinkPad       | 836       | 4.74%   |
| Dell Inspiron         | 636       | 3.61%   |
| Dell Latitude         | 536       | 3.04%   |
| HP Pavilion           | 533       | 3.02%   |
| Lenovo IdeaPad        | 496       | 2.81%   |
| Dell OptiPlex         | 360       | 2.04%   |
| HP Laptop             | 321       | 1.82%   |
| HP Compaq             | 321       | 1.82%   |
| Toshiba Satellite     | 286       | 1.62%   |
| HP EliteBook          | 285       | 1.62%   |
| ASUS PRIME            | 254       | 1.44%   |
| HP ProBook            | 253       | 1.43%   |
| Unknown               | 220       | 1.25%   |
| Lenovo ThinkCentre    | 182       | 1.03%   |
| ASUS ROG              | 172       | 0.98%   |
| ASUS VivoBook         | 146       | 0.83%   |
| ASUS All              | 146       | 0.83%   |
| Dell Precision        | 134       | 0.76%   |
| Dell Vostro           | 132       | 0.75%   |
| ASUS TUF              | 132       | 0.75%   |
| Dell XPS              | 131       | 0.74%   |
| HP ENVY               | 98        | 0.56%   |
| ASUS M5A78L-M         | 78        | 0.44%   |
| HP Notebook           | 73        | 0.41%   |
| Lenovo Yoga           | 71        | 0.4%    |
| Fujitsu LIFEBOOK      | 70        | 0.4%    |
| HP EliteDesk          | 68        | 0.39%   |
| ASUS ZenBook          | 60        | 0.34%   |
| HP 250                | 58        | 0.33%   |
| Acer Swift            | 58        | 0.33%   |
| Lenovo Legion         | 53        | 0.3%    |
| HP ProDesk            | 51        | 0.29%   |
| Fujitsu ESPRIMO       | 51        | 0.29%   |
| Acer TravelMate       | 49        | 0.28%   |
| HP ZBook              | 47        | 0.27%   |
| Microsoft Surface     | 46        | 0.26%   |
| Gigabyte B450M        | 46        | 0.26%   |
| ASUS P8H61-M          | 46        | 0.26%   |
| Packard Bell EasyNote | 45        | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 1648      | 9.34%   |
| 2011    | 1553      | 8.81%   |
| 2013    | 1419      | 8.05%   |
| 2018    | 1328      | 7.53%   |
| 2019    | 1203      | 6.82%   |
| 2020    | 1194      | 6.77%   |
| 2017    | 1098      | 6.23%   |
| 2010    | 1098      | 6.23%   |
| 2014    | 1067      | 6.05%   |
| 2021    | 1032      | 5.85%   |
| 2015    | 909       | 5.15%   |
| 2016    | 904       | 5.13%   |
| 2009    | 893       | 5.06%   |
| 2008    | 859       | 4.87%   |
| 2007    | 579       | 3.28%   |
| 2022    | 415       | 2.35%   |
| 2006    | 239       | 1.36%   |
| 2023    | 72        | 0.41%   |
| 2005    | 68        | 0.39%   |
| 2004    | 26        | 0.15%   |
| 2003    | 15        | 0.09%   |
| Unknown | 14        | 0.08%   |
| 2002    | 3         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 9820      | 55.68%  |
| Desktop     | 6873      | 38.97%  |
| Convertible | 297       | 1.68%   |
| All in one  | 228       | 1.29%   |
| Mini pc     | 226       | 1.28%   |
| Tablet      | 132       | 0.75%   |
| Server      | 58        | 0.33%   |
| Stick pc    | 2         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 16215     | 91.35%  |
| Enabled  | 1536      | 8.65%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 17533     | 99.41%  |
| Yes  | 104       | 0.59%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 4339      | 24.22%  |
| 3.01-4.0        | 4116      | 22.98%  |
| 8.01-16.0       | 3158      | 17.63%  |
| 16.01-24.0      | 3150      | 17.58%  |
| 32.01-64.0      | 1192      | 6.65%   |
| 1.01-2.0        | 970       | 5.41%   |
| 2.01-3.0        | 350       | 1.95%   |
| 64.01-256.0     | 278       | 1.55%   |
| 24.01-32.0      | 227       | 1.27%   |
| 0.51-1.0        | 128       | 0.71%   |
| More than 256.0 | 5         | 0.03%   |
| 0.01-0.5        | 2         | 0.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 1.01-2.0        | 7757      | 39.51%  |
| 2.01-3.0        | 5249      | 26.74%  |
| 3.01-4.0        | 2312      | 11.78%  |
| 4.01-8.0        | 2157      | 10.99%  |
| 0.51-1.0        | 1501      | 7.65%   |
| 8.01-16.0       | 470       | 2.39%   |
| 0.01-0.5        | 92        | 0.47%   |
| 16.01-24.0      | 59        | 0.3%    |
| 24.01-32.0      | 21        | 0.11%   |
| Unknown         | 7         | 0.04%   |
| 32.01-64.0      | 5         | 0.03%   |
| More than 256.0 | 1         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 10744     | 59.03%  |
| 2       | 4736      | 26.02%  |
| 3       | 1451      | 7.97%   |
| 4       | 633       | 3.48%   |
| 5       | 289       | 1.59%   |
| 0       | 123       | 0.68%   |
| 6       | 116       | 0.64%   |
| 7       | 56        | 0.31%   |
| 8       | 27        | 0.15%   |
| 9       | 12        | 0.07%   |
| 10      | 4         | 0.02%   |
| 14      | 3         | 0.02%   |
| Unknown | 3         | 0.02%   |
| 27      | 2         | 0.01%   |
| 28      | 1         | 0.01%   |
| 22      | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 9300      | 52.31%  |
| Yes       | 8480      | 47.69%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 15697     | 88.81%  |
| No        | 1978      | 11.19%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 13483     | 75.93%  |
| No        | 4275      | 24.07%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 9701      | 54.27%  |
| No        | 8176      | 45.73%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 2939      | 16.57%  |
| Germany      | 2856      | 16.1%   |
| Brazil       | 1835      | 10.34%  |
| Russia       | 1112      | 6.27%   |
| France       | 831       | 4.68%   |
| UK           | 712       | 4.01%   |
| Italy        | 601       | 3.39%   |
| Canada       | 548       | 3.09%   |
| Spain        | 472       | 2.66%   |
| Poland       | 421       | 2.37%   |
| Netherlands  | 378       | 2.13%   |
| Australia    | 326       | 1.84%   |
| Ukraine      | 283       | 1.6%    |
| India        | 212       | 1.2%    |
| Mexico       | 201       | 1.13%   |
| Switzerland  | 199       | 1.12%   |
| Austria      | 195       | 1.1%    |
| Czechia      | 194       | 1.09%   |
| Argentina    | 184       | 1.04%   |
| Belgium      | 176       | 0.99%   |
| Sweden       | 163       | 0.92%   |
| Hungary      | 153       | 0.86%   |
| Portugal     | 148       | 0.83%   |
| Turkey       | 140       | 0.79%   |
| South Africa | 130       | 0.73%   |
| Finland      | 120       | 0.68%   |
| Greece       | 119       | 0.67%   |
| Romania      | 107       | 0.6%    |
| Slovakia     | 90        | 0.51%   |
| Colombia     | 87        | 0.49%   |
| Bulgaria     | 86        | 0.48%   |
| Denmark      | 83        | 0.47%   |
| Indonesia    | 76        | 0.43%   |
| New Zealand  | 71        | 0.4%    |
| Chile        | 71        | 0.4%    |
| Norway       | 67        | 0.38%   |
| Belarus      | 67        | 0.38%   |
| Ireland      | 63        | 0.36%   |
| Japan        | 55        | 0.31%   |
| Israel       | 53        | 0.3%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 259       | 1.37%   |
| Berlin            | 226       | 1.2%    |
| Sao Paulo         | 201       | 1.06%   |
| Vienna            | 120       | 0.64%   |
| Rio de Janeiro    | 115       | 0.61%   |
| Paris             | 113       | 0.6%    |
| Hamburg           | 112       | 0.59%   |
| St Petersburg     | 109       | 0.58%   |
| Munich            | 96        | 0.51%   |
| Warsaw            | 93        | 0.49%   |
| Sydney            | 92        | 0.49%   |
| Frankfurt am Main | 88        | 0.47%   |
| Kyiv              | 82        | 0.43%   |
| Milan             | 81        | 0.43%   |
| Amsterdam         | 76        | 0.4%    |
| Madrid            | 74        | 0.39%   |
| Cologne           | 71        | 0.38%   |
| Rome              | 70        | 0.37%   |
| Rockville         | 67        | 0.35%   |
| Montreal          | 65        | 0.34%   |
| London            | 63        | 0.33%   |
| Chicago           | 63        | 0.33%   |
| Melbourne         | 61        | 0.32%   |
| Budapest          | 59        | 0.31%   |
| Prague            | 58        | 0.31%   |
| Curitiba          | 58        | 0.31%   |
| Helsinki          | 55        | 0.29%   |
| Barcelona         | 53        | 0.28%   |
| Leipzig           | 52        | 0.28%   |
| Toronto           | 51        | 0.27%   |
| Athens            | 51        | 0.27%   |
| Porto Alegre      | 50        | 0.26%   |
| Belo Horizonte    | 50        | 0.26%   |
| Brisbane          | 49        | 0.26%   |
| Brasília         | 49        | 0.26%   |
| Zurich            | 48        | 0.25%   |
| Stuttgart         | 46        | 0.24%   |
| Istanbul          | 46        | 0.24%   |
| Sofia             | 44        | 0.23%   |
| Krasnodar         | 43        | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 4275      | 6547   | 16.6%   |
| Seagate                   | 4158      | 6253   | 16.15%  |
| Samsung Electronics       | 3539      | 5263   | 13.75%  |
| Toshiba                   | 1675      | 2132   | 6.51%   |
| Kingston                  | 1468      | 1926   | 5.7%    |
| SanDisk                   | 1277      | 1754   | 4.96%   |
| Unknown                   | 1047      | 1460   | 4.07%   |
| Hitachi                   | 975       | 1246   | 3.79%   |
| Crucial                   | 952       | 1345   | 3.7%    |
| Intel                     | 508       | 679    | 1.97%   |
| SK hynix                  | 469       | 536    | 1.82%   |
| HGST                      | 462       | 618    | 1.79%   |
| A-DATA Technology         | 362       | 479    | 1.41%   |
| China                     | 306       | 377    | 1.19%   |
| Micron Technology         | 267       | 342    | 1.04%   |
| Intenso                   | 188       | 251    | 0.73%   |
| Apple                     | 171       | 219    | 0.66%   |
| PNY                       | 145       | 181    | 0.56%   |
| Maxtor                    | 136       | 187    | 0.53%   |
| Fujitsu                   | 134       | 179    | 0.52%   |
| SPCC                      | 132       | 175    | 0.51%   |
| Phison                    | 128       | 176    | 0.5%    |
| KIOXIA                    | 126       | 150    | 0.49%   |
| Patriot                   | 118       | 149    | 0.46%   |
| OCZ                       | 114       | 144    | 0.44%   |
| Transcend                 | 105       | 144    | 0.41%   |
| Unknown                   | 103       | 124    | 0.4%    |
| LITEON                    | 98        | 120    | 0.38%   |
| Silicon Motion            | 95        | 135    | 0.37%   |
| GOODRAM                   | 89        | 119    | 0.35%   |
| JMicron Technology        | 88        | 117    | 0.34%   |
| Micron/Crucial Technology | 81        | 128    | 0.31%   |
| Corsair                   | 80        | 94     | 0.31%   |
| Apacer                    | 65        | 75     | 0.25%   |
| KingSpec                  | 62        | 86     | 0.24%   |
| LITEONIT                  | 60        | 69     | 0.23%   |
| Team                      | 55        | 74     | 0.21%   |
| Netac                     | 51        | 68     | 0.2%    |
| Plextor                   | 50        | 64     | 0.19%   |
| Lexar                     | 50        | 62     | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 373       | 1.32%   |
| Unknown MMC Card  32GB                              | 220       | 0.78%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 213       | 0.75%   |
| Samsung SSD 850 EVO 250GB                           | 213       | 0.75%   |
| Seagate ST500DM002-1BD142 500GB                     | 212       | 0.75%   |
| Seagate ST1000LM035-1RK172 1TB                      | 209       | 0.74%   |
| Samsung SSD 860 EVO 500GB                           | 205       | 0.73%   |
| Toshiba MQ01ABD100 1TB                              | 194       | 0.69%   |
| Unknown MMC Card  64GB                              | 185       | 0.65%   |
| Kingston SA400S37120G 120GB SSD                     | 171       | 0.61%   |
| Kingston SA400S37480G 480GB SSD                     | 170       | 0.6%    |
| Samsung SSD 850 EVO 500GB                           | 157       | 0.56%   |
| Toshiba MQ01ABF050 500GB                            | 147       | 0.52%   |
| Seagate ST1000DM010-2EP102 1TB                      | 145       | 0.51%   |
| Samsung SSD 860 EVO 1TB                             | 144       | 0.51%   |
| Toshiba DT01ACA100 1TB                              | 137       | 0.49%   |
| Crucial CT500MX500SSD1 500GB                        | 132       | 0.47%   |
| Kingston SV300S37A120G 120GB SSD                    | 128       | 0.45%   |
| Seagate ST500LT012-1DG142 500GB                     | 127       | 0.45%   |
| Crucial CT1000MX500SSD1 1TB                         | 124       | 0.44%   |
| Crucial CT240BX500SSD1 240GB                        | 122       | 0.43%   |
| Unknown SD/MMC/MS PRO 1GB                           | 116       | 0.41%   |
| Toshiba MQ04ABF100 1TB                              | 116       | 0.41%   |
| Seagate ST9500325AS 500GB                           | 116       | 0.41%   |
| Seagate ST2000DM008-2FR102 2TB                      | 109       | 0.39%   |
| Unknown MMC Card  128GB                             | 108       | 0.38%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 107       | 0.38%   |
| Samsung SSD 860 EVO 250GB                           | 106       | 0.38%   |
| Seagate Expansion 2TB                               | 105       | 0.37%   |
| Unknown                                             | 103       | 0.36%   |
| Seagate ST3500418AS 500GB                           | 102       | 0.36%   |
| Seagate ST1000DM003-1CH162 1TB                      | 99        | 0.35%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 98        | 0.35%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 96        | 0.34%   |
| Seagate ST1000DM003-1ER162 1TB                      | 95        | 0.34%   |
| SanDisk SSD PLUS 240GB                              | 94        | 0.33%   |
| HGST HTS721010A9E630 1TB                            | 92        | 0.33%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 91        | 0.32%   |
| Samsung NVMe SSD Drive 500GB                        | 81        | 0.29%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 79        | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4083      | 6087   | 34.72%  |
| WDC                 | 3546      | 5448   | 30.15%  |
| Toshiba             | 1394      | 1753   | 11.85%  |
| Hitachi             | 975       | 1246   | 8.29%   |
| Samsung Electronics | 633       | 890    | 5.38%   |
| HGST                | 462       | 618    | 3.93%   |
| Maxtor              | 132       | 183    | 1.12%   |
| Fujitsu             | 132       | 176    | 1.12%   |
| Unknown             | 127       | 162    | 1.08%   |
| Apple               | 48        | 55     | 0.41%   |
| SABRENT             | 38        | 45     | 0.32%   |
| Intenso             | 18        | 22     | 0.15%   |
| ASMT                | 18        | 28     | 0.15%   |
| External            | 14        | 15     | 0.12%   |
| USB3.0              | 10        | 11     | 0.09%   |
| JMicron Technology  | 10        | 21     | 0.09%   |
| Hewlett-Packard     | 10        | 15     | 0.09%   |
| ASMedia             | 9         | 11     | 0.08%   |
| USB                 | 8         | 9      | 0.07%   |
| HGST HTS            | 7         | 10     | 0.06%   |
| ExcelStor           | 7         | 9      | 0.06%   |
| WD MediaMax         | 6         | 15     | 0.05%   |
| Pioneer             | 5         | 6      | 0.04%   |
| PHD 3.0             | 5         | 6      | 0.04%   |
| Maxone              | 4         | 5      | 0.03%   |
| HPE                 | 4         | 5      | 0.03%   |
| Unknown             | 4         | 6      | 0.03%   |
| SSK                 | 3         | 3      | 0.03%   |
| SAGE                | 3         | 4      | 0.03%   |
| LaCie               | 3         | 3      | 0.03%   |
| KESU                | 3         | 4      | 0.03%   |
| ASMT109x            | 3         | 3      | 0.03%   |
| Apricorn            | 3         | 5      | 0.03%   |
| RSH-319             | 2         | 2      | 0.02%   |
| Maxtor 6            | 2         | 3      | 0.02%   |
| Initio              | 2         | 2      | 0.02%   |
| Inateck             | 2         | 2      | 0.02%   |
| IBM/Hitachi         | 2         | 2      | 0.02%   |
| HGST HUS            | 2         | 2      | 0.02%   |
| China               | 2         | 2      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1894      | 2722   | 21.43%  |
| Kingston            | 1255      | 1655   | 14.2%   |
| SanDisk             | 895       | 1226   | 10.13%  |
| Crucial             | 879       | 1243   | 9.94%   |
| WDC                 | 547       | 717    | 6.19%   |
| China               | 302       | 373    | 3.42%   |
| A-DATA Technology   | 302       | 405    | 3.42%   |
| Intel               | 204       | 269    | 2.31%   |
| Intenso             | 146       | 192    | 1.65%   |
| PNY                 | 135       | 170    | 1.53%   |
| Toshiba             | 129       | 164    | 1.46%   |
| Micron Technology   | 125       | 164    | 1.41%   |
| SPCC                | 120       | 161    | 1.36%   |
| OCZ                 | 113       | 142    | 1.28%   |
| Patriot             | 109       | 140    | 1.23%   |
| SK hynix            | 100       | 122    | 1.13%   |
| Transcend           | 95        | 126    | 1.07%   |
| LITEON              | 90        | 112    | 1.02%   |
| GOODRAM             | 87        | 117    | 0.98%   |
| Apple               | 83        | 94     | 0.94%   |
| KingSpec            | 61        | 85     | 0.69%   |
| Apacer              | 61        | 71     | 0.69%   |
| LITEONIT            | 60        | 69     | 0.68%   |
| Team                | 52        | 70     | 0.59%   |
| Corsair             | 51        | 61     | 0.58%   |
| Lexar               | 46        | 58     | 0.52%   |
| Plextor             | 45        | 56     | 0.51%   |
| Netac               | 45        | 61     | 0.51%   |
| JMicron Technology  | 43        | 53     | 0.49%   |
| Unknown             | 40        | 51     | 0.45%   |
| Hewlett-Packard     | 26        | 29     | 0.29%   |
| Seagate             | 25        | 43     | 0.28%   |
| TO Exter            | 24        | 32     | 0.27%   |
| KingDian            | 24        | 36     | 0.27%   |
| Gigabyte Technology | 23        | 37     | 0.26%   |
| Verbatim            | 21        | 34     | 0.24%   |
| Dogfish             | 21        | 27     | 0.24%   |
| ASMT                | 21        | 28     | 0.24%   |
| Leven               | 16        | 20     | 0.18%   |
| KingFast            | 16        | 16     | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 9916      | 16921  | 43.11%  |
| SSD     | 7817      | 11873  | 33.98%  |
| NVMe    | 3921      | 5475   | 17.05%  |
| MMC     | 948       | 1285   | 4.12%   |
| Unknown | 400       | 594    | 1.74%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 14545     | 27749  | 70.94%  |
| NVMe | 3916      | 5453   | 19.1%   |
| SAS  | 1095      | 1661   | 5.34%   |
| MMC  | 948       | 1285   | 4.62%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 11023     | 17422  | 59.86%  |
| 0.51-1.0        | 5126      | 7518   | 27.84%  |
| 1.01-2.0        | 1406      | 2373   | 7.64%   |
| 3.01-4.0        | 349       | 628    | 1.9%    |
| 2.01-3.0        | 253       | 408    | 1.37%   |
| 4.01-10.0       | 219       | 354    | 1.19%   |
| 10.01-20.0      | 35        | 88     | 0.19%   |
| 0               | 2         | 2      | 0.01%   |
| More than 100.0 | 1         | 1      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 5434      | 29.31%  |
| 251-500        | 4538      | 24.48%  |
| 501-1000       | 2907      | 15.68%  |
| 1001-2000      | 1542      | 8.32%   |
| 51-100         | 1243      | 6.7%    |
| More than 3000 | 936       | 5.05%   |
| 21-50          | 692       | 3.73%   |
| 2001-3000      | 589       | 3.18%   |
| 1-20           | 531       | 2.86%   |
| Unknown        | 128       | 0.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 5194      | 26.7%   |
| 21-50          | 4263      | 21.92%  |
| 101-250        | 2958      | 15.21%  |
| 51-100         | 2793      | 14.36%  |
| 251-500        | 1668      | 8.57%   |
| 501-1000       | 1183      | 6.08%   |
| 1001-2000      | 647       | 3.33%   |
| More than 3000 | 359       | 1.85%   |
| 2001-3000      | 259       | 1.33%   |
| Unknown        | 128       | 0.66%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB           | 30        | 34     | 1.78%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 29        | 30     | 1.72%   |
| Seagate ST500DM002-1BD142 500GB     | 28        | 32     | 1.66%   |
| Seagate ST1000LM035-1RK172 1TB      | 22        | 30     | 1.31%   |
| Seagate ST500LT012-9WS142 500GB     | 21        | 23     | 1.25%   |
| Seagate ST3500418AS 500GB           | 20        | 22     | 1.19%   |
| HGST HTS545050A7E680 500GB          | 20        | 42     | 1.19%   |
| Seagate ST500LT012-1DG142 500GB     | 19        | 20     | 1.13%   |
| Toshiba MQ01ABD100 1TB              | 17        | 19     | 1.01%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 16        | 17     | 0.95%   |
| Toshiba MQ01ABF050 500GB            | 14        | 15     | 0.83%   |
| HGST HTS721010A9E630 1TB            | 13        | 13     | 0.77%   |
| Seagate ST9320325AS 320GB           | 11        | 11     | 0.65%   |
| LITEON CV8-8E128-HP 128GB SSD       | 11        | 13     | 0.65%   |
| HGST HTS725050A7E630 500GB          | 11        | 11     | 0.65%   |
| Seagate ST31000528AS 1TB            | 10        | 12     | 0.59%   |
| HGST HTS541010A9E680 1TB            | 10        | 10     | 0.59%   |
| Crucial CT525MX300SSD1 528GB        | 9         | 9      | 0.54%   |
| WDC WD10EARS-00Y5B1 1TB             | 8         | 8      | 0.48%   |
| Seagate ST9500420AS 500GB           | 8         | 8      | 0.48%   |
| Seagate ST9250315AS 250GB           | 8         | 8      | 0.48%   |
| Seagate ST1000DM003-9YN162 1TB      | 8         | 9      | 0.48%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 7         | 7      | 0.42%   |
| WDC WD10JPVX-22JC3T0 1TB            | 7         | 7      | 0.42%   |
| Toshiba MQ04ABF100 1TB              | 7         | 7      | 0.42%   |
| Toshiba MK7575GSX 752GB             | 7         | 7      | 0.42%   |
| Seagate ST3500320AS 500GB           | 7         | 9      | 0.42%   |
| Samsung Electronics HD322HJ 320GB   | 7         | 15     | 0.42%   |
| Kingston SV300S37A120G 120GB SSD    | 7         | 7      | 0.42%   |
| Hitachi HTS547575A9E384 752GB       | 7         | 7      | 0.42%   |
| Hitachi HTS547550A9E384 500GB       | 7         | 7      | 0.42%   |
| HGST HTS545050A7E380 500GB          | 7         | 8      | 0.42%   |
| WDC WD10EZEX-00BN5A0 1TB            | 6         | 7      | 0.36%   |
| Seagate ST3500413AS 500GB           | 6         | 8      | 0.36%   |
| Seagate ST31000524AS 1TB            | 6         | 7      | 0.36%   |
| Seagate ST2000DM001-1CH164 2TB      | 6         | 6      | 0.36%   |
| SanDisk SSD PLUS 240GB              | 6         | 6      | 0.36%   |
| Samsung Electronics HD502HI 500GB   | 6         | 6      | 0.36%   |
| Hitachi HTS725050A9A364 500GB       | 6         | 7      | 0.36%   |
| Hitachi HTS545050B9A300 500GB       | 6         | 7      | 0.36%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 484       | 566    | 29.71%  |
| WDC                 | 332       | 411    | 20.38%  |
| Hitachi             | 142       | 157    | 8.72%   |
| Toshiba             | 129       | 138    | 7.92%   |
| Samsung Electronics | 121       | 155    | 7.43%   |
| HGST                | 74        | 99     | 4.54%   |
| SanDisk             | 51        | 59     | 3.13%   |
| Kingston            | 43        | 45     | 2.64%   |
| Crucial             | 39        | 49     | 2.39%   |
| Intel               | 29        | 29     | 1.78%   |
| Maxtor              | 21        | 27     | 1.29%   |
| SK hynix            | 18        | 22     | 1.1%    |
| China               | 14        | 16     | 0.86%   |
| LITEON              | 13        | 15     | 0.8%    |
| A-DATA Technology   | 11        | 11     | 0.68%   |
| Fujitsu             | 10        | 17     | 0.61%   |
| OCZ                 | 7         | 8      | 0.43%   |
| Micron Technology   | 7         | 10     | 0.43%   |
| LITEONIT            | 6         | 6      | 0.37%   |
| Corsair             | 6         | 9      | 0.37%   |
| Apple               | 6         | 6      | 0.37%   |
| Transcend           | 5         | 5      | 0.31%   |
| KingSpec            | 4         | 4      | 0.25%   |
| Intenso             | 4         | 4      | 0.25%   |
| XPG                 | 3         | 4      | 0.18%   |
| SPCC                | 3         | 4      | 0.18%   |
| Lenovo              | 3         | 3      | 0.18%   |
| SSSTC               | 2         | 2      | 0.12%   |
| PNY                 | 2         | 3      | 0.12%   |
| Plextor             | 2         | 2      | 0.12%   |
| Patriot             | 2         | 2      | 0.12%   |
| Leven               | 2         | 2      | 0.12%   |
| LDLC                | 2         | 2      | 0.12%   |
| Kingmax             | 2         | 2      | 0.12%   |
| Hewlett-Packard     | 2         | 2      | 0.12%   |
| ASMT                | 2         | 3      | 0.12%   |
| Unknown             | 2         | 3      | 0.12%   |
| WDC WDS2            | 1         | 1      | 0.06%   |
| USB3.0              | 1         | 1      | 0.06%   |
| Unknown             | 1         | 1      | 0.06%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 484       | 566    | 38.26%  |
| WDC                 | 318       | 394    | 25.14%  |
| Hitachi             | 142       | 157    | 11.23%  |
| Toshiba             | 123       | 131    | 9.72%   |
| Samsung Electronics | 79        | 108    | 6.25%   |
| HGST                | 74        | 99     | 5.85%   |
| Maxtor              | 21        | 27     | 1.66%   |
| Fujitsu             | 10        | 17     | 0.79%   |
| Apple               | 3         | 3      | 0.24%   |
| USB3.0              | 1         | 1      | 0.08%   |
| Unknown             | 1         | 1      | 0.08%   |
| MDT                 | 1         | 1      | 0.08%   |
| JMicron Technology  | 1         | 1      | 0.08%   |
| HGST HTS            | 1         | 1      | 0.08%   |
| Hewlett-Packard     | 1         | 1      | 0.08%   |
| FEASSO              | 1         | 2      | 0.08%   |
| ExcelStor           | 1         | 1      | 0.08%   |
| ASMT                | 1         | 1      | 0.08%   |
| ASMedia             | 1         | 1      | 0.08%   |
| Unknown             | 1         | 2      | 0.08%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 1192      | 1515   | 76.66%  |
| SSD  | 318       | 359    | 20.45%  |
| NVMe | 45        | 53     | 2.89%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                           | Computers | Drives | Percent |
|-------------------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-80V0TT0 500GB                    | 2         | 2      | 8.7%    |
| Toshiba DT01ACA100 1TB                          | 2         | 2      | 8.7%    |
| Samsung Electronics HD252HJ 250GB               | 2         | 2      | 8.7%    |
| WDC WD2003FYYS-18W0B0 2TB                       | 1         | 1      | 4.35%   |
| Toshiba THNSN5512GPU7 512GB                     | 1         | 1      | 4.35%   |
| Toshiba MQ01ABF032 320GB                        | 1         | 1      | 4.35%   |
| Toshiba MQ01ABD075 752GB                        | 1         | 1      | 4.35%   |
| Seagate ST9160821AS 160GB                       | 1         | 1      | 4.35%   |
| Seagate ST500LM012 HN-M500MBB 500GB             | 1         | 1      | 4.35%   |
| Seagate ST1000LM 024 HN-M101MBB 1TB             | 1         | 1      | 4.35%   |
| Samsung Electronics SSD 980 1TB                 | 1         | 1      | 4.35%   |
| Samsung Electronics MZMPC032HBCD-000H1 32GB SSD | 1         | 1      | 4.35%   |
| Samsung Electronics HM160HC 160GB               | 1         | 2      | 4.35%   |
| Samsung Electronics HD322GJ 320GB               | 1         | 1      | 4.35%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD  | 1         | 1      | 4.35%   |
| Hitachi HTS547550A9E384 500GB                   | 1         | 1      | 4.35%   |
| Hitachi HDS721050DLE630 500GB                   | 1         | 1      | 4.35%   |
| Hitachi HDS721050CLA362 500GB                   | 1         | 1      | 4.35%   |
| HGST HTS545050A7E380 500GB                      | 1         | 1      | 4.35%   |
| HGST HTS541010B7E610 1TB                        | 1         | 1      | 4.35%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 7      | 26.09%  |
| Toshiba             | 5         | 5      | 21.74%  |
| WDC                 | 3         | 3      | 13.04%  |
| Seagate             | 3         | 3      | 13.04%  |
| Hitachi             | 3         | 3      | 13.04%  |
| HGST                | 2         | 2      | 8.7%    |
| Micron Technology   | 1         | 1      | 4.35%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 11387     | 23957  | 59.72%  |
| Works    | 6140      | 10239  | 32.2%   |
| Malfunc  | 1516      | 1927   | 7.95%   |
| Failed   | 23        | 24     | 0.12%   |
| Limited  | 1         | 1      | 0.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 12160     | 57.43%  |
| AMD                              | 3475      | 16.41%  |
| Samsung Electronics              | 1303      | 6.15%   |
| SanDisk                          | 649       | 3.07%   |
| Nvidia                           | 407       | 1.92%   |
| SK hynix                         | 353       | 1.67%   |
| ASMedia Technology               | 316       | 1.49%   |
| Kingston Technology Company      | 269       | 1.27%   |
| Marvell Technology Group         | 260       | 1.23%   |
| JMicron Technology               | 259       | 1.22%   |
| Phison Electronics               | 235       | 1.11%   |
| Toshiba America Info Systems     | 160       | 0.76%   |
| Micron/Crucial Technology        | 157       | 0.74%   |
| Micron Technology                | 144       | 0.68%   |
| KIOXIA                           | 135       | 0.64%   |
| Silicon Motion                   | 134       | 0.63%   |
| VIA Technologies                 | 107       | 0.51%   |
| ADATA Technology                 | 101       | 0.48%   |
| Silicon Integrated Systems [SiS] | 79        | 0.37%   |
| Union Memory (Shenzhen)          | 62        | 0.29%   |
| Realtek Semiconductor            | 61        | 0.29%   |
| Apple                            | 40        | 0.19%   |
| Solid State Storage Technology   | 37        | 0.17%   |
| LSI Logic / Symbios Logic        | 37        | 0.17%   |
| Silicon Image                    | 32        | 0.15%   |
| Lite-On Technology               | 29        | 0.14%   |
| Broadcom / LSI                   | 22        | 0.1%    |
| Adaptec                          | 20        | 0.09%   |
| MAXIO Technology (Hangzhou)      | 18        | 0.09%   |
| Shenzhen Longsys Electronics     | 15        | 0.07%   |
| Seagate Technology               | 15        | 0.07%   |
| Lenovo                           | 13        | 0.06%   |
| Hewlett-Packard                  | 11        | 0.05%   |
| Integrated Technology Express    | 8         | 0.04%   |
| HighPoint Technologies           | 6         | 0.03%   |
| Yangtze Memory Technologies      | 5         | 0.02%   |
| Transcend                        | 5         | 0.02%   |
| OCZ Technology Group             | 5         | 0.02%   |
| ULi Electronics                  | 4         | 0.02%   |
| Lite-On IT Corp. / Plextor       | 3         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 2077      | 8.27%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 930       | 3.7%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 821       | 3.27%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 794       | 3.16%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 652       | 2.6%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 624       | 2.48%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 564       | 2.25%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 555       | 2.21%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 509       | 2.03%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 470       | 1.87%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 465       | 1.85%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 460       | 1.83%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 400       | 1.59%   |
| AMD 400 Series Chipset SATA Controller                                                  | 388       | 1.54%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 387       | 1.54%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 386       | 1.54%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 341       | 1.36%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 332       | 1.32%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 326       | 1.3%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 304       | 1.21%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 285       | 1.13%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 283       | 1.13%   |
| Samsung NVMe SSD Controller 980                                                         | 280       | 1.11%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 279       | 1.11%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 270       | 1.07%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 266       | 1.06%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 264       | 1.05%   |
| Intel SATA Controller [RAID mode]                                                       | 246       | 0.98%   |
| AMD 500 Series Chipset SATA Controller                                                  | 245       | 0.98%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 230       | 0.92%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 221       | 0.88%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 220       | 0.88%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 211       | 0.84%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 190       | 0.76%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 182       | 0.72%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 178       | 0.71%   |
| Nvidia MCP61 SATA Controller                                                            | 174       | 0.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 164       | 0.65%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 162       | 0.64%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 159       | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 13182     | 60.48%  |
| NVMe | 3934      | 18.05%  |
| IDE  | 3320      | 15.23%  |
| RAID | 1276      | 5.85%   |
| SAS  | 48        | 0.22%   |
| SCSI | 35        | 0.16%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 13416     | 76.07%  |
| AMD          | 4215      | 23.9%   |
| CentaurHauls | 5         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 154       | 0.87%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 139       | 0.79%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 135       | 0.76%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 126       | 0.71%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 125       | 0.71%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 113       | 0.64%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 112       | 0.63%   |
| AMD Ryzen 5 3600 6-Core Processor             | 109       | 0.62%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 107       | 0.61%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 104       | 0.59%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 101       | 0.57%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 101       | 0.57%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 99        | 0.56%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 98        | 0.55%   |
| AMD FX-8350 Eight-Core Processor              | 96        | 0.54%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 95        | 0.54%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 93        | 0.53%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 92        | 0.52%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 92        | 0.52%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 88        | 0.5%    |
| Intel Core i7-3770 CPU @ 3.40GHz              | 85        | 0.48%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 85        | 0.48%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 81        | 0.46%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 79        | 0.45%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 79        | 0.45%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 79        | 0.45%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 78        | 0.44%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 78        | 0.44%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 78        | 0.44%   |
| AMD FX-6300 Six-Core Processor                | 78        | 0.44%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 77        | 0.44%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 76        | 0.43%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 76        | 0.43%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 76        | 0.43%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 74        | 0.42%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 73        | 0.41%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 73        | 0.41%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 71        | 0.4%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 67        | 0.38%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 67        | 0.38%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 3843      | 21.75%  |
| Intel Core i7           | 2708      | 15.33%  |
| Intel Core i3           | 1572      | 8.9%    |
| Intel Celeron           | 1059      | 5.99%   |
| Intel Core 2 Duo        | 941       | 5.33%   |
| AMD Ryzen 5             | 886       | 5.01%   |
| Other                   | 779       | 4.41%   |
| AMD Ryzen 7             | 592       | 3.35%   |
| Intel Pentium           | 576       | 3.26%   |
| Intel Atom              | 423       | 2.39%   |
| AMD FX                  | 379       | 2.14%   |
| Intel Xeon              | 335       | 1.9%    |
| Intel Pentium Dual-Core | 291       | 1.65%   |
| AMD Ryzen 3             | 214       | 1.21%   |
| Intel Core 2 Quad       | 210       | 1.19%   |
| AMD A6                  | 184       | 1.04%   |
| AMD A8                  | 168       | 0.95%   |
| AMD A4                  | 162       | 0.92%   |
| Intel Pentium Dual      | 153       | 0.87%   |
| AMD Ryzen 9             | 145       | 0.82%   |
| Intel Core 2            | 134       | 0.76%   |
| AMD A10                 | 130       | 0.74%   |
| AMD Phenom II X4        | 121       | 0.68%   |
| AMD Athlon 64 X2        | 110       | 0.62%   |
| AMD Athlon II X2        | 98        | 0.55%   |
| AMD E                   | 90        | 0.51%   |
| Intel Genuine           | 80        | 0.45%   |
| Intel Pentium Silver    | 76        | 0.43%   |
| Intel Core i9           | 74        | 0.42%   |
| AMD E2                  | 66        | 0.37%   |
| AMD Athlon              | 64        | 0.36%   |
| Intel Pentium 4         | 63        | 0.36%   |
| AMD E1                  | 63        | 0.36%   |
| AMD Athlon II X4        | 63        | 0.36%   |
| AMD Turion 64 X2 Mobile | 47        | 0.27%   |
| AMD Ryzen 7 PRO         | 46        | 0.26%   |
| Intel Pentium D         | 43        | 0.24%   |
| AMD Ryzen 5 PRO         | 42        | 0.24%   |
| AMD Phenom II X6        | 42        | 0.24%   |
| Intel Pentium Gold      | 36        | 0.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 8400      | 47.52%  |
| 4       | 5892      | 33.33%  |
| 6       | 1358      | 7.68%   |
| 8       | 867       | 4.9%    |
| 1       | 570       | 3.22%   |
| 12      | 177       | 1%      |
| 3       | 162       | 0.92%   |
| 10      | 87        | 0.49%   |
| 16      | 70        | 0.4%    |
| 14      | 53        | 0.3%    |
| 24      | 10        | 0.06%   |
| Unknown | 9         | 0.05%   |
| 20      | 6         | 0.03%   |
| 18      | 5         | 0.03%   |
| 5       | 5         | 0.03%   |
| 32      | 2         | 0.01%   |
| 64      | 1         | 0.01%   |
| 40      | 1         | 0.01%   |
| 36      | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 17540     | 99.46%  |
| 2      | 96        | 0.54%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 10537     | 59.66%  |
| 1       | 7113      | 40.27%  |
| Unknown | 9         | 0.05%   |
| 4       | 2         | 0.01%   |
| 8       | 1         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 16644     | 93.67%  |
| Unknown        | 939       | 5.28%   |
| 32-bit         | 185       | 1.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1669      | 9.24%   |
| 0x206a7    | 1413      | 7.82%   |
| 0x306a9    | 1299      | 7.19%   |
| 0x306c3    | 931       | 5.15%   |
| 0x1067a    | 897       | 4.97%   |
| 0x40651    | 498       | 2.76%   |
| 0x20655    | 427       | 2.36%   |
| 0x906ea    | 389       | 2.15%   |
| 0x406e3    | 372       | 2.06%   |
| 0x506e3    | 368       | 2.04%   |
| 0x306d4    | 344       | 1.9%    |
| 0x6fd      | 341       | 1.89%   |
| 0x806c1    | 340       | 1.88%   |
| 0x806ea    | 334       | 1.85%   |
| 0x806e9    | 333       | 1.84%   |
| 0x906e9    | 301       | 1.67%   |
| 0x806ec    | 285       | 1.58%   |
| 0x06000852 | 266       | 1.47%   |
| 0x406c4    | 255       | 1.41%   |
| 0x010000c8 | 239       | 1.32%   |
| 0x30678    | 235       | 1.3%    |
| 0x10676    | 225       | 1.25%   |
| 0x08108109 | 215       | 1.19%   |
| 0x08701021 | 211       | 1.17%   |
| 0x20652    | 209       | 1.16%   |
| 0x06001119 | 172       | 0.95%   |
| 0x706a8    | 167       | 0.92%   |
| 0x0800820d | 160       | 0.89%   |
| 0x0a50000c | 159       | 0.88%   |
| 0x6fb      | 146       | 0.81%   |
| 0x506c9    | 141       | 0.78%   |
| 0x706e5    | 139       | 0.77%   |
| 0x08600106 | 134       | 0.74%   |
| 0x706a1    | 132       | 0.73%   |
| 0x05000119 | 132       | 0.73%   |
| 0x06006705 | 129       | 0.71%   |
| 0x406c3    | 122       | 0.68%   |
| 0x106e5    | 118       | 0.65%   |
| 0x08608103 | 115       | 0.64%   |
| 0x08108102 | 103       | 0.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 2053      | 11.62%  |
| Haswell          | 1595      | 9.03%   |
| SandyBridge      | 1528      | 8.65%   |
| IvyBridge        | 1429      | 8.09%   |
| Penryn           | 1207      | 6.83%   |
| Skylake          | 834       | 4.72%   |
| Core             | 734       | 4.15%   |
| Westmere         | 718       | 4.06%   |
| Silvermont       | 672       | 3.8%    |
| Zen 2            | 560       | 3.17%   |
| Zen+             | 525       | 2.97%   |
| K10              | 509       | 2.88%   |
| Piledriver       | 488       | 2.76%   |
| Zen 3            | 393       | 2.22%   |
| Broadwell        | 380       | 2.15%   |
| TigerLake        | 377       | 2.13%   |
| Unknown          | 353       | 2%      |
| Goldmont plus    | 311       | 1.76%   |
| Excavator        | 297       | 1.68%   |
| Zen              | 291       | 1.65%   |
| CometLake        | 273       | 1.55%   |
| K8 Hammer        | 234       | 1.32%   |
| Icelake          | 220       | 1.25%   |
| Bonnell          | 195       | 1.1%    |
| Nehalem          | 186       | 1.05%   |
| Bobcat           | 179       | 1.01%   |
| Alderlake Hybrid | 167       | 0.95%   |
| Goldmont         | 159       | 0.9%    |
| Puma             | 134       | 0.76%   |
| NetBurst         | 123       | 0.7%    |
| P6               | 110       | 0.62%   |
| K10 Llano        | 101       | 0.57%   |
| Jaguar           | 91        | 0.52%   |
| Steamroller      | 87        | 0.49%   |
| Bulldozer        | 78        | 0.44%   |
| Tremont          | 41        | 0.23%   |
| K8 & K10 hybrid  | 28        | 0.16%   |
| K6               | 5         | 0.03%   |
| Gracemont        | 3         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 10228     | 50.32%  |
| Nvidia                                       | 5171      | 25.44%  |
| AMD                                          | 4770      | 23.47%  |
| Silicon Integrated Systems [SiS]             | 62        | 0.31%   |
| Matrox Electronics Systems                   | 38        | 0.19%   |
| VIA Technologies                             | 35        | 0.17%   |
| ASPEED Technology                            | 9         | 0.04%   |
| ATI Technologies                             | 6         | 0.03%   |
| S3 Graphics                                  | 4         | 0.02%   |
| XGI Technology (eXtreme Graphics Innovation) | 2         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1160      | 5.5%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 834       | 3.96%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 518       | 2.46%   |
| Intel Core Processor Integrated Graphics Controller                                      | 462       | 2.19%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 392       | 1.86%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 384       | 1.82%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 351       | 1.66%   |
| Intel HD Graphics 620                                                                    | 338       | 1.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 337       | 1.6%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 335       | 1.59%   |
| Intel UHD Graphics 620                                                                   | 323       | 1.53%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 304       | 1.44%   |
| Intel HD Graphics 5500                                                                   | 298       | 1.41%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 290       | 1.38%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 279       | 1.32%   |
| Intel HD Graphics 530                                                                    | 258       | 1.22%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 255       | 1.21%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 245       | 1.16%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 243       | 1.15%   |
| AMD Renoir                                                                               | 235       | 1.11%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 229       | 1.09%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 209       | 0.99%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 192       | 0.91%   |
| Intel HD Graphics 630                                                                    | 192       | 0.91%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 191       | 0.91%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 182       | 0.86%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 179       | 0.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 179       | 0.85%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 173       | 0.82%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 169       | 0.8%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 154       | 0.73%   |
| AMD Lucienne                                                                             | 148       | 0.7%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 145       | 0.69%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 131       | 0.62%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 128       | 0.61%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 125       | 0.59%   |
| Nvidia GT218 [GeForce 210]                                                               | 124       | 0.59%   |
| Intel HD Graphics 500                                                                    | 123       | 0.58%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 119       | 0.56%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 119       | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| 1 x Intel           | 7823      | 44.12%  |
| 1 x AMD             | 3795      | 21.4%   |
| 1 x Nvidia          | 3219      | 18.16%  |
| Intel + Nvidia      | 1705      | 9.62%   |
| Intel + AMD         | 495       | 2.79%   |
| 2 x AMD             | 294       | 1.66%   |
| AMD + Nvidia        | 180       | 1.02%   |
| 1 x SiS             | 62        | 0.35%   |
| 2 x Nvidia          | 47        | 0.27%   |
| 1 x VIA             | 35        | 0.2%    |
| 1 x Matrox          | 29        | 0.16%   |
| Other               | 13        | 0.07%   |
| Nvidia + Matrox     | 6         | 0.03%   |
| 3 x AMD             | 5         | 0.03%   |
| 1 x ASPEED          | 5         | 0.03%   |
| Nvidia + ASPEED     | 4         | 0.02%   |
| AMD + Matrox        | 4         | 0.02%   |
| 1 x S3 Graphics     | 3         | 0.02%   |
| Nvidia + XGI        | 2         | 0.01%   |
| 2 x Intel           | 1         | 0.01%   |
| Intel + 2 x Nvidia  | 1         | 0.01%   |
| Intel + S3 Graphics | 1         | 0.01%   |
| AMD + 2 x Nvidia    | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 13623     | 76.2%   |
| Proprietary | 3447      | 19.28%  |
| Unknown     | 809       | 4.52%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 8675      | 47.97%  |
| 1.01-2.0   | 2748      | 15.2%   |
| 0.01-0.5   | 2595      | 14.35%  |
| 0.51-1.0   | 1658      | 9.17%   |
| 3.01-4.0   | 1199      | 6.63%   |
| 7.01-8.0   | 558       | 3.09%   |
| 5.01-6.0   | 358       | 1.98%   |
| 8.01-16.0  | 151       | 0.83%   |
| 2.01-3.0   | 122       | 0.67%   |
| 16.01-24.0 | 17        | 0.09%   |
| 4.01-5.0   | 3         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 2441      | 13.22%  |
| AU Optronics            | 2202      | 11.93%  |
| LG Display              | 1672      | 9.06%   |
| Chimei Innolux          | 1400      | 7.58%   |
| BOE                     | 1339      | 7.25%   |
| Goldstar                | 1008      | 5.46%   |
| Dell                    | 917       | 4.97%   |
| Acer                    | 666       | 3.61%   |
| Hewlett-Packard         | 665       | 3.6%    |
| AOC                     | 470       | 2.55%   |
| Philips                 | 402       | 2.18%   |
| Ancor Communications    | 398       | 2.16%   |
| BenQ                    | 394       | 2.13%   |
| Apple                   | 354       | 1.92%   |
| Chi Mei Optoelectronics | 321       | 1.74%   |
| Lenovo                  | 307       | 1.66%   |
| LG Electronics          | 184       | 1%      |
| ViewSonic               | 179       | 0.97%   |
| Iiyama                  | 173       | 0.94%   |
| Sharp                   | 164       | 0.89%   |
| Unknown                 | 162       | 0.88%   |
| Sony                    | 156       | 0.85%   |
| LG Philips              | 138       | 0.75%   |
| PANDA                   | 129       | 0.7%    |
| InfoVision              | 124       | 0.67%   |
| ASUSTek Computer        | 117       | 0.63%   |
| HannStar                | 86        | 0.47%   |
| Eizo                    | 86        | 0.47%   |
| Fujitsu Siemens         | 78        | 0.42%   |
| NEC Computers           | 74        | 0.4%    |
| Toshiba                 | 72        | 0.39%   |
| CPT                     | 64        | 0.35%   |
| Panasonic               | 60        | 0.33%   |
| Vizio                   | 53        | 0.29%   |
| Sceptre Tech            | 43        | 0.23%   |
| MSI                     | 43        | 0.23%   |
| Medion                  | 42        | 0.23%   |
| Vestel Elektronik       | 40        | 0.22%   |
| Unknown                 | 40        | 0.22%   |
| Seiko/Epson             | 37        | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch      | 101       | 0.53%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 93        | 0.49%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 83        | 0.43%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 79        | 0.41%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 62        | 0.32%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch             | 61        | 0.32%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch             | 60        | 0.31%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                    | 58        | 0.3%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 56        | 0.29%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 52        | 0.27%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 51        | 0.27%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 50        | 0.26%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch             | 46        | 0.24%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                  | 45        | 0.24%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 44        | 0.23%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch           | 44        | 0.23%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                      | 44        | 0.23%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 42        | 0.22%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 41        | 0.21%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch             | 41        | 0.21%   |
| Vestel Elektronik 40W_LCD_TV VES3700 1920x540                             | 40        | 0.21%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch         | 40        | 0.21%   |
| Unknown                                                                   | 40        | 0.21%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                      | 39        | 0.2%    |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch             | 38        | 0.2%    |
| InfoVision LCD Monitor IVO03F4 1920x1200 263x164mm 12.2-inch              | 34        | 0.18%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch           | 34        | 0.18%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch             | 34        | 0.18%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                     | 33        | 0.17%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch             | 32        | 0.17%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch         | 31        | 0.16%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch           | 31        | 0.16%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                 | 30        | 0.16%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                      | 30        | 0.16%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch             | 30        | 0.16%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch             | 30        | 0.16%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 29        | 0.15%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch             | 29        | 0.15%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch               | 28        | 0.15%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                     | 28        | 0.15%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 6767      | 37.71%  |
| 1366x768 (WXGA)    | 4363      | 24.31%  |
| 1600x900 (HD+)     | 974       | 5.43%   |
| 3840x2160 (4K)     | 806       | 4.49%   |
| 1280x1024 (SXGA)   | 648       | 3.61%   |
| 1280x800 (WXGA)    | 570       | 3.18%   |
| 1440x900 (WXGA+)   | 560       | 3.12%   |
| 1680x1050 (WSXGA+) | 554       | 3.09%   |
| 2560x1440 (QHD)    | 506       | 2.82%   |
| 1920x1200 (WUXGA)  | 394       | 2.2%    |
| Unknown            | 294       | 1.64%   |
| 1360x768           | 216       | 1.2%    |
| 2560x1080          | 150       | 0.84%   |
| 3840x1080          | 106       | 0.59%   |
| 3440x1440          | 103       | 0.57%   |
| 1024x768 (XGA)     | 90        | 0.5%    |
| 1024x600           | 90        | 0.5%    |
| 2560x1600          | 89        | 0.5%    |
| 1920x540           | 58        | 0.32%   |
| 2880x1800          | 56        | 0.31%   |
| 1600x1200          | 52        | 0.29%   |
| 1280x720 (HD)      | 34        | 0.19%   |
| 2160x1440          | 27        | 0.15%   |
| 2736x1824          | 25        | 0.14%   |
| 3200x1080          | 20        | 0.11%   |
| 1680x945           | 20        | 0.11%   |
| 3200x1800 (QHD+)   | 19        | 0.11%   |
| 3840x1200          | 17        | 0.09%   |
| 3600x1080          | 16        | 0.09%   |
| 3000x2000          | 15        | 0.08%   |
| 3840x2400          | 13        | 0.07%   |
| 3072x1920          | 12        | 0.07%   |
| 1920x1280          | 12        | 0.07%   |
| 5760x1080          | 11        | 0.06%   |
| 1280x960           | 11        | 0.06%   |
| 4480x1440          | 10        | 0.06%   |
| 2256x1504          | 10        | 0.06%   |
| 1280x768           | 10        | 0.06%   |
| 2288x1287          | 9         | 0.05%   |
| 5120x1440          | 8         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 4765      | 25.92%  |
| Unknown | 1404      | 7.64%   |
| 13      | 1392      | 7.57%   |
| 14      | 1309      | 7.12%   |
| 17      | 1223      | 6.65%   |
| 24      | 1148      | 6.25%   |
| 23      | 1066      | 5.8%    |
| 27      | 1000      | 5.44%   |
| 21      | 965       | 5.25%   |
| 19      | 598       | 3.25%   |
| 18      | 481       | 2.62%   |
| 20      | 345       | 1.88%   |
| 22      | 341       | 1.86%   |
| 31      | 326       | 1.77%   |
| 12      | 298       | 1.62%   |
| 11      | 290       | 1.58%   |
| 34      | 211       | 1.15%   |
| 84      | 131       | 0.71%   |
| 72      | 113       | 0.61%   |
| 10      | 110       | 0.6%    |
| 16      | 107       | 0.58%   |
| 40      | 99        | 0.54%   |
| 32      | 91        | 0.5%    |
| 54      | 84        | 0.46%   |
| 25      | 57        | 0.31%   |
| 26      | 53        | 0.29%   |
| 46      | 30        | 0.16%   |
| 52      | 26        | 0.14%   |
| 28      | 24        | 0.13%   |
| 48      | 22        | 0.12%   |
| 36      | 22        | 0.12%   |
| 65      | 19        | 0.1%    |
| 37      | 19        | 0.1%    |
| 29      | 19        | 0.1%    |
| 39      | 17        | 0.09%   |
| 42      | 15        | 0.08%   |
| 33      | 15        | 0.08%   |
| 74      | 12        | 0.07%   |
| 55      | 11        | 0.06%   |
| 35      | 11        | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 7006      | 38.62%  |
| 501-600        | 3044      | 16.78%  |
| 401-500        | 2357      | 12.99%  |
| 351-400        | 1475      | 8.13%   |
| Unknown        | 1404      | 7.74%   |
| 201-300        | 1318      | 7.27%   |
| 601-700        | 486       | 2.68%   |
| 701-800        | 339       | 1.87%   |
| 1501-2000      | 265       | 1.46%   |
| 1001-1500      | 245       | 1.35%   |
| 801-900        | 156       | 0.86%   |
| 901-1000       | 28        | 0.15%   |
| 101-200        | 11        | 0.06%   |
| More than 2000 | 4         | 0.02%   |
| 1-100          | 2         | 0.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 12312     | 72.83%  |
| 16/10   | 2116      | 12.52%  |
| Unknown | 1251      | 7.4%    |
| 5/4     | 574       | 3.4%    |
| 21/9    | 230       | 1.36%   |
| 4/3     | 194       | 1.15%   |
| 3/2     | 156       | 0.92%   |
| 32/9    | 27        | 0.16%   |
| 6/5     | 25        | 0.15%   |
| 1.96    | 5         | 0.03%   |
| 1.00    | 5         | 0.03%   |
| 0.62    | 2         | 0.01%   |
| 3.40    | 1         | 0.01%   |
| 3.20    | 1         | 0.01%   |
| 2.00    | 1         | 0.01%   |
| 11/10   | 1         | 0.01%   |
| 0.80    | 1         | 0.01%   |
| 0.75    | 1         | 0.01%   |
| 0.67    | 1         | 0.01%   |
| 0.56    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 4741      | 25.99%  |
| 201-250        | 2846      | 15.6%   |
| 81-90          | 2223      | 12.19%  |
| Unknown        | 1404      | 7.7%    |
| 151-200        | 1241      | 6.8%    |
| 301-350        | 1034      | 5.67%   |
| 121-130        | 780       | 4.28%   |
| 351-500        | 685       | 3.76%   |
| 141-150        | 662       | 3.63%   |
| 71-80          | 491       | 2.69%   |
| More than 1000 | 446       | 2.45%   |
| 251-300        | 426       | 2.34%   |
| 51-60          | 292       | 1.6%    |
| 501-1000       | 258       | 1.41%   |
| 61-70          | 257       | 1.41%   |
| 131-140        | 190       | 1.04%   |
| 41-50          | 111       | 0.61%   |
| 111-120        | 94        | 0.52%   |
| 91-100         | 47        | 0.26%   |
| 1-40           | 12        | 0.07%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 5993      | 33.71%  |
| 101-120       | 5391      | 30.32%  |
| 121-160       | 3695      | 20.78%  |
| Unknown       | 1404      | 7.9%    |
| 161-240       | 610       | 3.43%   |
| 1-50          | 465       | 2.62%   |
| More than 240 | 220       | 1.24%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 14584     | 81.26%  |
| 2     | 2337      | 13.02%  |
| 0     | 792       | 4.41%   |
| 3     | 217       | 1.21%   |
| 4     | 16        | 0.09%   |
| 6     | 1         | 0.01%   |
| 5     | 1         | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 10148     | 37.29%  |
| Intel                             | 7116      | 26.15%  |
| Qualcomm Atheros                  | 3562      | 13.09%  |
| Broadcom                          | 1688      | 6.2%    |
| Ralink Technology                 | 453       | 1.66%   |
| Marvell Technology Group          | 400       | 1.47%   |
| Broadcom Limited                  | 392       | 1.44%   |
| Ralink                            | 384       | 1.41%   |
| TP-Link                           | 364       | 1.34%   |
| Nvidia                            | 324       | 1.19%   |
| MediaTek                          | 271       | 1%      |
| Samsung Electronics               | 149       | 0.55%   |
| ASIX Electronics                  | 126       | 0.46%   |
| Qualcomm Atheros Communications   | 107       | 0.39%   |
| Xiaomi                            | 92        | 0.34%   |
| NetGear                           | 90        | 0.33%   |
| Huawei Technologies               | 84        | 0.31%   |
| D-Link                            | 72        | 0.26%   |
| ASUSTek Computer                  | 71        | 0.26%   |
| Ericsson Business Mobile Networks | 70        | 0.26%   |
| D-Link System                     | 69        | 0.25%   |
| JMicron Technology                | 68        | 0.25%   |
| Dell                              | 68        | 0.25%   |
| Silicon Integrated Systems [SiS]  | 64        | 0.24%   |
| VIA Technologies                  | 62        | 0.23%   |
| Sierra Wireless                   | 54        | 0.2%    |
| Hewlett-Packard                   | 50        | 0.18%   |
| Qualcomm                          | 49        | 0.18%   |
| Edimax Technology                 | 47        | 0.17%   |
| Microsoft                         | 43        | 0.16%   |
| Motorola PCS                      | 42        | 0.15%   |
| Belkin Components                 | 39        | 0.14%   |
| Linksys                           | 36        | 0.13%   |
| DisplayLink                       | 36        | 0.13%   |
| Aquantia                          | 32        | 0.12%   |
| Lenovo                            | 27        | 0.1%    |
| IMC Networks                      | 25        | 0.09%   |
| AVM                               | 21        | 0.08%   |
| ICS Advent                        | 20        | 0.07%   |
| OPPO Electronics                  | 17        | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 6756      | 21.28%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 1545      | 4.87%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 740       | 2.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 506       | 1.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 502       | 1.58%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 500       | 1.58%   |
| Intel Wi-Fi 6 AX200                                                     | 467       | 1.47%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 436       | 1.37%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 425       | 1.34%   |
| Intel Wireless 7260                                                     | 372       | 1.17%   |
| Intel Wireless 8265 / 8275                                              | 326       | 1.03%   |
| Intel Wireless 7265                                                     | 325       | 1.02%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 284       | 0.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 284       | 0.89%   |
| Intel Wi-Fi 6 AX201                                                     | 266       | 0.84%   |
| Realtek RTL8125 2.5GbE Controller                                       | 254       | 0.8%    |
| Intel Wireless 3165                                                     | 253       | 0.8%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 252       | 0.79%   |
| Intel Ethernet Connection (2) I219-V                                    | 244       | 0.77%   |
| Intel Ethernet Connection I217-LM                                       | 241       | 0.76%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 236       | 0.74%   |
| Intel Wireless 8260                                                     | 234       | 0.74%   |
| Intel I211 Gigabit Network Connection                                   | 230       | 0.72%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 222       | 0.7%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 208       | 0.66%   |
| Broadcom BCM43142 802.11b/g/n                                           | 199       | 0.63%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 192       | 0.6%    |
| Ralink MT7601U Wireless Adapter                                         | 184       | 0.58%   |
| Realtek 802.11ac NIC                                                    | 182       | 0.57%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 174       | 0.55%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 173       | 0.54%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 171       | 0.54%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 167       | 0.53%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 166       | 0.52%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 165       | 0.52%   |
| Intel Wireless 3160                                                     | 165       | 0.52%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 160       | 0.5%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 149       | 0.47%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 147       | 0.46%   |
| Nvidia MCP61 Ethernet                                                   | 146       | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 5174      | 35.79%  |
| Qualcomm Atheros                      | 2859      | 19.77%  |
| Realtek Semiconductor                 | 2772      | 19.17%  |
| Broadcom                              | 1128      | 7.8%    |
| Ralink Technology                     | 453       | 3.13%   |
| Ralink                                | 384       | 2.66%   |
| TP-Link                               | 354       | 2.45%   |
| MediaTek                              | 238       | 1.65%   |
| Broadcom Limited                      | 225       | 1.56%   |
| Qualcomm Atheros Communications       | 107       | 0.74%   |
| NetGear                               | 89        | 0.62%   |
| ASUSTek Computer                      | 71        | 0.49%   |
| D-Link                                | 70        | 0.48%   |
| Sierra Wireless                       | 54        | 0.37%   |
| Edimax Technology                     | 47        | 0.33%   |
| D-Link System                         | 47        | 0.33%   |
| Microsoft                             | 37        | 0.26%   |
| Marvell Technology Group              | 36        | 0.25%   |
| Belkin Components                     | 36        | 0.25%   |
| Dell                                  | 35        | 0.24%   |
| Linksys                               | 34        | 0.24%   |
| IMC Networks                          | 25        | 0.17%   |
| AVM                                   | 21        | 0.15%   |
| Ericsson Business Mobile Networks     | 18        | 0.12%   |
| Qualcomm                              | 14        | 0.1%    |
| Sitecom Europe                        | 12        | 0.08%   |
| Hewlett-Packard                       | 10        | 0.07%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 9         | 0.06%   |
| Tenda                                 | 8         | 0.06%   |
| Fibocom                               | 8         | 0.06%   |
| ZyDAS                                 | 7         | 0.05%   |
| Accton Technology                     | 7         | 0.05%   |
| TRENDnet                              | 6         | 0.04%   |
| Texas Instruments                     | 6         | 0.04%   |
| Micro Star International              | 6         | 0.04%   |
| Gemtek                                | 6         | 0.04%   |
| ZyXEL Communications                  | 5         | 0.03%   |
| Fujitsu Siemens Computers             | 4         | 0.03%   |
| Philips (or NXP)                      | 3         | 0.02%   |
| Mercucys                              | 3         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 506       | 3.46%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 502       | 3.44%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 500       | 3.42%   |
| Intel Wi-Fi 6 AX200                                                     | 467       | 3.2%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 436       | 2.98%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 425       | 2.91%   |
| Intel Wireless 7260                                                     | 372       | 2.55%   |
| Intel Wireless 8265 / 8275                                              | 326       | 2.23%   |
| Intel Wireless 7265                                                     | 325       | 2.22%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 284       | 1.94%   |
| Intel Wi-Fi 6 AX201                                                     | 266       | 1.82%   |
| Intel Wireless 3165                                                     | 253       | 1.73%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 252       | 1.72%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 236       | 1.62%   |
| Intel Wireless 8260                                                     | 234       | 1.6%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 222       | 1.52%   |
| Broadcom BCM43142 802.11b/g/n                                           | 199       | 1.36%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 192       | 1.31%   |
| Ralink MT7601U Wireless Adapter                                         | 184       | 1.26%   |
| Realtek 802.11ac NIC                                                    | 182       | 1.25%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 174       | 1.19%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 173       | 1.18%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 171       | 1.17%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 167       | 1.14%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 165       | 1.13%   |
| Intel Wireless 3160                                                     | 165       | 1.13%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 160       | 1.1%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 149       | 1.02%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 147       | 1.01%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 139       | 0.95%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 138       | 0.94%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 135       | 0.92%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 124       | 0.85%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 124       | 0.85%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 120       | 0.82%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 119       | 0.81%   |
| Intel WiFi Link 5100                                                    | 115       | 0.79%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 114       | 0.78%   |
| Intel Wireless-AC 9260                                                  | 111       | 0.76%   |
| Intel Centrino Advanced-N 6200                                          | 109       | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 9054      | 54.76%  |
| Intel                                  | 3737      | 22.6%   |
| Qualcomm Atheros                       | 1074      | 6.5%    |
| Broadcom                               | 773       | 4.68%   |
| Marvell Technology Group               | 364       | 2.2%    |
| Nvidia                                 | 323       | 1.95%   |
| Broadcom Limited                       | 174       | 1.05%   |
| Samsung Electronics                    | 145       | 0.88%   |
| ASIX Electronics                       | 126       | 0.76%   |
| Xiaomi                                 | 90        | 0.54%   |
| JMicron Technology                     | 68        | 0.41%   |
| Silicon Integrated Systems [SiS]       | 61        | 0.37%   |
| VIA Technologies                       | 59        | 0.36%   |
| Huawei Technologies                    | 52        | 0.31%   |
| DisplayLink                            | 36        | 0.22%   |
| Aquantia                               | 32        | 0.19%   |
| Qualcomm                               | 31        | 0.19%   |
| MediaTek                               | 31        | 0.19%   |
| Motorola PCS                           | 30        | 0.18%   |
| Lenovo                                 | 26        | 0.16%   |
| D-Link System                          | 22        | 0.13%   |
| ICS Advent                             | 20        | 0.12%   |
| Hewlett-Packard                        | 18        | 0.11%   |
| Google                                 | 17        | 0.1%    |
| Attansic Technology                    | 17        | 0.1%    |
| OPPO Electronics                       | 16        | 0.1%    |
| Sundance Technology Inc / IC Plus      | 11        | 0.07%   |
| Apple                                  | 11        | 0.07%   |
| TP-Link                                | 10        | 0.06%   |
| ZTE WCDMA Technologies MSM             | 8         | 0.05%   |
| T & A Mobile Phones                    | 7         | 0.04%   |
| Sony Ericsson Mobile Communications AB | 6         | 0.04%   |
| Microsoft                              | 6         | 0.04%   |
| LG Electronics                         | 6         | 0.04%   |
| HMD Global                             | 6         | 0.04%   |
| OnePlus Technology (Shenzhen)          | 4         | 0.02%   |
| Microchip Technology                   | 4         | 0.02%   |
| HTC (High Tech Computer)               | 4         | 0.02%   |
| 3Com                                   | 4         | 0.02%   |
| Spreadtrum Communications              | 3         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6756      | 40.21%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1545      | 9.19%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 740       | 4.4%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 284       | 1.69%   |
| Realtek RTL8125 2.5GbE Controller                                 | 254       | 1.51%   |
| Intel Ethernet Connection (2) I219-V                              | 244       | 1.45%   |
| Intel Ethernet Connection I217-LM                                 | 241       | 1.43%   |
| Intel I211 Gigabit Network Connection                             | 230       | 1.37%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 208       | 1.24%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 166       | 0.99%   |
| Nvidia MCP61 Ethernet                                             | 146       | 0.87%   |
| Intel 82579V Gigabit Network Connection                           | 143       | 0.85%   |
| Intel Ethernet Controller I225-V                                  | 141       | 0.84%   |
| Intel 82577LM Gigabit Network Connection                          | 138       | 0.82%   |
| Intel Ethernet Connection I217-V                                  | 113       | 0.67%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 112       | 0.67%   |
| Intel Ethernet Connection I218-LM                                 | 111       | 0.66%   |
| Intel Ethernet Connection (7) I219-V                              | 111       | 0.66%   |
| Intel Ethernet Connection I219-LM                                 | 108       | 0.64%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 107       | 0.64%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 101       | 0.6%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 101       | 0.6%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 100       | 0.6%    |
| ASIX AX88179 Gigabit Ethernet                                     | 97        | 0.58%   |
| Intel Ethernet Connection (4) I219-LM                             | 93        | 0.55%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 90        | 0.54%   |
| Intel Ethernet Connection (2) I219-LM                             | 90        | 0.54%   |
| Intel 82567LM Gigabit Network Connection                          | 90        | 0.54%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 86        | 0.51%   |
| Intel Ethernet Connection (3) I218-LM                             | 84        | 0.5%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 83        | 0.49%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 80        | 0.48%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 78        | 0.46%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 76        | 0.45%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 74        | 0.44%   |
| Intel Ethernet Connection (2) I218-V                              | 70        | 0.42%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 64        | 0.38%   |
| Nvidia MCP79 Ethernet                                             | 63        | 0.37%   |
| Intel 82574L Gigabit Network Connection                           | 63        | 0.37%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 63        | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 15680     | 53.17%  |
| WiFi     | 13479     | 45.7%   |
| Modem    | 282       | 0.96%   |
| Unknown  | 51        | 0.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 10496     | 56.86%  |
| Ethernet | 7953      | 43.08%  |
| Unknown  | 8         | 0.04%   |
| Modem    | 2         | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 9951      | 56.24%  |
| 1     | 7121      | 40.24%  |
| 0     | 333       | 1.88%   |
| 3     | 245       | 1.38%   |
| 4     | 30        | 0.17%   |
| 5     | 7         | 0.04%   |
| 6     | 4         | 0.02%   |
| 7     | 3         | 0.02%   |
| 10    | 1         | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 13983     | 77.75%  |
| Yes     | 4000      | 22.24%  |
| Unknown | 1         | 0.01%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 3805      | 38.72%  |
| Realtek Semiconductor           | 1187      | 12.08%  |
| Qualcomm Atheros Communications | 933       | 9.49%   |
| Cambridge Silicon Radio         | 751       | 7.64%   |
| Broadcom                        | 637       | 6.48%   |
| Lite-On Technology              | 410       | 4.17%   |
| IMC Networks                    | 389       | 3.96%   |
| Apple                           | 351       | 3.57%   |
| Foxconn / Hon Hai               | 293       | 2.98%   |
| Dell                            | 169       | 1.72%   |
| ASUSTek Computer                | 161       | 1.64%   |
| Hewlett-Packard                 | 136       | 1.38%   |
| Ralink                          | 120       | 1.22%   |
| Toshiba                         | 91        | 0.93%   |
| MediaTek                        | 45        | 0.46%   |
| Realtek                         | 42        | 0.43%   |
| Alps Electric                   | 36        | 0.37%   |
| Foxconn International           | 35        | 0.36%   |
| Ralink Technology               | 31        | 0.32%   |
| Marvell Semiconductor           | 31        | 0.32%   |
| TP-Link                         | 21        | 0.21%   |
| Integrated System Solution      | 18        | 0.18%   |
| Taiyo Yuden                     | 13        | 0.13%   |
| Qcom                            | 13        | 0.13%   |
| Chicony Electronics             | 12        | 0.12%   |
| Edimax Technology               | 11        | 0.11%   |
| Belkin Components               | 11        | 0.11%   |
| Smart Modular Technologies      | 9         | 0.09%   |
| Askey Computer                  | 9         | 0.09%   |
| Micro Star International        | 7         | 0.07%   |
| Dynex                           | 7         | 0.07%   |
| Unknown                         | 6         | 0.06%   |
| Opticis                         | 5         | 0.05%   |
| Conwise Technology              | 5         | 0.05%   |
| Logitech                        | 4         | 0.04%   |
| Fujitsu                         | 4         | 0.04%   |
| USI                             | 3         | 0.03%   |
| Roper                           | 2         | 0.02%   |
| Primax Electronics              | 2         | 0.02%   |
| Motorola PCS                    | 2         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 1613      | 16.39%  |
| Realtek Bluetooth Radio                             | 757       | 7.69%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 750       | 7.62%   |
| Intel AX201 Bluetooth                               | 534       | 5.43%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 504       | 5.12%   |
| Intel AX200 Bluetooth                               | 436       | 4.43%   |
| Qualcomm Atheros  Bluetooth Device                  | 422       | 4.29%   |
| Realtek  Bluetooth 4.2 Adapter                      | 335       | 3.4%    |
| Intel Bluetooth Device                              | 254       | 2.58%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 180       | 1.83%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 159       | 1.62%   |
| Apple Bluetooth Host Controller                     | 144       | 1.46%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 143       | 1.45%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 141       | 1.43%   |
| IMC Networks Bluetooth Device                       | 125       | 1.27%   |
| Ralink RT3290 Bluetooth                             | 120       | 1.22%   |
| IMC Networks Bluetooth Radio                        | 117       | 1.19%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 108       | 1.1%    |
| Intel AX210 Bluetooth                               | 96        | 0.98%   |
| Apple Bluetooth USB Host Controller                 | 94        | 0.96%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 91        | 0.92%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 91        | 0.92%   |
| Lite-On Bluetooth Device                            | 90        | 0.91%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 86        | 0.87%   |
| Foxconn / Hon Hai Bluetooth Device                  | 84        | 0.85%   |
| Lite-On Atheros AR3012 Bluetooth                    | 76        | 0.77%   |
| HP Broadcom 2070 Bluetooth Combo                    | 70        | 0.71%   |
| Broadcom BCM2045B (BDC-2.1)                         | 67        | 0.68%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 62        | 0.63%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 60        | 0.61%   |
| IMC Networks Wireless_Device                        | 58        | 0.59%   |
| Dell DW375 Bluetooth Module                         | 58        | 0.59%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 56        | 0.57%   |
| Broadcom BCM2045 Bluetooth                          | 56        | 0.57%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 54        | 0.55%   |
| Apple Bluetooth HCI                                 | 51        | 0.52%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 49        | 0.5%    |
| Realtek RTL8821A Bluetooth                          | 45        | 0.46%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 45        | 0.46%   |
| Lite-On Wireless_Device                             | 40        | 0.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 12743     | 53.84%  |
| AMD                              | 4987      | 21.07%  |
| Nvidia                           | 3731      | 15.76%  |
| C-Media Electronics              | 404       | 1.71%   |
| Creative Labs                    | 176       | 0.74%   |
| Logitech                         | 170       | 0.72%   |
| Texas Instruments                | 91        | 0.38%   |
| Generalplus Technology           | 83        | 0.35%   |
| VIA Technologies                 | 81        | 0.34%   |
| Silicon Integrated Systems [SiS] | 79        | 0.33%   |
| JMTek                            | 75        | 0.32%   |
| GN Netcom                        | 66        | 0.28%   |
| Kingston Technology              | 62        | 0.26%   |
| Creative Technology              | 49        | 0.21%   |
| Plantronics                      | 44        | 0.19%   |
| Realtek Semiconductor            | 39        | 0.16%   |
| ASUSTek Computer                 | 38        | 0.16%   |
| Razer USA                        | 36        | 0.15%   |
| Focusrite-Novation               | 32        | 0.14%   |
| SteelSeries ApS                  | 31        | 0.13%   |
| Lenovo                           | 31        | 0.13%   |
| Corsair                          | 30        | 0.13%   |
| Apple                            | 24        | 0.1%    |
| Tenx Technology                  | 22        | 0.09%   |
| Hewlett-Packard                  | 22        | 0.09%   |
| Samson Technologies              | 19        | 0.08%   |
| Microsoft                        | 17        | 0.07%   |
| Dell                             | 17        | 0.07%   |
| Sennheiser Communications        | 15        | 0.06%   |
| Micro Star International         | 15        | 0.06%   |
| BEHRINGER International          | 14        | 0.06%   |
| Jieli Technology                 | 13        | 0.05%   |
| Blue Microphones                 | 13        | 0.05%   |
| Sony                             | 12        | 0.05%   |
| M-Audio                          | 12        | 0.05%   |
| XMOS                             | 11        | 0.05%   |
| Yamaha                           | 9         | 0.04%   |
| Trust                            | 9         | 0.04%   |
| SAVITECH                         | 9         | 0.04%   |
| KTMicro                          | 9         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1444      | 5.13%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1411      | 5.01%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 1163      | 4.13%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 1121      | 3.98%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 924       | 3.28%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 890       | 3.16%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 783       | 2.78%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 699       | 2.48%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 690       | 2.45%   |
| AMD FCH Azalia Controller                                                                         | 659       | 2.34%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 641       | 2.28%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 594       | 2.11%   |
| Intel 8 Series HD Audio Controller                                                                | 524       | 1.86%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 521       | 1.85%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 453       | 1.61%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 446       | 1.58%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 446       | 1.58%   |
| Intel Cannon Lake PCH cAVS                                                                        | 433       | 1.54%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 376       | 1.33%   |
| Intel Broadwell-U Audio Controller                                                                | 364       | 1.29%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 353       | 1.25%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 334       | 1.19%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 319       | 1.13%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 316       | 1.12%   |
| AMD Kabini HDMI/DP Audio                                                                          | 313       | 1.11%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 308       | 1.09%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 292       | 1.04%   |
| Intel 200 Series PCH HD Audio                                                                     | 282       | 1%      |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 279       | 0.99%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 268       | 0.95%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 254       | 0.9%    |
| Nvidia High Definition Audio Controller                                                           | 253       | 0.9%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 248       | 0.88%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 237       | 0.84%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 236       | 0.84%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 212       | 0.75%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 195       | 0.69%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 189       | 0.67%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 185       | 0.66%   |
| AMD High Definition Audio Controller                                                              | 181       | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1925      | 20.85%  |
| SK hynix            | 1626      | 17.61%  |
| Kingston            | 1021      | 11.06%  |
| Unknown             | 931       | 10.08%  |
| Micron Technology   | 847       | 9.17%   |
| Crucial             | 559       | 6.05%   |
| Corsair             | 463       | 5.01%   |
| G.Skill             | 295       | 3.19%   |
| A-DATA Technology   | 180       | 1.95%   |
| Elpida              | 179       | 1.94%   |
| Ramaxel Technology  | 172       | 1.86%   |
| Unknown (ABCD)      | 134       | 1.45%   |
| Nanya Technology    | 121       | 1.31%   |
| Smart               | 88        | 0.95%   |
| Team                | 70        | 0.76%   |
| Patriot             | 56        | 0.61%   |
| Unknown             | 53        | 0.57%   |
| GOODRAM             | 36        | 0.39%   |
| Transcend           | 33        | 0.36%   |
| AMD                 | 26        | 0.28%   |
| Teikon              | 25        | 0.27%   |
| Apacer              | 25        | 0.27%   |
| PNY                 | 16        | 0.17%   |
| ASint Technology    | 16        | 0.17%   |
| Avant               | 15        | 0.16%   |
| Unifosa             | 13        | 0.14%   |
| Sesame              | 13        | 0.14%   |
| Qimonda             | 13        | 0.14%   |
| Silicon Power       | 12        | 0.13%   |
| Kingmax             | 12        | 0.13%   |
| Smart Brazil        | 11        | 0.12%   |
| Multilaser          | 10        | 0.11%   |
| Kllisre             | 10        | 0.11%   |
| GeIL                | 10        | 0.11%   |
| Goldkey             | 8         | 0.09%   |
| Timetec             | 7         | 0.08%   |
| Qumo                | 6         | 0.06%   |
| PUSKILL             | 6         | 0.06%   |
| High Bridge         | 6         | 0.06%   |
| fef5                | 6         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 107       | 1.08%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 85        | 0.86%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 80        | 0.81%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 76        | 0.77%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 66        | 0.67%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 65        | 0.66%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 64        | 0.64%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 60        | 0.6%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 60        | 0.6%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 55        | 0.55%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 54        | 0.54%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 53        | 0.53%   |
| Unknown                                                          | 53        | 0.53%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 51        | 0.51%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 50        | 0.5%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 47        | 0.47%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 47        | 0.47%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 46        | 0.46%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 45        | 0.45%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 45        | 0.45%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 43        | 0.43%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 43        | 0.43%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 41        | 0.41%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 39        | 0.39%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 37        | 0.37%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 37        | 0.37%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 37        | 0.37%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 33        | 0.33%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 33        | 0.33%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 33        | 0.33%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 33        | 0.33%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 31        | 0.31%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 31        | 0.31%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 30        | 0.3%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 30        | 0.3%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 30        | 0.3%    |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s         | 30        | 0.3%    |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 29        | 0.29%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 29        | 0.29%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 29        | 0.29%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind         | Computers | Percent |
|--------------|-----------|---------|
| DDR4         | 3242      | 40.83%  |
| DDR3         | 3141      | 39.56%  |
| DDR2         | 400       | 5.04%   |
| LPDDR4       | 326       | 4.11%   |
| SDRAM        | 255       | 3.21%   |
| Unknown      | 236       | 2.97%   |
| LPDDR3       | 151       | 1.9%    |
| DDR5         | 69        | 0.87%   |
| DDR          | 60        | 0.76%   |
| LPDDR5       | 36        | 0.45%   |
| DRAM         | 20        | 0.25%   |
| RAM          | 2         | 0.03%   |
| EEPROM       | 1         | 0.01%   |
| DDR2 FB-DIMM | 1         | 0.01%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 4713      | 59.82%  |
| DIMM         | 2662      | 33.79%  |
| Row Of Chips | 430       | 5.46%   |
| Chip         | 31        | 0.39%   |
| Unknown      | 31        | 0.39%   |
| FB-DIMM      | 9         | 0.11%   |
| RIMM         | 3         | 0.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 3225      | 37.13%  |
| 4096  | 2663      | 30.66%  |
| 2048  | 1292      | 14.88%  |
| 16384 | 965       | 11.11%  |
| 1024  | 294       | 3.39%   |
| 32768 | 200       | 2.3%    |
| 512   | 33        | 0.38%   |
| 1536  | 5         | 0.06%   |
| 256   | 4         | 0.05%   |
| 3072  | 1         | 0.01%   |
| 16    | 1         | 0.01%   |
| 8     | 1         | 0.01%   |
| 1     | 1         | 0.01%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 2021      | 23.36%  |
| 3200    | 1075      | 12.43%  |
| 2667    | 1068      | 12.35%  |
| 1333    | 729       | 8.43%   |
| 2400    | 662       | 7.65%   |
| 2133    | 361       | 4.17%   |
| 1334    | 329       | 3.8%    |
| 667     | 219       | 2.53%   |
| 800     | 211       | 2.44%   |
| 3600    | 188       | 2.17%   |
| Unknown | 179       | 2.07%   |
| 1867    | 157       | 1.82%   |
| 1067    | 121       | 1.4%    |
| 3266    | 103       | 1.19%   |
| 4267    | 95        | 1.1%    |
| 1066    | 89        | 1.03%   |
| 1800    | 66        | 0.76%   |
| 3000    | 65        | 0.75%   |
| 4199    | 64        | 0.74%   |
| 1866    | 61        | 0.71%   |
| 4800    | 55        | 0.64%   |
| 2933    | 54        | 0.62%   |
| 2048    | 47        | 0.54%   |
| 3400    | 43        | 0.5%    |
| 3733    | 41        | 0.47%   |
| 6400    | 39        | 0.45%   |
| 2666    | 30        | 0.35%   |
| 3800    | 28        | 0.32%   |
| 8400    | 25        | 0.29%   |
| 2800    | 25        | 0.29%   |
| 533     | 25        | 0.29%   |
| 3866    | 24        | 0.28%   |
| 400     | 24        | 0.28%   |
| 3533    | 23        | 0.27%   |
| 975     | 22        | 0.25%   |
| 3466    | 21        | 0.24%   |
| 333     | 20        | 0.23%   |
| 4266    | 16        | 0.18%   |
| 3666    | 14        | 0.16%   |
| 1639    | 14        | 0.16%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Hewlett-Packard          | 235       | 35.34%  |
| Brother Industries       | 140       | 21.05%  |
| Canon                    | 109       | 16.39%  |
| Samsung Electronics      | 60        | 9.02%   |
| Seiko Epson              | 53        | 7.97%   |
| QinHeng Electronics      | 9         | 1.35%   |
| Prolific Technology      | 8         | 1.2%    |
| Kyocera                  | 8         | 1.2%    |
| Dymo-CoStar              | 6         | 0.9%    |
| Pantum                   | 5         | 0.75%   |
| Xerox                    | 4         | 0.6%    |
| Ricoh                    | 4         | 0.6%    |
| Lexmark International    | 4         | 0.6%    |
| Panasonic (Matsushita)   | 3         | 0.45%   |
| Oki Data                 | 3         | 0.45%   |
| Dell                     | 3         | 0.45%   |
| Seiko Instruments        | 2         | 0.3%    |
| Zebra                    | 1         | 0.15%   |
| STMicroelectronics       | 1         | 0.15%   |
| Sato                     | 1         | 0.15%   |
| NXP Semiconductors       | 1         | 0.15%   |
| Magic Control Technology | 1         | 0.15%   |
| Fuji Xerox               | 1         | 0.15%   |
| BIXOLON                  | 1         | 0.15%   |
| Agere Systems (Lucent)   | 1         | 0.15%   |
| Unknown                  | 1         | 0.15%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung M2020 Series                                  | 11        | 1.64%   |
| HP LaserJet 1020                                      | 11        | 1.64%   |
| Samsung M2070 Series                                  | 9         | 1.34%   |
| QinHeng CH340S                                        | 9         | 1.34%   |
| Prolific PL2305 Parallel Port                         | 8         | 1.19%   |
| HP LaserJet 1018                                      | 8         | 1.19%   |
| HP DeskJet 2700 series                                | 8         | 1.19%   |
| Seiko Epson ET-2710 Series                            | 7         | 1.04%   |
| HP DeskJet 2600 series                                | 7         | 1.04%   |
| Canon LiDE 400                                        | 7         | 1.04%   |
| Brother Printer                                       | 7         | 1.04%   |
| HP LaserJet Professional P1102w                       | 6         | 0.89%   |
| HP DeskJet 3630 series                                | 6         | 0.89%   |
| HP Deskjet 2050 J510                                  | 6         | 0.89%   |
| Canon PIXMA MG2500 Series                             | 6         | 0.89%   |
| Samsung SCX-3400 Series                               | 5         | 0.75%   |
| HP OfficeJet 5200 series                              | 5         | 0.75%   |
| HP Officejet 4620 series                              | 5         | 0.75%   |
| HP Officejet 4500 G510n-z                             | 5         | 0.75%   |
| HP LaserJet Professional P 1102w                      | 5         | 0.75%   |
| HP LaserJet P1005                                     | 5         | 0.75%   |
| HP ENVY 5000 series                                   | 5         | 0.75%   |
| HP ENVY 4520 series                                   | 5         | 0.75%   |
| HP Deskjet 2540 series                                | 5         | 0.75%   |
| HP DeskJet 2130 series                                | 5         | 0.75%   |
| Brother HL-L2360D series                              | 5         | 0.75%   |
| Brother HL-1210W series                               | 5         | 0.75%   |
| Seiko Epson L210 Series                               | 4         | 0.6%    |
| Samsung M267x 287x Series                             | 4         | 0.6%    |
| Samsung C48x Series Color Laser Multifunction Printer | 4         | 0.6%    |
| HP OfficeJet 3830 series                              | 4         | 0.6%    |
| HP LaserJet P1102                                     | 4         | 0.6%    |
| HP Ink Tank Wireless 410 series                       | 4         | 0.6%    |
| HP DeskJet F4200 series                               | 4         | 0.6%    |
| HP Deskjet 1000 J110 series                           | 4         | 0.6%    |
| Canon PIXMA MX920 Series                              | 4         | 0.6%    |
| Canon CanoScan LiDE 300                               | 4         | 0.6%    |
| Brother MFC-J497DW                                    | 4         | 0.6%    |
| Brother HL-L2340D series                              | 4         | 0.6%    |
| Brother HL-2270DW Laser Printer                       | 4         | 0.6%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Canon                       | 102       | 61.08%  |
| Seiko Epson                 | 30        | 17.96%  |
| Hewlett-Packard             | 18        | 10.78%  |
| Mustek Systems              | 6         | 3.59%   |
| AGFA-Gevaert NV             | 3         | 1.8%    |
| Ultima Electronics          | 2         | 1.2%    |
| Acer Peripherals (now BenQ) | 2         | 1.2%    |
| UMAX                        | 1         | 0.6%    |
| Salix Technology            | 1         | 0.6%    |
| Microtek International      | 1         | 0.6%    |
| Canon Electronics           | 1         | 0.6%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                                               | 15        | 8.93%   |
| Canon CanoScan LIDE 25                                                                | 11        | 6.55%   |
| Canon CanoScan LiDE 120                                                               | 11        | 6.55%   |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 9         | 5.36%   |
| Canon CanoScan LiDE 220                                                               | 9         | 5.36%   |
| Canon CanoScan LiDE 210                                                               | 7         | 4.17%   |
| Canon CanoScan LiDE 700F                                                              | 6         | 3.57%   |
| Canon CanoScan LiDE 60                                                                | 5         | 2.98%   |
| Canon CanoScan LiDE 100                                                               | 5         | 2.98%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]                                           | 4         | 2.38%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                   | 4         | 2.38%   |
| Mustek Systems ScanExpress 1200 UB                                                    | 4         | 2.38%   |
| Canon CanoScan LiDE 200                                                               | 4         | 2.38%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 3         | 1.79%   |
| HP ScanJet 2400c                                                                      | 3         | 1.79%   |
| HP ScanJet 2200c                                                                      | 3         | 1.79%   |
| Canon CanoScan N650U/N656U                                                            | 3         | 1.79%   |
| Canon CanoScan LiDE 90                                                                | 3         | 1.79%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 2         | 1.19%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 2         | 1.19%   |
| Seiko Epson GT-6600U [Perfection 610]                                                 | 2         | 1.19%   |
| Seiko Epson ES-D200 [GT-S50]                                                          | 2         | 1.19%   |
| Mustek Systems SNAPSCAN e22                                                           | 2         | 1.19%   |
| HP ScanJet 3800c                                                                      | 2         | 1.19%   |
| HP Scanjet 300                                                                        | 2         | 1.19%   |
| Canon CanoScan N1240U/LiDE 30                                                         | 2         | 1.19%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                                                | 2         | 1.19%   |
| Canon CanoScan 9000F Mark II                                                          | 2         | 1.19%   |
| AGFA-Gevaert NV SnapScan 1212U (?)                                                    | 2         | 1.19%   |
| Acer Peripherals (now BenQ) S2W 3300U/4300U                                           | 2         | 1.19%   |
| UMAX Astra 4400/4450                                                                  | 1         | 0.6%    |
| Seiko Epson Stylus Photo RX500/510                                                    | 1         | 0.6%    |
| Seiko Epson GT-X900 [Perfection V700/V750 Photo]                                      | 1         | 0.6%    |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]                                           | 1         | 0.6%    |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 1         | 0.6%    |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 1         | 0.6%    |
| Seiko Epson GT-F600 [Perfection 4180]                                                 | 1         | 0.6%    |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                                         | 1         | 0.6%    |
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO]                         | 1         | 0.6%    |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                                    | 1         | 0.6%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 2306      | 22.05%  |
| Microdia                               | 825       | 7.89%   |
| IMC Networks                           | 786       | 7.51%   |
| Realtek Semiconductor                  | 712       | 6.81%   |
| Logitech                               | 587       | 5.61%   |
| Sunplus Innovation Technology          | 570       | 5.45%   |
| Bison Electronics                      | 560       | 5.35%   |
| Quanta                                 | 484       | 4.63%   |
| Cheng Uei Precision Industry (Foxlink) | 454       | 4.34%   |
| Suyin                                  | 416       | 3.98%   |
| Apple                                  | 280       | 2.68%   |
| Syntek                                 | 250       | 2.39%   |
| Silicon Motion                         | 220       | 2.1%    |
| Lite-On Technology                     | 180       | 1.72%   |
| Alcor Micro                            | 174       | 1.66%   |
| Acer                                   | 137       | 1.31%   |
| Samsung Electronics                    | 130       | 1.24%   |
| Luxvisions Innotech Limited            | 120       | 1.15%   |
| Microsoft                              | 116       | 1.11%   |
| Z-Star Microelectronics                | 104       | 0.99%   |
| Ricoh                                  | 102       | 0.98%   |
| Generalplus Technology                 | 56        | 0.54%   |
| Lenovo                                 | 55        | 0.53%   |
| Importek                               | 49        | 0.47%   |
| ALi                                    | 45        | 0.43%   |
| Sonix Technology                       | 43        | 0.41%   |
| Primax Electronics                     | 38        | 0.36%   |
| icSpring                               | 35        | 0.33%   |
| GEMBIRD                                | 35        | 0.33%   |
| Creative Technology                    | 32        | 0.31%   |
| KYE Systems (Mouse Systems)            | 30        | 0.29%   |
| ARC International                      | 27        | 0.26%   |
| SunplusIT                              | 26        | 0.25%   |
| OmniVision Technologies                | 24        | 0.23%   |
| Y Media                                | 21        | 0.2%    |
| DigiTech                               | 20        | 0.19%   |
| Aveo Technology                        | 20        | 0.19%   |
| Jieli Technology                       | 19        | 0.18%   |
| Sunplus Technology                     | 18        | 0.17%   |
| MacroSilicon                           | 18        | 0.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 337       | 3.21%   |
| Chicony HD WebCam                                | 225       | 2.14%   |
| Microdia Integrated_Webcam_HD                    | 212       | 2.02%   |
| IMC Networks USB2.0 HD UVC WebCam                | 176       | 1.68%   |
| Realtek Integrated_Webcam_HD                     | 166       | 1.58%   |
| Sunplus Integrated_Webcam_HD                     | 148       | 1.41%   |
| IMC Networks Integrated Camera                   | 148       | 1.41%   |
| Bison Integrated Camera                          | 144       | 1.37%   |
| Logitech Webcam C270                             | 136       | 1.29%   |
| Samsung Galaxy series, misc. (MTP mode)          | 127       | 1.21%   |
| Syntek Integrated Camera                         | 96        | 0.91%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 95        | 0.9%    |
| Apple Built-in iSight                            | 90        | 0.86%   |
| Chicony HP Truevision HD                         | 87        | 0.83%   |
| Logitech HD Pro Webcam C920                      | 85        | 0.81%   |
| Microdia Integrated Webcam                       | 82        | 0.78%   |
| Chicony USB2.0 HD UVC WebCam                     | 81        | 0.77%   |
| Chicony HP HD Camera                             | 80        | 0.76%   |
| Sunplus HD WebCam                                | 79        | 0.75%   |
| Chicony EasyCamera                               | 77        | 0.73%   |
| Chicony HP TrueVision HD Camera                  | 76        | 0.72%   |
| Chicony USB 2.0 Camera                           | 74        | 0.7%    |
| Quanta HD User Facing                            | 71        | 0.68%   |
| Chicony HP Webcam                                | 71        | 0.68%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 68        | 0.65%   |
| Quanta HP TrueVision HD Camera                   | 67        | 0.64%   |
| Chicony HD User Facing                           | 66        | 0.63%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                  | 66        | 0.63%   |
| Realtek USB Camera                               | 64        | 0.61%   |
| Lite-On Integrated Camera                        | 64        | 0.61%   |
| Chicony USB2.0 VGA UVC WebCam                    | 64        | 0.61%   |
| Microdia Webcam Vitade AF                        | 63        | 0.6%    |
| Chicony Lenovo EasyCamera                        | 62        | 0.59%   |
| Chicony TOSHIBA Web Camera - HD                  | 61        | 0.58%   |
| Chicony VGA Webcam                               | 60        | 0.57%   |
| Syntek Lenovo EasyCamera                         | 58        | 0.55%   |
| Apple FaceTime HD Camera                         | 58        | 0.55%   |
| Alcor Micro USB 2.0 PC cam                       | 55        | 0.52%   |
| Quanta VGA WebCam                                | 54        | 0.51%   |
| Apple FaceTime HD Camera (Built-in)              | 54        | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 605       | 39.57%  |
| Synaptics                          | 288       | 18.84%  |
| Shenzhen Goodix Technology         | 151       | 9.88%   |
| AuthenTec                          | 145       | 9.48%   |
| Upek                               | 116       | 7.59%   |
| Elan Microelectronics              | 96        | 6.28%   |
| LighTuning Technology              | 71        | 4.64%   |
| STMicroelectronics                 | 27        | 1.77%   |
| Focal-systems.Corp                 | 9         | 0.59%   |
| Samsung Electronics                | 5         | 0.33%   |
| HOLTEK                             | 5         | 0.33%   |
| Realtek USB2.0 Finger Print Bridge | 4         | 0.26%   |
| Next Biometrics                    | 2         | 0.13%   |
| Suprema                            | 1         | 0.07%   |
| Microsoft                          | 1         | 0.07%   |
| GDMicroelectronics                 | 1         | 0.07%   |
| Futronic Technology                | 1         | 0.07%   |
| Dell                               | 1         | 0.07%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 132       | 8.63%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 112       | 7.33%   |
| Shenzhen Goodix  Fingerprint Device                                        | 85        | 5.56%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 68        | 4.45%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 67        | 4.38%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 57        | 3.73%   |
| Shenzhen Goodix Fingerprint Reader                                         | 52        | 3.4%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 51        | 3.34%   |
| Validity Sensors Fingerprint scanner                                       | 44        | 2.88%   |
| AuthenTec AES2810                                                          | 44        | 2.88%   |
| Elan ELAN:ARM-M4                                                           | 43        | 2.81%   |
| Validity Sensors Synaptics WBDI                                            | 42        | 2.75%   |
| Validity Sensors VFS491                                                    | 41        | 2.68%   |
| Elan ELAN:Fingerprint                                                      | 35        | 2.29%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 34        | 2.22%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 33        | 2.16%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 32        | 2.09%   |
| Synaptics  WBDI                                                            | 29        | 1.9%    |
| AuthenTec AES1600                                                          | 29        | 1.9%    |
| Synaptics WBDI                                                             | 27        | 1.77%   |
| STMicroelectronics Fingerprint Reader                                      | 27        | 1.77%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 26        | 1.7%    |
| Synaptics UWP WBDI                                                         | 26        | 1.7%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 25        | 1.64%   |
| AuthenTec Fingerprint Sensor                                               | 24        | 1.57%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 23        | 1.5%    |
| Validity Sensors VFS101 Fingerprint Reader                                 | 23        | 1.5%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 21        | 1.37%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 21        | 1.37%   |
| Synaptics Fingerprint reader [HP G6]                                       | 21        | 1.37%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 20        | 1.31%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 19        | 1.24%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 17        | 1.11%   |
| LighTuning Fingerprint Reader                                              | 17        | 1.11%   |
| Shenzhen Goodix FingerPrint                                                | 14        | 0.92%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 13        | 0.85%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 12        | 0.78%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 11        | 0.72%   |
| Validity Sensors VFS Fingerprint sensor                                    | 10        | 0.65%   |
| Synaptics UWP WBDI Device                                                  | 9         | 0.59%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 329       | 45.44%  |
| Alcor Micro                       | 168       | 23.2%   |
| O2 Micro                          | 69        | 9.53%   |
| Upek                              | 50        | 6.91%   |
| Lenovo                            | 42        | 5.8%    |
| Gemalto (was Gemplus)             | 12        | 1.66%   |
| SCM Microsystems                  | 11        | 1.52%   |
| OmniKey                           | 10        | 1.38%   |
| Realtek Semiconductor             | 6         | 0.83%   |
| Reiner SCT Kartensysteme          | 3         | 0.41%   |
| Cherry                            | 3         | 0.41%   |
| In Focus Systems                  | 2         | 0.28%   |
| Giesecke & Devrient               | 2         | 0.28%   |
| Chicony Electronics               | 2         | 0.28%   |
| Bit4id                            | 2         | 0.28%   |
| Aladdin Knowledge Systems         | 2         | 0.28%   |
| Advanced Card Systems             | 2         | 0.28%   |
| VASCO Data Security International | 1         | 0.14%   |
| Precise Biometrics                | 1         | 0.14%   |
| NXP Semiconductors                | 1         | 0.14%   |
| Hewlett-Packard                   | 1         | 0.14%   |
| Fujitsu Siemens Computers         | 1         | 0.14%   |
| Clay Logic                        | 1         | 0.14%   |
| C3PO                              | 1         | 0.14%   |
| Aladdin R.D.                      | 1         | 0.14%   |
| Aktiv                             | 1         | 0.14%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 158       | 21.82%  |
| Broadcom BCM5880 Secure Applications Processor                               | 151       | 20.86%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 70        | 9.67%   |
| Broadcom 5880                                                                | 62        | 8.56%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 56        | 7.73%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 50        | 6.91%   |
| Lenovo Integrated Smart Card Reader                                          | 42        | 5.8%    |
| Broadcom 58200                                                               | 42        | 5.8%    |
| O2 Micro Oz776 SmartCard Reader                                              | 13        | 1.8%    |
| Alcor Micro Watchdata W 1981                                                 | 9         | 1.24%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 7         | 0.97%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 6         | 0.83%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 6         | 0.83%   |
| OmniKey CardMan 3021 / 3121                                                  | 5         | 0.69%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 5         | 0.69%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 4         | 0.55%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 2         | 0.28%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 0.28%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 2         | 0.28%   |
| OmniKey CardMan 1021                                                         | 2         | 0.28%   |
| In Focus Systems EMV Smartcard Reader                                        | 2         | 0.28%   |
| Giesecke & Devrient StarSign CUT                                             | 2         | 0.28%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 2         | 0.28%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 2         | 0.28%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.28%   |
| Advanced Card Systems ACR122U                                                | 2         | 0.28%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.14%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 0.14%   |
| Reiner SCT Kartensysteme tanJack USB                                         | 1         | 0.14%   |
| Precise Biometrics 200 MC FingerPrint and SmartCard Reader                   | 1         | 0.14%   |
| OmniKey CardMan 4321                                                         | 1         | 0.14%   |
| OmniKey CardMan 3121 (HID Technologies)                                      | 1         | 0.14%   |
| OmniKey 5422 Smartcard Reader                                                | 1         | 0.14%   |
| NXP Semiconductors PR533                                                     | 1         | 0.14%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.14%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.14%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.14%   |
| Cherry SmartTerminal XX44                                                    | 1         | 0.14%   |
| C3PO USB SMART CARD READER                                                   | 1         | 0.14%   |
| Bit4id miniLector-s                                                          | 1         | 0.14%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 12575     | 69.59%  |
| 1     | 4305      | 23.82%  |
| 2     | 947       | 5.24%   |
| 3     | 167       | 0.92%   |
| 4     | 47        | 0.26%   |
| 5     | 16        | 0.09%   |
| 6     | 9         | 0.05%   |
| 7     | 3         | 0.02%   |
| 8     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 1734      | 25.9%   |
| Fingerprint reader       | 1509      | 22.54%  |
| Net/wireless             | 1064      | 15.89%  |
| Chipcard                 | 676       | 10.1%   |
| Multimedia controller    | 402       | 6.01%   |
| Communication controller | 279       | 4.17%   |
| Bluetooth                | 216       | 3.23%   |
| Camera                   | 154       | 2.3%    |
| Sound                    | 126       | 1.88%   |
| Storage                  | 117       | 1.75%   |
| Unassigned class         | 80        | 1.2%    |
| Card reader              | 59        | 0.88%   |
| Net/ethernet             | 58        | 0.87%   |
| Network                  | 54        | 0.81%   |
| Modem                    | 53        | 0.79%   |
| Storage/ide              | 28        | 0.42%   |
| Flash memory             | 27        | 0.4%    |
| Storage/raid             | 24        | 0.36%   |
| Dvb card                 | 12        | 0.18%   |
| Firewire controller      | 7         | 0.1%    |
| Unclassified device      | 4         | 0.06%   |
| Tv card                  | 4         | 0.06%   |
| Storage/nvme             | 3         | 0.04%   |
| Wireless                 | 2         | 0.03%   |
| Storage/ata              | 2         | 0.03%   |

