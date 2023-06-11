Fedora 38 - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Fedora 38.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 717

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
| Apple         | MacBookPro9,2               | [2a0add5b7e](https://linux-hardware.org/?probe=2a0add5b7e) | Jun 07, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | [e103817b2d](https://linux-hardware.org/?probe=e103817b2d) | Jun 07, 2023 |
| Lenovo        | Yoga Pro 9 14IRP8 83BU      | [7d33fb0564](https://linux-hardware.org/?probe=7d33fb0564) | Jun 07, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | [b6bb7bad1d](https://linux-hardware.org/?probe=b6bb7bad1d) | Jun 07, 2023 |
| Apple         | MacBookPro9,2               | [8d70c1dd42](https://linux-hardware.org/?probe=8d70c1dd42) | Jun 07, 2023 |
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
| HP            | Pavilion Laptop 15-eg3xx... | [2a612dc748](https://linux-hardware.org/?probe=2a612dc748) | Jun 06, 2023 |
| System76      | Oryx Pro                    | [4f39b2d690](https://linux-hardware.org/?probe=4f39b2d690) | Jun 06, 2023 |
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
| Dell          | Precision 7540              | [a10ecca056](https://linux-hardware.org/?probe=a10ecca056) | Jun 04, 2023 |
| Sony          | VPCSC1AFM                   | [2cf80cf628](https://linux-hardware.org/?probe=2cf80cf628) | Jun 04, 2023 |
| Apple         | MacBookPro8,1               | [e3f89d1faa](https://linux-hardware.org/?probe=e3f89d1faa) | Jun 04, 2023 |
| MECHREVO      | Code01 Ver2.0               | [d311022361](https://linux-hardware.org/?probe=d311022361) | Jun 04, 2023 |
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
| Dell          | Precision 7540              | [de2fc5bc92](https://linux-hardware.org/?probe=de2fc5bc92) | Jun 01, 2023 |
| Timi          | A35S                        | [c9ce47a446](https://linux-hardware.org/?probe=c9ce47a446) | Jun 01, 2023 |
| Dell          | Latitude 5490               | [34dde30b90](https://linux-hardware.org/?probe=34dde30b90) | Jun 01, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U7C... | [8c16cec2e8](https://linux-hardware.org/?probe=8c16cec2e8) | Jun 01, 2023 |
| Dell          | Latitude 5531               | [5dc2ae0939](https://linux-hardware.org/?probe=5dc2ae0939) | Jun 01, 2023 |
| Timi          | TM1801                      | [aa1db210df](https://linux-hardware.org/?probe=aa1db210df) | Jun 01, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [0b0c375bb8](https://linux-hardware.org/?probe=0b0c375bb8) | May 31, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [65b03710b2](https://linux-hardware.org/?probe=65b03710b2) | May 31, 2023 |
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
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [74447476fe](https://linux-hardware.org/?probe=74447476fe) | May 30, 2023 |
| Dell          | Precision 5540              | [2f3cdafe90](https://linux-hardware.org/?probe=2f3cdafe90) | May 30, 2023 |
| VPU Compan... | VWNC51518                   | [16329bde51](https://linux-hardware.org/?probe=16329bde51) | May 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [5839982a52](https://linux-hardware.org/?probe=5839982a52) | May 29, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [048a3a0f30](https://linux-hardware.org/?probe=048a3a0f30) | May 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [3933dfe4f0](https://linux-hardware.org/?probe=3933dfe4f0) | May 29, 2023 |
| Sony          | VPCSA25GB                   | [981a09e39a](https://linux-hardware.org/?probe=981a09e39a) | May 29, 2023 |
| Sony          | VPCSA25GB                   | [e36e944a92](https://linux-hardware.org/?probe=e36e944a92) | May 29, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [8e09d71949](https://linux-hardware.org/?probe=8e09d71949) | May 29, 2023 |
| Acer          | Aspire A315-51              | [d6f1c2bdbd](https://linux-hardware.org/?probe=d6f1c2bdbd) | May 29, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [230a02bfda](https://linux-hardware.org/?probe=230a02bfda) | May 29, 2023 |
| Lenovo        | ThinkPad T440p 20AWS19P0... | [8d25da413c](https://linux-hardware.org/?probe=8d25da413c) | May 29, 2023 |
| ASUSTek       | VivoBook S13 X330FN         | [e94b6fbf06](https://linux-hardware.org/?probe=e94b6fbf06) | May 29, 2023 |
| Apple         | MacBookAir7,2               | [2f44574d7c](https://linux-hardware.org/?probe=2f44574d7c) | May 29, 2023 |
| HP            | Laptop 15-dw0xxx            | [a430b5287c](https://linux-hardware.org/?probe=a430b5287c) | May 29, 2023 |
| HP            | Pavilion g4                 | [12bef484db](https://linux-hardware.org/?probe=12bef484db) | May 29, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [14e5763b6f](https://linux-hardware.org/?probe=14e5763b6f) | May 29, 2023 |
| Lenovo        | ThinkPad Edge 0301DCU       | [5b7394bc19](https://linux-hardware.org/?probe=5b7394bc19) | May 28, 2023 |
| Apple         | MacBookAir7,2               | [5e146ef326](https://linux-hardware.org/?probe=5e146ef326) | May 28, 2023 |
| HP            | Pavilion Laptop 14-ce3xx... | [01d3e0d237](https://linux-hardware.org/?probe=01d3e0d237) | May 28, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [1b4eb11af8](https://linux-hardware.org/?probe=1b4eb11af8) | May 28, 2023 |
| Acer          | Aspire A315-41              | [8bdf6722e2](https://linux-hardware.org/?probe=8bdf6722e2) | May 28, 2023 |
| Dell          | Inspiron 3542               | [423fe90cad](https://linux-hardware.org/?probe=423fe90cad) | May 28, 2023 |
| Razer         | Blade 15 Advanced Model ... | [92b96250d1](https://linux-hardware.org/?probe=92b96250d1) | May 28, 2023 |
| Toshiba       | Satellite C850-C5K          | [481789fa1e](https://linux-hardware.org/?probe=481789fa1e) | May 28, 2023 |
| Positivo      | N1250                       | [f014b93eba](https://linux-hardware.org/?probe=f014b93eba) | May 28, 2023 |
| Lenovo        | ThinkPad X240 20AMS1UB1H    | [4147fc8cb7](https://linux-hardware.org/?probe=4147fc8cb7) | May 27, 2023 |
| Dell          | Latitude E6330              | [dd302db25c](https://linux-hardware.org/?probe=dd302db25c) | May 27, 2023 |
| Lenovo        | ThinkPad X240 20AMS1UB1H    | [d9295f37bc](https://linux-hardware.org/?probe=d9295f37bc) | May 27, 2023 |
| Lenovo        | ThinkPad T470 20HES0FA03    | [c8c8087ee8](https://linux-hardware.org/?probe=c8c8087ee8) | May 27, 2023 |
| HP            | Laptop 14s-dk0xxx           | [902b837f1a](https://linux-hardware.org/?probe=902b837f1a) | May 27, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [767c697ac8](https://linux-hardware.org/?probe=767c697ac8) | May 27, 2023 |
| Dell          | Latitude E6330              | [f93b318d71](https://linux-hardware.org/?probe=f93b318d71) | May 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [82cad47c63](https://linux-hardware.org/?probe=82cad47c63) | May 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [09cc59aa19](https://linux-hardware.org/?probe=09cc59aa19) | May 27, 2023 |
| HP            | Laptop 14s-dk0xxx           | [5cf35078b0](https://linux-hardware.org/?probe=5cf35078b0) | May 26, 2023 |
| Acer          | Aspire F5-573G              | [f8ec1083ad](https://linux-hardware.org/?probe=f8ec1083ad) | May 26, 2023 |
| Acer          | Aspire F5-573G              | [eb636c0b30](https://linux-hardware.org/?probe=eb636c0b30) | May 26, 2023 |
| Lenovo        | ThinkPad T460s 20F90058G... | [71a2e90192](https://linux-hardware.org/?probe=71a2e90192) | May 26, 2023 |
| Dell          | XPS 13 9310                 | [689eec8b51](https://linux-hardware.org/?probe=689eec8b51) | May 26, 2023 |
| Notebook      | NV4xPZ                      | [750cb90d83](https://linux-hardware.org/?probe=750cb90d83) | May 26, 2023 |
| Acer          | Aspire V3-551               | [9d609ccd4a](https://linux-hardware.org/?probe=9d609ccd4a) | May 26, 2023 |
| Dell          | Inspiron 15-3567            | [0f79b43742](https://linux-hardware.org/?probe=0f79b43742) | May 26, 2023 |
| Dell          | G15 5525                    | [b2c8f44d8b](https://linux-hardware.org/?probe=b2c8f44d8b) | May 26, 2023 |
| Samsung       | 550XDA                      | [6cc9f3cbe4](https://linux-hardware.org/?probe=6cc9f3cbe4) | May 26, 2023 |
| ASUSTek       | X705UVR                     | [bedbf77e16](https://linux-hardware.org/?probe=bedbf77e16) | May 25, 2023 |
| Lenovo        | ThinkPad T490 20N3S5DQ02    | [bb00a96df8](https://linux-hardware.org/?probe=bb00a96df8) | May 25, 2023 |
| Dell          | Precision 7540              | [99c7b41c6b](https://linux-hardware.org/?probe=99c7b41c6b) | May 25, 2023 |
| Unknown       | Unknown                     | [cfaffcaa0a](https://linux-hardware.org/?probe=cfaffcaa0a) | May 25, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [913f21a49c](https://linux-hardware.org/?probe=913f21a49c) | May 25, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81FN      | [3304e68c39](https://linux-hardware.org/?probe=3304e68c39) | May 25, 2023 |
| ASUSTek       | GL553VD                     | [51dbf3c463](https://linux-hardware.org/?probe=51dbf3c463) | May 25, 2023 |
| Dell          | Vostro 3480                 | [490c47960a](https://linux-hardware.org/?probe=490c47960a) | May 25, 2023 |
| Lenovo        | ThinkPad T440p 20AW0045M... | [355e03f684](https://linux-hardware.org/?probe=355e03f684) | May 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [9294d16ea5](https://linux-hardware.org/?probe=9294d16ea5) | May 25, 2023 |
| Google        | Voxel                       | [9dae4b7464](https://linux-hardware.org/?probe=9dae4b7464) | May 25, 2023 |
| HP            | Victus by Laptop 16-d1xx... | [d03d942df4](https://linux-hardware.org/?probe=d03d942df4) | May 24, 2023 |
| Dell          | Precision 7540              | [65605ee5e8](https://linux-hardware.org/?probe=65605ee5e8) | May 24, 2023 |
| Dell          | Vostro 3480                 | [ae4f8dba2c](https://linux-hardware.org/?probe=ae4f8dba2c) | May 24, 2023 |
| Lenovo        | G500s 20245                 | [dd15a8197e](https://linux-hardware.org/?probe=dd15a8197e) | May 24, 2023 |
| Lenovo        | ThinkPad T530 24297XG       | [520e3d90a6](https://linux-hardware.org/?probe=520e3d90a6) | May 24, 2023 |
| ASUSTek       | UL30A                       | [d7ab3b0ed3](https://linux-hardware.org/?probe=d7ab3b0ed3) | May 24, 2023 |
| ASUSTek       | X542UN                      | [29547f8e99](https://linux-hardware.org/?probe=29547f8e99) | May 24, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [ba72bf9d52](https://linux-hardware.org/?probe=ba72bf9d52) | May 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [64ceddcdd4](https://linux-hardware.org/?probe=64ceddcdd4) | May 24, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [d99af6bab2](https://linux-hardware.org/?probe=d99af6bab2) | May 24, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [fff0e981f2](https://linux-hardware.org/?probe=fff0e981f2) | May 23, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [0dfd1ede62](https://linux-hardware.org/?probe=0dfd1ede62) | May 23, 2023 |
| Dell          | Inspiron 3593               | [715800f05d](https://linux-hardware.org/?probe=715800f05d) | May 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [691b17e221](https://linux-hardware.org/?probe=691b17e221) | May 23, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [eaa5b878d3](https://linux-hardware.org/?probe=eaa5b878d3) | May 23, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | [90235c6d2e](https://linux-hardware.org/?probe=90235c6d2e) | May 23, 2023 |
| MSI           | GF65 Thin 9SE               | [c485674a13](https://linux-hardware.org/?probe=c485674a13) | May 23, 2023 |
| ASUSTek       | N75SF                       | [a385375f4d](https://linux-hardware.org/?probe=a385375f4d) | May 23, 2023 |
| Dell          | G5 5587                     | [18faf1497f](https://linux-hardware.org/?probe=18faf1497f) | May 23, 2023 |
| Apple         | MacBookPro8,1               | [fadd25f4c5](https://linux-hardware.org/?probe=fadd25f4c5) | May 23, 2023 |
| Lenovo        | ThinkPad E495 20NE001GMX    | [cc966f1ede](https://linux-hardware.org/?probe=cc966f1ede) | May 23, 2023 |
| Lenovo        | Legion Y7000P IAH7 82RC     | [c4040a0905](https://linux-hardware.org/?probe=c4040a0905) | May 23, 2023 |
| Lenovo        | ThinkPad T420 4180Q3U       | [56042328ac](https://linux-hardware.org/?probe=56042328ac) | May 23, 2023 |
| Lenovo        | ThinkPad T420 4180Q3U       | [0d63b518e4](https://linux-hardware.org/?probe=0d63b518e4) | May 23, 2023 |
| ASUSTek       | ET2321I                     | [829fe9b078](https://linux-hardware.org/?probe=829fe9b078) | May 23, 2023 |
| Dell          | Precision 7540              | [95bbab11f1](https://linux-hardware.org/?probe=95bbab11f1) | May 23, 2023 |
| UNOWHY        | Y13G011S4EI                 | [3642f34cd6](https://linux-hardware.org/?probe=3642f34cd6) | May 23, 2023 |
| Lenovo        | ThinkPad L480 20LTA01LLM    | [ed45fc495a](https://linux-hardware.org/?probe=ed45fc495a) | May 22, 2023 |
| HP            | EliteBook 840 G5            | [74a0ea4304](https://linux-hardware.org/?probe=74a0ea4304) | May 22, 2023 |
| Lenovo        | ThinkPad T490s 20NYS7K91... | [7d81e00b27](https://linux-hardware.org/?probe=7d81e00b27) | May 22, 2023 |
| Framework     | Laptop                      | [7715f5f056](https://linux-hardware.org/?probe=7715f5f056) | May 22, 2023 |
| Apple         | MacBookPro5,5               | [a4b0d5fd13](https://linux-hardware.org/?probe=a4b0d5fd13) | May 22, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | [c492073bac](https://linux-hardware.org/?probe=c492073bac) | May 22, 2023 |
| Dell          | Precision 5560              | [1fc79f4cc0](https://linux-hardware.org/?probe=1fc79f4cc0) | May 22, 2023 |
| MSI           | Modern 14 B11MOL            | [7bc8f5e875](https://linux-hardware.org/?probe=7bc8f5e875) | May 21, 2023 |
| Micro Elec... | MG-VCP17I-3070              | [8c8c77d9a3](https://linux-hardware.org/?probe=8c8c77d9a3) | May 21, 2023 |
| HP            | Laptop 15-dy5xxx            | [3ab3a101e8](https://linux-hardware.org/?probe=3ab3a101e8) | May 21, 2023 |
| Lenovo        | ThinkPad T460s 20FAS0W90... | [0b3265b088](https://linux-hardware.org/?probe=0b3265b088) | May 21, 2023 |
| ASUSTek       | ZenBook UX425JA_UX425JA     | [916d381f2f](https://linux-hardware.org/?probe=916d381f2f) | May 21, 2023 |
| Dell          | XPS 13 9310                 | [19be933f8a](https://linux-hardware.org/?probe=19be933f8a) | May 21, 2023 |
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
| Lenovo        | ThinkPad T61 6463B45        | [a2445821f3](https://linux-hardware.org/?probe=a2445821f3) | May 19, 2023 |
| Google        | Candy                       | [2ed0555d82](https://linux-hardware.org/?probe=2ed0555d82) | May 19, 2023 |
| Lenovo        | ThinkPad P52 20MAS88000     | [f9a256566b](https://linux-hardware.org/?probe=f9a256566b) | May 19, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [7f2ca00e36](https://linux-hardware.org/?probe=7f2ca00e36) | May 18, 2023 |
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
| Dell          | XPS 15 9560                 | [d0a6a8e29e](https://linux-hardware.org/?probe=d0a6a8e29e) | May 14, 2023 |
| ASUSTek       | X510UQR                     | [2062004d5f](https://linux-hardware.org/?probe=2062004d5f) | May 14, 2023 |
| HP            | Compaq Presario CQ40        | [22d379cd2f](https://linux-hardware.org/?probe=22d379cd2f) | May 13, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | [0f3a2fae1b](https://linux-hardware.org/?probe=0f3a2fae1b) | May 13, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | [4a322b398b](https://linux-hardware.org/?probe=4a322b398b) | May 13, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | [d251ccd249](https://linux-hardware.org/?probe=d251ccd249) | May 13, 2023 |
| ASUSTek       | GL502VMK                    | [0b7232826d](https://linux-hardware.org/?probe=0b7232826d) | May 13, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [1e5caac049](https://linux-hardware.org/?probe=1e5caac049) | May 13, 2023 |
| Dell          | Latitude 7490               | [16cfe08da3](https://linux-hardware.org/?probe=16cfe08da3) | May 13, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [804de32208](https://linux-hardware.org/?probe=804de32208) | May 13, 2023 |
| GPU Compan... | GWTN156-11                  | [afb2844cb4](https://linux-hardware.org/?probe=afb2844cb4) | May 13, 2023 |
| ASUSTek       | K53SV                       | [60d7b5acf8](https://linux-hardware.org/?probe=60d7b5acf8) | May 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [a7e9891909](https://linux-hardware.org/?probe=a7e9891909) | May 12, 2023 |
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
| HP            | 250 G6 Notebook PC          | [a7cc3561af](https://linux-hardware.org/?probe=a7cc3561af) | May 10, 2023 |
| Lenovo        | ThinkPad X220 42911H8       | [d6933984d7](https://linux-hardware.org/?probe=d6933984d7) | May 10, 2023 |
| Lenovo        | ThinkPad X220 42911H8       | [6beb57f72d](https://linux-hardware.org/?probe=6beb57f72d) | May 10, 2023 |
| Lenovo        | ThinkPad T480 20L50018US    | [b98dfd1940](https://linux-hardware.org/?probe=b98dfd1940) | May 10, 2023 |
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
| Dell          | Inspiron 3442               | [e858474ff0](https://linux-hardware.org/?probe=e858474ff0) | May 09, 2023 |
| HP            | EliteBook 840 14 inch G9... | [a3e5adab46](https://linux-hardware.org/?probe=a3e5adab46) | May 08, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [205b8a8ca7](https://linux-hardware.org/?probe=205b8a8ca7) | May 08, 2023 |
| HP            | EliteBook 8740w             | [29d129229b](https://linux-hardware.org/?probe=29d129229b) | May 08, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [8bbe8f0a3f](https://linux-hardware.org/?probe=8bbe8f0a3f) | May 08, 2023 |
| Avell High... | A65 MOB                     | [d6c6781535](https://linux-hardware.org/?probe=d6c6781535) | May 08, 2023 |
| Dell          | Latitude E7450              | [0eff8f87c6](https://linux-hardware.org/?probe=0eff8f87c6) | May 08, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [75fe05267b](https://linux-hardware.org/?probe=75fe05267b) | May 08, 2023 |
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
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b8933c29ce](https://linux-hardware.org/?probe=b8933c29ce) | May 04, 2023 |
| HUAWEI        | RLEF-XX                     | [f4964352ac](https://linux-hardware.org/?probe=f4964352ac) | May 04, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [fbc24a91e6](https://linux-hardware.org/?probe=fbc24a91e6) | May 04, 2023 |
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
| HP            | Dragonfly Pro               | [365260c678](https://linux-hardware.org/?probe=365260c678) | May 01, 2023 |
| HP            | Dragonfly Pro               | [89a652fc25](https://linux-hardware.org/?probe=89a652fc25) | May 01, 2023 |
| HP            | 255 G4                      | [b06ddec94b](https://linux-hardware.org/?probe=b06ddec94b) | May 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [ed2a323b49](https://linux-hardware.org/?probe=ed2a323b49) | May 01, 2023 |
| ASUSTek       | X401A1                      | [2a7d35cc4e](https://linux-hardware.org/?probe=2a7d35cc4e) | May 01, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [c604e4ce30](https://linux-hardware.org/?probe=c604e4ce30) | May 01, 2023 |
| HUAWEI        | HVY-WXX9                    | [c5c9bbda3d](https://linux-hardware.org/?probe=c5c9bbda3d) | May 01, 2023 |
| Notebook      | NS5x_NS7xPU                 | [ee97e0f5f0](https://linux-hardware.org/?probe=ee97e0f5f0) | May 01, 2023 |
| HP            | Compaq 6910p                | [a697e756f5](https://linux-hardware.org/?probe=a697e756f5) | May 01, 2023 |
| Dell          | Inspiron 14 5420            | [cc65b3de6f](https://linux-hardware.org/?probe=cc65b3de6f) | May 01, 2023 |
| Valve         | Jupiter                     | [07ef050535](https://linux-hardware.org/?probe=07ef050535) | May 01, 2023 |
| HP            | Laptop 15z-fc000            | [7b57cc42a0](https://linux-hardware.org/?probe=7b57cc42a0) | May 01, 2023 |
| HP            | ElitePad 1000 G2            | [8ae27e00f6](https://linux-hardware.org/?probe=8ae27e00f6) | May 01, 2023 |
| HUAWEI        | CREM-WXX9                   | [ba99960d5f](https://linux-hardware.org/?probe=ba99960d5f) | May 01, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | [a7d6d782b2](https://linux-hardware.org/?probe=a7d6d782b2) | May 01, 2023 |
| Lenovo        | IdeaPad S340-15IWLTouch ... | [6857a16a6c](https://linux-hardware.org/?probe=6857a16a6c) | Apr 30, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [0784fc9b1c](https://linux-hardware.org/?probe=0784fc9b1c) | Apr 30, 2023 |
| HP            | Notebook                    | [fd6aa4aeb6](https://linux-hardware.org/?probe=fd6aa4aeb6) | Apr 30, 2023 |
| VIOS          | LTH17                       | [4d1a86ee61](https://linux-hardware.org/?probe=4d1a86ee61) | Apr 30, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [9c07454907](https://linux-hardware.org/?probe=9c07454907) | Apr 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [43a167afad](https://linux-hardware.org/?probe=43a167afad) | Apr 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [0ae3fb5506](https://linux-hardware.org/?probe=0ae3fb5506) | Apr 30, 2023 |
| Lenovo        | ThinkPad T490s 20NX002SG... | [874f19f26e](https://linux-hardware.org/?probe=874f19f26e) | Apr 30, 2023 |
| Acer          | Nitro AN515-45              | [9b28e69254](https://linux-hardware.org/?probe=9b28e69254) | Apr 30, 2023 |
| Framework     | Laptop                      | [84b3b9547b](https://linux-hardware.org/?probe=84b3b9547b) | Apr 29, 2023 |
| Dell          | XPS 13 7390                 | [b976cc9656](https://linux-hardware.org/?probe=b976cc9656) | Apr 29, 2023 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [6f6a016997](https://linux-hardware.org/?probe=6f6a016997) | Apr 29, 2023 |
| Lenovo        | ThinkPad T550 20CKA00ECD    | [2545d9dd31](https://linux-hardware.org/?probe=2545d9dd31) | Apr 29, 2023 |
| HUAWEI        | CREM-WXX9                   | [c17b468722](https://linux-hardware.org/?probe=c17b468722) | Apr 29, 2023 |
| Chuwi         | HeroBook Air                | [123f6df9f8](https://linux-hardware.org/?probe=123f6df9f8) | Apr 29, 2023 |
| Insyde        | CherryTrail                 | [a9f658c8af](https://linux-hardware.org/?probe=a9f658c8af) | Apr 29, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [cd266d7680](https://linux-hardware.org/?probe=cd266d7680) | Apr 29, 2023 |
| Acer          | Nitro AN515-58              | [2c335c5bfb](https://linux-hardware.org/?probe=2c335c5bfb) | Apr 29, 2023 |
| Google        | Banon                       | [c21a57806c](https://linux-hardware.org/?probe=c21a57806c) | Apr 29, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [e70d66b3ba](https://linux-hardware.org/?probe=e70d66b3ba) | Apr 29, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [2aa69de3ca](https://linux-hardware.org/?probe=2aa69de3ca) | Apr 29, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [4de963cbc6](https://linux-hardware.org/?probe=4de963cbc6) | Apr 28, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [d8af950fd8](https://linux-hardware.org/?probe=d8af950fd8) | Apr 28, 2023 |
| Acer          | Aspire E5-571               | [1d36dafa86](https://linux-hardware.org/?probe=1d36dafa86) | Apr 28, 2023 |
| Dell          | Precision 3551              | [99ff11c325](https://linux-hardware.org/?probe=99ff11c325) | Apr 28, 2023 |
| Lenovo        | ThinkPad T470p 20J60018M... | [a8deb2307c](https://linux-hardware.org/?probe=a8deb2307c) | Apr 28, 2023 |
| Dell          | Precision 3551              | [93a38e7384](https://linux-hardware.org/?probe=93a38e7384) | Apr 28, 2023 |
| Lenovo        | ThinkPad X260 20F5S56G00    | [8da21e9a17](https://linux-hardware.org/?probe=8da21e9a17) | Apr 28, 2023 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [5cb9fe1ae9](https://linux-hardware.org/?probe=5cb9fe1ae9) | Apr 28, 2023 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [3669ef1de9](https://linux-hardware.org/?probe=3669ef1de9) | Apr 28, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [b5a953a984](https://linux-hardware.org/?probe=b5a953a984) | Apr 28, 2023 |
| HP            | ProBook 455 15.6 inch G9... | [1cfc210ce1](https://linux-hardware.org/?probe=1cfc210ce1) | Apr 28, 2023 |
| Acer          | Nitro AN515-54              | [000022b2dd](https://linux-hardware.org/?probe=000022b2dd) | Apr 28, 2023 |
| Sony          | VPCEG23EL                   | [c28e3338ce](https://linux-hardware.org/?probe=c28e3338ce) | Apr 28, 2023 |
| Lenovo        | Legion 7-16-ITHg6 82K6      | [2baf2cbc85](https://linux-hardware.org/?probe=2baf2cbc85) | Apr 27, 2023 |
| ASUSTek       | Zephyrus M GU502GW_GU502... | [94d9250bc1](https://linux-hardware.org/?probe=94d9250bc1) | Apr 27, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [854cf327d8](https://linux-hardware.org/?probe=854cf327d8) | Apr 27, 2023 |
| HUAWEI        | HVY-WXX9                    | [dd5391c20d](https://linux-hardware.org/?probe=dd5391c20d) | Apr 27, 2023 |
| HP            | Laptop 17-ak0xx             | [6eed1fda15](https://linux-hardware.org/?probe=6eed1fda15) | Apr 27, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | [4cd1484039](https://linux-hardware.org/?probe=4cd1484039) | Apr 27, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | [0796e35c73](https://linux-hardware.org/?probe=0796e35c73) | Apr 27, 2023 |
| Dell          | XPS 15 9500                 | [a7cc631b80](https://linux-hardware.org/?probe=a7cc631b80) | Apr 27, 2023 |
| Timi          | Redmi Book Pro 14 2022      | [dcc8c22535](https://linux-hardware.org/?probe=dcc8c22535) | Apr 27, 2023 |
| Dell          | Vostro 15 3515              | [f58ab8b9c4](https://linux-hardware.org/?probe=f58ab8b9c4) | Apr 27, 2023 |
| Lenovo        | ThinkPad X270 20HN001HUS    | [3f6586f0d1](https://linux-hardware.org/?probe=3f6586f0d1) | Apr 27, 2023 |
| Lenovo        | ThinkPad T480s 20L8S45W0... | [0e8490c41f](https://linux-hardware.org/?probe=0e8490c41f) | Apr 27, 2023 |
| ASUSTek       | Zephyrus M GU502GW_GU502... | [67c865f449](https://linux-hardware.org/?probe=67c865f449) | Apr 27, 2023 |
| Acer          | Aspire A315-54              | [8137aa9008](https://linux-hardware.org/?probe=8137aa9008) | Apr 27, 2023 |
| HP            | EliteBook 630 13 inch G9... | [96bd4f8398](https://linux-hardware.org/?probe=96bd4f8398) | Apr 27, 2023 |
| Apple         | MacBookAir6,1               | [c0f967c0bc](https://linux-hardware.org/?probe=c0f967c0bc) | Apr 27, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [c443269a81](https://linux-hardware.org/?probe=c443269a81) | Apr 26, 2023 |
| ASUSTek       | ROG Strix G512LW_G512LW     | [a950f656f7](https://linux-hardware.org/?probe=a950f656f7) | Apr 26, 2023 |
| Timi          | TM1703                      | [7e6b948ea9](https://linux-hardware.org/?probe=7e6b948ea9) | Apr 26, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [96006a1098](https://linux-hardware.org/?probe=96006a1098) | Apr 26, 2023 |
| HUAWEI        | KLVL-WXXW                   | [de95ac0857](https://linux-hardware.org/?probe=de95ac0857) | Apr 26, 2023 |
| HUAWEI        | KLVL-WXXW                   | [07906a30e3](https://linux-hardware.org/?probe=07906a30e3) | Apr 26, 2023 |
| Dell          | Latitude 5520               | [7ee153b691](https://linux-hardware.org/?probe=7ee153b691) | Apr 26, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [86ba8ccc07](https://linux-hardware.org/?probe=86ba8ccc07) | Apr 26, 2023 |
| Lenovo        | ThinkPad T480s 20L8002WM... | [82bd4b0d20](https://linux-hardware.org/?probe=82bd4b0d20) | Apr 26, 2023 |
| Dell          | Latitude 5520               | [3071d4a9d8](https://linux-hardware.org/?probe=3071d4a9d8) | Apr 26, 2023 |
| Dell          | Latitude 5520               | [23fe32affd](https://linux-hardware.org/?probe=23fe32affd) | Apr 26, 2023 |
| Acer          | Swift SF114-32              | [13d7dc019c](https://linux-hardware.org/?probe=13d7dc019c) | Apr 26, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [a3df65a55c](https://linux-hardware.org/?probe=a3df65a55c) | Apr 26, 2023 |
| Razer         | Blade                       | [b170226896](https://linux-hardware.org/?probe=b170226896) | Apr 25, 2023 |
| Dell          | Inspiron 5748               | [dd4d50839d](https://linux-hardware.org/?probe=dd4d50839d) | Apr 25, 2023 |
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
| LDLC          | SPC-I                       | [899fb46a02](https://linux-hardware.org/?probe=899fb46a02) | Apr 25, 2023 |
| Chuwi         | GemiBook Pro                | [1287b17594](https://linux-hardware.org/?probe=1287b17594) | Apr 25, 2023 |
| Dell          | G3 3500                     | [46996524d0](https://linux-hardware.org/?probe=46996524d0) | Apr 25, 2023 |
| Dell          | XPS 13 9380                 | [290a99fee9](https://linux-hardware.org/?probe=290a99fee9) | Apr 25, 2023 |
| Lenovo        | Legion 5 17IMH05 82B3       | [2e542c241d](https://linux-hardware.org/?probe=2e542c241d) | Apr 25, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [0db2c54b2a](https://linux-hardware.org/?probe=0db2c54b2a) | Apr 24, 2023 |
| Dell          | Latitude 5580               | [a153ad5277](https://linux-hardware.org/?probe=a153ad5277) | Apr 24, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [de3ad583ab](https://linux-hardware.org/?probe=de3ad583ab) | Apr 24, 2023 |
| HP            | Laptop 15s-eq2xxx           | [699adff825](https://linux-hardware.org/?probe=699adff825) | Apr 24, 2023 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | [e028b13685](https://linux-hardware.org/?probe=e028b13685) | Apr 24, 2023 |
| Dell          | Vostro 5402                 | [b6cb9c9140](https://linux-hardware.org/?probe=b6cb9c9140) | Apr 24, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [d805c85a12](https://linux-hardware.org/?probe=d805c85a12) | Apr 24, 2023 |
| HP            | Laptop 14-cm0xxx            | [4591d1bf9d](https://linux-hardware.org/?probe=4591d1bf9d) | Apr 24, 2023 |
| Dell          | Latitude 9520               | [0ab9a83db6](https://linux-hardware.org/?probe=0ab9a83db6) | Apr 23, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [696ee85cc9](https://linux-hardware.org/?probe=696ee85cc9) | Apr 23, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [43aae4850b](https://linux-hardware.org/?probe=43aae4850b) | Apr 23, 2023 |
| Dynabook      | PORTEGE X30L-K              | [da178b8987](https://linux-hardware.org/?probe=da178b8987) | Apr 23, 2023 |
| HP            | Laptop 15-bs2xx             | [c40dac306c](https://linux-hardware.org/?probe=c40dac306c) | Apr 23, 2023 |
| ASUSTek       | X510UAR                     | [3321ccb912](https://linux-hardware.org/?probe=3321ccb912) | Apr 23, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [9a6f040039](https://linux-hardware.org/?probe=9a6f040039) | Apr 23, 2023 |
| Lenovo        | ThinkPad T495 20NJ000XGE    | [155072c012](https://linux-hardware.org/?probe=155072c012) | Apr 23, 2023 |
| Dell          | Latitude E6520              | [a8b5c5c3ad](https://linux-hardware.org/?probe=a8b5c5c3ad) | Apr 23, 2023 |
| Acer          | Aspire A514-55              | [d98f78cc01](https://linux-hardware.org/?probe=d98f78cc01) | Apr 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [9a92345b08](https://linux-hardware.org/?probe=9a92345b08) | Apr 23, 2023 |
| Lenovo        | ThinkPad X220 4291WSH       | [5a626f5754](https://linux-hardware.org/?probe=5a626f5754) | Apr 23, 2023 |
| Dell          | Latitude E6430              | [e844bce31c](https://linux-hardware.org/?probe=e844bce31c) | Apr 23, 2023 |
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
| ASUSTek       | VivoBook_ASUSLaptop X415... | [901b3d11dc](https://linux-hardware.org/?probe=901b3d11dc) | Apr 20, 2023 |
| Acer          | Swift SF314-511             | [96fd44e94a](https://linux-hardware.org/?probe=96fd44e94a) | Apr 20, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [3219512811](https://linux-hardware.org/?probe=3219512811) | Apr 20, 2023 |
| Dell          | XPS 13 9310                 | [55685c168f](https://linux-hardware.org/?probe=55685c168f) | Apr 20, 2023 |
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
| Dell          | XPS 13 7390                 | [357c45c81c](https://linux-hardware.org/?probe=357c45c81c) | Apr 19, 2023 |
| Apple         | MacBookAir6,1               | [5a600ce01b](https://linux-hardware.org/?probe=5a600ce01b) | Apr 19, 2023 |
| HUAWEI        | NBD-WXX9                    | [a55a03e648](https://linux-hardware.org/?probe=a55a03e648) | Apr 19, 2023 |
| PC Special... | PCx0Dx                      | [0f82987a84](https://linux-hardware.org/?probe=0f82987a84) | Apr 18, 2023 |
| Toshiba       | Kronos 10CUG                | [228e28e6a8](https://linux-hardware.org/?probe=228e28e6a8) | Apr 18, 2023 |
| Dell          | G5 5590                     | [c7334114be](https://linux-hardware.org/?probe=c7334114be) | Apr 18, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | [3b3f4afdd8](https://linux-hardware.org/?probe=3b3f4afdd8) | Apr 18, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [0ec2388253](https://linux-hardware.org/?probe=0ec2388253) | Apr 18, 2023 |
| HUAWEI        | RLEF-XX                     | [b425e2afaf](https://linux-hardware.org/?probe=b425e2afaf) | Apr 18, 2023 |
| ASUSTek       | GL502VML                    | [7c65476ce9](https://linux-hardware.org/?probe=7c65476ce9) | Apr 18, 2023 |
| HP            | Pavilion x2 Detachable      | [5d56d95ea5](https://linux-hardware.org/?probe=5d56d95ea5) | Apr 18, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [a196246f09](https://linux-hardware.org/?probe=a196246f09) | Apr 17, 2023 |
| Dell          | XPS 15 9500                 | [1a55ffc593](https://linux-hardware.org/?probe=1a55ffc593) | Apr 17, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [5e265fd8e1](https://linux-hardware.org/?probe=5e265fd8e1) | Apr 16, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [3ea28c33c9](https://linux-hardware.org/?probe=3ea28c33c9) | Apr 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [391b43ba8c](https://linux-hardware.org/?probe=391b43ba8c) | Apr 16, 2023 |
| Apple         | MacBookAir7,2               | [ed6f18d5ab](https://linux-hardware.org/?probe=ed6f18d5ab) | Apr 16, 2023 |
| Apple         | MacBookAir7,2               | [82509b267d](https://linux-hardware.org/?probe=82509b267d) | Apr 16, 2023 |
| ASUSTek       | TUF Gaming FX505DU_TUF50... | [91d7747b6f](https://linux-hardware.org/?probe=91d7747b6f) | Apr 14, 2023 |
| ASUSTek       | TUF Gaming FX505DU_TUF50... | [59b4139974](https://linux-hardware.org/?probe=59b4139974) | Apr 14, 2023 |
| Dell          | Latitude 7400               | [0f917420a1](https://linux-hardware.org/?probe=0f917420a1) | Apr 14, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [cc0b87e611](https://linux-hardware.org/?probe=cc0b87e611) | Apr 13, 2023 |
| HUAWEI        | KLVL-WXX9                   | [3166746b52](https://linux-hardware.org/?probe=3166746b52) | Apr 12, 2023 |
| Lenovo        | ThinkPad X220 42911H8       | [7eee4a859e](https://linux-hardware.org/?probe=7eee4a859e) | Apr 12, 2023 |
| Lenovo        | ThinkPad X220 42911H8       | [874513db8d](https://linux-hardware.org/?probe=874513db8d) | Apr 12, 2023 |
| ASUSTek       | ROG Strix G713QR_G713QR     | [65bb44978f](https://linux-hardware.org/?probe=65bb44978f) | Apr 12, 2023 |
| MSI           | Prestige 14Evo B13M         | [f1cafa77dd](https://linux-hardware.org/?probe=f1cafa77dd) | Apr 12, 2023 |
| HUAWEI        | KLVL-WXX9                   | [52e50e17de](https://linux-hardware.org/?probe=52e50e17de) | Apr 11, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | [69f8d7dfdf](https://linux-hardware.org/?probe=69f8d7dfdf) | Apr 11, 2023 |
| ASUSTek       | GL552VW                     | [396850fd22](https://linux-hardware.org/?probe=396850fd22) | Apr 09, 2023 |
| Google        | Bluebird                    | [6ab22238ac](https://linux-hardware.org/?probe=6ab22238ac) | Apr 07, 2023 |
| HP            | Sona                        | [64fa63647b](https://linux-hardware.org/?probe=64fa63647b) | Apr 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [0af2f7cc7f](https://linux-hardware.org/?probe=0af2f7cc7f) | Apr 05, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | [36338ecf6e](https://linux-hardware.org/?probe=36338ecf6e) | Apr 05, 2023 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [8982660d51](https://linux-hardware.org/?probe=8982660d51) | Apr 05, 2023 |
| Apple         | MacBookPro9,2               | [f4343acc49](https://linux-hardware.org/?probe=f4343acc49) | Apr 03, 2023 |
| Apple         | MacBookPro9,2               | [3e558165a4](https://linux-hardware.org/?probe=3e558165a4) | Apr 02, 2023 |
| Lenovo        | ThinkPad E495 20NE001RTX    | [804bf25c27](https://linux-hardware.org/?probe=804bf25c27) | Apr 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [95c5f574c9](https://linux-hardware.org/?probe=95c5f574c9) | Apr 01, 2023 |
| Dell          | Latitude E5450              | [89701abaa1](https://linux-hardware.org/?probe=89701abaa1) | Apr 01, 2023 |
| Acer          | Swift SF113-31              | [fc0539603c](https://linux-hardware.org/?probe=fc0539603c) | Mar 31, 2023 |
| Exo           | Smart XL4                   | [6421142cb6](https://linux-hardware.org/?probe=6421142cb6) | Mar 31, 2023 |
| Dell          | Inspiron 15 5510            | [162132b606](https://linux-hardware.org/?probe=162132b606) | Mar 30, 2023 |
| Toshiba       | Satellite C850-C5K          | [8fc7451def](https://linux-hardware.org/?probe=8fc7451def) | Mar 30, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [c73c5374a4](https://linux-hardware.org/?probe=c73c5374a4) | Mar 30, 2023 |
| Lenovo        | ThinkPad T470s 20HGS07D0... | [7a8b075b23](https://linux-hardware.org/?probe=7a8b075b23) | Mar 29, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [d74490158e](https://linux-hardware.org/?probe=d74490158e) | Mar 29, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [19efb75aa1](https://linux-hardware.org/?probe=19efb75aa1) | Mar 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [85accc79b1](https://linux-hardware.org/?probe=85accc79b1) | Mar 23, 2023 |
| HUAWEI        | KPL-W0X                     | [80e6d9af10](https://linux-hardware.org/?probe=80e6d9af10) | Mar 22, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QH... | [883d4de906](https://linux-hardware.org/?probe=883d4de906) | Mar 21, 2023 |
| Acer          | Aspire 5935                 | [0634ed91ba](https://linux-hardware.org/?probe=0634ed91ba) | Mar 19, 2023 |
| HIPER         | WORKBOOK                    | [ed14fd6e80](https://linux-hardware.org/?probe=ed14fd6e80) | Mar 17, 2023 |
| Dell          | Latitude E6430              | [e48fceb5f2](https://linux-hardware.org/?probe=e48fceb5f2) | Mar 16, 2023 |
| MSI           | Modern 14 B11MOL            | [33bbc272c0](https://linux-hardware.org/?probe=33bbc272c0) | Mar 15, 2023 |
| Toshiba       | Satellite P870              | [113fcf770d](https://linux-hardware.org/?probe=113fcf770d) | Mar 15, 2023 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | [59d7fa9a34](https://linux-hardware.org/?probe=59d7fa9a34) | Mar 15, 2023 |
| HIPER         | WORKBOOK                    | [3d1c928bcb](https://linux-hardware.org/?probe=3d1c928bcb) | Mar 15, 2023 |
| Lenovo        | ThinkPad 11e 3rd Gen 20G... | [1e037723cc](https://linux-hardware.org/?probe=1e037723cc) | Mar 12, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S0S... | [2e864ba25e](https://linux-hardware.org/?probe=2e864ba25e) | Mar 08, 2023 |
| Clevo         | W25xHNx                     | [5227127f81](https://linux-hardware.org/?probe=5227127f81) | Mar 03, 2023 |
| HP            | EliteBook 840 G6            | [ea6777bf2d](https://linux-hardware.org/?probe=ea6777bf2d) | Feb 23, 2023 |
| Apple         | MacBookPro11,3              | [b0ffb00d43](https://linux-hardware.org/?probe=b0ffb00d43) | Feb 10, 2023 |
| MACHENIKE     | MACHCREATOR-16              | [4608209d2d](https://linux-hardware.org/?probe=4608209d2d) | Feb 03, 2023 |
| MACHENIKE     | MACHCREATOR-16              | [81e773eade](https://linux-hardware.org/?probe=81e773eade) | Feb 02, 2023 |
| MACHENIKE     | MACHCREATOR-16              | [c44c077d1e](https://linux-hardware.org/?probe=c44c077d1e) | Jan 30, 2023 |
| MACHENIKE     | MACHCREATOR-16              | [e3d7c03a2e](https://linux-hardware.org/?probe=e3d7c03a2e) | Jan 29, 2023 |
| HUAWEI        | MACH-WX9                    | [5b00f79b72](https://linux-hardware.org/?probe=5b00f79b72) | Jan 28, 2023 |
| MACHENIKE     | MACHCREATOR-16              | [7b3107564a](https://linux-hardware.org/?probe=7b3107564a) | Jan 23, 2023 |
| MACHENIKE     | MACHCREATOR-16              | [6b370a283e](https://linux-hardware.org/?probe=6b370a283e) | Jan 23, 2023 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [aa6ca0d358](https://linux-hardware.org/?probe=aa6ca0d358) | Jan 17, 2023 |
| HP            | ZBook Fury 15 G7 Mobile ... | [2b8c216e1a](https://linux-hardware.org/?probe=2b8c216e1a) | Jan 08, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [cedce58f23](https://linux-hardware.org/?probe=cedce58f23) | Dec 27, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [0e063e5fd5](https://linux-hardware.org/?probe=0e063e5fd5) | Dec 27, 2022 |
| Dell          | XPS 15 9570                 | [ce6ac8ec7f](https://linux-hardware.org/?probe=ce6ac8ec7f) | Dec 16, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [091e12e551](https://linux-hardware.org/?probe=091e12e551) | Dec 08, 2022 |
| Acer          | Aspire V3-571               | [ab9e6cc193](https://linux-hardware.org/?probe=ab9e6cc193) | Nov 27, 2022 |
| Acer          | Aspire V3-571               | [a4d6ce5fa1](https://linux-hardware.org/?probe=a4d6ce5fa1) | Nov 27, 2022 |
| Acer          | Aspire V3-571               | [7aa6773734](https://linux-hardware.org/?probe=7aa6773734) | Nov 16, 2022 |
| Acer          | Aspire V3-571               | [d5c4a2f02e](https://linux-hardware.org/?probe=d5c4a2f02e) | Nov 16, 2022 |
| Unknown       | Unknown                     | [1e27521b13](https://linux-hardware.org/?probe=1e27521b13) | Sep 17, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Fedora_38/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                                          | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| 6.2.15-300.fc38.x86_64                                           | 134       | 23.06%  |
| 6.2.14-300.fc38.x86_64                                           | 90        | 15.49%  |
| 6.2.11-300.fc38.x86_64                                           | 87        | 14.97%  |
| 6.2.9-300.fc38.x86_64                                            | 55        | 9.47%   |
| 6.2.13-300.fc38.x86_64                                           | 46        | 7.92%   |
| 6.3.5-200.fc38.x86_64                                            | 41        | 7.06%   |
| 6.2.12-300.fc38.x86_64                                           | 32        | 5.51%   |
| 6.3.4-201.fc38.x86_64                                            | 24        | 4.13%   |
| 6.3.6-200.fc38.x86_64                                            | 11        | 1.89%   |
| 6.2.8-300.fc38.x86_64                                            | 9         | 1.55%   |
| 6.2.10-300.fc38.x86_64                                           | 7         | 1.2%    |
| 6.2.6-300.fc38.x86_64                                            | 6         | 1.03%   |
| 6.2.7-300.fc38.x86_64                                            | 3         | 0.52%   |
| 6.4.0-0.rc4.334.vanilla.fc38.x86_64                              | 2         | 0.34%   |
| 6.2.2-301.fc38.x86_64                                            | 2         | 0.34%   |
| 6.2.15-703.inttf.fc38.x86_64                                     | 2         | 0.34%   |
| 6.2.11-703.inttf.fc38.x86_64                                     | 2         | 0.34%   |
| 6.2.0-63.fc38.x86_64                                             | 2         | 0.34%   |
| 6.3.6-cb1.0.fc38.x86_64                                          | 1         | 0.17%   |
| 6.3.3-cb1.0.fc38.x86_64                                          | 1         | 0.17%   |
| 6.3.3-200.fc38.x86_64                                            | 1         | 0.17%   |
| 6.3.2-cbl1.0.fc38.x86_64                                         | 1         | 0.17%   |
| 6.3.1-cb3.0.fc38.x86_64                                          | 1         | 0.17%   |
| 6.3.1-350.vanilla.fc38.x86_64                                    | 1         | 0.17%   |
| 6.3.0+                                                           | 1         | 0.17%   |
| 6.2.5-300.fc38.x86_64                                            | 1         | 0.17%   |
| 6.2.2-300.fc38.x86_64                                            | 1         | 0.17%   |
| 6.2.15-200.fc37.x86_64                                           | 1         | 0.17%   |
| 6.2.14-703.inttf.fc38.x86_64                                     | 1         | 0.17%   |
| 6.2.14-450.asahi.fc38.aarch64                                    | 1         | 0.17%   |
| 6.2.10-300.rog.fc38.x86_64                                       | 1         | 0.17%   |
| 6.2.0-rc1-1b929c02afd37871d5afb9d498426f83432e71c2-btrfs-debug4+ | 1         | 0.17%   |
| 6.2.0-0.rc7.20230208git0983f6bf2bfc.52.fc38.x86_64               | 1         | 0.17%   |
| 6.2.0-0.rc5.20230126git7c46948a6e9c.41.fc38.x86_64               | 1         | 0.17%   |
| 6.2.0-0.rc4.20230120gitd368967cb103.35.fc38.x86_64               | 1         | 0.17%   |
| 6.2.0-0.rc3.20230113gitd9fc1511728c.28.fc38.x86_64               | 1         | 0.17%   |
| 6.2.0-0.rc2.20230105git41c03ba9beea.20.fc38.x86_64               | 1         | 0.17%   |
| 6.1.26-200.fc38.x86_64                                           | 1         | 0.17%   |
| 6.1.0-65.fc38.x86_64                                             | 1         | 0.17%   |
| 6.1.0-0.rc5.39.fc38.x86_64                                       | 1         | 0.17%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2.15  | 137       | 23.58%  |
| 6.2.14  | 92        | 15.83%  |
| 6.2.11  | 89        | 15.32%  |
| 6.2.9   | 55        | 9.47%   |
| 6.2.13  | 46        | 7.92%   |
| 6.3.5   | 41        | 7.06%   |
| 6.2.12  | 32        | 5.51%   |
| 6.3.4   | 24        | 4.13%   |
| 6.3.6   | 12        | 2.07%   |
| 6.2.8   | 9         | 1.55%   |
| 6.2.10  | 8         | 1.38%   |
| 6.2.0   | 8         | 1.38%   |
| 6.2.6   | 6         | 1.03%   |
| 6.2.7   | 3         | 0.52%   |
| 6.2.2   | 3         | 0.52%   |
| 6.4.0   | 2         | 0.34%   |
| 6.3.3   | 2         | 0.34%   |
| 6.3.1   | 2         | 0.34%   |
| 6.1.0   | 2         | 0.34%   |
| 6.3.2   | 1         | 0.17%   |
| 6.3.0   | 1         | 0.17%   |
| 6.2.5   | 1         | 0.17%   |
| 6.1.26  | 1         | 0.17%   |
| 6.0.17  | 1         | 0.17%   |
| 6.0.11  | 1         | 0.17%   |
| 6.0.0   | 1         | 0.17%   |
| 5.15.55 | 1         | 0.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2     | 471       | 83.66%  |
| 6.3     | 83        | 14.74%  |
| 6.1     | 3         | 0.53%   |
| 6.0     | 3         | 0.53%   |
| 6.4     | 2         | 0.36%   |
| 5.15    | 1         | 0.18%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 552       | 99.82%  |
| aarch64 | 1         | 0.18%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 442       | 79.93%  |
| KDE5          | 75        | 13.56%  |
| Unknown       | 10        | 1.81%   |
| XFCE          | 6         | 1.08%   |
| Cinnamon      | 5         | 0.9%    |
| MATE          | 4         | 0.72%   |
| X-Cinnamon    | 3         | 0.54%   |
| i3            | 2         | 0.36%   |
| sway          | 1         | 0.18%   |
| LXQt          | 1         | 0.18%   |
| LXDE          | 1         | 0.18%   |
| Hyprland      | 1         | 0.18%   |
| GNOME Classic | 1         | 0.18%   |
| Budgie        | 1         | 0.18%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 449       | 80.9%   |
| X11     | 95        | 17.12%  |
| Unknown | 9         | 1.62%   |
| Xcb     | 1         | 0.18%   |
| Tty     | 1         | 0.18%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 357       | 64.32%  |
| GDM     | 144       | 25.95%  |
| SDDM    | 32        | 5.77%   |
| LightDM | 20        | 3.6%    |
| SLiM    | 1         | 0.18%   |
| LXDM    | 1         | 0.18%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 285       | 51.54%  |
| en_GB | 39        | 7.05%   |
| pt_BR | 37        | 6.69%   |
| ru_RU | 26        | 4.7%    |
| de_DE | 25        | 4.52%   |
| fr_FR | 23        | 4.16%   |
| it_IT | 13        | 2.35%   |
| pl_PL | 9         | 1.63%   |
| es_MX | 7         | 1.27%   |
| es_ES | 7         | 1.27%   |
| es_CL | 7         | 1.27%   |
| en_CA | 7         | 1.27%   |
| en_IN | 6         | 1.08%   |
| hu_HU | 5         | 0.9%    |
| es_PE | 4         | 0.72%   |
| de_AT | 4         | 0.72%   |
| zh_CN | 3         | 0.54%   |
| tr_TR | 3         | 0.54%   |
| ru_UA | 3         | 0.54%   |
| pt_PT | 3         | 0.54%   |
| es_CO | 3         | 0.54%   |
| es_AR | 3         | 0.54%   |
| en_AU | 3         | 0.54%   |
| sk_SK | 2         | 0.36%   |
| nl_NL | 2         | 0.36%   |
| nl_BE | 2         | 0.36%   |
| id_ID | 2         | 0.36%   |
| fr_CA | 2         | 0.36%   |
| es_EC | 2         | 0.36%   |
| cs_CZ | 2         | 0.36%   |
| zh_TW | 1         | 0.18%   |
| uk_UA | 1         | 0.18%   |
| sv_SE | 1         | 0.18%   |
| nb_NO | 1         | 0.18%   |
| fr_CH | 1         | 0.18%   |
| es_VE | 1         | 0.18%   |
| es_UY | 1         | 0.18%   |
| es_PA | 1         | 0.18%   |
| en_IL | 1         | 0.18%   |
| en_DK | 1         | 0.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 469       | 84.5%   |
| BIOS | 86        | 15.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 472       | 85.35%  |
| Ext4    | 72        | 13.02%  |
| Xfs     | 8         | 1.45%   |
| Overlay | 1         | 0.18%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 349       | 62.88%  |
| GPT     | 200       | 36.04%  |
| MBR     | 6         | 1.08%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 518       | 93.67%  |
| Yes       | 35        | 6.33%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 486       | 87.73%  |
| Yes       | 68        | 12.27%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 157       | 28.39%  |
| Dell                   | 86        | 15.55%  |
| Hewlett-Packard        | 80        | 14.47%  |
| ASUSTek Computer       | 69        | 12.48%  |
| Acer                   | 30        | 5.42%   |
| Apple                  | 21        | 3.8%    |
| HUAWEI                 | 17        | 3.07%   |
| MSI                    | 9         | 1.63%   |
| Samsung Electronics    | 7         | 1.27%   |
| Toshiba                | 6         | 1.08%   |
| Timi                   | 6         | 1.08%   |
| Google                 | 5         | 0.9%    |
| Unknown                | 5         | 0.9%    |
| Sony                   | 4         | 0.72%   |
| Positivo               | 3         | 0.54%   |
| Notebook               | 3         | 0.54%   |
| Framework              | 3         | 0.54%   |
| UNOWHY                 | 2         | 0.36%   |
| TUXEDO                 | 2         | 0.36%   |
| Razer                  | 2         | 0.36%   |
| PC Specialist          | 2         | 0.36%   |
| MECHREVO               | 2         | 0.36%   |
| GPU Company            | 2         | 0.36%   |
| Gigabyte Technology    | 2         | 0.36%   |
| Chuwi                  | 2         | 0.36%   |
| Avell High Performance | 2         | 0.36%   |
| VPU Company            | 1         | 0.18%   |
| VIOS                   | 1         | 0.18%   |
| Valve                  | 1         | 0.18%   |
| System76               | 1         | 0.18%   |
| realme                 | 1         | 0.18%   |
| Positivo Bahia - VAIO  | 1         | 0.18%   |
| Monster                | 1         | 0.18%   |
| Micro Electronics      | 1         | 0.18%   |
| MACHENIKE              | 1         | 0.18%   |
| LDLC                   | 1         | 0.18%   |
| Intel Client Systems   | 1         | 0.18%   |
| Insyde                 | 1         | 0.18%   |
| HT                     | 1         | 0.18%   |
| HONOR                  | 1         | 0.18%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 7         | 1.27%   |
| HP Pavilion Aero Laptop 13-be0xxx        | 4         | 0.72%   |
| Dell XPS 13 9310                         | 4         | 0.72%   |
| Apple MacBookPro9,2                      | 4         | 0.72%   |
| Apple MacBookPro8,1                      | 4         | 0.72%   |
| Framework Laptop                         | 3         | 0.54%   |
| Dell XPS 13 9305                         | 3         | 0.54%   |
| Dell XPS 13 7390                         | 3         | 0.54%   |
| Dell Precision 7540                      | 3         | 0.54%   |
| Dell Latitude E7450                      | 3         | 0.54%   |
| Dell Latitude 5490                       | 3         | 0.54%   |
| Dell Inspiron 15 5510                    | 3         | 0.54%   |
| ASUS ROG Strix G513QY_G513QY             | 3         | 0.54%   |
| Acer Nitro AN515-54                      | 3         | 0.54%   |
| Timi Redmi Book Pro 14 2022              | 2         | 0.36%   |
| Samsung 730QCJ/730QCR                    | 2         | 0.36%   |
| Samsung 550XDA                           | 2         | 0.36%   |
| MSI Modern 14 B11MOL                     | 2         | 0.36%   |
| Lenovo Yoga Slim 7 14ARE05 82A2          | 2         | 0.36%   |
| Lenovo ThinkPad X220 42911H8             | 2         | 0.36%   |
| Lenovo Legion Y530-15ICH 81FV            | 2         | 0.36%   |
| Lenovo IdeaPad L340-15API 81LW           | 2         | 0.36%   |
| Lenovo IdeaPad Gaming 3 15IMH05 82CG     | 2         | 0.36%   |
| Lenovo IdeaPad 5 14ALC05 82LM            | 2         | 0.36%   |
| Lenovo IdeaPad 3 15ITL6 82H8             | 2         | 0.36%   |
| HUAWEI RLEF-XX                           | 2         | 0.36%   |
| HUAWEI CREM-WXX9                         | 2         | 0.36%   |
| HUAWEI BOHK-WAX9X                        | 2         | 0.36%   |
| HP ZBook 15 G2                           | 2         | 0.36%   |
| HP Pavilion g6                           | 2         | 0.36%   |
| HP Notebook                              | 2         | 0.36%   |
| HP Laptop 15s-eq2xxx                     | 2         | 0.36%   |
| HP 630                                   | 2         | 0.36%   |
| HP 255 G8 Notebook PC                    | 2         | 0.36%   |
| Dell XPS 15 9560                         | 2         | 0.36%   |
| Dell XPS 15 9500                         | 2         | 0.36%   |
| Dell Latitude E6520                      | 2         | 0.36%   |
| Dell Latitude E6430                      | 2         | 0.36%   |
| Dell Latitude 7420                       | 2         | 0.36%   |
| ASUS VivoBook_ASUSLaptop M6500RE_M6500RE | 2         | 0.36%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 90        | 16.27%  |
| Lenovo IdeaPad     | 34        | 6.15%   |
| Dell Latitude      | 26        | 4.7%    |
| HP Pavilion        | 20        | 3.62%   |
| Dell Inspiron      | 20        | 3.62%   |
| Dell XPS           | 19        | 3.44%   |
| ASUS VivoBook      | 19        | 3.44%   |
| HP Laptop          | 16        | 2.89%   |
| ASUS ROG           | 14        | 2.53%   |
| Acer Aspire        | 14        | 2.53%   |
| Dell Precision     | 11        | 1.99%   |
| Lenovo Legion      | 10        | 1.81%   |
| ASUS ASUS          | 10        | 1.81%   |
| Acer Nitro         | 9         | 1.63%   |
| HP EliteBook       | 8         | 1.45%   |
| Lenovo Yoga        | 7         | 1.27%   |
| Lenovo ThinkBook   | 7         | 1.27%   |
| HP ProBook         | 7         | 1.27%   |
| Unknown            | 7         | 1.27%   |
| HP ZBook           | 5         | 0.9%    |
| Dell Vostro        | 5         | 0.9%    |
| ASUS Zenbook       | 5         | 0.9%    |
| Apple MacBookPro9  | 5         | 0.9%    |
| Toshiba Satellite  | 4         | 0.72%   |
| Apple MacBookPro8  | 4         | 0.72%   |
| Acer Swift         | 4         | 0.72%   |
| Timi Redmi         | 3         | 0.54%   |
| HP Victus          | 3         | 0.54%   |
| HP ENVY            | 3         | 0.54%   |
| HP 255             | 3         | 0.54%   |
| Framework Laptop   | 3         | 0.54%   |
| ASUS TUF           | 3         | 0.54%   |
| Apple MacBookPro11 | 3         | 0.54%   |
| Samsung 730QCJ     | 2         | 0.36%   |
| Samsung 550XDA     | 2         | 0.36%   |
| Razer Blade        | 2         | 0.36%   |
| MSI Summit         | 2         | 0.36%   |
| MSI Modern         | 2         | 0.36%   |
| HUAWEI RLEF-XX     | 2         | 0.36%   |
| HUAWEI CREM-WXX9   | 2         | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 97        | 17.54%  |
| 2022    | 71        | 12.84%  |
| 2020    | 68        | 12.3%   |
| 2019    | 67        | 12.12%  |
| 2018    | 45        | 8.14%   |
| 2017    | 33        | 5.97%   |
| 2012    | 29        | 5.24%   |
| 2011    | 28        | 5.06%   |
| 2014    | 24        | 4.34%   |
| 2023    | 22        | 3.98%   |
| 2016    | 19        | 3.44%   |
| 2015    | 18        | 3.25%   |
| 2013    | 15        | 2.71%   |
| 2009    | 6         | 1.08%   |
| 2010    | 4         | 0.72%   |
| 2007    | 3         | 0.54%   |
| 2008    | 2         | 0.36%   |
| 2006    | 1         | 0.18%   |
| Unknown | 1         | 0.18%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 553       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 420       | 75.68%  |
| Enabled  | 135       | 24.32%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 545       | 98.55%  |
| Yes  | 8         | 1.45%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 159       | 28.75%  |
| 16.01-24.0  | 136       | 24.59%  |
| 8.01-16.0   | 114       | 20.61%  |
| 32.01-64.0  | 57        | 10.31%  |
| 3.01-4.0    | 49        | 8.86%   |
| 24.01-32.0  | 19        | 3.44%   |
| 64.01-256.0 | 12        | 2.17%   |
| 1.01-2.0    | 7         | 1.27%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 168       | 29.68%  |
| 3.01-4.0   | 154       | 27.21%  |
| 2.01-3.0   | 148       | 26.15%  |
| 1.01-2.0   | 59        | 10.42%  |
| 8.01-16.0  | 32        | 5.65%   |
| 0.51-1.0   | 4         | 0.71%   |
| 16.01-24.0 | 1         | 0.18%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 401       | 72.25%  |
| 2      | 134       | 24.14%  |
| 3      | 14        | 2.52%   |
| 4      | 3         | 0.54%   |
| 7      | 1         | 0.18%   |
| 6      | 1         | 0.18%   |
| 5      | 1         | 0.18%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 466       | 84.12%  |
| Yes       | 88        | 15.88%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 380       | 68.72%  |
| No        | 173       | 31.28%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 545       | 98.55%  |
| No        | 8         | 1.45%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 484       | 86.89%  |
| No        | 73        | 13.11%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 83        | 14.93%  |
| Brazil      | 48        | 8.63%   |
| Germany     | 46        | 8.27%   |
| Russia      | 28        | 5.04%   |
| France      | 25        | 4.5%    |
| Italy       | 21        | 3.78%   |
| India       | 20        | 3.6%    |
| Poland      | 19        | 3.42%   |
| Netherlands | 17        | 3.06%   |
| Canada      | 17        | 3.06%   |
| Mexico      | 14        | 2.52%   |
| UK          | 13        | 2.34%   |
| Turkey      | 13        | 2.34%   |
| Spain       | 11        | 1.98%   |
| Hungary     | 9         | 1.62%   |
| Chile       | 9         | 1.62%   |
| Czechia     | 8         | 1.44%   |
| Switzerland | 6         | 1.08%   |
| Belgium     | 6         | 1.08%   |
| Austria     | 6         | 1.08%   |
| South Korea | 5         | 0.9%    |
| Romania     | 5         | 0.9%    |
| Portugal    | 5         | 0.9%    |
| Peru        | 5         | 0.9%    |
| Finland     | 5         | 0.9%    |
| Denmark     | 5         | 0.9%    |
| Croatia     | 5         | 0.9%    |
| Colombia    | 5         | 0.9%    |
| Australia   | 5         | 0.9%    |
| Sweden      | 4         | 0.72%   |
| Norway      | 4         | 0.72%   |
| Israel      | 4         | 0.72%   |
| Indonesia   | 4         | 0.72%   |
| Egypt       | 4         | 0.72%   |
| Belarus     | 4         | 0.72%   |
| Argentina   | 4         | 0.72%   |
| Ukraine     | 3         | 0.54%   |
| Thailand    | 3         | 0.54%   |
| Taiwan      | 3         | 0.54%   |
| Sri Lanka   | 3         | 0.54%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Sao Paulo         | 8         | 1.42%   |
| Moscow            | 7         | 1.25%   |
| Santiago          | 6         | 1.07%   |
| Mexico City       | 5         | 0.89%   |
| Bengaluru         | 5         | 0.89%   |
| Prague            | 4         | 0.71%   |
| Paris             | 4         | 0.71%   |
| Istanbul          | 4         | 0.71%   |
| Helsinki          | 4         | 0.71%   |
| Fortaleza         | 4         | 0.71%   |
| Berlin            | 4         | 0.71%   |
| Amsterdam         | 4         | 0.71%   |
| Zurich            | 3         | 0.53%   |
| Zagreb            | 3         | 0.53%   |
| Toronto           | 3         | 0.53%   |
| Sofia             | 3         | 0.53%   |
| Singapore         | 3         | 0.53%   |
| Santa Maria       | 3         | 0.53%   |
| Rio de Janeiro    | 3         | 0.53%   |
| Pune              | 3         | 0.53%   |
| Poznan            | 3         | 0.53%   |
| Plymouth          | 3         | 0.53%   |
| New York          | 3         | 0.53%   |
| Munich            | 3         | 0.53%   |
| Madrid            | 3         | 0.53%   |
| Liverpool         | 3         | 0.53%   |
| Frankfurt am Main | 3         | 0.53%   |
| Delhi             | 3         | 0.53%   |
| Chennai           | 3         | 0.53%   |
| Budapest          | 3         | 0.53%   |
| Atlanta           | 3         | 0.53%   |
| Worms             | 2         | 0.36%   |
| Vilnius           | 2         | 0.36%   |
| Vienna            | 2         | 0.36%   |
| Ufa               | 2         | 0.36%   |
| Turin             | 2         | 0.36%   |
| Temecula          | 2         | 0.36%   |
| Sydney            | 2         | 0.36%   |
| St Petersburg     | 2         | 0.36%   |
| Springfield       | 2         | 0.36%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 133       | 161    | 18.68%  |
| Sandisk                        | 77        | 80     | 10.81%  |
| SK hynix                       | 44        | 45     | 6.18%   |
| Toshiba                        | 42        | 45     | 5.9%    |
| Kingston                       | 40        | 44     | 5.62%   |
| Unknown                        | 38        | 44     | 5.34%   |
| WDC                            | 37        | 40     | 5.2%    |
| Seagate                        | 35        | 39     | 4.92%   |
| Micron Technology              | 35        | 37     | 4.92%   |
| Intel                          | 26        | 32     | 3.65%   |
| Crucial                        | 17        | 18     | 2.39%   |
| China                          | 16        | 16     | 2.25%   |
| KIOXIA                         | 15        | 16     | 2.11%   |
| Apple                          | 11        | 19     | 1.54%   |
| Micron/Crucial Technology      | 10        | 10     | 1.4%    |
| HGST                           | 10        | 10     | 1.4%    |
| A-DATA Technology              | 10        | 10     | 1.4%    |
| Phison Electronics             | 9         | 9      | 1.26%   |
| Silicon Motion                 | 7         | 7      | 0.98%   |
| ADATA Technology               | 7         | 7      | 0.98%   |
| Phison                         | 6         | 7      | 0.84%   |
| Kingston Technology Company    | 6         | 7      | 0.84%   |
| SPCC                           | 5         | 5      | 0.7%    |
| Solid State Storage Technology | 4         | 4      | 0.56%   |
| JMicron Technology             | 4         | 5      | 0.56%   |
| SABRENT                        | 3         | 3      | 0.42%   |
| Netac                          | 3         | 3      | 0.42%   |
| LITEON                         | 3         | 3      | 0.42%   |
| Lexar                          | 3         | 3      | 0.42%   |
| Hitachi                        | 3         | 3      | 0.42%   |
| Gigabyte Technology            | 3         | 3      | 0.42%   |
| Apacer                         | 3         | 3      | 0.42%   |
| Union Memory (Shenzhen)        | 2         | 2      | 0.28%   |
| Union Memory                   | 2         | 2      | 0.28%   |
| Transcend                      | 2         | 2      | 0.28%   |
| Team                           | 2         | 2      | 0.28%   |
| Solid State Storage            | 2         | 2      | 0.28%   |
| Ramsta                         | 2         | 2      | 0.28%   |
| PNY                            | 2         | 2      | 0.28%   |
| Intenso                        | 2         | 2      | 0.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 33        | 4.5%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 16        | 2.18%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB                | 11        | 1.5%    |
| Kingston SA400S37240G 240GB SSD                     | 11        | 1.5%    |
| Unknown MMC Card  64GB                              | 10        | 1.36%   |
| Seagate ST1000LM035-1RK172 1TB                      | 10        | 1.36%   |
| Intel SSD 660P Series 512GB                         | 9         | 1.23%   |
| Kingston SA400S37480G 480GB SSD                     | 8         | 1.09%   |
| Unknown MMC Card  32GB                              | 7         | 0.95%   |
| Samsung SSD 980 1TB                                 | 7         | 0.95%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                 | 7         | 0.95%   |
| Toshiba XG6 NVMe SSD Controller 256GB               | 6         | 0.82%   |
| Toshiba MQ04ABF100 1TB                              | 6         | 0.82%   |
| SK hynix BC511 256GB                                | 6         | 0.82%   |
| Toshiba MQ01ABD100 1TB                              | 5         | 0.68%   |
| SK hynix PC401 NVMe Solid State Drive 256GB         | 5         | 0.68%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 512GB     | 5         | 0.68%   |
| Sandisk WD Black SN850 500GB                        | 5         | 0.68%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 256GB    | 5         | 0.68%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 5         | 0.68%   |
| Micron 2450_MTFDKBA512TFK 512GB                     | 5         | 0.68%   |
| HGST HTS721010A9E630 1TB                            | 5         | 0.68%   |
| Unknown MMC Card  128GB                             | 4         | 0.55%   |
| Toshiba MQ01ABF050 500GB                            | 4         | 0.55%   |
| SK hynix HFM512GD3JX013N 512GB                      | 4         | 0.55%   |
| SK hynix BC711 HFM512GD3JX013N 512GB                | 4         | 0.55%   |
| SK hynix BC501 NVMe Solid State Drive 512GB         | 4         | 0.55%   |
| Phison E16 PCIe4 NVMe Controller 1TB                | 4         | 0.55%   |
| JMicron Generic 320GB                               | 4         | 0.55%   |
| Intel SSD Pro 7600p/760p/E 6100p Series 1TB         | 4         | 0.55%   |
| China SSD 256GB                                     | 4         | 0.55%   |
| WDC WD10SPZX-60Z10T0 1TB                            | 3         | 0.41%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 1TB | 3         | 0.41%   |
| Seagate ST1000LM049-2GH172 1TB                      | 3         | 0.41%   |
| Seagate Expansion 1TB                               | 3         | 0.41%   |
| Sandisk WD_BLACK SN770 1TB                          | 3         | 0.41%   |
| Sandisk WDC PC SN530 SDBPMPZ-512G-1101 512GB        | 3         | 0.41%   |
| Sandisk WD Blue SN570 1TB                           | 3         | 0.41%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD 1TB | 3         | 0.41%   |
| SanDisk SSD PLUS 480GB                              | 3         | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 33        | 36     | 35.11%  |
| Toshiba             | 22        | 24     | 23.4%   |
| WDC                 | 21        | 24     | 22.34%  |
| HGST                | 10        | 10     | 10.64%  |
| Hitachi             | 3         | 3      | 3.19%   |
| Apple               | 2         | 2      | 2.13%   |
| Samsung Electronics | 1         | 1      | 1.06%   |
| SAGE                | 1         | 1      | 1.06%   |
| LaCie               | 1         | 1      | 1.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 34        | 43     | 17.17%  |
| Kingston            | 33        | 37     | 16.67%  |
| SanDisk             | 16        | 17     | 8.08%   |
| Crucial             | 16        | 17     | 8.08%   |
| China               | 16        | 16     | 8.08%   |
| WDC                 | 8         | 8      | 4.04%   |
| Toshiba             | 7         | 7      | 3.54%   |
| A-DATA Technology   | 6         | 6      | 3.03%   |
| SPCC                | 5         | 5      | 2.53%   |
| Intel               | 5         | 6      | 2.53%   |
| Apple               | 5         | 6      | 2.53%   |
| Micron Technology   | 4         | 4      | 2.02%   |
| JMicron Technology  | 4         | 5      | 2.02%   |
| SABRENT             | 3         | 3      | 1.52%   |
| Netac               | 3         | 3      | 1.52%   |
| LITEON              | 3         | 3      | 1.52%   |
| Lexar               | 3         | 3      | 1.52%   |
| Ramsta              | 2         | 2      | 1.01%   |
| PNY                 | 2         | 2      | 1.01%   |
| Hewlett-Packard     | 2         | 2      | 1.01%   |
| GOODRAM             | 2         | 4      | 1.01%   |
| Gigabyte Technology | 2         | 2      | 1.01%   |
| Apacer              | 2         | 2      | 1.01%   |
| Advantech           | 2         | 2      | 1.01%   |
| XrayDisk            | 1         | 1      | 0.51%   |
| Union Memory        | 1         | 1      | 0.51%   |
| Transcend           | 1         | 1      | 0.51%   |
| Team                | 1         | 1      | 0.51%   |
| Smart               | 1         | 1      | 0.51%   |
| Pichau              | 1         | 1      | 0.51%   |
| OEM                 | 1         | 1      | 0.51%   |
| MidasForce          | 1         | 1      | 0.51%   |
| LITEONIT            | 1         | 1      | 0.51%   |
| KingSpec            | 1         | 1      | 0.51%   |
| Kimtigo             | 1         | 1      | 0.51%   |
| HS-SSD-E100         | 1         | 1      | 0.51%   |
| Emtec               | 1         | 1      | 0.51%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 339       | 410    | 51.13%  |
| SSD     | 183       | 218    | 27.6%   |
| HDD     | 91        | 102    | 13.73%  |
| MMC     | 41        | 47     | 6.18%   |
| Unknown | 9         | 10     | 1.36%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 339       | 410    | 53.05%  |
| SATA | 237       | 299    | 37.09%  |
| MMC  | 41        | 47     | 6.42%   |
| SAS  | 22        | 31     | 3.44%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 172       | 216    | 64.18%  |
| 0.51-1.0   | 84        | 92     | 31.34%  |
| 1.01-2.0   | 8         | 8      | 2.99%   |
| 10.01-20.0 | 3         | 3      | 1.12%   |
| 3.01-4.0   | 1         | 1      | 0.37%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 125       | 22.44%  |
| 501-1000       | 125       | 22.44%  |
| 1001-2000      | 78        | 14%     |
| 101-250        | 69        | 12.39%  |
| Unknown        | 52        | 9.34%   |
| 1-20           | 49        | 8.8%    |
| More than 3000 | 20        | 3.59%   |
| 51-100         | 18        | 3.23%   |
| 2001-3000      | 12        | 2.15%   |
| 21-50          | 9         | 1.62%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 196       | 35.13%  |
| 21-50          | 87        | 15.59%  |
| 101-250        | 70        | 12.54%  |
| 51-100         | 67        | 12.01%  |
| Unknown        | 52        | 9.32%   |
| 251-500        | 50        | 8.96%   |
| 501-1000       | 21        | 3.76%   |
| 1001-2000      | 11        | 1.97%   |
| More than 3000 | 3         | 0.54%   |
| 2001-3000      | 1         | 0.18%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WDS240G2G0A-00JH30 240GB SSD             | 1         | 1      | 33.33%  |
| Toshiba MQ01ABF050 500GB                     | 1         | 1      | 33.33%  |
| Samsung Electronics SSD 840 PRO Series 256GB | 1         | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 33.33%  |
| Toshiba             | 1         | 1      | 33.33%  |
| Samsung Electronics | 1         | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 2         | 2      | 66.67%  |
| HDD  | 1         | 1      | 33.33%  |

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
| Detected | 393       | 549    | 68.23%  |
| Works    | 180       | 235    | 31.25%  |
| Malfunc  | 3         | 3      | 0.52%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 304       | 42.82%  |
| Samsung Electronics            | 101       | 14.23%  |
| SanDisk                        | 64        | 9.01%   |
| AMD                            | 59        | 8.31%   |
| SK hynix                       | 44        | 6.2%    |
| Micron Technology              | 31        | 4.37%   |
| Toshiba America Info Systems   | 16        | 2.25%   |
| Phison Electronics             | 13        | 1.83%   |
| Kingston Technology Company    | 13        | 1.83%   |
| KIOXIA                         | 12        | 1.69%   |
| ADATA Technology               | 11        | 1.55%   |
| Micron/Crucial Technology      | 10        | 1.41%   |
| Silicon Motion                 | 9         | 1.27%   |
| Solid State Storage Technology | 7         | 0.99%   |
| Union Memory (Shenzhen)        | 4         | 0.56%   |
| Apple                          | 3         | 0.42%   |
| Yangtze Memory Technologies    | 2         | 0.28%   |
| MAXIO Technology (Hangzhou)    | 2         | 0.28%   |
| Solidigm                       | 1         | 0.14%   |
| Shenzhen Longsys Electronics   | 1         | 0.14%   |
| Seagate Technology             | 1         | 0.14%   |
| Realtek Semiconductor          | 1         | 0.14%   |
| Nvidia                         | 1         | 0.14%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 59        | 7.91%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 41        | 5.5%    |
| Intel Volume Management Device NVMe RAID Controller                            | 34        | 4.56%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 34        | 4.56%   |
| Samsung NVMe SSD Controller 980                                                | 31        | 4.16%   |
| Micron NVMe Storage Controller                                                 | 29        | 3.89%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 27        | 3.62%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 26        | 3.49%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 20        | 2.68%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 18        | 2.41%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 18        | 2.41%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 18        | 2.41%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 16        | 2.14%   |
| SanDisk Non-Volatile memory controller                                         | 14        | 1.88%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 14        | 1.88%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 12        | 1.61%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 12        | 1.61%   |
| Intel Tiger Lake-LP SATA Controller                                            | 11        | 1.47%   |
| Intel Comet Lake SATA AHCI Controller                                          | 10        | 1.34%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 10        | 1.34%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 10        | 1.34%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 9         | 1.21%   |
| Intel SSD 660P Series                                                          | 9         | 1.21%   |
| SK hynix BC511                                                                 | 8         | 1.07%   |
| SanDisk WD Black SN770 NVMe SSD                                                | 8         | 1.07%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 8         | 1.07%   |
| Kingston Company Company Non-Volatile memory controller                        | 8         | 1.07%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 8         | 1.07%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 8         | 1.07%   |
| Solid State Storage Non-Volatile memory controller                             | 7         | 0.94%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 7         | 0.94%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 7         | 0.94%   |
| KIOXIA Non-Volatile memory controller                                          | 7         | 0.94%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 6         | 0.8%    |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 6         | 0.8%    |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 6         | 0.8%    |
| Intel Alder Lake-P SATA AHCI Controller                                        | 6         | 0.8%    |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 5         | 0.67%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 5         | 0.67%   |
| SanDisk NVMe Controller                                                        | 5         | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 335       | 47.32%  |
| SATA | 305       | 43.08%  |
| RAID | 60        | 8.47%   |
| IDE  | 8         | 1.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 420       | 75.95%  |
| AMD          | 131       | 23.69%  |
| CentaurHauls | 1         | 0.18%   |
| Unknown      | 1         | 0.18%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 22        | 3.98%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 12        | 2.17%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 11        | 1.99%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 10        | 1.81%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 9         | 1.63%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 9         | 1.63%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 9         | 1.63%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 8         | 1.45%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 8         | 1.45%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 8         | 1.45%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 8         | 1.45%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 7         | 1.27%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 7         | 1.27%   |
| Intel 12th Gen Core i7-12700H                 | 7         | 1.27%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 6         | 1.08%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 6         | 1.08%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 6         | 1.08%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 6         | 1.08%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 5         | 0.9%    |
| Intel Core i5-8350U CPU @ 1.70GHz             | 5         | 0.9%    |
| Intel Core i5-5300U CPU @ 2.30GHz             | 5         | 0.9%    |
| Intel Core i5-10300H CPU @ 2.50GHz            | 5         | 0.9%    |
| Intel 12th Gen Core i7-1260P                  | 5         | 0.9%    |
| AMD Ryzen 5 5600U with Radeon Graphics        | 5         | 0.9%    |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 4         | 0.72%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 0.72%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 4         | 0.72%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 4         | 0.72%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 4         | 0.72%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 4         | 0.72%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 4         | 0.72%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 0.72%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 0.72%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 4         | 0.72%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 4         | 0.72%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 4         | 0.72%   |
| Intel 12th Gen Core i7-1255U                  | 4         | 0.72%   |
| Intel 12th Gen Core i5-12500H                 | 4         | 0.72%   |
| Intel 12th Gen Core i5-12450H                 | 4         | 0.72%   |
| Intel 12th Gen Core i5-1240P                  | 4         | 0.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 121       | 21.88%  |
| Intel Core i5           | 110       | 19.89%  |
| Other                   | 106       | 19.17%  |
| AMD Ryzen 5             | 49        | 8.86%   |
| AMD Ryzen 7             | 36        | 6.51%   |
| Intel Core i3           | 30        | 5.42%   |
| Intel Celeron           | 23        | 4.16%   |
| AMD Ryzen 9             | 12        | 2.17%   |
| Intel Pentium Silver    | 7         | 1.27%   |
| AMD Ryzen 7 PRO         | 7         | 1.27%   |
| AMD Ryzen 3             | 7         | 1.27%   |
| Intel Pentium           | 6         | 1.08%   |
| Intel Core 2 Duo        | 6         | 1.08%   |
| Intel Atom              | 6         | 1.08%   |
| AMD Ryzen 5 PRO         | 6         | 1.08%   |
| AMD A6                  | 4         | 0.72%   |
| Intel Core i9           | 3         | 0.54%   |
| AMD A10                 | 3         | 0.54%   |
| AMD A8                  | 2         | 0.36%   |
| Intel Xeon              | 1         | 0.18%   |
| Intel Pentium Dual-Core | 1         | 0.18%   |
| Intel Pentium Dual      | 1         | 0.18%   |
| Intel Genuine           | 1         | 0.18%   |
| Intel Core m5           | 1         | 0.18%   |
| Intel Core m3           | 1         | 0.18%   |
| Intel Core 2            | 1         | 0.18%   |
| AMD E1                  | 1         | 0.18%   |
| AMD A12                 | 1         | 0.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 211       | 38.16%  |
| 2      | 169       | 30.56%  |
| 8      | 67        | 12.12%  |
| 6      | 67        | 12.12%  |
| 12     | 15        | 2.71%   |
| 14     | 13        | 2.35%   |
| 10     | 9         | 1.63%   |
| 16     | 2         | 0.36%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 553       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 481       | 86.98%  |
| 1      | 72        | 13.02%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 552       | 99.82%  |
| 64-bit         | 1         | 0.18%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 425       | 76.85%  |
| 0x0a50000c | 21        | 3.8%    |
| 0x0a50000d | 13        | 2.35%   |
| 0x08608103 | 12        | 2.17%   |
| 0x08108109 | 12        | 2.17%   |
| 0x0a404102 | 11        | 1.99%   |
| 0x08108102 | 8         | 1.45%   |
| 0x08600106 | 6         | 1.08%   |
| 0x0a404101 | 4         | 0.72%   |
| 0x08600104 | 4         | 0.72%   |
| 0x06006705 | 4         | 0.72%   |
| 0x0a601203 | 3         | 0.54%   |
| 0x08608102 | 3         | 0.54%   |
| 0x06001116 | 3         | 0.54%   |
| 0x0a50000b | 2         | 0.36%   |
| 0x08608104 | 2         | 0.36%   |
| 0x08600103 | 2         | 0.36%   |
| 0x0810100b | 2         | 0.36%   |
| 0x08101007 | 2         | 0.36%   |
| 0x906ea    | 1         | 0.18%   |
| 0x806e9    | 1         | 0.18%   |
| 0x806c1    | 1         | 0.18%   |
| 0x506c9    | 1         | 0.18%   |
| 0x306a9    | 1         | 0.18%   |
| 0x10676    | 1         | 0.18%   |
| 0x08900201 | 1         | 0.18%   |
| 0x08600109 | 1         | 0.18%   |
| 0x07030106 | 1         | 0.18%   |
| 0x07030104 | 1         | 0.18%   |
| 0x0700010f | 1         | 0.18%   |
| 0x06006704 | 1         | 0.18%   |
| 0x0600611a | 1         | 0.18%   |
| 0x06006110 | 1         | 0.18%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 111       | 20.07%  |
| TigerLake        | 52        | 9.4%    |
| Unknown          | 44        | 7.96%   |
| Zen 3            | 39        | 7.05%   |
| Alderlake Hybrid | 39        | 7.05%   |
| IvyBridge        | 30        | 5.42%   |
| Haswell          | 29        | 5.24%   |
| SandyBridge      | 27        | 4.88%   |
| Skylake          | 22        | 3.98%   |
| CometLake        | 21        | 3.8%    |
| Zen+             | 20        | 3.62%   |
| Icelake          | 20        | 3.62%   |
| Goldmont plus    | 17        | 3.07%   |
| Zen 2            | 14        | 2.53%   |
| Broadwell        | 14        | 2.53%   |
| Silvermont       | 12        | 2.17%   |
| Westmere         | 8         | 1.45%   |
| Penryn           | 7         | 1.27%   |
| Excavator        | 7         | 1.27%   |
| Zen              | 5         | 0.9%    |
| Goldmont         | 4         | 0.72%   |
| Piledriver       | 3         | 0.54%   |
| Core             | 3         | 0.54%   |
| Tremont          | 2         | 0.36%   |
| Puma             | 2         | 0.36%   |
| Jaguar           | 1         | 0.18%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 394       | 55.34%  |
| Nvidia  | 175       | 24.58%  |
| AMD     | 142       | 19.94%  |
| Zhaoxin | 1         | 0.14%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 48        | 6.64%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 29        | 4.01%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 26        | 3.6%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 26        | 3.6%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 25        | 3.46%   |
| Intel UHD Graphics 620                                                                   | 24        | 3.32%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 24        | 3.32%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 20        | 2.77%   |
| AMD Lucienne                                                                             | 19        | 2.63%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 18        | 2.49%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 18        | 2.49%   |
| AMD Rembrandt [Radeon 680M]                                                              | 16        | 2.21%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 14        | 1.94%   |
| Intel HD Graphics 620                                                                    | 14        | 1.94%   |
| AMD Renoir                                                                               | 14        | 1.94%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 13        | 1.8%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 12        | 1.66%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 12        | 1.66%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 11        | 1.52%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 10        | 1.38%   |
| Intel HD Graphics 630                                                                    | 10        | 1.38%   |
| Intel HD Graphics 5500                                                                   | 10        | 1.38%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 9         | 1.24%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 9         | 1.24%   |
| AMD Barcelo                                                                              | 9         | 1.24%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 8         | 1.11%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 8         | 1.11%   |
| Nvidia GP108M [GeForce MX150]                                                            | 7         | 0.97%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 7         | 0.97%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 7         | 0.97%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 7         | 0.97%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 6         | 0.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 0.83%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 0.83%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 5         | 0.69%   |
| Intel HD Graphics 530                                                                    | 5         | 0.69%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 5         | 0.69%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 5         | 0.69%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 5         | 0.69%   |
| Nvidia TU117M                                                                            | 4         | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 258       | 46.49%  |
| Intel + Nvidia | 128       | 23.06%  |
| 1 x AMD        | 104       | 18.74%  |
| 1 x Nvidia     | 25        | 4.5%    |
| AMD + Nvidia   | 23        | 4.14%   |
| Intel + AMD    | 8         | 1.44%   |
| 2 x AMD        | 6         | 1.08%   |
| Other          | 1         | 0.18%   |
| 2 x Intel      | 1         | 0.18%   |
| 1 x Zhaoxin    | 1         | 0.18%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 476       | 85.77%  |
| Proprietary | 65        | 11.71%  |
| Unknown     | 14        | 2.52%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 339       | 61.08%  |
| 0.01-0.5   | 64        | 11.53%  |
| 1.01-2.0   | 56        | 10.09%  |
| 3.01-4.0   | 44        | 7.93%   |
| 0.51-1.0   | 28        | 5.05%   |
| 5.01-6.0   | 13        | 2.34%   |
| 7.01-8.0   | 5         | 0.9%    |
| 8.01-16.0  | 5         | 0.9%    |
| 2.01-3.0   | 1         | 0.18%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 126       | 19.47%  |
| AU Optronics            | 104       | 16.07%  |
| Chimei Innolux          | 95        | 14.68%  |
| LG Display              | 68        | 10.51%  |
| Samsung Electronics     | 43        | 6.65%   |
| Sharp                   | 27        | 4.17%   |
| Dell                    | 22        | 3.4%    |
| Apple                   | 22        | 3.4%    |
| PANDA                   | 15        | 2.32%   |
| Lenovo                  | 15        | 2.32%   |
| CSO                     | 15        | 2.32%   |
| Goldstar                | 13        | 2.01%   |
| Chi Mei Optoelectronics | 8         | 1.24%   |
| Philips                 | 7         | 1.08%   |
| Hewlett-Packard         | 7         | 1.08%   |
| InfoVision              | 5         | 0.77%   |
| Ancor Communications    | 5         | 0.77%   |
| LG Philips              | 4         | 0.62%   |
| ASUSTek Computer        | 4         | 0.62%   |
| Acer                    | 4         | 0.62%   |
| BenQ                    | 3         | 0.46%   |
| AOC                     | 3         | 0.46%   |
| TMX                     | 2         | 0.31%   |
| Pixio                   | 2         | 0.31%   |
| Iiyama                  | 2         | 0.31%   |
| Gigabyte Technology     | 2         | 0.31%   |
| Fujitsu Siemens         | 2         | 0.31%   |
| WaveShare               | 1         | 0.15%   |
| Vizio                   | 1         | 0.15%   |
| ViewSonic               | 1         | 0.15%   |
| Vestel Elektronik       | 1         | 0.15%   |
| Valve                   | 1         | 0.15%   |
| Unknown (XXX)           | 1         | 0.15%   |
| SKY                     | 1         | 0.15%   |
| SANYO                   | 1         | 0.15%   |
| MSI                     | 1         | 0.15%   |
| Mi                      | 1         | 0.15%   |
| KDC                     | 1         | 0.15%   |
| KDB                     | 1         | 0.15%   |
| JDI                     | 1         | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 7         | 1.07%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 6         | 0.92%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                | 6         | 0.92%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 5         | 0.77%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch         | 4         | 0.61%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 4         | 0.61%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch     | 4         | 0.61%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 4         | 0.61%   |
| BOE LCD Monitor BOE09DE 1920x1080 309x174mm 14.0-inch                | 4         | 0.61%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                | 4         | 0.61%   |
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                | 4         | 0.61%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 4         | 0.61%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch               | 4         | 0.61%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch              | 3         | 0.46%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch              | 3         | 0.46%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch              | 3         | 0.46%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch          | 3         | 0.46%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch             | 3         | 0.46%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch             | 3         | 0.46%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch         | 3         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 3         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 3         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch      | 3         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch     | 3         | 0.46%   |
| Chimei Innolux LCD Monitor CMN153C 1920x1080 344x193mm 15.5-inch     | 3         | 0.46%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 3         | 0.46%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch      | 3         | 0.46%   |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch     | 3         | 0.46%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                | 3         | 0.46%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 3         | 0.46%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                 | 3         | 0.46%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 3         | 0.46%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch       | 3         | 0.46%   |
| AU Optronics LCD Monitor AUO408D 1920x1080 309x174mm 14.0-inch       | 3         | 0.46%   |
| AU Optronics LCD Monitor AUO103D 1920x1080 309x173mm 13.9-inch       | 3         | 0.46%   |
| Apple Color LCD APPA034 2880x1800 286x179mm 13.3-inch                | 3         | 0.46%   |
| Sharp LCD Monitor SHP14AE 1920x1080 294x165mm 13.3-inch              | 2         | 0.31%   |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch              | 2         | 0.31%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch              | 2         | 0.31%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch | 2         | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 312       | 52.09%  |
| 1366x768 (WXGA)    | 92        | 15.36%  |
| 3840x2160 (4K)     | 28        | 4.67%   |
| 2560x1440 (QHD)    | 28        | 4.67%   |
| 2560x1600          | 21        | 3.51%   |
| 1920x1200 (WUXGA)  | 21        | 3.51%   |
| 1600x900 (HD+)     | 18        | 3.01%   |
| 1280x800 (WXGA)    | 14        | 2.34%   |
| 2880x1800          | 10        | 1.67%   |
| 1440x900 (WXGA+)   | 9         | 1.5%    |
| 1680x1050 (WSXGA+) | 7         | 1.17%   |
| 3440x1440          | 5         | 0.83%   |
| 2256x1504          | 5         | 0.83%   |
| 2160x1440          | 5         | 0.83%   |
| 1280x1024 (SXGA)   | 3         | 0.5%    |
| 3840x2400          | 2         | 0.33%   |
| 3840x1100          | 2         | 0.33%   |
| 3456x2160          | 2         | 0.33%   |
| 2560x1080          | 2         | 0.33%   |
| 2520x1680          | 2         | 0.33%   |
| 800x1280           | 1         | 0.17%   |
| 3840x1600          | 1         | 0.17%   |
| 3200x2000          | 1         | 0.17%   |
| 3200x1800 (QHD+)   | 1         | 0.17%   |
| 3120x2080          | 1         | 0.17%   |
| 3072x1920          | 1         | 0.17%   |
| 3000x2000          | 1         | 0.17%   |
| 2880x1620          | 1         | 0.17%   |
| 2304x1440          | 1         | 0.17%   |
| 2160x1350          | 1         | 0.17%   |
| 1024x768 (XGA)     | 1         | 0.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 245       | 38.04%  |
| 13      | 117       | 18.17%  |
| 14      | 104       | 16.15%  |
| 27      | 24        | 3.73%   |
| 17      | 24        | 3.73%   |
| 24      | 16        | 2.48%   |
| 23      | 16        | 2.48%   |
| 16      | 16        | 2.48%   |
| 12      | 11        | 1.71%   |
| 21      | 10        | 1.55%   |
| 34      | 8         | 1.24%   |
| 31      | 8         | 1.24%   |
| 11      | 8         | 1.24%   |
| 22      | 5         | 0.78%   |
| 18      | 5         | 0.78%   |
| 84      | 4         | 0.62%   |
| 19      | 4         | 0.62%   |
| 40      | 3         | 0.47%   |
| 28      | 3         | 0.47%   |
| 10      | 3         | 0.47%   |
| 20      | 2         | 0.31%   |
| 65      | 1         | 0.16%   |
| 63      | 1         | 0.16%   |
| 54      | 1         | 0.16%   |
| 52      | 1         | 0.16%   |
| 42      | 1         | 0.16%   |
| 37      | 1         | 0.16%   |
| 7       | 1         | 0.16%   |
| Unknown | 1         | 0.16%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 402       | 63.11%  |
| 201-300     | 95        | 14.91%  |
| 501-600     | 52        | 8.16%   |
| 351-400     | 29        | 4.55%   |
| 401-500     | 24        | 3.77%   |
| 601-700     | 12        | 1.88%   |
| 701-800     | 8         | 1.26%   |
| 801-900     | 4         | 0.63%   |
| 1501-2000   | 4         | 0.63%   |
| 1001-1500   | 4         | 0.63%   |
| 901-1000    | 1         | 0.16%   |
| 1-100       | 1         | 0.16%   |
| Unknown     | 1         | 0.16%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 445       | 78.9%   |
| 16/10 | 91        | 16.13%  |
| 3/2   | 13        | 2.3%    |
| 21/9  | 8         | 1.42%   |
| 5/4   | 3         | 0.53%   |
| 3.40  | 2         | 0.35%   |
| 4/3   | 1         | 0.18%   |
| 0.67  | 1         | 0.18%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 247       | 38.41%  |
| 81-90          | 166       | 25.82%  |
| 71-80          | 48        | 7.47%   |
| 201-250        | 42        | 6.53%   |
| 301-350        | 26        | 4.04%   |
| 121-130        | 21        | 3.27%   |
| 351-500        | 17        | 2.64%   |
| 111-120        | 14        | 2.18%   |
| 61-70          | 11        | 1.71%   |
| 51-60          | 10        | 1.56%   |
| More than 1000 | 8         | 1.24%   |
| 151-200        | 8         | 1.24%   |
| 141-150        | 6         | 0.93%   |
| 501-1000       | 5         | 0.78%   |
| 91-100         | 4         | 0.62%   |
| 41-50          | 3         | 0.47%   |
| 251-300        | 3         | 0.47%   |
| 131-140        | 2         | 0.31%   |
| 1-40           | 1         | 0.16%   |
| Unknown        | 1         | 0.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 310       | 49.05%  |
| 101-120       | 120       | 18.99%  |
| 161-240       | 93        | 14.72%  |
| 51-100        | 76        | 12.03%  |
| More than 240 | 29        | 4.59%   |
| 1-50          | 3         | 0.47%   |
| Unknown       | 1         | 0.16%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 435       | 77.82%  |
| 2     | 91        | 16.28%  |
| 3     | 16        | 2.86%   |
| 0     | 16        | 2.86%   |
| 4     | 1         | 0.18%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 318       | 38.78%  |
| Realtek Semiconductor                 | 282       | 34.39%  |
| Qualcomm Atheros                      | 59        | 7.2%    |
| Broadcom                              | 49        | 5.98%   |
| MediaTek                              | 35        | 4.27%   |
| Lenovo                                | 8         | 0.98%   |
| TP-Link                               | 7         | 0.85%   |
| Sierra Wireless                       | 6         | 0.73%   |
| Broadcom Limited                      | 6         | 0.73%   |
| Samsung Electronics                   | 5         | 0.61%   |
| Qualcomm                              | 5         | 0.61%   |
| DisplayLink                           | 5         | 0.61%   |
| ASIX Electronics                      | 5         | 0.61%   |
| Ralink Technology                     | 3         | 0.37%   |
| Qualcomm Atheros Communications       | 3         | 0.37%   |
| OPPO Electronics                      | 3         | 0.37%   |
| Microsoft                             | 3         | 0.37%   |
| Ralink                                | 2         | 0.24%   |
| Ericsson Business Mobile Networks     | 2         | 0.24%   |
| Dell                                  | 2         | 0.24%   |
| Xiaomi                                | 1         | 0.12%   |
| WEMOS.CC                              | 1         | 0.12%   |
| Quectel Wireless Solutions            | 1         | 0.12%   |
| Qualcomm Technologies                 | 1         | 0.12%   |
| OnePlus Technology (Shenzhen)         | 1         | 0.12%   |
| Nvidia                                | 1         | 0.12%   |
| NetGear                               | 1         | 0.12%   |
| JMicron Technology                    | 1         | 0.12%   |
| Hewlett-Packard                       | 1         | 0.12%   |
| Google                                | 1         | 0.12%   |
| Bose                                  | 1         | 0.12%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.12%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 170       | 17.15%  |
| Intel Wi-Fi 6 AX201                                               | 43        | 4.34%   |
| Intel Wi-Fi 6 AX200                                               | 36        | 3.63%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 32        | 3.23%   |
| Intel Wireless 8265 / 8275                                        | 28        | 2.83%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 25        | 2.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 23        | 2.32%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 23        | 2.32%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 22        | 2.22%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 21        | 2.12%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 19        | 1.92%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 18        | 1.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 18        | 1.82%   |
| Intel Wireless 7265                                               | 17        | 1.72%   |
| Intel Wireless 7260                                               | 15        | 1.51%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 15        | 1.51%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 15        | 1.51%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 12        | 1.21%   |
| Intel Ethernet Connection (4) I219-LM                             | 12        | 1.21%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 12        | 1.21%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 11        | 1.11%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 11        | 1.11%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 11        | 1.11%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 10        | 1.01%   |
| Intel Wireless 8260                                               | 10        | 1.01%   |
| Realtek RTL8125 2.5GbE Controller                                 | 9         | 0.91%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 9         | 0.91%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 9         | 0.91%   |
| Broadcom BCM43142 802.11b/g/n                                     | 9         | 0.91%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 8         | 0.81%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 8         | 0.81%   |
| Intel Ethernet Connection I217-LM                                 | 8         | 0.81%   |
| Intel Ethernet Connection (4) I219-V                              | 7         | 0.71%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 0.61%   |
| Intel Wireless 3165                                               | 6         | 0.61%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 6         | 0.61%   |
| Sierra Wireless EM7455                                            | 5         | 0.5%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 5         | 0.5%    |
| Intel Ethernet Connection I219-LM                                 | 5         | 0.5%    |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 311       | 54.47%  |
| Realtek Semiconductor                 | 96        | 16.81%  |
| Qualcomm Atheros                      | 51        | 8.93%   |
| Broadcom                              | 46        | 8.06%   |
| MediaTek                              | 34        | 5.95%   |
| Sierra Wireless                       | 6         | 1.05%   |
| TP-Link                               | 5         | 0.88%   |
| Broadcom Limited                      | 5         | 0.88%   |
| Ralink Technology                     | 3         | 0.53%   |
| Qualcomm Atheros Communications       | 3         | 0.53%   |
| Qualcomm                              | 3         | 0.53%   |
| Ralink                                | 2         | 0.35%   |
| Quectel Wireless Solutions            | 1         | 0.18%   |
| Qualcomm Technologies                 | 1         | 0.18%   |
| NetGear                               | 1         | 0.18%   |
| Microsoft                             | 1         | 0.18%   |
| Dell                                  | 1         | 0.18%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.18%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                            | 43        | 7.5%    |
| Intel Wi-Fi 6 AX200                                            | 36        | 6.28%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 32        | 5.58%   |
| Intel Wireless 8265 / 8275                                     | 28        | 4.89%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 23        | 4.01%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 22        | 3.84%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 21        | 3.66%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 19        | 3.32%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 18        | 3.14%   |
| Intel Wireless 7265                                            | 17        | 2.97%   |
| Intel Wireless 7260                                            | 15        | 2.62%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 15        | 2.62%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 15        | 2.62%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 12        | 2.09%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 12        | 2.09%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 11        | 1.92%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 11        | 1.92%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 11        | 1.92%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 10        | 1.75%   |
| Intel Wireless 8260                                            | 10        | 1.75%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 9         | 1.57%   |
| Broadcom BCM43142 802.11b/g/n                                  | 9         | 1.57%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 8         | 1.4%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 8         | 1.4%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 6         | 1.05%   |
| Intel Wireless 3165                                            | 6         | 1.05%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 6         | 1.05%   |
| Sierra Wireless EM7455                                         | 5         | 0.87%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 5         | 0.87%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 4         | 0.7%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 4         | 0.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 0.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 4         | 0.7%    |
| Intel Wireless-AC 9260                                         | 4         | 0.7%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 4         | 0.7%    |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 4         | 0.7%    |
| Broadcom BCM4350 802.11ac Wireless Network Adapter             | 4         | 0.7%    |
| Broadcom BCM43228 802.11a/b/g/n                                | 4         | 0.7%    |
| TP-Link 802.11ac WLAN Adapter                                  | 3         | 0.52%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 3         | 0.52%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 229       | 56.82%  |
| Intel                         | 108       | 26.8%   |
| Qualcomm Atheros              | 14        | 3.47%   |
| Broadcom                      | 13        | 3.23%   |
| Lenovo                        | 8         | 1.99%   |
| Samsung Electronics           | 5         | 1.24%   |
| DisplayLink                   | 5         | 1.24%   |
| ASIX Electronics              | 5         | 1.24%   |
| OPPO Electronics              | 3         | 0.74%   |
| TP-Link                       | 2         | 0.5%    |
| Qualcomm                      | 2         | 0.5%    |
| Microsoft                     | 2         | 0.5%    |
| Xiaomi                        | 1         | 0.25%   |
| OnePlus Technology (Shenzhen) | 1         | 0.25%   |
| Nvidia                        | 1         | 0.25%   |
| MediaTek                      | 1         | 0.25%   |
| JMicron Technology            | 1         | 0.25%   |
| Google                        | 1         | 0.25%   |
| Broadcom Limited              | 1         | 0.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 170       | 41.36%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 25        | 6.08%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 23        | 5.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 18        | 4.38%   |
| Intel Ethernet Connection (4) I219-LM                             | 12        | 2.92%   |
| Realtek RTL8125 2.5GbE Controller                                 | 9         | 2.19%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 9         | 2.19%   |
| Intel Ethernet Connection I217-LM                                 | 8         | 1.95%   |
| Intel Ethernet Connection (4) I219-V                              | 7         | 1.7%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 5         | 1.22%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 1.22%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 1.22%   |
| Intel Ethernet Connection (16) I219-LM                            | 5         | 1.22%   |
| ASIX AX88179 Gigabit Ethernet                                     | 5         | 1.22%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 4         | 0.97%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 0.97%   |
| Intel Ethernet Connection (7) I219-LM                             | 4         | 0.97%   |
| Intel Ethernet Connection (16) I219-V                             | 4         | 0.97%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 0.73%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 0.73%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 3         | 0.73%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 0.73%   |
| Intel Ethernet Connection (6) I219-LM                             | 3         | 0.73%   |
| Intel Ethernet Connection (13) I219-LM                            | 3         | 0.73%   |
| Intel Ethernet Connection (10) I219-LM                            | 3         | 0.73%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.73%   |
| DisplayLink Dell Universal Dock D6000                             | 3         | 0.73%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 2         | 0.49%   |
| Qualcomm Fairphone 4 5G                                           | 2         | 0.49%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.49%   |
| OPPO SM8350-MTP _SN:1518BD09                                      | 2         | 0.49%   |
| Intel WiMAX Connection 2400m                                      | 2         | 0.49%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.49%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.49%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.49%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.49%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 0.49%   |
| Intel Ethernet Connection (11) I219-LM                            | 2         | 0.49%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 0.49%   |
| Intel 82566MM Gigabit Network Connection                          | 2         | 0.49%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 545       | 58.48%  |
| Ethernet | 380       | 40.77%  |
| Modem    | 6         | 0.64%   |
| Unknown  | 1         | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 472       | 80.68%  |
| Ethernet | 113       | 19.32%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 329       | 59.49%  |
| 1     | 204       | 36.89%  |
| 0     | 13        | 2.35%   |
| 3     | 7         | 1.27%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 386       | 69.55%  |
| Yes  | 169       | 30.45%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 270       | 55.21%  |
| Realtek Semiconductor           | 53        | 10.84%  |
| Qualcomm Atheros Communications | 31        | 6.34%   |
| Foxconn / Hon Hai               | 29        | 5.93%   |
| IMC Networks                    | 27        | 5.52%   |
| Broadcom                        | 22        | 4.5%    |
| Apple                           | 18        | 3.68%   |
| Lite-On Technology              | 9         | 1.84%   |
| Realtek                         | 5         | 1.02%   |
| Dell                            | 5         | 1.02%   |
| USI                             | 4         | 0.82%   |
| Opticis                         | 3         | 0.61%   |
| Hewlett-Packard                 | 3         | 0.61%   |
| Cambridge Silicon Radio         | 3         | 0.61%   |
| Toshiba                         | 2         | 0.41%   |
| Foxconn International           | 2         | 0.41%   |
| Smart Modular Technologies      | 1         | 0.2%    |
| MediaTek                        | 1         | 0.2%    |
| Fujitsu                         | 1         | 0.2%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                                                               | 83        | 16.97%  |
| Intel Bluetooth wireless interface                                                  | 68        | 13.91%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 42        | 8.59%   |
| Realtek Bluetooth Radio                                                             | 41        | 8.38%   |
| Intel AX200 Bluetooth                                                               | 36        | 7.36%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 21        | 4.29%   |
| Intel Bluetooth Device                                                              | 20        | 4.09%   |
| Intel AX210 Bluetooth                                                               | 11        | 2.25%   |
| IMC Networks Wireless_Device                                                        | 11        | 2.25%   |
| IMC Networks Bluetooth Radio                                                        | 11        | 2.25%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 10        | 2.04%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 9         | 1.84%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 9         | 1.84%   |
| Apple Bluetooth Host Controller                                                     | 9         | 1.84%   |
| Apple Bluetooth USB Host Controller                                                 | 8         | 1.64%   |
| Realtek Bluetooth Radio                                                             | 5         | 1.02%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 5         | 1.02%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 5         | 1.02%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 5         | 1.02%   |
| USI Bluetooth Device                                                                | 4         | 0.82%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 4         | 0.82%   |
| IMC Networks Bluetooth Device                                                       | 4         | 0.82%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 4         | 0.82%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 4         | 0.82%   |
| Opticis Bluetooth Radio                                                             | 3         | 0.61%   |
| Lite-On Wireless_Device                                                             | 3         | 0.61%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 3         | 0.61%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 3         | 0.61%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 3         | 0.61%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 0.41%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 0.41%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 2         | 0.41%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 0.41%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 2         | 0.41%   |
| Dell DW375 Bluetooth Module                                                         | 2         | 0.41%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 2         | 0.41%   |
| Broadcom HP Portable SoftSailing                                                    | 2         | 0.41%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 2         | 0.41%   |
| Broadcom BCM20702A0                                                                 | 2         | 0.41%   |
| Broadcom BCM2045A0                                                                  | 2         | 0.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 413       | 56.97%  |
| AMD                     | 136       | 18.76%  |
| Nvidia                  | 115       | 15.86%  |
| Lenovo                  | 8         | 1.1%    |
| Logitech                | 7         | 0.97%   |
| Realtek Semiconductor   | 6         | 0.83%   |
| C-Media Electronics     | 5         | 0.69%   |
| JMTek                   | 4         | 0.55%   |
| GN Netcom               | 4         | 0.55%   |
| ASUSTek Computer        | 4         | 0.55%   |
| Razer USA               | 2         | 0.28%   |
| Kingston Technology     | 2         | 0.28%   |
| Hewlett-Packard         | 2         | 0.28%   |
| Zhaoxin                 | 1         | 0.14%   |
| Texas Instruments       | 1         | 0.14%   |
| Synaptics               | 1         | 0.14%   |
| SteelSeries ApS         | 1         | 0.14%   |
| Silicon Motion          | 1         | 0.14%   |
| Samson Technologies     | 1         | 0.14%   |
| OPPO Electronics        | 1         | 0.14%   |
| Microsoft               | 1         | 0.14%   |
| Harman                  | 1         | 0.14%   |
| Focusrite-Novation      | 1         | 0.14%   |
| FIFINE Microphones      | 1         | 0.14%   |
| DCMT Technology         | 1         | 0.14%   |
| Creative Technology     | 1         | 0.14%   |
| Conexant Systems        | 1         | 0.14%   |
| Blue Microphones        | 1         | 0.14%   |
| BEHRINGER International | 1         | 0.14%   |
| Audio-Technica          | 1         | 0.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 113       | 12.81%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 66        | 7.48%   |
| Intel Sunrise Point-LP HD Audio                                            | 55        | 6.24%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 52        | 5.9%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 37        | 4.2%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 33        | 3.74%   |
| Intel Cannon Lake PCH cAVS                                                 | 28        | 3.17%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 24        | 2.72%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 22        | 2.49%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 21        | 2.38%   |
| Intel Comet Lake PCH-LP cAVS                                               | 20        | 2.27%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 20        | 2.27%   |
| Intel Comet Lake PCH cAVS                                                  | 19        | 2.15%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 17        | 1.93%   |
| Nvidia Audio device                                                        | 16        | 1.81%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 15        | 1.7%    |
| Intel Haswell-ULT HD Audio Controller                                      | 14        | 1.59%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 14        | 1.59%   |
| Intel Broadwell-U Audio Controller                                         | 14        | 1.59%   |
| Intel 8 Series HD Audio Controller                                         | 14        | 1.59%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 13        | 1.47%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 12        | 1.36%   |
| Nvidia GP107GL High Definition Audio Controller                            | 11        | 1.25%   |
| Intel CM238 HD Audio Controller                                            | 11        | 1.25%   |
| Nvidia GF108 High Definition Audio Controller                              | 10        | 1.13%   |
| Nvidia GA106 High Definition Audio Controller                              | 10        | 1.13%   |
| Nvidia GA104 High Definition Audio Controller                              | 9         | 1.02%   |
| Nvidia TU106 High Definition Audio Controller                              | 8         | 0.91%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 8         | 0.91%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 8         | 0.91%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 8         | 0.91%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 7         | 0.79%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 7         | 0.79%   |
| Realtek Semiconductor USB Audio                                            | 6         | 0.68%   |
| Nvidia GK107 HDMI Audio Controller                                         | 6         | 0.68%   |
| AMD FCH Azalia Controller                                                  | 6         | 0.68%   |
| Nvidia GP106 High Definition Audio Controller                              | 5         | 0.57%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 0.57%   |
| AMD Kabini HDMI/DP Audio                                                   | 5         | 0.57%   |
| AMD High Definition Audio Controller                                       | 5         | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 77        | 30.92%  |
| SK hynix            | 51        | 20.48%  |
| Micron Technology   | 44        | 17.67%  |
| Kingston            | 17        | 6.83%   |
| Crucial             | 16        | 6.43%   |
| Unknown             | 8         | 3.21%   |
| Ramaxel Technology  | 7         | 2.81%   |
| Teikon              | 5         | 2.01%   |
| A-DATA Technology   | 5         | 2.01%   |
| Unknown (ABCD)      | 4         | 1.61%   |
| Smart               | 2         | 0.8%    |
| Nanya Technology    | 2         | 0.8%    |
| Elpida              | 2         | 0.8%    |
| Corsair             | 2         | 0.8%    |
| Unknown             | 2         | 0.8%    |
| Patriot             | 1         | 0.4%    |
| Neo Forza           | 1         | 0.4%    |
| G.Skill             | 1         | 0.4%    |
| Avant               | 1         | 0.4%    |
| 4ea5                | 1         | 0.4%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 6         | 2.33%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 6         | 2.33%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 4         | 1.56%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 4         | 1.56%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 1.56%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 1.56%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 3         | 1.17%   |
| Teikon RAM TMA81GS6AFR8N-UHSC 8GB SODIMM DDR4 2400MT/s           | 3         | 1.17%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 3         | 1.17%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 1.17%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 3         | 1.17%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 3         | 1.17%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.17%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.17%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 1.17%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 1.17%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.17%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s            | 3         | 1.17%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 2         | 0.78%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 2         | 0.78%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 0.78%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 0.78%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.78%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s        | 2         | 0.78%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 0.78%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.78%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.78%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 2         | 0.78%   |
| Samsung RAM M471A5244CB0-CTD 4GB DDR4 2667MT/s                   | 2         | 0.78%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.78%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.78%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 0.78%   |
| Samsung RAM K4EBE304EB-EGCF 8GB Row Of Chips LPDDR3 1867MT/s     | 2         | 0.78%   |
| Micron RAM 8ATF2G64HZ-3G2E2 16GB SODIMM DDR4 3200MT/s            | 2         | 0.78%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.78%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 2         | 0.78%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 2         | 0.78%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.78%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.78%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 2         | 0.78%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 124       | 58.77%  |
| DDR3   | 34        | 16.11%  |
| LPDDR4 | 20        | 9.48%   |
| LPDDR3 | 12        | 5.69%   |
| LPDDR5 | 11        | 5.21%   |
| DDR5   | 9         | 4.27%   |
| DDR2   | 1         | 0.47%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 169       | 78.97%  |
| Row Of Chips | 41        | 19.16%  |
| Unknown      | 4         | 1.87%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 104       | 46.02%  |
| 4096  | 52        | 23.01%  |
| 16384 | 45        | 19.91%  |
| 2048  | 15        | 6.64%   |
| 32768 | 9         | 3.98%   |
| 1024  | 1         | 0.44%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 70        | 31.11%  |
| 2667    | 45        | 20%     |
| 1600    | 26        | 11.56%  |
| 2400    | 15        | 6.67%   |
| 4267    | 12        | 5.33%   |
| 6400    | 11        | 4.89%   |
| 2133    | 11        | 4.89%   |
| 4800    | 9         | 4%      |
| 1334    | 7         | 3.11%   |
| 3266    | 4         | 1.78%   |
| 1867    | 4         | 1.78%   |
| 1333    | 3         | 1.33%   |
| 4266    | 2         | 0.89%   |
| 1066    | 2         | 0.89%   |
| 1067    | 1         | 0.44%   |
| 800     | 1         | 0.44%   |
| 667     | 1         | 0.44%   |
| Unknown | 1         | 0.44%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 1         | 100%    |

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

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 92        | 18.47%  |
| IMC Networks                           | 68        | 13.65%  |
| Microdia                               | 49        | 9.84%   |
| Quanta                                 | 39        | 7.83%   |
| Realtek Semiconductor                  | 32        | 6.43%   |
| Bison Electronics                      | 30        | 6.02%   |
| Acer                                   | 26        | 5.22%   |
| Sunplus Innovation Technology          | 23        | 4.62%   |
| Syntek                                 | 17        | 3.41%   |
| Cheng Uei Precision Industry (Foxlink) | 17        | 3.41%   |
| Sonix Technology                       | 16        | 3.21%   |
| Luxvisions Innotech Limited            | 15        | 3.01%   |
| Apple                                  | 15        | 3.01%   |
| Logitech                               | 11        | 2.21%   |
| Lite-On Technology                     | 9         | 1.81%   |
| SunplusIT                              | 7         | 1.41%   |
| Suyin                                  | 5         | 1%      |
| Silicon Motion                         | 3         | 0.6%    |
| Alcor Micro                            | 3         | 0.6%    |
| ShineTech                              | 2         | 0.4%    |
| Shenzhen Kingcome Optoelectronic       | 2         | 0.4%    |
| Ricoh                                  | 2         | 0.4%    |
| Primax Electronics                     | 2         | 0.4%    |
| Lenovo                                 | 2         | 0.4%    |
| icSpring                               | 2         | 0.4%    |
| Unknown                                | 2         | 0.4%    |
| ZOOM                                   | 1         | 0.2%    |
| Remo Tech                              | 1         | 0.2%    |
| Razer USA                              | 1         | 0.2%    |
| MacroSilicon                           | 1         | 0.2%    |
| LG Electronics                         | 1         | 0.2%    |
| BRS 2Mp Camera                         | 1         | 0.2%    |
| 3730304231385031324E56                 | 1         | 0.2%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                   | 34        | 6.8%    |
| Chicony Integrated Camera                                       | 31        | 6.2%    |
| IMC Networks USB2.0 HD UVC WebCam                               | 22        | 4.4%    |
| IMC Networks Integrated Camera                                  | 22        | 4.4%    |
| Realtek Integrated_Webcam_HD                                    | 16        | 3.2%    |
| Syntek Integrated Camera                                        | 12        | 2.4%    |
| Acer Integrated Camera                                          | 11        | 2.2%    |
| Apple FaceTime HD Camera                                        | 9         | 1.8%    |
| Sonix USB2.0 HD UVC WebCam                                      | 8         | 1.6%    |
| Chicony Integrated Camera (1280x720@30)                         | 8         | 1.6%    |
| Chicony HD WebCam                                               | 8         | 1.6%    |
| Bison Integrated Camera                                         | 8         | 1.6%    |
| Sonix USB2.0 FHD UVC WebCam                                     | 7         | 1.4%    |
| Sunplus Integrated_Webcam_HD                                    | 6         | 1.2%    |
| Quanta HP Wide Vision HD Camera                                 | 6         | 1.2%    |
| Quanta HD User Facing                                           | 6         | 1.2%    |
| Lite-On Integrated Camera                                       | 6         | 1.2%    |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 6         | 1.2%    |
| Luxvisions Innotech Limited Integrated Camera                   | 5         | 1%      |
| Chicony HP TrueVision HD Camera                                 | 5         | 1%      |
| Acer Integrated RGB Camera                                      | 5         | 1%      |
| Acer BisonCam,NB Pro                                            | 5         | 1%      |
| Realtek USB Camera                                              | 4         | 0.8%    |
| Quanta VGA WebCam                                               | 4         | 0.8%    |
| Quanta HP HD Camera                                             | 4         | 0.8%    |
| Quanta ACER HD User Facing                                      | 4         | 0.8%    |
| Microdia Integrated_Webcam_FHD                                  | 4         | 0.8%    |
| Luxvisions Innotech Limited HP Wide Vision HD Camera            | 4         | 0.8%    |
| IMC Networks USB2.0 VGA UVC WebCam                              | 4         | 0.8%    |
| IMC Networks ov9734_azurewave_camera                            | 4         | 0.8%    |
| Chicony HD User Facing                                          | 4         | 0.8%    |
| Bison SunplusIT Integrated Camera                               | 4         | 0.8%    |
| SunplusIT MTD camera                                            | 3         | 0.6%    |
| Realtek Lenovo EasyCamera                                       | 3         | 0.6%    |
| Quanta HP TrueVision HD Camera                                  | 3         | 0.6%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 3         | 0.6%    |
| Luxvisions Innotech Limited HP HD Camera                        | 3         | 0.6%    |
| Logitech HD Pro Webcam C920                                     | 3         | 0.6%    |
| IMC Networks XHC Camera                                         | 3         | 0.6%    |
| IMC Networks VGA UVC WebCam                                     | 3         | 0.6%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Shenzhen Goodix Technology         | 35        | 27.13%  |
| Synaptics                          | 33        | 25.58%  |
| Validity Sensors                   | 25        | 19.38%  |
| Elan Microelectronics              | 15        | 11.63%  |
| Upek                               | 8         | 6.2%    |
| LighTuning Technology              | 5         | 3.88%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 2.33%   |
| Samsung Electronics                | 2         | 1.55%   |
| AuthenTec                          | 2         | 1.55%   |
| STMicroelectronics                 | 1         | 0.78%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 25        | 19.38%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 17        | 13.18%  |
| Elan ELAN:ARM-M4                                                           | 11        | 8.53%   |
| Validity Sensors Synaptics WBDI                                            | 8         | 6.2%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 6.2%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 7         | 5.43%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 6         | 4.65%   |
| Shenzhen Goodix Fingerprint Reader                                         | 5         | 3.88%   |
| Shenzhen Goodix FingerPrint                                                | 5         | 3.88%   |
| Validity Sensors VFS491                                                    | 3         | 2.33%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 3         | 2.33%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 3         | 2.33%   |
| Elan ELAN:Fingerprint                                                      | 3         | 2.33%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 1.55%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 2         | 1.55%   |
| Synaptics UWP WBDI Device                                                  | 2         | 1.55%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 1.55%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 2         | 1.55%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 1.55%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.78%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.78%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.78%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.78%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.78%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 0.78%   |
| Synaptics UWP WBDI                                                         | 1         | 0.78%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 0.78%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 0.78%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.78%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 1         | 0.78%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 0.78%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.78%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 24        | 48%     |
| Alcor Micro           | 14        | 28%     |
| Lenovo                | 4         | 8%      |
| Upek                  | 3         | 6%      |
| O2 Micro              | 2         | 4%      |
| Gemalto (was Gemplus) | 2         | 4%      |
| Yubico.com            | 1         | 2%      |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 14        | 28%     |
| Broadcom 58200                                                               | 12        | 24%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 7         | 14%     |
| Lenovo Integrated Smart Card Reader                                          | 4         | 8%      |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 6%      |
| Broadcom 5880                                                                | 3         | 6%      |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 4%      |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 4%      |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 2%      |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 2%      |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 2%      |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 321       | 57.42%  |
| 1     | 190       | 33.99%  |
| 2     | 43        | 7.69%   |
| 3     | 3         | 0.54%   |
| 8     | 1         | 0.18%   |
| 6     | 1         | 0.18%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 126       | 42.86%  |
| Graphics card         | 82        | 27.89%  |
| Multimedia controller | 39        | 13.27%  |
| Net/wireless          | 20        | 6.8%    |
| Chipcard              | 10        | 3.4%    |
| Camera                | 6         | 2.04%   |
| Storage               | 3         | 1.02%   |
| Sound                 | 3         | 1.02%   |
| Card reader           | 3         | 1.02%   |
| Bluetooth             | 2         | 0.68%   |

