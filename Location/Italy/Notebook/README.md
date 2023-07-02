Linux in Italy - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in Italy.

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

Total: 6178

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Aspire V5-123               | [8507833f22](https://linux-hardware.org/?probe=8507833f22) | Jul 01, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [39a8ee4269](https://linux-hardware.org/?probe=39a8ee4269) | Jun 30, 2023 |
| Dell          | Vostro 2520                 | [48d04d8282](https://linux-hardware.org/?probe=48d04d8282) | Jun 30, 2023 |
| Dell          | Latitude 5521               | [3a8f3794aa](https://linux-hardware.org/?probe=3a8f3794aa) | Jun 29, 2023 |
| HP            | Pavilion dv6                | [b6c2bcb025](https://linux-hardware.org/?probe=b6c2bcb025) | Jun 29, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [b52c0ac96a](https://linux-hardware.org/?probe=b52c0ac96a) | Jun 29, 2023 |
| HP            | Stream Laptop 14-cb1XX      | [1db11a4fa9](https://linux-hardware.org/?probe=1db11a4fa9) | Jun 29, 2023 |
| Acer          | Aspire 5750G                | [3c4acbf380](https://linux-hardware.org/?probe=3c4acbf380) | Jun 28, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [7017964456](https://linux-hardware.org/?probe=7017964456) | Jun 28, 2023 |
| Acer          | Aspire 5738                 | [b4fcb0d0c0](https://linux-hardware.org/?probe=b4fcb0d0c0) | Jun 28, 2023 |
| Acer          | Aspire 5750G                | [8ae62960d8](https://linux-hardware.org/?probe=8ae62960d8) | Jun 28, 2023 |
| Dell          | Latitude 7440               | [24f85667ac](https://linux-hardware.org/?probe=24f85667ac) | Jun 28, 2023 |
| Acer          | Aspire A315-21              | [4bf524cd80](https://linux-hardware.org/?probe=4bf524cd80) | Jun 27, 2023 |
| Lenovo        | ThinkPad SL 2746EDG         | [7f0ae1c657](https://linux-hardware.org/?probe=7f0ae1c657) | Jun 27, 2023 |
| Dell          | XPS 15 9500                 | [8ea6d92813](https://linux-hardware.org/?probe=8ea6d92813) | Jun 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [24d66c058b](https://linux-hardware.org/?probe=24d66c058b) | Jun 27, 2023 |
| HP            | ENVY 15                     | [0d46d829d2](https://linux-hardware.org/?probe=0d46d829d2) | Jun 27, 2023 |
| HP            | ENVY 15                     | [189cf01c37](https://linux-hardware.org/?probe=189cf01c37) | Jun 27, 2023 |
| Lenovo        | ThinkPad T480 20L6S5LF00    | [5a062be874](https://linux-hardware.org/?probe=5a062be874) | Jun 26, 2023 |
| HP            | Pavilion dv6                | [fe7974bbc9](https://linux-hardware.org/?probe=fe7974bbc9) | Jun 26, 2023 |
| HP            | Pavilion dv6                | [3051c4ac4e](https://linux-hardware.org/?probe=3051c4ac4e) | Jun 26, 2023 |
| Acer          | Aspire V3-772               | [12cc9ac9dc](https://linux-hardware.org/?probe=12cc9ac9dc) | Jun 25, 2023 |
| Acer          | Aspire 5600                 | [82fd23bd36](https://linux-hardware.org/?probe=82fd23bd36) | Jun 25, 2023 |
| Google        | Sasuke                      | [d2b46a08a3](https://linux-hardware.org/?probe=d2b46a08a3) | Jun 25, 2023 |
| Toshiba       | Satellite A300              | [6f1d7a6089](https://linux-hardware.org/?probe=6f1d7a6089) | Jun 25, 2023 |
| Lenovo        | ThinkPad E560 20EV000UIX    | [ac6bd9497a](https://linux-hardware.org/?probe=ac6bd9497a) | Jun 25, 2023 |
| MSI           | GL73 8RE                    | [0b8ee3c470](https://linux-hardware.org/?probe=0b8ee3c470) | Jun 25, 2023 |
| HUAWEI        | BOD-WXX9                    | [aa75d0dace](https://linux-hardware.org/?probe=aa75d0dace) | Jun 25, 2023 |
| Acer          | Aspire 5738                 | [8112b061f0](https://linux-hardware.org/?probe=8112b061f0) | Jun 24, 2023 |
| Microtech     | CoreBook Lite               | [1840bef280](https://linux-hardware.org/?probe=1840bef280) | Jun 24, 2023 |
| Packard Be... | EasyNote TJ65               | [cdc135487b](https://linux-hardware.org/?probe=cdc135487b) | Jun 24, 2023 |
| HP            | Presario CQ56               | [5a8991a97b](https://linux-hardware.org/?probe=5a8991a97b) | Jun 23, 2023 |
| HP            | Laptop 15-da0xxx            | [f8d0ce645a](https://linux-hardware.org/?probe=f8d0ce645a) | Jun 23, 2023 |
| HP            | ENVY 15                     | [3918cca1e5](https://linux-hardware.org/?probe=3918cca1e5) | Jun 23, 2023 |
| HP            | Pavilion g6                 | [fa58c1a1fd](https://linux-hardware.org/?probe=fa58c1a1fd) | Jun 22, 2023 |
| Acer          | Aspire 7720G                | [a8e44a5ab1](https://linux-hardware.org/?probe=a8e44a5ab1) | Jun 22, 2023 |
| HP            | Pavilion g6                 | [a58868d782](https://linux-hardware.org/?probe=a58868d782) | Jun 22, 2023 |
| HUAWEI        | BOD-WXX9                    | [83d89a8751](https://linux-hardware.org/?probe=83d89a8751) | Jun 22, 2023 |
| HP            | Pavilion Laptop 14-ce2xx... | [419687b31f](https://linux-hardware.org/?probe=419687b31f) | Jun 22, 2023 |
| Dell          | Vostro 3700                 | [6e4fe4f0c8](https://linux-hardware.org/?probe=6e4fe4f0c8) | Jun 22, 2023 |
| ASUSTek       | K55VD                       | [223967ea1d](https://linux-hardware.org/?probe=223967ea1d) | Jun 22, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [44050251e9](https://linux-hardware.org/?probe=44050251e9) | Jun 22, 2023 |
| Sony          | VGN-NS21M_W                 | [6813d6589e](https://linux-hardware.org/?probe=6813d6589e) | Jun 21, 2023 |
| HP            | EliteBook 820 G2            | [d4f506e331](https://linux-hardware.org/?probe=d4f506e331) | Jun 21, 2023 |
| ASUSTek       | K55VD                       | [49f6cc6986](https://linux-hardware.org/?probe=49f6cc6986) | Jun 20, 2023 |
| Lenovo        | ThinkPad SL 2746EDG         | [42ba3d75e5](https://linux-hardware.org/?probe=42ba3d75e5) | Jun 20, 2023 |
| HP            | OMEN by Laptop 15-dh0xxx    | [6e2f7d8295](https://linux-hardware.org/?probe=6e2f7d8295) | Jun 20, 2023 |
| Samsung       | RC420/RC520/RC720           | [406b650f19](https://linux-hardware.org/?probe=406b650f19) | Jun 19, 2023 |
| MSI           | PS63 Modern 8RC             | [f540e88555](https://linux-hardware.org/?probe=f540e88555) | Jun 18, 2023 |
| Dell          | Latitude 5520               | [09da4ee3c4](https://linux-hardware.org/?probe=09da4ee3c4) | Jun 18, 2023 |
| Dell          | Latitude 5520               | [5e70c1929c](https://linux-hardware.org/?probe=5e70c1929c) | Jun 18, 2023 |
| Acer          | Aspire 5600                 | [af924230a1](https://linux-hardware.org/?probe=af924230a1) | Jun 18, 2023 |
| HP            | EliteBook 2530p             | [7d246caf6f](https://linux-hardware.org/?probe=7d246caf6f) | Jun 18, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [46692b99cb](https://linux-hardware.org/?probe=46692b99cb) | Jun 18, 2023 |
| Acer          | Aspire 5738                 | [8247e349fc](https://linux-hardware.org/?probe=8247e349fc) | Jun 17, 2023 |
| Sony          | SVE1713X1EB                 | [8b346f7874](https://linux-hardware.org/?probe=8b346f7874) | Jun 17, 2023 |
| HUAWEI        | MACH-WX9                    | [4a86028eb3](https://linux-hardware.org/?probe=4a86028eb3) | Jun 17, 2023 |
| HP            | ENVY 15                     | [10a4cb8865](https://linux-hardware.org/?probe=10a4cb8865) | Jun 17, 2023 |
| Dell          | Vostro 3700                 | [dae8f5a0b4](https://linux-hardware.org/?probe=dae8f5a0b4) | Jun 15, 2023 |
| HP            | Laptop 15s-fq0xxx           | [bbc15bef9c](https://linux-hardware.org/?probe=bbc15bef9c) | Jun 15, 2023 |
| Acer          | Aspire 1810T                | [1b1d11f461](https://linux-hardware.org/?probe=1b1d11f461) | Jun 14, 2023 |
| Samsung       | N130                        | [3efb763643](https://linux-hardware.org/?probe=3efb763643) | Jun 14, 2023 |
| MSI           | GL73 8RE                    | [e37b06f2b0](https://linux-hardware.org/?probe=e37b06f2b0) | Jun 14, 2023 |
| ASUSTek       | P553UA                      | [2543eb4ce8](https://linux-hardware.org/?probe=2543eb4ce8) | Jun 14, 2023 |
| Dell          | XPS 15 9560                 | [f3b25c0959](https://linux-hardware.org/?probe=f3b25c0959) | Jun 14, 2023 |
| HP            | Pavilion dv7                | [3c113d457b](https://linux-hardware.org/?probe=3c113d457b) | Jun 13, 2023 |
| Dell          | Latitude E5540              | [029d51e57f](https://linux-hardware.org/?probe=029d51e57f) | Jun 13, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [d910ebe7bb](https://linux-hardware.org/?probe=d910ebe7bb) | Jun 13, 2023 |
| Dell          | Latitude E7250              | [cc9fc2bace](https://linux-hardware.org/?probe=cc9fc2bace) | Jun 13, 2023 |
| HP            | EliteBook 2530p             | [8e5a09ba99](https://linux-hardware.org/?probe=8e5a09ba99) | Jun 12, 2023 |
| HP            | EliteBook 2530p             | [b843a66531](https://linux-hardware.org/?probe=b843a66531) | Jun 11, 2023 |
| HP            | ZBook 15 G6                 | [180abd0b90](https://linux-hardware.org/?probe=180abd0b90) | Jun 11, 2023 |
| Valve         | Jupiter                     | [d276b58f38](https://linux-hardware.org/?probe=d276b58f38) | Jun 10, 2023 |
| HP            | Compaq CQ58                 | [98a4edb43d](https://linux-hardware.org/?probe=98a4edb43d) | Jun 10, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [bdca36306b](https://linux-hardware.org/?probe=bdca36306b) | Jun 10, 2023 |
| HUAWEI        | BOD-WXX9                    | [c4063bcf07](https://linux-hardware.org/?probe=c4063bcf07) | Jun 09, 2023 |
| HUAWEI        | BOD-WXX9                    | [9016ad81ae](https://linux-hardware.org/?probe=9016ad81ae) | Jun 09, 2023 |
| Sony          | SVE1713X1EB                 | [f1c10c92b3](https://linux-hardware.org/?probe=f1c10c92b3) | Jun 09, 2023 |
| Acer          | Aspire F5-573G              | [5648ca2620](https://linux-hardware.org/?probe=5648ca2620) | Jun 09, 2023 |
| Acer          | Aspire F5-573G              | [30dbebd931](https://linux-hardware.org/?probe=30dbebd931) | Jun 09, 2023 |
| Onda TLC      | ONDA Oliver                 | [80a06d821b](https://linux-hardware.org/?probe=80a06d821b) | Jun 09, 2023 |
| HP            | EliteBook 8440p             | [b88712538e](https://linux-hardware.org/?probe=b88712538e) | Jun 09, 2023 |
| HP            | EliteBook 8440p             | [51bfdec531](https://linux-hardware.org/?probe=51bfdec531) | Jun 09, 2023 |
| Acer          | Aspire A315-51              | [9bcc99d434](https://linux-hardware.org/?probe=9bcc99d434) | Jun 08, 2023 |
| Acer          | Aspire A315-51              | [3013e9caf2](https://linux-hardware.org/?probe=3013e9caf2) | Jun 08, 2023 |
| HP            | G42                         | [fe8d2be276](https://linux-hardware.org/?probe=fe8d2be276) | Jun 08, 2023 |
| HP            | G42                         | [4f33462d46](https://linux-hardware.org/?probe=4f33462d46) | Jun 08, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [8a01610ae4](https://linux-hardware.org/?probe=8a01610ae4) | Jun 08, 2023 |
| HUAWEI        | HKD-WXX                     | [d6a8e02362](https://linux-hardware.org/?probe=d6a8e02362) | Jun 08, 2023 |
| ASUSTek       | X580VN                      | [8c1cf3f164](https://linux-hardware.org/?probe=8c1cf3f164) | Jun 08, 2023 |
| HUAWEI        | HKD-WXX                     | [fdb80f6e89](https://linux-hardware.org/?probe=fdb80f6e89) | Jun 08, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [82d0019a0b](https://linux-hardware.org/?probe=82d0019a0b) | Jun 08, 2023 |
| Acer          | AO722                       | [a57b6cf2ff](https://linux-hardware.org/?probe=a57b6cf2ff) | Jun 08, 2023 |
| HP            | Pavilion dv7                | [75a37cd4c8](https://linux-hardware.org/?probe=75a37cd4c8) | Jun 07, 2023 |
| Onda TLC      | ONDA Oliver                 | [bbfcf4a3be](https://linux-hardware.org/?probe=bbfcf4a3be) | Jun 07, 2023 |
| Dell          | Latitude 5300               | [1eea10cfa3](https://linux-hardware.org/?probe=1eea10cfa3) | Jun 07, 2023 |
| HP            | Pavilion Notebook           | [5254a5fe09](https://linux-hardware.org/?probe=5254a5fe09) | Jun 07, 2023 |
| Acer          | Aspire E1-571               | [f4e4a4b982](https://linux-hardware.org/?probe=f4e4a4b982) | Jun 07, 2023 |
| Acer          | Aspire E1-571               | [7948f267c2](https://linux-hardware.org/?probe=7948f267c2) | Jun 07, 2023 |
| Acer          | AO722                       | [8840b1284b](https://linux-hardware.org/?probe=8840b1284b) | Jun 06, 2023 |
| Acer          | Aspire E1-571               | [1139c69312](https://linux-hardware.org/?probe=1139c69312) | Jun 06, 2023 |
| MSI           | GF63 Thin 9RCX              | [85ec51dbf3](https://linux-hardware.org/?probe=85ec51dbf3) | Jun 05, 2023 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [c20dd8572a](https://linux-hardware.org/?probe=c20dd8572a) | Jun 05, 2023 |
| HUAWEI        | KPR-WX9                     | [3eb711e453](https://linux-hardware.org/?probe=3eb711e453) | Jun 05, 2023 |
| Dell          | XPS 13 9305                 | [450d20f29d](https://linux-hardware.org/?probe=450d20f29d) | Jun 05, 2023 |
| Acer          | Aspire F5-573G              | [b4f165f28d](https://linux-hardware.org/?probe=b4f165f28d) | Jun 05, 2023 |
| Acer          | Aspire F5-573G              | [e0ce9df73c](https://linux-hardware.org/?probe=e0ce9df73c) | Jun 05, 2023 |
| MSI           | GL75 Leopard 10SER          | [24111ade43](https://linux-hardware.org/?probe=24111ade43) | Jun 04, 2023 |
| Acer          | Aspire E5-573G              | [3ef3c9ec82](https://linux-hardware.org/?probe=3ef3c9ec82) | Jun 04, 2023 |
| Sony          | SVE1713X1EB                 | [6a50598ca6](https://linux-hardware.org/?probe=6a50598ca6) | Jun 04, 2023 |
| HP            | 255 G7 Notebook PC          | [8b14da5cf8](https://linux-hardware.org/?probe=8b14da5cf8) | Jun 04, 2023 |
| HP            | ZBook 15 G2                 | [19ed8e22e6](https://linux-hardware.org/?probe=19ed8e22e6) | Jun 03, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [ac6745cffb](https://linux-hardware.org/?probe=ac6745cffb) | Jun 03, 2023 |
| Dell          | Latitude E5430 non-vPro     | [ba2dfac7ae](https://linux-hardware.org/?probe=ba2dfac7ae) | Jun 03, 2023 |
| Sony          | SVE1713X1EB                 | [fc0097b52f](https://linux-hardware.org/?probe=fc0097b52f) | Jun 03, 2023 |
| HONOR         | BBR-WAX9                    | [fe03659a55](https://linux-hardware.org/?probe=fe03659a55) | Jun 02, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [959b76650d](https://linux-hardware.org/?probe=959b76650d) | Jun 02, 2023 |
| Lenovo        | ThinkPad T470 20HES0FW00    | [174ffa62e4](https://linux-hardware.org/?probe=174ffa62e4) | Jun 02, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [49ca1fd34f](https://linux-hardware.org/?probe=49ca1fd34f) | Jun 02, 2023 |
| Lenovo        | G50-45 80E3                 | [3bc50c5ccb](https://linux-hardware.org/?probe=3bc50c5ccb) | Jun 02, 2023 |
| HONOR         | BBR-WAX9                    | [0a536c1198](https://linux-hardware.org/?probe=0a536c1198) | Jun 01, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [fcc2d0ed39](https://linux-hardware.org/?probe=fcc2d0ed39) | Jun 01, 2023 |
| MSI           | Prestige 15 A12UC           | [9324563727](https://linux-hardware.org/?probe=9324563727) | Jun 01, 2023 |
| MSI           | Prestige 15 A12UC           | [778e78d2a5](https://linux-hardware.org/?probe=778e78d2a5) | Jun 01, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [0b0c375bb8](https://linux-hardware.org/?probe=0b0c375bb8) | May 31, 2023 |
| Olidata       | Tehom cw4900                | [f5b147962f](https://linux-hardware.org/?probe=f5b147962f) | May 31, 2023 |
| HONOR         | BBR-WAX9                    | [8630cfad52](https://linux-hardware.org/?probe=8630cfad52) | May 31, 2023 |
| HP            | Laptop 15s-fq5xxx           | [bfcb7f950d](https://linux-hardware.org/?probe=bfcb7f950d) | May 31, 2023 |
| Dell          | Inspiron 15 5510            | [bd2319fd67](https://linux-hardware.org/?probe=bd2319fd67) | May 31, 2023 |
| Jumper        | EZbook                      | [3ccf2e1365](https://linux-hardware.org/?probe=3ccf2e1365) | May 31, 2023 |
| HP            | ENVY 15                     | [ad3cf182fe](https://linux-hardware.org/?probe=ad3cf182fe) | May 30, 2023 |
| HP            | ENVY 15                     | [5acbfb03f4](https://linux-hardware.org/?probe=5acbfb03f4) | May 30, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [bb50e13268](https://linux-hardware.org/?probe=bb50e13268) | May 30, 2023 |
| HP            | Pavilion 15                 | [ca18fafda8](https://linux-hardware.org/?probe=ca18fafda8) | May 29, 2023 |
| Lenovo        | G50-45 80E3                 | [013d065e72](https://linux-hardware.org/?probe=013d065e72) | May 29, 2023 |
| Dell          | Latitude E5470              | [77d85b619e](https://linux-hardware.org/?probe=77d85b619e) | May 29, 2023 |
| Unknown       | Unknown                     | [351ca28b27](https://linux-hardware.org/?probe=351ca28b27) | May 29, 2023 |
| Acer          | Aspire A515-41G             | [644a5d7a16](https://linux-hardware.org/?probe=644a5d7a16) | May 29, 2023 |
| Apple         | MacBookAir7,2               | [2f44574d7c](https://linux-hardware.org/?probe=2f44574d7c) | May 29, 2023 |
| Apple         | MacBookPro7,1               | [81a267d02b](https://linux-hardware.org/?probe=81a267d02b) | May 28, 2023 |
| Apple         | MacBookAir7,2               | [5e146ef326](https://linux-hardware.org/?probe=5e146ef326) | May 28, 2023 |
| HUAWEI        | BOHB-WAX9                   | [c7afdbbd76](https://linux-hardware.org/?probe=c7afdbbd76) | May 28, 2023 |
| Apple         | MacBookPro6,2               | [db9c87ce89](https://linux-hardware.org/?probe=db9c87ce89) | May 28, 2023 |
| Sony          | SVE1713X1EB                 | [2695d0a6c8](https://linux-hardware.org/?probe=2695d0a6c8) | May 28, 2023 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [1eecbd5808](https://linux-hardware.org/?probe=1eecbd5808) | May 27, 2023 |
| HP            | G42                         | [7b9612a51a](https://linux-hardware.org/?probe=7b9612a51a) | May 27, 2023 |
| Dell          | XPS 15 9570                 | [e74ee1390f](https://linux-hardware.org/?probe=e74ee1390f) | May 26, 2023 |
| Dell          | XPS 15 9570                 | [ac75726738](https://linux-hardware.org/?probe=ac75726738) | May 26, 2023 |
| HP            | Pavilion x2 Detachable      | [e21476b6d2](https://linux-hardware.org/?probe=e21476b6d2) | May 26, 2023 |
| Acer          | Aspire A515-52G             | [433b367e58](https://linux-hardware.org/?probe=433b367e58) | May 26, 2023 |
| Acer          | Aspire A515-52G             | [ac85063e46](https://linux-hardware.org/?probe=ac85063e46) | May 26, 2023 |
| Acer          | Aspire 7750G                | [1ddb5fe9a0](https://linux-hardware.org/?probe=1ddb5fe9a0) | May 26, 2023 |
| Lenovo        | IdeaPad Z580                | [8d9c3b024d](https://linux-hardware.org/?probe=8d9c3b024d) | May 25, 2023 |
| ASUSTek       | S551LB                      | [86f50d3933](https://linux-hardware.org/?probe=86f50d3933) | May 25, 2023 |
| Mediacom      | SMARTBOOK ONE               | [ad010a6b3e](https://linux-hardware.org/?probe=ad010a6b3e) | May 25, 2023 |
| Lenovo        | ThinkPad W541 20EGS24J00    | [d674d76da5](https://linux-hardware.org/?probe=d674d76da5) | May 24, 2023 |
| Sony          | SVF13N2J2ES                 | [978ae98d6e](https://linux-hardware.org/?probe=978ae98d6e) | May 24, 2023 |
| Lenovo        | ThinkPad W541 20EGS24J00    | [3b74b092c6](https://linux-hardware.org/?probe=3b74b092c6) | May 24, 2023 |
| Sony          | SVE1513Q1ESI                | [422e8954f2](https://linux-hardware.org/?probe=422e8954f2) | May 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [c5baa41ff7](https://linux-hardware.org/?probe=c5baa41ff7) | May 24, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | [e484eaf025](https://linux-hardware.org/?probe=e484eaf025) | May 24, 2023 |
| Dell          | Precision 3571              | [3806fcdb9c](https://linux-hardware.org/?probe=3806fcdb9c) | May 24, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [1280876877](https://linux-hardware.org/?probe=1280876877) | May 24, 2023 |
| Sony          | SVF13N2J2ES                 | [01e2285654](https://linux-hardware.org/?probe=01e2285654) | May 24, 2023 |
| Acer          | Aspire 7750G                | [4ddad1d733](https://linux-hardware.org/?probe=4ddad1d733) | May 24, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [0dfd1ede62](https://linux-hardware.org/?probe=0dfd1ede62) | May 23, 2023 |
| Apple         | MacBookPro7,1               | [e1baf451db](https://linux-hardware.org/?probe=e1baf451db) | May 23, 2023 |
| Apple         | MacBookPro7,1               | [61ef8e4e63](https://linux-hardware.org/?probe=61ef8e4e63) | May 23, 2023 |
| Valve         | Jupiter                     | [223ab4f15c](https://linux-hardware.org/?probe=223ab4f15c) | May 23, 2023 |
| HP            | ENVY 15                     | [85a97390d5](https://linux-hardware.org/?probe=85a97390d5) | May 23, 2023 |
| Sony          | SVE1513Q1ESI                | [eef57d6c26](https://linux-hardware.org/?probe=eef57d6c26) | May 23, 2023 |
| HP            | Pavilion x2 Detachable      | [f9f3305d0b](https://linux-hardware.org/?probe=f9f3305d0b) | May 23, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [14b20068ca](https://linux-hardware.org/?probe=14b20068ca) | May 22, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [5300f7df17](https://linux-hardware.org/?probe=5300f7df17) | May 22, 2023 |
| Dell          | Latitude E6230              | [89c5618eb8](https://linux-hardware.org/?probe=89c5618eb8) | May 22, 2023 |
| HUAWEI        | KLVL-WXX9                   | [5cb11eee20](https://linux-hardware.org/?probe=5cb11eee20) | May 22, 2023 |
| HP            | ENVY 15                     | [21a38278ca](https://linux-hardware.org/?probe=21a38278ca) | May 21, 2023 |
| MSI           | Modern 14 B11MOL            | [7bc8f5e875](https://linux-hardware.org/?probe=7bc8f5e875) | May 21, 2023 |
| Lenovo        | ThinkPad X395 20NLCTO1WW    | [55a289b426](https://linux-hardware.org/?probe=55a289b426) | May 21, 2023 |
| ASUSTek       | ZenBook UX425JA_UX425JA     | [916d381f2f](https://linux-hardware.org/?probe=916d381f2f) | May 21, 2023 |
| ASUSTek       | N53TK                       | [275e480739](https://linux-hardware.org/?probe=275e480739) | May 21, 2023 |
| Acer          | Aspire 7750G                | [61ebf173dc](https://linux-hardware.org/?probe=61ebf173dc) | May 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [fa899a9a41](https://linux-hardware.org/?probe=fa899a9a41) | May 21, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [8ec7bb4682](https://linux-hardware.org/?probe=8ec7bb4682) | May 21, 2023 |
| Acer          | Aspire V3-572G              | [8f1be2d961](https://linux-hardware.org/?probe=8f1be2d961) | May 21, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [74274a1304](https://linux-hardware.org/?probe=74274a1304) | May 21, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | [07039bd959](https://linux-hardware.org/?probe=07039bd959) | May 21, 2023 |
| Toshiba       | Satellite Pro S500          | [b08ca84ea8](https://linux-hardware.org/?probe=b08ca84ea8) | May 20, 2023 |
| HP            | Pavilion dv6                | [51e808c93a](https://linux-hardware.org/?probe=51e808c93a) | May 20, 2023 |
| Valve         | Jupiter                     | [6b5b728c7e](https://linux-hardware.org/?probe=6b5b728c7e) | May 20, 2023 |
| Unknown       | Unknown                     | [c7157cc723](https://linux-hardware.org/?probe=c7157cc723) | May 20, 2023 |
| HP            | Pavilion dv3                | [34c6a2c14a](https://linux-hardware.org/?probe=34c6a2c14a) | May 20, 2023 |
| Lenovo        | ThinkPad T470s 20HF0000M... | [3976703e20](https://linux-hardware.org/?probe=3976703e20) | May 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [1f6220f21a](https://linux-hardware.org/?probe=1f6220f21a) | May 19, 2023 |
| MSI           | Alpha 15 B5EEK              | [b309bee7e9](https://linux-hardware.org/?probe=b309bee7e9) | May 19, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [5e6991f9e3](https://linux-hardware.org/?probe=5e6991f9e3) | May 19, 2023 |
| Unknown       | Unknown                     | [49c702a8c9](https://linux-hardware.org/?probe=49c702a8c9) | May 18, 2023 |
| ASUSTek       | X555LPB                     | [c1082eef21](https://linux-hardware.org/?probe=c1082eef21) | May 18, 2023 |
| Acer          | Aspire 5920G                | [65638219a5](https://linux-hardware.org/?probe=65638219a5) | May 18, 2023 |
| HUAWEI        | BOD-WXX9                    | [62e064b7d0](https://linux-hardware.org/?probe=62e064b7d0) | May 18, 2023 |
| Lenovo        | ThinkPad X260 20F6CTO1WW    | [a35e6c0b2d](https://linux-hardware.org/?probe=a35e6c0b2d) | May 17, 2023 |
| HP            | Pavilion Laptop 15-eg1xx... | [b5aef01bc9](https://linux-hardware.org/?probe=b5aef01bc9) | May 17, 2023 |
| HP            | ENVY 15                     | [4576cea8b0](https://linux-hardware.org/?probe=4576cea8b0) | May 17, 2023 |
| ASUSTek       | UX305FA                     | [36cb231f34](https://linux-hardware.org/?probe=36cb231f34) | May 16, 2023 |
| HP            | Pavilion dv6                | [bc505434f7](https://linux-hardware.org/?probe=bc505434f7) | May 16, 2023 |
| Dell          | Latitude E5530 non-vPro     | [7c05862259](https://linux-hardware.org/?probe=7c05862259) | May 16, 2023 |
| Acer          | Nitro AN515-45              | [62e3c494bd](https://linux-hardware.org/?probe=62e3c494bd) | May 16, 2023 |
| Valve         | Jupiter                     | [6c64da33ef](https://linux-hardware.org/?probe=6c64da33ef) | May 16, 2023 |
| Apple         | MacBook4,1                  | [755f1920f2](https://linux-hardware.org/?probe=755f1920f2) | May 15, 2023 |
| HUAWEI        | KLVD-WXX9                   | [ba609eb1e6](https://linux-hardware.org/?probe=ba609eb1e6) | May 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [bfd8d8244b](https://linux-hardware.org/?probe=bfd8d8244b) | May 15, 2023 |
| HP            | Pavilion dv6                | [fd5291d10e](https://linux-hardware.org/?probe=fd5291d10e) | May 15, 2023 |
| Dell          | Precision 7520              | [cbfb960bae](https://linux-hardware.org/?probe=cbfb960bae) | May 15, 2023 |
| Dell          | Precision 7520              | [a42d1a8bf5](https://linux-hardware.org/?probe=a42d1a8bf5) | May 15, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [2750a05721](https://linux-hardware.org/?probe=2750a05721) | May 15, 2023 |
| HP            | Pavilion x2 Detachable      | [e9e5b21145](https://linux-hardware.org/?probe=e9e5b21145) | May 15, 2023 |
| HP            | Pavilion x2 Detachable      | [34c6621991](https://linux-hardware.org/?probe=34c6621991) | May 15, 2023 |
| Lenovo        | ThinkPad X100e 0022CTO      | [842b7a3ee2](https://linux-hardware.org/?probe=842b7a3ee2) | May 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | [bb119829d0](https://linux-hardware.org/?probe=bb119829d0) | May 14, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [020d4612bd](https://linux-hardware.org/?probe=020d4612bd) | May 14, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | [ca65ed1052](https://linux-hardware.org/?probe=ca65ed1052) | May 14, 2023 |
| HP            | Compaq CQ58                 | [0df5818390](https://linux-hardware.org/?probe=0df5818390) | May 14, 2023 |
| Valve         | Jupiter                     | [af70e39629](https://linux-hardware.org/?probe=af70e39629) | May 14, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [2be4ad0e3d](https://linux-hardware.org/?probe=2be4ad0e3d) | May 14, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | [1bb0ed422e](https://linux-hardware.org/?probe=1bb0ed422e) | May 14, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | [5f3a14748e](https://linux-hardware.org/?probe=5f3a14748e) | May 13, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | [24aaf9e627](https://linux-hardware.org/?probe=24aaf9e627) | May 13, 2023 |
| HP            | Pavilion dv6                | [e20ba378ac](https://linux-hardware.org/?probe=e20ba378ac) | May 13, 2023 |
| HP            | ENVY 15                     | [e188fe21b7](https://linux-hardware.org/?probe=e188fe21b7) | May 12, 2023 |
| Lenovo        | ThinkPad Edge 02173BG       | [05f67c346b](https://linux-hardware.org/?probe=05f67c346b) | May 12, 2023 |
| Unknown       | Unknown                     | [8375f52559](https://linux-hardware.org/?probe=8375f52559) | May 12, 2023 |
| HP            | OMEN by Laptop              | [8b187d1291](https://linux-hardware.org/?probe=8b187d1291) | May 11, 2023 |
| Unknown       | Unknown                     | [00f98129ce](https://linux-hardware.org/?probe=00f98129ce) | May 11, 2023 |
| Valve         | Jupiter                     | [ec8ac0aafd](https://linux-hardware.org/?probe=ec8ac0aafd) | May 11, 2023 |
| Dell          | XPS 9315                    | [d53e7f5d92](https://linux-hardware.org/?probe=d53e7f5d92) | May 11, 2023 |
| Samsung       | RV410/RV510/S3510/E3510     | [d6a837c94d](https://linux-hardware.org/?probe=d6a837c94d) | May 11, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | [e03da60adf](https://linux-hardware.org/?probe=e03da60adf) | May 11, 2023 |
| Acer          | Aspire 5715Z                | [81c255952d](https://linux-hardware.org/?probe=81c255952d) | May 10, 2023 |
| Lenovo        | V15-ADA 82C7                | [8eae6560cb](https://linux-hardware.org/?probe=8eae6560cb) | May 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [eb6941b1b8](https://linux-hardware.org/?probe=eb6941b1b8) | May 10, 2023 |
| Acer          | Aspire E5-553G              | [922a392eee](https://linux-hardware.org/?probe=922a392eee) | May 09, 2023 |
| Dell          | Latitude 7420               | [4b8927333b](https://linux-hardware.org/?probe=4b8927333b) | May 09, 2023 |
| Dell          | Latitude E6520              | [668b26cd28](https://linux-hardware.org/?probe=668b26cd28) | May 09, 2023 |
| HP            | 255 G5                      | [4ed50eeba3](https://linux-hardware.org/?probe=4ed50eeba3) | May 09, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [4e95a5b88e](https://linux-hardware.org/?probe=4e95a5b88e) | May 08, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [5cbf24306a](https://linux-hardware.org/?probe=5cbf24306a) | May 08, 2023 |
| Acer          | Aspire 5750G                | [6b908b35cc](https://linux-hardware.org/?probe=6b908b35cc) | May 08, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [a4f5dce6d6](https://linux-hardware.org/?probe=a4f5dce6d6) | May 08, 2023 |
| Dell          | XPS 15 9570                 | [100534a570](https://linux-hardware.org/?probe=100534a570) | May 08, 2023 |
| Notebook      | P750ZM                      | [2cbd56abdc](https://linux-hardware.org/?probe=2cbd56abdc) | May 08, 2023 |
| Apple         | MacBookPro3,1               | [561202c004](https://linux-hardware.org/?probe=561202c004) | May 07, 2023 |
| HP            | 255 G3                      | [d95f6211dc](https://linux-hardware.org/?probe=d95f6211dc) | May 07, 2023 |
| HP            | Pavilion dv6                | [978d2165ac](https://linux-hardware.org/?probe=978d2165ac) | May 07, 2023 |
| HP            | 250 G5 Notebook PC          | [c1a5a5b4d9](https://linux-hardware.org/?probe=c1a5a5b4d9) | May 07, 2023 |
| Lenovo        | ThinkPad X260 20F6CTO1WW    | [e81eb02947](https://linux-hardware.org/?probe=e81eb02947) | May 07, 2023 |
| Acer          | Aspire E5-551G              | [ab9ff23d88](https://linux-hardware.org/?probe=ab9ff23d88) | May 07, 2023 |
| Acer          | Aspire E5-551G              | [a21a8395d8](https://linux-hardware.org/?probe=a21a8395d8) | May 07, 2023 |
| Lenovo        | G50-70 20351                | [784570bae3](https://linux-hardware.org/?probe=784570bae3) | May 07, 2023 |
| Dell          | XPS 13 9343                 | [5e91733408](https://linux-hardware.org/?probe=5e91733408) | May 07, 2023 |
| Lenovo        | ThinkPad X260 20F6CTO1WW    | [7998abcdcd](https://linux-hardware.org/?probe=7998abcdcd) | May 07, 2023 |
| HP            | Notebook                    | [cb89261339](https://linux-hardware.org/?probe=cb89261339) | May 06, 2023 |
| HP            | Laptop 15s-fq5xxx           | [8ce0b92713](https://linux-hardware.org/?probe=8ce0b92713) | May 06, 2023 |
| HP            | EliteBook 2530p             | [9963aba3a2](https://linux-hardware.org/?probe=9963aba3a2) | May 06, 2023 |
| Lenovo        | IdeaPad U510 20191          | [23414f0626](https://linux-hardware.org/?probe=23414f0626) | May 06, 2023 |
| HP            | Notebook                    | [74f9f1122e](https://linux-hardware.org/?probe=74f9f1122e) | May 06, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [7aeb31c7f1](https://linux-hardware.org/?probe=7aeb31c7f1) | May 05, 2023 |
| MSI           | Modern 14 B11MOL            | [d6bc185f4e](https://linux-hardware.org/?probe=d6bc185f4e) | May 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH7 ... | [bd885c202d](https://linux-hardware.org/?probe=bd885c202d) | May 05, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [a27c899176](https://linux-hardware.org/?probe=a27c899176) | May 04, 2023 |
| HP            | 255 G8 Notebook PC          | [af9621c92b](https://linux-hardware.org/?probe=af9621c92b) | May 04, 2023 |
| HP            | Elite x2 1012 G1            | [20dcc3e6b3](https://linux-hardware.org/?probe=20dcc3e6b3) | May 04, 2023 |
| KUU           | Andes II                    | [b15876e521](https://linux-hardware.org/?probe=b15876e521) | May 04, 2023 |
| Dell          | XPS 15 9510                 | [ce70c65f11](https://linux-hardware.org/?probe=ce70c65f11) | May 03, 2023 |
| HP            | Compaq Presario C700        | [8c62d76e28](https://linux-hardware.org/?probe=8c62d76e28) | May 03, 2023 |
| Sony          | SVF1521G1EW                 | [b84b2ed08a](https://linux-hardware.org/?probe=b84b2ed08a) | May 03, 2023 |
| Acer          | Swift SF515-51T             | [80d7446f47](https://linux-hardware.org/?probe=80d7446f47) | May 03, 2023 |
| Olivetti      | OLIBOOK P35-XXXAEU          | [bb924b0c19](https://linux-hardware.org/?probe=bb924b0c19) | May 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [4280750d03](https://linux-hardware.org/?probe=4280750d03) | May 03, 2023 |
| Samsung       | 750XDA                      | [2e99c882ff](https://linux-hardware.org/?probe=2e99c882ff) | May 03, 2023 |
| HUAWEI        | BOM-WXX9                    | [fd0dee0606](https://linux-hardware.org/?probe=fd0dee0606) | May 03, 2023 |
| TELECOMITA... | M7x0S                       | [d8256a8177](https://linux-hardware.org/?probe=d8256a8177) | May 03, 2023 |
| TELECOMITA... | M7x0S                       | [d4019e13f1](https://linux-hardware.org/?probe=d4019e13f1) | May 03, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [910824ac40](https://linux-hardware.org/?probe=910824ac40) | May 03, 2023 |
| Lenovo        | ThinkPad X220 4291IR6       | [56d274f769](https://linux-hardware.org/?probe=56d274f769) | May 03, 2023 |
| Lenovo        | V130-15IKB 81HN             | [8c3e5e8d50](https://linux-hardware.org/?probe=8c3e5e8d50) | May 03, 2023 |
| Dell          | Latitude E7270              | [62c1cdc600](https://linux-hardware.org/?probe=62c1cdc600) | May 02, 2023 |
| Sony          | VPCF11C5E                   | [77f08d3d00](https://linux-hardware.org/?probe=77f08d3d00) | May 02, 2023 |
| Dell          | Latitude E7270              | [96e1a00bae](https://linux-hardware.org/?probe=96e1a00bae) | May 02, 2023 |
| HP            | Laptop 15s-eq3xxx           | [5375a4f57c](https://linux-hardware.org/?probe=5375a4f57c) | May 02, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [b56701568d](https://linux-hardware.org/?probe=b56701568d) | May 01, 2023 |
| HP            | 255 G4                      | [b06ddec94b](https://linux-hardware.org/?probe=b06ddec94b) | May 01, 2023 |
| Timi          | RedmiBook 16                | [01706331eb](https://linux-hardware.org/?probe=01706331eb) | May 01, 2023 |
| HP            | Compaq 8510w                | [eea89c8c92](https://linux-hardware.org/?probe=eea89c8c92) | May 01, 2023 |
| HP            | ENVY 15                     | [935dc183e1](https://linux-hardware.org/?probe=935dc183e1) | May 01, 2023 |
| HP            | OMEN by Laptop              | [bfbda66d8b](https://linux-hardware.org/?probe=bfbda66d8b) | May 01, 2023 |
| ASUSTek       | K52Jc                       | [ae414cf185](https://linux-hardware.org/?probe=ae414cf185) | May 01, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | [cbc75f825e](https://linux-hardware.org/?probe=cbc75f825e) | May 01, 2023 |
| Lenovo        | Legion S7 15IMH5 82BC       | [a57d01b946](https://linux-hardware.org/?probe=a57d01b946) | May 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [05251702aa](https://linux-hardware.org/?probe=05251702aa) | Apr 30, 2023 |
| HP            | 255 G8 Notebook PC          | [7262375294](https://linux-hardware.org/?probe=7262375294) | Apr 30, 2023 |
| HP            | Compaq 6720s                | [cc5f5ee72c](https://linux-hardware.org/?probe=cc5f5ee72c) | Apr 30, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [36ccc3c930](https://linux-hardware.org/?probe=36ccc3c930) | Apr 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [94118ab632](https://linux-hardware.org/?probe=94118ab632) | Apr 30, 2023 |
| MSI           | Modern 14 B11MOU            | [6b3fcf3fcc](https://linux-hardware.org/?probe=6b3fcf3fcc) | Apr 29, 2023 |
| Acer          | Aspire A515-51G             | [bd4c84da60](https://linux-hardware.org/?probe=bd4c84da60) | Apr 29, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [59fcc52279](https://linux-hardware.org/?probe=59fcc52279) | Apr 29, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [25d0c90e31](https://linux-hardware.org/?probe=25d0c90e31) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [b6bd42eb71](https://linux-hardware.org/?probe=b6bd42eb71) | Apr 27, 2023 |
| TUXEDO        | Unknown                     | [5108a05d49](https://linux-hardware.org/?probe=5108a05d49) | Apr 27, 2023 |
| Dell          | Latitude E6400              | [2cb1305ae1](https://linux-hardware.org/?probe=2cb1305ae1) | Apr 27, 2023 |
| Toshiba       | Satellite Pro S500          | [7a2503959a](https://linux-hardware.org/?probe=7a2503959a) | Apr 26, 2023 |
| Acer          | TravelMate 6593             | [58dce8147e](https://linux-hardware.org/?probe=58dce8147e) | Apr 26, 2023 |
| HP            | ENVY 15                     | [1f50420c44](https://linux-hardware.org/?probe=1f50420c44) | Apr 26, 2023 |
| Lenovo        | ThinkPad T480s 20L8002WM... | [82bd4b0d20](https://linux-hardware.org/?probe=82bd4b0d20) | Apr 26, 2023 |
| Acer          | Aspire A515-45              | [496934207f](https://linux-hardware.org/?probe=496934207f) | Apr 25, 2023 |
| Acer          | Aspire A515-45              | [0466417666](https://linux-hardware.org/?probe=0466417666) | Apr 25, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [50930ebe57](https://linux-hardware.org/?probe=50930ebe57) | Apr 25, 2023 |
| Acer          | Aspire 5920G                | [c6387003fc](https://linux-hardware.org/?probe=c6387003fc) | Apr 25, 2023 |
| HP            | Laptop 17-cp0xxx            | [288f3f709c](https://linux-hardware.org/?probe=288f3f709c) | Apr 24, 2023 |
| HP            | 470 17 inch G9 Notebook ... | [6b73c4cb65](https://linux-hardware.org/?probe=6b73c4cb65) | Apr 24, 2023 |
| Onda TLC      | ONDA Oliver                 | [c59dbdea18](https://linux-hardware.org/?probe=c59dbdea18) | Apr 23, 2023 |
| Gigabyte      | G5 KD                       | [d7648edaab](https://linux-hardware.org/?probe=d7648edaab) | Apr 23, 2023 |
| Acer          | Swift SF314-43              | [b18f893905](https://linux-hardware.org/?probe=b18f893905) | Apr 23, 2023 |
| Toshiba       | Satellite Pro S500          | [fcf8a7bdb4](https://linux-hardware.org/?probe=fcf8a7bdb4) | Apr 23, 2023 |
| Dell          | Inspiron MP061              | [2b25a48030](https://linux-hardware.org/?probe=2b25a48030) | Apr 23, 2023 |
| Sony          | SVE1713X1EB                 | [b935ad65e3](https://linux-hardware.org/?probe=b935ad65e3) | Apr 22, 2023 |
| ASUSTek       | 1215B                       | [a7fc39a85b](https://linux-hardware.org/?probe=a7fc39a85b) | Apr 22, 2023 |
| HUAWEI        | BOHB-WAX9                   | [5cceab0ac3](https://linux-hardware.org/?probe=5cceab0ac3) | Apr 22, 2023 |
| Apple         | MacBook6,1                  | [47ea666f74](https://linux-hardware.org/?probe=47ea666f74) | Apr 21, 2023 |
| HP            | Compaq 6735s                | [9a23d08368](https://linux-hardware.org/?probe=9a23d08368) | Apr 21, 2023 |
| HP            | Compaq 6735s                | [6b255d5f07](https://linux-hardware.org/?probe=6b255d5f07) | Apr 21, 2023 |
| HP            | Pavilion Sleekbook 15       | [644ea805a9](https://linux-hardware.org/?probe=644ea805a9) | Apr 21, 2023 |
| Acer          | Swift SF114-32              | [7641434e4d](https://linux-hardware.org/?probe=7641434e4d) | Apr 21, 2023 |
| Apple         | MacBookAir7,2               | [d34d10b1ad](https://linux-hardware.org/?probe=d34d10b1ad) | Apr 20, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [aace924665](https://linux-hardware.org/?probe=aace924665) | Apr 20, 2023 |
| Apple         | MacBookAir7,2               | [b54a612e76](https://linux-hardware.org/?probe=b54a612e76) | Apr 20, 2023 |
| Lenovo        | G50-45 80E3                 | [1943314777](https://linux-hardware.org/?probe=1943314777) | Apr 19, 2023 |
| ASUSTek       | 1011PX                      | [6aa9d32dda](https://linux-hardware.org/?probe=6aa9d32dda) | Apr 19, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [9df9b0d25d](https://linux-hardware.org/?probe=9df9b0d25d) | Apr 19, 2023 |
| HP            | Pavilion x2 Detachable      | [1c7cd2fe1d](https://linux-hardware.org/?probe=1c7cd2fe1d) | Apr 19, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [9db7166b25](https://linux-hardware.org/?probe=9db7166b25) | Apr 19, 2023 |
| Lenovo        | ThinkPad T480s 20L8S6S30... | [9241adf5fb](https://linux-hardware.org/?probe=9241adf5fb) | Apr 19, 2023 |
| PC Special... | PCx0Dx                      | [0f82987a84](https://linux-hardware.org/?probe=0f82987a84) | Apr 18, 2023 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | [cccb2ff44c](https://linux-hardware.org/?probe=cccb2ff44c) | Apr 18, 2023 |
| Toshiba       | Kronos 10CUG                | [228e28e6a8](https://linux-hardware.org/?probe=228e28e6a8) | Apr 18, 2023 |
| HP            | Laptop 15s-fq1xxx           | [9437766194](https://linux-hardware.org/?probe=9437766194) | Apr 18, 2023 |
| Toshiba       | Satellite Pro C850-1J2      | [e5c63957a2](https://linux-hardware.org/?probe=e5c63957a2) | Apr 18, 2023 |
| HP            | Pavilion x2 Detachable      | [5d56d95ea5](https://linux-hardware.org/?probe=5d56d95ea5) | Apr 18, 2023 |
| HP            | Laptop 15-da0xxx            | [c64154e569](https://linux-hardware.org/?probe=c64154e569) | Apr 17, 2023 |
| Apple         | MacBookPro8,1               | [fa475c8ca8](https://linux-hardware.org/?probe=fa475c8ca8) | Apr 17, 2023 |
| HP            | EliteBook 8570w             | [317efe55c2](https://linux-hardware.org/?probe=317efe55c2) | Apr 17, 2023 |
| HP            | ProBook 445 14 inch G9 N... | [877464f534](https://linux-hardware.org/?probe=877464f534) | Apr 17, 2023 |
| HP            | ProBook 445 14 inch G9 N... | [650deb855e](https://linux-hardware.org/?probe=650deb855e) | Apr 17, 2023 |
| Medion        | E16401                      | [e6c20783e7](https://linux-hardware.org/?probe=e6c20783e7) | Apr 17, 2023 |
| Acer          | TravelMate 5730             | [8e99149abe](https://linux-hardware.org/?probe=8e99149abe) | Apr 17, 2023 |
| MSI           | Modern 14 B11MOU            | [d76555e7e6](https://linux-hardware.org/?probe=d76555e7e6) | Apr 16, 2023 |
| Acer          | Swift SF314-41              | [8c42a0aba8](https://linux-hardware.org/?probe=8c42a0aba8) | Apr 16, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [40ec2e0cba](https://linux-hardware.org/?probe=40ec2e0cba) | Apr 16, 2023 |
| MAXDATA       | o.max_5xs                   | [cb90c411ca](https://linux-hardware.org/?probe=cb90c411ca) | Apr 16, 2023 |
| Lenovo        | G50-45 80E3                 | [55309d71c2](https://linux-hardware.org/?probe=55309d71c2) | Apr 16, 2023 |
| Chuwi         | HeroBook Air                | [360f364ebf](https://linux-hardware.org/?probe=360f364ebf) | Apr 15, 2023 |
| Google        | Dragonair                   | [be10ee5035](https://linux-hardware.org/?probe=be10ee5035) | Apr 15, 2023 |
| Google        | Dragonair                   | [cb2aa57d07](https://linux-hardware.org/?probe=cb2aa57d07) | Apr 15, 2023 |
| Lenovo        | ThinkPad X250 20CLS0CW00    | [2d25abe83c](https://linux-hardware.org/?probe=2d25abe83c) | Apr 15, 2023 |
| Lenovo        | XiaoXinPro 16ACH 2021 82... | [8ca60a45fe](https://linux-hardware.org/?probe=8ca60a45fe) | Apr 15, 2023 |
| Dell          | Inspiron 5570               | [d582f92277](https://linux-hardware.org/?probe=d582f92277) | Apr 15, 2023 |
| HP            | Pavilion 15                 | [a51b096e12](https://linux-hardware.org/?probe=a51b096e12) | Apr 15, 2023 |
| HP            | Pavilion 15                 | [1f524a54fc](https://linux-hardware.org/?probe=1f524a54fc) | Apr 15, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [b60b4dbb07](https://linux-hardware.org/?probe=b60b4dbb07) | Apr 14, 2023 |
| Dell          | Latitude 9420               | [529aa83bbc](https://linux-hardware.org/?probe=529aa83bbc) | Apr 14, 2023 |
| HP            | EliteBook 8440p             | [6522f4e2dc](https://linux-hardware.org/?probe=6522f4e2dc) | Apr 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [6af1f492c4](https://linux-hardware.org/?probe=6af1f492c4) | Apr 14, 2023 |
| Chuwi         | LapBook Pro                 | [3c8bbf6ec3](https://linux-hardware.org/?probe=3c8bbf6ec3) | Apr 14, 2023 |
| MAXDATA       | o.max_5xs                   | [81a407c1d5](https://linux-hardware.org/?probe=81a407c1d5) | Apr 13, 2023 |
| Lenovo        | V15-IGL 82C3                | [3b24daf87d](https://linux-hardware.org/?probe=3b24daf87d) | Apr 13, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [5a86b52121](https://linux-hardware.org/?probe=5a86b52121) | Apr 13, 2023 |
| Toshiba       | Satellite Pro S500          | [44dca3cd92](https://linux-hardware.org/?probe=44dca3cd92) | Apr 13, 2023 |
| Dell          | XPS 9315                    | [20fa2b86b9](https://linux-hardware.org/?probe=20fa2b86b9) | Apr 12, 2023 |
| Acer          | Aspire A715-42G             | [54a72d7d55](https://linux-hardware.org/?probe=54a72d7d55) | Apr 12, 2023 |
| Packard Be... | EasyNote_MX45               | [95935443c0](https://linux-hardware.org/?probe=95935443c0) | Apr 11, 2023 |
| Lenovo        | ThinkPad L530 24783B3       | [9cb172cc6b](https://linux-hardware.org/?probe=9cb172cc6b) | Apr 11, 2023 |
| HP            | ProBook 650 G1              | [1a09ecfcd1](https://linux-hardware.org/?probe=1a09ecfcd1) | Apr 11, 2023 |
| HP            | Pavilion Sleekbook 15       | [dae979ddc0](https://linux-hardware.org/?probe=dae979ddc0) | Apr 11, 2023 |
| BESSTAR Te... | X400                        | [6b1587e21d](https://linux-hardware.org/?probe=6b1587e21d) | Apr 11, 2023 |
| HP            | Pavilion Sleekbook 15       | [e6e26b16f3](https://linux-hardware.org/?probe=e6e26b16f3) | Apr 11, 2023 |
| ASUSTek       | X541UV                      | [07b7bedac7](https://linux-hardware.org/?probe=07b7bedac7) | Apr 10, 2023 |
| ASUSTek       | N552VX                      | [a5bf121256](https://linux-hardware.org/?probe=a5bf121256) | Apr 10, 2023 |
| HP            | Laptop 15s-fq5xxx           | [649a715fba](https://linux-hardware.org/?probe=649a715fba) | Apr 10, 2023 |
| HP            | Laptop 15s-fq5xxx           | [39c6b4afbe](https://linux-hardware.org/?probe=39c6b4afbe) | Apr 10, 2023 |
| Sony          | SVE1713X1EB                 | [ccf16cae6a](https://linux-hardware.org/?probe=ccf16cae6a) | Apr 10, 2023 |
| Apple         | MacBookPro11,5              | [2e428c73dc](https://linux-hardware.org/?probe=2e428c73dc) | Apr 10, 2023 |
| ASUSTek       | K52Jc                       | [0e6d01e44d](https://linux-hardware.org/?probe=0e6d01e44d) | Apr 09, 2023 |
| Lenovo        | V14-ADA 82C6                | [23a244aaf4](https://linux-hardware.org/?probe=23a244aaf4) | Apr 09, 2023 |
| AMI           | Intel                       | [f35d255c12](https://linux-hardware.org/?probe=f35d255c12) | Apr 09, 2023 |
| ASUSTek       | K52Jc                       | [594a8d9a89](https://linux-hardware.org/?probe=594a8d9a89) | Apr 08, 2023 |
| HP            | EliteBook 2560p             | [a4b27a5659](https://linux-hardware.org/?probe=a4b27a5659) | Apr 08, 2023 |
| Sony          | VPCSE1V9E                   | [e6dd1647f3](https://linux-hardware.org/?probe=e6dd1647f3) | Apr 08, 2023 |
| Lenovo        | Z50-75 80EC                 | [1502ff1933](https://linux-hardware.org/?probe=1502ff1933) | Apr 08, 2023 |
| MSI           | Katana GF66 12UC            | [5d0c8cade6](https://linux-hardware.org/?probe=5d0c8cade6) | Apr 08, 2023 |
| Lenovo        | ThinkPad L430 24683NG       | [d5f226c56f](https://linux-hardware.org/?probe=d5f226c56f) | Apr 08, 2023 |
| HP            | Pavilion dv7                | [3a159264b1](https://linux-hardware.org/?probe=3a159264b1) | Apr 07, 2023 |
| HP            | Pavilion dv7                | [3ec1e98abd](https://linux-hardware.org/?probe=3ec1e98abd) | Apr 07, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | [1e9120783f](https://linux-hardware.org/?probe=1e9120783f) | Apr 07, 2023 |
| HP            | 250 G6 Notebook PC          | [859f83bbfc](https://linux-hardware.org/?probe=859f83bbfc) | Apr 07, 2023 |
| HP            | G61                         | [8eec217a3a](https://linux-hardware.org/?probe=8eec217a3a) | Apr 07, 2023 |
| HP            | G61                         | [d00ad3f0fb](https://linux-hardware.org/?probe=d00ad3f0fb) | Apr 07, 2023 |
| Lenovo        | B51-80 80LM                 | [78e2e080ea](https://linux-hardware.org/?probe=78e2e080ea) | Apr 07, 2023 |
| System76      | Oryx Pro                    | [a221f4f9d4](https://linux-hardware.org/?probe=a221f4f9d4) | Apr 06, 2023 |
| HP            | 250 G4                      | [3e85d0e3ef](https://linux-hardware.org/?probe=3e85d0e3ef) | Apr 06, 2023 |
| Acer          | Aspire 5250                 | [bf0fc7e5d1](https://linux-hardware.org/?probe=bf0fc7e5d1) | Apr 06, 2023 |
| Dell          | XPS 9320                    | [ff14e0074a](https://linux-hardware.org/?probe=ff14e0074a) | Apr 06, 2023 |
| Dell          | XPS 13 9380                 | [58e0aa6707](https://linux-hardware.org/?probe=58e0aa6707) | Apr 06, 2023 |
| Acer          | Aspire 5750G                | [3fa6f0de7a](https://linux-hardware.org/?probe=3fa6f0de7a) | Apr 06, 2023 |
| Lenovo        | ThinkPad X250 20CLS2X60S    | [b5b5fd68e9](https://linux-hardware.org/?probe=b5b5fd68e9) | Apr 05, 2023 |
| Sony          | SVE1713X1EB                 | [c31fccd9d8](https://linux-hardware.org/?probe=c31fccd9d8) | Apr 05, 2023 |
| Lenovo        | ThinkPad X61s 7666WJ5       | [eb755a4a95](https://linux-hardware.org/?probe=eb755a4a95) | Apr 05, 2023 |
| Fujitsu       | LIFEBOOK U759               | [08e8eb7cea](https://linux-hardware.org/?probe=08e8eb7cea) | Apr 05, 2023 |
| Dell          | Latitude 5591               | [aa2f4e4208](https://linux-hardware.org/?probe=aa2f4e4208) | Apr 05, 2023 |
| Samsung       | RC530/RC730                 | [3f886e678f](https://linux-hardware.org/?probe=3f886e678f) | Apr 05, 2023 |
| Samsung       | RC530/RC730                 | [43e4869357](https://linux-hardware.org/?probe=43e4869357) | Apr 05, 2023 |
| Dell          | XPS 13 7390                 | [73056011a2](https://linux-hardware.org/?probe=73056011a2) | Apr 04, 2023 |
| Dell          | XPS 13 7390                 | [906d900083](https://linux-hardware.org/?probe=906d900083) | Apr 04, 2023 |
| ASUSTek       | S551LB                      | [cd1746937a](https://linux-hardware.org/?probe=cd1746937a) | Apr 04, 2023 |
| Lenovo        | ThinkPad L490 20Q6S90C00    | [93fa18f474](https://linux-hardware.org/?probe=93fa18f474) | Apr 03, 2023 |
| Lenovo        | ThinkPad L490 20Q6S90C00    | [915c34d052](https://linux-hardware.org/?probe=915c34d052) | Apr 03, 2023 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | [cef60ea315](https://linux-hardware.org/?probe=cef60ea315) | Apr 03, 2023 |
| Lenovo        | ThinkPad X200 7459J74       | [d7f98c1ddb](https://linux-hardware.org/?probe=d7f98c1ddb) | Apr 03, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [fc89f163b0](https://linux-hardware.org/?probe=fc89f163b0) | Apr 03, 2023 |
| Lenovo        | B50-30 80ES                 | [11da2097ba](https://linux-hardware.org/?probe=11da2097ba) | Apr 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [f995b3a81f](https://linux-hardware.org/?probe=f995b3a81f) | Apr 02, 2023 |
| Apple         | MacBook3,1                  | [44f31f3094](https://linux-hardware.org/?probe=44f31f3094) | Apr 02, 2023 |
| Packard Be... | EasyNote TJ65               | [cd6a05149d](https://linux-hardware.org/?probe=cd6a05149d) | Apr 02, 2023 |
| ASUSTek       | X555LAB                     | [95f5025351](https://linux-hardware.org/?probe=95f5025351) | Apr 02, 2023 |
| Lenovo        | B50-30 80ES                 | [a971008720](https://linux-hardware.org/?probe=a971008720) | Apr 02, 2023 |
| PC Special... | Elimina Iv 17               | [0681af5346](https://linux-hardware.org/?probe=0681af5346) | Apr 01, 2023 |
| Acer          | Aspire A515-41G             | [f047e9361c](https://linux-hardware.org/?probe=f047e9361c) | Apr 01, 2023 |
| Lenovo        | V110-15ISK 80TL             | [db058df07b](https://linux-hardware.org/?probe=db058df07b) | Apr 01, 2023 |
| Lenovo        | V110-15ISK 80TL             | [3691be13e8](https://linux-hardware.org/?probe=3691be13e8) | Apr 01, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [70fb59cd4f](https://linux-hardware.org/?probe=70fb59cd4f) | Apr 01, 2023 |
| Unknown       | Unknown                     | [702a241ca6](https://linux-hardware.org/?probe=702a241ca6) | Apr 01, 2023 |
| Lenovo        | G50-45 80E3                 | [f75af97954](https://linux-hardware.org/?probe=f75af97954) | Apr 01, 2023 |
| HP            | Notebook                    | [7cb279c8e0](https://linux-hardware.org/?probe=7cb279c8e0) | Apr 01, 2023 |
| HP            | Pavilion x2 Detachable      | [363d925d25](https://linux-hardware.org/?probe=363d925d25) | Apr 01, 2023 |
| ASUSTek       | X556UAK                     | [24f79c68f6](https://linux-hardware.org/?probe=24f79c68f6) | Mar 31, 2023 |
| Notebook      | W54_55SU1,SUW               | [74313ae73b](https://linux-hardware.org/?probe=74313ae73b) | Mar 31, 2023 |
| Microtech     | ebookPro                    | [ffe1da27cc](https://linux-hardware.org/?probe=ffe1da27cc) | Mar 31, 2023 |
| Acer          | Extensa 215-31              | [b1601e6747](https://linux-hardware.org/?probe=b1601e6747) | Mar 31, 2023 |
| Dell          | Latitude E7440              | [fdd9fda693](https://linux-hardware.org/?probe=fdd9fda693) | Mar 31, 2023 |
| HP            | Pavilion 15                 | [4dc2c9dfc1](https://linux-hardware.org/?probe=4dc2c9dfc1) | Mar 31, 2023 |
| Lenovo        | ThinkPad E14 20RA0016IX     | [685f18f5b3](https://linux-hardware.org/?probe=685f18f5b3) | Mar 31, 2023 |
| Lenovo        | Yoga 3 11 80J8              | [fce7483fa0](https://linux-hardware.org/?probe=fce7483fa0) | Mar 31, 2023 |
| Olivetti      | Spring Peak                 | [9678c685d7](https://linux-hardware.org/?probe=9678c685d7) | Mar 31, 2023 |
| Olivetti      | Spring Peak                 | [7878f53f36](https://linux-hardware.org/?probe=7878f53f36) | Mar 31, 2023 |
| Valve         | Jupiter                     | [34766581f3](https://linux-hardware.org/?probe=34766581f3) | Mar 31, 2023 |
| Toshiba       | Satellite Pro S500          | [b2e60d9170](https://linux-hardware.org/?probe=b2e60d9170) | Mar 31, 2023 |
| ASUSTek       | N552VX                      | [cacf95c277](https://linux-hardware.org/?probe=cacf95c277) | Mar 30, 2023 |
| Acer          | Aspire ES1-523              | [a800dab0ab](https://linux-hardware.org/?probe=a800dab0ab) | Mar 30, 2023 |
| Sony          | SVE1713X1EB                 | [8953aa2e04](https://linux-hardware.org/?probe=8953aa2e04) | Mar 30, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [45f39402f0](https://linux-hardware.org/?probe=45f39402f0) | Mar 30, 2023 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [976d8a1a13](https://linux-hardware.org/?probe=976d8a1a13) | Mar 30, 2023 |
| Dell          | Precision 3560              | [f6ef5c1a2c](https://linux-hardware.org/?probe=f6ef5c1a2c) | Mar 30, 2023 |
| Lenovo        | G505 20240                  | [25c5c7ee2e](https://linux-hardware.org/?probe=25c5c7ee2e) | Mar 30, 2023 |
| Toshiba       | Satellite L655              | [2e6ea8bf5c](https://linux-hardware.org/?probe=2e6ea8bf5c) | Mar 30, 2023 |
| Dell          | Latitude 5580               | [84157deda8](https://linux-hardware.org/?probe=84157deda8) | Mar 29, 2023 |
| Fujitsu       | LIFEBOOK A555               | [6f28f9e6ec](https://linux-hardware.org/?probe=6f28f9e6ec) | Mar 29, 2023 |
| MSI           | Prestige 14Evo A11M         | [fc06b01f31](https://linux-hardware.org/?probe=fc06b01f31) | Mar 29, 2023 |
| MSI           | Prestige 14Evo A11M         | [5ac693dbd4](https://linux-hardware.org/?probe=5ac693dbd4) | Mar 29, 2023 |
| Lenovo        | ThinkPad T440 20B7A0CYMH    | [428491a9d5](https://linux-hardware.org/?probe=428491a9d5) | Mar 29, 2023 |
| Lenovo        | G50-45 80E3                 | [7bfed0aedd](https://linux-hardware.org/?probe=7bfed0aedd) | Mar 29, 2023 |
| HP            | Laptop 15-dw0xxx            | [53bc341050](https://linux-hardware.org/?probe=53bc341050) | Mar 29, 2023 |
| Valve         | Jupiter                     | [889e4e5eef](https://linux-hardware.org/?probe=889e4e5eef) | Mar 29, 2023 |
| HP            | ProBook 640 G1              | [c9ac2eb353](https://linux-hardware.org/?probe=c9ac2eb353) | Mar 28, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [5520b0fc5f](https://linux-hardware.org/?probe=5520b0fc5f) | Mar 28, 2023 |
| HP            | OMEN Laptop 15-ek0xxx       | [f44d26ed76](https://linux-hardware.org/?probe=f44d26ed76) | Mar 28, 2023 |
| Acer          | Swift SF314-511             | [ccef379a7f](https://linux-hardware.org/?probe=ccef379a7f) | Mar 28, 2023 |
| HP            | ProBook 450 G7              | [8b27d78a17](https://linux-hardware.org/?probe=8b27d78a17) | Mar 28, 2023 |
| Dell          | Inspiron 16 5630            | [5838554410](https://linux-hardware.org/?probe=5838554410) | Mar 28, 2023 |
| ASUSTek       | N53SV                       | [77aa77b2a3](https://linux-hardware.org/?probe=77aa77b2a3) | Mar 28, 2023 |
| Unknown       | Unknown                     | [26d819f9fc](https://linux-hardware.org/?probe=26d819f9fc) | Mar 27, 2023 |
| HP            | 250 G1                      | [75cf798dde](https://linux-hardware.org/?probe=75cf798dde) | Mar 27, 2023 |
| Sony          | SVE1713X1EB                 | [fa77641b57](https://linux-hardware.org/?probe=fa77641b57) | Mar 27, 2023 |
| Dell          | XPS 13 9305                 | [2f96abf16a](https://linux-hardware.org/?probe=2f96abf16a) | Mar 27, 2023 |
| Dell          | XPS 13 9305                 | [07caea9176](https://linux-hardware.org/?probe=07caea9176) | Mar 27, 2023 |
| Acer          | Mammoth                     | [d43ab9891b](https://linux-hardware.org/?probe=d43ab9891b) | Mar 27, 2023 |
| Sony          | VPCEH1S1E                   | [081294b14c](https://linux-hardware.org/?probe=081294b14c) | Mar 27, 2023 |
| Lenovo        | G50-45 80E3                 | [279d3659a9](https://linux-hardware.org/?probe=279d3659a9) | Mar 26, 2023 |
| ASUSTek       | X550LD                      | [6ac498fa82](https://linux-hardware.org/?probe=6ac498fa82) | Mar 26, 2023 |
| ASUSTek       | N552VW                      | [322426698a](https://linux-hardware.org/?probe=322426698a) | Mar 26, 2023 |
| Apple         | MacBookPro11,5              | [0c2be4a34c](https://linux-hardware.org/?probe=0c2be4a34c) | Mar 26, 2023 |
| Dell          | XPS 13 9305                 | [5b29fbd6ac](https://linux-hardware.org/?probe=5b29fbd6ac) | Mar 26, 2023 |
| Sony          | SVE1713X1EB                 | [cf11e69c46](https://linux-hardware.org/?probe=cf11e69c46) | Mar 26, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [55c29cec29](https://linux-hardware.org/?probe=55c29cec29) | Mar 26, 2023 |
| HP            | Compaq 6730s                | [ca30390612](https://linux-hardware.org/?probe=ca30390612) | Mar 25, 2023 |
| HP            | Laptop 15-dw3xxx            | [3b8cd70b69](https://linux-hardware.org/?probe=3b8cd70b69) | Mar 25, 2023 |
| MSI           | Katana GF66 12UG            | [9e03ac14c0](https://linux-hardware.org/?probe=9e03ac14c0) | Mar 25, 2023 |
| Lenovo        | V130-15IKB 81HN             | [0bfaf1252f](https://linux-hardware.org/?probe=0bfaf1252f) | Mar 25, 2023 |
| Dell          | Latitude E6230              | [1a248bdc33](https://linux-hardware.org/?probe=1a248bdc33) | Mar 25, 2023 |
| Acer          | Aspire A517-52G             | [ce3133a010](https://linux-hardware.org/?probe=ce3133a010) | Mar 25, 2023 |
| ASUSTek       | GL503VS                     | [8e066fcf6e](https://linux-hardware.org/?probe=8e066fcf6e) | Mar 25, 2023 |
| Lenovo        | Z50-75 80EC                 | [d6783c57a6](https://linux-hardware.org/?probe=d6783c57a6) | Mar 24, 2023 |
| Lenovo        | Z50-75 80EC                 | [353666c217](https://linux-hardware.org/?probe=353666c217) | Mar 24, 2023 |
| Dell          | XPS 13 9305                 | [c7e354ffe3](https://linux-hardware.org/?probe=c7e354ffe3) | Mar 24, 2023 |
| Apple         | MacBookPro11,5              | [9fd6508caf](https://linux-hardware.org/?probe=9fd6508caf) | Mar 24, 2023 |
| Dell          | Latitude 5580               | [d4ad4c55a6](https://linux-hardware.org/?probe=d4ad4c55a6) | Mar 24, 2023 |
| ASUSTek       | K53SJ                       | [175f99ccdd](https://linux-hardware.org/?probe=175f99ccdd) | Mar 23, 2023 |
| Acer          | Aspire E3-112               | [721e804a03](https://linux-hardware.org/?probe=721e804a03) | Mar 23, 2023 |
| HUAWEI        | BOD-WXX9                    | [088494906d](https://linux-hardware.org/?probe=088494906d) | Mar 23, 2023 |
| HP            | ProBook 440 G8 Notebook ... | [aba9609828](https://linux-hardware.org/?probe=aba9609828) | Mar 23, 2023 |
| Dell          | Inspiron 1750               | [007a0b3bb7](https://linux-hardware.org/?probe=007a0b3bb7) | Mar 22, 2023 |
| Dell          | XPS 9315                    | [b082aa6edf](https://linux-hardware.org/?probe=b082aa6edf) | Mar 22, 2023 |
| Dell          | XPS 9315                    | [9a14590477](https://linux-hardware.org/?probe=9a14590477) | Mar 22, 2023 |
| TrekStor      | Notebook Slim S130          | [6c3a6e7e53](https://linux-hardware.org/?probe=6c3a6e7e53) | Mar 22, 2023 |
| Toshiba       | Satellite Pro S500          | [2bb2519c2c](https://linux-hardware.org/?probe=2bb2519c2c) | Mar 21, 2023 |
| Toshiba       | Satellite Pro S500          | [a45c7086e5](https://linux-hardware.org/?probe=a45c7086e5) | Mar 21, 2023 |
| Dell          | XPS 15 9570                 | [6fc76628d3](https://linux-hardware.org/?probe=6fc76628d3) | Mar 21, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [b4d5442d02](https://linux-hardware.org/?probe=b4d5442d02) | Mar 21, 2023 |
| MSI           | Prestige 14Evo A11M         | [cac8d6b991](https://linux-hardware.org/?probe=cac8d6b991) | Mar 21, 2023 |
| HP            | Pavilion Laptop 15-cs2xx... | [6d96576431](https://linux-hardware.org/?probe=6d96576431) | Mar 21, 2023 |
| Dell          | Inspiron 5570               | [e311e9a53a](https://linux-hardware.org/?probe=e311e9a53a) | Mar 21, 2023 |
| Acer          | Extensa 5235                | [270cd6ed83](https://linux-hardware.org/?probe=270cd6ed83) | Mar 20, 2023 |
| Lenovo        | ThinkPad T480s 20L8002WM... | [762762da77](https://linux-hardware.org/?probe=762762da77) | Mar 20, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [0a71696d3b](https://linux-hardware.org/?probe=0a71696d3b) | Mar 20, 2023 |
| HP            | Laptop 15s-eq3xxx           | [83fbe3a3d6](https://linux-hardware.org/?probe=83fbe3a3d6) | Mar 20, 2023 |
| Notebook      | P15SM                       | [00d7786f9f](https://linux-hardware.org/?probe=00d7786f9f) | Mar 19, 2023 |
| Microtech     | CoreBook                    | [d50c0297a6](https://linux-hardware.org/?probe=d50c0297a6) | Mar 19, 2023 |
| HP            | G62                         | [2cb4092da0](https://linux-hardware.org/?probe=2cb4092da0) | Mar 19, 2023 |
| HP            | G62                         | [76d7e36f21](https://linux-hardware.org/?probe=76d7e36f21) | Mar 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [cbad8c5f1e](https://linux-hardware.org/?probe=cbad8c5f1e) | Mar 18, 2023 |
| Lenovo        | ThinkPad T460s 20FAS6PN0... | [bb86a34180](https://linux-hardware.org/?probe=bb86a34180) | Mar 18, 2023 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [a3339e152a](https://linux-hardware.org/?probe=a3339e152a) | Mar 18, 2023 |
| HP            | Laptop 15-dw1xxx            | [63ecda6230](https://linux-hardware.org/?probe=63ecda6230) | Mar 18, 2023 |
| HP            | ProBook 6570b               | [f5c9cd8419](https://linux-hardware.org/?probe=f5c9cd8419) | Mar 17, 2023 |
| HP            | 255 G3                      | [3e5f860704](https://linux-hardware.org/?probe=3e5f860704) | Mar 17, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [2530e262d2](https://linux-hardware.org/?probe=2530e262d2) | Mar 17, 2023 |
| ASUSTek       | K61IC                       | [045474725b](https://linux-hardware.org/?probe=045474725b) | Mar 17, 2023 |
| Lenovo        | ThinkPad T480s 20L8S88M0... | [2ad89b7995](https://linux-hardware.org/?probe=2ad89b7995) | Mar 16, 2023 |
| HP            | Pavilion Laptop 15-ck0xx    | [6a1e908693](https://linux-hardware.org/?probe=6a1e908693) | Mar 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [2cb5e6ce4f](https://linux-hardware.org/?probe=2cb5e6ce4f) | Mar 16, 2023 |
| Dell          | Latitude E5470              | [cc4f08349d](https://linux-hardware.org/?probe=cc4f08349d) | Mar 16, 2023 |
| MSI           | Modern 14 B11MOL            | [33bbc272c0](https://linux-hardware.org/?probe=33bbc272c0) | Mar 15, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [c454542aaa](https://linux-hardware.org/?probe=c454542aaa) | Mar 15, 2023 |
| Valve         | Jupiter                     | [fc387a787e](https://linux-hardware.org/?probe=fc387a787e) | Mar 15, 2023 |
| Toshiba       | Satellite Pro S500          | [0065669867](https://linux-hardware.org/?probe=0065669867) | Mar 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [b0b311216d](https://linux-hardware.org/?probe=b0b311216d) | Mar 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [0f6370d7f7](https://linux-hardware.org/?probe=0f6370d7f7) | Mar 14, 2023 |
| ASUSTek       | U36SD                       | [74e2dfbbc6](https://linux-hardware.org/?probe=74e2dfbbc6) | Mar 14, 2023 |
| HP            | Pavilion Laptop 15-ck0xx    | [d9f9e09a41](https://linux-hardware.org/?probe=d9f9e09a41) | Mar 14, 2023 |
| HP            | Pavilion Laptop 15-ck0xx    | [be16fd4aab](https://linux-hardware.org/?probe=be16fd4aab) | Mar 13, 2023 |
| ASUSTek       | GL753VE                     | [8100c63113](https://linux-hardware.org/?probe=8100c63113) | Mar 13, 2023 |
| HP            | Pavilion dv6500             | [03097b6049](https://linux-hardware.org/?probe=03097b6049) | Mar 13, 2023 |
| Dell          | XPS 15 9570                 | [456057e6af](https://linux-hardware.org/?probe=456057e6af) | Mar 13, 2023 |
| Dell          | XPS 15 9570                 | [7ee93079fb](https://linux-hardware.org/?probe=7ee93079fb) | Mar 13, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [ee01825196](https://linux-hardware.org/?probe=ee01825196) | Mar 13, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [a7d30f68b1](https://linux-hardware.org/?probe=a7d30f68b1) | Mar 12, 2023 |
| Acer          | aspire5740                  | [d5e64f31d4](https://linux-hardware.org/?probe=d5e64f31d4) | Mar 12, 2023 |
| HP            | Laptop 15s-fq5xxx           | [5bf763c288](https://linux-hardware.org/?probe=5bf763c288) | Mar 11, 2023 |
| Dell          | Latitude E6440              | [e5ba284442](https://linux-hardware.org/?probe=e5ba284442) | Mar 11, 2023 |
| HP            | G61                         | [2f5e9f6f43](https://linux-hardware.org/?probe=2f5e9f6f43) | Mar 11, 2023 |
| Sony          | SVE1713X1EB                 | [2a7d9091ff](https://linux-hardware.org/?probe=2a7d9091ff) | Mar 11, 2023 |
| ASUSTek       | X556UQK                     | [e5c898a856](https://linux-hardware.org/?probe=e5c898a856) | Mar 11, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [d7ed4aaf2c](https://linux-hardware.org/?probe=d7ed4aaf2c) | Mar 11, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [4664479644](https://linux-hardware.org/?probe=4664479644) | Mar 11, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [6e97141469](https://linux-hardware.org/?probe=6e97141469) | Mar 10, 2023 |
| HP            | EliteBook 840 G1            | [1315898b67](https://linux-hardware.org/?probe=1315898b67) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [ffcc55bb14](https://linux-hardware.org/?probe=ffcc55bb14) | Mar 10, 2023 |
| Lenovo        | ThinkPad T460 20LPS3K002    | [c375b36f4a](https://linux-hardware.org/?probe=c375b36f4a) | Mar 10, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [420b463f4d](https://linux-hardware.org/?probe=420b463f4d) | Mar 10, 2023 |
| ASUSTek       | X540LA                      | [de3c24e686](https://linux-hardware.org/?probe=de3c24e686) | Mar 10, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [041ebfc8c6](https://linux-hardware.org/?probe=041ebfc8c6) | Mar 09, 2023 |
| Lenovo        | ThinkPad T440p 20AWS0XX0... | [780937bb9f](https://linux-hardware.org/?probe=780937bb9f) | Mar 09, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [ffbffb33ae](https://linux-hardware.org/?probe=ffbffb33ae) | Mar 09, 2023 |
| Fujitsu       | LIFEBOOK U7312              | [74bbf2c865](https://linux-hardware.org/?probe=74bbf2c865) | Mar 09, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [796b1ad7cb](https://linux-hardware.org/?probe=796b1ad7cb) | Mar 09, 2023 |
| HP            | Compaq Presario CQ60        | [4167bec602](https://linux-hardware.org/?probe=4167bec602) | Mar 09, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [8faa1d14ca](https://linux-hardware.org/?probe=8faa1d14ca) | Mar 08, 2023 |
| Lenovo        | ThinkPad E490 20N9S21H00    | [0bb64aee2c](https://linux-hardware.org/?probe=0bb64aee2c) | Mar 08, 2023 |
| HP            | Pavilion x2 Detachable      | [04ef76ee4a](https://linux-hardware.org/?probe=04ef76ee4a) | Mar 07, 2023 |
| Timi          | TM1701                      | [3a94d06b73](https://linux-hardware.org/?probe=3a94d06b73) | Mar 07, 2023 |
| HP            | Pavilion dv6                | [a1631eb10b](https://linux-hardware.org/?probe=a1631eb10b) | Mar 07, 2023 |
| Unknown       | Unknown                     | [fdc4f4d3c6](https://linux-hardware.org/?probe=fdc4f4d3c6) | Mar 07, 2023 |
| Dell          | Latitude 5330               | [c99cbe9970](https://linux-hardware.org/?probe=c99cbe9970) | Mar 07, 2023 |
| HP            | EliteBook 840 G1            | [f56dc75b4e](https://linux-hardware.org/?probe=f56dc75b4e) | Mar 07, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [16c33be9a3](https://linux-hardware.org/?probe=16c33be9a3) | Mar 07, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [be24c7e178](https://linux-hardware.org/?probe=be24c7e178) | Mar 07, 2023 |
| Acer          | Aspire E5-575G              | [fd8c378fda](https://linux-hardware.org/?probe=fd8c378fda) | Mar 07, 2023 |
| ASUSTek       | X556UAK                     | [51f2084195](https://linux-hardware.org/?probe=51f2084195) | Mar 06, 2023 |
| Lenovo        | IdeaPad S540-14IWL 81ND     | [745898b5de](https://linux-hardware.org/?probe=745898b5de) | Mar 06, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [8a70478523](https://linux-hardware.org/?probe=8a70478523) | Mar 06, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [6e08a2dcf9](https://linux-hardware.org/?probe=6e08a2dcf9) | Mar 06, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [20fbc926fd](https://linux-hardware.org/?probe=20fbc926fd) | Mar 06, 2023 |
| Lenovo        | G50-45 80E3                 | [02dfdb807e](https://linux-hardware.org/?probe=02dfdb807e) | Mar 06, 2023 |
| HP            | G72                         | [64009d0874](https://linux-hardware.org/?probe=64009d0874) | Mar 06, 2023 |
| HP            | ProBook 430 G5              | [aaebada0ca](https://linux-hardware.org/?probe=aaebada0ca) | Mar 06, 2023 |
| YJKC          | vBOOK Plus RVP7             | [acdf0dca1d](https://linux-hardware.org/?probe=acdf0dca1d) | Mar 06, 2023 |
| Microtech     | ebookPro                    | [cac30f03b1](https://linux-hardware.org/?probe=cac30f03b1) | Mar 06, 2023 |
| Dell          | Inspiron 17-7779            | [24b5bddf1d](https://linux-hardware.org/?probe=24b5bddf1d) | Mar 05, 2023 |
| SANTECH       | NHx0DB,DE                   | [9ebc94ec48](https://linux-hardware.org/?probe=9ebc94ec48) | Mar 04, 2023 |
| Apple         | MacBookPro10,1              | [7b7aa513b8](https://linux-hardware.org/?probe=7b7aa513b8) | Mar 04, 2023 |
| Toshiba       | NB550D                      | [8ba5171640](https://linux-hardware.org/?probe=8ba5171640) | Mar 04, 2023 |
| HP            | G72                         | [a094ef43f1](https://linux-hardware.org/?probe=a094ef43f1) | Mar 04, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [4816618219](https://linux-hardware.org/?probe=4816618219) | Mar 04, 2023 |
| Dell          | Inspiron 16 7610            | [1121d93a65](https://linux-hardware.org/?probe=1121d93a65) | Mar 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [71f2f93645](https://linux-hardware.org/?probe=71f2f93645) | Mar 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [13fc723c9e](https://linux-hardware.org/?probe=13fc723c9e) | Mar 04, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | [1a0011a745](https://linux-hardware.org/?probe=1a0011a745) | Mar 03, 2023 |
| HP            | 255 G8 Notebook PC          | [7dc484b236](https://linux-hardware.org/?probe=7dc484b236) | Mar 03, 2023 |
| HP            | 255 G8 Notebook PC          | [b7e4822b00](https://linux-hardware.org/?probe=b7e4822b00) | Mar 03, 2023 |
| HUAWEI        | CREF-XX                     | [bef62e57b0](https://linux-hardware.org/?probe=bef62e57b0) | Mar 03, 2023 |
| HUAWEI        | CREF-XX                     | [b42f1c3f6b](https://linux-hardware.org/?probe=b42f1c3f6b) | Mar 03, 2023 |
| HP            | ENVY 15                     | [9ceefd9a22](https://linux-hardware.org/?probe=9ceefd9a22) | Mar 03, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [17f1328add](https://linux-hardware.org/?probe=17f1328add) | Mar 03, 2023 |
| HP            | ENVY dv6                    | [357b5b3506](https://linux-hardware.org/?probe=357b5b3506) | Mar 03, 2023 |
| Apple         | MacBookAir6,2               | [f791caa732](https://linux-hardware.org/?probe=f791caa732) | Mar 03, 2023 |
| Acer          | Aspire 5732Z                | [bff68efdba](https://linux-hardware.org/?probe=bff68efdba) | Mar 03, 2023 |
| HP            | EliteBook 830 G5            | [cd6c75d08e](https://linux-hardware.org/?probe=cd6c75d08e) | Mar 03, 2023 |
| Toshiba       | Satellite L50-B             | [8abe852ff0](https://linux-hardware.org/?probe=8abe852ff0) | Mar 03, 2023 |
| Apple         | MacBookAir6,2               | [0b39498d52](https://linux-hardware.org/?probe=0b39498d52) | Mar 03, 2023 |
| GMK           | NucBox2                     | [84af5a7d53](https://linux-hardware.org/?probe=84af5a7d53) | Mar 02, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [c34c6d8786](https://linux-hardware.org/?probe=c34c6d8786) | Mar 02, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [2a1515aaa3](https://linux-hardware.org/?probe=2a1515aaa3) | Mar 02, 2023 |
| Acer          | TravelMate P253             | [aa56b7749c](https://linux-hardware.org/?probe=aa56b7749c) | Mar 02, 2023 |
| MSI           | Creator 15M A9SD            | [b19d8d936c](https://linux-hardware.org/?probe=b19d8d936c) | Mar 02, 2023 |
| Acer          | Aspire 5755G                | [c1594b1f9d](https://linux-hardware.org/?probe=c1594b1f9d) | Mar 02, 2023 |
| PC Special... | 14 Fusion IV                | [e465178d82](https://linux-hardware.org/?probe=e465178d82) | Mar 02, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [98e86d41d1](https://linux-hardware.org/?probe=98e86d41d1) | Mar 01, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [61fe88e268](https://linux-hardware.org/?probe=61fe88e268) | Mar 01, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [6a99428156](https://linux-hardware.org/?probe=6a99428156) | Mar 01, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [52ecc1a9fb](https://linux-hardware.org/?probe=52ecc1a9fb) | Mar 01, 2023 |
| HP            | Pavilion 15                 | [78f570552a](https://linux-hardware.org/?probe=78f570552a) | Mar 01, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [456504fe92](https://linux-hardware.org/?probe=456504fe92) | Feb 28, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [1165717061](https://linux-hardware.org/?probe=1165717061) | Feb 28, 2023 |
| HP            | ENVY Laptop 17-ch1xxx       | [b518eb9925](https://linux-hardware.org/?probe=b518eb9925) | Feb 28, 2023 |
| HUAWEI        | MRC-WX0                     | [e2776f99bf](https://linux-hardware.org/?probe=e2776f99bf) | Feb 28, 2023 |
| Acer          | Aspire 5750G                | [34b5806bcf](https://linux-hardware.org/?probe=34b5806bcf) | Feb 28, 2023 |
| Dell          | Latitude 5530               | [f892221e4c](https://linux-hardware.org/?probe=f892221e4c) | Feb 27, 2023 |
| Acer          | Aspire E1-531               | [a52b94c2d5](https://linux-hardware.org/?probe=a52b94c2d5) | Feb 27, 2023 |
| Getac         | V200-X                      | [f3a5da3eae](https://linux-hardware.org/?probe=f3a5da3eae) | Feb 27, 2023 |
| Acer          | TravelMate B113             | [31691f9681](https://linux-hardware.org/?probe=31691f9681) | Feb 27, 2023 |
| Razer         | Blade 15 Base Model (Ear... | [425567e8f3](https://linux-hardware.org/?probe=425567e8f3) | Feb 27, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [2cea6ee649](https://linux-hardware.org/?probe=2cea6ee649) | Feb 26, 2023 |
| ASUSTek       | X540NA                      | [8bca0d4eb5](https://linux-hardware.org/?probe=8bca0d4eb5) | Feb 26, 2023 |
| Timi          | TM1612                      | [eb4a3f330e](https://linux-hardware.org/?probe=eb4a3f330e) | Feb 26, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [67b8b5ad09](https://linux-hardware.org/?probe=67b8b5ad09) | Feb 26, 2023 |
| Lenovo        | Y50-70 20378                | [005749f4ef](https://linux-hardware.org/?probe=005749f4ef) | Feb 26, 2023 |
| ASUSTek       | T100HAN                     | [bde9736ffd](https://linux-hardware.org/?probe=bde9736ffd) | Feb 26, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [84750f9d96](https://linux-hardware.org/?probe=84750f9d96) | Feb 25, 2023 |
| Acer          | Aspire A515-51G             | [432235c684](https://linux-hardware.org/?probe=432235c684) | Feb 25, 2023 |
| Acer          | Aspire ES1-521              | [e5f0a23afd](https://linux-hardware.org/?probe=e5f0a23afd) | Feb 25, 2023 |
| ASUSTek       | X551CA                      | [c8ead0e580](https://linux-hardware.org/?probe=c8ead0e580) | Feb 25, 2023 |
| HP            | 250 G3                      | [6a3d2238ba](https://linux-hardware.org/?probe=6a3d2238ba) | Feb 25, 2023 |
| ASUSTek       | T100HAN                     | [fd75fdb59f](https://linux-hardware.org/?probe=fd75fdb59f) | Feb 25, 2023 |
| ASUSTek       | X556URK                     | [fc80e01794](https://linux-hardware.org/?probe=fc80e01794) | Feb 25, 2023 |
| HP            | EliteBook 820 G3            | [75a0fcca48](https://linux-hardware.org/?probe=75a0fcca48) | Feb 25, 2023 |
| BESSTAR Te... | X400                        | [e1c05e0782](https://linux-hardware.org/?probe=e1c05e0782) | Feb 25, 2023 |
| HP            | ENVY 17                     | [08db7a8be2](https://linux-hardware.org/?probe=08db7a8be2) | Feb 25, 2023 |
| HP            | ENVY 17                     | [0ad15a7e01](https://linux-hardware.org/?probe=0ad15a7e01) | Feb 25, 2023 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [e3578290d2](https://linux-hardware.org/?probe=e3578290d2) | Feb 25, 2023 |
| HONOR         | HYM-WXX                     | [c6f84d1224](https://linux-hardware.org/?probe=c6f84d1224) | Feb 24, 2023 |
| HP            | EliteBook 840 Aero G8 No... | [f24e6a55c4](https://linux-hardware.org/?probe=f24e6a55c4) | Feb 24, 2023 |
| Dell          | Latitude 5530               | [8ad26dd8a0](https://linux-hardware.org/?probe=8ad26dd8a0) | Feb 24, 2023 |
| Fujitsu       | LIFEBOOK U749               | [ba7cdc6018](https://linux-hardware.org/?probe=ba7cdc6018) | Feb 24, 2023 |
| ASUSTek       | X555LA                      | [502020fe52](https://linux-hardware.org/?probe=502020fe52) | Feb 24, 2023 |
| ASUSTek       | X551CA                      | [62b46afbb8](https://linux-hardware.org/?probe=62b46afbb8) | Feb 24, 2023 |
| ASUSTek       | X510UQR                     | [075081e4ad](https://linux-hardware.org/?probe=075081e4ad) | Feb 24, 2023 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | [ac2d78d240](https://linux-hardware.org/?probe=ac2d78d240) | Feb 24, 2023 |
| Acer          | Aspire E1-531               | [4526585d29](https://linux-hardware.org/?probe=4526585d29) | Feb 24, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | [a8fbcbec0e](https://linux-hardware.org/?probe=a8fbcbec0e) | Feb 23, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [cddc383ff9](https://linux-hardware.org/?probe=cddc383ff9) | Feb 23, 2023 |
| Acer          | Aspire SW3-013              | [771b90caaa](https://linux-hardware.org/?probe=771b90caaa) | Feb 23, 2023 |
| Dell          | Latitude 5530               | [dbbcb7502c](https://linux-hardware.org/?probe=dbbcb7502c) | Feb 23, 2023 |
| Dell          | Latitude 5530               | [d620cdcce0](https://linux-hardware.org/?probe=d620cdcce0) | Feb 23, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [0f5352f94f](https://linux-hardware.org/?probe=0f5352f94f) | Feb 23, 2023 |
| HP            | Laptop 15s-eq2xxx           | [8a638dd3a7](https://linux-hardware.org/?probe=8a638dd3a7) | Feb 23, 2023 |
| Dell          | Latitude 7300               | [c4bb27e884](https://linux-hardware.org/?probe=c4bb27e884) | Feb 23, 2023 |
| Acer          | TravelMate P253             | [b99414b6de](https://linux-hardware.org/?probe=b99414b6de) | Feb 23, 2023 |
| HP            | Pavilion g6                 | [c76844f9a1](https://linux-hardware.org/?probe=c76844f9a1) | Feb 22, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [7d3442e2a7](https://linux-hardware.org/?probe=7d3442e2a7) | Feb 22, 2023 |
| ASUSTek       | X555DG                      | [5e7abe271f](https://linux-hardware.org/?probe=5e7abe271f) | Feb 22, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [99d4f0df73](https://linux-hardware.org/?probe=99d4f0df73) | Feb 22, 2023 |
| ASUSTek       | X555LA                      | [e62c134a68](https://linux-hardware.org/?probe=e62c134a68) | Feb 22, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [71928c5a75](https://linux-hardware.org/?probe=71928c5a75) | Feb 22, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [57e007d035](https://linux-hardware.org/?probe=57e007d035) | Feb 22, 2023 |
| HP            | ENVY 17                     | [f705060f1e](https://linux-hardware.org/?probe=f705060f1e) | Feb 22, 2023 |
| HP            | ENVY 17                     | [bf86e7904b](https://linux-hardware.org/?probe=bf86e7904b) | Feb 22, 2023 |
| HUAWEI        | BOD-WXX9                    | [05f20bac2d](https://linux-hardware.org/?probe=05f20bac2d) | Feb 21, 2023 |
| HP            | Pavilion dv6                | [526430f218](https://linux-hardware.org/?probe=526430f218) | Feb 21, 2023 |
| Acer          | Aspire SW3-013              | [f0111df214](https://linux-hardware.org/?probe=f0111df214) | Feb 21, 2023 |
| BESSTAR Te... | X400                        | [f7f9004058](https://linux-hardware.org/?probe=f7f9004058) | Feb 21, 2023 |
| Teclast       | F7                          | [3f5fdc3aa9](https://linux-hardware.org/?probe=3f5fdc3aa9) | Feb 21, 2023 |
| Unknown       | Unknown                     | [46d473b3e5](https://linux-hardware.org/?probe=46d473b3e5) | Feb 21, 2023 |
| Lenovo        | ThinkPad S430 336457G       | [3a525ce932](https://linux-hardware.org/?probe=3a525ce932) | Feb 21, 2023 |
| Lenovo        | ThinkPad S430 336457G       | [f845d181ec](https://linux-hardware.org/?probe=f845d181ec) | Feb 20, 2023 |
| ASUSTek       | X555LPB                     | [29eb95639c](https://linux-hardware.org/?probe=29eb95639c) | Feb 20, 2023 |
| Lenovo        | ThinkPad E590 20NB001AMX    | [ec529ac1bd](https://linux-hardware.org/?probe=ec529ac1bd) | Feb 20, 2023 |
| Acer          | Aspire V5-573G              | [376b35f5b6](https://linux-hardware.org/?probe=376b35f5b6) | Feb 20, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | [6f9ef751cd](https://linux-hardware.org/?probe=6f9ef751cd) | Feb 20, 2023 |
| Lenovo        | ThinkPad T470s 20HGS0BY0... | [56c81f1044](https://linux-hardware.org/?probe=56c81f1044) | Feb 20, 2023 |
| HP            | EliteBook 8570w             | [a6fd2ffc5b](https://linux-hardware.org/?probe=a6fd2ffc5b) | Feb 20, 2023 |
| HP            | ProBook 650 G1              | [4e6687829e](https://linux-hardware.org/?probe=4e6687829e) | Feb 19, 2023 |
| ASUSTek       | X555LA                      | [51d702d217](https://linux-hardware.org/?probe=51d702d217) | Feb 19, 2023 |
| Dell          | XPS 15 7590                 | [297b06716d](https://linux-hardware.org/?probe=297b06716d) | Feb 19, 2023 |
| Dell          | Inspiron 7520               | [1489b9779a](https://linux-hardware.org/?probe=1489b9779a) | Feb 19, 2023 |
| ASUSTek       | S551LN                      | [ff5df2cf03](https://linux-hardware.org/?probe=ff5df2cf03) | Feb 19, 2023 |
| ASUSTek       | S551LN                      | [84e519800c](https://linux-hardware.org/?probe=84e519800c) | Feb 19, 2023 |
| ASUSTek       | X555LA                      | [2ffc7c4a96](https://linux-hardware.org/?probe=2ffc7c4a96) | Feb 19, 2023 |
| Packard Be... | EasyNote TJ65               | [2c98b99901](https://linux-hardware.org/?probe=2c98b99901) | Feb 19, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [1104c148d1](https://linux-hardware.org/?probe=1104c148d1) | Feb 19, 2023 |
| Dell          | Latitude 5480               | [e288a18f9d](https://linux-hardware.org/?probe=e288a18f9d) | Feb 18, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | [eb9f3822a0](https://linux-hardware.org/?probe=eb9f3822a0) | Feb 18, 2023 |
| HP            | 255 G8 Notebook PC          | [ecf73f400b](https://linux-hardware.org/?probe=ecf73f400b) | Feb 18, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [eb64c99981](https://linux-hardware.org/?probe=eb64c99981) | Feb 18, 2023 |
| HP            | OMEN by Laptop 15-dh0xxx    | [cadd20aaff](https://linux-hardware.org/?probe=cadd20aaff) | Feb 18, 2023 |
| Samsung       | RF511/RF411/RF711           | [355838f8b2](https://linux-hardware.org/?probe=355838f8b2) | Feb 18, 2023 |
| MSI           | Summit E13FlipEvo A11MT     | [df01e5357c](https://linux-hardware.org/?probe=df01e5357c) | Feb 18, 2023 |
| HP            | 240 G6 Notebook PC          | [fc39dde214](https://linux-hardware.org/?probe=fc39dde214) | Feb 18, 2023 |
| Acer          | Aspire A515-45              | [01a17523fa](https://linux-hardware.org/?probe=01a17523fa) | Feb 18, 2023 |
| Acer          | Aspire A515-45              | [6b59c75dec](https://linux-hardware.org/?probe=6b59c75dec) | Feb 18, 2023 |
| Jumper        | EZbook                      | [35f7c6a28a](https://linux-hardware.org/?probe=35f7c6a28a) | Feb 18, 2023 |
| HP            | ENVY 15                     | [bcdc62a706](https://linux-hardware.org/?probe=bcdc62a706) | Feb 18, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [7360e6e667](https://linux-hardware.org/?probe=7360e6e667) | Feb 17, 2023 |
| Dell          | Latitude E6440              | [96e9e43a2e](https://linux-hardware.org/?probe=96e9e43a2e) | Feb 17, 2023 |
| Getac         | V200-X                      | [754a4bd022](https://linux-hardware.org/?probe=754a4bd022) | Feb 17, 2023 |
| Getac         | V200-X                      | [6794c7246f](https://linux-hardware.org/?probe=6794c7246f) | Feb 17, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [e4483255db](https://linux-hardware.org/?probe=e4483255db) | Feb 17, 2023 |
| MSI           | Summit E13FlipEvo A11MT     | [b29933336d](https://linux-hardware.org/?probe=b29933336d) | Feb 17, 2023 |
| MSI           | Summit E13FlipEvo A11MT     | [d97ee3d7d1](https://linux-hardware.org/?probe=d97ee3d7d1) | Feb 17, 2023 |
| Acer          | Aspire E5-571G              | [7a47fab9f3](https://linux-hardware.org/?probe=7a47fab9f3) | Feb 17, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [e84edd71e7](https://linux-hardware.org/?probe=e84edd71e7) | Feb 17, 2023 |
| HP            | Pavilion 15                 | [a48098f6fc](https://linux-hardware.org/?probe=a48098f6fc) | Feb 17, 2023 |
| HP            | EliteBook 840 G3            | [f8b182d99b](https://linux-hardware.org/?probe=f8b182d99b) | Feb 17, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [85fd62f731](https://linux-hardware.org/?probe=85fd62f731) | Feb 17, 2023 |
| Jumper        | EZbook                      | [82ba62c4b0](https://linux-hardware.org/?probe=82ba62c4b0) | Feb 16, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [7d6dcd9cd1](https://linux-hardware.org/?probe=7d6dcd9cd1) | Feb 16, 2023 |
| Lenovo        | ThinkPad T430 2349IF8       | [4b6268364f](https://linux-hardware.org/?probe=4b6268364f) | Feb 16, 2023 |
| Jumper        | EZbook                      | [1009011b57](https://linux-hardware.org/?probe=1009011b57) | Feb 16, 2023 |
| Acer          | Swift SF314-59              | [fcf01071e5](https://linux-hardware.org/?probe=fcf01071e5) | Feb 15, 2023 |
| HP            | Notebook                    | [21442c303e](https://linux-hardware.org/?probe=21442c303e) | Feb 15, 2023 |
| Lenovo        | ThinkPad SL 2746AHG         | [c141867fa3](https://linux-hardware.org/?probe=c141867fa3) | Feb 15, 2023 |
| Google        | Grunt                       | [89c633c2c1](https://linux-hardware.org/?probe=89c633c2c1) | Feb 15, 2023 |
| ASUSTek       | X553MA                      | [56ee76d678](https://linux-hardware.org/?probe=56ee76d678) | Feb 15, 2023 |
| ASUSTek       | X553MA                      | [1f8387dde4](https://linux-hardware.org/?probe=1f8387dde4) | Feb 15, 2023 |
| ASUSTek       | F6A                         | [3660446fe5](https://linux-hardware.org/?probe=3660446fe5) | Feb 15, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [28ac8fee12](https://linux-hardware.org/?probe=28ac8fee12) | Feb 14, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [dddbb2d135](https://linux-hardware.org/?probe=dddbb2d135) | Feb 14, 2023 |
| Acer          | Aspire 7250G                | [5f5cec8261](https://linux-hardware.org/?probe=5f5cec8261) | Feb 14, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [a3eb6fde29](https://linux-hardware.org/?probe=a3eb6fde29) | Feb 14, 2023 |
| HP            | ENVY 17                     | [d07a7a99de](https://linux-hardware.org/?probe=d07a7a99de) | Feb 14, 2023 |
| Dell          | XPS 9320                    | [10eb3017b5](https://linux-hardware.org/?probe=10eb3017b5) | Feb 13, 2023 |
| HP            | Laptop 15s-fq4xxx           | [9d1c8bca14](https://linux-hardware.org/?probe=9d1c8bca14) | Feb 13, 2023 |
| Acer          | Swift SF114-33              | [14cd72be0e](https://linux-hardware.org/?probe=14cd72be0e) | Feb 13, 2023 |
| MSI           | Prestige 14Evo A11M         | [abeebd4312](https://linux-hardware.org/?probe=abeebd4312) | Feb 13, 2023 |
| Unknown       | Unknown                     | [23a611650b](https://linux-hardware.org/?probe=23a611650b) | Feb 13, 2023 |
| MSI           | GF63 Thin 11UC              | [6eb24e6e38](https://linux-hardware.org/?probe=6eb24e6e38) | Feb 13, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [23eec2d2bc](https://linux-hardware.org/?probe=23eec2d2bc) | Feb 13, 2023 |
| HP            | ProBook 455 G8 Notebook ... | [3cccebc1ef](https://linux-hardware.org/?probe=3cccebc1ef) | Feb 12, 2023 |
| HP            | ENVY 15                     | [efc0c8427a](https://linux-hardware.org/?probe=efc0c8427a) | Feb 12, 2023 |
| Lenovo        | ThinkPad L460 20FVS25H01    | [37383d8798](https://linux-hardware.org/?probe=37383d8798) | Feb 12, 2023 |
| MSI           | GF63 Thin 11UC              | [f12982699d](https://linux-hardware.org/?probe=f12982699d) | Feb 12, 2023 |
| HP            | 255 G8 Notebook PC          | [3542104e07](https://linux-hardware.org/?probe=3542104e07) | Feb 12, 2023 |
| HUAWEI        | BOM-WXX9                    | [c798855263](https://linux-hardware.org/?probe=c798855263) | Feb 12, 2023 |
| HP            | Compaq 6720s                | [4b8e0e10e0](https://linux-hardware.org/?probe=4b8e0e10e0) | Feb 12, 2023 |
| HP            | Compaq 6720s                | [a23186bb63](https://linux-hardware.org/?probe=a23186bb63) | Feb 11, 2023 |
| Lenovo        | ThinkPad T440p 20AWS0XX0... | [404cac8b60](https://linux-hardware.org/?probe=404cac8b60) | Feb 11, 2023 |
| Dell          | Vostro 15 3510              | [8291db193a](https://linux-hardware.org/?probe=8291db193a) | Feb 11, 2023 |
| HP            | Notebook                    | [94c42af775](https://linux-hardware.org/?probe=94c42af775) | Feb 11, 2023 |
| HP            | ZBook 17 G3                 | [f0dff8ed53](https://linux-hardware.org/?probe=f0dff8ed53) | Feb 11, 2023 |
| HP            | Notebook                    | [e19e0407ec](https://linux-hardware.org/?probe=e19e0407ec) | Feb 11, 2023 |
| Dell          | XPS 15 9500                 | [11222774d3](https://linux-hardware.org/?probe=11222774d3) | Feb 10, 2023 |
| MSI           | Prestige 15 A11SCX          | [a82372e461](https://linux-hardware.org/?probe=a82372e461) | Feb 10, 2023 |
| HP            | Notebook                    | [4daf49165c](https://linux-hardware.org/?probe=4daf49165c) | Feb 10, 2023 |
| HP            | ZBook 17 G3                 | [bd09c6036f](https://linux-hardware.org/?probe=bd09c6036f) | Feb 10, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [fd8d478a5b](https://linux-hardware.org/?probe=fd8d478a5b) | Feb 10, 2023 |
| Lenovo        | Yoga Slim 7 13ITL5 82CU     | [7f4c6d1757](https://linux-hardware.org/?probe=7f4c6d1757) | Feb 10, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [9de542dff7](https://linux-hardware.org/?probe=9de542dff7) | Feb 09, 2023 |
| HP            | 255 G4                      | [00870a3da9](https://linux-hardware.org/?probe=00870a3da9) | Feb 09, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [08f3d3b7d8](https://linux-hardware.org/?probe=08f3d3b7d8) | Feb 09, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [0cb6963914](https://linux-hardware.org/?probe=0cb6963914) | Feb 09, 2023 |
| Acer          | Extensa 5635ZG              | [dd22b216a9](https://linux-hardware.org/?probe=dd22b216a9) | Feb 08, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [96d63ff41b](https://linux-hardware.org/?probe=96d63ff41b) | Feb 08, 2023 |
| Acer          | Aspire A515-52G             | [e521c55b1a](https://linux-hardware.org/?probe=e521c55b1a) | Feb 08, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [5ce86509b6](https://linux-hardware.org/?probe=5ce86509b6) | Feb 08, 2023 |
| Dell          | XPS 17 9720                 | [3d1b70c4af](https://linux-hardware.org/?probe=3d1b70c4af) | Feb 08, 2023 |
| Google        | Grunt                       | [84ecb8aaf1](https://linux-hardware.org/?probe=84ecb8aaf1) | Feb 08, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [3089398556](https://linux-hardware.org/?probe=3089398556) | Feb 08, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [07d8f7c1da](https://linux-hardware.org/?probe=07d8f7c1da) | Feb 08, 2023 |
| HP            | ENVY 15                     | [641ce1347d](https://linux-hardware.org/?probe=641ce1347d) | Feb 08, 2023 |
| Acer          | Aspire E5-553               | [5e951ad06d](https://linux-hardware.org/?probe=5e951ad06d) | Feb 07, 2023 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | [0713732442](https://linux-hardware.org/?probe=0713732442) | Feb 07, 2023 |
| Google        | Grunt                       | [1bbc4ae776](https://linux-hardware.org/?probe=1bbc4ae776) | Feb 07, 2023 |
| Lenovo        | ThinkPad T430 2347G7G       | [925017105d](https://linux-hardware.org/?probe=925017105d) | Feb 07, 2023 |
| HUAWEI        | MACH-WX9                    | [263101d492](https://linux-hardware.org/?probe=263101d492) | Feb 07, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | [b7ab00ddb1](https://linux-hardware.org/?probe=b7ab00ddb1) | Feb 07, 2023 |
| MSI           | U90/U100                    | [f7dc915782](https://linux-hardware.org/?probe=f7dc915782) | Feb 06, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [50af8c9fe6](https://linux-hardware.org/?probe=50af8c9fe6) | Feb 06, 2023 |
| ASUSTek       | X550JF                      | [c8f1b71cfd](https://linux-hardware.org/?probe=c8f1b71cfd) | Feb 06, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [0edeee4ba6](https://linux-hardware.org/?probe=0edeee4ba6) | Feb 06, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [66201d26d7](https://linux-hardware.org/?probe=66201d26d7) | Feb 06, 2023 |
| Acer          | Extensa 5635                | [8f8f4d24f9](https://linux-hardware.org/?probe=8f8f4d24f9) | Feb 06, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [762c097b3e](https://linux-hardware.org/?probe=762c097b3e) | Feb 06, 2023 |
| Intel         | Unknown                     | [a1044e362f](https://linux-hardware.org/?probe=a1044e362f) | Feb 06, 2023 |
| Lenovo        | Flex 2-14D 20376            | [16f0d33c85](https://linux-hardware.org/?probe=16f0d33c85) | Feb 06, 2023 |
| Lenovo        | ThinkPad T470 20HES3X300    | [6a77ec4c4f](https://linux-hardware.org/?probe=6a77ec4c4f) | Feb 06, 2023 |
| Valve         | Jupiter                     | [8a1998f130](https://linux-hardware.org/?probe=8a1998f130) | Feb 05, 2023 |
| Dell          | Latitude 7380               | [7b9d4ef8b4](https://linux-hardware.org/?probe=7b9d4ef8b4) | Feb 05, 2023 |
| ASUSTek       | N55SF                       | [5b81cbed5f](https://linux-hardware.org/?probe=5b81cbed5f) | Feb 05, 2023 |
| Acer          | One S1002                   | [2d98ceddca](https://linux-hardware.org/?probe=2d98ceddca) | Feb 05, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [30676c5e14](https://linux-hardware.org/?probe=30676c5e14) | Feb 05, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [08bf9ddbcf](https://linux-hardware.org/?probe=08bf9ddbcf) | Feb 05, 2023 |
| ASUSTek       | K52Jc                       | [464b35f82b](https://linux-hardware.org/?probe=464b35f82b) | Feb 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [2ac999e9b0](https://linux-hardware.org/?probe=2ac999e9b0) | Feb 05, 2023 |
| HP            | 255 G3                      | [dfa2e96880](https://linux-hardware.org/?probe=dfa2e96880) | Feb 05, 2023 |
| Acer          | Aspire E5-573G              | [b7760210a8](https://linux-hardware.org/?probe=b7760210a8) | Feb 05, 2023 |
| Notebook      | W25CSW                      | [b63184cd07](https://linux-hardware.org/?probe=b63184cd07) | Feb 05, 2023 |
| Notebook      | W65_67SJ                    | [870af12011](https://linux-hardware.org/?probe=870af12011) | Feb 05, 2023 |
| Lenovo        | G50-45 80E3                 | [229050fbe5](https://linux-hardware.org/?probe=229050fbe5) | Feb 05, 2023 |
| Acer          | TravelMate P253             | [b2cad8970a](https://linux-hardware.org/?probe=b2cad8970a) | Feb 04, 2023 |
| Lenovo        | G50-45 80E3                 | [885ad2ae95](https://linux-hardware.org/?probe=885ad2ae95) | Feb 04, 2023 |
| SiComputer    | Nauta 01C                   | [1579a837f7](https://linux-hardware.org/?probe=1579a837f7) | Feb 04, 2023 |
| Microtech     | CoreBook                    | [2ee0649a6e](https://linux-hardware.org/?probe=2ee0649a6e) | Feb 03, 2023 |
| Toshiba       | Satellite Pro S500          | [9274080d89](https://linux-hardware.org/?probe=9274080d89) | Feb 03, 2023 |
| HP            | ProBook 440 G7              | [f9a4f80656](https://linux-hardware.org/?probe=f9a4f80656) | Feb 03, 2023 |
| Intel         | Unknown                     | [ba5bda9424](https://linux-hardware.org/?probe=ba5bda9424) | Feb 02, 2023 |
| Acer          | Aspire F5-573G              | [ba43497e32](https://linux-hardware.org/?probe=ba43497e32) | Feb 02, 2023 |
| HP            | 250 G6 Notebook PC          | [a0b5d1c73c](https://linux-hardware.org/?probe=a0b5d1c73c) | Feb 02, 2023 |
| ASUSTek       | K54L                        | [8568b17267](https://linux-hardware.org/?probe=8568b17267) | Feb 02, 2023 |
| Dell          | XPS 13 7390                 | [f86eaa6db8](https://linux-hardware.org/?probe=f86eaa6db8) | Feb 02, 2023 |
| Timi          | Mi Laptop Pro 15            | [9deaff7467](https://linux-hardware.org/?probe=9deaff7467) | Feb 02, 2023 |
| Toshiba       | Satellite Pro S500          | [19a2c05804](https://linux-hardware.org/?probe=19a2c05804) | Feb 02, 2023 |
| HP            | Pavilion 15                 | [946fec8f7d](https://linux-hardware.org/?probe=946fec8f7d) | Feb 01, 2023 |
| Acer          | Aspire 5750G                | [a8a3f37ad8](https://linux-hardware.org/?probe=a8a3f37ad8) | Feb 01, 2023 |
| HP            | Laptop 15s-fq5xxx           | [bd22f26ad1](https://linux-hardware.org/?probe=bd22f26ad1) | Jan 31, 2023 |
| HP            | Laptop 15s-fq5xxx           | [28ea3cafe8](https://linux-hardware.org/?probe=28ea3cafe8) | Jan 31, 2023 |
| HP            | ENVY 15                     | [c688eb85bb](https://linux-hardware.org/?probe=c688eb85bb) | Jan 31, 2023 |
| HP            | Notebook                    | [f352309997](https://linux-hardware.org/?probe=f352309997) | Jan 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [78bd5ea99c](https://linux-hardware.org/?probe=78bd5ea99c) | Jan 31, 2023 |
| Acer          | Swift SF114-32              | [8e8ae85d60](https://linux-hardware.org/?probe=8e8ae85d60) | Jan 31, 2023 |
| Dell          | XPS 15 9570                 | [ee60c1c921](https://linux-hardware.org/?probe=ee60c1c921) | Jan 31, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [5e5231a159](https://linux-hardware.org/?probe=5e5231a159) | Jan 31, 2023 |
| Acer          | Aspire ES1-512              | [0d254e85dd](https://linux-hardware.org/?probe=0d254e85dd) | Jan 30, 2023 |
| Acer          | Aspire E1-522               | [88de348bef](https://linux-hardware.org/?probe=88de348bef) | Jan 30, 2023 |
| Dell          | Precision 3560              | [3d5432deef](https://linux-hardware.org/?probe=3d5432deef) | Jan 30, 2023 |
| Dell          | Precision 3560              | [c250c935bd](https://linux-hardware.org/?probe=c250c935bd) | Jan 30, 2023 |
| Dell          | Precision 3571              | [55f371f4ef](https://linux-hardware.org/?probe=55f371f4ef) | Jan 30, 2023 |
| Acer          | Aspire 5552                 | [f1168775a7](https://linux-hardware.org/?probe=f1168775a7) | Jan 30, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [519a211655](https://linux-hardware.org/?probe=519a211655) | Jan 30, 2023 |
| HP            | Laptop 15s-eq1xxx           | [9f093d7cff](https://linux-hardware.org/?probe=9f093d7cff) | Jan 30, 2023 |
| Acer          | Aspire E5-553               | [8200b57a5b](https://linux-hardware.org/?probe=8200b57a5b) | Jan 29, 2023 |
| Acer          | Aspire E5-553               | [3ac195a476](https://linux-hardware.org/?probe=3ac195a476) | Jan 29, 2023 |
| Acer          | Aspire A315-41              | [f8ef554d85](https://linux-hardware.org/?probe=f8ef554d85) | Jan 29, 2023 |
| Lenovo        | ThinkPad X220 42915CG       | [d058eeaad5](https://linux-hardware.org/?probe=d058eeaad5) | Jan 29, 2023 |
| Apple         | MacBookPro7,1               | [615e9f22e4](https://linux-hardware.org/?probe=615e9f22e4) | Jan 29, 2023 |
| Valve         | Jupiter                     | [5ea763da5f](https://linux-hardware.org/?probe=5ea763da5f) | Jan 28, 2023 |
| Dell          | Inspiron 5570               | [17a8246044](https://linux-hardware.org/?probe=17a8246044) | Jan 28, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [edd571ba94](https://linux-hardware.org/?probe=edd571ba94) | Jan 28, 2023 |
| Acer          | Aspire A315-41              | [bbe5b30c42](https://linux-hardware.org/?probe=bbe5b30c42) | Jan 28, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [844e4e4b2a](https://linux-hardware.org/?probe=844e4e4b2a) | Jan 28, 2023 |
| Acer          | Swift SF314-511             | [eeaf26e835](https://linux-hardware.org/?probe=eeaf26e835) | Jan 28, 2023 |
| Sony          | SVE1711C5E                  | [73977968f5](https://linux-hardware.org/?probe=73977968f5) | Jan 27, 2023 |
| Sony          | SVE1711C5E                  | [d526ae42aa](https://linux-hardware.org/?probe=d526ae42aa) | Jan 27, 2023 |
| HP            | 255 G8 Notebook PC          | [23a84c76b8](https://linux-hardware.org/?probe=23a84c76b8) | Jan 27, 2023 |
| Apple         | MacBook4,1                  | [e00443a9cc](https://linux-hardware.org/?probe=e00443a9cc) | Jan 27, 2023 |
| HUAWEI        | VLT-WX0                     | [270e8da18d](https://linux-hardware.org/?probe=270e8da18d) | Jan 27, 2023 |
| Lenovo        | ThinkPad E590 20NB001AMX    | [4bf7b18ab1](https://linux-hardware.org/?probe=4bf7b18ab1) | Jan 27, 2023 |
| HUAWEI        | KLVC-WXX9                   | [8fa82c8684](https://linux-hardware.org/?probe=8fa82c8684) | Jan 26, 2023 |
| Toshiba       | Satellite Pro C50-A-1FD     | [7f7198cdcb](https://linux-hardware.org/?probe=7f7198cdcb) | Jan 26, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | [8725d530e5](https://linux-hardware.org/?probe=8725d530e5) | Jan 26, 2023 |
| Dell          | XPS 17 9700                 | [759ae65214](https://linux-hardware.org/?probe=759ae65214) | Jan 26, 2023 |
| Chuwi         | GemiBook Pro                | [bea1d8a9ce](https://linux-hardware.org/?probe=bea1d8a9ce) | Jan 25, 2023 |
| HUAWEI        | KLVL-WXX9                   | [f04915614f](https://linux-hardware.org/?probe=f04915614f) | Jan 25, 2023 |
| Sony          | SVE1513C5E                  | [48ee443aef](https://linux-hardware.org/?probe=48ee443aef) | Jan 25, 2023 |
| ASUSTek       | N551JW                      | [9694a30eff](https://linux-hardware.org/?probe=9694a30eff) | Jan 25, 2023 |
| HP            | EliteBook 820 G2            | [7b93d7477b](https://linux-hardware.org/?probe=7b93d7477b) | Jan 25, 2023 |
| HP            | ProBook 6440b               | [25c4dbbe9c](https://linux-hardware.org/?probe=25c4dbbe9c) | Jan 24, 2023 |
| HP            | Laptop 15s-eq2xxx           | [cb29f724a0](https://linux-hardware.org/?probe=cb29f724a0) | Jan 24, 2023 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [cfd65f9e9e](https://linux-hardware.org/?probe=cfd65f9e9e) | Jan 24, 2023 |
| TUXEDO        | Aura 15 Gen1                | [51d8d1eb34](https://linux-hardware.org/?probe=51d8d1eb34) | Jan 24, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [5df97c3eb1](https://linux-hardware.org/?probe=5df97c3eb1) | Jan 24, 2023 |
| Toshiba       | Satellite Pro S500          | [d529b5d578](https://linux-hardware.org/?probe=d529b5d578) | Jan 24, 2023 |
| Dell          | XPS 9320                    | [e6a308392c](https://linux-hardware.org/?probe=e6a308392c) | Jan 23, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | [cbd812094c](https://linux-hardware.org/?probe=cbd812094c) | Jan 23, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [a05bb7e519](https://linux-hardware.org/?probe=a05bb7e519) | Jan 23, 2023 |
| Toshiba       | Satellite Pro S500          | [118cda5e06](https://linux-hardware.org/?probe=118cda5e06) | Jan 23, 2023 |
| ASUSTek       | G75VW                       | [917f63e659](https://linux-hardware.org/?probe=917f63e659) | Jan 23, 2023 |
| Fujitsu       | LIFEBOOK A544               | [972194ff6e](https://linux-hardware.org/?probe=972194ff6e) | Jan 23, 2023 |
| HUAWEI        | KLVL-WXX9                   | [5cd697d63d](https://linux-hardware.org/?probe=5cd697d63d) | Jan 23, 2023 |
| Fujitsu       | LIFEBOOK U9311A             | [6bdcfeae43](https://linux-hardware.org/?probe=6bdcfeae43) | Jan 23, 2023 |
| Sony          | SVE1513C5E                  | [bff960bae2](https://linux-hardware.org/?probe=bff960bae2) | Jan 23, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | [adcd91409c](https://linux-hardware.org/?probe=adcd91409c) | Jan 23, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | [e2fd85407d](https://linux-hardware.org/?probe=e2fd85407d) | Jan 23, 2023 |
| HP            | Laptop 15-dw0xxx            | [8460e3552a](https://linux-hardware.org/?probe=8460e3552a) | Jan 22, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [8941c8857e](https://linux-hardware.org/?probe=8941c8857e) | Jan 22, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [89c37ebdfa](https://linux-hardware.org/?probe=89c37ebdfa) | Jan 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | [b1ced07f7b](https://linux-hardware.org/?probe=b1ced07f7b) | Jan 22, 2023 |
| HP            | ProBook 450 G3              | [a3ce3d4a23](https://linux-hardware.org/?probe=a3ce3d4a23) | Jan 22, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | [09650cf189](https://linux-hardware.org/?probe=09650cf189) | Jan 22, 2023 |
| Dell          | Vostro 15 3515              | [51234f64dd](https://linux-hardware.org/?probe=51234f64dd) | Jan 21, 2023 |
| HP            | ProBook 4520s               | [ab9f74eb2c](https://linux-hardware.org/?probe=ab9f74eb2c) | Jan 21, 2023 |
| Acer          | Aspire F5-573G              | [68847eb1e6](https://linux-hardware.org/?probe=68847eb1e6) | Jan 21, 2023 |
| Toshiba       | Satellite Pro C850-10L      | [c1de4d0e2b](https://linux-hardware.org/?probe=c1de4d0e2b) | Jan 21, 2023 |
| Acer          | Aspire E5-575G              | [d020dd93e4](https://linux-hardware.org/?probe=d020dd93e4) | Jan 21, 2023 |
| MSI           | Prestige 15 A12SC           | [b368e80a36](https://linux-hardware.org/?probe=b368e80a36) | Jan 21, 2023 |
| Acer          | Aspire 7745G                | [98d6ab791c](https://linux-hardware.org/?probe=98d6ab791c) | Jan 21, 2023 |
| Acer          | Aspire A315-55G             | [b8660798ec](https://linux-hardware.org/?probe=b8660798ec) | Jan 20, 2023 |
| Toshiba       | Satellite Pro S500          | [f1e995c40b](https://linux-hardware.org/?probe=f1e995c40b) | Jan 20, 2023 |
| Toshiba       | Satellite Pro S500          | [16708a6471](https://linux-hardware.org/?probe=16708a6471) | Jan 20, 2023 |
| Acer          | Aspire E5-573G              | [c87740267f](https://linux-hardware.org/?probe=c87740267f) | Jan 20, 2023 |
| HP            | Pavilion dv7                | [0a4700fc75](https://linux-hardware.org/?probe=0a4700fc75) | Jan 20, 2023 |
| HUAWEI        | BOM-WXX9                    | [77ac7a6fc3](https://linux-hardware.org/?probe=77ac7a6fc3) | Jan 20, 2023 |
| Toshiba       | Satellite Pro S500          | [194f5676bd](https://linux-hardware.org/?probe=194f5676bd) | Jan 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [76ab21d17b](https://linux-hardware.org/?probe=76ab21d17b) | Jan 20, 2023 |
| Acer          | TravelMate 5735Z            | [712fdb1fa7](https://linux-hardware.org/?probe=712fdb1fa7) | Jan 20, 2023 |
| Acer          | TravelMate 5735Z            | [5b1b812b6e](https://linux-hardware.org/?probe=5b1b812b6e) | Jan 20, 2023 |
| Lenovo        | V15-IIL 82C5                | [8fc05186e7](https://linux-hardware.org/?probe=8fc05186e7) | Jan 20, 2023 |
| Dell          | XPS 13 9305                 | [5175eeeff4](https://linux-hardware.org/?probe=5175eeeff4) | Jan 20, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [c1169d55de](https://linux-hardware.org/?probe=c1169d55de) | Jan 19, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [2f712e8614](https://linux-hardware.org/?probe=2f712e8614) | Jan 19, 2023 |
| HP            | Laptop 15s-eq2xxx           | [bbc2c32eee](https://linux-hardware.org/?probe=bbc2c32eee) | Jan 19, 2023 |
| HP            | Pavilion x2 Detachable      | [8a13d31503](https://linux-hardware.org/?probe=8a13d31503) | Jan 19, 2023 |
| Apple         | MacBookPro11,1              | [67e4dd8f10](https://linux-hardware.org/?probe=67e4dd8f10) | Jan 19, 2023 |
| Insyde        | Braswell                    | [18526fdbe2](https://linux-hardware.org/?probe=18526fdbe2) | Jan 19, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [79ad95dada](https://linux-hardware.org/?probe=79ad95dada) | Jan 18, 2023 |
| HP            | Pavilion g6                 | [d1d3fadd60](https://linux-hardware.org/?probe=d1d3fadd60) | Jan 18, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [5a1bee99ee](https://linux-hardware.org/?probe=5a1bee99ee) | Jan 18, 2023 |
| ASUSTek       | TP301UJ                     | [4ee30e82ab](https://linux-hardware.org/?probe=4ee30e82ab) | Jan 18, 2023 |
| ASUSTek       | E200HA                      | [f17b69afa1](https://linux-hardware.org/?probe=f17b69afa1) | Jan 18, 2023 |
| ASUSTek       | X505BP                      | [ec4d653e2f](https://linux-hardware.org/?probe=ec4d653e2f) | Jan 17, 2023 |
| HP            | Laptop 15s-fq2xxx           | [133972f199](https://linux-hardware.org/?probe=133972f199) | Jan 17, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [44bf2e2ced](https://linux-hardware.org/?probe=44bf2e2ced) | Jan 17, 2023 |
| Acer          | Aspire E5-573G              | [9dba648ced](https://linux-hardware.org/?probe=9dba648ced) | Jan 17, 2023 |
| HUAWEI        | BOHB-WAX9                   | [b39c4fc9b7](https://linux-hardware.org/?probe=b39c4fc9b7) | Jan 16, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | [1c81e8c322](https://linux-hardware.org/?probe=1c81e8c322) | Jan 16, 2023 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | [5b56cf615b](https://linux-hardware.org/?probe=5b56cf615b) | Jan 16, 2023 |
| HP            | 15                          | [ae082994e2](https://linux-hardware.org/?probe=ae082994e2) | Jan 16, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [3891575263](https://linux-hardware.org/?probe=3891575263) | Jan 16, 2023 |
| Sony          | SVT1312M1ES                 | [9244e6ad96](https://linux-hardware.org/?probe=9244e6ad96) | Jan 16, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [b36eb94e80](https://linux-hardware.org/?probe=b36eb94e80) | Jan 16, 2023 |
| HP            | Pavilion Laptop 15-ck0xx    | [360173820c](https://linux-hardware.org/?probe=360173820c) | Jan 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [8fb168e741](https://linux-hardware.org/?probe=8fb168e741) | Jan 16, 2023 |
| Acer          | TravelMate P253             | [8f2246679e](https://linux-hardware.org/?probe=8f2246679e) | Jan 15, 2023 |
| HP            | Pavilion x2 Detachable      | [aa28cfacc3](https://linux-hardware.org/?probe=aa28cfacc3) | Jan 15, 2023 |
| HP            | Notebook                    | [be5a441ca6](https://linux-hardware.org/?probe=be5a441ca6) | Jan 15, 2023 |
| HP            | Pavilion x2 Detachable      | [5f9aaa4add](https://linux-hardware.org/?probe=5f9aaa4add) | Jan 15, 2023 |
| HP            | 15                          | [3faa6c9265](https://linux-hardware.org/?probe=3faa6c9265) | Jan 15, 2023 |
| HP            | Pavilion dv7                | [b3cbaccd13](https://linux-hardware.org/?probe=b3cbaccd13) | Jan 15, 2023 |
| HP            | Pavilion dv7                | [08bbff061e](https://linux-hardware.org/?probe=08bbff061e) | Jan 15, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [57d99b139f](https://linux-hardware.org/?probe=57d99b139f) | Jan 15, 2023 |
| Apple         | MacBook5,1                  | [51581940b0](https://linux-hardware.org/?probe=51581940b0) | Jan 15, 2023 |
| Acer          | TravelMate P253             | [15c26878b5](https://linux-hardware.org/?probe=15c26878b5) | Jan 15, 2023 |
| Dell          | Vostro 15 3515              | [fdf3113afb](https://linux-hardware.org/?probe=fdf3113afb) | Jan 15, 2023 |
| Kiano         | SlimNote 14,2               | [7596dc87b3](https://linux-hardware.org/?probe=7596dc87b3) | Jan 14, 2023 |
| ASUSTek       | N501VW                      | [5f9c2eebd4](https://linux-hardware.org/?probe=5f9c2eebd4) | Jan 14, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | [e5c76bef74](https://linux-hardware.org/?probe=e5c76bef74) | Jan 14, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | [2a08ec8e9e](https://linux-hardware.org/?probe=2a08ec8e9e) | Jan 14, 2023 |
| Olivetti      | Olibook P55-431W850-8G50... | [fe5c9c2425](https://linux-hardware.org/?probe=fe5c9c2425) | Jan 14, 2023 |
| Olivetti      | Olibook P55-431W850-8G50... | [649546bc61](https://linux-hardware.org/?probe=649546bc61) | Jan 14, 2023 |
| HP            | Notebook                    | [4c9b4e3b67](https://linux-hardware.org/?probe=4c9b4e3b67) | Jan 14, 2023 |
| HP            | Stream Notebook PC 13       | [b31d60976b](https://linux-hardware.org/?probe=b31d60976b) | Jan 14, 2023 |
| Toshiba       | Satellite Pro C850-1HD      | [d9ecac6816](https://linux-hardware.org/?probe=d9ecac6816) | Jan 14, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [86fff559f5](https://linux-hardware.org/?probe=86fff559f5) | Jan 14, 2023 |
| MSI           | PS63 Modern 8RC             | [e55e0d9d0a](https://linux-hardware.org/?probe=e55e0d9d0a) | Jan 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [1b50127412](https://linux-hardware.org/?probe=1b50127412) | Jan 14, 2023 |
| HUAWEI        | KPL-W0X                     | [d1175d8dba](https://linux-hardware.org/?probe=d1175d8dba) | Jan 14, 2023 |
| HP            | 250 G4 Notebook PC          | [dda4a9ae38](https://linux-hardware.org/?probe=dda4a9ae38) | Jan 14, 2023 |
| ASUSTek       | X550LD                      | [60b21ee22f](https://linux-hardware.org/?probe=60b21ee22f) | Jan 14, 2023 |
| Acer          | Swift SF314-511             | [8a4bbb603e](https://linux-hardware.org/?probe=8a4bbb603e) | Jan 14, 2023 |
| Acer          | Aspire E1-572G              | [360a177e77](https://linux-hardware.org/?probe=360a177e77) | Jan 14, 2023 |
| Dell          | XPS 9320                    | [b8de11c93d](https://linux-hardware.org/?probe=b8de11c93d) | Jan 13, 2023 |
| Acer          | Swift SF314-511             | [baa87ed4e0](https://linux-hardware.org/?probe=baa87ed4e0) | Jan 13, 2023 |
| Acer          | Swift SF314-511             | [cb94045e18](https://linux-hardware.org/?probe=cb94045e18) | Jan 13, 2023 |
| HP            | Pavilion Laptop 15-cs2xx... | [e7bab74a13](https://linux-hardware.org/?probe=e7bab74a13) | Jan 13, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | [b3fed0d61d](https://linux-hardware.org/?probe=b3fed0d61d) | Jan 13, 2023 |
| Unknown       | Unknown                     | [d0391da5d8](https://linux-hardware.org/?probe=d0391da5d8) | Jan 13, 2023 |
| Dell          | Precision 3551              | [66d483ea58](https://linux-hardware.org/?probe=66d483ea58) | Jan 13, 2023 |
| Acer          | Swift SF514-52T             | [feb261f5f5](https://linux-hardware.org/?probe=feb261f5f5) | Jan 13, 2023 |
| ASUSTek       | G56JR                       | [3665659d26](https://linux-hardware.org/?probe=3665659d26) | Jan 13, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [033a92981f](https://linux-hardware.org/?probe=033a92981f) | Jan 13, 2023 |
| HP            | EliteBook 840 G6            | [0559975d13](https://linux-hardware.org/?probe=0559975d13) | Jan 13, 2023 |
| ASUSTek       | N501VW                      | [176a3488df](https://linux-hardware.org/?probe=176a3488df) | Jan 12, 2023 |
| Google        | Sasuke                      | [7241244512](https://linux-hardware.org/?probe=7241244512) | Jan 12, 2023 |
| Lenovo        | IdeaPad Slim 9 14ITL5 82... | [a8d6ad51af](https://linux-hardware.org/?probe=a8d6ad51af) | Jan 12, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [fb5857252b](https://linux-hardware.org/?probe=fb5857252b) | Jan 12, 2023 |
| Acer          | Aspire V5-561G              | [1551c2b90c](https://linux-hardware.org/?probe=1551c2b90c) | Jan 12, 2023 |
| HP            | Pavilion dv6                | [43e7923f04](https://linux-hardware.org/?probe=43e7923f04) | Jan 11, 2023 |
| ASUSTek       | E200HA                      | [828a42310a](https://linux-hardware.org/?probe=828a42310a) | Jan 11, 2023 |
| HP            | ProBook 430 G5              | [6403930d67](https://linux-hardware.org/?probe=6403930d67) | Jan 11, 2023 |
| Google        | Sasuke                      | [99ba2827e0](https://linux-hardware.org/?probe=99ba2827e0) | Jan 10, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [c82f19c656](https://linux-hardware.org/?probe=c82f19c656) | Jan 10, 2023 |
| Toshiba       | Satellite Pro S500          | [2549187c34](https://linux-hardware.org/?probe=2549187c34) | Jan 10, 2023 |
| ASUSTek       | N501VW                      | [07d13b3b0b](https://linux-hardware.org/?probe=07d13b3b0b) | Jan 10, 2023 |
| ASUSTek       | X555YI                      | [4968e51e0b](https://linux-hardware.org/?probe=4968e51e0b) | Jan 10, 2023 |
| MSI           | Modern 15 A11M              | [5b55647c95](https://linux-hardware.org/?probe=5b55647c95) | Jan 10, 2023 |
| HP            | 15                          | [f6b287dae1](https://linux-hardware.org/?probe=f6b287dae1) | Jan 10, 2023 |
| HP            | Pavilion dv6                | [8f65765701](https://linux-hardware.org/?probe=8f65765701) | Jan 09, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [d6cac381fd](https://linux-hardware.org/?probe=d6cac381fd) | Jan 09, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [9f1f002f51](https://linux-hardware.org/?probe=9f1f002f51) | Jan 09, 2023 |
| Dell          | Precision 7540              | [77b35e556c](https://linux-hardware.org/?probe=77b35e556c) | Jan 09, 2023 |
| ASUSTek       | K50IJ                       | [9d476dfade](https://linux-hardware.org/?probe=9d476dfade) | Jan 09, 2023 |
| HP            | Pavilion Power Laptop 15... | [4d7677f391](https://linux-hardware.org/?probe=4d7677f391) | Jan 09, 2023 |
| HP            | Pavilion dv7                | [d3177dc8b3](https://linux-hardware.org/?probe=d3177dc8b3) | Jan 09, 2023 |
| HP            | Pavilion dv7                | [77590fdff4](https://linux-hardware.org/?probe=77590fdff4) | Jan 09, 2023 |
| Dell          | XPS 9320                    | [a58b8a72b7](https://linux-hardware.org/?probe=a58b8a72b7) | Jan 09, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Italy/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 474       | 10.63%  |
| Ubuntu 18.04                 | 294       | 6.59%   |
| Ubuntu 22.04                 | 269       | 6.03%   |
| Arch Rolling                 | 139       | 3.12%   |
| Debian 11                    | 109       | 2.44%   |
| OpenMandriva 4.2             | 107       | 2.4%    |
| OpenMandriva 4.3             | 101       | 2.26%   |
| Fedora 36                    | 92        | 2.06%   |
| Linux Mint 21.1              | 80        | 1.79%   |
| Arch                         | 75        | 1.68%   |
| Pop!_OS 22.04                | 71        | 1.59%   |
| Fedora 37                    | 71        | 1.59%   |
| Xubuntu 18.04                | 69        | 1.55%   |
| Ubuntu 22.10                 | 69        | 1.55%   |
| Ubuntu 19.10                 | 68        | 1.52%   |
| Zorin 16                     | 62        | 1.39%   |
| Xubuntu 20.04                | 61        | 1.37%   |
| Ubuntu 20.10                 | 61        | 1.37%   |
| Linux Mint 20.3              | 60        | 1.35%   |
| Ubuntu 21.10                 | 58        | 1.3%    |
| Ubuntu 19.04                 | 56        | 1.26%   |
| KDE neon 20.04               | 54        | 1.21%   |
| Linux Mint 21                | 53        | 1.19%   |
| EndeavourOS Rolling          | 51        | 1.14%   |
| Zorin 15                     | 49        | 1.1%    |
| OpenMandriva 23.03           | 49        | 1.1%    |
| Debian 10                    | 46        | 1.03%   |
| Fedora 35                    | 42        | 0.94%   |
| Ubuntu 18.10                 | 40        | 0.9%    |
| Kubuntu 22.04                | 40        | 0.9%    |
| Ubuntu 21.04                 | 39        | 0.87%   |
| OpenMandriva 23.01           | 37        | 0.83%   |
| Linux Mint 20.1              | 36        | 0.81%   |
| Pop!_OS 20.10                | 35        | 0.78%   |
| Linux Mint 20                | 35        | 0.78%   |
| Linux Mint 19.3              | 35        | 0.78%   |
| Kubuntu 20.04                | 35        | 0.78%   |
| Fedora 33                    | 35        | 0.78%   |
| Linux Mint 20.2              | 34        | 0.76%   |
| openSUSE Tumbleweed-XXXXXXXX | 32        | 0.72%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1392      | 33.02%  |
| Linux Mint    | 331       | 7.85%   |
| Fedora        | 312       | 7.4%    |
| OpenMandriva  | 308       | 7.31%   |
| Arch          | 208       | 4.93%   |
| Debian        | 193       | 4.58%   |
| Xubuntu       | 182       | 4.32%   |
| Pop!_OS       | 163       | 3.87%   |
| Manjaro       | 124       | 2.94%   |
| Kubuntu       | 120       | 2.85%   |
| Zorin         | 117       | 2.78%   |
| ROSA          | 88        | 2.09%   |
| KDE neon      | 74        | 1.76%   |
| Lubuntu       | 63        | 1.49%   |
| EndeavourOS   | 53        | 1.26%   |
| openSUSE      | 50        | 1.19%   |
| Elementary    | 41        | 0.97%   |
| Ubuntu MATE   | 38        | 0.9%    |
| Endless       | 38        | 0.9%    |
| LMDE          | 23        | 0.55%   |
| ArcoLinux     | 23        | 0.55%   |
| Ubuntu Unity  | 21        | 0.5%    |
| MX            | 21        | 0.5%    |
| Gentoo        | 21        | 0.5%    |
| BlackPanther  | 20        | 0.47%   |
| Kali          | 17        | 0.4%    |
| Ubuntu Budgie | 16        | 0.38%   |
| Clear Linux   | 16        | 0.38%   |
| SteamOS       | 14        | 0.33%   |
| Garuda Linux  | 14        | 0.33%   |
| Peppermint    | 11        | 0.26%   |
| Parrot        | 8         | 0.19%   |
| LinuxFX       | 7         | 0.17%   |
| Nobara        | 6         | 0.14%   |
| NixOS         | 5         | 0.12%   |
| Chrome OS     | 5         | 0.12%   |
| Xero          | 4         | 0.09%   |
| Slackware     | 4         | 0.09%   |
| Linux Lite    | 4         | 0.09%   |
| CentOS        | 4         | 0.09%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 102       | 2.08%   |
| 5.15.0-52-generic        | 98        | 2%      |
| 5.16.7-desktop-1omv4003  | 96        | 1.96%   |
| 5.4.0-42-generic         | 68        | 1.39%   |
| 5.15.0-56-generic        | 63        | 1.28%   |
| 6.2.6-desktop-1omv2390   | 48        | 0.98%   |
| 5.15.0-58-generic        | 43        | 0.88%   |
| 5.4.0-26-generic         | 41        | 0.84%   |
| 5.15.0-46-generic        | 41        | 0.84%   |
| 5.3.0-46-generic         | 40        | 0.82%   |
| 5.4.0-52-generic         | 36        | 0.73%   |
| 5.4.0-29-generic         | 36        | 0.73%   |
| 5.15.0-47-generic        | 35        | 0.71%   |
| 5.4.0-58-generic         | 33        | 0.67%   |
| 5.15.0-43-generic        | 33        | 0.67%   |
| 5.3.0-40-generic         | 32        | 0.65%   |
| 6.1.1-desktop-1omv2290   | 31        | 0.63%   |
| 5.3.0-42-generic         | 31        | 0.63%   |
| 5.4.0-48-generic         | 30        | 0.61%   |
| 5.15.0-41-generic        | 30        | 0.61%   |
| 6.0.2-arch1-1            | 28        | 0.57%   |
| 5.15.0-53-generic        | 27        | 0.55%   |
| 5.13.0-28-generic        | 27        | 0.55%   |
| 5.0.0-37-generic         | 27        | 0.55%   |
| 5.15.0-48-generic        | 25        | 0.51%   |
| 5.19.0-32-generic        | 24        | 0.49%   |
| 5.10.0-19-amd64          | 24        | 0.49%   |
| 5.3.0-51-generic         | 23        | 0.47%   |
| 5.19.0-23-generic        | 23        | 0.47%   |
| 5.19.0-21-generic        | 23        | 0.47%   |
| 5.15.0-60-generic        | 23        | 0.47%   |
| 5.10.0-21-amd64          | 23        | 0.47%   |
| 5.4.0-54-generic         | 22        | 0.45%   |
| 5.4.0-47-generic         | 22        | 0.45%   |
| 5.4.0-28-generic         | 22        | 0.45%   |
| 5.15.0-50-generic        | 21        | 0.43%   |
| 4.18.0-15-generic        | 21        | 0.43%   |
| 5.4.0-33-generic         | 20        | 0.41%   |
| 5.19.0-76051900-generic  | 20        | 0.41%   |
| 5.4.0-37-generic         | 19        | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 690       | 15.02%  |
| 5.15.0  | 501       | 10.91%  |
| 4.15.0  | 243       | 5.29%   |
| 5.3.0   | 224       | 4.88%   |
| 5.19.0  | 211       | 4.59%   |
| 5.8.0   | 201       | 4.38%   |
| 5.13.0  | 198       | 4.31%   |
| 5.11.0  | 167       | 3.64%   |
| 5.10.0  | 146       | 3.18%   |
| 5.0.0   | 113       | 2.46%   |
| 5.10.14 | 102       | 2.22%   |
| 5.16.7  | 98        | 2.13%   |
| 4.18.0  | 87        | 1.89%   |
| 6.2.6   | 60        | 1.31%   |
| 6.0.2   | 53        | 1.15%   |
| 4.19.0  | 45        | 0.98%   |
| 6.1.1   | 38        | 0.83%   |
| 5.19.16 | 29        | 0.63%   |
| 6.0.0   | 27        | 0.59%   |
| 6.2.0   | 26        | 0.57%   |
| 6.0.12  | 22        | 0.48%   |
| 6.1.0   | 21        | 0.46%   |
| 5.17.5  | 20        | 0.44%   |
| 4.18.16 | 19        | 0.41%   |
| 6.0.7   | 18        | 0.39%   |
| 6.0.6   | 18        | 0.39%   |
| 4.9.60  | 18        | 0.39%   |
| 4.9.20  | 17        | 0.37%   |
| 4.4.0   | 17        | 0.37%   |
| 5.17.1  | 14        | 0.3%    |
| 6.0.5   | 13        | 0.28%   |
| 6.0.9   | 12        | 0.26%   |
| 5.18.0  | 12        | 0.26%   |
| 6.2.9   | 11        | 0.24%   |
| 6.1.8   | 11        | 0.24%   |
| 6.0.10  | 11        | 0.24%   |
| 5.19.12 | 11        | 0.24%   |
| 5.14.0  | 11        | 0.24%   |
| 6.1.12  | 10        | 0.22%   |
| 6.0.11  | 10        | 0.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 736       | 16.22%  |
| 5.15    | 590       | 13%     |
| 5.19    | 316       | 6.96%   |
| 5.10    | 305       | 6.72%   |
| 5.3     | 249       | 5.49%   |
| 4.15    | 244       | 5.38%   |
| 5.8     | 241       | 5.31%   |
| 5.13    | 219       | 4.83%   |
| 6.0     | 206       | 4.54%   |
| 5.11    | 204       | 4.5%    |
| 6.2     | 151       | 3.33%   |
| 5.16    | 150       | 3.31%   |
| 6.1     | 144       | 3.17%   |
| 5.0     | 116       | 2.56%   |
| 4.18    | 109       | 2.4%    |
| 5.17    | 65        | 1.43%   |
| 4.9     | 62        | 1.37%   |
| 4.19    | 58        | 1.28%   |
| 5.14    | 56        | 1.23%   |
| 5.18    | 54        | 1.19%   |
| 5.9     | 46        | 1.01%   |
| 5.12    | 37        | 0.82%   |
| 5.6     | 34        | 0.75%   |
| 5.5     | 34        | 0.75%   |
| 6.3     | 30        | 0.66%   |
| 5.7     | 23        | 0.51%   |
| 4.4     | 18        | 0.4%    |
| 5.2     | 9         | 0.2%    |
| 4.13    | 6         | 0.13%   |
| 4.1     | 6         | 0.13%   |
| 5.1     | 4         | 0.09%   |
| 4.12    | 4         | 0.09%   |
| 4.20    | 3         | 0.07%   |
| 4.17    | 3         | 0.07%   |
| 4.16    | 2         | 0.04%   |
| 3.10    | 2         | 0.04%   |
| 4.14    | 1         | 0.02%   |
| 4.10    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 3839      | 94.72%  |
| i686   | 213       | 5.26%   |
| armv7l | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| GNOME             | 1861      | 43.85%  |
| KDE5              | 802       | 18.9%   |
| Unknown           | 406       | 9.57%   |
| XFCE              | 383       | 9.02%   |
| X-Cinnamon        | 265       | 6.24%   |
| MATE              | 111       | 2.62%   |
| LXQt              | 72        | 1.7%    |
| KDE               | 69        | 1.63%   |
| KDE4              | 50        | 1.18%   |
| Pantheon          | 41        | 0.97%   |
| Cinnamon          | 29        | 0.68%   |
| LXDE              | 27        | 0.64%   |
| Budgie            | 23        | 0.54%   |
| Unity             | 22        | 0.52%   |
| i3                | 15        | 0.35%   |
| GNOME Flashback   | 15        | 0.35%   |
| GNOME Classic     | 8         | 0.19%   |
| sway              | 6         | 0.14%   |
| Deepin            | 6         | 0.14%   |
| bspwm             | 5         | 0.12%   |
| Hyprland          | 4         | 0.09%   |
| dwm               | 4         | 0.09%   |
| xubuntu           | 2         | 0.05%   |
| qtile             | 2         | 0.05%   |
| openbox           | 2         | 0.05%   |
| Enlightenment     | 2         | 0.05%   |
| awesome           | 2         | 0.05%   |
| ubuntu:pika:GNOME | 1         | 0.02%   |
| ubuntu            | 1         | 0.02%   |
| Trinity           | 1         | 0.02%   |
| pika:GNOME        | 1         | 0.02%   |
| none+i3           | 1         | 0.02%   |
| none+bspwm        | 1         | 0.02%   |
| lightdm-xsession  | 1         | 0.02%   |
| icewm             | 1         | 0.02%   |
| gamescope         | 1         | 0.02%   |
| Cutefish          | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 3139      | 74.93%  |
| Wayland | 800       | 19.1%   |
| Unknown | 209       | 4.99%   |
| Tty     | 41        | 0.98%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1817      | 42.99%  |
| SDDM    | 752       | 17.79%  |
| GDM3    | 540       | 12.78%  |
| GDM     | 509       | 12.04%  |
| LightDM | 443       | 10.48%  |
| TDM     | 95        | 2.25%   |
| KDM     | 51        | 1.21%   |
| XDM     | 6         | 0.14%   |
| SLiM    | 6         | 0.14%   |
| LXDM    | 3         | 0.07%   |
| WDM     | 1         | 0.02%   |
| SLIMSKI | 1         | 0.02%   |
| MDM     | 1         | 0.02%   |
| Ly      | 1         | 0.02%   |
| GREETD  | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang         | Notebooks | Percent |
|--------------|-----------|---------|
| it_IT        | 2582      | 61.87%  |
| en_US        | 912       | 21.85%  |
| Unknown      | 433       | 10.38%  |
| en_GB        | 95        | 2.28%   |
| C            | 75        | 1.8%    |
| de_DE        | 13        | 0.31%   |
| fr_FR        | 9         | 0.22%   |
| es_ES        | 8         | 0.19%   |
| de_IT        | 8         | 0.19%   |
| ru_RU        | 5         | 0.12%   |
| POSIX        | 4         | 0.1%    |
| en_AG        | 4         | 0.1%    |
| it_IT@euro   | 3         | 0.07%   |
| en_AU        | 3         | 0.07%   |
| en_US.UTF8   | 2         | 0.05%   |
| en_IE        | 2         | 0.05%   |
| ro_RO        | 1         | 0.02%   |
| pt_BR        | 1         | 0.02%   |
| pl_PL        | 1         | 0.02%   |
| it_IT.UTF -8 | 1         | 0.02%   |
| it_CH        | 1         | 0.02%   |
| fur_IT       | 1         | 0.02%   |
| fr_BE        | 1         | 0.02%   |
| es_US        | 1         | 0.02%   |
| en_US@euro   | 1         | 0.02%   |
| en_US.utf-8  | 1         | 0.02%   |
| en_IN        | 1         | 0.02%   |
| de_CH        | 1         | 0.02%   |
| de_AT        | 1         | 0.02%   |
| C.UTF8       | 1         | 0.02%   |
| bg_BG        | 1         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 2186      | 52.9%   |
| BIOS | 1946      | 47.1%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 3153      | 75.83%  |
| Overlay  | 400       | 9.62%   |
| Btrfs    | 367       | 8.83%   |
| Unknown  | 103       | 2.48%   |
| Tmpfs    | 50        | 1.2%    |
| Xfs      | 31        | 0.75%   |
| Zfs      | 26        | 0.63%   |
| Ext2     | 11        | 0.26%   |
| F2fs     | 8         | 0.19%   |
| Ext3     | 5         | 0.12%   |
| XXX4     | 2         | 0.05%   |
| Reiserfs | 1         | 0.02%   |
| Jfs      | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1985      | 47.76%  |
| GPT     | 1730      | 41.63%  |
| MBR     | 441       | 10.61%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3614      | 87.63%  |
| Yes       | 510       | 12.37%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2747      | 66.43%  |
| Yes       | 1388      | 33.57%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 922       | 22.77%  |
| Lenovo              | 661       | 16.33%  |
| ASUSTek Computer    | 621       | 15.34%  |
| Acer                | 461       | 11.39%  |
| Dell                | 418       | 10.32%  |
| Toshiba             | 103       | 2.54%   |
| HUAWEI              | 101       | 2.49%   |
| Apple               | 98        | 2.42%   |
| Sony                | 91        | 2.25%   |
| MSI                 | 83        | 2.05%   |
| Samsung Electronics | 73        | 1.8%    |
| Fujitsu             | 40        | 0.99%   |
| Unknown             | 33        | 0.82%   |
| Mediacom            | 32        | 0.79%   |
| Packard Bell        | 30        | 0.74%   |
| Notebook            | 22        | 0.54%   |
| Chuwi               | 22        | 0.54%   |
| Teclast             | 20        | 0.49%   |
| Timi                | 18        | 0.44%   |
| Fujitsu Siemens     | 18        | 0.44%   |
| Microtech           | 16        | 0.4%    |
| TUXEDO              | 13        | 0.32%   |
| Valve               | 12        | 0.3%    |
| PC Specialist       | 12        | 0.3%    |
| SANTECH             | 8         | 0.2%    |
| Jumper              | 8         | 0.2%    |
| Google              | 8         | 0.2%    |
| TrekStor            | 7         | 0.17%   |
| eMachines           | 7         | 0.17%   |
| Olivetti            | 6         | 0.15%   |
| LG Electronics      | 5         | 0.12%   |
| Alienware           | 5         | 0.12%   |
| YASHI               | 3         | 0.07%   |
| TELECOMITALIA       | 3         | 0.07%   |
| System76            | 3         | 0.07%   |
| SiComputer          | 3         | 0.07%   |
| Razer               | 3         | 0.07%   |
| Onda TLC            | 3         | 0.07%   |
| Intel               | 3         | 0.07%   |
| YJKC                | 2         | 0.05%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| HP Pavilion dv6                       | 55        | 1.36%   |
| Unknown                               | 48        | 1.19%   |
| HP Notebook                           | 40        | 0.99%   |
| HP Pavilion 15                        | 27        | 0.67%   |
| HP Pavilion g6                        | 23        | 0.57%   |
| HP 255 G8 Notebook PC                 | 20        | 0.49%   |
| HUAWEI NBLK-WAX9X                     | 18        | 0.44%   |
| Mediacom SmartBook 14 FullHD - SB14UC | 17        | 0.42%   |
| HP 15                                 | 15        | 0.37%   |
| HP ENVY 15                            | 13        | 0.32%   |
| HP 255 G7 Notebook PC                 | 13        | 0.32%   |
| Dell XPS 15 7590                      | 13        | 0.32%   |
| Valve Jupiter                         | 12        | 0.3%    |
| HUAWEI KLVL-WXX9                      | 12        | 0.3%    |
| HP G62                                | 12        | 0.3%    |
| HP 250 G6 Notebook PC                 | 12        | 0.3%    |
| Apple MacBook4,1                      | 12        | 0.3%    |
| Lenovo IdeaPad 330S-15IKB 81F5        | 11        | 0.27%   |
| Lenovo IdeaPad 3 15ADA05 81W1         | 11        | 0.27%   |
| HP Pavilion x2 Detachable             | 11        | 0.27%   |
| HP 255 G6 Notebook PC                 | 11        | 0.27%   |
| Dell XPS 15 9570                      | 11        | 0.27%   |
| Acer Aspire 5750G                     | 11        | 0.27%   |
| HP Pavilion dv7                       | 10        | 0.25%   |
| Dell XPS 15 9560                      | 10        | 0.25%   |
| HUAWEI BOD-WXX9                       | 9         | 0.22%   |
| HP Laptop 15s-eq2xxx                  | 9         | 0.22%   |
| HP EliteBook 8440p                    | 9         | 0.22%   |
| HP Compaq 6730s                       | 9         | 0.22%   |
| Dell Inspiron 5570                    | 9         | 0.22%   |
| Acer Aspire A515-51G                  | 9         | 0.22%   |
| Acer Aspire A515-45                   | 9         | 0.22%   |
| Acer Aspire 5920G                     | 9         | 0.22%   |
| Lenovo V145-15AST 81MT                | 8         | 0.2%    |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY  | 8         | 0.2%    |
| Jumper EZbook                         | 8         | 0.2%    |
| HUAWEI BOHB-WAX9                      | 8         | 0.2%    |
| HP ProBook 450 G5                     | 8         | 0.2%    |
| HP Pavilion Notebook                  | 8         | 0.2%    |
| HP 250 G3                             | 8         | 0.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 317       | 7.83%   |
| Acer Aspire           | 307       | 7.58%   |
| HP Pavilion           | 247       | 6.1%    |
| Lenovo IdeaPad        | 168       | 4.15%   |
| Dell Latitude         | 159       | 3.93%   |
| HP EliteBook          | 108       | 2.67%   |
| Dell XPS              | 97        | 2.4%    |
| ASUS VivoBook         | 94        | 2.32%   |
| Toshiba Satellite     | 89        | 2.2%    |
| HP Laptop             | 88        | 2.17%   |
| HP ProBook            | 83        | 2.05%   |
| Dell Inspiron         | 78        | 1.93%   |
| HP Compaq             | 68        | 1.68%   |
| HP 255                | 60        | 1.48%   |
| HP 250                | 54        | 1.33%   |
| Unknown               | 48        | 1.19%   |
| HP Notebook           | 40        | 0.99%   |
| Fujitsu LIFEBOOK      | 38        | 0.94%   |
| Acer Swift            | 37        | 0.91%   |
| Acer TravelMate       | 35        | 0.86%   |
| Acer Extensa          | 33        | 0.82%   |
| Dell Vostro           | 32        | 0.79%   |
| Dell Precision        | 32        | 0.79%   |
| Lenovo ThinkBook      | 29        | 0.72%   |
| HP ENVY               | 24        | 0.59%   |
| Packard Bell EasyNote | 23        | 0.57%   |
| Mediacom SmartBook    | 20        | 0.49%   |
| ASUS ROG              | 20        | 0.49%   |
| HUAWEI NBLK-WAX9X     | 18        | 0.44%   |
| Apple MacBookPro11    | 18        | 0.44%   |
| MSI Modern            | 16        | 0.4%    |
| HP ZBook              | 15        | 0.37%   |
| HP Presario           | 15        | 0.37%   |
| HP 15                 | 15        | 0.37%   |
| HP OMEN               | 14        | 0.35%   |
| ASUS Zenbook          | 14        | 0.35%   |
| Lenovo Legion         | 13        | 0.32%   |
| Acer Nitro            | 13        | 0.32%   |
| Valve Jupiter         | 12        | 0.3%    |
| MSI Prestige          | 12        | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 348       | 8.59%   |
| 2019    | 344       | 8.5%    |
| 2021    | 326       | 8.05%   |
| 2018    | 318       | 7.85%   |
| 2013    | 273       | 6.74%   |
| 2017    | 272       | 6.72%   |
| 2016    | 245       | 6.05%   |
| 2011    | 241       | 5.95%   |
| 2008    | 241       | 5.95%   |
| 2012    | 238       | 5.88%   |
| 2010    | 237       | 5.85%   |
| 2015    | 230       | 5.68%   |
| 2014    | 225       | 5.56%   |
| 2009    | 182       | 4.49%   |
| 2007    | 122       | 3.01%   |
| 2022    | 105       | 2.59%   |
| 2006    | 64        | 1.58%   |
| 2005    | 23        | 0.57%   |
| Unknown | 6         | 0.15%   |
| 2023    | 5         | 0.12%   |
| 2004    | 3         | 0.07%   |
| 2003    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 4049      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 3685      | 89.94%  |
| Enabled  | 412       | 10.06%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 4033      | 99.6%   |
| Yes  | 16        | 0.4%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1153      | 28.11%  |
| 3.01-4.0    | 1017      | 24.79%  |
| 16.01-24.0  | 655       | 15.97%  |
| 8.01-16.0   | 640       | 15.6%   |
| 1.01-2.0    | 266       | 6.48%   |
| 32.01-64.0  | 184       | 4.49%   |
| 2.01-3.0    | 89        | 2.17%   |
| 0.51-1.0    | 45        | 1.1%    |
| 24.01-32.0  | 29        | 0.71%   |
| 64.01-256.0 | 21        | 0.51%   |
| 0.01-0.5    | 3         | 0.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1721      | 38.23%  |
| 2.01-3.0   | 1097      | 24.37%  |
| 4.01-8.0   | 575       | 12.77%  |
| 3.01-4.0   | 542       | 12.04%  |
| 0.51-1.0   | 367       | 8.15%   |
| 8.01-16.0  | 140       | 3.11%   |
| 0.01-0.5   | 47        | 1.04%   |
| 16.01-24.0 | 9         | 0.2%    |
| 24.01-32.0 | 2         | 0.04%   |
| 32.01-64.0 | 1         | 0.02%   |
| Unknown    | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3092      | 74.98%  |
| 2      | 895       | 21.7%   |
| 3      | 91        | 2.21%   |
| 0      | 31        | 0.75%   |
| 4      | 11        | 0.27%   |
| 6      | 2         | 0.05%   |
| 5      | 2         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2333      | 57.36%  |
| Yes       | 1734      | 42.64%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3226      | 79.32%  |
| No        | 841       | 20.68%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3964      | 97.8%   |
| No        | 89        | 2.2%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2977      | 72.57%  |
| No        | 1125      | 27.43%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Italy   | 4049      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Milan               | 624       | 13.55%  |
| Rome                | 471       | 10.23%  |
| Turin               | 156       | 3.39%   |
| Florence            | 83        | 1.8%    |
| Naples              | 82        | 1.78%   |
| Bologna             | 80        | 1.74%   |
| Rho                 | 70        | 1.52%   |
| Genoa               | 63        | 1.37%   |
| Padova              | 56        | 1.22%   |
| Palermo             | 51        | 1.11%   |
| Verona              | 48        | 1.04%   |
| Bari                | 45        | 0.98%   |
| Milano              | 44        | 0.96%   |
| Catania             | 41        | 0.89%   |
| Brescia             | 35        | 0.76%   |
| Trieste             | 30        | 0.65%   |
| Parma               | 30        | 0.65%   |
| Bergamo             | 28        | 0.61%   |
| Venice              | 27        | 0.59%   |
| Pisa                | 27        | 0.59%   |
| Bolzano             | 22        | 0.48%   |
| Modena              | 21        | 0.46%   |
| Casalecchio di Reno | 21        | 0.46%   |
| Trento              | 20        | 0.43%   |
| Monza               | 20        | 0.43%   |
| Perugia             | 19        | 0.41%   |
| Cagliari            | 19        | 0.41%   |
| Reggio Emilia       | 18        | 0.39%   |
| Sesto San Giovanni  | 17        | 0.37%   |
| Seregno             | 17        | 0.37%   |
| Udine               | 16        | 0.35%   |
| Taranto             | 15        | 0.33%   |
| Salerno             | 15        | 0.33%   |
| Pescara             | 15        | 0.33%   |
| Vicenza             | 14        | 0.3%    |
| Reggio Calabria     | 14        | 0.3%    |
| Mestre              | 13        | 0.28%   |
| Forlì              | 13        | 0.28%   |
| Novara              | 12        | 0.26%   |
| Legnano             | 12        | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 884       | 1178   | 17.78%  |
| WDC                         | 483       | 604    | 9.72%   |
| Seagate                     | 460       | 555    | 9.25%   |
| Toshiba                     | 336       | 429    | 6.76%   |
| Sandisk                     | 310       | 412    | 6.24%   |
| Unknown                     | 309       | 420    | 6.22%   |
| Kingston                    | 290       | 339    | 5.83%   |
| Crucial                     | 282       | 329    | 5.67%   |
| Hitachi                     | 227       | 275    | 4.57%   |
| SK hynix                    | 185       | 227    | 3.72%   |
| HGST                        | 179       | 234    | 3.6%    |
| Micron Technology           | 133       | 162    | 2.68%   |
| Intel                       | 119       | 151    | 2.39%   |
| KIOXIA                      | 59        | 71     | 1.19%   |
| Fujitsu                     | 46        | 54     | 0.93%   |
| Phison                      | 41        | 49     | 0.82%   |
| China                       | 40        | 45     | 0.8%    |
| Apple                       | 33        | 36     | 0.66%   |
| SPCC                        | 28        | 34     | 0.56%   |
| LITEON                      | 28        | 35     | 0.56%   |
| Transcend                   | 24        | 31     | 0.48%   |
| Intenso                     | 24        | 25     | 0.48%   |
| JMicron Technology          | 22        | 25     | 0.44%   |
| A-DATA Technology           | 19        | 23     | 0.38%   |
| Phison Electronics          | 18        | 21     | 0.36%   |
| Netac                       | 18        | 19     | 0.36%   |
| Kingston Technology Company | 17        | 19     | 0.34%   |
| Teclast                     | 16        | 21     | 0.32%   |
| Unknown                     | 16        | 22     | 0.32%   |
| KingDian                    | 15        | 20     | 0.3%    |
| PNY                         | 13        | 15     | 0.26%   |
| SABRENT                     | 12        | 12     | 0.24%   |
| Micron/Crucial Technology   | 12        | 17     | 0.24%   |
| Silicon Motion              | 11        | 15     | 0.22%   |
| Drevo                       | 11        | 12     | 0.22%   |
| SSSTC                       | 9         | 9      | 0.18%   |
| Patriot                     | 9         | 12     | 0.18%   |
| LITEONIT                    | 9         | 20     | 0.18%   |
| Lenovo                      | 8         | 8      | 0.16%   |
| Corsair                     | 8         | 9      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 80        | 1.55%   |
| Crucial CT500MX500SSD1 500GB                        | 69        | 1.34%   |
| Unknown MMC Card  32GB                              | 66        | 1.28%   |
| Toshiba MQ01ABF050 500GB                            | 61        | 1.18%   |
| Samsung SSD 860 EVO 500GB                           | 61        | 1.18%   |
| Samsung SSD 850 EVO 250GB                           | 50        | 0.97%   |
| HGST HTS545050A7E680 500GB                          | 50        | 0.97%   |
| Seagate ST500LT012-1DG142 500GB                     | 49        | 0.95%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 47        | 0.91%   |
| Seagate ST1000LM035-1RK172 1TB                      | 46        | 0.89%   |
| HGST HTS721010A9E630 1TB                            | 46        | 0.89%   |
| Samsung SSD 850 EVO 500GB                           | 41        | 0.8%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 39        | 0.76%   |
| Unknown MMC Card  64GB                              | 38        | 0.74%   |
| Crucial CT240BX500SSD1 240GB                        | 36        | 0.7%    |
| Kingston SA400S37480G 480GB SSD                     | 34        | 0.66%   |
| Samsung NVMe SSD Drive 512GB                        | 32        | 0.62%   |
| Toshiba MQ01ABD100 1TB                              | 30        | 0.58%   |
| Seagate ST9500325AS 500GB                           | 28        | 0.54%   |
| SanDisk NVMe SSD Drive 512GB                        | 28        | 0.54%   |
| Toshiba MQ04ABF100 1TB                              | 27        | 0.52%   |
| Crucial CT480BX500SSD1 480GB                        | 27        | 0.52%   |
| SanDisk SSD PLUS 240GB                              | 25        | 0.48%   |
| Samsung SSD 860 EVO 250GB                           | 25        | 0.48%   |
| Crucial CT1000MX500SSD1 1TB                         | 25        | 0.48%   |
| Samsung SSD 860 EVO 1TB                             | 23        | 0.45%   |
| Samsung NVMe SSD Drive 256GB                        | 22        | 0.43%   |
| SanDisk NVMe SSD Drive 256GB                        | 21        | 0.41%   |
| Kingston SA400S37120G 120GB SSD                     | 21        | 0.41%   |
| Hitachi HTS545050A7E380 500GB                       | 21        | 0.41%   |
| Unknown NCard  32GB                                 | 20        | 0.39%   |
| Unknown MMC Card  128GB                             | 20        | 0.39%   |
| HGST HTS541010A9E680 1TB                            | 20        | 0.39%   |
| WDC WD5000LPVX-22V0TT0 500GB                        | 19        | 0.37%   |
| SK hynix NVMe SSD Drive 512GB                       | 19        | 0.37%   |
| Kingston SV300S37A120G 120GB SSD                    | 19        | 0.37%   |
| Hitachi HTS545050B9A300 500GB                       | 19        | 0.37%   |
| Seagate M3 Portable 4TB                             | 18        | 0.35%   |
| Samsung SSD 840 EVO 250GB                           | 18        | 0.35%   |
| Unknown MMC Card  16GB                              | 17        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 439       | 524    | 28.51%  |
| WDC                 | 338       | 426    | 21.95%  |
| Toshiba             | 234       | 280    | 15.19%  |
| Hitachi             | 227       | 275    | 14.74%  |
| HGST                | 179       | 234    | 11.62%  |
| Fujitsu             | 46        | 54     | 2.99%   |
| Samsung Electronics | 42        | 53     | 2.73%   |
| Unknown             | 18        | 19     | 1.17%   |
| ASMT                | 3         | 3      | 0.19%   |
| SSK                 | 2         | 2      | 0.13%   |
| IBM/Hitachi         | 2         | 3      | 0.13%   |
| HGST HTS            | 2         | 2      | 0.13%   |
| USB3.0              | 1         | 1      | 0.06%   |
| StoreJet            | 1         | 1      | 0.06%   |
| Intenso             | 1         | 1      | 0.06%   |
| Inateck             | 1         | 1      | 0.06%   |
| Generic-            | 1         | 1      | 0.06%   |
| DAS                 | 1         | 4      | 0.06%   |
| ASMedia             | 1         | 1      | 0.06%   |
| Apple               | 1         | 1      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 450       | 585    | 26.32%  |
| Crucial             | 264       | 311    | 15.44%  |
| Kingston            | 220       | 255    | 12.87%  |
| SanDisk             | 174       | 221    | 10.18%  |
| Micron Technology   | 56        | 72     | 3.27%   |
| WDC                 | 48        | 61     | 2.81%   |
| SK hynix            | 46        | 51     | 2.69%   |
| China               | 39        | 44     | 2.28%   |
| Toshiba             | 27        | 42     | 1.58%   |
| Apple               | 25        | 27     | 1.46%   |
| Transcend           | 24        | 31     | 1.4%    |
| SPCC                | 24        | 29     | 1.4%    |
| LITEON              | 24        | 27     | 1.4%    |
| Intel               | 23        | 28     | 1.35%   |
| Intenso             | 20        | 20     | 1.17%   |
| Netac               | 17        | 18     | 0.99%   |
| Teclast             | 16        | 21     | 0.94%   |
| KingDian            | 15        | 20     | 0.88%   |
| A-DATA Technology   | 14        | 16     | 0.82%   |
| PNY                 | 12        | 13     | 0.7%    |
| Drevo               | 10        | 11     | 0.58%   |
| Patriot             | 9         | 12     | 0.53%   |
| LITEONIT            | 9         | 20     | 0.53%   |
| Unknown             | 9         | 15     | 0.53%   |
| Corsair             | 8         | 9      | 0.47%   |
| Microtech           | 7         | 17     | 0.41%   |
| GOODRAM             | 7         | 8      | 0.41%   |
| Dogfish             | 7         | 8      | 0.41%   |
| Verbatim            | 5         | 10     | 0.29%   |
| TCSUNBOW            | 5         | 5      | 0.29%   |
| KingSpec            | 5         | 6      | 0.29%   |
| FORESEE             | 5         | 5      | 0.29%   |
| External            | 5         | 6      | 0.29%   |
| Emtec               | 5         | 5      | 0.29%   |
| BAITITON            | 5         | 7      | 0.29%   |
| Team                | 4         | 4      | 0.23%   |
| OCZ                 | 4         | 4      | 0.23%   |
| Leven               | 4         | 4      | 0.23%   |
| Hewlett-Packard     | 4         | 5      | 0.23%   |
| TO Exter            | 3         | 3      | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 1615      | 2112   | 34.06%  |
| HDD     | 1493      | 1886   | 31.49%  |
| NVMe    | 1250      | 1726   | 26.37%  |
| MMC     | 306       | 429    | 6.45%   |
| Unknown | 77        | 92     | 1.62%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2820      | 3903   | 62.14%  |
| NVMe | 1234      | 1699   | 27.19%  |
| MMC  | 306       | 429    | 6.74%   |
| SAS  | 178       | 214    | 3.92%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2306      | 3053   | 75.76%  |
| 0.51-1.0   | 684       | 880    | 22.47%  |
| 1.01-2.0   | 46        | 57     | 1.51%   |
| 4.01-10.0  | 5         | 5      | 0.16%   |
| 3.01-4.0   | 3         | 3      | 0.1%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1282      | 29.92%  |
| 251-500        | 1098      | 25.62%  |
| 501-1000       | 476       | 11.11%  |
| 1-20           | 441       | 10.29%  |
| 51-100         | 348       | 8.12%   |
| 21-50          | 222       | 5.18%   |
| 1001-2000      | 200       | 4.67%   |
| Unknown        | 94        | 2.19%   |
| 2001-3000      | 63        | 1.47%   |
| More than 3000 | 61        | 1.42%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1939      | 43.55%  |
| 21-50          | 720       | 16.17%  |
| 101-250        | 598       | 13.43%  |
| 51-100         | 540       | 12.13%  |
| 251-500        | 321       | 7.21%   |
| 501-1000       | 154       | 3.46%   |
| Unknown        | 94        | 2.11%   |
| 1001-2000      | 50        | 1.12%   |
| More than 3000 | 19        | 0.43%   |
| 2001-3000      | 17        | 0.38%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| HGST HTS545050A7E680 500GB                     | 14        | 17     | 5.28%   |
| Seagate ST9500325AS 500GB                      | 7         | 7      | 2.64%   |
| Seagate ST1000LM035-1RK172 1TB                 | 7         | 9      | 2.64%   |
| Seagate ST500LT012-1DG142 500GB                | 6         | 6      | 2.26%   |
| Hitachi HTS725050A9A364 500GB                  | 6         | 6      | 2.26%   |
| WDC WD3200BEVT-60A23T0 320GB                   | 5         | 5      | 1.89%   |
| Toshiba MQ01ABF050 500GB                       | 5         | 5      | 1.89%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 5         | 5      | 1.89%   |
| Hitachi HTS545050A7E380 500GB                  | 5         | 5      | 1.89%   |
| HGST HTS721010A9E630 1TB                       | 5         | 5      | 1.89%   |
| Hitachi HTS547550A9E384 500GB                  | 4         | 4      | 1.51%   |
| HGST HTS725050A7E630 500GB                     | 4         | 5      | 1.51%   |
| Toshiba MQ01ABD100 1TB                         | 3         | 4      | 1.13%   |
| Toshiba MK5065GSX 500GB                        | 3         | 3      | 1.13%   |
| SK hynix HFS512G39TND-N210A 512GB SSD          | 3         | 3      | 1.13%   |
| Seagate ST9320325AS 320GB                      | 3         | 3      | 1.13%   |
| Seagate ST500LT012-9WS142 500GB                | 3         | 3      | 1.13%   |
| Seagate ST500LM012 HN-M500MBB 500GB            | 3         | 3      | 1.13%   |
| Micron Technology 1100_MTFDDAV512TBN 512GB SSD | 3         | 3      | 1.13%   |
| Hitachi HTS543232A7A384 320GB                  | 3         | 4      | 1.13%   |
| HGST HTS541075A9E680 752GB                     | 3         | 6      | 1.13%   |
| WDC WD5000LPCX-24C6HT0 500GB                   | 2         | 2      | 0.75%   |
| WDC WD5000BEVT-22ZAT0 500GB                    | 2         | 2      | 0.75%   |
| WDC WD10JPVX-22JC3T0 1TB                       | 2         | 3      | 0.75%   |
| WDC WD10JPCX-24UE4T0 1TB                       | 2         | 2      | 0.75%   |
| SK hynix HFS128G39TND-N210A 128GB SSD          | 2         | 2      | 0.75%   |
| Seagate ST9320423AS 320GB                      | 2         | 2      | 0.75%   |
| Seagate ST9250315AS 250GB                      | 2         | 2      | 0.75%   |
| Seagate ST9160310AS 160GB                      | 2         | 3      | 0.75%   |
| Seagate ST500LM021-1KJ152 500GB                | 2         | 2      | 0.75%   |
| Seagate ST320LT020-9YG142 320GB                | 2         | 2      | 0.75%   |
| Seagate ST1000LM014-1EJ164 1TB                 | 2         | 2      | 0.75%   |
| Samsung Electronics HM160HC 160GB              | 2         | 2      | 0.75%   |
| Kingston SA400S37240G 240GB SSD                | 2         | 2      | 0.75%   |
| Hitachi HTS547575A9E384 752GB                  | 2         | 2      | 0.75%   |
| Hitachi HTS547564A9E384 640GB                  | 2         | 2      | 0.75%   |
| Hitachi HTS545032B9A300 320GB                  | 2         | 2      | 0.75%   |
| Hitachi HTS543225L9A300 250GB                  | 2         | 2      | 0.75%   |
| Hitachi HTS542516K9SA00 160GB                  | 2         | 2      | 0.75%   |
| HGST HTS541010A9E680 1TB                       | 2         | 2      | 0.75%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 57        | 60     | 21.51%  |
| Hitachi                     | 47        | 48     | 17.74%  |
| WDC                         | 31        | 36     | 11.7%   |
| Toshiba                     | 31        | 32     | 11.7%   |
| HGST                        | 30        | 37     | 11.32%  |
| Samsung Electronics         | 11        | 11     | 4.15%   |
| SK hynix                    | 9         | 11     | 3.4%    |
| Crucial                     | 8         | 8      | 3.02%   |
| Micron Technology           | 7         | 7      | 2.64%   |
| Kingston                    | 5         | 5      | 1.89%   |
| Intel                       | 5         | 7      | 1.89%   |
| Fujitsu                     | 5         | 5      | 1.89%   |
| SanDisk                     | 3         | 3      | 1.13%   |
| Drevo                       | 2         | 2      | 0.75%   |
| Yangtze Memory Technologies | 1         | 1      | 0.38%   |
| WINTEC                      | 1         | 1      | 0.38%   |
| WDC WDS2                    | 1         | 1      | 0.38%   |
| Unknown                     | 1         | 1      | 0.38%   |
| Transcend                   | 1         | 2      | 0.38%   |
| Teclast                     | 1         | 1      | 0.38%   |
| TCSUNBOW                    | 1         | 1      | 0.38%   |
| SSSTC                       | 1         | 1      | 0.38%   |
| NGFF                        | 1         | 1      | 0.38%   |
| LITEON                      | 1         | 1      | 0.38%   |
| KingSpec                    | 1         | 1      | 0.38%   |
| KingDian                    | 1         | 1      | 0.38%   |
| BAITITON                    | 1         | 3      | 0.38%   |
| A-DATA Technology           | 1         | 1      | 0.38%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 57        | 60     | 28.08%  |
| Hitachi             | 47        | 48     | 23.15%  |
| WDC                 | 30        | 35     | 14.78%  |
| HGST                | 30        | 37     | 14.78%  |
| Toshiba             | 29        | 30     | 14.29%  |
| Fujitsu             | 5         | 5      | 2.46%   |
| Samsung Electronics | 4         | 4      | 1.97%   |
| Unknown             | 1         | 1      | 0.49%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 202       | 220    | 76.52%  |
| SSD  | 55        | 58     | 20.83%  |
| NVMe | 7         | 11     | 2.65%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-26A0RT0 500GB                     | 1         | 1      | 11.11%  |
| WDC WD5000BEVT-22A0RT0 500GB                     | 1         | 1      | 11.11%  |
| WDC WD10JPVX-60JC3T0 1TB                         | 1         | 1      | 11.11%  |
| WDC PC SN520 SDAPNUW-256G-1102 256GB             | 1         | 1      | 11.11%  |
| Toshiba MK3265GSX 320GB                          | 1         | 1      | 11.11%  |
| Seagate ST9500420AS 500GB                        | 1         | 3      | 11.11%  |
| Seagate ST2000LX001-1RG174 2TB                   | 1         | 1      | 11.11%  |
| Samsung Electronics MZNTY128HDHP-00000 128GB SSD | 1         | 1      | 11.11%  |
| Hitachi HTS545050A7E380 500GB                    | 1         | 1      | 11.11%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 4      | 44.44%  |
| Seagate             | 2         | 4      | 22.22%  |
| Toshiba             | 1         | 1      | 11.11%  |
| Samsung Electronics | 1         | 1      | 11.11%  |
| Hitachi             | 1         | 1      | 11.11%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2378      | 3668   | 55.2%   |
| Works    | 1658      | 2277   | 38.49%  |
| Malfunc  | 263       | 289    | 6.1%    |
| Failed   | 9         | 11     | 0.21%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2857      | 61.36%  |
| AMD                              | 467       | 10.03%  |
| Samsung Electronics              | 434       | 9.32%   |
| SanDisk                          | 205       | 4.4%    |
| SK hynix                         | 130       | 2.79%   |
| Kingston Technology Company      | 86        | 1.85%   |
| Micron Technology                | 79        | 1.7%    |
| Toshiba America Info Systems     | 74        | 1.59%   |
| KIOXIA                           | 65        | 1.4%    |
| Phison Electronics               | 57        | 1.22%   |
| Nvidia                           | 48        | 1.03%   |
| Micron/Crucial Technology        | 28        | 0.6%    |
| Silicon Integrated Systems [SiS] | 25        | 0.54%   |
| Solid State Storage Technology   | 13        | 0.28%   |
| Silicon Motion                   | 13        | 0.28%   |
| Union Memory (Shenzhen)          | 12        | 0.26%   |
| ADATA Technology                 | 8         | 0.17%   |
| VIA Technologies                 | 7         | 0.15%   |
| Lite-On Technology               | 7         | 0.15%   |
| Lenovo                           | 7         | 0.15%   |
| Apple                            | 7         | 0.15%   |
| Yangtze Memory Technologies      | 4         | 0.09%   |
| MAXIO Technology (Hangzhou)      | 4         | 0.09%   |
| Silicon Image                    | 3         | 0.06%   |
| Shenzhen Longsys Electronics     | 3         | 0.06%   |
| Seagate Technology               | 3         | 0.06%   |
| ASMedia Technology               | 3         | 0.06%   |
| Realtek Semiconductor            | 2         | 0.04%   |
| JMicron Technology               | 2         | 0.04%   |
| O2 Micro                         | 1         | 0.02%   |
| Marvell Technology Group         | 1         | 0.02%   |
| Unknown                          | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 382       | 7.58%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 339       | 6.73%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 265       | 5.26%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 235       | 4.67%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 214       | 4.25%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 212       | 4.21%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 200       | 3.97%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 159       | 3.16%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 126       | 2.5%    |
| Samsung NVMe SSD Controller 980                                                  | 125       | 2.48%   |
| Intel Volume Management Device NVMe RAID Controller                              | 112       | 2.22%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 112       | 2.22%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 108       | 2.14%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 108       | 2.14%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 100       | 1.99%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 92        | 1.83%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 82        | 1.63%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 77        | 1.53%   |
| Intel Comet Lake SATA AHCI Controller                                            | 62        | 1.23%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 58        | 1.15%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 55        | 1.09%   |
| Intel SSD 660P Series                                                            | 54        | 1.07%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 50        | 0.99%   |
| Micron NVMe Storage Controller                                                   | 50        | 0.99%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 48        | 0.95%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 47        | 0.93%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 46        | 0.91%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 46        | 0.91%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 44        | 0.87%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 42        | 0.83%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 42        | 0.83%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 41        | 0.81%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 40        | 0.79%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 39        | 0.77%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 39        | 0.77%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 36        | 0.71%   |
| Intel Tiger Lake-LP SATA Controller                                              | 35        | 0.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 35        | 0.69%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 33        | 0.66%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 31        | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 2857      | 58.9%   |
| NVMe | 1242      | 25.6%   |
| IDE  | 396       | 8.16%   |
| RAID | 356       | 7.34%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 3343      | 82.56%  |
| AMD          | 702       | 17.34%  |
| CentaurHauls | 2         | 0.05%   |
| ARM          | 1         | 0.02%   |
| Unknown      | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 87        | 2.15%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 68        | 1.68%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 66        | 1.63%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 59        | 1.46%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 54        | 1.33%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 52        | 1.28%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 50        | 1.23%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 48        | 1.18%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 47        | 1.16%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 46        | 1.14%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 46        | 1.14%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 45        | 1.11%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 42        | 1.04%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 41        | 1.01%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 39        | 0.96%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 38        | 0.94%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 37        | 0.91%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 36        | 0.89%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 35        | 0.86%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 35        | 0.86%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 30        | 0.74%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 29        | 0.72%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 29        | 0.72%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 28        | 0.69%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 28        | 0.69%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 28        | 0.69%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 27        | 0.67%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 27        | 0.67%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 26        | 0.64%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 26        | 0.64%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 25        | 0.62%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 25        | 0.62%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 25        | 0.62%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 24        | 0.59%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 24        | 0.59%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 24        | 0.59%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 24        | 0.59%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 24        | 0.59%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 24        | 0.59%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 23        | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 996       | 24.59%  |
| Intel Core i5           | 785       | 19.38%  |
| Other                   | 300       | 7.41%   |
| Intel Core 2 Duo        | 291       | 7.19%   |
| Intel Core i3           | 285       | 7.04%   |
| Intel Celeron           | 248       | 6.12%   |
| Intel Atom              | 170       | 4.2%    |
| AMD Ryzen 7             | 143       | 3.53%   |
| AMD Ryzen 5             | 142       | 3.51%   |
| Intel Pentium           | 51        | 1.26%   |
| AMD E1                  | 47        | 1.16%   |
| Intel Pentium Dual-Core | 43        | 1.06%   |
| Intel Pentium Dual      | 37        | 0.91%   |
| Intel Genuine           | 35        | 0.86%   |
| Intel Core 2            | 33        | 0.81%   |
| AMD A4                  | 33        | 0.81%   |
| AMD A10                 | 31        | 0.77%   |
| AMD A8                  | 30        | 0.74%   |
| AMD A6                  | 30        | 0.74%   |
| AMD Ryzen 3             | 26        | 0.64%   |
| AMD Ryzen 9             | 22        | 0.54%   |
| AMD E2                  | 22        | 0.54%   |
| Intel Core i9           | 20        | 0.49%   |
| Intel Pentium M         | 16        | 0.4%    |
| AMD Ryzen 7 PRO         | 16        | 0.4%    |
| Intel Pentium Silver    | 15        | 0.37%   |
| AMD Turion 64 X2 Mobile | 15        | 0.37%   |
| Intel Celeron M         | 13        | 0.32%   |
| AMD Sempron             | 13        | 0.32%   |
| AMD Ryzen 5 PRO         | 11        | 0.27%   |
| Intel Celeron Dual-Core | 10        | 0.25%   |
| AMD E                   | 10        | 0.25%   |
| AMD Mobile Sempron      | 9         | 0.22%   |
| AMD A12                 | 9         | 0.22%   |
| Intel Core m3           | 8         | 0.2%    |
| AMD Athlon II           | 7         | 0.17%   |
| Intel Core M            | 6         | 0.15%   |
| Intel Core Duo          | 5         | 0.12%   |
| AMD C-60                | 5         | 0.12%   |
| AMD Turion 64 Mobile    | 4         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 2069      | 51.05%  |
| 4       | 1330      | 32.82%  |
| 6       | 218       | 5.38%   |
| 8       | 200       | 4.93%   |
| 1       | 169       | 4.17%   |
| 14      | 30        | 0.74%   |
| 10      | 24        | 0.59%   |
| 12      | 10        | 0.25%   |
| 16      | 1         | 0.02%   |
| 5       | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 4049      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 2817      | 69.45%  |
| 1       | 1236      | 30.47%  |
| 4       | 2         | 0.05%   |
| Unknown | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3924      | 96.79%  |
| 32-bit         | 101       | 2.49%   |
| Unknown        | 29        | 0.72%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 927       | 22.06%  |
| 0x306a9    | 213       | 5.07%   |
| 0x206a7    | 207       | 4.93%   |
| 0x1067a    | 146       | 3.47%   |
| 0x40651    | 143       | 3.4%    |
| 0x806ea    | 140       | 3.33%   |
| 0x806ec    | 132       | 3.14%   |
| 0x806c1    | 126       | 3%      |
| 0x406e3    | 125       | 2.97%   |
| 0x806e9    | 104       | 2.48%   |
| 0x6fd      | 95        | 2.26%   |
| 0x20655    | 92        | 2.19%   |
| 0x906ea    | 88        | 2.09%   |
| 0x306c3    | 87        | 2.07%   |
| 0x306d4    | 83        | 1.98%   |
| 0x10676    | 72        | 1.71%   |
| 0x08108109 | 67        | 1.59%   |
| 0x706e5    | 57        | 1.36%   |
| 0x406c3    | 56        | 1.33%   |
| 0x806eb    | 50        | 1.19%   |
| 0x906e9    | 48        | 1.14%   |
| 0x30678    | 47        | 1.12%   |
| 0x20652    | 47        | 1.12%   |
| 0x08608103 | 46        | 1.09%   |
| 0xa0652    | 44        | 1.05%   |
| 0x0a50000c | 44        | 1.05%   |
| 0x06006705 | 43        | 1.02%   |
| 0x706a8    | 40        | 0.95%   |
| 0x106ca    | 40        | 0.95%   |
| 0x406c4    | 39        | 0.93%   |
| 0x706a1    | 36        | 0.86%   |
| 0x506e3    | 32        | 0.76%   |
| 0x506c9    | 32        | 0.76%   |
| 0x07030105 | 30        | 0.71%   |
| 0x08600106 | 29        | 0.69%   |
| 0x08600104 | 28        | 0.67%   |
| 0x906a3    | 27        | 0.64%   |
| 0x106c2    | 27        | 0.64%   |
| 0x08108102 | 27        | 0.64%   |
| 0x0700010f | 25        | 0.59%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 710       | 17.52%  |
| Haswell          | 304       | 7.5%    |
| IvyBridge        | 267       | 6.59%   |
| Penryn           | 264       | 6.52%   |
| SandyBridge      | 253       | 6.24%   |
| Skylake          | 205       | 5.06%   |
| Core             | 192       | 4.74%   |
| TigerLake        | 174       | 4.29%   |
| Silvermont       | 174       | 4.29%   |
| Westmere         | 164       | 4.05%   |
| Unknown          | 134       | 3.31%   |
| Broadwell        | 110       | 2.71%   |
| Zen+             | 109       | 2.69%   |
| Goldmont plus    | 96        | 2.37%   |
| Excavator        | 96        | 2.37%   |
| IceLake          | 84        | 2.07%   |
| Bonnell          | 82        | 2.02%   |
| Zen 2            | 79        | 1.95%   |
| Zen 3            | 67        | 1.65%   |
| CometLake        | 63        | 1.55%   |
| P6               | 59        | 1.46%   |
| Alderlake Hybrid | 44        | 1.09%   |
| Puma             | 42        | 1.04%   |
| Jaguar           | 42        | 1.04%   |
| Goldmont         | 42        | 1.04%   |
| K8 Hammer        | 38        | 0.94%   |
| Bobcat           | 31        | 0.77%   |
| Zen              | 24        | 0.59%   |
| K10              | 21        | 0.52%   |
| Nehalem          | 20        | 0.49%   |
| K8 & K10 hybrid  | 17        | 0.42%   |
| K10 Llano        | 15        | 0.37%   |
| Steamroller      | 13        | 0.32%   |
| Piledriver       | 9         | 0.22%   |
| Tremont          | 5         | 0.12%   |
| NetBurst         | 3         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2936      | 56.81%  |
| Nvidia                           | 1190      | 23.03%  |
| AMD                              | 1021      | 19.76%  |
| Silicon Integrated Systems [SiS] | 15        | 0.29%   |
| VIA Technologies                 | 5         | 0.1%    |
| S3 Graphics                      | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 250       | 4.62%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 223       | 4.12%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 176       | 3.25%   |
| Intel UHD Graphics 620                                                                   | 173       | 3.2%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 161       | 2.97%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 147       | 2.72%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 144       | 2.66%   |
| Intel HD Graphics 620                                                                    | 120       | 2.22%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 118       | 2.18%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 112       | 2.07%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 112       | 2.07%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 111       | 2.05%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 106       | 1.96%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 106       | 1.96%   |
| Intel Core Processor Integrated Graphics Controller                                      | 96        | 1.77%   |
| Intel HD Graphics 5500                                                                   | 93        | 1.72%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 81        | 1.5%    |
| AMD Renoir                                                                               | 77        | 1.42%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 75        | 1.39%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 75        | 1.39%   |
| AMD Lucienne                                                                             | 74        | 1.37%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 69        | 1.27%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 65        | 1.2%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 63        | 1.16%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 62        | 1.15%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 57        | 1.05%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 55        | 1.02%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 55        | 1.02%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 54        | 1%      |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 49        | 0.91%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 46        | 0.85%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 45        | 0.83%   |
| Intel HD Graphics 630                                                                    | 44        | 0.81%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 43        | 0.79%   |
| Nvidia GP108M [GeForce MX150]                                                            | 43        | 0.79%   |
| Intel HD Graphics 530                                                                    | 40        | 0.74%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 40        | 0.74%   |
| Nvidia GM108M [GeForce MX130]                                                            | 37        | 0.68%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 37        | 0.68%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 36        | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 1860      | 45.82%  |
| Intel + Nvidia  | 881       | 21.7%   |
| 1 x AMD         | 692       | 17.05%  |
| 1 x Nvidia      | 249       | 6.13%   |
| Intel + AMD     | 179       | 4.41%   |
| 2 x AMD         | 96        | 2.37%   |
| AMD + Nvidia    | 58        | 1.43%   |
| 1 x SiS         | 15        | 0.37%   |
| 2 x Intel       | 14        | 0.34%   |
| Other           | 5         | 0.12%   |
| 1 x VIA         | 5         | 0.12%   |
| 2 x Nvidia      | 4         | 0.1%    |
| 1 x S3 Graphics | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 3466      | 84.5%   |
| Proprietary | 530       | 12.92%  |
| Unknown     | 106       | 2.58%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2520      | 60.61%  |
| 0.01-0.5   | 584       | 14.05%  |
| 1.01-2.0   | 538       | 12.94%  |
| 0.51-1.0   | 277       | 6.66%   |
| 3.01-4.0   | 168       | 4.04%   |
| 5.01-6.0   | 41        | 0.99%   |
| 7.01-8.0   | 20        | 0.48%   |
| 2.01-3.0   | 9         | 0.22%   |
| 8.01-16.0  | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 841       | 19.14%  |
| Chimei Innolux          | 648       | 14.75%  |
| BOE                     | 579       | 13.18%  |
| LG Display              | 577       | 13.13%  |
| Samsung Electronics     | 503       | 11.45%  |
| Chi Mei Optoelectronics | 133       | 3.03%   |
| Sharp                   | 111       | 2.53%   |
| Apple                   | 95        | 2.16%   |
| Goldstar                | 78        | 1.78%   |
| Hewlett-Packard         | 70        | 1.59%   |
| Philips                 | 67        | 1.53%   |
| LG Philips              | 65        | 1.48%   |
| PANDA                   | 57        | 1.3%    |
| Lenovo                  | 55        | 1.25%   |
| Dell                    | 49        | 1.12%   |
| Ancor Communications    | 49        | 1.12%   |
| Acer                    | 36        | 0.82%   |
| HannStar                | 34        | 0.77%   |
| InfoVision              | 32        | 0.73%   |
| BenQ                    | 31        | 0.71%   |
| Sony                    | 26        | 0.59%   |
| AOC                     | 23        | 0.52%   |
| CPT                     | 22        | 0.5%    |
| CSO                     | 21        | 0.48%   |
| Toshiba                 | 14        | 0.32%   |
| Quanta Display          | 13        | 0.3%    |
| LGD                     | 13        | 0.3%    |
| ASUSTek Computer        | 10        | 0.23%   |
| Valve                   | 9         | 0.2%    |
| MSI                     | 9         | 0.2%    |
| TMX                     | 8         | 0.18%   |
| Seiko/Epson             | 8         | 0.18%   |
| InnoLux Display         | 6         | 0.14%   |
| Vestel Elektronik       | 5         | 0.11%   |
| Panasonic               | 5         | 0.11%   |
| Iiyama                  | 5         | 0.11%   |
| Eizo                    | 5         | 0.11%   |
| Tianma XM               | 4         | 0.09%   |
| Nvidia                  | 4         | 0.09%   |
| Unknown                 | 3         | 0.07%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 67        | 1.51%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 35        | 0.79%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 34        | 0.77%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 32        | 0.72%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 32        | 0.72%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 32        | 0.72%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 31        | 0.7%    |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 29        | 0.65%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 28        | 0.63%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 28        | 0.63%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 26        | 0.59%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 25        | 0.56%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 23        | 0.52%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 23        | 0.52%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 22        | 0.5%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch     | 21        | 0.47%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 21        | 0.47%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 21        | 0.47%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 21        | 0.47%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 20        | 0.45%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 18        | 0.41%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 18        | 0.41%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 18        | 0.41%   |
| LG Display LCD Monitor LGD046F 1920x1080 350x190mm 15.7-inch             | 17        | 0.38%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 17        | 0.38%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                 | 15        | 0.34%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch     | 14        | 0.32%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch     | 14        | 0.32%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch              | 14        | 0.32%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 14        | 0.32%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 14        | 0.32%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 13        | 0.29%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch          | 13        | 0.29%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 13        | 0.29%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 13        | 0.29%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                    | 13        | 0.29%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 13        | 0.29%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 13        | 0.29%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 12        | 0.27%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 12        | 0.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1647      | 39.45%  |
| 1366x768 (WXGA)    | 1402      | 33.58%  |
| 1280x800 (WXGA)    | 292       | 6.99%   |
| 1600x900 (HD+)     | 146       | 3.5%    |
| 3840x2160 (4K)     | 132       | 3.16%   |
| 1440x900 (WXGA+)   | 69        | 1.65%   |
| 2560x1440 (QHD)    | 68        | 1.63%   |
| 1920x1200 (WUXGA)  | 65        | 1.56%   |
| 1024x600           | 60        | 1.44%   |
| 1680x1050 (WSXGA+) | 36        | 0.86%   |
| 2160x1440          | 33        | 0.79%   |
| 2560x1600          | 31        | 0.74%   |
| 1280x1024 (SXGA)   | 24        | 0.57%   |
| 2880x1800          | 23        | 0.55%   |
| 3840x2400          | 16        | 0.38%   |
| 2560x1080          | 14        | 0.34%   |
| 1360x768           | 14        | 0.34%   |
| 800x1280           | 10        | 0.24%   |
| 3440x1440          | 10        | 0.24%   |
| 3000x2000          | 8         | 0.19%   |
| 3200x1800 (QHD+)   | 7         | 0.17%   |
| 1024x768 (XGA)     | 7         | 0.17%   |
| 3072x1920          | 5         | 0.12%   |
| 2520x1680          | 5         | 0.12%   |
| 1920x1280          | 5         | 0.12%   |
| 2240x1400          | 4         | 0.1%    |
| 1920x540           | 4         | 0.1%    |
| Unknown            | 4         | 0.1%    |
| 3840x1080          | 3         | 0.07%   |
| 1400x1050          | 3         | 0.07%   |
| 3840x1600          | 2         | 0.05%   |
| 3456x2160          | 2         | 0.05%   |
| 2880x1920          | 2         | 0.05%   |
| 2880x1620          | 2         | 0.05%   |
| 2288x1287          | 2         | 0.05%   |
| 1680x945           | 2         | 0.05%   |
| 1600x1200          | 2         | 0.05%   |
| 1280x960           | 2         | 0.05%   |
| 1280x720 (HD)      | 2         | 0.05%   |
| 3840x1200          | 1         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 2243      | 51.09%  |
| 13      | 536       | 12.21%  |
| 14      | 385       | 8.77%   |
| 17      | 207       | 4.72%   |
| 24      | 134       | 3.05%   |
| 12      | 122       | 2.78%   |
| 27      | 121       | 2.76%   |
| 23      | 97        | 2.21%   |
| 21      | 79        | 1.8%    |
| 11      | 67        | 1.53%   |
| 10      | 66        | 1.5%    |
| Unknown | 61        | 1.39%   |
| 16      | 47        | 1.07%   |
| 19      | 29        | 0.66%   |
| 18      | 26        | 0.59%   |
| 22      | 18        | 0.41%   |
| 34      | 17        | 0.39%   |
| 31      | 15        | 0.34%   |
| 40      | 14        | 0.32%   |
| 20      | 14        | 0.32%   |
| 84      | 11        | 0.25%   |
| 54      | 10        | 0.23%   |
| 7       | 9         | 0.21%   |
| 32      | 7         | 0.16%   |
| 25      | 7         | 0.16%   |
| 8       | 6         | 0.14%   |
| 72      | 5         | 0.11%   |
| 65      | 4         | 0.09%   |
| 35      | 4         | 0.09%   |
| 58      | 3         | 0.07%   |
| 52      | 3         | 0.07%   |
| 48      | 3         | 0.07%   |
| 47      | 3         | 0.07%   |
| 26      | 3         | 0.07%   |
| 142     | 2         | 0.05%   |
| 46      | 2         | 0.05%   |
| 37      | 2         | 0.05%   |
| 49      | 1         | 0.02%   |
| 42      | 1         | 0.02%   |
| 39      | 1         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 2864      | 65.63%  |
| 201-300        | 548       | 12.56%  |
| 501-600        | 333       | 7.63%   |
| 351-400        | 268       | 6.14%   |
| 401-500        | 150       | 3.44%   |
| Unknown        | 61        | 1.4%    |
| 601-700        | 30        | 0.69%   |
| 1001-1500      | 28        | 0.64%   |
| 701-800        | 25        | 0.57%   |
| 801-900        | 21        | 0.48%   |
| 1501-2000      | 16        | 0.37%   |
| 1-100          | 10        | 0.23%   |
| 101-200        | 7         | 0.16%   |
| More than 2000 | 2         | 0.05%   |
| 901-1000       | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 3249      | 81.8%   |
| 16/10   | 529       | 13.32%  |
| 3/2     | 62        | 1.56%   |
| Unknown | 46        | 1.16%   |
| 5/4     | 25        | 0.63%   |
| 21/9    | 25        | 0.63%   |
| 4/3     | 17        | 0.43%   |
| 0.67    | 9         | 0.23%   |
| 32/9    | 4         | 0.1%    |
| 6/5     | 3         | 0.08%   |
| 1.00    | 2         | 0.05%   |
| 2.21    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 2240      | 51.14%  |
| 81-90          | 702       | 16.03%  |
| 201-250        | 275       | 6.28%   |
| 71-80          | 217       | 4.95%   |
| 121-130        | 165       | 3.77%   |
| 301-350        | 124       | 2.83%   |
| 61-70          | 117       | 2.67%   |
| 51-60          | 67        | 1.53%   |
| 41-50          | 67        | 1.53%   |
| Unknown        | 61        | 1.39%   |
| 151-200        | 56        | 1.28%   |
| 351-500        | 43        | 0.98%   |
| 251-300        | 43        | 0.98%   |
| 111-120        | 40        | 0.91%   |
| More than 1000 | 38        | 0.87%   |
| 141-150        | 37        | 0.84%   |
| 131-140        | 30        | 0.68%   |
| 501-1000       | 27        | 0.62%   |
| 1-40           | 16        | 0.37%   |
| 91-100         | 15        | 0.34%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1602      | 37.13%  |
| 101-120       | 1405      | 32.57%  |
| 51-100        | 836       | 19.38%  |
| 161-240       | 278       | 6.44%   |
| More than 240 | 102       | 2.36%   |
| Unknown       | 61        | 1.41%   |
| 1-50          | 30        | 0.7%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 3424      | 82.55%  |
| 2     | 557       | 13.43%  |
| 0     | 117       | 2.82%   |
| 3     | 46        | 1.11%   |
| 4     | 4         | 0.1%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2180      | 33.61%  |
| Intel                             | 1908      | 29.41%  |
| Qualcomm Atheros                  | 1010      | 15.57%  |
| Broadcom                          | 489       | 7.54%   |
| Marvell Technology Group          | 124       | 1.91%   |
| Broadcom Limited                  | 107       | 1.65%   |
| MediaTek                          | 77        | 1.19%   |
| Ralink                            | 70        | 1.08%   |
| TP-Link                           | 53        | 0.82%   |
| Ralink Technology                 | 46        | 0.71%   |
| Nvidia                            | 32        | 0.49%   |
| ASIX Electronics                  | 32        | 0.49%   |
| Dell                              | 27        | 0.42%   |
| Huawei Technologies               | 24        | 0.37%   |
| Ericsson Business Mobile Networks | 20        | 0.31%   |
| Xiaomi                            | 19        | 0.29%   |
| Silicon Integrated Systems [SiS]  | 18        | 0.28%   |
| Samsung Electronics               | 18        | 0.28%   |
| JMicron Technology                | 17        | 0.26%   |
| Attansic Technology               | 17        | 0.26%   |
| Sierra Wireless                   | 16        | 0.25%   |
| Qualcomm                          | 14        | 0.22%   |
| Qualcomm Atheros Communications   | 13        | 0.2%    |
| Hewlett-Packard                   | 12        | 0.18%   |
| OPPO Electronics                  | 9         | 0.14%   |
| Lenovo                            | 9         | 0.14%   |
| DisplayLink                       | 9         | 0.14%   |
| Sitecom Europe                    | 8         | 0.12%   |
| Apple                             | 7         | 0.11%   |
| ZTE WCDMA Technologies MSM        | 6         | 0.09%   |
| T & A Mobile Phones               | 6         | 0.09%   |
| OnePlus Technology (Shenzhen)     | 6         | 0.09%   |
| D-Link System                     | 6         | 0.09%   |
| AMD                               | 6         | 0.09%   |
| NetGear                           | 5         | 0.08%   |
| ICS Advent                        | 5         | 0.08%   |
| Fibocom                           | 5         | 0.08%   |
| Belkin Components                 | 5         | 0.08%   |
| D-Link                            | 4         | 0.06%   |
| ZyDAS                             | 3         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 1306      | 17.12%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 406       | 5.32%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 180       | 2.36%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 174       | 2.28%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 173       | 2.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 160       | 2.1%    |
| Intel Wireless 8265 / 8275                                              | 154       | 2.02%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 146       | 1.91%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 141       | 1.85%   |
| Intel Wi-Fi 6 AX200                                                     | 138       | 1.81%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 131       | 1.72%   |
| Intel Wi-Fi 6 AX201                                                     | 123       | 1.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 117       | 1.53%   |
| Intel Wireless 7265                                                     | 116       | 1.52%   |
| Intel Wireless 3165                                                     | 109       | 1.43%   |
| Intel Wireless 7260                                                     | 94        | 1.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 87        | 1.14%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 83        | 1.09%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 83        | 1.09%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 82        | 1.07%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 75        | 0.98%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 70        | 0.92%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 69        | 0.9%    |
| Intel Wireless 8260                                                     | 69        | 0.9%    |
| Intel WiFi Link 5100                                                    | 69        | 0.9%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 67        | 0.88%   |
| Broadcom BCM43142 802.11b/g/n                                           | 63        | 0.83%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 58        | 0.76%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 53        | 0.69%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 49        | 0.64%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 44        | 0.58%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 44        | 0.58%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 44        | 0.58%   |
| Intel Ethernet Connection (4) I219-LM                                   | 41        | 0.54%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 40        | 0.52%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 40        | 0.52%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 39        | 0.51%   |
| Intel Ethernet Connection I218-LM                                       | 37        | 0.48%   |
| Intel Centrino Advanced-N 6200                                          | 37        | 0.48%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 36        | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1830      | 43.92%  |
| Qualcomm Atheros                      | 921       | 22.1%   |
| Realtek Semiconductor                 | 654       | 15.69%  |
| Broadcom                              | 353       | 8.47%   |
| MediaTek                              | 75        | 1.8%    |
| Broadcom Limited                      | 74        | 1.78%   |
| Ralink                                | 70        | 1.68%   |
| Ralink Technology                     | 46        | 1.1%    |
| TP-Link                               | 43        | 1.03%   |
| Sierra Wireless                       | 16        | 0.38%   |
| Dell                                  | 16        | 0.38%   |
| Qualcomm Atheros Communications       | 13        | 0.31%   |
| Sitecom Europe                        | 7         | 0.17%   |
| Qualcomm                              | 6         | 0.14%   |
| D-Link System                         | 6         | 0.14%   |
| NetGear                               | 5         | 0.12%   |
| Fibocom                               | 5         | 0.12%   |
| Belkin Components                     | 5         | 0.12%   |
| ZyDAS                                 | 3         | 0.07%   |
| D-Link                                | 3         | 0.07%   |
| ASUSTek Computer                      | 3         | 0.07%   |
| U.S. Robotics                         | 2         | 0.05%   |
| Qcom                                  | 2         | 0.05%   |
| Microsoft                             | 2         | 0.05%   |
| Hewlett-Packard                       | 2         | 0.05%   |
| ZyXEL Communications                  | 1         | 0.02%   |
| Micro Star International              | 1         | 0.02%   |
| Edimax Technology                     | 1         | 0.02%   |
| AVM                                   | 1         | 0.02%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 180       | 4.3%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 174       | 4.16%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 173       | 4.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 160       | 3.82%   |
| Intel Wireless 8265 / 8275                                              | 154       | 3.68%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 141       | 3.37%   |
| Intel Wi-Fi 6 AX200                                                     | 138       | 3.3%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 131       | 3.13%   |
| Intel Wi-Fi 6 AX201                                                     | 123       | 2.94%   |
| Intel Wireless 7265                                                     | 116       | 2.77%   |
| Intel Wireless 3165                                                     | 109       | 2.6%    |
| Intel Wireless 7260                                                     | 94        | 2.25%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 87        | 2.08%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 83        | 1.98%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 83        | 1.98%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 82        | 1.96%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 75        | 1.79%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 70        | 1.67%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 69        | 1.65%   |
| Intel Wireless 8260                                                     | 69        | 1.65%   |
| Intel WiFi Link 5100                                                    | 69        | 1.65%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 67        | 1.6%    |
| Broadcom BCM43142 802.11b/g/n                                           | 63        | 1.51%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 58        | 1.39%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 53        | 1.27%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 49        | 1.17%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 44        | 1.05%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 44        | 1.05%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 40        | 0.96%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 40        | 0.96%   |
| Intel Centrino Advanced-N 6200                                          | 37        | 0.88%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 36        | 0.86%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 34        | 0.81%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 33        | 0.79%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 33        | 0.79%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 32        | 0.76%   |
| Intel Wireless-AC 9260                                                  | 32        | 0.76%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 31        | 0.74%   |
| Intel Centrino Wireless-N 2230                                          | 31        | 0.74%   |
| Intel Wireless 3160                                                     | 30        | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1930      | 58.01%  |
| Intel                            | 583       | 17.52%  |
| Qualcomm Atheros                 | 203       | 6.1%    |
| Broadcom                         | 195       | 5.86%   |
| Marvell Technology Group         | 124       | 3.73%   |
| Broadcom Limited                 | 34        | 1.02%   |
| ASIX Electronics                 | 32        | 0.96%   |
| Nvidia                           | 31        | 0.93%   |
| Xiaomi                           | 19        | 0.57%   |
| Huawei Technologies              | 19        | 0.57%   |
| JMicron Technology               | 17        | 0.51%   |
| Attansic Technology              | 17        | 0.51%   |
| Silicon Integrated Systems [SiS] | 16        | 0.48%   |
| Samsung Electronics              | 11        | 0.33%   |
| TP-Link                          | 10        | 0.3%    |
| OPPO Electronics                 | 9         | 0.27%   |
| Lenovo                           | 9         | 0.27%   |
| DisplayLink                      | 9         | 0.27%   |
| Qualcomm                         | 8         | 0.24%   |
| Apple                            | 7         | 0.21%   |
| OnePlus Technology (Shenzhen)    | 6         | 0.18%   |
| ICS Advent                       | 5         | 0.15%   |
| T & A Mobile Phones              | 4         | 0.12%   |
| ZTE WCDMA Technologies MSM       | 3         | 0.09%   |
| VIA Technologies                 | 3         | 0.09%   |
| Motorola PCS                     | 3         | 0.09%   |
| HMD Global                       | 3         | 0.09%   |
| Hewlett-Packard                  | 3         | 0.09%   |
| Spreadtrum Communications        | 2         | 0.06%   |
| MediaTek                         | 2         | 0.06%   |
| LG Electronics                   | 2         | 0.06%   |
| Google                           | 2         | 0.06%   |
| Sitecom Europe                   | 1         | 0.03%   |
| MosChip Semiconductor            | 1         | 0.03%   |
| Microchip Technology             | 1         | 0.03%   |
| D-Link                           | 1         | 0.03%   |
| ADMtek                           | 1         | 0.03%   |
| Accton Technology                | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 1306      | 38.94%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 406       | 12.1%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 146       | 4.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 117       | 3.49%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 44        | 1.31%   |
| Intel Ethernet Connection (4) I219-LM                                          | 41        | 1.22%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 39        | 1.16%   |
| Intel Ethernet Connection I218-LM                                              | 37        | 1.1%    |
| Intel 82577LM Gigabit Network Connection                                       | 35        | 1.04%   |
| Intel 82567LM Gigabit Network Connection                                       | 35        | 1.04%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 34        | 1.01%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 32        | 0.95%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 29        | 0.86%   |
| Intel Ethernet Connection I219-LM                                              | 29        | 0.86%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 28        | 0.83%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 28        | 0.83%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 25        | 0.75%   |
| Intel Ethernet Connection I217-LM                                              | 25        | 0.75%   |
| Intel Ethernet Connection (3) I218-LM                                          | 25        | 0.75%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 22        | 0.66%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 22        | 0.66%   |
| Intel Ethernet Connection I219-V                                               | 22        | 0.66%   |
| Intel Ethernet Connection (4) I219-V                                           | 20        | 0.6%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 20        | 0.6%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 18        | 0.54%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 18        | 0.54%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 17        | 0.51%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 17        | 0.51%   |
| Nvidia MCP79 Ethernet                                                          | 17        | 0.51%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 17        | 0.51%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 17        | 0.51%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 17        | 0.51%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 17        | 0.51%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 16        | 0.48%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 15        | 0.45%   |
| Intel Ethernet Connection (6) I219-V                                           | 15        | 0.45%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 15        | 0.45%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 15        | 0.45%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                           | 14        | 0.42%   |
| Intel Ethernet Connection (10) I219-V                                          | 14        | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3964      | 54.53%  |
| Ethernet | 3216      | 44.24%  |
| Modem    | 82        | 1.13%   |
| Unknown  | 7         | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3335      | 79.5%   |
| Ethernet | 857       | 20.43%  |
| Unknown  | 2         | 0.05%   |
| Modem    | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2937      | 72.43%  |
| 1     | 997       | 24.59%  |
| 0     | 97        | 2.39%   |
| 3     | 24        | 0.59%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3810      | 93.15%  |
| Yes  | 280       | 6.85%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1340      | 44.59%  |
| Realtek Semiconductor           | 373       | 12.41%  |
| Qualcomm Atheros Communications | 216       | 7.19%   |
| IMC Networks                    | 176       | 5.86%   |
| Lite-On Technology              | 173       | 5.76%   |
| Broadcom                        | 166       | 5.52%   |
| Foxconn / Hon Hai               | 135       | 4.49%   |
| Apple                           | 87        | 2.9%    |
| Hewlett-Packard                 | 67        | 2.23%   |
| Realtek                         | 54        | 1.8%    |
| Dell                            | 42        | 1.4%    |
| Cambridge Silicon Radio         | 40        | 1.33%   |
| Toshiba                         | 34        | 1.13%   |
| Ralink                          | 34        | 1.13%   |
| ASUSTek Computer                | 18        | 0.6%    |
| Alps Electric                   | 14        | 0.47%   |
| Ralink Technology               | 7         | 0.23%   |
| MediaTek                        | 5         | 0.17%   |
| Foxconn International           | 5         | 0.17%   |
| Chicony Electronics             | 4         | 0.13%   |
| Askey Computer                  | 4         | 0.13%   |
| Taiyo Yuden                     | 2         | 0.07%   |
| Integrated System Solution      | 2         | 0.07%   |
| USI                             | 1         | 0.03%   |
| Unknown                         | 1         | 0.03%   |
| Sitecom Europe                  | 1         | 0.03%   |
| Opticis                         | 1         | 0.03%   |
| ISSC                            | 1         | 0.03%   |
| Corsair                         | 1         | 0.03%   |
| Conwise Technology              | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 573       | 19.07%  |
| Realtek Bluetooth Radio                                                             | 250       | 8.32%   |
| Intel AX201 Bluetooth                                                               | 237       | 7.89%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 204       | 6.79%   |
| Intel AX200 Bluetooth                                                               | 133       | 4.43%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 94        | 3.13%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 85        | 2.83%   |
| IMC Networks Bluetooth Device                                                       | 73        | 2.43%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 60        | 2%      |
| Realtek Bluetooth Radio                                                             | 54        | 1.8%    |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 48        | 1.6%    |
| IMC Networks Bluetooth Radio                                                        | 48        | 1.6%    |
| Apple Bluetooth Host Controller                                                     | 47        | 1.56%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 45        | 1.5%    |
| Foxconn / Hon Hai Bluetooth Device                                                  | 44        | 1.46%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 43        | 1.43%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 42        | 1.4%    |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 40        | 1.33%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 40        | 1.33%   |
| Lite-On Bluetooth Device                                                            | 38        | 1.26%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 37        | 1.23%   |
| Ralink RT3290 Bluetooth                                                             | 34        | 1.13%   |
| Intel Bluetooth Device                                                              | 33        | 1.1%    |
| HP Broadcom 2070 Bluetooth Combo                                                    | 32        | 1.06%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 32        | 1.06%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 31        | 1.03%   |
| Broadcom BCM2045 Bluetooth                                                          | 25        | 0.83%   |
| IMC Networks Wireless_Device                                                        | 23        | 0.77%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 22        | 0.73%   |
| Apple Bluetooth HCI                                                                 | 20        | 0.67%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 19        | 0.63%   |
| Intel AX210 Bluetooth                                                               | 19        | 0.63%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 17        | 0.57%   |
| Realtek RTL8723B Bluetooth                                                          | 16        | 0.53%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 16        | 0.53%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 16        | 0.53%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 16        | 0.53%   |
| Apple Bluetooth USB Host Controller                                                 | 16        | 0.53%   |
| Lite-On Wireless_Device                                                             | 15        | 0.5%    |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 15        | 0.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 3196      | 67.47%  |
| AMD                                          | 828       | 17.48%  |
| Nvidia                                       | 464       | 9.8%    |
| C-Media Electronics                          | 28        | 0.59%   |
| Silicon Integrated Systems [SiS]             | 25        | 0.53%   |
| Logitech                                     | 19        | 0.4%    |
| GN Netcom                                    | 19        | 0.4%    |
| JMTek                                        | 15        | 0.32%   |
| Realtek Semiconductor                        | 13        | 0.27%   |
| Generalplus Technology                       | 12        | 0.25%   |
| VIA Technologies                             | 7         | 0.15%   |
| Lenovo                                       | 7         | 0.15%   |
| Texas Instruments                            | 6         | 0.13%   |
| CMX Systems                                  | 6         | 0.13%   |
| Plantronics                                  | 5         | 0.11%   |
| Hewlett-Packard                              | 5         | 0.11%   |
| Apple                                        | 5         | 0.11%   |
| Huawei Technologies                          | 4         | 0.08%   |
| Fujitsu                                      | 4         | 0.08%   |
| Creative Technology                          | 4         | 0.08%   |
| BEHRINGER International                      | 4         | 0.08%   |
| Sony                                         | 3         | 0.06%   |
| Samson Technologies                          | 3         | 0.06%   |
| Razer USA                                    | 3         | 0.06%   |
| M-Audio                                      | 3         | 0.06%   |
| Syntek                                       | 2         | 0.04%   |
| Medeli Electronics                           | 2         | 0.04%   |
| Focusrite-Novation                           | 2         | 0.04%   |
| Dell                                         | 2         | 0.04%   |
| Corsair                                      | 2         | 0.04%   |
| Cambridge Silicon Radio                      | 2         | 0.04%   |
| ASUSTek Computer                             | 2         | 0.04%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.02%   |
| XMOS                                         | 1         | 0.02%   |
| TEAC                                         | 1         | 0.02%   |
| SmartlinkTechnology                          | 1         | 0.02%   |
| Schiit Audio                                 | 1         | 0.02%   |
| Scarlett                                     | 1         | 0.02%   |
| RODE Microphones                             | 1         | 0.02%   |
| OnePlus Technology (Shenzhen)                | 1         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 461       | 8.02%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 355       | 6.18%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 299       | 5.2%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 236       | 4.11%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 221       | 3.85%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 194       | 3.38%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 184       | 3.2%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 178       | 3.1%    |
| Intel 8 Series HD Audio Controller                                                                | 178       | 3.1%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 174       | 3.03%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 143       | 2.49%   |
| AMD FCH Azalia Controller                                                                         | 135       | 2.35%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 129       | 2.25%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 127       | 2.21%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 125       | 2.18%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 120       | 2.09%   |
| Intel Cannon Lake PCH cAVS                                                                        | 118       | 2.05%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 116       | 2.02%   |
| AMD Kabini HDMI/DP Audio                                                                          | 115       | 2%      |
| Intel Broadwell-U Audio Controller                                                                | 110       | 1.91%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 106       | 1.85%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 106       | 1.85%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 95        | 1.65%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 95        | 1.65%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 66        | 1.15%   |
| AMD High Definition Audio Controller                                                              | 65        | 1.13%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 61        | 1.06%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 60        | 1.04%   |
| Intel Comet Lake PCH cAVS                                                                         | 58        | 1.01%   |
| Intel CM238 HD Audio Controller                                                                   | 56        | 0.97%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 55        | 0.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 47        | 0.82%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 45        | 0.78%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 44        | 0.77%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 42        | 0.73%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 39        | 0.68%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 35        | 0.61%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 34        | 0.59%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 32        | 0.56%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 31        | 0.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 788       | 29.64%  |
| SK hynix                     | 582       | 21.89%  |
| Micron Technology            | 341       | 12.82%  |
| Unknown                      | 239       | 8.99%   |
| Kingston                     | 221       | 8.31%   |
| Crucial                      | 118       | 4.44%   |
| Ramaxel Technology           | 66        | 2.48%   |
| Elpida                       | 61        | 2.29%   |
| Unknown (ABCD)               | 55        | 2.07%   |
| A-DATA Technology            | 41        | 1.54%   |
| Nanya Technology             | 34        | 1.28%   |
| Corsair                      | 34        | 1.28%   |
| Unknown                      | 14        | 0.53%   |
| Team                         | 9         | 0.34%   |
| Transcend                    | 8         | 0.3%    |
| ASint Technology             | 6         | 0.23%   |
| Toshiba                      | 5         | 0.19%   |
| G.Skill                      | 5         | 0.19%   |
| Qimonda                      | 4         | 0.15%   |
| 48spaces                     | 4         | 0.15%   |
| Timetec                      | 3         | 0.11%   |
| Patriot                      | 2         | 0.08%   |
| ChangXin Memory              | 2         | 0.08%   |
| Unknown (8A5D)               | 1         | 0.04%   |
| Unknown (8A02)               | 1         | 0.04%   |
| Unknown (7F7F7F7F7F7F6B00)   | 1         | 0.04%   |
| Unknown (0x5846)             | 1         | 0.04%   |
| Unknown (0x08A4FFFFFFFFFFFF) | 1         | 0.04%   |
| Unigen                       | 1         | 0.04%   |
| Unifosa                      | 1         | 0.04%   |
| Smart Brazil                 | 1         | 0.04%   |
| SHARETRONIC                  | 1         | 0.04%   |
| Sesame                       | 1         | 0.04%   |
| Neo Forza                    | 1         | 0.04%   |
| Infineon                     | 1         | 0.04%   |
| Goldkey                      | 1         | 0.04%   |
| Essencore Limited            | 1         | 0.04%   |
| Avant                        | 1         | 0.04%   |
| Apacer                       | 1         | 0.04%   |
| A Force                      | 1         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 51        | 1.8%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 42        | 1.48%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 37        | 1.31%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 36        | 1.27%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 31        | 1.1%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 30        | 1.06%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 29        | 1.02%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 28        | 0.99%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 25        | 0.88%   |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 25        | 0.88%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 25        | 0.88%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 25        | 0.88%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 23        | 0.81%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 22        | 0.78%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 20        | 0.71%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 20        | 0.71%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 20        | 0.71%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 20        | 0.71%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 19        | 0.67%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 19        | 0.67%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 19        | 0.67%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 18        | 0.64%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 18        | 0.64%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 17        | 0.6%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 17        | 0.6%    |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 17        | 0.6%    |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 17        | 0.6%    |
| Unknown RAM Module 4GB SODIMM DDR3                               | 16        | 0.57%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 16        | 0.57%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 16        | 0.57%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 16        | 0.57%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 15        | 0.53%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 15        | 0.53%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 14        | 0.49%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 14        | 0.49%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 14        | 0.49%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 14        | 0.49%   |
| Unknown                                                          | 14        | 0.49%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 13        | 0.46%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 13        | 0.46%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 1063      | 46.28%  |
| DDR3    | 778       | 33.87%  |
| LPDDR4  | 144       | 6.27%   |
| DDR2    | 135       | 5.88%   |
| LPDDR3  | 63        | 2.74%   |
| SDRAM   | 49        | 2.13%   |
| DDR5    | 18        | 0.78%   |
| Unknown | 17        | 0.74%   |
| LPDDR5  | 12        | 0.52%   |
| DRAM    | 10        | 0.44%   |
| DDR     | 8         | 0.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 2053      | 88.64%  |
| Row Of Chips | 240       | 10.36%  |
| DIMM         | 10        | 0.43%   |
| Chip         | 10        | 0.43%   |
| Unknown      | 3         | 0.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 924       | 37.11%  |
| 4096  | 800       | 32.13%  |
| 2048  | 340       | 13.65%  |
| 16384 | 306       | 12.29%  |
| 1024  | 73        | 2.93%   |
| 32768 | 31        | 1.24%   |
| 512   | 15        | 0.6%    |
| 256   | 1         | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 505       | 20.43%  |
| 1600    | 491       | 19.86%  |
| 3200    | 401       | 16.22%  |
| 2400    | 211       | 8.54%   |
| 1334    | 141       | 5.7%    |
| 2133    | 120       | 4.85%   |
| 1333    | 84        | 3.4%    |
| Unknown | 82        | 3.32%   |
| 667     | 76        | 3.07%   |
| 4267    | 51        | 2.06%   |
| 3266    | 42        | 1.7%    |
| 1066    | 41        | 1.66%   |
| 800     | 35        | 1.42%   |
| 1067    | 25        | 1.01%   |
| 1867    | 24        | 0.97%   |
| 4199    | 20        | 0.81%   |
| 4800    | 19        | 0.77%   |
| 8400    | 17        | 0.69%   |
| 533     | 15        | 0.61%   |
| 2048    | 14        | 0.57%   |
| 6400    | 12        | 0.49%   |
| 975     | 9         | 0.36%   |
| 4266    | 8         | 0.32%   |
| 2933    | 7         | 0.28%   |
| 3733    | 4         | 0.16%   |
| 3400    | 2         | 0.08%   |
| 1866    | 2         | 0.08%   |
| 1639    | 2         | 0.08%   |
| 1200    | 2         | 0.08%   |
| 400     | 2         | 0.08%   |
| 333     | 2         | 0.08%   |
| 2800    | 1         | 0.04%   |
| 2267    | 1         | 0.04%   |
| 2134    | 1         | 0.04%   |
| 2000    | 1         | 0.04%   |
| 1776    | 1         | 0.04%   |
| 933     | 1         | 0.04%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 21        | 33.33%  |
| Samsung Electronics | 16        | 25.4%   |
| Canon               | 11        | 17.46%  |
| Brother Industries  | 5         | 7.94%   |
| Seiko Epson         | 4         | 6.35%   |
| Pantum              | 2         | 3.17%   |
| Xerox               | 1         | 1.59%   |
| Sagem               | 1         | 1.59%   |
| ICS Advent          | 1         | 1.59%   |
| Apple               | 1         | 1.59%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Samsung ML-216x Series Laser Printer | 3         | 4.69%   |
| Samsung M267x 287x Series            | 2         | 3.13%   |
| Samsung M2070 Series                 | 2         | 3.13%   |
| HP OfficeJet 3830 series             | 2         | 3.13%   |
| HP Officejet 2620 series             | 2         | 3.13%   |
| Xerox B215                           | 1         | 1.56%   |
| Seiko Epson WF-2510 Series           | 1         | 1.56%   |
| Seiko Epson Printer                  | 1         | 1.56%   |
| Seiko Epson L355 Series              | 1         | 1.56%   |
| Seiko Epson ET-2810 Series           | 1         | 1.56%   |
| Samsung SCX-483x 5x3x Series         | 1         | 1.56%   |
| Samsung SCX-4623 Series              | 1         | 1.56%   |
| Samsung SCX-4300 Series              | 1         | 1.56%   |
| Samsung ML-331x Series Laser Printer | 1         | 1.56%   |
| Samsung ML-2010P Mono Laser Printer  | 1         | 1.56%   |
| Samsung ML-1865W Series              | 1         | 1.56%   |
| Samsung ML-1640 Series Laser Printer | 1         | 1.56%   |
| Samsung CLP-325 Color Laser Printer  | 1         | 1.56%   |
| Samsung C3060 Series                 | 1         | 1.56%   |
| Sagem Laser Pro LL                   | 1         | 1.56%   |
| Pantum P2500W series                 | 1         | 1.56%   |
| Pantum M6500W series                 | 1         | 1.56%   |
| ICS Advent Parallel Adapter          | 1         | 1.56%   |
| HP Officejet Pro 6230                | 1         | 1.56%   |
| HP OfficeJet 6950                    | 1         | 1.56%   |
| HP OfficeJet 5600 (USBHUB)           | 1         | 1.56%   |
| HP LaserJet P3005                    | 1         | 1.56%   |
| HP LaserJet P2055 series             | 1         | 1.56%   |
| HP LaserJet P1102                    | 1         | 1.56%   |
| HP LaserJet 1200                     | 1         | 1.56%   |
| HP LaserJet 1020                     | 1         | 1.56%   |
| HP LaserJet 1015                     | 1         | 1.56%   |
| HP LaserJet 1010                     | 1         | 1.56%   |
| HP ENVY 5000 series                  | 1         | 1.56%   |
| HP ENVY 4520 series                  | 1         | 1.56%   |
| HP DeskJet 940c                      | 1         | 1.56%   |
| HP DeskJet 840c                      | 1         | 1.56%   |
| HP Deskjet 3520 series               | 1         | 1.56%   |
| HP DeskJet 2700 series               | 1         | 1.56%   |
| HP Deskjet 2050 J510                 | 1         | 1.56%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 6         | 46.15%  |
| Seiko Epson     | 5         | 38.46%  |
| Hewlett-Packard | 2         | 15.38%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]        | 2         | 14.29%  |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1         | 7.14%   |
| Seiko Epson ES-D400 [GT-S80]                             | 1         | 7.14%   |
| Seiko Epson CC-570L [Stylus CX3100/CX3200]               | 1         | 7.14%   |
| HP Scanjet G2710                                         | 1         | 7.14%   |
| HP ScanJet 3570c                                         | 1         | 7.14%   |
| Canon CanoScan LIDE 25                                   | 1         | 7.14%   |
| Canon CanoScan LiDE 220                                  | 1         | 7.14%   |
| Canon CanoScan LiDE 120                                  | 1         | 7.14%   |
| Canon CanoScan LiDE 110                                  | 1         | 7.14%   |
| Canon CanoScan LiDE 100                                  | 1         | 7.14%   |
| Canon CanoScan 4400F                                     | 1         | 7.14%   |
| Canon CanoScan 1220U                                     | 1         | 7.14%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 951       | 26.29%  |
| IMC Networks                           | 445       | 12.3%   |
| Realtek Semiconductor                  | 269       | 7.44%   |
| Microdia                               | 253       | 6.99%   |
| Quanta                                 | 190       | 5.25%   |
| Bison Electronics                      | 186       | 5.14%   |
| Suyin                                  | 181       | 5%      |
| Sunplus Innovation Technology          | 155       | 4.29%   |
| Cheng Uei Precision Industry (Foxlink) | 155       | 4.29%   |
| Acer                                   | 114       | 3.15%   |
| Alcor Micro                            | 98        | 2.71%   |
| Syntek                                 | 90        | 2.49%   |
| Lite-On Technology                     | 86        | 2.38%   |
| Apple                                  | 77        | 2.13%   |
| Luxvisions Innotech Limited            | 66        | 1.82%   |
| Silicon Motion                         | 45        | 1.24%   |
| Ricoh                                  | 45        | 1.24%   |
| Logitech                               | 27        | 0.75%   |
| Z-Star Microelectronics                | 20        | 0.55%   |
| ALi                                    | 17        | 0.47%   |
| Samsung Electronics                    | 15        | 0.41%   |
| Primax Electronics                     | 15        | 0.41%   |
| USB Camera                             | 11        | 0.3%    |
| Lenovo                                 | 10        | 0.28%   |
| Sunplus Technology                     | 8         | 0.22%   |
| Sonix Technology                       | 7         | 0.19%   |
| Importek                               | 7         | 0.19%   |
| DigiTech                               | 7         | 0.19%   |
| ARC International                      | 6         | 0.17%   |
| Genesys Logic                          | 5         | 0.14%   |
| GEMBIRD                                | 5         | 0.14%   |
| SunplusIT                              | 4         | 0.11%   |
| Microsoft                              | 4         | 0.11%   |
| Generalplus Technology                 | 3         | 0.08%   |
| WaveRider Communications               | 2         | 0.06%   |
| USB Camera CS                          | 2         | 0.06%   |
| Unknown (3730304231385631394831)       | 2         | 0.06%   |
| Pixart Imaging                         | 2         | 0.06%   |
| OmniVision Technologies                | 2         | 0.06%   |
| Nebraska Furniture Mart                | 2         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 147       | 4.05%   |
| Microdia Integrated_Webcam_HD                           | 106       | 2.92%   |
| Chicony HD WebCam                                       | 91        | 2.51%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 82        | 2.26%   |
| IMC Networks Integrated Camera                          | 72        | 1.98%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 71        | 1.96%   |
| Realtek Integrated_Webcam_HD                            | 56        | 1.54%   |
| Alcor Micro USB 2.0 Camera                              | 49        | 1.35%   |
| Syntek Integrated Camera                                | 47        | 1.29%   |
| Chicony USB2.0 VGA UVC WebCam                           | 44        | 1.21%   |
| Realtek USB Camera                                      | 42        | 1.16%   |
| Chicony USB2.0 HD UVC WebCam                            | 42        | 1.16%   |
| Chicony HP Truevision HD                                | 42        | 1.16%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 41        | 1.13%   |
| Sunplus Integrated_Webcam_HD                            | 39        | 1.07%   |
| Quanta HP TrueVision HD Camera                          | 36        | 0.99%   |
| Bison Integrated Camera                                 | 35        | 0.96%   |
| Chicony HP TrueVision HD Camera                         | 32        | 0.88%   |
| Acer Integrated Camera                                  | 32        | 0.88%   |
| Acer HD Webcam                                          | 32        | 0.88%   |
| Chicony FJ Camera                                       | 30        | 0.83%   |
| IMC Networks ov9734_azurewave_camera                    | 29        | 0.8%    |
| Chicony HP Webcam                                       | 29        | 0.8%    |
| Sunplus HD WebCam                                       | 28        | 0.77%   |
| Quanta HP Webcam                                        | 28        | 0.77%   |
| IMC Networks HD Camera                                  | 27        | 0.74%   |
| Chicony HP HD Camera                                    | 27        | 0.74%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                         | 27        | 0.74%   |
| Suyin HP TrueVision HD                                  | 25        | 0.69%   |
| Realtek USB2.0 VGA UVC WebCam                           | 25        | 0.69%   |
| Alcor Micro Asus Integrated Webcam                      | 24        | 0.66%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 23        | 0.63%   |
| Microdia Integrated Webcam                              | 23        | 0.63%   |
| Chicony USB2.0 Camera                                   | 23        | 0.63%   |
| Chicony HP Wide Vision HD Camera                        | 23        | 0.63%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 23        | 0.63%   |
| Bison SunplusIT Integrated Camera                       | 23        | 0.63%   |
| Apple Built-in iSight                                   | 23        | 0.63%   |
| Lite-On HP HD Camera                                    | 22        | 0.61%   |
| IMC Networks UVC VGA Webcam                             | 22        | 0.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 205       | 29.45%  |
| Synaptics                          | 148       | 21.26%  |
| Shenzhen Goodix Technology         | 123       | 17.67%  |
| Elan Microelectronics              | 82        | 11.78%  |
| Upek                               | 43        | 6.18%   |
| AuthenTec                          | 41        | 5.89%   |
| LighTuning Technology              | 39        | 5.6%    |
| STMicroelectronics                 | 6         | 0.86%   |
| Focal-systems.Corp                 | 5         | 0.72%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.29%   |
| Microsoft                          | 1         | 0.14%   |
| HOLTEK                             | 1         | 0.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 96        | 13.79%  |
| Elan ELAN:ARM-M4                                                           | 56        | 8.05%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 43        | 6.18%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 41        | 5.89%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 38        | 5.46%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 27        | 3.88%   |
| Elan ELAN:Fingerprint                                                      | 26        | 3.74%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 25        | 3.59%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 21        | 3.02%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 20        | 2.87%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 20        | 2.87%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 19        | 2.73%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 16        | 2.3%    |
| Validity Sensors Fingerprint scanner                                       | 16        | 2.3%    |
| Shenzhen Goodix Fingerprint Reader                                         | 15        | 2.16%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 14        | 2.01%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 14        | 2.01%   |
| Shenzhen Goodix FingerPrint                                                | 12        | 1.72%   |
| Validity Sensors VFS491                                                    | 11        | 1.58%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 11        | 1.58%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 11        | 1.58%   |
| Unknown                                                                    | 10        | 1.44%   |
| Synaptics  WBDI                                                            | 9         | 1.29%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 8         | 1.15%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 8         | 1.15%   |
| Validity Sensors VFS Fingerprint sensor                                    | 7         | 1.01%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 7         | 1.01%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 1.01%   |
| AuthenTec AES1600                                                          | 7         | 1.01%   |
| Validity Sensors Synaptics WBDI                                            | 6         | 0.86%   |
| Synaptics UWP WBDI                                                         | 6         | 0.86%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 6         | 0.86%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 6         | 0.86%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 0.86%   |
| AuthenTec AES2810                                                          | 6         | 0.86%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 5         | 0.72%   |
| Upek TCS5B Fingerprint sensor                                              | 5         | 0.72%   |
| Synaptics UWP WBDI Device                                                  | 5         | 0.72%   |
| LighTuning Fingerprint Reader                                              | 5         | 0.72%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 5         | 0.72%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Broadcom                 | 111       | 40.81%  |
| Alcor Micro              | 88        | 32.35%  |
| O2 Micro                 | 27        | 9.93%   |
| Lenovo                   | 16        | 5.88%   |
| Upek                     | 11        | 4.04%   |
| Advanced Card Systems    | 5         | 1.84%   |
| Gemalto (was Gemplus)    | 4         | 1.47%   |
| BIT4ID                   | 4         | 1.47%   |
| Realtek Semiconductor    | 2         | 0.74%   |
| SCM Microsystems         | 1         | 0.37%   |
| Reiner SCT Kartensysteme | 1         | 0.37%   |
| OmniKey                  | 1         | 0.37%   |
| In Focus Systems         | 1         | 0.37%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 85        | 31.25%  |
| Broadcom BCM5880 Secure Applications Processor                               | 33        | 12.13%  |
| Broadcom 58200                                                               | 33        | 12.13%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 23        | 8.46%   |
| Broadcom 5880                                                                | 23        | 8.46%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 20        | 7.35%   |
| Lenovo Integrated Smart Card Reader                                          | 16        | 5.88%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 11        | 4.04%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 1.47%   |
| BIT4ID miniLector EVO                                                        | 4         | 1.47%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 1.1%    |
| Alcor Micro Watchdata W 1981                                                 | 3         | 1.1%    |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 3         | 1.1%    |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 0.74%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.74%   |
| Advanced Card Systems ACR122U                                                | 2         | 0.74%   |
| SCM Microsystems uTrust 3700 F CL Reader                                     | 1         | 0.37%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.37%   |
| OmniKey CardMan Smart@Link                                                   | 1         | 0.37%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.37%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.37%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 2576      | 61.82%  |
| 1     | 1246      | 29.9%   |
| 2     | 303       | 7.27%   |
| 3     | 29        | 0.7%    |
| 4     | 10        | 0.24%   |
| 5     | 2         | 0.05%   |
| 6     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 688       | 35.8%   |
| Graphics card            | 439       | 22.84%  |
| Chipcard                 | 237       | 12.33%  |
| Net/wireless             | 177       | 9.21%   |
| Multimedia controller    | 94        | 4.89%   |
| Camera                   | 72        | 3.75%   |
| Bluetooth                | 59        | 3.07%   |
| Storage                  | 32        | 1.66%   |
| Communication controller | 30        | 1.56%   |
| Sound                    | 19        | 0.99%   |
| Modem                    | 18        | 0.94%   |
| Flash memory             | 18        | 0.94%   |
| Net/ethernet             | 13        | 0.68%   |
| Card reader              | 13        | 0.68%   |
| Network                  | 6         | 0.31%   |
| Storage/ide              | 2         | 0.1%    |
| Dvb card                 | 2         | 0.1%    |
| Wireless                 | 1         | 0.05%   |
| Storage/raid             | 1         | 0.05%   |
| Storage/nvme             | 1         | 0.05%   |

