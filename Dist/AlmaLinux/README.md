AlmaLinux - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for AlmaLinux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/AlmaLinux/Desktop/README.md) and [notebooks](/Dist/AlmaLinux/Notebook/README.md).

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

Total: 373

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Supermicro    | H12SSL-i                    | Server      | [d5cf0eca85](https://linux-hardware.org/?probe=d5cf0eca85) | May 09, 2024 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [236ac0d0ed](https://linux-hardware.org/?probe=236ac0d0ed) | May 09, 2024 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | Notebook    | [c5f9a761a9](https://linux-hardware.org/?probe=c5f9a761a9) | May 05, 2024 |
| ASRockRack    | X570D4I-2T                  | Server      | [fd5c83c424](https://linux-hardware.org/?probe=fd5c83c424) | May 02, 2024 |
| Acer          | Aspire E1-571               | Notebook    | [0f3b954320](https://linux-hardware.org/?probe=0f3b954320) | May 02, 2024 |
| Lenovo        | Kabini CRB NOK              | Desktop     | [dfa3d8f2cd](https://linux-hardware.org/?probe=dfa3d8f2cd) | Apr 29, 2024 |
| Toshiba       | Satellite C50-A             | Notebook    | [cabe5d7a20](https://linux-hardware.org/?probe=cabe5d7a20) | Apr 23, 2024 |
| Haier         | TIGD2-CI                    | Desktop     | [dc4f526a80](https://linux-hardware.org/?probe=dc4f526a80) | Apr 23, 2024 |
| Dell          | 0D441T A01                  | Desktop     | [98b14bc73d](https://linux-hardware.org/?probe=98b14bc73d) | Apr 10, 2024 |
| Supermicro    | H12SSL-i                    | Server      | [ded5f6b3ba](https://linux-hardware.org/?probe=ded5f6b3ba) | Apr 07, 2024 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [4f14a1fb58](https://linux-hardware.org/?probe=4f14a1fb58) | Apr 07, 2024 |
| Supermicro    | H12SSL-i                    | Server      | [f1de845101](https://linux-hardware.org/?probe=f1de845101) | Apr 06, 2024 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [271844c58a](https://linux-hardware.org/?probe=271844c58a) | Apr 06, 2024 |
| Acer          | Aspire A315-59              | Notebook    | [f1c498121d](https://linux-hardware.org/?probe=f1c498121d) | Mar 13, 2024 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [7db787716d](https://linux-hardware.org/?probe=7db787716d) | Mar 12, 2024 |
| ASUSTek       | P6X58D PREMIUM              | Desktop     | [ffc080a6f0](https://linux-hardware.org/?probe=ffc080a6f0) | Mar 09, 2024 |
| ASUSTek       | P6X58D PREMIUM              | Desktop     | [3a33a36874](https://linux-hardware.org/?probe=3a33a36874) | Mar 09, 2024 |
| Toshiba       | Satellite C50-A             | Notebook    | [64c28ad883](https://linux-hardware.org/?probe=64c28ad883) | Mar 05, 2024 |
| Toshiba       | Satellite C50-A             | Notebook    | [2229c82401](https://linux-hardware.org/?probe=2229c82401) | Mar 03, 2024 |
| Dell          | Inspiron 5379               | Notebook    | [43522636f8](https://linux-hardware.org/?probe=43522636f8) | Mar 02, 2024 |
| Lenovo        | ThinkPad T480s 20L70028U... | Notebook    | [3ce277e7b9](https://linux-hardware.org/?probe=3ce277e7b9) | Feb 25, 2024 |
| Supermicro    | H12SSL-i                    | Server      | [c58df8f5e4](https://linux-hardware.org/?probe=c58df8f5e4) | Feb 19, 2024 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [4a75bbf769](https://linux-hardware.org/?probe=4a75bbf769) | Feb 19, 2024 |
| Supermicro    | H12SSL-i                    | Server      | [6745442873](https://linux-hardware.org/?probe=6745442873) | Feb 18, 2024 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [9a9a9f6fb3](https://linux-hardware.org/?probe=9a9a9f6fb3) | Feb 18, 2024 |
| ASUSTek       | GL552VW                     | Notebook    | [3d01ffb3f6](https://linux-hardware.org/?probe=3d01ffb3f6) | Feb 13, 2024 |
| Dell          | Inspiron 5379               | Notebook    | [ac5fe15861](https://linux-hardware.org/?probe=ac5fe15861) | Feb 12, 2024 |
| Supermicro    | H12SSL-i                    | Server      | [6db0b8a8f1](https://linux-hardware.org/?probe=6db0b8a8f1) | Feb 03, 2024 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [00056f1b48](https://linux-hardware.org/?probe=00056f1b48) | Feb 03, 2024 |
| Supermicro    | H12SSL-i                    | Server      | [17031c6aac](https://linux-hardware.org/?probe=17031c6aac) | Feb 02, 2024 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [0fa43445d1](https://linux-hardware.org/?probe=0fa43445d1) | Feb 02, 2024 |
| Supermicro    | H12SSL-i                    | Server      | [f206485d60](https://linux-hardware.org/?probe=f206485d60) | Feb 01, 2024 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [b7bc0cf1ac](https://linux-hardware.org/?probe=b7bc0cf1ac) | Feb 01, 2024 |
| Supermicro    | H12SSL-i                    | Server      | [6849639353](https://linux-hardware.org/?probe=6849639353) | Jan 31, 2024 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [d67b24a21d](https://linux-hardware.org/?probe=d67b24a21d) | Jan 31, 2024 |
| HP            | Falco                       | Notebook    | [9a82a5b9e8](https://linux-hardware.org/?probe=9a82a5b9e8) | Jan 26, 2024 |
| Raspberry ... | Raspberry Pi                | Soc         | [343e08f1a6](https://linux-hardware.org/?probe=343e08f1a6) | Jan 24, 2024 |
| HP            | 89D8 SMVB                   | Desktop     | [61f8c8c9e0](https://linux-hardware.org/?probe=61f8c8c9e0) | Jan 22, 2024 |
| HP            | 89D8 SMVB                   | Desktop     | [3c8308af97](https://linux-hardware.org/?probe=3c8308af97) | Jan 22, 2024 |
| HP            | ENVY 15                     | Notebook    | [95ec6d10d0](https://linux-hardware.org/?probe=95ec6d10d0) | Jan 19, 2024 |
| Acer          | TravelMate 5735Z            | Notebook    | [6d759892ab](https://linux-hardware.org/?probe=6d759892ab) | Jan 12, 2024 |
| Acer          | TravelMate 5735Z            | Notebook    | [2ad65584c2](https://linux-hardware.org/?probe=2ad65584c2) | Jan 11, 2024 |
| Raspberry ... | Raspberry Pi                | Soc         | [8cf8ef7602](https://linux-hardware.org/?probe=8cf8ef7602) | Jan 11, 2024 |
| Optimized ... | KVM                         | Desktop     | [4fe928d059](https://linux-hardware.org/?probe=4fe928d059) | Jan 11, 2024 |
| HP            | Falco                       | Notebook    | [f6a8ee9181](https://linux-hardware.org/?probe=f6a8ee9181) | Jan 11, 2024 |
| Dell          | Precision 5680              | Notebook    | [82dc0a13bb](https://linux-hardware.org/?probe=82dc0a13bb) | Jan 10, 2024 |
| Supermicro    | X8DTT-H                     | Server      | [0fb61ad105](https://linux-hardware.org/?probe=0fb61ad105) | Jan 05, 2024 |
| Supermicro    | H12SSL-i                    | Server      | [ac848615a7](https://linux-hardware.org/?probe=ac848615a7) | Jan 03, 2024 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [0be3bb4773](https://linux-hardware.org/?probe=0be3bb4773) | Jan 03, 2024 |
| Supermicro    | H12SSL-i                    | Server      | [454b403b53](https://linux-hardware.org/?probe=454b403b53) | Jan 02, 2024 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [a1095fd614](https://linux-hardware.org/?probe=a1095fd614) | Jan 02, 2024 |
| Supermicro    | H12SSL-i                    | Server      | [0003baf54d](https://linux-hardware.org/?probe=0003baf54d) | Jan 01, 2024 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [cc645ac529](https://linux-hardware.org/?probe=cc645ac529) | Jan 01, 2024 |
| Supermicro    | H12SSL-i                    | Server      | [ae544239b5](https://linux-hardware.org/?probe=ae544239b5) | Dec 31, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [b9db9c256b](https://linux-hardware.org/?probe=b9db9c256b) | Dec 31, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [a5f60699ce](https://linux-hardware.org/?probe=a5f60699ce) | Dec 25, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [b19b947d42](https://linux-hardware.org/?probe=b19b947d42) | Dec 25, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [df01343f10](https://linux-hardware.org/?probe=df01343f10) | Dec 24, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [346c422237](https://linux-hardware.org/?probe=346c422237) | Dec 24, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [aa11af3235](https://linux-hardware.org/?probe=aa11af3235) | Dec 20, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [f504f4b8d5](https://linux-hardware.org/?probe=f504f4b8d5) | Dec 19, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [f4707e0e75](https://linux-hardware.org/?probe=f4707e0e75) | Dec 19, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [27cd685574](https://linux-hardware.org/?probe=27cd685574) | Dec 18, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [9a521bb0c9](https://linux-hardware.org/?probe=9a521bb0c9) | Dec 18, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [3b37f8220f](https://linux-hardware.org/?probe=3b37f8220f) | Dec 17, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [91f9814da4](https://linux-hardware.org/?probe=91f9814da4) | Dec 17, 2023 |
| Timi          | TM1709                      | Notebook    | [f566951fd0](https://linux-hardware.org/?probe=f566951fd0) | Dec 14, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [230f41f6b5](https://linux-hardware.org/?probe=230f41f6b5) | Dec 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [e5415e7df5](https://linux-hardware.org/?probe=e5415e7df5) | Dec 12, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [93675534e1](https://linux-hardware.org/?probe=93675534e1) | Dec 05, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [85c03e03e8](https://linux-hardware.org/?probe=85c03e03e8) | Dec 04, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | Desktop     | [746c6adb3f](https://linux-hardware.org/?probe=746c6adb3f) | Dec 04, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | Desktop     | [7eaae92099](https://linux-hardware.org/?probe=7eaae92099) | Dec 04, 2023 |
| AOCWEI        | A2                          | Notebook    | [ac8272a8a8](https://linux-hardware.org/?probe=ac8272a8a8) | Nov 26, 2023 |
| MSI           | MPG Z590 GAMING PLUS        | Desktop     | [d231a15a8f](https://linux-hardware.org/?probe=d231a15a8f) | Nov 22, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [a2c80195ae](https://linux-hardware.org/?probe=a2c80195ae) | Nov 21, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [1d8266c67b](https://linux-hardware.org/?probe=1d8266c67b) | Nov 21, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [e8e233f240](https://linux-hardware.org/?probe=e8e233f240) | Nov 20, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [4dbe82fc95](https://linux-hardware.org/?probe=4dbe82fc95) | Nov 20, 2023 |
| Intel         | X99                         | Desktop     | [c07799299c](https://linux-hardware.org/?probe=c07799299c) | Nov 19, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [ec6ef64584](https://linux-hardware.org/?probe=ec6ef64584) | Nov 18, 2023 |
| Acer          | Aspire E5-553               | Notebook    | [a8349dda46](https://linux-hardware.org/?probe=a8349dda46) | Nov 16, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [e0bc805f38](https://linux-hardware.org/?probe=e0bc805f38) | Nov 16, 2023 |
| AOCWEI        | A2                          | Notebook    | [1006e22f22](https://linux-hardware.org/?probe=1006e22f22) | Nov 09, 2023 |
| Toshiba       | Satellite C50-A             | Notebook    | [056e939d6d](https://linux-hardware.org/?probe=056e939d6d) | Nov 09, 2023 |
| Toshiba       | Satellite C50-A             | Notebook    | [6c8040c314](https://linux-hardware.org/?probe=6c8040c314) | Nov 08, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [49051e4c14](https://linux-hardware.org/?probe=49051e4c14) | Nov 07, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [fca6e5bc74](https://linux-hardware.org/?probe=fca6e5bc74) | Nov 07, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [0bcc882e05](https://linux-hardware.org/?probe=0bcc882e05) | Nov 06, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [963acb5f2b](https://linux-hardware.org/?probe=963acb5f2b) | Nov 06, 2023 |
| MSI           | MPG Z590 GAMING PLUS        | Desktop     | [e3760a331a](https://linux-hardware.org/?probe=e3760a331a) | Oct 31, 2023 |
| Notebook      | NS50_70MU                   | Notebook    | [ad21a28397](https://linux-hardware.org/?probe=ad21a28397) | Oct 28, 2023 |
| Notebook      | NS50_70MU                   | Notebook    | [166a51fa8d](https://linux-hardware.org/?probe=166a51fa8d) | Oct 27, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [492563a83c](https://linux-hardware.org/?probe=492563a83c) | Oct 24, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [3e4b32b047](https://linux-hardware.org/?probe=3e4b32b047) | Oct 24, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [3880cb8ecf](https://linux-hardware.org/?probe=3880cb8ecf) | Oct 22, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [7cdd3de48b](https://linux-hardware.org/?probe=7cdd3de48b) | Oct 22, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [8deecaac39](https://linux-hardware.org/?probe=8deecaac39) | Oct 21, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [a0ebc9b489](https://linux-hardware.org/?probe=a0ebc9b489) | Oct 21, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [de8a8232ba](https://linux-hardware.org/?probe=de8a8232ba) | Oct 19, 2023 |
| Dell          | Precision 7760              | Notebook    | [4b42c6c7f1](https://linux-hardware.org/?probe=4b42c6c7f1) | Oct 14, 2023 |
| Gigabyte      | X399 DESIGNARE EX-CF        | Desktop     | [d9bbe8269c](https://linux-hardware.org/?probe=d9bbe8269c) | Oct 10, 2023 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [27ce5f6a61](https://linux-hardware.org/?probe=27ce5f6a61) | Oct 06, 2023 |
| HP            | 81C5 MVB                    | Desktop     | [ccdf9d0cfa](https://linux-hardware.org/?probe=ccdf9d0cfa) | Oct 02, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [527518057b](https://linux-hardware.org/?probe=527518057b) | Oct 02, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [88e4c09c2f](https://linux-hardware.org/?probe=88e4c09c2f) | Oct 02, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [53fec3f094](https://linux-hardware.org/?probe=53fec3f094) | Oct 01, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [9115ea465f](https://linux-hardware.org/?probe=9115ea465f) | Oct 01, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [6ce97609be](https://linux-hardware.org/?probe=6ce97609be) | Sep 30, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [da0e120624](https://linux-hardware.org/?probe=da0e120624) | Sep 30, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [7ab6fc6901](https://linux-hardware.org/?probe=7ab6fc6901) | Sep 27, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [1b72177563](https://linux-hardware.org/?probe=1b72177563) | Sep 26, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [2527f2a9fc](https://linux-hardware.org/?probe=2527f2a9fc) | Sep 26, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [3e533c5366](https://linux-hardware.org/?probe=3e533c5366) | Sep 25, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [d37c8958bf](https://linux-hardware.org/?probe=d37c8958bf) | Sep 25, 2023 |
| HP            | Laptop 14-ep0xxx            | Notebook    | [ee7b0c8506](https://linux-hardware.org/?probe=ee7b0c8506) | Sep 21, 2023 |
| Lenovo        | G580 20157                  | Notebook    | [9b576274e4](https://linux-hardware.org/?probe=9b576274e4) | Sep 20, 2023 |
| Dell          | Latitude E5420              | Notebook    | [0b1b042a5b](https://linux-hardware.org/?probe=0b1b042a5b) | Sep 19, 2023 |
| HP            | Notebook                    | Notebook    | [c41430992d](https://linux-hardware.org/?probe=c41430992d) | Sep 18, 2023 |
| HP            | 158B                        | Desktop     | [f8385c7d22](https://linux-hardware.org/?probe=f8385c7d22) | Sep 18, 2023 |
| HP            | 158B                        | Desktop     | [986f0c6ba1](https://linux-hardware.org/?probe=986f0c6ba1) | Sep 15, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [ac96127f34](https://linux-hardware.org/?probe=ac96127f34) | Sep 08, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [779e2ad458](https://linux-hardware.org/?probe=779e2ad458) | Sep 08, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [c0498360ff](https://linux-hardware.org/?probe=c0498360ff) | Sep 07, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [6cc92a61b2](https://linux-hardware.org/?probe=6cc92a61b2) | Sep 07, 2023 |
| Dell          | Inspiron 5379               | Notebook    | [cafe064514](https://linux-hardware.org/?probe=cafe064514) | Sep 05, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [f06bf24212](https://linux-hardware.org/?probe=f06bf24212) | Sep 05, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [167ab1eb1c](https://linux-hardware.org/?probe=167ab1eb1c) | Sep 05, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [dc9d1ca231](https://linux-hardware.org/?probe=dc9d1ca231) | Sep 04, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [b980688633](https://linux-hardware.org/?probe=b980688633) | Sep 04, 2023 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [727e431acb](https://linux-hardware.org/?probe=727e431acb) | Sep 03, 2023 |
| Dell          | Inspiron 5379               | Notebook    | [1cbc463a43](https://linux-hardware.org/?probe=1cbc463a43) | Sep 02, 2023 |
| Dell          | Latitude 5490               | Notebook    | [058fba578a](https://linux-hardware.org/?probe=058fba578a) | Aug 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | Notebook    | [b7a28997df](https://linux-hardware.org/?probe=b7a28997df) | Aug 15, 2023 |
| Dell          | 00WGD1 A01                  | Server      | [d288d87ab5](https://linux-hardware.org/?probe=d288d87ab5) | Aug 14, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [d61d7e9135](https://linux-hardware.org/?probe=d61d7e9135) | Aug 14, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [d319474025](https://linux-hardware.org/?probe=d319474025) | Aug 13, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [0b7f8d13d9](https://linux-hardware.org/?probe=0b7f8d13d9) | Aug 12, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [8a896a42c0](https://linux-hardware.org/?probe=8a896a42c0) | Aug 12, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [b7245ccb6f](https://linux-hardware.org/?probe=b7245ccb6f) | Aug 11, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [cff9e815b3](https://linux-hardware.org/?probe=cff9e815b3) | Aug 11, 2023 |
| Timi          | RedmiBook 14-APCS           | Notebook    | [d8939be040](https://linux-hardware.org/?probe=d8939be040) | Aug 06, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [35b274571c](https://linux-hardware.org/?probe=35b274571c) | Aug 05, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [92d07e2cae](https://linux-hardware.org/?probe=92d07e2cae) | Aug 05, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [592e977971](https://linux-hardware.org/?probe=592e977971) | Aug 04, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [d05269baea](https://linux-hardware.org/?probe=d05269baea) | Aug 04, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [e5659701d5](https://linux-hardware.org/?probe=e5659701d5) | Jul 26, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [b84ef586e7](https://linux-hardware.org/?probe=b84ef586e7) | Jul 26, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [68cf987c86](https://linux-hardware.org/?probe=68cf987c86) | Jul 25, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [8dc4e130f9](https://linux-hardware.org/?probe=8dc4e130f9) | Jul 25, 2023 |
| HP            | 17-ak041ur                  | Notebook    | [5881affa24](https://linux-hardware.org/?probe=5881affa24) | Jul 18, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [058672ddad](https://linux-hardware.org/?probe=058672ddad) | Jul 18, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [2330d7d072](https://linux-hardware.org/?probe=2330d7d072) | Jul 15, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [757ed62cbc](https://linux-hardware.org/?probe=757ed62cbc) | Jul 14, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [41261aa128](https://linux-hardware.org/?probe=41261aa128) | Jul 14, 2023 |
| Dell          | Inspiron 5555               | Notebook    | [a63fbcabfb](https://linux-hardware.org/?probe=a63fbcabfb) | Jul 14, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [ab93f5aa6e](https://linux-hardware.org/?probe=ab93f5aa6e) | Jul 09, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [59f9ee3ee8](https://linux-hardware.org/?probe=59f9ee3ee8) | Jul 09, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [2ee9eaf9d4](https://linux-hardware.org/?probe=2ee9eaf9d4) | Jul 08, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [a686a6eed6](https://linux-hardware.org/?probe=a686a6eed6) | Jul 08, 2023 |
| Gigabyte      | X570S UD                    | Desktop     | [cd368fbd36](https://linux-hardware.org/?probe=cd368fbd36) | Jul 07, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [b7e8961ef5](https://linux-hardware.org/?probe=b7e8961ef5) | Jul 03, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [da271abdd3](https://linux-hardware.org/?probe=da271abdd3) | Jul 03, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [2beb4fa40d](https://linux-hardware.org/?probe=2beb4fa40d) | Jul 02, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [92bf7e658e](https://linux-hardware.org/?probe=92bf7e658e) | Jul 02, 2023 |
| Dell          | Inspiron 5555               | Notebook    | [011aa45cc1](https://linux-hardware.org/?probe=011aa45cc1) | Jul 01, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [c86548f8aa](https://linux-hardware.org/?probe=c86548f8aa) | Jul 01, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [57424619e8](https://linux-hardware.org/?probe=57424619e8) | Jul 01, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [70ed50862c](https://linux-hardware.org/?probe=70ed50862c) | Jun 30, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [52b4c086dc](https://linux-hardware.org/?probe=52b4c086dc) | Jun 30, 2023 |
| Dell          | Inspiron 5555               | Notebook    | [7c07dbad40](https://linux-hardware.org/?probe=7c07dbad40) | Jun 29, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [c7e845c965](https://linux-hardware.org/?probe=c7e845c965) | Jun 26, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [f36489e090](https://linux-hardware.org/?probe=f36489e090) | Jun 26, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [d56f78f3ca](https://linux-hardware.org/?probe=d56f78f3ca) | Jun 25, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [cf3b44c0b6](https://linux-hardware.org/?probe=cf3b44c0b6) | Jun 25, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [2256046a01](https://linux-hardware.org/?probe=2256046a01) | Jun 11, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [8738063b30](https://linux-hardware.org/?probe=8738063b30) | Jun 11, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [15fb7b8736](https://linux-hardware.org/?probe=15fb7b8736) | Jun 10, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [8e10de95af](https://linux-hardware.org/?probe=8e10de95af) | Jun 10, 2023 |
| Maibenben     | MaiBook X series            | Notebook    | [5ca7ad5fb0](https://linux-hardware.org/?probe=5ca7ad5fb0) | Jun 07, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [a777ee9e06](https://linux-hardware.org/?probe=a777ee9e06) | Jun 06, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [9c282e76a6](https://linux-hardware.org/?probe=9c282e76a6) | Jun 06, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [7b384a40ce](https://linux-hardware.org/?probe=7b384a40ce) | Jun 05, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [4592ff63f3](https://linux-hardware.org/?probe=4592ff63f3) | Jun 05, 2023 |
| Dell          | Inspiron 5555               | Notebook    | [e14ab40d68](https://linux-hardware.org/?probe=e14ab40d68) | Jun 03, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [1243c65107](https://linux-hardware.org/?probe=1243c65107) | Jun 01, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [9a28272d6e](https://linux-hardware.org/?probe=9a28272d6e) | Jun 01, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [15e410d9f7](https://linux-hardware.org/?probe=15e410d9f7) | May 31, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [cffbd92b9f](https://linux-hardware.org/?probe=cffbd92b9f) | May 31, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [b1d9682c13](https://linux-hardware.org/?probe=b1d9682c13) | May 30, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [399cce0d30](https://linux-hardware.org/?probe=399cce0d30) | May 30, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [15d9c6fce4](https://linux-hardware.org/?probe=15d9c6fce4) | May 29, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [531455206b](https://linux-hardware.org/?probe=531455206b) | May 29, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [5726f59661](https://linux-hardware.org/?probe=5726f59661) | May 23, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [12a444a75a](https://linux-hardware.org/?probe=12a444a75a) | May 23, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [9cc4cbef4a](https://linux-hardware.org/?probe=9cc4cbef4a) | May 22, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [0f9deafb62](https://linux-hardware.org/?probe=0f9deafb62) | May 22, 2023 |
| MSI           | GL75 9SE                    | Notebook    | [7fd4d531c9](https://linux-hardware.org/?probe=7fd4d531c9) | May 18, 2023 |
| Dell          | 0FDY5C A00                  | Desktop     | [3d9b02954b](https://linux-hardware.org/?probe=3d9b02954b) | May 16, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [40aa9853c4](https://linux-hardware.org/?probe=40aa9853c4) | May 15, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [465488c540](https://linux-hardware.org/?probe=465488c540) | May 15, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [8d933d6988](https://linux-hardware.org/?probe=8d933d6988) | May 14, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [413d3b7b92](https://linux-hardware.org/?probe=413d3b7b92) | May 14, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [f074512a99](https://linux-hardware.org/?probe=f074512a99) | May 13, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [2a69d13961](https://linux-hardware.org/?probe=2a69d13961) | May 13, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [afd35343ad](https://linux-hardware.org/?probe=afd35343ad) | May 12, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [208afe074a](https://linux-hardware.org/?probe=208afe074a) | May 12, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [ac5899bc10](https://linux-hardware.org/?probe=ac5899bc10) | May 09, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [64bd100bb5](https://linux-hardware.org/?probe=64bd100bb5) | May 09, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [55af41b298](https://linux-hardware.org/?probe=55af41b298) | May 08, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [28a1f44a1e](https://linux-hardware.org/?probe=28a1f44a1e) | May 08, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [0f5dab42d2](https://linux-hardware.org/?probe=0f5dab42d2) | May 02, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [2849b9a200](https://linux-hardware.org/?probe=2849b9a200) | May 02, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [028a3c3b0b](https://linux-hardware.org/?probe=028a3c3b0b) | May 01, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [34e7df2c84](https://linux-hardware.org/?probe=34e7df2c84) | May 01, 2023 |
| ASRockRack    | ROMED8-2T                   | Server      | [457abef5d3](https://linux-hardware.org/?probe=457abef5d3) | May 01, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [31789f9473](https://linux-hardware.org/?probe=31789f9473) | Apr 30, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [f46e9f6ba7](https://linux-hardware.org/?probe=f46e9f6ba7) | Apr 30, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [be2089d630](https://linux-hardware.org/?probe=be2089d630) | Apr 27, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [9fdfb825c7](https://linux-hardware.org/?probe=9fdfb825c7) | Apr 27, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [9465aab832](https://linux-hardware.org/?probe=9465aab832) | Apr 26, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [b24f39801d](https://linux-hardware.org/?probe=b24f39801d) | Apr 26, 2023 |
| Dell          | 0FDY5C A00                  | Desktop     | [ddf678b11a](https://linux-hardware.org/?probe=ddf678b11a) | Apr 20, 2023 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [c370821f44](https://linux-hardware.org/?probe=c370821f44) | Apr 17, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [6e9640e9c2](https://linux-hardware.org/?probe=6e9640e9c2) | Apr 15, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [6eb92e0ea0](https://linux-hardware.org/?probe=6eb92e0ea0) | Apr 12, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [9dd9a74143](https://linux-hardware.org/?probe=9dd9a74143) | Apr 12, 2023 |
| MSI           | B85-G43                     | Desktop     | [49c7de9ea6](https://linux-hardware.org/?probe=49c7de9ea6) | Apr 08, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [fc2425ffde](https://linux-hardware.org/?probe=fc2425ffde) | Apr 08, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [ac75c58117](https://linux-hardware.org/?probe=ac75c58117) | Apr 06, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [d699519c30](https://linux-hardware.org/?probe=d699519c30) | Apr 06, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [9ef8e7a3d6](https://linux-hardware.org/?probe=9ef8e7a3d6) | Apr 02, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [fbd686e3e2](https://linux-hardware.org/?probe=fbd686e3e2) | Apr 02, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [61297d4bc4](https://linux-hardware.org/?probe=61297d4bc4) | Apr 01, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [acb0f81194](https://linux-hardware.org/?probe=acb0f81194) | Apr 01, 2023 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Desktop     | [3c3474d69b](https://linux-hardware.org/?probe=3c3474d69b) | Mar 28, 2023 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Desktop     | [21f6af6f50](https://linux-hardware.org/?probe=21f6af6f50) | Mar 28, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [586decd061](https://linux-hardware.org/?probe=586decd061) | Mar 27, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [d96c0cfcd9](https://linux-hardware.org/?probe=d96c0cfcd9) | Mar 27, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [56d537b480](https://linux-hardware.org/?probe=56d537b480) | Mar 26, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [da489de02c](https://linux-hardware.org/?probe=da489de02c) | Mar 26, 2023 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [1584039ca8](https://linux-hardware.org/?probe=1584039ca8) | Mar 24, 2023 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [a8e6ba1268](https://linux-hardware.org/?probe=a8e6ba1268) | Mar 24, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [0fc5cf1944](https://linux-hardware.org/?probe=0fc5cf1944) | Mar 19, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [d21d79ee06](https://linux-hardware.org/?probe=d21d79ee06) | Mar 19, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | Notebook    | [97af59e728](https://linux-hardware.org/?probe=97af59e728) | Mar 18, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [173e6ad8bf](https://linux-hardware.org/?probe=173e6ad8bf) | Mar 18, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [17e455c4df](https://linux-hardware.org/?probe=17e455c4df) | Mar 18, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [43b58e51b4](https://linux-hardware.org/?probe=43b58e51b4) | Mar 12, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [7d42741fac](https://linux-hardware.org/?probe=7d42741fac) | Mar 12, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [6b87ac7144](https://linux-hardware.org/?probe=6b87ac7144) | Mar 11, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [c5419b8b27](https://linux-hardware.org/?probe=c5419b8b27) | Mar 11, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [f98fe964b2](https://linux-hardware.org/?probe=f98fe964b2) | Mar 07, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [70b5b39ce8](https://linux-hardware.org/?probe=70b5b39ce8) | Mar 07, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [da9d93a7ea](https://linux-hardware.org/?probe=da9d93a7ea) | Mar 06, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [77ca3b430b](https://linux-hardware.org/?probe=77ca3b430b) | Mar 06, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [81c9f3a796](https://linux-hardware.org/?probe=81c9f3a796) | Mar 04, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [a750fc7c24](https://linux-hardware.org/?probe=a750fc7c24) | Mar 04, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [ff1f611cc9](https://linux-hardware.org/?probe=ff1f611cc9) | Mar 03, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [0a8ce98d46](https://linux-hardware.org/?probe=0a8ce98d46) | Mar 03, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [975790ee68](https://linux-hardware.org/?probe=975790ee68) | Mar 01, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [92300b45fe](https://linux-hardware.org/?probe=92300b45fe) | Mar 01, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [3b0e50edda](https://linux-hardware.org/?probe=3b0e50edda) | Feb 28, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [6ccb40f64d](https://linux-hardware.org/?probe=6ccb40f64d) | Feb 28, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [126100b078](https://linux-hardware.org/?probe=126100b078) | Feb 25, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [fb42cba088](https://linux-hardware.org/?probe=fb42cba088) | Feb 25, 2023 |
| Google        | Kefka                       | Notebook    | [8142fbc91a](https://linux-hardware.org/?probe=8142fbc91a) | Feb 24, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [6ecc72101c](https://linux-hardware.org/?probe=6ecc72101c) | Feb 24, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [59ec61666a](https://linux-hardware.org/?probe=59ec61666a) | Feb 24, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [cf977da464](https://linux-hardware.org/?probe=cf977da464) | Feb 18, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [2a2dfe19fc](https://linux-hardware.org/?probe=2a2dfe19fc) | Feb 18, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [0001e56a68](https://linux-hardware.org/?probe=0001e56a68) | Feb 17, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [c913edda07](https://linux-hardware.org/?probe=c913edda07) | Feb 17, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [016e12b43e](https://linux-hardware.org/?probe=016e12b43e) | Feb 12, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [3e048e046a](https://linux-hardware.org/?probe=3e048e046a) | Feb 12, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [4599836936](https://linux-hardware.org/?probe=4599836936) | Feb 11, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [9a81107301](https://linux-hardware.org/?probe=9a81107301) | Feb 11, 2023 |
| HP            | 8455                        | Desktop     | [ffc8587d29](https://linux-hardware.org/?probe=ffc8587d29) | Feb 08, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [84ba50b16d](https://linux-hardware.org/?probe=84ba50b16d) | Feb 08, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [0593b2bac6](https://linux-hardware.org/?probe=0593b2bac6) | Feb 08, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [ee7dbe4f81](https://linux-hardware.org/?probe=ee7dbe4f81) | Feb 07, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [a019143fe9](https://linux-hardware.org/?probe=a019143fe9) | Feb 07, 2023 |
| AZW           | SER                         | Mini pc     | [dd0c654d95](https://linux-hardware.org/?probe=dd0c654d95) | Feb 04, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [a0f53917f9](https://linux-hardware.org/?probe=a0f53917f9) | Feb 04, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [768696d7b8](https://linux-hardware.org/?probe=768696d7b8) | Feb 04, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [04a26e636e](https://linux-hardware.org/?probe=04a26e636e) | Feb 03, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [6bb0e68672](https://linux-hardware.org/?probe=6bb0e68672) | Feb 03, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [5b505d5d7a](https://linux-hardware.org/?probe=5b505d5d7a) | Feb 02, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [f6ad918c7e](https://linux-hardware.org/?probe=f6ad918c7e) | Feb 02, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [21ce876854](https://linux-hardware.org/?probe=21ce876854) | Feb 01, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [cca8d74416](https://linux-hardware.org/?probe=cca8d74416) | Feb 01, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [602482d070](https://linux-hardware.org/?probe=602482d070) | Feb 01, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [f0884ec1aa](https://linux-hardware.org/?probe=f0884ec1aa) | Jan 31, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [89430aeb82](https://linux-hardware.org/?probe=89430aeb82) | Jan 31, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [af3cf25119](https://linux-hardware.org/?probe=af3cf25119) | Jan 31, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [6d079ed3ca](https://linux-hardware.org/?probe=6d079ed3ca) | Jan 30, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [d81d33bda5](https://linux-hardware.org/?probe=d81d33bda5) | Jan 30, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [ec76a40223](https://linux-hardware.org/?probe=ec76a40223) | Jan 30, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [e4289105c5](https://linux-hardware.org/?probe=e4289105c5) | Jan 30, 2023 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | Desktop     | [ee36c9d395](https://linux-hardware.org/?probe=ee36c9d395) | Jan 30, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [725c2a80f8](https://linux-hardware.org/?probe=725c2a80f8) | Jan 29, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [091b3e37fb](https://linux-hardware.org/?probe=091b3e37fb) | Jan 29, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [49654976af](https://linux-hardware.org/?probe=49654976af) | Jan 29, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [6b99585bc0](https://linux-hardware.org/?probe=6b99585bc0) | Jan 29, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [d41a70cbf5](https://linux-hardware.org/?probe=d41a70cbf5) | Jan 28, 2023 |
| Lenovo        | V14-ARE 82DQ                | Notebook    | [9fbcd4b714](https://linux-hardware.org/?probe=9fbcd4b714) | Jan 28, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [af868046e3](https://linux-hardware.org/?probe=af868046e3) | Jan 26, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [b9f3d19faa](https://linux-hardware.org/?probe=b9f3d19faa) | Jan 26, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [df1811bf5d](https://linux-hardware.org/?probe=df1811bf5d) | Jan 26, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [7c026252d0](https://linux-hardware.org/?probe=7c026252d0) | Jan 24, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [bd3f6fa130](https://linux-hardware.org/?probe=bd3f6fa130) | Jan 24, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [477f1a3aad](https://linux-hardware.org/?probe=477f1a3aad) | Jan 24, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [71a9255bc8](https://linux-hardware.org/?probe=71a9255bc8) | Jan 24, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [e327d1dea4](https://linux-hardware.org/?probe=e327d1dea4) | Jan 24, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [f62d0d9183](https://linux-hardware.org/?probe=f62d0d9183) | Jan 24, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [ed6204876e](https://linux-hardware.org/?probe=ed6204876e) | Jan 22, 2023 |
| HP            | Falco                       | Notebook    | [a52a8f8f4e](https://linux-hardware.org/?probe=a52a8f8f4e) | Jan 14, 2023 |
| Dell          | Latitude E6510              | Notebook    | [dab9cdc1be](https://linux-hardware.org/?probe=dab9cdc1be) | Jan 11, 2023 |
| Dell          | XPS 13 9365                 | Convertible | [2b4b7560b7](https://linux-hardware.org/?probe=2b4b7560b7) | Jan 10, 2023 |
| HP            | 158A                        | Desktop     | [c0e1c9b6e6](https://linux-hardware.org/?probe=c0e1c9b6e6) | Jan 09, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [56758aeb6f](https://linux-hardware.org/?probe=56758aeb6f) | Jan 07, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [ec3b130618](https://linux-hardware.org/?probe=ec3b130618) | Jan 07, 2023 |
| MSI           | A88X-G45 GAMING             | Desktop     | [891e0757ed](https://linux-hardware.org/?probe=891e0757ed) | Dec 31, 2022 |
| MSI           | A88X-G45 GAMING             | Desktop     | [bdb45edaad](https://linux-hardware.org/?probe=bdb45edaad) | Dec 31, 2022 |
| HP            | Falco                       | Notebook    | [61ce7c6739](https://linux-hardware.org/?probe=61ce7c6739) | Dec 21, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [4571b799f0](https://linux-hardware.org/?probe=4571b799f0) | Dec 20, 2022 |
| Optimized ... | KVM                         | Desktop     | [d62625a751](https://linux-hardware.org/?probe=d62625a751) | Dec 13, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [95d47d14cb](https://linux-hardware.org/?probe=95d47d14cb) | Dec 09, 2022 |
| Lenovo        | B50-30 20382                | Notebook    | [3706f368de](https://linux-hardware.org/?probe=3706f368de) | Nov 24, 2022 |
| Gigabyte      | H81M-D2V                    | Desktop     | [6035f1ee45](https://linux-hardware.org/?probe=6035f1ee45) | Nov 11, 2022 |
| ASUSTek       | Q170M2                      | Desktop     | [c62954095d](https://linux-hardware.org/?probe=c62954095d) | Nov 11, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [832ebcb956](https://linux-hardware.org/?probe=832ebcb956) | Nov 03, 2022 |
| HP            | ProLiant DL360p Gen8        | Server      | [ef43d1f352](https://linux-hardware.org/?probe=ef43d1f352) | Nov 03, 2022 |
| Toshiba       | Satellite L50-C             | Notebook    | [b3e0ff9849](https://linux-hardware.org/?probe=b3e0ff9849) | Nov 01, 2022 |
| Acer          | TMP453-MG                   | Notebook    | [4d36d13ea9](https://linux-hardware.org/?probe=4d36d13ea9) | Oct 01, 2022 |
| Lenovo        | 1052 NOK                    | Desktop     | [28cd1416fe](https://linux-hardware.org/?probe=28cd1416fe) | Sep 22, 2022 |
| Acer          | TravelMate 5735Z            | Notebook    | [b920fce554](https://linux-hardware.org/?probe=b920fce554) | Sep 17, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [7e56cce9c8](https://linux-hardware.org/?probe=7e56cce9c8) | Sep 17, 2022 |
| HP            | Falco                       | Notebook    | [5fa86b77d6](https://linux-hardware.org/?probe=5fa86b77d6) | Sep 17, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [c01403937e](https://linux-hardware.org/?probe=c01403937e) | Sep 08, 2022 |
| HP            | ENVY dv6                    | Notebook    | [e7bc07047b](https://linux-hardware.org/?probe=e7bc07047b) | Aug 24, 2022 |
| Gigabyte      | MP32-AR1-00 01010101        | Server      | [e93d3eae0d](https://linux-hardware.org/?probe=e93d3eae0d) | Jul 20, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [82b34535ae](https://linux-hardware.org/?probe=82b34535ae) | Jul 06, 2022 |
| ASRock        | B460 Phantom Gaming 4       | Desktop     | [0dc125da55](https://linux-hardware.org/?probe=0dc125da55) | Jul 05, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [d6adb170de](https://linux-hardware.org/?probe=d6adb170de) | Jun 25, 2022 |
| Google        | Kohaku                      | Notebook    | [f43841c5e0](https://linux-hardware.org/?probe=f43841c5e0) | Jun 08, 2022 |
| Google        | Kohaku                      | Notebook    | [740a608274](https://linux-hardware.org/?probe=740a608274) | Jun 08, 2022 |
| Lenovo        | ThinkPad T440s 20ARS32P0... | Notebook    | [100b65a86d](https://linux-hardware.org/?probe=100b65a86d) | Jun 04, 2022 |
| Dell          | 060K5C A06                  | Server      | [c8be539d80](https://linux-hardware.org/?probe=c8be539d80) | May 14, 2022 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | Notebook    | [2fecc1fd76](https://linux-hardware.org/?probe=2fecc1fd76) | Apr 20, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [5ac68bc542](https://linux-hardware.org/?probe=5ac68bc542) | Mar 16, 2022 |
| Gigabyte      | Z590 AORUS PRO AX           | Desktop     | [a517886d4d](https://linux-hardware.org/?probe=a517886d4d) | Feb 10, 2022 |
| Dell          | 0R4CNN A02                  | Server      | [c701d3a15f](https://linux-hardware.org/?probe=c701d3a15f) | Feb 07, 2022 |
| Intel         | powered classmate PC        | Notebook    | [0585f5b715](https://linux-hardware.org/?probe=0585f5b715) | Dec 12, 2021 |
| Intel         | powered classmate PC        | Notebook    | [9416f348e4](https://linux-hardware.org/?probe=9416f348e4) | Dec 12, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [c28c41bdd4](https://linux-hardware.org/?probe=c28c41bdd4) | Nov 05, 2021 |
| Dell          | Inspiron 3185               | Notebook    | [53ac57fbea](https://linux-hardware.org/?probe=53ac57fbea) | Oct 26, 2021 |
| Dell          | Inspiron 3185               | Notebook    | [2c9cec7881](https://linux-hardware.org/?probe=2c9cec7881) | Oct 01, 2021 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [1a59499d3a](https://linux-hardware.org/?probe=1a59499d3a) | Sep 29, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [95a2b3a95d](https://linux-hardware.org/?probe=95a2b3a95d) | Aug 27, 2021 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [972f935578](https://linux-hardware.org/?probe=972f935578) | Aug 23, 2021 |
| HP            | EliteBook 8570w             | Notebook    | [37e72494a5](https://linux-hardware.org/?probe=37e72494a5) | Jul 29, 2021 |
| ASUSTek       | ASUS EXPERTBOOK B9450FA_... | Notebook    | [cdf0f4017c](https://linux-hardware.org/?probe=cdf0f4017c) | Jul 16, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [9044b57593](https://linux-hardware.org/?probe=9044b57593) | Jul 11, 2021 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [21a6135eda](https://linux-hardware.org/?probe=21a6135eda) | Jun 16, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [e5a30a171e](https://linux-hardware.org/?probe=e5a30a171e) | Jun 08, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [043878564d](https://linux-hardware.org/?probe=043878564d) | Jun 08, 2021 |
| Dell          | Inspiron 3185               | Notebook    | [84fa76eb2f](https://linux-hardware.org/?probe=84fa76eb2f) | Apr 20, 2021 |
| Dell          | Inspiron 3185               | Notebook    | [d49edb76fa](https://linux-hardware.org/?probe=d49edb76fa) | Apr 15, 2021 |
| Dell          | Inspiron 3185               | Notebook    | [15b8da5bc1](https://linux-hardware.org/?probe=15b8da5bc1) | Apr 14, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [f0791eb42d](https://linux-hardware.org/?probe=f0791eb42d) | Mar 30, 2021 |
| HP            | 0AE8h C                     | Desktop     | [b7fd559b13](https://linux-hardware.org/?probe=b7fd559b13) | Mar 24, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [8810309035](https://linux-hardware.org/?probe=8810309035) | Mar 24, 2021 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| AlmaLinux 9.1 | 21        | 16.41%  |
| AlmaLinux 9.3 | 20        | 15.63%  |
| AlmaLinux 9.2 | 20        | 15.63%  |
| AlmaLinux 8.8 | 11        | 8.59%   |
| AlmaLinux 8.6 | 11        | 8.59%   |
| AlmaLinux 8.9 | 10        | 7.81%   |
| AlmaLinux 8.7 | 10        | 7.81%   |
| AlmaLinux 9.0 | 9         | 7.03%   |
| AlmaLinux 8.4 | 9         | 7.03%   |
| AlmaLinux 8.3 | 4         | 3.13%   |
| AlmaLinux 8.5 | 3         | 2.34%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| AlmaLinux | 113       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 5.14.0-362.8.1.el9_3.x86_64  | 8         | 5.56%   |
| 5.14.0-284.30.1.el9_2.x86_64 | 8         | 5.56%   |
| 5.14.0-162.6.1.el9_1.x86_64  | 8         | 5.56%   |
| 4.18.0-425.3.1.el8.x86_64    | 7         | 4.86%   |
| 5.14.0-162.12.1.el9_1.x86_64 | 6         | 4.17%   |
| 4.18.0-477.27.2.el8_8.x86_64 | 6         | 4.17%   |
| 5.14.0-362.13.1.el9_3.x86_64 | 5         | 3.47%   |
| 5.14.0-284.25.1.el9_2.x86_64 | 5         | 3.47%   |
| 4.18.0-477.21.1.el8_8.x86_64 | 5         | 3.47%   |
| 4.18.0-513.9.1.el8_9.x86_64  | 4         | 2.78%   |
| 4.18.0-477.13.1.el8_8.x86_64 | 4         | 2.78%   |
| 5.14.0-70.22.1.el9_0.x86_64  | 3         | 2.08%   |
| 5.14.0-362.24.2.el9_3.x86_64 | 3         | 2.08%   |
| 5.14.0-362.18.1.el9_3.x86_64 | 3         | 2.08%   |
| 5.14.0-284.18.1.el9_2.x86_64 | 3         | 2.08%   |
| 5.14.0-284.11.1.el9_2.x86_64 | 3         | 2.08%   |
| 5.14.0-162.18.1.el9_1.x86_64 | 3         | 2.08%   |
| 4.18.0-372.26.1.el8_6.x86_64 | 3         | 2.08%   |
| 4.18.0-240.15.1.el8_3.x86_64 | 3         | 2.08%   |
| 5.14.0-70.30.1.el9_0.x86_64  | 2         | 1.39%   |
| 5.14.0-70.13.1.el9_0.x86_64  | 2         | 1.39%   |
| 5.14.0-162.22.2.el9_1.x86_64 | 2         | 1.39%   |
| 4.18.0-513.24.1.el8_9.x86_64 | 2         | 1.39%   |
| 4.18.0-513.18.1.el8_9.x86_64 | 2         | 1.39%   |
| 4.18.0-477.27.1.el8_8.x86_64 | 2         | 1.39%   |
| 4.18.0-477.15.1.el8_8.x86_64 | 2         | 1.39%   |
| 4.18.0-477.10.1.el8_8.x86_64 | 2         | 1.39%   |
| 4.18.0-425.19.2.el8_7.x86_64 | 2         | 1.39%   |
| 4.18.0-425.13.1.el8_7.x86_64 | 2         | 1.39%   |
| 4.18.0-372.9.1.el8.x86_64    | 2         | 1.39%   |
| 4.18.0-348.12.2.el8_5.x86_64 | 2         | 1.39%   |
| 4.18.0-305.el8.x86_64        | 2         | 1.39%   |
| 4.18.0-305.7.1.el8_4.x86_64  | 2         | 1.39%   |
| 4.18.0-305.12.1.el8_4.x86_64 | 2         | 1.39%   |
| 6.8.8-1.el8.elrepo.x86_64    | 1         | 0.69%   |
| 6.8.7-1.el8.elrepo.x86_64    | 1         | 0.69%   |
| 6.4.0-1.el8.elrepo.x86_64    | 1         | 0.69%   |
| 6.3.0-2.el9.elrepo.x86_64    | 1         | 0.69%   |
| 6.1.81-1.el9.elrepo.x86_64   | 1         | 0.69%   |
| 6.1.31-v8.1.el9              | 1         | 0.69%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14.0  | 64        | 54.7%   |
| 4.18.0  | 42        | 35.9%   |
| 6.8.8   | 1         | 0.85%   |
| 6.8.7   | 1         | 0.85%   |
| 6.4.0   | 1         | 0.85%   |
| 6.3.0   | 1         | 0.85%   |
| 6.1.81  | 1         | 0.85%   |
| 6.1.31  | 1         | 0.85%   |
| 6.1.24  | 1         | 0.85%   |
| 5.4.274 | 1         | 0.85%   |
| 5.4.175 | 1         | 0.85%   |
| 5.15.45 | 1         | 0.85%   |
| 5.10.60 | 1         | 0.85%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14    | 64        | 54.7%   |
| 4.18    | 42        | 35.9%   |
| 6.1     | 3         | 2.56%   |
| 6.8     | 2         | 1.71%   |
| 5.4     | 2         | 1.71%   |
| 6.4     | 1         | 0.85%   |
| 6.3     | 1         | 0.85%   |
| 5.15    | 1         | 0.85%   |
| 5.10    | 1         | 0.85%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 110       | 97.35%  |
| aarch64 | 3         | 2.65%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 68        | 59.13%  |
| Unknown         | 22        | 19.13%  |
| KDE5            | 9         | 7.83%   |
| XFCE            | 8         | 6.96%   |
| MATE            | 3         | 2.61%   |
| GNOME Classic   | 2         | 1.74%   |
| X-Cinnamon      | 1         | 0.87%   |
| GNOME Flashback | 1         | 0.87%   |
| Cinnamon        | 1         | 0.87%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 53        | 45.3%   |
| X11     | 48        | 41.03%  |
| Unknown | 9         | 7.69%   |
| Tty     | 6         | 5.13%   |
| Web     | 1         | 0.85%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 62        | 54.39%  |
| GDM     | 42        | 36.84%  |
| SDDM    | 5         | 4.39%   |
| LightDM | 5         | 4.39%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 61        | 52.59%  |
| en_GB   | 10        | 8.62%   |
| de_DE   | 9         | 7.76%   |
| C       | 5         | 4.31%   |
| fr_FR   | 4         | 3.45%   |
| en_CA   | 4         | 3.45%   |
| ru_RU   | 3         | 2.59%   |
| pl_PL   | 3         | 2.59%   |
| Unknown | 3         | 2.59%   |
| it_IT   | 2         | 1.72%   |
| hu_HU   | 2         | 1.72%   |
| en_AU   | 2         | 1.72%   |
| zh_CN   | 1         | 0.86%   |
| uk_UA   | 1         | 0.86%   |
| ru_UA   | 1         | 0.86%   |
| es_VE   | 1         | 0.86%   |
| es_ES   | 1         | 0.86%   |
| en_IN   | 1         | 0.86%   |
| en_IE   | 1         | 0.86%   |
| da_DK   | 1         | 0.86%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 76        | 66.09%  |
| BIOS | 39        | 33.91%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Xfs     | 88        | 76.52%  |
| Ext4    | 23        | 20%     |
| Tmpfs   | 2         | 1.74%   |
| Overlay | 1         | 0.87%   |
| Btrfs   | 1         | 0.87%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 57        | 50.44%  |
| Unknown | 40        | 35.4%   |
| MBR     | 16        | 14.16%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 97        | 85.84%  |
| Yes       | 16        | 14.16%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 97        | 85.84%  |
| Yes       | 16        | 14.16%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 21        | 18.58%  |
| Lenovo                  | 20        | 17.7%   |
| Dell                    | 15        | 13.27%  |
| ASUSTek Computer        | 9         | 7.96%   |
| MSI                     | 6         | 5.31%   |
| Gigabyte Technology     | 6         | 5.31%   |
| Intel                   | 5         | 4.42%   |
| ASRockRack              | 5         | 4.42%   |
| Acer                    | 5         | 4.42%   |
| Supermicro              | 4         | 3.54%   |
| Toshiba                 | 2         | 1.77%   |
| Timi                    | 2         | 1.77%   |
| Raspberry Pi Foundation | 2         | 1.77%   |
| Google                  | 2         | 1.77%   |
| ASRock                  | 2         | 1.77%   |
| TUXEDO                  | 1         | 0.88%   |
| Optimized Hosting       | 1         | 0.88%   |
| Notebook                | 1         | 0.88%   |
| Maibenben               | 1         | 0.88%   |
| Haier                   | 1         | 0.88%   |
| AZW                     | 1         | 0.88%   |
| AOCWEI                  | 1         | 0.88%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| RPi Raspberry Pi                         | 2         | 1.77%   |
| ASRockRack B650D4U-2L2T/BCM              | 2         | 1.77%   |
| TUXEDO Aura 15 Gen1                      | 1         | 0.88%   |
| Toshiba Satellite L50-C                  | 1         | 0.88%   |
| Toshiba Satellite C50-A                  | 1         | 0.88%   |
| Timi TM1709                              | 1         | 0.88%   |
| Timi RedmiBook 14-APCS                   | 1         | 0.88%   |
| Supermicro X8DTT-H                       | 1         | 0.88%   |
| Supermicro Super Server                  | 1         | 0.88%   |
| Supermicro PIO-617R-TLN4F+-ST031         | 1         | 0.88%   |
| Supermicro motherboard-H12 Series        | 1         | 0.88%   |
| Optimized Hosting KVM                    | 1         | 0.88%   |
| Notebook NS50_70MU                       | 1         | 0.88%   |
| MSI MS-7D91                              | 1         | 0.88%   |
| MSI MS-7D07                              | 1         | 0.88%   |
| MSI MS-7C95                              | 1         | 0.88%   |
| MSI MS-7900                              | 1         | 0.88%   |
| MSI MS-7816                              | 1         | 0.88%   |
| MSI GL75 9SE                             | 1         | 0.88%   |
| Maibenben MaiBook X series               | 1         | 0.88%   |
| Lenovo Yoga 2 13 20344                   | 1         | 0.88%   |
| Lenovo V14-ARE 82DQ                      | 1         | 0.88%   |
| Lenovo ThinkStation P350 30E6S20S00      | 1         | 0.88%   |
| Lenovo ThinkPad X1 Nano Gen 1 20UNS02500 | 1         | 0.88%   |
| Lenovo ThinkPad X1 Carbon 6th 20KH006JRT | 1         | 0.88%   |
| Lenovo ThinkPad T480s 20L70028US         | 1         | 0.88%   |
| Lenovo ThinkPad T440s 20ARS32P00         | 1         | 0.88%   |
| Lenovo ThinkPad T14 Gen 1 20S1S39Q00     | 1         | 0.88%   |
| Lenovo ThinkPad P1 Gen 4i 20Y3003XUS     | 1         | 0.88%   |
| Lenovo ThinkPad E14 Gen 2 20TBS0CK00     | 1         | 0.88%   |
| Lenovo Legion Y530-15ICH 81FV            | 1         | 0.88%   |
| Lenovo Legion 5 15IMH05H 81Y6            | 1         | 0.88%   |
| Lenovo IdeaPadFlex 5 14ITL05 82HS        | 1         | 0.88%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS      | 1         | 0.88%   |
| Lenovo IdeaPad S145-15IWL 81MV           | 1         | 0.88%   |
| Lenovo IdeaPad 330-15ARR 81D2            | 1         | 0.88%   |
| Lenovo H520S 10093                       | 1         | 0.88%   |
| Lenovo H515s 10126                       | 1         | 0.88%   |
| Lenovo G580 20157                        | 1         | 0.88%   |
| Lenovo B50-30 20382                      | 1         | 0.88%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| Lenovo ThinkPad                  | 7         | 6.19%   |
| Lenovo IdeaPad                   | 3         | 2.65%   |
| HP Laptop                        | 3         | 2.65%   |
| HP EliteBook                     | 3         | 2.65%   |
| Dell Precision                   | 3         | 2.65%   |
| Dell Latitude                    | 3         | 2.65%   |
| Dell Inspiron                    | 3         | 2.65%   |
| Acer Aspire                      | 3         | 2.65%   |
| Toshiba Satellite                | 2         | 1.77%   |
| RPi Raspberry                    | 2         | 1.77%   |
| Lenovo Legion                    | 2         | 1.77%   |
| HP ENVY                          | 2         | 1.77%   |
| Dell XPS                         | 2         | 1.77%   |
| Dell PowerEdge                   | 2         | 1.77%   |
| Dell OptiPlex                    | 2         | 1.77%   |
| ASRockRack B650D4U-2L2T          | 2         | 1.77%   |
| TUXEDO Aura                      | 1         | 0.88%   |
| Timi TM1709                      | 1         | 0.88%   |
| Timi RedmiBook                   | 1         | 0.88%   |
| Supermicro X8DTT-H               | 1         | 0.88%   |
| Supermicro Super                 | 1         | 0.88%   |
| Supermicro PIO-617R-TLN4F+-ST031 | 1         | 0.88%   |
| Supermicro motherboard-H12       | 1         | 0.88%   |
| Optimized Hosting KVM            | 1         | 0.88%   |
| Notebook NS50                    | 1         | 0.88%   |
| MSI MS-7D91                      | 1         | 0.88%   |
| MSI MS-7D07                      | 1         | 0.88%   |
| MSI MS-7C95                      | 1         | 0.88%   |
| MSI MS-7900                      | 1         | 0.88%   |
| MSI MS-7816                      | 1         | 0.88%   |
| MSI GL75                         | 1         | 0.88%   |
| Maibenben MaiBook                | 1         | 0.88%   |
| Lenovo Yoga                      | 1         | 0.88%   |
| Lenovo V14-ARE                   | 1         | 0.88%   |
| Lenovo ThinkStation              | 1         | 0.88%   |
| Lenovo IdeaPadFlex               | 1         | 0.88%   |
| Lenovo H520S                     | 1         | 0.88%   |
| Lenovo H515s                     | 1         | 0.88%   |
| Lenovo G580                      | 1         | 0.88%   |
| Lenovo B50-30                    | 1         | 0.88%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 19        | 16.81%  |
| 2018    | 11        | 9.73%   |
| 2022    | 10        | 8.85%   |
| 2021    | 10        | 8.85%   |
| 2019    | 10        | 8.85%   |
| 2012    | 10        | 8.85%   |
| 2013    | 7         | 6.19%   |
| 2010    | 7         | 6.19%   |
| 2023    | 6         | 5.31%   |
| 2015    | 5         | 4.42%   |
| 2014    | 5         | 4.42%   |
| 2016    | 4         | 3.54%   |
| 2011    | 4         | 3.54%   |
| 2017    | 2         | 1.77%   |
| Unknown | 2         | 1.77%   |
| 2009    | 1         | 0.88%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 56        | 49.56%  |
| Desktop        | 37        | 32.74%  |
| Server         | 12        | 10.62%  |
| Mini pc        | 3         | 2.65%   |
| System on chip | 2         | 1.77%   |
| Convertible    | 2         | 1.77%   |
| Tablet         | 1         | 0.88%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 102       | 88.7%   |
| Enabled  | 13        | 11.3%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 110       | 97.35%  |
| Yes  | 3         | 2.65%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 29        | 25.44%  |
| 4.01-8.0        | 25        | 21.93%  |
| 64.01-256.0     | 18        | 15.79%  |
| 3.01-4.0        | 9         | 7.89%   |
| 32.01-64.0      | 8         | 7.02%   |
| 16.01-24.0      | 8         | 7.02%   |
| 24.01-32.0      | 7         | 6.14%   |
| More than 256.0 | 6         | 5.26%   |
| 1.01-2.0        | 2         | 1.75%   |
| 0.51-1.0        | 2         | 1.75%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 2.01-3.0        | 27        | 21.95%  |
| 3.01-4.0        | 25        | 20.33%  |
| 4.01-8.0        | 23        | 18.7%   |
| 1.01-2.0        | 21        | 17.07%  |
| 8.01-16.0       | 7         | 5.69%   |
| 0.51-1.0        | 5         | 4.07%   |
| 32.01-64.0      | 3         | 2.44%   |
| 24.01-32.0      | 3         | 2.44%   |
| 16.01-24.0      | 3         | 2.44%   |
| More than 256.0 | 2         | 1.63%   |
| 64.01-256.0     | 2         | 1.63%   |
| 0.01-0.5        | 2         | 1.63%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 54        | 46.96%  |
| 2      | 29        | 25.22%  |
| 3      | 14        | 12.17%  |
| 4      | 7         | 6.09%   |
| 6      | 3         | 2.61%   |
| 5      | 2         | 1.74%   |
| 0      | 2         | 1.74%   |
| 12     | 1         | 0.87%   |
| 11     | 1         | 0.87%   |
| 10     | 1         | 0.87%   |
| 9      | 1         | 0.87%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 86        | 75.44%  |
| Yes       | 28        | 24.56%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 97        | 85.84%  |
| No        | 16        | 14.16%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 74        | 65.49%  |
| No        | 39        | 34.51%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 64        | 56.14%  |
| No        | 50        | 43.86%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 27        | 23.89%  |
| Germany      | 11        | 9.73%   |
| Canada       | 8         | 7.08%   |
| Russia       | 7         | 6.19%   |
| France       | 7         | 6.19%   |
| UK           | 5         | 4.42%   |
| Hungary      | 4         | 3.54%   |
| China        | 4         | 3.54%   |
| Romania      | 3         | 2.65%   |
| Netherlands  | 3         | 2.65%   |
| Italy        | 3         | 2.65%   |
| Indonesia    | 3         | 2.65%   |
| India        | 3         | 2.65%   |
| Ukraine      | 2         | 1.77%   |
| Switzerland  | 2         | 1.77%   |
| Spain        | 2         | 1.77%   |
| South Africa | 2         | 1.77%   |
| Poland       | 2         | 1.77%   |
| Australia    | 2         | 1.77%   |
| Venezuela    | 1         | 0.88%   |
| Sweden       | 1         | 0.88%   |
| Puerto Rico  | 1         | 0.88%   |
| Pakistan     | 1         | 0.88%   |
| Nigeria      | 1         | 0.88%   |
| Mexico       | 1         | 0.88%   |
| Greenland    | 1         | 0.88%   |
| Finland      | 1         | 0.88%   |
| Czechia      | 1         | 0.88%   |
| Bulgaria     | 1         | 0.88%   |
| Belgium      | 1         | 0.88%   |
| Bangladesh   | 1         | 0.88%   |
| Austria      | 1         | 0.88%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Hamburg            | 3         | 2.59%   |
| Tunari             | 2         | 1.72%   |
| Saint-Brieuc       | 2         | 1.72%   |
| Queens             | 2         | 1.72%   |
| Moscow             | 2         | 1.72%   |
| Milan              | 2         | 1.72%   |
| Los Angeles        | 2         | 1.72%   |
| Johannesburg       | 2         | 1.72%   |
| Dresden            | 2         | 1.72%   |
| Dallas             | 2         | 1.72%   |
| Budapest           | 2         | 1.72%   |
| Berlin             | 2         | 1.72%   |
| Zaporizhzhia       | 1         | 0.86%   |
| Zandvoort          | 1         | 0.86%   |
| Winterswijk        | 1         | 0.86%   |
| Wilmington         | 1         | 0.86%   |
| Wejherowo          | 1         | 0.86%   |
| Warsaw             | 1         | 0.86%   |
| Vienna             | 1         | 0.86%   |
| Varosfoeld         | 1         | 0.86%   |
| Uppsala            | 1         | 0.86%   |
| Tuusula            | 1         | 0.86%   |
| Thiruvananthapuram | 1         | 0.86%   |
| Tampa              | 1         | 0.86%   |
| Suzhou             | 1         | 0.86%   |
| Strasbourg         | 1         | 0.86%   |
| Stadtilm           | 1         | 0.86%   |
| St. Paul           | 1         | 0.86%   |
| South Tangerang    | 1         | 0.86%   |
| Sofia              | 1         | 0.86%   |
| Shimanovsk         | 1         | 0.86%   |
| Shanghai           | 1         | 0.86%   |
| San Diego          | 1         | 0.86%   |
| Saint-Cloud        | 1         | 0.86%   |
| Rothwell           | 1         | 0.86%   |
| Rome               | 1         | 0.86%   |
| Rochester          | 1         | 0.86%   |
| Regina             | 1         | 0.86%   |
| Redlands           | 1         | 0.86%   |
| Penza              | 1         | 0.86%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 28        | 36     | 16.09%  |
| Seagate                     | 27        | 41     | 15.52%  |
| WDC                         | 22        | 42     | 12.64%  |
| Sandisk                     | 9         | 13     | 5.17%   |
| SK hynix                    | 8         | 10     | 4.6%    |
| Kingston                    | 8         | 11     | 4.6%    |
| Kingston Technology Company | 6         | 39     | 3.45%   |
| Intel                       | 6         | 7      | 3.45%   |
| Hitachi                     | 5         | 6      | 2.87%   |
| Unknown                     | 4         | 7      | 2.3%    |
| Toshiba                     | 4         | 7      | 2.3%    |
| Micron Technology           | 4         | 5      | 2.3%    |
| HGST                        | 4         | 7      | 2.3%    |
| Crucial                     | 4         | 12     | 2.3%    |
| Netac                       | 3         | 3      | 1.72%   |
| Plextor                     | 2         | 2      | 1.15%   |
| LITEONIT                    | 2         | 5      | 1.15%   |
| KIOXIA                      | 2         | 2      | 1.15%   |
| Hewlett-Packard             | 2         | 10     | 1.15%   |
| Dell                        | 2         | 3      | 1.15%   |
| Union Memory                | 1         | 1      | 0.57%   |
| Transcend                   | 1         | 1      | 0.57%   |
| Team                        | 1         | 1      | 0.57%   |
| SSSTC                       | 1         | 1      | 0.57%   |
| Silicon Motion              | 1         | 14     | 0.57%   |
| QEMU                        | 1         | 2      | 0.57%   |
| Phison Electronics          | 1         | 1      | 0.57%   |
| Phison                      | 1         | 1      | 0.57%   |
| Patriot                     | 1         | 1      | 0.57%   |
| MidasForce                  | 1         | 1      | 0.57%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.57%   |
| LITEON                      | 1         | 1      | 0.57%   |
| Lite-On Technology          | 1         | 1      | 0.57%   |
| Lenovo                      | 1         | 1      | 0.57%   |
| HJDK                        | 1         | 1      | 0.57%   |
| Emtec                       | 1         | 2      | 0.57%   |
| DELLBOSS                    | 1         | 1      | 0.57%   |
| China                       | 1         | 1      | 0.57%   |
| ASMT                        | 1         | 2      | 0.57%   |
| AMD                         | 1         | 15     | 0.57%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 6         | 2.9%    |
| Kingston SA400S37480G 480GB SSD                   | 3         | 1.45%   |
| WDC WD10SPZX-24Z10 1TB                            | 2         | 0.97%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 2         | 0.97%   |
| SK hynix SC311 SATA 256GB SSD                     | 2         | 0.97%   |
| Seagate ST4000DM000-1F2168 4TB                    | 2         | 0.97%   |
| Seagate ST320LT020-9YG142 320GB                   | 2         | 0.97%   |
| Seagate ST2000DL003-9VT166 2TB                    | 2         | 0.97%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 2         | 0.97%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB  | 2         | 0.97%   |
| Samsung NVMe SSD Controller SM951/PM951 256GB     | 2         | 0.97%   |
| Samsung MZVL22T0HBLB-00BL7 2TB                    | 2         | 0.97%   |
| Kingston Company SNV2S1000G 1TB                   | 2         | 0.97%   |
| Kingston Company KC2000 NVMe SSD 1TB              | 2         | 0.97%   |
| Kingston Company A2000 NVMe SSD 500GB             | 2         | 0.97%   |
| Hitachi HTS543232A7A384 320GB                     | 2         | 0.97%   |
| HGST HTS541010A9E680 1TB                          | 2         | 0.97%   |
| Crucial CT240BX500SSD1 240GB                      | 2         | 0.97%   |
| WDC WDS100T2B0B-00YS70 1TB SSD                    | 1         | 0.48%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                    | 1         | 0.48%   |
| WDC WD60EFRX-68L0BN1 6TB                          | 1         | 0.48%   |
| WDC WD5000LPCX-21VHAT0 500GB                      | 1         | 0.48%   |
| WDC WD40EZRX-00SPEB0 4TB                          | 1         | 0.48%   |
| WDC WD40EFZX-68AWUN0 4TB                          | 1         | 0.48%   |
| WDC WD40EFRX-68N32N0 4TB                          | 1         | 0.48%   |
| WDC WD40EFAX-68JH4N1 4TB                          | 1         | 0.48%   |
| WDC WD4000FYYZ-01UL1B2 4TB                        | 1         | 0.48%   |
| WDC WD4000FYYZ-01UL1B1 4TB                        | 1         | 0.48%   |
| WDC WD4000FDYZ-27YA5B0 4TB                        | 1         | 0.48%   |
| WDC WD4000F9YZ-09N20L1 4TB                        | 1         | 0.48%   |
| WDC WD3600FYYZ-01UL1B3 4TB                        | 1         | 0.48%   |
| WDC WD3600FYYZ-01UL1B1 4TB                        | 1         | 0.48%   |
| WDC WD35EFRX-68WT0N0 4TB                          | 1         | 0.48%   |
| WDC WD2502ABYS-02B7A0 256GB                       | 1         | 0.48%   |
| WDC WD20EZBX-60AYRA0 2TB                          | 1         | 0.48%   |
| WDC WD20EARS-00J2GB0 2TB                          | 1         | 0.48%   |
| WDC WD10SPZX-60Z10T1 1TB                          | 1         | 0.48%   |
| WDC WD10SPZX-60Z10T0 1TB                          | 1         | 0.48%   |
| WDC WD10JPVX-00JC3T0 1TB                          | 1         | 0.48%   |
| WDC WD10EZEX-75M2NA0 1TB                          | 1         | 0.48%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 26        | 37     | 41.27%  |
| WDC                 | 19        | 37     | 30.16%  |
| Hitachi             | 5         | 6      | 7.94%   |
| Toshiba             | 4         | 7      | 6.35%   |
| HGST                | 4         | 7      | 6.35%   |
| Unknown             | 1         | 2      | 1.59%   |
| Samsung Electronics | 1         | 1      | 1.59%   |
| QEMU                | 1         | 2      | 1.59%   |
| Hewlett-Packard     | 1         | 9      | 1.59%   |
| DELLBOSS            | 1         | 1      | 1.59%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 9      | 17.02%  |
| Kingston            | 7         | 7      | 14.89%  |
| Intel               | 4         | 5      | 8.51%   |
| SK hynix            | 3         | 5      | 6.38%   |
| Micron Technology   | 3         | 4      | 6.38%   |
| Crucial             | 3         | 10     | 6.38%   |
| SanDisk             | 2         | 3      | 4.26%   |
| Plextor             | 2         | 2      | 4.26%   |
| Netac               | 2         | 2      | 4.26%   |
| LITEONIT            | 2         | 5      | 4.26%   |
| WDC                 | 1         | 3      | 2.13%   |
| Team                | 1         | 1      | 2.13%   |
| Patriot             | 1         | 1      | 2.13%   |
| MidasForce          | 1         | 1      | 2.13%   |
| LITEON              | 1         | 1      | 2.13%   |
| HJDK                | 1         | 1      | 2.13%   |
| Hewlett-Packard     | 1         | 1      | 2.13%   |
| Dell                | 1         | 2      | 2.13%   |
| China               | 1         | 1      | 2.13%   |
| ASMT                | 1         | 2      | 2.13%   |
| A-DATA Technology   | 1         | 1      | 2.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 59        | 156    | 37.58%  |
| HDD     | 51        | 109    | 32.48%  |
| SSD     | 43        | 67     | 27.39%  |
| MMC     | 3         | 5      | 1.91%   |
| Unknown | 1         | 2      | 0.64%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 76        | 168    | 52.78%  |
| NVMe | 59        | 156    | 40.97%  |
| SAS  | 6         | 10     | 4.17%   |
| MMC  | 3         | 5      | 2.08%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 49        | 66     | 47.12%  |
| 0.51-1.0   | 31        | 50     | 29.81%  |
| 1.01-2.0   | 10        | 16     | 9.62%   |
| 3.01-4.0   | 8         | 23     | 7.69%   |
| 4.01-10.0  | 5         | 20     | 4.81%   |
| 2.01-3.0   | 1         | 1      | 0.96%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 32        | 27.83%  |
| 501-1000       | 19        | 16.52%  |
| 251-500        | 18        | 15.65%  |
| More than 3000 | 10        | 8.7%    |
| 1001-2000      | 10        | 8.7%    |
| 51-100         | 8         | 6.96%   |
| Unknown        | 7         | 6.09%   |
| 2001-3000      | 5         | 4.35%   |
| 1-20           | 4         | 3.48%   |
| 21-50          | 2         | 1.74%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 45        | 36.59%  |
| 21-50          | 24        | 19.51%  |
| 101-250        | 15        | 12.2%   |
| 51-100         | 15        | 12.2%   |
| 251-500        | 7         | 5.69%   |
| Unknown        | 7         | 5.69%   |
| More than 3000 | 3         | 2.44%   |
| 1001-2000      | 3         | 2.44%   |
| 501-1000       | 3         | 2.44%   |
| 2001-3000      | 1         | 0.81%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD4000FDYZ-27YA5B0 4TB        | 1         | 1      | 7.69%   |
| WDC WD2502ABYS-02B7A0 256GB       | 1         | 1      | 7.69%   |
| WDC WD20EARS-00J2GB0 2TB          | 1         | 1      | 7.69%   |
| SK hynix SH920 2.5 7MM 256GB SSD  | 1         | 1      | 7.69%   |
| Seagate ST4000DM000-1F2168 4TB    | 1         | 1      | 7.69%   |
| Seagate ST2000DL003-9VT166 2TB    | 1         | 1      | 7.69%   |
| Seagate ST1000DM010-2EP102 1TB    | 1         | 2      | 7.69%   |
| Samsung Electronics HD642JJ 640GB | 1         | 1      | 7.69%   |
| LITEONIT LSS-16L6G-HP 16GB SSD    | 1         | 4      | 7.69%   |
| Kingston SUV400S37240G 240GB SSD  | 1         | 1      | 7.69%   |
| Hitachi HTS545050A7E380 500GB     | 1         | 1      | 7.69%   |
| HGST HTS725050A7E630 500GB        | 1         | 1      | 7.69%   |
| HGST HTS541010A9E680 1TB          | 1         | 1      | 7.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3         | 3      | 23.08%  |
| Seagate             | 3         | 4      | 23.08%  |
| HGST                | 2         | 2      | 15.38%  |
| SK hynix            | 1         | 1      | 7.69%   |
| Samsung Electronics | 1         | 1      | 7.69%   |
| LITEONIT            | 1         | 4      | 7.69%   |
| Kingston            | 1         | 1      | 7.69%   |
| Hitachi             | 1         | 1      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3         | 3      | 30%     |
| Seagate             | 3         | 4      | 30%     |
| HGST                | 2         | 2      | 20%     |
| Samsung Electronics | 1         | 1      | 10%     |
| Hitachi             | 1         | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 11     | 75%     |
| SSD  | 3         | 6      | 25%     |

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
| Works    | 65        | 191    | 50.78%  |
| Detected | 52        | 131    | 40.63%  |
| Malfunc  | 11        | 17     | 8.59%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 65        | 38.69%  |
| AMD                            | 30        | 17.86%  |
| Samsung Electronics            | 20        | 11.9%   |
| Kingston Technology Company    | 9         | 5.36%   |
| SanDisk                        | 8         | 4.76%   |
| LSI Logic / Symbios Logic      | 5         | 2.98%   |
| SK hynix                       | 4         | 2.38%   |
| Marvell Technology Group       | 3         | 1.79%   |
| ASMedia Technology             | 3         | 1.79%   |
| Union Memory (Shenzhen)        | 2         | 1.19%   |
| Silicon Motion                 | 2         | 1.19%   |
| Phison Electronics             | 2         | 1.19%   |
| Broadcom / LSI                 | 2         | 1.19%   |
| Toshiba America Info Systems   | 1         | 0.6%    |
| Solid State Storage Technology | 1         | 0.6%    |
| Seagate Technology             | 1         | 0.6%    |
| Red Hat                        | 1         | 0.6%    |
| Nextorage                      | 1         | 0.6%    |
| Netac Technology               | 1         | 0.6%    |
| Micron/Crucial Technology      | 1         | 0.6%    |
| Micron Technology              | 1         | 0.6%    |
| MAXIO Technology (Hangzhou)    | 1         | 0.6%    |
| Lite-On Technology             | 1         | 0.6%    |
| Lenovo                         | 1         | 0.6%    |
| KIOXIA                         | 1         | 0.6%    |
| Hewlett-Packard                | 1         | 0.6%    |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 23        | 12.17%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 8         | 4.23%   |
| Intel SATA Controller [RAID mode]                                              | 8         | 4.23%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 5         | 2.65%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 5         | 2.65%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4         | 2.12%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 2.12%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 2.12%   |
| AMD 400 Series Chipset SATA Controller                                         | 4         | 2.12%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 3         | 1.59%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 3         | 1.59%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 1.59%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 1.59%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 3         | 1.59%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 2         | 1.06%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 1.06%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 2         | 1.06%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]        | 2         | 1.06%   |
| Kingston Company NV2 NVMe SSD SM2267XT (DRAM-less)                             | 2         | 1.06%   |
| Kingston Company KC2000/KC2500 NVMe SSD SM2262EN                               | 2         | 1.06%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                       | 2         | 1.06%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 1.06%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 2         | 1.06%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 1.06%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 1.06%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                  | 2         | 1.06%   |
| Intel C600/X79 series chipset IDE-r Controller                                 | 2         | 1.06%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2         | 1.06%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 2         | 1.06%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 1.06%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 2         | 1.06%   |
| AMD 600 Series Chipset SATA Controller                                         | 2         | 1.06%   |
| AMD 500 Series Chipset SATA Controller                                         | 2         | 1.06%   |
| Union Memory (Shenzhen) AM610 PCIe 3.0 x2 NVMe SSD 128GB, 256GB                | 1         | 0.53%   |
| Union Memory (Shenzhen) AH631 PCIe 3.0 NVMe SSD 512GB                          | 1         | 0.53%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 0.53%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                 | 1         | 0.53%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 1         | 0.53%   |
| SK hynix PC300 NVMe Solid State Drive 256GB                                    | 1         | 0.53%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 1         | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 78        | 46.71%  |
| NVMe | 58        | 34.73%  |
| RAID | 17        | 10.18%  |
| IDE  | 7         | 4.19%   |
| SAS  | 6         | 3.59%   |
| SCSI | 1         | 0.6%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 75        | 66.37%  |
| AMD    | 35        | 30.97%  |
| ARM    | 3         | 2.65%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-10210U CPU @ 1.60GHz          | 3         | 2.63%   |
| ARM Processor                               | 3         | 2.63%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 1.75%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 2         | 1.75%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 2         | 1.75%   |
| AMD Ryzen 5 3500X 6-Core Processor          | 2         | 1.75%   |
| AMD EPYC 7282 16-Core Processor             | 2         | 1.75%   |
| Intel Xeon W-2223 CPU @ 3.60GHz             | 1         | 0.88%   |
| Intel Xeon W-1350 @ 3.30GHz                 | 1         | 0.88%   |
| Intel Xeon W-11855M CPU @ 3.20GHz           | 1         | 0.88%   |
| Intel Xeon Silver 4116 CPU @ 2.10GHz        | 1         | 0.88%   |
| Intel Xeon Gold 5220R CPU @ 2.20GHz         | 1         | 0.88%   |
| Intel Xeon E-2144G CPU @ 3.60GHz            | 1         | 0.88%   |
| Intel Xeon CPU X5550 @ 2.67GHz              | 1         | 0.88%   |
| Intel Xeon CPU L5520 @ 2.27GHz              | 1         | 0.88%   |
| Intel Xeon CPU E5540 @ 2.53GHz              | 1         | 0.88%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz          | 1         | 0.88%   |
| Intel Xeon CPU E5-2683 v4 @ 2.10GHz         | 1         | 0.88%   |
| Intel Xeon CPU E5-2667 v2 @ 3.30GHz         | 1         | 0.88%   |
| Intel Xeon CPU E5-2630 0 @ 2.30GHz          | 1         | 0.88%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz         | 1         | 0.88%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 0.88%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 1         | 0.88%   |
| Intel Pentium CPU 3825U @ 1.90GHz           | 1         | 0.88%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 0.88%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 0.88%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 0.88%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1         | 0.88%   |
| Intel Core i7-7560U CPU @ 2.40GHz           | 1         | 0.88%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 0.88%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 0.88%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz          | 1         | 0.88%   |
| Intel Core i7-4510U CPU @ 2.00GHz           | 1         | 0.88%   |
| Intel Core i7-3840QM CPU @ 2.80GHz          | 1         | 0.88%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1         | 0.88%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 1         | 0.88%   |
| Intel Core i7-14700K                        | 1         | 0.88%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 1         | 0.88%   |
| Intel Core i7 CPU X 980 @ 3.33GHz           | 1         | 0.88%   |
| Intel Core i7 CPU 870 @ 2.93GHz             | 1         | 0.88%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 19        | 16.81%  |
| Intel Core i7           | 16        | 14.16%  |
| Other                   | 15        | 13.27%  |
| Intel Xeon              | 12        | 10.62%  |
| Intel Core i3           | 6         | 5.31%   |
| AMD Ryzen 9             | 6         | 5.31%   |
| AMD Ryzen 7             | 6         | 5.31%   |
| AMD Ryzen 5             | 6         | 5.31%   |
| AMD EPYC                | 5         | 4.42%   |
| Intel Celeron           | 4         | 3.54%   |
| Intel Pentium           | 2         | 1.77%   |
| Intel Atom              | 2         | 1.77%   |
| AMD Ryzen Threadripper  | 2         | 1.77%   |
| AMD Ryzen 3             | 2         | 1.77%   |
| AMD A12                 | 2         | 1.77%   |
| AMD A10                 | 2         | 1.77%   |
| Intel Xeon Silver       | 1         | 0.88%   |
| Intel Xeon Gold         | 1         | 0.88%   |
| Intel Pentium Dual-Core | 1         | 0.88%   |
| AMD FX                  | 1         | 0.88%   |
| AMD E2                  | 1         | 0.88%   |
| AMD A6                  | 1         | 0.88%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 36        | 31.58%  |
| 2       | 31        | 27.19%  |
| 6       | 12        | 10.53%  |
| 8       | 8         | 7.02%   |
| 16      | 7         | 6.14%   |
| 12      | 6         | 5.26%   |
| 32      | 3         | 2.63%   |
| 24      | 2         | 1.75%   |
| 1       | 2         | 1.75%   |
| Unknown | 2         | 1.75%   |
| 80      | 1         | 0.88%   |
| 48      | 1         | 0.88%   |
| 20      | 1         | 0.88%   |
| 14      | 1         | 0.88%   |
| 10      | 1         | 0.88%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 102       | 90.27%  |
| 2       | 8         | 7.08%   |
| Unknown | 2         | 1.77%   |
| 4       | 1         | 0.88%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 92        | 81.42%  |
| 1       | 19        | 16.81%  |
| Unknown | 2         | 1.77%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 111       | 97.37%  |
| Unknown        | 3         | 2.63%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 33        | 27.05%  |
| 0x306a9    | 5         | 4.1%    |
| 0x08701021 | 5         | 4.1%    |
| 0x806ec    | 4         | 3.28%   |
| 0x806c1    | 4         | 3.28%   |
| 0xa0671    | 3         | 2.46%   |
| 0x40651    | 3         | 2.46%   |
| 0x306c3    | 3         | 2.46%   |
| 0x206a7    | 3         | 2.46%   |
| 0x106a5    | 3         | 2.46%   |
| 0x906ea    | 2         | 1.64%   |
| 0x806ea    | 2         | 1.64%   |
| 0x806e9    | 2         | 1.64%   |
| 0x806d1    | 2         | 1.64%   |
| 0x50657    | 2         | 1.64%   |
| 0x406e3    | 2         | 1.64%   |
| 0x306e4    | 2         | 1.64%   |
| 0x0a50000d | 2         | 1.64%   |
| 0x08600106 | 2         | 1.64%   |
| 0x0830107a | 2         | 1.64%   |
| 0x08301055 | 2         | 1.64%   |
| 0x08108109 | 2         | 1.64%   |
| 0x0600611a | 2         | 1.64%   |
| 0xb06a3    | 1         | 0.82%   |
| 0xa0655    | 1         | 0.82%   |
| 0xa0652    | 1         | 0.82%   |
| 0x906ed    | 1         | 0.82%   |
| 0x906e9    | 1         | 0.82%   |
| 0x906a4    | 1         | 0.82%   |
| 0x506e3    | 1         | 0.82%   |
| 0x50654    | 1         | 0.82%   |
| 0x406c4    | 1         | 0.82%   |
| 0x306d4    | 1         | 0.82%   |
| 0x30678    | 1         | 0.82%   |
| 0x30673    | 1         | 0.82%   |
| 0x30661    | 1         | 0.82%   |
| 0x206d7    | 1         | 0.82%   |
| 0x20655    | 1         | 0.82%   |
| 0x106ca    | 1         | 0.82%   |
| 0x1067a    | 1         | 0.82%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 17        | 15.04%  |
| Zen 2            | 14        | 12.39%  |
| IvyBridge        | 8         | 7.08%   |
| Skylake          | 7         | 6.19%   |
| Haswell          | 7         | 6.19%   |
| Unknown          | 6         | 5.31%   |
| Zen 3            | 5         | 4.42%   |
| TigerLake        | 5         | 4.42%   |
| SandyBridge      | 5         | 4.42%   |
| Icelake          | 5         | 4.42%   |
| Excavator        | 5         | 4.42%   |
| Nehalem          | 4         | 3.54%   |
| Alderlake Hybrid | 4         | 3.54%   |
| Zen+             | 3         | 2.65%   |
| Silvermont       | 3         | 2.65%   |
| Zen              | 2         | 1.77%   |
| Westmere         | 2         | 1.77%   |
| CometLake        | 2         | 1.77%   |
| Broadwell        | 2         | 1.77%   |
| Bonnell          | 2         | 1.77%   |
| Steamroller      | 1         | 0.88%   |
| Piledriver       | 1         | 0.88%   |
| Penryn           | 1         | 0.88%   |
| Jaguar           | 1         | 0.88%   |
| Goldmont plus    | 1         | 0.88%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 55        | 42.64%  |
| Nvidia                     | 33        | 25.58%  |
| AMD                        | 27        | 20.93%  |
| ASPEED Technology          | 8         | 6.2%    |
| Matrox Electronics Systems | 5         | 3.88%   |
| Red Hat                    | 1         | 0.78%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| ASPEED Technology ASPEED Graphics Family                                  | 8         | 6.15%   |
| Intel UHD Graphics 620                                                    | 5         | 3.85%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 4         | 3.08%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 4         | 3.08%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 3         | 2.31%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 3         | 2.31%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 3         | 2.31%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                       | 3         | 2.31%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 3         | 2.31%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 3         | 2.31%   |
| Nvidia GA106 [Geforce RTX 3050]                                           | 2         | 1.54%   |
| Matrox Electronics Systems MGA G200eW WPCM450                             | 2         | 1.54%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller  | 2         | 1.54%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                    | 2         | 1.54%   |
| Intel HD Graphics 530                                                     | 2         | 1.54%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 2         | 1.54%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 2         | 1.54%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 2         | 1.54%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]             | 2         | 1.54%   |
| AMD Raphael                                                               | 2         | 1.54%   |
| Red Hat QXL paravirtual graphic card                                      | 1         | 0.77%   |
| Nvidia TU117GLM [Quadro T400 Mobile]                                      | 1         | 0.77%   |
| Nvidia TU117 [GeForce GTX 1650]                                           | 1         | 0.77%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 1         | 0.77%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                     | 1         | 0.77%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 1         | 0.77%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 1         | 0.77%   |
| Nvidia GP107GL [Quadro P620]                                              | 1         | 0.77%   |
| Nvidia GP106GL [Quadro P2200]                                             | 1         | 0.77%   |
| Nvidia GP104 [GeForce GTX 1080]                                           | 1         | 0.77%   |
| Nvidia GM204GL [Quadro M4000]                                             | 1         | 0.77%   |
| Nvidia GM204 [GeForce GTX 970]                                            | 1         | 0.77%   |
| Nvidia GM108M [GeForce MX110]                                             | 1         | 0.77%   |
| Nvidia GM108M [GeForce 930M]                                              | 1         | 0.77%   |
| Nvidia GM107M [GeForce GTX 960M]                                          | 1         | 0.77%   |
| Nvidia GM107M [GeForce GTX 850M]                                          | 1         | 0.77%   |
| Nvidia GM107GL [Quadro K2200]                                             | 1         | 0.77%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                         | 1         | 0.77%   |
| Nvidia GK208B [GeForce GT 730]                                            | 1         | 0.77%   |
| Nvidia GK107GLM [Quadro K1000M]                                           | 1         | 0.77%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 42        | 37.17%  |
| 1 x AMD        | 21        | 18.58%  |
| 1 x Nvidia     | 18        | 15.93%  |
| Intel + Nvidia | 11        | 9.73%   |
| 1 x Matrox     | 5         | 4.42%   |
| 1 x ASPEED     | 5         | 4.42%   |
| Other          | 2         | 1.77%   |
| AMD + Nvidia   | 2         | 1.77%   |
| AMD + ASPEED   | 2         | 1.77%   |
| 2 x Nvidia     | 1         | 0.88%   |
| 2 x AMD        | 1         | 0.88%   |
| 1 x Red Hat    | 1         | 0.88%   |
| Intel + ASPEED | 1         | 0.88%   |
| Intel + AMD    | 1         | 0.88%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 88        | 77.19%  |
| Proprietary | 13        | 11.4%   |
| Unknown     | 13        | 11.4%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 68        | 59.13%  |
| 0.01-0.5   | 15        | 13.04%  |
| 1.01-2.0   | 9         | 7.83%   |
| 3.01-4.0   | 6         | 5.22%   |
| 5.01-6.0   | 5         | 4.35%   |
| 0.51-1.0   | 5         | 4.35%   |
| 7.01-8.0   | 4         | 3.48%   |
| 32.01-64.0 | 1         | 0.87%   |
| 4.01-5.0   | 1         | 0.87%   |
| 16.01-24.0 | 1         | 0.87%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 12        | 12.37%  |
| AU Optronics            | 12        | 12.37%  |
| Samsung Electronics     | 11        | 11.34%  |
| BOE                     | 10        | 10.31%  |
| Dell                    | 9         | 9.28%   |
| Chimei Innolux          | 7         | 7.22%   |
| PANDA                   | 4         | 4.12%   |
| Eizo                    | 4         | 4.12%   |
| BenQ                    | 4         | 4.12%   |
| Sharp                   | 3         | 3.09%   |
| Philips                 | 3         | 3.09%   |
| ViewSonic               | 2         | 2.06%   |
| Lenovo                  | 2         | 2.06%   |
| InfoVision              | 2         | 2.06%   |
| Goldstar                | 2         | 2.06%   |
| Acer                    | 2         | 2.06%   |
| TopView                 | 1         | 1.03%   |
| STD                     | 1         | 1.03%   |
| Seiki                   | 1         | 1.03%   |
| Medion                  | 1         | 1.03%   |
| HannStar                | 1         | 1.03%   |
| Chi Mei Optoelectronics | 1         | 1.03%   |
| ASUSTek Computer        | 1         | 1.03%   |
| AOC                     | 1         | 1.03%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch         | 2         | 2%      |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch        | 2         | 2%      |
| ViewSonic VX2233wm-1 VSC1D22 1920x1080 477x268mm 21.5-inch            | 1         | 1%      |
| ViewSonic VA2232 Series VSC8224 1680x1050 474x296mm 22.0-inch         | 1         | 1%      |
| TopView HD TV TOPC37E 1920x1080 700x390mm 31.5-inch                   | 1         | 1%      |
| STD HDMI TV STD00C7 1680x1050 698x392mm 31.5-inch                     | 1         | 1%      |
| Sharp LCD Monitor SHP146B 3200x1800 294x165mm 13.3-inch               | 1         | 1%      |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch               | 1         | 1%      |
| Sharp LC-32LB480U SHP3263 1920x1080 698x392mm 31.5-inch               | 1         | 1%      |
| Seiki SC32HT04 SEK1366 1366x768 700x390mm 31.5-inch                   | 1         | 1%      |
| Samsung Electronics SyncMaster SAM021B 1400x1050 408x300mm 19.9-inch  | 1         | 1%      |
| Samsung Electronics SyncMaster SAM01F9 1280x1024 380x300mm 19.1-inch  | 1         | 1%      |
| Samsung Electronics S27H65x SAM0E1D 1920x1080 598x336mm 27.0-inch     | 1         | 1%      |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 1         | 1%      |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch  | 1         | 1%      |
| Samsung Electronics LCD Monitor SEC4252 1366x768 344x194mm 15.5-inch  | 1         | 1%      |
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch  | 1         | 1%      |
| Samsung Electronics LCD Monitor SDC4164 3840x2400 344x215mm 16.0-inch | 1         | 1%      |
| Samsung Electronics LCD Monitor SDC4142 3840x2160 294x165mm 13.3-inch | 1         | 1%      |
| Samsung Electronics LCD Monitor SDC4141 1366x768 344x194mm 15.5-inch  | 1         | 1%      |
| Samsung Electronics LCD Monitor S32B80P 5760x2160                     | 1         | 1%      |
| Samsung Electronics LCD Monitor S32B80P                               | 1         | 1%      |
| Samsung Electronics F27G3xTF SAM710D 1920x1080 600x330mm 27.0-inch    | 1         | 1%      |
| Philips PHL 272B7QU PHL0926 2560x1440 597x336mm 27.0-inch             | 1         | 1%      |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 1         | 1%      |
| Philips 19B PHL0879 1280x1024 376x301mm 19.0-inch                     | 1         | 1%      |
| PANDA LCD Monitor NCP0058 1920x1080 344x194mm 15.5-inch               | 1         | 1%      |
| PANDA LCD Monitor NCP004A 1920x1080 309x174mm 14.0-inch               | 1         | 1%      |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch               | 1         | 1%      |
| PANDA LCD Monitor NCP002A 1920x1080 344x194mm 15.5-inch               | 1         | 1%      |
| Medion MD7212AS MED4971 1280x1024 359x287mm 18.1-inch                 | 1         | 1%      |
| LG Display LCD Monitor LGD0621 1920x1080 382x215mm 17.3-inch          | 1         | 1%      |
| LG Display LCD Monitor LGD056F 2736x1824 260x173mm 12.3-inch          | 1         | 1%      |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch          | 1         | 1%      |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 1         | 1%      |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch           | 1         | 1%      |
| LG Display LCD Monitor LGD042D 1920x1080 294x165mm 13.3-inch          | 1         | 1%      |
| LG Display LCD Monitor LGD03FB 1920x1080 382x215mm 17.3-inch          | 1         | 1%      |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch           | 1         | 1%      |
| LG Display LCD Monitor LGD034A 1366x768 345x194mm 15.6-inch           | 1         | 1%      |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 50        | 51.02%  |
| 1366x768 (WXGA)    | 16        | 16.33%  |
| 1280x1024 (SXGA)   | 7         | 7.14%   |
| 3840x2160 (4K)     | 4         | 4.08%   |
| 2560x1440 (QHD)    | 3         | 3.06%   |
| 1920x1200 (WUXGA)  | 3         | 3.06%   |
| 3200x1800 (QHD+)   | 2         | 2.04%   |
| 2560x1600          | 2         | 2.04%   |
| 1600x900 (HD+)     | 2         | 2.04%   |
| 5760x2160          | 1         | 1.02%   |
| 3840x2400          | 1         | 1.02%   |
| 2736x1824          | 1         | 1.02%   |
| 2560x1080          | 1         | 1.02%   |
| 2160x1350          | 1         | 1.02%   |
| 1680x1050 (WSXGA+) | 1         | 1.02%   |
| 1600x1200          | 1         | 1.02%   |
| 1400x1050          | 1         | 1.02%   |
| Unknown            | 1         | 1.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 23        | 23.47%  |
| 13      | 12        | 12.24%  |
| 14      | 10        | 10.2%   |
| 17      | 9         | 9.18%   |
| 24      | 7         | 7.14%   |
| 31      | 6         | 6.12%   |
| 27      | 6         | 6.12%   |
| 21      | 6         | 6.12%   |
| 19      | 4         | 4.08%   |
| Unknown | 3         | 3.06%   |
| 23      | 2         | 2.04%   |
| 16      | 2         | 2.04%   |
| 11      | 2         | 2.04%   |
| 34      | 1         | 1.02%   |
| 29      | 1         | 1.02%   |
| 22      | 1         | 1.02%   |
| 20      | 1         | 1.02%   |
| 18      | 1         | 1.02%   |
| 12      | 1         | 1.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 43        | 43.88%  |
| 501-600     | 15        | 15.31%  |
| 351-400     | 12        | 12.24%  |
| 201-300     | 9         | 9.18%   |
| 401-500     | 8         | 8.16%   |
| 601-700     | 7         | 7.14%   |
| Unknown     | 3         | 3.06%   |
| 701-800     | 1         | 1.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 72        | 77.42%  |
| 16/10   | 7         | 7.53%   |
| 5/4     | 6         | 6.45%   |
| Unknown | 3         | 3.23%   |
| 4/3     | 2         | 2.15%   |
| 6/5     | 1         | 1.08%   |
| 3/2     | 1         | 1.08%   |
| 21/9    | 1         | 1.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 23        | 23.47%  |
| 81-90          | 16        | 16.33%  |
| 201-250        | 13        | 13.27%  |
| 351-500        | 8         | 8.16%   |
| 151-200        | 7         | 7.14%   |
| 121-130        | 7         | 7.14%   |
| 71-80          | 6         | 6.12%   |
| 301-350        | 6         | 6.12%   |
| Unknown        | 3         | 3.06%   |
| 51-60          | 2         | 2.04%   |
| 251-300        | 2         | 2.04%   |
| 141-150        | 2         | 2.04%   |
| 111-120        | 2         | 2.04%   |
| 61-70          | 1         | 1.02%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 33        | 34.74%  |
| 51-100        | 27        | 28.42%  |
| 101-120       | 21        | 22.11%  |
| More than 240 | 6         | 6.32%   |
| 161-240       | 4         | 4.21%   |
| Unknown       | 3         | 3.16%   |
| 1-50          | 1         | 1.05%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 81        | 71.05%  |
| 0     | 21        | 18.42%  |
| 2     | 12        | 10.53%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 62        | 36.9%   |
| Realtek Semiconductor           | 44        | 26.19%  |
| Qualcomm Atheros                | 18        | 10.71%  |
| Broadcom                        | 12        | 7.14%   |
| Broadcom Limited                | 5         | 2.98%   |
| Mellanox Technologies           | 4         | 2.38%   |
| American Megatrends             | 4         | 2.38%   |
| TP-Link                         | 3         | 1.79%   |
| Standard Microsystems           | 2         | 1.19%   |
| Ralink Technology               | 2         | 1.19%   |
| MediaTek                        | 2         | 1.19%   |
| Insyde Software                 | 2         | 1.19%   |
| Sierra Wireless                 | 1         | 0.6%    |
| Samsung Electronics             | 1         | 0.6%    |
| Ralink                          | 1         | 0.6%    |
| Qualcomm Atheros Communications | 1         | 0.6%    |
| Marvell Technology Group        | 1         | 0.6%    |
| Emulex                          | 1         | 0.6%    |
| ASIX Electronics                | 1         | 0.6%    |
| 3Com                            | 1         | 0.6%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 29        | 13.81%  |
| Intel Wireless 8265 / 8275                                             | 6         | 2.86%   |
| Intel Wi-Fi 6 AX200                                                    | 6         | 2.86%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 5         | 2.38%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 5         | 2.38%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 5         | 2.38%   |
| Intel I350 Gigabit Network Connection                                  | 5         | 2.38%   |
| Intel I210 Gigabit Network Connection                                  | 5         | 2.38%   |
| Intel Ethernet Controller X550                                         | 5         | 2.38%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 4         | 1.9%    |
| Intel Wi-Fi 6 AX201                                                    | 4         | 1.9%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4         | 1.9%    |
| American Megatrends Virtual Ethernet.                                  | 4         | 1.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 3         | 1.43%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3         | 1.43%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 3         | 1.43%   |
| Intel Wireless 7260                                                    | 3         | 1.43%   |
| Intel I211 Gigabit Network Connection                                  | 3         | 1.43%   |
| Intel Ethernet Controller I225-V                                       | 3         | 1.43%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 3         | 1.43%   |
| Intel 82574L Gigabit Network Connection                                | 3         | 1.43%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                       | 3         | 1.43%   |
| Broadcom BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet Controller  | 3         | 1.43%   |
| Standard Microsystems Ethernet controller                              | 2         | 0.95%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                    | 2         | 0.95%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 2         | 0.95%   |
| Ralink MT7601U Wireless Adapter                                        | 2         | 0.95%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 2         | 0.95%   |
| Intel Wireless 8260                                                    | 2         | 0.95%   |
| Intel Wireless 3165                                                    | 2         | 0.95%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 2         | 0.95%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 0.95%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 0.95%   |
| Intel Ethernet Connection (14) I219-LM                                 | 2         | 0.95%   |
| Intel Ethernet Connection (10) I219-V                                  | 2         | 0.95%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                   | 2         | 0.95%   |
| Insyde Software RNDIS/Ethernet Gadget                                  | 2         | 0.95%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 2         | 0.95%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 1         | 0.48%   |
| TP-Link Archer T4U ver.3                                               | 1         | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 36        | 46.15%  |
| Qualcomm Atheros                | 16        | 20.51%  |
| Realtek Semiconductor           | 13        | 16.67%  |
| Broadcom                        | 3         | 3.85%   |
| TP-Link                         | 2         | 2.56%   |
| Ralink Technology               | 2         | 2.56%   |
| Broadcom Limited                | 2         | 2.56%   |
| Sierra Wireless                 | 1         | 1.28%   |
| Ralink                          | 1         | 1.28%   |
| Qualcomm Atheros Communications | 1         | 1.28%   |
| MediaTek                        | 1         | 1.28%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                  | 6         | 7.69%   |
| Intel Wi-Fi 6 AX200                                         | 6         | 7.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter  | 5         | 6.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter  | 4         | 5.13%   |
| Intel Wi-Fi 6 AX201                                         | 4         | 5.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter    | 3         | 3.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter  | 3         | 3.85%   |
| Intel Wireless 7260                                         | 3         | 3.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                           | 3         | 3.85%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter         | 2         | 2.56%   |
| Ralink MT7601U Wireless Adapter                             | 2         | 2.56%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter            | 2         | 2.56%   |
| Intel Wireless 8260                                         | 2         | 2.56%   |
| Intel Wireless 3165                                         | 2         | 2.56%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]   | 2         | 2.56%   |
| TP-Link Archer T4U ver.3                                    | 1         | 1.28%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                      | 1         | 1.28%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE               | 1         | 1.28%   |
| Realtek RTL88x2bu [AC1200 Techkey]                          | 1         | 1.28%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller | 1         | 1.28%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter    | 1         | 1.28%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter    | 1         | 1.28%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter             | 1         | 1.28%   |
| Realtek RTL8723DE Wireless Network Adapter                  | 1         | 1.28%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter             | 1         | 1.28%   |
| Realtek RTL8191SEvB Wireless LAN Controller                 | 1         | 1.28%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                   | 1         | 1.28%   |
| Qualcomm Atheros AR9271 802.11n                             | 1         | 1.28%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter            | 1         | 1.28%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter            | 1         | 1.28%   |
| MediaTek 802.11AC MT7663 Wireless Network Adapter           | 1         | 1.28%   |
| Intel Wireless 7265                                         | 1         | 1.28%   |
| Intel Raptor Lake-S PCH CNVi WiFi                           | 1         | 1.28%   |
| Intel Raptor Lake PCH CNVi WiFi                             | 1         | 1.28%   |
| Intel Comet Lake PCH CNVi WiFi                              | 1         | 1.28%   |
| Intel Centrino Wireless-N 2230                              | 1         | 1.28%   |
| Intel Centrino Ultimate-N 6300                              | 1         | 1.28%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                | 1         | 1.28%   |
| Intel Cannon Lake PCH CNVi WiFi                             | 1         | 1.28%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                     | 1         | 1.28%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 42        | 36.21%  |
| Realtek Semiconductor    | 41        | 35.34%  |
| Broadcom                 | 9         | 7.76%   |
| American Megatrends      | 4         | 3.45%   |
| Qualcomm Atheros         | 3         | 2.59%   |
| Mellanox Technologies    | 3         | 2.59%   |
| Broadcom Limited         | 3         | 2.59%   |
| Standard Microsystems    | 2         | 1.72%   |
| Insyde Software          | 2         | 1.72%   |
| TP-Link                  | 1         | 0.86%   |
| Samsung Electronics      | 1         | 0.86%   |
| MediaTek                 | 1         | 0.86%   |
| Marvell Technology Group | 1         | 0.86%   |
| Emulex                   | 1         | 0.86%   |
| ASIX Electronics         | 1         | 0.86%   |
| 3Com                     | 1         | 0.86%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 29        | 22.14%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 5         | 3.82%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 5         | 3.82%   |
| Intel I350 Gigabit Network Connection                                  | 5         | 3.82%   |
| Intel I210 Gigabit Network Connection                                  | 5         | 3.82%   |
| Intel Ethernet Controller X550                                         | 5         | 3.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4         | 3.05%   |
| American Megatrends Virtual Ethernet.                                  | 4         | 3.05%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3         | 2.29%   |
| Intel I211 Gigabit Network Connection                                  | 3         | 2.29%   |
| Intel Ethernet Controller I225-V                                       | 3         | 2.29%   |
| Intel 82574L Gigabit Network Connection                                | 3         | 2.29%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                       | 3         | 2.29%   |
| Broadcom BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet Controller  | 3         | 2.29%   |
| Standard Microsystems Ethernet controller                              | 2         | 1.53%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 2         | 1.53%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 1.53%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 1.53%   |
| Intel Ethernet Connection (14) I219-LM                                 | 2         | 1.53%   |
| Intel Ethernet Connection (10) I219-V                                  | 2         | 1.53%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                   | 2         | 1.53%   |
| Insyde Software RNDIS/Ethernet Gadget                                  | 2         | 1.53%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 2         | 1.53%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 1         | 0.76%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1         | 0.76%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 0.76%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1         | 0.76%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 0.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 0.76%   |
| Mellanox MT28800 Family [ConnectX-5 Ex]                                | 1         | 0.76%   |
| Mellanox MT27800 Family [ConnectX-5]                                   | 1         | 0.76%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                  | 1         | 0.76%   |
| MediaTek Infinix NOTE 30 VIP                                           | 1         | 0.76%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 1         | 0.76%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                          | 1         | 0.76%   |
| Intel Ethernet Connection I219-V                                       | 1         | 0.76%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 0.76%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 0.76%   |
| Intel Ethernet Connection I217-LM                                      | 1         | 0.76%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1         | 0.76%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 97        | 56.4%   |
| WiFi     | 74        | 43.02%  |
| Unknown  | 1         | 0.58%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 59        | 54.13%  |
| WiFi     | 50        | 45.87%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 58        | 50.88%  |
| 1     | 35        | 30.7%   |
| 4     | 7         | 6.14%   |
| 3     | 5         | 4.39%   |
| 0     | 4         | 3.51%   |
| 6     | 2         | 1.75%   |
| 5     | 2         | 1.75%   |
| 8     | 1         | 0.88%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 87        | 75%     |
| Yes  | 29        | 25%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 33        | 51.56%  |
| Realtek Semiconductor           | 9         | 14.06%  |
| Qualcomm Atheros Communications | 8         | 12.5%   |
| Broadcom                        | 4         | 6.25%   |
| Foxconn / Hon Hai               | 3         | 4.69%   |
| Lite-On Technology              | 2         | 3.13%   |
| IMC Networks                    | 2         | 3.13%   |
| Cambridge Silicon Radio         | 2         | 3.13%   |
| ASUSTek Computer                | 1         | 1.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                              | 8         | 12.5%   |
| Intel AX201 Bluetooth                               | 7         | 10.94%  |
| Realtek Bluetooth Radio                             | 6         | 9.38%   |
| Qualcomm Atheros  Bluetooth Device                  | 6         | 9.38%   |
| Intel Bluetooth wireless interface                  | 6         | 9.38%   |
| Intel AX200 Bluetooth                               | 6         | 9.38%   |
| Intel AX211 Bluetooth                               | 2         | 3.13%   |
| Intel AX210 Bluetooth                               | 2         | 3.13%   |
| IMC Networks Bluetooth Device                       | 2         | 3.13%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 3.13%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 3.13%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 1.56%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1.56%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 1.56%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.56%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.56%   |
| Lite-On Wireless_Device                             | 1         | 1.56%   |
| Lite-On Bluetooth Device                            | 1         | 1.56%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.56%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 1.56%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 1         | 1.56%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.56%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1         | 1.56%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1.56%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 1.56%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 1.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 71        | 48.97%  |
| AMD                      | 33        | 22.76%  |
| Nvidia                   | 28        | 19.31%  |
| C-Media Electronics      | 3         | 2.07%   |
| Micro Star International | 2         | 1.38%   |
| Plantronics              | 1         | 0.69%   |
| JMTek                    | 1         | 0.69%   |
| Giga-Byte Technology     | 1         | 0.69%   |
| Creative Technology      | 1         | 0.69%   |
| Conrad Electronic SE     | 1         | 0.69%   |
| Conexant Systems         | 1         | 0.69%   |
| ASUSTek Computer         | 1         | 0.69%   |
| Apple                    | 1         | 0.69%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 12        | 6.98%   |
| Intel Sunrise Point-LP HD Audio                                            | 10        | 5.81%   |
| AMD Starship/Matisse HD Audio Controller                                   | 9         | 5.23%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7         | 4.07%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 5         | 2.91%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 5         | 2.91%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 5         | 2.91%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 2.33%   |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 2.33%   |
| Intel 8 Series HD Audio Controller                                         | 4         | 2.33%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 2.33%   |
| AMD Kabini HDMI/DP Audio                                                   | 4         | 2.33%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 1.74%   |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 1.74%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 1.74%   |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 1.74%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3         | 1.74%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 1.74%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 1.16%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 1.16%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 1.16%   |
| Nvidia GM204 High Definition Audio Controller                              | 2         | 1.16%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 1.16%   |
| Nvidia GK104 HDMI Audio Controller                                         | 2         | 1.16%   |
| Nvidia Audio device                                                        | 2         | 1.16%   |
| Micro Star International USB Audio                                         | 2         | 1.16%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 2         | 1.16%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 1.16%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 2         | 1.16%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 1.16%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 1.16%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 1.16%   |
| Intel 200 Series PCH HD Audio                                              | 2         | 1.16%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 1.16%   |
| C-Media Electronics C-Media USB Audio Device                               | 2         | 1.16%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 2         | 1.16%   |
| AMD High Definition Audio Controller                                       | 2         | 1.16%   |
| AMD FCH Azalia Controller                                                  | 2         | 1.16%   |
| Plantronics Blackwire 320                                                  | 1         | 0.58%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 16        | 18.39%  |
| Kingston            | 15        | 17.24%  |
| SK hynix            | 14        | 16.09%  |
| Micron Technology   | 11        | 12.64%  |
| Crucial             | 7         | 8.05%   |
| G.Skill             | 4         | 4.6%    |
| Corsair             | 4         | 4.6%    |
| Unknown             | 3         | 3.45%   |
| Elpida              | 3         | 3.45%   |
| Unknown             | 3         | 3.45%   |
| Unknown (0x0100)    | 1         | 1.15%   |
| Timetec             | 1         | 1.15%   |
| QEMU                | 1         | 1.15%   |
| Nanya Technology    | 1         | 1.15%   |
| Micron/Elpida       | 1         | 1.15%   |
| Hewlett-Packard     | 1         | 1.15%   |
| GeIL                | 1         | 1.15%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 3         | 3%      |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 2%      |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 2         | 2%      |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s            | 2         | 2%      |
| Elpida RAM EBJ81UG8EFU0-GN-F 8GB SODIMM DDR3 1600MT/s            | 2         | 2%      |
| Unknown RAM Module 8GB DIMM 1600MT/s                             | 1         | 1%      |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 1%      |
| Unknown RAM Module 4GB DIMM 1066MT/s                             | 1         | 1%      |
| Unknown (0x0100) RAM R744G2133S1S 4GB SODIMM DDR4 1866MT/s       | 1         | 1%      |
| Timetec RAM SD3-1600 8GB SODIMM DDR3 1600MT/s                    | 1         | 1%      |
| SK hynix RAM Module 4GB DIMM DDR3 1066MT/s                       | 1         | 1%      |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1%      |
| SK hynix RAM HMT351U6AFR8C-H9 4GB DIMM DDR3 1333MT/s             | 1         | 1%      |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1%      |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 1%      |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1%      |
| SK hynix RAM HMT325S6BFR8C-H9 2048MB SODIMM DDR3 1333MT/s        | 1         | 1%      |
| SK hynix RAM HMAA8GR7CJR4N-XN 64GB DIMM DDR4 3200MT/s            | 1         | 1%      |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1%      |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 1866MT/s     | 1         | 1%      |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 1         | 1%      |
| SK hynix RAM HMA82GR7AFR8N-VK 16GB DIMM DDR4 2667MT/s            | 1         | 1%      |
| SK hynix RAM HMA82GR7AFR8N-UH 16GB DIMM DDR4 2400MT/s            | 1         | 1%      |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s             | 1         | 1%      |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1%      |
| SK hynix RAM H9CCNNNBJTALAR-NVD 4GB Row Of Chips LPDDR3 2133MT/s | 1         | 1%      |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 1%      |
| Samsung RAM Module 4GB Row Of Chips LPDDR3 2133MT/s              | 1         | 1%      |
| Samsung RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 1%      |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                     | 1         | 1%      |
| Samsung RAM Module 16GB DIMM DDR4 2667MT/s                       | 1         | 1%      |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1%      |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 1         | 1%      |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1%      |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1%      |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1%      |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1%      |
| Samsung RAM M393A4G43AB3-CWE 32GB DIMM DDR4 3200MT/s             | 1         | 1%      |
| Samsung RAM M393A1K43DB1-CVF 8GB DIMM DDR4 2933MT/s              | 1         | 1%      |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 3066MT/s              | 1         | 1%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 41        | 56.94%  |
| DDR3    | 19        | 26.39%  |
| LPDDR3  | 4         | 5.56%   |
| DDR5    | 2         | 2.78%   |
| Unknown | 2         | 2.78%   |
| RAM     | 1         | 1.39%   |
| LPDDR5  | 1         | 1.39%   |
| LPDDR4  | 1         | 1.39%   |
| DDR2    | 1         | 1.39%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 34        | 47.22%  |
| SODIMM       | 31        | 43.06%  |
| Row Of Chips | 7         | 9.72%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 28        | 35.9%   |
| 4096  | 20        | 25.64%  |
| 16384 | 12        | 15.38%  |
| 32768 | 9         | 11.54%  |
| 2048  | 5         | 6.41%   |
| 65536 | 3         | 3.85%   |
| 49152 | 1         | 1.28%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 24        | 29.27%  |
| 1600    | 12        | 14.63%  |
| 2667    | 11        | 13.41%  |
| 2400    | 5         | 6.1%    |
| 2133    | 5         | 6.1%    |
| 1333    | 4         | 4.88%   |
| 1866    | 3         | 3.66%   |
| 1066    | 3         | 3.66%   |
| 4800    | 2         | 2.44%   |
| 1867    | 2         | 2.44%   |
| 800     | 2         | 2.44%   |
| 6400    | 1         | 1.22%   |
| 4267    | 1         | 1.22%   |
| 3733    | 1         | 1.22%   |
| 3466    | 1         | 1.22%   |
| 3066    | 1         | 1.22%   |
| 2933    | 1         | 1.22%   |
| 1334    | 1         | 1.22%   |
| 667     | 1         | 1.22%   |
| Unknown | 1         | 1.22%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| HP LaserJet P1102 | 1         | 100%    |

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
| Chicony Electronics                    | 15        | 24.19%  |
| Microdia                               | 6         | 9.68%   |
| IMC Networks                           | 6         | 9.68%   |
| Realtek Semiconductor                  | 5         | 8.06%   |
| Bison Electronics                      | 5         | 8.06%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 6.45%   |
| Suyin                                  | 3         | 4.84%   |
| Luxvisions Innotech Limited            | 3         | 4.84%   |
| Logitech                               | 3         | 4.84%   |
| Sunplus Innovation Technology          | 2         | 3.23%   |
| Microsoft                              | 2         | 3.23%   |
| Syntek                                 | 1         | 1.61%   |
| SunplusIT                              | 1         | 1.61%   |
| Quanta                                 | 1         | 1.61%   |
| Importek                               | 1         | 1.61%   |
| icSpring                               | 1         | 1.61%   |
| Creative Technology                    | 1         | 1.61%   |
| Apple                                  | 1         | 1.61%   |
| Acer                                   | 1         | 1.61%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                              | 5         | 7.81%   |
| Chicony HP Truevision HD                                    | 3         | 4.69%   |
| Bison Integrated Camera                                     | 3         | 4.69%   |
| Realtek Integrated_Webcam_HD                                | 2         | 3.13%   |
| Realtek Integrated Webcam HD                                | 2         | 3.13%   |
| Microdia Integrated Webcam HD                               | 2         | 3.13%   |
| Chicony Integrated HP HD Webcam                             | 2         | 3.13%   |
| Syntek Integrated Camera                                    | 1         | 1.56%   |
| Suyin HP Truevision HD                                      | 1         | 1.56%   |
| Suyin HD WebCam                                             | 1         | 1.56%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 1.56%   |
| SunplusIT HD Webcam                                         | 1         | 1.56%   |
| Sunplus Laptop_Integrated_Webcam_FHD                        | 1         | 1.56%   |
| Sunplus HD WebCam                                           | 1         | 1.56%   |
| Realtek EasyCamera                                          | 1         | 1.56%   |
| Quanta ACER HD User Facing                                  | 1         | 1.56%   |
| Microsoft LifeCam VX-700                                    | 1         | 1.56%   |
| Microsoft LifeCam HD-3000                                   | 1         | 1.56%   |
| Microdia USB 2.0 Camera                                     | 1         | 1.56%   |
| Microdia Lenovo EasyCamera                                  | 1         | 1.56%   |
| Microdia Integrated_Webcam_HD                               | 1         | 1.56%   |
| Microdia Integrated Camera                                  | 1         | 1.56%   |
| Luxvisions Innotech Limited Integrated Camera               | 1         | 1.56%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera         | 1         | 1.56%   |
| Luxvisions Innotech Limited HP HD Camera                    | 1         | 1.56%   |
| Logitech Webcam C270                                        | 1         | 1.56%   |
| Logitech Webcam C120                                        | 1         | 1.56%   |
| Logitech Webcam B500                                        | 1         | 1.56%   |
| Logitech QuickCam Vision Pro                                | 1         | 1.56%   |
| Importek TOSHIBA Web Camera - HD                            | 1         | 1.56%   |
| IMC Networks USB2.0 HD IR UVC WebCam                        | 1         | 1.56%   |
| icSpring camera                                             | 1         | 1.56%   |
| Creative Live! Cam Chat HD [VF0700]                         | 1         | 1.56%   |
| Chicony USB2.0 HD UVC WebCam                                | 1         | 1.56%   |
| Chicony USB2.0 Camera                                       | 1         | 1.56%   |
| Chicony TOSHIBA Web Camera - HD                             | 1         | 1.56%   |
| Chicony Lenovo EasyCamera                                   | 1         | 1.56%   |
| Chicony Integrated RGB Camera                               | 1         | 1.56%   |
| Chicony Integrated Camera (1280x720@30)                     | 1         | 1.56%   |
| Chicony HP TrueVision HD Camera                             | 1         | 1.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 8         | 61.54%  |
| Synaptics             | 4         | 30.77%  |
| Elan Microelectronics | 1         | 7.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS491                           | 2         | 15.38%  |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 2         | 15.38%  |
| Validity Sensors VFS7552 Touch Fingerprint Sensor | 1         | 7.69%   |
| Validity Sensors VFS5011 Fingerprint Reader       | 1         | 7.69%   |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 7.69%   |
| Validity Sensors VFS 5011 fingerprint sensor      | 1         | 7.69%   |
| Validity Sensors Swipe Fingerprint Sensor         | 1         | 7.69%   |
| Validity Sensors Fingerprint scanner              | 1         | 7.69%   |
| Synaptics WBDI                                    | 1         | 7.69%   |
| Synaptics UWP WBDI Device                         | 1         | 7.69%   |
| Elan ELAN:ARM-M4                                  | 1         | 7.69%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Broadcom         | 2         | 40%     |
| SCM Microsystems | 1         | 20%     |
| OmniKey          | 1         | 20%     |
| Alcor Micro      | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 1         | 20%     |
| OmniKey CardMan 3021 / 3121                            | 1         | 20%     |
| Broadcom BCM5880 Secure Applications Processor         | 1         | 20%     |
| Broadcom 58200                                         | 1         | 20%     |
| Alcor Micro AU9540 Smartcard Reader                    | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 61        | 53.51%  |
| 1     | 40        | 35.09%  |
| 2     | 8         | 7.02%   |
| 5     | 2         | 1.75%   |
| 3     | 2         | 1.75%   |
| 7     | 1         | 0.88%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 18        | 25.71%  |
| Fingerprint reader       | 13        | 18.57%  |
| Net/wireless             | 9         | 12.86%  |
| Multimedia controller    | 6         | 8.57%   |
| Sound                    | 4         | 5.71%   |
| Unassigned class         | 3         | 4.29%   |
| Net/ethernet             | 3         | 4.29%   |
| Bluetooth                | 3         | 4.29%   |
| Network                  | 2         | 2.86%   |
| Firewire controller      | 2         | 2.86%   |
| Communication controller | 2         | 2.86%   |
| Storage/raid             | 1         | 1.43%   |
| Storage/ide              | 1         | 1.43%   |
| Storage                  | 1         | 1.43%   |
| Chipcard                 | 1         | 1.43%   |
| Camera                   | 1         | 1.43%   |

