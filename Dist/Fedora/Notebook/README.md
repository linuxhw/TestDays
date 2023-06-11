Fedora - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Fedora.

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

Total: 10109

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | X541UVK                     | [22a8a9d964](https://linux-hardware.org/?probe=22a8a9d964) | Jun 10, 2023 |
| Apple         | MacBookAir5,2               | [18e80281cc](https://linux-hardware.org/?probe=18e80281cc) | Jun 10, 2023 |
| Samsung       | 730QCJ/730QCR               | [96b21d42f1](https://linux-hardware.org/?probe=96b21d42f1) | Jun 10, 2023 |
| Apple         | MacBookAir5,2               | [f7bd03dbb9](https://linux-hardware.org/?probe=f7bd03dbb9) | Jun 10, 2023 |
| Lenovo        | G580 ChiefRiver Platform    | [ac48eeb92c](https://linux-hardware.org/?probe=ac48eeb92c) | Jun 10, 2023 |
| Lenovo        | G580 ChiefRiver Platform    | [ade15528d8](https://linux-hardware.org/?probe=ade15528d8) | Jun 10, 2023 |
| HP            | Pavilion Laptop 14-ec1xx... | [1eeb12a5ca](https://linux-hardware.org/?probe=1eeb12a5ca) | Jun 10, 2023 |
| HP            | Pavilion Laptop 14-ec1xx... | [e46f2fe66e](https://linux-hardware.org/?probe=e46f2fe66e) | Jun 10, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [1de48a4515](https://linux-hardware.org/?probe=1de48a4515) | Jun 10, 2023 |
| HP            | ZBook 15 G2                 | [68c941fe5d](https://linux-hardware.org/?probe=68c941fe5d) | Jun 10, 2023 |
| Toshiba       | PORTEGE Z10t-A              | [4a0712b322](https://linux-hardware.org/?probe=4a0712b322) | Jun 10, 2023 |
| Apple         | MacBookPro13,2              | [929c318674](https://linux-hardware.org/?probe=929c318674) | Jun 10, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [1a36e2fa98](https://linux-hardware.org/?probe=1a36e2fa98) | Jun 10, 2023 |
| Dell          | Inspiron 5515               | [36016c0c6b](https://linux-hardware.org/?probe=36016c0c6b) | Jun 10, 2023 |
| HUAWEI        | BOD-WXX9                    | [c4063bcf07](https://linux-hardware.org/?probe=c4063bcf07) | Jun 09, 2023 |
| HUAWEI        | BOD-WXX9                    | [9016ad81ae](https://linux-hardware.org/?probe=9016ad81ae) | Jun 09, 2023 |
| HP            | Laptop 15-db0xxx            | [881d5dc409](https://linux-hardware.org/?probe=881d5dc409) | Jun 09, 2023 |
| HP            | ZBook 15 G2                 | [2851b41659](https://linux-hardware.org/?probe=2851b41659) | Jun 09, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [1794287cf0](https://linux-hardware.org/?probe=1794287cf0) | Jun 09, 2023 |
| Lenovo        | ThinkPad P1 20MD001VUS      | [9765261d02](https://linux-hardware.org/?probe=9765261d02) | Jun 09, 2023 |
| Lenovo        | ThinkPad T460 20FN002JUS    | [8cc29c049e](https://linux-hardware.org/?probe=8cc29c049e) | Jun 09, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [9e3dfb25be](https://linux-hardware.org/?probe=9e3dfb25be) | Jun 09, 2023 |
| Dell          | XPS 13 9370                 | [c605e51eca](https://linux-hardware.org/?probe=c605e51eca) | Jun 09, 2023 |
| HP            | Laptop 15-db0xxx            | [5dd8c1fed8](https://linux-hardware.org/?probe=5dd8c1fed8) | Jun 09, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [e246e70bb6](https://linux-hardware.org/?probe=e246e70bb6) | Jun 09, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | [27c0e57cb3](https://linux-hardware.org/?probe=27c0e57cb3) | Jun 09, 2023 |
| Dell          | Inspiron 3493               | [ffcd21fc3b](https://linux-hardware.org/?probe=ffcd21fc3b) | Jun 09, 2023 |
| Dell          | Precision 7540              | [41fe2f93ff](https://linux-hardware.org/?probe=41fe2f93ff) | Jun 09, 2023 |
| Apple         | MacBookPro9,2               | [c22081b097](https://linux-hardware.org/?probe=c22081b097) | Jun 09, 2023 |
| Apple         | MacBookPro8,1               | [70fea7478a](https://linux-hardware.org/?probe=70fea7478a) | Jun 08, 2023 |
| Dell          | Latitude 5175               | [63d6fcf641](https://linux-hardware.org/?probe=63d6fcf641) | Jun 08, 2023 |
| Lenovo        | ThinkPad E14 20RA0016GE     | [4c8d8758b7](https://linux-hardware.org/?probe=4c8d8758b7) | Jun 08, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [e28668e147](https://linux-hardware.org/?probe=e28668e147) | Jun 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [59ff5486a9](https://linux-hardware.org/?probe=59ff5486a9) | Jun 08, 2023 |
| HP            | 240 G6 Notebook PC          | [eda13b898c](https://linux-hardware.org/?probe=eda13b898c) | Jun 08, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [13b0e73872](https://linux-hardware.org/?probe=13b0e73872) | Jun 08, 2023 |
| TUXEDO        | Stellaris Intel Gen4        | [e6cb646bd4](https://linux-hardware.org/?probe=e6cb646bd4) | Jun 08, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [6de4ea13fe](https://linux-hardware.org/?probe=6de4ea13fe) | Jun 08, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | [8f160a999a](https://linux-hardware.org/?probe=8f160a999a) | Jun 08, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [0aea375d78](https://linux-hardware.org/?probe=0aea375d78) | Jun 08, 2023 |
| Dell          | Precision 3551              | [0e484bd6a5](https://linux-hardware.org/?probe=0e484bd6a5) | Jun 08, 2023 |
| HP            | Pavilion g6                 | [12b1174ce8](https://linux-hardware.org/?probe=12b1174ce8) | Jun 08, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [7543a0bbc1](https://linux-hardware.org/?probe=7543a0bbc1) | Jun 08, 2023 |
| Dell          | Precision 5510              | [24317d94ff](https://linux-hardware.org/?probe=24317d94ff) | Jun 08, 2023 |
| Lenovo        | ThinkPad T580 20L90047US    | [bee34052a3](https://linux-hardware.org/?probe=bee34052a3) | Jun 08, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [9c9fb1b1a6](https://linux-hardware.org/?probe=9c9fb1b1a6) | Jun 08, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [82d0019a0b](https://linux-hardware.org/?probe=82d0019a0b) | Jun 08, 2023 |
| Dell          | Inspiron 5505               | [05973f7d9b](https://linux-hardware.org/?probe=05973f7d9b) | Jun 08, 2023 |
| Unknown       | Unknown                     | [829839a3b3](https://linux-hardware.org/?probe=829839a3b3) | Jun 07, 2023 |
| Dell          | Inspiron 15 5510            | [98d7cb7ea7](https://linux-hardware.org/?probe=98d7cb7ea7) | Jun 07, 2023 |
| Dell          | Inspiron 5565               | [91fc26029a](https://linux-hardware.org/?probe=91fc26029a) | Jun 07, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [06608c68d7](https://linux-hardware.org/?probe=06608c68d7) | Jun 07, 2023 |
| Fujitsu       | CELSIUS H730                | [a1e397f4a7](https://linux-hardware.org/?probe=a1e397f4a7) | Jun 07, 2023 |
| HP            | Pavilion dv7                | [75a37cd4c8](https://linux-hardware.org/?probe=75a37cd4c8) | Jun 07, 2023 |
| Dell          | Inspiron 5548               | [e67581e121](https://linux-hardware.org/?probe=e67581e121) | Jun 07, 2023 |
| Apple         | MacBookPro9,2               | [2a0add5b7e](https://linux-hardware.org/?probe=2a0add5b7e) | Jun 07, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | [e103817b2d](https://linux-hardware.org/?probe=e103817b2d) | Jun 07, 2023 |
| Lenovo        | ThinkPad T590 20N5S2NC0F    | [581602e921](https://linux-hardware.org/?probe=581602e921) | Jun 07, 2023 |
| Dell          | Latitude 5300               | [1eea10cfa3](https://linux-hardware.org/?probe=1eea10cfa3) | Jun 07, 2023 |
| Lenovo        | Yoga Pro 9 14IRP8 83BU      | [7d33fb0564](https://linux-hardware.org/?probe=7d33fb0564) | Jun 07, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | [b6bb7bad1d](https://linux-hardware.org/?probe=b6bb7bad1d) | Jun 07, 2023 |
| Apple         | MacBookPro9,2               | [8d70c1dd42](https://linux-hardware.org/?probe=8d70c1dd42) | Jun 07, 2023 |
| Acer          | Predator PH315-52           | [f7178495c7](https://linux-hardware.org/?probe=f7178495c7) | Jun 07, 2023 |
| Acer          | Aspire E5-411G              | [9a69b50d97](https://linux-hardware.org/?probe=9a69b50d97) | Jun 07, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [f9b3588ff3](https://linux-hardware.org/?probe=f9b3588ff3) | Jun 07, 2023 |
| Lenovo        | ThinkPad T495 20NKS10K00    | [f205c52b8f](https://linux-hardware.org/?probe=f205c52b8f) | Jun 07, 2023 |
| MSI           | GT72 2QE                    | [211494a051](https://linux-hardware.org/?probe=211494a051) | Jun 07, 2023 |
| Lenovo        | ThinkPad P1 20MD001VUS      | [8c505b5d84](https://linux-hardware.org/?probe=8c505b5d84) | Jun 06, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [9afe34cdd8](https://linux-hardware.org/?probe=9afe34cdd8) | Jun 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [b7ab29fbb5](https://linux-hardware.org/?probe=b7ab29fbb5) | Jun 06, 2023 |
| ASUSTek       | ZenBook UX325JA_UX325JA     | [721ff5908a](https://linux-hardware.org/?probe=721ff5908a) | Jun 06, 2023 |
| Toshiba       | Satellite L40               | [16c5f74991](https://linux-hardware.org/?probe=16c5f74991) | Jun 06, 2023 |
| Apple         | MacBookPro14,1              | [16aa33fdfe](https://linux-hardware.org/?probe=16aa33fdfe) | Jun 06, 2023 |
| Lenovo        | ThinkPad W520 4282AB9       | [790550e99f](https://linux-hardware.org/?probe=790550e99f) | Jun 06, 2023 |
| Lenovo        | ThinkPad T460 20FMS2292K    | [380ffe6574](https://linux-hardware.org/?probe=380ffe6574) | Jun 06, 2023 |
| Dell          | XPS 15 9560                 | [0d326774c9](https://linux-hardware.org/?probe=0d326774c9) | Jun 06, 2023 |
| Lenovo        | ThinkPad P51 20HH0011US     | [4766608bc1](https://linux-hardware.org/?probe=4766608bc1) | Jun 06, 2023 |
| Apple         | MacBookPro9,2               | [7394a9d94b](https://linux-hardware.org/?probe=7394a9d94b) | Jun 06, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | [2a612dc748](https://linux-hardware.org/?probe=2a612dc748) | Jun 06, 2023 |
| Apple         | MacBookPro9,2               | [9df43aede5](https://linux-hardware.org/?probe=9df43aede5) | Jun 06, 2023 |
| Lenovo        | ThinkPad P50 20EN001SUS     | [77b332cb2d](https://linux-hardware.org/?probe=77b332cb2d) | Jun 06, 2023 |
| System76      | Oryx Pro                    | [4f39b2d690](https://linux-hardware.org/?probe=4f39b2d690) | Jun 06, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [0deafae1f1](https://linux-hardware.org/?probe=0deafae1f1) | Jun 05, 2023 |
| realme        | CloudProXXXX                | [22cced9066](https://linux-hardware.org/?probe=22cced9066) | Jun 05, 2023 |
| Acer          | Nitro AN515-44              | [d7a2c59432](https://linux-hardware.org/?probe=d7a2c59432) | Jun 05, 2023 |
| Dell          | Latitude E7450              | [e19dbd1a84](https://linux-hardware.org/?probe=e19dbd1a84) | Jun 05, 2023 |
| Dell          | XPS 13 9305                 | [78459738e9](https://linux-hardware.org/?probe=78459738e9) | Jun 05, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | [9a1c9022af](https://linux-hardware.org/?probe=9a1c9022af) | Jun 05, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [bb29d15c61](https://linux-hardware.org/?probe=bb29d15c61) | Jun 05, 2023 |
| Acer          | Predator PT515-51           | [5c3daec3c7](https://linux-hardware.org/?probe=5c3daec3c7) | Jun 05, 2023 |
| GPU Compan... | GWTC116-2                   | [de8a3d6dab](https://linux-hardware.org/?probe=de8a3d6dab) | Jun 05, 2023 |
| Samsung       | 950XEE                      | [cc47fd0df0](https://linux-hardware.org/?probe=cc47fd0df0) | Jun 05, 2023 |
| Lenovo        | ThinkPad E450 20DC003WUS    | [6abecb1cd3](https://linux-hardware.org/?probe=6abecb1cd3) | Jun 05, 2023 |
| ASUSTek       | X540UP                      | [b6613930a2](https://linux-hardware.org/?probe=b6613930a2) | Jun 05, 2023 |
| Dell          | Precision 7540              | [a10ecca056](https://linux-hardware.org/?probe=a10ecca056) | Jun 04, 2023 |
| Sony          | VPCSC1AFM                   | [2cf80cf628](https://linux-hardware.org/?probe=2cf80cf628) | Jun 04, 2023 |
| Apple         | MacBookPro8,1               | [e3f89d1faa](https://linux-hardware.org/?probe=e3f89d1faa) | Jun 04, 2023 |
| ASUSTek       | X540UP                      | [5102ecc266](https://linux-hardware.org/?probe=5102ecc266) | Jun 04, 2023 |
| MECHREVO      | Code01 Ver2.0               | [d311022361](https://linux-hardware.org/?probe=d311022361) | Jun 04, 2023 |
| MSI           | Modern 14 C12M              | [a5d1a0e656](https://linux-hardware.org/?probe=a5d1a0e656) | Jun 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [dfb8881ffe](https://linux-hardware.org/?probe=dfb8881ffe) | Jun 04, 2023 |
| HP            | Laptop 17-cp0xxx            | [253c561829](https://linux-hardware.org/?probe=253c561829) | Jun 04, 2023 |
| AMI           | Intel                       | [cd2beb79d2](https://linux-hardware.org/?probe=cd2beb79d2) | Jun 04, 2023 |
| UNOWHY        | Y13G002S4EI                 | [f1b932f397](https://linux-hardware.org/?probe=f1b932f397) | Jun 04, 2023 |
| Lenovo        | B570 HuronRiver Platform    | [43cffb0d0f](https://linux-hardware.org/?probe=43cffb0d0f) | Jun 04, 2023 |
| Lenovo        | B570 HuronRiver Platform    | [cef2bf28c9](https://linux-hardware.org/?probe=cef2bf28c9) | Jun 04, 2023 |
| Dell          | Latitude D620               | [0e1b7f4320](https://linux-hardware.org/?probe=0e1b7f4320) | Jun 03, 2023 |
| HP            | ZBook 15 G2                 | [19ed8e22e6](https://linux-hardware.org/?probe=19ed8e22e6) | Jun 03, 2023 |
| Apple         | MacBookPro8,1               | [7bdff81d7d](https://linux-hardware.org/?probe=7bdff81d7d) | Jun 03, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | [f241c0cf38](https://linux-hardware.org/?probe=f241c0cf38) | Jun 03, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | [aea1babfb7](https://linux-hardware.org/?probe=aea1babfb7) | Jun 03, 2023 |
| Dell          | Latitude E6420              | [4d1ad8d52a](https://linux-hardware.org/?probe=4d1ad8d52a) | Jun 03, 2023 |
| Acer          | Aspire AV15-51              | [41e5c1790c](https://linux-hardware.org/?probe=41e5c1790c) | Jun 03, 2023 |
| Acer          | Aspire AV15-51              | [d583c74274](https://linux-hardware.org/?probe=d583c74274) | Jun 03, 2023 |
| Acer          | Aspire AV15-51              | [7ed9ba7165](https://linux-hardware.org/?probe=7ed9ba7165) | Jun 03, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [1aa286ccff](https://linux-hardware.org/?probe=1aa286ccff) | Jun 03, 2023 |
| Apple         | MacBookAir6,1               | [20a14caf03](https://linux-hardware.org/?probe=20a14caf03) | Jun 03, 2023 |
| Lenovo        | ThinkPad X220 4291WSH       | [f95d5c3046](https://linux-hardware.org/?probe=f95d5c3046) | Jun 03, 2023 |
| HONOR         | BBR-WAX9                    | [fe03659a55](https://linux-hardware.org/?probe=fe03659a55) | Jun 02, 2023 |
| Sony          | SVF1521A1EW                 | [4e3fe0308e](https://linux-hardware.org/?probe=4e3fe0308e) | Jun 02, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [d856669333](https://linux-hardware.org/?probe=d856669333) | Jun 02, 2023 |
| Gigabyte      | G5 GE                       | [558ee7e63f](https://linux-hardware.org/?probe=558ee7e63f) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [3a51aa06b9](https://linux-hardware.org/?probe=3a51aa06b9) | Jun 02, 2023 |
| Lenovo        | ThinkPad T460 20FMS0WN00    | [f576f54ff2](https://linux-hardware.org/?probe=f576f54ff2) | Jun 02, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XI... | [e920b77fbb](https://linux-hardware.org/?probe=e920b77fbb) | Jun 02, 2023 |
| HP            | Unknown                     | [626075d6f2](https://linux-hardware.org/?probe=626075d6f2) | Jun 02, 2023 |
| HP            | Unknown                     | [2289bb8d24](https://linux-hardware.org/?probe=2289bb8d24) | Jun 02, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [0a6e1e6be8](https://linux-hardware.org/?probe=0a6e1e6be8) | Jun 02, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | [13adb1e221](https://linux-hardware.org/?probe=13adb1e221) | Jun 02, 2023 |
| Acer          | Nitro AN515-51              | [2dc3c08466](https://linux-hardware.org/?probe=2dc3c08466) | Jun 02, 2023 |
| Lenovo        | ThinkPad T430 2350BG7       | [29d6e72544](https://linux-hardware.org/?probe=29d6e72544) | Jun 02, 2023 |
| Lenovo        | ThinkPad X220 42911H8       | [e28e041a5c](https://linux-hardware.org/?probe=e28e041a5c) | Jun 02, 2023 |
| Lenovo        | ThinkPad X220 42911H8       | [dcba8dc683](https://linux-hardware.org/?probe=dcba8dc683) | Jun 02, 2023 |
| Dell          | Latitude 7400               | [ef9ef10e4e](https://linux-hardware.org/?probe=ef9ef10e4e) | Jun 02, 2023 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [ca904474bf](https://linux-hardware.org/?probe=ca904474bf) | Jun 02, 2023 |
| Positivo B... | VJFE43F11X-XXXXXX           | [ea337d3d2a](https://linux-hardware.org/?probe=ea337d3d2a) | Jun 02, 2023 |
| HP            | EliteBook 8470p             | [bc606409ff](https://linux-hardware.org/?probe=bc606409ff) | Jun 01, 2023 |
| HONOR         | BBR-WAX9                    | [0a536c1198](https://linux-hardware.org/?probe=0a536c1198) | Jun 01, 2023 |
| UNOWHY        | Y13G002S4EI                 | [0bb0a8be66](https://linux-hardware.org/?probe=0bb0a8be66) | Jun 01, 2023 |
| HP            | ZBook 15 G3                 | [28eec89b69](https://linux-hardware.org/?probe=28eec89b69) | Jun 01, 2023 |
| Dell          | Latitude 7490               | [3cb9ad156f](https://linux-hardware.org/?probe=3cb9ad156f) | Jun 01, 2023 |
| Dell          | Precision 7540              | [de2fc5bc92](https://linux-hardware.org/?probe=de2fc5bc92) | Jun 01, 2023 |
| Timi          | A35S                        | [c9ce47a446](https://linux-hardware.org/?probe=c9ce47a446) | Jun 01, 2023 |
| Dell          | Latitude 5490               | [34dde30b90](https://linux-hardware.org/?probe=34dde30b90) | Jun 01, 2023 |
| Toshiba       | TECRA Z40t-C                | [f3dc10c852](https://linux-hardware.org/?probe=f3dc10c852) | Jun 01, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U7C... | [8c16cec2e8](https://linux-hardware.org/?probe=8c16cec2e8) | Jun 01, 2023 |
| Dell          | Latitude 5531               | [5dc2ae0939](https://linux-hardware.org/?probe=5dc2ae0939) | Jun 01, 2023 |
| Toshiba       | TECRA Z40t-C                | [1d128e6153](https://linux-hardware.org/?probe=1d128e6153) | Jun 01, 2023 |
| Timi          | TM1801                      | [aa1db210df](https://linux-hardware.org/?probe=aa1db210df) | Jun 01, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [0b0c375bb8](https://linux-hardware.org/?probe=0b0c375bb8) | May 31, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [65b03710b2](https://linux-hardware.org/?probe=65b03710b2) | May 31, 2023 |
| Acer          | Nitro AN515-42              | [fc808ec2fd](https://linux-hardware.org/?probe=fc808ec2fd) | May 31, 2023 |
| Lenovo        | ThinkPad T430 2350BG7       | [a09171afde](https://linux-hardware.org/?probe=a09171afde) | May 31, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | [f1e9073b3d](https://linux-hardware.org/?probe=f1e9073b3d) | May 31, 2023 |
| Dell          | Inspiron 15 5510            | [bd2319fd67](https://linux-hardware.org/?probe=bd2319fd67) | May 31, 2023 |
| Intel Clie... | LAPRC710                    | [ef0d589f75](https://linux-hardware.org/?probe=ef0d589f75) | May 31, 2023 |
| HP            | Unknown                     | [3eb658702b](https://linux-hardware.org/?probe=3eb658702b) | May 31, 2023 |
| Apple         | MacBookPro9,1               | [0b958e0c5c](https://linux-hardware.org/?probe=0b958e0c5c) | May 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [93ac1fb021](https://linux-hardware.org/?probe=93ac1fb021) | May 31, 2023 |
| Lenovo        | ZhaoYangN4620Z 20A0Z037K... | [7e07cca977](https://linux-hardware.org/?probe=7e07cca977) | May 31, 2023 |
| Acer          | Nitro AN515-42              | [75f612c4db](https://linux-hardware.org/?probe=75f612c4db) | May 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [32ba69494b](https://linux-hardware.org/?probe=32ba69494b) | May 31, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | [2f61fcf47d](https://linux-hardware.org/?probe=2f61fcf47d) | May 31, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [6d6d7c65a8](https://linux-hardware.org/?probe=6d6d7c65a8) | May 31, 2023 |
| ASUSTek       | ROG Strix G712LW_G712LW     | [5e96e1c54e](https://linux-hardware.org/?probe=5e96e1c54e) | May 31, 2023 |
| Lenovo        | ThinkPad X270 20HMS1RM02    | [8f39bcbb17](https://linux-hardware.org/?probe=8f39bcbb17) | May 30, 2023 |
| Acer          | Nitro AN515-51              | [d3ee3757e0](https://linux-hardware.org/?probe=d3ee3757e0) | May 30, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [29ec12f64d](https://linux-hardware.org/?probe=29ec12f64d) | May 30, 2023 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | [5881fb6ae2](https://linux-hardware.org/?probe=5881fb6ae2) | May 30, 2023 |
| Notebook      | P15SM-A/SM1-A               | [e71d8e3bc0](https://linux-hardware.org/?probe=e71d8e3bc0) | May 30, 2023 |
| Lenovo        | ThinkPad T480 20L6S09E00    | [894bac5d62](https://linux-hardware.org/?probe=894bac5d62) | May 30, 2023 |
| HP            | ENVY Laptop 16-h0xxx        | [59e9fd9749](https://linux-hardware.org/?probe=59e9fd9749) | May 30, 2023 |
| HP            | Unknown                     | [2007104aeb](https://linux-hardware.org/?probe=2007104aeb) | May 30, 2023 |
| Dell          | XPS 13 9310                 | [a3e4ffb4fd](https://linux-hardware.org/?probe=a3e4ffb4fd) | May 30, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [287ebf0b10](https://linux-hardware.org/?probe=287ebf0b10) | May 30, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [74447476fe](https://linux-hardware.org/?probe=74447476fe) | May 30, 2023 |
| HP            | EliteBook 6930p             | [882f43330b](https://linux-hardware.org/?probe=882f43330b) | May 30, 2023 |
| Dell          | Precision 5540              | [2f3cdafe90](https://linux-hardware.org/?probe=2f3cdafe90) | May 30, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [360e8fd5e5](https://linux-hardware.org/?probe=360e8fd5e5) | May 30, 2023 |
| VPU Compan... | VWNC51518                   | [16329bde51](https://linux-hardware.org/?probe=16329bde51) | May 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [7816244e1a](https://linux-hardware.org/?probe=7816244e1a) | May 30, 2023 |
| MSI           | GF65 Thin 10UE              | [98e2096ab6](https://linux-hardware.org/?probe=98e2096ab6) | May 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [5839982a52](https://linux-hardware.org/?probe=5839982a52) | May 29, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [048a3a0f30](https://linux-hardware.org/?probe=048a3a0f30) | May 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [3933dfe4f0](https://linux-hardware.org/?probe=3933dfe4f0) | May 29, 2023 |
| Lenovo        | ThinkPad E490 20N8000RPG    | [73b8bfb3a5](https://linux-hardware.org/?probe=73b8bfb3a5) | May 29, 2023 |
| Sony          | VPCSA25GB                   | [981a09e39a](https://linux-hardware.org/?probe=981a09e39a) | May 29, 2023 |
| Sony          | VPCSA25GB                   | [e36e944a92](https://linux-hardware.org/?probe=e36e944a92) | May 29, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [8e09d71949](https://linux-hardware.org/?probe=8e09d71949) | May 29, 2023 |
| Acer          | Aspire A315-51              | [d6f1c2bdbd](https://linux-hardware.org/?probe=d6f1c2bdbd) | May 29, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [230a02bfda](https://linux-hardware.org/?probe=230a02bfda) | May 29, 2023 |
| Lenovo        | ThinkPad T440p 20AWS19P0... | [8d25da413c](https://linux-hardware.org/?probe=8d25da413c) | May 29, 2023 |
| ASUSTek       | VivoBook S13 X330FN         | [e94b6fbf06](https://linux-hardware.org/?probe=e94b6fbf06) | May 29, 2023 |
| Dell          | Inspiron 7577               | [94e5a63c07](https://linux-hardware.org/?probe=94e5a63c07) | May 29, 2023 |
| Apple         | MacBookAir7,2               | [2f44574d7c](https://linux-hardware.org/?probe=2f44574d7c) | May 29, 2023 |
| HP            | Laptop 15-dw0xxx            | [a430b5287c](https://linux-hardware.org/?probe=a430b5287c) | May 29, 2023 |
| HP            | Pavilion g4                 | [12bef484db](https://linux-hardware.org/?probe=12bef484db) | May 29, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [14e5763b6f](https://linux-hardware.org/?probe=14e5763b6f) | May 29, 2023 |
| Lenovo        | ThinkPad Edge 0301DCU       | [5b7394bc19](https://linux-hardware.org/?probe=5b7394bc19) | May 28, 2023 |
| Apple         | MacBookAir7,2               | [5e146ef326](https://linux-hardware.org/?probe=5e146ef326) | May 28, 2023 |
| HP            | Pavilion Laptop 14-ce3xx... | [01d3e0d237](https://linux-hardware.org/?probe=01d3e0d237) | May 28, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [1b4eb11af8](https://linux-hardware.org/?probe=1b4eb11af8) | May 28, 2023 |
| Dell          | XPS 9320                    | [33e7d964ad](https://linux-hardware.org/?probe=33e7d964ad) | May 28, 2023 |
| Acer          | Aspire A315-41              | [8bdf6722e2](https://linux-hardware.org/?probe=8bdf6722e2) | May 28, 2023 |
| Dell          | Inspiron 3542               | [423fe90cad](https://linux-hardware.org/?probe=423fe90cad) | May 28, 2023 |
| Razer         | Blade 15 Advanced Model ... | [92b96250d1](https://linux-hardware.org/?probe=92b96250d1) | May 28, 2023 |
| Toshiba       | Satellite C850-C5K          | [481789fa1e](https://linux-hardware.org/?probe=481789fa1e) | May 28, 2023 |
| Positivo      | N1250                       | [f014b93eba](https://linux-hardware.org/?probe=f014b93eba) | May 28, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [dc2b5e538f](https://linux-hardware.org/?probe=dc2b5e538f) | May 27, 2023 |
| Lenovo        | ThinkPad X240 20AMS1UB1H    | [4147fc8cb7](https://linux-hardware.org/?probe=4147fc8cb7) | May 27, 2023 |
| Dell          | Latitude E6330              | [dd302db25c](https://linux-hardware.org/?probe=dd302db25c) | May 27, 2023 |
| Lenovo        | ThinkPad X240 20AMS1UB1H    | [d9295f37bc](https://linux-hardware.org/?probe=d9295f37bc) | May 27, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [f068d88c01](https://linux-hardware.org/?probe=f068d88c01) | May 27, 2023 |
| Lenovo        | ThinkPad T470 20HES0FA03    | [c8c8087ee8](https://linux-hardware.org/?probe=c8c8087ee8) | May 27, 2023 |
| HP            | Laptop 14s-dk0xxx           | [902b837f1a](https://linux-hardware.org/?probe=902b837f1a) | May 27, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [767c697ac8](https://linux-hardware.org/?probe=767c697ac8) | May 27, 2023 |
| Dell          | Latitude E6330              | [f93b318d71](https://linux-hardware.org/?probe=f93b318d71) | May 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [82cad47c63](https://linux-hardware.org/?probe=82cad47c63) | May 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [09cc59aa19](https://linux-hardware.org/?probe=09cc59aa19) | May 27, 2023 |
| HP            | Pavilion x2 Detachable      | [e21476b6d2](https://linux-hardware.org/?probe=e21476b6d2) | May 26, 2023 |
| HP            | Laptop 14s-dk0xxx           | [5cf35078b0](https://linux-hardware.org/?probe=5cf35078b0) | May 26, 2023 |
| Acer          | Aspire F5-573G              | [f8ec1083ad](https://linux-hardware.org/?probe=f8ec1083ad) | May 26, 2023 |
| Acer          | Aspire F5-573G              | [eb636c0b30](https://linux-hardware.org/?probe=eb636c0b30) | May 26, 2023 |
| AAEON         | AEC-6637                    | [19050f7ccd](https://linux-hardware.org/?probe=19050f7ccd) | May 26, 2023 |
| Lenovo        | ThinkPad T460s 20F90058G... | [71a2e90192](https://linux-hardware.org/?probe=71a2e90192) | May 26, 2023 |
| Dell          | XPS 13 9310                 | [689eec8b51](https://linux-hardware.org/?probe=689eec8b51) | May 26, 2023 |
| Notebook      | NV4xPZ                      | [750cb90d83](https://linux-hardware.org/?probe=750cb90d83) | May 26, 2023 |
| Intel Clie... | LAPBC510                    | [fe45f8ba3c](https://linux-hardware.org/?probe=fe45f8ba3c) | May 26, 2023 |
| Acer          | Aspire V3-551               | [9d609ccd4a](https://linux-hardware.org/?probe=9d609ccd4a) | May 26, 2023 |
| Dell          | Inspiron 15-3567            | [0f79b43742](https://linux-hardware.org/?probe=0f79b43742) | May 26, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | [29d761bff5](https://linux-hardware.org/?probe=29d761bff5) | May 26, 2023 |
| Dell          | G15 5525                    | [b2c8f44d8b](https://linux-hardware.org/?probe=b2c8f44d8b) | May 26, 2023 |
| Samsung       | 550XDA                      | [6cc9f3cbe4](https://linux-hardware.org/?probe=6cc9f3cbe4) | May 26, 2023 |
| ASUSTek       | X705UVR                     | [bedbf77e16](https://linux-hardware.org/?probe=bedbf77e16) | May 25, 2023 |
| Lenovo        | ThinkPad T490 20N3S5DQ02    | [bb00a96df8](https://linux-hardware.org/?probe=bb00a96df8) | May 25, 2023 |
| Dell          | Precision 7540              | [99c7b41c6b](https://linux-hardware.org/?probe=99c7b41c6b) | May 25, 2023 |
| Unknown       | Unknown                     | [cfaffcaa0a](https://linux-hardware.org/?probe=cfaffcaa0a) | May 25, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [913f21a49c](https://linux-hardware.org/?probe=913f21a49c) | May 25, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81FN      | [3304e68c39](https://linux-hardware.org/?probe=3304e68c39) | May 25, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [5dd56ed986](https://linux-hardware.org/?probe=5dd56ed986) | May 25, 2023 |
| ASUSTek       | GL553VD                     | [51dbf3c463](https://linux-hardware.org/?probe=51dbf3c463) | May 25, 2023 |
| Dell          | Vostro 3480                 | [490c47960a](https://linux-hardware.org/?probe=490c47960a) | May 25, 2023 |
| Lenovo        | ThinkPad T440p 20AW0045M... | [355e03f684](https://linux-hardware.org/?probe=355e03f684) | May 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [9294d16ea5](https://linux-hardware.org/?probe=9294d16ea5) | May 25, 2023 |
| Google        | Voxel                       | [9dae4b7464](https://linux-hardware.org/?probe=9dae4b7464) | May 25, 2023 |
| HP            | Victus by Laptop 16-d1xx... | [d03d942df4](https://linux-hardware.org/?probe=d03d942df4) | May 24, 2023 |
| Dell          | Precision 7530              | [5cf37f39f4](https://linux-hardware.org/?probe=5cf37f39f4) | May 24, 2023 |
| Dell          | Precision 7540              | [65605ee5e8](https://linux-hardware.org/?probe=65605ee5e8) | May 24, 2023 |
| Dell          | Vostro 3480                 | [ae4f8dba2c](https://linux-hardware.org/?probe=ae4f8dba2c) | May 24, 2023 |
| Lenovo        | G500s 20245                 | [dd15a8197e](https://linux-hardware.org/?probe=dd15a8197e) | May 24, 2023 |
| Lenovo        | ThinkPad T530 24297XG       | [520e3d90a6](https://linux-hardware.org/?probe=520e3d90a6) | May 24, 2023 |
| ASUSTek       | UL30A                       | [d7ab3b0ed3](https://linux-hardware.org/?probe=d7ab3b0ed3) | May 24, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [1280876877](https://linux-hardware.org/?probe=1280876877) | May 24, 2023 |
| ASUSTek       | X542UN                      | [29547f8e99](https://linux-hardware.org/?probe=29547f8e99) | May 24, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [ba72bf9d52](https://linux-hardware.org/?probe=ba72bf9d52) | May 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [64ceddcdd4](https://linux-hardware.org/?probe=64ceddcdd4) | May 24, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [d99af6bab2](https://linux-hardware.org/?probe=d99af6bab2) | May 24, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [fff0e981f2](https://linux-hardware.org/?probe=fff0e981f2) | May 23, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [0dfd1ede62](https://linux-hardware.org/?probe=0dfd1ede62) | May 23, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [428a152134](https://linux-hardware.org/?probe=428a152134) | May 23, 2023 |
| Dell          | Inspiron 3593               | [715800f05d](https://linux-hardware.org/?probe=715800f05d) | May 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [691b17e221](https://linux-hardware.org/?probe=691b17e221) | May 23, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [eaa5b878d3](https://linux-hardware.org/?probe=eaa5b878d3) | May 23, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | [90235c6d2e](https://linux-hardware.org/?probe=90235c6d2e) | May 23, 2023 |
| HUAWEI        | CREF-XX                     | [39ff25bc94](https://linux-hardware.org/?probe=39ff25bc94) | May 23, 2023 |
| MSI           | GF65 Thin 9SE               | [c485674a13](https://linux-hardware.org/?probe=c485674a13) | May 23, 2023 |
| ASUSTek       | N75SF                       | [a385375f4d](https://linux-hardware.org/?probe=a385375f4d) | May 23, 2023 |
| Dell          | G5 5587                     | [18faf1497f](https://linux-hardware.org/?probe=18faf1497f) | May 23, 2023 |
| Apple         | MacBookPro8,1               | [fadd25f4c5](https://linux-hardware.org/?probe=fadd25f4c5) | May 23, 2023 |
| Lenovo        | ThinkPad E495 20NE001GMX    | [cc966f1ede](https://linux-hardware.org/?probe=cc966f1ede) | May 23, 2023 |
| HP            | ENVY 15                     | [85a97390d5](https://linux-hardware.org/?probe=85a97390d5) | May 23, 2023 |
| Lenovo        | Legion Y7000P IAH7 82RC     | [c4040a0905](https://linux-hardware.org/?probe=c4040a0905) | May 23, 2023 |
| Lenovo        | ThinkPad T420 4180Q3U       | [56042328ac](https://linux-hardware.org/?probe=56042328ac) | May 23, 2023 |
| Lenovo        | ThinkPad T420 4180Q3U       | [0d63b518e4](https://linux-hardware.org/?probe=0d63b518e4) | May 23, 2023 |
| ASUSTek       | ET2321I                     | [829fe9b078](https://linux-hardware.org/?probe=829fe9b078) | May 23, 2023 |
| Dell          | Precision 7540              | [95bbab11f1](https://linux-hardware.org/?probe=95bbab11f1) | May 23, 2023 |
| HP            | Pavilion x2 Detachable      | [f9f3305d0b](https://linux-hardware.org/?probe=f9f3305d0b) | May 23, 2023 |
| UNOWHY        | Y13G011S4EI                 | [3642f34cd6](https://linux-hardware.org/?probe=3642f34cd6) | May 23, 2023 |
| Lenovo        | ThinkPad L480 20LTA01LLM    | [ed45fc495a](https://linux-hardware.org/?probe=ed45fc495a) | May 22, 2023 |
| HP            | EliteBook 840 G5            | [74a0ea4304](https://linux-hardware.org/?probe=74a0ea4304) | May 22, 2023 |
| Lenovo        | ThinkPad T490s 20NYS7K91... | [7d81e00b27](https://linux-hardware.org/?probe=7d81e00b27) | May 22, 2023 |
| Framework     | Laptop                      | [7715f5f056](https://linux-hardware.org/?probe=7715f5f056) | May 22, 2023 |
| Apple         | MacBookPro5,5               | [a4b0d5fd13](https://linux-hardware.org/?probe=a4b0d5fd13) | May 22, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | [c492073bac](https://linux-hardware.org/?probe=c492073bac) | May 22, 2023 |
| Dell          | Precision 5560              | [1fc79f4cc0](https://linux-hardware.org/?probe=1fc79f4cc0) | May 22, 2023 |
| HP            | ENVY 15                     | [21a38278ca](https://linux-hardware.org/?probe=21a38278ca) | May 21, 2023 |
| MSI           | Modern 14 B11MOL            | [7bc8f5e875](https://linux-hardware.org/?probe=7bc8f5e875) | May 21, 2023 |
| Micro Elec... | MG-VCP17I-3070              | [8c8c77d9a3](https://linux-hardware.org/?probe=8c8c77d9a3) | May 21, 2023 |
| HP            | Laptop 15-dy5xxx            | [3ab3a101e8](https://linux-hardware.org/?probe=3ab3a101e8) | May 21, 2023 |
| Lenovo        | ThinkPad T460s 20FAS0W90... | [0b3265b088](https://linux-hardware.org/?probe=0b3265b088) | May 21, 2023 |
| ASUSTek       | ZenBook UX425JA_UX425JA     | [916d381f2f](https://linux-hardware.org/?probe=916d381f2f) | May 21, 2023 |
| Dell          | XPS 13 9310                 | [19be933f8a](https://linux-hardware.org/?probe=19be933f8a) | May 21, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [8ec7bb4682](https://linux-hardware.org/?probe=8ec7bb4682) | May 21, 2023 |
| Lenovo        | ThinkBook 14 G5+ ARP 21H... | [5a30bf445a](https://linux-hardware.org/?probe=5a30bf445a) | May 21, 2023 |
| Lenovo        | ThinkPad Helix 36986DG      | [a6b4b230da](https://linux-hardware.org/?probe=a6b4b230da) | May 21, 2023 |
| MSI           | Summit E13FlipEvo A11MT     | [ef2b821a84](https://linux-hardware.org/?probe=ef2b821a84) | May 21, 2023 |
| ASUSTek       | G75VW                       | [7063bb70eb](https://linux-hardware.org/?probe=7063bb70eb) | May 21, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [fc75b5ebda](https://linux-hardware.org/?probe=fc75b5ebda) | May 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | [4fff2c9c8a](https://linux-hardware.org/?probe=4fff2c9c8a) | May 20, 2023 |
| HP            | 255 G8 Notebook PC          | [157b535164](https://linux-hardware.org/?probe=157b535164) | May 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [b695d18b13](https://linux-hardware.org/?probe=b695d18b13) | May 20, 2023 |
| HP            | ZBook 17 G2                 | [50b19fc413](https://linux-hardware.org/?probe=50b19fc413) | May 20, 2023 |
| Lenovo        | G500s 20245                 | [fc125408b5](https://linux-hardware.org/?probe=fc125408b5) | May 20, 2023 |
| Lenovo        | IdeaPad U430 Touch 20270    | [36d4349090](https://linux-hardware.org/?probe=36d4349090) | May 20, 2023 |
| Google        | Akemi                       | [595f8b1a24](https://linux-hardware.org/?probe=595f8b1a24) | May 20, 2023 |
| Dell          | Vostro 15-3568              | [5c6dbc1b8a](https://linux-hardware.org/?probe=5c6dbc1b8a) | May 20, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [0f8329fecb](https://linux-hardware.org/?probe=0f8329fecb) | May 20, 2023 |
| Lenovo        | ThinkPad W530 24382LU       | [908f53f58b](https://linux-hardware.org/?probe=908f53f58b) | May 20, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [e464ddd1b6](https://linux-hardware.org/?probe=e464ddd1b6) | May 20, 2023 |
| HP            | Laptop 17-by0061st          | [68e551f58a](https://linux-hardware.org/?probe=68e551f58a) | May 20, 2023 |
| Apple         | MacBookPro12,1              | [c25d920f3d](https://linux-hardware.org/?probe=c25d920f3d) | May 20, 2023 |
| HP            | Pavilion dv3                | [34c6a2c14a](https://linux-hardware.org/?probe=34c6a2c14a) | May 20, 2023 |
| Acer          | Nitro AN515-54              | [4f27fb9c64](https://linux-hardware.org/?probe=4f27fb9c64) | May 20, 2023 |
| Apple         | MacBookPro9,2               | [ac3d3ea87c](https://linux-hardware.org/?probe=ac3d3ea87c) | May 19, 2023 |
| HP            | Laptop 15-dw2xxx            | [7d7bdf142c](https://linux-hardware.org/?probe=7d7bdf142c) | May 19, 2023 |
| HP            | Laptop 15-dw2xxx            | [e0a1fa9223](https://linux-hardware.org/?probe=e0a1fa9223) | May 19, 2023 |
| Lenovo        | G500s 20245                 | [8c6b9dc52f](https://linux-hardware.org/?probe=8c6b9dc52f) | May 19, 2023 |
| Acer          | Aspire A515-57              | [3272ba5e49](https://linux-hardware.org/?probe=3272ba5e49) | May 19, 2023 |
| Dell          | Precision 5470              | [e600af2d5a](https://linux-hardware.org/?probe=e600af2d5a) | May 19, 2023 |
| Lenovo        | ThinkPad T480 20L5S1S000    | [30950ddd01](https://linux-hardware.org/?probe=30950ddd01) | May 19, 2023 |
| Lenovo        | ThinkPad T61 6463B45        | [a2445821f3](https://linux-hardware.org/?probe=a2445821f3) | May 19, 2023 |
| Google        | Candy                       | [2ed0555d82](https://linux-hardware.org/?probe=2ed0555d82) | May 19, 2023 |
| Lenovo        | ThinkPad P52 20MAS88000     | [f9a256566b](https://linux-hardware.org/?probe=f9a256566b) | May 19, 2023 |
| MSI           | Stealth 15M B12UE           | [d6e14242b8](https://linux-hardware.org/?probe=d6e14242b8) | May 19, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [7f2ca00e36](https://linux-hardware.org/?probe=7f2ca00e36) | May 18, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | [f811501691](https://linux-hardware.org/?probe=f811501691) | May 18, 2023 |
| Dell          | Precision 3560              | [f83f42ab2f](https://linux-hardware.org/?probe=f83f42ab2f) | May 18, 2023 |
| MSI           | GE72 7RE                    | [15a31e188f](https://linux-hardware.org/?probe=15a31e188f) | May 18, 2023 |
| Dell          | XPS 13 9305                 | [3eb1bee421](https://linux-hardware.org/?probe=3eb1bee421) | May 18, 2023 |
| MSI           | GS70 2PC Stealth            | [254f42a469](https://linux-hardware.org/?probe=254f42a469) | May 18, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [d4fc64a451](https://linux-hardware.org/?probe=d4fc64a451) | May 18, 2023 |
| HP            | 630                         | [bd7bdf5942](https://linux-hardware.org/?probe=bd7bdf5942) | May 18, 2023 |
| Dell          | Precision 7540              | [98727430ff](https://linux-hardware.org/?probe=98727430ff) | May 18, 2023 |
| Lenovo        | IdeaPad Z470                | [158feeb98d](https://linux-hardware.org/?probe=158feeb98d) | May 18, 2023 |
| Lenovo        | ThinkPad Edge E430 3254T... | [681fd36c12](https://linux-hardware.org/?probe=681fd36c12) | May 18, 2023 |
| Dell          | Precision 5520              | [6e4c751579](https://linux-hardware.org/?probe=6e4c751579) | May 18, 2023 |
| Dell          | Inspiron 15 3511            | [255961cb74](https://linux-hardware.org/?probe=255961cb74) | May 18, 2023 |
| Dell          | Latitude 7490               | [392cde1432](https://linux-hardware.org/?probe=392cde1432) | May 17, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [b22bdcc636](https://linux-hardware.org/?probe=b22bdcc636) | May 17, 2023 |
| Dell          | XPS 13 9305                 | [6adf226281](https://linux-hardware.org/?probe=6adf226281) | May 17, 2023 |
| HP            | ProBook 4540s               | [2a2712560e](https://linux-hardware.org/?probe=2a2712560e) | May 17, 2023 |
| HP            | ENVY 15                     | [4576cea8b0](https://linux-hardware.org/?probe=4576cea8b0) | May 17, 2023 |
| Acer          | Aspire E5-576G              | [6cba75fa36](https://linux-hardware.org/?probe=6cba75fa36) | May 17, 2023 |
| HP            | OMEN by Laptop 15-ce0xx     | [7d818512b8](https://linux-hardware.org/?probe=7d818512b8) | May 17, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [f31be9149e](https://linux-hardware.org/?probe=f31be9149e) | May 17, 2023 |
| Dell          | XPS 13 7390                 | [51ff9a820a](https://linux-hardware.org/?probe=51ff9a820a) | May 16, 2023 |
| Dell          | XPS 13 7390                 | [e98b404c17](https://linux-hardware.org/?probe=e98b404c17) | May 16, 2023 |
| HP            | EliteBook 8540p             | [4f5efbc9fe](https://linux-hardware.org/?probe=4f5efbc9fe) | May 16, 2023 |
| ASUSTek       | G73Sw                       | [ec9817e3d1](https://linux-hardware.org/?probe=ec9817e3d1) | May 16, 2023 |
| HP            | EliteBook 8540p             | [8041b17525](https://linux-hardware.org/?probe=8041b17525) | May 16, 2023 |
| Dell          | Latitude 7420               | [4e1680877b](https://linux-hardware.org/?probe=4e1680877b) | May 16, 2023 |
| Samsung       | 550XDA                      | [75bc1cdfb3](https://linux-hardware.org/?probe=75bc1cdfb3) | May 16, 2023 |
| HP            | 630                         | [3527caae6f](https://linux-hardware.org/?probe=3527caae6f) | May 16, 2023 |
| HP            | 630                         | [f34f960671](https://linux-hardware.org/?probe=f34f960671) | May 16, 2023 |
| Dell          | Latitude 7430               | [d137c2d73b](https://linux-hardware.org/?probe=d137c2d73b) | May 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [055aae99b8](https://linux-hardware.org/?probe=055aae99b8) | May 16, 2023 |
| HP            | ProBook 450 G2              | [a399b17822](https://linux-hardware.org/?probe=a399b17822) | May 16, 2023 |
| Acer          | Aspire A515-45              | [2375fac142](https://linux-hardware.org/?probe=2375fac142) | May 15, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [2ffc331e90](https://linux-hardware.org/?probe=2ffc331e90) | May 15, 2023 |
| MSI           | Summit E14FlipEvo A13MT     | [60e19220b9](https://linux-hardware.org/?probe=60e19220b9) | May 15, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [38482c1a10](https://linux-hardware.org/?probe=38482c1a10) | May 15, 2023 |
| Lenovo        | IdeaPad U430 Touch 20270    | [1e7e92e7e8](https://linux-hardware.org/?probe=1e7e92e7e8) | May 15, 2023 |
| HP            | Pavilion x2 Detachable      | [e9e5b21145](https://linux-hardware.org/?probe=e9e5b21145) | May 15, 2023 |
| HP            | Pavilion x2 Detachable      | [34c6621991](https://linux-hardware.org/?probe=34c6621991) | May 15, 2023 |
| Dell          | Latitude E6520              | [e4d8abe098](https://linux-hardware.org/?probe=e4d8abe098) | May 15, 2023 |
| Dell          | Latitude 5490               | [0a6ee8c111](https://linux-hardware.org/?probe=0a6ee8c111) | May 14, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [e9ce1757ae](https://linux-hardware.org/?probe=e9ce1757ae) | May 14, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | [66e7dc292e](https://linux-hardware.org/?probe=66e7dc292e) | May 14, 2023 |
| Lenovo        | ThinkPad T480 20L6A0XKUK    | [8921a6d64e](https://linux-hardware.org/?probe=8921a6d64e) | May 14, 2023 |
| HP            | ProBook 450 G2              | [2ab0709f22](https://linux-hardware.org/?probe=2ab0709f22) | May 14, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [0060b3cb1c](https://linux-hardware.org/?probe=0060b3cb1c) | May 14, 2023 |
| Lenovo        | ThinkBook Plus G2 ITG 20... | [2881ffcb77](https://linux-hardware.org/?probe=2881ffcb77) | May 14, 2023 |
| Dell          | Latitude E6520              | [78aaf99b7b](https://linux-hardware.org/?probe=78aaf99b7b) | May 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [72eaf980ad](https://linux-hardware.org/?probe=72eaf980ad) | May 14, 2023 |
| Lenovo        | G50-45 80E3                 | [9298a8529a](https://linux-hardware.org/?probe=9298a8529a) | May 14, 2023 |
| HP            | 630                         | [40e895a75a](https://linux-hardware.org/?probe=40e895a75a) | May 14, 2023 |
| Unknown       | Unknown                     | [077df36551](https://linux-hardware.org/?probe=077df36551) | May 14, 2023 |
| Dell          | XPS 15 9560                 | [d0a6a8e29e](https://linux-hardware.org/?probe=d0a6a8e29e) | May 14, 2023 |
| HP            | G50                         | [719a212774](https://linux-hardware.org/?probe=719a212774) | May 14, 2023 |
| ASUSTek       | X510UQR                     | [2062004d5f](https://linux-hardware.org/?probe=2062004d5f) | May 14, 2023 |
| HP            | Compaq Presario CQ40        | [22d379cd2f](https://linux-hardware.org/?probe=22d379cd2f) | May 13, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | [0f3a2fae1b](https://linux-hardware.org/?probe=0f3a2fae1b) | May 13, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | [4a322b398b](https://linux-hardware.org/?probe=4a322b398b) | May 13, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | [d251ccd249](https://linux-hardware.org/?probe=d251ccd249) | May 13, 2023 |
| ASUSTek       | GL502VMK                    | [0b7232826d](https://linux-hardware.org/?probe=0b7232826d) | May 13, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [1e5caac049](https://linux-hardware.org/?probe=1e5caac049) | May 13, 2023 |
| Dell          | Latitude 7490               | [16cfe08da3](https://linux-hardware.org/?probe=16cfe08da3) | May 13, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | [9dda4f6b83](https://linux-hardware.org/?probe=9dda4f6b83) | May 13, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [804de32208](https://linux-hardware.org/?probe=804de32208) | May 13, 2023 |
| GPU Compan... | GWTN156-11                  | [afb2844cb4](https://linux-hardware.org/?probe=afb2844cb4) | May 13, 2023 |
| ASUSTek       | K53SV                       | [60d7b5acf8](https://linux-hardware.org/?probe=60d7b5acf8) | May 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [a7e9891909](https://linux-hardware.org/?probe=a7e9891909) | May 12, 2023 |
| HP            | ENVY 15                     | [e188fe21b7](https://linux-hardware.org/?probe=e188fe21b7) | May 12, 2023 |
| Lenovo        | YangTian V340-15-IML 81V... | [cedb6136dc](https://linux-hardware.org/?probe=cedb6136dc) | May 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [5a39aa9b41](https://linux-hardware.org/?probe=5a39aa9b41) | May 12, 2023 |
| Dell          | Latitude E7450              | [cb96fcfaff](https://linux-hardware.org/?probe=cb96fcfaff) | May 12, 2023 |
| Dell          | XPS 13 9350                 | [e3c61280ed](https://linux-hardware.org/?probe=e3c61280ed) | May 12, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [1713b94d26](https://linux-hardware.org/?probe=1713b94d26) | May 12, 2023 |
| Positivo      | J14GL11                     | [bfdf0df9b8](https://linux-hardware.org/?probe=bfdf0df9b8) | May 12, 2023 |
| HP            | ENVY Laptop 14-eb0xxx       | [64353c7d87](https://linux-hardware.org/?probe=64353c7d87) | May 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [c590339049](https://linux-hardware.org/?probe=c590339049) | May 12, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [b01a016489](https://linux-hardware.org/?probe=b01a016489) | May 12, 2023 |
| Toshiba       | Satellite L40               | [9945f20a3a](https://linux-hardware.org/?probe=9945f20a3a) | May 11, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [637d09143c](https://linux-hardware.org/?probe=637d09143c) | May 11, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [a1cb5cae49](https://linux-hardware.org/?probe=a1cb5cae49) | May 11, 2023 |
| HP            | Laptop 15s-eq2xxx           | [32b3c782ff](https://linux-hardware.org/?probe=32b3c782ff) | May 11, 2023 |
| Acer          | Aspire A515-57G             | [a00d7ec568](https://linux-hardware.org/?probe=a00d7ec568) | May 11, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [9ff409cce8](https://linux-hardware.org/?probe=9ff409cce8) | May 11, 2023 |
| Positivo      | J14GL11                     | [9594837399](https://linux-hardware.org/?probe=9594837399) | May 11, 2023 |
| Unknown       | M-140BI3                    | [eb6507c151](https://linux-hardware.org/?probe=eb6507c151) | May 11, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | [d30d7d859b](https://linux-hardware.org/?probe=d30d7d859b) | May 11, 2023 |
| HP            | Victus by Gaming Laptop ... | [6b9e3d06b1](https://linux-hardware.org/?probe=6b9e3d06b1) | May 11, 2023 |
| HP            | Laptop 14-dq1xxx            | [76f23f434d](https://linux-hardware.org/?probe=76f23f434d) | May 10, 2023 |
| Dell          | Latitude 5510               | [2c279a470e](https://linux-hardware.org/?probe=2c279a470e) | May 10, 2023 |
| Lenovo        | ThinkPad T550 20CJS0AP00    | [f628b12917](https://linux-hardware.org/?probe=f628b12917) | May 10, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | [c18cfbaca2](https://linux-hardware.org/?probe=c18cfbaca2) | May 10, 2023 |
| Dell          | Precision M3800             | [f5f8f44c9e](https://linux-hardware.org/?probe=f5f8f44c9e) | May 10, 2023 |
| HP            | 250 G6 Notebook PC          | [a7cc3561af](https://linux-hardware.org/?probe=a7cc3561af) | May 10, 2023 |
| Lenovo        | ThinkPad X220 42911H8       | [d6933984d7](https://linux-hardware.org/?probe=d6933984d7) | May 10, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [b791be35c2](https://linux-hardware.org/?probe=b791be35c2) | May 10, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [7058baf75d](https://linux-hardware.org/?probe=7058baf75d) | May 10, 2023 |
| Lenovo        | ThinkPad X220 42911H8       | [6beb57f72d](https://linux-hardware.org/?probe=6beb57f72d) | May 10, 2023 |
| Lenovo        | ThinkPad T480 20L50018US    | [b98dfd1940](https://linux-hardware.org/?probe=b98dfd1940) | May 10, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [80a4bfeb08](https://linux-hardware.org/?probe=80a4bfeb08) | May 10, 2023 |
| Lenovo        | ThinkPad T450 20BUS3E800    | [c419e60853](https://linux-hardware.org/?probe=c419e60853) | May 09, 2023 |
| Acer          | Swift SF114-34              | [deab607d5b](https://linux-hardware.org/?probe=deab607d5b) | May 09, 2023 |
| Apple         | MacBookPro11,3              | [9bd04974e8](https://linux-hardware.org/?probe=9bd04974e8) | May 09, 2023 |
| Dell          | Inspiron 5555               | [378acd7874](https://linux-hardware.org/?probe=378acd7874) | May 09, 2023 |
| Dell          | Inspiron 5555               | [534af3636c](https://linux-hardware.org/?probe=534af3636c) | May 09, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [96d3be3118](https://linux-hardware.org/?probe=96d3be3118) | May 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [dfe5f362e2](https://linux-hardware.org/?probe=dfe5f362e2) | May 09, 2023 |
| Toshiba       | Satellite C55-C             | [1f5654331d](https://linux-hardware.org/?probe=1f5654331d) | May 09, 2023 |
| HUAWEI        | BOM-WXX9                    | [8f910a1997](https://linux-hardware.org/?probe=8f910a1997) | May 09, 2023 |
| HP            | 630                         | [69a6753dab](https://linux-hardware.org/?probe=69a6753dab) | May 09, 2023 |
| HP            | 630                         | [d729f66fa2](https://linux-hardware.org/?probe=d729f66fa2) | May 09, 2023 |
| Dell          | Inspiron N5010              | [5dd91a589b](https://linux-hardware.org/?probe=5dd91a589b) | May 09, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | [bae6aba4fb](https://linux-hardware.org/?probe=bae6aba4fb) | May 09, 2023 |
| Lenovo        | IdeaPad S540-14API 81NH     | [ce04ace3b3](https://linux-hardware.org/?probe=ce04ace3b3) | May 09, 2023 |
| SK hynix      | HyBook Plus                 | [817a46f154](https://linux-hardware.org/?probe=817a46f154) | May 09, 2023 |
| Dell          | Inspiron 3442               | [e858474ff0](https://linux-hardware.org/?probe=e858474ff0) | May 09, 2023 |
| Dell          | Inspiron N5110              | [2d5e375a3d](https://linux-hardware.org/?probe=2d5e375a3d) | May 09, 2023 |
| Dell          | XPS 15 9500                 | [0a72d00670](https://linux-hardware.org/?probe=0a72d00670) | May 09, 2023 |
| HP            | EliteBook 840 14 inch G9... | [a3e5adab46](https://linux-hardware.org/?probe=a3e5adab46) | May 08, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [205b8a8ca7](https://linux-hardware.org/?probe=205b8a8ca7) | May 08, 2023 |
| HP            | EliteBook 8740w             | [29d129229b](https://linux-hardware.org/?probe=29d129229b) | May 08, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [8bbe8f0a3f](https://linux-hardware.org/?probe=8bbe8f0a3f) | May 08, 2023 |
| Avell High... | A65 MOB                     | [d6c6781535](https://linux-hardware.org/?probe=d6c6781535) | May 08, 2023 |
| Dell          | Latitude E7450              | [0eff8f87c6](https://linux-hardware.org/?probe=0eff8f87c6) | May 08, 2023 |
| Notebook      | P750ZM                      | [2cbd56abdc](https://linux-hardware.org/?probe=2cbd56abdc) | May 08, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [75fe05267b](https://linux-hardware.org/?probe=75fe05267b) | May 08, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [d782846579](https://linux-hardware.org/?probe=d782846579) | May 08, 2023 |
| HP            | Laptop 15-ef2xxx            | [96c2411d79](https://linux-hardware.org/?probe=96c2411d79) | May 08, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [00df9b6bda](https://linux-hardware.org/?probe=00df9b6bda) | May 08, 2023 |
| ASUSTek       | G75VW                       | [273bbe68d5](https://linux-hardware.org/?probe=273bbe68d5) | May 07, 2023 |
| HP            | Pavilion Laptop 13-an0xx... | [ce611516ec](https://linux-hardware.org/?probe=ce611516ec) | May 07, 2023 |
| Dell          | Precision 5510              | [9a4ba61d41](https://linux-hardware.org/?probe=9a4ba61d41) | May 07, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [69dfa20c09](https://linux-hardware.org/?probe=69dfa20c09) | May 07, 2023 |
| HP            | Pavilion g6                 | [d6e340501e](https://linux-hardware.org/?probe=d6e340501e) | May 07, 2023 |
| Lenovo        | IdeaPad 5 Pro 14IAP7 82S... | [02fb267cbc](https://linux-hardware.org/?probe=02fb267cbc) | May 07, 2023 |
| PC Special... | NP5x_NP6x_NP7xPNP           | [72d9dac16b](https://linux-hardware.org/?probe=72d9dac16b) | May 07, 2023 |
| Lenovo        | B590 20208                  | [e505ff2542](https://linux-hardware.org/?probe=e505ff2542) | May 07, 2023 |
| Dell          | G5 5505                     | [94e01ce854](https://linux-hardware.org/?probe=94e01ce854) | May 07, 2023 |
| Dell          | G5 5505                     | [b484646926](https://linux-hardware.org/?probe=b484646926) | May 07, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [741b9f90e1](https://linux-hardware.org/?probe=741b9f90e1) | May 07, 2023 |
| Dell          | Inspiron N5010              | [2a418b4e97](https://linux-hardware.org/?probe=2a418b4e97) | May 07, 2023 |
| HT            | C20C WSTKA001               | [a7ffbb2fe3](https://linux-hardware.org/?probe=a7ffbb2fe3) | May 07, 2023 |
| HUAWEI        | CREM-WXX9                   | [93aaae065b](https://linux-hardware.org/?probe=93aaae065b) | May 07, 2023 |
| Alienware     | 18                          | [4c6abf91cd](https://linux-hardware.org/?probe=4c6abf91cd) | May 07, 2023 |
| Lenovo        | ThinkPad T470 20HD0001MX    | [66b49186cb](https://linux-hardware.org/?probe=66b49186cb) | May 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [85648a82df](https://linux-hardware.org/?probe=85648a82df) | May 06, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [2a8bbbef3d](https://linux-hardware.org/?probe=2a8bbbef3d) | May 06, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [696525cf17](https://linux-hardware.org/?probe=696525cf17) | May 06, 2023 |
| Monster       | ABRA A5 V16.4               | [a5507638d0](https://linux-hardware.org/?probe=a5507638d0) | May 06, 2023 |
| Lenovo        | V14-IIL 82C4                | [3ff6a3dac0](https://linux-hardware.org/?probe=3ff6a3dac0) | May 06, 2023 |
| HP            | ProBook 445 G7              | [c78f20f332](https://linux-hardware.org/?probe=c78f20f332) | May 06, 2023 |
| HP            | Pavilion Laptop 15t-cs20... | [177e6fefb1](https://linux-hardware.org/?probe=177e6fefb1) | May 06, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [b577b4aa25](https://linux-hardware.org/?probe=b577b4aa25) | May 06, 2023 |
| Dell          | Inspiron 5490               | [6e2a4689b5](https://linux-hardware.org/?probe=6e2a4689b5) | May 06, 2023 |
| Dell          | XPS 15 9560                 | [644110c9b9](https://linux-hardware.org/?probe=644110c9b9) | May 06, 2023 |
| HP            | ProBook 6570b               | [d240b443c4](https://linux-hardware.org/?probe=d240b443c4) | May 06, 2023 |
| ASUSTek       | Strix GL504GS_GL504GS       | [cdb842cc09](https://linux-hardware.org/?probe=cdb842cc09) | May 06, 2023 |
| Acer          | NC-V3-772G-747A8G1TMAKK     | [58f420d816](https://linux-hardware.org/?probe=58f420d816) | May 06, 2023 |
| HP            | Laptop 15s-eq2xxx           | [fe4b074a5c](https://linux-hardware.org/?probe=fe4b074a5c) | May 06, 2023 |
| HP            | Pavilion g6                 | [6c8f0f4521](https://linux-hardware.org/?probe=6c8f0f4521) | May 06, 2023 |
| Lenovo        | ThinkPad T460p 20FXS0BB0... | [881068ac47](https://linux-hardware.org/?probe=881068ac47) | May 06, 2023 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | [620d5955bb](https://linux-hardware.org/?probe=620d5955bb) | May 06, 2023 |
| Timi          | Redmi Book Pro 14 2022      | [384cc356fc](https://linux-hardware.org/?probe=384cc356fc) | May 06, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [c3ef7b4de9](https://linux-hardware.org/?probe=c3ef7b4de9) | May 06, 2023 |
| Avell High... | A70 HYB                     | [0d871806d1](https://linux-hardware.org/?probe=0d871806d1) | May 05, 2023 |
| Avell High... | A70 HYB                     | [9519eef96f](https://linux-hardware.org/?probe=9519eef96f) | May 05, 2023 |
| HP            | 630                         | [20d6860e43](https://linux-hardware.org/?probe=20d6860e43) | May 05, 2023 |
| HP            | 630                         | [57d5ffbec9](https://linux-hardware.org/?probe=57d5ffbec9) | May 05, 2023 |
| Apple         | MacBook10,1                 | [b951048d8f](https://linux-hardware.org/?probe=b951048d8f) | May 05, 2023 |
| Apple         | MacBook10,1                 | [6796aa4cf0](https://linux-hardware.org/?probe=6796aa4cf0) | May 05, 2023 |
| Unknown       | Cherry Trail CR             | [9569a530e8](https://linux-hardware.org/?probe=9569a530e8) | May 05, 2023 |
| Lenovo        | ThinkPad T450 20BUS46900    | [523dce6a6d](https://linux-hardware.org/?probe=523dce6a6d) | May 05, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [65ddedbd24](https://linux-hardware.org/?probe=65ddedbd24) | May 05, 2023 |
| Acer          | TravelMate P214-53          | [8e78c8d139](https://linux-hardware.org/?probe=8e78c8d139) | May 05, 2023 |
| Dell          | Inspiron 7520               | [2ae295d2a0](https://linux-hardware.org/?probe=2ae295d2a0) | May 05, 2023 |
| Dell          | Inspiron 5490               | [a6c9c8b3b5](https://linux-hardware.org/?probe=a6c9c8b3b5) | May 05, 2023 |
| Lenovo        | ThinkPad Edge E530 62723... | [61e998f782](https://linux-hardware.org/?probe=61e998f782) | May 05, 2023 |
| HP            | 255 G8 Notebook PC          | [49152448eb](https://linux-hardware.org/?probe=49152448eb) | May 05, 2023 |
| Acer          | Nitro AN515-55              | [6264cfc1e6](https://linux-hardware.org/?probe=6264cfc1e6) | May 04, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [3b1960bc9d](https://linux-hardware.org/?probe=3b1960bc9d) | May 04, 2023 |
| Dell          | XPS 13 9310                 | [0cd2974406](https://linux-hardware.org/?probe=0cd2974406) | May 04, 2023 |
| Apple         | MacBookAir7,2               | [d681957d5b](https://linux-hardware.org/?probe=d681957d5b) | May 04, 2023 |
| HUAWEI        | BDZ-WXX9                    | [6f864fb399](https://linux-hardware.org/?probe=6f864fb399) | May 04, 2023 |
| Gigabyte      | G5 KD                       | [15f1eb707f](https://linux-hardware.org/?probe=15f1eb707f) | May 04, 2023 |
| MSI           | Stealth 15M B12UE           | [9e3dbb15ed](https://linux-hardware.org/?probe=9e3dbb15ed) | May 04, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [c83ed0c49b](https://linux-hardware.org/?probe=c83ed0c49b) | May 04, 2023 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | [b8a363f717](https://linux-hardware.org/?probe=b8a363f717) | May 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b8933c29ce](https://linux-hardware.org/?probe=b8933c29ce) | May 04, 2023 |
| HUAWEI        | RLEF-XX                     | [f4964352ac](https://linux-hardware.org/?probe=f4964352ac) | May 04, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [fbc24a91e6](https://linux-hardware.org/?probe=fbc24a91e6) | May 04, 2023 |
| Dell          | Precision 5540              | [3139d97ce0](https://linux-hardware.org/?probe=3139d97ce0) | May 04, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [6fc095ce39](https://linux-hardware.org/?probe=6fc095ce39) | May 04, 2023 |
| Google        | Samus                       | [a7dfa29233](https://linux-hardware.org/?probe=a7dfa29233) | May 04, 2023 |
| Lenovo        | ThinkPad T540p 20BFS0MQ0... | [fc03f40473](https://linux-hardware.org/?probe=fc03f40473) | May 04, 2023 |
| Lenovo        | ThinkPad T540p 20BFS0MQ0... | [b5a88798e7](https://linux-hardware.org/?probe=b5a88798e7) | May 04, 2023 |
| Lenovo        | IdeaPad Yoga 11S 20246      | [fde0845fa4](https://linux-hardware.org/?probe=fde0845fa4) | May 04, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [a00f293aa7](https://linux-hardware.org/?probe=a00f293aa7) | May 04, 2023 |
| Apple         | MacBookPro8,1               | [e3dd9f70f6](https://linux-hardware.org/?probe=e3dd9f70f6) | May 04, 2023 |
| Lenovo        | IdeaPad Yoga 11S 20246      | [1a15177f0a](https://linux-hardware.org/?probe=1a15177f0a) | May 04, 2023 |
| Dell          | Latitude 3470               | [532cd0124e](https://linux-hardware.org/?probe=532cd0124e) | May 04, 2023 |
| HP            | Laptop 15-ef2xxx            | [d29dae3c91](https://linux-hardware.org/?probe=d29dae3c91) | May 04, 2023 |
| Lenovo        | ThinkPad X230 23252CG       | [00ff147a9a](https://linux-hardware.org/?probe=00ff147a9a) | May 03, 2023 |
| HP            | Unknown                     | [b99510884b](https://linux-hardware.org/?probe=b99510884b) | May 03, 2023 |
| Dell          | Latitude 5490               | [20c5ad2ee2](https://linux-hardware.org/?probe=20c5ad2ee2) | May 03, 2023 |
| Toshiba       | PORTEGE Z830                | [a8cc4a63c2](https://linux-hardware.org/?probe=a8cc4a63c2) | May 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [4280750d03](https://linux-hardware.org/?probe=4280750d03) | May 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [1515ab9d19](https://linux-hardware.org/?probe=1515ab9d19) | May 03, 2023 |
| Dell          | Latitude 7420               | [7986f6779d](https://linux-hardware.org/?probe=7986f6779d) | May 03, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [cefcc36d0e](https://linux-hardware.org/?probe=cefcc36d0e) | May 03, 2023 |
| Lenovo        | IdeaPad S540-14API 81NH     | [29f68ce8d7](https://linux-hardware.org/?probe=29f68ce8d7) | May 03, 2023 |
| Dell          | Inspiron 5391               | [5edc4b5738](https://linux-hardware.org/?probe=5edc4b5738) | May 03, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [3b04b16c3e](https://linux-hardware.org/?probe=3b04b16c3e) | May 03, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [1234a4cf5a](https://linux-hardware.org/?probe=1234a4cf5a) | May 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [61faf68b9f](https://linux-hardware.org/?probe=61faf68b9f) | May 03, 2023 |
| Adreamer      | PN1308P                     | [8ae75bc5a0](https://linux-hardware.org/?probe=8ae75bc5a0) | May 02, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [f2c18c96df](https://linux-hardware.org/?probe=f2c18c96df) | May 02, 2023 |
| HP            | Laptop 15s-eq3xxx           | [5375a4f57c](https://linux-hardware.org/?probe=5375a4f57c) | May 02, 2023 |
| Samsung       | 730QCJ/730QCR               | [4541d2e721](https://linux-hardware.org/?probe=4541d2e721) | May 02, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [c4841e9b59](https://linux-hardware.org/?probe=c4841e9b59) | May 02, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | [143b75f514](https://linux-hardware.org/?probe=143b75f514) | May 02, 2023 |
| HP            | Dragonfly Pro               | [365260c678](https://linux-hardware.org/?probe=365260c678) | May 01, 2023 |
| HP            | Dragonfly Pro               | [89a652fc25](https://linux-hardware.org/?probe=89a652fc25) | May 01, 2023 |
| HP            | 255 G4                      | [b06ddec94b](https://linux-hardware.org/?probe=b06ddec94b) | May 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [ed2a323b49](https://linux-hardware.org/?probe=ed2a323b49) | May 01, 2023 |
| ASUSTek       | X401A1                      | [2a7d35cc4e](https://linux-hardware.org/?probe=2a7d35cc4e) | May 01, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [c604e4ce30](https://linux-hardware.org/?probe=c604e4ce30) | May 01, 2023 |
| HUAWEI        | HVY-WXX9                    | [c5c9bbda3d](https://linux-hardware.org/?probe=c5c9bbda3d) | May 01, 2023 |
| Dell          | Inspiron 1564               | [e94ef67ab2](https://linux-hardware.org/?probe=e94ef67ab2) | May 01, 2023 |
| Notebook      | NS5x_NS7xPU                 | [ee97e0f5f0](https://linux-hardware.org/?probe=ee97e0f5f0) | May 01, 2023 |
| HP            | Compaq 6910p                | [a697e756f5](https://linux-hardware.org/?probe=a697e756f5) | May 01, 2023 |
| Dell          | Inspiron 14 5420            | [cc65b3de6f](https://linux-hardware.org/?probe=cc65b3de6f) | May 01, 2023 |
| Valve         | Jupiter                     | [07ef050535](https://linux-hardware.org/?probe=07ef050535) | May 01, 2023 |
| HP            | Laptop 15z-fc000            | [7b57cc42a0](https://linux-hardware.org/?probe=7b57cc42a0) | May 01, 2023 |
| HP            | ElitePad 1000 G2            | [8ae27e00f6](https://linux-hardware.org/?probe=8ae27e00f6) | May 01, 2023 |
| HUAWEI        | CREM-WXX9                   | [ba99960d5f](https://linux-hardware.org/?probe=ba99960d5f) | May 01, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | [a7d6d782b2](https://linux-hardware.org/?probe=a7d6d782b2) | May 01, 2023 |
| Intel         | CHERRYVIEW D1 PLATFORM      | [6c58138c35](https://linux-hardware.org/?probe=6c58138c35) | May 01, 2023 |
| Lenovo        | IdeaPad S340-15IWLTouch ... | [6857a16a6c](https://linux-hardware.org/?probe=6857a16a6c) | Apr 30, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [0784fc9b1c](https://linux-hardware.org/?probe=0784fc9b1c) | Apr 30, 2023 |
| HP            | Notebook                    | [fd6aa4aeb6](https://linux-hardware.org/?probe=fd6aa4aeb6) | Apr 30, 2023 |
| VIOS          | LTH17                       | [4d1a86ee61](https://linux-hardware.org/?probe=4d1a86ee61) | Apr 30, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [9c07454907](https://linux-hardware.org/?probe=9c07454907) | Apr 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [43a167afad](https://linux-hardware.org/?probe=43a167afad) | Apr 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [0ae3fb5506](https://linux-hardware.org/?probe=0ae3fb5506) | Apr 30, 2023 |
| ASUSTek       | X555QG                      | [5263b174b2](https://linux-hardware.org/?probe=5263b174b2) | Apr 30, 2023 |
| Lenovo        | ThinkPad T490s 20NX002SG... | [874f19f26e](https://linux-hardware.org/?probe=874f19f26e) | Apr 30, 2023 |
| Dell          | Latitude 5521               | [1629b4efc4](https://linux-hardware.org/?probe=1629b4efc4) | Apr 30, 2023 |
| HP            | Laptop 17-by3xxx            | [552dac328b](https://linux-hardware.org/?probe=552dac328b) | Apr 30, 2023 |
| HP            | EliteBook 840 G3            | [c262e81ab9](https://linux-hardware.org/?probe=c262e81ab9) | Apr 30, 2023 |
| Acer          | Nitro AN515-45              | [9b28e69254](https://linux-hardware.org/?probe=9b28e69254) | Apr 30, 2023 |
| Framework     | Laptop                      | [84b3b9547b](https://linux-hardware.org/?probe=84b3b9547b) | Apr 29, 2023 |
| Dell          | XPS 13 7390                 | [b976cc9656](https://linux-hardware.org/?probe=b976cc9656) | Apr 29, 2023 |
| Dell          | XPS 13 9380                 | [c6591b0852](https://linux-hardware.org/?probe=c6591b0852) | Apr 29, 2023 |
| Intel         | CHERRYVIEW D1 PLATFORM      | [edf1d60e46](https://linux-hardware.org/?probe=edf1d60e46) | Apr 29, 2023 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [6f6a016997](https://linux-hardware.org/?probe=6f6a016997) | Apr 29, 2023 |
| Lenovo        | ThinkPad T550 20CKA00ECD    | [2545d9dd31](https://linux-hardware.org/?probe=2545d9dd31) | Apr 29, 2023 |
| MSI           | Modern 14 B11MOU            | [6b3fcf3fcc](https://linux-hardware.org/?probe=6b3fcf3fcc) | Apr 29, 2023 |
| HUAWEI        | CREM-WXX9                   | [c17b468722](https://linux-hardware.org/?probe=c17b468722) | Apr 29, 2023 |
| Chuwi         | HeroBook Air                | [123f6df9f8](https://linux-hardware.org/?probe=123f6df9f8) | Apr 29, 2023 |
| Insyde        | M890BAP                     | [151efb0278](https://linux-hardware.org/?probe=151efb0278) | Apr 29, 2023 |
| Insyde        | CherryTrail                 | [a9f658c8af](https://linux-hardware.org/?probe=a9f658c8af) | Apr 29, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [cd266d7680](https://linux-hardware.org/?probe=cd266d7680) | Apr 29, 2023 |
| Acer          | Nitro AN515-58              | [2c335c5bfb](https://linux-hardware.org/?probe=2c335c5bfb) | Apr 29, 2023 |
| Google        | Banon                       | [c21a57806c](https://linux-hardware.org/?probe=c21a57806c) | Apr 29, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [e70d66b3ba](https://linux-hardware.org/?probe=e70d66b3ba) | Apr 29, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [2aa69de3ca](https://linux-hardware.org/?probe=2aa69de3ca) | Apr 29, 2023 |
| ASUSTek       | X555QG                      | [b33f41d3c3](https://linux-hardware.org/?probe=b33f41d3c3) | Apr 28, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [4de963cbc6](https://linux-hardware.org/?probe=4de963cbc6) | Apr 28, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [d8af950fd8](https://linux-hardware.org/?probe=d8af950fd8) | Apr 28, 2023 |
| Acer          | Aspire E5-571               | [1d36dafa86](https://linux-hardware.org/?probe=1d36dafa86) | Apr 28, 2023 |
| Dell          | Precision 3551              | [99ff11c325](https://linux-hardware.org/?probe=99ff11c325) | Apr 28, 2023 |
| Lenovo        | ThinkPad T470p 20J60018M... | [a8deb2307c](https://linux-hardware.org/?probe=a8deb2307c) | Apr 28, 2023 |
| Dell          | Precision 3551              | [93a38e7384](https://linux-hardware.org/?probe=93a38e7384) | Apr 28, 2023 |
| Lenovo        | ThinkPad X260 20F5S56G00    | [8da21e9a17](https://linux-hardware.org/?probe=8da21e9a17) | Apr 28, 2023 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [5cb9fe1ae9](https://linux-hardware.org/?probe=5cb9fe1ae9) | Apr 28, 2023 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [3669ef1de9](https://linux-hardware.org/?probe=3669ef1de9) | Apr 28, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [e0ef7894af](https://linux-hardware.org/?probe=e0ef7894af) | Apr 28, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [b5a953a984](https://linux-hardware.org/?probe=b5a953a984) | Apr 28, 2023 |
| HP            | ProBook 455 15.6 inch G9... | [1cfc210ce1](https://linux-hardware.org/?probe=1cfc210ce1) | Apr 28, 2023 |
| Acer          | Nitro AN515-54              | [000022b2dd](https://linux-hardware.org/?probe=000022b2dd) | Apr 28, 2023 |
| Sony          | VPCEG23EL                   | [c28e3338ce](https://linux-hardware.org/?probe=c28e3338ce) | Apr 28, 2023 |
| Lenovo        | Legion 7-16-ITHg6 82K6      | [2baf2cbc85](https://linux-hardware.org/?probe=2baf2cbc85) | Apr 27, 2023 |
| Lenovo        | ThinkPad X230 2325O32       | [b38ef1a717](https://linux-hardware.org/?probe=b38ef1a717) | Apr 27, 2023 |
| ASUSTek       | Zephyrus M GU502GW_GU502... | [94d9250bc1](https://linux-hardware.org/?probe=94d9250bc1) | Apr 27, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [854cf327d8](https://linux-hardware.org/?probe=854cf327d8) | Apr 27, 2023 |
| HUAWEI        | HVY-WXX9                    | [dd5391c20d](https://linux-hardware.org/?probe=dd5391c20d) | Apr 27, 2023 |
| HP            | Laptop 17-ak0xx             | [6eed1fda15](https://linux-hardware.org/?probe=6eed1fda15) | Apr 27, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | [4cd1484039](https://linux-hardware.org/?probe=4cd1484039) | Apr 27, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | [0796e35c73](https://linux-hardware.org/?probe=0796e35c73) | Apr 27, 2023 |
| Dell          | XPS 15 9500                 | [a7cc631b80](https://linux-hardware.org/?probe=a7cc631b80) | Apr 27, 2023 |
| Timi          | Redmi Book Pro 14 2022      | [dcc8c22535](https://linux-hardware.org/?probe=dcc8c22535) | Apr 27, 2023 |
| Lenovo        | ThinkPad T420 4177QKU       | [cbabefb1fa](https://linux-hardware.org/?probe=cbabefb1fa) | Apr 27, 2023 |
| Dell          | Vostro 15 3515              | [f58ab8b9c4](https://linux-hardware.org/?probe=f58ab8b9c4) | Apr 27, 2023 |
| Lenovo        | ThinkPad X270 20HN001HUS    | [3f6586f0d1](https://linux-hardware.org/?probe=3f6586f0d1) | Apr 27, 2023 |
| Lenovo        | ThinkPad T480s 20L8S45W0... | [0e8490c41f](https://linux-hardware.org/?probe=0e8490c41f) | Apr 27, 2023 |
| ASUSTek       | Zephyrus M GU502GW_GU502... | [67c865f449](https://linux-hardware.org/?probe=67c865f449) | Apr 27, 2023 |
| Acer          | Aspire A315-54              | [8137aa9008](https://linux-hardware.org/?probe=8137aa9008) | Apr 27, 2023 |
| HP            | EliteBook 630 13 inch G9... | [96bd4f8398](https://linux-hardware.org/?probe=96bd4f8398) | Apr 27, 2023 |
| Apple         | MacBookAir6,1               | [c0f967c0bc](https://linux-hardware.org/?probe=c0f967c0bc) | Apr 27, 2023 |
| Acer          | Aspire E5-575G              | [3497feda9f](https://linux-hardware.org/?probe=3497feda9f) | Apr 27, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [c443269a81](https://linux-hardware.org/?probe=c443269a81) | Apr 26, 2023 |
| ASUSTek       | ROG Strix G512LW_G512LW     | [a950f656f7](https://linux-hardware.org/?probe=a950f656f7) | Apr 26, 2023 |
| Timi          | TM1703                      | [7e6b948ea9](https://linux-hardware.org/?probe=7e6b948ea9) | Apr 26, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [96006a1098](https://linux-hardware.org/?probe=96006a1098) | Apr 26, 2023 |
| HUAWEI        | KLVL-WXXW                   | [de95ac0857](https://linux-hardware.org/?probe=de95ac0857) | Apr 26, 2023 |
| HUAWEI        | KLVL-WXXW                   | [07906a30e3](https://linux-hardware.org/?probe=07906a30e3) | Apr 26, 2023 |
| Acer          | Aspire E5-575G              | [3a7b41fb49](https://linux-hardware.org/?probe=3a7b41fb49) | Apr 26, 2023 |
| Dell          | Latitude 5520               | [7ee153b691](https://linux-hardware.org/?probe=7ee153b691) | Apr 26, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [3a6e27c6ce](https://linux-hardware.org/?probe=3a6e27c6ce) | Apr 26, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [86ba8ccc07](https://linux-hardware.org/?probe=86ba8ccc07) | Apr 26, 2023 |
| Lenovo        | ThinkPad T480s 20L8002WM... | [82bd4b0d20](https://linux-hardware.org/?probe=82bd4b0d20) | Apr 26, 2023 |
| Dell          | Latitude 5520               | [3071d4a9d8](https://linux-hardware.org/?probe=3071d4a9d8) | Apr 26, 2023 |
| Dell          | Latitude 5520               | [23fe32affd](https://linux-hardware.org/?probe=23fe32affd) | Apr 26, 2023 |
| Acer          | Swift SF114-32              | [13d7dc019c](https://linux-hardware.org/?probe=13d7dc019c) | Apr 26, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [a3df65a55c](https://linux-hardware.org/?probe=a3df65a55c) | Apr 26, 2023 |
| MSI           | Creator 15 A10SGS           | [1b364e385a](https://linux-hardware.org/?probe=1b364e385a) | Apr 26, 2023 |
| Razer         | Blade                       | [b170226896](https://linux-hardware.org/?probe=b170226896) | Apr 25, 2023 |
| Dell          | Inspiron 5748               | [dd4d50839d](https://linux-hardware.org/?probe=dd4d50839d) | Apr 25, 2023 |
| HP            | Laptop 15-fc0xxx            | [cc994920bf](https://linux-hardware.org/?probe=cc994920bf) | Apr 25, 2023 |
| Dell          | Precision 7550              | [987df8038c](https://linux-hardware.org/?probe=987df8038c) | Apr 25, 2023 |
| Dell          | G15 5515                    | [a0dd3f2003](https://linux-hardware.org/?probe=a0dd3f2003) | Apr 25, 2023 |
| Dell          | Vostro 3550                 | [653c3c4650](https://linux-hardware.org/?probe=653c3c4650) | Apr 25, 2023 |
| Lenovo        | ThinkPad E14 20RAS1DB00     | [8e09a153f5](https://linux-hardware.org/?probe=8e09a153f5) | Apr 25, 2023 |
| HP            | Dragonfly Pro               | [9bc83e741f](https://linux-hardware.org/?probe=9bc83e741f) | Apr 25, 2023 |
| HP            | Dragonfly Pro               | [b47e30ac80](https://linux-hardware.org/?probe=b47e30ac80) | Apr 25, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C8S... | [765b52074c](https://linux-hardware.org/?probe=765b52074c) | Apr 25, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C8S... | [9cd6c064cc](https://linux-hardware.org/?probe=9cd6c064cc) | Apr 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [5236dde38f](https://linux-hardware.org/?probe=5236dde38f) | Apr 25, 2023 |
| Apple         | MacBookPro11,1              | [7309ce024f](https://linux-hardware.org/?probe=7309ce024f) | Apr 25, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [c0d8e6e6b5](https://linux-hardware.org/?probe=c0d8e6e6b5) | Apr 25, 2023 |
| LDLC          | SPC-I                       | [899fb46a02](https://linux-hardware.org/?probe=899fb46a02) | Apr 25, 2023 |
| Chuwi         | GemiBook Pro                | [1287b17594](https://linux-hardware.org/?probe=1287b17594) | Apr 25, 2023 |
| Dell          | G3 3500                     | [46996524d0](https://linux-hardware.org/?probe=46996524d0) | Apr 25, 2023 |
| Dell          | XPS 13 9380                 | [290a99fee9](https://linux-hardware.org/?probe=290a99fee9) | Apr 25, 2023 |
| Lenovo        | Legion 5 17IMH05 82B3       | [2e542c241d](https://linux-hardware.org/?probe=2e542c241d) | Apr 25, 2023 |
| Sony          | SVS13A25PXB                 | [a31acd0a66](https://linux-hardware.org/?probe=a31acd0a66) | Apr 25, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [0db2c54b2a](https://linux-hardware.org/?probe=0db2c54b2a) | Apr 24, 2023 |
| Notebook      | P95_96_97Ex,Rx              | [297da8c979](https://linux-hardware.org/?probe=297da8c979) | Apr 24, 2023 |
| Lenovo        | V130-15IKB 81HN             | [1b26b3f89b](https://linux-hardware.org/?probe=1b26b3f89b) | Apr 24, 2023 |
| Sony          | SVS13A25PXB                 | [06138dd58a](https://linux-hardware.org/?probe=06138dd58a) | Apr 24, 2023 |
| Dell          | Latitude 5580               | [a153ad5277](https://linux-hardware.org/?probe=a153ad5277) | Apr 24, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [de3ad583ab](https://linux-hardware.org/?probe=de3ad583ab) | Apr 24, 2023 |
| HP            | Pavilion Laptop 15-cc1xx    | [2f3390afca](https://linux-hardware.org/?probe=2f3390afca) | Apr 24, 2023 |
| HP            | Laptop 15s-eq2xxx           | [699adff825](https://linux-hardware.org/?probe=699adff825) | Apr 24, 2023 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | [e028b13685](https://linux-hardware.org/?probe=e028b13685) | Apr 24, 2023 |
| Dell          | Vostro 5402                 | [b6cb9c9140](https://linux-hardware.org/?probe=b6cb9c9140) | Apr 24, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [d805c85a12](https://linux-hardware.org/?probe=d805c85a12) | Apr 24, 2023 |
| HP            | Laptop 14-cm0xxx            | [4591d1bf9d](https://linux-hardware.org/?probe=4591d1bf9d) | Apr 24, 2023 |
| BTO           | 17X1183                     | [134a6ead50](https://linux-hardware.org/?probe=134a6ead50) | Apr 23, 2023 |
| BTO           | 17X1183                     | [181163b5e8](https://linux-hardware.org/?probe=181163b5e8) | Apr 23, 2023 |
| Dell          | Latitude 9520               | [0ab9a83db6](https://linux-hardware.org/?probe=0ab9a83db6) | Apr 23, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [696ee85cc9](https://linux-hardware.org/?probe=696ee85cc9) | Apr 23, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [43aae4850b](https://linux-hardware.org/?probe=43aae4850b) | Apr 23, 2023 |
| Apple         | MacBookPro11,3              | [db4dd7bc7a](https://linux-hardware.org/?probe=db4dd7bc7a) | Apr 23, 2023 |
| Dynabook      | PORTEGE X30L-K              | [da178b8987](https://linux-hardware.org/?probe=da178b8987) | Apr 23, 2023 |
| HP            | Laptop 15-bs2xx             | [c40dac306c](https://linux-hardware.org/?probe=c40dac306c) | Apr 23, 2023 |
| Notebook      | NLxxPUx                     | [3648be5b0f](https://linux-hardware.org/?probe=3648be5b0f) | Apr 23, 2023 |
| ASUSTek       | X510UAR                     | [3321ccb912](https://linux-hardware.org/?probe=3321ccb912) | Apr 23, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [9a6f040039](https://linux-hardware.org/?probe=9a6f040039) | Apr 23, 2023 |
| Lenovo        | ThinkPad T495 20NJ000XGE    | [155072c012](https://linux-hardware.org/?probe=155072c012) | Apr 23, 2023 |
| Dell          | Latitude E6520              | [a8b5c5c3ad](https://linux-hardware.org/?probe=a8b5c5c3ad) | Apr 23, 2023 |
| Acer          | Aspire A514-55              | [d98f78cc01](https://linux-hardware.org/?probe=d98f78cc01) | Apr 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [9a92345b08](https://linux-hardware.org/?probe=9a92345b08) | Apr 23, 2023 |
| Lenovo        | ThinkPad X220 4291WSH       | [5a626f5754](https://linux-hardware.org/?probe=5a626f5754) | Apr 23, 2023 |
| Dell          | Latitude E6430              | [e844bce31c](https://linux-hardware.org/?probe=e844bce31c) | Apr 23, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [a8644a5b03](https://linux-hardware.org/?probe=a8644a5b03) | Apr 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [0e798db6a8](https://linux-hardware.org/?probe=0e798db6a8) | Apr 23, 2023 |
| ASUSTek       | X550CC                      | [f51db9e4de](https://linux-hardware.org/?probe=f51db9e4de) | Apr 23, 2023 |
| Dell          | Latitude E6420              | [ef822feab1](https://linux-hardware.org/?probe=ef822feab1) | Apr 22, 2023 |
| HUAWEI        | MRGF-XX                     | [25233eb8d1](https://linux-hardware.org/?probe=25233eb8d1) | Apr 22, 2023 |
| MSI           | Prestige 15 A10SC           | [f64336848a](https://linux-hardware.org/?probe=f64336848a) | Apr 22, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [bb1a40d839](https://linux-hardware.org/?probe=bb1a40d839) | Apr 22, 2023 |
| Dell          | Latitude D620               | [7b0c5ec6f2](https://linux-hardware.org/?probe=7b0c5ec6f2) | Apr 22, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [e682d7b9dd](https://linux-hardware.org/?probe=e682d7b9dd) | Apr 22, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [510237facd](https://linux-hardware.org/?probe=510237facd) | Apr 22, 2023 |
| HP            | Notebook                    | [1d975dfc4f](https://linux-hardware.org/?probe=1d975dfc4f) | Apr 22, 2023 |
| HUAWEI        | BOHB-WAX9                   | [5cceab0ac3](https://linux-hardware.org/?probe=5cceab0ac3) | Apr 22, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [c1139db413](https://linux-hardware.org/?probe=c1139db413) | Apr 22, 2023 |
| Dell          | XPS 15 9550                 | [2defeff264](https://linux-hardware.org/?probe=2defeff264) | Apr 22, 2023 |
| Dell          | Precision 5510              | [94b5586a2c](https://linux-hardware.org/?probe=94b5586a2c) | Apr 22, 2023 |
| Acer          | Nitro AN515-58              | [d342e4d24c](https://linux-hardware.org/?probe=d342e4d24c) | Apr 22, 2023 |
| Acer          | TP-SW3-013-181M             | [d231dc8846](https://linux-hardware.org/?probe=d231dc8846) | Apr 22, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [a7359e872e](https://linux-hardware.org/?probe=a7359e872e) | Apr 22, 2023 |
| Acer          | Nitro AN515-54              | [452177f9a5](https://linux-hardware.org/?probe=452177f9a5) | Apr 21, 2023 |
| Dell          | XPS 13 9310                 | [5c9b8fef2e](https://linux-hardware.org/?probe=5c9b8fef2e) | Apr 21, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [dae63185d5](https://linux-hardware.org/?probe=dae63185d5) | Apr 21, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [517662dd54](https://linux-hardware.org/?probe=517662dd54) | Apr 21, 2023 |
| Dynabook      | PORTEGE X30L-K              | [b52552ec7f](https://linux-hardware.org/?probe=b52552ec7f) | Apr 21, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [db069c8b89](https://linux-hardware.org/?probe=db069c8b89) | Apr 21, 2023 |
| HP            | Laptop 15s-eq2xxx           | [94bd5fe556](https://linux-hardware.org/?probe=94bd5fe556) | Apr 21, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [c46312dc86](https://linux-hardware.org/?probe=c46312dc86) | Apr 21, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [3fd583ee9b](https://linux-hardware.org/?probe=3fd583ee9b) | Apr 21, 2023 |
| Digibras      | NH4CU53                     | [d6571e3d78](https://linux-hardware.org/?probe=d6571e3d78) | Apr 21, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [f2f6b7ab4e](https://linux-hardware.org/?probe=f2f6b7ab4e) | Apr 21, 2023 |
| Positivo      | N6440                       | [b0a1fe417d](https://linux-hardware.org/?probe=b0a1fe417d) | Apr 21, 2023 |
| Lenovo        | IdeaPad S540-15IWL          | [8578f44f47](https://linux-hardware.org/?probe=8578f44f47) | Apr 21, 2023 |
| Apple         | MacBookPro11,3              | [09a203e882](https://linux-hardware.org/?probe=09a203e882) | Apr 21, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [8b18bb529f](https://linux-hardware.org/?probe=8b18bb529f) | Apr 21, 2023 |
| Framework     | Laptop                      | [226765247b](https://linux-hardware.org/?probe=226765247b) | Apr 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X540... | [91999697ba](https://linux-hardware.org/?probe=91999697ba) | Apr 20, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [b7f138b04c](https://linux-hardware.org/?probe=b7f138b04c) | Apr 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [901b3d11dc](https://linux-hardware.org/?probe=901b3d11dc) | Apr 20, 2023 |
| Acer          | Swift SF314-511             | [96fd44e94a](https://linux-hardware.org/?probe=96fd44e94a) | Apr 20, 2023 |
| Dell          | G15 5510                    | [724945ee92](https://linux-hardware.org/?probe=724945ee92) | Apr 20, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [3219512811](https://linux-hardware.org/?probe=3219512811) | Apr 20, 2023 |
| Dell          | XPS 13 9310                 | [55685c168f](https://linux-hardware.org/?probe=55685c168f) | Apr 20, 2023 |
| Dell          | Latitude 7490               | [57a719ce62](https://linux-hardware.org/?probe=57a719ce62) | Apr 20, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHS... | [59d7ef5ddd](https://linux-hardware.org/?probe=59d7ef5ddd) | Apr 20, 2023 |
| Toshiba       | Satellite L515              | [5262a186b5](https://linux-hardware.org/?probe=5262a186b5) | Apr 20, 2023 |
| Lenovo        | ThinkPad P52 20MAS5KM00     | [06ab19cc37](https://linux-hardware.org/?probe=06ab19cc37) | Apr 20, 2023 |
| Getac         | B300G5                      | [307cc71aa3](https://linux-hardware.org/?probe=307cc71aa3) | Apr 20, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | [8daf9af9b5](https://linux-hardware.org/?probe=8daf9af9b5) | Apr 20, 2023 |
| Lenovo        | ThinkPad T430 2349S4D       | [4b57440851](https://linux-hardware.org/?probe=4b57440851) | Apr 20, 2023 |
| MECHREVO      | Code10-7CC6U                | [0964cd2b26](https://linux-hardware.org/?probe=0964cd2b26) | Apr 20, 2023 |
| MECHREVO      | Code10-7CC6U                | [5ddc83a95c](https://linux-hardware.org/?probe=5ddc83a95c) | Apr 20, 2023 |
| Samsung       | 550P5C/550P7C               | [3648dd39f8](https://linux-hardware.org/?probe=3648dd39f8) | Apr 20, 2023 |
| Lenovo        | G40-30 80FY                 | [923b3fd46b](https://linux-hardware.org/?probe=923b3fd46b) | Apr 19, 2023 |
| HP            | Laptop 15s-eq2xxx           | [9f5fa03bfd](https://linux-hardware.org/?probe=9f5fa03bfd) | Apr 19, 2023 |
| Lenovo        | G50-30 80G0                 | [42cb984b27](https://linux-hardware.org/?probe=42cb984b27) | Apr 19, 2023 |
| Dell          | Inspiron 7460               | [bbfe51bf3c](https://linux-hardware.org/?probe=bbfe51bf3c) | Apr 19, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [b1c04430cc](https://linux-hardware.org/?probe=b1c04430cc) | Apr 19, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [b2873d15a0](https://linux-hardware.org/?probe=b2873d15a0) | Apr 19, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [258a5bb354](https://linux-hardware.org/?probe=258a5bb354) | Apr 19, 2023 |
| HP            | Pavilion x2 Detachable      | [1c7cd2fe1d](https://linux-hardware.org/?probe=1c7cd2fe1d) | Apr 19, 2023 |
| Dell          | Precision 5540              | [66b58fad6c](https://linux-hardware.org/?probe=66b58fad6c) | Apr 19, 2023 |
| Dell          | Precision 5540              | [e114fb911c](https://linux-hardware.org/?probe=e114fb911c) | Apr 19, 2023 |
| HP            | Pavilion 17                 | [66df49c906](https://linux-hardware.org/?probe=66df49c906) | Apr 19, 2023 |
| Dell          | XPS 13 7390                 | [357c45c81c](https://linux-hardware.org/?probe=357c45c81c) | Apr 19, 2023 |
| Apple         | MacBookAir6,1               | [5a600ce01b](https://linux-hardware.org/?probe=5a600ce01b) | Apr 19, 2023 |
| HUAWEI        | NBD-WXX9                    | [a55a03e648](https://linux-hardware.org/?probe=a55a03e648) | Apr 19, 2023 |
| PC Special... | PCx0Dx                      | [0f82987a84](https://linux-hardware.org/?probe=0f82987a84) | Apr 18, 2023 |
| Toshiba       | Kronos 10CUG                | [228e28e6a8](https://linux-hardware.org/?probe=228e28e6a8) | Apr 18, 2023 |
| Dell          | G5 5590                     | [c7334114be](https://linux-hardware.org/?probe=c7334114be) | Apr 18, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | [3b3f4afdd8](https://linux-hardware.org/?probe=3b3f4afdd8) | Apr 18, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [0ec2388253](https://linux-hardware.org/?probe=0ec2388253) | Apr 18, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [1a5add814c](https://linux-hardware.org/?probe=1a5add814c) | Apr 18, 2023 |
| HUAWEI        | RLEF-XX                     | [b425e2afaf](https://linux-hardware.org/?probe=b425e2afaf) | Apr 18, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [67a6474ece](https://linux-hardware.org/?probe=67a6474ece) | Apr 18, 2023 |
| Fujitsu       | LIFEBOOK U7510              | [21605e555f](https://linux-hardware.org/?probe=21605e555f) | Apr 18, 2023 |
| ASUSTek       | GL502VML                    | [7c65476ce9](https://linux-hardware.org/?probe=7c65476ce9) | Apr 18, 2023 |
| Lenovo        | ThinkPad Edge 031946U       | [f9d813509a](https://linux-hardware.org/?probe=f9d813509a) | Apr 18, 2023 |
| Lenovo        | ThinkPad P52 20MAS11D00     | [c2227e5f29](https://linux-hardware.org/?probe=c2227e5f29) | Apr 18, 2023 |
| Lenovo        | Unknown                     | [99a0c76ea9](https://linux-hardware.org/?probe=99a0c76ea9) | Apr 18, 2023 |
| Lenovo        | ThinkPad P52 20MAS11D00     | [f56edbb1d1](https://linux-hardware.org/?probe=f56edbb1d1) | Apr 18, 2023 |
| HP            | Pavilion x2 Detachable      | [5d56d95ea5](https://linux-hardware.org/?probe=5d56d95ea5) | Apr 18, 2023 |
| Acer          | Nitro AN515-54              | [7b3a68ca48](https://linux-hardware.org/?probe=7b3a68ca48) | Apr 18, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [90c4ba9f6e](https://linux-hardware.org/?probe=90c4ba9f6e) | Apr 17, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [a196246f09](https://linux-hardware.org/?probe=a196246f09) | Apr 17, 2023 |
| Dell          | Inspiron N5110              | [48b2d021fa](https://linux-hardware.org/?probe=48b2d021fa) | Apr 17, 2023 |
| Lenovo        | Unknown                     | [653cf225b8](https://linux-hardware.org/?probe=653cf225b8) | Apr 17, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [f8a45caf43](https://linux-hardware.org/?probe=f8a45caf43) | Apr 17, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | [7ca92cfada](https://linux-hardware.org/?probe=7ca92cfada) | Apr 17, 2023 |
| Dell          | XPS 15 9500                 | [1a55ffc593](https://linux-hardware.org/?probe=1a55ffc593) | Apr 17, 2023 |
| HP            | Pavilion 17                 | [a09113d5ab](https://linux-hardware.org/?probe=a09113d5ab) | Apr 17, 2023 |
| HUAWEI        | HVY-WXX9                    | [3d14cefd78](https://linux-hardware.org/?probe=3d14cefd78) | Apr 17, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [5e265fd8e1](https://linux-hardware.org/?probe=5e265fd8e1) | Apr 16, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [3ea28c33c9](https://linux-hardware.org/?probe=3ea28c33c9) | Apr 16, 2023 |
| HP            | EliteBook 845 14 inch G9... | [fd256ca124](https://linux-hardware.org/?probe=fd256ca124) | Apr 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [391b43ba8c](https://linux-hardware.org/?probe=391b43ba8c) | Apr 16, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [2092251807](https://linux-hardware.org/?probe=2092251807) | Apr 16, 2023 |
| HP            | 15-dc1018ur                 | [7df35a90ad](https://linux-hardware.org/?probe=7df35a90ad) | Apr 16, 2023 |
| Framework     | Laptop                      | [c03bcdf19a](https://linux-hardware.org/?probe=c03bcdf19a) | Apr 16, 2023 |
| Apple         | MacBookAir7,2               | [ed6f18d5ab](https://linux-hardware.org/?probe=ed6f18d5ab) | Apr 16, 2023 |
| Apple         | MacBookAir7,2               | [82509b267d](https://linux-hardware.org/?probe=82509b267d) | Apr 16, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [afc478cf27](https://linux-hardware.org/?probe=afc478cf27) | Apr 16, 2023 |
| Dell          | Inspiron 3501               | [19b858e5f8](https://linux-hardware.org/?probe=19b858e5f8) | Apr 16, 2023 |
| Sony          | VPCCA1S1E                   | [05ab5df066](https://linux-hardware.org/?probe=05ab5df066) | Apr 16, 2023 |
| Acer          | Nitro AN515-54              | [73c46e2901](https://linux-hardware.org/?probe=73c46e2901) | Apr 15, 2023 |
| Google        | Dragonair                   | [be10ee5035](https://linux-hardware.org/?probe=be10ee5035) | Apr 15, 2023 |
| Sony          | VPCCA1S1E                   | [30625007d9](https://linux-hardware.org/?probe=30625007d9) | Apr 15, 2023 |
| Google        | Dragonair                   | [cb2aa57d07](https://linux-hardware.org/?probe=cb2aa57d07) | Apr 15, 2023 |
| Acer          | Aspire A114-33              | [53c9fe0b8d](https://linux-hardware.org/?probe=53c9fe0b8d) | Apr 15, 2023 |
| Acer          | Aspire A114-33              | [99f95937d4](https://linux-hardware.org/?probe=99f95937d4) | Apr 15, 2023 |
| Acer          | Aspire E1-572               | [acf5e9b9f5](https://linux-hardware.org/?probe=acf5e9b9f5) | Apr 15, 2023 |
| Apple         | MacBookAir6,1               | [c649f1b898](https://linux-hardware.org/?probe=c649f1b898) | Apr 15, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [37eee19e22](https://linux-hardware.org/?probe=37eee19e22) | Apr 15, 2023 |
| HONOR         | HYM-WXX                     | [109b28f217](https://linux-hardware.org/?probe=109b28f217) | Apr 15, 2023 |
| Panasonic     | CF-C2CCEZXCM                | [361573ef78](https://linux-hardware.org/?probe=361573ef78) | Apr 14, 2023 |
| Dell          | Inspiron 7460               | [ae861b54cd](https://linux-hardware.org/?probe=ae861b54cd) | Apr 14, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [b60b4dbb07](https://linux-hardware.org/?probe=b60b4dbb07) | Apr 14, 2023 |
| Dell          | Precision 5560              | [b6d20ef4bf](https://linux-hardware.org/?probe=b6d20ef4bf) | Apr 14, 2023 |
| Dell          | Precision 5560              | [b76f840bd9](https://linux-hardware.org/?probe=b76f840bd9) | Apr 14, 2023 |
| HP            | ZBook 15                    | [c5397a7fbb](https://linux-hardware.org/?probe=c5397a7fbb) | Apr 14, 2023 |
| ASUSTek       | TUF Gaming FX505DU_TUF50... | [91d7747b6f](https://linux-hardware.org/?probe=91d7747b6f) | Apr 14, 2023 |
| ASUSTek       | TUF Gaming FX505DU_TUF50... | [59b4139974](https://linux-hardware.org/?probe=59b4139974) | Apr 14, 2023 |
| Dell          | Latitude 7400               | [0f917420a1](https://linux-hardware.org/?probe=0f917420a1) | Apr 14, 2023 |
| HP            | Laptop 15-db0xxx            | [f02a5fef82](https://linux-hardware.org/?probe=f02a5fef82) | Apr 14, 2023 |
| Lenovo        | Legion 5 15IAH7 82RC        | [9cb53e6d6f](https://linux-hardware.org/?probe=9cb53e6d6f) | Apr 13, 2023 |
| HP            | ZBook 15                    | [aaaa838a8f](https://linux-hardware.org/?probe=aaaa838a8f) | Apr 13, 2023 |
| Dell          | Inspiron N5110              | [065b7d4c01](https://linux-hardware.org/?probe=065b7d4c01) | Apr 13, 2023 |
| 3Logic Gro... | Graviton N15i-K2            | [7b75b7b08e](https://linux-hardware.org/?probe=7b75b7b08e) | Apr 13, 2023 |
| Dell          | Inspiron 5515               | [e7306b2521](https://linux-hardware.org/?probe=e7306b2521) | Apr 13, 2023 |
| HP            | ENVY Laptop 15-ep0xxx       | [04eb10296f](https://linux-hardware.org/?probe=04eb10296f) | Apr 13, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [cc0b87e611](https://linux-hardware.org/?probe=cc0b87e611) | Apr 13, 2023 |
| Lenovo        | ThinkPad T490 20N2000NRT    | [ea97cd752d](https://linux-hardware.org/?probe=ea97cd752d) | Apr 13, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [2d321f3134](https://linux-hardware.org/?probe=2d321f3134) | Apr 13, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [1707343b9b](https://linux-hardware.org/?probe=1707343b9b) | Apr 13, 2023 |
| HUAWEI        | KLVL-WXX9                   | [3166746b52](https://linux-hardware.org/?probe=3166746b52) | Apr 12, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [77384847ef](https://linux-hardware.org/?probe=77384847ef) | Apr 12, 2023 |
| Lenovo        | ThinkPad X220 42911H8       | [7eee4a859e](https://linux-hardware.org/?probe=7eee4a859e) | Apr 12, 2023 |
| Lenovo        | ThinkPad X220 42911H8       | [874513db8d](https://linux-hardware.org/?probe=874513db8d) | Apr 12, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [55a12acf3a](https://linux-hardware.org/?probe=55a12acf3a) | Apr 12, 2023 |
| Dell          | XPS 13 9370                 | [66924704d2](https://linux-hardware.org/?probe=66924704d2) | Apr 12, 2023 |
| ASUSTek       | ROG Strix G713QR_G713QR     | [65bb44978f](https://linux-hardware.org/?probe=65bb44978f) | Apr 12, 2023 |
| Lenovo        | IdeaPad Slim 9 14ITL5 82... | [16a7a866f1](https://linux-hardware.org/?probe=16a7a866f1) | Apr 12, 2023 |
| MSI           | Prestige 14Evo B13M         | [f1cafa77dd](https://linux-hardware.org/?probe=f1cafa77dd) | Apr 12, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [c33ef2ceeb](https://linux-hardware.org/?probe=c33ef2ceeb) | Apr 11, 2023 |
| HUAWEI        | HVY-WXX9                    | [10da0191c4](https://linux-hardware.org/?probe=10da0191c4) | Apr 11, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [5662df110d](https://linux-hardware.org/?probe=5662df110d) | Apr 11, 2023 |
| Dell          | XPS 13 7390                 | [da86532b55](https://linux-hardware.org/?probe=da86532b55) | Apr 11, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [3792cccd19](https://linux-hardware.org/?probe=3792cccd19) | Apr 11, 2023 |
| HUAWEI        | KLVL-WXX9                   | [52e50e17de](https://linux-hardware.org/?probe=52e50e17de) | Apr 11, 2023 |
| HP            | ProBook 650 G1              | [1a09ecfcd1](https://linux-hardware.org/?probe=1a09ecfcd1) | Apr 11, 2023 |
| Notebook      | NH55RGQ                     | [7fc1310fc2](https://linux-hardware.org/?probe=7fc1310fc2) | Apr 11, 2023 |
| Dell          | Latitude 5511               | [fa30633c71](https://linux-hardware.org/?probe=fa30633c71) | Apr 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [3c1e7c6f4a](https://linux-hardware.org/?probe=3c1e7c6f4a) | Apr 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [9d3c5ea28d](https://linux-hardware.org/?probe=9d3c5ea28d) | Apr 11, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | [69f8d7dfdf](https://linux-hardware.org/?probe=69f8d7dfdf) | Apr 11, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [ac983c99b9](https://linux-hardware.org/?probe=ac983c99b9) | Apr 10, 2023 |
| HUAWEI        | HVY-WXX9                    | [11ecb91fec](https://linux-hardware.org/?probe=11ecb91fec) | Apr 09, 2023 |
| ASUSTek       | GL552VW                     | [396850fd22](https://linux-hardware.org/?probe=396850fd22) | Apr 09, 2023 |
| ASUSTek       | P552LA                      | [803ac095e7](https://linux-hardware.org/?probe=803ac095e7) | Apr 08, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [a334fb8e82](https://linux-hardware.org/?probe=a334fb8e82) | Apr 08, 2023 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [c06058447c](https://linux-hardware.org/?probe=c06058447c) | Apr 08, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [5605228f3b](https://linux-hardware.org/?probe=5605228f3b) | Apr 08, 2023 |
| ASUSTek       | X553MA                      | [0a307c8c2b](https://linux-hardware.org/?probe=0a307c8c2b) | Apr 07, 2023 |
| HP            | Pavilion dv7                | [3a159264b1](https://linux-hardware.org/?probe=3a159264b1) | Apr 07, 2023 |
| Dell          | Inspiron N5110              | [a3ecc0f893](https://linux-hardware.org/?probe=a3ecc0f893) | Apr 07, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [8c1127cfab](https://linux-hardware.org/?probe=8c1127cfab) | Apr 07, 2023 |
| Dell          | Latitude 7490               | [01957ea955](https://linux-hardware.org/?probe=01957ea955) | Apr 07, 2023 |
| Google        | Bluebird                    | [6ab22238ac](https://linux-hardware.org/?probe=6ab22238ac) | Apr 07, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [8d68ef79c3](https://linux-hardware.org/?probe=8d68ef79c3) | Apr 06, 2023 |
| Clevo         | M815P                       | [e5194b9fea](https://linux-hardware.org/?probe=e5194b9fea) | Apr 06, 2023 |
| Dell          | XPS 9320                    | [ff14e0074a](https://linux-hardware.org/?probe=ff14e0074a) | Apr 06, 2023 |
| MSI           | Katana 17 B12VGK            | [0f8f9e8ba8](https://linux-hardware.org/?probe=0f8f9e8ba8) | Apr 06, 2023 |
| HP            | Sona                        | [64fa63647b](https://linux-hardware.org/?probe=64fa63647b) | Apr 06, 2023 |
| Samsung       | 760XDA                      | [625178fa5a](https://linux-hardware.org/?probe=625178fa5a) | Apr 06, 2023 |
| NEC Comput... | PC-VK27MCZCK                | [e9572ebd2e](https://linux-hardware.org/?probe=e9572ebd2e) | Apr 06, 2023 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [320195c782](https://linux-hardware.org/?probe=320195c782) | Apr 06, 2023 |
| MSI           | Delta 15 A5EFK              | [d3066bb3d4](https://linux-hardware.org/?probe=d3066bb3d4) | Apr 06, 2023 |
| ASUSTek       | GL552VW                     | [ab450c0ddd](https://linux-hardware.org/?probe=ab450c0ddd) | Apr 06, 2023 |
| HP            | OMEN by Laptop 16-b1xxx     | [d741226152](https://linux-hardware.org/?probe=d741226152) | Apr 06, 2023 |
| Dell          | Latitude E7470              | [64721a0d8a](https://linux-hardware.org/?probe=64721a0d8a) | Apr 05, 2023 |
| ASUSTek       | T100TAF                     | [fed8f42482](https://linux-hardware.org/?probe=fed8f42482) | Apr 05, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [a64c365f62](https://linux-hardware.org/?probe=a64c365f62) | Apr 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [0af2f7cc7f](https://linux-hardware.org/?probe=0af2f7cc7f) | Apr 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [f98b9efce7](https://linux-hardware.org/?probe=f98b9efce7) | Apr 05, 2023 |
| HUAWEI        | MACHD-WXX9                  | [7e5be74f0b](https://linux-hardware.org/?probe=7e5be74f0b) | Apr 05, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | [36338ecf6e](https://linux-hardware.org/?probe=36338ecf6e) | Apr 05, 2023 |
| Lenovo        | G50-80 80E5                 | [b469666726](https://linux-hardware.org/?probe=b469666726) | Apr 05, 2023 |
| Apple         | MacBookPro9,2               | [3a70dc24db](https://linux-hardware.org/?probe=3a70dc24db) | Apr 05, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [4710939159](https://linux-hardware.org/?probe=4710939159) | Apr 05, 2023 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [8982660d51](https://linux-hardware.org/?probe=8982660d51) | Apr 05, 2023 |
| HP            | 255 G8 Notebook PC          | [4c46d2ae80](https://linux-hardware.org/?probe=4c46d2ae80) | Apr 04, 2023 |
| ASUSTek       | X550JK                      | [b75b9b9fa2](https://linux-hardware.org/?probe=b75b9b9fa2) | Apr 04, 2023 |
| HP            | Notebook                    | [935131a649](https://linux-hardware.org/?probe=935131a649) | Apr 04, 2023 |
| HP            | Notebook                    | [f35bee3b90](https://linux-hardware.org/?probe=f35bee3b90) | Apr 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [c2240b20c2](https://linux-hardware.org/?probe=c2240b20c2) | Apr 04, 2023 |
| Dell          | XPS 15 9520                 | [1158a2ec97](https://linux-hardware.org/?probe=1158a2ec97) | Apr 04, 2023 |
| Notebook      | L140PU                      | [628319771e](https://linux-hardware.org/?probe=628319771e) | Apr 04, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [ddbd47af34](https://linux-hardware.org/?probe=ddbd47af34) | Apr 04, 2023 |
| Dell          | Vostro 15 3515              | [95a98c59b1](https://linux-hardware.org/?probe=95a98c59b1) | Apr 03, 2023 |
| Fujitsu       | LIFEBOOK U747               | [868448ea4b](https://linux-hardware.org/?probe=868448ea4b) | Apr 03, 2023 |
| Apple         | MacBookPro9,2               | [f4343acc49](https://linux-hardware.org/?probe=f4343acc49) | Apr 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [e6a732e9b0](https://linux-hardware.org/?probe=e6a732e9b0) | Apr 03, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [0b97a5a77a](https://linux-hardware.org/?probe=0b97a5a77a) | Apr 03, 2023 |
| Dell          | Inspiron 7577               | [ada2cb6e08](https://linux-hardware.org/?probe=ada2cb6e08) | Apr 02, 2023 |
| Dell          | Inspiron 7577               | [a761c8f978](https://linux-hardware.org/?probe=a761c8f978) | Apr 02, 2023 |
| Toshiba       | Satellite C55-B             | [da341e3be8](https://linux-hardware.org/?probe=da341e3be8) | Apr 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [f995b3a81f](https://linux-hardware.org/?probe=f995b3a81f) | Apr 02, 2023 |
| Apple         | MacBookPro9,2               | [3e558165a4](https://linux-hardware.org/?probe=3e558165a4) | Apr 02, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [65cee818b6](https://linux-hardware.org/?probe=65cee818b6) | Apr 02, 2023 |
| Samsung       | 550P5C/550P7C               | [8e6191f4bb](https://linux-hardware.org/?probe=8e6191f4bb) | Apr 02, 2023 |
| ilife         | S806                        | [d089301e66](https://linux-hardware.org/?probe=d089301e66) | Apr 02, 2023 |
| Lenovo        | ThinkPad E14 20RAS0D800     | [ea2f5b484f](https://linux-hardware.org/?probe=ea2f5b484f) | Apr 02, 2023 |
| Lenovo        | ThinkPad E495 20NE001RTX    | [804bf25c27](https://linux-hardware.org/?probe=804bf25c27) | Apr 02, 2023 |
| HP            | Laptop 17-by3xxx            | [76ad9ff828](https://linux-hardware.org/?probe=76ad9ff828) | Apr 02, 2023 |
| Dell          | Inspiron N5110              | [aa74b25c97](https://linux-hardware.org/?probe=aa74b25c97) | Apr 02, 2023 |
| Lenovo        | ThinkPad A485 20MUCTO1WW    | [f64cf6a2ae](https://linux-hardware.org/?probe=f64cf6a2ae) | Apr 02, 2023 |
| HP            | Snappy                      | [993161a4c7](https://linux-hardware.org/?probe=993161a4c7) | Apr 02, 2023 |
| ilife         | S806                        | [3a3ccd7c55](https://linux-hardware.org/?probe=3a3ccd7c55) | Apr 02, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [dabe76e4ca](https://linux-hardware.org/?probe=dabe76e4ca) | Apr 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [95c5f574c9](https://linux-hardware.org/?probe=95c5f574c9) | Apr 01, 2023 |
| Dell          | Latitude E5450              | [89701abaa1](https://linux-hardware.org/?probe=89701abaa1) | Apr 01, 2023 |
| HP            | ProBook 6475b               | [680348d948](https://linux-hardware.org/?probe=680348d948) | Apr 01, 2023 |
| ASUSTek       | T100TA                      | [5be9a0230e](https://linux-hardware.org/?probe=5be9a0230e) | Apr 01, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [36fab57ba7](https://linux-hardware.org/?probe=36fab57ba7) | Mar 31, 2023 |
| Dell          | Inspiron 7577               | [5800e3859c](https://linux-hardware.org/?probe=5800e3859c) | Mar 31, 2023 |
| Acer          | Nitro AN515-54              | [9e7aa15a9f](https://linux-hardware.org/?probe=9e7aa15a9f) | Mar 31, 2023 |
| HUAWEI        | HN-WX9X                     | [b10ed7894c](https://linux-hardware.org/?probe=b10ed7894c) | Mar 31, 2023 |
| Acer          | Swift SF113-31              | [fc0539603c](https://linux-hardware.org/?probe=fc0539603c) | Mar 31, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | [c76f4f4354](https://linux-hardware.org/?probe=c76f4f4354) | Mar 31, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | [3a74487ae8](https://linux-hardware.org/?probe=3a74487ae8) | Mar 31, 2023 |
| Toshiba       | Satellite U940              | [277dba9c1f](https://linux-hardware.org/?probe=277dba9c1f) | Mar 31, 2023 |
| Toshiba       | Satellite U940              | [8a5046cad7](https://linux-hardware.org/?probe=8a5046cad7) | Mar 31, 2023 |
| HP            | EliteBook 8460p             | [1d5f866283](https://linux-hardware.org/?probe=1d5f866283) | Mar 31, 2023 |
| MSI           | GS66 Stealth 10SF           | [a2589dd6f5](https://linux-hardware.org/?probe=a2589dd6f5) | Mar 31, 2023 |
| Google        | Cave                        | [8bd24407be](https://linux-hardware.org/?probe=8bd24407be) | Mar 31, 2023 |
| Exo           | Smart XL4                   | [6421142cb6](https://linux-hardware.org/?probe=6421142cb6) | Mar 31, 2023 |
| Dell          | Latitude D620               | [801ede47a2](https://linux-hardware.org/?probe=801ede47a2) | Mar 31, 2023 |
| Acer          | Swift SFA16-41              | [e110fbb7d6](https://linux-hardware.org/?probe=e110fbb7d6) | Mar 31, 2023 |
| HP            | EliteBook 6930p             | [5b087b11f5](https://linux-hardware.org/?probe=5b087b11f5) | Mar 30, 2023 |
| Dell          | Precision 5510              | [4bbf7f5ef2](https://linux-hardware.org/?probe=4bbf7f5ef2) | Mar 30, 2023 |
| AIR           | CX30500                     | [2ea4d0ec83](https://linux-hardware.org/?probe=2ea4d0ec83) | Mar 30, 2023 |
| Lenovo        | ThinkPad T470s 20HGS23V0... | [6af08c4bfe](https://linux-hardware.org/?probe=6af08c4bfe) | Mar 30, 2023 |
| Lenovo        | ThinkPad T470s 20HGS23V0... | [6f0d3fd82b](https://linux-hardware.org/?probe=6f0d3fd82b) | Mar 30, 2023 |
| HUAWEI        | KLVL-WXXW                   | [ab31f6f63d](https://linux-hardware.org/?probe=ab31f6f63d) | Mar 30, 2023 |
| Dell          | Inspiron 15 5510            | [162132b606](https://linux-hardware.org/?probe=162132b606) | Mar 30, 2023 |
| Toshiba       | Satellite C850-C5K          | [8fc7451def](https://linux-hardware.org/?probe=8fc7451def) | Mar 30, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | [5cf96e41e0](https://linux-hardware.org/?probe=5cf96e41e0) | Mar 30, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [c73c5374a4](https://linux-hardware.org/?probe=c73c5374a4) | Mar 30, 2023 |
| Dell          | G15 5515                    | [7bb6311632](https://linux-hardware.org/?probe=7bb6311632) | Mar 30, 2023 |
| HP            | 250 G6 Notebook PC          | [159d154fca](https://linux-hardware.org/?probe=159d154fca) | Mar 30, 2023 |
| Dell          | Latitude 5580               | [84157deda8](https://linux-hardware.org/?probe=84157deda8) | Mar 29, 2023 |
| Dell          | XPS 13 7390                 | [2eb96be1ee](https://linux-hardware.org/?probe=2eb96be1ee) | Mar 29, 2023 |
| Lenovo        | ThinkPad T470s 20HGS07D0... | [7a8b075b23](https://linux-hardware.org/?probe=7a8b075b23) | Mar 29, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [d74490158e](https://linux-hardware.org/?probe=d74490158e) | Mar 29, 2023 |
| Apple         | MacBookPro8,1               | [6023df2b8b](https://linux-hardware.org/?probe=6023df2b8b) | Mar 29, 2023 |
| Dell          | Latitude 5420               | [aee5c648e7](https://linux-hardware.org/?probe=aee5c648e7) | Mar 29, 2023 |
| Dell          | Latitude 7430               | [3f3b04c185](https://linux-hardware.org/?probe=3f3b04c185) | Mar 29, 2023 |
| HP            | EliteBook 8770w             | [46a3f1d497](https://linux-hardware.org/?probe=46a3f1d497) | Mar 29, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [2f6655b77c](https://linux-hardware.org/?probe=2f6655b77c) | Mar 29, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | [bf2f7820cd](https://linux-hardware.org/?probe=bf2f7820cd) | Mar 29, 2023 |
| Notebook      | L140CU                      | [e24f4b285d](https://linux-hardware.org/?probe=e24f4b285d) | Mar 29, 2023 |
| Notebook      | L140CU                      | [b1b0a5fc03](https://linux-hardware.org/?probe=b1b0a5fc03) | Mar 29, 2023 |
| ASUSTek       | Zenbook UX5401ZA_UX5401Z... | [c8f2b78c09](https://linux-hardware.org/?probe=c8f2b78c09) | Mar 29, 2023 |
| Clevo         | M815P                       | [ac4eae2a0b](https://linux-hardware.org/?probe=ac4eae2a0b) | Mar 29, 2023 |
| HP            | Pavilion g7                 | [5b1e547f92](https://linux-hardware.org/?probe=5b1e547f92) | Mar 29, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [ccb2d60f5c](https://linux-hardware.org/?probe=ccb2d60f5c) | Mar 29, 2023 |
| HP            | Pavilion g7                 | [ce74564fd9](https://linux-hardware.org/?probe=ce74564fd9) | Mar 28, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [5520b0fc5f](https://linux-hardware.org/?probe=5520b0fc5f) | Mar 28, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | [67789fc0d1](https://linux-hardware.org/?probe=67789fc0d1) | Mar 28, 2023 |
| Lenovo        | ThinkPad T470p 20J7S0QK0... | [7f5fb11940](https://linux-hardware.org/?probe=7f5fb11940) | Mar 28, 2023 |
| ASUSTek       | TX201LA                     | [27c77d0b6c](https://linux-hardware.org/?probe=27c77d0b6c) | Mar 28, 2023 |
| Lenovo        | ThinkPad T495 20NJ000XGE    | [70715024f2](https://linux-hardware.org/?probe=70715024f2) | Mar 28, 2023 |
| HP            | Compaq 6720s                | [9998cb9bfb](https://linux-hardware.org/?probe=9998cb9bfb) | Mar 27, 2023 |
| Dell          | Inspiron N5110              | [7ff133a50e](https://linux-hardware.org/?probe=7ff133a50e) | Mar 27, 2023 |
| HP            | 250 G1                      | [75cf798dde](https://linux-hardware.org/?probe=75cf798dde) | Mar 27, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [3173dc99b6](https://linux-hardware.org/?probe=3173dc99b6) | Mar 27, 2023 |
| Dell          | Latitude E5250              | [7d9e678484](https://linux-hardware.org/?probe=7d9e678484) | Mar 27, 2023 |
| Dell          | Inspiron N5110              | [6b3c579924](https://linux-hardware.org/?probe=6b3c579924) | Mar 27, 2023 |
| Alienware     | 17 R4                       | [4a61d300b5](https://linux-hardware.org/?probe=4a61d300b5) | Mar 27, 2023 |
| Acer          | Predator PT515-51           | [2ac6541cf1](https://linux-hardware.org/?probe=2ac6541cf1) | Mar 27, 2023 |
| Dell          | Latitude 7280               | [409cf549eb](https://linux-hardware.org/?probe=409cf549eb) | Mar 27, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | [0ab4054ab9](https://linux-hardware.org/?probe=0ab4054ab9) | Mar 26, 2023 |
| Dell          | G15 5515                    | [3af5157823](https://linux-hardware.org/?probe=3af5157823) | Mar 26, 2023 |
| Chuwi         | HeroBook Air                | [836112a53f](https://linux-hardware.org/?probe=836112a53f) | Mar 26, 2023 |
| Lenovo        | G50-80 80E5                 | [250e0a99d1](https://linux-hardware.org/?probe=250e0a99d1) | Mar 26, 2023 |
| Acer          | Nitro AN515-55              | [36d5ba7071](https://linux-hardware.org/?probe=36d5ba7071) | Mar 26, 2023 |
| Acer          | Nitro AN515-54              | [2163c72a12](https://linux-hardware.org/?probe=2163c72a12) | Mar 25, 2023 |
| Dell          | Vostro 15 3515              | [a999580cf7](https://linux-hardware.org/?probe=a999580cf7) | Mar 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [31788e7103](https://linux-hardware.org/?probe=31788e7103) | Mar 25, 2023 |
| Dell          | Latitude E6230              | [1a248bdc33](https://linux-hardware.org/?probe=1a248bdc33) | Mar 25, 2023 |
| Lenovo        | G580 2189                   | [edba6da5b6](https://linux-hardware.org/?probe=edba6da5b6) | Mar 25, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [ae09be520b](https://linux-hardware.org/?probe=ae09be520b) | Mar 25, 2023 |
| HP            | OMEN by Laptop 16-b1xxx     | [0096d3d3b1](https://linux-hardware.org/?probe=0096d3d3b1) | Mar 25, 2023 |
| ASUSTek       | GL503VS                     | [8e066fcf6e](https://linux-hardware.org/?probe=8e066fcf6e) | Mar 25, 2023 |
| MSI           | Summit E16FlipEvo A11MT     | [62839dd4ac](https://linux-hardware.org/?probe=62839dd4ac) | Mar 24, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [24784bc54d](https://linux-hardware.org/?probe=24784bc54d) | Mar 24, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [c2255f36b2](https://linux-hardware.org/?probe=c2255f36b2) | Mar 24, 2023 |
| ASUSTek       | ROG Strix G512LW_G512LW     | [cbb1418cfa](https://linux-hardware.org/?probe=cbb1418cfa) | Mar 24, 2023 |
| Acer          | Aspire E5-574               | [51a085fb56](https://linux-hardware.org/?probe=51a085fb56) | Mar 24, 2023 |
| Dell          | G15 5515                    | [3510cdb4cf](https://linux-hardware.org/?probe=3510cdb4cf) | Mar 24, 2023 |
| Dell          | Precision 3551              | [bc979e320b](https://linux-hardware.org/?probe=bc979e320b) | Mar 24, 2023 |
| Dell          | Precision 3551              | [0509bee16a](https://linux-hardware.org/?probe=0509bee16a) | Mar 24, 2023 |
| ASUSTek       | ZenBook UX433FN_BX433FN     | [d8e67b032e](https://linux-hardware.org/?probe=d8e67b032e) | Mar 24, 2023 |
| MSI           | Modern 14 B4MW              | [c81d9f3b07](https://linux-hardware.org/?probe=c81d9f3b07) | Mar 24, 2023 |
| HP            | Laptop 17-by3xxx            | [01cac0e411](https://linux-hardware.org/?probe=01cac0e411) | Mar 24, 2023 |
| Lenovo        | IdeaPad Yoga 13 20175       | [56d564423e](https://linux-hardware.org/?probe=56d564423e) | Mar 24, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [ca7d9a9342](https://linux-hardware.org/?probe=ca7d9a9342) | Mar 24, 2023 |
| Dell          | Latitude 5580               | [d4ad4c55a6](https://linux-hardware.org/?probe=d4ad4c55a6) | Mar 24, 2023 |
| Dell          | Latitude 5285               | [a8114ded15](https://linux-hardware.org/?probe=a8114ded15) | Mar 23, 2023 |
| HP            | 250 G4                      | [e0ff721413](https://linux-hardware.org/?probe=e0ff721413) | Mar 23, 2023 |
| Dell          | Latitude 5285               | [baa8f358cf](https://linux-hardware.org/?probe=baa8f358cf) | Mar 23, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [aeb25bc22b](https://linux-hardware.org/?probe=aeb25bc22b) | Mar 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [2d44e8f5c2](https://linux-hardware.org/?probe=2d44e8f5c2) | Mar 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [19efb75aa1](https://linux-hardware.org/?probe=19efb75aa1) | Mar 23, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Fedora/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| Fedora 36 | 1228      | 16.88%  |
| Fedora 37 | 1185      | 16.29%  |
| Fedora 35 | 967       | 13.29%  |
| Fedora 34 | 936       | 12.87%  |
| Fedora 33 | 855       | 11.75%  |
| Fedora 32 | 746       | 10.26%  |
| Fedora 38 | 553       | 7.6%    |
| Fedora 31 | 503       | 6.92%   |
| Fedora 30 | 163       | 2.24%   |
| Fedora 29 | 90        | 1.24%   |
| Fedora 28 | 22        | 0.3%    |
| Fedora 39 | 8         | 0.11%   |
| Fedora 27 | 8         | 0.11%   |
| Fedora 24 | 4         | 0.05%   |
| Fedora 21 | 4         | 0.05%   |
| Fedora 25 | 2         | 0.03%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Fedora | 6505      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 6.2.15-300.fc38.x86_64  | 134       | 1.65%   |
| 5.17.5-300.fc36.x86_64  | 113       | 1.4%    |
| 5.16.18-200.fc35.x86_64 | 92        | 1.14%   |
| 6.2.14-300.fc38.x86_64  | 90        | 1.11%   |
| 5.9.16-200.fc33.x86_64  | 90        | 1.11%   |
| 6.2.11-300.fc38.x86_64  | 87        | 1.07%   |
| 6.0.7-301.fc37.x86_64   | 85        | 1.05%   |
| 5.11.12-300.fc34.x86_64 | 77        | 0.95%   |
| 6.0.15-300.fc37.x86_64  | 76        | 0.94%   |
| 5.14.10-300.fc35.x86_64 | 70        | 0.86%   |
| 6.0.5-200.fc36.x86_64   | 69        | 0.85%   |
| 5.8.16-300.fc33.x86_64  | 64        | 0.79%   |
| 6.1.14-200.fc37.x86_64  | 61        | 0.75%   |
| 5.18.13-200.fc36.x86_64 | 61        | 0.75%   |
| 5.8.15-301.fc33.x86_64  | 60        | 0.74%   |
| 5.8.4-200.fc32.x86_64   | 57        | 0.7%    |
| 6.1.7-200.fc37.x86_64   | 56        | 0.69%   |
| 6.2.9-300.fc38.x86_64   | 55        | 0.68%   |
| 6.0.8-300.fc37.x86_64   | 54        | 0.67%   |
| 5.13.12-200.fc34.x86_64 | 54        | 0.67%   |
| 6.0.9-300.fc37.x86_64   | 52        | 0.64%   |
| 6.1.18-200.fc37.x86_64  | 51        | 0.63%   |
| 6.0.12-300.fc37.x86_64  | 51        | 0.63%   |
| 5.18.11-200.fc36.x86_64 | 50        | 0.62%   |
| 5.19.16-200.fc36.x86_64 | 47        | 0.58%   |
| 6.2.8-200.fc37.x86_64   | 46        | 0.57%   |
| 6.2.13-300.fc38.x86_64  | 46        | 0.57%   |
| 5.8.18-300.fc33.x86_64  | 46        | 0.57%   |
| 5.17.11-300.fc36.x86_64 | 46        | 0.57%   |
| 5.14.16-301.fc35.x86_64 | 46        | 0.57%   |
| 5.9.8-200.fc33.x86_64   | 45        | 0.56%   |
| 5.18.16-200.fc36.x86_64 | 45        | 0.56%   |
| 5.16.16-200.fc35.x86_64 | 44        | 0.54%   |
| 6.1.8-200.fc37.x86_64   | 43        | 0.53%   |
| 5.17.6-300.fc36.x86_64  | 43        | 0.53%   |
| 6.1.11-200.fc37.x86_64  | 42        | 0.52%   |
| 5.19.9-200.fc36.x86_64  | 42        | 0.52%   |
| 5.15.6-200.fc35.x86_64  | 42        | 0.52%   |
| 6.3.5-200.fc38.x86_64   | 41        | 0.51%   |
| 5.16.12-200.fc35.x86_64 | 41        | 0.51%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2.15  | 158       | 1.95%   |
| 5.17.5  | 147       | 1.82%   |
| 6.2.14  | 102       | 1.26%   |
| 6.2.11  | 99        | 1.22%   |
| 6.2.9   | 96        | 1.19%   |
| 5.9.16  | 96        | 1.19%   |
| 6.0.7   | 95        | 1.17%   |
| 5.16.18 | 95        | 1.17%   |
| 5.8.15  | 87        | 1.08%   |
| 6.0.15  | 86        | 1.06%   |
| 5.11.12 | 84        | 1.04%   |
| 5.8.16  | 81        | 1%      |
| 5.14.10 | 79        | 0.98%   |
| 6.0.5   | 75        | 0.93%   |
| 5.19.16 | 75        | 0.93%   |
| 6.0.9   | 67        | 0.83%   |
| 5.11.11 | 66        | 0.82%   |
| 5.18.13 | 65        | 0.8%    |
| 6.1.14  | 64        | 0.79%   |
| 6.0.8   | 64        | 0.79%   |
| 5.8.18  | 64        | 0.79%   |
| 6.0.12  | 63        | 0.78%   |
| 6.1.7   | 60        | 0.74%   |
| 6.2.8   | 57        | 0.7%    |
| 5.8.4   | 57        | 0.7%    |
| 5.13.12 | 57        | 0.7%    |
| 5.14.18 | 56        | 0.69%   |
| 5.18.11 | 53        | 0.65%   |
| 6.1.18  | 52        | 0.64%   |
| 5.14.16 | 52        | 0.64%   |
| 5.9.8   | 51        | 0.63%   |
| 5.19.8  | 50        | 0.62%   |
| 5.17.11 | 50        | 0.62%   |
| 5.15.6  | 50        | 0.62%   |
| 5.19.9  | 49        | 0.61%   |
| 5.18.16 | 48        | 0.59%   |
| 5.17.6  | 47        | 0.58%   |
| 5.16.16 | 47        | 0.58%   |
| 6.2.13  | 46        | 0.57%   |
| 6.1.8   | 46        | 0.57%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2     | 654       | 8.46%   |
| 6.0     | 638       | 8.26%   |
| 5.17    | 513       | 6.64%   |
| 6.1     | 479       | 6.2%    |
| 5.8     | 464       | 6.01%   |
| 5.11    | 449       | 5.81%   |
| 5.19    | 448       | 5.8%    |
| 5.18    | 410       | 5.31%   |
| 5.14    | 393       | 5.09%   |
| 5.16    | 384       | 4.97%   |
| 5.15    | 310       | 4.01%   |
| 5.9     | 304       | 3.93%   |
| 5.13    | 303       | 3.92%   |
| 5.10    | 293       | 3.79%   |
| 5.6     | 286       | 3.7%    |
| 5.12    | 282       | 3.65%   |
| 5.7     | 221       | 2.86%   |
| 5.3     | 194       | 2.51%   |
| 5.5     | 183       | 2.37%   |
| 5.4     | 168       | 2.17%   |
| 6.3     | 97        | 1.26%   |
| 5.0     | 62        | 0.8%    |
| 5.2     | 47        | 0.61%   |
| 5.1     | 43        | 0.56%   |
| 4.19    | 30        | 0.39%   |
| 4.18    | 27        | 0.35%   |
| 4.20    | 18        | 0.23%   |
| 6.4     | 5         | 0.06%   |
| 4.16    | 3         | 0.04%   |
| 4.15    | 3         | 0.04%   |
| 4.11    | 3         | 0.04%   |
| 4.1     | 3         | 0.04%   |
| 4.8     | 2         | 0.03%   |
| 4.17    | 2         | 0.03%   |
| 4.5     | 1         | 0.01%   |
| 4.14    | 1         | 0.01%   |
| 4.10    | 1         | 0.01%   |
| 3.17    | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 6496      | 99.85%  |
| i686    | 5         | 0.08%   |
| aarch64 | 4         | 0.06%   |
| Unknown | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 4930      | 73.77%  |
| KDE5            | 750       | 11.22%  |
| Unknown         | 315       | 4.71%   |
| XFCE            | 138       | 2.06%   |
| KDE             | 136       | 2.04%   |
| X-Cinnamon      | 91        | 1.36%   |
| MATE            | 86        | 1.29%   |
| Cinnamon        | 74        | 1.11%   |
| i3              | 33        | 0.49%   |
| LXQt            | 23        | 0.34%   |
| GNOME Classic   | 22        | 0.33%   |
| LXDE            | 17        | 0.25%   |
| sway            | 16        | 0.24%   |
| Deepin          | 13        | 0.19%   |
| Budgie          | 5         | 0.07%   |
| Pantheon        | 4         | 0.06%   |
| awesome         | 4         | 0.06%   |
| openbox         | 3         | 0.04%   |
| KDE4            | 3         | 0.04%   |
| GNOME Flashback | 3         | 0.04%   |
| fluxbox         | 3         | 0.04%   |
| xinit-compat    | 2         | 0.03%   |
| Hyprland        | 2         | 0.03%   |
| GNOME-Classic   | 2         | 0.03%   |
| dwm             | 2         | 0.03%   |
| bspwm           | 2         | 0.03%   |
| xmonad          | 1         | 0.01%   |
| qtile           | 1         | 0.01%   |
| KDE:old         | 1         | 0.01%   |
| custom          | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 4422      | 65.47%  |
| X11     | 2078      | 30.77%  |
| Unknown | 205       | 3.04%   |
| Tty     | 48        | 0.71%   |
| Xcb     | 1         | 0.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 3377      | 50.49%  |
| GDM     | 2469      | 36.91%  |
| SDDM    | 469       | 7.01%   |
| LightDM | 259       | 3.87%   |
| TDM     | 87        | 1.3%    |
| XDM     | 10        | 0.15%   |
| KDM     | 8         | 0.12%   |
| LXDM    | 7         | 0.1%    |
| SLiM    | 1         | 0.01%   |
| Ly      | 1         | 0.01%   |
| GREETD  | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 3382      | 51.04%  |
| en_GB   | 453       | 6.84%   |
| Unknown | 368       | 5.55%   |
| pt_BR   | 316       | 4.77%   |
| ru_RU   | 301       | 4.54%   |
| de_DE   | 227       | 3.43%   |
| fr_FR   | 204       | 3.08%   |
| it_IT   | 179       | 2.7%    |
| pl_PL   | 108       | 1.63%   |
| es_ES   | 100       | 1.51%   |
| en_CA   | 93        | 1.4%    |
| en_IN   | 81        | 1.22%   |
| en_AU   | 79        | 1.19%   |
| es_MX   | 65        | 0.98%   |
| es_CL   | 43        | 0.65%   |
| cs_CZ   | 42        | 0.63%   |
| zh_CN   | 34        | 0.51%   |
| tr_TR   | 34        | 0.51%   |
| es_AR   | 32        | 0.48%   |
| nl_NL   | 26        | 0.39%   |
| de_AT   | 25        | 0.38%   |
| pt_PT   | 24        | 0.36%   |
| sv_SE   | 22        | 0.33%   |
| hu_HU   | 22        | 0.33%   |
| es_CO   | 21        | 0.32%   |
| en_NZ   | 20        | 0.3%    |
| C       | 20        | 0.3%    |
| en_DK   | 18        | 0.27%   |
| en_IE   | 15        | 0.23%   |
| ru_UA   | 14        | 0.21%   |
| en_ZA   | 14        | 0.21%   |
| fr_CA   | 13        | 0.2%    |
| fi_FI   | 12        | 0.18%   |
| fr_BE   | 11        | 0.17%   |
| es_PE   | 11        | 0.17%   |
| de_CH   | 11        | 0.17%   |
| nb_NO   | 10        | 0.15%   |
| uk_UA   | 9         | 0.14%   |
| sk_SK   | 9         | 0.14%   |
| da_DK   | 9         | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 5283      | 80.11%  |
| BIOS | 1312      | 19.89%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type                | Notebooks | Percent |
|---------------------|-----------|---------|
| Btrfs               | 4021      | 60.33%  |
| Ext4                | 2266      | 34%     |
| Unknown             | 195       | 2.93%   |
| Xfs                 | 160       | 2.4%    |
| Overlay             | 12        | 0.18%   |
| Zfs                 | 3         | 0.05%   |
| F2fs                | 3         | 0.05%   |
| Ext3                | 3         | 0.05%   |
| Fuse.fuse-overlayfs | 2         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 3356      | 50.4%   |
| GPT     | 2908      | 43.67%  |
| MBR     | 395       | 5.93%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 5977      | 90.84%  |
| Yes       | 603       | 9.16%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 5377      | 81.64%  |
| Yes       | 1209      | 18.36%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 1936      | 29.76%  |
| Dell                   | 1170      | 17.99%  |
| Hewlett-Packard        | 960       | 14.76%  |
| ASUSTek Computer       | 666       | 10.24%  |
| Acer                   | 423       | 6.5%    |
| Apple                  | 168       | 2.58%   |
| MSI                    | 147       | 2.26%   |
| HUAWEI                 | 137       | 2.11%   |
| Toshiba                | 91        | 1.4%    |
| Samsung Electronics    | 87        | 1.34%   |
| Sony                   | 53        | 0.81%   |
| Notebook               | 53        | 0.81%   |
| Timi                   | 45        | 0.69%   |
| Unknown                | 34        | 0.52%   |
| Framework              | 33        | 0.51%   |
| Google                 | 31        | 0.48%   |
| Fujitsu                | 27        | 0.42%   |
| Alienware              | 26        | 0.4%    |
| Positivo               | 24        | 0.37%   |
| System76               | 19        | 0.29%   |
| TUXEDO                 | 18        | 0.28%   |
| Razer                  | 17        | 0.26%   |
| LG Electronics         | 16        | 0.25%   |
| HONOR                  | 12        | 0.18%   |
| Chuwi                  | 12        | 0.18%   |
| Avell High Performance | 12        | 0.18%   |
| Gigabyte Technology    | 11        | 0.17%   |
| PC Specialist          | 10        | 0.15%   |
| GPU Company            | 9         | 0.14%   |
| Panasonic              | 8         | 0.12%   |
| SLIMBOOK               | 7         | 0.11%   |
| Schenker               | 7         | 0.11%   |
| GPD                    | 7         | 0.11%   |
| Fujitsu Siemens        | 7         | 0.11%   |
| Packard Bell           | 6         | 0.09%   |
| Insyde                 | 6         | 0.09%   |
| Hampoo                 | 6         | 0.09%   |
| Clevo                  | 6         | 0.09%   |
| UNOWHY                 | 5         | 0.08%   |
| Standard               | 5         | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 57        | 0.88%   |
| HP Notebook                                | 32        | 0.49%   |
| Framework Laptop                           | 25        | 0.38%   |
| Dell XPS 15 9570                           | 25        | 0.38%   |
| Dell XPS 13 9370                           | 23        | 0.35%   |
| Dell Latitude 7490                         | 23        | 0.35%   |
| Dell XPS 15 7590                           | 22        | 0.34%   |
| Dell XPS 15 9560                           | 21        | 0.32%   |
| Dell XPS 13 9310                           | 20        | 0.31%   |
| Dell XPS 13 9360                           | 19        | 0.29%   |
| Dell XPS 13 7390                           | 19        | 0.29%   |
| HP EliteBook 840 G6                        | 18        | 0.28%   |
| Dell XPS 15 9500                           | 18        | 0.28%   |
| Dell Latitude E7450                        | 18        | 0.28%   |
| HP Pavilion dv6                            | 17        | 0.26%   |
| Dell XPS 15 9550                           | 17        | 0.26%   |
| Apple MacBookPro9,2                        | 16        | 0.25%   |
| HP Pavilion 15                             | 15        | 0.23%   |
| Lenovo ThinkBook 15 G2 ITL 20VE            | 14        | 0.22%   |
| HP Laptop 15-da0xxx                        | 14        | 0.22%   |
| Dell XPS 13 9300                           | 14        | 0.22%   |
| Apple MacBookPro12,1                       | 14        | 0.22%   |
| Lenovo ThinkPad X1 Carbon Gen 8 20U9CTO1WW | 13        | 0.2%    |
| HUAWEI KLVL-WXX9                           | 13        | 0.2%    |
| HP Pavilion Notebook                       | 13        | 0.2%    |
| HP EliteBook 840 G3                        | 13        | 0.2%    |
| Dell Latitude E6420                        | 13        | 0.2%    |
| Dell Latitude 5480                         | 13        | 0.2%    |
| Dell Inspiron 15 7000 Gaming               | 13        | 0.2%    |
| Acer Nitro AN515-54                        | 13        | 0.2%    |
| Lenovo IdeaPad 5 15ARE05 81YQ              | 12        | 0.18%   |
| HUAWEI NBLK-WAX9X                          | 12        | 0.18%   |
| HP Pavilion dv7                            | 12        | 0.18%   |
| Dell XPS 13 9380                           | 12        | 0.18%   |
| Dell Latitude E7440                        | 12        | 0.18%   |
| Dell Latitude E6520                        | 12        | 0.18%   |
| Dell Inspiron 5570                         | 12        | 0.18%   |
| ASUS ROG Zephyrus G14 GA401QM_GA401QM      | 12        | 0.18%   |
| Dell XPS 13 9350                           | 11        | 0.17%   |
| Dell Latitude 5490                         | 11        | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 1184      | 18.2%   |
| Lenovo IdeaPad     | 389       | 5.98%   |
| Dell Latitude      | 346       | 5.32%   |
| Dell Inspiron      | 326       | 5.01%   |
| Dell XPS           | 271       | 4.17%   |
| Acer Aspire        | 266       | 4.09%   |
| HP Pavilion        | 208       | 3.2%    |
| HP EliteBook       | 181       | 2.78%   |
| HP ProBook         | 146       | 2.24%   |
| HP Laptop          | 139       | 2.14%   |
| ASUS VivoBook      | 131       | 2.01%   |
| ASUS ROG           | 106       | 1.63%   |
| Dell Precision     | 99        | 1.52%   |
| Lenovo Legion      | 76        | 1.17%   |
| Toshiba Satellite  | 75        | 1.15%   |
| Lenovo ThinkBook   | 73        | 1.12%   |
| Acer Nitro         | 62        | 0.95%   |
| ASUS ASUS          | 60        | 0.92%   |
| Dell Vostro        | 58        | 0.89%   |
| Lenovo Yoga        | 57        | 0.88%   |
| Unknown            | 57        | 0.88%   |
| HP ZBook           | 54        | 0.83%   |
| ASUS ZenBook       | 53        | 0.81%   |
| Acer Swift         | 41        | 0.63%   |
| HP ENVY            | 39        | 0.6%    |
| Apple MacBookPro11 | 34        | 0.52%   |
| Framework Laptop   | 33        | 0.51%   |
| HP Notebook        | 32        | 0.49%   |
| HP OMEN            | 31        | 0.48%   |
| ASUS TUF           | 30        | 0.46%   |
| MSI Modern         | 24        | 0.37%   |
| Fujitsu LIFEBOOK   | 22        | 0.34%   |
| Dell G5            | 22        | 0.34%   |
| Apple MacBookPro9  | 20        | 0.31%   |
| Acer Predator      | 19        | 0.29%   |
| HP 250             | 17        | 0.26%   |
| Razer Blade        | 16        | 0.25%   |
| Apple MacBookPro8  | 15        | 0.23%   |
| Dell G3            | 14        | 0.22%   |
| Apple MacBookPro12 | 14        | 0.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 887       | 13.64%  |
| 2019    | 852       | 13.1%   |
| 2021    | 769       | 11.82%  |
| 2018    | 696       | 10.7%   |
| 2017    | 502       | 7.72%   |
| 2015    | 400       | 6.15%   |
| 2016    | 383       | 5.89%   |
| 2012    | 369       | 5.67%   |
| 2013    | 353       | 5.43%   |
| 2022    | 331       | 5.09%   |
| 2014    | 319       | 4.9%    |
| 2011    | 288       | 4.43%   |
| 2010    | 141       | 2.17%   |
| 2008    | 86        | 1.32%   |
| 2009    | 67        | 1.03%   |
| 2023    | 31        | 0.48%   |
| 2007    | 19        | 0.29%   |
| 2006    | 6         | 0.09%   |
| Unknown | 5         | 0.08%   |
| 2003    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 6505      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 5235      | 79.1%   |
| Enabled  | 1383      | 20.9%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 6453      | 99.2%   |
| Yes  | 52        | 0.8%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1930      | 29.24%  |
| 16.01-24.0  | 1590      | 24.09%  |
| 8.01-16.0   | 1307      | 19.8%   |
| 32.01-64.0  | 731       | 11.08%  |
| 3.01-4.0    | 642       | 9.73%   |
| 24.01-32.0  | 124       | 1.88%   |
| 1.01-2.0    | 124       | 1.88%   |
| 64.01-256.0 | 114       | 1.73%   |
| 2.01-3.0    | 25        | 0.38%   |
| 0.51-1.0    | 11        | 0.17%   |
| Unknown     | 2         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 2033      | 27.79%  |
| 4.01-8.0   | 2006      | 27.42%  |
| 3.01-4.0   | 1625      | 22.21%  |
| 1.01-2.0   | 962       | 13.15%  |
| 8.01-16.0  | 526       | 7.19%   |
| 0.51-1.0   | 78        | 1.07%   |
| 16.01-24.0 | 60        | 0.82%   |
| 24.01-32.0 | 14        | 0.19%   |
| 32.01-64.0 | 7         | 0.1%    |
| 0.01-0.5   | 3         | 0.04%   |
| Unknown    | 2         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 4777      | 72.21%  |
| 2      | 1572      | 23.76%  |
| 3      | 186       | 2.81%   |
| 0      | 36        | 0.54%   |
| 4      | 30        | 0.45%   |
| 5      | 7         | 0.11%   |
| 6      | 6         | 0.09%   |
| 7      | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 5181      | 79.31%  |
| Yes       | 1352      | 20.69%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4827      | 73.8%   |
| No        | 1714      | 26.2%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 6379      | 97.99%  |
| No        | 131       | 2.01%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 5481      | 83.22%  |
| No        | 1105      | 16.78%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 1099      | 16.71%  |
| Brazil       | 484       | 7.36%   |
| Germany      | 452       | 6.87%   |
| Russia       | 420       | 6.39%   |
| Italy        | 309       | 4.7%    |
| France       | 274       | 4.17%   |
| India        | 249       | 3.79%   |
| UK           | 222       | 3.38%   |
| Poland       | 199       | 3.03%   |
| Netherlands  | 194       | 2.95%   |
| Canada       | 178       | 2.71%   |
| Spain        | 156       | 2.37%   |
| Mexico       | 121       | 1.84%   |
| Czechia      | 110       | 1.67%   |
| Turkey       | 107       | 1.63%   |
| Australia    | 100       | 1.52%   |
| Austria      | 86        | 1.31%   |
| Sweden       | 84        | 1.28%   |
| Switzerland  | 73        | 1.11%   |
| Portugal     | 65        | 0.99%   |
| Ukraine      | 63        | 0.96%   |
| Belgium      | 61        | 0.93%   |
| Argentina    | 61        | 0.93%   |
| Chile        | 58        | 0.88%   |
| Romania      | 56        | 0.85%   |
| Indonesia    | 56        | 0.85%   |
| Hungary      | 56        | 0.85%   |
| Finland      | 56        | 0.85%   |
| Norway       | 54        | 0.82%   |
| Denmark      | 46        | 0.7%    |
| China        | 41        | 0.62%   |
| Colombia     | 39        | 0.59%   |
| Iran         | 38        | 0.58%   |
| Bulgaria     | 35        | 0.53%   |
| Israel       | 34        | 0.52%   |
| Greece       | 33        | 0.5%    |
| Slovakia     | 31        | 0.47%   |
| Belarus      | 31        | 0.47%   |
| South Africa | 28        | 0.43%   |
| Japan        | 28        | 0.43%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 140       | 1.99%   |
| Sao Paulo         | 68        | 0.97%   |
| St Petersburg     | 59        | 0.84%   |
| Vienna            | 54        | 0.77%   |
| Paris             | 53        | 0.75%   |
| Berlin            | 53        | 0.75%   |
| Amsterdam         | 48        | 0.68%   |
| Istanbul          | 47        | 0.67%   |
| Prague            | 46        | 0.65%   |
| Milan             | 46        | 0.65%   |
| Warsaw            | 43        | 0.61%   |
| Madrid            | 40        | 0.57%   |
| Bengaluru         | 36        | 0.51%   |
| Helsinki          | 34        | 0.48%   |
| Munich            | 33        | 0.47%   |
| Oslo              | 32        | 0.46%   |
| Mexico City       | 32        | 0.46%   |
| Sydney            | 29        | 0.41%   |
| Melbourne         | 29        | 0.41%   |
| Frankfurt am Main | 28        | 0.4%    |
| Delft             | 27        | 0.38%   |
| Rio de Janeiro    | 26        | 0.37%   |
| Budapest          | 26        | 0.37%   |
| Santiago          | 25        | 0.36%   |
| Zurich            | 24        | 0.34%   |
| Lisbon            | 24        | 0.34%   |
| Kyiv              | 24        | 0.34%   |
| Bucharest         | 24        | 0.34%   |
| Sofia             | 23        | 0.33%   |
| Hamburg           | 23        | 0.33%   |
| Jakarta           | 22        | 0.31%   |
| Brisbane          | 22        | 0.31%   |
| Tehran            | 21        | 0.3%    |
| Montreal          | 21        | 0.3%    |
| Brasília         | 21        | 0.3%    |
| Singapore         | 20        | 0.28%   |
| Rome              | 20        | 0.28%   |
| Pune              | 20        | 0.28%   |
| Portland          | 20        | 0.28%   |
| Chicago           | 20        | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 1741      | 2512   | 21.08%  |
| WDC                         | 818       | 1038   | 9.9%    |
| SanDisk                     | 611       | 788    | 7.4%    |
| Seagate                     | 604       | 796    | 7.31%   |
| Toshiba                     | 566       | 705    | 6.85%   |
| SK hynix                    | 498       | 614    | 6.03%   |
| Unknown                     | 438       | 574    | 5.3%    |
| Kingston                    | 406       | 497    | 4.92%   |
| Intel                       | 343       | 487    | 4.15%   |
| Micron Technology           | 267       | 352    | 3.23%   |
| Crucial                     | 246       | 321    | 2.98%   |
| HGST                        | 166       | 233    | 2.01%   |
| KIOXIA                      | 126       | 174    | 1.53%   |
| A-DATA Technology           | 123       | 142    | 1.49%   |
| Apple                       | 95        | 131    | 1.15%   |
| Hitachi                     | 80        | 92     | 0.97%   |
| LITEON                      | 75        | 81     | 0.91%   |
| Phison                      | 62        | 69     | 0.75%   |
| China                       | 59        | 67     | 0.71%   |
| Silicon Motion              | 46        | 63     | 0.56%   |
| Transcend                   | 38        | 55     | 0.46%   |
| PNY                         | 37        | 49     | 0.45%   |
| SPCC                        | 34        | 44     | 0.41%   |
| Micron/Crucial Technology   | 33        | 36     | 0.4%    |
| ADATA Technology            | 32        | 34     | 0.39%   |
| LITEONIT                    | 27        | 33     | 0.33%   |
| Phison Electronics          | 25        | 27     | 0.3%    |
| Lenovo                      | 22        | 25     | 0.27%   |
| Corsair                     | 22        | 27     | 0.27%   |
| Unknown                     | 22        | 26     | 0.27%   |
| Kingston Technology Company | 19        | 22     | 0.23%   |
| JMicron Technology          | 19        | 23     | 0.23%   |
| XPG                         | 18        | 27     | 0.22%   |
| Realtek Semiconductor       | 18        | 23     | 0.22%   |
| UMIS                        | 17        | 20     | 0.21%   |
| Team                        | 17        | 20     | 0.21%   |
| Patriot                     | 17        | 23     | 0.21%   |
| Intenso                     | 16        | 19     | 0.19%   |
| Gigabyte Technology         | 16        | 20     | 0.19%   |
| OCZ                         | 15        | 17     | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 129       | 1.49%   |
| Samsung NVMe SSD Drive 512GB                        | 113       | 1.3%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 107       | 1.23%   |
| Samsung NVMe SSD Drive 256GB                        | 83        | 0.96%   |
| SanDisk NVMe SSD Drive 512GB                        | 81        | 0.93%   |
| Kingston SA400S37240G 240GB SSD                     | 79        | 0.91%   |
| Toshiba MQ04ABF100 1TB                              | 72        | 0.83%   |
| Unknown MMC Card  32GB                              | 71        | 0.82%   |
| HGST HTS721010A9E630 1TB                            | 71        | 0.82%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 69        | 0.8%    |
| Unknown MMC Card  64GB                              | 62        | 0.71%   |
| Toshiba MQ01ABD100 1TB                              | 58        | 0.67%   |
| Samsung SSD 860 EVO 500GB                           | 55        | 0.63%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 55        | 0.63%   |
| Kingston SA400S37480G 480GB SSD                     | 53        | 0.61%   |
| SK hynix NVMe SSD Drive 512GB                       | 51        | 0.59%   |
| Samsung NVMe SSD Drive 1024GB                       | 51        | 0.59%   |
| SanDisk NVMe SSD Drive 256GB                        | 48        | 0.55%   |
| Intel NVMe SSD Drive 512GB                          | 46        | 0.53%   |
| Samsung NVMe SSD Drive 1TB                          | 43        | 0.5%    |
| Samsung SSD 850 EVO 250GB                           | 41        | 0.47%   |
| Unknown MMC Card  128GB                             | 40        | 0.46%   |
| Samsung SSD 850 EVO 500GB                           | 39        | 0.45%   |
| Toshiba NVMe SSD Drive 512GB                        | 38        | 0.44%   |
| Seagate ST500LT012-1DG142 500GB                     | 35        | 0.4%    |
| Crucial CT240BX500SSD1 240GB                        | 35        | 0.4%    |
| Seagate Expansion 1TB                               | 34        | 0.39%   |
| Toshiba NVMe SSD Drive 256GB                        | 33        | 0.38%   |
| Samsung SSD 860 EVO 250GB                           | 33        | 0.38%   |
| Samsung NVMe SSD Drive 500GB                        | 33        | 0.38%   |
| WDC WD10SPZX-21Z10T0 1TB                            | 31        | 0.36%   |
| Samsung SSD 860 EVO 1TB                             | 31        | 0.36%   |
| Crucial CT1000MX500SSD1 1TB                         | 31        | 0.36%   |
| SK hynix NVMe SSD Drive 256GB                       | 30        | 0.35%   |
| Samsung MZVLB512HBJQ-000L7 512GB                    | 30        | 0.35%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 256GB    | 29        | 0.33%   |
| Samsung MZVLB1T0HBLR-000L7 1TB                      | 29        | 0.33%   |
| Samsung MZALQ512HALU-000L2 512GB                    | 29        | 0.33%   |
| HGST HTS541010A9E680 1TB                            | 29        | 0.33%   |
| Samsung SSD 970 EVO Plus 1TB                        | 28        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 582       | 764    | 36.6%   |
| WDC                 | 411       | 531    | 25.85%  |
| Toshiba             | 274       | 334    | 17.23%  |
| HGST                | 166       | 233    | 10.44%  |
| Hitachi             | 80        | 92     | 5.03%   |
| Unknown             | 20        | 29     | 1.26%   |
| Samsung Electronics | 14        | 17     | 0.88%   |
| Fujitsu             | 11        | 11     | 0.69%   |
| Apple               | 10        | 11     | 0.63%   |
| External            | 4         | 6      | 0.25%   |
| USB3.0              | 2         | 2      | 0.13%   |
| LIO-ORG             | 2         | 8      | 0.13%   |
| LaCie               | 2         | 3      | 0.13%   |
| HGST HTS            | 2         | 2      | 0.13%   |
| ASMT                | 2         | 3      | 0.13%   |
| SSK                 | 1         | 1      | 0.06%   |
| SAGE                | 1         | 1      | 0.06%   |
| Phison              | 1         | 2      | 0.06%   |
| JMicron Technology  | 1         | 1      | 0.06%   |
| Intenso             | 1         | 1      | 0.06%   |
| Inateck             | 1         | 1      | 0.06%   |
| IB-AC703            | 1         | 1      | 0.06%   |
| ASMedia             | 1         | 1      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 625       | 899    | 24.5%   |
| Kingston            | 295       | 360    | 11.56%  |
| SanDisk             | 264       | 360    | 10.35%  |
| Crucial             | 218       | 291    | 8.55%   |
| WDC                 | 133       | 171    | 5.21%   |
| Intel               | 91        | 143    | 3.57%   |
| Micron Technology   | 82        | 101    | 3.21%   |
| A-DATA Technology   | 80        | 95     | 3.14%   |
| SK hynix            | 67        | 81     | 2.63%   |
| Apple               | 63        | 73     | 2.47%   |
| LITEON              | 60        | 66     | 2.35%   |
| China               | 58        | 66     | 2.27%   |
| Toshiba             | 56        | 72     | 2.2%    |
| PNY                 | 35        | 46     | 1.37%   |
| Transcend           | 32        | 45     | 1.25%   |
| SPCC                | 27        | 37     | 1.06%   |
| LITEONIT            | 27        | 33     | 1.06%   |
| Patriot             | 15        | 20     | 0.59%   |
| OCZ                 | 14        | 16     | 0.55%   |
| KingSpec            | 14        | 16     | 0.55%   |
| Corsair             | 14        | 16     | 0.55%   |
| Netac               | 13        | 17     | 0.51%   |
| Intenso             | 13        | 15     | 0.51%   |
| Gigabyte Technology | 13        | 17     | 0.51%   |
| SABRENT             | 12        | 12     | 0.47%   |
| JMicron Technology  | 12        | 16     | 0.47%   |
| Team                | 11        | 14     | 0.43%   |
| Lexar               | 11        | 19     | 0.43%   |
| Goodram             | 11        | 19     | 0.43%   |
| Seagate             | 9         | 9      | 0.35%   |
| Apacer              | 9         | 11     | 0.35%   |
| Hewlett-Packard     | 8         | 8      | 0.31%   |
| Unknown             | 6         | 6      | 0.24%   |
| Plextor             | 6         | 8      | 0.24%   |
| TO Exter            | 5         | 5      | 0.2%    |
| Ramsta              | 5         | 6      | 0.2%    |
| FORESEE             | 5         | 5      | 0.2%    |
| Mushkin             | 4         | 12     | 0.16%   |
| Leven               | 4         | 4      | 0.16%   |
| Dogfish             | 4         | 4      | 0.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 3387      | 4756   | 43.48%  |
| SSD     | 2353      | 3357   | 30.21%  |
| HDD     | 1535      | 2055   | 19.71%  |
| MMC     | 418       | 555    | 5.37%   |
| Unknown | 96        | 108    | 1.23%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3386      | 5161   | 45.38%  |
| NVMe | 3385      | 4752   | 45.37%  |
| MMC  | 418       | 555    | 5.6%    |
| SAS  | 272       | 363    | 3.65%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2402      | 3401   | 61.89%  |
| 0.51-1.0   | 1309      | 1771   | 33.73%  |
| 1.01-2.0   | 130       | 196    | 3.35%   |
| 4.01-10.0  | 14        | 15     | 0.36%   |
| 10.01-20.0 | 13        | 13     | 0.33%   |
| 3.01-4.0   | 12        | 14     | 0.31%   |
| 0          | 1         | 2      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 1503      | 22.02%  |
| 501-1000       | 1438      | 21.06%  |
| 101-250        | 1247      | 18.27%  |
| 1001-2000      | 729       | 10.68%  |
| 1-20           | 727       | 10.65%  |
| Unknown        | 488       | 7.15%   |
| 51-100         | 273       | 4%      |
| 21-50          | 158       | 2.31%   |
| More than 3000 | 137       | 2.01%   |
| 2001-3000      | 127       | 1.86%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 2145      | 29.92%  |
| 21-50          | 1246      | 17.38%  |
| 101-250        | 1120      | 15.63%  |
| 51-100         | 944       | 13.17%  |
| 251-500        | 676       | 9.43%   |
| Unknown        | 488       | 6.81%   |
| 501-1000       | 390       | 5.44%   |
| 1001-2000      | 124       | 1.73%   |
| More than 3000 | 19        | 0.27%   |
| 2001-3000      | 15        | 0.21%   |
| 0              | 1         | 0.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB                | 11        | 11     | 3.83%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 9         | 19     | 3.14%   |
| Seagate ST1000LM035-1RK172 1TB                 | 7         | 7      | 2.44%   |
| Toshiba MQ01ABD100 1TB                         | 6         | 6      | 2.09%   |
| Seagate ST9500325AS 500GB                      | 6         | 8      | 2.09%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 6         | 6      | 2.09%   |
| HGST HTS721010A9E630 1TB                       | 6         | 8      | 2.09%   |
| HGST HTS545050A7E680 500GB                     | 6         | 6      | 2.09%   |
| HGST HTS541010A9E680 1TB                       | 6         | 6      | 2.09%   |
| Toshiba MQ01ABD075 752GB                       | 4         | 4      | 1.39%   |
| Hitachi HTS547575A9E384 752GB                  | 4         | 6      | 1.39%   |
| SK hynix SC308 SATA 128GB SSD                  | 3         | 3      | 1.05%   |
| Seagate ST9320325AS 320GB                      | 3         | 3      | 1.05%   |
| Seagate ST500LM021-1KJ152 500GB                | 3         | 4      | 1.05%   |
| Samsung Electronics SSD 980 1TB                | 3         | 3      | 1.05%   |
| Samsung Electronics SSD 870 EVO 500GB          | 3         | 6      | 1.05%   |
| Hitachi HTS545050B9A300 500GB                  | 3         | 3      | 1.05%   |
| HGST HTS725050A7E630 500GB                     | 3         | 3      | 1.05%   |
| Crucial CT1000P1SSD8 1TB                       | 3         | 3      | 1.05%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD               | 2         | 2      | 0.7%    |
| WDC WD10SPZX-24Z10 1TB                         | 2         | 2      | 0.7%    |
| Toshiba MQ01ACF050 500GB                       | 2         | 2      | 0.7%    |
| Toshiba MQ01ABF050 500GB                       | 2         | 2      | 0.7%    |
| Toshiba MQ01ABD050V 500GB                      | 2         | 2      | 0.7%    |
| Toshiba MK5061GSY 500GB                        | 2         | 2      | 0.7%    |
| Toshiba MK3275GSX 320GB                        | 2         | 3      | 0.7%    |
| SPCC Solid State Disk 256GB                    | 2         | 2      | 0.7%    |
| SK hynix HFS256G39TND-N210A 256GB SSD          | 2         | 2      | 0.7%    |
| SK hynix HFS128G39TND-N210A 128GB SSD          | 2         | 2      | 0.7%    |
| Seagate ST9500420AS 500GB                      | 2         | 3      | 0.7%    |
| Seagate ST500LM012 HN-M500MBB 500GB            | 2         | 2      | 0.7%    |
| Seagate ST500LM000-SSHD-8GB                    | 2         | 3      | 0.7%    |
| Seagate ST500LM000-1EJ162 500GB                | 2         | 2      | 0.7%    |
| Seagate ST2000LM003 HN-M201RAD 2TB             | 2         | 2      | 0.7%    |
| Seagate ST1000LM014-1EJ164 1TB                 | 2         | 2      | 0.7%    |
| SanDisk SSD PLUS 240GB                         | 2         | 2      | 0.7%    |
| SanDisk SD6PP4M-256G-1006 256GB SSD            | 2         | 2      | 0.7%    |
| LITEON CV8-8E128-HP 128GB SSD                  | 2         | 2      | 0.7%    |
| Kingston SV300S37A480G 480GB SSD               | 2         | 2      | 0.7%    |
| Intel SSDSC2BF180A5L 180GB                     | 2         | 2      | 0.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 61        | 78     | 21.33%  |
| Toshiba             | 33        | 34     | 11.54%  |
| WDC                 | 29        | 32     | 10.14%  |
| Samsung Electronics | 25        | 30     | 8.74%   |
| HGST                | 25        | 27     | 8.74%   |
| Hitachi             | 19        | 22     | 6.64%   |
| Micron Technology   | 14        | 17     | 4.9%    |
| SK hynix            | 12        | 13     | 4.2%    |
| Intel               | 12        | 23     | 4.2%    |
| Crucial             | 11        | 18     | 3.85%   |
| SanDisk             | 10        | 12     | 3.5%    |
| Kingston            | 7         | 7      | 2.45%   |
| A-DATA Technology   | 5         | 5      | 1.75%   |
| LITEON              | 4         | 4      | 1.4%    |
| Fujitsu             | 3         | 3      | 1.05%   |
| SPCC                | 2         | 2      | 0.7%    |
| LITEONIT            | 2         | 3      | 0.7%    |
| walram              | 1         | 1      | 0.35%   |
| Union Memory        | 1         | 1      | 0.35%   |
| Teclast             | 1         | 1      | 0.35%   |
| SSD                 | 1         | 1      | 0.35%   |
| PNY                 | 1         | 1      | 0.35%   |
| Plextor             | 1         | 1      | 0.35%   |
| Origin              | 1         | 1      | 0.35%   |
| OCZ-VERTEX3         | 1         | 1      | 0.35%   |
| Lenovo              | 1         | 2      | 0.35%   |
| HGST HTS            | 1         | 1      | 0.35%   |
| China               | 1         | 1      | 0.35%   |
| Unknown             | 1         | 1      | 0.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 61        | 78     | 35.88%  |
| Toshiba             | 32        | 33     | 18.82%  |
| WDC                 | 26        | 29     | 15.29%  |
| HGST                | 25        | 27     | 14.71%  |
| Hitachi             | 19        | 22     | 11.18%  |
| Samsung Electronics | 3         | 3      | 1.76%   |
| Fujitsu             | 3         | 3      | 1.76%   |
| HGST HTS            | 1         | 1      | 0.59%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 169       | 196    | 59.51%  |
| SSD  | 93        | 122    | 32.75%  |
| NVMe | 22        | 25     | 7.75%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC PC SN520 SDAPMUW-512G-1001 512GB             | 1         | 1      | 14.29%  |
| Toshiba THNSN5512GPUK NVMe 512GB                 | 1         | 1      | 14.29%  |
| Seagate ST1000LM035-1RK172 1TB                   | 1         | 1      | 14.29%  |
| Samsung Electronics SSD 980 500GB                | 1         | 1      | 14.29%  |
| Samsung Electronics SSD 980 1TB                  | 1         | 1      | 14.29%  |
| Samsung Electronics MZNTY128HDHP-00000 128GB SSD | 1         | 1      | 14.29%  |
| HGST HTS721010A9E630 1TB                         | 1         | 1      | 14.29%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 42.86%  |
| WDC                 | 1         | 1      | 14.29%  |
| Toshiba             | 1         | 1      | 14.29%  |
| Seagate             | 1         | 1      | 14.29%  |
| HGST                | 1         | 1      | 14.29%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 3751      | 6237   | 53.7%   |
| Works    | 2950      | 4244   | 42.23%  |
| Malfunc  | 277       | 343    | 3.97%   |
| Failed   | 7         | 7      | 0.1%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 3992      | 49.23%  |
| Samsung Electronics                     | 1193      | 14.71%  |
| AMD                                     | 677       | 8.35%   |
| SanDisk                                 | 599       | 7.39%   |
| SK hynix                                | 417       | 5.14%   |
| Toshiba America Info Systems            | 242       | 2.98%   |
| Micron Technology                       | 187       | 2.31%   |
| Kingston Technology Company             | 130       | 1.6%    |
| KIOXIA                                  | 126       | 1.55%   |
| Phison Electronics                      | 98        | 1.21%   |
| ADATA Technology                        | 85        | 1.05%   |
| Silicon Motion                          | 64        | 0.79%   |
| Micron/Crucial Technology               | 58        | 0.72%   |
| Union Memory (Shenzhen)                 | 34        | 0.42%   |
| Solid State Storage Technology          | 28        | 0.35%   |
| Lite-On Technology                      | 28        | 0.35%   |
| Realtek Semiconductor                   | 25        | 0.31%   |
| Nvidia                                  | 25        | 0.31%   |
| Lenovo                                  | 21        | 0.26%   |
| Apple                                   | 19        | 0.23%   |
| Seagate Technology                      | 10        | 0.12%   |
| Yangtze Memory Technologies             | 9         | 0.11%   |
| Shenzhen Longsys Electronics            | 8         | 0.1%    |
| MAXIO Technology (Hangzhou)             | 6         | 0.07%   |
| Marvell Technology Group                | 6         | 0.07%   |
| JMicron Technology                      | 5         | 0.06%   |
| Biwin Storage Technology                | 3         | 0.04%   |
| Silicon Integrated Systems [SiS]        | 2         | 0.02%   |
| ULi Electronics                         | 1         | 0.01%   |
| Transcend                               | 1         | 0.01%   |
| Solidigm                                | 1         | 0.01%   |
| Shenzhen Unionmemory Information System | 1         | 0.01%   |
| OCZ Technology Group                    | 1         | 0.01%   |
| Netac Technology                        | 1         | 0.01%   |
| Lite-On IT Corp. / Plextor              | 1         | 0.01%   |
| INNOGRIT                                | 1         | 0.01%   |
| Enmotus                                 | 1         | 0.01%   |
| Beijing Starblaze Technology            | 1         | 0.01%   |
| ASMedia Technology                      | 1         | 0.01%   |
| Unknown                                 | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 645       | 7.61%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 642       | 7.57%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 600       | 7.08%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 396       | 4.67%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 383       | 4.52%   |
| Intel Volume Management Device NVMe RAID Controller                            | 269       | 3.17%   |
| Samsung NVMe SSD Controller 980                                                | 263       | 3.1%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 255       | 3.01%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 236       | 2.78%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 214       | 2.52%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 190       | 2.24%   |
| Micron NVMe Storage Controller                                                 | 182       | 2.15%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 180       | 2.12%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 170       | 2%      |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 161       | 1.9%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 157       | 1.85%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 156       | 1.84%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 114       | 1.34%   |
| Intel Comet Lake SATA AHCI Controller                                          | 113       | 1.33%   |
| Intel Tiger Lake-LP SATA Controller                                            | 112       | 1.32%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 111       | 1.31%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 107       | 1.26%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 95        | 1.12%   |
| Intel SSD 660P Series                                                          | 94        | 1.11%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 91        | 1.07%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 74        | 0.87%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 73        | 0.86%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 72        | 0.85%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 71        | 0.84%   |
| SK hynix Non-Volatile memory controller                                        | 69        | 0.81%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 69        | 0.81%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 68        | 0.8%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 67        | 0.79%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 61        | 0.72%   |
| SK hynix BC511                                                                 | 60        | 0.71%   |
| SanDisk Non-Volatile memory controller                                         | 58        | 0.68%   |
| Intel Non-Volatile memory controller                                           | 56        | 0.66%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 56        | 0.66%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 53        | 0.63%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 53        | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 3979      | 48.74%  |
| NVMe | 3390      | 41.53%  |
| RAID | 682       | 8.35%   |
| IDE  | 112       | 1.37%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 5244      | 80.61%  |
| AMD          | 1255      | 19.29%  |
| ARM          | 3         | 0.05%   |
| Unknown      | 2         | 0.03%   |
| CentaurHauls | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 162       | 2.49%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 154       | 2.37%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 136       | 2.09%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 134       | 2.06%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 114       | 1.75%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 113       | 1.74%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 107       | 1.64%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 105       | 1.61%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 104       | 1.6%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 104       | 1.6%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 99        | 1.52%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 96        | 1.48%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 93        | 1.43%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 90        | 1.38%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 85        | 1.31%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 72        | 1.11%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 71        | 1.09%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 71        | 1.09%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 69        | 1.06%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 67        | 1.03%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 65        | 1%      |
| Intel Core i5-3320M CPU @ 2.60GHz             | 64        | 0.98%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 59        | 0.91%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 58        | 0.89%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 56        | 0.86%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 55        | 0.85%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 49        | 0.75%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 48        | 0.74%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 47        | 0.72%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 46        | 0.71%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 45        | 0.69%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 45        | 0.69%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 44        | 0.68%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 43        | 0.66%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 41        | 0.63%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 40        | 0.61%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 39        | 0.6%    |
| Intel Core i5-8350U CPU @ 1.70GHz             | 37        | 0.57%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 37        | 0.57%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 37        | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 1937      | 29.77%  |
| Intel Core i5                  | 1617      | 24.85%  |
| Other                          | 718       | 11.04%  |
| AMD Ryzen 5                    | 398       | 6.12%   |
| Intel Core i3                  | 390       | 5.99%   |
| AMD Ryzen 7                    | 356       | 5.47%   |
| Intel Celeron                  | 161       | 2.47%   |
| Intel Atom                     | 105       | 1.61%   |
| Intel Core 2 Duo               | 104       | 1.6%    |
| AMD Ryzen 9                    | 94        | 1.44%   |
| AMD Ryzen 7 PRO                | 92        | 1.41%   |
| Intel Pentium                  | 75        | 1.15%   |
| Intel Core i9                  | 58        | 0.89%   |
| AMD Ryzen 3                    | 57        | 0.88%   |
| AMD Ryzen 5 PRO                | 51        | 0.78%   |
| AMD A6                         | 37        | 0.57%   |
| AMD A10                        | 34        | 0.52%   |
| AMD A8                         | 27        | 0.42%   |
| Intel Pentium Silver           | 24        | 0.37%   |
| AMD A4                         | 20        | 0.31%   |
| Intel Xeon                     | 16        | 0.25%   |
| Intel Pentium Dual-Core        | 15        | 0.23%   |
| AMD E1                         | 11        | 0.17%   |
| AMD A12                        | 11        | 0.17%   |
| Intel Core m3                  | 9         | 0.14%   |
| AMD Athlon                     | 9         | 0.14%   |
| Intel Pentium Dual             | 8         | 0.12%   |
| AMD E                          | 8         | 0.12%   |
| Intel Core m5                  | 7         | 0.11%   |
| Intel Genuine                  | 6         | 0.09%   |
| Intel Core m7                  | 5         | 0.08%   |
| Intel Core M                   | 5         | 0.08%   |
| AMD PRO A10                    | 4         | 0.06%   |
| AMD Phenom II                  | 4         | 0.06%   |
| AMD E2                         | 4         | 0.06%   |
| AMD Athlon II                  | 4         | 0.06%   |
| Intel Core 2                   | 3         | 0.05%   |
| AMD Turion X2 Dual-Core Mobile | 3         | 0.05%   |
| Intel Celeron Dual-Core        | 2         | 0.03%   |
| AMD Turion 64 X2 Mobile        | 2         | 0.03%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 4       | 2662      | 40.91%  |
| 2       | 2362      | 36.3%   |
| 6       | 656       | 10.08%  |
| 8       | 620       | 9.53%   |
| 12      | 69        | 1.06%   |
| 14      | 64        | 0.98%   |
| 10      | 43        | 0.66%   |
| 1       | 20        | 0.31%   |
| 16      | 7         | 0.11%   |
| 3       | 2         | 0.03%   |
| 5       | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 6504      | 99.97%  |
| 2       | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 5710      | 87.66%  |
| 1       | 803       | 12.33%  |
| Unknown | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 6368      | 97.58%  |
| Unknown        | 151       | 2.31%   |
| 32-bit         | 4         | 0.06%   |
| 64-bit         | 3         | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 913       | 13.65%  |
| 0x806ec    | 397       | 5.94%   |
| 0x806ea    | 381       | 5.7%    |
| 0x306a9    | 355       | 5.31%   |
| 0x806c1    | 348       | 5.2%    |
| 0x206a7    | 277       | 4.14%   |
| 0x906ea    | 272       | 4.07%   |
| 0x406e3    | 270       | 4.04%   |
| 0x806e9    | 269       | 4.02%   |
| 0x40651    | 220       | 3.29%   |
| 0x306d4    | 214       | 3.2%    |
| 0x0a50000c | 184       | 2.75%   |
| 0x306c3    | 168       | 2.51%   |
| 0xa0652    | 164       | 2.45%   |
| 0x08600106 | 126       | 1.88%   |
| 0x906e9    | 118       | 1.76%   |
| 0x08108109 | 118       | 1.76%   |
| 0x08108102 | 115       | 1.72%   |
| 0x506e3    | 111       | 1.66%   |
| 0x706e5    | 104       | 1.55%   |
| 0x08608103 | 89        | 1.33%   |
| 0x906a3    | 88        | 1.32%   |
| 0x20655    | 81        | 1.21%   |
| 0x806eb    | 75        | 1.12%   |
| 0x30678    | 75        | 1.12%   |
| 0x08600104 | 72        | 1.08%   |
| 0x1067a    | 70        | 1.05%   |
| 0x806d1    | 61        | 0.91%   |
| 0x906ed    | 56        | 0.84%   |
| 0x08600103 | 50        | 0.75%   |
| 0x0a404102 | 49        | 0.73%   |
| 0x406c4    | 42        | 0.63%   |
| 0x0810100b | 39        | 0.58%   |
| 0x706a8    | 34        | 0.51%   |
| 0x0a404101 | 31        | 0.46%   |
| 0x08608102 | 31        | 0.46%   |
| 0x406c3    | 30        | 0.45%   |
| 0x906a4    | 29        | 0.43%   |
| 0x506c9    | 28        | 0.42%   |
| 0x20652    | 28        | 0.42%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 1785      | 27.42%  |
| Haswell          | 465       | 7.14%   |
| TigerLake        | 441       | 6.77%   |
| Skylake          | 431       | 6.62%   |
| IvyBridge        | 400       | 6.14%   |
| SandyBridge      | 312       | 4.79%   |
| Zen 2            | 294       | 4.52%   |
| Zen+             | 241       | 3.7%    |
| Zen 3            | 239       | 3.67%   |
| Unknown          | 238       | 3.66%   |
| Broadwell        | 232       | 3.56%   |
| CometLake        | 212       | 3.26%   |
| IceLake          | 193       | 2.96%   |
| Silvermont       | 183       | 2.81%   |
| Alderlake Hybrid | 176       | 2.7%    |
| Westmere         | 122       | 1.87%   |
| Penryn           | 107       | 1.64%   |
| Zen              | 72        | 1.11%   |
| Goldmont plus    | 72        | 1.11%   |
| Excavator        | 62        | 0.95%   |
| Goldmont         | 34        | 0.52%   |
| Puma             | 31        | 0.48%   |
| Core             | 31        | 0.48%   |
| Piledriver       | 29        | 0.45%   |
| Jaguar           | 19        | 0.29%   |
| Nehalem          | 17        | 0.26%   |
| Bobcat           | 15        | 0.23%   |
| Tremont          | 12        | 0.18%   |
| K10              | 11        | 0.17%   |
| K10 Llano        | 9         | 0.14%   |
| Steamroller      | 7         | 0.11%   |
| K8 & K10 hybrid  | 5         | 0.08%   |
| Bonnell          | 5         | 0.08%   |
| K8 Hammer        | 4         | 0.06%   |
| P6               | 3         | 0.05%   |
| NetBurst         | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 4940      | 57.59%  |
| Nvidia                           | 2068      | 24.11%  |
| AMD                              | 1568      | 18.28%  |
| Zhaoxin                          | 1         | 0.01%   |
| Silicon Integrated Systems [SiS] | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 420       | 4.81%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 403       | 4.61%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 369       | 4.23%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 319       | 3.65%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 288       | 3.3%    |
| Intel HD Graphics 620                                                                    | 287       | 3.29%   |
| AMD Renoir                                                                               | 285       | 3.26%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 275       | 3.15%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 262       | 3%      |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 242       | 2.77%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 242       | 2.77%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 237       | 2.71%   |
| Intel HD Graphics 5500                                                                   | 202       | 2.31%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 197       | 2.26%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 181       | 2.07%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 178       | 2.04%   |
| AMD Lucienne                                                                             | 126       | 1.44%   |
| Intel HD Graphics 630                                                                    | 122       | 1.4%    |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 122       | 1.4%    |
| Intel HD Graphics 530                                                                    | 107       | 1.23%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 106       | 1.21%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 101       | 1.16%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 96        | 1.1%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 92        | 1.05%   |
| Intel Core Processor Integrated Graphics Controller                                      | 92        | 1.05%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 85        | 0.97%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 83        | 0.95%   |
| AMD Rembrandt [Radeon 680M]                                                              | 83        | 0.95%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 82        | 0.94%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 79        | 0.9%    |
| Nvidia GP108M [GeForce MX150]                                                            | 71        | 0.81%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 67        | 0.77%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 67        | 0.77%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 64        | 0.73%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 58        | 0.66%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 58        | 0.66%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 54        | 0.62%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 49        | 0.56%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 46        | 0.53%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 46        | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 3090      | 47.33%  |
| Intel + Nvidia     | 1596      | 24.44%  |
| 1 x AMD            | 987       | 15.12%  |
| 1 x Nvidia         | 255       | 3.91%   |
| Intel + AMD        | 247       | 3.78%   |
| AMD + Nvidia       | 219       | 3.35%   |
| 2 x AMD            | 116       | 1.78%   |
| Other              | 7         | 0.11%   |
| 2 x Intel          | 6         | 0.09%   |
| 2 x Nvidia         | 2         | 0.03%   |
| Intel + 2 x Nvidia | 2         | 0.03%   |
| 1 x Zhaoxin        | 1         | 0.02%   |
| 1 x SiS            | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 5584      | 84.8%   |
| Proprietary | 908       | 13.79%  |
| Unknown     | 93        | 1.41%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 4048      | 60.97%  |
| 1.01-2.0   | 883       | 13.3%   |
| 0.01-0.5   | 685       | 10.32%  |
| 3.01-4.0   | 445       | 6.7%    |
| 0.51-1.0   | 358       | 5.39%   |
| 5.01-6.0   | 95        | 1.43%   |
| 7.01-8.0   | 79        | 1.19%   |
| 2.01-3.0   | 24        | 0.36%   |
| 8.01-16.0  | 22        | 0.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 1385      | 17.3%   |
| BOE                     | 1192      | 14.89%  |
| Chimei Innolux          | 1081      | 13.51%  |
| LG Display              | 1046      | 13.07%  |
| Samsung Electronics     | 610       | 7.62%   |
| Dell                    | 376       | 4.7%    |
| Sharp                   | 349       | 4.36%   |
| Goldstar                | 234       | 2.92%   |
| Lenovo                  | 170       | 2.12%   |
| Apple                   | 169       | 2.11%   |
| PANDA                   | 151       | 1.89%   |
| Hewlett-Packard         | 132       | 1.65%   |
| CSO                     | 95        | 1.19%   |
| BenQ                    | 86        | 1.07%   |
| Chi Mei Optoelectronics | 85        | 1.06%   |
| Acer                    | 85        | 1.06%   |
| Philips                 | 84        | 1.05%   |
| AOC                     | 82        | 1.02%   |
| InfoVision              | 68        | 0.85%   |
| Ancor Communications    | 62        | 0.77%   |
| Iiyama                  | 37        | 0.46%   |
| ViewSonic               | 33        | 0.41%   |
| ASUSTek Computer        | 31        | 0.39%   |
| TMX                     | 30        | 0.37%   |
| Panasonic               | 20        | 0.25%   |
| Sony                    | 19        | 0.24%   |
| JDI                     | 19        | 0.24%   |
| Toshiba                 | 16        | 0.2%    |
| LG Philips              | 14        | 0.17%   |
| MSI                     | 12        | 0.15%   |
| Sceptre Tech            | 11        | 0.14%   |
| CPT                     | 10        | 0.12%   |
| HannStar                | 9         | 0.11%   |
| Vizio                   | 8         | 0.1%    |
| Gigabyte Technology     | 8         | 0.1%    |
| Fujitsu Siemens         | 8         | 0.1%    |
| Eizo                    | 8         | 0.1%    |
| Vestel Elektronik       | 7         | 0.09%   |
| NEC Computers           | 7         | 0.09%   |
| Mi                      | 7         | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 66        | 0.81%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 60        | 0.74%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch       | 52        | 0.64%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 51        | 0.63%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 50        | 0.62%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 44        | 0.54%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 38        | 0.47%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 38        | 0.47%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch       | 38        | 0.47%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 37        | 0.46%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 37        | 0.46%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                | 36        | 0.44%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch        | 34        | 0.42%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 33        | 0.41%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch             | 31        | 0.38%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 30        | 0.37%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch | 28        | 0.34%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 26        | 0.32%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 26        | 0.32%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch     | 25        | 0.31%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 24        | 0.3%    |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch         | 23        | 0.28%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch         | 23        | 0.28%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 23        | 0.28%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 23        | 0.28%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 23        | 0.28%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 23        | 0.28%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                | 23        | 0.28%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch       | 23        | 0.28%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch              | 22        | 0.27%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch         | 22        | 0.27%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch         | 22        | 0.27%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x193mm 15.5-inch       | 22        | 0.27%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch       | 22        | 0.27%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch          | 21        | 0.26%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                    | 21        | 0.26%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                | 21        | 0.26%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                | 21        | 0.26%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                | 21        | 0.26%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 21        | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 3750      | 51.15%  |
| 1366x768 (WXGA)    | 1415      | 19.3%   |
| 3840x2160 (4K)     | 417       | 5.69%   |
| 2560x1440 (QHD)    | 321       | 4.38%   |
| 1600x900 (HD+)     | 255       | 3.48%   |
| 1920x1200 (WUXGA)  | 216       | 2.95%   |
| 2560x1600          | 136       | 1.86%   |
| 1280x800 (WXGA)    | 113       | 1.54%   |
| 2880x1800          | 92        | 1.25%   |
| 2560x1080          | 68        | 0.93%   |
| 3440x1440          | 66        | 0.9%    |
| 1440x900 (WXGA+)   | 65        | 0.89%   |
| 3840x2400          | 52        | 0.71%   |
| 2160x1440          | 46        | 0.63%   |
| 1680x1050 (WSXGA+) | 46        | 0.63%   |
| 1280x1024 (SXGA)   | 38        | 0.52%   |
| 2256x1504          | 37        | 0.5%    |
| 3200x1800 (QHD+)   | 34        | 0.46%   |
| 3000x2000          | 19        | 0.26%   |
| 1360x768           | 18        | 0.25%   |
| 2520x1680          | 12        | 0.16%   |
| 3200x2000          | 11        | 0.15%   |
| 3456x2160          | 9         | 0.12%   |
| 3072x1920          | 9         | 0.12%   |
| 2240x1400          | 9         | 0.12%   |
| 2160x1350          | 7         | 0.1%    |
| 1920x1280          | 7         | 0.1%    |
| 3840x1600          | 6         | 0.08%   |
| 1024x768 (XGA)     | 6         | 0.08%   |
| 3840x1080          | 5         | 0.07%   |
| 1920x540           | 5         | 0.07%   |
| 1024x600           | 5         | 0.07%   |
| 3840x1100          | 4         | 0.05%   |
| Unknown            | 3         | 0.04%   |
| 800x1280           | 2         | 0.03%   |
| 2880x1920          | 2         | 0.03%   |
| 2880x1620          | 2         | 0.03%   |
| 2736x1824          | 2         | 0.03%   |
| 2304x1440          | 2         | 0.03%   |
| 1920x515           | 2         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 2964      | 37.03%  |
| 13      | 1310      | 16.37%  |
| 14      | 1112      | 13.89%  |
| 17      | 397       | 4.96%   |
| 27      | 375       | 4.69%   |
| 24      | 366       | 4.57%   |
| 23      | 249       | 3.11%   |
| 12      | 209       | 2.61%   |
| 21      | 198       | 2.47%   |
| 16      | 122       | 1.52%   |
| 34      | 117       | 1.46%   |
| 31      | 81        | 1.01%   |
| 18      | 73        | 0.91%   |
| 11      | 72        | 0.9%    |
| 19      | 41        | 0.51%   |
| 20      | 35        | 0.44%   |
| 22      | 31        | 0.39%   |
| 40      | 25        | 0.31%   |
| Unknown | 25        | 0.31%   |
| 25      | 24        | 0.3%    |
| 84      | 21        | 0.26%   |
| 32      | 15        | 0.19%   |
| 10      | 14        | 0.17%   |
| 35      | 12        | 0.15%   |
| 29      | 12        | 0.15%   |
| 26      | 12        | 0.15%   |
| 54      | 11        | 0.14%   |
| 28      | 11        | 0.14%   |
| 72      | 8         | 0.1%    |
| 37      | 7         | 0.09%   |
| 48      | 6         | 0.07%   |
| 42      | 5         | 0.06%   |
| 39      | 5         | 0.06%   |
| 74      | 4         | 0.05%   |
| 63      | 3         | 0.04%   |
| 57      | 3         | 0.04%   |
| 52      | 3         | 0.04%   |
| 36      | 3         | 0.04%   |
| 33      | 3         | 0.04%   |
| 69      | 2         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 4795      | 60.57%  |
| 501-600     | 927       | 11.71%  |
| 201-300     | 923       | 11.66%  |
| 351-400     | 483       | 6.1%    |
| 401-500     | 355       | 4.48%   |
| 701-800     | 138       | 1.74%   |
| 601-700     | 138       | 1.74%   |
| 801-900     | 51        | 0.64%   |
| 1001-1500   | 36        | 0.45%   |
| 1501-2000   | 35        | 0.44%   |
| Unknown     | 25        | 0.32%   |
| 901-1000    | 8         | 0.1%    |
| 1-100       | 2         | 0.03%   |
| 101-200     | 1         | 0.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 5607      | 82.91%  |
| 16/10   | 792       | 11.71%  |
| 21/9    | 141       | 2.08%   |
| 3/2     | 136       | 2.01%   |
| 5/4     | 36        | 0.53%   |
| 4/3     | 17        | 0.25%   |
| Unknown | 11        | 0.16%   |
| 32/9    | 9         | 0.13%   |
| 3.40    | 4         | 0.06%   |
| 6/5     | 2         | 0.03%   |
| 0.67    | 2         | 0.03%   |
| 3.88    | 1         | 0.01%   |
| 3.73    | 1         | 0.01%   |
| 3.33    | 1         | 0.01%   |
| 0.89    | 1         | 0.01%   |
| 0.62    | 1         | 0.01%   |
| 0.56    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 2960      | 37.07%  |
| 81-90          | 1922      | 24.07%  |
| 201-250        | 666       | 8.34%   |
| 71-80          | 487       | 6.1%    |
| 301-350        | 388       | 4.86%   |
| 121-130        | 355       | 4.45%   |
| 351-500        | 241       | 3.02%   |
| 61-70          | 200       | 2.5%    |
| 251-300        | 141       | 1.77%   |
| 151-200        | 131       | 1.64%   |
| 111-120        | 122       | 1.53%   |
| 51-60          | 76        | 0.95%   |
| 141-150        | 76        | 0.95%   |
| More than 1000 | 62        | 0.78%   |
| 501-1000       | 59        | 0.74%   |
| 131-140        | 36        | 0.45%   |
| Unknown        | 25        | 0.31%   |
| 91-100         | 20        | 0.25%   |
| 41-50          | 14        | 0.18%   |
| 1-40           | 4         | 0.05%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 3522      | 45.18%  |
| 101-120       | 1724      | 22.11%  |
| 51-100        | 1218      | 15.62%  |
| 161-240       | 843       | 10.81%  |
| More than 240 | 416       | 5.34%   |
| 1-50          | 48        | 0.62%   |
| Unknown       | 25        | 0.32%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 4928      | 73.05%  |
| 2     | 1457      | 21.6%   |
| 3     | 198       | 2.94%   |
| 0     | 146       | 2.16%   |
| 4     | 14        | 0.21%   |
| 5     | 3         | 0.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 3954      | 40.05%  |
| Realtek Semiconductor             | 3242      | 32.84%  |
| Qualcomm Atheros                  | 1102      | 11.16%  |
| Broadcom                          | 421       | 4.26%   |
| MediaTek                          | 224       | 2.27%   |
| Lenovo                            | 96        | 0.97%   |
| Broadcom Limited                  | 92        | 0.93%   |
| ASIX Electronics                  | 66        | 0.67%   |
| Sierra Wireless                   | 65        | 0.66%   |
| TP-Link                           | 63        | 0.64%   |
| Qualcomm                          | 46        | 0.47%   |
| DisplayLink                       | 43        | 0.44%   |
| Dell                              | 43        | 0.44%   |
| Ralink                            | 41        | 0.42%   |
| Marvell Technology Group          | 33        | 0.33%   |
| Ericsson Business Mobile Networks | 31        | 0.31%   |
| Samsung Electronics               | 30        | 0.3%    |
| Ralink Technology                 | 29        | 0.29%   |
| Hewlett-Packard                   | 27        | 0.27%   |
| Xiaomi                            | 20        | 0.2%    |
| Nvidia                            | 18        | 0.18%   |
| Huawei Technologies               | 18        | 0.18%   |
| ASUSTek Computer                  | 14        | 0.14%   |
| Apple                             | 13        | 0.13%   |
| Google                            | 11        | 0.11%   |
| Fibocom                           | 11        | 0.11%   |
| JMicron Technology                | 10        | 0.1%    |
| Qualcomm Atheros Communications   | 9         | 0.09%   |
| OPPO Electronics                  | 9         | 0.09%   |
| NetGear                           | 9         | 0.09%   |
| T & A Mobile Phones               | 6         | 0.06%   |
| Microsoft                         | 6         | 0.06%   |
| Linksys                           | 6         | 0.06%   |
| D-Link                            | 6         | 0.06%   |
| OnePlus Technology (Shenzhen)     | 5         | 0.05%   |
| D-Link System                     | 5         | 0.05%   |
| Motorola PCS                      | 4         | 0.04%   |
| Edimax Technology                 | 4         | 0.04%   |
| ZTE WCDMA Technologies MSM        | 3         | 0.03%   |
| Cypress Semiconductor             | 3         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2025      | 16.83%  |
| Intel Wi-Fi 6 AX200                                               | 473       | 3.93%   |
| Intel Wireless 8265 / 8275                                        | 425       | 3.53%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 412       | 3.42%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 361       | 3%      |
| Intel Wi-Fi 6 AX201                                               | 339       | 2.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 267       | 2.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 245       | 2.04%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 235       | 1.95%   |
| Intel Wireless 8260                                               | 234       | 1.94%   |
| Intel Wireless 7260                                               | 216       | 1.79%   |
| Intel Wireless 7265                                               | 212       | 1.76%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 203       | 1.69%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 197       | 1.64%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 180       | 1.5%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 172       | 1.43%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 168       | 1.4%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 164       | 1.36%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 163       | 1.35%   |
| Intel Ethernet Connection (4) I219-LM                             | 160       | 1.33%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 155       | 1.29%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 147       | 1.22%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 141       | 1.17%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 138       | 1.15%   |
| Intel Wireless 3165                                               | 107       | 0.89%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 102       | 0.85%   |
| Intel Ethernet Connection I219-LM                                 | 100       | 0.83%   |
| Intel Wireless-AC 9260                                            | 94        | 0.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 91        | 0.76%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 90        | 0.75%   |
| Intel Ethernet Connection (4) I219-V                              | 90        | 0.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 84        | 0.7%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 76        | 0.63%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 75        | 0.62%   |
| Intel Ethernet Connection I218-LM                                 | 75        | 0.62%   |
| Intel Centrino Ultimate-N 6300                                    | 70        | 0.58%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 68        | 0.57%   |
| Intel Ethernet Connection (6) I219-V                              | 68        | 0.57%   |
| Intel Wireless 3160                                               | 67        | 0.56%   |
| Intel Ethernet Connection (3) I218-LM                             | 67        | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 3852      | 57.63%  |
| Qualcomm Atheros                      | 966       | 14.45%  |
| Realtek Semiconductor                 | 909       | 13.6%   |
| Broadcom                              | 349       | 5.22%   |
| MediaTek                              | 217       | 3.25%   |
| Broadcom Limited                      | 70        | 1.05%   |
| Sierra Wireless                       | 65        | 0.97%   |
| TP-Link                               | 41        | 0.61%   |
| Ralink                                | 41        | 0.61%   |
| Qualcomm                              | 35        | 0.52%   |
| Dell                                  | 32        | 0.48%   |
| Ralink Technology                     | 29        | 0.43%   |
| ASUSTek Computer                      | 13        | 0.19%   |
| Fibocom                               | 11        | 0.16%   |
| Qualcomm Atheros Communications       | 9         | 0.13%   |
| NetGear                               | 8         | 0.12%   |
| Hewlett-Packard                       | 8         | 0.12%   |
| Linksys                               | 5         | 0.07%   |
| D-Link System                         | 5         | 0.07%   |
| Microsoft                             | 4         | 0.06%   |
| Edimax Technology                     | 4         | 0.06%   |
| D-Link                                | 3         | 0.04%   |
| Quectel Wireless Solutions            | 2         | 0.03%   |
| Belkin Components                     | 2         | 0.03%   |
| TRENDnet                              | 1         | 0.01%   |
| Qualcomm Technologies                 | 1         | 0.01%   |
| IMC Networks                          | 1         | 0.01%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 473       | 7.04%   |
| Intel Wireless 8265 / 8275                                     | 425       | 6.33%   |
| Intel Wi-Fi 6 AX201                                            | 339       | 5.05%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 267       | 3.97%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 235       | 3.5%    |
| Intel Wireless 8260                                            | 234       | 3.48%   |
| Intel Wireless 7260                                            | 216       | 3.21%   |
| Intel Wireless 7265                                            | 212       | 3.16%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 203       | 3.02%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 197       | 2.93%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 180       | 2.68%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 172       | 2.56%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 168       | 2.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 164       | 2.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 163       | 2.43%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 155       | 2.31%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 147       | 2.19%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 141       | 2.1%    |
| Intel Alder Lake-P PCH CNVi WiFi                               | 138       | 2.05%   |
| Intel Wireless 3165                                            | 107       | 1.59%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 102       | 1.52%   |
| Intel Wireless-AC 9260                                         | 94        | 1.4%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 91        | 1.35%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 90        | 1.34%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 84        | 1.25%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 76        | 1.13%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 75        | 1.12%   |
| Intel Centrino Ultimate-N 6300                                 | 70        | 1.04%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 68        | 1.01%   |
| Intel Wireless 3160                                            | 67        | 1%      |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 66        | 0.98%   |
| Broadcom BCM43142 802.11b/g/n                                  | 65        | 0.97%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 48        | 0.71%   |
| Intel Centrino Advanced-N 6235                                 | 47        | 0.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 46        | 0.68%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 45        | 0.67%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 37        | 0.55%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 37        | 0.55%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 36        | 0.54%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 35        | 0.52%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 2862      | 55.74%  |
| Intel                                  | 1453      | 28.3%   |
| Qualcomm Atheros                       | 233       | 4.54%   |
| Broadcom                               | 136       | 2.65%   |
| Lenovo                                 | 94        | 1.83%   |
| ASIX Electronics                       | 66        | 1.29%   |
| DisplayLink                            | 43        | 0.84%   |
| Marvell Technology Group               | 33        | 0.64%   |
| TP-Link                                | 24        | 0.47%   |
| Samsung Electronics                    | 23        | 0.45%   |
| Broadcom Limited                       | 22        | 0.43%   |
| Xiaomi                                 | 20        | 0.39%   |
| Nvidia                                 | 18        | 0.35%   |
| Apple                                  | 13        | 0.25%   |
| Qualcomm                               | 11        | 0.21%   |
| Google                                 | 11        | 0.21%   |
| JMicron Technology                     | 10        | 0.19%   |
| Huawei Technologies                    | 10        | 0.19%   |
| OPPO Electronics                       | 9         | 0.18%   |
| MediaTek                               | 7         | 0.14%   |
| Hewlett-Packard                        | 6         | 0.12%   |
| OnePlus Technology (Shenzhen)          | 4         | 0.08%   |
| ZTE WCDMA Technologies MSM             | 3         | 0.06%   |
| D-Link                                 | 3         | 0.06%   |
| Cypress Semiconductor                  | 3         | 0.06%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.04%   |
| Microsoft                              | 2         | 0.04%   |
| ICS Advent                             | 2         | 0.04%   |
| vivo                                   | 1         | 0.02%   |
| T & A Mobile Phones                    | 1         | 0.02%   |
| Spreadtrum Communications              | 1         | 0.02%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.02%   |
| Novatel Wireless                       | 1         | 0.02%   |
| NetGear                                | 1         | 0.02%   |
| Motorola PCS                           | 1         | 0.02%   |
| Linksys                                | 1         | 0.02%   |
| LG Electronics                         | 1         | 0.02%   |
| HMD Global                             | 1         | 0.02%   |
| ASUSTek Computer                       | 1         | 0.02%   |
| Aquantia                               | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2025      | 38.8%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 412       | 7.89%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 361       | 6.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 245       | 4.69%   |
| Intel Ethernet Connection (4) I219-LM                             | 160       | 3.07%   |
| Intel Ethernet Connection I219-LM                                 | 100       | 1.92%   |
| Intel Ethernet Connection (4) I219-V                              | 90        | 1.72%   |
| Intel Ethernet Connection I218-LM                                 | 75        | 1.44%   |
| Intel Ethernet Connection (6) I219-V                              | 68        | 1.3%    |
| Intel Ethernet Connection (3) I218-LM                             | 67        | 1.28%   |
| Intel Ethernet Connection I217-LM                                 | 66        | 1.26%   |
| ASIX AX88179 Gigabit Ethernet                                     | 61        | 1.17%   |
| Intel Ethernet Connection (7) I219-LM                             | 59        | 1.13%   |
| Intel Ethernet Connection (10) I219-V                             | 57        | 1.09%   |
| Intel Ethernet Connection (6) I219-LM                             | 55        | 1.05%   |
| Intel 82577LM Gigabit Network Connection                          | 41        | 0.79%   |
| Intel Ethernet Connection (2) I219-LM                             | 40        | 0.77%   |
| Realtek RTL8125 2.5GbE Controller                                 | 39        | 0.75%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 38        | 0.73%   |
| Intel Ethernet Connection I219-V                                  | 37        | 0.71%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 36        | 0.69%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 35        | 0.67%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 34        | 0.65%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 34        | 0.65%   |
| Intel Ethernet Connection (13) I219-V                             | 33        | 0.63%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 30        | 0.57%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 29        | 0.56%   |
| Intel Ethernet Connection (7) I219-V                              | 28        | 0.54%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 24        | 0.46%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 24        | 0.46%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 23        | 0.44%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 23        | 0.44%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 21        | 0.4%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 20        | 0.38%   |
| Intel Ethernet Connection (10) I219-LM                            | 19        | 0.36%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 18        | 0.34%   |
| Lenovo ThinkPad TBT3 LAN                                          | 18        | 0.34%   |
| Intel Ethernet Connection I217-V                                  | 18        | 0.34%   |
| Intel Ethernet Connection (16) I219-V                             | 18        | 0.34%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 17        | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 6381      | 56.46%  |
| Ethernet | 4824      | 42.68%  |
| Modem    | 85        | 0.75%   |
| Unknown  | 12        | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 5547      | 79.87%  |
| Ethernet | 1396      | 20.1%   |
| Modem    | 2         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 4311      | 66.2%   |
| 1     | 1990      | 30.56%  |
| 0     | 132       | 2.03%   |
| 3     | 79        | 1.21%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Notebooks | Percent |
|---------|-----------|---------|
| No      | 5383      | 81.15%  |
| Yes     | 1247      | 18.8%   |
| Unknown | 3         | 0.05%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 3207      | 58%     |
| Realtek Semiconductor           | 530       | 9.59%   |
| Qualcomm Atheros Communications | 483       | 8.74%   |
| IMC Networks                    | 236       | 4.27%   |
| Broadcom                        | 220       | 3.98%   |
| Foxconn / Hon Hai               | 214       | 3.87%   |
| Lite-On Technology              | 200       | 3.62%   |
| Apple                           | 140       | 2.53%   |
| Realtek                         | 65        | 1.18%   |
| Cambridge Silicon Radio         | 42        | 0.76%   |
| Dell                            | 40        | 0.72%   |
| Hewlett-Packard                 | 30        | 0.54%   |
| Ralink                          | 27        | 0.49%   |
| Toshiba                         | 22        | 0.4%    |
| ASUSTek Computer                | 16        | 0.29%   |
| Foxconn International           | 11        | 0.2%    |
| USI                             | 10        | 0.18%   |
| Opticis                         | 9         | 0.16%   |
| MediaTek                        | 7         | 0.13%   |
| Ralink Technology               | 4         | 0.07%   |
| Smart Modular Technologies      | 3         | 0.05%   |
| Chicony Electronics             | 3         | 0.05%   |
| Alps Electric                   | 3         | 0.05%   |
| Qcom                            | 2         | 0.04%   |
| Taiyo Yuden                     | 1         | 0.02%   |
| Micro Star International        | 1         | 0.02%   |
| Fujitsu                         | 1         | 0.02%   |
| Corsair                         | 1         | 0.02%   |
| Askey Computer                  | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 1162      | 21.01%  |
| Intel AX201 Bluetooth                               | 671       | 12.13%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 497       | 8.98%   |
| Intel AX200 Bluetooth                               | 462       | 8.35%   |
| Realtek Bluetooth Radio                             | 321       | 5.8%    |
| Qualcomm Atheros  Bluetooth Device                  | 282       | 5.1%    |
| Realtek  Bluetooth 4.2 Adapter                      | 127       | 2.3%    |
| Intel Bluetooth Device                              | 122       | 2.21%   |
| Intel AX210 Bluetooth                               | 99        | 1.79%   |
| Apple Bluetooth Host Controller                     | 99        | 1.79%   |
| IMC Networks Wireless_Device                        | 86        | 1.55%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 83        | 1.5%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 79        | 1.43%   |
| IMC Networks Bluetooth Radio                        | 75        | 1.36%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 73        | 1.32%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 71        | 1.28%   |
| Foxconn / Hon Hai Bluetooth Device                  | 69        | 1.25%   |
| Realtek Bluetooth Radio                             | 65        | 1.17%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 57        | 1.03%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 49        | 0.89%   |
| Lite-On Bluetooth Device                            | 48        | 0.87%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 48        | 0.87%   |
| Intel Wireless-AC 3168 Bluetooth                    | 43        | 0.78%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 42        | 0.76%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 41        | 0.74%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 39        | 0.7%    |
| Broadcom BCM2045B (BDC-2.1)                         | 37        | 0.67%   |
| IMC Networks Bluetooth Device                       | 34        | 0.61%   |
| Foxconn / Hon Hai Wireless_Device                   | 34        | 0.61%   |
| Apple Bluetooth USB Host Controller                 | 30        | 0.54%   |
| Ralink RT3290 Bluetooth                             | 27        | 0.49%   |
| Lite-On Atheros AR3012 Bluetooth                    | 26        | 0.47%   |
| Realtek RTL8723B Bluetooth                          | 23        | 0.42%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 23        | 0.42%   |
| Lite-On Wireless_Device                             | 22        | 0.4%    |
| HP Broadcom 2070 Bluetooth Combo                    | 22        | 0.4%    |
| Dell DW375 Bluetooth Module                         | 19        | 0.34%   |
| Dell BCM20702A0 Bluetooth Module                    | 17        | 0.31%   |
| Realtek RTL8821A Bluetooth                          | 16        | 0.29%   |
| Broadcom HP Portable SoftSailing                    | 16        | 0.29%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 5109      | 60.92%  |
| AMD                        | 1341      | 15.99%  |
| Nvidia                     | 1125      | 13.41%  |
| Lenovo                     | 109       | 1.3%    |
| C-Media Electronics        | 82        | 0.98%   |
| Realtek Semiconductor      | 81        | 0.97%   |
| GN Netcom                  | 59        | 0.7%    |
| Logitech                   | 58        | 0.69%   |
| Plantronics                | 37        | 0.44%   |
| Hewlett-Packard            | 29        | 0.35%   |
| JMTek                      | 26        | 0.31%   |
| Kingston Technology        | 18        | 0.21%   |
| Texas Instruments          | 17        | 0.2%    |
| Creative Technology        | 15        | 0.18%   |
| SteelSeries ApS            | 14        | 0.17%   |
| Razer USA                  | 12        | 0.14%   |
| Corsair                    | 12        | 0.14%   |
| DSEA A/S                   | 11        | 0.13%   |
| Apple                      | 11        | 0.13%   |
| Generalplus Technology     | 10        | 0.12%   |
| Blue Microphones           | 10        | 0.12%   |
| Sony                       | 9         | 0.11%   |
| Samson Technologies        | 9         | 0.11%   |
| ASUSTek Computer           | 9         | 0.11%   |
| RODE Microphones           | 8         | 0.1%    |
| Dell                       | 8         | 0.1%    |
| Conexant Systems           | 8         | 0.1%    |
| Microsoft                  | 7         | 0.08%   |
| Focusrite-Novation         | 7         | 0.08%   |
| XMOS                       | 6         | 0.07%   |
| Samsung Electronics        | 6         | 0.07%   |
| No brand                   | 6         | 0.07%   |
| CMX Systems                | 6         | 0.07%   |
| SAVITECH                   | 5         | 0.06%   |
| Tenx Technology            | 4         | 0.05%   |
| PreSonus Audio Electronics | 4         | 0.05%   |
| M-Audio                    | 4         | 0.05%   |
| GYROCOM C&C                | 4         | 0.05%   |
| Guangzhou FiiO Electronics | 4         | 0.05%   |
| FIFINE Microphones         | 4         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 1036      | 10.15%  |
| AMD Family 17h/19h HD Audio Controller                                     | 1022      | 10.01%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 565       | 5.53%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 440       | 4.31%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 439       | 4.3%    |
| Intel Cannon Lake PCH cAVS                                                 | 365       | 3.57%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 295       | 2.89%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 290       | 2.84%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 273       | 2.67%   |
| Intel Comet Lake PCH-LP cAVS                                               | 261       | 2.56%   |
| Intel Haswell-ULT HD Audio Controller                                      | 241       | 2.36%   |
| Intel 8 Series HD Audio Controller                                         | 241       | 2.36%   |
| Intel Broadwell-U Audio Controller                                         | 232       | 2.27%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 229       | 2.24%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 223       | 2.18%   |
| Intel Comet Lake PCH cAVS                                                  | 193       | 1.89%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 176       | 1.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 175       | 1.71%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 173       | 1.69%   |
| Intel CM238 HD Audio Controller                                            | 142       | 1.39%   |
| Nvidia GP107GL High Definition Audio Controller                            | 141       | 1.38%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 138       | 1.35%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 126       | 1.23%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 122       | 1.19%   |
| AMD FCH Azalia Controller                                                  | 103       | 1.01%   |
| Nvidia GA106 High Definition Audio Controller                              | 94        | 0.92%   |
| Nvidia TU106 High Definition Audio Controller                              | 85        | 0.83%   |
| AMD Kabini HDMI/DP Audio                                                   | 83        | 0.81%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 82        | 0.8%    |
| Realtek Semiconductor USB Audio                                            | 80        | 0.78%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 75        | 0.73%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 72        | 0.71%   |
| Nvidia GF108 High Definition Audio Controller                              | 71        | 0.7%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 71        | 0.7%    |
| Nvidia GK107 HDMI Audio Controller                                         | 63        | 0.62%   |
| Nvidia Audio device                                                        | 61        | 0.6%    |
| Nvidia TU116 High Definition Audio Controller                              | 59        | 0.58%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 59        | 0.58%   |
| Nvidia GA104 High Definition Audio Controller                              | 56        | 0.55%   |
| Nvidia GP106 High Definition Audio Controller                              | 48        | 0.47%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1220      | 29.8%   |
| SK hynix            | 921       | 22.5%   |
| Micron Technology   | 589       | 14.39%  |
| Kingston            | 336       | 8.21%   |
| Crucial             | 233       | 5.69%   |
| Unknown             | 212       | 5.18%   |
| Ramaxel Technology  | 98        | 2.39%   |
| A-DATA Technology   | 95        | 2.32%   |
| Corsair             | 58        | 1.42%   |
| Elpida              | 37        | 0.9%    |
| Smart               | 31        | 0.76%   |
| Unknown (ABCD)      | 27        | 0.66%   |
| G.Skill             | 26        | 0.64%   |
| Team                | 23        | 0.56%   |
| Nanya Technology    | 20        | 0.49%   |
| Patriot             | 19        | 0.46%   |
| Teikon              | 15        | 0.37%   |
| Unknown             | 15        | 0.37%   |
| Smart Brazil        | 12        | 0.29%   |
| Transcend           | 10        | 0.24%   |
| GOODRAM             | 10        | 0.24%   |
| Avant               | 9         | 0.22%   |
| Silicon Power       | 5         | 0.12%   |
| Goldkey             | 5         | 0.12%   |
| Apacer              | 4         | 0.1%    |
| PUSKILL             | 3         | 0.07%   |
| OnBoard             | 3         | 0.07%   |
| Kllisre             | 3         | 0.07%   |
| CSX                 | 3         | 0.07%   |
| Timetec             | 2         | 0.05%   |
| SHARETRONIC         | 2         | 0.05%   |
| Sesame              | 2         | 0.05%   |
| RZX                 | 2         | 0.05%   |
| Qimonda             | 2         | 0.05%   |
| PNY                 | 2         | 0.05%   |
| Memox               | 2         | 0.05%   |
| Lexar               | 2         | 0.05%   |
| ChangXin Memory     | 2         | 0.05%   |
| ASint Technology    | 2         | 0.05%   |
| 4ea5                | 2         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 77        | 1.79%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 70        | 1.62%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 56        | 1.3%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 55        | 1.28%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 39        | 0.9%    |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 36        | 0.84%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 34        | 0.79%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 33        | 0.77%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 33        | 0.77%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 33        | 0.77%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 32        | 0.74%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 29        | 0.67%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 29        | 0.67%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 28        | 0.65%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 28        | 0.65%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 28        | 0.65%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 28        | 0.65%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 27        | 0.63%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 27        | 0.63%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 26        | 0.6%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 26        | 0.6%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 25        | 0.58%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 25        | 0.58%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 25        | 0.58%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 25        | 0.58%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 24        | 0.56%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 23        | 0.53%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 23        | 0.53%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 23        | 0.53%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 23        | 0.53%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 22        | 0.51%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 22        | 0.51%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 22        | 0.51%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 21        | 0.49%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 21        | 0.49%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 21        | 0.49%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 21        | 0.49%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 21        | 0.49%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 21        | 0.49%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 20        | 0.46%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 1985      | 58.19%  |
| DDR3    | 864       | 25.33%  |
| LPDDR4  | 189       | 5.54%   |
| LPDDR3  | 187       | 5.48%   |
| LPDDR5  | 61        | 1.79%   |
| DDR5    | 48        | 1.41%   |
| DDR2    | 42        | 1.23%   |
| SDRAM   | 18        | 0.53%   |
| Unknown | 13        | 0.38%   |
| DDR     | 3         | 0.09%   |
| DRAM    | 1         | 0.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 2917      | 83.89%  |
| Row Of Chips | 476       | 13.69%  |
| Chip         | 46        | 1.32%   |
| Unknown      | 20        | 0.58%   |
| DIMM         | 18        | 0.52%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 1608      | 43.19%  |
| 4096  | 956       | 25.68%  |
| 16384 | 704       | 18.91%  |
| 2048  | 275       | 7.39%   |
| 32768 | 132       | 3.55%   |
| 1024  | 44        | 1.18%   |
| 3072  | 2         | 0.05%   |
| 512   | 1         | 0.03%   |
| 64    | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 895       | 24.35%  |
| 3200    | 856       | 23.29%  |
| 1600    | 625       | 17.01%  |
| 2400    | 278       | 7.56%   |
| 2133    | 252       | 6.86%   |
| 1333    | 110       | 2.99%   |
| 1334    | 100       | 2.72%   |
| 4267    | 94        | 2.56%   |
| 1867    | 74        | 2.01%   |
| 6400    | 61        | 1.66%   |
| 3266    | 56        | 1.52%   |
| 4800    | 53        | 1.44%   |
| 1067    | 36        | 0.98%   |
| Unknown | 30        | 0.82%   |
| 8400    | 26        | 0.71%   |
| 667     | 26        | 0.71%   |
| 4266    | 24        | 0.65%   |
| 1066    | 17        | 0.46%   |
| 4199    | 15        | 0.41%   |
| 3733    | 14        | 0.38%   |
| 800     | 13        | 0.35%   |
| 975     | 4         | 0.11%   |
| 2933    | 2         | 0.05%   |
| 933     | 2         | 0.05%   |
| 533     | 2         | 0.05%   |
| 5500    | 1         | 0.03%   |
| 3400    | 1         | 0.03%   |
| 2800    | 1         | 0.03%   |
| 2048    | 1         | 0.03%   |
| 1866    | 1         | 0.03%   |
| 1777    | 1         | 0.03%   |
| 1639    | 1         | 0.03%   |
| 1200    | 1         | 0.03%   |
| 333     | 1         | 0.03%   |
| 133     | 1         | 0.03%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 9         | 23.68%  |
| Canon               | 8         | 21.05%  |
| Samsung Electronics | 6         | 15.79%  |
| Brother Industries  | 5         | 13.16%  |
| Seiko Epson         | 4         | 10.53%  |
| Prolific Technology | 2         | 5.26%   |
| Ricoh               | 1         | 2.63%   |
| Pantum              | 1         | 2.63%   |
| NXP Semiconductors  | 1         | 2.63%   |
| MiiiW               | 1         | 2.63%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port                                         | 2         | 5.26%   |
| Seiko Epson WF-2830 Series                                            | 1         | 2.63%   |
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 1         | 2.63%   |
| Seiko Epson L200 Series                                               | 1         | 2.63%   |
| Seiko Epson ET-2710 Series                                            | 1         | 2.63%   |
| Samsung SCX-4200 series                                               | 1         | 2.63%   |
| Samsung SCX-3200 Series                                               | 1         | 2.63%   |
| Samsung ML-331x Series Laser Printer                                  | 1         | 2.63%   |
| Samsung M2070 Series                                                  | 1         | 2.63%   |
| Samsung CLX-6260 Series                                               | 1         | 2.63%   |
| Samsung C43x Series                                                   | 1         | 2.63%   |
| Ricoh SP 210SU                                                        | 1         | 2.63%   |
| Pantum P2500W series                                                  | 1         | 2.63%   |
| NXP Semiconductors Printer-80                                         | 1         | 2.63%   |
| MiiiW MW USB Receiver                                                 | 1         | 2.63%   |
| HP Photosmart B010 series                                             | 1         | 2.63%   |
| HP Officejet 2620 series                                              | 1         | 2.63%   |
| HP LaserJet 400 colorMFP M475dw                                       | 1         | 2.63%   |
| HP ENVY Pro 6400 series                                               | 1         | 2.63%   |
| HP ENVY 4500 series                                                   | 1         | 2.63%   |
| HP Deskjet 3510 series                                                | 1         | 2.63%   |
| HP Deskjet 3050A                                                      | 1         | 2.63%   |
| HP DeskJet 2300 series                                                | 1         | 2.63%   |
| HP DeskJet 2130 series                                                | 1         | 2.63%   |
| Canon TR8500 series                                                   | 1         | 2.63%   |
| Canon TR150 series                                                    | 1         | 2.63%   |
| Canon PIXMA MG3600 Series                                             | 1         | 2.63%   |
| Canon PIXMA MG3500 Series                                             | 1         | 2.63%   |
| Canon PIXMA MG3000 series                                             | 1         | 2.63%   |
| Canon MF3110                                                          | 1         | 2.63%   |
| Canon MF220 Series                                                    | 1         | 2.63%   |
| Canon iP7200 series                                                   | 1         | 2.63%   |
| Brother Printer                                                       | 1         | 2.63%   |
| Brother HL-5250DN Printer                                             | 1         | 2.63%   |
| Brother DCP-T220                                                      | 1         | 2.63%   |
| Brother DCP-7025 Printer                                              | 1         | 2.63%   |
| Brother DCP-1600                                                      | 1         | 2.63%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 6         | 60%     |
| Seiko Epson     | 3         | 30%     |
| Hewlett-Packard | 1         | 10%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20          | 2         | 20%     |
| Canon CanoScan LiDE 220                     | 2         | 20%     |
| Seiko Epson GT-X820 [Perfection V600 Photo] | 1         | 10%     |
| Seiko Epson GT-X770 [Perfection V500]       | 1         | 10%     |
| Seiko Epson ES-D400 [GT-S80]                | 1         | 10%     |
| HP Scanjet 300                              | 1         | 10%     |
| Canon CanoScan N650U/N656U                  | 1         | 10%     |
| Canon CanoScan LiDE 210                     | 1         | 10%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1472      | 24.12%  |
| IMC Networks                           | 751       | 12.3%   |
| Microdia                               | 557       | 9.13%   |
| Realtek Semiconductor                  | 512       | 8.39%   |
| Quanta                                 | 364       | 5.96%   |
| Bison Electronics                      | 342       | 5.6%    |
| Sunplus Innovation Technology          | 323       | 5.29%   |
| Acer                                   | 244       | 4%      |
| Cheng Uei Precision Industry (Foxlink) | 242       | 3.96%   |
| Lite-On Technology                     | 174       | 2.85%   |
| Syntek                                 | 171       | 2.8%    |
| Logitech                               | 145       | 2.38%   |
| Apple                                  | 125       | 2.05%   |
| Luxvisions Innotech Limited            | 112       | 1.83%   |
| Suyin                                  | 94        | 1.54%   |
| Silicon Motion                         | 71        | 1.16%   |
| Alcor Micro                            | 42        | 0.69%   |
| Sonix Technology                       | 41        | 0.67%   |
| Samsung Electronics                    | 39        | 0.64%   |
| Ricoh                                  | 36        | 0.59%   |
| Primax Electronics                     | 22        | 0.36%   |
| Lenovo                                 | 21        | 0.34%   |
| SunplusIT                              | 18        | 0.29%   |
| Microsoft                              | 16        | 0.26%   |
| Importek                               | 14        | 0.23%   |
| Z-Star Microelectronics                | 11        | 0.18%   |
| icSpring                               | 9         | 0.15%   |
| Generalplus Technology                 | 9         | 0.15%   |
| ARC International                      | 8         | 0.13%   |
| Shenzhen Kingcome Optoelectronic       | 6         | 0.1%    |
| MacroSilicon                           | 6         | 0.1%    |
| KYE Systems (Mouse Systems)            | 6         | 0.1%    |
| ALi                                    | 6         | 0.1%    |
| Pixart Imaging                         | 5         | 0.08%   |
| Intel                                  | 5         | 0.08%   |
| WaveRider Communications               | 4         | 0.07%   |
| Tobii Technology AB                    | 4         | 0.07%   |
| Razer USA                              | 4         | 0.07%   |
| Y Media                                | 3         | 0.05%   |
| Tripath Technology                     | 3         | 0.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 510       | 8.29%   |
| Microdia Integrated_Webcam_HD                       | 323       | 5.25%   |
| IMC Networks Integrated Camera                      | 296       | 4.81%   |
| Realtek Integrated_Webcam_HD                        | 230       | 3.74%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 193       | 3.14%   |
| Chicony HD WebCam                                   | 142       | 2.31%   |
| Sunplus Integrated_Webcam_HD                        | 138       | 2.24%   |
| Syntek Integrated Camera                            | 113       | 1.84%   |
| Bison Integrated Camera                             | 96        | 1.56%   |
| Chicony Integrated Camera (1280x720@30)             | 86        | 1.4%    |
| Lite-On Integrated Camera                           | 82        | 1.33%   |
| Acer Integrated Camera                              | 81        | 1.32%   |
| Quanta HD User Facing                               | 79        | 1.28%   |
| Bison SunplusIT Integrated Camera                   | 64        | 1.04%   |
| Chicony HP HD Camera                                | 61        | 0.99%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 57        | 0.93%   |
| Quanta HP TrueVision HD Camera                      | 52        | 0.85%   |
| Chicony USB2.0 Camera                               | 46        | 0.75%   |
| Lite-On HP HD Camera                                | 45        | 0.73%   |
| Logitech HD Pro Webcam C920                         | 44        | 0.72%   |
| Acer HD Webcam                                      | 43        | 0.7%    |
| Realtek USB Camera                                  | 42        | 0.68%   |
| Microdia Integrated Webcam                          | 42        | 0.68%   |
| Quanta HP HD Camera                                 | 41        | 0.67%   |
| IMC Networks HD Camera                              | 41        | 0.67%   |
| Chicony HP TrueVision HD Camera                     | 40        | 0.65%   |
| Samsung Galaxy series, misc. (MTP mode)             | 39        | 0.63%   |
| Chicony Integrated IR Camera                        | 37        | 0.6%    |
| Chicony HP Wide Vision HD Camera                    | 37        | 0.6%    |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 36        | 0.59%   |
| Realtek Integrated Webcam                           | 35        | 0.57%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 35        | 0.57%   |
| Quanta HD Webcam                                    | 34        | 0.55%   |
| Apple FaceTime HD Camera                            | 34        | 0.55%   |
| Sunplus HD WebCam                                   | 32        | 0.52%   |
| Quanta VGA WebCam                                   | 32        | 0.52%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 32        | 0.52%   |
| IMC Networks ov9734_azurewave_camera                | 32        | 0.52%   |
| Chicony HD User Facing                              | 32        | 0.52%   |
| Apple Built-in iSight                               | 32        | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 560       | 35.4%   |
| Validity Sensors                   | 476       | 30.09%  |
| Shenzhen Goodix Technology         | 278       | 17.57%  |
| Elan Microelectronics              | 97        | 6.13%   |
| Upek                               | 59        | 3.73%   |
| LighTuning Technology              | 54        | 3.41%   |
| AuthenTec                          | 34        | 2.15%   |
| Samsung Electronics                | 8         | 0.51%   |
| Realtek USB2.0 Finger Print Bridge | 6         | 0.38%   |
| STMicroelectronics                 | 5         | 0.32%   |
| Focal-systems.Corp                 | 4         | 0.25%   |
| Dell                               | 1         | 0.06%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 276       | 17.44%  |
| Shenzhen Goodix  FingerPrint Device                                        | 172       | 10.87%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 106       | 6.7%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 97        | 6.13%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 89        | 5.62%   |
| Shenzhen Goodix FingerPrint                                                | 58        | 3.66%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 56        | 3.54%   |
| Validity Sensors Synaptics WBDI                                            | 55        | 3.47%   |
| Elan ELAN:Fingerprint                                                      | 55        | 3.47%   |
| Shenzhen Goodix Fingerprint Reader                                         | 48        | 3.03%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 44        | 2.78%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 40        | 2.53%   |
| Elan ELAN:ARM-M4                                                           | 40        | 2.53%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 36        | 2.27%   |
| Validity Sensors VFS491                                                    | 28        | 1.77%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 28        | 1.77%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 27        | 1.71%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 24        | 1.52%   |
| Synaptics  WBDI                                                            | 21        | 1.33%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 21        | 1.33%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 20        | 1.26%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 20        | 1.26%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 18        | 1.14%   |
| Validity Sensors Fingerprint scanner                                       | 17        | 1.07%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 15        | 0.95%   |
| Synaptics UWP WBDI Device                                                  | 15        | 0.95%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 14        | 0.88%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 13        | 0.82%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 11        | 0.69%   |
| Synaptics UWP WBDI                                                         | 10        | 0.63%   |
| Synaptics WBDI                                                             | 9         | 0.57%   |
| AuthenTec Fingerprint Sensor                                               | 8         | 0.51%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 7         | 0.44%   |
| Validity Sensors VFS Fingerprint sensor                                    | 7         | 0.44%   |
| AuthenTec AES2810                                                          | 7         | 0.44%   |
| Unknown                                                                    | 7         | 0.44%   |
| Synaptics WBDI Device                                                      | 6         | 0.38%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 6         | 0.38%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 6         | 0.38%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 6         | 0.38%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Alcor Micro                | 250       | 41.53%  |
| Broadcom                   | 241       | 40.03%  |
| Upek                       | 38        | 6.31%   |
| Lenovo                     | 33        | 5.48%   |
| O2 Micro                   | 13        | 2.16%   |
| Gemalto (was Gemplus)      | 7         | 1.16%   |
| Yubico.com                 | 3         | 0.5%    |
| SCM Microsystems           | 3         | 0.5%    |
| OmniKey                    | 3         | 0.5%    |
| Aladdin Knowledge Systems  | 3         | 0.5%    |
| Realtek Semiconductor      | 2         | 0.33%   |
| Reiner SCT Kartensysteme   | 1         | 0.17%   |
| Purism, SPC                | 1         | 0.17%   |
| Hewlett-Packard            | 1         | 0.17%   |
| Chicony Electronics        | 1         | 0.17%   |
| Athena Smartcard Solutions | 1         | 0.17%   |
| Advanced Card Systems      | 1         | 0.17%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 249       | 41.36%  |
| Broadcom 5880                                                                | 79        | 13.12%  |
| Broadcom 58200                                                               | 65        | 10.8%   |
| Broadcom BCM5880 Secure Applications Processor                               | 53        | 8.8%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 42        | 6.98%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 38        | 6.31%   |
| Lenovo Integrated Smart Card Reader                                          | 32        | 5.32%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 10        | 1.66%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 6         | 1%      |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 3         | 0.5%    |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 0.5%    |
| Aladdin Knowledge Systems Token JC                                           | 3         | 0.5%    |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 0.33%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.33%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.17%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 0.17%   |
| SCM Microsystems CLOUD 2900 R Smart Card Reader                              | 1         | 0.17%   |
| Reiner SCT Kartensysteme tanJack USB                                         | 1         | 0.17%   |
| Purism, SPC Librem Key                                                       | 1         | 0.17%   |
| OmniKey CardMan 4321                                                         | 1         | 0.17%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.17%   |
| OmniKey CardMan 1021                                                         | 1         | 0.17%   |
| Lenovo Smartcard Keyboard                                                    | 1         | 0.17%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.17%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.17%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.17%   |
| Athena Smartcard Solutions ASEDrive CCID                                     | 1         | 0.17%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.17%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.17%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 3907      | 58.21%  |
| 1     | 2299      | 34.25%  |
| 2     | 430       | 6.41%   |
| 3     | 52        | 0.77%   |
| 4     | 8         | 0.12%   |
| 5     | 6         | 0.09%   |
| 7     | 4         | 0.06%   |
| 6     | 4         | 0.06%   |
| 8     | 2         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 1565      | 47.37%  |
| Graphics card            | 633       | 19.16%  |
| Multimedia controller    | 310       | 9.38%   |
| Net/wireless             | 228       | 6.9%    |
| Chipcard                 | 202       | 6.11%   |
| Camera                   | 123       | 3.72%   |
| Bluetooth                | 65        | 1.97%   |
| Storage                  | 46        | 1.39%   |
| Card reader              | 46        | 1.39%   |
| Sound                    | 25        | 0.76%   |
| Net/ethernet             | 17        | 0.51%   |
| Communication controller | 17        | 0.51%   |
| Network                  | 14        | 0.42%   |
| Modem                    | 8         | 0.24%   |
| Flash memory             | 2         | 0.06%   |
| Video                    | 1         | 0.03%   |
| Firewire controller      | 1         | 0.03%   |
| Dvb card                 | 1         | 0.03%   |

