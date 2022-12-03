SteamOS - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------

A project to collect tested hardware configurations for SteamOS.

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

Total: 446

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Valve     | Jupiter                     | [ec26a28bff](https://linux-hardware.org/?probe=ec26a28bff) | Dec 01, 2022 |
| Valve     | Jupiter                     | [a9299c074e](https://linux-hardware.org/?probe=a9299c074e) | Nov 29, 2022 |
| Valve     | Jupiter                     | [0f40429822](https://linux-hardware.org/?probe=0f40429822) | Nov 29, 2022 |
| Valve     | Jupiter                     | [de1a950876](https://linux-hardware.org/?probe=de1a950876) | Nov 29, 2022 |
| Apple     | MacBookAir6,2               | [ed4692d2a7](https://linux-hardware.org/?probe=ed4692d2a7) | Nov 28, 2022 |
| Valve     | Jupiter                     | [637e97b132](https://linux-hardware.org/?probe=637e97b132) | Nov 28, 2022 |
| Valve     | Jupiter                     | [f0d9943604](https://linux-hardware.org/?probe=f0d9943604) | Nov 28, 2022 |
| Valve     | Jupiter                     | [81b0ea6c7a](https://linux-hardware.org/?probe=81b0ea6c7a) | Nov 27, 2022 |
| Valve     | Jupiter                     | [1d12c5839a](https://linux-hardware.org/?probe=1d12c5839a) | Nov 27, 2022 |
| Valve     | Jupiter                     | [bee2852cb0](https://linux-hardware.org/?probe=bee2852cb0) | Nov 27, 2022 |
| Valve     | Jupiter                     | [ea37f7d713](https://linux-hardware.org/?probe=ea37f7d713) | Nov 26, 2022 |
| Valve     | Jupiter                     | [caf4a9c4d8](https://linux-hardware.org/?probe=caf4a9c4d8) | Nov 26, 2022 |
| Valve     | Jupiter                     | [c17d27ef9b](https://linux-hardware.org/?probe=c17d27ef9b) | Nov 26, 2022 |
| Valve     | Jupiter                     | [0a172d85fd](https://linux-hardware.org/?probe=0a172d85fd) | Nov 26, 2022 |
| Valve     | Jupiter                     | [7412d8b03b](https://linux-hardware.org/?probe=7412d8b03b) | Nov 26, 2022 |
| Valve     | Jupiter                     | [24d078fe91](https://linux-hardware.org/?probe=24d078fe91) | Nov 26, 2022 |
| Valve     | Jupiter                     | [5751db0994](https://linux-hardware.org/?probe=5751db0994) | Nov 24, 2022 |
| Valve     | Jupiter                     | [29f6c597e4](https://linux-hardware.org/?probe=29f6c597e4) | Nov 23, 2022 |
| Valve     | Jupiter                     | [6049221fab](https://linux-hardware.org/?probe=6049221fab) | Nov 23, 2022 |
| Valve     | Jupiter                     | [4c3a9fe5ae](https://linux-hardware.org/?probe=4c3a9fe5ae) | Nov 23, 2022 |
| Valve     | Jupiter                     | [575ab984df](https://linux-hardware.org/?probe=575ab984df) | Nov 21, 2022 |
| Valve     | Jupiter                     | [1e7b9730a4](https://linux-hardware.org/?probe=1e7b9730a4) | Nov 21, 2022 |
| Valve     | Jupiter                     | [e9f2caddf6](https://linux-hardware.org/?probe=e9f2caddf6) | Nov 21, 2022 |
| Valve     | Jupiter                     | [dd6f589d44](https://linux-hardware.org/?probe=dd6f589d44) | Nov 20, 2022 |
| Valve     | Jupiter                     | [0e77de9dba](https://linux-hardware.org/?probe=0e77de9dba) | Nov 20, 2022 |
| HP        | Pavilion 17                 | [1d4d49c9e4](https://linux-hardware.org/?probe=1d4d49c9e4) | Nov 19, 2022 |
| Valve     | Jupiter                     | [c89535828a](https://linux-hardware.org/?probe=c89535828a) | Nov 19, 2022 |
| Valve     | Jupiter                     | [5932954a14](https://linux-hardware.org/?probe=5932954a14) | Nov 19, 2022 |
| Valve     | Jupiter                     | [d7c9c529b6](https://linux-hardware.org/?probe=d7c9c529b6) | Nov 18, 2022 |
| Valve     | Jupiter                     | [d008ed40fe](https://linux-hardware.org/?probe=d008ed40fe) | Nov 17, 2022 |
| Valve     | Jupiter                     | [01e0010535](https://linux-hardware.org/?probe=01e0010535) | Nov 16, 2022 |
| Valve     | Jupiter                     | [4ab915f825](https://linux-hardware.org/?probe=4ab915f825) | Nov 15, 2022 |
| Valve     | Jupiter                     | [92eb4009f3](https://linux-hardware.org/?probe=92eb4009f3) | Nov 14, 2022 |
| Valve     | Jupiter                     | [0bd1833d8c](https://linux-hardware.org/?probe=0bd1833d8c) | Nov 13, 2022 |
| Valve     | Jupiter                     | [f90da254ff](https://linux-hardware.org/?probe=f90da254ff) | Nov 13, 2022 |
| Valve     | Jupiter                     | [0046f0e15d](https://linux-hardware.org/?probe=0046f0e15d) | Nov 13, 2022 |
| Valve     | Jupiter                     | [649043bb19](https://linux-hardware.org/?probe=649043bb19) | Nov 13, 2022 |
| Valve     | Jupiter                     | [5c1a39b012](https://linux-hardware.org/?probe=5c1a39b012) | Nov 13, 2022 |
| Valve     | Jupiter                     | [62e925fd8a](https://linux-hardware.org/?probe=62e925fd8a) | Nov 12, 2022 |
| Valve     | Jupiter                     | [829b573205](https://linux-hardware.org/?probe=829b573205) | Nov 12, 2022 |
| Valve     | Jupiter                     | [ed3f6fb61d](https://linux-hardware.org/?probe=ed3f6fb61d) | Nov 12, 2022 |
| Valve     | Jupiter                     | [c1805091ef](https://linux-hardware.org/?probe=c1805091ef) | Nov 12, 2022 |
| Valve     | Jupiter                     | [54bca16c61](https://linux-hardware.org/?probe=54bca16c61) | Nov 11, 2022 |
| Valve     | Jupiter                     | [34582d82a1](https://linux-hardware.org/?probe=34582d82a1) | Nov 10, 2022 |
| Valve     | Jupiter                     | [6227fbbebb](https://linux-hardware.org/?probe=6227fbbebb) | Nov 10, 2022 |
| ASUSTek   | ROG Zephyrus G15 GA503QR... | [2067c76d7b](https://linux-hardware.org/?probe=2067c76d7b) | Nov 09, 2022 |
| Valve     | Jupiter                     | [340ef95fd9](https://linux-hardware.org/?probe=340ef95fd9) | Nov 08, 2022 |
| Valve     | Jupiter                     | [5673f6f505](https://linux-hardware.org/?probe=5673f6f505) | Nov 08, 2022 |
| Valve     | Jupiter                     | [020eadb15a](https://linux-hardware.org/?probe=020eadb15a) | Nov 08, 2022 |
| Valve     | Jupiter                     | [3e3e947f9e](https://linux-hardware.org/?probe=3e3e947f9e) | Nov 08, 2022 |
| Valve     | Jupiter                     | [1991a35643](https://linux-hardware.org/?probe=1991a35643) | Nov 08, 2022 |
| GPD       | G1619-04                    | [0c0542ac2e](https://linux-hardware.org/?probe=0c0542ac2e) | Nov 07, 2022 |
| Valve     | Jupiter                     | [88af410b70](https://linux-hardware.org/?probe=88af410b70) | Nov 07, 2022 |
| GPD       | G1619-04                    | [ce6d16840e](https://linux-hardware.org/?probe=ce6d16840e) | Nov 07, 2022 |
| Valve     | Jupiter                     | [695f4b6a83](https://linux-hardware.org/?probe=695f4b6a83) | Nov 06, 2022 |
| Valve     | Jupiter                     | [5800bb0b18](https://linux-hardware.org/?probe=5800bb0b18) | Nov 06, 2022 |
| Valve     | Jupiter                     | [9e7987531b](https://linux-hardware.org/?probe=9e7987531b) | Nov 06, 2022 |
| Valve     | Jupiter                     | [2cc3a0b5de](https://linux-hardware.org/?probe=2cc3a0b5de) | Nov 06, 2022 |
| Valve     | Jupiter                     | [df94c19aa6](https://linux-hardware.org/?probe=df94c19aa6) | Nov 06, 2022 |
| Valve     | Jupiter                     | [55420be889](https://linux-hardware.org/?probe=55420be889) | Nov 05, 2022 |
| Valve     | Jupiter                     | [55293ff823](https://linux-hardware.org/?probe=55293ff823) | Nov 05, 2022 |
| Valve     | Jupiter                     | [946d382a37](https://linux-hardware.org/?probe=946d382a37) | Nov 05, 2022 |
| Valve     | Jupiter                     | [5c5b229108](https://linux-hardware.org/?probe=5c5b229108) | Nov 05, 2022 |
| Valve     | Jupiter                     | [62160ec2e5](https://linux-hardware.org/?probe=62160ec2e5) | Nov 03, 2022 |
| Apple     | MacBookPro8,1               | [b4f9d04f4d](https://linux-hardware.org/?probe=b4f9d04f4d) | Nov 03, 2022 |
| Valve     | Jupiter                     | [1757bc1f5a](https://linux-hardware.org/?probe=1757bc1f5a) | Nov 03, 2022 |
| Valve     | Jupiter                     | [f6295954bc](https://linux-hardware.org/?probe=f6295954bc) | Nov 02, 2022 |
| Valve     | Jupiter                     | [13e280e72f](https://linux-hardware.org/?probe=13e280e72f) | Nov 02, 2022 |
| Valve     | Jupiter                     | [99521b7f24](https://linux-hardware.org/?probe=99521b7f24) | Nov 02, 2022 |
| Valve     | Jupiter                     | [cf9998e9b9](https://linux-hardware.org/?probe=cf9998e9b9) | Nov 01, 2022 |
| Valve     | Jupiter                     | [9d237f0d30](https://linux-hardware.org/?probe=9d237f0d30) | Oct 31, 2022 |
| Valve     | Jupiter                     | [92b732ad9a](https://linux-hardware.org/?probe=92b732ad9a) | Oct 31, 2022 |
| Valve     | Jupiter                     | [d4c562a178](https://linux-hardware.org/?probe=d4c562a178) | Oct 30, 2022 |
| Valve     | Jupiter                     | [2d381c1626](https://linux-hardware.org/?probe=2d381c1626) | Oct 30, 2022 |
| Valve     | Jupiter                     | [dfc3eee826](https://linux-hardware.org/?probe=dfc3eee826) | Oct 29, 2022 |
| Valve     | Jupiter                     | [0405c29890](https://linux-hardware.org/?probe=0405c29890) | Oct 29, 2022 |
| Valve     | Jupiter                     | [127bd00558](https://linux-hardware.org/?probe=127bd00558) | Oct 28, 2022 |
| Valve     | Jupiter                     | [7cc988201b](https://linux-hardware.org/?probe=7cc988201b) | Oct 28, 2022 |
| Valve     | Jupiter                     | [746fdbcdec](https://linux-hardware.org/?probe=746fdbcdec) | Oct 26, 2022 |
| Valve     | Jupiter                     | [088235cbff](https://linux-hardware.org/?probe=088235cbff) | Oct 26, 2022 |
| Google    | Droid                       | [c8e4007ce4](https://linux-hardware.org/?probe=c8e4007ce4) | Oct 26, 2022 |
| Valve     | Jupiter                     | [dc86de125e](https://linux-hardware.org/?probe=dc86de125e) | Oct 25, 2022 |
| Valve     | Jupiter                     | [98a9dbc46f](https://linux-hardware.org/?probe=98a9dbc46f) | Oct 25, 2022 |
| Valve     | Jupiter                     | [c12839567e](https://linux-hardware.org/?probe=c12839567e) | Oct 25, 2022 |
| Valve     | Jupiter                     | [6ed87cbcfb](https://linux-hardware.org/?probe=6ed87cbcfb) | Oct 25, 2022 |
| Valve     | Jupiter                     | [fe664e172e](https://linux-hardware.org/?probe=fe664e172e) | Oct 24, 2022 |
| Valve     | Jupiter                     | [1963771551](https://linux-hardware.org/?probe=1963771551) | Oct 24, 2022 |
| Valve     | Jupiter                     | [e474d0929b](https://linux-hardware.org/?probe=e474d0929b) | Oct 24, 2022 |
| Valve     | Jupiter                     | [6e4712d276](https://linux-hardware.org/?probe=6e4712d276) | Oct 23, 2022 |
| Valve     | Jupiter                     | [719742423c](https://linux-hardware.org/?probe=719742423c) | Oct 23, 2022 |
| Valve     | Jupiter                     | [3e696c2b87](https://linux-hardware.org/?probe=3e696c2b87) | Oct 23, 2022 |
| Valve     | Jupiter                     | [b05efe341f](https://linux-hardware.org/?probe=b05efe341f) | Oct 22, 2022 |
| Valve     | Jupiter                     | [39c064d0df](https://linux-hardware.org/?probe=39c064d0df) | Oct 22, 2022 |
| Valve     | Jupiter                     | [302efb993a](https://linux-hardware.org/?probe=302efb993a) | Oct 22, 2022 |
| ADVANCE   | PS5077                      | [998e544711](https://linux-hardware.org/?probe=998e544711) | Oct 22, 2022 |
| ADVANCE   | PS5077                      | [97bfff0fc6](https://linux-hardware.org/?probe=97bfff0fc6) | Oct 22, 2022 |
| Valve     | Jupiter                     | [024fdc987b](https://linux-hardware.org/?probe=024fdc987b) | Oct 21, 2022 |
| Valve     | Jupiter                     | [13c98e0adc](https://linux-hardware.org/?probe=13c98e0adc) | Oct 21, 2022 |
| Valve     | Jupiter                     | [2582be110d](https://linux-hardware.org/?probe=2582be110d) | Oct 21, 2022 |
| MSI       | GP66 Leopard 11UH           | [9485d1e744](https://linux-hardware.org/?probe=9485d1e744) | Oct 20, 2022 |
| Valve     | Jupiter                     | [6249475f24](https://linux-hardware.org/?probe=6249475f24) | Oct 20, 2022 |
| Valve     | Jupiter                     | [7cb825e738](https://linux-hardware.org/?probe=7cb825e738) | Oct 20, 2022 |
| Valve     | Jupiter                     | [ea0d3e9186](https://linux-hardware.org/?probe=ea0d3e9186) | Oct 20, 2022 |
| Valve     | Jupiter                     | [a314a908eb](https://linux-hardware.org/?probe=a314a908eb) | Oct 20, 2022 |
| Valve     | Jupiter                     | [53e7ae8cd4](https://linux-hardware.org/?probe=53e7ae8cd4) | Oct 20, 2022 |
| Valve     | Jupiter                     | [bdca0279e2](https://linux-hardware.org/?probe=bdca0279e2) | Oct 20, 2022 |
| Valve     | Jupiter                     | [3fada6964f](https://linux-hardware.org/?probe=3fada6964f) | Oct 19, 2022 |
| Lenovo    | IdeaPad 1 14IAU7 82QC       | [429cfdd3df](https://linux-hardware.org/?probe=429cfdd3df) | Oct 19, 2022 |
| Valve     | Jupiter                     | [982d4175a3](https://linux-hardware.org/?probe=982d4175a3) | Oct 19, 2022 |
| Valve     | Jupiter                     | [1e000a30c5](https://linux-hardware.org/?probe=1e000a30c5) | Oct 18, 2022 |
| Valve     | Jupiter                     | [a52a79aad6](https://linux-hardware.org/?probe=a52a79aad6) | Oct 18, 2022 |
| Valve     | Jupiter                     | [0a198cb541](https://linux-hardware.org/?probe=0a198cb541) | Oct 18, 2022 |
| Valve     | Jupiter                     | [fb6fa1c746](https://linux-hardware.org/?probe=fb6fa1c746) | Oct 17, 2022 |
| Valve     | Jupiter                     | [1c513b151b](https://linux-hardware.org/?probe=1c513b151b) | Oct 17, 2022 |
| Valve     | Jupiter                     | [992d2b539a](https://linux-hardware.org/?probe=992d2b539a) | Oct 17, 2022 |
| Valve     | Jupiter                     | [0526c93d55](https://linux-hardware.org/?probe=0526c93d55) | Oct 17, 2022 |
| Valve     | Jupiter                     | [8a5f4671f1](https://linux-hardware.org/?probe=8a5f4671f1) | Oct 17, 2022 |
| Valve     | Jupiter                     | [281229d9ba](https://linux-hardware.org/?probe=281229d9ba) | Oct 16, 2022 |
| Valve     | Jupiter                     | [dde3144879](https://linux-hardware.org/?probe=dde3144879) | Oct 16, 2022 |
| Valve     | Jupiter                     | [7559400f9a](https://linux-hardware.org/?probe=7559400f9a) | Oct 15, 2022 |
| Valve     | Jupiter                     | [022a7cab63](https://linux-hardware.org/?probe=022a7cab63) | Oct 15, 2022 |
| Valve     | Jupiter                     | [bd47ebea62](https://linux-hardware.org/?probe=bd47ebea62) | Oct 15, 2022 |
| Valve     | Jupiter                     | [627b9225cb](https://linux-hardware.org/?probe=627b9225cb) | Oct 15, 2022 |
| Valve     | Jupiter                     | [9ed7280a28](https://linux-hardware.org/?probe=9ed7280a28) | Oct 14, 2022 |
| Valve     | Jupiter                     | [2d38b191e7](https://linux-hardware.org/?probe=2d38b191e7) | Oct 14, 2022 |
| Valve     | Jupiter                     | [e5f2c8aaae](https://linux-hardware.org/?probe=e5f2c8aaae) | Oct 14, 2022 |
| Valve     | Jupiter                     | [261a0464f4](https://linux-hardware.org/?probe=261a0464f4) | Oct 14, 2022 |
| AZW       | MINI S                      | [d12969169f](https://linux-hardware.org/?probe=d12969169f) | Oct 14, 2022 |
| Valve     | Jupiter                     | [cb0355ddf3](https://linux-hardware.org/?probe=cb0355ddf3) | Oct 13, 2022 |
| Valve     | Jupiter                     | [ec6c38cc2e](https://linux-hardware.org/?probe=ec6c38cc2e) | Oct 13, 2022 |
| Valve     | Jupiter                     | [62bdf474b3](https://linux-hardware.org/?probe=62bdf474b3) | Oct 11, 2022 |
| Valve     | Jupiter                     | [6da0b199d1](https://linux-hardware.org/?probe=6da0b199d1) | Oct 10, 2022 |
| Valve     | Jupiter                     | [c06c56de15](https://linux-hardware.org/?probe=c06c56de15) | Oct 10, 2022 |
| Valve     | Jupiter                     | [4c324f424d](https://linux-hardware.org/?probe=4c324f424d) | Oct 10, 2022 |
| Lenovo    | IdeaPad 3 15ITL6 82H8       | [2e1db47b63](https://linux-hardware.org/?probe=2e1db47b63) | Oct 10, 2022 |
| Valve     | Jupiter                     | [a5c71515b9](https://linux-hardware.org/?probe=a5c71515b9) | Oct 09, 2022 |
| Valve     | Jupiter                     | [eb5a512250](https://linux-hardware.org/?probe=eb5a512250) | Oct 09, 2022 |
| Valve     | Jupiter                     | [34b991043f](https://linux-hardware.org/?probe=34b991043f) | Oct 09, 2022 |
| Valve     | Jupiter                     | [c5c31bcc13](https://linux-hardware.org/?probe=c5c31bcc13) | Oct 08, 2022 |
| Valve     | Jupiter                     | [30d44ab77b](https://linux-hardware.org/?probe=30d44ab77b) | Oct 08, 2022 |
| Valve     | Jupiter                     | [2d8b46d523](https://linux-hardware.org/?probe=2d8b46d523) | Oct 07, 2022 |
| Valve     | Jupiter                     | [e064c0c3be](https://linux-hardware.org/?probe=e064c0c3be) | Oct 07, 2022 |
| Valve     | Jupiter                     | [ee7a8c8340](https://linux-hardware.org/?probe=ee7a8c8340) | Oct 07, 2022 |
| Valve     | Jupiter                     | [1ebf39c097](https://linux-hardware.org/?probe=1ebf39c097) | Oct 07, 2022 |
| Valve     | Jupiter                     | [8dcc3b36a0](https://linux-hardware.org/?probe=8dcc3b36a0) | Oct 06, 2022 |
| Valve     | Jupiter                     | [28900801aa](https://linux-hardware.org/?probe=28900801aa) | Oct 06, 2022 |
| Valve     | Jupiter                     | [9222d376ab](https://linux-hardware.org/?probe=9222d376ab) | Oct 06, 2022 |
| Valve     | Jupiter                     | [4905b59499](https://linux-hardware.org/?probe=4905b59499) | Oct 06, 2022 |
| Valve     | Jupiter                     | [64f5b28613](https://linux-hardware.org/?probe=64f5b28613) | Oct 06, 2022 |
| Valve     | Jupiter                     | [641bcdd8c5](https://linux-hardware.org/?probe=641bcdd8c5) | Oct 05, 2022 |
| Valve     | Jupiter                     | [471bd7e244](https://linux-hardware.org/?probe=471bd7e244) | Oct 05, 2022 |
| Valve     | Jupiter                     | [2f421c5aa6](https://linux-hardware.org/?probe=2f421c5aa6) | Oct 05, 2022 |
| Valve     | Jupiter                     | [c1206634aa](https://linux-hardware.org/?probe=c1206634aa) | Oct 05, 2022 |
| Valve     | Jupiter                     | [889099ff63](https://linux-hardware.org/?probe=889099ff63) | Oct 05, 2022 |
| Valve     | Jupiter                     | [ac2707d2e6](https://linux-hardware.org/?probe=ac2707d2e6) | Oct 05, 2022 |
| Valve     | Jupiter                     | [9dd9e70e1f](https://linux-hardware.org/?probe=9dd9e70e1f) | Oct 04, 2022 |
| Valve     | Jupiter                     | [70f65d68fc](https://linux-hardware.org/?probe=70f65d68fc) | Oct 04, 2022 |
| Valve     | Jupiter                     | [4bc40da6ce](https://linux-hardware.org/?probe=4bc40da6ce) | Oct 04, 2022 |
| Valve     | Jupiter                     | [047b9291b1](https://linux-hardware.org/?probe=047b9291b1) | Oct 03, 2022 |
| Valve     | Jupiter                     | [6bc437ef3d](https://linux-hardware.org/?probe=6bc437ef3d) | Oct 03, 2022 |
| Valve     | Jupiter                     | [c411f31824](https://linux-hardware.org/?probe=c411f31824) | Oct 03, 2022 |
| Valve     | Jupiter                     | [e051d6a0a9](https://linux-hardware.org/?probe=e051d6a0a9) | Oct 02, 2022 |
| Apple     | MacBookAir6,1               | [f5e8b6c1eb](https://linux-hardware.org/?probe=f5e8b6c1eb) | Oct 02, 2022 |
| Apple     | MacBookAir6,1               | [8e5a2bb3a6](https://linux-hardware.org/?probe=8e5a2bb3a6) | Oct 02, 2022 |
| Valve     | Jupiter                     | [5692645981](https://linux-hardware.org/?probe=5692645981) | Oct 02, 2022 |
| Valve     | Jupiter                     | [12f0d9358a](https://linux-hardware.org/?probe=12f0d9358a) | Oct 01, 2022 |
| Valve     | Jupiter                     | [9ea6c15d28](https://linux-hardware.org/?probe=9ea6c15d28) | Oct 01, 2022 |
| Valve     | Jupiter                     | [dab0a00c02](https://linux-hardware.org/?probe=dab0a00c02) | Sep 30, 2022 |
| Valve     | Jupiter                     | [4d1b722861](https://linux-hardware.org/?probe=4d1b722861) | Sep 30, 2022 |
| Valve     | Jupiter                     | [e9737fcadf](https://linux-hardware.org/?probe=e9737fcadf) | Sep 30, 2022 |
| Valve     | Jupiter                     | [5e7ec518d4](https://linux-hardware.org/?probe=5e7ec518d4) | Sep 30, 2022 |
| Valve     | Jupiter                     | [a031955ffb](https://linux-hardware.org/?probe=a031955ffb) | Sep 30, 2022 |
| Valve     | Jupiter                     | [66731152dd](https://linux-hardware.org/?probe=66731152dd) | Sep 29, 2022 |
| Valve     | Jupiter                     | [679b3600fa](https://linux-hardware.org/?probe=679b3600fa) | Sep 29, 2022 |
| Valve     | Jupiter                     | [92b774ed77](https://linux-hardware.org/?probe=92b774ed77) | Sep 29, 2022 |
| Valve     | Jupiter                     | [9de5371096](https://linux-hardware.org/?probe=9de5371096) | Sep 28, 2022 |
| Valve     | Jupiter                     | [bdc84f1b9b](https://linux-hardware.org/?probe=bdc84f1b9b) | Sep 28, 2022 |
| Valve     | Jupiter                     | [4c7799c515](https://linux-hardware.org/?probe=4c7799c515) | Sep 28, 2022 |
| GPD       | G1619-04                    | [9e99ae15fb](https://linux-hardware.org/?probe=9e99ae15fb) | Sep 27, 2022 |
| Valve     | Jupiter                     | [9a2af6352a](https://linux-hardware.org/?probe=9a2af6352a) | Sep 27, 2022 |
| Valve     | Jupiter                     | [0f1c8fad1c](https://linux-hardware.org/?probe=0f1c8fad1c) | Sep 26, 2022 |
| Valve     | Jupiter                     | [c3305d9bff](https://linux-hardware.org/?probe=c3305d9bff) | Sep 26, 2022 |
| Valve     | Jupiter                     | [8c94cd9bd3](https://linux-hardware.org/?probe=8c94cd9bd3) | Sep 26, 2022 |
| Valve     | Jupiter                     | [ebf3e70cf7](https://linux-hardware.org/?probe=ebf3e70cf7) | Sep 25, 2022 |
| Valve     | Jupiter                     | [315719a312](https://linux-hardware.org/?probe=315719a312) | Sep 25, 2022 |
| Valve     | Jupiter                     | [f5183f3eed](https://linux-hardware.org/?probe=f5183f3eed) | Sep 24, 2022 |
| Valve     | Jupiter                     | [6ddd668003](https://linux-hardware.org/?probe=6ddd668003) | Sep 24, 2022 |
| Valve     | Jupiter                     | [b70be12594](https://linux-hardware.org/?probe=b70be12594) | Sep 24, 2022 |
| Valve     | Jupiter                     | [c81b14b950](https://linux-hardware.org/?probe=c81b14b950) | Sep 23, 2022 |
| Valve     | Jupiter                     | [d03b845c90](https://linux-hardware.org/?probe=d03b845c90) | Sep 23, 2022 |
| Valve     | Jupiter                     | [ca6d2abcd9](https://linux-hardware.org/?probe=ca6d2abcd9) | Sep 23, 2022 |
| Valve     | Jupiter                     | [0b88f458d2](https://linux-hardware.org/?probe=0b88f458d2) | Sep 22, 2022 |
| Valve     | Jupiter                     | [ce15d6d4bb](https://linux-hardware.org/?probe=ce15d6d4bb) | Sep 22, 2022 |
| Valve     | Jupiter                     | [f9230d9e82](https://linux-hardware.org/?probe=f9230d9e82) | Sep 21, 2022 |
| Valve     | Jupiter                     | [a39be03b34](https://linux-hardware.org/?probe=a39be03b34) | Sep 21, 2022 |
| Valve     | Jupiter                     | [7bc45b1077](https://linux-hardware.org/?probe=7bc45b1077) | Sep 21, 2022 |
| Valve     | Jupiter                     | [721ede2e11](https://linux-hardware.org/?probe=721ede2e11) | Sep 20, 2022 |
| Valve     | Jupiter                     | [83ed33f7e6](https://linux-hardware.org/?probe=83ed33f7e6) | Sep 20, 2022 |
| Valve     | Jupiter                     | [e60653a4c7](https://linux-hardware.org/?probe=e60653a4c7) | Sep 20, 2022 |
| Valve     | Jupiter                     | [090e33f643](https://linux-hardware.org/?probe=090e33f643) | Sep 20, 2022 |
| Valve     | Jupiter                     | [919ae4fe6c](https://linux-hardware.org/?probe=919ae4fe6c) | Sep 19, 2022 |
| Valve     | Jupiter                     | [5ed6e54010](https://linux-hardware.org/?probe=5ed6e54010) | Sep 19, 2022 |
| Valve     | Jupiter                     | [52352bab7a](https://linux-hardware.org/?probe=52352bab7a) | Sep 19, 2022 |
| Valve     | Jupiter                     | [84051314e8](https://linux-hardware.org/?probe=84051314e8) | Sep 19, 2022 |
| Valve     | Jupiter                     | [de74f87be5](https://linux-hardware.org/?probe=de74f87be5) | Sep 18, 2022 |
| Valve     | Jupiter                     | [8273135785](https://linux-hardware.org/?probe=8273135785) | Sep 18, 2022 |
| Valve     | Jupiter                     | [4b802a9fe9](https://linux-hardware.org/?probe=4b802a9fe9) | Sep 18, 2022 |
| Valve     | Jupiter                     | [e65c41605f](https://linux-hardware.org/?probe=e65c41605f) | Sep 18, 2022 |
| Valve     | Jupiter                     | [b2a1aea8e2](https://linux-hardware.org/?probe=b2a1aea8e2) | Sep 17, 2022 |
| Valve     | Jupiter                     | [b667f00856](https://linux-hardware.org/?probe=b667f00856) | Sep 17, 2022 |
| Valve     | Jupiter                     | [221fd3ae1c](https://linux-hardware.org/?probe=221fd3ae1c) | Sep 17, 2022 |
| Valve     | Jupiter                     | [c4dd2bf91f](https://linux-hardware.org/?probe=c4dd2bf91f) | Sep 17, 2022 |
| Valve     | Jupiter                     | [0db4b64dcd](https://linux-hardware.org/?probe=0db4b64dcd) | Sep 16, 2022 |
| Valve     | Jupiter                     | [4540c4e930](https://linux-hardware.org/?probe=4540c4e930) | Sep 16, 2022 |
| Valve     | Jupiter                     | [47ac328960](https://linux-hardware.org/?probe=47ac328960) | Sep 16, 2022 |
| Valve     | Jupiter                     | [28a40721a8](https://linux-hardware.org/?probe=28a40721a8) | Sep 16, 2022 |
| Valve     | Jupiter                     | [44056051c4](https://linux-hardware.org/?probe=44056051c4) | Sep 16, 2022 |
| Valve     | Jupiter                     | [9adc000021](https://linux-hardware.org/?probe=9adc000021) | Sep 15, 2022 |
| Valve     | Jupiter                     | [9493095ab1](https://linux-hardware.org/?probe=9493095ab1) | Sep 15, 2022 |
| Valve     | Jupiter                     | [9817414c4e](https://linux-hardware.org/?probe=9817414c4e) | Sep 14, 2022 |
| Valve     | Jupiter                     | [0925a55100](https://linux-hardware.org/?probe=0925a55100) | Sep 13, 2022 |
| Valve     | Jupiter                     | [b2b312e843](https://linux-hardware.org/?probe=b2b312e843) | Sep 12, 2022 |
| Valve     | Jupiter                     | [694e9a60ad](https://linux-hardware.org/?probe=694e9a60ad) | Sep 11, 2022 |
| Valve     | Jupiter                     | [438ec3fe41](https://linux-hardware.org/?probe=438ec3fe41) | Sep 11, 2022 |
| Valve     | Jupiter                     | [17ddfcd578](https://linux-hardware.org/?probe=17ddfcd578) | Sep 11, 2022 |
| Valve     | Jupiter                     | [1dc4620833](https://linux-hardware.org/?probe=1dc4620833) | Sep 10, 2022 |
| Valve     | Jupiter                     | [2c95ed7c92](https://linux-hardware.org/?probe=2c95ed7c92) | Sep 10, 2022 |
| Valve     | Jupiter                     | [17eea2b641](https://linux-hardware.org/?probe=17eea2b641) | Sep 09, 2022 |
| Valve     | Jupiter                     | [49694d92f6](https://linux-hardware.org/?probe=49694d92f6) | Sep 09, 2022 |
| Valve     | Jupiter                     | [48df4850fe](https://linux-hardware.org/?probe=48df4850fe) | Sep 09, 2022 |
| Valve     | Jupiter                     | [c63b3ff391](https://linux-hardware.org/?probe=c63b3ff391) | Sep 09, 2022 |
| Valve     | Jupiter                     | [cb5ede9c6f](https://linux-hardware.org/?probe=cb5ede9c6f) | Sep 09, 2022 |
| Valve     | Jupiter                     | [9fce9d23c8](https://linux-hardware.org/?probe=9fce9d23c8) | Sep 09, 2022 |
| Valve     | Jupiter                     | [7d45c49609](https://linux-hardware.org/?probe=7d45c49609) | Sep 08, 2022 |
| ASUSTek   | ROG Zephyrus S17 GX703HS... | [041c6dac05](https://linux-hardware.org/?probe=041c6dac05) | Sep 08, 2022 |
| Valve     | Jupiter                     | [3c4865fc8c](https://linux-hardware.org/?probe=3c4865fc8c) | Sep 08, 2022 |
| Valve     | Jupiter                     | [1669287cbb](https://linux-hardware.org/?probe=1669287cbb) | Sep 07, 2022 |
| Valve     | Jupiter                     | [47baad2eed](https://linux-hardware.org/?probe=47baad2eed) | Sep 07, 2022 |
| Valve     | Jupiter                     | [eb15307366](https://linux-hardware.org/?probe=eb15307366) | Sep 07, 2022 |
| Valve     | Jupiter                     | [8cd669599d](https://linux-hardware.org/?probe=8cd669599d) | Sep 07, 2022 |
| Valve     | Jupiter                     | [090d406ac3](https://linux-hardware.org/?probe=090d406ac3) | Sep 07, 2022 |
| Valve     | Jupiter                     | [3f0eb4cd71](https://linux-hardware.org/?probe=3f0eb4cd71) | Sep 06, 2022 |
| Valve     | Jupiter                     | [04c7e44198](https://linux-hardware.org/?probe=04c7e44198) | Sep 05, 2022 |
| Valve     | Jupiter                     | [584ea1ade0](https://linux-hardware.org/?probe=584ea1ade0) | Sep 05, 2022 |
| Valve     | Jupiter                     | [bf34e42b02](https://linux-hardware.org/?probe=bf34e42b02) | Sep 04, 2022 |
| Valve     | Jupiter                     | [f9942c8a6b](https://linux-hardware.org/?probe=f9942c8a6b) | Sep 04, 2022 |
| Valve     | Jupiter                     | [93771f5a6b](https://linux-hardware.org/?probe=93771f5a6b) | Sep 04, 2022 |
| Valve     | Jupiter                     | [08728d3dc1](https://linux-hardware.org/?probe=08728d3dc1) | Sep 04, 2022 |
| Valve     | Jupiter                     | [a8038907ed](https://linux-hardware.org/?probe=a8038907ed) | Sep 03, 2022 |
| Valve     | Jupiter                     | [f35ef3a2e1](https://linux-hardware.org/?probe=f35ef3a2e1) | Sep 03, 2022 |
| Valve     | Jupiter                     | [e12248df34](https://linux-hardware.org/?probe=e12248df34) | Sep 03, 2022 |
| Valve     | Jupiter                     | [ad3ce497e7](https://linux-hardware.org/?probe=ad3ce497e7) | Sep 02, 2022 |
| Valve     | Jupiter                     | [c0094f39c5](https://linux-hardware.org/?probe=c0094f39c5) | Sep 02, 2022 |
| Valve     | Jupiter                     | [b3b1ffd7ff](https://linux-hardware.org/?probe=b3b1ffd7ff) | Sep 02, 2022 |
| Valve     | Jupiter                     | [3fdc8df5b2](https://linux-hardware.org/?probe=3fdc8df5b2) | Sep 02, 2022 |
| Valve     | Jupiter                     | [6e9790c5e7](https://linux-hardware.org/?probe=6e9790c5e7) | Sep 01, 2022 |
| Valve     | Jupiter                     | [c89533e9a2](https://linux-hardware.org/?probe=c89533e9a2) | Sep 01, 2022 |
| Valve     | Jupiter                     | [c348c06118](https://linux-hardware.org/?probe=c348c06118) | Sep 01, 2022 |
| Valve     | Jupiter                     | [60db4bfa03](https://linux-hardware.org/?probe=60db4bfa03) | Aug 31, 2022 |
| Valve     | Jupiter                     | [5a2483051c](https://linux-hardware.org/?probe=5a2483051c) | Aug 31, 2022 |
| Valve     | Jupiter                     | [0b928ad313](https://linux-hardware.org/?probe=0b928ad313) | Aug 31, 2022 |
| Valve     | Jupiter                     | [dbc549504c](https://linux-hardware.org/?probe=dbc549504c) | Aug 31, 2022 |
| Valve     | Jupiter                     | [1b38f48059](https://linux-hardware.org/?probe=1b38f48059) | Aug 30, 2022 |
| Valve     | Jupiter                     | [40b9dd39a6](https://linux-hardware.org/?probe=40b9dd39a6) | Aug 30, 2022 |
| Valve     | Jupiter                     | [ea6506cc93](https://linux-hardware.org/?probe=ea6506cc93) | Aug 30, 2022 |
| Lenovo    | IdeaPad Gaming 3 15ACH6 ... | [844a0c00e2](https://linux-hardware.org/?probe=844a0c00e2) | Aug 29, 2022 |
| Valve     | Jupiter                     | [830c22afde](https://linux-hardware.org/?probe=830c22afde) | Aug 29, 2022 |
| Dell      | XPS 13 9360                 | [1763ee1dd0](https://linux-hardware.org/?probe=1763ee1dd0) | Aug 29, 2022 |
| Valve     | Jupiter                     | [43ec7fb445](https://linux-hardware.org/?probe=43ec7fb445) | Aug 29, 2022 |
| Valve     | Jupiter                     | [3848655fce](https://linux-hardware.org/?probe=3848655fce) | Aug 28, 2022 |
| Valve     | Jupiter                     | [cd6744821b](https://linux-hardware.org/?probe=cd6744821b) | Aug 27, 2022 |
| Lenovo    | Legion Y740-15IRHg 81UH     | [521dd85c98](https://linux-hardware.org/?probe=521dd85c98) | Aug 26, 2022 |
| Valve     | Jupiter                     | [8027445785](https://linux-hardware.org/?probe=8027445785) | Aug 26, 2022 |
| Dell      | Precision 7720              | [7fafc0e50b](https://linux-hardware.org/?probe=7fafc0e50b) | Aug 26, 2022 |
| Valve     | Jupiter                     | [447edaff49](https://linux-hardware.org/?probe=447edaff49) | Aug 25, 2022 |
| Valve     | Jupiter                     | [ebd183fc4b](https://linux-hardware.org/?probe=ebd183fc4b) | Aug 25, 2022 |
| Valve     | Jupiter                     | [b74760105e](https://linux-hardware.org/?probe=b74760105e) | Aug 25, 2022 |
| Valve     | Jupiter                     | [5064c9f57b](https://linux-hardware.org/?probe=5064c9f57b) | Aug 24, 2022 |
| Valve     | Jupiter                     | [fbef109b91](https://linux-hardware.org/?probe=fbef109b91) | Aug 24, 2022 |
| Valve     | Jupiter                     | [de49ccefa5](https://linux-hardware.org/?probe=de49ccefa5) | Aug 24, 2022 |
| Valve     | Jupiter                     | [4c88b729d3](https://linux-hardware.org/?probe=4c88b729d3) | Aug 23, 2022 |
| Valve     | Jupiter                     | [ba1940016e](https://linux-hardware.org/?probe=ba1940016e) | Aug 23, 2022 |
| Valve     | Jupiter                     | [161cc0c135](https://linux-hardware.org/?probe=161cc0c135) | Aug 23, 2022 |
| Valve     | Jupiter                     | [078b8e8ff1](https://linux-hardware.org/?probe=078b8e8ff1) | Aug 22, 2022 |
| Valve     | Jupiter                     | [04b0de9007](https://linux-hardware.org/?probe=04b0de9007) | Aug 22, 2022 |
| Valve     | Jupiter                     | [1c25a3bf8a](https://linux-hardware.org/?probe=1c25a3bf8a) | Aug 22, 2022 |
| Valve     | Jupiter                     | [bc83cf9f77](https://linux-hardware.org/?probe=bc83cf9f77) | Aug 21, 2022 |
| Valve     | Jupiter                     | [36124147ef](https://linux-hardware.org/?probe=36124147ef) | Aug 20, 2022 |
| Valve     | Jupiter                     | [eb63fecd35](https://linux-hardware.org/?probe=eb63fecd35) | Aug 19, 2022 |
| Valve     | Jupiter                     | [d6b92d1aa0](https://linux-hardware.org/?probe=d6b92d1aa0) | Aug 19, 2022 |
| Valve     | Jupiter                     | [bff4d1ca46](https://linux-hardware.org/?probe=bff4d1ca46) | Aug 19, 2022 |
| Valve     | Jupiter                     | [87f3603202](https://linux-hardware.org/?probe=87f3603202) | Aug 18, 2022 |
| Valve     | Jupiter                     | [f0dc30e9f8](https://linux-hardware.org/?probe=f0dc30e9f8) | Aug 17, 2022 |
| Valve     | Jupiter                     | [5f3785b334](https://linux-hardware.org/?probe=5f3785b334) | Aug 16, 2022 |
| Valve     | Jupiter                     | [af4a593873](https://linux-hardware.org/?probe=af4a593873) | Aug 16, 2022 |
| Valve     | Jupiter                     | [c395a0f9db](https://linux-hardware.org/?probe=c395a0f9db) | Aug 16, 2022 |
| Valve     | Jupiter                     | [90ac03e747](https://linux-hardware.org/?probe=90ac03e747) | Aug 15, 2022 |
| Valve     | Jupiter                     | [c3f38697a4](https://linux-hardware.org/?probe=c3f38697a4) | Aug 15, 2022 |
| Valve     | Jupiter                     | [9ab7a2b695](https://linux-hardware.org/?probe=9ab7a2b695) | Aug 15, 2022 |
| Valve     | Jupiter                     | [2adcfce1c0](https://linux-hardware.org/?probe=2adcfce1c0) | Aug 14, 2022 |
| Valve     | Jupiter                     | [e9f1f10a4c](https://linux-hardware.org/?probe=e9f1f10a4c) | Aug 14, 2022 |
| Valve     | Jupiter                     | [50596cb93b](https://linux-hardware.org/?probe=50596cb93b) | Aug 13, 2022 |
| Valve     | Jupiter                     | [3a1e95f5d5](https://linux-hardware.org/?probe=3a1e95f5d5) | Aug 12, 2022 |
| Valve     | Jupiter                     | [b63f9aedab](https://linux-hardware.org/?probe=b63f9aedab) | Aug 12, 2022 |
| Valve     | Jupiter                     | [822737452b](https://linux-hardware.org/?probe=822737452b) | Aug 12, 2022 |
| Valve     | Jupiter                     | [9839802d27](https://linux-hardware.org/?probe=9839802d27) | Aug 12, 2022 |
| Valve     | Jupiter                     | [6b9bfad898](https://linux-hardware.org/?probe=6b9bfad898) | Aug 12, 2022 |
| Valve     | Jupiter                     | [c6e02c54e7](https://linux-hardware.org/?probe=c6e02c54e7) | Aug 11, 2022 |
| HP        | Laptop 14z-fq0000           | [9c62f8d392](https://linux-hardware.org/?probe=9c62f8d392) | Aug 11, 2022 |
| Valve     | Jupiter                     | [90e751b5cf](https://linux-hardware.org/?probe=90e751b5cf) | Aug 10, 2022 |
| Valve     | Jupiter                     | [6223a43fe2](https://linux-hardware.org/?probe=6223a43fe2) | Aug 10, 2022 |
| Valve     | Jupiter                     | [2cec170e55](https://linux-hardware.org/?probe=2cec170e55) | Aug 10, 2022 |
| AMI       | Unknown                     | [5cee81ed21](https://linux-hardware.org/?probe=5cee81ed21) | Aug 10, 2022 |
| Valve     | Jupiter                     | [68214f1af2](https://linux-hardware.org/?probe=68214f1af2) | Aug 10, 2022 |
| AMI       | Unknown                     | [7752037bab](https://linux-hardware.org/?probe=7752037bab) | Aug 10, 2022 |
| Valve     | Jupiter                     | [e4914b879a](https://linux-hardware.org/?probe=e4914b879a) | Aug 09, 2022 |
| Valve     | Jupiter                     | [813863fbbf](https://linux-hardware.org/?probe=813863fbbf) | Aug 09, 2022 |
| Valve     | Jupiter                     | [a5b1208abc](https://linux-hardware.org/?probe=a5b1208abc) | Aug 08, 2022 |
| Valve     | Jupiter                     | [a50e78265a](https://linux-hardware.org/?probe=a50e78265a) | Aug 07, 2022 |
| Valve     | Jupiter                     | [d8ef9609a7](https://linux-hardware.org/?probe=d8ef9609a7) | Aug 07, 2022 |
| Valve     | Jupiter                     | [ced35212a7](https://linux-hardware.org/?probe=ced35212a7) | Aug 07, 2022 |
| Valve     | Jupiter                     | [64a0d92417](https://linux-hardware.org/?probe=64a0d92417) | Aug 07, 2022 |
| Valve     | Jupiter                     | [b6c7ee76fa](https://linux-hardware.org/?probe=b6c7ee76fa) | Aug 06, 2022 |
| Valve     | Jupiter                     | [6bbc4f3d0a](https://linux-hardware.org/?probe=6bbc4f3d0a) | Aug 05, 2022 |
| Valve     | Jupiter                     | [d15c62e29a](https://linux-hardware.org/?probe=d15c62e29a) | Aug 05, 2022 |
| Valve     | Jupiter                     | [6f76f9d91a](https://linux-hardware.org/?probe=6f76f9d91a) | Aug 05, 2022 |
| Valve     | Jupiter                     | [4403a80bdc](https://linux-hardware.org/?probe=4403a80bdc) | Aug 03, 2022 |
| Valve     | Jupiter                     | [8689254ee7](https://linux-hardware.org/?probe=8689254ee7) | Aug 03, 2022 |
| Valve     | Jupiter                     | [bfddbf1d22](https://linux-hardware.org/?probe=bfddbf1d22) | Aug 02, 2022 |
| Valve     | Jupiter                     | [fdb514a999](https://linux-hardware.org/?probe=fdb514a999) | Aug 01, 2022 |
| Valve     | Jupiter                     | [e4c6300b68](https://linux-hardware.org/?probe=e4c6300b68) | Aug 01, 2022 |
| GPD       | G1619-02                    | [c61c4280c8](https://linux-hardware.org/?probe=c61c4280c8) | Jul 31, 2022 |
| Valve     | Jupiter                     | [ee3b662083](https://linux-hardware.org/?probe=ee3b662083) | Jul 30, 2022 |
| Acer      | Aspire A514-54              | [9a18d7476f](https://linux-hardware.org/?probe=9a18d7476f) | Jul 29, 2022 |
| Valve     | Jupiter                     | [225e2c825e](https://linux-hardware.org/?probe=225e2c825e) | Jul 29, 2022 |
| Acer      | Aspire A514-54              | [4a6c9ef157](https://linux-hardware.org/?probe=4a6c9ef157) | Jul 28, 2022 |
| Valve     | Jupiter                     | [dffaa71aed](https://linux-hardware.org/?probe=dffaa71aed) | Jul 28, 2022 |
| Valve     | Jupiter                     | [35608b206c](https://linux-hardware.org/?probe=35608b206c) | Jul 27, 2022 |
| Valve     | Jupiter                     | [e35fa6e699](https://linux-hardware.org/?probe=e35fa6e699) | Jul 27, 2022 |
| Valve     | Jupiter                     | [f43cbe28e9](https://linux-hardware.org/?probe=f43cbe28e9) | Jul 27, 2022 |
| Valve     | Jupiter                     | [d4e4413f9b](https://linux-hardware.org/?probe=d4e4413f9b) | Jul 26, 2022 |
| Valve     | Jupiter                     | [9c34e91c79](https://linux-hardware.org/?probe=9c34e91c79) | Jul 26, 2022 |
| Valve     | Jupiter                     | [b605f923c6](https://linux-hardware.org/?probe=b605f923c6) | Jul 25, 2022 |
| Valve     | Jupiter                     | [3e7b7cb8cd](https://linux-hardware.org/?probe=3e7b7cb8cd) | Jul 23, 2022 |
| Alienware | m17                         | [e14db26b9b](https://linux-hardware.org/?probe=e14db26b9b) | Jul 23, 2022 |
| Valve     | Jupiter                     | [ca07489d53](https://linux-hardware.org/?probe=ca07489d53) | Jul 23, 2022 |
| Valve     | Jupiter                     | [1860c6d71f](https://linux-hardware.org/?probe=1860c6d71f) | Jul 23, 2022 |
| Valve     | Jupiter                     | [2d0db23de3](https://linux-hardware.org/?probe=2d0db23de3) | Jul 23, 2022 |
| Valve     | Jupiter                     | [4aece18875](https://linux-hardware.org/?probe=4aece18875) | Jul 23, 2022 |
| Valve     | Jupiter                     | [44dca72cbb](https://linux-hardware.org/?probe=44dca72cbb) | Jul 22, 2022 |
| Unknown   | Unknown                     | [96af389676](https://linux-hardware.org/?probe=96af389676) | Jul 22, 2022 |
| ASRock    | X570 Extreme4 WiFi ax       | [bc52038c74](https://linux-hardware.org/?probe=bc52038c74) | Jul 21, 2022 |
| Valve     | Jupiter                     | [0cd166bdb1](https://linux-hardware.org/?probe=0cd166bdb1) | Jul 21, 2022 |
| Valve     | Jupiter                     | [2c1ad04467](https://linux-hardware.org/?probe=2c1ad04467) | Jul 18, 2022 |
| Valve     | Jupiter                     | [7f27efe00e](https://linux-hardware.org/?probe=7f27efe00e) | Jul 17, 2022 |
| HP        | Pavilion 17                 | [722f4eb4a9](https://linux-hardware.org/?probe=722f4eb4a9) | Jul 17, 2022 |
| Valve     | Jupiter                     | [b639365efd](https://linux-hardware.org/?probe=b639365efd) | Jul 16, 2022 |
| Valve     | Jupiter                     | [6c954fab9d](https://linux-hardware.org/?probe=6c954fab9d) | Jul 16, 2022 |
| Valve     | Jupiter                     | [eec9897935](https://linux-hardware.org/?probe=eec9897935) | Jul 15, 2022 |
| Valve     | Jupiter                     | [d4be0d94b4](https://linux-hardware.org/?probe=d4be0d94b4) | Jul 14, 2022 |
| Valve     | Jupiter                     | [d2f117e7f3](https://linux-hardware.org/?probe=d2f117e7f3) | Jul 14, 2022 |
| Dell      | XPS 15 9570                 | [e157e6d524](https://linux-hardware.org/?probe=e157e6d524) | Jul 14, 2022 |
| Valve     | Jupiter                     | [f7d66c8d35](https://linux-hardware.org/?probe=f7d66c8d35) | Jul 10, 2022 |
| Valve     | Jupiter                     | [0c2ea27c49](https://linux-hardware.org/?probe=0c2ea27c49) | Jul 09, 2022 |
| Valve     | Jupiter                     | [98711d54c1](https://linux-hardware.org/?probe=98711d54c1) | Jul 08, 2022 |
| Lenovo    | ThinkBook 13s G3 ACN 20Y... | [c3c73948f5](https://linux-hardware.org/?probe=c3c73948f5) | Jul 08, 2022 |
| Valve     | Jupiter                     | [3ede093138](https://linux-hardware.org/?probe=3ede093138) | Jul 07, 2022 |
| Valve     | Jupiter                     | [458276506d](https://linux-hardware.org/?probe=458276506d) | Jul 06, 2022 |
| Valve     | Jupiter                     | [663562cc6b](https://linux-hardware.org/?probe=663562cc6b) | Jul 06, 2022 |
| Valve     | Jupiter                     | [e640bab55c](https://linux-hardware.org/?probe=e640bab55c) | Jul 05, 2022 |
| Valve     | Jupiter                     | [0bd46afcda](https://linux-hardware.org/?probe=0bd46afcda) | Jul 04, 2022 |
| Valve     | Jupiter                     | [766a3583f0](https://linux-hardware.org/?probe=766a3583f0) | Jul 04, 2022 |
| Valve     | Jupiter                     | [ac0c161f66](https://linux-hardware.org/?probe=ac0c161f66) | Jul 02, 2022 |
| Valve     | Jupiter                     | [c591d23b4d](https://linux-hardware.org/?probe=c591d23b4d) | Jul 01, 2022 |
| Valve     | Jupiter                     | [bee9822ef6](https://linux-hardware.org/?probe=bee9822ef6) | Jun 30, 2022 |
| Valve     | Jupiter                     | [e98c07bc79](https://linux-hardware.org/?probe=e98c07bc79) | Jun 29, 2022 |
| Valve     | Jupiter                     | [261590e542](https://linux-hardware.org/?probe=261590e542) | Jun 29, 2022 |
| Valve     | Jupiter                     | [7c233f0a07](https://linux-hardware.org/?probe=7c233f0a07) | Jun 29, 2022 |
| Valve     | Jupiter                     | [e80815c8d4](https://linux-hardware.org/?probe=e80815c8d4) | Jun 27, 2022 |
| Valve     | Jupiter                     | [65e5ab29fd](https://linux-hardware.org/?probe=65e5ab29fd) | Jun 26, 2022 |
| Valve     | Jupiter                     | [e51f5d8645](https://linux-hardware.org/?probe=e51f5d8645) | Jun 26, 2022 |
| Valve     | Jupiter                     | [b4dd19f939](https://linux-hardware.org/?probe=b4dd19f939) | Jun 25, 2022 |
| Valve     | Jupiter                     | [c9ed3cf311](https://linux-hardware.org/?probe=c9ed3cf311) | Jun 23, 2022 |
| Dell      | G15 5510                    | [9c5777f505](https://linux-hardware.org/?probe=9c5777f505) | Jun 23, 2022 |
| Valve     | Jupiter                     | [213fbe4dd2](https://linux-hardware.org/?probe=213fbe4dd2) | Jun 22, 2022 |
| Valve     | Jupiter                     | [262a7f0cd4](https://linux-hardware.org/?probe=262a7f0cd4) | Jun 22, 2022 |
| Valve     | Jupiter                     | [f8722866b2](https://linux-hardware.org/?probe=f8722866b2) | Jun 22, 2022 |
| Valve     | Jupiter                     | [aa18022bce](https://linux-hardware.org/?probe=aa18022bce) | Jun 22, 2022 |
| Valve     | Jupiter                     | [000682313d](https://linux-hardware.org/?probe=000682313d) | Jun 20, 2022 |
| Valve     | Jupiter                     | [363ab9e4ea](https://linux-hardware.org/?probe=363ab9e4ea) | Jun 20, 2022 |
| Valve     | Jupiter                     | [dd5765a418](https://linux-hardware.org/?probe=dd5765a418) | Jun 18, 2022 |
| Valve     | Jupiter                     | [8e293bb4b1](https://linux-hardware.org/?probe=8e293bb4b1) | Jun 17, 2022 |
| Valve     | Jupiter                     | [ff0ce08944](https://linux-hardware.org/?probe=ff0ce08944) | Jun 16, 2022 |
| Valve     | Jupiter                     | [68a581ae0b](https://linux-hardware.org/?probe=68a581ae0b) | Jun 12, 2022 |
| HP        | Pavilion Gaming Laptop 1... | [df3f1b5d8f](https://linux-hardware.org/?probe=df3f1b5d8f) | Jun 11, 2022 |
| Valve     | Jupiter                     | [2353bf0f9d](https://linux-hardware.org/?probe=2353bf0f9d) | Jun 11, 2022 |
| Valve     | Jupiter                     | [17406c8741](https://linux-hardware.org/?probe=17406c8741) | Jun 11, 2022 |
| Valve     | Jupiter                     | [715e914cba](https://linux-hardware.org/?probe=715e914cba) | Jun 10, 2022 |
| Valve     | Jupiter                     | [cc0a20bb93](https://linux-hardware.org/?probe=cc0a20bb93) | Jun 06, 2022 |
| Valve     | Jupiter                     | [2fb1bfad12](https://linux-hardware.org/?probe=2fb1bfad12) | Jun 04, 2022 |
| Valve     | Jupiter                     | [322bdc2ce3](https://linux-hardware.org/?probe=322bdc2ce3) | Jun 03, 2022 |
| Valve     | Jupiter                     | [780d6b923a](https://linux-hardware.org/?probe=780d6b923a) | Jun 02, 2022 |
| Valve     | Jupiter                     | [f3910c9796](https://linux-hardware.org/?probe=f3910c9796) | May 29, 2022 |
| Valve     | Jupiter                     | [e415de106f](https://linux-hardware.org/?probe=e415de106f) | May 29, 2022 |
| Valve     | Jupiter                     | [0af4b9c805](https://linux-hardware.org/?probe=0af4b9c805) | May 29, 2022 |
| Valve     | Jupiter                     | [06b56d54d4](https://linux-hardware.org/?probe=06b56d54d4) | May 28, 2022 |
| Valve     | Jupiter                     | [1e966da4f8](https://linux-hardware.org/?probe=1e966da4f8) | May 27, 2022 |
| Valve     | Jupiter                     | [c716690aa2](https://linux-hardware.org/?probe=c716690aa2) | May 27, 2022 |
| Valve     | Jupiter                     | [43f315aa0c](https://linux-hardware.org/?probe=43f315aa0c) | May 27, 2022 |
| Valve     | Jupiter                     | [643322d821](https://linux-hardware.org/?probe=643322d821) | May 26, 2022 |
| HP        | Pavilion Gaming Laptop 1... | [b672eefb50](https://linux-hardware.org/?probe=b672eefb50) | May 25, 2022 |
| Valve     | Jupiter                     | [dee0bbedd1](https://linux-hardware.org/?probe=dee0bbedd1) | May 25, 2022 |
| Valve     | Jupiter                     | [c34173715a](https://linux-hardware.org/?probe=c34173715a) | May 24, 2022 |
| Valve     | Jupiter                     | [6ca95b630c](https://linux-hardware.org/?probe=6ca95b630c) | May 23, 2022 |
| Valve     | Jupiter                     | [7d3f9c0a5f](https://linux-hardware.org/?probe=7d3f9c0a5f) | May 23, 2022 |
| Acer      | Aspire A315-23              | [b5d37bf4f2](https://linux-hardware.org/?probe=b5d37bf4f2) | May 22, 2022 |
| Samsung   | 950XDB/951XDB/950XDY        | [fc970670a8](https://linux-hardware.org/?probe=fc970670a8) | May 22, 2022 |
| Valve     | Jupiter                     | [595b06f6c9](https://linux-hardware.org/?probe=595b06f6c9) | May 22, 2022 |
| Valve     | Jupiter                     | [d706d00651](https://linux-hardware.org/?probe=d706d00651) | May 21, 2022 |
| Valve     | Jupiter                     | [317e492fa3](https://linux-hardware.org/?probe=317e492fa3) | May 21, 2022 |
| Valve     | Jupiter                     | [f849597120](https://linux-hardware.org/?probe=f849597120) | May 18, 2022 |
| Valve     | Jupiter                     | [48df6e5c71](https://linux-hardware.org/?probe=48df6e5c71) | May 18, 2022 |
| Valve     | Jupiter                     | [9cf4d23a81](https://linux-hardware.org/?probe=9cf4d23a81) | May 13, 2022 |
| Valve     | Jupiter                     | [79f6db1d69](https://linux-hardware.org/?probe=79f6db1d69) | May 08, 2022 |
| Valve     | Jupiter                     | [771539d18d](https://linux-hardware.org/?probe=771539d18d) | May 03, 2022 |
| Valve     | Jupiter                     | [19d2c51aa6](https://linux-hardware.org/?probe=19d2c51aa6) | May 01, 2022 |
| Valve     | Jupiter                     | [1c826aed5e](https://linux-hardware.org/?probe=1c826aed5e) | Apr 30, 2022 |
| Valve     | Jupiter                     | [4c43342014](https://linux-hardware.org/?probe=4c43342014) | Apr 24, 2022 |
| Valve     | Jupiter                     | [8564bded7f](https://linux-hardware.org/?probe=8564bded7f) | Apr 21, 2022 |
| Valve     | Jupiter                     | [d761657c3a](https://linux-hardware.org/?probe=d761657c3a) | Apr 21, 2022 |
| Valve     | Jupiter                     | [f2e59fcb97](https://linux-hardware.org/?probe=f2e59fcb97) | Apr 20, 2022 |
| Valve     | Jupiter                     | [4f23fab4fd](https://linux-hardware.org/?probe=4f23fab4fd) | Apr 17, 2022 |
| Valve     | Jupiter                     | [ed07e93435](https://linux-hardware.org/?probe=ed07e93435) | Apr 16, 2022 |
| Valve     | Jupiter                     | [48aacdeee8](https://linux-hardware.org/?probe=48aacdeee8) | Apr 15, 2022 |
| Valve     | Jupiter                     | [6a042646dd](https://linux-hardware.org/?probe=6a042646dd) | Apr 14, 2022 |
| Valve     | Jupiter                     | [d4c9dba2a1](https://linux-hardware.org/?probe=d4c9dba2a1) | Apr 14, 2022 |
| Valve     | Jupiter                     | [852b6fb53a](https://linux-hardware.org/?probe=852b6fb53a) | Apr 08, 2022 |
| Valve     | Jupiter                     | [6129b15fb5](https://linux-hardware.org/?probe=6129b15fb5) | Apr 05, 2022 |
| Valve     | Jupiter                     | [ec05067a1d](https://linux-hardware.org/?probe=ec05067a1d) | Apr 03, 2022 |
| Valve     | Jupiter                     | [180c84c856](https://linux-hardware.org/?probe=180c84c856) | Apr 02, 2022 |
| Valve     | Jupiter                     | [d8625616de](https://linux-hardware.org/?probe=d8625616de) | Mar 30, 2022 |
| Valve     | Jupiter                     | [d181a912af](https://linux-hardware.org/?probe=d181a912af) | Mar 23, 2022 |
| Valve     | Jupiter                     | [0b6a21cf35](https://linux-hardware.org/?probe=0b6a21cf35) | Mar 18, 2022 |
| Valve     | Jupiter                     | [85328e8f3d](https://linux-hardware.org/?probe=85328e8f3d) | Mar 17, 2022 |
| Valve     | Jupiter                     | [023aea75e1](https://linux-hardware.org/?probe=023aea75e1) | Mar 14, 2022 |
| Valve     | Jupiter                     | [c7f6388908](https://linux-hardware.org/?probe=c7f6388908) | Mar 11, 2022 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| SteamOS 3.3.1                | 107       | 28.16%  |
| SteamOS 3.3.2                | 94        | 24.74%  |
| SteamOS 3.2                  | 58        | 15.26%  |
| SteamOS 3.3                  | 52        | 13.68%  |
| SteamOS 3.4                  | 22        | 5.79%   |
| SteamOS Snapshot             | 21        | 5.53%   |
| SteamOS 3.1                  | 11        | 2.89%   |
| SteamOS                      | 6         | 1.58%   |
| SteamOS Rolling              | 4         | 1.05%   |
| SteamOS 3.2 (steamdeck-main) | 3         | 0.79%   |
| SteamOS 3.5                  | 2         | 0.53%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SteamOS | 367       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                            | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| 5.13.0-valve21.1-1-neptune-02211-gc54cda5a36f3     | 110       | 28.65%  |
| 5.13.0-valve21.3-1-neptune                         | 93        | 24.22%  |
| 5.13.0-valve15-1-neptune-02197-gf6ec7ad3762a       | 54        | 14.06%  |
| 5.13.0-valve21-1-neptune-02209-g2a5bdc1102a0       | 35        | 9.11%   |
| 5.13.0-valve10.1-1-neptune-02144-g7fffaf925dfb     | 16        | 4.17%   |
| 5.13.0-valve24-1-neptune-02226-g5b8545e4c5a1       | 14        | 3.65%   |
| 5.13.0-valve10.3-1-neptune-02176-g5fe416c4acd8     | 13        | 3.39%   |
| 5.13.0-valve31-1-neptune                           | 11        | 2.86%   |
| 5.13.0-valve10.1-2-neptune-dri-02144-g7fffaf925dfb | 7         | 1.82%   |
| 5.13.0-valve24-1-neptune                           | 6         | 1.56%   |
| 5.13.0-valve21.2-1-neptune                         | 6         | 1.56%   |
| 5.13.0-valve14-1-neptune-02195-g5b0f749d00fa       | 5         | 1.3%    |
| 5.13.0-valve20-1-neptune-02207-gbd986a7e1c7f       | 4         | 1.04%   |
| 5.13.0-valve22-1-neptune-02213-gb68995364335       | 3         | 0.78%   |
| 5.18.1-arch1_testHoloISO_20220606.1811             | 2         | 0.52%   |
| 5.15.54-1-lts                                      | 2         | 0.52%   |
| 6.0.7-zen3-xanmod1-1                               | 1         | 0.26%   |
| 5.15.79-1-lts                                      | 1         | 0.26%   |
| 5.13.0-valve21-2-neptune-02209-g2a5bdc1102a0       | 1         | 0.26%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.13.0  | 361       | 98.37%  |
| 5.18.1  | 2         | 0.54%   |
| 5.15.54 | 2         | 0.54%   |
| 6.0.7   | 1         | 0.27%   |
| 5.15.79 | 1         | 0.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.13    | 361       | 98.37%  |
| 5.15    | 3         | 0.82%   |
| 5.18    | 2         | 0.54%   |
| 6.0     | 1         | 0.27%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 367       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| KDE5      | 362       | 98.37%  |
| Unknown   | 3         | 0.82%   |
| gamescope | 2         | 0.54%   |
| GNOME     | 1         | 0.27%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 363       | 98.64%  |
| Wayland | 3         | 0.82%   |
| Unknown | 2         | 0.54%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 363       | 98.91%  |
| SDDM    | 4         | 1.09%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang         | Notebooks | Percent |
|--------------|-----------|---------|
| en_US        | 312       | 84.78%  |
| en_GB        | 9         | 2.45%   |
| de_DE        | 9         | 2.45%   |
| fr_FR        | 7         | 1.9%    |
| en_DE        | 5         | 1.36%   |
| an_ES        | 5         | 1.36%   |
| zh_CN        | 3         | 0.82%   |
| es_ES        | 2         | 0.54%   |
| en_NL        | 2         | 0.54%   |
| sk_SK        | 1         | 0.27%   |
| ru_RU        | 1         | 0.27%   |
| pt_BR        | 1         | 0.27%   |
| pl_PL        | 1         | 0.27%   |
| nl_NL        | 1         | 0.27%   |
| it_IT        | 1         | 0.27%   |
| hr_HR        | 1         | 0.27%   |
| fr_BE        | 1         | 0.27%   |
| et_EE        | 1         | 0.27%   |
| en_SE        | 1         | 0.27%   |
| en_HK        | 1         | 0.27%   |
| en_GB.UTF-12 | 1         | 0.27%   |
| en_CA        | 1         | 0.27%   |
| ba_RU        | 1         | 0.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 360       | 98.09%  |
| EFI  | 7         | 1.91%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Btrfs | 366       | 99.73%  |
| Ext4  | 1         | 0.27%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 360       | 98.09%  |
| GPT     | 7         | 1.91%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 361       | 98.37%  |
| Yes       | 6         | 1.63%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 367       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Valve               | 333       | 90.74%  |
| Lenovo              | 5         | 1.36%   |
| Hewlett-Packard     | 5         | 1.36%   |
| GPD                 | 4         | 1.09%   |
| Dell                | 4         | 1.09%   |
| Apple               | 3         | 0.82%   |
| ASUSTek Computer    | 2         | 0.54%   |
| Acer                | 2         | 0.54%   |
| Samsung Electronics | 1         | 0.27%   |
| MSI                 | 1         | 0.27%   |
| Google              | 1         | 0.27%   |
| AZW                 | 1         | 0.27%   |
| ASRock              | 1         | 0.27%   |
| AMI                 | 1         | 0.27%   |
| Alienware           | 1         | 0.27%   |
| ADVANCE             | 1         | 0.27%   |
| Unknown             | 1         | 0.27%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Valve Jupiter                          | 333       | 90.74%  |
| GPD G1619-04                           | 3         | 0.82%   |
| HP Pavilion 17                         | 2         | 0.54%   |
| Unknown                                | 2         | 0.54%   |
| Samsung 950XDB/951XDB/950XDY           | 1         | 0.27%   |
| MSI GP66 Leopard 11UH                  | 1         | 0.27%   |
| Lenovo ThinkBook 13s G3 ACN 20YA       | 1         | 0.27%   |
| Lenovo Legion Y740-15IRHg 81UH         | 1         | 0.27%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2    | 1         | 0.27%   |
| Lenovo IdeaPad 3 15ITL6 82H8           | 1         | 0.27%   |
| Lenovo IdeaPad 1 14IAU7 82QC           | 1         | 0.27%   |
| HP Pavilion Gaming Laptop 15-ec2xxx    | 1         | 0.27%   |
| HP Pavilion Gaming Laptop 15-dk0xxx    | 1         | 0.27%   |
| HP Laptop 14z-fq0000                   | 1         | 0.27%   |
| GPD G1619-02                           | 1         | 0.27%   |
| Google Droid                           | 1         | 0.27%   |
| Dell XPS 15 9570                       | 1         | 0.27%   |
| Dell XPS 13 9360                       | 1         | 0.27%   |
| Dell Precision 7720                    | 1         | 0.27%   |
| Dell G15 5510                          | 1         | 0.27%   |
| AZW MINI S                             | 1         | 0.27%   |
| ASUS ROG Zephyrus S17 GX703HSD_GX703HS | 1         | 0.27%   |
| ASUS ROG Zephyrus G15 GA503QR_GA503QR  | 1         | 0.27%   |
| ASRock X570 Extreme4 WiFi ax           | 1         | 0.27%   |
| Apple MacBookPro8,1                    | 1         | 0.27%   |
| Apple MacBookAir6,2                    | 1         | 0.27%   |
| Apple MacBookAir6,1                    | 1         | 0.27%   |
| Alienware m17                          | 1         | 0.27%   |
| ADVANCE PS5077                         | 1         | 0.27%   |
| Acer Aspire A514-54                    | 1         | 0.27%   |
| Acer Aspire A315-23                    | 1         | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Valve Jupiter     | 333       | 90.74%  |
| HP Pavilion       | 4         | 1.09%   |
| Lenovo IdeaPad    | 3         | 0.82%   |
| GPD G1619-04      | 3         | 0.82%   |
| Dell XPS          | 2         | 0.54%   |
| ASUS ROG          | 2         | 0.54%   |
| Apple MacBookAir6 | 2         | 0.54%   |
| Acer Aspire       | 2         | 0.54%   |
| Unknown           | 2         | 0.54%   |
| Samsung 950XDB    | 1         | 0.27%   |
| MSI GP66          | 1         | 0.27%   |
| Lenovo ThinkBook  | 1         | 0.27%   |
| Lenovo Legion     | 1         | 0.27%   |
| HP Laptop         | 1         | 0.27%   |
| GPD G1619-02      | 1         | 0.27%   |
| Google Droid      | 1         | 0.27%   |
| Dell Precision    | 1         | 0.27%   |
| Dell G15          | 1         | 0.27%   |
| AZW MINI          | 1         | 0.27%   |
| ASRock X570       | 1         | 0.27%   |
| Apple MacBookPro8 | 1         | 0.27%   |
| Alienware m17     | 1         | 0.27%   |
| ADVANCE PS5077    | 1         | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2022    | 327       | 89.1%   |
| 2021    | 13        | 3.54%   |
| Unknown | 12        | 3.27%   |
| 2020    | 3         | 0.82%   |
| 2019    | 3         | 0.82%   |
| 2013    | 3         | 0.82%   |
| 2017    | 2         | 0.54%   |
| 2018    | 1         | 0.27%   |
| 2016    | 1         | 0.27%   |
| 2014    | 1         | 0.27%   |
| 2011    | 1         | 0.27%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 367       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 367       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 366       | 99.73%  |
| Yes  | 1         | 0.27%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 341       | 92.92%  |
| 4.01-8.0    | 11        | 3%      |
| 16.01-24.0  | 6         | 1.63%   |
| 3.01-4.0    | 3         | 0.82%   |
| 24.01-32.0  | 3         | 0.82%   |
| 32.01-64.0  | 2         | 0.54%   |
| 64.01-256.0 | 1         | 0.27%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 195       | 51.32%  |
| 3.01-4.0  | 89        | 23.42%  |
| 4.01-8.0  | 50        | 13.16%  |
| 1.01-2.0  | 45        | 11.84%  |
| 8.01-16.0 | 1         | 0.26%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 227       | 61.02%  |
| 1      | 134       | 36.02%  |
| 3      | 8         | 2.15%   |
| 0      | 2         | 0.54%   |
| 4      | 1         | 0.27%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 359       | 97.82%  |
| Yes       | 8         | 2.18%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 258       | 69.35%  |
| Yes       | 114       | 30.65%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 367       | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 362       | 98.64%  |
| No        | 5         | 1.36%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 169       | 46.05%  |
| UK          | 44        | 11.99%  |
| Germany     | 40        | 10.9%   |
| Canada      | 19        | 5.18%   |
| France      | 12        | 3.27%   |
| Spain       | 11        | 3%      |
| Netherlands | 10        | 2.72%   |
| Poland      | 8         | 2.18%   |
| Austria     | 5         | 1.36%   |
| Russia      | 4         | 1.09%   |
| Romania     | 4         | 1.09%   |
| Italy       | 4         | 1.09%   |
| Sweden      | 3         | 0.82%   |
| Czechia     | 3         | 0.82%   |
| China       | 3         | 0.82%   |
| Slovakia    | 2         | 0.54%   |
| Moldova     | 2         | 0.54%   |
| Hungary     | 2         | 0.54%   |
| Estonia     | 2         | 0.54%   |
| Brazil      | 2         | 0.54%   |
| Belgium     | 2         | 0.54%   |
| Peru        | 1         | 0.27%   |
| Palestine   | 1         | 0.27%   |
| Oman        | 1         | 0.27%   |
| Mexico      | 1         | 0.27%   |
| Malaysia    | 1         | 0.27%   |
| Latvia      | 1         | 0.27%   |
| Japan       | 1         | 0.27%   |
| Ireland     | 1         | 0.27%   |
| Indonesia   | 1         | 0.27%   |
| Hong Kong   | 1         | 0.27%   |
| Guatemala   | 1         | 0.27%   |
| Greece      | 1         | 0.27%   |
| Finland     | 1         | 0.27%   |
| Denmark     | 1         | 0.27%   |
| Cyprus      | 1         | 0.27%   |
| Australia   | 1         | 0.27%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Austin              | 4         | 1.08%   |
| Valencia            | 3         | 0.81%   |
| Seattle             | 3         | 0.81%   |
| Portland            | 3         | 0.81%   |
| Newcastle upon Tyne | 3         | 0.81%   |
| Madrid              | 3         | 0.81%   |
| Brooklyn            | 3         | 0.81%   |
| Washington          | 2         | 0.54%   |
| Warsaw              | 2         | 0.54%   |
| Sunnyvale           | 2         | 0.54%   |
| Stuttgart           | 2         | 0.54%   |
| Queens              | 2         | 0.54%   |
| Prague              | 2         | 0.54%   |
| Phoenix             | 2         | 0.54%   |
| Oxford              | 2         | 0.54%   |
| Nottingham          | 2         | 0.54%   |
| North Shields       | 2         | 0.54%   |
| Moscow              | 2         | 0.54%   |
| Mississauga         | 2         | 0.54%   |
| Manchester          | 2         | 0.54%   |
| Los Angeles         | 2         | 0.54%   |
| London              | 2         | 0.54%   |
| Gothenburg          | 2         | 0.54%   |
| Germantown          | 2         | 0.54%   |
| Dresden             | 2         | 0.54%   |
| Columbus            | 2         | 0.54%   |
| Colorado Springs    | 2         | 0.54%   |
| Charlotte           | 2         | 0.54%   |
| Calgary             | 2         | 0.54%   |
| Bristol             | 2         | 0.54%   |
| Boston              | 2         | 0.54%   |
| Berlin              | 2         | 0.54%   |
| Bamberg             | 2         | 0.54%   |
| Amsterdam           | 2         | 0.54%   |
| York                | 1         | 0.27%   |
| Yekaterinburg       | 1         | 0.27%   |
| Yaroslavl           | 1         | 0.27%   |
| Wokingham           | 1         | 0.27%   |
| Winter Park         | 1         | 0.27%   |
| Winston-Salem       | 1         | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Unknown                        | 184       | 199    | 29.73%  |
| Kingston                       | 76        | 83     | 12.28%  |
| Phison                         | 75        | 77     | 12.12%  |
| Kingston Technology Company    | 50        | 50     | 8.08%   |
| Unknown                        | 44        | 45     | 7.11%   |
| Phison Electronics             | 42        | 42     | 6.79%   |
| Samsung Electronics            | 40        | 43     | 6.46%   |
| O2 Micro                       | 30        | 31     | 4.85%   |
| Silicon Motion                 | 18        | 19     | 2.91%   |
| Sandisk                        | 15        | 17     | 2.42%   |
| SK hynix                       | 9         | 13     | 1.45%   |
| Solid State Storage Technology | 4         | 4      | 0.65%   |
| KIOXIA                         | 4         | 4      | 0.65%   |
| WDC                            | 2         | 2      | 0.32%   |
| Toshiba                        | 2         | 2      | 0.32%   |
| Seagate                        | 2         | 2      | 0.32%   |
| JMicron Technology             | 2         | 2      | 0.32%   |
| Apple                          | 2         | 2      | 0.32%   |
| ADATA Technology               | 2         | 2      | 0.32%   |
| Yangtze Memory Technologies    | 1         | 1      | 0.16%   |
| TrekStor                       | 1         | 1      | 0.16%   |
| SSK                            | 1         | 1      | 0.16%   |
| Realtek                        | 1         | 1      | 0.16%   |
| NGFF                           | 1         | 1      | 0.16%   |
| Micron/Crucial Technology      | 1         | 1      | 0.16%   |
| Micron Technology              | 1         | 1      | 0.16%   |
| Lexar 25                       | 1         | 1      | 0.16%   |
| KingSpec                       | 1         | 1      | 0.16%   |
| Intel                          | 1         | 1      | 0.16%   |
| Inateck                        | 1         | 1      | 0.16%   |
| External                       | 1         | 2      | 0.16%   |
| Crucial                        | 1         | 1      | 0.16%   |
| China                          | 1         | 1      | 0.16%   |
| Biwin Storage Technology       | 1         | 1      | 0.16%   |
| ASMT                           | 1         | 1      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Unknown MMC Card  512GB                               | 72        | 11.48%  |
| Phison NVMe SSD Drive 512GB                           | 54        | 8.61%   |
| Kingston Company OM3PDP3 NVMe SSD 256GB               | 50        | 7.97%   |
| Unknown                                               | 44        | 7.02%   |
| Phison PS5013 E13 NVMe Controller 256GB               | 42        | 6.7%    |
| Kingston NVMe SSD Drive 512GB                         | 42        | 6.7%    |
| Unknown MMC Card  256GB                               | 40        | 6.38%   |
| Kingston NVMe SSD Drive 256GB                         | 32        | 5.1%    |
| Unknown MMC Card  128GB                               | 27        | 4.31%   |
| Phison NVMe SSD Drive 256GB                           | 18        | 2.87%   |
| O2 Micro E2M2 64GB                                    | 16        | 2.55%   |
| O2 Micro NVMe SSD Drive 64GB                          | 15        | 2.39%   |
| Samsung MZ9LQ256HBJD-00BVL 256GB                      | 12        | 1.91%   |
| Unknown MMC Card  393GB                               | 9         | 1.44%   |
| Samsung MZ9LQ512HBLU-00BVL 512GB                      | 9         | 1.44%   |
| Unknown MMC Card  32GB                                | 8         | 1.28%   |
| Silicon Motion NVMe SSD Drive 512GB                   | 8         | 1.28%   |
| Unknown MMC Card  64GB                                | 7         | 1.12%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 128GB | 5         | 0.8%    |
| Silicon Motion NVMe SSD Drive 256GB                   | 5         | 0.8%    |
| Unknown MMC Card  500GB                               | 3         | 0.48%   |
| Unknown MMC Card  498GB                               | 3         | 0.48%   |
| Unknown MMC Card  16GB                                | 3         | 0.48%   |
| SK hynix BC711 NVMe 256GB                             | 3         | 0.48%   |
| Sandisk WDC PC SN530 SDBPTPZ-1T00 1024GB              | 3         | 0.48%   |
| Sandisk PC SN530 NVMe WDC 256GB                       | 3         | 0.48%   |
| Samsung NVMe SSD Drive 512GB                          | 3         | 0.48%   |
| Samsung NVMe SSD Drive 1024GB                         | 3         | 0.48%   |
| Unknown MMC Card  250GB                               | 2         | 0.32%   |
| Unknown MMC Card  196GB                               | 2         | 0.32%   |
| SK hynix NVMe SSD Drive 1024GB                        | 2         | 0.32%   |
| Sandisk WDC PC SN530 SDBPMPZ-256G-1101 256GB          | 2         | 0.32%   |
| SanDisk NVMe SSD Drive 512GB                          | 2         | 0.32%   |
| Samsung MZVLQ1T0HALB-00000 1024GB                     | 2         | 0.32%   |
| Phison ESMP512GKB4C3-E13TS 512GB                      | 2         | 0.32%   |
| Kingston OM3PDP3512B-A01 512GB                        | 2         | 0.32%   |
| JMicron Generic 1TB                                   | 2         | 0.32%   |
| Yangtze Memory NVMe SSD Drive 1024GB                  | 1         | 0.16%   |
| WDC WD10SPZX-75Z10T2 1TB                              | 1         | 0.16%   |
| WDC CH SN530 SDBPTPZ-1T00-1024 930GB                  | 1         | 0.16%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 66.67%  |
| WDC     | 1         | 1      | 33.33%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 21.43%  |
| JMicron Technology  | 2         | 2      | 14.29%  |
| Apple               | 2         | 2      | 14.29%  |
| TrekStor            | 1         | 1      | 7.14%   |
| NGFF                | 1         | 1      | 7.14%   |
| Lexar 25            | 1         | 1      | 7.14%   |
| KingSpec            | 1         | 1      | 7.14%   |
| Crucial             | 1         | 1      | 7.14%   |
| China               | 1         | 1      | 7.14%   |
| ASMT                | 1         | 1      | 7.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 355       | 394    | 59.46%  |
| MMC     | 225       | 243    | 37.69%  |
| SSD     | 12        | 14     | 2.01%   |
| HDD     | 3         | 3      | 0.5%    |
| Unknown | 2         | 2      | 0.34%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 355       | 389    | 59.07%  |
| MMC  | 225       | 243    | 37.44%  |
| SAS  | 11        | 12     | 1.83%   |
| SATA | 10        | 12     | 1.66%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 10        | 11     | 66.67%  |
| 0.51-1.0   | 4         | 5      | 26.67%  |
| 1.01-2.0   | 1         | 1      | 6.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 186       | 50.27%  |
| 101-250        | 105       | 28.38%  |
| 501-1000       | 38        | 10.27%  |
| 51-100         | 29        | 7.84%   |
| 1001-2000      | 10        | 2.7%    |
| More than 3000 | 2         | 0.54%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 101-250   | 145       | 38.56%  |
| 251-500   | 102       | 27.13%  |
| 21-50     | 50        | 13.3%   |
| 51-100    | 33        | 8.78%   |
| 1-20      | 30        | 7.98%   |
| 501-1000  | 12        | 3.19%   |
| 1001-2000 | 4         | 1.06%   |

Malfunc. Drives
---------------

Drive models with a malfunction

Zero info for selected period =(

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

Zero info for selected period =(

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

Zero info for selected period =(

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
| Detected | 364       | 649    | 98.11%  |
| Works    | 7         | 7      | 1.89%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Kingston Technology Company    | 122       | 31.94%  |
| Phison Electronics             | 114       | 29.84%  |
| Samsung Electronics            | 37        | 9.69%   |
| O2 Micro                       | 30        | 7.85%   |
| Silicon Motion                 | 18        | 4.71%   |
| SanDisk                        | 16        | 4.19%   |
| Intel                          | 13        | 3.4%    |
| SK hynix                       | 9         | 2.36%   |
| AMD                            | 5         | 1.31%   |
| Solid State Storage Technology | 4         | 1.05%   |
| KIOXIA                         | 4         | 1.05%   |
| Toshiba America Info Systems   | 3         | 0.79%   |
| ADATA Technology               | 2         | 0.52%   |
| Yangtze Memory Technologies    | 1         | 0.26%   |
| Micron/Crucial Technology      | 1         | 0.26%   |
| Micron Technology              | 1         | 0.26%   |
| Marvell Technology Group       | 1         | 0.26%   |
| Biwin Storage Technology       | 1         | 0.26%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Kingston Company OM3PDP3 NVMe SSD                                             | 121       | 31.43%  |
| Phison PS5013 E13 NVMe Controller                                             | 112       | 29.09%  |
| Samsung NVMe SSD Controller 980                                               | 33        | 8.57%   |
| O2 Micro Non-Volatile memory controller                                       | 30        | 7.79%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                               | 18        | 4.68%   |
| SanDisk Non-Volatile memory controller                                        | 11        | 2.86%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                | 9         | 2.34%   |
| AMD FCH SATA Controller [AHCI mode]                                           | 5         | 1.3%    |
| Solid State Storage Non-Volatile memory controller                            | 4         | 1.04%   |
| KIOXIA NVMe SSD Controller BG4                                                | 4         | 1.04%   |
| Intel Volume Management Device NVMe RAID Controller                           | 3         | 0.78%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 3         | 0.78%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                    | 2         | 0.52%   |
| SanDisk PC SN530 NVMe SSD                                                     | 2         | 0.52%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 2         | 0.52%   |
| Phison E12 NVMe Controller                                                    | 2         | 0.52%   |
| Intel Tiger Lake-LP SATA Controller                                           | 2         | 0.52%   |
| Yangtze Memory Non-Volatile memory controller                                 | 1         | 0.26%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                          | 1         | 0.26%   |
| Toshiba America Info Systems Toshiba America Info SATA controller             | 1         | 0.26%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                          | 1         | 0.26%   |
| SanDisk WD Blue SN550 NVMe SSD                                                | 1         | 0.26%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 1         | 0.26%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 1         | 0.26%   |
| Micron/Crucial P2 NVMe PCIe SSD                                               | 1         | 0.26%   |
| Micron Non-Volatile memory controller                                         | 1         | 0.26%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                    | 1         | 0.26%   |
| Kingston Company Company Non-Volatile memory controller                       | 1         | 0.26%   |
| Intel SSD 660P Series                                                         | 1         | 0.26%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 1         | 0.26%   |
| Intel Jasper Lake SATA AHCI Controller                                        | 1         | 0.26%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                             | 1         | 0.26%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                             | 1         | 0.26%   |
| Intel Alder Lake-P SATA AHCI Controller                                       | 1         | 0.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 1         | 0.26%   |
| Biwin Storage Non-Volatile memory controller                                  | 1         | 0.26%   |
| AMD FCH IDE Controller                                                        | 1         | 0.26%   |
| ADATA Non-Volatile memory controller                                          | 1         | 0.26%   |
| ADATA IM2P33F8ABR1 NVMe SSD                                                   | 1         | 0.26%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 356       | 94.18%  |
| SATA | 15        | 3.97%   |
| RAID | 6         | 1.59%   |
| IDE  | 1         | 0.26%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| AMD    | 346       | 94.28%  |
| Intel  | 21        | 5.72%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Custom APU 0405                           | 333       | 90.74%  |
| AMD Ryzen 7 6800U with Radeon Graphics        | 3         | 0.82%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 0.54%   |
| Intel Core i5-4260U CPU @ 1.40GHz             | 2         | 0.54%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 2         | 0.54%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 2         | 0.54%   |
| Intel Xeon CPU E3-1575M v5 @ 3.00GHz          | 1         | 0.27%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 0.27%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 0.27%   |
| Intel Core i7-7560U CPU @ 2.40GHz             | 1         | 0.27%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 1         | 0.27%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 1         | 0.27%   |
| Intel Core i5-8259U CPU @ 2.30GHz             | 1         | 0.27%   |
| Intel Core i5-2435M CPU @ 2.40GHz             | 1         | 0.27%   |
| Intel Celeron N5095 @ 2.00GHz                 | 1         | 0.27%   |
| Intel Atom x7-Z8750 CPU @ 1.60GHz             | 1         | 0.27%   |
| Intel 12th Gen Core i3-1215U                  | 1         | 0.27%   |
| Intel 11th Gen Core i9-11900H @ 2.50GHz       | 1         | 0.27%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 1         | 0.27%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 0.27%   |
| Intel 11th Gen Core i7-1160G7 @ 1.20GHz       | 1         | 0.27%   |
| AMD Ryzen 9 5900HS with Radeon Graphics       | 1         | 0.27%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 1         | 0.27%   |
| AMD Ryzen 7 4800U with Radeon Graphics        | 1         | 0.27%   |
| AMD Ryzen 5 5600U with Radeon Graphics        | 1         | 0.27%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 1         | 0.27%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 0.27%   |
| AMD A8-4500M APU with Radeon HD Graphics      | 1         | 0.27%   |
| AMD A10-5750M APU with Radeon HD Graphics     | 1         | 0.27%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Other                | 340       | 92.64%  |
| Intel Core i7        | 5         | 1.36%   |
| Intel Core i5        | 5         | 1.36%   |
| AMD Ryzen 5          | 5         | 1.36%   |
| AMD Ryzen 7          | 4         | 1.09%   |
| AMD Ryzen 9          | 2         | 0.54%   |
| Intel Xeon           | 1         | 0.27%   |
| Intel Pentium Silver | 1         | 0.27%   |
| Intel Celeron        | 1         | 0.27%   |
| Intel Atom           | 1         | 0.27%   |
| AMD A8               | 1         | 0.27%   |
| AMD A10              | 1         | 0.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 342       | 93.19%  |
| 2      | 9         | 2.45%   |
| 8      | 8         | 2.18%   |
| 6      | 7         | 1.91%   |
| 12     | 1         | 0.27%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 367       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 363       | 98.64%  |
| 1      | 5         | 1.36%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 367       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 360       | 98.09%  |
| 0x08900201 | 6         | 1.63%   |
| 0x0a50000c | 1         | 0.27%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Unknown       | 340       | 92.64%  |
| KabyLake      | 6         | 1.63%   |
| Zen 3         | 4         | 1.09%   |
| TigerLake     | 4         | 1.09%   |
| Zen 2         | 3         | 0.82%   |
| Piledriver    | 2         | 0.54%   |
| Haswell       | 2         | 0.54%   |
| Zen+          | 1         | 0.27%   |
| Skylake       | 1         | 0.27%   |
| Silvermont    | 1         | 0.27%   |
| SandyBridge   | 1         | 0.27%   |
| Goldmont plus | 1         | 0.27%   |
| CometLake     | 1         | 0.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| AMD    | 346       | 92.27%  |
| Intel  | 18        | 4.8%    |
| Nvidia | 11        | 2.93%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 333       | 88.8%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 1.07%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 0.8%    |
| AMD Rembrandt [Radeon 680M]                                                              | 3         | 0.8%    |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                                 | 2         | 0.53%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 2         | 0.53%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 0.53%   |
| AMD Renoir                                                                               | 2         | 0.53%   |
| Nvidia TU117M                                                                            | 1         | 0.27%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.27%   |
| Nvidia TU106BM [GeForce RTX 2060 Mobile]                                                 | 1         | 0.27%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.27%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.27%   |
| Nvidia GP104GLM [Quadro P4000 Mobile]                                                    | 1         | 0.27%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 1         | 0.27%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 0.27%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 1         | 0.27%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 0.27%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 0.27%   |
| Intel Tiger Lake-UP4 GT2 [Iris Xe Graphics]                                              | 1         | 0.27%   |
| Intel JasperLake [UHD Graphics]                                                          | 1         | 0.27%   |
| Intel Iris Plus Graphics 640                                                             | 1         | 0.27%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 0.27%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 0.27%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                                         | 1         | 0.27%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 0.27%   |
| Intel Alder Lake-UP3 GT1 [UHD Graphics]                                                  | 1         | 0.27%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1         | 0.27%   |
| AMD Trinity [Radeon HD 7640G]                                                            | 1         | 0.27%   |
| AMD Richland [Radeon HD 8650G]                                                           | 1         | 0.27%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 0.27%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 1         | 0.27%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x AMD        | 343       | 93.46%  |
| 1 x Intel      | 12        | 3.27%   |
| Intel + Nvidia | 5         | 1.36%   |
| 1 x Nvidia     | 3         | 0.82%   |
| AMD + Nvidia   | 3         | 0.82%   |
| Other          | 1         | 0.27%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 359       | 97.82%  |
| Proprietary | 8         | 2.18%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 357       | 97.28%  |
| 0.51-1.0   | 5         | 1.36%   |
| 7.01-8.0   | 2         | 0.54%   |
| 5.01-6.0   | 1         | 0.27%   |
| 1.01-2.0   | 1         | 0.27%   |
| 0.01-0.5   | 1         | 0.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| ANX                  | 189       | 41.36%  |
| Analogix             | 121       | 26.48%  |
| Valve                | 29        | 6.35%   |
| Goldstar             | 16        | 3.5%    |
| Samsung Electronics  | 12        | 2.63%   |
| Vizio                | 6         | 1.31%   |
| Chimei Innolux       | 6         | 1.31%   |
| BOE                  | 6         | 1.31%   |
| Dell                 | 5         | 1.09%   |
| ASUSTek Computer     | 5         | 1.09%   |
| Ancor Communications | 5         | 1.09%   |
| AU Optronics         | 4         | 0.88%   |
| AOC                  | 4         | 0.88%   |
| Sharp                | 3         | 0.66%   |
| Philips              | 3         | 0.66%   |
| JDI                  | 3         | 0.66%   |
| Hewlett-Packard      | 3         | 0.66%   |
| Apple                | 3         | 0.66%   |
| Acer                 | 3         | 0.66%   |
| Sony                 | 2         | 0.44%   |
| RTK                  | 2         | 0.44%   |
| Microsoft            | 2         | 0.44%   |
| BenQ                 | 2         | 0.44%   |
| ZSC                  | 1         | 0.22%   |
| YTH                  | 1         | 0.22%   |
| ViewSonic            | 1         | 0.22%   |
| TCL                  | 1         | 0.22%   |
| Sun                  | 1         | 0.22%   |
| SANYO                | 1         | 0.22%   |
| Pixio                | 1         | 0.22%   |
| PANDA                | 1         | 0.22%   |
| NRL                  | 1         | 0.22%   |
| NEC Computers        | 1         | 0.22%   |
| MSI                  | 1         | 0.22%   |
| LTM                  | 1         | 0.22%   |
| LG Display           | 1         | 0.22%   |
| Lenovo               | 1         | 0.22%   |
| INNOCN               | 1         | 0.22%   |
| InfoVision           | 1         | 0.22%   |
| Huion                | 1         | 0.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| ANX ANX7530 U ANX7539 800x1280                                         | 189       | 41.18%  |
| Analogix ANX7530 U ANX7539 800x1280                                    | 121       | 26.36%  |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                    | 29        | 6.32%   |
| JDI GPD1001H JDI0031 2560x1600 890x500mm 40.2-inch                     | 3         | 0.65%   |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                    | 3         | 0.65%   |
| Vizio E50-C1 VIZ1004 1920x1080 1095x616mm 49.5-inch                    | 2         | 0.44%   |
| Samsung Electronics C49HG9x SAM0E5D 3840x1080 1196x336mm 48.9-inch     | 2         | 0.44%   |
| Microsoft Xbox One MSH0001 1920x1080 520x290mm 23.4-inch               | 2         | 0.44%   |
| Goldstar 34GN850 GSM774A 3440x1440 800x335mm 34.1-inch                 | 2         | 0.44%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch       | 2         | 0.44%   |
| Ancor Communications ASUS VH242H ACI24F3 1920x1080 521x293mm 23.5-inch | 2         | 0.44%   |
| ZSC FHD HDR ZSCBC32 1920x1080 344x195mm 15.6-inch                      | 1         | 0.22%   |
| YTH HS133PC YTH1330 1920x1080 255x220mm 13.3-inch                      | 1         | 0.22%   |
| Vizio VO320E VIZ0035 1366x768 700x390mm 31.5-inch                      | 1         | 0.22%   |
| Vizio V585x-H1 VIZ1039 3840x2160 941x529mm 42.5-inch                   | 1         | 0.22%   |
| Vizio E241i-B1 VIZ1005 1920x1080 521x293mm 23.5-inch                   | 1         | 0.22%   |
| Vizio D24f4-J01 VIZ1044 1920x1080 527x296mm 23.8-inch                  | 1         | 0.22%   |
| ViewSonic VX2858Sml VSCD02F 1920x1080 621x341mm 27.9-inch              | 1         | 0.22%   |
| TCL SMART TV TCL6586 3840x2160 1209x680mm 54.6-inch                    | 1         | 0.22%   |
| Sun SCEI MONITOR SCE0301 1920x1080 522x294mm 23.6-inch                 | 1         | 0.22%   |
| Sony TV *00 SNY7A04 3840x2160 1218x685mm 55.0-inch                     | 1         | 0.22%   |
| Sony BW8 MS_9001 2560x1600                                             | 1         | 0.22%   |
| Sharp LQ156M1JW03 SHP155D 1920x1080 344x194mm 15.5-inch                | 1         | 0.22%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                | 1         | 0.22%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                | 1         | 0.22%   |
| SANYO LCD SAN0B75 1280x720                                             | 1         | 0.22%   |
| Samsung Electronics S34J55x SAM0F71 3440x1440 800x330mm 34.1-inch      | 1         | 0.22%   |
| Samsung Electronics S27HG5x SAM0E10 2560x1440 598x336mm 27.0-inch      | 1         | 0.22%   |
| Samsung Electronics S27A750D SAM0798 1920x1080 598x336mm 27.0-inch     | 1         | 0.22%   |
| Samsung Electronics S24B300 SAM08CC 1920x1080 521x293mm 23.5-inch      | 1         | 0.22%   |
| Samsung Electronics LCD Monitor SDC4159 1920x1080 344x194mm 15.5-inch  | 1         | 0.22%   |
| Samsung Electronics LCD Monitor SAM71B5 3840x2160 1020x570mm 46.0-inch | 1         | 0.22%   |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 700x390mm 31.5-inch  | 1         | 0.22%   |
| Samsung Electronics LCD Monitor SAM0A7E 1920x1080 1060x626mm 48.5-inch | 1         | 0.22%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 532x304mm 24.1-inch     | 1         | 0.22%   |
| Samsung Electronics C27R50x SAM0F9D 1920x1080 598x336mm 27.0-inch      | 1         | 0.22%   |
| RTK UHD HDR RTK1B1A 3840x2160 609x355mm 27.8-inch                      | 1         | 0.22%   |
| RTK FHD RTK2A3B 1920x1080 597x336mm 27.0-inch                          | 1         | 0.22%   |
| Pixio PX277P PNS0277 2560x1440 620x370mm 28.4-inch                     | 1         | 0.22%   |
| Philips PHL 345B1C PHL093D 3440x1440 797x334mm 34.0-inch               | 1         | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 800x1280          | 328       | 74.04%  |
| 1920x1080 (FHD)   | 56        | 12.64%  |
| 3840x2160 (4K)    | 16        | 3.61%   |
| 2560x1440 (QHD)   | 10        | 2.26%   |
| 3440x1440         | 9         | 2.03%   |
| 2560x1600         | 5         | 1.13%   |
| 2560x1080         | 4         | 0.9%    |
| 1366x768 (WXGA)   | 4         | 0.9%    |
| 3840x1080         | 2         | 0.45%   |
| 1600x900 (HD+)    | 2         | 0.45%   |
| 3840x1600         | 1         | 0.23%   |
| 3200x1800 (QHD+)  | 1         | 0.23%   |
| 1920x540          | 1         | 0.23%   |
| 1920x1200 (WUXGA) | 1         | 0.23%   |
| 1440x900 (WXGA+)  | 1         | 0.23%   |
| 1280x800 (WXGA)   | 1         | 0.23%   |
| 1024x768 (XGA)    | 1         | 0.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 306       | 67.85%  |
| 7       | 30        | 6.65%   |
| 15      | 17        | 3.77%   |
| 27      | 15        | 3.33%   |
| 34      | 11        | 2.44%   |
| 23      | 8         | 1.77%   |
| 24      | 7         | 1.55%   |
| 21      | 6         | 1.33%   |
| 13      | 6         | 1.33%   |
| 17      | 5         | 1.11%   |
| 49      | 4         | 0.89%   |
| 40      | 4         | 0.89%   |
| 31      | 4         | 0.89%   |
| 72      | 3         | 0.67%   |
| 14      | 3         | 0.67%   |
| 64      | 2         | 0.44%   |
| 54      | 2         | 0.44%   |
| 46      | 2         | 0.44%   |
| 36      | 2         | 0.44%   |
| 86      | 1         | 0.22%   |
| 69      | 1         | 0.22%   |
| 65      | 1         | 0.22%   |
| 57      | 1         | 0.22%   |
| 55      | 1         | 0.22%   |
| 52      | 1         | 0.22%   |
| 43      | 1         | 0.22%   |
| 42      | 1         | 0.22%   |
| 37      | 1         | 0.22%   |
| 35      | 1         | 0.22%   |
| 28      | 1         | 0.22%   |
| 26      | 1         | 0.22%   |
| 11      | 1         | 0.22%   |
| 8       | 1         | 0.22%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| Unknown     | 306       | 68%     |
| 501-600     | 29        | 6.44%   |
| 1-100       | 29        | 6.44%   |
| 301-350     | 21        | 4.67%   |
| 701-800     | 13        | 2.89%   |
| 1001-1500   | 13        | 2.89%   |
| 601-700     | 7         | 1.56%   |
| 801-900     | 6         | 1.33%   |
| 401-500     | 6         | 1.33%   |
| 201-300     | 6         | 1.33%   |
| 351-400     | 5         | 1.11%   |
| 1501-2000   | 5         | 1.11%   |
| 101-200     | 2         | 0.44%   |
| 901-1000    | 2         | 0.44%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 0.62  | 306       | 68.61%  |
| 16/9  | 88        | 19.73%  |
| 0.67  | 29        | 6.5%    |
| 21/9  | 13        | 2.91%   |
| 16/10 | 5         | 1.12%   |
| 32/9  | 3         | 0.67%   |
| 3/2   | 1         | 0.22%   |
| 1.00  | 1         | 0.22%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 306       | 68%     |
| 1-40           | 31        | 6.89%   |
| 351-500        | 18        | 4%      |
| 301-350        | 16        | 3.56%   |
| 101-110        | 16        | 3.56%   |
| 201-250        | 15        | 3.33%   |
| More than 1000 | 14        | 3.11%   |
| 501-1000       | 12        | 2.67%   |
| 81-90          | 5         | 1.11%   |
| 251-300        | 5         | 1.11%   |
| 121-130        | 5         | 1.11%   |
| 71-80          | 4         | 0.89%   |
| 51-60          | 1         | 0.22%   |
| 151-200        | 1         | 0.22%   |
| 91-100         | 1         | 0.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| Unknown       | 306       | 68%     |
| 51-100        | 42        | 9.33%   |
| 161-240       | 35        | 7.78%   |
| 101-120       | 30        | 6.67%   |
| 121-160       | 24        | 5.33%   |
| 1-50          | 11        | 2.44%   |
| More than 240 | 2         | 0.44%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 293       | 79.19%  |
| 2     | 74        | 20%     |
| 3     | 3         | 0.81%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 350       | 78.3%   |
| ASIX Electronics      | 50        | 11.19%  |
| Intel                 | 21        | 4.7%    |
| Qualcomm Atheros      | 4         | 0.89%   |
| TP-Link               | 3         | 0.67%   |
| DisplayLink           | 3         | 0.67%   |
| Microsoft             | 2         | 0.45%   |
| MediaTek              | 2         | 0.45%   |
| Lenovo                | 2         | 0.45%   |
| Broadcom Limited      | 2         | 0.45%   |
| Broadcom              | 2         | 0.45%   |
| Samsung Electronics   | 1         | 0.22%   |
| Ralink Technology     | 1         | 0.22%   |
| Google                | 1         | 0.22%   |
| Edimax Technology     | 1         | 0.22%   |
| Dell                  | 1         | 0.22%   |
| AVM                   | 1         | 0.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 333       | 67.68%  |
| ASIX AX88179 Gigabit Ethernet                                     | 50        | 10.16%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 38        | 7.72%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10        | 2.03%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 5         | 1.02%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 1.02%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 0.61%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 0.61%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.41%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 0.41%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 0.41%   |
| DisplayLink Dell Universal Dock D6000                             | 2         | 0.41%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 2         | 0.41%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1         | 0.2%    |
| TP-Link Archer T4U ver.3                                          | 1         | 0.2%    |
| TP-Link 802.11ac NIC                                              | 1         | 0.2%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.2%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 0.2%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.2%    |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.2%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.2%    |
| Realtek 802.11ac NIC                                              | 1         | 0.2%    |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1         | 0.2%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 0.2%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.2%    |
| Microsoft XBOX ACC                                                | 1         | 0.2%    |
| Microsoft Wireless XBox Controller Dongle                         | 1         | 0.2%    |
| Lenovo USB-C Dock Ethernet                                        | 1         | 0.2%    |
| Lenovo ThinkPad Lan                                               | 1         | 0.2%    |
| Intel Wireless 7265                                               | 1         | 0.2%    |
| Intel Wireless 3165                                               | 1         | 0.2%    |
| Intel WiFi Link 5100                                              | 1         | 0.2%    |
| Intel I211 Gigabit Network Connection                             | 1         | 0.2%    |
| Intel Gemini Lake PCH CNVi WiFi                                   | 1         | 0.2%    |
| Intel Ethernet Controller I225-V                                  | 1         | 0.2%    |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.2%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 0.2%    |
| Intel Centrino Advanced-N 6235                                    | 1         | 0.2%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1         | 0.2%    |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 1         | 0.2%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 336       | 89.36%  |
| Intel                 | 21        | 5.59%   |
| Qualcomm Atheros      | 4         | 1.06%   |
| TP-Link               | 3         | 0.8%    |
| Microsoft             | 2         | 0.53%   |
| MediaTek              | 2         | 0.53%   |
| Broadcom Limited      | 2         | 0.53%   |
| Broadcom              | 2         | 0.53%   |
| Ralink Technology     | 1         | 0.27%   |
| Edimax Technology     | 1         | 0.27%   |
| Dell                  | 1         | 0.27%   |
| AVM                   | 1         | 0.27%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 333       | 88.56%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 5         | 1.33%   |
| Intel Wi-Fi 6 AX200                                           | 5         | 1.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 3         | 0.8%    |
| Intel Wi-Fi 6 AX201                                           | 3         | 0.8%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 2         | 0.53%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter    | 2         | 0.53%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                   | 1         | 0.27%   |
| TP-Link Archer T4U ver.3                                      | 1         | 0.27%   |
| TP-Link 802.11ac NIC                                          | 1         | 0.27%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 1         | 0.27%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 1         | 0.27%   |
| Realtek 802.11ac NIC                                          | 1         | 0.27%   |
| Ralink RT2870/RT3070 Wireless Adapter                         | 1         | 0.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 1         | 0.27%   |
| Microsoft XBOX ACC                                            | 1         | 0.27%   |
| Microsoft Wireless XBox Controller Dongle                     | 1         | 0.27%   |
| Intel Wireless 7265                                           | 1         | 0.27%   |
| Intel Wireless 3165                                           | 1         | 0.27%   |
| Intel WiFi Link 5100                                          | 1         | 0.27%   |
| Intel Gemini Lake PCH CNVi WiFi                               | 1         | 0.27%   |
| Intel Comet Lake PCH CNVi WiFi                                | 1         | 0.27%   |
| Intel Centrino Advanced-N 6235                                | 1         | 0.27%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 1         | 0.27%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 1         | 0.27%   |
| Edimax AC600 USB                                              | 1         | 0.27%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                          | 1         | 0.27%   |
| Broadcom BCM4356 802.11ac Wireless Network Adapter            | 1         | 0.27%   |
| Broadcom BCM4331 802.11a/b/g/n                                | 1         | 0.27%   |
| AVM FRITZ!WLAN AC 860                                         | 1         | 0.27%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 53        | 46.09%  |
| ASIX Electronics      | 50        | 43.48%  |
| Intel                 | 3         | 2.61%   |
| DisplayLink           | 3         | 2.61%   |
| Lenovo                | 2         | 1.74%   |
| Samsung Electronics   | 1         | 0.87%   |
| Qualcomm Atheros      | 1         | 0.87%   |
| Google                | 1         | 0.87%   |
| Broadcom              | 1         | 0.87%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| ASIX AX88179 Gigabit Ethernet                                     | 50        | 43.1%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 38        | 32.76%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10        | 8.62%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 1.72%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 1.72%   |
| DisplayLink Dell Universal Dock D6000                             | 2         | 1.72%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.86%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.86%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.86%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.86%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 0.86%   |
| Lenovo ThinkPad Lan                                               | 1         | 0.86%   |
| Intel I211 Gigabit Network Connection                             | 1         | 0.86%   |
| Intel Ethernet Controller I225-V                                  | 1         | 0.86%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.86%   |
| Google Pixel 7                                                    | 1         | 0.86%   |
| DisplayLink USB-C Dual-4K Dock                                    | 1         | 0.86%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.86%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 367       | 76.46%  |
| Ethernet | 113       | 23.54%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 348       | 88.32%  |
| Ethernet | 46        | 11.68%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 349       | 95.1%   |
| 2     | 18        | 4.9%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 232       | 62.7%   |
| Yes  | 138       | 37.3%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| IMC Networks                    | 333       | 91.74%  |
| Intel                           | 19        | 5.23%   |
| Realtek Semiconductor           | 3         | 0.83%   |
| Qualcomm Atheros Communications | 3         | 0.83%   |
| Apple                           | 3         | 0.83%   |
| Lite-On Technology              | 1         | 0.28%   |
| Foxconn / Hon Hai               | 1         | 0.28%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| IMC Networks Bluetooth Radio                   | 333       | 91.74%  |
| Intel AX210 Bluetooth                          | 5         | 1.38%   |
| Intel AX200 Bluetooth                          | 5         | 1.38%   |
| Intel AX201 Bluetooth                          | 4         | 1.1%    |
| Qualcomm Atheros  Bluetooth Device             | 2         | 0.55%   |
| Intel Bluetooth wireless interface             | 2         | 0.55%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 2         | 0.55%   |
| Apple Bluetooth USB Host Controller            | 2         | 0.55%   |
| Realtek  Bluetooth 4.2 Adapter                 | 1         | 0.28%   |
| Realtek Bluetooth Radio                        | 1         | 0.28%   |
| Realtek Bluetooth 5.1 Radio                    | 1         | 0.28%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0         | 1         | 0.28%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth     | 1         | 0.28%   |
| Intel Centrino Bluetooth Wireless Transceiver  | 1         | 0.28%   |
| Foxconn / Hon Hai Wireless_Device              | 1         | 0.28%   |
| Apple Bluetooth Host Controller                | 1         | 0.28%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| AMD                    | 346       | 86.72%  |
| Intel                  | 20        | 5.01%   |
| Nvidia                 | 8         | 2.01%   |
| Realtek Semiconductor  | 2         | 0.5%    |
| Logitech               | 2         | 0.5%    |
| Lenovo                 | 2         | 0.5%    |
| JMTek                  | 2         | 0.5%    |
| Generalplus Technology | 2         | 0.5%    |
| Corsair                | 2         | 0.5%    |
| C-Media Electronics    | 2         | 0.5%    |
| Blue Microphones       | 2         | 0.5%    |
| Tenx Technology        | 1         | 0.25%   |
| Sony                   | 1         | 0.25%   |
| Razer USA              | 1         | 0.25%   |
| Nreal                  | 1         | 0.25%   |
| MosArt Semiconductor   | 1         | 0.25%   |
| KTMicro                | 1         | 0.25%   |
| Kingston Technology    | 1         | 0.25%   |
| GN Netcom              | 1         | 0.25%   |
| Alesis                 | 1         | 0.25%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Rembrandt Radeon High Definition Audio Controller                      | 336       | 81.36%  |
| AMD Family 17h/19h HD Audio Controller                                     | 10        | 2.42%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 5         | 1.21%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4         | 0.97%   |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 0.97%   |
| Realtek Semiconductor USB Audio                                            | 2         | 0.48%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 0.48%   |
| Nvidia GA104 High Definition Audio Controller                              | 2         | 0.48%   |
| JMTek USB PnP Audio Device                                                 | 2         | 0.48%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 0.48%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 0.48%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 0.48%   |
| Generalplus Technology USB Audio Device                                    | 2         | 0.48%   |
| AMD Trinity HDMI Audio Controller                                          | 2         | 0.48%   |
| AMD FCH Azalia Controller                                                  | 2         | 0.48%   |
| Tenx Technology USB AUDIO                                                  | 1         | 0.24%   |
| Sony DualSense wireless controller (PS5)                                   | 1         | 0.24%   |
| Razer USA Razer Barracuda Pro 2.4                                          | 1         | 0.24%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 0.24%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.24%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.24%   |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 0.24%   |
| Nreal Air                                                                  | 1         | 0.24%   |
| MosArt Semiconductor MosArt USB Audio Device                               | 1         | 0.24%   |
| Logitech G935 Gaming Headset                                               | 1         | 0.24%   |
| Logitech G432 Gaming Headset                                               | 1         | 0.24%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                  | 1         | 0.24%   |
| Lenovo ThinkPad USB-C Dock Audio                                           | 1         | 0.24%   |
| KTMicro KT USB Audio                                                       | 1         | 0.24%   |
| Kingston Technology HyperX QuadCast                                        | 1         | 0.24%   |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 0.24%   |
| Intel Jasper Lake HD Audio                                                 | 1         | 0.24%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 0.24%   |
| Intel CM238 HD Audio Controller                                            | 1         | 0.24%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 0.24%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 0.24%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 1         | 0.24%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 0.24%   |
| GN Netcom Jabra Link 370                                                   | 1         | 0.24%   |
| Corsair HS70 Pro Wireless Gaming Headset                                   | 1         | 0.24%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Unknown             | 6         | 75%     |
| Samsung Electronics | 1         | 12.5%   |
| Micron Technology   | 1         | 12.5%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Unknown                                               | 6         | 75%     |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s | 1         | 12.5%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s  | 1         | 12.5%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| LPDDR5 | 6         | 85.71%  |
| DDR4   | 1         | 14.29%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 7         | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Notebooks | Percent |
|------|-----------|---------|
| 4096 | 6         | 85.71%  |
| 8192 | 1         | 14.29%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 4266  | 6         | 85.71%  |
| 3200  | 1         | 14.29%  |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| HP Laserjet CP1525nw | 1         | 100%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 210 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 5         | 14.29%  |
| Tripath Technology                     | 3         | 8.57%   |
| Realtek Semiconductor                  | 3         | 8.57%   |
| Microdia                               | 3         | 8.57%   |
| Logitech                               | 3         | 8.57%   |
| Apple                                  | 3         | 8.57%   |
| Acer                                   | 3         | 8.57%   |
| Quanta                                 | 2         | 5.71%   |
| Unknown                                | 1         | 2.86%   |
| Syntek                                 | 1         | 2.86%   |
| Suyin                                  | 1         | 2.86%   |
| SunplusIT                              | 1         | 2.86%   |
| Sunplus Innovation Technology          | 1         | 2.86%   |
| Samsung Electronics                    | 1         | 2.86%   |
| Luxvisions Innotech Limited            | 1         | 2.86%   |
| IMC Networks                           | 1         | 2.86%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.86%   |
| AVerMedia Technologies                 | 1         | 2.86%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Tripath USB Camera                                                            | 3         | 8.57%   |
| Chicony HD User Facing                                                        | 2         | 5.71%   |
| Apple iPhone 5/5C/5S/6/SE                                                     | 2         | 5.71%   |
| Acer Integrated Camera                                                        | 2         | 5.71%   |
| Unknown 720p HD Camera                                                        | 1         | 2.86%   |
| Syntek Integrated Camera                                                      | 1         | 2.86%   |
| Suyin HP Truevision HD                                                        | 1         | 2.86%   |
| SunplusIT CODi A05020 Webcam                                                  | 1         | 2.86%   |
| Sunplus Integrated_Webcam_FHD                                                 | 1         | 2.86%   |
| Samsung Galaxy series, misc. (MTP mode)                                       | 1         | 2.86%   |
| Realtek WEB CAMERA M9 Pro                                                     | 1         | 2.86%   |
| Realtek USB Camera                                                            | 1         | 2.86%   |
| Realtek Integrated_Webcam_HD                                                  | 1         | 2.86%   |
| Quanta VGA WebCam                                                             | 1         | 2.86%   |
| Quanta HP Wide Vision HD Camera                                               | 1         | 2.86%   |
| Microdia Webcam Vitade AF                                                     | 1         | 2.86%   |
| Microdia Integrated_Webcam_HD                                                 | 1         | 2.86%   |
| Microdia Integrated Webcam HD                                                 | 1         | 2.86%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                           | 1         | 2.86%   |
| Logitech HD Webcam C615                                                       | 1         | 2.86%   |
| Logitech HD Pro Webcam C920                                                   | 1         | 2.86%   |
| Logitech CrystalCam                                                           | 1         | 2.86%   |
| IMC Networks USB2.0 HD UVC WebCam                                             | 1         | 2.86%   |
| Chicony Integrated Camera (1280x720@30)                                       | 1         | 2.86%   |
| Chicony Integrated Camera                                                     | 1         | 2.86%   |
| Chicony HP TrueVision HD Camera                                               | 1         | 2.86%   |
| Cheng Uei Precision Industry (Foxlink) SunplusIT INC. HP Truevision HD Webcam | 1         | 2.86%   |
| AVerMedia Live Streamer CAM 313                                               | 1         | 2.86%   |
| Apple FaceTime HD Camera                                                      | 1         | 2.86%   |
| Acer HD Webcam                                                                | 1         | 2.86%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 1         | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device | 1         | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| SCM Microsystems | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| SCM Microsystems SCR3500 A Contact Reader | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 348       | 94.82%  |
| 1     | 14        | 3.81%   |
| 2     | 5         | 1.36%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Multimedia controller | 9         | 39.13%  |
| Net/wireless          | 7         | 30.43%  |
| Graphics card         | 3         | 13.04%  |
| Storage/nvme          | 1         | 4.35%   |
| Modem                 | 1         | 4.35%   |
| Fingerprint reader    | 1         | 4.35%   |
| Chipcard              | 1         | 4.35%   |

