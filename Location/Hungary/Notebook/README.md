Linux in Hungary - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Hungary.

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

Total: 3530

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| eMachines     | E725                        | [8ba1579921](https://linux-hardware.org/?probe=8ba1579921) | Jul 01, 2022 |
| eMachines     | E725                        | [874b6bd7de](https://linux-hardware.org/?probe=874b6bd7de) | Jul 01, 2022 |
| eMachines     | E725                        | [021bcca061](https://linux-hardware.org/?probe=021bcca061) | Jun 30, 2022 |
| eMachines     | E725                        | [b8b332e92f](https://linux-hardware.org/?probe=b8b332e92f) | Jun 30, 2022 |
| HP            | EliteBook 8470p             | [96b07cbbd5](https://linux-hardware.org/?probe=96b07cbbd5) | Jun 30, 2022 |
| Dell          | Inspiron 5537               | [9758b4dcff](https://linux-hardware.org/?probe=9758b4dcff) | Jun 30, 2022 |
| HP            | EliteBook 840 G2            | [018b6945e1](https://linux-hardware.org/?probe=018b6945e1) | Jun 28, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [95db2f9536](https://linux-hardware.org/?probe=95db2f9536) | Jun 27, 2022 |
| eMachines     | E725                        | [3b272a4e25](https://linux-hardware.org/?probe=3b272a4e25) | Jun 26, 2022 |
| Acer          | Swift SF114-32              | [25e6653354](https://linux-hardware.org/?probe=25e6653354) | Jun 26, 2022 |
| Dell          | Latitude E5500              | [8002c78586](https://linux-hardware.org/?probe=8002c78586) | Jun 25, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | [8f9e6e12b1](https://linux-hardware.org/?probe=8f9e6e12b1) | Jun 25, 2022 |
| Dell          | Latitude E7450              | [a03ea66786](https://linux-hardware.org/?probe=a03ea66786) | Jun 24, 2022 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | [a26161ba2f](https://linux-hardware.org/?probe=a26161ba2f) | Jun 23, 2022 |
| Dell          | Latitude D630               | [60c9b1089c](https://linux-hardware.org/?probe=60c9b1089c) | Jun 23, 2022 |
| Dell          | Latitude E5500              | [ad849dbfe7](https://linux-hardware.org/?probe=ad849dbfe7) | Jun 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [f3ebefa03f](https://linux-hardware.org/?probe=f3ebefa03f) | Jun 21, 2022 |
| HP            | 255 G5 Notebook PC          | [d230e8311a](https://linux-hardware.org/?probe=d230e8311a) | Jun 21, 2022 |
| HP            | 255 G5 Notebook PC          | [7d1b0cfc99](https://linux-hardware.org/?probe=7d1b0cfc99) | Jun 21, 2022 |
| eMachines     | E725                        | [6e81be09d2](https://linux-hardware.org/?probe=6e81be09d2) | Jun 19, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [73f958fb35](https://linux-hardware.org/?probe=73f958fb35) | Jun 17, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [a7431ef0c5](https://linux-hardware.org/?probe=a7431ef0c5) | Jun 17, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [e9eb39efa4](https://linux-hardware.org/?probe=e9eb39efa4) | Jun 16, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [d4ad64d715](https://linux-hardware.org/?probe=d4ad64d715) | Jun 15, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [bffb7f61cb](https://linux-hardware.org/?probe=bffb7f61cb) | Jun 15, 2022 |
| HP            | x2 210                      | [8f6739cda0](https://linux-hardware.org/?probe=8f6739cda0) | Jun 15, 2022 |
| HP            | ProBook 4540s               | [934a74329f](https://linux-hardware.org/?probe=934a74329f) | Jun 14, 2022 |
| ASUSTek       | Zenbook UX5401ZA_UX5401Z... | [2b87adfa9f](https://linux-hardware.org/?probe=2b87adfa9f) | Jun 13, 2022 |
| Dell          | Inspiron 15-3567            | [013de61252](https://linux-hardware.org/?probe=013de61252) | Jun 12, 2022 |
| Dell          | Inspiron 15-3567            | [ad093b7b31](https://linux-hardware.org/?probe=ad093b7b31) | Jun 11, 2022 |
| Dell          | Latitude E6540              | [b1cc75656e](https://linux-hardware.org/?probe=b1cc75656e) | Jun 11, 2022 |
| HUAWEI        | WRT-WX9                     | [13dcf888fe](https://linux-hardware.org/?probe=13dcf888fe) | Jun 10, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [eb4a496e95](https://linux-hardware.org/?probe=eb4a496e95) | Jun 09, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [24b293410c](https://linux-hardware.org/?probe=24b293410c) | Jun 09, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [158a18f6d1](https://linux-hardware.org/?probe=158a18f6d1) | Jun 09, 2022 |
| HP            | Compaq 6710b (KE121EA#AK... | [940eb51107](https://linux-hardware.org/?probe=940eb51107) | Jun 09, 2022 |
| Lenovo        | Z50-70 20354                | [57582f68b6](https://linux-hardware.org/?probe=57582f68b6) | Jun 08, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [fce3696537](https://linux-hardware.org/?probe=fce3696537) | Jun 08, 2022 |
| Lenovo        | Z50-70 20354                | [870233669c](https://linux-hardware.org/?probe=870233669c) | Jun 07, 2022 |
| Lenovo        | ThinkPad X61 Tablet 7762... | [d2efe762b7](https://linux-hardware.org/?probe=d2efe762b7) | Jun 06, 2022 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [5f64f824aa](https://linux-hardware.org/?probe=5f64f824aa) | Jun 05, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [155a8dd1a5](https://linux-hardware.org/?probe=155a8dd1a5) | Jun 05, 2022 |
| Medion        | P6630                       | [c1de1611b8](https://linux-hardware.org/?probe=c1de1611b8) | Jun 04, 2022 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [b563da5d39](https://linux-hardware.org/?probe=b563da5d39) | Jun 04, 2022 |
| HP            | ProBook 650 G2              | [a580e923a7](https://linux-hardware.org/?probe=a580e923a7) | Jun 03, 2022 |
| HP            | ProBook 640 G8 Notebook ... | [15e4cca5bc](https://linux-hardware.org/?probe=15e4cca5bc) | Jun 03, 2022 |
| HP            | ProBook 640 G8 Notebook ... | [b99a9b1bce](https://linux-hardware.org/?probe=b99a9b1bce) | Jun 03, 2022 |
| HP            | ProBook 650 G2              | [27063b3b3a](https://linux-hardware.org/?probe=27063b3b3a) | Jun 03, 2022 |
| HP            | ProBook 640 G8 Notebook ... | [96768b6e5c](https://linux-hardware.org/?probe=96768b6e5c) | Jun 02, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | [d11a49f42b](https://linux-hardware.org/?probe=d11a49f42b) | Jun 02, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | [968decd1af](https://linux-hardware.org/?probe=968decd1af) | Jun 02, 2022 |
| Dell          | Latitude E6400              | [cea3337908](https://linux-hardware.org/?probe=cea3337908) | Jun 01, 2022 |
| HP            | 255 G5 Notebook PC          | [4ff7c85a84](https://linux-hardware.org/?probe=4ff7c85a84) | May 31, 2022 |
| HP            | 255 G5 Notebook PC          | [c65fb5ddb9](https://linux-hardware.org/?probe=c65fb5ddb9) | May 31, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [956299505f](https://linux-hardware.org/?probe=956299505f) | May 31, 2022 |
| HP            | EliteBook 8470p             | [6b22d31e8e](https://linux-hardware.org/?probe=6b22d31e8e) | May 31, 2022 |
| ASUSTek       | K53U                        | [efd067c3a8](https://linux-hardware.org/?probe=efd067c3a8) | May 30, 2022 |
| ASUSTek       | K53U                        | [a26756238b](https://linux-hardware.org/?probe=a26756238b) | May 30, 2022 |
| Dell          | Latitude E6230              | [068d9b4143](https://linux-hardware.org/?probe=068d9b4143) | May 29, 2022 |
| Dell          | Latitude E6230              | [c50bb14e9a](https://linux-hardware.org/?probe=c50bb14e9a) | May 29, 2022 |
| Medion        | P6630                       | [7f5b714dfc](https://linux-hardware.org/?probe=7f5b714dfc) | May 28, 2022 |
| HP            | 255 G5 Notebook PC          | [672f924aec](https://linux-hardware.org/?probe=672f924aec) | May 28, 2022 |
| ASUSTek       | K53U                        | [fdbe31f666](https://linux-hardware.org/?probe=fdbe31f666) | May 28, 2022 |
| HP            | 255 G5 Notebook PC          | [7f91291747](https://linux-hardware.org/?probe=7f91291747) | May 28, 2022 |
| ASUSTek       | K53U                        | [28565fc028](https://linux-hardware.org/?probe=28565fc028) | May 28, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [110903519d](https://linux-hardware.org/?probe=110903519d) | May 26, 2022 |
| HP            | 620                         | [b5bf98b16a](https://linux-hardware.org/?probe=b5bf98b16a) | May 23, 2022 |
| HP            | 620                         | [8bf9517a97](https://linux-hardware.org/?probe=8bf9517a97) | May 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [26d3a29dc1](https://linux-hardware.org/?probe=26d3a29dc1) | May 23, 2022 |
| HP            | Presario CQ58               | [bdf8b7e229](https://linux-hardware.org/?probe=bdf8b7e229) | May 22, 2022 |
| HP            | Presario CQ58               | [383a27dd29](https://linux-hardware.org/?probe=383a27dd29) | May 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [b128814505](https://linux-hardware.org/?probe=b128814505) | May 21, 2022 |
| Lenovo        | B590 20208                  | [b32a821a4c](https://linux-hardware.org/?probe=b32a821a4c) | May 21, 2022 |
| Lenovo        | B590 20208                  | [3386aeef48](https://linux-hardware.org/?probe=3386aeef48) | May 21, 2022 |
| Fujitsu       | LIFEBOOK U745               | [9003466ff8](https://linux-hardware.org/?probe=9003466ff8) | May 21, 2022 |
| Fujitsu       | LIFEBOOK U745               | [2e05001696](https://linux-hardware.org/?probe=2e05001696) | May 21, 2022 |
| HP            | 620                         | [babb1f392a](https://linux-hardware.org/?probe=babb1f392a) | May 21, 2022 |
| Dell          | Vostro 3500                 | [d30a648e90](https://linux-hardware.org/?probe=d30a648e90) | May 19, 2022 |
| Dell          | Inspiron 5759               | [bfe6579a0e](https://linux-hardware.org/?probe=bfe6579a0e) | May 16, 2022 |
| Lenovo        | G570 20079                  | [f4b9c3997d](https://linux-hardware.org/?probe=f4b9c3997d) | May 16, 2022 |
| Toshiba       | Satellite L775-18R          | [ec012c6b3d](https://linux-hardware.org/?probe=ec012c6b3d) | May 16, 2022 |
| Lenovo        | G580 20150                  | [75f2c0ab4e](https://linux-hardware.org/?probe=75f2c0ab4e) | May 15, 2022 |
| Lenovo        | G580 20150                  | [8d710ae7c3](https://linux-hardware.org/?probe=8d710ae7c3) | May 15, 2022 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | [758e2b869d](https://linux-hardware.org/?probe=758e2b869d) | May 15, 2022 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | [91c6da69a9](https://linux-hardware.org/?probe=91c6da69a9) | May 15, 2022 |
| Dell          | Latitude E6430              | [e805d60a6b](https://linux-hardware.org/?probe=e805d60a6b) | May 14, 2022 |
| Dell          | Vostro 3500                 | [f784f7eb95](https://linux-hardware.org/?probe=f784f7eb95) | May 14, 2022 |
| HP            | ProBook 640 G8 Notebook ... | [bfc1a518db](https://linux-hardware.org/?probe=bfc1a518db) | May 14, 2022 |
| HP            | 620                         | [62369d924a](https://linux-hardware.org/?probe=62369d924a) | May 12, 2022 |
| Unknown       | Unknown                     | [0099d17388](https://linux-hardware.org/?probe=0099d17388) | May 10, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [25787f8eb3](https://linux-hardware.org/?probe=25787f8eb3) | May 10, 2022 |
| Dell          | Latitude E6230              | [d9d1e38394](https://linux-hardware.org/?probe=d9d1e38394) | May 09, 2022 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [dd31ac3d4d](https://linux-hardware.org/?probe=dd31ac3d4d) | May 08, 2022 |
| HP            | EliteBook 2560p             | [ef54ce0eda](https://linux-hardware.org/?probe=ef54ce0eda) | May 06, 2022 |
| HP            | EliteBook 2560p             | [94a92586e6](https://linux-hardware.org/?probe=94a92586e6) | May 06, 2022 |
| Lenovo        | ThinkPad T460 20FMS6LB00    | [3d7e88cdae](https://linux-hardware.org/?probe=3d7e88cdae) | May 03, 2022 |
| ASUSTek       | GL552JX                     | [c91f42212d](https://linux-hardware.org/?probe=c91f42212d) | May 03, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [62f1d13e63](https://linux-hardware.org/?probe=62f1d13e63) | May 02, 2022 |
| Lenovo        | ThinkPad X240 20AL00FGMB    | [afba42bf24](https://linux-hardware.org/?probe=afba42bf24) | May 02, 2022 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [02872ac9a8](https://linux-hardware.org/?probe=02872ac9a8) | May 02, 2022 |
| HP            | ProBook 645 G4              | [0a4b56ae27](https://linux-hardware.org/?probe=0a4b56ae27) | Apr 29, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [ef265ae548](https://linux-hardware.org/?probe=ef265ae548) | Apr 29, 2022 |
| Dell          | Inspiron 3593               | [54087491d8](https://linux-hardware.org/?probe=54087491d8) | Apr 28, 2022 |
| HP            | ProBook 645 G4              | [1546b59830](https://linux-hardware.org/?probe=1546b59830) | Apr 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [382d77c2b0](https://linux-hardware.org/?probe=382d77c2b0) | Apr 28, 2022 |
| Toshiba       | NB550D                      | [386409d233](https://linux-hardware.org/?probe=386409d233) | Apr 24, 2022 |
| ASUSTek       | GL552JX                     | [dae470212d](https://linux-hardware.org/?probe=dae470212d) | Apr 22, 2022 |
| Acer          | Swift SF114-33              | [93239c624a](https://linux-hardware.org/?probe=93239c624a) | Apr 22, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [5a855c522f](https://linux-hardware.org/?probe=5a855c522f) | Apr 22, 2022 |
| HP            | EliteBook 8470p             | [c1623a9f89](https://linux-hardware.org/?probe=c1623a9f89) | Apr 21, 2022 |
| Dell          | Vostro 3580                 | [c34ed29ab2](https://linux-hardware.org/?probe=c34ed29ab2) | Apr 21, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [70547d6581](https://linux-hardware.org/?probe=70547d6581) | Apr 19, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [36e5a2229d](https://linux-hardware.org/?probe=36e5a2229d) | Apr 18, 2022 |
| Lenovo        | B590 20208                  | [af6b076e21](https://linux-hardware.org/?probe=af6b076e21) | Apr 18, 2022 |
| Hungaro Fl... | Navon Loop 360              | [48b6f0e313](https://linux-hardware.org/?probe=48b6f0e313) | Apr 18, 2022 |
| Hungaro Fl... | Navon Loop 360              | [cde65f88c1](https://linux-hardware.org/?probe=cde65f88c1) | Apr 17, 2022 |
| ASUSTek       | TP201SA                     | [2898b67bff](https://linux-hardware.org/?probe=2898b67bff) | Apr 16, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [a89ca51e1b](https://linux-hardware.org/?probe=a89ca51e1b) | Apr 15, 2022 |
| Fujitsu       | LIFEBOOK E743               | [43ee1b9237](https://linux-hardware.org/?probe=43ee1b9237) | Apr 14, 2022 |
| Dell          | G5 5587                     | [b3c44a59f0](https://linux-hardware.org/?probe=b3c44a59f0) | Apr 13, 2022 |
| Dell          | Inspiron 3537               | [88655213a1](https://linux-hardware.org/?probe=88655213a1) | Apr 12, 2022 |
| HP            | ProBook 470 G1              | [ee1f05022a](https://linux-hardware.org/?probe=ee1f05022a) | Apr 10, 2022 |
| Lenovo        | G580 20150                  | [00215e25c0](https://linux-hardware.org/?probe=00215e25c0) | Apr 10, 2022 |
| Dell          | Latitude 7480               | [b235ce5f92](https://linux-hardware.org/?probe=b235ce5f92) | Apr 10, 2022 |
| Fujitsu       | LIFEBOOK U745               | [9dc3653255](https://linux-hardware.org/?probe=9dc3653255) | Apr 09, 2022 |
| Valve         | Jupiter                     | [852b6fb53a](https://linux-hardware.org/?probe=852b6fb53a) | Apr 08, 2022 |
| ASUSTek       | N551JW                      | [3ddfbf37e2](https://linux-hardware.org/?probe=3ddfbf37e2) | Apr 08, 2022 |
| Lenovo        | Yoga Slim 7-14ARE05 82A2    | [ae77218dcf](https://linux-hardware.org/?probe=ae77218dcf) | Apr 07, 2022 |
| Toshiba       | TECRA A10                   | [b062d23fb7](https://linux-hardware.org/?probe=b062d23fb7) | Apr 07, 2022 |
| Dell          | Latitude E6530              | [a99419647f](https://linux-hardware.org/?probe=a99419647f) | Apr 07, 2022 |
| Lenovo        | ThinkPad T61 6458WK6        | [5303af9863](https://linux-hardware.org/?probe=5303af9863) | Apr 07, 2022 |
| Fujitsu       | LIFEBOOK U745               | [5d73ae026b](https://linux-hardware.org/?probe=5d73ae026b) | Apr 05, 2022 |
| Acer          | Swift SF114-32              | [3947799e36](https://linux-hardware.org/?probe=3947799e36) | Apr 05, 2022 |
| Acer          | TravelMate P215-41-G2       | [065554d2ad](https://linux-hardware.org/?probe=065554d2ad) | Apr 04, 2022 |
| Acer          | TravelMate P215-52          | [a5d16dc93e](https://linux-hardware.org/?probe=a5d16dc93e) | Apr 03, 2022 |
| Samsung       | RV410/RV510/S3510/E3510     | [495e271511](https://linux-hardware.org/?probe=495e271511) | Apr 03, 2022 |
| Lenovo        | G50-30 80G0                 | [46775a18b0](https://linux-hardware.org/?probe=46775a18b0) | Apr 03, 2022 |
| Dell          | Latitude E5420              | [a60c1a4785](https://linux-hardware.org/?probe=a60c1a4785) | Apr 03, 2022 |
| Lenovo        | G50-30 80G0                 | [be1de1d236](https://linux-hardware.org/?probe=be1de1d236) | Apr 03, 2022 |
| Lenovo        | G780 20138                  | [a7cad8a09a](https://linux-hardware.org/?probe=a7cad8a09a) | Apr 02, 2022 |
| HP            | Pavilion 15                 | [98be421e4c](https://linux-hardware.org/?probe=98be421e4c) | Apr 02, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [8ae9fd4940](https://linux-hardware.org/?probe=8ae9fd4940) | Apr 02, 2022 |
| Acer          | TravelMate P215-52          | [752d283e54](https://linux-hardware.org/?probe=752d283e54) | Apr 01, 2022 |
| Samsung       | RV410/RV510/S3510/E3510     | [666c8daa31](https://linux-hardware.org/?probe=666c8daa31) | Apr 01, 2022 |
| HP            | Unknown                     | [c6a02a2df5](https://linux-hardware.org/?probe=c6a02a2df5) | Apr 01, 2022 |
| HP            | Unknown                     | [71ae764e9f](https://linux-hardware.org/?probe=71ae764e9f) | Apr 01, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [1a946533b6](https://linux-hardware.org/?probe=1a946533b6) | Mar 31, 2022 |
| Dell          | Latitude E6420              | [2a0c2610ea](https://linux-hardware.org/?probe=2a0c2610ea) | Mar 30, 2022 |
| eMachines     | E725                        | [475f79831d](https://linux-hardware.org/?probe=475f79831d) | Mar 29, 2022 |
| eMachines     | E725                        | [f8e777c318](https://linux-hardware.org/?probe=f8e777c318) | Mar 29, 2022 |
| HP            | ProBook 640 G8 Notebook ... | [60da33f3aa](https://linux-hardware.org/?probe=60da33f3aa) | Mar 28, 2022 |
| Dell          | System XPS 15Z              | [3e4b6f7b57](https://linux-hardware.org/?probe=3e4b6f7b57) | Mar 28, 2022 |
| Dell          | Latitude E5540              | [838350f357](https://linux-hardware.org/?probe=838350f357) | Mar 28, 2022 |
| Lenovo        | ThinkPad W530 2463A58       | [8e8bd0aad5](https://linux-hardware.org/?probe=8e8bd0aad5) | Mar 28, 2022 |
| Lenovo        | G580 20150                  | [ec430f1afc](https://linux-hardware.org/?probe=ec430f1afc) | Mar 27, 2022 |
| Dell          | Inspiron M5030              | [a36af1ef0f](https://linux-hardware.org/?probe=a36af1ef0f) | Mar 27, 2022 |
| Dell          | Inspiron M5030              | [c3b9926b94](https://linux-hardware.org/?probe=c3b9926b94) | Mar 27, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5555        | [b557a2005c](https://linux-hardware.org/?probe=b557a2005c) | Mar 27, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [64606b8247](https://linux-hardware.org/?probe=64606b8247) | Mar 26, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [25ad4e35b9](https://linux-hardware.org/?probe=25ad4e35b9) | Mar 26, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [c527847cd3](https://linux-hardware.org/?probe=c527847cd3) | Mar 25, 2022 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | [ed4ed6851f](https://linux-hardware.org/?probe=ed4ed6851f) | Mar 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [c136393c4b](https://linux-hardware.org/?probe=c136393c4b) | Mar 23, 2022 |
| Dell          | Latitude E7450              | [57111f23b4](https://linux-hardware.org/?probe=57111f23b4) | Mar 23, 2022 |
| Dell          | Latitude E7450              | [ad41ea623a](https://linux-hardware.org/?probe=ad41ea623a) | Mar 23, 2022 |
| Lenovo        | G565 20071                  | [40cf723fac](https://linux-hardware.org/?probe=40cf723fac) | Mar 23, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [5b8c4678af](https://linux-hardware.org/?probe=5b8c4678af) | Mar 22, 2022 |
| Acer          | TravelMate P238-G2-M        | [7aa968ca84](https://linux-hardware.org/?probe=7aa968ca84) | Mar 22, 2022 |
| Apple         | MacBookPro6,2               | [5611c90f20](https://linux-hardware.org/?probe=5611c90f20) | Mar 21, 2022 |
| Apple         | MacBookPro6,2               | [2a71c88e71](https://linux-hardware.org/?probe=2a71c88e71) | Mar 21, 2022 |
| Lenovo        | Z50-70 20354                | [85236d7863](https://linux-hardware.org/?probe=85236d7863) | Mar 20, 2022 |
| Lenovo        | Z50-70 20354                | [2391a2db23](https://linux-hardware.org/?probe=2391a2db23) | Mar 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [3607969e9d](https://linux-hardware.org/?probe=3607969e9d) | Mar 20, 2022 |
| Lenovo        | G505s 20255                 | [9f18cfb328](https://linux-hardware.org/?probe=9f18cfb328) | Mar 19, 2022 |
| Lenovo        | G505s 20255                 | [716d4ed3be](https://linux-hardware.org/?probe=716d4ed3be) | Mar 18, 2022 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | [6ae5708fe3](https://linux-hardware.org/?probe=6ae5708fe3) | Mar 16, 2022 |
| Fujitsu       | LIFEBOOK U745               | [e8e4e5d953](https://linux-hardware.org/?probe=e8e4e5d953) | Mar 15, 2022 |
| HP            | 650                         | [3266dba7df](https://linux-hardware.org/?probe=3266dba7df) | Mar 14, 2022 |
| HP            | 650                         | [54df12f572](https://linux-hardware.org/?probe=54df12f572) | Mar 14, 2022 |
| Fujitsu Si... | AMILO Xi 3650               | [6f416ff93b](https://linux-hardware.org/?probe=6f416ff93b) | Mar 13, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [79a7c69b79](https://linux-hardware.org/?probe=79a7c69b79) | Mar 13, 2022 |
| ASUSTek       | Strix 15 GL503GE            | [29c3688c05](https://linux-hardware.org/?probe=29c3688c05) | Mar 13, 2022 |
| ASUSTek       | X541UVK                     | [74ba6d5353](https://linux-hardware.org/?probe=74ba6d5353) | Mar 12, 2022 |
| eMachines     | E725                        | [05b157a340](https://linux-hardware.org/?probe=05b157a340) | Mar 12, 2022 |
| Packard Be... | EasyNote TS13SB             | [9d702d33cb](https://linux-hardware.org/?probe=9d702d33cb) | Mar 12, 2022 |
| HP            | Pavilion 17                 | [f5ff2a8a14](https://linux-hardware.org/?probe=f5ff2a8a14) | Mar 10, 2022 |
| HP            | Pavilion 17                 | [b6bfe40827](https://linux-hardware.org/?probe=b6bfe40827) | Mar 10, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [299209635a](https://linux-hardware.org/?probe=299209635a) | Mar 09, 2022 |
| Dell          | Latitude E6230              | [20ca54a46c](https://linux-hardware.org/?probe=20ca54a46c) | Mar 09, 2022 |
| ASUSTek       | BU401LA                     | [2df54ef02e](https://linux-hardware.org/?probe=2df54ef02e) | Mar 08, 2022 |
| Sony          | SVS13118GBB                 | [64dc07d0af](https://linux-hardware.org/?probe=64dc07d0af) | Mar 08, 2022 |
| Sony          | SVS13118GBB                 | [76afe39f5e](https://linux-hardware.org/?probe=76afe39f5e) | Mar 08, 2022 |
| Dell          | Inspiron 5570               | [c2d75f15a4](https://linux-hardware.org/?probe=c2d75f15a4) | Mar 05, 2022 |
| Dell          | Inspiron 5570               | [8965098d65](https://linux-hardware.org/?probe=8965098d65) | Mar 05, 2022 |
| HP            | Compaq 6710b (GB890EA#AK... | [c313b8ee39](https://linux-hardware.org/?probe=c313b8ee39) | Mar 05, 2022 |
| HP            | Compaq 6720s                | [f83b83214e](https://linux-hardware.org/?probe=f83b83214e) | Mar 04, 2022 |
| HP            | Pavilion dv6700             | [4702dab234](https://linux-hardware.org/?probe=4702dab234) | Mar 04, 2022 |
| Acer          | Aspire A315-57G             | [83f0bbb366](https://linux-hardware.org/?probe=83f0bbb366) | Mar 04, 2022 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | [a3aed9d375](https://linux-hardware.org/?probe=a3aed9d375) | Mar 03, 2022 |
| Dell          | Latitude E5540              | [0e5ce3685b](https://linux-hardware.org/?probe=0e5ce3685b) | Mar 02, 2022 |
| HP            | Compaq 6720s                | [9d3882f4c5](https://linux-hardware.org/?probe=9d3882f4c5) | Mar 02, 2022 |
| Acer          | Aspire ES1-571              | [acc272ef5a](https://linux-hardware.org/?probe=acc272ef5a) | Feb 28, 2022 |
| Acer          | Aspire ES1-571              | [cf51003466](https://linux-hardware.org/?probe=cf51003466) | Feb 28, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [6875bd20ab](https://linux-hardware.org/?probe=6875bd20ab) | Feb 28, 2022 |
| Dell          | Latitude 5480               | [43ae797918](https://linux-hardware.org/?probe=43ae797918) | Feb 28, 2022 |
| ASUSTek       | K53U                        | [16c5ebe7c3](https://linux-hardware.org/?probe=16c5ebe7c3) | Feb 27, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | [5f74ba2ea7](https://linux-hardware.org/?probe=5f74ba2ea7) | Feb 27, 2022 |
| Dell          | Inspiron 3583               | [83dec4f285](https://linux-hardware.org/?probe=83dec4f285) | Feb 26, 2022 |
| HP            | ProBook 6470b               | [76e9b5f896](https://linux-hardware.org/?probe=76e9b5f896) | Feb 26, 2022 |
| HP            | ProBook 6470b               | [3b86510929](https://linux-hardware.org/?probe=3b86510929) | Feb 26, 2022 |
| HP            | ProBook 430 G5              | [1cf6d56319](https://linux-hardware.org/?probe=1cf6d56319) | Feb 25, 2022 |
| HP            | Laptop 14s-fq0xxx           | [8e06c09393](https://linux-hardware.org/?probe=8e06c09393) | Feb 25, 2022 |
| HP            | Pavilion 17                 | [97c44abef4](https://linux-hardware.org/?probe=97c44abef4) | Feb 22, 2022 |
| Medion        | Erazer P7647 MD60803        | [e958bf729a](https://linux-hardware.org/?probe=e958bf729a) | Feb 22, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [80ceccfdc7](https://linux-hardware.org/?probe=80ceccfdc7) | Feb 22, 2022 |
| eMachines     | E725                        | [4aa5e2b180](https://linux-hardware.org/?probe=4aa5e2b180) | Feb 21, 2022 |
| Dell          | Latitude D630               | [067e57eab9](https://linux-hardware.org/?probe=067e57eab9) | Feb 20, 2022 |
| Packard Be... | EasyNote ENLG81BA           | [fb281e6c00](https://linux-hardware.org/?probe=fb281e6c00) | Feb 20, 2022 |
| Packard Be... | EasyNote ENLG81BA           | [58e5e2c95c](https://linux-hardware.org/?probe=58e5e2c95c) | Feb 20, 2022 |
| Dell          | Inspiron 7737               | [cc09141607](https://linux-hardware.org/?probe=cc09141607) | Feb 19, 2022 |
| Acer          | Aspire E5-571G              | [276c87bdc5](https://linux-hardware.org/?probe=276c87bdc5) | Feb 19, 2022 |
| ASUSTek       | X550VX                      | [2cf18df101](https://linux-hardware.org/?probe=2cf18df101) | Feb 19, 2022 |
| HP            | Compaq 6530b (NJ641UC#AB... | [ab91a058c0](https://linux-hardware.org/?probe=ab91a058c0) | Feb 19, 2022 |
| HP            | Compaq 6530b (NJ641UC#AB... | [70ab79b3b4](https://linux-hardware.org/?probe=70ab79b3b4) | Feb 19, 2022 |
| Lenovo        | ThinkPad T470 20HES18R2G    | [bb387d7a5a](https://linux-hardware.org/?probe=bb387d7a5a) | Feb 18, 2022 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | [dc8d1eb5eb](https://linux-hardware.org/?probe=dc8d1eb5eb) | Feb 18, 2022 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | [58b92a0176](https://linux-hardware.org/?probe=58b92a0176) | Feb 18, 2022 |
| HP            | ProBook 6470b               | [4c37154dc3](https://linux-hardware.org/?probe=4c37154dc3) | Feb 17, 2022 |
| Dell          | Latitude E5430 non-vPro     | [a7afdd9d95](https://linux-hardware.org/?probe=a7afdd9d95) | Feb 17, 2022 |
| Lenovo        | ThinkPad T450 20BUS0VH08    | [c896752de0](https://linux-hardware.org/?probe=c896752de0) | Feb 17, 2022 |
| HP            | Pavilion 17                 | [166e1147d2](https://linux-hardware.org/?probe=166e1147d2) | Feb 17, 2022 |
| Dell          | XPS 13 7390                 | [5bca4c6855](https://linux-hardware.org/?probe=5bca4c6855) | Feb 16, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [c5eab4c7d9](https://linux-hardware.org/?probe=c5eab4c7d9) | Feb 16, 2022 |
| HP            | EliteBook 8570w             | [bdfcf410e6](https://linux-hardware.org/?probe=bdfcf410e6) | Feb 16, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [23e6094c83](https://linux-hardware.org/?probe=23e6094c83) | Feb 16, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [a0a9cf96a8](https://linux-hardware.org/?probe=a0a9cf96a8) | Feb 15, 2022 |
| HP            | Compaq 6530b (NJ641UC#AB... | [357881c642](https://linux-hardware.org/?probe=357881c642) | Feb 15, 2022 |
| Acer          | Aspire 7750G                | [fa1880e655](https://linux-hardware.org/?probe=fa1880e655) | Feb 15, 2022 |
| Dell          | Latitude D630               | [17929b78ff](https://linux-hardware.org/?probe=17929b78ff) | Feb 15, 2022 |
| HP            | Presario CQ57               | [14148f0279](https://linux-hardware.org/?probe=14148f0279) | Feb 15, 2022 |
| HP            | 620                         | [bd89b469e4](https://linux-hardware.org/?probe=bd89b469e4) | Feb 14, 2022 |
| HP            | Compaq 6530b (NJ641UC#AB... | [1cfe8d6cc4](https://linux-hardware.org/?probe=1cfe8d6cc4) | Feb 14, 2022 |
| HP            | 250 G1                      | [0c35eb7e0c](https://linux-hardware.org/?probe=0c35eb7e0c) | Feb 14, 2022 |
| HP            | 250 G1                      | [0e47dcd6ff](https://linux-hardware.org/?probe=0e47dcd6ff) | Feb 14, 2022 |
| Lenovo        | ThinkPad T410 2537VFQ       | [004fd97714](https://linux-hardware.org/?probe=004fd97714) | Feb 13, 2022 |
| Lenovo        | 3000 N500 423332G           | [5f673420ca](https://linux-hardware.org/?probe=5f673420ca) | Feb 13, 2022 |
| Fujitsu Si... | LIFEBOOK S7110              | [a3f36901a2](https://linux-hardware.org/?probe=a3f36901a2) | Feb 13, 2022 |
| HP            | Pavilion 17                 | [7e4c073be5](https://linux-hardware.org/?probe=7e4c073be5) | Feb 13, 2022 |
| Lenovo        | ThinkPad W510 4876A46       | [d4b8bb3ed1](https://linux-hardware.org/?probe=d4b8bb3ed1) | Feb 12, 2022 |
| HP            | EliteBook 745 G3            | [a84f254fbc](https://linux-hardware.org/?probe=a84f254fbc) | Feb 12, 2022 |
| HP            | EliteBook 745 G3            | [26ed6eddae](https://linux-hardware.org/?probe=26ed6eddae) | Feb 12, 2022 |
| Lenovo        | G50-30 80G0                 | [a72bae3658](https://linux-hardware.org/?probe=a72bae3658) | Feb 12, 2022 |
| Lenovo        | 3000 N500 423332G           | [aa5079471b](https://linux-hardware.org/?probe=aa5079471b) | Feb 12, 2022 |
| Acer          | TravelMate 8571             | [df168b8134](https://linux-hardware.org/?probe=df168b8134) | Feb 11, 2022 |
| Acer          | TravelMate 8571             | [c8493474f0](https://linux-hardware.org/?probe=c8493474f0) | Feb 11, 2022 |
| Acer          | Swift SF314-43              | [fe2ff58a88](https://linux-hardware.org/?probe=fe2ff58a88) | Feb 10, 2022 |
| Acer          | Predator PH517-51           | [de32d3b86d](https://linux-hardware.org/?probe=de32d3b86d) | Feb 10, 2022 |
| Acer          | F                           | [a5dd4a459a](https://linux-hardware.org/?probe=a5dd4a459a) | Feb 10, 2022 |
| HP            | EliteBook 745 G3            | [21d3c81852](https://linux-hardware.org/?probe=21d3c81852) | Feb 10, 2022 |
| HP            | 620                         | [7648e2fd3d](https://linux-hardware.org/?probe=7648e2fd3d) | Feb 09, 2022 |
| Acer          | Nitro AN515-42              | [4906efe7f4](https://linux-hardware.org/?probe=4906efe7f4) | Feb 09, 2022 |
| Acer          | Nitro AN515-42              | [52d6fa9b66](https://linux-hardware.org/?probe=52d6fa9b66) | Feb 09, 2022 |
| Sony          | VPCEB4M1E                   | [373127eb11](https://linux-hardware.org/?probe=373127eb11) | Feb 09, 2022 |
| ASUSTek       | X550VX                      | [8fd69ee74c](https://linux-hardware.org/?probe=8fd69ee74c) | Feb 09, 2022 |
| Dell          | Latitude 5480               | [0d2e568733](https://linux-hardware.org/?probe=0d2e568733) | Feb 09, 2022 |
| Lenovo        | G50-30 80G0                 | [b05f08f7d5](https://linux-hardware.org/?probe=b05f08f7d5) | Feb 08, 2022 |
| ASUSTek       | X541UVK                     | [c4556ed732](https://linux-hardware.org/?probe=c4556ed732) | Feb 08, 2022 |
| Dell          | Inspiron 5558               | [72501fb765](https://linux-hardware.org/?probe=72501fb765) | Feb 08, 2022 |
| Dell          | Latitude E5520m             | [0e5f84866b](https://linux-hardware.org/?probe=0e5f84866b) | Feb 07, 2022 |
| Lenovo        | ThinkPad L440 20ASS3A300    | [136f9d4c89](https://linux-hardware.org/?probe=136f9d4c89) | Feb 07, 2022 |
| ASUSTek       | X541UVK                     | [f293b3a040](https://linux-hardware.org/?probe=f293b3a040) | Feb 07, 2022 |
| Dell          | Inspiron 15-3567            | [e897975636](https://linux-hardware.org/?probe=e897975636) | Feb 06, 2022 |
| Sony          | SVE1511A1EW                 | [74ce3aa5bf](https://linux-hardware.org/?probe=74ce3aa5bf) | Feb 06, 2022 |
| Dell          | Latitude D630               | [553512c6fa](https://linux-hardware.org/?probe=553512c6fa) | Feb 06, 2022 |
| Fujitsu       | LIFEBOOK E756               | [92c26ed8dc](https://linux-hardware.org/?probe=92c26ed8dc) | Feb 06, 2022 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [14cfb63e15](https://linux-hardware.org/?probe=14cfb63e15) | Feb 06, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [9a75091962](https://linux-hardware.org/?probe=9a75091962) | Feb 04, 2022 |
| HP            | 650                         | [63c7a9f5bc](https://linux-hardware.org/?probe=63c7a9f5bc) | Feb 03, 2022 |
| Dell          | Vostro 3558                 | [de621c4916](https://linux-hardware.org/?probe=de621c4916) | Feb 02, 2022 |
| Lenovo        | ThinkPad T430 2349KQ3       | [42fa6dc2c1](https://linux-hardware.org/?probe=42fa6dc2c1) | Feb 02, 2022 |
| Dell          | Inspiron 3521               | [6a7e1e173a](https://linux-hardware.org/?probe=6a7e1e173a) | Feb 01, 2022 |
| Sony          | SVS13118GBB                 | [44ef5a252e](https://linux-hardware.org/?probe=44ef5a252e) | Feb 01, 2022 |
| HP            | Unknown                     | [6aa3eb854c](https://linux-hardware.org/?probe=6aa3eb854c) | Jan 31, 2022 |
| ASUSTek       | X541UVK                     | [e923d26564](https://linux-hardware.org/?probe=e923d26564) | Jan 30, 2022 |
| ASUSTek       | X541UVK                     | [01a2239429](https://linux-hardware.org/?probe=01a2239429) | Jan 30, 2022 |
| ASUSTek       | X541UVK                     | [d231ae37d8](https://linux-hardware.org/?probe=d231ae37d8) | Jan 29, 2022 |
| Dell          | System Vostro 3750          | [de27492af3](https://linux-hardware.org/?probe=de27492af3) | Jan 29, 2022 |
| Dell          | Latitude E6530              | [b47cc45b54](https://linux-hardware.org/?probe=b47cc45b54) | Jan 29, 2022 |
| Sony          | SVS13118GBB                 | [1e7063ddb5](https://linux-hardware.org/?probe=1e7063ddb5) | Jan 28, 2022 |
| HP            | 250 G6 Notebook PC          | [1168d4d65b](https://linux-hardware.org/?probe=1168d4d65b) | Jan 28, 2022 |
| HP            | 250 G6 Notebook PC          | [975facb986](https://linux-hardware.org/?probe=975facb986) | Jan 28, 2022 |
| Lenovo        | ThinkPad T61 6458Y56        | [4cef262fd4](https://linux-hardware.org/?probe=4cef262fd4) | Jan 28, 2022 |
| Acer          | Aspire A315-58G             | [cb4f253c1c](https://linux-hardware.org/?probe=cb4f253c1c) | Jan 28, 2022 |
| Dell          | G3 3579                     | [c869de19b3](https://linux-hardware.org/?probe=c869de19b3) | Jan 27, 2022 |
| Apple         | MacBookPro6,2               | [a2475cad56](https://linux-hardware.org/?probe=a2475cad56) | Jan 27, 2022 |
| HP            | ProBook 6470b               | [81afdce4bb](https://linux-hardware.org/?probe=81afdce4bb) | Jan 27, 2022 |
| Acer          | Aspire F5-573G              | [83dcbe0d18](https://linux-hardware.org/?probe=83dcbe0d18) | Jan 27, 2022 |
| ASUSTek       | X550VX                      | [a92b98a4cf](https://linux-hardware.org/?probe=a92b98a4cf) | Jan 26, 2022 |
| Insyde        | Braswell                    | [0d8764b0d5](https://linux-hardware.org/?probe=0d8764b0d5) | Jan 26, 2022 |
| HP            | EliteBook 850 G5            | [a780b76d00](https://linux-hardware.org/?probe=a780b76d00) | Jan 25, 2022 |
| HP            | EliteBook 850 G5            | [47a78966be](https://linux-hardware.org/?probe=47a78966be) | Jan 25, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [242f7d0fec](https://linux-hardware.org/?probe=242f7d0fec) | Jan 25, 2022 |
| Insyde        | Braswell                    | [c082266f28](https://linux-hardware.org/?probe=c082266f28) | Jan 25, 2022 |
| Acer          | Aspire F5-573G              | [51f8947e68](https://linux-hardware.org/?probe=51f8947e68) | Jan 25, 2022 |
| HP            | ProBook 6470b               | [820d0a16ea](https://linux-hardware.org/?probe=820d0a16ea) | Jan 24, 2022 |
| ASUSTek       | GL553VW                     | [7713319e74](https://linux-hardware.org/?probe=7713319e74) | Jan 24, 2022 |
| Lenovo        | G550 20023                  | [9432cdb859](https://linux-hardware.org/?probe=9432cdb859) | Jan 24, 2022 |
| HP            | ProBook 650 G3              | [32fcb78172](https://linux-hardware.org/?probe=32fcb78172) | Jan 23, 2022 |
| Dell          | Inspiron M5030              | [0918a672e0](https://linux-hardware.org/?probe=0918a672e0) | Jan 22, 2022 |
| Lenovo        | ThinkPad L420 78544UG       | [26c13c7d16](https://linux-hardware.org/?probe=26c13c7d16) | Jan 22, 2022 |
| Lenovo        | ThinkPad L420 78544UG       | [dc6c0d3559](https://linux-hardware.org/?probe=dc6c0d3559) | Jan 22, 2022 |
| ASUSTek       | K50IN                       | [64a1640588](https://linux-hardware.org/?probe=64a1640588) | Jan 21, 2022 |
| ASUSTek       | K50IN                       | [43c8a1b1ec](https://linux-hardware.org/?probe=43c8a1b1ec) | Jan 21, 2022 |
| Dell          | Inspiron 5558               | [fc8a233818](https://linux-hardware.org/?probe=fc8a233818) | Jan 21, 2022 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [df25e2a6d4](https://linux-hardware.org/?probe=df25e2a6d4) | Jan 21, 2022 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [7439a5647b](https://linux-hardware.org/?probe=7439a5647b) | Jan 21, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [cdda13eba7](https://linux-hardware.org/?probe=cdda13eba7) | Jan 20, 2022 |
| Lenovo        | ThinkPad T400 2768WGB       | [88150d957e](https://linux-hardware.org/?probe=88150d957e) | Jan 20, 2022 |
| Acer          | Swift SF314-42              | [af81e6fd78](https://linux-hardware.org/?probe=af81e6fd78) | Jan 20, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | [4d77516c19](https://linux-hardware.org/?probe=4d77516c19) | Jan 19, 2022 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [1d9c3b162d](https://linux-hardware.org/?probe=1d9c3b162d) | Jan 18, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [87bd7d315f](https://linux-hardware.org/?probe=87bd7d315f) | Jan 18, 2022 |
| Lenovo        | ThinkPad L470 20J5S2RA00    | [81d06b1028](https://linux-hardware.org/?probe=81d06b1028) | Jan 18, 2022 |
| HP            | EliteBook 8440p             | [eea8c3a5c3](https://linux-hardware.org/?probe=eea8c3a5c3) | Jan 18, 2022 |
| Lenovo        | G40-45 80E1                 | [4bdc747bd4](https://linux-hardware.org/?probe=4bdc747bd4) | Jan 18, 2022 |
| HP            | EliteBook 8440p             | [a3133c9aab](https://linux-hardware.org/?probe=a3133c9aab) | Jan 17, 2022 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | [42a841fb5b](https://linux-hardware.org/?probe=42a841fb5b) | Jan 17, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [10983d5883](https://linux-hardware.org/?probe=10983d5883) | Jan 17, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [0bd3f0c6c1](https://linux-hardware.org/?probe=0bd3f0c6c1) | Jan 17, 2022 |
| HP            | EliteBook 745 G3            | [7e44b8f1f8](https://linux-hardware.org/?probe=7e44b8f1f8) | Jan 16, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [7b614a5d11](https://linux-hardware.org/?probe=7b614a5d11) | Jan 15, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [30c367f8ca](https://linux-hardware.org/?probe=30c367f8ca) | Jan 15, 2022 |
| Packard Be... | EasyNote TK37               | [4b9de8a4a2](https://linux-hardware.org/?probe=4b9de8a4a2) | Jan 15, 2022 |
| Acer          | Aspire A315-51              | [841d415fa4](https://linux-hardware.org/?probe=841d415fa4) | Jan 15, 2022 |
| Lenovo        | ThinkPad T400 2768WGB       | [0d267e1823](https://linux-hardware.org/?probe=0d267e1823) | Jan 15, 2022 |
| ASUSTek       | X542UN                      | [f27ec23965](https://linux-hardware.org/?probe=f27ec23965) | Jan 15, 2022 |
| Packard Be... | EasyNote TK37               | [b511ea2a93](https://linux-hardware.org/?probe=b511ea2a93) | Jan 14, 2022 |
| Packard Be... | EasyNote TK37               | [28b9c9ef8e](https://linux-hardware.org/?probe=28b9c9ef8e) | Jan 14, 2022 |
| HP            | 255 G5 Notebook PC          | [6f20015e15](https://linux-hardware.org/?probe=6f20015e15) | Jan 13, 2022 |
| Lenovo        | ThinkPad T440 20B7S00H01    | [1bdc5dc298](https://linux-hardware.org/?probe=1bdc5dc298) | Jan 11, 2022 |
| MSI           | GF63 Thin 9SC               | [0914f76b4d](https://linux-hardware.org/?probe=0914f76b4d) | Jan 11, 2022 |
| Lenovo        | ThinkPad T500 2056CL8       | [ef244e06d3](https://linux-hardware.org/?probe=ef244e06d3) | Jan 10, 2022 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | [81f7bfbced](https://linux-hardware.org/?probe=81f7bfbced) | Jan 10, 2022 |
| ASUSTek       | K53U                        | [d39f634e72](https://linux-hardware.org/?probe=d39f634e72) | Jan 10, 2022 |
| ASUSTek       | K53U                        | [a174ee5aa1](https://linux-hardware.org/?probe=a174ee5aa1) | Jan 10, 2022 |
| Lenovo        | ThinkPad T420 42361P0       | [01499828ce](https://linux-hardware.org/?probe=01499828ce) | Jan 09, 2022 |
| Dell          | Latitude E6430              | [e25ec7e140](https://linux-hardware.org/?probe=e25ec7e140) | Jan 09, 2022 |
| Acer          | Aspire ES1-532G             | [7cecf04619](https://linux-hardware.org/?probe=7cecf04619) | Jan 09, 2022 |
| Acer          | Aspire ES1-532G             | [d2dfc8da4c](https://linux-hardware.org/?probe=d2dfc8da4c) | Jan 09, 2022 |
| Acer          | Aspire E1-571               | [c4d40f6344](https://linux-hardware.org/?probe=c4d40f6344) | Jan 08, 2022 |
| HP            | EliteBook 745 G3            | [5300368575](https://linux-hardware.org/?probe=5300368575) | Jan 08, 2022 |
| Acer          | Aspire F5-573G              | [719238f99c](https://linux-hardware.org/?probe=719238f99c) | Jan 08, 2022 |
| Acer          | Aspire F5-573G              | [3d833877a7](https://linux-hardware.org/?probe=3d833877a7) | Jan 08, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [8e4bf2cdb1](https://linux-hardware.org/?probe=8e4bf2cdb1) | Jan 08, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [e6501cd7df](https://linux-hardware.org/?probe=e6501cd7df) | Jan 08, 2022 |
| Lenovo        | ThinkPad T400 2768WGB       | [ac0e3dfe29](https://linux-hardware.org/?probe=ac0e3dfe29) | Jan 07, 2022 |
| Dell          | Latitude 5480               | [8a88e72831](https://linux-hardware.org/?probe=8a88e72831) | Jan 05, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [c1f08a0773](https://linux-hardware.org/?probe=c1f08a0773) | Jan 04, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [c52ca0986f](https://linux-hardware.org/?probe=c52ca0986f) | Jan 04, 2022 |
| ASUSTek       | X541UAK                     | [bd5145c8b1](https://linux-hardware.org/?probe=bd5145c8b1) | Jan 03, 2022 |
| ASUSTek       | GL552JX                     | [248ec86597](https://linux-hardware.org/?probe=248ec86597) | Jan 03, 2022 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [1c550c0bba](https://linux-hardware.org/?probe=1c550c0bba) | Jan 02, 2022 |
| Dell          | Inspiron 1525               | [11ecdbec1b](https://linux-hardware.org/?probe=11ecdbec1b) | Jan 02, 2022 |
| Dell          | Inspiron 1525               | [c1c0a04b87](https://linux-hardware.org/?probe=c1c0a04b87) | Jan 02, 2022 |
| HP            | EliteBook 820 G1            | [a474addf38](https://linux-hardware.org/?probe=a474addf38) | Jan 01, 2022 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | [a76fb98d8d](https://linux-hardware.org/?probe=a76fb98d8d) | Jan 01, 2022 |
| Dell          | Vostro 3500                 | [5ec7cee601](https://linux-hardware.org/?probe=5ec7cee601) | Jan 01, 2022 |
| Lenovo        | ThinkPad W510 431924G       | [c0ef5f6b84](https://linux-hardware.org/?probe=c0ef5f6b84) | Dec 29, 2021 |
| Lenovo        | B590 20208                  | [84ca821541](https://linux-hardware.org/?probe=84ca821541) | Dec 29, 2021 |
| ASUSTek       | GL503VD                     | [8918ebec98](https://linux-hardware.org/?probe=8918ebec98) | Dec 28, 2021 |
| ASUSTek       | GL503VD                     | [3ef04a0fe1](https://linux-hardware.org/?probe=3ef04a0fe1) | Dec 27, 2021 |
| HP            | 15                          | [76fef17b30](https://linux-hardware.org/?probe=76fef17b30) | Dec 27, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [988628f6b6](https://linux-hardware.org/?probe=988628f6b6) | Dec 25, 2021 |
| HP            | 650                         | [339ab3e2d2](https://linux-hardware.org/?probe=339ab3e2d2) | Dec 25, 2021 |
| Dell          | Latitude E6510              | [1fa89129c0](https://linux-hardware.org/?probe=1fa89129c0) | Dec 24, 2021 |
| Dell          | Latitude E6410              | [0588df88b2](https://linux-hardware.org/?probe=0588df88b2) | Dec 24, 2021 |
| Dell          | Latitude E6410              | [c30a066afc](https://linux-hardware.org/?probe=c30a066afc) | Dec 24, 2021 |
| Dell          | Inspiron 5502               | [020519cdfe](https://linux-hardware.org/?probe=020519cdfe) | Dec 24, 2021 |
| Acer          | Extensa 215-51K             | [eb7ebb463b](https://linux-hardware.org/?probe=eb7ebb463b) | Dec 23, 2021 |
| Mediacom      | GTZS                        | [d462097cdd](https://linux-hardware.org/?probe=d462097cdd) | Dec 23, 2021 |
| Dell          | Precision M6600             | [6be07fde65](https://linux-hardware.org/?probe=6be07fde65) | Dec 23, 2021 |
| Dell          | Precision M6600             | [a4f1415897](https://linux-hardware.org/?probe=a4f1415897) | Dec 23, 2021 |
| Medion        | E7218                       | [8d6ee5cd3e](https://linux-hardware.org/?probe=8d6ee5cd3e) | Dec 23, 2021 |
| ASUSTek       | Strix 17 GL703GE            | [f34a512b46](https://linux-hardware.org/?probe=f34a512b46) | Dec 22, 2021 |
| Medion        | E7218                       | [6b930af32f](https://linux-hardware.org/?probe=6b930af32f) | Dec 22, 2021 |
| ASUSTek       | K53BY                       | [c699d6fcd9](https://linux-hardware.org/?probe=c699d6fcd9) | Dec 22, 2021 |
| HP            | EliteBook 8570w             | [3d19abb9a8](https://linux-hardware.org/?probe=3d19abb9a8) | Dec 22, 2021 |
| Acer          | Aspire 3050                 | [888f7795aa](https://linux-hardware.org/?probe=888f7795aa) | Dec 22, 2021 |
| Acer          | Aspire 3050                 | [cfec9fece6](https://linux-hardware.org/?probe=cfec9fece6) | Dec 21, 2021 |
| Mediacom      | GTZS                        | [3694d520f6](https://linux-hardware.org/?probe=3694d520f6) | Dec 20, 2021 |
| Acer          | TP-W701P-53334G1            | [674f2996b5](https://linux-hardware.org/?probe=674f2996b5) | Dec 19, 2021 |
| Acer          | Aspire ES1-532G             | [cf832b7bf6](https://linux-hardware.org/?probe=cf832b7bf6) | Dec 19, 2021 |
| Acer          | Aspire ES1-532G             | [23d3dd911d](https://linux-hardware.org/?probe=23d3dd911d) | Dec 19, 2021 |
| Packard Be... | EasyNote TE11BZ             | [24fef50189](https://linux-hardware.org/?probe=24fef50189) | Dec 19, 2021 |
| Dell          | Latitude E6430              | [5b026ea45f](https://linux-hardware.org/?probe=5b026ea45f) | Dec 19, 2021 |
| Dell          | Latitude E6430              | [ae951db282](https://linux-hardware.org/?probe=ae951db282) | Dec 18, 2021 |
| ASUSTek       | X550VX                      | [db3cd6403d](https://linux-hardware.org/?probe=db3cd6403d) | Dec 16, 2021 |
| Dell          | Precision M2800             | [0a3b99488f](https://linux-hardware.org/?probe=0a3b99488f) | Dec 11, 2021 |
| Lenovo        | ThinkPad W530 24475HG       | [00379f5e66](https://linux-hardware.org/?probe=00379f5e66) | Dec 10, 2021 |
| ASUSTek       | VivoBook S13 X330FA_S330... | [9a01f01187](https://linux-hardware.org/?probe=9a01f01187) | Dec 09, 2021 |
| Dell          | Latitude E6420              | [51073dcf26](https://linux-hardware.org/?probe=51073dcf26) | Dec 05, 2021 |
| Dell          | Latitude E6420              | [6826928218](https://linux-hardware.org/?probe=6826928218) | Dec 05, 2021 |
| MSI           | CX600                       | [38b84f0feb](https://linux-hardware.org/?probe=38b84f0feb) | Dec 05, 2021 |
| Acer          | Swift SF114-32              | [06324a46eb](https://linux-hardware.org/?probe=06324a46eb) | Dec 05, 2021 |
| Dell          | Latitude 5480               | [412919400e](https://linux-hardware.org/?probe=412919400e) | Dec 05, 2021 |
| Dell          | Inspiron 15-3567            | [26a01c28fa](https://linux-hardware.org/?probe=26a01c28fa) | Dec 05, 2021 |
| Dell          | Inspiron 15-3567            | [bb8b782ef0](https://linux-hardware.org/?probe=bb8b782ef0) | Dec 05, 2021 |
| Lenovo        | G500 20236                  | [dab30215a2](https://linux-hardware.org/?probe=dab30215a2) | Dec 05, 2021 |
| Dell          | Latitude 5410               | [af7b378137](https://linux-hardware.org/?probe=af7b378137) | Dec 05, 2021 |
| Dell          | Latitude 5410               | [0d992a9be7](https://linux-hardware.org/?probe=0d992a9be7) | Dec 05, 2021 |
| Dell          | Latitude D630               | [718e2268fa](https://linux-hardware.org/?probe=718e2268fa) | Dec 04, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [496443510d](https://linux-hardware.org/?probe=496443510d) | Dec 04, 2021 |
| Lenovo        | ThinkPad T61 6458WK6        | [e24ba2f637](https://linux-hardware.org/?probe=e24ba2f637) | Dec 03, 2021 |
| Acer          | Aspire A315-58G             | [48e3c0e6c7](https://linux-hardware.org/?probe=48e3c0e6c7) | Dec 03, 2021 |
| Dell          | Latitude 5480               | [d1a9d603a9](https://linux-hardware.org/?probe=d1a9d603a9) | Nov 30, 2021 |
| Acer          | Swift SF314-43              | [01ce77a927](https://linux-hardware.org/?probe=01ce77a927) | Nov 30, 2021 |
| Apple         | MacBookPro5,5               | [c32c22a4b9](https://linux-hardware.org/?probe=c32c22a4b9) | Nov 30, 2021 |
| Apple         | MacBookPro5,5               | [01a1e9ffb0](https://linux-hardware.org/?probe=01a1e9ffb0) | Nov 30, 2021 |
| Acer          | Aspire 5930                 | [17eed17c54](https://linux-hardware.org/?probe=17eed17c54) | Nov 29, 2021 |
| Acer          | Aspire 5930                 | [9a4712d7ad](https://linux-hardware.org/?probe=9a4712d7ad) | Nov 29, 2021 |
| Dell          | Latitude E6430              | [39087042b7](https://linux-hardware.org/?probe=39087042b7) | Nov 28, 2021 |
| Dell          | Latitude 5480               | [70e231854b](https://linux-hardware.org/?probe=70e231854b) | Nov 28, 2021 |
| HP            | ZBook Studio G4             | [eb3da87330](https://linux-hardware.org/?probe=eb3da87330) | Nov 27, 2021 |
| HP            | EliteBook 8540p             | [38dd850a7c](https://linux-hardware.org/?probe=38dd850a7c) | Nov 26, 2021 |
| HP            | EliteBook 8540p             | [e6df5b59a8](https://linux-hardware.org/?probe=e6df5b59a8) | Nov 26, 2021 |
| BenQ          | Joybook A52                 | [f11e0f093f](https://linux-hardware.org/?probe=f11e0f093f) | Nov 26, 2021 |
| Lenovo        | G40-45 80E1                 | [0460c1b728](https://linux-hardware.org/?probe=0460c1b728) | Nov 25, 2021 |
| Dell          | Latitude 5480               | [c2079e6c03](https://linux-hardware.org/?probe=c2079e6c03) | Nov 23, 2021 |
| HP            | ProBook 4330s               | [74e6151748](https://linux-hardware.org/?probe=74e6151748) | Nov 23, 2021 |
| Dell          | Latitude E6230              | [5df4406c5b](https://linux-hardware.org/?probe=5df4406c5b) | Nov 23, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [b8d8d8e85e](https://linux-hardware.org/?probe=b8d8d8e85e) | Nov 23, 2021 |
| Fujitsu       | STYLISTIC Q702              | [b874076152](https://linux-hardware.org/?probe=b874076152) | Nov 22, 2021 |
| Dell          | Latitude E6410              | [20e60e8531](https://linux-hardware.org/?probe=20e60e8531) | Nov 22, 2021 |
| Dell          | Latitude E6410              | [96a9008d41](https://linux-hardware.org/?probe=96a9008d41) | Nov 22, 2021 |
| Toshiba       | NB550D                      | [ff322fa9a1](https://linux-hardware.org/?probe=ff322fa9a1) | Nov 21, 2021 |
| Apple         | MacBookPro6,2               | [33f1433007](https://linux-hardware.org/?probe=33f1433007) | Nov 21, 2021 |
| Lenovo        | G550 20023                  | [531304bd76](https://linux-hardware.org/?probe=531304bd76) | Nov 20, 2021 |
| MSI           | CR610                       | [63411cafc4](https://linux-hardware.org/?probe=63411cafc4) | Nov 20, 2021 |
| MSI           | CR610                       | [6f2f218e21](https://linux-hardware.org/?probe=6f2f218e21) | Nov 20, 2021 |
| HP            | EliteBook 840 G3            | [1a5ca1d992](https://linux-hardware.org/?probe=1a5ca1d992) | Nov 20, 2021 |
| Dell          | Vostro 3300                 | [04fc886be3](https://linux-hardware.org/?probe=04fc886be3) | Nov 20, 2021 |
| Lenovo        | G550 20023                  | [ce28fd38d4](https://linux-hardware.org/?probe=ce28fd38d4) | Nov 20, 2021 |
| Lenovo        | ThinkPad T530 2429NL6       | [44649d8cb3](https://linux-hardware.org/?probe=44649d8cb3) | Nov 19, 2021 |
| Lenovo        | ThinkPad T530 2429NL6       | [40e07deebb](https://linux-hardware.org/?probe=40e07deebb) | Nov 19, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [2f5c8e09bf](https://linux-hardware.org/?probe=2f5c8e09bf) | Nov 19, 2021 |
| Dell          | Latitude E6410              | [17e575c418](https://linux-hardware.org/?probe=17e575c418) | Nov 19, 2021 |
| Acer          | Aspire A315-58G             | [911895fcf2](https://linux-hardware.org/?probe=911895fcf2) | Nov 19, 2021 |
| Dell          | Latitude E7470              | [9fb42a7a17](https://linux-hardware.org/?probe=9fb42a7a17) | Nov 19, 2021 |
| Apple         | MacBookPro6,2               | [0dd964d22b](https://linux-hardware.org/?probe=0dd964d22b) | Nov 18, 2021 |
| Lenovo        | ThinkPad A475 20KMS0EJ00    | [e029652647](https://linux-hardware.org/?probe=e029652647) | Nov 18, 2021 |
| Lenovo        | ThinkBook 15p 20V3          | [855308b39c](https://linux-hardware.org/?probe=855308b39c) | Nov 18, 2021 |
| Fujitsu       | LIFEBOOK U745               | [647cd257ec](https://linux-hardware.org/?probe=647cd257ec) | Nov 18, 2021 |
| Apple         | MacBookPro5,5               | [e56e34b28a](https://linux-hardware.org/?probe=e56e34b28a) | Nov 18, 2021 |
| Apple         | MacBookPro5,5               | [35206eb5d3](https://linux-hardware.org/?probe=35206eb5d3) | Nov 18, 2021 |
| Dell          | Inspiron 5558               | [e86c8890fa](https://linux-hardware.org/?probe=e86c8890fa) | Nov 18, 2021 |
| Lenovo        | ThinkPad A475 20KMS0EJ00    | [26a144a0c7](https://linux-hardware.org/?probe=26a144a0c7) | Nov 17, 2021 |
| Lenovo        | Z50-75 80EC                 | [cbca714862](https://linux-hardware.org/?probe=cbca714862) | Nov 17, 2021 |
| Dell          | Latitude E5430 non-vPro     | [d4cf8a16f2](https://linux-hardware.org/?probe=d4cf8a16f2) | Nov 16, 2021 |
| Dell          | Latitude E5430 non-vPro     | [8d694f749f](https://linux-hardware.org/?probe=8d694f749f) | Nov 16, 2021 |
| Toshiba       | Satellite L750              | [f6ddfdb8ce](https://linux-hardware.org/?probe=f6ddfdb8ce) | Nov 16, 2021 |
| Toshiba       | Satellite L750              | [cc7c9dddca](https://linux-hardware.org/?probe=cc7c9dddca) | Nov 16, 2021 |
| ASUSTek       | S551LN                      | [53b3fced16](https://linux-hardware.org/?probe=53b3fced16) | Nov 16, 2021 |
| Lenovo        | B50-70 20384                | [da69364d7a](https://linux-hardware.org/?probe=da69364d7a) | Nov 16, 2021 |
| Lenovo        | B50-70 20384                | [ec91da9f30](https://linux-hardware.org/?probe=ec91da9f30) | Nov 16, 2021 |
| ASUSTek       | GL753VD                     | [8109914a61](https://linux-hardware.org/?probe=8109914a61) | Nov 16, 2021 |
| Lenovo        | G550 20023                  | [520ebfcf8a](https://linux-hardware.org/?probe=520ebfcf8a) | Nov 16, 2021 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [a2947ff518](https://linux-hardware.org/?probe=a2947ff518) | Nov 15, 2021 |
| MSI           | VR610                       | [9dd3927cf1](https://linux-hardware.org/?probe=9dd3927cf1) | Nov 15, 2021 |
| MSI           | VR610                       | [fa0f1da6d7](https://linux-hardware.org/?probe=fa0f1da6d7) | Nov 15, 2021 |
| Lenovo        | Y720-15IKB 80VR             | [56b6de179d](https://linux-hardware.org/?probe=56b6de179d) | Nov 14, 2021 |
| HP            | ProBook 4330s               | [4682329a97](https://linux-hardware.org/?probe=4682329a97) | Nov 14, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [1db693cc35](https://linux-hardware.org/?probe=1db693cc35) | Nov 14, 2021 |
| HP            | EliteBook 840 G5            | [6bde73e59b](https://linux-hardware.org/?probe=6bde73e59b) | Nov 13, 2021 |
| Acer          | Aspire A315-55KG            | [eddf767a4f](https://linux-hardware.org/?probe=eddf767a4f) | Nov 13, 2021 |
| Lenovo        | ThinkPad X200s 74695QG      | [1ff4f8e0fc](https://linux-hardware.org/?probe=1ff4f8e0fc) | Nov 13, 2021 |
| Samsung       | NC210/NC110                 | [126116dbac](https://linux-hardware.org/?probe=126116dbac) | Nov 12, 2021 |
| Acer          | Aspire A315-58G             | [5748b3cd05](https://linux-hardware.org/?probe=5748b3cd05) | Nov 12, 2021 |
| Lenovo        | ThinkPad T400 2768WGB       | [9d3272960f](https://linux-hardware.org/?probe=9d3272960f) | Nov 12, 2021 |
| Lenovo        | Z50-75 80EC                 | [f49b4f30dc](https://linux-hardware.org/?probe=f49b4f30dc) | Nov 11, 2021 |
| Dell          | Latitude D630               | [bd546ec46b](https://linux-hardware.org/?probe=bd546ec46b) | Nov 11, 2021 |
| Dell          | Inspiron 5567               | [049c9e4f07](https://linux-hardware.org/?probe=049c9e4f07) | Nov 10, 2021 |
| Dell          | Latitude 7280               | [c59152a648](https://linux-hardware.org/?probe=c59152a648) | Nov 10, 2021 |
| HUAWEI        | KPL-W0X                     | [807e59f1e3](https://linux-hardware.org/?probe=807e59f1e3) | Nov 10, 2021 |
| Dell          | Inspiron 3576               | [ad9fb758a6](https://linux-hardware.org/?probe=ad9fb758a6) | Nov 09, 2021 |
| eMachines     | eME732G                     | [1e7c39c762](https://linux-hardware.org/?probe=1e7c39c762) | Nov 09, 2021 |
| Acer          | Aspire A315-55KG            | [14826ce238](https://linux-hardware.org/?probe=14826ce238) | Nov 09, 2021 |
| eMachines     | eME732G                     | [b0c186d2e4](https://linux-hardware.org/?probe=b0c186d2e4) | Nov 09, 2021 |
| HP            | Pavilion Notebook           | [6ed0c89edd](https://linux-hardware.org/?probe=6ed0c89edd) | Nov 08, 2021 |
| Lenovo        | ThinkPad T460s 20F9CTO1W... | [b996ce8823](https://linux-hardware.org/?probe=b996ce8823) | Nov 07, 2021 |
| Lenovo        | ThinkPad W700 27523KG       | [73b193e1ca](https://linux-hardware.org/?probe=73b193e1ca) | Nov 07, 2021 |
| Lenovo        | ThinkPad W700 27523KG       | [4e6a02ec16](https://linux-hardware.org/?probe=4e6a02ec16) | Nov 07, 2021 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | [3ad8721d2a](https://linux-hardware.org/?probe=3ad8721d2a) | Nov 07, 2021 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | [0807858e11](https://linux-hardware.org/?probe=0807858e11) | Nov 07, 2021 |
| Dell          | Vostro 1540                 | [1372b6afee](https://linux-hardware.org/?probe=1372b6afee) | Nov 07, 2021 |
| Fujitsu Si... | LIFEBOOK S7110              | [6787f46858](https://linux-hardware.org/?probe=6787f46858) | Nov 06, 2021 |
| HP            | 250 G4                      | [8167957b46](https://linux-hardware.org/?probe=8167957b46) | Nov 06, 2021 |
| Sony          | SVS13118GBB                 | [741a2c8c9e](https://linux-hardware.org/?probe=741a2c8c9e) | Nov 06, 2021 |
| Dell          | Latitude E6430s             | [d7646260f0](https://linux-hardware.org/?probe=d7646260f0) | Nov 06, 2021 |
| Acer          | Aspire A315-58G             | [64f0bb3f2b](https://linux-hardware.org/?probe=64f0bb3f2b) | Nov 06, 2021 |
| eMachines     | E525                        | [05c829a085](https://linux-hardware.org/?probe=05c829a085) | Nov 06, 2021 |
| ASUSTek       | K53U                        | [6c7d579e49](https://linux-hardware.org/?probe=6c7d579e49) | Nov 05, 2021 |
| ASUSTek       | K50IN                       | [8c356405f0](https://linux-hardware.org/?probe=8c356405f0) | Nov 05, 2021 |
| Lenovo        | G505s 20255                 | [c9fb91eefc](https://linux-hardware.org/?probe=c9fb91eefc) | Nov 04, 2021 |
| ASUSTek       | K53U                        | [15adf4f30a](https://linux-hardware.org/?probe=15adf4f30a) | Nov 03, 2021 |
| Acer          | Swift SF314-42              | [07025c7436](https://linux-hardware.org/?probe=07025c7436) | Nov 02, 2021 |
| ASUSTek       | K50IN                       | [570da581ab](https://linux-hardware.org/?probe=570da581ab) | Nov 02, 2021 |
| HP            | ZBook Firefly 14 G7 Mobi... | [911f44bae3](https://linux-hardware.org/?probe=911f44bae3) | Nov 02, 2021 |
| Dell          | Vostro 1540                 | [0e6d351a5f](https://linux-hardware.org/?probe=0e6d351a5f) | Nov 01, 2021 |
| Fujitsu Si... | LIFEBOOK S7110              | [e5a8a22561](https://linux-hardware.org/?probe=e5a8a22561) | Nov 01, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [f55ff834af](https://linux-hardware.org/?probe=f55ff834af) | Nov 01, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [56fe9a754b](https://linux-hardware.org/?probe=56fe9a754b) | Nov 01, 2021 |
| Dell          | Latitude E6530              | [40d78b6ddd](https://linux-hardware.org/?probe=40d78b6ddd) | Nov 01, 2021 |
| Acer          | TravelMate 8571             | [57ed306b65](https://linux-hardware.org/?probe=57ed306b65) | Oct 31, 2021 |
| Dell          | Vostro 1700                 | [a9ba9df656](https://linux-hardware.org/?probe=a9ba9df656) | Oct 30, 2021 |
| Fujitsu Si... | AMILO Pro Edition V3505     | [1517ac0d45](https://linux-hardware.org/?probe=1517ac0d45) | Oct 30, 2021 |
| Acer          | Aspire A315-58G             | [905fce5118](https://linux-hardware.org/?probe=905fce5118) | Oct 29, 2021 |
| HP            | Pavilion 15                 | [1014243935](https://linux-hardware.org/?probe=1014243935) | Oct 29, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [dad06f3e70](https://linux-hardware.org/?probe=dad06f3e70) | Oct 29, 2021 |
| Lenovo        | G570 20079                  | [b2f7ab7e8a](https://linux-hardware.org/?probe=b2f7ab7e8a) | Oct 28, 2021 |
| Lenovo        | G570 20079                  | [b16cb4d0dc](https://linux-hardware.org/?probe=b16cb4d0dc) | Oct 28, 2021 |
| ASUSTek       | GL753VD                     | [8a5f05e4c1](https://linux-hardware.org/?probe=8a5f05e4c1) | Oct 28, 2021 |
| HP            | EliteBook 6930p             | [77895f2a3b](https://linux-hardware.org/?probe=77895f2a3b) | Oct 28, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [20f75f2d4c](https://linux-hardware.org/?probe=20f75f2d4c) | Oct 28, 2021 |
| HP            | ProBook 6475b               | [c4c890f06a](https://linux-hardware.org/?probe=c4c890f06a) | Oct 27, 2021 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | [55689e67b3](https://linux-hardware.org/?probe=55689e67b3) | Oct 27, 2021 |
| HP            | ProBook 6470b               | [1b2fbcdfa0](https://linux-hardware.org/?probe=1b2fbcdfa0) | Oct 26, 2021 |
| HP            | OMEN by Laptop 17-an0xx     | [57cd00ef8b](https://linux-hardware.org/?probe=57cd00ef8b) | Oct 25, 2021 |
| HP            | OMEN by Laptop 17-an0xx     | [e6f20aae28](https://linux-hardware.org/?probe=e6f20aae28) | Oct 24, 2021 |
| HP            | 650                         | [22e5d1948a](https://linux-hardware.org/?probe=22e5d1948a) | Oct 24, 2021 |
| HP            | ProBook 6470b               | [bef890f3d9](https://linux-hardware.org/?probe=bef890f3d9) | Oct 23, 2021 |
| Acer          | Swift SF114-32              | [87697aa300](https://linux-hardware.org/?probe=87697aa300) | Oct 23, 2021 |
| Acer          | Aspire V3-372               | [b185a2037d](https://linux-hardware.org/?probe=b185a2037d) | Oct 22, 2021 |
| HP            | 255 G5 Notebook PC          | [421c375338](https://linux-hardware.org/?probe=421c375338) | Oct 22, 2021 |
| Acer          | Aspire A315-53G             | [ebb8572b41](https://linux-hardware.org/?probe=ebb8572b41) | Oct 22, 2021 |
| Acer          | Swift SF314-43              | [8275d5fa0b](https://linux-hardware.org/?probe=8275d5fa0b) | Oct 22, 2021 |
| Lenovo        | G550 20023                  | [3bfb2e5e7b](https://linux-hardware.org/?probe=3bfb2e5e7b) | Oct 22, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [985d10d314](https://linux-hardware.org/?probe=985d10d314) | Oct 21, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [35a40c6757](https://linux-hardware.org/?probe=35a40c6757) | Oct 21, 2021 |
| Fujitsu Si... | AMILO Li1705                | [a61c777014](https://linux-hardware.org/?probe=a61c777014) | Oct 21, 2021 |
| Fujitsu Si... | AMILO Li1705                | [3a627aab0a](https://linux-hardware.org/?probe=3a627aab0a) | Oct 21, 2021 |
| Acer          | Aspire A315-53G             | [9231eabdb2](https://linux-hardware.org/?probe=9231eabdb2) | Oct 21, 2021 |
| HP            | 250 G1                      | [b0ed67249e](https://linux-hardware.org/?probe=b0ed67249e) | Oct 21, 2021 |
| HP            | 250 G1                      | [0790e099fa](https://linux-hardware.org/?probe=0790e099fa) | Oct 21, 2021 |
| speedmaste... | E131x series                | [44a79e6330](https://linux-hardware.org/?probe=44a79e6330) | Oct 21, 2021 |
| speedmaste... | E131x series                | [e539db1fcd](https://linux-hardware.org/?probe=e539db1fcd) | Oct 20, 2021 |
| Acer          | Nitro AN515-42              | [2ff605bdb0](https://linux-hardware.org/?probe=2ff605bdb0) | Oct 20, 2021 |
| ASUSTek       | N551JW                      | [a6c41c9d3e](https://linux-hardware.org/?probe=a6c41c9d3e) | Oct 19, 2021 |
| HP            | ZBook Studio G4             | [0fe0f1450c](https://linux-hardware.org/?probe=0fe0f1450c) | Oct 19, 2021 |
| Fujitsu       | LIFEBOOK A530               | [1c293cc8f0](https://linux-hardware.org/?probe=1c293cc8f0) | Oct 18, 2021 |
| HP            | 650                         | [f27e07a82b](https://linux-hardware.org/?probe=f27e07a82b) | Oct 17, 2021 |
| HP            | ZBook Studio G4             | [d79ba35f27](https://linux-hardware.org/?probe=d79ba35f27) | Oct 17, 2021 |
| Lenovo        | Z710 20250                  | [d2a9cd32b1](https://linux-hardware.org/?probe=d2a9cd32b1) | Oct 17, 2021 |
| Acer          | Aspire A315-21G             | [e740a4de27](https://linux-hardware.org/?probe=e740a4de27) | Oct 17, 2021 |
| Fujitsu       | LIFEBOOK A512               | [7a71621dde](https://linux-hardware.org/?probe=7a71621dde) | Oct 17, 2021 |
| Dell          | Latitude D630               | [b3e12559af](https://linux-hardware.org/?probe=b3e12559af) | Oct 17, 2021 |
| ASUSTek       | N50Vn                       | [3494a7c5b6](https://linux-hardware.org/?probe=3494a7c5b6) | Oct 16, 2021 |
| Lenovo        | ThinkPad T450s 20BWS0090... | [70872e756c](https://linux-hardware.org/?probe=70872e756c) | Oct 16, 2021 |
| Lenovo        | ThinkPad T450s 20BWS0090... | [8b133919fd](https://linux-hardware.org/?probe=8b133919fd) | Oct 16, 2021 |
| ASUSTek       | N50Vn                       | [a725c6feba](https://linux-hardware.org/?probe=a725c6feba) | Oct 16, 2021 |
| Apple         | MacBookPro12,1              | [4bfee9269a](https://linux-hardware.org/?probe=4bfee9269a) | Oct 16, 2021 |
| Fujitsu       | LIFEBOOK A530               | [8bf8b89539](https://linux-hardware.org/?probe=8bf8b89539) | Oct 15, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [70cb0eacd3](https://linux-hardware.org/?probe=70cb0eacd3) | Oct 15, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [b2342ea37d](https://linux-hardware.org/?probe=b2342ea37d) | Oct 15, 2021 |
| HP            | Presario CQ58               | [595d5385bc](https://linux-hardware.org/?probe=595d5385bc) | Oct 14, 2021 |
| HP            | Presario CQ58               | [8c8587b079](https://linux-hardware.org/?probe=8c8587b079) | Oct 14, 2021 |
| HP            | 250 G1                      | [2ec296247f](https://linux-hardware.org/?probe=2ec296247f) | Oct 14, 2021 |
| HP            | 250 G1                      | [c0cff54f9d](https://linux-hardware.org/?probe=c0cff54f9d) | Oct 14, 2021 |
| Lenovo        | ThinkPad T400 2768WGB       | [2ae81cd94f](https://linux-hardware.org/?probe=2ae81cd94f) | Oct 13, 2021 |
| Dell          | XPS 15 9570                 | [a72aad9b00](https://linux-hardware.org/?probe=a72aad9b00) | Oct 13, 2021 |
| Lenovo        | G580 20150                  | [a4da62f3ed](https://linux-hardware.org/?probe=a4da62f3ed) | Oct 12, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [bf181ddf64](https://linux-hardware.org/?probe=bf181ddf64) | Oct 10, 2021 |
| Dell          | Vostro 3401                 | [5e53dc591c](https://linux-hardware.org/?probe=5e53dc591c) | Oct 10, 2021 |
| Acer          | Swift SF114-32              | [7f914d54d9](https://linux-hardware.org/?probe=7f914d54d9) | Oct 08, 2021 |
| Lenovo        | E50-80 80J2                 | [80fc6ad252](https://linux-hardware.org/?probe=80fc6ad252) | Oct 08, 2021 |
| Lenovo        | E50-80 80J2                 | [ffdda637c6](https://linux-hardware.org/?probe=ffdda637c6) | Oct 08, 2021 |
| Dell          | Inspiron M5040              | [170de9cffb](https://linux-hardware.org/?probe=170de9cffb) | Oct 08, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [fe285a30ea](https://linux-hardware.org/?probe=fe285a30ea) | Oct 07, 2021 |
| Acer          | Aspire E5-573G              | [669024a52d](https://linux-hardware.org/?probe=669024a52d) | Oct 05, 2021 |
| HP            | EliteBook 840 G2            | [2df21ffa4d](https://linux-hardware.org/?probe=2df21ffa4d) | Oct 04, 2021 |
| Dell          | Inspiron 3537               | [db580317ec](https://linux-hardware.org/?probe=db580317ec) | Oct 01, 2021 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | [390b9a8a74](https://linux-hardware.org/?probe=390b9a8a74) | Oct 01, 2021 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [a0602a6457](https://linux-hardware.org/?probe=a0602a6457) | Sep 30, 2021 |
| ASUSTek       | Strix 15 GL503GE            | [21165a1b6d](https://linux-hardware.org/?probe=21165a1b6d) | Sep 30, 2021 |
| HP            | 650                         | [665fe92981](https://linux-hardware.org/?probe=665fe92981) | Sep 29, 2021 |
| HP            | 650                         | [068771ce30](https://linux-hardware.org/?probe=068771ce30) | Sep 29, 2021 |
| HP            | ENVY 15                     | [4b949c1a1b](https://linux-hardware.org/?probe=4b949c1a1b) | Sep 29, 2021 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [15138784a5](https://linux-hardware.org/?probe=15138784a5) | Sep 29, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [75b4cc49f0](https://linux-hardware.org/?probe=75b4cc49f0) | Sep 29, 2021 |
| eMachines     | E525                        | [e562d136e9](https://linux-hardware.org/?probe=e562d136e9) | Sep 29, 2021 |
| eMachines     | E525                        | [7962a481cb](https://linux-hardware.org/?probe=7962a481cb) | Sep 29, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [1fcc57fd89](https://linux-hardware.org/?probe=1fcc57fd89) | Sep 27, 2021 |
| Dell          | Latitude E6440              | [d3f2e61e9a](https://linux-hardware.org/?probe=d3f2e61e9a) | Sep 25, 2021 |
| Dell          | Inspiron 3537               | [cd2db35a2e](https://linux-hardware.org/?probe=cd2db35a2e) | Sep 25, 2021 |
| Dell          | Inspiron N4010              | [82ad91793d](https://linux-hardware.org/?probe=82ad91793d) | Sep 25, 2021 |
| Lenovo        | ThinkPad T400 2768WGB       | [fc93efcead](https://linux-hardware.org/?probe=fc93efcead) | Sep 25, 2021 |
| Lenovo        | ThinkPad T400 2768WGB       | [8a2d72befe](https://linux-hardware.org/?probe=8a2d72befe) | Sep 24, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [7565c48d46](https://linux-hardware.org/?probe=7565c48d46) | Sep 24, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [004998105d](https://linux-hardware.org/?probe=004998105d) | Sep 24, 2021 |
| HP            | Pavilion 17                 | [e97612e636](https://linux-hardware.org/?probe=e97612e636) | Sep 22, 2021 |
| Dell          | Vostro 15-3568              | [78b53bb20b](https://linux-hardware.org/?probe=78b53bb20b) | Sep 21, 2021 |
| Dell          | Vostro 15-3568              | [b65c308c97](https://linux-hardware.org/?probe=b65c308c97) | Sep 21, 2021 |
| Acer          | Aspire ES1-532G             | [ae4a442880](https://linux-hardware.org/?probe=ae4a442880) | Sep 20, 2021 |
| Dell          | Vostro 15-3568              | [c0334c463b](https://linux-hardware.org/?probe=c0334c463b) | Sep 20, 2021 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | [1e0de1e13f](https://linux-hardware.org/?probe=1e0de1e13f) | Sep 20, 2021 |
| ASUSTek       | X541UAK                     | [c0303b03f0](https://linux-hardware.org/?probe=c0303b03f0) | Sep 20, 2021 |
| Acer          | Aspire ES1-532G             | [d0709692c6](https://linux-hardware.org/?probe=d0709692c6) | Sep 20, 2021 |
| Acer          | TravelMate X514-51          | [a46639e28f](https://linux-hardware.org/?probe=a46639e28f) | Sep 20, 2021 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [b079ec3bca](https://linux-hardware.org/?probe=b079ec3bca) | Sep 18, 2021 |
| Dell          | Latitude E6430              | [b559ccbcf6](https://linux-hardware.org/?probe=b559ccbcf6) | Sep 18, 2021 |
| Packard Be... | EasyNote TK11BZ             | [3e3f80f7c6](https://linux-hardware.org/?probe=3e3f80f7c6) | Sep 18, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [3ad0348b26](https://linux-hardware.org/?probe=3ad0348b26) | Sep 18, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [1677f375b2](https://linux-hardware.org/?probe=1677f375b2) | Sep 18, 2021 |
| Lenovo        | ThinkPad P70 20ER003PGE     | [cea4459192](https://linux-hardware.org/?probe=cea4459192) | Sep 15, 2021 |
| Lenovo        | V130-15IKB 81HN             | [39ded78b09](https://linux-hardware.org/?probe=39ded78b09) | Sep 15, 2021 |
| Acer          | TravelMate 4400             | [8b304af834](https://linux-hardware.org/?probe=8b304af834) | Sep 15, 2021 |
| Lenovo        | ThinkPad T400 2768WGB       | [77d801bf3c](https://linux-hardware.org/?probe=77d801bf3c) | Sep 15, 2021 |
| Samsung       | R540/R580/R780/SA41/E452... | [9896fa3fa4](https://linux-hardware.org/?probe=9896fa3fa4) | Sep 15, 2021 |
| Lenovo        | G40-45 80E1                 | [48b771968f](https://linux-hardware.org/?probe=48b771968f) | Sep 14, 2021 |
| HP            | 620                         | [1ab2cc4e02](https://linux-hardware.org/?probe=1ab2cc4e02) | Sep 14, 2021 |
| Dell          | Inspiron 15-3567            | [591b18eef7](https://linux-hardware.org/?probe=591b18eef7) | Sep 13, 2021 |
| Lenovo        | V130-15IKB 81HN             | [eed7bb8324](https://linux-hardware.org/?probe=eed7bb8324) | Sep 13, 2021 |
| Dell          | Inspiron 7577               | [1a39f562b3](https://linux-hardware.org/?probe=1a39f562b3) | Sep 13, 2021 |
| Lenovo        | ThinkPad T420 42361P0       | [66dcb5905e](https://linux-hardware.org/?probe=66dcb5905e) | Sep 13, 2021 |
| Lenovo        | ThinkPad T420 42361P0       | [24f3d09047](https://linux-hardware.org/?probe=24f3d09047) | Sep 13, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [2f4eaa69ad](https://linux-hardware.org/?probe=2f4eaa69ad) | Sep 12, 2021 |
| Dell          | G3 3579                     | [c9add7ad1e](https://linux-hardware.org/?probe=c9add7ad1e) | Sep 12, 2021 |
| Dell          | Latitude 5420               | [fe7a0defea](https://linux-hardware.org/?probe=fe7a0defea) | Sep 12, 2021 |
| Dell          | Latitude 5420               | [e0b391ba90](https://linux-hardware.org/?probe=e0b391ba90) | Sep 12, 2021 |
| Lenovo        | V130-15IKB 81HN             | [b7cbadb1b3](https://linux-hardware.org/?probe=b7cbadb1b3) | Sep 12, 2021 |
| Dell          | XPS 15 9570                 | [661937dcfa](https://linux-hardware.org/?probe=661937dcfa) | Sep 12, 2021 |
| Dell          | XPS 15 9570                 | [a950c391ee](https://linux-hardware.org/?probe=a950c391ee) | Sep 12, 2021 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [8f7de35e87](https://linux-hardware.org/?probe=8f7de35e87) | Sep 09, 2021 |
| HP            | EliteBook 8470p             | [1dd7e46071](https://linux-hardware.org/?probe=1dd7e46071) | Sep 09, 2021 |
| Samsung       | N150/N210/N220              | [5443518a3c](https://linux-hardware.org/?probe=5443518a3c) | Sep 08, 2021 |
| Dell          | Latitude 5520               | [50c575ba9e](https://linux-hardware.org/?probe=50c575ba9e) | Sep 08, 2021 |
| Lenovo        | ThinkPad T420s 4174A53      | [38d904152e](https://linux-hardware.org/?probe=38d904152e) | Sep 08, 2021 |
| Lenovo        | ThinkPad T420s 4174A53      | [eceec06e8c](https://linux-hardware.org/?probe=eceec06e8c) | Sep 08, 2021 |
| Lenovo        | ThinkPad T400 2768WGB       | [7ed46b22a4](https://linux-hardware.org/?probe=7ed46b22a4) | Sep 08, 2021 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [3339b88a81](https://linux-hardware.org/?probe=3339b88a81) | Sep 07, 2021 |
| HP            | ProBook 4520s               | [7deeda6273](https://linux-hardware.org/?probe=7deeda6273) | Sep 07, 2021 |
| Acer          | F                           | [62b3bc2222](https://linux-hardware.org/?probe=62b3bc2222) | Sep 06, 2021 |
| Acer          | F                           | [016acbf29e](https://linux-hardware.org/?probe=016acbf29e) | Sep 06, 2021 |
| HP            | EliteBook 745 G2            | [dc9f6d9bf5](https://linux-hardware.org/?probe=dc9f6d9bf5) | Sep 06, 2021 |
| Dell          | Latitude E6420              | [8e0f8b77af](https://linux-hardware.org/?probe=8e0f8b77af) | Sep 05, 2021 |
| Dell          | Latitude E6420              | [0e7222da00](https://linux-hardware.org/?probe=0e7222da00) | Sep 05, 2021 |
| Dell          | Inspiron 5558               | [a656ff4b53](https://linux-hardware.org/?probe=a656ff4b53) | Sep 05, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [3a2547fb3c](https://linux-hardware.org/?probe=3a2547fb3c) | Sep 05, 2021 |
| ASUSTek       | 1215P                       | [dd6345e640](https://linux-hardware.org/?probe=dd6345e640) | Sep 04, 2021 |
| Lenovo        | ThinkPad T400 2768WGB       | [67fa77b42f](https://linux-hardware.org/?probe=67fa77b42f) | Sep 03, 2021 |
| Lenovo        | ThinkPad T400 2768WGB       | [dfcdd7558e](https://linux-hardware.org/?probe=dfcdd7558e) | Sep 03, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [c751938f66](https://linux-hardware.org/?probe=c751938f66) | Sep 03, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | [ae8bd5e632](https://linux-hardware.org/?probe=ae8bd5e632) | Sep 03, 2021 |
| Lenovo        | ThinkPad T400 2768WGB       | [a66a6f00e4](https://linux-hardware.org/?probe=a66a6f00e4) | Sep 03, 2021 |
| Lenovo        | ThinkPad T420s 4174A53      | [01adb249f3](https://linux-hardware.org/?probe=01adb249f3) | Sep 03, 2021 |
| Lenovo        | ThinkPad T400 2768WGB       | [4f0f285805](https://linux-hardware.org/?probe=4f0f285805) | Sep 03, 2021 |
| Acer          | TravelMate 5310             | [ac6597929a](https://linux-hardware.org/?probe=ac6597929a) | Sep 03, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [9df60e9850](https://linux-hardware.org/?probe=9df60e9850) | Sep 03, 2021 |
| HP            | ENVY 15                     | [d2bb5f165e](https://linux-hardware.org/?probe=d2bb5f165e) | Sep 01, 2021 |
| Dell          | Latitude 5420               | [335717eb52](https://linux-hardware.org/?probe=335717eb52) | Aug 30, 2021 |
| Samsung       | NC210/NC110                 | [1d2c227997](https://linux-hardware.org/?probe=1d2c227997) | Aug 30, 2021 |
| Insyde        | Braswell                    | [7857026d8a](https://linux-hardware.org/?probe=7857026d8a) | Aug 30, 2021 |
| Dell          | Inspiron 5558               | [61961ad5b1](https://linux-hardware.org/?probe=61961ad5b1) | Aug 30, 2021 |
| Toshiba       | Satellite C55-C             | [ebe9f952cc](https://linux-hardware.org/?probe=ebe9f952cc) | Aug 29, 2021 |
| Insyde        | Braswell                    | [8bdfa03ff1](https://linux-hardware.org/?probe=8bdfa03ff1) | Aug 29, 2021 |
| Insyde        | Braswell                    | [ef2719079d](https://linux-hardware.org/?probe=ef2719079d) | Aug 29, 2021 |
| Dell          | Latitude E6400              | [6b76ebb503](https://linux-hardware.org/?probe=6b76ebb503) | Aug 28, 2021 |
| Lenovo        | ThinkPad X260 20F5S6QX00    | [f10565a33d](https://linux-hardware.org/?probe=f10565a33d) | Aug 28, 2021 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [71a5232043](https://linux-hardware.org/?probe=71a5232043) | Aug 27, 2021 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [102e77fac6](https://linux-hardware.org/?probe=102e77fac6) | Aug 27, 2021 |
| Lenovo        | ThinkPad T420 4236Z9U       | [ccb6add1f8](https://linux-hardware.org/?probe=ccb6add1f8) | Aug 26, 2021 |
| Dell          | Latitude E6320              | [b9c8e81050](https://linux-hardware.org/?probe=b9c8e81050) | Aug 26, 2021 |
| Dell          | Latitude E6320              | [3d908f1107](https://linux-hardware.org/?probe=3d908f1107) | Aug 26, 2021 |
| Acer          | Swift SF314-42              | [63a90f69bb](https://linux-hardware.org/?probe=63a90f69bb) | Aug 26, 2021 |
| Fujitsu Si... | AMILO PRO V3515             | [696cade909](https://linux-hardware.org/?probe=696cade909) | Aug 25, 2021 |
| Lenovo        | V145-15AST 81MT             | [07a2d6ed16](https://linux-hardware.org/?probe=07a2d6ed16) | Aug 25, 2021 |
| MSI           | M670                        | [8db6fa7a1c](https://linux-hardware.org/?probe=8db6fa7a1c) | Aug 24, 2021 |
| Lenovo        | G500 20236                  | [73a5085a79](https://linux-hardware.org/?probe=73a5085a79) | Aug 24, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [1a571bccee](https://linux-hardware.org/?probe=1a571bccee) | Aug 24, 2021 |
| Lenovo        | ThinkPad T430 2349KQ3       | [04815c4b3a](https://linux-hardware.org/?probe=04815c4b3a) | Aug 23, 2021 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [6f6ea69bb2](https://linux-hardware.org/?probe=6f6ea69bb2) | Aug 23, 2021 |
| Fujitsu       | LIFEBOOK E756               | [ad2bc5b140](https://linux-hardware.org/?probe=ad2bc5b140) | Aug 23, 2021 |
| Dell          | Vostro 5471                 | [4e6b4d3b69](https://linux-hardware.org/?probe=4e6b4d3b69) | Aug 23, 2021 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [4c718cb3f4](https://linux-hardware.org/?probe=4c718cb3f4) | Aug 22, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | [e2bea90cec](https://linux-hardware.org/?probe=e2bea90cec) | Aug 22, 2021 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [d966ab0abc](https://linux-hardware.org/?probe=d966ab0abc) | Aug 22, 2021 |
| HP            | ProBook 6470b               | [3f31314b69](https://linux-hardware.org/?probe=3f31314b69) | Aug 22, 2021 |
| Dell          | Inspiron 5558               | [3141d99537](https://linux-hardware.org/?probe=3141d99537) | Aug 22, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | [7257fbcb36](https://linux-hardware.org/?probe=7257fbcb36) | Aug 21, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | [6b0d0cd446](https://linux-hardware.org/?probe=6b0d0cd446) | Aug 21, 2021 |
| Lenovo        | Z50-75 80EC                 | [90a3a840c5](https://linux-hardware.org/?probe=90a3a840c5) | Aug 21, 2021 |
| Lenovo        | Z50-75 80EC                 | [72d1104fb9](https://linux-hardware.org/?probe=72d1104fb9) | Aug 20, 2021 |
| Lenovo        | ThinkPad X60 1706GMG        | [263db92845](https://linux-hardware.org/?probe=263db92845) | Aug 17, 2021 |
| Dell          | Latitude E6400              | [71dc5f8ba2](https://linux-hardware.org/?probe=71dc5f8ba2) | Aug 17, 2021 |
| Toshiba       | Satellite L750              | [b9d7ea01d3](https://linux-hardware.org/?probe=b9d7ea01d3) | Aug 17, 2021 |
| Dell          | Latitude E6400              | [e479330726](https://linux-hardware.org/?probe=e479330726) | Aug 17, 2021 |
| Acer          | Swift SF314-59              | [3e1d44416d](https://linux-hardware.org/?probe=3e1d44416d) | Aug 16, 2021 |
| Dell          | Latitude D630               | [d2df28f3ce](https://linux-hardware.org/?probe=d2df28f3ce) | Aug 15, 2021 |
| Acer          | Swift SF314-59              | [223118b549](https://linux-hardware.org/?probe=223118b549) | Aug 15, 2021 |
| HP            | Compaq nc6400 (RM100AW#A... | [55629bc5f5](https://linux-hardware.org/?probe=55629bc5f5) | Aug 14, 2021 |
| HP            | Compaq nc6400 (RM100AW#A... | [4847736f17](https://linux-hardware.org/?probe=4847736f17) | Aug 14, 2021 |
| HP            | EliteBook 8470p             | [e0a8156e11](https://linux-hardware.org/?probe=e0a8156e11) | Aug 11, 2021 |
| HP            | ProBook 6450b               | [bc4f97b57d](https://linux-hardware.org/?probe=bc4f97b57d) | Aug 11, 2021 |
| HP            | 250 G5 Notebook PC          | [2e6a0e2dc9](https://linux-hardware.org/?probe=2e6a0e2dc9) | Aug 11, 2021 |
| HP            | 250 G5 Notebook PC          | [645f860f95](https://linux-hardware.org/?probe=645f860f95) | Aug 11, 2021 |
| Acer          | Acadia V1.45                | [674c93fe23](https://linux-hardware.org/?probe=674c93fe23) | Aug 10, 2021 |
| Lenovo        | Z51-70 80K6                 | [ae4b26780f](https://linux-hardware.org/?probe=ae4b26780f) | Aug 10, 2021 |
| Acer          | Aspire E1-571               | [146f910c76](https://linux-hardware.org/?probe=146f910c76) | Aug 09, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [d9e1a05930](https://linux-hardware.org/?probe=d9e1a05930) | Aug 09, 2021 |
| Lenovo        | ThinkPad T400 2768WGB       | [3d67fe63ad](https://linux-hardware.org/?probe=3d67fe63ad) | Aug 09, 2021 |
| Dell          | Inspiron 5558               | [d085548b4c](https://linux-hardware.org/?probe=d085548b4c) | Aug 09, 2021 |
| Toshiba       | Satellite C55-A-19D         | [1f942e8a05](https://linux-hardware.org/?probe=1f942e8a05) | Aug 06, 2021 |
| Toshiba       | Satellite C55-A-19D         | [f22eea3167](https://linux-hardware.org/?probe=f22eea3167) | Aug 06, 2021 |
| Dell          | Latitude E7450              | [57ff5a6546](https://linux-hardware.org/?probe=57ff5a6546) | Aug 06, 2021 |
| Dell          | Latitude E7450              | [0441f9ea79](https://linux-hardware.org/?probe=0441f9ea79) | Aug 06, 2021 |
| Lenovo        | Flex 2-14D 20376            | [dc5060d3a4](https://linux-hardware.org/?probe=dc5060d3a4) | Aug 05, 2021 |
| Lenovo        | Flex 2-14D 20376            | [92e83fc372](https://linux-hardware.org/?probe=92e83fc372) | Aug 05, 2021 |
| MSI           | U-100 Ver.001               | [480423bc8b](https://linux-hardware.org/?probe=480423bc8b) | Aug 04, 2021 |
| ASUSTek       | A7U                         | [011dfdf872](https://linux-hardware.org/?probe=011dfdf872) | Aug 03, 2021 |
| Toshiba       | Satellite Pro L300          | [56810e152d](https://linux-hardware.org/?probe=56810e152d) | Aug 02, 2021 |
| Dell          | G3 3579                     | [60616651d0](https://linux-hardware.org/?probe=60616651d0) | Aug 02, 2021 |
| Lenovo        | ThinkPad L420 78544UG       | [469a25a387](https://linux-hardware.org/?probe=469a25a387) | Aug 01, 2021 |
| ASUSTek       | ROG Strix G531GU_G531GU     | [29fa0f3b47](https://linux-hardware.org/?probe=29fa0f3b47) | Jul 31, 2021 |
| ASUSTek       | X550JX                      | [c69e06e7dc](https://linux-hardware.org/?probe=c69e06e7dc) | Jul 31, 2021 |
| Dell          | G5 5587                     | [035e2c24e8](https://linux-hardware.org/?probe=035e2c24e8) | Jul 31, 2021 |
| Dell          | G5 5587                     | [9f67659f5a](https://linux-hardware.org/?probe=9f67659f5a) | Jul 31, 2021 |
| HP            | ProBook 6470b               | [eec04aa99a](https://linux-hardware.org/?probe=eec04aa99a) | Jul 31, 2021 |
| HP            | ProBook 6470b               | [94632328c8](https://linux-hardware.org/?probe=94632328c8) | Jul 31, 2021 |
| Dell          | Latitude E5450              | [203e92fef9](https://linux-hardware.org/?probe=203e92fef9) | Jul 30, 2021 |
| Lenovo        | Y720-15IKB 80VR             | [db19ed5f30](https://linux-hardware.org/?probe=db19ed5f30) | Jul 30, 2021 |
| ASUSTek       | ROG Strix G531GU_G531GU     | [189ae5737f](https://linux-hardware.org/?probe=189ae5737f) | Jul 30, 2021 |
| Lenovo        | ThinkPad T500 2241CG9       | [912d324ee3](https://linux-hardware.org/?probe=912d324ee3) | Jul 29, 2021 |
| Lenovo        | ThinkPad E590 20NB000WHV    | [d9d7f4e3eb](https://linux-hardware.org/?probe=d9d7f4e3eb) | Jul 28, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [8cdb059bd7](https://linux-hardware.org/?probe=8cdb059bd7) | Jul 28, 2021 |
| Acer          | Aspire A315-21G             | [f6f7c5c935](https://linux-hardware.org/?probe=f6f7c5c935) | Jul 27, 2021 |
| Acer          | Aspire 5735                 | [a28b01d57e](https://linux-hardware.org/?probe=a28b01d57e) | Jul 27, 2021 |
| HP            | ProBook 4540s               | [0decc673fe](https://linux-hardware.org/?probe=0decc673fe) | Jul 27, 2021 |
| ASUSTek       | X550LD                      | [9bb5027af8](https://linux-hardware.org/?probe=9bb5027af8) | Jul 26, 2021 |
| ASUSTek       | X550LD                      | [f5ffd08a2d](https://linux-hardware.org/?probe=f5ffd08a2d) | Jul 26, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [2c81d26c70](https://linux-hardware.org/?probe=2c81d26c70) | Jul 26, 2021 |
| Acer          | Predator PH517-51           | [3c02eeb3b3](https://linux-hardware.org/?probe=3c02eeb3b3) | Jul 25, 2021 |
| Acer          | Predator PH517-51           | [98f2d80e8e](https://linux-hardware.org/?probe=98f2d80e8e) | Jul 25, 2021 |
| Acer          | Aspire 5735                 | [db933e0ebd](https://linux-hardware.org/?probe=db933e0ebd) | Jul 24, 2021 |
| Lenovo        | Flex 2-14D 20376            | [978cd052c6](https://linux-hardware.org/?probe=978cd052c6) | Jul 24, 2021 |
| HP            | EliteBook 8470p             | [296379d47c](https://linux-hardware.org/?probe=296379d47c) | Jul 24, 2021 |
| HP            | EliteBook 8470p             | [2dffc70504](https://linux-hardware.org/?probe=2dffc70504) | Jul 24, 2021 |
| ASUSTek       | X551CAP                     | [08a65e17b5](https://linux-hardware.org/?probe=08a65e17b5) | Jul 23, 2021 |
| ASUSTek       | X551CAP                     | [4bca8c2135](https://linux-hardware.org/?probe=4bca8c2135) | Jul 23, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [f281a6eac9](https://linux-hardware.org/?probe=f281a6eac9) | Jul 23, 2021 |
| Lenovo        | Flex 2-14D 20376            | [fdec85be7e](https://linux-hardware.org/?probe=fdec85be7e) | Jul 22, 2021 |
| ASUSTek       | X455LA                      | [2a7cc920d2](https://linux-hardware.org/?probe=2a7cc920d2) | Jul 22, 2021 |
| HP            | EliteBook 8530p             | [589a2ba326](https://linux-hardware.org/?probe=589a2ba326) | Jul 19, 2021 |
| HP            | EliteBook 8530p             | [e57777224a](https://linux-hardware.org/?probe=e57777224a) | Jul 19, 2021 |
| Fujitsu Si... | AMILO Xi 3650               | [561ed2dd58](https://linux-hardware.org/?probe=561ed2dd58) | Jul 18, 2021 |
| Dell          | G3 3579                     | [b376dde166](https://linux-hardware.org/?probe=b376dde166) | Jul 18, 2021 |
| Lenovo        | V145-15AST 81MT             | [ac665bab2e](https://linux-hardware.org/?probe=ac665bab2e) | Jul 17, 2021 |
| HUAWEI        | HLYL-WXX9                   | [a44ab9f722](https://linux-hardware.org/?probe=a44ab9f722) | Jul 17, 2021 |
| Dell          | Inspiron 7577               | [b221cbc463](https://linux-hardware.org/?probe=b221cbc463) | Jul 17, 2021 |
| Acer          | Aspire A315-21G             | [cbdec1f626](https://linux-hardware.org/?probe=cbdec1f626) | Jul 17, 2021 |
| Lenovo        | V145-15AST 81MT             | [861a7247ea](https://linux-hardware.org/?probe=861a7247ea) | Jul 16, 2021 |
| Dell          | G3 3579                     | [309fc0b931](https://linux-hardware.org/?probe=309fc0b931) | Jul 15, 2021 |
| Dell          | G3 3579                     | [4db8825aa6](https://linux-hardware.org/?probe=4db8825aa6) | Jul 15, 2021 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [5b765cf0bb](https://linux-hardware.org/?probe=5b765cf0bb) | Jul 12, 2021 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [437fa3ab41](https://linux-hardware.org/?probe=437fa3ab41) | Jul 12, 2021 |
| Toshiba       | Satellite L300              | [6103626346](https://linux-hardware.org/?probe=6103626346) | Jul 11, 2021 |
| HP            | ProBook 6570b               | [c96bdaba36](https://linux-hardware.org/?probe=c96bdaba36) | Jul 11, 2021 |
| HP            | ProBook 6570b               | [0142f24cd4](https://linux-hardware.org/?probe=0142f24cd4) | Jul 11, 2021 |
| Acer          | Aspire E5-773               | [7c4e8d0c1c](https://linux-hardware.org/?probe=7c4e8d0c1c) | Jul 10, 2021 |
| Acer          | Aspire 7750G                | [5cb3cd8c55](https://linux-hardware.org/?probe=5cb3cd8c55) | Jul 09, 2021 |
| Lenovo        | ThinkPad T400 6475W81       | [21a71a8f23](https://linux-hardware.org/?probe=21a71a8f23) | Jul 09, 2021 |
| Dell          | Latitude E6410              | [423920bd30](https://linux-hardware.org/?probe=423920bd30) | Jul 09, 2021 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [0a63b218ec](https://linux-hardware.org/?probe=0a63b218ec) | Jul 09, 2021 |
| Fujitsu Si... | AMILO Li 2727               | [53ae08bbd7](https://linux-hardware.org/?probe=53ae08bbd7) | Jul 08, 2021 |
| Fujitsu Si... | AMILO Li 2727               | [a11e614ce0](https://linux-hardware.org/?probe=a11e614ce0) | Jul 08, 2021 |
| ASUSTek       | X540LA                      | [95b6f836aa](https://linux-hardware.org/?probe=95b6f836aa) | Jul 08, 2021 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [2c8cdcb7b6](https://linux-hardware.org/?probe=2c8cdcb7b6) | Jul 08, 2021 |
| ASUSTek       | ZenBook 13 UX331FAL_UX33... | [31ae8b8049](https://linux-hardware.org/?probe=31ae8b8049) | Jul 08, 2021 |
| Dell          | G3 3579                     | [fb8f8476e1](https://linux-hardware.org/?probe=fb8f8476e1) | Jul 08, 2021 |
| Dell          | G3 3579                     | [245dc98218](https://linux-hardware.org/?probe=245dc98218) | Jul 08, 2021 |
| HP            | 250 G1                      | [294432f8ce](https://linux-hardware.org/?probe=294432f8ce) | Jul 08, 2021 |
| HP            | 250 G1                      | [af0ffff3e9](https://linux-hardware.org/?probe=af0ffff3e9) | Jul 08, 2021 |
| Dell          | Latitude E6410              | [c27b4de36e](https://linux-hardware.org/?probe=c27b4de36e) | Jul 07, 2021 |
| Lenovo        | G580                        | [e90428609f](https://linux-hardware.org/?probe=e90428609f) | Jul 07, 2021 |
| Dell          | Latitude E7470              | [30a4ee08e3](https://linux-hardware.org/?probe=30a4ee08e3) | Jul 07, 2021 |
| HP            | 250 G1                      | [5a2900dc56](https://linux-hardware.org/?probe=5a2900dc56) | Jul 07, 2021 |
| HP            | 250 G1                      | [a400d0ff73](https://linux-hardware.org/?probe=a400d0ff73) | Jul 07, 2021 |
| HP            | Pavilion g6                 | [c5091057e7](https://linux-hardware.org/?probe=c5091057e7) | Jul 06, 2021 |
| HP            | Pavilion g6                 | [93863aeca0](https://linux-hardware.org/?probe=93863aeca0) | Jul 05, 2021 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [4eef36a1a8](https://linux-hardware.org/?probe=4eef36a1a8) | Jul 05, 2021 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [f4376853bb](https://linux-hardware.org/?probe=f4376853bb) | Jul 05, 2021 |
| Dell          | Latitude E5470              | [279621a990](https://linux-hardware.org/?probe=279621a990) | Jul 05, 2021 |
| Dell          | Vostro 15-3568              | [12a581cdf9](https://linux-hardware.org/?probe=12a581cdf9) | Jul 04, 2021 |
| HP            | EliteBook 8440p             | [54918be301](https://linux-hardware.org/?probe=54918be301) | Jul 04, 2021 |
| Lenovo        | ThinkPad T400 6475W81       | [72f395a13b](https://linux-hardware.org/?probe=72f395a13b) | Jul 04, 2021 |
| Lenovo        | ThinkPad T400 6475W81       | [2b96de1195](https://linux-hardware.org/?probe=2b96de1195) | Jul 04, 2021 |
| Acer          | Aspire A315-32              | [abd46bd701](https://linux-hardware.org/?probe=abd46bd701) | Jul 03, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [7d081b14c6](https://linux-hardware.org/?probe=7d081b14c6) | Jul 03, 2021 |
| HP            | ZBook Fury 17 G7 Mobile ... | [c24fcd1454](https://linux-hardware.org/?probe=c24fcd1454) | Jul 02, 2021 |
| Toshiba       | Satellite C55-A-1NV         | [a5e757600b](https://linux-hardware.org/?probe=a5e757600b) | Jul 02, 2021 |
| Alcor         | Intel Education Tablet      | [c4ab659262](https://linux-hardware.org/?probe=c4ab659262) | Jul 01, 2021 |
| Alcor         | Intel Education Tablet      | [8157b090f8](https://linux-hardware.org/?probe=8157b090f8) | Jul 01, 2021 |
| Dell          | Latitude E7470              | [ef7ffab7f2](https://linux-hardware.org/?probe=ef7ffab7f2) | Jun 30, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | [d337aa625e](https://linux-hardware.org/?probe=d337aa625e) | Jun 30, 2021 |
| Alcor         | Intel Education Tablet      | [1164543f34](https://linux-hardware.org/?probe=1164543f34) | Jun 30, 2021 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [a2e3d692b7](https://linux-hardware.org/?probe=a2e3d692b7) | Jun 30, 2021 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [e465108823](https://linux-hardware.org/?probe=e465108823) | Jun 30, 2021 |
| Fujitsu       | LIFEBOOK S761               | [67b2b5e436](https://linux-hardware.org/?probe=67b2b5e436) | Jun 28, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | [a6a1935419](https://linux-hardware.org/?probe=a6a1935419) | Jun 27, 2021 |
| ASUSTek       | Strix 15 GL503GE            | [9256c09b4f](https://linux-hardware.org/?probe=9256c09b4f) | Jun 27, 2021 |
| Lenovo        | ThinkPad T460p 20FXS1SX0... | [09705e74ac](https://linux-hardware.org/?probe=09705e74ac) | Jun 27, 2021 |
| Acer          | Swift SF114-32              | [eab3844820](https://linux-hardware.org/?probe=eab3844820) | Jun 27, 2021 |
| HP            | ProBook 650 G5              | [00c095bc61](https://linux-hardware.org/?probe=00c095bc61) | Jun 27, 2021 |
| HP            | ZBook Fury 17 G7 Mobile ... | [c3d5fd07c1](https://linux-hardware.org/?probe=c3d5fd07c1) | Jun 27, 2021 |
| Acer          | Aspire 7738                 | [3f7b3f2d6b](https://linux-hardware.org/?probe=3f7b3f2d6b) | Jun 26, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [4f14f11ee3](https://linux-hardware.org/?probe=4f14f11ee3) | Jun 26, 2021 |
| Fujitsu       | LIFEBOOK S761               | [9991b431aa](https://linux-hardware.org/?probe=9991b431aa) | Jun 26, 2021 |
| HP            | ProBook 4730s               | [7e3d750bcf](https://linux-hardware.org/?probe=7e3d750bcf) | Jun 26, 2021 |
| Lenovo        | ThinkPad T410 2537KR6       | [dcfc0c4e7e](https://linux-hardware.org/?probe=dcfc0c4e7e) | Jun 25, 2021 |
| Clevo         | Unknown                     | [bfe26c3f21](https://linux-hardware.org/?probe=bfe26c3f21) | Jun 25, 2021 |
| Clevo         | Unknown                     | [2109e1a52e](https://linux-hardware.org/?probe=2109e1a52e) | Jun 25, 2021 |
| Lenovo        | ThinkPad T410 2537KR6       | [0586c90301](https://linux-hardware.org/?probe=0586c90301) | Jun 25, 2021 |
| Dell          | G3 3579                     | [c401a50882](https://linux-hardware.org/?probe=c401a50882) | Jun 25, 2021 |
| ASUSTek       | 1015BX                      | [d16bf50692](https://linux-hardware.org/?probe=d16bf50692) | Jun 24, 2021 |
| Dell          | Latitude E5520              | [d62458bdba](https://linux-hardware.org/?probe=d62458bdba) | Jun 24, 2021 |
| Dell          | Latitude 5511               | [10434415d8](https://linux-hardware.org/?probe=10434415d8) | Jun 24, 2021 |
| Lenovo        | ThinkPad W540 20BHS04T0K    | [7f9142fffb](https://linux-hardware.org/?probe=7f9142fffb) | Jun 24, 2021 |
| Lenovo        | G550 20023                  | [4f1e828f8f](https://linux-hardware.org/?probe=4f1e828f8f) | Jun 23, 2021 |
| Lenovo        | G580 20150                  | [365b7a8c77](https://linux-hardware.org/?probe=365b7a8c77) | Jun 22, 2021 |
| Medion        | E6220                       | [f51542090f](https://linux-hardware.org/?probe=f51542090f) | Jun 22, 2021 |
| Medion        | E6220                       | [3e82c8d336](https://linux-hardware.org/?probe=3e82c8d336) | Jun 22, 2021 |
| Dell          | Studio XPS 1647             | [fc9cf612e0](https://linux-hardware.org/?probe=fc9cf612e0) | Jun 22, 2021 |
| Dell          | Studio XPS 1647             | [29c1017d6a](https://linux-hardware.org/?probe=29c1017d6a) | Jun 22, 2021 |
| Lenovo        | ThinkPad T400 6474W66       | [0a7af0b209](https://linux-hardware.org/?probe=0a7af0b209) | Jun 22, 2021 |
| Lenovo        | ThinkPad T400 6474W66       | [30c9e5abef](https://linux-hardware.org/?probe=30c9e5abef) | Jun 21, 2021 |
| Toshiba       | Satellite M50D-A            | [418ed859c6](https://linux-hardware.org/?probe=418ed859c6) | Jun 21, 2021 |
| Toshiba       | Satellite M50D-A            | [79390f4848](https://linux-hardware.org/?probe=79390f4848) | Jun 20, 2021 |
| Lenovo        | G550 20023                  | [c61bd1175b](https://linux-hardware.org/?probe=c61bd1175b) | Jun 20, 2021 |
| Toshiba       | Satellite M50D-A            | [c2d32cddb9](https://linux-hardware.org/?probe=c2d32cddb9) | Jun 18, 2021 |
| Toshiba       | Satellite C660              | [26ee332633](https://linux-hardware.org/?probe=26ee332633) | Jun 18, 2021 |
| HP            | 250 G1                      | [999f6b9bf6](https://linux-hardware.org/?probe=999f6b9bf6) | Jun 18, 2021 |
| HP            | 250 G1                      | [7e2901e0e7](https://linux-hardware.org/?probe=7e2901e0e7) | Jun 18, 2021 |
| Sony          | VGN-FZ31S                   | [2d9cce8f8d](https://linux-hardware.org/?probe=2d9cce8f8d) | Jun 17, 2021 |
| Lenovo        | ThinkPad P50 20EQS3B41R     | [c9db630f4f](https://linux-hardware.org/?probe=c9db630f4f) | Jun 17, 2021 |
| Lenovo        | ThinkPad P50 20EQS3B41R     | [b4373a2445](https://linux-hardware.org/?probe=b4373a2445) | Jun 17, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [ac8e80e0cc](https://linux-hardware.org/?probe=ac8e80e0cc) | Jun 15, 2021 |
| HP            | ProBook 650 G5              | [9a8312032f](https://linux-hardware.org/?probe=9a8312032f) | Jun 15, 2021 |
| Dell          | Latitude E4200              | [cd56e039c0](https://linux-hardware.org/?probe=cd56e039c0) | Jun 14, 2021 |
| Medion        | Akoya THE TOUCH 10          | [b5c89fa6c1](https://linux-hardware.org/?probe=b5c89fa6c1) | Jun 14, 2021 |
| HP            | Presario CQ56               | [921b0ebcdc](https://linux-hardware.org/?probe=921b0ebcdc) | Jun 13, 2021 |
| HP            | Presario CQ56               | [f91003573a](https://linux-hardware.org/?probe=f91003573a) | Jun 13, 2021 |
| Medion        | Akoya THE TOUCH 10          | [56b32c2b32](https://linux-hardware.org/?probe=56b32c2b32) | Jun 12, 2021 |
| HP            | 250 G1                      | [693e61bf6a](https://linux-hardware.org/?probe=693e61bf6a) | Jun 12, 2021 |
| HP            | 250 G1                      | [9a83c195c4](https://linux-hardware.org/?probe=9a83c195c4) | Jun 12, 2021 |
| Hungaro Fl... | Navon Stark NX14 PRO 201... | [7db65618da](https://linux-hardware.org/?probe=7db65618da) | Jun 11, 2021 |
| Hungaro Fl... | Navon Stark NX14 PRO 201... | [4b06513768](https://linux-hardware.org/?probe=4b06513768) | Jun 11, 2021 |
| Lenovo        | V145-15AST 81MT             | [cbd2756905](https://linux-hardware.org/?probe=cbd2756905) | Jun 11, 2021 |
| Acer          | Aspire 7750G                | [6bddbb6c2a](https://linux-hardware.org/?probe=6bddbb6c2a) | Jun 11, 2021 |
| Lenovo        | G580 20150                  | [a6c7274e6f](https://linux-hardware.org/?probe=a6c7274e6f) | Jun 10, 2021 |
| Toshiba       | Satellite L300              | [3cceb6e3b5](https://linux-hardware.org/?probe=3cceb6e3b5) | Jun 10, 2021 |
| Toshiba       | Satellite L300              | [f48e689dcc](https://linux-hardware.org/?probe=f48e689dcc) | Jun 10, 2021 |
| Acer          | Aspire V3-372               | [cef1a574e6](https://linux-hardware.org/?probe=cef1a574e6) | Jun 10, 2021 |
| Acer          | Aspire V3-372               | [74c08d970a](https://linux-hardware.org/?probe=74c08d970a) | Jun 10, 2021 |
| ASUSTek       | K53TA                       | [f8db9dd91d](https://linux-hardware.org/?probe=f8db9dd91d) | Jun 09, 2021 |
| HP            | Pavilion Laptop 15-cc5xx    | [560b3be08f](https://linux-hardware.org/?probe=560b3be08f) | Jun 09, 2021 |
| HP            | Compaq 6710b (GR684EA#AK... | [a9e775e56c](https://linux-hardware.org/?probe=a9e775e56c) | Jun 09, 2021 |
| HP            | Compaq 6710b (GR684EA#AK... | [37af9a1167](https://linux-hardware.org/?probe=37af9a1167) | Jun 09, 2021 |
| MSI           | MS-1674 Ver                 | [2b037b30b1](https://linux-hardware.org/?probe=2b037b30b1) | Jun 08, 2021 |
| MSI           | MS-1674 Ver                 | [6c52c94714](https://linux-hardware.org/?probe=6c52c94714) | Jun 08, 2021 |
| HP            | Laptop 14s-fq0xxx           | [f485f80d53](https://linux-hardware.org/?probe=f485f80d53) | Jun 08, 2021 |
| HP            | 250 G1                      | [ad972b5829](https://linux-hardware.org/?probe=ad972b5829) | Jun 07, 2021 |
| Fujitsu Si... | AMILO Xi 3650               | [7dd86b4c8f](https://linux-hardware.org/?probe=7dd86b4c8f) | Jun 07, 2021 |
| ASUSTek       | X540LJ                      | [634949901a](https://linux-hardware.org/?probe=634949901a) | Jun 07, 2021 |
| HP            | 650                         | [c20dad874f](https://linux-hardware.org/?probe=c20dad874f) | Jun 07, 2021 |
| HP            | 650                         | [c7fce24360](https://linux-hardware.org/?probe=c7fce24360) | Jun 07, 2021 |
| Timi          | Mi Gaming Laptop 15.6       | [4766b913b6](https://linux-hardware.org/?probe=4766b913b6) | Jun 07, 2021 |
| Lenovo        | ThinkPad X250 20CLS7WY04    | [fc77801294](https://linux-hardware.org/?probe=fc77801294) | Jun 07, 2021 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | [aef4e323e2](https://linux-hardware.org/?probe=aef4e323e2) | Jun 06, 2021 |
| Samsung       | N150/N210/N220              | [f8ee78fcd6](https://linux-hardware.org/?probe=f8ee78fcd6) | Jun 06, 2021 |
| Dell          | G3 3579                     | [cda7c1f13e](https://linux-hardware.org/?probe=cda7c1f13e) | Jun 06, 2021 |
| Lenovo        | ThinkPad T440 20B7S27U00    | [6e357d5654](https://linux-hardware.org/?probe=6e357d5654) | Jun 06, 2021 |
| Lenovo        | ThinkPad T440 20B7S27U00    | [f0e837b577](https://linux-hardware.org/?probe=f0e837b577) | Jun 06, 2021 |
| Toshiba       | Satellite Pro C850-1LZ      | [a3b1bfc5e8](https://linux-hardware.org/?probe=a3b1bfc5e8) | Jun 06, 2021 |
| Packard Be... | EasyNote TM86               | [72778d6fb0](https://linux-hardware.org/?probe=72778d6fb0) | Jun 06, 2021 |
| Packard Be... | EasyNote TM86               | [c58e894035](https://linux-hardware.org/?probe=c58e894035) | Jun 06, 2021 |
| Fujitsu       | LIFEBOOK AH530              | [3d165be0e2](https://linux-hardware.org/?probe=3d165be0e2) | Jun 04, 2021 |
| Acer          | Aspire 5736Z                | [3af4bd4aee](https://linux-hardware.org/?probe=3af4bd4aee) | Jun 02, 2021 |
| Acer          | Aspire 5736Z                | [47262b3d8b](https://linux-hardware.org/?probe=47262b3d8b) | Jun 02, 2021 |
| Lenovo        | ThinkPad X230 2325AC7       | [23bb129cd2](https://linux-hardware.org/?probe=23bb129cd2) | Jun 02, 2021 |
| Lenovo        | ThinkPad X240 20AMA0XK00    | [8b7ecca1b8](https://linux-hardware.org/?probe=8b7ecca1b8) | Jun 02, 2021 |
| Dell          | Latitude E5420              | [9593642c34](https://linux-hardware.org/?probe=9593642c34) | Jun 01, 2021 |
| Dell          | Latitude E5420              | [eab182df77](https://linux-hardware.org/?probe=eab182df77) | Jun 01, 2021 |
| HP            | EliteBook 6930p             | [5254456bae](https://linux-hardware.org/?probe=5254456bae) | Jun 01, 2021 |
| Acer          | Aspire E5-774G              | [840315c6bd](https://linux-hardware.org/?probe=840315c6bd) | Jun 01, 2021 |
| HP            | ProBook 455 G4              | [3ea595a278](https://linux-hardware.org/?probe=3ea595a278) | May 31, 2021 |
| Dell          | Inspiron 5558               | [6a14872523](https://linux-hardware.org/?probe=6a14872523) | May 31, 2021 |
| ASUSTek       | X751MA                      | [a5a95a0f7b](https://linux-hardware.org/?probe=a5a95a0f7b) | May 31, 2021 |
| Timi          | Mi Gaming Laptop 15.6       | [ecc7f6b940](https://linux-hardware.org/?probe=ecc7f6b940) | May 31, 2021 |
| Dell          | Precision M4600             | [ee6c9c38b0](https://linux-hardware.org/?probe=ee6c9c38b0) | May 31, 2021 |
| HP            | ProBook 650 G2              | [bb92ab2244](https://linux-hardware.org/?probe=bb92ab2244) | May 30, 2021 |
| HP            | ProBook 4730s               | [deddbf979a](https://linux-hardware.org/?probe=deddbf979a) | May 30, 2021 |
| HP            | ProBook 4730s               | [b159faf10b](https://linux-hardware.org/?probe=b159faf10b) | May 30, 2021 |
| ASUSTek       | X751MA                      | [1f32496911](https://linux-hardware.org/?probe=1f32496911) | May 29, 2021 |
| ASUSTek       | X550EA                      | [e8b5dd859f](https://linux-hardware.org/?probe=e8b5dd859f) | May 29, 2021 |
| ASUSTek       | X550EA                      | [c8313d0a4a](https://linux-hardware.org/?probe=c8313d0a4a) | May 29, 2021 |
| Lenovo        | ThinkPad W510 431924G       | [41032e0f42](https://linux-hardware.org/?probe=41032e0f42) | May 28, 2021 |
| eMachines     | eME730G                     | [2c401bfdb4](https://linux-hardware.org/?probe=2c401bfdb4) | May 28, 2021 |
| eMachines     | eME730G                     | [c2b6786ab1](https://linux-hardware.org/?probe=c2b6786ab1) | May 28, 2021 |
| Lenovo        | V145-15AST 81MT             | [be27200090](https://linux-hardware.org/?probe=be27200090) | May 27, 2021 |
| Dell          | Latitude E6530              | [2907e3bb7d](https://linux-hardware.org/?probe=2907e3bb7d) | May 27, 2021 |
| Lenovo        | G505s 20255                 | [d6021a2855](https://linux-hardware.org/?probe=d6021a2855) | May 27, 2021 |
| Panasonic     | CF-19KDR80SH                | [99920ad031](https://linux-hardware.org/?probe=99920ad031) | May 26, 2021 |
| Panasonic     | CF-19KDR80SH                | [62858c1431](https://linux-hardware.org/?probe=62858c1431) | May 26, 2021 |
| Dell          | Latitude 5500               | [6265641cb1](https://linux-hardware.org/?probe=6265641cb1) | May 26, 2021 |
| Lenovo        | ThinkPad X220 429137G       | [b948fe4dd5](https://linux-hardware.org/?probe=b948fe4dd5) | May 25, 2021 |
| Lenovo        | ThinkPad X220 429137G       | [fb0db11f08](https://linux-hardware.org/?probe=fb0db11f08) | May 25, 2021 |
| Dell          | Latitude E6410              | [124fdcdccb](https://linux-hardware.org/?probe=124fdcdccb) | May 25, 2021 |
| Dell          | Latitude E6410              | [5715f12aee](https://linux-hardware.org/?probe=5715f12aee) | May 24, 2021 |
| ASUSTek       | K53BR                       | [6c0b7d6353](https://linux-hardware.org/?probe=6c0b7d6353) | May 24, 2021 |
| ASUSTek       | K53BR                       | [749f7b2e97](https://linux-hardware.org/?probe=749f7b2e97) | May 24, 2021 |
| Dell          | Precision M4800             | [a85ce8a041](https://linux-hardware.org/?probe=a85ce8a041) | May 24, 2021 |
| Lenovo        | G505s 20255                 | [abd645e7e0](https://linux-hardware.org/?probe=abd645e7e0) | May 23, 2021 |
| Lenovo        | V145-15AST 81MT             | [594255735f](https://linux-hardware.org/?probe=594255735f) | May 23, 2021 |
| Lenovo        | V330-15IKB 81AX             | [220542e252](https://linux-hardware.org/?probe=220542e252) | May 23, 2021 |
| HP            | Pavilion dv7                | [4e073a7e79](https://linux-hardware.org/?probe=4e073a7e79) | May 23, 2021 |
| HP            | Pavilion dv7                | [f6c91f906d](https://linux-hardware.org/?probe=f6c91f906d) | May 23, 2021 |
| Sony          | VPCYB3V1E                   | [02a7199588](https://linux-hardware.org/?probe=02a7199588) | May 23, 2021 |
| Sony          | VPCYB3V1E                   | [abe64c1425](https://linux-hardware.org/?probe=abe64c1425) | May 23, 2021 |
| Toshiba       | Satellite L750              | [f676707da3](https://linux-hardware.org/?probe=f676707da3) | May 23, 2021 |
| Toshiba       | Satellite L750              | [b2a5682582](https://linux-hardware.org/?probe=b2a5682582) | May 23, 2021 |
| HP            | Pavilion g7                 | [5deedda73f](https://linux-hardware.org/?probe=5deedda73f) | May 22, 2021 |
| HP            | Pavilion g7                 | [571a1f70a4](https://linux-hardware.org/?probe=571a1f70a4) | May 22, 2021 |
| Dell          | Inspiron 5558               | [1d53531d20](https://linux-hardware.org/?probe=1d53531d20) | May 22, 2021 |
| HP            | EliteBook 2540p             | [383932e73b](https://linux-hardware.org/?probe=383932e73b) | May 22, 2021 |
| HP            | ProBook 645 G1              | [dc3a057a95](https://linux-hardware.org/?probe=dc3a057a95) | May 22, 2021 |
| HP            | ProBook 645 G1              | [9953d450e6](https://linux-hardware.org/?probe=9953d450e6) | May 22, 2021 |
| ASUSTek       | X302LA                      | [083220e9b6](https://linux-hardware.org/?probe=083220e9b6) | May 22, 2021 |
| Lenovo        | ThinkPad W510 431924G       | [c9fa162681](https://linux-hardware.org/?probe=c9fa162681) | May 20, 2021 |
| ASUSTek       | X553SA                      | [218b46a19b](https://linux-hardware.org/?probe=218b46a19b) | May 19, 2021 |
| HP            | EliteBook 2540p             | [6821c0f82d](https://linux-hardware.org/?probe=6821c0f82d) | May 19, 2021 |
| HP            | 250 G1                      | [a49b4080f6](https://linux-hardware.org/?probe=a49b4080f6) | May 19, 2021 |
| HP            | 250 G1                      | [89018d40b0](https://linux-hardware.org/?probe=89018d40b0) | May 19, 2021 |
| ASUSTek       | A6M                         | [7bd5fa25b3](https://linux-hardware.org/?probe=7bd5fa25b3) | May 19, 2021 |
| HP            | 620                         | [702bda56a6](https://linux-hardware.org/?probe=702bda56a6) | May 18, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [089c319771](https://linux-hardware.org/?probe=089c319771) | May 18, 2021 |
| HP            | 620                         | [c02423a6cb](https://linux-hardware.org/?probe=c02423a6cb) | May 18, 2021 |
| HP            | 620                         | [b223c8dc46](https://linux-hardware.org/?probe=b223c8dc46) | May 18, 2021 |
| HP            | 620                         | [f257a4e2c6](https://linux-hardware.org/?probe=f257a4e2c6) | May 18, 2021 |
| Lenovo        | ThinkPad X250 20CLS1B803    | [ae357880c6](https://linux-hardware.org/?probe=ae357880c6) | May 18, 2021 |
| ASUSTek       | Strix 17 GL703GE            | [1cba3fc4fc](https://linux-hardware.org/?probe=1cba3fc4fc) | May 17, 2021 |
| HP            | ProBook 470 G1              | [136f81ef7f](https://linux-hardware.org/?probe=136f81ef7f) | May 17, 2021 |
| HP            | ProBook 470 G1              | [6e18c4e275](https://linux-hardware.org/?probe=6e18c4e275) | May 17, 2021 |
| HP            | 250 G1                      | [91b556e2a3](https://linux-hardware.org/?probe=91b556e2a3) | May 17, 2021 |
| HP            | 250 G1                      | [a8d99782e0](https://linux-hardware.org/?probe=a8d99782e0) | May 17, 2021 |
| HP            | EliteBook 8460p             | [37f8994bef](https://linux-hardware.org/?probe=37f8994bef) | May 17, 2021 |
| HP            | Laptop 15-da0xxx            | [eb1d2a1481](https://linux-hardware.org/?probe=eb1d2a1481) | May 17, 2021 |
| Dell          | Latitude 5500               | [4a47f18d16](https://linux-hardware.org/?probe=4a47f18d16) | May 16, 2021 |
| Dell          | Latitude 5401               | [335ecbb107](https://linux-hardware.org/?probe=335ecbb107) | May 16, 2021 |
| Acer          | Aspire A317-51G             | [da0502dc81](https://linux-hardware.org/?probe=da0502dc81) | May 16, 2021 |
| Lenovo        | ThinkPad X220 4293ER9       | [d2d5707dfd](https://linux-hardware.org/?probe=d2d5707dfd) | May 16, 2021 |
| Lenovo        | ThinkPad X220 4293ER9       | [5be89fccef](https://linux-hardware.org/?probe=5be89fccef) | May 16, 2021 |
| Acer          | Aspire 5333                 | [9327d7f9d1](https://linux-hardware.org/?probe=9327d7f9d1) | May 16, 2021 |
| Acer          | Aspire 5333                 | [44a472472a](https://linux-hardware.org/?probe=44a472472a) | May 15, 2021 |
| Lenovo        | ThinkPad X230 23259S9       | [38ceebb313](https://linux-hardware.org/?probe=38ceebb313) | May 15, 2021 |
| Dell          | Latitude E6330              | [4d7a7112a7](https://linux-hardware.org/?probe=4d7a7112a7) | May 14, 2021 |
| Acer          | Aspire 5610Z                | [4a0ee2eaa5](https://linux-hardware.org/?probe=4a0ee2eaa5) | May 14, 2021 |
| HP            | EliteBook 8540p             | [ffc46c9472](https://linux-hardware.org/?probe=ffc46c9472) | May 14, 2021 |
| Apple         | MacBookPro11,1              | [aa4c3ffed1](https://linux-hardware.org/?probe=aa4c3ffed1) | May 13, 2021 |
| HP            | ProBook 470 G1              | [66aabe5a6b](https://linux-hardware.org/?probe=66aabe5a6b) | May 13, 2021 |
| Toshiba       | Satellite C50D-A-133        | [0933fd31a1](https://linux-hardware.org/?probe=0933fd31a1) | May 13, 2021 |
| Toshiba       | Satellite C50D-A-133        | [2a7ec0ced7](https://linux-hardware.org/?probe=2a7ec0ced7) | May 12, 2021 |
| Acer          | Aspire SW3-013              | [ce6278c83c](https://linux-hardware.org/?probe=ce6278c83c) | May 12, 2021 |
| ASUSTek       | K52F                        | [9a11016355](https://linux-hardware.org/?probe=9a11016355) | May 12, 2021 |
| Acer          | Aspire SW3-013              | [83527d6c70](https://linux-hardware.org/?probe=83527d6c70) | May 12, 2021 |
| ASUSTek       | X555LB                      | [10b0865cab](https://linux-hardware.org/?probe=10b0865cab) | May 12, 2021 |
| Lenovo        | ThinkPad SL510 2847D8G      | [a687d09de6](https://linux-hardware.org/?probe=a687d09de6) | May 12, 2021 |
| ASUSTek       | K52F                        | [7e069d7ec9](https://linux-hardware.org/?probe=7e069d7ec9) | May 11, 2021 |
| ASUSTek       | F3Sc                        | [2494100ecb](https://linux-hardware.org/?probe=2494100ecb) | May 11, 2021 |
| ASUSTek       | F3Sc                        | [b274e46d26](https://linux-hardware.org/?probe=b274e46d26) | May 11, 2021 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | [e1e3be9efa](https://linux-hardware.org/?probe=e1e3be9efa) | May 11, 2021 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | [d8c688b688](https://linux-hardware.org/?probe=d8c688b688) | May 11, 2021 |
| Acer          | Aspire E1-530G              | [b890252fee](https://linux-hardware.org/?probe=b890252fee) | May 11, 2021 |
| HP            | EliteBook 8460p             | [e9b0567130](https://linux-hardware.org/?probe=e9b0567130) | May 11, 2021 |
| Acer          | Aspire A515-51G             | [03c919462c](https://linux-hardware.org/?probe=03c919462c) | May 11, 2021 |
| Fujitsu       | LIFEBOOK E751               | [70d2c30d2e](https://linux-hardware.org/?probe=70d2c30d2e) | May 11, 2021 |
| Acer          | Aspire A515-51G             | [9c1f8fc4cc](https://linux-hardware.org/?probe=9c1f8fc4cc) | May 10, 2021 |
| Acer          | Swift SF114-32              | [09ca2a6a53](https://linux-hardware.org/?probe=09ca2a6a53) | May 10, 2021 |
| Fujitsu       | LIFEBOOK E751               | [dd73d6b0ec](https://linux-hardware.org/?probe=dd73d6b0ec) | May 10, 2021 |
| Dell          | Inspiron 1018               | [d6c52e4456](https://linux-hardware.org/?probe=d6c52e4456) | May 09, 2021 |
| Dell          | Inspiron 1018               | [2d89d05cad](https://linux-hardware.org/?probe=2d89d05cad) | May 09, 2021 |
| Acer          | Aspire A315-53G             | [a706597a80](https://linux-hardware.org/?probe=a706597a80) | May 09, 2021 |
| Acer          | Aspire A315-53G             | [e2cb22ac9f](https://linux-hardware.org/?probe=e2cb22ac9f) | May 09, 2021 |
| ASUSTek       | X553SA                      | [075cfa61b8](https://linux-hardware.org/?probe=075cfa61b8) | May 09, 2021 |
| ASUSTek       | X553SA                      | [4eb5ce5eda](https://linux-hardware.org/?probe=4eb5ce5eda) | May 09, 2021 |
| Toshiba       | Satellite L500              | [743decd6fb](https://linux-hardware.org/?probe=743decd6fb) | May 08, 2021 |
| Dell          | Latitude D830               | [0b37bdb895](https://linux-hardware.org/?probe=0b37bdb895) | May 08, 2021 |
| HP            | ProBook 4740s               | [d8d5635b4a](https://linux-hardware.org/?probe=d8d5635b4a) | May 08, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [20f49f94f6](https://linux-hardware.org/?probe=20f49f94f6) | May 08, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [a4a9d8692a](https://linux-hardware.org/?probe=a4a9d8692a) | May 07, 2021 |
| Dell          | Inspiron 3576               | [743ffeb160](https://linux-hardware.org/?probe=743ffeb160) | May 06, 2021 |
| Dell          | Inspiron 3576               | [3ca8016da2](https://linux-hardware.org/?probe=3ca8016da2) | May 06, 2021 |
| Toshiba       | Satellite L300              | [8c5a2f7078](https://linux-hardware.org/?probe=8c5a2f7078) | May 05, 2021 |
| Toshiba       | Satellite L300              | [e09bf3a647](https://linux-hardware.org/?probe=e09bf3a647) | May 05, 2021 |
| Lenovo        | V145-15AST 81MT             | [e8994663d5](https://linux-hardware.org/?probe=e8994663d5) | May 05, 2021 |
| Dell          | Inspiron 5547               | [dc736c2997](https://linux-hardware.org/?probe=dc736c2997) | May 04, 2021 |
| Dell          | Inspiron 5547               | [323100dee1](https://linux-hardware.org/?probe=323100dee1) | May 03, 2021 |
| HP            | Compaq 6710b (KE121EA#AK... | [7d7629b2dc](https://linux-hardware.org/?probe=7d7629b2dc) | May 03, 2021 |
| ordissimo     | E17201                      | [ada3ab54e0](https://linux-hardware.org/?probe=ada3ab54e0) | May 03, 2021 |
| HP            | ProBook 6470b               | [6f4dfe8056](https://linux-hardware.org/?probe=6f4dfe8056) | May 02, 2021 |
| Lenovo        | G580 20150                  | [9e26f24725](https://linux-hardware.org/?probe=9e26f24725) | May 02, 2021 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | [fa2f690693](https://linux-hardware.org/?probe=fa2f690693) | May 02, 2021 |
| Lenovo        | G550 20023                  | [b9ce65486b](https://linux-hardware.org/?probe=b9ce65486b) | May 02, 2021 |
| Lenovo        | G550 20023                  | [3e6a6c06c0](https://linux-hardware.org/?probe=3e6a6c06c0) | May 02, 2021 |
| HP            | 250 G6 Notebook PC          | [e8192d388e](https://linux-hardware.org/?probe=e8192d388e) | May 02, 2021 |
| HP            | ElitePad 1000 G2            | [0015c6d1ec](https://linux-hardware.org/?probe=0015c6d1ec) | May 01, 2021 |
| HP            | Pavilion 15                 | [882223f1be](https://linux-hardware.org/?probe=882223f1be) | May 01, 2021 |
| Dell          | Latitude E6410              | [fa7d551f9c](https://linux-hardware.org/?probe=fa7d551f9c) | May 01, 2021 |
| Apple         | MacBookPro8,1               | [a737bdbca0](https://linux-hardware.org/?probe=a737bdbca0) | May 01, 2021 |
| Dell          | Inspiron 3542               | [2d9029a89c](https://linux-hardware.org/?probe=2d9029a89c) | May 01, 2021 |
| Acer          | Aspire ES1-332              | [a0ebb17e2e](https://linux-hardware.org/?probe=a0ebb17e2e) | May 01, 2021 |
| Dell          | Precision M4700             | [908638c5f1](https://linux-hardware.org/?probe=908638c5f1) | May 01, 2021 |
| ASUSTek       | K50AB                       | [30be682e1d](https://linux-hardware.org/?probe=30be682e1d) | Apr 30, 2021 |
| HP            | 250 G6 Notebook PC          | [cd5fe9200b](https://linux-hardware.org/?probe=cd5fe9200b) | Apr 29, 2021 |
| Acer          | Aspire one                  | [49995bd052](https://linux-hardware.org/?probe=49995bd052) | Apr 28, 2021 |
| Acer          | Swift SF114-32              | [2b9b5faf20](https://linux-hardware.org/?probe=2b9b5faf20) | Apr 28, 2021 |
| Lenovo        | ThinkPad P50 20EQS3B41R     | [cb16115760](https://linux-hardware.org/?probe=cb16115760) | Apr 28, 2021 |
| Lenovo        | ThinkPad T460p 20FXS1SX0... | [267f4b13f7](https://linux-hardware.org/?probe=267f4b13f7) | Apr 28, 2021 |
| Lenovo        | ThinkPad T460p 20FXS1SX0... | [9595aedbc6](https://linux-hardware.org/?probe=9595aedbc6) | Apr 28, 2021 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | [5886b4f226](https://linux-hardware.org/?probe=5886b4f226) | Apr 28, 2021 |
| Dell          | Inspiron 1525               | [cc25ad321c](https://linux-hardware.org/?probe=cc25ad321c) | Apr 25, 2021 |
| Dell          | Inspiron 1525               | [556597aee7](https://linux-hardware.org/?probe=556597aee7) | Apr 25, 2021 |
| ASUSTek       | X541NA                      | [8db0f5c7ac](https://linux-hardware.org/?probe=8db0f5c7ac) | Apr 24, 2021 |
| HP            | EliteBook 8470p             | [a7b2495ff3](https://linux-hardware.org/?probe=a7b2495ff3) | Apr 24, 2021 |
| ASUSTek       | K52F                        | [15a47f7878](https://linux-hardware.org/?probe=15a47f7878) | Apr 23, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [62a9d02812](https://linux-hardware.org/?probe=62a9d02812) | Apr 23, 2021 |
| HP            | Laptop 14s-dq1xxx           | [5dc2c58da2](https://linux-hardware.org/?probe=5dc2c58da2) | Apr 23, 2021 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | [284bb4ca17](https://linux-hardware.org/?probe=284bb4ca17) | Apr 23, 2021 |
| Lenovo        | ThinkPad T61 6458Y56        | [7ce9f79723](https://linux-hardware.org/?probe=7ce9f79723) | Apr 23, 2021 |
| Lenovo        | G550 20023                  | [5ef8b1f387](https://linux-hardware.org/?probe=5ef8b1f387) | Apr 23, 2021 |
| Lenovo        | ThinkPad T61 6458Y56        | [13d048c774](https://linux-hardware.org/?probe=13d048c774) | Apr 23, 2021 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | [8508d7af0d](https://linux-hardware.org/?probe=8508d7af0d) | Apr 22, 2021 |
| HP            | Pavilion 15                 | [87a58b7ab7](https://linux-hardware.org/?probe=87a58b7ab7) | Apr 22, 2021 |
| HP            | Pavilion 15                 | [65e4923f35](https://linux-hardware.org/?probe=65e4923f35) | Apr 22, 2021 |
| HP            | 255 G2                      | [338785dab3](https://linux-hardware.org/?probe=338785dab3) | Apr 22, 2021 |
| Dell          | Inspiron 1501               | [0d9873f612](https://linux-hardware.org/?probe=0d9873f612) | Apr 22, 2021 |
| Dell          | Inspiron 1501               | [c65615941e](https://linux-hardware.org/?probe=c65615941e) | Apr 22, 2021 |
| Toshiba       | Satellite C650              | [e030b89f2e](https://linux-hardware.org/?probe=e030b89f2e) | Apr 20, 2021 |
| HP            | 250 G1                      | [5cd293482f](https://linux-hardware.org/?probe=5cd293482f) | Apr 20, 2021 |
| HP            | 250 G1                      | [78f5d2ed14](https://linux-hardware.org/?probe=78f5d2ed14) | Apr 20, 2021 |
| Dell          | Inspiron N5010              | [c500bd2809](https://linux-hardware.org/?probe=c500bd2809) | Apr 19, 2021 |
| Lenovo        | G580 20150                  | [a48e280881](https://linux-hardware.org/?probe=a48e280881) | Apr 19, 2021 |
| Toshiba       | Satellite C650              | [49fd3f9b56](https://linux-hardware.org/?probe=49fd3f9b56) | Apr 19, 2021 |
| Toshiba       | Satellite C650              | [e3b0f7e80b](https://linux-hardware.org/?probe=e3b0f7e80b) | Apr 19, 2021 |
| Dell          | XPS 15 9570                 | [69ab37b6a8](https://linux-hardware.org/?probe=69ab37b6a8) | Apr 19, 2021 |
| Acer          | Aspire E5-772G              | [f391112497](https://linux-hardware.org/?probe=f391112497) | Apr 18, 2021 |
| Acer          | Aspire E5-772G              | [b0de5e017d](https://linux-hardware.org/?probe=b0de5e017d) | Apr 18, 2021 |
| HP            | EliteBook 2530p             | [a5594a75d1](https://linux-hardware.org/?probe=a5594a75d1) | Apr 18, 2021 |
| Lenovo        | V145-15AST 81MT             | [5e4713eb5b](https://linux-hardware.org/?probe=5e4713eb5b) | Apr 18, 2021 |
| HP            | EliteBook 2560p             | [c75019619f](https://linux-hardware.org/?probe=c75019619f) | Apr 17, 2021 |
| HP            | Pavilion 15                 | [62c864ead5](https://linux-hardware.org/?probe=62c864ead5) | Apr 17, 2021 |
| Acer          | Aspire V5-132P              | [ee640eb5c2](https://linux-hardware.org/?probe=ee640eb5c2) | Apr 17, 2021 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [0e0ef35397](https://linux-hardware.org/?probe=0e0ef35397) | Apr 17, 2021 |
| Dell          | Vostro 1015                 | [c55f3ca871](https://linux-hardware.org/?probe=c55f3ca871) | Apr 17, 2021 |
| Dell          | Latitude E6530              | [5fa024e64f](https://linux-hardware.org/?probe=5fa024e64f) | Apr 17, 2021 |
| Dell          | Latitude E6530              | [f395388089](https://linux-hardware.org/?probe=f395388089) | Apr 17, 2021 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | [5235d38647](https://linux-hardware.org/?probe=5235d38647) | Apr 17, 2021 |
| Lenovo        | ThinkPad T480 20L50056HV    | [db1bb2da24](https://linux-hardware.org/?probe=db1bb2da24) | Apr 17, 2021 |
| ASUSTek       | K50AB                       | [1f686c8c38](https://linux-hardware.org/?probe=1f686c8c38) | Apr 16, 2021 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [0e860ee7ba](https://linux-hardware.org/?probe=0e860ee7ba) | Apr 16, 2021 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | [796ff42739](https://linux-hardware.org/?probe=796ff42739) | Apr 16, 2021 |
| Acer          | Aspire ES1-131              | [5e36e69b21](https://linux-hardware.org/?probe=5e36e69b21) | Apr 15, 2021 |
| HP            | ProBook 6570b               | [9f433657f2](https://linux-hardware.org/?probe=9f433657f2) | Apr 15, 2021 |
| HP            | ProBook 6570b               | [bbfe232b00](https://linux-hardware.org/?probe=bbfe232b00) | Apr 15, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [ebab7a1a23](https://linux-hardware.org/?probe=ebab7a1a23) | Apr 15, 2021 |
| Lenovo        | IdeaPadFlex 3 11IGL05 82... | [eda2fbc232](https://linux-hardware.org/?probe=eda2fbc232) | Apr 14, 2021 |
| Lenovo        | IdeaPadFlex 3 11IGL05 82... | [973dc69b2c](https://linux-hardware.org/?probe=973dc69b2c) | Apr 14, 2021 |
| ASUSTek       | TP201SA                     | [e45685044d](https://linux-hardware.org/?probe=e45685044d) | Apr 14, 2021 |
| Dell          | Inspiron 3521               | [2c86cb6a03](https://linux-hardware.org/?probe=2c86cb6a03) | Apr 13, 2021 |
| Lenovo        | ThinkPad T400 64741EG       | [eb9c8a25e2](https://linux-hardware.org/?probe=eb9c8a25e2) | Apr 13, 2021 |
| Lenovo        | ThinkPad T400 64741EG       | [b16c5440aa](https://linux-hardware.org/?probe=b16c5440aa) | Apr 13, 2021 |
| Acer          | Swift SF114-32              | [0c564de83b](https://linux-hardware.org/?probe=0c564de83b) | Apr 12, 2021 |
| Acer          | Swift SF114-32              | [da518dee74](https://linux-hardware.org/?probe=da518dee74) | Apr 12, 2021 |
| Hungaro Fl... | Navon Loop 360              | [ca1ee467c1](https://linux-hardware.org/?probe=ca1ee467c1) | Apr 12, 2021 |
| Dell          | Inspiron 5584               | [81e060632a](https://linux-hardware.org/?probe=81e060632a) | Apr 11, 2021 |
| MSI           | EX620                       | [2641fba144](https://linux-hardware.org/?probe=2641fba144) | Apr 11, 2021 |
| MSI           | EX620                       | [60bcfde431](https://linux-hardware.org/?probe=60bcfde431) | Apr 11, 2021 |
| Dell          | Latitude 7280               | [7f4ef4bf0e](https://linux-hardware.org/?probe=7f4ef4bf0e) | Apr 10, 2021 |
| eMachines     | E525                        | [01be9fdecb](https://linux-hardware.org/?probe=01be9fdecb) | Apr 10, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [61f1bc3a08](https://linux-hardware.org/?probe=61f1bc3a08) | Apr 10, 2021 |
| Alcor         | Flashbook D1423I            | [7497df766d](https://linux-hardware.org/?probe=7497df766d) | Apr 10, 2021 |
| Alcor         | Flashbook D1423I            | [c6e457061a](https://linux-hardware.org/?probe=c6e457061a) | Apr 10, 2021 |
| ASUSTek       | TP201SA                     | [0feaa30009](https://linux-hardware.org/?probe=0feaa30009) | Apr 10, 2021 |
| Acer          | Nitro AN515-42              | [4c7acbbbc1](https://linux-hardware.org/?probe=4c7acbbbc1) | Apr 10, 2021 |
| Dell          | Latitude E6330              | [193e9dcf84](https://linux-hardware.org/?probe=193e9dcf84) | Apr 09, 2021 |
| HP            | EliteBook 8470p             | [ad6b18f63a](https://linux-hardware.org/?probe=ad6b18f63a) | Apr 09, 2021 |
| Dell          | Inspiron 5584               | [40e72b232a](https://linux-hardware.org/?probe=40e72b232a) | Apr 08, 2021 |
| HP            | 250 G1                      | [e96e21eb4c](https://linux-hardware.org/?probe=e96e21eb4c) | Apr 08, 2021 |
| HP            | Compaq 6710b (KE121EA#AK... | [0c96e91853](https://linux-hardware.org/?probe=0c96e91853) | Apr 08, 2021 |
| Acer          | Extensa 5635Z               | [815083f947](https://linux-hardware.org/?probe=815083f947) | Apr 08, 2021 |
| Acer          | Extensa 5635Z               | [8633c9d7b3](https://linux-hardware.org/?probe=8633c9d7b3) | Apr 08, 2021 |
| Dell          | Inspiron 3537               | [0e0f0105eb](https://linux-hardware.org/?probe=0e0f0105eb) | Apr 08, 2021 |
| Acer          | Aspire E5-572G              | [17042db699](https://linux-hardware.org/?probe=17042db699) | Apr 08, 2021 |
| Dell          | Latitude 5511               | [7f176658f8](https://linux-hardware.org/?probe=7f176658f8) | Apr 07, 2021 |
| HP            | ProBook 4720s               | [02e147cc86](https://linux-hardware.org/?probe=02e147cc86) | Apr 06, 2021 |
| Lenovo        | G550 20023                  | [a96062e31f](https://linux-hardware.org/?probe=a96062e31f) | Apr 06, 2021 |
| HP            | 650                         | [1ce32ec6d8](https://linux-hardware.org/?probe=1ce32ec6d8) | Apr 06, 2021 |
| Dell          | Inspiron 5584               | [f51c8134ea](https://linux-hardware.org/?probe=f51c8134ea) | Apr 05, 2021 |
| Lenovo        | ThinkPad T420 4236S3T       | [37f63d4dce](https://linux-hardware.org/?probe=37f63d4dce) | Apr 05, 2021 |
| HP            | 650                         | [c89c9113ad](https://linux-hardware.org/?probe=c89c9113ad) | Apr 04, 2021 |
| ASUSTek       | K53TA                       | [e6a17619d6](https://linux-hardware.org/?probe=e6a17619d6) | Apr 04, 2021 |
| Acer          | Aspire 7738                 | [d08e3b9cc7](https://linux-hardware.org/?probe=d08e3b9cc7) | Apr 03, 2021 |
| Toshiba       | NB550D                      | [913cfa6e46](https://linux-hardware.org/?probe=913cfa6e46) | Apr 03, 2021 |
| Acer          | Aspire F5-573G              | [da8838647c](https://linux-hardware.org/?probe=da8838647c) | Apr 03, 2021 |
| ASUSTek       | K53SJ                       | [c161a80f4d](https://linux-hardware.org/?probe=c161a80f4d) | Apr 03, 2021 |
| ASUSTek       | X541UAK                     | [b3c4cbf5d1](https://linux-hardware.org/?probe=b3c4cbf5d1) | Apr 03, 2021 |
| HP            | ProBook 6470b               | [09b18a9fc4](https://linux-hardware.org/?probe=09b18a9fc4) | Apr 02, 2021 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [9834fa97d4](https://linux-hardware.org/?probe=9834fa97d4) | Apr 02, 2021 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [0f579a986d](https://linux-hardware.org/?probe=0f579a986d) | Apr 02, 2021 |
| Lenovo        | ThinkPad X201 3626F9G       | [6205c1bc53](https://linux-hardware.org/?probe=6205c1bc53) | Apr 02, 2021 |
| Lenovo        | ThinkPad X201 3626F9G       | [be1072da12](https://linux-hardware.org/?probe=be1072da12) | Apr 02, 2021 |
| Dell          | Latitude E5270              | [8ceffb35da](https://linux-hardware.org/?probe=8ceffb35da) | Apr 01, 2021 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [1dd356e401](https://linux-hardware.org/?probe=1dd356e401) | Apr 01, 2021 |
| HP            | ProBook 6570b               | [eab5d4cdab](https://linux-hardware.org/?probe=eab5d4cdab) | Mar 31, 2021 |
| ASUSTek       | K54C                        | [d732f562ae](https://linux-hardware.org/?probe=d732f562ae) | Mar 31, 2021 |
| Lenovo        | ThinkPad W510 431924G       | [f07c1c58d4](https://linux-hardware.org/?probe=f07c1c58d4) | Mar 31, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [c8fd3965d2](https://linux-hardware.org/?probe=c8fd3965d2) | Mar 29, 2021 |
| Lenovo        | G550 20023                  | [4b5d7dc64b](https://linux-hardware.org/?probe=4b5d7dc64b) | Mar 29, 2021 |
| HP            | 250 G1                      | [f29918fb28](https://linux-hardware.org/?probe=f29918fb28) | Mar 29, 2021 |
| HP            | EliteBook 8540p             | [1ad126d1ca](https://linux-hardware.org/?probe=1ad126d1ca) | Mar 28, 2021 |
| HP            | EliteBook 8540p             | [76e68d794d](https://linux-hardware.org/?probe=76e68d794d) | Mar 28, 2021 |
| Fujitsu       | LIFEBOOK E5510              | [2c6074e5d3](https://linux-hardware.org/?probe=2c6074e5d3) | Mar 28, 2021 |
| Fujitsu       | LIFEBOOK E5510              | [ee1abc0012](https://linux-hardware.org/?probe=ee1abc0012) | Mar 28, 2021 |
| Acer          | Aspire V5-122P              | [f41eab205a](https://linux-hardware.org/?probe=f41eab205a) | Mar 27, 2021 |
| Acer          | Aspire V5-122P              | [be5f930563](https://linux-hardware.org/?probe=be5f930563) | Mar 27, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [dc78493d04](https://linux-hardware.org/?probe=dc78493d04) | Mar 27, 2021 |
| Toshiba       | Satellite C50-A-14G         | [42a4e083a7](https://linux-hardware.org/?probe=42a4e083a7) | Mar 27, 2021 |
| Acer          | Aspire 5310                 | [72e13cd94b](https://linux-hardware.org/?probe=72e13cd94b) | Mar 26, 2021 |
| Dell          | Inspiron 1440               | [64dba061ca](https://linux-hardware.org/?probe=64dba061ca) | Mar 26, 2021 |
| ASUSTek       | X541UAK                     | [fb156f123e](https://linux-hardware.org/?probe=fb156f123e) | Mar 26, 2021 |
| ASUSTek       | X541UAK                     | [8f800ab93f](https://linux-hardware.org/?probe=8f800ab93f) | Mar 26, 2021 |
| Acer          | Aspire ES1-531              | [4379311707](https://linux-hardware.org/?probe=4379311707) | Mar 26, 2021 |
| ASUSTek       | 1011PX                      | [3d23090e46](https://linux-hardware.org/?probe=3d23090e46) | Mar 26, 2021 |
| Toshiba       | Satellite C650              | [8ef9a1bb0d](https://linux-hardware.org/?probe=8ef9a1bb0d) | Mar 25, 2021 |
| Medion        | Akoya E1317T                | [5b9f33d75d](https://linux-hardware.org/?probe=5b9f33d75d) | Mar 25, 2021 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [f4f55b8315](https://linux-hardware.org/?probe=f4f55b8315) | Mar 25, 2021 |
| ASUSTek       | GL752VW                     | [b5571f477a](https://linux-hardware.org/?probe=b5571f477a) | Mar 25, 2021 |
| HP            | 250 G1                      | [571c5e86ca](https://linux-hardware.org/?probe=571c5e86ca) | Mar 25, 2021 |
| Lenovo        | ThinkPad X201 Tablet 323... | [6d77d65333](https://linux-hardware.org/?probe=6d77d65333) | Mar 25, 2021 |
| Lenovo        | V330-15IKB 81AX             | [54c3c0f350](https://linux-hardware.org/?probe=54c3c0f350) | Mar 24, 2021 |
| MSI           | GP72 2QE                    | [b2f358b988](https://linux-hardware.org/?probe=b2f358b988) | Mar 24, 2021 |
| MSI           | GP72 2QE                    | [5ad697075a](https://linux-hardware.org/?probe=5ad697075a) | Mar 24, 2021 |
| HP            | 250 G1                      | [31152f4a4d](https://linux-hardware.org/?probe=31152f4a4d) | Mar 24, 2021 |
| HP            | 250 G1                      | [c86932b151](https://linux-hardware.org/?probe=c86932b151) | Mar 24, 2021 |
| ASUSTek       | K53U                        | [098cd60d2e](https://linux-hardware.org/?probe=098cd60d2e) | Mar 23, 2021 |
| ASUSTek       | K53U                        | [d681adcc3d](https://linux-hardware.org/?probe=d681adcc3d) | Mar 23, 2021 |
| HP            | 250 G1                      | [bb19807dca](https://linux-hardware.org/?probe=bb19807dca) | Mar 23, 2021 |
| ASUSTek       | X540YA                      | [0a72e96074](https://linux-hardware.org/?probe=0a72e96074) | Mar 23, 2021 |
| Acer          | TravelMate 4230             | [b658db9732](https://linux-hardware.org/?probe=b658db9732) | Mar 23, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [6c53e53a64](https://linux-hardware.org/?probe=6c53e53a64) | Mar 23, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [c4854dcae9](https://linux-hardware.org/?probe=c4854dcae9) | Mar 23, 2021 |
| Toshiba       | Satellite L300              | [7eb9b157fc](https://linux-hardware.org/?probe=7eb9b157fc) | Mar 23, 2021 |
| Lenovo        | ThinkPad T400 6475VZZ       | [4c690bf6d0](https://linux-hardware.org/?probe=4c690bf6d0) | Mar 22, 2021 |
| Lenovo        | ThinkPad T400 6475VZZ       | [cfa452546d](https://linux-hardware.org/?probe=cfa452546d) | Mar 22, 2021 |
| HP            | 250 G1                      | [33687fcd77](https://linux-hardware.org/?probe=33687fcd77) | Mar 22, 2021 |
| Packard Be... | EasyNote TS44HR             | [5602ef0a89](https://linux-hardware.org/?probe=5602ef0a89) | Mar 22, 2021 |
| Lenovo        | G550 20023                  | [f5b02bf2e3](https://linux-hardware.org/?probe=f5b02bf2e3) | Mar 22, 2021 |
| Packard Be... | EasyNote TS44HR             | [bc1ed5af2c](https://linux-hardware.org/?probe=bc1ed5af2c) | Mar 22, 2021 |
| HP            | 250 G1                      | [6c53653092](https://linux-hardware.org/?probe=6c53653092) | Mar 22, 2021 |
| Acer          | Aspire 5738                 | [f5dc1b6871](https://linux-hardware.org/?probe=f5dc1b6871) | Mar 21, 2021 |
| ASUSTek       | X540YA                      | [998e4d57a2](https://linux-hardware.org/?probe=998e4d57a2) | Mar 21, 2021 |
| HP            | 250 G4                      | [f758afe9ec](https://linux-hardware.org/?probe=f758afe9ec) | Mar 21, 2021 |
| Dell          | Latitude E6320              | [aff5d25f77](https://linux-hardware.org/?probe=aff5d25f77) | Mar 21, 2021 |
| HP            | 250 G4                      | [434c23e406](https://linux-hardware.org/?probe=434c23e406) | Mar 21, 2021 |
| ASUSTek       | X51RL                       | [0451b6db0a](https://linux-hardware.org/?probe=0451b6db0a) | Mar 21, 2021 |
| Fujitsu Si... | AMILO Pro Edition V3505     | [37d02ad16c](https://linux-hardware.org/?probe=37d02ad16c) | Mar 21, 2021 |
| ASUSTek       | GL752VW                     | [1164af9892](https://linux-hardware.org/?probe=1164af9892) | Mar 20, 2021 |
| ASUSTek       | F5R                         | [e575c47a9f](https://linux-hardware.org/?probe=e575c47a9f) | Mar 20, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [fe0b110232](https://linux-hardware.org/?probe=fe0b110232) | Mar 20, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [e5c0bd65b4](https://linux-hardware.org/?probe=e5c0bd65b4) | Mar 20, 2021 |
| HP            | ProBook 430 G6              | [29ef42ccfc](https://linux-hardware.org/?probe=29ef42ccfc) | Mar 20, 2021 |
| HP            | Notebook                    | [1f1f1e9b8e](https://linux-hardware.org/?probe=1f1f1e9b8e) | Mar 19, 2021 |
| HP            | Notebook                    | [424c6ac58f](https://linux-hardware.org/?probe=424c6ac58f) | Mar 18, 2021 |
| Acer          | TravelMate B113             | [f93ee2f87d](https://linux-hardware.org/?probe=f93ee2f87d) | Mar 18, 2021 |
| ASUSTek       | Strix GL703GS_GL703GS       | [13d4c8dbbb](https://linux-hardware.org/?probe=13d4c8dbbb) | Mar 18, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0dd7142c8f](https://linux-hardware.org/?probe=0dd7142c8f) | Mar 18, 2021 |
| Medion        | Akoya E1317T                | [cdf507be57](https://linux-hardware.org/?probe=cdf507be57) | Mar 18, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [66520b695a](https://linux-hardware.org/?probe=66520b695a) | Mar 18, 2021 |
| Alcor         | Intel Education Tablet      | [eb20639ea8](https://linux-hardware.org/?probe=eb20639ea8) | Mar 17, 2021 |
| Medion        | Akoya E1317T                | [2799502802](https://linux-hardware.org/?probe=2799502802) | Mar 17, 2021 |
| Medion        | Akoya E1317T                | [0ba7cb99d4](https://linux-hardware.org/?probe=0ba7cb99d4) | Mar 17, 2021 |
| Acer          | Aspire 5720Z                | [3c8537dfe3](https://linux-hardware.org/?probe=3c8537dfe3) | Mar 16, 2021 |
| Acer          | Aspire 5720Z                | [51abe2f5bb](https://linux-hardware.org/?probe=51abe2f5bb) | Mar 16, 2021 |
| HP            | 250 G1                      | [23738f1488](https://linux-hardware.org/?probe=23738f1488) | Mar 16, 2021 |
| HP            | 250 G1                      | [127e667f59](https://linux-hardware.org/?probe=127e667f59) | Mar 16, 2021 |
| Lenovo        | ThinkPad T61 6458WK6        | [36086458e0](https://linux-hardware.org/?probe=36086458e0) | Mar 15, 2021 |
| Acer          | TravelMate P215-52          | [fac5349431](https://linux-hardware.org/?probe=fac5349431) | Mar 14, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [8bc72609a6](https://linux-hardware.org/?probe=8bc72609a6) | Mar 14, 2021 |
| Dell          | Latitude E5420              | [41bacbb72f](https://linux-hardware.org/?probe=41bacbb72f) | Mar 14, 2021 |
| Acer          | TravelMate P215-52          | [4e72aff862](https://linux-hardware.org/?probe=4e72aff862) | Mar 14, 2021 |
| A15HV01       | Unknown                     | [b35e7ae1ba](https://linux-hardware.org/?probe=b35e7ae1ba) | Mar 14, 2021 |
| A15HV01       | Unknown                     | [a89e4e3b11](https://linux-hardware.org/?probe=a89e4e3b11) | Mar 14, 2021 |
| Dell          | BNPPE5400___1_              | [80afc315b0](https://linux-hardware.org/?probe=80afc315b0) | Mar 14, 2021 |
| Dell          | BNPPE5400___1_              | [29efe45c73](https://linux-hardware.org/?probe=29efe45c73) | Mar 14, 2021 |
| Unknown       | Unknown                     | [0ca3544164](https://linux-hardware.org/?probe=0ca3544164) | Mar 14, 2021 |
| Unknown       | Unknown                     | [452c065e24](https://linux-hardware.org/?probe=452c065e24) | Mar 14, 2021 |
| Acer          | AOHAPPY                     | [2b59c324e6](https://linux-hardware.org/?probe=2b59c324e6) | Mar 14, 2021 |
| Lenovo        | G50-45 80E3                 | [34a9e811c9](https://linux-hardware.org/?probe=34a9e811c9) | Mar 14, 2021 |
| Toshiba       | Satellite A300              | [e1148ec276](https://linux-hardware.org/?probe=e1148ec276) | Mar 14, 2021 |
| Lenovo        | G50-45 80E3                 | [740b1749cb](https://linux-hardware.org/?probe=740b1749cb) | Mar 14, 2021 |
| Dell          | Inspiron 5737               | [34f67ab4f3](https://linux-hardware.org/?probe=34f67ab4f3) | Mar 13, 2021 |
| Dell          | Inspiron 5737               | [399a4677b9](https://linux-hardware.org/?probe=399a4677b9) | Mar 13, 2021 |
| Lenovo        | ThinkPad W510 4876A46       | [87e9190663](https://linux-hardware.org/?probe=87e9190663) | Mar 12, 2021 |
| Lenovo        | V15-ADA 82C7                | [395af60d19](https://linux-hardware.org/?probe=395af60d19) | Mar 12, 2021 |
| Dell          | Latitude D630               | [3db6fef5ae](https://linux-hardware.org/?probe=3db6fef5ae) | Mar 12, 2021 |
| Apple         | MacBook9,1                  | [1bbd86f09c](https://linux-hardware.org/?probe=1bbd86f09c) | Mar 12, 2021 |
| Dell          | Latitude E6330              | [1860c44201](https://linux-hardware.org/?probe=1860c44201) | Mar 12, 2021 |
| Dell          | Latitude E6320              | [9b5ab0b208](https://linux-hardware.org/?probe=9b5ab0b208) | Mar 11, 2021 |
| Dell          | Latitude E6320              | [e2d83357e4](https://linux-hardware.org/?probe=e2d83357e4) | Mar 11, 2021 |
| HP            | 250 G1                      | [fbec2919a3](https://linux-hardware.org/?probe=fbec2919a3) | Mar 11, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [090f2f9923](https://linux-hardware.org/?probe=090f2f9923) | Mar 11, 2021 |
| HP            | Notebook                    | [1f562e80a0](https://linux-hardware.org/?probe=1f562e80a0) | Mar 11, 2021 |
| HP            | Notebook                    | [211d3dd45c](https://linux-hardware.org/?probe=211d3dd45c) | Mar 11, 2021 |
| Dell          | Latitude E5440              | [c189f8d7d1](https://linux-hardware.org/?probe=c189f8d7d1) | Mar 10, 2021 |
| Dell          | Latitude E6420              | [00313f1a80](https://linux-hardware.org/?probe=00313f1a80) | Mar 10, 2021 |
| Dell          | Latitude E6420              | [10ed3d6907](https://linux-hardware.org/?probe=10ed3d6907) | Mar 10, 2021 |
| Dell          | Latitude E6320              | [87984c523d](https://linux-hardware.org/?probe=87984c523d) | Mar 10, 2021 |
| Lenovo        | ThinkPad X100e 287627G      | [3f010214d1](https://linux-hardware.org/?probe=3f010214d1) | Mar 10, 2021 |
| Lenovo        | ThinkPad X100e 287627G      | [0f9f81dbf1](https://linux-hardware.org/?probe=0f9f81dbf1) | Mar 10, 2021 |
| Dell          | Latitude E6530              | [0b6a7cb2c2](https://linux-hardware.org/?probe=0b6a7cb2c2) | Mar 10, 2021 |
| Dell          | Inspiron MM061              | [5f7050ed78](https://linux-hardware.org/?probe=5f7050ed78) | Mar 09, 2021 |
| Dell          | Inspiron MM061              | [cf40d9e104](https://linux-hardware.org/?probe=cf40d9e104) | Mar 09, 2021 |
| ASUSTek       | X540SA                      | [3be46fe93c](https://linux-hardware.org/?probe=3be46fe93c) | Mar 09, 2021 |
| ASUSTek       | X540SA                      | [4a86730d8a](https://linux-hardware.org/?probe=4a86730d8a) | Mar 09, 2021 |
| eMachines     | E525                        | [ee09927df0](https://linux-hardware.org/?probe=ee09927df0) | Mar 09, 2021 |
| HP            | EliteBook 8540p             | [3741826c9a](https://linux-hardware.org/?probe=3741826c9a) | Mar 08, 2021 |
| Lenovo        | E50-80 80J2                 | [308df9bec1](https://linux-hardware.org/?probe=308df9bec1) | Mar 08, 2021 |
| Lenovo        | E50-80 80J2                 | [f7974a4b31](https://linux-hardware.org/?probe=f7974a4b31) | Mar 08, 2021 |
| Dell          | Precision M4800             | [940b78b4e6](https://linux-hardware.org/?probe=940b78b4e6) | Mar 08, 2021 |
| Dell          | Latitude 5491               | [ccb1badf86](https://linux-hardware.org/?probe=ccb1badf86) | Mar 08, 2021 |
| HP            | EliteBook 820 G2            | [ccb914b0e4](https://linux-hardware.org/?probe=ccb914b0e4) | Mar 08, 2021 |
| HP            | EliteBook 840 G6            | [e6dd893b74](https://linux-hardware.org/?probe=e6dd893b74) | Mar 07, 2021 |
| ASUSTek       | GL752VW                     | [dd7392cb01](https://linux-hardware.org/?probe=dd7392cb01) | Mar 07, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [756d77e26f](https://linux-hardware.org/?probe=756d77e26f) | Mar 07, 2021 |
| HP            | EliteBook 820 G1            | [c666b27cd2](https://linux-hardware.org/?probe=c666b27cd2) | Mar 07, 2021 |
| HP            | EliteBook 820 G1            | [01f12453af](https://linux-hardware.org/?probe=01f12453af) | Mar 07, 2021 |
| Sony          | SVF1521B1EW                 | [a8a79ee4e9](https://linux-hardware.org/?probe=a8a79ee4e9) | Mar 07, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [626e4300f4](https://linux-hardware.org/?probe=626e4300f4) | Mar 07, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [a5cd163b82](https://linux-hardware.org/?probe=a5cd163b82) | Mar 07, 2021 |
| ASUSTek       | GL752VW                     | [196293bb97](https://linux-hardware.org/?probe=196293bb97) | Mar 07, 2021 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | [f7fc7ae3ae](https://linux-hardware.org/?probe=f7fc7ae3ae) | Mar 06, 2021 |
| Dell          | Inspiron 3584               | [20d71b7b1f](https://linux-hardware.org/?probe=20d71b7b1f) | Mar 05, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [80284f83dd](https://linux-hardware.org/?probe=80284f83dd) | Mar 05, 2021 |
| Acer          | Aspire 5755G                | [acc7434851](https://linux-hardware.org/?probe=acc7434851) | Mar 05, 2021 |
| Acer          | Aspire 5755G                | [6a759c27c3](https://linux-hardware.org/?probe=6a759c27c3) | Mar 05, 2021 |
| Dell          | Latitude D630               | [90ccb71f49](https://linux-hardware.org/?probe=90ccb71f49) | Mar 05, 2021 |
| Dell          | Latitude E6220              | [d0b6c97a41](https://linux-hardware.org/?probe=d0b6c97a41) | Mar 05, 2021 |
| Acer          | Aspire one                  | [0b7b2c2717](https://linux-hardware.org/?probe=0b7b2c2717) | Mar 05, 2021 |
| ASUSTek       | X550CC                      | [d9d0226043](https://linux-hardware.org/?probe=d9d0226043) | Mar 04, 2021 |
| ASUSTek       | X550CC                      | [3f8aa76720](https://linux-hardware.org/?probe=3f8aa76720) | Mar 04, 2021 |
| Lenovo        | ThinkPad W510 4876A46       | [5a37c63d6b](https://linux-hardware.org/?probe=5a37c63d6b) | Mar 03, 2021 |
| HP            | EliteBook 8460p             | [e02da0932b](https://linux-hardware.org/?probe=e02da0932b) | Mar 03, 2021 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [0dec6a51ae](https://linux-hardware.org/?probe=0dec6a51ae) | Mar 03, 2021 |
| HP            | EliteBook 6930p             | [5399ac86cd](https://linux-hardware.org/?probe=5399ac86cd) | Mar 03, 2021 |
| Acer          | Aspire F5-572G              | [1524ce2771](https://linux-hardware.org/?probe=1524ce2771) | Mar 03, 2021 |
| Acer          | Aspire F5-572G              | [9f22ceac3b](https://linux-hardware.org/?probe=9f22ceac3b) | Mar 03, 2021 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [42d9585ddc](https://linux-hardware.org/?probe=42d9585ddc) | Mar 03, 2021 |
| HP            | EliteBook 840 G6            | [2ab0bd9796](https://linux-hardware.org/?probe=2ab0bd9796) | Mar 02, 2021 |
| ASUSTek       | F83Se                       | [55ff60b946](https://linux-hardware.org/?probe=55ff60b946) | Mar 02, 2021 |
| HP            | Notebook                    | [2c72d2b104](https://linux-hardware.org/?probe=2c72d2b104) | Mar 02, 2021 |
| HP            | Notebook                    | [3b38a5f774](https://linux-hardware.org/?probe=3b38a5f774) | Mar 02, 2021 |
| HP            | EliteBook 8460p             | [7600790edf](https://linux-hardware.org/?probe=7600790edf) | Mar 02, 2021 |
| Lenovo        | 3000 N100 0768BNG           | [107a372549](https://linux-hardware.org/?probe=107a372549) | Mar 02, 2021 |
| HP            | 250 G1                      | [9ab9fe3df3](https://linux-hardware.org/?probe=9ab9fe3df3) | Mar 02, 2021 |
| Lenovo        | 3000 N100 0768BNG           | [1948693afe](https://linux-hardware.org/?probe=1948693afe) | Mar 02, 2021 |
| HP            | 250 G1                      | [c9e270c528](https://linux-hardware.org/?probe=c9e270c528) | Mar 02, 2021 |
| Dell          | Latitude E5540              | [dd7e5ca24d](https://linux-hardware.org/?probe=dd7e5ca24d) | Mar 02, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [20f1346601](https://linux-hardware.org/?probe=20f1346601) | Mar 01, 2021 |
| HP            | EliteBook 2540p             | [8112c59573](https://linux-hardware.org/?probe=8112c59573) | Mar 01, 2021 |
| HP            | EliteBook 2540p             | [f07d7ca74a](https://linux-hardware.org/?probe=f07d7ca74a) | Mar 01, 2021 |
| Packard Be... | EasyNote TK36               | [bb7ca88e4f](https://linux-hardware.org/?probe=bb7ca88e4f) | Mar 01, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [9c9f262fa8](https://linux-hardware.org/?probe=9c9f262fa8) | Mar 01, 2021 |
| HP            | Compaq 6710b (GB890EA#AK... | [4ca9714ef8](https://linux-hardware.org/?probe=4ca9714ef8) | Mar 01, 2021 |
| ASUSTek       | T300FA                      | [83760cad91](https://linux-hardware.org/?probe=83760cad91) | Feb 28, 2021 |
| Dell          | XPS 15 9570                 | [2e10422608](https://linux-hardware.org/?probe=2e10422608) | Feb 28, 2021 |
| Lenovo        | G585 20137                  | [b7804f3c41](https://linux-hardware.org/?probe=b7804f3c41) | Feb 28, 2021 |
| Lenovo        | G585 20137                  | [b0e869ae8d](https://linux-hardware.org/?probe=b0e869ae8d) | Feb 28, 2021 |
| HP            | ProBook 6570b               | [0e8689327d](https://linux-hardware.org/?probe=0e8689327d) | Feb 28, 2021 |
| Acer          | Aspire 5738                 | [cc0c3a8b65](https://linux-hardware.org/?probe=cc0c3a8b65) | Feb 28, 2021 |
| Acer          | Aspire 5738                 | [43f9d43867](https://linux-hardware.org/?probe=43f9d43867) | Feb 28, 2021 |
| Lenovo        | Y520-15IKBA 80WY            | [3c30cf3fc2](https://linux-hardware.org/?probe=3c30cf3fc2) | Feb 28, 2021 |
| ASUSTek       | K54C                        | [14005a55c9](https://linux-hardware.org/?probe=14005a55c9) | Feb 28, 2021 |
| Lenovo        | Y520-15IKBA 80WY            | [b330cba09d](https://linux-hardware.org/?probe=b330cba09d) | Feb 28, 2021 |
| Toshiba       | Satellite L300              | [97a2208e46](https://linux-hardware.org/?probe=97a2208e46) | Feb 28, 2021 |
| Toshiba       | Satellite L300              | [1d638916dd](https://linux-hardware.org/?probe=1d638916dd) | Feb 27, 2021 |
| Dell          | Latitude E7240              | [d5e3143971](https://linux-hardware.org/?probe=d5e3143971) | Feb 27, 2021 |
| Dell          | Latitude E7240              | [f136a8d103](https://linux-hardware.org/?probe=f136a8d103) | Feb 27, 2021 |
| HP            | Compaq 610                  | [b5b8949ca0](https://linux-hardware.org/?probe=b5b8949ca0) | Feb 27, 2021 |
| Fujitsu       | LIFEBOOK E744               | [faf8adc597](https://linux-hardware.org/?probe=faf8adc597) | Feb 27, 2021 |
| Dell          | G3 3579                     | [1f810bb2a2](https://linux-hardware.org/?probe=1f810bb2a2) | Feb 27, 2021 |
| HP            | ProBook 6450b               | [f1609d8f61](https://linux-hardware.org/?probe=f1609d8f61) | Feb 27, 2021 |
| HP            | ProBook 6450b               | [0529572419](https://linux-hardware.org/?probe=0529572419) | Feb 27, 2021 |
| Dell          | XPS 15 9570                 | [15192814e5](https://linux-hardware.org/?probe=15192814e5) | Feb 27, 2021 |
| ASUSTek       | K50AB                       | [846d821461](https://linux-hardware.org/?probe=846d821461) | Feb 27, 2021 |
| ASUSTek       | K50AB                       | [b61301dfd6](https://linux-hardware.org/?probe=b61301dfd6) | Feb 27, 2021 |
| HP            | EliteBook 2560p             | [fcb94e721c](https://linux-hardware.org/?probe=fcb94e721c) | Feb 27, 2021 |
| Acer          | Aspire E5-411               | [04bfc6df09](https://linux-hardware.org/?probe=04bfc6df09) | Feb 27, 2021 |
| Packard Be... | EasyNote TE11HC             | [d3328777ce](https://linux-hardware.org/?probe=d3328777ce) | Feb 26, 2021 |
| Acer          | Aspire E1-530G              | [25d1490e00](https://linux-hardware.org/?probe=25d1490e00) | Feb 26, 2021 |
| HP            | Pavilion Notebook           | [566be917bf](https://linux-hardware.org/?probe=566be917bf) | Feb 26, 2021 |
| HP            | EliteBook 2560p             | [cfe7bc97ee](https://linux-hardware.org/?probe=cfe7bc97ee) | Feb 26, 2021 |
| Dell          | Latitude E6220              | [dd5034ad28](https://linux-hardware.org/?probe=dd5034ad28) | Feb 25, 2021 |
| Lenovo        | Z50-70 20354                | [1dfe73ce7d](https://linux-hardware.org/?probe=1dfe73ce7d) | Feb 24, 2021 |
| ASUSTek       | X550VX                      | [b9d78cc0df](https://linux-hardware.org/?probe=b9d78cc0df) | Feb 24, 2021 |
| HP            | 620                         | [4608f73b7c](https://linux-hardware.org/?probe=4608f73b7c) | Feb 24, 2021 |
| HP            | 620                         | [a7df560942](https://linux-hardware.org/?probe=a7df560942) | Feb 24, 2021 |
| Lenovo        | G585 20137                  | [f6edfe8704](https://linux-hardware.org/?probe=f6edfe8704) | Feb 24, 2021 |
| Dell          | Inspiron 3580               | [aec0175dda](https://linux-hardware.org/?probe=aec0175dda) | Feb 24, 2021 |
| HP            | 250 G2                      | [9d3487fb0f](https://linux-hardware.org/?probe=9d3487fb0f) | Feb 23, 2021 |
| eMachines     | E525                        | [25c11f3181](https://linux-hardware.org/?probe=25c11f3181) | Feb 23, 2021 |
| HP            | EliteBook 2570p             | [f303c87784](https://linux-hardware.org/?probe=f303c87784) | Feb 23, 2021 |
| Dell          | Inspiron 3521               | [915894fb55](https://linux-hardware.org/?probe=915894fb55) | Feb 23, 2021 |
| Dell          | Inspiron 3521               | [e9926664b0](https://linux-hardware.org/?probe=e9926664b0) | Feb 23, 2021 |
| Dell          | Inspiron 3580               | [fc10e3808e](https://linux-hardware.org/?probe=fc10e3808e) | Feb 23, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f3bc5bcc4f](https://linux-hardware.org/?probe=f3bc5bcc4f) | Feb 23, 2021 |
| Lenovo        | ThinkPad Edge 02212SG       | [619a1a83d8](https://linux-hardware.org/?probe=619a1a83d8) | Feb 22, 2021 |
| HP            | 650                         | [78fdb5c4bc](https://linux-hardware.org/?probe=78fdb5c4bc) | Feb 22, 2021 |
| Dell          | Precision M4800             | [45c92f0ad1](https://linux-hardware.org/?probe=45c92f0ad1) | Feb 22, 2021 |
| Lenovo        | ThinkPad T410 2522A92       | [cbc3d700ee](https://linux-hardware.org/?probe=cbc3d700ee) | Feb 22, 2021 |
| eMachines     | E525                        | [481741977f](https://linux-hardware.org/?probe=481741977f) | Feb 22, 2021 |
| Dell          | Latitude E6420              | [b2e5f33e69](https://linux-hardware.org/?probe=b2e5f33e69) | Feb 21, 2021 |
| Acer          | Aspire F5-771G              | [15ca66e52d](https://linux-hardware.org/?probe=15ca66e52d) | Feb 21, 2021 |
| eMachines     | E525                        | [5b6e9566e7](https://linux-hardware.org/?probe=5b6e9566e7) | Feb 21, 2021 |
| Acer          | Aspire 7750G                | [56972b958c](https://linux-hardware.org/?probe=56972b958c) | Feb 21, 2021 |
| HP            | ProBook 6560b               | [ff06ba428e](https://linux-hardware.org/?probe=ff06ba428e) | Feb 20, 2021 |
| Lenovo        | Z50-75 80EC                 | [cebb0408b1](https://linux-hardware.org/?probe=cebb0408b1) | Feb 20, 2021 |
| Packard Be... | EasyNote TS44HR             | [dedfe3e8c0](https://linux-hardware.org/?probe=dedfe3e8c0) | Feb 20, 2021 |
| Lenovo        | ThinkPad X200 Tablet 745... | [4b4e21e607](https://linux-hardware.org/?probe=4b4e21e607) | Feb 20, 2021 |
| Lenovo        | ThinkPad X200 Tablet 745... | [937ee2d5ae](https://linux-hardware.org/?probe=937ee2d5ae) | Feb 20, 2021 |
| eMachines     | E525                        | [632a9307f6](https://linux-hardware.org/?probe=632a9307f6) | Feb 20, 2021 |
| Lenovo        | ThinkPad Edge 02212SG       | [e785a1317b](https://linux-hardware.org/?probe=e785a1317b) | Feb 20, 2021 |
| Acer          | Aspire A315-55KG            | [a30be319dc](https://linux-hardware.org/?probe=a30be319dc) | Feb 20, 2021 |
| HP            | Mini 110-3500               | [adf2557c53](https://linux-hardware.org/?probe=adf2557c53) | Feb 20, 2021 |
| Packard Be... | EasyNote TK81               | [70477a7af1](https://linux-hardware.org/?probe=70477a7af1) | Feb 19, 2021 |
| ASUSTek       | K52JB                       | [f11acb5bec](https://linux-hardware.org/?probe=f11acb5bec) | Feb 19, 2021 |
| Lenovo        | ThinkPad T440p 20AWS16U0... | [7bcb358d5a](https://linux-hardware.org/?probe=7bcb358d5a) | Feb 19, 2021 |
| ASUSTek       | X550CL                      | [6eb28f1624](https://linux-hardware.org/?probe=6eb28f1624) | Feb 19, 2021 |
| Fujitsu Si... | AMILO Pi 2540               | [e3f58cd216](https://linux-hardware.org/?probe=e3f58cd216) | Feb 18, 2021 |
| Dell          | Vostro 15-3568              | [c9c53d8959](https://linux-hardware.org/?probe=c9c53d8959) | Feb 18, 2021 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [20297c21f8](https://linux-hardware.org/?probe=20297c21f8) | Feb 18, 2021 |
| Acer          | Aspire E5-571G              | [d4a6b5ba05](https://linux-hardware.org/?probe=d4a6b5ba05) | Feb 18, 2021 |
| Acer          | Aspire E5-571G              | [2537521256](https://linux-hardware.org/?probe=2537521256) | Feb 18, 2021 |
| Lenovo        | IdeaPadFlex 10 20324        | [46f59cac87](https://linux-hardware.org/?probe=46f59cac87) | Feb 18, 2021 |
| Dell          | Precision 7530              | [0abb5fcc9e](https://linux-hardware.org/?probe=0abb5fcc9e) | Feb 18, 2021 |
| Dell          | System XPS L502X            | [c5d51e09ab](https://linux-hardware.org/?probe=c5d51e09ab) | Feb 18, 2021 |
| Dell          | System XPS L502X            | [8fa8b18042](https://linux-hardware.org/?probe=8fa8b18042) | Feb 18, 2021 |
| HP            | EliteBook 8540p             | [c7e8878f7b](https://linux-hardware.org/?probe=c7e8878f7b) | Feb 18, 2021 |
| ASUSTek       | 1011PX                      | [499fb41a44](https://linux-hardware.org/?probe=499fb41a44) | Feb 17, 2021 |
| ASUSTek       | 1011PX                      | [6bdaec6040](https://linux-hardware.org/?probe=6bdaec6040) | Feb 17, 2021 |
| Acer          | Aspire E5-411               | [8c0c324cb3](https://linux-hardware.org/?probe=8c0c324cb3) | Feb 16, 2021 |
| eMachines     | E525                        | [909a6a2329](https://linux-hardware.org/?probe=909a6a2329) | Feb 16, 2021 |
| ASUSTek       | K52Jr                       | [fae30cb04a](https://linux-hardware.org/?probe=fae30cb04a) | Feb 16, 2021 |
| ASUSTek       | K52Jr                       | [5a908f8b24](https://linux-hardware.org/?probe=5a908f8b24) | Feb 16, 2021 |
| ASUSTek       | X200MA                      | [489457e409](https://linux-hardware.org/?probe=489457e409) | Feb 15, 2021 |
| Samsung       | R540/R580/R780/SA41/E452... | [58e49bec1a](https://linux-hardware.org/?probe=58e49bec1a) | Feb 15, 2021 |
| HP            | 250 G2                      | [d9662e6e62](https://linux-hardware.org/?probe=d9662e6e62) | Feb 14, 2021 |
| Samsung       | R540/R580/R780/SA41/E452... | [6267428693](https://linux-hardware.org/?probe=6267428693) | Feb 14, 2021 |
| Dell          | System Inspiron N7110       | [07dfe506e8](https://linux-hardware.org/?probe=07dfe506e8) | Feb 14, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [9b487b6e58](https://linux-hardware.org/?probe=9b487b6e58) | Feb 14, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [5d0620c83d](https://linux-hardware.org/?probe=5d0620c83d) | Feb 14, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [fcd45a3dc4](https://linux-hardware.org/?probe=fcd45a3dc4) | Feb 14, 2021 |
| Lenovo        | ThinkPad X240 20AMA0YDHV    | [42a52f9660](https://linux-hardware.org/?probe=42a52f9660) | Feb 14, 2021 |
| Dell          | Latitude E5420              | [d6cb24338b](https://linux-hardware.org/?probe=d6cb24338b) | Feb 13, 2021 |
| Lenovo        | ThinkPad X240 20AMA0YDHV    | [05441468a9](https://linux-hardware.org/?probe=05441468a9) | Feb 13, 2021 |
| Dell          | Latitude E5420              | [e14362e581](https://linux-hardware.org/?probe=e14362e581) | Feb 13, 2021 |
| Acer          | Swift SF113-31              | [63765a9a2d](https://linux-hardware.org/?probe=63765a9a2d) | Feb 13, 2021 |
| Sony          | VPCEB4M1E                   | [8baf4338cd](https://linux-hardware.org/?probe=8baf4338cd) | Feb 13, 2021 |
| Sony          | VPCEB4M1E                   | [d1feea0a6b](https://linux-hardware.org/?probe=d1feea0a6b) | Feb 13, 2021 |
| Dell          | Latitude E5420              | [213509a58e](https://linux-hardware.org/?probe=213509a58e) | Feb 12, 2021 |
| HP            | ProBook 650 G1              | [b5aaa11bbc](https://linux-hardware.org/?probe=b5aaa11bbc) | Feb 11, 2021 |
| Dell          | Inspiron 15-3567            | [f8b215c3ed](https://linux-hardware.org/?probe=f8b215c3ed) | Feb 11, 2021 |
| Packard Be... | EasyNote TS44HR             | [f4440d6539](https://linux-hardware.org/?probe=f4440d6539) | Feb 11, 2021 |
| Dell          | Inspiron 15-3567            | [a4e2325400](https://linux-hardware.org/?probe=a4e2325400) | Feb 11, 2021 |
| Acer          | Aspire A315-32              | [0cabeaae69](https://linux-hardware.org/?probe=0cabeaae69) | Feb 11, 2021 |
| HP            | ProBook 650 G1              | [f629f81661](https://linux-hardware.org/?probe=f629f81661) | Feb 10, 2021 |
| HP            | 250 G1                      | [f893c5b619](https://linux-hardware.org/?probe=f893c5b619) | Feb 10, 2021 |
| Acer          | Aspire E1-530G              | [bbff22aeb1](https://linux-hardware.org/?probe=bbff22aeb1) | Feb 10, 2021 |
| Lenovo        | ThinkPad E520 1143GZG       | [68527c180a](https://linux-hardware.org/?probe=68527c180a) | Feb 10, 2021 |
| Dell          | Precision M4700             | [fb357e9f90](https://linux-hardware.org/?probe=fb357e9f90) | Feb 10, 2021 |
| Acer          | Aspire ES1-511              | [1978e01d5f](https://linux-hardware.org/?probe=1978e01d5f) | Feb 10, 2021 |
| ASUSTek       | 1011PX                      | [e61467f73c](https://linux-hardware.org/?probe=e61467f73c) | Feb 10, 2021 |
| ASUSTek       | 1011PX                      | [8145d4d80e](https://linux-hardware.org/?probe=8145d4d80e) | Feb 10, 2021 |
| Dell          | Latitude XT2                | [082037fcc0](https://linux-hardware.org/?probe=082037fcc0) | Feb 10, 2021 |
| Acer          | Aspire V3-731               | [7775d5d9df](https://linux-hardware.org/?probe=7775d5d9df) | Feb 10, 2021 |
| Lenovo        | ThinkPad T400 6474E18       | [e462c59db7](https://linux-hardware.org/?probe=e462c59db7) | Feb 09, 2021 |
| Dell          | Latitude E6530              | [411acc476b](https://linux-hardware.org/?probe=411acc476b) | Feb 09, 2021 |
| Acer          | TravelMate 4230             | [7b86af6955](https://linux-hardware.org/?probe=7b86af6955) | Feb 09, 2021 |
| Fujitsu       | LIFEBOOK T902               | [02bb4b97f9](https://linux-hardware.org/?probe=02bb4b97f9) | Feb 09, 2021 |
| Acer          | TravelMate 4230             | [a43a972e62](https://linux-hardware.org/?probe=a43a972e62) | Feb 09, 2021 |
| Dell          | Vostro 5581                 | [254dcc72cf](https://linux-hardware.org/?probe=254dcc72cf) | Feb 09, 2021 |
| Dell          | Inspiron 15-3552            | [f90e25519c](https://linux-hardware.org/?probe=f90e25519c) | Feb 09, 2021 |
| Dell          | Inspiron 15-3552            | [d9dc4f82fd](https://linux-hardware.org/?probe=d9dc4f82fd) | Feb 09, 2021 |
| Dell          | Precision M4700             | [f674f91052](https://linux-hardware.org/?probe=f674f91052) | Feb 08, 2021 |
| Lenovo        | G550 20023                  | [b359ae508c](https://linux-hardware.org/?probe=b359ae508c) | Feb 08, 2021 |
| Toshiba       | Satellite P870              | [dc8940596b](https://linux-hardware.org/?probe=dc8940596b) | Feb 08, 2021 |
| Lenovo        | ThinkPad L420 78544UG       | [fbfbf15f89](https://linux-hardware.org/?probe=fbfbf15f89) | Feb 08, 2021 |
| Lenovo        | ThinkPad L420 78544UG       | [1458fd9fa5](https://linux-hardware.org/?probe=1458fd9fa5) | Feb 08, 2021 |
| Fujitsu       | LIFEBOOK T902               | [7d4d4a7e58](https://linux-hardware.org/?probe=7d4d4a7e58) | Feb 08, 2021 |
| Acer          | Aspire ES1-511              | [ed0b8aaff9](https://linux-hardware.org/?probe=ed0b8aaff9) | Feb 08, 2021 |
| Acer          | Aspire ES1-511              | [b1b622e7ad](https://linux-hardware.org/?probe=b1b622e7ad) | Feb 07, 2021 |
| Dell          | Latitude E5440              | [55ee435a1f](https://linux-hardware.org/?probe=55ee435a1f) | Feb 07, 2021 |
| Toshiba       | Satellite L750              | [ef6d41cc6c](https://linux-hardware.org/?probe=ef6d41cc6c) | Feb 07, 2021 |
| Toshiba       | Satellite L750              | [f90432950f](https://linux-hardware.org/?probe=f90432950f) | Feb 07, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [cbe5666380](https://linux-hardware.org/?probe=cbe5666380) | Feb 07, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [e40f3ead0b](https://linux-hardware.org/?probe=e40f3ead0b) | Feb 07, 2021 |
| Lenovo        | G550 20023                  | [d96250849e](https://linux-hardware.org/?probe=d96250849e) | Feb 07, 2021 |
| HP            | 250 G4                      | [0f8f50f795](https://linux-hardware.org/?probe=0f8f50f795) | Feb 07, 2021 |
| Dell          | Latitude E6330              | [672ad9d2e4](https://linux-hardware.org/?probe=672ad9d2e4) | Feb 07, 2021 |
| HP            | EliteBook 8470p             | [023da1c7d7](https://linux-hardware.org/?probe=023da1c7d7) | Feb 06, 2021 |
| Lenovo        | ThinkPad T61 6458WK6        | [8d2918f06c](https://linux-hardware.org/?probe=8d2918f06c) | Feb 06, 2021 |
| HP            | EliteBook 2540p             | [80f2845dd1](https://linux-hardware.org/?probe=80f2845dd1) | Feb 06, 2021 |
| HP            | ProBook 6450b               | [e065e4826b](https://linux-hardware.org/?probe=e065e4826b) | Feb 06, 2021 |
| HP            | 15                          | [42d8bf57f7](https://linux-hardware.org/?probe=42d8bf57f7) | Feb 06, 2021 |
| HP            | EliteBook 8540p             | [92487a475d](https://linux-hardware.org/?probe=92487a475d) | Feb 06, 2021 |
| ASUSTek       | K52De                       | [d50c2dfa52](https://linux-hardware.org/?probe=d50c2dfa52) | Feb 05, 2021 |
| ASUSTek       | K52De                       | [4b71cf0f9d](https://linux-hardware.org/?probe=4b71cf0f9d) | Feb 05, 2021 |
| Dell          | Latitude E6230              | [856adf745b](https://linux-hardware.org/?probe=856adf745b) | Feb 05, 2021 |
| HP            | ProBook 650 G1              | [61c6a4c8bb](https://linux-hardware.org/?probe=61c6a4c8bb) | Feb 04, 2021 |
| HP            | ProBook 650 G1              | [85a6b90a87](https://linux-hardware.org/?probe=85a6b90a87) | Feb 04, 2021 |
| Lenovo        | ThinkPad T400 6474Y32       | [7375b7880b](https://linux-hardware.org/?probe=7375b7880b) | Feb 04, 2021 |
| Lenovo        | ThinkPad T400 6474Y32       | [27f00207e3](https://linux-hardware.org/?probe=27f00207e3) | Feb 04, 2021 |
| Acer          | Extensa 215-21G             | [81fda41eaa](https://linux-hardware.org/?probe=81fda41eaa) | Feb 04, 2021 |
| Lenovo        | ThinkPad W700 27523KG       | [e1d765e35a](https://linux-hardware.org/?probe=e1d765e35a) | Feb 03, 2021 |
| Acer          | Swift SF113-31              | [b9f7e42a01](https://linux-hardware.org/?probe=b9f7e42a01) | Feb 03, 2021 |
| Fujitsu Si... | LIFEBOOK E8410              | [1cc016f60c](https://linux-hardware.org/?probe=1cc016f60c) | Feb 03, 2021 |
| Acer          | Aspire F5-573G              | [0da3f32511](https://linux-hardware.org/?probe=0da3f32511) | Feb 03, 2021 |
| Dell          | System XPS L502X            | [1204db7bcd](https://linux-hardware.org/?probe=1204db7bcd) | Feb 03, 2021 |
| HP            | Pro x2 612 G1 Tablet        | [b42fce1a23](https://linux-hardware.org/?probe=b42fce1a23) | Feb 02, 2021 |
| Dell          | System XPS L502X            | [7b564d8b8f](https://linux-hardware.org/?probe=7b564d8b8f) | Feb 02, 2021 |
| Lenovo        | ThinkPad T61 6458WK6        | [ae4d68636d](https://linux-hardware.org/?probe=ae4d68636d) | Feb 02, 2021 |
| Acer          | Swift SF113-31              | [d6a2e6da4e](https://linux-hardware.org/?probe=d6a2e6da4e) | Feb 02, 2021 |
| Toshiba       | Satellite L500              | [2364e873bf](https://linux-hardware.org/?probe=2364e873bf) | Feb 02, 2021 |
| Lenovo        | V15-ADA 82C7                | [a80684e16a](https://linux-hardware.org/?probe=a80684e16a) | Feb 01, 2021 |
| Lenovo        | V15-ADA 82C7                | [01afa047d6](https://linux-hardware.org/?probe=01afa047d6) | Feb 01, 2021 |
| Dell          | Venue 11 Pro 7139           | [b2db29e616](https://linux-hardware.org/?probe=b2db29e616) | Jan 31, 2021 |
| ASUSTek       | X553MA                      | [1c1ede2b91](https://linux-hardware.org/?probe=1c1ede2b91) | Jan 31, 2021 |
| ASUSTek       | X553MA                      | [4592677cd8](https://linux-hardware.org/?probe=4592677cd8) | Jan 31, 2021 |
| Acer          | Aspire A515-51G             | [2c8dd459ff](https://linux-hardware.org/?probe=2c8dd459ff) | Jan 31, 2021 |
| Fujitsu       | LIFEBOOK AH512              | [f1131173b2](https://linux-hardware.org/?probe=f1131173b2) | Jan 31, 2021 |
| Fujitsu       | LIFEBOOK AH512              | [c7d95e1ab5](https://linux-hardware.org/?probe=c7d95e1ab5) | Jan 31, 2021 |
| HP            | EliteBook 850 G1            | [0cce9f1071](https://linux-hardware.org/?probe=0cce9f1071) | Jan 31, 2021 |
| HP            | EliteBook 850 G1            | [af0e04722e](https://linux-hardware.org/?probe=af0e04722e) | Jan 31, 2021 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | [c53c505ab6](https://linux-hardware.org/?probe=c53c505ab6) | Jan 30, 2021 |
| Lenovo        | G565 20071                  | [f32877769d](https://linux-hardware.org/?probe=f32877769d) | Jan 30, 2021 |
| Packard Be... | EasyNote TK85               | [c65fd44528](https://linux-hardware.org/?probe=c65fd44528) | Jan 30, 2021 |
| HP            | 15                          | [b871b51d0f](https://linux-hardware.org/?probe=b871b51d0f) | Jan 30, 2021 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [b7f4191e49](https://linux-hardware.org/?probe=b7f4191e49) | Jan 30, 2021 |
| HP            | 15                          | [13a8523f75](https://linux-hardware.org/?probe=13a8523f75) | Jan 30, 2021 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [f44cb9b8bf](https://linux-hardware.org/?probe=f44cb9b8bf) | Jan 30, 2021 |
| ASUSTek       | ZenBook 13 UX331FAL_UX33... | [2c7cc1502f](https://linux-hardware.org/?probe=2c7cc1502f) | Jan 30, 2021 |
| HP            | ProBook 6570b               | [8894e9a5ba](https://linux-hardware.org/?probe=8894e9a5ba) | Jan 29, 2021 |
| Acer          | Aspire ES1-523              | [5068058109](https://linux-hardware.org/?probe=5068058109) | Jan 29, 2021 |
| Lenovo        | ThinkPad T460s 20FAS0P90... | [e53b9e29ce](https://linux-hardware.org/?probe=e53b9e29ce) | Jan 29, 2021 |
| Lenovo        | ThinkPad T460s 20FAS0P90... | [43253657a3](https://linux-hardware.org/?probe=43253657a3) | Jan 29, 2021 |
| Lenovo        | G580 20150                  | [4ff748844d](https://linux-hardware.org/?probe=4ff748844d) | Jan 29, 2021 |
| Lenovo        | G580 20150                  | [28ab877fd2](https://linux-hardware.org/?probe=28ab877fd2) | Jan 29, 2021 |
| HP            | ENVY Notebook 13-ab0XX      | [2a88cf3422](https://linux-hardware.org/?probe=2a88cf3422) | Jan 29, 2021 |
| HP            | ENVY Notebook 13-ab0XX      | [0745dc3bf5](https://linux-hardware.org/?probe=0745dc3bf5) | Jan 29, 2021 |
| Dell          | Latitude E6220              | [c940c5f094](https://linux-hardware.org/?probe=c940c5f094) | Jan 28, 2021 |
| Dell          | Latitude E6220              | [08ecbfd1b9](https://linux-hardware.org/?probe=08ecbfd1b9) | Jan 28, 2021 |
| HP            | 250 G4                      | [1439cd5477](https://linux-hardware.org/?probe=1439cd5477) | Jan 28, 2021 |
| Dell          | Vostro 3590                 | [604dc62482](https://linux-hardware.org/?probe=604dc62482) | Jan 28, 2021 |
| Lenovo        | G580 20150                  | [a1a00af891](https://linux-hardware.org/?probe=a1a00af891) | Jan 28, 2021 |
| HP            | EliteBook 8540p             | [dd3793c498](https://linux-hardware.org/?probe=dd3793c498) | Jan 28, 2021 |
| ASUSTek       | X542UN                      | [c71208e5bb](https://linux-hardware.org/?probe=c71208e5bb) | Jan 28, 2021 |
| Dell          | Latitude E4310              | [1f602b4a6b](https://linux-hardware.org/?probe=1f602b4a6b) | Jan 28, 2021 |
| Dell          | Latitude E4310              | [62030c4e17](https://linux-hardware.org/?probe=62030c4e17) | Jan 28, 2021 |
| ASUSTek       | E502SA                      | [2edfdc183b](https://linux-hardware.org/?probe=2edfdc183b) | Jan 28, 2021 |
| ASUSTek       | E502SA                      | [14f031445b](https://linux-hardware.org/?probe=14f031445b) | Jan 28, 2021 |
| Lenovo        | ThinkPad T400 6475ZFX       | [c3038fd781](https://linux-hardware.org/?probe=c3038fd781) | Jan 27, 2021 |
| HP            | EliteBook 8540p             | [11f33ea64e](https://linux-hardware.org/?probe=11f33ea64e) | Jan 27, 2021 |
| HP            | 530 (KD088AA#ABB)           | [b73abc6f76](https://linux-hardware.org/?probe=b73abc6f76) | Jan 27, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [9bb49593b8](https://linux-hardware.org/?probe=9bb49593b8) | Jan 27, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [0e4d8f117e](https://linux-hardware.org/?probe=0e4d8f117e) | Jan 27, 2021 |
| ASUSTek       | E502SA                      | [485e03f522](https://linux-hardware.org/?probe=485e03f522) | Jan 26, 2021 |
| HP            | OMEN by Laptop 15-ce0xx     | [d7f47e4fc7](https://linux-hardware.org/?probe=d7f47e4fc7) | Jan 26, 2021 |
| HP            | 255 G5 Notebook PC          | [9af37cc441](https://linux-hardware.org/?probe=9af37cc441) | Jan 26, 2021 |
| Lenovo        | ThinkPad T420 4236S3T       | [b19ad0ddc5](https://linux-hardware.org/?probe=b19ad0ddc5) | Jan 26, 2021 |
| Dell          | Inspiron 1018               | [e297b7f16d](https://linux-hardware.org/?probe=e297b7f16d) | Jan 26, 2021 |
| Fujitsu       | LIFEBOOK E751               | [663e547ee8](https://linux-hardware.org/?probe=663e547ee8) | Jan 26, 2021 |
| Dell          | Latitude E6220              | [ba4dbd088b](https://linux-hardware.org/?probe=ba4dbd088b) | Jan 26, 2021 |
| Lenovo        | ThinkPad X260 20F5S5VD00    | [525bffab24](https://linux-hardware.org/?probe=525bffab24) | Jan 26, 2021 |
| Fujitsu       | STYLISTIC Q702              | [1ea03e2a92](https://linux-hardware.org/?probe=1ea03e2a92) | Jan 26, 2021 |
| HP            | ZBook 17 G2                 | [689f3a13e2](https://linux-hardware.org/?probe=689f3a13e2) | Jan 26, 2021 |
| Lenovo        | ThinkPad SL410 28423UG      | [a37a1b0ad6](https://linux-hardware.org/?probe=a37a1b0ad6) | Jan 25, 2021 |
| HP            | ZBook 17 G2                 | [e4a9deda20](https://linux-hardware.org/?probe=e4a9deda20) | Jan 25, 2021 |
| Alcor         | Flashbook D1423I            | [bf34fd0f6c](https://linux-hardware.org/?probe=bf34fd0f6c) | Jan 25, 2021 |
| Fujitsu       | STYLISTIC Q702              | [cdde88caca](https://linux-hardware.org/?probe=cdde88caca) | Jan 25, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [f7ae00f708](https://linux-hardware.org/?probe=f7ae00f708) | Jan 24, 2021 |
| Sony          | VPCEB4Z1E                   | [b1f783f8c0](https://linux-hardware.org/?probe=b1f783f8c0) | Jan 24, 2021 |
| Dell          | Latitude E6330              | [b1e58acab1](https://linux-hardware.org/?probe=b1e58acab1) | Jan 24, 2021 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [d90261745f](https://linux-hardware.org/?probe=d90261745f) | Jan 24, 2021 |
| Packard Be... | EasyNote TS13SB             | [6372f79bc4](https://linux-hardware.org/?probe=6372f79bc4) | Jan 23, 2021 |
| Acer          | Extensa 5635Z               | [8b06ad7ba6](https://linux-hardware.org/?probe=8b06ad7ba6) | Jan 23, 2021 |
| Packard Be... | EasyNote TS13SB             | [e1ca74f1f5](https://linux-hardware.org/?probe=e1ca74f1f5) | Jan 23, 2021 |
| Acer          | Aspire A317-51G             | [13bf4701bf](https://linux-hardware.org/?probe=13bf4701bf) | Jan 23, 2021 |
| Acer          | Extensa 5635Z               | [d58d993bc7](https://linux-hardware.org/?probe=d58d993bc7) | Jan 23, 2021 |
| Samsung       | RV410/RV510/S3510/E3510     | [4aba574c22](https://linux-hardware.org/?probe=4aba574c22) | Jan 23, 2021 |
| Samsung       | RV410/RV510/S3510/E3510     | [259c05eda2](https://linux-hardware.org/?probe=259c05eda2) | Jan 23, 2021 |
| HP            | ProBook 650 G5              | [314a05c196](https://linux-hardware.org/?probe=314a05c196) | Jan 23, 2021 |
| HP            | Notebook                    | [8446405348](https://linux-hardware.org/?probe=8446405348) | Jan 22, 2021 |
| HP            | Notebook                    | [6cb5047223](https://linux-hardware.org/?probe=6cb5047223) | Jan 22, 2021 |
| IBM           | Unknown                     | [3be2271444](https://linux-hardware.org/?probe=3be2271444) | Jan 22, 2021 |
| Lenovo        | ThinkPad W510 431924G       | [86c6abc57b](https://linux-hardware.org/?probe=86c6abc57b) | Jan 22, 2021 |
| Lenovo        | G50-45 80E3                 | [1022a2c818](https://linux-hardware.org/?probe=1022a2c818) | Jan 22, 2021 |
| Acer          | Aspire ES1-523              | [4690d43450](https://linux-hardware.org/?probe=4690d43450) | Jan 22, 2021 |
| Lenovo        | G505s 20255                 | [a70f24a3d4](https://linux-hardware.org/?probe=a70f24a3d4) | Jan 22, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [ebb77e712e](https://linux-hardware.org/?probe=ebb77e712e) | Jan 21, 2021 |
| Acer          | Aspire E5-573               | [36b20a1aec](https://linux-hardware.org/?probe=36b20a1aec) | Jan 21, 2021 |
| HP            | 250 G1                      | [fa7943e3c1](https://linux-hardware.org/?probe=fa7943e3c1) | Jan 21, 2021 |
| Dell          | Latitude E6530              | [41a0637bfa](https://linux-hardware.org/?probe=41a0637bfa) | Jan 21, 2021 |
| HP            | 250 G1                      | [f28eb8dd92](https://linux-hardware.org/?probe=f28eb8dd92) | Jan 21, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [074c40654f](https://linux-hardware.org/?probe=074c40654f) | Jan 21, 2021 |
| HP            | 250 G1                      | [07ae0b8525](https://linux-hardware.org/?probe=07ae0b8525) | Jan 21, 2021 |
| Medion        | E122X                       | [3cc8872d47](https://linux-hardware.org/?probe=3cc8872d47) | Jan 20, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [f5ad363078](https://linux-hardware.org/?probe=f5ad363078) | Jan 20, 2021 |
| Lenovo        | G505s 20255                 | [5521ddef20](https://linux-hardware.org/?probe=5521ddef20) | Jan 20, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [d3a3d2df41](https://linux-hardware.org/?probe=d3a3d2df41) | Jan 20, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [e97c74d8c9](https://linux-hardware.org/?probe=e97c74d8c9) | Jan 19, 2021 |
| HP            | EliteBook 8560w             | [ee7957f581](https://linux-hardware.org/?probe=ee7957f581) | Jan 19, 2021 |
| HP            | Pavilion Laptop 15-cc5xx    | [0c0ad1edec](https://linux-hardware.org/?probe=0c0ad1edec) | Jan 19, 2021 |
| Lenovo        | G580 20150                  | [befa288f83](https://linux-hardware.org/?probe=befa288f83) | Jan 19, 2021 |
| HP            | 620                         | [a86507a5cd](https://linux-hardware.org/?probe=a86507a5cd) | Jan 19, 2021 |
| Acer          | Nitro AN515-42              | [2e43134d4d](https://linux-hardware.org/?probe=2e43134d4d) | Jan 18, 2021 |
| HP            | EliteBook 8560w             | [90e0c0cec0](https://linux-hardware.org/?probe=90e0c0cec0) | Jan 18, 2021 |
| Lenovo        | G580 20150                  | [dc8bf051d3](https://linux-hardware.org/?probe=dc8bf051d3) | Jan 17, 2021 |
| Dell          | G3 3579                     | [ad25060944](https://linux-hardware.org/?probe=ad25060944) | Jan 17, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [a0c3014b22](https://linux-hardware.org/?probe=a0c3014b22) | Jan 17, 2021 |
| HP            | 250 G1                      | [e63d94044e](https://linux-hardware.org/?probe=e63d94044e) | Jan 17, 2021 |
| HP            | Laptop 17-ak0xx             | [5760ec207f](https://linux-hardware.org/?probe=5760ec207f) | Jan 16, 2021 |
| Dell          | Inspiron N5040              | [e6a927609f](https://linux-hardware.org/?probe=e6a927609f) | Jan 16, 2021 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | [325809a72d](https://linux-hardware.org/?probe=325809a72d) | Jan 16, 2021 |
| Dell          | Vostro 15-3568              | [b4bc9194b3](https://linux-hardware.org/?probe=b4bc9194b3) | Jan 16, 2021 |
| Acer          | Aspire A317-51G             | [984152be50](https://linux-hardware.org/?probe=984152be50) | Jan 16, 2021 |
| ASUSTek       | 1011PX                      | [8f2dd48c15](https://linux-hardware.org/?probe=8f2dd48c15) | Jan 15, 2021 |
| Dell          | Latitude 5480               | [3f873878ed](https://linux-hardware.org/?probe=3f873878ed) | Jan 14, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [293835037b](https://linux-hardware.org/?probe=293835037b) | Jan 13, 2021 |
| Acer          | Aspire E5-573               | [72ed6256a4](https://linux-hardware.org/?probe=72ed6256a4) | Jan 12, 2021 |
| HP            | Pavilion g6                 | [822e6b6c4f](https://linux-hardware.org/?probe=822e6b6c4f) | Jan 12, 2021 |
| Samsung       | R540/R580/R780/SA41/E452... | [82effa71c4](https://linux-hardware.org/?probe=82effa71c4) | Jan 11, 2021 |
| Lenovo        | ThinkPad W510 4876A46       | [d4688142cc](https://linux-hardware.org/?probe=d4688142cc) | Jan 11, 2021 |
| Fujitsu Si... | AMILO Xi 3650               | [0ed58f1c19](https://linux-hardware.org/?probe=0ed58f1c19) | Jan 11, 2021 |
| Fujitsu Si... | AMILO Xi 3650               | [b5b08b8e5c](https://linux-hardware.org/?probe=b5b08b8e5c) | Jan 11, 2021 |
| HP            | Compaq nc6320 (RH368EA#A... | [6b11dc5ae6](https://linux-hardware.org/?probe=6b11dc5ae6) | Jan 11, 2021 |
| Toshiba       | Satellite L750              | [d3716d3643](https://linux-hardware.org/?probe=d3716d3643) | Jan 11, 2021 |
| Lenovo        | IdeaPad 5-14ARE05 81YH      | [49eb50f6ed](https://linux-hardware.org/?probe=49eb50f6ed) | Jan 10, 2021 |
| HP            | 650                         | [984bbb5863](https://linux-hardware.org/?probe=984bbb5863) | Jan 10, 2021 |
| HP            | EliteBook 8470p             | [2a359fdfaf](https://linux-hardware.org/?probe=2a359fdfaf) | Jan 10, 2021 |
| HP            | EliteBook 8440p             | [ba250ee708](https://linux-hardware.org/?probe=ba250ee708) | Jan 09, 2021 |
| HP            | EliteBook 8440p             | [f6a9c2b7b9](https://linux-hardware.org/?probe=f6a9c2b7b9) | Jan 09, 2021 |
| HP            | 655                         | [9b8501d2f9](https://linux-hardware.org/?probe=9b8501d2f9) | Jan 09, 2021 |
| Lenovo        | ThinkPad T420 4236WCS       | [92abca59a9](https://linux-hardware.org/?probe=92abca59a9) | Jan 09, 2021 |
| Lenovo        | ThinkPad T420 4236WCS       | [2caf1727af](https://linux-hardware.org/?probe=2caf1727af) | Jan 09, 2021 |
| ASUSTek       | K53SJ                       | [19c9d1cd7e](https://linux-hardware.org/?probe=19c9d1cd7e) | Jan 09, 2021 |
| Dell          | Latitude E7240              | [dbb6065703](https://linux-hardware.org/?probe=dbb6065703) | Jan 09, 2021 |
| ASUSTek       | G752VT                      | [dbc78aa02e](https://linux-hardware.org/?probe=dbc78aa02e) | Jan 09, 2021 |
| Dell          | Latitude E5440              | [c0d46673e2](https://linux-hardware.org/?probe=c0d46673e2) | Jan 08, 2021 |
| Dell          | Inspiron 3585               | [a1ecf2b574](https://linux-hardware.org/?probe=a1ecf2b574) | Jan 08, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [2d414e0050](https://linux-hardware.org/?probe=2d414e0050) | Jan 08, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [be3082e900](https://linux-hardware.org/?probe=be3082e900) | Jan 08, 2021 |
| Dell          | Inspiron 3585               | [3f5bec0fd5](https://linux-hardware.org/?probe=3f5bec0fd5) | Jan 08, 2021 |
| Acer          | Aspire V3-551G              | [7f54c3b6fc](https://linux-hardware.org/?probe=7f54c3b6fc) | Jan 08, 2021 |
| Acer          | Aspire V3-551G              | [14431ab03a](https://linux-hardware.org/?probe=14431ab03a) | Jan 07, 2021 |
| Lenovo        | Z50-75 80EC                 | [ed8b12eae1](https://linux-hardware.org/?probe=ed8b12eae1) | Jan 07, 2021 |
| HP            | EliteBook 8560w             | [87a6fe0110](https://linux-hardware.org/?probe=87a6fe0110) | Jan 07, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [eb5f1ef793](https://linux-hardware.org/?probe=eb5f1ef793) | Jan 07, 2021 |
| ASUSTek       | X540NA                      | [006e6e9217](https://linux-hardware.org/?probe=006e6e9217) | Jan 07, 2021 |
| Lenovo        | Z50-75 80EC                 | [96f9b08bac](https://linux-hardware.org/?probe=96f9b08bac) | Jan 07, 2021 |
| Dell          | Latitude E7240              | [5c6b3b4c89](https://linux-hardware.org/?probe=5c6b3b4c89) | Jan 07, 2021 |
| HP            | EliteBook 8540p             | [a5612ca66a](https://linux-hardware.org/?probe=a5612ca66a) | Jan 07, 2021 |
| eMachines     | eME728                      | [9e4afb5c82](https://linux-hardware.org/?probe=9e4afb5c82) | Jan 06, 2021 |
| ASUSTek       | X751SA                      | [eb12bf09bb](https://linux-hardware.org/?probe=eb12bf09bb) | Jan 06, 2021 |
| Dell          | G3 3579                     | [688778fe70](https://linux-hardware.org/?probe=688778fe70) | Jan 06, 2021 |
| Dell          | Inspiron MXC061             | [31325155e6](https://linux-hardware.org/?probe=31325155e6) | Jan 06, 2021 |
| Dell          | Inspiron MXC061             | [3795955b65](https://linux-hardware.org/?probe=3795955b65) | Jan 06, 2021 |
| HP            | EliteBook 8560w             | [a38c239161](https://linux-hardware.org/?probe=a38c239161) | Jan 05, 2021 |
| Dell          | Precision 5540              | [f6c21b8453](https://linux-hardware.org/?probe=f6c21b8453) | Jan 05, 2021 |
| Acer          | Aspire F5-573G              | [f1a5da029b](https://linux-hardware.org/?probe=f1a5da029b) | Jan 05, 2021 |
| Lenovo        | G580 20150                  | [da0b2a8b72](https://linux-hardware.org/?probe=da0b2a8b72) | Jan 03, 2021 |
| Dell          | Inspiron 5558               | [525398f0bc](https://linux-hardware.org/?probe=525398f0bc) | Jan 03, 2021 |
| Acer          | Aspire 7720                 | [87a91e32b6](https://linux-hardware.org/?probe=87a91e32b6) | Jan 03, 2021 |
| Acer          | Aspire 7720                 | [c385eeb89a](https://linux-hardware.org/?probe=c385eeb89a) | Jan 02, 2021 |
| Acer          | Aspire F5-573G              | [a444a7a020](https://linux-hardware.org/?probe=a444a7a020) | Jan 02, 2021 |
| Packard Be... | EasyNote TK36               | [d5aeb5be31](https://linux-hardware.org/?probe=d5aeb5be31) | Jan 02, 2021 |
| HP            | Notebook                    | [0d1a9a7376](https://linux-hardware.org/?probe=0d1a9a7376) | Jan 02, 2021 |
| HP            | Notebook                    | [c73e79444f](https://linux-hardware.org/?probe=c73e79444f) | Jan 02, 2021 |
| HP            | Pavilion Notebook           | [9f05688ad9](https://linux-hardware.org/?probe=9f05688ad9) | Jan 02, 2021 |
| Packard Be... | EasyNote TK36               | [43b59e2a0c](https://linux-hardware.org/?probe=43b59e2a0c) | Jan 02, 2021 |
| Dell          | Inspiron 7737               | [2cec563402](https://linux-hardware.org/?probe=2cec563402) | Jan 01, 2021 |
| Dell          | Inspiron N5050              | [b027354a9f](https://linux-hardware.org/?probe=b027354a9f) | Jan 01, 2021 |
| Dell          | Inspiron N5050              | [9182d97e2f](https://linux-hardware.org/?probe=9182d97e2f) | Jan 01, 2021 |
| Dell          | Inspiron N5050              | [394d608dea](https://linux-hardware.org/?probe=394d608dea) | Jan 01, 2021 |
| ASUSTek       | Zephyrus M GM501GS          | [07531ef4c9](https://linux-hardware.org/?probe=07531ef4c9) | Jan 01, 2021 |
| Lenovo        | ThinkPad T510 4384VN6       | [4d7088c946](https://linux-hardware.org/?probe=4d7088c946) | Jan 01, 2021 |
| Intel         | Calistoga & ICH7M Chipse... | [25db9022c9](https://linux-hardware.org/?probe=25db9022c9) | Jan 01, 2021 |
| Lenovo        | ThinkPad T510 4384VN6       | [14bb6bb277](https://linux-hardware.org/?probe=14bb6bb277) | Jan 01, 2021 |
| Dell          | Inspiron 15-3552            | [0fd3b973ac](https://linux-hardware.org/?probe=0fd3b973ac) | Jan 01, 2021 |
| HP            | EliteBook 8440p             | [4569e4959d](https://linux-hardware.org/?probe=4569e4959d) | Dec 31, 2020 |
| HP            | EliteBook 8440p             | [6f0539d8eb](https://linux-hardware.org/?probe=6f0539d8eb) | Dec 31, 2020 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [50a80314e8](https://linux-hardware.org/?probe=50a80314e8) | Dec 31, 2020 |
| Lenovo        | V330-15IKB 81AX             | [198f958ead](https://linux-hardware.org/?probe=198f958ead) | Dec 30, 2020 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [cd8f240ffa](https://linux-hardware.org/?probe=cd8f240ffa) | Dec 30, 2020 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [5a2c5f2678](https://linux-hardware.org/?probe=5a2c5f2678) | Dec 30, 2020 |
| Acer          | Aspire E1-571               | [c1109a4213](https://linux-hardware.org/?probe=c1109a4213) | Dec 30, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [ab1115640a](https://linux-hardware.org/?probe=ab1115640a) | Dec 30, 2020 |
| HP            | ProBook 6570b               | [30b31762db](https://linux-hardware.org/?probe=30b31762db) | Dec 30, 2020 |
| HP            | ProBook 6570b               | [d31e77cf2d](https://linux-hardware.org/?probe=d31e77cf2d) | Dec 30, 2020 |
| Lenovo        | ThinkPad T400 6474E18       | [2c5f4da774](https://linux-hardware.org/?probe=2c5f4da774) | Dec 29, 2020 |
| Lenovo        | ThinkPad T400 6474E18       | [07981976b5](https://linux-hardware.org/?probe=07981976b5) | Dec 29, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [c11d9786f7](https://linux-hardware.org/?probe=c11d9786f7) | Dec 29, 2020 |
| Acer          | Sabine Platform             | [83a401daf2](https://linux-hardware.org/?probe=83a401daf2) | Dec 29, 2020 |
| Alcor         | Flashbook D1423I            | [838d77c388](https://linux-hardware.org/?probe=838d77c388) | Dec 29, 2020 |
| Acer          | Aspire 8930                 | [c9e3c337e0](https://linux-hardware.org/?probe=c9e3c337e0) | Dec 29, 2020 |
| Acer          | Aspire 8930                 | [0c2886cc08](https://linux-hardware.org/?probe=0c2886cc08) | Dec 29, 2020 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [da0f58d30c](https://linux-hardware.org/?probe=da0f58d30c) | Dec 29, 2020 |
| Dell          | Latitude E6400              | [4074e91eb7](https://linux-hardware.org/?probe=4074e91eb7) | Dec 29, 2020 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [42cd53b99c](https://linux-hardware.org/?probe=42cd53b99c) | Dec 28, 2020 |
| Dell          | Latitude 5285               | [21853e6ddd](https://linux-hardware.org/?probe=21853e6ddd) | Dec 28, 2020 |
| ASUSTek       | K53E                        | [9d1dc95853](https://linux-hardware.org/?probe=9d1dc95853) | Dec 28, 2020 |
| HP            | 650                         | [671043372d](https://linux-hardware.org/?probe=671043372d) | Dec 28, 2020 |
| HP            | Pavilion g7                 | [5182b86541](https://linux-hardware.org/?probe=5182b86541) | Dec 28, 2020 |
| HP            | 250 G4                      | [941d5d8bda](https://linux-hardware.org/?probe=941d5d8bda) | Dec 27, 2020 |
| HP            | 250 G1                      | [0ced050f60](https://linux-hardware.org/?probe=0ced050f60) | Dec 27, 2020 |
| Fujitsu       | CELSIUS H920                | [5d0bfd3988](https://linux-hardware.org/?probe=5d0bfd3988) | Dec 27, 2020 |
| ASUSTek       | N55SF                       | [989f4dec22](https://linux-hardware.org/?probe=989f4dec22) | Dec 27, 2020 |
| ASUSTek       | K53E                        | [9cd923608c](https://linux-hardware.org/?probe=9cd923608c) | Dec 26, 2020 |
| HP            | ProBook 6460b               | [308082255b](https://linux-hardware.org/?probe=308082255b) | Dec 26, 2020 |
| Dell          | Inspiron 7737               | [9903e3e092](https://linux-hardware.org/?probe=9903e3e092) | Dec 26, 2020 |
| HP            | 635                         | [8b759a0aa0](https://linux-hardware.org/?probe=8b759a0aa0) | Dec 26, 2020 |
| HP            | 635                         | [39ab2cefd8](https://linux-hardware.org/?probe=39ab2cefd8) | Dec 26, 2020 |
| Dell          | Inspiron 7737               | [a91f762908](https://linux-hardware.org/?probe=a91f762908) | Dec 26, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [c24291e06b](https://linux-hardware.org/?probe=c24291e06b) | Dec 26, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [9c3ab34497](https://linux-hardware.org/?probe=9c3ab34497) | Dec 26, 2020 |
| Acer          | Aspire 5542                 | [b61f73224f](https://linux-hardware.org/?probe=b61f73224f) | Dec 25, 2020 |
| Acer          | Aspire 5542                 | [5c31519f77](https://linux-hardware.org/?probe=5c31519f77) | Dec 25, 2020 |
| Toshiba       | Satellite L750              | [fb2add6887](https://linux-hardware.org/?probe=fb2add6887) | Dec 24, 2020 |
| Acer          | Aspire F5-573G              | [0866912c49](https://linux-hardware.org/?probe=0866912c49) | Dec 24, 2020 |
| Dell          | Inspiron 1440               | [6b169325ea](https://linux-hardware.org/?probe=6b169325ea) | Dec 23, 2020 |
| ASUSTek       | G752VT                      | [f2e1f5a299](https://linux-hardware.org/?probe=f2e1f5a299) | Dec 23, 2020 |
| Dell          | Inspiron 1090               | [86e4bdcdff](https://linux-hardware.org/?probe=86e4bdcdff) | Dec 23, 2020 |
| Dell          | Inspiron 1090               | [e32dfaa1e4](https://linux-hardware.org/?probe=e32dfaa1e4) | Dec 23, 2020 |
| HP            | Pavilion g7                 | [aa99273f61](https://linux-hardware.org/?probe=aa99273f61) | Dec 23, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [4c62752cb9](https://linux-hardware.org/?probe=4c62752cb9) | Dec 23, 2020 |
| ASUSTek       | K53E                        | [a8d66cc547](https://linux-hardware.org/?probe=a8d66cc547) | Dec 23, 2020 |
| Lenovo        | G50-45 80E3                 | [02e7794674](https://linux-hardware.org/?probe=02e7794674) | Dec 23, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [3372fd5612](https://linux-hardware.org/?probe=3372fd5612) | Dec 23, 2020 |
| Toshiba       | Satellite Pro L300          | [6472a832b4](https://linux-hardware.org/?probe=6472a832b4) | Dec 22, 2020 |
| Toshiba       | Satellite Pro L300          | [617710ee2d](https://linux-hardware.org/?probe=617710ee2d) | Dec 22, 2020 |
| HP            | Pavilion 11 x360 PC         | [66c5d91373](https://linux-hardware.org/?probe=66c5d91373) | Dec 22, 2020 |
| HP            | Pavilion 11 x360 PC         | [f0e36419ae](https://linux-hardware.org/?probe=f0e36419ae) | Dec 22, 2020 |
| HP            | Unknown                     | [8b9367606b](https://linux-hardware.org/?probe=8b9367606b) | Dec 22, 2020 |
| ASUSTek       | N55SF                       | [6558706cf9](https://linux-hardware.org/?probe=6558706cf9) | Dec 22, 2020 |
| Acer          | Aspire E5-772G              | [7159f22b25](https://linux-hardware.org/?probe=7159f22b25) | Dec 21, 2020 |
| Samsung       | N150/N210/N220              | [854cf323a6](https://linux-hardware.org/?probe=854cf323a6) | Dec 21, 2020 |
| Lenovo        | ThinkPad T61 6458WK6        | [aa2b5741ba](https://linux-hardware.org/?probe=aa2b5741ba) | Dec 21, 2020 |
| HP            | Unknown                     | [926ad2cdb1](https://linux-hardware.org/?probe=926ad2cdb1) | Dec 21, 2020 |
| Lenovo        | ThinkPad T480s 20L8S8540... | [12fb9652a7](https://linux-hardware.org/?probe=12fb9652a7) | Dec 21, 2020 |
| Acer          | Aspire E5-772G              | [f2427e7402](https://linux-hardware.org/?probe=f2427e7402) | Dec 21, 2020 |
| Hungaro Fl... | Navon Loop 360              | [f12051f884](https://linux-hardware.org/?probe=f12051f884) | Dec 20, 2020 |
| Lenovo        | ThinkPad T540p 20BFS0RK1... | [0377183ebd](https://linux-hardware.org/?probe=0377183ebd) | Dec 20, 2020 |
| Lenovo        | ThinkPad T540p 20BFS0RK1... | [17467ac4ff](https://linux-hardware.org/?probe=17467ac4ff) | Dec 20, 2020 |
| ASUSTek       | K53SK                       | [dc73de2e9f](https://linux-hardware.org/?probe=dc73de2e9f) | Dec 20, 2020 |
| Samsung       | N150/N210/N220              | [d1c819d6b8](https://linux-hardware.org/?probe=d1c819d6b8) | Dec 20, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [c7efde2762](https://linux-hardware.org/?probe=c7efde2762) | Dec 20, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [fed08acf3a](https://linux-hardware.org/?probe=fed08acf3a) | Dec 20, 2020 |
| HP            | 250 G4                      | [9bf0ebf1fd](https://linux-hardware.org/?probe=9bf0ebf1fd) | Dec 20, 2020 |
| Dell          | Latitude E7250              | [7b1e28859e](https://linux-hardware.org/?probe=7b1e28859e) | Dec 19, 2020 |
| HP            | ProBook 640 G2              | [6ff52b5c37](https://linux-hardware.org/?probe=6ff52b5c37) | Dec 19, 2020 |
| Dell          | Latitude E7250              | [d4ef339e3c](https://linux-hardware.org/?probe=d4ef339e3c) | Dec 19, 2020 |
| HP            | ProBook 640 G2              | [aa0abb8eb0](https://linux-hardware.org/?probe=aa0abb8eb0) | Dec 19, 2020 |
| Lenovo        | ThinkPad X260 20F5S1BC00    | [164b182eec](https://linux-hardware.org/?probe=164b182eec) | Dec 19, 2020 |
| Fujitsu       | CELSIUS H920                | [355d708b29](https://linux-hardware.org/?probe=355d708b29) | Dec 19, 2020 |
| Toshiba       | Satellite P100              | [c817dd53f4](https://linux-hardware.org/?probe=c817dd53f4) | Dec 19, 2020 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [0b0d3f98f9](https://linux-hardware.org/?probe=0b0d3f98f9) | Dec 19, 2020 |
| Fujitsu       | CELSIUS H920                | [8948650052](https://linux-hardware.org/?probe=8948650052) | Dec 19, 2020 |
| Acer          | Aspire 5732Z                | [94baf83aa4](https://linux-hardware.org/?probe=94baf83aa4) | Dec 18, 2020 |
| Acer          | Aspire 5732Z                | [6eaad6d04b](https://linux-hardware.org/?probe=6eaad6d04b) | Dec 18, 2020 |
| Fujitsu Si... | AMILO Li 2727               | [af3b3c5a1a](https://linux-hardware.org/?probe=af3b3c5a1a) | Dec 18, 2020 |
| Fujitsu Si... | AMILO Li 2727               | [518297ccb8](https://linux-hardware.org/?probe=518297ccb8) | Dec 18, 2020 |
| Toshiba       | Satellite Pro L300          | [e8335f20c1](https://linux-hardware.org/?probe=e8335f20c1) | Dec 18, 2020 |
| HP            | 250 G2                      | [adc6f86d58](https://linux-hardware.org/?probe=adc6f86d58) | Dec 17, 2020 |
| HP            | EliteBook 8540w             | [51fcd85905](https://linux-hardware.org/?probe=51fcd85905) | Dec 17, 2020 |
| Lenovo        | ThinkPad T400 6474E18       | [670a033f37](https://linux-hardware.org/?probe=670a033f37) | Dec 17, 2020 |
| HP            | G56                         | [1f1c829cd3](https://linux-hardware.org/?probe=1f1c829cd3) | Dec 17, 2020 |
| HP            | G56                         | [d8304a5c9b](https://linux-hardware.org/?probe=d8304a5c9b) | Dec 17, 2020 |
| HP            | 250 G1                      | [609b871759](https://linux-hardware.org/?probe=609b871759) | Dec 17, 2020 |
| HP            | 250 G1                      | [8bb5e1f25d](https://linux-hardware.org/?probe=8bb5e1f25d) | Dec 17, 2020 |
| HP            | EliteBook 2570p             | [d4cb7ccc8e](https://linux-hardware.org/?probe=d4cb7ccc8e) | Dec 17, 2020 |
| HP            | EliteBook 2570p             | [4103e3c28b](https://linux-hardware.org/?probe=4103e3c28b) | Dec 17, 2020 |
| Lenovo        | ThinkPad X260 20F5S1BC00    | [2553c6c31e](https://linux-hardware.org/?probe=2553c6c31e) | Dec 17, 2020 |
| Dell          | G3 3579                     | [b4f57b0991](https://linux-hardware.org/?probe=b4f57b0991) | Dec 16, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [61dc5d4b9b](https://linux-hardware.org/?probe=61dc5d4b9b) | Dec 16, 2020 |
| Fujitsu Si... | AMILO PRO V3515             | [4c0df03f70](https://linux-hardware.org/?probe=4c0df03f70) | Dec 15, 2020 |
| eMachines     | eME730G                     | [fb77fd1216](https://linux-hardware.org/?probe=fb77fd1216) | Dec 15, 2020 |
| Acer          | AO532h                      | [1a7648205f](https://linux-hardware.org/?probe=1a7648205f) | Dec 15, 2020 |
| Acer          | AO532h                      | [633d3c684e](https://linux-hardware.org/?probe=633d3c684e) | Dec 14, 2020 |
| HP            | Compaq 6715b (GB835EA#AK... | [d19283bc91](https://linux-hardware.org/?probe=d19283bc91) | Dec 14, 2020 |
| Acer          | Aspire F5-573G              | [a355470e32](https://linux-hardware.org/?probe=a355470e32) | Dec 14, 2020 |
| Acer          | Aspire F5-573G              | [7c47f34320](https://linux-hardware.org/?probe=7c47f34320) | Dec 14, 2020 |
| HP            | Compaq 6715b (GB835EA#AK... | [9a93ae3d7f](https://linux-hardware.org/?probe=9a93ae3d7f) | Dec 14, 2020 |
| Acer          | Aspire 5736Z                | [9772669197](https://linux-hardware.org/?probe=9772669197) | Dec 14, 2020 |
| ASUSTek       | F5N                         | [9f7742f32e](https://linux-hardware.org/?probe=9f7742f32e) | Dec 14, 2020 |
| ASUSTek       | F5N                         | [b25d8e2391](https://linux-hardware.org/?probe=b25d8e2391) | Dec 14, 2020 |
| ASUSTek       | K52Jr                       | [f01486b052](https://linux-hardware.org/?probe=f01486b052) | Dec 14, 2020 |
| ASUSTek       | K52Jr                       | [033a2c37e3](https://linux-hardware.org/?probe=033a2c37e3) | Dec 14, 2020 |
| Dell          | Latitude D630               | [3cc91fd794](https://linux-hardware.org/?probe=3cc91fd794) | Dec 13, 2020 |
| Acer          | Aspire 5732Z                | [2dd9847217](https://linux-hardware.org/?probe=2dd9847217) | Dec 13, 2020 |
| Lenovo        | IdeaPad 320-17ISK 80XJ      | [51b41f6080](https://linux-hardware.org/?probe=51b41f6080) | Dec 12, 2020 |
| HP            | Pavilion dv6                | [92982d40c3](https://linux-hardware.org/?probe=92982d40c3) | Dec 12, 2020 |
| HP            | Pavilion dv6                | [2d091efdb7](https://linux-hardware.org/?probe=2d091efdb7) | Dec 12, 2020 |
| Dell          | Latitude E4300              | [0b9e0759b6](https://linux-hardware.org/?probe=0b9e0759b6) | Dec 11, 2020 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [fe9eb7f00e](https://linux-hardware.org/?probe=fe9eb7f00e) | Dec 11, 2020 |
| Acer          | TravelMate 8571             | [2bab87c562](https://linux-hardware.org/?probe=2bab87c562) | Dec 11, 2020 |
| Acer          | Aspire 5732Z                | [adf2187447](https://linux-hardware.org/?probe=adf2187447) | Dec 11, 2020 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [9f9eae2212](https://linux-hardware.org/?probe=9f9eae2212) | Dec 11, 2020 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [e57a5c5302](https://linux-hardware.org/?probe=e57a5c5302) | Dec 11, 2020 |
| Dell          | Latitude E5500              | [6ce937d023](https://linux-hardware.org/?probe=6ce937d023) | Dec 10, 2020 |
| Samsung       | 905S3G/906S3G/915S3G/930... | [5c03c0c342](https://linux-hardware.org/?probe=5c03c0c342) | Dec 10, 2020 |
| Dell          | Latitude E6540              | [6517ec0d53](https://linux-hardware.org/?probe=6517ec0d53) | Dec 09, 2020 |
| HP            | Compaq 615                  | [1a6fc28bdc](https://linux-hardware.org/?probe=1a6fc28bdc) | Dec 09, 2020 |
| Packard Be... | EasyNote TS11HR             | [e21990cfd8](https://linux-hardware.org/?probe=e21990cfd8) | Dec 09, 2020 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [b34f8631c6](https://linux-hardware.org/?probe=b34f8631c6) | Dec 08, 2020 |
| HP            | Compaq 615                  | [1d5cf3a97d](https://linux-hardware.org/?probe=1d5cf3a97d) | Dec 08, 2020 |
| Dell          | Latitude 5401               | [2f4ca16020](https://linux-hardware.org/?probe=2f4ca16020) | Dec 08, 2020 |
| HP            | 530                         | [e613d164e7](https://linux-hardware.org/?probe=e613d164e7) | Dec 08, 2020 |
| HP            | 530                         | [7677ffebd6](https://linux-hardware.org/?probe=7677ffebd6) | Dec 08, 2020 |
| Acer          | E1-572G                     | [e9917f98d4](https://linux-hardware.org/?probe=e9917f98d4) | Dec 07, 2020 |
| HP            | EliteBook 840 G2            | [2a56049889](https://linux-hardware.org/?probe=2a56049889) | Dec 07, 2020 |
| HP            | Pavilion 15                 | [f85041de83](https://linux-hardware.org/?probe=f85041de83) | Dec 07, 2020 |
| HP            | Pavilion 15                 | [1cdb6d4983](https://linux-hardware.org/?probe=1cdb6d4983) | Dec 07, 2020 |
| Dell          | Latitude E5500              | [09cc0ae26d](https://linux-hardware.org/?probe=09cc0ae26d) | Dec 06, 2020 |
| Lenovo        | IdeaPad 320-17ISK 80XJ      | [8834d77b69](https://linux-hardware.org/?probe=8834d77b69) | Dec 06, 2020 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [f80f03d4bb](https://linux-hardware.org/?probe=f80f03d4bb) | Dec 06, 2020 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [da40d2b867](https://linux-hardware.org/?probe=da40d2b867) | Dec 05, 2020 |
| ASUSTek       | X540SA                      | [d7038b23de](https://linux-hardware.org/?probe=d7038b23de) | Dec 05, 2020 |
| HP            | ProBook 640 G2              | [366f05d4d1](https://linux-hardware.org/?probe=366f05d4d1) | Dec 04, 2020 |
| HP            | Pavilion g6                 | [ac1a52456d](https://linux-hardware.org/?probe=ac1a52456d) | Dec 04, 2020 |
| HUAWEI        | BOHK-WAX9X                  | [d81e6e9f36](https://linux-hardware.org/?probe=d81e6e9f36) | Dec 04, 2020 |
| HP            | Pavilion g6                 | [9e0e778e94](https://linux-hardware.org/?probe=9e0e778e94) | Dec 04, 2020 |
| HP            | 255 G2                      | [a49abb56b5](https://linux-hardware.org/?probe=a49abb56b5) | Dec 04, 2020 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [d51dfadd76](https://linux-hardware.org/?probe=d51dfadd76) | Dec 04, 2020 |
| Acer          | Aspire 5732Z                | [29ccd1be66](https://linux-hardware.org/?probe=29ccd1be66) | Dec 03, 2020 |
| Dell          | Latitude D630               | [7ca5122c8e](https://linux-hardware.org/?probe=7ca5122c8e) | Dec 03, 2020 |
| Acer          | Aspire 5732Z                | [6d39206cdb](https://linux-hardware.org/?probe=6d39206cdb) | Dec 03, 2020 |
| ASUSTek       | F9E                         | [14e9013532](https://linux-hardware.org/?probe=14e9013532) | Dec 03, 2020 |
| ASUSTek       | F9E                         | [6742378935](https://linux-hardware.org/?probe=6742378935) | Dec 03, 2020 |
| HP            | OMEN by Laptop 15-ce0xx     | [c78434ecd2](https://linux-hardware.org/?probe=c78434ecd2) | Dec 03, 2020 |
| ASUSTek       | Strix 15 GL503GE            | [b60e89e6b0](https://linux-hardware.org/?probe=b60e89e6b0) | Dec 02, 2020 |
| Dell          | Latitude E4310              | [b69c559451](https://linux-hardware.org/?probe=b69c559451) | Dec 02, 2020 |
| Dell          | Latitude E4310              | [523b28f370](https://linux-hardware.org/?probe=523b28f370) | Dec 02, 2020 |
| ASUSTek       | K54L                        | [d10ce66631](https://linux-hardware.org/?probe=d10ce66631) | Dec 02, 2020 |
| Dell          | Precision M4800             | [c6b54987f0](https://linux-hardware.org/?probe=c6b54987f0) | Dec 02, 2020 |
| Acer          | Aspire A515-51G             | [0b6e28e374](https://linux-hardware.org/?probe=0b6e28e374) | Dec 02, 2020 |
| HP            | EliteBook 8570p             | [fa751628e8](https://linux-hardware.org/?probe=fa751628e8) | Dec 02, 2020 |
| Acer          | Aspire A515-51G             | [5ef831db31](https://linux-hardware.org/?probe=5ef831db31) | Dec 02, 2020 |
| HP            | Pavilion dv6                | [38d1338392](https://linux-hardware.org/?probe=38d1338392) | Dec 02, 2020 |
| HP            | Pavilion dv6                | [fa9afce5c3](https://linux-hardware.org/?probe=fa9afce5c3) | Dec 02, 2020 |
| HP            | Laptop 15-ra0xx             | [b4b9f9d397](https://linux-hardware.org/?probe=b4b9f9d397) | Dec 02, 2020 |
| HP            | Laptop 15-ra0xx             | [4a0f3ebf74](https://linux-hardware.org/?probe=4a0f3ebf74) | Dec 02, 2020 |
| Lenovo        | G50-30 80G0                 | [ea306050eb](https://linux-hardware.org/?probe=ea306050eb) | Dec 01, 2020 |
| Lenovo        | G50-30 80G0                 | [de79017e16](https://linux-hardware.org/?probe=de79017e16) | Dec 01, 2020 |
| HP            | ProBook 4510s               | [9ebf817fd1](https://linux-hardware.org/?probe=9ebf817fd1) | Dec 01, 2020 |
| Fujitsu Si... | AMILO Li3710                | [9d462e3ce2](https://linux-hardware.org/?probe=9d462e3ce2) | Dec 01, 2020 |
| ASUSTek       | K54L                        | [2013a05582](https://linux-hardware.org/?probe=2013a05582) | Dec 01, 2020 |
| Fujitsu Si... | AMILO Li3710                | [c4b77f4529](https://linux-hardware.org/?probe=c4b77f4529) | Dec 01, 2020 |
| Dell          | Latitude 3330               | [bc07e493f9](https://linux-hardware.org/?probe=bc07e493f9) | Nov 30, 2020 |
| HP            | Compaq Presario CQ70        | [731f2e58f3](https://linux-hardware.org/?probe=731f2e58f3) | Nov 30, 2020 |
| HP            | ProBook 4510s               | [ce4302caf8](https://linux-hardware.org/?probe=ce4302caf8) | Nov 30, 2020 |
| Toshiba       | Satellite C70D-B            | [a9a8e81621](https://linux-hardware.org/?probe=a9a8e81621) | Nov 30, 2020 |
| Dell          | Precision M4800             | [f5d9e0ee82](https://linux-hardware.org/?probe=f5d9e0ee82) | Nov 29, 2020 |
| Dell          | Latitude D630               | [b93effc5c1](https://linux-hardware.org/?probe=b93effc5c1) | Nov 29, 2020 |
| Toshiba       | Satellite C50D-A-11M        | [e9ce7ac669](https://linux-hardware.org/?probe=e9ce7ac669) | Nov 29, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [6e5d6641f8](https://linux-hardware.org/?probe=6e5d6641f8) | Nov 29, 2020 |
| Toshiba       | Satellite C50D-A-11M        | [cdd71a9145](https://linux-hardware.org/?probe=cdd71a9145) | Nov 29, 2020 |
| Samsung       | 300E4C/300E5C/300E7C        | [9ef458d79b](https://linux-hardware.org/?probe=9ef458d79b) | Nov 29, 2020 |
| Samsung       | 300E4C/300E5C/300E7C        | [40ff247d5b](https://linux-hardware.org/?probe=40ff247d5b) | Nov 29, 2020 |
| HP            | Laptop 17-ak0xx             | [127da8d94b](https://linux-hardware.org/?probe=127da8d94b) | Nov 29, 2020 |
| Acer          | Aspire V5-121               | [0da1b79137](https://linux-hardware.org/?probe=0da1b79137) | Nov 29, 2020 |
| Acer          | Aspire V5-121               | [39bf9b7d6b](https://linux-hardware.org/?probe=39bf9b7d6b) | Nov 29, 2020 |
| HP            | ProBook 4510s               | [9d7796813c](https://linux-hardware.org/?probe=9d7796813c) | Nov 29, 2020 |
| Dell          | Precision M4800             | [376253c81b](https://linux-hardware.org/?probe=376253c81b) | Nov 29, 2020 |
| ASUSTek       | X541UJ                      | [db16fe45e5](https://linux-hardware.org/?probe=db16fe45e5) | Nov 28, 2020 |
| HP            | Laptop 15-da1xxx            | [690652480a](https://linux-hardware.org/?probe=690652480a) | Nov 28, 2020 |
| Toshiba       | NB550D                      | [d84dc0a8be](https://linux-hardware.org/?probe=d84dc0a8be) | Nov 28, 2020 |
| MSI           | GX720                       | [7a72676992](https://linux-hardware.org/?probe=7a72676992) | Nov 28, 2020 |
| MSI           | GX720                       | [50249ef7ec](https://linux-hardware.org/?probe=50249ef7ec) | Nov 28, 2020 |
| Lenovo        | G50-30 80G0                 | [e15310855c](https://linux-hardware.org/?probe=e15310855c) | Nov 28, 2020 |
| HP            | EliteBook 2540p             | [c02afe9dff](https://linux-hardware.org/?probe=c02afe9dff) | Nov 28, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [8c059ee43a](https://linux-hardware.org/?probe=8c059ee43a) | Nov 27, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [bee87843f6](https://linux-hardware.org/?probe=bee87843f6) | Nov 27, 2020 |
| Lenovo        | G550 20023                  | [2101abe01a](https://linux-hardware.org/?probe=2101abe01a) | Nov 27, 2020 |
| HP            | Compaq 6530b (NJ641UC#AB... | [eff4e0824b](https://linux-hardware.org/?probe=eff4e0824b) | Nov 27, 2020 |
| ASUSTek       | K53SK                       | [dd2db2307a](https://linux-hardware.org/?probe=dd2db2307a) | Nov 26, 2020 |
| Dell          | Latitude 5310               | [b941f2a157](https://linux-hardware.org/?probe=b941f2a157) | Nov 25, 2020 |
| HP            | 255 G2                      | [53ade96366](https://linux-hardware.org/?probe=53ade96366) | Nov 25, 2020 |
| Packard Be... | EasyNote TJ65               | [5513a9f382](https://linux-hardware.org/?probe=5513a9f382) | Nov 24, 2020 |
| Apple         | MacBookAir5,2               | [8137c0e671](https://linux-hardware.org/?probe=8137c0e671) | Nov 23, 2020 |
| Apple         | MacBookAir5,2               | [ea27a8b6d0](https://linux-hardware.org/?probe=ea27a8b6d0) | Nov 23, 2020 |
| ASUSTek       | UX305FA                     | [6644c4537d](https://linux-hardware.org/?probe=6644c4537d) | Nov 23, 2020 |
| ASUSTek       | UX305FA                     | [966cb11e8c](https://linux-hardware.org/?probe=966cb11e8c) | Nov 23, 2020 |
| Dell          | Inspiron 7577               | [0457a9af60](https://linux-hardware.org/?probe=0457a9af60) | Nov 22, 2020 |
| HP            | 250 G1                      | [b3bbb9f8c7](https://linux-hardware.org/?probe=b3bbb9f8c7) | Nov 22, 2020 |
| HP            | 250 G1                      | [e596417714](https://linux-hardware.org/?probe=e596417714) | Nov 22, 2020 |
| HP            | 250 G1                      | [66202ab0a3](https://linux-hardware.org/?probe=66202ab0a3) | Nov 22, 2020 |
| HP            | 250 G1                      | [73f41fd5c2](https://linux-hardware.org/?probe=73f41fd5c2) | Nov 22, 2020 |
| HP            | 250 G1                      | [b4940889f4](https://linux-hardware.org/?probe=b4940889f4) | Nov 22, 2020 |
| HP            | 250 G1                      | [38e86cb449](https://linux-hardware.org/?probe=38e86cb449) | Nov 22, 2020 |
| Acer          | Aspire A715-71G             | [66fccfbf35](https://linux-hardware.org/?probe=66fccfbf35) | Nov 22, 2020 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [314a356b32](https://linux-hardware.org/?probe=314a356b32) | Nov 22, 2020 |
| HP            | 250 G1                      | [e0c3ec4cff](https://linux-hardware.org/?probe=e0c3ec4cff) | Nov 22, 2020 |
| HP            | 250 G1                      | [db9f898d6a](https://linux-hardware.org/?probe=db9f898d6a) | Nov 22, 2020 |
| HP            | 250 G1                      | [df2c67173b](https://linux-hardware.org/?probe=df2c67173b) | Nov 22, 2020 |
| HP            | 250 G1                      | [e33e058e5b](https://linux-hardware.org/?probe=e33e058e5b) | Nov 22, 2020 |
| HP            | 250 G1                      | [65e41a1346](https://linux-hardware.org/?probe=65e41a1346) | Nov 22, 2020 |
| HP            | 250 G1                      | [63cce65c34](https://linux-hardware.org/?probe=63cce65c34) | Nov 22, 2020 |
| HP            | ProBook 6450b               | [8eaf59db41](https://linux-hardware.org/?probe=8eaf59db41) | Nov 22, 2020 |
| Toshiba       | Satellite Pro L300          | [f8b3366ea0](https://linux-hardware.org/?probe=f8b3366ea0) | Nov 22, 2020 |
| ASUSTek       | G752VY                      | [d7d0f64b0c](https://linux-hardware.org/?probe=d7d0f64b0c) | Nov 22, 2020 |
| ASUSTek       | G752VY                      | [225f411e3d](https://linux-hardware.org/?probe=225f411e3d) | Nov 21, 2020 |
| HP            | ProBook 6450b               | [f070695d52](https://linux-hardware.org/?probe=f070695d52) | Nov 21, 2020 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [6e6bb4eef2](https://linux-hardware.org/?probe=6e6bb4eef2) | Nov 21, 2020 |
| HP            | 250 G1                      | [cbe6c3767c](https://linux-hardware.org/?probe=cbe6c3767c) | Nov 21, 2020 |
| HP            | 250 G1                      | [135fba12b0](https://linux-hardware.org/?probe=135fba12b0) | Nov 21, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [21df7cf0bf](https://linux-hardware.org/?probe=21df7cf0bf) | Nov 21, 2020 |
| ASUSTek       | K53SK                       | [a4e2616410](https://linux-hardware.org/?probe=a4e2616410) | Nov 21, 2020 |
| Toshiba       | Satellite L750              | [1357d5a302](https://linux-hardware.org/?probe=1357d5a302) | Nov 21, 2020 |
| Acer          | Aspire 5745G                | [e697e86626](https://linux-hardware.org/?probe=e697e86626) | Nov 21, 2020 |
| Medion        | Unknown                     | [6cc7e51747](https://linux-hardware.org/?probe=6cc7e51747) | Nov 20, 2020 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [cc2b24605a](https://linux-hardware.org/?probe=cc2b24605a) | Nov 20, 2020 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [1869593cdb](https://linux-hardware.org/?probe=1869593cdb) | Nov 20, 2020 |
| Acer          | Extensa 5620                | [b5ede5c96b](https://linux-hardware.org/?probe=b5ede5c96b) | Nov 20, 2020 |
| Dell          | Latitude E6400              | [6861789d99](https://linux-hardware.org/?probe=6861789d99) | Nov 20, 2020 |
| Acer          | Extensa 5620                | [73352df219](https://linux-hardware.org/?probe=73352df219) | Nov 20, 2020 |
| Dell          | Latitude E6400              | [4d35331393](https://linux-hardware.org/?probe=4d35331393) | Nov 20, 2020 |
| HP            | EliteBook 8540p             | [d9ca357ad7](https://linux-hardware.org/?probe=d9ca357ad7) | Nov 20, 2020 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [fdd7c714b5](https://linux-hardware.org/?probe=fdd7c714b5) | Nov 19, 2020 |
| Lenovo        | 3000 G530 444622G           | [0d985dc8b1](https://linux-hardware.org/?probe=0d985dc8b1) | Nov 19, 2020 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [66cd39bdfb](https://linux-hardware.org/?probe=66cd39bdfb) | Nov 19, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e9e0b4e8a8](https://linux-hardware.org/?probe=e9e0b4e8a8) | Nov 18, 2020 |
| Acer          | Aspire one                  | [ee70b34093](https://linux-hardware.org/?probe=ee70b34093) | Nov 18, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [6a3b7a867a](https://linux-hardware.org/?probe=6a3b7a867a) | Nov 18, 2020 |
| HP            | 250 G1                      | [909f88604f](https://linux-hardware.org/?probe=909f88604f) | Nov 17, 2020 |
| HP            | EliteBook 2540p             | [c5324cbe9f](https://linux-hardware.org/?probe=c5324cbe9f) | Nov 17, 2020 |
| HP            | 250 G1                      | [7fd18cdfeb](https://linux-hardware.org/?probe=7fd18cdfeb) | Nov 16, 2020 |
| HP            | 250 G1                      | [e0067597a7](https://linux-hardware.org/?probe=e0067597a7) | Nov 16, 2020 |
| HP            | 250 G1                      | [67eba59bfe](https://linux-hardware.org/?probe=67eba59bfe) | Nov 16, 2020 |
| Medion        | Unknown                     | [bce8626f48](https://linux-hardware.org/?probe=bce8626f48) | Nov 15, 2020 |
| Lenovo        | ThinkPad T410 253723G       | [d1d3998f45](https://linux-hardware.org/?probe=d1d3998f45) | Nov 15, 2020 |
| Lenovo        | ThinkPad T410 253723G       | [ec4e9009af](https://linux-hardware.org/?probe=ec4e9009af) | Nov 15, 2020 |
| Acer          | Aspire A315-54K             | [17d065565e](https://linux-hardware.org/?probe=17d065565e) | Nov 15, 2020 |
| Acer          | Aspire A315-54K             | [c917123a0e](https://linux-hardware.org/?probe=c917123a0e) | Nov 15, 2020 |
| Acer          | Aspire 8930                 | [24e3233d7a](https://linux-hardware.org/?probe=24e3233d7a) | Nov 15, 2020 |
| Acer          | Aspire V3-772               | [53f0d7b945](https://linux-hardware.org/?probe=53f0d7b945) | Nov 15, 2020 |
| Lenovo        | G585 20137                  | [954b3568e6](https://linux-hardware.org/?probe=954b3568e6) | Nov 14, 2020 |
| Lenovo        | ThinkPad T61 6458WK6        | [b400bd3c48](https://linux-hardware.org/?probe=b400bd3c48) | Nov 14, 2020 |
| HP            | Compaq nx9420 (RU480ET#A... | [3ffd093a67](https://linux-hardware.org/?probe=3ffd093a67) | Nov 14, 2020 |
| Fujitsu Si... | LIFEBOOK S7210              | [19df86707e](https://linux-hardware.org/?probe=19df86707e) | Nov 13, 2020 |
| Lenovo        | G50-30 80G0                 | [98a6788ce9](https://linux-hardware.org/?probe=98a6788ce9) | Nov 13, 2020 |
| Acer          | Aspire 5745G                | [62cbade85e](https://linux-hardware.org/?probe=62cbade85e) | Nov 13, 2020 |
| Acer          | Aspire 5745G                | [92ce5f634e](https://linux-hardware.org/?probe=92ce5f634e) | Nov 13, 2020 |
| HP            | Unknown                     | [f470a75dfe](https://linux-hardware.org/?probe=f470a75dfe) | Nov 13, 2020 |
| HP            | Compaq 6730s                | [8e9654126d](https://linux-hardware.org/?probe=8e9654126d) | Nov 13, 2020 |
| HP            | EliteBook 8540p             | [1df463aa08](https://linux-hardware.org/?probe=1df463aa08) | Nov 13, 2020 |
| Lenovo        | G50-30 80G0                 | [aa5c8505dc](https://linux-hardware.org/?probe=aa5c8505dc) | Nov 12, 2020 |
| Dell          | Inspiron 3542               | [474f6dc3cd](https://linux-hardware.org/?probe=474f6dc3cd) | Nov 12, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [78d0a27bf0](https://linux-hardware.org/?probe=78d0a27bf0) | Nov 12, 2020 |
| HP            | 250 G1                      | [7d00459686](https://linux-hardware.org/?probe=7d00459686) | Nov 12, 2020 |
| HP            | 250 G4                      | [45ff9070b8](https://linux-hardware.org/?probe=45ff9070b8) | Nov 12, 2020 |
| HP            | 250 G1                      | [559400d348](https://linux-hardware.org/?probe=559400d348) | Nov 12, 2020 |
| eMachines     | Rhine V1.44                 | [c5af2df9bc](https://linux-hardware.org/?probe=c5af2df9bc) | Nov 11, 2020 |
| HP            | EliteBook 8570p             | [d4ac12ab42](https://linux-hardware.org/?probe=d4ac12ab42) | Nov 11, 2020 |
| Dell          | Latitude E6420              | [9b397c378e](https://linux-hardware.org/?probe=9b397c378e) | Nov 11, 2020 |
| HP            | EliteBook 8540p             | [6a0b95782d](https://linux-hardware.org/?probe=6a0b95782d) | Nov 11, 2020 |
| Acer          | Aspire 5745G                | [a533350727](https://linux-hardware.org/?probe=a533350727) | Nov 10, 2020 |
| Lenovo        | G585 20137                  | [9c7693245c](https://linux-hardware.org/?probe=9c7693245c) | Nov 10, 2020 |
| HP            | 255 G2                      | [8d2c4c0826](https://linux-hardware.org/?probe=8d2c4c0826) | Nov 10, 2020 |
| HP            | EliteBook 8540p             | [a3264597e8](https://linux-hardware.org/?probe=a3264597e8) | Nov 10, 2020 |
| Packard Be... | EasyNote MB87               | [004c9d1fa7](https://linux-hardware.org/?probe=004c9d1fa7) | Nov 09, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [aacbf98a23](https://linux-hardware.org/?probe=aacbf98a23) | Nov 09, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0a94255cd7](https://linux-hardware.org/?probe=0a94255cd7) | Nov 09, 2020 |
| HP            | Compaq nc6320 (RH368EA#A... | [146d8409d7](https://linux-hardware.org/?probe=146d8409d7) | Nov 09, 2020 |
| ASUSTek       | X201EP                      | [221566c86d](https://linux-hardware.org/?probe=221566c86d) | Nov 09, 2020 |
| ASUSTek       | X201EP                      | [f70a0508e1](https://linux-hardware.org/?probe=f70a0508e1) | Nov 09, 2020 |
| Packard Be... | EasyNote TK81               | [8d407e72c0](https://linux-hardware.org/?probe=8d407e72c0) | Nov 09, 2020 |
| Dell          | Latitude E6530              | [3d606b3078](https://linux-hardware.org/?probe=3d606b3078) | Nov 09, 2020 |
| HP            | 250 G1                      | [be5abac629](https://linux-hardware.org/?probe=be5abac629) | Nov 09, 2020 |
| ASUSTek       | ROG Strix G531GV_G531GV     | [e57921a880](https://linux-hardware.org/?probe=e57921a880) | Nov 09, 2020 |
| ASUSTek       | ROG Strix G531GV_G531GV     | [cdd96c128f](https://linux-hardware.org/?probe=cdd96c128f) | Nov 08, 2020 |
| IBM           | Unknown                     | [ddf98baf67](https://linux-hardware.org/?probe=ddf98baf67) | Nov 08, 2020 |
| HP            | ProBook 4510s               | [c4da38504a](https://linux-hardware.org/?probe=c4da38504a) | Nov 08, 2020 |
| ASUSTek       | UX32VD                      | [a84706c108](https://linux-hardware.org/?probe=a84706c108) | Nov 08, 2020 |
| Dell          | Inspiron N5050              | [d5dc14532e](https://linux-hardware.org/?probe=d5dc14532e) | Nov 07, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [f0868a3007](https://linux-hardware.org/?probe=f0868a3007) | Nov 07, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [35ababaa99](https://linux-hardware.org/?probe=35ababaa99) | Nov 07, 2020 |
| ASUSTek       | UX32VD                      | [4b635b4f2b](https://linux-hardware.org/?probe=4b635b4f2b) | Nov 07, 2020 |
| Dell          | Vostro 3350                 | [06a3c722c2](https://linux-hardware.org/?probe=06a3c722c2) | Nov 07, 2020 |
| Acer          | Aspire A114-31              | [675381f7b3](https://linux-hardware.org/?probe=675381f7b3) | Nov 06, 2020 |
| Dell          | Vostro 3350                 | [4dc00fd38e](https://linux-hardware.org/?probe=4dc00fd38e) | Nov 06, 2020 |
| Dell          | Vostro 3350                 | [b24afb086f](https://linux-hardware.org/?probe=b24afb086f) | Nov 06, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [517f296618](https://linux-hardware.org/?probe=517f296618) | Nov 05, 2020 |
| Toshiba       | Satellite L750              | [34721ce733](https://linux-hardware.org/?probe=34721ce733) | Nov 05, 2020 |
| HP            | 255 G2                      | [8da2baba47](https://linux-hardware.org/?probe=8da2baba47) | Nov 05, 2020 |
| HP            | 250 G1                      | [8537c39cae](https://linux-hardware.org/?probe=8537c39cae) | Nov 05, 2020 |
| HP            | 250 G1                      | [7921c02e99](https://linux-hardware.org/?probe=7921c02e99) | Nov 05, 2020 |
| Lenovo        | IdeaPad 3 17ARE05 81W5      | [8b35ff9c88](https://linux-hardware.org/?probe=8b35ff9c88) | Nov 05, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [f04c475c87](https://linux-hardware.org/?probe=f04c475c87) | Nov 03, 2020 |
| Acer          | Aspire E5-772G              | [5a898c1812](https://linux-hardware.org/?probe=5a898c1812) | Nov 02, 2020 |
| Acer          | Aspire E5-772G              | [7a61db9db9](https://linux-hardware.org/?probe=7a61db9db9) | Nov 02, 2020 |
| HP            | 250 G3                      | [8f9843ca68](https://linux-hardware.org/?probe=8f9843ca68) | Nov 02, 2020 |
| Medion        | Unknown                     | [c7701aa4af](https://linux-hardware.org/?probe=c7701aa4af) | Nov 02, 2020 |
| Lenovo        | ThinkPad L450 20DSS1X52L    | [dc2c531b35](https://linux-hardware.org/?probe=dc2c531b35) | Nov 01, 2020 |
| Lenovo        | ThinkPad L450 20DSS1X52L    | [850cdbed76](https://linux-hardware.org/?probe=850cdbed76) | Nov 01, 2020 |
| HP            | 650                         | [07b95d5d88](https://linux-hardware.org/?probe=07b95d5d88) | Nov 01, 2020 |
| HP            | Pavilion Notebook           | [c41845981b](https://linux-hardware.org/?probe=c41845981b) | Nov 01, 2020 |
| HP            | 650                         | [d08f4fbf95](https://linux-hardware.org/?probe=d08f4fbf95) | Nov 01, 2020 |
| HP            | Pavilion Notebook           | [7a1fd75c56](https://linux-hardware.org/?probe=7a1fd75c56) | Nov 01, 2020 |
| Lenovo        | IdeaPad 3 17ARE05 81W5      | [a15c0be22a](https://linux-hardware.org/?probe=a15c0be22a) | Nov 01, 2020 |
| Lenovo        | IdeaPad 3 17ARE05 81W5      | [b428ee0e38](https://linux-hardware.org/?probe=b428ee0e38) | Nov 01, 2020 |
| Alcor         | Flashbook D1423I            | [1ecc856ca2](https://linux-hardware.org/?probe=1ecc856ca2) | Oct 31, 2020 |
| Lenovo        | ThinkPad T440p 20AWS16U0... | [8c6e1506b5](https://linux-hardware.org/?probe=8c6e1506b5) | Oct 31, 2020 |
| Lenovo        | ThinkPad T440p 20AWS16U0... | [0866254476](https://linux-hardware.org/?probe=0866254476) | Oct 31, 2020 |
| Lenovo        | G580 20150                  | [4c611ea003](https://linux-hardware.org/?probe=4c611ea003) | Oct 31, 2020 |
| ASUSTek       | GL702VSK                    | [613f5982d9](https://linux-hardware.org/?probe=613f5982d9) | Oct 31, 2020 |
| HP            | 255 G2                      | [eed8f6b472](https://linux-hardware.org/?probe=eed8f6b472) | Oct 30, 2020 |
| Lenovo        | ThinkPad X230 2325AT6       | [fb2baece47](https://linux-hardware.org/?probe=fb2baece47) | Oct 29, 2020 |
| ASUSTek       | X541UVK                     | [bfa0b2b521](https://linux-hardware.org/?probe=bfa0b2b521) | Oct 29, 2020 |
| ASUSTek       | X541UVK                     | [405d022f51](https://linux-hardware.org/?probe=405d022f51) | Oct 29, 2020 |
| ASUSTek       | X540LA                      | [c5bfef2a87](https://linux-hardware.org/?probe=c5bfef2a87) | Oct 28, 2020 |
| Acer          | Aspire ES1-531              | [fb1db58c15](https://linux-hardware.org/?probe=fb1db58c15) | Oct 28, 2020 |
| HP            | Compaq 8710p (GC100EA#AB... | [9355c0eac9](https://linux-hardware.org/?probe=9355c0eac9) | Oct 27, 2020 |
| Dell          | G3 3579                     | [fd89a0651f](https://linux-hardware.org/?probe=fd89a0651f) | Oct 27, 2020 |
| Dell          | Latitude E5410              | [030406a017](https://linux-hardware.org/?probe=030406a017) | Oct 27, 2020 |
| Dell          | Latitude E5410              | [ae2d38870e](https://linux-hardware.org/?probe=ae2d38870e) | Oct 27, 2020 |
| Acer          | Aspire V3-531               | [0c32fdfa48](https://linux-hardware.org/?probe=0c32fdfa48) | Oct 26, 2020 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [a071445291](https://linux-hardware.org/?probe=a071445291) | Oct 26, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [a181bab42e](https://linux-hardware.org/?probe=a181bab42e) | Oct 26, 2020 |
| ASUSTek       | K50IJ                       | [41d94ba840](https://linux-hardware.org/?probe=41d94ba840) | Oct 25, 2020 |
| Lenovo        | ThinkPad T480 20L50004HV    | [34e897ac40](https://linux-hardware.org/?probe=34e897ac40) | Oct 25, 2020 |
| Lenovo        | G50-45 80E3                 | [01b35d7467](https://linux-hardware.org/?probe=01b35d7467) | Oct 25, 2020 |
| Acer          | Aspire ES1-511              | [471f0ec3d6](https://linux-hardware.org/?probe=471f0ec3d6) | Oct 25, 2020 |
| HP            | EliteBook 8460p             | [83d1965847](https://linux-hardware.org/?probe=83d1965847) | Oct 25, 2020 |
| Acer          | Aspire ES1-511              | [9d6ac47af5](https://linux-hardware.org/?probe=9d6ac47af5) | Oct 25, 2020 |
| HP            | 620                         | [52d7c81419](https://linux-hardware.org/?probe=52d7c81419) | Oct 25, 2020 |
| ASUSTek       | X55U                        | [db9b7304c2](https://linux-hardware.org/?probe=db9b7304c2) | Oct 25, 2020 |
| Lenovo        | ThinkPad X230 2325AC7       | [84f608bcec](https://linux-hardware.org/?probe=84f608bcec) | Oct 24, 2020 |
| ASUSTek       | X556UQ                      | [952525adc3](https://linux-hardware.org/?probe=952525adc3) | Oct 24, 2020 |
| ASUSTek       | X556UQ                      | [16b7ef2bad](https://linux-hardware.org/?probe=16b7ef2bad) | Oct 24, 2020 |
| ASUSTek       | K50IJ                       | [a92adf353f](https://linux-hardware.org/?probe=a92adf353f) | Oct 24, 2020 |
| Dell          | Inspiron 15-3573            | [f44afb87f4](https://linux-hardware.org/?probe=f44afb87f4) | Oct 24, 2020 |
| Dell          | Inspiron 15-3573            | [e1c6f99cb1](https://linux-hardware.org/?probe=e1c6f99cb1) | Oct 24, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [039fb44636](https://linux-hardware.org/?probe=039fb44636) | Oct 24, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [692bf25870](https://linux-hardware.org/?probe=692bf25870) | Oct 24, 2020 |
| Dell          | Inspiron 1110               | [62092186ca](https://linux-hardware.org/?probe=62092186ca) | Oct 23, 2020 |
| ASUSTek       | X555SJ                      | [055675c5c1](https://linux-hardware.org/?probe=055675c5c1) | Oct 23, 2020 |
| Lenovo        | ThinkPad W510 4389A44       | [3bf23c9317](https://linux-hardware.org/?probe=3bf23c9317) | Oct 23, 2020 |
| Acer          | Aspire E5-522G              | [4ba3d57eb8](https://linux-hardware.org/?probe=4ba3d57eb8) | Oct 23, 2020 |
| Lenovo        | ThinkPad E15 20RD0069HV     | [f8496d57cd](https://linux-hardware.org/?probe=f8496d57cd) | Oct 23, 2020 |
| Dell          | Vostro 1015                 | [d8665102c0](https://linux-hardware.org/?probe=d8665102c0) | Oct 23, 2020 |
| Acer          | Aspire E5-522G              | [3a49431dbd](https://linux-hardware.org/?probe=3a49431dbd) | Oct 23, 2020 |
| eMachines     | E725                        | [ba8ca77e06](https://linux-hardware.org/?probe=ba8ca77e06) | Oct 23, 2020 |
| ASUSTek       | X555SJ                      | [723bbf8486](https://linux-hardware.org/?probe=723bbf8486) | Oct 23, 2020 |
| ASUSTek       | K50IJ                       | [4ff1d3656b](https://linux-hardware.org/?probe=4ff1d3656b) | Oct 22, 2020 |
| ASUSTek       | K50IJ                       | [0fbbb2e687](https://linux-hardware.org/?probe=0fbbb2e687) | Oct 22, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [88aa6bddcd](https://linux-hardware.org/?probe=88aa6bddcd) | Oct 21, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [bd22dae2d0](https://linux-hardware.org/?probe=bd22dae2d0) | Oct 21, 2020 |
| ASUSTek       | X540LA                      | [115f22ec2d](https://linux-hardware.org/?probe=115f22ec2d) | Oct 21, 2020 |
| Acer          | Aspire 5755G                | [10953e9414](https://linux-hardware.org/?probe=10953e9414) | Oct 21, 2020 |
| MSI           | M670                        | [4ef9bcc780](https://linux-hardware.org/?probe=4ef9bcc780) | Oct 21, 2020 |
| MSI           | M670                        | [57e5943c8c](https://linux-hardware.org/?probe=57e5943c8c) | Oct 21, 2020 |
| ASUSTek       | X751SJ                      | [0ca73f1022](https://linux-hardware.org/?probe=0ca73f1022) | Oct 21, 2020 |
| ASUSTek       | X541SA                      | [62c14c2d23](https://linux-hardware.org/?probe=62c14c2d23) | Oct 21, 2020 |
| ASUSTek       | X751SJ                      | [357df9aca0](https://linux-hardware.org/?probe=357df9aca0) | Oct 20, 2020 |
| Toshiba       | TECRA A10                   | [f75ac94851](https://linux-hardware.org/?probe=f75ac94851) | Oct 19, 2020 |
| Acer          | Aspire A315-41              | [4de8d1be4b](https://linux-hardware.org/?probe=4de8d1be4b) | Oct 19, 2020 |
| ASUSTek       | F3F                         | [a4cf3b1e1d](https://linux-hardware.org/?probe=a4cf3b1e1d) | Oct 19, 2020 |
| Samsung       | R519/R719                   | [0018fa7eee](https://linux-hardware.org/?probe=0018fa7eee) | Oct 19, 2020 |
| Samsung       | R519/R719                   | [fc6eefb607](https://linux-hardware.org/?probe=fc6eefb607) | Oct 19, 2020 |
| Acer          | Aspire A315-41              | [6c5dcbb906](https://linux-hardware.org/?probe=6c5dcbb906) | Oct 19, 2020 |
| HP            | Compaq nc6320 (RH368EA#A... | [2cbc90e7de](https://linux-hardware.org/?probe=2cbc90e7de) | Oct 18, 2020 |
| Toshiba       | Satellite C50D-A-10H        | [46eec06de5](https://linux-hardware.org/?probe=46eec06de5) | Oct 18, 2020 |
| HP            | EliteBook 8470p             | [1a049977b7](https://linux-hardware.org/?probe=1a049977b7) | Oct 18, 2020 |
| Acer          | Aspire 5755G                | [1e5e1826b8](https://linux-hardware.org/?probe=1e5e1826b8) | Oct 18, 2020 |
| HP            | Notebook                    | [f828800ef0](https://linux-hardware.org/?probe=f828800ef0) | Oct 18, 2020 |
| Lenovo        | Z50-70 20354                | [5fb91bed81](https://linux-hardware.org/?probe=5fb91bed81) | Oct 17, 2020 |
| Lenovo        | Z50-70 20354                | [b76fdf709b](https://linux-hardware.org/?probe=b76fdf709b) | Oct 17, 2020 |
| Toshiba       | Satellite C50D-A-10H        | [01c2c5f7f8](https://linux-hardware.org/?probe=01c2c5f7f8) | Oct 17, 2020 |
| Dell          | Inspiron 1545               | [9c648dd410](https://linux-hardware.org/?probe=9c648dd410) | Oct 17, 2020 |
| Lenovo        | G50-45 80E3                 | [2906ab6483](https://linux-hardware.org/?probe=2906ab6483) | Oct 16, 2020 |
| Lenovo        | G50-45 80E3                 | [81e1a7c77b](https://linux-hardware.org/?probe=81e1a7c77b) | Oct 16, 2020 |
| HP            | 655                         | [8d521629e4](https://linux-hardware.org/?probe=8d521629e4) | Oct 16, 2020 |
| Acer          | Aspire A315-54K             | [adc0430521](https://linux-hardware.org/?probe=adc0430521) | Oct 15, 2020 |
| Acer          | Aspire A315-42              | [e9bbf7ab66](https://linux-hardware.org/?probe=e9bbf7ab66) | Oct 15, 2020 |
| Acer          | Aspire A315-42              | [3ac7787e1a](https://linux-hardware.org/?probe=3ac7787e1a) | Oct 15, 2020 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [04938ec3c9](https://linux-hardware.org/?probe=04938ec3c9) | Oct 15, 2020 |
| HP            | EliteBook 8460p             | [efc5e42972](https://linux-hardware.org/?probe=efc5e42972) | Oct 15, 2020 |
| Sony          | VPCEB1E1E                   | [cbd4fefba6](https://linux-hardware.org/?probe=cbd4fefba6) | Oct 14, 2020 |
| HP            | Compaq 6710b (KE121EA#AK... | [3f1e352f39](https://linux-hardware.org/?probe=3f1e352f39) | Oct 14, 2020 |
| Lenovo        | ThinkPad T520 4243GE9       | [d4a560f987](https://linux-hardware.org/?probe=d4a560f987) | Oct 14, 2020 |
| Acer          | Aspire ES1-571              | [1eaefc7e04](https://linux-hardware.org/?probe=1eaefc7e04) | Oct 13, 2020 |
| HP            | 250 G1                      | [9d22d73548](https://linux-hardware.org/?probe=9d22d73548) | Oct 12, 2020 |
| HP            | 250 G1                      | [caf9970d05](https://linux-hardware.org/?probe=caf9970d05) | Oct 12, 2020 |
| Lenovo        | Z50-70 20354                | [b8d993427d](https://linux-hardware.org/?probe=b8d993427d) | Oct 12, 2020 |
| Acer          | Aspire ES1-571              | [88306a05b4](https://linux-hardware.org/?probe=88306a05b4) | Oct 12, 2020 |
| Lenovo        | Z50-70 20354                | [387d3bf936](https://linux-hardware.org/?probe=387d3bf936) | Oct 11, 2020 |
| Lenovo        | ThinkPad X61 7673BW3        | [8e0342ed4f](https://linux-hardware.org/?probe=8e0342ed4f) | Oct 11, 2020 |
| Lenovo        | ThinkPad X61 7673BW3        | [675ac103c5](https://linux-hardware.org/?probe=675ac103c5) | Oct 11, 2020 |
| ASUSTek       | 1201N                       | [15d97a9353](https://linux-hardware.org/?probe=15d97a9353) | Oct 11, 2020 |
| ASUSTek       | 1201N                       | [3ef9d56dc5](https://linux-hardware.org/?probe=3ef9d56dc5) | Oct 11, 2020 |
| Acer          | Aspire A315-54K             | [be2952e600](https://linux-hardware.org/?probe=be2952e600) | Oct 09, 2020 |
| ASUSTek       | X402CA                      | [b2b269d822](https://linux-hardware.org/?probe=b2b269d822) | Oct 09, 2020 |
| ASUSTek       | X402CA                      | [16cf7025b0](https://linux-hardware.org/?probe=16cf7025b0) | Oct 09, 2020 |
| Dell          | Latitude E6430              | [d51aec6b61](https://linux-hardware.org/?probe=d51aec6b61) | Oct 09, 2020 |
| Acer          | AOD257                      | [dc05d7202b](https://linux-hardware.org/?probe=dc05d7202b) | Oct 07, 2020 |
| Toshiba       | Satellite L300              | [58d5ec31bb](https://linux-hardware.org/?probe=58d5ec31bb) | Oct 07, 2020 |
| Toshiba       | Satellite L300              | [17f8ebc0ff](https://linux-hardware.org/?probe=17f8ebc0ff) | Oct 07, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [05598c35df](https://linux-hardware.org/?probe=05598c35df) | Oct 07, 2020 |
| HP            | Compaq nx7400 (RH412EA#A... | [e407430195](https://linux-hardware.org/?probe=e407430195) | Oct 07, 2020 |
| Dell          | Inspiron 7559               | [385e62f20e](https://linux-hardware.org/?probe=385e62f20e) | Oct 07, 2020 |
| Dell          | Inspiron 15-3567            | [686fcd1775](https://linux-hardware.org/?probe=686fcd1775) | Oct 06, 2020 |
| Dell          | Inspiron 15-3567            | [f8f1202815](https://linux-hardware.org/?probe=f8f1202815) | Oct 06, 2020 |
| Lenovo        | ThinkPad T440s 20ARS0BH0... | [0872481f4a](https://linux-hardware.org/?probe=0872481f4a) | Oct 06, 2020 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [4bdb222c7e](https://linux-hardware.org/?probe=4bdb222c7e) | Oct 06, 2020 |
| Dell          | Latitude E6430              | [853a19b0da](https://linux-hardware.org/?probe=853a19b0da) | Oct 06, 2020 |
| HP            | ZBook 15 G5                 | [be0c71550b](https://linux-hardware.org/?probe=be0c71550b) | Oct 06, 2020 |
| Lenovo        | 3000 G530 444622G           | [f86fb3c189](https://linux-hardware.org/?probe=f86fb3c189) | Oct 05, 2020 |
| Lenovo        | 3000 G530 444622G           | [3c90bf1f15](https://linux-hardware.org/?probe=3c90bf1f15) | Oct 05, 2020 |
| eMachines     | eME728                      | [a9cf9971ed](https://linux-hardware.org/?probe=a9cf9971ed) | Oct 05, 2020 |
| Packard Be... | EasyNote TK81               | [e8a2595183](https://linux-hardware.org/?probe=e8a2595183) | Oct 05, 2020 |
| Lenovo        | ThinkPad L540 20AUA128HV    | [1892d178c6](https://linux-hardware.org/?probe=1892d178c6) | Oct 05, 2020 |
| Acer          | Aspire E1-570G              | [13b54afceb](https://linux-hardware.org/?probe=13b54afceb) | Oct 04, 2020 |
| Acer          | Aspire E1-570G              | [c524e2cc84](https://linux-hardware.org/?probe=c524e2cc84) | Oct 04, 2020 |
| HP            | Notebook                    | [725127fd94](https://linux-hardware.org/?probe=725127fd94) | Oct 04, 2020 |
| MSI           | MS-1672 Ver                 | [503719edc3](https://linux-hardware.org/?probe=503719edc3) | Oct 04, 2020 |
| MSI           | MS-1672 Ver                 | [1bbde8c84f](https://linux-hardware.org/?probe=1bbde8c84f) | Oct 04, 2020 |
| HP            | Pavilion dv6700             | [6b96f8636c](https://linux-hardware.org/?probe=6b96f8636c) | Oct 04, 2020 |
| Dell          | Latitude E6330              | [b379188d3c](https://linux-hardware.org/?probe=b379188d3c) | Oct 04, 2020 |
| ASUSTek       | X55A                        | [17fd11ed65](https://linux-hardware.org/?probe=17fd11ed65) | Oct 04, 2020 |
| Samsung       | RV411/RV511/E3511/S3511/... | [6285ea29da](https://linux-hardware.org/?probe=6285ea29da) | Oct 03, 2020 |
| Samsung       | RV411/RV511/E3511/S3511/... | [4fb391497b](https://linux-hardware.org/?probe=4fb391497b) | Oct 03, 2020 |
| HP            | ProBook 4540s               | [99911be77c](https://linux-hardware.org/?probe=99911be77c) | Oct 02, 2020 |
| Toshiba       | Satellite A200              | [cf7135723d](https://linux-hardware.org/?probe=cf7135723d) | Oct 02, 2020 |
| Dell          | Latitude E6440              | [fd7d0876dd](https://linux-hardware.org/?probe=fd7d0876dd) | Oct 02, 2020 |
| Dell          | Latitude E6440              | [f059e14504](https://linux-hardware.org/?probe=f059e14504) | Oct 02, 2020 |
| HP            | 530                         | [d55c2c396f](https://linux-hardware.org/?probe=d55c2c396f) | Oct 02, 2020 |
| Dell          | Vostro 1510                 | [d9ebf271ea](https://linux-hardware.org/?probe=d9ebf271ea) | Oct 02, 2020 |
| Lenovo        | 3000 N100 07686VG           | [5e31620078](https://linux-hardware.org/?probe=5e31620078) | Oct 02, 2020 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [d19ffbb6b6](https://linux-hardware.org/?probe=d19ffbb6b6) | Oct 01, 2020 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [16e8175178](https://linux-hardware.org/?probe=16e8175178) | Oct 01, 2020 |
| Dell          | Vostro 5581                 | [95a4bb6b5a](https://linux-hardware.org/?probe=95a4bb6b5a) | Oct 01, 2020 |
| HP            | EliteBook 2560p             | [1e8d8c11bd](https://linux-hardware.org/?probe=1e8d8c11bd) | Oct 01, 2020 |
| ASUSTek       | Strix 15 GL503GE            | [e380012053](https://linux-hardware.org/?probe=e380012053) | Oct 01, 2020 |
| HP            | EliteBook 2560p             | [224b783206](https://linux-hardware.org/?probe=224b783206) | Sep 30, 2020 |
| Dell          | Inspiron 3780               | [d92c6e83b3](https://linux-hardware.org/?probe=d92c6e83b3) | Sep 30, 2020 |
| Dell          | Inspiron N5010              | [3c26f539a5](https://linux-hardware.org/?probe=3c26f539a5) | Sep 30, 2020 |
| ASUSTek       | X551CAP                     | [47e7324b87](https://linux-hardware.org/?probe=47e7324b87) | Sep 29, 2020 |
| Lenovo        | ThinkPad W510 431924G       | [28f5d612b7](https://linux-hardware.org/?probe=28f5d612b7) | Sep 29, 2020 |
| ASUSTek       | X551CAP                     | [3add5753e6](https://linux-hardware.org/?probe=3add5753e6) | Sep 29, 2020 |
| ASUSTek       | N550JK                      | [08316445d1](https://linux-hardware.org/?probe=08316445d1) | Sep 29, 2020 |
| HP            | ProBook 4540s               | [c4f70904bf](https://linux-hardware.org/?probe=c4f70904bf) | Sep 29, 2020 |
| ASUSTek       | X551CAP                     | [812f15f371](https://linux-hardware.org/?probe=812f15f371) | Sep 28, 2020 |
| Acer          | Aspire E1-531               | [20ca35bf09](https://linux-hardware.org/?probe=20ca35bf09) | Sep 28, 2020 |
| HP            | EliteBook 2540p (WK303EA... | [90eb71c4f7](https://linux-hardware.org/?probe=90eb71c4f7) | Sep 28, 2020 |
| Lenovo        | ThinkPad T440s 20ARS1QC0... | [af344861d5](https://linux-hardware.org/?probe=af344861d5) | Sep 27, 2020 |
| Acer          | Aspire 7750G                | [f22a2a52f4](https://linux-hardware.org/?probe=f22a2a52f4) | Sep 27, 2020 |
| Hungaro Fl... | Navon Loop 360              | [0c629fde52](https://linux-hardware.org/?probe=0c629fde52) | Sep 27, 2020 |
| Dell          | Inspiron N5110              | [b23e266947](https://linux-hardware.org/?probe=b23e266947) | Sep 27, 2020 |
| Dell          | Latitude E6400              | [67f6c20a2e](https://linux-hardware.org/?probe=67f6c20a2e) | Sep 27, 2020 |
| HP            | Laptop 15-bs0xx             | [5a367b46b2](https://linux-hardware.org/?probe=5a367b46b2) | Sep 27, 2020 |
| Dell          | Inspiron N5110              | [8026151048](https://linux-hardware.org/?probe=8026151048) | Sep 27, 2020 |
| ASUSTek       | N551JW                      | [bbe5800595](https://linux-hardware.org/?probe=bbe5800595) | Sep 27, 2020 |
| ASUSTek       | TP201SA                     | [932a0a60f7](https://linux-hardware.org/?probe=932a0a60f7) | Sep 27, 2020 |
| HP            | ProBook 4540s               | [2d701d47c9](https://linux-hardware.org/?probe=2d701d47c9) | Sep 27, 2020 |
| ASUSTek       | Strix 15 GL503GE            | [6f28c0f7e7](https://linux-hardware.org/?probe=6f28c0f7e7) | Sep 27, 2020 |
| HP            | EliteBook 2540p (WK303EA... | [37bd7657bf](https://linux-hardware.org/?probe=37bd7657bf) | Sep 27, 2020 |
| Toshiba       | Satellite Pro C660          | [075d46f568](https://linux-hardware.org/?probe=075d46f568) | Sep 26, 2020 |
| Acer          | Aspire 5755G                | [605e801c05](https://linux-hardware.org/?probe=605e801c05) | Sep 26, 2020 |
| HP            | Compaq nx7400 (RH412EA#A... | [5d7aceebef](https://linux-hardware.org/?probe=5d7aceebef) | Sep 26, 2020 |
| HP            | Compaq nx7400 (RH412EA#A... | [1702cc45b6](https://linux-hardware.org/?probe=1702cc45b6) | Sep 26, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [382de97334](https://linux-hardware.org/?probe=382de97334) | Sep 25, 2020 |
| HP            | Presario CQ57               | [bfd317474c](https://linux-hardware.org/?probe=bfd317474c) | Sep 25, 2020 |
| HP            | 650                         | [46e5ed2227](https://linux-hardware.org/?probe=46e5ed2227) | Sep 24, 2020 |
| HP            | Presario CQ57               | [e11f916bd4](https://linux-hardware.org/?probe=e11f916bd4) | Sep 24, 2020 |
| Acer          | Aspire 5755G                | [8eff6c0cf9](https://linux-hardware.org/?probe=8eff6c0cf9) | Sep 22, 2020 |
| Medion        | Unknown                     | [b02bda38c2](https://linux-hardware.org/?probe=b02bda38c2) | Sep 22, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [9e94e7e3be](https://linux-hardware.org/?probe=9e94e7e3be) | Sep 21, 2020 |
| Acer          | V5-131                      | [c7a2b4065f](https://linux-hardware.org/?probe=c7a2b4065f) | Sep 21, 2020 |
| ASUSTek       | TP201SA                     | [7ad7fb15a1](https://linux-hardware.org/?probe=7ad7fb15a1) | Sep 21, 2020 |
| Acer          | Aspire V5-121               | [45e2636f1d](https://linux-hardware.org/?probe=45e2636f1d) | Sep 21, 2020 |
| Lenovo        | G710 20252                  | [db5ee3605f](https://linux-hardware.org/?probe=db5ee3605f) | Sep 21, 2020 |
| Lenovo        | G710 20252                  | [274deeb9af](https://linux-hardware.org/?probe=274deeb9af) | Sep 21, 2020 |
| HP            | 250 G1                      | [f5c5812346](https://linux-hardware.org/?probe=f5c5812346) | Sep 21, 2020 |
| Acer          | Aspire 5755G                | [34514b88b3](https://linux-hardware.org/?probe=34514b88b3) | Sep 20, 2020 |
| Acer          | Aspire V5-121               | [62394c7389](https://linux-hardware.org/?probe=62394c7389) | Sep 20, 2020 |
| Lenovo        | Y50-70 20378                | [1b5cd85b2f](https://linux-hardware.org/?probe=1b5cd85b2f) | Sep 20, 2020 |
| HP            | Notebook                    | [9513ff9545](https://linux-hardware.org/?probe=9513ff9545) | Sep 20, 2020 |
| HP            | Notebook                    | [b69494cbb0](https://linux-hardware.org/?probe=b69494cbb0) | Sep 20, 2020 |
| Acer          | Unknown                     | [4361d1170b](https://linux-hardware.org/?probe=4361d1170b) | Sep 19, 2020 |
| Acer          | Unknown                     | [52b0731496](https://linux-hardware.org/?probe=52b0731496) | Sep 19, 2020 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [2bd0c68297](https://linux-hardware.org/?probe=2bd0c68297) | Sep 19, 2020 |
| ASUSTek       | X555LB                      | [64109fc31e](https://linux-hardware.org/?probe=64109fc31e) | Sep 18, 2020 |
| ASUSTek       | X555LB                      | [ac389754da](https://linux-hardware.org/?probe=ac389754da) | Sep 18, 2020 |
| MSI           | GP62 6QF                    | [91f9a73ba1](https://linux-hardware.org/?probe=91f9a73ba1) | Sep 18, 2020 |
| Toshiba       | Satellite C55-C             | [b2e485b94f](https://linux-hardware.org/?probe=b2e485b94f) | Sep 17, 2020 |
| Dell          | Latitude E6230              | [66d4b65b89](https://linux-hardware.org/?probe=66d4b65b89) | Sep 17, 2020 |
| Lenovo        | ThinkPad T400 2768WGB       | [31c09f5239](https://linux-hardware.org/?probe=31c09f5239) | Sep 16, 2020 |
| Acer          | Aspire V3-571G              | [01823a254f](https://linux-hardware.org/?probe=01823a254f) | Sep 16, 2020 |
| Acer          | Aspire ES1-411              | [8dcd17e446](https://linux-hardware.org/?probe=8dcd17e446) | Sep 15, 2020 |
| Acer          | Aspire 8930                 | [2b4861ffe7](https://linux-hardware.org/?probe=2b4861ffe7) | Sep 15, 2020 |
| Lenovo        | ThinkPad T400 2768WGB       | [f23a7d1768](https://linux-hardware.org/?probe=f23a7d1768) | Sep 15, 2020 |
| Fujitsu       | LIFEBOOK AH530              | [486dd12a7f](https://linux-hardware.org/?probe=486dd12a7f) | Sep 15, 2020 |
| Fujitsu       | LIFEBOOK AH530              | [8db841bd3b](https://linux-hardware.org/?probe=8db841bd3b) | Sep 15, 2020 |
| HP            | 250 G1                      | [8b80d9ab04](https://linux-hardware.org/?probe=8b80d9ab04) | Sep 15, 2020 |
| Dell          | XPS 12 9Q23                 | [877be59ac2](https://linux-hardware.org/?probe=877be59ac2) | Sep 15, 2020 |
| Dell          | Inspiron 3584               | [fd7c20e3ff](https://linux-hardware.org/?probe=fd7c20e3ff) | Sep 14, 2020 |
| Dell          | Inspiron N5110              | [13fb4b7f32](https://linux-hardware.org/?probe=13fb4b7f32) | Sep 14, 2020 |
| Acer          | Swift SF514-53T             | [faed7578a5](https://linux-hardware.org/?probe=faed7578a5) | Sep 13, 2020 |
| Dell          | Inspiron N5110              | [47f3dc5654](https://linux-hardware.org/?probe=47f3dc5654) | Sep 13, 2020 |
| Fujitsu       | LIFEBOOK S751               | [10a9a710ab](https://linux-hardware.org/?probe=10a9a710ab) | Sep 13, 2020 |
| LG Electro... | P310-S.CBRAG                | [d0364b9f0c](https://linux-hardware.org/?probe=d0364b9f0c) | Sep 12, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [2879ac2881](https://linux-hardware.org/?probe=2879ac2881) | Sep 12, 2020 |
| Dell          | Latitude E6420              | [f8bfac0dc8](https://linux-hardware.org/?probe=f8bfac0dc8) | Sep 12, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [8c18da9906](https://linux-hardware.org/?probe=8c18da9906) | Sep 12, 2020 |
| LG Electro... | P310-S.CBRAG                | [5b043121d8](https://linux-hardware.org/?probe=5b043121d8) | Sep 12, 2020 |
| Dell          | Vostro 1015                 | [45e50ebfe3](https://linux-hardware.org/?probe=45e50ebfe3) | Sep 12, 2020 |
| Dell          | Inspiron N5110              | [be913cfe66](https://linux-hardware.org/?probe=be913cfe66) | Sep 12, 2020 |
| Dell          | Inspiron N5110              | [6884736dd5](https://linux-hardware.org/?probe=6884736dd5) | Sep 11, 2020 |
| Acer          | E1-572G                     | [f929666b56](https://linux-hardware.org/?probe=f929666b56) | Sep 11, 2020 |
| Acer          | E1-572G                     | [410b8f1ec1](https://linux-hardware.org/?probe=410b8f1ec1) | Sep 11, 2020 |
| Dell          | Latitude E6420              | [65cda67833](https://linux-hardware.org/?probe=65cda67833) | Sep 11, 2020 |
| Dell          | Latitude E6400              | [60d47e9c71](https://linux-hardware.org/?probe=60d47e9c71) | Sep 10, 2020 |
| Fujitsu       | LIFEBOOK AH530              | [009e26123c](https://linux-hardware.org/?probe=009e26123c) | Sep 10, 2020 |
| Fujitsu Si... | LIFEBOOK E8310              | [09522a75c2](https://linux-hardware.org/?probe=09522a75c2) | Sep 09, 2020 |
| Fujitsu Si... | LIFEBOOK E8310              | [699359cd69](https://linux-hardware.org/?probe=699359cd69) | Sep 09, 2020 |
| HP            | EliteBook 840 G6            | [7b0c82c0ba](https://linux-hardware.org/?probe=7b0c82c0ba) | Sep 09, 2020 |
| Dell          | Inspiron 1018               | [52f8e584c5](https://linux-hardware.org/?probe=52f8e584c5) | Sep 09, 2020 |
| HP            | 250 G5 Notebook PC          | [2995bc48ad](https://linux-hardware.org/?probe=2995bc48ad) | Sep 09, 2020 |
| HP            | 250 G5 Notebook PC          | [e155944bd9](https://linux-hardware.org/?probe=e155944bd9) | Sep 08, 2020 |
| HP            | ProBook 4540s               | [34b1dc92eb](https://linux-hardware.org/?probe=34b1dc92eb) | Sep 08, 2020 |
| ASUSTek       | 1011PX                      | [03d93777a4](https://linux-hardware.org/?probe=03d93777a4) | Sep 08, 2020 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [b5e7dae48e](https://linux-hardware.org/?probe=b5e7dae48e) | Sep 08, 2020 |
| ASUSTek       | 1011PX                      | [cc8acefa5d](https://linux-hardware.org/?probe=cc8acefa5d) | Sep 08, 2020 |
| Acer          | Aspire 3810T                | [724dc30019](https://linux-hardware.org/?probe=724dc30019) | Sep 08, 2020 |
| Acer          | Aspire 3810T                | [364bc63d96](https://linux-hardware.org/?probe=364bc63d96) | Sep 08, 2020 |
| ASUSTek       | X540LA                      | [7588546e0d](https://linux-hardware.org/?probe=7588546e0d) | Sep 08, 2020 |
| Lenovo        | ThinkPad E15 20RD006LHV     | [f2ef943b44](https://linux-hardware.org/?probe=f2ef943b44) | Sep 08, 2020 |
| Lenovo        | G560 0679                   | [263430a3c9](https://linux-hardware.org/?probe=263430a3c9) | Sep 07, 2020 |
| Dell          | Latitude E5450              | [d5eebfddb5](https://linux-hardware.org/?probe=d5eebfddb5) | Sep 07, 2020 |
| Medion        | Akoya P7818                 | [87db741693](https://linux-hardware.org/?probe=87db741693) | Sep 07, 2020 |
| Medion        | Akoya P7818                 | [a9a45316ee](https://linux-hardware.org/?probe=a9a45316ee) | Sep 07, 2020 |
| Dell          | Inspiron N5110              | [fa3ab0be44](https://linux-hardware.org/?probe=fa3ab0be44) | Sep 06, 2020 |
| eMachines     | eME730G                     | [9ad58191ef](https://linux-hardware.org/?probe=9ad58191ef) | Sep 06, 2020 |
| Dell          | Inspiron 1018               | [cb764ba0cb](https://linux-hardware.org/?probe=cb764ba0cb) | Sep 06, 2020 |
| Dell          | Inspiron 1018               | [0899321767](https://linux-hardware.org/?probe=0899321767) | Sep 05, 2020 |
| Dell          | Vostro 3700                 | [c9b764a48b](https://linux-hardware.org/?probe=c9b764a48b) | Sep 05, 2020 |
| Dell          | Inspiron 5758               | [740fd6b861](https://linux-hardware.org/?probe=740fd6b861) | Sep 05, 2020 |
| Dell          | Inspiron 5758               | [d003e33155](https://linux-hardware.org/?probe=d003e33155) | Sep 05, 2020 |
| Lenovo        | ThinkPad L540 20AUA128HV    | [c0cf7ba97c](https://linux-hardware.org/?probe=c0cf7ba97c) | Sep 05, 2020 |
| HP            | 255 G7 Notebook PC          | [4a67af8db2](https://linux-hardware.org/?probe=4a67af8db2) | Sep 05, 2020 |
| Lenovo        | ThinkPad L540 20AUA128HV    | [a680e564ce](https://linux-hardware.org/?probe=a680e564ce) | Sep 05, 2020 |
| Dell          | Inspiron 15-3573            | [975ef0be47](https://linux-hardware.org/?probe=975ef0be47) | Sep 05, 2020 |
| Acer          | Aspire V3-571G              | [1e0b93171c](https://linux-hardware.org/?probe=1e0b93171c) | Sep 05, 2020 |
| HP            | EliteBook 8540p             | [45852b242b](https://linux-hardware.org/?probe=45852b242b) | Sep 05, 2020 |
| Lenovo        | ThinkPad T420 4236A26       | [f6817fa146](https://linux-hardware.org/?probe=f6817fa146) | Sep 04, 2020 |
| Lenovo        | ThinkPad T420 4236A26       | [1e16bff40c](https://linux-hardware.org/?probe=1e16bff40c) | Sep 04, 2020 |
| Dell          | Latitude E5440              | [b17b828025](https://linux-hardware.org/?probe=b17b828025) | Sep 04, 2020 |
| Dell          | Latitude E5440              | [0cd98933cc](https://linux-hardware.org/?probe=0cd98933cc) | Sep 04, 2020 |
| Lenovo        | G505 20240                  | [9fa55678ea](https://linux-hardware.org/?probe=9fa55678ea) | Sep 04, 2020 |
| Lenovo        | G505 20240                  | [de01986083](https://linux-hardware.org/?probe=de01986083) | Sep 04, 2020 |
| HP            | Compaq 8510p                | [74e0b56a8b](https://linux-hardware.org/?probe=74e0b56a8b) | Sep 04, 2020 |
| HP            | Compaq 8510p                | [64a60f9e6a](https://linux-hardware.org/?probe=64a60f9e6a) | Sep 04, 2020 |
| HP            | Presario CQ57               | [e443bcec3b](https://linux-hardware.org/?probe=e443bcec3b) | Sep 04, 2020 |
| Acer          | Aspire V3-571G              | [198862a2eb](https://linux-hardware.org/?probe=198862a2eb) | Sep 03, 2020 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [c3d6bf727b](https://linux-hardware.org/?probe=c3d6bf727b) | Sep 03, 2020 |
| ASUSTek       | K52F                        | [d28986cd8f](https://linux-hardware.org/?probe=d28986cd8f) | Sep 02, 2020 |
| ASUSTek       | K52F                        | [7e044786a8](https://linux-hardware.org/?probe=7e044786a8) | Sep 02, 2020 |
| Samsung       | RV411/RV511/E3511/S3511/... | [678260ccb5](https://linux-hardware.org/?probe=678260ccb5) | Sep 01, 2020 |
| HP            | EliteBook 2560p             | [c6b2d14c4a](https://linux-hardware.org/?probe=c6b2d14c4a) | Sep 01, 2020 |
| Dell          | XPS 11 9P33                 | [503aaa8e6a](https://linux-hardware.org/?probe=503aaa8e6a) | Sep 01, 2020 |
| Dell          | XPS 11 9P33                 | [a30302f24f](https://linux-hardware.org/?probe=a30302f24f) | Sep 01, 2020 |
| HP            | ProBook 5330m               | [16fba68861](https://linux-hardware.org/?probe=16fba68861) | Sep 01, 2020 |
| HP            | ProBook 5330m               | [b52ee4569e](https://linux-hardware.org/?probe=b52ee4569e) | Sep 01, 2020 |
| ASUSTek       | X555LJ                      | [f40b687fb7](https://linux-hardware.org/?probe=f40b687fb7) | Sep 01, 2020 |
| HP            | 350 G1                      | [80815864dc](https://linux-hardware.org/?probe=80815864dc) | Sep 01, 2020 |
| HP            | 350 G1                      | [90a49cee89](https://linux-hardware.org/?probe=90a49cee89) | Aug 31, 2020 |
| Samsung       | RV411/RV511/E3511/S3511/... | [f6a049cc84](https://linux-hardware.org/?probe=f6a049cc84) | Aug 31, 2020 |
| Samsung       | RV411/RV511/E3511/S3511/... | [da1b679cda](https://linux-hardware.org/?probe=da1b679cda) | Aug 31, 2020 |
| ASUSTek       | X555LJ                      | [fe2ce87bda](https://linux-hardware.org/?probe=fe2ce87bda) | Aug 31, 2020 |
| Lenovo        | ThinkPad P50 20EQS3B41R     | [dab43e3477](https://linux-hardware.org/?probe=dab43e3477) | Aug 31, 2020 |
| ASUSTek       | X555UB                      | [8f8d6b009a](https://linux-hardware.org/?probe=8f8d6b009a) | Aug 30, 2020 |
| Lenovo        | ThinkPad T410 2537BF9       | [18ac8539a0](https://linux-hardware.org/?probe=18ac8539a0) | Aug 30, 2020 |
| Lenovo        | ThinkPad T410 2537BF9       | [2370f8c2d0](https://linux-hardware.org/?probe=2370f8c2d0) | Aug 30, 2020 |
| HP            | Laptop 17-bs0xx             | [3b9bc3a768](https://linux-hardware.org/?probe=3b9bc3a768) | Aug 30, 2020 |
| HP            | EliteBook 8460p             | [4c59d52fae](https://linux-hardware.org/?probe=4c59d52fae) | Aug 30, 2020 |
| HP            | EliteBook 8460p             | [39c7a844e0](https://linux-hardware.org/?probe=39c7a844e0) | Aug 30, 2020 |
| Lenovo        | ThinkPad T430 2350B58       | [c440bf2e56](https://linux-hardware.org/?probe=c440bf2e56) | Aug 29, 2020 |
| Lenovo        | ThinkPad W510 431924G       | [39c6ce673d](https://linux-hardware.org/?probe=39c6ce673d) | Aug 28, 2020 |
| Dell          | Latitude D830               | [75b838c87c](https://linux-hardware.org/?probe=75b838c87c) | Aug 27, 2020 |
| Dell          | Latitude D830               | [275b991b94](https://linux-hardware.org/?probe=275b991b94) | Aug 27, 2020 |
| Dell          | Latitude E4310              | [d7434e1c05](https://linux-hardware.org/?probe=d7434e1c05) | Aug 26, 2020 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | [8e25577b95](https://linux-hardware.org/?probe=8e25577b95) | Aug 26, 2020 |
| Dell          | Latitude E5420              | [c3335bda3f](https://linux-hardware.org/?probe=c3335bda3f) | Aug 26, 2020 |
| Dell          | Latitude E5420              | [4fb6579ef7](https://linux-hardware.org/?probe=4fb6579ef7) | Aug 26, 2020 |
| ASUSTek       | X555LJ                      | [cad3453382](https://linux-hardware.org/?probe=cad3453382) | Aug 26, 2020 |
| ASUSTek       | K55VD                       | [c1e87554d1](https://linux-hardware.org/?probe=c1e87554d1) | Aug 26, 2020 |
| ASUSTek       | GL552VW                     | [9462a9e9ec](https://linux-hardware.org/?probe=9462a9e9ec) | Aug 26, 2020 |
| ASUSTek       | K55VD                       | [094af396d9](https://linux-hardware.org/?probe=094af396d9) | Aug 26, 2020 |
| Acer          | Aspire ES1-511              | [ae8c7effee](https://linux-hardware.org/?probe=ae8c7effee) | Aug 26, 2020 |
| Acer          | Aspire ES1-511              | [70d3a04bf9](https://linux-hardware.org/?probe=70d3a04bf9) | Aug 26, 2020 |
| Dell          | Latitude E6430              | [bb1cad481e](https://linux-hardware.org/?probe=bb1cad481e) | Aug 25, 2020 |
| ASUSTek       | G750JZA                     | [3093532c5a](https://linux-hardware.org/?probe=3093532c5a) | Aug 25, 2020 |
| Dell          | Latitude E6430              | [45a1c36a9a](https://linux-hardware.org/?probe=45a1c36a9a) | Aug 25, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [9fece39e61](https://linux-hardware.org/?probe=9fece39e61) | Aug 25, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [715d89b1a5](https://linux-hardware.org/?probe=715d89b1a5) | Aug 25, 2020 |
| ASUSTek       | GL552VW                     | [1e5df72d90](https://linux-hardware.org/?probe=1e5df72d90) | Aug 25, 2020 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [7bd7e7d8d8](https://linux-hardware.org/?probe=7bd7e7d8d8) | Aug 25, 2020 |
| HP            | ZBook 15                    | [3475715fe2](https://linux-hardware.org/?probe=3475715fe2) | Aug 25, 2020 |
| HP            | ZBook 15                    | [7f3c51a801](https://linux-hardware.org/?probe=7f3c51a801) | Aug 25, 2020 |
| Dell          | Latitude E4310              | [f3a8d03820](https://linux-hardware.org/?probe=f3a8d03820) | Aug 24, 2020 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [eae7fef49d](https://linux-hardware.org/?probe=eae7fef49d) | Aug 24, 2020 |
| Fujitsu       | LIFEBOOK A512               | [0a82c3e749](https://linux-hardware.org/?probe=0a82c3e749) | Aug 24, 2020 |
| Lenovo        | ThinkPad T440 20B7S19L00    | [41bec5c51d](https://linux-hardware.org/?probe=41bec5c51d) | Aug 24, 2020 |
| Lenovo        | ThinkPad T440 20B7S19L00    | [dbd72a2074](https://linux-hardware.org/?probe=dbd72a2074) | Aug 24, 2020 |
| Acer          | Aspire ES1-571              | [c9625b0618](https://linux-hardware.org/?probe=c9625b0618) | Aug 23, 2020 |
| Dell          | Inspiron N5110              | [10543b6890](https://linux-hardware.org/?probe=10543b6890) | Aug 23, 2020 |
| Dell          | Latitude E6410              | [4217658a1b](https://linux-hardware.org/?probe=4217658a1b) | Aug 23, 2020 |
| HP            | Laptop 15-bs0xx             | [41ed3ca700](https://linux-hardware.org/?probe=41ed3ca700) | Aug 23, 2020 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | [ee5415f1b7](https://linux-hardware.org/?probe=ee5415f1b7) | Aug 23, 2020 |
| Fujitsu       | LIFEBOOK S751               | [f6d3886103](https://linux-hardware.org/?probe=f6d3886103) | Aug 22, 2020 |
| HP            | EliteBook 8460p             | [e31307fb47](https://linux-hardware.org/?probe=e31307fb47) | Aug 22, 2020 |
| HP            | Presario CQ57               | [67eba29e4c](https://linux-hardware.org/?probe=67eba29e4c) | Aug 22, 2020 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | [105b239349](https://linux-hardware.org/?probe=105b239349) | Aug 22, 2020 |
| Lenovo        | Legion Y7000 2019 PG0 81... | [09da46f5d5](https://linux-hardware.org/?probe=09da46f5d5) | Aug 22, 2020 |
| Lenovo        | Legion Y7000 2019 PG0 81... | [c252e7658b](https://linux-hardware.org/?probe=c252e7658b) | Aug 22, 2020 |
| HP            | EliteBook 8460p             | [39ffacf310](https://linux-hardware.org/?probe=39ffacf310) | Aug 22, 2020 |
| ASUSTek       | X101CH                      | [ef84a5397b](https://linux-hardware.org/?probe=ef84a5397b) | Aug 21, 2020 |
| Acer          | Acadia V1.45                | [94ad672425](https://linux-hardware.org/?probe=94ad672425) | Aug 21, 2020 |
| Acer          | Acadia V1.45                | [8efaa72adb](https://linux-hardware.org/?probe=8efaa72adb) | Aug 21, 2020 |
| Lenovo        | G560 0679                   | [99c996a86e](https://linux-hardware.org/?probe=99c996a86e) | Aug 21, 2020 |
| Acer          | Aspire A315-33              | [80a21949e0](https://linux-hardware.org/?probe=80a21949e0) | Aug 21, 2020 |
| Acer          | Aspire A315-33              | [4b9320979e](https://linux-hardware.org/?probe=4b9320979e) | Aug 21, 2020 |
| Acer          | Aspire E5-521               | [193abc405d](https://linux-hardware.org/?probe=193abc405d) | Aug 21, 2020 |
| ASUSTek       | Strix 15 GL503GE            | [0328ae6fb9](https://linux-hardware.org/?probe=0328ae6fb9) | Aug 21, 2020 |
| HP            | ProBook 450 G1              | [fe46cd0a41](https://linux-hardware.org/?probe=fe46cd0a41) | Aug 21, 2020 |
| HP            | ProBook 450 G1              | [cd21111dfc](https://linux-hardware.org/?probe=cd21111dfc) | Aug 20, 2020 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [41c2de94ec](https://linux-hardware.org/?probe=41c2de94ec) | Aug 20, 2020 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [d8a8cf122c](https://linux-hardware.org/?probe=d8a8cf122c) | Aug 20, 2020 |
| ASUSTek       | X550CC                      | [a02734e111](https://linux-hardware.org/?probe=a02734e111) | Aug 20, 2020 |
| ASUSTek       | X550CC                      | [5d14236180](https://linux-hardware.org/?probe=5d14236180) | Aug 20, 2020 |
| Dell          | Inspiron 5567               | [c6a996e6be](https://linux-hardware.org/?probe=c6a996e6be) | Aug 20, 2020 |
| Acer          | Aspire 5735                 | [043232c833](https://linux-hardware.org/?probe=043232c833) | Aug 20, 2020 |
| Lenovo        | G570 20079                  | [c7e42187a8](https://linux-hardware.org/?probe=c7e42187a8) | Aug 20, 2020 |
| Acer          | Aspire E5-521               | [93426b4185](https://linux-hardware.org/?probe=93426b4185) | Aug 20, 2020 |
| ASUSTek       | X55A                        | [2f2fc84e80](https://linux-hardware.org/?probe=2f2fc84e80) | Aug 19, 2020 |
| Lenovo        | ThinkPad T410 2537CS0       | [d390ae1026](https://linux-hardware.org/?probe=d390ae1026) | Aug 19, 2020 |
| Lenovo        | ThinkPad T410 2537CS0       | [9008b8a6de](https://linux-hardware.org/?probe=9008b8a6de) | Aug 19, 2020 |
| Acer          | Aspire 8930                 | [1141ff574e](https://linux-hardware.org/?probe=1141ff574e) | Aug 19, 2020 |
| Lenovo        | ThinkPad T420 4180W15       | [a5bfc9ca87](https://linux-hardware.org/?probe=a5bfc9ca87) | Aug 19, 2020 |
| ASUSTek       | K52Je                       | [ec04a8cfc1](https://linux-hardware.org/?probe=ec04a8cfc1) | Aug 19, 2020 |
| ASUSTek       | K52Je                       | [aef391fee5](https://linux-hardware.org/?probe=aef391fee5) | Aug 19, 2020 |
| Fujitsu       | LIFEBOOK E554               | [9ab157686a](https://linux-hardware.org/?probe=9ab157686a) | Aug 18, 2020 |
| Fujitsu       | LIFEBOOK E554               | [c62a88f717](https://linux-hardware.org/?probe=c62a88f717) | Aug 18, 2020 |
| HP            | EliteBook 6930p             | [27e2e2d70c](https://linux-hardware.org/?probe=27e2e2d70c) | Aug 18, 2020 |
| HP            | EliteBook 6930p             | [9eb9b2b1e3](https://linux-hardware.org/?probe=9eb9b2b1e3) | Aug 18, 2020 |
| Dell          | Latitude E6430              | [4504b5491e](https://linux-hardware.org/?probe=4504b5491e) | Aug 18, 2020 |
| Dell          | Latitude E6430              | [d6c6637d01](https://linux-hardware.org/?probe=d6c6637d01) | Aug 18, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [660303468b](https://linux-hardware.org/?probe=660303468b) | Aug 18, 2020 |
| Lenovo        | ThinkPad P50 20EQS3B41R     | [3770f89aa3](https://linux-hardware.org/?probe=3770f89aa3) | Aug 18, 2020 |
| Lenovo        | ThinkPad P50 20EQS3B41R     | [a3305b5414](https://linux-hardware.org/?probe=a3305b5414) | Aug 18, 2020 |
| Dell          | Inspiron 3585               | [358ac64e9c](https://linux-hardware.org/?probe=358ac64e9c) | Aug 18, 2020 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [3f5b1781c3](https://linux-hardware.org/?probe=3f5b1781c3) | Aug 17, 2020 |
| Lenovo        | Z50-75 80EC                 | [3967255b87](https://linux-hardware.org/?probe=3967255b87) | Aug 17, 2020 |
| Dell          | Latitude E6330              | [43a324d886](https://linux-hardware.org/?probe=43a324d886) | Aug 17, 2020 |
| Acer          | Aspire A515-44G             | [ad50c2f263](https://linux-hardware.org/?probe=ad50c2f263) | Aug 17, 2020 |
| Dell          | Latitude D630               | [2a089cce28](https://linux-hardware.org/?probe=2a089cce28) | Aug 17, 2020 |
| Acer          | Aspire A515-44G             | [97a874306a](https://linux-hardware.org/?probe=97a874306a) | Aug 17, 2020 |
| HP            | 250 G6 Notebook PC          | [573feaa3a2](https://linux-hardware.org/?probe=573feaa3a2) | Aug 17, 2020 |
| HP            | 250 G6 Notebook PC          | [22d19d2369](https://linux-hardware.org/?probe=22d19d2369) | Aug 17, 2020 |
| Dell          | Latitude E7240              | [c534de1b0f](https://linux-hardware.org/?probe=c534de1b0f) | Aug 17, 2020 |
| Dell          | Latitude E6430              | [0039dc6fd6](https://linux-hardware.org/?probe=0039dc6fd6) | Aug 17, 2020 |
| Lenovo        | G550 20023                  | [f7d881f2e8](https://linux-hardware.org/?probe=f7d881f2e8) | Aug 17, 2020 |
| Lenovo        | ThinkPad T420 4236Z9U       | [b589cb4a2f](https://linux-hardware.org/?probe=b589cb4a2f) | Aug 17, 2020 |
| Dell          | Latitude E6420              | [b07144f024](https://linux-hardware.org/?probe=b07144f024) | Aug 16, 2020 |
| HP            | EliteBook 2540p             | [9fe0f4da0b](https://linux-hardware.org/?probe=9fe0f4da0b) | Aug 16, 2020 |
| HP            | EliteBook 2570p             | [68b54a8e19](https://linux-hardware.org/?probe=68b54a8e19) | Aug 16, 2020 |
| Acer          | Aspire E5-521               | [0e1e5eae0b](https://linux-hardware.org/?probe=0e1e5eae0b) | Aug 16, 2020 |
| Notebook      | W65_67SR                    | [0966030821](https://linux-hardware.org/?probe=0966030821) | Aug 15, 2020 |
| Dell          | Latitude D630               | [99d75dac5b](https://linux-hardware.org/?probe=99d75dac5b) | Aug 15, 2020 |
| Toshiba       | Satellite C55-C             | [e21594a307](https://linux-hardware.org/?probe=e21594a307) | Aug 14, 2020 |
| HP            | EliteBook 2540p             | [3568944dfb](https://linux-hardware.org/?probe=3568944dfb) | Aug 14, 2020 |
| ASUSTek       | K53TA                       | [814ef3ac33](https://linux-hardware.org/?probe=814ef3ac33) | Aug 14, 2020 |
| HP            | Presario CQ61               | [f0240de631](https://linux-hardware.org/?probe=f0240de631) | Aug 14, 2020 |
| HP            | Presario CQ61               | [a823a116cc](https://linux-hardware.org/?probe=a823a116cc) | Aug 14, 2020 |
| HP            | Compaq 6530b (GW688AV)      | [90dbb75c0b](https://linux-hardware.org/?probe=90dbb75c0b) | Aug 13, 2020 |
| Samsung       | N145P/N250P/N260P           | [1cc1148442](https://linux-hardware.org/?probe=1cc1148442) | Aug 13, 2020 |
| HP            | Compaq 6530b (GW688AV)      | [c9372eb2f7](https://linux-hardware.org/?probe=c9372eb2f7) | Aug 13, 2020 |
| Dell          | Latitude D830               | [bd4705452c](https://linux-hardware.org/?probe=bd4705452c) | Aug 12, 2020 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [7726f83eb6](https://linux-hardware.org/?probe=7726f83eb6) | Aug 12, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f056c26050](https://linux-hardware.org/?probe=f056c26050) | Aug 12, 2020 |
| HP            | Presario CQ61               | [e52b2eca43](https://linux-hardware.org/?probe=e52b2eca43) | Aug 11, 2020 |
| HP            | Presario CQ61               | [a199c20c73](https://linux-hardware.org/?probe=a199c20c73) | Aug 11, 2020 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | [fc94d09264](https://linux-hardware.org/?probe=fc94d09264) | Aug 11, 2020 |
| Dell          | Inspiron 1018               | [fd96ebe278](https://linux-hardware.org/?probe=fd96ebe278) | Aug 11, 2020 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [0be61fdc2c](https://linux-hardware.org/?probe=0be61fdc2c) | Aug 11, 2020 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [bab4e4b6b3](https://linux-hardware.org/?probe=bab4e4b6b3) | Aug 10, 2020 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [1441e93848](https://linux-hardware.org/?probe=1441e93848) | Aug 10, 2020 |
| Lenovo        | ThinkPad E14 20RA002UHV     | [982607f4a0](https://linux-hardware.org/?probe=982607f4a0) | Aug 10, 2020 |
| Lenovo        | ThinkPad E14 20RA002UHV     | [b84ee35937](https://linux-hardware.org/?probe=b84ee35937) | Aug 10, 2020 |
| ASUSTek       | X540SA                      | [e5ef1f4a85](https://linux-hardware.org/?probe=e5ef1f4a85) | Aug 10, 2020 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [06f46d57ef](https://linux-hardware.org/?probe=06f46d57ef) | Aug 09, 2020 |
| Acer          | Aspire 5732Z                | [193c114ad0](https://linux-hardware.org/?probe=193c114ad0) | Aug 09, 2020 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [49f890e3cf](https://linux-hardware.org/?probe=49f890e3cf) | Aug 09, 2020 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [04a58954c0](https://linux-hardware.org/?probe=04a58954c0) | Aug 09, 2020 |
| Medion        | E122X                       | [c125ffcb3d](https://linux-hardware.org/?probe=c125ffcb3d) | Aug 09, 2020 |
| Medion        | E122X                       | [a9239bb8dc](https://linux-hardware.org/?probe=a9239bb8dc) | Aug 09, 2020 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [0b6ddb5626](https://linux-hardware.org/?probe=0b6ddb5626) | Aug 09, 2020 |
| ASUSTek       | Strix 15 GL503GE            | [afcdfa8d46](https://linux-hardware.org/?probe=afcdfa8d46) | Aug 08, 2020 |
| HP            | 250 G6 Notebook PC          | [1ec8af3962](https://linux-hardware.org/?probe=1ec8af3962) | Aug 08, 2020 |
| Lenovo        | ThinkPad X250 20CLS1JN00    | [baac22f66a](https://linux-hardware.org/?probe=baac22f66a) | Aug 08, 2020 |
| Lenovo        | ThinkPad X250 20CLS1JN00    | [430602d59a](https://linux-hardware.org/?probe=430602d59a) | Aug 08, 2020 |
| Acer          | Aspire V5-121               | [a031319ce7](https://linux-hardware.org/?probe=a031319ce7) | Aug 08, 2020 |
| Toshiba       | Satellite A200              | [e06a576378](https://linux-hardware.org/?probe=e06a576378) | Aug 07, 2020 |
| Intel         | Shark Bay Platform          | [32ddddaa97](https://linux-hardware.org/?probe=32ddddaa97) | Aug 07, 2020 |
| Dell          | Latitude E7450              | [2d43213819](https://linux-hardware.org/?probe=2d43213819) | Aug 07, 2020 |
| Gigabyte      | MMLP5AP-00                  | [9fa9fcb073](https://linux-hardware.org/?probe=9fa9fcb073) | Aug 06, 2020 |
| Dell          | Latitude D430               | [08a7b521df](https://linux-hardware.org/?probe=08a7b521df) | Aug 06, 2020 |
| Acer          | Aspire 7750G                | [b8dce798c2](https://linux-hardware.org/?probe=b8dce798c2) | Aug 05, 2020 |
| ASUSTek       | X541UJ                      | [ce8023840f](https://linux-hardware.org/?probe=ce8023840f) | Aug 05, 2020 |
| ASUSTek       | X541UJ                      | [29018cc865](https://linux-hardware.org/?probe=29018cc865) | Aug 05, 2020 |
| ASUSTek       | X751SA                      | [5d21f2cf77](https://linux-hardware.org/?probe=5d21f2cf77) | Aug 05, 2020 |
| HP            | EliteBook 8470p             | [2f68aeb923](https://linux-hardware.org/?probe=2f68aeb923) | Aug 05, 2020 |
| Lenovo        | G50-45 80E3                 | [0feebc49c0](https://linux-hardware.org/?probe=0feebc49c0) | Aug 04, 2020 |
| Acer          | Aspire ES1-132              | [f82817880e](https://linux-hardware.org/?probe=f82817880e) | Aug 04, 2020 |
| Dell          | Latitude E5420              | [0f29c1cfc9](https://linux-hardware.org/?probe=0f29c1cfc9) | Aug 03, 2020 |
| Lenovo        | ThinkPad X200s 7470Y1K      | [e8ca410719](https://linux-hardware.org/?probe=e8ca410719) | Aug 03, 2020 |
| Lenovo        | ThinkPad X200s 7470Y1K      | [d4673dcb65](https://linux-hardware.org/?probe=d4673dcb65) | Aug 03, 2020 |
| Acer          | Aspire ES1-132              | [3cd035912e](https://linux-hardware.org/?probe=3cd035912e) | Aug 03, 2020 |
| Dell          | Latitude E6420              | [5f83f8d6d3](https://linux-hardware.org/?probe=5f83f8d6d3) | Aug 02, 2020 |
| HP            | ProBook 6550b               | [3f8f0958cf](https://linux-hardware.org/?probe=3f8f0958cf) | Aug 02, 2020 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [7fbb8e5aab](https://linux-hardware.org/?probe=7fbb8e5aab) | Aug 01, 2020 |
| Lenovo        | G580                        | [f34ebc9a9d](https://linux-hardware.org/?probe=f34ebc9a9d) | Aug 01, 2020 |
| Lenovo        | G580                        | [4f8510d353](https://linux-hardware.org/?probe=4f8510d353) | Aug 01, 2020 |
| Lenovo        | ThinkPad X200s 7470Y1K      | [5905e36563](https://linux-hardware.org/?probe=5905e36563) | Aug 01, 2020 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [cf9ab14a10](https://linux-hardware.org/?probe=cf9ab14a10) | Jul 31, 2020 |
| Toshiba       | Satellite L40               | [2bfeced980](https://linux-hardware.org/?probe=2bfeced980) | Jul 31, 2020 |
| Toshiba       | Satellite L40               | [fbbbc2b1ab](https://linux-hardware.org/?probe=fbbbc2b1ab) | Jul 31, 2020 |
| HP            | Laptop 15-bs0xx             | [edb456d8c5](https://linux-hardware.org/?probe=edb456d8c5) | Jul 31, 2020 |
| HP            | Laptop 15-bs0xx             | [86caec9af6](https://linux-hardware.org/?probe=86caec9af6) | Jul 31, 2020 |
| eMachines     | E727                        | [1f41baa69d](https://linux-hardware.org/?probe=1f41baa69d) | Jul 31, 2020 |
| eMachines     | E727                        | [2f462186c0](https://linux-hardware.org/?probe=2f462186c0) | Jul 31, 2020 |
| Lenovo        | ThinkPad R61 7735ah7        | [b6deb16d5a](https://linux-hardware.org/?probe=b6deb16d5a) | Jul 30, 2020 |
| ASUSTek       | X200MA                      | [a34da34ec9](https://linux-hardware.org/?probe=a34da34ec9) | Jul 29, 2020 |
| ASUSTek       | X200MA                      | [25b3b26cdc](https://linux-hardware.org/?probe=25b3b26cdc) | Jul 29, 2020 |
| HP            | ENVY Laptop 13-ah0xxx       | [bb6dc74cb3](https://linux-hardware.org/?probe=bb6dc74cb3) | Jul 29, 2020 |
| Acer          | Aspire one                  | [ab42d57be4](https://linux-hardware.org/?probe=ab42d57be4) | Jul 29, 2020 |
| ASUSTek       | ZenBook 13 UX331FAL_UX33... | [ccff8576fc](https://linux-hardware.org/?probe=ccff8576fc) | Jul 29, 2020 |
| Lenovo        | ThinkPad X200s 7470Y1K      | [a54e02fee8](https://linux-hardware.org/?probe=a54e02fee8) | Jul 28, 2020 |
| ASUSTek       | K50IJ                       | [6fac9d3b06](https://linux-hardware.org/?probe=6fac9d3b06) | Jul 28, 2020 |
| ASUSTek       | X55A                        | [e37c15bae8](https://linux-hardware.org/?probe=e37c15bae8) | Jul 28, 2020 |
| Medion        | P7624                       | [c5a4cd4b17](https://linux-hardware.org/?probe=c5a4cd4b17) | Jul 28, 2020 |
| ASUSTek       | K50IJ                       | [b414b2e721](https://linux-hardware.org/?probe=b414b2e721) | Jul 28, 2020 |
| Medion        | P7624                       | [ca493bacf0](https://linux-hardware.org/?probe=ca493bacf0) | Jul 28, 2020 |
| ASUSTek       | X550VX                      | [183c5c0949](https://linux-hardware.org/?probe=183c5c0949) | Jul 27, 2020 |
| Lenovo        | ThinkPad X200s 7470Y1K      | [470a0e3653](https://linux-hardware.org/?probe=470a0e3653) | Jul 27, 2020 |
| Acer          | Aspire E5-772G              | [5dc5e85dda](https://linux-hardware.org/?probe=5dc5e85dda) | Jul 26, 2020 |
| Acer          | Aspire E5-772G              | [a2debcfa4c](https://linux-hardware.org/?probe=a2debcfa4c) | Jul 26, 2020 |
| ASUSTek       | Strix 15 GL503GE            | [fa9c5656b4](https://linux-hardware.org/?probe=fa9c5656b4) | Jul 26, 2020 |
| Lenovo        | ThinkPad W510 431924G       | [6143d3181f](https://linux-hardware.org/?probe=6143d3181f) | Jul 26, 2020 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [072bc559da](https://linux-hardware.org/?probe=072bc559da) | Jul 26, 2020 |
| Lenovo        | ThinkPad R61 7735ah7        | [403d064247](https://linux-hardware.org/?probe=403d064247) | Jul 25, 2020 |
| Lenovo        | ThinkPad R61 7735ah7        | [d150357be5](https://linux-hardware.org/?probe=d150357be5) | Jul 25, 2020 |
| Hungaro Fl... | Navon Stark NX14 PRO 201... | [8d1a6b1cc1](https://linux-hardware.org/?probe=8d1a6b1cc1) | Jul 25, 2020 |
| Toshiba       | Satellite L40               | [6624afde28](https://linux-hardware.org/?probe=6624afde28) | Jul 25, 2020 |
| Toshiba       | Satellite L40               | [5d2b79518a](https://linux-hardware.org/?probe=5d2b79518a) | Jul 25, 2020 |
| ASUSTek       | X540NA                      | [0b7875ea24](https://linux-hardware.org/?probe=0b7875ea24) | Jul 25, 2020 |
| Lenovo        | Z50-70 20354                | [ba5506eb4c](https://linux-hardware.org/?probe=ba5506eb4c) | Jul 24, 2020 |
| Lenovo        | ThinkPad T460s 20FAS07N0... | [ff0675addc](https://linux-hardware.org/?probe=ff0675addc) | Jul 24, 2020 |
| Lenovo        | ThinkPad X200 7458C81       | [6b5e1aab81](https://linux-hardware.org/?probe=6b5e1aab81) | Jul 24, 2020 |
| Dell          | Inspiron 5770               | [c704a8ce66](https://linux-hardware.org/?probe=c704a8ce66) | Jul 24, 2020 |
| Toshiba       | Satellite L50-A-19N         | [1bf97ce75f](https://linux-hardware.org/?probe=1bf97ce75f) | Jul 23, 2020 |
| HP            | Laptop 15-ra0xx             | [f97d817e5b](https://linux-hardware.org/?probe=f97d817e5b) | Jul 23, 2020 |
| Dell          | Latitude E6230              | [899b9a192a](https://linux-hardware.org/?probe=899b9a192a) | Jul 23, 2020 |
| HP            | Laptop 15-ra0xx             | [a428ac6b7e](https://linux-hardware.org/?probe=a428ac6b7e) | Jul 23, 2020 |
| Hungaro Fl... | Navon Stark NX14 PRO 201... | [927345cbaa](https://linux-hardware.org/?probe=927345cbaa) | Jul 22, 2020 |
| HP            | Compaq 6710b                | [38fe8cbb0b](https://linux-hardware.org/?probe=38fe8cbb0b) | Jul 22, 2020 |
| HP            | Compaq 6710b                | [e7a7e9d11c](https://linux-hardware.org/?probe=e7a7e9d11c) | Jul 22, 2020 |
| HP            | EliteBook 8570w             | [de99c4512f](https://linux-hardware.org/?probe=de99c4512f) | Jul 22, 2020 |
| Acidanther... | MacBookPro14,1              | [212fcf71f3](https://linux-hardware.org/?probe=212fcf71f3) | Jul 22, 2020 |
| Lenovo        | B50-70 20384                | [9b70bb4251](https://linux-hardware.org/?probe=9b70bb4251) | Jul 21, 2020 |
| HP            | Pavilion dv6700             | [2310c3e075](https://linux-hardware.org/?probe=2310c3e075) | Jul 21, 2020 |
| Dell          | Latitude D530               | [1d5196ee87](https://linux-hardware.org/?probe=1d5196ee87) | Jul 20, 2020 |
| Lenovo        | Z50-70 20354                | [d103625336](https://linux-hardware.org/?probe=d103625336) | Jul 19, 2020 |
| HP            | Presario V6000 (RR735EA#... | [8736d5c850](https://linux-hardware.org/?probe=8736d5c850) | Jul 19, 2020 |
| Lenovo        | B50-70 20384                | [34276f195b](https://linux-hardware.org/?probe=34276f195b) | Jul 19, 2020 |
| Dell          | Inspiron 3542               | [b84c824e4c](https://linux-hardware.org/?probe=b84c824e4c) | Jul 19, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [801d10cca6](https://linux-hardware.org/?probe=801d10cca6) | Jul 18, 2020 |
| Dell          | Inspiron 15-3573            | [5457aedab9](https://linux-hardware.org/?probe=5457aedab9) | Jul 18, 2020 |
| Toshiba       | Satellite A200              | [3626eb537e](https://linux-hardware.org/?probe=3626eb537e) | Jul 18, 2020 |
| Acer          | Aspire 5755G                | [bf81b23d9a](https://linux-hardware.org/?probe=bf81b23d9a) | Jul 18, 2020 |
| Lenovo        | ThinkPad T400 6474W66       | [b6114e356e](https://linux-hardware.org/?probe=b6114e356e) | Jul 18, 2020 |
| Lenovo        | ThinkPad T400 6474W66       | [36580b0231](https://linux-hardware.org/?probe=36580b0231) | Jul 18, 2020 |
| eMachines     | eME732Z                     | [fc471c2d21](https://linux-hardware.org/?probe=fc471c2d21) | Jul 17, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [757c5eea30](https://linux-hardware.org/?probe=757c5eea30) | Jul 17, 2020 |
| Lenovo        | ThinkPad T540p 20BF002CH... | [17057eabf3](https://linux-hardware.org/?probe=17057eabf3) | Jul 17, 2020 |
| Lenovo        | ThinkPad T540p 20BF002CH... | [408263ca6a](https://linux-hardware.org/?probe=408263ca6a) | Jul 17, 2020 |
| Dell          | Latitude E5410              | [ac90111589](https://linux-hardware.org/?probe=ac90111589) | Jul 17, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [da3178714a](https://linux-hardware.org/?probe=da3178714a) | Jul 16, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [36c2743e5d](https://linux-hardware.org/?probe=36c2743e5d) | Jul 16, 2020 |
| AMI           | Cherry Trail CR             | [788afcbff5](https://linux-hardware.org/?probe=788afcbff5) | Jul 16, 2020 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [a4072a6c25](https://linux-hardware.org/?probe=a4072a6c25) | Jul 16, 2020 |
| AMI           | Cherry Trail CR             | [b67ab4839e](https://linux-hardware.org/?probe=b67ab4839e) | Jul 16, 2020 |
| Fujitsu Si... | ESPRIMO Mobile M9410        | [ad9cc83c92](https://linux-hardware.org/?probe=ad9cc83c92) | Jul 15, 2020 |
| ASUSTek       | 1015BXO                     | [9595a993e1](https://linux-hardware.org/?probe=9595a993e1) | Jul 14, 2020 |
| ASUSTek       | 1015BXO                     | [49c16057fe](https://linux-hardware.org/?probe=49c16057fe) | Jul 14, 2020 |
| ASUSTek       | Strix 15 GL503GE            | [d3c46dfc18](https://linux-hardware.org/?probe=d3c46dfc18) | Jul 13, 2020 |
| Dell          | Latitude E6410              | [e3f35182be](https://linux-hardware.org/?probe=e3f35182be) | Jul 12, 2020 |
| Acer          | Aspire E1-772G              | [2aa637baf6](https://linux-hardware.org/?probe=2aa637baf6) | Jul 12, 2020 |
| Fujitsu       | LIFEBOOK E554               | [190bbd1209](https://linux-hardware.org/?probe=190bbd1209) | Jul 12, 2020 |
| Fujitsu       | LIFEBOOK E554               | [810545a108](https://linux-hardware.org/?probe=810545a108) | Jul 12, 2020 |
| Dell          | Latitude E6410              | [a2317af125](https://linux-hardware.org/?probe=a2317af125) | Jul 12, 2020 |
| Lenovo        | G505s 20255                 | [fd0b49c43d](https://linux-hardware.org/?probe=fd0b49c43d) | Jul 12, 2020 |
| Lenovo        | G505s 20255                 | [3c1a864273](https://linux-hardware.org/?probe=3c1a864273) | Jul 12, 2020 |
| HP            | Compaq 6710b (KE121EA#AK... | [206106ba5c](https://linux-hardware.org/?probe=206106ba5c) | Jul 12, 2020 |
| Dell          | Latitude E7240              | [d758435a2d](https://linux-hardware.org/?probe=d758435a2d) | Jul 11, 2020 |
| Dell          | Latitude E7240              | [d3b184d9c2](https://linux-hardware.org/?probe=d3b184d9c2) | Jul 11, 2020 |
| Lenovo        | ThinkPad T420 4236A26       | [81c3521c3b](https://linux-hardware.org/?probe=81c3521c3b) | Jul 10, 2020 |
| ASUSTek       | X540LA                      | [7e39235606](https://linux-hardware.org/?probe=7e39235606) | Jul 10, 2020 |
| ASUSTek       | X540LA                      | [c7565f589a](https://linux-hardware.org/?probe=c7565f589a) | Jul 10, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [a4074b0ce0](https://linux-hardware.org/?probe=a4074b0ce0) | Jul 10, 2020 |
| Packard Be... | EasyNote ENTG81BA           | [d05ede06dd](https://linux-hardware.org/?probe=d05ede06dd) | Jul 10, 2020 |
| Lenovo        | ThinkPad T540p 20BF002CH... | [67f7a5e843](https://linux-hardware.org/?probe=67f7a5e843) | Jul 09, 2020 |
| Dell          | Latitude E6330              | [3e26e4cb42](https://linux-hardware.org/?probe=3e26e4cb42) | Jul 09, 2020 |
| ASUSTek       | X751SA                      | [0bb63b5d87](https://linux-hardware.org/?probe=0bb63b5d87) | Jul 09, 2020 |
| HP            | Compaq 6710b (GR679EA#AK... | [5f0ab4c9cd](https://linux-hardware.org/?probe=5f0ab4c9cd) | Jul 09, 2020 |
| Dell          | Latitude D530               | [091b0bb19d](https://linux-hardware.org/?probe=091b0bb19d) | Jul 08, 2020 |
| Acer          | Aspire 5951G                | [25e6e25fa9](https://linux-hardware.org/?probe=25e6e25fa9) | Jul 08, 2020 |
| HP            | Compaq 6710b (GR679EA#AK... | [4d589c42d5](https://linux-hardware.org/?probe=4d589c42d5) | Jul 08, 2020 |
| eMachines     | E727                        | [1c85fa3b3e](https://linux-hardware.org/?probe=1c85fa3b3e) | Jul 06, 2020 |
| eMachines     | E727                        | [841f094e77](https://linux-hardware.org/?probe=841f094e77) | Jul 06, 2020 |
| Packard Be... | EasyNote TM85               | [01bd1661f6](https://linux-hardware.org/?probe=01bd1661f6) | Jul 06, 2020 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [74083dffa5](https://linux-hardware.org/?probe=74083dffa5) | Jul 06, 2020 |
| Dell          | Vostro 5581                 | [bb2b8e5c44](https://linux-hardware.org/?probe=bb2b8e5c44) | Jul 06, 2020 |
| Timi          | TM1701                      | [05eea71f44](https://linux-hardware.org/?probe=05eea71f44) | Jul 05, 2020 |
| Dell          | Latitude E5570              | [7181a84595](https://linux-hardware.org/?probe=7181a84595) | Jul 05, 2020 |
| Toshiba       | Unknown                     | [30d646257f](https://linux-hardware.org/?probe=30d646257f) | Jul 04, 2020 |
| Dell          | Latitude E6330              | [acce568eef](https://linux-hardware.org/?probe=acce568eef) | Jul 04, 2020 |
| ASUSTek       | K54C                        | [f936cec21b](https://linux-hardware.org/?probe=f936cec21b) | Jul 04, 2020 |
| ASUSTek       | K54C                        | [d72c8b2b69](https://linux-hardware.org/?probe=d72c8b2b69) | Jul 04, 2020 |
| Alcor         | Flashbook D1423I            | [df9d5958c0](https://linux-hardware.org/?probe=df9d5958c0) | Jul 03, 2020 |
| Lenovo        | G550 20023                  | [500301dc41](https://linux-hardware.org/?probe=500301dc41) | Jul 03, 2020 |
| Dell          | Inspiron 3737               | [767a39b33b](https://linux-hardware.org/?probe=767a39b33b) | Jul 03, 2020 |
| Dell          | Latitude E5540              | [7e5045a90d](https://linux-hardware.org/?probe=7e5045a90d) | Jul 03, 2020 |
| ASUSTek       | U53Jc                       | [3a09838831](https://linux-hardware.org/?probe=3a09838831) | Jul 02, 2020 |
| HP            | ZBook 15 G5                 | [e2d4f0103b](https://linux-hardware.org/?probe=e2d4f0103b) | Jul 02, 2020 |
| ASUSTek       | K52F                        | [5eab41677a](https://linux-hardware.org/?probe=5eab41677a) | Jul 02, 2020 |
| ASUSTek       | K52F                        | [4143df4d99](https://linux-hardware.org/?probe=4143df4d99) | Jul 02, 2020 |
| HP            | ProBook 450 G0              | [141927b3e6](https://linux-hardware.org/?probe=141927b3e6) | Jul 02, 2020 |
| Lenovo        | ThinkPad T420 42364F2       | [0e50d49f55](https://linux-hardware.org/?probe=0e50d49f55) | Jul 02, 2020 |
| HP            | EliteBook 8470p             | [76c43ea41d](https://linux-hardware.org/?probe=76c43ea41d) | Jul 01, 2020 |
| HP            | EliteBook 8470p             | [a107d5308a](https://linux-hardware.org/?probe=a107d5308a) | Jul 01, 2020 |
| Lenovo        | ThinkPad T410 2537V2L       | [aed7203289](https://linux-hardware.org/?probe=aed7203289) | Jul 01, 2020 |
| Lenovo        | ThinkPad T410 2537V2L       | [dfa429a19a](https://linux-hardware.org/?probe=dfa429a19a) | Jul 01, 2020 |
| Dell          | Latitude E6420              | [5bf9e46087](https://linux-hardware.org/?probe=5bf9e46087) | Jun 27, 2020 |
| Toshiba       | Satellite A100              | [a3ca809f72](https://linux-hardware.org/?probe=a3ca809f72) | Jun 27, 2020 |
| Toshiba       | Satellite A100              | [5d64cf0193](https://linux-hardware.org/?probe=5d64cf0193) | Jun 26, 2020 |
| Dell          | Latitude E4310              | [d7b710d7b2](https://linux-hardware.org/?probe=d7b710d7b2) | Jun 26, 2020 |
| Minix         | M1200 Series                | [dd694ed67b](https://linux-hardware.org/?probe=dd694ed67b) | Jun 26, 2020 |
| Fujitsu       | LIFEBOOK A512               | [7fb87fe855](https://linux-hardware.org/?probe=7fb87fe855) | Jun 25, 2020 |
| Lenovo        | ThinkPad T420 42364F2       | [8431ad7228](https://linux-hardware.org/?probe=8431ad7228) | Jun 24, 2020 |
| HP            | Laptop 15-bs0xx             | [de4ebdb760](https://linux-hardware.org/?probe=de4ebdb760) | Jun 24, 2020 |
| Dell          | Inspiron N5110              | [9247b0d391](https://linux-hardware.org/?probe=9247b0d391) | Jun 24, 2020 |
| HP            | EliteBook 840 G6            | [a7583112c2](https://linux-hardware.org/?probe=a7583112c2) | Jun 24, 2020 |
| Medion        | E7214                       | [569c936d9e](https://linux-hardware.org/?probe=569c936d9e) | Jun 24, 2020 |
| ASUSTek       | VivoBook E14 E402WAS        | [c0c85439f6](https://linux-hardware.org/?probe=c0c85439f6) | Jun 23, 2020 |
| HP            | EliteBook 840 G6            | [068efa1ec2](https://linux-hardware.org/?probe=068efa1ec2) | Jun 23, 2020 |
| Dell          | System Inspiron N7110       | [9d4406c5a3](https://linux-hardware.org/?probe=9d4406c5a3) | Jun 22, 2020 |
| ASUSTek       | UX32VD                      | [0ed5ebf652](https://linux-hardware.org/?probe=0ed5ebf652) | Jun 22, 2020 |
| HP            | G62                         | [9f802845e8](https://linux-hardware.org/?probe=9f802845e8) | Jun 22, 2020 |
| HP            | G62                         | [724c2b3afe](https://linux-hardware.org/?probe=724c2b3afe) | Jun 22, 2020 |
| Acer          | Predator PH317-52           | [44a505fdce](https://linux-hardware.org/?probe=44a505fdce) | Jun 21, 2020 |
| HP            | Laptop 15-bw0xx             | [e133326c53](https://linux-hardware.org/?probe=e133326c53) | Jun 21, 2020 |
| HP            | Laptop 15-bw0xx             | [a8f7e24434](https://linux-hardware.org/?probe=a8f7e24434) | Jun 21, 2020 |
| Acer          | Aspire E5-772G              | [d560f8695c](https://linux-hardware.org/?probe=d560f8695c) | Jun 21, 2020 |
| ASUSTek       | VivoBook E14 E402WAS        | [9c7ed9e4c2](https://linux-hardware.org/?probe=9c7ed9e4c2) | Jun 21, 2020 |
| Lenovo        | ThinkBook 15-IML 20RW       | [13a804c100](https://linux-hardware.org/?probe=13a804c100) | Jun 21, 2020 |
| Minix         | M1200 Series                | [626bfa6c77](https://linux-hardware.org/?probe=626bfa6c77) | Jun 21, 2020 |
| Dell          | Vostro 15-3568              | [b533788722](https://linux-hardware.org/?probe=b533788722) | Jun 20, 2020 |
| Dell          | Latitude E5540              | [9529cbc1c6](https://linux-hardware.org/?probe=9529cbc1c6) | Jun 20, 2020 |
| eMachines     | eME730G                     | [4882c24467](https://linux-hardware.org/?probe=4882c24467) | Jun 20, 2020 |
| HP            | Compaq 6710b (GB890EA#AK... | [a98a015405](https://linux-hardware.org/?probe=a98a015405) | Jun 20, 2020 |
| ASUSTek       | X540NA                      | [bb52e41d78](https://linux-hardware.org/?probe=bb52e41d78) | Jun 20, 2020 |
| Acer          | Aspire A715-71G             | [792164a91d](https://linux-hardware.org/?probe=792164a91d) | Jun 19, 2020 |
| Dell          | Inspiron 3542               | [697594601f](https://linux-hardware.org/?probe=697594601f) | Jun 19, 2020 |
| Acer          | Aspire A715-71G             | [8293c98601](https://linux-hardware.org/?probe=8293c98601) | Jun 19, 2020 |
| HP            | 250 G3                      | [c493969b5b](https://linux-hardware.org/?probe=c493969b5b) | Jun 19, 2020 |
| ASUSTek       | K53U                        | [8fd080e8c0](https://linux-hardware.org/?probe=8fd080e8c0) | Jun 18, 2020 |
| Acer          | Aspire A315-55KG            | [5f8560fecd](https://linux-hardware.org/?probe=5f8560fecd) | Jun 17, 2020 |
| Acer          | Aspire A315-55KG            | [23f978175b](https://linux-hardware.org/?probe=23f978175b) | Jun 17, 2020 |
| Lenovo        | 3000 V200 076472G           | [41093b8cec](https://linux-hardware.org/?probe=41093b8cec) | Jun 17, 2020 |
| Lenovo        | 3000 V200 076472G           | [00ee827d2b](https://linux-hardware.org/?probe=00ee827d2b) | Jun 17, 2020 |
| Packard Be... | EasyNote TV43HC             | [f96ba991ea](https://linux-hardware.org/?probe=f96ba991ea) | Jun 17, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [6f16c5a682](https://linux-hardware.org/?probe=6f16c5a682) | Jun 17, 2020 |
| Dell          | Inspiron 5558               | [86e3e4e9b3](https://linux-hardware.org/?probe=86e3e4e9b3) | Jun 16, 2020 |
| HP            | Laptop 15-bs0xx             | [b7aad273e4](https://linux-hardware.org/?probe=b7aad273e4) | Jun 16, 2020 |
| Fujitsu Si... | AMILO Xi 2528               | [912200dde3](https://linux-hardware.org/?probe=912200dde3) | Jun 16, 2020 |
| Fujitsu Si... | AMILO Xi 2528               | [eaf6f8054e](https://linux-hardware.org/?probe=eaf6f8054e) | Jun 16, 2020 |
| Dell          | Latitude E5420              | [fce7dd38a2](https://linux-hardware.org/?probe=fce7dd38a2) | Jun 15, 2020 |
| Panasonic     | CF-31JLGAX1M                | [c7b71dd511](https://linux-hardware.org/?probe=c7b71dd511) | Jun 14, 2020 |
| Lenovo        | ThinkPad X230 2325AC7       | [5d03f14c67](https://linux-hardware.org/?probe=5d03f14c67) | Jun 14, 2020 |
| Lenovo        | ThinkPad X230 2325AC7       | [f683673b9a](https://linux-hardware.org/?probe=f683673b9a) | Jun 14, 2020 |
| ASUSTek       | VivoBook E14 E402WAS        | [8720d5a7da](https://linux-hardware.org/?probe=8720d5a7da) | Jun 14, 2020 |
| Dell          | Latitude E7240              | [389e7537a3](https://linux-hardware.org/?probe=389e7537a3) | Jun 14, 2020 |
| Dell          | Latitude E7240              | [3f502fabdc](https://linux-hardware.org/?probe=3f502fabdc) | Jun 14, 2020 |
| Lenovo        | G580 20150                  | [64d910ae93](https://linux-hardware.org/?probe=64d910ae93) | Jun 14, 2020 |
| Dell          | XPS 11 9P33                 | [725e866779](https://linux-hardware.org/?probe=725e866779) | Jun 14, 2020 |
| Dell          | System Inspiron N7110       | [951aa04cf7](https://linux-hardware.org/?probe=951aa04cf7) | Jun 14, 2020 |
| Packard Be... | EasyNote TV43HC             | [8bc972e43c](https://linux-hardware.org/?probe=8bc972e43c) | Jun 13, 2020 |
| Lenovo        | M5400 20281                 | [126abfe6b7](https://linux-hardware.org/?probe=126abfe6b7) | Jun 13, 2020 |
| Lenovo        | M5400 20281                 | [55658f5dee](https://linux-hardware.org/?probe=55658f5dee) | Jun 13, 2020 |
| Packard Be... | EasyNote TV43HC             | [dd17456f76](https://linux-hardware.org/?probe=dd17456f76) | Jun 13, 2020 |
| Acer          | Aspire 5742G                | [07e3988023](https://linux-hardware.org/?probe=07e3988023) | Jun 13, 2020 |
| Unknown       | T3 MRD                      | [1d3b3acea9](https://linux-hardware.org/?probe=1d3b3acea9) | Jun 13, 2020 |
| Unknown       | T3 MRD                      | [0e99d2a7d7](https://linux-hardware.org/?probe=0e99d2a7d7) | Jun 13, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [d85da8f9ab](https://linux-hardware.org/?probe=d85da8f9ab) | Jun 12, 2020 |
| Fujitsu Si... | AMILO Pro Edition V3505     | [5aa1642777](https://linux-hardware.org/?probe=5aa1642777) | Jun 12, 2020 |
| ASUSTek       | 1016P                       | [f815796cfd](https://linux-hardware.org/?probe=f815796cfd) | Jun 12, 2020 |
| Lenovo        | M5400 20281                 | [dbb653aa9f](https://linux-hardware.org/?probe=dbb653aa9f) | Jun 12, 2020 |
| HP            | EliteBook 8440p             | [f19f73b851](https://linux-hardware.org/?probe=f19f73b851) | Jun 11, 2020 |
| Dell          | Vostro 5471                 | [3ddd98d23e](https://linux-hardware.org/?probe=3ddd98d23e) | Jun 11, 2020 |
| Fujitsu Si... | AMILO Pro Edition V3505     | [344bc5cf43](https://linux-hardware.org/?probe=344bc5cf43) | Jun 11, 2020 |
| Alcor         | Intel Education Tablet      | [18349fc93e](https://linux-hardware.org/?probe=18349fc93e) | Jun 11, 2020 |
| Alcor         | Intel Education Tablet      | [b1cb3a54bf](https://linux-hardware.org/?probe=b1cb3a54bf) | Jun 11, 2020 |
| Dell          | Latitude E6430              | [983e66e5cf](https://linux-hardware.org/?probe=983e66e5cf) | Jun 10, 2020 |
| Dell          | Latitude E6430              | [b18091287d](https://linux-hardware.org/?probe=b18091287d) | Jun 10, 2020 |
| ASUSTek       | U53Jc                       | [a6f6a752c1](https://linux-hardware.org/?probe=a6f6a752c1) | Jun 10, 2020 |
| HP            | EliteBook 8530p             | [379528cc6b](https://linux-hardware.org/?probe=379528cc6b) | Jun 10, 2020 |
| Dell          | System Inspiron N7110       | [1e4e0cb9cd](https://linux-hardware.org/?probe=1e4e0cb9cd) | Jun 10, 2020 |
| Dell          | System Inspiron N7110       | [b06001fc15](https://linux-hardware.org/?probe=b06001fc15) | Jun 10, 2020 |
| Lenovo        | ThinkPad T430 23498R6       | [0abc86809d](https://linux-hardware.org/?probe=0abc86809d) | Jun 10, 2020 |
| Acer          | AOD257                      | [c1b8eea87f](https://linux-hardware.org/?probe=c1b8eea87f) | Jun 10, 2020 |
| Acer          | AOD257                      | [ca2b1cd11c](https://linux-hardware.org/?probe=ca2b1cd11c) | Jun 10, 2020 |
| Dell          | Inspiron 5570               | [f68f77d75c](https://linux-hardware.org/?probe=f68f77d75c) | Jun 09, 2020 |
| Lenovo        | ThinkPad T410 2537V2L       | [662170927a](https://linux-hardware.org/?probe=662170927a) | Jun 09, 2020 |
| Dell          | Inspiron 5570               | [5d9a239089](https://linux-hardware.org/?probe=5d9a239089) | Jun 09, 2020 |
| Dell          | Latitude E6520              | [562518e066](https://linux-hardware.org/?probe=562518e066) | Jun 09, 2020 |
| HP            | Compaq 6715s (GA009ET#AB... | [bbfe74d0cf](https://linux-hardware.org/?probe=bbfe74d0cf) | Jun 08, 2020 |
| Acer          | Aspire E1-571               | [d95570bdfb](https://linux-hardware.org/?probe=d95570bdfb) | Jun 08, 2020 |
| Dell          | Latitude E6520              | [0092736486](https://linux-hardware.org/?probe=0092736486) | Jun 08, 2020 |
| Acer          | TravelMate 4060             | [4709aa7a69](https://linux-hardware.org/?probe=4709aa7a69) | Jun 08, 2020 |
| ASUSTek       | X555SJ                      | [3ed99b5264](https://linux-hardware.org/?probe=3ed99b5264) | Jun 07, 2020 |
| NEC Comput... | PC-GL20ESYA6                | [523026c1bf](https://linux-hardware.org/?probe=523026c1bf) | Jun 07, 2020 |
| ASUSTek       | VivoBook E14 E402WAS        | [d7387b56cc](https://linux-hardware.org/?probe=d7387b56cc) | Jun 07, 2020 |
| ASUSTek       | VivoBook E14 E402WAS        | [919f49ca10](https://linux-hardware.org/?probe=919f49ca10) | Jun 07, 2020 |
| Alcor         | Intel Education Tablet      | [7e79d46068](https://linux-hardware.org/?probe=7e79d46068) | Jun 07, 2020 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [5239aadad7](https://linux-hardware.org/?probe=5239aadad7) | Jun 07, 2020 |
| Dell          | Inspiron 15-3567            | [9b6cd896be](https://linux-hardware.org/?probe=9b6cd896be) | Jun 06, 2020 |
| Toshiba       | Satellite L500              | [20f1ae8860](https://linux-hardware.org/?probe=20f1ae8860) | Jun 06, 2020 |
| Acer          | Aspire 5732Z                | [811b582b16](https://linux-hardware.org/?probe=811b582b16) | Jun 06, 2020 |
| Acer          | Aspire 5732Z                | [5a16f8fb7f](https://linux-hardware.org/?probe=5a16f8fb7f) | Jun 06, 2020 |
| Acer          | TravelMate 2490             | [95db700f93](https://linux-hardware.org/?probe=95db700f93) | Jun 06, 2020 |
| Lenovo        | ThinkPad T410 2537V2L       | [93e81f1ce0](https://linux-hardware.org/?probe=93e81f1ce0) | Jun 06, 2020 |
| ASUSTek       | K53SC                       | [7a0cda0747](https://linux-hardware.org/?probe=7a0cda0747) | Jun 06, 2020 |
| HP            | EliteBook 8530p             | [80c42736a1](https://linux-hardware.org/?probe=80c42736a1) | Jun 05, 2020 |
| Lenovo        | G570 20079                  | [b2a2398c2c](https://linux-hardware.org/?probe=b2a2398c2c) | Jun 05, 2020 |
| HP            | EliteBook 8530p             | [80584c791c](https://linux-hardware.org/?probe=80584c791c) | Jun 05, 2020 |
| Dell          | Inspiron 15-3567            | [e80bee428d](https://linux-hardware.org/?probe=e80bee428d) | Jun 05, 2020 |
| Dell          | Inspiron 1012               | [580dbabc2c](https://linux-hardware.org/?probe=580dbabc2c) | Jun 04, 2020 |
| Dell          | Latitude E5420              | [8a80a119eb](https://linux-hardware.org/?probe=8a80a119eb) | Jun 04, 2020 |
| Dell          | Inspiron 5558               | [5ab3161b2d](https://linux-hardware.org/?probe=5ab3161b2d) | Jun 04, 2020 |
| Acer          | Aspire 5720Z                | [125f8f6f08](https://linux-hardware.org/?probe=125f8f6f08) | Jun 04, 2020 |
| ASUSTek       | K401UB                      | [0bdc4b43f4](https://linux-hardware.org/?probe=0bdc4b43f4) | Jun 04, 2020 |
| ASUSTek       | X541UAK                     | [c6cb3d4ab2](https://linux-hardware.org/?probe=c6cb3d4ab2) | Jun 04, 2020 |
| ASUSTek       | X541UAK                     | [e9567f698e](https://linux-hardware.org/?probe=e9567f698e) | Jun 04, 2020 |
| Acer          | Nitro AN515-51              | [aab0994586](https://linux-hardware.org/?probe=aab0994586) | Jun 03, 2020 |
| Acer          | AOA150                      | [4c8c319a43](https://linux-hardware.org/?probe=4c8c319a43) | Jun 03, 2020 |
| Dell          | Latitude E5540              | [e9d89375c8](https://linux-hardware.org/?probe=e9d89375c8) | Jun 03, 2020 |
| Lenovo        | G50-45 80E3                 | [106c3af66c](https://linux-hardware.org/?probe=106c3af66c) | Jun 03, 2020 |
| Lenovo        | G50-45 80E3                 | [31a63a4579](https://linux-hardware.org/?probe=31a63a4579) | Jun 03, 2020 |
| Acer          | Aspire E5-522G              | [f2933caad2](https://linux-hardware.org/?probe=f2933caad2) | Jun 03, 2020 |
| Lenovo        | ThinkPad T60 2008VKP        | [d7af92ab85](https://linux-hardware.org/?probe=d7af92ab85) | Jun 03, 2020 |
| Toshiba       | Satellite C660              | [b9b6a99e5b](https://linux-hardware.org/?probe=b9b6a99e5b) | Jun 02, 2020 |
| Acer          | Aspire E1-570G              | [b05371b38e](https://linux-hardware.org/?probe=b05371b38e) | Jun 02, 2020 |
| Acer          | Aspire E1-570G              | [fbbc79ed98](https://linux-hardware.org/?probe=fbbc79ed98) | Jun 02, 2020 |
| Acer          | Nitro AN515-54              | [c3b149dff5](https://linux-hardware.org/?probe=c3b149dff5) | Jun 02, 2020 |
| Acer          | Nitro AN515-54              | [f458ad2849](https://linux-hardware.org/?probe=f458ad2849) | Jun 02, 2020 |
| Dell          | Latitude E7240              | [7a06c8e313](https://linux-hardware.org/?probe=7a06c8e313) | Jun 02, 2020 |
| HP            | Spectre 13 Ultrabook        | [e42d9a0a09](https://linux-hardware.org/?probe=e42d9a0a09) | Jun 01, 2020 |
| HP            | Spectre 13 Ultrabook        | [bd7e98703f](https://linux-hardware.org/?probe=bd7e98703f) | Jun 01, 2020 |
| Lenovo        | G500 20236                  | [d7046fbc7b](https://linux-hardware.org/?probe=d7046fbc7b) | Jun 01, 2020 |
| Lenovo        | G500 20236                  | [1354d0a689](https://linux-hardware.org/?probe=1354d0a689) | Jun 01, 2020 |
| Alcor         | Intel Education Tablet      | [914ffced39](https://linux-hardware.org/?probe=914ffced39) | Jun 01, 2020 |
| ASUSTek       | K54C                        | [3aadbaf7df](https://linux-hardware.org/?probe=3aadbaf7df) | Jun 01, 2020 |
| Toshiba       | Satellite C660              | [ebfd5cc437](https://linux-hardware.org/?probe=ebfd5cc437) | Jun 01, 2020 |
| Toshiba       | Satellite C660              | [772658ba5f](https://linux-hardware.org/?probe=772658ba5f) | Jun 01, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ada71e183e](https://linux-hardware.org/?probe=ada71e183e) | Jun 01, 2020 |
| Dell          | Latitude E6430              | [ad78c45f8d](https://linux-hardware.org/?probe=ad78c45f8d) | May 31, 2020 |
| Medion        | Akoya E1317T                | [9f9fd282c0](https://linux-hardware.org/?probe=9f9fd282c0) | May 31, 2020 |
| Medion        | Akoya E1317T                | [44b73ea787](https://linux-hardware.org/?probe=44b73ea787) | May 31, 2020 |
| Timi          | TM1701                      | [e39c6b97a0](https://linux-hardware.org/?probe=e39c6b97a0) | May 30, 2020 |
| Dell          | Latitude E4310              | [3928d2b887](https://linux-hardware.org/?probe=3928d2b887) | May 30, 2020 |
| Dell          | Latitude E6500              | [7c50268f4f](https://linux-hardware.org/?probe=7c50268f4f) | May 30, 2020 |
| Acer          | Aspire 5536                 | [f8d78992d0](https://linux-hardware.org/?probe=f8d78992d0) | May 30, 2020 |
| Acer          | Aspire 5536                 | [95321b6ac7](https://linux-hardware.org/?probe=95321b6ac7) | May 30, 2020 |
| HP            | EliteBook 2560p             | [9ae00bd212](https://linux-hardware.org/?probe=9ae00bd212) | May 30, 2020 |
| HP            | EliteBook 2560p             | [579f692f05](https://linux-hardware.org/?probe=579f692f05) | May 30, 2020 |
| Lenovo        | G50-80 80E5                 | [496d5f27c0](https://linux-hardware.org/?probe=496d5f27c0) | May 29, 2020 |
| Lenovo        | G50-80 80E5                 | [0479a66ce9](https://linux-hardware.org/?probe=0479a66ce9) | May 29, 2020 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [9afd86ec08](https://linux-hardware.org/?probe=9afd86ec08) | May 29, 2020 |
| HP            | Laptop 15-bs0xx             | [e4efca872f](https://linux-hardware.org/?probe=e4efca872f) | May 29, 2020 |
| ASUSTek       | VivoBook E14 E402WA         | [d56379f560](https://linux-hardware.org/?probe=d56379f560) | May 29, 2020 |
| Dell          | Inspiron M5040              | [cec49fe521](https://linux-hardware.org/?probe=cec49fe521) | May 29, 2020 |
| Dell          | Latitude E5450              | [548207b349](https://linux-hardware.org/?probe=548207b349) | May 29, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | [30ae792fa6](https://linux-hardware.org/?probe=30ae792fa6) | May 28, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | [23a1cf10b7](https://linux-hardware.org/?probe=23a1cf10b7) | May 28, 2020 |
| Hungaro Fl... | Navon Vision Book           | [d9719b16b7](https://linux-hardware.org/?probe=d9719b16b7) | May 28, 2020 |
| Hungaro Fl... | Navon Vision Book           | [ccbf4538ac](https://linux-hardware.org/?probe=ccbf4538ac) | May 28, 2020 |
| ASUSTek       | T300FA                      | [42d53f4fa3](https://linux-hardware.org/?probe=42d53f4fa3) | May 28, 2020 |
| Lenovo        | G50-45 80E3                 | [8512ddfc22](https://linux-hardware.org/?probe=8512ddfc22) | May 28, 2020 |
| Lenovo        | G50-45 80E3                 | [2ac77f8722](https://linux-hardware.org/?probe=2ac77f8722) | May 28, 2020 |
| HP            | ProBook 4535s               | [c9b410a1da](https://linux-hardware.org/?probe=c9b410a1da) | May 28, 2020 |
| Lenovo        | V110-15IAP 80TG             | [5359d4331c](https://linux-hardware.org/?probe=5359d4331c) | May 28, 2020 |
| Lenovo        | V110-15IAP 80TG             | [242a7532aa](https://linux-hardware.org/?probe=242a7532aa) | May 28, 2020 |
| HP            | EliteBook 8470p             | [e713c7d51a](https://linux-hardware.org/?probe=e713c7d51a) | May 28, 2020 |
| HP            | EliteBook 8470p             | [d833b4ad7a](https://linux-hardware.org/?probe=d833b4ad7a) | May 28, 2020 |
| Dell          | Inspiron 3521               | [9528241314](https://linux-hardware.org/?probe=9528241314) | May 27, 2020 |
| ASUSTek       | X550ZE                      | [92057cfea6](https://linux-hardware.org/?probe=92057cfea6) | May 27, 2020 |
| Fujitsu       | LIFEBOOK E780               | [26c7c388c2](https://linux-hardware.org/?probe=26c7c388c2) | May 27, 2020 |
| Fujitsu       | LIFEBOOK E780               | [f4d9f5b808](https://linux-hardware.org/?probe=f4d9f5b808) | May 27, 2020 |
| Fujitsu       | LIFEBOOK E780               | [22fad2b819](https://linux-hardware.org/?probe=22fad2b819) | May 27, 2020 |
| Dell          | Latitude E6410              | [19b60f0dfd](https://linux-hardware.org/?probe=19b60f0dfd) | May 27, 2020 |
| Dell          | Latitude E6410              | [3f6b112812](https://linux-hardware.org/?probe=3f6b112812) | May 27, 2020 |
| ASUSTek       | K53TA                       | [905df686ae](https://linux-hardware.org/?probe=905df686ae) | May 27, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | [7c5cff83d6](https://linux-hardware.org/?probe=7c5cff83d6) | May 26, 2020 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [cca70cdefb](https://linux-hardware.org/?probe=cca70cdefb) | May 26, 2020 |
| HP            | EliteBook 8540p             | [2c00474a77](https://linux-hardware.org/?probe=2c00474a77) | May 25, 2020 |
| HP            | 620                         | [5bbc6d248d](https://linux-hardware.org/?probe=5bbc6d248d) | May 25, 2020 |
| HP            | Compaq nc4200 (PA750AV)     | [27e013bc5f](https://linux-hardware.org/?probe=27e013bc5f) | May 25, 2020 |
| HP            | 620                         | [3459f8d789](https://linux-hardware.org/?probe=3459f8d789) | May 25, 2020 |
| HP            | 620                         | [3430cf518f](https://linux-hardware.org/?probe=3430cf518f) | May 25, 2020 |
| Dell          | Inspiron 1545               | [670c9551e0](https://linux-hardware.org/?probe=670c9551e0) | May 25, 2020 |
| ASUSTek       | F5SL                        | [947c9e7acf](https://linux-hardware.org/?probe=947c9e7acf) | May 25, 2020 |
| ASUSTek       | F5SL                        | [f61f397a5c](https://linux-hardware.org/?probe=f61f397a5c) | May 25, 2020 |
| Dell          | Inspiron 3521               | [355527de5f](https://linux-hardware.org/?probe=355527de5f) | May 24, 2020 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [768f8edb59](https://linux-hardware.org/?probe=768f8edb59) | May 24, 2020 |
| Acer          | Aspire A715-71G             | [3533ba173f](https://linux-hardware.org/?probe=3533ba173f) | May 24, 2020 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [372a446fd0](https://linux-hardware.org/?probe=372a446fd0) | May 24, 2020 |
| Packard Be... | EasyNote TE11HC             | [1fd9e50e15](https://linux-hardware.org/?probe=1fd9e50e15) | May 24, 2020 |
| Packard Be... | EasyNote TE11HC             | [d2e8cefcb0](https://linux-hardware.org/?probe=d2e8cefcb0) | May 24, 2020 |
| Packard Be... | EasyNote TE11HC             | [bd5aba1b09](https://linux-hardware.org/?probe=bd5aba1b09) | May 24, 2020 |
| Dell          | Latitude E7470              | [013ecf0c81](https://linux-hardware.org/?probe=013ecf0c81) | May 24, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [7c44f570b3](https://linux-hardware.org/?probe=7c44f570b3) | May 24, 2020 |
| HP            | ProBook 6475b               | [e751bd4702](https://linux-hardware.org/?probe=e751bd4702) | May 24, 2020 |
| Lenovo        | ThinkPad W510 431924G       | [3149353cfa](https://linux-hardware.org/?probe=3149353cfa) | May 24, 2020 |
| HP            | ProBook 6475b               | [c15f3eded2](https://linux-hardware.org/?probe=c15f3eded2) | May 24, 2020 |
| Dell          | Inspiron 5558               | [6d3341c8be](https://linux-hardware.org/?probe=6d3341c8be) | May 24, 2020 |
| Lenovo        | ThinkPad P50 20EQS12Q3N     | [5637432d92](https://linux-hardware.org/?probe=5637432d92) | May 24, 2020 |
| Lenovo        | G580 20150                  | [b6af882614](https://linux-hardware.org/?probe=b6af882614) | May 23, 2020 |
| ASUSTek       | K50IJ                       | [8a53b66af5](https://linux-hardware.org/?probe=8a53b66af5) | May 23, 2020 |
| HP            | ProBook 6475b               | [011b0613db](https://linux-hardware.org/?probe=011b0613db) | May 23, 2020 |
| Lenovo        | G580 20150                  | [eba5bab4d3](https://linux-hardware.org/?probe=eba5bab4d3) | May 23, 2020 |
| HP            | ProBook 6475b               | [747ad055cb](https://linux-hardware.org/?probe=747ad055cb) | May 23, 2020 |
| Acer          | Aspire E5-772G              | [6800b50380](https://linux-hardware.org/?probe=6800b50380) | May 23, 2020 |
| Gigabyte      | Q1580L                      | [671db3df19](https://linux-hardware.org/?probe=671db3df19) | May 23, 2020 |
| Gigabyte      | Q1580L                      | [077339a2e0](https://linux-hardware.org/?probe=077339a2e0) | May 23, 2020 |
| Gigabyte      | Q1580L                      | [31b973ab41](https://linux-hardware.org/?probe=31b973ab41) | May 23, 2020 |
| Dell          | Inspiron 5558               | [2b8440de08](https://linux-hardware.org/?probe=2b8440de08) | May 23, 2020 |
| Dell          | Inspiron 5558               | [b3801cb8b1](https://linux-hardware.org/?probe=b3801cb8b1) | May 23, 2020 |
| HP            | Laptop 17-bs0xx             | [ebc36005ca](https://linux-hardware.org/?probe=ebc36005ca) | May 21, 2020 |
| ASUSTek       | X541SA                      | [c9c200c774](https://linux-hardware.org/?probe=c9c200c774) | May 21, 2020 |
| Toshiba       | Satellite L20               | [d2372ec185](https://linux-hardware.org/?probe=d2372ec185) | May 20, 2020 |
| HP            | Pavilion Notebook           | [b1fce0cd91](https://linux-hardware.org/?probe=b1fce0cd91) | May 20, 2020 |
| HP            | Pavilion Notebook           | [0b0b9ea893](https://linux-hardware.org/?probe=0b0b9ea893) | May 20, 2020 |
| Dell          | Latitude 7390               | [49112c8937](https://linux-hardware.org/?probe=49112c8937) | May 20, 2020 |
| HP            | 15                          | [95b3870dc4](https://linux-hardware.org/?probe=95b3870dc4) | May 19, 2020 |
| HP            | 15                          | [0c1b154fb8](https://linux-hardware.org/?probe=0c1b154fb8) | May 19, 2020 |
| Packard Be... | EasyNote TS44HR             | [6eef0ecf19](https://linux-hardware.org/?probe=6eef0ecf19) | May 19, 2020 |
| Lenovo        | G580 20150                  | [79049fb484](https://linux-hardware.org/?probe=79049fb484) | May 18, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [8c21ab7223](https://linux-hardware.org/?probe=8c21ab7223) | May 18, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [f24bd12d8b](https://linux-hardware.org/?probe=f24bd12d8b) | May 18, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [9fa159de13](https://linux-hardware.org/?probe=9fa159de13) | May 18, 2020 |
| HP            | Laptop 17-bs0xx             | [39d62b9ce7](https://linux-hardware.org/?probe=39d62b9ce7) | May 18, 2020 |
| Timi          | TM1701                      | [a5ee5848dd](https://linux-hardware.org/?probe=a5ee5848dd) | May 17, 2020 |
| HP            | EliteBook 8470p             | [e4b360801a](https://linux-hardware.org/?probe=e4b360801a) | May 17, 2020 |
| HP            | EliteBook 8470p             | [5ab7a88f30](https://linux-hardware.org/?probe=5ab7a88f30) | May 17, 2020 |
| Sony          | VGN-NR21Z_S                 | [f0988ad637](https://linux-hardware.org/?probe=f0988ad637) | May 17, 2020 |
| Fujitsu Si... | AMILO Ui 3520               | [325eb98a43](https://linux-hardware.org/?probe=325eb98a43) | May 16, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [675713472d](https://linux-hardware.org/?probe=675713472d) | May 16, 2020 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [a6f70ddb28](https://linux-hardware.org/?probe=a6f70ddb28) | May 15, 2020 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [9b29426b05](https://linux-hardware.org/?probe=9b29426b05) | May 14, 2020 |
| Lenovo        | IdeaPad Z585 20152          | [12a0320d2a](https://linux-hardware.org/?probe=12a0320d2a) | May 14, 2020 |
| HP            | Laptop 17-bs0xx             | [440401a1d5](https://linux-hardware.org/?probe=440401a1d5) | May 14, 2020 |
| Lenovo        | IdeaPad Z585 20152          | [c0ee243521](https://linux-hardware.org/?probe=c0ee243521) | May 13, 2020 |
| Lenovo        | G580 20150                  | [ea219f9268](https://linux-hardware.org/?probe=ea219f9268) | May 12, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [77e8562103](https://linux-hardware.org/?probe=77e8562103) | May 11, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [9221984693](https://linux-hardware.org/?probe=9221984693) | May 10, 2020 |
| HP            | Laptop 15-da0xxx            | [cc8ec3027d](https://linux-hardware.org/?probe=cc8ec3027d) | May 10, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [6561a91b6e](https://linux-hardware.org/?probe=6561a91b6e) | May 10, 2020 |
| HP            | Laptop 15-da0xxx            | [aa2ec0229a](https://linux-hardware.org/?probe=aa2ec0229a) | May 10, 2020 |
| Medion        | E7214                       | [3dd5830933](https://linux-hardware.org/?probe=3dd5830933) | May 10, 2020 |
| Lenovo        | ThinkPad T530 2394D27       | [41267a881d](https://linux-hardware.org/?probe=41267a881d) | May 10, 2020 |
| ASUSTek       | 1005HA                      | [58f2b991e1](https://linux-hardware.org/?probe=58f2b991e1) | May 10, 2020 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [9440e144fe](https://linux-hardware.org/?probe=9440e144fe) | May 09, 2020 |
| Samsung       | NC20/NB20                   | [085b83a79c](https://linux-hardware.org/?probe=085b83a79c) | May 09, 2020 |
| HP            | ProBook 4320s               | [69124ccee6](https://linux-hardware.org/?probe=69124ccee6) | May 09, 2020 |
| HP            | Compaq 8510p                | [c32fcd0277](https://linux-hardware.org/?probe=c32fcd0277) | May 09, 2020 |
| HP            | EliteBook 8460p             | [361bf46faa](https://linux-hardware.org/?probe=361bf46faa) | May 08, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [f9aa057dd8](https://linux-hardware.org/?probe=f9aa057dd8) | May 08, 2020 |
| Lenovo        | 3000 N500 423338G           | [ef15e4b171](https://linux-hardware.org/?probe=ef15e4b171) | May 07, 2020 |
| Lenovo        | ThinkPad T60 1952VYF        | [205d8a73ee](https://linux-hardware.org/?probe=205d8a73ee) | May 07, 2020 |
| Fujitsu Si... | AMILO La1703                | [841c85d27a](https://linux-hardware.org/?probe=841c85d27a) | May 07, 2020 |
| HP            | 620                         | [544caa6c45](https://linux-hardware.org/?probe=544caa6c45) | May 07, 2020 |
| ASUSTek       | X550VX                      | [a59971972d](https://linux-hardware.org/?probe=a59971972d) | May 06, 2020 |
| Dell          | Latitude E5540              | [deda61d84e](https://linux-hardware.org/?probe=deda61d84e) | May 06, 2020 |
| Lenovo        | G580 20150                  | [1dbc72f410](https://linux-hardware.org/?probe=1dbc72f410) | May 06, 2020 |
| Sony          | SVE1512W1ESI                | [174a86b409](https://linux-hardware.org/?probe=174a86b409) | May 06, 2020 |
| Dell          | G5 5587                     | [e9d0e13760](https://linux-hardware.org/?probe=e9d0e13760) | May 06, 2020 |
| Lenovo        | ThinkPad L520 5016BK3       | [1e9562d830](https://linux-hardware.org/?probe=1e9562d830) | May 06, 2020 |
| Lenovo        | ThinkPad T60 1952VYF        | [91db5be25e](https://linux-hardware.org/?probe=91db5be25e) | May 05, 2020 |
| Lenovo        | ThinkPad X61 7673BW3        | [94bb4ce023](https://linux-hardware.org/?probe=94bb4ce023) | May 05, 2020 |
| Acer          | TravelMate 8571             | [0260f00269](https://linux-hardware.org/?probe=0260f00269) | May 05, 2020 |
| HP            | EliteBook 8440p             | [d1b938ad78](https://linux-hardware.org/?probe=d1b938ad78) | May 05, 2020 |
| HP            | 250 G1                      | [54e9461053](https://linux-hardware.org/?probe=54e9461053) | May 05, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [e77f75deba](https://linux-hardware.org/?probe=e77f75deba) | May 05, 2020 |
| Toshiba       | Satellite L300              | [d84957d374](https://linux-hardware.org/?probe=d84957d374) | May 05, 2020 |
| Lenovo        | B50-80 80EW                 | [557dd56394](https://linux-hardware.org/?probe=557dd56394) | May 05, 2020 |
| ASUSTek       | 1101HA                      | [0d3abba09d](https://linux-hardware.org/?probe=0d3abba09d) | May 05, 2020 |
| Sony          | VPCYB3V1E                   | [dc2d35826a](https://linux-hardware.org/?probe=dc2d35826a) | May 05, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [2a83f63a3a](https://linux-hardware.org/?probe=2a83f63a3a) | May 05, 2020 |
| Lenovo        | ThinkPad X200 74595FG       | [a7363bfa6e](https://linux-hardware.org/?probe=a7363bfa6e) | May 05, 2020 |
| HP            | 15                          | [fbcdce31d2](https://linux-hardware.org/?probe=fbcdce31d2) | May 05, 2020 |
| HP            | Pavilion dv6                | [63e29bba3c](https://linux-hardware.org/?probe=63e29bba3c) | May 05, 2020 |
| ASUSTek       | K54HR                       | [4ac7b4ec3e](https://linux-hardware.org/?probe=4ac7b4ec3e) | May 04, 2020 |
| Medion        | E7214                       | [f67257c904](https://linux-hardware.org/?probe=f67257c904) | May 04, 2020 |
| eMachines     | eME730G                     | [cde2877de5](https://linux-hardware.org/?probe=cde2877de5) | May 04, 2020 |
| Lenovo        | ThinkPad T450 20BUS09Y0E    | [3c6bbb0634](https://linux-hardware.org/?probe=3c6bbb0634) | May 04, 2020 |
| HP            | ProBook 450 G1              | [2730754663](https://linux-hardware.org/?probe=2730754663) | May 04, 2020 |
| ASUSTek       | X541SA                      | [bd56c2f0c4](https://linux-hardware.org/?probe=bd56c2f0c4) | May 04, 2020 |
| HP            | Pavilion g6                 | [26c5cf3251](https://linux-hardware.org/?probe=26c5cf3251) | May 04, 2020 |
| Dell          | System XPS L502X            | [0eb233d98d](https://linux-hardware.org/?probe=0eb233d98d) | May 04, 2020 |
| HP            | ProBook 5330m               | [d86984d786](https://linux-hardware.org/?probe=d86984d786) | May 04, 2020 |
| ASUSTek       | X550CC                      | [62159b77c6](https://linux-hardware.org/?probe=62159b77c6) | May 04, 2020 |
| Dell          | Latitude 5480               | [55ae584f78](https://linux-hardware.org/?probe=55ae584f78) | May 04, 2020 |
| Fujitsu       | LIFEBOOK A555               | [ae283ab838](https://linux-hardware.org/?probe=ae283ab838) | May 04, 2020 |
| Acer          | Aspire A315-21              | [c3b4f188d0](https://linux-hardware.org/?probe=c3b4f188d0) | May 04, 2020 |
| ASUSTek       | K52Jr                       | [f62a0b5177](https://linux-hardware.org/?probe=f62a0b5177) | May 04, 2020 |
| Acer          | Swift SF113-31              | [4a6a713ef8](https://linux-hardware.org/?probe=4a6a713ef8) | May 03, 2020 |
| Acer          | Aspire 5742G                | [38175190e2](https://linux-hardware.org/?probe=38175190e2) | May 03, 2020 |
| Dell          | Latitude D630               | [58dad68d1d](https://linux-hardware.org/?probe=58dad68d1d) | May 03, 2020 |
| Acer          | Aspire 3810T                | [9be9f49f0d](https://linux-hardware.org/?probe=9be9f49f0d) | May 03, 2020 |
| HP            | Laptop 15-bs0xx             | [40f722892f](https://linux-hardware.org/?probe=40f722892f) | May 03, 2020 |
| Lenovo        | ThinkPad X1 Carbon 34608... | [34eeee2e97](https://linux-hardware.org/?probe=34eeee2e97) | May 03, 2020 |
| Dell          | Latitude E7240              | [ada31e1562](https://linux-hardware.org/?probe=ada31e1562) | May 03, 2020 |
| Dell          | Latitude E5420              | [6ece305dcb](https://linux-hardware.org/?probe=6ece305dcb) | May 03, 2020 |
| ASUSTek       | X200MA                      | [b21018798e](https://linux-hardware.org/?probe=b21018798e) | May 03, 2020 |
| Dell          | Vostro 1700                 | [28816a64b9](https://linux-hardware.org/?probe=28816a64b9) | May 03, 2020 |
| HP            | Notebook                    | [fffd7bab85](https://linux-hardware.org/?probe=fffd7bab85) | May 03, 2020 |
| HP            | Pavilion g6                 | [36190a060b](https://linux-hardware.org/?probe=36190a060b) | May 03, 2020 |
| Acer          | Aspire 5742G                | [3b95947884](https://linux-hardware.org/?probe=3b95947884) | May 03, 2020 |
| Acer          | Aspire A315-21              | [3c875f5cce](https://linux-hardware.org/?probe=3c875f5cce) | May 02, 2020 |
| ASUSTek       | E205SA                      | [7571621a3d](https://linux-hardware.org/?probe=7571621a3d) | May 02, 2020 |
| Lenovo        | Z51-70 80K6                 | [88e2b10d54](https://linux-hardware.org/?probe=88e2b10d54) | May 02, 2020 |
| Dell          | Latitude E6410              | [2f23602ace](https://linux-hardware.org/?probe=2f23602ace) | May 02, 2020 |
| Lenovo        | G50-45 80E3                 | [582a58130b](https://linux-hardware.org/?probe=582a58130b) | May 02, 2020 |
| Acer          | Swift SF114-32              | [172a00d950](https://linux-hardware.org/?probe=172a00d950) | May 01, 2020 |
| Dell          | Latitude D630               | [05ea46edf5](https://linux-hardware.org/?probe=05ea46edf5) | May 01, 2020 |
| Dell          | Latitude E5540              | [3772ccfc75](https://linux-hardware.org/?probe=3772ccfc75) | May 01, 2020 |
| Dell          | Inspiron 7737               | [af18c1f61e](https://linux-hardware.org/?probe=af18c1f61e) | Apr 30, 2020 |
| ASUSTek       | X550VX                      | [6cc63c8d97](https://linux-hardware.org/?probe=6cc63c8d97) | Apr 30, 2020 |
| HP            | EliteBook 8470p             | [cc455e8353](https://linux-hardware.org/?probe=cc455e8353) | Apr 29, 2020 |
| Acer          | Nitro AN515-42              | [8b9ad27475](https://linux-hardware.org/?probe=8b9ad27475) | Apr 29, 2020 |
| ASUSTek       | X550VX                      | [8dd83e435e](https://linux-hardware.org/?probe=8dd83e435e) | Apr 29, 2020 |
| Acer          | TravelMate P246-M           | [a73f0af0e3](https://linux-hardware.org/?probe=a73f0af0e3) | Apr 29, 2020 |
| Dell          | Latitude E5530 non-vPro     | [73d821eb2f](https://linux-hardware.org/?probe=73d821eb2f) | Apr 29, 2020 |
| Lenovo        | G550 20023                  | [b4052e2b99](https://linux-hardware.org/?probe=b4052e2b99) | Apr 29, 2020 |
| HP            | EliteBook 8460p             | [cc0851e314](https://linux-hardware.org/?probe=cc0851e314) | Apr 28, 2020 |
| HP            | EliteBook 8440p             | [456b7a27c2](https://linux-hardware.org/?probe=456b7a27c2) | Apr 26, 2020 |
| HP            | EliteBook 8570p             | [cb9bea6a48](https://linux-hardware.org/?probe=cb9bea6a48) | Apr 26, 2020 |
| HP            | EliteBook 8440p             | [878befa22a](https://linux-hardware.org/?probe=878befa22a) | Apr 25, 2020 |
| Packard Be... | EasyNote TS44HR             | [f761229cd6](https://linux-hardware.org/?probe=f761229cd6) | Apr 25, 2020 |
| HP            | Mini 5101                   | [c0abbe79e6](https://linux-hardware.org/?probe=c0abbe79e6) | Apr 24, 2020 |
| HP            | Mini 5101                   | [8fd41129bc](https://linux-hardware.org/?probe=8fd41129bc) | Apr 24, 2020 |
| Lenovo        | ThinkPad T61 6458WK6        | [25956359b1](https://linux-hardware.org/?probe=25956359b1) | Apr 24, 2020 |
| HP            | Compaq nc4200 (PA750AV)     | [5f47fcb36c](https://linux-hardware.org/?probe=5f47fcb36c) | Apr 24, 2020 |
| Dell          | Inspiron 1010               | [75b73090f8](https://linux-hardware.org/?probe=75b73090f8) | Apr 24, 2020 |
| Acer          | Aspire A315-21G             | [e5d998cd61](https://linux-hardware.org/?probe=e5d998cd61) | Apr 23, 2020 |
| eMachines     | eM250                       | [53a663b394](https://linux-hardware.org/?probe=53a663b394) | Apr 23, 2020 |
| HP            | EliteBook 2560p             | [4b1c02f879](https://linux-hardware.org/?probe=4b1c02f879) | Apr 23, 2020 |
| HP            | EliteBook 8440p             | [18fe9e1834](https://linux-hardware.org/?probe=18fe9e1834) | Apr 22, 2020 |
| Dell          | Latitude E5540              | [7d72490792](https://linux-hardware.org/?probe=7d72490792) | Apr 22, 2020 |
| Lenovo        | 3000 N100 07686VG           | [02617e2da3](https://linux-hardware.org/?probe=02617e2da3) | Apr 22, 2020 |
| Acer          | Aspire V5-123               | [703e5d5a58](https://linux-hardware.org/?probe=703e5d5a58) | Apr 22, 2020 |
| ASUSTek       | X751NA                      | [00df7a44a6](https://linux-hardware.org/?probe=00df7a44a6) | Apr 21, 2020 |
| Dell          | Inspiron 5558               | [d02e383afa](https://linux-hardware.org/?probe=d02e383afa) | Apr 21, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [117134fa79](https://linux-hardware.org/?probe=117134fa79) | Apr 20, 2020 |
| ASUSTek       | K54C                        | [e93a47161f](https://linux-hardware.org/?probe=e93a47161f) | Apr 20, 2020 |
| Dell          | Latitude E5470              | [56593ad320](https://linux-hardware.org/?probe=56593ad320) | Apr 20, 2020 |
| HP            | ProBook 450 G5              | [3ab6f90d86](https://linux-hardware.org/?probe=3ab6f90d86) | Apr 20, 2020 |
| Dell          | Latitude E6540              | [5fa0cb8aac](https://linux-hardware.org/?probe=5fa0cb8aac) | Apr 20, 2020 |
| HP            | ProBook 450 G1              | [4cefaa67d7](https://linux-hardware.org/?probe=4cefaa67d7) | Apr 19, 2020 |
| Samsung       | NC210/NC110                 | [4840b56872](https://linux-hardware.org/?probe=4840b56872) | Apr 19, 2020 |
| Acer          | Aspire one                  | [d840d1f1c8](https://linux-hardware.org/?probe=d840d1f1c8) | Apr 19, 2020 |
| HP            | EliteBook 2570p             | [b0a3f9c7c4](https://linux-hardware.org/?probe=b0a3f9c7c4) | Apr 19, 2020 |
| Acer          | Aspire V3-531               | [efd1eed422](https://linux-hardware.org/?probe=efd1eed422) | Apr 19, 2020 |
| Lenovo        | G505s 20255                 | [2178918e30](https://linux-hardware.org/?probe=2178918e30) | Apr 19, 2020 |
| Lenovo        | G550 20023                  | [4bf5755400](https://linux-hardware.org/?probe=4bf5755400) | Apr 19, 2020 |
| Dell          | Vostro 1015                 | [ddd1946bd2](https://linux-hardware.org/?probe=ddd1946bd2) | Apr 19, 2020 |
| Dell          | Latitude E5540              | [552a8727e3](https://linux-hardware.org/?probe=552a8727e3) | Apr 18, 2020 |
| ASUSTek       | X541SA                      | [d7a0ed87ca](https://linux-hardware.org/?probe=d7a0ed87ca) | Apr 18, 2020 |
| Fujitsu Si... | STYLISTIC ST5112            | [11b436117a](https://linux-hardware.org/?probe=11b436117a) | Apr 18, 2020 |
| Dell          | Latitude E6400              | [5132bac24a](https://linux-hardware.org/?probe=5132bac24a) | Apr 18, 2020 |
| HP            | 250 G7 Notebook PC          | [4c86d4f513](https://linux-hardware.org/?probe=4c86d4f513) | Apr 18, 2020 |
| HP            | 250 G7 Notebook PC          | [9a6b7fa423](https://linux-hardware.org/?probe=9a6b7fa423) | Apr 17, 2020 |
| Samsung       | NC210/NC110                 | [2bfc6d5089](https://linux-hardware.org/?probe=2bfc6d5089) | Apr 17, 2020 |
| Acer          | Aspire V3-531               | [a419a4fa2d](https://linux-hardware.org/?probe=a419a4fa2d) | Apr 17, 2020 |
| Samsung       | NC210/NC110                 | [560c37edcb](https://linux-hardware.org/?probe=560c37edcb) | Apr 17, 2020 |
| HP            | EliteBook 840 G6            | [2943b5a174](https://linux-hardware.org/?probe=2943b5a174) | Apr 17, 2020 |
| Dell          | Latitude E7270              | [7bee223e1c](https://linux-hardware.org/?probe=7bee223e1c) | Apr 17, 2020 |
| Dell          | Latitude E6530              | [3aa4cd1887](https://linux-hardware.org/?probe=3aa4cd1887) | Apr 17, 2020 |
| Dell          | Latitude E6530              | [aca6136878](https://linux-hardware.org/?probe=aca6136878) | Apr 16, 2020 |
| Toshiba       | Satellite C55-C             | [052bdab78d](https://linux-hardware.org/?probe=052bdab78d) | Apr 16, 2020 |
| Fujitsu Si... | ESPRIMO Mobile U9200        | [c886d54d5d](https://linux-hardware.org/?probe=c886d54d5d) | Apr 15, 2020 |
| HP            | 255 G1                      | [4e51f33173](https://linux-hardware.org/?probe=4e51f33173) | Apr 15, 2020 |
| HP            | ProBook 455 G1              | [db987c7f2c](https://linux-hardware.org/?probe=db987c7f2c) | Apr 15, 2020 |
| Dell          | Latitude E6320              | [ddd1262c4d](https://linux-hardware.org/?probe=ddd1262c4d) | Apr 14, 2020 |
| Acer          | Aspire 5710Z                | [8b779c1c32](https://linux-hardware.org/?probe=8b779c1c32) | Apr 14, 2020 |
| MSI           | MS-1228 Ver                 | [806ecba4ae](https://linux-hardware.org/?probe=806ecba4ae) | Apr 14, 2020 |
| HP            | Pavilion dv7                | [2b7a34eac4](https://linux-hardware.org/?probe=2b7a34eac4) | Apr 14, 2020 |
| Lenovo        | ThinkPad T410 2537CS0       | [a28cce80a7](https://linux-hardware.org/?probe=a28cce80a7) | Apr 14, 2020 |
| HP            | Presario CQ57               | [811b113efe](https://linux-hardware.org/?probe=811b113efe) | Apr 13, 2020 |
| Fujitsu Si... | AMILO PRO V2030             | [b4e4a1f374](https://linux-hardware.org/?probe=b4e4a1f374) | Apr 13, 2020 |
| Dell          | Latitude E7470              | [bb80903cd4](https://linux-hardware.org/?probe=bb80903cd4) | Apr 13, 2020 |
| HP            | Presario CQ57               | [cc829427cb](https://linux-hardware.org/?probe=cc829427cb) | Apr 13, 2020 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | [5714b4c927](https://linux-hardware.org/?probe=5714b4c927) | Apr 13, 2020 |
| HP            | Presario CQ57               | [7e8847f054](https://linux-hardware.org/?probe=7e8847f054) | Apr 13, 2020 |
| ASUSTek       | X302LJ                      | [f96917d84c](https://linux-hardware.org/?probe=f96917d84c) | Apr 12, 2020 |
| ASUSTek       | X302LJ                      | [d84b0c6e60](https://linux-hardware.org/?probe=d84b0c6e60) | Apr 12, 2020 |
| Packard Be... | EasyNote TE11HC             | [30591600d3](https://linux-hardware.org/?probe=30591600d3) | Apr 12, 2020 |
| Lenovo        | Yoga 300-11IBY 80M0         | [6696bf32b5](https://linux-hardware.org/?probe=6696bf32b5) | Apr 12, 2020 |
| Dell          | Latitude E6320              | [d1ffc53a12](https://linux-hardware.org/?probe=d1ffc53a12) | Apr 12, 2020 |
| Dell          | Latitude E5440              | [947154f2b3](https://linux-hardware.org/?probe=947154f2b3) | Apr 12, 2020 |
| MSI           | MS-1228 Ver                 | [3e712ae2f6](https://linux-hardware.org/?probe=3e712ae2f6) | Apr 12, 2020 |
| MSI           | MS-1228 Ver                 | [2f89037228](https://linux-hardware.org/?probe=2f89037228) | Apr 12, 2020 |
| Acer          | Aspire E5-573               | [fdfab4d5fc](https://linux-hardware.org/?probe=fdfab4d5fc) | Apr 11, 2020 |
| Lenovo        | Z51-70 80K6                 | [4ef6622ff2](https://linux-hardware.org/?probe=4ef6622ff2) | Apr 11, 2020 |
| HP            | ProBook 450 G1              | [f97c0ded43](https://linux-hardware.org/?probe=f97c0ded43) | Apr 10, 2020 |
| HP            | EliteBook 8470p             | [7541bab08d](https://linux-hardware.org/?probe=7541bab08d) | Apr 10, 2020 |
| HP            | ENVY Notebook               | [9e161b49dd](https://linux-hardware.org/?probe=9e161b49dd) | Apr 10, 2020 |
| Lenovo        | G50-45 80E3                 | [711256bbd3](https://linux-hardware.org/?probe=711256bbd3) | Apr 10, 2020 |
| Lenovo        | G50-80 80E5                 | [0fed3389ef](https://linux-hardware.org/?probe=0fed3389ef) | Apr 09, 2020 |
| Dell          | Latitude E7240              | [3150a762ff](https://linux-hardware.org/?probe=3150a762ff) | Apr 09, 2020 |
| Dell          | Latitude E7240              | [8a18d92a27](https://linux-hardware.org/?probe=8a18d92a27) | Apr 09, 2020 |
| Acer          | AO725                       | [d96e18ebbb](https://linux-hardware.org/?probe=d96e18ebbb) | Apr 09, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [e3305723fe](https://linux-hardware.org/?probe=e3305723fe) | Apr 09, 2020 |
| Dell          | Inspiron 5559               | [945a30f5ab](https://linux-hardware.org/?probe=945a30f5ab) | Apr 08, 2020 |
| HP            | ZBook 15 G2                 | [20bae8e7d6](https://linux-hardware.org/?probe=20bae8e7d6) | Apr 08, 2020 |
| HP            | ZBook 15 G2                 | [854dc319d2](https://linux-hardware.org/?probe=854dc319d2) | Apr 08, 2020 |
| HP            | ProBook 450 G1              | [454b33e2de](https://linux-hardware.org/?probe=454b33e2de) | Apr 08, 2020 |
| HP            | EliteBook 8460p             | [21db702c1f](https://linux-hardware.org/?probe=21db702c1f) | Apr 08, 2020 |
| Chiligreen    | Unknown                     | [e22efac1b5](https://linux-hardware.org/?probe=e22efac1b5) | Apr 07, 2020 |
| Dell          | Latitude E6420              | [63776b0ecb](https://linux-hardware.org/?probe=63776b0ecb) | Apr 07, 2020 |
| HP            | Presario CQ57               | [d18a7c0310](https://linux-hardware.org/?probe=d18a7c0310) | Apr 07, 2020 |
| speedmaste... | E131x series                | [7ee6ac275c](https://linux-hardware.org/?probe=7ee6ac275c) | Apr 07, 2020 |
| ASUSTek       | 1011PX                      | [613772d03c](https://linux-hardware.org/?probe=613772d03c) | Apr 07, 2020 |
| Lenovo        | B50-30 20382                | [70ccb27a0e](https://linux-hardware.org/?probe=70ccb27a0e) | Apr 07, 2020 |
| Alcor         | Intel Education Tablet      | [22e25b4433](https://linux-hardware.org/?probe=22e25b4433) | Apr 07, 2020 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [f3595ffc7d](https://linux-hardware.org/?probe=f3595ffc7d) | Apr 06, 2020 |
| HP            | 550                         | [ab2beb2398](https://linux-hardware.org/?probe=ab2beb2398) | Apr 06, 2020 |
| Dell          | Inspiron 11-3168            | [da83849403](https://linux-hardware.org/?probe=da83849403) | Apr 06, 2020 |
| Dell          | Latitude E6410              | [48ad76329f](https://linux-hardware.org/?probe=48ad76329f) | Apr 05, 2020 |
| Lenovo        | ThinkPad T410 2522A92       | [a95b190952](https://linux-hardware.org/?probe=a95b190952) | Apr 05, 2020 |
| Dell          | Latitude 5480               | [92a070aab4](https://linux-hardware.org/?probe=92a070aab4) | Apr 04, 2020 |
| Lenovo        | IdeaPad S100 20109          | [2829c078d5](https://linux-hardware.org/?probe=2829c078d5) | Apr 04, 2020 |
| Lenovo        | G505s 20255                 | [390fea121d](https://linux-hardware.org/?probe=390fea121d) | Apr 04, 2020 |
| Lenovo        | Flex 2-15 20405             | [f3a0d9bdc7](https://linux-hardware.org/?probe=f3a0d9bdc7) | Apr 04, 2020 |
| Toshiba       | Satellite L50-B             | [cdaf570f74](https://linux-hardware.org/?probe=cdaf570f74) | Apr 04, 2020 |
| Insyde        | M66xN                       | [5686c1435b](https://linux-hardware.org/?probe=5686c1435b) | Apr 04, 2020 |
| Lenovo        | G505 20240                  | [7ee93e59d7](https://linux-hardware.org/?probe=7ee93e59d7) | Apr 04, 2020 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [74fd76934b](https://linux-hardware.org/?probe=74fd76934b) | Apr 03, 2020 |
| Dell          | Inspiron 3543               | [1de56736e0](https://linux-hardware.org/?probe=1de56736e0) | Apr 03, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [20b925b7b2](https://linux-hardware.org/?probe=20b925b7b2) | Apr 03, 2020 |
| HP            | 620                         | [66915e5b24](https://linux-hardware.org/?probe=66915e5b24) | Apr 03, 2020 |
| HP            | EliteBook 2740p             | [46a64c10d7](https://linux-hardware.org/?probe=46a64c10d7) | Apr 02, 2020 |
| Lenovo        | B50-80 80EW                 | [c474dc2345](https://linux-hardware.org/?probe=c474dc2345) | Apr 02, 2020 |
| Lenovo        | B50-80 80EW                 | [724e79ed78](https://linux-hardware.org/?probe=724e79ed78) | Apr 02, 2020 |
| Lenovo        | ThinkPad T500 2056CL8       | [84040ff493](https://linux-hardware.org/?probe=84040ff493) | Apr 02, 2020 |
| Lenovo        | B50-80 80EW                 | [08b048f130](https://linux-hardware.org/?probe=08b048f130) | Apr 01, 2020 |
| Lenovo        | B50-80 80EW                 | [d1ac466914](https://linux-hardware.org/?probe=d1ac466914) | Apr 01, 2020 |
| Packard Be... | EasyNote TS44HR             | [82ddbf9984](https://linux-hardware.org/?probe=82ddbf9984) | Apr 01, 2020 |
| Lenovo        | B50-80 80EW                 | [e71494ee7e](https://linux-hardware.org/?probe=e71494ee7e) | Mar 31, 2020 |
| HP            | 620                         | [051a30cc0f](https://linux-hardware.org/?probe=051a30cc0f) | Mar 31, 2020 |
| Lenovo        | B50-80 80EW                 | [adae1cc4b3](https://linux-hardware.org/?probe=adae1cc4b3) | Mar 31, 2020 |
| Medion        | Unknown                     | [e19febc7b2](https://linux-hardware.org/?probe=e19febc7b2) | Mar 31, 2020 |
| Acer          | Aspire 5349                 | [a8bc8c9290](https://linux-hardware.org/?probe=a8bc8c9290) | Mar 30, 2020 |
| Lenovo        | ThinkPad X201 3680D13       | [04fd353218](https://linux-hardware.org/?probe=04fd353218) | Mar 29, 2020 |
| Acer          | Swift SF114-32              | [c083fb971c](https://linux-hardware.org/?probe=c083fb971c) | Mar 29, 2020 |
| Dell          | Latitude E7240              | [042ac82374](https://linux-hardware.org/?probe=042ac82374) | Mar 29, 2020 |
| Lenovo        | B50-80 80EW                 | [66b91a8ff4](https://linux-hardware.org/?probe=66b91a8ff4) | Mar 28, 2020 |
| Samsung       | RV411/RV511/E3511/S3511/... | [9c84641419](https://linux-hardware.org/?probe=9c84641419) | Mar 28, 2020 |
| ASUSTek       | X541NA                      | [1e51eb504f](https://linux-hardware.org/?probe=1e51eb504f) | Mar 28, 2020 |
| Packard Be... | EasyNote TK11BZ             | [81b20e6f4b](https://linux-hardware.org/?probe=81b20e6f4b) | Mar 28, 2020 |
| ASUSTek       | X55U                        | [0d77eb5730](https://linux-hardware.org/?probe=0d77eb5730) | Mar 27, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [dd21c3aba3](https://linux-hardware.org/?probe=dd21c3aba3) | Mar 27, 2020 |
| HP            | EliteBook 840 G6            | [5ed448ba13](https://linux-hardware.org/?probe=5ed448ba13) | Mar 27, 2020 |
| Lenovo        | G585 20137                  | [6193211eb7](https://linux-hardware.org/?probe=6193211eb7) | Mar 27, 2020 |
| ASUSTek       | X541UJ                      | [f3c8144c70](https://linux-hardware.org/?probe=f3c8144c70) | Mar 26, 2020 |
| Lenovo        | IdeaPad L340-15API 81LW     | [1c6c251445](https://linux-hardware.org/?probe=1c6c251445) | Mar 26, 2020 |
| Lenovo        | IdeaPad L340-15API 81LW     | [44ce2e5bed](https://linux-hardware.org/?probe=44ce2e5bed) | Mar 26, 2020 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [010b5ba201](https://linux-hardware.org/?probe=010b5ba201) | Mar 25, 2020 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [80bc427cc2](https://linux-hardware.org/?probe=80bc427cc2) | Mar 25, 2020 |
| Lenovo        | ThinkPad L490 20Q5002DGE    | [3d3ec4c784](https://linux-hardware.org/?probe=3d3ec4c784) | Mar 25, 2020 |
| HP            | 250 G1                      | [9fd65a1385](https://linux-hardware.org/?probe=9fd65a1385) | Mar 24, 2020 |
| Dell          | Inspiron 5558               | [8c93e0f6e6](https://linux-hardware.org/?probe=8c93e0f6e6) | Mar 24, 2020 |
| Samsung       | R510/P510                   | [3498539c38](https://linux-hardware.org/?probe=3498539c38) | Mar 23, 2020 |
| Samsung       | R510/P510                   | [2ac09f45ec](https://linux-hardware.org/?probe=2ac09f45ec) | Mar 23, 2020 |
| ASUSTek       | X541UJ                      | [ae871c19d9](https://linux-hardware.org/?probe=ae871c19d9) | Mar 23, 2020 |
| HP            | 250 G5 Notebook PC          | [d48b06d02b](https://linux-hardware.org/?probe=d48b06d02b) | Mar 23, 2020 |
| Toshiba       | Satellite L655D             | [c246e763e0](https://linux-hardware.org/?probe=c246e763e0) | Mar 23, 2020 |
| Acer          | AOA150                      | [b046e757aa](https://linux-hardware.org/?probe=b046e757aa) | Mar 22, 2020 |
| Packard Be... | EasyNote LE69KB             | [dd581c1d89](https://linux-hardware.org/?probe=dd581c1d89) | Mar 22, 2020 |
| ASUSTek       | X541UJ                      | [4c75a81d16](https://linux-hardware.org/?probe=4c75a81d16) | Mar 22, 2020 |
| Packard Be... | EasyNote LE69KB             | [5b6f36e504](https://linux-hardware.org/?probe=5b6f36e504) | Mar 22, 2020 |
| Dell          | Latitude E7240              | [2c7176ef63](https://linux-hardware.org/?probe=2c7176ef63) | Mar 22, 2020 |
| Fujitsu Si... | AMILO Pro Series V8210      | [d99250b47c](https://linux-hardware.org/?probe=d99250b47c) | Mar 22, 2020 |
| Lenovo        | G50-45 80E3                 | [cfb803b98c](https://linux-hardware.org/?probe=cfb803b98c) | Mar 21, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [d77f23226e](https://linux-hardware.org/?probe=d77f23226e) | Mar 21, 2020 |
| Albacomp      | Intel powered classmate ... | [0ced530b98](https://linux-hardware.org/?probe=0ced530b98) | Mar 21, 2020 |
| Clevo         | D40EV/D47EV                 | [0e6fd48967](https://linux-hardware.org/?probe=0e6fd48967) | Mar 21, 2020 |
| HP            | ENVY Notebook               | [0aac1919dd](https://linux-hardware.org/?probe=0aac1919dd) | Mar 21, 2020 |
| Dell          | Inspiron 5567               | [7fd82af53f](https://linux-hardware.org/?probe=7fd82af53f) | Mar 20, 2020 |
| Clevo         | D40EV/D47EV                 | [5ea2e0156e](https://linux-hardware.org/?probe=5ea2e0156e) | Mar 20, 2020 |
| Lenovo        | Z50-70 20354                | [2384218ea0](https://linux-hardware.org/?probe=2384218ea0) | Mar 20, 2020 |
| Dell          | Latitude E6410              | [0ee3cac055](https://linux-hardware.org/?probe=0ee3cac055) | Mar 19, 2020 |
| Packard Be... | EasyNote TS44HR             | [31afcbe023](https://linux-hardware.org/?probe=31afcbe023) | Mar 19, 2020 |
| ASUSTek       | K50IE                       | [0d0b6384b6](https://linux-hardware.org/?probe=0d0b6384b6) | Mar 19, 2020 |
| HP            | ENVY Notebook               | [decfe8d3c1](https://linux-hardware.org/?probe=decfe8d3c1) | Mar 18, 2020 |
| HP            | 530                         | [3aebcf0814](https://linux-hardware.org/?probe=3aebcf0814) | Mar 18, 2020 |
| ASUSTek       | X55U                        | [a2579fb8a9](https://linux-hardware.org/?probe=a2579fb8a9) | Mar 18, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [7b303ad125](https://linux-hardware.org/?probe=7b303ad125) | Mar 17, 2020 |
| Acer          | Aspire 5349                 | [491ff33177](https://linux-hardware.org/?probe=491ff33177) | Mar 17, 2020 |
| ASUSTek       | K53BY                       | [7c444e7f57](https://linux-hardware.org/?probe=7c444e7f57) | Mar 17, 2020 |
| Acer          | Aspire 1650                 | [b8567ee0ee](https://linux-hardware.org/?probe=b8567ee0ee) | Mar 17, 2020 |
| Lenovo        | Flex 2-15 20405             | [8f39a07222](https://linux-hardware.org/?probe=8f39a07222) | Mar 16, 2020 |
| HP            | Pavilion 15                 | [7046c208d8](https://linux-hardware.org/?probe=7046c208d8) | Mar 15, 2020 |
| Dell          | Latitude E6540              | [f3c7ac656f](https://linux-hardware.org/?probe=f3c7ac656f) | Mar 15, 2020 |
| ASUSTek       | K50ID                       | [5ad7e03755](https://linux-hardware.org/?probe=5ad7e03755) | Mar 15, 2020 |
| Acer          | TravelMate 6292             | [13a5e4d74d](https://linux-hardware.org/?probe=13a5e4d74d) | Mar 15, 2020 |
| ASUSTek       | X550CC                      | [4180ea3167](https://linux-hardware.org/?probe=4180ea3167) | Mar 15, 2020 |
| Acer          | Aspire 5742G                | [6066a17ff2](https://linux-hardware.org/?probe=6066a17ff2) | Mar 15, 2020 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [ef8db8dba1](https://linux-hardware.org/?probe=ef8db8dba1) | Mar 15, 2020 |
| Packard Be... | EasyNote TS44HR             | [cea0a95fb5](https://linux-hardware.org/?probe=cea0a95fb5) | Mar 15, 2020 |
| Dell          | Latitude E6410              | [d556aaa907](https://linux-hardware.org/?probe=d556aaa907) | Mar 14, 2020 |
| HP            | EliteBook 2530p             | [5c21990489](https://linux-hardware.org/?probe=5c21990489) | Mar 14, 2020 |
| Acer          | Aspire A315-21G             | [7cd95460a9](https://linux-hardware.org/?probe=7cd95460a9) | Mar 14, 2020 |
| ASUSTek       | X55U                        | [18d0a2b9ee](https://linux-hardware.org/?probe=18d0a2b9ee) | Mar 13, 2020 |
| Dell          | Inspiron 5558               | [fa5d5fba02](https://linux-hardware.org/?probe=fa5d5fba02) | Mar 12, 2020 |
| HP            | Notebook                    | [68f27b2e1d](https://linux-hardware.org/?probe=68f27b2e1d) | Mar 11, 2020 |
| Lenovo        | G580 20150                  | [80cf78af28](https://linux-hardware.org/?probe=80cf78af28) | Mar 11, 2020 |
| Toshiba       | PORTEGE R830                | [89a86357f2](https://linux-hardware.org/?probe=89a86357f2) | Mar 11, 2020 |
| HP            | Pavilion 15                 | [8c931f1b85](https://linux-hardware.org/?probe=8c931f1b85) | Mar 10, 2020 |
| ASUSTek       | X550CL                      | [e08640756c](https://linux-hardware.org/?probe=e08640756c) | Mar 10, 2020 |
| HP            | Pavilion 15                 | [e934c5f53a](https://linux-hardware.org/?probe=e934c5f53a) | Mar 10, 2020 |
| HP            | Pavilion 17                 | [7f794d6e4e](https://linux-hardware.org/?probe=7f794d6e4e) | Mar 10, 2020 |
| HP            | Pavilion 17                 | [16e7ffa736](https://linux-hardware.org/?probe=16e7ffa736) | Mar 10, 2020 |
| Dell          | G5 5590                     | [bb140890aa](https://linux-hardware.org/?probe=bb140890aa) | Mar 09, 2020 |
| HP            | 250 G1                      | [cbaab736c7](https://linux-hardware.org/?probe=cbaab736c7) | Mar 09, 2020 |
| Lenovo        | Flex 2-15 20405             | [2f9e0a8dce](https://linux-hardware.org/?probe=2f9e0a8dce) | Mar 09, 2020 |
| HP            | ProBook 6360b               | [0f1094af6f](https://linux-hardware.org/?probe=0f1094af6f) | Mar 08, 2020 |
| HP            | Pavilion g6                 | [072db2873d](https://linux-hardware.org/?probe=072db2873d) | Mar 08, 2020 |
| Lenovo        | IdeaPad S100 20109          | [7a0199a783](https://linux-hardware.org/?probe=7a0199a783) | Mar 08, 2020 |
| ASUSTek       | X71SL                       | [77fff90e12](https://linux-hardware.org/?probe=77fff90e12) | Mar 07, 2020 |
| ASUSTek       | X71SL                       | [7a90ad35d7](https://linux-hardware.org/?probe=7a90ad35d7) | Mar 07, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [1518ac36c0](https://linux-hardware.org/?probe=1518ac36c0) | Mar 07, 2020 |
| HP            | G62                         | [086381cfff](https://linux-hardware.org/?probe=086381cfff) | Mar 07, 2020 |
| Dell          | Latitude E6410              | [c44ea57ed1](https://linux-hardware.org/?probe=c44ea57ed1) | Mar 07, 2020 |
| ASUSTek       | X55CR                       | [78b850564d](https://linux-hardware.org/?probe=78b850564d) | Mar 07, 2020 |
| Dell          | Inspiron 7737               | [22a40c8ccf](https://linux-hardware.org/?probe=22a40c8ccf) | Mar 07, 2020 |
| HP            | OMEN by Laptop 15-ce0xx     | [31ff4ac5f1](https://linux-hardware.org/?probe=31ff4ac5f1) | Mar 07, 2020 |
| ASUSTek       | X550CL                      | [26c49a1705](https://linux-hardware.org/?probe=26c49a1705) | Mar 06, 2020 |
| ASUSTek       | K52Jr                       | [5d736c45e2](https://linux-hardware.org/?probe=5d736c45e2) | Mar 06, 2020 |
| Dell          | Latitude E6530              | [98cd2f4c05](https://linux-hardware.org/?probe=98cd2f4c05) | Mar 05, 2020 |
| Acer          | Aspire E5-571G              | [b7c23a5d5f](https://linux-hardware.org/?probe=b7c23a5d5f) | Mar 05, 2020 |
| Acer          | Aspire E5-571G              | [31a8139552](https://linux-hardware.org/?probe=31a8139552) | Mar 05, 2020 |
| Acer          | TravelMate X349-G2-M        | [45e5b2371a](https://linux-hardware.org/?probe=45e5b2371a) | Mar 05, 2020 |
| Dell          | Latitude D610               | [9b5dd0e798](https://linux-hardware.org/?probe=9b5dd0e798) | Mar 04, 2020 |
| Lenovo        | G550 20023                  | [8fa0b95557](https://linux-hardware.org/?probe=8fa0b95557) | Mar 04, 2020 |
| HP            | Notebook                    | [e297672fde](https://linux-hardware.org/?probe=e297672fde) | Mar 04, 2020 |
| Dell          | Latitude E6410              | [4443ea2ca7](https://linux-hardware.org/?probe=4443ea2ca7) | Mar 03, 2020 |
| HP            | Compaq 6530b (GW688AV)      | [937fec0133](https://linux-hardware.org/?probe=937fec0133) | Mar 03, 2020 |
| Dell          | Inspiron 1501               | [f3ae17034a](https://linux-hardware.org/?probe=f3ae17034a) | Mar 03, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [4af9eb070e](https://linux-hardware.org/?probe=4af9eb070e) | Mar 03, 2020 |
| Dell          | Latitude E6400              | [9730a8dd11](https://linux-hardware.org/?probe=9730a8dd11) | Mar 03, 2020 |
| HP            | 550                         | [216dc37dd4](https://linux-hardware.org/?probe=216dc37dd4) | Mar 03, 2020 |
| Dell          | Inspiron 7559               | [35d7e25844](https://linux-hardware.org/?probe=35d7e25844) | Mar 02, 2020 |
| Dell          | Inspiron 7737               | [cc827bed84](https://linux-hardware.org/?probe=cc827bed84) | Mar 02, 2020 |
| HP            | EliteBook 8470p             | [86481261f8](https://linux-hardware.org/?probe=86481261f8) | Mar 02, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Hungary/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| BlackPanther 18.1            | 996       | 52.06%  |
| BlackPanther 16.2            | 157       | 8.21%   |
| Ubuntu 20.04                 | 153       | 8%      |
| Ubuntu 18.04                 | 93        | 4.86%   |
| OpenMandriva 4.2             | 21        | 1.1%    |
| Linux Mint 20.2              | 18        | 0.94%   |
| Linux Mint 19.3              | 15        | 0.78%   |
| Arch                         | 13        | 0.68%   |
| Ubuntu 19.10                 | 11        | 0.58%   |
| Linux Mint 20.3              | 11        | 0.58%   |
| Kubuntu 20.04                | 11        | 0.58%   |
| ArcoLinux Rolling            | 11        | 0.58%   |
| Ubuntu 21.10                 | 10        | 0.52%   |
| Ubuntu 21.04                 | 10        | 0.52%   |
| OpenMandriva 4.3             | 10        | 0.52%   |
| KDE neon 20.04               | 10        | 0.52%   |
| Fedora 35                    | 10        | 0.52%   |
| Fedora 33                    | 10        | 0.52%   |
| Ubuntu 19.04                 | 9         | 0.47%   |
| Ubuntu 16.04                 | 9         | 0.47%   |
| Linux Mint 20                | 9         | 0.47%   |
| Debian 11                    | 9         | 0.47%   |
| Debian 10                    | 9         | 0.47%   |
| Manjaro                      | 8         | 0.42%   |
| Linux Mint 20.1              | 8         | 0.42%   |
| Endless 3.9.5                | 8         | 0.42%   |
| Xubuntu 20.04                | 7         | 0.37%   |
| Xubuntu 18.04                | 7         | 0.37%   |
| Ubuntu 22.04                 | 6         | 0.31%   |
| Ubuntu 20.10                 | 6         | 0.31%   |
| Pop!_OS 21.04                | 6         | 0.31%   |
| Endless 3.9.1                | 6         | 0.31%   |
| Endless 3.8.0                | 6         | 0.31%   |
| Zorin 16                     | 5         | 0.26%   |
| openSUSE Tumbleweed-XXXXXXXX | 5         | 0.26%   |
| Fedora 34                    | 5         | 0.26%   |
| Fedora 32                    | 5         | 0.26%   |
| Endless 3.7.7                | 5         | 0.26%   |
| Endless 3.7.5                | 5         | 0.26%   |
| Endless 3.3.19               | 5         | 0.26%   |
| Arch Rolling                 | 5         | 0.26%   |
| Zorin 15                     | 4         | 0.21%   |
| ROSA R10                     | 4         | 0.21%   |
| Pop!_OS 20.10                | 4         | 0.21%   |
| Fedora 36                    | 4         | 0.21%   |
| Endless 3.7.8                | 4         | 0.21%   |
| Endless 3.5.8                | 4         | 0.21%   |
| Endless 3.5.3                | 4         | 0.21%   |
| Debian Testing               | 4         | 0.21%   |
| Ubuntu Budgie 20.04          | 3         | 0.16%   |
| ROSA R9                      | 3         | 0.16%   |
| Pop!_OS 21.10                | 3         | 0.16%   |
| Pop!_OS 20.04                | 3         | 0.16%   |
| Manjaro 21.2.1               | 3         | 0.16%   |
| Linux Mint 19.2              | 3         | 0.16%   |
| Endless 3.9.4                | 3         | 0.16%   |
| Endless 3.9.3                | 3         | 0.16%   |
| Endless 3.8.7                | 3         | 0.16%   |
| Endless 3.8.4                | 3         | 0.16%   |
| Endless 3.6.2                | 3         | 0.16%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| BlackPanther  | 1130      | 61.78%  |
| Ubuntu        | 296       | 16.18%  |
| Endless       | 69        | 3.77%   |
| Linux Mint    | 61        | 3.34%   |
| Fedora        | 34        | 1.86%   |
| OpenMandriva  | 33        | 1.8%    |
| Debian        | 24        | 1.31%   |
| Manjaro       | 20        | 1.09%   |
| Xubuntu       | 17        | 0.93%   |
| Arch          | 17        | 0.93%   |
| Pop!_OS       | 16        | 0.87%   |
| Kubuntu       | 16        | 0.87%   |
| ArcoLinux     | 13        | 0.71%   |
| ROSA          | 12        | 0.66%   |
| KDE neon      | 12        | 0.66%   |
| Zorin         | 9         | 0.49%   |
| openSUSE      | 8         | 0.44%   |
| Elementary    | 6         | 0.33%   |
| Lubuntu       | 5         | 0.27%   |
| Ubuntu Budgie | 4         | 0.22%   |
| Kali          | 3         | 0.16%   |
| Clear Linux   | 3         | 0.16%   |
| UbuntuDDE     | 2         | 0.11%   |
| Gentoo        | 2         | 0.11%   |
| Devuan        | 2         | 0.11%   |
| Xero          | 1         | 0.05%   |
| UHU           | 1         | 0.05%   |
| Ubuntu Studio | 1         | 0.05%   |
| Ubuntu MATE   | 1         | 0.05%   |
| SteamOS       | 1         | 0.05%   |
| Solus         | 1         | 0.05%   |
| PCLinuxOS     | 1         | 0.05%   |
| Parrot        | 1         | 0.05%   |
| MX            | 1         | 0.05%   |
| LMDE          | 1         | 0.05%   |
| Garuda Linux  | 1         | 0.05%   |
| EndeavourOS   | 1         | 0.05%   |
| Chrome OS     | 1         | 0.05%   |
| Archman       | 1         | 0.05%   |
| antiX         | 1         | 0.05%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 4.18.16-desktop-1bP      | 755       | 35.9%   |
| 5.6.14-desktop-2bP       | 292       | 13.88%  |
| 4.9.20-desktop-pae-1bP   | 148       | 7.04%   |
| 5.1.15-desktop-1bP       | 56        | 2.66%   |
| 5.4.0-42-generic         | 28        | 1.33%   |
| 5.8.0-14-generic         | 22        | 1.05%   |
| 5.10.14-desktop-1omv4002 | 20        | 0.95%   |
| 5.4.0-58-generic         | 14        | 0.67%   |
| 4.18.0-15-generic        | 14        | 0.67%   |
| 5.3.0-28-generic         | 12        | 0.57%   |
| 5.4.0-52-generic         | 11        | 0.52%   |
| 5.4.0-48-generic         | 11        | 0.52%   |
| 5.4.0-19-generic         | 11        | 0.52%   |
| 5.11.0-27-generic        | 11        | 0.52%   |
| 5.16.7-desktop-1omv4003  | 10        | 0.48%   |
| 5.4.0-40-generic         | 9         | 0.43%   |
| 5.4.0-29-generic         | 9         | 0.43%   |
| 5.11.0-34-generic        | 9         | 0.43%   |
| 5.4.0-54-generic         | 7         | 0.33%   |
| 5.4.0-26-generic         | 7         | 0.33%   |
| 5.8.0-53-generic         | 6         | 0.29%   |
| 5.4.0-91-generic         | 6         | 0.29%   |
| 5.4.0-81-generic         | 6         | 0.29%   |
| 5.4.0-39-generic         | 6         | 0.29%   |
| 5.3.0-23-generic         | 6         | 0.29%   |
| 5.13.0-27-generic        | 6         | 0.29%   |
| 5.11.0-40-generic        | 6         | 0.29%   |
| 4.15.0-43-generic        | 6         | 0.29%   |
| 4.13.0-32-generic        | 6         | 0.29%   |
| 5.8.0-59-generic         | 5         | 0.24%   |
| 5.3.0-42-generic         | 5         | 0.24%   |
| 5.3.0-40-generic         | 5         | 0.24%   |
| 5.3.0-26-generic         | 5         | 0.24%   |
| 5.13.0-28-generic        | 5         | 0.24%   |
| 5.0.0-37-generic         | 5         | 0.24%   |
| 5.0.0-32-generic         | 5         | 0.24%   |
| 5.0.0-25-generic         | 5         | 0.24%   |
| 5.0.0-20-generic         | 5         | 0.24%   |
| 4.9.20-desktop-1bP       | 5         | 0.24%   |
| 4.15.0-72-generic        | 5         | 0.24%   |
| 4.15.0-20-generic        | 5         | 0.24%   |
| 5.8.0-48-generic         | 4         | 0.19%   |
| 5.8.0-43-generic         | 4         | 0.19%   |
| 5.4.0-92-generic         | 4         | 0.19%   |
| 5.4.0-84-generic         | 4         | 0.19%   |
| 5.4.0-74-generic         | 4         | 0.19%   |
| 5.4.0-73-generic         | 4         | 0.19%   |
| 5.4.0-70-generic         | 4         | 0.19%   |
| 5.4.0-66-generic         | 4         | 0.19%   |
| 5.4.0-45-generic         | 4         | 0.19%   |
| 5.4.0-31-generic         | 4         | 0.19%   |
| 5.4.0-100-generic        | 4         | 0.19%   |
| 5.3.0-46-generic         | 4         | 0.19%   |
| 5.3.0-24-generic         | 4         | 0.19%   |
| 5.0.0-23-generic         | 4         | 0.19%   |
| 5.0.0-13-generic         | 4         | 0.19%   |
| 4.18.0-25-generic        | 4         | 0.19%   |
| 4.18.0-11-generic        | 4         | 0.19%   |
| 4.16.0-4-generic         | 4         | 0.19%   |
| 4.15.0-96-generic        | 4         | 0.19%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18.16 | 755       | 36.97%  |
| 5.6.14  | 292       | 14.3%   |
| 5.4.0   | 189       | 9.26%   |
| 4.9.20  | 156       | 7.64%   |
| 4.15.0  | 65        | 3.18%   |
| 5.8.0   | 60        | 2.94%   |
| 5.1.15  | 56        | 2.74%   |
| 5.11.0  | 52        | 2.55%   |
| 5.3.0   | 51        | 2.5%    |
| 5.13.0  | 40        | 1.96%   |
| 5.0.0   | 33        | 1.62%   |
| 4.18.0  | 30        | 1.47%   |
| 5.10.14 | 20        | 0.98%   |
| 5.10.0  | 19        | 0.93%   |
| 5.15.0  | 12        | 0.59%   |
| 5.16.7  | 11        | 0.54%   |
| 4.19.0  | 9         | 0.44%   |
| 4.13.0  | 8         | 0.39%   |
| 5.9.0   | 6         | 0.29%   |
| 4.4.0   | 6         | 0.29%   |
| 5.15.12 | 4         | 0.2%    |
| 5.12.9  | 4         | 0.2%    |
| 5.12.4  | 4         | 0.2%    |
| 5.10.7  | 4         | 0.2%    |
| 4.16.0  | 4         | 0.2%    |
| 5.8.16  | 3         | 0.15%   |
| 5.8.14  | 3         | 0.15%   |
| 5.3.18  | 3         | 0.15%   |
| 5.17.1  | 3         | 0.15%   |
| 5.16.2  | 3         | 0.15%   |
| 5.16.18 | 3         | 0.15%   |
| 5.16.0  | 3         | 0.15%   |
| 5.14.0  | 3         | 0.15%   |
| 5.13.13 | 3         | 0.15%   |
| 5.11.16 | 3         | 0.15%   |
| 4.9.60  | 3         | 0.15%   |
| 5.9.16  | 2         | 0.1%    |
| 5.9.1   | 2         | 0.1%    |
| 5.7.11  | 2         | 0.1%    |
| 5.6.15  | 2         | 0.1%    |
| 5.6.13  | 2         | 0.1%    |
| 5.4.83  | 2         | 0.1%    |
| 5.4.15  | 2         | 0.1%    |
| 5.16.19 | 2         | 0.1%    |
| 5.16.16 | 2         | 0.1%    |
| 5.15.6  | 2         | 0.1%    |
| 5.15.41 | 2         | 0.1%    |
| 5.14.16 | 2         | 0.1%    |
| 5.14.14 | 2         | 0.1%    |
| 5.12.11 | 2         | 0.1%    |
| 5.11.2  | 2         | 0.1%    |
| 5.11.15 | 2         | 0.1%    |
| 5.10.11 | 2         | 0.1%    |
| 5.10.1  | 2         | 0.1%    |
| 4.9.0   | 2         | 0.1%    |
| 4.7.0   | 2         | 0.1%    |
| 5.9.8   | 1         | 0.05%   |
| 5.9.6   | 1         | 0.05%   |
| 5.9.11  | 1         | 0.05%   |
| 5.8.7   | 1         | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18    | 784       | 38.58%  |
| 5.6     | 302       | 14.86%  |
| 5.4     | 201       | 9.89%   |
| 4.9     | 163       | 8.02%   |
| 5.8     | 70        | 3.44%   |
| 4.15    | 65        | 3.2%    |
| 5.11    | 62        | 3.05%   |
| 5.3     | 56        | 2.76%   |
| 5.1     | 56        | 2.76%   |
| 5.10    | 52        | 2.56%   |
| 5.13    | 44        | 2.17%   |
| 5.0     | 33        | 1.62%   |
| 5.16    | 26        | 1.28%   |
| 5.15    | 26        | 1.28%   |
| 5.12    | 15        | 0.74%   |
| 5.9     | 13        | 0.64%   |
| 4.19    | 10        | 0.49%   |
| 5.14    | 9         | 0.44%   |
| 4.13    | 8         | 0.39%   |
| 5.17    | 7         | 0.34%   |
| 5.7     | 6         | 0.3%    |
| 4.4     | 6         | 0.3%    |
| 5.5     | 4         | 0.2%    |
| 5.18    | 4         | 0.2%    |
| 4.16    | 4         | 0.2%    |
| 4.7     | 2         | 0.1%    |
| 5.2     | 1         | 0.05%   |
| 5.19    | 1         | 0.05%   |
| 4.14    | 1         | 0.05%   |
| 4.1     | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 1619      | 89.55%  |
| i686   | 189       | 10.45%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KDE5            | 1196      | 65%     |
| GNOME           | 310       | 16.85%  |
| Unknown         | 136       | 7.39%   |
| XFCE            | 46        | 2.5%    |
| X-Cinnamon      | 41        | 2.23%   |
| KDE             | 23        | 1.25%   |
| MATE            | 21        | 1.14%   |
| Cinnamon        | 16        | 0.87%   |
| Unity           | 9         | 0.49%   |
| KDE4            | 9         | 0.49%   |
| Pantheon        | 6         | 0.33%   |
| LXQt            | 5         | 0.27%   |
| Budgie          | 5         | 0.27%   |
| GNOME Flashback | 4         | 0.22%   |
| Deepin          | 4         | 0.22%   |
| i3              | 3         | 0.16%   |
| qtile           | 1         | 0.05%   |
| LXDE            | 1         | 0.05%   |
| ICEWM           | 1         | 0.05%   |
| GNOME Classic   | 1         | 0.05%   |
| bspwm           | 1         | 0.05%   |
| awesome         | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 1663      | 91.52%  |
| Unknown | 82        | 4.51%   |
| Wayland | 67        | 3.69%   |
| Tty     | 5         | 0.28%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 1194      | 65.39%  |
| Unknown | 415       | 22.73%  |
| GDM     | 92        | 5.04%   |
| LightDM | 46        | 2.52%   |
| TDM     | 34        | 1.86%   |
| GDM3    | 31        | 1.7%    |
| KDM     | 9         | 0.49%   |
| SLiM    | 3         | 0.16%   |
| XDM     | 2         | 0.11%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1239      | 67.56%  |
| hu_HU   | 376       | 20.5%   |
| en_US   | 185       | 10.09%  |
| en_GB   | 15        | 0.82%   |
| C       | 9         | 0.49%   |
| de_DE   | 4         | 0.22%   |
| nl_NL   | 2         | 0.11%   |
| ru_UA   | 1         | 0.05%   |
| ru_RU   | 1         | 0.05%   |
| fr_BE   | 1         | 0.05%   |
| en_AU   | 1         | 0.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 1117      | 59.96%  |
| EFI  | 746       | 40.04%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 1072      | 54.97%  |
| Overlay | 765       | 39.23%  |
| Unknown | 57        | 2.92%   |
| Btrfs   | 42        | 2.15%   |
| Ext2    | 6         | 0.31%   |
| Ext3    | 4         | 0.21%   |
| Xfs     | 2         | 0.1%    |
| Zfs     | 1         | 0.05%   |
| F2fs    | 1         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| MBR     | 869       | 46.62%  |
| GPT     | 557       | 29.88%  |
| Unknown | 438       | 23.5%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1463      | 76.04%  |
| Yes       | 461       | 23.96%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1075      | 56.76%  |
| Yes       | 819       | 43.24%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 374       | 20.95%  |
| Hewlett-Packard     | 349       | 19.55%  |
| Dell                | 312       | 17.48%  |
| ASUSTek Computer    | 255       | 14.29%  |
| Acer                | 201       | 11.26%  |
| Toshiba             | 50        | 2.8%    |
| Samsung Electronics | 34        | 1.9%    |
| Fujitsu Siemens     | 34        | 1.9%    |
| Packard Bell        | 28        | 1.57%   |
| Fujitsu             | 26        | 1.46%   |
| eMachines           | 17        | 0.95%   |
| MSI                 | 16        | 0.9%    |
| Medion              | 14        | 0.78%   |
| Sony                | 12        | 0.67%   |
| Apple               | 8         | 0.45%   |
| Hungaro Flotta Kft  | 7         | 0.39%   |
| Alcor               | 6         | 0.34%   |
| HUAWEI              | 5         | 0.28%   |
| Intel               | 3         | 0.17%   |
| Insyde              | 3         | 0.17%   |
| Clevo               | 3         | 0.17%   |
| Unknown             | 3         | 0.17%   |
| TUXEDO              | 2         | 0.11%   |
| Timi                | 2         | 0.11%   |
| speedmaster         | 2         | 0.11%   |
| Panasonic           | 2         | 0.11%   |
| Notebook            | 2         | 0.11%   |
| Gigabyte Technology | 2         | 0.11%   |
| Valve               | 1         | 0.06%   |
| ordissimo           | 1         | 0.06%   |
| NEC Computers       | 1         | 0.06%   |
| Minix               | 1         | 0.06%   |
| LG Electronics      | 1         | 0.06%   |
| IBM                 | 1         | 0.06%   |
| Chiligreen          | 1         | 0.06%   |
| BenQ                | 1         | 0.06%   |
| AMI                 | 1         | 0.06%   |
| Allview             | 1         | 0.06%   |
| Albacomp            | 1         | 0.06%   |
| Acidanthera         | 1         | 0.06%   |
| A15HV01             | 1         | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| HP 250 G1                            | 41        | 2.3%    |
| Dell Latitude E6410                  | 17        | 0.95%   |
| Unknown                              | 12        | 0.67%   |
| Lenovo IdeaPad 100-15IBD 80QQ        | 10        | 0.56%   |
| Lenovo G50-45 80E3                   | 10        | 0.56%   |
| HP 650                               | 10        | 0.56%   |
| Lenovo IdeaPad 330-15IKB 81DE        | 9         | 0.5%    |
| HP Notebook                          | 9         | 0.5%    |
| HP 620                               | 9         | 0.5%    |
| Dell Latitude E6400                  | 9         | 0.5%    |
| Lenovo ThinkPad T400 2768WGB         | 8         | 0.45%   |
| HP Pavilion 15                       | 8         | 0.45%   |
| Dell Latitude E6530                  | 8         | 0.45%   |
| Dell Latitude E6420                  | 8         | 0.45%   |
| Lenovo G550 20023                    | 7         | 0.39%   |
| HP EliteBook 8460p                   | 7         | 0.39%   |
| HP EliteBook 6930p                   | 7         | 0.39%   |
| Dell Inspiron 15-3567                | 7         | 0.39%   |
| ASUS VivoBook 15_ASUS Laptop X540UBR | 7         | 0.39%   |
| Lenovo Z50-70 20354                  | 6         | 0.34%   |
| Lenovo G580 20150                    | 6         | 0.34%   |
| HP Pavilion g6                       | 6         | 0.34%   |
| HP EliteBook 8440p                   | 6         | 0.34%   |
| HP EliteBook 2560p                   | 6         | 0.34%   |
| eMachines E525                       | 6         | 0.34%   |
| Dell Vostro 15-3568                  | 6         | 0.34%   |
| Dell Latitude E6430                  | 6         | 0.34%   |
| Dell Latitude E5420                  | 6         | 0.34%   |
| Dell Inspiron N5110                  | 6         | 0.34%   |
| Dell Inspiron 5558                   | 6         | 0.34%   |
| ASUS X541NA                          | 6         | 0.34%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR | 6         | 0.34%   |
| ASUS K50IJ                           | 6         | 0.34%   |
| ASUS 1011PX                          | 6         | 0.34%   |
| Toshiba Satellite L300               | 5         | 0.28%   |
| Lenovo Z50-75 80EC                   | 5         | 0.28%   |
| Lenovo IdeaPad 110-15IBR 80T7        | 5         | 0.28%   |
| Lenovo IdeaPad 100-15IBY 80MJ        | 5         | 0.28%   |
| Lenovo G505s 20255                   | 5         | 0.28%   |
| Lenovo G50-30 80G0                   | 5         | 0.28%   |
| HP ProBook 6450b                     | 5         | 0.28%   |
| HP EliteBook 8540p                   | 5         | 0.28%   |
| HP EliteBook 8470p                   | 5         | 0.28%   |
| Dell Latitude E7450                  | 5         | 0.28%   |
| Dell Latitude E7240                  | 5         | 0.28%   |
| Dell Latitude E4310                  | 5         | 0.28%   |
| Dell Latitude D630                   | 5         | 0.28%   |
| Dell Inspiron 3542                   | 5         | 0.28%   |
| Dell Inspiron 3521                   | 5         | 0.28%   |
| ASUS X540LA                          | 5         | 0.28%   |
| Toshiba Satellite C660               | 4         | 0.22%   |
| Lenovo G570 20079                    | 4         | 0.22%   |
| Hungaro Flotta Kft Navon Loop 360    | 4         | 0.22%   |
| HP Pavilion Notebook                 | 4         | 0.22%   |
| HP EliteBook 8570p                   | 4         | 0.22%   |
| HP EliteBook 2570p                   | 4         | 0.22%   |
| HP EliteBook 2540p                   | 4         | 0.22%   |
| HP 250 G6 Notebook PC                | 4         | 0.22%   |
| HP 250 G5 Notebook PC                | 4         | 0.22%   |
| Fujitsu Siemens ESPRIMO Mobile V5535 | 4         | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 159       | 8.91%   |
| Dell Latitude            | 158       | 8.85%   |
| Acer Aspire              | 145       | 8.12%   |
| Dell Inspiron            | 99        | 5.55%   |
| Lenovo IdeaPad           | 95        | 5.32%   |
| HP EliteBook             | 74        | 4.15%   |
| HP 250                   | 56        | 3.14%   |
| HP ProBook               | 54        | 3.03%   |
| ASUS VivoBook            | 52        | 2.91%   |
| Toshiba Satellite        | 44        | 2.46%   |
| HP Pavilion              | 37        | 2.07%   |
| Packard Bell EasyNote    | 28        | 1.57%   |
| HP Compaq                | 28        | 1.57%   |
| Dell Vostro              | 24        | 1.34%   |
| Fujitsu LIFEBOOK         | 23        | 1.29%   |
| Fujitsu Siemens AMILO    | 19        | 1.06%   |
| Acer TravelMate          | 17        | 0.95%   |
| HP Laptop                | 14        | 0.78%   |
| Acer Swift               | 14        | 0.78%   |
| Unknown                  | 12        | 0.67%   |
| Lenovo G50-45            | 10        | 0.56%   |
| HP 650                   | 10        | 0.56%   |
| Lenovo 3000              | 9         | 0.5%    |
| HP Notebook              | 9         | 0.5%    |
| HP 620                   | 9         | 0.5%    |
| Fujitsu Siemens ESPRIMO  | 9         | 0.5%    |
| Dell Precision           | 9         | 0.5%    |
| Lenovo G580              | 8         | 0.45%   |
| HP ZBook                 | 8         | 0.45%   |
| Lenovo G550              | 7         | 0.39%   |
| Hungaro Flotta Kft Navon | 7         | 0.39%   |
| HP Presario              | 7         | 0.39%   |
| Lenovo Z50-70            | 6         | 0.34%   |
| Lenovo ThinkBook         | 6         | 0.34%   |
| HP 255                   | 6         | 0.34%   |
| eMachines E525           | 6         | 0.34%   |
| Dell System              | 6         | 0.34%   |
| ASUS X541NA              | 6         | 0.34%   |
| ASUS K50IJ               | 6         | 0.34%   |
| ASUS 1011PX              | 6         | 0.34%   |
| Acer Extensa             | 6         | 0.34%   |
| Lenovo Z50-75            | 5         | 0.28%   |
| Lenovo Yoga              | 5         | 0.28%   |
| Lenovo G505s             | 5         | 0.28%   |
| Lenovo G50-30            | 5         | 0.28%   |
| HP OMEN                  | 5         | 0.28%   |
| Fujitsu Siemens LIFEBOOK | 5         | 0.28%   |
| Dell XPS                 | 5         | 0.28%   |
| ASUS ZenBook             | 5         | 0.28%   |
| ASUS X540LA              | 5         | 0.28%   |
| ASUS Strix               | 5         | 0.28%   |
| ASUS ROG                 | 5         | 0.28%   |
| Medion Akoya             | 4         | 0.22%   |
| Lenovo Legion            | 4         | 0.22%   |
| Lenovo G570              | 4         | 0.22%   |
| HP ENVY                  | 4         | 0.22%   |
| HP 530                   | 4         | 0.22%   |
| Dell G5                  | 4         | 0.22%   |
| Dell G3                  | 4         | 0.22%   |
| ASUS X55U                | 4         | 0.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 196       | 10.98%  |
| 2013    | 170       | 9.52%   |
| 2010    | 164       | 9.19%   |
| 2018    | 146       | 8.18%   |
| 2012    | 135       | 7.56%   |
| 2015    | 126       | 7.06%   |
| 2008    | 119       | 6.67%   |
| 2016    | 117       | 6.55%   |
| 2014    | 113       | 6.33%   |
| 2017    | 107       | 5.99%   |
| 2009    | 107       | 5.99%   |
| 2007    | 86        | 4.82%   |
| 2019    | 76        | 4.26%   |
| 2020    | 54        | 3.03%   |
| 2006    | 35        | 1.96%   |
| 2021    | 19        | 1.06%   |
| 2005    | 11        | 0.62%   |
| 2022    | 2         | 0.11%   |
| Unknown | 2         | 0.11%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1785      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1721      | 95.93%  |
| Enabled  | 73        | 4.07%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1785      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 665       | 36.24%  |
| 4.01-8.0   | 428       | 23.32%  |
| 8.01-16.0  | 229       | 12.48%  |
| 1.01-2.0   | 224       | 12.21%  |
| 16.01-24.0 | 125       | 6.81%   |
| 2.01-3.0   | 84        | 4.58%   |
| 32.01-64.0 | 41        | 2.23%   |
| 0.51-1.0   | 30        | 1.63%   |
| 24.01-32.0 | 8         | 0.44%   |
| 0.01-0.5   | 1         | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.51-1.0   | 784       | 37.4%   |
| 1.01-2.0   | 682       | 32.54%  |
| 2.01-3.0   | 222       | 10.59%  |
| 0.01-0.5   | 183       | 8.73%   |
| 3.01-4.0   | 104       | 4.96%   |
| 4.01-8.0   | 91        | 4.34%   |
| 8.01-16.0  | 29        | 1.38%   |
| 16.01-24.0 | 1         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1448      | 78.19%  |
| 2      | 347       | 18.74%  |
| 3      | 34        | 1.84%   |
| 0      | 17        | 0.92%   |
| 4      | 5         | 0.27%   |
| 5      | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1051      | 58.26%  |
| No        | 753       | 41.74%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1626      | 90.79%  |
| No        | 165       | 9.21%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1764      | 98.82%  |
| No        | 21        | 1.18%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1313      | 72.5%   |
| No        | 498       | 27.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Hungary | 1785      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Budapest          | 728       | 35.24%  |
| Pécs             | 44        | 2.13%   |
| Miskolc           | 44        | 2.13%   |
| Debrecen          | 42        | 2.03%   |
| Szeged            | 40        | 1.94%   |
| Győr             | 35        | 1.69%   |
| Székesfehérvár | 32        | 1.55%   |
| Tatabánya        | 31        | 1.5%    |
| Veszprém         | 28        | 1.36%   |
| Szombathely       | 24        | 1.16%   |
| Nyiregyhaza       | 23        | 1.11%   |
| Kecskemét        | 22        | 1.06%   |
| Zalaegerszeg      | 20        | 0.97%   |
| Érd              | 20        | 0.97%   |
| Szigetszentmiklos | 17        | 0.82%   |
| Dunaújváros     | 16        | 0.77%   |
| Toekoel           | 15        | 0.73%   |
| Szolnok           | 15        | 0.73%   |
| Szekszárd        | 15        | 0.73%   |
| Salgotarjan       | 13        | 0.63%   |
| Szorgalmatos      | 12        | 0.58%   |
| Sopron            | 11        | 0.53%   |
| Pomaz             | 11        | 0.53%   |
| Kaposvár         | 11        | 0.53%   |
| Gyomro            | 11        | 0.53%   |
| Maglod            | 10        | 0.48%   |
| Kiskunfelegyhaza  | 10        | 0.48%   |
| Kazincbarcika     | 10        | 0.48%   |
| Oroshaza          | 9         | 0.44%   |
| Monor             | 9         | 0.44%   |
| Gödöllő        | 9         | 0.44%   |
| Cegled            | 9         | 0.44%   |
| Ajka              | 9         | 0.44%   |
| Tiszaujvaros      | 8         | 0.39%   |
| Tata              | 8         | 0.39%   |
| Tarnok            | 8         | 0.39%   |
| Solymar           | 8         | 0.39%   |
| Siófok           | 8         | 0.39%   |
| Nagykanizsa       | 8         | 0.39%   |
| Karcag            | 8         | 0.39%   |
| Hatvan            | 8         | 0.39%   |
| Békéscsaba      | 8         | 0.39%   |
| Toeroekbalint     | 7         | 0.34%   |
| Mosonmagyaróvár | 7         | 0.34%   |
| Jaszbereny        | 7         | 0.34%   |
| Hodmezovasarhely  | 7         | 0.34%   |
| Fot               | 7         | 0.34%   |
| Esztergom         | 7         | 0.34%   |
| Veresegyhaz       | 6         | 0.29%   |
| Szentendre        | 6         | 0.29%   |
| Budakeszi         | 6         | 0.29%   |
| Baja              | 6         | 0.29%   |
| Vecses            | 5         | 0.24%   |
| Tolna             | 5         | 0.24%   |
| Szerencs          | 5         | 0.24%   |
| Papa              | 5         | 0.24%   |
| Mezobereny        | 5         | 0.24%   |
| Mako              | 5         | 0.24%   |
| Eger              | 5         | 0.24%   |
| Dunakeszi         | 5         | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 346       | 495    | 15.62%  |
| WDC                       | 302       | 422    | 13.63%  |
| Kingston                  | 236       | 329    | 10.65%  |
| Samsung Electronics       | 233       | 345    | 10.52%  |
| Toshiba                   | 229       | 327    | 10.34%  |
| HGST                      | 129       | 181    | 5.82%   |
| Hitachi                   | 127       | 171    | 5.73%   |
| Unknown                   | 87        | 120    | 3.93%   |
| SanDisk                   | 81        | 131    | 3.66%   |
| SK hynix                  | 56        | 84     | 2.53%   |
| Intel                     | 52        | 73     | 2.35%   |
| Fujitsu                   | 42        | 54     | 1.9%    |
| Micron Technology         | 32        | 43     | 1.44%   |
| Crucial                   | 31        | 50     | 1.4%    |
| A-DATA Technology         | 26        | 36     | 1.17%   |
| SPCC                      | 17        | 21     | 0.77%   |
| JMicron Technology        | 17        | 18     | 0.77%   |
| Apacer                    | 17        | 30     | 0.77%   |
| LITEON                    | 12        | 14     | 0.54%   |
| PNY                       | 10        | 15     | 0.45%   |
| Kingmax                   | 9         | 9      | 0.41%   |
| China                     | 8         | 15     | 0.36%   |
| Transcend                 | 7         | 7      | 0.32%   |
| KingSpec                  | 7         | 8      | 0.32%   |
| Intenso                   | 7         | 14     | 0.32%   |
| Gigabyte Technology       | 7         | 10     | 0.32%   |
| OCZ                       | 6         | 6      | 0.27%   |
| Phison                    | 5         | 6      | 0.23%   |
| LITEONIT                  | 5         | 7      | 0.23%   |
| KIOXIA                    | 5         | 5      | 0.23%   |
| Goodram                   | 5         | 6      | 0.23%   |
| ASMT                      | 5         | 7      | 0.23%   |
| Team                      | 4         | 6      | 0.18%   |
| Patriot                   | 4         | 6      | 0.18%   |
| Apple                     | 4         | 5      | 0.18%   |
| Verbatim                  | 3         | 4      | 0.14%   |
| SSSTC                     | 3         | 4      | 0.14%   |
| IBM/Hitachi               | 3         | 4      | 0.14%   |
| BHT                       | 3         | 3      | 0.14%   |
| Zheino                    | 2         | 2      | 0.09%   |
| XPG                       | 2         | 3      | 0.09%   |
| Silicon Motion            | 2         | 3      | 0.09%   |
| Plextor                   | 2         | 3      | 0.09%   |
| Micron/Crucial Technology | 2         | 4      | 0.09%   |
| HS-SSD-C100               | 2         | 2      | 0.09%   |
| HGST HTS                  | 2         | 7      | 0.09%   |
| Corsair                   | 2         | 3      | 0.09%   |
| Unknown                   | 2         | 3      | 0.09%   |
| ZTE                       | 1         | 1      | 0.05%   |
| USB2.0                    | 1         | 1      | 0.05%   |
| Union Memory              | 1         | 5      | 0.05%   |
| TO Exter                  | 1         | 1      | 0.05%   |
| Solid                     | 1         | 4      | 0.05%   |
| sobetter                  | 1         | 1      | 0.05%   |
| SATAFIRM                  | 1         | 1      | 0.05%   |
| Philips                   | 1         | 2      | 0.05%   |
| Netac                     | 1         | 1      | 0.05%   |
| Leven                     | 1         | 1      | 0.05%   |
| KingFast                  | 1         | 1      | 0.05%   |
| KingDian                  | 1         | 1      | 0.05%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD       | 53        | 2.32%   |
| Kingston SA400S37120G 120GB SSD       | 50        | 2.18%   |
| Seagate ST1000LM035-1RK172 1TB        | 48        | 2.1%    |
| Toshiba MQ01ABF050 500GB              | 42        | 1.83%   |
| Toshiba MQ01ABD100 1TB                | 38        | 1.66%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 38        | 1.66%   |
| Seagate ST500LT012-1DG142 500GB       | 33        | 1.44%   |
| HGST HTS545032A7E380 320GB            | 32        | 1.4%    |
| Kingston SV300S37A120G 120GB SSD      | 30        | 1.31%   |
| Kingston SA400S37480G 480GB SSD       | 27        | 1.18%   |
| HGST HTS545050A7E680 500GB            | 24        | 1.05%   |
| Toshiba MQ04ABF100 1TB                | 22        | 0.96%   |
| Seagate ST9320325AS 320GB             | 21        | 0.92%   |
| Samsung SSD 850 EVO 250GB             | 20        | 0.87%   |
| HGST HTS721010A9E630 1TB              | 18        | 0.79%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 15        | 0.66%   |
| Seagate ST9500325AS 500GB             | 15        | 0.66%   |
| Seagate ST9250315AS 250GB             | 15        | 0.66%   |
| Kingston SUV400S37120G 120GB SSD      | 14        | 0.61%   |
| HGST HTS541010A9E680 1TB              | 13        | 0.57%   |
| WDC WD1600BEVT-22ZCT0 160GB           | 12        | 0.52%   |
| WDC WD10JPVX-22JC3T0 1TB              | 12        | 0.52%   |
| WDC WD5000LPCX-24VHAT0 500GB          | 10        | 0.44%   |
| Seagate ST500LT012-9WS142 500GB       | 10        | 0.44%   |
| Samsung NVMe SSD Drive 512GB          | 10        | 0.44%   |
| JMicron Generic 2TB                   | 10        | 0.44%   |
| HGST HTS725050A7E630 500GB            | 10        | 0.44%   |
| WDC WD5000LPCX-24C6HT0 500GB          | 9         | 0.39%   |
| Unknown MMC Card  32GB                | 9         | 0.39%   |
| Toshiba MQ01ABD050 500GB              | 9         | 0.39%   |
| Seagate M3 Portable 2TB               | 9         | 0.39%   |
| SanDisk NVMe SSD Drive 512GB          | 9         | 0.39%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 8         | 0.35%   |
| WDC WD10SPZX-24Z10 1TB                | 8         | 0.35%   |
| Seagate ST9320423AS 320GB             | 8         | 0.35%   |
| Seagate ST1000LX015-1U7172 1TB        | 8         | 0.35%   |
| SanDisk NVMe SSD Drive 256GB          | 8         | 0.35%   |
| Samsung SSD 860 EVO 500GB             | 8         | 0.35%   |
| Samsung HM160HI 160GB                 | 8         | 0.35%   |
| Hitachi HTS542516K9SA00 160GB         | 8         | 0.35%   |
| HGST HTS545050A7E380 500GB            | 8         | 0.35%   |
| HGST HTS541010B7E610 1TB              | 8         | 0.35%   |
| WDC WDS120G2G0A-00JH30 120GB SSD      | 7         | 0.31%   |
| WDC WD10SPZX-21Z10T0 1TB              | 7         | 0.31%   |
| WDC WD10JPVX-60JC3T0 1TB              | 7         | 0.31%   |
| SPCC Solid State Disk 128GB           | 7         | 0.31%   |
| Seagate ST500LM000-1EJ162 500GB       | 7         | 0.31%   |
| Seagate ST1000LM049-2GH172 1TB        | 7         | 0.31%   |
| Samsung SSD 860 EVO 250GB             | 7         | 0.31%   |
| Samsung SSD 850 EVO 500GB             | 7         | 0.31%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD   | 7         | 0.31%   |
| Hitachi HTS543232A7A384 320GB         | 7         | 0.31%   |
| Hitachi HTS543216L9A300 160GB         | 7         | 0.31%   |
| WDC WD3200BPVT-22JJ5T0 320GB          | 6         | 0.26%   |
| WDC WD2500BEVS-22UST0 250GB           | 6         | 0.26%   |
| WDC WD10SPCX-24HWST1 1TB              | 6         | 0.26%   |
| Unknown SD/MMC/MS PRO 128GB           | 6         | 0.26%   |
| Toshiba MQ01ABD075 752GB              | 6         | 0.26%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 6         | 0.26%   |
| Seagate ST500LM021-1KJ152 500GB       | 6         | 0.26%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 337       | 480    | 29.67%  |
| WDC                 | 252       | 342    | 22.18%  |
| Toshiba             | 197       | 268    | 17.34%  |
| HGST                | 129       | 181    | 11.36%  |
| Hitachi             | 127       | 171    | 11.18%  |
| Fujitsu             | 42        | 54     | 3.7%    |
| Samsung Electronics | 29        | 36     | 2.55%   |
| JMicron Technology  | 10        | 10     | 0.88%   |
| Unknown             | 6         | 7      | 0.53%   |
| ASMT                | 4         | 6      | 0.35%   |
| IBM/Hitachi         | 3         | 4      | 0.26%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 219       | 307    | 28.59%  |
| Samsung Electronics | 145       | 206    | 18.93%  |
| SanDisk             | 56        | 90     | 7.31%   |
| Intel               | 38        | 53     | 4.96%   |
| WDC                 | 35        | 56     | 4.57%   |
| SK hynix            | 32        | 49     | 4.18%   |
| Crucial             | 31        | 50     | 4.05%   |
| Micron Technology   | 26        | 32     | 3.39%   |
| A-DATA Technology   | 24        | 34     | 3.13%   |
| SPCC                | 16        | 20     | 2.09%   |
| Apacer              | 16        | 29     | 2.09%   |
| LITEON              | 12        | 14     | 1.57%   |
| Toshiba             | 11        | 23     | 1.44%   |
| PNY                 | 10        | 15     | 1.31%   |
| Kingmax             | 9         | 9      | 1.17%   |
| China               | 8         | 15     | 1.04%   |
| Transcend           | 7         | 7      | 0.91%   |
| Intenso             | 7         | 14     | 0.91%   |
| OCZ                 | 6         | 6      | 0.78%   |
| KingSpec            | 6         | 7      | 0.78%   |
| Gigabyte Technology | 6         | 9      | 0.78%   |
| LITEONIT            | 5         | 7      | 0.65%   |
| Goodram             | 5         | 6      | 0.65%   |
| Team                | 4         | 6      | 0.52%   |
| Verbatim            | 3         | 4      | 0.39%   |
| Patriot             | 3         | 4      | 0.39%   |
| BHT                 | 3         | 3      | 0.39%   |
| Apple               | 3         | 3      | 0.39%   |
| Unknown             | 2         | 4      | 0.26%   |
| HS-SSD-C100         | 2         | 2      | 0.26%   |
| Corsair             | 2         | 3      | 0.26%   |
| Zheino              | 1         | 1      | 0.13%   |
| Union Memory        | 1         | 5      | 0.13%   |
| TO Exter            | 1         | 1      | 0.13%   |
| Solid               | 1         | 4      | 0.13%   |
| Seagate             | 1         | 1      | 0.13%   |
| SATAFIRM            | 1         | 1      | 0.13%   |
| Plextor             | 1         | 1      | 0.13%   |
| Philips             | 1         | 2      | 0.13%   |
| Netac               | 1         | 1      | 0.13%   |
| Leven               | 1         | 1      | 0.13%   |
| KingDian            | 1         | 1      | 0.13%   |
| JMicron Technology  | 1         | 1      | 0.13%   |
| Hewlett-Packard     | 1         | 1      | 0.13%   |
| AMD                 | 1         | 1      | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1084      | 1559   | 51.3%   |
| SSD     | 714       | 1109   | 33.79%  |
| NVMe    | 202       | 315    | 9.56%   |
| MMC     | 87        | 126    | 4.12%   |
| Unknown | 26        | 35     | 1.23%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1594      | 2607   | 81.83%  |
| NVMe | 202       | 315    | 10.37%  |
| MMC  | 87        | 126    | 4.47%   |
| SAS  | 65        | 96     | 3.34%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1340      | 2073   | 77.37%  |
| 0.51-1.0   | 360       | 546    | 20.79%  |
| 1.01-2.0   | 25        | 40     | 1.44%   |
| 4.01-10.0  | 3         | 3      | 0.17%   |
| 2.01-3.0   | 2         | 4      | 0.12%   |
| 3.01-4.0   | 1         | 1      | 0.06%   |
| 10.01-20.0 | 1         | 1      | 0.06%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 706       | 34.19%  |
| 101-250        | 484       | 23.44%  |
| 251-500        | 329       | 15.93%  |
| 51-100         | 158       | 7.65%   |
| 501-1000       | 147       | 7.12%   |
| 21-50          | 84        | 4.07%   |
| 1-20           | 77        | 3.73%   |
| 1001-2000      | 53        | 2.57%   |
| 2001-3000      | 17        | 0.82%   |
| More than 3000 | 10        | 0.48%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 779       | 37.04%  |
| Unknown        | 706       | 33.57%  |
| 21-50          | 207       | 9.84%   |
| 51-100         | 151       | 7.18%   |
| 101-250        | 127       | 6.04%   |
| 251-500        | 62        | 2.95%   |
| 501-1000       | 45        | 2.14%   |
| 1001-2000      | 23        | 1.09%   |
| More than 3000 | 2         | 0.1%    |
| 2001-3000      | 1         | 0.05%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Notebooks | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| HGST HTS545032A7E380 320GB              | 30        | 40     | 6.77%   |
| HGST HTS545050A7E680 500GB              | 17        | 26     | 3.84%   |
| Seagate ST9320325AS 320GB               | 10        | 22     | 2.26%   |
| Seagate ST500LT012-1DG142 500GB         | 10        | 13     | 2.26%   |
| Toshiba MQ01ABF050 500GB                | 8         | 20     | 1.81%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 8         | 12     | 1.81%   |
| Seagate ST9320423AS 320GB               | 7         | 7      | 1.58%   |
| Seagate ST9250315AS 250GB               | 7         | 9      | 1.58%   |
| Toshiba MQ01ABD100 1TB                  | 6         | 7      | 1.35%   |
| Seagate ST9500325AS 500GB               | 6         | 10     | 1.35%   |
| Seagate ST500LT012-9WS142 500GB         | 6         | 7      | 1.35%   |
| Samsung Electronics HM160HI 160GB       | 6         | 7      | 1.35%   |
| Kingston SV300S37A120G 120GB SSD        | 6         | 9      | 1.35%   |
| HGST HTS541010A9E680 1TB                | 6         | 13     | 1.35%   |
| Toshiba MQ01ABD050 500GB                | 5         | 5      | 1.13%   |
| HGST HTS545050A7E380 500GB              | 5         | 9      | 1.13%   |
| WDC WD10JPVX-22JC3T0 1TB                | 4         | 7      | 0.9%    |
| Seagate ST320LT007-9ZV142 320GB         | 4         | 4      | 0.9%    |
| Seagate ST1000LX015-1U7172 1TB          | 4         | 9      | 0.9%    |
| Hitachi HTS723232A7A364 320GB           | 4         | 4      | 0.9%    |
| Hitachi HTS545050B9A300 500GB           | 4         | 5      | 0.9%    |
| Hitachi HTS545050A7E380 500GB           | 4         | 6      | 0.9%    |
| Hitachi HTS545032B9A300 320GB           | 4         | 5      | 0.9%    |
| Hitachi HTS545016B9A300 160GB           | 4         | 4      | 0.9%    |
| Hitachi HTS543216L9A300 160GB           | 4         | 4      | 0.9%    |
| Hitachi HTS542516K9SA00 160GB           | 4         | 4      | 0.9%    |
| Hitachi HTS541680J9SA00 80GB            | 4         | 4      | 0.9%    |
| Toshiba MQ01ABF032 320GB                | 3         | 3      | 0.68%   |
| Seagate ST980811AS 80GB                 | 3         | 3      | 0.68%   |
| Seagate ST9250410AS 250GB               | 3         | 3      | 0.68%   |
| Seagate ST500LM021-1KJ152 500GB         | 3         | 3      | 0.68%   |
| Seagate ST500LM012 HN-M500MBB 500GB     | 3         | 4      | 0.68%   |
| Seagate ST1000LM035-1RK172 1TB          | 3         | 3      | 0.68%   |
| Samsung Electronics HM321HI 320GB       | 3         | 5      | 0.68%   |
| Hitachi HTS547550A9E384 500GB           | 3         | 9      | 0.68%   |
| Hitachi HTS545025B9A300 250GB           | 3         | 8      | 0.68%   |
| Hitachi HTS543232A7A384 320GB           | 3         | 5      | 0.68%   |
| Hitachi HTS541612J9SA00 120GB           | 3         | 3      | 0.68%   |
| WDC WDS120G2G0A-00JH30 120GB SSD        | 2         | 2      | 0.45%   |
| WDC WD5000LPCX-24VHAT0 500GB            | 2         | 2      | 0.45%   |
| WDC WD5000LPCX-24C6HT0 500GB            | 2         | 2      | 0.45%   |
| WDC WD5000BPVT-80HXZT3 500GB            | 2         | 2      | 0.45%   |
| WDC WD3200BEVT-22ZCT0 320GB             | 2         | 2      | 0.45%   |
| WDC WD3200BEVT-22A23T0 320GB            | 2         | 4      | 0.45%   |
| WDC WD3200BEKT-60V5T1 320GB             | 2         | 2      | 0.45%   |
| WDC WD2500BEVT-22A23T0 250GB            | 2         | 2      | 0.45%   |
| WDC WD2500BEKT-75PVMT0 250GB            | 2         | 2      | 0.45%   |
| WDC WD2500BEKT-60PVMT0 250GB            | 2         | 4      | 0.45%   |
| Toshiba THNSFJ256GCSU 256GB SSD         | 2         | 7      | 0.45%   |
| Toshiba MQ01ABD075 752GB                | 2         | 4      | 0.45%   |
| Toshiba MK5061GSYN 500GB                | 2         | 2      | 0.45%   |
| Toshiba MK3261GSYN 320GB                | 2         | 2      | 0.45%   |
| Toshiba MK2561GSYN 250GB                | 2         | 2      | 0.45%   |
| Toshiba MK1652GSX 160GB                 | 2         | 4      | 0.45%   |
| Toshiba MK1246GSX 120GB                 | 2         | 2      | 0.45%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD | 2         | 3      | 0.45%   |
| Seagate ST9500420AS 500GB               | 2         | 4      | 0.45%   |
| Seagate ST9250827AS 250GB               | 2         | 2      | 0.45%   |
| Seagate ST9160821AS 160GB               | 2         | 2      | 0.45%   |
| Seagate ST9160314AS 160GB               | 2         | 2      | 0.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 110       | 149    | 24.94%  |
| Hitachi             | 72        | 101    | 16.33%  |
| Toshiba             | 65        | 95     | 14.74%  |
| HGST                | 65        | 97     | 14.74%  |
| WDC                 | 48        | 62     | 10.88%  |
| Samsung Electronics | 18        | 24     | 4.08%   |
| Kingston            | 16        | 24     | 3.63%   |
| Fujitsu             | 16        | 23     | 3.63%   |
| Intel               | 11        | 16     | 2.49%   |
| SK hynix            | 6         | 7      | 1.36%   |
| A-DATA Technology   | 3         | 3      | 0.68%   |
| SanDisk             | 2         | 3      | 0.45%   |
| IBM/Hitachi         | 2         | 2      | 0.45%   |
| SPCC                | 1         | 1      | 0.23%   |
| LITEON              | 1         | 1      | 0.23%   |
| Kingmax             | 1         | 1      | 0.23%   |
| JMicron Technology  | 1         | 1      | 0.23%   |
| Intenso             | 1         | 1      | 0.23%   |
| Crucial             | 1         | 1      | 0.23%   |
| Apacer              | 1         | 2      | 0.23%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 110       | 149    | 28.42%  |
| Hitachi             | 72        | 101    | 18.6%   |
| HGST                | 65        | 97     | 16.8%   |
| Toshiba             | 61        | 85     | 15.76%  |
| WDC                 | 46        | 60     | 11.89%  |
| Fujitsu             | 16        | 23     | 4.13%   |
| Samsung Electronics | 15        | 20     | 3.88%   |
| IBM/Hitachi         | 2         | 2      | 0.52%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 377       | 537    | 87.47%  |
| SSD     | 50        | 73     | 11.6%   |
| NVMe    | 3         | 3      | 0.7%    |
| Unknown | 1         | 1      | 0.23%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-22A0RT0 500GB       | 1         | 4      | 8.33%   |
| WDC WD3200BVVT-63A26Y0 320GB       | 1         | 1      | 8.33%   |
| WDC WD3200BPVT-24JJ5T0 320GB       | 1         | 1      | 8.33%   |
| WDC WD3200BEVT-08A23T1 320GB       | 1         | 1      | 8.33%   |
| WDC WD2500LPCX-24C6HT0 250GB       | 1         | 1      | 8.33%   |
| WDC WD1600BEVT-22ZCT0 160GB        | 1         | 1      | 8.33%   |
| Toshiba MQ01ABD050V 500GB          | 1         | 1      | 8.33%   |
| Toshiba MK6475GSX 640GB            | 1         | 1      | 8.33%   |
| Toshiba MK3275GSX 320GB            | 1         | 1      | 8.33%   |
| Seagate ST9160821AS 160GB          | 1         | 1      | 8.33%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 8.33%   |
| Samsung Electronics HM060HI 64GB   | 1         | 1      | 8.33%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 9      | 50%     |
| Toshiba             | 3         | 3      | 25%     |
| Seagate             | 2         | 2      | 16.67%  |
| Samsung Electronics | 1         | 1      | 8.33%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1001      | 1655   | 50.79%  |
| Detected | 533       | 860    | 27.04%  |
| Malfunc  | 425       | 614    | 21.56%  |
| Failed   | 12        | 15     | 0.61%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1478      | 77.14%  |
| AMD                              | 201       | 10.49%  |
| Samsung Electronics              | 67        | 3.5%    |
| SanDisk                          | 40        | 2.09%   |
| SK hynix                         | 21        | 1.1%    |
| Toshiba America Info Systems     | 19        | 0.99%   |
| Kingston Technology Company      | 17        | 0.89%   |
| Silicon Integrated Systems [SiS] | 11        | 0.57%   |
| Nvidia                           | 10        | 0.52%   |
| KIOXIA                           | 9         | 0.47%   |
| VIA Technologies                 | 7         | 0.37%   |
| Phison Electronics               | 7         | 0.37%   |
| Micron Technology                | 6         | 0.31%   |
| JMicron Technology               | 5         | 0.26%   |
| Solid State Storage Technology   | 4         | 0.21%   |
| Silicon Motion                   | 3         | 0.16%   |
| ADATA Technology                 | 3         | 0.16%   |
| Silicon Image                    | 2         | 0.1%    |
| Micron/Crucial Technology        | 2         | 0.1%    |
| Seagate Technology               | 1         | 0.05%   |
| Realtek Semiconductor            | 1         | 0.05%   |
| Lite-On Technology               | 1         | 0.05%   |
| Apple                            | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 178       | 8.19%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 147       | 6.76%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 143       | 6.58%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 130       | 5.98%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 117       | 5.38%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 99        | 4.55%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 80        | 3.68%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 76        | 3.5%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 67        | 3.08%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 64        | 2.94%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 56        | 2.58%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 55        | 2.53%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 46        | 2.12%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 44        | 2.02%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 40        | 1.84%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 36        | 1.66%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 33        | 1.52%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 32        | 1.47%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 31        | 1.43%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 31        | 1.43%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 29        | 1.33%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 28        | 1.29%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                   | 28        | 1.29%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 26        | 1.2%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 26        | 1.2%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 22        | 1.01%   |
| Samsung NVMe SSD Controller 980                                                        | 20        | 0.92%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 20        | 0.92%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 20        | 0.92%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 15        | 0.69%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 15        | 0.69%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                       | 14        | 0.64%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 13        | 0.6%    |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 13        | 0.6%    |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 13        | 0.6%    |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                   | 11        | 0.51%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 11        | 0.51%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 11        | 0.51%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                            | 10        | 0.46%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 10        | 0.46%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 10        | 0.46%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 10        | 0.46%   |
| KIOXIA Non-Volatile memory controller                                                  | 9         | 0.41%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 9         | 0.41%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 9         | 0.41%   |
| SanDisk PC SN520 NVMe SSD                                                              | 8         | 0.37%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 8         | 0.37%   |
| Intel Mobile PM965/GM965 PT IDER Controller                                            | 8         | 0.37%   |
| AMD SB600 Non-Raid-5 SATA                                                              | 8         | 0.37%   |
| AMD SB600 IDE                                                                          | 8         | 0.37%   |
| AMD FCH SATA Controller [IDE mode]                                                     | 8         | 0.37%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 7         | 0.32%   |
| SanDisk WD Blue SN550 NVMe SSD                                                         | 7         | 0.32%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 7         | 0.32%   |
| Intel SSD 660P Series                                                                  | 7         | 0.32%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                      | 7         | 0.32%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 6         | 0.28%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller       | 6         | 0.28%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                   | 6         | 0.28%   |
| Micron Non-Volatile memory controller                                                  | 6         | 0.28%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1457      | 70.49%  |
| IDE  | 295       | 14.27%  |
| NVMe | 205       | 9.92%   |
| RAID | 110       | 5.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 1558      | 87.28%  |
| AMD          | 225       | 12.61%  |
| CentaurHauls | 2         | 0.11%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz           | 43        | 2.4%    |
| Intel Celeron CPU 1000M @ 1.80GHz           | 41        | 2.29%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 27        | 1.51%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 26        | 1.45%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 26        | 1.45%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 25        | 1.4%    |
| Intel Core i3-5005U CPU @ 2.00GHz           | 25        | 1.4%    |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 20        | 1.12%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 20        | 1.12%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 18        | 1.01%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 18        | 1.01%   |
| Intel Core i3-7020U CPU @ 2.30GHz           | 18        | 1.01%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 17        | 0.95%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz        | 17        | 0.95%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 17        | 0.95%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 16        | 0.89%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 15        | 0.84%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 14        | 0.78%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 14        | 0.78%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 14        | 0.78%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 14        | 0.78%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz        | 14        | 0.78%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 13        | 0.73%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 13        | 0.73%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 13        | 0.73%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 13        | 0.73%   |
| Intel Core i3 CPU M 350 @ 2.27GHz           | 13        | 0.73%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 13        | 0.73%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 12        | 0.67%   |
| Intel Core i5 CPU M 540 @ 2.53GHz           | 12        | 0.67%   |
| Intel Atom CPU N450 @ 1.66GHz               | 12        | 0.67%   |
| Intel Atom CPU N270 @ 1.60GHz               | 12        | 0.67%   |
| Intel Pentium CPU B960 @ 2.20GHz            | 11        | 0.61%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 11        | 0.61%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 11        | 0.61%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 11        | 0.61%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 11        | 0.61%   |
| Intel Core i5 CPU M 560 @ 2.67GHz           | 11        | 0.61%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 11        | 0.61%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 11        | 0.61%   |
| Intel Atom CPU N455 @ 1.66GHz               | 11        | 0.61%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 10        | 0.56%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 10        | 0.56%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 10        | 0.56%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 10        | 0.56%   |
| Intel Core i5-3340M CPU @ 2.70GHz           | 10        | 0.56%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 10        | 0.56%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 10        | 0.56%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz      | 9         | 0.5%    |
| Intel Core i5-3230M CPU @ 2.60GHz           | 9         | 0.5%    |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz        | 9         | 0.5%    |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz | 8         | 0.45%   |
| Intel Pentium CPU N3710 @ 1.60GHz           | 8         | 0.45%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 8         | 0.45%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 8         | 0.45%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 8         | 0.45%   |
| Intel Core i3-4030U CPU @ 1.90GHz           | 8         | 0.45%   |
| Intel Core i3-3217U CPU @ 1.80GHz           | 8         | 0.45%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz        | 8         | 0.45%   |
| Intel Core 2 CPU T5600 @ 1.83GHz            | 8         | 0.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5                        | 433       | 24.2%   |
| Intel Core i3                        | 237       | 13.25%  |
| Intel Core i7                        | 221       | 12.35%  |
| Intel Celeron                        | 173       | 9.67%   |
| Intel Core 2 Duo                     | 161       | 9%      |
| Intel Pentium                        | 82        | 4.58%   |
| Intel Atom                           | 66        | 3.69%   |
| Intel Pentium Dual-Core              | 38        | 2.12%   |
| Intel Pentium Dual                   | 28        | 1.57%   |
| AMD A4                               | 27        | 1.51%   |
| Other                                | 24        | 1.34%   |
| Intel Core 2                         | 23        | 1.29%   |
| AMD A8                               | 23        | 1.29%   |
| AMD Ryzen 5                          | 20        | 1.12%   |
| Intel Genuine                        | 16        | 0.89%   |
| AMD E1                               | 16        | 0.89%   |
| AMD Ryzen 7                          | 15        | 0.84%   |
| AMD A6                               | 15        | 0.84%   |
| AMD E2                               | 14        | 0.78%   |
| Intel Pentium Silver                 | 13        | 0.73%   |
| Intel Celeron Dual-Core              | 13        | 0.73%   |
| AMD E                                | 13        | 0.73%   |
| Intel Celeron M                      | 11        | 0.61%   |
| AMD A10                              | 10        | 0.56%   |
| Intel Pentium M                      | 9         | 0.5%    |
| Intel Core Duo                       | 8         | 0.45%   |
| AMD Ryzen 3                          | 7         | 0.39%   |
| AMD Turion 64 X2 Mobile              | 5         | 0.28%   |
| AMD C-60                             | 5         | 0.28%   |
| AMD Ryzen 7 PRO                      | 4         | 0.22%   |
| AMD Mobile Sempron                   | 4         | 0.22%   |
| AMD FX                               | 4         | 0.22%   |
| AMD C-50                             | 4         | 0.22%   |
| AMD Athlon II                        | 4         | 0.22%   |
| Intel Core i9                        | 3         | 0.17%   |
| AMD Athlon X2                        | 3         | 0.17%   |
| AMD Athlon II Dual-Core              | 3         | 0.17%   |
| AMD Athlon 64 X2                     | 3         | 0.17%   |
| AMD A12                              | 3         | 0.17%   |
| Intel Core M                         | 2         | 0.11%   |
| AMD Turion II                        | 2         | 0.11%   |
| AMD Ryzen 5 PRO                      | 2         | 0.11%   |
| AMD C-70                             | 2         | 0.11%   |
| AMD C-30                             | 2         | 0.11%   |
| Intel Core m3                        | 1         | 0.06%   |
| Intel Core 2 Solo                    | 1         | 0.06%   |
| Intel Core 2 Quad                    | 1         | 0.06%   |
| Intel Core 2 Extreme                 | 1         | 0.06%   |
| CentaurHauls VIA Nano                | 1         | 0.06%   |
| CentaurHauls VIA C7                  | 1         | 0.06%   |
| AMD V160                             | 1         | 0.06%   |
| AMD Turion X2 Ultra Dual-Core Mobile | 1         | 0.06%   |
| AMD Turion II Dual-Core              | 1         | 0.06%   |
| AMD Turion 64 Mobile                 | 1         | 0.06%   |
| AMD Ryzen 9                          | 1         | 0.06%   |
| AMD Ryzen 3 PRO                      | 1         | 0.06%   |
| AMD Quad-Core                        | 1         | 0.06%   |
| AMD PRO A10                          | 1         | 0.06%   |
| AMD Phenom II                        | 1         | 0.06%   |
| AMD Athlon Neo                       | 1         | 0.06%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1261      | 70.41%  |
| 4      | 344       | 19.21%  |
| 1      | 123       | 6.87%   |
| 6      | 45        | 2.51%   |
| 8      | 17        | 0.95%   |
| 14     | 1         | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1785      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1011      | 56.32%  |
| 1      | 784       | 43.68%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1713      | 95.48%  |
| 32-bit         | 52        | 2.9%    |
| Unknown        | 29        | 1.62%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 175       | 9.53%   |
| 0x206a7    | 166       | 9.04%   |
| 0x306a9    | 159       | 8.66%   |
| 0x1067a    | 128       | 6.97%   |
| 0x20655    | 97        | 5.28%   |
| 0x40651    | 76        | 4.14%   |
| 0x306d4    | 71        | 3.86%   |
| 0x406e3    | 68        | 3.7%    |
| 0x6fd      | 66        | 3.59%   |
| 0x306c3    | 44        | 2.4%    |
| 0x806ea    | 43        | 2.34%   |
| 0x806e9    | 41        | 2.23%   |
| 0x406c4    | 38        | 2.07%   |
| 0x906ea    | 35        | 1.91%   |
| 0x10676    | 35        | 1.91%   |
| 0x20652    | 31        | 1.69%   |
| 0x106ca    | 31        | 1.69%   |
| 0x806ec    | 30        | 1.63%   |
| 0x30678    | 26        | 1.42%   |
| 0x506c9    | 25        | 1.36%   |
| 0x706a1    | 23        | 1.25%   |
| 0x05000119 | 23        | 1.25%   |
| 0x07030105 | 22        | 1.2%    |
| 0x406c3    | 19        | 1.03%   |
| 0x106c2    | 19        | 1.03%   |
| 0x806eb    | 18        | 0.98%   |
| 0x806c1    | 18        | 0.98%   |
| 0x906e9    | 17        | 0.93%   |
| 0x6fb      | 17        | 0.93%   |
| 0x506e3    | 17        | 0.93%   |
| 0x6f6      | 15        | 0.82%   |
| 0x0700010f | 14        | 0.76%   |
| 0x06001119 | 13        | 0.71%   |
| 0x6ec      | 11        | 0.6%    |
| 0x05000029 | 11        | 0.6%    |
| 0x6f2      | 10        | 0.54%   |
| 0x6d8      | 10        | 0.54%   |
| 0x08600106 | 10        | 0.54%   |
| 0x706e5    | 9         | 0.49%   |
| 0x10661    | 9         | 0.49%   |
| 0x0810100b | 8         | 0.44%   |
| 0x06006705 | 8         | 0.44%   |
| 0x6e8      | 7         | 0.38%   |
| 0x06003106 | 7         | 0.38%   |
| 0x010000c8 | 7         | 0.38%   |
| 0x906ed    | 6         | 0.33%   |
| 0x06006704 | 6         | 0.33%   |
| 0x03000027 | 6         | 0.33%   |
| 0xa0652    | 5         | 0.27%   |
| 0x6fa      | 5         | 0.27%   |
| 0x106e5    | 5         | 0.27%   |
| 0x08108109 | 5         | 0.27%   |
| 0x07030104 | 5         | 0.27%   |
| 0x706a8    | 4         | 0.22%   |
| 0x08101007 | 4         | 0.22%   |
| 0x07030106 | 4         | 0.22%   |
| 0x0600611a | 4         | 0.22%   |
| 0x06006118 | 4         | 0.22%   |
| 0x30673    | 3         | 0.16%   |
| 0x0a50000c | 3         | 0.16%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 218       | 12.21%  |
| SandyBridge      | 171       | 9.58%   |
| Penryn           | 166       | 9.3%    |
| IvyBridge        | 165       | 9.24%   |
| Haswell          | 133       | 7.45%   |
| Westmere         | 130       | 7.28%   |
| Core             | 126       | 7.06%   |
| Skylake          | 98        | 5.49%   |
| Silvermont       | 89        | 4.99%   |
| Broadwell        | 78        | 4.37%   |
| Bonnell          | 52        | 2.91%   |
| Bobcat           | 38        | 2.13%   |
| Puma             | 32        | 1.79%   |
| P6               | 31        | 1.74%   |
| Goldmont plus    | 30        | 1.68%   |
| Goldmont         | 29        | 1.62%   |
| Excavator        | 22        | 1.23%   |
| Zen 2            | 19        | 1.06%   |
| TigerLake        | 18        | 1.01%   |
| Piledriver       | 17        | 0.95%   |
| Jaguar           | 17        | 0.95%   |
| K8 Hammer        | 15        | 0.84%   |
| Zen              | 13        | 0.73%   |
| K10              | 13        | 0.73%   |
| IceLake          | 11        | 0.62%   |
| Zen+             | 9         | 0.5%    |
| Steamroller      | 9         | 0.5%    |
| K10 Llano        | 7         | 0.39%   |
| Zen 3            | 6         | 0.34%   |
| CometLake        | 6         | 0.34%   |
| Unknown          | 6         | 0.34%   |
| Nehalem          | 5         | 0.28%   |
| K8 & K10 hybrid  | 4         | 0.22%   |
| NetBurst         | 1         | 0.06%   |
| Alderlake Hybrid | 1         | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1391      | 63.49%  |
| Nvidia                           | 414       | 18.9%   |
| AMD                              | 373       | 17.02%  |
| VIA Technologies                 | 7         | 0.32%   |
| Silicon Integrated Systems [SiS] | 6         | 0.27%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 163       | 6.94%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 157       | 6.69%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 132       | 5.62%   |
| Intel Core Processor Integrated Graphics Controller                                      | 91        | 3.88%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 81        | 3.45%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 71        | 3.02%   |
| Intel HD Graphics 5500                                                                   | 69        | 2.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 59        | 2.51%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 55        | 2.34%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 49        | 2.09%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 49        | 2.09%   |
| Intel UHD Graphics 620                                                                   | 45        | 1.92%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 43        | 1.83%   |
| Intel HD Graphics 620                                                                    | 41        | 1.75%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 38        | 1.62%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 36        | 1.53%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 32        | 1.36%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 32        | 1.36%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 30        | 1.28%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 28        | 1.19%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 28        | 1.19%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 27        | 1.15%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 24        | 1.02%   |
| Intel HD Graphics 500                                                                    | 22        | 0.94%   |
| Intel HD Graphics 530                                                                    | 20        | 0.85%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 20        | 0.85%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 19        | 0.81%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 19        | 0.81%   |
| AMD Renoir                                                                               | 19        | 0.81%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 18        | 0.77%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                             | 18        | 0.77%   |
| Nvidia GP108M [GeForce MX150]                                                            | 17        | 0.72%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 17        | 0.72%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 17        | 0.72%   |
| Nvidia GM108M [GeForce MX110]                                                            | 16        | 0.68%   |
| Intel HD Graphics 630                                                                    | 15        | 0.64%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 15        | 0.64%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 14        | 0.6%    |
| Nvidia GM108M [GeForce MX130]                                                            | 13        | 0.55%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 13        | 0.55%   |
| Intel Kaby Lake-U GT2f HD 620 Graphics Controller                                        | 13        | 0.55%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 13        | 0.55%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 13        | 0.55%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 13        | 0.55%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 12        | 0.51%   |
| Nvidia GM108M [GeForce 840M]                                                             | 12        | 0.51%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 12        | 0.51%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                        | 12        | 0.51%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 11        | 0.47%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 11        | 0.47%   |
| Nvidia GM108M [GeForce 940M]                                                             | 9         | 0.38%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 9         | 0.38%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 9         | 0.38%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 9         | 0.38%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 8         | 0.34%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 8         | 0.34%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 8         | 0.34%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 8         | 0.34%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 8         | 0.34%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 8         | 0.34%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 997       | 55.76%  |
| Intel + Nvidia | 306       | 17.11%  |
| 1 x AMD        | 222       | 12.42%  |
| 1 x Nvidia     | 97        | 5.43%   |
| Intel + AMD    | 88        | 4.92%   |
| 2 x AMD        | 52        | 2.91%   |
| AMD + Nvidia   | 12        | 0.67%   |
| 1 x VIA        | 7         | 0.39%   |
| 1 x SiS        | 6         | 0.34%   |
| Other          | 1         | 0.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1686      | 93.77%  |
| Proprietary | 87        | 4.84%   |
| Unknown     | 25        | 1.39%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1026      | 55.73%  |
| 0.01-0.5   | 339       | 18.41%  |
| 1.01-2.0   | 265       | 14.39%  |
| 0.51-1.0   | 113       | 6.14%   |
| 3.01-4.0   | 78        | 4.24%   |
| 5.01-6.0   | 13        | 0.71%   |
| 7.01-8.0   | 4         | 0.22%   |
| 2.01-3.0   | 3         | 0.16%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 381       | 19.92%  |
| AU Optronics            | 377       | 19.71%  |
| Samsung Electronics     | 286       | 14.95%  |
| Chimei Innolux          | 227       | 11.87%  |
| BOE                     | 182       | 9.51%   |
| Chi Mei Optoelectronics | 88        | 4.6%    |
| Lenovo                  | 72        | 3.76%   |
| LG Philips              | 35        | 1.83%   |
| Goldstar                | 35        | 1.83%   |
| Dell                    | 24        | 1.25%   |
| InfoVision              | 21        | 1.1%    |
| CPT                     | 14        | 0.73%   |
| PANDA                   | 13        | 0.68%   |
| Philips                 | 12        | 0.63%   |
| HannStar                | 10        | 0.52%   |
| Hewlett-Packard         | 9         | 0.47%   |
| Apple                   | 9         | 0.47%   |
| Sharp                   | 8         | 0.42%   |
| BenQ                    | 8         | 0.42%   |
| Toshiba                 | 7         | 0.37%   |
| Sony                    | 7         | 0.37%   |
| Quanta Display          | 7         | 0.37%   |
| ASUSTek Computer        | 7         | 0.37%   |
| Acer                    | 7         | 0.37%   |
| AOC                     | 6         | 0.31%   |
| Ancor Communications    | 6         | 0.31%   |
| InnoLux Display         | 5         | 0.26%   |
| Panasonic               | 4         | 0.21%   |
| Fujitsu Siemens         | 4         | 0.21%   |
| Vestel Elektronik       | 3         | 0.16%   |
| NEC Computers           | 3         | 0.16%   |
| IBM                     | 3         | 0.16%   |
| Eizo                    | 3         | 0.16%   |
| SKY                     | 2         | 0.1%    |
| Plain Tree Systems      | 2         | 0.1%    |
| OEM                     | 2         | 0.1%    |
| MiTAC                   | 2         | 0.1%    |
| Lenovo Group Limited    | 2         | 0.1%    |
| HKC                     | 2         | 0.1%    |
| CTV                     | 2         | 0.1%    |
| ViewSonic               | 1         | 0.05%   |
| Onkyo                   | 1         | 0.05%   |
| Nvidia                  | 1         | 0.05%   |
| MStar                   | 1         | 0.05%   |
| MSI                     | 1         | 0.05%   |
| Medion                  | 1         | 0.05%   |
| LPL                     | 1         | 0.05%   |
| ITE                     | 1         | 0.05%   |
| Iiyama                  | 1         | 0.05%   |
| Daewoo                  | 1         | 0.05%   |
| CSO                     | 1         | 0.05%   |
| CHI                     | 1         | 0.05%   |
| CHD                     | 1         | 0.05%   |
| Belinea                 | 1         | 0.05%   |
| Arnos Instruments       | 1         | 0.05%   |
| ANX                     | 1         | 0.05%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 49        | 2.55%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 34        | 1.77%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 32        | 1.66%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 24        | 1.25%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 24        | 1.25%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 20        | 1.04%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 19        | 0.99%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 16        | 0.83%   |
| Lenovo LCD Monitor LEN4036 1440x900 304x190mm 14.1-inch                  | 14        | 0.73%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 14        | 0.73%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 14        | 0.73%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 13        | 0.68%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 12        | 0.62%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 12        | 0.62%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 12        | 0.62%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 11        | 0.57%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 11        | 0.57%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch     | 10        | 0.52%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch            | 10        | 0.52%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 10        | 0.52%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 10        | 0.52%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 10        | 0.52%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 9         | 0.47%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 8         | 0.42%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch              | 8         | 0.42%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 8         | 0.42%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 8         | 0.42%   |
| Chi Mei Optoelectronics LCD Monitor CMO1526 1280x800 331x207mm 15.4-inch | 8         | 0.42%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 8         | 0.42%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch            | 8         | 0.42%   |
| Samsung Electronics LCD Monitor SEC3245 1280x800 261x163mm 12.1-inch     | 7         | 0.36%   |
| LG Philips LP154WX4-TLC8 LPL0120 1280x800 331x207mm 15.4-inch            | 7         | 0.36%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 7         | 0.36%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch              | 7         | 0.36%   |
| LG Display LCD Monitor LGD02AD 1366x768 344x194mm 15.5-inch              | 7         | 0.36%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 7         | 0.36%   |
| BOE LCD Monitor BOE061D 1366x768 309x173mm 13.9-inch                     | 7         | 0.36%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 7         | 0.36%   |
| AU Optronics LCD Monitor AUO5544 1280x800 303x189mm 14.1-inch            | 7         | 0.36%   |
| AU Optronics LCD Monitor AUO206C 1366x768 277x156mm 12.5-inch            | 7         | 0.36%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 7         | 0.36%   |
| Samsung Electronics LCD Monitor SEC3046 1366x768 340x190mm 15.3-inch     | 6         | 0.31%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 6         | 0.31%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x194mm 15.5-inch                  | 6         | 0.31%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x190mm 14.1-inch                  | 6         | 0.31%   |
| Lenovo LCD Monitor LEN4031 1280x800 304x190mm 14.1-inch                  | 6         | 0.31%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch              | 6         | 0.31%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 382x214mm 17.2-inch          | 6         | 0.31%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 340x190mm 15.3-inch          | 6         | 0.31%   |
| Chimei Innolux LCD Monitor CMN15CB 1920x1080 344x193mm 15.5-inch         | 6         | 0.31%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 6         | 0.31%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 6         | 0.31%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 6         | 0.31%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch          | 6         | 0.31%   |
| BOE LCD Monitor BOE07A3 1920x1080 344x193mm 15.5-inch                    | 6         | 0.31%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 6         | 0.31%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 6         | 0.31%   |
| AU Optronics LCD Monitor AUO193C 1366x768 309x173mm 13.9-inch            | 6         | 0.31%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 5         | 0.26%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 303x190mm 14.1-inch     | 5         | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 797       | 43.01%  |
| 1920x1080 (FHD)    | 525       | 28.33%  |
| 1280x800 (WXGA)    | 157       | 8.47%   |
| 1600x900 (HD+)     | 126       | 6.8%    |
| 1440x900 (WXGA+)   | 54        | 2.91%   |
| 1024x600           | 38        | 2.05%   |
| 3840x2160 (4K)     | 33        | 1.78%   |
| 1920x1200 (WUXGA)  | 23        | 1.24%   |
| 1680x1050 (WSXGA+) | 20        | 1.08%   |
| 1280x1024 (SXGA)   | 17        | 0.92%   |
| 1024x768 (XGA)     | 14        | 0.76%   |
| 2560x1440 (QHD)    | 11        | 0.59%   |
| 2880x1800          | 5         | 0.27%   |
| 1920x540           | 5         | 0.27%   |
| 1360x768           | 5         | 0.27%   |
| 2560x1080          | 4         | 0.22%   |
| 2560x1600          | 3         | 0.16%   |
| 2160x1440          | 2         | 0.11%   |
| 1400x1050          | 2         | 0.11%   |
| 1280x768           | 2         | 0.11%   |
| 800x1280           | 1         | 0.05%   |
| 3840x2400          | 1         | 0.05%   |
| 3440x1440          | 1         | 0.05%   |
| 2304x1440          | 1         | 0.05%   |
| 2288x1287          | 1         | 0.05%   |
| 1920x1280          | 1         | 0.05%   |
| 1800x1440          | 1         | 0.05%   |
| 1680x945           | 1         | 0.05%   |
| 1600x1200          | 1         | 0.05%   |
| 1280x720 (HD)      | 1         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1055      | 55.06%  |
| 14      | 209       | 10.91%  |
| 13      | 146       | 7.62%   |
| 17      | 122       | 6.37%   |
| 12      | 73        | 3.81%   |
| 10      | 48        | 2.51%   |
| 24      | 38        | 1.98%   |
| 23      | 38        | 1.98%   |
| 11      | 34        | 1.77%   |
| 21      | 30        | 1.57%   |
| 27      | 27        | 1.41%   |
| 18      | 18        | 0.94%   |
| 19      | 13        | 0.68%   |
| 22      | 9         | 0.47%   |
| Unknown | 9         | 0.47%   |
| 20      | 6         | 0.31%   |
| 72      | 5         | 0.26%   |
| 34      | 5         | 0.26%   |
| 40      | 4         | 0.21%   |
| 32      | 4         | 0.21%   |
| 84      | 3         | 0.16%   |
| 54      | 3         | 0.16%   |
| 31      | 3         | 0.16%   |
| 8       | 3         | 0.16%   |
| 65      | 2         | 0.1%    |
| 16      | 2         | 0.1%    |
| 52      | 1         | 0.05%   |
| 48      | 1         | 0.05%   |
| 41      | 1         | 0.05%   |
| 39      | 1         | 0.05%   |
| 33      | 1         | 0.05%   |
| 29      | 1         | 0.05%   |
| 9       | 1         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 1311      | 68.82%  |
| 201-300     | 216       | 11.34%  |
| 351-400     | 165       | 8.66%   |
| 501-600     | 97        | 5.09%   |
| 401-500     | 65        | 3.41%   |
| 701-800     | 10        | 0.52%   |
| Unknown     | 9         | 0.47%   |
| 1501-2000   | 8         | 0.42%   |
| 601-700     | 7         | 0.37%   |
| 1001-1500   | 7         | 0.37%   |
| 801-900     | 5         | 0.26%   |
| 101-200     | 4         | 0.21%   |
| 901-1000    | 1         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1462      | 82.27%  |
| 16/10   | 261       | 14.69%  |
| 4/3     | 19        | 1.07%   |
| 5/4     | 16        | 0.9%    |
| 3/2     | 8         | 0.45%   |
| 21/9    | 5         | 0.28%   |
| Unknown | 5         | 0.28%   |
| 0.62    | 1         | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1053      | 54.99%  |
| 81-90          | 300       | 15.67%  |
| 201-250        | 94        | 4.91%   |
| 121-130        | 88        | 4.6%    |
| 61-70          | 71        | 3.71%   |
| 71-80          | 53        | 2.77%   |
| 41-50          | 48        | 2.51%   |
| 51-60          | 34        | 1.78%   |
| 301-350        | 27        | 1.41%   |
| 151-200        | 27        | 1.41%   |
| 131-140        | 27        | 1.41%   |
| 141-150        | 23        | 1.2%    |
| 251-300        | 16        | 0.84%   |
| More than 1000 | 15        | 0.78%   |
| 351-500        | 13        | 0.68%   |
| Unknown        | 9         | 0.47%   |
| 91-100         | 7         | 0.37%   |
| 501-1000       | 6         | 0.31%   |
| 1-40           | 4         | 0.21%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 817       | 43.18%  |
| 121-160       | 607       | 32.08%  |
| 51-100        | 379       | 20.03%  |
| 161-240       | 55        | 2.91%   |
| More than 240 | 13        | 0.69%   |
| 1-50          | 12        | 0.63%   |
| Unknown       | 9         | 0.48%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1606      | 87.76%  |
| 2     | 193       | 10.55%  |
| 0     | 19        | 1.04%   |
| 3     | 12        | 0.66%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 883       | 30.16%  |
| Intel                             | 832       | 28.42%  |
| Qualcomm Atheros                  | 558       | 19.06%  |
| Broadcom                          | 238       | 8.13%   |
| Ralink                            | 93        | 3.18%   |
| Broadcom Limited                  | 83        | 2.83%   |
| Marvell Technology Group          | 44        | 1.5%    |
| Dell                              | 24        | 0.82%   |
| Hewlett-Packard                   | 17        | 0.58%   |
| Sierra Wireless                   | 13        | 0.44%   |
| MediaTek                          | 13        | 0.44%   |
| Ericsson Business Mobile Networks | 13        | 0.44%   |
| Samsung Electronics               | 12        | 0.41%   |
| Huawei Technologies               | 12        | 0.41%   |
| Attansic Technology               | 11        | 0.38%   |
| Silicon Integrated Systems [SiS]  | 10        | 0.34%   |
| JMicron Technology                | 10        | 0.34%   |
| Ralink Technology                 | 9         | 0.31%   |
| TP-Link                           | 8         | 0.27%   |
| Qualcomm Atheros Communications   | 6         | 0.2%    |
| VIA Technologies                  | 5         | 0.17%   |
| Xiaomi                            | 4         | 0.14%   |
| Nvidia                            | 4         | 0.14%   |
| ASIX Electronics                  | 4         | 0.14%   |
| DisplayLink                       | 3         | 0.1%    |
| D-Link                            | 2         | 0.07%   |
| Belkin Components                 | 2         | 0.07%   |
| ASUSTek Computer                  | 2         | 0.07%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.03%   |
| Spreadtrum Communications         | 1         | 0.03%   |
| OPPO Electronics                  | 1         | 0.03%   |
| NetGear                           | 1         | 0.03%   |
| Motorola PCS                      | 1         | 0.03%   |
| Micro Star International          | 1         | 0.03%   |
| LG Electronics                    | 1         | 0.03%   |
| Lenovo                            | 1         | 0.03%   |
| ICS Advent                        | 1         | 0.03%   |
| Fujitsu Siemens Computers         | 1         | 0.03%   |
| Davicom Semiconductor             | 1         | 0.03%   |
| AMD                               | 1         | 0.03%   |
| 3DSP                              | 1         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 525       | 14.76%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 272       | 7.65%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 108       | 3.04%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 101       | 2.84%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 98        | 2.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 93        | 2.61%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 72        | 2.02%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 70        | 1.97%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 64        | 1.8%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 63        | 1.77%   |
| Intel Wireless 7260                                                     | 59        | 1.66%   |
| Intel 82577LM Gigabit Network Connection                                | 58        | 1.63%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 54        | 1.52%   |
| Intel Wireless 8265 / 8275                                              | 54        | 1.52%   |
| Intel 82567LM Gigabit Network Connection                                | 52        | 1.46%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 51        | 1.43%   |
| Intel Wireless 7265                                                     | 48        | 1.35%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 48        | 1.35%   |
| Intel Centrino Advanced-N 6200                                          | 47        | 1.32%   |
| Intel Wireless 3165                                                     | 32        | 0.9%    |
| Intel Wireless 3160                                                     | 32        | 0.9%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 32        | 0.9%    |
| Intel Centrino Ultimate-N 6300                                          | 32        | 0.9%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 31        | 0.87%   |
| Intel Wireless 8260                                                     | 30        | 0.84%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 29        | 0.82%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 28        | 0.79%   |
| Intel WiFi Link 5100                                                    | 27        | 0.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 25        | 0.7%    |
| Broadcom BCM43142 802.11b/g/n                                           | 25        | 0.7%    |
| Intel Ethernet Connection I218-LM                                       | 24        | 0.67%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 24        | 0.67%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 23        | 0.65%   |
| Intel Ethernet Connection (3) I218-LM                                   | 23        | 0.65%   |
| Intel Wi-Fi 6 AX200                                                     | 22        | 0.62%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 20        | 0.56%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 19        | 0.53%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 19        | 0.53%   |
| Intel Ultimate N WiFi Link 5300                                         | 18        | 0.51%   |
| Intel 82566MM Gigabit Network Connection                                | 18        | 0.51%   |
| Intel Wi-Fi 6 AX201                                                     | 17        | 0.48%   |
| Intel Ethernet Connection I217-LM                                       | 17        | 0.48%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 16        | 0.45%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 16        | 0.45%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 16        | 0.45%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 16        | 0.45%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 16        | 0.45%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 16        | 0.45%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 15        | 0.42%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 15        | 0.42%   |
| Intel Ethernet Connection I219-LM                                       | 14        | 0.39%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 14        | 0.39%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                 | 14        | 0.39%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 13        | 0.37%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 13        | 0.37%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 13        | 0.37%   |
| Intel Ethernet Connection (4) I219-LM                                   | 13        | 0.37%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 12        | 0.34%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 12        | 0.34%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 12        | 0.34%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 775       | 42.17%  |
| Qualcomm Atheros                | 495       | 26.93%  |
| Realtek Semiconductor           | 208       | 11.32%  |
| Broadcom                        | 158       | 8.6%    |
| Ralink                          | 93        | 5.06%   |
| Broadcom Limited                | 37        | 2.01%   |
| Dell                            | 14        | 0.76%   |
| Sierra Wireless                 | 13        | 0.71%   |
| MediaTek                        | 12        | 0.65%   |
| Ralink Technology               | 9         | 0.49%   |
| TP-Link                         | 6         | 0.33%   |
| Qualcomm Atheros Communications | 6         | 0.33%   |
| Hewlett-Packard                 | 3         | 0.16%   |
| D-Link                          | 2         | 0.11%   |
| Belkin Components               | 2         | 0.11%   |
| ASUSTek Computer                | 2         | 0.11%   |
| NetGear                         | 1         | 0.05%   |
| Micro Star International        | 1         | 0.05%   |
| Fujitsu Siemens Computers       | 1         | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 108       | 5.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 98        | 5.31%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 93        | 5.04%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 72        | 3.9%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 70        | 3.79%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 64        | 3.47%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 63        | 3.41%   |
| Intel Wireless 7260                                                     | 59        | 3.2%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 54        | 2.93%   |
| Intel Wireless 8265 / 8275                                              | 54        | 2.93%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 51        | 2.76%   |
| Intel Wireless 7265                                                     | 48        | 2.6%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 48        | 2.6%    |
| Intel Centrino Advanced-N 6200                                          | 47        | 2.55%   |
| Intel Wireless 3165                                                     | 32        | 1.73%   |
| Intel Wireless 3160                                                     | 32        | 1.73%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 32        | 1.73%   |
| Intel Centrino Ultimate-N 6300                                          | 32        | 1.73%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 31        | 1.68%   |
| Intel Wireless 8260                                                     | 30        | 1.63%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 29        | 1.57%   |
| Intel WiFi Link 5100                                                    | 27        | 1.46%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 25        | 1.36%   |
| Broadcom BCM43142 802.11b/g/n                                           | 25        | 1.36%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 24        | 1.3%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 23        | 1.25%   |
| Intel Wi-Fi 6 AX200                                                     | 22        | 1.19%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 19        | 1.03%   |
| Intel Ultimate N WiFi Link 5300                                         | 18        | 0.98%   |
| Intel Wi-Fi 6 AX201                                                     | 17        | 0.92%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 16        | 0.87%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 16        | 0.87%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 16        | 0.87%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 16        | 0.87%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 16        | 0.87%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 15        | 0.81%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 14        | 0.76%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 13        | 0.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 12        | 0.65%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 12        | 0.65%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 12        | 0.65%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 11        | 0.6%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 11        | 0.6%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 11        | 0.6%    |
| Intel Centrino Advanced-N 6235                                          | 11        | 0.6%    |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 10        | 0.54%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 9         | 0.49%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 9         | 0.49%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 8         | 0.43%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 8         | 0.43%   |
| Intel Centrino Wireless-N 2230                                          | 8         | 0.43%   |
| Intel Centrino Wireless-N 130                                           | 8         | 0.43%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 8         | 0.43%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 8         | 0.43%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 7         | 0.38%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 7         | 0.38%   |
| Intel Wireless-AC 9260                                                  | 7         | 0.38%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 7         | 0.38%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter             | 7         | 0.38%   |
| Broadcom BCM43225 802.11b/g/n                                           | 7         | 0.38%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 832       | 50%     |
| Intel                            | 412       | 24.76%  |
| Qualcomm Atheros                 | 139       | 8.35%   |
| Broadcom                         | 103       | 6.19%   |
| Broadcom Limited                 | 47        | 2.82%   |
| Marvell Technology Group         | 44        | 2.64%   |
| Samsung Electronics              | 12        | 0.72%   |
| Huawei Technologies              | 11        | 0.66%   |
| Attansic Technology              | 11        | 0.66%   |
| Silicon Integrated Systems [SiS] | 10        | 0.6%    |
| JMicron Technology               | 10        | 0.6%    |
| VIA Technologies                 | 5         | 0.3%    |
| Xiaomi                           | 4         | 0.24%   |
| Nvidia                           | 4         | 0.24%   |
| ASIX Electronics                 | 4         | 0.24%   |
| DisplayLink                      | 3         | 0.18%   |
| TP-Link                          | 2         | 0.12%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.06%   |
| Spreadtrum Communications        | 1         | 0.06%   |
| OPPO Electronics                 | 1         | 0.06%   |
| Motorola PCS                     | 1         | 0.06%   |
| MediaTek                         | 1         | 0.06%   |
| LG Electronics                   | 1         | 0.06%   |
| Lenovo                           | 1         | 0.06%   |
| ICS Advent                       | 1         | 0.06%   |
| Hewlett-Packard                  | 1         | 0.06%   |
| Davicom Semiconductor            | 1         | 0.06%   |
| 3DSP                             | 1         | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 525       | 31.49%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 272       | 16.32%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 101       | 6.06%   |
| Intel 82577LM Gigabit Network Connection                          | 58        | 3.48%   |
| Intel 82567LM Gigabit Network Connection                          | 52        | 3.12%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 28        | 1.68%   |
| Intel Ethernet Connection I218-LM                                 | 24        | 1.44%   |
| Intel Ethernet Connection (3) I218-LM                             | 23        | 1.38%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 20        | 1.2%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 19        | 1.14%   |
| Intel 82566MM Gigabit Network Connection                          | 18        | 1.08%   |
| Intel Ethernet Connection I217-LM                                 | 17        | 1.02%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 16        | 0.96%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 15        | 0.9%    |
| Intel Ethernet Connection I219-LM                                 | 14        | 0.84%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 14        | 0.84%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 13        | 0.78%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 13        | 0.78%   |
| Intel Ethernet Connection (4) I219-LM                             | 13        | 0.78%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 12        | 0.72%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 12        | 0.72%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 12        | 0.72%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 12        | 0.72%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 12        | 0.72%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 11        | 0.66%   |
| Intel 82579V Gigabit Network Connection                           | 11        | 0.66%   |
| Huawei COL-L29                                                    | 11        | 0.66%   |
| Attansic AR8152 v2.0 Fast Ethernet                                | 11        | 0.66%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 10        | 0.6%    |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 10        | 0.6%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 10        | 0.6%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 10        | 0.6%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 10        | 0.6%    |
| Broadcom BCM4401-B0 100Base-TX                                    | 10        | 0.6%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 9         | 0.54%   |
| Intel Ethernet Connection I219-V                                  | 8         | 0.48%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 8         | 0.48%   |
| Intel Ethernet Connection (2) I219-LM                             | 7         | 0.42%   |
| Intel 82577LC Gigabit Network Connection                          | 7         | 0.42%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 6         | 0.36%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 6         | 0.36%   |
| Intel Ethernet Connection (4) I219-V                              | 6         | 0.36%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 6         | 0.36%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 6         | 0.36%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 5         | 0.3%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 5         | 0.3%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 5         | 0.3%    |
| Intel Ethernet Connection (7) I219-LM                             | 5         | 0.3%    |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 5         | 0.3%    |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                 | 5         | 0.3%    |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 5         | 0.3%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 4         | 0.24%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 4         | 0.24%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 4         | 0.24%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 4         | 0.24%   |
| Intel Ethernet Connection I217-V                                  | 4         | 0.24%   |
| Intel Ethernet Connection (6) I219-LM                             | 4         | 0.24%   |
| Intel Ethernet Connection (13) I219-V                             | 4         | 0.24%   |
| Intel Ethernet Connection (10) I219-V                             | 4         | 0.24%   |
| Intel 82573L Gigabit Ethernet Controller                          | 4         | 0.24%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1764      | 51.4%   |
| Ethernet | 1623      | 47.29%  |
| Modem    | 45        | 1.31%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1457      | 74.99%  |
| Ethernet | 486       | 25.01%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1575      | 88.14%  |
| 1     | 184       | 10.3%   |
| 0     | 21        | 1.18%   |
| 3     | 7         | 0.39%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1619      | 88.04%  |
| Yes  | 220       | 11.96%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 429       | 32.43%  |
| Qualcomm Atheros Communications | 153       | 11.56%  |
| Broadcom                        | 128       | 9.67%   |
| Realtek Semiconductor           | 110       | 8.31%   |
| Lite-On Technology              | 78        | 5.9%    |
| Dell                            | 75        | 5.67%   |
| Hewlett-Packard                 | 65        | 4.91%   |
| Ralink                          | 64        | 4.84%   |
| IMC Networks                    | 64        | 4.84%   |
| Foxconn / Hon Hai               | 54        | 4.08%   |
| Cambridge Silicon Radio         | 26        | 1.97%   |
| Toshiba                         | 19        | 1.44%   |
| ASUSTek Computer                | 11        | 0.83%   |
| Ralink Technology               | 8         | 0.6%    |
| Realtek                         | 7         | 0.53%   |
| Apple                           | 7         | 0.53%   |
| Chicony Electronics             | 5         | 0.38%   |
| Askey Computer                  | 5         | 0.38%   |
| Taiyo Yuden                     | 4         | 0.3%    |
| Foxconn International           | 4         | 0.3%    |
| Micro Star International        | 3         | 0.23%   |
| Alps Electric                   | 2         | 0.15%   |
| MediaTek                        | 1         | 0.08%   |
| Fujitsu Siemens Computers       | 1         | 0.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 261       | 19.68%  |
| Ralink RT3290 Bluetooth                             | 64        | 4.83%   |
| Qualcomm Atheros  Bluetooth Device                  | 60        | 4.52%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 60        | 4.52%   |
| Realtek Bluetooth Radio                             | 57        | 4.3%    |
| Dell DW375 Bluetooth Module                         | 38        | 2.87%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 34        | 2.56%   |
| Intel Bluetooth Device                              | 33        | 2.49%   |
| HP Broadcom 2070 Bluetooth Combo                    | 33        | 2.49%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 31        | 2.34%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 29        | 2.19%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 29        | 2.19%   |
| Broadcom BCM2045B (BDC-2.1)                         | 28        | 2.11%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 26        | 1.96%   |
| IMC Networks Bluetooth Radio                        | 23        | 1.73%   |
| IMC Networks Bluetooth Device                       | 22        | 1.66%   |
| Intel AX200 Bluetooth                               | 20        | 1.51%   |
| Broadcom HP Portable SoftSailing                    | 20        | 1.51%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 19        | 1.43%   |
| Foxconn / Hon Hai Bluetooth Device                  | 19        | 1.43%   |
| Realtek RTL8821A Bluetooth                          | 18        | 1.36%   |
| Realtek RTL8723B Bluetooth                          | 18        | 1.36%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 18        | 1.36%   |
| Lite-On Bluetooth Device                            | 17        | 1.28%   |
| Realtek  Bluetooth 4.2 Adapter                      | 15        | 1.13%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 14        | 1.06%   |
| Dell BCM20702A0 Bluetooth Module                    | 14        | 1.06%   |
| Lite-On Atheros AR3012 Bluetooth                    | 13        | 0.98%   |
| Intel Wireless-AC 3168 Bluetooth                    | 13        | 0.98%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 13        | 0.98%   |
| Broadcom BCM2070 Bluetooth Device                   | 11        | 0.83%   |
| Foxconn / Hon Hai BCM20702A0                        | 9         | 0.68%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 9         | 0.68%   |
| Toshiba Bluetooth Device                            | 8         | 0.6%    |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 8         | 0.6%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 8         | 0.6%    |
| Realtek Bluetooth Radio                             | 7         | 0.53%   |
| Qualcomm Atheros Bluetooth                          | 7         | 0.53%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 7         | 0.53%   |
| Dell Wireless 360 Bluetooth                         | 7         | 0.53%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 7         | 0.53%   |
| Broadcom BCM2046 Bluetooth Device                   | 7         | 0.53%   |
| Broadcom BCM2045 Bluetooth                          | 7         | 0.53%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 6         | 0.45%   |
| IMC Networks Wireless_Device                        | 6         | 0.45%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 6         | 0.45%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 5         | 0.38%   |
| Lite-On Qualcomm Atheros Bluetooth                  | 5         | 0.38%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 5         | 0.38%   |
| Dell Wireless 365 Bluetooth                         | 5         | 0.38%   |
| Dell Wireless 355 Bluetooth                         | 5         | 0.38%   |
| Chicony Bluetooth (RTL8723BE)                       | 5         | 0.38%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 5         | 0.38%   |
| Askey Bluetooth Device                              | 5         | 0.38%   |
| Apple Bluetooth Host Controller                     | 5         | 0.38%   |
| Toshiba Integrated Bluetooth HCI                    | 4         | 0.3%    |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)             | 4         | 0.3%    |
| IMC Networks Bluetooth module                       | 4         | 0.3%    |
| Foxconn International BCM43142A0 Bluetooth module   | 4         | 0.3%    |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 4         | 0.3%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1520      | 77.31%  |
| AMD                              | 265       | 13.48%  |
| Nvidia                           | 137       | 6.97%   |
| Silicon Integrated Systems [SiS] | 11        | 0.56%   |
| VIA Technologies                 | 7         | 0.36%   |
| Logitech                         | 5         | 0.25%   |
| C-Media Electronics              | 5         | 0.25%   |
| Texas Instruments                | 3         | 0.15%   |
| Lenovo                           | 2         | 0.1%    |
| Creative Technology              | 2         | 0.1%    |
| Tenx Technology                  | 1         | 0.05%   |
| Sennheiser Communications        | 1         | 0.05%   |
| PreSonus Audio Electronics       | 1         | 0.05%   |
| Plantronics                      | 1         | 0.05%   |
| Numark                           | 1         | 0.05%   |
| GN Netcom                        | 1         | 0.05%   |
| AudioQuest                       | 1         | 0.05%   |
| ASUSTek Computer                 | 1         | 0.05%   |
| AKAI Professional M.I.           | 1         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 200       | 8.45%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 176       | 7.43%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 167       | 7.05%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 136       | 5.74%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 135       | 5.7%    |
| AMD FCH Azalia Controller                                                                         | 100       | 4.22%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 93        | 3.93%   |
| Intel 8 Series HD Audio Controller                                                                | 84        | 3.55%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 83        | 3.51%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 80        | 3.38%   |
| Intel Broadwell-U Audio Controller                                                                | 78        | 3.29%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 77        | 3.25%   |
| AMD Kabini HDMI/DP Audio                                                                          | 57        | 2.41%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 49        | 2.07%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 49        | 2.07%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 48        | 2.03%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 46        | 1.94%   |
| Intel Cannon Lake PCH cAVS                                                                        | 45        | 1.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 41        | 1.73%   |
| AMD Wrestler HDMI Audio                                                                           | 37        | 1.56%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 34        | 1.44%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 30        | 1.27%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 29        | 1.22%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 27        | 1.14%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 22        | 0.93%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 22        | 0.93%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 22        | 0.93%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 20        | 0.84%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 20        | 0.84%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 20        | 0.84%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 18        | 0.76%   |
| Intel CM238 HD Audio Controller                                                                   | 18        | 0.76%   |
| AMD Trinity HDMI Audio Controller                                                                 | 17        | 0.72%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 16        | 0.68%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 15        | 0.63%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 14        | 0.59%   |
| AMD High Definition Audio Controller                                                              | 14        | 0.59%   |
| Nvidia High Definition Audio Controller                                                           | 13        | 0.55%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 13        | 0.55%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 11        | 0.46%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 11        | 0.46%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 10        | 0.42%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 10        | 0.42%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 9         | 0.38%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 8         | 0.34%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 7         | 0.3%    |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 7         | 0.3%    |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 7         | 0.3%    |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 6         | 0.25%   |
| Intel Comet Lake PCH cAVS                                                                         | 6         | 0.25%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 6         | 0.25%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 6         | 0.25%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 5         | 0.21%   |
| Nvidia MCP79 High Definition Audio                                                                | 5         | 0.21%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 5         | 0.21%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 4         | 0.17%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 4         | 0.17%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 3         | 0.13%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 3         | 0.13%   |
| Nvidia MCP51 High Definition Audio                                                                | 3         | 0.13%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Samsung Electronics   | 465       | 27.5%   |
| SK hynix              | 427       | 25.25%  |
| Unknown               | 185       | 10.94%  |
| Kingston              | 183       | 10.82%  |
| Micron Technology     | 165       | 9.76%   |
| Elpida                | 59        | 3.49%   |
| Nanya Technology      | 58        | 3.43%   |
| Ramaxel Technology    | 37        | 2.19%   |
| A-DATA Technology     | 24        | 1.42%   |
| Crucial               | 16        | 0.95%   |
| Kingmax               | 15        | 0.89%   |
| ASint Technology      | 9         | 0.53%   |
| Corsair               | 8         | 0.47%   |
| 48spaces              | 7         | 0.41%   |
| Qimonda               | 5         | 0.3%    |
| Unknown (ABCD)        | 4         | 0.24%   |
| Transcend             | 4         | 0.24%   |
| Patriot               | 3         | 0.18%   |
| Apacer                | 3         | 0.18%   |
| Kingmax Semiconductor | 2         | 0.12%   |
| Infineon              | 2         | 0.12%   |
| CSX                   | 2         | 0.12%   |
| Unknown (09D5)        | 1         | 0.06%   |
| Toshiba               | 1         | 0.06%   |
| Strontium             | 1         | 0.06%   |
| SHARETRONIC           | 1         | 0.06%   |
| Memory Solution       | 1         | 0.06%   |
| Melco                 | 1         | 0.06%   |
| G.Skill               | 1         | 0.06%   |
| Unknown               | 1         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 39        | 2.15%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 30        | 1.65%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 29        | 1.6%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 28        | 1.54%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                             | 26        | 1.43%   |
| SK hynix RAM HMT325S6CFR8A-PB 2GB SODIMM DDR3 1600MT/s                    | 24        | 1.32%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 24        | 1.32%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s                 | 22        | 1.21%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s                     | 21        | 1.16%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s                     | 20        | 1.1%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s                     | 20        | 1.1%    |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s                     | 18        | 0.99%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 17        | 0.94%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                    | 17        | 0.94%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s                    | 17        | 0.94%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 17        | 0.94%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s                  | 17        | 0.94%   |
| Unknown RAM Module 2048MB SODIMM DDR2                                     | 16        | 0.88%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s                     | 16        | 0.88%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                             | 15        | 0.83%   |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s                    | 15        | 0.83%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s                    | 14        | 0.77%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s                     | 14        | 0.77%   |
| Unknown RAM Module 1024MB SODIMM DDR2                                     | 13        | 0.72%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s                     | 13        | 0.72%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 12        | 0.66%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s                    | 12        | 0.66%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 11        | 0.61%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s                    | 10        | 0.55%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s                     | 10        | 0.55%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s                     | 10        | 0.55%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4096MB SODIMM DDR3 1334MT/s                   | 10        | 0.55%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s                      | 10        | 0.55%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s                     | 10        | 0.55%   |
| Elpida RAM EBJ21UE8BDS0-DJ-F 2048MB SODIMM DDR3 1334MT/s                  | 10        | 0.55%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                                  | 9         | 0.5%    |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 4199MT/s                     | 9         | 0.5%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s                     | 9         | 0.5%    |
| Nanya RAM NT4GC64B8HG0NS-CG 4GB SODIMM DDR3 1334MT/s                      | 9         | 0.5%    |
| Micron RAM 8JSF25664HZ-1G4D1 2048MB SODIMM DDR3 1334MT/s                  | 9         | 0.5%    |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                            | 8         | 0.44%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s                 | 8         | 0.44%   |
| SK hynix RAM HMT351S6BFR8C-H9 4096MB SODIMM DDR3 1334MT/s                 | 8         | 0.44%   |
| SK hynix RAM HMT325S6BFR8C-H9 2048MB SODIMM DDR3 1333MT/s                 | 8         | 0.44%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s                     | 8         | 0.44%   |
| Samsung RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2667MT/s                  | 8         | 0.44%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s                    | 8         | 0.44%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4096MB SODIMM DDR3 1334MT/s                  | 8         | 0.44%   |
| Elpida RAM EBJ21UE8BFU0-DJ-F 2GB SODIMM DDR3 1334MT/s                     | 8         | 0.44%   |
| Unknown RAM Module 512MB SODIMM DDR2                                      | 7         | 0.39%   |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s                             | 7         | 0.39%   |
| SK hynix RAM HYMP125S64CP8-Y5 2048MB SODIMM DDR 667MT/s                   | 7         | 0.39%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 7         | 0.39%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s                    | 7         | 0.39%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s                    | 7         | 0.39%   |
| 48spaces RAM 012345678901234567890123456789012345 2GB SODIMM DDR2 667MT/s | 7         | 0.39%   |
| SK hynix RAM HMT125S6TFR8C-G7 2GB SODIMM DDR3 1067MT/s                    | 6         | 0.33%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s                     | 6         | 0.33%   |
| Samsung RAM M471A1K43BB0-CPB 8192MB SODIMM DDR4 2133MT/s                  | 6         | 0.33%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s                   | 6         | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 804       | 56.18%  |
| DDR4    | 270       | 18.87%  |
| DDR2    | 193       | 13.49%  |
| SDRAM   | 72        | 5.03%   |
| LPDDR4  | 30        | 2.1%    |
| Unknown | 24        | 1.68%   |
| DDR     | 17        | 1.19%   |
| LPDDR3  | 13        | 0.91%   |
| DRAM    | 8         | 0.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1352      | 96.99%  |
| Row Of Chips | 24        | 1.72%   |
| DIMM         | 12        | 0.86%   |
| Chip         | 6         | 0.43%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Notebooks | Percent |
|---------|-----------|---------|
| 4096    | 638       | 41.16%  |
| 2048    | 439       | 28.32%  |
| 8192    | 250       | 16.13%  |
| 1024    | 144       | 9.29%   |
| 16384   | 51        | 3.29%   |
| 512     | 20        | 1.29%   |
| 32768   | 6         | 0.39%   |
| Unknown | 2         | 0.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 533       | 33.88%  |
| 2667    | 181       | 11.51%  |
| 1334    | 162       | 10.3%   |
| 667     | 116       | 7.37%   |
| 1333    | 80        | 5.09%   |
| 1067    | 69        | 4.39%   |
| 2400    | 65        | 4.13%   |
| Unknown | 56        | 3.56%   |
| 800     | 51        | 3.24%   |
| 3200    | 40        | 2.54%   |
| 2133    | 37        | 2.35%   |
| 4199    | 36        | 2.29%   |
| 2048    | 26        | 1.65%   |
| 533     | 26        | 1.65%   |
| 975     | 18        | 1.14%   |
| 1066    | 16        | 1.02%   |
| 3266    | 13        | 0.83%   |
| 333     | 10        | 0.64%   |
| 1867    | 9         | 0.57%   |
| 1639    | 8         | 0.51%   |
| 4266    | 5         | 0.32%   |
| 1776    | 4         | 0.25%   |
| 4267    | 2         | 0.13%   |
| 2267    | 2         | 0.13%   |
| 1866    | 2         | 0.13%   |
| 400     | 2         | 0.13%   |
| 6400    | 1         | 0.06%   |
| 3733    | 1         | 0.06%   |
| 1400    | 1         | 0.06%   |
| 200     | 1         | 0.06%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 11        | 50%     |
| Samsung Electronics   | 3         | 13.64%  |
| Brother Industries    | 3         | 13.64%  |
| Seiko Epson           | 1         | 4.55%   |
| Ricoh                 | 1         | 4.55%   |
| Oki Data              | 1         | 4.55%   |
| Lexmark International | 1         | 4.55%   |
| Canon                 | 1         | 4.55%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| HP Officejet J4500 series               | 2         | 9.09%   |
| HP DeskJet 2130 series                  | 2         | 9.09%   |
| Seiko Epson XP-243 245 247 Series       | 1         | 4.55%   |
| Samsung Xerox Phaser 3117 Laser Printer | 1         | 4.55%   |
| Samsung SCX-4200 series                 | 1         | 4.55%   |
| Samsung Composite Device                | 1         | 4.55%   |
| Ricoh SP 112                            | 1         | 4.55%   |
| Oki Data USB Device                     | 1         | 4.55%   |
| Lexmark International Lexmark X203n     | 1         | 4.55%   |
| HP LaserJet P1102                       | 1         | 4.55%   |
| HP LaserJet P1005                       | 1         | 4.55%   |
| HP LaserJet 1022                        | 1         | 4.55%   |
| HP LaserJet 1020                        | 1         | 4.55%   |
| HP LaserJet 1018                        | 1         | 4.55%   |
| HP DeskJet 5550                         | 1         | 4.55%   |
| HP Deskjet 1510                         | 1         | 4.55%   |
| Canon LiDE 400                          | 1         | 4.55%   |
| Brother PTUSB Printing                  | 1         | 4.55%   |
| Brother HL-1110 series                  | 1         | 4.55%   |
| Brother DCP-1610W                       | 1         | 4.55%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                                         | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Canon                                          | 2         | 50%     |
| Siemens Information and Communication Products | 1         | 25%     |
| Mustek Systems                                 | 1         | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                           | Notebooks | Percent |
|---------------------------------------------------------------------------------|-----------|---------|
| Siemens Information and Communication Products ID-Mouse with Fingerprint Reader | 1         | 25%     |
| Mustek Systems SNAPSCAN e22                                                     | 1         | 25%     |
| Canon CanoScan LIDE 25                                                          | 1         | 25%     |
| Canon CanoScan 4200F                                                            | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 431       | 28.7%   |
| IMC Networks                           | 155       | 10.32%  |
| Microdia                               | 138       | 9.19%   |
| Realtek Semiconductor                  | 135       | 8.99%   |
| Sunplus Innovation Technology          | 110       | 7.32%   |
| Acer                                   | 99        | 6.59%   |
| Suyin                                  | 82        | 5.46%   |
| Quanta                                 | 54        | 3.6%    |
| Cheng Uei Precision Industry (Foxlink) | 50        | 3.33%   |
| Syntek                                 | 42        | 2.8%    |
| Silicon Motion                         | 28        | 1.86%   |
| Lenovo                                 | 28        | 1.86%   |
| Lite-On Technology                     | 22        | 1.46%   |
| Primax Electronics                     | 19        | 1.26%   |
| Alcor Micro                            | 19        | 1.26%   |
| Ricoh                                  | 16        | 1.07%   |
| Z-Star Microelectronics                | 11        | 0.73%   |
| ALi                                    | 10        | 0.67%   |
| Samsung Electronics                    | 7         | 0.47%   |
| Logitech                               | 7         | 0.47%   |
| Importek                               | 6         | 0.4%    |
| Apple                                  | 6         | 0.4%    |
| OmniVision Technologies                | 5         | 0.33%   |
| Luxvisions Innotech Limited            | 4         | 0.27%   |
| GEMBIRD                                | 3         | 0.2%    |
| DigiTech                               | 3         | 0.2%    |
| Sunplus Technology                     | 2         | 0.13%   |
| Genesys Logic                          | 2         | 0.13%   |
| Xiaomi                                 | 1         | 0.07%   |
| Spreadtrum Communications              | 1         | 0.07%   |
| Speed Tech                             | 1         | 0.07%   |
| SHENZHEN EMEET TECHNOLOGY              | 1         | 0.07%   |
| Holitech                               | 1         | 0.07%   |
| GoPro                                  | 1         | 0.07%   |
| eMPIA Technology                       | 1         | 0.07%   |
| Alpha Imaging Technology               | 1         | 0.07%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam                          | 53        | 3.52%   |
| Chicony Integrated Camera                                   | 46        | 3.06%   |
| Chicony HD WebCam                                           | 44        | 2.92%   |
| Chicony HP Truevision HD                                    | 38        | 2.52%   |
| Acer Lenovo EasyCamera                                      | 32        | 2.13%   |
| Microdia Integrated_Webcam_HD                               | 31        | 2.06%   |
| Chicony USB2.0 VGA UVC WebCam                               | 28        | 1.86%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 26        | 1.73%   |
| Realtek USB Camera                                          | 25        | 1.66%   |
| Sunplus HP Truevision HD                                    | 24        | 1.59%   |
| Sunplus Integrated_Webcam_HD                                | 23        | 1.53%   |
| Microdia Integrated Webcam                                  | 23        | 1.53%   |
| Chicony Lenovo EasyCamera                                   | 22        | 1.46%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                    | 20        | 1.33%   |
| Realtek Integrated_Webcam_HD                                | 20        | 1.33%   |
| Sunplus HD WebCam                                           | 18        | 1.2%    |
| IMC Networks EasyCamera                                     | 18        | 1.2%    |
| Quanta VGA WebCam                                           | 17        | 1.13%   |
| Chicony USB2.0 HD UVC WebCam                                | 17        | 1.13%   |
| Chicony Integrated HP HD Webcam                             | 16        | 1.06%   |
| Chicony FJ Camera                                           | 16        | 1.06%   |
| Chicony EasyCamera                                          | 16        | 1.06%   |
| Realtek Integrated Webcam                                   | 15        | 1%      |
| Lenovo Integrated Webcam                                    | 15        | 1%      |
| Chicony VGA Webcam                                          | 15        | 1%      |
| Acer Integrated Camera                                      | 15        | 1%      |
| Microdia Laptop_Integrated_Webcam_HD                        | 14        | 0.93%   |
| Primax HP HD Webcam [Fixed]                                 | 13        | 0.86%   |
| Chicony HP Webcam [2 MP Macro]                              | 13        | 0.86%   |
| Syntek Lenovo EasyCamera                                    | 12        | 0.8%    |
| Lenovo Integrated Webcam [R5U877]                           | 12        | 0.8%    |
| Acer Lenovo Integrated Webcam                               | 12        | 0.8%    |
| Syntek EasyCamera                                           | 11        | 0.73%   |
| Realtek USB2.0 VGA UVC WebCam                               | 11        | 0.73%   |
| Realtek Lenovo EasyCamera                                   | 11        | 0.73%   |
| Chicony 2.0M UVC Webcam / CNF7129                           | 11        | 0.73%   |
| Syntek Integrated Camera                                    | 10        | 0.66%   |
| Suyin Acer CrystalEye Webcam                                | 10        | 0.66%   |
| Silicon Motion WebCam SC-0311139N                           | 10        | 0.66%   |
| Realtek Integrated Webcam HD                                | 10        | 0.66%   |
| Realtek Acer 640 x 480 laptop camera                        | 10        | 0.66%   |
| IMC Networks Integrated Camera                              | 10        | 0.66%   |
| Lite-On Integrated Camera                                   | 9         | 0.6%    |
| IMC Networks UVC VGA Webcam                                 | 9         | 0.6%    |
| IMC Networks Integrated Webcam                              | 9         | 0.6%    |
| Chicony HP Webcam                                           | 9         | 0.6%    |
| Cheng Uei Precision Industry (Foxlink) Webcam               | 9         | 0.6%    |
| ALi Gateway Webcam                                          | 9         | 0.6%    |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 8         | 0.53%   |
| Sunplus HP HD Webcam [Fixed]                                | 8         | 0.53%   |
| Ricoh HD Webcam                                             | 8         | 0.53%   |
| Quanta HD User Facing                                       | 8         | 0.53%   |
| Microdia Sonix USB 2.0 Camera                               | 8         | 0.53%   |
| Microdia Lenovo EasyCamera                                  | 8         | 0.53%   |
| Microdia Dell Laptop Integrated Webcam HD                   | 8         | 0.53%   |
| Chicony HP HD Webcam                                        | 8         | 0.53%   |
| Chicony HP HD Camera                                        | 8         | 0.53%   |
| Acer EasyCamera                                             | 8         | 0.53%   |
| Suyin 1.3M HD WebCam                                        | 7         | 0.47%   |
| Sunplus Asus Webcam                                         | 7         | 0.47%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 85        | 38.81%  |
| AuthenTec                  | 52        | 23.74%  |
| Synaptics                  | 21        | 9.59%   |
| Upek                       | 18        | 8.22%   |
| LighTuning Technology      | 16        | 7.31%   |
| Shenzhen Goodix Technology | 13        | 5.94%   |
| STMicroelectronics         | 10        | 4.57%   |
| Elan Microelectronics      | 4         | 1.83%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AuthenTec AES2810                                                          | 23        | 10.5%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 21        | 9.59%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 18        | 8.22%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 17        | 7.76%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 11        | 5.02%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 11        | 5.02%   |
| STMicroelectronics Fingerprint Reader                                      | 10        | 4.57%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 10        | 4.57%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 8         | 3.65%   |
| Validity Sensors VFS491                                                    | 8         | 3.65%   |
| Shenzhen Goodix  FingerPrint Device                                        | 8         | 3.65%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 6         | 2.74%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 6         | 2.74%   |
| LighTuning Fingerprint Reader                                              | 6         | 2.74%   |
| AuthenTec Fingerprint Sensor                                               | 6         | 2.74%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 5         | 2.28%   |
| Shenzhen Goodix Fingerprint Reader                                         | 5         | 2.28%   |
| Synaptics  WBDI                                                            | 4         | 1.83%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 1.83%   |
| Elan ELAN:Fingerprint                                                      | 4         | 1.83%   |
| AuthenTec AES1600                                                          | 4         | 1.83%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 3         | 1.37%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 1.37%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 1.37%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 3         | 1.37%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 1.37%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 0.91%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 0.91%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.46%   |
| Synaptics WBDI Device                                                      | 1         | 0.46%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.46%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.46%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.46%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 103       | 55.38%  |
| Lenovo                | 27        | 14.52%  |
| Alcor Micro           | 27        | 14.52%  |
| O2 Micro              | 24        | 12.9%   |
| Upek                  | 3         | 1.61%   |
| Yubico.com            | 1         | 0.54%   |
| Gemalto (was Gemplus) | 1         | 0.54%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 59        | 31.72%  |
| Lenovo Integrated Smart Card Reader                                          | 27        | 14.52%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 27        | 14.52%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 23        | 12.37%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 22        | 11.83%  |
| Broadcom 5880                                                                | 11        | 5.91%   |
| Broadcom 58200                                                               | 11        | 5.91%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 1.61%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.54%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.54%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.54%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1213      | 66.18%  |
| 1     | 522       | 28.48%  |
| 2     | 90        | 4.91%   |
| 3     | 7         | 0.38%   |
| 7     | 1         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 219       | 31.33%  |
| Chipcard                 | 174       | 24.89%  |
| Graphics card            | 89        | 12.73%  |
| Bluetooth                | 71        | 10.16%  |
| Net/wireless             | 45        | 6.44%   |
| Storage                  | 34        | 4.86%   |
| Multimedia controller    | 20        | 2.86%   |
| Flash memory             | 14        | 2%      |
| Communication controller | 14        | 2%      |
| Camera                   | 8         | 1.14%   |
| Card reader              | 3         | 0.43%   |
| Sound                    | 2         | 0.29%   |
| Modem                    | 2         | 0.29%   |
| Network                  | 1         | 0.14%   |
| Net/ethernet             | 1         | 0.14%   |
| Firewire controller      | 1         | 0.14%   |
| Dvb card                 | 1         | 0.14%   |

