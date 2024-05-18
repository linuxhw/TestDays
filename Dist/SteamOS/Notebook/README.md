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

Total: 1911

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Valve         | Jupiter                     | [99879342f6](https://linux-hardware.org/?probe=99879342f6) | May 09, 2024 |
| Valve         | Jupiter                     | [18c9c24ecb](https://linux-hardware.org/?probe=18c9c24ecb) | May 09, 2024 |
| Valve         | Jupiter                     | [fadecff7cd](https://linux-hardware.org/?probe=fadecff7cd) | May 08, 2024 |
| Valve         | Jupiter                     | [c0eded1dbf](https://linux-hardware.org/?probe=c0eded1dbf) | May 08, 2024 |
| Valve         | Jupiter                     | [cdb467c650](https://linux-hardware.org/?probe=cdb467c650) | May 08, 2024 |
| Valve         | Galileo                     | [9b9caa6850](https://linux-hardware.org/?probe=9b9caa6850) | May 07, 2024 |
| Valve         | Galileo                     | [af20242820](https://linux-hardware.org/?probe=af20242820) | May 06, 2024 |
| Valve         | Jupiter                     | [9a90343d3e](https://linux-hardware.org/?probe=9a90343d3e) | May 06, 2024 |
| Valve         | Jupiter                     | [829ef0c2ba](https://linux-hardware.org/?probe=829ef0c2ba) | May 06, 2024 |
| Valve         | Jupiter                     | [728da6c7b1](https://linux-hardware.org/?probe=728da6c7b1) | May 05, 2024 |
| Valve         | Jupiter                     | [5f8e391778](https://linux-hardware.org/?probe=5f8e391778) | May 04, 2024 |
| Valve         | Jupiter                     | [9a03d01cbc](https://linux-hardware.org/?probe=9a03d01cbc) | May 03, 2024 |
| Valve         | Jupiter                     | [912546851a](https://linux-hardware.org/?probe=912546851a) | May 01, 2024 |
| Valve         | Galileo                     | [fc102d1c7f](https://linux-hardware.org/?probe=fc102d1c7f) | May 01, 2024 |
| Valve         | Jupiter                     | [5266501940](https://linux-hardware.org/?probe=5266501940) | Apr 30, 2024 |
| Valve         | Jupiter                     | [20eca8966f](https://linux-hardware.org/?probe=20eca8966f) | Apr 28, 2024 |
| Valve         | Jupiter                     | [4360127fcb](https://linux-hardware.org/?probe=4360127fcb) | Apr 28, 2024 |
| Valve         | Jupiter                     | [42fe2e9ed4](https://linux-hardware.org/?probe=42fe2e9ed4) | Apr 28, 2024 |
| Valve         | Jupiter                     | [db12022c45](https://linux-hardware.org/?probe=db12022c45) | Apr 27, 2024 |
| Valve         | Jupiter                     | [2b383bd91e](https://linux-hardware.org/?probe=2b383bd91e) | Apr 27, 2024 |
| Valve         | Jupiter                     | [7a58749308](https://linux-hardware.org/?probe=7a58749308) | Apr 27, 2024 |
| Valve         | Jupiter                     | [bca2851ff6](https://linux-hardware.org/?probe=bca2851ff6) | Apr 27, 2024 |
| Valve         | Jupiter                     | [93f380bf3e](https://linux-hardware.org/?probe=93f380bf3e) | Apr 27, 2024 |
| Valve         | Jupiter                     | [2c0ec8539f](https://linux-hardware.org/?probe=2c0ec8539f) | Apr 26, 2024 |
| Valve         | Jupiter                     | [49fd8e0c8f](https://linux-hardware.org/?probe=49fd8e0c8f) | Apr 26, 2024 |
| Valve         | Jupiter                     | [3b3674f61e](https://linux-hardware.org/?probe=3b3674f61e) | Apr 26, 2024 |
| Valve         | Jupiter                     | [5430bf31d1](https://linux-hardware.org/?probe=5430bf31d1) | Apr 26, 2024 |
| Valve         | Jupiter                     | [81ec451d66](https://linux-hardware.org/?probe=81ec451d66) | Apr 26, 2024 |
| Valve         | Jupiter                     | [4cad19c61a](https://linux-hardware.org/?probe=4cad19c61a) | Apr 25, 2024 |
| Valve         | Jupiter                     | [61762f3b53](https://linux-hardware.org/?probe=61762f3b53) | Apr 24, 2024 |
| Valve         | Jupiter                     | [8b69a30a9d](https://linux-hardware.org/?probe=8b69a30a9d) | Apr 23, 2024 |
| Valve         | Jupiter                     | [7c8a53ecb1](https://linux-hardware.org/?probe=7c8a53ecb1) | Apr 23, 2024 |
| Valve         | Jupiter                     | [53f25f4dba](https://linux-hardware.org/?probe=53f25f4dba) | Apr 22, 2024 |
| Valve         | Jupiter                     | [665861dbf9](https://linux-hardware.org/?probe=665861dbf9) | Apr 22, 2024 |
| Valve         | Galileo                     | [3baa035f72](https://linux-hardware.org/?probe=3baa035f72) | Apr 21, 2024 |
| Valve         | Jupiter                     | [bc9b5cbcc5](https://linux-hardware.org/?probe=bc9b5cbcc5) | Apr 20, 2024 |
| Valve         | Jupiter                     | [3d82c7c0ee](https://linux-hardware.org/?probe=3d82c7c0ee) | Apr 20, 2024 |
| Valve         | Jupiter                     | [8cbd37a2d2](https://linux-hardware.org/?probe=8cbd37a2d2) | Apr 19, 2024 |
| Valve         | Galileo                     | [c3c28433cd](https://linux-hardware.org/?probe=c3c28433cd) | Apr 19, 2024 |
| Valve         | Jupiter                     | [38ab9d1cca](https://linux-hardware.org/?probe=38ab9d1cca) | Apr 18, 2024 |
| Valve         | Jupiter                     | [46fe84935f](https://linux-hardware.org/?probe=46fe84935f) | Apr 18, 2024 |
| Valve         | Jupiter                     | [85092eabaa](https://linux-hardware.org/?probe=85092eabaa) | Apr 18, 2024 |
| Valve         | Jupiter                     | [541aacb1a1](https://linux-hardware.org/?probe=541aacb1a1) | Apr 17, 2024 |
| Valve         | Jupiter                     | [37f71f57a0](https://linux-hardware.org/?probe=37f71f57a0) | Apr 17, 2024 |
| Valve         | Jupiter                     | [04d302c0e5](https://linux-hardware.org/?probe=04d302c0e5) | Apr 16, 2024 |
| Valve         | Jupiter                     | [d5c75e66f1](https://linux-hardware.org/?probe=d5c75e66f1) | Apr 16, 2024 |
| Valve         | Jupiter                     | [7de67bf8c5](https://linux-hardware.org/?probe=7de67bf8c5) | Apr 16, 2024 |
| Valve         | Jupiter                     | [211106f4c1](https://linux-hardware.org/?probe=211106f4c1) | Apr 14, 2024 |
| Valve         | Jupiter                     | [0043fe12b0](https://linux-hardware.org/?probe=0043fe12b0) | Apr 13, 2024 |
| Valve         | Jupiter                     | [8b4172f55b](https://linux-hardware.org/?probe=8b4172f55b) | Apr 13, 2024 |
| Valve         | Jupiter                     | [64cab9101d](https://linux-hardware.org/?probe=64cab9101d) | Apr 12, 2024 |
| Valve         | Jupiter                     | [c5c95abb79](https://linux-hardware.org/?probe=c5c95abb79) | Apr 12, 2024 |
| Valve         | Jupiter                     | [5f44467298](https://linux-hardware.org/?probe=5f44467298) | Apr 11, 2024 |
| Valve         | Jupiter                     | [a75cf3dc0f](https://linux-hardware.org/?probe=a75cf3dc0f) | Apr 10, 2024 |
| Valve         | Jupiter                     | [6f2b093298](https://linux-hardware.org/?probe=6f2b093298) | Apr 09, 2024 |
| Valve         | Jupiter                     | [a80d8086f4](https://linux-hardware.org/?probe=a80d8086f4) | Apr 09, 2024 |
| Valve         | Galileo                     | [942bd1a16a](https://linux-hardware.org/?probe=942bd1a16a) | Apr 08, 2024 |
| Valve         | Galileo                     | [9ce0365088](https://linux-hardware.org/?probe=9ce0365088) | Apr 08, 2024 |
| Valve         | Jupiter                     | [36089b579d](https://linux-hardware.org/?probe=36089b579d) | Apr 07, 2024 |
| Valve         | Jupiter                     | [8cd7c7653a](https://linux-hardware.org/?probe=8cd7c7653a) | Apr 07, 2024 |
| Valve         | Jupiter                     | [6fb589032f](https://linux-hardware.org/?probe=6fb589032f) | Apr 07, 2024 |
| Valve         | Jupiter                     | [ca414b0905](https://linux-hardware.org/?probe=ca414b0905) | Apr 07, 2024 |
| Valve         | Jupiter                     | [80b0985ecd](https://linux-hardware.org/?probe=80b0985ecd) | Apr 07, 2024 |
| Valve         | Jupiter                     | [1cd9cc4807](https://linux-hardware.org/?probe=1cd9cc4807) | Apr 07, 2024 |
| Unknown       | X570 Phantom Gaming-ITX/... | [d0447bf92e](https://linux-hardware.org/?probe=d0447bf92e) | Apr 06, 2024 |
| Valve         | Jupiter                     | [70c2145a5e](https://linux-hardware.org/?probe=70c2145a5e) | Apr 06, 2024 |
| Valve         | Jupiter                     | [2e89c99bcd](https://linux-hardware.org/?probe=2e89c99bcd) | Apr 06, 2024 |
| Valve         | Jupiter                     | [bf17940c69](https://linux-hardware.org/?probe=bf17940c69) | Apr 06, 2024 |
| Valve         | Jupiter                     | [04c5de9351](https://linux-hardware.org/?probe=04c5de9351) | Apr 05, 2024 |
| Valve         | Jupiter                     | [a981f41f5c](https://linux-hardware.org/?probe=a981f41f5c) | Apr 05, 2024 |
| Valve         | Jupiter                     | [806dd327bf](https://linux-hardware.org/?probe=806dd327bf) | Apr 05, 2024 |
| Valve         | Jupiter                     | [e7ac70b5b9](https://linux-hardware.org/?probe=e7ac70b5b9) | Apr 04, 2024 |
| Valve         | Galileo                     | [968d4e6589](https://linux-hardware.org/?probe=968d4e6589) | Apr 03, 2024 |
| Valve         | Jupiter                     | [450a01c984](https://linux-hardware.org/?probe=450a01c984) | Apr 03, 2024 |
| Valve         | Jupiter                     | [a9bb9ace67](https://linux-hardware.org/?probe=a9bb9ace67) | Apr 03, 2024 |
| Valve         | Galileo                     | [0e73d5c7db](https://linux-hardware.org/?probe=0e73d5c7db) | Apr 03, 2024 |
| Valve         | Jupiter                     | [3f58323ccb](https://linux-hardware.org/?probe=3f58323ccb) | Apr 02, 2024 |
| Valve         | Jupiter                     | [780ff142f3](https://linux-hardware.org/?probe=780ff142f3) | Apr 01, 2024 |
| Valve         | Jupiter                     | [83291b94be](https://linux-hardware.org/?probe=83291b94be) | Mar 31, 2024 |
| Valve         | Jupiter                     | [16cef49100](https://linux-hardware.org/?probe=16cef49100) | Mar 31, 2024 |
| Valve         | Galileo                     | [f1d07303d3](https://linux-hardware.org/?probe=f1d07303d3) | Mar 30, 2024 |
| Unknown       | X570 Phantom Gaming-ITX/... | [1fb1798295](https://linux-hardware.org/?probe=1fb1798295) | Mar 30, 2024 |
| Valve         | Jupiter                     | [65e56cbf7d](https://linux-hardware.org/?probe=65e56cbf7d) | Mar 30, 2024 |
| Valve         | Jupiter                     | [1a14e1128b](https://linux-hardware.org/?probe=1a14e1128b) | Mar 29, 2024 |
| Valve         | Galileo                     | [cf3139b931](https://linux-hardware.org/?probe=cf3139b931) | Mar 29, 2024 |
| Valve         | Jupiter                     | [b2242c7939](https://linux-hardware.org/?probe=b2242c7939) | Mar 28, 2024 |
| Valve         | Jupiter                     | [735b182e71](https://linux-hardware.org/?probe=735b182e71) | Mar 27, 2024 |
| Valve         | Jupiter                     | [767300c112](https://linux-hardware.org/?probe=767300c112) | Mar 27, 2024 |
| Valve         | Jupiter                     | [6ded41cc7e](https://linux-hardware.org/?probe=6ded41cc7e) | Mar 26, 2024 |
| Valve         | Jupiter                     | [99fec85b50](https://linux-hardware.org/?probe=99fec85b50) | Mar 25, 2024 |
| Valve         | Jupiter                     | [28b02c08d8](https://linux-hardware.org/?probe=28b02c08d8) | Mar 25, 2024 |
| Valve         | Jupiter                     | [8c039323e6](https://linux-hardware.org/?probe=8c039323e6) | Mar 24, 2024 |
| Valve         | Jupiter                     | [4342049244](https://linux-hardware.org/?probe=4342049244) | Mar 24, 2024 |
| Valve         | Jupiter                     | [b61c5a739b](https://linux-hardware.org/?probe=b61c5a739b) | Mar 24, 2024 |
| Valve         | Galileo                     | [edb753ac8d](https://linux-hardware.org/?probe=edb753ac8d) | Mar 24, 2024 |
| Valve         | Jupiter                     | [d2155ef727](https://linux-hardware.org/?probe=d2155ef727) | Mar 23, 2024 |
| Valve         | Jupiter                     | [a4d5199429](https://linux-hardware.org/?probe=a4d5199429) | Mar 23, 2024 |
| Valve         | Galileo                     | [5e7e2c39df](https://linux-hardware.org/?probe=5e7e2c39df) | Mar 22, 2024 |
| Valve         | Galileo                     | [14e646cf21](https://linux-hardware.org/?probe=14e646cf21) | Mar 22, 2024 |
| Valve         | Jupiter                     | [4de44d6cdd](https://linux-hardware.org/?probe=4de44d6cdd) | Mar 22, 2024 |
| Valve         | Jupiter                     | [3984f68c68](https://linux-hardware.org/?probe=3984f68c68) | Mar 22, 2024 |
| Valve         | Galileo                     | [cd0fb4513f](https://linux-hardware.org/?probe=cd0fb4513f) | Mar 21, 2024 |
| Valve         | Jupiter                     | [799336fb6f](https://linux-hardware.org/?probe=799336fb6f) | Mar 21, 2024 |
| Valve         | Galileo                     | [21dd2b032b](https://linux-hardware.org/?probe=21dd2b032b) | Mar 20, 2024 |
| Valve         | Jupiter                     | [00d8e6290f](https://linux-hardware.org/?probe=00d8e6290f) | Mar 20, 2024 |
| Valve         | Galileo                     | [f27bde39ca](https://linux-hardware.org/?probe=f27bde39ca) | Mar 20, 2024 |
| Valve         | Jupiter                     | [fdd201eb62](https://linux-hardware.org/?probe=fdd201eb62) | Mar 20, 2024 |
| Valve         | Jupiter                     | [5c3d9869b4](https://linux-hardware.org/?probe=5c3d9869b4) | Mar 20, 2024 |
| Valve         | Jupiter                     | [ff5812e646](https://linux-hardware.org/?probe=ff5812e646) | Mar 20, 2024 |
| Valve         | Galileo                     | [0bbc97ddea](https://linux-hardware.org/?probe=0bbc97ddea) | Mar 19, 2024 |
| Valve         | Galileo                     | [085b9b9244](https://linux-hardware.org/?probe=085b9b9244) | Mar 19, 2024 |
| Valve         | Jupiter                     | [869100ba40](https://linux-hardware.org/?probe=869100ba40) | Mar 19, 2024 |
| Valve         | Jupiter                     | [0f1ba4ef31](https://linux-hardware.org/?probe=0f1ba4ef31) | Mar 18, 2024 |
| Valve         | Jupiter                     | [4d0b384f4d](https://linux-hardware.org/?probe=4d0b384f4d) | Mar 17, 2024 |
| Valve         | Jupiter                     | [ebb293f4f2](https://linux-hardware.org/?probe=ebb293f4f2) | Mar 16, 2024 |
| Valve         | Galileo                     | [1b0c67a809](https://linux-hardware.org/?probe=1b0c67a809) | Mar 16, 2024 |
| Valve         | Galileo                     | [94545cd73f](https://linux-hardware.org/?probe=94545cd73f) | Mar 16, 2024 |
| Valve         | Jupiter                     | [5592371b6d](https://linux-hardware.org/?probe=5592371b6d) | Mar 15, 2024 |
| Valve         | Jupiter                     | [ed1ff78792](https://linux-hardware.org/?probe=ed1ff78792) | Mar 14, 2024 |
| Valve         | Jupiter                     | [930838ef76](https://linux-hardware.org/?probe=930838ef76) | Mar 14, 2024 |
| Valve         | Galileo                     | [ce3a2505b6](https://linux-hardware.org/?probe=ce3a2505b6) | Mar 14, 2024 |
| Valve         | Jupiter                     | [c3514740e2](https://linux-hardware.org/?probe=c3514740e2) | Mar 14, 2024 |
| Valve         | Jupiter                     | [14ec218ad2](https://linux-hardware.org/?probe=14ec218ad2) | Mar 14, 2024 |
| Valve         | Jupiter                     | [850f86c442](https://linux-hardware.org/?probe=850f86c442) | Mar 13, 2024 |
| Valve         | Galileo                     | [a55314d630](https://linux-hardware.org/?probe=a55314d630) | Mar 13, 2024 |
| Valve         | Jupiter                     | [14ed8497d8](https://linux-hardware.org/?probe=14ed8497d8) | Mar 12, 2024 |
| Valve         | Galileo                     | [fd1ccf71a2](https://linux-hardware.org/?probe=fd1ccf71a2) | Mar 12, 2024 |
| Valve         | Jupiter                     | [19c2d88d48](https://linux-hardware.org/?probe=19c2d88d48) | Mar 11, 2024 |
| Valve         | Jupiter                     | [ee85c6e7e9](https://linux-hardware.org/?probe=ee85c6e7e9) | Mar 11, 2024 |
| Valve         | Jupiter                     | [0a31a36586](https://linux-hardware.org/?probe=0a31a36586) | Mar 10, 2024 |
| Valve         | Galileo                     | [d816b83ec2](https://linux-hardware.org/?probe=d816b83ec2) | Mar 10, 2024 |
| Gigabyte      | B650 GAMING X AX            | [3ee6829e26](https://linux-hardware.org/?probe=3ee6829e26) | Mar 10, 2024 |
| Valve         | Jupiter                     | [af7786fb34](https://linux-hardware.org/?probe=af7786fb34) | Mar 10, 2024 |
| Valve         | Jupiter                     | [d38b45b5d5](https://linux-hardware.org/?probe=d38b45b5d5) | Mar 10, 2024 |
| Valve         | Jupiter                     | [f8cd449a7b](https://linux-hardware.org/?probe=f8cd449a7b) | Mar 09, 2024 |
| Valve         | Galileo                     | [1b9852cbf9](https://linux-hardware.org/?probe=1b9852cbf9) | Mar 09, 2024 |
| Valve         | Jupiter                     | [b69d18360e](https://linux-hardware.org/?probe=b69d18360e) | Mar 08, 2024 |
| Valve         | Galileo                     | [b2d15e9047](https://linux-hardware.org/?probe=b2d15e9047) | Mar 08, 2024 |
| Valve         | Jupiter                     | [035ae9a246](https://linux-hardware.org/?probe=035ae9a246) | Mar 08, 2024 |
| Valve         | Galileo                     | [7ae1784e3b](https://linux-hardware.org/?probe=7ae1784e3b) | Mar 06, 2024 |
| Valve         | Jupiter                     | [677470b88d](https://linux-hardware.org/?probe=677470b88d) | Mar 06, 2024 |
| Valve         | Jupiter                     | [1af9e94fb7](https://linux-hardware.org/?probe=1af9e94fb7) | Mar 05, 2024 |
| Valve         | Galileo                     | [88afcecdbe](https://linux-hardware.org/?probe=88afcecdbe) | Mar 05, 2024 |
| Valve         | Jupiter                     | [f1068af6ca](https://linux-hardware.org/?probe=f1068af6ca) | Mar 03, 2024 |
| Valve         | Jupiter                     | [3937ff45d4](https://linux-hardware.org/?probe=3937ff45d4) | Mar 03, 2024 |
| Valve         | Galileo                     | [fd78eb29e4](https://linux-hardware.org/?probe=fd78eb29e4) | Mar 02, 2024 |
| Valve         | Jupiter                     | [eecf1f7620](https://linux-hardware.org/?probe=eecf1f7620) | Mar 02, 2024 |
| Valve         | Jupiter                     | [8a19c9b077](https://linux-hardware.org/?probe=8a19c9b077) | Mar 02, 2024 |
| Valve         | Jupiter                     | [b455b30583](https://linux-hardware.org/?probe=b455b30583) | Mar 02, 2024 |
| Valve         | Jupiter                     | [8b06ba52f8](https://linux-hardware.org/?probe=8b06ba52f8) | Mar 02, 2024 |
| Valve         | Jupiter                     | [b2228e6857](https://linux-hardware.org/?probe=b2228e6857) | Mar 02, 2024 |
| Valve         | Jupiter                     | [febb7c9dec](https://linux-hardware.org/?probe=febb7c9dec) | Mar 01, 2024 |
| Valve         | Jupiter                     | [610fa788bb](https://linux-hardware.org/?probe=610fa788bb) | Mar 01, 2024 |
| Valve         | Jupiter                     | [a3062daa4e](https://linux-hardware.org/?probe=a3062daa4e) | Mar 01, 2024 |
| Valve         | Jupiter                     | [25aac8bc03](https://linux-hardware.org/?probe=25aac8bc03) | Mar 01, 2024 |
| Valve         | Galileo                     | [63cd4fe821](https://linux-hardware.org/?probe=63cd4fe821) | Feb 29, 2024 |
| Valve         | Jupiter                     | [30c94fd159](https://linux-hardware.org/?probe=30c94fd159) | Feb 29, 2024 |
| Valve         | Jupiter                     | [2f381a7a43](https://linux-hardware.org/?probe=2f381a7a43) | Feb 29, 2024 |
| Valve         | Jupiter                     | [ecfc325c0f](https://linux-hardware.org/?probe=ecfc325c0f) | Feb 29, 2024 |
| Valve         | Galileo                     | [341298d11f](https://linux-hardware.org/?probe=341298d11f) | Feb 28, 2024 |
| Valve         | Galileo                     | [d8f5007f65](https://linux-hardware.org/?probe=d8f5007f65) | Feb 27, 2024 |
| Valve         | Galileo                     | [10c68c0f8b](https://linux-hardware.org/?probe=10c68c0f8b) | Feb 27, 2024 |
| Valve         | Galileo                     | [1eecc5bac8](https://linux-hardware.org/?probe=1eecc5bac8) | Feb 27, 2024 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [14d015f400](https://linux-hardware.org/?probe=14d015f400) | Feb 26, 2024 |
| Valve         | Galileo                     | [de70e171dc](https://linux-hardware.org/?probe=de70e171dc) | Feb 25, 2024 |
| Valve         | Jupiter                     | [a559534ad7](https://linux-hardware.org/?probe=a559534ad7) | Feb 25, 2024 |
| Valve         | Jupiter                     | [ac52b6fbea](https://linux-hardware.org/?probe=ac52b6fbea) | Feb 25, 2024 |
| Valve         | Jupiter                     | [4da56c1b32](https://linux-hardware.org/?probe=4da56c1b32) | Feb 24, 2024 |
| Valve         | Galileo                     | [222802e961](https://linux-hardware.org/?probe=222802e961) | Feb 24, 2024 |
| Valve         | Jupiter                     | [c54b01f190](https://linux-hardware.org/?probe=c54b01f190) | Feb 23, 2024 |
| Valve         | Jupiter                     | [723e90e0ad](https://linux-hardware.org/?probe=723e90e0ad) | Feb 23, 2024 |
| Valve         | Jupiter                     | [17b0edd6f8](https://linux-hardware.org/?probe=17b0edd6f8) | Feb 23, 2024 |
| Valve         | Galileo                     | [f4c12237df](https://linux-hardware.org/?probe=f4c12237df) | Feb 22, 2024 |
| Valve         | Jupiter                     | [4a80cf0f13](https://linux-hardware.org/?probe=4a80cf0f13) | Feb 22, 2024 |
| Valve         | Jupiter                     | [fa56f61268](https://linux-hardware.org/?probe=fa56f61268) | Feb 21, 2024 |
| Valve         | Jupiter                     | [e0565441ff](https://linux-hardware.org/?probe=e0565441ff) | Feb 21, 2024 |
| Valve         | Jupiter                     | [cdcf85f04c](https://linux-hardware.org/?probe=cdcf85f04c) | Feb 21, 2024 |
| Valve         | Jupiter                     | [e493063cc7](https://linux-hardware.org/?probe=e493063cc7) | Feb 21, 2024 |
| Valve         | Jupiter                     | [61c3ec125c](https://linux-hardware.org/?probe=61c3ec125c) | Feb 20, 2024 |
| HP            | Laptop 14-fq0xxx            | [852d20d6f7](https://linux-hardware.org/?probe=852d20d6f7) | Feb 20, 2024 |
| HP            | Laptop 15s-eq2xxx           | [63c3d36c4b](https://linux-hardware.org/?probe=63c3d36c4b) | Feb 19, 2024 |
| Valve         | Jupiter                     | [1e4fe945b9](https://linux-hardware.org/?probe=1e4fe945b9) | Feb 19, 2024 |
| Valve         | Jupiter                     | [259bfa3fd6](https://linux-hardware.org/?probe=259bfa3fd6) | Feb 18, 2024 |
| Valve         | Jupiter                     | [fc900c86f1](https://linux-hardware.org/?probe=fc900c86f1) | Feb 18, 2024 |
| Valve         | Galileo                     | [aabc3c448c](https://linux-hardware.org/?probe=aabc3c448c) | Feb 18, 2024 |
| Valve         | Jupiter                     | [1fea584115](https://linux-hardware.org/?probe=1fea584115) | Feb 17, 2024 |
| Valve         | Jupiter                     | [d575568ecc](https://linux-hardware.org/?probe=d575568ecc) | Feb 17, 2024 |
| Valve         | Jupiter                     | [51257484fe](https://linux-hardware.org/?probe=51257484fe) | Feb 17, 2024 |
| Valve         | Jupiter                     | [51f10c1fc1](https://linux-hardware.org/?probe=51f10c1fc1) | Feb 16, 2024 |
| Valve         | Jupiter                     | [db182bfb66](https://linux-hardware.org/?probe=db182bfb66) | Feb 16, 2024 |
| Valve         | Galileo                     | [e8ff67fb4c](https://linux-hardware.org/?probe=e8ff67fb4c) | Feb 16, 2024 |
| Valve         | Jupiter                     | [4014dc3070](https://linux-hardware.org/?probe=4014dc3070) | Feb 15, 2024 |
| Valve         | Jupiter                     | [3cc9a72587](https://linux-hardware.org/?probe=3cc9a72587) | Feb 15, 2024 |
| Valve         | Jupiter                     | [71c7cf074b](https://linux-hardware.org/?probe=71c7cf074b) | Feb 12, 2024 |
| Valve         | Jupiter                     | [4bfb818f2f](https://linux-hardware.org/?probe=4bfb818f2f) | Feb 12, 2024 |
| Valve         | Jupiter                     | [ffaf97c4b5](https://linux-hardware.org/?probe=ffaf97c4b5) | Feb 12, 2024 |
| Valve         | Jupiter                     | [b87bcc0c74](https://linux-hardware.org/?probe=b87bcc0c74) | Feb 12, 2024 |
| Valve         | Galileo                     | [19586b27b1](https://linux-hardware.org/?probe=19586b27b1) | Feb 11, 2024 |
| Valve         | Jupiter                     | [715d0ca807](https://linux-hardware.org/?probe=715d0ca807) | Feb 10, 2024 |
| Valve         | Jupiter                     | [43e2aaa664](https://linux-hardware.org/?probe=43e2aaa664) | Feb 10, 2024 |
| Valve         | Jupiter                     | [fe45dc1492](https://linux-hardware.org/?probe=fe45dc1492) | Feb 10, 2024 |
| Valve         | Jupiter                     | [7753a449fe](https://linux-hardware.org/?probe=7753a449fe) | Feb 09, 2024 |
| Valve         | Jupiter                     | [b2758be2c2](https://linux-hardware.org/?probe=b2758be2c2) | Feb 08, 2024 |
| Valve         | Jupiter                     | [e2f2d83b90](https://linux-hardware.org/?probe=e2f2d83b90) | Feb 08, 2024 |
| Valve         | Galileo                     | [11d7631320](https://linux-hardware.org/?probe=11d7631320) | Feb 08, 2024 |
| Valve         | Jupiter                     | [85375b8312](https://linux-hardware.org/?probe=85375b8312) | Feb 07, 2024 |
| Valve         | Jupiter                     | [da9c1d2875](https://linux-hardware.org/?probe=da9c1d2875) | Feb 07, 2024 |
| Valve         | Jupiter                     | [624ed1cc79](https://linux-hardware.org/?probe=624ed1cc79) | Feb 07, 2024 |
| Valve         | Jupiter                     | [f01021ead3](https://linux-hardware.org/?probe=f01021ead3) | Feb 07, 2024 |
| Valve         | Galileo                     | [2ec00ae541](https://linux-hardware.org/?probe=2ec00ae541) | Feb 06, 2024 |
| HP            | Laptop 15s-eq2xxx           | [9b1ea3c33b](https://linux-hardware.org/?probe=9b1ea3c33b) | Feb 06, 2024 |
| Valve         | Jupiter                     | [aed70e45ab](https://linux-hardware.org/?probe=aed70e45ab) | Feb 06, 2024 |
| Valve         | Jupiter                     | [aa0a520e23](https://linux-hardware.org/?probe=aa0a520e23) | Feb 06, 2024 |
| Valve         | Jupiter                     | [1564fac4f6](https://linux-hardware.org/?probe=1564fac4f6) | Feb 04, 2024 |
| Dell          | Precision M6700             | [c35af6db34](https://linux-hardware.org/?probe=c35af6db34) | Feb 04, 2024 |
| Valve         | Jupiter                     | [ae2cb6e513](https://linux-hardware.org/?probe=ae2cb6e513) | Feb 04, 2024 |
| Valve         | Jupiter                     | [a9f76ff5b1](https://linux-hardware.org/?probe=a9f76ff5b1) | Feb 04, 2024 |
| Valve         | Jupiter                     | [6c300e05f5](https://linux-hardware.org/?probe=6c300e05f5) | Feb 03, 2024 |
| Valve         | Jupiter                     | [5823a5e361](https://linux-hardware.org/?probe=5823a5e361) | Feb 03, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [f0f4ead532](https://linux-hardware.org/?probe=f0f4ead532) | Feb 03, 2024 |
| Valve         | Jupiter                     | [658987799e](https://linux-hardware.org/?probe=658987799e) | Feb 03, 2024 |
| Valve         | Jupiter                     | [ff59f7877a](https://linux-hardware.org/?probe=ff59f7877a) | Feb 02, 2024 |
| Valve         | Galileo                     | [3b44d4da2f](https://linux-hardware.org/?probe=3b44d4da2f) | Feb 02, 2024 |
| Valve         | Galileo                     | [aebc4c73ad](https://linux-hardware.org/?probe=aebc4c73ad) | Feb 01, 2024 |
| Valve         | Jupiter                     | [ab5f4937c1](https://linux-hardware.org/?probe=ab5f4937c1) | Feb 01, 2024 |
| Valve         | Jupiter                     | [238b20b912](https://linux-hardware.org/?probe=238b20b912) | Feb 01, 2024 |
| Valve         | Jupiter                     | [f7647969b5](https://linux-hardware.org/?probe=f7647969b5) | Feb 01, 2024 |
| Valve         | Galileo                     | [c286128e50](https://linux-hardware.org/?probe=c286128e50) | Feb 01, 2024 |
| Valve         | Jupiter                     | [282271ee83](https://linux-hardware.org/?probe=282271ee83) | Jan 31, 2024 |
| Valve         | Jupiter                     | [574ab05eb4](https://linux-hardware.org/?probe=574ab05eb4) | Jan 31, 2024 |
| Valve         | Jupiter                     | [1cdbb473c3](https://linux-hardware.org/?probe=1cdbb473c3) | Jan 30, 2024 |
| Valve         | Jupiter                     | [0db5dcce8b](https://linux-hardware.org/?probe=0db5dcce8b) | Jan 30, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [27229e7136](https://linux-hardware.org/?probe=27229e7136) | Jan 30, 2024 |
| Valve         | Jupiter                     | [e9a7ccf69a](https://linux-hardware.org/?probe=e9a7ccf69a) | Jan 29, 2024 |
| Valve         | Jupiter                     | [f3af706ee0](https://linux-hardware.org/?probe=f3af706ee0) | Jan 29, 2024 |
| Valve         | Jupiter                     | [71066ddcbf](https://linux-hardware.org/?probe=71066ddcbf) | Jan 29, 2024 |
| Valve         | Jupiter                     | [72f7a8c4e7](https://linux-hardware.org/?probe=72f7a8c4e7) | Jan 29, 2024 |
| Valve         | Jupiter                     | [d12b2f3bf3](https://linux-hardware.org/?probe=d12b2f3bf3) | Jan 28, 2024 |
| Valve         | Jupiter                     | [7c87eec092](https://linux-hardware.org/?probe=7c87eec092) | Jan 27, 2024 |
| Valve         | Jupiter                     | [7ff59e8f3a](https://linux-hardware.org/?probe=7ff59e8f3a) | Jan 27, 2024 |
| Valve         | Jupiter                     | [8ae43fed66](https://linux-hardware.org/?probe=8ae43fed66) | Jan 27, 2024 |
| Valve         | Jupiter                     | [3e0bcfc51d](https://linux-hardware.org/?probe=3e0bcfc51d) | Jan 26, 2024 |
| Valve         | Jupiter                     | [b69df41d1b](https://linux-hardware.org/?probe=b69df41d1b) | Jan 26, 2024 |
| Valve         | Jupiter                     | [ad91e418c3](https://linux-hardware.org/?probe=ad91e418c3) | Jan 25, 2024 |
| Valve         | Galileo                     | [b9012d8d8c](https://linux-hardware.org/?probe=b9012d8d8c) | Jan 25, 2024 |
| Valve         | Galileo                     | [4d738e6ad2](https://linux-hardware.org/?probe=4d738e6ad2) | Jan 25, 2024 |
| Valve         | Jupiter                     | [56666176ea](https://linux-hardware.org/?probe=56666176ea) | Jan 23, 2024 |
| Valve         | Galileo                     | [55087a9f6f](https://linux-hardware.org/?probe=55087a9f6f) | Jan 23, 2024 |
| Valve         | Jupiter                     | [83f771db1c](https://linux-hardware.org/?probe=83f771db1c) | Jan 23, 2024 |
| Valve         | Jupiter                     | [9ac816140b](https://linux-hardware.org/?probe=9ac816140b) | Jan 23, 2024 |
| Valve         | Galileo                     | [f819a94a66](https://linux-hardware.org/?probe=f819a94a66) | Jan 22, 2024 |
| Valve         | Jupiter                     | [d2a4f1790a](https://linux-hardware.org/?probe=d2a4f1790a) | Jan 22, 2024 |
| Medion        | Deputy P50                  | [57081b7e90](https://linux-hardware.org/?probe=57081b7e90) | Jan 22, 2024 |
| AMI           | Cherry Trail CR             | [873a9b67e1](https://linux-hardware.org/?probe=873a9b67e1) | Jan 22, 2024 |
| Valve         | Jupiter                     | [03734c93e6](https://linux-hardware.org/?probe=03734c93e6) | Jan 21, 2024 |
| Valve         | Jupiter                     | [9e62126d95](https://linux-hardware.org/?probe=9e62126d95) | Jan 21, 2024 |
| Valve         | Jupiter                     | [4d7a6b2c71](https://linux-hardware.org/?probe=4d7a6b2c71) | Jan 21, 2024 |
| Valve         | Jupiter                     | [890477dbac](https://linux-hardware.org/?probe=890477dbac) | Jan 21, 2024 |
| Valve         | Jupiter                     | [f0e5f47e6b](https://linux-hardware.org/?probe=f0e5f47e6b) | Jan 20, 2024 |
| Valve         | Jupiter                     | [e65dcac4a9](https://linux-hardware.org/?probe=e65dcac4a9) | Jan 20, 2024 |
| Valve         | Jupiter                     | [4dd4fc3a4c](https://linux-hardware.org/?probe=4dd4fc3a4c) | Jan 19, 2024 |
| Valve         | Jupiter                     | [a64bc13a23](https://linux-hardware.org/?probe=a64bc13a23) | Jan 19, 2024 |
| Valve         | Jupiter                     | [3fac9b5786](https://linux-hardware.org/?probe=3fac9b5786) | Jan 18, 2024 |
| Valve         | Jupiter                     | [d9666cbb26](https://linux-hardware.org/?probe=d9666cbb26) | Jan 18, 2024 |
| Valve         | Galileo                     | [e11c272188](https://linux-hardware.org/?probe=e11c272188) | Jan 16, 2024 |
| Valve         | Jupiter                     | [1ebf344a00](https://linux-hardware.org/?probe=1ebf344a00) | Jan 16, 2024 |
| Valve         | Jupiter                     | [df98e57037](https://linux-hardware.org/?probe=df98e57037) | Jan 15, 2024 |
| Valve         | Galileo                     | [c9db96cd08](https://linux-hardware.org/?probe=c9db96cd08) | Jan 15, 2024 |
| Valve         | Jupiter                     | [ff4dff4d2f](https://linux-hardware.org/?probe=ff4dff4d2f) | Jan 15, 2024 |
| Valve         | Jupiter                     | [5a872c599e](https://linux-hardware.org/?probe=5a872c599e) | Jan 15, 2024 |
| Valve         | Jupiter                     | [354c998efb](https://linux-hardware.org/?probe=354c998efb) | Jan 15, 2024 |
| Valve         | Galileo                     | [5d92a542e4](https://linux-hardware.org/?probe=5d92a542e4) | Jan 14, 2024 |
| Valve         | Galileo                     | [48d337c0f3](https://linux-hardware.org/?probe=48d337c0f3) | Jan 14, 2024 |
| Valve         | Jupiter                     | [51d79bc7e2](https://linux-hardware.org/?probe=51d79bc7e2) | Jan 14, 2024 |
| Valve         | Jupiter                     | [4b71896940](https://linux-hardware.org/?probe=4b71896940) | Jan 13, 2024 |
| Valve         | Galileo                     | [48f9b2ac8a](https://linux-hardware.org/?probe=48f9b2ac8a) | Jan 13, 2024 |
| Valve         | Jupiter                     | [07ee2b0014](https://linux-hardware.org/?probe=07ee2b0014) | Jan 12, 2024 |
| Valve         | Jupiter                     | [32a7347cc6](https://linux-hardware.org/?probe=32a7347cc6) | Jan 12, 2024 |
| Valve         | Galileo                     | [8e6568f88e](https://linux-hardware.org/?probe=8e6568f88e) | Jan 12, 2024 |
| Valve         | Jupiter                     | [168d28210d](https://linux-hardware.org/?probe=168d28210d) | Jan 12, 2024 |
| Valve         | Jupiter                     | [96faa10437](https://linux-hardware.org/?probe=96faa10437) | Jan 11, 2024 |
| Valve         | Jupiter                     | [ab13227de0](https://linux-hardware.org/?probe=ab13227de0) | Jan 10, 2024 |
| Valve         | Jupiter                     | [bc2f7eea4c](https://linux-hardware.org/?probe=bc2f7eea4c) | Jan 10, 2024 |
| Valve         | Jupiter                     | [941126dfcc](https://linux-hardware.org/?probe=941126dfcc) | Jan 10, 2024 |
| Valve         | Jupiter                     | [62bf989a58](https://linux-hardware.org/?probe=62bf989a58) | Jan 09, 2024 |
| Valve         | Jupiter                     | [3462a5ad9f](https://linux-hardware.org/?probe=3462a5ad9f) | Jan 09, 2024 |
| Valve         | Jupiter                     | [400f14241d](https://linux-hardware.org/?probe=400f14241d) | Jan 09, 2024 |
| Valve         | Jupiter                     | [eac99b5d0a](https://linux-hardware.org/?probe=eac99b5d0a) | Jan 09, 2024 |
| Valve         | Galileo                     | [4032bdfc39](https://linux-hardware.org/?probe=4032bdfc39) | Jan 08, 2024 |
| Valve         | Jupiter                     | [bddd9671c1](https://linux-hardware.org/?probe=bddd9671c1) | Jan 08, 2024 |
| Valve         | Galileo                     | [ef6307532c](https://linux-hardware.org/?probe=ef6307532c) | Jan 08, 2024 |
| Valve         | Galileo                     | [e71ef9c36d](https://linux-hardware.org/?probe=e71ef9c36d) | Jan 07, 2024 |
| Valve         | Jupiter                     | [4ee3e89964](https://linux-hardware.org/?probe=4ee3e89964) | Jan 07, 2024 |
| Valve         | Jupiter                     | [67ec614b0e](https://linux-hardware.org/?probe=67ec614b0e) | Jan 07, 2024 |
| Valve         | Jupiter                     | [1d07e80599](https://linux-hardware.org/?probe=1d07e80599) | Jan 07, 2024 |
| Valve         | Galileo                     | [7365f742df](https://linux-hardware.org/?probe=7365f742df) | Jan 06, 2024 |
| Valve         | Jupiter                     | [da56767d30](https://linux-hardware.org/?probe=da56767d30) | Jan 05, 2024 |
| Valve         | Jupiter                     | [561c912554](https://linux-hardware.org/?probe=561c912554) | Jan 05, 2024 |
| Valve         | Jupiter                     | [3d47c0ba48](https://linux-hardware.org/?probe=3d47c0ba48) | Jan 04, 2024 |
| Valve         | Jupiter                     | [2ccc42584e](https://linux-hardware.org/?probe=2ccc42584e) | Jan 04, 2024 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [c23d61cde7](https://linux-hardware.org/?probe=c23d61cde7) | Jan 04, 2024 |
| Valve         | Jupiter                     | [2942273257](https://linux-hardware.org/?probe=2942273257) | Jan 04, 2024 |
| Valve         | Jupiter                     | [348b004789](https://linux-hardware.org/?probe=348b004789) | Jan 04, 2024 |
| Valve         | Jupiter                     | [9d4ea07ea6](https://linux-hardware.org/?probe=9d4ea07ea6) | Jan 03, 2024 |
| Valve         | Galileo                     | [1e16b6eb69](https://linux-hardware.org/?probe=1e16b6eb69) | Jan 03, 2024 |
| Valve         | Jupiter                     | [b3ada6c407](https://linux-hardware.org/?probe=b3ada6c407) | Jan 02, 2024 |
| HP            | 15 Notebook PC              | [9eb25ba0bf](https://linux-hardware.org/?probe=9eb25ba0bf) | Jan 02, 2024 |
| Valve         | Jupiter                     | [e381b764b0](https://linux-hardware.org/?probe=e381b764b0) | Jan 02, 2024 |
| Valve         | Jupiter                     | [95183ba54e](https://linux-hardware.org/?probe=95183ba54e) | Jan 01, 2024 |
| Valve         | Jupiter                     | [c9de553faa](https://linux-hardware.org/?probe=c9de553faa) | Jan 01, 2024 |
| Valve         | Jupiter                     | [b16497fbfc](https://linux-hardware.org/?probe=b16497fbfc) | Jan 01, 2024 |
| Valve         | Jupiter                     | [e714aab1f3](https://linux-hardware.org/?probe=e714aab1f3) | Jan 01, 2024 |
| Valve         | Jupiter                     | [ca7a54408f](https://linux-hardware.org/?probe=ca7a54408f) | Dec 31, 2023 |
| Valve         | Jupiter                     | [5be404c400](https://linux-hardware.org/?probe=5be404c400) | Dec 31, 2023 |
| Valve         | Jupiter                     | [e80d5f8a2b](https://linux-hardware.org/?probe=e80d5f8a2b) | Dec 31, 2023 |
| Valve         | Jupiter                     | [c459051f01](https://linux-hardware.org/?probe=c459051f01) | Dec 31, 2023 |
| Valve         | Jupiter                     | [2f8ea60a38](https://linux-hardware.org/?probe=2f8ea60a38) | Dec 30, 2023 |
| Valve         | Jupiter                     | [0254493ea3](https://linux-hardware.org/?probe=0254493ea3) | Dec 29, 2023 |
| Valve         | Galileo                     | [83bfa965fb](https://linux-hardware.org/?probe=83bfa965fb) | Dec 28, 2023 |
| Valve         | Jupiter                     | [73a4d3fcfd](https://linux-hardware.org/?probe=73a4d3fcfd) | Dec 27, 2023 |
| Valve         | Jupiter                     | [bee71f6f73](https://linux-hardware.org/?probe=bee71f6f73) | Dec 27, 2023 |
| Valve         | Jupiter                     | [eeac675274](https://linux-hardware.org/?probe=eeac675274) | Dec 27, 2023 |
| Valve         | Jupiter                     | [c2f08b6c04](https://linux-hardware.org/?probe=c2f08b6c04) | Dec 26, 2023 |
| HP            | ProBook 455 G3              | [9e47611108](https://linux-hardware.org/?probe=9e47611108) | Dec 26, 2023 |
| Unknown       | X570 Phantom Gaming-ITX/... | [b5b5857360](https://linux-hardware.org/?probe=b5b5857360) | Dec 26, 2023 |
| Valve         | Jupiter                     | [6117a0c576](https://linux-hardware.org/?probe=6117a0c576) | Dec 25, 2023 |
| Valve         | Galileo                     | [e21296767e](https://linux-hardware.org/?probe=e21296767e) | Dec 25, 2023 |
| Valve         | Jupiter                     | [4ab75ea56b](https://linux-hardware.org/?probe=4ab75ea56b) | Dec 25, 2023 |
| Valve         | Jupiter                     | [509364a4ac](https://linux-hardware.org/?probe=509364a4ac) | Dec 25, 2023 |
| Valve         | Jupiter                     | [94cf6bda69](https://linux-hardware.org/?probe=94cf6bda69) | Dec 25, 2023 |
| Valve         | Galileo                     | [99c3c24140](https://linux-hardware.org/?probe=99c3c24140) | Dec 25, 2023 |
| Valve         | Jupiter                     | [6ec124a0c4](https://linux-hardware.org/?probe=6ec124a0c4) | Dec 24, 2023 |
| Valve         | Jupiter                     | [3f9fc8839c](https://linux-hardware.org/?probe=3f9fc8839c) | Dec 24, 2023 |
| Valve         | Jupiter                     | [f57d2e51fe](https://linux-hardware.org/?probe=f57d2e51fe) | Dec 24, 2023 |
| Valve         | Jupiter                     | [4c98f6b6f3](https://linux-hardware.org/?probe=4c98f6b6f3) | Dec 24, 2023 |
| Valve         | Jupiter                     | [c0b15b216d](https://linux-hardware.org/?probe=c0b15b216d) | Dec 24, 2023 |
| Valve         | Jupiter                     | [19f8d4f0b4](https://linux-hardware.org/?probe=19f8d4f0b4) | Dec 24, 2023 |
| Anbernic      | Win600                      | [3b5255f14b](https://linux-hardware.org/?probe=3b5255f14b) | Dec 24, 2023 |
| Valve         | Galileo                     | [aa141b8ea2](https://linux-hardware.org/?probe=aa141b8ea2) | Dec 24, 2023 |
| Anbernic      | Win600                      | [02e1d7adeb](https://linux-hardware.org/?probe=02e1d7adeb) | Dec 23, 2023 |
| Valve         | Jupiter                     | [6fd8f41741](https://linux-hardware.org/?probe=6fd8f41741) | Dec 23, 2023 |
| Valve         | Jupiter                     | [482500f7b0](https://linux-hardware.org/?probe=482500f7b0) | Dec 22, 2023 |
| Valve         | Jupiter                     | [03491495da](https://linux-hardware.org/?probe=03491495da) | Dec 22, 2023 |
| Valve         | Jupiter                     | [4899962b6a](https://linux-hardware.org/?probe=4899962b6a) | Dec 22, 2023 |
| Valve         | Jupiter                     | [f30a4a2d8a](https://linux-hardware.org/?probe=f30a4a2d8a) | Dec 21, 2023 |
| Valve         | Jupiter                     | [6003cb709f](https://linux-hardware.org/?probe=6003cb709f) | Dec 21, 2023 |
| Valve         | Jupiter                     | [186428f160](https://linux-hardware.org/?probe=186428f160) | Dec 21, 2023 |
| Valve         | Jupiter                     | [091511a6c2](https://linux-hardware.org/?probe=091511a6c2) | Dec 20, 2023 |
| Valve         | Jupiter                     | [ceba2299c2](https://linux-hardware.org/?probe=ceba2299c2) | Dec 20, 2023 |
| Valve         | Jupiter                     | [aecbb83cd6](https://linux-hardware.org/?probe=aecbb83cd6) | Dec 20, 2023 |
| Valve         | Jupiter                     | [1265867fcf](https://linux-hardware.org/?probe=1265867fcf) | Dec 19, 2023 |
| Valve         | Jupiter                     | [feae313bc0](https://linux-hardware.org/?probe=feae313bc0) | Dec 19, 2023 |
| Valve         | Jupiter                     | [d6b925353e](https://linux-hardware.org/?probe=d6b925353e) | Dec 18, 2023 |
| Valve         | Jupiter                     | [f8d7e441a5](https://linux-hardware.org/?probe=f8d7e441a5) | Dec 18, 2023 |
| Valve         | Galileo                     | [b79c5fbf78](https://linux-hardware.org/?probe=b79c5fbf78) | Dec 18, 2023 |
| Valve         | Jupiter                     | [b5b29d3c59](https://linux-hardware.org/?probe=b5b29d3c59) | Dec 18, 2023 |
| Valve         | Jupiter                     | [6235a63aa5](https://linux-hardware.org/?probe=6235a63aa5) | Dec 17, 2023 |
| Valve         | Galileo                     | [c02b71450c](https://linux-hardware.org/?probe=c02b71450c) | Dec 17, 2023 |
| Valve         | Jupiter                     | [0cda5b9141](https://linux-hardware.org/?probe=0cda5b9141) | Dec 17, 2023 |
| Valve         | Jupiter                     | [241ed280af](https://linux-hardware.org/?probe=241ed280af) | Dec 17, 2023 |
| Valve         | Jupiter                     | [d6c8debc47](https://linux-hardware.org/?probe=d6c8debc47) | Dec 16, 2023 |
| Valve         | Jupiter                     | [dfdfbefee5](https://linux-hardware.org/?probe=dfdfbefee5) | Dec 16, 2023 |
| Valve         | Jupiter                     | [298b8b5df0](https://linux-hardware.org/?probe=298b8b5df0) | Dec 16, 2023 |
| Valve         | Jupiter                     | [ee39964f52](https://linux-hardware.org/?probe=ee39964f52) | Dec 15, 2023 |
| Valve         | Galileo                     | [cd8b629d23](https://linux-hardware.org/?probe=cd8b629d23) | Dec 15, 2023 |
| Valve         | Jupiter                     | [bef7a2d5b3](https://linux-hardware.org/?probe=bef7a2d5b3) | Dec 15, 2023 |
| Valve         | Jupiter                     | [4e56fce432](https://linux-hardware.org/?probe=4e56fce432) | Dec 15, 2023 |
| Valve         | Galileo                     | [adb5dc0f2d](https://linux-hardware.org/?probe=adb5dc0f2d) | Dec 14, 2023 |
| Valve         | Jupiter                     | [594141dc7c](https://linux-hardware.org/?probe=594141dc7c) | Dec 14, 2023 |
| Valve         | Jupiter                     | [c2879ac10a](https://linux-hardware.org/?probe=c2879ac10a) | Dec 14, 2023 |
| Valve         | Jupiter                     | [9e2657f1ed](https://linux-hardware.org/?probe=9e2657f1ed) | Dec 14, 2023 |
| Valve         | Jupiter                     | [b746c80979](https://linux-hardware.org/?probe=b746c80979) | Dec 13, 2023 |
| Valve         | Jupiter                     | [4e38f77c8d](https://linux-hardware.org/?probe=4e38f77c8d) | Dec 13, 2023 |
| Valve         | Galileo                     | [719db5099f](https://linux-hardware.org/?probe=719db5099f) | Dec 13, 2023 |
| Valve         | Galileo                     | [835c844aed](https://linux-hardware.org/?probe=835c844aed) | Dec 13, 2023 |
| Valve         | Galileo                     | [d6ea0e047a](https://linux-hardware.org/?probe=d6ea0e047a) | Dec 13, 2023 |
| Valve         | Jupiter                     | [75070d8783](https://linux-hardware.org/?probe=75070d8783) | Dec 12, 2023 |
| Valve         | Galileo                     | [beb6edb04f](https://linux-hardware.org/?probe=beb6edb04f) | Dec 12, 2023 |
| Valve         | Jupiter                     | [3f0800eb70](https://linux-hardware.org/?probe=3f0800eb70) | Dec 11, 2023 |
| Valve         | Galileo                     | [494f369350](https://linux-hardware.org/?probe=494f369350) | Dec 11, 2023 |
| Valve         | Jupiter                     | [449a971a56](https://linux-hardware.org/?probe=449a971a56) | Dec 11, 2023 |
| Valve         | Jupiter                     | [b78720dbf3](https://linux-hardware.org/?probe=b78720dbf3) | Dec 11, 2023 |
| Apple         | MacBookPro15,1              | [9d882fc801](https://linux-hardware.org/?probe=9d882fc801) | Dec 11, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [9f6ce5cca9](https://linux-hardware.org/?probe=9f6ce5cca9) | Dec 10, 2023 |
| Valve         | Jupiter                     | [7d649cef63](https://linux-hardware.org/?probe=7d649cef63) | Dec 09, 2023 |
| Valve         | Jupiter                     | [f61425f9af](https://linux-hardware.org/?probe=f61425f9af) | Dec 09, 2023 |
| Valve         | Jupiter                     | [60c55f7c8c](https://linux-hardware.org/?probe=60c55f7c8c) | Dec 08, 2023 |
| Valve         | Jupiter                     | [c40a4f6672](https://linux-hardware.org/?probe=c40a4f6672) | Dec 08, 2023 |
| Valve         | Jupiter                     | [afd88ac5ea](https://linux-hardware.org/?probe=afd88ac5ea) | Dec 08, 2023 |
| Valve         | Galileo                     | [0eacb54dca](https://linux-hardware.org/?probe=0eacb54dca) | Dec 08, 2023 |
| Valve         | Jupiter                     | [326f2a7596](https://linux-hardware.org/?probe=326f2a7596) | Dec 08, 2023 |
| Valve         | Jupiter                     | [dfa143c1c0](https://linux-hardware.org/?probe=dfa143c1c0) | Dec 08, 2023 |
| Valve         | Galileo                     | [f72b98880f](https://linux-hardware.org/?probe=f72b98880f) | Dec 07, 2023 |
| Valve         | Jupiter                     | [2c693deae3](https://linux-hardware.org/?probe=2c693deae3) | Dec 07, 2023 |
| Valve         | Jupiter                     | [1a0ea506dc](https://linux-hardware.org/?probe=1a0ea506dc) | Dec 07, 2023 |
| Valve         | Jupiter                     | [602605d28d](https://linux-hardware.org/?probe=602605d28d) | Dec 07, 2023 |
| Valve         | Jupiter                     | [7eec257dd6](https://linux-hardware.org/?probe=7eec257dd6) | Dec 07, 2023 |
| Valve         | Jupiter                     | [bbb500139e](https://linux-hardware.org/?probe=bbb500139e) | Dec 07, 2023 |
| Valve         | Galileo                     | [20b7e72741](https://linux-hardware.org/?probe=20b7e72741) | Dec 06, 2023 |
| Valve         | Jupiter                     | [14e2e0d2b6](https://linux-hardware.org/?probe=14e2e0d2b6) | Dec 06, 2023 |
| Valve         | Galileo                     | [4704035dff](https://linux-hardware.org/?probe=4704035dff) | Dec 06, 2023 |
| Valve         | Jupiter                     | [93bf1ceeec](https://linux-hardware.org/?probe=93bf1ceeec) | Dec 05, 2023 |
| Valve         | Jupiter                     | [f7115ec7c0](https://linux-hardware.org/?probe=f7115ec7c0) | Dec 05, 2023 |
| Valve         | Jupiter                     | [2a17ca7efe](https://linux-hardware.org/?probe=2a17ca7efe) | Dec 05, 2023 |
| Valve         | Jupiter                     | [4ffa224365](https://linux-hardware.org/?probe=4ffa224365) | Dec 05, 2023 |
| Valve         | Jupiter                     | [63e8b02453](https://linux-hardware.org/?probe=63e8b02453) | Dec 05, 2023 |
| Valve         | Jupiter                     | [ea1ae6a495](https://linux-hardware.org/?probe=ea1ae6a495) | Dec 04, 2023 |
| Valve         | Galileo                     | [1760875677](https://linux-hardware.org/?probe=1760875677) | Dec 04, 2023 |
| Valve         | Jupiter                     | [286c2304f5](https://linux-hardware.org/?probe=286c2304f5) | Dec 03, 2023 |
| Valve         | Jupiter                     | [21c483ddcf](https://linux-hardware.org/?probe=21c483ddcf) | Dec 03, 2023 |
| Valve         | Jupiter                     | [36af755784](https://linux-hardware.org/?probe=36af755784) | Dec 03, 2023 |
| Valve         | Jupiter                     | [80a3ff932f](https://linux-hardware.org/?probe=80a3ff932f) | Dec 03, 2023 |
| ASRock        | B550M Steel Legend          | [532cab64b5](https://linux-hardware.org/?probe=532cab64b5) | Dec 03, 2023 |
| Valve         | Galileo                     | [7c11f8f225](https://linux-hardware.org/?probe=7c11f8f225) | Dec 02, 2023 |
| Valve         | Galileo                     | [63234eea22](https://linux-hardware.org/?probe=63234eea22) | Dec 02, 2023 |
| Valve         | Jupiter                     | [6a95e96b1b](https://linux-hardware.org/?probe=6a95e96b1b) | Dec 02, 2023 |
| Valve         | Jupiter                     | [e5546145aa](https://linux-hardware.org/?probe=e5546145aa) | Dec 02, 2023 |
| Valve         | Jupiter                     | [dc16a663fa](https://linux-hardware.org/?probe=dc16a663fa) | Dec 02, 2023 |
| Valve         | Jupiter                     | [e6d5beb948](https://linux-hardware.org/?probe=e6d5beb948) | Dec 01, 2023 |
| Valve         | Galileo                     | [3239203d03](https://linux-hardware.org/?probe=3239203d03) | Dec 01, 2023 |
| Valve         | Jupiter                     | [ff8952a98c](https://linux-hardware.org/?probe=ff8952a98c) | Dec 01, 2023 |
| Valve         | Galileo                     | [3006af1c16](https://linux-hardware.org/?probe=3006af1c16) | Dec 01, 2023 |
| Valve         | Jupiter                     | [545d093510](https://linux-hardware.org/?probe=545d093510) | Nov 30, 2023 |
| Valve         | Jupiter                     | [2251ba47fb](https://linux-hardware.org/?probe=2251ba47fb) | Nov 30, 2023 |
| Valve         | Jupiter                     | [da673c17c8](https://linux-hardware.org/?probe=da673c17c8) | Nov 29, 2023 |
| Valve         | Jupiter                     | [e92fd78128](https://linux-hardware.org/?probe=e92fd78128) | Nov 29, 2023 |
| Valve         | Jupiter                     | [b5216ccd78](https://linux-hardware.org/?probe=b5216ccd78) | Nov 29, 2023 |
| Valve         | Galileo                     | [f8322860f1](https://linux-hardware.org/?probe=f8322860f1) | Nov 29, 2023 |
| Valve         | Jupiter                     | [2ceef57eaa](https://linux-hardware.org/?probe=2ceef57eaa) | Nov 28, 2023 |
| Valve         | Jupiter                     | [ebc4731c68](https://linux-hardware.org/?probe=ebc4731c68) | Nov 28, 2023 |
| Valve         | Jupiter                     | [9544f59716](https://linux-hardware.org/?probe=9544f59716) | Nov 27, 2023 |
| Valve         | Jupiter                     | [2bf5b349c3](https://linux-hardware.org/?probe=2bf5b349c3) | Nov 27, 2023 |
| Valve         | Jupiter                     | [d2e56a6b92](https://linux-hardware.org/?probe=d2e56a6b92) | Nov 27, 2023 |
| Valve         | Jupiter                     | [855c477023](https://linux-hardware.org/?probe=855c477023) | Nov 27, 2023 |
| Valve         | Jupiter                     | [2a0b1b3a9b](https://linux-hardware.org/?probe=2a0b1b3a9b) | Nov 27, 2023 |
| Valve         | Jupiter                     | [933ce1aa7d](https://linux-hardware.org/?probe=933ce1aa7d) | Nov 27, 2023 |
| Valve         | Jupiter                     | [c6c33679d8](https://linux-hardware.org/?probe=c6c33679d8) | Nov 26, 2023 |
| Valve         | Jupiter                     | [a208b7bd3a](https://linux-hardware.org/?probe=a208b7bd3a) | Nov 26, 2023 |
| Valve         | Jupiter                     | [2b2f81a5b3](https://linux-hardware.org/?probe=2b2f81a5b3) | Nov 26, 2023 |
| Valve         | Jupiter                     | [95bd4c2832](https://linux-hardware.org/?probe=95bd4c2832) | Nov 26, 2023 |
| Dell          | Precision M4800             | [8712b3ecb9](https://linux-hardware.org/?probe=8712b3ecb9) | Nov 26, 2023 |
| Valve         | Jupiter                     | [fe89edacdc](https://linux-hardware.org/?probe=fe89edacdc) | Nov 26, 2023 |
| Valve         | Jupiter                     | [d760d5c451](https://linux-hardware.org/?probe=d760d5c451) | Nov 26, 2023 |
| Valve         | Jupiter                     | [7f42b09854](https://linux-hardware.org/?probe=7f42b09854) | Nov 26, 2023 |
| Valve         | Jupiter                     | [3e59300230](https://linux-hardware.org/?probe=3e59300230) | Nov 25, 2023 |
| Valve         | Galileo                     | [905889b654](https://linux-hardware.org/?probe=905889b654) | Nov 25, 2023 |
| Valve         | Galileo                     | [15994404a2](https://linux-hardware.org/?probe=15994404a2) | Nov 24, 2023 |
| Valve         | Jupiter                     | [2c7d8106d0](https://linux-hardware.org/?probe=2c7d8106d0) | Nov 24, 2023 |
| Valve         | Jupiter                     | [68d1729e3b](https://linux-hardware.org/?probe=68d1729e3b) | Nov 24, 2023 |
| Valve         | Jupiter                     | [cd4e80c195](https://linux-hardware.org/?probe=cd4e80c195) | Nov 24, 2023 |
| Valve         | Jupiter                     | [cb881f1c27](https://linux-hardware.org/?probe=cb881f1c27) | Nov 24, 2023 |
| Valve         | Jupiter                     | [8ba2f4981d](https://linux-hardware.org/?probe=8ba2f4981d) | Nov 24, 2023 |
| Valve         | Jupiter                     | [0c58fa47b9](https://linux-hardware.org/?probe=0c58fa47b9) | Nov 24, 2023 |
| Valve         | Jupiter                     | [399542e5be](https://linux-hardware.org/?probe=399542e5be) | Nov 24, 2023 |
| Valve         | Galileo                     | [0e0c27070c](https://linux-hardware.org/?probe=0e0c27070c) | Nov 23, 2023 |
| Gigabyte      | B650M DS3H                  | [dfcb329b5a](https://linux-hardware.org/?probe=dfcb329b5a) | Nov 23, 2023 |
| Valve         | Jupiter                     | [a4f7cad00f](https://linux-hardware.org/?probe=a4f7cad00f) | Nov 22, 2023 |
| Valve         | Jupiter                     | [bdb118e120](https://linux-hardware.org/?probe=bdb118e120) | Nov 22, 2023 |
| Valve         | Jupiter                     | [678fc160d6](https://linux-hardware.org/?probe=678fc160d6) | Nov 22, 2023 |
| Valve         | Jupiter                     | [157c8167b7](https://linux-hardware.org/?probe=157c8167b7) | Nov 22, 2023 |
| Valve         | Jupiter                     | [525a89cf72](https://linux-hardware.org/?probe=525a89cf72) | Nov 22, 2023 |
| Valve         | Jupiter                     | [2fa43c6f3d](https://linux-hardware.org/?probe=2fa43c6f3d) | Nov 22, 2023 |
| Valve         | Jupiter                     | [b73a5b800d](https://linux-hardware.org/?probe=b73a5b800d) | Nov 22, 2023 |
| Valve         | Jupiter                     | [a81bb49e88](https://linux-hardware.org/?probe=a81bb49e88) | Nov 21, 2023 |
| Valve         | Jupiter                     | [ba3c14e8e7](https://linux-hardware.org/?probe=ba3c14e8e7) | Nov 21, 2023 |
| Valve         | Jupiter                     | [3bac0a6d11](https://linux-hardware.org/?probe=3bac0a6d11) | Nov 21, 2023 |
| Valve         | Jupiter                     | [0454a567a0](https://linux-hardware.org/?probe=0454a567a0) | Nov 21, 2023 |
| Valve         | Jupiter                     | [57479f92a2](https://linux-hardware.org/?probe=57479f92a2) | Nov 21, 2023 |
| Valve         | Jupiter                     | [e782bdc7ec](https://linux-hardware.org/?probe=e782bdc7ec) | Nov 21, 2023 |
| Valve         | Jupiter                     | [f36d771d28](https://linux-hardware.org/?probe=f36d771d28) | Nov 20, 2023 |
| Valve         | Jupiter                     | [be5497e3a7](https://linux-hardware.org/?probe=be5497e3a7) | Nov 20, 2023 |
| Valve         | Jupiter                     | [93c68a0d33](https://linux-hardware.org/?probe=93c68a0d33) | Nov 20, 2023 |
| Valve         | Jupiter                     | [a6240c8d6a](https://linux-hardware.org/?probe=a6240c8d6a) | Nov 20, 2023 |
| Valve         | Jupiter                     | [4d99a400c5](https://linux-hardware.org/?probe=4d99a400c5) | Nov 20, 2023 |
| Valve         | Jupiter                     | [08b0fccf59](https://linux-hardware.org/?probe=08b0fccf59) | Nov 20, 2023 |
| Valve         | Jupiter                     | [b3d483cfb9](https://linux-hardware.org/?probe=b3d483cfb9) | Nov 19, 2023 |
| Valve         | Jupiter                     | [e226cd6888](https://linux-hardware.org/?probe=e226cd6888) | Nov 18, 2023 |
| Valve         | Jupiter                     | [d859d4f159](https://linux-hardware.org/?probe=d859d4f159) | Nov 18, 2023 |
| Valve         | Jupiter                     | [82eedfb8be](https://linux-hardware.org/?probe=82eedfb8be) | Nov 18, 2023 |
| Valve         | Jupiter                     | [2c773bdad4](https://linux-hardware.org/?probe=2c773bdad4) | Nov 18, 2023 |
| Valve         | Jupiter                     | [adbc907a31](https://linux-hardware.org/?probe=adbc907a31) | Nov 18, 2023 |
| Valve         | Jupiter                     | [9d693c070e](https://linux-hardware.org/?probe=9d693c070e) | Nov 18, 2023 |
| Valve         | Jupiter                     | [fdddf0d94f](https://linux-hardware.org/?probe=fdddf0d94f) | Nov 18, 2023 |
| Valve         | Jupiter                     | [97695463df](https://linux-hardware.org/?probe=97695463df) | Nov 17, 2023 |
| Valve         | Jupiter                     | [8734420ff1](https://linux-hardware.org/?probe=8734420ff1) | Nov 17, 2023 |
| Valve         | Jupiter                     | [c726569566](https://linux-hardware.org/?probe=c726569566) | Nov 16, 2023 |
| Valve         | Jupiter                     | [521a021c1d](https://linux-hardware.org/?probe=521a021c1d) | Nov 16, 2023 |
| Valve         | Jupiter                     | [10f96b411d](https://linux-hardware.org/?probe=10f96b411d) | Nov 16, 2023 |
| Valve         | Jupiter                     | [af72567b85](https://linux-hardware.org/?probe=af72567b85) | Nov 16, 2023 |
| Valve         | Jupiter                     | [751a8a13dc](https://linux-hardware.org/?probe=751a8a13dc) | Nov 15, 2023 |
| Valve         | Jupiter                     | [821a98f0f9](https://linux-hardware.org/?probe=821a98f0f9) | Nov 15, 2023 |
| Valve         | Jupiter                     | [9f8fc1d4d7](https://linux-hardware.org/?probe=9f8fc1d4d7) | Nov 15, 2023 |
| Valve         | Jupiter                     | [31a965ca9d](https://linux-hardware.org/?probe=31a965ca9d) | Nov 14, 2023 |
| Valve         | Jupiter                     | [638956d8a1](https://linux-hardware.org/?probe=638956d8a1) | Nov 13, 2023 |
| Valve         | Jupiter                     | [acdbd4cb2a](https://linux-hardware.org/?probe=acdbd4cb2a) | Nov 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [2802d9278d](https://linux-hardware.org/?probe=2802d9278d) | Nov 13, 2023 |
| Valve         | Jupiter                     | [1f6282ce11](https://linux-hardware.org/?probe=1f6282ce11) | Nov 12, 2023 |
| Valve         | Jupiter                     | [040bcdd741](https://linux-hardware.org/?probe=040bcdd741) | Nov 10, 2023 |
| Valve         | Jupiter                     | [f3e618c03e](https://linux-hardware.org/?probe=f3e618c03e) | Nov 10, 2023 |
| Valve         | Jupiter                     | [ff8cbcd6be](https://linux-hardware.org/?probe=ff8cbcd6be) | Nov 09, 2023 |
| Valve         | Jupiter                     | [196bc6a3db](https://linux-hardware.org/?probe=196bc6a3db) | Nov 08, 2023 |
| Valve         | Jupiter                     | [ca05263192](https://linux-hardware.org/?probe=ca05263192) | Nov 08, 2023 |
| Valve         | Jupiter                     | [98976642aa](https://linux-hardware.org/?probe=98976642aa) | Nov 08, 2023 |
| Valve         | Jupiter                     | [848dfcb217](https://linux-hardware.org/?probe=848dfcb217) | Nov 08, 2023 |
| Valve         | Jupiter                     | [03f6022593](https://linux-hardware.org/?probe=03f6022593) | Nov 07, 2023 |
| Valve         | Jupiter                     | [ef2daabe89](https://linux-hardware.org/?probe=ef2daabe89) | Nov 07, 2023 |
| Valve         | Jupiter                     | [b662e225f4](https://linux-hardware.org/?probe=b662e225f4) | Nov 07, 2023 |
| Valve         | Jupiter                     | [21df431e01](https://linux-hardware.org/?probe=21df431e01) | Nov 07, 2023 |
| Valve         | Jupiter                     | [58ecc57dcf](https://linux-hardware.org/?probe=58ecc57dcf) | Nov 07, 2023 |
| Valve         | Jupiter                     | [c00bcace68](https://linux-hardware.org/?probe=c00bcace68) | Nov 06, 2023 |
| Valve         | Jupiter                     | [aef9c84cf7](https://linux-hardware.org/?probe=aef9c84cf7) | Nov 06, 2023 |
| Valve         | Jupiter                     | [d8ac880948](https://linux-hardware.org/?probe=d8ac880948) | Nov 06, 2023 |
| Valve         | Jupiter                     | [2e74968a1e](https://linux-hardware.org/?probe=2e74968a1e) | Nov 05, 2023 |
| Valve         | Jupiter                     | [edb0760b00](https://linux-hardware.org/?probe=edb0760b00) | Nov 05, 2023 |
| Valve         | Jupiter                     | [555d9146a4](https://linux-hardware.org/?probe=555d9146a4) | Nov 05, 2023 |
| Valve         | Jupiter                     | [4ece1b1597](https://linux-hardware.org/?probe=4ece1b1597) | Nov 05, 2023 |
| Valve         | Jupiter                     | [28e2c2aa38](https://linux-hardware.org/?probe=28e2c2aa38) | Nov 05, 2023 |
| Valve         | Jupiter                     | [af20418f73](https://linux-hardware.org/?probe=af20418f73) | Nov 04, 2023 |
| Valve         | Jupiter                     | [28f8f3e3cd](https://linux-hardware.org/?probe=28f8f3e3cd) | Nov 04, 2023 |
| Valve         | Jupiter                     | [b526accbcd](https://linux-hardware.org/?probe=b526accbcd) | Nov 03, 2023 |
| Valve         | Jupiter                     | [14de2c4b3a](https://linux-hardware.org/?probe=14de2c4b3a) | Nov 02, 2023 |
| Valve         | Jupiter                     | [26b7407b02](https://linux-hardware.org/?probe=26b7407b02) | Nov 02, 2023 |
| Valve         | Jupiter                     | [088df44ddf](https://linux-hardware.org/?probe=088df44ddf) | Nov 01, 2023 |
| Valve         | Jupiter                     | [b5bd58d350](https://linux-hardware.org/?probe=b5bd58d350) | Oct 31, 2023 |
| Valve         | Jupiter                     | [ea0f1bf927](https://linux-hardware.org/?probe=ea0f1bf927) | Oct 31, 2023 |
| Valve         | Jupiter                     | [9749e20de1](https://linux-hardware.org/?probe=9749e20de1) | Oct 31, 2023 |
| Valve         | Jupiter                     | [7eda72383a](https://linux-hardware.org/?probe=7eda72383a) | Oct 30, 2023 |
| Valve         | Jupiter                     | [e73e0881d6](https://linux-hardware.org/?probe=e73e0881d6) | Oct 30, 2023 |
| Valve         | Jupiter                     | [ede97625bd](https://linux-hardware.org/?probe=ede97625bd) | Oct 30, 2023 |
| Valve         | Jupiter                     | [8bb009206e](https://linux-hardware.org/?probe=8bb009206e) | Oct 29, 2023 |
| Valve         | Jupiter                     | [bbf3f7c198](https://linux-hardware.org/?probe=bbf3f7c198) | Oct 29, 2023 |
| Valve         | Jupiter                     | [935baa5e6a](https://linux-hardware.org/?probe=935baa5e6a) | Oct 29, 2023 |
| Valve         | Jupiter                     | [3e84a41deb](https://linux-hardware.org/?probe=3e84a41deb) | Oct 28, 2023 |
| Valve         | Jupiter                     | [8eebce7a7b](https://linux-hardware.org/?probe=8eebce7a7b) | Oct 26, 2023 |
| Valve         | Jupiter                     | [a524108535](https://linux-hardware.org/?probe=a524108535) | Oct 26, 2023 |
| Valve         | Jupiter                     | [ae2eee1640](https://linux-hardware.org/?probe=ae2eee1640) | Oct 26, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | [6c603a7186](https://linux-hardware.org/?probe=6c603a7186) | Oct 26, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | [7858b6a253](https://linux-hardware.org/?probe=7858b6a253) | Oct 26, 2023 |
| Valve         | Jupiter                     | [38a8824fe8](https://linux-hardware.org/?probe=38a8824fe8) | Oct 25, 2023 |
| Valve         | Jupiter                     | [eda569093f](https://linux-hardware.org/?probe=eda569093f) | Oct 25, 2023 |
| Valve         | Jupiter                     | [0b8471e81a](https://linux-hardware.org/?probe=0b8471e81a) | Oct 25, 2023 |
| Valve         | Jupiter                     | [158b201b0e](https://linux-hardware.org/?probe=158b201b0e) | Oct 24, 2023 |
| Valve         | Jupiter                     | [83d3faf177](https://linux-hardware.org/?probe=83d3faf177) | Oct 23, 2023 |
| Valve         | Jupiter                     | [fa38785b75](https://linux-hardware.org/?probe=fa38785b75) | Oct 23, 2023 |
| Valve         | Jupiter                     | [8e04b76eb0](https://linux-hardware.org/?probe=8e04b76eb0) | Oct 22, 2023 |
| Valve         | Jupiter                     | [1c5a3146ce](https://linux-hardware.org/?probe=1c5a3146ce) | Oct 22, 2023 |
| Valve         | Jupiter                     | [d93782448d](https://linux-hardware.org/?probe=d93782448d) | Oct 21, 2023 |
| Valve         | Jupiter                     | [69762a50c8](https://linux-hardware.org/?probe=69762a50c8) | Oct 21, 2023 |
| Valve         | Jupiter                     | [5c8fbec79f](https://linux-hardware.org/?probe=5c8fbec79f) | Oct 21, 2023 |
| Valve         | Jupiter                     | [3431f785cf](https://linux-hardware.org/?probe=3431f785cf) | Oct 21, 2023 |
| Valve         | Jupiter                     | [3fa710b9ff](https://linux-hardware.org/?probe=3fa710b9ff) | Oct 20, 2023 |
| Valve         | Jupiter                     | [fdbd97d08c](https://linux-hardware.org/?probe=fdbd97d08c) | Oct 20, 2023 |
| Valve         | Jupiter                     | [ca9cd15419](https://linux-hardware.org/?probe=ca9cd15419) | Oct 19, 2023 |
| Valve         | Jupiter                     | [6eab7fbd58](https://linux-hardware.org/?probe=6eab7fbd58) | Oct 18, 2023 |
| Valve         | Jupiter                     | [bcc8229faa](https://linux-hardware.org/?probe=bcc8229faa) | Oct 18, 2023 |
| Valve         | Jupiter                     | [d91ad654e6](https://linux-hardware.org/?probe=d91ad654e6) | Oct 18, 2023 |
| Valve         | Jupiter                     | [4c916d65a8](https://linux-hardware.org/?probe=4c916d65a8) | Oct 18, 2023 |
| Valve         | Jupiter                     | [9a1b2b4816](https://linux-hardware.org/?probe=9a1b2b4816) | Oct 18, 2023 |
| Valve         | Jupiter                     | [08d5fc51ed](https://linux-hardware.org/?probe=08d5fc51ed) | Oct 17, 2023 |
| Valve         | Jupiter                     | [c6e5484c88](https://linux-hardware.org/?probe=c6e5484c88) | Oct 17, 2023 |
| Valve         | Jupiter                     | [1e55c77dc0](https://linux-hardware.org/?probe=1e55c77dc0) | Oct 17, 2023 |
| Valve         | Jupiter                     | [54604c764b](https://linux-hardware.org/?probe=54604c764b) | Oct 16, 2023 |
| Valve         | Jupiter                     | [cfbfe426e2](https://linux-hardware.org/?probe=cfbfe426e2) | Oct 16, 2023 |
| Valve         | Jupiter                     | [d8ba22dd7f](https://linux-hardware.org/?probe=d8ba22dd7f) | Oct 16, 2023 |
| Valve         | Jupiter                     | [11ee2fce41](https://linux-hardware.org/?probe=11ee2fce41) | Oct 16, 2023 |
| Valve         | Jupiter                     | [e0e2e64ce4](https://linux-hardware.org/?probe=e0e2e64ce4) | Oct 16, 2023 |
| Valve         | Jupiter                     | [674d290b37](https://linux-hardware.org/?probe=674d290b37) | Oct 15, 2023 |
| Valve         | Jupiter                     | [ec059c9ea7](https://linux-hardware.org/?probe=ec059c9ea7) | Oct 15, 2023 |
| Valve         | Jupiter                     | [9ed8384df0](https://linux-hardware.org/?probe=9ed8384df0) | Oct 15, 2023 |
| Valve         | Jupiter                     | [0d088b07f0](https://linux-hardware.org/?probe=0d088b07f0) | Oct 14, 2023 |
| Valve         | Jupiter                     | [594ab95469](https://linux-hardware.org/?probe=594ab95469) | Oct 13, 2023 |
| Valve         | Jupiter                     | [bc127c6288](https://linux-hardware.org/?probe=bc127c6288) | Oct 13, 2023 |
| Valve         | Jupiter                     | [2bde49db66](https://linux-hardware.org/?probe=2bde49db66) | Oct 11, 2023 |
| Valve         | Jupiter                     | [79652d4b80](https://linux-hardware.org/?probe=79652d4b80) | Oct 10, 2023 |
| Valve         | Jupiter                     | [daeb359dfb](https://linux-hardware.org/?probe=daeb359dfb) | Oct 10, 2023 |
| Valve         | Jupiter                     | [100d2ff5c3](https://linux-hardware.org/?probe=100d2ff5c3) | Oct 10, 2023 |
| Valve         | Jupiter                     | [8746055b62](https://linux-hardware.org/?probe=8746055b62) | Oct 09, 2023 |
| Valve         | Jupiter                     | [ece1acc9c3](https://linux-hardware.org/?probe=ece1acc9c3) | Oct 09, 2023 |
| Valve         | Jupiter                     | [e8f2d96884](https://linux-hardware.org/?probe=e8f2d96884) | Oct 09, 2023 |
| Valve         | Jupiter                     | [19f850d49e](https://linux-hardware.org/?probe=19f850d49e) | Oct 08, 2023 |
| Valve         | Jupiter                     | [83976ddca6](https://linux-hardware.org/?probe=83976ddca6) | Oct 08, 2023 |
| Valve         | Jupiter                     | [86be8c226a](https://linux-hardware.org/?probe=86be8c226a) | Oct 08, 2023 |
| Acer          | Swift SFA16-41              | [9d284c1003](https://linux-hardware.org/?probe=9d284c1003) | Oct 08, 2023 |
| Valve         | Jupiter                     | [aa51056093](https://linux-hardware.org/?probe=aa51056093) | Oct 08, 2023 |
| Valve         | Jupiter                     | [225fbcc2e5](https://linux-hardware.org/?probe=225fbcc2e5) | Oct 08, 2023 |
| Valve         | Jupiter                     | [e88c7ccef3](https://linux-hardware.org/?probe=e88c7ccef3) | Oct 08, 2023 |
| Acer          | Nitro AN515-56              | [6a98464415](https://linux-hardware.org/?probe=6a98464415) | Oct 07, 2023 |
| Valve         | Jupiter                     | [4db1b82d76](https://linux-hardware.org/?probe=4db1b82d76) | Oct 07, 2023 |
| Valve         | Jupiter                     | [7372c13af4](https://linux-hardware.org/?probe=7372c13af4) | Oct 07, 2023 |
| Valve         | Jupiter                     | [19509bb422](https://linux-hardware.org/?probe=19509bb422) | Oct 05, 2023 |
| Valve         | Jupiter                     | [f39bde007d](https://linux-hardware.org/?probe=f39bde007d) | Oct 04, 2023 |
| Valve         | Jupiter                     | [6a0aaac720](https://linux-hardware.org/?probe=6a0aaac720) | Oct 04, 2023 |
| Valve         | Jupiter                     | [0e8526e2df](https://linux-hardware.org/?probe=0e8526e2df) | Oct 04, 2023 |
| Valve         | Jupiter                     | [54eaf1a92d](https://linux-hardware.org/?probe=54eaf1a92d) | Oct 04, 2023 |
| Valve         | Jupiter                     | [4c7b5edf25](https://linux-hardware.org/?probe=4c7b5edf25) | Oct 04, 2023 |
| Valve         | Jupiter                     | [1fc3301438](https://linux-hardware.org/?probe=1fc3301438) | Oct 03, 2023 |
| Valve         | Jupiter                     | [71e7e7bd84](https://linux-hardware.org/?probe=71e7e7bd84) | Oct 03, 2023 |
| Valve         | Jupiter                     | [888143673a](https://linux-hardware.org/?probe=888143673a) | Oct 03, 2023 |
| Valve         | Jupiter                     | [43244b054f](https://linux-hardware.org/?probe=43244b054f) | Oct 03, 2023 |
| Valve         | Jupiter                     | [a37cbce440](https://linux-hardware.org/?probe=a37cbce440) | Oct 02, 2023 |
| Valve         | Jupiter                     | [35dc2f9bbd](https://linux-hardware.org/?probe=35dc2f9bbd) | Oct 02, 2023 |
| HP            | Victus by Gaming Laptop ... | [60a8a7d13f](https://linux-hardware.org/?probe=60a8a7d13f) | Oct 02, 2023 |
| HP            | Victus by Gaming Laptop ... | [28a54d8189](https://linux-hardware.org/?probe=28a54d8189) | Oct 02, 2023 |
| Valve         | Jupiter                     | [bb4a397154](https://linux-hardware.org/?probe=bb4a397154) | Oct 01, 2023 |
| Valve         | Jupiter                     | [1323f200dd](https://linux-hardware.org/?probe=1323f200dd) | Oct 01, 2023 |
| Valve         | Jupiter                     | [c31d1a5288](https://linux-hardware.org/?probe=c31d1a5288) | Oct 01, 2023 |
| Valve         | Jupiter                     | [d64d0a1997](https://linux-hardware.org/?probe=d64d0a1997) | Sep 30, 2023 |
| Valve         | Jupiter                     | [0488b8fd24](https://linux-hardware.org/?probe=0488b8fd24) | Sep 30, 2023 |
| Valve         | Jupiter                     | [85eac5b7ce](https://linux-hardware.org/?probe=85eac5b7ce) | Sep 30, 2023 |
| Valve         | Jupiter                     | [1ed8509a3d](https://linux-hardware.org/?probe=1ed8509a3d) | Sep 30, 2023 |
| Valve         | Jupiter                     | [d065544135](https://linux-hardware.org/?probe=d065544135) | Sep 29, 2023 |
| Valve         | Jupiter                     | [c881d3edc2](https://linux-hardware.org/?probe=c881d3edc2) | Sep 29, 2023 |
| Valve         | Jupiter                     | [2f4eb9f823](https://linux-hardware.org/?probe=2f4eb9f823) | Sep 29, 2023 |
| Valve         | Jupiter                     | [937f10463d](https://linux-hardware.org/?probe=937f10463d) | Sep 29, 2023 |
| Valve         | Jupiter                     | [acc0ad7283](https://linux-hardware.org/?probe=acc0ad7283) | Sep 28, 2023 |
| Valve         | Jupiter                     | [39bc0d89fe](https://linux-hardware.org/?probe=39bc0d89fe) | Sep 28, 2023 |
| Valve         | Jupiter                     | [a447ea95b0](https://linux-hardware.org/?probe=a447ea95b0) | Sep 28, 2023 |
| Valve         | Jupiter                     | [b178e71c45](https://linux-hardware.org/?probe=b178e71c45) | Sep 28, 2023 |
| Valve         | Jupiter                     | [0948401e7d](https://linux-hardware.org/?probe=0948401e7d) | Sep 28, 2023 |
| Valve         | Jupiter                     | [8de9bb39df](https://linux-hardware.org/?probe=8de9bb39df) | Sep 28, 2023 |
| Valve         | Jupiter                     | [2c1e6c791d](https://linux-hardware.org/?probe=2c1e6c791d) | Sep 28, 2023 |
| Valve         | Jupiter                     | [277f5aca9b](https://linux-hardware.org/?probe=277f5aca9b) | Sep 26, 2023 |
| Valve         | Jupiter                     | [3c758abd49](https://linux-hardware.org/?probe=3c758abd49) | Sep 26, 2023 |
| HP            | Laptop 15-bw0xx             | [ba7c544fbb](https://linux-hardware.org/?probe=ba7c544fbb) | Sep 26, 2023 |
| Valve         | Jupiter                     | [651e61bc4b](https://linux-hardware.org/?probe=651e61bc4b) | Sep 25, 2023 |
| Valve         | Jupiter                     | [7a64b4c44f](https://linux-hardware.org/?probe=7a64b4c44f) | Sep 25, 2023 |
| Valve         | Jupiter                     | [7af512f94c](https://linux-hardware.org/?probe=7af512f94c) | Sep 24, 2023 |
| Valve         | Jupiter                     | [610cd4fd42](https://linux-hardware.org/?probe=610cd4fd42) | Sep 23, 2023 |
| Valve         | Jupiter                     | [287bf4d933](https://linux-hardware.org/?probe=287bf4d933) | Sep 23, 2023 |
| Valve         | Jupiter                     | [3889f9ca9d](https://linux-hardware.org/?probe=3889f9ca9d) | Sep 23, 2023 |
| Valve         | Jupiter                     | [b0abd58408](https://linux-hardware.org/?probe=b0abd58408) | Sep 22, 2023 |
| Valve         | Jupiter                     | [dcc631e0fd](https://linux-hardware.org/?probe=dcc631e0fd) | Sep 22, 2023 |
| Valve         | Jupiter                     | [f4582a5754](https://linux-hardware.org/?probe=f4582a5754) | Sep 22, 2023 |
| Valve         | Jupiter                     | [de6ae4f340](https://linux-hardware.org/?probe=de6ae4f340) | Sep 21, 2023 |
| Valve         | Jupiter                     | [9971977392](https://linux-hardware.org/?probe=9971977392) | Sep 21, 2023 |
| Valve         | Jupiter                     | [7247eddba1](https://linux-hardware.org/?probe=7247eddba1) | Sep 21, 2023 |
| Valve         | Jupiter                     | [2b2966eb3d](https://linux-hardware.org/?probe=2b2966eb3d) | Sep 21, 2023 |
| Valve         | Jupiter                     | [2c967e82b6](https://linux-hardware.org/?probe=2c967e82b6) | Sep 21, 2023 |
| Valve         | Jupiter                     | [fc14aeacc1](https://linux-hardware.org/?probe=fc14aeacc1) | Sep 20, 2023 |
| Valve         | Jupiter                     | [458972a2c0](https://linux-hardware.org/?probe=458972a2c0) | Sep 19, 2023 |
| Valve         | Jupiter                     | [c26c68e9a4](https://linux-hardware.org/?probe=c26c68e9a4) | Sep 19, 2023 |
| Valve         | Jupiter                     | [7baec97424](https://linux-hardware.org/?probe=7baec97424) | Sep 19, 2023 |
| Valve         | Jupiter                     | [2c3f76de4d](https://linux-hardware.org/?probe=2c3f76de4d) | Sep 18, 2023 |
| Valve         | Jupiter                     | [9b95215db5](https://linux-hardware.org/?probe=9b95215db5) | Sep 17, 2023 |
| Valve         | Jupiter                     | [ffa55f4f83](https://linux-hardware.org/?probe=ffa55f4f83) | Sep 17, 2023 |
| Valve         | Jupiter                     | [55f9c98103](https://linux-hardware.org/?probe=55f9c98103) | Sep 17, 2023 |
| Valve         | Jupiter                     | [243f46cfa8](https://linux-hardware.org/?probe=243f46cfa8) | Sep 17, 2023 |
| Valve         | Jupiter                     | [3bd1c975cc](https://linux-hardware.org/?probe=3bd1c975cc) | Sep 16, 2023 |
| Valve         | Jupiter                     | [17d891df44](https://linux-hardware.org/?probe=17d891df44) | Sep 13, 2023 |
| Valve         | Jupiter                     | [06f7e4ef1b](https://linux-hardware.org/?probe=06f7e4ef1b) | Sep 13, 2023 |
| Valve         | Jupiter                     | [5f155701b1](https://linux-hardware.org/?probe=5f155701b1) | Sep 13, 2023 |
| Valve         | Jupiter                     | [0ddb3447d3](https://linux-hardware.org/?probe=0ddb3447d3) | Sep 13, 2023 |
| Valve         | Jupiter                     | [bee3c23461](https://linux-hardware.org/?probe=bee3c23461) | Sep 12, 2023 |
| Valve         | Jupiter                     | [f6467570d4](https://linux-hardware.org/?probe=f6467570d4) | Sep 11, 2023 |
| Valve         | Jupiter                     | [e4939089f7](https://linux-hardware.org/?probe=e4939089f7) | Sep 11, 2023 |
| Valve         | Jupiter                     | [9f57588968](https://linux-hardware.org/?probe=9f57588968) | Sep 10, 2023 |
| Valve         | Jupiter                     | [3ae7c4440b](https://linux-hardware.org/?probe=3ae7c4440b) | Sep 10, 2023 |
| Valve         | Jupiter                     | [bbbc40365d](https://linux-hardware.org/?probe=bbbc40365d) | Sep 10, 2023 |
| Valve         | Jupiter                     | [9c09efc5b0](https://linux-hardware.org/?probe=9c09efc5b0) | Sep 09, 2023 |
| Valve         | Jupiter                     | [249a085da0](https://linux-hardware.org/?probe=249a085da0) | Sep 09, 2023 |
| Valve         | Jupiter                     | [6a818c55ff](https://linux-hardware.org/?probe=6a818c55ff) | Sep 09, 2023 |
| Valve         | Jupiter                     | [85a4fe79c2](https://linux-hardware.org/?probe=85a4fe79c2) | Sep 07, 2023 |
| Valve         | Jupiter                     | [1b3337e0ad](https://linux-hardware.org/?probe=1b3337e0ad) | Sep 07, 2023 |
| Valve         | Jupiter                     | [ec724ade59](https://linux-hardware.org/?probe=ec724ade59) | Sep 07, 2023 |
| Valve         | Jupiter                     | [d4ca58e970](https://linux-hardware.org/?probe=d4ca58e970) | Sep 07, 2023 |
| Valve         | Jupiter                     | [83b9205283](https://linux-hardware.org/?probe=83b9205283) | Sep 07, 2023 |
| Valve         | Jupiter                     | [f9b0d35f75](https://linux-hardware.org/?probe=f9b0d35f75) | Sep 06, 2023 |
| Valve         | Jupiter                     | [8209a15afb](https://linux-hardware.org/?probe=8209a15afb) | Sep 06, 2023 |
| MSI           | MS-7995                     | [3269e143a3](https://linux-hardware.org/?probe=3269e143a3) | Sep 06, 2023 |
| Valve         | Jupiter                     | [da71ec43ea](https://linux-hardware.org/?probe=da71ec43ea) | Sep 06, 2023 |
| Valve         | Jupiter                     | [8ae585f958](https://linux-hardware.org/?probe=8ae585f958) | Sep 05, 2023 |
| Valve         | Jupiter                     | [20541373d1](https://linux-hardware.org/?probe=20541373d1) | Sep 04, 2023 |
| Valve         | Jupiter                     | [fb306539b2](https://linux-hardware.org/?probe=fb306539b2) | Sep 04, 2023 |
| Valve         | Jupiter                     | [9e037b28bc](https://linux-hardware.org/?probe=9e037b28bc) | Sep 03, 2023 |
| Valve         | Jupiter                     | [e172cd5895](https://linux-hardware.org/?probe=e172cd5895) | Sep 03, 2023 |
| Valve         | Jupiter                     | [25261ec140](https://linux-hardware.org/?probe=25261ec140) | Sep 03, 2023 |
| Valve         | Jupiter                     | [413ea68e2d](https://linux-hardware.org/?probe=413ea68e2d) | Sep 03, 2023 |
| Valve         | Jupiter                     | [0f61122c7a](https://linux-hardware.org/?probe=0f61122c7a) | Sep 03, 2023 |
| Valve         | Jupiter                     | [6df7fe9dca](https://linux-hardware.org/?probe=6df7fe9dca) | Sep 02, 2023 |
| Valve         | Jupiter                     | [8e59296a5c](https://linux-hardware.org/?probe=8e59296a5c) | Sep 02, 2023 |
| Valve         | Jupiter                     | [df8dfd608f](https://linux-hardware.org/?probe=df8dfd608f) | Sep 02, 2023 |
| Valve         | Jupiter                     | [8313f463cf](https://linux-hardware.org/?probe=8313f463cf) | Sep 02, 2023 |
| Valve         | Jupiter                     | [fd0297e4e0](https://linux-hardware.org/?probe=fd0297e4e0) | Sep 01, 2023 |
| Valve         | Jupiter                     | [4a61e467d0](https://linux-hardware.org/?probe=4a61e467d0) | Aug 31, 2023 |
| Valve         | Jupiter                     | [acd834caed](https://linux-hardware.org/?probe=acd834caed) | Aug 30, 2023 |
| Valve         | Jupiter                     | [1e494aa7bf](https://linux-hardware.org/?probe=1e494aa7bf) | Aug 30, 2023 |
| Valve         | Jupiter                     | [ea71d4832d](https://linux-hardware.org/?probe=ea71d4832d) | Aug 29, 2023 |
| Valve         | Jupiter                     | [b23a3244d0](https://linux-hardware.org/?probe=b23a3244d0) | Aug 29, 2023 |
| Valve         | Jupiter                     | [fff7e4f400](https://linux-hardware.org/?probe=fff7e4f400) | Aug 29, 2023 |
| Valve         | Jupiter                     | [8a68ffe7b0](https://linux-hardware.org/?probe=8a68ffe7b0) | Aug 28, 2023 |
| Valve         | Jupiter                     | [fda85e8d96](https://linux-hardware.org/?probe=fda85e8d96) | Aug 27, 2023 |
| Valve         | Jupiter                     | [11f20f1134](https://linux-hardware.org/?probe=11f20f1134) | Aug 27, 2023 |
| Valve         | Jupiter                     | [4d894addd1](https://linux-hardware.org/?probe=4d894addd1) | Aug 27, 2023 |
| Valve         | Jupiter                     | [41823ead70](https://linux-hardware.org/?probe=41823ead70) | Aug 27, 2023 |
| Valve         | Jupiter                     | [3c1874890b](https://linux-hardware.org/?probe=3c1874890b) | Aug 26, 2023 |
| Valve         | Jupiter                     | [437c3eee58](https://linux-hardware.org/?probe=437c3eee58) | Aug 25, 2023 |
| Unknown       | X570 Phantom Gaming-ITX/... | [2956ecb7bf](https://linux-hardware.org/?probe=2956ecb7bf) | Aug 25, 2023 |
| Valve         | Jupiter                     | [98dce455d0](https://linux-hardware.org/?probe=98dce455d0) | Aug 24, 2023 |
| Valve         | Jupiter                     | [0b773e8e0c](https://linux-hardware.org/?probe=0b773e8e0c) | Aug 24, 2023 |
| Valve         | Jupiter                     | [904e60e2d7](https://linux-hardware.org/?probe=904e60e2d7) | Aug 23, 2023 |
| Valve         | Jupiter                     | [3439659413](https://linux-hardware.org/?probe=3439659413) | Aug 23, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 PRO ARP23P     | [0005c7836c](https://linux-hardware.org/?probe=0005c7836c) | Aug 22, 2023 |
| Valve         | Jupiter                     | [a83e32b89c](https://linux-hardware.org/?probe=a83e32b89c) | Aug 22, 2023 |
| Apple         | MacBookPro9,2               | [cc8234f447](https://linux-hardware.org/?probe=cc8234f447) | Aug 22, 2023 |
| Valve         | Jupiter                     | [57038f50cd](https://linux-hardware.org/?probe=57038f50cd) | Aug 20, 2023 |
| Valve         | Jupiter                     | [692495c520](https://linux-hardware.org/?probe=692495c520) | Aug 20, 2023 |
| Valve         | Jupiter                     | [5fd29eeb8a](https://linux-hardware.org/?probe=5fd29eeb8a) | Aug 20, 2023 |
| Valve         | Jupiter                     | [1d87714ed5](https://linux-hardware.org/?probe=1d87714ed5) | Aug 20, 2023 |
| Valve         | Jupiter                     | [0a6ed7bae4](https://linux-hardware.org/?probe=0a6ed7bae4) | Aug 19, 2023 |
| Valve         | Jupiter                     | [1e25ced64f](https://linux-hardware.org/?probe=1e25ced64f) | Aug 18, 2023 |
| Valve         | Jupiter                     | [b2c7c5cb9f](https://linux-hardware.org/?probe=b2c7c5cb9f) | Aug 17, 2023 |
| Valve         | Jupiter                     | [2981eb04ba](https://linux-hardware.org/?probe=2981eb04ba) | Aug 16, 2023 |
| Valve         | Jupiter                     | [013de8bfe6](https://linux-hardware.org/?probe=013de8bfe6) | Aug 16, 2023 |
| Valve         | Jupiter                     | [508611b16c](https://linux-hardware.org/?probe=508611b16c) | Aug 16, 2023 |
| Valve         | Jupiter                     | [590dbcbd7b](https://linux-hardware.org/?probe=590dbcbd7b) | Aug 15, 2023 |
| Valve         | Jupiter                     | [f52ceb7ab6](https://linux-hardware.org/?probe=f52ceb7ab6) | Aug 15, 2023 |
| Valve         | Jupiter                     | [ed10f1ef39](https://linux-hardware.org/?probe=ed10f1ef39) | Aug 13, 2023 |
| Valve         | Jupiter                     | [35eb2f8f2d](https://linux-hardware.org/?probe=35eb2f8f2d) | Aug 13, 2023 |
| Valve         | Jupiter                     | [441be5ab4d](https://linux-hardware.org/?probe=441be5ab4d) | Aug 13, 2023 |
| Valve         | Jupiter                     | [9fe8ae1836](https://linux-hardware.org/?probe=9fe8ae1836) | Aug 12, 2023 |
| Valve         | Jupiter                     | [b770999baf](https://linux-hardware.org/?probe=b770999baf) | Aug 12, 2023 |
| Valve         | Jupiter                     | [c34cb54bc8](https://linux-hardware.org/?probe=c34cb54bc8) | Aug 12, 2023 |
| Valve         | Jupiter                     | [61e105aa9d](https://linux-hardware.org/?probe=61e105aa9d) | Aug 12, 2023 |
| Valve         | Jupiter                     | [dbb797aa33](https://linux-hardware.org/?probe=dbb797aa33) | Aug 12, 2023 |
| Valve         | Jupiter                     | [3f6cd697d5](https://linux-hardware.org/?probe=3f6cd697d5) | Aug 12, 2023 |
| Valve         | Jupiter                     | [069bfd618c](https://linux-hardware.org/?probe=069bfd618c) | Aug 11, 2023 |
| Valve         | Jupiter                     | [dad1808c0d](https://linux-hardware.org/?probe=dad1808c0d) | Aug 11, 2023 |
| Valve         | Jupiter                     | [d88c707cfc](https://linux-hardware.org/?probe=d88c707cfc) | Aug 10, 2023 |
| Valve         | Jupiter                     | [613dc3eb7d](https://linux-hardware.org/?probe=613dc3eb7d) | Aug 09, 2023 |
| Valve         | Jupiter                     | [ff196a6c3d](https://linux-hardware.org/?probe=ff196a6c3d) | Aug 08, 2023 |
| Valve         | Jupiter                     | [f674ac251e](https://linux-hardware.org/?probe=f674ac251e) | Aug 06, 2023 |
| Valve         | Jupiter                     | [efbeafcf8f](https://linux-hardware.org/?probe=efbeafcf8f) | Aug 05, 2023 |
| Valve         | Jupiter                     | [6bf7b7dc2b](https://linux-hardware.org/?probe=6bf7b7dc2b) | Aug 05, 2023 |
| Valve         | Jupiter                     | [eadfa77bef](https://linux-hardware.org/?probe=eadfa77bef) | Aug 05, 2023 |
| Valve         | Jupiter                     | [96b8677500](https://linux-hardware.org/?probe=96b8677500) | Aug 05, 2023 |
| Valve         | Jupiter                     | [26e20fe1cf](https://linux-hardware.org/?probe=26e20fe1cf) | Aug 04, 2023 |
| Valve         | Jupiter                     | [0d684621df](https://linux-hardware.org/?probe=0d684621df) | Aug 03, 2023 |
| Valve         | Jupiter                     | [37400e051e](https://linux-hardware.org/?probe=37400e051e) | Aug 03, 2023 |
| Valve         | Jupiter                     | [f928feaff9](https://linux-hardware.org/?probe=f928feaff9) | Aug 02, 2023 |
| Anbernic      | Win600                      | [6d076e4bc9](https://linux-hardware.org/?probe=6d076e4bc9) | Aug 02, 2023 |
| Valve         | Jupiter                     | [896569d1d6](https://linux-hardware.org/?probe=896569d1d6) | Aug 01, 2023 |
| Valve         | Jupiter                     | [02eeabe071](https://linux-hardware.org/?probe=02eeabe071) | Aug 01, 2023 |
| Valve         | Jupiter                     | [6eb487950f](https://linux-hardware.org/?probe=6eb487950f) | Aug 01, 2023 |
| Valve         | Jupiter                     | [6ea9f908cb](https://linux-hardware.org/?probe=6ea9f908cb) | Aug 01, 2023 |
| Valve         | Jupiter                     | [2c25ad9f3a](https://linux-hardware.org/?probe=2c25ad9f3a) | Jul 31, 2023 |
| Valve         | Jupiter                     | [e47da31f03](https://linux-hardware.org/?probe=e47da31f03) | Jul 31, 2023 |
| Valve         | Jupiter                     | [3bc193bd23](https://linux-hardware.org/?probe=3bc193bd23) | Jul 30, 2023 |
| Valve         | Jupiter                     | [db58810c8c](https://linux-hardware.org/?probe=db58810c8c) | Jul 30, 2023 |
| Valve         | Jupiter                     | [82e4fa2fbc](https://linux-hardware.org/?probe=82e4fa2fbc) | Jul 30, 2023 |
| Valve         | Jupiter                     | [9a37bd442d](https://linux-hardware.org/?probe=9a37bd442d) | Jul 30, 2023 |
| Valve         | Jupiter                     | [a3d0515a92](https://linux-hardware.org/?probe=a3d0515a92) | Jul 29, 2023 |
| Valve         | Jupiter                     | [ff714f1791](https://linux-hardware.org/?probe=ff714f1791) | Jul 28, 2023 |
| Valve         | Jupiter                     | [3afdfaee86](https://linux-hardware.org/?probe=3afdfaee86) | Jul 28, 2023 |
| Valve         | Jupiter                     | [8b17f4e7f8](https://linux-hardware.org/?probe=8b17f4e7f8) | Jul 28, 2023 |
| Valve         | Jupiter                     | [f05b93c2c5](https://linux-hardware.org/?probe=f05b93c2c5) | Jul 28, 2023 |
| Valve         | Jupiter                     | [fc294ac015](https://linux-hardware.org/?probe=fc294ac015) | Jul 27, 2023 |
| Valve         | Jupiter                     | [7ca21b7b46](https://linux-hardware.org/?probe=7ca21b7b46) | Jul 26, 2023 |
| Valve         | Jupiter                     | [46476d31e0](https://linux-hardware.org/?probe=46476d31e0) | Jul 26, 2023 |
| Valve         | Jupiter                     | [ece0a7a538](https://linux-hardware.org/?probe=ece0a7a538) | Jul 26, 2023 |
| Valve         | Jupiter                     | [1adda13639](https://linux-hardware.org/?probe=1adda13639) | Jul 26, 2023 |
| Valve         | Jupiter                     | [8ba9103155](https://linux-hardware.org/?probe=8ba9103155) | Jul 26, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [8cde0390c4](https://linux-hardware.org/?probe=8cde0390c4) | Jul 26, 2023 |
| Valve         | Jupiter                     | [bebbacfd8c](https://linux-hardware.org/?probe=bebbacfd8c) | Jul 25, 2023 |
| Valve         | Jupiter                     | [72bde0bc85](https://linux-hardware.org/?probe=72bde0bc85) | Jul 24, 2023 |
| Valve         | Jupiter                     | [4e9a981c7b](https://linux-hardware.org/?probe=4e9a981c7b) | Jul 24, 2023 |
| Valve         | Jupiter                     | [cdf83d0eb8](https://linux-hardware.org/?probe=cdf83d0eb8) | Jul 24, 2023 |
| Valve         | Jupiter                     | [59b11daded](https://linux-hardware.org/?probe=59b11daded) | Jul 24, 2023 |
| Valve         | Jupiter                     | [0e8e6ce1ae](https://linux-hardware.org/?probe=0e8e6ce1ae) | Jul 22, 2023 |
| Valve         | Jupiter                     | [fa8db9f24a](https://linux-hardware.org/?probe=fa8db9f24a) | Jul 22, 2023 |
| Valve         | Jupiter                     | [00ad68f9ea](https://linux-hardware.org/?probe=00ad68f9ea) | Jul 22, 2023 |
| Apple         | MacBookPro8,1               | [75fbfdd46a](https://linux-hardware.org/?probe=75fbfdd46a) | Jul 21, 2023 |
| Valve         | Jupiter                     | [4172f7fd39](https://linux-hardware.org/?probe=4172f7fd39) | Jul 21, 2023 |
| Valve         | Jupiter                     | [4551de298d](https://linux-hardware.org/?probe=4551de298d) | Jul 21, 2023 |
| Valve         | Jupiter                     | [db220d13d6](https://linux-hardware.org/?probe=db220d13d6) | Jul 20, 2023 |
| Valve         | Jupiter                     | [d8b50a466c](https://linux-hardware.org/?probe=d8b50a466c) | Jul 19, 2023 |
| Valve         | Jupiter                     | [6ddba888cf](https://linux-hardware.org/?probe=6ddba888cf) | Jul 19, 2023 |
| Valve         | Jupiter                     | [3abdfed88b](https://linux-hardware.org/?probe=3abdfed88b) | Jul 18, 2023 |
| Valve         | Jupiter                     | [4beb3117df](https://linux-hardware.org/?probe=4beb3117df) | Jul 18, 2023 |
| Valve         | Jupiter                     | [f5c7022902](https://linux-hardware.org/?probe=f5c7022902) | Jul 18, 2023 |
| Valve         | Jupiter                     | [d5af3b1fe2](https://linux-hardware.org/?probe=d5af3b1fe2) | Jul 17, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [7278a4ed50](https://linux-hardware.org/?probe=7278a4ed50) | Jul 16, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [9b0f9e2480](https://linux-hardware.org/?probe=9b0f9e2480) | Jul 16, 2023 |
| Valve         | Jupiter                     | [5151b41560](https://linux-hardware.org/?probe=5151b41560) | Jul 15, 2023 |
| Valve         | Jupiter                     | [ce85b9f39b](https://linux-hardware.org/?probe=ce85b9f39b) | Jul 15, 2023 |
| Valve         | Jupiter                     | [095261aa8d](https://linux-hardware.org/?probe=095261aa8d) | Jul 13, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH7 ... | [6277c7ff61](https://linux-hardware.org/?probe=6277c7ff61) | Jul 13, 2023 |
| Acer          | Nitro AN515-53              | [368352c126](https://linux-hardware.org/?probe=368352c126) | Jul 12, 2023 |
| Valve         | Jupiter                     | [110622383d](https://linux-hardware.org/?probe=110622383d) | Jul 11, 2023 |
| Valve         | Jupiter                     | [822aabfc22](https://linux-hardware.org/?probe=822aabfc22) | Jul 11, 2023 |
| Valve         | Jupiter                     | [5d55bf223d](https://linux-hardware.org/?probe=5d55bf223d) | Jul 10, 2023 |
| Valve         | Jupiter                     | [cd94be4fe3](https://linux-hardware.org/?probe=cd94be4fe3) | Jul 10, 2023 |
| Valve         | Jupiter                     | [969616fa6e](https://linux-hardware.org/?probe=969616fa6e) | Jul 09, 2023 |
| Valve         | Jupiter                     | [77fccecf08](https://linux-hardware.org/?probe=77fccecf08) | Jul 09, 2023 |
| Monster       | ABRA A5 V17.3               | [2b65146842](https://linux-hardware.org/?probe=2b65146842) | Jul 08, 2023 |
| Valve         | Jupiter                     | [b2fd5a2c42](https://linux-hardware.org/?probe=b2fd5a2c42) | Jul 08, 2023 |
| Valve         | Jupiter                     | [7fc70add85](https://linux-hardware.org/?probe=7fc70add85) | Jul 08, 2023 |
| Valve         | Jupiter                     | [fd3d1bc540](https://linux-hardware.org/?probe=fd3d1bc540) | Jul 08, 2023 |
| Valve         | Jupiter                     | [07aa881213](https://linux-hardware.org/?probe=07aa881213) | Jul 07, 2023 |
| Valve         | Jupiter                     | [db404b2507](https://linux-hardware.org/?probe=db404b2507) | Jul 06, 2023 |
| Valve         | Jupiter                     | [6400b6b07c](https://linux-hardware.org/?probe=6400b6b07c) | Jul 06, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [4ff583eb14](https://linux-hardware.org/?probe=4ff583eb14) | Jul 05, 2023 |
| Valve         | Jupiter                     | [dfb0bd07f1](https://linux-hardware.org/?probe=dfb0bd07f1) | Jul 05, 2023 |
| Valve         | Jupiter                     | [d62c8c81d4](https://linux-hardware.org/?probe=d62c8c81d4) | Jul 04, 2023 |
| Valve         | Jupiter                     | [a39f1dd1ad](https://linux-hardware.org/?probe=a39f1dd1ad) | Jul 04, 2023 |
| Valve         | Jupiter                     | [8b40767026](https://linux-hardware.org/?probe=8b40767026) | Jul 04, 2023 |
| Dell          | Inspiron 1545               | [5634e7a412](https://linux-hardware.org/?probe=5634e7a412) | Jul 03, 2023 |
| Valve         | Jupiter                     | [a4a8cc1e65](https://linux-hardware.org/?probe=a4a8cc1e65) | Jul 03, 2023 |
| Valve         | Jupiter                     | [fb8590ef39](https://linux-hardware.org/?probe=fb8590ef39) | Jul 03, 2023 |
| Valve         | Jupiter                     | [7863106765](https://linux-hardware.org/?probe=7863106765) | Jul 02, 2023 |
| Valve         | Jupiter                     | [7f3a0ce58f](https://linux-hardware.org/?probe=7f3a0ce58f) | Jul 02, 2023 |
| Valve         | Jupiter                     | [d6be2a190b](https://linux-hardware.org/?probe=d6be2a190b) | Jul 01, 2023 |
| Valve         | Jupiter                     | [5628897658](https://linux-hardware.org/?probe=5628897658) | Jul 01, 2023 |
| Valve         | Jupiter                     | [86984d2e19](https://linux-hardware.org/?probe=86984d2e19) | Jun 30, 2023 |
| Valve         | Jupiter                     | [cd28af9419](https://linux-hardware.org/?probe=cd28af9419) | Jun 30, 2023 |
| Valve         | Jupiter                     | [89d751f07f](https://linux-hardware.org/?probe=89d751f07f) | Jun 30, 2023 |
| Valve         | Jupiter                     | [d8a4613446](https://linux-hardware.org/?probe=d8a4613446) | Jun 29, 2023 |
| Valve         | Jupiter                     | [f6d3a1e787](https://linux-hardware.org/?probe=f6d3a1e787) | Jun 27, 2023 |
| Valve         | Jupiter                     | [0817dd25ff](https://linux-hardware.org/?probe=0817dd25ff) | Jun 27, 2023 |
| Valve         | Jupiter                     | [650287f33d](https://linux-hardware.org/?probe=650287f33d) | Jun 27, 2023 |
| Valve         | Jupiter                     | [563dc53040](https://linux-hardware.org/?probe=563dc53040) | Jun 27, 2023 |
| Valve         | Jupiter                     | [9262a02e0e](https://linux-hardware.org/?probe=9262a02e0e) | Jun 26, 2023 |
| Valve         | Jupiter                     | [5115b6e139](https://linux-hardware.org/?probe=5115b6e139) | Jun 26, 2023 |
| Sony          | VGN-Z520N                   | [d1b8aa8d53](https://linux-hardware.org/?probe=d1b8aa8d53) | Jun 25, 2023 |
| Sony          | VGN-Z520N                   | [093ca7f305](https://linux-hardware.org/?probe=093ca7f305) | Jun 25, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [e10aa58dda](https://linux-hardware.org/?probe=e10aa58dda) | Jun 24, 2023 |
| Valve         | Jupiter                     | [20678f1d9f](https://linux-hardware.org/?probe=20678f1d9f) | Jun 24, 2023 |
| Valve         | Jupiter                     | [ba0343b607](https://linux-hardware.org/?probe=ba0343b607) | Jun 24, 2023 |
| Valve         | Jupiter                     | [a373e679ae](https://linux-hardware.org/?probe=a373e679ae) | Jun 23, 2023 |
| Valve         | Jupiter                     | [d8f3d630c3](https://linux-hardware.org/?probe=d8f3d630c3) | Jun 23, 2023 |
| Valve         | Jupiter                     | [4da7495332](https://linux-hardware.org/?probe=4da7495332) | Jun 23, 2023 |
| Valve         | Jupiter                     | [73e80c2b31](https://linux-hardware.org/?probe=73e80c2b31) | Jun 23, 2023 |
| Valve         | Jupiter                     | [196d127382](https://linux-hardware.org/?probe=196d127382) | Jun 23, 2023 |
| Valve         | Jupiter                     | [329518de92](https://linux-hardware.org/?probe=329518de92) | Jun 22, 2023 |
| Valve         | Jupiter                     | [576a62665a](https://linux-hardware.org/?probe=576a62665a) | Jun 20, 2023 |
| Dell          | Venue 11 Pro 7140           | [f9bf8920f7](https://linux-hardware.org/?probe=f9bf8920f7) | Jun 20, 2023 |
| Valve         | Jupiter                     | [f4e47bb83e](https://linux-hardware.org/?probe=f4e47bb83e) | Jun 20, 2023 |
| Dell          | Venue 11 Pro 7140           | [c436287876](https://linux-hardware.org/?probe=c436287876) | Jun 20, 2023 |
| Valve         | Jupiter                     | [6858460566](https://linux-hardware.org/?probe=6858460566) | Jun 19, 2023 |
| Valve         | Jupiter                     | [9da2af6fe5](https://linux-hardware.org/?probe=9da2af6fe5) | Jun 18, 2023 |
| Dell          | Inspiron 5535               | [88a1d18ea0](https://linux-hardware.org/?probe=88a1d18ea0) | Jun 17, 2023 |
| Valve         | Jupiter                     | [b684643576](https://linux-hardware.org/?probe=b684643576) | Jun 16, 2023 |
| Valve         | Jupiter                     | [28dc5a83fe](https://linux-hardware.org/?probe=28dc5a83fe) | Jun 16, 2023 |
| Valve         | Jupiter                     | [29869b2464](https://linux-hardware.org/?probe=29869b2464) | Jun 15, 2023 |
| Valve         | Jupiter                     | [bdd96d41a7](https://linux-hardware.org/?probe=bdd96d41a7) | Jun 15, 2023 |
| Valve         | Jupiter                     | [dcf3ae5611](https://linux-hardware.org/?probe=dcf3ae5611) | Jun 15, 2023 |
| Valve         | Jupiter                     | [d68b6167ae](https://linux-hardware.org/?probe=d68b6167ae) | Jun 14, 2023 |
| Valve         | Jupiter                     | [f4bace1d39](https://linux-hardware.org/?probe=f4bace1d39) | Jun 13, 2023 |
| Valve         | Jupiter                     | [19d9c2a44a](https://linux-hardware.org/?probe=19d9c2a44a) | Jun 11, 2023 |
| Valve         | Jupiter                     | [b7ffc34483](https://linux-hardware.org/?probe=b7ffc34483) | Jun 11, 2023 |
| Valve         | Jupiter                     | [8c9765a31c](https://linux-hardware.org/?probe=8c9765a31c) | Jun 11, 2023 |
| Valve         | Jupiter                     | [c7e458735d](https://linux-hardware.org/?probe=c7e458735d) | Jun 11, 2023 |
| Valve         | Jupiter                     | [3e31827529](https://linux-hardware.org/?probe=3e31827529) | Jun 11, 2023 |
| Dell          | Precision 5520              | [bcbd324c4b](https://linux-hardware.org/?probe=bcbd324c4b) | Jun 11, 2023 |
| Dell          | Precision 5520              | [ab408edcbd](https://linux-hardware.org/?probe=ab408edcbd) | Jun 11, 2023 |
| Valve         | Jupiter                     | [bcc3eb4ffe](https://linux-hardware.org/?probe=bcc3eb4ffe) | Jun 11, 2023 |
| Valve         | Jupiter                     | [fc47f86c91](https://linux-hardware.org/?probe=fc47f86c91) | Jun 11, 2023 |
| Valve         | Jupiter                     | [d276b58f38](https://linux-hardware.org/?probe=d276b58f38) | Jun 10, 2023 |
| Valve         | Jupiter                     | [d2df298764](https://linux-hardware.org/?probe=d2df298764) | Jun 10, 2023 |
| Valve         | Jupiter                     | [c1e32f24ee](https://linux-hardware.org/?probe=c1e32f24ee) | Jun 10, 2023 |
| Valve         | Jupiter                     | [fab558feb4](https://linux-hardware.org/?probe=fab558feb4) | Jun 10, 2023 |
| Valve         | Jupiter                     | [7a36bdb92a](https://linux-hardware.org/?probe=7a36bdb92a) | Jun 09, 2023 |
| Valve         | Jupiter                     | [628ee9ac88](https://linux-hardware.org/?probe=628ee9ac88) | Jun 09, 2023 |
| Valve         | Jupiter                     | [06f5f2068f](https://linux-hardware.org/?probe=06f5f2068f) | Jun 09, 2023 |
| ASUSTek       | S400CA                      | [25c1d47331](https://linux-hardware.org/?probe=25c1d47331) | Jun 08, 2023 |
| Valve         | Jupiter                     | [b23bc1dc48](https://linux-hardware.org/?probe=b23bc1dc48) | Jun 08, 2023 |
| Valve         | Jupiter                     | [f41491d8ac](https://linux-hardware.org/?probe=f41491d8ac) | Jun 08, 2023 |
| Valve         | Jupiter                     | [27771c5ea8](https://linux-hardware.org/?probe=27771c5ea8) | Jun 07, 2023 |
| Valve         | Jupiter                     | [7e07a9c15d](https://linux-hardware.org/?probe=7e07a9c15d) | Jun 07, 2023 |
| Valve         | Jupiter                     | [2a6ad8df3c](https://linux-hardware.org/?probe=2a6ad8df3c) | Jun 07, 2023 |
| Valve         | Jupiter                     | [99a7a5bd6e](https://linux-hardware.org/?probe=99a7a5bd6e) | Jun 06, 2023 |
| Valve         | Jupiter                     | [0d22bd5256](https://linux-hardware.org/?probe=0d22bd5256) | Jun 06, 2023 |
| Valve         | Jupiter                     | [6e40377338](https://linux-hardware.org/?probe=6e40377338) | Jun 06, 2023 |
| Valve         | Jupiter                     | [4e212c07cc](https://linux-hardware.org/?probe=4e212c07cc) | Jun 06, 2023 |
| Valve         | Jupiter                     | [27fda0a97e](https://linux-hardware.org/?probe=27fda0a97e) | Jun 05, 2023 |
| Valve         | Jupiter                     | [aa2925f22f](https://linux-hardware.org/?probe=aa2925f22f) | Jun 05, 2023 |
| Valve         | Jupiter                     | [9c11d12e34](https://linux-hardware.org/?probe=9c11d12e34) | Jun 04, 2023 |
| Valve         | Jupiter                     | [0c81d929ca](https://linux-hardware.org/?probe=0c81d929ca) | Jun 04, 2023 |
| GPD           | G1619-04                    | [fcc919c1c2](https://linux-hardware.org/?probe=fcc919c1c2) | Jun 03, 2023 |
| Valve         | Jupiter                     | [d21eb9432c](https://linux-hardware.org/?probe=d21eb9432c) | Jun 03, 2023 |
| Valve         | Jupiter                     | [fdfee4fc99](https://linux-hardware.org/?probe=fdfee4fc99) | Jun 03, 2023 |
| Valve         | Jupiter                     | [8c33873318](https://linux-hardware.org/?probe=8c33873318) | Jun 03, 2023 |
| Valve         | Jupiter                     | [cf26028872](https://linux-hardware.org/?probe=cf26028872) | Jun 03, 2023 |
| Valve         | Jupiter                     | [e7409e91d9](https://linux-hardware.org/?probe=e7409e91d9) | Jun 03, 2023 |
| Valve         | Jupiter                     | [7a616b305a](https://linux-hardware.org/?probe=7a616b305a) | Jun 02, 2023 |
| Valve         | Jupiter                     | [d1fec35ece](https://linux-hardware.org/?probe=d1fec35ece) | Jun 02, 2023 |
| Valve         | Jupiter                     | [49135876a9](https://linux-hardware.org/?probe=49135876a9) | Jun 02, 2023 |
| Valve         | Jupiter                     | [762287e555](https://linux-hardware.org/?probe=762287e555) | Jun 02, 2023 |
| Valve         | Jupiter                     | [6c04c9e646](https://linux-hardware.org/?probe=6c04c9e646) | Jun 02, 2023 |
| Valve         | Jupiter                     | [ab56e219fd](https://linux-hardware.org/?probe=ab56e219fd) | Jun 02, 2023 |
| GPD           | G1619-01                    | [ca7d008d32](https://linux-hardware.org/?probe=ca7d008d32) | Jun 02, 2023 |
| Valve         | Jupiter                     | [a33a5c45ac](https://linux-hardware.org/?probe=a33a5c45ac) | Jun 02, 2023 |
| Valve         | Jupiter                     | [30a2370d6e](https://linux-hardware.org/?probe=30a2370d6e) | Jun 01, 2023 |
| Valve         | Jupiter                     | [ec5403a37e](https://linux-hardware.org/?probe=ec5403a37e) | Jun 01, 2023 |
| Valve         | Jupiter                     | [06000e9b0e](https://linux-hardware.org/?probe=06000e9b0e) | Jun 01, 2023 |
| Valve         | Jupiter                     | [175e48a789](https://linux-hardware.org/?probe=175e48a789) | May 31, 2023 |
| Valve         | Jupiter                     | [f2f00bcfcc](https://linux-hardware.org/?probe=f2f00bcfcc) | May 29, 2023 |
| Valve         | Jupiter                     | [e47423fe9c](https://linux-hardware.org/?probe=e47423fe9c) | May 29, 2023 |
| Valve         | Jupiter                     | [c1d10ab583](https://linux-hardware.org/?probe=c1d10ab583) | May 29, 2023 |
| Valve         | Jupiter                     | [e6e97426e3](https://linux-hardware.org/?probe=e6e97426e3) | May 29, 2023 |
| Valve         | Jupiter                     | [66bff91fdb](https://linux-hardware.org/?probe=66bff91fdb) | May 28, 2023 |
| GPD           | G1619-04                    | [49b9e4edd3](https://linux-hardware.org/?probe=49b9e4edd3) | May 28, 2023 |
| GPD           | G1619-04                    | [caa6b5459d](https://linux-hardware.org/?probe=caa6b5459d) | May 28, 2023 |
| Valve         | Jupiter                     | [242a13f378](https://linux-hardware.org/?probe=242a13f378) | May 27, 2023 |
| HP            | 15                          | [df11918bf5](https://linux-hardware.org/?probe=df11918bf5) | May 26, 2023 |
| Valve         | Jupiter                     | [84756c6406](https://linux-hardware.org/?probe=84756c6406) | May 25, 2023 |
| Valve         | Jupiter                     | [a933a0ea14](https://linux-hardware.org/?probe=a933a0ea14) | May 24, 2023 |
| Valve         | Jupiter                     | [117db8031d](https://linux-hardware.org/?probe=117db8031d) | May 24, 2023 |
| Valve         | Jupiter                     | [3af0dc2cce](https://linux-hardware.org/?probe=3af0dc2cce) | May 24, 2023 |
| Valve         | Jupiter                     | [fd4190f3d7](https://linux-hardware.org/?probe=fd4190f3d7) | May 24, 2023 |
| Valve         | Jupiter                     | [223ab4f15c](https://linux-hardware.org/?probe=223ab4f15c) | May 23, 2023 |
| Dell          | Precision 7510              | [0b6f0b96e9](https://linux-hardware.org/?probe=0b6f0b96e9) | May 23, 2023 |
| Valve         | Jupiter                     | [0213edfe88](https://linux-hardware.org/?probe=0213edfe88) | May 22, 2023 |
| Valve         | Jupiter                     | [c7f1f9d62a](https://linux-hardware.org/?probe=c7f1f9d62a) | May 22, 2023 |
| Valve         | Jupiter                     | [0a03a5a40a](https://linux-hardware.org/?probe=0a03a5a40a) | May 22, 2023 |
| Valve         | Jupiter                     | [f59c4fec2f](https://linux-hardware.org/?probe=f59c4fec2f) | May 20, 2023 |
| Valve         | Jupiter                     | [c6d16a4831](https://linux-hardware.org/?probe=c6d16a4831) | May 20, 2023 |
| Valve         | Jupiter                     | [cf5c419d13](https://linux-hardware.org/?probe=cf5c419d13) | May 20, 2023 |
| Valve         | Jupiter                     | [6b5b728c7e](https://linux-hardware.org/?probe=6b5b728c7e) | May 20, 2023 |
| Valve         | Jupiter                     | [52c421fe83](https://linux-hardware.org/?probe=52c421fe83) | May 20, 2023 |
| Valve         | Jupiter                     | [7d600a9c24](https://linux-hardware.org/?probe=7d600a9c24) | May 19, 2023 |
| Valve         | Jupiter                     | [b57c75520f](https://linux-hardware.org/?probe=b57c75520f) | May 19, 2023 |
| Valve         | Jupiter                     | [0de060a93f](https://linux-hardware.org/?probe=0de060a93f) | May 18, 2023 |
| Valve         | Jupiter                     | [18a67acdf1](https://linux-hardware.org/?probe=18a67acdf1) | May 18, 2023 |
| Valve         | Jupiter                     | [c16624e321](https://linux-hardware.org/?probe=c16624e321) | May 17, 2023 |
| Valve         | Jupiter                     | [a4cdb81f46](https://linux-hardware.org/?probe=a4cdb81f46) | May 16, 2023 |
| Valve         | Jupiter                     | [71e3add4b4](https://linux-hardware.org/?probe=71e3add4b4) | May 16, 2023 |
| Valve         | Jupiter                     | [6c64da33ef](https://linux-hardware.org/?probe=6c64da33ef) | May 16, 2023 |
| Valve         | Jupiter                     | [dca8b16469](https://linux-hardware.org/?probe=dca8b16469) | May 15, 2023 |
| Valve         | Jupiter                     | [6df9aa02d5](https://linux-hardware.org/?probe=6df9aa02d5) | May 14, 2023 |
| Valve         | Jupiter                     | [a130b1b1d0](https://linux-hardware.org/?probe=a130b1b1d0) | May 14, 2023 |
| Valve         | Jupiter                     | [9a9b88a86c](https://linux-hardware.org/?probe=9a9b88a86c) | May 14, 2023 |
| Valve         | Jupiter                     | [af70e39629](https://linux-hardware.org/?probe=af70e39629) | May 14, 2023 |
| Valve         | Jupiter                     | [6d8b04de33](https://linux-hardware.org/?probe=6d8b04de33) | May 13, 2023 |
| Valve         | Jupiter                     | [02275a9849](https://linux-hardware.org/?probe=02275a9849) | May 13, 2023 |
| Valve         | Jupiter                     | [d19fe8d808](https://linux-hardware.org/?probe=d19fe8d808) | May 13, 2023 |
| Valve         | Jupiter                     | [abf57f2578](https://linux-hardware.org/?probe=abf57f2578) | May 13, 2023 |
| Valve         | Jupiter                     | [49d110c5d2](https://linux-hardware.org/?probe=49d110c5d2) | May 13, 2023 |
| Valve         | Jupiter                     | [a9795ddfa7](https://linux-hardware.org/?probe=a9795ddfa7) | May 13, 2023 |
| Valve         | Jupiter                     | [0b26ce1a71](https://linux-hardware.org/?probe=0b26ce1a71) | May 12, 2023 |
| Valve         | Jupiter                     | [1a3b8caff1](https://linux-hardware.org/?probe=1a3b8caff1) | May 12, 2023 |
| Valve         | Jupiter                     | [9d7e434968](https://linux-hardware.org/?probe=9d7e434968) | May 12, 2023 |
| Valve         | Jupiter                     | [4b2b4bf799](https://linux-hardware.org/?probe=4b2b4bf799) | May 12, 2023 |
| Valve         | Jupiter                     | [01ee28074b](https://linux-hardware.org/?probe=01ee28074b) | May 12, 2023 |
| Valve         | Jupiter                     | [e89eb08b8d](https://linux-hardware.org/?probe=e89eb08b8d) | May 11, 2023 |
| Valve         | Jupiter                     | [ec8ac0aafd](https://linux-hardware.org/?probe=ec8ac0aafd) | May 11, 2023 |
| Valve         | Jupiter                     | [706456af07](https://linux-hardware.org/?probe=706456af07) | May 11, 2023 |
| Valve         | Jupiter                     | [8a4a20096f](https://linux-hardware.org/?probe=8a4a20096f) | May 11, 2023 |
| Valve         | Jupiter                     | [5bfb32e683](https://linux-hardware.org/?probe=5bfb32e683) | May 11, 2023 |
| Valve         | Jupiter                     | [1285d2af93](https://linux-hardware.org/?probe=1285d2af93) | May 10, 2023 |
| Valve         | Jupiter                     | [e5c9c71313](https://linux-hardware.org/?probe=e5c9c71313) | May 10, 2023 |
| Valve         | Jupiter                     | [21471afcae](https://linux-hardware.org/?probe=21471afcae) | May 09, 2023 |
| Valve         | Jupiter                     | [1324443418](https://linux-hardware.org/?probe=1324443418) | May 09, 2023 |
| Valve         | Jupiter                     | [8cc543c6af](https://linux-hardware.org/?probe=8cc543c6af) | May 09, 2023 |
| Valve         | Jupiter                     | [08aba8925e](https://linux-hardware.org/?probe=08aba8925e) | May 08, 2023 |
| Valve         | Jupiter                     | [e6397e7f9f](https://linux-hardware.org/?probe=e6397e7f9f) | May 08, 2023 |
| Valve         | Jupiter                     | [270eaa3e12](https://linux-hardware.org/?probe=270eaa3e12) | May 07, 2023 |
| Valve         | Jupiter                     | [6769250b94](https://linux-hardware.org/?probe=6769250b94) | May 07, 2023 |
| Valve         | Jupiter                     | [d0eb83c0af](https://linux-hardware.org/?probe=d0eb83c0af) | May 07, 2023 |
| Biostar       | A320MH                      | [5b240feaed](https://linux-hardware.org/?probe=5b240feaed) | May 07, 2023 |
| Valve         | Jupiter                     | [2854045b14](https://linux-hardware.org/?probe=2854045b14) | May 07, 2023 |
| Valve         | Jupiter                     | [17b055eca4](https://linux-hardware.org/?probe=17b055eca4) | May 07, 2023 |
| Valve         | Jupiter                     | [55acf244c5](https://linux-hardware.org/?probe=55acf244c5) | May 06, 2023 |
| Valve         | Jupiter                     | [42abbac529](https://linux-hardware.org/?probe=42abbac529) | May 05, 2023 |
| Valve         | Jupiter                     | [50656044eb](https://linux-hardware.org/?probe=50656044eb) | May 05, 2023 |
| Valve         | Jupiter                     | [2a9ff9e061](https://linux-hardware.org/?probe=2a9ff9e061) | May 05, 2023 |
| Valve         | Jupiter                     | [04f1f6146c](https://linux-hardware.org/?probe=04f1f6146c) | May 04, 2023 |
| Valve         | Jupiter                     | [1f41754528](https://linux-hardware.org/?probe=1f41754528) | May 03, 2023 |
| Valve         | Jupiter                     | [c2e70cab2c](https://linux-hardware.org/?probe=c2e70cab2c) | May 03, 2023 |
| Valve         | Jupiter                     | [0a6a9a6675](https://linux-hardware.org/?probe=0a6a9a6675) | May 03, 2023 |
| MSI           | GF62 7RE                    | [f238bed93a](https://linux-hardware.org/?probe=f238bed93a) | May 03, 2023 |
| Valve         | Jupiter                     | [c6e5e310b9](https://linux-hardware.org/?probe=c6e5e310b9) | May 02, 2023 |
| Valve         | Jupiter                     | [388caab99a](https://linux-hardware.org/?probe=388caab99a) | May 02, 2023 |
| Valve         | Jupiter                     | [206f95ee6f](https://linux-hardware.org/?probe=206f95ee6f) | May 02, 2023 |
| Valve         | Jupiter                     | [eab445bfa5](https://linux-hardware.org/?probe=eab445bfa5) | May 01, 2023 |
| Valve         | Jupiter                     | [09f9cbd392](https://linux-hardware.org/?probe=09f9cbd392) | May 01, 2023 |
| Valve         | Jupiter                     | [9d8a549c47](https://linux-hardware.org/?probe=9d8a549c47) | May 01, 2023 |
| Valve         | Jupiter                     | [0494e0759f](https://linux-hardware.org/?probe=0494e0759f) | May 01, 2023 |
| Valve         | Jupiter                     | [3bee1a3271](https://linux-hardware.org/?probe=3bee1a3271) | Apr 30, 2023 |
| Valve         | Jupiter                     | [5645561cbb](https://linux-hardware.org/?probe=5645561cbb) | Apr 30, 2023 |
| Valve         | Jupiter                     | [23d976b25f](https://linux-hardware.org/?probe=23d976b25f) | Apr 30, 2023 |
| Valve         | Jupiter                     | [183d16708b](https://linux-hardware.org/?probe=183d16708b) | Apr 29, 2023 |
| Valve         | Jupiter                     | [cf4ff7fcb1](https://linux-hardware.org/?probe=cf4ff7fcb1) | Apr 29, 2023 |
| Lenovo        | Legion 5 17IMH05H 81Y8      | [d435f7df68](https://linux-hardware.org/?probe=d435f7df68) | Apr 29, 2023 |
| Valve         | Jupiter                     | [0958caf898](https://linux-hardware.org/?probe=0958caf898) | Apr 27, 2023 |
| Valve         | Jupiter                     | [72f64e795a](https://linux-hardware.org/?probe=72f64e795a) | Apr 27, 2023 |
| Valve         | Jupiter                     | [4066c253b5](https://linux-hardware.org/?probe=4066c253b5) | Apr 27, 2023 |
| Valve         | Jupiter                     | [823e1bb624](https://linux-hardware.org/?probe=823e1bb624) | Apr 27, 2023 |
| Valve         | Jupiter                     | [ff3e33e935](https://linux-hardware.org/?probe=ff3e33e935) | Apr 26, 2023 |
| Valve         | Jupiter                     | [7ab7e066cf](https://linux-hardware.org/?probe=7ab7e066cf) | Apr 26, 2023 |
| Valve         | Jupiter                     | [9b44e9bc2c](https://linux-hardware.org/?probe=9b44e9bc2c) | Apr 25, 2023 |
| Valve         | Jupiter                     | [7c7421ffeb](https://linux-hardware.org/?probe=7c7421ffeb) | Apr 25, 2023 |
| Valve         | Jupiter                     | [78a3abdc19](https://linux-hardware.org/?probe=78a3abdc19) | Apr 25, 2023 |
| Valve         | Jupiter                     | [7501c5e0e4](https://linux-hardware.org/?probe=7501c5e0e4) | Apr 23, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | [bee909cfcd](https://linux-hardware.org/?probe=bee909cfcd) | Apr 23, 2023 |
| Valve         | Jupiter                     | [637dccb4d9](https://linux-hardware.org/?probe=637dccb4d9) | Apr 23, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | [c101faa12e](https://linux-hardware.org/?probe=c101faa12e) | Apr 23, 2023 |
| Valve         | Jupiter                     | [1ec068394a](https://linux-hardware.org/?probe=1ec068394a) | Apr 23, 2023 |
| Valve         | Jupiter                     | [b34ccafbdf](https://linux-hardware.org/?probe=b34ccafbdf) | Apr 23, 2023 |
| Valve         | Jupiter                     | [ff8440808f](https://linux-hardware.org/?probe=ff8440808f) | Apr 22, 2023 |
| Valve         | Jupiter                     | [0d6278dd3a](https://linux-hardware.org/?probe=0d6278dd3a) | Apr 22, 2023 |
| Valve         | Jupiter                     | [9091e5efc9](https://linux-hardware.org/?probe=9091e5efc9) | Apr 21, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/SteamOS/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| SteamOS 3.5.7                | 209       | 13.14%  |
| SteamOS 3.4.4                | 179       | 11.26%  |
| SteamOS 3.4.6                | 157       | 9.87%   |
| SteamOS 3.4.8                | 145       | 9.12%   |
| SteamOS 3.3.2                | 117       | 7.36%   |
| SteamOS 3.3.1                | 107       | 6.73%   |
| SteamOS 3.5.17               | 104       | 6.54%   |
| SteamOS 3.4.10               | 64        | 4.03%   |
| SteamOS 3.2                  | 58        | 3.65%   |
| SteamOS 3.4.11               | 57        | 3.58%   |
| SteamOS 3.3                  | 53        | 3.33%   |
| SteamOS 3.4                  | 44        | 2.77%   |
| SteamOS 3.5                  | 30        | 1.89%   |
| SteamOS 3.6                  | 26        | 1.64%   |
| SteamOS 3.5.5                | 26        | 1.64%   |
| SteamOS 3.4.2                | 23        | 1.45%   |
| SteamOS Snapshot             | 21        | 1.32%   |
| SteamOS 4                    | 21        | 1.32%   |
| SteamOS 3.5.19               | 19        | 1.19%   |
| SteamOS 3.1                  | 17        | 1.07%   |
| SteamOS 3.3.3                | 15        | 0.94%   |
| SteamOS Rolling              | 14        | 0.88%   |
| SteamOS 3.5.1                | 14        | 0.88%   |
| SteamOS                      | 14        | 0.88%   |
| SteamOS 3.5.13               | 9         | 0.57%   |
| SteamOS 3.4.5                | 8         | 0.5%    |
| SteamOS 3.4.3                | 7         | 0.44%   |
| SteamOS 3.5.6                | 3         | 0.19%   |
| SteamOS 3.5.15               | 3         | 0.19%   |
| SteamOS 3.5.12               | 3         | 0.19%   |
| SteamOS 3.4.9                | 3         | 0.19%   |
| SteamOS 3.2 (steamdeck-main) | 3         | 0.19%   |
| SteamOS 3.5.3                | 2         | 0.13%   |
| SteamOS 3.5.14               | 2         | 0.13%   |
| SteamOS 3.5.11               | 2         | 0.13%   |
| SteamOS 3.5.10               | 2         | 0.13%   |
| SteamOS 3.4.7                | 2         | 0.13%   |
| SteamOS 1.1.4                | 2         | 0.13%   |
| SteamOS 1.051-prerelease     | 2         | 0.13%   |
| SteamOS 3.7                  | 1         | 0.06%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SteamOS | 1432      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                            | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| 5.13.0-valve36-1-neptune                           | 498       | 31.68%  |
| 6.1.52-valve9-1-neptune-61                         | 207       | 13.17%  |
| 5.13.0-valve21.3-1-neptune                         | 141       | 8.97%   |
| 5.13.0-valve37-1-neptune                           | 127       | 8.08%   |
| 6.1.52-valve16-1-neptune-61                        | 126       | 8.02%   |
| 5.13.0-valve21.1-1-neptune-02211-gc54cda5a36f3     | 110       | 7%      |
| 5.13.0-valve15-1-neptune-02197-gf6ec7ad3762a       | 54        | 3.44%   |
| 5.13.0-valve21-1-neptune-02209-g2a5bdc1102a0       | 35        | 2.23%   |
| 6.1.52-valve7-1-neptune-61                         | 29        | 1.84%   |
| 6.1.52-valve2-1-neptune-61                         | 19        | 1.21%   |
| 5.13.0-valve10.3-1-neptune-02176-g5fe416c4acd8     | 19        | 1.21%   |
| 5.13.0-valve10.1-1-neptune-02144-g7fffaf925dfb     | 16        | 1.02%   |
| 6.3.7-zen1-1-zen                                   | 15        | 0.95%   |
| 5.13.0-valve24-1-neptune-02226-g5b8545e4c5a1       | 15        | 0.95%   |
| 6.1.52-valve3-1-neptune-61                         | 14        | 0.89%   |
| 6.1.52-valve14-1-neptune-61                        | 12        | 0.76%   |
| 5.13.0-valve31-1-neptune                           | 11        | 0.7%    |
| 6.1.52-valve10-1-neptune-61                        | 8         | 0.51%   |
| 5.13.0-valve35-1-neptune                           | 8         | 0.51%   |
| 6.1.43-valve1-1-neptune-61                         | 7         | 0.45%   |
| 5.18.1-arch1_testHoloISO_20220606.1811             | 7         | 0.45%   |
| 5.13.0-valve10.1-2-neptune-dri-02144-g7fffaf925dfb | 7         | 0.45%   |
| 6.4.12-zen1-1-zen                                  | 6         | 0.38%   |
| 5.13.0-valve24-1-neptune                           | 6         | 0.38%   |
| 5.13.0-valve21.2-1-neptune                         | 6         | 0.38%   |
| 6.1.52-valve19-1-neptune-61                        | 5         | 0.32%   |
| 6.1.52-valve15-4-neptune-61                        | 5         | 0.32%   |
| 6.1.21-valve1-3-neptune-61                         | 5         | 0.32%   |
| 5.13.0-valve14-1-neptune-02195-g5b0f749d00fa       | 5         | 0.32%   |
| 6.1.21-valve1-1-neptune-61                         | 4         | 0.25%   |
| 5.13.0-valve20-1-neptune-02207-gbd986a7e1c7f       | 4         | 0.25%   |
| 6.1.52-valve17-1-neptune-61                        | 3         | 0.19%   |
| 6.1.52-valve12-1-neptune-61                        | 3         | 0.19%   |
| 6.1.12-valve2-1-neptune-61                         | 3         | 0.19%   |
| 5.15.93-1-lts                                      | 3         | 0.19%   |
| 5.13.0-valve22-1-neptune-02213-gb68995364335       | 3         | 0.19%   |
| 5.13.0-valve21-1-steamos-02209-g2a5bdc1102a0       | 3         | 0.19%   |
| 6.1.9-valve2-1-neptune-61                          | 2         | 0.13%   |
| 6.1.52-valve6-1-neptune-61                         | 2         | 0.13%   |
| 6.1.52-valve5-1-neptune-61                         | 2         | 0.13%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.13.0  | 1008      | 68.02%  |
| 6.1.52  | 407       | 27.46%  |
| 6.3.7   | 15        | 1.01%   |
| 6.1.21  | 11        | 0.74%   |
| 6.1.43  | 7         | 0.47%   |
| 5.18.1  | 7         | 0.47%   |
| 6.4.12  | 6         | 0.4%    |
| 6.1.12  | 3         | 0.2%    |
| 5.15.93 | 3         | 0.2%    |
| 6.5.0   | 2         | 0.13%   |
| 6.1.9   | 2         | 0.13%   |
| 5.15.79 | 2         | 0.13%   |
| 5.15.54 | 2         | 0.13%   |
| 6.4.3   | 1         | 0.07%   |
| 6.4.0   | 1         | 0.07%   |
| 6.1.5   | 1         | 0.07%   |
| 6.1.39  | 1         | 0.07%   |
| 6.1.29  | 1         | 0.07%   |
| 6.0.9   | 1         | 0.07%   |
| 6.0.7   | 1         | 0.07%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.13    | 1008      | 68.2%   |
| 6.1     | 430       | 29.09%  |
| 6.3     | 15        | 1.01%   |
| 6.4     | 7         | 0.47%   |
| 5.18    | 7         | 0.47%   |
| 5.15    | 7         | 0.47%   |
| 6.5     | 2         | 0.14%   |
| 6.0     | 2         | 0.14%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 1432      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| KDE5      | 1424      | 98.89%  |
| gamescope | 8         | 0.56%   |
| Unknown   | 6         | 0.42%   |
| KDE       | 1         | 0.07%   |
| GNOME     | 1         | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 1427      | 99.44%  |
| Wayland | 4         | 0.28%   |
| Tty     | 2         | 0.14%   |
| Unknown | 2         | 0.14%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1420      | 99.09%  |
| SDDM    | 13        | 0.91%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang         | Notebooks | Percent |
|--------------|-----------|---------|
| en_US        | 1239      | 85.39%  |
| de_DE        | 39        | 2.69%   |
| ru_RU        | 27        | 1.86%   |
| en_GB        | 19        | 1.31%   |
| es_ES        | 16        | 1.1%    |
| fr_FR        | 15        | 1.03%   |
| zh_CN        | 12        | 0.83%   |
| en_DE        | 11        | 0.76%   |
| pt_BR        | 9         | 0.62%   |
| C            | 9         | 0.62%   |
| pl_PL        | 8         | 0.55%   |
| an_ES        | 7         | 0.48%   |
| it_IT        | 6         | 0.41%   |
| ko_KR        | 3         | 0.21%   |
| cs_CZ        | 3         | 0.21%   |
| zh_TW        | 2         | 0.14%   |
| ru_UA        | 2         | 0.14%   |
| es_MX        | 2         | 0.14%   |
| en_NL        | 2         | 0.14%   |
| en_CA        | 2         | 0.14%   |
| ba_RU        | 2         | 0.14%   |
| sk_SK        | 1         | 0.07%   |
| pl           | 1         | 0.07%   |
| nl_NL        | 1         | 0.07%   |
| nl_BE        | 1         | 0.07%   |
| ksh_DE       | 1         | 0.07%   |
| hu_HU        | 1         | 0.07%   |
| hr_HR        | 1         | 0.07%   |
| fr_BE        | 1         | 0.07%   |
| et_EE        | 1         | 0.07%   |
| es_UY        | 1         | 0.07%   |
| en_SE        | 1         | 0.07%   |
| en_IE        | 1         | 0.07%   |
| en_HK        | 1         | 0.07%   |
| en_GB.UTF-12 | 1         | 0.07%   |
| en_DK        | 1         | 0.07%   |
| en_AU        | 1         | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 1416      | 98.61%  |
| EFI  | 20        | 1.39%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Btrfs | 1425      | 99.51%  |
| Tmpfs | 6         | 0.42%   |
| Ext4  | 1         | 0.07%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1415      | 98.47%  |
| GPT     | 22        | 1.53%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1417      | 98.75%  |
| Yes       | 18        | 1.25%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1429      | 99.79%  |
| Yes       | 3         | 0.21%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Valve               | 1338      | 93.44%  |
| Hewlett-Packard     | 17        | 1.19%   |
| Dell                | 13        | 0.91%   |
| Lenovo              | 10        | 0.7%    |
| ASUSTek Computer    | 9         | 0.63%   |
| GPD                 | 7         | 0.49%   |
| Apple               | 6         | 0.42%   |
| Acer                | 5         | 0.35%   |
| MSI                 | 3         | 0.21%   |
| Gigabyte Technology | 3         | 0.21%   |
| Anbernic            | 3         | 0.21%   |
| Samsung Electronics | 2         | 0.14%   |
| ASRock              | 2         | 0.14%   |
| AMI                 | 2         | 0.14%   |
| Unknown             | 2         | 0.14%   |
| Sony                | 1         | 0.07%   |
| ONE-NETBOOK         | 1         | 0.07%   |
| Monster             | 1         | 0.07%   |
| Medion              | 1         | 0.07%   |
| GPU Company         | 1         | 0.07%   |
| Google              | 1         | 0.07%   |
| Biostar             | 1         | 0.07%   |
| AZW                 | 1         | 0.07%   |
| Alienware           | 1         | 0.07%   |
| ADVANCE             | 1         | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Valve Jupiter                       | 1262      | 88.13%  |
| Valve Galileo                       | 76        | 5.31%   |
| GPD G1619-04                        | 5         | 0.35%   |
| Anbernic Win600                     | 3         | 0.21%   |
| Unknown                             | 3         | 0.21%   |
| HP Pavilion 17                      | 2         | 0.14%   |
| HP Laptop 15s-eq2xxx                | 2         | 0.14%   |
| HP Laptop 15-bs0xx                  | 2         | 0.14%   |
| Apple MacBookPro8,1                 | 2         | 0.14%   |
| Sony VGN-Z520N                      | 1         | 0.07%   |
| Samsung 950XDB/951XDB/950XDY        | 1         | 0.07%   |
| Samsung 300E4C/300E5C/300E7C        | 1         | 0.07%   |
| ONE-NETBOOK ONEXPLAYER 2 PRO ARP23P | 1         | 0.07%   |
| MSI MS-7995                         | 1         | 0.07%   |
| MSI GP66 Leopard 11UH               | 1         | 0.07%   |
| MSI GF62 7RE                        | 1         | 0.07%   |
| Monster ABRA A5 V17.3               | 1         | 0.07%   |
| Medion Deputy P50                   | 1         | 0.07%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS  | 1         | 0.07%   |
| Lenovo ThinkBook 13s G3 ACN 20YA    | 1         | 0.07%   |
| Lenovo Legion Y740-15IRHg 81UH      | 1         | 0.07%   |
| Lenovo Legion 5 17IMH05H 81Y8       | 1         | 0.07%   |
| Lenovo IdeaPad Gaming 3 15ARH7 82SB | 1         | 0.07%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2 | 1         | 0.07%   |
| Lenovo IdeaPad 330-15IKB 81DE       | 1         | 0.07%   |
| Lenovo IdeaPad 3 15ITL6 82H8        | 1         | 0.07%   |
| Lenovo IdeaPad 130-15AST 81H5       | 1         | 0.07%   |
| Lenovo IdeaPad 1 14IAU7 82QC        | 1         | 0.07%   |
| HP Victus by Gaming Laptop 16-s0xxx | 1         | 0.07%   |
| HP ProBook 455 G3                   | 1         | 0.07%   |
| HP Pavilion Laptop 15-eh1xxx        | 1         | 0.07%   |
| HP Pavilion Laptop 15-eh0xxx        | 1         | 0.07%   |
| HP Pavilion Gaming Laptop 15-ec2xxx | 1         | 0.07%   |
| HP Pavilion Gaming Laptop 15-dk2xxx | 1         | 0.07%   |
| HP Pavilion Gaming Laptop 15-dk0xxx | 1         | 0.07%   |
| HP Laptop 15-bw0xx                  | 1         | 0.07%   |
| HP Laptop 14z-fq0000                | 1         | 0.07%   |
| HP 15 Notebook PC                   | 1         | 0.07%   |
| HP 15                               | 1         | 0.07%   |
| GPU Company GWNR71517               | 1         | 0.07%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Valve Jupiter          | 1262      | 88.13%  |
| Valve Galileo          | 76        | 5.31%   |
| HP Pavilion            | 7         | 0.49%   |
| Lenovo IdeaPad         | 6         | 0.42%   |
| HP Laptop              | 6         | 0.42%   |
| GPD G1619-04           | 5         | 0.35%   |
| Dell Precision         | 5         | 0.35%   |
| Dell Inspiron          | 3         | 0.21%   |
| Anbernic Win600        | 3         | 0.21%   |
| Unknown                | 3         | 0.21%   |
| Lenovo Legion          | 2         | 0.14%   |
| HP 15                  | 2         | 0.14%   |
| Dell XPS               | 2         | 0.14%   |
| Dell Venue             | 2         | 0.14%   |
| ASUS TUF               | 2         | 0.14%   |
| ASUS ROG               | 2         | 0.14%   |
| Apple MacBookPro8      | 2         | 0.14%   |
| Apple MacBookAir6      | 2         | 0.14%   |
| Acer Nitro             | 2         | 0.14%   |
| Acer Aspire            | 2         | 0.14%   |
| Sony VGN-Z520N         | 1         | 0.07%   |
| Samsung 950XDB         | 1         | 0.07%   |
| Samsung 300E4C         | 1         | 0.07%   |
| ONE-NETBOOK ONEXPLAYER | 1         | 0.07%   |
| MSI MS-7995            | 1         | 0.07%   |
| MSI GP66               | 1         | 0.07%   |
| MSI GF62               | 1         | 0.07%   |
| Monster ABRA           | 1         | 0.07%   |
| Medion Deputy          | 1         | 0.07%   |
| Lenovo Yoga            | 1         | 0.07%   |
| Lenovo ThinkBook       | 1         | 0.07%   |
| HP Victus              | 1         | 0.07%   |
| HP ProBook             | 1         | 0.07%   |
| GPU Company GWNR71517  | 1         | 0.07%   |
| GPD G1619-02           | 1         | 0.07%   |
| GPD G1619-01           | 1         | 0.07%   |
| Google Droid           | 1         | 0.07%   |
| Gigabyte B650M         | 1         | 0.07%   |
| Gigabyte B650          | 1         | 0.07%   |
| Gigabyte B550I         | 1         | 0.07%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2022    | 893       | 62.36%  |
| 2023    | 446       | 31.15%  |
| 2021    | 23        | 1.61%   |
| Unknown | 14        | 0.98%   |
| 2013    | 8         | 0.56%   |
| 2020    | 7         | 0.49%   |
| 2017    | 7         | 0.49%   |
| 2024    | 6         | 0.42%   |
| 2018    | 6         | 0.42%   |
| 2019    | 5         | 0.35%   |
| 2012    | 5         | 0.35%   |
| 2015    | 4         | 0.28%   |
| 2016    | 2         | 0.14%   |
| 2014    | 2         | 0.14%   |
| 2011    | 2         | 0.14%   |
| 2009    | 1         | 0.07%   |
| 2008    | 1         | 0.07%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1432      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1432      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1431      | 99.93%  |
| Yes  | 1         | 0.07%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 1363      | 95.12%  |
| 4.01-8.0    | 21        | 1.47%   |
| 16.01-24.0  | 18        | 1.26%   |
| 3.01-4.0    | 12        | 0.84%   |
| 32.01-64.0  | 9         | 0.63%   |
| 24.01-32.0  | 8         | 0.56%   |
| 2.01-3.0    | 1         | 0.07%   |
| 64.01-256.0 | 1         | 0.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 3.01-4.0  | 500       | 32.34%  |
| 2.01-3.0  | 491       | 31.76%  |
| 4.01-8.0  | 434       | 28.07%  |
| 1.01-2.0  | 82        | 5.3%    |
| 8.01-16.0 | 38        | 2.46%   |
| 0.51-1.0  | 1         | 0.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 899       | 60.99%  |
| 1      | 520       | 35.28%  |
| 3      | 43        | 2.92%   |
| 4      | 8         | 0.54%   |
| 5      | 2         | 0.14%   |
| 0      | 2         | 0.14%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1403      | 97.91%  |
| Yes       | 30        | 2.09%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 948       | 64.58%  |
| Yes       | 520       | 35.42%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1428      | 99.72%  |
| No        | 4         | 0.28%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1331      | 92.88%  |
| No        | 102       | 7.12%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 565       | 39.37%  |
| Germany      | 138       | 9.62%   |
| UK           | 130       | 9.06%   |
| Russia       | 64        | 4.46%   |
| Canada       | 60        | 4.18%   |
| Poland       | 41        | 2.86%   |
| Spain        | 38        | 2.65%   |
| France       | 37        | 2.58%   |
| Netherlands  | 30        | 2.09%   |
| Brazil       | 30        | 2.09%   |
| Italy        | 19        | 1.32%   |
| Mexico       | 17        | 1.18%   |
| Australia    | 16        | 1.11%   |
| Austria      | 15        | 1.05%   |
| China        | 13        | 0.91%   |
| Sweden       | 11        | 0.77%   |
| Czechia      | 10        | 0.7%    |
| Philippines  | 9         | 0.63%   |
| Israel       | 9         | 0.63%   |
| Hungary      | 9         | 0.63%   |
| Belgium      | 9         | 0.63%   |
| Romania      | 8         | 0.56%   |
| UAE          | 7         | 0.49%   |
| Chile        | 7         | 0.49%   |
| Taiwan       | 6         | 0.42%   |
| Switzerland  | 6         | 0.42%   |
| South Korea  | 6         | 0.42%   |
| Slovakia     | 6         | 0.42%   |
| Saudi Arabia | 6         | 0.42%   |
| Ireland      | 6         | 0.42%   |
| Denmark      | 6         | 0.42%   |
| Ukraine      | 5         | 0.35%   |
| Japan        | 5         | 0.35%   |
| Finland      | 5         | 0.35%   |
| Turkey       | 4         | 0.28%   |
| Portugal     | 4         | 0.28%   |
| Malaysia     | 4         | 0.28%   |
| Indonesia    | 4         | 0.28%   |
| India        | 4         | 0.28%   |
| Hong Kong    | 4         | 0.28%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Moscow        | 23        | 1.52%   |
| Berlin        | 14        | 0.93%   |
| Seattle       | 11        | 0.73%   |
| Madrid        | 10        | 0.66%   |
| Austin        | 10        | 0.66%   |
| Warsaw        | 8         | 0.53%   |
| Los Angeles   | 8         | 0.53%   |
| London        | 8         | 0.53%   |
| Flushing      | 8         | 0.53%   |
| St Petersburg | 7         | 0.46%   |
| Portland      | 7         | 0.46%   |
| Chicago       | 7         | 0.46%   |
| Brooklyn      | 7         | 0.46%   |
| Toronto       | 6         | 0.4%    |
| Sydney        | 6         | 0.4%    |
| Santiago      | 6         | 0.4%    |
| New York      | 6         | 0.4%    |
| Munich        | 6         | 0.4%    |
| Melbourne     | 6         | 0.4%    |
| Hamburg       | 6         | 0.4%    |
| Dubai         | 6         | 0.4%    |
| Denver        | 6         | 0.4%    |
| Dallas        | 6         | 0.4%    |
| Amsterdam     | 6         | 0.4%    |
| Vienna        | 5         | 0.33%   |
| Valencia      | 5         | 0.33%   |
| Prague        | 5         | 0.33%   |
| Nuremberg     | 5         | 0.33%   |
| Minneapolis   | 5         | 0.33%   |
| Manchester    | 5         | 0.33%   |
| Leicester     | 5         | 0.33%   |
| Indianapolis  | 5         | 0.33%   |
| Washington    | 4         | 0.27%   |
| Tacoma        | 4         | 0.27%   |
| Sao Paulo     | 4         | 0.27%   |
| San Diego     | 4         | 0.27%   |
| Richmond      | 4         | 0.27%   |
| Poznan        | 4         | 0.27%   |
| Phoenix       | 4         | 0.27%   |
| Paris         | 4         | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Unknown                        | 727       | 842    | 29.5%   |
| Phison Electronics             | 302       | 353    | 12.26%  |
| Kingston Technology Company    | 271       | 318    | 11%     |
| Samsung Electronics            | 239       | 284    | 9.7%    |
| O2 Micro                       | 204       | 222    | 8.28%   |
| Unknown                        | 187       | 221    | 7.59%   |
| Sandisk                        | 97        | 112    | 3.94%   |
| Kingston                       | 83        | 91     | 3.37%   |
| Phison                         | 79        | 81     | 3.21%   |
| Silicon Motion                 | 52        | 57     | 2.11%   |
| Micron Technology              | 30        | 33     | 1.22%   |
| SK hynix                       | 29        | 41     | 1.18%   |
| KIOXIA                         | 24        | 27     | 0.97%   |
| Seagate                        | 18        | 23     | 0.73%   |
| JMicron Technology             | 11        | 11     | 0.45%   |
| MAXIO Technology (Hangzhou)    | 10        | 11     | 0.41%   |
| Realtek                        | 8         | 11     | 0.32%   |
| Solid State Storage Technology | 6         | 7      | 0.24%   |
| WDC                            | 5         | 5      | 0.2%    |
| Toshiba                        | 5         | 5      | 0.2%    |
| Biwin Storage Technology       | 5         | 5      | 0.2%    |
| A-DATA Technology              | 5         | 5      | 0.2%    |
| SABRENT                        | 4         | 4      | 0.16%   |
| Intel                          | 4         | 4      | 0.16%   |
| Apple                          | 4         | 8      | 0.16%   |
| Micron/Crucial Technology      | 3         | 3      | 0.12%   |
| Crucial                        | 3         | 5      | 0.12%   |
| ASMT                           | 3         | 4      | 0.12%   |
| Solid State Storage            | 2         | 2      | 0.08%   |
| Patriot                        | 2         | 2      | 0.08%   |
| Netac                          | 2         | 2      | 0.08%   |
| KingSpec                       | 2         | 2      | 0.08%   |
| Hitachi                        | 2         | 2      | 0.08%   |
| HGST                           | 2         | 2      | 0.08%   |
| GLOWAY                         | 2         | 2      | 0.08%   |
| China                          | 2         | 2      | 0.08%   |
| ADATA Technology               | 2         | 2      | 0.08%   |
| Yangtze Memory Technologies    | 1         | 1      | 0.04%   |
| WDC WDB                        | 1         | 1      | 0.04%   |
| W800S                          | 1         | 1      | 0.04%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Unknown MMC Card  512GB                               | 320       | 12.78%  |
| Kingston Company OM3PDP3 NVMe SSD 512GB               | 268       | 10.71%  |
| Phison PS5013 E13 NVMe Controller 512GB               | 239       | 9.55%   |
| O2 Micro E2M2 64GB                                    | 190       | 7.59%   |
| Unknown                                               | 187       | 7.47%   |
| Unknown MMC Card  256GB                               | 167       | 6.67%   |
| Samsung MZ9LQ512HBLU-00BVL 512GB                      | 106       | 4.23%   |
| Unknown MMC Card  128GB                               | 92        | 3.68%   |
| Samsung MZ9LQ256HBJD-00BVL 256GB                      | 64        | 2.56%   |
| Phison NVMe SSD Drive 512GB                           | 54        | 2.16%   |
| Kingston NVMe SSD Drive 512GB                         | 42        | 1.68%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 37        | 1.48%   |
| Kingston NVMe SSD Drive 256GB                         | 32        | 1.28%   |
| Unknown MMC Card  64GB                                | 29        | 1.16%   |
| Sandisk WD PC SN740 SDDPTQD-1T00 1024GB               | 28        | 1.12%   |
| Unknown MMC Card  32GB                                | 26        | 1.04%   |
| Phison Sabrent SB-2130-1TB                            | 25        | 1%      |
| Unknown MMC Card  393GB                               | 23        | 0.92%   |
| Sandisk WD PC SN740 SDDPTQE-2T00 2TB                  | 19        | 0.76%   |
| Phison NVMe SSD Drive 256GB                           | 18        | 0.72%   |
| O2 Micro NVMe SSD Drive 64GB                          | 15        | 0.6%    |
| Phison ESMP001TKB5C3-E19TS 1024GB                     | 13        | 0.52%   |
| Sandisk WDC PC SN530 SDBPTPZ-1T00 1024GB              | 12        | 0.48%   |
| Micron 2400_MTFDKBK1T0QFM 1024GB                      | 12        | 0.48%   |
| Unknown MMC Card  16GB                                | 10        | 0.4%    |
| SK hynix BC711 NVMe 256GB                             | 9         | 0.36%   |
| Unknown MMC Card  250GB                               | 8         | 0.32%   |
| Unknown MMC Card  249GB                               | 8         | 0.32%   |
| Unknown MMC Card  196GB                               | 8         | 0.32%   |
| Silicon Motion NVMe SSD Drive 512GB                   | 8         | 0.32%   |
| Unknown MMC Card  500GB                               | 7         | 0.28%   |
| Unknown MMC Card  498GB                               | 7         | 0.28%   |
| Samsung MZ9LQ1T0HBLB-00B00 1024GB                     | 7         | 0.28%   |
| Samsung MZ9L41T0HBLB-00AVL 1024GB                     | 7         | 0.28%   |
| Realtek RTL9210B-CG 512GB                             | 7         | 0.28%   |
| Phison Corsair MP600 MINI 1TB                         | 7         | 0.28%   |
| Micron 2400_MTFDKBK2T0QFM 2TB                         | 7         | 0.28%   |
| Unknown MMC Card  1TB                                 | 6         | 0.24%   |
| SK hynix BC711 NVMe 512GB                             | 6         | 0.24%   |
| Samsung PM991a NVMe 512GB                             | 6         | 0.24%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 20     | 36.59%  |
| JMicron Technology  | 5         | 5      | 12.2%   |
| Toshiba             | 3         | 3      | 7.32%   |
| SABRENT             | 3         | 3      | 7.32%   |
| ASMT                | 3         | 4      | 7.32%   |
| WDC                 | 2         | 2      | 4.88%   |
| Hitachi             | 2         | 2      | 4.88%   |
| HGST                | 2         | 2      | 4.88%   |
| Unknown             | 1         | 1      | 2.44%   |
| TO Exter            | 1         | 1      | 2.44%   |
| StoreJet            | 1         | 1      | 2.44%   |
| Samsung Electronics | 1         | 1      | 2.44%   |
| Maxone              | 1         | 1      | 2.44%   |
| Apple               | 1         | 5      | 2.44%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 13        | 18     | 21.31%  |
| Kingston            | 7         | 8      | 11.48%  |
| SanDisk             | 6         | 6      | 9.84%   |
| Crucial             | 3         | 5      | 4.92%   |
| WDC                 | 2         | 2      | 3.28%   |
| Patriot             | 2         | 2      | 3.28%   |
| KingSpec            | 2         | 2      | 3.28%   |
| GLOWAY              | 2         | 2      | 3.28%   |
| China               | 2         | 2      | 3.28%   |
| Apple               | 2         | 2      | 3.28%   |
| A-DATA Technology   | 2         | 2      | 3.28%   |
| Unknown             | 2         | 2      | 3.28%   |
| WDC WDB             | 1         | 1      | 1.64%   |
| Verbatim            | 1         | 2      | 1.64%   |
| Union Memory        | 1         | 1      | 1.64%   |
| TrekStor            | 1         | 1      | 1.64%   |
| SSK                 | 1         | 1      | 1.64%   |
| SPCC                | 1         | 1      | 1.64%   |
| SK hynix            | 1         | 1      | 1.64%   |
| PNY                 | 1         | 1      | 1.64%   |
| NGFF                | 1         | 1      | 1.64%   |
| Netac               | 1         | 1      | 1.64%   |
| Mushkin             | 1         | 1      | 1.64%   |
| Micron Technology   | 1         | 1      | 1.64%   |
| Lexar 25            | 1         | 1      | 1.64%   |
| Kingchuxing         | 1         | 1      | 1.64%   |
| KEEPDATA            | 1         | 1      | 1.64%   |
| External            | 1         | 2      | 1.64%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 1391      | 1647   | 57.74%  |
| MMC     | 904       | 1055   | 37.53%  |
| SSD     | 58        | 71     | 2.41%   |
| HDD     | 38        | 51     | 1.58%   |
| Unknown | 18        | 19     | 0.75%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 1391      | 1628   | 57.69%  |
| MMC  | 904       | 1055   | 37.49%  |
| SAS  | 71        | 92     | 2.94%   |
| SATA | 45        | 68     | 1.87%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 51        | 59     | 53.13%  |
| 0.51-1.0   | 25        | 39     | 26.04%  |
| 1.01-2.0   | 11        | 14     | 11.46%  |
| 3.01-4.0   | 5         | 6      | 5.21%   |
| 4.01-10.0  | 3         | 3      | 3.13%   |
| 10.01-20.0 | 1         | 1      | 1.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 584       | 38.83%  |
| 501-1000       | 297       | 19.75%  |
| 101-250        | 294       | 19.55%  |
| 51-100         | 150       | 9.97%   |
| 1001-2000      | 131       | 8.71%   |
| 2001-3000      | 23        | 1.53%   |
| More than 3000 | 17        | 1.13%   |
| Unknown        | 5         | 0.33%   |
| 21-50          | 3         | 0.2%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 430       | 28.16%  |
| 251-500        | 399       | 26.13%  |
| 21-50          | 210       | 13.75%  |
| 501-1000       | 172       | 11.26%  |
| 1-20           | 125       | 8.19%   |
| 51-100         | 124       | 8.12%   |
| 1001-2000      | 49        | 3.21%   |
| 2001-3000      | 9         | 0.59%   |
| Unknown        | 5         | 0.33%   |
| More than 3000 | 4         | 0.26%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 1         | 1      | 100%    |

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
| Detected | 1424      | 2813   | 98.27%  |
| Works    | 24        | 29     | 1.66%   |
| Malfunc  | 1         | 1      | 0.07%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Phison Electronics             | 377       | 25.51%  |
| Kingston Technology Company    | 339       | 22.94%  |
| Samsung Electronics            | 224       | 15.16%  |
| O2 Micro                       | 204       | 13.8%   |
| Sandisk                        | 92        | 6.22%   |
| Silicon Motion                 | 52        | 3.52%   |
| Intel                          | 44        | 2.98%   |
| SK hynix                       | 29        | 1.96%   |
| Micron Technology              | 29        | 1.96%   |
| KIOXIA                         | 24        | 1.62%   |
| AMD                            | 21        | 1.42%   |
| MAXIO Technology (Hangzhou)    | 10        | 0.68%   |
| Solid State Storage Technology | 8         | 0.54%   |
| Biwin Storage Technology       | 5         | 0.34%   |
| ADATA Technology               | 5         | 0.34%   |
| Toshiba America Info Systems   | 3         | 0.2%    |
| Micron/Crucial Technology      | 3         | 0.2%    |
| INNOGRIT                       | 3         | 0.2%    |
| Yangtze Memory Technologies    | 1         | 0.07%   |
| Solidigm                       | 1         | 0.07%   |
| Realtek Semiconductor          | 1         | 0.07%   |
| Netac Technology               | 1         | 0.07%   |
| Marvell Technology Group       | 1         | 0.07%   |
| Apple                          | 1         | 0.07%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Kingston Company OM3PDP3 NVMe SSD                                             | 335       | 22.51%  |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                           | 308       | 20.7%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                   | 209       | 14.05%  |
| O2 Micro FORESEE E2M2 NVMe SSD                                                | 204       | 13.71%  |
| Phison PS5021-E21 PCIe4 NVMe Controller (DRAM-less)                           | 51        | 3.43%   |
| Sandisk PC SN740 NVMe SSD (DRAM-less)                                         | 50        | 3.36%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers             | 49        | 3.29%   |
| Micron 2400 NVMe SSD (DRAM-less)                                              | 25        | 1.68%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                          | 22        | 1.48%   |
| SanDisk IX SN530 NVMe SSD (DRAM-less)                                         | 19        | 1.28%   |
| AMD FCH SATA Controller [AHCI mode]                                           | 17        | 1.14%   |
| Phison PS5019-E19 PCIe4 NVMe Controller (DRAM-less)                           | 14        | 0.94%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                    | 13        | 0.87%   |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                    | 11        | 0.74%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                 | 8         | 0.54%   |
| Intel Volume Management Device NVMe RAID Controller                           | 8         | 0.54%   |
| SK hynix BC511 NVMe SSD                                                       | 6         | 0.4%    |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                      | 6         | 0.4%    |
| Solid State Storage XA1-311024 NVMe SSD M.2                                   | 5         | 0.34%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                    | 5         | 0.34%   |
| Sandisk WD Black SN770M NVMe SSD (DRAM-less)                                  | 5         | 0.34%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 5         | 0.34%   |
| SanDisk PC SN530 NVMe SSD                                                     | 4         | 0.27%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1602 (DRAM-less)                      | 4         | 0.27%   |
| Intel Tiger Lake-LP SATA Controller                                           | 4         | 0.27%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 4         | 0.27%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 4         | 0.27%   |
| Biwin Storage KingSpec NX series NVMe SSD (DRAM-less)                         | 4         | 0.27%   |
| ADATA IM2P33F3 NVMe SSD (DRAM-less)                                           | 4         | 0.27%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                | 3         | 0.2%    |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                     | 3         | 0.2%    |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                         | 3         | 0.2%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 3         | 0.2%    |
| Phison E12 NVMe Controller                                                    | 3         | 0.2%    |
| Intel SSD 660P Series                                                         | 3         | 0.2%    |
| Silicon Motion SM2269XT (DRAM-less) NVMe SSD Controller                       | 2         | 0.13%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 2         | 0.13%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                          | 2         | 0.13%   |
| Micron 2200S NVMe SSD [Cassandra]                                             | 2         | 0.13%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 2         | 0.13%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 1392      | 95.21%  |
| SATA | 57        | 3.9%    |
| RAID | 12        | 0.82%   |
| IDE  | 1         | 0.07%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| AMD    | 1379      | 96.3%   |
| Intel  | 53        | 3.7%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Custom APU 0405                           | 1312      | 91.49%  |
| AMD Custom APU 0932                           | 28        | 1.95%   |
| AMD Ryzen 7 6800U with Radeon Graphics        | 5         | 0.35%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 0.14%   |
| Intel Core i5-4260U CPU @ 1.40GHz             | 2         | 0.14%   |
| Intel Core i5-2435M CPU @ 2.40GHz             | 2         | 0.14%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 2         | 0.14%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 2         | 0.14%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 0.14%   |
| Intel 11th Gen Core i5-11300H @ 3.10GHz       | 2         | 0.14%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 2         | 0.14%   |
| AMD Ryzen 7 7840U w/ Radeon 780M Graphics     | 2         | 0.14%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 0.14%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 2         | 0.14%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 2         | 0.14%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 2         | 0.14%   |
| AMD Athlon Silver 3050e with Radeon Graphics  | 2         | 0.14%   |
| Intel Xeon CPU E3-1575M v5 @ 3.00GHz          | 1         | 0.07%   |
| Intel Processor 5Y10 CPU @ 0.80GHz            | 1         | 0.07%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 0.07%   |
| Intel Core i9-9880H CPU @ 2.30GHz             | 1         | 0.07%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 0.07%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 0.07%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.07%   |
| Intel Core i7-7560U CPU @ 2.40GHz             | 1         | 0.07%   |
| Intel Core i7-6920HQ CPU @ 2.90GHz            | 1         | 0.07%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 1         | 0.07%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 1         | 0.07%   |
| Intel Core i7-3840QM CPU @ 2.80GHz            | 1         | 0.07%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 0.07%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 1         | 0.07%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 0.07%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 1         | 0.07%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 0.07%   |
| Intel Core i5-8259U CPU @ 2.30GHz             | 1         | 0.07%   |
| Intel Core i5-4300Y CPU @ 1.60GHz             | 1         | 0.07%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 1         | 0.07%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 0.07%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 0.07%   |
| Intel Core i5-1035G7 CPU @ 1.20GHz            | 1         | 0.07%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Other                | 1354      | 94.55%  |
| AMD Ryzen 7          | 15        | 1.05%   |
| Intel Core i7        | 13        | 0.91%   |
| Intel Core i5        | 12        | 0.84%   |
| AMD Ryzen 5          | 11        | 0.77%   |
| Intel Core i3        | 4         | 0.28%   |
| AMD Ryzen 9          | 4         | 0.28%   |
| Intel Celeron        | 3         | 0.21%   |
| AMD A10              | 3         | 0.21%   |
| Intel Core 2 Duo     | 2         | 0.14%   |
| Intel Atom           | 2         | 0.14%   |
| AMD Athlon           | 2         | 0.14%   |
| Intel Xeon           | 1         | 0.07%   |
| Intel Pentium Silver | 1         | 0.07%   |
| Intel Core i9        | 1         | 0.07%   |
| AMD Ryzen 3          | 1         | 0.07%   |
| AMD E1               | 1         | 0.07%   |
| AMD A8               | 1         | 0.07%   |
| AMD A6               | 1         | 0.07%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 1364      | 95.25%  |
| 2      | 32        | 2.23%   |
| 8      | 21        | 1.47%   |
| 6      | 12        | 0.84%   |
| 12     | 2         | 0.14%   |
| 16     | 1         | 0.07%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1432      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1413      | 98.54%  |
| 1      | 21        | 1.46%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1432      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1415      | 98.54%  |
| 0x08900201 | 16        | 1.11%   |
| 0x40651    | 1         | 0.07%   |
| 0x1067a    | 1         | 0.07%   |
| 0x0a704103 | 1         | 0.07%   |
| 0x0a50000c | 1         | 0.07%   |
| 0x0a404102 | 1         | 0.07%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Unknown       | 1358      | 94.83%  |
| KabyLake      | 12        | 0.84%   |
| Zen 3         | 8         | 0.56%   |
| TigerLake     | 8         | 0.56%   |
| Haswell       | 6         | 0.42%   |
| Zen 2         | 5         | 0.35%   |
| Zen+          | 4         | 0.28%   |
| Silvermont    | 4         | 0.28%   |
| IvyBridge     | 4         | 0.28%   |
| Zen           | 3         | 0.21%   |
| Skylake       | 3         | 0.21%   |
| SandyBridge   | 3         | 0.21%   |
| Piledriver    | 3         | 0.21%   |
| Excavator     | 3         | 0.21%   |
| Penryn        | 2         | 0.14%   |
| CometLake     | 2         | 0.14%   |
| Jaguar        | 1         | 0.07%   |
| IceLake       | 1         | 0.07%   |
| Goldmont plus | 1         | 0.07%   |
| Broadwell     | 1         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| AMD    | 1380      | 94.52%  |
| Intel  | 47        | 3.22%   |
| Nvidia | 33        | 2.26%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 1262      | 86.32%  |
| AMD Sephiroth [AMD Custom GPU 0405]                                                      | 76        | 5.2%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 0.48%   |
| AMD Rembrandt [Radeon 680M]                                                              | 6         | 0.41%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 6         | 0.41%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 0.34%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 0.27%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 4         | 0.27%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 0.27%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 0.27%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 0.27%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 0.21%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 0.21%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 3         | 0.21%   |
| AMD Phoenix1                                                                             | 3         | 0.21%   |
| AMD Lucienne                                                                             | 3         | 0.21%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 2         | 0.14%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.14%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                                 | 2         | 0.14%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 0.14%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 2         | 0.14%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.14%   |
| Intel HD Graphics 630                                                                    | 2         | 0.14%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 0.14%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 0.14%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 0.14%   |
| AMD Raphael                                                                              | 2         | 0.14%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX/7900M]                                           | 2         | 0.14%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                            | 2         | 0.14%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.07%   |
| Nvidia TU106BM [GeForce RTX 2060 Mobile]                                                 | 1         | 0.07%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 0.07%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.07%   |
| Nvidia GP104GLM [Quadro P4000 Mobile]                                                    | 1         | 0.07%   |
| Nvidia GP104 [GeForce GTX 1060 6GB]                                                      | 1         | 0.07%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.07%   |
| Nvidia GM107GLM [Quadro M2000M]                                                          | 1         | 0.07%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                                    | 1         | 0.07%   |
| Nvidia GK107M [GeForce GT 740M]                                                          | 1         | 0.07%   |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 1         | 0.07%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x AMD        | 1371      | 95.67%  |
| 1 x Intel      | 26        | 1.81%   |
| Intel + Nvidia | 20        | 1.4%    |
| AMD + Nvidia   | 8         | 0.56%   |
| 1 x Nvidia     | 5         | 0.35%   |
| 2 x AMD        | 2         | 0.14%   |
| Other          | 1         | 0.07%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1421      | 99.16%  |
| Proprietary | 12        | 0.84%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1411      | 98.26%  |
| 0.51-1.0   | 11        | 0.77%   |
| 7.01-8.0   | 4         | 0.28%   |
| 3.01-4.0   | 4         | 0.28%   |
| 5.01-6.0   | 2         | 0.14%   |
| 2.01-3.0   | 2         | 0.14%   |
| 1.01-2.0   | 1         | 0.07%   |
| 0.01-0.5   | 1         | 0.07%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| Valve                | 999       | 59.86%  |
| Analogix             | 167       | 10.01%  |
| Samsung Electronics  | 70        | 4.19%   |
| Goldstar             | 53        | 3.18%   |
| Dell                 | 31        | 1.86%   |
| Acer                 | 22        | 1.32%   |
| AOC                  | 19        | 1.14%   |
| Hewlett-Packard      | 17        | 1.02%   |
| BOE                  | 17        | 1.02%   |
| Chimei Innolux       | 14        | 0.84%   |
| ASUSTek Computer     | 14        | 0.84%   |
| Ancor Communications | 14        | 0.84%   |
| Philips              | 13        | 0.78%   |
| Vizio                | 12        | 0.72%   |
| Sony                 | 12        | 0.72%   |
| AU Optronics         | 12        | 0.72%   |
| Lenovo               | 11        | 0.66%   |
| BenQ                 | 11        | 0.66%   |
| LG Display           | 8         | 0.48%   |
| RTK                  | 7         | 0.42%   |
| Apple                | 7         | 0.42%   |
| Sceptre Tech         | 6         | 0.36%   |
| MSI                  | 6         | 0.36%   |
| Panasonic            | 5         | 0.3%    |
| JDI                  | 5         | 0.3%    |
| ViewSonic            | 4         | 0.24%   |
| Toshiba              | 4         | 0.24%   |
| Sharp                | 4         | 0.24%   |
| SGT                  | 4         | 0.24%   |
| Hitachi              | 4         | 0.24%   |
| GreenWood            | 4         | 0.24%   |
| Gigabyte Technology  | 4         | 0.24%   |
| Unknown (XXX)        | 3         | 0.18%   |
| Pixio                | 3         | 0.18%   |
| ONN                  | 3         | 0.18%   |
| Insignia             | 3         | 0.18%   |
| INNOCN               | 3         | 0.18%   |
| Huion                | 3         | 0.18%   |
| DHD                  | 3         | 0.18%   |
| Vestel Elektronik    | 2         | 0.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                     | 923       | 54.91%  |
| Analogix ANX7530 U ANX7539 800x1280                                     | 167       | 9.93%   |
| Valve ANX7530 U VLV3003 800x1280 100x160mm 7.4-inch                     | 67        | 3.99%   |
| Valve ANX7530 U VLV3004 800x1280 100x160mm 7.4-inch                     | 9         | 0.54%   |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                     | 7         | 0.42%   |
| JDI GPD1001H JDI0031 2560x1600 890x500mm 40.2-inch                      | 5         | 0.3%    |
| RTK 7911D RTK2A3B 720x1280 720x1280mm 57.8-inch                         | 4         | 0.24%   |
| Samsung Electronics LCD Monitor SAM7017 3840x2160 1872x1053mm 84.6-inch | 3         | 0.18%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch    | 3         | 0.18%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch       | 3         | 0.18%   |
| Philips FTV PHL04C3 3840x2160 1440x810mm 65.0-inch                      | 3         | 0.18%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 3         | 0.18%   |
| Vizio V555-J01 VIZ1039 3840x2160 1209x680mm 54.6-inch                   | 2         | 0.12%   |
| Vizio M322i-B1 VIZ1005 1920x1080 698x392mm 31.5-inch                    | 2         | 0.12%   |
| Vizio E500i-A1 VIZ1004 1920x1080 1095x616mm 49.5-inch                   | 2         | 0.12%   |
| Vizio D40f-J09 VIZ1044 1920x1080 890x490mm 40.0-inch                    | 2         | 0.12%   |
| Vestel Elektronik 22W_LCD_TV VES3700 1920x540                           | 2         | 0.12%   |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1209x680mm 54.6-inch          | 2         | 0.12%   |
| Sceptre Tech Sceptre F24 SPT09AB 1920x1080 530x290mm 23.8-inch          | 2         | 0.12%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 2         | 0.12%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch   | 2         | 0.12%   |
| Samsung Electronics LCD Monitor SAM0F14 3840x2160 1872x1053mm 84.6-inch | 2         | 0.12%   |
| Samsung Electronics C49HG9x SAM0E5D 3840x1080 1196x336mm 48.9-inch      | 2         | 0.12%   |
| Samsung Electronics C27R50x SAM0F9D 1920x1080 598x336mm 27.0-inch       | 2         | 0.12%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 2         | 0.12%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                 | 2         | 0.12%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                      | 2         | 0.12%   |
| ONN ONA18HO015 ONN0101 1920x1080 698x393mm 31.5-inch                    | 2         | 0.12%   |
| MStar TV MST0030 1920x1080 708x398mm 32.0-inch                          | 2         | 0.12%   |
| MSI Optix MAG24C MSI1462 1920x1080 521x293mm 23.5-inch                  | 2         | 0.12%   |
| Microsoft Xbox One MSH0001 1920x1080 700x390mm 31.5-inch                | 2         | 0.12%   |
| Lenovo LEN G34w-10 LEN66A1 3440x1440 797x334mm 34.0-inch                | 2         | 0.12%   |
| Hitachi HISENSE HEC002F 3840x2160 1872x1053mm 84.6-inch                 | 2         | 0.12%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch                | 2         | 0.12%   |
| Goldstar ULTRAGEAR GSM774A 3440x1440 800x335mm 34.1-inch                | 2         | 0.12%   |
| Goldstar ULTRAGEAR GSM5BB2 1920x1080 527x296mm 23.8-inch                | 2         | 0.12%   |
| Goldstar ULTRAGEAR GSM5B8D 1920x1080 600x303mm 26.5-inch                | 2         | 0.12%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch                 | 2         | 0.12%   |
| Goldstar QHD GSM778E 2560x1440 698x392mm 31.5-inch                      | 2         | 0.12%   |
| Goldstar FULL HD GSM5BDF 1920x1080 480x270mm 21.7-inch                  | 2         | 0.12%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 800x1280           | 1145      | 70.12%  |
| 1920x1080 (FHD)    | 249       | 15.25%  |
| 3840x2160 (4K)     | 94        | 5.76%   |
| 2560x1440 (QHD)    | 43        | 2.63%   |
| 1366x768 (WXGA)    | 26        | 1.59%   |
| 3440x1440          | 18        | 1.1%    |
| 2560x1600          | 10        | 0.61%   |
| 2560x1080          | 10        | 0.61%   |
| 3840x1080          | 3         | 0.18%   |
| 1920x1200 (WUXGA)  | 3         | 0.18%   |
| 1680x1050 (WSXGA+) | 3         | 0.18%   |
| 1600x900 (HD+)     | 3         | 0.18%   |
| 1440x900 (WXGA+)   | 3         | 0.18%   |
| 1360x768           | 3         | 0.18%   |
| 1280x800 (WXGA)    | 3         | 0.18%   |
| 1200x1920          | 3         | 0.18%   |
| 3840x1600          | 2         | 0.12%   |
| 2880x1800          | 2         | 0.12%   |
| 1600x2560          | 2         | 0.12%   |
| 1280x1024 (SXGA)   | 2         | 0.12%   |
| 1024x768 (XGA)     | 2         | 0.12%   |
| 3840x2400          | 1         | 0.06%   |
| 3200x1800 (QHD+)   | 1         | 0.06%   |
| 1920x800           | 1         | 0.06%   |
| 1920x540           | 1         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 7       | 1003      | 60.13%  |
| 3       | 167       | 10.01%  |
| 27      | 76        | 4.56%   |
| 15      | 57        | 3.42%   |
| 24      | 44        | 2.64%   |
| 23      | 43        | 2.58%   |
| 21      | 32        | 1.92%   |
| 31      | 29        | 1.74%   |
| 84      | 24        | 1.44%   |
| 34      | 23        | 1.38%   |
| 72      | 13        | 0.78%   |
| 54      | 13        | 0.78%   |
| 40      | 13        | 0.78%   |
| 32      | 11        | 0.66%   |
| 13      | 11        | 0.66%   |
| 17      | 9         | 0.54%   |
| 14      | 9         | 0.54%   |
| 16      | 8         | 0.48%   |
| Unknown | 7         | 0.42%   |
| 65      | 6         | 0.36%   |
| 57      | 5         | 0.3%    |
| 36      | 5         | 0.3%    |
| 86      | 4         | 0.24%   |
| 55      | 4         | 0.24%   |
| 19      | 4         | 0.24%   |
| 11      | 4         | 0.24%   |
| 52      | 3         | 0.18%   |
| 35      | 3         | 0.18%   |
| 26      | 3         | 0.18%   |
| 22      | 3         | 0.18%   |
| 18      | 3         | 0.18%   |
| 8       | 3         | 0.18%   |
| 69      | 2         | 0.12%   |
| 64      | 2         | 0.12%   |
| 49      | 2         | 0.12%   |
| 47      | 2         | 0.12%   |
| 43      | 2         | 0.12%   |
| 42      | 2         | 0.12%   |
| 33      | 2         | 0.12%   |
| 25      | 2         | 0.12%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 1-100       | 1148      | 70.09%  |
| 501-600     | 153       | 9.34%   |
| 301-350     | 69        | 4.21%   |
| 701-800     | 45        | 2.75%   |
| 1501-2000   | 44        | 2.69%   |
| 401-500     | 41        | 2.5%    |
| 601-700     | 39        | 2.38%   |
| 1001-1500   | 35        | 2.14%   |
| 801-900     | 18        | 1.1%    |
| 201-300     | 16        | 0.98%   |
| 351-400     | 15        | 0.92%   |
| Unknown     | 7         | 0.43%   |
| 101-200     | 4         | 0.24%   |
| 901-1000    | 4         | 0.24%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 0.67  | 926       | 56.57%  |
| 16/9  | 397       | 24.25%  |
| 6/5   | 167       | 10.2%   |
| 0.62  | 78        | 4.76%   |
| 21/9  | 28        | 1.71%   |
| 16/10 | 24        | 1.47%   |
| 0.56  | 5         | 0.31%   |
| 32/9  | 4         | 0.24%   |
| 5/4   | 2         | 0.12%   |
| 4/3   | 2         | 0.12%   |
| 3/2   | 1         | 0.06%   |
| 2.12  | 1         | 0.06%   |
| 1.00  | 1         | 0.06%   |
| 0.63  | 1         | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 1-40           | 1152      | 70.16%  |
| 201-250        | 98        | 5.97%   |
| 301-350        | 79        | 4.81%   |
| More than 1000 | 77        | 4.69%   |
| 351-500        | 67        | 4.08%   |
| 101-110        | 60        | 3.65%   |
| 501-1000       | 29        | 1.77%   |
| 251-300        | 19        | 1.16%   |
| 81-90          | 13        | 0.79%   |
| 151-200        | 12        | 0.73%   |
| 121-130        | 8         | 0.49%   |
| 71-80          | 7         | 0.43%   |
| Unknown        | 7         | 0.43%   |
| 51-60          | 4         | 0.24%   |
| 141-150        | 4         | 0.24%   |
| 111-120        | 4         | 0.24%   |
| 91-100         | 2         | 0.12%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 161-240       | 1007      | 61.74%  |
| 51-100        | 223       | 13.67%  |
| More than 240 | 177       | 10.85%  |
| 101-120       | 101       | 6.19%   |
| 121-160       | 73        | 4.48%   |
| 1-50          | 43        | 2.64%   |
| Unknown       | 7         | 0.43%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1081      | 73.89%  |
| 2     | 365       | 24.95%  |
| 3     | 15        | 1.03%   |
| 4     | 2         | 0.14%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 1325      | 75.93%  |
| ASIX Electronics              | 212       | 12.15%  |
| Qualcomm                      | 76        | 4.36%   |
| Intel                         | 52        | 2.98%   |
| Qualcomm Atheros              | 14        | 0.8%    |
| DisplayLink                   | 11        | 0.63%   |
| Microsoft                     | 8         | 0.46%   |
| MediaTek                      | 6         | 0.34%   |
| TP-Link                       | 5         | 0.29%   |
| Lenovo                        | 5         | 0.29%   |
| Broadcom                      | 5         | 0.29%   |
| Ralink Technology             | 4         | 0.23%   |
| Broadcom Limited              | 4         | 0.23%   |
| Samsung Electronics           | 3         | 0.17%   |
| Google                        | 2         | 0.11%   |
| Edimax Technology             | 2         | 0.11%   |
| Dell                          | 2         | 0.11%   |
| ASUSTek Computer              | 2         | 0.11%   |
| ZyXEL Communications          | 1         | 0.06%   |
| Raspberry Pi                  | 1         | 0.06%   |
| OnePlus Technology (Shenzhen) | 1         | 0.06%   |
| Marvell Technology Group      | 1         | 0.06%   |
| Davicom Semiconductor         | 1         | 0.06%   |
| AVM                           | 1         | 0.06%   |
| Artery Technology             | 1         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 1260      | 63.16%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 214       | 10.73%  |
| ASIX AX88179 Gigabit Ethernet                                          | 211       | 10.58%  |
| Qualcomm QCNFA765 Wireless Network Adapter                             | 76        | 3.81%   |
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 28        | 1.4%    |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 24        | 1.2%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 10        | 0.5%    |
| Intel Wi-Fi 6 AX200                                                    | 8         | 0.4%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 7         | 0.35%   |
| Intel Wi-Fi 6 AX201                                                    | 7         | 0.35%   |
| Microsoft Xbox Wireless Adapter for Windows                            | 6         | 0.3%    |
| Realtek RTL8125 2.5GbE Controller                                      | 5         | 0.25%   |
| Realtek 802.11ac NIC                                                   | 4         | 0.2%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 4         | 0.2%    |
| Intel Wireless 3165                                                    | 4         | 0.2%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 3         | 0.15%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 3         | 0.15%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 3         | 0.15%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 3         | 0.15%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 3         | 0.15%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 3         | 0.15%   |
| Lenovo USB-C Dock Ethernet                                             | 3         | 0.15%   |
| Intel Wireless 7265                                                    | 3         | 0.15%   |
| DisplayLink Dell Universal Dock D6000                                  | 3         | 0.15%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 3         | 0.15%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 3         | 0.15%   |
| TP-Link 802.11ac NIC                                                   | 2         | 0.1%    |
| Samsung Galaxy series, misc. (tethering mode)                          | 2         | 0.1%    |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                    | 2         | 0.1%    |
| Realtek Killer E2600 GbE Controller                                    | 2         | 0.1%    |
| Ralink RT5370 Wireless Adapter                                         | 2         | 0.1%    |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 2         | 0.1%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 2         | 0.1%    |
| Intel Wireless 8260                                                    | 2         | 0.1%    |
| Intel WiFi Link 5100                                                   | 2         | 0.1%    |
| Intel I211 Gigabit Network Connection                                  | 2         | 0.1%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 2         | 0.1%    |
| Intel Comet Lake PCH CNVi WiFi                                         | 2         | 0.1%    |
| Intel Cannon Lake PCH CNVi WiFi                                        | 2         | 0.1%    |
| DisplayLink Plugable UD-3900                                           | 2         | 0.1%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 1274      | 87.62%  |
| Qualcomm              | 76        | 5.23%   |
| Intel                 | 51        | 3.51%   |
| Qualcomm Atheros      | 13        | 0.89%   |
| Microsoft             | 8         | 0.55%   |
| MediaTek              | 6         | 0.41%   |
| TP-Link               | 5         | 0.34%   |
| Broadcom              | 5         | 0.34%   |
| Ralink Technology     | 4         | 0.28%   |
| Broadcom Limited      | 4         | 0.28%   |
| Edimax Technology     | 2         | 0.14%   |
| Dell                  | 2         | 0.14%   |
| ASUSTek Computer      | 2         | 0.14%   |
| ZyXEL Communications  | 1         | 0.07%   |
| AVM                   | 1         | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 1260      | 86.3%   |
| Qualcomm QCNFA765 Wireless Network Adapter                           | 76        | 5.21%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 10        | 0.68%   |
| Intel Wi-Fi 6 AX200                                                  | 8         | 0.55%   |
| Intel Wi-Fi 6 AX201                                                  | 7         | 0.48%   |
| Microsoft Xbox Wireless Adapter for Windows                          | 6         | 0.41%   |
| Realtek 802.11ac NIC                                                 | 4         | 0.27%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 4         | 0.27%   |
| Intel Wireless 3165                                                  | 4         | 0.27%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 3         | 0.21%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 3         | 0.21%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 3         | 0.21%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 3         | 0.21%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 3         | 0.21%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 3         | 0.21%   |
| Intel Wireless 7265                                                  | 3         | 0.21%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 3         | 0.21%   |
| TP-Link 802.11ac NIC                                                 | 2         | 0.14%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                  | 2         | 0.14%   |
| Ralink RT5370 Wireless Adapter                                       | 2         | 0.14%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 2         | 0.14%   |
| Intel Wireless 8260                                                  | 2         | 0.14%   |
| Intel WiFi Link 5100                                                 | 2         | 0.14%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 2         | 0.14%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 2         | 0.14%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 2         | 0.14%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 2         | 0.14%   |
| ZyXEL 802.11ax WLAN Adapter                                          | 1         | 0.07%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 1         | 0.07%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                           | 1         | 0.07%   |
| TP-Link Archer T4U ver.3                                             | 1         | 0.07%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 1         | 0.07%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller          | 1         | 0.07%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 1         | 0.07%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 1         | 0.07%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter              | 1         | 0.07%   |
| Realtek RTL8723DE Wireless Network Adapter                           | 1         | 0.07%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                           | 1         | 0.07%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 1         | 0.07%   |
| Microsoft XBOX ACC                                                   | 1         | 0.07%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 280       | 52.63%  |
| ASIX Electronics              | 212       | 39.85%  |
| DisplayLink                   | 11        | 2.07%   |
| Intel                         | 9         | 1.69%   |
| Lenovo                        | 5         | 0.94%   |
| Qualcomm Atheros              | 4         | 0.75%   |
| Samsung Electronics           | 3         | 0.56%   |
| Broadcom                      | 3         | 0.56%   |
| Google                        | 2         | 0.38%   |
| OnePlus Technology (Shenzhen) | 1         | 0.19%   |
| Marvell Technology Group      | 1         | 0.19%   |
| Davicom Semiconductor         | 1         | 0.19%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 214       | 40.15%  |
| ASIX AX88179 Gigabit Ethernet                                          | 211       | 39.59%  |
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 28        | 5.25%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 24        | 4.5%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 7         | 1.31%   |
| Realtek RTL8125 2.5GbE Controller                                      | 5         | 0.94%   |
| Lenovo USB-C Dock Ethernet                                             | 3         | 0.56%   |
| DisplayLink Dell Universal Dock D6000                                  | 3         | 0.56%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 3         | 0.56%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2         | 0.38%   |
| Realtek Killer E2600 GbE Controller                                    | 2         | 0.38%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 2         | 0.38%   |
| Intel I211 Gigabit Network Connection                                  | 2         | 0.38%   |
| DisplayLink Plugable UD-3900                                           | 2         | 0.38%   |
| DisplayLink DL-Dock                                                    | 2         | 0.38%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1         | 0.19%   |
| Realtek PCIe GbE Family Controller                                     | 1         | 0.19%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 0.19%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1         | 0.19%   |
| OnePlus (Shenzhen) OnePlus                                             | 1         | 0.19%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 1         | 0.19%   |
| Lenovo ThinkPad TBT 3 Dock                                             | 1         | 0.19%   |
| Lenovo ThinkPad Lan                                                    | 1         | 0.19%   |
| Intel Ethernet Controller I225-V                                       | 1         | 0.19%   |
| Intel Ethernet Controller I219-V                                       | 1         | 0.19%   |
| Intel Ethernet Connection I217-LM                                      | 1         | 0.19%   |
| Intel Ethernet Connection (5) I219-LM                                  | 1         | 0.19%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 0.19%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 1         | 0.19%   |
| Intel 82567LM Gigabit Network Connection                               | 1         | 0.19%   |
| Google Pixel 7 Pro                                                     | 1         | 0.19%   |
| Google Pixel 6                                                         | 1         | 0.19%   |
| DisplayLink ThinkPad USB 3.0 Ultra Dock                                | 1         | 0.19%   |
| DisplayLink Targus USB3.0 DV2K Dock w Power                            | 1         | 0.19%   |
| DisplayLink PR09 DisplayPort Dock                                      | 1         | 0.19%   |
| DisplayLink LAPDOCK                                                    | 1         | 0.19%   |
| Davicom DM9621A USB To FastEther                                       | 1         | 0.19%   |
| ASIX AX88772B                                                          | 1         | 0.19%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1428      | 73.27%  |
| Ethernet | 519       | 26.63%  |
| Modem    | 2         | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1365      | 89.45%  |
| Ethernet | 161       | 10.55%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1373      | 95.88%  |
| 2     | 56        | 3.91%   |
| 0     | 3         | 0.21%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 873       | 59.75%  |
| Yes  | 588       | 40.25%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| IMC Networks                    | 1254      | 93.58%  |
| Intel                           | 46        | 3.43%   |
| Realtek Semiconductor           | 10        | 0.75%   |
| Qualcomm Atheros Communications | 9         | 0.67%   |
| Apple                           | 5         | 0.37%   |
| Cambridge Silicon Radio         | 3         | 0.22%   |
| SINO WEALTH                     | 2         | 0.15%   |
| Foxconn / Hon Hai               | 2         | 0.15%   |
| Dell                            | 2         | 0.15%   |
| Realtek                         | 1         | 0.07%   |
| MediaTek                        | 1         | 0.07%   |
| Lite-On Technology              | 1         | 0.07%   |
| HTC (High Tech Computer)        | 1         | 0.07%   |
| Broadcom                        | 1         | 0.07%   |
| ASUSTek Computer                | 1         | 0.07%   |
| Alps Electric                   | 1         | 0.07%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| IMC Networks Bluetooth Radio                                         | 1253      | 93.51%  |
| Intel AX201 Bluetooth                                                | 10        | 0.75%   |
| Intel AX210 Bluetooth                                                | 9         | 0.67%   |
| Realtek Bluetooth Radio                                              | 8         | 0.6%    |
| Intel Bluetooth wireless interface                                   | 8         | 0.6%    |
| Intel AX200 Bluetooth                                                | 8         | 0.6%    |
| Qualcomm Atheros  Bluetooth Device                                   | 4         | 0.3%    |
| Intel Bluetooth Device                                               | 3         | 0.22%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 3         | 0.22%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 3         | 0.22%   |
| Apple Bluetooth USB Host Controller                                  | 3         | 0.22%   |
| SINO WEALTH RK Bluetooth Keyboar                                     | 2         | 0.15%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 2         | 0.15%   |
| Qualcomm Atheros AR9462 Bluetooth                                    | 2         | 0.15%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 2         | 0.15%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 2         | 0.15%   |
| Apple Bluetooth Host Controller                                      | 2         | 0.15%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 1         | 0.07%   |
| Realtek 802.11ac WLAN Adapter                                        | 1         | 0.07%   |
| Realtek Bluetooth Radio                                              | 1         | 0.07%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 1         | 0.07%   |
| MediaTek Wireless_Device                                             | 1         | 0.07%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 1         | 0.07%   |
| Intel AX211 Bluetooth                                                | 1         | 0.07%   |
| IMC Networks Wireless_Device                                         | 1         | 0.07%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1         | 0.07%   |
| Foxconn / Hon Hai Wireless_Device                                    | 1         | 0.07%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                         | 1         | 0.07%   |
| Dell Broadcom BCM20702A0 Bluetooth                                   | 1         | 0.07%   |
| Dell BCM20702A0 Bluetooth Module                                     | 1         | 0.07%   |
| Broadcom BCM20702A0                                                  | 1         | 0.07%   |
| ASUS ASUS USB-BT500                                                  | 1         | 0.07%   |
| Alps Electric BCM2046 Bluetooth Device                               | 1         | 0.07%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| AMD                         | 1381      | 86.75%  |
| Intel                       | 51        | 3.2%    |
| Nvidia                      | 24        | 1.51%   |
| Logitech                    | 16        | 1.01%   |
| Sony                        | 11        | 0.69%   |
| Realtek Semiconductor       | 9         | 0.57%   |
| Kingston Technology         | 8         | 0.5%    |
| Generalplus Technology      | 8         | 0.5%    |
| C-Media Electronics         | 8         | 0.5%    |
| Razer USA                   | 7         | 0.44%   |
| Lenovo                      | 6         | 0.38%   |
| Nreal                       | 5         | 0.31%   |
| Hewlett-Packard             | 5         | 0.31%   |
| Corsair                     | 4         | 0.25%   |
| SteelSeries ApS             | 3         | 0.19%   |
| Plantronics                 | 3         | 0.19%   |
| JMTek                       | 3         | 0.19%   |
| GN Netcom                   | 3         | 0.19%   |
| Focusrite-Novation          | 3         | 0.19%   |
| Blue Microphones            | 3         | 0.19%   |
| Apple                       | 2         | 0.13%   |
| Antlion Audio               | 2         | 0.13%   |
| Yamaha                      | 1         | 0.06%   |
| Universal Audio             | 1         | 0.06%   |
| Texas Instruments           | 1         | 0.06%   |
| Tenx Technology             | 1         | 0.06%   |
| Teenage Engineering         | 1         | 0.06%   |
| Silicon Motion              | 1         | 0.06%   |
| SHI GANTECH                 | 1         | 0.06%   |
| PreSonus Audio Electronics  | 1         | 0.06%   |
| Nordic Semiconductor ASA    | 1         | 0.06%   |
| Native Instruments          | 1         | 0.06%   |
| MVSILICON.INC.              | 1         | 0.06%   |
| MosArt Semiconductor        | 1         | 0.06%   |
| miniDSP                     | 1         | 0.06%   |
| KTMicro                     | 1         | 0.06%   |
| KORG                        | 1         | 0.06%   |
| HTC (High Tech Computer)    | 1         | 0.06%   |
| FiiO Electronics Technology | 1         | 0.06%   |
| Comtrue                     | 1         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| AMD Rembrandt Radeon High Definition Audio Controller               | 1349      | 82.31%  |
| AMD Family 17h/19h HD Audio Controller                              | 31        | 1.89%   |
| AMD Renoir Radeon High Definition Audio Controller                  | 12        | 0.73%   |
| Realtek Semiconductor USB Audio                                     | 9         | 0.55%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller         | 8         | 0.49%   |
| Generalplus Technology USB Audio Device                             | 8         | 0.49%   |
| Sony DualSense wireless controller (PS5)                            | 6         | 0.37%   |
| Nvidia Audio device                                                 | 5         | 0.31%   |
| Nreal Air                                                           | 5         | 0.31%   |
| Kingston Technology HyperX 7.1 Audio                                | 5         | 0.31%   |
| Intel Cannon Lake PCH cAVS                                          | 5         | 0.31%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 5         | 0.31%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                 | 5         | 0.31%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller      | 4         | 0.24%   |
| Intel Haswell-ULT HD Audio Controller                               | 4         | 0.24%   |
| Intel 8 Series HD Audio Controller                                  | 4         | 0.24%   |
| AMD FCH Azalia Controller                                           | 4         | 0.24%   |
| Sony DualSense Edge wireless controller (PS5)                       | 3         | 0.18%   |
| Nvidia TU106 High Definition Audio Controller                       | 3         | 0.18%   |
| Logitech G733 Gaming Headset                                        | 3         | 0.18%   |
| Logitech G432 Gaming Headset                                        | 3         | 0.18%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                           | 3         | 0.18%   |
| JMTek USB PnP Audio Device                                          | 3         | 0.18%   |
| Intel Tiger Lake-H HD Audio Controller                              | 3         | 0.18%   |
| Intel Sunrise Point-LP HD Audio                                     | 3         | 0.18%   |
| Intel CM238 HD Audio Controller                                     | 3         | 0.18%   |
| Hewlett-Packard USB Audio                                           | 3         | 0.18%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                   | 3         | 0.18%   |
| AMD Trinity HDMI Audio Controller                                   | 3         | 0.18%   |
| AMD Starship/Matisse HD Audio Controller                            | 3         | 0.18%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                    | 3         | 0.18%   |
| SteelSeries ApS SteelSeries Arctis 7                                | 2         | 0.12%   |
| Sony DualShock 4 [CUH-ZCT2x]                                        | 2         | 0.12%   |
| Nvidia GP107GL High Definition Audio Controller                     | 2         | 0.12%   |
| Nvidia GP104 High Definition Audio Controller                       | 2         | 0.12%   |
| Nvidia GK107 HDMI Audio Controller                                  | 2         | 0.12%   |
| Nvidia GA104 High Definition Audio Controller                       | 2         | 0.12%   |
| Logitech G935 Gaming Headset                                        | 2         | 0.12%   |
| Logitech G435 Wireless Gaming Headset                               | 2         | 0.12%   |
| Logitech Blue Microphones                                           | 2         | 0.12%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 14        | 60.87%  |
| Micron Technology   | 6         | 26.09%  |
| SK hynix            | 1         | 4.35%   |
| Nanya Technology    | 1         | 4.35%   |
| Kingston            | 1         | 4.35%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Samsung RAM K3LK7K70BM-BGCP000 4096MB SODIMM 4266MT/s      | 12        | 52.17%  |
| Micron RAM MT62F1G32D4DR-031 WT 4GB SODIMM LPDDR5 6400MT/s | 2         | 8.7%    |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 4GB DIMM LPDDR5 6400MT/s   | 1         | 4.35%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s   | 1         | 4.35%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s     | 1         | 4.35%   |
| Nanya RAM NT2GT64U8HD0BN-AD 2GB SODIMM DDR2 800MT/s        | 1         | 4.35%   |
| Micron RAM MT62F2G32D4DS-026 WT 8GB SODIMM LPDDR5 7500MT/s | 1         | 4.35%   |
| Micron RAM Module 2GB SODIMM DDR3 1600MT/s                 | 1         | 4.35%   |
| Micron RAM 8JTF5126 4HZ1G6D 1 4GB SODIMM DDR3 1600MT/s     | 1         | 4.35%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s       | 1         | 4.35%   |
| Kingston RAM 9905417-054.A00G 4GB SODIMM DDR3 1600MT/s     | 1         | 4.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| LPDDR5 | 16        | 80%     |
| DDR3   | 2         | 10%     |
| SDRAM  | 1         | 5%      |
| DDR4   | 1         | 5%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 19        | 95%     |
| DIMM   | 1         | 5%      |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Notebooks | Percent |
|------|-----------|---------|
| 4096 | 16        | 80%     |
| 8192 | 2         | 10%     |
| 2048 | 2         | 10%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 4266  | 12        | 60%     |
| 6400  | 3         | 15%     |
| 1600  | 2         | 10%     |
| 7500  | 1         | 5%      |
| 3200  | 1         | 5%      |
| 2048  | 1         | 5%      |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Canon               | 3         | 37.5%   |
| Hewlett-Packard     | 2         | 25%     |
| Samsung Electronics | 1         | 12.5%   |
| KODAK               | 1         | 12.5%   |
| Dymo-CoStar         | 1         | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                       | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Samsung M2020 Series        | 1         | 12.5%   |
| KODAK ESP 5 AiO             | 1         | 12.5%   |
| HP LaserJet CP1525nw/x      | 1         | 12.5%   |
| HP DeskJet 2700 series      | 1         | 12.5%   |
| Dymo-CoStar LabelWriter 400 | 1         | 12.5%   |
| Canon PIXMA MG3600 Series   | 1         | 12.5%   |
| Canon PIXMA MG2500 Series   | 1         | 12.5%   |
| Canon LiDE 400              | 1         | 12.5%   |

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
| Logitech                               | 17        | 15.32%  |
| Microdia                               | 13        | 11.71%  |
| Chicony Electronics                    | 12        | 10.81%  |
| Realtek Semiconductor                  | 9         | 8.11%   |
| Apple                                  | 7         | 6.31%   |
| IMC Networks                           | 6         | 5.41%   |
| Tripath Technology                     | 5         | 4.5%    |
| Cheng Uei Precision Industry (Foxlink) | 5         | 4.5%    |
| Sunplus Innovation Technology          | 4         | 3.6%    |
| Samsung Electronics                    | 4         | 3.6%    |
| Quanta                                 | 4         | 3.6%    |
| Microsoft                              | 3         | 2.7%    |
| Luxvisions Innotech Limited            | 3         | 2.7%    |
| Bison Electronics                      | 3         | 2.7%    |
| Alpha Imaging Technology               | 2         | 1.8%    |
| Acer                                   | 2         | 1.8%    |
| Syntek                                 | 1         | 0.9%    |
| Suyin                                  | 1         | 0.9%    |
| SunplusIT                              | 1         | 0.9%    |
| Silicon Motion                         | 1         | 0.9%    |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.9%    |
| Ricoh                                  | 1         | 0.9%    |
| Razer USA                              | 1         | 0.9%    |
| Lite-On Technology                     | 1         | 0.9%    |
| HTC (High Tech Computer)               | 1         | 0.9%    |
| Google                                 | 1         | 0.9%    |
| Generalplus Technology                 | 1         | 0.9%    |
| AVerMedia Technologies                 | 1         | 0.9%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Tripath USB Camera                                              | 5         | 4.5%    |
| Samsung Galaxy series, misc. (MTP mode)                         | 4         | 3.6%    |
| Microdia Webcam Vitade AF                                       | 4         | 3.6%    |
| Logitech HD Pro Webcam C920                                     | 4         | 3.6%    |
| IMC Networks USB2.0 HD UVC WebCam                               | 4         | 3.6%    |
| Microdia Integrated_Webcam_HD                                   | 3         | 2.7%    |
| Chicony HP TrueVision HD Camera                                 | 3         | 2.7%    |
| Chicony HD User Facing                                          | 3         | 2.7%    |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                 | 3         | 2.7%    |
| Apple FaceTime HD Camera                                        | 3         | 2.7%    |
| Sunplus Asus Webcam                                             | 2         | 1.8%    |
| Realtek Thronmax Stream Go Pro Webcam                           | 2         | 1.8%    |
| Microsoft LifeCam HD-3000                                       | 2         | 1.8%    |
| Microdia Integrated Webcam                                      | 2         | 1.8%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 2         | 1.8%    |
| Logitech Webcam C270                                            | 2         | 1.8%    |
| Logitech HD Webcam C615                                         | 2         | 1.8%    |
| Chicony Integrated Camera                                       | 2         | 1.8%    |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 2         | 1.8%    |
| Alpha Imaging Integrated_Webcam_8M                              | 2         | 1.8%    |
| Acer Integrated Camera                                          | 2         | 1.8%    |
| Syntek Integrated Camera                                        | 1         | 0.9%    |
| Suyin HP Truevision HD                                          | 1         | 0.9%    |
| SunplusIT CODi A05020 Webcam                                    | 1         | 0.9%    |
| Sunplus Integrated_Webcam_FHD                                   | 1         | 0.9%    |
| Sunplus Dell E5570 integrated webcam                            | 1         | 0.9%    |
| Silicon Motion WebCam SC-13HDL11939N                            | 1         | 0.9%    |
| Shenzhen Kingcome Optoelectronic 720p HD Camera                 | 1         | 0.9%    |
| Ricoh Sony Vaio Integrated Webcam                               | 1         | 0.9%    |
| Realtek USB Camera                                              | 1         | 0.9%    |
| Realtek Integrated_Webcam_HD                                    | 1         | 0.9%    |
| Realtek Integrated_Webcam_FHD                                   | 1         | 0.9%    |
| Realtek Integrated Webcam                                       | 1         | 0.9%    |
| Realtek HP Truevision HD integrated webcam                      | 1         | 0.9%    |
| Realtek FULL HD 1080P Webcam                                    | 1         | 0.9%    |
| Realtek EasyCamera                                              | 1         | 0.9%    |
| Razer USA Razer Kiyo X                                          | 1         | 0.9%    |
| Quanta VGA WebCam                                               | 1         | 0.9%    |
| Quanta HP Wide Vision HD Camera                                 | 1         | 0.9%    |
| Quanta HD Webcam                                                | 1         | 0.9%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Upek                       | 1         | 33.33%  |
| Shenzhen Goodix Technology | 1         | 33.33%  |
| Focal-systems.Corp         | 1         | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 33.33%  |
| Shenzhen Goodix  FingerPrint Device                    | 1         | 33.33%  |
| Focal-systems.Corp FT9201Fingerprint.                  | 1         | 33.33%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 3         | 50%     |
| SCM Microsystems      | 1         | 16.67%  |
| Realtek Semiconductor | 1         | 16.67%  |
| Lenovo                | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| SCM Microsystems SCR3500 A Contact Reader                                    | 1         | 16.67%  |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 16.67%  |
| Lenovo Smartcard Keyboard                                                    | 1         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 16.67%  |
| Broadcom 5880                                                                | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1379      | 96.23%  |
| 1     | 42        | 2.93%   |
| 2     | 11        | 0.77%   |
| 3     | 1         | 0.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 22        | 32.84%  |
| Graphics card         | 15        | 22.39%  |
| Multimedia controller | 11        | 16.42%  |
| Camera                | 5         | 7.46%   |
| Chipcard              | 4         | 5.97%   |
| Fingerprint reader    | 3         | 4.48%   |
| Storage/nvme          | 2         | 2.99%   |
| Card reader           | 2         | 2.99%   |
| Sound                 | 1         | 1.49%   |
| Net/ethernet          | 1         | 1.49%   |
| Modem                 | 1         | 1.49%   |

