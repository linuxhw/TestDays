Linux in Canada - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Canada.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Canada/Desktop/README.md) and [notebooks](/Location/Canada/Notebook/README.md).

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

Total: 7857

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | Pavilion dv6                | Notebook    | [c937edbfcd](https://linux-hardware.org/?probe=c937edbfcd) | Mar 01, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [ecfa5f6c27](https://linux-hardware.org/?probe=ecfa5f6c27) | Mar 01, 2023 |
| Gigabyte      | GA-880GA-UD3H               | Desktop     | [483db5a7bd](https://linux-hardware.org/?probe=483db5a7bd) | Feb 28, 2023 |
| MSI           | MPG Z390M GAMING EDGE AC    | Desktop     | [d0813971b9](https://linux-hardware.org/?probe=d0813971b9) | Feb 28, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | Notebook    | [d8b58a8ea1](https://linux-hardware.org/?probe=d8b58a8ea1) | Feb 28, 2023 |
| ASRockRack    | E3C246D4U2-2T               | Desktop     | [1ad2cb5102](https://linux-hardware.org/?probe=1ad2cb5102) | Feb 28, 2023 |
| Alienware     | x15 R2                      | Notebook    | [f0335542ce](https://linux-hardware.org/?probe=f0335542ce) | Feb 28, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [6ccb40f64d](https://linux-hardware.org/?probe=6ccb40f64d) | Feb 28, 2023 |
| Lenovo        | SKYBAY SDK0J40697 WIN 33... | Desktop     | [75e0fb99ed](https://linux-hardware.org/?probe=75e0fb99ed) | Feb 28, 2023 |
| ASRock        | Z790 PG Lightning           | Desktop     | [86c7144757](https://linux-hardware.org/?probe=86c7144757) | Feb 27, 2023 |
| HP            | 18E4                        | Desktop     | [cab6d807e9](https://linux-hardware.org/?probe=cab6d807e9) | Feb 27, 2023 |
| Unknown       | HX90                        | Desktop     | [bc8bed9135](https://linux-hardware.org/?probe=bc8bed9135) | Feb 27, 2023 |
| Toshiba       | Satellite P870              | Notebook    | [6d9216b866](https://linux-hardware.org/?probe=6d9216b866) | Feb 27, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [7f907fadb7](https://linux-hardware.org/?probe=7f907fadb7) | Feb 27, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [766991da5e](https://linux-hardware.org/?probe=766991da5e) | Feb 27, 2023 |
| ASUSTek       | B150 PRO GAMING/AURA        | Desktop     | [618e3d30fc](https://linux-hardware.org/?probe=618e3d30fc) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [091e4e3188](https://linux-hardware.org/?probe=091e4e3188) | Feb 27, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [a9a8184201](https://linux-hardware.org/?probe=a9a8184201) | Feb 27, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [07f46e8e62](https://linux-hardware.org/?probe=07f46e8e62) | Feb 27, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [8de57c03d5](https://linux-hardware.org/?probe=8de57c03d5) | Feb 27, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [a3b8430bad](https://linux-hardware.org/?probe=a3b8430bad) | Feb 26, 2023 |
| HP            | 18E4                        | Desktop     | [5c7c3413c9](https://linux-hardware.org/?probe=5c7c3413c9) | Feb 26, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [28bb1541b4](https://linux-hardware.org/?probe=28bb1541b4) | Feb 26, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [8906540d72](https://linux-hardware.org/?probe=8906540d72) | Feb 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [97b08529eb](https://linux-hardware.org/?probe=97b08529eb) | Feb 26, 2023 |
| Sapphire      | PE-AM2RS690V2               | Desktop     | [8aa6cda98e](https://linux-hardware.org/?probe=8aa6cda98e) | Feb 26, 2023 |
| Dell          | 0G3HR7 A00                  | Desktop     | [33723c8b80](https://linux-hardware.org/?probe=33723c8b80) | Feb 25, 2023 |
| Lenovo        | ThinkPad T460 20FMS35H02    | Notebook    | [a396e54378](https://linux-hardware.org/?probe=a396e54378) | Feb 25, 2023 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [c863d76de9](https://linux-hardware.org/?probe=c863d76de9) | Feb 25, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [fbb2478f8c](https://linux-hardware.org/?probe=fbb2478f8c) | Feb 25, 2023 |
| HP            | G60                         | Notebook    | [6e4b159708](https://linux-hardware.org/?probe=6e4b159708) | Feb 25, 2023 |
| Protectli     | VP2420                      | Desktop     | [ea5f851cf3](https://linux-hardware.org/?probe=ea5f851cf3) | Feb 25, 2023 |
| MSI           | PRO Z790-P WIFI DDR4        | Desktop     | [59b7e1da6d](https://linux-hardware.org/?probe=59b7e1da6d) | Feb 25, 2023 |
| Dell          | 0XCR8D A02                  | Desktop     | [6053547fd3](https://linux-hardware.org/?probe=6053547fd3) | Feb 25, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [fb42cba088](https://linux-hardware.org/?probe=fb42cba088) | Feb 25, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [79bb0eb4c9](https://linux-hardware.org/?probe=79bb0eb4c9) | Feb 25, 2023 |
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [3575d2e78d](https://linux-hardware.org/?probe=3575d2e78d) | Feb 25, 2023 |
| Intel         | JSL MRD                     | Desktop     | [84a33f3c84](https://linux-hardware.org/?probe=84a33f3c84) | Feb 24, 2023 |
| Google        | Kefka                       | Notebook    | [8142fbc91a](https://linux-hardware.org/?probe=8142fbc91a) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [297c37ec04](https://linux-hardware.org/?probe=297c37ec04) | Feb 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [5070b384cc](https://linux-hardware.org/?probe=5070b384cc) | Feb 24, 2023 |
| Dell          | 0GDJXY A00                  | All in one  | [ea8027e95b](https://linux-hardware.org/?probe=ea8027e95b) | Feb 24, 2023 |
| Dell          | 0GDJXY A00                  | All in one  | [6db3a90234](https://linux-hardware.org/?probe=6db3a90234) | Feb 24, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [59ec61666a](https://linux-hardware.org/?probe=59ec61666a) | Feb 24, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [e162d5848c](https://linux-hardware.org/?probe=e162d5848c) | Feb 24, 2023 |
| AZW           | U59                         | Desktop     | [b574c32b53](https://linux-hardware.org/?probe=b574c32b53) | Feb 24, 2023 |
| Gateway       | SX2185                      | Desktop     | [32ab171e53](https://linux-hardware.org/?probe=32ab171e53) | Feb 23, 2023 |
| ASUSTek       | P5K                         | Desktop     | [2fb7f1713b](https://linux-hardware.org/?probe=2fb7f1713b) | Feb 23, 2023 |
| MSI           | MPG Z790 CARBON WIFI        | Desktop     | [e0687d11bb](https://linux-hardware.org/?probe=e0687d11bb) | Feb 23, 2023 |
| MSI           | MPG Z790 CARBON WIFI        | Desktop     | [49e71eb5b4](https://linux-hardware.org/?probe=49e71eb5b4) | Feb 22, 2023 |
| Dell          | Inspiron 5566               | Notebook    | [0233d7525d](https://linux-hardware.org/?probe=0233d7525d) | Feb 22, 2023 |
| Dell          | Latitude E6520              | Notebook    | [4a9371ec87](https://linux-hardware.org/?probe=4a9371ec87) | Feb 22, 2023 |
| Acer          | Aspire X3470                | Desktop     | [659a1f31bd](https://linux-hardware.org/?probe=659a1f31bd) | Feb 22, 2023 |
| AWOW          | NY PC BOX                   | Mini pc     | [3e9e7c877c](https://linux-hardware.org/?probe=3e9e7c877c) | Feb 22, 2023 |
| CWWK          | CW-J6-6L                    | Desktop     | [7599e919d9](https://linux-hardware.org/?probe=7599e919d9) | Feb 22, 2023 |
| CWWK          | CW-J6-6L                    | Desktop     | [d003c3ed81](https://linux-hardware.org/?probe=d003c3ed81) | Feb 22, 2023 |
| Acer          | Aspire TC-605               | Desktop     | [7234bd12f6](https://linux-hardware.org/?probe=7234bd12f6) | Feb 22, 2023 |
| Intel         | NUC7JYB J67969-405          | Mini pc     | [a28282663a](https://linux-hardware.org/?probe=a28282663a) | Feb 22, 2023 |
| Dell          | 0PM2CW A05                  | Server      | [13c1bd9dcd](https://linux-hardware.org/?probe=13c1bd9dcd) | Feb 22, 2023 |
| Intel         | NUC7JYB J67969-405          | Mini pc     | [524153d219](https://linux-hardware.org/?probe=524153d219) | Feb 22, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [ade0244936](https://linux-hardware.org/?probe=ade0244936) | Feb 21, 2023 |
| Dell          | Inspiron 5493               | Notebook    | [ad7bee8a6e](https://linux-hardware.org/?probe=ad7bee8a6e) | Feb 20, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [04130aaf41](https://linux-hardware.org/?probe=04130aaf41) | Feb 20, 2023 |
| Dell          | Latitude E5440              | Notebook    | [10b94a411c](https://linux-hardware.org/?probe=10b94a411c) | Feb 20, 2023 |
| ASUSTek       | ROG STRIX B760-I GAMING ... | Desktop     | [40ae7724b9](https://linux-hardware.org/?probe=40ae7724b9) | Feb 20, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [08d8865fcf](https://linux-hardware.org/?probe=08d8865fcf) | Feb 20, 2023 |
| Dell          | 0D24M8 A01                  | Desktop     | [924264cbec](https://linux-hardware.org/?probe=924264cbec) | Feb 20, 2023 |
| AZW           | GK mini                     | Desktop     | [6fc9af1346](https://linux-hardware.org/?probe=6fc9af1346) | Feb 20, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [d346153872](https://linux-hardware.org/?probe=d346153872) | Feb 20, 2023 |
| Lenovo        | ThinkCentre M58 8910B4U     | Desktop     | [03c8e6d135](https://linux-hardware.org/?probe=03c8e6d135) | Feb 19, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [f55697d9b3](https://linux-hardware.org/?probe=f55697d9b3) | Feb 19, 2023 |
| Dell          | Precision M4500             | Notebook    | [b0d8bf3c56](https://linux-hardware.org/?probe=b0d8bf3c56) | Feb 19, 2023 |
| Panasonic     | CF-S10CDHEDM                | Notebook    | [7228f7a915](https://linux-hardware.org/?probe=7228f7a915) | Feb 19, 2023 |
| Lenovo        | IdeaPad Yoga 11S 20246      | Notebook    | [b0941b8ef0](https://linux-hardware.org/?probe=b0941b8ef0) | Feb 18, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [58ca93166c](https://linux-hardware.org/?probe=58ca93166c) | Feb 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [9978dc62b3](https://linux-hardware.org/?probe=9978dc62b3) | Feb 18, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [6b7a3b68f3](https://linux-hardware.org/?probe=6b7a3b68f3) | Feb 18, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [51cf60bd9b](https://linux-hardware.org/?probe=51cf60bd9b) | Feb 18, 2023 |
| Intel         | X79                         | Desktop     | [28c9b2590c](https://linux-hardware.org/?probe=28c9b2590c) | Feb 18, 2023 |
| Intel         | X79                         | Desktop     | [89c51847f9](https://linux-hardware.org/?probe=89c51847f9) | Feb 18, 2023 |
| MSI           | Raider GE76 12UGS           | Notebook    | [041cf0d3d8](https://linux-hardware.org/?probe=041cf0d3d8) | Feb 18, 2023 |
| MSI           | Raider GE76 12UGS           | Notebook    | [20dc6d6c5c](https://linux-hardware.org/?probe=20dc6d6c5c) | Feb 18, 2023 |
| HP            | Pavilion 13 x360 PC         | Notebook    | [af3167a0d4](https://linux-hardware.org/?probe=af3167a0d4) | Feb 18, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [2a2dfe19fc](https://linux-hardware.org/?probe=2a2dfe19fc) | Feb 18, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [feae434e9e](https://linux-hardware.org/?probe=feae434e9e) | Feb 18, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [9ab628bcf2](https://linux-hardware.org/?probe=9ab628bcf2) | Feb 18, 2023 |
| Dell          | Inspiron 5575               | Notebook    | [aaa83a4af0](https://linux-hardware.org/?probe=aaa83a4af0) | Feb 18, 2023 |
| Dell          | Inspiron 5575               | Notebook    | [18b6274238](https://linux-hardware.org/?probe=18b6274238) | Feb 18, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [33d9c73cb9](https://linux-hardware.org/?probe=33d9c73cb9) | Feb 17, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [7ef47e7131](https://linux-hardware.org/?probe=7ef47e7131) | Feb 17, 2023 |
| Google        | Coral                       | Notebook    | [7a9869ff50](https://linux-hardware.org/?probe=7a9869ff50) | Feb 17, 2023 |
| ASUSTek       | X450LD                      | Notebook    | [b4fb1ddc5a](https://linux-hardware.org/?probe=b4fb1ddc5a) | Feb 17, 2023 |
| ASRock        | B360M Xtreme                | Desktop     | [0804d226b0](https://linux-hardware.org/?probe=0804d226b0) | Feb 17, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [c913edda07](https://linux-hardware.org/?probe=c913edda07) | Feb 17, 2023 |
| HP            | 1825                        | Desktop     | [858ebd3baf](https://linux-hardware.org/?probe=858ebd3baf) | Feb 17, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [4101f152f5](https://linux-hardware.org/?probe=4101f152f5) | Feb 17, 2023 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [395a5da0fb](https://linux-hardware.org/?probe=395a5da0fb) | Feb 17, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [92901492fc](https://linux-hardware.org/?probe=92901492fc) | Feb 16, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [361eb28148](https://linux-hardware.org/?probe=361eb28148) | Feb 16, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [0e694f49fe](https://linux-hardware.org/?probe=0e694f49fe) | Feb 16, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [5398361b68](https://linux-hardware.org/?probe=5398361b68) | Feb 16, 2023 |
| BESSTAR Te... | DMAF5 V1.0                  | Desktop     | [af47a30d6a](https://linux-hardware.org/?probe=af47a30d6a) | Feb 15, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [987c9b1854](https://linux-hardware.org/?probe=987c9b1854) | Feb 15, 2023 |
| Dell          | Precision 7710              | Notebook    | [3db09e931e](https://linux-hardware.org/?probe=3db09e931e) | Feb 15, 2023 |
| Dell          | Precision 7710              | Notebook    | [ed02038c00](https://linux-hardware.org/?probe=ed02038c00) | Feb 15, 2023 |
| IBM           | 811328U                     | Desktop     | [dc9536a0f2](https://linux-hardware.org/?probe=dc9536a0f2) | Feb 14, 2023 |
| IBM           | 811328U                     | Desktop     | [6ad9b1f22a](https://linux-hardware.org/?probe=6ad9b1f22a) | Feb 14, 2023 |
| Pegatron      | Narra6                      | Desktop     | [13f0acba4c](https://linux-hardware.org/?probe=13f0acba4c) | Feb 14, 2023 |
| ASRock        | X370 Gaming X               | Desktop     | [2b9a026876](https://linux-hardware.org/?probe=2b9a026876) | Feb 14, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [4262fa293e](https://linux-hardware.org/?probe=4262fa293e) | Feb 14, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [9de6fe5d90](https://linux-hardware.org/?probe=9de6fe5d90) | Feb 14, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [43d2279955](https://linux-hardware.org/?probe=43d2279955) | Feb 14, 2023 |
| ASUSTek       | ProArt Z490-CREATOR 10G     | Desktop     | [500a5cf614](https://linux-hardware.org/?probe=500a5cf614) | Feb 14, 2023 |
| HP            | 83EE                        | Desktop     | [f83f333b3c](https://linux-hardware.org/?probe=f83f333b3c) | Feb 14, 2023 |
| ASUSTek       | Zenbook UN5401QAB_UN5401... | Convertible | [256f660b72](https://linux-hardware.org/?probe=256f660b72) | Feb 13, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [68463d6d4b](https://linux-hardware.org/?probe=68463d6d4b) | Feb 13, 2023 |
| ASUSTek       | Rampage IV EXTREME          | Desktop     | [60ddb51b98](https://linux-hardware.org/?probe=60ddb51b98) | Feb 13, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [2d99eeaca6](https://linux-hardware.org/?probe=2d99eeaca6) | Feb 13, 2023 |
| Panasonic     | CF-C2CCEZXCM                | Notebook    | [c435502e6e](https://linux-hardware.org/?probe=c435502e6e) | Feb 13, 2023 |
| Lenovo        | ThinkPad T440s 20ARS1VL0... | Notebook    | [d4b5ca228c](https://linux-hardware.org/?probe=d4b5ca228c) | Feb 13, 2023 |
| HP            | Pavilion dv2500             | Notebook    | [bea8c0162f](https://linux-hardware.org/?probe=bea8c0162f) | Feb 12, 2023 |
| Panasonic     | CF-C2CCEZXCM                | Notebook    | [3a0ce0730a](https://linux-hardware.org/?probe=3a0ce0730a) | Feb 12, 2023 |
| Lenovo        | 4030                        | Desktop     | [a0052fd936](https://linux-hardware.org/?probe=a0052fd936) | Feb 12, 2023 |
| ASRock        | B650M PG Riptide            | Desktop     | [bf986cc448](https://linux-hardware.org/?probe=bf986cc448) | Feb 12, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [8133fc11b8](https://linux-hardware.org/?probe=8133fc11b8) | Feb 12, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [866ad6408c](https://linux-hardware.org/?probe=866ad6408c) | Feb 12, 2023 |
| Acer          | Aspire 8942G                | Notebook    | [d517f63625](https://linux-hardware.org/?probe=d517f63625) | Feb 12, 2023 |
| Valve         | Jupiter                     | Notebook    | [10084e1b16](https://linux-hardware.org/?probe=10084e1b16) | Feb 12, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [3e048e046a](https://linux-hardware.org/?probe=3e048e046a) | Feb 12, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [3982ec4e74](https://linux-hardware.org/?probe=3982ec4e74) | Feb 12, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [a034121d24](https://linux-hardware.org/?probe=a034121d24) | Feb 12, 2023 |
| Pegatron      | Narra6                      | Desktop     | [77bed4b6f3](https://linux-hardware.org/?probe=77bed4b6f3) | Feb 12, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [7092ef977d](https://linux-hardware.org/?probe=7092ef977d) | Feb 11, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [9a81107301](https://linux-hardware.org/?probe=9a81107301) | Feb 11, 2023 |
| HP            | Presario V6000 (RN927UA#... | Notebook    | [0524b3b524](https://linux-hardware.org/?probe=0524b3b524) | Feb 11, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [266a3eff3f](https://linux-hardware.org/?probe=266a3eff3f) | Feb 10, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [18b84d9ea2](https://linux-hardware.org/?probe=18b84d9ea2) | Feb 10, 2023 |
| Google        | Droid                       | Notebook    | [33dbb43623](https://linux-hardware.org/?probe=33dbb43623) | Feb 10, 2023 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [663cbf83ff](https://linux-hardware.org/?probe=663cbf83ff) | Feb 10, 2023 |
| HP            | Notebook                    | Notebook    | [17664bf689](https://linux-hardware.org/?probe=17664bf689) | Feb 10, 2023 |
| Supermicro    | C7Z370-CG-IW                | Server      | [5145e7d26e](https://linux-hardware.org/?probe=5145e7d26e) | Feb 10, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [0a74293474](https://linux-hardware.org/?probe=0a74293474) | Feb 10, 2023 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | Notebook    | [9b8563ab53](https://linux-hardware.org/?probe=9b8563ab53) | Feb 10, 2023 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [ed180eeb68](https://linux-hardware.org/?probe=ed180eeb68) | Feb 09, 2023 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [fff827c027](https://linux-hardware.org/?probe=fff827c027) | Feb 09, 2023 |
| Acer          | Aspire M3970                | Desktop     | [718cc13462](https://linux-hardware.org/?probe=718cc13462) | Feb 09, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [91de8b5956](https://linux-hardware.org/?probe=91de8b5956) | Feb 09, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [d236f5fa51](https://linux-hardware.org/?probe=d236f5fa51) | Feb 09, 2023 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [aaa509fed7](https://linux-hardware.org/?probe=aaa509fed7) | Feb 09, 2023 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [148b3b0adc](https://linux-hardware.org/?probe=148b3b0adc) | Feb 09, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [7ad97f8b6d](https://linux-hardware.org/?probe=7ad97f8b6d) | Feb 09, 2023 |
| ASUSTek       | P8Z68-V PRO                 | Desktop     | [7b17cbd936](https://linux-hardware.org/?probe=7b17cbd936) | Feb 08, 2023 |
| HP            | Pavilion dv7                | Notebook    | [6b7ba3365e](https://linux-hardware.org/?probe=6b7ba3365e) | Feb 08, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [0593b2bac6](https://linux-hardware.org/?probe=0593b2bac6) | Feb 08, 2023 |
| ASUSTek       | B150 PRO GAMING D3          | Desktop     | [8178f6bf56](https://linux-hardware.org/?probe=8178f6bf56) | Feb 08, 2023 |
| Lenovo        | Unknown                     | Notebook    | [67c2761551](https://linux-hardware.org/?probe=67c2761551) | Feb 07, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [feeed093c0](https://linux-hardware.org/?probe=feeed093c0) | Feb 07, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [ebe5940bd7](https://linux-hardware.org/?probe=ebe5940bd7) | Feb 07, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [a019143fe9](https://linux-hardware.org/?probe=a019143fe9) | Feb 07, 2023 |
| MSI           | GT72 6QE                    | Notebook    | [bd02e4c770](https://linux-hardware.org/?probe=bd02e4c770) | Feb 07, 2023 |
| MSI           | GT72 6QE                    | Notebook    | [43a7194d4b](https://linux-hardware.org/?probe=43a7194d4b) | Feb 07, 2023 |
| Acer          | Aspire TC-1760              | Desktop     | [b7fdb6cd73](https://linux-hardware.org/?probe=b7fdb6cd73) | Feb 06, 2023 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | Desktop     | [70f715ffb4](https://linux-hardware.org/?probe=70f715ffb4) | Feb 06, 2023 |
| Acer          | Okinawa                     | Notebook    | [eab799e6dc](https://linux-hardware.org/?probe=eab799e6dc) | Feb 06, 2023 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | Desktop     | [f7ca9a94c5](https://linux-hardware.org/?probe=f7ca9a94c5) | Feb 06, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [c73a4ad56a](https://linux-hardware.org/?probe=c73a4ad56a) | Feb 06, 2023 |
| Dell          | 0XNNCJ A03                  | Server      | [a0b1f2a7b4](https://linux-hardware.org/?probe=a0b1f2a7b4) | Feb 06, 2023 |
| AZW           | U59                         | Desktop     | [b97c4f6277](https://linux-hardware.org/?probe=b97c4f6277) | Feb 06, 2023 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [99a4bb9e50](https://linux-hardware.org/?probe=99a4bb9e50) | Feb 05, 2023 |
| Acer          | Aspire A315-21              | Notebook    | [b452c164d0](https://linux-hardware.org/?probe=b452c164d0) | Feb 05, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [2543adebba](https://linux-hardware.org/?probe=2543adebba) | Feb 05, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [c35fa9b7f5](https://linux-hardware.org/?probe=c35fa9b7f5) | Feb 05, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [f3f4d9fc40](https://linux-hardware.org/?probe=f3f4d9fc40) | Feb 04, 2023 |
| ASUSTek       | PRO H410M-C                 | Desktop     | [486f19af99](https://linux-hardware.org/?probe=486f19af99) | Feb 04, 2023 |
| HP            | G60                         | Notebook    | [518195af9f](https://linux-hardware.org/?probe=518195af9f) | Feb 04, 2023 |
| MSI           | 870-G45                     | Desktop     | [92b840c75e](https://linux-hardware.org/?probe=92b840c75e) | Feb 04, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [768696d7b8](https://linux-hardware.org/?probe=768696d7b8) | Feb 04, 2023 |
| Valve         | Jupiter                     | Notebook    | [d78de63927](https://linux-hardware.org/?probe=d78de63927) | Feb 04, 2023 |
| HP            | 0AACh                       | Desktop     | [86d994993f](https://linux-hardware.org/?probe=86d994993f) | Feb 03, 2023 |
| AZW           | SER                         | Mini pc     | [ce867dfcef](https://linux-hardware.org/?probe=ce867dfcef) | Feb 03, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [6bb0e68672](https://linux-hardware.org/?probe=6bb0e68672) | Feb 03, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [afadbdee59](https://linux-hardware.org/?probe=afadbdee59) | Feb 03, 2023 |
| Acer          | Aspire A517-51G             | Notebook    | [7555fafa98](https://linux-hardware.org/?probe=7555fafa98) | Feb 03, 2023 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [93630ab2ea](https://linux-hardware.org/?probe=93630ab2ea) | Feb 03, 2023 |
| Xunlong       | Orange Pi Zero              | Soc         | [3af57a322f](https://linux-hardware.org/?probe=3af57a322f) | Feb 03, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [c122070f4f](https://linux-hardware.org/?probe=c122070f4f) | Feb 03, 2023 |
| ASRock        | H510M-HVS                   | Desktop     | [c2bdc49f09](https://linux-hardware.org/?probe=c2bdc49f09) | Feb 03, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [830188ba1b](https://linux-hardware.org/?probe=830188ba1b) | Feb 03, 2023 |
| Dell          | Latitude 3400               | Notebook    | [c954aad23a](https://linux-hardware.org/?probe=c954aad23a) | Feb 02, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [43101dad89](https://linux-hardware.org/?probe=43101dad89) | Feb 02, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [f6ad918c7e](https://linux-hardware.org/?probe=f6ad918c7e) | Feb 02, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [78ea388883](https://linux-hardware.org/?probe=78ea388883) | Feb 02, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [ef1817a829](https://linux-hardware.org/?probe=ef1817a829) | Feb 02, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | Desktop     | [d2696b9042](https://linux-hardware.org/?probe=d2696b9042) | Feb 02, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [f2919f7135](https://linux-hardware.org/?probe=f2919f7135) | Feb 01, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [ab92a33bdf](https://linux-hardware.org/?probe=ab92a33bdf) | Feb 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | Notebook    | [8bc290ef67](https://linux-hardware.org/?probe=8bc290ef67) | Feb 01, 2023 |
| HP            | 0AACh                       | Desktop     | [f41abcf7f9](https://linux-hardware.org/?probe=f41abcf7f9) | Feb 01, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [95e019beb2](https://linux-hardware.org/?probe=95e019beb2) | Feb 01, 2023 |
| Dell          | Latitude 7490               | Notebook    | [b2c18d04be](https://linux-hardware.org/?probe=b2c18d04be) | Feb 01, 2023 |
| Dell          | Latitude 7490               | Notebook    | [050126f7f7](https://linux-hardware.org/?probe=050126f7f7) | Feb 01, 2023 |
| Dell          | 09KPNV A01                  | Desktop     | [5dcda0d3e5](https://linux-hardware.org/?probe=5dcda0d3e5) | Feb 01, 2023 |
| Dell          | 0GDJXY A00                  | All in one  | [1ce7db78c1](https://linux-hardware.org/?probe=1ce7db78c1) | Feb 01, 2023 |
| ASUSTek       | Z87-A                       | Desktop     | [1b880dbac2](https://linux-hardware.org/?probe=1b880dbac2) | Feb 01, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [602482d070](https://linux-hardware.org/?probe=602482d070) | Feb 01, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [ffe1cabad7](https://linux-hardware.org/?probe=ffe1cabad7) | Feb 01, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CH0... | Notebook    | [78eeec802b](https://linux-hardware.org/?probe=78eeec802b) | Feb 01, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [bea57d418a](https://linux-hardware.org/?probe=bea57d418a) | Feb 01, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [455825998f](https://linux-hardware.org/?probe=455825998f) | Feb 01, 2023 |
| HP            | Laptop 14-dq4xxx            | Notebook    | [c102edf6a0](https://linux-hardware.org/?probe=c102edf6a0) | Feb 01, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [4f8642280f](https://linux-hardware.org/?probe=4f8642280f) | Feb 01, 2023 |
| Dell          | 0PU052                      | Desktop     | [d2f241353d](https://linux-hardware.org/?probe=d2f241353d) | Feb 01, 2023 |
| Intel         | DG965OT AAD75595-200        | Desktop     | [8ab85c58be](https://linux-hardware.org/?probe=8ab85c58be) | Feb 01, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [23b27dab7d](https://linux-hardware.org/?probe=23b27dab7d) | Feb 01, 2023 |
| ASUSTek       | Zenbook UX8402ZA_UX8402Z... | Notebook    | [1d212c67b2](https://linux-hardware.org/?probe=1d212c67b2) | Jan 31, 2023 |
| Dell          | Inspiron 15-7579            | Notebook    | [b5bd231bf3](https://linux-hardware.org/?probe=b5bd231bf3) | Jan 31, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [21b6d00ff2](https://linux-hardware.org/?probe=21b6d00ff2) | Jan 31, 2023 |
| HP            | 0AACh                       | Desktop     | [32961ffb11](https://linux-hardware.org/?probe=32961ffb11) | Jan 31, 2023 |
| Acer          | Aspire AV14-51              | Notebook    | [fa801eea4b](https://linux-hardware.org/?probe=fa801eea4b) | Jan 31, 2023 |
| HP            | 0AACh                       | Desktop     | [94baf3c57c](https://linux-hardware.org/?probe=94baf3c57c) | Jan 31, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [d59770af38](https://linux-hardware.org/?probe=d59770af38) | Jan 31, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [3a5ae3d1e8](https://linux-hardware.org/?probe=3a5ae3d1e8) | Jan 31, 2023 |
| ASUSTek       | Zenbook UX8402ZA_UX8402Z... | Notebook    | [4dcc88b215](https://linux-hardware.org/?probe=4dcc88b215) | Jan 31, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [af3cf25119](https://linux-hardware.org/?probe=af3cf25119) | Jan 31, 2023 |
| Dell          | Latitude D630               | Notebook    | [ff0aa8c4ed](https://linux-hardware.org/?probe=ff0aa8c4ed) | Jan 31, 2023 |
| Dell          | Latitude D630               | Notebook    | [d8ac695aa3](https://linux-hardware.org/?probe=d8ac695aa3) | Jan 31, 2023 |
| Lenovo        | ThinkPad P51 20HJS0BR00     | Notebook    | [6c05048c9d](https://linux-hardware.org/?probe=6c05048c9d) | Jan 31, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [989e45d84b](https://linux-hardware.org/?probe=989e45d84b) | Jan 31, 2023 |
| MSI           | 870-G45                     | Desktop     | [cda1aade14](https://linux-hardware.org/?probe=cda1aade14) | Jan 31, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [6e7d6aae31](https://linux-hardware.org/?probe=6e7d6aae31) | Jan 31, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [6296345ebb](https://linux-hardware.org/?probe=6296345ebb) | Jan 31, 2023 |
| HP            | 339A                        | Desktop     | [e3078cd4d7](https://linux-hardware.org/?probe=e3078cd4d7) | Jan 31, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [6a0af9dbcb](https://linux-hardware.org/?probe=6a0af9dbcb) | Jan 31, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [0eac708be5](https://linux-hardware.org/?probe=0eac708be5) | Jan 31, 2023 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [1196b501d5](https://linux-hardware.org/?probe=1196b501d5) | Jan 31, 2023 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [9edd1a1969](https://linux-hardware.org/?probe=9edd1a1969) | Jan 30, 2023 |
| Intel         | DQ77MK AAG39642-500         | Desktop     | [3e004045f7](https://linux-hardware.org/?probe=3e004045f7) | Jan 30, 2023 |
| HP            | Notebook                    | Notebook    | [fc93f8e357](https://linux-hardware.org/?probe=fc93f8e357) | Jan 30, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [cbfcb68cc6](https://linux-hardware.org/?probe=cbfcb68cc6) | Jan 30, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [ec76a40223](https://linux-hardware.org/?probe=ec76a40223) | Jan 30, 2023 |
| Lenovo        | ThinkPad T430 2347G4U       | Notebook    | [5802e6b9b9](https://linux-hardware.org/?probe=5802e6b9b9) | Jan 30, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [f0000c6ae7](https://linux-hardware.org/?probe=f0000c6ae7) | Jan 30, 2023 |
| Lenovo        | ThinkPad T430 2347G4U       | Notebook    | [3fcf581653](https://linux-hardware.org/?probe=3fcf581653) | Jan 30, 2023 |
| Dell          | Vostro 7620                 | Notebook    | [b6d43b8741](https://linux-hardware.org/?probe=b6d43b8741) | Jan 29, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [830de1d797](https://linux-hardware.org/?probe=830de1d797) | Jan 29, 2023 |
| Microsoft     | Surface Laptop 4            | Tablet      | [77c9cc065f](https://linux-hardware.org/?probe=77c9cc065f) | Jan 29, 2023 |
| Microsoft     | Surface Laptop 4            | Tablet      | [1ddc17833b](https://linux-hardware.org/?probe=1ddc17833b) | Jan 29, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [6b99585bc0](https://linux-hardware.org/?probe=6b99585bc0) | Jan 29, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [104fb04e91](https://linux-hardware.org/?probe=104fb04e91) | Jan 29, 2023 |
| ASUSTek       | B150M-C                     | Desktop     | [6eb1a5b38e](https://linux-hardware.org/?probe=6eb1a5b38e) | Jan 29, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [03171e1e33](https://linux-hardware.org/?probe=03171e1e33) | Jan 29, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [9f2e4066f6](https://linux-hardware.org/?probe=9f2e4066f6) | Jan 29, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [f2bf9c3c82](https://linux-hardware.org/?probe=f2bf9c3c82) | Jan 28, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [2d2e42ae23](https://linux-hardware.org/?probe=2d2e42ae23) | Jan 28, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [3e7c902731](https://linux-hardware.org/?probe=3e7c902731) | Jan 28, 2023 |
| ASUSTek       | X555QA                      | Notebook    | [8eec8468fb](https://linux-hardware.org/?probe=8eec8468fb) | Jan 28, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [0da956ecde](https://linux-hardware.org/?probe=0da956ecde) | Jan 28, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [e00bd18cc2](https://linux-hardware.org/?probe=e00bd18cc2) | Jan 28, 2023 |
| Notebook      | P9XXEN_EF_ED                | Notebook    | [991bb71df8](https://linux-hardware.org/?probe=991bb71df8) | Jan 28, 2023 |
| Notebook      | P9XXEN_EF_ED                | Notebook    | [d86e915f12](https://linux-hardware.org/?probe=d86e915f12) | Jan 28, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [796df2715d](https://linux-hardware.org/?probe=796df2715d) | Jan 28, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [a6f188ab67](https://linux-hardware.org/?probe=a6f188ab67) | Jan 28, 2023 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [f328fab9f1](https://linux-hardware.org/?probe=f328fab9f1) | Jan 27, 2023 |
| Lenovo        | ThinkPad E485 20KUCTO1WW    | Notebook    | [49e82c2714](https://linux-hardware.org/?probe=49e82c2714) | Jan 27, 2023 |
| Dell          | 057FFP A01                  | Desktop     | [ec0e3da69d](https://linux-hardware.org/?probe=ec0e3da69d) | Jan 27, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [06c6af6032](https://linux-hardware.org/?probe=06c6af6032) | Jan 27, 2023 |
| ASUSTek       | P5K                         | Desktop     | [6d496e6965](https://linux-hardware.org/?probe=6d496e6965) | Jan 27, 2023 |
| ASUSTek       | PRIME X299-DELUXE II        | Desktop     | [c7e2bde422](https://linux-hardware.org/?probe=c7e2bde422) | Jan 27, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [c2a36422b4](https://linux-hardware.org/?probe=c2a36422b4) | Jan 27, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [38e4843e09](https://linux-hardware.org/?probe=38e4843e09) | Jan 27, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [55477da159](https://linux-hardware.org/?probe=55477da159) | Jan 27, 2023 |
| Dell          | Latitude E6540              | Notebook    | [2e014cf1ba](https://linux-hardware.org/?probe=2e014cf1ba) | Jan 27, 2023 |
| Acer          | Aspire R3-131T              | Notebook    | [021d999708](https://linux-hardware.org/?probe=021d999708) | Jan 27, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [f83ff94df6](https://linux-hardware.org/?probe=f83ff94df6) | Jan 27, 2023 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [6766a92ee5](https://linux-hardware.org/?probe=6766a92ee5) | Jan 27, 2023 |
| HP            | Compaq 8200 Elite SFF PC    | Desktop     | [73f629ca61](https://linux-hardware.org/?probe=73f629ca61) | Jan 27, 2023 |
| Dell          | Latitude E6420              | Notebook    | [9837928212](https://linux-hardware.org/?probe=9837928212) | Jan 26, 2023 |
| MSI           | X99A SLI PLUS               | Desktop     | [931a186515](https://linux-hardware.org/?probe=931a186515) | Jan 26, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [b9f3d19faa](https://linux-hardware.org/?probe=b9f3d19faa) | Jan 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [08204bf161](https://linux-hardware.org/?probe=08204bf161) | Jan 26, 2023 |
| Apple         | MacBookAir4,1               | Notebook    | [45ea832a59](https://linux-hardware.org/?probe=45ea832a59) | Jan 26, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [aa6488b6b8](https://linux-hardware.org/?probe=aa6488b6b8) | Jan 25, 2023 |
| Samsung       | 930QED                      | Convertible | [1a699655f8](https://linux-hardware.org/?probe=1a699655f8) | Jan 25, 2023 |
| Valve         | Jupiter                     | Notebook    | [ba217c947c](https://linux-hardware.org/?probe=ba217c947c) | Jan 25, 2023 |
| Valve         | Jupiter                     | Notebook    | [ffd9523db2](https://linux-hardware.org/?probe=ffd9523db2) | Jan 25, 2023 |
| ASUSTek       | Z87-A                       | Desktop     | [755bed02ff](https://linux-hardware.org/?probe=755bed02ff) | Jan 25, 2023 |
| ASUSTek       | Z87-A                       | Desktop     | [6ccfafe0d6](https://linux-hardware.org/?probe=6ccfafe0d6) | Jan 24, 2023 |
| Apple         | MacBookPro5,4               | Notebook    | [4bdccd0680](https://linux-hardware.org/?probe=4bdccd0680) | Jan 24, 2023 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [a4e4317d4d](https://linux-hardware.org/?probe=a4e4317d4d) | Jan 24, 2023 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | Desktop     | [0300fb4b9a](https://linux-hardware.org/?probe=0300fb4b9a) | Jan 24, 2023 |
| ASUSTek       | Z87-PRO                     | Desktop     | [ea0a73ca90](https://linux-hardware.org/?probe=ea0a73ca90) | Jan 24, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [610ffedb4c](https://linux-hardware.org/?probe=610ffedb4c) | Jan 24, 2023 |
| Lenovo        | 36E9 SDK0T08861 WIN 3305... | Desktop     | [82705366d7](https://linux-hardware.org/?probe=82705366d7) | Jan 24, 2023 |
| ASUSTek       | Z87-PRO                     | Desktop     | [8bbff4abbd](https://linux-hardware.org/?probe=8bbff4abbd) | Jan 24, 2023 |
| HP            | 339A                        | Desktop     | [a2784a6575](https://linux-hardware.org/?probe=a2784a6575) | Jan 24, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [71a9255bc8](https://linux-hardware.org/?probe=71a9255bc8) | Jan 24, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [e327d1dea4](https://linux-hardware.org/?probe=e327d1dea4) | Jan 24, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [f62d0d9183](https://linux-hardware.org/?probe=f62d0d9183) | Jan 24, 2023 |
| ASUSTek       | X555QA                      | Notebook    | [f981af502a](https://linux-hardware.org/?probe=f981af502a) | Jan 24, 2023 |
| Lenovo        | ThinkPad E485 20KUCTO1WW    | Notebook    | [495cd98904](https://linux-hardware.org/?probe=495cd98904) | Jan 23, 2023 |
| ASRock        | 990FX Killer                | Desktop     | [b6bd3a3bdb](https://linux-hardware.org/?probe=b6bd3a3bdb) | Jan 23, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [3d1f5b0ee9](https://linux-hardware.org/?probe=3d1f5b0ee9) | Jan 23, 2023 |
| Acer          | AO722                       | Notebook    | [85f48171a2](https://linux-hardware.org/?probe=85f48171a2) | Jan 23, 2023 |
| GPU Compan... | GWNR71517                   | Notebook    | [77d4494f3b](https://linux-hardware.org/?probe=77d4494f3b) | Jan 23, 2023 |
| GPU Compan... | GWNR71517                   | Notebook    | [f3d76bcb70](https://linux-hardware.org/?probe=f3d76bcb70) | Jan 23, 2023 |
| Dell          | Inspiron 3521               | Notebook    | [ff122405db](https://linux-hardware.org/?probe=ff122405db) | Jan 22, 2023 |
| Dell          | Inspiron 3521               | Notebook    | [bb77ccdda7](https://linux-hardware.org/?probe=bb77ccdda7) | Jan 22, 2023 |
| Lenovo        | ThinkCentre M90z 5205W5Q    | All in one  | [ed812a8a26](https://linux-hardware.org/?probe=ed812a8a26) | Jan 22, 2023 |
| Acer          | Aspire C24-960              | All in one  | [ff5e69ca71](https://linux-hardware.org/?probe=ff5e69ca71) | Jan 22, 2023 |
| MSI           | MS-AF82                     | All in one  | [7340fe42ba](https://linux-hardware.org/?probe=7340fe42ba) | Jan 22, 2023 |
| ASUSTek       | P5K                         | Desktop     | [dc5b823cb5](https://linux-hardware.org/?probe=dc5b823cb5) | Jan 22, 2023 |
| Dell          | Inspiron 3521               | Notebook    | [2189958490](https://linux-hardware.org/?probe=2189958490) | Jan 22, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | Notebook    | [76955052a7](https://linux-hardware.org/?probe=76955052a7) | Jan 22, 2023 |
| ASUSTek       | P8P67 LE                    | Desktop     | [6afc30df3b](https://linux-hardware.org/?probe=6afc30df3b) | Jan 22, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [8e037468e4](https://linux-hardware.org/?probe=8e037468e4) | Jan 22, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [6ae7274931](https://linux-hardware.org/?probe=6ae7274931) | Jan 22, 2023 |
| Acer          | Aspire E1-531               | Notebook    | [217c63b8f6](https://linux-hardware.org/?probe=217c63b8f6) | Jan 22, 2023 |
| Dell          | Latitude E5400              | Notebook    | [ee6e466820](https://linux-hardware.org/?probe=ee6e466820) | Jan 22, 2023 |
| Dell          | Latitude E5400              | Notebook    | [f61d1e0868](https://linux-hardware.org/?probe=f61d1e0868) | Jan 22, 2023 |
| MSI           | MPG Z390M GAMING EDGE AC    | Desktop     | [085d30a350](https://linux-hardware.org/?probe=085d30a350) | Jan 21, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [330a3844cb](https://linux-hardware.org/?probe=330a3844cb) | Jan 21, 2023 |
| Lenovo        | ThinkPad X13 Yoga Gen 2 ... | Convertible | [32faa4aac5](https://linux-hardware.org/?probe=32faa4aac5) | Jan 21, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [3eb2d3a903](https://linux-hardware.org/?probe=3eb2d3a903) | Jan 21, 2023 |
| Lenovo        | ThinkPad P52s 20LBCTO1WW    | Notebook    | [e0b197c0c4](https://linux-hardware.org/?probe=e0b197c0c4) | Jan 21, 2023 |
| ASUSTek       | P6T SE                      | Desktop     | [011553878f](https://linux-hardware.org/?probe=011553878f) | Jan 21, 2023 |
| HP            | Laptop 15-dy3xxx            | Notebook    | [1053d34e69](https://linux-hardware.org/?probe=1053d34e69) | Jan 20, 2023 |
| ASUSTek       | X555QA                      | Notebook    | [cd42f89819](https://linux-hardware.org/?probe=cd42f89819) | Jan 20, 2023 |
| Valve         | Jupiter                     | Notebook    | [e29a7a31ae](https://linux-hardware.org/?probe=e29a7a31ae) | Jan 20, 2023 |
| Lenovo        | ThinkPad Yoga 11e 4th Ge... | Convertible | [c79dd9971a](https://linux-hardware.org/?probe=c79dd9971a) | Jan 20, 2023 |
| Alienware     | 0N43JM A00                  | Desktop     | [06a6ec74c0](https://linux-hardware.org/?probe=06a6ec74c0) | Jan 20, 2023 |
| Dell          | Studio XPS 1647             | Notebook    | [4086a6120a](https://linux-hardware.org/?probe=4086a6120a) | Jan 20, 2023 |
| Lenovo        | 3767 WIN SDK0T76461 3422... | All in one  | [f9f38488a8](https://linux-hardware.org/?probe=f9f38488a8) | Jan 19, 2023 |
| ASUSTek       | ROG Strix G512LU_G512LU     | Notebook    | [edc36777f0](https://linux-hardware.org/?probe=edc36777f0) | Jan 19, 2023 |
| Toshiba       | Satellite L650D             | Notebook    | [86d99d74cd](https://linux-hardware.org/?probe=86d99d74cd) | Jan 19, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [0770f064de](https://linux-hardware.org/?probe=0770f064de) | Jan 19, 2023 |
| Intel Clie... | LAPRC510                    | Notebook    | [6d570a1aee](https://linux-hardware.org/?probe=6d570a1aee) | Jan 19, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [68a73ee517](https://linux-hardware.org/?probe=68a73ee517) | Jan 19, 2023 |
| ASUSTek       | P6T SE                      | Desktop     | [d13ca33fcf](https://linux-hardware.org/?probe=d13ca33fcf) | Jan 18, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [8af55733d7](https://linux-hardware.org/?probe=8af55733d7) | Jan 18, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [9a99559833](https://linux-hardware.org/?probe=9a99559833) | Jan 18, 2023 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [dfac4d4f79](https://linux-hardware.org/?probe=dfac4d4f79) | Jan 17, 2023 |
| Lenovo        | ThinkPad T420 4236V6S       | Notebook    | [3ab44ae2f5](https://linux-hardware.org/?probe=3ab44ae2f5) | Jan 17, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [b45cef8a55](https://linux-hardware.org/?probe=b45cef8a55) | Jan 17, 2023 |
| HP            | Pavilion dv7                | Notebook    | [2efb4b16de](https://linux-hardware.org/?probe=2efb4b16de) | Jan 17, 2023 |
| ASUSTek       | Z97-A                       | Desktop     | [c1b01960be](https://linux-hardware.org/?probe=c1b01960be) | Jan 17, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [d173b719da](https://linux-hardware.org/?probe=d173b719da) | Jan 17, 2023 |
| Foxconn       | nT-A3000 series FAB         | Desktop     | [0bdefb0a4f](https://linux-hardware.org/?probe=0bdefb0a4f) | Jan 17, 2023 |
| MSI           | MS-AF82                     | All in one  | [82cc6bd7b4](https://linux-hardware.org/?probe=82cc6bd7b4) | Jan 17, 2023 |
| MSI           | MS-AF82                     | All in one  | [57e12122db](https://linux-hardware.org/?probe=57e12122db) | Jan 17, 2023 |
| ASUSTek       | ZenBook UX363EA_UX371EA     | Convertible | [c371212092](https://linux-hardware.org/?probe=c371212092) | Jan 17, 2023 |
| MSI           | MS-AF82                     | All in one  | [6fb499c15a](https://linux-hardware.org/?probe=6fb499c15a) | Jan 17, 2023 |
| Dell          | Inspiron 3521               | Notebook    | [2d46e86664](https://linux-hardware.org/?probe=2d46e86664) | Jan 17, 2023 |
| ASUSTek       | P5K-E                       | Desktop     | [2b7ce8a40b](https://linux-hardware.org/?probe=2b7ce8a40b) | Jan 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [a602bcd50a](https://linux-hardware.org/?probe=a602bcd50a) | Jan 17, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [c5387e7fd9](https://linux-hardware.org/?probe=c5387e7fd9) | Jan 17, 2023 |
| Lenovo        | ThinkPad T420 4236AK9       | Notebook    | [1bd88ff8c7](https://linux-hardware.org/?probe=1bd88ff8c7) | Jan 17, 2023 |
| Valve         | Jupiter                     | Notebook    | [2b355faaee](https://linux-hardware.org/?probe=2b355faaee) | Jan 16, 2023 |
| Dell          | Inspiron 3521               | Notebook    | [da7f445f06](https://linux-hardware.org/?probe=da7f445f06) | Jan 16, 2023 |
| Foxconn       | ALOE                        | Desktop     | [0b3564ef16](https://linux-hardware.org/?probe=0b3564ef16) | Jan 16, 2023 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [69b469a6fb](https://linux-hardware.org/?probe=69b469a6fb) | Jan 16, 2023 |
| HP            | Pavilion 17                 | Notebook    | [09b186fbf7](https://linux-hardware.org/?probe=09b186fbf7) | Jan 16, 2023 |
| MSI           | 990FXA-GD80                 | Desktop     | [bbddcc3653](https://linux-hardware.org/?probe=bbddcc3653) | Jan 16, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [9b1e965bca](https://linux-hardware.org/?probe=9b1e965bca) | Jan 16, 2023 |
| Lenovo        | ThinkPad T440s 20AQCTO1W... | Notebook    | [e04d230b62](https://linux-hardware.org/?probe=e04d230b62) | Jan 16, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [4572999070](https://linux-hardware.org/?probe=4572999070) | Jan 16, 2023 |
| Lenovo        | IdeaPad Slim 7 Carbon 14... | Notebook    | [620185bf98](https://linux-hardware.org/?probe=620185bf98) | Jan 15, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [422f31719c](https://linux-hardware.org/?probe=422f31719c) | Jan 15, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [c16748dc74](https://linux-hardware.org/?probe=c16748dc74) | Jan 15, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [f7422d49df](https://linux-hardware.org/?probe=f7422d49df) | Jan 15, 2023 |
| Lenovo        | G560 0679                   | Notebook    | [26e16a5898](https://linux-hardware.org/?probe=26e16a5898) | Jan 15, 2023 |
| ASUSTek       | GD30CI                      | Desktop     | [7d1227f25f](https://linux-hardware.org/?probe=7d1227f25f) | Jan 15, 2023 |
| Toshiba       | Satellite L650              | Notebook    | [b893aecea2](https://linux-hardware.org/?probe=b893aecea2) | Jan 15, 2023 |
| ASUSTek       | GD30CI                      | Desktop     | [2ed7e76dbe](https://linux-hardware.org/?probe=2ed7e76dbe) | Jan 15, 2023 |
| Dell          | 0WK833                      | Desktop     | [100d6694e5](https://linux-hardware.org/?probe=100d6694e5) | Jan 15, 2023 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [227b58bf8f](https://linux-hardware.org/?probe=227b58bf8f) | Jan 15, 2023 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [23748f30aa](https://linux-hardware.org/?probe=23748f30aa) | Jan 15, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [202535bce7](https://linux-hardware.org/?probe=202535bce7) | Jan 15, 2023 |
| ASUSTek       | P5B-VM                      | Desktop     | [53b563ef2f](https://linux-hardware.org/?probe=53b563ef2f) | Jan 15, 2023 |
| Valve         | Jupiter                     | Notebook    | [c9bc8bf29b](https://linux-hardware.org/?probe=c9bc8bf29b) | Jan 15, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [9527eef253](https://linux-hardware.org/?probe=9527eef253) | Jan 15, 2023 |
| Dell          | 0UW457 A04                  | Desktop     | [0c637493cc](https://linux-hardware.org/?probe=0c637493cc) | Jan 15, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [6194c3a2fe](https://linux-hardware.org/?probe=6194c3a2fe) | Jan 15, 2023 |
| Lenovo        | ThinkPad T420 4236V6S       | Notebook    | [a24b95f891](https://linux-hardware.org/?probe=a24b95f891) | Jan 15, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [4776fc6062](https://linux-hardware.org/?probe=4776fc6062) | Jan 15, 2023 |
| Lenovo        | ThinkPad T420 4236V6S       | Notebook    | [f9fe88837c](https://linux-hardware.org/?probe=f9fe88837c) | Jan 15, 2023 |
| Lenovo        | ThinkPad T420 4236V6S       | Notebook    | [59607f5e75](https://linux-hardware.org/?probe=59607f5e75) | Jan 15, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [a4b4747500](https://linux-hardware.org/?probe=a4b4747500) | Jan 14, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [4340505060](https://linux-hardware.org/?probe=4340505060) | Jan 14, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [03f7a5fdea](https://linux-hardware.org/?probe=03f7a5fdea) | Jan 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [db57593b81](https://linux-hardware.org/?probe=db57593b81) | Jan 14, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [9e4c15fff7](https://linux-hardware.org/?probe=9e4c15fff7) | Jan 14, 2023 |
| ASUSTek       | P8H61-M LE/CSM              | Desktop     | [06aff9f10a](https://linux-hardware.org/?probe=06aff9f10a) | Jan 14, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [77d37c245a](https://linux-hardware.org/?probe=77d37c245a) | Jan 14, 2023 |
| MSI           | GP72 7RDX                   | Notebook    | [9cf1da2d69](https://linux-hardware.org/?probe=9cf1da2d69) | Jan 14, 2023 |
| Dell          | Latitude E6420              | Notebook    | [e7c4823aee](https://linux-hardware.org/?probe=e7c4823aee) | Jan 14, 2023 |
| MSI           | X99A SLI PLUS               | Desktop     | [4ab9753ab5](https://linux-hardware.org/?probe=4ab9753ab5) | Jan 14, 2023 |
| HP            | Notebook                    | Notebook    | [e242059a08](https://linux-hardware.org/?probe=e242059a08) | Jan 14, 2023 |
| MSI           | B450 GAMING PRO CARBON M... | Desktop     | [c01da2fcf9](https://linux-hardware.org/?probe=c01da2fcf9) | Jan 14, 2023 |
| MSI           | B450 GAMING PRO CARBON M... | Desktop     | [d4a8ff871f](https://linux-hardware.org/?probe=d4a8ff871f) | Jan 14, 2023 |
| Lenovo        | ThinkCentre XXXX 7360EHF    | Desktop     | [fdfe8c5881](https://linux-hardware.org/?probe=fdfe8c5881) | Jan 13, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [ed62a9383e](https://linux-hardware.org/?probe=ed62a9383e) | Jan 13, 2023 |
| Dell          | XPS 13 9365                 | Convertible | [9730761eb1](https://linux-hardware.org/?probe=9730761eb1) | Jan 13, 2023 |
| Acer          | Aspire X1800                | Desktop     | [16f6ad749f](https://linux-hardware.org/?probe=16f6ad749f) | Jan 13, 2023 |
| Dell          | 0UW457 A04                  | Desktop     | [4c5689de9c](https://linux-hardware.org/?probe=4c5689de9c) | Jan 13, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [eeec2db688](https://linux-hardware.org/?probe=eeec2db688) | Jan 13, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [d7c612580f](https://linux-hardware.org/?probe=d7c612580f) | Jan 13, 2023 |
| Acer          | Aspire E1-572               | Notebook    | [fa6e296766](https://linux-hardware.org/?probe=fa6e296766) | Jan 13, 2023 |
| Acer          | Aspire X1800                | Desktop     | [929228726d](https://linux-hardware.org/?probe=929228726d) | Jan 13, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [da5cb78b32](https://linux-hardware.org/?probe=da5cb78b32) | Jan 12, 2023 |
| ASUSTek       | M3N78-VM                    | Desktop     | [dad2489f95](https://linux-hardware.org/?probe=dad2489f95) | Jan 12, 2023 |
| ASUSTek       | P5K                         | Desktop     | [ec9ba21c49](https://linux-hardware.org/?probe=ec9ba21c49) | Jan 12, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [1706cf55cf](https://linux-hardware.org/?probe=1706cf55cf) | Jan 12, 2023 |
| ASRockRack    | E3C246D4U2-2T               | Desktop     | [354d25ae30](https://linux-hardware.org/?probe=354d25ae30) | Jan 12, 2023 |
| Acer          | Aspire M3450                | Desktop     | [0ed84a21b2](https://linux-hardware.org/?probe=0ed84a21b2) | Jan 12, 2023 |
| ASUSTek       | G11CD                       | Desktop     | [f39178befb](https://linux-hardware.org/?probe=f39178befb) | Jan 12, 2023 |
| Dell          | 0DXJD9 A01                  | Desktop     | [78549912fa](https://linux-hardware.org/?probe=78549912fa) | Jan 12, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | Notebook    | [fad743f278](https://linux-hardware.org/?probe=fad743f278) | Jan 12, 2023 |
| ECS           | A55F-M2                     | Desktop     | [b891de98a1](https://linux-hardware.org/?probe=b891de98a1) | Jan 11, 2023 |
| Matsushita... | CF-18KH2ZXBC                | Notebook    | [41e8ef7b23](https://linux-hardware.org/?probe=41e8ef7b23) | Jan 11, 2023 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [f78e703512](https://linux-hardware.org/?probe=f78e703512) | Jan 11, 2023 |
| Dell          | 0PM2CW A05                  | Server      | [d76d38ba9b](https://linux-hardware.org/?probe=d76d38ba9b) | Jan 11, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [0f1f6b2662](https://linux-hardware.org/?probe=0f1f6b2662) | Jan 11, 2023 |
| ASUSTek       | Z97-E/USB                   | Desktop     | [b4b3e05975](https://linux-hardware.org/?probe=b4b3e05975) | Jan 11, 2023 |
| HP            | 18E4                        | Desktop     | [600d82b264](https://linux-hardware.org/?probe=600d82b264) | Jan 11, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [747c3d8c1f](https://linux-hardware.org/?probe=747c3d8c1f) | Jan 11, 2023 |
| Valve         | Jupiter                     | Notebook    | [6bfa934fb6](https://linux-hardware.org/?probe=6bfa934fb6) | Jan 11, 2023 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | Desktop     | [1705a3f042](https://linux-hardware.org/?probe=1705a3f042) | Jan 11, 2023 |
| Dell          | G5 5590                     | Notebook    | [846a462365](https://linux-hardware.org/?probe=846a462365) | Jan 10, 2023 |
| Lenovo        | ThinkPad T450s 20BX001PU... | Notebook    | [c6e3650e2b](https://linux-hardware.org/?probe=c6e3650e2b) | Jan 10, 2023 |
| HP            | 18E4                        | Desktop     | [3386d53667](https://linux-hardware.org/?probe=3386d53667) | Jan 10, 2023 |
| HP            | 8433 11                     | Desktop     | [2036bb2c1a](https://linux-hardware.org/?probe=2036bb2c1a) | Jan 10, 2023 |
| ASUSTek       | P5K                         | Desktop     | [64c746ef0b](https://linux-hardware.org/?probe=64c746ef0b) | Jan 10, 2023 |
| System76      | Darter Pro                  | Notebook    | [ffaaf5c90e](https://linux-hardware.org/?probe=ffaaf5c90e) | Jan 10, 2023 |
| HP            | ENVY Notebook               | Notebook    | [ff8cd12017](https://linux-hardware.org/?probe=ff8cd12017) | Jan 10, 2023 |
| Google        | Blooglet                    | Notebook    | [bf644ec6f4](https://linux-hardware.org/?probe=bf644ec6f4) | Jan 10, 2023 |
| Dell          | Inspiron 5577               | Notebook    | [86cfa19622](https://linux-hardware.org/?probe=86cfa19622) | Jan 10, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [66ffdd11c5](https://linux-hardware.org/?probe=66ffdd11c5) | Jan 10, 2023 |
| Lenovo        | ThinkPad T420 4236A38       | Notebook    | [302f3a5ebe](https://linux-hardware.org/?probe=302f3a5ebe) | Jan 10, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [0a2fd6c8e7](https://linux-hardware.org/?probe=0a2fd6c8e7) | Jan 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | Notebook    | [2bbe617df6](https://linux-hardware.org/?probe=2bbe617df6) | Jan 09, 2023 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [f2895e4b94](https://linux-hardware.org/?probe=f2895e4b94) | Jan 09, 2023 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [d6115e24c1](https://linux-hardware.org/?probe=d6115e24c1) | Jan 09, 2023 |
| ASRockRack    | X470D4U                     | Desktop     | [0e51eb7caa](https://linux-hardware.org/?probe=0e51eb7caa) | Jan 09, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [a14e62fdf8](https://linux-hardware.org/?probe=a14e62fdf8) | Jan 09, 2023 |
| GPU Compan... | GWNR71517                   | Notebook    | [5626a7c211](https://linux-hardware.org/?probe=5626a7c211) | Jan 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [f884203e84](https://linux-hardware.org/?probe=f884203e84) | Jan 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [b518c0a817](https://linux-hardware.org/?probe=b518c0a817) | Jan 09, 2023 |
| ASUSTek       | X550ZA                      | Notebook    | [272bff51c5](https://linux-hardware.org/?probe=272bff51c5) | Jan 09, 2023 |
| Dell          | 084J0R A00                  | Desktop     | [7aaeb8fbfc](https://linux-hardware.org/?probe=7aaeb8fbfc) | Jan 08, 2023 |
| GPU Compan... | GWNR71517                   | Notebook    | [11cb3f9636](https://linux-hardware.org/?probe=11cb3f9636) | Jan 08, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [c8e96fe453](https://linux-hardware.org/?probe=c8e96fe453) | Jan 08, 2023 |
| Lenovo        | ThinkPad T420 4236A38       | Notebook    | [b95882e5cf](https://linux-hardware.org/?probe=b95882e5cf) | Jan 08, 2023 |
| HP            | 2B05                        | Desktop     | [a6f3a8c157](https://linux-hardware.org/?probe=a6f3a8c157) | Jan 08, 2023 |
| Lenovo        | N22 80S6                    | Notebook    | [cfcc0a49c6](https://linux-hardware.org/?probe=cfcc0a49c6) | Jan 08, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [e8e8ca3959](https://linux-hardware.org/?probe=e8e8ca3959) | Jan 08, 2023 |
| Valve         | Jupiter                     | Notebook    | [4c96ccba44](https://linux-hardware.org/?probe=4c96ccba44) | Jan 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [2e22cc1bb2](https://linux-hardware.org/?probe=2e22cc1bb2) | Jan 08, 2023 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [2dfeda8d20](https://linux-hardware.org/?probe=2dfeda8d20) | Jan 08, 2023 |
| Gigabyte      | X570S I AORUS PRO AX        | Desktop     | [2b8206db29](https://linux-hardware.org/?probe=2b8206db29) | Jan 08, 2023 |
| Lenovo        | ThinkPad W520 4284A24       | Notebook    | [263e00840a](https://linux-hardware.org/?probe=263e00840a) | Jan 08, 2023 |
| Gigabyte      | X570S I AORUS PRO AX        | Desktop     | [68fe02a04c](https://linux-hardware.org/?probe=68fe02a04c) | Jan 08, 2023 |
| Dell          | XPS 9320                    | Notebook    | [55be119900](https://linux-hardware.org/?probe=55be119900) | Jan 08, 2023 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [15f31fc9a5](https://linux-hardware.org/?probe=15f31fc9a5) | Jan 07, 2023 |
| ASRock        | H470M-STX                   | Desktop     | [60b8fb9dc4](https://linux-hardware.org/?probe=60b8fb9dc4) | Jan 07, 2023 |
| ASUSTek       | M4A785-M                    | Desktop     | [be50406f89](https://linux-hardware.org/?probe=be50406f89) | Jan 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [83ec1382a3](https://linux-hardware.org/?probe=83ec1382a3) | Jan 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [354b2538a4](https://linux-hardware.org/?probe=354b2538a4) | Jan 07, 2023 |
| HP            | Pavilion dv4                | Notebook    | [5caee4abe0](https://linux-hardware.org/?probe=5caee4abe0) | Jan 07, 2023 |
| Lenovo        | ThinkCentre M90z 5205W5Q    | All in one  | [3267811ed5](https://linux-hardware.org/?probe=3267811ed5) | Jan 07, 2023 |
| ASUSTek       | Z97-C                       | Desktop     | [2b61136e8d](https://linux-hardware.org/?probe=2b61136e8d) | Jan 07, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [15eaac1fac](https://linux-hardware.org/?probe=15eaac1fac) | Jan 07, 2023 |
| HP            | Elite x2 1011 G1 Tablet     | Notebook    | [28c9b60939](https://linux-hardware.org/?probe=28c9b60939) | Jan 07, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [22894be0e8](https://linux-hardware.org/?probe=22894be0e8) | Jan 06, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [ff95fa094b](https://linux-hardware.org/?probe=ff95fa094b) | Jan 06, 2023 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [1720ed7ed6](https://linux-hardware.org/?probe=1720ed7ed6) | Jan 06, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [1608711aa0](https://linux-hardware.org/?probe=1608711aa0) | Jan 06, 2023 |
| ASUSTek       | X301A1                      | Notebook    | [e575482522](https://linux-hardware.org/?probe=e575482522) | Jan 06, 2023 |
| Dell          | G15 5525                    | Notebook    | [2c61cbc942](https://linux-hardware.org/?probe=2c61cbc942) | Jan 06, 2023 |
| MSI           | Z97 GAMING 5                | Desktop     | [1edff66d1a](https://linux-hardware.org/?probe=1edff66d1a) | Jan 06, 2023 |
| Lenovo        | ThinkPad T450s 20BX001PU... | Notebook    | [4d2721777a](https://linux-hardware.org/?probe=4d2721777a) | Jan 06, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [f9f6df3b14](https://linux-hardware.org/?probe=f9f6df3b14) | Jan 06, 2023 |
| Lenovo        | ThinkPad X131e 33723FU      | Notebook    | [d2ee3f78a9](https://linux-hardware.org/?probe=d2ee3f78a9) | Jan 06, 2023 |
| Lenovo        | ThinkPad X131e 33723FU      | Notebook    | [9c9801b860](https://linux-hardware.org/?probe=9c9801b860) | Jan 06, 2023 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [7fe70dc4c8](https://linux-hardware.org/?probe=7fe70dc4c8) | Jan 06, 2023 |
| Lenovo        | ThinkPad T450s 20BX001PU... | Notebook    | [907ceedda1](https://linux-hardware.org/?probe=907ceedda1) | Jan 05, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [1c58ea8841](https://linux-hardware.org/?probe=1c58ea8841) | Jan 05, 2023 |
| ASUSTek       | P5WD2-E Premium             | Desktop     | [c97e28eb76](https://linux-hardware.org/?probe=c97e28eb76) | Jan 05, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [47938bccb6](https://linux-hardware.org/?probe=47938bccb6) | Jan 05, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [0fb5f590d5](https://linux-hardware.org/?probe=0fb5f590d5) | Jan 05, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [90cbbe6b1d](https://linux-hardware.org/?probe=90cbbe6b1d) | Jan 04, 2023 |
| Lenovo        | 1031 SBB0J05441 WIN 3305... | Desktop     | [0ff94735bd](https://linux-hardware.org/?probe=0ff94735bd) | Jan 04, 2023 |
| ASUSTek       | PRIME B650M-A AX            | Desktop     | [872a58377f](https://linux-hardware.org/?probe=872a58377f) | Jan 04, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [2da57c3386](https://linux-hardware.org/?probe=2da57c3386) | Jan 04, 2023 |
| HP            | 1998                        | Desktop     | [7c067688db](https://linux-hardware.org/?probe=7c067688db) | Jan 04, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [50d8f0c1cb](https://linux-hardware.org/?probe=50d8f0c1cb) | Jan 04, 2023 |
| HP            | 1998                        | Desktop     | [1eb07196f7](https://linux-hardware.org/?probe=1eb07196f7) | Jan 04, 2023 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [5c352967e4](https://linux-hardware.org/?probe=5c352967e4) | Jan 04, 2023 |
| Dell          | Latitude 7420               | Notebook    | [e770b3e784](https://linux-hardware.org/?probe=e770b3e784) | Jan 04, 2023 |
| Dell          | Latitude 7420               | Notebook    | [bab9b86606](https://linux-hardware.org/?probe=bab9b86606) | Jan 04, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [3d589a827c](https://linux-hardware.org/?probe=3d589a827c) | Jan 04, 2023 |
| Dell          | 0M9KCM A02                  | Desktop     | [dc9d77448b](https://linux-hardware.org/?probe=dc9d77448b) | Jan 04, 2023 |
| Dell          | Latitude D520               | Notebook    | [7f05ddf105](https://linux-hardware.org/?probe=7f05ddf105) | Jan 04, 2023 |
| Datto         | Unknown                     | Notebook    | [e8c9c2e91f](https://linux-hardware.org/?probe=e8c9c2e91f) | Jan 04, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [2e047c3ad5](https://linux-hardware.org/?probe=2e047c3ad5) | Jan 04, 2023 |
| Pegatron      | 2ACF                        | Desktop     | [50da80ab44](https://linux-hardware.org/?probe=50da80ab44) | Jan 04, 2023 |
| Lenovo        | MAHOBAY No DPK              | Desktop     | [b829ec9d52](https://linux-hardware.org/?probe=b829ec9d52) | Jan 03, 2023 |
| HP            | Pavilion dv7                | Notebook    | [574f62a8ad](https://linux-hardware.org/?probe=574f62a8ad) | Jan 03, 2023 |
| Lenovo        | IdeaPad Yoga 11S 20246      | Notebook    | [a73ca839a1](https://linux-hardware.org/?probe=a73ca839a1) | Jan 03, 2023 |
| Dell          | Inspiron 5515               | Notebook    | [27a4df28b2](https://linux-hardware.org/?probe=27a4df28b2) | Jan 03, 2023 |
| Dell          | Inspiron 7706 2n1           | Convertible | [71ebcdc5ff](https://linux-hardware.org/?probe=71ebcdc5ff) | Jan 02, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [386eb7bc28](https://linux-hardware.org/?probe=386eb7bc28) | Jan 02, 2023 |
| HP            | 0AACh                       | Desktop     | [216ba22b5a](https://linux-hardware.org/?probe=216ba22b5a) | Jan 02, 2023 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [f85aeab3e5](https://linux-hardware.org/?probe=f85aeab3e5) | Jan 02, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [0e4b6aa6c2](https://linux-hardware.org/?probe=0e4b6aa6c2) | Jan 02, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [b613cd1179](https://linux-hardware.org/?probe=b613cd1179) | Jan 02, 2023 |
| Dell          | Latitude E5440              | Notebook    | [d8b08abf08](https://linux-hardware.org/?probe=d8b08abf08) | Jan 02, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [13df46e700](https://linux-hardware.org/?probe=13df46e700) | Jan 02, 2023 |
| Razer         | Blade 15 (2022) - RZ09-0... | Notebook    | [b9522e3683](https://linux-hardware.org/?probe=b9522e3683) | Jan 02, 2023 |
| HP            | 0AACh                       | Desktop     | [0730634b36](https://linux-hardware.org/?probe=0730634b36) | Jan 02, 2023 |
| ASUSTek       | F2A85-V PRO                 | Desktop     | [f252f31761](https://linux-hardware.org/?probe=f252f31761) | Jan 01, 2023 |
| HP            | Pavilion dv6                | Notebook    | [d735200dcf](https://linux-hardware.org/?probe=d735200dcf) | Jan 01, 2023 |
| Valve         | Jupiter                     | Notebook    | [1dedff3ad9](https://linux-hardware.org/?probe=1dedff3ad9) | Jan 01, 2023 |
| MSI           | PRO B550-VC                 | Desktop     | [f5574e6e00](https://linux-hardware.org/?probe=f5574e6e00) | Jan 01, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [13c0ee7f2d](https://linux-hardware.org/?probe=13c0ee7f2d) | Jan 01, 2023 |
| Dell          | Latitude E7450              | Notebook    | [f48717bb6f](https://linux-hardware.org/?probe=f48717bb6f) | Jan 01, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [b79de349a9](https://linux-hardware.org/?probe=b79de349a9) | Jan 01, 2023 |
| HP            | 18E4                        | Desktop     | [c83c8341e3](https://linux-hardware.org/?probe=c83c8341e3) | Jan 01, 2023 |
| Acer          | Predator PO3-600 V:1.1      | Desktop     | [e5f5073bcd](https://linux-hardware.org/?probe=e5f5073bcd) | Dec 31, 2022 |
| MSI           | A88X-G45 GAMING             | Desktop     | [891e0757ed](https://linux-hardware.org/?probe=891e0757ed) | Dec 31, 2022 |
| MSI           | A88X-G45 GAMING             | Desktop     | [bdb45edaad](https://linux-hardware.org/?probe=bdb45edaad) | Dec 31, 2022 |
| Acer          | Aspire E5-521               | Notebook    | [d9b5e3cfc3](https://linux-hardware.org/?probe=d9b5e3cfc3) | Dec 31, 2022 |
| Intel Clie... | LAPRC710                    | Notebook    | [47e562afc7](https://linux-hardware.org/?probe=47e562afc7) | Dec 31, 2022 |
| HP            | 18E4                        | Desktop     | [1b1eccbbe1](https://linux-hardware.org/?probe=1b1eccbbe1) | Dec 31, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [b0dd8fc6b5](https://linux-hardware.org/?probe=b0dd8fc6b5) | Dec 31, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [92ce347d5f](https://linux-hardware.org/?probe=92ce347d5f) | Dec 31, 2022 |
| ASUSTek       | TP501UA                     | Notebook    | [1f2aaf8804](https://linux-hardware.org/?probe=1f2aaf8804) | Dec 30, 2022 |
| Dell          | 0XPDFK A01                  | Desktop     | [37d47ff0dc](https://linux-hardware.org/?probe=37d47ff0dc) | Dec 30, 2022 |
| ASUSTek       | P8B-M Series                | Server      | [b559ad98cf](https://linux-hardware.org/?probe=b559ad98cf) | Dec 30, 2022 |
| Acer          | Aspire XC-885 V:1.1         | Desktop     | [4f3bc75747](https://linux-hardware.org/?probe=4f3bc75747) | Dec 30, 2022 |
| Acer          | Aspire XC-885 V:1.1         | Desktop     | [e0f8b8c7b9](https://linux-hardware.org/?probe=e0f8b8c7b9) | Dec 30, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [770c5eee84](https://linux-hardware.org/?probe=770c5eee84) | Dec 30, 2022 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [a323cc954e](https://linux-hardware.org/?probe=a323cc954e) | Dec 30, 2022 |
| Acer          | Aspire A115-32              | Notebook    | [7c8ec90c8a](https://linux-hardware.org/?probe=7c8ec90c8a) | Dec 30, 2022 |
| ASUSTek       | PRIME X399-A                | Desktop     | [d8ae46ad2b](https://linux-hardware.org/?probe=d8ae46ad2b) | Dec 30, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [4d915292f4](https://linux-hardware.org/?probe=4d915292f4) | Dec 30, 2022 |
| Lenovo        | 3181 SEK0T35577 IOT 4247... | Mini pc     | [fa1b60ae23](https://linux-hardware.org/?probe=fa1b60ae23) | Dec 29, 2022 |
| Dell          | 0UW457 A04                  | Desktop     | [047e7036d4](https://linux-hardware.org/?probe=047e7036d4) | Dec 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | Notebook    | [1cab27a65e](https://linux-hardware.org/?probe=1cab27a65e) | Dec 29, 2022 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [36074d3f54](https://linux-hardware.org/?probe=36074d3f54) | Dec 29, 2022 |
| HP            | EliteBook 2540p             | Notebook    | [ec9251ac5d](https://linux-hardware.org/?probe=ec9251ac5d) | Dec 28, 2022 |
| Dell          | 0VRWRC A00                  | Desktop     | [2135b5161f](https://linux-hardware.org/?probe=2135b5161f) | Dec 28, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [9e95d6a4ac](https://linux-hardware.org/?probe=9e95d6a4ac) | Dec 28, 2022 |
| ASUSTek       | ROG Strix G513QE_G513QE     | Notebook    | [00a92c3818](https://linux-hardware.org/?probe=00a92c3818) | Dec 28, 2022 |
| ASUSTek       | M4N72-E                     | Desktop     | [1902350147](https://linux-hardware.org/?probe=1902350147) | Dec 28, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [fba6e6e090](https://linux-hardware.org/?probe=fba6e6e090) | Dec 27, 2022 |
| Acer          | Aspire M3970                | Desktop     | [c2232f44d6](https://linux-hardware.org/?probe=c2232f44d6) | Dec 27, 2022 |
| Panasonic     | FZ55-2                      | Notebook    | [1699b7c3b2](https://linux-hardware.org/?probe=1699b7c3b2) | Dec 27, 2022 |
| Microsoft     | Surface Book                | Tablet      | [c374cd1b63](https://linux-hardware.org/?probe=c374cd1b63) | Dec 27, 2022 |
| Acer          | Aspire XC-885 V:1.1         | Desktop     | [bfc68f7816](https://linux-hardware.org/?probe=bfc68f7816) | Dec 27, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [d1d8257c05](https://linux-hardware.org/?probe=d1d8257c05) | Dec 27, 2022 |
| Lenovo        | ThinkPad T500 205545F       | Notebook    | [c12d9f8c6a](https://linux-hardware.org/?probe=c12d9f8c6a) | Dec 27, 2022 |
| Dell          | Latitude E7440              | Notebook    | [f2c052dde9](https://linux-hardware.org/?probe=f2c052dde9) | Dec 27, 2022 |
| Microsoft     | Surface Book                | Tablet      | [e9380c21e6](https://linux-hardware.org/?probe=e9380c21e6) | Dec 26, 2022 |
| Lenovo        | ThinkPad E560 20EV002FUS    | Notebook    | [3bb1c5cc47](https://linux-hardware.org/?probe=3bb1c5cc47) | Dec 26, 2022 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [c9668c2e08](https://linux-hardware.org/?probe=c9668c2e08) | Dec 26, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [877e3cd944](https://linux-hardware.org/?probe=877e3cd944) | Dec 26, 2022 |
| Dell          | Latitude E4310              | Notebook    | [f63df6ad2c](https://linux-hardware.org/?probe=f63df6ad2c) | Dec 26, 2022 |
| HP            | 3397                        | Desktop     | [c546bb007b](https://linux-hardware.org/?probe=c546bb007b) | Dec 26, 2022 |
| HP            | 3397                        | Desktop     | [4286520907](https://linux-hardware.org/?probe=4286520907) | Dec 26, 2022 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [82b0efdce8](https://linux-hardware.org/?probe=82b0efdce8) | Dec 25, 2022 |
| Gigabyte      | B660M AORUS PRO AX DDR4     | Desktop     | [7b965d8da8](https://linux-hardware.org/?probe=7b965d8da8) | Dec 25, 2022 |
| ASRock        | Z390 Phantom Gaming 6       | Desktop     | [61be8271df](https://linux-hardware.org/?probe=61be8271df) | Dec 25, 2022 |
| Lenovo        | ThinkPad T500 2055A38       | Notebook    | [90a67d3589](https://linux-hardware.org/?probe=90a67d3589) | Dec 25, 2022 |
| Valve         | Jupiter                     | Notebook    | [91be8cc560](https://linux-hardware.org/?probe=91be8cc560) | Dec 25, 2022 |
| Lenovo        | ThinkPad T495 20NKS01W02    | Notebook    | [cc7b02033a](https://linux-hardware.org/?probe=cc7b02033a) | Dec 24, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [dc6cc81a73](https://linux-hardware.org/?probe=dc6cc81a73) | Dec 24, 2022 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [c8b4b6d3bc](https://linux-hardware.org/?probe=c8b4b6d3bc) | Dec 24, 2022 |
| HP            | Pavilion dv7                | Notebook    | [a099e9b6ac](https://linux-hardware.org/?probe=a099e9b6ac) | Dec 24, 2022 |
| System76      | Pangolin                    | Notebook    | [1c936bfe04](https://linux-hardware.org/?probe=1c936bfe04) | Dec 24, 2022 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [90802fc782](https://linux-hardware.org/?probe=90802fc782) | Dec 24, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [d1e21fd9ca](https://linux-hardware.org/?probe=d1e21fd9ca) | Dec 23, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [7fe5933133](https://linux-hardware.org/?probe=7fe5933133) | Dec 23, 2022 |
| MSI           | Pulse GL76 12UEK            | Notebook    | [9ca4075241](https://linux-hardware.org/?probe=9ca4075241) | Dec 23, 2022 |
| MSI           | Pulse GL76 12UEK            | Notebook    | [099b612c13](https://linux-hardware.org/?probe=099b612c13) | Dec 23, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [723811132a](https://linux-hardware.org/?probe=723811132a) | Dec 23, 2022 |
| Toshiba       | TECRA R940                  | Notebook    | [939e438746](https://linux-hardware.org/?probe=939e438746) | Dec 22, 2022 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [828e019570](https://linux-hardware.org/?probe=828e019570) | Dec 22, 2022 |
| HP            | Stream Notebook PC 13       | Notebook    | [b049c64ff7](https://linux-hardware.org/?probe=b049c64ff7) | Dec 22, 2022 |
| Razer         | Blade 15 (2022) - RZ09-0... | Notebook    | [13e778509f](https://linux-hardware.org/?probe=13e778509f) | Dec 22, 2022 |
| Dell          | Latitude 5510               | Notebook    | [b4f32be15b](https://linux-hardware.org/?probe=b4f32be15b) | Dec 22, 2022 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [68a977c101](https://linux-hardware.org/?probe=68a977c101) | Dec 22, 2022 |
| Dell          | 0T10XW A00                  | Desktop     | [b8f7268dcf](https://linux-hardware.org/?probe=b8f7268dcf) | Dec 22, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [fb60e7984c](https://linux-hardware.org/?probe=fb60e7984c) | Dec 21, 2022 |
| ASUSTek       | Strix 15 GL503GE            | Notebook    | [0377cc3170](https://linux-hardware.org/?probe=0377cc3170) | Dec 21, 2022 |
| Dell          | Latitude D820               | Notebook    | [e79993028e](https://linux-hardware.org/?probe=e79993028e) | Dec 21, 2022 |
| Microsoft     | Surface Pro 7               | Tablet      | [6651a137ce](https://linux-hardware.org/?probe=6651a137ce) | Dec 20, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [77bf96f401](https://linux-hardware.org/?probe=77bf96f401) | Dec 20, 2022 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [51c1da3d29](https://linux-hardware.org/?probe=51c1da3d29) | Dec 20, 2022 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [18e982583e](https://linux-hardware.org/?probe=18e982583e) | Dec 20, 2022 |
| Lenovo        | Y70-70 Touch 80DU           | Notebook    | [d5a877b2c6](https://linux-hardware.org/?probe=d5a877b2c6) | Dec 20, 2022 |
| Supermicro    | X9DR3-F                     | Desktop     | [0a1557ab4a](https://linux-hardware.org/?probe=0a1557ab4a) | Dec 20, 2022 |
| Dell          | 0MN1TX A00                  | Desktop     | [f2ae430663](https://linux-hardware.org/?probe=f2ae430663) | Dec 20, 2022 |
| HP            | 18E7                        | Desktop     | [c3b91e80df](https://linux-hardware.org/?probe=c3b91e80df) | Dec 20, 2022 |
| ASUSTek       | Zenbook UP6502ZD_UP6502Z... | Convertible | [6044a618cf](https://linux-hardware.org/?probe=6044a618cf) | Dec 19, 2022 |
| MSI           | H81M-E34                    | Desktop     | [3aa811568d](https://linux-hardware.org/?probe=3aa811568d) | Dec 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [5ba954d88a](https://linux-hardware.org/?probe=5ba954d88a) | Dec 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [318b7c1400](https://linux-hardware.org/?probe=318b7c1400) | Dec 19, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [d5d8eaf2b9](https://linux-hardware.org/?probe=d5d8eaf2b9) | Dec 19, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [a4c5e58eec](https://linux-hardware.org/?probe=a4c5e58eec) | Dec 19, 2022 |
| GIFA Indus... | TM-J3355-2G2L               | Desktop     | [526697a9d0](https://linux-hardware.org/?probe=526697a9d0) | Dec 19, 2022 |
| Gigabyte      | Z790 AORUS MASTER           | Desktop     | [a5f6a25d72](https://linux-hardware.org/?probe=a5f6a25d72) | Dec 19, 2022 |
| Gigabyte      | Z790 AORUS MASTER           | Desktop     | [2b955ca3b3](https://linux-hardware.org/?probe=2b955ca3b3) | Dec 19, 2022 |
| Gigabyte      | X79-UP4                     | Desktop     | [900fd62aaf](https://linux-hardware.org/?probe=900fd62aaf) | Dec 19, 2022 |
| Gigabyte      | X79-UP4                     | Desktop     | [b34721e6cb](https://linux-hardware.org/?probe=b34721e6cb) | Dec 19, 2022 |
| HP            | 85BA 00100                  | All in one  | [a67c97653f](https://linux-hardware.org/?probe=a67c97653f) | Dec 18, 2022 |
| Dell          | XPS 13 9350                 | Notebook    | [d414748117](https://linux-hardware.org/?probe=d414748117) | Dec 18, 2022 |
| Alienware     | 02XRCM A02                  | Desktop     | [ece4e302f1](https://linux-hardware.org/?probe=ece4e302f1) | Dec 18, 2022 |
| EUROCOM       | SCORPIUS 3D                 | Notebook    | [4fdf299276](https://linux-hardware.org/?probe=4fdf299276) | Dec 18, 2022 |
| ASUSTek       | M51BC                       | Desktop     | [78a6f49d22](https://linux-hardware.org/?probe=78a6f49d22) | Dec 18, 2022 |
| Lenovo        | IdeaPad Z570 10249UU        | Notebook    | [2160e3e2c3](https://linux-hardware.org/?probe=2160e3e2c3) | Dec 18, 2022 |
| Lenovo        | Y70-70 Touch 80DU           | Notebook    | [916375929d](https://linux-hardware.org/?probe=916375929d) | Dec 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [071b57d5f6](https://linux-hardware.org/?probe=071b57d5f6) | Dec 18, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [db7b91ac2f](https://linux-hardware.org/?probe=db7b91ac2f) | Dec 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [2a0f5be3bf](https://linux-hardware.org/?probe=2a0f5be3bf) | Dec 17, 2022 |
| ASUSTek       | TUF Z270 MARK 2             | Desktop     | [1bb7d1bffe](https://linux-hardware.org/?probe=1bb7d1bffe) | Dec 17, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [c5adff1ad5](https://linux-hardware.org/?probe=c5adff1ad5) | Dec 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | Notebook    | [2ba98da01d](https://linux-hardware.org/?probe=2ba98da01d) | Dec 16, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [a12207ff89](https://linux-hardware.org/?probe=a12207ff89) | Dec 16, 2022 |
| Google        | Blorb                       | Notebook    | [4134deb94e](https://linux-hardware.org/?probe=4134deb94e) | Dec 16, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [20240705a9](https://linux-hardware.org/?probe=20240705a9) | Dec 16, 2022 |
| ASUSTek       | M51BC                       | Desktop     | [3b744c3d0c](https://linux-hardware.org/?probe=3b744c3d0c) | Dec 16, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [fc8f4624a4](https://linux-hardware.org/?probe=fc8f4624a4) | Dec 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [955de558cb](https://linux-hardware.org/?probe=955de558cb) | Dec 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [e1d8403247](https://linux-hardware.org/?probe=e1d8403247) | Dec 16, 2022 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [8f89f95e37](https://linux-hardware.org/?probe=8f89f95e37) | Dec 16, 2022 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [e4734e61ed](https://linux-hardware.org/?probe=e4734e61ed) | Dec 15, 2022 |
| Dell          | Inspiron 7501               | Notebook    | [1749ece1b3](https://linux-hardware.org/?probe=1749ece1b3) | Dec 15, 2022 |
| MSI           | Z170A PC MATE               | Desktop     | [e6f5c32627](https://linux-hardware.org/?probe=e6f5c32627) | Dec 15, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [2751fbc549](https://linux-hardware.org/?probe=2751fbc549) | Dec 15, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [8968e6816e](https://linux-hardware.org/?probe=8968e6816e) | Dec 15, 2022 |
| HP            | 18E4                        | Desktop     | [26757adc9d](https://linux-hardware.org/?probe=26757adc9d) | Dec 15, 2022 |
| HP            | 18E4                        | Desktop     | [ba6bef79d5](https://linux-hardware.org/?probe=ba6bef79d5) | Dec 15, 2022 |
| MSI           | A88X-G45 GAMING             | Desktop     | [7b92a8398f](https://linux-hardware.org/?probe=7b92a8398f) | Dec 15, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e647deca28](https://linux-hardware.org/?probe=e647deca28) | Dec 14, 2022 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | Notebook    | [36afd57275](https://linux-hardware.org/?probe=36afd57275) | Dec 14, 2022 |
| Dell          | 0R6PCT A01                  | Desktop     | [c0c28e38d0](https://linux-hardware.org/?probe=c0c28e38d0) | Dec 14, 2022 |
| MSI           | GE72VR 6RF                  | Notebook    | [ce2ebf80a1](https://linux-hardware.org/?probe=ce2ebf80a1) | Dec 14, 2022 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [2d1d10e6b9](https://linux-hardware.org/?probe=2d1d10e6b9) | Dec 14, 2022 |
| MSI           | B250 GAMING M3              | Desktop     | [cf050915a5](https://linux-hardware.org/?probe=cf050915a5) | Dec 14, 2022 |
| HP            | 18E4                        | Desktop     | [00f1e4a14a](https://linux-hardware.org/?probe=00f1e4a14a) | Dec 14, 2022 |
| HP            | Pavilion dv7                | Notebook    | [7067714e91](https://linux-hardware.org/?probe=7067714e91) | Dec 14, 2022 |
| ASUSTek       | P8H77-M                     | Desktop     | [32901a2ae5](https://linux-hardware.org/?probe=32901a2ae5) | Dec 13, 2022 |
| Dell          | Latitude E4310              | Notebook    | [dd3e716d03](https://linux-hardware.org/?probe=dd3e716d03) | Dec 13, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [9ddb08e4ae](https://linux-hardware.org/?probe=9ddb08e4ae) | Dec 13, 2022 |
| Dell          | 0X9M3X A04                  | Desktop     | [c3ad967780](https://linux-hardware.org/?probe=c3ad967780) | Dec 13, 2022 |
| Dell          | 0X9M3X A04                  | Desktop     | [a6ca46d45a](https://linux-hardware.org/?probe=a6ca46d45a) | Dec 13, 2022 |
| Dell          | 0X9M3X A04                  | Desktop     | [4059f02137](https://linux-hardware.org/?probe=4059f02137) | Dec 13, 2022 |
| Dell          | 0X9M3X A04                  | Desktop     | [f89f577056](https://linux-hardware.org/?probe=f89f577056) | Dec 13, 2022 |
| Dell          | 0X9M3X A04                  | Desktop     | [667ee69b40](https://linux-hardware.org/?probe=667ee69b40) | Dec 13, 2022 |
| Acer          | Aspire T3-100               | Desktop     | [918ad73eb1](https://linux-hardware.org/?probe=918ad73eb1) | Dec 13, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [e583774bc6](https://linux-hardware.org/?probe=e583774bc6) | Dec 13, 2022 |
| ASRock        | Z390 Phantom Gaming 6       | Desktop     | [51ddf66bff](https://linux-hardware.org/?probe=51ddf66bff) | Dec 12, 2022 |
| Acer          | Nitro AN517-41              | Notebook    | [468d665801](https://linux-hardware.org/?probe=468d665801) | Dec 12, 2022 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [893190593e](https://linux-hardware.org/?probe=893190593e) | Dec 12, 2022 |
| Dell          | Latitude 7430               | Notebook    | [87e9348100](https://linux-hardware.org/?probe=87e9348100) | Dec 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [ca560a74e4](https://linux-hardware.org/?probe=ca560a74e4) | Dec 12, 2022 |
| Apple         | MacBookPro11,2              | Notebook    | [6048cffe66](https://linux-hardware.org/?probe=6048cffe66) | Dec 12, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [9537bff125](https://linux-hardware.org/?probe=9537bff125) | Dec 11, 2022 |
| Dell          | Inspiron 13-5378            | Notebook    | [d8bb31c8c7](https://linux-hardware.org/?probe=d8bb31c8c7) | Dec 11, 2022 |
| Alienware     | 18                          | Notebook    | [707124d216](https://linux-hardware.org/?probe=707124d216) | Dec 11, 2022 |
| Acer          | Aspire A515-55              | Notebook    | [9451601259](https://linux-hardware.org/?probe=9451601259) | Dec 11, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | Desktop     | [51263f4a54](https://linux-hardware.org/?probe=51263f4a54) | Dec 11, 2022 |
| Dell          | Inspiron 7537               | Notebook    | [890f5f6529](https://linux-hardware.org/?probe=890f5f6529) | Dec 11, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [48ccfd51b4](https://linux-hardware.org/?probe=48ccfd51b4) | Dec 11, 2022 |
| ASUSTek       | P5K                         | Desktop     | [7cef6adb1e](https://linux-hardware.org/?probe=7cef6adb1e) | Dec 11, 2022 |
| HP            | 8860 A                      | Desktop     | [c039452bd4](https://linux-hardware.org/?probe=c039452bd4) | Dec 11, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | Desktop     | [1a83431b77](https://linux-hardware.org/?probe=1a83431b77) | Dec 11, 2022 |
| Google        | Candy                       | Notebook    | [12e6466598](https://linux-hardware.org/?probe=12e6466598) | Dec 11, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [be6c0926b1](https://linux-hardware.org/?probe=be6c0926b1) | Dec 10, 2022 |
| Intel         | NUC5i5MYBE H47797-205       | Mini pc     | [20a5e76a25](https://linux-hardware.org/?probe=20a5e76a25) | Dec 10, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [56347e9ad2](https://linux-hardware.org/?probe=56347e9ad2) | Dec 10, 2022 |
| Dell          | G5 5505                     | Notebook    | [60053b5d4b](https://linux-hardware.org/?probe=60053b5d4b) | Dec 10, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [5f3e259429](https://linux-hardware.org/?probe=5f3e259429) | Dec 10, 2022 |
| Gigabyte      | Z97X-SLI-CF                 | Desktop     | [4e829bc252](https://linux-hardware.org/?probe=4e829bc252) | Dec 10, 2022 |
| ASRock        | Z390 Phantom Gaming 6       | Desktop     | [fc58d30c61](https://linux-hardware.org/?probe=fc58d30c61) | Dec 10, 2022 |
| HP            | 18E4                        | Desktop     | [418a689ae5](https://linux-hardware.org/?probe=418a689ae5) | Dec 10, 2022 |
| ASUSTek       | P5K                         | Desktop     | [9db010e6f2](https://linux-hardware.org/?probe=9db010e6f2) | Dec 10, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [febce6b929](https://linux-hardware.org/?probe=febce6b929) | Dec 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [ed7cb7fb48](https://linux-hardware.org/?probe=ed7cb7fb48) | Dec 09, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [2dc32e31b3](https://linux-hardware.org/?probe=2dc32e31b3) | Dec 09, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [e61897fa56](https://linux-hardware.org/?probe=e61897fa56) | Dec 09, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [b2aa17a680](https://linux-hardware.org/?probe=b2aa17a680) | Dec 09, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [416ad70d66](https://linux-hardware.org/?probe=416ad70d66) | Dec 08, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [182502f08c](https://linux-hardware.org/?probe=182502f08c) | Dec 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [aebce6bc5f](https://linux-hardware.org/?probe=aebce6bc5f) | Dec 08, 2022 |
| Lenovo        | Annapurna CRB NOK           | Desktop     | [548e2f6cd0](https://linux-hardware.org/?probe=548e2f6cd0) | Dec 08, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [4c7a6feb83](https://linux-hardware.org/?probe=4c7a6feb83) | Dec 08, 2022 |
| ASUSTek       | P5K                         | Desktop     | [832ef547a1](https://linux-hardware.org/?probe=832ef547a1) | Dec 08, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [91aa6eb03e](https://linux-hardware.org/?probe=91aa6eb03e) | Dec 07, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [963477cf57](https://linux-hardware.org/?probe=963477cf57) | Dec 07, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [57373e16ba](https://linux-hardware.org/?probe=57373e16ba) | Dec 07, 2022 |
| HP            | Laptop 15-dy5xxx            | Notebook    | [12676c4b5b](https://linux-hardware.org/?probe=12676c4b5b) | Dec 07, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [4c5be8eaf3](https://linux-hardware.org/?probe=4c5be8eaf3) | Dec 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [388bcfc8e6](https://linux-hardware.org/?probe=388bcfc8e6) | Dec 07, 2022 |
| Dell          | Latitude 5421               | Notebook    | [f310b80613](https://linux-hardware.org/?probe=f310b80613) | Dec 06, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [6ff5feb92c](https://linux-hardware.org/?probe=6ff5feb92c) | Dec 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [ce36965c1f](https://linux-hardware.org/?probe=ce36965c1f) | Dec 06, 2022 |
| Dell          | Latitude 5421               | Notebook    | [5114034147](https://linux-hardware.org/?probe=5114034147) | Dec 06, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [109d33ef14](https://linux-hardware.org/?probe=109d33ef14) | Dec 06, 2022 |
| MSI           | B150M MORTAR                | Desktop     | [9a87b35e1c](https://linux-hardware.org/?probe=9a87b35e1c) | Dec 06, 2022 |
| MSI           | GE72VR 6RF                  | Notebook    | [23a83a5e8e](https://linux-hardware.org/?probe=23a83a5e8e) | Dec 06, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [c0f26cbe79](https://linux-hardware.org/?probe=c0f26cbe79) | Dec 06, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [54d896b9ed](https://linux-hardware.org/?probe=54d896b9ed) | Dec 06, 2022 |
| HP            | 18E4                        | Desktop     | [e897549786](https://linux-hardware.org/?probe=e897549786) | Dec 06, 2022 |
| ASRock        | Z390 Phantom Gaming 6       | Desktop     | [cda3502c1e](https://linux-hardware.org/?probe=cda3502c1e) | Dec 06, 2022 |
| HP            | 18E4                        | Desktop     | [b12969b62f](https://linux-hardware.org/?probe=b12969b62f) | Dec 06, 2022 |
| HP            | 15                          | Notebook    | [e5a0cdc9de](https://linux-hardware.org/?probe=e5a0cdc9de) | Dec 06, 2022 |
| Lenovo        | 0x36A017AA 31900058 STD     | Desktop     | [ccc212b757](https://linux-hardware.org/?probe=ccc212b757) | Dec 06, 2022 |
| MSI           | GS66 Stealth 11UH           | Notebook    | [b16c3a06ba](https://linux-hardware.org/?probe=b16c3a06ba) | Dec 05, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [1421946e24](https://linux-hardware.org/?probe=1421946e24) | Dec 05, 2022 |
| Apple         | MacBookPro6,1               | Notebook    | [137dd6d1ba](https://linux-hardware.org/?probe=137dd6d1ba) | Dec 05, 2022 |
| ASUSTek       | UL50VT                      | Notebook    | [ff4edb7010](https://linux-hardware.org/?probe=ff4edb7010) | Dec 05, 2022 |
| Dell          | Latitude 7490               | Notebook    | [7377ad6d99](https://linux-hardware.org/?probe=7377ad6d99) | Dec 05, 2022 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [b9d333782f](https://linux-hardware.org/?probe=b9d333782f) | Dec 05, 2022 |
| Dell          | Latitude 7430               | Notebook    | [d153a4f803](https://linux-hardware.org/?probe=d153a4f803) | Dec 05, 2022 |
| HP            | Pavilion dv7                | Notebook    | [901e0c59ce](https://linux-hardware.org/?probe=901e0c59ce) | Dec 05, 2022 |
| HP            | 8158 A01                    | Mini pc     | [f64d5afb00](https://linux-hardware.org/?probe=f64d5afb00) | Dec 05, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [d321abafcd](https://linux-hardware.org/?probe=d321abafcd) | Dec 05, 2022 |
| HP            | Pavilion dv7                | Notebook    | [d02f343be8](https://linux-hardware.org/?probe=d02f343be8) | Dec 05, 2022 |
| Toshiba       | Satellite C650D             | Notebook    | [694d2c9099](https://linux-hardware.org/?probe=694d2c9099) | Dec 05, 2022 |
| System76      | Gazelle                     | Notebook    | [deb2c9b6c9](https://linux-hardware.org/?probe=deb2c9b6c9) | Dec 04, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [8fc8a7552b](https://linux-hardware.org/?probe=8fc8a7552b) | Dec 04, 2022 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [a57440ec11](https://linux-hardware.org/?probe=a57440ec11) | Dec 04, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [dcd57e5862](https://linux-hardware.org/?probe=dcd57e5862) | Dec 04, 2022 |
| ASUSTek       | A8N32-SLI-Deluxe            | Desktop     | [831d9e3a99](https://linux-hardware.org/?probe=831d9e3a99) | Dec 04, 2022 |
| ASUSTek       | A8N32-SLI-Deluxe            | Desktop     | [6ac526e02a](https://linux-hardware.org/?probe=6ac526e02a) | Dec 04, 2022 |
| Dell          | 0DFRFW A01                  | Desktop     | [a3ee070c79](https://linux-hardware.org/?probe=a3ee070c79) | Dec 03, 2022 |
| Dell          | 0DFRFW A01                  | Desktop     | [45543562ff](https://linux-hardware.org/?probe=45543562ff) | Dec 03, 2022 |
| Dell          | Latitude E5450              | Notebook    | [eced7855f2](https://linux-hardware.org/?probe=eced7855f2) | Dec 03, 2022 |
| ASRock        | Z390 Phantom Gaming 6       | Desktop     | [bee1776fbf](https://linux-hardware.org/?probe=bee1776fbf) | Dec 03, 2022 |
| Intel         | NUC6CAYB J23203-404         | Mini pc     | [5d702b9b28](https://linux-hardware.org/?probe=5d702b9b28) | Dec 03, 2022 |
| HP            | 1494                        | Desktop     | [d9dd7b9fc1](https://linux-hardware.org/?probe=d9dd7b9fc1) | Dec 03, 2022 |
| HP            | G62                         | Notebook    | [494d9e65e4](https://linux-hardware.org/?probe=494d9e65e4) | Dec 03, 2022 |
| Pegatron      | 2AC2                        | Desktop     | [29d43d4af8](https://linux-hardware.org/?probe=29d43d4af8) | Dec 03, 2022 |
| HP            | ProBook 4530s               | Notebook    | [f8f94617e8](https://linux-hardware.org/?probe=f8f94617e8) | Dec 03, 2022 |
| Toshiba       | Satellite S50-A             | Notebook    | [ac76869bea](https://linux-hardware.org/?probe=ac76869bea) | Dec 02, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [54e06d37fc](https://linux-hardware.org/?probe=54e06d37fc) | Dec 02, 2022 |
| Intel         | NUC6CAYB J23203-404         | Mini pc     | [a0fe553fc7](https://linux-hardware.org/?probe=a0fe553fc7) | Dec 02, 2022 |
| ASUSTek       | P7P55D PRO                  | Desktop     | [b566591b3c](https://linux-hardware.org/?probe=b566591b3c) | Dec 02, 2022 |
| ASUSTek       | ZenBook UX362FA_UX362FA     | Convertible | [06148b5d6a](https://linux-hardware.org/?probe=06148b5d6a) | Dec 02, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [dfd11598ed](https://linux-hardware.org/?probe=dfd11598ed) | Dec 02, 2022 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [3c05de2bb5](https://linux-hardware.org/?probe=3c05de2bb5) | Dec 02, 2022 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [17e6d4dbb5](https://linux-hardware.org/?probe=17e6d4dbb5) | Dec 02, 2022 |
| Dell          | Latitude E6410              | Notebook    | [92bae2f9d5](https://linux-hardware.org/?probe=92bae2f9d5) | Dec 02, 2022 |
| ASRock        | H97 Pro4                    | Desktop     | [0e0ed0822c](https://linux-hardware.org/?probe=0e0ed0822c) | Dec 02, 2022 |
| ASRock        | H97 Pro4                    | Desktop     | [adeb151478](https://linux-hardware.org/?probe=adeb151478) | Dec 02, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | Notebook    | [253135f8dc](https://linux-hardware.org/?probe=253135f8dc) | Dec 01, 2022 |
| Acer          | Aspire V5-121               | Notebook    | [473cfb46f7](https://linux-hardware.org/?probe=473cfb46f7) | Dec 01, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [5b22a7d584](https://linux-hardware.org/?probe=5b22a7d584) | Dec 01, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [019a1b2e2a](https://linux-hardware.org/?probe=019a1b2e2a) | Dec 01, 2022 |
| Lenovo        | ThinkPad T420 4236V6S       | Notebook    | [5900d34c9a](https://linux-hardware.org/?probe=5900d34c9a) | Dec 01, 2022 |
| HP            | 18E4                        | Desktop     | [b0254c66c7](https://linux-hardware.org/?probe=b0254c66c7) | Dec 01, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [443bd561a5](https://linux-hardware.org/?probe=443bd561a5) | Dec 01, 2022 |
| Pegatron      | 2AC2                        | Desktop     | [3d92c6cbc8](https://linux-hardware.org/?probe=3d92c6cbc8) | Dec 01, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [19c2f41d14](https://linux-hardware.org/?probe=19c2f41d14) | Dec 01, 2022 |
| HP            | EliteBook 820 G3            | Notebook    | [d313455fa8](https://linux-hardware.org/?probe=d313455fa8) | Dec 01, 2022 |
| HP            | EliteBook 820 G3            | Notebook    | [31b9efe771](https://linux-hardware.org/?probe=31b9efe771) | Dec 01, 2022 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [473821d177](https://linux-hardware.org/?probe=473821d177) | Nov 30, 2022 |
| HP            | Pavilion dv5                | Notebook    | [0fc7017b0c](https://linux-hardware.org/?probe=0fc7017b0c) | Nov 30, 2022 |
| Dell          | 0WWJRX A00                  | Desktop     | [83ef480c7d](https://linux-hardware.org/?probe=83ef480c7d) | Nov 30, 2022 |
| ASUSTek       | Z170-E                      | Desktop     | [5e68d23175](https://linux-hardware.org/?probe=5e68d23175) | Nov 30, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [6b21f343c3](https://linux-hardware.org/?probe=6b21f343c3) | Nov 30, 2022 |
| ZOTAC         | ZBOX-MI522NANO/MI542NANO    | Mini pc     | [26a5aa815f](https://linux-hardware.org/?probe=26a5aa815f) | Nov 30, 2022 |
| HP            | Elite x2 1011 G1 Tablet     | Notebook    | [1a00258de3](https://linux-hardware.org/?probe=1a00258de3) | Nov 29, 2022 |
| MSI           | GF75 Thin 9SC               | Notebook    | [50a779c35d](https://linux-hardware.org/?probe=50a779c35d) | Nov 29, 2022 |
| HP            | ProBook 450 G8              | Notebook    | [eec30c7857](https://linux-hardware.org/?probe=eec30c7857) | Nov 29, 2022 |
| ASUSTek       | P8H77-M                     | Desktop     | [4aafb7e858](https://linux-hardware.org/?probe=4aafb7e858) | Nov 29, 2022 |
| ASRock        | Z77 Extreme3                | Desktop     | [e473c1c45c](https://linux-hardware.org/?probe=e473c1c45c) | Nov 29, 2022 |
| Lenovo        | 1031 SBB0J05441 WIN 3305... | Desktop     | [cc75562371](https://linux-hardware.org/?probe=cc75562371) | Nov 29, 2022 |
| Acer          | Aspire A315-22              | Notebook    | [c52689296b](https://linux-hardware.org/?probe=c52689296b) | Nov 29, 2022 |
| Lenovo        | 1031 SBB0J05441 WIN 3305... | Desktop     | [a6ea0d5259](https://linux-hardware.org/?probe=a6ea0d5259) | Nov 29, 2022 |
| ASRock        | B550 Phantom Gaming 4/ac    | Desktop     | [66525e5501](https://linux-hardware.org/?probe=66525e5501) | Nov 29, 2022 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [6d711e74c3](https://linux-hardware.org/?probe=6d711e74c3) | Nov 28, 2022 |
| Dell          | Latitude 7480               | Notebook    | [409c2f27c8](https://linux-hardware.org/?probe=409c2f27c8) | Nov 28, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [f038c3cc67](https://linux-hardware.org/?probe=f038c3cc67) | Nov 28, 2022 |
| HP            | EliteBook Folio 9480m       | Notebook    | [7f9d229259](https://linux-hardware.org/?probe=7f9d229259) | Nov 28, 2022 |
| Dell          | 09WH54 A00                  | Desktop     | [2700be5b4a](https://linux-hardware.org/?probe=2700be5b4a) | Nov 28, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [0149d91a8d](https://linux-hardware.org/?probe=0149d91a8d) | Nov 28, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [03a1a706d1](https://linux-hardware.org/?probe=03a1a706d1) | Nov 28, 2022 |
| HP            | 212B                        | Desktop     | [53471968c2](https://linux-hardware.org/?probe=53471968c2) | Nov 28, 2022 |
| ASUSTek       | P8Z68 DELUXE/GEN3           | Desktop     | [cbd36eefe1](https://linux-hardware.org/?probe=cbd36eefe1) | Nov 27, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [e87a096d85](https://linux-hardware.org/?probe=e87a096d85) | Nov 27, 2022 |
| ASUSTek       | P8Z68 DELUXE/GEN3           | Desktop     | [508e04de6e](https://linux-hardware.org/?probe=508e04de6e) | Nov 27, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [fada18bff7](https://linux-hardware.org/?probe=fada18bff7) | Nov 27, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [d5d04cf0f9](https://linux-hardware.org/?probe=d5d04cf0f9) | Nov 26, 2022 |
| HP            | 18E4                        | Desktop     | [d72a174606](https://linux-hardware.org/?probe=d72a174606) | Nov 26, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [f76927c5ef](https://linux-hardware.org/?probe=f76927c5ef) | Nov 26, 2022 |
| ASUSTek       | T100TA                      | Notebook    | [2734591eb0](https://linux-hardware.org/?probe=2734591eb0) | Nov 26, 2022 |
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [a8a722921c](https://linux-hardware.org/?probe=a8a722921c) | Nov 26, 2022 |
| Acer          | Swift SF314-57              | Notebook    | [ba4ed6c5f4](https://linux-hardware.org/?probe=ba4ed6c5f4) | Nov 26, 2022 |
| Gigabyte      | AORUS 5 SE                  | Notebook    | [d9e1ceb3c1](https://linux-hardware.org/?probe=d9e1ceb3c1) | Nov 26, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [9e465f741d](https://linux-hardware.org/?probe=9e465f741d) | Nov 26, 2022 |
| HP            | 1589                        | Desktop     | [077a89fb54](https://linux-hardware.org/?probe=077a89fb54) | Nov 26, 2022 |
| Dell          | 0VRWRC A00                  | Desktop     | [26bfa13122](https://linux-hardware.org/?probe=26bfa13122) | Nov 25, 2022 |
| Sony          | VGN-NS110E                  | Notebook    | [5ccfd5f230](https://linux-hardware.org/?probe=5ccfd5f230) | Nov 25, 2022 |
| Pegatron      | 2A9A                        | Desktop     | [ee74398a78](https://linux-hardware.org/?probe=ee74398a78) | Nov 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | Notebook    | [682993f58f](https://linux-hardware.org/?probe=682993f58f) | Nov 25, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [83daa0cf15](https://linux-hardware.org/?probe=83daa0cf15) | Nov 25, 2022 |
| Sony          | VGN-NS110E                  | Notebook    | [999e5f4ed6](https://linux-hardware.org/?probe=999e5f4ed6) | Nov 25, 2022 |
| Dell          | 088DT1 A01                  | Desktop     | [eb243079e8](https://linux-hardware.org/?probe=eb243079e8) | Nov 25, 2022 |
| HP            | 18E4                        | Desktop     | [4a4ac150b6](https://linux-hardware.org/?probe=4a4ac150b6) | Nov 24, 2022 |
| ASUSTek       | G73Jh                       | Notebook    | [575f0a8c5a](https://linux-hardware.org/?probe=575f0a8c5a) | Nov 24, 2022 |
| Dell          | 0Y2MRG A00                  | Desktop     | [581cd43952](https://linux-hardware.org/?probe=581cd43952) | Nov 24, 2022 |
| ASUSTek       | Z87-PRO                     | Desktop     | [95ebdc23ea](https://linux-hardware.org/?probe=95ebdc23ea) | Nov 24, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [1986287453](https://linux-hardware.org/?probe=1986287453) | Nov 24, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [344721473a](https://linux-hardware.org/?probe=344721473a) | Nov 23, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [4f6911ae2c](https://linux-hardware.org/?probe=4f6911ae2c) | Nov 23, 2022 |
| Dell          | Latitude E6530              | Notebook    | [71623eedf3](https://linux-hardware.org/?probe=71623eedf3) | Nov 23, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [96e8bf5249](https://linux-hardware.org/?probe=96e8bf5249) | Nov 23, 2022 |
| HP            | 339A                        | Desktop     | [13c1a4b520](https://linux-hardware.org/?probe=13c1a4b520) | Nov 23, 2022 |
| Toshiba       | PORTEGE R930                | Notebook    | [9e5d02ab88](https://linux-hardware.org/?probe=9e5d02ab88) | Nov 23, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [0e778da8b6](https://linux-hardware.org/?probe=0e778da8b6) | Nov 22, 2022 |
| Lenovo        | Y520-15IKBA 80WY            | Notebook    | [c1cccb2b2a](https://linux-hardware.org/?probe=c1cccb2b2a) | Nov 22, 2022 |
| Gigabyte      | AORUS 5 SE                  | Notebook    | [c88614e7f3](https://linux-hardware.org/?probe=c88614e7f3) | Nov 22, 2022 |
| AZW           | BT3 PRO                     | Notebook    | [ee8fc8db42](https://linux-hardware.org/?probe=ee8fc8db42) | Nov 22, 2022 |
| AZW           | BT3 PRO                     | Notebook    | [48047be395](https://linux-hardware.org/?probe=48047be395) | Nov 21, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [5360c65b7a](https://linux-hardware.org/?probe=5360c65b7a) | Nov 21, 2022 |
| Apple         | MacBookPro5,4               | Notebook    | [722165a975](https://linux-hardware.org/?probe=722165a975) | Nov 21, 2022 |
| Lenovo        | Gardenia CRB SDK0J40709 ... | All in one  | [489592e334](https://linux-hardware.org/?probe=489592e334) | Nov 21, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [5c1c053b03](https://linux-hardware.org/?probe=5c1c053b03) | Nov 21, 2022 |
| ASUSTek       | GL552VW                     | Notebook    | [66f37717f6](https://linux-hardware.org/?probe=66f37717f6) | Nov 21, 2022 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [d7f34b8543](https://linux-hardware.org/?probe=d7f34b8543) | Nov 21, 2022 |
| HP            | 18E4                        | Desktop     | [ff954b29c9](https://linux-hardware.org/?probe=ff954b29c9) | Nov 21, 2022 |
| ASRock        | B365M Pro4                  | Desktop     | [0f0d4f70b0](https://linux-hardware.org/?probe=0f0d4f70b0) | Nov 20, 2022 |
| ASUSTek       | M2N-E                       | Desktop     | [150565ed00](https://linux-hardware.org/?probe=150565ed00) | Nov 20, 2022 |
| Toshiba       | TECRA R940                  | Notebook    | [0f231b600d](https://linux-hardware.org/?probe=0f231b600d) | Nov 20, 2022 |
| Dell          | Latitude 5285               | Notebook    | [145341899a](https://linux-hardware.org/?probe=145341899a) | Nov 20, 2022 |
| HP            | ZBook 15 G4                 | Notebook    | [ad20223c29](https://linux-hardware.org/?probe=ad20223c29) | Nov 20, 2022 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [a890ae6d6c](https://linux-hardware.org/?probe=a890ae6d6c) | Nov 20, 2022 |
| Dell          | 0C522T A01                  | Desktop     | [7a475c6f79](https://linux-hardware.org/?probe=7a475c6f79) | Nov 19, 2022 |
| Acer          | Aspire A317-51              | Notebook    | [43c8f9b08b](https://linux-hardware.org/?probe=43c8f9b08b) | Nov 19, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [d4bb2f3867](https://linux-hardware.org/?probe=d4bb2f3867) | Nov 19, 2022 |
| Acer          | Aspire A317-51              | Notebook    | [a4a3dabbb4](https://linux-hardware.org/?probe=a4a3dabbb4) | Nov 19, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [7ac338ce0d](https://linux-hardware.org/?probe=7ac338ce0d) | Nov 19, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [50bd30f30d](https://linux-hardware.org/?probe=50bd30f30d) | Nov 19, 2022 |
| Lenovo        | ThinkPad T480 20L6S09E00    | Notebook    | [cd7fb0289f](https://linux-hardware.org/?probe=cd7fb0289f) | Nov 19, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [6fb901efa3](https://linux-hardware.org/?probe=6fb901efa3) | Nov 19, 2022 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [ea98e803d1](https://linux-hardware.org/?probe=ea98e803d1) | Nov 18, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [57c6327e27](https://linux-hardware.org/?probe=57c6327e27) | Nov 18, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [d1d9ddf9f3](https://linux-hardware.org/?probe=d1d9ddf9f3) | Nov 18, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [da04bee118](https://linux-hardware.org/?probe=da04bee118) | Nov 18, 2022 |
| ASUSTek       | P8H77-M LE                  | Desktop     | [42f0e4b33e](https://linux-hardware.org/?probe=42f0e4b33e) | Nov 18, 2022 |
| ASUSTek       | PRIME H370-A                | Desktop     | [0c4442c160](https://linux-hardware.org/?probe=0c4442c160) | Nov 18, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [af5361313b](https://linux-hardware.org/?probe=af5361313b) | Nov 17, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [078e04eb73](https://linux-hardware.org/?probe=078e04eb73) | Nov 17, 2022 |
| Alienware     | m17                         | Notebook    | [e3e14a271a](https://linux-hardware.org/?probe=e3e14a271a) | Nov 17, 2022 |
| MSI           | B350M MORTAR                | Desktop     | [f85255857d](https://linux-hardware.org/?probe=f85255857d) | Nov 17, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [01810a4098](https://linux-hardware.org/?probe=01810a4098) | Nov 17, 2022 |
| HP            | 18E4                        | Desktop     | [37dd18c268](https://linux-hardware.org/?probe=37dd18c268) | Nov 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [33f2716179](https://linux-hardware.org/?probe=33f2716179) | Nov 17, 2022 |
| Toshiba       | Satellite A200              | Notebook    | [5648565f20](https://linux-hardware.org/?probe=5648565f20) | Nov 17, 2022 |
| Toshiba       | Satellite A200              | Notebook    | [7c530443f0](https://linux-hardware.org/?probe=7c530443f0) | Nov 17, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [b21e07c887](https://linux-hardware.org/?probe=b21e07c887) | Nov 16, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [39aedb7818](https://linux-hardware.org/?probe=39aedb7818) | Nov 16, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [ba362db69a](https://linux-hardware.org/?probe=ba362db69a) | Nov 16, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [985fb6d758](https://linux-hardware.org/?probe=985fb6d758) | Nov 16, 2022 |
| MSI           | 870-G45                     | Desktop     | [5d5dabd8ac](https://linux-hardware.org/?probe=5d5dabd8ac) | Nov 16, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [d0bcf66bd1](https://linux-hardware.org/?probe=d0bcf66bd1) | Nov 16, 2022 |
| Dell          | Latitude E6520              | Notebook    | [ed6f93342d](https://linux-hardware.org/?probe=ed6f93342d) | Nov 15, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [5e6c94e04c](https://linux-hardware.org/?probe=5e6c94e04c) | Nov 15, 2022 |
| Lenovo        | Gardenia CRB SDK0J40709 ... | All in one  | [4c5b1fed6f](https://linux-hardware.org/?probe=4c5b1fed6f) | Nov 15, 2022 |
| ASUSTek       | PRIME H370-A                | Desktop     | [9a93c5f349](https://linux-hardware.org/?probe=9a93c5f349) | Nov 15, 2022 |
| Alienware     | m17                         | Notebook    | [4140c68e95](https://linux-hardware.org/?probe=4140c68e95) | Nov 15, 2022 |
| Dell          | 0RY007                      | Desktop     | [84453b7c4b](https://linux-hardware.org/?probe=84453b7c4b) | Nov 15, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [5fa04fae9e](https://linux-hardware.org/?probe=5fa04fae9e) | Nov 15, 2022 |
| Dell          | 0RY007                      | Desktop     | [dc49babf5c](https://linux-hardware.org/?probe=dc49babf5c) | Nov 15, 2022 |
| Razer         | Blade Stealth               | Notebook    | [52ac7c7393](https://linux-hardware.org/?probe=52ac7c7393) | Nov 14, 2022 |
| Razer         | Blade Stealth               | Notebook    | [6f8078d5ec](https://linux-hardware.org/?probe=6f8078d5ec) | Nov 14, 2022 |
| Acer          | E1-532P                     | Notebook    | [1e666341f7](https://linux-hardware.org/?probe=1e666341f7) | Nov 14, 2022 |
| Lenovo        | ThinkPad T470p 20J6CTO1W... | Notebook    | [4121297e16](https://linux-hardware.org/?probe=4121297e16) | Nov 14, 2022 |
| ASRock        | Z77 Extreme3                | Desktop     | [1485faa2cc](https://linux-hardware.org/?probe=1485faa2cc) | Nov 14, 2022 |
| ASUSTek       | CM6870                      | Desktop     | [c050452a72](https://linux-hardware.org/?probe=c050452a72) | Nov 14, 2022 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [80cce966ce](https://linux-hardware.org/?probe=80cce966ce) | Nov 14, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [25df2f9dc5](https://linux-hardware.org/?probe=25df2f9dc5) | Nov 14, 2022 |
| ASUSTek       | P8P67 LE                    | Desktop     | [970f0b9990](https://linux-hardware.org/?probe=970f0b9990) | Nov 13, 2022 |
| ReachingTe... | Dream Quest Office 2021     | Mini pc     | [c8b868a9b2](https://linux-hardware.org/?probe=c8b868a9b2) | Nov 13, 2022 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [4788a2a91d](https://linux-hardware.org/?probe=4788a2a91d) | Nov 13, 2022 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [18b42b8ead](https://linux-hardware.org/?probe=18b42b8ead) | Nov 13, 2022 |
| Lenovo        | ThinkPad L490 20Q5CTO1WW    | Notebook    | [575d67b22c](https://linux-hardware.org/?probe=575d67b22c) | Nov 13, 2022 |
| HP            | 18E4                        | Desktop     | [be545cc91f](https://linux-hardware.org/?probe=be545cc91f) | Nov 13, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [2d2cdbb40b](https://linux-hardware.org/?probe=2d2cdbb40b) | Nov 12, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [cedb086e46](https://linux-hardware.org/?probe=cedb086e46) | Nov 12, 2022 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [632037506d](https://linux-hardware.org/?probe=632037506d) | Nov 12, 2022 |
| ASUSTek       | P8H61-M LX PLUS R2.0        | Desktop     | [b042e75495](https://linux-hardware.org/?probe=b042e75495) | Nov 11, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [2d830dc96d](https://linux-hardware.org/?probe=2d830dc96d) | Nov 11, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [8d1eaa5bf0](https://linux-hardware.org/?probe=8d1eaa5bf0) | Nov 10, 2022 |
| Google        | Droid                       | Notebook    | [e73c485f75](https://linux-hardware.org/?probe=e73c485f75) | Nov 10, 2022 |
| Microsoft     | Surface 2                   | Tablet      | [0cab1d9501](https://linux-hardware.org/?probe=0cab1d9501) | Nov 10, 2022 |
| HP            | Victus by Laptop 16-d0xx... | Notebook    | [94c1e12b90](https://linux-hardware.org/?probe=94c1e12b90) | Nov 09, 2022 |
| HP            | Victus by Laptop 16-d0xx... | Notebook    | [431acad421](https://linux-hardware.org/?probe=431acad421) | Nov 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [fba0c1a99c](https://linux-hardware.org/?probe=fba0c1a99c) | Nov 09, 2022 |
| ASRock        | Z77 Extreme3                | Desktop     | [d8638412d9](https://linux-hardware.org/?probe=d8638412d9) | Nov 09, 2022 |
| Google        | Cyan                        | Notebook    | [814cdea7b3](https://linux-hardware.org/?probe=814cdea7b3) | Nov 08, 2022 |
| AZW           | Gemini T34                  | Desktop     | [b8aee41f46](https://linux-hardware.org/?probe=b8aee41f46) | Nov 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [be28c34da3](https://linux-hardware.org/?probe=be28c34da3) | Nov 07, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [f0e91578b7](https://linux-hardware.org/?probe=f0e91578b7) | Nov 07, 2022 |
| Lenovo        | ThinkPad T420 4236V6S       | Notebook    | [a1d8f7bbca](https://linux-hardware.org/?probe=a1d8f7bbca) | Nov 07, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [f18ccfd249](https://linux-hardware.org/?probe=f18ccfd249) | Nov 07, 2022 |
| HP            | ENVY 17                     | Notebook    | [83906ebbfc](https://linux-hardware.org/?probe=83906ebbfc) | Nov 07, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [3febd144a4](https://linux-hardware.org/?probe=3febd144a4) | Nov 07, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [5cee459a0f](https://linux-hardware.org/?probe=5cee459a0f) | Nov 06, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [caf9066e2a](https://linux-hardware.org/?probe=caf9066e2a) | Nov 06, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [d137598aff](https://linux-hardware.org/?probe=d137598aff) | Nov 06, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [4f7462e06e](https://linux-hardware.org/?probe=4f7462e06e) | Nov 05, 2022 |
| ASUSTek       | P8H61-M LE/CSM              | Desktop     | [fb29e83d2d](https://linux-hardware.org/?probe=fb29e83d2d) | Nov 05, 2022 |
| Lenovo        | ThinkCentre M91p 4518RS8    | Desktop     | [00fc5e3a1b](https://linux-hardware.org/?probe=00fc5e3a1b) | Nov 05, 2022 |
| ASRock        | B365M Pro4                  | Desktop     | [f5305c9730](https://linux-hardware.org/?probe=f5305c9730) | Nov 04, 2022 |
| Timi          | RedmiBook Pro 15            | Notebook    | [226d8de9bb](https://linux-hardware.org/?probe=226d8de9bb) | Nov 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [507697b22f](https://linux-hardware.org/?probe=507697b22f) | Nov 04, 2022 |
| HP            | Victus by Laptop 16-d0xx... | Notebook    | [fab8493ac2](https://linux-hardware.org/?probe=fab8493ac2) | Nov 04, 2022 |
| HP            | Victus by Laptop 16-d0xx... | Notebook    | [a2362fefe3](https://linux-hardware.org/?probe=a2362fefe3) | Nov 04, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [6491b1d525](https://linux-hardware.org/?probe=6491b1d525) | Nov 04, 2022 |
| HP            | 18E4                        | Desktop     | [66463ac87d](https://linux-hardware.org/?probe=66463ac87d) | Nov 04, 2022 |
| Dell          | G3 3590                     | Notebook    | [03fec4f4d4](https://linux-hardware.org/?probe=03fec4f4d4) | Nov 04, 2022 |
| ASUSTek       | P8H61-M LX PLUS R2.0        | Desktop     | [423d3158cd](https://linux-hardware.org/?probe=423d3158cd) | Nov 03, 2022 |
| MSI           | 870-G45                     | Desktop     | [671a906cbb](https://linux-hardware.org/?probe=671a906cbb) | Nov 03, 2022 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [ab0a9cd47d](https://linux-hardware.org/?probe=ab0a9cd47d) | Nov 03, 2022 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | Desktop     | [7255a61579](https://linux-hardware.org/?probe=7255a61579) | Nov 03, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [608c7f56e6](https://linux-hardware.org/?probe=608c7f56e6) | Nov 03, 2022 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | Desktop     | [953e399168](https://linux-hardware.org/?probe=953e399168) | Nov 03, 2022 |
| ASRock        | Z270 Taichi                 | Desktop     | [60996cd2dc](https://linux-hardware.org/?probe=60996cd2dc) | Nov 02, 2022 |
| HP            | 18E4                        | Desktop     | [1b1339be3d](https://linux-hardware.org/?probe=1b1339be3d) | Nov 02, 2022 |
| ReachingTe... | Dream Quest Office 2021     | Mini pc     | [fde67e1423](https://linux-hardware.org/?probe=fde67e1423) | Nov 02, 2022 |
| Lenovo        | ThinkPad T495 20NKS01W02    | Notebook    | [e4d29df724](https://linux-hardware.org/?probe=e4d29df724) | Nov 02, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | Notebook    | [a65efa454e](https://linux-hardware.org/?probe=a65efa454e) | Nov 01, 2022 |
| Acer          | Aspire X1430                | Desktop     | [f48a8d45d8](https://linux-hardware.org/?probe=f48a8d45d8) | Nov 01, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | Notebook    | [3380dfae20](https://linux-hardware.org/?probe=3380dfae20) | Nov 01, 2022 |
| HP            | 8054                        | Desktop     | [9e1b99d9bb](https://linux-hardware.org/?probe=9e1b99d9bb) | Nov 01, 2022 |
| HP            | Stream Laptop 14-cb1XX      | Notebook    | [18db43ffed](https://linux-hardware.org/?probe=18db43ffed) | Oct 31, 2022 |
| ASUSTek       | Crosshair V Formula         | Desktop     | [c07ddbeb76](https://linux-hardware.org/?probe=c07ddbeb76) | Oct 31, 2022 |
| ASUSTek       | P8H77-M                     | Desktop     | [2ae72e7e22](https://linux-hardware.org/?probe=2ae72e7e22) | Oct 31, 2022 |
| Lenovo        | ThinkPad T420 4180DW1       | Notebook    | [b1e229b9a0](https://linux-hardware.org/?probe=b1e229b9a0) | Oct 31, 2022 |
| Intel         | D33217GKE G76540-201        | Desktop     | [b3403874f4](https://linux-hardware.org/?probe=b3403874f4) | Oct 31, 2022 |
| ReachingTe... | Dream Quest Office 2021     | Mini pc     | [dfdf6532b6](https://linux-hardware.org/?probe=dfdf6532b6) | Oct 31, 2022 |
| ASUSTek       | PRIME Z690-A                | Desktop     | [b1027d78bc](https://linux-hardware.org/?probe=b1027d78bc) | Oct 31, 2022 |
| Toshiba       | Satellite A200              | Notebook    | [296d9a0f38](https://linux-hardware.org/?probe=296d9a0f38) | Oct 31, 2022 |
| Toshiba       | Satellite A200              | Notebook    | [07a165b373](https://linux-hardware.org/?probe=07a165b373) | Oct 31, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [411f4cbf40](https://linux-hardware.org/?probe=411f4cbf40) | Oct 30, 2022 |
| ASUSTek       | PRIME H370-A                | Desktop     | [f7dd154c47](https://linux-hardware.org/?probe=f7dd154c47) | Oct 30, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [54c64976ee](https://linux-hardware.org/?probe=54c64976ee) | Oct 30, 2022 |
| HP            | Pavilion dv7                | Notebook    | [6ff9a469f7](https://linux-hardware.org/?probe=6ff9a469f7) | Oct 30, 2022 |
| Lenovo        | ThinkPad T460 20FMS7DA00    | Notebook    | [861aaf5a99](https://linux-hardware.org/?probe=861aaf5a99) | Oct 29, 2022 |
| HP            | ProLiant ML310e Gen8 v2     | Desktop     | [768d0e85c9](https://linux-hardware.org/?probe=768d0e85c9) | Oct 29, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [ce9df2cf8f](https://linux-hardware.org/?probe=ce9df2cf8f) | Oct 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [77ef1a661c](https://linux-hardware.org/?probe=77ef1a661c) | Oct 29, 2022 |
| ASUSTek       | PRIME A320I-K               | Desktop     | [91f4cd151f](https://linux-hardware.org/?probe=91f4cd151f) | Oct 29, 2022 |
| Dell          | Precision 7520              | Notebook    | [30f6ad7a26](https://linux-hardware.org/?probe=30f6ad7a26) | Oct 29, 2022 |
| Dell          | Precision 7520              | Notebook    | [b81923dbd2](https://linux-hardware.org/?probe=b81923dbd2) | Oct 29, 2022 |
| HP            | 18E4                        | Desktop     | [9d0444b1b8](https://linux-hardware.org/?probe=9d0444b1b8) | Oct 28, 2022 |
| Acer          | Aspire TC-710 V:1.1         | Desktop     | [b9c0f59afa](https://linux-hardware.org/?probe=b9c0f59afa) | Oct 28, 2022 |
| ASRock        | Z270 Killer SLI/ac          | Desktop     | [22ec61d307](https://linux-hardware.org/?probe=22ec61d307) | Oct 28, 2022 |
| HP            | G60                         | Notebook    | [e9af8a9e61](https://linux-hardware.org/?probe=e9af8a9e61) | Oct 28, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [ed6d5efa84](https://linux-hardware.org/?probe=ed6d5efa84) | Oct 28, 2022 |
| ASRock        | X570 Taichi                 | Desktop     | [967f52e510](https://linux-hardware.org/?probe=967f52e510) | Oct 28, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [2829b0b18f](https://linux-hardware.org/?probe=2829b0b18f) | Oct 28, 2022 |
| Acer          | AOD257                      | Notebook    | [d3efba72cc](https://linux-hardware.org/?probe=d3efba72cc) | Oct 28, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [6263763f01](https://linux-hardware.org/?probe=6263763f01) | Oct 27, 2022 |
| Acer          | AOD257                      | Notebook    | [c399f9db2b](https://linux-hardware.org/?probe=c399f9db2b) | Oct 27, 2022 |
| Apple         | MacBookAir5,2               | Notebook    | [f3c9ea3e12](https://linux-hardware.org/?probe=f3c9ea3e12) | Oct 27, 2022 |
| Sun Micros... | ASSY,MOTHERBOARD,X4170 5... | Server      | [ddfefe06a3](https://linux-hardware.org/?probe=ddfefe06a3) | Oct 27, 2022 |
| Oracle        | ASSY,MOTHERBOARD,1U         | Server      | [fec3d1a36e](https://linux-hardware.org/?probe=fec3d1a36e) | Oct 27, 2022 |
| Oracle        | ASSY,MB,X4-2, 1U            | Server      | [4622ac730a](https://linux-hardware.org/?probe=4622ac730a) | Oct 26, 2022 |
| Gigabyte      | GA-990FXA-UD5               | Desktop     | [6faf6b40b1](https://linux-hardware.org/?probe=6faf6b40b1) | Oct 26, 2022 |
| Dell          | Precision 5570              | Notebook    | [67d7b55dab](https://linux-hardware.org/?probe=67d7b55dab) | Oct 26, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [c19eaa0502](https://linux-hardware.org/?probe=c19eaa0502) | Oct 26, 2022 |
| Alienware     | 0PGRP5 A02                  | Desktop     | [126f440ca7](https://linux-hardware.org/?probe=126f440ca7) | Oct 26, 2022 |
| ASUSTek       | UX430UAR                    | Notebook    | [07d56a833e](https://linux-hardware.org/?probe=07d56a833e) | Oct 25, 2022 |
| Panasonic     | CFSX4-1                     | Notebook    | [2ddae6e0e1](https://linux-hardware.org/?probe=2ddae6e0e1) | Oct 25, 2022 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [68aeedffa7](https://linux-hardware.org/?probe=68aeedffa7) | Oct 24, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [927bfd543c](https://linux-hardware.org/?probe=927bfd543c) | Oct 24, 2022 |
| Acer          | TravelMate B311-31          | Notebook    | [010dd1e876](https://linux-hardware.org/?probe=010dd1e876) | Oct 24, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [ce143b473f](https://linux-hardware.org/?probe=ce143b473f) | Oct 24, 2022 |
| ASRock        | Z97 Anniversary             | Desktop     | [9c94714d56](https://linux-hardware.org/?probe=9c94714d56) | Oct 24, 2022 |
| Alienware     | 18                          | Notebook    | [11e8831b9d](https://linux-hardware.org/?probe=11e8831b9d) | Oct 24, 2022 |
| Alienware     | 18                          | Notebook    | [86eb347494](https://linux-hardware.org/?probe=86eb347494) | Oct 24, 2022 |
| MSI           | B350M MORTAR                | Desktop     | [9312be9510](https://linux-hardware.org/?probe=9312be9510) | Oct 23, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [04ea0c7dd2](https://linux-hardware.org/?probe=04ea0c7dd2) | Oct 23, 2022 |
| Lenovo        | ThinkCentre A57 9851CDF     | Desktop     | [8910fecc7d](https://linux-hardware.org/?probe=8910fecc7d) | Oct 23, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [33bef6bb6f](https://linux-hardware.org/?probe=33bef6bb6f) | Oct 23, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [da114c9e74](https://linux-hardware.org/?probe=da114c9e74) | Oct 23, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [3d217d0a43](https://linux-hardware.org/?probe=3d217d0a43) | Oct 23, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [77bbf74390](https://linux-hardware.org/?probe=77bbf74390) | Oct 22, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [acbf2e94c1](https://linux-hardware.org/?probe=acbf2e94c1) | Oct 22, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [32a9b1de4f](https://linux-hardware.org/?probe=32a9b1de4f) | Oct 22, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [66fae864f2](https://linux-hardware.org/?probe=66fae864f2) | Oct 22, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [2a02bdc30d](https://linux-hardware.org/?probe=2a02bdc30d) | Oct 22, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [eaff8befe8](https://linux-hardware.org/?probe=eaff8befe8) | Oct 22, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [b2cc208474](https://linux-hardware.org/?probe=b2cc208474) | Oct 22, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [9042357a86](https://linux-hardware.org/?probe=9042357a86) | Oct 22, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [9f293160d5](https://linux-hardware.org/?probe=9f293160d5) | Oct 22, 2022 |
| Sony          | VPCEH3QFX                   | Notebook    | [def39e1ddd](https://linux-hardware.org/?probe=def39e1ddd) | Oct 21, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Canada/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 806       | 14.85%  |
| Ubuntu 18.04        | 422       | 7.77%   |
| Ubuntu 22.04        | 219       | 4.03%   |
| OpenMandriva 4.2    | 116       | 2.14%   |
| OpenMandriva 4.3    | 109       | 2.01%   |
| Linux Mint 20.3     | 108       | 1.99%   |
| Debian 11           | 105       | 1.93%   |
| Pop!_OS 22.04       | 102       | 1.88%   |
| KDE neon 20.04      | 100       | 1.84%   |
| Xubuntu 20.04       | 95        | 1.75%   |
| Zorin 16            | 93        | 1.71%   |
| Manjaro             | 93        | 1.71%   |
| Pop!_OS 20.04       | 88        | 1.62%   |
| Pop!_OS 21.04       | 84        | 1.55%   |
| Arch                | 80        | 1.47%   |
| Linux Mint 20.1     | 78        | 1.44%   |
| Linux Mint 19.3     | 76        | 1.4%    |
| Arch Rolling        | 73        | 1.34%   |
| Ubuntu 19.10        | 71        | 1.31%   |
| Zorin 15            | 69        | 1.27%   |
| Ubuntu 21.10        | 69        | 1.27%   |
| Fedora 35           | 68        | 1.25%   |
| Ubuntu 20.10        | 66        | 1.22%   |
| Pop!_OS 20.10       | 65        | 1.2%    |
| Linux Mint 20.2     | 64        | 1.18%   |
| Fedora 33           | 64        | 1.18%   |
| ArcoLinux Rolling   | 64        | 1.18%   |
| OpenMandriva 23.01  | 61        | 1.12%   |
| Linux Mint 20       | 59        | 1.09%   |
| Fedora 32           | 56        | 1.03%   |
| Ubuntu 21.04        | 53        | 0.98%   |
| Fedora 34           | 50        | 0.92%   |
| Ubuntu 19.04        | 48        | 0.88%   |
| Pop!_OS 21.10       | 48        | 0.88%   |
| Fedora 37           | 48        | 0.88%   |
| Fedora 36           | 48        | 0.88%   |
| Linux Mint 21       | 45        | 0.83%   |
| Ubuntu 22.10        | 37        | 0.68%   |
| EndeavourOS Rolling | 34        | 0.63%   |
| Fedora 31           | 33        | 0.61%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1758      | 34.07%  |
| Linux Mint    | 468       | 9.07%   |
| Pop!_OS       | 372       | 7.21%   |
| Fedora        | 343       | 6.65%   |
| OpenMandriva  | 316       | 6.12%   |
| Manjaro       | 200       | 3.88%   |
| Debian        | 177       | 3.43%   |
| Zorin         | 171       | 3.31%   |
| Arch          | 148       | 2.87%   |
| Xubuntu       | 145       | 2.81%   |
| KDE neon      | 123       | 2.38%   |
| Kubuntu       | 85        | 1.65%   |
| ROSA          | 76        | 1.47%   |
| ArcoLinux     | 68        | 1.32%   |
| Gentoo        | 49        | 0.95%   |
| Elementary    | 45        | 0.87%   |
| openSUSE      | 38        | 0.74%   |
| EndeavourOS   | 38        | 0.74%   |
| Lubuntu       | 36        | 0.7%    |
| Endless       | 35        | 0.68%   |
| SteamOS       | 31        | 0.6%    |
| Ubuntu MATE   | 30        | 0.58%   |
| Clear Linux   | 28        | 0.54%   |
| CentOS        | 28        | 0.54%   |
| BlackPanther  | 28        | 0.54%   |
| Ubuntu Unity  | 26        | 0.5%    |
| Kali          | 25        | 0.48%   |
| LMDE          | 22        | 0.43%   |
| Ubuntu Budgie | 21        | 0.41%   |
| MX            | 17        | 0.33%   |
| Garuda Linux  | 15        | 0.29%   |
| Nobara        | 12        | 0.23%   |
| Peppermint    | 11        | 0.21%   |
| LinuxFX       | 11        | 0.21%   |
| Alpine        | 9         | 0.17%   |
| RHEL          | 8         | 0.16%   |
| Parrot        | 8         | 0.16%   |
| Rocky Linux   | 7         | 0.14%   |
| Reborn OS     | 7         | 0.14%   |
| Raspbian      | 7         | 0.14%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 113       | 1.87%   |
| 5.16.7-desktop-1omv4003  | 103       | 1.7%    |
| 5.4.0-42-generic         | 92        | 1.52%   |
| 5.15.0-56-generic        | 63        | 1.04%   |
| 5.11.0-27-generic        | 59        | 0.98%   |
| 6.1.1-desktop-1omv2290   | 55        | 0.91%   |
| 5.4.0-58-generic         | 53        | 0.88%   |
| 5.15.0-58-generic        | 52        | 0.86%   |
| 5.4.0-48-generic         | 50        | 0.83%   |
| 5.3.0-40-generic         | 50        | 0.83%   |
| 5.15.0-52-generic        | 45        | 0.74%   |
| 5.4.0-52-generic         | 44        | 0.73%   |
| 5.4.0-29-generic         | 43        | 0.71%   |
| 5.8.0-7630-generic       | 42        | 0.7%    |
| 5.11.0-40-generic        | 42        | 0.7%    |
| 5.4.0-40-generic         | 38        | 0.63%   |
| 5.0.0-37-generic         | 38        | 0.63%   |
| 5.4.0-26-generic         | 36        | 0.6%    |
| 5.13.0-39-generic        | 36        | 0.6%    |
| 5.4.0-54-generic         | 35        | 0.58%   |
| 5.3.0-46-generic         | 35        | 0.58%   |
| 5.15.0-48-generic        | 35        | 0.58%   |
| 5.15.0-47-generic        | 33        | 0.55%   |
| 5.15.0-41-generic        | 33        | 0.55%   |
| 5.11.0-7620-generic      | 33        | 0.55%   |
| 5.4.0-37-generic         | 32        | 0.53%   |
| 5.8.0-50-generic         | 31        | 0.51%   |
| 5.4.0-66-generic         | 30        | 0.5%    |
| 5.4.0-45-generic         | 29        | 0.48%   |
| 5.15.0-46-generic        | 29        | 0.48%   |
| 5.4.0-47-generic         | 27        | 0.45%   |
| 5.11.0-38-generic        | 27        | 0.45%   |
| 5.4.0-91-generic         | 26        | 0.43%   |
| 5.4.0-7634-generic       | 26        | 0.43%   |
| 5.4.0-56-generic         | 26        | 0.43%   |
| 5.4.0-33-generic         | 26        | 0.43%   |
| 5.3.0-42-generic         | 26        | 0.43%   |
| 5.8.0-59-generic         | 25        | 0.41%   |
| 5.8.0-44-generic         | 25        | 0.41%   |
| 5.15.0-53-generic        | 25        | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 1063      | 18.85%  |
| 5.15.0  | 409       | 7.25%   |
| 5.11.0  | 352       | 6.24%   |
| 5.8.0   | 337       | 5.98%   |
| 4.15.0  | 321       | 5.69%   |
| 5.13.0  | 309       | 5.48%   |
| 5.3.0   | 272       | 4.82%   |
| 5.0.0   | 151       | 2.68%   |
| 5.10.14 | 115       | 2.04%   |
| 5.10.0  | 114       | 2.02%   |
| 4.18.0  | 109       | 1.93%   |
| 5.16.7  | 105       | 1.86%   |
| 5.19.0  | 80        | 1.42%   |
| 6.1.1   | 63        | 1.12%   |
| 4.19.0  | 43        | 0.76%   |
| 6.0.12  | 28        | 0.5%    |
| 6.0.6   | 26        | 0.46%   |
| 5.17.5  | 26        | 0.46%   |
| 5.14.0  | 26        | 0.46%   |
| 5.15.5  | 23        | 0.41%   |
| 4.18.16 | 23        | 0.41%   |
| 6.0.0   | 22        | 0.39%   |
| 4.9.20  | 20        | 0.35%   |
| 4.4.0   | 18        | 0.32%   |
| 4.9.60  | 17        | 0.3%    |
| 5.18.0  | 15        | 0.27%   |
| 5.16.0  | 15        | 0.27%   |
| 5.15.11 | 15        | 0.27%   |
| 5.12.4  | 15        | 0.27%   |
| 5.9.16  | 14        | 0.25%   |
| 5.9.11  | 14        | 0.25%   |
| 5.17.9  | 14        | 0.25%   |
| 5.7.0   | 13        | 0.23%   |
| 3.10.0  | 13        | 0.23%   |
| 5.18.12 | 12        | 0.21%   |
| 5.17.0  | 12        | 0.21%   |
| 5.16.13 | 12        | 0.21%   |
| 5.16.11 | 12        | 0.21%   |
| 5.15.15 | 12        | 0.21%   |
| 5.11.12 | 12        | 0.21%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 1153      | 20.8%   |
| 5.15    | 587       | 10.59%  |
| 5.8     | 431       | 7.77%   |
| 5.11    | 407       | 7.34%   |
| 5.13    | 364       | 6.57%   |
| 5.10    | 334       | 6.02%   |
| 4.15    | 322       | 5.81%   |
| 5.3     | 293       | 5.28%   |
| 5.16    | 210       | 3.79%   |
| 5.0     | 160       | 2.89%   |
| 6.0     | 140       | 2.53%   |
| 5.19    | 138       | 2.49%   |
| 4.18    | 132       | 2.38%   |
| 6.1     | 121       | 2.18%   |
| 5.17    | 97        | 1.75%   |
| 5.9     | 84        | 1.52%   |
| 5.14    | 80        | 1.44%   |
| 5.18    | 74        | 1.33%   |
| 5.12    | 71        | 1.28%   |
| 4.9     | 65        | 1.17%   |
| 5.6     | 60        | 1.08%   |
| 4.19    | 58        | 1.05%   |
| 5.7     | 51        | 0.92%   |
| 5.5     | 29        | 0.52%   |
| 4.4     | 22        | 0.4%    |
| 3.10    | 16        | 0.29%   |
| 5.2     | 11        | 0.2%    |
| 4.1     | 6         | 0.11%   |
| 4.13    | 5         | 0.09%   |
| 5.1     | 4         | 0.07%   |
| 4.14    | 3         | 0.05%   |
| 6.2     | 2         | 0.04%   |
| 4.8     | 2         | 0.04%   |
| 4.20    | 2         | 0.04%   |
| 4.16    | 2         | 0.04%   |
| 4.12    | 2         | 0.04%   |
| Unknown | 2         | 0.04%   |
| 5       | 1         | 0.02%   |
| 4.17    | 1         | 0.02%   |
| 4.11    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 4772      | 96.52%  |
| i686    | 114       | 2.31%   |
| aarch64 | 35        | 0.71%   |
| armv7l  | 19        | 0.38%   |
| mips64  | 2         | 0.04%   |
| armv8l  | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| GNOME                | 2293      | 44.14%  |
| KDE5                 | 785       | 15.11%  |
| Unknown              | 699       | 13.46%  |
| X-Cinnamon           | 372       | 7.16%   |
| XFCE                 | 365       | 7.03%   |
| KDE                  | 146       | 2.81%   |
| MATE                 | 117       | 2.25%   |
| Cinnamon             | 65        | 1.25%   |
| KDE4                 | 57        | 1.1%    |
| Pantheon             | 43        | 0.83%   |
| LXQt                 | 43        | 0.83%   |
| i3                   | 35        | 0.67%   |
| Budgie               | 33        | 0.64%   |
| Unity                | 29        | 0.56%   |
| LXDE                 | 28        | 0.54%   |
| GNOME Flashback      | 18        | 0.35%   |
| Deepin               | 13        | 0.25%   |
| GNOME Classic        | 8         | 0.15%   |
| DWM                  | 7         | 0.13%   |
| qtile                | 6         | 0.12%   |
| awesome              | 6         | 0.12%   |
| sway                 | 4         | 0.08%   |
| Openbox              | 4         | 0.08%   |
| Enlightenment        | 4         | 0.08%   |
| xmonad               | 3         | 0.06%   |
| wmaker-common        | 1         | 0.02%   |
| ubuntustudio         | 1         | 0.02%   |
| trinity              | 1         | 0.02%   |
| swayLANG=en_CA.UTF-8 | 1         | 0.02%   |
| spectrwm             | 1         | 0.02%   |
| river                | 1         | 0.02%   |
| Lubuntu              | 1         | 0.02%   |
| lightdm-xsession     | 1         | 0.02%   |
| LeftWM               | 1         | 0.02%   |
| Hyprland             | 1         | 0.02%   |
| chadwm               | 1         | 0.02%   |
| bspwm                | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 3960      | 77.75%  |
| Wayland | 659       | 12.94%  |
| Unknown | 351       | 6.89%   |
| Tty     | 118       | 2.32%   |
| Web     | 5         | 0.1%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2863      | 55.54%  |
| SDDM    | 680       | 13.19%  |
| GDM     | 542       | 10.51%  |
| GDM3    | 454       | 8.81%   |
| LightDM | 392       | 7.6%    |
| TDM     | 142       | 2.75%   |
| KDM     | 51        | 0.99%   |
| XDM     | 13        | 0.25%   |
| SLiM    | 7         | 0.14%   |
| Ly      | 5         | 0.1%    |
| LXDM    | 3         | 0.06%   |
| GREETD  | 2         | 0.04%   |
| MDM     | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_CA      | 2617      | 51.09%  |
| en_US      | 1325      | 25.87%  |
| Unknown    | 574       | 11.21%  |
| fr_CA      | 350       | 6.83%   |
| C          | 110       | 2.15%   |
| fr_FR      | 49        | 0.96%   |
| en_GB      | 30        | 0.59%   |
| POSIX      | 8         | 0.16%   |
| en_AU      | 8         | 0.16%   |
| zh_CN      | 4         | 0.08%   |
| pt_BR      | 4         | 0.08%   |
| es_ES      | 4         | 0.08%   |
| en_IN      | 4         | 0.08%   |
| C.UTF8     | 4         | 0.08%   |
| uk_UA      | 3         | 0.06%   |
| ru_RU      | 3         | 0.06%   |
| de_DE      | 3         | 0.06%   |
| zh_TW      | 2         | 0.04%   |
| pl_PL      | 2         | 0.04%   |
| pa_IN      | 2         | 0.04%   |
| ro_RO      | 1         | 0.02%   |
| nan_TW     | 1         | 0.02%   |
| iu_CA      | 1         | 0.02%   |
| hu_HU      | 1         | 0.02%   |
| hr_HR      | 1         | 0.02%   |
| ga_IE      | 1         | 0.02%   |
| es_CL      | 1         | 0.02%   |
| es_BO      | 1         | 0.02%   |
| en_ZM      | 1         | 0.02%   |
| en_ZA      | 1         | 0.02%   |
| en_US.UTF8 | 1         | 0.02%   |
| en_NZ      | 1         | 0.02%   |
| en_IE      | 1         | 0.02%   |
| en_FI      | 1         | 0.02%   |
| de_CH      | 1         | 0.02%   |
| co_FR      | 1         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2770      | 54.64%  |
| EFI  | 2300      | 45.36%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 3864      | 76.14%  |
| Btrfs   | 426       | 8.39%   |
| Overlay | 421       | 8.3%    |
| Unknown | 177       | 3.49%   |
| Xfs     | 85        | 1.67%   |
| Zfs     | 50        | 0.99%   |
| Ext2    | 19        | 0.37%   |
| Ext3    | 10        | 0.2%    |
| Aufs    | 8         | 0.16%   |
| F2fs    | 7         | 0.14%   |
| Tmpfs   | 5         | 0.1%    |
| Jfs     | 2         | 0.04%   |
| XXX4    | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2954      | 58.25%  |
| GPT     | 1605      | 31.65%  |
| MBR     | 512       | 10.1%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4237      | 83.8%   |
| Yes       | 819       | 16.2%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3675      | 72.92%  |
| Yes       | 1365      | 27.08%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 920       | 18.63%  |
| Dell                    | 733       | 14.84%  |
| Lenovo                  | 646       | 13.08%  |
| Hewlett-Packard         | 616       | 12.47%  |
| Acer                    | 370       | 7.49%   |
| Gigabyte Technology     | 301       | 6.1%    |
| MSI                     | 300       | 6.08%   |
| Apple                   | 174       | 3.52%   |
| ASRock                  | 128       | 2.59%   |
| Toshiba                 | 97        | 1.96%   |
| Intel                   | 73        | 1.48%   |
| Alienware               | 36        | 0.73%   |
| Raspberry Pi Foundation | 35        | 0.71%   |
| Unknown                 | 33        | 0.67%   |
| Sony                    | 32        | 0.65%   |
| Pegatron                | 29        | 0.59%   |
| Gateway                 | 28        | 0.57%   |
| Supermicro              | 27        | 0.55%   |
| Microsoft               | 27        | 0.55%   |
| Valve                   | 26        | 0.53%   |
| Foxconn                 | 26        | 0.53%   |
| Samsung Electronics     | 25        | 0.51%   |
| Google                  | 25        | 0.51%   |
| System76                | 18        | 0.36%   |
| Panasonic               | 17        | 0.34%   |
| ECS                     | 10        | 0.2%    |
| Biostar                 | 10        | 0.2%    |
| ZOTAC                   | 9         | 0.18%   |
| AZW                     | 9         | 0.18%   |
| Razer                   | 8         | 0.16%   |
| Fujitsu                 | 7         | 0.14%   |
| Notebook                | 5         | 0.1%    |
| HUAWEI                  | 5         | 0.1%    |
| eMachines               | 5         | 0.1%    |
| ASRockRack              | 5         | 0.1%    |
| AMI                     | 5         | 0.1%    |
| TYAN Computer           | 4         | 0.08%   |
| LG Electronics          | 4         | 0.08%   |
| IBM                     | 4         | 0.08%   |
| Fanless Mini PC         | 4         | 0.08%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| ASUS All Series                    | 58        | 1.17%   |
| Unknown                            | 44        | 0.89%   |
| Valve Jupiter                      | 26        | 0.53%   |
| HP Notebook                        | 22        | 0.45%   |
| ASUS TUF Gaming X570-PLUS          | 19        | 0.38%   |
| HP Pavilion g6                     | 18        | 0.36%   |
| Acer Aspire A315-21                | 15        | 0.3%    |
| MSI MS-7C02                        | 13        | 0.26%   |
| Dell XPS 15 7590                   | 13        | 0.26%   |
| Dell OptiPlex 790                  | 13        | 0.26%   |
| Dell Latitude E6410                | 13        | 0.26%   |
| ASUS PRIME B450M-A                 | 13        | 0.26%   |
| MSI MS-7C37                        | 12        | 0.24%   |
| HP Z400 Workstation                | 12        | 0.24%   |
| Dell XPS 15 9500                   | 12        | 0.24%   |
| Dell Latitude E6420                | 12        | 0.24%   |
| RPi Raspberry Pi                   | 11        | 0.22%   |
| HP Pavilion dv6                    | 11        | 0.22%   |
| ASRock B450M Pro4                  | 11        | 0.22%   |
| Apple iMac8,1                      | 11        | 0.22%   |
| HP Pavilion 15                     | 10        | 0.2%    |
| HP EliteBook 8460p                 | 10        | 0.2%    |
| Dell OptiPlex 780                  | 10        | 0.2%    |
| ASUS TP410UAR                      | 10        | 0.2%    |
| ASUS ROG STRIX B450-F GAMING       | 10        | 0.2%    |
| ASUS M5A97 LE R2.0                 | 10        | 0.2%    |
| Apple MacBookPro9,2                | 10        | 0.2%    |
| Apple MacBookPro8,1                | 10        | 0.2%    |
| Apple iMac7,1                      | 10        | 0.2%    |
| RPi Raspberry Pi 4 Model B Rev 1.1 | 9         | 0.18%   |
| MSI MS-7C84                        | 9         | 0.18%   |
| MSI MS-7C56                        | 9         | 0.18%   |
| HP Pavilion Notebook               | 9         | 0.18%   |
| Gigabyte B450 AORUS PRO WIFI       | 9         | 0.18%   |
| Dell OptiPlex 7010                 | 9         | 0.18%   |
| ASUS M5A99FX PRO R2.0              | 9         | 0.18%   |
| Toshiba Satellite A200             | 8         | 0.16%   |
| MSI MS-7C95                        | 8         | 0.16%   |
| MSI MS-7693                        | 8         | 0.16%   |
| HP Compaq Pro 6300 SFF             | 8         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 329       | 6.66%   |
| Acer Aspire         | 291       | 5.89%   |
| Dell Inspiron       | 159       | 3.22%   |
| Dell Latitude       | 156       | 3.16%   |
| Dell XPS            | 132       | 2.67%   |
| HP Pavilion         | 120       | 2.43%   |
| Dell OptiPlex       | 119       | 2.41%   |
| ASUS PRIME          | 107       | 2.17%   |
| Lenovo ThinkCentre  | 102       | 2.07%   |
| ASUS ROG            | 102       | 2.07%   |
| HP Compaq           | 83        | 1.68%   |
| Toshiba Satellite   | 82        | 1.66%   |
| Lenovo IdeaPad      | 79        | 1.6%    |
| HP EliteBook        | 76        | 1.54%   |
| ASUS All            | 58        | 1.17%   |
| ASUS TUF            | 56        | 1.13%   |
| Dell Precision      | 55        | 1.11%   |
| ASUS VivoBook       | 53        | 1.07%   |
| HP Laptop           | 50        | 1.01%   |
| Unknown             | 44        | 0.89%   |
| HP ProBook          | 40        | 0.81%   |
| HP ENVY             | 38        | 0.77%   |
| RPi Raspberry       | 35        | 0.71%   |
| Dell Vostro         | 30        | 0.61%   |
| Microsoft Surface   | 27        | 0.55%   |
| Valve Jupiter       | 26        | 0.53%   |
| Gigabyte X570       | 25        | 0.51%   |
| Dell Studio         | 25        | 0.51%   |
| HP EliteDesk        | 24        | 0.49%   |
| ASUS M5A97          | 23        | 0.47%   |
| HP Notebook         | 22        | 0.45%   |
| ASUS ZenBook        | 22        | 0.45%   |
| Gigabyte B450       | 21        | 0.43%   |
| Lenovo Legion       | 19        | 0.38%   |
| Dell PowerEdge      | 19        | 0.38%   |
| Acer Nitro          | 19        | 0.38%   |
| Lenovo Yoga         | 18        | 0.36%   |
| Lenovo ThinkStation | 18        | 0.36%   |
| ASRock B450M        | 18        | 0.36%   |
| Acer Swift          | 18        | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 436       | 8.83%   |
| 2020    | 427       | 8.65%   |
| 2012    | 426       | 8.63%   |
| 2019    | 416       | 8.42%   |
| 2011    | 414       | 8.38%   |
| 2013    | 357       | 7.23%   |
| 2017    | 320       | 6.48%   |
| 2010    | 293       | 5.93%   |
| 2014    | 283       | 5.73%   |
| 2008    | 245       | 4.96%   |
| 2016    | 229       | 4.64%   |
| 2021    | 224       | 4.54%   |
| 2009    | 216       | 4.37%   |
| 2015    | 209       | 4.23%   |
| 2007    | 160       | 3.24%   |
| 2022    | 144       | 2.92%   |
| 2006    | 67        | 1.36%   |
| Unknown | 41        | 0.83%   |
| 2005    | 22        | 0.45%   |
| 2004    | 6         | 0.12%   |
| 2023    | 3         | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 2304      | 46.66%  |
| Desktop        | 2197      | 44.49%  |
| Convertible    | 138       | 2.79%   |
| All in one     | 94        | 1.9%    |
| Server         | 60        | 1.22%   |
| Mini pc        | 57        | 1.15%   |
| System on chip | 46        | 0.93%   |
| Tablet         | 39        | 0.79%   |
| Phone          | 3         | 0.06%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 4667      | 93.83%  |
| Enabled  | 307       | 6.17%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4898      | 99.17%  |
| Yes  | 41        | 0.83%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 1085      | 21.62%  |
| 4.01-8.0        | 1078      | 21.48%  |
| 8.01-16.0       | 927       | 18.47%  |
| 3.01-4.0        | 784       | 15.62%  |
| 32.01-64.0      | 573       | 11.42%  |
| 1.01-2.0        | 185       | 3.69%   |
| 64.01-256.0     | 165       | 3.29%   |
| 24.01-32.0      | 96        | 1.91%   |
| 2.01-3.0        | 71        | 1.41%   |
| 0.51-1.0        | 36        | 0.72%   |
| More than 256.0 | 8         | 0.16%   |
| 0.01-0.5        | 8         | 0.16%   |
| Unknown         | 2         | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 1942      | 35.13%  |
| 2.01-3.0    | 1339      | 24.22%  |
| 4.01-8.0    | 818       | 14.8%   |
| 3.01-4.0    | 695       | 12.57%  |
| 0.51-1.0    | 352       | 6.37%   |
| 8.01-16.0   | 227       | 4.11%   |
| 0.01-0.5    | 85        | 1.54%   |
| 24.01-32.0  | 22        | 0.4%    |
| 32.01-64.0  | 20        | 0.36%   |
| 16.01-24.0  | 19        | 0.34%   |
| 64.01-256.0 | 5         | 0.09%   |
| Unknown     | 4         | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2882      | 55.94%  |
| 2       | 1217      | 23.62%  |
| 3       | 450       | 8.73%   |
| 4       | 254       | 4.93%   |
| 5       | 136       | 2.64%   |
| 6       | 64        | 1.24%   |
| 0       | 53        | 1.03%   |
| 7       | 38        | 0.74%   |
| 8       | 19        | 0.37%   |
| 9       | 11        | 0.21%   |
| 10      | 8         | 0.16%   |
| 11      | 6         | 0.12%   |
| 12      | 4         | 0.08%   |
| Unknown | 4         | 0.08%   |
| 13      | 3         | 0.06%   |
| 14      | 2         | 0.04%   |
| 16      | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2818      | 56.44%  |
| Yes       | 2175      | 43.56%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4328      | 87.42%  |
| No        | 623       | 12.58%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3667      | 73.66%  |
| No        | 1311      | 26.34%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2809      | 55.96%  |
| No        | 2211      | 44.04%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Canada  | 4938      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City            | Computers | Percent |
|-----------------|-----------|---------|
| Toronto         | 503       | 9.67%   |
| Montreal        | 497       | 9.55%   |
| Vancouver       | 223       | 4.29%   |
| Calgary         | 203       | 3.9%    |
| Ottawa          | 189       | 3.63%   |
| Edmonton        | 166       | 3.19%   |
| Québec         | 109       | 2.09%   |
| Winnipeg        | 100       | 1.92%   |
| Mississauga     | 77        | 1.48%   |
| Victoria        | 73        | 1.4%    |
| Surrey          | 61        | 1.17%   |
| Regina          | 56        | 1.08%   |
| Laval           | 54        | 1.04%   |
| Brampton        | 53        | 1.02%   |
| London          | 52        | 1%      |
| Kitchener       | 50        | 0.96%   |
| Hamilton        | 48        | 0.92%   |
| Saskatoon       | 46        | 0.88%   |
| Burnaby         | 42        | 0.81%   |
| Gatineau        | 41        | 0.79%   |
| Windsor         | 40        | 0.77%   |
| Halifax         | 36        | 0.69%   |
| Oshawa          | 34        | 0.65%   |
| Sherbrooke      | 32        | 0.62%   |
| Kingston        | 31        | 0.6%    |
| Scarborough     | 30        | 0.58%   |
| Richmond Hill   | 29        | 0.56%   |
| Markham         | 28        | 0.54%   |
| Trois-Rivières | 26        | 0.5%    |
| Oakville        | 26        | 0.5%    |
| New Westminster | 26        | 0.5%    |
| Moncton         | 26        | 0.5%    |
| Barrie          | 25        | 0.48%   |
| North Vancouver | 23        | 0.44%   |
| Waterloo        | 22        | 0.42%   |
| Red Deer        | 22        | 0.42%   |
| Kelowna         | 22        | 0.42%   |
| Fredericton     | 21        | 0.4%    |
| Dartmouth       | 21        | 0.4%    |
| Sherwood Park   | 20        | 0.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 1395      | 2304   | 18.49%  |
| Seagate                   | 1353      | 2354   | 17.93%  |
| Samsung Electronics       | 1042      | 1637   | 13.81%  |
| Kingston                  | 467       | 644    | 6.19%   |
| Toshiba                   | 396       | 511    | 5.25%   |
| SanDisk                   | 337       | 424    | 4.47%   |
| Unknown                   | 323       | 439    | 4.28%   |
| Hitachi                   | 263       | 346    | 3.49%   |
| Intel                     | 225       | 342    | 2.98%   |
| Crucial                   | 209       | 288    | 2.77%   |
| A-DATA Technology         | 174       | 230    | 2.31%   |
| SK hynix                  | 157       | 190    | 2.08%   |
| HGST                      | 123       | 160    | 1.63%   |
| Micron Technology         | 76        | 107    | 1.01%   |
| Apple                     | 59        | 75     | 0.78%   |
| Phison                    | 54        | 81     | 0.72%   |
| Fujitsu                   | 43        | 54     | 0.57%   |
| SPCC                      | 41        | 51     | 0.54%   |
| OCZ                       | 38        | 50     | 0.5%    |
| KIOXIA                    | 34        | 39     | 0.45%   |
| Corsair                   | 32        | 39     | 0.42%   |
| China                     | 32        | 36     | 0.42%   |
| Silicon Motion            | 31        | 46     | 0.41%   |
| LITEONIT                  | 28        | 31     | 0.37%   |
| PNY                       | 27        | 40     | 0.36%   |
| ASMT                      | 23        | 28     | 0.3%    |
| Patriot                   | 22        | 26     | 0.29%   |
| Mushkin                   | 22        | 26     | 0.29%   |
| Micron/Crucial Technology | 22        | 35     | 0.29%   |
| LITEON                    | 21        | 23     | 0.28%   |
| Team                      | 20        | 24     | 0.27%   |
| XPG                       | 19        | 28     | 0.25%   |
| JMicron Technology        | 18        | 25     | 0.24%   |
| Phison Electronics        | 17        | 20     | 0.23%   |
| Hewlett-Packard           | 17        | 28     | 0.23%   |
| Unknown                   | 17        | 17     | 0.23%   |
| Maxtor                    | 16        | 22     | 0.21%   |
| SABRENT                   | 14        | 19     | 0.19%   |
| KingFast                  | 14        | 17     | 0.19%   |
| Dogfish                   | 14        | 18     | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD        | 114       | 1.32%   |
| Samsung SSD 850 EVO 250GB              | 83        | 0.96%   |
| Samsung SSD 860 EVO 500GB              | 74        | 0.86%   |
| Seagate ST2000DM008-2FR102 2TB         | 66        | 0.77%   |
| Samsung SSD 850 EVO 500GB              | 61        | 0.71%   |
| Kingston SA400S37120G 120GB SSD        | 61        | 0.71%   |
| Samsung SSD 860 EVO 1TB                | 56        | 0.65%   |
| Samsung NVMe SSD Drive 500GB           | 54        | 0.63%   |
| Kingston SA400S37480G 480GB SSD        | 54        | 0.63%   |
| Unknown MMC Card  32GB                 | 53        | 0.62%   |
| Seagate ST1000DM010-2EP102 1TB         | 52        | 0.6%    |
| SanDisk NVMe SSD Drive 500GB           | 52        | 0.6%    |
| Unknown MMC Card  64GB                 | 49        | 0.57%   |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 48        | 0.56%   |
| Toshiba MQ01ABD100 1TB                 | 48        | 0.56%   |
| Unknown SD/MMC/MS PRO 16GB             | 47        | 0.55%   |
| Seagate ST4000DM004-2CV104 4TB         | 46        | 0.53%   |
| WDC WDS100T2B0A-00SM50 1TB SSD         | 43        | 0.5%    |
| WDC WD10EZEX-08WN4A0 1TB               | 43        | 0.5%    |
| Seagate ST500DM002-1BD142 500GB        | 43        | 0.5%    |
| SanDisk NVMe SSD Drive 1TB             | 43        | 0.5%    |
| Kingston SV300S37A120G 120GB SSD       | 43        | 0.5%    |
| Seagate ST1000LM035-1RK172 1TB         | 42        | 0.49%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 42        | 0.49%   |
| Seagate ST1000LX015-1U7172 1TB         | 41        | 0.48%   |
| Samsung SSD 860 EVO 250GB              | 41        | 0.48%   |
| Seagate ST2000DM001-1ER164 2TB         | 39        | 0.45%   |
| Seagate ST2000DM006-2DM164 2TB         | 38        | 0.44%   |
| Crucial CT1000MX500SSD1 1TB            | 38        | 0.44%   |
| Seagate ST1000DM003-1CH162 1TB         | 37        | 0.43%   |
| Toshiba DT01ACA200 2TB                 | 35        | 0.41%   |
| Seagate ST1000DM003-1ER162 1TB         | 35        | 0.41%   |
| HGST HTS721010A9E630 1TB               | 35        | 0.41%   |
| Seagate Expansion Desk 5TB             | 34        | 0.39%   |
| Seagate Expansion 1TB                  | 33        | 0.38%   |
| Seagate ST3500418AS 500GB              | 31        | 0.36%   |
| Seagate ST31000528AS 1TB               | 29        | 0.34%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 29        | 0.34%   |
| Samsung NVMe SSD Drive 512GB           | 29        | 0.34%   |
| WDC WD20EARS-00MVWB0 2TB               | 28        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1309      | 2260   | 38.91%  |
| WDC                 | 1107      | 1826   | 32.91%  |
| Toshiba             | 320       | 421    | 9.51%   |
| Hitachi             | 263       | 346    | 7.82%   |
| HGST                | 123       | 160    | 3.66%   |
| Samsung Electronics | 53        | 71     | 1.58%   |
| Unknown             | 47        | 60     | 1.4%    |
| Fujitsu             | 43        | 54     | 1.28%   |
| Apple               | 23        | 25     | 0.68%   |
| Maxtor              | 16        | 22     | 0.48%   |
| SABRENT             | 13        | 18     | 0.39%   |
| JMicron Technology  | 11        | 16     | 0.33%   |
| ASMT                | 8         | 11     | 0.24%   |
| Maxone              | 6         | 8      | 0.18%   |
| USB 3.0             | 2         | 6      | 0.06%   |
| Hewlett-Packard     | 2         | 9      | 0.06%   |
| External            | 2         | 2      | 0.06%   |
| DAS                 | 2         | 14     | 0.06%   |
| USB3.0              | 1         | 2      | 0.03%   |
| Quantum             | 1         | 1      | 0.03%   |
| QNAP                | 1         | 6      | 0.03%   |
| Pioneer             | 1         | 1      | 0.03%   |
| PHD 3.0             | 1         | 1      | 0.03%   |
| Maxtor 6            | 1         | 1      | 0.03%   |
| MaxDigital          | 1         | 1      | 0.03%   |
| LaCie               | 1         | 1      | 0.03%   |
| KESU                | 1         | 2      | 0.03%   |
| Generic-            | 1         | 1      | 0.03%   |
| DELLBOSS            | 1         | 1      | 0.03%   |
| ASMT109x            | 1         | 1      | 0.03%   |
| ASMedia             | 1         | 1      | 0.03%   |
| ACASIS              | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 614       | 929    | 25.35%  |
| Kingston            | 403       | 555    | 16.64%  |
| WDC                 | 211       | 296    | 8.71%   |
| Crucial             | 188       | 250    | 7.76%   |
| A-DATA Technology   | 154       | 204    | 6.36%   |
| SanDisk             | 150       | 178    | 6.19%   |
| Intel               | 98        | 131    | 4.05%   |
| Micron Technology   | 49        | 73     | 2.02%   |
| SPCC                | 37        | 47     | 1.53%   |
| OCZ                 | 37        | 46     | 1.53%   |
| China               | 32        | 36     | 1.32%   |
| Seagate             | 31        | 45     | 1.28%   |
| Apple               | 31        | 37     | 1.28%   |
| SK hynix            | 29        | 37     | 1.2%    |
| LITEONIT            | 28        | 31     | 1.16%   |
| PNY                 | 27        | 40     | 1.11%   |
| Toshiba             | 24        | 28     | 0.99%   |
| Patriot             | 22        | 26     | 0.91%   |
| Mushkin             | 20        | 24     | 0.83%   |
| Team                | 19        | 23     | 0.78%   |
| Corsair             | 19        | 22     | 0.78%   |
| LITEON              | 17        | 18     | 0.7%    |
| Dogfish             | 14        | 18     | 0.58%   |
| ASMT                | 13        | 15     | 0.54%   |
| TO Exter            | 10        | 12     | 0.41%   |
| Hewlett-Packard     | 10        | 13     | 0.41%   |
| OWC                 | 8         | 17     | 0.33%   |
| Transcend           | 7         | 8      | 0.29%   |
| NGFF                | 7         | 8      | 0.29%   |
| Lexar               | 7         | 8      | 0.29%   |
| KingDian            | 7         | 7      | 0.29%   |
| KingFast            | 6         | 6      | 0.25%   |
| TCSUNBOW            | 5         | 6      | 0.21%   |
| T-FORCE             | 5         | 5      | 0.21%   |
| WDC WDS             | 4         | 5      | 0.17%   |
| Timetec             | 4         | 8      | 0.17%   |
| KingSpec            | 4         | 6      | 0.17%   |
| Vaseky              | 3         | 4      | 0.12%   |
| TSA                 | 3         | 3      | 0.12%   |
| Super Talent        | 3         | 4      | 0.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2766      | 5350   | 41.83%  |
| SSD     | 2063      | 3301   | 31.2%   |
| NVMe    | 1383      | 2088   | 20.92%  |
| MMC     | 266       | 361    | 4.02%   |
| Unknown | 134       | 183    | 2.03%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3886      | 8185   | 65.18%  |
| NVMe | 1372      | 2064   | 23.01%  |
| SAS  | 438       | 673    | 7.35%   |
| MMC  | 266       | 361    | 4.46%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2801      | 4445   | 52.72%  |
| 0.51-1.0   | 1525      | 2399   | 28.7%   |
| 1.01-2.0   | 506       | 881    | 9.52%   |
| 4.01-10.0  | 181       | 372    | 3.41%   |
| 3.01-4.0   | 159       | 282    | 2.99%   |
| 2.01-3.0   | 131       | 250    | 2.47%   |
| 10.01-20.0 | 10        | 22     | 0.19%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1232      | 23.23%  |
| 251-500        | 1154      | 21.76%  |
| 501-1000       | 813       | 15.33%  |
| 1001-2000      | 439       | 8.28%   |
| 1-20           | 418       | 7.88%   |
| More than 3000 | 379       | 7.15%   |
| 51-100         | 283       | 5.34%   |
| 21-50          | 203       | 3.83%   |
| Unknown        | 195       | 3.68%   |
| 2001-3000      | 188       | 3.54%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2162      | 39.35%  |
| 21-50          | 919       | 16.73%  |
| 101-250        | 619       | 11.27%  |
| 51-100         | 555       | 10.1%   |
| 251-500        | 372       | 6.77%   |
| 501-1000       | 268       | 4.88%   |
| Unknown        | 195       | 3.55%   |
| 1001-2000      | 189       | 3.44%   |
| More than 3000 | 139       | 2.53%   |
| 2001-3000      | 75        | 1.37%   |
| 0              | 1         | 0.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 8         | 9      | 1.75%   |
| Seagate ST500LM000-1EJ162 500GB     | 6         | 6      | 1.32%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 6         | 7      | 1.32%   |
| WDC WD2500HHTZ-04N21V0 250GB        | 5         | 5      | 1.1%    |
| WDC WD20EARS-00MVWB0 2TB            | 5         | 6      | 1.1%    |
| Toshiba MQ01ABD100 1TB              | 5         | 7      | 1.1%    |
| Seagate ST9500420AS 500GB           | 5         | 5      | 1.1%    |
| Seagate ST9500325AS 500GB           | 5         | 5      | 1.1%    |
| Seagate ST500LT012-9WS142 500GB     | 5         | 5      | 1.1%    |
| Seagate ST3500418AS 500GB           | 5         | 6      | 1.1%    |
| Seagate ST31000528AS 1TB            | 5         | 5      | 1.1%    |
| HGST HTS541010A9E680 1TB            | 5         | 5      | 1.1%    |
| WDC WD40EFRX-68WT0N0 4TB            | 4         | 17     | 0.88%   |
| Seagate ST500LM021-1KJ152 500GB     | 4         | 6      | 0.88%   |
| Samsung Electronics SSD 870 EVO 1TB | 4         | 5      | 0.88%   |
| Kingston SV300S37A120G 120GB SSD    | 4         | 6      | 0.88%   |
| Intel SSDSA1M080G2LE 80GB           | 4         | 4      | 0.88%   |
| HGST HTS725050A7E630 500GB          | 4         | 5      | 0.88%   |
| HGST HTS721010A9E630 1TB            | 4         | 4      | 0.88%   |
| HGST HTS545050A7E680 500GB          | 4         | 4      | 0.88%   |
| WDC WD6400AAKS-22A7B2 640GB         | 3         | 3      | 0.66%   |
| WDC WD30EFRX-68EUZN0 3TB            | 3         | 4      | 0.66%   |
| WDC WD10EARX-00N0YB0 1TB            | 3         | 4      | 0.66%   |
| Toshiba MK3261GSYN 320GB            | 3         | 3      | 0.66%   |
| Seagate ST9320325AS 320GB           | 3         | 6      | 0.66%   |
| Seagate ST500LT012-1DG142 500GB     | 3         | 3      | 0.66%   |
| Seagate ST31500341AS 1TB            | 3         | 3      | 0.66%   |
| Seagate ST2000DM001-1CH164 2TB      | 3         | 3      | 0.66%   |
| Seagate ST1000LM035-1RK172 1TB      | 3         | 3      | 0.66%   |
| Seagate ST1000DM003-1ER162 1TB      | 3         | 4      | 0.66%   |
| Hitachi HDS721010CLA332 1TB         | 3         | 3      | 0.66%   |
| Crucial CT1000P1SSD8 1TB            | 3         | 9      | 0.66%   |
| A-DATA Technology SX900 256GB SSD   | 3         | 3      | 0.66%   |
| WDC WD6400AAKS-65Z7B0 640GB         | 2         | 3      | 0.44%   |
| WDC WD5000LPVX-75V0TT0 500GB        | 2         | 2      | 0.44%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 2         | 2      | 0.44%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 2         | 2      | 0.44%   |
| WDC WD20EZRZ-00Z5HB0 2TB            | 2         | 2      | 0.44%   |
| WDC WD20EARS-00J2GB0 2TB            | 2         | 2      | 0.44%   |
| WDC WD10EZEX-08WN4A0 1TB            | 2         | 2      | 0.44%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 141       | 181    | 31.97%  |
| WDC                 | 117       | 157    | 26.53%  |
| Hitachi             | 36        | 37     | 8.16%   |
| Samsung Electronics | 26        | 34     | 5.9%    |
| Toshiba             | 25        | 27     | 5.67%   |
| HGST                | 18        | 19     | 4.08%   |
| Kingston            | 16        | 21     | 3.63%   |
| Intel               | 13        | 14     | 2.95%   |
| Crucial             | 10        | 17     | 2.27%   |
| A-DATA Technology   | 10        | 11     | 2.27%   |
| SK hynix            | 3         | 3      | 0.68%   |
| LITEONIT            | 3         | 3      | 0.68%   |
| Fujitsu             | 3         | 4      | 0.68%   |
| Apple               | 3         | 3      | 0.68%   |
| OCZ                 | 2         | 2      | 0.45%   |
| Mushkin             | 2         | 2      | 0.45%   |
| ASMT                | 2         | 3      | 0.45%   |
| Super Talent        | 1         | 1      | 0.23%   |
| Sandisk             | 1         | 1      | 0.23%   |
| Micron Technology   | 1         | 1      | 0.23%   |
| Maxtor              | 1         | 1      | 0.23%   |
| LITEON              | 1         | 1      | 0.23%   |
| LaCie               | 1         | 1      | 0.23%   |
| Hewlett-Packard     | 1         | 1      | 0.23%   |
| Drevo               | 1         | 1      | 0.23%   |
| DAS                 | 1         | 3      | 0.23%   |
| Corsair             | 1         | 1      | 0.23%   |
| China               | 1         | 1      | 0.23%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 141       | 181    | 39.94%  |
| WDC                 | 117       | 157    | 33.14%  |
| Hitachi             | 36        | 37     | 10.2%   |
| Toshiba             | 24        | 26     | 6.8%    |
| HGST                | 18        | 19     | 5.1%    |
| Samsung Electronics | 8         | 14     | 2.27%   |
| Fujitsu             | 3         | 4      | 0.85%   |
| Apple               | 2         | 2      | 0.57%   |
| Maxtor              | 1         | 1      | 0.28%   |
| LaCie               | 1         | 1      | 0.28%   |
| DAS                 | 1         | 3      | 0.28%   |
| ASMT                | 1         | 2      | 0.28%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 331       | 447    | 78.81%  |
| SSD  | 74        | 82     | 17.62%  |
| NVMe | 15        | 22     | 3.57%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD2003FYYS-18W0B0 2TB         | 1         | 1      | 20%     |
| Samsung Electronics HD502HJ 500GB | 1         | 1      | 20%     |
| LITEON CA3-8D512 512GB            | 1         | 2      | 20%     |
| Intel SSDSA1M160G2HP 160GB        | 1         | 1      | 20%     |
| Hewlett-Packard EF0450FARMV 450GB | 1         | 4      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 20%     |
| Samsung Electronics | 1         | 1      | 20%     |
| LITEON              | 1         | 2      | 20%     |
| Intel               | 1         | 1      | 20%     |
| Hewlett-Packard     | 1         | 4      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 3285      | 7295   | 60.61%  |
| Works    | 1725      | 3428   | 31.83%  |
| Malfunc  | 405       | 551    | 7.47%   |
| Failed   | 5         | 9      | 0.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3179      | 50.3%   |
| AMD                              | 1140      | 18.04%  |
| Samsung Electronics              | 490       | 7.75%   |
| SanDisk                          | 321       | 5.08%   |
| ASMedia Technology               | 144       | 2.28%   |
| SK hynix                         | 124       | 1.96%   |
| Marvell Technology Group         | 124       | 1.96%   |
| Nvidia                           | 114       | 1.8%    |
| JMicron Technology               | 91        | 1.44%   |
| Phison Electronics               | 83        | 1.31%   |
| Kingston Technology Company      | 78        | 1.23%   |
| Toshiba America Info Systems     | 54        | 0.85%   |
| ADATA Technology                 | 46        | 0.73%   |
| Micron/Crucial Technology        | 44        | 0.7%    |
| Silicon Motion                   | 41        | 0.65%   |
| LSI Logic / Symbios Logic        | 38        | 0.6%    |
| KIOXIA                           | 37        | 0.59%   |
| Micron Technology                | 29        | 0.46%   |
| Broadcom / LSI                   | 25        | 0.4%    |
| Silicon Image                    | 15        | 0.24%   |
| Realtek Semiconductor            | 15        | 0.24%   |
| Seagate Technology               | 13        | 0.21%   |
| VIA Technologies                 | 9         | 0.14%   |
| Union Memory (Shenzhen)          | 9         | 0.14%   |
| Lite-On Technology               | 7         | 0.11%   |
| Lenovo                           | 7         | 0.11%   |
| Hewlett-Packard                  | 7         | 0.11%   |
| Apple                            | 6         | 0.09%   |
| INNOGRIT                         | 4         | 0.06%   |
| HighPoint Technologies           | 4         | 0.06%   |
| Adaptec                          | 4         | 0.06%   |
| Solid State Storage Technology   | 3         | 0.05%   |
| Silicon Integrated Systems [SiS] | 3         | 0.05%   |
| Integrated Technology Express    | 3         | 0.05%   |
| Shenzhen Longsys Electronics     | 2         | 0.03%   |
| OCZ Technology Group             | 2         | 0.03%   |
| Yangtze Memory Technologies      | 1         | 0.02%   |
| ULi Electronics                  | 1         | 0.02%   |
| Promise Technology               | 1         | 0.02%   |
| O2 Micro                         | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 749       | 10.04%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 253       | 3.39%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 221       | 2.96%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 204       | 2.74%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 171       | 2.29%   |
| AMD 400 Series Chipset SATA Controller                                         | 165       | 2.21%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 164       | 2.2%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 162       | 2.17%   |
| Intel SATA Controller [RAID mode]                                              | 143       | 1.92%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 137       | 1.84%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 135       | 1.81%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 130       | 1.74%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 114       | 1.53%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 112       | 1.5%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 103       | 1.38%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 96        | 1.29%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 93        | 1.25%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 91        | 1.22%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 87        | 1.17%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 87        | 1.17%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 87        | 1.17%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 81        | 1.09%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 79        | 1.06%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 76        | 1.02%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 75        | 1.01%   |
| Intel Volume Management Device NVMe RAID Controller                            | 75        | 1.01%   |
| AMD 500 Series Chipset SATA Controller                                         | 74        | 0.99%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 73        | 0.98%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 72        | 0.97%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 68        | 0.91%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 67        | 0.9%    |
| Samsung NVMe SSD Controller 980                                                | 62        | 0.83%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 62        | 0.83%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 60        | 0.8%    |
| Intel SSD 660P Series                                                          | 58        | 0.78%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 56        | 0.75%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 49        | 0.66%   |
| SanDisk Non-Volatile memory controller                                         | 48        | 0.64%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 48        | 0.64%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 47        | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 3594      | 56.84%  |
| NVMe | 1388      | 21.95%  |
| IDE  | 793       | 12.54%  |
| RAID | 491       | 7.77%   |
| SAS  | 44        | 0.7%    |
| SCSI | 13        | 0.21%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 3544      | 71.77%  |
| AMD      | 1337      | 27.08%  |
| ARM      | 51        | 1.03%   |
| Unknown  | 5         | 0.1%    |
| QUALCOMM | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz       | 55        | 1.11%   |
| AMD Ryzen 5 3600 6-Core Processor       | 48        | 0.97%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 40        | 0.81%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 40        | 0.81%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 38        | 0.77%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 37        | 0.75%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 35        | 0.71%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 34        | 0.69%   |
| Intel Core i7-6700 CPU @ 3.40GHz        | 34        | 0.69%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 34        | 0.69%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 34        | 0.69%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 33        | 0.67%   |
| ARM Processor                           | 32        | 0.65%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 31        | 0.63%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 30        | 0.61%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 30        | 0.61%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 30        | 0.61%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 28        | 0.57%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 27        | 0.55%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 27        | 0.55%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 27        | 0.55%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 26        | 0.53%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 26        | 0.53%   |
| AMD Custom APU 0405                     | 26        | 0.53%   |
| Intel Core i5-4570 CPU @ 3.20GHz        | 25        | 0.51%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 25        | 0.51%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 25        | 0.51%   |
| AMD Ryzen 5 2600 Six-Core Processor     | 25        | 0.51%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 24        | 0.49%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz   | 24        | 0.49%   |
| Intel Core i7-4770 CPU @ 3.40GHz        | 23        | 0.46%   |
| AMD Ryzen 7 4700U with Radeon Graphics  | 23        | 0.46%   |
| AMD FX-8350 Eight-Core Processor        | 23        | 0.46%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 22        | 0.44%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 21        | 0.42%   |
| Intel Core i7-2600K CPU @ 3.40GHz       | 21        | 0.42%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 21        | 0.42%   |
| Intel Core i7-8700K CPU @ 3.70GHz       | 20        | 0.4%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 20        | 0.4%    |
| Intel Core i7-4790K CPU @ 4.00GHz       | 20        | 0.4%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1043      | 21.09%  |
| Intel Core i7           | 1020      | 20.62%  |
| Other                   | 293       | 5.92%   |
| AMD Ryzen 7             | 249       | 5.03%   |
| AMD Ryzen 5             | 249       | 5.03%   |
| Intel Core i3           | 245       | 4.95%   |
| Intel Core 2 Duo        | 243       | 4.91%   |
| Intel Xeon              | 180       | 3.64%   |
| Intel Celeron           | 149       | 3.01%   |
| AMD FX                  | 103       | 2.08%   |
| AMD Ryzen 9             | 94        | 1.9%    |
| Intel Pentium           | 89        | 1.8%    |
| AMD A6                  | 72        | 1.46%   |
| AMD A10                 | 66        | 1.33%   |
| Intel Core 2 Quad       | 61        | 1.23%   |
| Intel Atom              | 61        | 1.23%   |
| Intel Pentium Dual-Core | 57        | 1.15%   |
| AMD Ryzen 3             | 46        | 0.93%   |
| Intel Core i9           | 43        | 0.87%   |
| AMD A8                  | 41        | 0.83%   |
| AMD Athlon 64 X2        | 40        | 0.81%   |
| Intel Pentium Dual      | 38        | 0.77%   |
| Intel Core 2            | 37        | 0.75%   |
| AMD A4                  | 35        | 0.71%   |
| Intel Genuine           | 22        | 0.44%   |
| AMD Athlon II X2        | 22        | 0.44%   |
| AMD Phenom II X4        | 19        | 0.38%   |
| AMD Phenom II X6        | 18        | 0.36%   |
| AMD E                   | 18        | 0.36%   |
| AMD Phenom              | 17        | 0.34%   |
| Intel Pentium Silver    | 16        | 0.32%   |
| Intel Pentium D         | 16        | 0.32%   |
| Intel Pentium 4         | 15        | 0.3%    |
| AMD Ryzen Threadripper  | 14        | 0.28%   |
| AMD Athlon              | 14        | 0.28%   |
| AMD E2                  | 13        | 0.26%   |
| AMD E1                  | 13        | 0.26%   |
| AMD Ryzen 5 PRO         | 11        | 0.22%   |
| AMD Turion 64 X2 Mobile | 10        | 0.2%    |
| ARM BCM                 | 9         | 0.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 1836      | 37.05%  |
| 2       | 1821      | 36.75%  |
| 6       | 503       | 10.15%  |
| 8       | 397       | 8.01%   |
| 1       | 107       | 2.16%   |
| 12      | 102       | 2.06%   |
| 16      | 53        | 1.07%   |
| 3       | 49        | 0.99%   |
| 10      | 29        | 0.59%   |
| 14      | 26        | 0.52%   |
| 24      | 12        | 0.24%   |
| Unknown | 10        | 0.2%    |
| 20      | 5         | 0.1%    |
| 56      | 2         | 0.04%   |
| 64      | 1         | 0.02%   |
| 28      | 1         | 0.02%   |
| 7       | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 4856      | 98.26%  |
| 2       | 77        | 1.56%   |
| Unknown | 8         | 0.16%   |
| 3       | 1         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 3184      | 64.34%  |
| 1       | 1753      | 35.42%  |
| Unknown | 10        | 0.2%    |
| 12      | 1         | 0.02%   |
| 4       | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4796      | 96.73%  |
| Unknown        | 116       | 2.34%   |
| 32-bit         | 38        | 0.77%   |
| 64-bit         | 8         | 0.16%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1271      | 24.78%  |
| 0x306a9    | 286       | 5.58%   |
| 0x206a7    | 273       | 5.32%   |
| 0x306c3    | 219       | 4.27%   |
| 0x1067a    | 177       | 3.45%   |
| 0x906ea    | 132       | 2.57%   |
| 0x506e3    | 98        | 1.91%   |
| 0x806ea    | 89        | 1.73%   |
| 0x40651    | 87        | 1.7%    |
| 0x20655    | 86        | 1.68%   |
| 0x906e9    | 84        | 1.64%   |
| 0x08701021 | 84        | 1.64%   |
| 0x806e9    | 71        | 1.38%   |
| 0x6fd      | 71        | 1.38%   |
| 0x406e3    | 70        | 1.36%   |
| 0x806ec    | 59        | 1.15%   |
| 0x06001119 | 58        | 1.13%   |
| 0x306d4    | 55        | 1.07%   |
| 0x20652    | 55        | 1.07%   |
| 0x10676    | 51        | 0.99%   |
| 0x6fb      | 49        | 0.96%   |
| 0x08701013 | 49        | 0.96%   |
| 0x106e5    | 48        | 0.94%   |
| 0x0800820d | 48        | 0.94%   |
| 0x806c1    | 47        | 0.92%   |
| 0x06000852 | 47        | 0.92%   |
| 0xa0652    | 46        | 0.9%    |
| 0x010000c8 | 44        | 0.86%   |
| 0x706e5    | 36        | 0.7%    |
| 0x206d7    | 36        | 0.7%    |
| 0x0a50000c | 36        | 0.7%    |
| 0x30678    | 35        | 0.68%   |
| 0x08108109 | 32        | 0.62%   |
| 0x406c4    | 31        | 0.6%    |
| 0x106a5    | 31        | 0.6%    |
| 0x906ed    | 30        | 0.58%   |
| 0x906a3    | 30        | 0.58%   |
| 0x206c2    | 27        | 0.53%   |
| 0x03000027 | 27        | 0.53%   |
| 0x806eb    | 25        | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 645       | 13.05%  |
| Haswell          | 430       | 8.7%    |
| IvyBridge        | 381       | 7.71%   |
| SandyBridge      | 371       | 7.51%   |
| Penryn           | 281       | 5.69%   |
| Zen 2            | 247       | 5%      |
| Skylake          | 226       | 4.57%   |
| Westmere         | 199       | 4.03%   |
| Core             | 193       | 3.91%   |
| Unknown          | 182       | 3.68%   |
| Zen+             | 150       | 3.04%   |
| Piledriver       | 143       | 2.89%   |
| Zen 3            | 133       | 2.69%   |
| K10              | 126       | 2.55%   |
| CometLake        | 116       | 2.35%   |
| Silvermont       | 115       | 2.33%   |
| Zen              | 111       | 2.25%   |
| Nehalem          | 102       | 2.06%   |
| Excavator        | 87        | 1.76%   |
| Broadwell        | 87        | 1.76%   |
| TigerLake        | 73        | 1.48%   |
| K8 Hammer        | 65        | 1.32%   |
| IceLake          | 62        | 1.25%   |
| Alderlake Hybrid | 52        | 1.05%   |
| Goldmont plus    | 45        | 0.91%   |
| Puma             | 39        | 0.79%   |
| Bobcat           | 39        | 0.79%   |
| NetBurst         | 36        | 0.73%   |
| K10 Llano        | 35        | 0.71%   |
| Bulldozer        | 34        | 0.69%   |
| Bonnell          | 27        | 0.55%   |
| Jaguar           | 25        | 0.51%   |
| Goldmont         | 24        | 0.49%   |
| P6               | 23        | 0.47%   |
| Steamroller      | 21        | 0.42%   |
| K8 & K10 hybrid  | 11        | 0.22%   |
| Tremont          | 6         | 0.12%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2484      | 44.32%  |
| Nvidia                                       | 1626      | 29.01%  |
| AMD                                          | 1426      | 25.44%  |
| Matrox Electronics Systems                   | 37        | 0.66%   |
| ASPEED Technology                            | 23        | 0.41%   |
| Silicon Integrated Systems [SiS]             | 3         | 0.05%   |
| XGI Technology (eXtreme Graphics Innovation) | 2         | 0.04%   |
| VIA Technologies                             | 2         | 0.04%   |
| Loongson Technology                          | 1         | 0.02%   |
| ATI Technologies                             | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 236       | 4.05%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 179       | 3.07%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 141       | 2.42%   |
| Intel UHD Graphics 620                                                                   | 121       | 2.08%   |
| Intel Core Processor Integrated Graphics Controller                                      | 121       | 2.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 106       | 1.82%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 101       | 1.73%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 93        | 1.6%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 90        | 1.55%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 81        | 1.39%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 80        | 1.37%   |
| Intel HD Graphics 530                                                                    | 78        | 1.34%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 72        | 1.24%   |
| Intel HD Graphics 620                                                                    | 70        | 1.2%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 69        | 1.18%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 67        | 1.15%   |
| AMD Renoir                                                                               | 65        | 1.12%   |
| Intel HD Graphics 5500                                                                   | 63        | 1.08%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 61        | 1.05%   |
| Intel HD Graphics 630                                                                    | 60        | 1.03%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 59        | 1.01%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 58        | 1%      |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 55        | 0.94%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 53        | 0.91%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 51        | 0.88%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 50        | 0.86%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 50        | 0.86%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 50        | 0.86%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 49        | 0.84%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 47        | 0.81%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 46        | 0.79%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 44        | 0.76%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 40        | 0.69%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 37        | 0.64%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 36        | 0.62%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 35        | 0.6%    |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 35        | 0.6%    |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 35        | 0.6%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 34        | 0.58%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 33        | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                      | Computers | Percent |
|---------------------------|-----------|---------|
| 1 x Intel                 | 1880      | 37.71%  |
| 1 x AMD                   | 1207      | 24.21%  |
| 1 x Nvidia                | 1052      | 21.1%   |
| Intel + Nvidia            | 447       | 8.97%   |
| Intel + AMD               | 74        | 1.48%   |
| AMD + Nvidia              | 72        | 1.44%   |
| 2 x AMD                   | 70        | 1.4%    |
| Other                     | 63        | 1.26%   |
| 2 x Nvidia                | 39        | 0.78%   |
| 1 x Matrox                | 28        | 0.56%   |
| 1 x ASPEED                | 19        | 0.38%   |
| Nvidia + Matrox           | 8         | 0.16%   |
| 2 x Intel                 | 7         | 0.14%   |
| Intel + 2 x Nvidia        | 4         | 0.08%   |
| 1 x SiS                   | 3         | 0.06%   |
| Nvidia + ASPEED           | 3         | 0.06%   |
| 1 x VIA                   | 2         | 0.04%   |
| 5 x Nvidia                | 1         | 0.02%   |
| 2 x Loongson Technology   | 1         | 0.02%   |
| 1 x XGI                   | 1         | 0.02%   |
| 1 x Intel + 3 x AMD       | 1         | 0.02%   |
| AMD + 2 x Nvidia          | 1         | 0.02%   |
| AMD + XGI                 | 1         | 0.02%   |
| AMD + Nvidia + 1 x ASPEED | 1         | 0.02%   |
| AMD + Matrox              | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 3855      | 76.72%  |
| Proprietary | 931       | 18.53%  |
| Unknown     | 239       | 4.76%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2723      | 53.1%   |
| 0.01-0.5   | 629       | 12.27%  |
| 1.01-2.0   | 541       | 10.55%  |
| 0.51-1.0   | 380       | 7.41%   |
| 3.01-4.0   | 299       | 5.83%   |
| 7.01-8.0   | 293       | 5.71%   |
| 5.01-6.0   | 137       | 2.67%   |
| 8.01-16.0  | 78        | 1.52%   |
| 2.01-3.0   | 41        | 0.8%    |
| 4.01-5.0   | 3         | 0.06%   |
| 16.01-24.0 | 3         | 0.06%   |
| 32.01-64.0 | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 723       | 13.06%  |
| AU Optronics            | 545       | 9.84%   |
| LG Display              | 402       | 7.26%   |
| Dell                    | 374       | 6.76%   |
| Goldstar                | 341       | 6.16%   |
| Acer                    | 300       | 5.42%   |
| Chimei Innolux          | 299       | 5.4%    |
| BOE                     | 260       | 4.7%    |
| Hewlett-Packard         | 232       | 4.19%   |
| Ancor Communications    | 209       | 3.78%   |
| Sharp                   | 165       | 2.98%   |
| BenQ                    | 161       | 2.91%   |
| Apple                   | 154       | 2.78%   |
| Lenovo                  | 129       | 2.33%   |
| ViewSonic               | 109       | 1.97%   |
| ASUSTek Computer        | 101       | 1.82%   |
| Chi Mei Optoelectronics | 73        | 1.32%   |
| LG Electronics          | 65        | 1.17%   |
| Unknown                 | 58        | 1.05%   |
| Toshiba                 | 56        | 1.01%   |
| Philips                 | 55        | 0.99%   |
| Sony                    | 54        | 0.98%   |
| AOC                     | 52        | 0.94%   |
| PANDA                   | 43        | 0.78%   |
| LG Philips              | 31        | 0.56%   |
| InfoVision              | 25        | 0.45%   |
| Panasonic               | 23        | 0.42%   |
| NEC Computers           | 23        | 0.42%   |
| MSI                     | 22        | 0.4%    |
| HannStar                | 19        | 0.34%   |
| Insignia                | 15        | 0.27%   |
| HKC                     | 15        | 0.27%   |
| Gigabyte Technology     | 15        | 0.27%   |
| Gateway                 | 15        | 0.27%   |
| ANX                     | 14        | 0.25%   |
| Valve                   | 13        | 0.23%   |
| Vizio                   | 12        | 0.22%   |
| AUS                     | 12        | 0.22%   |
| Unknown                 | 12        | 0.22%   |
| Sceptre Tech            | 10        | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch  | 31        | 0.53%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch         | 31        | 0.53%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 28        | 0.48%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 23        | 0.39%   |
| Toshiba TV TSB0206 1920x1080 886x498mm 40.0-inch                      | 21        | 0.36%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 18        | 0.31%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch         | 18        | 0.31%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch         | 18        | 0.31%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 17        | 0.29%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 17        | 0.29%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 16        | 0.27%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 15        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 15        | 0.26%   |
| Goldstar FULL HD GSM5ABA 1920x1080 480x270mm 21.7-inch                | 14        | 0.24%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 14        | 0.24%   |
| ANX ANX7530 U ANX7539 800x1280                                        | 14        | 0.24%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch     | 13        | 0.22%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 13        | 0.22%   |
| AU Optronics LCD Monitor AUO423D 1920x1080 309x173mm 13.9-inch        | 13        | 0.22%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 13        | 0.22%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 13        | 0.22%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch      | 13        | 0.22%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch              | 12        | 0.21%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 12        | 0.21%   |
| BenQ GW2765 BNQ78D6 2560x1440 597x336mm 27.0-inch                     | 12        | 0.21%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 531x299mm 24.0-inch          | 12        | 0.21%   |
| Ancor Communications ASUS VE278 ACI27F6 1920x1080 598x336mm 27.0-inch | 12        | 0.21%   |
| Unknown                                                               | 12        | 0.21%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 11        | 0.19%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 11        | 0.19%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 11        | 0.19%   |
| Sharp HDMI SHP0FFB 1920x1080 820x460mm 37.0-inch                      | 11        | 0.19%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 11        | 0.19%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch              | 11        | 0.19%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 11        | 0.19%   |
| Toshiba TV TSB0205 1360x765 886x498mm 40.0-inch                       | 10        | 0.17%   |
| MSI MAG341CQ MSI1462 3440x1440 797x334mm 34.0-inch                    | 10        | 0.17%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 10        | 0.17%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch      | 10        | 0.17%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch        | 10        | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2133      | 40.03%  |
| 1366x768 (WXGA)    | 825       | 15.48%  |
| 3840x2160 (4K)     | 355       | 6.66%   |
| 1680x1050 (WSXGA+) | 254       | 4.77%   |
| 2560x1440 (QHD)    | 247       | 4.64%   |
| 1600x900 (HD+)     | 228       | 4.28%   |
| 1280x1024 (SXGA)   | 187       | 3.51%   |
| 1280x800 (WXGA)    | 150       | 2.81%   |
| 1920x1200 (WUXGA)  | 148       | 2.78%   |
| 1440x900 (WXGA+)   | 129       | 2.42%   |
| Unknown            | 114       | 2.14%   |
| 3440x1440          | 56        | 1.05%   |
| 1360x768           | 56        | 1.05%   |
| 3840x1080          | 50        | 0.94%   |
| 2560x1080          | 34        | 0.64%   |
| 1920x540           | 31        | 0.58%   |
| 800x1280           | 26        | 0.49%   |
| 2880x1800          | 26        | 0.49%   |
| 2560x1600          | 21        | 0.39%   |
| 1600x1200          | 19        | 0.36%   |
| 1024x768 (XGA)     | 16        | 0.3%    |
| 3840x2400          | 15        | 0.28%   |
| 3200x1800 (QHD+)   | 14        | 0.26%   |
| 1280x720 (HD)      | 14        | 0.26%   |
| 1024x600           | 13        | 0.24%   |
| 2736x1824          | 12        | 0.23%   |
| 5760x1080          | 7         | 0.13%   |
| 3840x1200          | 7         | 0.13%   |
| 3600x1080          | 7         | 0.13%   |
| 2160x1440          | 7         | 0.13%   |
| 7680x2160          | 6         | 0.11%   |
| 3200x2000          | 6         | 0.11%   |
| 2048x1152          | 6         | 0.11%   |
| 3200x1080          | 5         | 0.09%   |
| 2288x1287          | 5         | 0.09%   |
| 3456x2160          | 4         | 0.08%   |
| 2256x1504          | 4         | 0.08%   |
| 1920x1280          | 4         | 0.08%   |
| 5760x2160          | 3         | 0.06%   |
| 5120x1440          | 3         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1206      | 21.94%  |
| 27      | 445       | 8.1%    |
| 13      | 405       | 7.37%   |
| Unknown | 405       | 7.37%   |
| 24      | 398       | 7.24%   |
| 23      | 384       | 6.99%   |
| 21      | 327       | 5.95%   |
| 14      | 318       | 5.79%   |
| 17      | 280       | 5.09%   |
| 19      | 169       | 3.07%   |
| 31      | 148       | 2.69%   |
| 22      | 145       | 2.64%   |
| 20      | 140       | 2.55%   |
| 34      | 74        | 1.35%   |
| 18      | 74        | 1.35%   |
| 12      | 69        | 1.26%   |
| 72      | 57        | 1.04%   |
| 11      | 53        | 0.96%   |
| 84      | 50        | 0.91%   |
| 32      | 38        | 0.69%   |
| 40      | 26        | 0.47%   |
| 25      | 23        | 0.42%   |
| 74      | 21        | 0.38%   |
| 54      | 20        | 0.36%   |
| 37      | 18        | 0.33%   |
| 26      | 18        | 0.33%   |
| 16      | 17        | 0.31%   |
| 10      | 17        | 0.31%   |
| 43      | 13        | 0.24%   |
| 28      | 12        | 0.22%   |
| 48      | 11        | 0.2%    |
| 7       | 11        | 0.2%    |
| 49      | 10        | 0.18%   |
| 47      | 9         | 0.16%   |
| 46      | 8         | 0.15%   |
| 36      | 7         | 0.13%   |
| 52      | 6         | 0.11%   |
| 42      | 6         | 0.11%   |
| 39      | 6         | 0.11%   |
| 69      | 5         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1749      | 32.59%  |
| 501-600        | 1110      | 20.69%  |
| 401-500        | 741       | 13.81%  |
| Unknown        | 405       | 7.55%   |
| 351-400        | 357       | 6.65%   |
| 201-300        | 354       | 6.6%    |
| 601-700        | 216       | 4.03%   |
| 1501-2000      | 137       | 2.55%   |
| 701-800        | 119       | 2.22%   |
| 1001-1500      | 84        | 1.57%   |
| 801-900        | 59        | 1.1%    |
| 901-1000       | 21        | 0.39%   |
| 1-100          | 11        | 0.2%    |
| More than 2000 | 2         | 0.04%   |
| 101-200        | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 3411      | 69.39%  |
| 16/10   | 746       | 15.17%  |
| Unknown | 319       | 6.49%   |
| 5/4     | 173       | 3.52%   |
| 21/9    | 82        | 1.67%   |
| 3/2     | 62        | 1.26%   |
| 4/3     | 47        | 0.96%   |
| 32/9    | 22        | 0.45%   |
| 0.62    | 16        | 0.33%   |
| 6/5     | 14        | 0.28%   |
| 0.67    | 11        | 0.22%   |
| 1.96    | 4         | 0.08%   |
| 3.40    | 2         | 0.04%   |
| 1.00    | 2         | 0.04%   |
| 3.73    | 1         | 0.02%   |
| 3.33    | 1         | 0.02%   |
| 3.20    | 1         | 0.02%   |
| 0.56    | 1         | 0.02%   |
| 0.45    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1197      | 22.16%  |
| 201-250        | 1007      | 18.64%  |
| 81-90          | 551       | 10.2%   |
| 301-350        | 458       | 8.48%   |
| Unknown        | 405       | 7.5%    |
| 151-200        | 391       | 7.24%   |
| 351-500        | 272       | 5.04%   |
| More than 1000 | 189       | 3.5%    |
| 71-80          | 170       | 3.15%   |
| 121-130        | 168       | 3.11%   |
| 141-150        | 139       | 2.57%   |
| 251-300        | 136       | 2.52%   |
| 501-1000       | 114       | 2.11%   |
| 61-70          | 56        | 1.04%   |
| 51-60          | 55        | 1.02%   |
| 131-140        | 29        | 0.54%   |
| 111-120        | 22        | 0.41%   |
| 41-50          | 17        | 0.31%   |
| 91-100         | 13        | 0.24%   |
| 1-40           | 12        | 0.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1903      | 36.43%  |
| 101-120       | 1290      | 24.7%   |
| 121-160       | 1059      | 20.28%  |
| Unknown       | 405       | 7.75%   |
| 161-240       | 244       | 4.67%   |
| 1-50          | 200       | 3.83%   |
| More than 240 | 122       | 2.34%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3835      | 75.61%  |
| 2     | 844       | 16.64%  |
| 0     | 244       | 4.81%   |
| 3     | 135       | 2.66%   |
| 4     | 11        | 0.22%   |
| 5     | 2         | 0.04%   |
| 6     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2588      | 34.83%  |
| Realtek Semiconductor           | 2317      | 31.18%  |
| Qualcomm Atheros                | 830       | 11.17%  |
| Broadcom                        | 514       | 6.92%   |
| Broadcom Limited                | 126       | 1.7%    |
| Marvell Technology Group        | 121       | 1.63%   |
| Nvidia                          | 99        | 1.33%   |
| Ralink                          | 98        | 1.32%   |
| Ralink Technology               | 72        | 0.97%   |
| TP-Link                         | 68        | 0.92%   |
| D-Link                          | 60        | 0.81%   |
| ASIX Electronics                | 58        | 0.78%   |
| MediaTek                        | 57        | 0.77%   |
| Linksys                         | 42        | 0.57%   |
| D-Link System                   | 33        | 0.44%   |
| ASUSTek Computer                | 32        | 0.43%   |
| Samsung Electronics             | 29        | 0.39%   |
| Qualcomm Atheros Communications | 27        | 0.36%   |
| Microsoft                       | 20        | 0.27%   |
| Aquantia                        | 20        | 0.27%   |
| NetGear                         | 19        | 0.26%   |
| Lenovo                          | 17        | 0.23%   |
| DisplayLink                     | 17        | 0.23%   |
| Google                          | 10        | 0.13%   |
| Belkin Components               | 10        | 0.13%   |
| Sierra Wireless                 | 9         | 0.12%   |
| Qualcomm                        | 6         | 0.08%   |
| Motorola PCS                    | 6         | 0.08%   |
| Apple                           | 6         | 0.08%   |
| Microchip Technology            | 5         | 0.07%   |
| Edimax Technology               | 5         | 0.07%   |
| Arduino SA                      | 5         | 0.07%   |
| AMD                             | 5         | 0.07%   |
| VIA Technologies                | 4         | 0.05%   |
| Micro Star International        | 4         | 0.05%   |
| LG Electronics                  | 4         | 0.05%   |
| Hewlett-Packard                 | 4         | 0.05%   |
| Dell                            | 4         | 0.05%   |
| ZyDAS                           | 3         | 0.04%   |
| Xiaomi                          | 3         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1547      | 17.6%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 285       | 3.24%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 267       | 3.04%   |
| Intel Wi-Fi 6 AX200                                               | 243       | 2.77%   |
| Intel I211 Gigabit Network Connection                             | 158       | 1.8%    |
| Intel Wireless 8265 / 8275                                        | 148       | 1.68%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 123       | 1.4%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 110       | 1.25%   |
| Intel Wireless 7260                                               | 110       | 1.25%   |
| Intel Wireless 7265                                               | 103       | 1.17%   |
| Realtek RTL8125 2.5GbE Controller                                 | 97        | 1.1%    |
| Intel Ethernet Connection (2) I219-V                              | 93        | 1.06%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 90        | 1.02%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 89        | 1.01%   |
| Intel Ethernet Connection I217-LM                                 | 89        | 1.01%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 87        | 0.99%   |
| Intel Wireless 8260                                               | 85        | 0.97%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 81        | 0.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 81        | 0.92%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 80        | 0.91%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 79        | 0.9%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 72        | 0.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 69        | 0.79%   |
| Intel 82579V Gigabit Network Connection                           | 63        | 0.72%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 61        | 0.69%   |
| Intel Ethernet Controller I225-V                                  | 57        | 0.65%   |
| Intel Wireless-AC 9260                                            | 56        | 0.64%   |
| Intel Wi-Fi 6 AX201                                               | 56        | 0.64%   |
| Intel Ethernet Connection (7) I219-V                              | 51        | 0.58%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 50        | 0.57%   |
| Intel Wireless 3165                                               | 50        | 0.57%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 48        | 0.55%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 47        | 0.53%   |
| Intel Centrino Ultimate-N 6300                                    | 47        | 0.53%   |
| Intel Ethernet Connection (2) I219-LM                             | 46        | 0.52%   |
| Intel 82577LM Gigabit Network Connection                          | 46        | 0.52%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 46        | 0.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 45        | 0.51%   |
| ASIX AX88179 Gigabit Ethernet                                     | 45        | 0.51%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 43        | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1759      | 44.64%  |
| Qualcomm Atheros                      | 661       | 16.78%  |
| Realtek Semiconductor                 | 538       | 13.65%  |
| Broadcom                              | 339       | 8.6%    |
| Ralink                                | 98        | 2.49%   |
| Broadcom Limited                      | 76        | 1.93%   |
| Ralink Technology                     | 72        | 1.83%   |
| TP-Link                               | 62        | 1.57%   |
| D-Link                                | 59        | 1.5%    |
| MediaTek                              | 52        | 1.32%   |
| Linksys                               | 40        | 1.02%   |
| ASUSTek Computer                      | 32        | 0.81%   |
| Qualcomm Atheros Communications       | 27        | 0.69%   |
| D-Link System                         | 21        | 0.53%   |
| Marvell Technology Group              | 20        | 0.51%   |
| NetGear                               | 19        | 0.48%   |
| Microsoft                             | 15        | 0.38%   |
| Belkin Components                     | 10        | 0.25%   |
| Sierra Wireless                       | 9         | 0.23%   |
| Qualcomm                              | 5         | 0.13%   |
| Edimax Technology                     | 5         | 0.13%   |
| Micro Star International              | 4         | 0.1%    |
| ZyDAS                                 | 3         | 0.08%   |
| Gemtek                                | 3         | 0.08%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.08%   |
| Dell                                  | 2         | 0.05%   |
| Wilocity                              | 1         | 0.03%   |
| Wacom                                 | 1         | 0.03%   |
| TRENDnet                              | 1         | 0.03%   |
| BUFFALO                               | 1         | 0.03%   |
| Belkin                                | 1         | 0.03%   |
| Accton Technology                     | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 243       | 6.11%   |
| Intel Wireless 8265 / 8275                                     | 148       | 3.72%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 110       | 2.77%   |
| Intel Wireless 7260                                            | 110       | 2.77%   |
| Intel Wireless 7265                                            | 103       | 2.59%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 90        | 2.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 89        | 2.24%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 87        | 2.19%   |
| Intel Wireless 8260                                            | 85        | 2.14%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 81        | 2.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 81        | 2.04%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 80        | 2.01%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 79        | 1.99%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 72        | 1.81%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 69        | 1.73%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 61        | 1.53%   |
| Intel Wireless-AC 9260                                         | 56        | 1.41%   |
| Intel Wi-Fi 6 AX201                                            | 56        | 1.41%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 50        | 1.26%   |
| Intel Wireless 3165                                            | 50        | 1.26%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 47        | 1.18%   |
| Intel Centrino Ultimate-N 6300                                 | 47        | 1.18%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 46        | 1.16%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 45        | 1.13%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 43        | 1.08%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 42        | 1.06%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 39        | 0.98%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 39        | 0.98%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 37        | 0.93%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 34        | 0.85%   |
| Realtek 802.11ac NIC                                           | 34        | 0.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 34        | 0.85%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 34        | 0.85%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 33        | 0.83%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 31        | 0.78%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 31        | 0.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 30        | 0.75%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 30        | 0.75%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 30        | 0.75%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 29        | 0.73%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 2080      | 44.93%  |
| Intel                                  | 1528      | 33.01%  |
| Broadcom                               | 268       | 5.79%   |
| Qualcomm Atheros                       | 255       | 5.51%   |
| Marvell Technology Group               | 101       | 2.18%   |
| Nvidia                                 | 98        | 2.12%   |
| ASIX Electronics                       | 58        | 1.25%   |
| Broadcom Limited                       | 55        | 1.19%   |
| Samsung Electronics                    | 29        | 0.63%   |
| Aquantia                               | 20        | 0.43%   |
| DisplayLink                            | 17        | 0.37%   |
| Lenovo                                 | 16        | 0.35%   |
| D-Link System                          | 12        | 0.26%   |
| Google                                 | 9         | 0.19%   |
| TP-Link                                | 8         | 0.17%   |
| Apple                                  | 6         | 0.13%   |
| MediaTek                               | 5         | 0.11%   |
| VIA Technologies                       | 4         | 0.09%   |
| LG Electronics                         | 4         | 0.09%   |
| Hewlett-Packard                        | 4         | 0.09%   |
| Xiaomi                                 | 3         | 0.06%   |
| Research In Motion                     | 3         | 0.06%   |
| Microsoft                              | 3         | 0.06%   |
| Microchip Technology                   | 3         | 0.06%   |
| Mellanox Technologies                  | 3         | 0.06%   |
| JMicron Technology                     | 3         | 0.06%   |
| 3Com                                   | 3         | 0.06%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.04%   |
| Motorola PCS                           | 2         | 0.04%   |
| Linksys                                | 2         | 0.04%   |
| ICS Advent                             | 2         | 0.04%   |
| IBM                                    | 2         | 0.04%   |
| Huawei Technologies                    | 2         | 0.04%   |
| Dell                                   | 2         | 0.04%   |
| D-Link                                 | 2         | 0.04%   |
| Chelsio Communications                 | 2         | 0.04%   |
| American Megatrends                    | 2         | 0.04%   |
| Sundance Technology Inc / IC Plus      | 1         | 0.02%   |
| Sun Microsystems                       | 1         | 0.02%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1547      | 32.56%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 285       | 6%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 267       | 5.62%   |
| Intel I211 Gigabit Network Connection                             | 158       | 3.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 123       | 2.59%   |
| Realtek RTL8125 2.5GbE Controller                                 | 96        | 2.02%   |
| Intel Ethernet Connection (2) I219-V                              | 93        | 1.96%   |
| Intel Ethernet Connection I217-LM                                 | 89        | 1.87%   |
| Intel 82579V Gigabit Network Connection                           | 63        | 1.33%   |
| Intel Ethernet Controller I225-V                                  | 57        | 1.2%    |
| Intel Ethernet Connection (7) I219-V                              | 51        | 1.07%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 48        | 1.01%   |
| Intel Ethernet Connection (2) I219-LM                             | 46        | 0.97%   |
| Intel 82577LM Gigabit Network Connection                          | 46        | 0.97%   |
| ASIX AX88179 Gigabit Ethernet                                     | 45        | 0.95%   |
| Intel 82574L Gigabit Network Connection                           | 42        | 0.88%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 40        | 0.84%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 40        | 0.84%   |
| Intel Ethernet Connection I218-LM                                 | 38        | 0.8%    |
| Intel Ethernet Connection (2) I218-V                              | 35        | 0.74%   |
| Intel Ethernet Connection (4) I219-LM                             | 34        | 0.72%   |
| Intel Ethernet Connection I217-V                                  | 32        | 0.67%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 30        | 0.63%   |
| Nvidia MCP61 Ethernet                                             | 30        | 0.63%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 28        | 0.59%   |
| Intel I210 Gigabit Network Connection                             | 28        | 0.59%   |
| Intel Ethernet Connection I219-LM                                 | 27        | 0.57%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 26        | 0.55%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 25        | 0.53%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 25        | 0.53%   |
| Intel Ethernet Connection (4) I219-V                              | 25        | 0.53%   |
| Intel 82567LM Gigabit Network Connection                          | 25        | 0.53%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 23        | 0.48%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 23        | 0.48%   |
| Nvidia MCP79 Ethernet                                             | 23        | 0.48%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 23        | 0.48%   |
| Intel Ethernet Connection (3) I218-LM                             | 22        | 0.46%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 20        | 0.42%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 20        | 0.42%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 20        | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 4322      | 53.74%  |
| WiFi     | 3662      | 45.54%  |
| Modem    | 45        | 0.56%   |
| Unknown  | 13        | 0.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2733      | 52.5%   |
| Ethernet | 2473      | 47.5%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2746      | 55.22%  |
| 1     | 1931      | 38.83%  |
| 3     | 144       | 2.9%    |
| 0     | 102       | 2.05%   |
| 4     | 29        | 0.58%   |
| 5     | 11        | 0.22%   |
| 6     | 6         | 0.12%   |
| 22    | 1         | 0.02%   |
| 21    | 1         | 0.02%   |
| 12    | 1         | 0.02%   |
| 8     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4336      | 86.53%  |
| Yes  | 675       | 13.47%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1368      | 47.68%  |
| Broadcom                        | 206       | 7.18%   |
| Qualcomm Atheros Communications | 192       | 6.69%   |
| Realtek Semiconductor           | 189       | 6.59%   |
| Apple                           | 162       | 5.65%   |
| Cambridge Silicon Radio         | 157       | 5.47%   |
| IMC Networks                    | 132       | 4.6%    |
| Lite-On Technology              | 122       | 4.25%   |
| ASUSTek Computer                | 80        | 2.79%   |
| Foxconn / Hon Hai               | 75        | 2.61%   |
| Dell                            | 41        | 1.43%   |
| Hewlett-Packard                 | 27        | 0.94%   |
| Marvell Semiconductor           | 19        | 0.66%   |
| Ralink                          | 15        | 0.52%   |
| Toshiba                         | 14        | 0.49%   |
| Dynex                           | 13        | 0.45%   |
| MediaTek                        | 10        | 0.35%   |
| Realtek                         | 8         | 0.28%   |
| Alps Electric                   | 7         | 0.24%   |
| Logitech                        | 5         | 0.17%   |
| Micro Star International        | 4         | 0.14%   |
| Primax Electronics              | 3         | 0.1%    |
| Integrated System Solution      | 3         | 0.1%    |
| TP-Link                         | 2         | 0.07%   |
| Ralink Technology               | 2         | 0.07%   |
| Zeevo                           | 1         | 0.03%   |
| USI                             | 1         | 0.03%   |
| SINO WEALTH                     | 1         | 0.03%   |
| Qcom                            | 1         | 0.03%   |
| Nintendo                        | 1         | 0.03%   |
| Kensington                      | 1         | 0.03%   |
| HTC (High Tech Computer)        | 1         | 0.03%   |
| Fujitsu                         | 1         | 0.03%   |
| Foxconn International           | 1         | 0.03%   |
| Edimax Technology               | 1         | 0.03%   |
| D-Link System                   | 1         | 0.03%   |
| Belkin Components               | 1         | 0.03%   |
| Askey Computer                  | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                       | 496       | 17.26%  |
| Intel AX200 Bluetooth                                    | 236       | 8.21%   |
| Intel AX201 Bluetooth                                    | 193       | 6.72%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 157       | 5.46%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 149       | 5.19%   |
| Realtek Bluetooth Radio                                  | 127       | 4.42%   |
| Intel Wireless-AC 3168 Bluetooth                         | 90        | 3.13%   |
| Qualcomm Atheros  Bluetooth Device                       | 88        | 3.06%   |
| IMC Networks Bluetooth Radio                             | 71        | 2.47%   |
| Apple Bluetooth Host Controller                          | 60        | 2.09%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 56        | 1.95%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 56        | 1.95%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 54        | 1.88%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth               | 46        | 1.6%    |
| Apple Bluetooth USB Host Controller                      | 44        | 1.53%   |
| Intel Bluetooth Device                                   | 39        | 1.36%   |
| Intel AX210 Bluetooth                                    | 39        | 1.36%   |
| Realtek  Bluetooth 4.2 Adapter                           | 37        | 1.29%   |
| Foxconn / Hon Hai Bluetooth Device                       | 35        | 1.22%   |
| Lite-On Atheros AR3012 Bluetooth                         | 33        | 1.15%   |
| Apple Bluetooth HCI                                      | 33        | 1.15%   |
| Qualcomm Atheros AR3011 Bluetooth                        | 30        | 1.04%   |
| Broadcom BCM2045B (BDC-2.1)                              | 28        | 0.97%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 27        | 0.94%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                   | 26        | 0.9%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                     | 24        | 0.84%   |
| Lite-On Bluetooth Device                                 | 23        | 0.8%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter         | 20        | 0.7%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]               | 20        | 0.7%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                    | 18        | 0.63%   |
| IMC Networks Bluetooth Device                            | 18        | 0.63%   |
| Broadcom HP Portable SoftSailing                         | 17        | 0.59%   |
| Ralink RT3290 Bluetooth                                  | 15        | 0.52%   |
| IMC Networks Wireless_Device                             | 15        | 0.52%   |
| Marvell Bluetooth and Wireless LAN Composite             | 14        | 0.49%   |
| HP Broadcom 2070 Bluetooth Combo                         | 14        | 0.49%   |
| Foxconn / Hon Hai Wireless_Device                        | 14        | 0.49%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                  | 13        | 0.45%   |
| Qualcomm Atheros Bluetooth USB Host Controller           | 13        | 0.45%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 13        | 0.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 3358      | 46.95%  |
| AMD                                             | 1622      | 22.68%  |
| Nvidia                                          | 1301      | 18.19%  |
| C-Media Electronics                             | 152       | 2.12%   |
| Logitech                                        | 79        | 1.1%    |
| Creative Labs                                   | 57        | 0.8%    |
| Realtek Semiconductor                           | 32        | 0.45%   |
| Corsair                                         | 29        | 0.41%   |
| Texas Instruments                               | 26        | 0.36%   |
| JMTek                                           | 25        | 0.35%   |
| Blue Microphones                                | 25        | 0.35%   |
| SteelSeries ApS                                 | 23        | 0.32%   |
| Razer USA                                       | 21        | 0.29%   |
| Focusrite-Novation                              | 21        | 0.29%   |
| Creative Technology                             | 20        | 0.28%   |
| ASUSTek Computer                                | 18        | 0.25%   |
| Plantronics                                     | 17        | 0.24%   |
| Lenovo                                          | 17        | 0.24%   |
| GN Netcom                                       | 17        | 0.24%   |
| Kingston Technology                             | 16        | 0.22%   |
| Samson Technologies                             | 13        | 0.18%   |
| GYROCOM C&C                                     | 13        | 0.18%   |
| Sony                                            | 12        | 0.17%   |
| Generalplus Technology                          | 11        | 0.15%   |
| VIA Technologies                                | 9         | 0.13%   |
| M-Audio                                         | 9         | 0.13%   |
| Dell                                            | 8         | 0.11%   |
| FiiO Electronics Technology                     | 7         | 0.1%    |
| Yamaha                                          | 6         | 0.08%   |
| XMOS                                            | 6         | 0.08%   |
| Thesycon Systemsoftware & Consulting            | 6         | 0.08%   |
| SAVITECH                                        | 6         | 0.08%   |
| Micro Star International                        | 6         | 0.08%   |
| Cambridge Silicon Radio                         | 6         | 0.08%   |
| Bose                                            | 6         | 0.08%   |
| Audio-Technica                                  | 6         | 0.08%   |
| Tenx Technology                                 | 5         | 0.07%   |
| Sennheiser Communications                       | 5         | 0.07%   |
| NAD Electronics                                 | 5         | 0.07%   |
| Licensed by Sony Computer Entertainment America | 4         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 359       | 4.27%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 321       | 3.81%   |
| Intel Sunrise Point-LP HD Audio                                            | 294       | 3.49%   |
| AMD Family 17h/19h HD Audio Controller                                     | 291       | 3.46%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 250       | 2.97%   |
| AMD Starship/Matisse HD Audio Controller                                   | 239       | 2.84%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 239       | 2.84%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 216       | 2.57%   |
| AMD FCH Azalia Controller                                                  | 203       | 2.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 183       | 2.17%   |
| Intel Cannon Lake PCH cAVS                                                 | 178       | 2.12%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 176       | 2.09%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 142       | 1.69%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 139       | 1.65%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 134       | 1.59%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 131       | 1.56%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 109       | 1.3%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 105       | 1.25%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 105       | 1.25%   |
| Intel Haswell-ULT HD Audio Controller                                      | 104       | 1.24%   |
| Intel 8 Series HD Audio Controller                                         | 104       | 1.24%   |
| Nvidia GP107GL High Definition Audio Controller                            | 99        | 1.18%   |
| Intel 200 Series PCH HD Audio                                              | 98        | 1.16%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 96        | 1.14%   |
| AMD Kabini HDMI/DP Audio                                                   | 96        | 1.14%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 92        | 1.09%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 85        | 1.01%   |
| Intel Comet Lake PCH cAVS                                                  | 84        | 1%      |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 84        | 1%      |
| Nvidia GP106 High Definition Audio Controller                              | 77        | 0.91%   |
| Intel Broadwell-U Audio Controller                                         | 77        | 0.91%   |
| Nvidia TU116 High Definition Audio Controller                              | 76        | 0.9%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 73        | 0.87%   |
| Nvidia GP104 High Definition Audio Controller                              | 72        | 0.86%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 72        | 0.86%   |
| Nvidia TU106 High Definition Audio Controller                              | 71        | 0.84%   |
| Nvidia GK107 HDMI Audio Controller                                         | 68        | 0.81%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 65        | 0.77%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 59        | 0.7%    |
| AMD Navi 10 HDMI Audio                                                     | 57        | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                                           | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 557       | 19.67%  |
| SK hynix                                         | 522       | 18.43%  |
| Kingston                                         | 344       | 12.15%  |
| Unknown                                          | 278       | 9.82%   |
| Micron Technology                                | 275       | 9.71%   |
| G.Skill                                          | 196       | 6.92%   |
| Corsair                                          | 175       | 6.18%   |
| Crucial                                          | 123       | 4.34%   |
| Nanya Technology                                 | 54        | 1.91%   |
| Elpida                                           | 52        | 1.84%   |
| A-DATA Technology                                | 47        | 1.66%   |
| Ramaxel Technology                               | 45        | 1.59%   |
| Patriot                                          | 28        | 0.99%   |
| Unknown                                          | 20        | 0.71%   |
| Team                                             | 13        | 0.46%   |
| Unknown (ABCD)                                   | 8         | 0.28%   |
| Transcend                                        | 8         | 0.28%   |
| Timetec                                          | 7         | 0.25%   |
| ASint Technology                                 | 7         | 0.25%   |
| Unifosa                                          | 6         | 0.21%   |
| Toshiba                                          | 6         | 0.21%   |
| Goldkey                                          | 4         | 0.14%   |
| Avant                                            | 4         | 0.14%   |
| Qimonda                                          | 3         | 0.11%   |
| PNY                                              | 3         | 0.11%   |
| OCZ                                              | 3         | 0.11%   |
| CSX                                              | 3         | 0.11%   |
| Unknown (7F7F7F94FFFFFFFF)                       | 2         | 0.07%   |
| SHARETRONIC                                      | 2         | 0.07%   |
| Sesame                                           | 2         | 0.07%   |
| Neo Forza                                        | 2         | 0.07%   |
| Mushkin                                          | 2         | 0.07%   |
| Hewlett-Packard                                  | 2         | 0.07%   |
| ff                                               | 2         | 0.07%   |
| Axiom                                            | 2         | 0.07%   |
| Apacer                                           | 2         | 0.07%   |
| 4ea5                                             | 2         | 0.07%   |
| Unknown (0x505344323247363637325300000000000000) | 1         | 0.04%   |
| Unknown (0x4D342037305432383634515A332D43453620) | 1         | 0.04%   |
| Unknown (0x0C26)                                 | 1         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 31        | 1.01%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 21        | 0.68%   |
| Unknown                                                          | 20        | 0.65%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 19        | 0.62%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 19        | 0.62%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 18        | 0.59%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 18        | 0.59%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 18        | 0.59%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s             | 18        | 0.59%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 17        | 0.55%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 17        | 0.55%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 17        | 0.55%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 16        | 0.52%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 15        | 0.49%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 15        | 0.49%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 14        | 0.46%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 14        | 0.46%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 13        | 0.42%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 12        | 0.39%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 12        | 0.39%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 12        | 0.39%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 12        | 0.39%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s              | 12        | 0.39%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 11        | 0.36%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 11        | 0.36%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s            | 11        | 0.36%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 10        | 0.33%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 10        | 0.33%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 10        | 0.33%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 10        | 0.33%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s              | 10        | 0.33%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 9         | 0.29%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 9         | 0.29%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 9         | 0.29%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 9         | 0.29%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 9         | 0.29%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                          | 8         | 0.26%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 0.26%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 8         | 0.26%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 8         | 0.26%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1039      | 43.09%  |
| DDR3    | 881       | 36.54%  |
| DDR2    | 140       | 5.81%   |
| LPDDR4  | 77        | 3.19%   |
| SDRAM   | 69        | 2.86%   |
| LPDDR3  | 68        | 2.82%   |
| Unknown | 65        | 2.7%    |
| DDR     | 32        | 1.33%   |
| DDR5    | 29        | 1.2%    |
| LPDDR5  | 9         | 0.37%   |
| DRAM    | 2         | 0.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1171      | 49.16%  |
| DIMM         | 1032      | 43.32%  |
| Row Of Chips | 149       | 6.26%   |
| Chip         | 17        | 0.71%   |
| Unknown      | 10        | 0.42%   |
| FB-DIMM      | 3         | 0.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size   | Computers | Percent |
|--------|-----------|---------|
| 8192   | 971       | 36.38%  |
| 4096   | 756       | 28.33%  |
| 16384  | 381       | 14.28%  |
| 2048   | 366       | 13.71%  |
| 1024   | 114       | 4.27%   |
| 32768  | 67        | 2.51%   |
| 512    | 11        | 0.41%   |
| 129408 | 1         | 0.04%   |
| 65536  | 1         | 0.04%   |
| 256    | 1         | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 540       | 20.52%  |
| 3200    | 311       | 11.82%  |
| 2667    | 307       | 11.66%  |
| 1333    | 235       | 8.93%   |
| 2400    | 191       | 7.26%   |
| 2133    | 137       | 5.21%   |
| 3600    | 88        | 3.34%   |
| 667     | 76        | 2.89%   |
| 800     | 70        | 2.66%   |
| 1334    | 67        | 2.55%   |
| 1867    | 61        | 2.32%   |
| 1067    | 45        | 1.71%   |
| 4267    | 37        | 1.41%   |
| 1066    | 37        | 1.41%   |
| Unknown | 36        | 1.37%   |
| 3266    | 26        | 0.99%   |
| 4800    | 21        | 0.8%    |
| 3733    | 21        | 0.8%    |
| 1866    | 21        | 0.8%    |
| 3866    | 19        | 0.72%   |
| 3800    | 19        | 0.72%   |
| 2666    | 19        | 0.72%   |
| 3400    | 18        | 0.68%   |
| 3466    | 16        | 0.61%   |
| 2933    | 16        | 0.61%   |
| 3000    | 15        | 0.57%   |
| 6400    | 13        | 0.49%   |
| 4199    | 13        | 0.49%   |
| 533     | 13        | 0.49%   |
| 8400    | 9         | 0.34%   |
| 2800    | 8         | 0.3%    |
| 2048    | 8         | 0.3%    |
| 975     | 8         | 0.3%    |
| 4266    | 7         | 0.27%   |
| 1800    | 7         | 0.27%   |
| 1639    | 7         | 0.27%   |
| 400     | 7         | 0.27%   |
| 2465    | 6         | 0.23%   |
| 2000    | 6         | 0.23%   |
| 3534    | 5         | 0.19%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Brother Industries       | 67        | 33.84%  |
| Hewlett-Packard          | 56        | 28.28%  |
| Samsung Electronics      | 30        | 15.15%  |
| Canon                    | 28        | 14.14%  |
| Seiko Epson              | 8         | 4.04%   |
| Lexmark International    | 3         | 1.52%   |
| Dymo-CoStar              | 2         | 1.01%   |
| Dell                     | 2         | 1.01%   |
| Zhuhai Poskey Technology | 1         | 0.51%   |
| Prolific Technology      | 1         | 0.51%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Brother Printer                      | 9         | 4.43%   |
| HP LaserJet 1018                     | 5         | 2.46%   |
| Brother HL-L2390DW                   | 5         | 2.46%   |
| Seiko Epson ET-3750 Series           | 4         | 1.97%   |
| HP LaserJet 1020                     | 4         | 1.97%   |
| Brother HL-L2320D series             | 4         | 1.97%   |
| Brother HL-5370DW series             | 4         | 1.97%   |
| Samsung ML-216x Series Laser Printer | 3         | 1.48%   |
| Samsung ML-1670 Series               | 3         | 1.48%   |
| HP LaserJet 4250                     | 3         | 1.48%   |
| HP ENVY 4520 series                  | 3         | 1.48%   |
| HP DeskJet 3630 series               | 3         | 1.48%   |
| HP DeskJet 2620 All-in-One Printer   | 3         | 1.48%   |
| Canon PIXMA MX920 Series             | 3         | 1.48%   |
| Canon PIXMA MG2900 Series            | 3         | 1.48%   |
| Brother MFC-J480DW                   | 3         | 1.48%   |
| Brother MFC-9130CW                   | 3         | 1.48%   |
| Brother HL-L2360D series             | 3         | 1.48%   |
| Brother HL-2270DW Laser Printer      | 3         | 1.48%   |
| Brother DCP-L2540DW                  | 3         | 1.48%   |
| Samsung ML-1660 Series               | 2         | 0.99%   |
| Samsung M267x 287x Series            | 2         | 0.99%   |
| Samsung M2070 Series                 | 2         | 0.99%   |
| Samsung M2020 Series                 | 2         | 0.99%   |
| Samsung CLP-310 Color Laser Printer  | 2         | 0.99%   |
| Samsung C460 Series                  | 2         | 0.99%   |
| HP OfficeJet 3830 series             | 2         | 0.99%   |
| HP LaserJet Pro M202dw               | 2         | 0.99%   |
| HP LaserJet M101-M106                | 2         | 0.99%   |
| HP DeskJet 3700 series               | 2         | 0.99%   |
| Dymo-CoStar LabelWriter 450          | 2         | 0.99%   |
| Canon PIXMA MX530 Series             | 2         | 0.99%   |
| Canon MG2100 series                  | 2         | 0.99%   |
| Canon MF4410                         | 2         | 0.99%   |
| Canon MF3010                         | 2         | 0.99%   |
| Brother MFC-J485DW                   | 2         | 0.99%   |
| Brother MFC-9330CDW                  | 2         | 0.99%   |
| Brother HL-L3290CDW series           | 2         | 0.99%   |
| Brother HL-2140 series               | 2         | 0.99%   |
| Zhuhai Poskey Printer                | 1         | 0.49%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 19        | 59.38%  |
| Hewlett-Packard | 8         | 25%     |
| Seiko Epson     | 5         | 15.63%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 700F                                | 4         | 12.5%   |
| Canon CanoScan LiDE 220                                 | 4         | 12.5%   |
| Canon CanoScan LiDE 210                                 | 4         | 12.5%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]             | 2         | 6.25%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]             | 1         | 3.13%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1         | 3.13%   |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]           | 1         | 3.13%   |
| HP ScanJet G4050                                        | 1         | 3.13%   |
| HP ScanJet G4010                                        | 1         | 3.13%   |
| HP ScanJet 82x0C                                        | 1         | 3.13%   |
| HP ScanJet 5590                                         | 1         | 3.13%   |
| HP ScanJet 5200c                                        | 1         | 3.13%   |
| HP ScanJet 3670                                         | 1         | 3.13%   |
| HP ScanJet 3400cse                                      | 1         | 3.13%   |
| HP ScanJet 2200c                                        | 1         | 3.13%   |
| Canon CanoScan LiDE 70                                  | 1         | 3.13%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                  | 1         | 3.13%   |
| Canon CanoScan LiDE 200                                 | 1         | 3.13%   |
| Canon CanoScan LiDE 120                                 | 1         | 3.13%   |
| Canon CanoScan LiDE 110                                 | 1         | 3.13%   |
| Canon CanoScan 4200F                                    | 1         | 3.13%   |
| Canon CanoScan                                          | 1         | 3.13%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 520       | 19.27%  |
| Microdia                               | 278       | 10.3%   |
| Logitech                               | 253       | 9.37%   |
| IMC Networks                           | 223       | 8.26%   |
| Realtek Semiconductor                  | 187       | 6.93%   |
| Acer                                   | 180       | 6.67%   |
| Apple                                  | 163       | 6.04%   |
| Sunplus Innovation Technology          | 140       | 5.19%   |
| Suyin                                  | 94        | 3.48%   |
| Quanta                                 | 93        | 3.45%   |
| Microsoft                              | 71        | 2.63%   |
| Cheng Uei Precision Industry (Foxlink) | 65        | 2.41%   |
| Syntek                                 | 38        | 1.41%   |
| Samsung Electronics                    | 36        | 1.33%   |
| Lite-On Technology                     | 36        | 1.33%   |
| Ricoh                                  | 27        | 1%      |
| Silicon Motion                         | 26        | 0.96%   |
| Lenovo                                 | 23        | 0.85%   |
| Luxvisions Innotech Limited            | 22        | 0.82%   |
| Importek                               | 19        | 0.7%    |
| Z-Star Microelectronics                | 16        | 0.59%   |
| AVerMedia Technologies                 | 14        | 0.52%   |
| Alcor Micro                            | 14        | 0.52%   |
| MacroSilicon                           | 13        | 0.48%   |
| ALi                                    | 9         | 0.33%   |
| Sonix Technology                       | 8         | 0.3%    |
| OmniVision Technologies                | 8         | 0.3%    |
| Primax Electronics                     | 7         | 0.26%   |
| LG Electronics                         | 7         | 0.26%   |
| Cubeternet                             | 7         | 0.26%   |
| Creative Technology                    | 7         | 0.26%   |
| 2M UVC CAMERA                          | 6         | 0.22%   |
| Razer USA                              | 5         | 0.19%   |
| Huawei Technologies                    | 5         | 0.19%   |
| Hewlett-Packard                        | 5         | 0.19%   |
| Genesys Logic                          | 5         | 0.19%   |
| Generalplus Technology                 | 5         | 0.19%   |
| DLEQNA19IFK6G2                         | 5         | 0.19%   |
| Unknown                                | 4         | 0.15%   |
| Canon                                  | 4         | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Chicony Integrated Camera            | 112       | 4.11%   |
| Microdia Integrated_Webcam_HD        | 104       | 3.82%   |
| IMC Networks USB2.0 HD UVC WebCam    | 81        | 2.97%   |
| Realtek Integrated_Webcam_HD         | 70        | 2.57%   |
| Apple Built-in iSight                | 60        | 2.2%    |
| Logitech HD Pro Webcam C920          | 56        | 2.06%   |
| Logitech Webcam C270                 | 54        | 1.98%   |
| Acer Integrated Camera               | 50        | 1.84%   |
| Chicony HD WebCam                    | 48        | 1.76%   |
| IMC Networks Integrated Camera       | 46        | 1.69%   |
| Apple iPhone 5/5C/5S/6/SE            | 45        | 1.65%   |
| Samsung Galaxy A5 (MTP)              | 36        | 1.32%   |
| Sunplus Integrated_Webcam_HD         | 32        | 1.18%   |
| Apple FaceTime HD Camera (Built-in)  | 32        | 1.18%   |
| Microdia Integrated Webcam           | 31        | 1.14%   |
| IMC Networks USB2.0 VGA UVC WebCam   | 28        | 1.03%   |
| Syntek Integrated Camera             | 27        | 0.99%   |
| Microdia Webcam Vitade AF            | 24        | 0.88%   |
| Sunplus HD WebCam                    | 23        | 0.84%   |
| Chicony VGA WebCam                   | 22        | 0.81%   |
| Apple FaceTime HD Camera             | 22        | 0.81%   |
| Microsoft LifeCam HD-3000            | 21        | 0.77%   |
| Logitech C922 Pro Stream Webcam      | 20        | 0.73%   |
| Acer Lenovo EasyCamera               | 20        | 0.73%   |
| Chicony HP TrueVision HD             | 19        | 0.7%    |
| Lite-On Integrated Camera            | 18        | 0.66%   |
| Chicony USB2.0 HD UVC WebCam         | 18        | 0.66%   |
| Acer HD Webcam                       | 18        | 0.66%   |
| Quanta VGA WebCam                    | 17        | 0.62%   |
| Quanta HD User Facing                | 16        | 0.59%   |
| Chicony USB 2.0 Camera               | 16        | 0.59%   |
| Realtek USB Camera                   | 15        | 0.55%   |
| Quanta HP TrueVision HD Camera       | 15        | 0.55%   |
| Chicony HP HD Camera                 | 15        | 0.55%   |
| Acer SunplusIT Integrated Camera     | 15        | 0.55%   |
| Chicony TOSHIBA Web Camera - HD      | 14        | 0.51%   |
| Microdia Laptop_Integrated_Webcam_HD | 13        | 0.48%   |
| Microdia CameraA                     | 13        | 0.48%   |
| Logitech HD Webcam C615              | 13        | 0.48%   |
| Chicony USB2.0 VGA UVC WebCam        | 13        | 0.48%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 187       | 37.78%  |
| Synaptics                          | 116       | 23.43%  |
| Shenzhen Goodix Technology         | 47        | 9.49%   |
| Elan Microelectronics              | 36        | 7.27%   |
| Upek                               | 32        | 6.46%   |
| AuthenTec                          | 30        | 6.06%   |
| LighTuning Technology              | 22        | 4.44%   |
| STMicroelectronics                 | 15        | 3.03%   |
| Focal-systems.Corp                 | 3         | 0.61%   |
| Samsung Electronics                | 2         | 0.4%    |
| Microsoft                          | 2         | 0.4%    |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.2%    |
| HOLTEK                             | 1         | 0.2%    |
| Dell                               | 1         | 0.2%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 44        | 8.89%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 33        | 6.67%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 31        | 6.26%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 31        | 6.26%   |
| Unknown                                                                    | 31        | 6.26%   |
| Elan ELAN:Fingerprint                                                      | 29        | 5.86%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 23        | 4.65%   |
| Shenzhen Goodix FingerPrint                                                | 23        | 4.65%   |
| Validity Sensors Synaptics WBDI                                            | 21        | 4.24%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 19        | 3.84%   |
| Validity Sensors VFS491                                                    | 18        | 3.64%   |
| STMicroelectronics Fingerprint Reader                                      | 15        | 3.03%   |
| AuthenTec AES2810                                                          | 14        | 2.83%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 12        | 2.42%   |
| Synaptics  WBDI                                                            | 12        | 2.42%   |
| Shenzhen Goodix  FingerPrint Device                                        | 12        | 2.42%   |
| Shenzhen Goodix Fingerprint Reader                                         | 12        | 2.42%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 11        | 2.22%   |
| Validity Sensors Fingerprint scanner                                       | 9         | 1.82%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 8         | 1.62%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 8         | 1.62%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 7         | 1.41%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 7         | 1.41%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 7         | 1.41%   |
| Elan ELAN:ARM-M4                                                           | 6         | 1.21%   |
| AuthenTec Fingerprint Sensor                                               | 6         | 1.21%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 6         | 1.21%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 5         | 1.01%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 0.61%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 3         | 0.61%   |
| AuthenTec AES1600                                                          | 3         | 0.61%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 2         | 0.4%    |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 0.4%    |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.4%    |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 2         | 0.4%    |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 0.4%    |
| Samsung Fingerprint Sensor Device - 730B                                   | 2         | 0.4%    |
| Microsoft Fingerprint Reader                                               | 2         | 0.4%    |
| LighTuning Fingerprint Reader                                              | 2         | 0.4%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.2%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 81        | 43.09%  |
| Alcor Micro               | 36        | 19.15%  |
| O2 Micro                  | 25        | 13.3%   |
| Upek                      | 21        | 11.17%  |
| Lenovo                    | 12        | 6.38%   |
| Gemalto (was Gemplus)     | 4         | 2.13%   |
| Yubico.com                | 2         | 1.06%   |
| SCM Microsystems          | 2         | 1.06%   |
| Aladdin Knowledge Systems | 2         | 1.06%   |
| In Focus Systems          | 1         | 0.53%   |
| Giesecke & Devrient       | 1         | 0.53%   |
| Clay Logic                | 1         | 0.53%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 45        | 23.94%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 34        | 18.09%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 21        | 11.17%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 21        | 11.17%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 17        | 9.04%   |
| Lenovo Integrated Smart Card Reader                                          | 12        | 6.38%   |
| Broadcom 5880                                                                | 12        | 6.38%   |
| Broadcom 58200                                                               | 6         | 3.19%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 2.13%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 4         | 2.13%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 1.06%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 1.06%   |
| Yubico.com Yubikey 4/5 CCID                                                  | 1         | 0.53%   |
| Yubico.com Yubikey 4 U2F+CCID                                                | 1         | 0.53%   |
| SCM Microsystems SCR3500 A Contact Reader                                    | 1         | 0.53%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.53%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.53%   |
| Giesecke & Devrient StarSign CUT S                                           | 1         | 0.53%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.53%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.53%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 3617      | 71.27%  |
| 1     | 1162      | 22.9%   |
| 2     | 241       | 4.75%   |
| 3     | 34        | 0.67%   |
| 4     | 12        | 0.24%   |
| 5     | 5         | 0.1%    |
| 8     | 2         | 0.04%   |
| 7     | 1         | 0.02%   |
| 6     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 487       | 27.88%  |
| Graphics card            | 363       | 20.78%  |
| Net/wireless             | 256       | 14.65%  |
| Chipcard                 | 172       | 9.85%   |
| Communication controller | 103       | 5.9%    |
| Multimedia controller    | 91        | 5.21%   |
| Unassigned class         | 42        | 2.4%    |
| Bluetooth                | 37        | 2.12%   |
| Camera                   | 33        | 1.89%   |
| Storage                  | 32        | 1.83%   |
| Sound                    | 32        | 1.83%   |
| Net/ethernet             | 26        | 1.49%   |
| Network                  | 15        | 0.86%   |
| Modem                    | 11        | 0.63%   |
| Card reader              | 9         | 0.52%   |
| Storage/raid             | 7         | 0.4%    |
| Storage/ide              | 7         | 0.4%    |
| Firewire controller      | 7         | 0.4%    |
| Dvb card                 | 7         | 0.4%    |
| Flash memory             | 4         | 0.23%   |
| Tv card                  | 2         | 0.11%   |
| Video                    | 1         | 0.06%   |
| Unclassified device      | 1         | 0.06%   |
| Storage/nvme             | 1         | 0.06%   |
| Storage/ata              | 1         | 0.06%   |

