Linux in Czechia - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Czechia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Czechia/Desktop/README.md) and [notebooks](/Location/Czechia/Notebook/README.md).

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

Total: 3004

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | 09CCh                       | Desktop     | [15bfdf7213](https://linux-hardware.org/?probe=15bfdf7213) | Aug 12, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [475b07d2dc](https://linux-hardware.org/?probe=475b07d2dc) | Aug 12, 2023 |
| HP            | 250 G3                      | Notebook    | [6ba303bc6b](https://linux-hardware.org/?probe=6ba303bc6b) | Aug 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [ffa9b97bf7](https://linux-hardware.org/?probe=ffa9b97bf7) | Aug 10, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [82dde7d058](https://linux-hardware.org/?probe=82dde7d058) | Aug 10, 2023 |
| HP            | ZBook Studio 16 inch G9 ... | Notebook    | [e1462f1e3a](https://linux-hardware.org/?probe=e1462f1e3a) | Aug 10, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | Notebook    | [6415840d5b](https://linux-hardware.org/?probe=6415840d5b) | Aug 09, 2023 |
| HP            | ProBook 455 G7              | Notebook    | [bd9f67ee72](https://linux-hardware.org/?probe=bd9f67ee72) | Aug 07, 2023 |
| Acer          | Swift SF514-53T             | Notebook    | [30d8fefda4](https://linux-hardware.org/?probe=30d8fefda4) | Aug 07, 2023 |
| Acer          | Swift SF514-53T             | Notebook    | [f1cef350fb](https://linux-hardware.org/?probe=f1cef350fb) | Aug 07, 2023 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | Notebook    | [b69ff09aa4](https://linux-hardware.org/?probe=b69ff09aa4) | Aug 05, 2023 |
| ASUSTek       | ROG STRIX B450-E GAMING     | Desktop     | [401fdc46ef](https://linux-hardware.org/?probe=401fdc46ef) | Aug 05, 2023 |
| Dell          | Latitude E6420              | Notebook    | [3636e69adb](https://linux-hardware.org/?probe=3636e69adb) | Aug 05, 2023 |
| Acer          | Aspire E5-572G              | Notebook    | [846dce7b1b](https://linux-hardware.org/?probe=846dce7b1b) | Aug 05, 2023 |
| Dell          | Latitude E5500              | Notebook    | [95ddcb321c](https://linux-hardware.org/?probe=95ddcb321c) | Aug 05, 2023 |
| Acer          | Swift SF514-54GT            | Notebook    | [12ee4ed8f6](https://linux-hardware.org/?probe=12ee4ed8f6) | Aug 05, 2023 |
| Acer          | Swift SF514-54GT            | Notebook    | [5a2ed78e49](https://linux-hardware.org/?probe=5a2ed78e49) | Aug 05, 2023 |
| Dell          | Latitude 7400               | Notebook    | [48e2858e56](https://linux-hardware.org/?probe=48e2858e56) | Aug 04, 2023 |
| Lenovo        | ThinkPad T480 20L50000MC    | Notebook    | [341698801e](https://linux-hardware.org/?probe=341698801e) | Aug 04, 2023 |
| Dell          | Latitude 7440               | Notebook    | [195716ccf3](https://linux-hardware.org/?probe=195716ccf3) | Aug 04, 2023 |
| ASRock        | 4CoreDual-SATA2             | Desktop     | [6495cadf19](https://linux-hardware.org/?probe=6495cadf19) | Aug 04, 2023 |
| Dell          | Latitude 7440               | Notebook    | [5a9a057759](https://linux-hardware.org/?probe=5a9a057759) | Aug 04, 2023 |
| Dell          | Latitude 7440               | Notebook    | [367f14eae6](https://linux-hardware.org/?probe=367f14eae6) | Aug 04, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | Notebook    | [1317097350](https://linux-hardware.org/?probe=1317097350) | Aug 03, 2023 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | Notebook    | [e5be227d11](https://linux-hardware.org/?probe=e5be227d11) | Aug 03, 2023 |
| Dell          | 0CRH6C A02                  | Desktop     | [141928d8e2](https://linux-hardware.org/?probe=141928d8e2) | Aug 02, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [2d1e78ec7e](https://linux-hardware.org/?probe=2d1e78ec7e) | Aug 02, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [589f0a8599](https://linux-hardware.org/?probe=589f0a8599) | Aug 01, 2023 |
| Acer          | Aspire 1810TZ               | Notebook    | [8cbec4eb45](https://linux-hardware.org/?probe=8cbec4eb45) | Jul 31, 2023 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [5ce91f2c11](https://linux-hardware.org/?probe=5ce91f2c11) | Jul 30, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | Notebook    | [6ec734b217](https://linux-hardware.org/?probe=6ec734b217) | Jul 30, 2023 |
| Acer          | Aspire 5742                 | Notebook    | [37be5a1c80](https://linux-hardware.org/?probe=37be5a1c80) | Jul 30, 2023 |
| ASRock        | 4CoreDual-SATA2             | Desktop     | [44438ab71e](https://linux-hardware.org/?probe=44438ab71e) | Jul 30, 2023 |
| HP            | 843B                        | Desktop     | [c570a7c5f2](https://linux-hardware.org/?probe=c570a7c5f2) | Jul 29, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [a7b390cdf4](https://linux-hardware.org/?probe=a7b390cdf4) | Jul 29, 2023 |
| Lenovo        | Yoga 7 14ARP8 82YM          | Convertible | [4baa3fe63b](https://linux-hardware.org/?probe=4baa3fe63b) | Jul 29, 2023 |
| Lenovo        | Yoga 7 14ARP8 82YM          | Convertible | [254354d9aa](https://linux-hardware.org/?probe=254354d9aa) | Jul 29, 2023 |
| Gigabyte      | X570S AERO G                | Desktop     | [d500093891](https://linux-hardware.org/?probe=d500093891) | Jul 28, 2023 |
| Google        | Edgar                       | Notebook    | [7e19b1e507](https://linux-hardware.org/?probe=7e19b1e507) | Jul 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [f5497a92cf](https://linux-hardware.org/?probe=f5497a92cf) | Jul 28, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [fd41467554](https://linux-hardware.org/?probe=fd41467554) | Jul 28, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [ccfe4b2234](https://linux-hardware.org/?probe=ccfe4b2234) | Jul 27, 2023 |
| Acer          | Aspire A315-24P             | Notebook    | [6799c4be4a](https://linux-hardware.org/?probe=6799c4be4a) | Jul 27, 2023 |
| Toshiba       | Satellite A135              | Notebook    | [91f5602ed7](https://linux-hardware.org/?probe=91f5602ed7) | Jul 26, 2023 |
| HP            | 8169                        | Desktop     | [f2885ba2de](https://linux-hardware.org/?probe=f2885ba2de) | Jul 26, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [74adf4cb3d](https://linux-hardware.org/?probe=74adf4cb3d) | Jul 26, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [9f384d336d](https://linux-hardware.org/?probe=9f384d336d) | Jul 23, 2023 |
| Gigabyte      | X570S AERO G                | Desktop     | [8e3dbf7ff9](https://linux-hardware.org/?probe=8e3dbf7ff9) | Jul 23, 2023 |
| Dell          | Latitude E7440              | Notebook    | [ffa2aad2b5](https://linux-hardware.org/?probe=ffa2aad2b5) | Jul 21, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [2c2c4bdcf2](https://linux-hardware.org/?probe=2c2c4bdcf2) | Jul 21, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [4f00ba88de](https://linux-hardware.org/?probe=4f00ba88de) | Jul 21, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [6a048ba2cc](https://linux-hardware.org/?probe=6a048ba2cc) | Jul 21, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [0d5bd8b2f2](https://linux-hardware.org/?probe=0d5bd8b2f2) | Jul 20, 2023 |
| AMI           | Intel                       | Convertible | [896ed95f63](https://linux-hardware.org/?probe=896ed95f63) | Jul 19, 2023 |
| MSI           | IONA                        | Desktop     | [7b8b6c38e1](https://linux-hardware.org/?probe=7b8b6c38e1) | Jul 18, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [4ad55cf9da](https://linux-hardware.org/?probe=4ad55cf9da) | Jul 16, 2023 |
| Lenovo        | B5400 80B6QB0               | Notebook    | [7108435241](https://linux-hardware.org/?probe=7108435241) | Jul 15, 2023 |
| ASUSTek       | J1800I-A                    | Desktop     | [ce7f031b0a](https://linux-hardware.org/?probe=ce7f031b0a) | Jul 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [cf9bdab1ee](https://linux-hardware.org/?probe=cf9bdab1ee) | Jul 13, 2023 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | Notebook    | [f742573138](https://linux-hardware.org/?probe=f742573138) | Jul 12, 2023 |
| Dell          | 0J3C2F A00                  | Desktop     | [b3770db2e8](https://linux-hardware.org/?probe=b3770db2e8) | Jul 12, 2023 |
| Dell          | 0J3C2F A00                  | Desktop     | [d7d8d93ac1](https://linux-hardware.org/?probe=d7d8d93ac1) | Jul 10, 2023 |
| ASUSTek       | P7P55D DELUXE               | Desktop     | [ecba1dae0a](https://linux-hardware.org/?probe=ecba1dae0a) | Jul 09, 2023 |
| Notebook      | NP5x_NP6x_NP7xRNJ_RNH       | Notebook    | [7663e77bff](https://linux-hardware.org/?probe=7663e77bff) | Jul 09, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [003c30f690](https://linux-hardware.org/?probe=003c30f690) | Jul 09, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [76a4853c56](https://linux-hardware.org/?probe=76a4853c56) | Jul 08, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [624fca7465](https://linux-hardware.org/?probe=624fca7465) | Jul 07, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [d09af80a65](https://linux-hardware.org/?probe=d09af80a65) | Jul 07, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B2502CBA... | Notebook    | [397adc6b70](https://linux-hardware.org/?probe=397adc6b70) | Jul 06, 2023 |
| Lenovo        | ThinkPad E570 20H50074MC    | Notebook    | [029e84bf8a](https://linux-hardware.org/?probe=029e84bf8a) | Jul 06, 2023 |
| Dell          | 05XGC8 A01                  | Desktop     | [ef4d169d77](https://linux-hardware.org/?probe=ef4d169d77) | Jul 05, 2023 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [33e4bac631](https://linux-hardware.org/?probe=33e4bac631) | Jul 05, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [b0432f19ba](https://linux-hardware.org/?probe=b0432f19ba) | Jul 05, 2023 |
| HP            | ProBook 455 15.6 inch G9... | Notebook    | [bedadd4478](https://linux-hardware.org/?probe=bedadd4478) | Jul 05, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1e57d7c40d](https://linux-hardware.org/?probe=1e57d7c40d) | Jul 05, 2023 |
| HP            | EliteBook 8770w             | Notebook    | [8f298fa9aa](https://linux-hardware.org/?probe=8f298fa9aa) | Jul 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [73e054c849](https://linux-hardware.org/?probe=73e054c849) | Jul 04, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | Notebook    | [5d2bd9c3ce](https://linux-hardware.org/?probe=5d2bd9c3ce) | Jul 04, 2023 |
| Dell          | 05XGC8 A01                  | Desktop     | [eada4fe260](https://linux-hardware.org/?probe=eada4fe260) | Jul 02, 2023 |
| AMI           | Intel                       | Notebook    | [65aafdb0b0](https://linux-hardware.org/?probe=65aafdb0b0) | Jul 02, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [7beeaf657d](https://linux-hardware.org/?probe=7beeaf657d) | Jul 02, 2023 |
| Dell          | 0T656F A02                  | Desktop     | [e9b879f3ff](https://linux-hardware.org/?probe=e9b879f3ff) | Jul 02, 2023 |
| MSI           | A320M GAMING PRO            | Desktop     | [7bdc183ddc](https://linux-hardware.org/?probe=7bdc183ddc) | Jul 02, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [05394ee8a5](https://linux-hardware.org/?probe=05394ee8a5) | Jul 02, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [37a73c8939](https://linux-hardware.org/?probe=37a73c8939) | Jul 01, 2023 |
| Acer          | Swift SF314-42              | Notebook    | [c5820f8068](https://linux-hardware.org/?probe=c5820f8068) | Jul 01, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [f22f547276](https://linux-hardware.org/?probe=f22f547276) | Jul 01, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [07ab83bef1](https://linux-hardware.org/?probe=07ab83bef1) | Jun 30, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [fcf9a0fd47](https://linux-hardware.org/?probe=fcf9a0fd47) | Jun 30, 2023 |
| UMAX          | VisionBook-N12R             | Notebook    | [6144190349](https://linux-hardware.org/?probe=6144190349) | Jun 30, 2023 |
| Acer          | NC-A515-51G-59DM            | Notebook    | [a521f2cc60](https://linux-hardware.org/?probe=a521f2cc60) | Jun 29, 2023 |
| ASUSTek       | H87M-E                      | Desktop     | [7e7af2948c](https://linux-hardware.org/?probe=7e7af2948c) | Jun 29, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [5496b9130e](https://linux-hardware.org/?probe=5496b9130e) | Jun 29, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [607da926f3](https://linux-hardware.org/?probe=607da926f3) | Jun 28, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [8112f38f33](https://linux-hardware.org/?probe=8112f38f33) | Jun 27, 2023 |
| Lenovo        | ThinkCentre M58p 3285A1G    | Desktop     | [d5e4ce2efa](https://linux-hardware.org/?probe=d5e4ce2efa) | Jun 25, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [223911e8f0](https://linux-hardware.org/?probe=223911e8f0) | Jun 25, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [234a73d6b0](https://linux-hardware.org/?probe=234a73d6b0) | Jun 23, 2023 |
| MSI           | A320M GAMING PRO            | Desktop     | [70b7839ea8](https://linux-hardware.org/?probe=70b7839ea8) | Jun 23, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [5879c3e9ad](https://linux-hardware.org/?probe=5879c3e9ad) | Jun 22, 2023 |
| ASUSTek       | GL552VX                     | Notebook    | [348e36123f](https://linux-hardware.org/?probe=348e36123f) | Jun 22, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [51b4c8d9ef](https://linux-hardware.org/?probe=51b4c8d9ef) | Jun 22, 2023 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [61ba243843](https://linux-hardware.org/?probe=61ba243843) | Jun 21, 2023 |
| Lenovo        | 01GR176                     | Server      | [6d28cbec97](https://linux-hardware.org/?probe=6d28cbec97) | Jun 21, 2023 |
| ASRockRack    | X470D4U                     | Desktop     | [9e0ba5032b](https://linux-hardware.org/?probe=9e0ba5032b) | Jun 21, 2023 |
| Lenovo        | 310C SDK0J40697 WIN 3305... | Mini pc     | [0aa3b8d433](https://linux-hardware.org/?probe=0aa3b8d433) | Jun 21, 2023 |
| ASRock        | X570 Extreme4               | Desktop     | [3ff2c9e4cc](https://linux-hardware.org/?probe=3ff2c9e4cc) | Jun 21, 2023 |
| Shuttle       | FX21V10                     | Desktop     | [d77f55da92](https://linux-hardware.org/?probe=d77f55da92) | Jun 19, 2023 |
| Shuttle       | FX21V10                     | Desktop     | [71a0effa3a](https://linux-hardware.org/?probe=71a0effa3a) | Jun 19, 2023 |
| Acer          | Aspire ES1-420              | Notebook    | [76aab864d4](https://linux-hardware.org/?probe=76aab864d4) | Jun 19, 2023 |
| Dell          | Latitude E6540              | Notebook    | [3721b0046f](https://linux-hardware.org/?probe=3721b0046f) | Jun 19, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [0806a6be0a](https://linux-hardware.org/?probe=0806a6be0a) | Jun 19, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [0054d0c92e](https://linux-hardware.org/?probe=0054d0c92e) | Jun 18, 2023 |
| ASUSTek       | A55BM-E                     | Desktop     | [98b3d14b06](https://linux-hardware.org/?probe=98b3d14b06) | Jun 17, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [d9e1222bc3](https://linux-hardware.org/?probe=d9e1222bc3) | Jun 17, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [706eeef80f](https://linux-hardware.org/?probe=706eeef80f) | Jun 15, 2023 |
| Dell          | Latitude 5420               | Notebook    | [d3327c76f1](https://linux-hardware.org/?probe=d3327c76f1) | Jun 15, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [17c4d68066](https://linux-hardware.org/?probe=17c4d68066) | Jun 14, 2023 |
| Acer          | Aspire ES1-420              | Notebook    | [5c3a2078ca](https://linux-hardware.org/?probe=5c3a2078ca) | Jun 14, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [c74f83bbea](https://linux-hardware.org/?probe=c74f83bbea) | Jun 13, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [77ce1af9f8](https://linux-hardware.org/?probe=77ce1af9f8) | Jun 13, 2023 |
| MSI           | IONA                        | Desktop     | [86535af79b](https://linux-hardware.org/?probe=86535af79b) | Jun 13, 2023 |
| Dell          | 0PTTT9 A01                  | Desktop     | [4d019c4a6f](https://linux-hardware.org/?probe=4d019c4a6f) | Jun 13, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | Notebook    | [edf817eef9](https://linux-hardware.org/?probe=edf817eef9) | Jun 12, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | Notebook    | [5c98700539](https://linux-hardware.org/?probe=5c98700539) | Jun 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [f6e70e460f](https://linux-hardware.org/?probe=f6e70e460f) | Jun 11, 2023 |
| Dell          | Latitude 5420               | Notebook    | [956a995580](https://linux-hardware.org/?probe=956a995580) | Jun 09, 2023 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [09ba95bf3b](https://linux-hardware.org/?probe=09ba95bf3b) | Jun 08, 2023 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [a2c63b86b0](https://linux-hardware.org/?probe=a2c63b86b0) | Jun 08, 2023 |
| ASUSTek       | PN51-E1                     | Mini pc     | [0f41ab04b6](https://linux-hardware.org/?probe=0f41ab04b6) | Jun 07, 2023 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [9d0aa12b81](https://linux-hardware.org/?probe=9d0aa12b81) | Jun 06, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [92d0de412b](https://linux-hardware.org/?probe=92d0de412b) | Jun 06, 2023 |
| Dell          | Latitude 7400               | Notebook    | [9968377d89](https://linux-hardware.org/?probe=9968377d89) | Jun 06, 2023 |
| MSI           | H110M ECO                   | Desktop     | [4215fc5993](https://linux-hardware.org/?probe=4215fc5993) | Jun 05, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [d7a2c59432](https://linux-hardware.org/?probe=d7a2c59432) | Jun 05, 2023 |
| Gigabyte      | B360M HD3                   | Desktop     | [fcb1b60578](https://linux-hardware.org/?probe=fcb1b60578) | Jun 04, 2023 |
| MSI           | GF615M-P33                  | Desktop     | [84f237f434](https://linux-hardware.org/?probe=84f237f434) | Jun 04, 2023 |
| Acer          | Veriton M2631 V:1.0         | Desktop     | [e64369d2ec](https://linux-hardware.org/?probe=e64369d2ec) | Jun 03, 2023 |
| Gigabyte      | H67MA-USB3-B3               | Desktop     | [1908e7e6f5](https://linux-hardware.org/?probe=1908e7e6f5) | Jun 03, 2023 |
| Lenovo        | ThinkPad T420 4236WQD       | Notebook    | [69a63f31e1](https://linux-hardware.org/?probe=69a63f31e1) | Jun 03, 2023 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [7ae3c54a4c](https://linux-hardware.org/?probe=7ae3c54a4c) | Jun 03, 2023 |
| Timi          | A35S                        | Notebook    | [c9ce47a446](https://linux-hardware.org/?probe=c9ce47a446) | Jun 01, 2023 |
| HP            | 158A                        | Desktop     | [39d4ab7307](https://linux-hardware.org/?probe=39d4ab7307) | May 31, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [ab97cb7f09](https://linux-hardware.org/?probe=ab97cb7f09) | May 30, 2023 |
| Intel         | NUC11TNBi5 M11904-404       | Mini pc     | [b706fad8dc](https://linux-hardware.org/?probe=b706fad8dc) | May 30, 2023 |
| Gigabyte      | X399 AORUS PRO-CF           | Desktop     | [b00cd1c84e](https://linux-hardware.org/?probe=b00cd1c84e) | May 30, 2023 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [b3966a1d81](https://linux-hardware.org/?probe=b3966a1d81) | May 30, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [ad3464fd76](https://linux-hardware.org/?probe=ad3464fd76) | May 30, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [643710864a](https://linux-hardware.org/?probe=643710864a) | May 30, 2023 |
| Lenovo        | ThinkPad T480 20L6S42000    | Notebook    | [ea6330526c](https://linux-hardware.org/?probe=ea6330526c) | May 29, 2023 |
| Gigabyte      | Z690 UD                     | Desktop     | [feab206ef4](https://linux-hardware.org/?probe=feab206ef4) | May 29, 2023 |
| ASRock        | X670E Taichi Carrara        | Desktop     | [7b001db11a](https://linux-hardware.org/?probe=7b001db11a) | May 29, 2023 |
| Acer          | Aspire 7540                 | Notebook    | [82fcb3124c](https://linux-hardware.org/?probe=82fcb3124c) | May 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [56fca4583d](https://linux-hardware.org/?probe=56fca4583d) | May 28, 2023 |
| Lenovo        | ThinkPad P51 20HJS01Q04     | Notebook    | [520eb0074c](https://linux-hardware.org/?probe=520eb0074c) | May 26, 2023 |
| Lenovo        | ThinkPad T490 20N3S5DQ02    | Notebook    | [bb00a96df8](https://linux-hardware.org/?probe=bb00a96df8) | May 25, 2023 |
| Unknown       | Unknown                     | Notebook    | [cfaffcaa0a](https://linux-hardware.org/?probe=cfaffcaa0a) | May 25, 2023 |
| Dell          | G15 5511                    | Notebook    | [3876065a3e](https://linux-hardware.org/?probe=3876065a3e) | May 24, 2023 |
| ASUSTek       | ASUS BR1100FKA BR1100FKA... | Convertible | [84b7538837](https://linux-hardware.org/?probe=84b7538837) | May 23, 2023 |
| Dell          | G5 5587                     | Notebook    | [18faf1497f](https://linux-hardware.org/?probe=18faf1497f) | May 23, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [2fffd70abb](https://linux-hardware.org/?probe=2fffd70abb) | May 23, 2023 |
| HP            | 1495                        | Desktop     | [200cab3da9](https://linux-hardware.org/?probe=200cab3da9) | May 23, 2023 |
| Lenovo        | 36C8 SDK0J40700 WIN 3258... | Desktop     | [7e8b42ab5f](https://linux-hardware.org/?probe=7e8b42ab5f) | May 22, 2023 |
| Dell          | Vostro 5620                 | Notebook    | [6e87c1ac87](https://linux-hardware.org/?probe=6e87c1ac87) | May 21, 2023 |
| Acer          | TravelMate Spin P414RN-4... | Convertible | [cb8bc926b8](https://linux-hardware.org/?probe=cb8bc926b8) | May 21, 2023 |
| HP            | 2B5E                        | Desktop     | [a221629f4d](https://linux-hardware.org/?probe=a221629f4d) | May 21, 2023 |
| Dell          | G15 5511                    | Notebook    | [ad4c2a0521](https://linux-hardware.org/?probe=ad4c2a0521) | May 21, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [0f8329fecb](https://linux-hardware.org/?probe=0f8329fecb) | May 20, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | Desktop     | [5da7add39a](https://linux-hardware.org/?probe=5da7add39a) | May 20, 2023 |
| MSI           | GF615M-P33                  | Desktop     | [09ae9aca26](https://linux-hardware.org/?probe=09ae9aca26) | May 19, 2023 |
| Acer          | TravelMate Spin P414RN-4... | Convertible | [69d4abb6e4](https://linux-hardware.org/?probe=69d4abb6e4) | May 18, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [a74f787d52](https://linux-hardware.org/?probe=a74f787d52) | May 18, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | Desktop     | [c3626b71ae](https://linux-hardware.org/?probe=c3626b71ae) | May 18, 2023 |
| Lenovo        | 36C8 SDK0J40700 WIN 3258... | Desktop     | [166ec29ce0](https://linux-hardware.org/?probe=166ec29ce0) | May 18, 2023 |
| HP            | ProBook 4540s               | Notebook    | [1ea4f5cce0](https://linux-hardware.org/?probe=1ea4f5cce0) | May 18, 2023 |
| MSI           | MAG B760M MORTAR WIFI       | Desktop     | [f7c208d0f0](https://linux-hardware.org/?probe=f7c208d0f0) | May 16, 2023 |
| Dell          | Latitude 5521               | Notebook    | [9f671f21c1](https://linux-hardware.org/?probe=9f671f21c1) | May 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [b4e8e5504e](https://linux-hardware.org/?probe=b4e8e5504e) | May 15, 2023 |
| Gigabyte      | H410M H V2                  | Desktop     | [1effa68567](https://linux-hardware.org/?probe=1effa68567) | May 15, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [c12ae2e393](https://linux-hardware.org/?probe=c12ae2e393) | May 15, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [14aeaeafe8](https://linux-hardware.org/?probe=14aeaeafe8) | May 15, 2023 |
| Lenovo        | NOK                         | Desktop     | [9c6f0bae8f](https://linux-hardware.org/?probe=9c6f0bae8f) | May 14, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [53f535546a](https://linux-hardware.org/?probe=53f535546a) | May 12, 2023 |
| Dell          | Latitude 7400               | Notebook    | [14de9baf53](https://linux-hardware.org/?probe=14de9baf53) | May 12, 2023 |
| Dell          | Vostro 5620                 | Notebook    | [5248735c71](https://linux-hardware.org/?probe=5248735c71) | May 12, 2023 |
| Dell          | Vostro 5620                 | Notebook    | [daa5b232fc](https://linux-hardware.org/?probe=daa5b232fc) | May 12, 2023 |
| eMachines     | E620                        | Notebook    | [827a81facc](https://linux-hardware.org/?probe=827a81facc) | May 11, 2023 |
| TUXEDO        | Polaris 15 AMD Gen1         | Notebook    | [81e75bd6e7](https://linux-hardware.org/?probe=81e75bd6e7) | May 11, 2023 |
| Lenovo        | IdeaPad Duet 3 10IGL5 82... | Tablet      | [e63410f299](https://linux-hardware.org/?probe=e63410f299) | May 09, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [c941da38cd](https://linux-hardware.org/?probe=c941da38cd) | May 08, 2023 |
| MSI           | H81M-P33                    | Desktop     | [b5c0679341](https://linux-hardware.org/?probe=b5c0679341) | May 08, 2023 |
| Dell          | Latitude E7450              | Notebook    | [0eff8f87c6](https://linux-hardware.org/?probe=0eff8f87c6) | May 08, 2023 |
| Fujitsu Si... | LIFEBOOK S6420              | Notebook    | [953d03df07](https://linux-hardware.org/?probe=953d03df07) | May 08, 2023 |
| Fujitsu Si... | LIFEBOOK S6420              | Notebook    | [ee52ca7ce5](https://linux-hardware.org/?probe=ee52ca7ce5) | May 08, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [b979325eea](https://linux-hardware.org/?probe=b979325eea) | May 07, 2023 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Desktop     | [701907636a](https://linux-hardware.org/?probe=701907636a) | May 06, 2023 |
| ASUSTek       | P8Z68 DELUXE/GEN3           | Desktop     | [288e495c16](https://linux-hardware.org/?probe=288e495c16) | May 06, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [61a2726a1d](https://linux-hardware.org/?probe=61a2726a1d) | May 04, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [0767486bb6](https://linux-hardware.org/?probe=0767486bb6) | May 04, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [3c6e20e260](https://linux-hardware.org/?probe=3c6e20e260) | May 04, 2023 |
| Valve         | Jupiter                     | Notebook    | [1f41754528](https://linux-hardware.org/?probe=1f41754528) | May 03, 2023 |
| Apple         | MacBookAir3,1               | Notebook    | [97d802a5d6](https://linux-hardware.org/?probe=97d802a5d6) | May 03, 2023 |
| Lenovo        | ThinkPad W541 20EGS0B010    | Notebook    | [3f87bce0eb](https://linux-hardware.org/?probe=3f87bce0eb) | May 01, 2023 |
| Gigabyte      | B660M DS3H DDR4             | Desktop     | [ab48e66c38](https://linux-hardware.org/?probe=ab48e66c38) | May 01, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [1fb0ca13ff](https://linux-hardware.org/?probe=1fb0ca13ff) | May 01, 2023 |
| Gigabyte      | B660M DS3H DDR4             | Desktop     | [0e035d415e](https://linux-hardware.org/?probe=0e035d415e) | May 01, 2023 |
| Acer          | Extensa 5620                | Notebook    | [415396fa78](https://linux-hardware.org/?probe=415396fa78) | Apr 30, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [e0367e684f](https://linux-hardware.org/?probe=e0367e684f) | Apr 28, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [fed0a1a719](https://linux-hardware.org/?probe=fed0a1a719) | Apr 28, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [e2c8068a7d](https://linux-hardware.org/?probe=e2c8068a7d) | Apr 28, 2023 |
| Lenovo        | NOK                         | Desktop     | [cf3db26781](https://linux-hardware.org/?probe=cf3db26781) | Apr 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [92be2563a8](https://linux-hardware.org/?probe=92be2563a8) | Apr 28, 2023 |
| Acer          | Aspire E1-572G              | Notebook    | [6c35501215](https://linux-hardware.org/?probe=6c35501215) | Apr 27, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [486535a4d3](https://linux-hardware.org/?probe=486535a4d3) | Apr 27, 2023 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | Notebook    | [ca568572da](https://linux-hardware.org/?probe=ca568572da) | Apr 26, 2023 |
| Dell          | Inspiron 3793               | Notebook    | [f9d337a0a1](https://linux-hardware.org/?probe=f9d337a0a1) | Apr 26, 2023 |
| ASUSTek       | G750JS                      | Notebook    | [fa228f68e4](https://linux-hardware.org/?probe=fa228f68e4) | Apr 26, 2023 |
| ASUSTek       | G750JS                      | Notebook    | [33bc801258](https://linux-hardware.org/?probe=33bc801258) | Apr 26, 2023 |
| HP            | ProBook 4540s               | Notebook    | [ac831756d0](https://linux-hardware.org/?probe=ac831756d0) | Apr 26, 2023 |
| Valve         | Jupiter                     | Notebook    | [9b44e9bc2c](https://linux-hardware.org/?probe=9b44e9bc2c) | Apr 25, 2023 |
| Valve         | Jupiter                     | Notebook    | [7c7421ffeb](https://linux-hardware.org/?probe=7c7421ffeb) | Apr 25, 2023 |
| Dell          | System XPS L502X            | Notebook    | [4fd4992d0f](https://linux-hardware.org/?probe=4fd4992d0f) | Apr 24, 2023 |
| HP            | ProBook 4540s               | Notebook    | [db866a1036](https://linux-hardware.org/?probe=db866a1036) | Apr 24, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [68d1859c93](https://linux-hardware.org/?probe=68d1859c93) | Apr 23, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [1cc955413f](https://linux-hardware.org/?probe=1cc955413f) | Apr 23, 2023 |
| Pegatron      | 2AB5                        | Desktop     | [5f771d8ee5](https://linux-hardware.org/?probe=5f771d8ee5) | Apr 23, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [db069c8b89](https://linux-hardware.org/?probe=db069c8b89) | Apr 21, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [91f538e2ab](https://linux-hardware.org/?probe=91f538e2ab) | Apr 21, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [085b87dc27](https://linux-hardware.org/?probe=085b87dc27) | Apr 21, 2023 |
| UMAX          | VisionBook 14Wa Pro         | Notebook    | [525241657b](https://linux-hardware.org/?probe=525241657b) | Apr 20, 2023 |
| UMAX          | VisionBook 14Wa Pro         | Notebook    | [07e2728dfe](https://linux-hardware.org/?probe=07e2728dfe) | Apr 20, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [42ca23ca64](https://linux-hardware.org/?probe=42ca23ca64) | Apr 20, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [e315ba7088](https://linux-hardware.org/?probe=e315ba7088) | Apr 20, 2023 |
| Lenovo        | ThinkPad P52 20MAS5KM00     | Notebook    | [06ab19cc37](https://linux-hardware.org/?probe=06ab19cc37) | Apr 20, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [ec0b554256](https://linux-hardware.org/?probe=ec0b554256) | Apr 19, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [f158ac4161](https://linux-hardware.org/?probe=f158ac4161) | Apr 17, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [980c6d63d6](https://linux-hardware.org/?probe=980c6d63d6) | Apr 16, 2023 |
| Acer          | Aspire ES1-731G             | Notebook    | [1ef0f89c83](https://linux-hardware.org/?probe=1ef0f89c83) | Apr 15, 2023 |
| HP            | ProBook 455 G7              | Notebook    | [b6615d2b7b](https://linux-hardware.org/?probe=b6615d2b7b) | Apr 15, 2023 |
| UMAX          | VisionBook 15Wg Plus        | Notebook    | [59d15de09e](https://linux-hardware.org/?probe=59d15de09e) | Apr 15, 2023 |
| Gigabyte      | AX370-Gaming K7 se3         | Desktop     | [5439790362](https://linux-hardware.org/?probe=5439790362) | Apr 15, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [429e68a4ac](https://linux-hardware.org/?probe=429e68a4ac) | Apr 14, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | Desktop     | [9518f3e6d8](https://linux-hardware.org/?probe=9518f3e6d8) | Apr 13, 2023 |
| HP            | ProBook 450 G6              | Notebook    | [3364cf411c](https://linux-hardware.org/?probe=3364cf411c) | Apr 13, 2023 |
| Acer          | Aspire one                  | Notebook    | [481024a7cb](https://linux-hardware.org/?probe=481024a7cb) | Apr 12, 2023 |
| Gigabyte      | AX370-Gaming K7 se3         | Desktop     | [ef5cbba147](https://linux-hardware.org/?probe=ef5cbba147) | Apr 12, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [9a592d3392](https://linux-hardware.org/?probe=9a592d3392) | Apr 11, 2023 |
| Acer          | Aspire A515-47              | Notebook    | [8a78c5b08f](https://linux-hardware.org/?probe=8a78c5b08f) | Apr 11, 2023 |
| Lenovo        | Dory CRB                    | Desktop     | [cab4258e1b](https://linux-hardware.org/?probe=cab4258e1b) | Apr 11, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [fff8cbca92](https://linux-hardware.org/?probe=fff8cbca92) | Apr 10, 2023 |
| Lenovo        | ThinkCentre M90p 5536W67    | Desktop     | [f67448dd99](https://linux-hardware.org/?probe=f67448dd99) | Apr 09, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [bf531c6e34](https://linux-hardware.org/?probe=bf531c6e34) | Apr 09, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [2652354b7a](https://linux-hardware.org/?probe=2652354b7a) | Apr 09, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [e5393f2dd6](https://linux-hardware.org/?probe=e5393f2dd6) | Apr 07, 2023 |
| Dell          | 0J3C2F A00                  | Desktop     | [e2c3600e8b](https://linux-hardware.org/?probe=e2c3600e8b) | Apr 07, 2023 |
| MSI           | J1800I                      | Desktop     | [983e4f18d4](https://linux-hardware.org/?probe=983e4f18d4) | Apr 06, 2023 |
| MSI           | B150 PC MATE                | Desktop     | [da2d2d3d5c](https://linux-hardware.org/?probe=da2d2d3d5c) | Apr 05, 2023 |
| ASRock        | Z87 Killer                  | Desktop     | [ec627dea03](https://linux-hardware.org/?probe=ec627dea03) | Apr 05, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [3a1b0cca6b](https://linux-hardware.org/?probe=3a1b0cca6b) | Apr 04, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [b1168b92c0](https://linux-hardware.org/?probe=b1168b92c0) | Apr 03, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [f013c5ca48](https://linux-hardware.org/?probe=f013c5ca48) | Apr 03, 2023 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [5499373552](https://linux-hardware.org/?probe=5499373552) | Apr 03, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [70ed012fb4](https://linux-hardware.org/?probe=70ed012fb4) | Apr 03, 2023 |
| Notebook      | NJ50GU                      | Notebook    | [91e860cd94](https://linux-hardware.org/?probe=91e860cd94) | Apr 02, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [e3078a63c3](https://linux-hardware.org/?probe=e3078a63c3) | Apr 02, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [1c8c26f5c0](https://linux-hardware.org/?probe=1c8c26f5c0) | Apr 02, 2023 |
| MSI           | GF615M-P33                  | Desktop     | [022324033e](https://linux-hardware.org/?probe=022324033e) | Apr 02, 2023 |
| HP            | 250 G3                      | Notebook    | [2030ba57b9](https://linux-hardware.org/?probe=2030ba57b9) | Apr 02, 2023 |
| Pegatron      | 2ACF                        | Desktop     | [c015b7fd50](https://linux-hardware.org/?probe=c015b7fd50) | Apr 01, 2023 |
| Dell          | Latitude 5511               | Notebook    | [86b4fcff61](https://linux-hardware.org/?probe=86b4fcff61) | Apr 01, 2023 |
| Lenovo        | ThinkPad T420s 4173R44      | Notebook    | [84e9a5f3d9](https://linux-hardware.org/?probe=84e9a5f3d9) | Apr 01, 2023 |
| UMAX          | VisionBook 14Wa Plus        | Notebook    | [ea8016c4a5](https://linux-hardware.org/?probe=ea8016c4a5) | Apr 01, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [0014e52bf3](https://linux-hardware.org/?probe=0014e52bf3) | Mar 31, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [2b23ce3fed](https://linux-hardware.org/?probe=2b23ce3fed) | Mar 31, 2023 |
| ASUSTek       | Zenbook UN5401QAB_UN5401... | Convertible | [448d1a491c](https://linux-hardware.org/?probe=448d1a491c) | Mar 31, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [0ffc78eac6](https://linux-hardware.org/?probe=0ffc78eac6) | Mar 30, 2023 |
| ASUSTek       | F7L                         | Notebook    | [8d6f90f843](https://linux-hardware.org/?probe=8d6f90f843) | Mar 29, 2023 |
| ASUSTek       | F7L                         | Notebook    | [cdc5ab3b8a](https://linux-hardware.org/?probe=cdc5ab3b8a) | Mar 29, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [6599d32d74](https://linux-hardware.org/?probe=6599d32d74) | Mar 29, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [64bef0aff5](https://linux-hardware.org/?probe=64bef0aff5) | Mar 29, 2023 |
| ASUSTek       | PN41-S1                     | Mini pc     | [95da0c6b8a](https://linux-hardware.org/?probe=95da0c6b8a) | Mar 28, 2023 |
| Lenovo        | ThinkPad T580 20LAS4L216    | Notebook    | [9c3464baf9](https://linux-hardware.org/?probe=9c3464baf9) | Mar 27, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [eb82e949b2](https://linux-hardware.org/?probe=eb82e949b2) | Mar 27, 2023 |
| MSI           | B250M PRO-VDH 2018-05-07    | Desktop     | [6f7e481d06](https://linux-hardware.org/?probe=6f7e481d06) | Mar 27, 2023 |
| ASRock        | Z87 Killer                  | Desktop     | [53ec55f5ae](https://linux-hardware.org/?probe=53ec55f5ae) | Mar 27, 2023 |
| Shenzhen M... | HX90G                       | Desktop     | [b6bd6cab94](https://linux-hardware.org/?probe=b6bd6cab94) | Mar 26, 2023 |
| MSI           | GF615M-P33                  | Desktop     | [51276a5f00](https://linux-hardware.org/?probe=51276a5f00) | Mar 25, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [df8f872445](https://linux-hardware.org/?probe=df8f872445) | Mar 25, 2023 |
| Lenovo        | G780                        | Notebook    | [1ad87e5add](https://linux-hardware.org/?probe=1ad87e5add) | Mar 23, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | Notebook    | [aa102c68bf](https://linux-hardware.org/?probe=aa102c68bf) | Mar 23, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [47992266f4](https://linux-hardware.org/?probe=47992266f4) | Mar 22, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [dc56e35adc](https://linux-hardware.org/?probe=dc56e35adc) | Mar 22, 2023 |
| Lenovo        | ThinkPad T440 20B7S3N304    | Notebook    | [af39e826be](https://linux-hardware.org/?probe=af39e826be) | Mar 22, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [de7c628210](https://linux-hardware.org/?probe=de7c628210) | Mar 22, 2023 |
| Gigabyte      | GA-990FX-GAMING             | Desktop     | [7f1e3cf271](https://linux-hardware.org/?probe=7f1e3cf271) | Mar 20, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [9b2ff390f6](https://linux-hardware.org/?probe=9b2ff390f6) | Mar 20, 2023 |
| Dell          | Latitude 5590               | Notebook    | [49922a3223](https://linux-hardware.org/?probe=49922a3223) | Mar 19, 2023 |
| Acer          | TravelMate 2490             | Notebook    | [5a21a61bef](https://linux-hardware.org/?probe=5a21a61bef) | Mar 19, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [b637fa75c8](https://linux-hardware.org/?probe=b637fa75c8) | Mar 18, 2023 |
| MSI           | B365M PRO-VDH               | Desktop     | [3332cb54e5](https://linux-hardware.org/?probe=3332cb54e5) | Mar 18, 2023 |
| Acer          | TravelMate 7750ZG           | Notebook    | [5108cfe57c](https://linux-hardware.org/?probe=5108cfe57c) | Mar 16, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [5bf235f5d3](https://linux-hardware.org/?probe=5bf235f5d3) | Mar 16, 2023 |
| Dell          | Inspiron 5767               | Notebook    | [b7c8484508](https://linux-hardware.org/?probe=b7c8484508) | Mar 14, 2023 |
| Lenovo        | Yoga 510-14AST 80S9         | Convertible | [31c28e071b](https://linux-hardware.org/?probe=31c28e071b) | Mar 13, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [7f3525f6ef](https://linux-hardware.org/?probe=7f3525f6ef) | Mar 12, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [e82b110a76](https://linux-hardware.org/?probe=e82b110a76) | Mar 12, 2023 |
| HP            | 09CCh                       | Desktop     | [e122b11e42](https://linux-hardware.org/?probe=e122b11e42) | Mar 12, 2023 |
| Dell          | Inspiron 5748               | Notebook    | [ef020a54d0](https://linux-hardware.org/?probe=ef020a54d0) | Mar 12, 2023 |
| Lenovo        | Yoga 510-14AST 80S9         | Convertible | [e51e1c905c](https://linux-hardware.org/?probe=e51e1c905c) | Mar 11, 2023 |
| Lenovo        | ThinkPad Edge E330 3354A... | Notebook    | [b343b9ea49](https://linux-hardware.org/?probe=b343b9ea49) | Mar 11, 2023 |
| HP            | 09CCh                       | Desktop     | [9421be2c59](https://linux-hardware.org/?probe=9421be2c59) | Mar 11, 2023 |
| ASUSTek       | K54LY                       | Notebook    | [a846675d7f](https://linux-hardware.org/?probe=a846675d7f) | Mar 09, 2023 |
| Lenovo        | ThinkPad L440 20ASS29900    | Notebook    | [fda0cb7297](https://linux-hardware.org/?probe=fda0cb7297) | Mar 08, 2023 |
| Dell          | Latitude E6420              | Notebook    | [c3384b7787](https://linux-hardware.org/?probe=c3384b7787) | Mar 07, 2023 |
| Lenovo        | ThinkPad L440 20ASS29900    | Notebook    | [707155405b](https://linux-hardware.org/?probe=707155405b) | Mar 07, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [e88ffa7e1d](https://linux-hardware.org/?probe=e88ffa7e1d) | Mar 07, 2023 |
| HP            | ProBook 455 G7              | Notebook    | [0faa2cd96c](https://linux-hardware.org/?probe=0faa2cd96c) | Mar 06, 2023 |
| Dell          | Inspiron 5406 2n1           | Convertible | [70d063d399](https://linux-hardware.org/?probe=70d063d399) | Mar 05, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [ba97297cf9](https://linux-hardware.org/?probe=ba97297cf9) | Mar 04, 2023 |
| ASUSTek       | ROG Strix G531GT            | Notebook    | [810e15295b](https://linux-hardware.org/?probe=810e15295b) | Mar 03, 2023 |
| Dell          | Latitude 5421               | Notebook    | [16d34b8b56](https://linux-hardware.org/?probe=16d34b8b56) | Mar 03, 2023 |
| ASUSTek       | 1016P                       | Notebook    | [739984c8cf](https://linux-hardware.org/?probe=739984c8cf) | Mar 03, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS0... | Notebook    | [e73235d592](https://linux-hardware.org/?probe=e73235d592) | Mar 03, 2023 |
| ASRock        | Z170 Extreme4               | Desktop     | [428377b153](https://linux-hardware.org/?probe=428377b153) | Mar 03, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [2c6ad91981](https://linux-hardware.org/?probe=2c6ad91981) | Mar 02, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | Notebook    | [ceb6fb20b2](https://linux-hardware.org/?probe=ceb6fb20b2) | Mar 02, 2023 |
| ASUSTek       | 1016P                       | Notebook    | [29798857a5](https://linux-hardware.org/?probe=29798857a5) | Mar 02, 2023 |
| ASUSTek       | X555LA                      | Notebook    | [5dbbffb04e](https://linux-hardware.org/?probe=5dbbffb04e) | Mar 02, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [9e63190b6f](https://linux-hardware.org/?probe=9e63190b6f) | Mar 01, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [10f864cbb0](https://linux-hardware.org/?probe=10f864cbb0) | Mar 01, 2023 |
| Acer          | TravelMate Spin P614RN-5... | Convertible | [8c36af11ab](https://linux-hardware.org/?probe=8c36af11ab) | Mar 01, 2023 |
| ASUSTek       | AM1I-A                      | Desktop     | [b5fe605f8b](https://linux-hardware.org/?probe=b5fe605f8b) | Feb 27, 2023 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [2071bc50ce](https://linux-hardware.org/?probe=2071bc50ce) | Feb 27, 2023 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [472c035387](https://linux-hardware.org/?probe=472c035387) | Feb 27, 2023 |
| Dell          | 0MH651                      | Desktop     | [7921e9f8bc](https://linux-hardware.org/?probe=7921e9f8bc) | Feb 27, 2023 |
| UMAX          | VisionBook-N12R             | Notebook    | [2477ae9a0e](https://linux-hardware.org/?probe=2477ae9a0e) | Feb 27, 2023 |
| Lenovo        | Yoga 510-14AST 80S9         | Convertible | [0ea2a54b39](https://linux-hardware.org/?probe=0ea2a54b39) | Feb 26, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [9b2a57b7d2](https://linux-hardware.org/?probe=9b2a57b7d2) | Feb 26, 2023 |
| Standard      | Unknown                     | Notebook    | [9d002e0593](https://linux-hardware.org/?probe=9d002e0593) | Feb 26, 2023 |
| HP            | ProBook 445 G7              | Notebook    | [f2671a0f62](https://linux-hardware.org/?probe=f2671a0f62) | Feb 25, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [f0fa613cd2](https://linux-hardware.org/?probe=f0fa613cd2) | Feb 25, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [1c1e5c991f](https://linux-hardware.org/?probe=1c1e5c991f) | Feb 25, 2023 |
| ASRock        | B550M Phantom Gaming 4      | Desktop     | [8bfeed43ef](https://linux-hardware.org/?probe=8bfeed43ef) | Feb 24, 2023 |
| MSI           | C847MS-E33                  | Desktop     | [698d950f05](https://linux-hardware.org/?probe=698d950f05) | Feb 24, 2023 |
| Lenovo        | ThinkPad L15 Gen1 20U700... | Notebook    | [6829c25808](https://linux-hardware.org/?probe=6829c25808) | Feb 23, 2023 |
| Lenovo        | ThinkPad L15 Gen1 20U700... | Notebook    | [ca9a037662](https://linux-hardware.org/?probe=ca9a037662) | Feb 23, 2023 |
| Dell          | Latitude 5420               | Notebook    | [231c7534d3](https://linux-hardware.org/?probe=231c7534d3) | Feb 21, 2023 |
| Dell          | 02YYK5 A00                  | Desktop     | [cff33d0b1e](https://linux-hardware.org/?probe=cff33d0b1e) | Feb 20, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [503fe663b4](https://linux-hardware.org/?probe=503fe663b4) | Feb 20, 2023 |
| HP            | Laptop 15-rb0xx             | Notebook    | [3dd7359a43](https://linux-hardware.org/?probe=3dd7359a43) | Feb 20, 2023 |
| HP            | Laptop 15-rb0xx             | Notebook    | [53ef54922c](https://linux-hardware.org/?probe=53ef54922c) | Feb 20, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [4a77848908](https://linux-hardware.org/?probe=4a77848908) | Feb 20, 2023 |
| Toshiba       | Satellite L50D-B            | Notebook    | [689c37d3b7](https://linux-hardware.org/?probe=689c37d3b7) | Feb 19, 2023 |
| Dell          | Vostro1710                  | Notebook    | [91b1af7ed6](https://linux-hardware.org/?probe=91b1af7ed6) | Feb 19, 2023 |
| Standard      | Unknown                     | Notebook    | [149bdc4e40](https://linux-hardware.org/?probe=149bdc4e40) | Feb 19, 2023 |
| ASUSTek       | PRIME H570M-PLUS            | Desktop     | [4fac3ddf27](https://linux-hardware.org/?probe=4fac3ddf27) | Feb 19, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [e2facdc650](https://linux-hardware.org/?probe=e2facdc650) | Feb 19, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [82db23bd7f](https://linux-hardware.org/?probe=82db23bd7f) | Feb 19, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [4c3c50a992](https://linux-hardware.org/?probe=4c3c50a992) | Feb 18, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [e6391763b2](https://linux-hardware.org/?probe=e6391763b2) | Feb 17, 2023 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [0e2199617b](https://linux-hardware.org/?probe=0e2199617b) | Feb 17, 2023 |
| ASRock        | B550M-HDV                   | Desktop     | [755006e226](https://linux-hardware.org/?probe=755006e226) | Feb 17, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [6c8bdf1f73](https://linux-hardware.org/?probe=6c8bdf1f73) | Feb 17, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [89f9d45c66](https://linux-hardware.org/?probe=89f9d45c66) | Feb 17, 2023 |
| Lenovo        | ThinkPad X270 20HN0015GE    | Notebook    | [f546833d76](https://linux-hardware.org/?probe=f546833d76) | Feb 17, 2023 |
| Lenovo        | ThinkPad X250 20CM001XMC    | Notebook    | [1026c10fa9](https://linux-hardware.org/?probe=1026c10fa9) | Feb 16, 2023 |
| Dell          | 03NVJ6 A00                  | Desktop     | [d118fe4ba2](https://linux-hardware.org/?probe=d118fe4ba2) | Feb 16, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [0255141f61](https://linux-hardware.org/?probe=0255141f61) | Feb 15, 2023 |
| HP            | ProBook 470 G4              | Notebook    | [8730091665](https://linux-hardware.org/?probe=8730091665) | Feb 15, 2023 |
| HP            | Pavilion g6                 | Notebook    | [8a53743bd0](https://linux-hardware.org/?probe=8a53743bd0) | Feb 15, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [849a50c7fd](https://linux-hardware.org/?probe=849a50c7fd) | Feb 15, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [bc69f33fa2](https://linux-hardware.org/?probe=bc69f33fa2) | Feb 15, 2023 |
| Acer          | Swift SF314-42              | Notebook    | [938edcc32a](https://linux-hardware.org/?probe=938edcc32a) | Feb 15, 2023 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [ef3ee2ebf2](https://linux-hardware.org/?probe=ef3ee2ebf2) | Feb 14, 2023 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [cdd9011e76](https://linux-hardware.org/?probe=cdd9011e76) | Feb 13, 2023 |
| Lenovo        | IdeaPad U330p 20267         | Notebook    | [de30205f54](https://linux-hardware.org/?probe=de30205f54) | Feb 12, 2023 |
| Pegatron      | 2AB6                        | Desktop     | [65b3bb622e](https://linux-hardware.org/?probe=65b3bb622e) | Feb 12, 2023 |
| Lenovo        | IdeaPad U330p 20267         | Notebook    | [19700ab1bd](https://linux-hardware.org/?probe=19700ab1bd) | Feb 12, 2023 |
| MSI           | 2A9Ch                       | Desktop     | [934ca9b130](https://linux-hardware.org/?probe=934ca9b130) | Feb 12, 2023 |
| MSI           | 2A9Ch                       | Desktop     | [1a76baff0f](https://linux-hardware.org/?probe=1a76baff0f) | Feb 12, 2023 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [19547b9a43](https://linux-hardware.org/?probe=19547b9a43) | Feb 12, 2023 |
| MSI           | GX700                       | Notebook    | [11154709fd](https://linux-hardware.org/?probe=11154709fd) | Feb 11, 2023 |
| Pegatron      | 2AB6                        | Desktop     | [1f727ee133](https://linux-hardware.org/?probe=1f727ee133) | Feb 11, 2023 |
| Acer          | Aspire 5742G                | Notebook    | [1315dbeb6c](https://linux-hardware.org/?probe=1315dbeb6c) | Feb 11, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [2b4f9e9f21](https://linux-hardware.org/?probe=2b4f9e9f21) | Feb 11, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [e8fdc1676a](https://linux-hardware.org/?probe=e8fdc1676a) | Feb 10, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [16d6cdad97](https://linux-hardware.org/?probe=16d6cdad97) | Feb 09, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | Notebook    | [26f7ad82d9](https://linux-hardware.org/?probe=26f7ad82d9) | Feb 08, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | Notebook    | [d54546bce9](https://linux-hardware.org/?probe=d54546bce9) | Feb 08, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [731d910d0c](https://linux-hardware.org/?probe=731d910d0c) | Feb 08, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [d7157a7862](https://linux-hardware.org/?probe=d7157a7862) | Feb 07, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | Notebook    | [c0aab06a5c](https://linux-hardware.org/?probe=c0aab06a5c) | Feb 07, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | Notebook    | [830072137a](https://linux-hardware.org/?probe=830072137a) | Feb 07, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [8cb1801046](https://linux-hardware.org/?probe=8cb1801046) | Feb 07, 2023 |
| Intel         | NUC5PPYB H76558-109         | Mini pc     | [a3384bd952](https://linux-hardware.org/?probe=a3384bd952) | Feb 06, 2023 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [6490f4cb92](https://linux-hardware.org/?probe=6490f4cb92) | Feb 05, 2023 |
| MSI           | GE620/GE620DX/FX620DX/FX... | Notebook    | [e9082b6ebf](https://linux-hardware.org/?probe=e9082b6ebf) | Feb 04, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [4214ad8f29](https://linux-hardware.org/?probe=4214ad8f29) | Feb 04, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [330da24dc9](https://linux-hardware.org/?probe=330da24dc9) | Feb 04, 2023 |
| HP            | ProBook 4530s               | Notebook    | [9ff88cbe9a](https://linux-hardware.org/?probe=9ff88cbe9a) | Feb 03, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [922ee5ede0](https://linux-hardware.org/?probe=922ee5ede0) | Feb 03, 2023 |
| Intel         | X79M-S                      | Desktop     | [91ab5e33ed](https://linux-hardware.org/?probe=91ab5e33ed) | Feb 03, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [0b73c3afe8](https://linux-hardware.org/?probe=0b73c3afe8) | Feb 03, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [8ae0d42e1a](https://linux-hardware.org/?probe=8ae0d42e1a) | Feb 03, 2023 |
| HP            | Stream Notebook PC 14       | Notebook    | [69628da41b](https://linux-hardware.org/?probe=69628da41b) | Feb 03, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [3bcca39276](https://linux-hardware.org/?probe=3bcca39276) | Feb 02, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [1651e1e5af](https://linux-hardware.org/?probe=1651e1e5af) | Feb 02, 2023 |
| Intel         | NUC7i5BNB J31144-310        | Mini pc     | [87fe173b18](https://linux-hardware.org/?probe=87fe173b18) | Feb 02, 2023 |
| ASUSTek       | G10DK                       | Desktop     | [80e1fa4ed8](https://linux-hardware.org/?probe=80e1fa4ed8) | Feb 01, 2023 |
| ASUSTek       | GL702VT                     | Notebook    | [83abe24c59](https://linux-hardware.org/?probe=83abe24c59) | Feb 01, 2023 |
| Lenovo        | ThinkPad E520 1143JYG       | Notebook    | [87735dd3b0](https://linux-hardware.org/?probe=87735dd3b0) | Feb 01, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [b7fce61d74](https://linux-hardware.org/?probe=b7fce61d74) | Jan 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [1c798340db](https://linux-hardware.org/?probe=1c798340db) | Jan 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [3ecd91770e](https://linux-hardware.org/?probe=3ecd91770e) | Jan 30, 2023 |
| HP            | Compaq CQ58                 | Notebook    | [63dfd6ca48](https://linux-hardware.org/?probe=63dfd6ca48) | Jan 30, 2023 |
| Dell          | Inspiron 14 5410 2-in-1     | Convertible | [36caf406ce](https://linux-hardware.org/?probe=36caf406ce) | Jan 29, 2023 |
| Lenovo        | ThinkPad T580 20LA0025MX    | Notebook    | [c5e4274143](https://linux-hardware.org/?probe=c5e4274143) | Jan 29, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [6444a93633](https://linux-hardware.org/?probe=6444a93633) | Jan 29, 2023 |
| ASUSTek       | V241DA                      | All in one  | [72df681f16](https://linux-hardware.org/?probe=72df681f16) | Jan 28, 2023 |
| ASUSTek       | X200MA                      | Notebook    | [1c1f2d4d5b](https://linux-hardware.org/?probe=1c1f2d4d5b) | Jan 28, 2023 |
| Timi          | A35S                        | Notebook    | [b6611f9b22](https://linux-hardware.org/?probe=b6611f9b22) | Jan 28, 2023 |
| HP            | Pavilion dv6500             | Notebook    | [ec9bed5b5d](https://linux-hardware.org/?probe=ec9bed5b5d) | Jan 28, 2023 |
| HP            | Pavilion dv6500             | Notebook    | [e225ce26a1](https://linux-hardware.org/?probe=e225ce26a1) | Jan 28, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [d87ac57c19](https://linux-hardware.org/?probe=d87ac57c19) | Jan 27, 2023 |
| Lenovo        | MAHOBAY 31900003 STD        | All in one  | [d75e472005](https://linux-hardware.org/?probe=d75e472005) | Jan 26, 2023 |
| UMAX          | VisionBook 10Wr Tab         | Convertible | [6d747e3841](https://linux-hardware.org/?probe=6d747e3841) | Jan 26, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [bb83f545f7](https://linux-hardware.org/?probe=bb83f545f7) | Jan 24, 2023 |
| Dell          | Latitude 5530               | Notebook    | [b365359e5f](https://linux-hardware.org/?probe=b365359e5f) | Jan 24, 2023 |
| Dell          | Precision 3530              | Notebook    | [f0fa541c85](https://linux-hardware.org/?probe=f0fa541c85) | Jan 24, 2023 |
| HP            | 8750                        | Desktop     | [e8b02ffbb5](https://linux-hardware.org/?probe=e8b02ffbb5) | Jan 23, 2023 |
| Intel         | X79M-S                      | Desktop     | [ccad523936](https://linux-hardware.org/?probe=ccad523936) | Jan 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [ae270718a7](https://linux-hardware.org/?probe=ae270718a7) | Jan 22, 2023 |
| ASUSTek       | UX303LN                     | Notebook    | [60f8946cdf](https://linux-hardware.org/?probe=60f8946cdf) | Jan 21, 2023 |
| Lenovo        | Yoga 700-14ISK 80QD         | Notebook    | [4e07ace043](https://linux-hardware.org/?probe=4e07ace043) | Jan 21, 2023 |
| ASUSTek       | UX303LN                     | Notebook    | [846e3df466](https://linux-hardware.org/?probe=846e3df466) | Jan 21, 2023 |
| ASUSTek       | H81M-C                      | Desktop     | [ec12d33bd7](https://linux-hardware.org/?probe=ec12d33bd7) | Jan 21, 2023 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [5a32ba3cd1](https://linux-hardware.org/?probe=5a32ba3cd1) | Jan 21, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [66c806fbfe](https://linux-hardware.org/?probe=66c806fbfe) | Jan 21, 2023 |
| ASUSTek       | X555LF                      | Notebook    | [7220c25a3b](https://linux-hardware.org/?probe=7220c25a3b) | Jan 20, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d77bf1f32b](https://linux-hardware.org/?probe=d77bf1f32b) | Jan 20, 2023 |
| UMAX          | VisionBook 12Wr             | Notebook    | [0707d617f7](https://linux-hardware.org/?probe=0707d617f7) | Jan 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [6c2dd878d0](https://linux-hardware.org/?probe=6c2dd878d0) | Jan 19, 2023 |
| ASRock        | X99 Taichi                  | Desktop     | [793777c14e](https://linux-hardware.org/?probe=793777c14e) | Jan 19, 2023 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [0e8d25f649](https://linux-hardware.org/?probe=0e8d25f649) | Jan 19, 2023 |
| ASUSTek       | PRIME H570M-PLUS            | Desktop     | [4932579d3e](https://linux-hardware.org/?probe=4932579d3e) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [5f73278ca0](https://linux-hardware.org/?probe=5f73278ca0) | Jan 19, 2023 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [a1b3ac9ccc](https://linux-hardware.org/?probe=a1b3ac9ccc) | Jan 19, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [f7fcfb7b18](https://linux-hardware.org/?probe=f7fcfb7b18) | Jan 19, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [b11a63e25d](https://linux-hardware.org/?probe=b11a63e25d) | Jan 19, 2023 |
| ASUSTek       | 1011PX                      | Notebook    | [4c7cc6f614](https://linux-hardware.org/?probe=4c7cc6f614) | Jan 19, 2023 |
| Lenovo        | ThinkPad E550 20DF0081MC    | Notebook    | [1b7e734f36](https://linux-hardware.org/?probe=1b7e734f36) | Jan 19, 2023 |
| ASRock        | AM1H-ITX                    | Desktop     | [7427c997d7](https://linux-hardware.org/?probe=7427c997d7) | Jan 18, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IHU5 8... | Notebook    | [5b0e671bb8](https://linux-hardware.org/?probe=5b0e671bb8) | Jan 18, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [395a44652b](https://linux-hardware.org/?probe=395a44652b) | Jan 17, 2023 |
| Dynabook      | PORTEGE X30W-K              | Convertible | [5c3d7c049e](https://linux-hardware.org/?probe=5c3d7c049e) | Jan 17, 2023 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | Notebook    | [5ebc1885c3](https://linux-hardware.org/?probe=5ebc1885c3) | Jan 17, 2023 |
| Dell          | 0PM2CW A04                  | Server      | [5f3e7922cd](https://linux-hardware.org/?probe=5f3e7922cd) | Jan 16, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [fa4fd9061f](https://linux-hardware.org/?probe=fa4fd9061f) | Jan 16, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [6841633faf](https://linux-hardware.org/?probe=6841633faf) | Jan 16, 2023 |
| HP            | Pavilion dv6500             | Notebook    | [33985f088a](https://linux-hardware.org/?probe=33985f088a) | Jan 16, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [3677d8f4e7](https://linux-hardware.org/?probe=3677d8f4e7) | Jan 15, 2023 |
| Dell          | 0PM2CW A04                  | Server      | [b4bc427969](https://linux-hardware.org/?probe=b4bc427969) | Jan 15, 2023 |
| HP            | 250 G3                      | Notebook    | [717fbc7972](https://linux-hardware.org/?probe=717fbc7972) | Jan 15, 2023 |
| UMAX          | U-Box N42                   | Mini pc     | [4f778e38f0](https://linux-hardware.org/?probe=4f778e38f0) | Jan 14, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [291dceb273](https://linux-hardware.org/?probe=291dceb273) | Jan 14, 2023 |
| ASUSTek       | P5KPL-AM                    | Desktop     | [9d4f877d3d](https://linux-hardware.org/?probe=9d4f877d3d) | Jan 14, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [32f2651aa1](https://linux-hardware.org/?probe=32f2651aa1) | Jan 14, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [bd4516127b](https://linux-hardware.org/?probe=bd4516127b) | Jan 14, 2023 |
| HP            | ProBook 6560b               | Notebook    | [a9eba68b79](https://linux-hardware.org/?probe=a9eba68b79) | Jan 14, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [3c475bc193](https://linux-hardware.org/?probe=3c475bc193) | Jan 14, 2023 |
| Gigabyte      | B75M-D2V                    | Desktop     | [8f9d1f85ee](https://linux-hardware.org/?probe=8f9d1f85ee) | Jan 14, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [d60bab803e](https://linux-hardware.org/?probe=d60bab803e) | Jan 13, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [362d8c4594](https://linux-hardware.org/?probe=362d8c4594) | Jan 13, 2023 |
| Lenovo        | ThinkPad T450 20BUA0UG00    | Notebook    | [b0854ecbf8](https://linux-hardware.org/?probe=b0854ecbf8) | Jan 12, 2023 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [1d6a667a5b](https://linux-hardware.org/?probe=1d6a667a5b) | Jan 11, 2023 |
| HP            | 304Ah                       | Desktop     | [c79a932800](https://linux-hardware.org/?probe=c79a932800) | Jan 11, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [a02943108d](https://linux-hardware.org/?probe=a02943108d) | Jan 11, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [88ffbf550c](https://linux-hardware.org/?probe=88ffbf550c) | Jan 11, 2023 |
| Acer          | Extensa 2519                | Notebook    | [c044faaa05](https://linux-hardware.org/?probe=c044faaa05) | Jan 11, 2023 |
| Dell          | Precision 7710              | Notebook    | [fada5459cb](https://linux-hardware.org/?probe=fada5459cb) | Jan 11, 2023 |
| Dell          | 0PTTT9 A01                  | Desktop     | [fa17d61c80](https://linux-hardware.org/?probe=fa17d61c80) | Jan 11, 2023 |
| HP            | Laptop 15-rb0xx             | Notebook    | [fd8d969adb](https://linux-hardware.org/?probe=fd8d969adb) | Jan 11, 2023 |
| UMAX          | VisionBook 15Wg Plus        | Notebook    | [e4c19089b5](https://linux-hardware.org/?probe=e4c19089b5) | Jan 11, 2023 |
| Gigabyte      | H170-D3H-CF                 | Desktop     | [8064745798](https://linux-hardware.org/?probe=8064745798) | Jan 10, 2023 |
| Dell          | Precision 5510              | Notebook    | [22a344ddad](https://linux-hardware.org/?probe=22a344ddad) | Jan 09, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [42f10f6d45](https://linux-hardware.org/?probe=42f10f6d45) | Jan 09, 2023 |
| Dell          | Precision 7710              | Notebook    | [0e64a34c3e](https://linux-hardware.org/?probe=0e64a34c3e) | Jan 09, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [3e39bca3ed](https://linux-hardware.org/?probe=3e39bca3ed) | Jan 09, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [2f03fd41c1](https://linux-hardware.org/?probe=2f03fd41c1) | Jan 09, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [92205d303f](https://linux-hardware.org/?probe=92205d303f) | Jan 08, 2023 |
| ASRock        | B450M Pro4-F                | Desktop     | [182a43f2b4](https://linux-hardware.org/?probe=182a43f2b4) | Jan 08, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [b808a6be1a](https://linux-hardware.org/?probe=b808a6be1a) | Jan 08, 2023 |
| Lenovo        | ThinkPad X230 2320JNG       | Notebook    | [29d3023af5](https://linux-hardware.org/?probe=29d3023af5) | Jan 08, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [667330c83f](https://linux-hardware.org/?probe=667330c83f) | Jan 07, 2023 |
| Dell          | 0C27VV A00                  | Desktop     | [317f136007](https://linux-hardware.org/?probe=317f136007) | Jan 07, 2023 |
| UMAX          | VisionBook N14G Plus        | Notebook    | [412180b4de](https://linux-hardware.org/?probe=412180b4de) | Jan 06, 2023 |
| Acer          | TravelMate B115-M           | Notebook    | [c39cf71ff8](https://linux-hardware.org/?probe=c39cf71ff8) | Jan 05, 2023 |
| ASUSTek       | X405UA                      | Notebook    | [c56206ea8a](https://linux-hardware.org/?probe=c56206ea8a) | Jan 05, 2023 |
| Acer          | Aspire E1-531G              | Notebook    | [9b5a0200df](https://linux-hardware.org/?probe=9b5a0200df) | Jan 04, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [abdf0ab0b9](https://linux-hardware.org/?probe=abdf0ab0b9) | Jan 03, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [5c14d6ea96](https://linux-hardware.org/?probe=5c14d6ea96) | Jan 03, 2023 |
| ASRock        | AM1H-ITX                    | Desktop     | [3b32e784a3](https://linux-hardware.org/?probe=3b32e784a3) | Jan 03, 2023 |
| Intel         | X79M-S                      | Desktop     | [3b38d8023e](https://linux-hardware.org/?probe=3b38d8023e) | Jan 03, 2023 |
| Acer          | Aspire E1-531G              | Notebook    | [47813fa627](https://linux-hardware.org/?probe=47813fa627) | Jan 03, 2023 |
| HP            | ProBook 635 Aero G8         | Notebook    | [f710248f3c](https://linux-hardware.org/?probe=f710248f3c) | Jan 02, 2023 |
| Google        | Chell                       | Notebook    | [02a0ae3bea](https://linux-hardware.org/?probe=02a0ae3bea) | Jan 02, 2023 |
| Valve         | Jupiter                     | Notebook    | [dc3612b4e1](https://linux-hardware.org/?probe=dc3612b4e1) | Jan 01, 2023 |
| Acer          | Aspire ES1-131              | Notebook    | [79d4fe0592](https://linux-hardware.org/?probe=79d4fe0592) | Jan 01, 2023 |
| Acer          | Aspire ES1-131              | Notebook    | [aeb6ecee74](https://linux-hardware.org/?probe=aeb6ecee74) | Jan 01, 2023 |
| Acer          | Aspire A515-47              | Notebook    | [aaf0830ffc](https://linux-hardware.org/?probe=aaf0830ffc) | Jan 01, 2023 |
| Intel         | X79M-S                      | Desktop     | [5c97a3976d](https://linux-hardware.org/?probe=5c97a3976d) | Jan 01, 2023 |
| Fujitsu Si... | D2420 S26361-D2420          | Desktop     | [9e8c937daa](https://linux-hardware.org/?probe=9e8c937daa) | Dec 31, 2022 |
| Gigabyte      | B75M-D3V                    | Desktop     | [ce23d2f7cd](https://linux-hardware.org/?probe=ce23d2f7cd) | Dec 31, 2022 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [cecef0575d](https://linux-hardware.org/?probe=cecef0575d) | Dec 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [bd53b75b7b](https://linux-hardware.org/?probe=bd53b75b7b) | Dec 30, 2022 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [498c8c83e2](https://linux-hardware.org/?probe=498c8c83e2) | Dec 30, 2022 |
| Lenovo        | 31900003 STD                | All in one  | [4cc2e8cadd](https://linux-hardware.org/?probe=4cc2e8cadd) | Dec 30, 2022 |
| Fujitsu Si... | D2420 S26361-D2420          | Desktop     | [019236854d](https://linux-hardware.org/?probe=019236854d) | Dec 30, 2022 |
| Fujitsu Si... | D2420 S26361-D2420          | Desktop     | [d6f064e643](https://linux-hardware.org/?probe=d6f064e643) | Dec 30, 2022 |
| MSI           | B75MA-P45                   | Desktop     | [f0b4df8849](https://linux-hardware.org/?probe=f0b4df8849) | Dec 29, 2022 |
| MSI           | Z97 PC Mate                 | Desktop     | [1b7e70ab6e](https://linux-hardware.org/?probe=1b7e70ab6e) | Dec 29, 2022 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | Notebook    | [2b646304f0](https://linux-hardware.org/?probe=2b646304f0) | Dec 29, 2022 |
| Lenovo        | ThinkPad T15 Gen 1 20S7S... | Notebook    | [74f8dcfbb4](https://linux-hardware.org/?probe=74f8dcfbb4) | Dec 29, 2022 |
| Fujitsu       | LIFEBOOK E736               | Notebook    | [8d54484965](https://linux-hardware.org/?probe=8d54484965) | Dec 29, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [9e6b5e5ebf](https://linux-hardware.org/?probe=9e6b5e5ebf) | Dec 27, 2022 |
| Gigabyte      | M61SME-S2                   | Desktop     | [5d0485ba40](https://linux-hardware.org/?probe=5d0485ba40) | Dec 26, 2022 |
| Gigabyte      | M61SME-S2                   | Desktop     | [d68451099d](https://linux-hardware.org/?probe=d68451099d) | Dec 26, 2022 |
| UMAX          | VisionBook 14Wa Pro         | Notebook    | [7eb49ce0ab](https://linux-hardware.org/?probe=7eb49ce0ab) | Dec 24, 2022 |
| UMAX          | VisionBook 14Wa Pro         | Notebook    | [4123115ef0](https://linux-hardware.org/?probe=4123115ef0) | Dec 24, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [08a1ad1c63](https://linux-hardware.org/?probe=08a1ad1c63) | Dec 24, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [1c7e7f8dd2](https://linux-hardware.org/?probe=1c7e7f8dd2) | Dec 24, 2022 |
| Dell          | 0T656F A02                  | Desktop     | [35aa2eee2a](https://linux-hardware.org/?probe=35aa2eee2a) | Dec 23, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | Desktop     | [c5cc33f2c6](https://linux-hardware.org/?probe=c5cc33f2c6) | Dec 23, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | Desktop     | [ffbf35fd33](https://linux-hardware.org/?probe=ffbf35fd33) | Dec 23, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [3d90b10b72](https://linux-hardware.org/?probe=3d90b10b72) | Dec 22, 2022 |
| Lenovo        | XiaoXinPro 16ACH 2021 82... | Notebook    | [2b25ab8790](https://linux-hardware.org/?probe=2b25ab8790) | Dec 22, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [64f6471e58](https://linux-hardware.org/?probe=64f6471e58) | Dec 21, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [b01c41faa0](https://linux-hardware.org/?probe=b01c41faa0) | Dec 21, 2022 |
| HP            | 09CCh                       | Desktop     | [60d8cc87c7](https://linux-hardware.org/?probe=60d8cc87c7) | Dec 20, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [af14f0c425](https://linux-hardware.org/?probe=af14f0c425) | Dec 20, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [e7393fd2b7](https://linux-hardware.org/?probe=e7393fd2b7) | Dec 20, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [cf62b1c520](https://linux-hardware.org/?probe=cf62b1c520) | Dec 20, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [2a2f618c62](https://linux-hardware.org/?probe=2a2f618c62) | Dec 19, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [c20be92503](https://linux-hardware.org/?probe=c20be92503) | Dec 19, 2022 |
| UMAX          | 13Wr-Flex                   | Convertible | [487bef515a](https://linux-hardware.org/?probe=487bef515a) | Dec 18, 2022 |
| UMAX          | 13Wr-Flex                   | Convertible | [669c43b4f3](https://linux-hardware.org/?probe=669c43b4f3) | Dec 18, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | Notebook    | [3fe5be03b1](https://linux-hardware.org/?probe=3fe5be03b1) | Dec 18, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | Notebook    | [b34d0f3a2c](https://linux-hardware.org/?probe=b34d0f3a2c) | Dec 18, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [4f41f354cd](https://linux-hardware.org/?probe=4f41f354cd) | Dec 18, 2022 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [c106327357](https://linux-hardware.org/?probe=c106327357) | Dec 18, 2022 |
| Dell          | 0Y2MRG A00                  | Desktop     | [e5525b45b5](https://linux-hardware.org/?probe=e5525b45b5) | Dec 18, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [00cc810cfc](https://linux-hardware.org/?probe=00cc810cfc) | Dec 17, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [a6dfbac9f9](https://linux-hardware.org/?probe=a6dfbac9f9) | Dec 15, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [651fa58fbd](https://linux-hardware.org/?probe=651fa58fbd) | Dec 12, 2022 |
| Lenovo        | IdeaPad Duet 3 10IGL5 82... | Tablet      | [4471c4a012](https://linux-hardware.org/?probe=4471c4a012) | Dec 11, 2022 |
| HP            | Pavilion TS 11              | Notebook    | [db2a3e8ebb](https://linux-hardware.org/?probe=db2a3e8ebb) | Dec 11, 2022 |
| Acer          | Predator PH315-52           | Notebook    | [b5d4116615](https://linux-hardware.org/?probe=b5d4116615) | Dec 11, 2022 |
| Acer          | Predator PH315-52           | Notebook    | [144f698515](https://linux-hardware.org/?probe=144f698515) | Dec 11, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [6e2cf6514a](https://linux-hardware.org/?probe=6e2cf6514a) | Dec 10, 2022 |
| ASUSTek       | Zenbook UP5401EA_UP5401E... | Convertible | [6b999f972f](https://linux-hardware.org/?probe=6b999f972f) | Dec 10, 2022 |
| ASUSTek       | Zenbook UP5401EA_UP5401E... | Convertible | [c415ea37d7](https://linux-hardware.org/?probe=c415ea37d7) | Dec 10, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [b9ea8b5b2b](https://linux-hardware.org/?probe=b9ea8b5b2b) | Dec 08, 2022 |
| ASUSTek       | X55A                        | Notebook    | [283ef64c76](https://linux-hardware.org/?probe=283ef64c76) | Dec 08, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [e0de9de530](https://linux-hardware.org/?probe=e0de9de530) | Dec 07, 2022 |
| MSI           | Prestige 14 A11SCX          | Notebook    | [2b5a2c145c](https://linux-hardware.org/?probe=2b5a2c145c) | Dec 06, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | Notebook    | [2f14f32399](https://linux-hardware.org/?probe=2f14f32399) | Dec 06, 2022 |
| Lenovo        | ThinkPad T460 20FMS2291X    | Notebook    | [312119ddbd](https://linux-hardware.org/?probe=312119ddbd) | Dec 06, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [57b6a24933](https://linux-hardware.org/?probe=57b6a24933) | Dec 05, 2022 |
| MSI           | Prestige 14 A11SCX          | Notebook    | [ca5bc5dfe6](https://linux-hardware.org/?probe=ca5bc5dfe6) | Dec 05, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [2e39eb3e3b](https://linux-hardware.org/?probe=2e39eb3e3b) | Dec 04, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [7bde8b90c7](https://linux-hardware.org/?probe=7bde8b90c7) | Dec 04, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [059ed32da0](https://linux-hardware.org/?probe=059ed32da0) | Dec 03, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [e44ba4a41b](https://linux-hardware.org/?probe=e44ba4a41b) | Dec 03, 2022 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | Notebook    | [2b1a977b21](https://linux-hardware.org/?probe=2b1a977b21) | Dec 02, 2022 |
| ASUSTek       | A88XM-A/USB                 | Desktop     | [012f2dccba](https://linux-hardware.org/?probe=012f2dccba) | Dec 01, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [5955142015](https://linux-hardware.org/?probe=5955142015) | Dec 01, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [ea8b9066f6](https://linux-hardware.org/?probe=ea8b9066f6) | Nov 30, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [4e6ae396d9](https://linux-hardware.org/?probe=4e6ae396d9) | Nov 30, 2022 |
| UMAX          | U-Box N42                   | Mini pc     | [44170ddf90](https://linux-hardware.org/?probe=44170ddf90) | Nov 29, 2022 |
| UMAX          | U-Box N42                   | Mini pc     | [5953c13736](https://linux-hardware.org/?probe=5953c13736) | Nov 29, 2022 |
| HP            | 620                         | Notebook    | [5baeeace34](https://linux-hardware.org/?probe=5baeeace34) | Nov 28, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [97c63f232d](https://linux-hardware.org/?probe=97c63f232d) | Nov 28, 2022 |
| ASUSTek       | P5WD2-Premium               | Desktop     | [aad7343998](https://linux-hardware.org/?probe=aad7343998) | Nov 25, 2022 |
| Fujitsu       | LIFEBOOK E756               | Notebook    | [9e69bdbaff](https://linux-hardware.org/?probe=9e69bdbaff) | Nov 25, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [53b311f78c](https://linux-hardware.org/?probe=53b311f78c) | Nov 25, 2022 |
| Fujitsu       | LIFEBOOK E756               | Notebook    | [16acde36ab](https://linux-hardware.org/?probe=16acde36ab) | Nov 25, 2022 |
| ASRock        | X570 Pro4                   | Desktop     | [dad186aa07](https://linux-hardware.org/?probe=dad186aa07) | Nov 24, 2022 |
| HP            | 8750                        | Desktop     | [b1ac308187](https://linux-hardware.org/?probe=b1ac308187) | Nov 24, 2022 |
| ASRock        | X670E Taichi Carrara        | Desktop     | [7e844d7172](https://linux-hardware.org/?probe=7e844d7172) | Nov 24, 2022 |
| HP            | 0AACh                       | Desktop     | [9e37ad4151](https://linux-hardware.org/?probe=9e37ad4151) | Nov 23, 2022 |
| HP            | 620                         | Notebook    | [a09882989c](https://linux-hardware.org/?probe=a09882989c) | Nov 23, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [be7a4a88a1](https://linux-hardware.org/?probe=be7a4a88a1) | Nov 23, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [00faab62d7](https://linux-hardware.org/?probe=00faab62d7) | Nov 22, 2022 |
| HP            | 82B4                        | Desktop     | [c56604f389](https://linux-hardware.org/?probe=c56604f389) | Nov 21, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [2bd9abfe2c](https://linux-hardware.org/?probe=2bd9abfe2c) | Nov 20, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [1502b216b8](https://linux-hardware.org/?probe=1502b216b8) | Nov 20, 2022 |
| ASUSTek       | N73SV                       | Notebook    | [10840bac50](https://linux-hardware.org/?probe=10840bac50) | Nov 20, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [c57a9ae3d5](https://linux-hardware.org/?probe=c57a9ae3d5) | Nov 19, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [99ed91b58d](https://linux-hardware.org/?probe=99ed91b58d) | Nov 19, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [73c9daf454](https://linux-hardware.org/?probe=73c9daf454) | Nov 19, 2022 |
| Dell          | Precision 5510              | Notebook    | [a9467ec69d](https://linux-hardware.org/?probe=a9467ec69d) | Nov 18, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [3050d57edc](https://linux-hardware.org/?probe=3050d57edc) | Nov 17, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [9c25ade74d](https://linux-hardware.org/?probe=9c25ade74d) | Nov 16, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [3eaa12ef7a](https://linux-hardware.org/?probe=3eaa12ef7a) | Nov 16, 2022 |
| ASUSTek       | A55BM-E                     | Desktop     | [9ed6d8ee1e](https://linux-hardware.org/?probe=9ed6d8ee1e) | Nov 16, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [c7ac1636bc](https://linux-hardware.org/?probe=c7ac1636bc) | Nov 15, 2022 |
| ASUSTek       | N61Jv                       | Notebook    | [c8c143ccdd](https://linux-hardware.org/?probe=c8c143ccdd) | Nov 14, 2022 |
| Fujitsu       | D2679-B1 S26361-D2679-Bx... | Desktop     | [b8da32bca0](https://linux-hardware.org/?probe=b8da32bca0) | Nov 14, 2022 |
| Lenovo        | 0x36C4 SDK0K17763 WIN 18... | All in one  | [7a3f735fc0](https://linux-hardware.org/?probe=7a3f735fc0) | Nov 13, 2022 |
| ASUSTek       | N61Jv                       | Notebook    | [bc9518dbad](https://linux-hardware.org/?probe=bc9518dbad) | Nov 13, 2022 |
| Supermicro    | X9DAL                       | Desktop     | [56d4bd9f26](https://linux-hardware.org/?probe=56d4bd9f26) | Nov 13, 2022 |
| ASUSTek       | N61Jv                       | Notebook    | [a7e35fd231](https://linux-hardware.org/?probe=a7e35fd231) | Nov 12, 2022 |
| Dell          | Latitude 7480               | Notebook    | [62d1e401a4](https://linux-hardware.org/?probe=62d1e401a4) | Nov 12, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [48572e207b](https://linux-hardware.org/?probe=48572e207b) | Nov 12, 2022 |
| HP            | Pavilion g6                 | Notebook    | [dc20b80b34](https://linux-hardware.org/?probe=dc20b80b34) | Nov 12, 2022 |
| Dell          | Latitude 7480               | Notebook    | [350e3f7ee2](https://linux-hardware.org/?probe=350e3f7ee2) | Nov 11, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [fa27762189](https://linux-hardware.org/?probe=fa27762189) | Nov 11, 2022 |
| HP            | 872E                        | Mini pc     | [b2e72a139e](https://linux-hardware.org/?probe=b2e72a139e) | Nov 11, 2022 |
| HP            | Pavilion dv7                | Notebook    | [5b01559647](https://linux-hardware.org/?probe=5b01559647) | Nov 11, 2022 |
| ASUSTek       | K54LY                       | Notebook    | [721020a0fe](https://linux-hardware.org/?probe=721020a0fe) | Nov 11, 2022 |
| ASUSTek       | X550VXK                     | Notebook    | [f752e7959c](https://linux-hardware.org/?probe=f752e7959c) | Nov 10, 2022 |
| HP            | Pavilion g6                 | Notebook    | [9fa4176934](https://linux-hardware.org/?probe=9fa4176934) | Nov 09, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [558d46bf81](https://linux-hardware.org/?probe=558d46bf81) | Nov 08, 2022 |
| Packard Be... | EasyNote TK85               | Notebook    | [8a4f5a2c29](https://linux-hardware.org/?probe=8a4f5a2c29) | Nov 07, 2022 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [9f586bafd4](https://linux-hardware.org/?probe=9f586bafd4) | Nov 07, 2022 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [1d9cb16e2f](https://linux-hardware.org/?probe=1d9cb16e2f) | Nov 07, 2022 |
| HP            | ProBook 4530s               | Notebook    | [afb0629ea9](https://linux-hardware.org/?probe=afb0629ea9) | Nov 07, 2022 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [82bf0e80f0](https://linux-hardware.org/?probe=82bf0e80f0) | Nov 06, 2022 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [28af0c9803](https://linux-hardware.org/?probe=28af0c9803) | Nov 06, 2022 |
| Dell          | Inspiron 5515               | Notebook    | [fcb59bae39](https://linux-hardware.org/?probe=fcb59bae39) | Nov 06, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [4432a70f95](https://linux-hardware.org/?probe=4432a70f95) | Nov 06, 2022 |
| Dell          | Inspiron 5515               | Notebook    | [001308a248](https://linux-hardware.org/?probe=001308a248) | Nov 06, 2022 |
| ASRock        | AB350M Pro4                 | Desktop     | [96bd39af33](https://linux-hardware.org/?probe=96bd39af33) | Nov 05, 2022 |
| HP            | Pavilion g6                 | Notebook    | [5ad3928a6d](https://linux-hardware.org/?probe=5ad3928a6d) | Nov 05, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [bd1833650d](https://linux-hardware.org/?probe=bd1833650d) | Nov 04, 2022 |
| HP            | Pavilion g6                 | Notebook    | [38b8d5a898](https://linux-hardware.org/?probe=38b8d5a898) | Nov 04, 2022 |
| Acer          | Aspire 5738                 | Notebook    | [f5ac63680f](https://linux-hardware.org/?probe=f5ac63680f) | Nov 04, 2022 |
| HP            | 3029h                       | Desktop     | [2acf620628](https://linux-hardware.org/?probe=2acf620628) | Nov 04, 2022 |
| SLIMBOOK      | Executive                   | Notebook    | [cff86cc921](https://linux-hardware.org/?probe=cff86cc921) | Nov 04, 2022 |
| Sony          | VPCYB1S1E                   | Notebook    | [54d0a26de9](https://linux-hardware.org/?probe=54d0a26de9) | Nov 03, 2022 |
| UMAX          | VisionBook N15G Plus        | Notebook    | [eba9cd6286](https://linux-hardware.org/?probe=eba9cd6286) | Nov 03, 2022 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [e4f3828910](https://linux-hardware.org/?probe=e4f3828910) | Nov 01, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [21213fdeec](https://linux-hardware.org/?probe=21213fdeec) | Oct 31, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [919fad100f](https://linux-hardware.org/?probe=919fad100f) | Oct 31, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [6e9cb9c0e0](https://linux-hardware.org/?probe=6e9cb9c0e0) | Oct 29, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [eb22113dae](https://linux-hardware.org/?probe=eb22113dae) | Oct 29, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [f45ab957da](https://linux-hardware.org/?probe=f45ab957da) | Oct 28, 2022 |
| UMAX          | VisionBook 12Wi 64G         | Notebook    | [9fe98911c1](https://linux-hardware.org/?probe=9fe98911c1) | Oct 27, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [8a8967999b](https://linux-hardware.org/?probe=8a8967999b) | Oct 27, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [d58a7c30a9](https://linux-hardware.org/?probe=d58a7c30a9) | Oct 26, 2022 |
| HP            | 3029h                       | Desktop     | [46c9e39101](https://linux-hardware.org/?probe=46c9e39101) | Oct 26, 2022 |
| Dell          | Latitude E6440              | Notebook    | [307356784a](https://linux-hardware.org/?probe=307356784a) | Oct 26, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [5bc9d4bdc8](https://linux-hardware.org/?probe=5bc9d4bdc8) | Oct 26, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [212ce8900d](https://linux-hardware.org/?probe=212ce8900d) | Oct 26, 2022 |
| Acer          | Veriton NBU                 | Desktop     | [7be04cd3ed](https://linux-hardware.org/?probe=7be04cd3ed) | Oct 25, 2022 |
| ASUSTek       | ASUS EXPERTBOOK L1500CDA... | Notebook    | [3d86f7ccac](https://linux-hardware.org/?probe=3d86f7ccac) | Oct 25, 2022 |
| Gigabyte      | X58A-UD7                    | Desktop     | [6d3bf37ff3](https://linux-hardware.org/?probe=6d3bf37ff3) | Oct 25, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [025f4fa8ab](https://linux-hardware.org/?probe=025f4fa8ab) | Oct 22, 2022 |
| Dell          | 0J3C2F A00                  | Desktop     | [c97e42e738](https://linux-hardware.org/?probe=c97e42e738) | Oct 20, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [e3265d4cdc](https://linux-hardware.org/?probe=e3265d4cdc) | Oct 20, 2022 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [2ead6c088f](https://linux-hardware.org/?probe=2ead6c088f) | Oct 20, 2022 |
| HP            | Pavilion dv7                | Notebook    | [4c6edfec3e](https://linux-hardware.org/?probe=4c6edfec3e) | Oct 18, 2022 |
| HP            | Pavilion dv7                | Notebook    | [22031176a8](https://linux-hardware.org/?probe=22031176a8) | Oct 18, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [5335a66143](https://linux-hardware.org/?probe=5335a66143) | Oct 17, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [40c27af11f](https://linux-hardware.org/?probe=40c27af11f) | Oct 17, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [25fdbfba33](https://linux-hardware.org/?probe=25fdbfba33) | Oct 17, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [a6e072bc6b](https://linux-hardware.org/?probe=a6e072bc6b) | Oct 15, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [6bc730181f](https://linux-hardware.org/?probe=6bc730181f) | Oct 15, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [4e66c25e04](https://linux-hardware.org/?probe=4e66c25e04) | Oct 15, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [bddc33ef5a](https://linux-hardware.org/?probe=bddc33ef5a) | Oct 14, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [da04425205](https://linux-hardware.org/?probe=da04425205) | Oct 14, 2022 |
| Dell          | XPS 15 9550                 | Notebook    | [00d5f7c4b1](https://linux-hardware.org/?probe=00d5f7c4b1) | Oct 13, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [5074f8e471](https://linux-hardware.org/?probe=5074f8e471) | Oct 12, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [fb97ad01eb](https://linux-hardware.org/?probe=fb97ad01eb) | Oct 12, 2022 |
| ASUSTek       | PRIME A320M-E               | Desktop     | [ff58ea3dc1](https://linux-hardware.org/?probe=ff58ea3dc1) | Oct 12, 2022 |
| SmbiosType... | SmbiosType1_SystemProduc... | Notebook    | [d105b4c1f7](https://linux-hardware.org/?probe=d105b4c1f7) | Oct 11, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [e2d9db1022](https://linux-hardware.org/?probe=e2d9db1022) | Oct 10, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [22cf469faa](https://linux-hardware.org/?probe=22cf469faa) | Oct 10, 2022 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [3837291e33](https://linux-hardware.org/?probe=3837291e33) | Oct 10, 2022 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [cf3661bb7c](https://linux-hardware.org/?probe=cf3661bb7c) | Oct 09, 2022 |
| Lenovo        | ThinkPad Helix 2nd 20CHS... | Tablet      | [18ac5ede65](https://linux-hardware.org/?probe=18ac5ede65) | Oct 08, 2022 |
| Dell          | Latitude E7250              | Notebook    | [5ecb7bbb6c](https://linux-hardware.org/?probe=5ecb7bbb6c) | Oct 07, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [704da5b600](https://linux-hardware.org/?probe=704da5b600) | Oct 07, 2022 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [829a14598f](https://linux-hardware.org/?probe=829a14598f) | Oct 07, 2022 |
| ASUSTek       | 1001PXD                     | Notebook    | [524e4ab046](https://linux-hardware.org/?probe=524e4ab046) | Oct 06, 2022 |
| HP            | EliteBook 1040 G4           | Notebook    | [8a19b834c8](https://linux-hardware.org/?probe=8a19b834c8) | Oct 04, 2022 |
| Dell          | 0D28YY A01                  | Desktop     | [5c85c7623a](https://linux-hardware.org/?probe=5c85c7623a) | Oct 04, 2022 |
| Timi          | A35S                        | Notebook    | [fe7ad0ac13](https://linux-hardware.org/?probe=fe7ad0ac13) | Oct 03, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [13f60e066f](https://linux-hardware.org/?probe=13f60e066f) | Oct 03, 2022 |
| ASUSTek       | K54LY                       | Notebook    | [230a36c236](https://linux-hardware.org/?probe=230a36c236) | Oct 03, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [e3eb4cd95f](https://linux-hardware.org/?probe=e3eb4cd95f) | Oct 02, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [a4c73b484e](https://linux-hardware.org/?probe=a4c73b484e) | Oct 02, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [ff11bc4efb](https://linux-hardware.org/?probe=ff11bc4efb) | Oct 02, 2022 |
| ASUSTek       | K54LY                       | Notebook    | [7c19c1f557](https://linux-hardware.org/?probe=7c19c1f557) | Oct 02, 2022 |
| Acer          | Aspire 7540                 | Notebook    | [8e80ccea19](https://linux-hardware.org/?probe=8e80ccea19) | Oct 01, 2022 |
| ASUSTek       | K54LY                       | Notebook    | [98197c818f](https://linux-hardware.org/?probe=98197c818f) | Oct 01, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [92f9efe077](https://linux-hardware.org/?probe=92f9efe077) | Sep 30, 2022 |
| Notebook      | NJ50GU                      | Notebook    | [430d3b2873](https://linux-hardware.org/?probe=430d3b2873) | Sep 30, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [9015ce1da8](https://linux-hardware.org/?probe=9015ce1da8) | Sep 30, 2022 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [9377d23abd](https://linux-hardware.org/?probe=9377d23abd) | Sep 28, 2022 |
| Timi          | A35S                        | Notebook    | [bdb2ba4eab](https://linux-hardware.org/?probe=bdb2ba4eab) | Sep 27, 2022 |
| ASUSTek       | K53SV                       | Notebook    | [d2801f9560](https://linux-hardware.org/?probe=d2801f9560) | Sep 26, 2022 |
| Lenovo        | 3000 V100 076346G           | Notebook    | [0575c1ea4f](https://linux-hardware.org/?probe=0575c1ea4f) | Sep 26, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [923985941d](https://linux-hardware.org/?probe=923985941d) | Sep 25, 2022 |
| Timi          | RedmiBook 16                | Notebook    | [0a65bab615](https://linux-hardware.org/?probe=0a65bab615) | Sep 25, 2022 |
| Acer          | Aspire VN7-592G             | Notebook    | [cfc28181e5](https://linux-hardware.org/?probe=cfc28181e5) | Sep 25, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [262ff53f6a](https://linux-hardware.org/?probe=262ff53f6a) | Sep 25, 2022 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [4f9ff1b402](https://linux-hardware.org/?probe=4f9ff1b402) | Sep 24, 2022 |
| Toshiba       | Satellite A305              | Notebook    | [d1ed6b20cf](https://linux-hardware.org/?probe=d1ed6b20cf) | Sep 24, 2022 |
| Toshiba       | Satellite A305              | Notebook    | [9e04fb330b](https://linux-hardware.org/?probe=9e04fb330b) | Sep 24, 2022 |
| Timi          | A35S                        | Notebook    | [d0f195a77a](https://linux-hardware.org/?probe=d0f195a77a) | Sep 23, 2022 |
| Lenovo        | ThinkCentre Edge71 1578D... | Desktop     | [95dded89b8](https://linux-hardware.org/?probe=95dded89b8) | Sep 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [0b88f458d2](https://linux-hardware.org/?probe=0b88f458d2) | Sep 22, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [59219d6ded](https://linux-hardware.org/?probe=59219d6ded) | Sep 21, 2022 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [ea8ea96269](https://linux-hardware.org/?probe=ea8ea96269) | Sep 21, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [ea0ab53cac](https://linux-hardware.org/?probe=ea0ab53cac) | Sep 21, 2022 |
| Lenovo        | ThinkPad T410 2518Q6G       | Notebook    | [b0568eadf2](https://linux-hardware.org/?probe=b0568eadf2) | Sep 20, 2022 |
| ASUSTek       | AM1M-A                      | Desktop     | [a6e61a9993](https://linux-hardware.org/?probe=a6e61a9993) | Sep 19, 2022 |
| Gigabyte      | X58A-UD7                    | Desktop     | [b7f881a109](https://linux-hardware.org/?probe=b7f881a109) | Sep 19, 2022 |
| Gigabyte      | X58A-UD7                    | Desktop     | [59e7485a11](https://linux-hardware.org/?probe=59e7485a11) | Sep 19, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [dce5b5917c](https://linux-hardware.org/?probe=dce5b5917c) | Sep 18, 2022 |
| Acer          | Swift SF314-511             | Notebook    | [914d532c78](https://linux-hardware.org/?probe=914d532c78) | Sep 17, 2022 |
| Acer          | Swift SF314-511             | Notebook    | [a171efb42c](https://linux-hardware.org/?probe=a171efb42c) | Sep 17, 2022 |
| ASUSTek       | PRIME H310-PLUS             | Desktop     | [b9693eaf7c](https://linux-hardware.org/?probe=b9693eaf7c) | Sep 17, 2022 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [b5a0c6309d](https://linux-hardware.org/?probe=b5a0c6309d) | Sep 17, 2022 |
| Lenovo        | IdeaPad Y570 20091          | Notebook    | [5e2681360e](https://linux-hardware.org/?probe=5e2681360e) | Sep 15, 2022 |
| Dell          | Latitude 5430               | Notebook    | [617563f7a7](https://linux-hardware.org/?probe=617563f7a7) | Sep 14, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [bfd4a6b00a](https://linux-hardware.org/?probe=bfd4a6b00a) | Sep 13, 2022 |
| Lenovo        | ThinkPad T540p 20BF002CM... | Notebook    | [3343da6005](https://linux-hardware.org/?probe=3343da6005) | Sep 12, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [910cdee832](https://linux-hardware.org/?probe=910cdee832) | Sep 11, 2022 |
| Lenovo        | ThinkPad T430 23444ZG       | Notebook    | [d83eee9752](https://linux-hardware.org/?probe=d83eee9752) | Sep 11, 2022 |
| UMAX          | VisionBook N14G Plus        | Notebook    | [6d05deca49](https://linux-hardware.org/?probe=6d05deca49) | Sep 11, 2022 |
| UMAX          | VisionBook N15G Plus        | Notebook    | [d17fb4f8f9](https://linux-hardware.org/?probe=d17fb4f8f9) | Sep 11, 2022 |
| ASUSTek       | PN41                        | Mini pc     | [be7516b088](https://linux-hardware.org/?probe=be7516b088) | Sep 10, 2022 |
| Dell          | Latitude 5531               | Notebook    | [66eac260ef](https://linux-hardware.org/?probe=66eac260ef) | Sep 09, 2022 |
| Dell          | Precision 3551              | Notebook    | [78f7c77b35](https://linux-hardware.org/?probe=78f7c77b35) | Sep 09, 2022 |
| Lenovo        | B71-80 80RJ                 | Notebook    | [c16dc3a768](https://linux-hardware.org/?probe=c16dc3a768) | Sep 06, 2022 |
| Dell          | Latitude 5531               | Notebook    | [dff44a5e24](https://linux-hardware.org/?probe=dff44a5e24) | Sep 05, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [459e11c8ba](https://linux-hardware.org/?probe=459e11c8ba) | Sep 05, 2022 |
| Google        | Coral                       | Notebook    | [af898f9be4](https://linux-hardware.org/?probe=af898f9be4) | Sep 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [88392a79f5](https://linux-hardware.org/?probe=88392a79f5) | Sep 04, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [21183dcf00](https://linux-hardware.org/?probe=21183dcf00) | Sep 02, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [60b4add0a0](https://linux-hardware.org/?probe=60b4add0a0) | Sep 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [2a3eb4b772](https://linux-hardware.org/?probe=2a3eb4b772) | Sep 02, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [cc30fbdce2](https://linux-hardware.org/?probe=cc30fbdce2) | Sep 01, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | Notebook    | [c48154f5f4](https://linux-hardware.org/?probe=c48154f5f4) | Sep 01, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [4d1339ef49](https://linux-hardware.org/?probe=4d1339ef49) | Aug 31, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [0ca693e2dd](https://linux-hardware.org/?probe=0ca693e2dd) | Aug 31, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING     | Desktop     | [fc3200b967](https://linux-hardware.org/?probe=fc3200b967) | Aug 31, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [a01239fd83](https://linux-hardware.org/?probe=a01239fd83) | Aug 29, 2022 |
| HP            | EliteBook 650 15.6 inch ... | Notebook    | [918418e0fc](https://linux-hardware.org/?probe=918418e0fc) | Aug 29, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [108e0c7803](https://linux-hardware.org/?probe=108e0c7803) | Aug 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [bddbedffed](https://linux-hardware.org/?probe=bddbedffed) | Aug 29, 2022 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | Notebook    | [1ea46f19be](https://linux-hardware.org/?probe=1ea46f19be) | Aug 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [208be390fa](https://linux-hardware.org/?probe=208be390fa) | Aug 26, 2022 |
| HP            | 8509                        | Desktop     | [0656e40cba](https://linux-hardware.org/?probe=0656e40cba) | Aug 26, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [945109f9f8](https://linux-hardware.org/?probe=945109f9f8) | Aug 25, 2022 |
| Valve         | Jupiter                     | Notebook    | [fbef109b91](https://linux-hardware.org/?probe=fbef109b91) | Aug 24, 2022 |
| MSI           | GS73VR 6RF                  | Notebook    | [870534e620](https://linux-hardware.org/?probe=870534e620) | Aug 23, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [595bf9c8a7](https://linux-hardware.org/?probe=595bf9c8a7) | Aug 23, 2022 |
| Dell          | Latitude 5490               | Notebook    | [a37eabe03f](https://linux-hardware.org/?probe=a37eabe03f) | Aug 21, 2022 |
| Lenovo        | ThinkPad T500 2082BRG       | Notebook    | [29d7ac6ea6](https://linux-hardware.org/?probe=29d7ac6ea6) | Aug 21, 2022 |
| Lenovo        | ThinkPad T500 2082BRG       | Notebook    | [c8f76780a1](https://linux-hardware.org/?probe=c8f76780a1) | Aug 21, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [2e77015116](https://linux-hardware.org/?probe=2e77015116) | Aug 21, 2022 |
| ASRock        | N68C-S UCC                  | Desktop     | [bb19c0586c](https://linux-hardware.org/?probe=bb19c0586c) | Aug 20, 2022 |
| ASUSTek       | P5KPL-SE                    | Desktop     | [2925e63a87](https://linux-hardware.org/?probe=2925e63a87) | Aug 20, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [84ed4c9d73](https://linux-hardware.org/?probe=84ed4c9d73) | Aug 20, 2022 |
| HP            | Stream 7 Tablet             | Tablet      | [9d4dabb130](https://linux-hardware.org/?probe=9d4dabb130) | Aug 19, 2022 |
| HP            | ElitePad 1000 G2            | Notebook    | [ed06ba603c](https://linux-hardware.org/?probe=ed06ba603c) | Aug 19, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [6865f5ed0b](https://linux-hardware.org/?probe=6865f5ed0b) | Aug 19, 2022 |
| Lenovo        | ThinkPad Edge E431 62774... | Notebook    | [b7d37d0c4c](https://linux-hardware.org/?probe=b7d37d0c4c) | Aug 18, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [68697e720d](https://linux-hardware.org/?probe=68697e720d) | Aug 18, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [f89a185aa6](https://linux-hardware.org/?probe=f89a185aa6) | Aug 17, 2022 |
| Gigabyte      | B450 GAMING X               | Desktop     | [80760b8e4b](https://linux-hardware.org/?probe=80760b8e4b) | Aug 16, 2022 |
| ASUSTek       | X101CH                      | Notebook    | [174bc50211](https://linux-hardware.org/?probe=174bc50211) | Aug 14, 2022 |
| Acer          | Aspire 3100                 | Notebook    | [8ea61dbd3c](https://linux-hardware.org/?probe=8ea61dbd3c) | Aug 14, 2022 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [acf8952e47](https://linux-hardware.org/?probe=acf8952e47) | Aug 13, 2022 |
| HP            | 805B                        | Desktop     | [188fdd3a56](https://linux-hardware.org/?probe=188fdd3a56) | Aug 13, 2022 |
| Acer          | Aspire A515-56              | Notebook    | [e93f8de88b](https://linux-hardware.org/?probe=e93f8de88b) | Aug 13, 2022 |
| Acer          | Aspire A515-56              | Notebook    | [e429237c05](https://linux-hardware.org/?probe=e429237c05) | Aug 13, 2022 |
| Lenovo        | IdeaPad 330S-15AST 81F9     | Notebook    | [0f367345a0](https://linux-hardware.org/?probe=0f367345a0) | Aug 12, 2022 |
| Notebook      | NJ50GU                      | Notebook    | [59d1efda98](https://linux-hardware.org/?probe=59d1efda98) | Aug 12, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [a78c885366](https://linux-hardware.org/?probe=a78c885366) | Aug 12, 2022 |
| Lenovo        | ThinkPad E590 20NB0029MC    | Notebook    | [233b3cdd54](https://linux-hardware.org/?probe=233b3cdd54) | Aug 11, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [8b0ede5e40](https://linux-hardware.org/?probe=8b0ede5e40) | Aug 10, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [9d55b54de7](https://linux-hardware.org/?probe=9d55b54de7) | Aug 10, 2022 |
| ASRock        | 990FX Killer                | Desktop     | [cba7d360f1](https://linux-hardware.org/?probe=cba7d360f1) | Aug 10, 2022 |
| Dell          | Latitude 5421               | Notebook    | [b088f6b599](https://linux-hardware.org/?probe=b088f6b599) | Aug 10, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [ee1bdd9333](https://linux-hardware.org/?probe=ee1bdd9333) | Aug 09, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [a0243ce6f0](https://linux-hardware.org/?probe=a0243ce6f0) | Aug 09, 2022 |
| Dell          | Latitude 5531               | Notebook    | [64998a7d5a](https://linux-hardware.org/?probe=64998a7d5a) | Aug 09, 2022 |
| Gigabyte      | EP35-DS3P                   | Desktop     | [5c29aee903](https://linux-hardware.org/?probe=5c29aee903) | Aug 08, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [61e317887a](https://linux-hardware.org/?probe=61e317887a) | Aug 07, 2022 |
| Lenovo        | ThinkPad T430 2350B58       | Notebook    | [9c945add4e](https://linux-hardware.org/?probe=9c945add4e) | Aug 06, 2022 |
| Lenovo        | ThinkPad T430 2350B58       | Notebook    | [d1ab7d1d36](https://linux-hardware.org/?probe=d1ab7d1d36) | Aug 06, 2022 |
| Lenovo        | ThinkPad X270 20HN0015GE    | Notebook    | [2577ffae50](https://linux-hardware.org/?probe=2577ffae50) | Aug 06, 2022 |
| Dell          | 0VHWTR A02                  | Desktop     | [61b30cfde0](https://linux-hardware.org/?probe=61b30cfde0) | Aug 06, 2022 |
| Gigabyte      | B450 GAMING X               | Desktop     | [b875ef6dbf](https://linux-hardware.org/?probe=b875ef6dbf) | Aug 04, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [8c6442a868](https://linux-hardware.org/?probe=8c6442a868) | Aug 04, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [01430753da](https://linux-hardware.org/?probe=01430753da) | Aug 02, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [cc8b9aa8f6](https://linux-hardware.org/?probe=cc8b9aa8f6) | Aug 01, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [2dee8f9fb1](https://linux-hardware.org/?probe=2dee8f9fb1) | Jul 31, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d704ff7364](https://linux-hardware.org/?probe=d704ff7364) | Jul 30, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [82d0a7ace6](https://linux-hardware.org/?probe=82d0a7ace6) | Jul 29, 2022 |
| MSI           | G31TM-P35                   | Desktop     | [1bc8def241](https://linux-hardware.org/?probe=1bc8def241) | Jul 28, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [75477a4d7a](https://linux-hardware.org/?probe=75477a4d7a) | Jul 28, 2022 |
| HP            | 1494                        | Desktop     | [6805afe809](https://linux-hardware.org/?probe=6805afe809) | Jul 27, 2022 |
| ASUSTek       | V161GAR                     | All in one  | [55e2c27aaa](https://linux-hardware.org/?probe=55e2c27aaa) | Jul 27, 2022 |
| Dell          | G5 5590                     | Notebook    | [20f75f2334](https://linux-hardware.org/?probe=20f75f2334) | Jul 27, 2022 |
| Minix         | NEO Z83-4 V1.1              | Desktop     | [e8c6448552](https://linux-hardware.org/?probe=e8c6448552) | Jul 23, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [45e79d015c](https://linux-hardware.org/?probe=45e79d015c) | Jul 23, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [1ae28afad9](https://linux-hardware.org/?probe=1ae28afad9) | Jul 22, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [2986a26253](https://linux-hardware.org/?probe=2986a26253) | Jul 22, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [7e6502be7c](https://linux-hardware.org/?probe=7e6502be7c) | Jul 20, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [c000bcc566](https://linux-hardware.org/?probe=c000bcc566) | Jul 20, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [47c85dbefd](https://linux-hardware.org/?probe=47c85dbefd) | Jul 18, 2022 |
| Lenovo        | YB1-X91L                    | Convertible | [c6888145e7](https://linux-hardware.org/?probe=c6888145e7) | Jul 18, 2022 |
| Dell          | 0PM2CW A04                  | Server      | [8162a1a915](https://linux-hardware.org/?probe=8162a1a915) | Jul 17, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [2349372af2](https://linux-hardware.org/?probe=2349372af2) | Jul 16, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [eb5b940f17](https://linux-hardware.org/?probe=eb5b940f17) | Jul 16, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [e5fed36e22](https://linux-hardware.org/?probe=e5fed36e22) | Jul 15, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [9c06bd996b](https://linux-hardware.org/?probe=9c06bd996b) | Jul 15, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [9e71693839](https://linux-hardware.org/?probe=9e71693839) | Jul 15, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [179267a713](https://linux-hardware.org/?probe=179267a713) | Jul 15, 2022 |
| Dell          | G3 3590                     | Notebook    | [86835e6c2b](https://linux-hardware.org/?probe=86835e6c2b) | Jul 15, 2022 |
| ASUSTek       | K54LY                       | Notebook    | [9b66e8ad0e](https://linux-hardware.org/?probe=9b66e8ad0e) | Jul 14, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [004f74eaf4](https://linux-hardware.org/?probe=004f74eaf4) | Jul 13, 2022 |
| HP            | Compaq nx6310 (EY589ES#A... | Notebook    | [613395d2cf](https://linux-hardware.org/?probe=613395d2cf) | Jul 13, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [e3962f34e4](https://linux-hardware.org/?probe=e3962f34e4) | Jul 11, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [e5316b7d72](https://linux-hardware.org/?probe=e5316b7d72) | Jul 09, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [3df269fec9](https://linux-hardware.org/?probe=3df269fec9) | Jul 09, 2022 |
| Lenovo        | ThinkPad T460 20FMS2292S    | Notebook    | [cd5635c63c](https://linux-hardware.org/?probe=cd5635c63c) | Jul 08, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [90f45f2ebc](https://linux-hardware.org/?probe=90f45f2ebc) | Jul 08, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [d8f1865db2](https://linux-hardware.org/?probe=d8f1865db2) | Jul 08, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [02a8803d9a](https://linux-hardware.org/?probe=02a8803d9a) | Jul 07, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [6a78826e86](https://linux-hardware.org/?probe=6a78826e86) | Jul 07, 2022 |
| ASUSTek       | X542UQR                     | Notebook    | [04cc10b779](https://linux-hardware.org/?probe=04cc10b779) | Jul 07, 2022 |
| MSI           | X470 GAMING PRO             | Desktop     | [b94f3f8031](https://linux-hardware.org/?probe=b94f3f8031) | Jul 07, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [57fc50a4fb](https://linux-hardware.org/?probe=57fc50a4fb) | Jul 06, 2022 |
| HP            | ProBook 4530s               | Notebook    | [db207530bc](https://linux-hardware.org/?probe=db207530bc) | Jul 06, 2022 |
| HP            | Notebook                    | Notebook    | [9b87d6ee2d](https://linux-hardware.org/?probe=9b87d6ee2d) | Jul 06, 2022 |
| ASUSTek       | P5B                         | Desktop     | [149ab02b84](https://linux-hardware.org/?probe=149ab02b84) | Jul 06, 2022 |
| Dell          | Latitude 7520               | Notebook    | [531ccedcf2](https://linux-hardware.org/?probe=531ccedcf2) | Jul 04, 2022 |
| Sony          | VPCSA3M9E                   | Notebook    | [b36435a1fd](https://linux-hardware.org/?probe=b36435a1fd) | Jul 03, 2022 |
| HP            | 625                         | Notebook    | [0acc5581d4](https://linux-hardware.org/?probe=0acc5581d4) | Jul 03, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [38b91d59e7](https://linux-hardware.org/?probe=38b91d59e7) | Jul 02, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [7504f06baa](https://linux-hardware.org/?probe=7504f06baa) | Jul 02, 2022 |
| MSI           | 880GMA-E35                  | Desktop     | [8bcc34797b](https://linux-hardware.org/?probe=8bcc34797b) | Jul 02, 2022 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [eaf34443c7](https://linux-hardware.org/?probe=eaf34443c7) | Jul 01, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [d3f27ab291](https://linux-hardware.org/?probe=d3f27ab291) | Jul 01, 2022 |
| ASUSTek       | A88XM-A/USB                 | Desktop     | [01fb492b9d](https://linux-hardware.org/?probe=01fb492b9d) | Jul 01, 2022 |
| ASUSTek       | A88XM-A/USB                 | Desktop     | [b4b8457bd9](https://linux-hardware.org/?probe=b4b8457bd9) | Jul 01, 2022 |
| Lenovo        | ThinkPad T460 20FMS2292S    | Notebook    | [cf313915ab](https://linux-hardware.org/?probe=cf313915ab) | Jun 30, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [7e2ddf75e5](https://linux-hardware.org/?probe=7e2ddf75e5) | Jun 30, 2022 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [bef849e3d1](https://linux-hardware.org/?probe=bef849e3d1) | Jun 29, 2022 |
| Lenovo        | ThinkPad S5-S540 20B3001... | Notebook    | [d5be9c4fca](https://linux-hardware.org/?probe=d5be9c4fca) | Jun 29, 2022 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [7b07f30b17](https://linux-hardware.org/?probe=7b07f30b17) | Jun 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [e98c07bc79](https://linux-hardware.org/?probe=e98c07bc79) | Jun 29, 2022 |
| Gigabyte      | Z170-Gaming K3              | Desktop     | [70dc9ba605](https://linux-hardware.org/?probe=70dc9ba605) | Jun 28, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [a346ece8f5](https://linux-hardware.org/?probe=a346ece8f5) | Jun 26, 2022 |
| Gigabyte      | Z690 UD                     | Desktop     | [2c21dadeed](https://linux-hardware.org/?probe=2c21dadeed) | Jun 25, 2022 |
| ASUSTek       | H81M-R 2016-11-08           | Desktop     | [f9ac4d3e81](https://linux-hardware.org/?probe=f9ac4d3e81) | Jun 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X321... | Notebook    | [d2925f529c](https://linux-hardware.org/?probe=d2925f529c) | Jun 25, 2022 |
| Dell          | Precision 5550              | Notebook    | [0811e8c956](https://linux-hardware.org/?probe=0811e8c956) | Jun 23, 2022 |
| Lenovo        | Legion Y740-15IRHg 81UH     | Notebook    | [e0da282c48](https://linux-hardware.org/?probe=e0da282c48) | Jun 23, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [cf76d2d9a4](https://linux-hardware.org/?probe=cf76d2d9a4) | Jun 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [86c0fc94e6](https://linux-hardware.org/?probe=86c0fc94e6) | Jun 23, 2022 |
| Dell          | Precision 5550              | Notebook    | [0ae65f654e](https://linux-hardware.org/?probe=0ae65f654e) | Jun 23, 2022 |
| Gigabyte      | B660M GAMING DDR4           | Desktop     | [80ecbe8684](https://linux-hardware.org/?probe=80ecbe8684) | Jun 21, 2022 |
| Lenovo        | Legion S7 15IMH5 82BC       | Notebook    | [6ed235813a](https://linux-hardware.org/?probe=6ed235813a) | Jun 19, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [27fd147a80](https://linux-hardware.org/?probe=27fd147a80) | Jun 19, 2022 |
| Lenovo        | Legion S7 15IMH5 82BC       | Notebook    | [af51b1d9da](https://linux-hardware.org/?probe=af51b1d9da) | Jun 19, 2022 |
| Dell          | Latitude E5470              | Notebook    | [e18ba2b5d7](https://linux-hardware.org/?probe=e18ba2b5d7) | Jun 18, 2022 |
| HP            | Compaq nc6120 (PN936AV)     | Notebook    | [c1ecdd7b5a](https://linux-hardware.org/?probe=c1ecdd7b5a) | Jun 17, 2022 |
| HP            | 8711                        | Mini pc     | [6ceafddb10](https://linux-hardware.org/?probe=6ceafddb10) | Jun 13, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [bbba4fae4b](https://linux-hardware.org/?probe=bbba4fae4b) | Jun 12, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [4a8b021e76](https://linux-hardware.org/?probe=4a8b021e76) | Jun 11, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [8b02f3e420](https://linux-hardware.org/?probe=8b02f3e420) | Jun 10, 2022 |
| Lenovo        | ThinkPad X200 7459V2R       | Notebook    | [565722f81e](https://linux-hardware.org/?probe=565722f81e) | Jun 09, 2022 |
| Lenovo        | ThinkPad X200 7459V2R       | Notebook    | [c36b6d8e2c](https://linux-hardware.org/?probe=c36b6d8e2c) | Jun 09, 2022 |
| Lenovo        | ThinkPad T460s 20FA003JM... | Notebook    | [417d162cab](https://linux-hardware.org/?probe=417d162cab) | Jun 09, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [4abfa2a1d0](https://linux-hardware.org/?probe=4abfa2a1d0) | Jun 08, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [81335c6978](https://linux-hardware.org/?probe=81335c6978) | Jun 08, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [62d39f4677](https://linux-hardware.org/?probe=62d39f4677) | Jun 08, 2022 |
| ASUSTek       | K54LY                       | Notebook    | [39ad69783e](https://linux-hardware.org/?probe=39ad69783e) | Jun 08, 2022 |
| ASUSTek       | M4A78 PRO                   | Desktop     | [805f88e697](https://linux-hardware.org/?probe=805f88e697) | Jun 08, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [c6975f2914](https://linux-hardware.org/?probe=c6975f2914) | Jun 07, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [0732a60437](https://linux-hardware.org/?probe=0732a60437) | Jun 06, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [77b282aaaa](https://linux-hardware.org/?probe=77b282aaaa) | Jun 05, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [b320ea6050](https://linux-hardware.org/?probe=b320ea6050) | Jun 05, 2022 |
| MSI           | GP72 7QF                    | Notebook    | [ad0e85dbf9](https://linux-hardware.org/?probe=ad0e85dbf9) | Jun 05, 2022 |
| MSI           | B85M-G43                    | Desktop     | [097b308b60](https://linux-hardware.org/?probe=097b308b60) | Jun 04, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [250825e17e](https://linux-hardware.org/?probe=250825e17e) | Jun 03, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [ac88b5f927](https://linux-hardware.org/?probe=ac88b5f927) | Jun 03, 2022 |
| ASUSTek       | P5E-VM DO                   | Desktop     | [935c03cd63](https://linux-hardware.org/?probe=935c03cd63) | Jun 03, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [010b492184](https://linux-hardware.org/?probe=010b492184) | May 31, 2022 |
| Lenovo        | ThinkCentre M57 00P4496     | Desktop     | [07ba75838a](https://linux-hardware.org/?probe=07ba75838a) | May 31, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [201add5732](https://linux-hardware.org/?probe=201add5732) | May 29, 2022 |
| ASUSTek       | M4A78 PRO                   | Desktop     | [276f8565dc](https://linux-hardware.org/?probe=276f8565dc) | May 29, 2022 |
| HP            | Pavilion dv6                | Notebook    | [3623a980f8](https://linux-hardware.org/?probe=3623a980f8) | May 28, 2022 |
| ASUSTek       | TUF X299 MARK 2             | Desktop     | [8409764263](https://linux-hardware.org/?probe=8409764263) | May 27, 2022 |
| HP            | EliteBook 8760w             | Notebook    | [b4066f49b0](https://linux-hardware.org/?probe=b4066f49b0) | May 25, 2022 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [0d439f9812](https://linux-hardware.org/?probe=0d439f9812) | May 25, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [3905de150e](https://linux-hardware.org/?probe=3905de150e) | May 24, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [9f202f07cd](https://linux-hardware.org/?probe=9f202f07cd) | May 24, 2022 |
| SIEMENS       | A5E02122237 ES010           | Desktop     | [3d7173e7a3](https://linux-hardware.org/?probe=3d7173e7a3) | May 24, 2022 |
| Lenovo        | ThinkPad T420 42362L0       | Notebook    | [3aa17b879d](https://linux-hardware.org/?probe=3aa17b879d) | May 22, 2022 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [e7c21e067a](https://linux-hardware.org/?probe=e7c21e067a) | May 22, 2022 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [8ed772fb1d](https://linux-hardware.org/?probe=8ed772fb1d) | May 22, 2022 |
| Toshiba       | Satellite L10W-C            | Notebook    | [a66d178a46](https://linux-hardware.org/?probe=a66d178a46) | May 21, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [12407852be](https://linux-hardware.org/?probe=12407852be) | May 21, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [5f03a4b52d](https://linux-hardware.org/?probe=5f03a4b52d) | May 21, 2022 |
| Acer          | Z2621G                      | All in one  | [139c780029](https://linux-hardware.org/?probe=139c780029) | May 20, 2022 |
| HP            | Compaq nc6320 (RH374EA#A... | Notebook    | [baed2325d7](https://linux-hardware.org/?probe=baed2325d7) | May 20, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [2320338e52](https://linux-hardware.org/?probe=2320338e52) | May 19, 2022 |
| Acer          | Swift SF314-52              | Notebook    | [4c199417ea](https://linux-hardware.org/?probe=4c199417ea) | May 19, 2022 |
| MSI           | B85M-G43                    | Desktop     | [ef33bf347c](https://linux-hardware.org/?probe=ef33bf347c) | May 18, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [d39e962536](https://linux-hardware.org/?probe=d39e962536) | May 18, 2022 |
| ASUSTek       | M5A88-V EVO                 | Desktop     | [ab5a307891](https://linux-hardware.org/?probe=ab5a307891) | May 18, 2022 |
| Acer          | Aspire 3100                 | Notebook    | [47e42883f4](https://linux-hardware.org/?probe=47e42883f4) | May 18, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [77c7c34b9e](https://linux-hardware.org/?probe=77c7c34b9e) | May 18, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [6f48a71a87](https://linux-hardware.org/?probe=6f48a71a87) | May 17, 2022 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | Notebook    | [a49d97c9e6](https://linux-hardware.org/?probe=a49d97c9e6) | May 17, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [798bcbfce3](https://linux-hardware.org/?probe=798bcbfce3) | May 17, 2022 |
| Acer          | Swift SF314-52              | Notebook    | [a532101bbf](https://linux-hardware.org/?probe=a532101bbf) | May 17, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [95daa19596](https://linux-hardware.org/?probe=95daa19596) | May 17, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [a96c7163a5](https://linux-hardware.org/?probe=a96c7163a5) | May 17, 2022 |
| Dell          | Vostro 5568                 | Notebook    | [c7075dab69](https://linux-hardware.org/?probe=c7075dab69) | May 16, 2022 |
| HP            | 22F8                        | Desktop     | [70f6561c5c](https://linux-hardware.org/?probe=70f6561c5c) | May 16, 2022 |
| ASUSTek       | X101CH                      | Notebook    | [544536b2d8](https://linux-hardware.org/?probe=544536b2d8) | May 16, 2022 |
| ASUSTek       | X101CH                      | Notebook    | [fbcf200ed5](https://linux-hardware.org/?probe=fbcf200ed5) | May 16, 2022 |
| Clientron     | Sunshine Valley             | Desktop     | [e8915a5023](https://linux-hardware.org/?probe=e8915a5023) | May 15, 2022 |
| ASUSTek       | X555LB                      | Notebook    | [2c2e8fcf67](https://linux-hardware.org/?probe=2c2e8fcf67) | May 15, 2022 |
| Clientron     | Sunshine Valley             | Desktop     | [5f148de534](https://linux-hardware.org/?probe=5f148de534) | May 15, 2022 |
| MSI           | AM1I                        | Desktop     | [f22b398676](https://linux-hardware.org/?probe=f22b398676) | May 15, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [0ec606b729](https://linux-hardware.org/?probe=0ec606b729) | May 14, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [6fdf1cd28c](https://linux-hardware.org/?probe=6fdf1cd28c) | May 14, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [85613b8729](https://linux-hardware.org/?probe=85613b8729) | May 14, 2022 |
| Pegatron      | 2AB5                        | Desktop     | [14905c8ec7](https://linux-hardware.org/?probe=14905c8ec7) | May 14, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [a3b1829dec](https://linux-hardware.org/?probe=a3b1829dec) | May 13, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [0b0ffcbfee](https://linux-hardware.org/?probe=0b0ffcbfee) | May 13, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [b83f4f894e](https://linux-hardware.org/?probe=b83f4f894e) | May 13, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [ea75711bf8](https://linux-hardware.org/?probe=ea75711bf8) | May 12, 2022 |
| Chuwi         | MiniBook X                  | Notebook    | [541609a32e](https://linux-hardware.org/?probe=541609a32e) | May 12, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [52fa4973d5](https://linux-hardware.org/?probe=52fa4973d5) | May 10, 2022 |
| Lenovo        | ThinkPad T495s 20QJ0012U... | Notebook    | [2add3d77c6](https://linux-hardware.org/?probe=2add3d77c6) | May 09, 2022 |
| HP            | 255 G6 Notebook PC          | Notebook    | [a70f694f0b](https://linux-hardware.org/?probe=a70f694f0b) | May 09, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [badd8c8562](https://linux-hardware.org/?probe=badd8c8562) | May 09, 2022 |
| SIEMENS       | A5E02122237 ES010           | Desktop     | [cc728f6c38](https://linux-hardware.org/?probe=cc728f6c38) | May 09, 2022 |
| Clientron     | Sunshine Valley             | Desktop     | [d2deff798c](https://linux-hardware.org/?probe=d2deff798c) | May 08, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [a3e95474a0](https://linux-hardware.org/?probe=a3e95474a0) | May 08, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [1983ed1d48](https://linux-hardware.org/?probe=1983ed1d48) | May 07, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [2853128cd0](https://linux-hardware.org/?probe=2853128cd0) | May 05, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [5f51fd4cf8](https://linux-hardware.org/?probe=5f51fd4cf8) | May 05, 2022 |
| HP            | 255 G6 Notebook PC          | Notebook    | [73714bdb43](https://linux-hardware.org/?probe=73714bdb43) | May 05, 2022 |
| Clientron     | Sunshine Valley             | Desktop     | [97a95fa1af](https://linux-hardware.org/?probe=97a95fa1af) | May 05, 2022 |
| MSI           | B85M-G43                    | Desktop     | [f5deeb2d19](https://linux-hardware.org/?probe=f5deeb2d19) | May 04, 2022 |
| Dell          | 0P301D A02                  | Desktop     | [ab9edfbc39](https://linux-hardware.org/?probe=ab9edfbc39) | May 03, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [f20f31b107](https://linux-hardware.org/?probe=f20f31b107) | May 03, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [73a563257a](https://linux-hardware.org/?probe=73a563257a) | May 03, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | Notebook    | [dcff76e99c](https://linux-hardware.org/?probe=dcff76e99c) | May 02, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [35c8958673](https://linux-hardware.org/?probe=35c8958673) | May 01, 2022 |
| Lenovo        | Yoga Duet 7 13IML05 82AS    | Tablet      | [09944d29bf](https://linux-hardware.org/?probe=09944d29bf) | May 01, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [ff568c874c](https://linux-hardware.org/?probe=ff568c874c) | Apr 30, 2022 |
| Dell          | Latitude 3330               | Notebook    | [1843c62895](https://linux-hardware.org/?probe=1843c62895) | Apr 30, 2022 |
| Gigabyte      | M68MT-S2                    | Desktop     | [f3b89e43d4](https://linux-hardware.org/?probe=f3b89e43d4) | Apr 30, 2022 |
| Gigabyte      | H310N x.x                   | Desktop     | [d0daa33c07](https://linux-hardware.org/?probe=d0daa33c07) | Apr 30, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [f4a6777382](https://linux-hardware.org/?probe=f4a6777382) | Apr 30, 2022 |
| Gigabyte      | H170-HD3 DDR3-CF            | Desktop     | [b23594dfa0](https://linux-hardware.org/?probe=b23594dfa0) | Apr 29, 2022 |
| Lenovo        | ThinkPad S3-S440 20AY00B... | Notebook    | [1ecbcb6b83](https://linux-hardware.org/?probe=1ecbcb6b83) | Apr 29, 2022 |
| Lenovo        | ThinkPad S3-S440 20AY00B... | Notebook    | [474e572043](https://linux-hardware.org/?probe=474e572043) | Apr 29, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [8f165f54aa](https://linux-hardware.org/?probe=8f165f54aa) | Apr 29, 2022 |
| Lenovo        | ThinkPad T420 4180A21       | Notebook    | [6b5a6e89a2](https://linux-hardware.org/?probe=6b5a6e89a2) | Apr 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [ffdfb3a578](https://linux-hardware.org/?probe=ffdfb3a578) | Apr 29, 2022 |
| Cisco Syst... | 0T38HV A02                  | Server      | [abc0c5402d](https://linux-hardware.org/?probe=abc0c5402d) | Apr 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [55c0ec3653](https://linux-hardware.org/?probe=55c0ec3653) | Apr 29, 2022 |
| Cisco Syst... | 0T38HV A02                  | Server      | [9389a4bd1e](https://linux-hardware.org/?probe=9389a4bd1e) | Apr 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [a3ddc714b0](https://linux-hardware.org/?probe=a3ddc714b0) | Apr 28, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [aee7cca97f](https://linux-hardware.org/?probe=aee7cca97f) | Apr 28, 2022 |
| Intel         | NUC6CAYB J23203-409         | Mini pc     | [3b927afe90](https://linux-hardware.org/?probe=3b927afe90) | Apr 28, 2022 |
| Intel         | NUC6CAYB J23203-409         | Mini pc     | [97c0bfb76c](https://linux-hardware.org/?probe=97c0bfb76c) | Apr 28, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [ef86b0396a](https://linux-hardware.org/?probe=ef86b0396a) | Apr 27, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [4185312ca8](https://linux-hardware.org/?probe=4185312ca8) | Apr 27, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [88248eb2e6](https://linux-hardware.org/?probe=88248eb2e6) | Apr 27, 2022 |
| HP            | 22F8                        | Desktop     | [eb4d49a17b](https://linux-hardware.org/?probe=eb4d49a17b) | Apr 27, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [313e7bcf23](https://linux-hardware.org/?probe=313e7bcf23) | Apr 27, 2022 |
| HP            | ZBook 17 G3                 | Notebook    | [133232a304](https://linux-hardware.org/?probe=133232a304) | Apr 26, 2022 |
| Dell          | Latitude 7390 2-in-1        | Notebook    | [8391ca514e](https://linux-hardware.org/?probe=8391ca514e) | Apr 23, 2022 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [ab5986371d](https://linux-hardware.org/?probe=ab5986371d) | Apr 23, 2022 |
| HP            | 22F8                        | Desktop     | [67dc13d1ad](https://linux-hardware.org/?probe=67dc13d1ad) | Apr 23, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [4e8b5f940a](https://linux-hardware.org/?probe=4e8b5f940a) | Apr 23, 2022 |
| Lenovo        | ThinkPad E15 20RD001EMC     | Notebook    | [d98ca42427](https://linux-hardware.org/?probe=d98ca42427) | Apr 20, 2022 |
| Dell          | Latitude 5480               | Notebook    | [811930e65e](https://linux-hardware.org/?probe=811930e65e) | Apr 20, 2022 |
| ASRock        | B450M Pro4-F                | Desktop     | [68d9ef89c7](https://linux-hardware.org/?probe=68d9ef89c7) | Apr 19, 2022 |
| MSI           | B150 PC MATE                | Desktop     | [34c7fe45bc](https://linux-hardware.org/?probe=34c7fe45bc) | Apr 19, 2022 |
| Lenovo        | B50-80 80EW                 | Notebook    | [2d1471986b](https://linux-hardware.org/?probe=2d1471986b) | Apr 19, 2022 |
| Intel         | X79G V2.x                   | Desktop     | [497807c732](https://linux-hardware.org/?probe=497807c732) | Apr 18, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [874e39c8ef](https://linux-hardware.org/?probe=874e39c8ef) | Apr 18, 2022 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [a2b841241d](https://linux-hardware.org/?probe=a2b841241d) | Apr 17, 2022 |
| ASRockRack    | X470D4U                     | Desktop     | [1b9b990e65](https://linux-hardware.org/?probe=1b9b990e65) | Apr 17, 2022 |
| Acer          | Aspire V3-112P              | Notebook    | [c27219930e](https://linux-hardware.org/?probe=c27219930e) | Apr 17, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Czechia/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 247       | 11.18%  |
| Ubuntu 18.04                 | 151       | 6.84%   |
| OpenMandriva 4.2             | 117       | 5.3%    |
| Ubuntu 22.04                 | 113       | 5.12%   |
| OpenMandriva 4.3             | 70        | 3.17%   |
| OpenMandriva 4.50            | 66        | 2.99%   |
| Debian 11                    | 42        | 1.9%    |
| Ubuntu 21.10                 | 38        | 1.72%   |
| Ubuntu 20.10                 | 35        | 1.58%   |
| Fedora 34                    | 35        | 1.58%   |
| Arch Rolling                 | 33        | 1.49%   |
| Zorin 16                     | 31        | 1.4%    |
| OpenMandriva 23.01           | 29        | 1.31%   |
| Linux Mint 21.1              | 29        | 1.31%   |
| Ubuntu 19.10                 | 28        | 1.27%   |
| Linux Mint 20.1              | 28        | 1.27%   |
| Ubuntu 21.04                 | 27        | 1.22%   |
| Arch                         | 27        | 1.22%   |
| Linux Mint 20                | 26        | 1.18%   |
| Fedora 35                    | 26        | 1.18%   |
| OpenMandriva 23.03           | 25        | 1.13%   |
| Linux Mint 20.2              | 25        | 1.13%   |
| Fedora 32                    | 25        | 1.13%   |
| Ubuntu 19.04                 | 24        | 1.09%   |
| Linux Mint 20.3              | 24        | 1.09%   |
| Zorin 15                     | 23        | 1.04%   |
| Linux Mint 19.3              | 23        | 1.04%   |
| Fedora 33                    | 23        | 1.04%   |
| Ubuntu 22.10                 | 22        | 1%      |
| openSUSE Tumbleweed-XXXXXXXX | 21        | 0.95%   |
| Fedora 38                    | 21        | 0.95%   |
| Fedora 37                    | 21        | 0.95%   |
| Fedora 36                    | 20        | 0.91%   |
| Pop!_OS 22.04                | 19        | 0.86%   |
| Linux Mint 21                | 19        | 0.86%   |
| Manjaro                      | 18        | 0.81%   |
| Fedora 31                    | 18        | 0.81%   |
| Kubuntu 20.04                | 17        | 0.77%   |
| Xubuntu 20.04                | 16        | 0.72%   |
| Xubuntu 18.04                | 15        | 0.68%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 670       | 32.35%  |
| OpenMandriva  | 307       | 14.82%  |
| Linux Mint    | 190       | 9.17%   |
| Fedora        | 184       | 8.88%   |
| Debian        | 74        | 3.57%   |
| Arch          | 60        | 2.9%    |
| Zorin         | 58        | 2.8%    |
| Manjaro       | 54        | 2.61%   |
| Pop!_OS       | 48        | 2.32%   |
| Xubuntu       | 46        | 2.22%   |
| Kubuntu       | 40        | 1.93%   |
| ROSA          | 39        | 1.88%   |
| Gentoo        | 35        | 1.69%   |
| openSUSE      | 27        | 1.3%    |
| KDE neon      | 21        | 1.01%   |
| Lubuntu       | 20        | 0.97%   |
| Kali          | 17        | 0.82%   |
| Ubuntu MATE   | 14        | 0.68%   |
| Endless       | 14        | 0.68%   |
| Elementary    | 14        | 0.68%   |
| ArcoLinux     | 14        | 0.68%   |
| RHEL          | 13        | 0.63%   |
| Ubuntu Unity  | 10        | 0.48%   |
| CentOS        | 9         | 0.43%   |
| EndeavourOS   | 7         | 0.34%   |
| Void Linux    | 6         | 0.29%   |
| Parrot        | 6         | 0.29%   |
| SteamOS       | 5         | 0.24%   |
| LMDE          | 5         | 0.24%   |
| ACI           | 5         | 0.24%   |
| Rocky Linux   | 4         | 0.19%   |
| MX            | 4         | 0.19%   |
| BlackPanther  | 4         | 0.19%   |
| Nobara        | 3         | 0.14%   |
| NixOS         | 3         | 0.14%   |
| Neptune OS    | 3         | 0.14%   |
| LinuxFX       | 3         | 0.14%   |
| Ubuntu Budgie | 2         | 0.1%    |
| GNOME OS      | 2         | 0.1%    |
| Garuda Linux  | 2         | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 115       | 4.74%   |
| 5.16.7-desktop-1omv4003  | 68        | 2.81%   |
| 5.14.7-desktop-1omv4050  | 55        | 2.27%   |
| 5.4.0-42-generic         | 34        | 1.4%    |
| 6.2.6-desktop-1omv2390   | 26        | 1.07%   |
| 6.1.1-desktop-1omv2290   | 26        | 1.07%   |
| 5.4.0-58-generic         | 23        | 0.95%   |
| 5.4.0-52-generic         | 22        | 0.91%   |
| 5.15.0-56-generic        | 22        | 0.91%   |
| 5.15.0-46-generic        | 21        | 0.87%   |
| 5.4.0-26-generic         | 20        | 0.83%   |
| 5.15.0-58-generic        | 17        | 0.7%    |
| 5.15.0-52-generic        | 16        | 0.66%   |
| 5.11.0-27-generic        | 16        | 0.66%   |
| 5.3.0-40-generic         | 15        | 0.62%   |
| 5.0.0-37-generic         | 15        | 0.62%   |
| 5.13.0-30-generic        | 14        | 0.58%   |
| 5.4.0-48-generic         | 12        | 0.5%    |
| 5.4.0-40-generic         | 12        | 0.5%    |
| 5.3.0-28-generic         | 12        | 0.5%    |
| 5.15.0-48-generic        | 12        | 0.5%    |
| 5.4.0-65-generic         | 11        | 0.45%   |
| 5.15.0-41-generic        | 11        | 0.45%   |
| 5.4.0-29-generic         | 10        | 0.41%   |
| 5.11.0-37-generic        | 10        | 0.41%   |
| 5.8.0-53-generic         | 9         | 0.37%   |
| 5.4.0-91-generic         | 9         | 0.37%   |
| 5.4.0-37-generic         | 9         | 0.37%   |
| 5.19.0-32-generic        | 9         | 0.37%   |
| 5.15.0-43-generic        | 9         | 0.37%   |
| 5.10.0-8-amd64           | 9         | 0.37%   |
| 4.15.0-43-generic        | 9         | 0.37%   |
| 5.8.0-59-generic         | 8         | 0.33%   |
| 5.8.0-50-generic         | 8         | 0.33%   |
| 5.4.0-72-generic         | 8         | 0.33%   |
| 5.4.0-56-generic         | 8         | 0.33%   |
| 5.4.0-33-generic         | 8         | 0.33%   |
| 5.3.0-42-generic         | 8         | 0.33%   |
| 5.15.0-78-generic        | 8         | 0.33%   |
| 5.15.0-53-generic        | 8         | 0.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 317       | 13.95%  |
| 5.15.0  | 183       | 8.05%   |
| 5.10.14 | 115       | 5.06%   |
| 4.15.0  | 112       | 4.93%   |
| 5.8.0   | 101       | 4.44%   |
| 5.11.0  | 96        | 4.22%   |
| 5.3.0   | 92        | 4.05%   |
| 5.13.0  | 92        | 4.05%   |
| 5.19.0  | 71        | 3.12%   |
| 5.0.0   | 71        | 3.12%   |
| 5.16.7  | 69        | 3.04%   |
| 4.18.0  | 57        | 2.51%   |
| 5.14.7  | 56        | 2.46%   |
| 5.10.0  | 44        | 1.94%   |
| 6.1.1   | 32        | 1.41%   |
| 6.2.6   | 31        | 1.36%   |
| 6.1.0   | 18        | 0.79%   |
| 4.19.0  | 17        | 0.75%   |
| 6.2.0   | 14        | 0.62%   |
| 6.0.0   | 12        | 0.53%   |
| 3.10.0  | 11        | 0.48%   |
| 6.3.5   | 9         | 0.4%    |
| 4.9.20  | 9         | 0.4%    |
| 5.16.11 | 8         | 0.35%   |
| 5.11.12 | 8         | 0.35%   |
| 5.17.0  | 7         | 0.31%   |
| 5.15.12 | 7         | 0.31%   |
| 6.2.15  | 6         | 0.26%   |
| 6.0.12  | 6         | 0.26%   |
| 5.9.16  | 6         | 0.26%   |
| 5.9.0   | 6         | 0.26%   |
| 5.18.12 | 6         | 0.26%   |
| 5.14.0  | 6         | 0.26%   |
| 5.12.4  | 6         | 0.26%   |
| 5.10.74 | 6         | 0.26%   |
| 4.4.0   | 6         | 0.26%   |
| 4.13.0  | 6         | 0.26%   |
| 6.4.7   | 5         | 0.22%   |
| 6.3.8   | 5         | 0.22%   |
| 6.3.1   | 5         | 0.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.4      | 341       | 15.12%  |
| 5.15     | 234       | 10.38%  |
| 5.10     | 202       | 8.96%   |
| 5.8      | 134       | 5.94%   |
| 5.11     | 130       | 5.76%   |
| 4.15     | 114       | 5.06%   |
| 5.13     | 110       | 4.88%   |
| 5.3      | 103       | 4.57%   |
| 5.16     | 100       | 4.43%   |
| 5.19     | 95        | 4.21%   |
| 5.14     | 82        | 3.64%   |
| 6.1      | 81        | 3.59%   |
| 5.0      | 77        | 3.41%   |
| 6.2      | 73        | 3.24%   |
| 4.18     | 60        | 2.66%   |
| 6.0      | 38        | 1.69%   |
| 5.17     | 34        | 1.51%   |
| 6.3      | 28        | 1.24%   |
| 5.9      | 25        | 1.11%   |
| 5.18     | 24        | 1.06%   |
| 5.6      | 23        | 1.02%   |
| 4.19     | 22        | 0.98%   |
| 5.12     | 21        | 0.93%   |
| 4.9      | 20        | 0.89%   |
| 6.4      | 15        | 0.67%   |
| 5.7      | 14        | 0.62%   |
| 3.10     | 12        | 0.53%   |
| 5.5      | 11        | 0.49%   |
| 4.4      | 6         | 0.27%   |
| 4.13     | 6         | 0.27%   |
| 5.1      | 4         | 0.18%   |
| 5.2      | 3         | 0.13%   |
| 4.17     | 3         | 0.13%   |
| 4.14     | 3         | 0.13%   |
| 4.1      | 2         | 0.09%   |
| 5.10.164 | 1         | 0.04%   |
| 4.8      | 1         | 0.04%   |
| 4.20     | 1         | 0.04%   |
| 4.10     | 1         | 0.04%   |
| 2.6      | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1961      | 96.22%  |
| i686    | 63        | 3.09%   |
| aarch64 | 12        | 0.59%   |
| armv8l  | 1         | 0.05%   |
| armv7l  | 1         | 0.05%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| GNOME             | 829       | 39.36%  |
| KDE5              | 477       | 22.65%  |
| Unknown           | 270       | 12.82%  |
| XFCE              | 158       | 7.5%    |
| X-Cinnamon        | 118       | 5.6%    |
| MATE              | 52        | 2.47%   |
| KDE               | 47        | 2.23%   |
| Cinnamon          | 34        | 1.61%   |
| LXQt              | 24        | 1.14%   |
| Pantheon          | 14        | 0.66%   |
| KDE4              | 13        | 0.62%   |
| GNOME Flashback   | 12        | 0.57%   |
| Unity             | 11        | 0.52%   |
| LXDE              | 10        | 0.47%   |
| i3                | 6         | 0.28%   |
| openbox           | 5         | 0.24%   |
| Budgie            | 4         | 0.19%   |
| awesome           | 4         | 0.19%   |
| sway              | 3         | 0.14%   |
| qtile             | 3         | 0.14%   |
| Hyprland          | 2         | 0.09%   |
| Yaru:ubuntu:GNOME | 1         | 0.05%   |
| XSession          | 1         | 0.05%   |
| xinitrc           | 1         | 0.05%   |
| xinit-compat      | 1         | 0.05%   |
| GNUstep           | 1         | 0.05%   |
| GNOME Classic     | 1         | 0.05%   |
| Enlightenment     | 1         | 0.05%   |
| DWM               | 1         | 0.05%   |
| custom            | 1         | 0.05%   |
| Core              | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1570      | 75.05%  |
| Wayland | 340       | 16.25%  |
| Unknown | 143       | 6.84%   |
| Tty     | 39        | 1.86%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 943       | 44.69%  |
| SDDM    | 461       | 21.85%  |
| GDM     | 220       | 10.43%  |
| GDM3    | 209       | 9.91%   |
| LightDM | 180       | 8.53%   |
| TDM     | 71        | 3.36%   |
| KDM     | 12        | 0.57%   |
| XDM     | 5         | 0.24%   |
| SLiM    | 4         | 0.19%   |
| LXDM    | 3         | 0.14%   |
| Ly      | 1         | 0.05%   |
| GREETD  | 1         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| cs_CZ   | 1101      | 52.93%  |
| en_US   | 610       | 29.33%  |
| Unknown | 227       | 10.91%  |
| en_GB   | 46        | 2.21%   |
| C       | 34        | 1.63%   |
| ru_RU   | 20        | 0.96%   |
| sk_SK   | 10        | 0.48%   |
| POSIX   | 5         | 0.24%   |
| pl_PL   | 5         | 0.24%   |
| it_IT   | 3         | 0.14%   |
| fr_FR   | 3         | 0.14%   |
| de_DE   | 3         | 0.14%   |
| en_CA   | 2         | 0.1%    |
| uk_UA   | 1         | 0.05%   |
| ro_RO   | 1         | 0.05%   |
| pt_PT   | 1         | 0.05%   |
| fi_FI   | 1         | 0.05%   |
| es_ES   | 1         | 0.05%   |
| en_NG   | 1         | 0.05%   |
| en_AU   | 1         | 0.05%   |
| en_150  | 1         | 0.05%   |
| el_GR   | 1         | 0.05%   |
| C.UTF8  | 1         | 0.05%   |
| bg_BG   | 1         | 0.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 1099      | 52.74%  |
| EFI  | 985       | 47.26%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 1409      | 67.38%  |
| Overlay  | 314       | 15.02%  |
| Btrfs    | 196       | 9.37%   |
| Unknown  | 64        | 3.06%   |
| Xfs      | 52        | 2.49%   |
| Tmpfs    | 24        | 1.15%   |
| Zfs      | 16        | 0.77%   |
| Ext2     | 5         | 0.24%   |
| Ext3     | 4         | 0.19%   |
| F2fs     | 3         | 0.14%   |
| Reiserfs | 2         | 0.1%    |
| Aufs     | 2         | 0.1%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 973       | 46.82%  |
| GPT     | 764       | 36.77%  |
| MBR     | 341       | 16.41%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1792      | 86.86%  |
| Yes       | 271       | 13.14%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1376      | 66.19%  |
| Yes       | 703       | 33.81%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 444       | 21.8%   |
| Lenovo                  | 376       | 18.46%  |
| Hewlett-Packard         | 307       | 15.07%  |
| Dell                    | 216       | 10.6%   |
| Gigabyte Technology     | 138       | 6.77%   |
| Acer                    | 135       | 6.63%   |
| MSI                     | 126       | 6.19%   |
| ASRock                  | 51        | 2.5%    |
| Intel                   | 29        | 1.42%   |
| UMAX                    | 22        | 1.08%   |
| Toshiba                 | 17        | 0.83%   |
| Fujitsu                 | 16        | 0.79%   |
| Sony                    | 14        | 0.69%   |
| Raspberry Pi Foundation | 12        | 0.59%   |
| Unknown                 | 10        | 0.49%   |
| Apple                   | 9         | 0.44%   |
| Fujitsu Siemens         | 8         | 0.39%   |
| Pegatron                | 7         | 0.34%   |
| HUAWEI                  | 7         | 0.34%   |
| Supermicro              | 6         | 0.29%   |
| Google                  | 6         | 0.29%   |
| AMI                     | 6         | 0.29%   |
| Valve                   | 5         | 0.25%   |
| TUXEDO                  | 4         | 0.2%    |
| Timi                    | 4         | 0.2%    |
| Packard Bell            | 4         | 0.2%    |
| Microsoft               | 4         | 0.2%    |
| ZOTAC                   | 3         | 0.15%   |
| Notebook                | 3         | 0.15%   |
| Foxconn                 | 3         | 0.15%   |
| Insyde                  | 2         | 0.1%    |
| IBM                     | 2         | 0.1%    |
| Dynabook                | 2         | 0.1%    |
| Clientron               | 2         | 0.1%    |
| Chuwi                   | 2         | 0.1%    |
| Biostar                 | 2         | 0.1%    |
| ASRockRack              | 2         | 0.1%    |
| Alienware               | 2         | 0.1%    |
| Wortmann AG             | 1         | 0.05%   |
| Standard                | 1         | 0.05%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| ASUS UX31E                            | 126       | 6.19%   |
| ASUS All Series                       | 13        | 0.64%   |
| Unknown                               | 13        | 0.64%   |
| MSI MS-7C91                           | 10        | 0.49%   |
| MSI MS-7C02                           | 7         | 0.34%   |
| MSI MS-7693                           | 7         | 0.34%   |
| HP ProBook 455 G7                     | 7         | 0.34%   |
| MSI MS-7A34                           | 6         | 0.29%   |
| Valve Jupiter                         | 5         | 0.25%   |
| RPi Raspberry Pi                      | 5         | 0.25%   |
| Lenovo ThinkPad E14 20RA001LMC        | 5         | 0.25%   |
| HP ProLiant DL380e Gen8               | 5         | 0.25%   |
| HP ProBook 4540s                      | 5         | 0.25%   |
| HP ProBook 4530s                      | 5         | 0.25%   |
| HP ProBook 450 G5                     | 5         | 0.25%   |
| HP EliteBook 840 G3                   | 5         | 0.25%   |
| Dell Latitude E6420                   | 5         | 0.25%   |
| Dell Latitude E6400                   | 5         | 0.25%   |
| Dell Latitude 5401                    | 5         | 0.25%   |
| ASUS P5G41T-M LX                      | 5         | 0.25%   |
| MSI MS-7592                           | 4         | 0.2%    |
| Lenovo IdeaPad S145-15AST 81N3        | 4         | 0.2%    |
| HP ProDesk 405 G6 Desktop Mini PC     | 4         | 0.2%    |
| HP Pavilion dv7                       | 4         | 0.2%    |
| HP Notebook                           | 4         | 0.2%    |
| HP EliteBook 845 G8 Notebook PC       | 4         | 0.2%    |
| HP EliteBook 840 G6                   | 4         | 0.2%    |
| HP Compaq 8200 Elite SFF PC           | 4         | 0.2%    |
| HP 250 G6 Notebook PC                 | 4         | 0.2%    |
| Dell XPS 15 7590                      | 4         | 0.2%    |
| Dell Precision M6500                  | 4         | 0.2%    |
| Acer Extensa 5620                     | 4         | 0.2%    |
| MSI MS-7817                           | 3         | 0.15%   |
| Lenovo Z50-75 80EC                    | 3         | 0.15%   |
| Lenovo ThinkPad T14 Gen 1 20UES2WA00  | 3         | 0.15%   |
| Lenovo IdeaPad S130-11IGM 81J1        | 3         | 0.15%   |
| Lenovo IdeaPad L340-17IRH Gaming 81LL | 3         | 0.15%   |
| Lenovo IdeaPad Duet 3 10IGL5 82AT     | 3         | 0.15%   |
| Lenovo IdeaPad 5 14ARE05 81YM         | 3         | 0.15%   |
| Lenovo IdeaPad 5 14ALC05 82LM         | 3         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 177       | 8.69%   |
| ASUS UX31E         | 126       | 6.19%   |
| Dell Latitude      | 91        | 4.47%   |
| Acer Aspire        | 78        | 3.83%   |
| Lenovo IdeaPad     | 70        | 3.44%   |
| HP ProBook         | 64        | 3.14%   |
| HP EliteBook       | 64        | 3.14%   |
| HP Compaq          | 34        | 1.67%   |
| HP Pavilion        | 31        | 1.52%   |
| ASUS ROG           | 31        | 1.52%   |
| ASUS PRIME         | 30        | 1.47%   |
| Dell Inspiron      | 26        | 1.28%   |
| Lenovo Yoga        | 25        | 1.23%   |
| Dell Precision     | 25        | 1.23%   |
| Dell OptiPlex      | 25        | 1.23%   |
| Dell XPS           | 24        | 1.18%   |
| ASUS TUF           | 20        | 0.98%   |
| Lenovo ThinkCentre | 17        | 0.83%   |
| Toshiba Satellite  | 16        | 0.79%   |
| ASUS VivoBook      | 16        | 0.79%   |
| UMAX VisionBook    | 15        | 0.74%   |
| ASUS Zenbook       | 15        | 0.74%   |
| HP Laptop          | 14        | 0.69%   |
| Acer TravelMate    | 14        | 0.69%   |
| Acer Extensa       | 14        | 0.69%   |
| Lenovo Legion      | 13        | 0.64%   |
| HP ENVY            | 13        | 0.64%   |
| ASUS All           | 13        | 0.64%   |
| Unknown            | 13        | 0.64%   |
| RPi Raspberry      | 12        | 0.59%   |
| HP ZBook           | 12        | 0.59%   |
| HP ProDesk         | 11        | 0.54%   |
| Dell Vostro        | 11        | 0.54%   |
| Acer Swift         | 11        | 0.54%   |
| MSI MS-7C91        | 10        | 0.49%   |
| Lenovo ThinkBook   | 10        | 0.49%   |
| HP 250             | 10        | 0.49%   |
| Fujitsu LIFEBOOK   | 9         | 0.44%   |
| ASUS ASUS          | 8         | 0.39%   |
| MSI MS-7C02        | 7         | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 249       | 12.22%  |
| 2020    | 202       | 9.92%   |
| 2018    | 176       | 8.64%   |
| 2019    | 170       | 8.35%   |
| 2021    | 149       | 7.31%   |
| 2012    | 135       | 6.63%   |
| 2017    | 131       | 6.43%   |
| 2014    | 118       | 5.79%   |
| 2013    | 106       | 5.2%    |
| 2015    | 101       | 4.96%   |
| 2008    | 94        | 4.61%   |
| 2016    | 82        | 4.03%   |
| 2010    | 80        | 3.93%   |
| 2009    | 68        | 3.34%   |
| 2007    | 65        | 3.19%   |
| 2022    | 51        | 2.5%    |
| 2006    | 26        | 1.28%   |
| Unknown | 14        | 0.69%   |
| 2005    | 9         | 0.44%   |
| 2023    | 6         | 0.29%   |
| 2004    | 4         | 0.2%    |
| 2000    | 1         | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1236      | 60.68%  |
| Desktop        | 649       | 31.86%  |
| Convertible    | 59        | 2.9%    |
| Mini pc        | 30        | 1.47%   |
| Tablet         | 17        | 0.83%   |
| All in one     | 16        | 0.79%   |
| Server         | 16        | 0.79%   |
| System on chip | 13        | 0.64%   |
| Phone          | 1         | 0.05%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1861      | 90.52%  |
| Enabled  | 195       | 9.48%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2031      | 99.71%  |
| Yes  | 6         | 0.29%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 519       | 24.99%  |
| 4.01-8.0        | 381       | 18.34%  |
| 8.01-16.0       | 370       | 17.81%  |
| 16.01-24.0      | 344       | 16.56%  |
| 32.01-64.0      | 213       | 10.26%  |
| 1.01-2.0        | 103       | 4.96%   |
| 64.01-256.0     | 49        | 2.36%   |
| 24.01-32.0      | 39        | 1.88%   |
| 2.01-3.0        | 37        | 1.78%   |
| 0.51-1.0        | 18        | 0.87%   |
| More than 256.0 | 2         | 0.1%    |
| 0.01-0.5        | 2         | 0.1%    |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 835       | 36.96%  |
| 2.01-3.0    | 495       | 21.91%  |
| 4.01-8.0    | 341       | 15.1%   |
| 3.01-4.0    | 260       | 11.51%  |
| 0.51-1.0    | 140       | 6.2%    |
| 8.01-16.0   | 120       | 5.31%   |
| 0.01-0.5    | 30        | 1.33%   |
| 16.01-24.0  | 22        | 0.97%   |
| 32.01-64.0  | 9         | 0.4%    |
| 24.01-32.0  | 5         | 0.22%   |
| 64.01-256.0 | 1         | 0.04%   |
| Unknown     | 1         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1369      | 65%     |
| 2      | 445       | 21.13%  |
| 3      | 139       | 6.6%    |
| 4      | 58        | 2.75%   |
| 5      | 36        | 1.71%   |
| 0      | 26        | 1.23%   |
| 6      | 17        | 0.81%   |
| 7      | 11        | 0.52%   |
| 8      | 4         | 0.19%   |
| 9      | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1345      | 65.51%  |
| Yes       | 708       | 34.49%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1766      | 86.23%  |
| No        | 282       | 13.77%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1514      | 74%     |
| No        | 532       | 26%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1165      | 56.55%  |
| No        | 895       | 43.45%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Czechia | 2037      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Prague               | 800       | 37.63%  |
| Brno                 | 174       | 8.18%   |
| Ostrava              | 61        | 2.87%   |
| Pilsen               | 46        | 2.16%   |
| Olomouc              | 31        | 1.46%   |
| Liberec              | 31        | 1.46%   |
| Pardubice            | 29        | 1.36%   |
| Hradec Králové     | 29        | 1.36%   |
| České Budějovice  | 26        | 1.22%   |
| Zlín                | 18        | 0.85%   |
| Havířov            | 18        | 0.85%   |
| Znojmo               | 16        | 0.75%   |
| Most                 | 14        | 0.66%   |
| Chomutov             | 13        | 0.61%   |
| Jihlava              | 11        | 0.52%   |
| Frýdek-Místek      | 11        | 0.52%   |
| Brdo                 | 11        | 0.52%   |
| Přerov              | 9         | 0.42%   |
| Ústí nad Labem     | 8         | 0.38%   |
| Opava                | 8         | 0.38%   |
| Mladá Boleslav      | 8         | 0.38%   |
| Litoměřice         | 8         | 0.38%   |
| Karlovy Vary         | 8         | 0.38%   |
| Uherské Hradiště  | 7         | 0.33%   |
| Třebíč            | 7         | 0.33%   |
| Teplice              | 7         | 0.33%   |
| Tábor               | 7         | 0.33%   |
| Roznov pod Radhostem | 7         | 0.33%   |
| Prelouc              | 7         | 0.33%   |
| Praha 10             | 7         | 0.33%   |
| Kladno               | 7         | 0.33%   |
| Horice               | 7         | 0.33%   |
| Česká Lípa        | 7         | 0.33%   |
| Rumburk              | 6         | 0.28%   |
| Příbram            | 6         | 0.28%   |
| Mariánské Lázně  | 6         | 0.28%   |
| Kralupy nad Vltavou  | 6         | 0.28%   |
| Ivancice             | 6         | 0.28%   |
| Český Těšín     | 6         | 0.28%   |
| As                   | 6         | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 466       | 650    | 16.44%  |
| WDC                         | 452       | 745    | 15.94%  |
| Seagate                     | 402       | 619    | 14.18%  |
| SanDisk                     | 218       | 237    | 7.69%   |
| Kingston                    | 195       | 243    | 6.88%   |
| Toshiba                     | 162       | 200    | 5.71%   |
| Unknown                     | 112       | 165    | 3.95%   |
| Hitachi                     | 84        | 97     | 2.96%   |
| SK hynix                    | 79        | 94     | 2.79%   |
| Intel                       | 75        | 92     | 2.65%   |
| A-DATA Technology           | 71        | 85     | 2.5%    |
| Crucial                     | 66        | 82     | 2.33%   |
| Micron Technology           | 52        | 69     | 1.83%   |
| HGST                        | 51        | 62     | 1.8%    |
| Patriot                     | 47        | 58     | 1.66%   |
| KIOXIA                      | 20        | 32     | 0.71%   |
| Apacer                      | 20        | 26     | 0.71%   |
| Transcend                   | 18        | 28     | 0.63%   |
| Phison                      | 15        | 27     | 0.53%   |
| Verbatim                    | 12        | 12     | 0.42%   |
| Gigabyte Technology         | 12        | 23     | 0.42%   |
| Unknown                     | 12        | 13     | 0.42%   |
| Silicon Motion              | 10        | 12     | 0.35%   |
| OCZ                         | 10        | 33     | 0.35%   |
| LITEONIT                    | 10        | 12     | 0.35%   |
| China                       | 10        | 11     | 0.35%   |
| Maxtor                      | 9         | 13     | 0.32%   |
| Fujitsu                     | 9         | 10     | 0.32%   |
| XPG                         | 7         | 14     | 0.25%   |
| LITEON                      | 7         | 8      | 0.25%   |
| GOODRAM                     | 7         | 10     | 0.25%   |
| Apple                       | 7         | 10     | 0.25%   |
| Phison Electronics          | 6         | 6      | 0.21%   |
| Kingston Technology Company | 6         | 7      | 0.21%   |
| JMicron Technology          | 6         | 7      | 0.21%   |
| UMAX                        | 5         | 5      | 0.18%   |
| Realtek Semiconductor       | 5         | 9      | 0.18%   |
| Micron/Crucial Technology   | 5         | 5      | 0.18%   |
| Corsair                     | 5         | 5      | 0.18%   |
| ASMedia                     | 5         | 7      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| SanDisk SSD U100 256GB                              | 125       | 4%      |
| Kingston SA400S37240G 240GB SSD                     | 30        | 0.96%   |
| Samsung SSD 860 EVO 500GB                           | 28        | 0.9%    |
| Samsung NVMe SSD Drive 512GB                        | 24        | 0.77%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 22        | 0.7%    |
| Kingston SA400S37120G 120GB SSD                     | 22        | 0.7%    |
| Kingston SA400S37480G 480GB SSD                     | 21        | 0.67%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 20        | 0.64%   |
| Unknown MMC Card  64GB                              | 20        | 0.64%   |
| Unknown MMC Card  32GB                              | 20        | 0.64%   |
| Samsung SSD 850 EVO 250GB                           | 19        | 0.61%   |
| Seagate ST1000LM035-1RK172 1TB                      | 18        | 0.58%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 17        | 0.54%   |
| HGST HTS721010A9E630 1TB                            | 17        | 0.54%   |
| Samsung NVMe SSD Drive 500GB                        | 16        | 0.51%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 14        | 0.45%   |
| Seagate ST1000DM010-2EP102 1TB                      | 14        | 0.45%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD                 | 13        | 0.42%   |
| Seagate ST3500418AS 500GB                           | 13        | 0.42%   |
| Seagate ST2000DM008-2FR102 2TB                      | 13        | 0.42%   |
| Samsung SSD 860 EVO 1TB                             | 12        | 0.38%   |
| Samsung NVMe SSD Drive 256GB                        | 12        | 0.38%   |
| Patriot Burst 120GB SSD                             | 12        | 0.38%   |
| Kingston SV300S37A120G 120GB SSD                    | 12        | 0.38%   |
| Unknown                                             | 12        | 0.38%   |
| WDC WD30EFRX-68EUZN0 3TB                            | 11        | 0.35%   |
| Seagate ST500LT012-1DG142 500GB                     | 11        | 0.35%   |
| Samsung MZVLB1T0HBLR-000L2 1TB                      | 11        | 0.35%   |
| Patriot Burst 480GB SSD                             | 11        | 0.35%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 10        | 0.32%   |
| Unknown MMC Card  128GB                             | 10        | 0.32%   |
| Toshiba MQ01ABD100 1TB                              | 10        | 0.32%   |
| Seagate ST500DM002-1BD142 500GB                     | 10        | 0.32%   |
| SanDisk NVMe SSD Drive 512GB                        | 10        | 0.32%   |
| Samsung SSD 980 1TB                                 | 10        | 0.32%   |
| Samsung SSD 850 EVO 500GB                           | 10        | 0.32%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 10        | 0.32%   |
| WDC WD10EZEX-08M2NA0 1TB                            | 9         | 0.29%   |
| Toshiba MQ01ABF050 500GB                            | 9         | 0.29%   |
| SK hynix NVMe SSD Drive 512GB                       | 9         | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 392       | 601    | 37.19%  |
| WDC                 | 344       | 578    | 32.64%  |
| Toshiba             | 99        | 113    | 9.39%   |
| Hitachi             | 84        | 97     | 7.97%   |
| HGST                | 51        | 62     | 4.84%   |
| Samsung Electronics | 48        | 74     | 4.55%   |
| Maxtor              | 9         | 13     | 0.85%   |
| Fujitsu             | 9         | 10     | 0.85%   |
| Unknown             | 4         | 4      | 0.38%   |
| JMicron Technology  | 3         | 3      | 0.28%   |
| ASMedia             | 3         | 4      | 0.28%   |
| pqi                 | 2         | 2      | 0.19%   |
| USB3.0              | 1         | 1      | 0.09%   |
| IBM/Hitachi         | 1         | 1      | 0.09%   |
| External            | 1         | 1      | 0.09%   |
| ASUSTOR             | 1         | 1      | 0.09%   |
| ASMT                | 1         | 1      | 0.09%   |
| Apple               | 1         | 4      | 0.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 187       | 237    | 19%     |
| SanDisk             | 167       | 173    | 16.97%  |
| Kingston            | 153       | 193    | 15.55%  |
| WDC                 | 81        | 110    | 8.23%   |
| A-DATA Technology   | 66        | 78     | 6.71%   |
| Crucial             | 60        | 76     | 6.1%    |
| Patriot             | 46        | 57     | 4.67%   |
| Intel               | 31        | 38     | 3.15%   |
| Micron Technology   | 22        | 34     | 2.24%   |
| Apacer              | 20        | 26     | 2.03%   |
| Transcend           | 17        | 25     | 1.73%   |
| SK hynix            | 15        | 16     | 1.52%   |
| Toshiba             | 13        | 16     | 1.32%   |
| Verbatim            | 12        | 12     | 1.22%   |
| LITEONIT            | 10        | 12     | 1.02%   |
| China               | 10        | 11     | 1.02%   |
| OCZ                 | 8         | 15     | 0.81%   |
| LITEON              | 6         | 7      | 0.61%   |
| GOODRAM             | 6         | 9      | 0.61%   |
| UMAX                | 5         | 5      | 0.51%   |
| Gigabyte Technology | 5         | 12     | 0.51%   |
| Apple               | 5         | 5      | 0.51%   |
| Seagate             | 4         | 4      | 0.41%   |
| Team                | 3         | 3      | 0.3%    |
| SPCC                | 3         | 3      | 0.3%    |
| HPE                 | 3         | 3      | 0.3%    |
| Unknown             | 2         | 8      | 0.2%    |
| FORESEE             | 2         | 2      | 0.2%    |
| WDC WDS1            | 1         | 1      | 0.1%    |
| UMIS                | 1         | 1      | 0.1%    |
| TO Exter            | 1         | 2      | 0.1%    |
| TCSUNBOW            | 1         | 1      | 0.1%    |
| T-CREATE            | 1         | 1      | 0.1%    |
| ShanDianZhe         | 1         | 1      | 0.1%    |
| SATAFIRM            | 1         | 1      | 0.1%    |
| Phison              | 1         | 1      | 0.1%    |
| Netac               | 1         | 1      | 0.1%    |
| Mushkin             | 1         | 1      | 0.1%    |
| Linux               | 1         | 1      | 0.1%    |
| Kingchuxing         | 1         | 1      | 0.1%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 893       | 1570   | 34.73%  |
| SSD     | 890       | 1213   | 34.62%  |
| NVMe    | 651       | 941    | 25.32%  |
| MMC     | 120       | 168    | 4.67%   |
| Unknown | 17        | 22     | 0.66%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1477      | 2711   | 63.53%  |
| NVMe | 650       | 939    | 27.96%  |
| MMC  | 120       | 168    | 5.16%   |
| SAS  | 78        | 96     | 3.35%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1197      | 1752   | 64.39%  |
| 0.51-1.0   | 445       | 635    | 23.94%  |
| 1.01-2.0   | 103       | 201    | 5.54%   |
| 3.01-4.0   | 38        | 55     | 2.04%   |
| 2.01-3.0   | 30        | 51     | 1.61%   |
| 4.01-10.0  | 30        | 61     | 1.61%   |
| 10.01-20.0 | 16        | 28     | 0.86%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 538       | 25.03%  |
| 251-500        | 445       | 20.71%  |
| 1-20           | 309       | 14.38%  |
| 501-1000       | 266       | 12.38%  |
| 51-100         | 151       | 7.03%   |
| 1001-2000      | 140       | 6.51%   |
| Unknown        | 89        | 4.14%   |
| More than 3000 | 88        | 4.09%   |
| 21-50          | 82        | 3.82%   |
| 2001-3000      | 41        | 1.91%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 957       | 43.03%  |
| 21-50          | 286       | 12.86%  |
| 101-250        | 270       | 12.14%  |
| 51-100         | 219       | 9.85%   |
| 251-500        | 169       | 7.6%    |
| 501-1000       | 109       | 4.9%    |
| Unknown        | 89        | 4%      |
| 1001-2000      | 56        | 2.52%   |
| More than 3000 | 44        | 1.98%   |
| 2001-3000      | 25        | 1.12%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| SanDisk SSD U100 256GB                | 125       | 125    | 42.66%  |
| HGST HTS725050A7E630 500GB            | 4         | 4      | 1.37%   |
| SK hynix BC711 HFM512GD3JX013N 512GB  | 3         | 4      | 1.02%   |
| WDC WD60EFRX-68L0BN1 6TB              | 2         | 3      | 0.68%   |
| Toshiba MQ01ABD075 752GB              | 2         | 2      | 0.68%   |
| Toshiba MK1234GSX 120GB               | 2         | 2      | 0.68%   |
| Seagate ST9500420AS 500GB             | 2         | 3      | 0.68%   |
| Seagate ST3250410AS 250GB             | 2         | 4      | 0.68%   |
| Seagate ST3160318AS 160GB             | 2         | 2      | 0.68%   |
| Seagate ST2000DM008-2FR102 2TB        | 2         | 3      | 0.68%   |
| Seagate ST1000LX015-1U7172 1TB        | 2         | 2      | 0.68%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 2         | 2      | 0.68%   |
| Micron Technology 1100 SATA 256GB SSD | 2         | 2      | 0.68%   |
| Kingston SV300S37A120G 120GB SSD      | 2         | 2      | 0.68%   |
| Hitachi HTS541610J9SA00 100GB         | 2         | 2      | 0.68%   |
| HGST HTS721010A9E630 1TB              | 2         | 2      | 0.68%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1         | 1      | 0.34%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD      | 1         | 1      | 0.34%   |
| WDC WDS120G2G0A-00JH30 120GB SSD      | 1         | 1      | 0.34%   |
| WDC WDS100T2B0A-00SM50 1TB SSD        | 1         | 1      | 0.34%   |
| WDC WD800BB-00JHA0 80GB               | 1         | 1      | 0.34%   |
| WDC WD7500BPVT-22HXZT3 752GB          | 1         | 1      | 0.34%   |
| WDC WD7500AADS-00M2B0 752GB           | 1         | 1      | 0.34%   |
| WDC WD6400BPVT-60HXZT1 640GB          | 1         | 1      | 0.34%   |
| WDC WD6400AAKS-22A7B2 640GB           | 1         | 1      | 0.34%   |
| WDC WD5000AAKS-00V0A0 500GB           | 1         | 1      | 0.34%   |
| WDC WD3200BEVT-60ZCT1 320GB           | 1         | 1      | 0.34%   |
| WDC WD3200AAKS-00L9A0 320GB           | 1         | 1      | 0.34%   |
| WDC WD30EFRX-68EUZN0 3TB              | 1         | 1      | 0.34%   |
| WDC WD2502ABYS-02B7A0 256GB           | 1         | 1      | 0.34%   |
| WDC WD2500BPVT-22JJ5T0 250GB          | 1         | 1      | 0.34%   |
| WDC WD2500BEVS-22UST0 250GB           | 1         | 1      | 0.34%   |
| WDC WD2500AAKX-75U6AA0 250GB          | 1         | 1      | 0.34%   |
| WDC WD2500AAKX-60U6AA0 250GB          | 1         | 1      | 0.34%   |
| WDC WD2500AAKX-603CA0 250GB           | 1         | 1      | 0.34%   |
| WDC WD2500AAKX-083CA1 250GB           | 1         | 2      | 0.34%   |
| WDC WD2500AAKS-00VSA0 250GB           | 1         | 1      | 0.34%   |
| WDC WD2500AAJS-08L7A0 250GB           | 1         | 2      | 0.34%   |
| WDC WD20EARX-008FB0 2TB               | 1         | 4      | 0.34%   |
| WDC WD20EARS-00MVWB0 2TB              | 1         | 1      | 0.34%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| SanDisk               | 127       | 127    | 43.94%  |
| Seagate               | 44        | 56     | 15.22%  |
| WDC                   | 32        | 41     | 11.07%  |
| Hitachi               | 17        | 17     | 5.88%   |
| Samsung Electronics   | 16        | 18     | 5.54%   |
| Toshiba               | 12        | 14     | 4.15%   |
| HGST                  | 10        | 10     | 3.46%   |
| Kingston              | 7         | 7      | 2.42%   |
| SK hynix              | 5         | 6      | 1.73%   |
| Micron Technology     | 3         | 3      | 1.04%   |
| Crucial               | 3         | 3      | 1.04%   |
| A-DATA Technology     | 3         | 5      | 1.04%   |
| Intel                 | 2         | 2      | 0.69%   |
| SPCC                  | 1         | 1      | 0.35%   |
| SATAFIRM              | 1         | 1      | 0.35%   |
| Realtek Semiconductor | 1         | 4      | 0.35%   |
| Maxtor                | 1         | 1      | 0.35%   |
| LITEONIT              | 1         | 1      | 0.35%   |
| IBM/Hitachi           | 1         | 1      | 0.35%   |
| Gigabyte Technology   | 1         | 1      | 0.35%   |
| Fujitsu               | 1         | 1      | 0.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 44        | 56     | 36.36%  |
| WDC                 | 27        | 35     | 22.31%  |
| Hitachi             | 17        | 17     | 14.05%  |
| Toshiba             | 12        | 14     | 9.92%   |
| HGST                | 10        | 10     | 8.26%   |
| Samsung Electronics | 8         | 9      | 6.61%   |
| Maxtor              | 1         | 1      | 0.83%   |
| IBM/Hitachi         | 1         | 1      | 0.83%   |
| Fujitsu             | 1         | 1      | 0.83%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 160       | 162    | 55.75%  |
| HDD  | 118       | 144    | 41.11%  |
| NVMe | 9         | 14     | 3.14%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST3500418AS 500GB | 2         | 4      | 66.67%  |
| Unknown 00000  16GB       | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 4      | 66.67%  |
| Unknown | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1116      | 2213   | 51.1%   |
| Works    | 782       | 1376   | 35.81%  |
| Malfunc  | 283       | 320    | 12.96%  |
| Failed   | 3         | 5      | 0.14%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1323      | 52.15%  |
| AMD                              | 401       | 15.81%  |
| Samsung Electronics              | 258       | 10.17%  |
| SanDisk                          | 89        | 3.51%   |
| SK hynix                         | 59        | 2.33%   |
| Kingston Technology Company      | 51        | 2.01%   |
| Toshiba America Info Systems     | 50        | 1.97%   |
| JMicron Technology               | 33        | 1.3%    |
| Phison Electronics               | 30        | 1.18%   |
| Micron Technology                | 30        | 1.18%   |
| ASMedia Technology               | 28        | 1.1%    |
| Nvidia                           | 27        | 1.06%   |
| Marvell Technology Group         | 25        | 0.99%   |
| KIOXIA                           | 22        | 0.87%   |
| Silicon Motion                   | 15        | 0.59%   |
| ADATA Technology                 | 14        | 0.55%   |
| VIA Technologies                 | 11        | 0.43%   |
| Micron/Crucial Technology        | 10        | 0.39%   |
| Seagate Technology               | 7         | 0.28%   |
| Realtek Semiconductor            | 6         | 0.24%   |
| Hewlett-Packard                  | 6         | 0.24%   |
| Union Memory (Shenzhen)          | 5         | 0.2%    |
| Solid State Storage Technology   | 4         | 0.16%   |
| Silicon Image                    | 4         | 0.16%   |
| Silicon Integrated Systems [SiS] | 3         | 0.12%   |
| LSI Logic / Symbios Logic        | 3         | 0.12%   |
| Lite-On Technology               | 3         | 0.12%   |
| Lenovo                           | 3         | 0.12%   |
| Adaptec                          | 3         | 0.12%   |
| OCZ Technology Group             | 2         | 0.08%   |
| Integrated Technology Express    | 2         | 0.08%   |
| Broadcom / LSI                   | 2         | 0.08%   |
| Western Digital                  | 1         | 0.04%   |
| Solidigm                         | 1         | 0.04%   |
| Promise Technology               | 1         | 0.04%   |
| INNOGRIT                         | 1         | 0.04%   |
| Chelsio Communications           | 1         | 0.04%   |
| Biwin Storage Technology         | 1         | 0.04%   |
| Apple                            | 1         | 0.04%   |
| 3ware                            | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 262       | 8.87%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 188       | 6.36%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 121       | 4.09%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 90        | 3.05%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 80        | 2.71%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 72        | 2.44%   |
| Samsung NVMe SSD Controller 980                                                  | 68        | 2.3%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 58        | 1.96%   |
| AMD 400 Series Chipset SATA Controller                                           | 51        | 1.73%   |
| Intel Volume Management Device NVMe RAID Controller                              | 49        | 1.66%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 47        | 1.59%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 46        | 1.56%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 44        | 1.49%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 43        | 1.46%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 38        | 1.29%   |
| AMD 500 Series Chipset SATA Controller                                           | 37        | 1.25%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 36        | 1.22%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 36        | 1.22%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 35        | 1.18%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 33        | 1.12%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 32        | 1.08%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 31        | 1.05%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 31        | 1.05%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 30        | 1.02%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 29        | 0.98%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 29        | 0.98%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 26        | 0.88%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 26        | 0.88%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 26        | 0.88%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 25        | 0.85%   |
| Intel Comet Lake SATA AHCI Controller                                            | 25        | 0.85%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 25        | 0.85%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 22        | 0.74%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 22        | 0.74%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 21        | 0.71%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 21        | 0.71%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 20        | 0.68%   |
| JMicron JMB363 SATA/IDE Controller                                               | 20        | 0.68%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 20        | 0.68%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 20        | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1452      | 56.43%  |
| NVMe | 658       | 25.57%  |
| IDE  | 303       | 11.78%  |
| RAID | 148       | 5.75%   |
| SAS  | 8         | 0.31%   |
| SCSI | 4         | 0.16%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 1511      | 74.18%  |
| AMD      | 512       | 25.14%  |
| ARM      | 13        | 0.64%   |
| QUALCOMM | 1         | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-2677M CPU @ 1.80GHz             | 126       | 6.16%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 23        | 1.12%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 19        | 0.93%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 17        | 0.83%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 17        | 0.83%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 17        | 0.83%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 17        | 0.83%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 16        | 0.78%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 16        | 0.78%   |
| AMD Ryzen 5 3600 6-Core Processor             | 16        | 0.78%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 15        | 0.73%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 14        | 0.68%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 13        | 0.64%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 13        | 0.64%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 13        | 0.64%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 12        | 0.59%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 12        | 0.59%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 11        | 0.54%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 11        | 0.54%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 11        | 0.54%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 11        | 0.54%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 11        | 0.54%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 10        | 0.49%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 10        | 0.49%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 10        | 0.49%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 10        | 0.49%   |
| ARM Processor                                 | 10        | 0.49%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 10        | 0.49%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 9         | 0.44%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 9         | 0.44%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 9         | 0.44%   |
| Intel Celeron N4100 CPU @ 1.10GHz             | 9         | 0.44%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 9         | 0.44%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 9         | 0.44%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 9         | 0.44%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 9         | 0.44%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 8         | 0.39%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 8         | 0.39%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 8         | 0.39%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 8         | 0.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 446       | 21.8%   |
| Intel Core i5           | 365       | 17.84%  |
| AMD Ryzen 5             | 137       | 6.7%    |
| Other                   | 124       | 6.06%   |
| Intel Celeron           | 119       | 5.82%   |
| Intel Core 2 Duo        | 115       | 5.62%   |
| Intel Core i3           | 106       | 5.18%   |
| AMD Ryzen 7             | 89        | 4.35%   |
| Intel Pentium           | 62        | 3.03%   |
| Intel Xeon              | 41        | 2%      |
| Intel Atom              | 38        | 1.86%   |
| AMD FX                  | 36        | 1.76%   |
| AMD Ryzen 7 PRO         | 27        | 1.32%   |
| AMD Ryzen 9             | 26        | 1.27%   |
| Intel Pentium Dual-Core | 23        | 1.12%   |
| AMD Ryzen 3             | 17        | 0.83%   |
| AMD A4                  | 17        | 0.83%   |
| AMD A8                  | 16        | 0.78%   |
| AMD A6                  | 15        | 0.73%   |
| Intel Core 2            | 14        | 0.68%   |
| Intel Pentium Dual      | 12        | 0.59%   |
| AMD Athlon 64 X2        | 12        | 0.59%   |
| Intel Core 2 Quad       | 11        | 0.54%   |
| AMD Ryzen 5 PRO         | 11        | 0.54%   |
| Intel Pentium Silver    | 10        | 0.49%   |
| AMD Phenom II X4        | 10        | 0.49%   |
| AMD A10                 | 10        | 0.49%   |
| Intel Core i9           | 9         | 0.44%   |
| AMD Athlon              | 9         | 0.44%   |
| AMD Athlon II X2        | 8         | 0.39%   |
| Intel Celeron M         | 7         | 0.34%   |
| Intel Pentium Gold      | 6         | 0.29%   |
| AMD E1                  | 6         | 0.29%   |
| Intel Pentium 4         | 5         | 0.24%   |
| Intel Genuine           | 5         | 0.24%   |
| Intel Celeron Dual-Core | 5         | 0.24%   |
| AMD Sempron             | 5         | 0.24%   |
| Intel Pentium M         | 4         | 0.2%    |
| Intel Pentium D         | 4         | 0.2%    |
| AMD Turion II           | 4         | 0.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 890       | 43.48%  |
| 4       | 657       | 32.1%   |
| 6       | 220       | 10.75%  |
| 8       | 144       | 7.03%   |
| 1       | 62        | 3.03%   |
| 12      | 33        | 1.61%   |
| 3       | 13        | 0.64%   |
| 16      | 9         | 0.44%   |
| 10      | 7         | 0.34%   |
| 14      | 6         | 0.29%   |
| Unknown | 3         | 0.15%   |
| 32      | 1         | 0.05%   |
| 28      | 1         | 0.05%   |
| 20      | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 2023      | 99.31%  |
| 2      | 14        | 0.69%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1311      | 64.2%   |
| 1       | 727       | 35.6%   |
| Unknown | 3         | 0.15%   |
| 4       | 1         | 0.05%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1979      | 96.77%  |
| Unknown        | 37        | 1.81%   |
| 32-bit         | 26        | 1.27%   |
| 64-bit         | 3         | 0.15%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 460       | 21.69%  |
| 0x206a7    | 217       | 10.23%  |
| 0x306c3    | 78        | 3.68%   |
| 0x1067a    | 74        | 3.49%   |
| 0x306a9    | 70        | 3.3%    |
| 0x906ea    | 50        | 2.36%   |
| 0x806ec    | 50        | 2.36%   |
| 0x806ea    | 47        | 2.22%   |
| 0x806c1    | 39        | 1.84%   |
| 0x406e3    | 38        | 1.79%   |
| 0x806e9    | 34        | 1.6%    |
| 0x506e3    | 33        | 1.56%   |
| 0x08600106 | 33        | 1.56%   |
| 0x40651    | 32        | 1.51%   |
| 0x6fd      | 31        | 1.46%   |
| 0x0a50000c | 30        | 1.41%   |
| 0x906e9    | 28        | 1.32%   |
| 0x306d4    | 25        | 1.18%   |
| 0x30678    | 24        | 1.13%   |
| 0x08701021 | 23        | 1.08%   |
| 0x10676    | 22        | 1.04%   |
| 0x6fb      | 21        | 0.99%   |
| 0x406c4    | 19        | 0.9%    |
| 0x06000852 | 19        | 0.9%    |
| 0x010000c8 | 19        | 0.9%    |
| 0x706a1    | 18        | 0.85%   |
| 0x20655    | 17        | 0.8%    |
| 0x0800820d | 17        | 0.8%    |
| 0xa0652    | 15        | 0.71%   |
| 0x906ed    | 15        | 0.71%   |
| 0x506c9    | 15        | 0.71%   |
| 0x08608103 | 15        | 0.71%   |
| 0x08600104 | 15        | 0.71%   |
| 0x706e5    | 14        | 0.66%   |
| 0x706a8    | 14        | 0.66%   |
| 0x08108102 | 14        | 0.66%   |
| 0x406c3    | 13        | 0.61%   |
| 0x08701013 | 13        | 0.61%   |
| 0x06001119 | 13        | 0.61%   |
| 0x06006705 | 12        | 0.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 295       | 14.46%  |
| SandyBridge      | 260       | 12.75%  |
| Haswell          | 150       | 7.35%   |
| Penryn           | 118       | 5.78%   |
| Zen 2            | 116       | 5.69%   |
| IvyBridge        | 96        | 4.71%   |
| Skylake          | 90        | 4.41%   |
| Core             | 79        | 3.87%   |
| Zen 3            | 78        | 3.82%   |
| Silvermont       | 75        | 3.68%   |
| Unknown          | 60        | 2.94%   |
| TigerLake        | 56        | 2.75%   |
| Zen+             | 46        | 2.25%   |
| Piledriver       | 46        | 2.25%   |
| Zen              | 42        | 2.06%   |
| Westmere         | 41        | 2.01%   |
| Goldmont plus    | 39        | 1.91%   |
| K10              | 38        | 1.86%   |
| CometLake        | 37        | 1.81%   |
| Broadwell        | 32        | 1.57%   |
| K8 Hammer        | 28        | 1.37%   |
| Excavator        | 26        | 1.27%   |
| Alderlake Hybrid | 26        | 1.27%   |
| IceLake          | 25        | 1.23%   |
| Goldmont         | 18        | 0.88%   |
| Nehalem          | 17        | 0.83%   |
| Bonnell          | 17        | 0.83%   |
| Steamroller      | 13        | 0.64%   |
| Puma             | 13        | 0.64%   |
| P6               | 13        | 0.64%   |
| NetBurst         | 11        | 0.54%   |
| Bobcat           | 10        | 0.49%   |
| Jaguar           | 9         | 0.44%   |
| Tremont          | 7         | 0.34%   |
| K10 Llano        | 6         | 0.29%   |
| K8 & K10 hybrid  | 3         | 0.15%   |
| Bulldozer        | 3         | 0.15%   |
| K6               | 1         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1206      | 50.76%  |
| Nvidia                           | 585       | 24.62%  |
| AMD                              | 562       | 23.65%  |
| Matrox Electronics Systems       | 13        | 0.55%   |
| ASPEED Technology                | 5         | 0.21%   |
| VIA Technologies                 | 2         | 0.08%   |
| Silicon Integrated Systems [SiS] | 2         | 0.08%   |
| ATI Technologies                 | 1         | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 223       | 9.03%   |
| AMD Renoir                                                                               | 69        | 2.79%   |
| Intel UHD Graphics 620                                                                   | 60        | 2.43%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 59        | 2.39%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 47        | 1.9%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 43        | 1.74%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 43        | 1.74%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 41        | 1.66%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 39        | 1.58%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 39        | 1.58%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 38        | 1.54%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 38        | 1.54%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 37        | 1.5%    |
| Intel HD Graphics 620                                                                    | 37        | 1.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 37        | 1.5%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 36        | 1.46%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 32        | 1.3%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 32        | 1.3%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 30        | 1.21%   |
| Intel HD Graphics 5500                                                                   | 26        | 1.05%   |
| Intel HD Graphics 530                                                                    | 26        | 1.05%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 25        | 1.01%   |
| Intel HD Graphics 630                                                                    | 24        | 0.97%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 21        | 0.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 21        | 0.85%   |
| Intel Core Processor Integrated Graphics Controller                                      | 21        | 0.85%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 20        | 0.81%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 20        | 0.81%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 20        | 0.81%   |
| AMD Lucienne                                                                             | 20        | 0.81%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 19        | 0.77%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 18        | 0.73%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 17        | 0.69%   |
| Intel HD Graphics 500                                                                    | 16        | 0.65%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 14        | 0.57%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 14        | 0.57%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 14        | 0.57%   |
| Nvidia GP108M [GeForce MX150]                                                            | 13        | 0.53%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 13        | 0.53%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 13        | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 894       | 43.63%  |
| 1 x AMD        | 434       | 21.18%  |
| 1 x Nvidia     | 311       | 15.18%  |
| Intel + Nvidia | 239       | 11.66%  |
| Intel + AMD    | 61        | 2.98%   |
| 2 x AMD        | 37        | 1.81%   |
| AMD + Nvidia   | 30        | 1.46%   |
| Other          | 14        | 0.68%   |
| 1 x Matrox     | 12        | 0.59%   |
| 1 x ASPEED     | 5         | 0.24%   |
| 2 x Intel      | 3         | 0.15%   |
| 3 x Nvidia     | 2         | 0.1%    |
| 2 x Nvidia     | 2         | 0.1%    |
| 1 x VIA        | 2         | 0.1%    |
| 1 x SiS        | 2         | 0.1%    |
| AMD + Matrox   | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1710      | 82.85%  |
| Proprietary | 278       | 13.47%  |
| Unknown     | 76        | 3.68%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1220      | 58.04%  |
| 0.01-0.5   | 262       | 12.46%  |
| 1.01-2.0   | 232       | 11.04%  |
| 0.51-1.0   | 139       | 6.61%   |
| 3.01-4.0   | 113       | 5.38%   |
| 7.01-8.0   | 61        | 2.9%    |
| 5.01-6.0   | 36        | 1.71%   |
| 2.01-3.0   | 20        | 0.95%   |
| 8.01-16.0  | 16        | 0.76%   |
| 16.01-24.0 | 3         | 0.14%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 281       | 11.98%  |
| Samsung Electronics     | 265       | 11.3%   |
| LG Display              | 200       | 8.53%   |
| Chimei Innolux          | 168       | 7.16%   |
| BOE                     | 157       | 6.7%    |
| Dell                    | 145       | 6.18%   |
| CPT                     | 128       | 5.46%   |
| Goldstar                | 92        | 3.92%   |
| BenQ                    | 90        | 3.84%   |
| Acer                    | 82        | 3.5%    |
| Eizo                    | 77        | 3.28%   |
| Hewlett-Packard         | 71        | 3.03%   |
| Philips                 | 66        | 2.81%   |
| AOC                     | 59        | 2.52%   |
| Lenovo                  | 54        | 2.3%    |
| Ancor Communications    | 45        | 1.92%   |
| Sharp                   | 40        | 1.71%   |
| Iiyama                  | 31        | 1.32%   |
| Chi Mei Optoelectronics | 31        | 1.32%   |
| PANDA                   | 29        | 1.24%   |
| Sony                    | 17        | 0.72%   |
| LG Philips              | 17        | 0.72%   |
| Fujitsu Siemens         | 15        | 0.64%   |
| ASUSTek Computer        | 14        | 0.6%    |
| NEC Computers           | 12        | 0.51%   |
| InfoVision              | 12        | 0.51%   |
| Panasonic               | 11        | 0.47%   |
| CSO                     | 11        | 0.47%   |
| Apple                   | 9         | 0.38%   |
| ViewSonic               | 8         | 0.34%   |
| Vestel Elektronik       | 8         | 0.34%   |
| Unknown                 | 6         | 0.26%   |
| Quanta Display          | 6         | 0.26%   |
| MSI                     | 6         | 0.26%   |
| LG Electronics          | 6         | 0.26%   |
| HannStar                | 6         | 0.26%   |
| Toshiba                 | 4         | 0.17%   |
| Lenovo Group Limited    | 4         | 0.17%   |
| Hitachi                 | 4         | 0.17%   |
| OEM                     | 3         | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| CPT LCD Monitor COR17DB 1600x900 293x164mm 13.2-inch                      | 126       | 5.15%   |
| Eizo EV3285 ENC2979 3840x2160 698x393mm 31.5-inch                         | 56        | 2.29%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 14        | 0.57%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch         | 13        | 0.53%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 13        | 0.53%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 12        | 0.49%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch            | 12        | 0.49%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                       | 11        | 0.45%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 10        | 0.41%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                   | 9         | 0.37%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                          | 8         | 0.33%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 8         | 0.33%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch         | 7         | 0.29%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch         | 7         | 0.29%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                   | 7         | 0.29%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 7         | 0.29%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                  | 7         | 0.29%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                         | 7         | 0.29%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 7         | 0.29%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                   | 6         | 0.25%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch      | 6         | 0.25%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch              | 6         | 0.25%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch               | 6         | 0.25%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch          | 6         | 0.25%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                     | 6         | 0.25%   |
| BenQ GW2470 BNQ78D9 1920x1080 527x296mm 23.8-inch                         | 6         | 0.25%   |
| AU Optronics LCD Monitor AUO34ED 1920x1080 344x193mm 15.5-inch            | 6         | 0.25%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 6         | 0.25%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch             | 6         | 0.25%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                   | 5         | 0.2%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 5         | 0.2%    |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                        | 5         | 0.2%    |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                         | 5         | 0.2%    |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch          | 5         | 0.2%    |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch          | 5         | 0.2%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 5         | 0.2%    |
| Chi Mei Optoelectronics LCD Monitor CMO1520 1680x1050 331x207mm 15.4-inch | 5         | 0.2%    |
| BOE LCD Monitor BOE07BB 1920x1080 309x173mm 13.9-inch                     | 5         | 0.2%    |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch             | 5         | 0.2%    |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch            | 5         | 0.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 977       | 44.13%  |
| 1366x768 (WXGA)    | 269       | 12.15%  |
| 1600x900 (HD+)     | 200       | 9.03%   |
| 3840x2160 (4K)     | 159       | 7.18%   |
| 2560x1440 (QHD)    | 104       | 4.7%    |
| 1920x1200 (WUXGA)  | 79        | 3.57%   |
| 1280x1024 (SXGA)   | 79        | 3.57%   |
| 1680x1050 (WSXGA+) | 76        | 3.43%   |
| 1280x800 (WXGA)    | 63        | 2.85%   |
| 1440x900 (WXGA+)   | 36        | 1.63%   |
| 2560x1600          | 16        | 0.72%   |
| Unknown            | 14        | 0.63%   |
| 2560x1080          | 13        | 0.59%   |
| 3440x1440          | 11        | 0.5%    |
| 1024x768 (XGA)     | 11        | 0.5%    |
| 3840x1080          | 9         | 0.41%   |
| 1360x768           | 9         | 0.41%   |
| 1024x600           | 8         | 0.36%   |
| 1600x1200          | 7         | 0.32%   |
| 2880x1800          | 6         | 0.27%   |
| 1920x540           | 6         | 0.27%   |
| 2160x1350          | 5         | 0.23%   |
| 1280x720 (HD)      | 5         | 0.23%   |
| 3840x2400          | 4         | 0.18%   |
| 2288x1287          | 4         | 0.18%   |
| 1400x1050          | 4         | 0.18%   |
| 3456x2160          | 3         | 0.14%   |
| 3000x2000          | 3         | 0.14%   |
| 2736x1824          | 3         | 0.14%   |
| 2160x1440          | 3         | 0.14%   |
| 800x1280           | 2         | 0.09%   |
| 3840x1200          | 2         | 0.09%   |
| 3200x1800 (QHD+)   | 2         | 0.09%   |
| 1280x768           | 2         | 0.09%   |
| 9600x2160          | 1         | 0.05%   |
| 8320x2160          | 1         | 0.05%   |
| 7680x2160          | 1         | 0.05%   |
| 640x480            | 1         | 0.05%   |
| 6400x2160          | 1         | 0.05%   |
| 6400x1440          | 1         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 532       | 22.53%  |
| 13      | 315       | 13.34%  |
| 24      | 229       | 9.7%    |
| 14      | 187       | 7.92%   |
| 27      | 153       | 6.48%   |
| 23      | 132       | 5.59%   |
| 17      | 116       | 4.91%   |
| 21      | 112       | 4.74%   |
| 31      | 100       | 4.24%   |
| Unknown | 72        | 3.05%   |
| 19      | 71        | 3.01%   |
| 22      | 48        | 2.03%   |
| 12      | 35        | 1.48%   |
| 11      | 33        | 1.4%    |
| 20      | 32        | 1.36%   |
| 18      | 22        | 0.93%   |
| 34      | 19        | 0.8%    |
| 84      | 17        | 0.72%   |
| 16      | 16        | 0.68%   |
| 33      | 12        | 0.51%   |
| 25      | 11        | 0.47%   |
| 40      | 10        | 0.42%   |
| 26      | 10        | 0.42%   |
| 10      | 10        | 0.42%   |
| 32      | 9         | 0.38%   |
| 54      | 8         | 0.34%   |
| 72      | 7         | 0.3%    |
| 52      | 5         | 0.21%   |
| 65      | 4         | 0.17%   |
| 47      | 4         | 0.17%   |
| 46      | 4         | 0.17%   |
| 39      | 4         | 0.17%   |
| 49      | 3         | 0.13%   |
| 43      | 3         | 0.13%   |
| 29      | 3         | 0.13%   |
| 48      | 2         | 0.08%   |
| 28      | 2         | 0.08%   |
| 7       | 2         | 0.08%   |
| 142     | 1         | 0.04%   |
| 60      | 1         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 840       | 36.52%  |
| 501-600        | 471       | 20.48%  |
| 201-300        | 296       | 12.87%  |
| 401-500        | 226       | 9.83%   |
| 351-400        | 159       | 6.91%   |
| 601-700        | 116       | 5.04%   |
| Unknown        | 72        | 3.13%   |
| 701-800        | 39        | 1.7%    |
| 1001-1500      | 35        | 1.52%   |
| 1501-2000      | 24        | 1.04%   |
| 801-900        | 17        | 0.74%   |
| 901-1000       | 2         | 0.09%   |
| 1-100          | 2         | 0.09%   |
| More than 2000 | 1         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1521      | 74.2%   |
| 16/10   | 311       | 15.17%  |
| 5/4     | 85        | 4.15%   |
| Unknown | 59        | 2.88%   |
| 4/3     | 25        | 1.22%   |
| 21/9    | 20        | 0.98%   |
| 3/2     | 19        | 0.93%   |
| 32/9    | 4         | 0.2%    |
| 3.20    | 2         | 0.1%    |
| 0.67    | 2         | 0.1%    |
| 3.73    | 1         | 0.05%   |
| 1.00    | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 525       | 22.44%  |
| 201-250        | 395       | 16.88%  |
| 81-90          | 291       | 12.44%  |
| 71-80          | 213       | 9.1%    |
| 301-350        | 162       | 6.92%   |
| 351-500        | 143       | 6.11%   |
| 151-200        | 131       | 5.6%    |
| 251-300        | 98        | 4.19%   |
| Unknown        | 72        | 3.08%   |
| 121-130        | 71        | 3.03%   |
| More than 1000 | 46        | 1.97%   |
| 141-150        | 45        | 1.92%   |
| 51-60          | 33        | 1.41%   |
| 501-1000       | 32        | 1.37%   |
| 61-70          | 30        | 1.28%   |
| 111-120        | 18        | 0.77%   |
| 131-140        | 15        | 0.64%   |
| 41-50          | 10        | 0.43%   |
| 91-100         | 8         | 0.34%   |
| 1-40           | 2         | 0.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 756       | 34.27%  |
| 51-100        | 745       | 33.77%  |
| 101-120       | 430       | 19.49%  |
| 161-240       | 131       | 5.94%   |
| Unknown       | 72        | 3.26%   |
| 1-50          | 38        | 1.72%   |
| More than 240 | 34        | 1.54%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1552      | 73.83%  |
| 2     | 400       | 19.03%  |
| 0     | 90        | 4.28%   |
| 3     | 58        | 2.76%   |
| 4     | 2         | 0.1%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 981       | 32.09%  |
| Intel                             | 952       | 31.14%  |
| Qualcomm Atheros                  | 440       | 14.39%  |
| Broadcom                          | 133       | 4.35%   |
| Samsung Electronics               | 132       | 4.32%   |
| Broadcom Limited                  | 55        | 1.8%    |
| MediaTek                          | 41        | 1.34%   |
| Marvell Technology Group          | 36        | 1.18%   |
| TP-Link                           | 30        | 0.98%   |
| Lenovo                            | 23        | 0.75%   |
| Qualcomm Atheros Communications   | 21        | 0.69%   |
| Ralink Technology                 | 19        | 0.62%   |
| Nvidia                            | 19        | 0.62%   |
| Ralink                            | 18        | 0.59%   |
| Dell                              | 17        | 0.56%   |
| ASIX Electronics                  | 13        | 0.43%   |
| DisplayLink                       | 12        | 0.39%   |
| Sierra Wireless                   | 11        | 0.36%   |
| ASUSTek Computer                  | 8         | 0.26%   |
| VIA Technologies                  | 6         | 0.2%    |
| Microsoft                         | 6         | 0.2%    |
| D-Link                            | 6         | 0.2%    |
| Xiaomi                            | 5         | 0.16%   |
| QLogic                            | 5         | 0.16%   |
| Ericsson Business Mobile Networks | 5         | 0.16%   |
| Attansic Technology               | 5         | 0.16%   |
| ZyDAS                             | 3         | 0.1%    |
| Qualcomm                          | 3         | 0.1%    |
| OnePlus Technology (Shenzhen)     | 3         | 0.1%    |
| Mellanox Technologies             | 3         | 0.1%    |
| Huawei Technologies               | 3         | 0.1%    |
| Hewlett-Packard                   | 3         | 0.1%    |
| Edimax Technology                 | 3         | 0.1%    |
| Spreadtrum Communications         | 2         | 0.07%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.07%   |
| IBM                               | 2         | 0.07%   |
| Fibocom                           | 2         | 0.07%   |
| D-Link System                     | 2         | 0.07%   |
| Arduino SA                        | 2         | 0.07%   |
| American Megatrends               | 2         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 685       | 19.27%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 152       | 4.28%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 128       | 3.6%    |
| Intel Wi-Fi 6 AX200                                               | 104       | 2.93%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 92        | 2.59%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 72        | 2.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 70        | 1.97%   |
| Intel Wireless 8265 / 8275                                        | 68        | 1.91%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 46        | 1.29%   |
| Intel Wireless 7260                                               | 46        | 1.29%   |
| Intel Wi-Fi 6 AX201                                               | 42        | 1.18%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 41        | 1.15%   |
| Realtek RTL8125 2.5GbE Controller                                 | 40        | 1.13%   |
| Intel Wireless 8260                                               | 39        | 1.1%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 38        | 1.07%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 36        | 1.01%   |
| Intel I211 Gigabit Network Connection                             | 36        | 1.01%   |
| Intel Ethernet Connection I217-LM                                 | 34        | 0.96%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 32        | 0.9%    |
| Intel Wireless 7265                                               | 32        | 0.9%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 32        | 0.9%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 32        | 0.9%    |
| Intel Wireless 3165                                               | 31        | 0.87%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 30        | 0.84%   |
| Intel Ethernet Connection (4) I219-LM                             | 28        | 0.79%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 28        | 0.79%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 26        | 0.73%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 23        | 0.65%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 22        | 0.62%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 21        | 0.59%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 21        | 0.59%   |
| Intel Ethernet Connection (2) I219-V                              | 20        | 0.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 19        | 0.53%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 18        | 0.51%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 18        | 0.51%   |
| Qualcomm Atheros AR9271 802.11n                                   | 18        | 0.51%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 18        | 0.51%   |
| Intel 82567LM Gigabit Network Connection                          | 18        | 0.51%   |
| Intel Wireless 3160                                               | 17        | 0.48%   |
| Intel WiFi Link 5100                                              | 17        | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 755       | 47.75%  |
| Qualcomm Atheros                  | 355       | 22.45%  |
| Realtek Semiconductor             | 183       | 11.57%  |
| Broadcom                          | 76        | 4.81%   |
| MediaTek                          | 39        | 2.47%   |
| TP-Link                           | 28        | 1.77%   |
| Broadcom Limited                  | 27        | 1.71%   |
| Qualcomm Atheros Communications   | 21        | 1.33%   |
| Ralink Technology                 | 19        | 1.2%    |
| Ralink                            | 18        | 1.14%   |
| Sierra Wireless                   | 11        | 0.7%    |
| Dell                              | 11        | 0.7%    |
| ASUSTek Computer                  | 7         | 0.44%   |
| Microsoft                         | 6         | 0.38%   |
| D-Link                            | 5         | 0.32%   |
| ZyDAS                             | 3         | 0.19%   |
| Edimax Technology                 | 3         | 0.19%   |
| Qualcomm                          | 2         | 0.13%   |
| Marvell Technology Group          | 2         | 0.13%   |
| Fibocom                           | 2         | 0.13%   |
| ZyXEL Communications              | 1         | 0.06%   |
| Texas Instruments                 | 1         | 0.06%   |
| Mercucys                          | 1         | 0.06%   |
| Intersil                          | 1         | 0.06%   |
| Hewlett-Packard                   | 1         | 0.06%   |
| Fujitsu Siemens Computers         | 1         | 0.06%   |
| Ericsson Business Mobile Networks | 1         | 0.06%   |
| D-Link System                     | 1         | 0.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 152       | 9.59%   |
| Intel Wi-Fi 6 AX200                                            | 104       | 6.56%   |
| Intel Wireless 8265 / 8275                                     | 68        | 4.29%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 46        | 2.9%    |
| Intel Wireless 7260                                            | 46        | 2.9%    |
| Intel Wi-Fi 6 AX201                                            | 42        | 2.65%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 41        | 2.59%   |
| Intel Wireless 8260                                            | 39        | 2.46%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 38        | 2.4%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 36        | 2.27%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 32        | 2.02%   |
| Intel Wireless 7265                                            | 32        | 2.02%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 32        | 2.02%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 32        | 2.02%   |
| Intel Wireless 3165                                            | 31        | 1.96%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 30        | 1.89%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 28        | 1.77%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 26        | 1.64%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 23        | 1.45%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 22        | 1.39%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 18        | 1.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 18        | 1.14%   |
| Qualcomm Atheros AR9271 802.11n                                | 18        | 1.14%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 18        | 1.14%   |
| Intel Wireless 3160                                            | 17        | 1.07%   |
| Intel WiFi Link 5100                                           | 17        | 1.07%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 17        | 1.07%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 17        | 1.07%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 17        | 1.07%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 16        | 1.01%   |
| Broadcom BCM43142 802.11b/g/n                                  | 14        | 0.88%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 13        | 0.82%   |
| Intel Centrino Wireless-N 2230                                 | 13        | 0.82%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 12        | 0.76%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 11        | 0.69%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 11        | 0.69%   |
| Intel Wireless-AC 9260                                         | 11        | 0.69%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 11        | 0.69%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 10        | 0.63%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 10        | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 895       | 47.58%  |
| Intel                             | 485       | 25.78%  |
| Samsung Electronics               | 128       | 6.8%    |
| Qualcomm Atheros                  | 125       | 6.65%   |
| Broadcom                          | 65        | 3.46%   |
| Marvell Technology Group          | 35        | 1.86%   |
| Broadcom Limited                  | 28        | 1.49%   |
| Lenovo                            | 23        | 1.22%   |
| Nvidia                            | 19        | 1.01%   |
| ASIX Electronics                  | 13        | 0.69%   |
| DisplayLink                       | 12        | 0.64%   |
| Xiaomi                            | 5         | 0.27%   |
| VIA Technologies                  | 5         | 0.27%   |
| QLogic                            | 5         | 0.27%   |
| Attansic Technology               | 5         | 0.27%   |
| Mellanox Technologies             | 3         | 0.16%   |
| TP-Link                           | 2         | 0.11%   |
| Spreadtrum Communications         | 2         | 0.11%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.11%   |
| MediaTek                          | 2         | 0.11%   |
| IBM                               | 2         | 0.11%   |
| Huawei Technologies               | 2         | 0.11%   |
| American Megatrends               | 2         | 0.11%   |
| Sundance Technology Inc / IC Plus | 1         | 0.05%   |
| Qualcomm                          | 1         | 0.05%   |
| MosChip Semiconductor             | 1         | 0.05%   |
| Microchip Technology              | 1         | 0.05%   |
| JMicron Technology                | 1         | 0.05%   |
| ICS Advent                        | 1         | 0.05%   |
| Hewlett-Packard                   | 1         | 0.05%   |
| Google                            | 1         | 0.05%   |
| Foxconn / Hon Hai                 | 1         | 0.05%   |
| Emulex                            | 1         | 0.05%   |
| D-Link System                     | 1         | 0.05%   |
| D-Link                            | 1         | 0.05%   |
| Chelsio Communications            | 1         | 0.05%   |
| ASUSTek Computer                  | 1         | 0.05%   |
| Aquantia                          | 1         | 0.05%   |
| 3Com                              | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 685       | 35.4%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 128       | 6.61%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 92        | 4.75%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 72        | 3.72%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 70        | 3.62%   |
| Realtek RTL8125 2.5GbE Controller                                 | 40        | 2.07%   |
| Intel I211 Gigabit Network Connection                             | 36        | 1.86%   |
| Intel Ethernet Connection I217-LM                                 | 34        | 1.76%   |
| Intel Ethernet Connection (4) I219-LM                             | 28        | 1.45%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 21        | 1.09%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 21        | 1.09%   |
| Intel Ethernet Connection (2) I219-V                              | 20        | 1.03%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 19        | 0.98%   |
| Intel 82567LM Gigabit Network Connection                          | 18        | 0.93%   |
| Intel Ethernet Controller I225-V                                  | 16        | 0.83%   |
| Intel Ethernet Connection I219-LM                                 | 16        | 0.83%   |
| Intel Ethernet Connection I218-LM                                 | 15        | 0.78%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 13        | 0.67%   |
| Intel Ethernet Connection (7) I219-LM                             | 13        | 0.67%   |
| Intel Ethernet Connection (4) I219-V                              | 13        | 0.67%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 13        | 0.67%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 12        | 0.62%   |
| Intel Ethernet Connection (7) I219-V                              | 12        | 0.62%   |
| ASIX AX88179 Gigabit Ethernet                                     | 12        | 0.62%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 11        | 0.57%   |
| Intel Ethernet Connection (6) I219-V                              | 11        | 0.57%   |
| Intel 82579V Gigabit Network Connection                           | 10        | 0.52%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 10        | 0.52%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 10        | 0.52%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 9         | 0.47%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 9         | 0.47%   |
| Intel Ethernet Connection (2) I219-LM                             | 9         | 0.47%   |
| Intel Ethernet Connection (2) I218-V                              | 9         | 0.47%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 8         | 0.41%   |
| Intel Ethernet Connection (6) I219-LM                             | 8         | 0.41%   |
| Intel Ethernet Connection (3) I218-LM                             | 8         | 0.41%   |
| Intel Ethernet Connection (11) I219-LM                            | 8         | 0.41%   |
| Intel Ethernet Connection (10) I219-LM                            | 8         | 0.41%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 8         | 0.41%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 8         | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1762      | 53.25%  |
| WiFi     | 1514      | 45.75%  |
| Modem    | 28        | 0.85%   |
| Unknown  | 5         | 0.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1079      | 51.21%  |
| Ethernet | 1026      | 48.69%  |
| Modem    | 2         | 0.09%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1029      | 50.29%  |
| 1     | 921       | 45.01%  |
| 0     | 48        | 2.35%   |
| 3     | 31        | 1.52%   |
| 4     | 7         | 0.34%   |
| 8     | 4         | 0.2%    |
| 5     | 3         | 0.15%   |
| 10    | 1         | 0.05%   |
| 9     | 1         | 0.05%   |
| 6     | 1         | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1803      | 87.14%  |
| Yes  | 266       | 12.86%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 572       | 48.64%  |
| Realtek Semiconductor           | 108       | 9.18%   |
| Qualcomm Atheros Communications | 77        | 6.55%   |
| IMC Networks                    | 74        | 6.29%   |
| Broadcom                        | 62        | 5.27%   |
| Cambridge Silicon Radio         | 58        | 4.93%   |
| Foxconn / Hon Hai               | 45        | 3.83%   |
| Lite-On Technology              | 41        | 3.49%   |
| ASUSTek Computer                | 41        | 3.49%   |
| Hewlett-Packard                 | 25        | 2.13%   |
| Dell                            | 17        | 1.45%   |
| MediaTek                        | 9         | 0.77%   |
| Ralink                          | 8         | 0.68%   |
| Apple                           | 8         | 0.68%   |
| Alps Electric                   | 5         | 0.43%   |
| Toshiba                         | 4         | 0.34%   |
| Realtek                         | 4         | 0.34%   |
| Integrated System Solution      | 3         | 0.26%   |
| TP-Link                         | 2         | 0.17%   |
| Ralink Technology               | 2         | 0.17%   |
| Micro Star International        | 2         | 0.17%   |
| Marvell Semiconductor           | 2         | 0.17%   |
| Creative Technology             | 2         | 0.17%   |
| Mobile Action Technology        | 1         | 0.09%   |
| Fujitsu Siemens Computers       | 1         | 0.09%   |
| Foxconn International           | 1         | 0.09%   |
| Belkin Components               | 1         | 0.09%   |
| Askey Computer                  | 1         | 0.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 223       | 18.96%  |
| Intel AX200 Bluetooth                               | 101       | 8.59%   |
| Intel AX201 Bluetooth                               | 98        | 8.33%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 77        | 6.55%   |
| Realtek Bluetooth Radio                             | 70        | 5.95%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 58        | 4.93%   |
| Qualcomm Atheros  Bluetooth Device                  | 31        | 2.64%   |
| Realtek  Bluetooth 4.2 Adapter                      | 26        | 2.21%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 23        | 1.96%   |
| IMC Networks Bluetooth Device                       | 19        | 1.62%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 18        | 1.53%   |
| Intel Wireless-AC 3168 Bluetooth                    | 17        | 1.45%   |
| IMC Networks Bluetooth Radio                        | 17        | 1.45%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 15        | 1.28%   |
| Intel Bluetooth Device                              | 15        | 1.28%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 14        | 1.19%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 14        | 1.19%   |
| IMC Networks Wireless_Device                        | 13        | 1.11%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 12        | 1.02%   |
| Broadcom BCM2045 Bluetooth                          | 12        | 1.02%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 12        | 1.02%   |
| Intel AX210 Bluetooth                               | 11        | 0.94%   |
| Lite-On Atheros AR3012 Bluetooth                    | 10        | 0.85%   |
| HP Broadcom 2070 Bluetooth Combo                    | 10        | 0.85%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 10        | 0.85%   |
| Foxconn / Hon Hai Bluetooth Device                  | 10        | 0.85%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 9         | 0.77%   |
| Dell DW375 Bluetooth Module                         | 9         | 0.77%   |
| Broadcom BCM2045B (BDC-2.1)                         | 9         | 0.77%   |
| ASUS ASUS USB-BT500                                 | 9         | 0.77%   |
| Ralink RT3290 Bluetooth                             | 8         | 0.68%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 8         | 0.68%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter               | 8         | 0.68%   |
| Broadcom HP Portable SoftSailing                    | 7         | 0.6%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 7         | 0.6%    |
| Qualcomm Atheros Bluetooth                          | 6         | 0.51%   |
| MediaTek Wireless_Device                            | 6         | 0.51%   |
| Lite-On Bluetooth Device                            | 6         | 0.51%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 6         | 0.51%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 5         | 0.43%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1441      | 53.47%  |
| AMD                                  | 594       | 22.04%  |
| Nvidia                               | 384       | 14.25%  |
| C-Media Electronics                  | 50        | 1.86%   |
| Lenovo                               | 32        | 1.19%   |
| Realtek Semiconductor                | 23        | 0.85%   |
| Creative Labs                        | 16        | 0.59%   |
| Logitech                             | 14        | 0.52%   |
| GN Netcom                            | 13        | 0.48%   |
| Creative Technology                  | 13        | 0.48%   |
| VIA Technologies                     | 12        | 0.45%   |
| JMTek                                | 10        | 0.37%   |
| Hewlett-Packard                      | 8         | 0.3%    |
| Plantronics                          | 6         | 0.22%   |
| Kingston Technology                  | 6         | 0.22%   |
| Dell                                 | 5         | 0.19%   |
| Trust                                | 4         | 0.15%   |
| Razer USA                            | 4         | 0.15%   |
| GYROCOM C&C                          | 4         | 0.15%   |
| Focusrite-Novation                   | 4         | 0.15%   |
| DSEA A/S                             | 4         | 0.15%   |
| Silicon Integrated Systems [SiS]     | 3         | 0.11%   |
| BEHRINGER International              | 3         | 0.11%   |
| ASUSTek Computer                     | 3         | 0.11%   |
| Samson Technologies                  | 2         | 0.07%   |
| RODE Microphones                     | 2         | 0.07%   |
| Micro Star International             | 2         | 0.07%   |
| M-Audio                              | 2         | 0.07%   |
| Harman                               | 2         | 0.07%   |
| DigiTech                             | 2         | 0.07%   |
| Conexant Systems                     | 2         | 0.07%   |
| Yealink Network Technology           | 1         | 0.04%   |
| Toshiba                              | 1         | 0.04%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.04%   |
| Texas Instruments                    | 1         | 0.04%   |
| Tenx Technology                      | 1         | 0.04%   |
| Syntek                               | 1         | 0.04%   |
| SteelSeries ApS                      | 1         | 0.04%   |
| Sony                                 | 1         | 0.04%   |
| Sennheiser Communications            | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 237       | 7.38%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 194       | 6.04%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 144       | 4.48%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 122       | 3.8%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 100       | 3.11%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 86        | 2.68%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 84        | 2.62%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 77        | 2.4%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 72        | 2.24%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 71        | 2.21%   |
| Intel Cannon Lake PCH cAVS                                                                        | 71        | 2.21%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 69        | 2.15%   |
| AMD FCH Azalia Controller                                                                         | 60        | 1.87%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 56        | 1.74%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 49        | 1.53%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 47        | 1.46%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 44        | 1.37%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 43        | 1.34%   |
| Intel 8 Series HD Audio Controller                                                                | 43        | 1.34%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 42        | 1.31%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 41        | 1.28%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 39        | 1.21%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 38        | 1.18%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 38        | 1.18%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 36        | 1.12%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 36        | 1.12%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 36        | 1.12%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 34        | 1.06%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 33        | 1.03%   |
| Intel Broadwell-U Audio Controller                                                                | 31        | 0.97%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 30        | 0.93%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 30        | 0.93%   |
| Intel 200 Series PCH HD Audio                                                                     | 26        | 0.81%   |
| AMD Kabini HDMI/DP Audio                                                                          | 26        | 0.81%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 25        | 0.78%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 25        | 0.78%   |
| Intel Comet Lake PCH cAVS                                                                         | 24        | 0.75%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 22        | 0.69%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 21        | 0.65%   |
| Realtek Semiconductor USB Audio                                                                   | 20        | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 263       | 19.85%  |
| Kingston             | 239       | 18.04%  |
| SK hynix             | 205       | 15.47%  |
| Elpida               | 143       | 10.79%  |
| Micron Technology    | 130       | 9.81%   |
| Unknown              | 125       | 9.43%   |
| Crucial              | 51        | 3.85%   |
| Corsair              | 37        | 2.79%   |
| Ramaxel Technology   | 29        | 2.19%   |
| Patriot              | 23        | 1.74%   |
| A-DATA Technology    | 21        | 1.58%   |
| Unknown (ABCD)       | 16        | 1.21%   |
| G.Skill              | 11        | 0.83%   |
| Nanya Technology     | 10        | 0.75%   |
| Transcend            | 5         | 0.38%   |
| GOODRAM              | 2         | 0.15%   |
| Unknown (AB)         | 1         | 0.08%   |
| Toshiba              | 1         | 0.08%   |
| TakeMS               | 1         | 0.08%   |
| ProMos/Mosel Vitelic | 1         | 0.08%   |
| PDPSystems           | 1         | 0.08%   |
| Patriot Memory       | 1         | 0.08%   |
| OnBoard              | 1         | 0.08%   |
| Nayna                | 1         | 0.08%   |
| Kingmax              | 1         | 0.08%   |
| Kimtigo              | 1         | 0.08%   |
| H                    | 1         | 0.08%   |
| Golden Empire        | 1         | 0.08%   |
| Apacer               | 1         | 0.08%   |
| AMD                  | 1         | 0.08%   |
| Unknown              | 1         | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Elpida RAM Module 2GB SODIMM DDR3 1333MT/s                       | 125       | 8.82%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 15        | 1.06%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 13        | 0.92%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 12        | 0.85%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 10        | 0.71%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 9         | 0.63%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 9         | 0.63%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 9         | 0.63%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 9         | 0.63%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 9         | 0.63%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s             | 9         | 0.63%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 8         | 0.56%   |
| SK hynix RAM Module 8GB SODIMM DDR4 3200MT/s                     | 7         | 0.49%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 0.49%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 7         | 0.49%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 7         | 0.49%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 7         | 0.49%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s              | 7         | 0.49%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 6         | 0.42%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 6         | 0.42%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.42%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.42%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s            | 6         | 0.42%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 5         | 0.35%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 5         | 0.35%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.35%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.35%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 0.35%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 0.35%   |
| Samsung RAM Module 8GB SODIMM DDR4 3200MT/s                      | 5         | 0.35%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.35%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 5         | 0.35%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 5         | 0.35%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 5         | 0.35%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 5         | 0.35%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.35%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 5         | 0.35%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 5         | 0.35%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 5         | 0.35%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s           | 5         | 0.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 512       | 44.02%  |
| DDR3    | 436       | 37.49%  |
| DDR2    | 58        | 4.99%   |
| LPDDR4  | 55        | 4.73%   |
| Unknown | 33        | 2.84%   |
| SDRAM   | 22        | 1.89%   |
| LPDDR3  | 22        | 1.89%   |
| DDR5    | 8         | 0.69%   |
| DDR     | 8         | 0.69%   |
| LPDDR5  | 7         | 0.6%    |
| DRAM    | 2         | 0.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 730       | 62.61%  |
| DIMM         | 345       | 29.59%  |
| Row Of Chips | 76        | 6.52%   |
| Chip         | 12        | 1.03%   |
| RIMM         | 2         | 0.17%   |
| Unknown      | 1         | 0.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 436       | 34.71%  |
| 4096  | 278       | 22.13%  |
| 2048  | 260       | 20.7%   |
| 16384 | 187       | 14.89%  |
| 32768 | 51        | 4.06%   |
| 1024  | 36        | 2.87%   |
| 512   | 4         | 0.32%   |
| 256   | 2         | 0.16%   |
| 6144  | 1         | 0.08%   |
| 3072  | 1         | 0.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1333    | 199       | 15.88%  |
| 3200    | 194       | 15.48%  |
| 1600    | 192       | 15.32%  |
| 2667    | 150       | 11.97%  |
| 2400    | 93        | 7.42%   |
| 2133    | 62        | 4.95%   |
| 3600    | 38        | 3.03%   |
| 800     | 37        | 2.95%   |
| 1334    | 35        | 2.79%   |
| 667     | 23        | 1.84%   |
| Unknown | 22        | 1.76%   |
| 4267    | 20        | 1.6%    |
| 1867    | 17        | 1.36%   |
| 3266    | 14        | 1.12%   |
| 1067    | 14        | 1.12%   |
| 3400    | 9         | 0.72%   |
| 6400    | 8         | 0.64%   |
| 2666    | 8         | 0.64%   |
| 1866    | 8         | 0.64%   |
| 3466    | 7         | 0.56%   |
| 1066    | 7         | 0.56%   |
| 4266    | 6         | 0.48%   |
| 3733    | 6         | 0.48%   |
| 3000    | 6         | 0.48%   |
| 533     | 6         | 0.48%   |
| 4199    | 5         | 0.4%    |
| 2933    | 5         | 0.4%    |
| 1800    | 5         | 0.4%    |
| 975     | 5         | 0.4%    |
| 4800    | 4         | 0.32%   |
| 3933    | 4         | 0.32%   |
| 3800    | 4         | 0.32%   |
| 400     | 4         | 0.32%   |
| 3533    | 3         | 0.24%   |
| 3333    | 3         | 0.24%   |
| 2800    | 3         | 0.24%   |
| 2048    | 3         | 0.24%   |
| 8400    | 2         | 0.16%   |
| 5600    | 2         | 0.16%   |
| 4133    | 2         | 0.16%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 10        | 24.39%  |
| Canon               | 10        | 24.39%  |
| Samsung Electronics | 6         | 14.63%  |
| Brother Industries  | 5         | 12.2%   |
| QinHeng Electronics | 3         | 7.32%   |
| Xerox               | 2         | 4.88%   |
| Seiko Epson         | 1         | 2.44%   |
| Prolific Technology | 1         | 2.44%   |
| Pantum              | 1         | 2.44%   |
| Minolta             | 1         | 2.44%   |
| ICS Advent          | 1         | 2.44%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| QinHeng CH340S                          | 3         | 7.14%   |
| HP DeskJet 2620 All-in-One Printer      | 3         | 7.14%   |
| Samsung M2070 Series                    | 2         | 4.76%   |
| HP LaserJet P2014                       | 2         | 4.76%   |
| Xerox Phaser 3260                       | 1         | 2.38%   |
| Xerox B215                              | 1         | 2.38%   |
| Seiko Epson L365 Series                 | 1         | 2.38%   |
| Samsung Xerox Phaser 3117 Laser Printer | 1         | 2.38%   |
| Samsung M267x 287x Series               | 1         | 2.38%   |
| Samsung M2020 Series                    | 1         | 2.38%   |
| Samsung C460 Series                     | 1         | 2.38%   |
| Prolific PL2305 Parallel Port           | 1         | 2.38%   |
| Pantum P2000                            | 1         | 2.38%   |
| Minolta PagePro 1300W                   | 1         | 2.38%   |
| ICS Advent Parallel Adapter             | 1         | 2.38%   |
| HP Officejet 4500 G510g-m               | 1         | 2.38%   |
| HP Neverstop Laser 100x                 | 1         | 2.38%   |
| HP LaserJet Professional P 1102w        | 1         | 2.38%   |
| HP LaserJet 1018                        | 1         | 2.38%   |
| HP Deskjet 3050 J610 series             | 1         | 2.38%   |
| Canon TS6300 series                     | 1         | 2.38%   |
| Canon PIXMA MX920 Series                | 1         | 2.38%   |
| Canon PIXMA MX720 Series                | 1         | 2.38%   |
| Canon PIXMA MP280                       | 1         | 2.38%   |
| Canon PIXMA MG3500 Series               | 1         | 2.38%   |
| Canon PIXMA MG2500 Series               | 1         | 2.38%   |
| Canon MG5600 series                     | 1         | 2.38%   |
| Canon MF4100 series                     | 1         | 2.38%   |
| Canon LBP3010/LBP3018/LBP3050           | 1         | 2.38%   |
| Canon iP7200 series                     | 1         | 2.38%   |
| Canon CanoScan LiDE 300                 | 1         | 2.38%   |
| Brother MFC-J3930DW                     | 1         | 2.38%   |
| Brother HL-2030 Laser Printer           | 1         | 2.38%   |
| Brother HL-1430 Laser Printer           | 1         | 2.38%   |
| Brother DCP-J105                        | 1         | 2.38%   |
| Brother DCP-1610W                       | 1         | 2.38%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 7         | 77.78%  |
| Mustek Systems  | 1         | 11.11%  |
| Hewlett-Packard | 1         | 11.11%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Canon CanoScan LIDE 25              | 2         | 22.22%  |
| Canon CanoScan LiDE 210             | 2         | 22.22%  |
| Mustek Systems BearPaw 1200 CU Plus | 1         | 11.11%  |
| HP ScanJet 2200c                    | 1         | 11.11%  |
| Canon CanoScan LiDE 200             | 1         | 11.11%  |
| Canon CanoScan LiDE 120             | 1         | 11.11%  |
| Canon CanoScan LiDE 100             | 1         | 11.11%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 274       | 23.89%  |
| Realtek Semiconductor                  | 115       | 10.03%  |
| IMC Networks                           | 105       | 9.15%   |
| Microdia                               | 86        | 7.5%    |
| Bison Electronics                      | 70        | 6.1%    |
| Sunplus Innovation Technology          | 69        | 6.02%   |
| Quanta                                 | 48        | 4.18%   |
| Cheng Uei Precision Industry (Foxlink) | 47        | 4.1%    |
| Lite-On Technology                     | 45        | 3.92%   |
| Acer                                   | 35        | 3.05%   |
| Suyin                                  | 34        | 2.96%   |
| Syntek                                 | 32        | 2.79%   |
| Logitech                               | 28        | 2.44%   |
| Apple                                  | 17        | 1.48%   |
| Samsung Electronics                    | 12        | 1.05%   |
| KYE Systems (Mouse Systems)            | 12        | 1.05%   |
| Luxvisions Innotech Limited            | 11        | 0.96%   |
| Lenovo                                 | 11        | 0.96%   |
| Alcor Micro                            | 11        | 0.96%   |
| Ricoh                                  | 10        | 0.87%   |
| Z-Star Microelectronics                | 9         | 0.78%   |
| Microsoft                              | 8         | 0.7%    |
| Creative Technology                    | 8         | 0.7%    |
| Primax Electronics                     | 5         | 0.44%   |
| GEMBIRD                                | 5         | 0.44%   |
| Hopewin Electronic Material            | 4         | 0.35%   |
| Sonix Technology                       | 3         | 0.26%   |
| icSpring                               | 3         | 0.26%   |
| Generalplus Technology                 | 3         | 0.26%   |
| Intel                                  | 2         | 0.17%   |
| Hewlett-Packard                        | 2         | 0.17%   |
| YGTek                                  | 1         | 0.09%   |
| WaveRider Communications               | 1         | 0.09%   |
| Unknown                                | 1         | 0.09%   |
| SunplusIT                              | 1         | 0.09%   |
| Sunplus Technology                     | 1         | 0.09%   |
| Smartronix                             | 1         | 0.09%   |
| Silicon Motion                         | 1         | 0.09%   |
| Ruision                                | 1         | 0.09%   |
| Pixart Imaging                         | 1         | 0.09%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 70        | 6.03%   |
| IMC Networks Integrated Camera                      | 47        | 4.05%   |
| Realtek Integrated_Webcam_HD                        | 38        | 3.27%   |
| Microdia Integrated_Webcam_HD                       | 35        | 3.01%   |
| Chicony HD WebCam                                   | 28        | 2.41%   |
| Chicony HP HD Camera                                | 27        | 2.33%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 24        | 2.07%   |
| Lite-On HP HD Camera                                | 19        | 1.64%   |
| Syntek Integrated Camera                            | 17        | 1.46%   |
| Sunplus Integrated_Webcam_HD                        | 16        | 1.38%   |
| Bison Integrated Camera                             | 16        | 1.38%   |
| Chicony Integrated Camera (1280x720@30)             | 15        | 1.29%   |
| Acer Integrated Camera                              | 15        | 1.29%   |
| Realtek USB Camera                                  | 14        | 1.21%   |
| Bison Lenovo EasyCamera                             | 13        | 1.12%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 13        | 1.12%   |
| Samsung Galaxy series, misc. (MTP mode)             | 12        | 1.03%   |
| Lite-On Integrated Camera                           | 12        | 1.03%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 12        | 1.03%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 11        | 0.95%   |
| Sunplus HD WebCam                                   | 10        | 0.86%   |
| Quanta HP HD Camera                                 | 10        | 0.86%   |
| Microdia Integrated Webcam                          | 10        | 0.86%   |
| Chicony USB2.0 VGA UVC WebCam                       | 10        | 0.86%   |
| Bison SunplusIT Integrated Camera                   | 10        | 0.86%   |
| Quanta HD User Facing                               | 9         | 0.78%   |
| Syntek Lenovo EasyCamera                            | 8         | 0.69%   |
| Realtek Integrated Webcam HD                        | 8         | 0.69%   |
| Quanta HP Wide Vision HD Camera                     | 8         | 0.69%   |
| Chicony Lenovo EasyCamera                           | 8         | 0.69%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 8         | 0.69%   |
| Sunplus Asus Webcam                                 | 7         | 0.6%    |
| Logitech Webcam C270                                | 7         | 0.6%    |
| Lenovo Integrated Webcam                            | 7         | 0.6%    |
| Chicony HP HD Webcam                                | 7         | 0.6%    |
| Cheng Uei Precision Industry (Foxlink) Webcam       | 7         | 0.6%    |
| Bison Lenovo Integrated Webcam                      | 7         | 0.6%    |
| Sunplus HP HD Webcam [Fixed]                        | 6         | 0.52%   |
| Realtek USB2.0 VGA UVC WebCam                       | 6         | 0.52%   |
| Realtek Acer 640 x 480 laptop camera                | 6         | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 109       | 35.39%  |
| Validity Sensors                   | 98        | 31.82%  |
| Shenzhen Goodix Technology         | 36        | 11.69%  |
| AuthenTec                          | 28        | 9.09%   |
| Upek                               | 13        | 4.22%   |
| Elan Microelectronics              | 13        | 4.22%   |
| LighTuning Technology              | 7         | 2.27%   |
| STMicroelectronics                 | 1         | 0.32%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.32%   |
| Microsoft                          | 1         | 0.32%   |
| Dell                               | 1         | 0.32%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 30        | 9.74%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 26        | 8.44%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 20        | 6.49%   |
| Shenzhen Goodix  FingerPrint Device                                        | 18        | 5.84%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 15        | 4.87%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 13        | 4.22%   |
| Synaptics Fingerprint reader [HP G6]                                       | 13        | 4.22%   |
| Shenzhen Goodix Fingerprint Reader                                         | 12        | 3.9%    |
| AuthenTec AES2810                                                          | 11        | 3.57%   |
| Validity Sensors VFS491                                                    | 10        | 3.25%   |
| Validity Sensors Synaptics WBDI                                            | 10        | 3.25%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 10        | 3.25%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 10        | 3.25%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 9         | 2.92%   |
| Elan ELAN:Fingerprint                                                      | 9         | 2.92%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 9         | 2.92%   |
| AuthenTec AES1600                                                          | 7         | 2.27%   |
| Synaptics UWP WBDI                                                         | 6         | 1.95%   |
| Shenzhen Goodix FingerPrint                                                | 6         | 1.95%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 6         | 1.95%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 1.62%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 5         | 1.62%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 5         | 1.62%   |
| Synaptics WBDI                                                             | 4         | 1.3%    |
| Synaptics  WBDI                                                            | 4         | 1.3%    |
| Elan ELAN:ARM-M4                                                           | 4         | 1.3%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 0.97%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 3         | 0.97%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 0.97%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 0.97%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 3         | 0.97%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 0.65%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 0.65%   |
| Synaptics UWP WBDI Device                                                  | 2         | 0.65%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.32%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.32%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 1         | 0.32%   |
| Synaptics WBDI Device                                                      | 1         | 0.32%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.32%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 0.32%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 64        | 49.61%  |
| Alcor Micro               | 40        | 31.01%  |
| O2 Micro                  | 9         | 6.98%   |
| Lenovo                    | 5         | 3.88%   |
| Upek                      | 2         | 1.55%   |
| SCM Microsystems          | 2         | 1.55%   |
| Realtek Semiconductor     | 2         | 1.55%   |
| Aladdin Knowledge Systems | 2         | 1.55%   |
| Purism, SPC               | 1         | 0.78%   |
| OmniKey                   | 1         | 0.78%   |
| Fujitsu Siemens Computers | 1         | 0.78%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 40        | 31.01%  |
| Broadcom 58200                                                               | 22        | 17.05%  |
| Broadcom BCM5880 Secure Applications Processor                               | 15        | 11.63%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 14        | 10.85%  |
| Broadcom 5880                                                                | 13        | 10.08%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 8         | 6.2%    |
| Lenovo Integrated Smart Card Reader                                          | 5         | 3.88%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 1.55%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 1.55%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 1.55%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 1.55%   |
| Purism, SPC Librem Key                                                       | 1         | 0.78%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.78%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.78%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.78%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1402      | 67.73%  |
| 1     | 506       | 24.44%  |
| 2     | 130       | 6.28%   |
| 3     | 24        | 1.16%   |
| 4     | 5         | 0.24%   |
| 5     | 3         | 0.14%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 302       | 36%     |
| Graphics card            | 171       | 20.38%  |
| Chipcard                 | 111       | 13.23%  |
| Net/wireless             | 59        | 7.03%   |
| Multimedia controller    | 47        | 5.6%    |
| Camera                   | 23        | 2.74%   |
| Communication controller | 22        | 2.62%   |
| Storage                  | 21        | 2.5%    |
| Bluetooth                | 20        | 2.38%   |
| Unassigned class         | 12        | 1.43%   |
| Card reader              | 10        | 1.19%   |
| Net/ethernet             | 9         | 1.07%   |
| Sound                    | 8         | 0.95%   |
| Flash memory             | 7         | 0.83%   |
| Modem                    | 6         | 0.72%   |
| Network                  | 4         | 0.48%   |
| Storage/ata              | 2         | 0.24%   |
| Dvb card                 | 2         | 0.24%   |
| Tv card                  | 1         | 0.12%   |
| Storage/raid             | 1         | 0.12%   |
| Storage/ide              | 1         | 0.12%   |

