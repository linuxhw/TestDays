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

Total: 686

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [784f886357](https://linux-hardware.org/?probe=784f886357) | Jul 10, 2023 |
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
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [01076d8e8b](https://linux-hardware.org/?probe=01076d8e8b) | May 30, 2023 |
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
| ASUSTek       | PRIME B450M-A               | [59456f2a25](https://linux-hardware.org/?probe=59456f2a25) | Aug 16, 2022 |
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
| Dell          | 01TKCC A01                  | [94e2e60839](https://linux-hardware.org/?probe=94e2e60839) | Apr 11, 2019 |
| MSI           | Z87M-G43                    | [cbb0c4be39](https://linux-hardware.org/?probe=cbb0c4be39) | Apr 11, 2019 |
| MSI           | Z87M-G43                    | [6fb3422b8b](https://linux-hardware.org/?probe=6fb3422b8b) | Apr 11, 2019 |
| HP            | 158A                        | [61be039d0f](https://linux-hardware.org/?probe=61be039d0f) | Apr 02, 2019 |
| Intel         | DH55HC AAE70933-502         | [8f109c807c](https://linux-hardware.org/?probe=8f109c807c) | Feb 15, 2019 |
| Intel         | DH55HC AAE70933-502         | [be7548c062](https://linux-hardware.org/?probe=be7548c062) | Feb 15, 2019 |
| Wibtek        | H61-M HDMI2                 | [6f082a4f2d](https://linux-hardware.org/?probe=6f082a4f2d) | Feb 12, 2019 |
| Wibtek        | H61-M HDMI2                 | [3a44341e10](https://linux-hardware.org/?probe=3a44341e10) | Feb 12, 2019 |
| ECS           | H61H2-M2                    | [ed1e345718](https://linux-hardware.org/?probe=ed1e345718) | Feb 02, 2019 |
| ECS           | H61H2-M2                    | [554a16077e](https://linux-hardware.org/?probe=554a16077e) | Feb 01, 2019 |
| Gigabyte      | G31M-ES2L                   | [8531feefb2](https://linux-hardware.org/?probe=8531feefb2) | Jan 07, 2019 |
| Gigabyte      | A320M-S2H-CF                | [a72d5458ff](https://linux-hardware.org/?probe=a72d5458ff) | Nov 23, 2018 |
| Gigabyte      | B85M-D3H                    | [d206454b5f](https://linux-hardware.org/?probe=d206454b5f) | Aug 27, 2018 |
| ASUSTek       | P5GD1 PRO                   | [7f52004043](https://linux-hardware.org/?probe=7f52004043) | Aug 02, 2018 |
| ECS           | H61H2-M2                    | [765806fe73](https://linux-hardware.org/?probe=765806fe73) | Jun 01, 2018 |
| Gigabyte      | GA-990FXA-UD3               | [2e67236dbb](https://linux-hardware.org/?probe=2e67236dbb) | Feb 23, 2018 |

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
| Elementary 6.1   | 185      | 37.6%   |
| Elementary 5.1.7 | 71       | 14.43%  |
| Elementary 7     | 67       | 13.62%  |
| Elementary 6     | 66       | 13.41%  |
| Elementary 7.1   | 28       | 5.69%   |
| Elementary 5.1   | 17       | 3.46%   |
| Elementary 5.0   | 17       | 3.46%   |
| Elementary 5.1.2 | 10       | 2.03%   |
| Elementary 5.1.4 | 7        | 1.42%   |
| Elementary 5.1.3 | 7        | 1.42%   |
| Elementary 0.4.1 | 7        | 1.42%   |
| Elementary 5.1.6 | 6        | 1.22%   |
| Elementary 6.0   | 2        | 0.41%   |
| Elementary 5.1.5 | 2        | 0.41%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Elementary | 461      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.11.0-43-generic | 36       | 6.67%   |
| 5.15.0-58-generic | 25       | 4.63%   |
| 5.11.0-41-generic | 19       | 3.52%   |
| 5.13.0-39-generic | 17       | 3.15%   |
| 5.11.0-40-generic | 17       | 3.15%   |
| 5.13.0-28-generic | 16       | 2.96%   |
| 5.15.0-46-generic | 14       | 2.59%   |
| 5.0.0-37-generic  | 11       | 2.04%   |
| 5.13.0-27-generic | 10       | 1.85%   |
| 5.11.0-27-generic | 10       | 1.85%   |
| 5.4.0-42-generic  | 9        | 1.67%   |
| 5.19.0-32-generic | 9        | 1.67%   |
| 5.15.0-56-generic | 9        | 1.67%   |
| 5.13.0-40-generic | 9        | 1.67%   |
| 5.13.0-30-generic | 9        | 1.67%   |
| 6.2.0-36-generic  | 8        | 1.48%   |
| 5.4.0-48-generic  | 8        | 1.48%   |
| 5.13.0-35-generic | 7        | 1.3%    |
| 5.11.0-37-generic | 7        | 1.3%    |
| 6.2.0-35-generic  | 6        | 1.11%   |
| 5.4.0-65-generic  | 6        | 1.11%   |
| 5.4.0-58-generic  | 6        | 1.11%   |
| 5.19.0-35-generic | 6        | 1.11%   |
| 5.13.0-37-generic | 6        | 1.11%   |
| 5.11.0-25-generic | 6        | 1.11%   |
| 5.4.0-54-generic  | 5        | 0.93%   |
| 5.3.0-46-generic  | 5        | 0.93%   |
| 5.3.0-40-generic  | 5        | 0.93%   |
| 5.19.0-38-generic | 5        | 0.93%   |
| 5.15.0-60-generic | 5        | 0.93%   |
| 5.13.0-52-generic | 5        | 0.93%   |
| 5.13.0-51-generic | 5        | 0.93%   |
| 5.11.0-38-generic | 5        | 0.93%   |
| 6.2.0-33-generic  | 4        | 0.74%   |
| 6.2.0-32-generic  | 4        | 0.74%   |
| 6.2.0-26-generic  | 4        | 0.74%   |
| 5.19.0-46-generic | 4        | 0.74%   |
| 5.19.0-41-generic | 4        | 0.74%   |
| 5.15.0-53-generic | 4        | 0.74%   |
| 5.15.0-52-generic | 4        | 0.74%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11.0  | 105      | 21.38%  |
| 5.13.0  | 87       | 17.72%  |
| 5.15.0  | 78       | 15.89%  |
| 5.4.0   | 67       | 13.65%  |
| 6.2.0   | 35       | 7.13%   |
| 5.19.0  | 34       | 6.92%   |
| 5.3.0   | 24       | 4.89%   |
| 4.15.0  | 24       | 4.89%   |
| 5.0.0   | 15       | 3.05%   |
| 5.8.0   | 5        | 1.02%   |
| 4.18.0  | 3        | 0.61%   |
| 4.4.0   | 2        | 0.41%   |
| 6.4.5   | 1        | 0.2%    |
| 6.1.8   | 1        | 0.2%    |
| 5.2.11  | 1        | 0.2%    |
| 5.17.3  | 1        | 0.2%    |
| 5.17.0  | 1        | 0.2%    |
| 5.16.15 | 1        | 0.2%    |
| 5.15.36 | 1        | 0.2%    |
| 5.15.12 | 1        | 0.2%    |
| 5.15.1  | 1        | 0.2%    |
| 5.14.0  | 1        | 0.2%    |
| 5.0.11  | 1        | 0.2%    |
| 4.10.0  | 1        | 0.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11    | 105      | 21.38%  |
| 5.13    | 87       | 17.72%  |
| 5.15    | 81       | 16.5%   |
| 5.4     | 67       | 13.65%  |
| 6.2     | 35       | 7.13%   |
| 5.19    | 34       | 6.92%   |
| 5.3     | 24       | 4.89%   |
| 4.15    | 24       | 4.89%   |
| 5.0     | 16       | 3.26%   |
| 5.8     | 5        | 1.02%   |
| 4.18    | 3        | 0.61%   |
| 5.17    | 2        | 0.41%   |
| 4.4     | 2        | 0.41%   |
| 6.4     | 1        | 0.2%    |
| 6.1     | 1        | 0.2%    |
| 5.2     | 1        | 0.2%    |
| 5.16    | 1        | 0.2%    |
| 5.14    | 1        | 0.2%    |
| 4.10    | 1        | 0.2%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 461      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| Pantheon | 437      | 93.38%  |
| Unknown  | 26       | 5.56%   |
| GNOME    | 3        | 0.64%   |
| MATE     | 1        | 0.21%   |
| KDE5     | 1        | 0.21%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 460      | 99.78%  |
| Unknown | 1        | 0.22%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 391      | 83.01%  |
| LightDM | 62       | 13.16%  |
| TDM     | 16       | 3.4%    |
| SDDM    | 1        | 0.21%   |
| GDM     | 1        | 0.21%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 184      | 38.9%   |
| de_DE   | 52       | 10.99%  |
| es_ES   | 33       | 6.98%   |
| ru_RU   | 25       | 5.29%   |
| Unknown | 24       | 5.07%   |
| fr_FR   | 19       | 4.02%   |
| pt_BR   | 18       | 3.81%   |
| en_GB   | 17       | 3.59%   |
| it_IT   | 14       | 2.96%   |
| en_CA   | 13       | 2.75%   |
| pl_PL   | 9        | 1.9%    |
| pt_PT   | 7        | 1.48%   |
| tr_TR   | 6        | 1.27%   |
| en_AU   | 6        | 1.27%   |
| nl_NL   | 3        | 0.63%   |
| ja_JP   | 3        | 0.63%   |
| es_MX   | 3        | 0.63%   |
| de_CH   | 3        | 0.63%   |
| zh_CN   | 2        | 0.42%   |
| sv_SE   | 2        | 0.42%   |
| hu_HU   | 2        | 0.42%   |
| fi_FI   | 2        | 0.42%   |
| en_IN   | 2        | 0.42%   |
| cs_CZ   | 2        | 0.42%   |
| zh_TW   | 1        | 0.21%   |
| uk_UA   | 1        | 0.21%   |
| sr_RS   | 1        | 0.21%   |
| nb_NO   | 1        | 0.21%   |
| id_ID   | 1        | 0.21%   |
| hr_HR   | 1        | 0.21%   |
| gl_ES   | 1        | 0.21%   |
| fr_CA   | 1        | 0.21%   |
| fr_BE   | 1        | 0.21%   |
| es_VE   | 1        | 0.21%   |
| es_SV   | 1        | 0.21%   |
| es_PA   | 1        | 0.21%   |
| es_EC   | 1        | 0.21%   |
| en_ZA   | 1        | 0.21%   |
| en_PH   | 1        | 0.21%   |
| en_IE   | 1        | 0.21%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 279      | 59.24%  |
| EFI  | 192      | 40.76%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 434      | 93.13%  |
| Btrfs    | 15       | 3.22%   |
| Unknown  | 6        | 1.29%   |
| Xfs      | 5        | 1.07%   |
| Tmpfs    | 3        | 0.64%   |
| Overlay  | 2        | 0.43%   |
| Reiserfs | 1        | 0.21%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 403      | 86.11%  |
| GPT     | 43       | 9.19%   |
| MBR     | 22       | 4.7%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 433      | 93.52%  |
| Yes       | 30       | 6.48%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 403      | 86.67%  |
| Yes       | 62       | 13.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 116      | 25.16%  |
| Gigabyte Technology | 79       | 17.14%  |
| MSI                 | 51       | 11.06%  |
| Hewlett-Packard     | 41       | 8.89%   |
| Dell                | 36       | 7.81%   |
| ASRock              | 31       | 6.72%   |
| Intel               | 13       | 2.82%   |
| Lenovo              | 12       | 2.6%    |
| Acer                | 12       | 2.6%    |
| Biostar             | 9        | 1.95%   |
| Foxconn             | 7        | 1.52%   |
| Pegatron            | 6        | 1.3%    |
| Apple               | 6        | 1.3%    |
| Unknown             | 6        | 1.3%    |
| Fujitsu             | 4        | 0.87%   |
| ECS                 | 4        | 0.87%   |
| MACHINIST           | 3        | 0.65%   |
| Wibtek              | 2        | 0.43%   |
| Inventec            | 2        | 0.43%   |
| EVGA                | 2        | 0.43%   |
| AZW                 | 2        | 0.43%   |
| Wortmann AG         | 1        | 0.22%   |
| T-bao               | 1        | 0.22%   |
| SYS                 | 1        | 0.22%   |
| Shuttle             | 1        | 0.22%   |
| Packard Bell        | 1        | 0.22%   |
| LORD ELECTRONICS    | 1        | 0.22%   |
| LattePanda          | 1        | 0.22%   |
| Kraftway            | 1        | 0.22%   |
| Jetway              | 1        | 0.22%   |
| IceWhale Technology | 1        | 0.22%   |
| HC Technology.      | 1        | 0.22%   |
| FIRICH              | 1        | 0.22%   |
| eMachines           | 1        | 0.22%   |
| BESSTAR Tech        | 1        | 0.22%   |
| AOpen               | 1        | 0.22%   |
| AMI                 | 1        | 0.22%   |
| Alienware           | 1        | 0.22%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| ASUS All Series                   | 10       | 2.17%   |
| Unknown                           | 6        | 1.3%    |
| ASUS PRIME A320M-K                | 5        | 1.08%   |
| MSI MS-7C02                       | 4        | 0.87%   |
| Dell OptiPlex 790                 | 4        | 0.87%   |
| ASUS P8H61-M LX3 R2.0             | 4        | 0.87%   |
| MSI MS-7B84                       | 3        | 0.65%   |
| ASUS ROG STRIX B350-F GAMING      | 3        | 0.65%   |
| Wibtek H61-M HDMI2                | 2        | 0.43%   |
| Pegatron IPMH61P1                 | 2        | 0.43%   |
| MSI MS-7C52                       | 2        | 0.43%   |
| MSI MS-7C35                       | 2        | 0.43%   |
| MSI MS-7B86                       | 2        | 0.43%   |
| MSI MS-7B17                       | 2        | 0.43%   |
| MSI MS-7817                       | 2        | 0.43%   |
| MSI MS-7721                       | 2        | 0.43%   |
| Intel Jasper Lake Client Platform | 2        | 0.43%   |
| Intel H61                         | 2        | 0.43%   |
| HP ProDesk 600 G1 SFF             | 2        | 0.43%   |
| HP Compaq Pro 6300 MT             | 2        | 0.43%   |
| HP Compaq Elite 8300 SFF          | 2        | 0.43%   |
| Gigabyte Z390 UD                  | 2        | 0.43%   |
| Gigabyte H61M-S1                  | 2        | 0.43%   |
| Gigabyte H61M-DS2                 | 2        | 0.43%   |
| Gigabyte GA-990FXA-UD3            | 2        | 0.43%   |
| Gigabyte AB350-Gaming 3           | 2        | 0.43%   |
| Gigabyte A320M-S2H V2             | 2        | 0.43%   |
| ECS H55H-M                        | 2        | 0.43%   |
| Dell Precision WorkStation T3500  | 2        | 0.43%   |
| Dell OptiPlex 960                 | 2        | 0.43%   |
| Dell OptiPlex 9010                | 2        | 0.43%   |
| Dell OptiPlex 5040                | 2        | 0.43%   |
| Dell OptiPlex 3070                | 2        | 0.43%   |
| ASUS TUF Gaming B550M-PLUS        | 2        | 0.43%   |
| ASUS PRIME Z390-A                 | 2        | 0.43%   |
| ASUS PRIME H310M-E R2.0           | 2        | 0.43%   |
| ASUS P8H61-MX R2.0                | 2        | 0.43%   |
| ASUS H110M-A/M.2                  | 2        | 0.43%   |
| ASRock B450M-HDV R4.0             | 2        | 0.43%   |
| Apple MacPro5,1                   | 2        | 0.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 24       | 5.21%   |
| Dell OptiPlex          | 23       | 4.99%   |
| ASUS ROG               | 17       | 3.69%   |
| HP Compaq              | 11       | 2.39%   |
| ASUS TUF               | 11       | 2.39%   |
| Lenovo ThinkCentre     | 10       | 2.17%   |
| ASUS All               | 10       | 2.17%   |
| Acer Aspire            | 7        | 1.52%   |
| Dell Precision         | 6        | 1.3%    |
| ASUS P8H61-M           | 6        | 1.3%    |
| Unknown                | 6        | 1.3%    |
| Gigabyte Z390          | 5        | 1.08%   |
| MSI MS-7C02            | 4        | 0.87%   |
| HP ProDesk             | 4        | 0.87%   |
| HP EliteDesk           | 4        | 0.87%   |
| Fujitsu ESPRIMO        | 4        | 0.87%   |
| MSI MS-7B84            | 3        | 0.65%   |
| HP Pavilion            | 3        | 0.65%   |
| Gigabyte X570          | 3        | 0.65%   |
| Gigabyte H310M         | 3        | 0.65%   |
| Gigabyte B450M         | 3        | 0.65%   |
| Gigabyte A320M-S2H     | 3        | 0.65%   |
| ASUS SABERTOOTH        | 3        | 0.65%   |
| ASUS M5A78L-M          | 3        | 0.65%   |
| Acer Veriton           | 3        | 0.65%   |
| Wibtek H61-M           | 2        | 0.43%   |
| Pegatron IPMH61P1      | 2        | 0.43%   |
| MSI MS-7C52            | 2        | 0.43%   |
| MSI MS-7C35            | 2        | 0.43%   |
| MSI MS-7B86            | 2        | 0.43%   |
| MSI MS-7B17            | 2        | 0.43%   |
| MSI MS-7817            | 2        | 0.43%   |
| MSI MS-7721            | 2        | 0.43%   |
| Lenovo IdeaCentre      | 2        | 0.43%   |
| Intel Jasper           | 2        | 0.43%   |
| Intel H61              | 2        | 0.43%   |
| Gigabyte H61M-S1       | 2        | 0.43%   |
| Gigabyte H61M-DS2      | 2        | 0.43%   |
| Gigabyte GA-990FXA-UD3 | 2        | 0.43%   |
| Gigabyte B560M         | 2        | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 56       | 12.15%  |
| 2012 | 55       | 11.93%  |
| 2013 | 47       | 10.2%   |
| 2011 | 37       | 8.03%   |
| 2010 | 32       | 6.94%   |
| 2019 | 31       | 6.72%   |
| 2017 | 29       | 6.29%   |
| 2014 | 26       | 5.64%   |
| 2020 | 25       | 5.42%   |
| 2009 | 25       | 5.42%   |
| 2021 | 21       | 4.56%   |
| 2015 | 21       | 4.56%   |
| 2016 | 20       | 4.34%   |
| 2008 | 17       | 3.69%   |
| 2022 | 8        | 1.74%   |
| 2007 | 7        | 1.52%   |
| 2006 | 2        | 0.43%   |
| 2023 | 1        | 0.22%   |
| 2005 | 1        | 0.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 461      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 445      | 96.53%  |
| Enabled  | 16       | 3.47%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 461      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 109      | 23.44%  |
| 8.01-16.0   | 94       | 20.22%  |
| 4.01-8.0    | 89       | 19.14%  |
| 32.01-64.0  | 73       | 15.7%   |
| 3.01-4.0    | 64       | 13.76%  |
| 64.01-256.0 | 12       | 2.58%   |
| 24.01-32.0  | 10       | 2.15%   |
| 1.01-2.0    | 9        | 1.94%   |
| 2.01-3.0    | 5        | 1.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 175      | 33.72%  |
| 2.01-3.0   | 164      | 31.6%   |
| 4.01-8.0   | 81       | 15.61%  |
| 3.01-4.0   | 74       | 14.26%  |
| 8.01-16.0  | 13       | 2.5%    |
| 0.51-1.0   | 11       | 2.12%   |
| 32.01-64.0 | 1        | 0.19%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 174      | 36.55%  |
| 1      | 173      | 36.34%  |
| 3      | 67       | 14.08%  |
| 4      | 32       | 6.72%   |
| 5      | 17       | 3.57%   |
| 6      | 6        | 1.26%   |
| 7      | 4        | 0.84%   |
| 0      | 2        | 0.42%   |
| 8      | 1        | 0.21%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 263      | 55.72%  |
| Yes       | 209      | 44.28%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 457      | 99.13%  |
| No        | 4        | 0.87%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 243      | 51.81%  |
| Yes       | 226      | 48.19%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 301      | 64.32%  |
| Yes       | 167      | 35.68%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 64       | 13.82%  |
| Germany     | 49       | 10.58%  |
| Russia      | 31       | 6.7%    |
| Brazil      | 31       | 6.7%    |
| UK          | 23       | 4.97%   |
| Canada      | 22       | 4.75%   |
| Spain       | 19       | 4.1%    |
| Italy       | 17       | 3.67%   |
| France      | 16       | 3.46%   |
| Indonesia   | 11       | 2.38%   |
| Poland      | 9        | 1.94%   |
| Mexico      | 9        | 1.94%   |
| India       | 9        | 1.94%   |
| Argentina   | 9        | 1.94%   |
| Turkey      | 8        | 1.73%   |
| Netherlands | 8        | 1.73%   |
| Austria     | 8        | 1.73%   |
| Australia   | 8        | 1.73%   |
| Portugal    | 6        | 1.3%    |
| Switzerland | 5        | 1.08%   |
| Sweden      | 5        | 1.08%   |
| Greece      | 5        | 1.08%   |
| Venezuela   | 4        | 0.86%   |
| Ukraine     | 4        | 0.86%   |
| Japan       | 4        | 0.86%   |
| Finland     | 4        | 0.86%   |
| Egypt       | 4        | 0.86%   |
| Czechia     | 4        | 0.86%   |
| Colombia    | 4        | 0.86%   |
| Malaysia    | 3        | 0.65%   |
| Israel      | 3        | 0.65%   |
| Hong Kong   | 3        | 0.65%   |
| Bulgaria    | 3        | 0.65%   |
| Thailand    | 2        | 0.43%   |
| Romania     | 2        | 0.43%   |
| Philippines | 2        | 0.43%   |
| Norway      | 2        | 0.43%   |
| Kenya       | 2        | 0.43%   |
| Ireland     | 2        | 0.43%   |
| Iran        | 2        | 0.43%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Moscow         | 10       | 2.02%   |
| Warsaw         | 5        | 1.01%   |
| Vienna         | 5        | 1.01%   |
| Sao Paulo      | 4        | 0.81%   |
| Rio de Janeiro | 4        | 0.81%   |
| Paris          | 4        | 0.81%   |
| Munich         | 4        | 0.81%   |
| Fortaleza      | 4        | 0.81%   |
| Berlin         | 4        | 0.81%   |
| Toronto        | 3        | 0.61%   |
| Sofia          | 3        | 0.61%   |
| Novosibirsk    | 3        | 0.61%   |
| Montreal       | 3        | 0.61%   |
| Melbourne      | 3        | 0.61%   |
| Los Angeles    | 3        | 0.61%   |
| Istanbul       | 3        | 0.61%   |
| Hamburg        | 3        | 0.61%   |
| Caslano        | 3        | 0.61%   |
| Brisbane       | 3        | 0.61%   |
| Tucson         | 2        | 0.4%    |
| Tangerang      | 2        | 0.4%    |
| Sydney         | 2        | 0.4%    |
| Stuttgart      | 2        | 0.4%    |
| St Petersburg  | 2        | 0.4%    |
| Saskatoon      | 2        | 0.4%    |
| Sarajevo       | 2        | 0.4%    |
| Sao Vicente    | 2        | 0.4%    |
| Santiago       | 2        | 0.4%    |
| Rome           | 2        | 0.4%    |
| Petah Tikva    | 2        | 0.4%    |
| Nuremberg      | 2        | 0.4%    |
| Nairobi        | 2        | 0.4%    |
| Morelia        | 2        | 0.4%    |
| Montenegro     | 2        | 0.4%    |
| Milan          | 2        | 0.4%    |
| Mexico City    | 2        | 0.4%    |
| Madrid         | 2        | 0.4%    |
| Kazan’       | 2        | 0.4%    |
| George Town    | 2        | 0.4%    |
| Dublin         | 2        | 0.4%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 154      | 228    | 18.67%  |
| Seagate                     | 144      | 211    | 17.45%  |
| Samsung Electronics         | 112      | 190    | 13.58%  |
| Kingston                    | 57       | 82     | 6.91%   |
| Toshiba                     | 42       | 68     | 5.09%   |
| SanDisk                     | 42       | 46     | 5.09%   |
| Crucial                     | 37       | 51     | 4.48%   |
| Hitachi                     | 26       | 30     | 3.15%   |
| A-DATA Technology           | 14       | 15     | 1.7%    |
| Unknown                     | 12       | 22     | 1.45%   |
| China                       | 12       | 14     | 1.45%   |
| Intel                       | 11       | 11     | 1.33%   |
| PNY                         | 9        | 15     | 1.09%   |
| Micron/Crucial Technology   | 9        | 15     | 1.09%   |
| HGST                        | 9        | 13     | 1.09%   |
| Phison                      | 7        | 8      | 0.85%   |
| OCZ                         | 7        | 12     | 0.85%   |
| Team                        | 6        | 9      | 0.73%   |
| Micron Technology           | 6        | 7      | 0.73%   |
| Corsair                     | 6        | 6      | 0.73%   |
| Transcend                   | 5        | 6      | 0.61%   |
| SPCC                        | 5        | 5      | 0.61%   |
| Patriot                     | 5        | 5      | 0.61%   |
| Netac                       | 4        | 5      | 0.48%   |
| Maxtor                      | 4        | 4      | 0.48%   |
| Intenso                     | 4        | 5      | 0.48%   |
| Gigabyte Technology         | 4        | 4      | 0.48%   |
| SK hynix                    | 3        | 3      | 0.36%   |
| Silicon Motion              | 3        | 3      | 0.36%   |
| Realtek Semiconductor       | 3        | 4      | 0.36%   |
| Plextor                     | 3        | 5      | 0.36%   |
| LITEON                      | 3        | 3      | 0.36%   |
| JMicron Technology          | 3        | 3      | 0.36%   |
| HUSKY                       | 3        | 5      | 0.36%   |
| ASMT                        | 3        | 3      | 0.36%   |
| Unknown                     | 3        | 3      | 0.36%   |
| MAXIO Technology (Hangzhou) | 2        | 2      | 0.24%   |
| KingSpec                    | 2        | 2      | 0.24%   |
| KingFast                    | 2        | 2      | 0.24%   |
| HS-SSD-C100                 | 2        | 2      | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 20       | 2.13%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 13       | 1.38%   |
| Seagate ST500DM002-1BD142 500GB                     | 12       | 1.28%   |
| Samsung SSD 850 EVO 250GB                           | 12       | 1.28%   |
| Samsung NVMe SSD Drive 500GB                        | 12       | 1.28%   |
| Toshiba DT01ACA050 500GB                            | 9        | 0.96%   |
| Seagate ST1000DM003-1ER162 1TB                      | 9        | 0.96%   |
| Kingston SA400S37120G 120GB SSD                     | 9        | 0.96%   |
| Toshiba DT01ACA100 1TB                              | 8        | 0.85%   |
| Samsung SSD 860 EVO 1TB                             | 8        | 0.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 8        | 0.85%   |
| Crucial CT240BX500SSD1 240GB                        | 8        | 0.85%   |
| Seagate ST1000DM010-2EP102 1TB                      | 7        | 0.75%   |
| Samsung NVMe SSD Drive 1TB                          | 7        | 0.75%   |
| Kingston SV300S37A120G 120GB SSD                    | 7        | 0.75%   |
| Seagate ST3500418AS 500GB                           | 6        | 0.64%   |
| Seagate ST31000528AS 1TB                            | 6        | 0.64%   |
| Seagate ST2000DM008-2FR102 2TB                      | 6        | 0.64%   |
| Samsung SSD 860 EVO 250GB                           | 6        | 0.64%   |
| Samsung SSD 840 EVO 250GB                           | 6        | 0.64%   |
| WDC WD5000AAKX-00ERMA0 500GB                        | 5        | 0.53%   |
| WDC WD10EZEX-60WN4A0 1TB                            | 5        | 0.53%   |
| Toshiba HDWD110 1TB                                 | 5        | 0.53%   |
| SanDisk NVMe SSD Drive 500GB                        | 5        | 0.53%   |
| Samsung SSD 860 EVO 500GB                           | 5        | 0.53%   |
| Samsung SSD 850 EVO 500GB                           | 5        | 0.53%   |
| WDC WD5000AAKX-001CA0 500GB                         | 4        | 0.43%   |
| WDC WD5000AAKS-00UU3A0 500GB                        | 4        | 0.43%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 4        | 0.43%   |
| Unknown SD/MMC 2GB                                  | 4        | 0.43%   |
| Unknown M.S./M.S.Pro/HG 16GB                        | 4        | 0.43%   |
| Toshiba DT01ACA300 3TB                              | 4        | 0.43%   |
| Seagate ST3500312CS 500GB                           | 4        | 0.43%   |
| Seagate ST3160815AS 160GB                           | 4        | 0.43%   |
| Seagate ST1000DM003-1CH162 1TB                      | 4        | 0.43%   |
| SanDisk SSD PLUS 480GB                              | 4        | 0.43%   |
| SanDisk SSD PLUS 240GB                              | 4        | 0.43%   |
| Samsung SSD 850 PRO 256GB                           | 4        | 0.43%   |
| Samsung SSD 840 EVO 120GB                           | 4        | 0.43%   |
| Phison NVMe SSD Drive 1TB                           | 4        | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 141      | 202    | 36.72%  |
| WDC                 | 132      | 190    | 34.38%  |
| Toshiba             | 41       | 66     | 10.68%  |
| Hitachi             | 26       | 30     | 6.77%   |
| Samsung Electronics | 25       | 29     | 6.51%   |
| HGST                | 9        | 13     | 2.34%   |
| Unknown             | 3        | 4      | 0.78%   |
| Maxtor              | 3        | 3      | 0.78%   |
| Hewlett-Packard     | 1        | 1      | 0.26%   |
| Fujitsu             | 1        | 1      | 0.26%   |
| ASMT                | 1        | 1      | 0.26%   |
| Apple               | 1        | 1      | 0.26%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 66       | 104    | 19.58%  |
| Kingston            | 51       | 62     | 15.13%  |
| Crucial             | 36       | 49     | 10.68%  |
| SanDisk             | 29       | 32     | 8.61%   |
| WDC                 | 21       | 30     | 6.23%   |
| A-DATA Technology   | 13       | 14     | 3.86%   |
| China               | 12       | 14     | 3.56%   |
| PNY                 | 9        | 15     | 2.67%   |
| OCZ                 | 7        | 12     | 2.08%   |
| Team                | 6        | 9      | 1.78%   |
| Corsair             | 6        | 6      | 1.78%   |
| Transcend           | 5        | 6      | 1.48%   |
| SPCC                | 5        | 5      | 1.48%   |
| Patriot             | 5        | 5      | 1.48%   |
| Intel               | 5        | 5      | 1.48%   |
| Intenso             | 4        | 5      | 1.19%   |
| Plextor             | 3        | 5      | 0.89%   |
| Micron Technology   | 3        | 3      | 0.89%   |
| LITEON              | 3        | 3      | 0.89%   |
| HUSKY               | 3        | 5      | 0.89%   |
| Gigabyte Technology | 3        | 3      | 0.89%   |
| SK hynix            | 2        | 2      | 0.59%   |
| Seagate             | 2        | 4      | 0.59%   |
| Netac               | 2        | 2      | 0.59%   |
| KingSpec            | 2        | 2      | 0.59%   |
| GOODRAM             | 2        | 5      | 0.59%   |
| ASMT                | 2        | 2      | 0.59%   |
| Apacer              | 2        | 2      | 0.59%   |
| Unknown             | 2        | 2      | 0.59%   |
| XrayDisk            | 1        | 2      | 0.3%    |
| WDC WDS             | 1        | 1      | 0.3%    |
| Verbatim            | 1        | 1      | 0.3%    |
| Toshiba             | 1        | 1      | 0.3%    |
| tigo                | 1        | 1      | 0.3%    |
| SD                  | 1        | 1      | 0.3%    |
| ROG                 | 1        | 1      | 0.3%    |
| OWC                 | 1        | 1      | 0.3%    |
| OCZ-VERTEX3         | 1        | 1      | 0.3%    |
| OCZ-VERTEX2         | 1        | 3      | 0.3%    |
| NGFF                | 1        | 1      | 0.3%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 307      | 541    | 43.36%  |
| SSD     | 279      | 444    | 39.41%  |
| NVMe    | 97       | 151    | 13.7%   |
| Unknown | 22       | 35     | 3.11%   |
| MMC     | 3        | 3      | 0.42%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 434      | 975    | 76.81%  |
| NVMe | 97       | 151    | 17.17%  |
| SAS  | 31       | 45     | 5.49%   |
| MMC  | 3        | 3      | 0.53%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 344      | 605    | 58.11%  |
| 0.51-1.0   | 165      | 260    | 27.87%  |
| 1.01-2.0   | 40       | 55     | 6.76%   |
| 2.01-3.0   | 20       | 37     | 3.38%   |
| 3.01-4.0   | 13       | 14     | 2.2%    |
| 4.01-10.0  | 10       | 14     | 1.69%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 157      | 32.44%  |
| 251-500        | 107      | 22.11%  |
| 501-1000       | 84       | 17.36%  |
| 1001-2000      | 47       | 9.71%   |
| 51-100         | 29       | 5.99%   |
| More than 3000 | 21       | 4.34%   |
| 21-50          | 20       | 4.13%   |
| 2001-3000      | 16       | 3.31%   |
| 1-20           | 3        | 0.62%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 188      | 36.29%  |
| 21-50          | 99       | 19.11%  |
| 101-250        | 66       | 12.74%  |
| 51-100         | 66       | 12.74%  |
| 251-500        | 38       | 7.34%   |
| 501-1000       | 28       | 5.41%   |
| 1001-2000      | 21       | 4.05%   |
| More than 3000 | 7        | 1.35%   |
| 2001-3000      | 5        | 0.97%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC WD5000AAKX-22ERMA0 500GB       | 1        | 1      | 3.7%    |
| WDC WD5000AAKX-221CA1 500GB        | 1        | 1      | 3.7%    |
| WDC WD5000AAKX-00ERMA0 500GB       | 1        | 1      | 3.7%    |
| WDC WD5000AAKS-00UU3A0 500GB       | 1        | 1      | 3.7%    |
| WDC WD3200AAJS-56B4A0 320GB        | 1        | 1      | 3.7%    |
| WDC WD10EZEX-00KUWA0 1TB           | 1        | 1      | 3.7%    |
| WDC WD1003FZEX-00MK2A0 1TB         | 1        | 1      | 3.7%    |
| Seagate ST500DM002-1BD142 500GB    | 1        | 1      | 3.7%    |
| Seagate ST3500414CS 500GB          | 1        | 2      | 3.7%    |
| Seagate ST3500312CS 500GB          | 1        | 1      | 3.7%    |
| Seagate ST3320613AS 320GB          | 1        | 1      | 3.7%    |
| Seagate ST3250312AS 250GB          | 1        | 1      | 3.7%    |
| Seagate ST3160813AS 160GB          | 1        | 1      | 3.7%    |
| Seagate ST3160318AS 160GB          | 1        | 1      | 3.7%    |
| Seagate ST2000DM006-2DM164 2TB     | 1        | 1      | 3.7%    |
| SanDisk SSD PLUS 240GB             | 1        | 1      | 3.7%    |
| Samsung Electronics HD322GJ 320GB  | 1        | 1      | 3.7%    |
| Samsung Electronics HD204UI 2TB    | 1        | 1      | 3.7%    |
| Samsung Electronics HD160JJ/ 160GB | 1        | 1      | 3.7%    |
| OCZ VECTOR150 240GB SSD            | 1        | 1      | 3.7%    |
| Kingston SA400S37120G 120GB SSD    | 1        | 1      | 3.7%    |
| Hitachi HTS725050A7E630 500GB      | 1        | 1      | 3.7%    |
| Hitachi HTS542525K9SA00 250GB      | 1        | 1      | 3.7%    |
| Hitachi HDT721064SLA360 640GB      | 1        | 1      | 3.7%    |
| Hitachi HDS721010CLA332 1TB        | 1        | 1      | 3.7%    |
| HGST HUS724030ALA640 3TB           | 1        | 1      | 3.7%    |
| Crucial CT256M550SSD1 256GB        | 1        | 1      | 3.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 8        | 9      | 29.63%  |
| WDC                 | 7        | 7      | 25.93%  |
| Hitachi             | 4        | 4      | 14.81%  |
| Samsung Electronics | 3        | 3      | 11.11%  |
| SanDisk             | 1        | 1      | 3.7%    |
| OCZ                 | 1        | 1      | 3.7%    |
| Kingston            | 1        | 1      | 3.7%    |
| HGST                | 1        | 1      | 3.7%    |
| Crucial             | 1        | 1      | 3.7%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 8        | 9      | 34.78%  |
| WDC                 | 7        | 7      | 30.43%  |
| Hitachi             | 4        | 4      | 17.39%  |
| Samsung Electronics | 3        | 3      | 13.04%  |
| HGST                | 1        | 1      | 4.35%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 20       | 24     | 83.33%  |
| SSD  | 4        | 4      | 16.67%  |

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
| Detected | 415      | 1033   | 84.87%  |
| Works    | 51       | 113    | 10.43%  |
| Malfunc  | 23       | 28     | 4.7%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 320      | 52.29%  |
| AMD                          | 124      | 20.26%  |
| Samsung Electronics          | 45       | 7.35%   |
| ASMedia Technology           | 18       | 2.94%   |
| SanDisk                      | 16       | 2.61%   |
| Nvidia                       | 15       | 2.45%   |
| Marvell Technology Group     | 12       | 1.96%   |
| JMicron Technology           | 12       | 1.96%   |
| Micron/Crucial Technology    | 10       | 1.63%   |
| Phison Electronics           | 8        | 1.31%   |
| Kingston Technology Company  | 8        | 1.31%   |
| Realtek Semiconductor        | 4        | 0.65%   |
| Silicon Motion               | 3        | 0.49%   |
| Micron Technology            | 3        | 0.49%   |
| LSI Logic / Symbios Logic    | 3        | 0.49%   |
| Seagate Technology           | 2        | 0.33%   |
| MAXIO Technology (Hangzhou)  | 2        | 0.33%   |
| ADATA Technology             | 2        | 0.33%   |
| VIA Technologies             | 1        | 0.16%   |
| Toshiba America Info Systems | 1        | 0.16%   |
| SK hynix                     | 1        | 0.16%   |
| Silicon Image                | 1        | 0.16%   |
| Broadcom / LSI               | 1        | 0.16%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 80       | 10.26%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 40       | 5.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 40       | 5.13%   |
| AMD 400 Series Chipset SATA Controller                                                  | 31       | 3.97%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 26       | 3.33%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 25       | 3.21%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 22       | 2.82%   |
| Intel SATA Controller [RAID mode]                                                       | 21       | 2.69%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 21       | 2.69%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 21       | 2.69%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 21       | 2.69%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 20       | 2.56%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 17       | 2.18%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 17       | 2.18%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 16       | 2.05%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 13       | 1.67%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 12       | 1.54%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 12       | 1.54%   |
| AMD 300 Series Chipset SATA Controller                                                  | 12       | 1.54%   |
| AMD FCH SATA Controller D                                                               | 11       | 1.41%   |
| Nvidia MCP61 SATA Controller                                                            | 8        | 1.03%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 8        | 1.03%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 8        | 1.03%   |
| AMD 500 Series Chipset SATA Controller                                                  | 8        | 1.03%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 7        | 0.9%    |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 7        | 0.9%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 6        | 0.77%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                                | 6        | 0.77%   |
| JMicron JMB368 IDE controller                                                           | 6        | 0.77%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 6        | 0.77%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 6        | 0.77%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 6        | 0.77%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 6        | 0.77%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 6        | 0.77%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 6        | 0.77%   |
| Intel SSD 660P Series                                                                   | 5        | 0.64%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 5        | 0.64%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 5        | 0.64%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 4        | 0.51%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 4        | 0.51%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 357      | 58.91%  |
| IDE  | 113      | 18.65%  |
| NVMe | 98       | 16.17%  |
| RAID | 33       | 5.45%   |
| SAS  | 3        | 0.5%    |
| SCSI | 2        | 0.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 324      | 70.28%  |
| AMD    | 137      | 29.72%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-2400 CPU @ 3.10GHz            | 12       | 2.6%    |
| AMD Ryzen 5 3600 6-Core Processor           | 11       | 2.39%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 8        | 1.74%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 7        | 1.52%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 7        | 1.52%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 6        | 1.3%    |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 5        | 1.08%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 5        | 1.08%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 5        | 1.08%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 5        | 1.08%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 5        | 1.08%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 5        | 1.08%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 5        | 1.08%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 4        | 0.87%   |
| Intel Core i7-3770S CPU @ 3.10GHz           | 4        | 0.87%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 4        | 0.87%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 4        | 0.87%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 4        | 0.87%   |
| Intel Core i5-3330S CPU @ 2.70GHz           | 4        | 0.87%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 4        | 0.87%   |
| Intel Core i3-9100 CPU @ 3.60GHz            | 4        | 0.87%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 4        | 0.87%   |
| Intel Core i3 CPU 530 @ 2.93GHz             | 4        | 0.87%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 4        | 0.87%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 4        | 0.87%   |
| AMD FX-8350 Eight-Core Processor            | 4        | 0.87%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 3        | 0.65%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 3        | 0.65%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 3        | 0.65%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 3        | 0.65%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 3        | 0.65%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 3        | 0.65%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 3        | 0.65%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 3        | 0.65%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 3        | 0.65%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 3        | 0.65%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 3        | 0.65%   |
| Intel Core i5-2320 CPU @ 3.00GHz            | 3        | 0.65%   |
| Intel Core i5 CPU 760 @ 2.80GHz             | 3        | 0.65%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 3        | 0.65%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 96       | 20.82%  |
| Intel Core i7           | 71       | 15.4%   |
| Intel Core i3           | 40       | 8.68%   |
| AMD Ryzen 5             | 38       | 8.24%   |
| Intel Xeon              | 29       | 6.29%   |
| Intel Celeron           | 20       | 4.34%   |
| AMD Ryzen 7             | 18       | 3.9%    |
| Intel Core 2 Quad       | 13       | 2.82%   |
| AMD FX                  | 13       | 2.82%   |
| Other                   | 12       | 2.6%    |
| Intel Pentium Dual-Core | 10       | 2.17%   |
| Intel Core 2 Duo        | 10       | 2.17%   |
| AMD Ryzen 9             | 10       | 2.17%   |
| AMD Ryzen 3             | 10       | 2.17%   |
| AMD Phenom II X4        | 9        | 1.95%   |
| Intel Pentium           | 8        | 1.74%   |
| Intel Core i9           | 7        | 1.52%   |
| AMD A8                  | 7        | 1.52%   |
| AMD Athlon II X4        | 4        | 0.87%   |
| AMD Athlon II X2        | 4        | 0.87%   |
| Intel Pentium Dual      | 3        | 0.65%   |
| Intel Atom              | 3        | 0.65%   |
| AMD Athlon              | 3        | 0.65%   |
| AMD A4                  | 3        | 0.65%   |
| AMD A10                 | 3        | 0.65%   |
| AMD Phenom              | 2        | 0.43%   |
| AMD G                   | 2        | 0.43%   |
| Intel Pentium Gold      | 1        | 0.22%   |
| Intel Pentium D         | 1        | 0.22%   |
| Intel Pentium 4         | 1        | 0.22%   |
| Intel Core m3           | 1        | 0.22%   |
| AMD Sempron             | 1        | 0.22%   |
| AMD Ryzen Threadripper  | 1        | 0.22%   |
| AMD Ryzen 5 PRO         | 1        | 0.22%   |
| AMD Phenom II X6        | 1        | 0.22%   |
| AMD E1                  | 1        | 0.22%   |
| AMD Athlon X4           | 1        | 0.22%   |
| AMD Athlon II X3        | 1        | 0.22%   |
| AMD Athlon 64 X2        | 1        | 0.22%   |
| AMD A6                  | 1        | 0.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 220      | 47.41%  |
| 2      | 104      | 22.41%  |
| 6      | 58       | 12.5%   |
| 8      | 45       | 9.7%    |
| 12     | 13       | 2.8%    |
| 1      | 10       | 2.16%   |
| 3      | 8        | 1.72%   |
| 16     | 4        | 0.86%   |
| 10     | 1        | 0.22%   |
| 5      | 1        | 0.22%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 454      | 98.48%  |
| 2      | 7        | 1.52%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 246      | 53.13%  |
| 1      | 217      | 46.87%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 457      | 98.92%  |
| Unknown        | 5        | 1.08%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 108      | 22.74%  |
| 0x206a7    | 44       | 9.26%   |
| 0x306c3    | 42       | 8.84%   |
| 0x306a9    | 30       | 6.32%   |
| 0x08701021 | 17       | 3.58%   |
| 0x1067a    | 14       | 2.95%   |
| 0x906ea    | 13       | 2.74%   |
| 0x906e9    | 12       | 2.53%   |
| 0x0800820d | 11       | 2.32%   |
| 0x906ed    | 9        | 1.89%   |
| 0x506e3    | 9        | 1.89%   |
| 0x08108109 | 9        | 1.89%   |
| 0x906eb    | 8        | 1.68%   |
| 0x06000852 | 8        | 1.68%   |
| 0x010000c8 | 8        | 1.68%   |
| 0x6fb      | 7        | 1.47%   |
| 0x106e5    | 6        | 1.26%   |
| 0x206d7    | 5        | 1.05%   |
| 0x20652    | 5        | 1.05%   |
| 0x10676    | 5        | 1.05%   |
| 0x0a201016 | 5        | 1.05%   |
| 0x08701013 | 5        | 1.05%   |
| 0xa0671    | 4        | 0.84%   |
| 0xa0655    | 4        | 0.84%   |
| 0x106a5    | 4        | 0.84%   |
| 0x08001138 | 4        | 0.84%   |
| 0x06003106 | 4        | 0.84%   |
| 0x06001119 | 4        | 0.84%   |
| 0x0600063e | 4        | 0.84%   |
| 0x010000db | 4        | 0.84%   |
| 0xa0653    | 3        | 0.63%   |
| 0x306e4    | 3        | 0.63%   |
| 0x206c2    | 3        | 0.63%   |
| 0x20655    | 3        | 0.63%   |
| 0x0810100b | 3        | 0.63%   |
| 0x0600611a | 3        | 0.63%   |
| 0x906ec    | 2        | 0.42%   |
| 0x906c0    | 2        | 0.42%   |
| 0x6fd      | 2        | 0.42%   |
| 0x406c4    | 2        | 0.42%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| KabyLake         | 59       | 12.8%   |
| SandyBridge      | 56       | 12.15%  |
| Haswell          | 56       | 12.15%  |
| IvyBridge        | 41       | 8.89%   |
| Zen 2            | 25       | 5.42%   |
| Penryn           | 25       | 5.42%   |
| Zen+             | 24       | 5.21%   |
| K10              | 22       | 4.77%   |
| Zen              | 18       | 3.9%    |
| Skylake          | 15       | 3.25%   |
| Core             | 14       | 3.04%   |
| Zen 3            | 13       | 2.82%   |
| Piledriver       | 13       | 2.82%   |
| Nehalem          | 13       | 2.82%   |
| Westmere         | 12       | 2.6%    |
| CometLake        | 9        | 1.95%   |
| Steamroller      | 7        | 1.52%   |
| Unknown          | 6        | 1.3%    |
| Excavator        | 5        | 1.08%   |
| Silvermont       | 4        | 0.87%   |
| Icelake          | 4        | 0.87%   |
| Bulldozer        | 4        | 0.87%   |
| Tremont          | 2        | 0.43%   |
| NetBurst         | 2        | 0.43%   |
| Goldmont plus    | 2        | 0.43%   |
| Bobcat           | 2        | 0.43%   |
| TigerLake        | 1        | 0.22%   |
| Puma             | 1        | 0.22%   |
| K8 Hammer        | 1        | 0.22%   |
| K10 Llano        | 1        | 0.22%   |
| Goldmont         | 1        | 0.22%   |
| Broadwell        | 1        | 0.22%   |
| Bonnell          | 1        | 0.22%   |
| Alderlake Hybrid | 1        | 0.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Nvidia           | 184      | 37.02%  |
| AMD              | 159      | 31.99%  |
| Intel            | 152      | 30.58%  |
| Conexant Systems | 1        | 0.2%    |
| ATI Technologies | 1        | 0.2%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 28       | 5.46%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 26       | 5.07%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 23       | 4.48%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 17       | 3.31%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 12       | 2.34%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 12       | 2.34%   |
| Intel HD Graphics 530                                                       | 9        | 1.75%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 8        | 1.56%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 8        | 1.56%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 7        | 1.36%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 7        | 1.36%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 7        | 1.36%   |
| Nvidia GK208B [GeForce GT 710]                                              | 7        | 1.36%   |
| Intel HD Graphics 630                                                       | 7        | 1.36%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 7        | 1.36%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 7        | 1.36%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 6        | 1.17%   |
| Nvidia GT218 [GeForce 210]                                                  | 6        | 1.17%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 6        | 1.17%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 6        | 1.17%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 6        | 1.17%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 5        | 0.97%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 5        | 0.97%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 5        | 0.97%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 5        | 0.97%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 5        | 0.97%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 5        | 0.97%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 4        | 0.78%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 4        | 0.78%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 4        | 0.78%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 4        | 0.78%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 4        | 0.78%   |
| Nvidia GK208B [GeForce GT 730]                                              | 4        | 0.78%   |
| Nvidia GF119 [GeForce GT 610]                                               | 4        | 0.78%   |
| Nvidia GF108 [GeForce GT 730]                                               | 4        | 0.78%   |
| Nvidia GF108 [GeForce GT 430]                                               | 4        | 0.78%   |
| Intel Core Processor Integrated Graphics Controller                         | 4        | 0.78%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 4        | 0.78%   |
| AMD RS880 [Radeon HD 4200]                                                  | 4        | 0.78%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 4        | 0.78%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| 1 x Nvidia                     | 168      | 36.13%  |
| 1 x AMD                        | 144      | 30.97%  |
| 1 x Intel                      | 125      | 26.88%  |
| Intel + Nvidia                 | 8        | 1.72%   |
| 2 x AMD                        | 7        | 1.51%   |
| 2 x Nvidia                     | 4        | 0.86%   |
| Intel + AMD                    | 4        | 0.86%   |
| Intel + 2 x AMD                | 2        | 0.43%   |
| AMD + Nvidia                   | 2        | 0.43%   |
| 2 x AMD + 1 x Conexant Systems | 1        | 0.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 355      | 76.18%  |
| Proprietary | 103      | 22.1%   |
| Unknown     | 8        | 1.72%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 190      | 39.92%  |
| 1.01-2.0   | 77       | 16.18%  |
| 0.51-1.0   | 54       | 11.34%  |
| 3.01-4.0   | 49       | 10.29%  |
| 7.01-8.0   | 40       | 8.4%    |
| 0.01-0.5   | 31       | 6.51%   |
| 5.01-6.0   | 19       | 3.99%   |
| 8.01-16.0  | 10       | 2.1%    |
| 2.01-3.0   | 6        | 1.26%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 79       | 15.8%   |
| Goldstar             | 56       | 11.2%   |
| Hewlett-Packard      | 46       | 9.2%    |
| Dell                 | 46       | 9.2%    |
| Acer                 | 41       | 8.2%    |
| AOC                  | 30       | 6%      |
| Philips              | 21       | 4.2%    |
| BenQ                 | 21       | 4.2%    |
| Ancor Communications | 20       | 4%      |
| LG Electronics       | 16       | 3.2%    |
| Lenovo               | 10       | 2%      |
| ViewSonic            | 9        | 1.8%    |
| Vizio                | 8        | 1.6%    |
| Unknown              | 7        | 1.4%    |
| NEC Computers        | 6        | 1.2%    |
| Fujitsu Siemens      | 5        | 1%      |
| ___                  | 3        | 0.6%    |
| Sony                 | 3        | 0.6%    |
| Sharp                | 3        | 0.6%    |
| Iiyama               | 3        | 0.6%    |
| HPN                  | 3        | 0.6%    |
| AUS                  | 3        | 0.6%    |
| ASUSTek Computer     | 3        | 0.6%    |
| Apple                | 3        | 0.6%    |
| Vestel               | 2        | 0.4%    |
| Sceptre Tech         | 2        | 0.4%    |
| MSI                  | 2        | 0.4%    |
| HKC                  | 2        | 0.4%    |
| Hitachi              | 2        | 0.4%    |
| HannStar             | 2        | 0.4%    |
| Grundig              | 2        | 0.4%    |
| Eizo                 | 2        | 0.4%    |
| CHR                  | 2        | 0.4%    |
| Unknown              | 2        | 0.4%    |
| TBD                  | 1        | 0.2%    |
| SPC                  | 1        | 0.2%    |
| Skyworth             | 1        | 0.2%    |
| SKY                  | 1        | 0.2%    |
| Seiki                | 1        | 0.2%    |
| SAC                  | 1        | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 4        | 0.75%   |
| Goldstar 20EN33 GSM4EE1 1600x900 443x249mm 20.0-inch                  | 4        | 0.75%   |
| AOC 27V2G5 AOC2702 1920x1080 598x336mm 27.0-inch                      | 4        | 0.75%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch  | 3        | 0.56%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch     | 3        | 0.56%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 3        | 0.56%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                   | 3        | 0.56%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch          | 3        | 0.56%   |
| AOC 24B1W AOC2401 1920x1080 521x293mm 23.5-inch                       | 3        | 0.56%   |
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                       | 3        | 0.56%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 3        | 0.56%   |
| Vizio E280i-A1 VIZ1002 1360x768 607x345mm 27.5-inch                   | 2        | 0.38%   |
| Vizio E221VA VIZ0070 1920x1080 476x268mm 21.5-inch                    | 2        | 0.38%   |
| ViewSonic VA2719 Series VSCC132 1920x1080 598x336mm 27.0-inch         | 2        | 0.38%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 2        | 0.38%   |
| Sharp HDMI SHP1048 1920x1080 820x460mm 37.0-inch                      | 2        | 0.38%   |
| Samsung Electronics SyncMaster SAM0423 1920x1080                      | 2        | 0.38%   |
| Samsung Electronics SA300/SA350 SAM078B 1600x900 443x249mm 20.0-inch  | 2        | 0.38%   |
| Samsung Electronics LCD Monitor C32F391 1920x1080                     | 2        | 0.38%   |
| Philips LCD Monitor PHL 276E8V 3840x2160                              | 2        | 0.38%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                       | 2        | 0.38%   |
| Hewlett-Packard w2207 HWP26A9 1680x1050 473x296mm 22.0-inch           | 2        | 0.38%   |
| Hewlett-Packard TouchSmart HWP4211 1920x1080 509x286mm 23.0-inch      | 2        | 0.38%   |
| Hewlett-Packard 24f HPN3545 1920x1080 527x296mm 23.8-inch             | 2        | 0.38%   |
| Hewlett-Packard 2010 HWP2889 1600x900 442x249mm 20.0-inch             | 2        | 0.38%   |
| Grundig WXGA GRU4448 1600x1200                                        | 2        | 0.38%   |
| Goldstar L1753T GSM4434 1280x1024 338x270mm 17.0-inch                 | 2        | 0.38%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                | 2        | 0.38%   |
| Goldstar E2211 GSM5838 1920x1080 477x268mm 21.5-inch                  | 2        | 0.38%   |
| Goldstar 2D HD TV GSM59C8 1366x768 509x286mm 23.0-inch                | 2        | 0.38%   |
| Goldstar 25UM58G GSM5B98 2560x1080 673x284mm 28.8-inch                | 2        | 0.38%   |
| Goldstar 22EN33 GSM597C 1920x1080 480x270mm 21.7-inch                 | 2        | 0.38%   |
| Dell U3415W DELA0A7 3440x1440 798x335mm 34.1-inch                     | 2        | 0.38%   |
| Dell U2417H DEL40E7 1920x1080 527x296mm 23.8-inch                     | 2        | 0.38%   |
| Dell P2214H DELA098 1920x1080 477x268mm 21.5-inch                     | 2        | 0.38%   |
| Dell E1914H DELD03A 1366x768 410x230mm 18.5-inch                      | 2        | 0.38%   |
| Dell 1704FPV DEL3016 1280x1024 338x270mm 17.0-inch                    | 2        | 0.38%   |
| CHR CH7511B CHR7511 1920x1080 519x324mm 24.1-inch                     | 2        | 0.38%   |
| BenQ EL2870U BNQ7949 3840x2160 621x341mm 27.9-inch                    | 2        | 0.38%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 531x299mm 24.0-inch          | 2        | 0.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 222      | 45.12%  |
| 2560x1440 (QHD)    | 35       | 7.11%   |
| 3840x2160 (4K)     | 34       | 6.91%   |
| 1680x1050 (WSXGA+) | 34       | 6.91%   |
| 1280x1024 (SXGA)   | 26       | 5.28%   |
| 1366x768 (WXGA)    | 24       | 4.88%   |
| 1600x900 (HD+)     | 23       | 4.67%   |
| Unknown            | 15       | 3.05%   |
| 1440x900 (WXGA+)   | 13       | 2.64%   |
| 1920x1200 (WUXGA)  | 10       | 2.03%   |
| 3840x1080          | 9        | 1.83%   |
| 1360x768           | 9        | 1.83%   |
| 3440x1440          | 7        | 1.42%   |
| 2560x1080          | 7        | 1.42%   |
| 5120x1440          | 3        | 0.61%   |
| 2560x1600          | 3        | 0.61%   |
| 1600x1200          | 3        | 0.61%   |
| 2048x1152          | 2        | 0.41%   |
| 7680x2160          | 1        | 0.2%    |
| 7680x1600          | 1        | 0.2%    |
| 5760x2160          | 1        | 0.2%    |
| 5760x1080          | 1        | 0.2%    |
| 4480x1440          | 1        | 0.2%    |
| 3968x1280          | 1        | 0.2%    |
| 3840x1600          | 1        | 0.2%    |
| 3840x1200          | 1        | 0.2%    |
| 3600x1080          | 1        | 0.2%    |
| 2288x1287          | 1        | 0.2%    |
| 2048x1536          | 1        | 0.2%    |
| 1920x540           | 1        | 0.2%    |
| 1024x768 (XGA)     | 1        | 0.2%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 85       | 17.03%  |
| 27      | 55       | 11.02%  |
| 24      | 55       | 11.02%  |
| 21      | 51       | 10.22%  |
| 23      | 49       | 9.82%   |
| 19      | 28       | 5.61%   |
| 22      | 26       | 5.21%   |
| 18      | 20       | 4.01%   |
| 20      | 18       | 3.61%   |
| 31      | 16       | 3.21%   |
| 17      | 14       | 2.81%   |
| 32      | 10       | 2%      |
| 34      | 9        | 1.8%    |
| 84      | 5        | 1%      |
| 72      | 5        | 1%      |
| 36      | 5        | 1%      |
| 15      | 5        | 1%      |
| 54      | 4        | 0.8%    |
| 29      | 4        | 0.8%    |
| 26      | 4        | 0.8%    |
| 49      | 3        | 0.6%    |
| 48      | 3        | 0.6%    |
| 42      | 3        | 0.6%    |
| 40      | 3        | 0.6%    |
| 60      | 2        | 0.4%    |
| 39      | 2        | 0.4%    |
| 38      | 2        | 0.4%    |
| 33      | 2        | 0.4%    |
| 28      | 2        | 0.4%    |
| 25      | 2        | 0.4%    |
| 65      | 1        | 0.2%    |
| 57      | 1        | 0.2%    |
| 55      | 1        | 0.2%    |
| 43      | 1        | 0.2%    |
| 37      | 1        | 0.2%    |
| 35      | 1        | 0.2%    |
| 14      | 1        | 0.2%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 147      | 30.63%  |
| 401-500     | 127      | 26.46%  |
| Unknown     | 85       | 17.71%  |
| 601-700     | 27       | 5.63%   |
| 701-800     | 25       | 5.21%   |
| 301-350     | 17       | 3.54%   |
| 1001-1500   | 15       | 3.13%   |
| 351-400     | 13       | 2.71%   |
| 1501-2000   | 10       | 2.08%   |
| 801-900     | 9        | 1.88%   |
| 901-1000    | 4        | 0.83%   |
| 201-300     | 1        | 0.21%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 273      | 60%     |
| Unknown | 78       | 17.14%  |
| 16/10   | 56       | 12.31%  |
| 5/4     | 21       | 4.62%   |
| 21/9    | 13       | 2.86%   |
| 4/3     | 5        | 1.1%    |
| 3/2     | 4        | 0.88%   |
| 32/9    | 3        | 0.66%   |
| 6/5     | 2        | 0.44%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 144      | 29.57%  |
| Unknown        | 85       | 17.45%  |
| 301-350        | 57       | 11.7%   |
| 151-200        | 55       | 11.29%  |
| 351-500        | 41       | 8.42%   |
| 141-150        | 30       | 6.16%   |
| 251-300        | 25       | 5.13%   |
| More than 1000 | 22       | 4.52%   |
| 501-1000       | 20       | 4.11%   |
| 101-110        | 4        | 0.82%   |
| 131-140        | 2        | 0.41%   |
| 111-120        | 1        | 0.21%   |
| 91-100         | 1        | 0.21%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 261      | 56.62%  |
| Unknown | 85       | 18.44%  |
| 101-120 | 79       | 17.14%  |
| 1-50    | 21       | 4.56%   |
| 121-160 | 13       | 2.82%   |
| 161-240 | 2        | 0.43%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 374      | 79.57%  |
| 2     | 75       | 15.96%  |
| 3     | 12       | 2.55%   |
| 0     | 9        | 1.91%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 286      | 42.18%  |
| Intel                             | 179      | 26.4%   |
| Qualcomm Atheros                  | 36       | 5.31%   |
| Broadcom                          | 31       | 4.57%   |
| TP-Link                           | 25       | 3.69%   |
| Ralink Technology                 | 21       | 3.1%    |
| Nvidia                            | 12       | 1.77%   |
| Samsung Electronics               | 10       | 1.47%   |
| Xiaomi                            | 8        | 1.18%   |
| Ralink                            | 7        | 1.03%   |
| Marvell Technology Group          | 7        | 1.03%   |
| Qualcomm Atheros Communications   | 5        | 0.74%   |
| D-Link System                     | 5        | 0.74%   |
| Broadcom Limited                  | 5        | 0.74%   |
| Microsoft                         | 4        | 0.59%   |
| Linksys                           | 4        | 0.59%   |
| MediaTek                          | 3        | 0.44%   |
| Huawei Technologies               | 3        | 0.44%   |
| NetGear                           | 2        | 0.29%   |
| D-Link                            | 2        | 0.29%   |
| ASUSTek Computer                  | 2        | 0.29%   |
| ZyXEL Communications              | 1        | 0.15%   |
| vivo                              | 1        | 0.15%   |
| VIA Technologies                  | 1        | 0.15%   |
| TRENDnet                          | 1        | 0.15%   |
| Sundance Technology Inc / IC Plus | 1        | 0.15%   |
| Qualcomm                          | 1        | 0.15%   |
| OPPO Electronics                  | 1        | 0.15%   |
| Motorola PCS                      | 1        | 0.15%   |
| Mercucys                          | 1        | 0.15%   |
| LG Electronics                    | 1        | 0.15%   |
| Input Club                        | 1        | 0.15%   |
| ICS Advent                        | 1        | 0.15%   |
| Exar                              | 1        | 0.15%   |
| Edimax Technology                 | 1        | 0.15%   |
| BUFFALO                           | 1        | 0.15%   |
| AVM                               | 1        | 0.15%   |
| ASIX Electronics                  | 1        | 0.15%   |
| Aquantia                          | 1        | 0.15%   |
| AirTies Wireless Networks         | 1        | 0.15%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 229      | 29.93%  |
| Intel I211 Gigabit Network Connection                             | 24       | 3.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 22       | 2.88%   |
| Intel Ethernet Connection (2) I219-V                              | 19       | 2.48%   |
| Realtek RTL8125 2.5GbE Controller                                 | 16       | 2.09%   |
| Intel Wi-Fi 6 AX200                                               | 16       | 2.09%   |
| Ralink MT7601U Wireless Adapter                                   | 14       | 1.83%   |
| Intel Ethernet Connection (7) I219-V                              | 14       | 1.83%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13       | 1.7%    |
| Intel 82579V Gigabit Network Connection                           | 11       | 1.44%   |
| Realtek 802.11ac NIC                                              | 10       | 1.31%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 9        | 1.18%   |
| Intel Ethernet Controller I225-V                                  | 9        | 1.18%   |
| Intel Ethernet Connection I217-LM                                 | 9        | 1.18%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 8        | 1.05%   |
| Intel 82574L Gigabit Network Connection                           | 8        | 1.05%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 7        | 0.92%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 7        | 0.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 7        | 0.92%   |
| Nvidia MCP61 Ethernet                                             | 7        | 0.92%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter      | 7        | 0.92%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 6        | 0.78%   |
| Intel Wireless 3165                                               | 6        | 0.78%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 6        | 0.78%   |
| Intel Ethernet Connection I217-V                                  | 6        | 0.78%   |
| Qualcomm Atheros AR9271 802.11n                                   | 5        | 0.65%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 5        | 0.65%   |
| Intel Wireless-AC 9260                                            | 5        | 0.65%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5        | 0.65%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 5        | 0.65%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 5        | 0.65%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 4        | 0.52%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 4        | 0.52%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 4        | 0.52%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4        | 0.52%   |
| Intel Ethernet Connection (2) I218-V                              | 4        | 0.52%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4        | 0.52%   |
| Intel 82578DM Gigabit Network Connection                          | 4        | 0.52%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 3        | 0.39%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 3        | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 61       | 24.4%   |
| Intel                           | 60       | 24%     |
| TP-Link                         | 24       | 9.6%    |
| Ralink Technology               | 21       | 8.4%    |
| Broadcom                        | 19       | 7.6%    |
| Qualcomm Atheros                | 16       | 6.4%    |
| Ralink                          | 7        | 2.8%    |
| Qualcomm Atheros Communications | 5        | 2%      |
| Microsoft                       | 4        | 1.6%    |
| Linksys                         | 4        | 1.6%    |
| D-Link System                   | 4        | 1.6%    |
| Broadcom Limited                | 4        | 1.6%    |
| Marvell Technology Group        | 3        | 1.2%    |
| NetGear                         | 2        | 0.8%    |
| MediaTek                        | 2        | 0.8%    |
| D-Link                          | 2        | 0.8%    |
| ASUSTek Computer                | 2        | 0.8%    |
| ZyXEL Communications            | 1        | 0.4%    |
| TRENDnet                        | 1        | 0.4%    |
| Mercucys                        | 1        | 0.4%    |
| LG Electronics                  | 1        | 0.4%    |
| Edimax Technology               | 1        | 0.4%    |
| BUFFALO                         | 1        | 0.4%    |
| AVM                             | 1        | 0.4%    |
| AirTies Wireless Networks       | 1        | 0.4%    |
| Accton Technology               | 1        | 0.4%    |
| AboCom Systems                  | 1        | 0.4%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                          | 16       | 6.3%    |
| Ralink MT7601U Wireless Adapter                              | 14       | 5.51%   |
| Realtek 802.11ac NIC                                         | 10       | 3.94%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter          | 9        | 3.54%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter     | 8        | 3.15%   |
| Realtek RTL88x2bu [AC1200 Techkey]                           | 7        | 2.76%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter             | 7        | 2.76%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter | 7        | 2.76%   |
| Intel Wireless 3165                                          | 6        | 2.36%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                       | 6        | 2.36%   |
| Qualcomm Atheros AR9271 802.11n                              | 5        | 1.97%   |
| Intel Wireless-AC 9260                                       | 5        | 1.97%   |
| Intel Cannon Lake PCH CNVi WiFi                              | 5        | 1.97%   |
| Broadcom BCM43228 802.11a/b/g/n                              | 5        | 1.97%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                  | 4        | 1.57%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                          | 4        | 1.57%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]             | 4        | 1.57%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                 | 3        | 1.18%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]   | 3        | 1.18%   |
| TP-Link 802.11ac NIC                                         | 3        | 1.18%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter     | 3        | 1.18%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                   | 3        | 1.18%   |
| Microsoft Xbox 360 Wireless Adapter                          | 3        | 1.18%   |
| Intel Wireless 8260                                          | 3        | 1.18%   |
| Intel Comet Lake PCH CNVi WiFi                               | 3        | 1.18%   |
| Intel Alder Lake-S PCH CNVi WiFi                             | 3        | 1.18%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter | 3        | 1.18%   |
| TP-Link Archer T4U ver.3                                     | 2        | 0.79%   |
| TP-Link 802.11ac WLAN Adapter                                | 2        | 0.79%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter     | 2        | 0.79%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter              | 2        | 0.79%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                      | 2        | 0.79%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                   | 2        | 0.79%   |
| Realtek RTL8187 Wireless Adapter                             | 2        | 0.79%   |
| Ralink RT5372 Wireless Adapter                               | 2        | 0.79%   |
| Ralink RT2870/RT3070 Wireless Adapter                        | 2        | 0.79%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                    | 2        | 0.79%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter             | 2        | 0.79%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                      | 2        | 0.79%   |
| Marvell Group 88w8335 [Libertas] 802.11b/g Wireless          | 2        | 0.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 264      | 53.33%  |
| Intel                             | 152      | 30.71%  |
| Qualcomm Atheros                  | 22       | 4.44%   |
| Broadcom                          | 13       | 2.63%   |
| Nvidia                            | 12       | 2.42%   |
| Xiaomi                            | 8        | 1.62%   |
| Samsung Electronics               | 4        | 0.81%   |
| Marvell Technology Group          | 4        | 0.81%   |
| Huawei Technologies               | 3        | 0.61%   |
| vivo                              | 1        | 0.2%    |
| VIA Technologies                  | 1        | 0.2%    |
| TP-Link                           | 1        | 0.2%    |
| Sundance Technology Inc / IC Plus | 1        | 0.2%    |
| Qualcomm                          | 1        | 0.2%    |
| OPPO Electronics                  | 1        | 0.2%    |
| Motorola PCS                      | 1        | 0.2%    |
| MediaTek                          | 1        | 0.2%    |
| ICS Advent                        | 1        | 0.2%    |
| D-Link System                     | 1        | 0.2%    |
| Broadcom Limited                  | 1        | 0.2%    |
| ASIX Electronics                  | 1        | 0.2%    |
| Aquantia                          | 1        | 0.2%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 229      | 45.53%  |
| Intel I211 Gigabit Network Connection                             | 24       | 4.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 22       | 4.37%   |
| Intel Ethernet Connection (2) I219-V                              | 19       | 3.78%   |
| Realtek RTL8125 2.5GbE Controller                                 | 16       | 3.18%   |
| Intel Ethernet Connection (7) I219-V                              | 14       | 2.78%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13       | 2.58%   |
| Intel 82579V Gigabit Network Connection                           | 11       | 2.19%   |
| Intel Ethernet Controller I225-V                                  | 9        | 1.79%   |
| Intel Ethernet Connection I217-LM                                 | 9        | 1.79%   |
| Intel 82574L Gigabit Network Connection                           | 8        | 1.59%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 7        | 1.39%   |
| Nvidia MCP61 Ethernet                                             | 7        | 1.39%   |
| Intel Ethernet Connection I217-V                                  | 6        | 1.19%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 5        | 0.99%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 5        | 0.99%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 4        | 0.8%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4        | 0.8%    |
| Intel Ethernet Connection (2) I218-V                              | 4        | 0.8%    |
| Intel 82578DM Gigabit Network Connection                          | 4        | 0.8%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3        | 0.6%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3        | 0.6%    |
| Nvidia MCP77 Ethernet                                             | 3        | 0.6%    |
| Intel Ethernet Connection (7) I219-LM                             | 3        | 0.6%    |
| Intel Ethernet Connection (2) I219-LM                             | 3        | 0.6%    |
| Huawei MAR-LX1M                                                   | 3        | 0.6%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2        | 0.4%    |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 2        | 0.4%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 0.4%    |
| Nvidia MCP55 Ethernet                                             | 2        | 0.4%    |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 2        | 0.4%    |
| Intel Ethernet Connection (14) I219-V                             | 2        | 0.4%    |
| Intel Ethernet Connection (11) I219-V                             | 2        | 0.4%    |
| Intel 82578DC Gigabit Network Connection                          | 2        | 0.4%    |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 0.4%    |
| Intel 82566DC-2 Gigabit Network Connection                        | 2        | 0.4%    |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)            | 2        | 0.4%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2        | 0.4%    |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 2        | 0.4%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2        | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 458      | 66.09%  |
| WiFi     | 228      | 32.9%   |
| Modem    | 7        | 1.01%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 337      | 72.32%  |
| WiFi     | 128      | 27.47%  |
| Modem    | 1        | 0.21%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 305      | 65.73%  |
| 2     | 131      | 28.23%  |
| 3     | 22       | 4.74%   |
| 0     | 5        | 1.08%   |
| 4     | 1        | 0.22%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 351      | 75.48%  |
| Yes  | 114      | 24.52%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 58       | 33.92%  |
| Cambridge Silicon Radio         | 50       | 29.24%  |
| Realtek Semiconductor           | 17       | 9.94%   |
| Broadcom                        | 12       | 7.02%   |
| ASUSTek Computer                | 11       | 6.43%   |
| Apple                           | 8        | 4.68%   |
| Qualcomm Atheros Communications | 3        | 1.75%   |
| TP-Link                         | 2        | 1.17%   |
| MediaTek                        | 2        | 1.17%   |
| IMC Networks                    | 2        | 1.17%   |
| Belkin Components               | 2        | 1.17%   |
| Ralink                          | 1        | 0.58%   |
| Qcom                            | 1        | 0.58%   |
| Edimax Technology               | 1        | 0.58%   |
| 3Com                            | 1        | 0.58%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 50       | 29.24%  |
| Intel AX200 Bluetooth                                 | 15       | 8.77%   |
| Intel Bluetooth wireless interface                    | 14       | 8.19%   |
| Realtek Bluetooth Radio                               | 12       | 7.02%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 7        | 4.09%   |
| Intel AX210 Bluetooth                                 | 7        | 4.09%   |
| Intel AX201 Bluetooth                                 | 6        | 3.51%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 5        | 2.92%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 4        | 2.34%   |
| Intel Wireless-AC 3168 Bluetooth                      | 4        | 2.34%   |
| Realtek  Bluetooth 4.2 Adapter                        | 3        | 1.75%   |
| Broadcom HP Portable Bumble Bee                       | 3        | 1.75%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 3        | 1.75%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                  | 3        | 1.75%   |
| TP-Link TP-Cdj+ UB5A Adapter                          | 2        | 1.17%   |
| Qualcomm Atheros  Bluetooth Device                    | 2        | 1.17%   |
| MediaTek Wireless_Device                              | 2        | 1.17%   |
| IMC Networks BCM20702A0                               | 2        | 1.17%   |
| Broadcom Bluetooth 3.0 Dongle                         | 2        | 1.17%   |
| Belkin Components Bluetooth Mini Dongle               | 2        | 1.17%   |
| ASUS Bluetooth Radio                                  | 2        | 1.17%   |
| ASUS BCM20702A0                                       | 2        | 1.17%   |
| Apple Bluetooth USB Host Controller                   | 2        | 1.17%   |
| Apple Bluetooth Host Controller                       | 2        | 1.17%   |
| Realtek Bluetooth 5.1 Radio                           | 1        | 0.58%   |
| Realtek 802.11ac WLAN Adapter                         | 1        | 0.58%   |
| Ralink RT3290 Bluetooth                               | 1        | 0.58%   |
| Qualcomm Atheros Bluetooth USB Host Controller        | 1        | 0.58%   |
| Qcom Bluetooth USB                                    | 1        | 0.58%   |
| Intel Bluetooth Device                                | 1        | 0.58%   |
| Edimax Bluetooth Adapter                              | 1        | 0.58%   |
| Broadcom Bluetooth dongle                             | 1        | 0.58%   |
| Broadcom Bluetooth Controller                         | 1        | 0.58%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter      | 1        | 0.58%   |
| Broadcom BCM43142A0 Bluetooth 4.0                     | 1        | 0.58%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 0.58%   |
| ASUS ASUS USB-BT500                                   | 1        | 0.58%   |
| Apple Bluetooth HCI                                   | 1        | 0.58%   |
| 3Com 3CREB96 Bluetooth Adapter                        | 1        | 0.58%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 308      | 38.5%   |
| AMD                                  | 196      | 24.5%   |
| Nvidia                               | 179      | 22.38%  |
| C-Media Electronics                  | 36       | 4.5%    |
| Creative Labs                        | 13       | 1.63%   |
| Logitech                             | 12       | 1.5%    |
| JMTek                                | 6        | 0.75%   |
| Generalplus Technology               | 6        | 0.75%   |
| Razer USA                            | 4        | 0.5%    |
| Creative Technology                  | 4        | 0.5%    |
| ASUSTek Computer                     | 3        | 0.38%   |
| Texas Instruments                    | 2        | 0.25%   |
| GN Netcom                            | 2        | 0.25%   |
| Focusrite-Novation                   | 2        | 0.25%   |
| Corsair                              | 2        | 0.25%   |
| BR25                                 | 2        | 0.25%   |
| BEHRINGER International              | 2        | 0.25%   |
| VIA Technologies                     | 1        | 0.13%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.13%   |
| Tenx Technology                      | 1        | 0.13%   |
| Sony                                 | 1        | 0.13%   |
| Samson Technologies                  | 1        | 0.13%   |
| Realtek Semiconductor                | 1        | 0.13%   |
| PreSonus Audio Electronics           | 1        | 0.13%   |
| Plantronics                          | 1        | 0.13%   |
| Philips Speech Processing            | 1        | 0.13%   |
| Nordic Semiconductor ASA             | 1        | 0.13%   |
| Native Instruments                   | 1        | 0.13%   |
| Microsoft                            | 1        | 0.13%   |
| Micro Star International             | 1        | 0.13%   |
| KTMicro                              | 1        | 0.13%   |
| iCreate Technologies                 | 1        | 0.13%   |
| Hewlett-Packard                      | 1        | 0.13%   |
| Goldvish                             | 1        | 0.13%   |
| Fortemedia                           | 1        | 0.13%   |
| Edifier Technology                   | 1        | 0.13%   |
| ATI Technologies                     | 1        | 0.13%   |
| Astro Gaming                         | 1        | 0.13%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 62       | 6.74%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 43       | 4.67%   |
| AMD Starship/Matisse HD Audio Controller                                          | 30       | 3.26%   |
| Intel Cannon Lake PCH cAVS                                                        | 28       | 3.04%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 28       | 3.04%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 25       | 2.72%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 25       | 2.72%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 25       | 2.72%   |
| AMD Family 17h/19h HD Audio Controller                                            | 24       | 2.61%   |
| Intel 200 Series PCH HD Audio                                                     | 22       | 2.39%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 22       | 2.39%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 19       | 2.07%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 17       | 1.85%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 16       | 1.74%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 16       | 1.74%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 15       | 1.63%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 15       | 1.63%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 15       | 1.63%   |
| AMD FCH Azalia Controller                                                         | 14       | 1.52%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 14       | 1.52%   |
| Nvidia GF108 High Definition Audio Controller                                     | 13       | 1.41%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 13       | 1.41%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 11       | 1.2%    |
| Nvidia TU116 High Definition Audio Controller                                     | 10       | 1.09%   |
| Nvidia GP104 High Definition Audio Controller                                     | 10       | 1.09%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 10       | 1.09%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 9        | 0.98%   |
| Nvidia TU106 High Definition Audio Controller                                     | 8        | 0.87%   |
| Nvidia MCP61 High Definition Audio                                                | 8        | 0.87%   |
| Nvidia GP106 High Definition Audio Controller                                     | 8        | 0.87%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 8        | 0.87%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 8        | 0.87%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 8        | 0.87%   |
| Nvidia TU104 HD Audio Controller                                                  | 7        | 0.76%   |
| Nvidia High Definition Audio Controller                                           | 7        | 0.76%   |
| Nvidia GP108 High Definition Audio Controller                                     | 7        | 0.76%   |
| Nvidia GM204 High Definition Audio Controller                                     | 7        | 0.76%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 7        | 0.76%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 6        | 0.65%   |
| Nvidia GA102 High Definition Audio Controller                                     | 6        | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 33       | 26.4%   |
| Samsung Electronics | 15       | 12%     |
| Unknown             | 13       | 10.4%   |
| Corsair             | 10       | 8%      |
| SK hynix            | 9        | 7.2%    |
| G.Skill             | 9        | 7.2%    |
| Crucial             | 9        | 7.2%    |
| Ramaxel Technology  | 3        | 2.4%    |
| Patriot             | 3        | 2.4%    |
| Nanya Technology    | 3        | 2.4%    |
| Micron Technology   | 3        | 2.4%    |
| A-DATA Technology   | 3        | 2.4%    |
| Apacer              | 2        | 1.6%    |
| Unknown             | 2        | 1.6%    |
| Unknown (82B5)      | 1        | 0.8%    |
| Unknown (0x5846)    | 1        | 0.8%    |
| Unknown (0x038A)    | 1        | 0.8%    |
| Transcend           | 1        | 0.8%    |
| Team                | 1        | 0.8%    |
| PNY                 | 1        | 0.8%    |
| Neo Forza           | 1        | 0.8%    |
| CSX                 | 1        | 0.8%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Unknown RAM Module 8GB DIMM 1333MT/s                            | 2        | 1.53%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                            | 2        | 1.53%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s                     | 2        | 1.53%   |
| SK hynix RAM HMT31GR7BFR4C-H9 8192MB DIMM DDR3 1333MT/s         | 2        | 1.53%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s           | 2        | 1.53%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1923MT/s             | 2        | 1.53%   |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 2800MT/s            | 2        | 1.53%   |
| Unknown                                                         | 2        | 1.53%   |
| Unknown RAM Module 8GB DIMM DDR3 1066MT/s                       | 1        | 0.76%   |
| Unknown RAM Module 8192MB DIMM DDR3 1066MT/s                    | 1        | 0.76%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                         | 1        | 0.76%   |
| Unknown RAM Module 8192MB DIMM 1066MT/s                         | 1        | 0.76%   |
| Unknown RAM Module 512MB DIMM SDRAM                             | 1        | 0.76%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                       | 1        | 0.76%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                    | 1        | 0.76%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                            | 1        | 0.76%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                     | 1        | 0.76%   |
| Unknown RAM Module 2048MB DIMM DDR 133MT/s                      | 1        | 0.76%   |
| Unknown RAM Module 1024MB DIMM SDRAM                            | 1        | 0.76%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s                     | 1        | 0.76%   |
| Unknown (82B5) RAM OP 117100 05/14 2M 4096MB DIMM DDR3 1333MT/s | 1        | 0.76%   |
| Unknown (0x5846) RAM DDR4 NB 8G 2666 8GB SODIMM DDR4 2667MT/s   | 1        | 0.76%   |
| Unknown (0x038A) RAM Module 4GB DIMM DDR3 1066MT/s              | 1        | 0.76%   |
| Transcend RAM JM1333KLN-2G 2GB DIMM DDR3 1333MT/s               | 1        | 0.76%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s              | 1        | 0.76%   |
| SK hynix RAM HYMP112U64CP8-Y5 1GB DIMM DDR2 1639MT/s            | 1        | 0.76%   |
| SK hynix RAM HMT42GR7BMR4C 16384MB DIMM DDR3 1066MT/s           | 1        | 0.76%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s            | 1        | 0.76%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s            | 1        | 0.76%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s            | 1        | 0.76%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s          | 1        | 0.76%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8192MB DIMM DDR4 2400MT/s         | 1        | 0.76%   |
| Samsung RAM Module 8192MB Row Of Chips LPDDR4 3733MT/s          | 1        | 0.76%   |
| Samsung RAM Module 8192MB DIMM DDR4 2666MT/s                    | 1        | 0.76%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s           | 1        | 0.76%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s           | 1        | 0.76%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s           | 1        | 0.76%   |
| Samsung RAM M393B2K70DM0 16384MB DIMM DDR3 1066MT/s             | 1        | 0.76%   |
| Samsung RAM M393B1K70CHD-CH9 8GB DIMM DDR3 1333MT/s             | 1        | 0.76%   |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM DDR3 1333MT/s             | 1        | 0.76%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 45       | 45.45%  |
| DDR4    | 31       | 31.31%  |
| DDR2    | 8        | 8.08%   |
| Unknown | 7        | 7.07%   |
| SDRAM   | 6        | 6.06%   |
| LPDDR4  | 1        | 1.01%   |
| DDR     | 1        | 1.01%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 88       | 90.72%  |
| SODIMM       | 7        | 7.22%   |
| Row Of Chips | 1        | 1.03%   |
| FB-DIMM      | 1        | 1.03%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 46       | 41.07%  |
| 4096  | 29       | 25.89%  |
| 2048  | 17       | 15.18%  |
| 16384 | 12       | 10.71%  |
| 1024  | 5        | 4.46%   |
| 32768 | 2        | 1.79%   |
| 512   | 1        | 0.89%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 22       | 19.13%  |
| 1333    | 20       | 17.39%  |
| 2400    | 7        | 6.09%   |
| 3600    | 6        | 5.22%   |
| 667     | 6        | 5.22%   |
| 3200    | 5        | 4.35%   |
| 2667    | 4        | 3.48%   |
| 1867    | 4        | 3.48%   |
| 1800    | 4        | 3.48%   |
| 1066    | 4        | 3.48%   |
| 800     | 4        | 3.48%   |
| 2800    | 3        | 2.61%   |
| 2133    | 3        | 2.61%   |
| 3733    | 2        | 1.74%   |
| 3466    | 2        | 1.74%   |
| 1866    | 2        | 1.74%   |
| 4800    | 1        | 0.87%   |
| 3533    | 1        | 0.87%   |
| 3400    | 1        | 0.87%   |
| 3334    | 1        | 0.87%   |
| 3266    | 1        | 0.87%   |
| 3007    | 1        | 0.87%   |
| 3000    | 1        | 0.87%   |
| 2934    | 1        | 0.87%   |
| 2933    | 1        | 0.87%   |
| 2733    | 1        | 0.87%   |
| 2666    | 1        | 0.87%   |
| 2200    | 1        | 0.87%   |
| 2000    | 1        | 0.87%   |
| 1639    | 1        | 0.87%   |
| 533     | 1        | 0.87%   |
| 133     | 1        | 0.87%   |
| Unknown | 1        | 0.87%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 10       | 43.48%  |
| Brother Industries    | 5        | 21.74%  |
| Canon                 | 4        | 17.39%  |
| Samsung Electronics   | 2        | 8.7%    |
| Lexmark International | 1        | 4.35%   |
| Dymo-CoStar           | 1        | 4.35%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Samsung M2070 Series                     | 1        | 4.35%   |
| Samsung M2020 Series                     | 1        | 4.35%   |
| Lexmark International Laser Printer E210 | 1        | 4.35%   |
| HP Smart Tank 580-590 series             | 1        | 4.35%   |
| HP Printing Support                      | 1        | 4.35%   |
| HP OfficeJet 5200 series                 | 1        | 4.35%   |
| HP LaserJet Pro M201dw                   | 1        | 4.35%   |
| HP LaserJet M101-M106                    | 1        | 4.35%   |
| HP LaserJet 1320                         | 1        | 4.35%   |
| HP LaserJet 1300                         | 1        | 4.35%   |
| HP Ink Tank 110 series                   | 1        | 4.35%   |
| HP Deskjet 2050 J510                     | 1        | 4.35%   |
| HP Deskjet 1000 J110 series              | 1        | 4.35%   |
| Dymo-CoStar LabelWriter 450              | 1        | 4.35%   |
| Canon TR8500 series                      | 1        | 4.35%   |
| Canon PIXMA MX390 Series                 | 1        | 4.35%   |
| Canon PIXMA MG3600 Series                | 1        | 4.35%   |
| Canon MF4320-4350                        | 1        | 4.35%   |
| Brother MFC-T910DW                       | 1        | 4.35%   |
| Brother MFC-J5335DW                      | 1        | 4.35%   |
| Brother MFC-J5330DW                      | 1        | 4.35%   |
| Brother HL-4140CN series                 | 1        | 4.35%   |
| Brother DCP-L2550DN series               | 1        | 4.35%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Canon CanoScan LIDE 25 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 28       | 31.11%  |
| Microdia                      | 9        | 10%     |
| Microsoft                     | 7        | 7.78%   |
| Apple                         | 6        | 6.67%   |
| Chicony Electronics           | 5        | 5.56%   |
| Z-Star Microelectronics       | 3        | 3.33%   |
| Generalplus Technology        | 3        | 3.33%   |
| Sunplus Innovation Technology | 2        | 2.22%   |
| Samsung Electronics           | 2        | 2.22%   |
| KYE Systems (Mouse Systems)   | 2        | 2.22%   |
| Cubeternet                    | 2        | 2.22%   |
| Alcor Micro                   | 2        | 2.22%   |
| Trust                         | 1        | 1.11%   |
| Teslong Camera                | 1        | 1.11%   |
| SunplusIT                     | 1        | 1.11%   |
| Silicon Motion                | 1        | 1.11%   |
| Realtek Semiconductor         | 1        | 1.11%   |
| Razer USA                     | 1        | 1.11%   |
| Philips (or NXP)              | 1        | 1.11%   |
| OmniVision Technologies       | 1        | 1.11%   |
| MacroSilicon                  | 1        | 1.11%   |
| LG Electronics                | 1        | 1.11%   |
| Hopewin Electronic Material   | 1        | 1.11%   |
| Hewlett-Packard               | 1        | 1.11%   |
| HD USB Camera                 | 1        | 1.11%   |
| Guillemot                     | 1        | 1.11%   |
| GEMBIRD                       | 1        | 1.11%   |
| Creative Technology           | 1        | 1.11%   |
| AVerMedia Technologies        | 1        | 1.11%   |
| Arkmicro Technologies         | 1        | 1.11%   |
| ANYKA                         | 1        | 1.11%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920             | 7        | 7.78%   |
| Logitech Webcam C270                    | 5        | 5.56%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR      | 5        | 5.56%   |
| Microsoft LifeCam HD-3000               | 3        | 3.33%   |
| Microdia Integrated Camera              | 3        | 3.33%   |
| Logitech HD Webcam C615                 | 3        | 3.33%   |
| Chicony HP High Definition 1MP Webcam   | 3        | 3.33%   |
| Samsung Galaxy series, misc. (MTP mode) | 2        | 2.22%   |
| Microdia USB Camera                     | 2        | 2.22%   |
| Logitech C922 Pro Stream Webcam         | 2        | 2.22%   |
| Logitech BRIO 4K Stream Edition         | 2        | 2.22%   |
| Logitech B525 HD Webcam                 | 2        | 2.22%   |
| Generalplus GENERAL WEBCAM              | 2        | 2.22%   |
| Cubeternet GL-UPC822 UVC WebCam         | 2        | 2.22%   |
| Z-Star Venus USB2.0 Camera              | 1        | 1.11%   |
| Z-Star Vega USB 2.0 Camera              | 1        | 1.11%   |
| Z-Star Sirius USB2.0 Camera             | 1        | 1.11%   |
| Trust USB Camera                        | 1        | 1.11%   |
| Teslong Camera                          | 1        | 1.11%   |
| SunplusIT MTD camera                    | 1        | 1.11%   |
| Sunplus FHD Camera Microphone           | 1        | 1.11%   |
| Sunplus 5Mega Webcam                    | 1        | 1.11%   |
| Silicon Motion Silicon Motion Camera    | 1        | 1.11%   |
| Realtek FULL HD 1080P Webcam            | 1        | 1.11%   |
| Razer USA Razer Kiyo Pro                | 1        | 1.11%   |
| Philips (or NXP) SPZ2500                | 1        | 1.11%   |
| OmniVision Monitor Webcam               | 1        | 1.11%   |
| Microsoft Xbox NUI Camera               | 1        | 1.11%   |
| Microsoft LifeCam VX-800                | 1        | 1.11%   |
| Microsoft LifeCam VX-2000               | 1        | 1.11%   |
| Microsoft LifeCam HD-5000               | 1        | 1.11%   |
| Microdia Webcam Vitade AF               | 1        | 1.11%   |
| Microdia USB 2.0 Camera                 | 1        | 1.11%   |
| Microdia Sonix USB 2.0 Camera           | 1        | 1.11%   |
| Microdia Camera                         | 1        | 1.11%   |
| MacroSilicon USB3.0 UHD                 | 1        | 1.11%   |
| Logitech Webcam C310                    | 1        | 1.11%   |
| Logitech Webcam C250                    | 1        | 1.11%   |
| Logitech QuickCam Communicate Deluxe    | 1        | 1.11%   |
| Logitech Logitech Webcam C925e          | 1        | 1.11%   |

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


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| OmniKey             | 1        | 33.33%  |
| Chicony Electronics | 1        | 33.33%  |
| Alcor Micro         | 1        | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| OmniKey CardMan 3121 (HID Technologies)              | 1        | 33.33%  |
| Chicony Electronics HP Skylab USB Smartcard Keyboard | 1        | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader                  | 1        | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 403      | 85.38%  |
| 1     | 57       | 12.08%  |
| 2     | 9        | 1.91%   |
| 4     | 2        | 0.42%   |
| 3     | 1        | 0.21%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 35       | 45.45%  |
| Graphics card            | 14       | 18.18%  |
| Sound                    | 6        | 7.79%   |
| Network                  | 3        | 3.9%    |
| Multimedia controller    | 3        | 3.9%    |
| Bluetooth                | 3        | 3.9%    |
| Unassigned class         | 2        | 2.6%    |
| Communication controller | 2        | 2.6%    |
| Chipcard                 | 2        | 2.6%    |
| Card reader              | 2        | 2.6%    |
| Camera                   | 2        | 2.6%    |
| Storage/ide              | 1        | 1.3%    |
| Net/ethernet             | 1        | 1.3%    |
| Fingerprint reader       | 1        | 1.3%    |

