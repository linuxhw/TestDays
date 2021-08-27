Debian 11 - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Debian 11 (Beta test).

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=debian-11

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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T440p 20AN006GU... | [bca7704bb0](https://linux-hardware.org/?probe=bca7704bb0) | Aug 27, 2021 |
| Apple         | MacBookAir7,2               | [14747d88b3](https://linux-hardware.org/?probe=14747d88b3) | Aug 26, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [87904cbe92](https://linux-hardware.org/?probe=87904cbe92) | Aug 26, 2021 |
| Apple         | MacBookAir7,2               | [1c2e910793](https://linux-hardware.org/?probe=1c2e910793) | Aug 26, 2021 |
| Apple         | MacBookAir7,1               | [4a69118897](https://linux-hardware.org/?probe=4a69118897) | Aug 26, 2021 |
| Apple         | MacBookAir7,1               | [474216fba9](https://linux-hardware.org/?probe=474216fba9) | Aug 26, 2021 |
| Apple         | MacBookAir7,2               | [76d9383f33](https://linux-hardware.org/?probe=76d9383f33) | Aug 26, 2021 |
| Apple         | MacBookAir7,2               | [213d3f817b](https://linux-hardware.org/?probe=213d3f817b) | Aug 26, 2021 |
| YJKC          | vBOOK Plus RVP7             | [8c051a0ce9](https://linux-hardware.org/?probe=8c051a0ce9) | Aug 26, 2021 |
| Gigabyte      | AORUS 15G KB                | [6afefe68d7](https://linux-hardware.org/?probe=6afefe68d7) | Aug 26, 2021 |
| HP            | ProBook 4530s               | [2b4cab4d7c](https://linux-hardware.org/?probe=2b4cab4d7c) | Aug 25, 2021 |
| Dell          | Inspiron 3537               | [7bab6dd9db](https://linux-hardware.org/?probe=7bab6dd9db) | Aug 25, 2021 |
| HP            | ProBook 450 G7              | [a2f161dee0](https://linux-hardware.org/?probe=a2f161dee0) | Aug 25, 2021 |
| HUAWEI        | WRT-WX9                     | [e1e5a14c77](https://linux-hardware.org/?probe=e1e5a14c77) | Aug 25, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [3da8591ac6](https://linux-hardware.org/?probe=3da8591ac6) | Aug 25, 2021 |
| HP            | 630                         | [004d2b364d](https://linux-hardware.org/?probe=004d2b364d) | Aug 25, 2021 |
| Dell          | Latitude 7490               | [23ad45f1fd](https://linux-hardware.org/?probe=23ad45f1fd) | Aug 25, 2021 |
| Apple         | MacBookAir7,2               | [65d82bc8e7](https://linux-hardware.org/?probe=65d82bc8e7) | Aug 24, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [e1bd0ec7fd](https://linux-hardware.org/?probe=e1bd0ec7fd) | Aug 24, 2021 |
| Apple         | MacBookAir7,2               | [8a72f87e7b](https://linux-hardware.org/?probe=8a72f87e7b) | Aug 24, 2021 |
| Apple         | MacBookAir7,1               | [1f257714a9](https://linux-hardware.org/?probe=1f257714a9) | Aug 24, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [102aea0211](https://linux-hardware.org/?probe=102aea0211) | Aug 24, 2021 |
| HP            | Laptop 15s-fq2xxx           | [f755838fd8](https://linux-hardware.org/?probe=f755838fd8) | Aug 24, 2021 |
| Apple         | MacBookAir7,2               | [5cc74103a8](https://linux-hardware.org/?probe=5cc74103a8) | Aug 24, 2021 |
| HP            | 250 G4                      | [5d47aa9804](https://linux-hardware.org/?probe=5d47aa9804) | Aug 24, 2021 |
| ASUSTek       | UX430UAR                    | [77ce457de4](https://linux-hardware.org/?probe=77ce457de4) | Aug 24, 2021 |
| HP            | Laptop 14-cm0xxx            | [df0fa8e968](https://linux-hardware.org/?probe=df0fa8e968) | Aug 24, 2021 |
| Sony          | VPCF115FM                   | [9f9abf79b2](https://linux-hardware.org/?probe=9f9abf79b2) | Aug 23, 2021 |
| Apple         | MacBookAir7,2               | [8a88eabb1c](https://linux-hardware.org/?probe=8a88eabb1c) | Aug 23, 2021 |
| Apple         | MacBookAir7,2               | [c4ecd51a21](https://linux-hardware.org/?probe=c4ecd51a21) | Aug 23, 2021 |
| HP            | Laptop 15s-eq2xxx           | [1c9d3bb8b4](https://linux-hardware.org/?probe=1c9d3bb8b4) | Aug 23, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [45ec27282a](https://linux-hardware.org/?probe=45ec27282a) | Aug 23, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | [14af647cc5](https://linux-hardware.org/?probe=14af647cc5) | Aug 23, 2021 |
| Apple         | MacBookAir7,2               | [5bc9372587](https://linux-hardware.org/?probe=5bc9372587) | Aug 23, 2021 |
| Apple         | MacBookAir7,2               | [8bcb9e62e1](https://linux-hardware.org/?probe=8bcb9e62e1) | Aug 23, 2021 |
| Apple         | MacBookAir7,2               | [6c44c4f7e3](https://linux-hardware.org/?probe=6c44c4f7e3) | Aug 23, 2021 |
| Google        | Enguarde                    | [12a2003770](https://linux-hardware.org/?probe=12a2003770) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [7f190e4ed2](https://linux-hardware.org/?probe=7f190e4ed2) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [2db5cafda3](https://linux-hardware.org/?probe=2db5cafda3) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [abcab36e0c](https://linux-hardware.org/?probe=abcab36e0c) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [f3ccb91568](https://linux-hardware.org/?probe=f3ccb91568) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [0d8fa16f47](https://linux-hardware.org/?probe=0d8fa16f47) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [680e8106ec](https://linux-hardware.org/?probe=680e8106ec) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [c18b0215e9](https://linux-hardware.org/?probe=c18b0215e9) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [fcc821b941](https://linux-hardware.org/?probe=fcc821b941) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [59f760dbb9](https://linux-hardware.org/?probe=59f760dbb9) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [e22a8e2ea4](https://linux-hardware.org/?probe=e22a8e2ea4) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [4fc69342da](https://linux-hardware.org/?probe=4fc69342da) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [f2fcae5696](https://linux-hardware.org/?probe=f2fcae5696) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [2f823b2f52](https://linux-hardware.org/?probe=2f823b2f52) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [adf5b71331](https://linux-hardware.org/?probe=adf5b71331) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [618c1c7838](https://linux-hardware.org/?probe=618c1c7838) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [0dff1056d5](https://linux-hardware.org/?probe=0dff1056d5) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [fb0cf0a7a3](https://linux-hardware.org/?probe=fb0cf0a7a3) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [6b9f550210](https://linux-hardware.org/?probe=6b9f550210) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [4b22440e91](https://linux-hardware.org/?probe=4b22440e91) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [6bab7cdc7c](https://linux-hardware.org/?probe=6bab7cdc7c) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [d2a08022bd](https://linux-hardware.org/?probe=d2a08022bd) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [f39d94cf1b](https://linux-hardware.org/?probe=f39d94cf1b) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [e35bbfda2d](https://linux-hardware.org/?probe=e35bbfda2d) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [60170675ca](https://linux-hardware.org/?probe=60170675ca) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [64a6aa27db](https://linux-hardware.org/?probe=64a6aa27db) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [06b1dab7a0](https://linux-hardware.org/?probe=06b1dab7a0) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [cec5c36945](https://linux-hardware.org/?probe=cec5c36945) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [6f38e35f9a](https://linux-hardware.org/?probe=6f38e35f9a) | Aug 23, 2021 |
| HP            | EliteBook 840 G4            | [ebe40b3244](https://linux-hardware.org/?probe=ebe40b3244) | Aug 22, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [d98bdb0d1c](https://linux-hardware.org/?probe=d98bdb0d1c) | Aug 22, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [d688bffa01](https://linux-hardware.org/?probe=d688bffa01) | Aug 22, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [3d52884b6e](https://linux-hardware.org/?probe=3d52884b6e) | Aug 22, 2021 |
| ASUSTek       | G771JM                      | [57b847b12c](https://linux-hardware.org/?probe=57b847b12c) | Aug 22, 2021 |
| ASUSTek       | G771JM                      | [db4b9878fa](https://linux-hardware.org/?probe=db4b9878fa) | Aug 22, 2021 |
| Dell          | Inspiron 6000               | [67c6b36361](https://linux-hardware.org/?probe=67c6b36361) | Aug 22, 2021 |
| Dell          | Inspiron 3593               | [dfed5d8b7a](https://linux-hardware.org/?probe=dfed5d8b7a) | Aug 21, 2021 |
| Dell          | Latitude E7470              | [e954672cb2](https://linux-hardware.org/?probe=e954672cb2) | Aug 21, 2021 |
| Lenovo        | IdeaPad Y500 20193          | [5b2d90a434](https://linux-hardware.org/?probe=5b2d90a434) | Aug 21, 2021 |
| HP            | 14s-dq2003nw                | [f4dcd70da5](https://linux-hardware.org/?probe=f4dcd70da5) | Aug 21, 2021 |
| Lenovo        | ThinkPad E570 20H500B4GE    | [be964b556b](https://linux-hardware.org/?probe=be964b556b) | Aug 21, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [5ecdc39ac1](https://linux-hardware.org/?probe=5ecdc39ac1) | Aug 21, 2021 |
| Dell          | Precision 7520              | [372d627a69](https://linux-hardware.org/?probe=372d627a69) | Aug 21, 2021 |
| Apple         | MacBookAir7,1               | [daa01f79aa](https://linux-hardware.org/?probe=daa01f79aa) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | [a96a7ada4f](https://linux-hardware.org/?probe=a96a7ada4f) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | [c8305c0d4c](https://linux-hardware.org/?probe=c8305c0d4c) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | [77359352d0](https://linux-hardware.org/?probe=77359352d0) | Aug 20, 2021 |
| Apple         | MacBookAir7,2               | [5312257240](https://linux-hardware.org/?probe=5312257240) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | [75e262ddba](https://linux-hardware.org/?probe=75e262ddba) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | [bd216572a3](https://linux-hardware.org/?probe=bd216572a3) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | [e57aeadfef](https://linux-hardware.org/?probe=e57aeadfef) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | [7211565d4a](https://linux-hardware.org/?probe=7211565d4a) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | [1c490522df](https://linux-hardware.org/?probe=1c490522df) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | [16f0b9c14a](https://linux-hardware.org/?probe=16f0b9c14a) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | [691bb379e5](https://linux-hardware.org/?probe=691bb379e5) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | [fe880ac0c8](https://linux-hardware.org/?probe=fe880ac0c8) | Aug 20, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [a5a146e42a](https://linux-hardware.org/?probe=a5a146e42a) | Aug 20, 2021 |
| Apple         | MacBookAir7,2               | [c60ef3fa1e](https://linux-hardware.org/?probe=c60ef3fa1e) | Aug 20, 2021 |
| Timi          | TM1612                      | [485caf5846](https://linux-hardware.org/?probe=485caf5846) | Aug 20, 2021 |
| Lenovo        | V510-15IKB 80WQ             | [2a61705899](https://linux-hardware.org/?probe=2a61705899) | Aug 20, 2021 |
| SLIMBOOK      | TITAN                       | [a2abd981d1](https://linux-hardware.org/?probe=a2abd981d1) | Aug 19, 2021 |
| Apple         | MacBookAir7,2               | [1ce6738560](https://linux-hardware.org/?probe=1ce6738560) | Aug 19, 2021 |
| Apple         | MacBookAir7,2               | [e134a1f7c3](https://linux-hardware.org/?probe=e134a1f7c3) | Aug 19, 2021 |
| Apple         | MacBookAir7,2               | [87fa430aab](https://linux-hardware.org/?probe=87fa430aab) | Aug 19, 2021 |
| Apple         | MacBookAir7,2               | [c989eac16b](https://linux-hardware.org/?probe=c989eac16b) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [3169e477dd](https://linux-hardware.org/?probe=3169e477dd) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [5fcb7fdb26](https://linux-hardware.org/?probe=5fcb7fdb26) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [7afbba35b0](https://linux-hardware.org/?probe=7afbba35b0) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [f1d159bbd1](https://linux-hardware.org/?probe=f1d159bbd1) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [38e8211556](https://linux-hardware.org/?probe=38e8211556) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [bd587e5998](https://linux-hardware.org/?probe=bd587e5998) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [3fa54711ec](https://linux-hardware.org/?probe=3fa54711ec) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [4a7f287161](https://linux-hardware.org/?probe=4a7f287161) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [fed5f28778](https://linux-hardware.org/?probe=fed5f28778) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [0ba8599928](https://linux-hardware.org/?probe=0ba8599928) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [e31d43b39d](https://linux-hardware.org/?probe=e31d43b39d) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [703cdcf766](https://linux-hardware.org/?probe=703cdcf766) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [9b8ce55c3d](https://linux-hardware.org/?probe=9b8ce55c3d) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [2b4af51f46](https://linux-hardware.org/?probe=2b4af51f46) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [b802b4a25b](https://linux-hardware.org/?probe=b802b4a25b) | Aug 18, 2021 |
| Google        | Enguarde                    | [cb421b796b](https://linux-hardware.org/?probe=cb421b796b) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [f6c7230675](https://linux-hardware.org/?probe=f6c7230675) | Aug 18, 2021 |
| Google        | Enguarde                    | [7116839a4b](https://linux-hardware.org/?probe=7116839a4b) | Aug 18, 2021 |
| Google        | Enguarde                    | [04817bfb7f](https://linux-hardware.org/?probe=04817bfb7f) | Aug 18, 2021 |
| Google        | Enguarde                    | [92b401a705](https://linux-hardware.org/?probe=92b401a705) | Aug 18, 2021 |
| Google        | Enguarde                    | [f2a438a9be](https://linux-hardware.org/?probe=f2a438a9be) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [c9239b499b](https://linux-hardware.org/?probe=c9239b499b) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [b708a97ef1](https://linux-hardware.org/?probe=b708a97ef1) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [31dc792a8b](https://linux-hardware.org/?probe=31dc792a8b) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [76a48b344d](https://linux-hardware.org/?probe=76a48b344d) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [244aba47d4](https://linux-hardware.org/?probe=244aba47d4) | Aug 18, 2021 |
| Google        | Enguarde                    | [b2391216c6](https://linux-hardware.org/?probe=b2391216c6) | Aug 18, 2021 |
| Google        | Enguarde                    | [53b311c24c](https://linux-hardware.org/?probe=53b311c24c) | Aug 18, 2021 |
| Google        | Enguarde                    | [61de56951c](https://linux-hardware.org/?probe=61de56951c) | Aug 18, 2021 |
| Google        | Enguarde                    | [7fd7f1ea77](https://linux-hardware.org/?probe=7fd7f1ea77) | Aug 18, 2021 |
| Google        | Enguarde                    | [2a090f8b2a](https://linux-hardware.org/?probe=2a090f8b2a) | Aug 18, 2021 |
| Google        | Enguarde                    | [62e4ff915a](https://linux-hardware.org/?probe=62e4ff915a) | Aug 18, 2021 |
| Google        | Enguarde                    | [eada085a33](https://linux-hardware.org/?probe=eada085a33) | Aug 18, 2021 |
| Google        | Enguarde                    | [474e20b9f2](https://linux-hardware.org/?probe=474e20b9f2) | Aug 18, 2021 |
| ASUSTek       | UX305CA                     | [6ab6beca67](https://linux-hardware.org/?probe=6ab6beca67) | Aug 18, 2021 |
| HP            | EliteBook 820 G1            | [c7155dfa07](https://linux-hardware.org/?probe=c7155dfa07) | Aug 18, 2021 |
| Google        | Enguarde                    | [dd0de8b832](https://linux-hardware.org/?probe=dd0de8b832) | Aug 17, 2021 |
| Google        | Enguarde                    | [a6ac2782a6](https://linux-hardware.org/?probe=a6ac2782a6) | Aug 17, 2021 |
| Google        | Enguarde                    | [d32e974941](https://linux-hardware.org/?probe=d32e974941) | Aug 17, 2021 |
| Google        | Enguarde                    | [fe90c1da98](https://linux-hardware.org/?probe=fe90c1da98) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [c3d98780bf](https://linux-hardware.org/?probe=c3d98780bf) | Aug 17, 2021 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [4b38b9e598](https://linux-hardware.org/?probe=4b38b9e598) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [2c30321150](https://linux-hardware.org/?probe=2c30321150) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [2f6317ebc5](https://linux-hardware.org/?probe=2f6317ebc5) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [707606ff5e](https://linux-hardware.org/?probe=707606ff5e) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [0c43bb89c0](https://linux-hardware.org/?probe=0c43bb89c0) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [fcb540b848](https://linux-hardware.org/?probe=fcb540b848) | Aug 17, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [46240d5ef9](https://linux-hardware.org/?probe=46240d5ef9) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [6e85db6058](https://linux-hardware.org/?probe=6e85db6058) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [2e26440865](https://linux-hardware.org/?probe=2e26440865) | Aug 17, 2021 |
| Apple         | MacBook7,1                  | [5ad65197ad](https://linux-hardware.org/?probe=5ad65197ad) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [c185e120f1](https://linux-hardware.org/?probe=c185e120f1) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [ee22c0dcc0](https://linux-hardware.org/?probe=ee22c0dcc0) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [b3fd5bee39](https://linux-hardware.org/?probe=b3fd5bee39) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [d68e571cd0](https://linux-hardware.org/?probe=d68e571cd0) | Aug 17, 2021 |
| Dell          | Latitude 7480               | [49272ed382](https://linux-hardware.org/?probe=49272ed382) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [28c2f85e9c](https://linux-hardware.org/?probe=28c2f85e9c) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [1f8c3f9487](https://linux-hardware.org/?probe=1f8c3f9487) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [9f6a737d07](https://linux-hardware.org/?probe=9f6a737d07) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [4eb4afec6b](https://linux-hardware.org/?probe=4eb4afec6b) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [5949002919](https://linux-hardware.org/?probe=5949002919) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [b0d4ba09f6](https://linux-hardware.org/?probe=b0d4ba09f6) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [12377bdf65](https://linux-hardware.org/?probe=12377bdf65) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [f345284082](https://linux-hardware.org/?probe=f345284082) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [6229638b59](https://linux-hardware.org/?probe=6229638b59) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [b95e1787ff](https://linux-hardware.org/?probe=b95e1787ff) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [f1d344625b](https://linux-hardware.org/?probe=f1d344625b) | Aug 17, 2021 |
| Google        | Enguarde                    | [4d7eaa38ba](https://linux-hardware.org/?probe=4d7eaa38ba) | Aug 17, 2021 |
| Google        | Enguarde                    | [8be28c3080](https://linux-hardware.org/?probe=8be28c3080) | Aug 17, 2021 |
| Lenovo        | ThinkPad X230 2325AT6       | [9e66245080](https://linux-hardware.org/?probe=9e66245080) | Aug 17, 2021 |
| Google        | Enguarde                    | [cfdf77fbd9](https://linux-hardware.org/?probe=cfdf77fbd9) | Aug 17, 2021 |
| Google        | Enguarde                    | [6e84dfb541](https://linux-hardware.org/?probe=6e84dfb541) | Aug 17, 2021 |
| Google        | Enguarde                    | [2549683d9f](https://linux-hardware.org/?probe=2549683d9f) | Aug 17, 2021 |
| Dell          | Latitude 7410               | [f7f6e5a4d5](https://linux-hardware.org/?probe=f7f6e5a4d5) | Aug 17, 2021 |
| ASUSTek       | 1225B                       | [1dd6877b22](https://linux-hardware.org/?probe=1dd6877b22) | Aug 17, 2021 |
| Google        | Enguarde                    | [0bdebdb178](https://linux-hardware.org/?probe=0bdebdb178) | Aug 16, 2021 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [3a489f9498](https://linux-hardware.org/?probe=3a489f9498) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [635d3ab3e5](https://linux-hardware.org/?probe=635d3ab3e5) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | [2e04ae93d1](https://linux-hardware.org/?probe=2e04ae93d1) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | [dffcb4d4f6](https://linux-hardware.org/?probe=dffcb4d4f6) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | [e3816a3d3a](https://linux-hardware.org/?probe=e3816a3d3a) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [d76cf98938](https://linux-hardware.org/?probe=d76cf98938) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [fc7b752ce3](https://linux-hardware.org/?probe=fc7b752ce3) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | [346d3ca919](https://linux-hardware.org/?probe=346d3ca919) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | [eb7cdde4b5](https://linux-hardware.org/?probe=eb7cdde4b5) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [ae1b239645](https://linux-hardware.org/?probe=ae1b239645) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [d7e9112089](https://linux-hardware.org/?probe=d7e9112089) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [35ab4c3075](https://linux-hardware.org/?probe=35ab4c3075) | Aug 16, 2021 |
| Lenovo        | ThinkPad E490 20N8001EUS    | [40796d62c2](https://linux-hardware.org/?probe=40796d62c2) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [1fa30fb77a](https://linux-hardware.org/?probe=1fa30fb77a) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [81f2a65461](https://linux-hardware.org/?probe=81f2a65461) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | [a54d2e496c](https://linux-hardware.org/?probe=a54d2e496c) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [d0581c16e9](https://linux-hardware.org/?probe=d0581c16e9) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [4704dd7dc2](https://linux-hardware.org/?probe=4704dd7dc2) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | [2d48e28c72](https://linux-hardware.org/?probe=2d48e28c72) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | [dcded26792](https://linux-hardware.org/?probe=dcded26792) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [de06f0cb03](https://linux-hardware.org/?probe=de06f0cb03) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [3171a06ab2](https://linux-hardware.org/?probe=3171a06ab2) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | [154d3f4aac](https://linux-hardware.org/?probe=154d3f4aac) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 20J10046US      | [6943b835e5](https://linux-hardware.org/?probe=6943b835e5) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [56e2f75dab](https://linux-hardware.org/?probe=56e2f75dab) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [7e070c3cee](https://linux-hardware.org/?probe=7e070c3cee) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [be42bbb09a](https://linux-hardware.org/?probe=be42bbb09a) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | [42a5d4fb48](https://linux-hardware.org/?probe=42a5d4fb48) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [845219864e](https://linux-hardware.org/?probe=845219864e) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [99531c5564](https://linux-hardware.org/?probe=99531c5564) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [7e2e8d1364](https://linux-hardware.org/?probe=7e2e8d1364) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [c9b0773c42](https://linux-hardware.org/?probe=c9b0773c42) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [947e3524e3](https://linux-hardware.org/?probe=947e3524e3) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [a30c87c3fe](https://linux-hardware.org/?probe=a30c87c3fe) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [edaac7af9f](https://linux-hardware.org/?probe=edaac7af9f) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [94047a5fdc](https://linux-hardware.org/?probe=94047a5fdc) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [ccd9ef4a72](https://linux-hardware.org/?probe=ccd9ef4a72) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [97aab17694](https://linux-hardware.org/?probe=97aab17694) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [3112135337](https://linux-hardware.org/?probe=3112135337) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [8da303b571](https://linux-hardware.org/?probe=8da303b571) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [449ea4adf6](https://linux-hardware.org/?probe=449ea4adf6) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [5bd9662328](https://linux-hardware.org/?probe=5bd9662328) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | [079ef9affe](https://linux-hardware.org/?probe=079ef9affe) | Aug 16, 2021 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [9e81b88eb8](https://linux-hardware.org/?probe=9e81b88eb8) | Aug 16, 2021 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [7b614dd679](https://linux-hardware.org/?probe=7b614dd679) | Aug 16, 2021 |
| Acer          | Swift SF114-33              | [2cd1a890fa](https://linux-hardware.org/?probe=2cd1a890fa) | Aug 16, 2021 |
| Dell          | G3 3590                     | [05e11ad38d](https://linux-hardware.org/?probe=05e11ad38d) | Aug 16, 2021 |
| HP            | 630                         | [a57ed15001](https://linux-hardware.org/?probe=a57ed15001) | Aug 15, 2021 |
| HP            | Laptop 15s-eq1xxx           | [31fcb375f4](https://linux-hardware.org/?probe=31fcb375f4) | Aug 15, 2021 |
| Lenovo        | ThinkPad S1 Yoga 20C0S0X... | [e3fd79d228](https://linux-hardware.org/?probe=e3fd79d228) | Aug 15, 2021 |
| Apple         | MacBookPro11,3              | [daf1b7a963](https://linux-hardware.org/?probe=daf1b7a963) | Aug 15, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [0b7f4b2da5](https://linux-hardware.org/?probe=0b7f4b2da5) | Aug 15, 2021 |
| Apple         | MacBookPro11,3              | [f6b6388040](https://linux-hardware.org/?probe=f6b6388040) | Aug 14, 2021 |
| HP            | Compaq nc6320 (EV073AV)     | [bf6050f750](https://linux-hardware.org/?probe=bf6050f750) | Aug 14, 2021 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | [f3506aaa1c](https://linux-hardware.org/?probe=f3506aaa1c) | Aug 14, 2021 |
| Dell          | Latitude 7490               | [6ca174eba8](https://linux-hardware.org/?probe=6ca174eba8) | Aug 14, 2021 |
| Dell          | Latitude 7490               | [85cacfa170](https://linux-hardware.org/?probe=85cacfa170) | Aug 13, 2021 |
| Google        | Enguarde                    | [cac72ff077](https://linux-hardware.org/?probe=cac72ff077) | Aug 13, 2021 |
| Google        | Enguarde                    | [8c489e2c59](https://linux-hardware.org/?probe=8c489e2c59) | Aug 13, 2021 |
| Google        | Enguarde                    | [d79905590c](https://linux-hardware.org/?probe=d79905590c) | Aug 13, 2021 |
| Google        | Enguarde                    | [7efce8d06b](https://linux-hardware.org/?probe=7efce8d06b) | Aug 13, 2021 |
| Google        | Enguarde                    | [c53a0803e7](https://linux-hardware.org/?probe=c53a0803e7) | Aug 13, 2021 |
| Google        | Enguarde                    | [410a4b2e26](https://linux-hardware.org/?probe=410a4b2e26) | Aug 13, 2021 |
| Google        | Enguarde                    | [cbc9f75923](https://linux-hardware.org/?probe=cbc9f75923) | Aug 13, 2021 |
| Google        | Enguarde                    | [4ca322af56](https://linux-hardware.org/?probe=4ca322af56) | Aug 13, 2021 |
| Google        | Enguarde                    | [2af4090c36](https://linux-hardware.org/?probe=2af4090c36) | Aug 13, 2021 |
| Google        | Enguarde                    | [43919a91f3](https://linux-hardware.org/?probe=43919a91f3) | Aug 12, 2021 |
| Google        | Enguarde                    | [c93dcd9531](https://linux-hardware.org/?probe=c93dcd9531) | Aug 12, 2021 |
| Google        | Enguarde                    | [8e7147d832](https://linux-hardware.org/?probe=8e7147d832) | Aug 12, 2021 |
| Apple         | MacBookAir7,1               | [65a4eb9f2c](https://linux-hardware.org/?probe=65a4eb9f2c) | Aug 12, 2021 |
| Google        | Enguarde                    | [e9f95dc0ed](https://linux-hardware.org/?probe=e9f95dc0ed) | Aug 12, 2021 |
| Google        | Enguarde                    | [3b5b9d1698](https://linux-hardware.org/?probe=3b5b9d1698) | Aug 12, 2021 |
| Google        | Enguarde                    | [e423d1eee6](https://linux-hardware.org/?probe=e423d1eee6) | Aug 12, 2021 |
| Google        | Enguarde                    | [1f00600e9b](https://linux-hardware.org/?probe=1f00600e9b) | Aug 12, 2021 |
| Google        | Enguarde                    | [88adc88ccd](https://linux-hardware.org/?probe=88adc88ccd) | Aug 12, 2021 |
| Notebook      | NL4x_NL5xLU                 | [82a8b9c657](https://linux-hardware.org/?probe=82a8b9c657) | Aug 12, 2021 |
| Google        | Enguarde                    | [2434eac448](https://linux-hardware.org/?probe=2434eac448) | Aug 12, 2021 |
| Google        | Enguarde                    | [d766910df0](https://linux-hardware.org/?probe=d766910df0) | Aug 12, 2021 |
| Google        | Enguarde                    | [c0516ce965](https://linux-hardware.org/?probe=c0516ce965) | Aug 12, 2021 |
| Google        | Enguarde                    | [728007c621](https://linux-hardware.org/?probe=728007c621) | Aug 12, 2021 |
| Google        | Enguarde                    | [b808ac5856](https://linux-hardware.org/?probe=b808ac5856) | Aug 12, 2021 |
| Google        | Enguarde                    | [326cc3aae3](https://linux-hardware.org/?probe=326cc3aae3) | Aug 12, 2021 |
| Google        | Enguarde                    | [1fddcb2525](https://linux-hardware.org/?probe=1fddcb2525) | Aug 12, 2021 |
| Lenovo        | ThinkPad T440s 20AR0011M... | [df7a1d9358](https://linux-hardware.org/?probe=df7a1d9358) | Aug 12, 2021 |
| Lenovo        | V14 G2 ITL 82KA             | [2bc14051d8](https://linux-hardware.org/?probe=2bc14051d8) | Aug 12, 2021 |
| Lenovo        | ThinkPad X250 20CM001RMS    | [d0dfc1011e](https://linux-hardware.org/?probe=d0dfc1011e) | Aug 12, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [cbe8c5170f](https://linux-hardware.org/?probe=cbe8c5170f) | Aug 12, 2021 |
| HP            | ProBook 4530s               | [14a78c65a1](https://linux-hardware.org/?probe=14a78c65a1) | Aug 12, 2021 |
| Lenovo        | ThinkPad X250 20CLS4WV08    | [2c09cdd5bd](https://linux-hardware.org/?probe=2c09cdd5bd) | Aug 12, 2021 |
| Samsung       | 300E5M/300E5L               | [4139a3a855](https://linux-hardware.org/?probe=4139a3a855) | Aug 11, 2021 |
| Notebook      | N13_N140ZU                  | [cbaecf1d3e](https://linux-hardware.org/?probe=cbaecf1d3e) | Aug 11, 2021 |
| Samsung       | 300E5M/300E5L               | [48573ed425](https://linux-hardware.org/?probe=48573ed425) | Aug 11, 2021 |
| HP            | ENVY Laptop 13-ad1xx        | [4d023d9be2](https://linux-hardware.org/?probe=4d023d9be2) | Aug 11, 2021 |
| HP            | ENVY Laptop 13-ad1xx        | [927a3673b9](https://linux-hardware.org/?probe=927a3673b9) | Aug 11, 2021 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [cabe0ebbc8](https://linux-hardware.org/?probe=cabe0ebbc8) | Aug 10, 2021 |
| Apple         | MacBookAir7,2               | [1dcbf85471](https://linux-hardware.org/?probe=1dcbf85471) | Aug 10, 2021 |
| Apple         | MacBookAir7,2               | [0c67490330](https://linux-hardware.org/?probe=0c67490330) | Aug 10, 2021 |
| Dell          | Precision 3551              | [da8459ac73](https://linux-hardware.org/?probe=da8459ac73) | Aug 10, 2021 |
| HP            | 250 G4                      | [5640b0689d](https://linux-hardware.org/?probe=5640b0689d) | Aug 10, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [d650ff0c3e](https://linux-hardware.org/?probe=d650ff0c3e) | Aug 10, 2021 |
| HP            | Laptop 15s-eq1xxx           | [4ce98656a4](https://linux-hardware.org/?probe=4ce98656a4) | Aug 10, 2021 |
| Dell          | Inspiron ME051              | [5ca4e6101b](https://linux-hardware.org/?probe=5ca4e6101b) | Aug 10, 2021 |
| Lenovo        | B51-35 80LH                 | [5f87168a65](https://linux-hardware.org/?probe=5f87168a65) | Aug 10, 2021 |
| Apple         | MacBookAir7,1               | [6ab68482c0](https://linux-hardware.org/?probe=6ab68482c0) | Aug 09, 2021 |
| Lenovo        | ThinkPad T470s 20HGS3R80... | [fbc29e2063](https://linux-hardware.org/?probe=fbc29e2063) | Aug 09, 2021 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [e4ce236efd](https://linux-hardware.org/?probe=e4ce236efd) | Aug 09, 2021 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [1c26f935e6](https://linux-hardware.org/?probe=1c26f935e6) | Aug 09, 2021 |
| HP            | Pavilion Laptop 15-cw0xx... | [538a15f3cc](https://linux-hardware.org/?probe=538a15f3cc) | Aug 09, 2021 |
| HP            | 2000                        | [73e2b73533](https://linux-hardware.org/?probe=73e2b73533) | Aug 09, 2021 |
| Lenovo        | ThinkPad T580 20L9001AUS    | [65e201224c](https://linux-hardware.org/?probe=65e201224c) | Aug 09, 2021 |
| MSI           | GP60 2PE                    | [516f3cd4e5](https://linux-hardware.org/?probe=516f3cd4e5) | Aug 09, 2021 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [64784dd9c7](https://linux-hardware.org/?probe=64784dd9c7) | Aug 09, 2021 |
| Lenovo        | ThinkPad T410 2537E49       | [ea10aead92](https://linux-hardware.org/?probe=ea10aead92) | Aug 08, 2021 |
| Dell          | XPS 13 9370                 | [575a84d010](https://linux-hardware.org/?probe=575a84d010) | Aug 08, 2021 |
| Clevo         | W55xEU                      | [ee96e1ca32](https://linux-hardware.org/?probe=ee96e1ca32) | Aug 08, 2021 |
| Lenovo        | ThinkPad W500 406152G       | [b400f1bc46](https://linux-hardware.org/?probe=b400f1bc46) | Aug 08, 2021 |
| Acer          | TravelMate 5720             | [43aae04fa6](https://linux-hardware.org/?probe=43aae04fa6) | Aug 08, 2021 |
| Lenovo        | ThinkPad X230 23252FG       | [1c7914d660](https://linux-hardware.org/?probe=1c7914d660) | Aug 08, 2021 |
| HP            | Laptop 15s-fq2xxx           | [c5ef006a35](https://linux-hardware.org/?probe=c5ef006a35) | Aug 08, 2021 |
| Acer          | Swift SF314-51              | [88fa728376](https://linux-hardware.org/?probe=88fa728376) | Aug 07, 2021 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [e18202a558](https://linux-hardware.org/?probe=e18202a558) | Aug 07, 2021 |
| HP            | Laptop 15s-fq2xxx           | [a89cdf06f5](https://linux-hardware.org/?probe=a89cdf06f5) | Aug 07, 2021 |
| Samsung       | 900X3C/900X3D/900X3E/900... | [18d1628875](https://linux-hardware.org/?probe=18d1628875) | Aug 07, 2021 |
| Clevo         | P170EM                      | [f101b2b318](https://linux-hardware.org/?probe=f101b2b318) | Aug 07, 2021 |
| Acer          | Aspire E5-575               | [3caca4f238](https://linux-hardware.org/?probe=3caca4f238) | Aug 07, 2021 |
| Acer          | Aspire E5-571P              | [1dbaeef7d2](https://linux-hardware.org/?probe=1dbaeef7d2) | Aug 07, 2021 |
| Google        | Parrot                      | [2efb04c61c](https://linux-hardware.org/?probe=2efb04c61c) | Aug 07, 2021 |
| Lenovo        | ThinkPad T61 7661BK7        | [bbabc03a27](https://linux-hardware.org/?probe=bbabc03a27) | Aug 07, 2021 |
| Sony          | VPCF21AFX                   | [40aa5144f7](https://linux-hardware.org/?probe=40aa5144f7) | Aug 07, 2021 |
| Lenovo        | ThinkPad T450 20BUS16700    | [8123256638](https://linux-hardware.org/?probe=8123256638) | Aug 07, 2021 |
| Dell          | XPS 13 9350                 | [e82d4c3561](https://linux-hardware.org/?probe=e82d4c3561) | Aug 07, 2021 |
| HP            | Pavilion 15                 | [73f50567a1](https://linux-hardware.org/?probe=73f50567a1) | Aug 07, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [412f800d01](https://linux-hardware.org/?probe=412f800d01) | Aug 07, 2021 |
| Lenovo        | ThinkPad T550 20CK0002MZ    | [701a99b60f](https://linux-hardware.org/?probe=701a99b60f) | Aug 07, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [69696c0e3a](https://linux-hardware.org/?probe=69696c0e3a) | Aug 07, 2021 |
| Lenovo        | ThinkPad X200 7458B64       | [110a19b1b7](https://linux-hardware.org/?probe=110a19b1b7) | Aug 07, 2021 |
| Lenovo        | ThinkPad X240 20AMS0BU0T    | [f22b591a0a](https://linux-hardware.org/?probe=f22b591a0a) | Aug 07, 2021 |
| Lenovo        | ThinkPad T440s 20ARA1DJM... | [3d02d8b67f](https://linux-hardware.org/?probe=3d02d8b67f) | Aug 07, 2021 |
| HP            | 630                         | [b2d03b8717](https://linux-hardware.org/?probe=b2d03b8717) | Aug 07, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [368abe4066](https://linux-hardware.org/?probe=368abe4066) | Aug 07, 2021 |
| HP            | 630                         | [428ee9672e](https://linux-hardware.org/?probe=428ee9672e) | Aug 07, 2021 |
| Lenovo        | ThinkPad P17 Gen 1 20SNZ... | [669874ee19](https://linux-hardware.org/?probe=669874ee19) | Aug 07, 2021 |
| MSI           | GP60 2PE                    | [ad24cf2899](https://linux-hardware.org/?probe=ad24cf2899) | Aug 07, 2021 |
| MSI           | GP60 2PE                    | [9f994fc086](https://linux-hardware.org/?probe=9f994fc086) | Aug 07, 2021 |
| Apple         | MacBookAir7,1               | [e2b8c558f7](https://linux-hardware.org/?probe=e2b8c558f7) | Aug 06, 2021 |
| HP            | Compaq nx6125 (PZ849UA#A... | [8cc604abc2](https://linux-hardware.org/?probe=8cc604abc2) | Aug 06, 2021 |
| Apple         | MacBookAir7,2               | [c9c4b53460](https://linux-hardware.org/?probe=c9c4b53460) | Aug 06, 2021 |
| HP            | Compaq nx6110 (PZ065UA#A... | [f54c45ab89](https://linux-hardware.org/?probe=f54c45ab89) | Aug 06, 2021 |
| Apple         | MacBookAir7,2               | [81fef8f548](https://linux-hardware.org/?probe=81fef8f548) | Aug 06, 2021 |
| HP            | Compaq nx6125 (PZ849UA#A... | [4e000b3710](https://linux-hardware.org/?probe=4e000b3710) | Aug 06, 2021 |
| HP            | Compaq nx6110 (PZ065UA#A... | [493e2762bc](https://linux-hardware.org/?probe=493e2762bc) | Aug 06, 2021 |
| Apple         | MacBookAir7,2               | [2eb3a16b53](https://linux-hardware.org/?probe=2eb3a16b53) | Aug 06, 2021 |
| Dell          | Precision 3540              | [1b8206cd29](https://linux-hardware.org/?probe=1b8206cd29) | Aug 06, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | [10811e8109](https://linux-hardware.org/?probe=10811e8109) | Aug 06, 2021 |
| Apple         | MacBookAir7,2               | [bba0c0a13c](https://linux-hardware.org/?probe=bba0c0a13c) | Aug 06, 2021 |
| Apple         | MacBookAir7,1               | [25f1a5ecdf](https://linux-hardware.org/?probe=25f1a5ecdf) | Aug 06, 2021 |
| HP            | EliteBook 8460p             | [a7114078e2](https://linux-hardware.org/?probe=a7114078e2) | Aug 06, 2021 |
| Lenovo        | ThinkPad W520 4284CY1       | [5e1c9e9e30](https://linux-hardware.org/?probe=5e1c9e9e30) | Aug 06, 2021 |
| Apple         | MacBookAir7,1               | [639bb0ca17](https://linux-hardware.org/?probe=639bb0ca17) | Aug 06, 2021 |
| Dell          | G3 3579                     | [5a268dbc14](https://linux-hardware.org/?probe=5a268dbc14) | Aug 06, 2021 |
| Dell          | G3 3579                     | [6aae1a533f](https://linux-hardware.org/?probe=6aae1a533f) | Aug 06, 2021 |
| Apple         | MacBookAir7,1               | [41d352c625](https://linux-hardware.org/?probe=41d352c625) | Aug 06, 2021 |
| Acer          | Aspire 5315                 | [3256d646b0](https://linux-hardware.org/?probe=3256d646b0) | Aug 06, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | [f7718b0dfe](https://linux-hardware.org/?probe=f7718b0dfe) | Aug 06, 2021 |
| Dell          | Latitude E7240              | [4dd840f3dd](https://linux-hardware.org/?probe=4dd840f3dd) | Aug 06, 2021 |
| Acer          | Aspire 5315                 | [64b6992b74](https://linux-hardware.org/?probe=64b6992b74) | Aug 06, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [f8727e28db](https://linux-hardware.org/?probe=f8727e28db) | Aug 05, 2021 |
| Acer          | Aspire 5315                 | [249a58dd07](https://linux-hardware.org/?probe=249a58dd07) | Aug 05, 2021 |
| Apple         | MacBookAir7,2               | [fa1f3da353](https://linux-hardware.org/?probe=fa1f3da353) | Aug 05, 2021 |
| Acer          | Aspire 5315                 | [812e20e37e](https://linux-hardware.org/?probe=812e20e37e) | Aug 05, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [b90c18f9a0](https://linux-hardware.org/?probe=b90c18f9a0) | Aug 05, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [393c8e4faa](https://linux-hardware.org/?probe=393c8e4faa) | Aug 05, 2021 |
| Apple         | MacBook2,1                  | [103dba0476](https://linux-hardware.org/?probe=103dba0476) | Aug 05, 2021 |
| HP            | ProBook 6450b               | [ec02a5333b](https://linux-hardware.org/?probe=ec02a5333b) | Aug 05, 2021 |
| HP            | 3085B                       | [6be769f55c](https://linux-hardware.org/?probe=6be769f55c) | Aug 05, 2021 |
| Apple         | MacBook5,2                  | [0a79f49420](https://linux-hardware.org/?probe=0a79f49420) | Aug 05, 2021 |
| HP            | Pavilion dm4                | [7ba854b03e](https://linux-hardware.org/?probe=7ba854b03e) | Aug 05, 2021 |
| Clevo         | W240HU/W250HUQ              | [f71032cd7f](https://linux-hardware.org/?probe=f71032cd7f) | Aug 05, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [5ba990c425](https://linux-hardware.org/?probe=5ba990c425) | Aug 04, 2021 |
| Apple         | MacBook7,1                  | [a0e7632e28](https://linux-hardware.org/?probe=a0e7632e28) | Aug 04, 2021 |
| Apple         | MacBook5,2                  | [803a6be591](https://linux-hardware.org/?probe=803a6be591) | Aug 04, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | [cca5aa2900](https://linux-hardware.org/?probe=cca5aa2900) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | [2c8c33becf](https://linux-hardware.org/?probe=2c8c33becf) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | [97f8f86784](https://linux-hardware.org/?probe=97f8f86784) | Aug 04, 2021 |
| Notebook      | NJ50_70CU                   | [a9b3790d07](https://linux-hardware.org/?probe=a9b3790d07) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | [2d764714a4](https://linux-hardware.org/?probe=2d764714a4) | Aug 04, 2021 |
| Acer          | Aspire E5-571G              | [b2a62f65d6](https://linux-hardware.org/?probe=b2a62f65d6) | Aug 04, 2021 |
| HP            | EliteBook 8460p             | [09a6257403](https://linux-hardware.org/?probe=09a6257403) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | [eafaf5ece3](https://linux-hardware.org/?probe=eafaf5ece3) | Aug 04, 2021 |
| ASUSTek       | N53Ta                       | [896a02b57b](https://linux-hardware.org/?probe=896a02b57b) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | [c0bf2b7b10](https://linux-hardware.org/?probe=c0bf2b7b10) | Aug 03, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | [3d29b58c58](https://linux-hardware.org/?probe=3d29b58c58) | Aug 03, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | [8b35a81ed6](https://linux-hardware.org/?probe=8b35a81ed6) | Aug 03, 2021 |
| Apple         | MacBookAir7,2               | [87bca8ecbc](https://linux-hardware.org/?probe=87bca8ecbc) | Aug 03, 2021 |
| Apple         | MacBook7,1                  | [fbbd748072](https://linux-hardware.org/?probe=fbbd748072) | Aug 03, 2021 |
| Apple         | MacBook4,1                  | [71738ebf7e](https://linux-hardware.org/?probe=71738ebf7e) | Aug 03, 2021 |
| Apple         | MacBook7,1                  | [06d86172a1](https://linux-hardware.org/?probe=06d86172a1) | Aug 03, 2021 |
| HP            | EliteBook 8460p             | [aa415746d6](https://linux-hardware.org/?probe=aa415746d6) | Aug 03, 2021 |
| Apple         | MacBookAir7,1               | [c8674581d0](https://linux-hardware.org/?probe=c8674581d0) | Aug 03, 2021 |
| Dell          | Latitude E4310              | [75a9aa20f2](https://linux-hardware.org/?probe=75a9aa20f2) | Aug 03, 2021 |
| Google        | Enguarde                    | [c758164470](https://linux-hardware.org/?probe=c758164470) | Aug 03, 2021 |
| Lenovo        | ThinkPad R61e 7650DHU       | [82f2f3a1a7](https://linux-hardware.org/?probe=82f2f3a1a7) | Aug 03, 2021 |
| ASUSTek       | 1005HA                      | [1f83d95a2a](https://linux-hardware.org/?probe=1f83d95a2a) | Aug 03, 2021 |
| Lenovo        | ThinkPad T410 2537W2L       | [c14dd630ed](https://linux-hardware.org/?probe=c14dd630ed) | Aug 03, 2021 |
| Apple         | MacBookAir7,2               | [99ccdd5455](https://linux-hardware.org/?probe=99ccdd5455) | Aug 02, 2021 |
| Apple         | MacBook5,2                  | [aa5aaf6fd0](https://linux-hardware.org/?probe=aa5aaf6fd0) | Aug 02, 2021 |
| Google        | Stout                       | [e4463bb3d4](https://linux-hardware.org/?probe=e4463bb3d4) | Aug 02, 2021 |
| Fujitsu       | LIFEBOOK T5010              | [75a544682e](https://linux-hardware.org/?probe=75a544682e) | Aug 02, 2021 |
| Google        | Enguarde                    | [09406c6908](https://linux-hardware.org/?probe=09406c6908) | Aug 02, 2021 |
| Apple         | MacBookAir7,1               | [01315f2df2](https://linux-hardware.org/?probe=01315f2df2) | Aug 02, 2021 |
| Apple         | MacBookAir7,1               | [e6ca37026c](https://linux-hardware.org/?probe=e6ca37026c) | Aug 02, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [70647a7f66](https://linux-hardware.org/?probe=70647a7f66) | Aug 02, 2021 |
| Dell          | Inspiron 7391               | [c4ac48e264](https://linux-hardware.org/?probe=c4ac48e264) | Aug 02, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | [ace43d8e9f](https://linux-hardware.org/?probe=ace43d8e9f) | Aug 02, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | [384ffe1123](https://linux-hardware.org/?probe=384ffe1123) | Aug 02, 2021 |
| Lenovo        | ThinkPad L520 5016NU7       | [101a0ca1b3](https://linux-hardware.org/?probe=101a0ca1b3) | Aug 01, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [9c7fb8e911](https://linux-hardware.org/?probe=9c7fb8e911) | Aug 01, 2021 |
| Lenovo        | ThinkPad L520 5016NU7       | [08fe25ec71](https://linux-hardware.org/?probe=08fe25ec71) | Aug 01, 2021 |
| Lenovo        | ThinkPad Edge E330 3354D... | [9c317f536b](https://linux-hardware.org/?probe=9c317f536b) | Aug 01, 2021 |
| ASUSTek       | ROG Strix G731GT_G731GT     | [f851abbdf5](https://linux-hardware.org/?probe=f851abbdf5) | Aug 01, 2021 |
| Dell          | Inspiron 5570               | [5b89a99ad8](https://linux-hardware.org/?probe=5b89a99ad8) | Jul 31, 2021 |
| Dell          | Vostro 5502                 | [f1e6f11078](https://linux-hardware.org/?probe=f1e6f11078) | Jul 31, 2021 |
| HP            | OMEN by HP Laptop 15-dc0... | [60f065b770](https://linux-hardware.org/?probe=60f065b770) | Jul 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [b62fb400bf](https://linux-hardware.org/?probe=b62fb400bf) | Jul 31, 2021 |
| Acer          | Aspire 7720                 | [6472272bf7](https://linux-hardware.org/?probe=6472272bf7) | Jul 30, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | [b16533813f](https://linux-hardware.org/?probe=b16533813f) | Jul 30, 2021 |
| Lenovo        | ThinkPad T470s 20HGS0A60... | [8a3c585de4](https://linux-hardware.org/?probe=8a3c585de4) | Jul 30, 2021 |
| Lenovo        | ThinkPad T450s 20BX004QG... | [a46cb950a4](https://linux-hardware.org/?probe=a46cb950a4) | Jul 29, 2021 |
| Dell          | XPS 13 7390                 | [370cea169d](https://linux-hardware.org/?probe=370cea169d) | Jul 29, 2021 |
| Dell          | XPS 13 7390                 | [a5a9ca4678](https://linux-hardware.org/?probe=a5a9ca4678) | Jul 29, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [55c54d17ad](https://linux-hardware.org/?probe=55c54d17ad) | Jul 29, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [1bb07ffc9f](https://linux-hardware.org/?probe=1bb07ffc9f) | Jul 29, 2021 |
| SLIMBOOK      | PROX14-AMD                  | [16aeb37a86](https://linux-hardware.org/?probe=16aeb37a86) | Jul 29, 2021 |
| Acer          | Nitro AN517-41              | [ccc850c1da](https://linux-hardware.org/?probe=ccc850c1da) | Jul 29, 2021 |
| Lenovo        | ThinkPad T420s 4174PEG      | [e448710e41](https://linux-hardware.org/?probe=e448710e41) | Jul 28, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [89d3c0f09d](https://linux-hardware.org/?probe=89d3c0f09d) | Jul 28, 2021 |
| HP            | OMEN by HP Laptop 17-cb1... | [bee4fd945a](https://linux-hardware.org/?probe=bee4fd945a) | Jul 28, 2021 |
| Lenovo        | ThinkPad T470 20HES1UD00    | [6034f6a417](https://linux-hardware.org/?probe=6034f6a417) | Jul 28, 2021 |
| Lenovo        | ThinkPad X230 2325BQ3       | [79a19ade20](https://linux-hardware.org/?probe=79a19ade20) | Jul 28, 2021 |
| Dell          | Inspiron 8600               | [2f49d18738](https://linux-hardware.org/?probe=2f49d18738) | Jul 28, 2021 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | [abdeaec5ce](https://linux-hardware.org/?probe=abdeaec5ce) | Jul 28, 2021 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | [5258847421](https://linux-hardware.org/?probe=5258847421) | Jul 28, 2021 |
| Lenovo        | ThinkPad T490 20RYCTO1WW    | [60c16ed267](https://linux-hardware.org/?probe=60c16ed267) | Jul 28, 2021 |
| Acer          | Swift SF313-52G             | [87add43827](https://linux-hardware.org/?probe=87add43827) | Jul 28, 2021 |
| Casper        | C17B                        | [6f56921ba5](https://linux-hardware.org/?probe=6f56921ba5) | Jul 27, 2021 |
| Lenovo        | ThinkPad X240 20AL008EUK    | [367150f04f](https://linux-hardware.org/?probe=367150f04f) | Jul 27, 2021 |
| HP            | Laptop 17-by0xxx            | [0cb6fde0ef](https://linux-hardware.org/?probe=0cb6fde0ef) | Jul 27, 2021 |
| HP            | ProBook 445 G7              | [bc4f8acaf2](https://linux-hardware.org/?probe=bc4f8acaf2) | Jul 27, 2021 |
| HP            | ProBook 635 Aero G7 Note... | [e6ee486690](https://linux-hardware.org/?probe=e6ee486690) | Jul 27, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [2a645d9cba](https://linux-hardware.org/?probe=2a645d9cba) | Jul 27, 2021 |
| Lenovo        | IdeaPad S540-13ITL 82H1     | [730c33a1b0](https://linux-hardware.org/?probe=730c33a1b0) | Jul 27, 2021 |
| Lenovo        | ThinkPad E14 20RAS13M00     | [b46ca83c19](https://linux-hardware.org/?probe=b46ca83c19) | Jul 27, 2021 |
| Dell          | Latitude 7480               | [0c79ad3dd4](https://linux-hardware.org/?probe=0c79ad3dd4) | Jul 27, 2021 |
| Dell          | Inspiron 7420               | [5b2e06697e](https://linux-hardware.org/?probe=5b2e06697e) | Jul 27, 2021 |
| Dell          | Inspiron 7420               | [567612e805](https://linux-hardware.org/?probe=567612e805) | Jul 27, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [0172934285](https://linux-hardware.org/?probe=0172934285) | Jul 27, 2021 |
| HP            | EliteBook 820 G1            | [f3878ff548](https://linux-hardware.org/?probe=f3878ff548) | Jul 27, 2021 |
| Apple         | MacBookPro11,4              | [d58bb90557](https://linux-hardware.org/?probe=d58bb90557) | Jul 26, 2021 |
| Dell          | Inspiron 5558               | [1bbe185e86](https://linux-hardware.org/?probe=1bbe185e86) | Jul 26, 2021 |
| Lenovo        | ThinkPad E14 20RA001HRT     | [f7175e6651](https://linux-hardware.org/?probe=f7175e6651) | Jul 26, 2021 |
| Quanta        | TWC                         | [1ecec0372f](https://linux-hardware.org/?probe=1ecec0372f) | Jul 26, 2021 |
| HP            | Laptop 15s-fq2xxx           | [2f259b4ae2](https://linux-hardware.org/?probe=2f259b4ae2) | Jul 26, 2021 |
| Dell          | Vostro 5471                 | [73c1da1908](https://linux-hardware.org/?probe=73c1da1908) | Jul 26, 2021 |
| Lenovo        | G50-80 80E5                 | [eaedf12907](https://linux-hardware.org/?probe=eaedf12907) | Jul 26, 2021 |
| HP            | EliteBook 8470p             | [8bfc663f48](https://linux-hardware.org/?probe=8bfc663f48) | Jul 26, 2021 |
| HP            | ProBook 470 G3              | [cb1b02b979](https://linux-hardware.org/?probe=cb1b02b979) | Jul 26, 2021 |
| ASUSTek       | 701                         | [db72d4004a](https://linux-hardware.org/?probe=db72d4004a) | Jul 26, 2021 |
| ASUSTek       | 1215B                       | [ce53b40511](https://linux-hardware.org/?probe=ce53b40511) | Jul 26, 2021 |
| Dell          | Latitude E6420              | [01000461fc](https://linux-hardware.org/?probe=01000461fc) | Jul 26, 2021 |
| Dell          | Studio 1555                 | [30b17f2421](https://linux-hardware.org/?probe=30b17f2421) | Jul 26, 2021 |
| Lenovo        | ThinkPad E14 20RA0036RT     | [e4f29039a8](https://linux-hardware.org/?probe=e4f29039a8) | Jul 26, 2021 |
| Apple         | MacBookPro9,2               | [c676ac21ee](https://linux-hardware.org/?probe=c676ac21ee) | Jul 26, 2021 |
| ASUSTek       | 701SD                       | [b7c888a9a7](https://linux-hardware.org/?probe=b7c888a9a7) | Jul 26, 2021 |
| Toshiba       | Satellite S55-A             | [a145aa9a69](https://linux-hardware.org/?probe=a145aa9a69) | Jul 26, 2021 |
| ASUSTek       | X541NC                      | [500a26f588](https://linux-hardware.org/?probe=500a26f588) | Jul 26, 2021 |
| Toshiba       | Satellite S55-A             | [08eec2f3a7](https://linux-hardware.org/?probe=08eec2f3a7) | Jul 25, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [ec1cea0d9d](https://linux-hardware.org/?probe=ec1cea0d9d) | Jul 25, 2021 |
| Dell          | XPS 17 9700                 | [92cd785445](https://linux-hardware.org/?probe=92cd785445) | Jul 25, 2021 |
| Lenovo        | ThinkPad T460 20FMS03600    | [84f380e2a2](https://linux-hardware.org/?probe=84f380e2a2) | Jul 25, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [4454739a42](https://linux-hardware.org/?probe=4454739a42) | Jul 25, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3UX0... | [abced1dd83](https://linux-hardware.org/?probe=abced1dd83) | Jul 25, 2021 |
| Lenovo        | ThinkPad E480 20KN001NGE    | [e3b2914d19](https://linux-hardware.org/?probe=e3b2914d19) | Jul 25, 2021 |
| Toshiba       | Satellite C45-A             | [0497ab613d](https://linux-hardware.org/?probe=0497ab613d) | Jul 25, 2021 |
| Lenovo        | ThinkPad T420 4236WNU       | [d817abc511](https://linux-hardware.org/?probe=d817abc511) | Jul 25, 2021 |
| HP            | ProBook x360 11 G1 EE       | [90aeea53cc](https://linux-hardware.org/?probe=90aeea53cc) | Jul 25, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [5c61fdfb49](https://linux-hardware.org/?probe=5c61fdfb49) | Jul 25, 2021 |
| Dell          | Latitude E5520              | [0d74f57317](https://linux-hardware.org/?probe=0d74f57317) | Jul 25, 2021 |
| Dell          | Latitude E5520              | [5866765bab](https://linux-hardware.org/?probe=5866765bab) | Jul 25, 2021 |
| HP            | 250 G7 Notebook PC          | [ab8a90e145](https://linux-hardware.org/?probe=ab8a90e145) | Jul 25, 2021 |
| HP            | OMEN by HP Laptop 15-dc0... | [b8a2299d30](https://linux-hardware.org/?probe=b8a2299d30) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [0d45d49199](https://linux-hardware.org/?probe=0d45d49199) | Jul 25, 2021 |
| PC Special... | NV4XMB,ME,MZ                | [eb789efe18](https://linux-hardware.org/?probe=eb789efe18) | Jul 25, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [a172262124](https://linux-hardware.org/?probe=a172262124) | Jul 25, 2021 |
| Lenovo        | ThinkPad T410 2522WUZ       | [62cddaceb1](https://linux-hardware.org/?probe=62cddaceb1) | Jul 25, 2021 |
| Lenovo        | ThinkPad T480 20L5S1S000    | [1217d711fb](https://linux-hardware.org/?probe=1217d711fb) | Jul 25, 2021 |
| Lenovo        | ThinkPad T480 20L50063EU    | [c59c2aa27d](https://linux-hardware.org/?probe=c59c2aa27d) | Jul 25, 2021 |
| Lenovo        | ThinkPad X201 3626ES3       | [c18f4c4102](https://linux-hardware.org/?probe=c18f4c4102) | Jul 25, 2021 |
| Lenovo        | ThinkPad T430 2349BW1       | [75c4d5c7a9](https://linux-hardware.org/?probe=75c4d5c7a9) | Jul 25, 2021 |
| Lenovo        | ThinkPad T495 20NKS0PG00    | [59533bd2bf](https://linux-hardware.org/?probe=59533bd2bf) | Jul 25, 2021 |
| Acer          | Aspire 5735                 | [60451d6f55](https://linux-hardware.org/?probe=60451d6f55) | Jul 25, 2021 |
| Fujitsu       | LIFEBOOK AH532/G52          | [4e8d8d9253](https://linux-hardware.org/?probe=4e8d8d9253) | Jul 25, 2021 |
| HP            | ProBook 470 G5              | [a778d78c98](https://linux-hardware.org/?probe=a778d78c98) | Jul 25, 2021 |
| Lenovo        | ThinkPad T420 4236EV9       | [62cc86b330](https://linux-hardware.org/?probe=62cc86b330) | Jul 25, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [b3dca0cfaa](https://linux-hardware.org/?probe=b3dca0cfaa) | Jul 25, 2021 |
| HP            | 250 G5 Notebook PC          | [53d3003d94](https://linux-hardware.org/?probe=53d3003d94) | Jul 25, 2021 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | [043c5815ee](https://linux-hardware.org/?probe=043c5815ee) | Jul 25, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [a30a8b568e](https://linux-hardware.org/?probe=a30a8b568e) | Jul 25, 2021 |
| ASUSTek       | TUF GAMING FX504GD_FX80G... | [686f21af90](https://linux-hardware.org/?probe=686f21af90) | Jul 25, 2021 |
| Dell          | XPS L322X                   | [6b0ab2e22d](https://linux-hardware.org/?probe=6b0ab2e22d) | Jul 25, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [722792ec34](https://linux-hardware.org/?probe=722792ec34) | Jul 25, 2021 |
| Dell          | Inspiron 3505               | [be67f17212](https://linux-hardware.org/?probe=be67f17212) | Jul 25, 2021 |
| Dell          | XPS 13 9300                 | [15012d7630](https://linux-hardware.org/?probe=15012d7630) | Jul 25, 2021 |
| Panasonic     | CF-AX2LDCZMF                | [31feab61fe](https://linux-hardware.org/?probe=31feab61fe) | Jul 25, 2021 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [3dae264c17](https://linux-hardware.org/?probe=3dae264c17) | Jul 25, 2021 |
| HP            | Laptop 14-ck0xxx            | [814f91322d](https://linux-hardware.org/?probe=814f91322d) | Jul 25, 2021 |
| Dell          | Inspiron 5423               | [f15c87c33c](https://linux-hardware.org/?probe=f15c87c33c) | Jul 25, 2021 |
| Lenovo        | ThinkPad T480s 20L8S7HF0... | [5417d20b5b](https://linux-hardware.org/?probe=5417d20b5b) | Jul 25, 2021 |
| Lenovo        | ThinkPad T430 2349GCG       | [7275a5dc90](https://linux-hardware.org/?probe=7275a5dc90) | Jul 25, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [8e2d810033](https://linux-hardware.org/?probe=8e2d810033) | Jul 25, 2021 |
| Lenovo        | ThinkPad T450s 20BX004QG... | [079f1c9006](https://linux-hardware.org/?probe=079f1c9006) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [6f137bd0e5](https://linux-hardware.org/?probe=6f137bd0e5) | Jul 25, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [94307be3d8](https://linux-hardware.org/?probe=94307be3d8) | Jul 25, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [9e0045da76](https://linux-hardware.org/?probe=9e0045da76) | Jul 25, 2021 |
| MSI           | Modern 15 A11M              | [acfcaa9077](https://linux-hardware.org/?probe=acfcaa9077) | Jul 25, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [fb8dc2feb1](https://linux-hardware.org/?probe=fb8dc2feb1) | Jul 25, 2021 |
| HP            | Stream Notebook             | [078c5d40f8](https://linux-hardware.org/?probe=078c5d40f8) | Jul 25, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [49198ead06](https://linux-hardware.org/?probe=49198ead06) | Jul 25, 2021 |
| Lenovo        | ThinkPad X260 20F5S0JF00    | [98cbf345d9](https://linux-hardware.org/?probe=98cbf345d9) | Jul 25, 2021 |
| Dell          | Inspiron 5402               | [f54ac49b39](https://linux-hardware.org/?probe=f54ac49b39) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [10fb3b6e94](https://linux-hardware.org/?probe=10fb3b6e94) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [96fd57ba79](https://linux-hardware.org/?probe=96fd57ba79) | Jul 25, 2021 |
| Lenovo        | ThinkPad X260 20F5S46R00    | [c72e326772](https://linux-hardware.org/?probe=c72e326772) | Jul 25, 2021 |
| Gigabyte      | AERO 15 KB                  | [d66f45fc2e](https://linux-hardware.org/?probe=d66f45fc2e) | Jul 25, 2021 |
| HP            | ProBook 640 G2              | [558f739aab](https://linux-hardware.org/?probe=558f739aab) | Jul 25, 2021 |
| Dell          | XPS 13 9370                 | [2c9c978361](https://linux-hardware.org/?probe=2c9c978361) | Jul 25, 2021 |
| Lenovo        | ThinkPad T420 4236WC3       | [2dbdc931e7](https://linux-hardware.org/?probe=2dbdc931e7) | Jul 25, 2021 |
| Lenovo        | ThinkPad E14 20RB000UBR     | [c25d549bd7](https://linux-hardware.org/?probe=c25d549bd7) | Jul 25, 2021 |
| HP            | Laptop 15-ef1xxx            | [9f0fbc1613](https://linux-hardware.org/?probe=9f0fbc1613) | Jul 25, 2021 |
| Lenovo        | G50-80 80E5                 | [4c5e0baffe](https://linux-hardware.org/?probe=4c5e0baffe) | Jul 25, 2021 |
| HP            | EliteBook 820 G2            | [17b5a12640](https://linux-hardware.org/?probe=17b5a12640) | Jul 25, 2021 |
| Lenovo        | ThinkPad T430 2347FF9       | [cdc7a6e9c8](https://linux-hardware.org/?probe=cdc7a6e9c8) | Jul 25, 2021 |
| HP            | 2000                        | [0187fe7c8a](https://linux-hardware.org/?probe=0187fe7c8a) | Jul 25, 2021 |
| Acer          | Aspire A515-41G             | [a34056020d](https://linux-hardware.org/?probe=a34056020d) | Jul 25, 2021 |
| Dell          | XPS 13 7390                 | [02e6821b40](https://linux-hardware.org/?probe=02e6821b40) | Jul 24, 2021 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [4cf2681a8c](https://linux-hardware.org/?probe=4cf2681a8c) | Jul 24, 2021 |
| Apple         | MacBookPro8,1               | [b0e58bf8de](https://linux-hardware.org/?probe=b0e58bf8de) | Jul 24, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [3491bd4228](https://linux-hardware.org/?probe=3491bd4228) | Jul 23, 2021 |
| Lenovo        | ThinkPad E595 20NF0005IX    | [dd220c0bdb](https://linux-hardware.org/?probe=dd220c0bdb) | Jul 23, 2021 |
| Gigabyte      | AERO 17-SA                  | [eaff86e276](https://linux-hardware.org/?probe=eaff86e276) | Jul 23, 2021 |
| Acer          | Aspire A715-72G             | [b436023dda](https://linux-hardware.org/?probe=b436023dda) | Jul 23, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [ecd10ec3a7](https://linux-hardware.org/?probe=ecd10ec3a7) | Jul 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [1abb08da83](https://linux-hardware.org/?probe=1abb08da83) | Jul 21, 2021 |
| HP            | Laptop 15s-fq1xxx           | [4ed280d4c8](https://linux-hardware.org/?probe=4ed280d4c8) | Jul 19, 2021 |
| HP            | EliteBook 830 G7 Noteboo... | [acca72e9c1](https://linux-hardware.org/?probe=acca72e9c1) | Jul 15, 2021 |
| Lenovo        | ThinkPad Edge E540 20C60... | [a5daecad1d](https://linux-hardware.org/?probe=a5daecad1d) | Jul 15, 2021 |
| Dell          | Precision 3540              | [383ebf30aa](https://linux-hardware.org/?probe=383ebf30aa) | Jul 14, 2021 |
| Itautec       | Infoway                     | [06dc7b0fd1](https://linux-hardware.org/?probe=06dc7b0fd1) | Jul 14, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [71d234aaef](https://linux-hardware.org/?probe=71d234aaef) | Jul 14, 2021 |
| Acer          | Aspire 7741                 | [6ed4934b61](https://linux-hardware.org/?probe=6ed4934b61) | Jul 13, 2021 |
| Acer          | Aspire 7741                 | [ee5a2b2029](https://linux-hardware.org/?probe=ee5a2b2029) | Jul 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [54bfb26e0f](https://linux-hardware.org/?probe=54bfb26e0f) | Jul 12, 2021 |
| ASUSTek       | ROG Strix G533QS_G533QS     | [98271924ba](https://linux-hardware.org/?probe=98271924ba) | Jul 11, 2021 |
| Lenovo        | ThinkPad T430 2349V4B       | [d39fe8e9d4](https://linux-hardware.org/?probe=d39fe8e9d4) | Jul 11, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | [1cb0058b88](https://linux-hardware.org/?probe=1cb0058b88) | Jul 10, 2021 |
| Acer          | Aspire A315-23G             | [e6aa891005](https://linux-hardware.org/?probe=e6aa891005) | Jul 08, 2021 |
| Dell          | XPS 13 9380                 | [b31688ecfa](https://linux-hardware.org/?probe=b31688ecfa) | Jul 08, 2021 |
| Dell          | Latitude E6330              | [321bec10eb](https://linux-hardware.org/?probe=321bec10eb) | Jul 05, 2021 |
| HP            | Compaq 6830s                | [9c47e76afe](https://linux-hardware.org/?probe=9c47e76afe) | Jul 04, 2021 |
| HP            | Compaq 6830s                | [b524035304](https://linux-hardware.org/?probe=b524035304) | Jul 04, 2021 |
| Dell          | Inspiron 5570               | [b760b0d9cc](https://linux-hardware.org/?probe=b760b0d9cc) | Jul 03, 2021 |
| Acer          | Aspire A515-51              | [f94bb31c5a](https://linux-hardware.org/?probe=f94bb31c5a) | Jul 03, 2021 |
| HP            | ZBook Fury 17 G7 Mobile ... | [c24fcd1454](https://linux-hardware.org/?probe=c24fcd1454) | Jul 02, 2021 |
| Dell          | Inspiron 5570               | [44b96068f2](https://linux-hardware.org/?probe=44b96068f2) | Jul 02, 2021 |
| Acer          | Aspire A315-23G             | [5729444e9b](https://linux-hardware.org/?probe=5729444e9b) | Jul 02, 2021 |
| Acer          | Aspire A315-23G             | [bd3211a03b](https://linux-hardware.org/?probe=bd3211a03b) | Jun 30, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [c8cb82f74d](https://linux-hardware.org/?probe=c8cb82f74d) | Jun 30, 2021 |
| Dell          | XPS 13 9310                 | [24a52836b4](https://linux-hardware.org/?probe=24a52836b4) | Jun 30, 2021 |
| HP            | ProBook 640 G3              | [c56b8f3ff1](https://linux-hardware.org/?probe=c56b8f3ff1) | Jun 29, 2021 |
| HP            | ZBook 17 G5                 | [5557a5c23c](https://linux-hardware.org/?probe=5557a5c23c) | Jun 29, 2021 |
| Lenovo        | IdeaPad Z580                | [6a9d31c8ef](https://linux-hardware.org/?probe=6a9d31c8ef) | Jun 29, 2021 |
| Dell          | Inspiron 5570               | [5335641d04](https://linux-hardware.org/?probe=5335641d04) | Jun 28, 2021 |
| Dell          | Inspiron 5570               | [0632a7bf28](https://linux-hardware.org/?probe=0632a7bf28) | Jun 28, 2021 |
| Acer          | Aspire A315-23G             | [834b68e61a](https://linux-hardware.org/?probe=834b68e61a) | Jun 28, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [65c54db09e](https://linux-hardware.org/?probe=65c54db09e) | Jun 27, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [fda3d18cf7](https://linux-hardware.org/?probe=fda3d18cf7) | Jun 27, 2021 |
| HP            | ZBook Fury 17 G7 Mobile ... | [c3d5fd07c1](https://linux-hardware.org/?probe=c3d5fd07c1) | Jun 27, 2021 |
| Acer          | Nitro AN515-51              | [6c4a46b4ec](https://linux-hardware.org/?probe=6c4a46b4ec) | Jun 26, 2021 |
| Dell          | Inspiron 3501               | [d6f07cb592](https://linux-hardware.org/?probe=d6f07cb592) | Jun 23, 2021 |
| MSI           | GF65 Thin 10UE              | [d1e0b6ee58](https://linux-hardware.org/?probe=d1e0b6ee58) | Jun 22, 2021 |
| Lenovo        | ThinkPad T495 20NKS0PG00    | [9e646a384e](https://linux-hardware.org/?probe=9e646a384e) | Jun 22, 2021 |
| Dell          | Precision 3560              | [81efcf647c](https://linux-hardware.org/?probe=81efcf647c) | Jun 21, 2021 |
| Fujitsu       | LIFEBOOK A357               | [75c4ec9e5a](https://linux-hardware.org/?probe=75c4ec9e5a) | Jun 21, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [c62a9a5058](https://linux-hardware.org/?probe=c62a9a5058) | Jun 20, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [5a39dabe8a](https://linux-hardware.org/?probe=5a39dabe8a) | Jun 20, 2021 |
| Acer          | Aspire A315-23G             | [b37bec27b3](https://linux-hardware.org/?probe=b37bec27b3) | Jun 20, 2021 |
| Dell          | Latitude E7470              | [49cb9ff0b0](https://linux-hardware.org/?probe=49cb9ff0b0) | Jun 20, 2021 |
| Acer          | Aspire 5750G                | [73d6b46b6b](https://linux-hardware.org/?probe=73d6b46b6b) | Jun 19, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [a894e25838](https://linux-hardware.org/?probe=a894e25838) | Jun 19, 2021 |
| Acer          | Aspire A315-23G             | [dde7123487](https://linux-hardware.org/?probe=dde7123487) | Jun 19, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [842c53b8e2](https://linux-hardware.org/?probe=842c53b8e2) | Jun 18, 2021 |
| Acer          | Aspire A315-23G             | [1a8a3efde5](https://linux-hardware.org/?probe=1a8a3efde5) | Jun 18, 2021 |
| Lenovo        | ThinkPad X230 2325AZ8       | [b5ea5009bf](https://linux-hardware.org/?probe=b5ea5009bf) | Jun 18, 2021 |
| Lenovo        | Yoga 300-11IBR 80M1         | [259fc86278](https://linux-hardware.org/?probe=259fc86278) | Jun 18, 2021 |
| Acer          | Aspire ES1-132              | [c26c0f6e33](https://linux-hardware.org/?probe=c26c0f6e33) | Jun 15, 2021 |
| Acer          | Aspire A315-23G             | [eb77944ea2](https://linux-hardware.org/?probe=eb77944ea2) | Jun 14, 2021 |
| Acer          | Aspire V3-331               | [91f4f7aab6](https://linux-hardware.org/?probe=91f4f7aab6) | Jun 13, 2021 |
| UNOWHY        | Y13G002S4EI                 | [3d25dc9f69](https://linux-hardware.org/?probe=3d25dc9f69) | Jun 13, 2021 |
| ASUSTek       | X550LD                      | [2d1f6364aa](https://linux-hardware.org/?probe=2d1f6364aa) | Jun 13, 2021 |
| Acer          | Aspire V3-331               | [02e288caf9](https://linux-hardware.org/?probe=02e288caf9) | Jun 13, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [1b2cda6c08](https://linux-hardware.org/?probe=1b2cda6c08) | Jun 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [f6ba765876](https://linux-hardware.org/?probe=f6ba765876) | Jun 12, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [57684125de](https://linux-hardware.org/?probe=57684125de) | Jun 12, 2021 |
| Dell          | Latitude E7470              | [51c1f3f1f5](https://linux-hardware.org/?probe=51c1f3f1f5) | Jun 10, 2021 |
| Acer          | Aspire A315-23G             | [377f2e9ec6](https://linux-hardware.org/?probe=377f2e9ec6) | Jun 09, 2021 |
| Dell          | Latitude E6330              | [ba88cd6328](https://linux-hardware.org/?probe=ba88cd6328) | Jun 08, 2021 |
| Lenovo        | ThinkPad T430s 2356A89      | [0195b8564e](https://linux-hardware.org/?probe=0195b8564e) | Jun 08, 2021 |
| Acer          | Aspire ES1-132              | [2db77f0d01](https://linux-hardware.org/?probe=2db77f0d01) | Jun 07, 2021 |
| Acer          | Aspire A315-23G             | [548356ed30](https://linux-hardware.org/?probe=548356ed30) | Jun 06, 2021 |
| Dell          | Inspiron 3793               | [f65812f774](https://linux-hardware.org/?probe=f65812f774) | Jun 06, 2021 |
| ASUSTek       | M3N                         | [ec5f914161](https://linux-hardware.org/?probe=ec5f914161) | Jun 06, 2021 |
| ASUSTek       | M3N                         | [bd89f26d7e](https://linux-hardware.org/?probe=bd89f26d7e) | Jun 05, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [5c16d903d3](https://linux-hardware.org/?probe=5c16d903d3) | Jun 05, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [47e9dfd146](https://linux-hardware.org/?probe=47e9dfd146) | Jun 05, 2021 |
| Acer          | Aspire A315-23G             | [90dbe22a68](https://linux-hardware.org/?probe=90dbe22a68) | Jun 05, 2021 |
| HP            | ProBook 640 G8 Notebook ... | [e20b51102d](https://linux-hardware.org/?probe=e20b51102d) | Jun 03, 2021 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | [b513f2fc77](https://linux-hardware.org/?probe=b513f2fc77) | Jun 03, 2021 |
| Monster       | ABRA A5 V15.2               | [012bfa586d](https://linux-hardware.org/?probe=012bfa586d) | Jun 02, 2021 |
| Pegatron      | A15                         | [dec1b6b43a](https://linux-hardware.org/?probe=dec1b6b43a) | Jun 02, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [ac80feea4f](https://linux-hardware.org/?probe=ac80feea4f) | Jun 01, 2021 |
| Acer          | Aspire A315-23G             | [80cf3dc8e7](https://linux-hardware.org/?probe=80cf3dc8e7) | Jun 01, 2021 |
| HP            | Compaq tc4400 (GE179UP#A... | [eeaee9f1ad](https://linux-hardware.org/?probe=eeaee9f1ad) | Jun 01, 2021 |
| Toshiba       | Satellite U800W             | [ac79b35dfd](https://linux-hardware.org/?probe=ac79b35dfd) | May 30, 2021 |
| MSI           | U90/U100                    | [477251f62e](https://linux-hardware.org/?probe=477251f62e) | May 30, 2021 |
| MSI           | U90/U100                    | [1a0476551b](https://linux-hardware.org/?probe=1a0476551b) | May 30, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [c33e7ced42](https://linux-hardware.org/?probe=c33e7ced42) | May 29, 2021 |
| MSI           | CX700                       | [ef40976753](https://linux-hardware.org/?probe=ef40976753) | May 29, 2021 |
| Dell          | XPS 13 9310                 | [5de2c933c1](https://linux-hardware.org/?probe=5de2c933c1) | May 28, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | [88cee1e822](https://linux-hardware.org/?probe=88cee1e822) | May 28, 2021 |
| Samsung       | 370E4K                      | [125fbb3d15](https://linux-hardware.org/?probe=125fbb3d15) | May 28, 2021 |
| MSI           | CX700                       | [535d0016e2](https://linux-hardware.org/?probe=535d0016e2) | May 27, 2021 |
| Acer          | Aspire A315-23G             | [c091670daa](https://linux-hardware.org/?probe=c091670daa) | May 25, 2021 |
| Acer          | Aspire A315-23G             | [ad6cd7847f](https://linux-hardware.org/?probe=ad6cd7847f) | May 24, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [f03341d873](https://linux-hardware.org/?probe=f03341d873) | May 23, 2021 |
| HP            | EliteBook 840 G1            | [6573923d55](https://linux-hardware.org/?probe=6573923d55) | May 21, 2021 |
| Acer          | Aspire A315-23G             | [8b7b153998](https://linux-hardware.org/?probe=8b7b153998) | May 20, 2021 |
| Dell          | Latitude 7480               | [0f2477786d](https://linux-hardware.org/?probe=0f2477786d) | May 19, 2021 |
| Lenovo        | ThinkPad T440p 20AWS4PN0... | [f8b2c84bc1](https://linux-hardware.org/?probe=f8b2c84bc1) | May 19, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [b9d0acf0a6](https://linux-hardware.org/?probe=b9d0acf0a6) | May 19, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [97a658e572](https://linux-hardware.org/?probe=97a658e572) | May 19, 2021 |
| Acer          | Aspire A315-23G             | [28bb88d60c](https://linux-hardware.org/?probe=28bb88d60c) | May 17, 2021 |
| HP            | Compaq Presario C700        | [91a939ce16](https://linux-hardware.org/?probe=91a939ce16) | May 16, 2021 |
| Acer          | Aspire A315-23G             | [646b64ccb3](https://linux-hardware.org/?probe=646b64ccb3) | May 15, 2021 |
| HP            | Split 13 x2 PC              | [5834b6321d](https://linux-hardware.org/?probe=5834b6321d) | May 05, 2021 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [bf3e99374e](https://linux-hardware.org/?probe=bf3e99374e) | Apr 29, 2021 |
| Lenovo        | IdeaPad Z500 20202          | [a06f2bc29e](https://linux-hardware.org/?probe=a06f2bc29e) | Apr 27, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [a042fd63c6](https://linux-hardware.org/?probe=a042fd63c6) | Apr 27, 2021 |
| Dell          | Inspiron 3793               | [a4c79ea8c3](https://linux-hardware.org/?probe=a4c79ea8c3) | Apr 26, 2021 |
| HP            | EliteBook 8460p             | [bcea790fba](https://linux-hardware.org/?probe=bcea790fba) | Apr 24, 2021 |
| Lenovo        | ThinkPad T430s 23533KJ      | [39aa120e47](https://linux-hardware.org/?probe=39aa120e47) | Apr 21, 2021 |
| Dell          | Inspiron 5468               | [cfc77b26b5](https://linux-hardware.org/?probe=cfc77b26b5) | Apr 17, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | [4967255e37](https://linux-hardware.org/?probe=4967255e37) | Apr 14, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | [e1a5725060](https://linux-hardware.org/?probe=e1a5725060) | Apr 14, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Notebooks | Percent |
|----------------------------|-----------|---------|
| 5.10.0-8-amd64             | 392       | 75.82%  |
| 5.10.0-7-amd64             | 65        | 12.57%  |
| 5.10.0-6-amd64             | 23        | 4.45%   |
| 5.10.0-8-686-pae           | 5         | 0.97%   |
| 5.10.0-8-686               | 4         | 0.77%   |
| 5.12.0-19.3-liquorix-amd64 | 2         | 0.39%   |
| 4.19.0-14-amd64            | 2         | 0.39%   |
| 5.14.0-rc3-prygun          | 1         | 0.19%   |
| 5.13.8-xanmod1             | 1         | 0.19%   |
| 5.13.8                     | 1         | 0.19%   |
| 5.13.5-xanmod1             | 1         | 0.19%   |
| 5.13.4-e5520               | 1         | 0.19%   |
| 5.12.10                    | 1         | 0.19%   |
| 5.12.1                     | 1         | 0.19%   |
| 5.12.0-9.2-liquorix-amd64  | 1         | 0.19%   |
| 5.12.0-14.2-liquorix-amd64 | 1         | 0.19%   |
| 5.11.9+                    | 1         | 0.19%   |
| 5.11.22-1-pve              | 1         | 0.19%   |
| 5.11.15-051115-generic     | 1         | 0.19%   |
| 5.11.14                    | 1         | 0.19%   |
| 5.11.0-rc6                 | 1         | 0.19%   |
| 5.10.40-ismynik            | 1         | 0.19%   |
| 5.10.10-64                 | 1         | 0.19%   |
| 5.10.0-io7-amd64           | 1         | 0.19%   |
| 5.10.0-6-rt-amd64          | 1         | 0.19%   |
| 5.10.0-6-686               | 1         | 0.19%   |
| 5.10.0-5-amd64             | 1         | 0.19%   |
| 5.10.0-4-amd64             | 1         | 0.19%   |
| 4.19.181-z580322           | 1         | 0.19%   |
| 4.19.0-16-amd64            | 1         | 0.19%   |
| 4.19.0-16-686-pae          | 1         | 0.19%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.10.0   | 487       | 95.68%  |
| 4.19.0   | 4         | 0.79%   |
| 5.12.0   | 3         | 0.59%   |
| 5.13.8   | 2         | 0.39%   |
| 5.14.0   | 1         | 0.2%    |
| 5.13.5   | 1         | 0.2%    |
| 5.13.4   | 1         | 0.2%    |
| 5.12.10  | 1         | 0.2%    |
| 5.12.1   | 1         | 0.2%    |
| 5.11.9   | 1         | 0.2%    |
| 5.11.22  | 1         | 0.2%    |
| 5.11.15  | 1         | 0.2%    |
| 5.11.14  | 1         | 0.2%    |
| 5.11.0   | 1         | 0.2%    |
| 5.10.40  | 1         | 0.2%    |
| 5.10.10  | 1         | 0.2%    |
| 4.19.181 | 1         | 0.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 489       | 96.07%  |
| 5.12    | 5         | 0.98%   |
| 5.11    | 5         | 0.98%   |
| 4.19    | 5         | 0.98%   |
| 5.13    | 4         | 0.79%   |
| 5.14    | 1         | 0.2%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 497       | 97.83%  |
| i686   | 11        | 2.17%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Unknown          | 229       | 44.9%   |
| GNOME            | 103       | 20.2%   |
| KDE5             | 70        | 13.73%  |
| XFCE             | 38        | 7.45%   |
| MATE             | 16        | 3.14%   |
| i3               | 10        | 1.96%   |
| LXQt             | 7         | 1.37%   |
| X-Cinnamon       | 6         | 1.18%   |
| LXDE             | 6         | 1.18%   |
| Cinnamon         | 6         | 1.18%   |
| KDE              | 5         | 0.98%   |
| lightdm-xsession | 4         | 0.78%   |
| openbox          | 2         | 0.39%   |
| GNOME Flashback  | 2         | 0.39%   |
| Enlightenment    | 2         | 0.39%   |
| sway             | 1         | 0.2%    |
| ICEWM            | 1         | 0.2%    |
| default          | 1         | 0.2%    |
| awesome          | 1         | 0.2%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 218       | 42.58%  |
| X11     | 194       | 37.89%  |
| Wayland | 84        | 16.41%  |
| Tty     | 16        | 3.13%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 252       | 49.51%  |
| GDM     | 99        | 19.45%  |
| SDDM    | 75        | 14.73%  |
| TDM     | 72        | 14.15%  |
| LightDM | 9         | 1.77%   |
| XDM     | 1         | 0.2%    |
| KDM     | 1         | 0.2%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 204       | 40.08%  |
| en_US   | 126       | 24.75%  |
| ru_RU   | 26        | 5.11%   |
| en_GB   | 21        | 4.13%   |
| fr_FR   | 17        | 3.34%   |
| de_DE   | 15        | 2.95%   |
| es_ES   | 12        | 2.36%   |
| pt_BR   | 8         | 1.57%   |
| pl_PL   | 7         | 1.38%   |
| en_IN   | 7         | 1.38%   |
| sv_SE   | 5         | 0.98%   |
| tr_TR   | 4         | 0.79%   |
| it_IT   | 4         | 0.79%   |
| es_MX   | 4         | 0.79%   |
| en_CA   | 4         | 0.79%   |
| de_CH   | 4         | 0.79%   |
| C       | 4         | 0.79%   |
| nn_NO   | 3         | 0.59%   |
| pt_PT   | 2         | 0.39%   |
| ja_JP   | 2         | 0.39%   |
| fi_FI   | 2         | 0.39%   |
| es_CO   | 2         | 0.39%   |
| en_SG   | 2         | 0.39%   |
| en_AU   | 2         | 0.39%   |
| de_AT   | 2         | 0.39%   |
| cs_CZ   | 2         | 0.39%   |
| zh_CN   | 1         | 0.2%    |
| uk_UA   | 1         | 0.2%    |
| sk_SK   | 1         | 0.2%    |
| ru_UA   | 1         | 0.2%    |
| ro_RO   | 1         | 0.2%    |
| nl_BE   | 1         | 0.2%    |
| hu_HU   | 1         | 0.2%    |
| hr_HR   | 1         | 0.2%    |
| gl_ES   | 1         | 0.2%    |
| es_UY   | 1         | 0.2%    |
| es_GT   | 1         | 0.2%    |
| es_EC   | 1         | 0.2%    |
| en_SI   | 1         | 0.2%    |
| en_NZ   | 1         | 0.2%    |
| en_IE   | 1         | 0.2%    |
| en_HK   | 1         | 0.2%    |
| ca_ES   | 1         | 0.2%    |
| bg_BG   | 1         | 0.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 399       | 78.39%  |
| BIOS | 110       | 21.61%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 254       | 50%     |
| Overlay | 228       | 44.88%  |
| Btrfs   | 19        | 3.74%   |
| Zfs     | 2         | 0.39%   |
| Xfs     | 2         | 0.39%   |
| Unknown | 2         | 0.39%   |
| Rootfs  | 1         | 0.2%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 412       | 80.94%  |
| MBR     | 72        | 14.15%  |
| Unknown | 25        | 4.91%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 473       | 92.93%  |
| Yes       | 36        | 7.07%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 422       | 83.07%  |
| Yes       | 86        | 16.93%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Apple               | 141       | 27.76%  |
| Lenovo              | 120       | 23.62%  |
| Hewlett-Packard     | 55        | 10.83%  |
| Dell                | 52        | 10.24%  |
| Google              | 49        | 9.65%   |
| ASUSTek Computer    | 28        | 5.51%   |
| Acer                | 21        | 4.13%   |
| MSI                 | 5         | 0.98%   |
| HUAWEI              | 4         | 0.79%   |
| Toshiba             | 3         | 0.59%   |
| Samsung Electronics | 3         | 0.59%   |
| Notebook            | 3         | 0.59%   |
| Gigabyte Technology | 3         | 0.59%   |
| Fujitsu             | 3         | 0.59%   |
| Clevo               | 3         | 0.59%   |
| Sony                | 2         | 0.39%   |
| SLIMBOOK            | 2         | 0.39%   |
| YJKC                | 1         | 0.2%    |
| UNOWHY              | 1         | 0.2%    |
| TUXEDO              | 1         | 0.2%    |
| Timi                | 1         | 0.2%    |
| Quanta              | 1         | 0.2%    |
| Pegatron            | 1         | 0.2%    |
| PC Specialist       | 1         | 0.2%    |
| Panasonic           | 1         | 0.2%    |
| Monster             | 1         | 0.2%    |
| Itautec             | 1         | 0.2%    |
| Casper              | 1         | 0.2%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Apple MacBookAir7,1                        | 73        | 14.37%  |
| Apple MacBookAir7,2                        | 58        | 11.42%  |
| Google Enguarde                            | 47        | 9.25%   |
| Lenovo ThinkPad 13 2nd Gen 20J10046US      | 11        | 2.17%   |
| Dell Latitude 7480                         | 3         | 0.59%   |
| Lenovo ThinkPad T490 20N2CTO1WW            | 2         | 0.39%   |
| Lenovo ThinkPad E475 20H40006US            | 2         | 0.39%   |
| Lenovo ThinkBook 14 G2 ARE 20VF            | 2         | 0.39%   |
| Lenovo G50-80 80E5                         | 2         | 0.39%   |
| HUAWEI NBLK-WAX9X                          | 2         | 0.39%   |
| HP Laptop 15s-fq2xxx                       | 2         | 0.39%   |
| HP EliteBook 8460p                         | 2         | 0.39%   |
| HP Compaq nx6125 (PZ849UA#ABA)             | 2         | 0.39%   |
| HP Compaq nx6110 (PZ065UA#ABA)             | 2         | 0.39%   |
| Dell XPS 13 9370                           | 2         | 0.39%   |
| Dell XPS 13 9310                           | 2         | 0.39%   |
| Dell XPS 13 7390                           | 2         | 0.39%   |
| Dell Precision 3540                        | 2         | 0.39%   |
| Dell Latitude E7470                        | 2         | 0.39%   |
| Dell Inspiron 5570                         | 2         | 0.39%   |
| Dell Inspiron 3793                         | 2         | 0.39%   |
| Dell Inspiron 15 7000 Gaming               | 2         | 0.39%   |
| ASUS VivoBook_ASUS Laptop E210MA_L210MA    | 2         | 0.39%   |
| Apple MacBook7,1                           | 2         | 0.39%   |
| Apple MacBook5,2                           | 2         | 0.39%   |
| Acer Aspire 5315                           | 2         | 0.39%   |
| YJKC vBOOK Plus                            | 1         | 0.2%    |
| UNOWHY Y13G002S4EI                         | 1         | 0.2%    |
| TUXEDO Pulse 15 Gen1                       | 1         | 0.2%    |
| Toshiba Satellite U800W                    | 1         | 0.2%    |
| Toshiba Satellite S55-A                    | 1         | 0.2%    |
| Toshiba Satellite C45-A                    | 1         | 0.2%    |
| Timi TM1612                                | 1         | 0.2%    |
| Sony VPCF21AFX                             | 1         | 0.2%    |
| Sony VPCF115FM                             | 1         | 0.2%    |
| SLIMBOOK TITAN                             | 1         | 0.2%    |
| SLIMBOOK PROX14-AMD                        | 1         | 0.2%    |
| Samsung 900X3C/900X3D/900X3E/900X4C/900X4D | 1         | 0.2%    |
| Samsung 370E4K                             | 1         | 0.2%    |
| Samsung 300E5M/300E5L                      | 1         | 0.2%    |
| Quanta TWC                                 | 1         | 0.2%    |
| Pegatron A15                               | 1         | 0.2%    |
| PC Specialist NV4XMB,ME,MZ                 | 1         | 0.2%    |
| Panasonic CF-AX2LDCZMF                     | 1         | 0.2%    |
| Notebook NL4x_NL5xLU                       | 1         | 0.2%    |
| Notebook NJ50_70CU                         | 1         | 0.2%    |
| Notebook N13_N140ZU                        | 1         | 0.2%    |
| MSI U90/U100                               | 1         | 0.2%    |
| MSI Modern 15 A11M                         | 1         | 0.2%    |
| MSI GP60 2PE                               | 1         | 0.2%    |
| MSI GF65 Thin 10UE                         | 1         | 0.2%    |
| MSI CX700                                  | 1         | 0.2%    |
| Monster ABRA A5 V15.2                      | 1         | 0.2%    |
| Lenovo Yoga 300-11IBR 80M1                 | 1         | 0.2%    |
| Lenovo V510-15IKB 80WQ                     | 1         | 0.2%    |
| Lenovo V14 G2 ITL 82KA                     | 1         | 0.2%    |
| Lenovo ThinkPad X270 W10DG 20K5S41E00      | 1         | 0.2%    |
| Lenovo ThinkPad X260 20F5S46R00            | 1         | 0.2%    |
| Lenovo ThinkPad X260 20F5S0JF00            | 1         | 0.2%    |
| Lenovo ThinkPad X250 20CM001RMS            | 1         | 0.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Apple MacBookAir7      | 131       | 25.79%  |
| Lenovo ThinkPad        | 94        | 18.5%   |
| Google Enguarde        | 47        | 9.25%   |
| Dell Inspiron          | 19        | 3.74%   |
| Lenovo IdeaPad         | 17        | 3.35%   |
| Acer Aspire            | 15        | 2.95%   |
| HP ProBook             | 12        | 2.36%   |
| Dell Latitude          | 12        | 2.36%   |
| Dell XPS               | 11        | 2.17%   |
| HP Laptop              | 9         | 1.77%   |
| HP EliteBook           | 9         | 1.77%   |
| HP Compaq              | 8         | 1.57%   |
| Dell Precision         | 5         | 0.98%   |
| ASUS ZenBook           | 5         | 0.98%   |
| ASUS VivoBook          | 5         | 0.98%   |
| ASUS ROG               | 4         | 0.79%   |
| Toshiba Satellite      | 3         | 0.59%   |
| Lenovo ThinkBook       | 3         | 0.59%   |
| HP Pavilion            | 3         | 0.59%   |
| HP 250                 | 3         | 0.59%   |
| Fujitsu LIFEBOOK       | 3         | 0.59%   |
| Acer Swift             | 3         | 0.59%   |
| Lenovo G50-80          | 2         | 0.39%   |
| HUAWEI NBLK-WAX9X      | 2         | 0.39%   |
| HP ZBook               | 2         | 0.39%   |
| HP OMEN                | 2         | 0.39%   |
| Gigabyte AERO          | 2         | 0.39%   |
| Dell Vostro            | 2         | 0.39%   |
| Dell G3                | 2         | 0.39%   |
| Apple MacBookPro11     | 2         | 0.39%   |
| Apple MacBook7         | 2         | 0.39%   |
| Apple MacBook5         | 2         | 0.39%   |
| Acer Nitro             | 2         | 0.39%   |
| YJKC vBOOK             | 1         | 0.2%    |
| UNOWHY Y13G002S4EI     | 1         | 0.2%    |
| TUXEDO Pulse           | 1         | 0.2%    |
| Timi TM1612            | 1         | 0.2%    |
| Sony VPCF21AFX         | 1         | 0.2%    |
| Sony VPCF115FM         | 1         | 0.2%    |
| SLIMBOOK TITAN         | 1         | 0.2%    |
| SLIMBOOK PROX14-AMD    | 1         | 0.2%    |
| Samsung 900X3C         | 1         | 0.2%    |
| Samsung 370E4K         | 1         | 0.2%    |
| Samsung 300E5M         | 1         | 0.2%    |
| Quanta TWC             | 1         | 0.2%    |
| Pegatron A15           | 1         | 0.2%    |
| PC Specialist NV4XMB   | 1         | 0.2%    |
| Panasonic CF-AX2LDCZMF | 1         | 0.2%    |
| Notebook NL4x          | 1         | 0.2%    |
| Notebook NJ50          | 1         | 0.2%    |
| Notebook N13           | 1         | 0.2%    |
| MSI U90                | 1         | 0.2%    |
| MSI Modern             | 1         | 0.2%    |
| MSI GP60               | 1         | 0.2%    |
| MSI GF65               | 1         | 0.2%    |
| MSI CX700              | 1         | 0.2%    |
| Monster ABRA           | 1         | 0.2%    |
| Lenovo Yoga            | 1         | 0.2%    |
| Lenovo V510-15IKB      | 1         | 0.2%    |
| Lenovo V14             | 1         | 0.2%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 132       | 25.98%  |
| 2021 | 127       | 25%     |
| 2019 | 104       | 20.47%  |
| 2018 | 24        | 4.72%   |
| 2013 | 15        | 2.95%   |
| 2012 | 15        | 2.95%   |
| 2011 | 14        | 2.76%   |
| 2017 | 12        | 2.36%   |
| 2008 | 12        | 2.36%   |
| 2016 | 11        | 2.17%   |
| 2015 | 10        | 1.97%   |
| 2014 | 9         | 1.77%   |
| 2009 | 9         | 1.77%   |
| 2010 | 4         | 0.79%   |
| 2007 | 3         | 0.59%   |
| 2005 | 3         | 0.59%   |
| 2006 | 2         | 0.39%   |
| 2004 | 2         | 0.39%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 508       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 464       | 90.98%  |
| Enabled  | 46        | 9.02%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 459       | 90.35%  |
| Yes  | 49        | 9.65%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 158       | 31.1%   |
| 3.01-4.0    | 157       | 30.91%  |
| 16.01-24.0  | 83        | 16.34%  |
| 8.01-16.0   | 53        | 10.43%  |
| 32.01-64.0  | 22        | 4.33%   |
| 1.01-2.0    | 16        | 3.15%   |
| 2.01-3.0    | 5         | 0.98%   |
| 64.01-256.0 | 4         | 0.79%   |
| 0.51-1.0    | 4         | 0.79%   |
| 0.01-0.5    | 4         | 0.79%   |
| 24.01-32.0  | 2         | 0.39%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 273       | 53.01%  |
| 2.01-3.0   | 85        | 16.5%   |
| 4.01-8.0   | 52        | 10.1%   |
| 0.51-1.0   | 33        | 6.41%   |
| 3.01-4.0   | 32        | 6.21%   |
| 8.01-16.0  | 24        | 4.66%   |
| 0.01-0.5   | 15        | 2.91%   |
| 32.01-64.0 | 1         | 0.19%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 407       | 80.12%  |
| 2      | 92        | 18.11%  |
| 3      | 5         | 0.98%   |
| 4      | 2         | 0.39%   |
| 0      | 2         | 0.39%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 423       | 83.27%  |
| Yes       | 85        | 16.73%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 276       | 54.33%  |
| No        | 232       | 45.67%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 502       | 98.82%  |
| No        | 6         | 1.18%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 442       | 87.01%  |
| No        | 66        | 12.99%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 251       | 49.41%  |
| France      | 26        | 5.12%   |
| Germany     | 25        | 4.92%   |
| Russia      | 23        | 4.53%   |
| Spain       | 16        | 3.15%   |
| Poland      | 13        | 2.56%   |
| Ukraine     | 11        | 2.17%   |
| UK          | 11        | 2.17%   |
| Brazil      | 10        | 1.97%   |
| Switzerland | 8         | 1.57%   |
| India       | 7         | 1.38%   |
| Canada      | 7         | 1.38%   |
| Turkey      | 6         | 1.18%   |
| Sweden      | 6         | 1.18%   |
| Netherlands | 6         | 1.18%   |
| Portugal    | 5         | 0.98%   |
| Mexico      | 5         | 0.98%   |
| Greece      | 5         | 0.98%   |
| Thailand    | 4         | 0.79%   |
| Norway      | 4         | 0.79%   |
| Kazakhstan  | 4         | 0.79%   |
| Italy       | 4         | 0.79%   |
| Belarus     | 4         | 0.79%   |
| Austria     | 4         | 0.79%   |
| Czechia     | 3         | 0.59%   |
| China       | 3         | 0.59%   |
| Slovenia    | 2         | 0.39%   |
| Japan       | 2         | 0.39%   |
| Indonesia   | 2         | 0.39%   |
| Finland     | 2         | 0.39%   |
| Ecuador     | 2         | 0.39%   |
| Croatia     | 2         | 0.39%   |
| Colombia    | 2         | 0.39%   |
| Bulgaria    | 2         | 0.39%   |
| Belgium     | 2         | 0.39%   |
| Australia   | 2         | 0.39%   |
| Uruguay     | 1         | 0.2%    |
| South Sudan | 1         | 0.2%    |
| Slovakia    | 1         | 0.2%    |
| Romania     | 1         | 0.2%    |
| Philippines | 1         | 0.2%    |
| New Zealand | 1         | 0.2%    |
| Morocco     | 1         | 0.2%    |
| Mongolia    | 1         | 0.2%    |
| Malaysia    | 1         | 0.2%    |
| Ireland     | 1         | 0.2%    |
| Hungary     | 1         | 0.2%    |
| Guatemala   | 1         | 0.2%    |
| Denmark     | 1         | 0.2%    |
| Bangladesh  | 1         | 0.2%    |
| Azerbaijan  | 1         | 0.2%    |
| Aruba       | 1         | 0.2%    |
| Argentina   | 1         | 0.2%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Notebooks | Percent |
|-----------------|-----------|---------|
| Portland        | 211       | 41.29%  |
| St Petersburg   | 12        | 2.35%   |
| Paris           | 9         | 1.76%   |
| Vienna          | 4         | 0.78%   |
| London          | 4         | 0.78%   |
| Berlin          | 4         | 0.78%   |
| Bengaluru       | 4         | 0.78%   |
| Bangkok         | 4         | 0.78%   |
| Zurich          | 3         | 0.59%   |
| Sevastopol      | 3         | 0.59%   |
| Lyon            | 3         | 0.59%   |
| Athens          | 3         | 0.59%   |
| Yevpatoriya     | 2         | 0.39%   |
| Tyreso Strand   | 2         | 0.39%   |
| Toronto         | 2         | 0.39%   |
| Sunnyvale       | 2         | 0.39%   |
| S??o Paulo      | 2         | 0.39%   |
| Rio de Janeiro  | 2         | 0.39%   |
| Offenburg       | 2         | 0.39%   |
| Moscow          | 2         | 0.39%   |
| Molde           | 2         | 0.39%   |
| Mesa            | 2         | 0.39%   |
| Manchester      | 2         | 0.39%   |
| Madrid          | 2         | 0.39%   |
| Loziska         | 2         | 0.39%   |
| Kyiv            | 2         | 0.39%   |
| Krakow          | 2         | 0.39%   |
| Kalamazoo       | 2         | 0.39%   |
| Istanbul        | 2         | 0.39%   |
| Hampden         | 2         | 0.39%   |
| Halifax         | 2         | 0.39%   |
| Gorinchem       | 2         | 0.39%   |
| Gloucester      | 2         | 0.39%   |
| Fryazino        | 2         | 0.39%   |
| Frankfort       | 2         | 0.39%   |
| Denpasar        | 2         | 0.39%   |
| Ankara          | 2         | 0.39%   |
| Ajdov????ina    | 2         | 0.39%   |
| Zhuhai          | 1         | 0.2%    |
| Zaragoza        | 1         | 0.2%    |
| Zagreb          | 1         | 0.2%    |
| Xalapa          | 1         | 0.2%    |
| Wroclaw         | 1         | 0.2%    |
| Waterloo        | 1         | 0.2%    |
| Warsaw          | 1         | 0.2%    |
| Waregem         | 1         | 0.2%    |
| Voronezh        | 1         | 0.2%    |
| Vitória        | 1         | 0.2%    |
| Vitry-sur-Seine | 1         | 0.2%    |
| Vigo            | 1         | 0.2%    |
| Valladolid      | 1         | 0.2%    |
| Valencia        | 1         | 0.2%    |
| Utrecht         | 1         | 0.2%    |
| Tyumen          | 1         | 0.2%    |
| Turin           | 1         | 0.2%    |
| Touques         | 1         | 0.2%    |
| Toul            | 1         | 0.2%    |
| Thonex          | 1         | 0.2%    |
| Thermopolis     | 1         | 0.2%    |
| The Hague       | 1         | 0.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Apple                     | 134       | 134    | 22.37%  |
| Samsung Electronics       | 94        | 104    | 15.69%  |
| Unknown                   | 64        | 67     | 10.68%  |
| WDC                       | 47        | 54     | 7.85%   |
| Seagate                   | 37        | 41     | 6.18%   |
| Toshiba                   | 26        | 27     | 4.34%   |
| Kingston                  | 26        | 28     | 4.34%   |
| SanDisk                   | 19        | 21     | 3.17%   |
| Crucial                   | 16        | 17     | 2.67%   |
| SK Hynix                  | 15        | 15     | 2.5%    |
| Intel                     | 15        | 15     | 2.5%    |
| SABRENT                   | 13        | 13     | 2.17%   |
| Hitachi                   | 13        | 13     | 2.17%   |
| Micron Technology         | 8         | 8      | 1.34%   |
| A-DATA Technology         | 8         | 10     | 1.34%   |
| China                     | 6         | 6      | 1%      |
| Fujitsu                   | 5         | 5      | 0.83%   |
| Union Memory              | 4         | 4      | 0.67%   |
| Transcend                 | 4         | 4      | 0.67%   |
| LITEON                    | 4         | 4      | 0.67%   |
| KIOXIA                    | 4         | 5      | 0.67%   |
| HGST                      | 4         | 4      | 0.67%   |
| LITEONIT                  | 3         | 3      | 0.5%    |
| JMicron                   | 3         | 3      | 0.5%    |
| ZTC                       | 2         | 2      | 0.33%   |
| XPG                       | 2         | 2      | 0.33%   |
| PNY                       | 2         | 2      | 0.33%   |
| Patriot                   | 2         | 2      | 0.33%   |
| Lenovo                    | 2         | 2      | 0.33%   |
| Intenso                   | 2         | 2      | 0.33%   |
| SPCC                      | 1         | 1      | 0.17%   |
| SILICONMOTION             | 1         | 1      | 0.17%   |
| Silicon Motion            | 1         | 2      | 0.17%   |
| Phison                    | 1         | 4      | 0.17%   |
| MyDigitalSSD              | 1         | 1      | 0.17%   |
| Micron/Crucial Technology | 1         | 1      | 0.17%   |
| Maxtor                    | 1         | 3      | 0.17%   |
| LDLC                      | 1         | 1      | 0.17%   |
| KIOXIA-EXCERIA            | 1         | 1      | 0.17%   |
| GOODRAM                   | 1         | 1      | 0.17%   |
| FORESEE                   | 1         | 1      | 0.17%   |
| Corsair                   | 1         | 1      | 0.17%   |
| ASUS-PHISON               | 1         | 1      | 0.17%   |
| Apacer                    | 1         | 1      | 0.17%   |
| AMD                       | 1         | 2      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Apple SSD AP0128H 121GB                 | 73        | 11.85%  |
| Apple SSD SM0128G 121GB                 | 57        | 9.25%   |
| Unknown AGND3R  16GB                    | 25        | 4.06%   |
| Unknown HAG2e  16GB                     | 19        | 3.08%   |
| SABRENT Disk 1TB                        | 13        | 2.11%   |
| Seagate ST1000LM035-1RK172 1TB          | 7         | 1.14%   |
| SanDisk SD8SN8U128G1001 128GB SSD       | 7         | 1.14%   |
| Samsung SSD 970 EVO Plus 500GB          | 5         | 0.81%   |
| Samsung SSD 970 EVO Plus 1TB            | 5         | 0.81%   |
| Samsung MZNTY128HDHP-000L1 128GB SSD    | 5         | 0.81%   |
| Kingston SA400S37120G 120GB SSD         | 5         | 0.81%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 4         | 0.65%   |
| Samsung SSD 860 EVO 500GB               | 4         | 0.65%   |
| Samsung SSD 850 PRO 1TB                 | 4         | 0.65%   |
| Samsung SSD 850 EVO 500GB               | 4         | 0.65%   |
| Kingston SA400S37240G 240GB SSD         | 4         | 0.65%   |
| WDC WD10SPZX-21Z10T0 1TB                | 3         | 0.49%   |
| WDC WD10JPVX-22JC3T0 1TB                | 3         | 0.49%   |
| Unknown SDW16G  16GB                    | 3         | 0.49%   |
| Unknown DA4064  64GB                    | 3         | 0.49%   |
| Toshiba MQ04ABF100 1TB                  | 3         | 0.49%   |
| Seagate ST2000LX001-1RG174 2TB          | 3         | 0.49%   |
| Samsung SSD 860 EVO M.2 1TB             | 3         | 0.49%   |
| Samsung SSD 860 EVO 1TB                 | 3         | 0.49%   |
| Samsung SSD 850 EVO 250GB               | 3         | 0.49%   |
| Samsung MZALQ256HAJD-000L1 256GB        | 3         | 0.49%   |
| Hitachi HTS543216L9A300 160GB           | 3         | 0.49%   |
| HGST HTS721010A9E630 1TB                | 3         | 0.49%   |
| Crucial CT500MX500SSD1 500GB            | 3         | 0.49%   |
| Crucial CT1000MX500SSD1 1TB             | 3         | 0.49%   |
| ZTC SM201-512G SSD                      | 2         | 0.32%   |
| XPG NVMe SSD Drive 1024GB               | 2         | 0.32%   |
| WDC PC SN730 SDBPNTY-1T00-1006 1TB      | 2         | 0.32%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB    | 2         | 0.32%   |
| Unknown SD32G  32GB                     | 2         | 0.32%   |
| Union Memory UMIS RPJTJ256MEE1OWX 256GB | 2         | 0.32%   |
| Toshiba MQ01ABF050 500GB                | 2         | 0.32%   |
| Toshiba KXG60PNV2T04 NVMe KIOXIA 2048GB | 2         | 0.32%   |
| Toshiba KXG50ZNV512G NVMe 512GB         | 2         | 0.32%   |
| SK Hynix HFM001TD3JX013N 1TB            | 2         | 0.32%   |
| Seagate ST1000LX015-1U7172 1TB          | 2         | 0.32%   |
| SanDisk SSD PLUS 240GB                  | 2         | 0.32%   |
| Samsung SSD 980 1TB                     | 2         | 0.32%   |
| Samsung SSD 970 EVO 1TB                 | 2         | 0.32%   |
| Samsung SSD 850 PRO 256GB               | 2         | 0.32%   |
| Samsung SSD 850 EVO M.2 250GB           | 2         | 0.32%   |
| Samsung NVMe SSD Drive 1TB              | 2         | 0.32%   |
| Samsung MZVLB512HAJQ-000L7 512GB        | 2         | 0.32%   |
| Samsung MZ7TE256HMHP-000L7 256GB SSD    | 2         | 0.32%   |
| Micron 2300 NVMe 512GB                  | 2         | 0.32%   |
| Kingston SV300S37A120G 120GB SSD        | 2         | 0.32%   |
| Kingston SUV400S37120G 120GB SSD        | 2         | 0.32%   |
| Kingston OM8PCP3512F-AI1 512GB          | 2         | 0.32%   |
| JMicron Generic 240GB SSD               | 2         | 0.32%   |
| Intel SSDPEKNW010T8 1TB                 | 2         | 0.32%   |
| Hitachi HTS541040G9AT00 40GB            | 2         | 0.32%   |
| Fujitsu MHZ2160BH FFS G1 160GB          | 2         | 0.32%   |
| Crucial M4-CT256M4SSD2 256GB            | 2         | 0.32%   |
| Crucial CT1000P2SSD8 1TB                | 2         | 0.32%   |
| Crucial CT1000P1SSD8 1TB                | 2         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 33        | 37     | 35.87%  |
| WDC                 | 22        | 23     | 23.91%  |
| Hitachi             | 13        | 13     | 14.13%  |
| Toshiba             | 12        | 12     | 13.04%  |
| Fujitsu             | 5         | 5      | 5.43%   |
| HGST                | 4         | 4      | 4.35%   |
| Samsung Electronics | 2         | 2      | 2.17%   |
| SILICONMOTION       | 1         | 1      | 1.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Apple               | 61        | 61     | 25.85%  |
| Samsung Electronics | 54        | 59     | 22.88%  |
| Kingston            | 18        | 20     | 7.63%   |
| SanDisk             | 17        | 19     | 7.2%    |
| SABRENT             | 13        | 13     | 5.51%   |
| Crucial             | 11        | 12     | 4.66%   |
| Intel               | 7         | 7      | 2.97%   |
| China               | 6         | 6      | 2.54%   |
| WDC                 | 4         | 6      | 1.69%   |
| Transcend           | 4         | 4      | 1.69%   |
| Toshiba             | 4         | 4      | 1.69%   |
| SK Hynix            | 4         | 4      | 1.69%   |
| LITEONIT            | 3         | 3      | 1.27%   |
| LITEON              | 3         | 3      | 1.27%   |
| A-DATA Technology   | 3         | 3      | 1.27%   |
| ZTC                 | 2         | 2      | 0.85%   |
| Seagate             | 2         | 2      | 0.85%   |
| PNY                 | 2         | 2      | 0.85%   |
| Patriot             | 2         | 2      | 0.85%   |
| Micron Technology   | 2         | 2      | 0.85%   |
| JMicron             | 2         | 2      | 0.85%   |
| Intenso             | 2         | 2      | 0.85%   |
| Union Memory        | 1         | 1      | 0.42%   |
| SPCC                | 1         | 1      | 0.42%   |
| MyDigitalSSD        | 1         | 1      | 0.42%   |
| Maxtor              | 1         | 3      | 0.42%   |
| LDLC                | 1         | 1      | 0.42%   |
| GOODRAM             | 1         | 1      | 0.42%   |
| FORESEE             | 1         | 1      | 0.42%   |
| ASUS-PHISON         | 1         | 1      | 0.42%   |
| Apacer              | 1         | 1      | 0.42%   |
| AMD                 | 1         | 2      | 0.42%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 221       | 251    | 38.24%  |
| NVMe    | 198       | 221    | 34.26%  |
| HDD     | 92        | 97     | 15.92%  |
| MMC     | 63        | 66     | 10.9%   |
| Unknown | 4         | 4      | 0.69%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 276       | 325    | 49.2%   |
| NVMe | 198       | 221    | 35.29%  |
| MMC  | 63        | 66     | 11.23%  |
| SAS  | 24        | 27     | 4.28%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 227       | 255    | 72.06%  |
| 0.51-1.0   | 78        | 82     | 24.76%  |
| 1.01-2.0   | 6         | 7      | 1.9%    |
| 3.01-4.0   | 2         | 2      | 0.63%   |
| 2.01-3.0   | 1         | 1      | 0.32%   |
| 4.01-10.0  | 1         | 1      | 0.32%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 247       | 48.34%  |
| 251-500        | 71        | 13.89%  |
| 1-20           | 70        | 13.7%   |
| 501-1000       | 42        | 8.22%   |
| 1001-2000      | 28        | 5.48%   |
| 51-100         | 19        | 3.72%   |
| 21-50          | 13        | 2.54%   |
| Unknown        | 12        | 2.35%   |
| More than 3000 | 7         | 1.37%   |
| 2001-3000      | 2         | 0.39%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 296       | 57.59%  |
| 101-250   | 53        | 10.31%  |
| 21-50     | 46        | 8.95%   |
| 51-100    | 40        | 7.78%   |
| 251-500   | 32        | 6.23%   |
| 501-1000  | 22        | 4.28%   |
| Unknown   | 12        | 2.33%   |
| 1001-2000 | 9         | 1.75%   |
| 0         | 3         | 0.58%   |
| 2001-3000 | 1         | 0.19%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD10JPVX-22JC3T0 1TB                       | 2         | 2      | 5.26%   |
| WDC WD10JPVT-75A1YT0 1TB                       | 1         | 1      | 2.63%   |
| Toshiba MQ04ABF100 1TB                         | 1         | 1      | 2.63%   |
| Toshiba MQ01ABF050 500GB                       | 1         | 1      | 2.63%   |
| Toshiba MQ01ABD100 1TB                         | 1         | 1      | 2.63%   |
| SK Hynix HFS256G39TND-N210A 256GB SSD          | 1         | 1      | 2.63%   |
| Seagate ST960822A 64GB                         | 1         | 1      | 2.63%   |
| Seagate ST9320325AS 320GB                      | 1         | 1      | 2.63%   |
| Seagate ST9160310AS 160GB                      | 1         | 1      | 2.63%   |
| Seagate ST500LT012-9WS142 500GB                | 1         | 1      | 2.63%   |
| Seagate ST500LM021-1KJ152 500GB                | 1         | 1      | 2.63%   |
| Seagate ST2000LX001-1RG174 2TB                 | 1         | 1      | 2.63%   |
| Seagate ST1000LX015-1U7172 1TB                 | 1         | 1      | 2.63%   |
| Seagate ST1000LM035-1RK172 1TB                 | 1         | 1      | 2.63%   |
| SanDisk SD7SB3Q128G1002 128GB SSD              | 1         | 1      | 2.63%   |
| SanDisk SD7SB2Q512G1001 512GB SSD              | 1         | 1      | 2.63%   |
| Samsung Electronics SSD 870 EVO 500GB          | 1         | 1      | 2.63%   |
| Samsung Electronics SSD 850 EVO 1TB            | 1         | 1      | 2.63%   |
| Samsung Electronics SSD 840 PRO Series 256GB   | 1         | 2      | 2.63%   |
| Samsung Electronics HM321HI 320GB              | 1         | 1      | 2.63%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 2.63%   |
| LITEONIT LMT-64M6M-HP 64GB SSD                 | 1         | 1      | 2.63%   |
| Kingston SV300S37A120G 120GB SSD               | 1         | 1      | 2.63%   |
| Kingston SA400S37120G 120GB SSD                | 1         | 1      | 2.63%   |
| Intel SSDSC2KW120H6 120GB                      | 1         | 1      | 2.63%   |
| Intel SSDSC2BF180A4H 180GB                     | 1         | 1      | 2.63%   |
| Intel SSDSA2M160G2HP 160GB                     | 1         | 1      | 2.63%   |
| Intel SSDPEKKF256G7H 256GB                     | 1         | 1      | 2.63%   |
| Hitachi HTS725050A9A364 500GB                  | 1         | 1      | 2.63%   |
| Hitachi HTS545050A7E380 500GB                  | 1         | 1      | 2.63%   |
| Hitachi HTS543225L9A300 250GB                  | 1         | 1      | 2.63%   |
| Hitachi HTS543212L9A300 120GB                  | 1         | 1      | 2.63%   |
| Hitachi HTS542516K9SA00 160GB                  | 1         | 1      | 2.63%   |
| Hitachi HTS542512K9SA00 120GB                  | 1         | 1      | 2.63%   |
| Hitachi HTS541040G9AT00 40GB                   | 1         | 1      | 2.63%   |
| HGST HTS725050A7E630 500GB                     | 1         | 1      | 2.63%   |
| A-DATA Technology SU630 480GB SSD              | 1         | 1      | 2.63%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 21.05%  |
| Hitachi             | 7         | 7      | 18.42%  |
| Samsung Electronics | 4         | 5      | 10.53%  |
| Intel               | 4         | 4      | 10.53%  |
| WDC                 | 3         | 3      | 7.89%   |
| Toshiba             | 3         | 3      | 7.89%   |
| SanDisk             | 2         | 2      | 5.26%   |
| Kingston            | 2         | 2      | 5.26%   |
| SK Hynix            | 1         | 1      | 2.63%   |
| Micron Technology   | 1         | 1      | 2.63%   |
| LITEONIT            | 1         | 1      | 2.63%   |
| HGST                | 1         | 1      | 2.63%   |
| A-DATA Technology   | 1         | 1      | 2.63%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 34.78%  |
| Hitachi             | 7         | 7      | 30.43%  |
| WDC                 | 3         | 3      | 13.04%  |
| Toshiba             | 3         | 3      | 13.04%  |
| Samsung Electronics | 1         | 1      | 4.35%   |
| HGST                | 1         | 1      | 4.35%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 23        | 23     | 60.53%  |
| SSD  | 14        | 15     | 36.84%  |
| NVMe | 1         | 1      | 2.63%   |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 400       | 469    | 73.66%  |
| Detected | 105       | 131    | 19.34%  |
| Malfunc  | 38        | 39     | 7%      |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 226       | 43.46%  |
| Samsung Electronics          | 101       | 19.42%  |
| Apple                        | 73        | 14.04%  |
| AMD                          | 31        | 5.96%   |
| Sandisk                      | 24        | 4.62%   |
| SK Hynix                     | 11        | 2.12%   |
| Toshiba America Info Systems | 9         | 1.73%   |
| Kingston Technology Company  | 8         | 1.54%   |
| Micron/Crucial Technology    | 6         | 1.15%   |
| Micron Technology            | 6         | 1.15%   |
| KIOXIA                       | 6         | 1.15%   |
| ADATA Technology             | 6         | 1.15%   |
| Nvidia                       | 4         | 0.77%   |
| Union Memory (Shenzhen)      | 3         | 0.58%   |
| Phison Electronics           | 2         | 0.38%   |
| Lenovo                       | 2         | 0.38%   |
| Silicon Motion               | 1         | 0.19%   |
| Lite-On Technology           | 1         | 0.19%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Apple S1X NVMe Controller                                                        | 73        | 13.49%  |
| Samsung Electronics SATA controller                                              | 59        | 10.91%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 41        | 7.58%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 30        | 5.55%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 26        | 4.81%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 26        | 4.81%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 19        | 3.51%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 17        | 3.14%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 14        | 2.59%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 14        | 2.59%   |
| Intel Volume Management Device NVMe RAID Controller                              | 11        | 2.03%   |
| Samsung NVMe Controller                                                          | 10        | 1.85%   |
| Intel Comet Lake SATA AHCI Controller                                            | 8         | 1.48%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 8         | 1.48%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 8         | 1.48%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 7         | 1.29%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 7         | 1.29%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 6         | 1.11%   |
| Micron Non-Volatile memory controller                                            | 6         | 1.11%   |
| KIOXIA Non-Volatile memory controller                                            | 6         | 1.11%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 6         | 1.11%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 6         | 1.11%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 5         | 0.92%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 5         | 0.92%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 4         | 0.74%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 4         | 0.74%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 4         | 0.74%   |
| Sandisk Non-Volatile memory controller                                           | 4         | 0.74%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                  | 4         | 0.74%   |
| Intel SSD 660P Series                                                            | 4         | 0.74%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 4         | 0.74%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 4         | 0.74%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 4         | 0.74%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 3         | 0.55%   |
| SK Hynix NVMe SSD Controller                                                     | 3         | 0.55%   |
| SK Hynix BC511                                                                   | 3         | 0.55%   |
| Sandisk PC SN520 NVMe SSD                                                        | 3         | 0.55%   |
| Kingston Company Company Non-Volatile memory controller                          | 3         | 0.55%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 3         | 0.55%   |
| Intel SSD 600P Series                                                            | 3         | 0.55%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 3         | 0.55%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 0.55%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 3         | 0.55%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 3         | 0.55%   |
| Intel 82801FBM (ICH6M) SATA Controller                                           | 3         | 0.55%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                         | 3         | 0.55%   |
| AMD IXP SB4x0 IDE Controller                                                     | 3         | 0.55%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 2         | 0.37%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 2         | 0.37%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 0.37%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 0.37%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                         | 2         | 0.37%   |
| Nvidia MCP79 AHCI Controller                                                     | 2         | 0.37%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 2         | 0.37%   |
| Lenovo Non-Volatile memory controller                                            | 2         | 0.37%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 2         | 0.37%   |
| Kingston Company A2000 NVMe SSD                                                  | 2         | 0.37%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                           | 2         | 0.37%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 2         | 0.37%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 2         | 0.37%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 279       | 52.64%  |
| NVMe | 198       | 37.36%  |
| RAID | 29        | 5.47%   |
| IDE  | 24        | 4.53%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 459       | 90.35%  |
| AMD    | 49        | 9.65%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-5250U CPU @ 1.60GHz             | 130       | 25.59%  |
| Intel Celeron CPU N2840 @ 2.16GHz             | 47        | 9.25%   |
| Intel Celeron CPU 3865U @ 1.80GHz             | 12        | 2.36%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 11        | 2.17%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 9         | 1.77%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 9         | 1.77%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 7         | 1.38%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 6         | 1.18%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 6         | 1.18%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 6         | 1.18%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 6         | 1.18%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 6         | 1.18%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 6         | 1.18%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 6         | 1.18%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 5         | 0.98%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 5         | 0.98%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 5         | 0.98%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 5         | 0.98%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 5         | 0.98%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 0.79%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 0.79%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 4         | 0.79%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 4         | 0.79%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 0.79%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 4         | 0.79%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 4         | 0.79%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 4         | 0.79%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 4         | 0.79%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 0.79%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 3         | 0.59%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 3         | 0.59%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 3         | 0.59%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 3         | 0.59%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 3         | 0.59%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 0.59%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 3         | 0.59%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 3         | 0.59%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 3         | 0.59%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 0.59%   |
| Intel Pentium M processor 1.73GHz             | 2         | 0.39%   |
| Intel Genuine CPU T1400 @ 1.73GHz             | 2         | 0.39%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 2         | 0.39%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.39%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 2         | 0.39%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 2         | 0.39%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 2         | 0.39%   |
| Intel Core i7-3612QM CPU @ 2.10GHz            | 2         | 0.39%   |
| Intel Core i7-3537U CPU @ 2.00GHz             | 2         | 0.39%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 2         | 0.39%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 2         | 0.39%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 2         | 0.39%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 0.39%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 0.39%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 2         | 0.39%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 2         | 0.39%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 2         | 0.39%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 2         | 0.39%   |
| Intel Core 2 Duo CPU T6400 @ 2.00GHz          | 2         | 0.39%   |
| Intel Core 2 Duo CPU P7450 @ 2.13GHz          | 2         | 0.39%   |
| Intel Core 2 CPU T7200 @ 2.00GHz              | 2         | 0.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 224       | 44.09%  |
| Intel Core i7        | 88        | 17.32%  |
| Intel Celeron        | 71        | 13.98%  |
| Other                | 22        | 4.33%   |
| Intel Core i3        | 15        | 2.95%   |
| Intel Core 2 Duo     | 15        | 2.95%   |
| AMD Ryzen 5          | 13        | 2.56%   |
| AMD Ryzen 7          | 9         | 1.77%   |
| AMD Ryzen 7 PRO      | 7         | 1.38%   |
| Intel Pentium        | 6         | 1.18%   |
| Intel Pentium M      | 5         | 0.98%   |
| AMD Ryzen 9          | 4         | 0.79%   |
| Intel Core 2         | 3         | 0.59%   |
| Intel Celeron M      | 3         | 0.59%   |
| Intel Genuine        | 2         | 0.39%   |
| Intel Atom           | 2         | 0.39%   |
| AMD Turion 64 Mobile | 2         | 0.39%   |
| AMD Ryzen 3          | 2         | 0.39%   |
| AMD A8               | 2         | 0.39%   |
| AMD A12              | 2         | 0.39%   |
| Intel Xeon           | 1         | 0.2%    |
| Intel Pentium Silver | 1         | 0.2%    |
| Intel Pentium Gold   | 1         | 0.2%    |
| Intel Pentium Dual   | 1         | 0.2%    |
| Intel Core m7        | 1         | 0.2%    |
| Intel Core m3        | 1         | 0.2%    |
| AMD E                | 1         | 0.2%    |
| AMD C-30             | 1         | 0.2%    |
| AMD Athlon 64        | 1         | 0.2%    |
| AMD Athlon           | 1         | 0.2%    |
| AMD A6               | 1         | 0.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 344       | 67.72%  |
| 4      | 108       | 21.26%  |
| 6      | 20        | 3.94%   |
| 8      | 19        | 3.74%   |
| 1      | 17        | 3.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 508       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 383       | 75.39%  |
| 1      | 125       | 24.61%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 498       | 98.03%  |
| 32-bit         | 10        | 1.97%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x306d4    | 145       | 28.43%  |
| Unknown    | 53        | 10.39%  |
| 0x30678    | 47        | 9.22%   |
| 0x806e9    | 28        | 5.49%   |
| 0x306a9    | 26        | 5.1%    |
| 0x206a7    | 21        | 4.12%   |
| 0x806c1    | 18        | 3.53%   |
| 0x806ec    | 14        | 2.75%   |
| 0x806ea    | 13        | 2.55%   |
| 0x406e3    | 11        | 2.16%   |
| 0x40651    | 10        | 1.96%   |
| 0xa0652    | 9         | 1.76%   |
| 0x1067a    | 9         | 1.76%   |
| 0x906ea    | 8         | 1.57%   |
| 0x706e5    | 8         | 1.57%   |
| 0x08600106 | 8         | 1.57%   |
| 0x806eb    | 7         | 1.37%   |
| 0x08108109 | 7         | 1.37%   |
| 0x6d8      | 6         | 1.18%   |
| 0x306c3    | 5         | 0.98%   |
| 0x6fd      | 4         | 0.78%   |
| 0x506c9    | 4         | 0.78%   |
| 0x20655    | 4         | 0.78%   |
| 0x906e9    | 3         | 0.59%   |
| 0x706a8    | 3         | 0.59%   |
| 0x6f6      | 3         | 0.59%   |
| 0x0a50000b | 3         | 0.59%   |
| 0x08608103 | 3         | 0.59%   |
| 0x0600611a | 3         | 0.59%   |
| 0x6fa      | 2         | 0.39%   |
| 0x695      | 2         | 0.39%   |
| 0x40661    | 2         | 0.39%   |
| 0x106c2    | 2         | 0.39%   |
| 0x08600104 | 2         | 0.39%   |
| 0x08600103 | 2         | 0.39%   |
| 0x08108102 | 2         | 0.39%   |
| 0x06006705 | 2         | 0.39%   |
| 0x406c4    | 1         | 0.2%    |
| 0x406c3    | 1         | 0.2%    |
| 0x106e5    | 1         | 0.2%    |
| 0x10676    | 1         | 0.2%    |
| 0x10661    | 1         | 0.2%    |
| 0x0a50000c | 1         | 0.2%    |
| 0x0810100b | 1         | 0.2%    |
| 0x07030105 | 1         | 0.2%    |
| 0x05000101 | 1         | 0.2%    |
| 0x05000029 | 1         | 0.2%    |
| 0x03000027 | 1         | 0.2%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Broadwell     | 145       | 28.54%  |
| KabyLake      | 88        | 17.32%  |
| Silvermont    | 49        | 9.65%   |
| IvyBridge     | 30        | 5.91%   |
| Haswell       | 24        | 4.72%   |
| SandyBridge   | 21        | 4.13%   |
| TigerLake     | 20        | 3.94%   |
| Zen 2         | 15        | 2.95%   |
| Skylake       | 15        | 2.95%   |
| Zen+          | 11        | 2.17%   |
| Penryn        | 11        | 2.17%   |
| Core          | 11        | 2.17%   |
| CometLake     | 10        | 1.97%   |
| IceLake       | 9         | 1.77%   |
| Westmere      | 8         | 1.57%   |
| P6            | 8         | 1.57%   |
| Excavator     | 6         | 1.18%   |
| Zen 3         | 5         | 0.98%   |
| Goldmont      | 4         | 0.79%   |
| K8 Hammer     | 3         | 0.59%   |
| Goldmont plus | 3         | 0.59%   |
| Unknown       | 3         | 0.59%   |
| Zen           | 2         | 0.39%   |
| Bonnell       | 2         | 0.39%   |
| Bobcat        | 2         | 0.39%   |
| Puma          | 1         | 0.2%    |
| Nehalem       | 1         | 0.2%    |
| K10 Llano     | 1         | 0.2%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 441       | 76.43%  |
| Nvidia | 71        | 12.31%  |
| AMD    | 65        | 11.27%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 6000                                                                   | 131       | 22.09%  |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 47        | 7.93%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 28        | 4.72%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 19        | 3.2%    |
| Intel UHD Graphics 620                                                                   | 18        | 3.04%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 17        | 2.87%   |
| Intel HD Graphics 620                                                                    | 17        | 2.87%   |
| AMD Renoir                                                                               | 15        | 2.53%   |
| Intel HD Graphics 5500                                                                   | 14        | 2.36%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 14        | 2.36%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 14        | 2.36%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 13        | 2.19%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 12        | 2.02%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 12        | 2.02%   |
| AMD Picasso                                                                              | 11        | 1.85%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 9         | 1.52%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 8         | 1.35%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 8         | 1.35%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 8         | 1.35%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 1.18%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 7         | 1.18%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 6         | 1.01%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 6         | 1.01%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 5         | 0.84%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 5         | 0.84%   |
| Intel Iris Plus Graphics G7                                                              | 5         | 0.84%   |
| Nvidia GK107M [GeForce GT 640M]                                                          | 4         | 0.67%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 0.67%   |
| Intel HD Graphics 630                                                                    | 4         | 0.67%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 4         | 0.67%   |
| AMD Cezanne                                                                              | 4         | 0.67%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.51%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 3         | 0.51%   |
| Nvidia GM108M [GeForce 840M]                                                             | 3         | 0.51%   |
| Intel Tiger Lake UHD Graphics                                                            | 3         | 0.51%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 3         | 0.51%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 0.51%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 3         | 0.51%   |
| AMD RS480M [Mobility Radeon Xpress 200]                                                  | 3         | 0.51%   |
| AMD Lucienne                                                                             | 3         | 0.51%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 2         | 0.34%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.34%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 2         | 0.34%   |
| Nvidia GP108M [GeForce MX250]                                                            | 2         | 0.34%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.34%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 2         | 0.34%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 2         | 0.34%   |
| Nvidia GF119M [NVS 4200M]                                                                | 2         | 0.34%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.34%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 0.34%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                                 | 2         | 0.34%   |
| Nvidia C79 [GeForce 9400M G]                                                             | 2         | 0.34%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2         | 0.34%   |
| Intel HD Graphics 515                                                                    | 2         | 0.34%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 0.34%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.34%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 2         | 0.34%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 0.34%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 0.34%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 0.34%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 377       | 73.92%  |
| Intel + Nvidia | 53        | 10.39%  |
| 1 x AMD        | 46        | 9.02%   |
| 1 x Nvidia     | 14        | 2.75%   |
| Intel + AMD    | 11        | 2.16%   |
| AMD + Nvidia   | 5         | 0.98%   |
| 2 x AMD        | 3         | 0.59%   |
| Other          | 1         | 0.2%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 477       | 93.71%  |
| Proprietary | 28        | 5.5%    |
| Unknown     | 4         | 0.79%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 433       | 84.74%  |
| 0.01-0.5   | 34        | 6.65%   |
| 1.01-2.0   | 17        | 3.33%   |
| 0.51-1.0   | 15        | 2.94%   |
| 3.01-4.0   | 10        | 1.96%   |
| 7.01-8.0   | 1         | 0.2%    |
| 5.01-6.0   | 1         | 0.2%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Apple                   | 141       | 25%     |
| BOE                     | 91        | 16.13%  |
| AU Optronics            | 84        | 14.89%  |
| Chimei Innolux          | 60        | 10.64%  |
| LG Display              | 48        | 8.51%   |
| Samsung Electronics     | 28        | 4.96%   |
| Sharp                   | 16        | 2.84%   |
| Lenovo                  | 12        | 2.13%   |
| Dell                    | 11        | 1.95%   |
| InfoVision              | 8         | 1.42%   |
| Philips                 | 6         | 1.06%   |
| Hewlett-Packard         | 6         | 1.06%   |
| Ancor Communications    | 5         | 0.89%   |
| ViewSonic               | 4         | 0.71%   |
| Goldstar                | 4         | 0.71%   |
| Chi Mei Optoelectronics | 4         | 0.71%   |
| BenQ                    | 4         | 0.71%   |
| PANDA                   | 3         | 0.53%   |
| LG Philips              | 3         | 0.53%   |
| Unknown                 | 2         | 0.35%   |
| NEC Computers           | 2         | 0.35%   |
| HannStar                | 2         | 0.35%   |
| CPT                     | 2         | 0.35%   |
| AOC                     | 2         | 0.35%   |
| Acer                    | 2         | 0.35%   |
| ___                     | 1         | 0.18%   |
| Vestel Elektronik       | 1         | 0.18%   |
| Sony                    | 1         | 0.18%   |
| Quanta Display          | 1         | 0.18%   |
| NCS                     | 1         | 0.18%   |
| MSI                     | 1         | 0.18%   |
| LPL                     | 1         | 0.18%   |
| JXG                     | 1         | 0.18%   |
| JRY                     | 1         | 0.18%   |
| IOD                     | 1         | 0.18%   |
| CSO                     | 1         | 0.18%   |
| Compaq Computer         | 1         | 0.18%   |
| CMN                     | 1         | 0.18%   |
| ASUSTek Computer        | 1         | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                      | 39        | 6.87%   |
| Apple Color LCD APP9CF2 1366x768 260x140mm 11.6-inch                      | 34        | 5.99%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                      | 34        | 5.99%   |
| BOE LCD Monitor BOE0609 1366x768 256x144mm 11.6-inch                      | 30        | 5.28%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                      | 20        | 3.52%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch           | 10        | 1.76%   |
| AU Optronics LCD Monitor AUO235C 1366x768 260x140mm 11.6-inch             | 10        | 1.76%   |
| BOE LCD Monitor BOE06CF 1366x768 277x156mm 12.5-inch                      | 7         | 1.23%   |
| InfoVision LCD Monitor IVO0533 1366x768 293x164mm 13.2-inch               | 5         | 0.88%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch            | 5         | 0.88%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                   | 4         | 0.7%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 4         | 0.7%    |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch          | 4         | 0.7%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 4         | 0.7%    |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch             | 4         | 0.7%    |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch            | 4         | 0.7%    |
| Apple Color LCD APPA01B 1440x900 286x179mm 13.3-inch                      | 4         | 0.7%    |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch               | 3         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 3         | 0.53%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 3         | 0.53%   |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                      | 3         | 0.53%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 340x190mm 15.3-inch            | 3         | 0.53%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 3         | 0.53%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch            | 3         | 0.53%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch             | 3         | 0.53%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                   | 2         | 0.35%   |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch                   | 2         | 0.35%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch                   | 2         | 0.35%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 2         | 0.35%   |
| Samsung Electronics LCD Monitor SEC4351 1366x768 344x194mm 15.5-inch      | 2         | 0.35%   |
| LG Philips LCD Monitor LPL1151 1024x768 304x228mm 15.0-inch               | 2         | 0.35%   |
| LG Display LCD Monitor LGD064C 1920x1080 344x194mm 15.5-inch              | 2         | 0.35%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch              | 2         | 0.35%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch              | 2         | 0.35%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 2         | 0.35%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch              | 2         | 0.35%   |
| LG Display LCD Monitor LGD03A3 1366x768 277x156mm 12.5-inch               | 2         | 0.35%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                  | 2         | 0.35%   |
| Lenovo LCD Monitor LEN4036 1440x900 304x190mm 14.1-inch                   | 2         | 0.35%   |
| Hewlett-Packard LA2405 HWP284C 1920x1200 518x324mm 24.1-inch              | 2         | 0.35%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 2         | 0.35%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 2         | 0.35%   |
| Chimei Innolux LCD Monitor CMN1515 1920x1080 344x193mm 15.5-inch          | 2         | 0.35%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch          | 2         | 0.35%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch          | 2         | 0.35%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 0.35%   |
| BOE LCD Monitor BOE097D 1920x1080 344x194mm 15.5-inch                     | 2         | 0.35%   |
| BOE LCD Monitor BOE0903 1920x1080 344x194mm 15.5-inch                     | 2         | 0.35%   |
| BOE LCD Monitor BOE0868 1920x1080 309x174mm 14.0-inch                     | 2         | 0.35%   |
| BOE LCD Monitor BOE0718 1920x1080 309x173mm 13.9-inch                     | 2         | 0.35%   |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch                     | 2         | 0.35%   |
| BOE LCD Monitor BOE06CE 1366x768 277x156mm 12.5-inch                      | 2         | 0.35%   |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                     | 2         | 0.35%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch             | 2         | 0.35%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch             | 2         | 0.35%   |
| AU Optronics LCD Monitor AUO5C2D 1920x1080 293x165mm 13.2-inch            | 2         | 0.35%   |
| AU Optronics LCD Monitor AUO333D 1920x1080 309x174mm 14.0-inch            | 2         | 0.35%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch             | 2         | 0.35%   |
| AU Optronics LCD Monitor AUO223E 1600x900 309x174mm 14.0-inch             | 2         | 0.35%   |
| AU Optronics LCD Monitor AUO139D 1920x1080 381x214mm 17.2-inch            | 2         | 0.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 209       | 38.28%  |
| 1920x1080 (FHD)    | 171       | 31.32%  |
| 1440x900 (WXGA+)   | 63        | 11.54%  |
| 1280x800 (WXGA)    | 20        | 3.66%   |
| 1600x900 (HD+)     | 18        | 3.3%    |
| 3840x2160 (4K)     | 12        | 2.2%    |
| 1920x1200 (WUXGA)  | 11        | 2.01%   |
| 2560x1440 (QHD)    | 10        | 1.83%   |
| 1280x1024 (SXGA)   | 5         | 0.92%   |
| 1024x768 (XGA)     | 5         | 0.92%   |
| 1680x1050 (WSXGA+) | 3         | 0.55%   |
| 3840x1080          | 2         | 0.37%   |
| 3440x1440          | 2         | 0.37%   |
| 3200x1800 (QHD+)   | 2         | 0.37%   |
| 2880x1800          | 2         | 0.37%   |
| 1024x600           | 2         | 0.37%   |
| 3840x2400          | 1         | 0.18%   |
| 2880x1920          | 1         | 0.18%   |
| 2560x1600          | 1         | 0.18%   |
| 2288x1287          | 1         | 0.18%   |
| 2256x1504          | 1         | 0.18%   |
| 2160x1440          | 1         | 0.18%   |
| 1792x768           | 1         | 0.18%   |
| 1600x1200          | 1         | 0.18%   |
| Unknown            | 1         | 0.18%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 13      | 141       | 25.09%  |
| 11      | 129       | 22.95%  |
| 15      | 116       | 20.64%  |
| 14      | 53        | 9.43%   |
| 12      | 29        | 5.16%   |
| 17      | 22        | 3.91%   |
| 24      | 17        | 3.02%   |
| 21      | 10        | 1.78%   |
| 23      | 9         | 1.6%    |
| 27      | 6         | 1.07%   |
| 25      | 4         | 0.71%   |
| 19      | 3         | 0.53%   |
| 40      | 2         | 0.36%   |
| 34      | 2         | 0.36%   |
| 32      | 2         | 0.36%   |
| 31      | 2         | 0.36%   |
| 10      | 2         | 0.36%   |
| Unknown | 2         | 0.36%   |
| 142     | 1         | 0.18%   |
| 84      | 1         | 0.18%   |
| 72      | 1         | 0.18%   |
| 48      | 1         | 0.18%   |
| 47      | 1         | 0.18%   |
| 46      | 1         | 0.18%   |
| 33      | 1         | 0.18%   |
| 22      | 1         | 0.18%   |
| 20      | 1         | 0.18%   |
| 18      | 1         | 0.18%   |
| 16      | 1         | 0.18%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 201-300        | 256       | 45.63%  |
| 301-350        | 214       | 38.15%  |
| 501-600        | 32        | 5.7%    |
| 351-400        | 24        | 4.28%   |
| 401-500        | 16        | 2.85%   |
| 701-800        | 5         | 0.89%   |
| 601-700        | 4         | 0.71%   |
| 1001-1500      | 3         | 0.53%   |
| 801-900        | 2         | 0.36%   |
| 1501-2000      | 2         | 0.36%   |
| Unknown        | 2         | 0.36%   |
| More than 2000 | 1         | 0.18%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 400       | 76.63%  |
| 16/10   | 98        | 18.77%  |
| 4/3     | 7         | 1.34%   |
| 5/4     | 5         | 0.96%   |
| 3/2     | 5         | 0.96%   |
| 21/9    | 3         | 0.57%   |
| Unknown | 2         | 0.38%   |
| 32/9    | 1         | 0.19%   |
| 1.00    | 1         | 0.19%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 130       | 23.09%  |
| 51-60          | 129       | 22.91%  |
| 101-110        | 117       | 20.78%  |
| 71-80          | 65        | 11.55%  |
| 201-250        | 30        | 5.33%   |
| 61-70          | 27        | 4.8%    |
| 121-130        | 18        | 3.2%    |
| 251-300        | 9         | 1.6%    |
| 351-500        | 7         | 1.24%   |
| 301-350        | 6         | 1.07%   |
| 151-200        | 6         | 1.07%   |
| 141-150        | 5         | 0.89%   |
| 501-1000       | 5         | 0.89%   |
| More than 1000 | 3         | 0.53%   |
| 41-50          | 2         | 0.36%   |
| Unknown        | 2         | 0.36%   |
| 131-140        | 1         | 0.18%   |
| 91-100         | 1         | 0.18%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 371       | 66.85%  |
| 101-120       | 80        | 14.41%  |
| 51-100        | 63        | 11.35%  |
| 161-240       | 25        | 4.5%    |
| More than 240 | 9         | 1.62%   |
| 1-50          | 5         | 0.9%    |
| Unknown       | 2         | 0.36%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 439       | 86.25%  |
| 2     | 58        | 11.39%  |
| 3     | 6         | 1.18%   |
| 0     | 6         | 1.18%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 259       | 37.7%   |
| Realtek Semiconductor             | 147       | 21.4%   |
| Broadcom Limited                  | 140       | 20.38%  |
| Qualcomm Atheros                  | 60        | 8.73%   |
| Broadcom                          | 32        | 4.66%   |
| Marvell Technology Group          | 6         | 0.87%   |
| Sierra Wireless                   | 4         | 0.58%   |
| Nvidia                            | 4         | 0.58%   |
| Ericsson Business Mobile Networks | 4         | 0.58%   |
| Dell                              | 4         | 0.58%   |
| DisplayLink                       | 3         | 0.44%   |
| AMD                               | 3         | 0.44%   |
| TP-Link                           | 2         | 0.29%   |
| Ralink                            | 2         | 0.29%   |
| MEDIATEK                          | 2         | 0.29%   |
| Cypress Semiconductor             | 2         | 0.29%   |
| Xiaomi                            | 1         | 0.15%   |
| Ralink Technology                 | 1         | 0.15%   |
| Qualcomm Atheros Communications   | 1         | 0.15%   |
| Qualcomm                          | 1         | 0.15%   |
| Microchip Technology              | 1         | 0.15%   |
| Lenovo                            | 1         | 0.15%   |
| JMicron Technology                | 1         | 0.15%   |
| Huawei Technologies               | 1         | 0.15%   |
| Hewlett-Packard                   | 1         | 0.15%   |
| FIBOCOM                           | 1         | 0.15%   |
| Edimax Technology                 | 1         | 0.15%   |
| D-Link                            | 1         | 0.15%   |
| Attansic Technology               | 1         | 0.15%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 131       | 15.9%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 97        | 11.77%  |
| Intel Wireless 7260                                                     | 59        | 7.16%   |
| Intel Wireless 8265 / 8275                                              | 32        | 3.88%   |
| Intel Wi-Fi 6 AX200                                                     | 23        | 2.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 23        | 2.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 20        | 2.43%   |
| Intel Ethernet Connection (4) I219-V                                    | 18        | 2.18%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 17        | 2.06%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 15        | 1.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 14        | 1.7%    |
| Intel Wireless 7265                                                     | 12        | 1.46%   |
| Intel Wi-Fi 6 AX201                                                     | 11        | 1.33%   |
| Intel Wireless 8260                                                     | 10        | 1.21%   |
| Intel Ethernet Connection (4) I219-LM                                   | 10        | 1.21%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 10        | 1.21%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 9         | 1.09%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 8         | 0.97%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 8         | 0.97%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 8         | 0.97%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 0.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 7         | 0.85%   |
| Intel Ethernet Connection I218-LM                                       | 7         | 0.85%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 7         | 0.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 0.85%   |
| Intel Ethernet Connection I219-LM                                       | 6         | 0.73%   |
| Intel Ethernet Connection (3) I218-LM                                   | 6         | 0.73%   |
| Intel Centrino Wireless-N 2230                                          | 6         | 0.73%   |
| Intel Centrino Ultimate-N 6300                                          | 6         | 0.73%   |
| Intel Wireless 3165                                                     | 5         | 0.61%   |
| Intel Wireless 3160                                                     | 5         | 0.61%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 0.61%   |
| Intel 82577LM Gigabit Network Connection                                | 5         | 0.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 0.49%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                        | 4         | 0.49%   |
| Intel Wireless-AC 9260                                                  | 4         | 0.49%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 0.49%   |
| Intel Ethernet Connection (6) I219-V                                    | 4         | 0.49%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 0.49%   |
| Sierra Wireless EM7345 4G LTE                                           | 3         | 0.36%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 3         | 0.36%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 3         | 0.36%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 0.36%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 0.36%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller        | 3         | 0.36%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                  | 3         | 0.36%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 3         | 0.36%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 0.36%   |
| AMD IXP SB400 AC'97 Modem Controller                                    | 3         | 0.36%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 0.24%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 0.24%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.24%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 2         | 0.24%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 2         | 0.24%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 0.24%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 0.24%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 2         | 0.24%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 2         | 0.24%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.24%   |
| Nvidia MCP89 Ethernet                                                   | 2         | 0.24%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 254       | 49.03%  |
| Broadcom Limited                  | 136       | 26.25%  |
| Qualcomm Atheros                  | 53        | 10.23%  |
| Realtek Semiconductor             | 39        | 7.53%   |
| Broadcom                          | 19        | 3.67%   |
| Sierra Wireless                   | 4         | 0.77%   |
| Ralink                            | 2         | 0.39%   |
| MEDIATEK                          | 2         | 0.39%   |
| Dell                              | 2         | 0.39%   |
| TP-Link                           | 1         | 0.19%   |
| Ralink Technology                 | 1         | 0.19%   |
| Qualcomm Atheros Communications   | 1         | 0.19%   |
| Qualcomm                          | 1         | 0.19%   |
| FIBOCOM                           | 1         | 0.19%   |
| Ericsson Business Mobile Networks | 1         | 0.19%   |
| Edimax Technology                 | 1         | 0.19%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                  | 131       | 25.19%  |
| Intel Wireless 7260                                                         | 59        | 11.35%  |
| Intel Wireless 8265 / 8275                                                  | 32        | 6.15%   |
| Intel Wi-Fi 6 AX200                                                         | 23        | 4.42%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                  | 20        | 3.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                    | 15        | 2.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 14        | 2.69%   |
| Intel Wireless 7265                                                         | 12        | 2.31%   |
| Intel Wi-Fi 6 AX201                                                         | 11        | 2.12%   |
| Intel Wireless 8260                                                         | 10        | 1.92%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                           | 10        | 1.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 9         | 1.73%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 8         | 1.54%   |
| Intel Comet Lake PCH CNVi WiFi                                              | 8         | 1.54%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 7         | 1.35%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                  | 7         | 1.35%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                    | 7         | 1.35%   |
| Intel Cannon Lake PCH CNVi WiFi                                             | 7         | 1.35%   |
| Intel Centrino Wireless-N 2230                                              | 6         | 1.15%   |
| Intel Centrino Ultimate-N 6300                                              | 6         | 1.15%   |
| Intel Wireless 3165                                                         | 5         | 0.96%   |
| Intel Wireless 3160                                                         | 5         | 0.96%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 5         | 0.96%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 4         | 0.77%   |
| Intel Wireless-AC 9260                                                      | 4         | 0.77%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                             | 4         | 0.77%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                             | 4         | 0.77%   |
| Sierra Wireless EM7345 4G LTE                                               | 3         | 0.58%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                            | 3         | 0.58%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection               | 3         | 0.58%   |
| Intel Centrino Advanced-N 6200                                              | 3         | 0.58%   |
| Broadcom BCM43224 802.11a/b/g/n                                             | 3         | 0.58%   |
| Broadcom BCM43142 802.11b/g/n                                               | 3         | 0.58%   |
| Realtek RTL8723DE Wireless Network Adapter                                  | 2         | 0.38%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 2         | 0.38%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 2         | 0.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 2         | 0.38%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)              | 2         | 0.38%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)     | 2         | 0.38%   |
| MEDIATEK Network controller                                                 | 2         | 0.38%   |
| Intel Ultimate N WiFi Link 5300                                             | 2         | 0.38%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                   | 2         | 0.38%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                    | 2         | 0.38%   |
| Intel Centrino Advanced-N 6235                                              | 2         | 0.38%   |
| Broadcom Limited BCM4318 [AirForce 54g] 802.11a/b/g PCI Express Transceiver | 2         | 0.38%   |
| Broadcom BCM4331 802.11a/b/g/n                                              | 2         | 0.38%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                      | 2         | 0.38%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller         | 2         | 0.38%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                         | 2         | 0.38%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                  | 1         | 0.19%   |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A                         | 1         | 0.19%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                             | 1         | 0.19%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                     | 1         | 0.19%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                             | 1         | 0.19%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                    | 1         | 0.19%   |
| Realtek 802.11ac NIC                                                        | 1         | 0.19%   |
| Ralink RT5370 Wireless Adapter                                              | 1         | 0.19%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                   | 1         | 0.19%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                   | 1         | 0.19%   |
| Qualcomm QCA6390 Wireless Network Adapter [AX500-DBS (2x2)]                 | 1         | 0.19%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 128       | 44.76%  |
| Intel                    | 100       | 34.97%  |
| Broadcom                 | 17        | 5.94%   |
| Qualcomm Atheros         | 13        | 4.55%   |
| Marvell Technology Group | 6         | 2.1%    |
| Broadcom Limited         | 5         | 1.75%   |
| Nvidia                   | 4         | 1.4%    |
| DisplayLink              | 3         | 1.05%   |
| Cypress Semiconductor    | 2         | 0.7%    |
| Xiaomi                   | 1         | 0.35%   |
| TP-Link                  | 1         | 0.35%   |
| Microchip Technology     | 1         | 0.35%   |
| Lenovo                   | 1         | 0.35%   |
| JMicron Technology       | 1         | 0.35%   |
| Huawei Technologies      | 1         | 0.35%   |
| D-Link                   | 1         | 0.35%   |
| Attansic Technology      | 1         | 0.35%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 97        | 33.45%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 23        | 7.93%   |
| Intel Ethernet Connection (4) I219-V                              | 18        | 6.21%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 17        | 5.86%   |
| Intel Ethernet Connection (4) I219-LM                             | 10        | 3.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 2.76%   |
| Intel Ethernet Connection I218-LM                                 | 7         | 2.41%   |
| Intel Ethernet Connection I219-LM                                 | 6         | 2.07%   |
| Intel Ethernet Connection (3) I218-LM                             | 6         | 2.07%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 1.72%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 4         | 1.38%   |
| Intel Ethernet Connection (6) I219-V                              | 4         | 1.38%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 1.03%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 3         | 1.03%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.69%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.69%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.69%   |
| Nvidia MCP89 Ethernet                                             | 2         | 0.69%   |
| Nvidia MCP79 Ethernet                                             | 2         | 0.69%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.69%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.69%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 0.69%   |
| Intel Ethernet Connection (11) I219-LM                            | 2         | 0.69%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 0.69%   |
| Cypress K38231_03                                                 | 2         | 0.69%   |
| Broadcom NetXtreme BCM5788 Gigabit Ethernet                       | 2         | 0.69%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.69%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 0.69%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 0.69%   |
| Broadcom Limited BCM4401-B0 100Base-TX                            | 2         | 0.69%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 2         | 0.69%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.34%   |
| TP-Link USB 10/100/1000 LAN                                       | 1         | 0.34%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.34%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.34%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.34%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1         | 0.34%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.34%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.34%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.34%   |
| Microchip LAN9512/LAN9514 Ethernet 10/100 Adapter (SAL10)         | 1         | 0.34%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 0.34%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.34%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.34%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.34%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.34%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.34%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                  | 1         | 0.34%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.34%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.34%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.34%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.34%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.34%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 0.34%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 0.34%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.34%   |
| Intel Centrino Advanced-N + WiMAX 6250                            | 1         | 0.34%   |
| Intel 82801DB PRO/100 VM (MOB) Ethernet Controller                | 1         | 0.34%   |
| Intel 82577LC Gigabit Network Connection                          | 1         | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 502       | 63.38%  |
| Ethernet | 276       | 34.85%  |
| Modem    | 14        | 1.77%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 484       | 70.86%  |
| Ethernet | 197       | 28.84%  |
| Modem    | 2         | 0.29%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 254       | 50%     |
| 1     | 249       | 49.02%  |
| 3     | 5         | 0.98%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 444       | 87.23%  |
| Yes  | 65        | 12.77%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 193       | 43.57%  |
| Apple                           | 140       | 31.6%   |
| Realtek Semiconductor           | 26        | 5.87%   |
| Qualcomm Atheros Communications | 25        | 5.64%   |
| Broadcom                        | 17        | 3.84%   |
| Lite-On Technology              | 11        | 2.48%   |
| IMC Networks                    | 7         | 1.58%   |
| Foxconn / Hon Hai               | 6         | 1.35%   |
| Cambridge Silicon Radio         | 5         | 1.13%   |
| Hewlett-Packard                 | 4         | 0.9%    |
| Realtek                         | 3         | 0.68%   |
| Toshiba                         | 2         | 0.45%   |
| Dell                            | 2         | 0.45%   |
| Taiyo Yuden                     | 1         | 0.23%   |
| Ralink                          | 1         | 0.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Apple Bluetooth USB Host Controller                                                 | 131       | 29.57%  |
| Intel Bluetooth wireless interface                                                  | 112       | 25.28%  |
| Intel Bluetooth Device                                                              | 29        | 6.55%   |
| Intel AX200 Bluetooth                                                               | 24        | 5.42%   |
| Realtek Bluetooth Radio                                                             | 18        | 4.06%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 18        | 4.06%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 18        | 4.06%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 6         | 1.35%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 6         | 1.35%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 6         | 1.35%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 5         | 1.13%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 5         | 1.13%   |
| Apple Bluetooth Host Controller                                                     | 5         | 1.13%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 4         | 0.9%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 4         | 0.9%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 4         | 0.9%    |
| Foxconn / Hon Hai Bluetooth Device                                                  | 4         | 0.9%    |
| Realtek Bluetooth Radio                                                             | 3         | 0.68%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 0.68%   |
| Lite-On Bluetooth Device                                                            | 3         | 0.68%   |
| IMC Networks Bluetooth Radio                                                        | 3         | 0.68%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 3         | 0.68%   |
| Toshiba Bluetooth Device                                                            | 2         | 0.45%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 0.45%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 2         | 0.45%   |
| Apple Bluetooth HCI MacBookPro (HID mode)                                           | 2         | 0.45%   |
| Taiyo Yuden Bluetooth Device                                                        | 1         | 0.23%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.23%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.23%   |
| Realtek CSR BS8510                                                                  | 1         | 0.23%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.23%   |
| Lite-On Wireless_Device                                                             | 1         | 0.23%   |
| Lite-On BCM43142A0                                                                  | 1         | 0.23%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.23%   |
| IMC Networks Bluetooth module                                                       | 1         | 0.23%   |
| IMC Networks Bluetooth Device                                                       | 1         | 0.23%   |
| IMC Networks Bluetooth                                                              | 1         | 0.23%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.23%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.23%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth                                       | 1         | 0.23%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.23%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 0.23%   |
| Broadcom HP Portable SoftSailing                                                    | 1         | 0.23%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 0.23%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 1         | 0.23%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 1         | 0.23%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 1         | 0.23%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 455       | 79.13%  |
| AMD                    | 53        | 9.22%   |
| Nvidia                 | 42        | 7.3%    |
| Generalplus Technology | 5         | 0.87%   |
| Plantronics            | 3         | 0.52%   |
| Logitech               | 3         | 0.52%   |
| GN Netcom              | 3         | 0.52%   |
| C-Media Electronics    | 3         | 0.52%   |
| Texas Instruments      | 2         | 0.35%   |
| Creative Technology    | 2         | 0.35%   |
| SAVITECH               | 1         | 0.17%   |
| Razer USA              | 1         | 0.17%   |
| Lenovo                 | 1         | 0.17%   |
| CMX Systems            | 1         | 0.17%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 145       | 18.42%  |
| Intel Broadwell-U Audio Controller                                                                | 145       | 18.42%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 62        | 7.88%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 47        | 5.97%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 36        | 4.57%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 33        | 4.19%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 21        | 2.67%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 20        | 2.54%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 18        | 2.29%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 15        | 1.91%   |
| Intel 8 Series HD Audio Controller                                                                | 15        | 1.91%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 14        | 1.78%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 13        | 1.65%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 12        | 1.52%   |
| Intel Comet Lake PCH cAVS                                                                         | 10        | 1.27%   |
| Intel Cannon Lake PCH cAVS                                                                        | 10        | 1.27%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 9         | 1.14%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 9         | 1.14%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 9         | 1.14%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 9         | 1.14%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 7         | 0.89%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 7         | 0.89%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 7         | 0.89%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 0.76%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 6         | 0.76%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 0.64%   |
| Generalplus Technology USB Audio Device                                                           | 5         | 0.64%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 0.64%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 0.51%   |
| Intel CM238 HD Audio Controller                                                                   | 4         | 0.51%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4         | 0.51%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 3         | 0.38%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.38%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 3         | 0.38%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 0.38%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 0.38%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller                        | 3         | 0.38%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 3         | 0.38%   |
| AMD IXP SB400 AC'97 Audio Controller                                                              | 3         | 0.38%   |
| Texas Instruments PCM2912A Audio Codec                                                            | 2         | 0.25%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.25%   |
| Nvidia MCP89 High Definition Audio                                                                | 2         | 0.25%   |
| Nvidia MCP79 High Definition Audio                                                                | 2         | 0.25%   |
| Nvidia Audio device                                                                               | 2         | 0.25%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.25%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 2         | 0.25%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 0.25%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 0.25%   |
| AMD High Definition Audio Controller                                                              | 2         | 0.25%   |
| AMD FCH Azalia Controller                                                                         | 2         | 0.25%   |
| SAVITECH SA9023 audio controller                                                                  | 1         | 0.13%   |
| Razer USA Razer Thresher 7.1                                                                      | 1         | 0.13%   |
| Plantronics DA40                                                                                  | 1         | 0.13%   |
| Plantronics Blackwire 3225 Series                                                                 | 1         | 0.13%   |
| Plantronics Blackwire 315.1                                                                       | 1         | 0.13%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.13%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.13%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 0.13%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.13%   |
| Logitech [G533 Wireless Headset Dongle]                                                           | 1         | 0.13%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Samsung Electronics    | 195       | 36.18%  |
| SK Hynix               | 108       | 20.04%  |
| Elpida                 | 47        | 8.72%   |
| Micron Technology      | 46        | 8.53%   |
| Crucial                | 35        | 6.49%   |
| Kingston               | 32        | 5.94%   |
| Unknown                | 24        | 4.45%   |
| A-DATA Technology      | 10        | 1.86%   |
| Ramaxel Technology     | 9         | 1.67%   |
| Corsair                | 7         | 1.3%    |
| Nanya Technology       | 6         | 1.11%   |
| Team                   | 3         | 0.56%   |
| Smart                  | 2         | 0.37%   |
| PNY                    | 2         | 0.37%   |
| GOODRAM                | 2         | 0.37%   |
| Wilk                   | 1         | 0.19%   |
| Unknown (ABCD)         | 1         | 0.19%   |
| Unknown (0080000080AD) | 1         | 0.19%   |
| Unifosa                | 1         | 0.19%   |
| SMART Brazil           | 1         | 0.19%   |
| Silicon Power          | 1         | 0.19%   |
| Sesame                 | 1         | 0.19%   |
| Kllisre                | 1         | 0.19%   |
| Infineon               | 1         | 0.19%   |
| G.Skill                | 1         | 0.19%   |
| AMD                    | 1         | 0.19%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                         | 59        | 10.55%  |
| Samsung RAM M471B5674QH0-YK0 2048MB SODIMM DDR3 1600MT/s            | 36        | 6.44%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                          | 27        | 4.83%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                        | 19        | 3.4%    |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                         | 14        | 2.5%    |
| Elpida RAM Module 2GB SODIMM DDR3 1600MT/s                          | 14        | 2.5%    |
| Crucial RAM CT8G4SFS824A.M8FE 8GB SODIMM DDR4 2667MT/s              | 13        | 2.33%   |
| Micron RAM 4KTF25664HZ-1G6E 2GB SODIMM DDR3 1333MT/s                | 10        | 1.79%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s           | 6         | 1.07%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 6         | 1.07%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 5         | 0.89%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 5         | 0.89%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 4         | 0.72%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 4         | 0.72%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s               | 4         | 0.72%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s            | 4         | 0.72%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 2667MT/s            | 4         | 0.72%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s            | 4         | 0.72%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s            | 4         | 0.72%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB SODIMM DDR4 3200MT/s             | 4         | 0.72%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 3         | 0.54%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 0.54%   |
| SK Hynix RAM HMA82GS6CJR8N-VK 16384MB SODIMM DDR4 2667MT/s          | 3         | 0.54%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 3         | 0.54%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2133MT/s              | 3         | 0.54%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 3         | 0.54%   |
| Samsung RAM Module 1GB SODIMM DDR2 533MT/s                          | 3         | 0.54%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 3         | 0.54%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 3         | 0.54%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                | 3         | 0.54%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s                | 3         | 0.54%   |
| Kingston RAM 99U5469-046.A00LF 4096MB SODIMM DDR3 1333MT/s          | 3         | 0.54%   |
| Crucial RAM CT102464BF160B.M16 8192MB SODIMM DDR3 1600MT/s          | 3         | 0.54%   |
| Unknown RAM Module 512MB SODIMM DDR2 400MT/s                        | 2         | 0.36%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                         | 2         | 0.36%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                         | 2         | 0.36%   |
| Unknown RAM Module 4GB SODIMM DDR3                                  | 2         | 0.36%   |
| Unknown RAM Module 1GB SODIMM SDRAM                                 | 2         | 0.36%   |
| SK Hynix RAM Module 1GB SODIMM DDR2 800MT/s                         | 2         | 0.36%   |
| SK Hynix RAM Module 1GB SODIMM DDR2 667MT/s                         | 2         | 0.36%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s              | 2         | 0.36%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 2         | 0.36%   |
| SK Hynix RAM HMT325S6CFR8C-PB 2048MB SODIMM DDR3 1600MT/s           | 2         | 0.36%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s              | 2         | 0.36%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s        | 2         | 0.36%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s             | 2         | 0.36%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8192MB SODIMM DDR4 2667MT/s           | 2         | 0.36%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 2         | 0.36%   |
| SK Hynix RAM HMA81GS6DJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 2         | 0.36%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 2         | 0.36%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 2         | 0.36%   |
| Samsung RAM M471A2K43DB1-CWE 16384MB SODIMM DDR4 3200MT/s           | 2         | 0.36%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s              | 2         | 0.36%   |
| Samsung RAM M471A1K43DB1-CTD 8192MB SODIMM DDR4 2667MT/s            | 2         | 0.36%   |
| Samsung RAM M4 70L6524CU0-CB3 512MB SODIMM DDR 333MT/s              | 2         | 0.36%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s           | 2         | 0.36%   |
| Nanya RAM NT512D64SH8B0GN-6K 512MB SODIMM DDR 333MT/s               | 2         | 0.36%   |
| Micron RAM MT52L512M32D2PF-09 4GB Row Of Chips LPDDR3 2133MT/s      | 2         | 0.36%   |
| Micron RAM Module 8GB SODIMM DDR4 2133MT/s                          | 2         | 0.36%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s         | 2         | 0.36%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 281       | 57.7%   |
| DDR4   | 150       | 30.8%   |
| DDR2   | 19        | 3.9%    |
| LPDDR3 | 17        | 3.49%   |
| LPDDR4 | 9         | 1.85%   |
| DDR    | 7         | 1.44%   |
| SDRAM  | 3         | 0.62%   |
| DRAM   | 1         | 0.21%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 456       | 93.25%  |
| Row Of Chips | 28        | 5.73%   |
| Chip         | 4         | 0.82%   |
| Unknown      | 1         | 0.2%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 164       | 32.03%  |
| 2048  | 147       | 28.71%  |
| 8192  | 119       | 23.24%  |
| 16384 | 45        | 8.79%   |
| 1024  | 21        | 4.1%    |
| 32768 | 8         | 1.56%   |
| 512   | 6         | 1.17%   |
| 256   | 2         | 0.39%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 240       | 47.34%  |
| 2667    | 79        | 15.58%  |
| 3200    | 48        | 9.47%   |
| 2400    | 25        | 4.93%   |
| 1333    | 25        | 4.93%   |
| 2133    | 21        | 4.14%   |
| 1334    | 20        | 3.94%   |
| 667     | 10        | 1.97%   |
| 1867    | 8         | 1.58%   |
| Unknown | 6         | 1.18%   |
| 533     | 5         | 0.99%   |
| 4267    | 4         | 0.79%   |
| 333     | 4         | 0.79%   |
| 1067    | 3         | 0.59%   |
| 400     | 3         | 0.59%   |
| 800     | 2         | 0.39%   |
| 4266    | 1         | 0.2%    |
| 4199    | 1         | 0.2%    |
| 1866    | 1         | 0.2%    |
| 975     | 1         | 0.2%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 50%     |
| Brother Industries  | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Samsung ML-2010P Mono Laser Printer | 1         | 50%     |
| Brother MFC-L2707DW                 | 1         | 50%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 1         | 50%     |
| Seiko Epson GT-7700U [Perfection 1240U]       | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 83        | 25.23%  |
| Quanta                                 | 50        | 15.2%   |
| IMC Networks                           | 40        | 12.16%  |
| Acer                                   | 35        | 10.64%  |
| Realtek Semiconductor                  | 27        | 8.21%   |
| Microdia                               | 22        | 6.69%   |
| Lite-On Technology                     | 11        | 3.34%   |
| Sunplus Innovation Technology          | 10        | 3.04%   |
| Suyin                                  | 8         | 2.43%   |
| Logitech                               | 6         | 1.82%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 1.82%   |
| Apple                                  | 6         | 1.82%   |
| Syntek                                 | 5         | 1.52%   |
| Luxvisions Innotech Limited            | 5         | 1.52%   |
| Lenovo                                 | 4         | 1.22%   |
| Silicon Motion                         | 2         | 0.61%   |
| Z-Star Microelectronics                | 1         | 0.3%    |
| Ricoh                                  | 1         | 0.3%    |
| Primax Electronics                     | 1         | 0.3%    |
| Pixart Imaging                         | 1         | 0.3%    |
| eMPIA Technology                       | 1         | 0.3%    |
| ALi                                    | 1         | 0.3%    |
| Alcor Micro                            | 1         | 0.3%    |
| A4Tech                                 | 1         | 0.3%    |
| 8SSC20F27114V1SR11K1SE2                | 1         | 0.3%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Quanta Chromebook HD Camera                         | 37        | 11.18%  |
| Chicony Integrated Camera                           | 33        | 9.97%   |
| Microdia Integrated_Webcam_HD                       | 13        | 3.93%   |
| IMC Networks Integrated Camera                      | 13        | 3.93%   |
| Realtek Integrated_Webcam_HD                        | 12        | 3.63%   |
| Acer Integrated Camera                              | 12        | 3.63%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 10        | 3.02%   |
| Chicony HD Webcam                                   | 10        | 3.02%   |
| Chicony Chromebook HD Camera                        | 10        | 3.02%   |
| Acer SunplusIT Integrated Camera                    | 7         | 2.11%   |
| Chicony HP HD Camera                                | 6         | 1.81%   |
| Lite-On Integrated Camera                           | 4         | 1.21%   |
| Syntek Integrated Camera                            | 3         | 0.91%   |
| Sunplus Integrated_Webcam_HD                        | 3         | 0.91%   |
| Realtek Integrated Webcam                           | 3         | 0.91%   |
| Quanta HD WebCam                                    | 3         | 0.91%   |
| Microdia Integrated Webcam HD                       | 3         | 0.91%   |
| Lite-On HP HD Camera                                | 3         | 0.91%   |
| Lenovo Integrated Webcam                            | 3         | 0.91%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 3         | 0.91%   |
| IMC Networks HP TrueVision HD Camera                | 3         | 0.91%   |
| Chicony USB2.0 Camera                               | 3         | 0.91%   |
| Chicony Integrated Camera (1280x720@30)             | 3         | 0.91%   |
| Acer ThinkPad Integrated Camera                     | 3         | 0.91%   |
| Acer Lenovo EasyCamera                              | 3         | 0.91%   |
| Acer EasyCamera                                     | 3         | 0.91%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 2         | 0.6%    |
| Sunplus HP Universal Camera                         | 2         | 0.6%    |
| Realtek USB Camera                                  | 2         | 0.6%    |
| Realtek Integrated Webcam_HD                        | 2         | 0.6%    |
| Quanta HP Webcam                                    | 2         | 0.6%    |
| Quanta HP TrueVision HD Camera                      | 2         | 0.6%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 2         | 0.6%    |
| Luxvisions Innotech Limited HP HD Camera            | 2         | 0.6%    |
| Logitech Webcam C270                                | 2         | 0.6%    |
| Logitech C505 HD Webcam                             | 2         | 0.6%    |
| Lite-On HP Webcam                                   | 2         | 0.6%    |
| IMC Networks UVC VGA Webcam                         | 2         | 0.6%    |
| IMC Networks USB2.0 HD IR UVC WebCam                | 2         | 0.6%    |
| IMC Networks ov9734_azurewave_camera                | 2         | 0.6%    |
| IMC Networks Lenovo EasyCamera                      | 2         | 0.6%    |
| Chicony ThinkPad T490 Webcam                        | 2         | 0.6%    |
| Chicony Lenovo EasyCamera                           | 2         | 0.6%    |
| Chicony HP HD Webcam                                | 2         | 0.6%    |
| Apple FaceTime HD Camera                            | 2         | 0.6%    |
| Apple Built-in iSight                               | 2         | 0.6%    |
| Acer SunplusIT INC. Integrated Camera               | 2         | 0.6%    |
| Acer BisonCam, NB Pro                               | 2         | 0.6%    |
| Z-Star Sirius USB2.0 Camera                         | 1         | 0.3%    |
| Syntek USB 2.0 UVC PC Camera                        | 1         | 0.3%    |
| Syntek Lenovo EasyCamera                            | 1         | 0.3%    |
| Suyin Sony Visual Communication Camera              | 1         | 0.3%    |
| Suyin Laptop_Integrated_Webcam_HD                   | 1         | 0.3%    |
| Suyin HP TrueVision HD Integrated Webcam            | 1         | 0.3%    |
| Suyin HP TrueVision Full HD                         | 1         | 0.3%    |
| Suyin HD WebCam                                     | 1         | 0.3%    |
| Suyin Acer CrystalEye Webcam                        | 1         | 0.3%    |
| Sunplus Laptop_Integrated_Webcam_HD                 | 1         | 0.3%    |
| Sunplus Laptop_Integrated_Webcam_FHD                | 1         | 0.3%    |
| Sunplus Laptop Integrated Webcam FHD                | 1         | 0.3%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 30        | 37.97%  |
| Synaptics                  | 20        | 25.32%  |
| Shenzhen Goodix Technology | 11        | 13.92%  |
| Upek                       | 7         | 8.86%   |
| AuthenTec                  | 5         | 6.33%   |
| Elan Microelectronics      | 4         | 5.06%   |
| LighTuning Technology      | 2         | 2.53%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader                                | 13        | 16.46%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 9         | 11.39%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 8         | 10.13%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 7         | 8.86%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 7.59%   |
| Shenzhen Goodix  FingerPrint Device                                        | 6         | 7.59%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 5.06%   |
| Shenzhen Goodix FingerPrint                                                | 4         | 5.06%   |
| Elan ELAN:Fingerprint                                                      | 4         | 5.06%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 4         | 5.06%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 3.8%    |
| Validity Sensors Synaptics WBDI                                            | 2         | 2.53%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 2.53%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 2.53%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 1.27%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 1.27%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.27%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 1.27%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 1.27%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 13        | 36.11%  |
| Broadcom    | 11        | 30.56%  |
| Lenovo      | 5         | 13.89%  |
| Upek        | 4         | 11.11%  |
| OmniKey     | 1         | 2.78%   |
| O2 Micro    | 1         | 2.78%   |
| Cherry      | 1         | 2.78%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 13        | 36.11%  |
| Lenovo Integrated Smart Card Reader                                          | 5         | 13.89%  |
| Broadcom 5880                                                                | 5         | 13.89%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 11.11%  |
| Broadcom 58200                                                               | 3         | 8.33%   |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 5.56%   |
| OmniKey CardMan 4321                                                         | 1         | 2.78%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 2.78%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 2.78%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 2.78%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 256       | 50.1%   |
| 1     | 219       | 42.86%  |
| 2     | 34        | 6.65%   |
| 4     | 1         | 0.2%    |
| 3     | 1         | 0.2%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Multimedia controller    | 137       | 47.24%  |
| Fingerprint reader       | 79        | 27.24%  |
| Chipcard                 | 30        | 10.34%  |
| Graphics card            | 20        | 6.9%    |
| Net/wireless             | 8         | 2.76%   |
| Communication controller | 5         | 1.72%   |
| Storage                  | 3         | 1.03%   |
| Network                  | 2         | 0.69%   |
| Card reader              | 2         | 0.69%   |
| Bluetooth                | 2         | 0.69%   |
| Modem                    | 1         | 0.34%   |
| Firewire controller      | 1         | 0.34%   |

