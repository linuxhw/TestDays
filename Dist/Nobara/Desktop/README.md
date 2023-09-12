Nobara - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for Nobara.

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

Total: 418

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock        | B460 Phantom Gaming 4       | [6521407977](https://linux-hardware.org/?probe=6521407977) | Sep 06, 2023 |
| MSI           | MPG B650I EDGE WIFI         | [b395463f0e](https://linux-hardware.org/?probe=b395463f0e) | Sep 06, 2023 |
| Gigabyte      | B550M K                     | [95d0f9505b](https://linux-hardware.org/?probe=95d0f9505b) | Sep 03, 2023 |
| MSI           | PRO X670-P WIFI             | [174cff0e19](https://linux-hardware.org/?probe=174cff0e19) | Sep 02, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [07a44c323f](https://linux-hardware.org/?probe=07a44c323f) | Sep 01, 2023 |
| Pegatron      | 2AB6                        | [a0649549b3](https://linux-hardware.org/?probe=a0649549b3) | Sep 01, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c865cde7a2](https://linux-hardware.org/?probe=c865cde7a2) | Sep 01, 2023 |
| ASRock        | Z490M Pro4                  | [e07d4a9c90](https://linux-hardware.org/?probe=e07d4a9c90) | Aug 30, 2023 |
| MSI           | Z170A GAMING M3             | [cdbff2ba81](https://linux-hardware.org/?probe=cdbff2ba81) | Aug 28, 2023 |
| Gigabyte      | H410M H                     | [a4fe691c36](https://linux-hardware.org/?probe=a4fe691c36) | Aug 28, 2023 |
| ASRock        | B650 PG Lightning           | [de1d12ec95](https://linux-hardware.org/?probe=de1d12ec95) | Aug 24, 2023 |
| Gigabyte      | H310M H x.x                 | [523acf034e](https://linux-hardware.org/?probe=523acf034e) | Aug 23, 2023 |
| MSI           | PRO X670-P WIFI             | [0887b2e549](https://linux-hardware.org/?probe=0887b2e549) | Aug 20, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [f7d3395ffc](https://linux-hardware.org/?probe=f7d3395ffc) | Aug 18, 2023 |
| ASUSTek       | Pro B550M-C                 | [712bd65558](https://linux-hardware.org/?probe=712bd65558) | Aug 16, 2023 |
| Pegatron      | Benicia                     | [0ab394fa9e](https://linux-hardware.org/?probe=0ab394fa9e) | Aug 15, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [e9b2347b46](https://linux-hardware.org/?probe=e9b2347b46) | Aug 14, 2023 |
| Gigabyte      | G1.Sniper M3-CF             | [f4d0fd6811](https://linux-hardware.org/?probe=f4d0fd6811) | Aug 12, 2023 |
| Gigabyte      | G1.Sniper M3-CF             | [a5681e12d3](https://linux-hardware.org/?probe=a5681e12d3) | Aug 12, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E GENE    | [f016fa3756](https://linux-hardware.org/?probe=f016fa3756) | Aug 11, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | [d490bb32ec](https://linux-hardware.org/?probe=d490bb32ec) | Aug 10, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | [fffee60e72](https://linux-hardware.org/?probe=fffee60e72) | Aug 10, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [d9c999ffa3](https://linux-hardware.org/?probe=d9c999ffa3) | Aug 08, 2023 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | [f7c7290847](https://linux-hardware.org/?probe=f7c7290847) | Aug 08, 2023 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | [9a0fa703d7](https://linux-hardware.org/?probe=9a0fa703d7) | Aug 07, 2023 |
| Gigabyte      | Z270P-D3-CF                 | [ec7fa20ab4](https://linux-hardware.org/?probe=ec7fa20ab4) | Aug 06, 2023 |
| ASRock        | B550M Steel Legend          | [d9107b9cb9](https://linux-hardware.org/?probe=d9107b9cb9) | Aug 06, 2023 |
| MSI           | FM2-A55M-E33                | [28384fb38c](https://linux-hardware.org/?probe=28384fb38c) | Aug 06, 2023 |
| Gigabyte      | Z270P-D3-CF                 | [5ec7de1222](https://linux-hardware.org/?probe=5ec7de1222) | Aug 06, 2023 |
| MSI           | PRO X670-P WIFI             | [cd0d64a16a](https://linux-hardware.org/?probe=cd0d64a16a) | Aug 03, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [53c9161fc5](https://linux-hardware.org/?probe=53c9161fc5) | Aug 03, 2023 |
| AOpen         | iBDWMUx-MD R1.04            | [18dad15a33](https://linux-hardware.org/?probe=18dad15a33) | Aug 02, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | [ceb7e754a1](https://linux-hardware.org/?probe=ceb7e754a1) | Aug 02, 2023 |
| ASRock        | Z170 Extreme6+              | [84c1a14a56](https://linux-hardware.org/?probe=84c1a14a56) | Aug 01, 2023 |
| Gigabyte      | B75M-D3H                    | [3aeae112c3](https://linux-hardware.org/?probe=3aeae112c3) | Jul 31, 2023 |
| NZXT          | N7 B650E                    | [38e481c3d5](https://linux-hardware.org/?probe=38e481c3d5) | Jul 29, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [513ac15990](https://linux-hardware.org/?probe=513ac15990) | Jul 28, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | [c9c42e4857](https://linux-hardware.org/?probe=c9c42e4857) | Jul 26, 2023 |
| ASUSTek       | X99-DELUXE II               | [35f41c1327](https://linux-hardware.org/?probe=35f41c1327) | Jul 25, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [567693892b](https://linux-hardware.org/?probe=567693892b) | Jul 23, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [228ded2955](https://linux-hardware.org/?probe=228ded2955) | Jul 21, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [5f9962eafc](https://linux-hardware.org/?probe=5f9962eafc) | Jul 21, 2023 |
| MSI           | B450M PRO-M2 V2             | [2109b6ace6](https://linux-hardware.org/?probe=2109b6ace6) | Jul 21, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [022d677eda](https://linux-hardware.org/?probe=022d677eda) | Jul 21, 2023 |
| MSI           | B450M BAZOOKA MAX WIFI      | [25311760a9](https://linux-hardware.org/?probe=25311760a9) | Jul 21, 2023 |
| ASRock        | Z170 Extreme6+              | [5ead4ab228](https://linux-hardware.org/?probe=5ead4ab228) | Jul 17, 2023 |
| HP            | 8906 SMVB                   | [70b7e2a7f5](https://linux-hardware.org/?probe=70b7e2a7f5) | Jul 16, 2023 |
| ASRock        | H370 Performance            | [43286f18d3](https://linux-hardware.org/?probe=43286f18d3) | Jul 16, 2023 |
| HP            | 3396                        | [5713dca497](https://linux-hardware.org/?probe=5713dca497) | Jul 15, 2023 |
| Gigabyte      | X399 DESIGNARE EX-CF        | [d8550d27e3](https://linux-hardware.org/?probe=d8550d27e3) | Jul 15, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [7026c5b007](https://linux-hardware.org/?probe=7026c5b007) | Jul 14, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [8e3cc576fd](https://linux-hardware.org/?probe=8e3cc576fd) | Jul 14, 2023 |
| MSI           | PRO Z690-A WIFI             | [d20f9ee7a7](https://linux-hardware.org/?probe=d20f9ee7a7) | Jul 14, 2023 |
| MSI           | Z87-G45 GAMING              | [110a53c220](https://linux-hardware.org/?probe=110a53c220) | Jul 13, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | [e612d95542](https://linux-hardware.org/?probe=e612d95542) | Jul 12, 2023 |
| Unknown       | EA A520M-E                  | [184201d556](https://linux-hardware.org/?probe=184201d556) | Jul 12, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [0e411803b2](https://linux-hardware.org/?probe=0e411803b2) | Jul 10, 2023 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | [429e4e7636](https://linux-hardware.org/?probe=429e4e7636) | Jul 10, 2023 |
| Acer          | Nitro N50-620               | [8286ddb9ae](https://linux-hardware.org/?probe=8286ddb9ae) | Jul 08, 2023 |
| Shenzhen M... | F6BFC                       | [f4f1e6f9ff](https://linux-hardware.org/?probe=f4f1e6f9ff) | Jul 05, 2023 |
| GPD           | G1618-03                    | [0cb58087bf](https://linux-hardware.org/?probe=0cb58087bf) | Jul 04, 2023 |
| Gigabyte      | B550M DS3H AC               | [626416c230](https://linux-hardware.org/?probe=626416c230) | Jul 03, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [ff0f73c325](https://linux-hardware.org/?probe=ff0f73c325) | Jul 02, 2023 |
| Gigabyte      | X670 GAMING X AX            | [e7e4a3562f](https://linux-hardware.org/?probe=e7e4a3562f) | Jul 02, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [488ebd160a](https://linux-hardware.org/?probe=488ebd160a) | Jul 02, 2023 |
| ASRock        | X299 Taichi CLX             | [ff1f31ff36](https://linux-hardware.org/?probe=ff1f31ff36) | Jul 01, 2023 |
| ASRock        | X299 Taichi CLX             | [d4362fb3ca](https://linux-hardware.org/?probe=d4362fb3ca) | Jul 01, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E GENE    | [c93f4f0d0b](https://linux-hardware.org/?probe=c93f4f0d0b) | Jun 30, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [5b780b9ebd](https://linux-hardware.org/?probe=5b780b9ebd) | Jun 24, 2023 |
| ASRock        | B85M Pro4                   | [0ee3f7532c](https://linux-hardware.org/?probe=0ee3f7532c) | Jun 23, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [379c36642b](https://linux-hardware.org/?probe=379c36642b) | Jun 22, 2023 |
| AOpen         | iBDWMUx-MD R1.04            | [2656caf6b8](https://linux-hardware.org/?probe=2656caf6b8) | Jun 22, 2023 |
| MSI           | H81M-E34                    | [ac0a9c170f](https://linux-hardware.org/?probe=ac0a9c170f) | Jun 22, 2023 |
| MSI           | H81M-E34                    | [666f5d0ce5](https://linux-hardware.org/?probe=666f5d0ce5) | Jun 22, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | [0f5435c665](https://linux-hardware.org/?probe=0f5435c665) | Jun 22, 2023 |
| ASRock        | Z370 Gaming-ITX/ac          | [e05a90c6c5](https://linux-hardware.org/?probe=e05a90c6c5) | Jun 16, 2023 |
| HP            | 8054                        | [97a4b34236](https://linux-hardware.org/?probe=97a4b34236) | Jun 15, 2023 |
| ASRock        | X470 Master SLI             | [448a3cf6b1](https://linux-hardware.org/?probe=448a3cf6b1) | Jun 15, 2023 |
| ASRock        | B650E Steel Legend WiFi     | [3edca35793](https://linux-hardware.org/?probe=3edca35793) | Jun 14, 2023 |
| ASUSTek       | PRIME B760M-A WIFI D4       | [6febc3ef2e](https://linux-hardware.org/?probe=6febc3ef2e) | Jun 13, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [6491127e6e](https://linux-hardware.org/?probe=6491127e6e) | Jun 09, 2023 |
| ASRock        | B450 Steel Legend           | [483ac7223f](https://linux-hardware.org/?probe=483ac7223f) | Jun 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [12736be80e](https://linux-hardware.org/?probe=12736be80e) | Jun 07, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [bc00b26e0a](https://linux-hardware.org/?probe=bc00b26e0a) | Jun 06, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [ee25039289](https://linux-hardware.org/?probe=ee25039289) | Jun 06, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [43c70efbe7](https://linux-hardware.org/?probe=43c70efbe7) | Jun 05, 2023 |
| Gigabyte      | X570 AORUS PRO              | [efa9cac1df](https://linux-hardware.org/?probe=efa9cac1df) | Jun 04, 2023 |
| ASRock        | FM2A68M-DG3+                | [3e7ad22b6b](https://linux-hardware.org/?probe=3e7ad22b6b) | Jun 03, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [9a91f8aedc](https://linux-hardware.org/?probe=9a91f8aedc) | Jun 02, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [259865e80e](https://linux-hardware.org/?probe=259865e80e) | Jun 01, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [54b872a39b](https://linux-hardware.org/?probe=54b872a39b) | May 31, 2023 |
| ASRock        | B650E Steel Legend WiFi     | [88d16bf040](https://linux-hardware.org/?probe=88d16bf040) | May 31, 2023 |
| Dell          | 0J3C2F A02                  | [c2640c22ff](https://linux-hardware.org/?probe=c2640c22ff) | May 27, 2023 |
| HP            | 1497                        | [94f79f2f74](https://linux-hardware.org/?probe=94f79f2f74) | May 27, 2023 |
| HP            | 1497                        | [d2cca6c2a1](https://linux-hardware.org/?probe=d2cca6c2a1) | May 27, 2023 |
| Shenzhen M... | F7BFC                       | [6bf848e58f](https://linux-hardware.org/?probe=6bf848e58f) | May 25, 2023 |
| AOpen         | iBDWMUx-MD R1.04            | [cc674d2878](https://linux-hardware.org/?probe=cc674d2878) | May 25, 2023 |
| ASRock        | AB350M Pro4                 | [1efd2eb268](https://linux-hardware.org/?probe=1efd2eb268) | May 24, 2023 |
| Gigabyte      | B550 GAMING X V2            | [c43cfd04ad](https://linux-hardware.org/?probe=c43cfd04ad) | May 24, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [0d3bc48240](https://linux-hardware.org/?probe=0d3bc48240) | May 23, 2023 |
| ASRock        | B650E Steel Legend WiFi     | [b034244bec](https://linux-hardware.org/?probe=b034244bec) | May 20, 2023 |
| langchao      | IPM41-D3                    | [2f659faa92](https://linux-hardware.org/?probe=2f659faa92) | May 20, 2023 |
| MSI           | PRO Z690-A DDR4             | [758f0dbd4b](https://linux-hardware.org/?probe=758f0dbd4b) | May 19, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [ca0ae58640](https://linux-hardware.org/?probe=ca0ae58640) | May 18, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [fee6b2f55b](https://linux-hardware.org/?probe=fee6b2f55b) | May 17, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | [dc2f3b9cdc](https://linux-hardware.org/?probe=dc2f3b9cdc) | May 17, 2023 |
| ASRock        | Z97 Pro3                    | [f8be8d5d2c](https://linux-hardware.org/?probe=f8be8d5d2c) | May 16, 2023 |
| ASRock        | Z97 Pro3                    | [34b2fb40b9](https://linux-hardware.org/?probe=34b2fb40b9) | May 13, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [bd6f8927b4](https://linux-hardware.org/?probe=bd6f8927b4) | May 12, 2023 |
| ASUSTek       | B85-PLUS                    | [9346ce422f](https://linux-hardware.org/?probe=9346ce422f) | May 11, 2023 |
| MSI           | PRO Z690-A DDR4             | [45c02c8b1b](https://linux-hardware.org/?probe=45c02c8b1b) | May 11, 2023 |
| ASUSTek       | P8B75-M LE                  | [2b0bc04757](https://linux-hardware.org/?probe=2b0bc04757) | May 10, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [ebe0f52831](https://linux-hardware.org/?probe=ebe0f52831) | May 10, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [aa31c3dd8f](https://linux-hardware.org/?probe=aa31c3dd8f) | May 09, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | [c39e7fa08d](https://linux-hardware.org/?probe=c39e7fa08d) | May 09, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [dc1db599ea](https://linux-hardware.org/?probe=dc1db599ea) | May 09, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [e2ce1c3d6c](https://linux-hardware.org/?probe=e2ce1c3d6c) | May 07, 2023 |
| Gigabyte      | P43-ES3G                    | [1095d1ef7f](https://linux-hardware.org/?probe=1095d1ef7f) | May 06, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [de65a79bf1](https://linux-hardware.org/?probe=de65a79bf1) | May 06, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [4b76463d57](https://linux-hardware.org/?probe=4b76463d57) | May 06, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [b0a2a0b536](https://linux-hardware.org/?probe=b0a2a0b536) | May 06, 2023 |
| ASUSTek       | B85-PLUS                    | [352e8b2616](https://linux-hardware.org/?probe=352e8b2616) | May 03, 2023 |
| MSI           | B450 GAMING PLUS            | [017222d810](https://linux-hardware.org/?probe=017222d810) | May 02, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [62d194e85e](https://linux-hardware.org/?probe=62d194e85e) | May 01, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [e2acacabb3](https://linux-hardware.org/?probe=e2acacabb3) | Apr 30, 2023 |
| MSI           | B450 GAMING PLUS            | [8aa973e0f5](https://linux-hardware.org/?probe=8aa973e0f5) | Apr 30, 2023 |
| MSI           | PRO Z690-A DDR4             | [9419686ec7](https://linux-hardware.org/?probe=9419686ec7) | Apr 30, 2023 |
| MSI           | PRO Z690-A DDR4             | [1f61fda034](https://linux-hardware.org/?probe=1f61fda034) | Apr 30, 2023 |
| ASUSTek       | TUF Gaming B460-PLUS        | [b2616ea409](https://linux-hardware.org/?probe=b2616ea409) | Apr 28, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [169e095fab](https://linux-hardware.org/?probe=169e095fab) | Apr 27, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [c80b811f3e](https://linux-hardware.org/?probe=c80b811f3e) | Apr 27, 2023 |
| ASRock        | B550M Phantom Gaming 4      | [072b88204c](https://linux-hardware.org/?probe=072b88204c) | Apr 26, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [f02e8339e9](https://linux-hardware.org/?probe=f02e8339e9) | Apr 25, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [8de5e39740](https://linux-hardware.org/?probe=8de5e39740) | Apr 25, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [e4064abe78](https://linux-hardware.org/?probe=e4064abe78) | Apr 24, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [8db6f88fd3](https://linux-hardware.org/?probe=8db6f88fd3) | Apr 22, 2023 |
| ASUSTek       | TUF Gaming A520M-PLUS       | [28631c09aa](https://linux-hardware.org/?probe=28631c09aa) | Apr 22, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [47831c9091](https://linux-hardware.org/?probe=47831c9091) | Apr 18, 2023 |
| Gigabyte      | B150M-D3H-CF                | [c248c05349](https://linux-hardware.org/?probe=c248c05349) | Apr 18, 2023 |
| MSI           | Z87M GAMING                 | [9552ef2174](https://linux-hardware.org/?probe=9552ef2174) | Apr 17, 2023 |
| HP            | 18E7                        | [ef0b00cf80](https://linux-hardware.org/?probe=ef0b00cf80) | Apr 17, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [d40208e7f6](https://linux-hardware.org/?probe=d40208e7f6) | Apr 17, 2023 |
| Protectli     | FW6 Ver                     | [7371569bbf](https://linux-hardware.org/?probe=7371569bbf) | Apr 15, 2023 |
| Dell          | 0KWVT8 A00                  | [d1084f0d90](https://linux-hardware.org/?probe=d1084f0d90) | Apr 15, 2023 |
| ASUSTek       | A68HM-K                     | [6419c7fb77](https://linux-hardware.org/?probe=6419c7fb77) | Apr 15, 2023 |
| Protectli     | FW6 Ver                     | [26db4eab1f](https://linux-hardware.org/?probe=26db4eab1f) | Apr 15, 2023 |
| MSI           | B450 GAMING PLUS            | [d49b1775be](https://linux-hardware.org/?probe=d49b1775be) | Apr 14, 2023 |
| Dell          | 0XR1GT A00                  | [1c8d776510](https://linux-hardware.org/?probe=1c8d776510) | Apr 13, 2023 |
| Dell          | 0XR1GT A00                  | [06e6f2f745](https://linux-hardware.org/?probe=06e6f2f745) | Apr 13, 2023 |
| Dell          | 0KWVT8 A00                  | [4cea64e81b](https://linux-hardware.org/?probe=4cea64e81b) | Apr 13, 2023 |
| ASUSTek       | PRIME B450M-A II            | [3e3a141713](https://linux-hardware.org/?probe=3e3a141713) | Apr 11, 2023 |
| HP            | 805F                        | [07bd1b4df7](https://linux-hardware.org/?probe=07bd1b4df7) | Apr 11, 2023 |
| HP            | 805F                        | [7863ff02eb](https://linux-hardware.org/?probe=7863ff02eb) | Apr 11, 2023 |
| MSI           | B450 GAMING PLUS            | [b35b8e1503](https://linux-hardware.org/?probe=b35b8e1503) | Apr 09, 2023 |
| Gigabyte      | G1.Sniper B5-CF             | [e0913458ee](https://linux-hardware.org/?probe=e0913458ee) | Apr 07, 2023 |
| Gigabyte      | B650 AORUS PRO AX           | [5a044a37f7](https://linux-hardware.org/?probe=5a044a37f7) | Apr 07, 2023 |
| Gigabyte      | B650 AORUS PRO AX           | [81a8d7a1fc](https://linux-hardware.org/?probe=81a8d7a1fc) | Apr 07, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [c599e701fc](https://linux-hardware.org/?probe=c599e701fc) | Apr 06, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [7aec6da94d](https://linux-hardware.org/?probe=7aec6da94d) | Apr 05, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [aa3b0a7d6f](https://linux-hardware.org/?probe=aa3b0a7d6f) | Apr 04, 2023 |
| MSI           | B450 GAMING PLUS            | [731bd99503](https://linux-hardware.org/?probe=731bd99503) | Apr 03, 2023 |
| Gigabyte      | Z77P-D3                     | [e97e71fc7a](https://linux-hardware.org/?probe=e97e71fc7a) | Apr 02, 2023 |
| Gigabyte      | Z77P-D3                     | [f96e01d74d](https://linux-hardware.org/?probe=f96e01d74d) | Apr 01, 2023 |
| MSI           | B450 GAMING PLUS            | [539137fb36](https://linux-hardware.org/?probe=539137fb36) | Apr 01, 2023 |
| ASUSTek       | B85M-G R2.0                 | [4434a1266b](https://linux-hardware.org/?probe=4434a1266b) | Mar 31, 2023 |
| ASUSTek       | B85M-G R2.0                 | [fbef2fe274](https://linux-hardware.org/?probe=fbef2fe274) | Mar 31, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [d79127e48c](https://linux-hardware.org/?probe=d79127e48c) | Mar 31, 2023 |
| Intel         | X79                         | [c06125262b](https://linux-hardware.org/?probe=c06125262b) | Mar 31, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | [f0540604bc](https://linux-hardware.org/?probe=f0540604bc) | Mar 30, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | [1c575e8cb6](https://linux-hardware.org/?probe=1c575e8cb6) | Mar 30, 2023 |
| ASRock        | X470 Master SLI             | [e4d56ca8c8](https://linux-hardware.org/?probe=e4d56ca8c8) | Mar 28, 2023 |
| ASUSTek       | M3N78 PRO                   | [0f9abe9400](https://linux-hardware.org/?probe=0f9abe9400) | Mar 28, 2023 |
| MSI           | B450 GAMING PLUS            | [5242d56a0f](https://linux-hardware.org/?probe=5242d56a0f) | Mar 27, 2023 |
| MSI           | B550-A PRO                  | [ebb59fa31d](https://linux-hardware.org/?probe=ebb59fa31d) | Mar 27, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [b084807397](https://linux-hardware.org/?probe=b084807397) | Mar 26, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [bc38c5ed22](https://linux-hardware.org/?probe=bc38c5ed22) | Mar 26, 2023 |
| ASUSTek       | PRIME B450M-A               | [6601de8aae](https://linux-hardware.org/?probe=6601de8aae) | Mar 25, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [9240540b33](https://linux-hardware.org/?probe=9240540b33) | Mar 24, 2023 |
| Gigabyte      | GA-970A-DS3                 | [82a69c4ec6](https://linux-hardware.org/?probe=82a69c4ec6) | Mar 23, 2023 |
| ASRock        | B660M-ITX/ac                | [95687a223c](https://linux-hardware.org/?probe=95687a223c) | Mar 22, 2023 |
| Dell          | 0XR1GT A00                  | [0912041935](https://linux-hardware.org/?probe=0912041935) | Mar 21, 2023 |
| Dell          | 0XR1GT A00                  | [61e1c5eff9](https://linux-hardware.org/?probe=61e1c5eff9) | Mar 21, 2023 |
| ASRock        | X670E Steel Legend          | [7891e82ac4](https://linux-hardware.org/?probe=7891e82ac4) | Mar 17, 2023 |
| ASUSTek       | PRIME X370-PRO              | [ab4a88037a](https://linux-hardware.org/?probe=ab4a88037a) | Mar 16, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [37bf97e9b3](https://linux-hardware.org/?probe=37bf97e9b3) | Mar 16, 2023 |
| ASUSTek       | PRIME X370-PRO              | [23e21d1440](https://linux-hardware.org/?probe=23e21d1440) | Mar 15, 2023 |
| Gigabyte      | Z77P-D3                     | [34ad3eb730](https://linux-hardware.org/?probe=34ad3eb730) | Mar 15, 2023 |
| Gigabyte      | Z77P-D3                     | [06c53ecdec](https://linux-hardware.org/?probe=06c53ecdec) | Mar 15, 2023 |
| Intel         | DB85FL AAG89861-203         | [e17dae3447](https://linux-hardware.org/?probe=e17dae3447) | Mar 14, 2023 |
| Intel         | DB85FL AAG89861-203         | [f1004a32e1](https://linux-hardware.org/?probe=f1004a32e1) | Mar 14, 2023 |
| MSI           | X470 GAMING PLUS            | [727390b14d](https://linux-hardware.org/?probe=727390b14d) | Mar 14, 2023 |
| ASRock        | X670E Steel Legend          | [0eefdece9c](https://linux-hardware.org/?probe=0eefdece9c) | Mar 13, 2023 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | [7320131972](https://linux-hardware.org/?probe=7320131972) | Mar 13, 2023 |
| ASUSTek       | PRIME Z690M-PLUS D4         | [e41f3ed4ab](https://linux-hardware.org/?probe=e41f3ed4ab) | Mar 13, 2023 |
| ASUSTek       | PRIME B450M-A               | [1ad75bea9c](https://linux-hardware.org/?probe=1ad75bea9c) | Mar 12, 2023 |
| ASRock        | X670E Steel Legend          | [3ec784f6be](https://linux-hardware.org/?probe=3ec784f6be) | Mar 11, 2023 |
| ASUSTek       | PRIME B450M-A               | [7ba7da9138](https://linux-hardware.org/?probe=7ba7da9138) | Mar 10, 2023 |
| MSI           | B450 GAMING PLUS            | [46b213149e](https://linux-hardware.org/?probe=46b213149e) | Mar 10, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [3629efc5a5](https://linux-hardware.org/?probe=3629efc5a5) | Mar 08, 2023 |
| Dell          | 0773VG A01                  | [d954bdd915](https://linux-hardware.org/?probe=d954bdd915) | Mar 07, 2023 |
| ASRock        | H310M-HDV                   | [316510fe69](https://linux-hardware.org/?probe=316510fe69) | Mar 07, 2023 |
| Acer          | Aspire X1400                | [195337bbc6](https://linux-hardware.org/?probe=195337bbc6) | Mar 07, 2023 |
| ASUSTek       | PRIME B560M-A AC            | [21db48a23b](https://linux-hardware.org/?probe=21db48a23b) | Mar 06, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [4eb7bea837](https://linux-hardware.org/?probe=4eb7bea837) | Mar 04, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [1d24df340b](https://linux-hardware.org/?probe=1d24df340b) | Mar 04, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [950e36afc7](https://linux-hardware.org/?probe=950e36afc7) | Mar 03, 2023 |
| MSI           | MPG Z390M GAMING EDGE AC    | [d0813971b9](https://linux-hardware.org/?probe=d0813971b9) | Feb 28, 2023 |
| ASRock        | B660M-ITX/ac                | [c2e600e445](https://linux-hardware.org/?probe=c2e600e445) | Feb 28, 2023 |
| ASRock        | B660M-ITX/ac                | [1efc15e2cc](https://linux-hardware.org/?probe=1efc15e2cc) | Feb 28, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [15318beac5](https://linux-hardware.org/?probe=15318beac5) | Feb 27, 2023 |
| MSI           | Z170A-G45 GAMING            | [a5496030e7](https://linux-hardware.org/?probe=a5496030e7) | Feb 27, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E EXTR... | [659ff1672e](https://linux-hardware.org/?probe=659ff1672e) | Feb 26, 2023 |
| ASUSTek       | P8Z77-M PRO                 | [92f1f7d3b5](https://linux-hardware.org/?probe=92f1f7d3b5) | Feb 26, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [101d8d4577](https://linux-hardware.org/?probe=101d8d4577) | Feb 25, 2023 |
| ASUSTek       | H97M-E                      | [b2ef9d5ede](https://linux-hardware.org/?probe=b2ef9d5ede) | Feb 21, 2023 |
| MSI           | B450 GAMING PRO CARBON M... | [fb4420dbc4](https://linux-hardware.org/?probe=fb4420dbc4) | Feb 20, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [737c043ed7](https://linux-hardware.org/?probe=737c043ed7) | Feb 20, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [2752a9660a](https://linux-hardware.org/?probe=2752a9660a) | Feb 19, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | [a62c4f0fcd](https://linux-hardware.org/?probe=a62c4f0fcd) | Feb 18, 2023 |
| MSI           | B550-A PRO                  | [e81d0741bb](https://linux-hardware.org/?probe=e81d0741bb) | Feb 17, 2023 |
| MSI           | B550-A PRO                  | [dd63e968bd](https://linux-hardware.org/?probe=dd63e968bd) | Feb 17, 2023 |
| ASUSTek       | PRIME B450M-A II            | [e486b2bb46](https://linux-hardware.org/?probe=e486b2bb46) | Feb 15, 2023 |
| Dell          | 0KWVT8 A02                  | [486f7258a6](https://linux-hardware.org/?probe=486f7258a6) | Feb 14, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [dc91c0e32b](https://linux-hardware.org/?probe=dc91c0e32b) | Feb 14, 2023 |
| Dell          | 0KWVT8 A02                  | [c3d08b4f2e](https://linux-hardware.org/?probe=c3d08b4f2e) | Feb 13, 2023 |
| ASRock        | B650M PG Riptide            | [bf986cc448](https://linux-hardware.org/?probe=bf986cc448) | Feb 12, 2023 |
| ASUSTek       | PRIME X570-P                | [74d6af0f75](https://linux-hardware.org/?probe=74d6af0f75) | Feb 11, 2023 |
| MSI           | PRO Z690-A DDR4             | [caca2e6be1](https://linux-hardware.org/?probe=caca2e6be1) | Feb 11, 2023 |
| ASUSTek       | TUF Gaming B460-PLUS        | [afefa761d5](https://linux-hardware.org/?probe=afefa761d5) | Feb 09, 2023 |
| MSI           | B450M BAZOOKA MAX WIFI      | [fdaab67fe9](https://linux-hardware.org/?probe=fdaab67fe9) | Feb 09, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [eece150870](https://linux-hardware.org/?probe=eece150870) | Feb 05, 2023 |
| ASUSTek       | TUF Gaming B460-PLUS        | [20086250d5](https://linux-hardware.org/?probe=20086250d5) | Feb 05, 2023 |
| ASUSTek       | TUF Gaming B460-PLUS        | [9905642762](https://linux-hardware.org/?probe=9905642762) | Feb 05, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [cbac9c37ba](https://linux-hardware.org/?probe=cbac9c37ba) | Feb 04, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [8ae0d42e1a](https://linux-hardware.org/?probe=8ae0d42e1a) | Feb 03, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [513dd8e40b](https://linux-hardware.org/?probe=513dd8e40b) | Feb 03, 2023 |
| MSI           | PRO Z690-A DDR4             | [5a7a0cf485](https://linux-hardware.org/?probe=5a7a0cf485) | Feb 03, 2023 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | [7645e16594](https://linux-hardware.org/?probe=7645e16594) | Feb 03, 2023 |
| HP            | 834F                        | [394eb5f9cc](https://linux-hardware.org/?probe=394eb5f9cc) | Feb 02, 2023 |
| HP            | 8054                        | [36f5306e37](https://linux-hardware.org/?probe=36f5306e37) | Jan 30, 2023 |
| Gigabyte      | F2A88XM-D3H                 | [1605fbe62a](https://linux-hardware.org/?probe=1605fbe62a) | Jan 28, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | [95f5d0904e](https://linux-hardware.org/?probe=95f5d0904e) | Jan 26, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [c69db4d96f](https://linux-hardware.org/?probe=c69db4d96f) | Jan 24, 2023 |
| MSI           | B450 GAMING PLUS            | [bc95b86800](https://linux-hardware.org/?probe=bc95b86800) | Jan 22, 2023 |
| Gigabyte      | Z77-D3H                     | [9035a00600](https://linux-hardware.org/?probe=9035a00600) | Jan 22, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [3eb7e4f3cf](https://linux-hardware.org/?probe=3eb7e4f3cf) | Jan 22, 2023 |
| MSI           | MPG Z390M GAMING EDGE AC    | [085d30a350](https://linux-hardware.org/?probe=085d30a350) | Jan 21, 2023 |
| MSI           | Z490-A PRO                  | [0a3fe4cb00](https://linux-hardware.org/?probe=0a3fe4cb00) | Jan 21, 2023 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | [9a70fa222c](https://linux-hardware.org/?probe=9a70fa222c) | Jan 19, 2023 |
| Gigabyte      | B450 AORUS M                | [4d52b408c2](https://linux-hardware.org/?probe=4d52b408c2) | Jan 19, 2023 |
| MSI           | GF615M-P33                  | [bf838ee958](https://linux-hardware.org/?probe=bf838ee958) | Jan 18, 2023 |
| ASUSTek       | PRIME Z370-A                | [f215410f54](https://linux-hardware.org/?probe=f215410f54) | Jan 17, 2023 |
| ASUSTek       | Z97-A                       | [c1b01960be](https://linux-hardware.org/?probe=c1b01960be) | Jan 17, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [aade436557](https://linux-hardware.org/?probe=aade436557) | Jan 14, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [5b50555e06](https://linux-hardware.org/?probe=5b50555e06) | Jan 13, 2023 |
| ASUSTek       | P9X79 DELUXE                | [d73373e8e9](https://linux-hardware.org/?probe=d73373e8e9) | Jan 13, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [73da880450](https://linux-hardware.org/?probe=73da880450) | Jan 12, 2023 |
| HP            | 8054                        | [d4398dee29](https://linux-hardware.org/?probe=d4398dee29) | Jan 08, 2023 |
| MSI           | MAG B560M MORTAR WIFI       | [33f6781ba8](https://linux-hardware.org/?probe=33f6781ba8) | Jan 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [c74a6daaaa](https://linux-hardware.org/?probe=c74a6daaaa) | Jan 07, 2023 |
| ASRock        | X470 Master SLI             | [c138f9159c](https://linux-hardware.org/?probe=c138f9159c) | Jan 07, 2023 |
| HP            | 1497                        | [71550a0f21](https://linux-hardware.org/?probe=71550a0f21) | Jan 07, 2023 |
| ASRock        | H77M-ITX                    | [fb6cbfce9a](https://linux-hardware.org/?probe=fb6cbfce9a) | Jan 06, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [406b407b64](https://linux-hardware.org/?probe=406b407b64) | Jan 06, 2023 |
| ASUSTek       | PRIME B450M-A               | [61b7c0cda0](https://linux-hardware.org/?probe=61b7c0cda0) | Jan 06, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [569f5cd751](https://linux-hardware.org/?probe=569f5cd751) | Jan 06, 2023 |
| Gigabyte      | B550M DS3H                  | [3978c4253f](https://linux-hardware.org/?probe=3978c4253f) | Jan 06, 2023 |
| ASUSTek       | G20AJ                       | [9be7e0b11f](https://linux-hardware.org/?probe=9be7e0b11f) | Jan 05, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [b6bf9d074f](https://linux-hardware.org/?probe=b6bf9d074f) | Jan 05, 2023 |
| ASUSTek       | PRIME B550M-K               | [11d17c68b8](https://linux-hardware.org/?probe=11d17c68b8) | Jan 05, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [7655f77ada](https://linux-hardware.org/?probe=7655f77ada) | Jan 04, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [6c40dc7dd6](https://linux-hardware.org/?probe=6c40dc7dd6) | Jan 03, 2023 |
| ASUSTek       | M5A88-M                     | [dc7201711c](https://linux-hardware.org/?probe=dc7201711c) | Dec 30, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [4ca2070d42](https://linux-hardware.org/?probe=4ca2070d42) | Dec 29, 2022 |
| ASUSTek       | PRIME Z270-P                | [b9e4ff3fea](https://linux-hardware.org/?probe=b9e4ff3fea) | Dec 25, 2022 |
| HP            | 1589                        | [4769414712](https://linux-hardware.org/?probe=4769414712) | Dec 24, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [353cbeb5c8](https://linux-hardware.org/?probe=353cbeb5c8) | Dec 19, 2022 |
| Biostar       | X470GTN                     | [7c067277b2](https://linux-hardware.org/?probe=7c067277b2) | Dec 17, 2022 |
| ASUSTek       | M5A88-M                     | [3bc811ef2a](https://linux-hardware.org/?probe=3bc811ef2a) | Dec 17, 2022 |
| HP            | 2ABD A01                    | [c5c5c07485](https://linux-hardware.org/?probe=c5c5c07485) | Dec 16, 2022 |
| HP            | 2ABD A01                    | [c992b15fbe](https://linux-hardware.org/?probe=c992b15fbe) | Dec 16, 2022 |
| ASUSTek       | M5A97 LE R2.0               | [fc8f4624a4](https://linux-hardware.org/?probe=fc8f4624a4) | Dec 16, 2022 |
| ASRock        | H310M-HDV/M.2               | [76dff63f5c](https://linux-hardware.org/?probe=76dff63f5c) | Dec 15, 2022 |
| ASUSTek       | M5A88-M                     | [4378eff64f](https://linux-hardware.org/?probe=4378eff64f) | Dec 13, 2022 |
| MSI           | MAG B660 TOMAHAWK WIFI      | [1beb5ff3c4](https://linux-hardware.org/?probe=1beb5ff3c4) | Dec 13, 2022 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [3f57fa2c71](https://linux-hardware.org/?probe=3f57fa2c71) | Dec 12, 2022 |
| Gigabyte      | H81M-H                      | [02ba14a443](https://linux-hardware.org/?probe=02ba14a443) | Dec 09, 2022 |
| Dell          | 0215PR A02                  | [b9d16b98d2](https://linux-hardware.org/?probe=b9d16b98d2) | Dec 09, 2022 |
| Gigabyte      | Z590I VISION D              | [9cc2be8747](https://linux-hardware.org/?probe=9cc2be8747) | Dec 09, 2022 |
| MSI           | GF615M-P33                  | [af4d483414](https://linux-hardware.org/?probe=af4d483414) | Dec 08, 2022 |
| ASUSTek       | M5A88-M                     | [d7b2726838](https://linux-hardware.org/?probe=d7b2726838) | Dec 08, 2022 |
| ASUSTek       | STRIX Z270H GAMING          | [c9cc6de1c4](https://linux-hardware.org/?probe=c9cc6de1c4) | Dec 08, 2022 |
| ASUSTek       | STRIX Z270H GAMING          | [8973296b3b](https://linux-hardware.org/?probe=8973296b3b) | Dec 08, 2022 |
| ASUSTek       | M5A88-M                     | [f5bd8a0e5b](https://linux-hardware.org/?probe=f5bd8a0e5b) | Dec 07, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [a742429421](https://linux-hardware.org/?probe=a742429421) | Dec 06, 2022 |
| ASUSTek       | M5A88-M                     | [69ed3a0345](https://linux-hardware.org/?probe=69ed3a0345) | Dec 02, 2022 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | [1775ec9d4b](https://linux-hardware.org/?probe=1775ec9d4b) | Dec 01, 2022 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | [097d1c062e](https://linux-hardware.org/?probe=097d1c062e) | Dec 01, 2022 |
| Gigabyte      | Z590I VISION D              | [655e907d62](https://linux-hardware.org/?probe=655e907d62) | Dec 01, 2022 |
| Intel         | X79G V2.x                   | [6b229554fc](https://linux-hardware.org/?probe=6b229554fc) | Nov 28, 2022 |
| Gigabyte      | H410M H V3                  | [afea73cc2a](https://linux-hardware.org/?probe=afea73cc2a) | Nov 22, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [56c9fb93ce](https://linux-hardware.org/?probe=56c9fb93ce) | Nov 22, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [1ec2520541](https://linux-hardware.org/?probe=1ec2520541) | Nov 22, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [0fd2d81cad](https://linux-hardware.org/?probe=0fd2d81cad) | Nov 22, 2022 |
| OEM           | SHARKBAY JHS695             | [03c915bbd9](https://linux-hardware.org/?probe=03c915bbd9) | Nov 22, 2022 |
| MSI           | GF615M-P33                  | [7a6be335c4](https://linux-hardware.org/?probe=7a6be335c4) | Nov 22, 2022 |
| ASRock        | B550 Extreme4               | [7fba8e38dc](https://linux-hardware.org/?probe=7fba8e38dc) | Nov 20, 2022 |
| Gigabyte      | H310M M.2 x.x               | [87406f0722](https://linux-hardware.org/?probe=87406f0722) | Nov 19, 2022 |
| Alienware     | 0PGRP5 A01                  | [2ff9360669](https://linux-hardware.org/?probe=2ff9360669) | Nov 17, 2022 |
| MSI           | MEG X570 UNIFY              | [750d7eb0d7](https://linux-hardware.org/?probe=750d7eb0d7) | Nov 16, 2022 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | [4d4d5aa456](https://linux-hardware.org/?probe=4d4d5aa456) | Nov 15, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [d4240ae5c7](https://linux-hardware.org/?probe=d4240ae5c7) | Nov 12, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | [51d6598b74](https://linux-hardware.org/?probe=51d6598b74) | Nov 11, 2022 |
| ASUSTek       | A68HM-K                     | [70daf967f2](https://linux-hardware.org/?probe=70daf967f2) | Nov 10, 2022 |
| Gigabyte      | 990FXA-UD3                  | [a49a1465d3](https://linux-hardware.org/?probe=a49a1465d3) | Nov 10, 2022 |
| ASRock        | N68C-GS4 FX                 | [5e151ea22f](https://linux-hardware.org/?probe=5e151ea22f) | Nov 07, 2022 |
| Intel         | D33217GKE G76540-207        | [f90e6e931c](https://linux-hardware.org/?probe=f90e6e931c) | Nov 07, 2022 |
| Intel         | D33217GKE G76540-207        | [a154fd19a0](https://linux-hardware.org/?probe=a154fd19a0) | Nov 07, 2022 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [4239b9f4a9](https://linux-hardware.org/?probe=4239b9f4a9) | Nov 06, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | [05529fe361](https://linux-hardware.org/?probe=05529fe361) | Nov 06, 2022 |
| Dell          | 042P49 A02                  | [55d7ddf0c8](https://linux-hardware.org/?probe=55d7ddf0c8) | Nov 06, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | [677dcff84a](https://linux-hardware.org/?probe=677dcff84a) | Nov 06, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | [049bac8501](https://linux-hardware.org/?probe=049bac8501) | Nov 06, 2022 |
| ASUSTek       | M5A97 R2.0                  | [5ca257fd77](https://linux-hardware.org/?probe=5ca257fd77) | Nov 06, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [bd9e0be4e8](https://linux-hardware.org/?probe=bd9e0be4e8) | Nov 03, 2022 |
| ECS           | H61H2-CM                    | [792ce0e34e](https://linux-hardware.org/?probe=792ce0e34e) | Oct 31, 2022 |
| ASRock        | Z77 Pro4                    | [5ab5790e5f](https://linux-hardware.org/?probe=5ab5790e5f) | Oct 29, 2022 |
| ASRock        | Z77 Pro4                    | [74cc7f147b](https://linux-hardware.org/?probe=74cc7f147b) | Oct 29, 2022 |
| HP            | 8653 A                      | [bc1f3b445b](https://linux-hardware.org/?probe=bc1f3b445b) | Oct 28, 2022 |
| ASRock        | X570 Taichi                 | [967f52e510](https://linux-hardware.org/?probe=967f52e510) | Oct 28, 2022 |
| Dell          | 09KPNV A00                  | [c25493f420](https://linux-hardware.org/?probe=c25493f420) | Oct 27, 2022 |
| Gigabyte      | 970A-DS3P                   | [7e31b6af67](https://linux-hardware.org/?probe=7e31b6af67) | Oct 27, 2022 |
| Gigabyte      | 970A-DS3P                   | [6823943242](https://linux-hardware.org/?probe=6823943242) | Oct 27, 2022 |
| Intel         | B75                         | [eb7c27f1e5](https://linux-hardware.org/?probe=eb7c27f1e5) | Oct 26, 2022 |
| HP            | 3029h                       | [c278953154](https://linux-hardware.org/?probe=c278953154) | Oct 25, 2022 |
| Gigabyte      | Z590I VISION D              | [be4c6573cd](https://linux-hardware.org/?probe=be4c6573cd) | Oct 25, 2022 |
| ASUSTek       | PRIME A320M-K               | [c0b3f0d88e](https://linux-hardware.org/?probe=c0b3f0d88e) | Oct 24, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [7e40be1c82](https://linux-hardware.org/?probe=7e40be1c82) | Oct 23, 2022 |
| Gigabyte      | Z97-HD3                     | [f79eb0cbb0](https://linux-hardware.org/?probe=f79eb0cbb0) | Oct 23, 2022 |
| ASUSTek       | TUF Gaming X570-PRO WIFI... | [c3b1784ecc](https://linux-hardware.org/?probe=c3b1784ecc) | Oct 21, 2022 |
| Gigabyte      | B450M DS3H-CF               | [c901f6927c](https://linux-hardware.org/?probe=c901f6927c) | Oct 18, 2022 |
| MSI           | MPG Z390 GAMING PLUS        | [624be3f0f3](https://linux-hardware.org/?probe=624be3f0f3) | Oct 17, 2022 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [cb63aa5619](https://linux-hardware.org/?probe=cb63aa5619) | Oct 17, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | [a4919afa07](https://linux-hardware.org/?probe=a4919afa07) | Oct 16, 2022 |
| MSI           | Z87 XPOWER                  | [5e73f5004a](https://linux-hardware.org/?probe=5e73f5004a) | Oct 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | [0a89e9b77e](https://linux-hardware.org/?probe=0a89e9b77e) | Oct 13, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | [a920c57a3e](https://linux-hardware.org/?probe=a920c57a3e) | Oct 11, 2022 |
| Dell          | 0F6X5P A00                  | [49baafbc65](https://linux-hardware.org/?probe=49baafbc65) | Oct 10, 2022 |
| MSI           | PRO Z690-A DDR4             | [2a1088b211](https://linux-hardware.org/?probe=2a1088b211) | Oct 08, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [05dfea29df](https://linux-hardware.org/?probe=05dfea29df) | Oct 07, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [24471f06da](https://linux-hardware.org/?probe=24471f06da) | Oct 07, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [cc955e89b7](https://linux-hardware.org/?probe=cc955e89b7) | Oct 07, 2022 |
| HP            | 1998                        | [f2b9957fdd](https://linux-hardware.org/?probe=f2b9957fdd) | Oct 06, 2022 |
| MSI           | B450-A PRO MAX              | [b161553abb](https://linux-hardware.org/?probe=b161553abb) | Oct 05, 2022 |
| ASRock        | B450M Steel Legend          | [4f4352de45](https://linux-hardware.org/?probe=4f4352de45) | Oct 04, 2022 |
| ASUSTek       | H61M-K                      | [e0408b49e7](https://linux-hardware.org/?probe=e0408b49e7) | Oct 02, 2022 |
| MSI           | B350 PC MATE                | [a4c73b484e](https://linux-hardware.org/?probe=a4c73b484e) | Oct 02, 2022 |
| Dell          | 0M5DCD A00                  | [3cc1e139dc](https://linux-hardware.org/?probe=3cc1e139dc) | Oct 02, 2022 |
| MSI           | MEG X570 UNIFY              | [4d2e449699](https://linux-hardware.org/?probe=4d2e449699) | Sep 30, 2022 |
| ASRock        | X470 Master SLI             | [47c190b6e9](https://linux-hardware.org/?probe=47c190b6e9) | Sep 30, 2022 |
| Gigabyte      | H270-Gaming 3               | [9426d21070](https://linux-hardware.org/?probe=9426d21070) | Sep 29, 2022 |
| Gigabyte      | H270-Gaming 3               | [830af9c53e](https://linux-hardware.org/?probe=830af9c53e) | Sep 29, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [365d74f8e4](https://linux-hardware.org/?probe=365d74f8e4) | Sep 28, 2022 |
| Intel         | B75                         | [af5aef869c](https://linux-hardware.org/?probe=af5aef869c) | Sep 28, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [cfd24b9e0a](https://linux-hardware.org/?probe=cfd24b9e0a) | Sep 27, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [6bfc8d43ef](https://linux-hardware.org/?probe=6bfc8d43ef) | Sep 27, 2022 |
| MSI           | A68HM-E33 V2                | [d51c90a7a8](https://linux-hardware.org/?probe=d51c90a7a8) | Sep 27, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | [f61a736922](https://linux-hardware.org/?probe=f61a736922) | Sep 26, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | [1ecfe379e7](https://linux-hardware.org/?probe=1ecfe379e7) | Sep 26, 2022 |
| ASUSTek       | PRIME H410M-A               | [dafae8d45b](https://linux-hardware.org/?probe=dafae8d45b) | Sep 26, 2022 |
| MSI           | 970 GAMING                  | [015cd37f26](https://linux-hardware.org/?probe=015cd37f26) | Sep 24, 2022 |
| Dell          | 0G785M A00                  | [c461ec42d6](https://linux-hardware.org/?probe=c461ec42d6) | Sep 24, 2022 |
| ASUSTek       | PRIME A320M-K               | [d72e6b3865](https://linux-hardware.org/?probe=d72e6b3865) | Sep 23, 2022 |
| Gigabyte      | EP45-UD3L                   | [71c630ea03](https://linux-hardware.org/?probe=71c630ea03) | Sep 22, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [7299d75966](https://linux-hardware.org/?probe=7299d75966) | Sep 22, 2022 |
| HP            | 8594                        | [281774ad4a](https://linux-hardware.org/?probe=281774ad4a) | Sep 21, 2022 |
| Gigabyte      | EP45-UD3L                   | [2b90168b71](https://linux-hardware.org/?probe=2b90168b71) | Sep 21, 2022 |
| ASRock        | X470 Master SLI             | [3c8fefe578](https://linux-hardware.org/?probe=3c8fefe578) | Sep 20, 2022 |
| ASRock        | X470 Master SLI             | [1975320cad](https://linux-hardware.org/?probe=1975320cad) | Sep 20, 2022 |
| Dell          | 0G785M A00                  | [8b8c41b401](https://linux-hardware.org/?probe=8b8c41b401) | Sep 19, 2022 |
| Unknown       | T3 MRD                      | [1f60a4d202](https://linux-hardware.org/?probe=1f60a4d202) | Sep 19, 2022 |
| MSI           | X570-A PRO                  | [cabf88c8be](https://linux-hardware.org/?probe=cabf88c8be) | Sep 19, 2022 |
| Gigabyte      | A320M-S2H-CF                | [7b95813c96](https://linux-hardware.org/?probe=7b95813c96) | Sep 18, 2022 |
| Unknown       | T3 MRD                      | [b10823b50f](https://linux-hardware.org/?probe=b10823b50f) | Sep 17, 2022 |
| Biostar       | H410MH S2                   | [832dd81851](https://linux-hardware.org/?probe=832dd81851) | Sep 17, 2022 |
| Lenovo        | MAHOBAY NOK                 | [cce010fd53](https://linux-hardware.org/?probe=cce010fd53) | Sep 16, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [d9e9ec9afa](https://linux-hardware.org/?probe=d9e9ec9afa) | Sep 09, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [1cdd7cda15](https://linux-hardware.org/?probe=1cdd7cda15) | Sep 09, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [6eae76b5d0](https://linux-hardware.org/?probe=6eae76b5d0) | Sep 01, 2022 |
| ASRock        | FM2A55M-HD+                 | [2f96c73efb](https://linux-hardware.org/?probe=2f96c73efb) | Sep 01, 2022 |
| Gigabyte      | H110M-H-CF                  | [86fc2bf58f](https://linux-hardware.org/?probe=86fc2bf58f) | Aug 31, 2022 |
| Alienware     | 01NYPT A00                  | [cd95b79270](https://linux-hardware.org/?probe=cd95b79270) | Aug 29, 2022 |
| ASRock        | B560 Steel Legend           | [c64907de8d](https://linux-hardware.org/?probe=c64907de8d) | Aug 27, 2022 |
| ASUSTek       | P8Z68-V PRO                 | [37ae937f4d](https://linux-hardware.org/?probe=37ae937f4d) | Aug 26, 2022 |
| ASUSTek       | PRIME X570-PRO              | [663509c999](https://linux-hardware.org/?probe=663509c999) | Aug 24, 2022 |
| ASUSTek       | PRIME X570-PRO              | [2b7d1d59a1](https://linux-hardware.org/?probe=2b7d1d59a1) | Aug 24, 2022 |
| ASUSTek       | PRIME A320M-K               | [928ce75df1](https://linux-hardware.org/?probe=928ce75df1) | Aug 24, 2022 |
| ASRock        | H61M-VG3                    | [a3cd7ba2c1](https://linux-hardware.org/?probe=a3cd7ba2c1) | Aug 22, 2022 |
| ASUSTek       | B85M-E                      | [0b5044dacf](https://linux-hardware.org/?probe=0b5044dacf) | Aug 19, 2022 |
| Gigabyte      | B450M DS3H-CF               | [a2b6c2ae17](https://linux-hardware.org/?probe=a2b6c2ae17) | Aug 19, 2022 |
| ASRock        | X470 Master SLI             | [ce62975b20](https://linux-hardware.org/?probe=ce62975b20) | Aug 15, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [b2bbce2845](https://linux-hardware.org/?probe=b2bbce2845) | Aug 15, 2022 |
| ASRock        | Z97 Extreme6                | [31d7973a9d](https://linux-hardware.org/?probe=31d7973a9d) | Aug 14, 2022 |
| ASRock        | 760GM-HDV                   | [beabb7dd99](https://linux-hardware.org/?probe=beabb7dd99) | Aug 14, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [27cd96982f](https://linux-hardware.org/?probe=27cd96982f) | Aug 10, 2022 |
| HP            | 8906 SMVB                   | [8f30392f49](https://linux-hardware.org/?probe=8f30392f49) | Aug 10, 2022 |
| HP            | 8054                        | [469b765fe0](https://linux-hardware.org/?probe=469b765fe0) | Aug 10, 2022 |
| ASUSTek       | G20AJ                       | [613f8a0c36](https://linux-hardware.org/?probe=613f8a0c36) | Aug 08, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [f65ba77de3](https://linux-hardware.org/?probe=f65ba77de3) | Aug 07, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [7a60eede9a](https://linux-hardware.org/?probe=7a60eede9a) | Aug 04, 2022 |
| MSI           | B450-A PRO MAX              | [e142cf5c91](https://linux-hardware.org/?probe=e142cf5c91) | Aug 04, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [7c4355417f](https://linux-hardware.org/?probe=7c4355417f) | Aug 03, 2022 |
| MSI           | X570-A PRO                  | [f034a02e69](https://linux-hardware.org/?probe=f034a02e69) | Aug 01, 2022 |
| MSI           | 970 GAMING                  | [bf2a870952](https://linux-hardware.org/?probe=bf2a870952) | Jul 23, 2022 |
| Dell          | 0J8H4R A01                  | [3d7d06475c](https://linux-hardware.org/?probe=3d7d06475c) | Jul 23, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [7d6b6d93d3](https://linux-hardware.org/?probe=7d6b6d93d3) | Jul 21, 2022 |
| eMachines     | EL1870                      | [58e76fb684](https://linux-hardware.org/?probe=58e76fb684) | Jul 19, 2022 |
| MSI           | X570-A PRO                  | [c9683ea265](https://linux-hardware.org/?probe=c9683ea265) | Jul 19, 2022 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| Nobara 37 | 131      | 42.12%  |
| Nobara 36 | 131      | 42.12%  |
| Nobara 38 | 49       | 15.76%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Nobara | 306      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                       | Desktops | Percent |
|-------------------------------|----------|---------|
| 6.0.14-201.fsync.fc36.x86_64  | 23       | 6.82%   |
| 6.2.14-300.fsync.fc37.x86_64  | 21       | 6.23%   |
| 6.1.14-201.fsync.fc37.x86_64  | 16       | 4.75%   |
| 6.0.10-201.fc36.x86_64        | 16       | 4.75%   |
| 6.3.12-204.fsync.fc38.x86_64  | 15       | 4.45%   |
| 6.2.12-200.fsync.fc37.x86_64  | 12       | 3.56%   |
| 6.4.10-202.fsync.fc38.x86_64  | 11       | 3.26%   |
| 6.2.6-201.fsync.fc37.x86_64   | 10       | 2.97%   |
| 5.19.14-201.fsync.fc36.x86_64 | 9        | 2.67%   |
| 6.2.8-200.fsync.fc37.x86_64   | 8        | 2.37%   |
| 6.2.10-200.fsync.fc37.x86_64  | 8        | 2.37%   |
| 6.1.9-200.fsync.fc37.x86_64   | 8        | 2.37%   |
| 5.19.9-201.fsync.fc36.x86_64  | 8        | 2.37%   |
| 5.19.7-204.fsync.fc36.x86_64  | 8        | 2.37%   |
| 5.19.16-201.fsync.fc36.x86_64 | 8        | 2.37%   |
| 6.3.7-200.fsync.fc37.x86_64   | 7        | 2.08%   |
| 6.3.12-205.fsync.fc38.x86_64  | 7        | 2.08%   |
| 6.3.10-200.fsync.fc38.x86_64  | 7        | 2.08%   |
| 6.1.6-203.fsync.fc37.x86_64   | 7        | 2.08%   |
| 6.1.4-203.fsync.fc37.x86_64   | 7        | 2.08%   |
| 6.1.11-201.fsync.fc37.x86_64  | 7        | 2.08%   |
| 5.18.13-201.fsync.fc36.x86_64 | 7        | 2.08%   |
| 6.2.11-202.fsync.fc37.x86_64  | 6        | 1.78%   |
| 6.0.9-201.fc36.x86_64         | 6        | 1.78%   |
| 6.0.7-201.fsync.fc36.x86_64   | 6        | 1.78%   |
| 6.0.5-201.fsync.fc36.x86_64   | 6        | 1.78%   |
| 5.19.10-201.fsync.fc36.x86_64 | 6        | 1.78%   |
| 6.3.12-203.fsync.fc38.x86_64  | 4        | 1.19%   |
| 6.1.8-202.fsync.fc37.x86_64   | 4        | 1.19%   |
| 5.19.4-201.fsync.fc36.x86_64  | 4        | 1.19%   |
| 5.19.15-202.fsync.fc36.x86_64 | 4        | 1.19%   |
| 5.18.17-201.fsync.fc36.x86_64 | 4        | 1.19%   |
| 5.18.16-201.fsync.fc36.x86_64 | 4        | 1.19%   |
| 6.3.5-201.fsync.fc37.x86_64   | 3        | 0.89%   |
| 6.3.12-205.fsync.fc37.x86_64  | 3        | 0.89%   |
| 6.0.16-301.fsync.fc37.x86_64  | 3        | 0.89%   |
| 5.19.12-201.fsync.fc36.x86_64 | 3        | 0.89%   |
| 5.18.19-201.fsync.fc36.x86_64 | 3        | 0.89%   |
| 5.18.11-201.fsync.fc36.x86_64 | 3        | 0.89%   |
| 6.4.8-203.fsync.fc38.x86_64   | 2        | 0.59%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.3.12  | 30       | 8.93%   |
| 6.0.14  | 23       | 6.85%   |
| 6.2.14  | 21       | 6.25%   |
| 6.1.14  | 16       | 4.76%   |
| 6.0.10  | 16       | 4.76%   |
| 6.4.10  | 13       | 3.87%   |
| 6.2.12  | 12       | 3.57%   |
| 6.2.6   | 10       | 2.98%   |
| 6.3.10  | 9        | 2.68%   |
| 6.1.6   | 9        | 2.68%   |
| 5.19.7  | 9        | 2.68%   |
| 5.19.14 | 9        | 2.68%   |
| 6.2.8   | 8        | 2.38%   |
| 6.2.11  | 8        | 2.38%   |
| 6.2.10  | 8        | 2.38%   |
| 6.1.9   | 8        | 2.38%   |
| 6.0.7   | 8        | 2.38%   |
| 5.19.9  | 8        | 2.38%   |
| 5.19.16 | 8        | 2.38%   |
| 6.3.7   | 7        | 2.08%   |
| 6.1.4   | 7        | 2.08%   |
| 6.1.11  | 7        | 2.08%   |
| 5.18.13 | 7        | 2.08%   |
| 6.1.8   | 6        | 1.79%   |
| 6.0.9   | 6        | 1.79%   |
| 6.0.5   | 6        | 1.79%   |
| 5.19.10 | 6        | 1.79%   |
| 6.4.8   | 4        | 1.19%   |
| 6.3.5   | 4        | 1.19%   |
| 5.19.4  | 4        | 1.19%   |
| 5.19.15 | 4        | 1.19%   |
| 5.18.17 | 4        | 1.19%   |
| 5.18.16 | 4        | 1.19%   |
| 6.0.16  | 3        | 0.89%   |
| 5.19.12 | 3        | 0.89%   |
| 5.18.19 | 3        | 0.89%   |
| 5.18.11 | 3        | 0.89%   |
| 6.0.8   | 2        | 0.6%    |
| 6.0.18  | 2        | 0.6%    |
| 5.19.13 | 2        | 0.6%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.2     | 64       | 19.51%  |
| 6.0     | 63       | 19.21%  |
| 5.19    | 56       | 17.07%  |
| 6.1     | 53       | 16.16%  |
| 6.3     | 51       | 15.55%  |
| 5.18    | 23       | 7.01%   |
| 6.4     | 18       | 5.49%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 306      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 218      | 70.78%  |
| KDE5          | 84       | 27.27%  |
| GNOME Classic | 2        | 0.65%   |
| Unknown       | 2        | 0.65%   |
| X-Cinnamon    | 1        | 0.32%   |
| sway          | 1        | 0.32%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 229      | 73.16%  |
| X11     | 82       | 26.2%   |
| Unknown | 2        | 0.64%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 254      | 82.74%  |
| GDM     | 34       | 11.07%  |
| SDDM    | 17       | 5.54%   |
| LightDM | 2        | 0.65%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 169      | 55.05%  |
| en_GB   | 29       | 9.45%   |
| de_DE   | 19       | 6.19%   |
| es_ES   | 11       | 3.58%   |
| es_MX   | 9        | 2.93%   |
| en_CA   | 9        | 2.93%   |
| fr_FR   | 7        | 2.28%   |
| es_AR   | 7        | 2.28%   |
| pt_BR   | 5        | 1.63%   |
| de_AT   | 5        | 1.63%   |
| ru_RU   | 4        | 1.3%    |
| pl_PL   | 3        | 0.98%   |
| nl_NL   | 3        | 0.98%   |
| it_IT   | 3        | 0.98%   |
| es_CO   | 3        | 0.98%   |
| en_PH   | 2        | 0.65%   |
| en_NZ   | 2        | 0.65%   |
| en_AU   | 2        | 0.65%   |
| sv_SE   | 1        | 0.33%   |
| sk_SK   | 1        | 0.33%   |
| pt_PT   | 1        | 0.33%   |
| nl_BE   | 1        | 0.33%   |
| fr_BE   | 1        | 0.33%   |
| fi_FI   | 1        | 0.33%   |
| es_GT   | 1        | 0.33%   |
| es_EC   | 1        | 0.33%   |
| es_CL   | 1        | 0.33%   |
| en_IL   | 1        | 0.33%   |
| da_DK   | 1        | 0.33%   |
| cs_CZ   | 1        | 0.33%   |
| C       | 1        | 0.33%   |
| ar_SA   | 1        | 0.33%   |
| Unknown | 1        | 0.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 238      | 77.27%  |
| BIOS | 70       | 22.73%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Btrfs | 236      | 76.87%  |
| Ext4  | 70       | 22.8%   |
| Xfs   | 1        | 0.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 251      | 81.76%  |
| GPT     | 51       | 16.61%  |
| MBR     | 5        | 1.63%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 292      | 95.42%  |
| Yes       | 14       | 4.58%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 277      | 90.52%  |
| Yes       | 29       | 9.48%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 93       | 30.39%  |
| MSI                                  | 69       | 22.55%  |
| Gigabyte Technology                  | 52       | 16.99%  |
| ASRock                               | 36       | 11.76%  |
| Hewlett-Packard                      | 13       | 4.25%   |
| Dell                                 | 13       | 4.25%   |
| Intel                                | 5        | 1.63%   |
| Lenovo                               | 3        | 0.98%   |
| Shenzhen Meigao Electronic Equipment | 2        | 0.65%   |
| Pegatron                             | 2        | 0.65%   |
| Biostar                              | 2        | 0.65%   |
| Alienware                            | 2        | 0.65%   |
| Acer                                 | 2        | 0.65%   |
| Unknown                              | 2        | 0.65%   |
| Protectli                            | 1        | 0.33%   |
| OEM                                  | 1        | 0.33%   |
| NZXT                                 | 1        | 0.33%   |
| langchao                             | 1        | 0.33%   |
| GPD                                  | 1        | 0.33%   |
| Fujitsu                              | 1        | 0.33%   |
| eMachines                            | 1        | 0.33%   |
| ECS                                  | 1        | 0.33%   |
| AOpen                                | 1        | 0.33%   |
| Acidanthera                          | 1        | 0.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| MSI MS-7B86                                | 8        | 2.61%   |
| MSI MS-7D25                                | 5        | 1.63%   |
| MSI MS-7C91                                | 5        | 1.63%   |
| MSI MS-7C37                                | 5        | 1.63%   |
| MSI MS-7C02                                | 5        | 1.63%   |
| ASUS All Series                            | 5        | 1.63%   |
| MSI MS-7B79                                | 4        | 1.31%   |
| ASUS ROG STRIX B550-F GAMING               | 4        | 1.31%   |
| Gigabyte B550 AORUS ELITE V2               | 3        | 0.98%   |
| Dell XPS 8700                              | 3        | 0.98%   |
| ASUS PRIME A320M-K                         | 3        | 0.98%   |
| MSI MS-7C87                                | 2        | 0.65%   |
| MSI MS-7C56                                | 2        | 0.65%   |
| MSI MS-7B85                                | 2        | 0.65%   |
| MSI MS-7721                                | 2        | 0.65%   |
| MSI MS-7693                                | 2        | 0.65%   |
| Intel X79                                  | 2        | 0.65%   |
| Gigabyte Z590I VISION D                    | 2        | 0.65%   |
| Gigabyte X570 AORUS ELITE WIFI             | 2        | 0.65%   |
| Gigabyte X570 AORUS ELITE                  | 2        | 0.65%   |
| Gigabyte B450M DS3H                        | 2        | 0.65%   |
| Dell OptiPlex 390                          | 2        | 0.65%   |
| ASUS TUF Gaming X570-PLUS                  | 2        | 0.65%   |
| ASUS TUF Gaming B550M-PLUS                 | 2        | 0.65%   |
| ASUS TUF Gaming B550-PLUS                  | 2        | 0.65%   |
| ASUS TUF Gaming B460-PLUS                  | 2        | 0.65%   |
| ASUS ROG STRIX B650E-I GAMING WIFI         | 2        | 0.65%   |
| ASUS ROG CROSSHAIR X670E GENE              | 2        | 0.65%   |
| ASUS ROG CROSSHAIR VIII HERO               | 2        | 0.65%   |
| ASUS PRIME X370-PRO                        | 2        | 0.65%   |
| ASUS PRIME B450M-A                         | 2        | 0.65%   |
| ASUS CROSSHAIR VI HERO                     | 2        | 0.65%   |
| ASUS A68HM-K                               | 2        | 0.65%   |
| ASRock X670E Steel Legend                  | 2        | 0.65%   |
| ASRock B550 Phantom Gaming-ITX/ax          | 2        | 0.65%   |
| Unknown                                    | 2        | 0.65%   |
| Shenzhen Meigao Electronic Equipment UM690 | 1        | 0.33%   |
| Shenzhen Meigao Electronic Equipment UM590 | 1        | 0.33%   |
| Protectli FW6                              | 1        | 0.33%   |
| Pegatron NF335AA-ABZ a6664it               | 1        | 0.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| ASUS ROG           | 26       | 8.5%    |
| ASUS PRIME         | 21       | 6.86%   |
| ASUS TUF           | 19       | 6.21%   |
| MSI MS-7B86        | 8        | 2.61%   |
| Gigabyte X570      | 7        | 2.29%   |
| Dell OptiPlex      | 6        | 1.96%   |
| MSI MS-7D25        | 5        | 1.63%   |
| MSI MS-7C91        | 5        | 1.63%   |
| MSI MS-7C37        | 5        | 1.63%   |
| MSI MS-7C02        | 5        | 1.63%   |
| ASUS All           | 5        | 1.63%   |
| MSI MS-7B79        | 4        | 1.31%   |
| Gigabyte B550M     | 4        | 1.31%   |
| Gigabyte B550      | 4        | 1.31%   |
| HP Pavilion        | 3        | 0.98%   |
| HP EliteDesk       | 3        | 0.98%   |
| HP Compaq          | 3        | 0.98%   |
| Dell XPS           | 3        | 0.98%   |
| ASRock B550        | 3        | 0.98%   |
| MSI MS-7C87        | 2        | 0.65%   |
| MSI MS-7C56        | 2        | 0.65%   |
| MSI MS-7B85        | 2        | 0.65%   |
| MSI MS-7721        | 2        | 0.65%   |
| MSI MS-7693        | 2        | 0.65%   |
| Lenovo ThinkCentre | 2        | 0.65%   |
| Intel X79          | 2        | 0.65%   |
| HP ProDesk         | 2        | 0.65%   |
| Gigabyte Z590I     | 2        | 0.65%   |
| Gigabyte X670      | 2        | 0.65%   |
| Gigabyte H410M     | 2        | 0.65%   |
| Gigabyte H310M     | 2        | 0.65%   |
| Gigabyte G1.Sniper | 2        | 0.65%   |
| Gigabyte B450M     | 2        | 0.65%   |
| Dell Precision     | 2        | 0.65%   |
| ASUS M5A97         | 2        | 0.65%   |
| ASUS CROSSHAIR     | 2        | 0.65%   |
| ASUS A68HM-K       | 2        | 0.65%   |
| ASRock Z97         | 2        | 0.65%   |
| ASRock X670E       | 2        | 0.65%   |
| ASRock H310M-HDV   | 2        | 0.65%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 48       | 15.69%  |
| 2019 | 46       | 15.03%  |
| 2021 | 35       | 11.44%  |
| 2018 | 34       | 11.11%  |
| 2022 | 32       | 10.46%  |
| 2013 | 24       | 7.84%   |
| 2012 | 17       | 5.56%   |
| 2017 | 14       | 4.58%   |
| 2016 | 13       | 4.25%   |
| 2014 | 13       | 4.25%   |
| 2011 | 12       | 3.92%   |
| 2015 | 6        | 1.96%   |
| 2008 | 4        | 1.31%   |
| 2023 | 3        | 0.98%   |
| 2010 | 3        | 0.98%   |
| 2009 | 2        | 0.65%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 306      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 306      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 306      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 109      | 35.5%   |
| 32.01-64.0  | 95       | 30.94%  |
| 8.01-16.0   | 27       | 8.79%   |
| 24.01-32.0  | 24       | 7.82%   |
| 64.01-256.0 | 21       | 6.84%   |
| 4.01-8.0    | 19       | 6.19%   |
| 3.01-4.0    | 12       | 3.91%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 149      | 45.71%  |
| 3.01-4.0   | 74       | 22.7%   |
| 2.01-3.0   | 43       | 13.19%  |
| 8.01-16.0  | 40       | 12.27%  |
| 1.01-2.0   | 9        | 2.76%   |
| 16.01-24.0 | 8        | 2.45%   |
| 24.01-32.0 | 2        | 0.61%   |
| 32.01-64.0 | 1        | 0.31%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 92       | 29.39%  |
| 1      | 75       | 23.96%  |
| 3      | 73       | 23.32%  |
| 4      | 31       | 9.9%    |
| 5      | 24       | 7.67%   |
| 6      | 7        | 2.24%   |
| 7      | 4        | 1.28%   |
| 8      | 3        | 0.96%   |
| 10     | 2        | 0.64%   |
| 9      | 2        | 0.64%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 249      | 80.84%  |
| Yes       | 59       | 19.16%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 303      | 99.02%  |
| No        | 3        | 0.98%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 182      | 58.9%   |
| No        | 127      | 41.1%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 166      | 54.07%  |
| No        | 141      | 45.93%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 101      | 33.01%  |
| Germany      | 23       | 7.52%   |
| UK           | 20       | 6.54%   |
| France       | 14       | 4.58%   |
| Netherlands  | 12       | 3.92%   |
| Canada       | 12       | 3.92%   |
| Argentina    | 11       | 3.59%   |
| Spain        | 10       | 3.27%   |
| Brazil       | 9        | 2.94%   |
| Mexico       | 7        | 2.29%   |
| Italy        | 7        | 2.29%   |
| Sweden       | 6        | 1.96%   |
| Russia       | 5        | 1.63%   |
| Austria      | 5        | 1.63%   |
| Saudi Arabia | 4        | 1.31%   |
| Poland       | 4        | 1.31%   |
| Australia    | 4        | 1.31%   |
| Philippines  | 3        | 0.98%   |
| Hungary      | 3        | 0.98%   |
| Finland      | 3        | 0.98%   |
| Colombia     | 3        | 0.98%   |
| Chile        | 3        | 0.98%   |
| Belgium      | 3        | 0.98%   |
| Venezuela    | 2        | 0.65%   |
| Turkey       | 2        | 0.65%   |
| Serbia       | 2        | 0.65%   |
| Portugal     | 2        | 0.65%   |
| New Zealand  | 2        | 0.65%   |
| Japan        | 2        | 0.65%   |
| Estonia      | 2        | 0.65%   |
| Czechia      | 2        | 0.65%   |
| Ukraine      | 1        | 0.33%   |
| Thailand     | 1        | 0.33%   |
| Switzerland  | 1        | 0.33%   |
| South Korea  | 1        | 0.33%   |
| South Africa | 1        | 0.33%   |
| Slovakia     | 1        | 0.33%   |
| Norway       | 1        | 0.33%   |
| Lithuania    | 1        | 0.33%   |
| Kuwait       | 1        | 0.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Buenos Aires             | 3        | 0.95%   |
| Atlanta                  | 3        | 0.95%   |
| Amsterdam                | 3        | 0.95%   |
| Vienna                   | 2        | 0.63%   |
| Victoria                 | 2        | 0.63%   |
| Toulouse                 | 2        | 0.63%   |
| Stockholm                | 2        | 0.63%   |
| Seattle                  | 2        | 0.63%   |
| Rotterdam                | 2        | 0.63%   |
| Roseville                | 2        | 0.63%   |
| Rome                     | 2        | 0.63%   |
| Philadelphia             | 2        | 0.63%   |
| New York                 | 2        | 0.63%   |
| Herten                   | 2        | 0.63%   |
| Helsinki                 | 2        | 0.63%   |
| Guadalajara              | 2        | 0.63%   |
| Gothenburg               | 2        | 0.63%   |
| Goiânia                 | 2        | 0.63%   |
| Frankfurt am Main        | 2        | 0.63%   |
| Donostia / San Sebastian | 2        | 0.63%   |
| Denver                   | 2        | 0.63%   |
| Cardiff                  | 2        | 0.63%   |
| Berlin                   | 2        | 0.63%   |
| Bad Wildbad              | 2        | 0.63%   |
| Zurich                   | 1        | 0.32%   |
| Zagreb                   | 1        | 0.32%   |
| Wuppertal                | 1        | 0.32%   |
| Wooster                  | 1        | 0.32%   |
| Wilkesboro               | 1        | 0.32%   |
| Wiesbaden                | 1        | 0.32%   |
| Whippany                 | 1        | 0.32%   |
| Wellington               | 1        | 0.32%   |
| Wassenberg               | 1        | 0.32%   |
| Warsaw                   | 1        | 0.32%   |
| Waldorf                  | 1        | 0.32%   |
| Vouziers                 | 1        | 0.32%   |
| Voiron                   | 1        | 0.32%   |
| Vineland                 | 1        | 0.32%   |
| Vilnius                  | 1        | 0.32%   |
| Villahermosa             | 1        | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 113      | 204    | 16.52%  |
| WDC                         | 102      | 149    | 14.91%  |
| Seagate                     | 87       | 122    | 12.72%  |
| Sandisk                     | 50       | 62     | 7.31%   |
| Kingston                    | 48       | 56     | 7.02%   |
| Crucial                     | 41       | 60     | 5.99%   |
| Toshiba                     | 39       | 44     | 5.7%    |
| Phison Electronics          | 23       | 27     | 3.36%   |
| Micron/Crucial Technology   | 19       | 27     | 2.78%   |
| PNY                         | 10       | 17     | 1.46%   |
| Intel                       | 10       | 16     | 1.46%   |
| Hitachi                     | 10       | 14     | 1.46%   |
| Phison                      | 8        | 9      | 1.17%   |
| Kingston Technology Company | 8        | 8      | 1.17%   |
| SPCC                        | 7        | 8      | 1.02%   |
| Silicon Motion              | 7        | 7      | 1.02%   |
| Realtek Semiconductor       | 7        | 7      | 1.02%   |
| Unknown                     | 6        | 10     | 0.88%   |
| China                       | 6        | 6      | 0.88%   |
| Team                        | 5        | 5      | 0.73%   |
| HGST                        | 5        | 8      | 0.73%   |
| ADATA Technology            | 5        | 5      | 0.73%   |
| Micron Technology           | 4        | 4      | 0.58%   |
| A-DATA Technology           | 4        | 4      | 0.58%   |
| KIOXIA-EXCERIA              | 3        | 3      | 0.44%   |
| KIOXIA                      | 3        | 3      | 0.44%   |
| Verbatim                    | 2        | 2      | 0.29%   |
| Transcend                   | 2        | 2      | 0.29%   |
| SK hynix                    | 2        | 3      | 0.29%   |
| OCZ                         | 2        | 2      | 0.29%   |
| Maxtor                      | 2        | 2      | 0.29%   |
| MAXIO Technology (Hangzhou) | 2        | 2      | 0.29%   |
| Intenso                     | 2        | 3      | 0.29%   |
| Drevo                       | 2        | 2      | 0.29%   |
| Corsair                     | 2        | 2      | 0.29%   |
| Apple                       | 2        | 2      | 0.29%   |
| Apacer                      | 2        | 2      | 0.29%   |
| XSTAR                       | 1        | 1      | 0.15%   |
| XPG                         | 1        | 1      | 0.15%   |
| WDC WDS                     | 1        | 1      | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB   | 23       | 2.85%   |
| Phison E12 NVMe Controller 256GB                      | 15       | 1.86%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                   | 15       | 1.86%   |
| Kingston SA400S37240G 240GB SSD                       | 14       | 1.73%   |
| Samsung SSD 850 EVO 500GB                             | 11       | 1.36%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1024GB | 11       | 1.36%   |
| Seagate ST2000DM008-2FR102 2TB                        | 10       | 1.24%   |
| Samsung SSD 860 EVO 1TB                               | 10       | 1.24%   |
| Samsung SSD 860 EVO 500GB                             | 9        | 1.11%   |
| Crucial CT1000MX500SSD1 1TB                           | 9        | 1.11%   |
| Sandisk WD Blue SN550 NVMe SSD 250GB                  | 8        | 0.99%   |
| Samsung SSD 850 EVO 250GB                             | 7        | 0.87%   |
| WDC WD10EZEX-00BN5A0 1TB                              | 6        | 0.74%   |
| Toshiba DT01ACA100 1TB                                | 6        | 0.74%   |
| Intel SSD 660P Series 512GB                           | 6        | 0.74%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 5        | 0.62%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                        | 5        | 0.62%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 5        | 0.62%   |
| Toshiba HDWD110 1TB                                   | 5        | 0.62%   |
| Toshiba DT01ACA200 2TB                                | 5        | 0.62%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 5        | 0.62%   |
| Seagate ST2000DM001-1ER164 2TB                        | 5        | 0.62%   |
| Samsung SSD 980 1TB                                   | 5        | 0.62%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1024GB  | 5        | 0.62%   |
| Crucial CT240BX500SSD1 240GB                          | 5        | 0.62%   |
| Crucial CT1000BX500SSD1 1TB                           | 5        | 0.62%   |
| WDC WD10JPCX-24UE4T0 1TB                              | 4        | 0.5%    |
| Seagate ST500DM002-1BD142 500GB                       | 4        | 0.5%    |
| Seagate ST4000DM004-2CV104 4TB                        | 4        | 0.5%    |
| Seagate ST1000DM003-1ER162 1TB                        | 4        | 0.5%    |
| Sandisk WD Blue SN570 500GB                           | 4        | 0.5%    |
| Sandisk WD Black SN850 256GB                          | 4        | 0.5%    |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB     | 4        | 0.5%    |
| Samsung SSD 980 500GB                                 | 4        | 0.5%    |
| Samsung SSD 870 EVO 1TB                               | 4        | 0.5%    |
| Samsung SSD 840 EVO 250GB                             | 4        | 0.5%    |
| PNY CS900 500GB SSD                                   | 4        | 0.5%    |
| Phison PS5013 E13 NVMe Controller 512GB               | 4        | 0.5%    |
| Kingston SA400S37960G 960GB SSD                       | 4        | 0.5%    |
| Kingston SA400S37480G 480GB SSD                       | 4        | 0.5%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 85       | 117    | 36.48%  |
| WDC                 | 81       | 116    | 34.76%  |
| Toshiba             | 33       | 38     | 14.16%  |
| Samsung Electronics | 13       | 22     | 5.58%   |
| Hitachi             | 10       | 14     | 4.29%   |
| HGST                | 5        | 8      | 2.15%   |
| Maxtor              | 2        | 2      | 0.86%   |
| Apple               | 2        | 2      | 0.86%   |
| SABRENT             | 1        | 2      | 0.43%   |
| Hewlett-Packard     | 1        | 1      | 0.43%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 71       | 97     | 26.2%   |
| Crucial             | 40       | 59     | 14.76%  |
| Kingston            | 38       | 44     | 14.02%  |
| WDC                 | 27       | 30     | 9.96%   |
| SanDisk             | 16       | 19     | 5.9%    |
| PNY                 | 10       | 17     | 3.69%   |
| SPCC                | 7        | 8      | 2.58%   |
| China               | 6        | 6      | 2.21%   |
| Team                | 4        | 4      | 1.48%   |
| A-DATA Technology   | 4        | 4      | 1.48%   |
| Toshiba             | 3        | 3      | 1.11%   |
| Micron Technology   | 3        | 3      | 1.11%   |
| KIOXIA-EXCERIA      | 3        | 3      | 1.11%   |
| Verbatim            | 2        | 2      | 0.74%   |
| Transcend           | 2        | 2      | 0.74%   |
| Seagate             | 2        | 2      | 0.74%   |
| OCZ                 | 2        | 2      | 0.74%   |
| Intel               | 2        | 2      | 0.74%   |
| Drevo               | 2        | 2      | 0.74%   |
| Apacer              | 2        | 2      | 0.74%   |
| XSTAR               | 1        | 1      | 0.37%   |
| WDC WDS             | 1        | 1      | 0.37%   |
| USB3.0              | 1        | 1      | 0.37%   |
| SuperSSpeed         | 1        | 1      | 0.37%   |
| SD                  | 1        | 1      | 0.37%   |
| SCY                 | 1        | 1      | 0.37%   |
| Ramaxel Technology  | 1        | 1      | 0.37%   |
| PNY CS90            | 1        | 1      | 0.37%   |
| Patriot             | 1        | 1      | 0.37%   |
| ORTIAL              | 1        | 1      | 0.37%   |
| Neo                 | 1        | 1      | 0.37%   |
| MyDigitalSSD        | 1        | 1      | 0.37%   |
| Mushkin             | 1        | 1      | 0.37%   |
| LITEONIT            | 1        | 1      | 0.37%   |
| Leven               | 1        | 1      | 0.37%   |
| KingFast            | 1        | 1      | 0.37%   |
| JMicron Technology  | 1        | 1      | 0.37%   |
| Intenso             | 1        | 1      | 0.37%   |
| Hypertec            | 1        | 1      | 0.37%   |
| GOODRAM             | 1        | 1      | 0.37%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 209      | 336    | 36.67%  |
| HDD     | 183      | 322    | 32.11%  |
| NVMe    | 166      | 269    | 29.12%  |
| Unknown | 11       | 14     | 1.93%   |
| MMC     | 1        | 1      | 0.18%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 260      | 635    | 57.52%  |
| NVMe | 165      | 268    | 36.5%   |
| SAS  | 26       | 38     | 5.75%   |
| MMC  | 1        | 1      | 0.22%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 178      | 290    | 40.64%  |
| 0.51-1.0   | 140      | 200    | 31.96%  |
| 1.01-2.0   | 68       | 101    | 15.53%  |
| 3.01-4.0   | 21       | 27     | 4.79%   |
| 4.01-10.0  | 17       | 23     | 3.88%   |
| 2.01-3.0   | 10       | 12     | 2.28%   |
| 10.01-20.0 | 4        | 5      | 0.91%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 72       | 23.15%  |
| More than 3000 | 53       | 17.04%  |
| 501-1000       | 51       | 16.4%   |
| 251-500        | 48       | 15.43%  |
| 101-250        | 44       | 14.15%  |
| 2001-3000      | 24       | 7.72%   |
| 21-50          | 8        | 2.57%   |
| 51-100         | 6        | 1.93%   |
| Unknown        | 3        | 0.96%   |
| 1-20           | 2        | 0.64%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 21-50          | 71       | 21.98%  |
| 1-20           | 55       | 17.03%  |
| 101-250        | 42       | 13%     |
| 51-100         | 38       | 11.76%  |
| 251-500        | 35       | 10.84%  |
| 501-1000       | 33       | 10.22%  |
| 1001-2000      | 19       | 5.88%   |
| More than 3000 | 14       | 4.33%   |
| 2001-3000      | 13       | 4.02%   |
| Unknown        | 3        | 0.93%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Desktops | Drives | Percent |
|------------------------------------------------|----------|--------|---------|
| WDC WD5000BEVT-75ZAT0 500GB                    | 2        | 2      | 16.67%  |
| WDC WD30EZRX-00DC0B0 3TB                       | 1        | 1      | 8.33%   |
| WDC WD20EURS-63S48Y0 2TB                       | 1        | 1      | 8.33%   |
| WDC WD10EZEX-08M2NA0 1TB                       | 1        | 1      | 8.33%   |
| WDC WD10EACS-00D6B0 1TB                        | 1        | 1      | 8.33%   |
| Seagate ST500DM002-1BD142 500GB                | 1        | 1      | 8.33%   |
| Seagate ST2000DX002-2DV164 2TB                 | 1        | 1      | 8.33%   |
| Seagate ST1000DM003-9YN162 1TB                 | 1        | 1      | 8.33%   |
| Samsung Electronics SSD 970 EVO 1TB            | 1        | 1      | 8.33%   |
| Samsung Electronics HD161GJ 160GB              | 1        | 1      | 8.33%   |
| Micron Technology MTFDDAK256MAM-1K12 256GB SSD | 1        | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 6        | 6      | 50%     |
| Seagate             | 3        | 3      | 25%     |
| Samsung Electronics | 2        | 2      | 16.67%  |
| Micron Technology   | 1        | 1      | 8.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 6        | 6      | 60%     |
| Seagate             | 3        | 3      | 30%     |
| Samsung Electronics | 1        | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 10       | 10     | 83.33%  |
| NVMe | 1        | 1      | 8.33%   |
| SSD  | 1        | 1      | 8.33%   |

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
| Detected | 256      | 784    | 80%     |
| Works    | 52       | 145    | 16.25%  |
| Malfunc  | 11       | 12     | 3.44%   |
| Limited  | 1        | 1      | 0.31%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| AMD                          | 163      | 30.13%  |
| Intel                        | 141      | 26.06%  |
| Samsung Electronics          | 56       | 10.35%  |
| SanDisk                      | 37       | 6.84%   |
| Phison Electronics           | 31       | 5.73%   |
| ASMedia Technology           | 24       | 4.44%   |
| Micron/Crucial Technology    | 20       | 3.7%    |
| Kingston Technology Company  | 20       | 3.7%    |
| Realtek Semiconductor        | 8        | 1.48%   |
| Silicon Motion               | 7        | 1.29%   |
| ADATA Technology             | 5        | 0.92%   |
| Nvidia                       | 4        | 0.74%   |
| Marvell Technology Group     | 4        | 0.74%   |
| KIOXIA                       | 3        | 0.55%   |
| JMicron Technology           | 3        | 0.55%   |
| Toshiba America Info Systems | 2        | 0.37%   |
| Solidigm                     | 2        | 0.37%   |
| SK hynix                     | 2        | 0.37%   |
| MAXIO Technology (Hangzhou)  | 2        | 0.37%   |
| Broadcom / LSI               | 2        | 0.37%   |
| Silicon Image                | 1        | 0.18%   |
| Seagate Technology           | 1        | 0.18%   |
| Micron Technology            | 1        | 0.18%   |
| LSI Logic / Symbios Logic    | 1        | 0.18%   |
| Biwin Storage Technology     | 1        | 0.18%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 96       | 15.48%  |
| AMD 400 Series Chipset SATA Controller                                         | 41       | 6.61%   |
| AMD 500 Series Chipset SATA Controller                                         | 36       | 5.81%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 30       | 4.84%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 23       | 3.71%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 17       | 2.74%   |
| Phison E12 NVMe Controller                                                     | 16       | 2.58%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 15       | 2.42%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 14       | 2.26%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 14       | 2.26%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 13       | 2.1%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 11       | 1.77%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 10       | 1.61%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 10       | 1.61%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 10       | 1.61%   |
| Samsung NVMe SSD Controller 980                                                | 9        | 1.45%   |
| Intel SATA Controller [RAID mode]                                              | 9        | 1.45%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 9        | 1.45%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 9        | 1.45%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 8        | 1.29%   |
| Kingston Company A2000 NVMe SSD                                                | 8        | 1.29%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 8        | 1.29%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                             | 7        | 1.13%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 6        | 0.97%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 6        | 0.97%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 6        | 0.97%   |
| Phison E16 PCIe4 NVMe Controller                                               | 6        | 0.97%   |
| Intel SSD 660P Series                                                          | 6        | 0.97%   |
| Sandisk Western Digital WD Black SN850X NVMe SSD                               | 5        | 0.81%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 5        | 0.81%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 5        | 0.81%   |
| Kingston Company Company Non-Volatile memory controller                        | 5        | 0.81%   |
| Intel Volume Management Device NVMe RAID Controller                            | 5        | 0.81%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 5        | 0.81%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 5        | 0.81%   |
| Realtek RTS5763DL NVMe SSD Controller                                          | 4        | 0.65%   |
| Phison PS5013 E13 NVMe Controller                                              | 4        | 0.65%   |
| Phison E18 PCIe4 NVMe Controller                                               | 4        | 0.65%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                           | 4        | 0.65%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4        | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 282      | 57.43%  |
| NVMe | 165      | 33.6%   |
| IDE  | 24       | 4.89%   |
| RAID | 16       | 3.26%   |
| SAS  | 4        | 0.81%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 168      | 54.9%   |
| Intel  | 138      | 45.1%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 14       | 4.56%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 13       | 4.23%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 11       | 3.58%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 9        | 2.93%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 8        | 2.61%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 7        | 2.28%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 6        | 1.95%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 5        | 1.63%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 5        | 1.63%   |
| AMD Ryzen 9 7950X 16-Core Processor         | 5        | 1.63%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 5        | 1.63%   |
| AMD Ryzen 7 5700X 8-Core Processor          | 5        | 1.63%   |
| AMD Ryzen 5 7600X 6-Core Processor          | 5        | 1.63%   |
| AMD FX-8350 Eight-Core Processor            | 5        | 1.63%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 4        | 1.3%    |
| Intel Core i7-4770 CPU @ 3.40GHz            | 4        | 1.3%    |
| Intel Core i5-9400F CPU @ 2.90GHz           | 4        | 1.3%    |
| Intel Core i5-10400F CPU @ 2.90GHz          | 4        | 1.3%    |
| Intel 12th Gen Core i5-12600K               | 4        | 1.3%    |
| AMD Ryzen 9 7900X 12-Core Processor         | 4        | 1.3%    |
| AMD Ryzen 9 5950X 16-Core Processor         | 4        | 1.3%    |
| AMD Ryzen 7 5700G with Radeon Graphics      | 4        | 1.3%    |
| AMD Ryzen 5 5500                            | 4        | 1.3%    |
| Intel Core i7-4790K CPU @ 4.00GHz           | 3        | 0.98%   |
| Intel 12th Gen Core i7-12700K               | 3        | 0.98%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz      | 3        | 0.98%   |
| AMD Ryzen 7 5800X3D 8-Core Processor        | 3        | 0.98%   |
| AMD Ryzen 5 5600 6-Core Processor           | 3        | 0.98%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 3        | 0.98%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 3        | 0.98%   |
| AMD FX-6300 Six-Core Processor              | 3        | 0.98%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 2        | 0.65%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 2        | 0.65%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 2        | 0.65%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2        | 0.65%   |
| Intel Core i7-10700K CPU @ 3.80GHz          | 2        | 0.65%   |
| Intel Core i5-8600K CPU @ 3.60GHz           | 2        | 0.65%   |
| Intel Core i5-7600K CPU @ 3.80GHz           | 2        | 0.65%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 2        | 0.65%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 2        | 0.65%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| AMD Ryzen 5             | 68       | 22.15%  |
| Intel Core i5           | 46       | 14.98%  |
| AMD Ryzen 7             | 37       | 12.05%  |
| Intel Core i7           | 33       | 10.75%  |
| AMD Ryzen 9             | 32       | 10.42%  |
| Other                   | 23       | 7.49%   |
| Intel Core i3           | 15       | 4.89%   |
| AMD FX                  | 11       | 3.58%   |
| Intel Xeon              | 9        | 2.93%   |
| Intel Core i9           | 5        | 1.63%   |
| AMD Ryzen 3             | 5        | 1.63%   |
| AMD Phenom II X6        | 3        | 0.98%   |
| Intel Pentium           | 2        | 0.65%   |
| Intel Core 2 Duo        | 2        | 0.65%   |
| AMD A4                  | 2        | 0.65%   |
| AMD A10                 | 2        | 0.65%   |
| Intel Pentium Dual-Core | 1        | 0.33%   |
| Intel Core 2 Quad       | 1        | 0.33%   |
| Intel Celeron           | 1        | 0.33%   |
| Intel Atom              | 1        | 0.33%   |
| AMD Ryzen Threadripper  | 1        | 0.33%   |
| AMD Phenom II X4        | 1        | 0.33%   |
| AMD Phenom              | 1        | 0.33%   |
| AMD Athlon X4           | 1        | 0.33%   |
| AMD Athlon II X2        | 1        | 0.33%   |
| AMD Athlon Dual Core    | 1        | 0.33%   |
| AMD A8                  | 1        | 0.33%   |
| AMD A6                  | 1        | 0.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 6      | 97       | 31.7%   |
| 4      | 76       | 24.84%  |
| 8      | 53       | 17.32%  |
| 2      | 27       | 8.82%   |
| 12     | 20       | 6.54%   |
| 16     | 17       | 5.56%   |
| 10     | 5        | 1.63%   |
| 3      | 4        | 1.31%   |
| 1      | 3        | 0.98%   |
| 24     | 2        | 0.65%   |
| 14     | 2        | 0.65%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 305      | 99.67%  |
| 2      | 1        | 0.33%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 243      | 79.15%  |
| 1      | 64       | 20.85%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 306      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 62       | 19.94%  |
| 0x08701021 | 29       | 9.32%   |
| 0x0a601203 | 20       | 6.43%   |
| 0x306c3    | 15       | 4.82%   |
| 0x0a201016 | 15       | 4.82%   |
| 0x0800820d | 13       | 4.18%   |
| 0x306a9    | 12       | 3.86%   |
| 0x0a50000d | 9        | 2.89%   |
| 0x0a20120a | 9        | 2.89%   |
| 0x06000822 | 8        | 2.57%   |
| 0x206a7    | 7        | 2.25%   |
| 0x906ea    | 6        | 1.93%   |
| 0x90672    | 6        | 1.93%   |
| 0x0a201205 | 6        | 1.93%   |
| 0xa0655    | 5        | 1.61%   |
| 0x906e9    | 5        | 1.61%   |
| 0x0a50000c | 5        | 1.61%   |
| 0x0a201204 | 5        | 1.61%   |
| 0xa0653    | 4        | 1.29%   |
| 0x906ed    | 4        | 1.29%   |
| 0x906ec    | 4        | 1.29%   |
| 0x506e3    | 4        | 1.29%   |
| 0x206d7    | 4        | 1.29%   |
| 0x08701013 | 4        | 1.29%   |
| 0x08108109 | 4        | 1.29%   |
| 0x08001138 | 4        | 1.29%   |
| 0x0800820b | 3        | 0.96%   |
| 0x06003106 | 3        | 0.96%   |
| 0x06001119 | 3        | 0.96%   |
| 0x010000bf | 3        | 0.96%   |
| 0xa0671    | 2        | 0.64%   |
| 0x1067a    | 2        | 0.64%   |
| 0x0a201025 | 2        | 0.64%   |
| 0x0a201009 | 2        | 0.64%   |
| 0x08701030 | 2        | 0.64%   |
| 0x00000000 | 2        | 0.64%   |
| 0x906eb    | 1        | 0.32%   |
| 0x406f1    | 1        | 0.32%   |
| 0x406c4    | 1        | 0.32%   |
| 0x40651    | 1        | 0.32%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 3            | 58       | 18.89%  |
| Zen 2            | 35       | 11.4%   |
| Haswell          | 27       | 8.79%   |
| KabyLake         | 25       | 8.14%   |
| Unknown          | 24       | 7.82%   |
| Zen+             | 22       | 7.17%   |
| IvyBridge        | 16       | 5.21%   |
| SandyBridge      | 15       | 4.89%   |
| Alderlake Hybrid | 15       | 4.89%   |
| CometLake        | 14       | 4.56%   |
| Piledriver       | 13       | 4.23%   |
| Skylake          | 10       | 3.26%   |
| Zen              | 6        | 1.95%   |
| K10              | 6        | 1.95%   |
| Icelake          | 5        | 1.63%   |
| Penryn           | 4        | 1.3%    |
| Steamroller      | 3        | 0.98%   |
| Broadwell        | 2        | 0.65%   |
| TigerLake        | 1        | 0.33%   |
| Silvermont       | 1        | 0.33%   |
| Nehalem          | 1        | 0.33%   |
| K8 Hammer        | 1        | 0.33%   |
| Excavator        | 1        | 0.33%   |
| Core             | 1        | 0.33%   |
| Bulldozer        | 1        | 0.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 156      | 45.75%  |
| Nvidia | 135      | 39.59%  |
| Intel  | 50       | 14.66%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 31       | 8.59%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 20       | 5.54%   |
| AMD Raphael                                                                 | 19       | 5.26%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 14       | 3.88%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 13       | 3.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 10       | 2.77%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 9        | 2.49%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX]                                    | 8        | 2.22%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 7        | 1.94%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 7        | 1.94%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 6        | 1.66%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 6        | 1.66%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 5        | 1.39%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 5        | 1.39%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 5        | 1.39%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 5        | 1.39%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 5        | 1.39%   |
| Intel AlderLake-S GT1                                                       | 5        | 1.39%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 4        | 1.11%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 4        | 1.11%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 4        | 1.11%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 4        | 1.11%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4        | 1.11%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 4        | 1.11%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4        | 1.11%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 4        | 1.11%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 4        | 1.11%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 3        | 0.83%   |
| Nvidia TU104 [GeForce RTX 2060]                                             | 3        | 0.83%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 3        | 0.83%   |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                              | 3        | 0.83%   |
| Nvidia AD102 [GeForce RTX 4090]                                             | 3        | 0.83%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                  | 3        | 0.83%   |
| Intel HD Graphics 530                                                       | 3        | 0.83%   |
| Intel DG2 [Arc A750]                                                        | 3        | 0.83%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 0.83%   |
| AMD Navi 23 [Radeon RX 6650 XT / 6700S / 6800S]                             | 3        | 0.83%   |
| AMD Navi 21 [Radeon RX 6950 XT]                                             | 3        | 0.83%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 3        | 0.83%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 3        | 0.83%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 125      | 40.72%  |
| 1 x Nvidia     | 119      | 38.76%  |
| 1 x Intel      | 29       | 9.45%   |
| 2 x AMD        | 15       | 4.89%   |
| AMD + Nvidia   | 10       | 3.26%   |
| 2 x Nvidia     | 3        | 0.98%   |
| Intel + Nvidia | 3        | 0.98%   |
| Intel + AMD    | 3        | 0.98%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 196      | 63.43%  |
| Proprietary | 105      | 33.98%  |
| Unknown     | 8        | 2.59%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 94       | 30.32%  |
| 7.01-8.0   | 72       | 23.23%  |
| 8.01-16.0  | 44       | 14.19%  |
| 3.01-4.0   | 28       | 9.03%   |
| 1.01-2.0   | 24       | 7.74%   |
| 0.01-0.5   | 14       | 4.52%   |
| 16.01-24.0 | 11       | 3.55%   |
| 0.51-1.0   | 11       | 3.55%   |
| 5.01-6.0   | 8        | 2.58%   |
| 2.01-3.0   | 4        | 1.29%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 63       | 17.36%  |
| Goldstar             | 45       | 12.4%   |
| Acer                 | 30       | 8.26%   |
| Dell                 | 28       | 7.71%   |
| Ancor Communications | 23       | 6.34%   |
| BenQ                 | 20       | 5.51%   |
| AOC                  | 18       | 4.96%   |
| Hewlett-Packard      | 17       | 4.68%   |
| ASUSTek Computer     | 16       | 4.41%   |
| MSI                  | 11       | 3.03%   |
| Vizio                | 9        | 2.48%   |
| ViewSonic            | 9        | 2.48%   |
| Gigabyte Technology  | 8        | 2.2%    |
| Sony                 | 7        | 1.93%   |
| Philips              | 6        | 1.65%   |
| Lenovo               | 6        | 1.65%   |
| Toshiba              | 4        | 1.1%    |
| Iiyama               | 4        | 1.1%    |
| Sceptre Tech         | 3        | 0.83%   |
| Unknown              | 2        | 0.55%   |
| NEC Computers        | 2        | 0.55%   |
| Insignia             | 2        | 0.55%   |
| Corsair              | 2        | 0.55%   |
| Yeyian               | 1        | 0.28%   |
| WIT                  | 1        | 0.28%   |
| Viotek               | 1        | 0.28%   |
| Valve                | 1        | 0.28%   |
| SNC                  | 1        | 0.28%   |
| Sharp                | 1        | 0.28%   |
| SFX                  | 1        | 0.28%   |
| PRI                  | 1        | 0.28%   |
| Pixio                | 1        | 0.28%   |
| Packard Bell         | 1        | 0.28%   |
| Olevia               | 1        | 0.28%   |
| OEM                  | 1        | 0.28%   |
| ODH                  | 1        | 0.28%   |
| NPC                  | 1        | 0.28%   |
| MStar                | 1        | 0.28%   |
| Impression           | 1        | 0.28%   |
| Huion                | 1        | 0.28%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch  | 6        | 1.55%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch         | 4        | 1.03%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 3        | 0.78%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 3        | 0.78%   |
| ASUSTek Computer PA278QV AUS2700 2560x1440 600x340mm 27.2-inch         | 3        | 0.78%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                    | 3        | 0.78%   |
| Acer GN246HL ACR02FA 1920x1080 531x299mm 24.0-inch                     | 3        | 0.78%   |
| Acer GN246HL ACR02F9 1920x1080 531x299mm 24.0-inch                     | 3        | 0.78%   |
| Vizio M50Q7-H1 VIZ1039 3840x2160 941x529mm 42.5-inch                   | 2        | 0.52%   |
| Vizio E500i-A1 VIZ1004 1920x1080 1095x616mm 49.5-inch                  | 2        | 0.52%   |
| ViewSonic XG2401 SERIES VSCBB31 1920x1080 531x299mm 24.0-inch          | 2        | 0.52%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 2        | 0.52%   |
| Toshiba TV TSB0108 1360x768 698x393mm 31.5-inch                        | 2        | 0.52%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch   | 2        | 0.52%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 1060x626mm 48.5-inch | 2        | 0.52%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 2        | 0.52%   |
| MSI Optix MAG27C MSI1462 1920x1080 598x336mm 27.0-inch                 | 2        | 0.52%   |
| MSI G27C5 MSI3CA9 1920x1080 598x336mm 27.0-inch                        | 2        | 0.52%   |
| Goldstar ULTRAGEAR GSM7766 2560x1440 697x392mm 31.5-inch               | 2        | 0.52%   |
| Goldstar ULTRAGEAR GSM5BD3 2560x1440 697x392mm 31.5-inch               | 2        | 0.52%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 2        | 0.52%   |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                    | 2        | 0.52%   |
| Goldstar QHD GSM772A 2560x1440 697x392mm 31.5-inch                     | 2        | 0.52%   |
| Goldstar 29EA93 GSM5974 2560x1080 677x290mm 29.0-inch                  | 2        | 0.52%   |
| Dell U2717D DEL40EB 2560x1440 597x336mm 27.0-inch                      | 2        | 0.52%   |
| Dell S2721DGF DEL41D9 2560x1440 597x336mm 27.0-inch                    | 2        | 0.52%   |
| Dell P2214H DELA097 1920x1080 477x268mm 21.5-inch                      | 2        | 0.52%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                      | 2        | 0.52%   |
| BenQ EW3270ZL BNQ7945 2560x1440 709x399mm 32.0-inch                    | 2        | 0.52%   |
| ASUSTek Computer VP28U AUS28B1 3840x2160 621x341mm 27.9-inch           | 2        | 0.52%   |
| ASUSTek Computer VP249 AUS24AF 1920x1080 530x300mm 24.0-inch           | 2        | 0.52%   |
| ASUSTek Computer VA27EHE AUS27D2 1920x1080 598x336mm 27.0-inch         | 2        | 0.52%   |
| ASUSTek Computer ROG XG27UQR AUS27BA 3840x2160 596x335mm 26.9-inch     | 2        | 0.52%   |
| AOC 27G2WG3 AOC2702 1920x1080 598x336mm 27.0-inch                      | 2        | 0.52%   |
| AOC 2243W AOC2243 1920x1080 477x268mm 21.5-inch                        | 2        | 0.52%   |
| Ancor Communications VX238 ACI23C1 1920x1080 510x290mm 23.1-inch       | 2        | 0.52%   |
| Ancor Communications ASUS PB278 ACI27A3 2560x1440 597x336mm 27.0-inch  | 2        | 0.52%   |
| Acer AL1916W ACRAD80 1440x900 410x257mm 19.1-inch                      | 2        | 0.52%   |
| Yeyian YMC-70102 YEY2700 1920x1080 698x393mm 31.5-inch                 | 1        | 0.26%   |
| WIT DVI WIT00FA 2560x1600 670x430mm 31.3-inch                          | 1        | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 138      | 39.09%  |
| 2560x1440 (QHD)    | 69       | 19.55%  |
| 3840x2160 (4K)     | 54       | 15.3%   |
| 3440x1440          | 14       | 3.97%   |
| 1680x1050 (WSXGA+) | 13       | 3.68%   |
| 2560x1080          | 9        | 2.55%   |
| 1440x900 (WXGA+)   | 8        | 2.27%   |
| 1360x768           | 7        | 1.98%   |
| 1280x1024 (SXGA)   | 7        | 1.98%   |
| 1600x900 (HD+)     | 6        | 1.7%    |
| 1366x768 (WXGA)    | 5        | 1.42%   |
| 1920x540           | 4        | 1.13%   |
| 1920x1200 (WUXGA)  | 4        | 1.13%   |
| 2560x1600          | 3        | 0.85%   |
| 3840x1600          | 2        | 0.57%   |
| 3840x1080          | 2        | 0.57%   |
| 2288x1287          | 2        | 0.57%   |
| Unknown            | 2        | 0.57%   |
| 5760x1080          | 1        | 0.28%   |
| 3840x2560          | 1        | 0.28%   |
| 2048x1152          | 1        | 0.28%   |
| 1600x1200          | 1        | 0.28%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 83       | 22.74%  |
| 24      | 37       | 10.14%  |
| 23      | 36       | 9.86%   |
| 31      | 34       | 9.32%   |
| 21      | 27       | 7.4%    |
| 34      | 17       | 4.66%   |
| 84      | 11       | 3.01%   |
| 22      | 9        | 2.47%   |
| 20      | 9        | 2.47%   |
| 19      | 9        | 2.47%   |
| Unknown | 9        | 2.47%   |
| 72      | 7        | 1.92%   |
| 18      | 7        | 1.92%   |
| 48      | 6        | 1.64%   |
| 29      | 6        | 1.64%   |
| 42      | 5        | 1.37%   |
| 32      | 5        | 1.37%   |
| 17      | 5        | 1.37%   |
| 26      | 4        | 1.1%    |
| 52      | 3        | 0.82%   |
| 49      | 3        | 0.82%   |
| 40      | 3        | 0.82%   |
| 33      | 3        | 0.82%   |
| 142     | 2        | 0.55%   |
| 69      | 2        | 0.55%   |
| 60      | 2        | 0.55%   |
| 38      | 2        | 0.55%   |
| 37      | 2        | 0.55%   |
| 35      | 2        | 0.55%   |
| 28      | 2        | 0.55%   |
| 25      | 2        | 0.55%   |
| 14      | 2        | 0.55%   |
| 85      | 1        | 0.27%   |
| 75      | 1        | 0.27%   |
| 58      | 1        | 0.27%   |
| 55      | 1        | 0.27%   |
| 54      | 1        | 0.27%   |
| 47      | 1        | 0.27%   |
| 46      | 1        | 0.27%   |
| 43      | 1        | 0.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 141      | 40.06%  |
| 401-500        | 61       | 17.33%  |
| 601-700        | 49       | 13.92%  |
| 701-800        | 24       | 6.82%   |
| 1501-2000      | 22       | 6.25%   |
| 1001-1500      | 19       | 5.4%    |
| 801-900        | 9        | 2.56%   |
| Unknown        | 9        | 2.56%   |
| 301-350        | 7        | 1.99%   |
| 901-1000       | 6        | 1.7%    |
| More than 2000 | 2        | 0.57%   |
| 351-400        | 2        | 0.57%   |
| 201-300        | 1        | 0.28%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 229      | 75.33%  |
| 16/10   | 28       | 9.21%   |
| 21/9    | 24       | 7.89%   |
| 5/4     | 7        | 2.3%    |
| 4/3     | 4        | 1.32%   |
| 32/9    | 3        | 0.99%   |
| 3/2     | 3        | 0.99%   |
| Unknown | 3        | 0.99%   |
| 1.00    | 2        | 0.66%   |
| 1.96    | 1        | 0.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 90       | 25.42%  |
| 301-350        | 89       | 25.14%  |
| 351-500        | 60       | 16.95%  |
| More than 1000 | 37       | 10.45%  |
| 151-200        | 29       | 8.19%   |
| 501-1000       | 19       | 5.37%   |
| 251-300        | 11       | 3.11%   |
| Unknown        | 9        | 2.54%   |
| 141-150        | 7        | 1.98%   |
| 81-90          | 1        | 0.28%   |
| 101-110        | 1        | 0.28%   |
| 91-100         | 1        | 0.28%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 186      | 55.52%  |
| 101-120 | 85       | 25.37%  |
| 1-50    | 29       | 8.66%   |
| 121-160 | 15       | 4.48%   |
| 161-240 | 11       | 3.28%   |
| Unknown | 9        | 2.69%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 206      | 66.45%  |
| 2     | 74       | 23.87%  |
| 3     | 17       | 5.48%   |
| 0     | 11       | 3.55%   |
| 4     | 2        | 0.65%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 190      | 41.13%  |
| Intel                           | 155      | 33.55%  |
| MediaTek                        | 23       | 4.98%   |
| TP-Link                         | 17       | 3.68%   |
| Qualcomm Atheros                | 17       | 3.68%   |
| Microsoft                       | 11       | 2.38%   |
| Broadcom                        | 10       | 2.16%   |
| Ralink Technology               | 6        | 1.3%    |
| Broadcom Limited                | 3        | 0.65%   |
| Xiaomi                          | 2        | 0.43%   |
| Ralink                          | 2        | 0.43%   |
| Qualcomm                        | 2        | 0.43%   |
| Oculus VR                       | 2        | 0.43%   |
| NetGear                         | 2        | 0.43%   |
| Aquantia                        | 2        | 0.43%   |
| ZTE WCDMA Technologies MSM      | 1        | 0.22%   |
| Wacom                           | 1        | 0.22%   |
| T & A Mobile Phones             | 1        | 0.22%   |
| Samsung Electronics             | 1        | 0.22%   |
| Qualcomm Atheros Communications | 1        | 0.22%   |
| Padix (Rockfire)                | 1        | 0.22%   |
| OPPO Electronics                | 1        | 0.22%   |
| Nvidia                          | 1        | 0.22%   |
| Motorola PCS                    | 1        | 0.22%   |
| Microchip Technology            | 1        | 0.22%   |
| Mellanox Technologies           | 1        | 0.22%   |
| Loupedeck                       | 1        | 0.22%   |
| Linksys                         | 1        | 0.22%   |
| ICS Advent                      | 1        | 0.22%   |
| Holtek Semiconductor            | 1        | 0.22%   |
| D-Link System                   | 1        | 0.22%   |
| D-Link                          | 1        | 0.22%   |
| ASUSTek Computer                | 1        | 0.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 138      | 25.6%   |
| Realtek RTL8125 2.5GbE Controller                                 | 48       | 8.91%   |
| Intel Wi-Fi 6 AX200                                               | 31       | 5.75%   |
| Intel Ethernet Controller I225-V                                  | 31       | 5.75%   |
| Intel I211 Gigabit Network Connection                             | 28       | 5.19%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 13       | 2.41%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 12       | 2.23%   |
| Intel Ethernet Connection (7) I219-V                              | 11       | 2.04%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 10       | 1.86%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 9        | 1.67%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 8        | 1.48%   |
| Intel Ethernet Connection (2) I219-V                              | 7        | 1.3%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 7        | 1.3%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7        | 1.3%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 6        | 1.11%   |
| Microsoft Wireless XBox Controller Dongle                         | 6        | 1.11%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 5        | 0.93%   |
| Intel Wireless-AC 9260                                            | 5        | 0.93%   |
| Intel Ethernet Connection (2) I218-V                              | 5        | 0.93%   |
| Intel 82579V Gigabit Network Connection                           | 5        | 0.93%   |
| TP-Link 802.11ac NIC                                              | 4        | 0.74%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 4        | 0.74%   |
| Microsoft Xbox 360 Wireless Adapter                               | 4        | 0.74%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4        | 0.74%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 3        | 0.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3        | 0.56%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 3        | 0.56%   |
| Realtek 802.11ac NIC                                              | 3        | 0.56%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3        | 0.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3        | 0.56%   |
| Intel Wireless 7265                                               | 3        | 0.56%   |
| Intel Ethernet Connection I217-V                                  | 3        | 0.56%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 0.56%   |
| Intel Ethernet Connection (14) I219-V                             | 3        | 0.56%   |
| Intel Ethernet Connection (12) I219-V                             | 3        | 0.56%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 0.37%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2        | 0.37%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 2        | 0.37%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 2        | 0.37%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 2        | 0.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 84       | 42.86%  |
| Realtek Semiconductor           | 29       | 14.8%   |
| MediaTek                        | 23       | 11.73%  |
| TP-Link                         | 17       | 8.67%   |
| Microsoft                       | 11       | 5.61%   |
| Broadcom                        | 9        | 4.59%   |
| Ralink Technology               | 6        | 3.06%   |
| Qualcomm Atheros                | 5        | 2.55%   |
| Ralink                          | 2        | 1.02%   |
| NetGear                         | 2        | 1.02%   |
| Broadcom Limited                | 2        | 1.02%   |
| Wacom                           | 1        | 0.51%   |
| Qualcomm Atheros Communications | 1        | 0.51%   |
| Linksys                         | 1        | 0.51%   |
| D-Link System                   | 1        | 0.51%   |
| D-Link                          | 1        | 0.51%   |
| ASUSTek Computer                | 1        | 0.51%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                           | 31       | 15.74%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 13       | 6.6%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 12       | 6.09%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 10       | 5.08%   |
| Intel Alder Lake-S PCH CNVi WiFi                              | 9        | 4.57%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter            | 8        | 4.06%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 7        | 3.55%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 6        | 3.05%   |
| Microsoft Wireless XBox Controller Dongle                     | 6        | 3.05%   |
| Intel Wireless-AC 9260                                        | 5        | 2.54%   |
| TP-Link 802.11ac NIC                                          | 4        | 2.03%   |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 4        | 2.03%   |
| Microsoft Xbox 360 Wireless Adapter                           | 4        | 2.03%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 4        | 2.03%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                   | 3        | 1.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 3        | 1.52%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter      | 3        | 1.52%   |
| Realtek 802.11ac NIC                                          | 3        | 1.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 3        | 1.52%   |
| Intel Wireless 7265                                           | 3        | 1.52%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                  | 2        | 1.02%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                        | 2        | 1.02%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                           | 2        | 1.02%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter               | 2        | 1.02%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter               | 2        | 1.02%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter         | 2        | 1.02%   |
| Ralink RT5370 Wireless Adapter                                | 2        | 1.02%   |
| Intel Wireless 8265 / 8275                                    | 2        | 1.02%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 2        | 1.02%   |
| Intel 700 Series Chipset Family Wi-Fi                         | 2        | 1.02%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                      | 1        | 0.51%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                         | 1        | 0.51%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                    | 1        | 0.51%   |
| TP-Link Archer T4U ver.3                                      | 1        | 0.51%   |
| TP-Link 802.11n NIC                                           | 1        | 0.51%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter      | 1        | 0.51%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter           | 1        | 0.51%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter       | 1        | 0.51%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                        | 1        | 0.51%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller     | 1        | 0.51%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Realtek Semiconductor      | 182      | 55.83%  |
| Intel                      | 115      | 35.28%  |
| Qualcomm Atheros           | 12       | 3.68%   |
| Xiaomi                     | 2        | 0.61%   |
| Qualcomm                   | 2        | 0.61%   |
| Aquantia                   | 2        | 0.61%   |
| ZTE WCDMA Technologies MSM | 1        | 0.31%   |
| T & A Mobile Phones        | 1        | 0.31%   |
| Samsung Electronics        | 1        | 0.31%   |
| OPPO Electronics           | 1        | 0.31%   |
| Nvidia                     | 1        | 0.31%   |
| Motorola PCS               | 1        | 0.31%   |
| Mellanox Technologies      | 1        | 0.31%   |
| MediaTek                   | 1        | 0.31%   |
| ICS Advent                 | 1        | 0.31%   |
| Broadcom Limited           | 1        | 0.31%   |
| Broadcom                   | 1        | 0.31%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 138      | 41.07%  |
| Realtek RTL8125 2.5GbE Controller                                 | 48       | 14.29%  |
| Intel Ethernet Controller I225-V                                  | 31       | 9.23%   |
| Intel I211 Gigabit Network Connection                             | 28       | 8.33%   |
| Intel Ethernet Connection (7) I219-V                              | 11       | 3.27%   |
| Intel Ethernet Connection (2) I219-V                              | 7        | 2.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7        | 2.08%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 5        | 1.49%   |
| Intel Ethernet Connection (2) I218-V                              | 5        | 1.49%   |
| Intel 82579V Gigabit Network Connection                           | 5        | 1.49%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3        | 0.89%   |
| Intel Ethernet Connection I217-V                                  | 3        | 0.89%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 0.89%   |
| Intel Ethernet Connection (14) I219-V                             | 3        | 0.89%   |
| Intel Ethernet Connection (12) I219-V                             | 3        | 0.89%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 0.6%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 0.6%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 0.6%    |
| Intel I210 Gigabit Network Connection                             | 2        | 0.6%    |
| Intel Ethernet Connection (17) I219-V                             | 2        | 0.6%    |
| Intel Ethernet Connection (11) I219-V                             | 2        | 0.6%    |
| ZTE WCDMA MSM Unisoc Phone                                        | 1        | 0.3%    |
| T & A Mobile Phones Alcatel 1                                     | 1        | 0.3%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.3%    |
| Realtek RTL8150 Fast Ethernet Adapter                             | 1        | 0.3%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.3%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.3%    |
| Qualcomm Android                                                  | 1        | 0.3%    |
| Qualcomm A0001                                                    | 1        | 0.3%    |
| OPPO OnePlus Nord                                                 | 1        | 0.3%    |
| Nvidia MCP61 Ethernet                                             | 1        | 0.3%    |
| Motorola PCS motorola edge 20 lite                                | 1        | 0.3%    |
| Mellanox MT27500 Family [ConnectX-3]                              | 1        | 0.3%    |
| MediaTek moto g22                                                 | 1        | 0.3%    |
| Intel Ethernet Controller I226-V                                  | 1        | 0.3%    |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 1        | 0.3%    |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.3%    |
| Intel Ethernet Connection (3) I218-LM                             | 1        | 0.3%    |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 0.3%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 0.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 303      | 62.09%  |
| WiFi     | 179      | 36.68%  |
| Modem    | 4        | 0.82%   |
| Unknown  | 2        | 0.41%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 238      | 73.91%  |
| WiFi     | 84       | 26.09%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 163      | 53.09%  |
| 2     | 127      | 41.37%  |
| 3     | 13       | 4.23%   |
| 0     | 2        | 0.65%   |
| 6     | 1        | 0.33%   |
| 4     | 1        | 0.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 196      | 63.64%  |
| Yes  | 112      | 36.36%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 80       | 46.78%  |
| Cambridge Silicon Radio         | 32       | 18.71%  |
| MediaTek                        | 16       | 9.36%   |
| Realtek Semiconductor           | 7        | 4.09%   |
| TP-Link                         | 6        | 3.51%   |
| Broadcom                        | 6        | 3.51%   |
| ASUSTek Computer                | 6        | 3.51%   |
| Qualcomm Atheros Communications | 4        | 2.34%   |
| Foxconn / Hon Hai               | 4        | 2.34%   |
| IMC Networks                    | 2        | 1.17%   |
| Edimax Technology               | 2        | 1.17%   |
| Actions                         | 2        | 1.17%   |
| Integrated System Solution      | 1        | 0.58%   |
| Dynex                           | 1        | 0.58%   |
| Dell                            | 1        | 0.58%   |
| Unknown                         | 1        | 0.58%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 32       | 18.71%  |
| Intel AX200 Bluetooth                                    | 31       | 18.13%  |
| MediaTek Wireless_Device                                 | 16       | 9.36%   |
| Intel Bluetooth Device                                   | 12       | 7.02%   |
| Intel AX210 Bluetooth                                    | 12       | 7.02%   |
| Intel Bluetooth wireless interface                       | 8        | 4.68%   |
| TP-Link UB5A Adapter                                     | 6        | 3.51%   |
| Realtek Bluetooth Radio                                  | 6        | 3.51%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 6        | 3.51%   |
| Intel AX201 Bluetooth                                    | 6        | 3.51%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 4        | 2.34%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 4        | 2.34%   |
| ASUS ASUS USB-BT500                                      | 4        | 2.34%   |
| Qualcomm Atheros Bluetooth USB Host Controller           | 3        | 1.75%   |
| Foxconn / Hon Hai Wireless_Device                        | 3        | 1.75%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter  | 2        | 1.17%   |
| Actions general adapter                                  | 2        | 1.17%   |
| Realtek  Bluetooth 4.2 Adapter                           | 1        | 0.58%   |
| Qualcomm Atheros AR3011 Bluetooth                        | 1        | 0.58%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 1        | 0.58%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter    | 1        | 0.58%   |
| IMC Networks Wireless_Device                             | 1        | 0.58%   |
| IMC Networks Bluetooth Radio                             | 1        | 0.58%   |
| Foxconn / Hon Hai Bluetooth Device                       | 1        | 0.58%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 1        | 0.58%   |
| Dell Broadcom BCM20702A0 Bluetooth                       | 1        | 0.58%   |
| Broadcom Bluetooth Device                                | 1        | 0.58%   |
| Broadcom BCM2045 Bluetooth                               | 1        | 0.58%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 1        | 0.58%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE    | 1        | 0.58%   |
| Unknown                                                  | 1        | 0.58%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| AMD                        | 210      | 32.76%  |
| Intel                      | 135      | 21.06%  |
| Nvidia                     | 134      | 20.9%   |
| C-Media Electronics        | 24       | 3.74%   |
| Logitech                   | 21       | 3.28%   |
| ASUSTek Computer           | 11       | 1.72%   |
| Kingston Technology        | 10       | 1.56%   |
| Razer USA                  | 9        | 1.4%    |
| SteelSeries ApS            | 7        | 1.09%   |
| Creative Labs              | 6        | 0.94%   |
| Texas Instruments          | 5        | 0.78%   |
| Samson Technologies        | 5        | 0.78%   |
| Realtek Semiconductor      | 4        | 0.62%   |
| Plantronics                | 4        | 0.62%   |
| Micro Star International   | 4        | 0.62%   |
| JMTek                      | 4        | 0.62%   |
| Creative Technology        | 4        | 0.62%   |
| Focusrite-Novation         | 3        | 0.47%   |
| Corsair                    | 3        | 0.47%   |
| Blue Microphones           | 3        | 0.47%   |
| Audio-Technica             | 3        | 0.47%   |
| SAVITECH                   | 2        | 0.31%   |
| PreSonus Audio Electronics | 2        | 0.31%   |
| Asahi Kasei Microsystems   | 2        | 0.31%   |
| Unknown                    | 2        | 0.31%   |
| VIA Technologies           | 1        | 0.16%   |
| Turtle Beach               | 1        | 0.16%   |
| Trust                      | 1        | 0.16%   |
| Tenx Technology            | 1        | 0.16%   |
| Sony                       | 1        | 0.16%   |
| ROCCAT                     | 1        | 0.16%   |
| Positive Grid              | 1        | 0.16%   |
| Ploopy                     | 1        | 0.16%   |
| Native Instruments         | 1        | 0.16%   |
| Nam Tai E&E Products       | 1        | 0.16%   |
| MCS                        | 1        | 0.16%   |
| Mark of the Unicorn        | 1        | 0.16%   |
| Lautsprecher Teufel        | 1        | 0.16%   |
| Hewlett-Packard            | 1        | 0.16%   |
| GN Netcom                  | 1        | 0.16%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 73       | 9.43%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 56       | 7.24%   |
| AMD Family 17h/19h HD Audio Controller                                     | 35       | 4.52%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 33       | 4.26%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 22       | 2.84%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 20       | 2.58%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 18       | 2.33%   |
| Nvidia GA104 High Definition Audio Controller                              | 17       | 2.2%    |
| Nvidia GP104 High Definition Audio Controller                              | 15       | 1.94%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 15       | 1.94%   |
| Intel Cannon Lake PCH cAVS                                                 | 14       | 1.81%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 14       | 1.81%   |
| Intel Alder Lake-S HD Audio Controller                                     | 13       | 1.68%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 13       | 1.68%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 13       | 1.68%   |
| Nvidia GA102 High Definition Audio Controller                              | 12       | 1.55%   |
| Nvidia TU106 High Definition Audio Controller                              | 11       | 1.42%   |
| ASUSTek Computer USB Audio                                                 | 11       | 1.42%   |
| AMD Navi 10 HDMI Audio                                                     | 11       | 1.42%   |
| Nvidia TU116 High Definition Audio Controller                              | 10       | 1.29%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 10       | 1.29%   |
| Intel 200 Series PCH HD Audio                                              | 10       | 1.29%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 10       | 1.29%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 10       | 1.29%   |
| Nvidia TU104 HD Audio Controller                                           | 9        | 1.16%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 8        | 1.03%   |
| Nvidia GA106 High Definition Audio Controller                              | 7        | 0.9%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 7        | 0.9%    |
| AMD FCH Azalia Controller                                                  | 7        | 0.9%    |
| Nvidia GP107GL High Definition Audio Controller                            | 6        | 0.78%   |
| Nvidia GP106 High Definition Audio Controller                              | 6        | 0.78%   |
| Logitech PRO X Wireless Gaming Headset                                     | 6        | 0.78%   |
| Intel Comet Lake PCH-V cAVS                                                | 6        | 0.78%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 6        | 0.78%   |
| Nvidia GM204 High Definition Audio Controller                              | 5        | 0.65%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 5        | 0.65%   |
| C-Media Electronics KLIM Mantis Audio 7.1                                  | 5        | 0.65%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5        | 0.65%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4        | 0.52%   |
| Nvidia GM206 High Definition Audio Controller                              | 4        | 0.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 14       | 20.9%   |
| G.Skill             | 12       | 17.91%  |
| Kingston            | 11       | 16.42%  |
| Samsung Electronics | 6        | 8.96%   |
| Crucial             | 6        | 8.96%   |
| Unknown             | 5        | 7.46%   |
| Team                | 5        | 7.46%   |
| SK hynix            | 2        | 2.99%   |
| A-DATA Technology   | 2        | 2.99%   |
| Ramaxel Technology  | 1        | 1.49%   |
| Micron Technology   | 1        | 1.49%   |
| Hewlett-Packard     | 1        | 1.49%   |
| Asgard              | 1        | 1.49%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s               | 2        | 2.78%   |
| Kingston RAM KHX3200C16D4/8GX 8192MB DIMM DDR4 3600MT/s | 2        | 2.78%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s       | 2        | 2.78%   |
| G.Skill RAM F4-3600C16-8GTZNC 8GB DIMM DDR4 3800MT/s    | 2        | 2.78%   |
| G.Skill RAM F4-3200C16-8GVKB 8192MB DIMM DDR4 3866MT/s  | 2        | 2.78%   |
| G.Skill RAM F4-3200C16-16GVK 16384MB DIMM DDR4 3600MT/s | 2        | 2.78%   |
| Corsair RAM CMY16GX3M2A1866C9 8GB DIMM DDR3 2400MT/s    | 2        | 2.78%   |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3733MT/s   | 2        | 2.78%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s   | 2        | 2.78%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s               | 1        | 1.39%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                    | 1        | 1.39%   |
| Unknown RAM 2400 C15 Series 16384MB DIMM DDR4 2133MT/s  | 1        | 1.39%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s      | 1        | 1.39%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3733MT/s     | 1        | 1.39%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s      | 1        | 1.39%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s      | 1        | 1.39%   |
| Team RAM TEAMGROUP-UD3 8192MB DIMM DDR3 1600MT/s        | 1        | 1.39%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s              | 1        | 1.39%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB DIMM DDR3 1600MT/s    | 1        | 1.39%   |
| Samsung RAM Module 2GB Row Of Chips LPDDR4 4267MT/s     | 1        | 1.39%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s               | 1        | 1.39%   |
| Samsung RAM M471B5674EB0-YK0 2GB SODIMM DDR3 1600MT/s   | 1        | 1.39%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s   | 1        | 1.39%   |
| Samsung RAM M392B2G70BM0 16GB DIMM DDR3 1333MT/s        | 1        | 1.39%   |
| Samsung RAM M392B2G70AM0 16GB DIMM DDR3 1333MT/s        | 1        | 1.39%   |
| Samsung RAM M378A1K43CB2-CTD 8192MB DIMM DDR4 3266MT/s  | 1        | 1.39%   |
| Samsung RAM M3 78T2863QZS-CF7 1024MB DIMM DDR2 800MT/s  | 1        | 1.39%   |
| Ramaxel RAM RMR5030ED58E8W1600 2GB DIMM DDR3 1600MT/s   | 1        | 1.39%   |
| Micron RAM Module 2GB DIMM DDR3 1333MT/s                | 1        | 1.39%   |
| Kingston RAM KHX2933C15D4/8GX 8GB DIMM DDR4 2933MT/s    | 1        | 1.39%   |
| Kingston RAM KHX2400C15/16G 16GB DIMM DDR4 3334MT/s     | 1        | 1.39%   |
| Kingston RAM KF560C32-16 16GB DIMM DDR5 6000MT/s        | 1        | 1.39%   |
| Kingston RAM KF552C40-16 16GB DIMM DDR5 5200MT/s        | 1        | 1.39%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3933MT/s   | 1        | 1.39%   |
| Kingston RAM CL16-18-18 D4-3200 16GB DIMM DDR4 3200MT/s | 1        | 1.39%   |
| Kingston RAM 9965525-111.A00LF 8GB DIMM DDR3 1600MT/s   | 1        | 1.39%   |
| HP RAM 7EH52AA#ABB 8GB DIMM DDR4 2400MT/s               | 1        | 1.39%   |
| G.Skill RAM F5-5600J3636D32G 32GB DIMM 6000MT/s         | 1        | 1.39%   |
| G.Skill RAM F5-5600J2834F16G 16GB DIMM DDR5 4800MT/s    | 1        | 1.39%   |
| G.Skill RAM F4-3600C14-8GTZNB 8GB DIMM DDR4 3600MT/s    | 1        | 1.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 40       | 65.57%  |
| DDR3    | 13       | 21.31%  |
| DDR5    | 5        | 8.2%    |
| SDRAM   | 1        | 1.64%   |
| LPDDR4  | 1        | 1.64%   |
| Unknown | 1        | 1.64%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 59       | 96.72%  |
| SODIMM       | 1        | 1.64%   |
| Row Of Chips | 1        | 1.64%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 26       | 41.27%  |
| 16384 | 19       | 30.16%  |
| 32768 | 8        | 12.7%   |
| 2048  | 5        | 7.94%   |
| 4096  | 4        | 6.35%   |
| 1024  | 1        | 1.59%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 10       | 15.15%  |
| 3600  | 9        | 13.64%  |
| 1600  | 8        | 12.12%  |
| 3733  | 4        | 6.06%   |
| 2400  | 4        | 6.06%   |
| 3800  | 3        | 4.55%   |
| 1333  | 3        | 4.55%   |
| 6000  | 2        | 3.03%   |
| 3866  | 2        | 3.03%   |
| 3466  | 2        | 3.03%   |
| 2933  | 2        | 3.03%   |
| 1066  | 2        | 3.03%   |
| 5600  | 1        | 1.52%   |
| 5200  | 1        | 1.52%   |
| 4800  | 1        | 1.52%   |
| 4267  | 1        | 1.52%   |
| 3933  | 1        | 1.52%   |
| 3534  | 1        | 1.52%   |
| 3533  | 1        | 1.52%   |
| 3400  | 1        | 1.52%   |
| 3334  | 1        | 1.52%   |
| 3266  | 1        | 1.52%   |
| 3100  | 1        | 1.52%   |
| 3000  | 1        | 1.52%   |
| 2800  | 1        | 1.52%   |
| 2667  | 1        | 1.52%   |
| 800   | 1        | 1.52%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Canon              | 3        | 33.33%  |
| Brother Industries | 3        | 33.33%  |
| STMicroelectronics | 1        | 11.11%  |
| Hewlett-Packard    | 1        | 11.11%  |
| Dell               | 1        | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1        | 11.11%  |
| HP DeskJet Plus 4100 series                               | 1        | 11.11%  |
| Dell 1130 Laser Printer                                   | 1        | 11.11%  |
| Canon TS700 series                                        | 1        | 11.11%  |
| Canon TR4500 series                                       | 1        | 11.11%  |
| Canon PIXMA MX370 Series                                  | 1        | 11.11%  |
| Brother MFC-L2710DN series                                | 1        | 11.11%  |
| Brother HL-L2370DW series                                 | 1        | 11.11%  |
| Brother DCP-1510                                          | 1        | 11.11%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 1        | 50%     |
| Canon           | 1        | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| HP ScanJet 2400c              | 1        | 50%     |
| Canon CanoScan N1240U/LiDE 30 | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 20       | 31.25%  |
| Microsoft                     | 7        | 10.94%  |
| Apple                         | 7        | 10.94%  |
| Microdia                      | 5        | 7.81%   |
| Sunplus Innovation Technology | 3        | 4.69%   |
| ARC International             | 3        | 4.69%   |
| MacroSilicon                  | 2        | 3.13%   |
| Hewlett-Packard               | 2        | 3.13%   |
| Chicony Electronics           | 2        | 3.13%   |
| WCM_USB                       | 1        | 1.56%   |
| SunplusIT                     | 1        | 1.56%   |
| Samsung Electronics           | 1        | 1.56%   |
| Owon                          | 1        | 1.56%   |
| lihappe8                      | 1        | 1.56%   |
| Lenovo                        | 1        | 1.56%   |
| KYE Systems (Mouse Systems)   | 1        | 1.56%   |
| Generalplus Technology        | 1        | 1.56%   |
| Fifine K420                   | 1        | 1.56%   |
| EVGA                          | 1        | 1.56%   |
| Cubeternet                    | 1        | 1.56%   |
| ANYKA                         | 1        | 1.56%   |
| 2M UVC CAMERA                 | 1        | 1.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 7        | 10.94%  |
| Logitech C922 Pro Stream Webcam                     | 6        | 9.38%   |
| Logitech HD Pro Webcam C920                         | 5        | 7.81%   |
| Logitech Webcam C270                                | 4        | 6.25%   |
| Logitech StreamCam                                  | 3        | 4.69%   |
| ARC International Camera                            | 3        | 4.69%   |
| Sunplus Canyon CNS-CWC5 Webcam                      | 2        | 3.13%   |
| Microsoft LifeCam Cinema                            | 2        | 3.13%   |
| Microdia Integrated Camera                          | 2        | 3.13%   |
| MacroSilicon USB Video                              | 2        | 3.13%   |
| WCM_USB WEB CAM                                     | 1        | 1.56%   |
| SunplusIT Umax Webcam W5                            | 1        | 1.56%   |
| Sunplus Sandberg USB Webcam Pro                     | 1        | 1.56%   |
| Samsung Galaxy series, misc. (MTP mode)             | 1        | 1.56%   |
| Owon USB CAMERA                                     | 1        | 1.56%   |
| Microsoft Xbox NUI Camera                           | 1        | 1.56%   |
| Microsoft MicrosoftÂ LifeCam HD-6000 for Notebooks | 1        | 1.56%   |
| Microsoft LifeCam VX-800                            | 1        | 1.56%   |
| Microsoft LifeCam Studio                            | 1        | 1.56%   |
| Microsoft LifeCam HD-3000                           | 1        | 1.56%   |
| Microdia Webcam Vitade AF                           | 1        | 1.56%   |
| Microdia USB Live camera                            | 1        | 1.56%   |
| Microdia GC02M2                                     | 1        | 1.56%   |
| Logitech QuickCam Pro 9000                          | 1        | 1.56%   |
| Logitech BRIO 4K Stream Edition                     | 1        | 1.56%   |
| lihappe8 USB 2.0 Camera                             | 1        | 1.56%   |
| Lenovo 500 RGB Camera                               | 1        | 1.56%   |
| KYE Systems (Mouse Systems) Genius Webcam           | 1        | 1.56%   |
| HP Webcam HD-2200                                   | 1        | 1.56%   |
| HP Webcam HD 2300                                   | 1        | 1.56%   |
| Generalplus 808 Camera                              | 1        | 1.56%   |
| Fifine K420 Fifine K420                             | 1        | 1.56%   |
| EVGA XR1 Capture Box                                | 1        | 1.56%   |
| Cubeternet eEver USB Device                         | 1        | 1.56%   |
| Chicony HP Webcam 2100                              | 1        | 1.56%   |
| Chicony CNFA035                                     | 1        | 1.56%   |
| ANYKA V380 FHD Camera                               | 1        | 1.56%   |
| 2M UVC CAMERA Web Camera                            | 1        | 1.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Realtek Semiconductor Smart Card Reader Interface | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 259      | 83.55%  |
| 1     | 47       | 15.16%  |
| 2     | 4        | 1.29%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 26       | 48.15%  |
| Graphics card            | 20       | 37.04%  |
| Multimedia controller    | 3        | 5.56%   |
| Unassigned class         | 2        | 3.7%    |
| Sound                    | 1        | 1.85%   |
| Communication controller | 1        | 1.85%   |
| Camera                   | 1        | 1.85%   |

