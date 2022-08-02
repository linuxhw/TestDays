Zorin 15 - Tested Hardware & Statistics
---------------------------------------

A project to collect tested hardware configurations for Zorin 15.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Zorin_15/Desktop/README.md) and [notebooks](/Dist/Zorin_15/Notebook/README.md).

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

Total: 2338

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | Compaq 6730s                | Notebook    | [5d805b2f5e](https://linux-hardware.org/?probe=5d805b2f5e) | Jul 31, 2022 |
| Dell          | Inspiron 1525               | Notebook    | [f1af5f5e45](https://linux-hardware.org/?probe=f1af5f5e45) | Jul 22, 2022 |
| Dell          | Inspiron 1525               | Notebook    | [6c43e1dfd6](https://linux-hardware.org/?probe=6c43e1dfd6) | Jul 22, 2022 |
| Dell          | MXG061                      | Notebook    | [9301162b93](https://linux-hardware.org/?probe=9301162b93) | Jul 18, 2022 |
| HP            | ENVY 17                     | Notebook    | [bc1e8b41a5](https://linux-hardware.org/?probe=bc1e8b41a5) | Jul 17, 2022 |
| HP            | Compaq nx6310 (EY589ES#A... | Notebook    | [613395d2cf](https://linux-hardware.org/?probe=613395d2cf) | Jul 13, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [9e604c2dcc](https://linux-hardware.org/?probe=9e604c2dcc) | Jul 12, 2022 |
| Fujitsu Si... | AMILO L Series              | Notebook    | [410cd1aeec](https://linux-hardware.org/?probe=410cd1aeec) | Jul 08, 2022 |
| Lenovo        | ThinkPad E570 20H50047US    | Notebook    | [f11f4826ba](https://linux-hardware.org/?probe=f11f4826ba) | Jul 08, 2022 |
| Lenovo        | ThinkPad E570 20H50047US    | Notebook    | [50e02d8554](https://linux-hardware.org/?probe=50e02d8554) | Jul 08, 2022 |
| ASUSTek       | K70IC                       | Notebook    | [baa2ddeb5a](https://linux-hardware.org/?probe=baa2ddeb5a) | Jul 08, 2022 |
| Lenovo        | 3098 0B98401 PRO            | Desktop     | [830b5c1c8d](https://linux-hardware.org/?probe=830b5c1c8d) | Jul 07, 2022 |
| ASUSTek       | M3A78-EM                    | Desktop     | [426bb60e88](https://linux-hardware.org/?probe=426bb60e88) | Jul 04, 2022 |
| Gigabyte      | EP45-DS3                    | Desktop     | [bc316ca4cb](https://linux-hardware.org/?probe=bc316ca4cb) | Jul 02, 2022 |
| ASUSTek       | ZenBook UX392FN_UX392FN     | Notebook    | [b4699ba106](https://linux-hardware.org/?probe=b4699ba106) | Jun 30, 2022 |
| Dell          | 0HJ054                      | Desktop     | [bb9d7a3a58](https://linux-hardware.org/?probe=bb9d7a3a58) | Jun 30, 2022 |
| Dell          | Latitude E6400              | Notebook    | [df93b48c3c](https://linux-hardware.org/?probe=df93b48c3c) | Jun 28, 2022 |
| Lenovo        | 3098 0B98401 PRO            | Desktop     | [9923c241d9](https://linux-hardware.org/?probe=9923c241d9) | Jun 27, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [57d9c7c28a](https://linux-hardware.org/?probe=57d9c7c28a) | Jun 24, 2022 |
| Dell          | Latitude E6400              | Notebook    | [6198dd2784](https://linux-hardware.org/?probe=6198dd2784) | Jun 22, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [551da1dbb6](https://linux-hardware.org/?probe=551da1dbb6) | Jun 20, 2022 |
| Foxconn       | Irvine HP P/N               | Desktop     | [551f18d133](https://linux-hardware.org/?probe=551f18d133) | Jun 11, 2022 |
| MSI           | Z97 XPOWER AC               | Desktop     | [dd5c7a981a](https://linux-hardware.org/?probe=dd5c7a981a) | May 29, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [293f5586bd](https://linux-hardware.org/?probe=293f5586bd) | May 25, 2022 |
| Acer          | TravelMate 5320             | Notebook    | [4d7e13024d](https://linux-hardware.org/?probe=4d7e13024d) | May 19, 2022 |
| Dell          | 08HPGT A01                  | Desktop     | [aa8b5a4aec](https://linux-hardware.org/?probe=aa8b5a4aec) | May 17, 2022 |
| Dell          | 08HPGT A01                  | Desktop     | [4b277b05bb](https://linux-hardware.org/?probe=4b277b05bb) | May 17, 2022 |
| HP            | 2ADE                        | Desktop     | [77c2ea750b](https://linux-hardware.org/?probe=77c2ea750b) | May 17, 2022 |
| HP            | Pavilion 17                 | Notebook    | [a3f1fe480c](https://linux-hardware.org/?probe=a3f1fe480c) | May 14, 2022 |
| Foxconn       | LIMA                        | Desktop     | [fc4662a00e](https://linux-hardware.org/?probe=fc4662a00e) | May 09, 2022 |
| Maxtone       | HIS-G41L V1.1               | Desktop     | [ce61ffd777](https://linux-hardware.org/?probe=ce61ffd777) | May 02, 2022 |
| Maxtone       | HIS-G41L V1.1               | Desktop     | [63fc1199bc](https://linux-hardware.org/?probe=63fc1199bc) | May 01, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [5d02fb20c7](https://linux-hardware.org/?probe=5d02fb20c7) | Apr 29, 2022 |
| Lenovo        | ThinkPad L412 440332U       | Notebook    | [6616ce20ee](https://linux-hardware.org/?probe=6616ce20ee) | Apr 28, 2022 |
| MSI           | MS-6701                     | Desktop     | [8853d92523](https://linux-hardware.org/?probe=8853d92523) | Apr 26, 2022 |
| MSI           | MS-6701                     | Desktop     | [0bde2af604](https://linux-hardware.org/?probe=0bde2af604) | Apr 26, 2022 |
| Acer          | Aspire 9410                 | Notebook    | [f6c795c09a](https://linux-hardware.org/?probe=f6c795c09a) | Apr 20, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [9b742eb785](https://linux-hardware.org/?probe=9b742eb785) | Apr 20, 2022 |
| HP            | Notebook                    | Notebook    | [b746d96b41](https://linux-hardware.org/?probe=b746d96b41) | Apr 19, 2022 |
| Dell          | Latitude E6410              | Notebook    | [391866815a](https://linux-hardware.org/?probe=391866815a) | Apr 17, 2022 |
| Packard Be... | EasyNote TN36               | Notebook    | [23936e29bb](https://linux-hardware.org/?probe=23936e29bb) | Apr 15, 2022 |
| Packard Be... | EasyNote TN36               | Notebook    | [ae514187f2](https://linux-hardware.org/?probe=ae514187f2) | Apr 15, 2022 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [d6463e4014](https://linux-hardware.org/?probe=d6463e4014) | Apr 14, 2022 |
| Pegatron      | 2A99h                       | Desktop     | [0d208bc673](https://linux-hardware.org/?probe=0d208bc673) | Apr 13, 2022 |
| Pegatron      | 2A99h                       | Desktop     | [7a31392de4](https://linux-hardware.org/?probe=7a31392de4) | Apr 13, 2022 |
| HP            | Presario C500 (GF852EA#A... | Notebook    | [b14e9c5694](https://linux-hardware.org/?probe=b14e9c5694) | Apr 08, 2022 |
| Lenovo        | ThinkPad R61 8933W4F        | Notebook    | [4864fcdfa0](https://linux-hardware.org/?probe=4864fcdfa0) | Apr 07, 2022 |
| Gigabyte      | 945PL-S3                    | Desktop     | [ef7f30cc40](https://linux-hardware.org/?probe=ef7f30cc40) | Apr 07, 2022 |
| ECS           | Livermore                   | Desktop     | [afafdb72a7](https://linux-hardware.org/?probe=afafdb72a7) | Apr 06, 2022 |
| ECS           | Livermore                   | Desktop     | [d801396140](https://linux-hardware.org/?probe=d801396140) | Apr 02, 2022 |
| ASUSTek       | P5GD1 PRO                   | Desktop     | [9156c67116](https://linux-hardware.org/?probe=9156c67116) | Apr 01, 2022 |
| Biostar       | P4M90-M7A Ver:1.0           | Desktop     | [9cd4056356](https://linux-hardware.org/?probe=9cd4056356) | Mar 28, 2022 |
| Panasonic     | CF-31ACJAXPM                | Notebook    | [c90a918208](https://linux-hardware.org/?probe=c90a918208) | Mar 28, 2022 |
| ASUSTek       | K70IC                       | Notebook    | [25066676e9](https://linux-hardware.org/?probe=25066676e9) | Mar 28, 2022 |
| ASUSTek       | K70IC                       | Notebook    | [977e15d60c](https://linux-hardware.org/?probe=977e15d60c) | Mar 28, 2022 |
| Acer          | Aspire 3690                 | Notebook    | [76139c48e8](https://linux-hardware.org/?probe=76139c48e8) | Mar 25, 2022 |
| Biostar       | P4M90-M7A Ver:1.0           | Desktop     | [fc2b611797](https://linux-hardware.org/?probe=fc2b611797) | Mar 25, 2022 |
| BGH e-Nova    | Unknown                     | Notebook    | [408be10e82](https://linux-hardware.org/?probe=408be10e82) | Mar 22, 2022 |
| Acer          | Unknown                     | Notebook    | [3c80f8700c](https://linux-hardware.org/?probe=3c80f8700c) | Mar 19, 2022 |
| Toshiba       | Satellite M505              | Notebook    | [924c539075](https://linux-hardware.org/?probe=924c539075) | Mar 12, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [ad5413d163](https://linux-hardware.org/?probe=ad5413d163) | Mar 06, 2022 |
| HP            | ProBook 445 G7              | Notebook    | [b0b810cf14](https://linux-hardware.org/?probe=b0b810cf14) | Mar 04, 2022 |
| Lenovo        | ThinkCentre M91p 4524WAP    | Desktop     | [1d01e4616b](https://linux-hardware.org/?probe=1d01e4616b) | Mar 03, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [a94729eaf7](https://linux-hardware.org/?probe=a94729eaf7) | Mar 01, 2022 |
| HP            | 255 G5                      | Notebook    | [050e7b02e7](https://linux-hardware.org/?probe=050e7b02e7) | Feb 28, 2022 |
| Gigabyte      | GA-990FXA-D3                | Desktop     | [67943c7786](https://linux-hardware.org/?probe=67943c7786) | Feb 27, 2022 |
| Gigabyte      | GA-990FXA-D3                | Desktop     | [badbd8817c](https://linux-hardware.org/?probe=badbd8817c) | Feb 27, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [d5c0be1b13](https://linux-hardware.org/?probe=d5c0be1b13) | Feb 27, 2022 |
| ASUSTek       | S500CA                      | Notebook    | [db6a143f17](https://linux-hardware.org/?probe=db6a143f17) | Feb 27, 2022 |
| Fujitsu       | FARQ0200GZ                  | Notebook    | [a309120953](https://linux-hardware.org/?probe=a309120953) | Feb 26, 2022 |
| ASUSTek       | S500CA                      | Notebook    | [d8941a4a85](https://linux-hardware.org/?probe=d8941a4a85) | Feb 25, 2022 |
| IBM           | 819046G                     | Desktop     | [54b0798b76](https://linux-hardware.org/?probe=54b0798b76) | Feb 22, 2022 |
| HP            | 2140                        | Notebook    | [ad18e8d0b3](https://linux-hardware.org/?probe=ad18e8d0b3) | Feb 22, 2022 |
| HP            | 2140                        | Notebook    | [e0757f087f](https://linux-hardware.org/?probe=e0757f087f) | Feb 22, 2022 |
| Sony          | VPCEH3L1E                   | Notebook    | [4fa6aebb55](https://linux-hardware.org/?probe=4fa6aebb55) | Feb 21, 2022 |
| HP            | Notebook                    | Notebook    | [aee3f5ce0b](https://linux-hardware.org/?probe=aee3f5ce0b) | Feb 18, 2022 |
| ATI           | BONEFISH                    | Notebook    | [caa7c41c75](https://linux-hardware.org/?probe=caa7c41c75) | Feb 17, 2022 |
| Lenovo        | ThinkPad T61 6458CTO        | Notebook    | [9081d7a51d](https://linux-hardware.org/?probe=9081d7a51d) | Feb 17, 2022 |
| Lenovo        | ThinkPad T61 6458CTO        | Notebook    | [4f0437053f](https://linux-hardware.org/?probe=4f0437053f) | Feb 17, 2022 |
| Acer          | K8VM800MAE                  | Desktop     | [e4505f1541](https://linux-hardware.org/?probe=e4505f1541) | Feb 17, 2022 |
| Acer          | K8VM800MAE                  | Desktop     | [ac2f1dab87](https://linux-hardware.org/?probe=ac2f1dab87) | Feb 17, 2022 |
| ASUSTek       | A88XM-PLUS                  | Desktop     | [3a6147e5db](https://linux-hardware.org/?probe=3a6147e5db) | Feb 16, 2022 |
| HP            | Compaq 6910p (GR670ET#UU... | Notebook    | [f21dcf572e](https://linux-hardware.org/?probe=f21dcf572e) | Feb 13, 2022 |
| HP            | Compaq 6910p (GR670ET#UU... | Notebook    | [7f07e2a9da](https://linux-hardware.org/?probe=7f07e2a9da) | Feb 13, 2022 |
| Dell          | Inspiron 1525               | Notebook    | [3db88da0ec](https://linux-hardware.org/?probe=3db88da0ec) | Feb 13, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [feafacf00d](https://linux-hardware.org/?probe=feafacf00d) | Feb 13, 2022 |
| HP            | 255 G5                      | Notebook    | [a030b8f406](https://linux-hardware.org/?probe=a030b8f406) | Feb 13, 2022 |
| HP            | Compaq 6530b (NA755ES#AB... | Notebook    | [5bc4fdcfb0](https://linux-hardware.org/?probe=5bc4fdcfb0) | Feb 13, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [00d31012f1](https://linux-hardware.org/?probe=00d31012f1) | Feb 12, 2022 |
| Dell          | 0GM819                      | Desktop     | [bdd485de00](https://linux-hardware.org/?probe=bdd485de00) | Feb 10, 2022 |
| Acer          | Aspire 5600                 | Notebook    | [35dd7239e3](https://linux-hardware.org/?probe=35dd7239e3) | Feb 06, 2022 |
| Acer          | Aspire 5600                 | Notebook    | [4d2723a19e](https://linux-hardware.org/?probe=4d2723a19e) | Feb 06, 2022 |
| ASUSTek       | H110M-CS/BR                 | Desktop     | [f4319bd379](https://linux-hardware.org/?probe=f4319bd379) | Feb 05, 2022 |
| Dell          | 0DN075                      | Desktop     | [eb385877ae](https://linux-hardware.org/?probe=eb385877ae) | Feb 05, 2022 |
| Gigabyte      | H81M-S2V                    | Desktop     | [4c9a0cdddb](https://linux-hardware.org/?probe=4c9a0cdddb) | Feb 03, 2022 |
| BenQ          | Joybook Lite U121           | Notebook    | [28f254dd8d](https://linux-hardware.org/?probe=28f254dd8d) | Feb 02, 2022 |
| Toshiba       | Satellite Pro C660          | Notebook    | [8be575e86a](https://linux-hardware.org/?probe=8be575e86a) | Feb 01, 2022 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | Notebook    | [7db720ba39](https://linux-hardware.org/?probe=7db720ba39) | Feb 01, 2022 |
| Gigabyte      | M68MT-D3                    | Desktop     | [8818e2647a](https://linux-hardware.org/?probe=8818e2647a) | Jan 29, 2022 |
| ASUSTek       | H110M-CS/BR                 | Desktop     | [a3f76dfb23](https://linux-hardware.org/?probe=a3f76dfb23) | Jan 29, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [e498058bd8](https://linux-hardware.org/?probe=e498058bd8) | Jan 28, 2022 |
| Intel         | DH55TC AAE70932-302         | Desktop     | [d66879ebac](https://linux-hardware.org/?probe=d66879ebac) | Jan 27, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [0e47f03d64](https://linux-hardware.org/?probe=0e47f03d64) | Jan 24, 2022 |
| Toshiba       | Satellite Pro C660          | Notebook    | [49c83041f3](https://linux-hardware.org/?probe=49c83041f3) | Jan 24, 2022 |
| Gigabyte      | M68MT-D3                    | Desktop     | [9f01c8b5ba](https://linux-hardware.org/?probe=9f01c8b5ba) | Jan 21, 2022 |
| Shuttle       | FB62                        | Desktop     | [01c9cc70b3](https://linux-hardware.org/?probe=01c9cc70b3) | Jan 20, 2022 |
| Toshiba       | Satellite M505              | Notebook    | [9356dfa5a9](https://linux-hardware.org/?probe=9356dfa5a9) | Jan 20, 2022 |
| WinSome       | A14C .B005                  | Notebook    | [d685b78944](https://linux-hardware.org/?probe=d685b78944) | Jan 19, 2022 |
| Lenovo        | ThinkCentre M91p 4524WAP    | Desktop     | [bb0d1c1c68](https://linux-hardware.org/?probe=bb0d1c1c68) | Jan 19, 2022 |
| TWC           | Unknown                     | Notebook    | [85a8fd2cf1](https://linux-hardware.org/?probe=85a8fd2cf1) | Jan 18, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [4b51693e30](https://linux-hardware.org/?probe=4b51693e30) | Jan 17, 2022 |
| TWC           | Unknown                     | Notebook    | [d4cc69cea7](https://linux-hardware.org/?probe=d4cc69cea7) | Jan 16, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [a6c2013bf1](https://linux-hardware.org/?probe=a6c2013bf1) | Jan 15, 2022 |
| Lenovo        | ThinkCentre M91p 4524WAP    | Desktop     | [ce5b35b77b](https://linux-hardware.org/?probe=ce5b35b77b) | Jan 10, 2022 |
| Phitronics    | P33G                        | Desktop     | [d21245c1ea](https://linux-hardware.org/?probe=d21245c1ea) | Jan 09, 2022 |
| eMachines     | G625                        | Notebook    | [1c60347748](https://linux-hardware.org/?probe=1c60347748) | Jan 07, 2022 |
| Shuttle       | FB62                        | Desktop     | [704df008d5](https://linux-hardware.org/?probe=704df008d5) | Jan 06, 2022 |
| Shuttle       | FB62                        | Desktop     | [2da02c481d](https://linux-hardware.org/?probe=2da02c481d) | Jan 06, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [b05f843820](https://linux-hardware.org/?probe=b05f843820) | Jan 06, 2022 |
| Packard Be... | EasyNote MZ35               | Notebook    | [63281c8766](https://linux-hardware.org/?probe=63281c8766) | Jan 06, 2022 |
| Packard Be... | EasyNote MZ35               | Notebook    | [205f3bc0b9](https://linux-hardware.org/?probe=205f3bc0b9) | Jan 06, 2022 |
| Dell          | 096JG8 A01                  | Desktop     | [fecf0d29c7](https://linux-hardware.org/?probe=fecf0d29c7) | Jan 05, 2022 |
| ASUSTek       | NODUSM3                     | Desktop     | [88f0b2e09a](https://linux-hardware.org/?probe=88f0b2e09a) | Jan 05, 2022 |
| Toshiba       | Satellite Pro C660          | Notebook    | [4d080d5d7a](https://linux-hardware.org/?probe=4d080d5d7a) | Jan 03, 2022 |
| eMachines     | G625                        | Notebook    | [03810742ed](https://linux-hardware.org/?probe=03810742ed) | Jan 03, 2022 |
| Lenovo        | ThinkPad T540p 20BFS5630... | Notebook    | [e1e090d622](https://linux-hardware.org/?probe=e1e090d622) | Jan 02, 2022 |
| eMachines     | G625                        | Notebook    | [e3f96637bb](https://linux-hardware.org/?probe=e3f96637bb) | Jan 02, 2022 |
| Lenovo        | ThinkPad X1 1294BL5         | Notebook    | [2cd6f5fbb0](https://linux-hardware.org/?probe=2cd6f5fbb0) | Jan 01, 2022 |
| HP            | 3031h                       | Desktop     | [cc5f90a5be](https://linux-hardware.org/?probe=cc5f90a5be) | Jan 01, 2022 |
| HP            | Unknown                     | Notebook    | [acd2b01673](https://linux-hardware.org/?probe=acd2b01673) | Dec 31, 2021 |
| HP            | Unknown                     | Notebook    | [8f2ecbe94d](https://linux-hardware.org/?probe=8f2ecbe94d) | Dec 31, 2021 |
| Dell          | Latitude D420               | Notebook    | [3caac63d5f](https://linux-hardware.org/?probe=3caac63d5f) | Dec 31, 2021 |
| HP            | ZBook 15u G3                | Notebook    | [e220b55c78](https://linux-hardware.org/?probe=e220b55c78) | Dec 30, 2021 |
| HP            | Pavilion dv6700             | Notebook    | [ce62bcd9b0](https://linux-hardware.org/?probe=ce62bcd9b0) | Dec 28, 2021 |
| HP            | 255 G5                      | Notebook    | [0bf7bc5435](https://linux-hardware.org/?probe=0bf7bc5435) | Dec 28, 2021 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [31fbadcc88](https://linux-hardware.org/?probe=31fbadcc88) | Dec 28, 2021 |
| Packard Be... | MCP73VT-PM                  | Desktop     | [c4f47dca10](https://linux-hardware.org/?probe=c4f47dca10) | Dec 27, 2021 |
| HP            | ZBook 15u G3                | Notebook    | [f770dacb13](https://linux-hardware.org/?probe=f770dacb13) | Dec 25, 2021 |
| Acer          | Aspire 5250                 | Notebook    | [bef8e4334a](https://linux-hardware.org/?probe=bef8e4334a) | Dec 23, 2021 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | Notebook    | [8f7a53f316](https://linux-hardware.org/?probe=8f7a53f316) | Dec 20, 2021 |
| Unknown       | Unknown                     | Desktop     | [86f9e26389](https://linux-hardware.org/?probe=86f9e26389) | Dec 19, 2021 |
| Unknown       | Unknown                     | Desktop     | [0b6e5a76bf](https://linux-hardware.org/?probe=0b6e5a76bf) | Dec 19, 2021 |
| Dell          | 0MN1TX A01                  | Desktop     | [312bd0bfd8](https://linux-hardware.org/?probe=312bd0bfd8) | Dec 18, 2021 |
| Quanta        | MW1/HW1                     | Notebook    | [06bcb3603d](https://linux-hardware.org/?probe=06bcb3603d) | Dec 17, 2021 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [b9908b0aa8](https://linux-hardware.org/?probe=b9908b0aa8) | Dec 12, 2021 |
| HP            | Notebook                    | Notebook    | [97e434f4aa](https://linux-hardware.org/?probe=97e434f4aa) | Dec 11, 2021 |
| HP            | 3047h                       | Desktop     | [b389ca7104](https://linux-hardware.org/?probe=b389ca7104) | Dec 08, 2021 |
| Packard Be... | EasyNote MH35               | Notebook    | [c5dd11f2bd](https://linux-hardware.org/?probe=c5dd11f2bd) | Dec 08, 2021 |
| Packard Be... | EasyNote MH35               | Notebook    | [87a83af447](https://linux-hardware.org/?probe=87a83af447) | Dec 08, 2021 |
| INTELBRAS     | IE-G41T-M7                  | Desktop     | [ff7f8750ea](https://linux-hardware.org/?probe=ff7f8750ea) | Dec 05, 2021 |
| Dell          | 0GY6Y8 A03                  | Desktop     | [4d2767bbdc](https://linux-hardware.org/?probe=4d2767bbdc) | Dec 04, 2021 |
| Lenovo        | S10-3                       | Notebook    | [19cd43f2f7](https://linux-hardware.org/?probe=19cd43f2f7) | Nov 29, 2021 |
| Dell          | Inspiron 14-3452            | Notebook    | [b0fb64bf16](https://linux-hardware.org/?probe=b0fb64bf16) | Nov 27, 2021 |
| Lenovo        | ThinkPad T460 20FMS7DA00    | Notebook    | [c23b71e54e](https://linux-hardware.org/?probe=c23b71e54e) | Nov 27, 2021 |
| HP            | Pavilion g7                 | Notebook    | [e8dcea99ad](https://linux-hardware.org/?probe=e8dcea99ad) | Nov 26, 2021 |
| Toshiba       | Satellite L750              | Notebook    | [836cf1ca10](https://linux-hardware.org/?probe=836cf1ca10) | Nov 25, 2021 |
| Toshiba       | Satellite L750              | Notebook    | [827e07a075](https://linux-hardware.org/?probe=827e07a075) | Nov 24, 2021 |
| Acer          | Spin SP513-53N              | Convertible | [db2f01559f](https://linux-hardware.org/?probe=db2f01559f) | Nov 22, 2021 |
| Gigabyte      | H57M-USB3                   | Desktop     | [97409a8d1c](https://linux-hardware.org/?probe=97409a8d1c) | Nov 22, 2021 |
| Gigabyte      | H57M-USB3                   | Desktop     | [e0e4ee802a](https://linux-hardware.org/?probe=e0e4ee802a) | Nov 22, 2021 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [c239a2a68f](https://linux-hardware.org/?probe=c239a2a68f) | Nov 21, 2021 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [f9ca6a2f97](https://linux-hardware.org/?probe=f9ca6a2f97) | Nov 21, 2021 |
| ASUSTek       | P5PL2-E                     | Desktop     | [00ec0123c5](https://linux-hardware.org/?probe=00ec0123c5) | Nov 20, 2021 |
| Fujitsu Si... | AMILO Li1705                | Notebook    | [397611b48d](https://linux-hardware.org/?probe=397611b48d) | Nov 20, 2021 |
| ASUSTek       | P5PL2-E                     | Desktop     | [12db2d9ccc](https://linux-hardware.org/?probe=12db2d9ccc) | Nov 19, 2021 |
| Lenovo        | ThinkPad X1 1294BL5         | Notebook    | [d543e2cd80](https://linux-hardware.org/?probe=d543e2cd80) | Nov 19, 2021 |
| HP            | Pavilion dv7                | Notebook    | [33202c35ad](https://linux-hardware.org/?probe=33202c35ad) | Nov 19, 2021 |
| HP            | Pavilion dv7                | Notebook    | [66ec298a1c](https://linux-hardware.org/?probe=66ec298a1c) | Nov 18, 2021 |
| Gigabyte      | VM900M                      | Desktop     | [80536ac6e5](https://linux-hardware.org/?probe=80536ac6e5) | Nov 16, 2021 |
| Gigabyte      | VM900M                      | Desktop     | [7cd9a0a1ca](https://linux-hardware.org/?probe=7cd9a0a1ca) | Nov 16, 2021 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | Notebook    | [641218d2e6](https://linux-hardware.org/?probe=641218d2e6) | Nov 16, 2021 |
| HP            | Pavilion dv9500             | Notebook    | [bef50ae82a](https://linux-hardware.org/?probe=bef50ae82a) | Nov 15, 2021 |
| HP            | Compaq nx8220 (PG801ET#A... | Notebook    | [60c7204131](https://linux-hardware.org/?probe=60c7204131) | Nov 14, 2021 |
| Dell          | 0UY253 A00                  | Desktop     | [274a0a6b16](https://linux-hardware.org/?probe=274a0a6b16) | Nov 14, 2021 |
| HP            | EliteBook x360 1040 G6      | Convertible | [a887aae273](https://linux-hardware.org/?probe=a887aae273) | Nov 12, 2021 |
| Samsung       | 370E4K                      | Notebook    | [f076dae1f9](https://linux-hardware.org/?probe=f076dae1f9) | Nov 12, 2021 |
| Medion        | P8610                       | Notebook    | [122043c04d](https://linux-hardware.org/?probe=122043c04d) | Nov 08, 2021 |
| Medion        | P8610                       | Notebook    | [4d519680a1](https://linux-hardware.org/?probe=4d519680a1) | Nov 07, 2021 |
| ASUSTek       | K42F                        | Notebook    | [a0fc0b335f](https://linux-hardware.org/?probe=a0fc0b335f) | Nov 07, 2021 |
| MAXDATA       | ECO4000IW                   | Notebook    | [5a5fb011c7](https://linux-hardware.org/?probe=5a5fb011c7) | Nov 06, 2021 |
| Apple         | MacBookAir4,1               | Notebook    | [01eb7627e2](https://linux-hardware.org/?probe=01eb7627e2) | Nov 06, 2021 |
| Dell          | XPS M1330                   | Notebook    | [3fcb1bf591](https://linux-hardware.org/?probe=3fcb1bf591) | Nov 06, 2021 |
| ASRock        | 970M Pro3                   | Desktop     | [6da9b773d5](https://linux-hardware.org/?probe=6da9b773d5) | Nov 03, 2021 |
| Gigabyte      | B450 AORUS M                | Desktop     | [0b2266e44a](https://linux-hardware.org/?probe=0b2266e44a) | Nov 03, 2021 |
| Pegatron      | IPPCR-SS                    | Desktop     | [0179d16327](https://linux-hardware.org/?probe=0179d16327) | Nov 02, 2021 |
| Intel         | HURONRIVER                  | Notebook    | [5ded89b4a5](https://linux-hardware.org/?probe=5ded89b4a5) | Nov 02, 2021 |
| Lenovo        | ThinkPad X1 1294BL5         | Notebook    | [e18dd8b896](https://linux-hardware.org/?probe=e18dd8b896) | Nov 01, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [e52e9002d0](https://linux-hardware.org/?probe=e52e9002d0) | Oct 31, 2021 |
| Toshiba       | Satellite U400              | Notebook    | [abcf2eee75](https://linux-hardware.org/?probe=abcf2eee75) | Oct 27, 2021 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [541092026f](https://linux-hardware.org/?probe=541092026f) | Oct 26, 2021 |
| HP            | 1850                        | Desktop     | [e8c750c4b9](https://linux-hardware.org/?probe=e8c750c4b9) | Oct 25, 2021 |
| MSI           | Z77A-GD65                   | Desktop     | [947cdfd30b](https://linux-hardware.org/?probe=947cdfd30b) | Oct 24, 2021 |
| Acer          | Acadia V1.42                | Notebook    | [01122f69f4](https://linux-hardware.org/?probe=01122f69f4) | Oct 23, 2021 |
| Acer          | Acadia V1.42                | Notebook    | [11b24034fc](https://linux-hardware.org/?probe=11b24034fc) | Oct 23, 2021 |
| HP            | 255 G5                      | Notebook    | [02e4b753ca](https://linux-hardware.org/?probe=02e4b753ca) | Oct 22, 2021 |
| HP            | 2B0C MVB,A                  | All in one  | [46a74b74fc](https://linux-hardware.org/?probe=46a74b74fc) | Oct 22, 2021 |
| Dell          | 0GDG8Y A00                  | Desktop     | [a4bf9808a8](https://linux-hardware.org/?probe=a4bf9808a8) | Oct 21, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [24535d9a4b](https://linux-hardware.org/?probe=24535d9a4b) | Oct 20, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [cf78694aa7](https://linux-hardware.org/?probe=cf78694aa7) | Oct 20, 2021 |
| Dell          | System XPS 15Z              | Notebook    | [751ffeefa0](https://linux-hardware.org/?probe=751ffeefa0) | Oct 20, 2021 |
| HP            | Presario CQ42               | Notebook    | [d82c04d026](https://linux-hardware.org/?probe=d82c04d026) | Oct 19, 2021 |
| Dell          | 0PU052                      | Desktop     | [1bb0034b64](https://linux-hardware.org/?probe=1bb0034b64) | Oct 19, 2021 |
| Acer          | Aspire ES1-531              | Notebook    | [a7058244ce](https://linux-hardware.org/?probe=a7058244ce) | Oct 16, 2021 |
| Dell          | Inspiron N5010              | Notebook    | [eca5c4cbf7](https://linux-hardware.org/?probe=eca5c4cbf7) | Oct 15, 2021 |
| HP            | 09E8h                       | Desktop     | [7faca26f13](https://linux-hardware.org/?probe=7faca26f13) | Oct 14, 2021 |
| HP            | 09E8h                       | Desktop     | [5013f5686b](https://linux-hardware.org/?probe=5013f5686b) | Oct 14, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [3054954ea5](https://linux-hardware.org/?probe=3054954ea5) | Oct 14, 2021 |
| Dell          | Inspiron N5010              | Notebook    | [2495309045](https://linux-hardware.org/?probe=2495309045) | Oct 14, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [dd3b21ba26](https://linux-hardware.org/?probe=dd3b21ba26) | Oct 14, 2021 |
| Dell          | Inspiron N5050              | Notebook    | [1dd1c022a2](https://linux-hardware.org/?probe=1dd1c022a2) | Oct 13, 2021 |
| Dell          | Inspiron N5050              | Notebook    | [8866975539](https://linux-hardware.org/?probe=8866975539) | Oct 13, 2021 |
| Lenovo        | Yoga 510-14ISK 80S7         | Convertible | [350d402895](https://linux-hardware.org/?probe=350d402895) | Oct 13, 2021 |
| American M... | 255/259 Series              | Notebook    | [e8761321aa](https://linux-hardware.org/?probe=e8761321aa) | Oct 13, 2021 |
| Acer          | Aspire E1-572               | Notebook    | [dc154fe7c0](https://linux-hardware.org/?probe=dc154fe7c0) | Oct 13, 2021 |
| ASUSTek       | N61Jv                       | Notebook    | [0e300bafe8](https://linux-hardware.org/?probe=0e300bafe8) | Oct 12, 2021 |
| Unknown       | Unknown                     | Desktop     | [3598241674](https://linux-hardware.org/?probe=3598241674) | Oct 10, 2021 |
| Toshiba       | Satellite Pro C660          | Notebook    | [14a96b5cec](https://linux-hardware.org/?probe=14a96b5cec) | Oct 10, 2021 |
| Acer          | TravelMate 2400             | Notebook    | [34d9be1b4a](https://linux-hardware.org/?probe=34d9be1b4a) | Oct 10, 2021 |
| Acer          | TravelMate 2400             | Notebook    | [4895b20211](https://linux-hardware.org/?probe=4895b20211) | Oct 09, 2021 |
| HP            | Laptop 15-db0xxx            | Notebook    | [a49c0e5d41](https://linux-hardware.org/?probe=a49c0e5d41) | Oct 08, 2021 |
| Sony          | VPCEA20FB                   | Notebook    | [de4d94232e](https://linux-hardware.org/?probe=de4d94232e) | Oct 07, 2021 |
| Sony          | VPCEA20FB                   | Notebook    | [52e6abba3c](https://linux-hardware.org/?probe=52e6abba3c) | Oct 07, 2021 |
| Matsushita... | CF-19CHB23BE                | Notebook    | [7024487bcd](https://linux-hardware.org/?probe=7024487bcd) | Oct 07, 2021 |
| ASUSTek       | P7H55-M SI                  | Desktop     | [704043deab](https://linux-hardware.org/?probe=704043deab) | Oct 06, 2021 |
| HP            | 2B0C MVB,A                  | All in one  | [b411cfd959](https://linux-hardware.org/?probe=b411cfd959) | Oct 04, 2021 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [f72bc27861](https://linux-hardware.org/?probe=f72bc27861) | Oct 03, 2021 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [5904ce7230](https://linux-hardware.org/?probe=5904ce7230) | Oct 03, 2021 |
| Acer          | AOD255                      | Notebook    | [79fa37e2d3](https://linux-hardware.org/?probe=79fa37e2d3) | Sep 30, 2021 |
| Lenovo        | ThinkPad Edge E531 68852... | Notebook    | [4cd46a616f](https://linux-hardware.org/?probe=4cd46a616f) | Sep 29, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [ec5453ee8c](https://linux-hardware.org/?probe=ec5453ee8c) | Sep 28, 2021 |
| Digibras      | NH4CU53                     | Notebook    | [f0615abf72](https://linux-hardware.org/?probe=f0615abf72) | Sep 27, 2021 |
| Biostar       | P4M89-M7B Ver:1.0           | Desktop     | [c499580572](https://linux-hardware.org/?probe=c499580572) | Sep 26, 2021 |
| HP            | 0A80h                       | Desktop     | [b939bfa24c](https://linux-hardware.org/?probe=b939bfa24c) | Sep 25, 2021 |
| Biostar       | P4M89-M7B Ver:1.0           | Desktop     | [e540393e87](https://linux-hardware.org/?probe=e540393e87) | Sep 25, 2021 |
| Toshiba       | Satellite C50-B             | Notebook    | [0914aeed54](https://linux-hardware.org/?probe=0914aeed54) | Sep 25, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1070... | Notebook    | [c77dd4d1b4](https://linux-hardware.org/?probe=c77dd4d1b4) | Sep 23, 2021 |
| Philco        | 14F                         | Notebook    | [093b9632e8](https://linux-hardware.org/?probe=093b9632e8) | Sep 23, 2021 |
| Dell          | Inspiron 6000               | Notebook    | [f48bad44cd](https://linux-hardware.org/?probe=f48bad44cd) | Sep 22, 2021 |
| ASUSTek       | UX430UAR                    | Notebook    | [57d695a843](https://linux-hardware.org/?probe=57d695a843) | Sep 21, 2021 |
| Unknown       | G31T-M7                     | Desktop     | [7dcab46660](https://linux-hardware.org/?probe=7dcab46660) | Sep 20, 2021 |
| HP            | ProBook 4540s               | Notebook    | [ccac6a82ca](https://linux-hardware.org/?probe=ccac6a82ca) | Sep 20, 2021 |
| Fujitsu Si... | AMILO M7440D                | Notebook    | [e23f21b9b4](https://linux-hardware.org/?probe=e23f21b9b4) | Sep 19, 2021 |
| Fujitsu Si... | AMILO M7440D                | Notebook    | [bce3e66350](https://linux-hardware.org/?probe=bce3e66350) | Sep 19, 2021 |
| JOOYON        | IPM41-D3G                   | Desktop     | [54cc0ff25b](https://linux-hardware.org/?probe=54cc0ff25b) | Sep 17, 2021 |
| Positivo      | Mobile                      | Notebook    | [6f701d72fd](https://linux-hardware.org/?probe=6f701d72fd) | Sep 17, 2021 |
| Unknown       | G31T-M7                     | Desktop     | [54c45c2abb](https://linux-hardware.org/?probe=54c45c2abb) | Sep 16, 2021 |
| Acer          | AZ1100                      | All in one  | [6a428a166a](https://linux-hardware.org/?probe=6a428a166a) | Sep 16, 2021 |
| Acer          | AZ1100                      | All in one  | [e4f070935b](https://linux-hardware.org/?probe=e4f070935b) | Sep 16, 2021 |
| HP            | 0A64h                       | Desktop     | [edcb77e9a1](https://linux-hardware.org/?probe=edcb77e9a1) | Sep 15, 2021 |
| ASUSTek       | F5SL                        | Notebook    | [e6e93168a6](https://linux-hardware.org/?probe=e6e93168a6) | Sep 15, 2021 |
| Toshiba       | Satellite Pro C850-1H8      | Notebook    | [ea23c035b2](https://linux-hardware.org/?probe=ea23c035b2) | Sep 15, 2021 |
| HP            | EliteBook 6930p             | Notebook    | [8f38de340d](https://linux-hardware.org/?probe=8f38de340d) | Sep 15, 2021 |
| Lenovo        | ThinkPad T460 20FMS7DA00    | Notebook    | [445f079c6d](https://linux-hardware.org/?probe=445f079c6d) | Sep 15, 2021 |
| HP            | 0B40h                       | Desktop     | [c48744b986](https://linux-hardware.org/?probe=c48744b986) | Sep 14, 2021 |
| eMachines     | EL1352                      | Desktop     | [f9df6297b5](https://linux-hardware.org/?probe=f9df6297b5) | Sep 12, 2021 |
| JOOYON        | IPM41-D3G                   | Desktop     | [4f8d90f8ef](https://linux-hardware.org/?probe=4f8d90f8ef) | Sep 12, 2021 |
| Lenovo        | ThinkPad T61 765818U        | Notebook    | [7bae831cdf](https://linux-hardware.org/?probe=7bae831cdf) | Sep 12, 2021 |
| Dell          | 0GDG8Y A00                  | Desktop     | [70e6485466](https://linux-hardware.org/?probe=70e6485466) | Sep 11, 2021 |
| Acer          | Lugano M                    | Notebook    | [5c114a6e41](https://linux-hardware.org/?probe=5c114a6e41) | Sep 11, 2021 |
| Acer          | Aspire 5020                 | Notebook    | [54ddef7aa7](https://linux-hardware.org/?probe=54ddef7aa7) | Sep 11, 2021 |
| Acer          | Aspire 5020                 | Notebook    | [8c00427976](https://linux-hardware.org/?probe=8c00427976) | Sep 11, 2021 |
| Acer          | Aspire 3610                 | Notebook    | [fc6953a3f9](https://linux-hardware.org/?probe=fc6953a3f9) | Sep 10, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [303cc5e8d6](https://linux-hardware.org/?probe=303cc5e8d6) | Sep 10, 2021 |
| HP            | ProBook 6460b               | Notebook    | [b0f0eaf216](https://linux-hardware.org/?probe=b0f0eaf216) | Sep 09, 2021 |
| Pendo Indu... | PNDFWXUFD11BLK6             | Notebook    | [06d0750e6e](https://linux-hardware.org/?probe=06d0750e6e) | Sep 08, 2021 |
| Acer          | Aspire 3610                 | Notebook    | [3ab0387498](https://linux-hardware.org/?probe=3ab0387498) | Sep 08, 2021 |
| Dell          | Inspiron 1010               | Notebook    | [ee05ebef50](https://linux-hardware.org/?probe=ee05ebef50) | Sep 07, 2021 |
| Dell          | Inspiron 1010               | Notebook    | [8805be4e5c](https://linux-hardware.org/?probe=8805be4e5c) | Sep 07, 2021 |
| Lenovo        | ThinkPad T61 765818U        | Notebook    | [df384e1ab4](https://linux-hardware.org/?probe=df384e1ab4) | Sep 06, 2021 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [ce822e1caa](https://linux-hardware.org/?probe=ce822e1caa) | Sep 06, 2021 |
| ASUSTek       | M2N-E                       | Desktop     | [1b02673a1a](https://linux-hardware.org/?probe=1b02673a1a) | Sep 06, 2021 |
| GPD           | MicroPC                     | Notebook    | [d0ffed23be](https://linux-hardware.org/?probe=d0ffed23be) | Sep 05, 2021 |
| ASUSTek       | K8N                         | Desktop     | [224c8289b1](https://linux-hardware.org/?probe=224c8289b1) | Sep 05, 2021 |
| Unknown       | T3 MRD                      | Notebook    | [0687d6609d](https://linux-hardware.org/?probe=0687d6609d) | Sep 03, 2021 |
| Dell          | Latitude D630               | Notebook    | [6b4af154d5](https://linux-hardware.org/?probe=6b4af154d5) | Sep 03, 2021 |
| Acer          | Aspire 9410                 | Notebook    | [d6632fcd8b](https://linux-hardware.org/?probe=d6632fcd8b) | Sep 02, 2021 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [ff69ae3970](https://linux-hardware.org/?probe=ff69ae3970) | Sep 01, 2021 |
| Intel         | D865GLC AAC28906-407        | Desktop     | [5936f5b3ba](https://linux-hardware.org/?probe=5936f5b3ba) | Sep 01, 2021 |
| HP            | 530                         | Notebook    | [cc7cc97ae3](https://linux-hardware.org/?probe=cc7cc97ae3) | Aug 31, 2021 |
| Dell          | 0GM819                      | Desktop     | [7a17c1970d](https://linux-hardware.org/?probe=7a17c1970d) | Aug 31, 2021 |
| HP            | 530                         | Notebook    | [20bf2422fc](https://linux-hardware.org/?probe=20bf2422fc) | Aug 31, 2021 |
| ASUSTek       | P7H55-M SI                  | Desktop     | [462a181df0](https://linux-hardware.org/?probe=462a181df0) | Aug 30, 2021 |
| ASUSTek       | X55U                        | Notebook    | [b37f7fdf24](https://linux-hardware.org/?probe=b37f7fdf24) | Aug 30, 2021 |
| ASUSTek       | P7H55-M SI                  | Desktop     | [2f9f7d43ad](https://linux-hardware.org/?probe=2f9f7d43ad) | Aug 30, 2021 |
| Dell          | 0GY6Y8 A03                  | Desktop     | [4d30a11af1](https://linux-hardware.org/?probe=4d30a11af1) | Aug 29, 2021 |
| Acer          | Aspire 8920                 | Notebook    | [8a006e9280](https://linux-hardware.org/?probe=8a006e9280) | Aug 28, 2021 |
| Packard Be... | MCP73VT-PM                  | Desktop     | [c9ed90c1a7](https://linux-hardware.org/?probe=c9ed90c1a7) | Aug 27, 2021 |
| ASUSTek       | 1001PX                      | Notebook    | [1b8954cf9f](https://linux-hardware.org/?probe=1b8954cf9f) | Aug 27, 2021 |
| Lenovo        | ThinkPad R61e 7650ELU       | Notebook    | [7c29fad093](https://linux-hardware.org/?probe=7c29fad093) | Aug 26, 2021 |
| ASRock        | G31M-GS                     | Desktop     | [c9ed7c2d8a](https://linux-hardware.org/?probe=c9ed7c2d8a) | Aug 26, 2021 |
| Lenovo        | ThinkPad SL510 28752NG      | Notebook    | [285a023dd8](https://linux-hardware.org/?probe=285a023dd8) | Aug 26, 2021 |
| ASUSTek       | UX430UAR                    | Notebook    | [88f301b39f](https://linux-hardware.org/?probe=88f301b39f) | Aug 26, 2021 |
| HP            | Mini 110-3100               | Notebook    | [2bca9a30ab](https://linux-hardware.org/?probe=2bca9a30ab) | Aug 25, 2021 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [4908383621](https://linux-hardware.org/?probe=4908383621) | Aug 25, 2021 |
| Dell          | Inspiron 6000               | Notebook    | [f4ae3e605a](https://linux-hardware.org/?probe=f4ae3e605a) | Aug 24, 2021 |
| Gigabyte      | EP45-DS3                    | Desktop     | [a2a6e3ee32](https://linux-hardware.org/?probe=a2a6e3ee32) | Aug 24, 2021 |
| Gigabyte      | H87M-HD3                    | Desktop     | [b39ebeca56](https://linux-hardware.org/?probe=b39ebeca56) | Aug 23, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [ab8a4f01d9](https://linux-hardware.org/?probe=ab8a4f01d9) | Aug 22, 2021 |
| Panasonic     | CF-31JEGAX1M                | Notebook    | [c5acecef3a](https://linux-hardware.org/?probe=c5acecef3a) | Aug 22, 2021 |
| HP            | 1632                        | Desktop     | [52a448c332](https://linux-hardware.org/?probe=52a448c332) | Aug 22, 2021 |
| HP            | Compaq Presario CQ61        | Notebook    | [c7c1d06954](https://linux-hardware.org/?probe=c7c1d06954) | Aug 21, 2021 |
| Unknown       | Unknown                     | Desktop     | [7406e49c18](https://linux-hardware.org/?probe=7406e49c18) | Aug 21, 2021 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [42a7ad3cb2](https://linux-hardware.org/?probe=42a7ad3cb2) | Aug 21, 2021 |
| Positivo      | Mobile                      | Notebook    | [e4a47e39b6](https://linux-hardware.org/?probe=e4a47e39b6) | Aug 21, 2021 |
| Positivo      | POS-MIH61CF                 | Desktop     | [aaa1640628](https://linux-hardware.org/?probe=aaa1640628) | Aug 20, 2021 |
| Samsung       | RV419                       | Notebook    | [ba6f454b7d](https://linux-hardware.org/?probe=ba6f454b7d) | Aug 20, 2021 |
| Samsung       | N150                        | Notebook    | [86914b23ac](https://linux-hardware.org/?probe=86914b23ac) | Aug 19, 2021 |
| Positivo      | Q232A                       | Notebook    | [f76d2dc489](https://linux-hardware.org/?probe=f76d2dc489) | Aug 19, 2021 |
| ECS           | A960M-MV                    | Desktop     | [684f50eff8](https://linux-hardware.org/?probe=684f50eff8) | Aug 18, 2021 |
| HP            | ProBook 4430s               | Notebook    | [0235e3c344](https://linux-hardware.org/?probe=0235e3c344) | Aug 18, 2021 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [5ab0429d85](https://linux-hardware.org/?probe=5ab0429d85) | Aug 17, 2021 |
| HP            | ENVY 17                     | Notebook    | [7c9143912d](https://linux-hardware.org/?probe=7c9143912d) | Aug 17, 2021 |
| HP            | 8430 1000                   | All in one  | [38088141ff](https://linux-hardware.org/?probe=38088141ff) | Aug 17, 2021 |
| ASUSTek       | X441SA                      | Notebook    | [f23d4d50be](https://linux-hardware.org/?probe=f23d4d50be) | Aug 16, 2021 |
| Itautec       | Infoway                     | Notebook    | [f66edac6bd](https://linux-hardware.org/?probe=f66edac6bd) | Aug 16, 2021 |
| Itautec       | Infoway                     | Notebook    | [94c198d530](https://linux-hardware.org/?probe=94c198d530) | Aug 16, 2021 |
| Wiltronic     | Maximus IV                  | Convertible | [fcd665c1a0](https://linux-hardware.org/?probe=fcd665c1a0) | Aug 15, 2021 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [2aa00ea596](https://linux-hardware.org/?probe=2aa00ea596) | Aug 15, 2021 |
| HP            | Pavilion 17                 | Notebook    | [b628f70687](https://linux-hardware.org/?probe=b628f70687) | Aug 15, 2021 |
| Dell          | 096JG8 A01                  | Desktop     | [64f4c407c6](https://linux-hardware.org/?probe=64f4c407c6) | Aug 14, 2021 |
| SiS           | M672 Board SI94B-20+SI96... | Notebook    | [8268c73ee9](https://linux-hardware.org/?probe=8268c73ee9) | Aug 14, 2021 |
| HP            | Pavilion g7                 | Notebook    | [cf766b8d76](https://linux-hardware.org/?probe=cf766b8d76) | Aug 13, 2021 |
| Quanta        | QL5 TBD                     | Notebook    | [be465dec60](https://linux-hardware.org/?probe=be465dec60) | Aug 13, 2021 |
| MSI           | MS-7309                     | Desktop     | [2d726fe8ea](https://linux-hardware.org/?probe=2d726fe8ea) | Aug 13, 2021 |
| Toshiba       | Satellite L505D             | Notebook    | [b7b43a605d](https://linux-hardware.org/?probe=b7b43a605d) | Aug 12, 2021 |
| Toshiba       | Satellite L505D             | Notebook    | [8560337601](https://linux-hardware.org/?probe=8560337601) | Aug 12, 2021 |
| Acer          | Aspire 8920                 | Notebook    | [9ac1d0a471](https://linux-hardware.org/?probe=9ac1d0a471) | Aug 12, 2021 |
| Toshiba       | STI 910121                  | Desktop     | [2754eead70](https://linux-hardware.org/?probe=2754eead70) | Aug 11, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [1eba114602](https://linux-hardware.org/?probe=1eba114602) | Aug 11, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [a31c1f0fda](https://linux-hardware.org/?probe=a31c1f0fda) | Aug 11, 2021 |
| HP            | Pavilion dv6700             | Notebook    | [ebf6b956cb](https://linux-hardware.org/?probe=ebf6b956cb) | Aug 10, 2021 |
| Apple         | MacBookPro7,1               | Notebook    | [da4107ffc3](https://linux-hardware.org/?probe=da4107ffc3) | Aug 10, 2021 |
| Samsung       | RV419                       | Notebook    | [66823b7d4d](https://linux-hardware.org/?probe=66823b7d4d) | Aug 10, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [d914912052](https://linux-hardware.org/?probe=d914912052) | Aug 09, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [31f5694698](https://linux-hardware.org/?probe=31f5694698) | Aug 08, 2021 |
| ASUSTek       | X51R                        | Notebook    | [1d1aad3900](https://linux-hardware.org/?probe=1d1aad3900) | Aug 08, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [d0814fcb72](https://linux-hardware.org/?probe=d0814fcb72) | Aug 08, 2021 |
| Acer          | Extensa 5220                | Notebook    | [c2e39c0d39](https://linux-hardware.org/?probe=c2e39c0d39) | Aug 07, 2021 |
| HP            | Compaq 2510p                | Notebook    | [ea3c7d2fe2](https://linux-hardware.org/?probe=ea3c7d2fe2) | Aug 07, 2021 |
| HP            | Compaq 2510p                | Notebook    | [31449a4b42](https://linux-hardware.org/?probe=31449a4b42) | Aug 07, 2021 |
| Dell          | Inspiron 3421               | Notebook    | [dc8767625f](https://linux-hardware.org/?probe=dc8767625f) | Aug 07, 2021 |
| Acer          | Extensa 5220                | Notebook    | [b0da636247](https://linux-hardware.org/?probe=b0da636247) | Aug 07, 2021 |
| Dell          | Inspiron 3421               | Notebook    | [52f396865d](https://linux-hardware.org/?probe=52f396865d) | Aug 07, 2021 |
| Positivo      | CHT14B                      | Notebook    | [c8d89d2cde](https://linux-hardware.org/?probe=c8d89d2cde) | Aug 06, 2021 |
| Acer          | Aspire E5-575               | Notebook    | [9d4f584337](https://linux-hardware.org/?probe=9d4f584337) | Aug 06, 2021 |
| Lenovo        | ThinkPad T61 6468AE2        | Notebook    | [58f1efa783](https://linux-hardware.org/?probe=58f1efa783) | Aug 06, 2021 |
| Dell          | Latitude E5500              | Notebook    | [0688139a45](https://linux-hardware.org/?probe=0688139a45) | Aug 04, 2021 |
| Lenovo        | ThinkPad T61 6465CTO        | Notebook    | [d93258840e](https://linux-hardware.org/?probe=d93258840e) | Aug 04, 2021 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | Notebook    | [1b40831803](https://linux-hardware.org/?probe=1b40831803) | Aug 04, 2021 |
| Pegatron      | 2AB6                        | Desktop     | [79dffb5346](https://linux-hardware.org/?probe=79dffb5346) | Jul 31, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [a8abc9f29f](https://linux-hardware.org/?probe=a8abc9f29f) | Jul 29, 2021 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [0033aa7340](https://linux-hardware.org/?probe=0033aa7340) | Jul 28, 2021 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [af9bf0e1ff](https://linux-hardware.org/?probe=af9bf0e1ff) | Jul 27, 2021 |
| Acer          | Extensa 5220                | Notebook    | [e8b82c756d](https://linux-hardware.org/?probe=e8b82c756d) | Jul 26, 2021 |
| Acer          | Extensa 5220                | Notebook    | [82ae089b21](https://linux-hardware.org/?probe=82ae089b21) | Jul 26, 2021 |
| ASUSTek       | P5KC                        | Desktop     | [38dd8e10c7](https://linux-hardware.org/?probe=38dd8e10c7) | Jul 26, 2021 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [85fddcd068](https://linux-hardware.org/?probe=85fddcd068) | Jul 26, 2021 |
| Medion        | Unknown                     | Notebook    | [021ba4d5b5](https://linux-hardware.org/?probe=021ba4d5b5) | Jul 25, 2021 |
| Xi3           | 401-0001-303 303            | Desktop     | [0f9e40f5fc](https://linux-hardware.org/?probe=0f9e40f5fc) | Jul 25, 2021 |
| Medion        | Unknown                     | Notebook    | [e9c5e99e0b](https://linux-hardware.org/?probe=e9c5e99e0b) | Jul 25, 2021 |
| HP            | Compaq CQ58                 | Notebook    | [96df68c59e](https://linux-hardware.org/?probe=96df68c59e) | Jul 25, 2021 |
| Gigabyte      | B460M DS3H                  | Desktop     | [c989b48f08](https://linux-hardware.org/?probe=c989b48f08) | Jul 24, 2021 |
| Dell          | Latitude 5480               | Notebook    | [1b32299688](https://linux-hardware.org/?probe=1b32299688) | Jul 24, 2021 |
| HP            | Notebook                    | Notebook    | [71959b30db](https://linux-hardware.org/?probe=71959b30db) | Jul 23, 2021 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [8d72c96d15](https://linux-hardware.org/?probe=8d72c96d15) | Jul 23, 2021 |
| ASUSTek       | P7H55-USB3                  | Desktop     | [cd727a9f3d](https://linux-hardware.org/?probe=cd727a9f3d) | Jul 22, 2021 |
| Dell          | 0427JK A00                  | Desktop     | [3e66028cf8](https://linux-hardware.org/?probe=3e66028cf8) | Jul 22, 2021 |
| Dell          | Inspiron N5010              | Notebook    | [4a76f84bf5](https://linux-hardware.org/?probe=4a76f84bf5) | Jul 22, 2021 |
| Lenovo        | Y70-70 Touch 80DU           | Notebook    | [36fb0f3df5](https://linux-hardware.org/?probe=36fb0f3df5) | Jul 16, 2021 |
| Sony          | SVE14A2V1EW                 | Notebook    | [2b1ce53eca](https://linux-hardware.org/?probe=2b1ce53eca) | Jul 16, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [846febb191](https://linux-hardware.org/?probe=846febb191) | Jul 14, 2021 |
| Dell          | 0M9KCM A00                  | Desktop     | [162b090056](https://linux-hardware.org/?probe=162b090056) | Jul 14, 2021 |
| HP            | EliteBook 820 G2            | Notebook    | [8c035c3e82](https://linux-hardware.org/?probe=8c035c3e82) | Jul 14, 2021 |
| ASUSTek       | G50V                        | Notebook    | [ec1ddd4644](https://linux-hardware.org/?probe=ec1ddd4644) | Jul 11, 2021 |
| Samsung       | N145P/N250P/N260P           | Notebook    | [e60ff3401a](https://linux-hardware.org/?probe=e60ff3401a) | Jul 11, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [9765ba93ab](https://linux-hardware.org/?probe=9765ba93ab) | Jul 10, 2021 |
| Dell          | 0427JK A00                  | Desktop     | [82c73cf6be](https://linux-hardware.org/?probe=82c73cf6be) | Jul 09, 2021 |
| Sony          | VPCEH16EA                   | Notebook    | [189be303f7](https://linux-hardware.org/?probe=189be303f7) | Jul 09, 2021 |
| Sony          | VPCEH16EA                   | Notebook    | [c93e5aee87](https://linux-hardware.org/?probe=c93e5aee87) | Jul 08, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [b543fedfd0](https://linux-hardware.org/?probe=b543fedfd0) | Jul 08, 2021 |
| Dell          | 0M9KCM A00                  | Desktop     | [5bcc11cd03](https://linux-hardware.org/?probe=5bcc11cd03) | Jul 08, 2021 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [508ac5b4d5](https://linux-hardware.org/?probe=508ac5b4d5) | Jul 07, 2021 |
| Gigabyte      | M61PME-S2                   | Desktop     | [8c1e919c7b](https://linux-hardware.org/?probe=8c1e919c7b) | Jul 07, 2021 |
| Sony          | VPCSB25FB                   | Notebook    | [6de928a758](https://linux-hardware.org/?probe=6de928a758) | Jul 07, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [fe78759b7d](https://linux-hardware.org/?probe=fe78759b7d) | Jul 07, 2021 |
| Acer          | Aspire X3950                | Desktop     | [1ff3961dca](https://linux-hardware.org/?probe=1ff3961dca) | Jul 06, 2021 |
| HP            | 0A80h                       | Desktop     | [1d3b01bec4](https://linux-hardware.org/?probe=1d3b01bec4) | Jul 06, 2021 |
| Gigabyte      | G31M-S2C                    | Desktop     | [7756be5173](https://linux-hardware.org/?probe=7756be5173) | Jul 06, 2021 |
| Gigabyte      | G31M-S2C                    | Desktop     | [9282eabbef](https://linux-hardware.org/?probe=9282eabbef) | Jul 06, 2021 |
| Gateway       | MX8711                      | Notebook    | [185e86b37e](https://linux-hardware.org/?probe=185e86b37e) | Jul 06, 2021 |
| Dell          | 0T10XW A00                  | Desktop     | [38235d3567](https://linux-hardware.org/?probe=38235d3567) | Jul 05, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [a05f25993e](https://linux-hardware.org/?probe=a05f25993e) | Jul 04, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [b839aa5520](https://linux-hardware.org/?probe=b839aa5520) | Jul 03, 2021 |
| Acer          | Aspire A515-45              | Notebook    | [42249c6e47](https://linux-hardware.org/?probe=42249c6e47) | Jul 02, 2021 |
| ASUSTek       | A58M-A/BR                   | Desktop     | [2215ebf487](https://linux-hardware.org/?probe=2215ebf487) | Jul 02, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [88044da394](https://linux-hardware.org/?probe=88044da394) | Jul 01, 2021 |
| Gigabyte      | 8IPE1000-G/L                | Desktop     | [0301b9707b](https://linux-hardware.org/?probe=0301b9707b) | Jun 29, 2021 |
| ASUSTek       | Z170-P D3                   | Desktop     | [a0a2c651ab](https://linux-hardware.org/?probe=a0a2c651ab) | Jun 29, 2021 |
| HP            | Pavilion dv6700             | Notebook    | [93c6a703a7](https://linux-hardware.org/?probe=93c6a703a7) | Jun 27, 2021 |
| HP            | Pavilion dv6700             | Notebook    | [f7e407b14c](https://linux-hardware.org/?probe=f7e407b14c) | Jun 27, 2021 |
| Acer          | EG43LMK                     | Desktop     | [5df39d6ba0](https://linux-hardware.org/?probe=5df39d6ba0) | Jun 26, 2021 |
| ASUSTek       | K54HR                       | Notebook    | [8fcbeb49c1](https://linux-hardware.org/?probe=8fcbeb49c1) | Jun 26, 2021 |
| Sony          | VPCSB16FG                   | Notebook    | [ead356e548](https://linux-hardware.org/?probe=ead356e548) | Jun 24, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [f3430744d8](https://linux-hardware.org/?probe=f3430744d8) | Jun 24, 2021 |
| Dell          | 0427JK A00                  | Desktop     | [d9270ab2c1](https://linux-hardware.org/?probe=d9270ab2c1) | Jun 23, 2021 |
| HP            | EliteBook x360 1040 G6      | Convertible | [67ad5cb330](https://linux-hardware.org/?probe=67ad5cb330) | Jun 22, 2021 |
| Lenovo        | ThinkCentre M70e 0830WK7    | Desktop     | [ef51073699](https://linux-hardware.org/?probe=ef51073699) | Jun 22, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [77fba11f44](https://linux-hardware.org/?probe=77fba11f44) | Jun 21, 2021 |
| Lenovo        | G40-30 80FY                 | Notebook    | [114ba38c36](https://linux-hardware.org/?probe=114ba38c36) | Jun 20, 2021 |
| Positivo      | POS-MI945AA                 | Desktop     | [e255c00c8a](https://linux-hardware.org/?probe=e255c00c8a) | Jun 19, 2021 |
| Lenovo        | G40-30 80FY                 | Notebook    | [0cb7e73af9](https://linux-hardware.org/?probe=0cb7e73af9) | Jun 19, 2021 |
| Wistron       | ProLiant ML110 G5           | Desktop     | [bc2d293d15](https://linux-hardware.org/?probe=bc2d293d15) | Jun 18, 2021 |
| Wistron       | ProLiant ML110 G5           | Desktop     | [ef21ac93c3](https://linux-hardware.org/?probe=ef21ac93c3) | Jun 18, 2021 |
| Dell          | Precision 7520              | Notebook    | [9b19302ca7](https://linux-hardware.org/?probe=9b19302ca7) | Jun 18, 2021 |
| Dell          | 0F6X5P A00                  | Desktop     | [4f957170f1](https://linux-hardware.org/?probe=4f957170f1) | Jun 16, 2021 |
| Dell          | 0F6X5P A00                  | Desktop     | [9b0c004cd8](https://linux-hardware.org/?probe=9b0c004cd8) | Jun 16, 2021 |
| Dell          | Inspiron N4010              | Notebook    | [d385bb7617](https://linux-hardware.org/?probe=d385bb7617) | Jun 15, 2021 |
| Dell          | Inspiron N4010              | Notebook    | [be79fbc95c](https://linux-hardware.org/?probe=be79fbc95c) | Jun 15, 2021 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [064a49e346](https://linux-hardware.org/?probe=064a49e346) | Jun 15, 2021 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [fcf3b71433](https://linux-hardware.org/?probe=fcf3b71433) | Jun 15, 2021 |
| Unknown       | Unknown                     | Desktop     | [6defc2c42b](https://linux-hardware.org/?probe=6defc2c42b) | Jun 14, 2021 |
| Unknown       | Unknown                     | Desktop     | [03c0890c33](https://linux-hardware.org/?probe=03c0890c33) | Jun 14, 2021 |
| HP            | 2129                        | Desktop     | [d33501d092](https://linux-hardware.org/?probe=d33501d092) | Jun 13, 2021 |
| Dell          | 02YYK5 A01                  | Desktop     | [74a4b076a9](https://linux-hardware.org/?probe=74a4b076a9) | Jun 13, 2021 |
| Shuttle       | FH61R                       | Desktop     | [c7bf67e0ec](https://linux-hardware.org/?probe=c7bf67e0ec) | Jun 13, 2021 |
| Samsung       | N150/N210/N220              | Notebook    | [8e03d52f53](https://linux-hardware.org/?probe=8e03d52f53) | Jun 12, 2021 |
| HP            | 0A64h                       | Desktop     | [cd257e99d6](https://linux-hardware.org/?probe=cd257e99d6) | Jun 12, 2021 |
| Lenovo        | Unknown                     | Notebook    | [108d3cba46](https://linux-hardware.org/?probe=108d3cba46) | Jun 10, 2021 |
| HP            | Stream Notebook             | Notebook    | [806c24449c](https://linux-hardware.org/?probe=806c24449c) | Jun 09, 2021 |
| Biostar       | TA870+                      | Desktop     | [c86568a140](https://linux-hardware.org/?probe=c86568a140) | Jun 09, 2021 |
| HCL Infosy... | HCL ME Laptop               | Notebook    | [0aaf1b69bc](https://linux-hardware.org/?probe=0aaf1b69bc) | Jun 08, 2021 |
| Dell          | Latitude E6520              | Notebook    | [04a7f10801](https://linux-hardware.org/?probe=04a7f10801) | Jun 08, 2021 |
| Lenovo        | G40-30 80FY                 | Notebook    | [b2fe748178](https://linux-hardware.org/?probe=b2fe748178) | Jun 08, 2021 |
| MSI           | A68HM-E33 V2                | Desktop     | [10ccc894a1](https://linux-hardware.org/?probe=10ccc894a1) | Jun 07, 2021 |
| Sony          | VGN-BX51VN                  | Notebook    | [debf4b3290](https://linux-hardware.org/?probe=debf4b3290) | Jun 06, 2021 |
| ASUSTek       | Q524UQ                      | Notebook    | [442c1c8b06](https://linux-hardware.org/?probe=442c1c8b06) | Jun 05, 2021 |
| Intel         | DG31GL AAE33912-200         | Desktop     | [1b0aa26214](https://linux-hardware.org/?probe=1b0aa26214) | Jun 05, 2021 |
| Dell          | 06NWYK A01                  | Desktop     | [b2411c10e0](https://linux-hardware.org/?probe=b2411c10e0) | Jun 04, 2021 |
| HP            | Pavilion dv5                | Notebook    | [94cfdbc88f](https://linux-hardware.org/?probe=94cfdbc88f) | Jun 03, 2021 |
| Intel         | DG31GL AAE33912-200         | Desktop     | [f9ec7fb220](https://linux-hardware.org/?probe=f9ec7fb220) | Jun 03, 2021 |
| Unknown       | Unknown                     | Notebook    | [3ce5819b57](https://linux-hardware.org/?probe=3ce5819b57) | Jun 02, 2021 |
| Apple         | MacBookPro12,1              | Notebook    | [f7f5736b13](https://linux-hardware.org/?probe=f7f5736b13) | Jun 01, 2021 |
| Sony          | VGN-BX51VN                  | Notebook    | [055903703c](https://linux-hardware.org/?probe=055903703c) | Jun 01, 2021 |
| Toshiba       | Satellite M70               | Notebook    | [67580c50df](https://linux-hardware.org/?probe=67580c50df) | Jun 01, 2021 |
| Acer          | Aspire 3100                 | Notebook    | [d38f5b09d2](https://linux-hardware.org/?probe=d38f5b09d2) | Jun 01, 2021 |
| Acer          | Aspire 3100                 | Notebook    | [fbcd23ac31](https://linux-hardware.org/?probe=fbcd23ac31) | May 31, 2021 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [0f7555a7bd](https://linux-hardware.org/?probe=0f7555a7bd) | May 30, 2021 |
| Toshiba       | Satellite P300              | Notebook    | [feb13460e8](https://linux-hardware.org/?probe=feb13460e8) | May 30, 2021 |
| Toshiba       | Satellite P300              | Notebook    | [8b5034adc9](https://linux-hardware.org/?probe=8b5034adc9) | May 30, 2021 |
| Lenovo        | G40-30 80FY                 | Notebook    | [eb9aaa55ea](https://linux-hardware.org/?probe=eb9aaa55ea) | May 30, 2021 |
| Shuttle       | SH55J V10                   | Desktop     | [8240168c32](https://linux-hardware.org/?probe=8240168c32) | May 28, 2021 |
| HP            | 8054                        | Desktop     | [cdf6d69f38](https://linux-hardware.org/?probe=cdf6d69f38) | May 28, 2021 |
| AWOW          | Book10-N34                  | Tablet      | [902ad35db3](https://linux-hardware.org/?probe=902ad35db3) | May 27, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [9fc71241e6](https://linux-hardware.org/?probe=9fc71241e6) | May 26, 2021 |
| Lenovo        | G40-30 80FY                 | Notebook    | [0c3e0e8293](https://linux-hardware.org/?probe=0c3e0e8293) | May 26, 2021 |
| ARIMA         | W351UI                      | Notebook    | [6cbffa9177](https://linux-hardware.org/?probe=6cbffa9177) | May 25, 2021 |
| Dell          | Latitude D520               | Notebook    | [7a817a0426](https://linux-hardware.org/?probe=7a817a0426) | May 25, 2021 |
| HP            | Pavilion dv6700             | Notebook    | [b30d13bbba](https://linux-hardware.org/?probe=b30d13bbba) | May 25, 2021 |
| HP            | 8054                        | Desktop     | [bcd64c3695](https://linux-hardware.org/?probe=bcd64c3695) | May 25, 2021 |
| Gigabyte      | GA-MA74GM-S2                | Desktop     | [a348b29a71](https://linux-hardware.org/?probe=a348b29a71) | May 25, 2021 |
| ASUSTek       | UX31A                       | Notebook    | [edeed3b99b](https://linux-hardware.org/?probe=edeed3b99b) | May 23, 2021 |
| ASUSTek       | UX31A                       | Notebook    | [7f750ead39](https://linux-hardware.org/?probe=7f750ead39) | May 23, 2021 |
| Google        | Candy                       | Notebook    | [f6b5b1fd81](https://linux-hardware.org/?probe=f6b5b1fd81) | May 23, 2021 |
| ASUSTek       | X540YA                      | Notebook    | [369ebd51b8](https://linux-hardware.org/?probe=369ebd51b8) | May 23, 2021 |
| ASRock        | A320M-HD                    | Desktop     | [8ee79771d4](https://linux-hardware.org/?probe=8ee79771d4) | May 22, 2021 |
| ASUSTek       | F5N                         | Notebook    | [414786c3d5](https://linux-hardware.org/?probe=414786c3d5) | May 22, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [ef65e1a0f7](https://linux-hardware.org/?probe=ef65e1a0f7) | May 21, 2021 |
| ASRock        | A320M-HD                    | Desktop     | [ce92979262](https://linux-hardware.org/?probe=ce92979262) | May 21, 2021 |
| Dell          | Latitude E7240              | Notebook    | [9e790ba3f0](https://linux-hardware.org/?probe=9e790ba3f0) | May 21, 2021 |
| Samsung       | DeskTop System              | Desktop     | [5f7fa12392](https://linux-hardware.org/?probe=5f7fa12392) | May 21, 2021 |
| Samsung       | DeskTop System              | Desktop     | [4591d38397](https://linux-hardware.org/?probe=4591d38397) | May 21, 2021 |
| HP            | 802F                        | Desktop     | [88fa80f493](https://linux-hardware.org/?probe=88fa80f493) | May 20, 2021 |
| HP            | 255 G5                      | Notebook    | [cbd6a96f91](https://linux-hardware.org/?probe=cbd6a96f91) | May 20, 2021 |
| ASUSTek       | T100TA                      | Notebook    | [bca3c06314](https://linux-hardware.org/?probe=bca3c06314) | May 20, 2021 |
| ASUSTek       | T100TA                      | Notebook    | [f232d2395d](https://linux-hardware.org/?probe=f232d2395d) | May 19, 2021 |
| Dell          | G5 5587                     | Notebook    | [39be80ad79](https://linux-hardware.org/?probe=39be80ad79) | May 19, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [d9592ead1e](https://linux-hardware.org/?probe=d9592ead1e) | May 18, 2021 |
| Gigabyte      | H110-D3A-CF                 | Desktop     | [8993d6b2c9](https://linux-hardware.org/?probe=8993d6b2c9) | May 16, 2021 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [bc6920fa56](https://linux-hardware.org/?probe=bc6920fa56) | May 16, 2021 |
| HP            | 435                         | Notebook    | [65bbde1e13](https://linux-hardware.org/?probe=65bbde1e13) | May 16, 2021 |
| HP            | 435                         | Notebook    | [fe5a82cf02](https://linux-hardware.org/?probe=fe5a82cf02) | May 16, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [03065735ff](https://linux-hardware.org/?probe=03065735ff) | May 15, 2021 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [a31ac61c4b](https://linux-hardware.org/?probe=a31ac61c4b) | May 15, 2021 |
| ASUSTek       | K54C                        | Notebook    | [af86f8b1ed](https://linux-hardware.org/?probe=af86f8b1ed) | May 14, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [713c416c24](https://linux-hardware.org/?probe=713c416c24) | May 14, 2021 |
| Dell          | Inspiron 14-3467            | Notebook    | [511f638394](https://linux-hardware.org/?probe=511f638394) | May 14, 2021 |
| MSI           | A68HM-E33 V2                | Desktop     | [fe0008fa30](https://linux-hardware.org/?probe=fe0008fa30) | May 14, 2021 |
| Acer          | V5-131                      | Notebook    | [d78c3cc207](https://linux-hardware.org/?probe=d78c3cc207) | May 14, 2021 |
| ASUSTek       | P5W DH Deluxe               | Desktop     | [66e5011d45](https://linux-hardware.org/?probe=66e5011d45) | May 13, 2021 |
| ASUSTek       | P5W DH Deluxe               | Desktop     | [0f34bf0050](https://linux-hardware.org/?probe=0f34bf0050) | May 13, 2021 |
| Dell          | Inspiron 1525               | Notebook    | [22f4b67d9b](https://linux-hardware.org/?probe=22f4b67d9b) | May 12, 2021 |
| HP            | 0AA8h                       | Desktop     | [05a670078d](https://linux-hardware.org/?probe=05a670078d) | May 12, 2021 |
| Dell          | Inspiron 7520               | Notebook    | [fdf52a6676](https://linux-hardware.org/?probe=fdf52a6676) | May 11, 2021 |
| Samsung       | RF712                       | Notebook    | [a3624b29fa](https://linux-hardware.org/?probe=a3624b29fa) | May 11, 2021 |
| Samsung       | RF712                       | Notebook    | [652fb28adb](https://linux-hardware.org/?probe=652fb28adb) | May 11, 2021 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [7fcd5a81a0](https://linux-hardware.org/?probe=7fcd5a81a0) | May 11, 2021 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [2fb86d5263](https://linux-hardware.org/?probe=2fb86d5263) | May 11, 2021 |
| Lenovo        | Unknown                     | Desktop     | [a7113d0b62](https://linux-hardware.org/?probe=a7113d0b62) | May 11, 2021 |
| HP            | ProBook 4510s               | Notebook    | [dbdd169cb4](https://linux-hardware.org/?probe=dbdd169cb4) | May 10, 2021 |
| Dell          | 0X2MKR A00                  | All in one  | [0e09b99fc0](https://linux-hardware.org/?probe=0e09b99fc0) | May 10, 2021 |
| Dell          | Inspiron 14-3467            | Notebook    | [2fd207a33d](https://linux-hardware.org/?probe=2fd207a33d) | May 10, 2021 |
| MSI           | B250M PRO-VDH               | Desktop     | [62c8feddc5](https://linux-hardware.org/?probe=62c8feddc5) | May 09, 2021 |
| Fujitsu       | FMVNF40UK                   | Notebook    | [8648b42278](https://linux-hardware.org/?probe=8648b42278) | May 09, 2021 |
| Dell          | Inspiron 14-3467            | Notebook    | [173baf5fdb](https://linux-hardware.org/?probe=173baf5fdb) | May 09, 2021 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [753357ca18](https://linux-hardware.org/?probe=753357ca18) | May 08, 2021 |
| ASRock        | N68-S                       | Desktop     | [ca240bb5bd](https://linux-hardware.org/?probe=ca240bb5bd) | May 08, 2021 |
| Lenovo        | Yoga Book C930 ZA3S         | Convertible | [6f018f175e](https://linux-hardware.org/?probe=6f018f175e) | May 06, 2021 |
| Toshiba       | Satellite P200              | Notebook    | [5fff6be5f0](https://linux-hardware.org/?probe=5fff6be5f0) | May 05, 2021 |
| Gigabyte      | H81M-S2V                    | Desktop     | [57c9671690](https://linux-hardware.org/?probe=57c9671690) | May 05, 2021 |
| Gigabyte      | H81M-S2V                    | Desktop     | [36d4d5ea8f](https://linux-hardware.org/?probe=36d4d5ea8f) | May 05, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [0c612ea2a3](https://linux-hardware.org/?probe=0c612ea2a3) | May 04, 2021 |
| Lenovo        | 406822U                     | Notebook    | [68080373ce](https://linux-hardware.org/?probe=68080373ce) | May 03, 2021 |
| Lenovo        | 406822U                     | Notebook    | [5d498a42cc](https://linux-hardware.org/?probe=5d498a42cc) | May 03, 2021 |
| ASUSTek       | X540SA                      | Notebook    | [0f79fb429b](https://linux-hardware.org/?probe=0f79fb429b) | May 02, 2021 |
| Acer          | Aspire 5538                 | Notebook    | [b01066567a](https://linux-hardware.org/?probe=b01066567a) | May 02, 2021 |
| MSI           | 2A9C                        | Desktop     | [db1be00449](https://linux-hardware.org/?probe=db1be00449) | May 02, 2021 |
| Acer          | Aspire 5538                 | Notebook    | [39c929202c](https://linux-hardware.org/?probe=39c929202c) | May 02, 2021 |
| Acer          | AOD255E                     | Notebook    | [202573d3f1](https://linux-hardware.org/?probe=202573d3f1) | May 02, 2021 |
| Lenovo        | ThinkPad T460 20FMS7DA00    | Notebook    | [21666fb8b5](https://linux-hardware.org/?probe=21666fb8b5) | May 01, 2021 |
| TrekStor      | Notebook Slim S130          | Notebook    | [3ee0251799](https://linux-hardware.org/?probe=3ee0251799) | May 01, 2021 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [d20fdbecdb](https://linux-hardware.org/?probe=d20fdbecdb) | May 01, 2021 |
| HP            | ENVY Notebook               | Notebook    | [00123e7e27](https://linux-hardware.org/?probe=00123e7e27) | May 01, 2021 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | Desktop     | [7743b27212](https://linux-hardware.org/?probe=7743b27212) | Apr 30, 2021 |
| Positivo      | S14CT01                     | Notebook    | [d6ad6f67a7](https://linux-hardware.org/?probe=d6ad6f67a7) | Apr 30, 2021 |
| Dell          | Latitude D630               | Notebook    | [ce166d946d](https://linux-hardware.org/?probe=ce166d946d) | Apr 30, 2021 |
| NEC Comput... | PC-VY25AACZ9                | Notebook    | [dc22e810b4](https://linux-hardware.org/?probe=dc22e810b4) | Apr 29, 2021 |
| Itautec       | Infoway                     | Notebook    | [01e1f5151c](https://linux-hardware.org/?probe=01e1f5151c) | Apr 28, 2021 |
| HP            | 0AA8h                       | Desktop     | [5c4fd824be](https://linux-hardware.org/?probe=5c4fd824be) | Apr 28, 2021 |
| HP            | 0AA8h                       | Desktop     | [4db2c25cef](https://linux-hardware.org/?probe=4db2c25cef) | Apr 28, 2021 |
| Dell          | 02YYK5 A01                  | Desktop     | [bd1254fe8d](https://linux-hardware.org/?probe=bd1254fe8d) | Apr 28, 2021 |
| Fujitsu       | LIFEBOOK U772               | Notebook    | [e2c74983d8](https://linux-hardware.org/?probe=e2c74983d8) | Apr 28, 2021 |
| Pegatron      | 2AD3                        | Desktop     | [7f9c809a1d](https://linux-hardware.org/?probe=7f9c809a1d) | Apr 28, 2021 |
| Lenovo        | 31900058 STD                | Desktop     | [b0c02d52c9](https://linux-hardware.org/?probe=b0c02d52c9) | Apr 27, 2021 |
| Lenovo        | 31900058 STD                | Desktop     | [ede4ef1dad](https://linux-hardware.org/?probe=ede4ef1dad) | Apr 27, 2021 |
| Lenovo        | ThinkPad X131e 3372A14      | Notebook    | [3c79681783](https://linux-hardware.org/?probe=3c79681783) | Apr 26, 2021 |
| ASUSTek       | Maximus VII RANGER          | Desktop     | [e6db3b7986](https://linux-hardware.org/?probe=e6db3b7986) | Apr 26, 2021 |
| Acer          | Aspire E5-523               | Notebook    | [7acc074ffd](https://linux-hardware.org/?probe=7acc074ffd) | Apr 26, 2021 |
| Acer          | Aspire E5-523               | Notebook    | [349b8662d9](https://linux-hardware.org/?probe=349b8662d9) | Apr 26, 2021 |
| ASRock        | B550M Steel Legend          | Desktop     | [e2125b5e62](https://linux-hardware.org/?probe=e2125b5e62) | Apr 26, 2021 |
| Unknown       | 4CoreDX90-VSTA              | Desktop     | [6410827a2f](https://linux-hardware.org/?probe=6410827a2f) | Apr 25, 2021 |
| Unknown       | 4CoreDX90-VSTA              | Desktop     | [a8c42b2d94](https://linux-hardware.org/?probe=a8c42b2d94) | Apr 25, 2021 |
| MSI           | A75A-G55                    | Desktop     | [085f17910f](https://linux-hardware.org/?probe=085f17910f) | Apr 24, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [599315872a](https://linux-hardware.org/?probe=599315872a) | Apr 24, 2021 |
| ASUSTek       | ROG Zephyrus M15 GU502LV... | Notebook    | [4cffaa3991](https://linux-hardware.org/?probe=4cffaa3991) | Apr 23, 2021 |
| Acer          | Unknown                     | Notebook    | [cd6b0eabe2](https://linux-hardware.org/?probe=cd6b0eabe2) | Apr 23, 2021 |
| Acer          | Aspire 5333                 | Notebook    | [c6227d5004](https://linux-hardware.org/?probe=c6227d5004) | Apr 23, 2021 |
| Toshiba       | IS 1422                     | Notebook    | [f52456fce9](https://linux-hardware.org/?probe=f52456fce9) | Apr 22, 2021 |
| Toshiba       | IS 1422                     | Notebook    | [9443f68502](https://linux-hardware.org/?probe=9443f68502) | Apr 22, 2021 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [2a2a56b6d4](https://linux-hardware.org/?probe=2a2a56b6d4) | Apr 22, 2021 |
| ASUSTek       | ZenBook UX331FA_UX331FA     | Notebook    | [d8340c053a](https://linux-hardware.org/?probe=d8340c053a) | Apr 22, 2021 |
| Packard Be... | EasyNote_BU45               | Notebook    | [7d3e06e670](https://linux-hardware.org/?probe=7d3e06e670) | Apr 21, 2021 |
| Packard Be... | EasyNote_BU45               | Notebook    | [c97faabab8](https://linux-hardware.org/?probe=c97faabab8) | Apr 21, 2021 |
| Dell          | 0HD5W2 A01                  | Desktop     | [14f5b0daaf](https://linux-hardware.org/?probe=14f5b0daaf) | Apr 19, 2021 |
| Dell          | Latitude D620               | Notebook    | [116568909e](https://linux-hardware.org/?probe=116568909e) | Apr 19, 2021 |
| MSI           | X399 GAMING PRO CARBON A... | Desktop     | [f1d84c2d34](https://linux-hardware.org/?probe=f1d84c2d34) | Apr 18, 2021 |
| Microsoft     | Surface Laptop Go           | Tablet      | [d34ecf1b95](https://linux-hardware.org/?probe=d34ecf1b95) | Apr 18, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [dbc571160d](https://linux-hardware.org/?probe=dbc571160d) | Apr 18, 2021 |
| ASUSTek       | B150 PRO GAMING D3          | Desktop     | [5a72089fcc](https://linux-hardware.org/?probe=5a72089fcc) | Apr 17, 2021 |
| HC            | HCAR357-MI V1.0             | Desktop     | [32f62b91ef](https://linux-hardware.org/?probe=32f62b91ef) | Apr 17, 2021 |
| Dell          | Latitude D520               | Notebook    | [4e8b58ab28](https://linux-hardware.org/?probe=4e8b58ab28) | Apr 16, 2021 |
| Acer          | Aspire 5333                 | Notebook    | [2171d74173](https://linux-hardware.org/?probe=2171d74173) | Apr 15, 2021 |
| Acer          | Aspire 5333                 | Notebook    | [dd4fee2ece](https://linux-hardware.org/?probe=dd4fee2ece) | Apr 15, 2021 |
| Lenovo        | IdeaCentre K330             | Desktop     | [daf1de2c2a](https://linux-hardware.org/?probe=daf1de2c2a) | Apr 15, 2021 |
| Toshiba       | Satellite C55-A             | Notebook    | [6670c58f24](https://linux-hardware.org/?probe=6670c58f24) | Apr 15, 2021 |
| Dell          | Inspiron 5759               | Notebook    | [7fcec2352e](https://linux-hardware.org/?probe=7fcec2352e) | Apr 15, 2021 |
| HP            | Pavilion dv5                | Notebook    | [901dd6f4bc](https://linux-hardware.org/?probe=901dd6f4bc) | Apr 14, 2021 |
| Toshiba       | Satellite C55-A             | Notebook    | [7862f9a6e6](https://linux-hardware.org/?probe=7862f9a6e6) | Apr 14, 2021 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [6cc145348c](https://linux-hardware.org/?probe=6cc145348c) | Apr 11, 2021 |
| Toshiba       | Satellite P200              | Notebook    | [f6b3c134f2](https://linux-hardware.org/?probe=f6b3c134f2) | Apr 11, 2021 |
| HP            | EliteBook 850 G5            | Notebook    | [8351e652e0](https://linux-hardware.org/?probe=8351e652e0) | Apr 11, 2021 |
| AMD           | Inagua CRB                  | Desktop     | [8f12c8050f](https://linux-hardware.org/?probe=8f12c8050f) | Apr 11, 2021 |
| Dell          | Latitude D620               | Notebook    | [f0eb74cd27](https://linux-hardware.org/?probe=f0eb74cd27) | Apr 11, 2021 |
| Dell          | Latitude D620               | Notebook    | [599e543d6b](https://linux-hardware.org/?probe=599e543d6b) | Apr 11, 2021 |
| Gigabyte      | B75M-D3V                    | Desktop     | [e99429099b](https://linux-hardware.org/?probe=e99429099b) | Apr 10, 2021 |
| NEC Comput... | PC-VY25AACZ9                | Notebook    | [24f7a90612](https://linux-hardware.org/?probe=24f7a90612) | Apr 10, 2021 |
| Lenovo        | ThinkPad W540 20BHS1MX00    | Notebook    | [762a1d15ab](https://linux-hardware.org/?probe=762a1d15ab) | Apr 09, 2021 |
| Toshiba       | dynabook R731/E             | Notebook    | [108510a130](https://linux-hardware.org/?probe=108510a130) | Apr 08, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [cdf6743f68](https://linux-hardware.org/?probe=cdf6743f68) | Apr 08, 2021 |
| Positivo      | Mobile                      | Notebook    | [340616710c](https://linux-hardware.org/?probe=340616710c) | Apr 07, 2021 |
| Toshiba       | QOSMIO X300                 | Notebook    | [7f3b22129c](https://linux-hardware.org/?probe=7f3b22129c) | Apr 07, 2021 |
| Toshiba       | QOSMIO X300                 | Notebook    | [c1e66d512d](https://linux-hardware.org/?probe=c1e66d512d) | Apr 07, 2021 |
| Unknown       | DH61BR G32662-203           | Desktop     | [5ade6cc464](https://linux-hardware.org/?probe=5ade6cc464) | Apr 06, 2021 |
| Unknown       | DH61BR G32662-203           | Desktop     | [81fe29e1f4](https://linux-hardware.org/?probe=81fe29e1f4) | Apr 06, 2021 |
| HP            | 15                          | Notebook    | [69d2aa2538](https://linux-hardware.org/?probe=69d2aa2538) | Apr 05, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [e06e6b98d6](https://linux-hardware.org/?probe=e06e6b98d6) | Apr 05, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [b45b1c9c54](https://linux-hardware.org/?probe=b45b1c9c54) | Apr 05, 2021 |
| HP            | EliteBook Folio 9480m       | Notebook    | [c878c10e7b](https://linux-hardware.org/?probe=c878c10e7b) | Apr 03, 2021 |
| Gigabyte      | AERO 15-SA                  | Notebook    | [b162082414](https://linux-hardware.org/?probe=b162082414) | Apr 03, 2021 |
| Intel         | DG41MJ AAE54659-206         | Desktop     | [d7673aebbf](https://linux-hardware.org/?probe=d7673aebbf) | Apr 02, 2021 |
| Acer          | Predator G3610              | Desktop     | [58f942e8c3](https://linux-hardware.org/?probe=58f942e8c3) | Apr 02, 2021 |
| Compaq        | Presario CQ-17              | Notebook    | [d1ae1543d9](https://linux-hardware.org/?probe=d1ae1543d9) | Apr 02, 2021 |
| HP            | Stream Notebook PC 11       | Notebook    | [a2a25ee9ac](https://linux-hardware.org/?probe=a2a25ee9ac) | Apr 02, 2021 |
| HP            | Stream Notebook PC 11       | Notebook    | [bb9c9dc740](https://linux-hardware.org/?probe=bb9c9dc740) | Apr 01, 2021 |
| Dell          | 0GWHMW A01                  | Desktop     | [95e63df251](https://linux-hardware.org/?probe=95e63df251) | Mar 31, 2021 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [276153c011](https://linux-hardware.org/?probe=276153c011) | Mar 31, 2021 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [7dc5cad98d](https://linux-hardware.org/?probe=7dc5cad98d) | Mar 31, 2021 |
| Gigabyte      | AERO 15-SA                  | Notebook    | [26957c118d](https://linux-hardware.org/?probe=26957c118d) | Mar 30, 2021 |
| Toshiba       | QOSMIO F50                  | Notebook    | [d9d565847f](https://linux-hardware.org/?probe=d9d565847f) | Mar 29, 2021 |
| MSI           | B250M MORTAR                | Desktop     | [58329aa9f7](https://linux-hardware.org/?probe=58329aa9f7) | Mar 29, 2021 |
| HP            | ProBook 4540s               | Notebook    | [94b1064fc6](https://linux-hardware.org/?probe=94b1064fc6) | Mar 28, 2021 |
| HP            | ProBook 4540s               | Notebook    | [c6e6b05536](https://linux-hardware.org/?probe=c6e6b05536) | Mar 28, 2021 |
| ASUSTek       | X200CA                      | Notebook    | [fd66b80491](https://linux-hardware.org/?probe=fd66b80491) | Mar 28, 2021 |
| Gigabyte      | AERO 15-SA                  | Notebook    | [536dfb993f](https://linux-hardware.org/?probe=536dfb993f) | Mar 28, 2021 |
| Lenovo        | ThinkPad T430s 2356DH2      | Notebook    | [86d756fb89](https://linux-hardware.org/?probe=86d756fb89) | Mar 27, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T8S... | Notebook    | [327b8352df](https://linux-hardware.org/?probe=327b8352df) | Mar 27, 2021 |
| MSI           | B250M MORTAR                | Desktop     | [7bf436d1fd](https://linux-hardware.org/?probe=7bf436d1fd) | Mar 27, 2021 |
| MSI           | MS-A912 200                 | All in one  | [24b782cfdd](https://linux-hardware.org/?probe=24b782cfdd) | Mar 26, 2021 |
| HP            | Mini 110-1100               | Notebook    | [05039f09e2](https://linux-hardware.org/?probe=05039f09e2) | Mar 26, 2021 |
| HP            | Mini 110-1100               | Notebook    | [5192a10f03](https://linux-hardware.org/?probe=5192a10f03) | Mar 26, 2021 |
| ASUSTek       | 1011PX                      | Notebook    | [3d23090e46](https://linux-hardware.org/?probe=3d23090e46) | Mar 26, 2021 |
| HP            | Compaq Presario CQ61        | Notebook    | [58db0eef1f](https://linux-hardware.org/?probe=58db0eef1f) | Mar 25, 2021 |
| Gigabyte      | F2A88XM-HD3P                | Desktop     | [aab9ef0b36](https://linux-hardware.org/?probe=aab9ef0b36) | Mar 24, 2021 |
| MSI           | MS-A912 200                 | All in one  | [9d0ab9ce9f](https://linux-hardware.org/?probe=9d0ab9ce9f) | Mar 23, 2021 |
| Medion        | MS-7646                     | Desktop     | [b5d6b375f2](https://linux-hardware.org/?probe=b5d6b375f2) | Mar 21, 2021 |
| Lenovo        | ThinkPad L470 20J4000LGE    | Notebook    | [125911ba8d](https://linux-hardware.org/?probe=125911ba8d) | Mar 21, 2021 |
| Apple         | MacBookPro5,4               | Notebook    | [e1ff6cd3c6](https://linux-hardware.org/?probe=e1ff6cd3c6) | Mar 20, 2021 |
| ASUSTek       | X555LD                      | Notebook    | [cf0c496200](https://linux-hardware.org/?probe=cf0c496200) | Mar 20, 2021 |
| HP            | ProBook 470 G1              | Notebook    | [7358a0ab88](https://linux-hardware.org/?probe=7358a0ab88) | Mar 20, 2021 |
| HP            | ProBook 470 G1              | Notebook    | [9a754ec32f](https://linux-hardware.org/?probe=9a754ec32f) | Mar 20, 2021 |
| Lenovo        | ThinkPad T420 41786UU       | Notebook    | [3965832137](https://linux-hardware.org/?probe=3965832137) | Mar 20, 2021 |
| Gigabyte      | H110-D3A-CF                 | Desktop     | [3a935344f1](https://linux-hardware.org/?probe=3a935344f1) | Mar 20, 2021 |
| Dell          | Dimension E521              | Desktop     | [5b40d0affe](https://linux-hardware.org/?probe=5b40d0affe) | Mar 19, 2021 |
| Dell          | Dimension E521              | Desktop     | [ba2b49690b](https://linux-hardware.org/?probe=ba2b49690b) | Mar 18, 2021 |
| Dell          | Latitude D610               | Notebook    | [faaf3b4f3d](https://linux-hardware.org/?probe=faaf3b4f3d) | Mar 18, 2021 |
| Dell          | 0M858N A01                  | Desktop     | [6ddb3dd318](https://linux-hardware.org/?probe=6ddb3dd318) | Mar 17, 2021 |
| Pegatron      | 2ACD                        | Desktop     | [4614f28db7](https://linux-hardware.org/?probe=4614f28db7) | Mar 15, 2021 |
| Panasonic     | CF-31JEGAX1M                | Notebook    | [4636e611d8](https://linux-hardware.org/?probe=4636e611d8) | Mar 14, 2021 |
| Gigabyte      | GA-MA78GM-US2H              | Desktop     | [0f6037a19e](https://linux-hardware.org/?probe=0f6037a19e) | Mar 14, 2021 |
| Lenovo        | ThinkPad Edge E531 68852... | Notebook    | [9707772e02](https://linux-hardware.org/?probe=9707772e02) | Mar 13, 2021 |
| Acer          | Aspire 5610Z                | Notebook    | [ba43bff53e](https://linux-hardware.org/?probe=ba43bff53e) | Mar 13, 2021 |
| ASUSTek       | E402SA                      | Notebook    | [eec3171b5f](https://linux-hardware.org/?probe=eec3171b5f) | Mar 13, 2021 |
| ASUSTek       | P5P43TD                     | Desktop     | [f0539d32a3](https://linux-hardware.org/?probe=f0539d32a3) | Mar 13, 2021 |
| ASUSTek       | P5P43TD                     | Desktop     | [b3f2fab399](https://linux-hardware.org/?probe=b3f2fab399) | Mar 13, 2021 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | Notebook    | [85703241b5](https://linux-hardware.org/?probe=85703241b5) | Mar 13, 2021 |
| MSI           | GX60 1AC                    | Notebook    | [774db4f685](https://linux-hardware.org/?probe=774db4f685) | Mar 12, 2021 |
| AZW           | U57                         | Mini pc     | [7840462c30](https://linux-hardware.org/?probe=7840462c30) | Mar 12, 2021 |
| Dell          | 0CXTWJ A00                  | All in one  | [5c781b927f](https://linux-hardware.org/?probe=5c781b927f) | Mar 12, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [c4237133e9](https://linux-hardware.org/?probe=c4237133e9) | Mar 10, 2021 |
| Hometech      | ELITE TAB 10                | Notebook    | [8bfad5d181](https://linux-hardware.org/?probe=8bfad5d181) | Mar 09, 2021 |
| Fujitsu       | LIFEBOOK AH531/GFO          | Notebook    | [8a0395042b](https://linux-hardware.org/?probe=8a0395042b) | Mar 08, 2021 |
| Toshiba       | Satellite P300-17Q          | Notebook    | [72b5282501](https://linux-hardware.org/?probe=72b5282501) | Mar 08, 2021 |
| Gateway       | NV55C                       | Notebook    | [3f5377a2de](https://linux-hardware.org/?probe=3f5377a2de) | Mar 08, 2021 |
| Alienware     | 0H869M A00                  | Desktop     | [28760e307c](https://linux-hardware.org/?probe=28760e307c) | Mar 08, 2021 |
| Gigabyte      | GA-MA69VM-S2                | Desktop     | [3fa7fe2918](https://linux-hardware.org/?probe=3fa7fe2918) | Mar 08, 2021 |
| Acer          | Aspire 5735                 | Notebook    | [cde827bd2e](https://linux-hardware.org/?probe=cde827bd2e) | Mar 07, 2021 |
| Acer          | Aspire 5735                 | Notebook    | [9730b9273d](https://linux-hardware.org/?probe=9730b9273d) | Mar 07, 2021 |
| Acer          | Predator G3610              | Desktop     | [49b3263bb1](https://linux-hardware.org/?probe=49b3263bb1) | Mar 07, 2021 |
| Dell          | 0RD203                      | Desktop     | [3a9c112992](https://linux-hardware.org/?probe=3a9c112992) | Mar 07, 2021 |
| Dell          | 0RD203                      | Desktop     | [00a7560365](https://linux-hardware.org/?probe=00a7560365) | Mar 07, 2021 |
| HP            | 8457                        | Mini pc     | [c15e7f2a47](https://linux-hardware.org/?probe=c15e7f2a47) | Mar 06, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [273cda0045](https://linux-hardware.org/?probe=273cda0045) | Mar 05, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [f5600011bb](https://linux-hardware.org/?probe=f5600011bb) | Mar 05, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [19e8d1a155](https://linux-hardware.org/?probe=19e8d1a155) | Mar 05, 2021 |
| Unknown       | Unknown                     | Tablet      | [315c09fd74](https://linux-hardware.org/?probe=315c09fd74) | Mar 04, 2021 |
| Toshiba       | Satellite U920t             | Notebook    | [26b9e489aa](https://linux-hardware.org/?probe=26b9e489aa) | Mar 04, 2021 |
| IBM           | 8172W5K                     | Desktop     | [2b1eed5f2c](https://linux-hardware.org/?probe=2b1eed5f2c) | Mar 02, 2021 |
| Positivo      | POS-MIG31AG                 | Desktop     | [de72249cdc](https://linux-hardware.org/?probe=de72249cdc) | Mar 02, 2021 |
| Dell          | 0K216C                      | Desktop     | [1f4fb8cc42](https://linux-hardware.org/?probe=1f4fb8cc42) | Mar 02, 2021 |
| Dell          | 0PU052                      | Desktop     | [3839b34d2b](https://linux-hardware.org/?probe=3839b34d2b) | Mar 01, 2021 |
| Dell          | 0K216C                      | Desktop     | [edbaf73f30](https://linux-hardware.org/?probe=edbaf73f30) | Feb 28, 2021 |
| Toshiba       | Satellite NB10t-A           | Notebook    | [c1c084e42c](https://linux-hardware.org/?probe=c1c084e42c) | Feb 28, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [dfc0744775](https://linux-hardware.org/?probe=dfc0744775) | Feb 28, 2021 |
| Multilaser    | PC024                       | Notebook    | [abaddb333b](https://linux-hardware.org/?probe=abaddb333b) | Feb 27, 2021 |
| Multilaser    | PC024                       | Notebook    | [54e46489ac](https://linux-hardware.org/?probe=54e46489ac) | Feb 27, 2021 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [6f49c2288d](https://linux-hardware.org/?probe=6f49c2288d) | Feb 27, 2021 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [fd2bf42cc7](https://linux-hardware.org/?probe=fd2bf42cc7) | Feb 27, 2021 |
| MSI           | MPG Z490 GAMING PLUS        | Desktop     | [d2f0487234](https://linux-hardware.org/?probe=d2f0487234) | Feb 27, 2021 |
| HP            | Compaq 6510b (GR690ET#AB... | Notebook    | [b9b8fa550a](https://linux-hardware.org/?probe=b9b8fa550a) | Feb 26, 2021 |
| HP            | Compaq 6510b (GR690ET#AB... | Notebook    | [4529dc90b2](https://linux-hardware.org/?probe=4529dc90b2) | Feb 26, 2021 |
| ASUSTek       | M2A-MX                      | Desktop     | [38f069f44b](https://linux-hardware.org/?probe=38f069f44b) | Feb 26, 2021 |
| ASUSTek       | X555LD                      | Notebook    | [665cf4701a](https://linux-hardware.org/?probe=665cf4701a) | Feb 25, 2021 |
| Dell          | Inspiron 3543               | Notebook    | [cfc4c1a529](https://linux-hardware.org/?probe=cfc4c1a529) | Feb 24, 2021 |
| ASUSTek       | X751SJ                      | Notebook    | [81295695f3](https://linux-hardware.org/?probe=81295695f3) | Feb 24, 2021 |
| MSI           | Z97 XPOWER AC               | Desktop     | [c627833398](https://linux-hardware.org/?probe=c627833398) | Feb 23, 2021 |
| Intel         | DG45ID AAE27729-310         | Desktop     | [0935f61041](https://linux-hardware.org/?probe=0935f61041) | Feb 23, 2021 |
| Dell          | Inspiron 3543               | Notebook    | [6b53f592ed](https://linux-hardware.org/?probe=6b53f592ed) | Feb 22, 2021 |
| HP            | ZBook 17 G2                 | Notebook    | [7213996a6e](https://linux-hardware.org/?probe=7213996a6e) | Feb 22, 2021 |
| Samsung       | 370E4K                      | Notebook    | [9d25cf824e](https://linux-hardware.org/?probe=9d25cf824e) | Feb 20, 2021 |
| Dell          | Inspiron 7737               | Notebook    | [ffaf611204](https://linux-hardware.org/?probe=ffaf611204) | Feb 20, 2021 |
| ASUSTek       | K52N                        | Notebook    | [0139461f57](https://linux-hardware.org/?probe=0139461f57) | Feb 19, 2021 |
| Gigabyte      | B460M DS3H                  | Desktop     | [fe95f7aef8](https://linux-hardware.org/?probe=fe95f7aef8) | Feb 19, 2021 |
| ASUSTek       | U36SD                       | Notebook    | [981c7e8da7](https://linux-hardware.org/?probe=981c7e8da7) | Feb 19, 2021 |
| ASUSTek       | X550ZA                      | Notebook    | [503250e6f1](https://linux-hardware.org/?probe=503250e6f1) | Feb 19, 2021 |
| HP            | 255 G5                      | Notebook    | [2ffdcec174](https://linux-hardware.org/?probe=2ffdcec174) | Feb 19, 2021 |
| HP            | 86F3 00100                  | All in one  | [a444431ab4](https://linux-hardware.org/?probe=a444431ab4) | Feb 18, 2021 |
| ASUSTek       | P7P55D-E LX                 | Desktop     | [55170d3db9](https://linux-hardware.org/?probe=55170d3db9) | Feb 18, 2021 |
| Pegatron      | NARRA5                      | Desktop     | [4618dd21fe](https://linux-hardware.org/?probe=4618dd21fe) | Feb 17, 2021 |
| Dell          | XPS 13 9333                 | Notebook    | [0166a2e7b9](https://linux-hardware.org/?probe=0166a2e7b9) | Feb 17, 2021 |
| Dell          | XPS 13 9333                 | Notebook    | [4e08aeb5c5](https://linux-hardware.org/?probe=4e08aeb5c5) | Feb 17, 2021 |
| MSI           | B450M PRO-VDH               | Desktop     | [5fdc562401](https://linux-hardware.org/?probe=5fdc562401) | Feb 16, 2021 |
| MSI           | B450M PRO-VDH               | Desktop     | [cca1ddda94](https://linux-hardware.org/?probe=cca1ddda94) | Feb 16, 2021 |
| Dell          | 0200DY A03                  | Desktop     | [b0f9340f5c](https://linux-hardware.org/?probe=b0f9340f5c) | Feb 15, 2021 |
| HP            | Compaq Presario CQ61        | Notebook    | [e72ebb6663](https://linux-hardware.org/?probe=e72ebb6663) | Feb 14, 2021 |
| Toshiba       | Satellite L855              | Notebook    | [941b946e5e](https://linux-hardware.org/?probe=941b946e5e) | Feb 14, 2021 |
| Toshiba       | Satellite L855              | Notebook    | [4cfe29288e](https://linux-hardware.org/?probe=4cfe29288e) | Feb 14, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [622900874e](https://linux-hardware.org/?probe=622900874e) | Feb 14, 2021 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [fd9c733ca2](https://linux-hardware.org/?probe=fd9c733ca2) | Feb 14, 2021 |
| ASRock        | N68C-S                      | Desktop     | [5c775cdfce](https://linux-hardware.org/?probe=5c775cdfce) | Feb 14, 2021 |
| HP            | Pavilion dv6000 (RR398EA... | Notebook    | [2b5732689b](https://linux-hardware.org/?probe=2b5732689b) | Feb 13, 2021 |
| HP            | Pavilion dv6000 (RR398EA... | Notebook    | [0005b66219](https://linux-hardware.org/?probe=0005b66219) | Feb 13, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [bbc90d233b](https://linux-hardware.org/?probe=bbc90d233b) | Feb 13, 2021 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [6a47cb6e65](https://linux-hardware.org/?probe=6a47cb6e65) | Feb 13, 2021 |
| Dell          | 0200DY A03                  | Desktop     | [7c242f4e40](https://linux-hardware.org/?probe=7c242f4e40) | Feb 13, 2021 |
| HP            | ENVY 15                     | Notebook    | [ab6ef5e4cf](https://linux-hardware.org/?probe=ab6ef5e4cf) | Feb 12, 2021 |
| HP            | Compaq Presario CQ61        | Notebook    | [bcf179fa51](https://linux-hardware.org/?probe=bcf179fa51) | Feb 12, 2021 |
| ASUSTek       | X510UAR                     | Notebook    | [e194fe9742](https://linux-hardware.org/?probe=e194fe9742) | Feb 12, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [c7c4c6fe88](https://linux-hardware.org/?probe=c7c4c6fe88) | Feb 11, 2021 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | Desktop     | [8999187095](https://linux-hardware.org/?probe=8999187095) | Feb 10, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1070... | Notebook    | [b14a3d0adb](https://linux-hardware.org/?probe=b14a3d0adb) | Feb 09, 2021 |
| Acer          | Spin SP515-51N              | Convertible | [cf6164516e](https://linux-hardware.org/?probe=cf6164516e) | Feb 08, 2021 |
| NEC Comput... | PC-VY12FBHEW                | Notebook    | [c65bc992c6](https://linux-hardware.org/?probe=c65bc992c6) | Feb 08, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [b58275d29b](https://linux-hardware.org/?probe=b58275d29b) | Feb 08, 2021 |
| Dell          | Inspiron 1012               | Notebook    | [e5ec198a6d](https://linux-hardware.org/?probe=e5ec198a6d) | Feb 07, 2021 |
| HP            | Stream Laptop 11-y0XX       | Notebook    | [1a6227c6cf](https://linux-hardware.org/?probe=1a6227c6cf) | Feb 07, 2021 |
| Toshiba       | Satellite Pro L550          | Notebook    | [b6870f2fea](https://linux-hardware.org/?probe=b6870f2fea) | Feb 07, 2021 |
| Lenovo        | ThinkPad R61 8943DKG        | Notebook    | [fd7beeb674](https://linux-hardware.org/?probe=fd7beeb674) | Feb 06, 2021 |
| Lenovo        | ThinkPad R61 8943DKG        | Notebook    | [6a3c7e3263](https://linux-hardware.org/?probe=6a3c7e3263) | Feb 06, 2021 |
| Foxconn       | 2AA9                        | Desktop     | [f345ae2db5](https://linux-hardware.org/?probe=f345ae2db5) | Feb 06, 2021 |
| Acer          | TravelMate 6592             | Notebook    | [9b2c049705](https://linux-hardware.org/?probe=9b2c049705) | Feb 06, 2021 |
| Microsoft     | Surface 3                   | Tablet      | [2b55730d0b](https://linux-hardware.org/?probe=2b55730d0b) | Feb 05, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [067995d50f](https://linux-hardware.org/?probe=067995d50f) | Feb 05, 2021 |
| Unknown       | ARCELIK ANB 573 D SR        | Notebook    | [7ef8639d95](https://linux-hardware.org/?probe=7ef8639d95) | Feb 04, 2021 |
| Unknown       | ARCELIK ANB 573 D SR        | Notebook    | [70b60f77cc](https://linux-hardware.org/?probe=70b60f77cc) | Feb 04, 2021 |
| Lenovo        | G560 0679                   | Notebook    | [ebf2298ba0](https://linux-hardware.org/?probe=ebf2298ba0) | Feb 04, 2021 |
| Dell          | Latitude E6400              | Notebook    | [99e1f46388](https://linux-hardware.org/?probe=99e1f46388) | Feb 03, 2021 |
| HP            | EliteBook 2560p             | Notebook    | [f741035d0d](https://linux-hardware.org/?probe=f741035d0d) | Feb 02, 2021 |
| Dell          | Latitude D520               | Notebook    | [038841ada5](https://linux-hardware.org/?probe=038841ada5) | Feb 02, 2021 |
| HP            | 2ADE                        | Desktop     | [2ee5093250](https://linux-hardware.org/?probe=2ee5093250) | Feb 02, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [2dd10bb86f](https://linux-hardware.org/?probe=2dd10bb86f) | Feb 01, 2021 |
| HP            | G42                         | Notebook    | [532d273aec](https://linux-hardware.org/?probe=532d273aec) | Feb 01, 2021 |
| Lenovo        | ThinkPad Edge E531 68852... | Notebook    | [18ceaaebaf](https://linux-hardware.org/?probe=18ceaaebaf) | Feb 01, 2021 |
| Lenovo        | ThinkPad Edge E531 68852... | Notebook    | [90149b2d99](https://linux-hardware.org/?probe=90149b2d99) | Feb 01, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [f3dbe33c7c](https://linux-hardware.org/?probe=f3dbe33c7c) | Feb 01, 2021 |
| Dell          | 0C27VV A00                  | Desktop     | [6c44704d47](https://linux-hardware.org/?probe=6c44704d47) | Jan 31, 2021 |
| ASUSTek       | X555LD                      | Notebook    | [eb3be3f63f](https://linux-hardware.org/?probe=eb3be3f63f) | Jan 31, 2021 |
| Sony          | VGN-AR630E                  | Notebook    | [2e155fc628](https://linux-hardware.org/?probe=2e155fc628) | Jan 31, 2021 |
| ASUSTek       | B85M-E                      | Desktop     | [09183ba425](https://linux-hardware.org/?probe=09183ba425) | Jan 31, 2021 |
| Panasonic     | CF-30K3PAZN2                | Notebook    | [9a9c09f250](https://linux-hardware.org/?probe=9a9c09f250) | Jan 30, 2021 |
| ASUSTek       | P7P55D-E LX                 | Desktop     | [dcfcadb84a](https://linux-hardware.org/?probe=dcfcadb84a) | Jan 30, 2021 |
| ASUSTek       | P7P55D-E LX                 | Desktop     | [99c7263b04](https://linux-hardware.org/?probe=99c7263b04) | Jan 30, 2021 |
| Panasonic     | CF-30K3PAZN2                | Notebook    | [a1b4116c85](https://linux-hardware.org/?probe=a1b4116c85) | Jan 30, 2021 |
| ASUSTek       | U36SD                       | Notebook    | [5267c17fbb](https://linux-hardware.org/?probe=5267c17fbb) | Jan 30, 2021 |
| HP            | Pavilion zd8000 (PW934EA... | Notebook    | [640a4d1741](https://linux-hardware.org/?probe=640a4d1741) | Jan 29, 2021 |
| Olidata       | U40SI1                      | Notebook    | [60dd97276a](https://linux-hardware.org/?probe=60dd97276a) | Jan 28, 2021 |
| Olidata       | U40SI1                      | Notebook    | [cca9468e85](https://linux-hardware.org/?probe=cca9468e85) | Jan 28, 2021 |
| ASUSTek       | U36SD                       | Notebook    | [15288996d1](https://linux-hardware.org/?probe=15288996d1) | Jan 28, 2021 |
| Lenovo        | ThinkPad X240 20AM006KMN    | Notebook    | [7c40d08353](https://linux-hardware.org/?probe=7c40d08353) | Jan 28, 2021 |
| Acer          | Aspire E1-570G              | Notebook    | [19e6d6afd7](https://linux-hardware.org/?probe=19e6d6afd7) | Jan 28, 2021 |
| Toshiba       | Satellite L500              | Notebook    | [f9341665f3](https://linux-hardware.org/?probe=f9341665f3) | Jan 27, 2021 |
| Dell          | Latitude E5470              | Notebook    | [72db68119a](https://linux-hardware.org/?probe=72db68119a) | Jan 27, 2021 |
| Gigabyte      | G41M-Combo                  | Desktop     | [a85f6c4759](https://linux-hardware.org/?probe=a85f6c4759) | Jan 27, 2021 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | Notebook    | [00f0257410](https://linux-hardware.org/?probe=00f0257410) | Jan 27, 2021 |
| HP            | ZBook 17 G6                 | Notebook    | [63c3d95bd5](https://linux-hardware.org/?probe=63c3d95bd5) | Jan 27, 2021 |
| Dell          | Latitude D630               | Notebook    | [efc4256a09](https://linux-hardware.org/?probe=efc4256a09) | Jan 26, 2021 |
| Dell          | Latitude E6400              | Notebook    | [91be1b1bd7](https://linux-hardware.org/?probe=91be1b1bd7) | Jan 26, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [4e52d174c9](https://linux-hardware.org/?probe=4e52d174c9) | Jan 26, 2021 |
| Acer          | Aspire E1-570G              | Notebook    | [f8f4880823](https://linux-hardware.org/?probe=f8f4880823) | Jan 26, 2021 |
| ASUSTek       | TUF B360M-PLUS GAMING/BR    | Desktop     | [b8b7fd3f20](https://linux-hardware.org/?probe=b8b7fd3f20) | Jan 25, 2021 |
| Toshiba       | Satellite L635              | Notebook    | [ca6d27fd9c](https://linux-hardware.org/?probe=ca6d27fd9c) | Jan 24, 2021 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [de29897632](https://linux-hardware.org/?probe=de29897632) | Jan 23, 2021 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | Desktop     | [64b170a0ff](https://linux-hardware.org/?probe=64b170a0ff) | Jan 23, 2021 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | Notebook    | [158b3578e3](https://linux-hardware.org/?probe=158b3578e3) | Jan 23, 2021 |
| Unknown       | Unknown                     | Notebook    | [0c6628ea31](https://linux-hardware.org/?probe=0c6628ea31) | Jan 23, 2021 |
| Dell          | Latitude E6400              | Notebook    | [fc052ebe8f](https://linux-hardware.org/?probe=fc052ebe8f) | Jan 23, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [0dc84304c0](https://linux-hardware.org/?probe=0dc84304c0) | Jan 22, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [b27a2d92e2](https://linux-hardware.org/?probe=b27a2d92e2) | Jan 22, 2021 |
| ASUSTek       | M4N68T-M LE                 | Desktop     | [b5c6a734f2](https://linux-hardware.org/?probe=b5c6a734f2) | Jan 21, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [f124b7e7bb](https://linux-hardware.org/?probe=f124b7e7bb) | Jan 21, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [a0db065ae8](https://linux-hardware.org/?probe=a0db065ae8) | Jan 21, 2021 |
| Lenovo        | ThinkCentre M90 5485W2H     | Desktop     | [4765bdb0d2](https://linux-hardware.org/?probe=4765bdb0d2) | Jan 20, 2021 |
| Sony          | SVE14A2V1EW                 | Notebook    | [baaf829145](https://linux-hardware.org/?probe=baaf829145) | Jan 20, 2021 |
| ASRock        | Z97 Extreme4                | Desktop     | [87b97328a8](https://linux-hardware.org/?probe=87b97328a8) | Jan 20, 2021 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [db6d4d3deb](https://linux-hardware.org/?probe=db6d4d3deb) | Jan 20, 2021 |
| ASUSTek       | Acacia                      | Desktop     | [1ec9e34121](https://linux-hardware.org/?probe=1ec9e34121) | Jan 18, 2021 |
| HP            | ProBook 6560b               | Notebook    | [4771c30f72](https://linux-hardware.org/?probe=4771c30f72) | Jan 18, 2021 |
| Lenovo        | ThinkPad X220 4290NC9       | Notebook    | [f90fbc6c88](https://linux-hardware.org/?probe=f90fbc6c88) | Jan 18, 2021 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [1dfeaa1b83](https://linux-hardware.org/?probe=1dfeaa1b83) | Jan 17, 2021 |
| Toshiba       | Satellite L850-1HP          | Notebook    | [1e0aa7f353](https://linux-hardware.org/?probe=1e0aa7f353) | Jan 17, 2021 |
| Toshiba       | Satellite U920t             | Notebook    | [566f573caf](https://linux-hardware.org/?probe=566f573caf) | Jan 17, 2021 |
| Itautec       | Infoway a7420               | Notebook    | [d32d9bf816](https://linux-hardware.org/?probe=d32d9bf816) | Jan 16, 2021 |
| Quanta        | MW1/HW1                     | Notebook    | [ebab0a47f8](https://linux-hardware.org/?probe=ebab0a47f8) | Jan 16, 2021 |
| Lenovo        | 370C SDK0J40700 WIN 3258... | All in one  | [e678313d40](https://linux-hardware.org/?probe=e678313d40) | Jan 15, 2021 |
| Unknown       | Unknown                     | Notebook    | [1fddcd5f95](https://linux-hardware.org/?probe=1fddcd5f95) | Jan 15, 2021 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [ecaaa0fccb](https://linux-hardware.org/?probe=ecaaa0fccb) | Jan 14, 2021 |
| Unknown       | Unknown                     | Desktop     | [85c5454ed1](https://linux-hardware.org/?probe=85c5454ed1) | Jan 14, 2021 |
| Lenovo        | ThinkPad Edge E530 3259A... | Notebook    | [e7ef3a9e86](https://linux-hardware.org/?probe=e7ef3a9e86) | Jan 14, 2021 |
| HP            | 834F                        | Desktop     | [c849bbc95a](https://linux-hardware.org/?probe=c849bbc95a) | Jan 14, 2021 |
| MiTAC         | E220 6A7                    | Desktop     | [0d75e5ba34](https://linux-hardware.org/?probe=0d75e5ba34) | Jan 14, 2021 |
| IP3 Tech      | AB1                         | Mini pc     | [511b8b9080](https://linux-hardware.org/?probe=511b8b9080) | Jan 13, 2021 |
| HP            | Presario V6000 (GF814EA#... | Notebook    | [1cb2345540](https://linux-hardware.org/?probe=1cb2345540) | Jan 12, 2021 |
| HP            | Compaq 6730s                | Notebook    | [71a2587c96](https://linux-hardware.org/?probe=71a2587c96) | Jan 12, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [b30b783683](https://linux-hardware.org/?probe=b30b783683) | Jan 12, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [2e84869a9a](https://linux-hardware.org/?probe=2e84869a9a) | Jan 11, 2021 |
| Shuttle       | FG45 V10                    | Desktop     | [267e7c47d6](https://linux-hardware.org/?probe=267e7c47d6) | Jan 11, 2021 |
| ASUSTek       | P5K SE                      | Desktop     | [d0353b806e](https://linux-hardware.org/?probe=d0353b806e) | Jan 10, 2021 |
| ASUSTek       | P5K SE                      | Desktop     | [32891b789b](https://linux-hardware.org/?probe=32891b789b) | Jan 10, 2021 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [a8a6e06472](https://linux-hardware.org/?probe=a8a6e06472) | Jan 10, 2021 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [26d768f03e](https://linux-hardware.org/?probe=26d768f03e) | Jan 10, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9088e2aaad](https://linux-hardware.org/?probe=9088e2aaad) | Jan 09, 2021 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [4db19bc22f](https://linux-hardware.org/?probe=4db19bc22f) | Jan 09, 2021 |
| MSI           | G41M-P28                    | Desktop     | [fd37a435f8](https://linux-hardware.org/?probe=fd37a435f8) | Jan 09, 2021 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [6164e26717](https://linux-hardware.org/?probe=6164e26717) | Jan 09, 2021 |
| HP            | Pavilion (EH735UA#ABA)      | Notebook    | [f01f51c47c](https://linux-hardware.org/?probe=f01f51c47c) | Jan 09, 2021 |
| HP            | Pavilion (EH735UA#ABA)      | Notebook    | [d3c610e2b0](https://linux-hardware.org/?probe=d3c610e2b0) | Jan 08, 2021 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [12a8399ea8](https://linux-hardware.org/?probe=12a8399ea8) | Jan 07, 2021 |
| Acer          | Aspire V5-571               | Notebook    | [1d56503d52](https://linux-hardware.org/?probe=1d56503d52) | Jan 06, 2021 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [ab603b2fe8](https://linux-hardware.org/?probe=ab603b2fe8) | Jan 06, 2021 |
| Dell          | Inspiron M5040              | Notebook    | [1cac82f558](https://linux-hardware.org/?probe=1cac82f558) | Jan 06, 2021 |
| HP            | 1497                        | Desktop     | [89c87e060b](https://linux-hardware.org/?probe=89c87e060b) | Jan 05, 2021 |
| Acer          | Aspire 5100                 | Notebook    | [a009c7e619](https://linux-hardware.org/?probe=a009c7e619) | Jan 05, 2021 |
| Gigabyte      | B75M-D3V                    | Desktop     | [29a9e9dd7a](https://linux-hardware.org/?probe=29a9e9dd7a) | Jan 04, 2021 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [183c76aab8](https://linux-hardware.org/?probe=183c76aab8) | Jan 04, 2021 |
| ASUSTek       | G74Sx                       | Notebook    | [17e1f90630](https://linux-hardware.org/?probe=17e1f90630) | Jan 04, 2021 |
| ASRock        | Z97 Extreme4                | Desktop     | [f7d6c8e379](https://linux-hardware.org/?probe=f7d6c8e379) | Jan 03, 2021 |
| HP            | Compaq 6730s                | Notebook    | [00acad5ef5](https://linux-hardware.org/?probe=00acad5ef5) | Jan 03, 2021 |
| HP            | 250 G5 Notebook PC          | Notebook    | [a79116f681](https://linux-hardware.org/?probe=a79116f681) | Jan 03, 2021 |
| ASRock        | Z97 Extreme4                | Desktop     | [6633fa2565](https://linux-hardware.org/?probe=6633fa2565) | Jan 02, 2021 |
| ASUSTek       | DIRETTO                     | Desktop     | [ab742e4cf2](https://linux-hardware.org/?probe=ab742e4cf2) | Jan 02, 2021 |
| Dell          | XPS 13 9300                 | Notebook    | [0d6592676a](https://linux-hardware.org/?probe=0d6592676a) | Jan 02, 2021 |
| MSI           | G41M-P28                    | Desktop     | [44ae201a42](https://linux-hardware.org/?probe=44ae201a42) | Jan 02, 2021 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [343249d2da](https://linux-hardware.org/?probe=343249d2da) | Jan 02, 2021 |
| Intel         | DP965LT AAD41694-209        | Desktop     | [c577103201](https://linux-hardware.org/?probe=c577103201) | Jan 02, 2021 |
| HP            | 250 G5 Notebook PC          | Notebook    | [393c8ee706](https://linux-hardware.org/?probe=393c8ee706) | Jan 01, 2021 |
| HP            | 2171                        | Desktop     | [3367d296c3](https://linux-hardware.org/?probe=3367d296c3) | Jan 01, 2021 |
| HP            | 2171                        | Desktop     | [e8e0d2bd1f](https://linux-hardware.org/?probe=e8e0d2bd1f) | Jan 01, 2021 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [58432eb50f](https://linux-hardware.org/?probe=58432eb50f) | Jan 01, 2021 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [a3b15d44e6](https://linux-hardware.org/?probe=a3b15d44e6) | Jan 01, 2021 |
| Dell          | Inspiron 3541               | Notebook    | [e194f83f11](https://linux-hardware.org/?probe=e194f83f11) | Jan 01, 2021 |
| Dell          | Inspiron 3541               | Notebook    | [6d747c6598](https://linux-hardware.org/?probe=6d747c6598) | Jan 01, 2021 |
| Panasonic     | CF-31JEGAX1M                | Notebook    | [c0745f5a94](https://linux-hardware.org/?probe=c0745f5a94) | Dec 31, 2020 |
| HP            | ProBook 6560b               | Notebook    | [d6d7748e86](https://linux-hardware.org/?probe=d6d7748e86) | Dec 30, 2020 |
| Dell          | Inspiron 7737               | Notebook    | [494c51dbea](https://linux-hardware.org/?probe=494c51dbea) | Dec 30, 2020 |
| Gateway       | G33M05G1 MP                 | Desktop     | [460acf5c52](https://linux-hardware.org/?probe=460acf5c52) | Dec 30, 2020 |
| HP            | Compaq Presario CQ61        | Notebook    | [82c51cc214](https://linux-hardware.org/?probe=82c51cc214) | Dec 29, 2020 |
| HP            | Compaq Presario CQ61        | Notebook    | [a28099fd90](https://linux-hardware.org/?probe=a28099fd90) | Dec 29, 2020 |
| BGH           | C46G                        | Notebook    | [e61ae53564](https://linux-hardware.org/?probe=e61ae53564) | Dec 29, 2020 |
| Gigabyte      | H61M-S2P-R3                 | Desktop     | [1bb1099d2e](https://linux-hardware.org/?probe=1bb1099d2e) | Dec 28, 2020 |
| HP            | Pavilion g7                 | Notebook    | [df2771c104](https://linux-hardware.org/?probe=df2771c104) | Dec 28, 2020 |
| ASUSTek       | P8P67-M PRO                 | Desktop     | [33b473fd04](https://linux-hardware.org/?probe=33b473fd04) | Dec 28, 2020 |
| ASRock        | 960GC-GS FX                 | Desktop     | [324a0faa28](https://linux-hardware.org/?probe=324a0faa28) | Dec 28, 2020 |
| Dell          | Inspiron 6000               | Notebook    | [7158c9692c](https://linux-hardware.org/?probe=7158c9692c) | Dec 27, 2020 |
| Insyde        | CherryTrail                 | Notebook    | [3d9eb0babd](https://linux-hardware.org/?probe=3d9eb0babd) | Dec 26, 2020 |
| BGH           | C46G                        | Notebook    | [515be17b75](https://linux-hardware.org/?probe=515be17b75) | Dec 26, 2020 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [a5c3438330](https://linux-hardware.org/?probe=a5c3438330) | Dec 26, 2020 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [e339224671](https://linux-hardware.org/?probe=e339224671) | Dec 26, 2020 |
| HP            | Mini 110-3100               | Notebook    | [f716ec84db](https://linux-hardware.org/?probe=f716ec84db) | Dec 26, 2020 |
| Dell          | Inspiron 5490               | Notebook    | [25dadb6466](https://linux-hardware.org/?probe=25dadb6466) | Dec 26, 2020 |
| Dell          | Inspiron 5490               | Notebook    | [72bfd374e3](https://linux-hardware.org/?probe=72bfd374e3) | Dec 26, 2020 |
| Gigabyte      | H61M-S2P-R3                 | Desktop     | [2fb0c896b0](https://linux-hardware.org/?probe=2fb0c896b0) | Dec 25, 2020 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | Desktop     | [3cb679217f](https://linux-hardware.org/?probe=3cb679217f) | Dec 25, 2020 |
| HP            | 255 G5                      | Notebook    | [0dc71b4d28](https://linux-hardware.org/?probe=0dc71b4d28) | Dec 24, 2020 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [3323693d65](https://linux-hardware.org/?probe=3323693d65) | Dec 24, 2020 |
| Acer          | Aspire 5715Z                | Notebook    | [8e6e0fd1c6](https://linux-hardware.org/?probe=8e6e0fd1c6) | Dec 24, 2020 |
| Ematic        | EWT127                      | Notebook    | [c48f491ddd](https://linux-hardware.org/?probe=c48f491ddd) | Dec 24, 2020 |
| MSI           | H81M-P33                    | Desktop     | [73342ba685](https://linux-hardware.org/?probe=73342ba685) | Dec 23, 2020 |
| MSI           | H81M-P33                    | Desktop     | [ce959f9cb1](https://linux-hardware.org/?probe=ce959f9cb1) | Dec 23, 2020 |
| MSI           | B85-G43 GAMING              | Desktop     | [d9523e89f8](https://linux-hardware.org/?probe=d9523e89f8) | Dec 23, 2020 |
| MiTAC         | E220 6A7                    | Desktop     | [e051bc126d](https://linux-hardware.org/?probe=e051bc126d) | Dec 23, 2020 |
| HP            | Pavilion Laptop 14-ce3xx... | Notebook    | [d3a90166ed](https://linux-hardware.org/?probe=d3a90166ed) | Dec 23, 2020 |
| ZOTAC         | Unknown                     | Desktop     | [a64af30c01](https://linux-hardware.org/?probe=a64af30c01) | Dec 23, 2020 |
| Acer          | Aspire 5738                 | Notebook    | [27df1aad94](https://linux-hardware.org/?probe=27df1aad94) | Dec 22, 2020 |
| Lenovo        | G700 20251                  | Notebook    | [2bf9eaa028](https://linux-hardware.org/?probe=2bf9eaa028) | Dec 22, 2020 |
| HP            | Stream Notebook PC 14       | Notebook    | [515632d3df](https://linux-hardware.org/?probe=515632d3df) | Dec 22, 2020 |
| Dell          | Inspiron M5040              | Notebook    | [aa3db87a20](https://linux-hardware.org/?probe=aa3db87a20) | Dec 22, 2020 |
| MSI           | Boston                      | Desktop     | [5901ad0392](https://linux-hardware.org/?probe=5901ad0392) | Dec 21, 2020 |
| Dell          | Latitude E6540              | Notebook    | [a210e1c5b0](https://linux-hardware.org/?probe=a210e1c5b0) | Dec 21, 2020 |
| ASRock        | H81M-GL                     | Desktop     | [218126d732](https://linux-hardware.org/?probe=218126d732) | Dec 21, 2020 |
| Lenovo        | G700 20251                  | Notebook    | [33926859e5](https://linux-hardware.org/?probe=33926859e5) | Dec 20, 2020 |
| Dell          | Inspiron 6000               | Notebook    | [2cb0530e89](https://linux-hardware.org/?probe=2cb0530e89) | Dec 20, 2020 |
| Acer          | Aspire E1-570G              | Notebook    | [54c4be3905](https://linux-hardware.org/?probe=54c4be3905) | Dec 19, 2020 |
| ASRock        | G41C-GS                     | Desktop     | [822e9847fc](https://linux-hardware.org/?probe=822e9847fc) | Dec 19, 2020 |
| Phoenix/Si... | M720SR                      | Notebook    | [019e901528](https://linux-hardware.org/?probe=019e901528) | Dec 19, 2020 |
| ASUSTek       | P4P800-E                    | Desktop     | [68d70f6aa0](https://linux-hardware.org/?probe=68d70f6aa0) | Dec 19, 2020 |
| MSI           | B350M BAZOOKA               | Desktop     | [10b55bcb64](https://linux-hardware.org/?probe=10b55bcb64) | Dec 19, 2020 |
| Lenovo        | ThinkPad T460 20FMS7DA00    | Notebook    | [7148c9a870](https://linux-hardware.org/?probe=7148c9a870) | Dec 19, 2020 |
| IP3 Tech      | AB1                         | Mini pc     | [293c924ae4](https://linux-hardware.org/?probe=293c924ae4) | Dec 18, 2020 |
| HP            | 550                         | Notebook    | [43d983a998](https://linux-hardware.org/?probe=43d983a998) | Dec 16, 2020 |
| Dell          | Precision 3520              | Notebook    | [688878db51](https://linux-hardware.org/?probe=688878db51) | Dec 16, 2020 |
| ELSA          | P45IA-R2 1048               | Desktop     | [1f9d0ca73d](https://linux-hardware.org/?probe=1f9d0ca73d) | Dec 15, 2020 |
| ELSA          | P45IA-R2 1048               | Desktop     | [a4f63e4d00](https://linux-hardware.org/?probe=a4f63e4d00) | Dec 15, 2020 |
| ASRock        | AB350M-HDV                  | Desktop     | [755da64b4e](https://linux-hardware.org/?probe=755da64b4e) | Dec 14, 2020 |
| Toshiba       | Satellite L40               | Notebook    | [1ec0f32bdf](https://linux-hardware.org/?probe=1ec0f32bdf) | Dec 14, 2020 |
| HP            | Stream Laptop 11-y0XX       | Notebook    | [ed04aa76f7](https://linux-hardware.org/?probe=ed04aa76f7) | Dec 13, 2020 |
| HP            | Stream Laptop 11-y0XX       | Notebook    | [a45597a09a](https://linux-hardware.org/?probe=a45597a09a) | Dec 13, 2020 |
| ASUSTek       | G74Sx                       | Notebook    | [79afc26e90](https://linux-hardware.org/?probe=79afc26e90) | Dec 13, 2020 |
| Acer          | Aspire ES1-111              | Notebook    | [89f4d8b69a](https://linux-hardware.org/?probe=89f4d8b69a) | Dec 13, 2020 |
| Hampoo        | I1D6_C189_2051              | Tablet      | [f02f480cc0](https://linux-hardware.org/?probe=f02f480cc0) | Dec 13, 2020 |
| Acer          | Aspire ES1-111              | Notebook    | [d0f8154669](https://linux-hardware.org/?probe=d0f8154669) | Dec 13, 2020 |
| Lenovo        | ThinkPad T440p 20AWS37D0... | Notebook    | [c35140641b](https://linux-hardware.org/?probe=c35140641b) | Dec 13, 2020 |
| NEC Comput... | PC-VY16AWZE4                | Notebook    | [c395763d53](https://linux-hardware.org/?probe=c395763d53) | Dec 12, 2020 |
| Dell          | Inspiron 3737               | Notebook    | [db241e053d](https://linux-hardware.org/?probe=db241e053d) | Dec 11, 2020 |
| ASRock        | AB350 Gaming-ITX/ac         | Desktop     | [d5365561c6](https://linux-hardware.org/?probe=d5365561c6) | Dec 11, 2020 |
| HP            | ZBook 17 G5                 | Notebook    | [ca21d7e31d](https://linux-hardware.org/?probe=ca21d7e31d) | Dec 11, 2020 |
| ASUSTek       | P5QD TURBO                  | Desktop     | [5fa9477ba3](https://linux-hardware.org/?probe=5fa9477ba3) | Dec 11, 2020 |
| ASUSTek       | P5QD TURBO                  | Desktop     | [9f8c1a298a](https://linux-hardware.org/?probe=9f8c1a298a) | Dec 11, 2020 |
| NEC Comput... | PC-VY16AWZE4                | Notebook    | [eb1884e7bd](https://linux-hardware.org/?probe=eb1884e7bd) | Dec 10, 2020 |
| ASRock        | G41C-GS                     | Desktop     | [84feb3d2f6](https://linux-hardware.org/?probe=84feb3d2f6) | Dec 10, 2020 |
| ASRock        | G41C-GS                     | Desktop     | [92ad61acb2](https://linux-hardware.org/?probe=92ad61acb2) | Dec 10, 2020 |
| Insyde        | CAVION BASE 8 MS            | Notebook    | [b2a146e87c](https://linux-hardware.org/?probe=b2a146e87c) | Dec 09, 2020 |
| Insyde        | CAVION BASE 8 MS            | Notebook    | [9a210b4ebc](https://linux-hardware.org/?probe=9a210b4ebc) | Dec 09, 2020 |
| HP            | Laptop 15-bw0xx             | Notebook    | [577608cf6f](https://linux-hardware.org/?probe=577608cf6f) | Dec 08, 2020 |
| HP            | Laptop 15-bw0xx             | Notebook    | [f20b348140](https://linux-hardware.org/?probe=f20b348140) | Dec 08, 2020 |
| HP            | ProBook 450 G3              | Notebook    | [68d5e14ae0](https://linux-hardware.org/?probe=68d5e14ae0) | Dec 08, 2020 |
| Gigabyte      | H110-D3A-CF                 | Desktop     | [487903a901](https://linux-hardware.org/?probe=487903a901) | Dec 08, 2020 |
| Gigabyte      | H87M-HD3                    | Desktop     | [216f1a6892](https://linux-hardware.org/?probe=216f1a6892) | Dec 08, 2020 |
| HP            | Mini 110-1000               | Notebook    | [b0b1659e5a](https://linux-hardware.org/?probe=b0b1659e5a) | Dec 07, 2020 |
| Toshiba       | NB500                       | Notebook    | [fa6b10012f](https://linux-hardware.org/?probe=fa6b10012f) | Dec 06, 2020 |
| HP            | Pavilion dv9700             | Notebook    | [c2e755bbd2](https://linux-hardware.org/?probe=c2e755bbd2) | Dec 06, 2020 |
| Gigabyte      | H110-D3A-CF                 | Desktop     | [8d99fe0bc2](https://linux-hardware.org/?probe=8d99fe0bc2) | Dec 06, 2020 |
| HP            | ProBook 450 G3              | Notebook    | [a2e08c9405](https://linux-hardware.org/?probe=a2e08c9405) | Dec 06, 2020 |
| Dell          | 0KP561                      | Desktop     | [cbbc323d4c](https://linux-hardware.org/?probe=cbbc323d4c) | Dec 06, 2020 |
| Dell          | 0KP561                      | Desktop     | [070bfb2894](https://linux-hardware.org/?probe=070bfb2894) | Dec 06, 2020 |
| Supermicro    | X10SLL-F                    | Server      | [c889e2066f](https://linux-hardware.org/?probe=c889e2066f) | Dec 06, 2020 |
| Lenovo        | 30BE SDK0J40697 WIN 3305... | Desktop     | [427497efa0](https://linux-hardware.org/?probe=427497efa0) | Dec 05, 2020 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [ba02c398cd](https://linux-hardware.org/?probe=ba02c398cd) | Dec 04, 2020 |
| Acer          | WMCP78M                     | Desktop     | [880ac071b8](https://linux-hardware.org/?probe=880ac071b8) | Dec 04, 2020 |
| Acer          | WMCP78M                     | Desktop     | [b616b220de](https://linux-hardware.org/?probe=b616b220de) | Dec 04, 2020 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [31f7a22aab](https://linux-hardware.org/?probe=31f7a22aab) | Dec 04, 2020 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [411cb199ce](https://linux-hardware.org/?probe=411cb199ce) | Dec 04, 2020 |
| IP3 Tech      | AB1                         | Mini pc     | [b84e33f4dc](https://linux-hardware.org/?probe=b84e33f4dc) | Dec 04, 2020 |
| Lenovo        | ThinkCentre M57p 9088A55    | Desktop     | [4b6e3890ec](https://linux-hardware.org/?probe=4b6e3890ec) | Dec 04, 2020 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | Desktop     | [092528a895](https://linux-hardware.org/?probe=092528a895) | Dec 03, 2020 |
| Acer          | V5-131                      | Notebook    | [bfdf441399](https://linux-hardware.org/?probe=bfdf441399) | Dec 03, 2020 |
| HP            | EliteBook 2560p             | Notebook    | [704777ce16](https://linux-hardware.org/?probe=704777ce16) | Dec 03, 2020 |
| ASRock        | FM2A75 Pro4+                | Desktop     | [d12dc95e76](https://linux-hardware.org/?probe=d12dc95e76) | Dec 03, 2020 |
| Gigabyte      | H87M-HD3                    | Desktop     | [72fe4852f5](https://linux-hardware.org/?probe=72fe4852f5) | Dec 03, 2020 |
| HP            | 2820h                       | Desktop     | [660de2a3e5](https://linux-hardware.org/?probe=660de2a3e5) | Dec 02, 2020 |
| Philco        | 14A4                        | Desktop     | [2c64de874c](https://linux-hardware.org/?probe=2c64de874c) | Dec 02, 2020 |
| Philco        | 14A4                        | Desktop     | [387d4bea10](https://linux-hardware.org/?probe=387d4bea10) | Dec 02, 2020 |
| Dell          | 0RY007                      | Desktop     | [8762bbb2b6](https://linux-hardware.org/?probe=8762bbb2b6) | Dec 02, 2020 |
| Fujitsu       | CELSIUS H710                | Notebook    | [03fea3325c](https://linux-hardware.org/?probe=03fea3325c) | Dec 01, 2020 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [ef728fc5d7](https://linux-hardware.org/?probe=ef728fc5d7) | Dec 01, 2020 |
| ASRock        | Z97 Extreme6                | Desktop     | [9c98fe9c79](https://linux-hardware.org/?probe=9c98fe9c79) | Dec 01, 2020 |
| Gateway       | G33M05G1 MP                 | Desktop     | [8ec0050494](https://linux-hardware.org/?probe=8ec0050494) | Dec 01, 2020 |
| Intel         | X79 V1.x                    | Desktop     | [cb01d33033](https://linux-hardware.org/?probe=cb01d33033) | Dec 01, 2020 |
| Fujitsu       | CELSIUS H710                | Notebook    | [1214e804ff](https://linux-hardware.org/?probe=1214e804ff) | Dec 01, 2020 |
| Dell          | Latitude E6410              | Notebook    | [073ae61394](https://linux-hardware.org/?probe=073ae61394) | Nov 30, 2020 |
| HP            | G7000                       | Notebook    | [9596f449f8](https://linux-hardware.org/?probe=9596f449f8) | Nov 30, 2020 |
| HP            | G7000                       | Notebook    | [ae575e12ab](https://linux-hardware.org/?probe=ae575e12ab) | Nov 30, 2020 |
| Notebook      | RIM2020                     | Notebook    | [2b494bfd6c](https://linux-hardware.org/?probe=2b494bfd6c) | Nov 28, 2020 |
| Dell          | Inspiron 15-3552            | Notebook    | [762c5e70ba](https://linux-hardware.org/?probe=762c5e70ba) | Nov 28, 2020 |
| Dell          | Inspiron 15-3552            | Notebook    | [fc13827e05](https://linux-hardware.org/?probe=fc13827e05) | Nov 28, 2020 |
| Dell          | Latitude E6410              | Notebook    | [c17a248879](https://linux-hardware.org/?probe=c17a248879) | Nov 28, 2020 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | Notebook    | [b6570c8388](https://linux-hardware.org/?probe=b6570c8388) | Nov 28, 2020 |
| HP            | 530                         | Notebook    | [8f3bc43ec5](https://linux-hardware.org/?probe=8f3bc43ec5) | Nov 27, 2020 |
| Notebook      | RIM2020                     | Notebook    | [a8a163c8b0](https://linux-hardware.org/?probe=a8a163c8b0) | Nov 27, 2020 |
| ASUSTek       | P5KPL-CM                    | Desktop     | [ca9077ede2](https://linux-hardware.org/?probe=ca9077ede2) | Nov 27, 2020 |
| Dell          | Vostro A860                 | Notebook    | [beffd605b7](https://linux-hardware.org/?probe=beffd605b7) | Nov 27, 2020 |
| HP            | 530                         | Notebook    | [4d719de8d0](https://linux-hardware.org/?probe=4d719de8d0) | Nov 26, 2020 |
| Lenovo        | IdeaPad 330-14IKB 81G2      | Notebook    | [4be164a8cb](https://linux-hardware.org/?probe=4be164a8cb) | Nov 26, 2020 |
| Unknown       | G41                         | Desktop     | [a606df50a7](https://linux-hardware.org/?probe=a606df50a7) | Nov 26, 2020 |
| MSI           | Gypsum                      | Desktop     | [22314ebafc](https://linux-hardware.org/?probe=22314ebafc) | Nov 25, 2020 |
| MSI           | Gypsum                      | Desktop     | [fdfd3108bd](https://linux-hardware.org/?probe=fdfd3108bd) | Nov 25, 2020 |
| ASUSTek       | P5KPL-CM                    | Desktop     | [9148a1a402](https://linux-hardware.org/?probe=9148a1a402) | Nov 25, 2020 |
| ASUSTek       | P5KPL-CM                    | Desktop     | [054642cdd4](https://linux-hardware.org/?probe=054642cdd4) | Nov 25, 2020 |
| HP            | 2000                        | Notebook    | [031b9cf2af](https://linux-hardware.org/?probe=031b9cf2af) | Nov 25, 2020 |
| HP            | Pavilion dv6                | Notebook    | [678f6ed857](https://linux-hardware.org/?probe=678f6ed857) | Nov 24, 2020 |
| ASRock        | X370 Professional Gaming    | Desktop     | [8094fde100](https://linux-hardware.org/?probe=8094fde100) | Nov 24, 2020 |
| ASRock        | X370 Professional Gaming    | Desktop     | [2b462b5e18](https://linux-hardware.org/?probe=2b462b5e18) | Nov 24, 2020 |
| eMachines     | eM350                       | Notebook    | [2bafdd62aa](https://linux-hardware.org/?probe=2bafdd62aa) | Nov 23, 2020 |
| eMachines     | eM350                       | Notebook    | [03b9a0de29](https://linux-hardware.org/?probe=03b9a0de29) | Nov 23, 2020 |
| HP            | Presario V6500              | Notebook    | [6950f2532b](https://linux-hardware.org/?probe=6950f2532b) | Nov 23, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [a021bfc757](https://linux-hardware.org/?probe=a021bfc757) | Nov 23, 2020 |
| Lenovo        | IdeaPad 330-14IKB 81G2      | Notebook    | [4accc1011e](https://linux-hardware.org/?probe=4accc1011e) | Nov 23, 2020 |
| HP            | 2000                        | Notebook    | [2090a455f6](https://linux-hardware.org/?probe=2090a455f6) | Nov 23, 2020 |
| HP            | 2000                        | Notebook    | [39c1685ce9](https://linux-hardware.org/?probe=39c1685ce9) | Nov 23, 2020 |
| HP            | Presario V6500              | Notebook    | [f4f30c83df](https://linux-hardware.org/?probe=f4f30c83df) | Nov 23, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [7fe15caabf](https://linux-hardware.org/?probe=7fe15caabf) | Nov 23, 2020 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [a06a1c64ac](https://linux-hardware.org/?probe=a06a1c64ac) | Nov 22, 2020 |
| eMachines     | E525 V1.03                  | Notebook    | [a5c37bf711](https://linux-hardware.org/?probe=a5c37bf711) | Nov 22, 2020 |
| Dell          | Inspiron 3737               | Notebook    | [7dced8b5ca](https://linux-hardware.org/?probe=7dced8b5ca) | Nov 22, 2020 |
| Dell          | Vostro1710                  | Notebook    | [a359187c45](https://linux-hardware.org/?probe=a359187c45) | Nov 22, 2020 |
| Dell          | Vostro1710                  | Notebook    | [748c9cec43](https://linux-hardware.org/?probe=748c9cec43) | Nov 22, 2020 |
| ASRock        | ConRoeXFire-eSATA2          | Desktop     | [4818c2eae0](https://linux-hardware.org/?probe=4818c2eae0) | Nov 22, 2020 |
| ASRock        | ConRoeXFire-eSATA2          | Desktop     | [b0cee03629](https://linux-hardware.org/?probe=b0cee03629) | Nov 22, 2020 |
| ARIMA         | W622-DCX                    | Notebook    | [07cc1e0952](https://linux-hardware.org/?probe=07cc1e0952) | Nov 22, 2020 |
| ARIMA         | W622-DCX                    | Notebook    | [7388498d54](https://linux-hardware.org/?probe=7388498d54) | Nov 22, 2020 |
| Dell          | Latitude D430               | Notebook    | [77ef794b1d](https://linux-hardware.org/?probe=77ef794b1d) | Nov 21, 2020 |
| Dell          | Latitude D430               | Notebook    | [c028c146b6](https://linux-hardware.org/?probe=c028c146b6) | Nov 21, 2020 |
| HP            | 304Ah                       | Desktop     | [94ae3f54d1](https://linux-hardware.org/?probe=94ae3f54d1) | Nov 20, 2020 |
| HP            | 304Ah                       | Desktop     | [b2aad1ea8f](https://linux-hardware.org/?probe=b2aad1ea8f) | Nov 20, 2020 |
| Dell          | Inspiron 3737               | Notebook    | [80df1af89c](https://linux-hardware.org/?probe=80df1af89c) | Nov 20, 2020 |
| Dell          | Latitude E6410              | Notebook    | [4879940968](https://linux-hardware.org/?probe=4879940968) | Nov 19, 2020 |
| HP            | Pavilion x2 Detachable      | Notebook    | [742f34e12f](https://linux-hardware.org/?probe=742f34e12f) | Nov 19, 2020 |
| Acer          | Aspire 5253                 | Notebook    | [5700a5a6f1](https://linux-hardware.org/?probe=5700a5a6f1) | Nov 19, 2020 |
| Dell          | Latitude E5420              | Notebook    | [816b9060e4](https://linux-hardware.org/?probe=816b9060e4) | Nov 19, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [88e0ee53b6](https://linux-hardware.org/?probe=88e0ee53b6) | Nov 18, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [6e9cf39149](https://linux-hardware.org/?probe=6e9cf39149) | Nov 18, 2020 |
| HP            | Compaq Mini 110c-1100       | Notebook    | [36bc2c3cdf](https://linux-hardware.org/?probe=36bc2c3cdf) | Nov 18, 2020 |
| Acer          | Aspire one V1.03            | Notebook    | [455b9d5ac3](https://linux-hardware.org/?probe=455b9d5ac3) | Nov 17, 2020 |
| Acer          | Aspire E1-570G              | Notebook    | [3ac799a86e](https://linux-hardware.org/?probe=3ac799a86e) | Nov 17, 2020 |
| HP            | Pavilion x2 Detachable      | Notebook    | [14c5b0631b](https://linux-hardware.org/?probe=14c5b0631b) | Nov 17, 2020 |
| Toshiba       | Satellite Pro L550          | Notebook    | [0bd37ae304](https://linux-hardware.org/?probe=0bd37ae304) | Nov 16, 2020 |
| HP            | Pavilion dv6                | Notebook    | [b9e6c75b90](https://linux-hardware.org/?probe=b9e6c75b90) | Nov 15, 2020 |
| Dell          | Latitude E5440              | Notebook    | [b010db49f4](https://linux-hardware.org/?probe=b010db49f4) | Nov 15, 2020 |
| Acer          | Aspire 5630                 | Notebook    | [7479658951](https://linux-hardware.org/?probe=7479658951) | Nov 15, 2020 |
| Dell          | Latitude E6410              | Notebook    | [415cdc7c74](https://linux-hardware.org/?probe=415cdc7c74) | Nov 15, 2020 |
| HP            | EliteBook 840 G3            | Notebook    | [ec506b9770](https://linux-hardware.org/?probe=ec506b9770) | Nov 14, 2020 |
| Lenovo        | G550 20023                  | Notebook    | [9d67fb8d8b](https://linux-hardware.org/?probe=9d67fb8d8b) | Nov 13, 2020 |
| Acer          | EM61SM/EM61PM               | Desktop     | [54b2a67e58](https://linux-hardware.org/?probe=54b2a67e58) | Nov 13, 2020 |
| Fujitsu Si... | LIFEBOOK E8410              | Notebook    | [d79b3878a5](https://linux-hardware.org/?probe=d79b3878a5) | Nov 13, 2020 |
| Dell          | Latitude E6410              | Notebook    | [11be79ed72](https://linux-hardware.org/?probe=11be79ed72) | Nov 13, 2020 |
| Dell          | Inspiron 1545               | Notebook    | [3a0512d317](https://linux-hardware.org/?probe=3a0512d317) | Nov 13, 2020 |
| Dell          | Inspiron 1545               | Notebook    | [0c78c7bd9e](https://linux-hardware.org/?probe=0c78c7bd9e) | Nov 13, 2020 |
| HP            | 09F8h                       | Desktop     | [41f17bf7fc](https://linux-hardware.org/?probe=41f17bf7fc) | Nov 12, 2020 |
| HP            | 09F8h                       | Desktop     | [879925f102](https://linux-hardware.org/?probe=879925f102) | Nov 12, 2020 |
| Lenovo        | ThinkPad T460 20FMS7DA00    | Notebook    | [0470427c68](https://linux-hardware.org/?probe=0470427c68) | Nov 12, 2020 |
| HP            | Pavilion dv5000 (EP413UA... | Notebook    | [d8592798be](https://linux-hardware.org/?probe=d8592798be) | Nov 12, 2020 |
| ASUSTek       | M50Vm                       | Notebook    | [152f954015](https://linux-hardware.org/?probe=152f954015) | Nov 11, 2020 |
| ASUSTek       | M50Vm                       | Notebook    | [46b6e6863b](https://linux-hardware.org/?probe=46b6e6863b) | Nov 11, 2020 |
| Acer          | Aspire ZC-605               | All in one  | [89f713c877](https://linux-hardware.org/?probe=89f713c877) | Nov 11, 2020 |
| HP            | Pavilion dv5                | Notebook    | [8be4ce3c5a](https://linux-hardware.org/?probe=8be4ce3c5a) | Nov 11, 2020 |
| Toshiba       | Satellite C660              | Notebook    | [a5ce6d0206](https://linux-hardware.org/?probe=a5ce6d0206) | Nov 11, 2020 |
| Notebook      | RIM2520                     | Notebook    | [771a897694](https://linux-hardware.org/?probe=771a897694) | Nov 11, 2020 |
| Lenovo        | ThinkPad T460 20FMS7DA00    | Notebook    | [2c5e88fe3a](https://linux-hardware.org/?probe=2c5e88fe3a) | Nov 10, 2020 |
| ASUSTek       | X550CC                      | Notebook    | [cb23a45745](https://linux-hardware.org/?probe=cb23a45745) | Nov 10, 2020 |
| ASUSTek       | X550CC                      | Notebook    | [ccdf1d9de6](https://linux-hardware.org/?probe=ccdf1d9de6) | Nov 10, 2020 |
| ASUSTek       | Acacia                      | Desktop     | [00da4f7c88](https://linux-hardware.org/?probe=00da4f7c88) | Nov 10, 2020 |
| HP            | EliteBook 820 G2            | Notebook    | [d57310a957](https://linux-hardware.org/?probe=d57310a957) | Nov 10, 2020 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [4c0fec3ac5](https://linux-hardware.org/?probe=4c0fec3ac5) | Nov 09, 2020 |
| Lenovo        | S20-30 Touch 20434          | Notebook    | [bbac27d1f0](https://linux-hardware.org/?probe=bbac27d1f0) | Nov 08, 2020 |
| Lenovo        | ThinkPad T530 23595JU       | Notebook    | [2cce5c789a](https://linux-hardware.org/?probe=2cce5c789a) | Nov 08, 2020 |
| HP            | ENVY 15                     | Notebook    | [1fc6315caf](https://linux-hardware.org/?probe=1fc6315caf) | Nov 08, 2020 |
| HP            | ENVY 15                     | Notebook    | [996ca9b894](https://linux-hardware.org/?probe=996ca9b894) | Nov 08, 2020 |
| Dell          | Latitude D520               | Notebook    | [48ca9c477c](https://linux-hardware.org/?probe=48ca9c477c) | Nov 08, 2020 |
| Lenovo        | S20-30 Touch 20434          | Notebook    | [344bc8046a](https://linux-hardware.org/?probe=344bc8046a) | Nov 08, 2020 |
| HP            | Pavilion g6                 | Notebook    | [a1e12ac11a](https://linux-hardware.org/?probe=a1e12ac11a) | Nov 07, 2020 |
| HP            | 15                          | Notebook    | [a322932224](https://linux-hardware.org/?probe=a322932224) | Nov 07, 2020 |
| HP            | Pavilion g6                 | Notebook    | [c9fef7b025](https://linux-hardware.org/?probe=c9fef7b025) | Nov 07, 2020 |
| Toshiba       | Satellite C660              | Notebook    | [d5f99c156c](https://linux-hardware.org/?probe=d5f99c156c) | Nov 07, 2020 |
| Toshiba       | Satellite C660              | Notebook    | [45404bd97a](https://linux-hardware.org/?probe=45404bd97a) | Nov 07, 2020 |
| Medion        | MS-7857                     | Desktop     | [762cc97e3b](https://linux-hardware.org/?probe=762cc97e3b) | Nov 06, 2020 |
| ASUSTek       | 1001PXD                     | Notebook    | [d50b2e1307](https://linux-hardware.org/?probe=d50b2e1307) | Nov 05, 2020 |
| Dell          | 0HK980 A01                  | Desktop     | [f821adfa17](https://linux-hardware.org/?probe=f821adfa17) | Nov 04, 2020 |
| Dell          | Inspiron 3421               | Notebook    | [e08c38affc](https://linux-hardware.org/?probe=e08c38affc) | Nov 04, 2020 |
| Dell          | System Inspiron N7110       | Notebook    | [df14fcf89e](https://linux-hardware.org/?probe=df14fcf89e) | Nov 04, 2020 |
| HP            | Compaq Presario CQ60        | Notebook    | [dd9a86b9e4](https://linux-hardware.org/?probe=dd9a86b9e4) | Nov 04, 2020 |
| HP            | Compaq Presario CQ60        | Notebook    | [04db08c84c](https://linux-hardware.org/?probe=04db08c84c) | Nov 04, 2020 |
| Dell          | 0HK980 A01                  | Desktop     | [e369f5563d](https://linux-hardware.org/?probe=e369f5563d) | Nov 03, 2020 |
| Gigabyte      | AM1M-S2H                    | Desktop     | [b087bebc1e](https://linux-hardware.org/?probe=b087bebc1e) | Nov 03, 2020 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [ec59038f98](https://linux-hardware.org/?probe=ec59038f98) | Nov 02, 2020 |
| Acer          | Aspire 5742G                | Notebook    | [9bc7704a4f](https://linux-hardware.org/?probe=9bc7704a4f) | Nov 02, 2020 |
| Packard Be... | EasyNote TJ65               | Notebook    | [f4459e22c9](https://linux-hardware.org/?probe=f4459e22c9) | Nov 02, 2020 |
| Acer          | Aspire V5-531               | Notebook    | [8eb2cc2336](https://linux-hardware.org/?probe=8eb2cc2336) | Nov 01, 2020 |
| Acer          | Aspire 5742G                | Notebook    | [214289d932](https://linux-hardware.org/?probe=214289d932) | Oct 29, 2020 |
| Dell          | 07N90W A01                  | Desktop     | [127c1a4946](https://linux-hardware.org/?probe=127c1a4946) | Oct 29, 2020 |
| HP            | 255 G5                      | Notebook    | [e0fe2872e1](https://linux-hardware.org/?probe=e0fe2872e1) | Oct 29, 2020 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [5e797005c4](https://linux-hardware.org/?probe=5e797005c4) | Oct 27, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [3e49c517bb](https://linux-hardware.org/?probe=3e49c517bb) | Oct 25, 2020 |
| Gigabyte      | B550 AORUS MASTER           | Desktop     | [871b949fa7](https://linux-hardware.org/?probe=871b949fa7) | Oct 25, 2020 |
| Acer          | Extensa 5635Z               | Notebook    | [c0b6900751](https://linux-hardware.org/?probe=c0b6900751) | Oct 24, 2020 |
| ASUSTek       | TUF B360M-PLUS GAMING/BR    | Desktop     | [e094c9d100](https://linux-hardware.org/?probe=e094c9d100) | Oct 24, 2020 |
| ECS           | MCP61M-M3                   | Desktop     | [6459695e6a](https://linux-hardware.org/?probe=6459695e6a) | Oct 23, 2020 |
| Toshiba       | Satellite P100              | Notebook    | [60e53b8e68](https://linux-hardware.org/?probe=60e53b8e68) | Oct 22, 2020 |
| Intel         | X99                         | Desktop     | [53e51e0b25](https://linux-hardware.org/?probe=53e51e0b25) | Oct 22, 2020 |
| Intel         | X99                         | Desktop     | [194038048f](https://linux-hardware.org/?probe=194038048f) | Oct 22, 2020 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [5142bd6587](https://linux-hardware.org/?probe=5142bd6587) | Oct 22, 2020 |
| Apple         | Mac-F2218FA9                | All in one  | [a3bf786e45](https://linux-hardware.org/?probe=a3bf786e45) | Oct 22, 2020 |
| Dell          | 0HK980 A01                  | Desktop     | [247fdeaec2](https://linux-hardware.org/?probe=247fdeaec2) | Oct 21, 2020 |
| Toshiba       | Satellite M70               | Notebook    | [b99abfd9d6](https://linux-hardware.org/?probe=b99abfd9d6) | Oct 21, 2020 |
| Sony          | SVE15115ENB                 | Notebook    | [fb5da6e89d](https://linux-hardware.org/?probe=fb5da6e89d) | Oct 20, 2020 |
| Lenovo        | ThinkCentre M57p 9088A55    | Desktop     | [54a8faab61](https://linux-hardware.org/?probe=54a8faab61) | Oct 20, 2020 |
| Lenovo        | ThinkPad Edge E540 20C6A... | Notebook    | [9565cc6937](https://linux-hardware.org/?probe=9565cc6937) | Oct 20, 2020 |
| HP            | Notebook                    | Notebook    | [8057d8104a](https://linux-hardware.org/?probe=8057d8104a) | Oct 19, 2020 |
| SiS Techno... | 661                         | Desktop     | [841ee85bb9](https://linux-hardware.org/?probe=841ee85bb9) | Oct 19, 2020 |
| HP            | Compaq Presario CQ60        | Notebook    | [3b01f6d9e5](https://linux-hardware.org/?probe=3b01f6d9e5) | Oct 19, 2020 |
| ASUSTek       | P6X58D-E                    | Desktop     | [5f0bf94d1c](https://linux-hardware.org/?probe=5f0bf94d1c) | Oct 19, 2020 |
| Gigabyte      | GA-MA74GM-S2                | Desktop     | [10a2e03972](https://linux-hardware.org/?probe=10a2e03972) | Oct 19, 2020 |
| ASRock        | Z270 Killer SLI             | Desktop     | [42e012b0e1](https://linux-hardware.org/?probe=42e012b0e1) | Oct 19, 2020 |
| HP            | Pavilion dv6                | Notebook    | [6fd2a79436](https://linux-hardware.org/?probe=6fd2a79436) | Oct 18, 2020 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [4408c079e4](https://linux-hardware.org/?probe=4408c079e4) | Oct 17, 2020 |
| ASUSTek       | K53BR                       | Notebook    | [11d1b669d5](https://linux-hardware.org/?probe=11d1b669d5) | Oct 17, 2020 |
| Unknown       | Unknown                     | Notebook    | [4b9298725d](https://linux-hardware.org/?probe=4b9298725d) | Oct 17, 2020 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [50453a3ff1](https://linux-hardware.org/?probe=50453a3ff1) | Oct 17, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3a3de52609](https://linux-hardware.org/?probe=3a3de52609) | Oct 16, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [7e7adfbb13](https://linux-hardware.org/?probe=7e7adfbb13) | Oct 16, 2020 |
| Dell          | Vostro 3578                 | Notebook    | [aca3bf63fc](https://linux-hardware.org/?probe=aca3bf63fc) | Oct 16, 2020 |
| Lenovo        | ThinkPad T400 64752C3       | Notebook    | [1729f0708e](https://linux-hardware.org/?probe=1729f0708e) | Oct 15, 2020 |
| Apple         | Mac-F221BEC8                | Desktop     | [6068d6b4be](https://linux-hardware.org/?probe=6068d6b4be) | Oct 15, 2020 |
| ZOTAC         | Unknown                     | Desktop     | [ca4b1c0036](https://linux-hardware.org/?probe=ca4b1c0036) | Oct 14, 2020 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [1dbe6e7540](https://linux-hardware.org/?probe=1dbe6e7540) | Oct 14, 2020 |
| Lenovo        | ThinkCentre A70z 1165ACG    | Desktop     | [c2eb28c9f6](https://linux-hardware.org/?probe=c2eb28c9f6) | Oct 14, 2020 |
| Lenovo        | ThinkCentre A70z 1165ACG    | Desktop     | [a829cdeb90](https://linux-hardware.org/?probe=a829cdeb90) | Oct 14, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [b572236a74](https://linux-hardware.org/?probe=b572236a74) | Oct 14, 2020 |
| Gateway       | MS-7399                     | Desktop     | [c75b63eb1a](https://linux-hardware.org/?probe=c75b63eb1a) | Oct 13, 2020 |
| Dell          | Inspiron 15-3567            | Notebook    | [42a82239c5](https://linux-hardware.org/?probe=42a82239c5) | Oct 13, 2020 |
| HP            | Mini 5103                   | Notebook    | [d51f4ebf17](https://linux-hardware.org/?probe=d51f4ebf17) | Oct 13, 2020 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [6c015911fb](https://linux-hardware.org/?probe=6c015911fb) | Oct 12, 2020 |
| HP            | 2000                        | Notebook    | [36cb1ae33f](https://linux-hardware.org/?probe=36cb1ae33f) | Oct 12, 2020 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | Notebook    | [7f2d533ddf](https://linux-hardware.org/?probe=7f2d533ddf) | Oct 12, 2020 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [00f264d5ce](https://linux-hardware.org/?probe=00f264d5ce) | Oct 12, 2020 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [78f452a46b](https://linux-hardware.org/?probe=78f452a46b) | Oct 12, 2020 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [dd64edf5f8](https://linux-hardware.org/?probe=dd64edf5f8) | Oct 11, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [bbdac8d808](https://linux-hardware.org/?probe=bbdac8d808) | Oct 10, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [b07caee43e](https://linux-hardware.org/?probe=b07caee43e) | Oct 10, 2020 |
| HP            | Pavilion dv6                | Notebook    | [5b878286a6](https://linux-hardware.org/?probe=5b878286a6) | Oct 10, 2020 |
| Medion        | MS-7681                     | Desktop     | [9eadfdb4d0](https://linux-hardware.org/?probe=9eadfdb4d0) | Oct 09, 2020 |
| Lenovo        | Kona                        | Notebook    | [7490728355](https://linux-hardware.org/?probe=7490728355) | Oct 09, 2020 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [2b12ebd1f3](https://linux-hardware.org/?probe=2b12ebd1f3) | Oct 09, 2020 |
| HP            | Notebook                    | Notebook    | [60b847baba](https://linux-hardware.org/?probe=60b847baba) | Oct 08, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [8e441f98e8](https://linux-hardware.org/?probe=8e441f98e8) | Oct 08, 2020 |
| ASUSTek       | G60VX                       | Notebook    | [737170838e](https://linux-hardware.org/?probe=737170838e) | Oct 07, 2020 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [6a58f23a74](https://linux-hardware.org/?probe=6a58f23a74) | Oct 07, 2020 |
| Panasonic     | CF-31JQH7MDM                | Notebook    | [bd9af285fe](https://linux-hardware.org/?probe=bd9af285fe) | Oct 07, 2020 |
| Dell          | Latitude E5470              | Notebook    | [a1ae53e261](https://linux-hardware.org/?probe=a1ae53e261) | Oct 06, 2020 |
| Dell          | Vostro 1510                 | Notebook    | [b2e8cb8306](https://linux-hardware.org/?probe=b2e8cb8306) | Oct 06, 2020 |
| Toshiba       | NB100                       | Notebook    | [0136048af7](https://linux-hardware.org/?probe=0136048af7) | Oct 06, 2020 |
| ECS           | MCP61M-M3                   | Desktop     | [15897a6642](https://linux-hardware.org/?probe=15897a6642) | Oct 05, 2020 |
| ASUSTek       | P5QL-EM                     | Desktop     | [3da565f16e](https://linux-hardware.org/?probe=3da565f16e) | Oct 05, 2020 |
| ASUSTek       | 1015PX                      | Notebook    | [4c53e6b790](https://linux-hardware.org/?probe=4c53e6b790) | Oct 05, 2020 |
| Acer          | AOD260                      | Notebook    | [df3f6056c4](https://linux-hardware.org/?probe=df3f6056c4) | Oct 05, 2020 |
| HP            | Presario C700 (GY219LA#A... | Notebook    | [4154ef951b](https://linux-hardware.org/?probe=4154ef951b) | Oct 03, 2020 |
| HP            | Presario C700 (GY219LA#A... | Notebook    | [322081e0c8](https://linux-hardware.org/?probe=322081e0c8) | Oct 03, 2020 |
| Fujitsu       | LIFEBOOK T730               | Notebook    | [79e7520c34](https://linux-hardware.org/?probe=79e7520c34) | Oct 02, 2020 |
| Fujitsu       | LIFEBOOK T730               | Notebook    | [df7fc1fcdd](https://linux-hardware.org/?probe=df7fc1fcdd) | Oct 02, 2020 |
| ASUSTek       | K54C                        | Notebook    | [b82b607833](https://linux-hardware.org/?probe=b82b607833) | Oct 02, 2020 |
| Toshiba       | Satellite A100              | Notebook    | [05371b4921](https://linux-hardware.org/?probe=05371b4921) | Oct 02, 2020 |
| HUAWEI        | HN-WX9X                     | Notebook    | [2b80873c58](https://linux-hardware.org/?probe=2b80873c58) | Oct 02, 2020 |
| Dell          | 0PU052                      | Desktop     | [88ee7bda18](https://linux-hardware.org/?probe=88ee7bda18) | Oct 01, 2020 |
| Acer          | Makalu                      | Notebook    | [e68197eded](https://linux-hardware.org/?probe=e68197eded) | Sep 30, 2020 |
| Apple         | MacBook5,2                  | Notebook    | [47c45ae46f](https://linux-hardware.org/?probe=47c45ae46f) | Sep 30, 2020 |
| Acer          | AOD270                      | Notebook    | [4d7f40e97b](https://linux-hardware.org/?probe=4d7f40e97b) | Sep 30, 2020 |
| Apple         | MacBookPro8,1               | Notebook    | [7b095a0a58](https://linux-hardware.org/?probe=7b095a0a58) | Sep 30, 2020 |
| ASUSTek       | K54C                        | Notebook    | [a15a6332bf](https://linux-hardware.org/?probe=a15a6332bf) | Sep 30, 2020 |
| Lenovo        | 3000 N200 0769B6G           | Notebook    | [7e9967fb0e](https://linux-hardware.org/?probe=7e9967fb0e) | Sep 30, 2020 |
| HP            | 530                         | Notebook    | [c330f06c15](https://linux-hardware.org/?probe=c330f06c15) | Sep 30, 2020 |
| Intel         | DH55PJ AAE93812-301         | Desktop     | [f6a0fd4389](https://linux-hardware.org/?probe=f6a0fd4389) | Sep 30, 2020 |
| ASUSTek       | ROG Maximus XII FORMULA     | Desktop     | [baf6875e8d](https://linux-hardware.org/?probe=baf6875e8d) | Sep 29, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [3a13d6bd4b](https://linux-hardware.org/?probe=3a13d6bd4b) | Sep 28, 2020 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [f6ce95194c](https://linux-hardware.org/?probe=f6ce95194c) | Sep 27, 2020 |
| HP            | ZBook 17 G2                 | Notebook    | [0d0b182c79](https://linux-hardware.org/?probe=0d0b182c79) | Sep 27, 2020 |
| MSI           | MS-7312                     | Desktop     | [6fe2f03579](https://linux-hardware.org/?probe=6fe2f03579) | Sep 26, 2020 |
| MSI           | MS-7312                     | Desktop     | [af9ead3738](https://linux-hardware.org/?probe=af9ead3738) | Sep 26, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [655ea09cda](https://linux-hardware.org/?probe=655ea09cda) | Sep 26, 2020 |
| Intel         | 945GCT-M                    | Desktop     | [c0ad55286f](https://linux-hardware.org/?probe=c0ad55286f) | Sep 26, 2020 |
| Dell          | Latitude D630               | Notebook    | [fa947637f9](https://linux-hardware.org/?probe=fa947637f9) | Sep 25, 2020 |
| Samsung       | RV420/RV520/RV720/E3530/... | Notebook    | [fffe9391c2](https://linux-hardware.org/?probe=fffe9391c2) | Sep 25, 2020 |
| Lenovo        | ThinkPad X230 23252EG       | Notebook    | [31e0cd8ca1](https://linux-hardware.org/?probe=31e0cd8ca1) | Sep 24, 2020 |
| ASRock        | 775i65G                     | Desktop     | [0d0504c1a5](https://linux-hardware.org/?probe=0d0504c1a5) | Sep 24, 2020 |
| Acer          | Extensa 5620                | Notebook    | [2cd43c8065](https://linux-hardware.org/?probe=2cd43c8065) | Sep 24, 2020 |
| HP            | Laptop 15-bw0xx             | Notebook    | [9067f67190](https://linux-hardware.org/?probe=9067f67190) | Sep 24, 2020 |
| ASUSTek       | P5N-D                       | Desktop     | [44d0e240bc](https://linux-hardware.org/?probe=44d0e240bc) | Sep 23, 2020 |
| MSI           | A68HI AC                    | Desktop     | [a2599d7ffb](https://linux-hardware.org/?probe=a2599d7ffb) | Sep 23, 2020 |
| Acer          | Swift SF314-42              | Notebook    | [03a2ad0203](https://linux-hardware.org/?probe=03a2ad0203) | Sep 23, 2020 |
| Sony          | VGN-SZ4VWN_X                | Notebook    | [b5f136ce13](https://linux-hardware.org/?probe=b5f136ce13) | Sep 23, 2020 |
| Fujitsu Si... | AMILO Li3710                | Notebook    | [4e11c10492](https://linux-hardware.org/?probe=4e11c10492) | Sep 23, 2020 |
| Fujitsu Si... | AMILO Li3710                | Notebook    | [a5d32c72d2](https://linux-hardware.org/?probe=a5d32c72d2) | Sep 23, 2020 |
| Sony          | VGN-CR120E                  | Notebook    | [8569f91c17](https://linux-hardware.org/?probe=8569f91c17) | Sep 23, 2020 |
| Intel         | NUC8BEB J72693-303          | Mini pc     | [7a4d8d9062](https://linux-hardware.org/?probe=7a4d8d9062) | Sep 23, 2020 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [2b3c2ec612](https://linux-hardware.org/?probe=2b3c2ec612) | Sep 22, 2020 |
| HP            | EliteBook 840 G4            | Notebook    | [adec24022c](https://linux-hardware.org/?probe=adec24022c) | Sep 22, 2020 |
| ASUSTek       | W7J                         | Notebook    | [70078e77fa](https://linux-hardware.org/?probe=70078e77fa) | Sep 22, 2020 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [9ea0f3d77c](https://linux-hardware.org/?probe=9ea0f3d77c) | Sep 22, 2020 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [d21c655eeb](https://linux-hardware.org/?probe=d21c655eeb) | Sep 22, 2020 |
| Acer          | Swift SF314-42              | Notebook    | [a243f6284c](https://linux-hardware.org/?probe=a243f6284c) | Sep 21, 2020 |
| Dell          | Inspiron 1110               | Notebook    | [01517be2d7](https://linux-hardware.org/?probe=01517be2d7) | Sep 20, 2020 |
| ASUSTek       | G74Sx                       | Notebook    | [76f3c2d574](https://linux-hardware.org/?probe=76f3c2d574) | Sep 20, 2020 |
| AMI           | Cherry Trail CR             | Notebook    | [a1343de48d](https://linux-hardware.org/?probe=a1343de48d) | Sep 20, 2020 |
| Toshiba       | Satellite C660              | Notebook    | [ba30a12748](https://linux-hardware.org/?probe=ba30a12748) | Sep 19, 2020 |
| HP            | ENVY Notebook               | Notebook    | [fab3ee0d2e](https://linux-hardware.org/?probe=fab3ee0d2e) | Sep 19, 2020 |
| Lenovo        | IdeaPad 320S-13IKB 81AK     | Notebook    | [fe11f72b06](https://linux-hardware.org/?probe=fe11f72b06) | Sep 19, 2020 |
| HP            | ProBook 4540s               | Notebook    | [9ca21222f5](https://linux-hardware.org/?probe=9ca21222f5) | Sep 19, 2020 |
| HP            | Compaq Presario C700        | Notebook    | [4e8ba77ee3](https://linux-hardware.org/?probe=4e8ba77ee3) | Sep 18, 2020 |
| HP            | Compaq Presario C700        | Notebook    | [b9b510693c](https://linux-hardware.org/?probe=b9b510693c) | Sep 18, 2020 |
| Acer          | AO722                       | Notebook    | [d4c9b21741](https://linux-hardware.org/?probe=d4c9b21741) | Sep 18, 2020 |
| Toshiba       | NA 1402                     | Notebook    | [e1d38cee7f](https://linux-hardware.org/?probe=e1d38cee7f) | Sep 17, 2020 |
| HP            | Mini 210-1100               | Notebook    | [3b76e02a8f](https://linux-hardware.org/?probe=3b76e02a8f) | Sep 17, 2020 |
| HP            | 1825                        | Desktop     | [a87a5b9450](https://linux-hardware.org/?probe=a87a5b9450) | Sep 17, 2020 |
| Packard Be... | EasyNote ENTF71BM           | Notebook    | [b6c8ba71e9](https://linux-hardware.org/?probe=b6c8ba71e9) | Sep 17, 2020 |
| Packard Be... | EasyNote ENTF71BM           | Notebook    | [e09802de6b](https://linux-hardware.org/?probe=e09802de6b) | Sep 17, 2020 |
| ASUSTek       | P8H61-M LX2                 | Desktop     | [6b0f8a2063](https://linux-hardware.org/?probe=6b0f8a2063) | Sep 16, 2020 |
| ASUSTek       | P8H61-M LX2                 | Desktop     | [048dd53259](https://linux-hardware.org/?probe=048dd53259) | Sep 16, 2020 |
| Foxconn       | 2AAF                        | Desktop     | [b435a34320](https://linux-hardware.org/?probe=b435a34320) | Sep 15, 2020 |
| Foxconn       | ETON                        | Desktop     | [970cfd7db2](https://linux-hardware.org/?probe=970cfd7db2) | Sep 15, 2020 |
| Biostar       | N61PC-M2S                   | Desktop     | [09ab16ff61](https://linux-hardware.org/?probe=09ab16ff61) | Sep 15, 2020 |
| Dell          | Inspiron 5577               | Notebook    | [17862346f8](https://linux-hardware.org/?probe=17862346f8) | Sep 15, 2020 |
| OVERPOWERE... | OP-DTW1-BK                  | Desktop     | [e7e89745cd](https://linux-hardware.org/?probe=e7e89745cd) | Sep 14, 2020 |
| Acer          | Aspire 7520                 | Notebook    | [d8ae16fc0b](https://linux-hardware.org/?probe=d8ae16fc0b) | Sep 14, 2020 |
| Unknown       | Unknown                     | Notebook    | [2c52151f77](https://linux-hardware.org/?probe=2c52151f77) | Sep 13, 2020 |
| Acer          | AO722                       | Notebook    | [39f920ae53](https://linux-hardware.org/?probe=39f920ae53) | Sep 13, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [9720f7f8bc](https://linux-hardware.org/?probe=9720f7f8bc) | Sep 13, 2020 |
| ASUSTek       | N750JK                      | Notebook    | [e140f6e3e4](https://linux-hardware.org/?probe=e140f6e3e4) | Sep 12, 2020 |
| Unknown       | Unknown                     | Notebook    | [922d1c2533](https://linux-hardware.org/?probe=922d1c2533) | Sep 11, 2020 |
| Unknown       | Unknown                     | Notebook    | [f56d6dcffd](https://linux-hardware.org/?probe=f56d6dcffd) | Sep 11, 2020 |
| HP            | 530                         | Notebook    | [e0ea19e1dc](https://linux-hardware.org/?probe=e0ea19e1dc) | Sep 10, 2020 |
| HP            | Pavilion dv5                | Notebook    | [f5a369d166](https://linux-hardware.org/?probe=f5a369d166) | Sep 10, 2020 |
| Dell          | 0HY9JP A01                  | Desktop     | [5c1c0c9fcf](https://linux-hardware.org/?probe=5c1c0c9fcf) | Sep 10, 2020 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [223327c010](https://linux-hardware.org/?probe=223327c010) | Sep 09, 2020 |
| HP            | Pavilion dv5                | Notebook    | [f9f9a9ca5f](https://linux-hardware.org/?probe=f9f9a9ca5f) | Sep 09, 2020 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [8222d70ff5](https://linux-hardware.org/?probe=8222d70ff5) | Sep 09, 2020 |
| ASRock        | A320M-HD                    | Desktop     | [1bdc29a0e3](https://linux-hardware.org/?probe=1bdc29a0e3) | Sep 09, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [07fb4fed45](https://linux-hardware.org/?probe=07fb4fed45) | Sep 08, 2020 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [8a359c201f](https://linux-hardware.org/?probe=8a359c201f) | Sep 08, 2020 |
| HP            | 530                         | Notebook    | [8d751d7d91](https://linux-hardware.org/?probe=8d751d7d91) | Sep 07, 2020 |
| Lenovo        | ThinkPad T520 4239CTO       | Notebook    | [fa8846ee61](https://linux-hardware.org/?probe=fa8846ee61) | Sep 07, 2020 |
| ASUSTek       | A55BM-E                     | Desktop     | [01463318ac](https://linux-hardware.org/?probe=01463318ac) | Sep 07, 2020 |
| HP            | 3029h                       | Desktop     | [b341561a73](https://linux-hardware.org/?probe=b341561a73) | Sep 06, 2020 |
| HP            | 3029h                       | Desktop     | [1aa4904ff1](https://linux-hardware.org/?probe=1aa4904ff1) | Sep 06, 2020 |
| ASUSTek       | M4A87TD EVO                 | Desktop     | [4b2b8ed64f](https://linux-hardware.org/?probe=4b2b8ed64f) | Sep 06, 2020 |
| Dell          | Inspiron 5577               | Notebook    | [da6490c410](https://linux-hardware.org/?probe=da6490c410) | Sep 06, 2020 |
| Toshiba       | Satellite L855D             | Notebook    | [a14d72d23c](https://linux-hardware.org/?probe=a14d72d23c) | Sep 06, 2020 |
| ASUSTek       | W7J                         | Notebook    | [c505a80ea5](https://linux-hardware.org/?probe=c505a80ea5) | Sep 06, 2020 |
| ASRock        | X570 Steel Legend           | Desktop     | [fcc32617ab](https://linux-hardware.org/?probe=fcc32617ab) | Sep 06, 2020 |
| Dell          | Vostro 3700                 | Notebook    | [c9b764a48b](https://linux-hardware.org/?probe=c9b764a48b) | Sep 05, 2020 |
| Pegatron      | Maureen                     | Desktop     | [5f77e5da26](https://linux-hardware.org/?probe=5f77e5da26) | Sep 05, 2020 |
| Dell          | Inspiron 5537               | Notebook    | [4ddf924081](https://linux-hardware.org/?probe=4ddf924081) | Sep 05, 2020 |
| Dell          | Inspiron 5537               | Notebook    | [23a0e05047](https://linux-hardware.org/?probe=23a0e05047) | Sep 05, 2020 |
| HP            | EliteBook 840 G6            | Notebook    | [4a5bac87d8](https://linux-hardware.org/?probe=4a5bac87d8) | Sep 04, 2020 |
| Dell          | Inspiron N4010              | Notebook    | [59357480b7](https://linux-hardware.org/?probe=59357480b7) | Sep 04, 2020 |
| MSI           | 760GM-E51                   | Desktop     | [6db68cb189](https://linux-hardware.org/?probe=6db68cb189) | Sep 04, 2020 |
| Toshiba       | Satellite C650D             | Notebook    | [c661cb7e35](https://linux-hardware.org/?probe=c661cb7e35) | Sep 03, 2020 |
| HP            | Laptop 15-bw0xx             | Notebook    | [02c0bf156d](https://linux-hardware.org/?probe=02c0bf156d) | Sep 03, 2020 |
| HP            | Presario CQ57               | Notebook    | [2dcab385bd](https://linux-hardware.org/?probe=2dcab385bd) | Sep 03, 2020 |
| NEXCOM        | SKLD4-P1                    | Desktop     | [23c5f53c73](https://linux-hardware.org/?probe=23c5f53c73) | Sep 03, 2020 |
| NEXCOM        | SKLD4-P1                    | Desktop     | [e27e3df3f3](https://linux-hardware.org/?probe=e27e3df3f3) | Sep 03, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [9661146a6a](https://linux-hardware.org/?probe=9661146a6a) | Sep 02, 2020 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [8639b42e78](https://linux-hardware.org/?probe=8639b42e78) | Sep 02, 2020 |
| OVERPOWERE... | OP-DTW1-BK                  | Desktop     | [1102743961](https://linux-hardware.org/?probe=1102743961) | Sep 02, 2020 |
| ASRock        | 760GM-HDV                   | Desktop     | [445b280b1a](https://linux-hardware.org/?probe=445b280b1a) | Sep 01, 2020 |
| MSI           | 760GM-E51                   | Desktop     | [c514ab6cc6](https://linux-hardware.org/?probe=c514ab6cc6) | Sep 01, 2020 |
| Acer          | Aspire one V1.13            | Notebook    | [37b4d70de4](https://linux-hardware.org/?probe=37b4d70de4) | Sep 01, 2020 |
| Toshiba       | Satellite C55-A-16D         | Notebook    | [ffb7e1e547](https://linux-hardware.org/?probe=ffb7e1e547) | Aug 31, 2020 |
| Dell          | Inspiron 15-3567            | Notebook    | [f9903ce5d2](https://linux-hardware.org/?probe=f9903ce5d2) | Aug 31, 2020 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [88e9449008](https://linux-hardware.org/?probe=88e9449008) | Aug 30, 2020 |
| Toshiba       | Satellite Pro L550          | Notebook    | [02e28c5706](https://linux-hardware.org/?probe=02e28c5706) | Aug 30, 2020 |
| Apple         | MacBookAir3,1               | Notebook    | [a3168c57ea](https://linux-hardware.org/?probe=a3168c57ea) | Aug 30, 2020 |
| Dell          | Inspiron 1520               | Notebook    | [6d520f3f75](https://linux-hardware.org/?probe=6d520f3f75) | Aug 29, 2020 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [f72e36a4c1](https://linux-hardware.org/?probe=f72e36a4c1) | Aug 28, 2020 |
| Dell          | Inspiron N4010              | Notebook    | [f80559862a](https://linux-hardware.org/?probe=f80559862a) | Aug 27, 2020 |
| Lenovo        | IdeaPad 310-14ISK 80UG      | Notebook    | [a2b597141c](https://linux-hardware.org/?probe=a2b597141c) | Aug 27, 2020 |
| HP            | Pavilion g4                 | Notebook    | [55dec82070](https://linux-hardware.org/?probe=55dec82070) | Aug 26, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [de3f00fc50](https://linux-hardware.org/?probe=de3f00fc50) | Aug 26, 2020 |
| Lenovo        | G475 20080                  | Notebook    | [c97ad59308](https://linux-hardware.org/?probe=c97ad59308) | Aug 26, 2020 |
| Medion        | MS-7366                     | Desktop     | [ff7271711d](https://linux-hardware.org/?probe=ff7271711d) | Aug 25, 2020 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [6b7781d4f0](https://linux-hardware.org/?probe=6b7781d4f0) | Aug 25, 2020 |
| HP            | 0AA4h                       | Desktop     | [e1d187b146](https://linux-hardware.org/?probe=e1d187b146) | Aug 24, 2020 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [4a0e2f20ed](https://linux-hardware.org/?probe=4a0e2f20ed) | Aug 23, 2020 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [9b13901024](https://linux-hardware.org/?probe=9b13901024) | Aug 23, 2020 |
| Acer          | Aspire A515-52G             | Notebook    | [86a890eb18](https://linux-hardware.org/?probe=86a890eb18) | Aug 23, 2020 |
| Acer          | Aspire A515-52G             | Notebook    | [5034bf6bc3](https://linux-hardware.org/?probe=5034bf6bc3) | Aug 23, 2020 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [dcc65ae2a7](https://linux-hardware.org/?probe=dcc65ae2a7) | Aug 23, 2020 |
| Dell          | Inspiron MM061              | Notebook    | [a34d3a0236](https://linux-hardware.org/?probe=a34d3a0236) | Aug 22, 2020 |
| Unknown       | Unknown                     | Notebook    | [858431dd69](https://linux-hardware.org/?probe=858431dd69) | Aug 22, 2020 |
| HP            | EliteBook 725 G2            | Notebook    | [f9f5c68624](https://linux-hardware.org/?probe=f9f5c68624) | Aug 22, 2020 |
| Dell          | Inspiron 1545               | Notebook    | [0502d22a6e](https://linux-hardware.org/?probe=0502d22a6e) | Aug 22, 2020 |
| Lenovo        | IdeaPad 300-15ISK 80RS      | Notebook    | [955166808e](https://linux-hardware.org/?probe=955166808e) | Aug 22, 2020 |
| Lenovo        | IdeaPad 2in1 11 81CX        | Convertible | [bdd8a1858c](https://linux-hardware.org/?probe=bdd8a1858c) | Aug 21, 2020 |
| ASRock        | H61M-HVS                    | Desktop     | [b18b88b955](https://linux-hardware.org/?probe=b18b88b955) | Aug 21, 2020 |
| ASRock        | H61M-HVS                    | Desktop     | [c5563cf252](https://linux-hardware.org/?probe=c5563cf252) | Aug 21, 2020 |
| Lenovo        | 4068RZ7                     | Notebook    | [a019743ebe](https://linux-hardware.org/?probe=a019743ebe) | Aug 20, 2020 |
| Lenovo        | 4068RZ7                     | Notebook    | [8b55712014](https://linux-hardware.org/?probe=8b55712014) | Aug 20, 2020 |
| Dell          | Inspiron 1545               | Notebook    | [20a0eaa36a](https://linux-hardware.org/?probe=20a0eaa36a) | Aug 20, 2020 |
| Toshiba       | Satellite L670D             | Notebook    | [746e1de754](https://linux-hardware.org/?probe=746e1de754) | Aug 19, 2020 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [33bf8a1800](https://linux-hardware.org/?probe=33bf8a1800) | Aug 19, 2020 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [47f5ea43b8](https://linux-hardware.org/?probe=47f5ea43b8) | Aug 18, 2020 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [712e524505](https://linux-hardware.org/?probe=712e524505) | Aug 18, 2020 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | Notebook    | [188c3f31c6](https://linux-hardware.org/?probe=188c3f31c6) | Aug 18, 2020 |
| Lenovo        | Unknown                     | Desktop     | [ce25b58c15](https://linux-hardware.org/?probe=ce25b58c15) | Aug 18, 2020 |
| HP            | 530 Notebook PC(GU327AA#... | Notebook    | [55d79e4d6a](https://linux-hardware.org/?probe=55d79e4d6a) | Aug 17, 2020 |
| HP            | 530 Notebook PC(GU327AA#... | Notebook    | [19b6cecfad](https://linux-hardware.org/?probe=19b6cecfad) | Aug 17, 2020 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [5faf279c4f](https://linux-hardware.org/?probe=5faf279c4f) | Aug 17, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [2edfec0469](https://linux-hardware.org/?probe=2edfec0469) | Aug 17, 2020 |
| ASRock        | B450 Steel Legend           | Desktop     | [ff8b55d6af](https://linux-hardware.org/?probe=ff8b55d6af) | Aug 17, 2020 |
| HP            | Laptop 15-bs0xx             | Notebook    | [45004f5195](https://linux-hardware.org/?probe=45004f5195) | Aug 17, 2020 |
| Lenovo        | Unknown                     | Desktop     | [317a952c6b](https://linux-hardware.org/?probe=317a952c6b) | Aug 16, 2020 |
| Lenovo        | Unknown                     | Desktop     | [a58cceda96](https://linux-hardware.org/?probe=a58cceda96) | Aug 16, 2020 |
| Medion        | ERAZER X7853 MD60604        | Notebook    | [1216fcc86c](https://linux-hardware.org/?probe=1216fcc86c) | Aug 16, 2020 |
| Medion        | ERAZER X7853 MD60604        | Notebook    | [6be345d7bd](https://linux-hardware.org/?probe=6be345d7bd) | Aug 16, 2020 |
| OVERPOWERE... | OP-DTW1-BK                  | Desktop     | [3239ee82ee](https://linux-hardware.org/?probe=3239ee82ee) | Aug 15, 2020 |
| OVERPOWERE... | OP-DTW1-BK                  | Desktop     | [5d14b52f44](https://linux-hardware.org/?probe=5d14b52f44) | Aug 15, 2020 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [fd59235192](https://linux-hardware.org/?probe=fd59235192) | Aug 15, 2020 |
| Samsung       | 400B4B/400B5B/200B4B/200... | Notebook    | [299e17392c](https://linux-hardware.org/?probe=299e17392c) | Aug 15, 2020 |
| Acer          | Aspire one V1.13            | Notebook    | [c2802686dc](https://linux-hardware.org/?probe=c2802686dc) | Aug 15, 2020 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [bab7cedeb6](https://linux-hardware.org/?probe=bab7cedeb6) | Aug 15, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [363c54d31f](https://linux-hardware.org/?probe=363c54d31f) | Aug 14, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [862a4bab99](https://linux-hardware.org/?probe=862a4bab99) | Aug 14, 2020 |
| Dell          | G5 5505                     | Notebook    | [9d7d4c771b](https://linux-hardware.org/?probe=9d7d4c771b) | Aug 14, 2020 |
| Lenovo        | Yoga 520-14IKB 81C8         | Convertible | [8a6fdea191](https://linux-hardware.org/?probe=8a6fdea191) | Aug 13, 2020 |
| Lenovo        | Yoga 520-14IKB 81C8         | Convertible | [2db0caca58](https://linux-hardware.org/?probe=2db0caca58) | Aug 13, 2020 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [72b1361358](https://linux-hardware.org/?probe=72b1361358) | Aug 13, 2020 |
| Toshiba       | STI NA 1402                 | Notebook    | [d75672b88f](https://linux-hardware.org/?probe=d75672b88f) | Aug 13, 2020 |
| Alienware     | 15                          | Notebook    | [4b1d9f9153](https://linux-hardware.org/?probe=4b1d9f9153) | Aug 13, 2020 |
| Alienware     | 15                          | Notebook    | [dfde91faf2](https://linux-hardware.org/?probe=dfde91faf2) | Aug 13, 2020 |
| Dell          | 0HY9JP A01                  | Desktop     | [c415d30e67](https://linux-hardware.org/?probe=c415d30e67) | Aug 13, 2020 |
| Toshiba       | Satellite C650              | Notebook    | [0b2880b414](https://linux-hardware.org/?probe=0b2880b414) | Aug 12, 2020 |
| Dell          | G5 5505                     | Notebook    | [c4a555abaa](https://linux-hardware.org/?probe=c4a555abaa) | Aug 12, 2020 |
| MSI           | GT72 2PC                    | Notebook    | [464657ada9](https://linux-hardware.org/?probe=464657ada9) | Aug 11, 2020 |
| Acer          | Aspire 5532                 | Notebook    | [6d1ed17c3a](https://linux-hardware.org/?probe=6d1ed17c3a) | Aug 10, 2020 |
| HP            | 255 G3                      | Notebook    | [4d659eb265](https://linux-hardware.org/?probe=4d659eb265) | Aug 10, 2020 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [ce47a9613b](https://linux-hardware.org/?probe=ce47a9613b) | Aug 10, 2020 |
| ASUSTek       | GRYPHON Z97 ARMOR EDITIO... | Desktop     | [e0855b4bf3](https://linux-hardware.org/?probe=e0855b4bf3) | Aug 09, 2020 |
| Bluechip C... | Crestline & ICH8M Chipse... | Notebook    | [9b8c4353cc](https://linux-hardware.org/?probe=9b8c4353cc) | Aug 09, 2020 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [0af3102e30](https://linux-hardware.org/?probe=0af3102e30) | Aug 08, 2020 |
| HP            | G62                         | Notebook    | [79f5cf8c86](https://linux-hardware.org/?probe=79f5cf8c86) | Aug 08, 2020 |
| HP            | 14                          | Notebook    | [b7289075c1](https://linux-hardware.org/?probe=b7289075c1) | Aug 08, 2020 |
| Dell          | Vostro 15-3568              | Notebook    | [3b1e04b2da](https://linux-hardware.org/?probe=3b1e04b2da) | Aug 07, 2020 |
| Lenovo        | ThinkPad X230 23252EG       | Notebook    | [df9004d133](https://linux-hardware.org/?probe=df9004d133) | Aug 07, 2020 |
| Gigabyte      | H87M-HD3                    | Desktop     | [f22dd35202](https://linux-hardware.org/?probe=f22dd35202) | Aug 07, 2020 |
| HP            | ProBook 650 G1              | Notebook    | [3790f3b233](https://linux-hardware.org/?probe=3790f3b233) | Aug 07, 2020 |
| Gigabyte      | H310M H x.x                 | Desktop     | [8067b679a3](https://linux-hardware.org/?probe=8067b679a3) | Aug 06, 2020 |
| Gigabyte      | AB350M-D3H-CF               | Desktop     | [a98afd6112](https://linux-hardware.org/?probe=a98afd6112) | Aug 06, 2020 |
| Toshiba       | Satellite C55-A             | Notebook    | [8fb6762361](https://linux-hardware.org/?probe=8fb6762361) | Aug 06, 2020 |
| MSI           | GE620/GE620DX/FX620DX/FX... | Notebook    | [b9fddd15e8](https://linux-hardware.org/?probe=b9fddd15e8) | Aug 05, 2020 |
| Toshiba       | Satellite L670D             | Notebook    | [d28122373c](https://linux-hardware.org/?probe=d28122373c) | Aug 05, 2020 |
| Toshiba       | STI 005038 G31T-M7          | Desktop     | [e13c9ce6fb](https://linux-hardware.org/?probe=e13c9ce6fb) | Aug 04, 2020 |
| HP            | EliteBook 8460p             | Notebook    | [452088e655](https://linux-hardware.org/?probe=452088e655) | Aug 03, 2020 |
| Dell          | Inspiron MP061              | Notebook    | [7355e190ca](https://linux-hardware.org/?probe=7355e190ca) | Aug 03, 2020 |
| HP            | Pavilion g4                 | Notebook    | [4fc16d6e09](https://linux-hardware.org/?probe=4fc16d6e09) | Aug 02, 2020 |
| HP            | Pavilion g4                 | Notebook    | [0b9fc56cd1](https://linux-hardware.org/?probe=0b9fc56cd1) | Aug 02, 2020 |
| Unknown       | Unknown                     | Notebook    | [59c9ce7401](https://linux-hardware.org/?probe=59c9ce7401) | Aug 02, 2020 |
| Dell          | Latitude E5450              | Notebook    | [884ee42c35](https://linux-hardware.org/?probe=884ee42c35) | Aug 01, 2020 |
| ASUSTek       | GX501VIK                    | Notebook    | [de4780e6e4](https://linux-hardware.org/?probe=de4780e6e4) | Aug 01, 2020 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | Notebook    | [18b9136e87](https://linux-hardware.org/?probe=18b9136e87) | Aug 01, 2020 |
| Gigabyte      | AB350M-D3H-CF               | Desktop     | [07d1179bc9](https://linux-hardware.org/?probe=07d1179bc9) | Aug 01, 2020 |
| Dell          | 0HN7XN A01                  | Desktop     | [30e0b2e7e7](https://linux-hardware.org/?probe=30e0b2e7e7) | Jul 31, 2020 |
| Gigabyte      | AB350M-D3H-CF               | Desktop     | [0946988847](https://linux-hardware.org/?probe=0946988847) | Jul 31, 2020 |
| Hampoo        | I1D6_C189_2051              | Tablet      | [8b45f62f88](https://linux-hardware.org/?probe=8b45f62f88) | Jul 30, 2020 |
| Gigabyte      | F2A55M-S1                   | Desktop     | [355600cf2f](https://linux-hardware.org/?probe=355600cf2f) | Jul 30, 2020 |
| Dell          | Inspiron N5050              | Notebook    | [cb18c38bd3](https://linux-hardware.org/?probe=cb18c38bd3) | Jul 30, 2020 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [dc8ed0c837](https://linux-hardware.org/?probe=dc8ed0c837) | Jul 30, 2020 |
| HP            | EliteBook 2760p             | Notebook    | [ef84151f18](https://linux-hardware.org/?probe=ef84151f18) | Jul 29, 2020 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [3db826b463](https://linux-hardware.org/?probe=3db826b463) | Jul 29, 2020 |
| ASUSTek       | A68HM-K                     | Desktop     | [3d97268e3c](https://linux-hardware.org/?probe=3d97268e3c) | Jul 29, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [3fd417f684](https://linux-hardware.org/?probe=3fd417f684) | Jul 29, 2020 |
| HP            | ProBook 6470b               | Notebook    | [fe3206ee5f](https://linux-hardware.org/?probe=fe3206ee5f) | Jul 28, 2020 |
| Toshiba       | Satellite L670D             | Notebook    | [91a4aad7d7](https://linux-hardware.org/?probe=91a4aad7d7) | Jul 28, 2020 |
| Toshiba       | Satellite L670D             | Notebook    | [10658a729f](https://linux-hardware.org/?probe=10658a729f) | Jul 28, 2020 |
| HP            | 1000                        | Notebook    | [d0cdc87248](https://linux-hardware.org/?probe=d0cdc87248) | Jul 27, 2020 |
| Hampoo        | I1D6_C189_2051              | Tablet      | [d6bc6b6676](https://linux-hardware.org/?probe=d6bc6b6676) | Jul 27, 2020 |
| Lenovo        | G560 20042                  | Notebook    | [fb76f0edee](https://linux-hardware.org/?probe=fb76f0edee) | Jul 27, 2020 |
| Acer          | Aspire 5741                 | Notebook    | [6fa0f96d6b](https://linux-hardware.org/?probe=6fa0f96d6b) | Jul 27, 2020 |
| Gigabyte      | 970A-D3                     | Desktop     | [30bc79956d](https://linux-hardware.org/?probe=30bc79956d) | Jul 27, 2020 |
| Gigabyte      | 970A-D3                     | Desktop     | [60bef36b06](https://linux-hardware.org/?probe=60bef36b06) | Jul 27, 2020 |
| HP            | 1000                        | Notebook    | [36db752887](https://linux-hardware.org/?probe=36db752887) | Jul 26, 2020 |
| Sony          | VPCYB35AB                   | Notebook    | [6cc28f56ff](https://linux-hardware.org/?probe=6cc28f56ff) | Jul 26, 2020 |
| Sony          | VPCYB35AB                   | Notebook    | [4b5b2115c1](https://linux-hardware.org/?probe=4b5b2115c1) | Jul 26, 2020 |
| ASUSTek       | G750JM                      | Notebook    | [9b3a5ac253](https://linux-hardware.org/?probe=9b3a5ac253) | Jul 25, 2020 |
| Dell          | Inspiron 1545               | Notebook    | [57675258c0](https://linux-hardware.org/?probe=57675258c0) | Jul 25, 2020 |
| Compal        | HGL31I                      | Notebook    | [8f7aac30a8](https://linux-hardware.org/?probe=8f7aac30a8) | Jul 25, 2020 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [cd9aea2be2](https://linux-hardware.org/?probe=cd9aea2be2) | Jul 25, 2020 |
| Dell          | Latitude E6420              | Notebook    | [0de23594ba](https://linux-hardware.org/?probe=0de23594ba) | Jul 24, 2020 |
| Acer          | Aspire 5750                 | Notebook    | [fbb8795c20](https://linux-hardware.org/?probe=fbb8795c20) | Jul 24, 2020 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [b448f96a57](https://linux-hardware.org/?probe=b448f96a57) | Jul 24, 2020 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [8dd238e5a1](https://linux-hardware.org/?probe=8dd238e5a1) | Jul 24, 2020 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [d65a2f5a5a](https://linux-hardware.org/?probe=d65a2f5a5a) | Jul 24, 2020 |
| HP            | 14                          | Notebook    | [143464e093](https://linux-hardware.org/?probe=143464e093) | Jul 24, 2020 |
| Dell          | Vostro 3460                 | Notebook    | [ecdbc21896](https://linux-hardware.org/?probe=ecdbc21896) | Jul 24, 2020 |
| Foxconn       | ETON                        | Desktop     | [9d886493d1](https://linux-hardware.org/?probe=9d886493d1) | Jul 22, 2020 |
| Clevo         | M540SR VT6363A              | Notebook    | [b5b4e22b05](https://linux-hardware.org/?probe=b5b4e22b05) | Jul 21, 2020 |
| Lenovo        | Yoga C740-15IML 81TD        | Convertible | [8f98fbed33](https://linux-hardware.org/?probe=8f98fbed33) | Jul 21, 2020 |
| ABIT          | AW9D-MAX                    | Desktop     | [fca26e4a11](https://linux-hardware.org/?probe=fca26e4a11) | Jul 21, 2020 |
| Dell          | Vostro 15-3568              | Notebook    | [7ef51b8ffe](https://linux-hardware.org/?probe=7ef51b8ffe) | Jul 20, 2020 |
| Dell          | Vostro 15-3568              | Notebook    | [7ba1b7b850](https://linux-hardware.org/?probe=7ba1b7b850) | Jul 19, 2020 |
| Digibras      | NH4CU03                     | Notebook    | [3bad8b713e](https://linux-hardware.org/?probe=3bad8b713e) | Jul 19, 2020 |
| HP            | ElitePad 1000 G2            | Notebook    | [a8871cdcff](https://linux-hardware.org/?probe=a8871cdcff) | Jul 19, 2020 |
| HP            | Notebook                    | Notebook    | [875e3886d1](https://linux-hardware.org/?probe=875e3886d1) | Jul 18, 2020 |
| Dell          | Studio 1737                 | Notebook    | [b08787e998](https://linux-hardware.org/?probe=b08787e998) | Jul 17, 2020 |
| Acer          | Aspire 5715Z                | Notebook    | [929559cae0](https://linux-hardware.org/?probe=929559cae0) | Jul 17, 2020 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [1e49fe5909](https://linux-hardware.org/?probe=1e49fe5909) | Jul 16, 2020 |
| ASUSTek       | M2A-MX                      | Desktop     | [b35aa1c01f](https://linux-hardware.org/?probe=b35aa1c01f) | Jul 16, 2020 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [2a545cac20](https://linux-hardware.org/?probe=2a545cac20) | Jul 16, 2020 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [7e5966439c](https://linux-hardware.org/?probe=7e5966439c) | Jul 16, 2020 |
| ASUSTek       | P5G41T-M LX2/BR             | Desktop     | [e1e2ca2c0c](https://linux-hardware.org/?probe=e1e2ca2c0c) | Jul 16, 2020 |
| Google        | Chell                       | Notebook    | [fb663766c0](https://linux-hardware.org/?probe=fb663766c0) | Jul 16, 2020 |
| Google        | Chell                       | Notebook    | [af33f4bc7b](https://linux-hardware.org/?probe=af33f4bc7b) | Jul 15, 2020 |
| Intel         | D945GTP AAC97841-303        | Desktop     | [207ab6bfc7](https://linux-hardware.org/?probe=207ab6bfc7) | Jul 15, 2020 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [87895d9fa9](https://linux-hardware.org/?probe=87895d9fa9) | Jul 15, 2020 |
| Pegatron      | 2ACB                        | Desktop     | [f2326878af](https://linux-hardware.org/?probe=f2326878af) | Jul 15, 2020 |
| HP            | EliteBook 840 G2            | Notebook    | [a2a8e9d267](https://linux-hardware.org/?probe=a2a8e9d267) | Jul 13, 2020 |
| Gigabyte      | X570 UD                     | Desktop     | [dffcf158e7](https://linux-hardware.org/?probe=dffcf158e7) | Jul 12, 2020 |
| Sony          | VGN-P11Z_G                  | Notebook    | [7615c6d02b](https://linux-hardware.org/?probe=7615c6d02b) | Jul 11, 2020 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [8164d6222a](https://linux-hardware.org/?probe=8164d6222a) | Jul 11, 2020 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [478d2b6718](https://linux-hardware.org/?probe=478d2b6718) | Jul 11, 2020 |
| Lenovo        | BP PV CLASSMATE+            | Notebook    | [0e381612fb](https://linux-hardware.org/?probe=0e381612fb) | Jul 11, 2020 |
| Toshiba       | Satellite C660              | Notebook    | [b15da8cdfc](https://linux-hardware.org/?probe=b15da8cdfc) | Jul 11, 2020 |
| Gigabyte      | H87M-HD3                    | Desktop     | [b7b5bf6672](https://linux-hardware.org/?probe=b7b5bf6672) | Jul 10, 2020 |
| Lenovo        | Yoga C740-15IML 81TD        | Convertible | [4e62de9789](https://linux-hardware.org/?probe=4e62de9789) | Jul 10, 2020 |
| HP            | ElitePad 1000 G2            | Notebook    | [b2c793bfb4](https://linux-hardware.org/?probe=b2c793bfb4) | Jul 09, 2020 |
| HP            | ElitePad 1000 G2            | Notebook    | [152f8e9ebd](https://linux-hardware.org/?probe=152f8e9ebd) | Jul 09, 2020 |
| Unknown       | Unknown                     | Desktop     | [398053b030](https://linux-hardware.org/?probe=398053b030) | Jul 08, 2020 |
| ECS           | Livermore8                  | Desktop     | [434040dc80](https://linux-hardware.org/?probe=434040dc80) | Jul 08, 2020 |
| HP            | ElitePad 1000 G2            | Notebook    | [5054174795](https://linux-hardware.org/?probe=5054174795) | Jul 08, 2020 |
| MSI           | H61M-P31                    | Desktop     | [0f3d2686fb](https://linux-hardware.org/?probe=0f3d2686fb) | Jul 07, 2020 |
| ASUSTek       | GX501VIK                    | Notebook    | [0dc513d440](https://linux-hardware.org/?probe=0dc513d440) | Jul 07, 2020 |
| UMAX          | VisionBook 14Wg Pro         | Notebook    | [5d2b6ed775](https://linux-hardware.org/?probe=5d2b6ed775) | Jul 06, 2020 |
| Dell          | Latitude E6520              | Notebook    | [c11c08470c](https://linux-hardware.org/?probe=c11c08470c) | Jul 06, 2020 |
| Cube          | SurfTab twin 11.6           | Convertible | [ad9cbb4801](https://linux-hardware.org/?probe=ad9cbb4801) | Jul 06, 2020 |
| ECS           | G410                        | Notebook    | [38bad5d8cb](https://linux-hardware.org/?probe=38bad5d8cb) | Jul 05, 2020 |
| Samsung       | N150                        | Notebook    | [76e856e9e9](https://linux-hardware.org/?probe=76e856e9e9) | Jul 04, 2020 |
| Samsung       | N150                        | Notebook    | [cf90fb442b](https://linux-hardware.org/?probe=cf90fb442b) | Jul 04, 2020 |
| Lenovo        | ThinkPad X140e 20BMS00E0... | Notebook    | [ee2280ecd4](https://linux-hardware.org/?probe=ee2280ecd4) | Jul 04, 2020 |
| Dell          | 0VNP2H A00                  | Desktop     | [de21e4bff4](https://linux-hardware.org/?probe=de21e4bff4) | Jul 04, 2020 |
| Toshiba       | Satellite C40-A             | Notebook    | [672cca96fd](https://linux-hardware.org/?probe=672cca96fd) | Jul 04, 2020 |
| Acer          | Lugano M                    | Notebook    | [c3722a65f4](https://linux-hardware.org/?probe=c3722a65f4) | Jul 04, 2020 |
| WIPRO         | WIVNB7B1623-0002            | Notebook    | [4669989193](https://linux-hardware.org/?probe=4669989193) | Jul 03, 2020 |
| Gigabyte      | 965P-S3                     | Desktop     | [a1bd9cbad0](https://linux-hardware.org/?probe=a1bd9cbad0) | Jul 03, 2020 |
| Dell          | 0200DY A02                  | Desktop     | [fcc768d660](https://linux-hardware.org/?probe=fcc768d660) | Jul 03, 2020 |
| MSI           | 970A-G46                    | Desktop     | [9518d416ac](https://linux-hardware.org/?probe=9518d416ac) | Jul 03, 2020 |
| Acer          | Lugano M                    | Notebook    | [d91f2c3af1](https://linux-hardware.org/?probe=d91f2c3af1) | Jul 03, 2020 |
| Dell          | 0200DY A02                  | Desktop     | [f919408b8e](https://linux-hardware.org/?probe=f919408b8e) | Jul 03, 2020 |
| Dell          | Latitude E6440              | Notebook    | [521818b099](https://linux-hardware.org/?probe=521818b099) | Jul 02, 2020 |
| HP            | ProBook 450 G3              | Notebook    | [cf66568c1a](https://linux-hardware.org/?probe=cf66568c1a) | Jul 01, 2020 |
| ASUSTek       | B75M-A                      | Desktop     | [19d715cc29](https://linux-hardware.org/?probe=19d715cc29) | Jul 01, 2020 |
| ASUSTek       | B75M-A                      | Desktop     | [7c902136f4](https://linux-hardware.org/?probe=7c902136f4) | Jul 01, 2020 |
| HP            | 3029h                       | Desktop     | [83bd0d970c](https://linux-hardware.org/?probe=83bd0d970c) | Jun 30, 2020 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | Desktop     | [597b6bd7c1](https://linux-hardware.org/?probe=597b6bd7c1) | Jun 30, 2020 |
| HP            | Notebook                    | Notebook    | [1b077e7d7e](https://linux-hardware.org/?probe=1b077e7d7e) | Jun 30, 2020 |
| HP            | G60                         | Notebook    | [2c11d20a74](https://linux-hardware.org/?probe=2c11d20a74) | Jun 29, 2020 |
| Toshiba       | Satellite C645              | Notebook    | [962d89d16d](https://linux-hardware.org/?probe=962d89d16d) | Jun 29, 2020 |
| Toshiba       | Satellite C645              | Notebook    | [bec8895749](https://linux-hardware.org/?probe=bec8895749) | Jun 29, 2020 |
| ASUSTek       | Puffer                      | Desktop     | [5a6724a6bb](https://linux-hardware.org/?probe=5a6724a6bb) | Jun 29, 2020 |
| Gigabyte      | 965P-S3                     | Desktop     | [cc0925a796](https://linux-hardware.org/?probe=cc0925a796) | Jun 28, 2020 |
| Toshiba       | Satellite S50-B             | Notebook    | [2e8165ca6a](https://linux-hardware.org/?probe=2e8165ca6a) | Jun 28, 2020 |
| Biostar       | A68N-5000                   | Desktop     | [33f0f081e9](https://linux-hardware.org/?probe=33f0f081e9) | Jun 27, 2020 |
| MSI           | Boston                      | Desktop     | [f911162633](https://linux-hardware.org/?probe=f911162633) | Jun 27, 2020 |
| Dell          | Inspiron 1525               | Notebook    | [754b2de717](https://linux-hardware.org/?probe=754b2de717) | Jun 27, 2020 |
| ECS           | G31T-M7                     | Desktop     | [95eaae406a](https://linux-hardware.org/?probe=95eaae406a) | Jun 27, 2020 |
| Dell          | System Vostro 3450          | Notebook    | [6ecdf91891](https://linux-hardware.org/?probe=6ecdf91891) | Jun 27, 2020 |
| MSI           | Boston                      | Desktop     | [3c584bef15](https://linux-hardware.org/?probe=3c584bef15) | Jun 26, 2020 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [120fd84f28](https://linux-hardware.org/?probe=120fd84f28) | Jun 26, 2020 |
| Alienware     | M17x                        | Notebook    | [4a26920858](https://linux-hardware.org/?probe=4a26920858) | Jun 26, 2020 |
| Gigabyte      | 965P-S3                     | Desktop     | [e811eb9589](https://linux-hardware.org/?probe=e811eb9589) | Jun 26, 2020 |
| Toshiba       | Satellite L655              | Notebook    | [d03c7bb948](https://linux-hardware.org/?probe=d03c7bb948) | Jun 26, 2020 |
| Toshiba       | Satellite L655              | Notebook    | [002ace5d32](https://linux-hardware.org/?probe=002ace5d32) | Jun 26, 2020 |
| Acer          | Aspire A515-51              | Notebook    | [636d176056](https://linux-hardware.org/?probe=636d176056) | Jun 25, 2020 |
| MSI           | H61M-P31                    | Desktop     | [a0aefb9623](https://linux-hardware.org/?probe=a0aefb9623) | Jun 25, 2020 |
| Dell          | Latitude E6440              | Notebook    | [1ffde1aa78](https://linux-hardware.org/?probe=1ffde1aa78) | Jun 24, 2020 |
| Inventec      | D CLASS A02                 | Desktop     | [c4c0c498d3](https://linux-hardware.org/?probe=c4c0c498d3) | Jun 23, 2020 |
| HP            | 3646h                       | Desktop     | [1882125d6e](https://linux-hardware.org/?probe=1882125d6e) | Jun 23, 2020 |
| HP            | 1497                        | Desktop     | [2fda25d6a2](https://linux-hardware.org/?probe=2fda25d6a2) | Jun 22, 2020 |
| HP            | 1497                        | Desktop     | [a47bcc975c](https://linux-hardware.org/?probe=a47bcc975c) | Jun 22, 2020 |
| Intel         | DX79SI AAG28808-600         | Desktop     | [9c6a249675](https://linux-hardware.org/?probe=9c6a249675) | Jun 21, 2020 |
| Intel         | DX79SI AAG28808-600         | Desktop     | [a86350872e](https://linux-hardware.org/?probe=a86350872e) | Jun 21, 2020 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [67c4745d3a](https://linux-hardware.org/?probe=67c4745d3a) | Jun 21, 2020 |
| UMAX          | VisionBook 14Wg Pro         | Notebook    | [a50a75e674](https://linux-hardware.org/?probe=a50a75e674) | Jun 21, 2020 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [d59cf3e39f](https://linux-hardware.org/?probe=d59cf3e39f) | Jun 21, 2020 |
| Pegatron      | 2ACB                        | Desktop     | [37b37c6c60](https://linux-hardware.org/?probe=37b37c6c60) | Jun 21, 2020 |
| Pegatron      | 2ACB                        | Desktop     | [9c2f5182a6](https://linux-hardware.org/?probe=9c2f5182a6) | Jun 21, 2020 |
| Acer          | Aspire S3                   | Notebook    | [431c5f1360](https://linux-hardware.org/?probe=431c5f1360) | Jun 20, 2020 |
| Acer          | Aspire S3                   | Notebook    | [2ecc528f99](https://linux-hardware.org/?probe=2ecc528f99) | Jun 20, 2020 |
| ASUSTek       | TP300LA                     | Notebook    | [a24e3e59e4](https://linux-hardware.org/?probe=a24e3e59e4) | Jun 20, 2020 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [c2f7f39a83](https://linux-hardware.org/?probe=c2f7f39a83) | Jun 20, 2020 |
| ECS           | H81H3-MV                    | Desktop     | [d39e7a605d](https://linux-hardware.org/?probe=d39e7a605d) | Jun 20, 2020 |
| HP            | ProBook 6470b               | Notebook    | [37be0cfc66](https://linux-hardware.org/?probe=37be0cfc66) | Jun 19, 2020 |
| Lenovo        | G50-30 80G0                 | Notebook    | [d9f9497fd7](https://linux-hardware.org/?probe=d9f9497fd7) | Jun 19, 2020 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [d79300ba76](https://linux-hardware.org/?probe=d79300ba76) | Jun 18, 2020 |
| Foxconn       | 2AB7                        | Desktop     | [7c4bca9a4f](https://linux-hardware.org/?probe=7c4bca9a4f) | Jun 18, 2020 |
| Qbex          | K131                        | Notebook    | [4f86406fcd](https://linux-hardware.org/?probe=4f86406fcd) | Jun 18, 2020 |
| Toshiba       | Satellite C55D-B            | Notebook    | [8e66b0c5f9](https://linux-hardware.org/?probe=8e66b0c5f9) | Jun 17, 2020 |
| HP            | Pavilion dm1                | Notebook    | [cfa6ec6eee](https://linux-hardware.org/?probe=cfa6ec6eee) | Jun 17, 2020 |
| Dell          | 054KM3 A01                  | Desktop     | [59451c84ff](https://linux-hardware.org/?probe=59451c84ff) | Jun 17, 2020 |
| Foxconn       | G41MXE/G41MXE-K             | Desktop     | [c05f965fec](https://linux-hardware.org/?probe=c05f965fec) | Jun 17, 2020 |
| Dell          | 054KM3 A01                  | Desktop     | [43c2648d7f](https://linux-hardware.org/?probe=43c2648d7f) | Jun 17, 2020 |
| ASUSTek       | P8P67-M                     | Desktop     | [d07aba1f9c](https://linux-hardware.org/?probe=d07aba1f9c) | Jun 17, 2020 |
| Gigabyte      | CROSS B02                   | Desktop     | [e510d6bf4b](https://linux-hardware.org/?probe=e510d6bf4b) | Jun 16, 2020 |
| HP            | Laptop 15-bw0xx             | Notebook    | [b19bfe7909](https://linux-hardware.org/?probe=b19bfe7909) | Jun 16, 2020 |
| HP            | Compaq Mini                 | Notebook    | [bb593c0696](https://linux-hardware.org/?probe=bb593c0696) | Jun 16, 2020 |
| Foxconn       | G41MXE/G41MXE-K             | Desktop     | [835aa152dd](https://linux-hardware.org/?probe=835aa152dd) | Jun 16, 2020 |
| HP            | 0B54h D                     | Desktop     | [d77840ef5a](https://linux-hardware.org/?probe=d77840ef5a) | Jun 15, 2020 |
| Dell          | Inspiron 14-3452            | Notebook    | [c83e4c2dd8](https://linux-hardware.org/?probe=c83e4c2dd8) | Jun 15, 2020 |
| MSI           | 970A-G46                    | Desktop     | [724efa2b05](https://linux-hardware.org/?probe=724efa2b05) | Jun 15, 2020 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [e23bad65bc](https://linux-hardware.org/?probe=e23bad65bc) | Jun 14, 2020 |
| Samsung       | N130                        | Notebook    | [4e60aa279e](https://linux-hardware.org/?probe=4e60aa279e) | Jun 14, 2020 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [358e086ce3](https://linux-hardware.org/?probe=358e086ce3) | Jun 14, 2020 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [6700a5b937](https://linux-hardware.org/?probe=6700a5b937) | Jun 14, 2020 |
| Foxconn       | 2AB7                        | Desktop     | [345f9112a1](https://linux-hardware.org/?probe=345f9112a1) | Jun 14, 2020 |
| HP            | ProBook 6470b               | Notebook    | [f5cc0bfea1](https://linux-hardware.org/?probe=f5cc0bfea1) | Jun 14, 2020 |
| Toshiba       | Satellite C55-A             | Notebook    | [7c435001c2](https://linux-hardware.org/?probe=7c435001c2) | Jun 14, 2020 |
| HP            | EliteBook 6930p             | Notebook    | [521bd09de6](https://linux-hardware.org/?probe=521bd09de6) | Jun 13, 2020 |
| ASUSTek       | K75DE                       | Notebook    | [ab5984d317](https://linux-hardware.org/?probe=ab5984d317) | Jun 13, 2020 |
| ASUSTek       | K75DE                       | Notebook    | [3a77ccc6d1](https://linux-hardware.org/?probe=3a77ccc6d1) | Jun 13, 2020 |
| HP            | ProBook 450 G3              | Notebook    | [7c8e952de0](https://linux-hardware.org/?probe=7c8e952de0) | Jun 12, 2020 |
| HP            | ENVY TS m7                  | Notebook    | [3186cbcb82](https://linux-hardware.org/?probe=3186cbcb82) | Jun 12, 2020 |
| ECS           | Livermore8                  | Desktop     | [43a7445da6](https://linux-hardware.org/?probe=43a7445da6) | Jun 12, 2020 |
| Intel         | D845GRG AAA81583-300        | Desktop     | [90de626b6d](https://linux-hardware.org/?probe=90de626b6d) | Jun 11, 2020 |
| Intel         | D845GRG AAA81583-300        | Desktop     | [7775d50156](https://linux-hardware.org/?probe=7775d50156) | Jun 11, 2020 |
| MSI           | 0A90                        | Desktop     | [fa39a9a0c6](https://linux-hardware.org/?probe=fa39a9a0c6) | Jun 11, 2020 |
| MSI           | 0A90                        | Desktop     | [747826ea27](https://linux-hardware.org/?probe=747826ea27) | Jun 11, 2020 |
| ASUSTek       | UX331UA                     | Notebook    | [064e95c086](https://linux-hardware.org/?probe=064e95c086) | Jun 10, 2020 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [524e18fe98](https://linux-hardware.org/?probe=524e18fe98) | Jun 09, 2020 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [b143cee87c](https://linux-hardware.org/?probe=b143cee87c) | Jun 09, 2020 |
| Apple         | MacBookAir3,1               | Notebook    | [e31264d63b](https://linux-hardware.org/?probe=e31264d63b) | Jun 09, 2020 |
| Apple         | MacBookAir3,1               | Notebook    | [7ebb47dc43](https://linux-hardware.org/?probe=7ebb47dc43) | Jun 09, 2020 |
| Acer          | AOD270                      | Notebook    | [3a0d567ba7](https://linux-hardware.org/?probe=3a0d567ba7) | Jun 09, 2020 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [e8f424ff31](https://linux-hardware.org/?probe=e8f424ff31) | Jun 09, 2020 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [12857735fa](https://linux-hardware.org/?probe=12857735fa) | Jun 09, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [27b21d21f9](https://linux-hardware.org/?probe=27b21d21f9) | Jun 09, 2020 |
| ASUSTek       | P5Q-VM DO                   | Desktop     | [346628ed49](https://linux-hardware.org/?probe=346628ed49) | Jun 09, 2020 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [a1615f709d](https://linux-hardware.org/?probe=a1615f709d) | Jun 07, 2020 |
| Toshiba       | PORTEGE Z20t-C              | Notebook    | [4e2285206e](https://linux-hardware.org/?probe=4e2285206e) | Jun 07, 2020 |
| ASRock        | B450M Pro4                  | Desktop     | [dd2266a382](https://linux-hardware.org/?probe=dd2266a382) | Jun 07, 2020 |
| Acer          | Spin SP111-32N              | Convertible | [1b328a3040](https://linux-hardware.org/?probe=1b328a3040) | Jun 06, 2020 |
| HP            | Laptop 17-by0xxx            | Notebook    | [95415bf222](https://linux-hardware.org/?probe=95415bf222) | Jun 06, 2020 |
| HP            | Laptop 17-by0xxx            | Notebook    | [9fb0632ef6](https://linux-hardware.org/?probe=9fb0632ef6) | Jun 06, 2020 |
| Fujitsu Si... | LIFEBOOK S7220              | Notebook    | [f3c44830da](https://linux-hardware.org/?probe=f3c44830da) | Jun 06, 2020 |
| ASRock        | P4VM8                       | Desktop     | [6958ec038e](https://linux-hardware.org/?probe=6958ec038e) | Jun 06, 2020 |
| ASUSTek       | A55BM-E                     | Desktop     | [07382dc0c4](https://linux-hardware.org/?probe=07382dc0c4) | Jun 06, 2020 |
| ASRock        | P4VM8                       | Desktop     | [c018c0a70c](https://linux-hardware.org/?probe=c018c0a70c) | Jun 05, 2020 |
| Toshiba       | Satellite A100              | Notebook    | [eddce8db1a](https://linux-hardware.org/?probe=eddce8db1a) | Jun 05, 2020 |
| HP            | Pavilion dv6700             | Notebook    | [a53258f04c](https://linux-hardware.org/?probe=a53258f04c) | Jun 05, 2020 |
| Dell          | 0N4YC8 A00                  | Desktop     | [195c9f0cfd](https://linux-hardware.org/?probe=195c9f0cfd) | Jun 04, 2020 |
| ASUSTek       | X555LD                      | Notebook    | [5fcb4e6866](https://linux-hardware.org/?probe=5fcb4e6866) | Jun 03, 2020 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [5b1664a4bb](https://linux-hardware.org/?probe=5b1664a4bb) | Jun 03, 2020 |
| Dell          | Latitude XT2                | Notebook    | [5970770ec5](https://linux-hardware.org/?probe=5970770ec5) | Jun 03, 2020 |
| Dell          | Latitude XT2                | Notebook    | [bc35b5f660](https://linux-hardware.org/?probe=bc35b5f660) | Jun 03, 2020 |
| Dell          | Latitude XT2                | Notebook    | [0f863604a4](https://linux-hardware.org/?probe=0f863604a4) | Jun 03, 2020 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [76c2001b93](https://linux-hardware.org/?probe=76c2001b93) | Jun 03, 2020 |
| ASUSTek       | UX331UA                     | Notebook    | [8ca766622f](https://linux-hardware.org/?probe=8ca766622f) | Jun 02, 2020 |
| Lenovo        | 30C9 SDK0J40697 WIN 3305... | Desktop     | [b56fca6b80](https://linux-hardware.org/?probe=b56fca6b80) | Jun 02, 2020 |
| HP            | EliteBook 8770w             | Notebook    | [9bba8e0daf](https://linux-hardware.org/?probe=9bba8e0daf) | Jun 01, 2020 |
| Lenovo        | ThinkPad W520 42844LG       | Notebook    | [9bc21e2e76](https://linux-hardware.org/?probe=9bc21e2e76) | Jun 01, 2020 |
| Dell          | Vostro 5470                 | Notebook    | [c519aedd88](https://linux-hardware.org/?probe=c519aedd88) | Jun 01, 2020 |
| Acer          | Aspire A315-51              | Notebook    | [b524806f7a](https://linux-hardware.org/?probe=b524806f7a) | May 31, 2020 |
| Intel         | DG45ID AAE46743-303         | Desktop     | [a401a76cc7](https://linux-hardware.org/?probe=a401a76cc7) | May 31, 2020 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [c5d60d0373](https://linux-hardware.org/?probe=c5d60d0373) | May 31, 2020 |
| HP            | Pavilion dv6000 (RP986EA... | Notebook    | [1e4d134edf](https://linux-hardware.org/?probe=1e4d134edf) | May 30, 2020 |
| HP            | 635                         | Notebook    | [4c1e9766eb](https://linux-hardware.org/?probe=4c1e9766eb) | May 30, 2020 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [3717bb5ab4](https://linux-hardware.org/?probe=3717bb5ab4) | May 29, 2020 |
| Notebook      | P570WM                      | Notebook    | [1694f6a1b4](https://linux-hardware.org/?probe=1694f6a1b4) | May 28, 2020 |
| Insyde        | TW36                        | Notebook    | [7038a5c61c](https://linux-hardware.org/?probe=7038a5c61c) | May 28, 2020 |
| Dell          | Inspiron 5480               | Notebook    | [aeaf1790c2](https://linux-hardware.org/?probe=aeaf1790c2) | May 28, 2020 |
| MSI           | A68HM-E33 V2                | Desktop     | [ea48f46d27](https://linux-hardware.org/?probe=ea48f46d27) | May 27, 2020 |
| HP            | 635                         | Notebook    | [fec1f36696](https://linux-hardware.org/?probe=fec1f36696) | May 27, 2020 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [0508854129](https://linux-hardware.org/?probe=0508854129) | May 27, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V6555        | Notebook    | [e6a298846b](https://linux-hardware.org/?probe=e6a298846b) | May 27, 2020 |
| Intel         | SBC-FITPC2                  | Desktop     | [032a1a34df](https://linux-hardware.org/?probe=032a1a34df) | May 27, 2020 |
| Intel         | SBC-FITPC2                  | Desktop     | [aef59ca303](https://linux-hardware.org/?probe=aef59ca303) | May 26, 2020 |
| Dell          | Latitude XT2                | Notebook    | [760d50a6bc](https://linux-hardware.org/?probe=760d50a6bc) | May 26, 2020 |
| Durabook      | S15H                        | Notebook    | [2599b1778a](https://linux-hardware.org/?probe=2599b1778a) | May 26, 2020 |
| Durabook      | S15H                        | Notebook    | [3563afb99e](https://linux-hardware.org/?probe=3563afb99e) | May 26, 2020 |
| Dell          | Inspiron 14-3452            | Notebook    | [f894499ac3](https://linux-hardware.org/?probe=f894499ac3) | May 26, 2020 |
| Dell          | Inspiron 1440               | Notebook    | [51cbf53227](https://linux-hardware.org/?probe=51cbf53227) | May 26, 2020 |
| HP            | 15                          | Notebook    | [c39075bd80](https://linux-hardware.org/?probe=c39075bd80) | May 25, 2020 |
| ASUSTek       | P5VD2-MX                    | Desktop     | [524c1edf41](https://linux-hardware.org/?probe=524c1edf41) | May 25, 2020 |
| ASUSTek       | A55BM-E                     | Desktop     | [6d32273098](https://linux-hardware.org/?probe=6d32273098) | May 24, 2020 |
| ASUSTek       | A55BM-E                     | Desktop     | [2031edbb27](https://linux-hardware.org/?probe=2031edbb27) | May 24, 2020 |
| ASUSTek       | Z450LA                      | Notebook    | [e64dcdf564](https://linux-hardware.org/?probe=e64dcdf564) | May 24, 2020 |
| Gigabyte      | B75MS                       | Desktop     | [0a89e7c898](https://linux-hardware.org/?probe=0a89e7c898) | May 24, 2020 |
| Gigabyte      | B75MS                       | Desktop     | [45e89b7d24](https://linux-hardware.org/?probe=45e89b7d24) | May 24, 2020 |
| HP            | 18E7                        | Desktop     | [12e697ae24](https://linux-hardware.org/?probe=12e697ae24) | May 24, 2020 |
| Lenovo        | ThinkPad X140e 20BMS00E0... | Notebook    | [edc9f5d43a](https://linux-hardware.org/?probe=edc9f5d43a) | May 24, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [2001de6cd9](https://linux-hardware.org/?probe=2001de6cd9) | May 24, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [275aa1bafe](https://linux-hardware.org/?probe=275aa1bafe) | May 24, 2020 |
| Acer          | Aspire one                  | Notebook    | [610bb91d45](https://linux-hardware.org/?probe=610bb91d45) | May 23, 2020 |
| ASUSTek       | P552SA                      | Notebook    | [cd07bb014c](https://linux-hardware.org/?probe=cd07bb014c) | May 23, 2020 |
| Gigabyte      | GA-78LMT-S2PT               | Desktop     | [90f3ca9c43](https://linux-hardware.org/?probe=90f3ca9c43) | May 23, 2020 |
| Acer          | Aspire 5755G                | Notebook    | [58e9aedfca](https://linux-hardware.org/?probe=58e9aedfca) | May 23, 2020 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [206613fa48](https://linux-hardware.org/?probe=206613fa48) | May 22, 2020 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [6570cd4d9d](https://linux-hardware.org/?probe=6570cd4d9d) | May 22, 2020 |
| ECS           | A740GM-M                    | Desktop     | [2fc676a203](https://linux-hardware.org/?probe=2fc676a203) | May 22, 2020 |
| HP            | EliteBook x360 1030 G2      | Convertible | [bc2a228855](https://linux-hardware.org/?probe=bc2a228855) | May 22, 2020 |
| ASRock        | 960GC-GS FX                 | Desktop     | [443f5e2835](https://linux-hardware.org/?probe=443f5e2835) | May 22, 2020 |
| HP            | Pavilion (EC436AV#ABA)      | Notebook    | [16430a960e](https://linux-hardware.org/?probe=16430a960e) | May 22, 2020 |
| Acer          | AOD270                      | Notebook    | [e254f3b7e5](https://linux-hardware.org/?probe=e254f3b7e5) | May 22, 2020 |
| Sony          | VGN-AW11Z_B                 | Notebook    | [71a7a9f1f3](https://linux-hardware.org/?probe=71a7a9f1f3) | May 22, 2020 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [29131d3d86](https://linux-hardware.org/?probe=29131d3d86) | May 21, 2020 |
| HP            | ZBook 17 G5                 | Notebook    | [81b70e2c63](https://linux-hardware.org/?probe=81b70e2c63) | May 21, 2020 |
| MSI           | AMETHYST-M                  | Desktop     | [b22dad141f](https://linux-hardware.org/?probe=b22dad141f) | May 21, 2020 |
| MSI           | AMETHYST-M                  | Desktop     | [cfd86618c2](https://linux-hardware.org/?probe=cfd86618c2) | May 21, 2020 |
| ASUSTek       | 1005P                       | Notebook    | [a2b309ff12](https://linux-hardware.org/?probe=a2b309ff12) | May 21, 2020 |
| HP            | EliteBook 840 G1            | Notebook    | [a39e33b1f4](https://linux-hardware.org/?probe=a39e33b1f4) | May 20, 2020 |
| HP            | EliteBook 840 G1            | Notebook    | [4f773edbaa](https://linux-hardware.org/?probe=4f773edbaa) | May 20, 2020 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [53e1908687](https://linux-hardware.org/?probe=53e1908687) | May 20, 2020 |
| Dell          | Inspiron 1420               | Notebook    | [1269d54a19](https://linux-hardware.org/?probe=1269d54a19) | May 20, 2020 |
| ASUSTek       | K84L                        | Notebook    | [01c734a603](https://linux-hardware.org/?probe=01c734a603) | May 19, 2020 |
| Gigabyte      | GA-MA78G-DS3H               | Desktop     | [8d16a2150c](https://linux-hardware.org/?probe=8d16a2150c) | May 19, 2020 |
| Acer          | Aspire ES1-711              | Notebook    | [f0d922b2a0](https://linux-hardware.org/?probe=f0d922b2a0) | May 19, 2020 |
| ASUSTek       | F2A85-M PRO                 | Desktop     | [680a98718a](https://linux-hardware.org/?probe=680a98718a) | May 19, 2020 |
| ASUSTek       | P5QL/EPU                    | Desktop     | [92b1b60d4f](https://linux-hardware.org/?probe=92b1b60d4f) | May 19, 2020 |
| ASUSTek       | K50AB                       | Notebook    | [96ccf326a8](https://linux-hardware.org/?probe=96ccf326a8) | May 19, 2020 |
| Soyo          | P4IPE                       | Desktop     | [f254b75397](https://linux-hardware.org/?probe=f254b75397) | May 19, 2020 |
| Soyo          | P4IPE                       | Desktop     | [c3716dc8a2](https://linux-hardware.org/?probe=c3716dc8a2) | May 18, 2020 |
| Advantec      | CX23200W                    | Notebook    | [3c46531687](https://linux-hardware.org/?probe=3c46531687) | May 18, 2020 |
| HP            | EliteBook 6930p             | Notebook    | [0659c564f2](https://linux-hardware.org/?probe=0659c564f2) | May 17, 2020 |
| Dell          | Latitude E5570              | Notebook    | [7e63fb0312](https://linux-hardware.org/?probe=7e63fb0312) | May 17, 2020 |
| HP            | Presario V5000 (EX096PA#... | Notebook    | [f3c46cc46c](https://linux-hardware.org/?probe=f3c46cc46c) | May 17, 2020 |
| Lenovo        | Unknown                     | Notebook    | [ff60458293](https://linux-hardware.org/?probe=ff60458293) | May 17, 2020 |
| Lenovo        | Unknown                     | Notebook    | [2176e7fb78](https://linux-hardware.org/?probe=2176e7fb78) | May 17, 2020 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [b9ae621029](https://linux-hardware.org/?probe=b9ae621029) | May 16, 2020 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [ef94f890dd](https://linux-hardware.org/?probe=ef94f890dd) | May 16, 2020 |
| Acer          | V5-131                      | Notebook    | [9d9e227434](https://linux-hardware.org/?probe=9d9e227434) | May 16, 2020 |
| Acer          | AO722                       | Notebook    | [822175ace8](https://linux-hardware.org/?probe=822175ace8) | May 16, 2020 |
| Samsung       | R425D/R525D                 | Notebook    | [8e54082560](https://linux-hardware.org/?probe=8e54082560) | May 16, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V6555        | Notebook    | [abf8542459](https://linux-hardware.org/?probe=abf8542459) | May 16, 2020 |
| Gigabyte      | H61M-S1                     | Desktop     | [493ce118d1](https://linux-hardware.org/?probe=493ce118d1) | May 16, 2020 |
| ASUSTek       | UX331UA                     | Notebook    | [0a0319493d](https://linux-hardware.org/?probe=0a0319493d) | May 15, 2020 |
| Gigabyte      | H61M-S1                     | Desktop     | [98a86c1397](https://linux-hardware.org/?probe=98a86c1397) | May 15, 2020 |
| Acer          | Aspire 8943G                | Notebook    | [1b520f3904](https://linux-hardware.org/?probe=1b520f3904) | May 15, 2020 |
| ASUSTek       | P5KPL-CM                    | Desktop     | [812daab45f](https://linux-hardware.org/?probe=812daab45f) | May 15, 2020 |
| MSI           | GL63 8RD                    | Notebook    | [c291440c2f](https://linux-hardware.org/?probe=c291440c2f) | May 14, 2020 |
| MSI           | GL63 8RD                    | Notebook    | [96120d0ebb](https://linux-hardware.org/?probe=96120d0ebb) | May 14, 2020 |
| ASUSTek       | F2A85-M PRO                 | Desktop     | [3edebf56b2](https://linux-hardware.org/?probe=3edebf56b2) | May 13, 2020 |
| Acer          | MCP73O NVIDIA MCP73O        | Desktop     | [25be25d5ee](https://linux-hardware.org/?probe=25be25d5ee) | May 13, 2020 |
| HP            | Pavilion dv7                | Notebook    | [d7bfa6ea91](https://linux-hardware.org/?probe=d7bfa6ea91) | May 13, 2020 |
| Dell          | 05DN3X A00                  | Desktop     | [e206d656a7](https://linux-hardware.org/?probe=e206d656a7) | May 13, 2020 |
| ECS           | G41T-M                      | Desktop     | [6349e4f073](https://linux-hardware.org/?probe=6349e4f073) | May 13, 2020 |
| HP            | Notebook                    | Notebook    | [dbed542e5a](https://linux-hardware.org/?probe=dbed542e5a) | May 12, 2020 |
| Dell          | Latitude E6330              | Notebook    | [7f58dd399d](https://linux-hardware.org/?probe=7f58dd399d) | May 12, 2020 |
| Dell          | Latitude E6330              | Notebook    | [1e167b4d43](https://linux-hardware.org/?probe=1e167b4d43) | May 12, 2020 |
| Dell          | Precision M4800             | Notebook    | [028edf486d](https://linux-hardware.org/?probe=028edf486d) | May 11, 2020 |
| Durabook      | S15H                        | Notebook    | [1a1add4428](https://linux-hardware.org/?probe=1a1add4428) | May 11, 2020 |
| Acer          | Spin SP111-32N              | Convertible | [dd5825cb70](https://linux-hardware.org/?probe=dd5825cb70) | May 11, 2020 |
| Lenovo        | ThinkPad X240 20AMS72T00    | Notebook    | [e24475b169](https://linux-hardware.org/?probe=e24475b169) | May 11, 2020 |
| Medion        | ERAZER X7853 MD60604        | Notebook    | [adfafba25e](https://linux-hardware.org/?probe=adfafba25e) | May 10, 2020 |
| Dell          | 0HJ054                      | Desktop     | [27a904303c](https://linux-hardware.org/?probe=27a904303c) | May 09, 2020 |
| Lenovo        | ThinkPad E585 20KV0010US    | Notebook    | [43f18a12b0](https://linux-hardware.org/?probe=43f18a12b0) | May 09, 2020 |
| HP            | EliteBook Folio 9480m       | Notebook    | [3956d54072](https://linux-hardware.org/?probe=3956d54072) | May 09, 2020 |
| ASUSTek       | X750JA                      | Notebook    | [d03ab2ced2](https://linux-hardware.org/?probe=d03ab2ced2) | May 08, 2020 |
| Acer          | AOD255                      | Notebook    | [c9feab0ae6](https://linux-hardware.org/?probe=c9feab0ae6) | May 07, 2020 |
| Acer          | AOD255                      | Notebook    | [685122de57](https://linux-hardware.org/?probe=685122de57) | May 07, 2020 |
| Acer          | AOD255                      | Notebook    | [8f8f4e61eb](https://linux-hardware.org/?probe=8f8f4e61eb) | May 07, 2020 |
| HP            | Pavilion dv7                | Notebook    | [886f774f58](https://linux-hardware.org/?probe=886f774f58) | May 07, 2020 |
| Apple         | Mac-F4208EC8 PVT            | Mini pc     | [970a9cb8bf](https://linux-hardware.org/?probe=970a9cb8bf) | May 07, 2020 |
| HP            | 15                          | Notebook    | [e4ffb09704](https://linux-hardware.org/?probe=e4ffb09704) | May 07, 2020 |
| Dell          | Vostro 3550                 | Notebook    | [aeb508b54b](https://linux-hardware.org/?probe=aeb508b54b) | May 07, 2020 |
| Acer          | Acadia V1.17                | Notebook    | [eed274f8c5](https://linux-hardware.org/?probe=eed274f8c5) | May 07, 2020 |
| HP            | Compaq 6735s                | Notebook    | [d5aff5abe3](https://linux-hardware.org/?probe=d5aff5abe3) | May 07, 2020 |
| Fujitsu       | LIFEBOOK S752               | Notebook    | [3150f82299](https://linux-hardware.org/?probe=3150f82299) | May 06, 2020 |
| HP            | Laptop 15-rb0xx             | Notebook    | [0d840277dc](https://linux-hardware.org/?probe=0d840277dc) | May 06, 2020 |
| ASUSTek       | T100TA                      | Notebook    | [84f83e4bff](https://linux-hardware.org/?probe=84f83e4bff) | May 06, 2020 |
| ASUSTek       | X302LA                      | Notebook    | [a994852110](https://linux-hardware.org/?probe=a994852110) | May 06, 2020 |
| Foxconn       | 2AAF                        | Desktop     | [62a67147a3](https://linux-hardware.org/?probe=62a67147a3) | May 05, 2020 |
| HP            | Pavilion dv6                | Notebook    | [f1cc639edf](https://linux-hardware.org/?probe=f1cc639edf) | May 04, 2020 |
| Fujitsu       | LIFEBOOK AH531/GFO          | Notebook    | [5e583d58df](https://linux-hardware.org/?probe=5e583d58df) | May 03, 2020 |
| Positivo      | S14CT01                     | Notebook    | [493497d221](https://linux-hardware.org/?probe=493497d221) | May 03, 2020 |
| Positivo      | S14CT01                     | Notebook    | [518301afe9](https://linux-hardware.org/?probe=518301afe9) | May 03, 2020 |
| Dell          | Inspiron 7548               | Notebook    | [b951e05771](https://linux-hardware.org/?probe=b951e05771) | May 03, 2020 |
| Dell          | Latitude E6400              | Notebook    | [a50bb7e32a](https://linux-hardware.org/?probe=a50bb7e32a) | May 03, 2020 |
| Dell          | 0YXT71 A02                  | Desktop     | [421a518f5e](https://linux-hardware.org/?probe=421a518f5e) | May 02, 2020 |
| Dell          | 0YXT71 A02                  | Desktop     | [f734fb76dd](https://linux-hardware.org/?probe=f734fb76dd) | May 02, 2020 |
| Dell          | Inspiron N4050              | Notebook    | [e64e5a4e36](https://linux-hardware.org/?probe=e64e5a4e36) | May 02, 2020 |
| ASUSTek       | UL20A                       | Notebook    | [de8a903a2b](https://linux-hardware.org/?probe=de8a903a2b) | May 01, 2020 |
| Lenovo        | ThinkCentre M57 6072W2A     | Desktop     | [d42ad893b6](https://linux-hardware.org/?probe=d42ad893b6) | May 01, 2020 |
| Pegatron      | 2A99                        | Desktop     | [8dabe1b5d6](https://linux-hardware.org/?probe=8dabe1b5d6) | May 01, 2020 |
| Pegatron      | 2A99                        | Desktop     | [1d07b40055](https://linux-hardware.org/?probe=1d07b40055) | May 01, 2020 |
| HP            | 0AE8h C                     | Desktop     | [94f0b85b34](https://linux-hardware.org/?probe=94f0b85b34) | May 01, 2020 |
| Lenovo        | ThinkCentre M57 6072W2A     | Desktop     | [366d3d0483](https://linux-hardware.org/?probe=366d3d0483) | May 01, 2020 |
| HP            | ProBook 450 G2              | Notebook    | [887a19760b](https://linux-hardware.org/?probe=887a19760b) | May 01, 2020 |
| HP            | Pavilion x2 Detachable      | Notebook    | [4b6ec5f44b](https://linux-hardware.org/?probe=4b6ec5f44b) | May 01, 2020 |
| Dell          | Studio 1737                 | Notebook    | [50af5c4e99](https://linux-hardware.org/?probe=50af5c4e99) | May 01, 2020 |
| HP            | EliteBook Folio 9480m       | Notebook    | [41b9926566](https://linux-hardware.org/?probe=41b9926566) | May 01, 2020 |
| Medion        | E5217                       | Notebook    | [a6b33d3a94](https://linux-hardware.org/?probe=a6b33d3a94) | Apr 30, 2020 |
| ASUSTek       | P5PL2                       | Desktop     | [e0c0ba9cf1](https://linux-hardware.org/?probe=e0c0ba9cf1) | Apr 30, 2020 |
| HP            | 84EE 1100                   | All in one  | [64755a3ad1](https://linux-hardware.org/?probe=64755a3ad1) | Apr 30, 2020 |
| Acer          | Nitro AN515-42              | Notebook    | [8b9ad27475](https://linux-hardware.org/?probe=8b9ad27475) | Apr 29, 2020 |
| Dixonsxp      | Unknown                     | Notebook    | [e9bf36b6e0](https://linux-hardware.org/?probe=e9bf36b6e0) | Apr 29, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | Notebook    | [bf1e5c9655](https://linux-hardware.org/?probe=bf1e5c9655) | Apr 29, 2020 |
| HP            | 84EE 1100                   | All in one  | [f41c6840ba](https://linux-hardware.org/?probe=f41c6840ba) | Apr 29, 2020 |
| HP            | Pavilion dv6                | Notebook    | [887b97f4e8](https://linux-hardware.org/?probe=887b97f4e8) | Apr 28, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [fc5a0610b7](https://linux-hardware.org/?probe=fc5a0610b7) | Apr 28, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [33d573c960](https://linux-hardware.org/?probe=33d573c960) | Apr 28, 2020 |
| Dell          | Inspiron 5570               | Notebook    | [1e1ab08268](https://linux-hardware.org/?probe=1e1ab08268) | Apr 28, 2020 |
| IBM           | ThinkPad X40 2371H4G        | Notebook    | [190737f754](https://linux-hardware.org/?probe=190737f754) | Apr 28, 2020 |
| HP            | Compaq Presario CQ60        | Notebook    | [2539260c46](https://linux-hardware.org/?probe=2539260c46) | Apr 28, 2020 |
| ASUSTek       | T100TA                      | Notebook    | [bebdfd359d](https://linux-hardware.org/?probe=bebdfd359d) | Apr 27, 2020 |
| Dell          | 0CU409                      | Desktop     | [4f9670da15](https://linux-hardware.org/?probe=4f9670da15) | Apr 26, 2020 |
| Dell          | 0CU409                      | Desktop     | [126e4066c8](https://linux-hardware.org/?probe=126e4066c8) | Apr 26, 2020 |
| ASUSTek       | T100TA                      | Notebook    | [c1abf7906c](https://linux-hardware.org/?probe=c1abf7906c) | Apr 26, 2020 |
| Toshiba       | Satellite L550              | Notebook    | [73f10216d6](https://linux-hardware.org/?probe=73f10216d6) | Apr 25, 2020 |
| ABIT          | IP35 Pro                    | Desktop     | [0465b43386](https://linux-hardware.org/?probe=0465b43386) | Apr 25, 2020 |
| HP            | Laptop 15-da0xxx            | Notebook    | [34c85393d6](https://linux-hardware.org/?probe=34c85393d6) | Apr 24, 2020 |
| HP            | 15                          | Notebook    | [54d9c92866](https://linux-hardware.org/?probe=54d9c92866) | Apr 24, 2020 |
| ASUSTek       | P5KPL-AM                    | Desktop     | [7dceeca2dd](https://linux-hardware.org/?probe=7dceeca2dd) | Apr 24, 2020 |
| ASUSTek       | UX331UA                     | Notebook    | [634f000249](https://linux-hardware.org/?probe=634f000249) | Apr 24, 2020 |
| ASUSTek       | UX331UA                     | Notebook    | [94be2c2ea7](https://linux-hardware.org/?probe=94be2c2ea7) | Apr 24, 2020 |
| Dell          | Inspiron 15-3567            | Notebook    | [0e9d3a198e](https://linux-hardware.org/?probe=0e9d3a198e) | Apr 24, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [b3a9583301](https://linux-hardware.org/?probe=b3a9583301) | Apr 23, 2020 |
| Notebook      | N750BU                      | Notebook    | [e3f870729f](https://linux-hardware.org/?probe=e3f870729f) | Apr 23, 2020 |
| ASUSTek       | T100TA                      | Notebook    | [6cd72a2a26](https://linux-hardware.org/?probe=6cd72a2a26) | Apr 23, 2020 |
| Gigabyte      | AM1M-S2H                    | Desktop     | [70238ca50c](https://linux-hardware.org/?probe=70238ca50c) | Apr 23, 2020 |
| Gigabyte      | AM1M-S2H                    | Desktop     | [fcb68181d7](https://linux-hardware.org/?probe=fcb68181d7) | Apr 23, 2020 |
| Dell          | 0HJ054                      | Desktop     | [5c8a25898b](https://linux-hardware.org/?probe=5c8a25898b) | Apr 22, 2020 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | Notebook    | [f35ddd7bef](https://linux-hardware.org/?probe=f35ddd7bef) | Apr 22, 2020 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | Notebook    | [53b078eba2](https://linux-hardware.org/?probe=53b078eba2) | Apr 22, 2020 |
| ASUSTek       | M2A-MX                      | Desktop     | [1a52399cac](https://linux-hardware.org/?probe=1a52399cac) | Apr 21, 2020 |
| ASUSTek       | X553MA                      | Notebook    | [dabe283d4d](https://linux-hardware.org/?probe=dabe283d4d) | Apr 21, 2020 |
| HP            | Presario V3700              | Notebook    | [0eac5f43d5](https://linux-hardware.org/?probe=0eac5f43d5) | Apr 21, 2020 |
| Dell          | Inspiron 1720               | Notebook    | [5bbab2bc27](https://linux-hardware.org/?probe=5bbab2bc27) | Apr 21, 2020 |
| ASUSTek       | TP300LA                     | Notebook    | [c3f624dcbd](https://linux-hardware.org/?probe=c3f624dcbd) | Apr 20, 2020 |
| ASUSTek       | P5Q-VM DO                   | Desktop     | [fc60d56b77](https://linux-hardware.org/?probe=fc60d56b77) | Apr 19, 2020 |
| HP            | 255 G2                      | Notebook    | [2e24d05e40](https://linux-hardware.org/?probe=2e24d05e40) | Apr 19, 2020 |
| HP            | Pavilion dv1000 (ET735UA... | Notebook    | [6eea6e679b](https://linux-hardware.org/?probe=6eea6e679b) | Apr 19, 2020 |
| HP            | Pavilion dv9500             | Notebook    | [24a912a8a2](https://linux-hardware.org/?probe=24a912a8a2) | Apr 19, 2020 |
| Sony          | VPCEB3M1E                   | Notebook    | [de0457eba6](https://linux-hardware.org/?probe=de0457eba6) | Apr 19, 2020 |
| Dell          | Inspiron 7537               | Notebook    | [58c5b959e4](https://linux-hardware.org/?probe=58c5b959e4) | Apr 19, 2020 |
| HP            | 2133 (FU338EA)              | Notebook    | [d9b0c55ac8](https://linux-hardware.org/?probe=d9b0c55ac8) | Apr 18, 2020 |
| Sony          | VGN-AW11Z_B                 | Notebook    | [c831660ca5](https://linux-hardware.org/?probe=c831660ca5) | Apr 18, 2020 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [45f9fd21d8](https://linux-hardware.org/?probe=45f9fd21d8) | Apr 18, 2020 |
| Gateway       | MX3225                      | Notebook    | [2b23ba49b1](https://linux-hardware.org/?probe=2b23ba49b1) | Apr 18, 2020 |
| Gateway       | MX3225                      | Notebook    | [b3844e839e](https://linux-hardware.org/?probe=b3844e839e) | Apr 18, 2020 |
| Lenovo        | ThinkPad T420 42368H6       | Notebook    | [f65f8c3464](https://linux-hardware.org/?probe=f65f8c3464) | Apr 18, 2020 |
| HP            | 550                         | Notebook    | [078cde1a1b](https://linux-hardware.org/?probe=078cde1a1b) | Apr 18, 2020 |
| Lenovo        | ThinkPad T420 42368H6       | Notebook    | [806064d978](https://linux-hardware.org/?probe=806064d978) | Apr 18, 2020 |
| ABIT          | IP35 Pro                    | Desktop     | [c1d15add68](https://linux-hardware.org/?probe=c1d15add68) | Apr 18, 2020 |
| ASUSTek       | ROG STRIX X399-E GAMING     | Desktop     | [e77ad6aa22](https://linux-hardware.org/?probe=e77ad6aa22) | Apr 18, 2020 |
| AXIOO         | NEON CNW                    | Notebook    | [64edfa7923](https://linux-hardware.org/?probe=64edfa7923) | Apr 18, 2020 |
| ASUSTek       | N46VB                       | Notebook    | [d27bf3c005](https://linux-hardware.org/?probe=d27bf3c005) | Apr 18, 2020 |
| ASUSTek       | N46VB                       | Notebook    | [5d25f725c9](https://linux-hardware.org/?probe=5d25f725c9) | Apr 18, 2020 |
| Sony          | VPCYB35AL                   | Notebook    | [a96bfb28b5](https://linux-hardware.org/?probe=a96bfb28b5) | Apr 18, 2020 |
| ASUSTek       | N46VB                       | Notebook    | [eae7b8a990](https://linux-hardware.org/?probe=eae7b8a990) | Apr 17, 2020 |
| ASUSTek       | N46VB                       | Notebook    | [ab1938abc6](https://linux-hardware.org/?probe=ab1938abc6) | Apr 17, 2020 |
| Clevo         | M7x0S                       | Notebook    | [2dc8a215f6](https://linux-hardware.org/?probe=2dc8a215f6) | Apr 17, 2020 |
| Clevo         | M7x0S                       | Notebook    | [562739a94b](https://linux-hardware.org/?probe=562739a94b) | Apr 17, 2020 |
| Acer          | E1-510                      | Notebook    | [933b2f30b0](https://linux-hardware.org/?probe=933b2f30b0) | Apr 17, 2020 |
| HP            | ProBook 450 G2              | Notebook    | [1ef49ff7a3](https://linux-hardware.org/?probe=1ef49ff7a3) | Apr 17, 2020 |
| HP            | EliteBook 8460p             | Notebook    | [41c3cb6523](https://linux-hardware.org/?probe=41c3cb6523) | Apr 17, 2020 |
| HP            | EliteBook 8460p             | Notebook    | [e5283d7a27](https://linux-hardware.org/?probe=e5283d7a27) | Apr 17, 2020 |
| Sony          | VGN-AW11Z_B                 | Notebook    | [57a0d65d23](https://linux-hardware.org/?probe=57a0d65d23) | Apr 16, 2020 |
| Lenovo        | Yoga C740-15IML 81TD        | Convertible | [1c0d6b2c66](https://linux-hardware.org/?probe=1c0d6b2c66) | Apr 16, 2020 |
| Samsung       | RV410/RV510/S3510/E3510     | Notebook    | [a63c3876d5](https://linux-hardware.org/?probe=a63c3876d5) | Apr 16, 2020 |
| ASUSTek       | T100TA                      | Notebook    | [487d046945](https://linux-hardware.org/?probe=487d046945) | Apr 16, 2020 |
| Dell          | Latitude E6440              | Notebook    | [d2eaa5d809](https://linux-hardware.org/?probe=d2eaa5d809) | Apr 16, 2020 |
| ASUSTek       | S400CA                      | Notebook    | [ddc5a34acb](https://linux-hardware.org/?probe=ddc5a34acb) | Apr 16, 2020 |
| ASUSTek       | S400CA                      | Notebook    | [959d3bcbb2](https://linux-hardware.org/?probe=959d3bcbb2) | Apr 16, 2020 |
| Acer          | Prespa1                     | Notebook    | [791259386e](https://linux-hardware.org/?probe=791259386e) | Apr 16, 2020 |
| HP            | Pavilion 17                 | Notebook    | [d54ff69694](https://linux-hardware.org/?probe=d54ff69694) | Apr 16, 2020 |
| HP            | Gaming PC                   | Notebook    | [472ccadaa3](https://linux-hardware.org/?probe=472ccadaa3) | Apr 16, 2020 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | Notebook    | [e2a5957771](https://linux-hardware.org/?probe=e2a5957771) | Apr 15, 2020 |
| Lenovo        | ThinkPad Edge E440 20C50... | Notebook    | [bc9d3d1f9c](https://linux-hardware.org/?probe=bc9d3d1f9c) | Apr 15, 2020 |
| ASUSTek       | Z97-AR                      | Desktop     | [77c735475e](https://linux-hardware.org/?probe=77c735475e) | Apr 15, 2020 |
| Samsung       | 905S3G/906S3G/915S3G/930... | Notebook    | [7c86e73d6e](https://linux-hardware.org/?probe=7c86e73d6e) | Apr 15, 2020 |
| Dell          | Latitude E5550              | Notebook    | [37d3c8c386](https://linux-hardware.org/?probe=37d3c8c386) | Apr 15, 2020 |
| HP            | 2133 (FU338EA)              | Notebook    | [029ce5169b](https://linux-hardware.org/?probe=029ce5169b) | Apr 15, 2020 |
| MSI           | A68HM-E33 V2                | Desktop     | [d88e072663](https://linux-hardware.org/?probe=d88e072663) | Apr 15, 2020 |
| Acer          | Aspire 5610Z                | Notebook    | [65a4d9621d](https://linux-hardware.org/?probe=65a4d9621d) | Apr 14, 2020 |
| Acer          | Nitro N50-600 V:1.1         | Desktop     | [9215c07605](https://linux-hardware.org/?probe=9215c07605) | Apr 14, 2020 |
| Acer          | Nitro N50-600 V:1.1         | Desktop     | [9fef854e9c](https://linux-hardware.org/?probe=9fef854e9c) | Apr 14, 2020 |
| ASRock        | A320M-HDV R3.0              | Desktop     | [6095aae488](https://linux-hardware.org/?probe=6095aae488) | Apr 14, 2020 |
| Universal ... | ITL 1161-32                 | Convertible | [96bd1814c7](https://linux-hardware.org/?probe=96bd1814c7) | Apr 14, 2020 |
| Dell          | Latitude E6510              | Notebook    | [ca17782e8f](https://linux-hardware.org/?probe=ca17782e8f) | Apr 14, 2020 |
| Dell          | Latitude E6510              | Notebook    | [a276d0e4e8](https://linux-hardware.org/?probe=a276d0e4e8) | Apr 14, 2020 |
| Apple         | MacBookPro10,1              | Notebook    | [37327526d9](https://linux-hardware.org/?probe=37327526d9) | Apr 13, 2020 |
| Nuvision      | L1W6_I1101_G Hampoo Rese... | Notebook    | [0277194797](https://linux-hardware.org/?probe=0277194797) | Apr 13, 2020 |
| Dell          | Latitude E6410              | Notebook    | [54dd58d213](https://linux-hardware.org/?probe=54dd58d213) | Apr 13, 2020 |
| eMachines     | G630                        | Notebook    | [2f15422dcd](https://linux-hardware.org/?probe=2f15422dcd) | Apr 13, 2020 |
| Dell          | Inspiron 3442               | Notebook    | [4d48cc531a](https://linux-hardware.org/?probe=4d48cc531a) | Apr 13, 2020 |
| Dell          | Inspiron 3442               | Notebook    | [07a7a6e630](https://linux-hardware.org/?probe=07a7a6e630) | Apr 13, 2020 |
| ASRock        | A320M-HDV R3.0              | Desktop     | [41f0f05e33](https://linux-hardware.org/?probe=41f0f05e33) | Apr 13, 2020 |
| ECS           | MCP61M-M3                   | Desktop     | [647ce2238f](https://linux-hardware.org/?probe=647ce2238f) | Apr 13, 2020 |
| ECS           | MCP61M-M3                   | Desktop     | [f15d3102c6](https://linux-hardware.org/?probe=f15d3102c6) | Apr 13, 2020 |
| MSI           | MS-1688                     | Notebook    | [e6a4077b27](https://linux-hardware.org/?probe=e6a4077b27) | Apr 13, 2020 |
| MSI           | MS-1688                     | Notebook    | [d0d5f98071](https://linux-hardware.org/?probe=d0d5f98071) | Apr 12, 2020 |
| Clevo         | D900C Revision D            | Notebook    | [1fb3feea04](https://linux-hardware.org/?probe=1fb3feea04) | Apr 12, 2020 |
| ASUSTek       | X200CA                      | Notebook    | [3c52d09634](https://linux-hardware.org/?probe=3c52d09634) | Apr 12, 2020 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [20eeb3f580](https://linux-hardware.org/?probe=20eeb3f580) | Apr 12, 2020 |
| Ematic        | EW147                       | Notebook    | [4dd070feda](https://linux-hardware.org/?probe=4dd070feda) | Apr 12, 2020 |
| Ematic        | EW147                       | Notebook    | [1176adc6a1](https://linux-hardware.org/?probe=1176adc6a1) | Apr 12, 2020 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [11251407bd](https://linux-hardware.org/?probe=11251407bd) | Apr 11, 2020 |
| Acer          | One S1002                   | Notebook    | [83314e9687](https://linux-hardware.org/?probe=83314e9687) | Apr 11, 2020 |
| Lenovo        | ThinkPad 10 20C10026UK      | Tablet      | [5cb3ab4e0b](https://linux-hardware.org/?probe=5cb3ab4e0b) | Apr 11, 2020 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [37f223475f](https://linux-hardware.org/?probe=37f223475f) | Apr 11, 2020 |
| Pegatron      | Narra6                      | Desktop     | [f256bf6555](https://linux-hardware.org/?probe=f256bf6555) | Apr 11, 2020 |
| HP            | Pavilion 15                 | Notebook    | [2f38c60e21](https://linux-hardware.org/?probe=2f38c60e21) | Apr 11, 2020 |
| HP            | Pavilion 15                 | Notebook    | [5b41ba3e4e](https://linux-hardware.org/?probe=5b41ba3e4e) | Apr 11, 2020 |
| Acer          | Extensa 5620                | Notebook    | [9501d84629](https://linux-hardware.org/?probe=9501d84629) | Apr 11, 2020 |
| Lenovo        | ThinkPad 11e 20DAS0YW00     | Notebook    | [15057e288d](https://linux-hardware.org/?probe=15057e288d) | Apr 11, 2020 |
| Apple         | MacBookAir4,2               | Notebook    | [5f84027e54](https://linux-hardware.org/?probe=5f84027e54) | Apr 11, 2020 |
| Acer          | Aspire 5741G                | Notebook    | [2a4c7dd1d5](https://linux-hardware.org/?probe=2a4c7dd1d5) | Apr 10, 2020 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [21a5c2580f](https://linux-hardware.org/?probe=21a5c2580f) | Apr 10, 2020 |
| Lenovo        | ThinkPad 11e 20DAS0YW00     | Notebook    | [90ca183e3d](https://linux-hardware.org/?probe=90ca183e3d) | Apr 10, 2020 |
| AXIOO         | NEON CNW                    | Notebook    | [b31fc0c0dd](https://linux-hardware.org/?probe=b31fc0c0dd) | Apr 10, 2020 |
| Fujitsu Si... | AMILO PRO V2030             | Notebook    | [67b8c113f9](https://linux-hardware.org/?probe=67b8c113f9) | Apr 10, 2020 |
| Fujitsu Si... | AMILO PRO V2030             | Notebook    | [432926e63e](https://linux-hardware.org/?probe=432926e63e) | Apr 10, 2020 |
| Lenovo        | G580 20157                  | Notebook    | [30a8d59bdc](https://linux-hardware.org/?probe=30a8d59bdc) | Apr 09, 2020 |
| Samsung       | 905S3G/906S3G/915S3G/930... | Notebook    | [ba943d4bc5](https://linux-hardware.org/?probe=ba943d4bc5) | Apr 09, 2020 |
| Lenovo        | G580 20157                  | Notebook    | [fc6eaad779](https://linux-hardware.org/?probe=fc6eaad779) | Apr 09, 2020 |
| MSI           | A68HM-E33 V2                | Desktop     | [6277a6ec0b](https://linux-hardware.org/?probe=6277a6ec0b) | Apr 08, 2020 |
| Lenovo        | Tiger Hill                  | Desktop     | [b1393ddb5a](https://linux-hardware.org/?probe=b1393ddb5a) | Apr 08, 2020 |
| Lenovo        | Tiger Hill                  | Desktop     | [122ea8633e](https://linux-hardware.org/?probe=122ea8633e) | Apr 08, 2020 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [0248492e22](https://linux-hardware.org/?probe=0248492e22) | Apr 08, 2020 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [b19f7181b4](https://linux-hardware.org/?probe=b19f7181b4) | Apr 08, 2020 |
| Gateway       | ML6228                      | Notebook    | [3fd17b9f82](https://linux-hardware.org/?probe=3fd17b9f82) | Apr 08, 2020 |
| Dell          | 0HY9JP A01                  | Desktop     | [3afcedf368](https://linux-hardware.org/?probe=3afcedf368) | Apr 07, 2020 |
| Packard Be... | EasyNote TJ65               | Notebook    | [3008be40c7](https://linux-hardware.org/?probe=3008be40c7) | Apr 06, 2020 |
| Gigabyte      | H67M-D2-B3                  | Desktop     | [d9e3975f83](https://linux-hardware.org/?probe=d9e3975f83) | Apr 06, 2020 |
| Dell          | 0KP561                      | Desktop     | [30bc17e0c1](https://linux-hardware.org/?probe=30bc17e0c1) | Apr 06, 2020 |
| Dell          | 0KP561                      | Desktop     | [d6260387a4](https://linux-hardware.org/?probe=d6260387a4) | Apr 06, 2020 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | Desktop     | [68b232efe4](https://linux-hardware.org/?probe=68b232efe4) | Apr 06, 2020 |
| Lenovo        | ThinkPad T440s 20AQ009HU... | Notebook    | [695389401a](https://linux-hardware.org/?probe=695389401a) | Apr 06, 2020 |
| Toshiba       | Satellite A200              | Notebook    | [b66adc41e3](https://linux-hardware.org/?probe=b66adc41e3) | Apr 05, 2020 |
| Toshiba       | Satellite A200              | Notebook    | [9b9a8bf80f](https://linux-hardware.org/?probe=9b9a8bf80f) | Apr 05, 2020 |
| Toshiba       | Satellite A200              | Notebook    | [59ab95abbb](https://linux-hardware.org/?probe=59ab95abbb) | Apr 05, 2020 |
| Acer          | Aspire 5741G                | Notebook    | [8ea2a664b6](https://linux-hardware.org/?probe=8ea2a664b6) | Apr 05, 2020 |
| Dell          | Latitude E6400              | Notebook    | [5a96047b26](https://linux-hardware.org/?probe=5a96047b26) | Apr 05, 2020 |
| Dell          | Latitude D520               | Notebook    | [69f550a570](https://linux-hardware.org/?probe=69f550a570) | Apr 05, 2020 |
| ASUSTek       | P5Q-VM DO                   | Desktop     | [f1dcc22829](https://linux-hardware.org/?probe=f1dcc22829) | Apr 05, 2020 |
| Toshiba       | Satellite C850D-B810        | Notebook    | [bfa7a5b4b3](https://linux-hardware.org/?probe=bfa7a5b4b3) | Apr 04, 2020 |
| Toshiba       | Satellite C850D-B810        | Notebook    | [d911f2bb34](https://linux-hardware.org/?probe=d911f2bb34) | Apr 04, 2020 |
| PCChips       | P49G                        | Desktop     | [57f11f5c76](https://linux-hardware.org/?probe=57f11f5c76) | Apr 04, 2020 |
| Toshiba       | Satellite L450              | Notebook    | [b18b01a081](https://linux-hardware.org/?probe=b18b01a081) | Apr 04, 2020 |
| Acer          | Aspire 5742G                | Notebook    | [c83a4dfe3c](https://linux-hardware.org/?probe=c83a4dfe3c) | Apr 04, 2020 |
| HP            | Mini 5103                   | Notebook    | [c60a2a2852](https://linux-hardware.org/?probe=c60a2a2852) | Apr 04, 2020 |
| Dell          | Inspiron 3179               | Notebook    | [4f8f1dd9c8](https://linux-hardware.org/?probe=4f8f1dd9c8) | Apr 04, 2020 |
| HP            | G62                         | Notebook    | [65f362927c](https://linux-hardware.org/?probe=65f362927c) | Apr 04, 2020 |
| Dell          | Latitude X1                 | Notebook    | [47f2bd6300](https://linux-hardware.org/?probe=47f2bd6300) | Apr 03, 2020 |
| Dell          | Latitude X1                 | Notebook    | [d753de9b00](https://linux-hardware.org/?probe=d753de9b00) | Apr 03, 2020 |
| Dell          | 03KPVW A00                  | All in one  | [421117de9d](https://linux-hardware.org/?probe=421117de9d) | Apr 03, 2020 |
| Acer          | Aspire A315-41              | Notebook    | [ec505d4ab7](https://linux-hardware.org/?probe=ec505d4ab7) | Apr 02, 2020 |
| Dell          | 06NWYK A01                  | Desktop     | [4229337b5c](https://linux-hardware.org/?probe=4229337b5c) | Apr 02, 2020 |
| NEC Comput... | PC-VY24GXZ7A                | Notebook    | [a602b4a98e](https://linux-hardware.org/?probe=a602b4a98e) | Apr 02, 2020 |
| NEC Comput... | PC-VY24GXZ7A                | Notebook    | [bc0996781f](https://linux-hardware.org/?probe=bc0996781f) | Apr 02, 2020 |
| Dell          | Latitude E6410              | Notebook    | [147488a290](https://linux-hardware.org/?probe=147488a290) | Apr 02, 2020 |
| ASUSTek       | P5KPL-AM                    | Desktop     | [4db785101b](https://linux-hardware.org/?probe=4db785101b) | Apr 01, 2020 |
| Acer          | Nitro AN515-51              | Notebook    | [d6b01aa670](https://linux-hardware.org/?probe=d6b01aa670) | Apr 01, 2020 |
| Lenovo        | 370C SDK0J40700 WIN 3258... | All in one  | [4ea81b87e9](https://linux-hardware.org/?probe=4ea81b87e9) | Apr 01, 2020 |
| HP            | 1632                        | Desktop     | [660244a3b1](https://linux-hardware.org/?probe=660244a3b1) | Apr 01, 2020 |
| Dell          | Latitude E6410              | Notebook    | [766122819f](https://linux-hardware.org/?probe=766122819f) | Apr 01, 2020 |
| ABIT          | AV8                         | Desktop     | [b996d0c641](https://linux-hardware.org/?probe=b996d0c641) | Mar 31, 2020 |
| Acer          | Extensa 5620                | Notebook    | [2cc79b3cc5](https://linux-hardware.org/?probe=2cc79b3cc5) | Mar 31, 2020 |
| Lenovo        | ThinkPad R400 7440WWQ       | Notebook    | [ac4c4ee6d7](https://linux-hardware.org/?probe=ac4c4ee6d7) | Mar 31, 2020 |
| HP            | ProBook 4525s               | Notebook    | [cb0a6c08db](https://linux-hardware.org/?probe=cb0a6c08db) | Mar 31, 2020 |
| Lenovo        | IdeaPad Y570 20091          | Notebook    | [2a38b92cb1](https://linux-hardware.org/?probe=2a38b92cb1) | Mar 31, 2020 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [2a761bfaee](https://linux-hardware.org/?probe=2a761bfaee) | Mar 30, 2020 |
| Acer          | Aspire A315-41              | Notebook    | [59c568e03a](https://linux-hardware.org/?probe=59c568e03a) | Mar 30, 2020 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [d27ea3ee61](https://linux-hardware.org/?probe=d27ea3ee61) | Mar 30, 2020 |
| Sony          | VPCM13M1E                   | Notebook    | [eb20399d8b](https://linux-hardware.org/?probe=eb20399d8b) | Mar 30, 2020 |
| Acer          | Aspire A315-41              | Notebook    | [592d008d70](https://linux-hardware.org/?probe=592d008d70) | Mar 30, 2020 |
| Gigabyte      | Z170N-Gaming 5              | Desktop     | [4d21c77b2b](https://linux-hardware.org/?probe=4d21c77b2b) | Mar 30, 2020 |
| Gigabyte      | Z170N-Gaming 5              | Desktop     | [6b1c9f4403](https://linux-hardware.org/?probe=6b1c9f4403) | Mar 30, 2020 |
| ASUSTek       | X553MA                      | Notebook    | [47e6377b3b](https://linux-hardware.org/?probe=47e6377b3b) | Mar 30, 2020 |
| ASUSTek       | X553MA                      | Notebook    | [63e00b46e2](https://linux-hardware.org/?probe=63e00b46e2) | Mar 30, 2020 |
| ASUSTek       | 1101HAGG                    | Notebook    | [1ecc8fa4d3](https://linux-hardware.org/?probe=1ecc8fa4d3) | Mar 29, 2020 |
| HP            | Notebook                    | Notebook    | [6d16eabcdb](https://linux-hardware.org/?probe=6d16eabcdb) | Mar 29, 2020 |
| ASUSTek       | 1101HAGG                    | Notebook    | [8d2c258ed7](https://linux-hardware.org/?probe=8d2c258ed7) | Mar 29, 2020 |
| ASUSTek       | M2N-E                       | Desktop     | [374938e33e](https://linux-hardware.org/?probe=374938e33e) | Mar 29, 2020 |
| HP            | OMEN by Laptop              | Notebook    | [eec0858042](https://linux-hardware.org/?probe=eec0858042) | Mar 29, 2020 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [0120aa60f5](https://linux-hardware.org/?probe=0120aa60f5) | Mar 29, 2020 |
| ASRock        | P43D1600Twins-1394          | Desktop     | [5bfcede830](https://linux-hardware.org/?probe=5bfcede830) | Mar 29, 2020 |
| Dell          | Inspiron 1520               | Notebook    | [146388e7f0](https://linux-hardware.org/?probe=146388e7f0) | Mar 29, 2020 |
| ASUSTek       | M2N-E                       | Desktop     | [7a234988b2](https://linux-hardware.org/?probe=7a234988b2) | Mar 28, 2020 |
| HP            | ProBook 4525s               | Notebook    | [dc9164d939](https://linux-hardware.org/?probe=dc9164d939) | Mar 28, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [bcbfe2da9a](https://linux-hardware.org/?probe=bcbfe2da9a) | Mar 28, 2020 |
| Samsung       | 305V4A/305V5A/3415VA        | Notebook    | [118b531086](https://linux-hardware.org/?probe=118b531086) | Mar 28, 2020 |
| Samsung       | 305V4A/305V5A/3415VA        | Notebook    | [4d70e47759](https://linux-hardware.org/?probe=4d70e47759) | Mar 28, 2020 |
| Samsung       | 800G5M/800G5W               | Notebook    | [f8a5c21d24](https://linux-hardware.org/?probe=f8a5c21d24) | Mar 28, 2020 |
| HP            | Pavilion g6                 | Notebook    | [cfe67dc8eb](https://linux-hardware.org/?probe=cfe67dc8eb) | Mar 27, 2020 |
| HP            | Pavilion g6                 | Notebook    | [058cce86bb](https://linux-hardware.org/?probe=058cce86bb) | Mar 27, 2020 |
| ASUSTek       | N750JK                      | Notebook    | [172ea4a7d1](https://linux-hardware.org/?probe=172ea4a7d1) | Mar 27, 2020 |
| Dell          | Inspiron 1520               | Notebook    | [0bd42bbb3a](https://linux-hardware.org/?probe=0bd42bbb3a) | Mar 27, 2020 |
| Dell          | Inspiron 5570               | Notebook    | [922814f637](https://linux-hardware.org/?probe=922814f637) | Mar 27, 2020 |
| Dell          | Inspiron 5570               | Notebook    | [b8ac8ae9e4](https://linux-hardware.org/?probe=b8ac8ae9e4) | Mar 27, 2020 |
| I-Life Dig... | ZED_AIR_PLUS                | Convertible | [b1a911e13e](https://linux-hardware.org/?probe=b1a911e13e) | Mar 27, 2020 |
| HP            | Pavilion 10 TS              | Notebook    | [87484a7033](https://linux-hardware.org/?probe=87484a7033) | Mar 27, 2020 |
| Panasonic     | CF-31ACJAXPM                | Notebook    | [44a7635515](https://linux-hardware.org/?probe=44a7635515) | Mar 27, 2020 |
| eMachines     | eME728                      | Notebook    | [26425bd7a4](https://linux-hardware.org/?probe=26425bd7a4) | Mar 26, 2020 |
| Acer          | Aspire A315-31              | Notebook    | [1755330821](https://linux-hardware.org/?probe=1755330821) | Mar 26, 2020 |
| HP            | Pavilion dv9700             | Notebook    | [7567e3c677](https://linux-hardware.org/?probe=7567e3c677) | Mar 26, 2020 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [2160b3217e](https://linux-hardware.org/?probe=2160b3217e) | Mar 25, 2020 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [105f3f7e4b](https://linux-hardware.org/?probe=105f3f7e4b) | Mar 25, 2020 |
| ASRock        | B85M Pro4                   | Desktop     | [ec25a2a206](https://linux-hardware.org/?probe=ec25a2a206) | Mar 25, 2020 |
| Dell          | Latitude E5440              | Notebook    | [d5e19d53dc](https://linux-hardware.org/?probe=d5e19d53dc) | Mar 25, 2020 |
| MSI           | GE62 6QF                    | Notebook    | [f951247a44](https://linux-hardware.org/?probe=f951247a44) | Mar 25, 2020 |
| HP            | ProBook 6550b               | Notebook    | [9cd41d9853](https://linux-hardware.org/?probe=9cd41d9853) | Mar 25, 2020 |
| Dell          | XPS 15 9560                 | Notebook    | [0f39d105a8](https://linux-hardware.org/?probe=0f39d105a8) | Mar 25, 2020 |
| Dell          | XPS 15 9560                 | Notebook    | [9453dadbd6](https://linux-hardware.org/?probe=9453dadbd6) | Mar 25, 2020 |
| HP            | Pavilion dv5                | Notebook    | [009a4aed18](https://linux-hardware.org/?probe=009a4aed18) | Mar 25, 2020 |
| ECS           | K8M890M-M                   | Desktop     | [93490e7142](https://linux-hardware.org/?probe=93490e7142) | Mar 24, 2020 |
| HP            | Presario C500 (RY510EA#A... | Notebook    | [e69a3bef68](https://linux-hardware.org/?probe=e69a3bef68) | Mar 24, 2020 |
| Toshiba       | Satellite C660              | Notebook    | [38c32074a0](https://linux-hardware.org/?probe=38c32074a0) | Mar 24, 2020 |
| Apple         | Mac-81E3E92DD6088272 iMa... | All in one  | [8c8d4642d3](https://linux-hardware.org/?probe=8c8d4642d3) | Mar 24, 2020 |
| Apple         | Mac-81E3E92DD6088272 iMa... | All in one  | [f4f823b37e](https://linux-hardware.org/?probe=f4f823b37e) | Mar 24, 2020 |
| HP            | ZBook 14u G4                | Notebook    | [2843fde2a7](https://linux-hardware.org/?probe=2843fde2a7) | Mar 23, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [e274c73209](https://linux-hardware.org/?probe=e274c73209) | Mar 23, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [e1607c9705](https://linux-hardware.org/?probe=e1607c9705) | Mar 23, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [a88a9a71a9](https://linux-hardware.org/?probe=a88a9a71a9) | Mar 23, 2020 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [1202fcbadd](https://linux-hardware.org/?probe=1202fcbadd) | Mar 23, 2020 |
| Toshiba       | Satellite L455D             | Notebook    | [1d8583d691](https://linux-hardware.org/?probe=1d8583d691) | Mar 23, 2020 |
| HP            | Pavilion 15                 | Notebook    | [b37a8bd4ff](https://linux-hardware.org/?probe=b37a8bd4ff) | Mar 22, 2020 |
| HP            | Pavilion x2 Detachable      | Notebook    | [27c5f0f340](https://linux-hardware.org/?probe=27c5f0f340) | Mar 22, 2020 |
| Lenovo        | ThinkPad T510 4349AW2       | Notebook    | [e8351b04a1](https://linux-hardware.org/?probe=e8351b04a1) | Mar 22, 2020 |
| HP            | ProBook 6550b               | Notebook    | [08a8d59e31](https://linux-hardware.org/?probe=08a8d59e31) | Mar 22, 2020 |
| Lenovo        | G510 20238                  | Notebook    | [9130b68bf4](https://linux-hardware.org/?probe=9130b68bf4) | Mar 22, 2020 |
| Sony          | SVF15A17CLB                 | Notebook    | [6f9e42f276](https://linux-hardware.org/?probe=6f9e42f276) | Mar 22, 2020 |
| Lenovo        | ThinkPad T510 4349AW2       | Notebook    | [428a0150aa](https://linux-hardware.org/?probe=428a0150aa) | Mar 21, 2020 |
| Samsung       | R519/R719                   | Notebook    | [df651d6929](https://linux-hardware.org/?probe=df651d6929) | Mar 21, 2020 |
| HP            | Pavilion Notebook 15-bc5... | Notebook    | [712dd83a31](https://linux-hardware.org/?probe=712dd83a31) | Mar 21, 2020 |
| HP            | G62                         | Notebook    | [6f4776017d](https://linux-hardware.org/?probe=6f4776017d) | Mar 21, 2020 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [a2d8924557](https://linux-hardware.org/?probe=a2d8924557) | Mar 21, 2020 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [4511e5932e](https://linux-hardware.org/?probe=4511e5932e) | Mar 21, 2020 |
| HP            | EliteBook x360 1040 G6      | Convertible | [917bcfb4a3](https://linux-hardware.org/?probe=917bcfb4a3) | Mar 21, 2020 |
| ASUSTek       | F3Sg                        | Notebook    | [149527329c](https://linux-hardware.org/?probe=149527329c) | Mar 20, 2020 |
| ASRock        | X570 Taichi                 | Desktop     | [c9edc06f7f](https://linux-hardware.org/?probe=c9edc06f7f) | Mar 20, 2020 |
| Medion        | B360H4-EM V1.0              | Desktop     | [f1f43e0def](https://linux-hardware.org/?probe=f1f43e0def) | Mar 20, 2020 |
| Unknown       | Unknown                     | Notebook    | [268c0d4b3e](https://linux-hardware.org/?probe=268c0d4b3e) | Mar 20, 2020 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [fd49842929](https://linux-hardware.org/?probe=fd49842929) | Mar 20, 2020 |
| HP            | Pavilion Notebook 15-bc5... | Notebook    | [b67aef950d](https://linux-hardware.org/?probe=b67aef950d) | Mar 19, 2020 |
| HP            | Pavilion Notebook 15-bc5... | Notebook    | [c2b75c6e1a](https://linux-hardware.org/?probe=c2b75c6e1a) | Mar 19, 2020 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [6b2513855e](https://linux-hardware.org/?probe=6b2513855e) | Mar 19, 2020 |
| HP            | Compaq 8510p                | Notebook    | [df003f9b94](https://linux-hardware.org/?probe=df003f9b94) | Mar 19, 2020 |
| HP            | Compaq 8510p                | Notebook    | [6a272fe91c](https://linux-hardware.org/?probe=6a272fe91c) | Mar 19, 2020 |
| HP            | Unknown                     | Notebook    | [0720ac35fc](https://linux-hardware.org/?probe=0720ac35fc) | Mar 19, 2020 |
| HP            | Pavilion Laptop 14-ce0xx... | Notebook    | [a351ec49d6](https://linux-hardware.org/?probe=a351ec49d6) | Mar 19, 2020 |
| HP            | Pavilion Laptop 14-ce0xx... | Notebook    | [824e8de596](https://linux-hardware.org/?probe=824e8de596) | Mar 19, 2020 |
| Dell          | Inspiron 1520               | Notebook    | [e603a6de90](https://linux-hardware.org/?probe=e603a6de90) | Mar 19, 2020 |
| HP            | G42                         | Notebook    | [81475e20fc](https://linux-hardware.org/?probe=81475e20fc) | Mar 19, 2020 |
| Lenovo        | ThinkPad L412 058542G       | Notebook    | [1bc705430b](https://linux-hardware.org/?probe=1bc705430b) | Mar 18, 2020 |
| HP            | Unknown                     | Notebook    | [7ebfd4d205](https://linux-hardware.org/?probe=7ebfd4d205) | Mar 18, 2020 |
| HP            | Pavilion tx1000             | Notebook    | [5f8a15817c](https://linux-hardware.org/?probe=5f8a15817c) | Mar 18, 2020 |
| HP            | Pavilion tx1000             | Notebook    | [76f5c62167](https://linux-hardware.org/?probe=76f5c62167) | Mar 18, 2020 |
| Toshiba       | Satellite L305              | Notebook    | [e3b6115f5e](https://linux-hardware.org/?probe=e3b6115f5e) | Mar 17, 2020 |
| Toshiba       | Satellite L305              | Notebook    | [7d2f3a78fe](https://linux-hardware.org/?probe=7d2f3a78fe) | Mar 17, 2020 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [b19ba42878](https://linux-hardware.org/?probe=b19ba42878) | Mar 17, 2020 |
| PCChips       | P49G                        | Desktop     | [1cedc0a4f7](https://linux-hardware.org/?probe=1cedc0a4f7) | Mar 17, 2020 |
| HP            | ProBook 640 G4              | Notebook    | [9240c255ae](https://linux-hardware.org/?probe=9240c255ae) | Mar 16, 2020 |
| MSI           | X470 GAMING PLUS            | Desktop     | [4396349f5a](https://linux-hardware.org/?probe=4396349f5a) | Mar 15, 2020 |
| Dell          | 0HN7XN A01                  | Desktop     | [867363eb66](https://linux-hardware.org/?probe=867363eb66) | Mar 15, 2020 |
| ASUSTek       | CM6850                      | Desktop     | [c1a5bcb59e](https://linux-hardware.org/?probe=c1a5bcb59e) | Mar 15, 2020 |
| Lenovo        | ThinkPad S3-S440 20AY00B... | Notebook    | [86e1d115b9](https://linux-hardware.org/?probe=86e1d115b9) | Mar 15, 2020 |
| Dell          | Inspiron 6000               | Notebook    | [e81704d568](https://linux-hardware.org/?probe=e81704d568) | Mar 15, 2020 |
| HP            | Pavilion dv9700             | Notebook    | [60bcd3ac92](https://linux-hardware.org/?probe=60bcd3ac92) | Mar 15, 2020 |
| Apple         | Mac-7BA5B2D9E42DDD94 iMa... | Desktop     | [b88416c7c1](https://linux-hardware.org/?probe=b88416c7c1) | Mar 15, 2020 |
| Apple         | Mac-7BA5B2D9E42DDD94 iMa... | Desktop     | [895855b3e7](https://linux-hardware.org/?probe=895855b3e7) | Mar 15, 2020 |
| ASUSTek       | IPN73-BA                    | Desktop     | [5efede21e2](https://linux-hardware.org/?probe=5efede21e2) | Mar 15, 2020 |
| Lenovo        | Y70-70 Touch 80DU           | Notebook    | [6ab7a0c0f5](https://linux-hardware.org/?probe=6ab7a0c0f5) | Mar 15, 2020 |
| ASUSTek       | CM6850                      | Desktop     | [1d8b5643fc](https://linux-hardware.org/?probe=1d8b5643fc) | Mar 15, 2020 |
| ASUSTek       | CM6850                      | Desktop     | [9574ecd632](https://linux-hardware.org/?probe=9574ecd632) | Mar 15, 2020 |
| Dell          | 0HN7XN A01                  | Desktop     | [9eef241af4](https://linux-hardware.org/?probe=9eef241af4) | Mar 14, 2020 |
| MSI           | X470 GAMING PLUS            | Desktop     | [0f3b67bbd0](https://linux-hardware.org/?probe=0f3b67bbd0) | Mar 14, 2020 |
| ASUSTek       | N750JK                      | Notebook    | [7b51fed304](https://linux-hardware.org/?probe=7b51fed304) | Mar 13, 2020 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [cf79468d97](https://linux-hardware.org/?probe=cf79468d97) | Mar 13, 2020 |
| Dell          | Inspiron 7560               | Notebook    | [bdfbbe481f](https://linux-hardware.org/?probe=bdfbbe481f) | Mar 13, 2020 |
| Acer          | Aspire E1-572G              | Notebook    | [cc8b5532c5](https://linux-hardware.org/?probe=cc8b5532c5) | Mar 12, 2020 |
| HP            | Pavilion dv7                | Notebook    | [61bbb3da8a](https://linux-hardware.org/?probe=61bbb3da8a) | Mar 12, 2020 |
| Acer          | Ferrari IV                  | Notebook    | [a1626355ea](https://linux-hardware.org/?probe=a1626355ea) | Mar 11, 2020 |
| Acer          | Ferrari IV                  | Notebook    | [fa404be8fd](https://linux-hardware.org/?probe=fa404be8fd) | Mar 11, 2020 |
| Dell          | Latitude E5440              | Notebook    | [7582be2134](https://linux-hardware.org/?probe=7582be2134) | Mar 11, 2020 |
| HP            | ProBook 4320s               | Notebook    | [92478c20d5](https://linux-hardware.org/?probe=92478c20d5) | Mar 11, 2020 |
| ASUSTek       | TAICHI21                    | Notebook    | [608a903011](https://linux-hardware.org/?probe=608a903011) | Mar 11, 2020 |
| Apple         | MacBookPro9,2               | Notebook    | [81823b3c54](https://linux-hardware.org/?probe=81823b3c54) | Mar 11, 2020 |
| Dell          | Latitude XT2                | Notebook    | [bf5cd05553](https://linux-hardware.org/?probe=bf5cd05553) | Mar 10, 2020 |
| Samsung       | N102                        | Notebook    | [40dba99330](https://linux-hardware.org/?probe=40dba99330) | Mar 10, 2020 |
| Pegatron      | DB                          | Desktop     | [20768d0e33](https://linux-hardware.org/?probe=20768d0e33) | Mar 10, 2020 |
| Apple         | MacBookPro9,2               | Notebook    | [ccde97eb8a](https://linux-hardware.org/?probe=ccde97eb8a) | Mar 10, 2020 |
| Apple         | MacBookPro9,2               | Notebook    | [289d3eb3d3](https://linux-hardware.org/?probe=289d3eb3d3) | Mar 10, 2020 |
| Positivo      | POS-EIBTDB                  | Desktop     | [31ea3af3e0](https://linux-hardware.org/?probe=31ea3af3e0) | Mar 10, 2020 |
| MSI           | MS-7135                     | Desktop     | [8379ec143c](https://linux-hardware.org/?probe=8379ec143c) | Mar 09, 2020 |
| MSI           | MS-7135                     | Desktop     | [50653703d8](https://linux-hardware.org/?probe=50653703d8) | Mar 09, 2020 |
| Acer          | Veriton X275                | Desktop     | [a19716bfc1](https://linux-hardware.org/?probe=a19716bfc1) | Mar 08, 2020 |
| Pegatron      | Benicia                     | Desktop     | [c27aa90095](https://linux-hardware.org/?probe=c27aa90095) | Mar 08, 2020 |
| MSI           | A320M PRO-M2 V2             | Desktop     | [51366f30d7](https://linux-hardware.org/?probe=51366f30d7) | Mar 08, 2020 |
| HP            | Compaq 615                  | Notebook    | [20f4720634](https://linux-hardware.org/?probe=20f4720634) | Mar 08, 2020 |
| Biostar       | N61PC-M2S                   | Desktop     | [d05836b07a](https://linux-hardware.org/?probe=d05836b07a) | Mar 08, 2020 |
| Dell          | Latitude E5440              | Notebook    | [a03a2405a2](https://linux-hardware.org/?probe=a03a2405a2) | Mar 08, 2020 |
| Lenovo        | ThinkPad T430s 23563RB      | Notebook    | [a011b81975](https://linux-hardware.org/?probe=a011b81975) | Mar 07, 2020 |
| Lenovo        | ThinkPad T430s 23563RB      | Notebook    | [8ce2fe5d52](https://linux-hardware.org/?probe=8ce2fe5d52) | Mar 07, 2020 |
| Gigabyte      | H61M-DS2                    | Desktop     | [22dd80e73e](https://linux-hardware.org/?probe=22dd80e73e) | Mar 07, 2020 |
| Biostar       | N61PC-M2S                   | Desktop     | [55cf072af6](https://linux-hardware.org/?probe=55cf072af6) | Mar 07, 2020 |
| HP            | 339B                        | Desktop     | [141457d68c](https://linux-hardware.org/?probe=141457d68c) | Mar 06, 2020 |
| HP            | 2B17                        | Desktop     | [af7f44cf00](https://linux-hardware.org/?probe=af7f44cf00) | Mar 06, 2020 |
| HP            | EliteBook 840 G2            | Notebook    | [b23a6cc526](https://linux-hardware.org/?probe=b23a6cc526) | Mar 06, 2020 |
| ASRock        | X570 Steel Legend           | Desktop     | [f591fd6f3d](https://linux-hardware.org/?probe=f591fd6f3d) | Mar 06, 2020 |
| Dixonsxp      | Unknown                     | Notebook    | [d51d943904](https://linux-hardware.org/?probe=d51d943904) | Mar 06, 2020 |
| HP            | 2B17                        | Desktop     | [d4b9f62257](https://linux-hardware.org/?probe=d4b9f62257) | Mar 05, 2020 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [e5d46d214b](https://linux-hardware.org/?probe=e5d46d214b) | Mar 05, 2020 |
| HP            | ProBook 4320s               | Notebook    | [96b40c5d0e](https://linux-hardware.org/?probe=96b40c5d0e) | Mar 05, 2020 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [ad88b9d524](https://linux-hardware.org/?probe=ad88b9d524) | Mar 04, 2020 |
| HP            | 339B                        | Desktop     | [2bc26d9a1c](https://linux-hardware.org/?probe=2bc26d9a1c) | Mar 03, 2020 |
| ASUSTek       | P5PE-VM                     | Desktop     | [d4016b39b4](https://linux-hardware.org/?probe=d4016b39b4) | Mar 03, 2020 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [b673427507](https://linux-hardware.org/?probe=b673427507) | Mar 03, 2020 |
| QDI           | P4I865MA                    | Desktop     | [14dd36d514](https://linux-hardware.org/?probe=14dd36d514) | Mar 02, 2020 |
| Dell          | 0N4YC8 A00                  | Desktop     | [f241cfd505](https://linux-hardware.org/?probe=f241cfd505) | Mar 02, 2020 |
| Google        | Gnawty                      | Notebook    | [6f3ac8ce74](https://linux-hardware.org/?probe=6f3ac8ce74) | Mar 01, 2020 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [5b1e502fce](https://linux-hardware.org/?probe=5b1e502fce) | Mar 01, 2020 |
| ASUSTek       | P4R800-VM                   | Desktop     | [a348387325](https://linux-hardware.org/?probe=a348387325) | Feb 29, 2020 |
| QDI           | P4I865MA                    | Desktop     | [abdbf93db4](https://linux-hardware.org/?probe=abdbf93db4) | Feb 29, 2020 |
| Gigabyte      | MZBAYAP-D9                  | Desktop     | [e53d3f792d](https://linux-hardware.org/?probe=e53d3f792d) | Feb 29, 2020 |
| ASUSTek       | P8H61                       | Desktop     | [5b28b44909](https://linux-hardware.org/?probe=5b28b44909) | Feb 28, 2020 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [e77a0a6719](https://linux-hardware.org/?probe=e77a0a6719) | Feb 27, 2020 |
| Fujitsu Si... | AMILO M1451G Series         | Notebook    | [ae442cc174](https://linux-hardware.org/?probe=ae442cc174) | Feb 26, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [9344a74aa9](https://linux-hardware.org/?probe=9344a74aa9) | Feb 26, 2020 |
| ASUSTek       | X555LD                      | Notebook    | [c3ba184dbb](https://linux-hardware.org/?probe=c3ba184dbb) | Feb 25, 2020 |
| Packard Be... | IMEDIA S3720                | Desktop     | [04ba71e930](https://linux-hardware.org/?probe=04ba71e930) | Feb 25, 2020 |
| Gigabyte      | M68MT-S2                    | Desktop     | [6a5c6cf0dc](https://linux-hardware.org/?probe=6a5c6cf0dc) | Feb 23, 2020 |
| HP            | EliteBook 840 G1            | Notebook    | [cd0a628cc6](https://linux-hardware.org/?probe=cd0a628cc6) | Feb 23, 2020 |
| HP            | Pavilion dm1                | Notebook    | [e4a08b8741](https://linux-hardware.org/?probe=e4a08b8741) | Feb 23, 2020 |
| ASUSTek       | CG8580                      | Desktop     | [a2755006be](https://linux-hardware.org/?probe=a2755006be) | Feb 22, 2020 |
| ASUSTek       | CG8580                      | Desktop     | [ca764ea79e](https://linux-hardware.org/?probe=ca764ea79e) | Feb 22, 2020 |
| Dell          | 0HY9JP A01                  | Desktop     | [ae0ada26bd](https://linux-hardware.org/?probe=ae0ada26bd) | Feb 22, 2020 |
| Google        | Enguarde                    | Notebook    | [1b6835ab9d](https://linux-hardware.org/?probe=1b6835ab9d) | Feb 21, 2020 |
| MSI           | B450 TOMAHAWK               | Desktop     | [e2be196dd3](https://linux-hardware.org/?probe=e2be196dd3) | Feb 21, 2020 |
| MSI           | B450 TOMAHAWK               | Desktop     | [0d6b91e4e1](https://linux-hardware.org/?probe=0d6b91e4e1) | Feb 21, 2020 |
| ASUSTek       | GX501VIK                    | Notebook    | [717e762d70](https://linux-hardware.org/?probe=717e762d70) | Feb 20, 2020 |
| Apple         | MacBook4,1                  | Notebook    | [4eb748a8df](https://linux-hardware.org/?probe=4eb748a8df) | Feb 20, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [b253180703](https://linux-hardware.org/?probe=b253180703) | Feb 20, 2020 |
| ASUSTek       | GX501VIK                    | Notebook    | [a8d5bc13f9](https://linux-hardware.org/?probe=a8d5bc13f9) | Feb 19, 2020 |
| HP            | 81BB                        | All in one  | [d13b8c6487](https://linux-hardware.org/?probe=d13b8c6487) | Feb 19, 2020 |
| ASRock        | H81M-ITX/WiFi               | Desktop     | [4b746c7d20](https://linux-hardware.org/?probe=4b746c7d20) | Feb 19, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [ad43873fae](https://linux-hardware.org/?probe=ad43873fae) | Feb 19, 2020 |
| HP            | ProBook 4530s               | Notebook    | [639dbf3714](https://linux-hardware.org/?probe=639dbf3714) | Feb 16, 2020 |
| Bak USA Te... | Atlas                       | Notebook    | [faa71e71eb](https://linux-hardware.org/?probe=faa71e71eb) | Feb 16, 2020 |
| ASUSTek       | A6Km                        | Notebook    | [674156522d](https://linux-hardware.org/?probe=674156522d) | Feb 16, 2020 |
| Pegatron      | Benicia                     | Desktop     | [607c001ed3](https://linux-hardware.org/?probe=607c001ed3) | Feb 16, 2020 |
| Bak USA Te... | Atlas                       | Notebook    | [4e1dd1b730](https://linux-hardware.org/?probe=4e1dd1b730) | Feb 14, 2020 |
| NEC Comput... | PC-VY25AACZ9                | Notebook    | [87e4d3dd9a](https://linux-hardware.org/?probe=87e4d3dd9a) | Feb 14, 2020 |
| Toshiba       | PORTEGE Z30-A               | Notebook    | [897030a5ea](https://linux-hardware.org/?probe=897030a5ea) | Feb 13, 2020 |
| ASUSTek       | H81M-A                      | Desktop     | [4267e74d14](https://linux-hardware.org/?probe=4267e74d14) | Feb 13, 2020 |
| Dell          | Vostro 3550                 | Notebook    | [edfe8875af](https://linux-hardware.org/?probe=edfe8875af) | Feb 12, 2020 |
| IBM           | ThinkPad T43 26688AG        | Notebook    | [ce6973ce12](https://linux-hardware.org/?probe=ce6973ce12) | Feb 12, 2020 |
| Toshiba       | Satellite L55-C             | Notebook    | [acebd8101e](https://linux-hardware.org/?probe=acebd8101e) | Feb 11, 2020 |
| Dell          | System Vostro 3750          | Notebook    | [73e23c8357](https://linux-hardware.org/?probe=73e23c8357) | Feb 11, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [91ba437052](https://linux-hardware.org/?probe=91ba437052) | Feb 11, 2020 |
| Toshiba       | PORTEGE Z30-A               | Notebook    | [8b26c24d93](https://linux-hardware.org/?probe=8b26c24d93) | Feb 11, 2020 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [24928e9fa8](https://linux-hardware.org/?probe=24928e9fa8) | Feb 11, 2020 |
| Gigabyte      | B450 AORUS M                | Desktop     | [40a6532cf5](https://linux-hardware.org/?probe=40a6532cf5) | Feb 10, 2020 |
| Alienware     | 06G6JW A00                  | Desktop     | [f3eab06bb2](https://linux-hardware.org/?probe=f3eab06bb2) | Feb 10, 2020 |
| ASUSTek       | E203NA                      | Notebook    | [09dbcdcddc](https://linux-hardware.org/?probe=09dbcdcddc) | Feb 10, 2020 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [d9fdcbf4d8](https://linux-hardware.org/?probe=d9fdcbf4d8) | Feb 10, 2020 |
| ASUSTek       | H61M-K                      | Desktop     | [2dfd7e9f59](https://linux-hardware.org/?probe=2dfd7e9f59) | Feb 10, 2020 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [7974f28802](https://linux-hardware.org/?probe=7974f28802) | Feb 08, 2020 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [e1cdb8a0fc](https://linux-hardware.org/?probe=e1cdb8a0fc) | Feb 08, 2020 |
| ASUSTek       | H81M-A                      | Desktop     | [d263970407](https://linux-hardware.org/?probe=d263970407) | Feb 07, 2020 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [10d5285055](https://linux-hardware.org/?probe=10d5285055) | Feb 07, 2020 |
| Dell          | 09KPNV A00                  | Desktop     | [a242b5b90b](https://linux-hardware.org/?probe=a242b5b90b) | Feb 07, 2020 |
| HP            | 81BB                        | All in one  | [6e9fce0a81](https://linux-hardware.org/?probe=6e9fce0a81) | Feb 06, 2020 |
| ASRock        | FM2A75M-HD+                 | Desktop     | [3fdebe8d22](https://linux-hardware.org/?probe=3fdebe8d22) | Feb 06, 2020 |
| Lenovo        | ThinkPad T440p 20ANCTO1W... | Notebook    | [d80811a73d](https://linux-hardware.org/?probe=d80811a73d) | Feb 05, 2020 |
| Lenovo        | G505 20240                  | Notebook    | [3208a023bf](https://linux-hardware.org/?probe=3208a023bf) | Feb 04, 2020 |
| Lenovo        | ThinkPad E550 20DF0040US    | Notebook    | [ce3ebef6dc](https://linux-hardware.org/?probe=ce3ebef6dc) | Feb 04, 2020 |
| HP            | 1998                        | Desktop     | [c2bdaa70cf](https://linux-hardware.org/?probe=c2bdaa70cf) | Feb 04, 2020 |
| Pegatron      | Benicia                     | Desktop     | [077bb98064](https://linux-hardware.org/?probe=077bb98064) | Feb 03, 2020 |
| HP            | 3648h                       | Desktop     | [5af75f8b5f](https://linux-hardware.org/?probe=5af75f8b5f) | Feb 03, 2020 |
| Dell          | 01V648 A03                  | Server      | [e1ff42ff0b](https://linux-hardware.org/?probe=e1ff42ff0b) | Feb 03, 2020 |
| Dell          | 01V648 A03                  | Server      | [ea45cdba76](https://linux-hardware.org/?probe=ea45cdba76) | Feb 03, 2020 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [e9238fd8ed](https://linux-hardware.org/?probe=e9238fd8ed) | Feb 03, 2020 |
| Acer          | H57M01                      | Desktop     | [19a293b841](https://linux-hardware.org/?probe=19a293b841) | Feb 03, 2020 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [d53f359250](https://linux-hardware.org/?probe=d53f359250) | Feb 02, 2020 |
| Gigabyte      | 945GCM-S2C                  | Desktop     | [7122f11c2e](https://linux-hardware.org/?probe=7122f11c2e) | Feb 02, 2020 |
| TrekStor      | Notebook Slim S130          | Notebook    | [e0e1b59385](https://linux-hardware.org/?probe=e0e1b59385) | Feb 01, 2020 |
| Acer          | Nitro AN515-42              | Notebook    | [a1d38e2afe](https://linux-hardware.org/?probe=a1d38e2afe) | Feb 01, 2020 |
| Acer          | Aspire 5735                 | Notebook    | [e517ff7dc7](https://linux-hardware.org/?probe=e517ff7dc7) | Jan 31, 2020 |
| HP            | Pavilion dv7                | Notebook    | [1359dd6ebc](https://linux-hardware.org/?probe=1359dd6ebc) | Jan 31, 2020 |
| Acer          | Aspire 5336                 | Notebook    | [7827c16291](https://linux-hardware.org/?probe=7827c16291) | Jan 30, 2020 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [fbdcd4fb9f](https://linux-hardware.org/?probe=fbdcd4fb9f) | Jan 30, 2020 |
| Pegatron      | Benicia                     | Desktop     | [7ad790ff7a](https://linux-hardware.org/?probe=7ad790ff7a) | Jan 29, 2020 |
| Dell          | 054KM3 A01                  | Desktop     | [857f976c7f](https://linux-hardware.org/?probe=857f976c7f) | Jan 29, 2020 |
| HP            | Pavilion dv6700             | Notebook    | [11b6b91acc](https://linux-hardware.org/?probe=11b6b91acc) | Jan 29, 2020 |
| Dell          | 0HY9JP A01                  | Desktop     | [3af780abb2](https://linux-hardware.org/?probe=3af780abb2) | Jan 29, 2020 |
| HP            | Compaq Presario CQ50        | Notebook    | [1e88106854](https://linux-hardware.org/?probe=1e88106854) | Jan 28, 2020 |
| HP            | ProBook 450 G1              | Notebook    | [7393534af1](https://linux-hardware.org/?probe=7393534af1) | Jan 26, 2020 |
| Lenovo        | IdeaPad Z400 Touch VIWZ1    | Notebook    | [7282fec433](https://linux-hardware.org/?probe=7282fec433) | Jan 26, 2020 |
| ASUSTek       | P-P5N9300                   | Desktop     | [aaf6fafad6](https://linux-hardware.org/?probe=aaf6fafad6) | Jan 25, 2020 |
| Toshiba       | Satellite L55-B             | Notebook    | [cbf62518f7](https://linux-hardware.org/?probe=cbf62518f7) | Jan 25, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [d84c64a7b4](https://linux-hardware.org/?probe=d84c64a7b4) | Jan 23, 2020 |
| Acer          | AOA150                      | Notebook    | [0b619b41c1](https://linux-hardware.org/?probe=0b619b41c1) | Jan 23, 2020 |
| HP            | 18E7                        | Desktop     | [de846e5f4f](https://linux-hardware.org/?probe=de846e5f4f) | Jan 22, 2020 |
| Lenovo        | IdeaPad N581 7505           | Notebook    | [2d053580c5](https://linux-hardware.org/?probe=2d053580c5) | Jan 22, 2020 |
| ASRock        | H110M-DGS                   | Desktop     | [e7b2bbeb81](https://linux-hardware.org/?probe=e7b2bbeb81) | Jan 21, 2020 |
| HP            | 09F0h                       | Desktop     | [bff6b4f556](https://linux-hardware.org/?probe=bff6b4f556) | Jan 21, 2020 |
| HP            | 09F0h                       | Desktop     | [ad09a9a9d4](https://linux-hardware.org/?probe=ad09a9a9d4) | Jan 21, 2020 |
| Dell          | 054KM3 A01                  | Desktop     | [f682ad8814](https://linux-hardware.org/?probe=f682ad8814) | Jan 21, 2020 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [5ad36ed47a](https://linux-hardware.org/?probe=5ad36ed47a) | Jan 21, 2020 |
| WinFast       | NF4UK8AA                    | Desktop     | [33bf094e83](https://linux-hardware.org/?probe=33bf094e83) | Jan 20, 2020 |
| Gigabyte      | H97M-D3H                    | Desktop     | [5766c0d32a](https://linux-hardware.org/?probe=5766c0d32a) | Jan 19, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [c20e4254c8](https://linux-hardware.org/?probe=c20e4254c8) | Jan 18, 2020 |
| HP            | Split 13 x2 Detachable P... | Notebook    | [508422072e](https://linux-hardware.org/?probe=508422072e) | Jan 17, 2020 |
| HP            | Split 13 x2 Detachable P... | Notebook    | [8ef1114860](https://linux-hardware.org/?probe=8ef1114860) | Jan 17, 2020 |
| Acer          | Switch SW312-31             | Tablet      | [005e499237](https://linux-hardware.org/?probe=005e499237) | Jan 16, 2020 |
| Acer          | Switch SW312-31             | Tablet      | [347194b1d7](https://linux-hardware.org/?probe=347194b1d7) | Jan 16, 2020 |
| Lenovo        | V155-15API 81V5             | Notebook    | [62d9f6fd7f](https://linux-hardware.org/?probe=62d9f6fd7f) | Jan 16, 2020 |
| Jetway        | 1.0                         | Desktop     | [c8c8069fef](https://linux-hardware.org/?probe=c8c8069fef) | Jan 16, 2020 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [c924cce6c4](https://linux-hardware.org/?probe=c924cce6c4) | Jan 16, 2020 |
| AMI           | Unknown                     | Notebook    | [4d89af9f9b](https://linux-hardware.org/?probe=4d89af9f9b) | Jan 16, 2020 |
| AMI           | Cherry Trail CR             | Mini pc     | [6055b5511f](https://linux-hardware.org/?probe=6055b5511f) | Jan 15, 2020 |
| Acer          | AOA150                      | Notebook    | [94fa7756d5](https://linux-hardware.org/?probe=94fa7756d5) | Jan 15, 2020 |
| Toshiba       | Satellite L55-B             | Notebook    | [67b00cee9e](https://linux-hardware.org/?probe=67b00cee9e) | Jan 15, 2020 |
| ASUSTek       | P5B                         | Desktop     | [149a63defe](https://linux-hardware.org/?probe=149a63defe) | Jan 15, 2020 |
| Acer          | Aspire 5750                 | Notebook    | [b4b48d57a5](https://linux-hardware.org/?probe=b4b48d57a5) | Jan 15, 2020 |
| HP            | 1495                        | Desktop     | [25dd45a7d1](https://linux-hardware.org/?probe=25dd45a7d1) | Jan 15, 2020 |
| HP            | 1495                        | Desktop     | [c46d3b66fb](https://linux-hardware.org/?probe=c46d3b66fb) | Jan 15, 2020 |
| Gigabyte      | B250-HD3-CF                 | Desktop     | [c228f44226](https://linux-hardware.org/?probe=c228f44226) | Jan 14, 2020 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | Notebook    | [db6935033e](https://linux-hardware.org/?probe=db6935033e) | Jan 11, 2020 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | Notebook    | [c0265e0fd2](https://linux-hardware.org/?probe=c0265e0fd2) | Jan 11, 2020 |
| Gigabyte      | P55A-UD3                    | Desktop     | [7168fd0137](https://linux-hardware.org/?probe=7168fd0137) | Jan 11, 2020 |
| Gigabyte      | H97M-D3H                    | Desktop     | [7e39118627](https://linux-hardware.org/?probe=7e39118627) | Jan 11, 2020 |
| WinFast       | 761GXK8MC                   | Desktop     | [38fd9cb386](https://linux-hardware.org/?probe=38fd9cb386) | Jan 10, 2020 |
| Samsung       | R710                        | Notebook    | [f9cd84fa75](https://linux-hardware.org/?probe=f9cd84fa75) | Jan 10, 2020 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [674bcbab06](https://linux-hardware.org/?probe=674bcbab06) | Jan 08, 2020 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [6f7553f71d](https://linux-hardware.org/?probe=6f7553f71d) | Jan 08, 2020 |
| Lenovo        | ThinkCentre M71z 1761E3U    | Desktop     | [bc8e3cec2f](https://linux-hardware.org/?probe=bc8e3cec2f) | Jan 07, 2020 |
| Packard Be... | EasyNote MH36               | Notebook    | [ce56ea59c0](https://linux-hardware.org/?probe=ce56ea59c0) | Jan 06, 2020 |
| Packard Be... | EasyNote MH35               | Notebook    | [219fd394d3](https://linux-hardware.org/?probe=219fd394d3) | Jan 06, 2020 |
| Packard Be... | EasyNote MH35               | Notebook    | [c686755748](https://linux-hardware.org/?probe=c686755748) | Jan 06, 2020 |
| ECS           | P4M800-M                    | Desktop     | [caab4a3b82](https://linux-hardware.org/?probe=caab4a3b82) | Jan 06, 2020 |
| Acer          | Aspire 4752                 | Notebook    | [4e0f6ed499](https://linux-hardware.org/?probe=4e0f6ed499) | Jan 05, 2020 |
| Acer          | Aspire 4752                 | Notebook    | [ef80f122b5](https://linux-hardware.org/?probe=ef80f122b5) | Jan 05, 2020 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [53f1ac9906](https://linux-hardware.org/?probe=53f1ac9906) | Jan 04, 2020 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [ecf6141388](https://linux-hardware.org/?probe=ecf6141388) | Jan 02, 2020 |
| Toshiba       | Satellite A215              | Notebook    | [47dcd6e7bf](https://linux-hardware.org/?probe=47dcd6e7bf) | Jan 02, 2020 |
| Toshiba       | Satellite A215              | Notebook    | [746c66b8c6](https://linux-hardware.org/?probe=746c66b8c6) | Jan 02, 2020 |
| HP            | Laptop 15-bw0xx             | Notebook    | [defb99f1cc](https://linux-hardware.org/?probe=defb99f1cc) | Jan 01, 2020 |
| Packard Be... | EasyNote TJ65               | Notebook    | [11c8b385a6](https://linux-hardware.org/?probe=11c8b385a6) | Jan 01, 2020 |
| Dell          | Latitude E6420              | Notebook    | [22ac950018](https://linux-hardware.org/?probe=22ac950018) | Dec 31, 2019 |
| Dell          | Latitude E6420              | Notebook    | [c0dcaf12d6](https://linux-hardware.org/?probe=c0dcaf12d6) | Dec 31, 2019 |
| MSI           | MS-7010                     | Desktop     | [d74ae7fdf2](https://linux-hardware.org/?probe=d74ae7fdf2) | Dec 31, 2019 |
| Lenovo        | V155-15API 81V5             | Notebook    | [c379f2d81b](https://linux-hardware.org/?probe=c379f2d81b) | Dec 31, 2019 |
| Fujitsu       | D3223-C1 S26361-D3223-C1    | Desktop     | [18674d7b06](https://linux-hardware.org/?probe=18674d7b06) | Dec 31, 2019 |
| Dell          | Latitude E6420              | Notebook    | [57a24730d1](https://linux-hardware.org/?probe=57a24730d1) | Dec 31, 2019 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [561a2b1118](https://linux-hardware.org/?probe=561a2b1118) | Dec 31, 2019 |
| Packard Be... | EasyNote MH36               | Notebook    | [2acbacb783](https://linux-hardware.org/?probe=2acbacb783) | Dec 30, 2019 |
| Dell          | Latitude D630               | Notebook    | [aa6eee7a18](https://linux-hardware.org/?probe=aa6eee7a18) | Dec 30, 2019 |
| ASRock        | H81M-ITX/WiFi               | Desktop     | [b4fc494391](https://linux-hardware.org/?probe=b4fc494391) | Dec 30, 2019 |
| Dell          | 088DT1 A01                  | Desktop     | [097005061e](https://linux-hardware.org/?probe=097005061e) | Dec 30, 2019 |
| MSI           | GT70                        | Notebook    | [c86693c4ea](https://linux-hardware.org/?probe=c86693c4ea) | Dec 29, 2019 |
| NEC Comput... | PC-LC900HJ                  | Notebook    | [76bec35362](https://linux-hardware.org/?probe=76bec35362) | Dec 29, 2019 |
| HP            | Presario F500 (GL935UA#A... | Notebook    | [974afae9cf](https://linux-hardware.org/?probe=974afae9cf) | Dec 27, 2019 |
| Toshiba       | Satellite L775D             | Notebook    | [936a9682fa](https://linux-hardware.org/?probe=936a9682fa) | Dec 27, 2019 |
| Dell          | Inspiron 5566               | Notebook    | [f0139b5341](https://linux-hardware.org/?probe=f0139b5341) | Dec 26, 2019 |
| Intel         | DQ45CB AAE30148-303         | Desktop     | [4e93b3e62b](https://linux-hardware.org/?probe=4e93b3e62b) | Dec 26, 2019 |
| Dell          | Latitude E6530              | Notebook    | [813731ab25](https://linux-hardware.org/?probe=813731ab25) | Dec 26, 2019 |
| Lenovo        | V155-15API 81V5             | Notebook    | [8a74f889ca](https://linux-hardware.org/?probe=8a74f889ca) | Dec 26, 2019 |
| Dell          | Latitude E6530              | Notebook    | [e27a23f80b](https://linux-hardware.org/?probe=e27a23f80b) | Dec 24, 2019 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [49bc4a3291](https://linux-hardware.org/?probe=49bc4a3291) | Dec 24, 2019 |
| Acer          | Veriton M275                | Desktop     | [4795bf2a94](https://linux-hardware.org/?probe=4795bf2a94) | Dec 24, 2019 |
| HP            | EliteBook 2540p             | Notebook    | [4663deb0dd](https://linux-hardware.org/?probe=4663deb0dd) | Dec 23, 2019 |
| Unknown       | Unknown                     | Notebook    | [ebb7e1b084](https://linux-hardware.org/?probe=ebb7e1b084) | Dec 22, 2019 |
| AMI           | Cherry Trail FFD            | Notebook    | [c62d47b2a1](https://linux-hardware.org/?probe=c62d47b2a1) | Dec 22, 2019 |
| Unknown       | Unknown                     | Notebook    | [a0cdc78762](https://linux-hardware.org/?probe=a0cdc78762) | Dec 22, 2019 |
| HP            | Laptop 15-db0xxx            | Notebook    | [3b491b92b3](https://linux-hardware.org/?probe=3b491b92b3) | Dec 21, 2019 |
| HP            | EliteBook 2760p             | Notebook    | [6d298da4a5](https://linux-hardware.org/?probe=6d298da4a5) | Dec 20, 2019 |
| Dell          | Latitude E5420              | Notebook    | [4673399116](https://linux-hardware.org/?probe=4673399116) | Dec 19, 2019 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [b276e5aad5](https://linux-hardware.org/?probe=b276e5aad5) | Dec 19, 2019 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [67bbeb29a4](https://linux-hardware.org/?probe=67bbeb29a4) | Dec 19, 2019 |
| Fujitsu       | D3223-C1 S26361-D3223-C1    | Desktop     | [84669a36b5](https://linux-hardware.org/?probe=84669a36b5) | Dec 18, 2019 |
| Fujitsu       | D3223-C1 S26361-D3223-C1    | Desktop     | [e87c9c3d58](https://linux-hardware.org/?probe=e87c9c3d58) | Dec 18, 2019 |
| Dell          | Inspiron 7520               | Notebook    | [e5cda35a9a](https://linux-hardware.org/?probe=e5cda35a9a) | Dec 16, 2019 |
| Dell          | Latitude E6430              | Notebook    | [39d47c0f09](https://linux-hardware.org/?probe=39d47c0f09) | Dec 16, 2019 |
| Minix         | NEO Z83-4 V1.1              | Notebook    | [c298c38fa6](https://linux-hardware.org/?probe=c298c38fa6) | Dec 16, 2019 |
| HP            | EliteBook 2760p             | Notebook    | [6ca3976164](https://linux-hardware.org/?probe=6ca3976164) | Dec 16, 2019 |
| Multilaser    | PC024                       | Tablet      | [8847fa9fcb](https://linux-hardware.org/?probe=8847fa9fcb) | Dec 16, 2019 |
| Minix         | NEO Z83-4 V1.1              | Notebook    | [8de9a4ef47](https://linux-hardware.org/?probe=8de9a4ef47) | Dec 15, 2019 |
| HP            | Compaq nc6220 (PL814AV)     | Notebook    | [a770cf025e](https://linux-hardware.org/?probe=a770cf025e) | Dec 15, 2019 |
| WinFast       | 761GXK8MC                   | Desktop     | [e819949ecb](https://linux-hardware.org/?probe=e819949ecb) | Dec 14, 2019 |
| WinFast       | 761GXK8MC                   | Desktop     | [e40339b238](https://linux-hardware.org/?probe=e40339b238) | Dec 14, 2019 |
| ASUSTek       | ZenBook Pro 15 UX550GDX_... | Notebook    | [f4689330d7](https://linux-hardware.org/?probe=f4689330d7) | Dec 14, 2019 |
| Acer          | Aspire ES1-531              | Notebook    | [0949108352](https://linux-hardware.org/?probe=0949108352) | Dec 14, 2019 |
| ASUSTek       | ZenBook Pro 15 UX550GDX_... | Notebook    | [d651477524](https://linux-hardware.org/?probe=d651477524) | Dec 14, 2019 |
| Dell          | 0M858N A00                  | Desktop     | [b532d7e443](https://linux-hardware.org/?probe=b532d7e443) | Dec 14, 2019 |
| Dell          | Latitude E6430              | Notebook    | [65ccc430a7](https://linux-hardware.org/?probe=65ccc430a7) | Dec 14, 2019 |
| Lenovo        | IdeaPad Z400 Touch VIWZ1    | Notebook    | [7c53a00cb0](https://linux-hardware.org/?probe=7c53a00cb0) | Dec 12, 2019 |
| Lenovo        | IdeaPad Z400 Touch VIWZ1    | Notebook    | [4b9dba4d4a](https://linux-hardware.org/?probe=4b9dba4d4a) | Dec 12, 2019 |
| NEC Comput... | PC-VY25AACZ9                | Notebook    | [67db0cd3e1](https://linux-hardware.org/?probe=67db0cd3e1) | Dec 12, 2019 |
| MSI           | GT72 2PC                    | Notebook    | [dbe1269ea7](https://linux-hardware.org/?probe=dbe1269ea7) | Dec 11, 2019 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [2c0e1e641e](https://linux-hardware.org/?probe=2c0e1e641e) | Dec 11, 2019 |
| Dell          | 0VNP2H A01                  | Desktop     | [fac164e5f3](https://linux-hardware.org/?probe=fac164e5f3) | Dec 11, 2019 |
| Gigabyte      | GA-73PVM-S2H                | Desktop     | [8996cebf5b](https://linux-hardware.org/?probe=8996cebf5b) | Dec 10, 2019 |
| MSI           | GL62M 7RDX                  | Notebook    | [b8aa5ef26c](https://linux-hardware.org/?probe=b8aa5ef26c) | Dec 09, 2019 |
| MSI           | GL62M 7RDX                  | Notebook    | [9c863ea710](https://linux-hardware.org/?probe=9c863ea710) | Dec 09, 2019 |
| ASUSTek       | W2P                         | Notebook    | [bae8402d0d](https://linux-hardware.org/?probe=bae8402d0d) | Dec 08, 2019 |
| ASRock        | B450M Pro4                  | Desktop     | [a7df8a79e0](https://linux-hardware.org/?probe=a7df8a79e0) | Dec 08, 2019 |
| Dell          | 0M858N A00                  | Desktop     | [a74908ee91](https://linux-hardware.org/?probe=a74908ee91) | Dec 06, 2019 |
| Dell          | 0M858N A00                  | Desktop     | [dc458be8fe](https://linux-hardware.org/?probe=dc458be8fe) | Dec 05, 2019 |
| Gigabyte      | GA-73PVM-S2H                | Desktop     | [9f1614f7fa](https://linux-hardware.org/?probe=9f1614f7fa) | Dec 05, 2019 |
| ASUSTek       | 1001PX                      | Notebook    | [e368a28816](https://linux-hardware.org/?probe=e368a28816) | Dec 04, 2019 |
| Dell          | Studio 1735                 | Notebook    | [586b67318a](https://linux-hardware.org/?probe=586b67318a) | Dec 03, 2019 |
| Dell          | Studio 1735                 | Notebook    | [b90b1732fc](https://linux-hardware.org/?probe=b90b1732fc) | Dec 03, 2019 |
| BQ            | Tesla2 W10                  | Notebook    | [d404a738dc](https://linux-hardware.org/?probe=d404a738dc) | Dec 03, 2019 |
| ASUSTek       | X550CC                      | Notebook    | [b2fb796fab](https://linux-hardware.org/?probe=b2fb796fab) | Dec 03, 2019 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [5b4aff6fe8](https://linux-hardware.org/?probe=5b4aff6fe8) | Dec 03, 2019 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [abeaa01348](https://linux-hardware.org/?probe=abeaa01348) | Dec 03, 2019 |
| HP            | EliteBook 6930p             | Notebook    | [94af8c86b1](https://linux-hardware.org/?probe=94af8c86b1) | Dec 03, 2019 |
| Dell          | Inspiron 15-3567            | Notebook    | [f952dc6f5d](https://linux-hardware.org/?probe=f952dc6f5d) | Dec 03, 2019 |
| Unknown       | Unknown                     | Notebook    | [8b11eb98d3](https://linux-hardware.org/?probe=8b11eb98d3) | Dec 02, 2019 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [6bd7363656](https://linux-hardware.org/?probe=6bd7363656) | Nov 30, 2019 |
| Unknown       | Unknown                     | Notebook    | [cd4af41624](https://linux-hardware.org/?probe=cd4af41624) | Nov 30, 2019 |
| ASUSTek       | 1000H                       | Notebook    | [22b31ccf0f](https://linux-hardware.org/?probe=22b31ccf0f) | Nov 29, 2019 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [44a360aef9](https://linux-hardware.org/?probe=44a360aef9) | Nov 28, 2019 |
| Gigabyte      | F2A55M-HD2                  | Desktop     | [3b1818c06c](https://linux-hardware.org/?probe=3b1818c06c) | Nov 26, 2019 |
| Gigabyte      | GA-MA74GMT-S2               | Desktop     | [6f2de6cd54](https://linux-hardware.org/?probe=6f2de6cd54) | Nov 26, 2019 |
| HP            | Pavilion dv6                | Notebook    | [fdc46ce1cd](https://linux-hardware.org/?probe=fdc46ce1cd) | Nov 26, 2019 |
| Gigabyte      | F2A55M-HD2                  | Desktop     | [f9a2a4d6ba](https://linux-hardware.org/?probe=f9a2a4d6ba) | Nov 26, 2019 |
| Dell          | Latitude E6540              | Notebook    | [25a99fe356](https://linux-hardware.org/?probe=25a99fe356) | Nov 25, 2019 |
| Dell          | Latitude E6540              | Notebook    | [fab2125ce9](https://linux-hardware.org/?probe=fab2125ce9) | Nov 25, 2019 |
| Gigabyte      | Z97-HD3                     | Desktop     | [3e770677b5](https://linux-hardware.org/?probe=3e770677b5) | Nov 24, 2019 |
| Apple         | MacBookPro11,1              | Notebook    | [25987883b0](https://linux-hardware.org/?probe=25987883b0) | Nov 24, 2019 |
| Gigabyte      | Z97-HD3                     | Desktop     | [0a954db5ed](https://linux-hardware.org/?probe=0a954db5ed) | Nov 24, 2019 |
| Dell          | Latitude E6520              | Notebook    | [4384225066](https://linux-hardware.org/?probe=4384225066) | Nov 21, 2019 |
| Compal        | Unknown                     | Notebook    | [718c425aa1](https://linux-hardware.org/?probe=718c425aa1) | Nov 19, 2019 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [ddc989eb17](https://linux-hardware.org/?probe=ddc989eb17) | Nov 16, 2019 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [df6bcc4167](https://linux-hardware.org/?probe=df6bcc4167) | Nov 16, 2019 |
| Medion        | S6421 MD60702               | Notebook    | [b2abbfcf51](https://linux-hardware.org/?probe=b2abbfcf51) | Nov 16, 2019 |
| Dell          | Latitude E6520              | Notebook    | [5f41cfdbb1](https://linux-hardware.org/?probe=5f41cfdbb1) | Nov 16, 2019 |
| Gigabyte      | GA-73PVM-S2H                | Desktop     | [6b8473d21f](https://linux-hardware.org/?probe=6b8473d21f) | Nov 15, 2019 |
| Lenovo        | G710 20252                  | Notebook    | [d11fbec88a](https://linux-hardware.org/?probe=d11fbec88a) | Nov 14, 2019 |
| Lenovo        | Yoga 720-13IKB 80X6         | Convertible | [1681edb0f6](https://linux-hardware.org/?probe=1681edb0f6) | Nov 13, 2019 |
| ASUSTek       | B9440UA                     | Notebook    | [7f6afd4c6b](https://linux-hardware.org/?probe=7f6afd4c6b) | Nov 13, 2019 |
| ASUSTek       | B9440UA                     | Notebook    | [370c185f25](https://linux-hardware.org/?probe=370c185f25) | Nov 13, 2019 |
| HP            | ProLiant ML350 G6           | Desktop     | [8e0c4f7db2](https://linux-hardware.org/?probe=8e0c4f7db2) | Nov 13, 2019 |
| HP            | ProLiant ML350 G6           | Desktop     | [05c451c685](https://linux-hardware.org/?probe=05c451c685) | Nov 12, 2019 |
| Dell          | 0DT031 A00                  | Desktop     | [44936a50a7](https://linux-hardware.org/?probe=44936a50a7) | Nov 11, 2019 |
| ASUSTek       | B9440UA                     | Notebook    | [79c10ef42c](https://linux-hardware.org/?probe=79c10ef42c) | Nov 11, 2019 |
| Alienware     | M14xR1                      | Notebook    | [8be5b82b62](https://linux-hardware.org/?probe=8be5b82b62) | Nov 10, 2019 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [bc49d0b842](https://linux-hardware.org/?probe=bc49d0b842) | Nov 10, 2019 |
| Lenovo        | G710 20252                  | Notebook    | [21ae1ec676](https://linux-hardware.org/?probe=21ae1ec676) | Nov 10, 2019 |
| ASUSTek       | M4A88TD-M EVO               | Desktop     | [891f7e03d0](https://linux-hardware.org/?probe=891f7e03d0) | Nov 10, 2019 |
| HP            | ProBook 6470b               | Notebook    | [ef310ee8d7](https://linux-hardware.org/?probe=ef310ee8d7) | Nov 09, 2019 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | Notebook    | [e3a70e566b](https://linux-hardware.org/?probe=e3a70e566b) | Nov 07, 2019 |
| Intel         | DQ57TM AAE70931-404         | Desktop     | [3c5baf94f5](https://linux-hardware.org/?probe=3c5baf94f5) | Nov 07, 2019 |
| ASUSTek       | NODUSM3                     | Desktop     | [32f7f650b9](https://linux-hardware.org/?probe=32f7f650b9) | Nov 05, 2019 |
| ASUSTek       | M4A88TD-M EVO               | Desktop     | [953835fc09](https://linux-hardware.org/?probe=953835fc09) | Nov 03, 2019 |
| ASRock        | A55M-HVS                    | Desktop     | [c63b9d3831](https://linux-hardware.org/?probe=c63b9d3831) | Nov 01, 2019 |
| HP            | 2215                        | Desktop     | [46b03d239a](https://linux-hardware.org/?probe=46b03d239a) | Oct 30, 2019 |
| ASUSTek       | M4A88TD-M EVO               | Desktop     | [2e459a054e](https://linux-hardware.org/?probe=2e459a054e) | Oct 30, 2019 |
| ASUSTek       | M4A88TD-M EVO               | Desktop     | [adfe27a574](https://linux-hardware.org/?probe=adfe27a574) | Oct 30, 2019 |
| ASUSTek       | NODUSM3                     | Desktop     | [a4bfdf316c](https://linux-hardware.org/?probe=a4bfdf316c) | Oct 24, 2019 |
| HP            | 09F0h                       | Desktop     | [416d2a031d](https://linux-hardware.org/?probe=416d2a031d) | Oct 24, 2019 |
| Sony          | VPCZ227GG                   | Notebook    | [6e74a95929](https://linux-hardware.org/?probe=6e74a95929) | Oct 23, 2019 |
| HP            | 15                          | Notebook    | [918baa5980](https://linux-hardware.org/?probe=918baa5980) | Oct 22, 2019 |
| Lenovo        | G550 2958                   | Notebook    | [7a2714efe5](https://linux-hardware.org/?probe=7a2714efe5) | Oct 21, 2019 |
| Acer          | Makalu                      | Notebook    | [00dd5c3407](https://linux-hardware.org/?probe=00dd5c3407) | Oct 19, 2019 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [460d3c193d](https://linux-hardware.org/?probe=460d3c193d) | Oct 18, 2019 |
| AMI           | Cherry Trail CR             | Notebook    | [b0d2ba14cc](https://linux-hardware.org/?probe=b0d2ba14cc) | Oct 17, 2019 |
| AMI           | Cherry Trail CR             | Notebook    | [0a982341da](https://linux-hardware.org/?probe=0a982341da) | Oct 15, 2019 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [a605c98275](https://linux-hardware.org/?probe=a605c98275) | Oct 13, 2019 |
| Toshiba       | Satellite A210              | Notebook    | [afeba73834](https://linux-hardware.org/?probe=afeba73834) | Oct 12, 2019 |
| Dell          | Latitude E6430              | Notebook    | [eb05a0d70d](https://linux-hardware.org/?probe=eb05a0d70d) | Oct 11, 2019 |
| Dell          | Latitude E6430              | Notebook    | [35e84bfd49](https://linux-hardware.org/?probe=35e84bfd49) | Oct 11, 2019 |
| ECS           | A785GM-AD3                  | Desktop     | [69dee2c465](https://linux-hardware.org/?probe=69dee2c465) | Oct 10, 2019 |
| Pegatron      | Benicia                     | Desktop     | [4b4babe809](https://linux-hardware.org/?probe=4b4babe809) | Oct 09, 2019 |
| Toshiba       | Satellite L845              | Notebook    | [f39187603d](https://linux-hardware.org/?probe=f39187603d) | Oct 09, 2019 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [ce2e3ad9ae](https://linux-hardware.org/?probe=ce2e3ad9ae) | Oct 08, 2019 |
| HP            | ProBook 450 G2              | Notebook    | [b87761d1c1](https://linux-hardware.org/?probe=b87761d1c1) | Oct 07, 2019 |
| HP            | 3397                        | Desktop     | [ec39b3f48a](https://linux-hardware.org/?probe=ec39b3f48a) | Sep 27, 2019 |
| HP            | EliteBook 8560p             | Notebook    | [ea58ac738c](https://linux-hardware.org/?probe=ea58ac738c) | Sep 25, 2019 |
| Toshiba       | Satellite A210              | Notebook    | [8017271f37](https://linux-hardware.org/?probe=8017271f37) | Sep 21, 2019 |
| ASUSTek       | M4A78-VM                    | Desktop     | [fc5bd8749b](https://linux-hardware.org/?probe=fc5bd8749b) | Sep 17, 2019 |
| Alienware     | M14xR2                      | Notebook    | [6bf9694a56](https://linux-hardware.org/?probe=6bf9694a56) | Sep 17, 2019 |
| HP            | ProBook 640 G2              | Notebook    | [c4ee36c621](https://linux-hardware.org/?probe=c4ee36c621) | Sep 15, 2019 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | Desktop     | [e8a0b17de8](https://linux-hardware.org/?probe=e8a0b17de8) | Sep 13, 2019 |
| ASRock        | Q1900-ITX                   | Desktop     | [fbffb61b86](https://linux-hardware.org/?probe=fbffb61b86) | Sep 10, 2019 |
| ASRock        | Q1900-ITX                   | Desktop     | [f683158983](https://linux-hardware.org/?probe=f683158983) | Sep 10, 2019 |
| HP            | 630                         | Notebook    | [8cb4c328bb](https://linux-hardware.org/?probe=8cb4c328bb) | Sep 10, 2019 |
| ASUSTek       | H81-PLUS                    | Desktop     | [d185f00f05](https://linux-hardware.org/?probe=d185f00f05) | Sep 08, 2019 |
| Lenovo        | Z50-70 20354                | Notebook    | [93800ed65a](https://linux-hardware.org/?probe=93800ed65a) | Sep 06, 2019 |
| Lenovo        | Edge 2-1580 80QF            | Notebook    | [b1950e5bff](https://linux-hardware.org/?probe=b1950e5bff) | Sep 04, 2019 |
| Purism        | Librem 13 v2                | Notebook    | [fa805c25c3](https://linux-hardware.org/?probe=fa805c25c3) | Aug 31, 2019 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [2a2ba2584f](https://linux-hardware.org/?probe=2a2ba2584f) | Aug 30, 2019 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [be1d448db2](https://linux-hardware.org/?probe=be1d448db2) | Aug 30, 2019 |
| Positivo      | Mobile                      | Notebook    | [7ceaddd485](https://linux-hardware.org/?probe=7ceaddd485) | Aug 29, 2019 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [6821f97b7e](https://linux-hardware.org/?probe=6821f97b7e) | Aug 28, 2019 |
| Dell          | Latitude E5470              | Notebook    | [0652d6a102](https://linux-hardware.org/?probe=0652d6a102) | Aug 26, 2019 |
| Apple         | Mac-F2218FC8                | All in one  | [f633253277](https://linux-hardware.org/?probe=f633253277) | Aug 23, 2019 |
| Dell          | 0D28YY A00                  | Desktop     | [7a405e7455](https://linux-hardware.org/?probe=7a405e7455) | Aug 22, 2019 |
| HP            | 15                          | Notebook    | [9bafe7cbbc](https://linux-hardware.org/?probe=9bafe7cbbc) | Aug 21, 2019 |
| Acer          | Nitro AN515-42              | Notebook    | [c5d12ef3a9](https://linux-hardware.org/?probe=c5d12ef3a9) | Aug 21, 2019 |
| Lenovo        | IdeaPad Z570 10243VU        | Notebook    | [b668fbf73f](https://linux-hardware.org/?probe=b668fbf73f) | Aug 20, 2019 |
| ASRock        | X470 Taichi                 | Desktop     | [b05236c1f1](https://linux-hardware.org/?probe=b05236c1f1) | Aug 19, 2019 |
| Intel         | DX58SO2 AAG10925-207        | Desktop     | [a71ec70bc8](https://linux-hardware.org/?probe=a71ec70bc8) | Aug 18, 2019 |
| Panasonic     | CF-SX2JDQZF5                | Notebook    | [6986c9f2d2](https://linux-hardware.org/?probe=6986c9f2d2) | Aug 17, 2019 |
| ASUSTek       | Rampage Formula             | Desktop     | [35ad6a34c0](https://linux-hardware.org/?probe=35ad6a34c0) | Aug 16, 2019 |
| Dell          | Latitude E6410              | Notebook    | [1ab976aaff](https://linux-hardware.org/?probe=1ab976aaff) | Aug 15, 2019 |
| Toshiba       | Satellite E45t-B            | Notebook    | [156d965d57](https://linux-hardware.org/?probe=156d965d57) | Aug 14, 2019 |
| HP            | 0A5Ch                       | Desktop     | [7bffd403ae](https://linux-hardware.org/?probe=7bffd403ae) | Aug 13, 2019 |
| HP            | 3085B                       | Notebook    | [eeb9f3af7f](https://linux-hardware.org/?probe=eeb9f3af7f) | Aug 11, 2019 |
| Panasonic     | CF-191FYC51M                | Notebook    | [beedf64235](https://linux-hardware.org/?probe=beedf64235) | Aug 11, 2019 |
| Panasonic     | CF-191FYC51M                | Notebook    | [77a0f7454e](https://linux-hardware.org/?probe=77a0f7454e) | Aug 11, 2019 |
| Dell          | Studio XPS 1640             | Notebook    | [549588a8f2](https://linux-hardware.org/?probe=549588a8f2) | Aug 10, 2019 |
| ASUSTek       | P8Z68-V PRO GEN3            | Desktop     | [a6b3b6fb45](https://linux-hardware.org/?probe=a6b3b6fb45) | Aug 10, 2019 |
| ASUSTek       | P8Z68-V PRO GEN3            | Desktop     | [f8eb77cd0b](https://linux-hardware.org/?probe=f8eb77cd0b) | Aug 10, 2019 |
| ASUSTek       | P8Z68-V PRO GEN3            | Desktop     | [b1e1f405be](https://linux-hardware.org/?probe=b1e1f405be) | Aug 10, 2019 |
| ASUSTek       | P8Z68-V PRO GEN3            | Desktop     | [1751775bc6](https://linux-hardware.org/?probe=1751775bc6) | Aug 09, 2019 |
| Acer          | Aspire E1-571               | Notebook    | [16eca8b913](https://linux-hardware.org/?probe=16eca8b913) | Aug 09, 2019 |
| ASUSTek       | P8Z68-V PRO GEN3            | Desktop     | [a37487a77b](https://linux-hardware.org/?probe=a37487a77b) | Aug 09, 2019 |
| Dell          | 0RK936                      | Desktop     | [060c60558b](https://linux-hardware.org/?probe=060c60558b) | Aug 08, 2019 |
| Sony          | VPCEH17FG                   | Notebook    | [68a12a9dfa](https://linux-hardware.org/?probe=68a12a9dfa) | Aug 08, 2019 |
| Sony          | VPCEH17FG                   | Notebook    | [f5b54a27c8](https://linux-hardware.org/?probe=f5b54a27c8) | Aug 08, 2019 |
| Lenovo        | Bantry CRB SDK0J40709 WI... | Desktop     | [0d36c8246a](https://linux-hardware.org/?probe=0d36c8246a) | Aug 06, 2019 |
| Lenovo        | ThinkPad T460s 20FAS3J30... | Notebook    | [9ffffef6da](https://linux-hardware.org/?probe=9ffffef6da) | Aug 06, 2019 |
| Ematic        | EWT147                      | Notebook    | [7ccb76ba13](https://linux-hardware.org/?probe=7ccb76ba13) | Aug 06, 2019 |
| ASUSTek       | P8Z68-V PRO GEN3            | Desktop     | [52a21e2dd3](https://linux-hardware.org/?probe=52a21e2dd3) | Aug 05, 2019 |
| ASUSTek       | M2N-MX                      | Desktop     | [97e0e3e7ce](https://linux-hardware.org/?probe=97e0e3e7ce) | Aug 04, 2019 |
| ASUSTek       | M2N-MX                      | Desktop     | [662d4876ce](https://linux-hardware.org/?probe=662d4876ce) | Aug 04, 2019 |
| Lenovo        | ThinkPad T530 2392APU       | Notebook    | [364e945cdb](https://linux-hardware.org/?probe=364e945cdb) | Aug 04, 2019 |
| Intel         | Crestline & ICH8M Chipse... | Notebook    | [6b7d39e528](https://linux-hardware.org/?probe=6b7d39e528) | Aug 04, 2019 |
| Intel         | Crestline & ICH8M Chipse... | Notebook    | [12a25c12c5](https://linux-hardware.org/?probe=12a25c12c5) | Aug 04, 2019 |
| HP            | 0AA8h                       | Desktop     | [e4137ad45b](https://linux-hardware.org/?probe=e4137ad45b) | Jul 31, 2019 |
| HP            | 0AA8h                       | Desktop     | [22921b3801](https://linux-hardware.org/?probe=22921b3801) | Jul 31, 2019 |
| Foxconn       | G41MX/G41MX-K 2.0 1.0       | Desktop     | [497734b7f0](https://linux-hardware.org/?probe=497734b7f0) | Jul 30, 2019 |
| Dell          | Inspiron 5521               | Notebook    | [5e78d3fef1](https://linux-hardware.org/?probe=5e78d3fef1) | Jul 29, 2019 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [c61c9e33f6](https://linux-hardware.org/?probe=c61c9e33f6) | Jul 28, 2019 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [d0006f445b](https://linux-hardware.org/?probe=d0006f445b) | Jul 28, 2019 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | Notebook    | [7957c03703](https://linux-hardware.org/?probe=7957c03703) | Jul 28, 2019 |
| HP            | ENVY m6                     | Notebook    | [a978f2ca38](https://linux-hardware.org/?probe=a978f2ca38) | Jul 25, 2019 |
| Dell          | XPS 15 9570                 | Notebook    | [7a9639f003](https://linux-hardware.org/?probe=7a9639f003) | Jul 24, 2019 |
| Dell          | XPS 15 9570                 | Notebook    | [9ca695a346](https://linux-hardware.org/?probe=9ca695a346) | Jul 24, 2019 |
| HP            | EliteBook 840 G1            | Notebook    | [a6a99375a8](https://linux-hardware.org/?probe=a6a99375a8) | Jul 22, 2019 |
| HP            | Pavilion tx1000             | Notebook    | [4a6a073320](https://linux-hardware.org/?probe=4a6a073320) | Jul 22, 2019 |
| TUXEDO        | Unknown                     | Notebook    | [087a8f3344](https://linux-hardware.org/?probe=087a8f3344) | Jul 21, 2019 |
| HP            | Compaq nc6400 (RM100ET#A... | Notebook    | [9f51d8d813](https://linux-hardware.org/?probe=9f51d8d813) | Jul 21, 2019 |
| Dell          | Inspiron 3521               | Notebook    | [b471f52a9a](https://linux-hardware.org/?probe=b471f52a9a) | Jul 20, 2019 |
| HP            | EliteBook 840 G1            | Notebook    | [b3bb828c5a](https://linux-hardware.org/?probe=b3bb828c5a) | Jul 19, 2019 |
| Apple         | MacBookPro5,1               | Notebook    | [e6f14346be](https://linux-hardware.org/?probe=e6f14346be) | Jul 15, 2019 |
| Intel         | D34010WYK H14771-302        | Desktop     | [84e10f6b4c](https://linux-hardware.org/?probe=84e10f6b4c) | Jul 15, 2019 |
| HP            | Pavilion g7                 | Notebook    | [fef9011be9](https://linux-hardware.org/?probe=fef9011be9) | Jul 13, 2019 |
| HP            | Pavilion g7                 | Notebook    | [586d054ba7](https://linux-hardware.org/?probe=586d054ba7) | Jul 13, 2019 |
| Toshiba       | Satellite C55D-A            | Notebook    | [98772b73bb](https://linux-hardware.org/?probe=98772b73bb) | Jul 12, 2019 |
| HP            | 3047h                       | Desktop     | [69c510957c](https://linux-hardware.org/?probe=69c510957c) | Jul 10, 2019 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [3c4f4aba16](https://linux-hardware.org/?probe=3c4f4aba16) | Jul 09, 2019 |
| ASUSTek       | P5LD2-X/1333                | Desktop     | [7d6812488d](https://linux-hardware.org/?probe=7d6812488d) | Jul 08, 2019 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | Desktop     | [d8dff6cec0](https://linux-hardware.org/?probe=d8dff6cec0) | Jul 06, 2019 |
| Dell          | Inspiron 7520               | Notebook    | [8529fa049a](https://linux-hardware.org/?probe=8529fa049a) | Jul 04, 2019 |
| Dell          | Inspiron 7520               | Notebook    | [3227e98bbe](https://linux-hardware.org/?probe=3227e98bbe) | Jul 04, 2019 |
| Supermicro    | X11SAE-M                    | Server      | [c392838a14](https://linux-hardware.org/?probe=c392838a14) | Jul 04, 2019 |
| Pegatron      | NARRA5                      | Desktop     | [2157826b54](https://linux-hardware.org/?probe=2157826b54) | Jul 03, 2019 |
| Pegatron      | NARRA5                      | Desktop     | [277d5004d4](https://linux-hardware.org/?probe=277d5004d4) | Jul 03, 2019 |
| Sony          | VPCZ227GG                   | Notebook    | [9109d4a264](https://linux-hardware.org/?probe=9109d4a264) | Jul 03, 2019 |
| HP            | ProBook 450 G4              | Notebook    | [4fb036ba95](https://linux-hardware.org/?probe=4fb036ba95) | Jul 03, 2019 |
| HP            | ProBook 4730s               | Notebook    | [ed98a45d81](https://linux-hardware.org/?probe=ed98a45d81) | Jul 01, 2019 |
| Dell          | 0G261D A00                  | Desktop     | [13d30ec9c7](https://linux-hardware.org/?probe=13d30ec9c7) | Jun 30, 2019 |
| Dell          | 0G261D A00                  | Desktop     | [68cf43b792](https://linux-hardware.org/?probe=68cf43b792) | Jun 29, 2019 |
| Dell          | 0G261D A00                  | Desktop     | [4bc356e77f](https://linux-hardware.org/?probe=4bc356e77f) | Jun 29, 2019 |
| Sony          | SVF1521B1EW                 | Notebook    | [20f5b70678](https://linux-hardware.org/?probe=20f5b70678) | Jun 28, 2019 |
| HP            | 304Ah                       | Desktop     | [99c6f2f320](https://linux-hardware.org/?probe=99c6f2f320) | Jun 26, 2019 |
| HP            | 304Ah                       | Desktop     | [5c7e5fec70](https://linux-hardware.org/?probe=5c7e5fec70) | Jun 26, 2019 |
| Acer          | Veriton M2631G V:1.0        | Desktop     | [183a936816](https://linux-hardware.org/?probe=183a936816) | Jun 25, 2019 |
| Dell          | Latitude E7240              | Notebook    | [9cc6b87f3a](https://linux-hardware.org/?probe=9cc6b87f3a) | Jun 25, 2019 |
| ASUSTek       | X541UVK                     | Notebook    | [baf89919e7](https://linux-hardware.org/?probe=baf89919e7) | Jun 24, 2019 |
| ASUSTek       | T300CHI                     | Notebook    | [1211294e7c](https://linux-hardware.org/?probe=1211294e7c) | Jun 23, 2019 |
| Lenovo        | 31900006 STD                | Desktop     | [92a61c8b37](https://linux-hardware.org/?probe=92a61c8b37) | Jun 23, 2019 |
| ASUSTek       | H81M-A                      | Desktop     | [dd373074f4](https://linux-hardware.org/?probe=dd373074f4) | Jun 23, 2019 |
| Dell          | 0M9KCM A00                  | Desktop     | [a36e17bc4e](https://linux-hardware.org/?probe=a36e17bc4e) | Jun 21, 2019 |
| Dell          | 0M9KCM A00                  | Desktop     | [e07c830a5e](https://linux-hardware.org/?probe=e07c830a5e) | Jun 21, 2019 |
| Toshiba       | Satellite P755              | Notebook    | [d9fc00d39e](https://linux-hardware.org/?probe=d9fc00d39e) | Jun 17, 2019 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | Desktop     | [ca162546ee](https://linux-hardware.org/?probe=ca162546ee) | Jun 16, 2019 |
| Acer          | Veriton M2631G V:1.0        | Desktop     | [54c54c6722](https://linux-hardware.org/?probe=54c54c6722) | Jun 16, 2019 |
| Acer          | Veriton M2631G V:1.0        | Desktop     | [2a79bbc472](https://linux-hardware.org/?probe=2a79bbc472) | Jun 15, 2019 |
| Gigabyte      | Z87X-UD4H-CF                | Desktop     | [b189962fa8](https://linux-hardware.org/?probe=b189962fa8) | Jun 14, 2019 |
| Gigabyte      | Z87X-UD4H-CF                | Desktop     | [3166cd0be4](https://linux-hardware.org/?probe=3166cd0be4) | Jun 14, 2019 |
| Lenovo        | ThinkStation D20 4158V7V    | Desktop     | [29b0070304](https://linux-hardware.org/?probe=29b0070304) | Jun 13, 2019 |
| ASUSTek       | X99-A/USB                   | Desktop     | [d1e49be03d](https://linux-hardware.org/?probe=d1e49be03d) | Jun 11, 2019 |
| ASRock        | N68C-S UCC                  | Desktop     | [ac6b9f6fbe](https://linux-hardware.org/?probe=ac6b9f6fbe) | Jun 11, 2019 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | Notebook    | [7d66aa72d3](https://linux-hardware.org/?probe=7d66aa72d3) | Jun 10, 2019 |
| ASUSTek       | T102HA                      | Notebook    | [1a0e086ef8](https://linux-hardware.org/?probe=1a0e086ef8) | Jun 10, 2019 |
| ASUSTek       | T101HA                      | Tablet      | [1eb4640c84](https://linux-hardware.org/?probe=1eb4640c84) | Jun 09, 2019 |
| ASUSTek       | T101HA                      | Tablet      | [c4d7f7a2f4](https://linux-hardware.org/?probe=c4d7f7a2f4) | Jun 09, 2019 |
| HP            | Pavilion tx1000             | Notebook    | [a783eb7140](https://linux-hardware.org/?probe=a783eb7140) | Jun 08, 2019 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [0aeb179eb6](https://linux-hardware.org/?probe=0aeb179eb6) | Jun 07, 2019 |
| ASRock        | G31M-S                      | Desktop     | [556d0f2ca6](https://linux-hardware.org/?probe=556d0f2ca6) | Jun 06, 2019 |
| Toshiba       | Satellite A215              | Notebook    | [08d2d708f8](https://linux-hardware.org/?probe=08d2d708f8) | May 23, 2019 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Zorin_15/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.3.0-40-generic  | 110       | 6.32%   |
| 5.4.0-42-generic  | 97        | 5.57%   |
| 5.0.0-37-generic  | 79        | 4.54%   |
| 5.3.0-46-generic  | 73        | 4.2%    |
| 5.3.0-51-generic  | 65        | 3.74%   |
| 5.4.0-47-generic  | 60        | 3.45%   |
| 5.3.0-53-generic  | 54        | 3.1%    |
| 5.4.0-58-generic  | 52        | 2.99%   |
| 5.3.0-42-generic  | 52        | 2.99%   |
| 5.4.0-48-generic  | 48        | 2.76%   |
| 5.4.0-65-generic  | 46        | 2.64%   |
| 5.4.0-72-generic  | 45        | 2.59%   |
| 5.4.0-45-generic  | 45        | 2.59%   |
| 5.4.0-80-generic  | 41        | 2.36%   |
| 5.3.0-62-generic  | 38        | 2.18%   |
| 5.3.0-28-generic  | 36        | 2.07%   |
| 5.4.0-81-generic  | 33        | 1.9%    |
| 5.4.0-54-generic  | 33        | 1.9%    |
| 5.3.0-59-generic  | 33        | 1.9%    |
| 5.4.0-73-generic  | 31        | 1.78%   |
| 5.4.0-66-generic  | 31        | 1.78%   |
| 5.4.0-52-generic  | 31        | 1.78%   |
| 5.4.0-74-generic  | 28        | 1.61%   |
| 5.4.0-70-generic  | 28        | 1.61%   |
| 5.3.0-45-generic  | 28        | 1.61%   |
| 4.18.0-21-generic | 28        | 1.61%   |
| 5.4.0-77-generic  | 25        | 1.44%   |
| 4.18.0-25-generic | 25        | 1.44%   |
| 5.4.0-91-generic  | 21        | 1.21%   |
| 5.4.0-87-generic  | 21        | 1.21%   |
| 5.4.0-56-generic  | 21        | 1.21%   |
| 5.0.0-36-generic  | 20        | 1.15%   |
| 4.18.0-22-generic | 20        | 1.15%   |
| 5.4.0-89-generic  | 18        | 1.03%   |
| 5.3.0-61-generic  | 17        | 0.98%   |
| 5.4.0-64-generic  | 16        | 0.92%   |
| 5.4.0-90-generic  | 15        | 0.86%   |
| 5.4.0-51-generic  | 15        | 0.86%   |
| 5.4.0-62-generic  | 14        | 0.8%    |
| 5.4.0-53-generic  | 14        | 0.8%    |
| 5.3.0-26-generic  | 14        | 0.8%    |
| 5.4.0-67-generic  | 13        | 0.75%   |
| 5.4.0-60-generic  | 13        | 0.75%   |
| 5.0.0-32-generic  | 12        | 0.69%   |
| 5.0.0-25-generic  | 12        | 0.69%   |
| 5.4.0-99-generic  | 11        | 0.63%   |
| 5.0.0-23-generic  | 11        | 0.63%   |
| 5.4.0-84-generic  | 10        | 0.57%   |
| 5.4.0-100-generic | 10        | 0.57%   |
| 5.0.0-31-generic  | 9         | 0.52%   |
| 5.4.0-86-generic  | 8         | 0.46%   |
| 5.4.0-97-generic  | 7         | 0.4%    |
| 5.4.0-92-generic  | 7         | 0.4%    |
| 5.4.0-120-generic | 6         | 0.34%   |
| 5.4.0-109-generic | 6         | 0.34%   |
| 5.4.0-107-generic | 6         | 0.34%   |
| 5.4.0-105-generic | 6         | 0.34%   |
| 5.0.0-27-generic  | 6         | 0.34%   |
| 5.4.0-96-generic  | 5         | 0.29%   |
| 5.4.0-121-generic | 5         | 0.29%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 877       | 54.54%  |
| 5.3.0   | 487       | 30.29%  |
| 5.0.0   | 153       | 9.51%   |
| 4.18.0  | 75        | 4.66%   |
| 5.7.1   | 3         | 0.19%   |
| 5.7.0   | 2         | 0.12%   |
| 5.6.0   | 2         | 0.12%   |
| 5.9.12  | 1         | 0.06%   |
| 5.9.0   | 1         | 0.06%   |
| 5.8.5   | 1         | 0.06%   |
| 5.8.0   | 1         | 0.06%   |
| 5.7.17  | 1         | 0.06%   |
| 5.4.1   | 1         | 0.06%   |
| 5.15.0  | 1         | 0.06%   |
| 5.10.35 | 1         | 0.06%   |
| 5.10.16 | 1         | 0.06%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 878       | 54.6%   |
| 5.3     | 487       | 30.29%  |
| 5.0     | 153       | 9.51%   |
| 4.18    | 75        | 4.66%   |
| 5.7     | 6         | 0.37%   |
| 5.9     | 2         | 0.12%   |
| 5.8     | 2         | 0.12%   |
| 5.6     | 2         | 0.12%   |
| 5.10    | 2         | 0.12%   |
| 5.15    | 1         | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 1286      | 82.54%  |
| i686   | 272       | 17.46%  |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 881       | 55.69%  |
| XFCE       | 535       | 33.82%  |
| Unknown    | 160       | 10.11%  |
| KDE        | 3         | 0.19%   |
| X-Cinnamon | 1         | 0.06%   |
| Unity      | 1         | 0.06%   |
| KDE5       | 1         | 0.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1448      | 92.11%  |
| Unknown | 104       | 6.62%   |
| Wayland | 20        | 1.27%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1400      | 88.33%  |
| LightDM | 100       | 6.31%   |
| GDM3    | 58        | 3.66%   |
| GDM     | 17        | 1.07%   |
| TDM     | 9         | 0.57%   |
| SDDM    | 1         | 0.06%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 518       | 33.04%  |
| pt_BR   | 125       | 7.97%   |
| Unknown | 110       | 7.02%   |
| de_DE   | 85        | 5.42%   |
| en_GB   | 80        | 5.1%    |
| it_IT   | 64        | 4.08%   |
| en_IN   | 49        | 3.13%   |
| en_CA   | 48        | 3.06%   |
| es_ES   | 36        | 2.3%    |
| pl_PL   | 34        | 2.17%   |
| fr_FR   | 34        | 2.17%   |
| es_AR   | 28        | 1.79%   |
| pt_PT   | 26        | 1.66%   |
| C       | 24        | 1.53%   |
| es_MX   | 22        | 1.4%    |
| ru_RU   | 20        | 1.28%   |
| nl_NL   | 20        | 1.28%   |
| en_AU   | 20        | 1.28%   |
| en_ZA   | 15        | 0.96%   |
| cs_CZ   | 15        | 0.96%   |
| es_CL   | 13        | 0.83%   |
| tr_TR   | 12        | 0.77%   |
| sv_SE   | 12        | 0.77%   |
| es_CO   | 12        | 0.77%   |
| fr_CA   | 11        | 0.7%    |
| hu_HU   | 10        | 0.64%   |
| ja_JP   | 8         | 0.51%   |
| es_PE   | 8         | 0.51%   |
| de_AT   | 8         | 0.51%   |
| en_NZ   | 7         | 0.45%   |
| el_GR   | 7         | 0.45%   |
| da_DK   | 7         | 0.45%   |
| ro_RO   | 6         | 0.38%   |
| en_PH   | 6         | 0.38%   |
| ru_UA   | 5         | 0.32%   |
| bg_BG   | 5         | 0.32%   |
| de_CH   | 4         | 0.26%   |
| sr_RS   | 3         | 0.19%   |
| sl_SI   | 3         | 0.19%   |
| sk_SK   | 3         | 0.19%   |
| nl_BE   | 3         | 0.19%   |
| nb_NO   | 3         | 0.19%   |
| fi_FI   | 3         | 0.19%   |
| en_IL   | 3         | 0.19%   |
| id_ID   | 2         | 0.13%   |
| hr_HR   | 2         | 0.13%   |
| es_VE   | 2         | 0.13%   |
| es_UY   | 2         | 0.13%   |
| es_PA   | 2         | 0.13%   |
| es_EC   | 2         | 0.13%   |
| en_IE   | 2         | 0.13%   |
| uk_UA   | 1         | 0.06%   |
| th_TH   | 1         | 0.06%   |
| ko_KR   | 1         | 0.06%   |
| it_CH   | 1         | 0.06%   |
| is_IS   | 1         | 0.06%   |
| he_IL   | 1         | 0.06%   |
| fr_CH   | 1         | 0.06%   |
| eu_ES   | 1         | 0.06%   |
| es_US   | 1         | 0.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 1089      | 69.23%  |
| EFI  | 484       | 30.77%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1468      | 93.98%  |
| Overlay | 51        | 3.27%   |
| Unknown | 24        | 1.54%   |
| Btrfs   | 9         | 0.58%   |
| Ext2    | 8         | 0.51%   |
| Ext3    | 2         | 0.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1529      | 98.2%   |
| MBR     | 14        | 0.9%    |
| GPT     | 14        | 0.9%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1406      | 89.61%  |
| Yes       | 163       | 10.39%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1075      | 68.08%  |
| Yes       | 504       | 31.92%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                            | Computers | Percent |
|---------------------------------|-----------|---------|
| Hewlett-Packard                 | 291       | 18.69%  |
| Dell                            | 199       | 12.78%  |
| ASUSTek Computer                | 197       | 12.65%  |
| Lenovo                          | 161       | 10.34%  |
| Acer                            | 104       | 6.68%   |
| Gigabyte Technology             | 77        | 4.95%   |
| Toshiba                         | 63        | 4.05%   |
| ASRock                          | 46        | 2.95%   |
| MSI                             | 44        | 2.83%   |
| Apple                           | 31        | 1.99%   |
| Samsung Electronics             | 28        | 1.8%    |
| Intel                           | 23        | 1.48%   |
| Unknown                         | 22        | 1.41%   |
| Sony                            | 20        | 1.28%   |
| Pegatron                        | 16        | 1.03%   |
| Fujitsu                         | 14        | 0.9%    |
| Packard Bell                    | 13        | 0.83%   |
| ECS                             | 13        | 0.83%   |
| Positivo                        | 12        | 0.77%   |
| Fujitsu Siemens                 | 11        | 0.71%   |
| Medion                          | 10        | 0.64%   |
| Foxconn                         | 8         | 0.51%   |
| AMI                             | 7         | 0.45%   |
| Panasonic                       | 6         | 0.39%   |
| Gateway                         | 6         | 0.39%   |
| eMachines                       | 6         | 0.39%   |
| Semp Toshiba                    | 5         | 0.32%   |
| HUAWEI                          | 5         | 0.32%   |
| Biostar                         | 5         | 0.32%   |
| Alienware                       | 5         | 0.32%   |
| Shuttle                         | 4         | 0.26%   |
| Notebook                        | 4         | 0.26%   |
| NEC Computers                   | 4         | 0.26%   |
| IBM                             | 4         | 0.26%   |
| Quanta                          | 3         | 0.19%   |
| Itautec                         | 3         | 0.19%   |
| Insyde                          | 3         | 0.19%   |
| Google                          | 3         | 0.19%   |
| Ematic                          | 3         | 0.19%   |
| Clevo                           | 3         | 0.19%   |
| ZOTAC                           | 2         | 0.13%   |
| WinFast                         | 2         | 0.13%   |
| TrekStor                        | 2         | 0.13%   |
| Supermicro                      | 2         | 0.13%   |
| Philco                          | 2         | 0.13%   |
| Multilaser                      | 2         | 0.13%   |
| Microsoft                       | 2         | 0.13%   |
| Durabook                        | 2         | 0.13%   |
| Digibras                        | 2         | 0.13%   |
| ARIMA                           | 2         | 0.13%   |
| ABIT                            | 2         | 0.13%   |
| Xi3                             | 1         | 0.06%   |
| Wistron                         | 1         | 0.06%   |
| WIPRO                           | 1         | 0.06%   |
| WinSome                         | 1         | 0.06%   |
| Wiltronic                       | 1         | 0.06%   |
| Universal Exports Group Limited | 1         | 0.06%   |
| UMAX                            | 1         | 0.06%   |
| TWC                             | 1         | 0.06%   |
| TUXEDO                          | 1         | 0.06%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Unknown                      | 39        | 2.5%    |
| HP Notebook                  | 9         | 0.58%   |
| ASUS All Series              | 8         | 0.51%   |
| HP Pavilion dv6              | 6         | 0.39%   |
| HP Pavilion dv7              | 5         | 0.32%   |
| HP Pavilion dv6700           | 5         | 0.32%   |
| Dell Latitude E6410          | 5         | 0.32%   |
| Dell Latitude E6400          | 5         | 0.32%   |
| Dell Inspiron 1545           | 5         | 0.32%   |
| Toshiba Satellite C660       | 4         | 0.26%   |
| Positivo Mobile              | 4         | 0.26%   |
| HP Laptop 15-bw0xx           | 4         | 0.26%   |
| HP Compaq Presario CQ61      | 4         | 0.26%   |
| HP 530                       | 4         | 0.26%   |
| HP 15                        | 4         | 0.26%   |
| Gigabyte A320M-S2H           | 4         | 0.26%   |
| Dell Latitude D630           | 4         | 0.26%   |
| Dell Inspiron 1525           | 4         | 0.26%   |
| Toshiba Satellite C55-A      | 3         | 0.19%   |
| Samsung 340XAA/350XAA/550XAA | 3         | 0.19%   |
| Packard Bell EasyNote TJ65   | 3         | 0.19%   |
| MSI MS-7721                  | 3         | 0.19%   |
| Lenovo MIIX 320-10ICR 80XF   | 3         | 0.19%   |
| HUAWEI BOHK-WAX9X            | 3         | 0.19%   |
| HP ProBook 4540s             | 3         | 0.19%   |
| HP Pavilion Notebook         | 3         | 0.19%   |
| HP Pavilion g7               | 3         | 0.19%   |
| HP Pavilion dv5              | 3         | 0.19%   |
| HP Pavilion 17               | 3         | 0.19%   |
| HP EliteBook 8460p           | 3         | 0.19%   |
| HP EliteBook 840 G1          | 3         | 0.19%   |
| HP EliteBook 6930p           | 3         | 0.19%   |
| HP Compaq Presario CQ60      | 3         | 0.19%   |
| Gigabyte 970A-DS3P           | 3         | 0.19%   |
| Dell OptiPlex 780            | 3         | 0.19%   |
| Dell OptiPlex 755            | 3         | 0.19%   |
| Dell OptiPlex 7010           | 3         | 0.19%   |
| Dell Latitude D520           | 3         | 0.19%   |
| Dell Inspiron N4010          | 3         | 0.19%   |
| Dell Inspiron 7520           | 3         | 0.19%   |
| Dell Inspiron 6000           | 3         | 0.19%   |
| Dell Inspiron 3521           | 3         | 0.19%   |
| Dell Inspiron 1520           | 3         | 0.19%   |
| Dell Inspiron 15-3567        | 3         | 0.19%   |
| ASUS M5A97 R2.0              | 3         | 0.19%   |
| ASRock N68C-S UCC            | 3         | 0.19%   |
| Acer Aspire one              | 3         | 0.19%   |
| TrekStor Notebook Slim S130  | 2         | 0.13%   |
| Toshiba Satellite M70        | 2         | 0.13%   |
| Toshiba Satellite A215       | 2         | 0.13%   |
| Toshiba Satellite A100       | 2         | 0.13%   |
| Semp Toshiba STI             | 2         | 0.13%   |
| Samsung 305E4A/305E5A/305E7A | 2         | 0.13%   |
| Quanta MW1/HW1               | 2         | 0.13%   |
| Positivo S14CT01             | 2         | 0.13%   |
| Pegatron NE502AV-ABA a6750t  | 2         | 0.13%   |
| Pegatron 320-1030            | 2         | 0.13%   |
| Packard Bell EasyNote MH35   | 2         | 0.13%   |
| Multilaser PC024             | 2         | 0.13%   |
| MSI MS-7C02                  | 2         | 0.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell Inspiron           | 74        | 4.75%   |
| Acer Aspire             | 67        | 4.3%    |
| HP Pavilion             | 64        | 4.11%   |
| Toshiba Satellite       | 56        | 3.6%    |
| Lenovo ThinkPad         | 51        | 3.28%   |
| HP Compaq               | 49        | 3.15%   |
| Dell Latitude           | 47        | 3.02%   |
| Unknown                 | 39        | 2.5%    |
| Lenovo IdeaPad          | 38        | 2.44%   |
| Dell OptiPlex           | 30        | 1.93%   |
| HP EliteBook            | 29        | 1.86%   |
| HP ProBook              | 24        | 1.54%   |
| Lenovo ThinkCentre      | 18        | 1.16%   |
| HP Laptop               | 17        | 1.09%   |
| Dell Vostro             | 13        | 0.83%   |
| Packard Bell EasyNote   | 11        | 0.71%   |
| HP Presario             | 10        | 0.64%   |
| Dell Precision          | 10        | 0.64%   |
| HP Notebook             | 9         | 0.58%   |
| Lenovo Yoga             | 8         | 0.51%   |
| ASUS All                | 8         | 0.51%   |
| HP Mini                 | 7         | 0.45%   |
| HP ENVY                 | 7         | 0.45%   |
| Fujitsu ESPRIMO         | 7         | 0.45%   |
| Dell XPS                | 7         | 0.45%   |
| ASUS TUF                | 7         | 0.45%   |
| HP 255                  | 6         | 0.39%   |
| Fujitsu Siemens AMILO   | 6         | 0.39%   |
| ASUS ROG                | 6         | 0.39%   |
| ASUS PRIME              | 6         | 0.39%   |
| HP ZBook                | 5         | 0.32%   |
| HP Stream               | 5         | 0.32%   |
| HP 530                  | 5         | 0.32%   |
| ASUS VivoBook           | 5         | 0.32%   |
| Acer Veriton            | 5         | 0.32%   |
| Positivo Mobile         | 4         | 0.26%   |
| Lenovo MIIX             | 4         | 0.26%   |
| HP 15                   | 4         | 0.26%   |
| Gigabyte A320M-S2H      | 4         | 0.26%   |
| Fujitsu LIFEBOOK        | 4         | 0.26%   |
| Dell System             | 4         | 0.26%   |
| Dell Studio             | 4         | 0.26%   |
| ASUS ZenBook            | 4         | 0.26%   |
| ASUS P5G41T-M           | 4         | 0.26%   |
| ASUS M5A97              | 4         | 0.26%   |
| ASRock N68C-S           | 4         | 0.26%   |
| Acer Extensa            | 4         | 0.26%   |
| Semp Toshiba STI        | 3         | 0.19%   |
| Samsung 340XAA          | 3         | 0.19%   |
| MSI MS-7721             | 3         | 0.19%   |
| Lenovo IdeaCentre       | 3         | 0.19%   |
| Itautec Infoway         | 3         | 0.19%   |
| HUAWEI BOHK-WAX9X       | 3         | 0.19%   |
| HP ProDesk              | 3         | 0.19%   |
| HP EliteDesk            | 3         | 0.19%   |
| Gigabyte GA-78LMT-USB3  | 3         | 0.19%   |
| Gigabyte B450           | 3         | 0.19%   |
| Gigabyte 970A-DS3P      | 3         | 0.19%   |
| Fujitsu Siemens ESPRIMO | 3         | 0.19%   |
| ASUS M5A78L-M           | 3         | 0.19%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2010    | 152       | 9.76%   |
| 2011    | 149       | 9.57%   |
| 2008    | 132       | 8.48%   |
| 2009    | 130       | 8.35%   |
| 2007    | 127       | 8.16%   |
| 2013    | 114       | 7.32%   |
| 2012    | 114       | 7.32%   |
| 2018    | 104       | 6.68%   |
| 2017    | 89        | 5.72%   |
| 2014    | 89        | 5.72%   |
| 2015    | 72        | 4.62%   |
| 2019    | 67        | 4.3%    |
| 2016    | 66        | 4.24%   |
| 2006    | 57        | 3.66%   |
| 2005    | 44        | 2.83%   |
| 2020    | 33        | 2.12%   |
| 2004    | 7         | 0.45%   |
| 2021    | 6         | 0.39%   |
| 2003    | 3         | 0.19%   |
| 2002    | 1         | 0.06%   |
| Unknown | 1         | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 958       | 61.53%  |
| Desktop     | 528       | 33.91%  |
| Convertible | 22        | 1.41%   |
| All in one  | 22        | 1.41%   |
| Tablet      | 12        | 0.77%   |
| Mini pc     | 12        | 0.77%   |
| Server      | 3         | 0.19%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1467      | 94.04%  |
| Enabled  | 93        | 5.96%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1553      | 99.74%  |
| Yes  | 4         | 0.26%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 476       | 30.18%  |
| 4.01-8.0    | 300       | 19.02%  |
| 1.01-2.0    | 249       | 15.79%  |
| 8.01-16.0   | 207       | 13.13%  |
| 16.01-24.0  | 136       | 8.62%   |
| 2.01-3.0    | 87        | 5.52%   |
| 0.51-1.0    | 68        | 4.31%   |
| 32.01-64.0  | 39        | 2.47%   |
| 64.01-256.0 | 8         | 0.51%   |
| 24.01-32.0  | 7         | 0.44%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 820       | 49.25%  |
| 2.01-3.0   | 339       | 20.36%  |
| 0.51-1.0   | 251       | 15.08%  |
| 3.01-4.0   | 136       | 8.17%   |
| 4.01-8.0   | 87        | 5.23%   |
| 0.01-0.5   | 17        | 1.02%   |
| 8.01-16.0  | 14        | 0.84%   |
| 16.01-24.0 | 1         | 0.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1100      | 69.14%  |
| 2      | 353       | 22.19%  |
| 3      | 85        | 5.34%   |
| 4      | 25        | 1.57%   |
| 5      | 13        | 0.82%   |
| 0      | 8         | 0.5%    |
| 6      | 3         | 0.19%   |
| 7      | 2         | 0.13%   |
| 10     | 1         | 0.06%   |
| 8      | 1         | 0.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 904       | 57.73%  |
| No        | 662       | 42.27%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1423      | 91.28%  |
| No        | 136       | 8.72%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1242      | 79.41%  |
| No        | 322       | 20.59%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 876       | 55.8%   |
| Yes       | 694       | 44.2%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 327       | 20.92%  |
| Brazil       | 144       | 9.21%   |
| Germany      | 107       | 6.85%   |
| UK           | 89        | 5.69%   |
| Canada       | 68        | 4.35%   |
| Italy        | 66        | 4.22%   |
| India        | 55        | 3.52%   |
| France       | 39        | 2.5%    |
| Spain        | 36        | 2.3%    |
| Netherlands  | 36        | 2.3%    |
| Poland       | 35        | 2.24%   |
| Argentina    | 34        | 2.18%   |
| Portugal     | 29        | 1.86%   |
| Mexico       | 28        | 1.79%   |
| Australia    | 24        | 1.54%   |
| Indonesia    | 23        | 1.47%   |
| Sweden       | 21        | 1.34%   |
| South Africa | 19        | 1.22%   |
| Romania      | 19        | 1.22%   |
| Czechia      | 18        | 1.15%   |
| Greece       | 17        | 1.09%   |
| Colombia     | 16        | 1.02%   |
| Switzerland  | 15        | 0.96%   |
| Russia       | 15        | 0.96%   |
| Chile        | 14        | 0.9%    |
| Serbia       | 13        | 0.83%   |
| Turkey       | 12        | 0.77%   |
| New Zealand  | 12        | 0.77%   |
| Philippines  | 11        | 0.7%    |
| Denmark      | 11        | 0.7%    |
| Bulgaria     | 11        | 0.7%    |
| Austria      | 11        | 0.7%    |
| Ukraine      | 10        | 0.64%   |
| Peru         | 10        | 0.64%   |
| Japan        | 10        | 0.64%   |
| Hungary      | 10        | 0.64%   |
| Norway       | 8         | 0.51%   |
| Belgium      | 8         | 0.51%   |
| Thailand     | 7         | 0.45%   |
| Egypt        | 7         | 0.45%   |
| Kenya        | 6         | 0.38%   |
| Israel       | 6         | 0.38%   |
| Pakistan     | 5         | 0.32%   |
| South Korea  | 4         | 0.26%   |
| Slovenia     | 4         | 0.26%   |
| Slovakia     | 4         | 0.26%   |
| Panama       | 4         | 0.26%   |
| Malaysia     | 4         | 0.26%   |
| Ireland      | 4         | 0.26%   |
| Iran         | 4         | 0.26%   |
| Finland      | 4         | 0.26%   |
| Ecuador      | 4         | 0.26%   |
| Croatia      | 4         | 0.26%   |
| Bangladesh   | 4         | 0.26%   |
| Vietnam      | 3         | 0.19%   |
| Venezuela    | 3         | 0.19%   |
| UAE          | 3         | 0.19%   |
| Tunisia      | 3         | 0.19%   |
| Sri Lanka    | 3         | 0.19%   |
| Uruguay      | 2         | 0.13%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Sao Paulo      | 20        | 1.23%   |
| Rio de Janeiro | 11        | 0.68%   |
| Berlin         | 11        | 0.68%   |
| Milan          | 10        | 0.62%   |
| Vienna         | 9         | 0.55%   |
| Zurich         | 8         | 0.49%   |
| Warsaw         | 8         | 0.49%   |
| Toronto        | 8         | 0.49%   |
| Perth          | 8         | 0.49%   |
| Johannesburg   | 8         | 0.49%   |
| Buenos Aires   | 8         | 0.49%   |
| Auckland       | 8         | 0.49%   |
| Sydney         | 7         | 0.43%   |
| Rome           | 7         | 0.43%   |
| Montreal       | 7         | 0.43%   |
| Bengaluru      | 7         | 0.43%   |
| Belgrade       | 7         | 0.43%   |
| Athens         | 7         | 0.43%   |
| Sofia          | 6         | 0.37%   |
| Prague         | 6         | 0.37%   |
| Nairobi        | 6         | 0.37%   |
| Mexico City    | 6         | 0.37%   |
| Istanbul       | 6         | 0.37%   |
| Cairo          | 6         | 0.37%   |
| Bucharest      | 6         | 0.37%   |
| Bogotá        | 6         | 0.37%   |
| The Hague      | 5         | 0.31%   |
| Stockholm      | 5         | 0.31%   |
| Salvador       | 5         | 0.31%   |
| Portland       | 5         | 0.31%   |
| Paris          | 5         | 0.31%   |
| Munich         | 5         | 0.31%   |
| Madrid         | 5         | 0.31%   |
| Lima           | 5         | 0.31%   |
| Joao Pessoa    | 5         | 0.31%   |
| Denver         | 5         | 0.31%   |
| Copenhagen     | 5         | 0.31%   |
| Brooklyn       | 5         | 0.31%   |
| Yogyakarta     | 4         | 0.25%   |
| Winnipeg       | 4         | 0.25%   |
| Tel Aviv       | 4         | 0.25%   |
| Surabaya       | 4         | 0.25%   |
| Seattle        | 4         | 0.25%   |
| San Francisco  | 4         | 0.25%   |
| Rotterdam      | 4         | 0.25%   |
| Pune           | 4         | 0.25%   |
| Panama City    | 4         | 0.25%   |
| New Delhi      | 4         | 0.25%   |
| Moscow         | 4         | 0.25%   |
| Los Angeles    | 4         | 0.25%   |
| London         | 4         | 0.25%   |
| Lisbon         | 4         | 0.25%   |
| Las Vegas      | 4         | 0.25%   |
| Kyiv           | 4         | 0.25%   |
| Jakarta        | 4         | 0.25%   |
| Jaipur         | 4         | 0.25%   |
| Houston        | 4         | 0.25%   |
| Dortmund       | 4         | 0.25%   |
| Dayton         | 4         | 0.25%   |
| Cape Town      | 4         | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 362       | 450    | 18.38%  |
| Seagate                   | 360       | 458    | 18.28%  |
| Samsung Electronics       | 207       | 278    | 10.51%  |
| Toshiba                   | 172       | 205    | 8.74%   |
| Hitachi                   | 139       | 161    | 7.06%   |
| Unknown                   | 119       | 170    | 6.04%   |
| Kingston                  | 98        | 113    | 4.98%   |
| SanDisk                   | 77        | 94     | 3.91%   |
| Crucial                   | 42        | 50     | 2.13%   |
| HGST                      | 37        | 45     | 1.88%   |
| Intel                     | 34        | 41     | 1.73%   |
| Fujitsu                   | 28        | 29     | 1.42%   |
| Maxtor                    | 27        | 38     | 1.37%   |
| China                     | 17        | 18     | 0.86%   |
| Phison                    | 16        | 24     | 0.81%   |
| SK hynix                  | 14        | 18     | 0.71%   |
| Apple                     | 14        | 14     | 0.71%   |
| A-DATA Technology         | 14        | 14     | 0.71%   |
| PNY                       | 13        | 17     | 0.66%   |
| Intenso                   | 11        | 13     | 0.56%   |
| OCZ                       | 10        | 11     | 0.51%   |
| Micron Technology         | 10        | 12     | 0.51%   |
| Transcend                 | 9         | 12     | 0.46%   |
| SPCC                      | 9         | 10     | 0.46%   |
| Patriot                   | 8         | 14     | 0.41%   |
| Micron/Crucial Technology | 8         | 9      | 0.41%   |
| LITEON                    | 8         | 11     | 0.41%   |
| SABRENT                   | 7         | 7      | 0.36%   |
| JMicron Technology        | 5         | 8      | 0.25%   |
| Corsair                   | 5         | 6      | 0.25%   |
| Team                      | 4         | 4      | 0.2%    |
| TCSUNBOW                  | 4         | 4      | 0.2%    |
| LITEONIT                  | 4         | 4      | 0.2%    |
| Hewlett-Packard           | 4         | 4      | 0.2%    |
| Plextor                   | 3         | 3      | 0.15%   |
| Leven                     | 3         | 3      | 0.15%   |
| GOODRAM                   | 3         | 3      | 0.15%   |
| ASMT                      | 3         | 3      | 0.15%   |
| Apacer                    | 3         | 3      | 0.15%   |
| Zheino                    | 2         | 2      | 0.1%    |
| XrayDisk                  | 2         | 2      | 0.1%    |
| Verbatim                  | 2         | 2      | 0.1%    |
| TO Exter                  | 2         | 3      | 0.1%    |
| Silicon Motion            | 2         | 3      | 0.1%    |
| Pioneer                   | 2         | 2      | 0.1%    |
| OWC                       | 2         | 2      | 0.1%    |
| KingDian                  | 2         | 2      | 0.1%    |
| IBM/Hitachi               | 2         | 3      | 0.1%    |
| Gigabyte Technology       | 2         | 8      | 0.1%    |
| XPG                       | 1         | 2      | 0.05%   |
| WD MediaMax               | 1         | 1      | 0.05%   |
| USB30                     | 1         | 1      | 0.05%   |
| USB3.0                    | 1         | 1      | 0.05%   |
| TSA                       | 1         | 1      | 0.05%   |
| TrekStor                  | 1         | 1      | 0.05%   |
| S3+                       | 1         | 1      | 0.05%   |
| Realtek Semiconductor     | 1         | 1      | 0.05%   |
| PNY USB                   | 1         | 1      | 0.05%   |
| Pacific Sun               | 1         | 1      | 0.05%   |
| Mushkin                   | 1         | 1      | 0.05%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown MMC Card  32GB              | 46        | 2.21%   |
| Kingston SA400S37240G 240GB SSD     | 27        | 1.3%    |
| Unknown MMC Card  64GB              | 26        | 1.25%   |
| Toshiba MQ01ABF050 500GB            | 22        | 1.06%   |
| Kingston SA400S37480G 480GB SSD     | 17        | 0.82%   |
| Seagate ST500LT012-1DG142 500GB     | 15        | 0.72%   |
| Seagate ST500DM002-1BD142 500GB     | 14        | 0.67%   |
| Seagate ST1000LM035-1RK172 1TB      | 13        | 0.63%   |
| Kingston SA400S37120G 120GB SSD     | 13        | 0.63%   |
| Seagate ST3500418AS 500GB           | 12        | 0.58%   |
| Seagate ST1000DM010-2EP102 1TB      | 12        | 0.58%   |
| Crucial CT240BX500SSD1 240GB        | 12        | 0.58%   |
| Unknown MMC Card  128GB             | 11        | 0.53%   |
| Toshiba DT01ACA100 1TB              | 11        | 0.53%   |
| Seagate ST9500325AS 500GB           | 11        | 0.53%   |
| Samsung SSD 850 EVO 500GB           | 11        | 0.53%   |
| Kingston SV300S37A120G 120GB SSD    | 11        | 0.53%   |
| Hitachi HTS545032B9A300 320GB       | 11        | 0.53%   |
| Unknown MMC Card  16GB              | 10        | 0.48%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 10        | 0.48%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 10        | 0.48%   |
| Samsung SSD 860 EVO 500GB           | 10        | 0.48%   |
| Toshiba MQ04ABF100 1TB              | 9         | 0.43%   |
| Toshiba MQ01ABD100 1TB              | 9         | 0.43%   |
| Samsung SSD 860 EVO 250GB           | 9         | 0.43%   |
| Samsung NVMe SSD Drive 512GB        | 9         | 0.43%   |
| Samsung NVMe SSD Drive 500GB        | 9         | 0.43%   |
| Samsung NVMe SSD Drive 256GB        | 9         | 0.43%   |
| HGST HTS725050A7E630 500GB          | 9         | 0.43%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 8         | 0.38%   |
| Seagate ST1000DM003-1ER162 1TB      | 8         | 0.38%   |
| Hitachi HTS543232A7A384 320GB       | 8         | 0.38%   |
| WDC WD10EZEX-08WN4A0 1TB            | 7         | 0.34%   |
| Unknown SD/MMC/MS PRO 64GB          | 7         | 0.34%   |
| Seagate ST9250315AS 250GB           | 7         | 0.34%   |
| Seagate ST31000528AS 1TB            | 7         | 0.34%   |
| Samsung SSD 850 EVO 250GB           | 7         | 0.34%   |
| Samsung HM321HI 320GB               | 7         | 0.34%   |
| Samsung HM160HI 160GB               | 7         | 0.34%   |
| Crucial CT500MX500SSD1 500GB        | 7         | 0.34%   |
| Seagate ST9320325AS 320GB           | 6         | 0.29%   |
| Seagate ST9160314AS 160GB           | 6         | 0.29%   |
| Seagate ST1000DM003-1CH162 1TB      | 6         | 0.29%   |
| Seagate Expansion 1TB               | 6         | 0.29%   |
| SABRENT Disk 1TB                    | 6         | 0.29%   |
| Intel NVMe SSD Drive 512GB          | 6         | 0.29%   |
| Hitachi HTS547550A9E384 500GB       | 6         | 0.29%   |
| HGST HTS541010A9E680 1TB            | 6         | 0.29%   |
| WDC WD40EZRZ-00GXCB0 4TB            | 5         | 0.24%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 5         | 0.24%   |
| WDC WD3200BEVT-22ZCT0 320GB         | 5         | 0.24%   |
| WDC WD20EZRZ-00Z5HB0 2TB            | 5         | 0.24%   |
| WDC WD10JPVX-60JC3T0 1TB            | 5         | 0.24%   |
| Seagate ST9320423AS 320GB           | 5         | 0.24%   |
| Seagate ST9160821AS 160GB           | 5         | 0.24%   |
| Seagate ST500LT012-9WS142 500GB     | 5         | 0.24%   |
| SanDisk SDSSDA240G 240GB            | 5         | 0.24%   |
| SanDisk NVMe SSD Drive 500GB        | 5         | 0.24%   |
| Micron/Crucial NVMe SSD Drive 1TB   | 5         | 0.24%   |
| Kingston SV300S37A240G 240GB SSD    | 5         | 0.24%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 355       | 449    | 30.16%  |
| WDC                 | 340       | 417    | 28.89%  |
| Toshiba             | 156       | 187    | 13.25%  |
| Hitachi             | 139       | 161    | 11.81%  |
| Samsung Electronics | 69        | 86     | 5.86%   |
| HGST                | 37        | 45     | 3.14%   |
| Fujitsu             | 28        | 29     | 2.38%   |
| Maxtor              | 25        | 36     | 2.12%   |
| Unknown             | 7         | 11     | 0.59%   |
| SABRENT             | 7         | 7      | 0.59%   |
| Apple               | 7         | 7      | 0.59%   |
| ASMT                | 3         | 3      | 0.25%   |
| IBM/Hitachi         | 2         | 3      | 0.17%   |
| ExcelStor           | 1         | 1      | 0.08%   |
| ASMT109x            | 1         | 2      | 0.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 105       | 141    | 19.41%  |
| Kingston            | 91        | 105    | 16.82%  |
| SanDisk             | 55        | 66     | 10.17%  |
| Crucial             | 42        | 50     | 7.76%   |
| WDC                 | 27        | 33     | 4.99%   |
| Intel               | 25        | 29     | 4.62%   |
| China               | 16        | 17     | 2.96%   |
| A-DATA Technology   | 14        | 14     | 2.59%   |
| PNY                 | 13        | 17     | 2.4%    |
| Toshiba             | 10        | 11     | 1.85%   |
| SK hynix            | 10        | 14     | 1.85%   |
| Transcend           | 9         | 12     | 1.66%   |
| OCZ                 | 9         | 10     | 1.66%   |
| Intenso             | 9         | 11     | 1.66%   |
| SPCC                | 8         | 9      | 1.48%   |
| Patriot             | 8         | 14     | 1.48%   |
| Micron Technology   | 8         | 10     | 1.48%   |
| LITEON              | 8         | 11     | 1.48%   |
| Apple               | 6         | 6      | 1.11%   |
| Corsair             | 5         | 6      | 0.92%   |
| Team                | 4         | 4      | 0.74%   |
| TCSUNBOW            | 4         | 4      | 0.74%   |
| LITEONIT            | 4         | 4      | 0.74%   |
| Plextor             | 3         | 3      | 0.55%   |
| Leven               | 3         | 3      | 0.55%   |
| Hewlett-Packard     | 3         | 3      | 0.55%   |
| GOODRAM             | 3         | 3      | 0.55%   |
| Apacer              | 3         | 3      | 0.55%   |
| Verbatim            | 2         | 2      | 0.37%   |
| TO Exter            | 2         | 3      | 0.37%   |
| Pioneer             | 2         | 2      | 0.37%   |
| OWC                 | 2         | 2      | 0.37%   |
| Maxtor              | 2         | 2      | 0.37%   |
| KingDian            | 2         | 2      | 0.37%   |
| Gigabyte Technology | 2         | 8      | 0.37%   |
| Zheino              | 1         | 1      | 0.18%   |
| USB30               | 1         | 1      | 0.18%   |
| USB3.0              | 1         | 1      | 0.18%   |
| Unknown             | 1         | 1      | 0.18%   |
| TSA                 | 1         | 1      | 0.18%   |
| TrekStor            | 1         | 1      | 0.18%   |
| Seagate             | 1         | 1      | 0.18%   |
| S3+                 | 1         | 1      | 0.18%   |
| PNY USB             | 1         | 1      | 0.18%   |
| Pacific Sun         | 1         | 1      | 0.18%   |
| Mushkin             | 1         | 1      | 0.18%   |
| KingSpec            | 1         | 1      | 0.18%   |
| Kingmax             | 1         | 1      | 0.18%   |
| Integral            | 1         | 1      | 0.18%   |
| Hikvision           | 1         | 1      | 0.18%   |
| EMTEC               | 1         | 1      | 0.18%   |
| Drevo               | 1         | 1      | 0.18%   |
| Dogfish             | 1         | 1      | 0.18%   |
| BIWIN               | 1         | 1      | 0.18%   |
| BHT                 | 1         | 1      | 0.18%   |
| AS201               | 1         | 1      | 0.18%   |
| AMD-RAID            | 1         | 2      | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1052      | 1444   | 58.15%  |
| SSD     | 495       | 657    | 27.36%  |
| NVMe    | 120       | 158    | 6.63%   |
| MMC     | 111       | 156    | 6.14%   |
| Unknown | 31        | 37     | 1.71%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1402      | 2062   | 83.11%  |
| NVMe | 116       | 150    | 6.88%   |
| MMC  | 111       | 156    | 6.58%   |
| SAS  | 58        | 84     | 3.44%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1155      | 1524   | 73.47%  |
| 0.51-1.0   | 333       | 443    | 21.18%  |
| 1.01-2.0   | 51        | 77     | 3.24%   |
| 3.01-4.0   | 19        | 37     | 1.21%   |
| 2.01-3.0   | 7         | 12     | 0.45%   |
| 4.01-10.0  | 7         | 8      | 0.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 541       | 33.77%  |
| 251-500        | 381       | 23.78%  |
| 51-100         | 197       | 12.3%   |
| 501-1000       | 170       | 10.61%  |
| 21-50          | 118       | 7.37%   |
| 1-20           | 71        | 4.43%   |
| 1001-2000      | 68        | 4.24%   |
| More than 3000 | 31        | 1.94%   |
| 2001-3000      | 20        | 1.25%   |
| Unknown        | 5         | 0.31%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1002      | 60.62%  |
| 21-50          | 254       | 15.37%  |
| 51-100         | 138       | 8.35%   |
| 101-250        | 115       | 6.96%   |
| 251-500        | 66        | 3.99%   |
| 501-1000       | 31        | 1.88%   |
| 1001-2000      | 27        | 1.63%   |
| More than 3000 | 11        | 0.67%   |
| Unknown        | 5         | 0.3%    |
| 2001-3000      | 4         | 0.24%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                           | 2         | 2      | 16.67%  |
| WDC WD5000AAKS-00V1A0 500GB                         | 1         | 1      | 8.33%   |
| WDC WD3200BPVT-55ZEST0 320GB                        | 1         | 1      | 8.33%   |
| Toshiba MK5061GSY 500GB                             | 1         | 1      | 8.33%   |
| Seagate ST9320325AS 320GB                           | 1         | 1      | 8.33%   |
| Seagate ST9160314AS 160GB                           | 1         | 1      | 8.33%   |
| Seagate ST9120822AS 120GB                           | 1         | 1      | 8.33%   |
| Seagate ST500LT012-9WS142 500GB                     | 1         | 1      | 8.33%   |
| Micron Technology MTFDDAV256TBN-1AR15ABHA 256GB SSD | 1         | 1      | 8.33%   |
| LITEON CV8-8E128-HP 128GB SSD                       | 1         | 1      | 8.33%   |
| Hitachi HTS545050B9A300 500GB                       | 1         | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 6         | 6      | 50%     |
| WDC               | 2         | 2      | 16.67%  |
| Toshiba           | 1         | 1      | 8.33%   |
| Micron Technology | 1         | 1      | 8.33%   |
| LITEON            | 1         | 1      | 8.33%   |
| Hitachi           | 1         | 1      | 8.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 6      | 60%     |
| WDC     | 2         | 2      | 20%     |
| Toshiba | 1         | 1      | 10%     |
| Hitachi | 1         | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 10     | 83.33%  |
| SSD  | 2         | 2      | 16.67%  |

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
| Detected | 1514      | 2397   | 97.18%  |
| Works    | 32        | 43     | 2.05%   |
| Malfunc  | 12        | 12     | 0.77%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1095      | 65.33%  |
| AMD                              | 270       | 16.11%  |
| Nvidia                           | 70        | 4.18%   |
| Samsung Electronics              | 46        | 2.74%   |
| JMicron Technology               | 30        | 1.79%   |
| Silicon Integrated Systems [SiS] | 28        | 1.67%   |
| VIA Technologies                 | 23        | 1.37%   |
| SanDisk                          | 18        | 1.07%   |
| Marvell Technology Group         | 18        | 1.07%   |
| Phison Electronics               | 16        | 0.95%   |
| ASMedia Technology               | 15        | 0.89%   |
| Micron/Crucial Technology        | 8         | 0.48%   |
| Kingston Technology Company      | 8         | 0.48%   |
| Toshiba America Info Systems     | 7         | 0.42%   |
| SK hynix                         | 3         | 0.18%   |
| Silicon Image                    | 3         | 0.18%   |
| Broadcom / LSI                   | 3         | 0.18%   |
| Union Memory (Shenzhen)          | 2         | 0.12%   |
| Silicon Motion                   | 2         | 0.12%   |
| Micron Technology                | 2         | 0.12%   |
| Realtek Semiconductor            | 1         | 0.06%   |
| Promise Technology               | 1         | 0.06%   |
| OCZ Technology Group             | 1         | 0.06%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.06%   |
| KIOXIA                           | 1         | 0.06%   |
| Hewlett-Packard                  | 1         | 0.06%   |
| Apple                            | 1         | 0.06%   |
| ADATA Technology                 | 1         | 0.06%   |
| Adaptec                          | 1         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 147       | 6.87%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 90        | 4.2%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 75        | 3.5%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 71        | 3.32%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 70        | 3.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 70        | 3.27%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 69        | 3.22%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 59        | 2.76%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 59        | 2.76%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 52        | 2.43%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 50        | 2.34%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 48        | 2.24%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 41        | 1.91%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 38        | 1.77%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 36        | 1.68%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 36        | 1.68%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 35        | 1.63%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 29        | 1.35%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 29        | 1.35%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                    | 28        | 1.31%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 26        | 1.21%   |
| Intel SATA Controller [RAID mode]                                                       | 25        | 1.17%   |
| Nvidia MCP61 SATA Controller                                                            | 24        | 1.12%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 24        | 1.12%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                             | 21        | 0.98%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 20        | 0.93%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 20        | 0.93%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 18        | 0.84%   |
| Nvidia MCP61 IDE                                                                        | 17        | 0.79%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 17        | 0.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 17        | 0.79%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 17        | 0.79%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 16        | 0.75%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                            | 16        | 0.75%   |
| AMD 400 Series Chipset SATA Controller                                                  | 16        | 0.75%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 15        | 0.7%    |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                                | 15        | 0.7%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 13        | 0.61%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 13        | 0.61%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 13        | 0.61%   |
| JMicron JMB368 IDE controller                                                           | 12        | 0.56%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 12        | 0.56%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 12        | 0.56%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 12        | 0.56%   |
| AMD IXP SB4x0 IDE Controller                                                            | 12        | 0.56%   |
| AMD FCH IDE Controller                                                                  | 12        | 0.56%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 11        | 0.51%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 11        | 0.51%   |
| Intel 82801FBM (ICH6M) SATA Controller                                                  | 11        | 0.51%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 11        | 0.51%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 11        | 0.51%   |
| Phison E12 NVMe Controller                                                              | 10        | 0.47%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 10        | 0.47%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 10        | 0.47%   |
| Intel 82801EB/ER (ICH5/ICH5R) IDE Controller                                            | 10        | 0.47%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 10        | 0.47%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 9         | 0.42%   |
| Nvidia MCP79 AHCI Controller                                                            | 9         | 0.42%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 9         | 0.42%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 9         | 0.42%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1033      | 57.77%  |
| IDE  | 535       | 29.92%  |
| NVMe | 118       | 6.6%    |
| RAID | 98        | 5.48%   |
| SAS  | 2         | 0.11%   |
| SCSI | 2         | 0.11%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 1228      | 78.87%  |
| AMD          | 328       | 21.07%  |
| CentaurHauls | 1         | 0.06%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 23        | 1.47%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 15        | 0.96%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 14        | 0.9%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 13        | 0.83%   |
| Intel Pentium 4 CPU 3.00GHz                   | 12        | 0.77%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 12        | 0.77%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 12        | 0.77%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 12        | 0.77%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 12        | 0.77%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 11        | 0.7%    |
| Intel Celeron CPU N3350 @ 1.10GHz             | 11        | 0.7%    |
| Intel Atom CPU N455 @ 1.66GHz                 | 11        | 0.7%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 9         | 0.58%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 9         | 0.58%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 9         | 0.58%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz          | 9         | 0.58%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 9         | 0.58%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 8         | 0.51%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 8         | 0.51%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 8         | 0.51%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 8         | 0.51%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 8         | 0.51%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 7         | 0.45%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz   | 7         | 0.45%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz        | 7         | 0.45%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 7         | 0.45%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 7         | 0.45%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 7         | 0.45%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 7         | 0.45%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 7         | 0.45%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 7         | 0.45%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 7         | 0.45%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 7         | 0.45%   |
| Intel Core 2 Duo CPU T6400 @ 2.00GHz          | 7         | 0.45%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 7         | 0.45%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 7         | 0.45%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 7         | 0.45%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 7         | 0.45%   |
| AMD FX-6300 Six-Core Processor                | 7         | 0.45%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz   | 6         | 0.38%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 6         | 0.38%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 6         | 0.38%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 6         | 0.38%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 6         | 0.38%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 6         | 0.38%   |
| Intel Core 2 Duo CPU T6500 @ 2.10GHz          | 6         | 0.38%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 6         | 0.38%   |
| Intel Celeron CPU 550 @ 2.00GHz               | 6         | 0.38%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 6         | 0.38%   |
| AMD E-450 APU with Radeon HD Graphics         | 6         | 0.38%   |
| AMD C-50 Processor                            | 6         | 0.38%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 5         | 0.32%   |
| Intel Pentium Dual CPU E2220 @ 2.40GHz        | 5         | 0.32%   |
| Intel Genuine CPU T2050 @ 1.60GHz             | 5         | 0.32%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 5         | 0.32%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 5         | 0.32%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 5         | 0.32%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 5         | 0.32%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 5         | 0.32%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 5         | 0.32%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 249       | 15.96%  |
| Intel Core i7           | 173       | 11.09%  |
| Intel Core 2 Duo        | 155       | 9.94%   |
| Intel Core i3           | 131       | 8.4%    |
| Intel Celeron           | 104       | 6.67%   |
| Intel Atom              | 95        | 6.09%   |
| Intel Pentium           | 50        | 3.21%   |
| Intel Pentium Dual-Core | 43        | 2.76%   |
| Intel Pentium Dual      | 35        | 2.24%   |
| Intel Genuine           | 30        | 1.92%   |
| Intel Core 2 Quad       | 29        | 1.86%   |
| AMD Ryzen 5             | 27        | 1.73%   |
| Intel Core 2            | 25        | 1.6%    |
| AMD A4                  | 25        | 1.6%    |
| Intel Xeon              | 24        | 1.54%   |
| Intel Pentium 4         | 24        | 1.54%   |
| AMD Athlon 64 X2        | 23        | 1.47%   |
| AMD Ryzen 7             | 22        | 1.41%   |
| AMD A6                  | 22        | 1.41%   |
| AMD Ryzen 3             | 20        | 1.28%   |
| AMD FX                  | 20        | 1.28%   |
| Intel Pentium M         | 18        | 1.15%   |
| Intel Celeron M         | 17        | 1.09%   |
| AMD A8                  | 15        | 0.96%   |
| AMD E                   | 13        | 0.83%   |
| AMD Athlon II X2        | 13        | 0.83%   |
| AMD Sempron             | 10        | 0.64%   |
| AMD E1                  | 9         | 0.58%   |
| AMD A10                 | 9         | 0.58%   |
| Other                   | 8         | 0.51%   |
| AMD Turion 64 X2 Mobile | 8         | 0.51%   |
| AMD Phenom II X4        | 8         | 0.51%   |
| AMD Turion 64 Mobile    | 7         | 0.45%   |
| AMD Athlon              | 7         | 0.45%   |
| AMD C-50                | 6         | 0.38%   |
| AMD Athlon 64           | 6         | 0.38%   |
| Intel Pentium D         | 5         | 0.32%   |
| Intel Celeron Dual-Core | 5         | 0.32%   |
| Intel Core Duo          | 4         | 0.26%   |
| AMD Phenom II X2        | 4         | 0.26%   |
| AMD Mobile Sempron      | 4         | 0.26%   |
| AMD E2                  | 4         | 0.26%   |
| AMD C-60                | 4         | 0.26%   |
| AMD Athlon X2           | 4         | 0.26%   |
| AMD Athlon II X4        | 4         | 0.26%   |
| Intel Core 2 Extreme    | 3         | 0.19%   |
| AMD Ryzen 9             | 3         | 0.19%   |
| AMD Phenom              | 3         | 0.19%   |
| AMD Athlon II X3        | 3         | 0.19%   |
| Intel Core i9           | 2         | 0.13%   |
| AMD Turion Dual-Core    | 2         | 0.13%   |
| AMD Ryzen Threadripper  | 2         | 0.13%   |
| AMD Phenom II X6        | 2         | 0.13%   |
| AMD Phenom II           | 2         | 0.13%   |
| AMD Athlon II           | 2         | 0.13%   |
| AMD Athlon Dual Core    | 2         | 0.13%   |
| Intel Pentium Silver    | 1         | 0.06%   |
| Intel Pentium Gold      | 1         | 0.06%   |
| Intel Core m7           | 1         | 0.06%   |
| Intel Core m3           | 1         | 0.06%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 909       | 58.23%  |
| 4      | 379       | 24.28%  |
| 1      | 184       | 11.79%  |
| 6      | 39        | 2.5%    |
| 8      | 32        | 2.05%   |
| 3      | 12        | 0.77%   |
| 16     | 2         | 0.13%   |
| 10     | 2         | 0.13%   |
| 20     | 1         | 0.06%   |
| 12     | 1         | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 1552      | 99.68%  |
| 2      | 5         | 0.32%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 860       | 55.23%  |
| 2      | 697       | 44.77%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1457      | 93.52%  |
| 32-bit         | 99        | 6.35%   |
| Unknown        | 2         | 0.13%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 171       | 10.82%  |
| 0x206a7    | 140       | 8.86%   |
| 0x1067a    | 134       | 8.48%   |
| 0x306a9    | 77        | 4.87%   |
| 0x6fd      | 72        | 4.56%   |
| 0x306c3    | 72        | 4.56%   |
| 0x40651    | 44        | 2.78%   |
| 0x20655    | 40        | 2.53%   |
| 0x406e3    | 30        | 1.9%    |
| 0x10676    | 29        | 1.84%   |
| 0x406c4    | 27        | 1.71%   |
| 0x106ca    | 27        | 1.71%   |
| 0x6fb      | 26        | 1.65%   |
| 0x010000c8 | 26        | 1.65%   |
| 0x806e9    | 25        | 1.58%   |
| 0x6e8      | 23        | 1.46%   |
| 0x306d4    | 23        | 1.46%   |
| 0x806ea    | 21        | 1.33%   |
| 0x6f6      | 21        | 1.33%   |
| 0x6d8      | 21        | 1.33%   |
| 0x30678    | 21        | 1.33%   |
| 0x06001119 | 21        | 1.33%   |
| 0x106c2    | 20        | 1.27%   |
| 0x10661    | 19        | 1.2%    |
| 0x906e9    | 18        | 1.14%   |
| 0x506e3    | 18        | 1.14%   |
| 0x406c3    | 17        | 1.08%   |
| 0x20652    | 16        | 1.01%   |
| 0x06000852 | 16        | 1.01%   |
| 0x906ea    | 15        | 0.95%   |
| 0x806ec    | 15        | 0.95%   |
| 0x506c9    | 15        | 0.95%   |
| 0x06006705 | 15        | 0.95%   |
| 0x05000119 | 15        | 0.95%   |
| 0x0700010f | 12        | 0.76%   |
| 0x6ec      | 11        | 0.7%    |
| 0x05000029 | 11        | 0.7%    |
| 0x03000027 | 11        | 0.7%    |
| 0x08108109 | 10        | 0.63%   |
| 0xf41      | 9         | 0.57%   |
| 0x0810100b | 9         | 0.57%   |
| 0x706a1    | 8         | 0.51%   |
| 0x08108102 | 8         | 0.51%   |
| 0x0800820d | 8         | 0.51%   |
| 0x06003106 | 8         | 0.51%   |
| 0x6f2      | 7         | 0.44%   |
| 0x30673    | 7         | 0.44%   |
| 0x106e5    | 7         | 0.44%   |
| 0xf43      | 6         | 0.38%   |
| 0x806eb    | 6         | 0.38%   |
| 0x906ed    | 5         | 0.32%   |
| 0x106a5    | 5         | 0.32%   |
| 0x07030105 | 5         | 0.32%   |
| 0x010000db | 5         | 0.32%   |
| 0xa0655    | 4         | 0.25%   |
| 0x706e5    | 4         | 0.25%   |
| 0x6fa      | 4         | 0.25%   |
| 0x206c2    | 4         | 0.25%   |
| 0x0800820c | 4         | 0.25%   |
| 0x0600063e | 4         | 0.25%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Penryn          | 177       | 11.35%  |
| Core            | 156       | 10.01%  |
| SandyBridge     | 143       | 9.17%   |
| Haswell         | 126       | 8.08%   |
| KabyLake        | 114       | 7.31%   |
| Silvermont      | 89        | 5.71%   |
| IvyBridge       | 85        | 5.45%   |
| Westmere        | 66        | 4.23%   |
| K8 Hammer       | 59        | 3.78%   |
| P6              | 58        | 3.72%   |
| Skylake         | 53        | 3.4%    |
| Bonnell         | 51        | 3.27%   |
| K10             | 48        | 3.08%   |
| Piledriver      | 39        | 2.5%    |
| Zen+            | 34        | 2.18%   |
| NetBurst        | 34        | 2.18%   |
| Bobcat          | 27        | 1.73%   |
| Broadwell       | 24        | 1.54%   |
| Zen             | 23        | 1.48%   |
| Excavator       | 21        | 1.35%   |
| Zen 2           | 17        | 1.09%   |
| Goldmont        | 16        | 1.03%   |
| Jaguar          | 15        | 0.96%   |
| Nehalem         | 14        | 0.9%    |
| K10 Llano       | 11        | 0.71%   |
| Puma            | 10        | 0.64%   |
| Goldmont plus   | 10        | 0.64%   |
| Steamroller     | 9         | 0.58%   |
| K8 & K10 hybrid | 8         | 0.51%   |
| CometLake       | 7         | 0.45%   |
| Unknown         | 5         | 0.32%   |
| IceLake         | 4         | 0.26%   |
| Bulldozer       | 4         | 0.26%   |
| Zen 3           | 2         | 0.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 891       | 51.53%  |
| AMD                              | 407       | 23.54%  |
| Nvidia                           | 392       | 22.67%  |
| Silicon Integrated Systems [SiS] | 23        | 1.33%   |
| VIA Technologies                 | 11        | 0.64%   |
| Matrox Electronics Systems       | 2         | 0.12%   |
| Trident Microsystems             | 1         | 0.06%   |
| Silicon Motion                   | 1         | 0.06%   |
| ASPEED Technology                | 1         | 0.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 106       | 5.7%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 60        | 3.22%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 58        | 3.12%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 54        | 2.9%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 50        | 2.69%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 46        | 2.47%   |
| Intel Core Processor Integrated Graphics Controller                                      | 46        | 2.47%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 42        | 2.26%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 42        | 2.26%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 35        | 1.88%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 32        | 1.72%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 31        | 1.67%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 30        | 1.61%   |
| Intel HD Graphics 620                                                                    | 29        | 1.56%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 28        | 1.5%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 28        | 1.5%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 24        | 1.29%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 22        | 1.18%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 21        | 1.13%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 20        | 1.07%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 19        | 1.02%   |
| Intel HD Graphics 5500                                                                   | 19        | 1.02%   |
| Intel UHD Graphics 620                                                                   | 18        | 0.97%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 18        | 0.97%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 18        | 0.97%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 14        | 0.75%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 14        | 0.75%   |
| Intel HD Graphics 500                                                                    | 13        | 0.7%    |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 13        | 0.7%    |
| Intel HD Graphics 630                                                                    | 12        | 0.64%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 12        | 0.64%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 12        | 0.64%   |
| Nvidia GT218 [GeForce 210]                                                               | 11        | 0.59%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 11        | 0.59%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 10        | 0.54%   |
| Intel HD Graphics 530                                                                    | 10        | 0.54%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 10        | 0.54%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 9         | 0.48%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 9         | 0.48%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 9         | 0.48%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 9         | 0.48%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 8         | 0.43%   |
| AMD RS780L [Radeon 3000]                                                                 | 8         | 0.43%   |
| AMD Renoir                                                                               | 8         | 0.43%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 7         | 0.38%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 7         | 0.38%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 7         | 0.38%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 7         | 0.38%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 7         | 0.38%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 7         | 0.38%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 7         | 0.38%   |
| AMD Wrestler [Radeon HD 6250]                                                            | 7         | 0.38%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 6         | 0.32%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 6         | 0.32%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 6         | 0.32%   |
| Intel 82865G Integrated Graphics Controller                                              | 6         | 0.32%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 6         | 0.32%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 6         | 0.32%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                        | 6         | 0.32%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 6         | 0.32%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 732       | 46.83%  |
| 1 x AMD                  | 316       | 20.22%  |
| 1 x Nvidia               | 284       | 18.17%  |
| Intel + Nvidia           | 98        | 6.27%   |
| Intel + AMD              | 51        | 3.26%   |
| 2 x AMD                  | 32        | 2.05%   |
| 1 x SiS                  | 23        | 1.47%   |
| 1 x VIA                  | 11        | 0.7%    |
| AMD + Nvidia             | 6         | 0.38%   |
| 2 x Nvidia               | 3         | 0.19%   |
| Other                    | 2         | 0.13%   |
| 1 x Matrox               | 2         | 0.13%   |
| 1 x Trident Microsystems | 1         | 0.06%   |
| Nvidia + Silicon Motion  | 1         | 0.06%   |
| Nvidia + ASPEED          | 1         | 0.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1267      | 80.8%   |
| Proprietary | 178       | 11.35%  |
| Unknown     | 123       | 7.84%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 926       | 58.68%  |
| 0.01-0.5   | 293       | 18.57%  |
| 0.51-1.0   | 142       | 9%      |
| 1.01-2.0   | 135       | 8.56%   |
| 3.01-4.0   | 45        | 2.85%   |
| 7.01-8.0   | 23        | 1.46%   |
| 5.01-6.0   | 9         | 0.57%   |
| 2.01-3.0   | 3         | 0.19%   |
| 4.01-5.0   | 1         | 0.06%   |
| 8.01-16.0  | 1         | 0.06%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 226       | 15.49%  |
| AU Optronics            | 191       | 13.09%  |
| LG Display              | 147       | 10.08%  |
| Chimei Innolux          | 89        | 6.1%    |
| BOE                     | 79        | 5.41%   |
| Goldstar                | 61        | 4.18%   |
| Dell                    | 61        | 4.18%   |
| Hewlett-Packard         | 53        | 3.63%   |
| Chi Mei Optoelectronics | 51        | 3.5%    |
| Acer                    | 41        | 2.81%   |
| LG Philips              | 38        | 2.6%    |
| AOC                     | 31        | 2.12%   |
| Apple                   | 26        | 1.78%   |
| Ancor Communications    | 24        | 1.64%   |
| Philips                 | 22        | 1.51%   |
| InfoVision              | 22        | 1.51%   |
| BenQ                    | 20        | 1.37%   |
| Lenovo                  | 19        | 1.3%    |
| Toshiba                 | 16        | 1.1%    |
| ViewSonic               | 15        | 1.03%   |
| Unknown                 | 14        | 0.96%   |
| LG Electronics          | 13        | 0.89%   |
| HannStar                | 13        | 0.89%   |
| Sharp                   | 12        | 0.82%   |
| CPT                     | 9         | 0.62%   |
| Quanta Display          | 8         | 0.55%   |
| Vizio                   | 7         | 0.48%   |
| Sony                    | 7         | 0.48%   |
| Seiko/Epson             | 7         | 0.48%   |
| Eizo                    | 7         | 0.48%   |
| PANDA                   | 6         | 0.41%   |
| Iiyama                  | 6         | 0.41%   |
| InnoLux Display         | 5         | 0.34%   |
| Panasonic               | 4         | 0.27%   |
| NEC Computers           | 4         | 0.27%   |
| LGD                     | 4         | 0.27%   |
| Insignia                | 4         | 0.27%   |
| Gateway                 | 4         | 0.27%   |
| CVT                     | 4         | 0.27%   |
| ___                     | 3         | 0.21%   |
| VIZ                     | 3         | 0.21%   |
| Sceptre Tech            | 3         | 0.21%   |
| Nvidia                  | 3         | 0.21%   |
| MSI                     | 3         | 0.21%   |
| KTC                     | 3         | 0.21%   |
| Idek Iiyama             | 3         | 0.21%   |
| Fujitsu Siemens         | 3         | 0.21%   |
| ASUSTek Computer        | 3         | 0.21%   |
| TCL                     | 2         | 0.14%   |
| SKY                     | 2         | 0.14%   |
| SANYO                   | 2         | 0.14%   |
| Medion                  | 2         | 0.14%   |
| IBM                     | 2         | 0.14%   |
| Envision                | 2         | 0.14%   |
| Daewoo                  | 2         | 0.14%   |
| CHR                     | 2         | 0.14%   |
| Xiaomi                  | 1         | 0.07%   |
| Vita                    | 1         | 0.07%   |
| Vestel Elektronik       | 1         | 0.07%   |
| Vestel                  | 1         | 0.07%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 15        | 1%      |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 13        | 0.87%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 9         | 0.6%    |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 9         | 0.6%    |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 7         | 0.47%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                 | 7         | 0.47%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch              | 6         | 0.4%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 6         | 0.4%    |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 6         | 0.4%    |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 5         | 0.33%   |
| Samsung Electronics LCD Monitor SEC3633 1280x800 331x207mm 15.4-inch     | 5         | 0.33%   |
| LG Philips LCD Monitor LPLDB00 1280x800 331x207mm 15.4-inch              | 5         | 0.33%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 5         | 0.33%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 5         | 0.33%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch                  | 5         | 0.33%   |
| Chi Mei Optoelectronics LCD Monitor CMO1007 1024x600 222x125mm 10.0-inch | 5         | 0.33%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 5         | 0.33%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 5         | 0.33%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 5         | 0.33%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 5         | 0.33%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 4         | 0.27%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch     | 4         | 0.27%   |
| Philips PHL 242M8 PHLC253 1920x1080 527x296mm 23.8-inch                  | 4         | 0.27%   |
| LG Philips LCD Monitor LPLBC00 1280x800 331x207mm 15.4-inch              | 4         | 0.27%   |
| InfoVision LCD Monitor IVO057A 1366x768 309x174mm 14.0-inch              | 4         | 0.27%   |
| InfoVision LCD Monitor IVO0489 1366x768 256x144mm 11.6-inch              | 4         | 0.27%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 4         | 0.27%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch          | 4         | 0.27%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 4         | 0.27%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch           | 4         | 0.27%   |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch            | 4         | 0.27%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 4         | 0.27%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 4         | 0.27%   |
| AU Optronics LCD Monitor AUO193C 1366x768 309x173mm 13.9-inch            | 4         | 0.27%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 4         | 0.27%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 331x207mm 15.4-inch     | 3         | 0.2%    |
| Samsung Electronics LCD Monitor SEC4E45 1280x800 331x207mm 15.4-inch     | 3         | 0.2%    |
| Samsung Electronics LCD Monitor SEC4C42 1280x800 303x190mm 14.1-inch     | 3         | 0.2%    |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch     | 3         | 0.2%    |
| Samsung Electronics LCD Monitor SEC4351 1366x768 340x190mm 15.3-inch     | 3         | 0.2%    |
| Samsung Electronics LCD Monitor SEC3358 1280x800 331x207mm 15.4-inch     | 3         | 0.2%    |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch     | 3         | 0.2%    |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 890x500mm 40.2-inch    | 3         | 0.2%    |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch              | 3         | 0.2%    |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch              | 3         | 0.2%    |
| LG Display LCD Monitor LGD0250 1366x768 345x194mm 15.6-inch              | 3         | 0.2%    |
| Lenovo LCD Monitor LEN40B0 1366x768 344x194mm 15.5-inch                  | 3         | 0.2%    |
| Hewlett-Packard 2009 HWP2827 1600x900 443x250mm 20.0-inch                | 3         | 0.2%    |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 3         | 0.2%    |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                         | 3         | 0.2%    |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 3         | 0.2%    |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch         | 3         | 0.2%    |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 3         | 0.2%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 3         | 0.2%    |
| Chimei Innolux LCD Monitor CMN1487 1366x768 309x173mm 13.9-inch          | 3         | 0.2%    |
| Chi Mei Optoelectronics LCD Monitor CMO1719 1600x900 382x215mm 17.3-inch | 3         | 0.2%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 3         | 0.2%    |
| Chi Mei Optoelectronics LCD Monitor CMO1526 1280x800 331x207mm 15.4-inch | 3         | 0.2%    |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 3         | 0.2%    |
| BOE LCD Monitor BOE0731 1366x768 256x144mm 11.6-inch                     | 3         | 0.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 445       | 30.77%  |
| 1920x1080 (FHD)    | 402       | 27.8%   |
| 1280x800 (WXGA)    | 111       | 7.68%   |
| 1600x900 (HD+)     | 92        | 6.36%   |
| 1280x1024 (SXGA)   | 60        | 4.15%   |
| 1440x900 (WXGA+)   | 58        | 4.01%   |
| 3840x2160 (4K)     | 37        | 2.56%   |
| 1680x1050 (WSXGA+) | 36        | 2.49%   |
| 1024x600           | 33        | 2.28%   |
| 1920x1200 (WUXGA)  | 29        | 2.01%   |
| 1360x768           | 24        | 1.66%   |
| 2560x1440 (QHD)    | 16        | 1.11%   |
| Unknown            | 16        | 1.11%   |
| 1024x768 (XGA)     | 13        | 0.9%    |
| 3840x1080          | 6         | 0.41%   |
| 3440x1440          | 6         | 0.41%   |
| 1920x540           | 6         | 0.41%   |
| 1280x768           | 6         | 0.41%   |
| 2560x1600          | 5         | 0.35%   |
| 2560x1080          | 5         | 0.35%   |
| 5760x1080          | 4         | 0.28%   |
| 2048x1152          | 3         | 0.21%   |
| 1400x1050          | 3         | 0.21%   |
| 1024x576           | 3         | 0.21%   |
| 5760x2160          | 2         | 0.14%   |
| 3200x1080          | 2         | 0.14%   |
| 1680x945           | 2         | 0.14%   |
| 1600x1200          | 2         | 0.14%   |
| 1152x864           | 2         | 0.14%   |
| 7680x1080          | 1         | 0.07%   |
| 6400x1440          | 1         | 0.07%   |
| 6400x1080          | 1         | 0.07%   |
| 5440x1080          | 1         | 0.07%   |
| 4480x1440          | 1         | 0.07%   |
| 3840x1200          | 1         | 0.07%   |
| 3600x1080          | 1         | 0.07%   |
| 3200x1800 (QHD+)   | 1         | 0.07%   |
| 2880x1800          | 1         | 0.07%   |
| 2736x1824          | 1         | 0.07%   |
| 2646x768           | 1         | 0.07%   |
| 2390x899           | 1         | 0.07%   |
| 2288x1287          | 1         | 0.07%   |
| 2160x1440          | 1         | 0.07%   |
| 1360x765           | 1         | 0.07%   |
| 1280x960           | 1         | 0.07%   |
| 1280x720 (HD)      | 1         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 436       | 30.01%  |
| Unknown | 133       | 9.15%   |
| 14      | 113       | 7.78%   |
| 13      | 110       | 7.57%   |
| 17      | 108       | 7.43%   |
| 21      | 58        | 3.99%   |
| 23      | 52        | 3.58%   |
| 18      | 52        | 3.58%   |
| 24      | 50        | 3.44%   |
| 27      | 47        | 3.23%   |
| 19      | 44        | 3.03%   |
| 11      | 38        | 2.62%   |
| 10      | 37        | 2.55%   |
| 20      | 28        | 1.93%   |
| 12      | 23        | 1.58%   |
| 22      | 21        | 1.45%   |
| 31      | 16        | 1.1%    |
| 34      | 11        | 0.76%   |
| 72      | 9         | 0.62%   |
| 26      | 8         | 0.55%   |
| 84      | 6         | 0.41%   |
| 54      | 6         | 0.41%   |
| 40      | 5         | 0.34%   |
| 52      | 3         | 0.21%   |
| 46      | 3         | 0.21%   |
| 42      | 3         | 0.21%   |
| 16      | 3         | 0.21%   |
| 8       | 3         | 0.21%   |
| 74      | 2         | 0.14%   |
| 65      | 2         | 0.14%   |
| 49      | 2         | 0.14%   |
| 44      | 2         | 0.14%   |
| 39      | 2         | 0.14%   |
| 33      | 2         | 0.14%   |
| 32      | 2         | 0.14%   |
| 29      | 2         | 0.14%   |
| 60      | 1         | 0.07%   |
| 59      | 1         | 0.07%   |
| 58      | 1         | 0.07%   |
| 55      | 1         | 0.07%   |
| 47      | 1         | 0.07%   |
| 43      | 1         | 0.07%   |
| 41      | 1         | 0.07%   |
| 37      | 1         | 0.07%   |
| 36      | 1         | 0.07%   |
| 30      | 1         | 0.07%   |
| 28      | 1         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 626       | 43.38%  |
| 401-500     | 177       | 12.27%  |
| 501-600     | 150       | 10.4%   |
| 201-300     | 140       | 9.7%    |
| Unknown     | 133       | 9.22%   |
| 351-400     | 124       | 8.59%   |
| 601-700     | 21        | 1.46%   |
| 1001-1500   | 21        | 1.46%   |
| 1501-2000   | 17        | 1.18%   |
| 701-800     | 16        | 1.11%   |
| 801-900     | 8         | 0.55%   |
| 901-1000    | 7         | 0.49%   |
| 101-200     | 3         | 0.21%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 935       | 68.1%   |
| 16/10   | 227       | 16.53%  |
| Unknown | 116       | 8.45%   |
| 5/4     | 52        | 3.79%   |
| 4/3     | 22        | 1.6%    |
| 21/9    | 10        | 0.73%   |
| 32/9    | 4         | 0.29%   |
| 3/2     | 4         | 0.29%   |
| 6/5     | 3         | 0.22%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 434       | 30.06%  |
| 81-90          | 186       | 12.88%  |
| 201-250        | 134       | 9.28%   |
| Unknown        | 133       | 9.21%   |
| 151-200        | 103       | 7.13%   |
| 141-150        | 69        | 4.78%   |
| 301-350        | 48        | 3.32%   |
| 121-130        | 47        | 3.25%   |
| 51-60          | 38        | 2.63%   |
| 41-50          | 37        | 2.56%   |
| 351-500        | 34        | 2.35%   |
| 131-140        | 34        | 2.35%   |
| More than 1000 | 31        | 2.15%   |
| 71-80          | 31        | 2.15%   |
| 251-300        | 29        | 2.01%   |
| 501-1000       | 23        | 1.59%   |
| 61-70          | 22        | 1.52%   |
| 91-100         | 6         | 0.42%   |
| 1-40           | 3         | 0.21%   |
| 111-120        | 2         | 0.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 508       | 35.85%  |
| 51-100        | 484       | 34.16%  |
| 121-160       | 220       | 15.53%  |
| Unknown       | 133       | 9.39%   |
| 1-50          | 36        | 2.54%   |
| 161-240       | 31        | 2.19%   |
| More than 240 | 5         | 0.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1318      | 83.1%   |
| 2     | 131       | 8.26%   |
| 0     | 123       | 7.76%   |
| 3     | 13        | 0.82%   |
| 4     | 1         | 0.06%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 811       | 32.23%  |
| Intel                                  | 543       | 21.58%  |
| Qualcomm Atheros                       | 356       | 14.15%  |
| Broadcom                               | 235       | 9.34%   |
| Broadcom Limited                       | 81        | 3.22%   |
| Marvell Technology Group               | 63        | 2.5%    |
| Nvidia                                 | 58        | 2.31%   |
| Ralink Technology                      | 50        | 1.99%   |
| Ralink                                 | 35        | 1.39%   |
| Silicon Integrated Systems [SiS]       | 27        | 1.07%   |
| VIA Technologies                       | 20        | 0.79%   |
| TP-Link                                | 20        | 0.79%   |
| D-Link                                 | 17        | 0.68%   |
| Samsung Electronics                    | 14        | 0.56%   |
| JMicron Technology                     | 13        | 0.52%   |
| D-Link System                          | 13        | 0.52%   |
| Xiaomi                                 | 12        | 0.48%   |
| NetGear                                | 11        | 0.44%   |
| Qualcomm Atheros Communications        | 10        | 0.4%    |
| ASUSTek Computer                       | 9         | 0.36%   |
| MediaTek                               | 8         | 0.32%   |
| Huawei Technologies                    | 8         | 0.32%   |
| Sierra Wireless                        | 7         | 0.28%   |
| Edimax Technology                      | 7         | 0.28%   |
| ASIX Electronics                       | 7         | 0.28%   |
| AMD                                    | 6         | 0.24%   |
| Motorola PCS                           | 5         | 0.2%    |
| Dell                                   | 5         | 0.2%    |
| OPPO Electronics                       | 4         | 0.16%   |
| Micro Star International               | 4         | 0.16%   |
| Hewlett-Packard                        | 4         | 0.16%   |
| DisplayLink                            | 4         | 0.16%   |
| Sitecom Europe                         | 3         | 0.12%   |
| Qualcomm                               | 3         | 0.12%   |
| Linksys                                | 3         | 0.12%   |
| Davicom Semiconductor                  | 3         | 0.12%   |
| Attansic Technology                    | 3         | 0.12%   |
| Aquantia                               | 3         | 0.12%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.08%   |
| Senao                                  | 2         | 0.08%   |
| Microsoft                              | 2         | 0.08%   |
| IMC Networks                           | 2         | 0.08%   |
| Gemtek                                 | 2         | 0.08%   |
| Belkin Components                      | 2         | 0.08%   |
| Apple                                  | 2         | 0.08%   |
| 802.11g Adapter [Linksys WUSB54GC v3]  | 2         | 0.08%   |
| ZyDAS                                  | 1         | 0.04%   |
| Toshiba                                | 1         | 0.04%   |
| T & A Mobile Phones                    | 1         | 0.04%   |
| Sundance Technology Inc / IC Plus      | 1         | 0.04%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.04%   |
| Qcom                                   | 1         | 0.04%   |
| Philips (or NXP)                       | 1         | 0.04%   |
| Motorola                               | 1         | 0.04%   |
| Microchip Technology                   | 1         | 0.04%   |
| LSI                                    | 1         | 0.04%   |
| Lite-On Technology                     | 1         | 0.04%   |
| GCT Semiconductor                      | 1         | 0.04%   |
| Ericsson Business Mobile Networks      | 1         | 0.04%   |
| Comneon                                | 1         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 458       | 15.62%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 191       | 6.51%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 66        | 2.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 55        | 1.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 47        | 1.6%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 44        | 1.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 42        | 1.43%   |
| Intel Wireless 7260                                                     | 40        | 1.36%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 37        | 1.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 37        | 1.26%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 37        | 1.26%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 35        | 1.19%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 34        | 1.16%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 33        | 1.13%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 27        | 0.92%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 25        | 0.85%   |
| Intel Ethernet Connection I217-LM                                       | 25        | 0.85%   |
| Ralink MT7601U Wireless Adapter                                         | 24        | 0.82%   |
| Intel Wireless 3165                                                     | 24        | 0.82%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 23        | 0.78%   |
| Nvidia MCP61 Ethernet                                                   | 22        | 0.75%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 21        | 0.72%   |
| Intel Wireless 8265 / 8275                                              | 21        | 0.72%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 20        | 0.68%   |
| Intel WiFi Link 5100                                                    | 19        | 0.65%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 17        | 0.58%   |
| Intel Wireless 7265                                                     | 17        | 0.58%   |
| Intel Wi-Fi 6 AX200                                                     | 17        | 0.58%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 17        | 0.58%   |
| Broadcom BCM43142 802.11b/g/n                                           | 17        | 0.58%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 17        | 0.58%   |
| VIA VT6102/VT6103 [Rhine-II]                                            | 16        | 0.55%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller        | 15        | 0.51%   |
| Intel 82579V Gigabit Network Connection                                 | 15        | 0.51%   |
| Broadcom BCM4401-B0 100Base-TX                                          | 15        | 0.51%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 14        | 0.48%   |
| Intel Wireless 8260                                                     | 14        | 0.48%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 14        | 0.48%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 13        | 0.44%   |
| Intel Wireless 3160                                                     | 13        | 0.44%   |
| Intel Ethernet Connection I218-LM                                       | 13        | 0.44%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 13        | 0.44%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller     | 13        | 0.44%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 12        | 0.41%   |
| Realtek 802.11ac NIC                                                    | 12        | 0.41%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 12        | 0.41%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 12        | 0.41%   |
| Intel I211 Gigabit Network Connection                                   | 12        | 0.41%   |
| Intel Centrino Wireless-N 2230                                          | 12        | 0.41%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 11        | 0.38%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 11        | 0.38%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                              | 11        | 0.38%   |
| Intel Centrino Ultimate-N 6300                                          | 11        | 0.38%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 11        | 0.38%   |
| Intel 82567LM-3 Gigabit Network Connection                              | 11        | 0.38%   |
| Intel 82567LM Gigabit Network Connection                                | 11        | 0.38%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 10        | 0.34%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 10        | 0.34%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 10        | 0.34%   |
| Qualcomm Atheros AR9271 802.11n                                         | 10        | 0.34%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 385       | 28.39%  |
| Qualcomm Atheros                      | 285       | 21.02%  |
| Realtek Semiconductor                 | 262       | 19.32%  |
| Broadcom                              | 157       | 11.58%  |
| Broadcom Limited                      | 54        | 3.98%   |
| Ralink Technology                     | 50        | 3.69%   |
| Ralink                                | 35        | 2.58%   |
| TP-Link                               | 19        | 1.4%    |
| D-Link                                | 17        | 1.25%   |
| D-Link System                         | 11        | 0.81%   |
| Qualcomm Atheros Communications       | 10        | 0.74%   |
| NetGear                               | 10        | 0.74%   |
| ASUSTek Computer                      | 8         | 0.59%   |
| Sierra Wireless                       | 7         | 0.52%   |
| Edimax Technology                     | 7         | 0.52%   |
| Micro Star International              | 4         | 0.29%   |
| Marvell Technology Group              | 4         | 0.29%   |
| Sitecom Europe                        | 3         | 0.22%   |
| MediaTek                              | 3         | 0.22%   |
| Linksys                               | 3         | 0.22%   |
| Senao                                 | 2         | 0.15%   |
| Microsoft                             | 2         | 0.15%   |
| IMC Networks                          | 2         | 0.15%   |
| Hewlett-Packard                       | 2         | 0.15%   |
| Gemtek                                | 2         | 0.15%   |
| Dell                                  | 2         | 0.15%   |
| Belkin Components                     | 2         | 0.15%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.15%   |
| ZyDAS                                 | 1         | 0.07%   |
| Xiaomi                                | 1         | 0.07%   |
| Qcom                                  | 1         | 0.07%   |
| Philips (or NXP)                      | 1         | 0.07%   |
| Lite-On Technology                    | 1         | 0.07%   |
| Comneon                               | 1         | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 66        | 4.82%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 47        | 3.44%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 44        | 3.22%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 42        | 3.07%   |
| Intel Wireless 7260                                                         | 40        | 2.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                  | 37        | 2.7%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)     | 37        | 2.7%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                         | 35        | 2.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 34        | 2.49%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                           | 33        | 2.41%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 27        | 1.97%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 25        | 1.83%   |
| Ralink MT7601U Wireless Adapter                                             | 24        | 1.75%   |
| Intel Wireless 3165                                                         | 24        | 1.75%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 23        | 1.68%   |
| Intel Wireless 8265 / 8275                                                  | 21        | 1.54%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 20        | 1.46%   |
| Intel WiFi Link 5100                                                        | 19        | 1.39%   |
| Intel Wireless 7265                                                         | 17        | 1.24%   |
| Intel Wi-Fi 6 AX200                                                         | 17        | 1.24%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection               | 17        | 1.24%   |
| Broadcom BCM43142 802.11b/g/n                                               | 17        | 1.24%   |
| Broadcom BCM4311 802.11b/g WLAN                                             | 17        | 1.24%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                          | 14        | 1.02%   |
| Intel Wireless 8260                                                         | 14        | 1.02%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                   | 14        | 1.02%   |
| Intel Wireless 3160                                                         | 13        | 0.95%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                | 13        | 0.95%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller         | 13        | 0.95%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                 | 12        | 0.88%   |
| Realtek 802.11ac NIC                                                        | 12        | 0.88%   |
| Intel Centrino Wireless-N 2230                                              | 12        | 0.88%   |
| Realtek RTL8723DE Wireless Network Adapter                                  | 11        | 0.8%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                       | 11        | 0.8%    |
| Intel Centrino Ultimate-N 6300                                              | 11        | 0.8%    |
| Intel Cannon Lake PCH CNVi WiFi                                             | 11        | 0.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                    | 10        | 0.73%   |
| Realtek RTL8188EE Wireless Network Adapter                                  | 10        | 0.73%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                  | 10        | 0.73%   |
| Qualcomm Atheros AR9271 802.11n                                             | 10        | 0.73%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 10        | 0.73%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                            | 9         | 0.66%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                    | 9         | 0.66%   |
| Broadcom Limited BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 9         | 0.66%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                 | 8         | 0.58%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                    | 8         | 0.58%   |
| Ralink RT2870/RT3070 Wireless Adapter                                       | 8         | 0.58%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                   | 8         | 0.58%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                     | 8         | 0.58%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                            | 8         | 0.58%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                             | 7         | 0.51%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                  | 7         | 0.51%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                     | 7         | 0.51%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                   | 7         | 0.51%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)              | 7         | 0.51%   |
| Intel Centrino Advanced-N 6235                                              | 7         | 0.51%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                  | 7         | 0.51%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                      | 7         | 0.51%   |
| Intel Wireless-AC 9260                                                      | 6         | 0.44%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]              | 6         | 0.44%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 712       | 47.28%  |
| Intel                                  | 291       | 19.32%  |
| Qualcomm Atheros                       | 110       | 7.3%    |
| Broadcom                               | 105       | 6.97%   |
| Marvell Technology Group               | 59        | 3.92%   |
| Nvidia                                 | 58        | 3.85%   |
| Broadcom Limited                       | 31        | 2.06%   |
| Silicon Integrated Systems [SiS]       | 26        | 1.73%   |
| VIA Technologies                       | 20        | 1.33%   |
| Samsung Electronics                    | 14        | 0.93%   |
| JMicron Technology                     | 13        | 0.86%   |
| Xiaomi                                 | 11        | 0.73%   |
| Huawei Technologies                    | 7         | 0.46%   |
| ASIX Electronics                       | 7         | 0.46%   |
| MediaTek                               | 5         | 0.33%   |
| OPPO Electronics                       | 4         | 0.27%   |
| Motorola PCS                           | 4         | 0.27%   |
| DisplayLink                            | 4         | 0.27%   |
| Qualcomm                               | 3         | 0.2%    |
| Davicom Semiconductor                  | 3         | 0.2%    |
| Attansic Technology                    | 3         | 0.2%    |
| Aquantia                               | 3         | 0.2%    |
| D-Link System                          | 2         | 0.13%   |
| Apple                                  | 2         | 0.13%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.07%   |
| TP-Link                                | 1         | 0.07%   |
| T & A Mobile Phones                    | 1         | 0.07%   |
| Sundance Technology Inc / IC Plus      | 1         | 0.07%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.07%   |
| NetGear                                | 1         | 0.07%   |
| GCT Semiconductor                      | 1         | 0.07%   |
| ASUSTek Computer                       | 1         | 0.07%   |
| 3Com                                   | 1         | 0.07%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 458       | 30.13%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 191       | 12.57%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 55        | 3.62%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 37        | 2.43%   |
| Intel Ethernet Connection I217-LM                                 | 25        | 1.64%   |
| Nvidia MCP61 Ethernet                                             | 22        | 1.45%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 21        | 1.38%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 17        | 1.12%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 16        | 1.05%   |
| Intel 82579V Gigabit Network Connection                           | 15        | 0.99%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 15        | 0.99%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 13        | 0.86%   |
| Intel Ethernet Connection I218-LM                                 | 13        | 0.86%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 12        | 0.79%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 12        | 0.79%   |
| Intel I211 Gigabit Network Connection                             | 12        | 0.79%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 11        | 0.72%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 11        | 0.72%   |
| Intel 82567LM Gigabit Network Connection                          | 11        | 0.72%   |
| Intel 82577LM Gigabit Network Connection                          | 10        | 0.66%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 9         | 0.59%   |
| Intel 82566MM Gigabit Network Connection                          | 9         | 0.59%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 9         | 0.59%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 9         | 0.59%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 9         | 0.59%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 8         | 0.53%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 8         | 0.53%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 8         | 0.53%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 8         | 0.53%   |
| Nvidia MCP79 Ethernet                                             | 8         | 0.53%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 8         | 0.53%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 8         | 0.53%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 7         | 0.46%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 7         | 0.46%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 7         | 0.46%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 7         | 0.46%   |
| Nvidia MCP73 Ethernet                                             | 7         | 0.46%   |
| Nvidia MCP67 Ethernet                                             | 7         | 0.46%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 7         | 0.46%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 7         | 0.46%   |
| Intel PRO/100 VE Network Connection                               | 7         | 0.46%   |
| Intel Ethernet Connection I219-LM                                 | 7         | 0.46%   |
| Intel Ethernet Connection (2) I219-V                              | 7         | 0.46%   |
| Intel Ethernet Connection (2) I219-LM                             | 7         | 0.46%   |
| Intel Ethernet Connection (2) I218-V                              | 7         | 0.46%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 7         | 0.46%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 6         | 0.39%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 6         | 0.39%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 6         | 0.39%   |
| Intel Ethernet Connection I217-V                                  | 6         | 0.39%   |
| Intel Ethernet Connection (3) I218-LM                             | 6         | 0.39%   |
| Broadcom Limited BCM4401-B0 100Base-TX                            | 6         | 0.39%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 5         | 0.33%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 5         | 0.33%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 5         | 0.33%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 5         | 0.33%   |
| Nvidia MCP77 Ethernet                                             | 5         | 0.33%   |
| Nvidia MCP51 Ethernet Controller                                  | 5         | 0.33%   |
| Intel 82578DM Gigabit Network Connection                          | 5         | 0.33%   |
| Intel 82574L Gigabit Network Connection                           | 5         | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1422      | 52.51%  |
| WiFi     | 1242      | 45.86%  |
| Modem    | 42        | 1.55%   |
| Unknown  | 2         | 0.07%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 970       | 60.21%  |
| Ethernet | 641       | 39.79%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 964       | 61.83%  |
| 1     | 539       | 34.57%  |
| 0     | 41        | 2.63%   |
| 3     | 14        | 0.9%    |
| 5     | 1         | 0.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1451      | 92.3%   |
| Yes  | 121       | 7.7%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 203       | 29%     |
| Qualcomm Atheros Communications | 84        | 12%     |
| Realtek Semiconductor           | 74        | 10.57%  |
| Broadcom                        | 67        | 9.57%   |
| Cambridge Silicon Radio         | 38        | 5.43%   |
| Dell                            | 31        | 4.43%   |
| Apple                           | 31        | 4.43%   |
| Hewlett-Packard                 | 30        | 4.29%   |
| Lite-On Technology              | 27        | 3.86%   |
| IMC Networks                    | 21        | 3%      |
| Foxconn / Hon Hai               | 19        | 2.71%   |
| Toshiba                         | 11        | 1.57%   |
| ASUSTek Computer                | 10        | 1.43%   |
| Alps Electric                   | 8         | 1.14%   |
| Realtek                         | 7         | 1%      |
| Ralink                          | 7         | 1%      |
| Foxconn International           | 5         | 0.71%   |
| Dynex                           | 5         | 0.71%   |
| Taiyo Yuden                     | 3         | 0.43%   |
| Ralink Technology               | 3         | 0.43%   |
| Micro Star International        | 3         | 0.43%   |
| Integrated System Solution      | 2         | 0.29%   |
| Belkin Components               | 2         | 0.29%   |
| Askey Computer                  | 2         | 0.29%   |
| TP-Link                         | 1         | 0.14%   |
| Qcom                            | 1         | 0.14%   |
| MediaTek                        | 1         | 0.14%   |
| Marvell Semiconductor           | 1         | 0.14%   |
| Logitech                        | 1         | 0.14%   |
| Fujitsu                         | 1         | 0.14%   |
| Chicony Electronics             | 1         | 0.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 119       | 16.98%  |
| Realtek Bluetooth Radio                                                             | 41        | 5.85%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 39        | 5.56%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 38        | 5.42%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 29        | 4.14%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 21        | 3%      |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 18        | 2.57%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 16        | 2.28%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 16        | 2.28%   |
| Intel AX200 Bluetooth                                                               | 16        | 2.28%   |
| Intel Bluetooth Device                                                              | 14        | 2%      |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 11        | 1.57%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 10        | 1.43%   |
| Apple Bluetooth USB Host Controller                                                 | 10        | 1.43%   |
| Apple Bluetooth Host Controller                                                     | 10        | 1.43%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 9         | 1.28%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 9         | 1.28%   |
| Intel AX201 Bluetooth                                                               | 9         | 1.28%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 9         | 1.28%   |
| Broadcom BCM2045 Bluetooth                                                          | 9         | 1.28%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 8         | 1.14%   |
| IMC Networks Bluetooth Radio                                                        | 8         | 1.14%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 8         | 1.14%   |
| Realtek Bluetooth Radio                                                             | 7         | 1%      |
| Ralink RT3290 Bluetooth                                                             | 7         | 1%      |
| Dell Wireless 365 Bluetooth                                                         | 7         | 1%      |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 7         | 1%      |
| Lite-On Bluetooth Device                                                            | 6         | 0.86%   |
| IMC Networks Bluetooth Device                                                       | 6         | 0.86%   |
| Dell DW375 Bluetooth Module                                                         | 6         | 0.86%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 5         | 0.71%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 5         | 0.71%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 5         | 0.71%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]                            | 5         | 0.71%   |
| Dell Wireless 350 Bluetooth                                                         | 5         | 0.71%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 5         | 0.71%   |
| Broadcom BCM20702A0                                                                 | 5         | 0.71%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 5         | 0.71%   |
| Toshiba Bluetooth Device                                                            | 4         | 0.57%   |
| Dell Wireless 370 Bluetooth Mini-card                                               | 4         | 0.57%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 4         | 0.57%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 4         | 0.57%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 4         | 0.57%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 4         | 0.57%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 4         | 0.57%   |
| Apple Bluetooth HCI                                                                 | 4         | 0.57%   |
| HP Bluetooth 1.2 Interface [Broadcom BCM2035]                                       | 3         | 0.43%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 3         | 0.43%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 3         | 0.43%   |
| Dell Wireless 360 Bluetooth                                                         | 3         | 0.43%   |
| Broadcom BCM2046 Bluetooth Device                                                   | 3         | 0.43%   |
| ASUS BT-253 Bluetooth Adapter                                                       | 3         | 0.43%   |
| Alps Electric UGTZ4 Bluetooth                                                       | 3         | 0.43%   |
| Toshiba Integrated Bluetooth HCI                                                    | 2         | 0.29%   |
| Toshiba Integrated Bluetooth (Taiyo Yuden)                                          | 2         | 0.29%   |
| Realtek RTL8821A Bluetooth                                                          | 2         | 0.29%   |
| Realtek RTL8723B Bluetooth                                                          | 2         | 0.29%   |
| Ralink CSR BS8510                                                                   | 2         | 0.29%   |
| Qualcomm Atheros Bluetooth                                                          | 2         | 0.29%   |
| Micro Star International Bluetooth Device                                           | 2         | 0.29%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1115      | 59.37%  |
| AMD                                  | 364       | 19.38%  |
| Nvidia                               | 265       | 14.11%  |
| Silicon Integrated Systems [SiS]     | 28        | 1.49%   |
| C-Media Electronics                  | 25        | 1.33%   |
| VIA Technologies                     | 19        | 1.01%   |
| Creative Labs                        | 10        | 0.53%   |
| Logitech                             | 8         | 0.43%   |
| Generalplus Technology               | 6         | 0.32%   |
| Tenx Technology                      | 4         | 0.21%   |
| Creative Technology                  | 4         | 0.21%   |
| JMTek                                | 3         | 0.16%   |
| GN Netcom                            | 3         | 0.16%   |
| Yamaha                               | 2         | 0.11%   |
| Turtle Beach                         | 2         | 0.11%   |
| Texas Instruments                    | 2         | 0.11%   |
| Ensoniq                              | 2         | 0.11%   |
| ZOOM                                 | 1         | 0.05%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.05%   |
| Syntek                               | 1         | 0.05%   |
| Shenzhen Riitek Technology           | 1         | 0.05%   |
| Samsung Electronics                  | 1         | 0.05%   |
| Razer USA                            | 1         | 0.05%   |
| Plantronics                          | 1         | 0.05%   |
| OPPO Electronics                     | 1         | 0.05%   |
| Micronas                             | 1         | 0.05%   |
| Klipsch Audio                        | 1         | 0.05%   |
| Hewlett-Packard                      | 1         | 0.05%   |
| Corsair                              | 1         | 0.05%   |
| Avance Logic                         | 1         | 0.05%   |
| Astro Gaming                         | 1         | 0.05%   |
| Apple                                | 1         | 0.05%   |
| AKAI Professional M.I.               | 1         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 167       | 7.55%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 129       | 5.83%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 104       | 4.7%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 95        | 4.29%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 93        | 4.2%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 84        | 3.8%    |
| AMD FCH Azalia Controller                                                                         | 72        | 3.25%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 70        | 3.16%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 68        | 3.07%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 66        | 2.98%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 55        | 2.49%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 47        | 2.12%   |
| Intel 8 Series HD Audio Controller                                                                | 47        | 2.12%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 43        | 1.94%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 36        | 1.63%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 30        | 1.36%   |
| AMD Kabini HDMI/DP Audio                                                                          | 27        | 1.22%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 24        | 1.08%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 24        | 1.08%   |
| Nvidia MCP61 High Definition Audio                                                                | 23        | 1.04%   |
| Nvidia High Definition Audio Controller                                                           | 23        | 1.04%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 23        | 1.04%   |
| Intel Broadwell-U Audio Controller                                                                | 23        | 1.04%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 23        | 1.04%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 22        | 0.99%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 22        | 0.99%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 22        | 0.99%   |
| Intel Cannon Lake PCH cAVS                                                                        | 21        | 0.95%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 21        | 0.95%   |
| AMD Wrestler HDMI Audio                                                                           | 21        | 0.95%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 21        | 0.95%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 20        | 0.9%    |
| AMD High Definition Audio Controller                                                              | 18        | 0.81%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 17        | 0.77%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 17        | 0.77%   |
| AMD Trinity HDMI Audio Controller                                                                 | 17        | 0.77%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 16        | 0.72%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 16        | 0.72%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 13        | 0.59%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 12        | 0.54%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 12        | 0.54%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 12        | 0.54%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 11        | 0.5%    |
| AMD Starship/Matisse HD Audio Controller                                                          | 11        | 0.5%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 11        | 0.5%    |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                                         | 10        | 0.45%   |
| Nvidia MCP79 High Definition Audio                                                                | 10        | 0.45%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 10        | 0.45%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 10        | 0.45%   |
| Intel CM238 HD Audio Controller                                                                   | 10        | 0.45%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 10        | 0.45%   |
| Intel 82801EB/ER (ICH5/ICH5R) AC'97 Audio Controller                                              | 10        | 0.45%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 10        | 0.45%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 9         | 0.41%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 9         | 0.41%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 9         | 0.41%   |
| Nvidia MCP73 High Definition Audio                                                                | 8         | 0.36%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 8         | 0.36%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 8         | 0.36%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 8         | 0.36%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 69        | 21.43%  |
| Unknown             | 63        | 19.57%  |
| Samsung Electronics | 57        | 17.7%   |
| Kingston            | 30        | 9.32%   |
| Micron Technology   | 25        | 7.76%   |
| Elpida              | 10        | 3.11%   |
| Corsair             | 10        | 3.11%   |
| Nanya Technology    | 9         | 2.8%    |
| Crucial             | 9         | 2.8%    |
| Ramaxel Technology  | 7         | 2.17%   |
| G.Skill             | 6         | 1.86%   |
| Smart               | 3         | 0.93%   |
| Qimonda             | 3         | 0.93%   |
| Unknown (ABCD)      | 2         | 0.62%   |
| High Bridge         | 2         | 0.62%   |
| A-DATA Technology   | 2         | 0.62%   |
| Walton Chaintech    | 1         | 0.31%   |
| Transcend           | 1         | 0.31%   |
| Toshiba             | 1         | 0.31%   |
| Team                | 1         | 0.31%   |
| Smart Brazil        | 1         | 0.31%   |
| SHARETRONIC         | 1         | 0.31%   |
| Ramos Technology    | 1         | 0.31%   |
| PNY                 | 1         | 0.31%   |
| Patriot             | 1         | 0.31%   |
| Nayna               | 1         | 0.31%   |
| HBS                 | 1         | 0.31%   |
| CSX                 | 1         | 0.31%   |
| COS Memory          | 1         | 0.31%   |
| Avant               | 1         | 0.31%   |
| ASint Technology    | 1         | 0.31%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 6         | 1.71%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 800MT/s             | 5         | 1.43%   |
| Unknown RAM Module 1GB DIMM SDRAM                                | 4         | 1.14%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 1.14%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s         | 4         | 1.14%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR2 667MT/s            | 3         | 0.86%   |
| SK hynix RAM HYMP112S64CP6-S6 1GB SODIMM DDR2 975MT/s            | 3         | 0.86%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 0.86%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.86%   |
| Unknown RAM Module 512MB SODIMM DDR                              | 2         | 0.57%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 2         | 0.57%   |
| Unknown RAM Module 2GB SODIMM DDR2 533MT/s                       | 2         | 0.57%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 2         | 0.57%   |
| Unknown RAM Module 2GB SODIMM DDR                                | 2         | 0.57%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                           | 2         | 0.57%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 2         | 0.57%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                           | 2         | 0.57%   |
| Unknown RAM Module 1GB DIMM DDR2                                 | 2         | 0.57%   |
| Unknown RAM Module 1024MB DIMM DDR2 333MT/s                      | 2         | 0.57%   |
| Unknown RAM Module 1024MB DIMM                                   | 2         | 0.57%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 2         | 0.57%   |
| SK hynix RAM Module 4096MB DIMM DDR3 1066MT/s                    | 2         | 0.57%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 2         | 0.57%   |
| SK hynix RAM Module 2048MB SODIMM DDR3 1066MT/s                  | 2         | 0.57%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.57%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.57%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 2         | 0.57%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.57%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 0.57%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 2         | 0.57%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 2         | 0.57%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.57%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.57%   |
| Samsung RAM M471A5244CB0-CTD 4096MB Row Of Chips DDR4 2667MT/s   | 2         | 0.57%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s          | 2         | 0.57%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 2         | 0.57%   |
| Micron RAM Module 2048MB SODIMM DDR3 1600MT/s                    | 2         | 0.57%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 2         | 0.57%   |
| Micron RAM 8JSF25664HZ-1G4D1 2048MB SODIMM DDR3 1334MT/s         | 2         | 0.57%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 2         | 0.57%   |
| Kingston RAM KCM633-ELC 1GB DIMM DDR2 2048MT/s                   | 2         | 0.57%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s          | 2         | 0.57%   |
| Elpida RAM EBJ20UF8BCF0-DJ-F 2GB DIMM DDR3 1333MT/s              | 2         | 0.57%   |
| Crucial RAM BLS4G3D1609DS1S00. 4GB DIMM DDR3 1600MT/s            | 2         | 0.57%   |
| A-DATA RAM AM1U16BC4P2-B19H 4GB SODIMM DDR3 1600MT/s             | 2         | 0.57%   |
| Walton Chaintech RAM AS2G833-13GH905 2048MB SODIMM DDR2          | 1         | 0.29%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.29%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 1         | 0.29%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2400MT/s                   | 1         | 0.29%   |
| Unknown RAM Module 8192MB DIMM SDRAM                             | 1         | 0.29%   |
| Unknown RAM Module 512MB SODIMM DRAM                             | 1         | 0.29%   |
| Unknown RAM Module 512MB SODIMM DDR2 667MT/s                     | 1         | 0.29%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 0.29%   |
| Unknown RAM Module 512MB DIMM 400MT/s                            | 1         | 0.29%   |
| Unknown RAM Module 512MB DIMM 333MT/s                            | 1         | 0.29%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.29%   |
| Unknown RAM Module 4GB SODIMM DDR2 667MT/s                       | 1         | 0.29%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 0.29%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 0.29%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 0.29%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 115       | 40.78%  |
| DDR4    | 59        | 20.92%  |
| DDR2    | 55        | 19.5%   |
| SDRAM   | 24        | 8.51%   |
| Unknown | 14        | 4.96%   |
| DRAM    | 5         | 1.77%   |
| DDR     | 5         | 1.77%   |
| LPDDR4  | 3         | 1.06%   |
| LPDDR3  | 2         | 0.71%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 176       | 65.19%  |
| DIMM         | 87        | 32.22%  |
| Row Of Chips | 6         | 2.22%   |
| Chip         | 1         | 0.37%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 2048  | 94        | 29.65%  |
| 4096  | 93        | 29.34%  |
| 8192  | 60        | 18.93%  |
| 1024  | 48        | 15.14%  |
| 16384 | 10        | 3.15%   |
| 512   | 10        | 3.15%   |
| 256   | 2         | 0.63%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 70        | 22.95%  |
| 1333    | 26        | 8.52%   |
| Unknown | 26        | 8.52%   |
| 2667    | 25        | 8.2%    |
| 667     | 25        | 8.2%    |
| 1334    | 15        | 4.92%   |
| 800     | 15        | 4.92%   |
| 2133    | 12        | 3.93%   |
| 1066    | 12        | 3.93%   |
| 533     | 9         | 2.95%   |
| 3200    | 8         | 2.62%   |
| 2400    | 8         | 2.62%   |
| 4199    | 7         | 2.3%    |
| 975     | 7         | 2.3%    |
| 3600    | 5         | 1.64%   |
| 2048    | 5         | 1.64%   |
| 3266    | 4         | 1.31%   |
| 400     | 4         | 1.31%   |
| 333     | 3         | 0.98%   |
| 3466    | 2         | 0.66%   |
| 3000    | 2         | 0.66%   |
| 1866    | 2         | 0.66%   |
| 1639    | 2         | 0.66%   |
| 1067    | 2         | 0.66%   |
| 49926   | 1         | 0.33%   |
| 4400    | 1         | 0.33%   |
| 3733    | 1         | 0.33%   |
| 3151    | 1         | 0.33%   |
| 2933    | 1         | 0.33%   |
| 2800    | 1         | 0.33%   |
| 2666    | 1         | 0.33%   |
| 2134    | 1         | 0.33%   |
| 1867    | 1         | 0.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 16        | 30.77%  |
| Canon               | 14        | 26.92%  |
| Brother Industries  | 10        | 19.23%  |
| Seiko Epson         | 4         | 7.69%   |
| Samsung Electronics | 4         | 7.69%   |
| Toshiba TEC         | 1         | 1.92%   |
| STMicroelectronics  | 1         | 1.92%   |
| Ricoh               | 1         | 1.92%   |
| Pantum              | 1         | 1.92%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| HP LaserJet Professional P 1102w                          | 2         | 3.85%   |
| HP ENVY 5000 series                                       | 2         | 3.85%   |
| Canon PIXMA MX340                                         | 2         | 3.85%   |
| Canon PIXMA MG2500 Series                                 | 2         | 3.85%   |
| Canon MF4010 series                                       | 2         | 3.85%   |
| Brother HL-2130 series                                    | 2         | 3.85%   |
| Toshiba TEC e-STD120 USB                                  | 1         | 1.92%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 1.92%   |
| Seiko Epson WF-2010 Series                                | 1         | 1.92%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]              | 1         | 1.92%   |
| Seiko Epson L220 Series                                   | 1         | 1.92%   |
| Seiko Epson L120 Series                                   | 1         | 1.92%   |
| Samsung SCX-3400 Series                                   | 1         | 1.92%   |
| Samsung ML-2010P Mono Laser Printer                       | 1         | 1.92%   |
| Samsung M2070 Series                                      | 1         | 1.92%   |
| Samsung CLX-3300 Series                                   | 1         | 1.92%   |
| Ricoh SP C250SF                                           | 1         | 1.92%   |
| Pantum P2500W series                                      | 1         | 1.92%   |
| HP OfficeJet 3830 series                                  | 1         | 1.92%   |
| HP Laserjet P1505                                         | 1         | 1.92%   |
| HP LaserJet P1102                                         | 1         | 1.92%   |
| HP LaserJet 3050                                          | 1         | 1.92%   |
| HP LaserJet 1020                                          | 1         | 1.92%   |
| HP ENVY 4520 series                                       | 1         | 1.92%   |
| HP Deskjet 4620 series                                    | 1         | 1.92%   |
| HP Deskjet 3050A                                          | 1         | 1.92%   |
| HP DeskJet 2700 series                                    | 1         | 1.92%   |
| HP Deskjet 1510                                           | 1         | 1.92%   |
| HP DeskJet 1110 series                                    | 1         | 1.92%   |
| HP Deskjet 1050 J410                                      | 1         | 1.92%   |
| Canon TS3100 series                                       | 1         | 1.92%   |
| Canon PIXMA MG3600 Series                                 | 1         | 1.92%   |
| Canon Pixma iP4500 Printer                                | 1         | 1.92%   |
| Canon MG2100 series                                       | 1         | 1.92%   |
| Canon LiDE 300                                            | 1         | 1.92%   |
| Canon LBP810                                              | 1         | 1.92%   |
| Canon iP7200 series                                       | 1         | 1.92%   |
| Canon FAXPHONE L80                                        | 1         | 1.92%   |
| Brother MFC-L2730DW series                                | 1         | 1.92%   |
| Brother MFC-J470DW                                        | 1         | 1.92%   |
| Brother HL-L2380DW                                        | 1         | 1.92%   |
| Brother HL-L2350DW series                                 | 1         | 1.92%   |
| Brother HL-L2340D series                                  | 1         | 1.92%   |
| Brother HL-52x0 series                                    | 1         | 1.92%   |
| Brother DCP-T300                                          | 1         | 1.92%   |
| Brother DCP-1610W                                         | 1         | 1.92%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 50%     |
| Canon CanoScan LIDE 25             | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 212       | 26.08%  |
| Microdia                               | 77        | 9.47%   |
| Suyin                                  | 54        | 6.64%   |
| Acer                                   | 53        | 6.52%   |
| Realtek Semiconductor                  | 52        | 6.4%    |
| IMC Networks                           | 49        | 6.03%   |
| Sunplus Innovation Technology          | 37        | 4.55%   |
| Cheng Uei Precision Industry (Foxlink) | 32        | 3.94%   |
| Apple                                  | 31        | 3.81%   |
| Silicon Motion                         | 25        | 3.08%   |
| Quanta                                 | 21        | 2.58%   |
| Logitech                               | 17        | 2.09%   |
| Lite-On Technology                     | 17        | 2.09%   |
| Alcor Micro                            | 17        | 2.09%   |
| Syntek                                 | 14        | 1.72%   |
| Ricoh                                  | 12        | 1.48%   |
| Importek                               | 11        | 1.35%   |
| Z-Star Microelectronics                | 9         | 1.11%   |
| Samsung Electronics                    | 9         | 1.11%   |
| ALi                                    | 9         | 1.11%   |
| Microsoft                              | 8         | 0.98%   |
| OmniVision Technologies                | 5         | 0.62%   |
| GEMBIRD                                | 5         | 0.62%   |
| Cubeternet                             | 4         | 0.49%   |
| Lenovo                                 | 3         | 0.37%   |
| Genesys Logic                          | 3         | 0.37%   |
| Primax Electronics                     | 2         | 0.25%   |
| Pixart Imaging                         | 2         | 0.25%   |
| Luxvisions Innotech Limited            | 2         | 0.25%   |
| LG Electronics                         | 2         | 0.25%   |
| Generalplus Technology                 | 2         | 0.25%   |
| YGTek                                  | 1         | 0.12%   |
| Trust                                  | 1         | 0.12%   |
| Sunplus Technology                     | 1         | 0.12%   |
| Sonix Technology                       | 1         | 0.12%   |
| Novatel Wireless                       | 1         | 0.12%   |
| Novatek Microelectronics               | 1         | 0.12%   |
| Jieli Technology                       | 1         | 0.12%   |
| Intel                                  | 1         | 0.12%   |
| Huawei Technologies                    | 1         | 0.12%   |
| Foxconn / Hon Hai                      | 1         | 0.12%   |
| eMPIA Technology                       | 1         | 0.12%   |
| Elecom                                 | 1         | 0.12%   |
| Creative Technology                    | 1         | 0.12%   |
| Camera                                 | 1         | 0.12%   |
| AVerMedia Technologies                 | 1         | 0.12%   |
| Aveo Technology                        | 1         | 0.12%   |
| Arkmicro Technologies                  | 1         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 17        | 2.09%   |
| Chicony USB 2.0 Camera                                  | 14        | 1.72%   |
| Acer Lenovo EasyCamera                                  | 12        | 1.47%   |
| Realtek Integrated_Webcam_HD                            | 11        | 1.35%   |
| Chicony EasyCamera                                      | 11        | 1.35%   |
| Microdia Sonix USB 2.0 Camera                           | 10        | 1.23%   |
| Microdia Integrated Webcam                              | 10        | 1.23%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 10        | 1.23%   |
| Apple iPhone 5/5C/5S/6/SE                               | 10        | 1.23%   |
| Samsung Galaxy A5 (MTP)                                 | 9         | 1.1%    |
| Chicony HP Truevision HD camera                         | 9         | 1.1%    |
| Chicony HP Truevision HD                                | 9         | 1.1%    |
| Suyin HP Truevision HD                                  | 8         | 0.98%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 8         | 0.98%   |
| Sunplus Integrated_Webcam_HD                            | 8         | 0.98%   |
| Realtek Integrated Webcam                               | 8         | 0.98%   |
| Chicony VGA WebCam                                      | 8         | 0.98%   |
| Chicony Lenovo EasyCamera                               | 8         | 0.98%   |
| Chicony HP HD Webcam                                    | 8         | 0.98%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 7         | 0.86%   |
| Chicony TOSHIBA Web Camera - HD                         | 7         | 0.86%   |
| Chicony HP Webcam                                       | 7         | 0.86%   |
| Chicony HD WebCam                                       | 7         | 0.86%   |
| Apple FaceTime HD Camera (Built-in)                     | 7         | 0.86%   |
| Apple Built-in iSight                                   | 7         | 0.86%   |
| ALi Gateway Webcam                                      | 7         | 0.86%   |
| Quanta HP Webcam                                        | 6         | 0.74%   |
| Microdia Laptop_Integrated_Webcam_HD                    | 6         | 0.74%   |
| Microdia Integrated_Webcam_HD                           | 6         | 0.74%   |
| Lite-On Integrated Camera                               | 6         | 0.74%   |
| IMC Networks Integrated Camera                          | 6         | 0.74%   |
| Chicony CNF9055 Toshiba Webcam                          | 6         | 0.74%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 6         | 0.74%   |
| Alcor Micro USB 2.0 PC cam                              | 6         | 0.74%   |
| Acer EasyCamera                                         | 6         | 0.74%   |
| Sunplus HP HD Webcam [Fixed]                            | 5         | 0.61%   |
| Sunplus HD WebCam                                       | 5         | 0.61%   |
| Silicon Motion Web Camera                               | 5         | 0.61%   |
| Quanta HP TrueVision HD Camera                          | 5         | 0.61%   |
| Microdia HP Integrated Webcam                           | 5         | 0.61%   |
| Logitech Webcam C270                                    | 5         | 0.61%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]       | 5         | 0.61%   |
| Chicony USB2.0 VGA UVC WebCam                           | 5         | 0.61%   |
| Chicony USB2.0 HD UVC WebCam                            | 5         | 0.61%   |
| Chicony HP Wide Vision HD Camera                        | 5         | 0.61%   |
| Cheng Uei Precision Industry (Foxlink) Webcam           | 5         | 0.61%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera     | 5         | 0.61%   |
| Acer Integrated Camera                                  | 5         | 0.61%   |
| Acer BisonCam, NB Pro                                   | 5         | 0.61%   |
| Z-Star Webcam                                           | 4         | 0.49%   |
| Syntek EasyCamera                                       | 4         | 0.49%   |
| Suyin Acer CrystalEye Webcam                            | 4         | 0.49%   |
| Silicon Motion WebCam SCB-0355N                         | 4         | 0.49%   |
| Realtek USB2.0 VGA UVC WebCam                           | 4         | 0.49%   |
| Realtek USB2.0 HD UVC WebCam                            | 4         | 0.49%   |
| Realtek HP Webcam-101                                   | 4         | 0.49%   |
| Quanta HD Webcam                                        | 4         | 0.49%   |
| OmniVision OV2640 Webcam                                | 4         | 0.49%   |
| Microdia Laptop_Integrated_Webcam_E4HD                  | 4         | 0.49%   |
| Microdia Integrated_Webcam_1.3M                         | 4         | 0.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 69        | 50.74%  |
| AuthenTec                  | 25        | 18.38%  |
| STMicroelectronics         | 9         | 6.62%   |
| Upek                       | 8         | 5.88%   |
| Synaptics                  | 8         | 5.88%   |
| Shenzhen Goodix Technology | 8         | 5.88%   |
| Elan Microelectronics      | 7         | 5.15%   |
| LighTuning Technology      | 2         | 1.47%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 15        | 11.03%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 10        | 7.35%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 10        | 7.35%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 9         | 6.62%   |
| STMicroelectronics Fingerprint Reader                                      | 9         | 6.62%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 9         | 6.62%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 8         | 5.88%   |
| Validity Sensors Fingerprint scanner                                       | 6         | 4.41%   |
| Elan ELAN:Fingerprint                                                      | 6         | 4.41%   |
| Validity Sensors VFS491                                                    | 5         | 3.68%   |
| AuthenTec AES2810                                                          | 5         | 3.68%   |
| AuthenTec AES1600                                                          | 5         | 3.68%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 2.94%   |
| Synaptics  WBDI                                                            | 4         | 2.94%   |
| Shenzhen Goodix  Fingerprint Device                                        | 4         | 2.94%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 2.21%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 3         | 2.21%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 2.21%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 3         | 2.21%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 1.47%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 1.47%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 1.47%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.74%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.74%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.74%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 0.74%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.74%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.74%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.74%   |
| Elan ELAN:ARM-M4                                                           | 1         | 0.74%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.74%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 24        | 44.44%  |
| O2 Micro              | 12        | 22.22%  |
| Alcor Micro           | 10        | 18.52%  |
| Lenovo                | 3         | 5.56%   |
| Upek                  | 2         | 3.7%    |
| SCM Microsystems      | 1         | 1.85%   |
| Realtek Semiconductor | 1         | 1.85%   |
| Kobil Systems         | 1         | 1.85%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 15        | 27.78%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 10        | 18.52%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 8         | 14.81%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 5         | 9.26%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 7.41%   |
| Broadcom 5880                                                                | 4         | 7.41%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 5.56%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 3.7%    |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 1.85%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 1.85%   |
| Kobil Systems KOBIL Class 3 Reader                                           | 1         | 1.85%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1064      | 67.21%  |
| 1     | 421       | 26.6%   |
| 2     | 88        | 5.56%   |
| 3     | 7         | 0.44%   |
| 4     | 2         | 0.13%   |
| 7     | 1         | 0.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 170       | 28.29%  |
| Fingerprint reader       | 135       | 22.46%  |
| Net/wireless             | 115       | 19.13%  |
| Chipcard                 | 53        | 8.82%   |
| Modem                    | 24        | 3.99%   |
| Multimedia controller    | 20        | 3.33%   |
| Communication controller | 20        | 3.33%   |
| Storage                  | 16        | 2.66%   |
| Sound                    | 10        | 1.66%   |
| Bluetooth                | 10        | 1.66%   |
| Flash memory             | 8         | 1.33%   |
| Camera                   | 6         | 1%      |
| Unassigned class         | 5         | 0.83%   |
| Net/ethernet             | 3         | 0.5%    |
| Card reader              | 2         | 0.33%   |
| Storage/raid             | 1         | 0.17%   |
| Storage/nvme             | 1         | 0.17%   |
| Storage/ata              | 1         | 0.17%   |
| Network                  | 1         | 0.17%   |

