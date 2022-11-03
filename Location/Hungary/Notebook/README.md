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

Total: 3725

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [c83f37c114](https://linux-hardware.org/?probe=c83f37c114) | Nov 01, 2022 |
| Dell          | G5 5587                     | [a4e32e9eb8](https://linux-hardware.org/?probe=a4e32e9eb8) | Nov 01, 2022 |
| Dell          | Inspiron 5558               | [416655ce7d](https://linux-hardware.org/?probe=416655ce7d) | Oct 30, 2022 |
| Dell          | Inspiron 5558               | [ae71fe1a19](https://linux-hardware.org/?probe=ae71fe1a19) | Oct 30, 2022 |
| Lenovo        | ThinkPad W510 431965U       | [56dd93206a](https://linux-hardware.org/?probe=56dd93206a) | Oct 29, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [aea626acae](https://linux-hardware.org/?probe=aea626acae) | Oct 29, 2022 |
| Dell          | Inspiron 7737               | [f352df76ef](https://linux-hardware.org/?probe=f352df76ef) | Oct 29, 2022 |
| Phoenix/Si... | M7x0S                       | [8b27fc5eb3](https://linux-hardware.org/?probe=8b27fc5eb3) | Oct 29, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HM... | [3b67700f14](https://linux-hardware.org/?probe=3b67700f14) | Oct 28, 2022 |
| HP            | Compaq nx6310 (EY589ES#A... | [a80d2e7626](https://linux-hardware.org/?probe=a80d2e7626) | Oct 27, 2022 |
| Fujitsu       | LIFEBOOK U745               | [7cb792e432](https://linux-hardware.org/?probe=7cb792e432) | Oct 27, 2022 |
| Fujitsu       | LIFEBOOK U745               | [0c33d71210](https://linux-hardware.org/?probe=0c33d71210) | Oct 27, 2022 |
| ASUSTek       | K55VJ                       | [eac363d110](https://linux-hardware.org/?probe=eac363d110) | Oct 25, 2022 |
| ALLDOCUBE     | i1402A                      | [22c255e8cd](https://linux-hardware.org/?probe=22c255e8cd) | Oct 25, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [e5d5599bc7](https://linux-hardware.org/?probe=e5d5599bc7) | Oct 25, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [9cc8a69671](https://linux-hardware.org/?probe=9cc8a69671) | Oct 25, 2022 |
| Dell          | Vostro 3501                 | [df16ec68c3](https://linux-hardware.org/?probe=df16ec68c3) | Oct 24, 2022 |
| Dell          | Vostro 3501                 | [996a5a3b8d](https://linux-hardware.org/?probe=996a5a3b8d) | Oct 24, 2022 |
| HP            | Compaq 6910p (GH717AW#AB... | [02d31506a2](https://linux-hardware.org/?probe=02d31506a2) | Oct 24, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [c24c3f0836](https://linux-hardware.org/?probe=c24c3f0836) | Oct 23, 2022 |
| Dell          | Latitude E6230              | [73ee8be4e9](https://linux-hardware.org/?probe=73ee8be4e9) | Oct 23, 2022 |
| Dell          | Latitude E6230              | [52ee15a8f5](https://linux-hardware.org/?probe=52ee15a8f5) | Oct 23, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [bd25fa1073](https://linux-hardware.org/?probe=bd25fa1073) | Oct 23, 2022 |
| Dell          | Latitude 7390               | [71f8a9e59b](https://linux-hardware.org/?probe=71f8a9e59b) | Oct 22, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [0cf70c348b](https://linux-hardware.org/?probe=0cf70c348b) | Oct 21, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [238c40d2e4](https://linux-hardware.org/?probe=238c40d2e4) | Oct 19, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [680823db07](https://linux-hardware.org/?probe=680823db07) | Oct 19, 2022 |
| Alcor Digi... | Snugbook N1431              | [eb7940e5a4](https://linux-hardware.org/?probe=eb7940e5a4) | Oct 19, 2022 |
| eMachines     | E725                        | [ea21ca2d78](https://linux-hardware.org/?probe=ea21ca2d78) | Oct 19, 2022 |
| Alcor Digi... | Snugbook N1431              | [098e362854](https://linux-hardware.org/?probe=098e362854) | Oct 19, 2022 |
| eMachines     | E725                        | [6d5ddca6c9](https://linux-hardware.org/?probe=6d5ddca6c9) | Oct 18, 2022 |
| Lenovo        | ThinkPad T490 20N2S29E00    | [dd61a6ea26](https://linux-hardware.org/?probe=dd61a6ea26) | Oct 18, 2022 |
| Dell          | Inspiron 3584               | [c80df2b63c](https://linux-hardware.org/?probe=c80df2b63c) | Oct 17, 2022 |
| Acer          | Aspire A717-71G             | [969c0ac771](https://linux-hardware.org/?probe=969c0ac771) | Oct 17, 2022 |
| eMachines     | E725                        | [f365f1eaa7](https://linux-hardware.org/?probe=f365f1eaa7) | Oct 17, 2022 |
| eMachines     | E725                        | [7003528b88](https://linux-hardware.org/?probe=7003528b88) | Oct 17, 2022 |
| ASUSTek       | GL552VW                     | [a49ebeea02](https://linux-hardware.org/?probe=a49ebeea02) | Oct 17, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [528fc3c5ec](https://linux-hardware.org/?probe=528fc3c5ec) | Oct 17, 2022 |
| Unknown       | Unknown                     | [07a141abbb](https://linux-hardware.org/?probe=07a141abbb) | Oct 14, 2022 |
| eMachines     | E725                        | [77e7244d88](https://linux-hardware.org/?probe=77e7244d88) | Oct 14, 2022 |
| eMachines     | E725                        | [34538c32c5](https://linux-hardware.org/?probe=34538c32c5) | Oct 14, 2022 |
| Lenovo        | Z50-75 80EC                 | [b36e579d37](https://linux-hardware.org/?probe=b36e579d37) | Oct 14, 2022 |
| Unknown       | Unknown                     | [0d8c24c367](https://linux-hardware.org/?probe=0d8c24c367) | Oct 13, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [f4d09b3dae](https://linux-hardware.org/?probe=f4d09b3dae) | Oct 13, 2022 |
| Lenovo        | ThinkPad SL510 2847CXG      | [5680d8a827](https://linux-hardware.org/?probe=5680d8a827) | Oct 12, 2022 |
| Acer          | Aspire A515-45              | [3ba623cebe](https://linux-hardware.org/?probe=3ba623cebe) | Oct 12, 2022 |
| Dell          | Latitude 5410               | [e468acae5c](https://linux-hardware.org/?probe=e468acae5c) | Oct 11, 2022 |
| Lenovo        | ThinkPad W530 2463A58       | [dc933df0a9](https://linux-hardware.org/?probe=dc933df0a9) | Oct 10, 2022 |
| ASUSTek       | X550VX                      | [63a8f1baa1](https://linux-hardware.org/?probe=63a8f1baa1) | Oct 10, 2022 |
| ASUSTek       | X550VX                      | [7f9e9ab40b](https://linux-hardware.org/?probe=7f9e9ab40b) | Oct 10, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [5268977f64](https://linux-hardware.org/?probe=5268977f64) | Oct 09, 2022 |
| ASUSTek       | F3Sv                        | [042104bbc2](https://linux-hardware.org/?probe=042104bbc2) | Oct 08, 2022 |
| Lenovo        | V145-15AST 81MT             | [91163f885b](https://linux-hardware.org/?probe=91163f885b) | Oct 07, 2022 |
| Lenovo        | ThinkPad T460s 20FAS30L0... | [ea6a5c970c](https://linux-hardware.org/?probe=ea6a5c970c) | Oct 07, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [7f186dfabd](https://linux-hardware.org/?probe=7f186dfabd) | Oct 07, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [6bae0e4f18](https://linux-hardware.org/?probe=6bae0e4f18) | Oct 07, 2022 |
| eMachines     | E725                        | [9a77e04f3c](https://linux-hardware.org/?probe=9a77e04f3c) | Oct 05, 2022 |
| eMachines     | E725                        | [e413d82fa5](https://linux-hardware.org/?probe=e413d82fa5) | Oct 05, 2022 |
| Dell          | Inspiron 5593               | [33e28ce993](https://linux-hardware.org/?probe=33e28ce993) | Oct 05, 2022 |
| Lenovo        | ThinkPad T410 2537CS0       | [c6a45619c4](https://linux-hardware.org/?probe=c6a45619c4) | Oct 03, 2022 |
| Toshiba       | Satellite M50D-A            | [6eaada1ab0](https://linux-hardware.org/?probe=6eaada1ab0) | Oct 03, 2022 |
| Lenovo        | ThinkPad X230 2325Y5L       | [7c5c62cc90](https://linux-hardware.org/?probe=7c5c62cc90) | Oct 03, 2022 |
| HP            | EliteBook 850 G1            | [7bb0235bd2](https://linux-hardware.org/?probe=7bb0235bd2) | Oct 03, 2022 |
| Dell          | Latitude D630               | [90dc2dddf8](https://linux-hardware.org/?probe=90dc2dddf8) | Oct 02, 2022 |
| Sony          | SVS13118GBB                 | [48dd8fb419](https://linux-hardware.org/?probe=48dd8fb419) | Oct 01, 2022 |
| Dell          | Latitude D630               | [d00c756052](https://linux-hardware.org/?probe=d00c756052) | Oct 01, 2022 |
| Sony          | SVS13118GBB                 | [75e6dbe3d2](https://linux-hardware.org/?probe=75e6dbe3d2) | Oct 01, 2022 |
| ASUSTek       | Strix 15 GL503GE            | [e48bab666f](https://linux-hardware.org/?probe=e48bab666f) | Oct 01, 2022 |
| Sony          | SVS13118GBB                 | [0e0ca26d00](https://linux-hardware.org/?probe=0e0ca26d00) | Sep 30, 2022 |
| Sony          | SVS13118GBB                 | [12868cf90f](https://linux-hardware.org/?probe=12868cf90f) | Sep 30, 2022 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | [1ff8e037f4](https://linux-hardware.org/?probe=1ff8e037f4) | Sep 30, 2022 |
| Acer          | Aspire E5-521               | [a55d68e93c](https://linux-hardware.org/?probe=a55d68e93c) | Sep 30, 2022 |
| Acer          | Aspire A715-72G             | [8b7e129d4a](https://linux-hardware.org/?probe=8b7e129d4a) | Sep 29, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [65f56cc48b](https://linux-hardware.org/?probe=65f56cc48b) | Sep 29, 2022 |
| Lenovo        | IdeaPad 3 15ARE 81W4        | [b784552e84](https://linux-hardware.org/?probe=b784552e84) | Sep 28, 2022 |
| eMachines     | E725                        | [04c9a24d86](https://linux-hardware.org/?probe=04c9a24d86) | Sep 28, 2022 |
| eMachines     | E725                        | [f99f2244c7](https://linux-hardware.org/?probe=f99f2244c7) | Sep 28, 2022 |
| Acer          | Aspire E1-531               | [b7d37d0c6f](https://linux-hardware.org/?probe=b7d37d0c6f) | Sep 27, 2022 |
| Acer          | Aspire E1-531               | [90856d2122](https://linux-hardware.org/?probe=90856d2122) | Sep 27, 2022 |
| ASUSTek       | 1015BX                      | [5190c360db](https://linux-hardware.org/?probe=5190c360db) | Sep 25, 2022 |
| HP            | 650                         | [f835e52a64](https://linux-hardware.org/?probe=f835e52a64) | Sep 25, 2022 |
| HP            | Compaq 6710b (KE125ET#AB... | [fc7831b371](https://linux-hardware.org/?probe=fc7831b371) | Sep 23, 2022 |
| HP            | Compaq 6710b (KE125ET#AB... | [15cffbb03b](https://linux-hardware.org/?probe=15cffbb03b) | Sep 23, 2022 |
| Fujitsu       | LIFEBOOK U745               | [0570d2318c](https://linux-hardware.org/?probe=0570d2318c) | Sep 23, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [4d47a6bfcf](https://linux-hardware.org/?probe=4d47a6bfcf) | Sep 22, 2022 |
| ASUSTek       | K54HR                       | [dbf0f3b1c8](https://linux-hardware.org/?probe=dbf0f3b1c8) | Sep 21, 2022 |
| ASUSTek       | K54HR                       | [25fd2ae90c](https://linux-hardware.org/?probe=25fd2ae90c) | Sep 21, 2022 |
| HP            | 250 G8 Notebook PC          | [17945ad430](https://linux-hardware.org/?probe=17945ad430) | Sep 21, 2022 |
| HP            | 250 G8 Notebook PC          | [49c7f8f204](https://linux-hardware.org/?probe=49c7f8f204) | Sep 21, 2022 |
| Toshiba       | Satellite L450              | [20b85987c4](https://linux-hardware.org/?probe=20b85987c4) | Sep 20, 2022 |
| Toshiba       | Satellite L450              | [9f694612d3](https://linux-hardware.org/?probe=9f694612d3) | Sep 20, 2022 |
| ASUSTek       | X550CL                      | [16d313fefa](https://linux-hardware.org/?probe=16d313fefa) | Sep 20, 2022 |
| eMachines     | E725                        | [141723a3e2](https://linux-hardware.org/?probe=141723a3e2) | Sep 16, 2022 |
| eMachines     | E725                        | [bf27205286](https://linux-hardware.org/?probe=bf27205286) | Sep 15, 2022 |
| Acer          | Aspire 5310                 | [963a5bcade](https://linux-hardware.org/?probe=963a5bcade) | Sep 15, 2022 |
| Dell          | Latitude 7480               | [a9432965f4](https://linux-hardware.org/?probe=a9432965f4) | Sep 15, 2022 |
| Timi          | RedmiBook Pro 15S           | [20b9167fee](https://linux-hardware.org/?probe=20b9167fee) | Sep 11, 2022 |
| HP            | EliteBook 860 16 inch G9... | [080ffe37b9](https://linux-hardware.org/?probe=080ffe37b9) | Sep 08, 2022 |
| Dell          | Latitude E6230              | [41c1130440](https://linux-hardware.org/?probe=41c1130440) | Sep 07, 2022 |
| Dell          | Latitude E6230              | [5e0436a64a](https://linux-hardware.org/?probe=5e0436a64a) | Sep 07, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [32715c6eb9](https://linux-hardware.org/?probe=32715c6eb9) | Sep 06, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [cbc35f08cb](https://linux-hardware.org/?probe=cbc35f08cb) | Sep 06, 2022 |
| Dell          | Latitude 7490               | [4a59725d2d](https://linux-hardware.org/?probe=4a59725d2d) | Sep 05, 2022 |
| Mediacom      | GTZS                        | [d62a43f91e](https://linux-hardware.org/?probe=d62a43f91e) | Sep 04, 2022 |
| HP            | 650                         | [526b86a559](https://linux-hardware.org/?probe=526b86a559) | Sep 04, 2022 |
| HP            | 650                         | [6f184e96df](https://linux-hardware.org/?probe=6f184e96df) | Sep 04, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [e4a4630b4e](https://linux-hardware.org/?probe=e4a4630b4e) | Sep 01, 2022 |
| eMachines     | E725                        | [3e5c01d133](https://linux-hardware.org/?probe=3e5c01d133) | Aug 28, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [1dd156b433](https://linux-hardware.org/?probe=1dd156b433) | Aug 27, 2022 |
| Lenovo        | ThinkPad T420s 4173RT4      | [a10cbdb73b](https://linux-hardware.org/?probe=a10cbdb73b) | Aug 27, 2022 |
| Lenovo        | ThinkPad T420s 4173RT4      | [562d827323](https://linux-hardware.org/?probe=562d827323) | Aug 27, 2022 |
| eMachines     | E725                        | [b73baa0850](https://linux-hardware.org/?probe=b73baa0850) | Aug 25, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [72888e9acb](https://linux-hardware.org/?probe=72888e9acb) | Aug 25, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [92be7f3368](https://linux-hardware.org/?probe=92be7f3368) | Aug 24, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [421ab76c43](https://linux-hardware.org/?probe=421ab76c43) | Aug 24, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [c7d603acb8](https://linux-hardware.org/?probe=c7d603acb8) | Aug 24, 2022 |
| Lenovo        | ThinkPad T410 2537BF9       | [be0227ed47](https://linux-hardware.org/?probe=be0227ed47) | Aug 23, 2022 |
| Dell          | Latitude D630               | [be9c4025cb](https://linux-hardware.org/?probe=be9c4025cb) | Aug 23, 2022 |
| Apple         | MacBookPro8,1               | [88bb92c310](https://linux-hardware.org/?probe=88bb92c310) | Aug 22, 2022 |
| ASUSTek       | 1015BX                      | [94f3284833](https://linux-hardware.org/?probe=94f3284833) | Aug 21, 2022 |
| HP            | ZBook Fury 17.3 inch G8 ... | [8b1d8459e2](https://linux-hardware.org/?probe=8b1d8459e2) | Aug 20, 2022 |
| HP            | 620                         | [d3b1eb8b4e](https://linux-hardware.org/?probe=d3b1eb8b4e) | Aug 20, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [0cef35b44a](https://linux-hardware.org/?probe=0cef35b44a) | Aug 20, 2022 |
| Lenovo        | ThinkPad X220 4290L39       | [31a7893b95](https://linux-hardware.org/?probe=31a7893b95) | Aug 20, 2022 |
| HP            | 620                         | [259635c419](https://linux-hardware.org/?probe=259635c419) | Aug 19, 2022 |
| Dell          | Latitude 5580               | [5c9db9ff58](https://linux-hardware.org/?probe=5c9db9ff58) | Aug 18, 2022 |
| Lenovo        | G50-80 80E5                 | [1a392021c7](https://linux-hardware.org/?probe=1a392021c7) | Aug 18, 2022 |
| Lenovo        | G580 20150                  | [3c18536e95](https://linux-hardware.org/?probe=3c18536e95) | Aug 18, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [9003287b49](https://linux-hardware.org/?probe=9003287b49) | Aug 17, 2022 |
| Dell          | Latitude 5420               | [0dec3e9676](https://linux-hardware.org/?probe=0dec3e9676) | Aug 15, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [6649d66a82](https://linux-hardware.org/?probe=6649d66a82) | Aug 15, 2022 |
| Lenovo        | G50-80 80E5                 | [132a476896](https://linux-hardware.org/?probe=132a476896) | Aug 14, 2022 |
| eMachines     | E725                        | [928cfd8881](https://linux-hardware.org/?probe=928cfd8881) | Aug 13, 2022 |
| eMachines     | E725                        | [e1d0d38a1c](https://linux-hardware.org/?probe=e1d0d38a1c) | Aug 13, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [1d7c1c5212](https://linux-hardware.org/?probe=1d7c1c5212) | Aug 13, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [70b0d2bb45](https://linux-hardware.org/?probe=70b0d2bb45) | Aug 13, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [5d50a29ca9](https://linux-hardware.org/?probe=5d50a29ca9) | Aug 13, 2022 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [4c3d230572](https://linux-hardware.org/?probe=4c3d230572) | Aug 10, 2022 |
| Dell          | Latitude E7450              | [f2d8a030f4](https://linux-hardware.org/?probe=f2d8a030f4) | Aug 08, 2022 |
| Acer          | Nitro AN515-55              | [01e6e21efb](https://linux-hardware.org/?probe=01e6e21efb) | Aug 06, 2022 |
| eMachines     | E520 V1.10                  | [a5c7ca58d9](https://linux-hardware.org/?probe=a5c7ca58d9) | Aug 06, 2022 |
| Dell          | Inspiron 15-3567            | [2ac3b9a2f1](https://linux-hardware.org/?probe=2ac3b9a2f1) | Aug 06, 2022 |
| Dell          | Precision 7530              | [40854a027f](https://linux-hardware.org/?probe=40854a027f) | Aug 05, 2022 |
| Fujitsu       | LIFEBOOK U745               | [c6d5fcceee](https://linux-hardware.org/?probe=c6d5fcceee) | Aug 05, 2022 |
| Fujitsu       | LIFEBOOK U745               | [0e067ccc56](https://linux-hardware.org/?probe=0e067ccc56) | Aug 05, 2022 |
| eMachines     | E725                        | [8028786618](https://linux-hardware.org/?probe=8028786618) | Aug 04, 2022 |
| HP            | Notebook                    | [81b05860ab](https://linux-hardware.org/?probe=81b05860ab) | Aug 04, 2022 |
| Apple         | MacBookAir7,2               | [3e5f261f2a](https://linux-hardware.org/?probe=3e5f261f2a) | Aug 04, 2022 |
| HP            | 625                         | [1c59a9a3d3](https://linux-hardware.org/?probe=1c59a9a3d3) | Aug 03, 2022 |
| HP            | 625                         | [02db8f5852](https://linux-hardware.org/?probe=02db8f5852) | Aug 03, 2022 |
| ASUSTek       | X550JX                      | [469c737a9b](https://linux-hardware.org/?probe=469c737a9b) | Aug 03, 2022 |
| eMachines     | E725                        | [fe35b6624b](https://linux-hardware.org/?probe=fe35b6624b) | Aug 02, 2022 |
| eMachines     | E725                        | [25d51b3945](https://linux-hardware.org/?probe=25d51b3945) | Aug 02, 2022 |
| ASUSTek       | X550JX                      | [edf8c765aa](https://linux-hardware.org/?probe=edf8c765aa) | Aug 02, 2022 |
| eMachines     | E520 V1.10                  | [bb16305e18](https://linux-hardware.org/?probe=bb16305e18) | Aug 01, 2022 |
| HP            | EliteBook 8470p             | [a1d5593420](https://linux-hardware.org/?probe=a1d5593420) | Aug 01, 2022 |
| Packard Be... | EasyNote TM85               | [a6df06f9e5](https://linux-hardware.org/?probe=a6df06f9e5) | Jul 31, 2022 |
| Samsung       | RV415/RV515                 | [5bb2e2b3e9](https://linux-hardware.org/?probe=5bb2e2b3e9) | Jul 31, 2022 |
| HP            | EliteBook 8470p             | [0cecb854f4](https://linux-hardware.org/?probe=0cecb854f4) | Jul 31, 2022 |
| HP            | EliteBook 8470p             | [5e73e33a77](https://linux-hardware.org/?probe=5e73e33a77) | Jul 31, 2022 |
| ASUSTek       | Zenbook UX5401ZA_UX5401Z... | [b8daa2d973](https://linux-hardware.org/?probe=b8daa2d973) | Jul 30, 2022 |
| HP            | 250 G2                      | [43d1d3ae24](https://linux-hardware.org/?probe=43d1d3ae24) | Jul 30, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [e5e5cc4bbc](https://linux-hardware.org/?probe=e5e5cc4bbc) | Jul 29, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [486ef751f0](https://linux-hardware.org/?probe=486ef751f0) | Jul 29, 2022 |
| Lenovo        | Z50-75 80EC                 | [44f505647d](https://linux-hardware.org/?probe=44f505647d) | Jul 29, 2022 |
| HUAWEI        | WRT-WX9                     | [ed09406e6c](https://linux-hardware.org/?probe=ed09406e6c) | Jul 28, 2022 |
| Lenovo        | ThinkPad W510 431965U       | [ab6b15eef4](https://linux-hardware.org/?probe=ab6b15eef4) | Jul 28, 2022 |
| MSI           | GF63 Thin 9SC               | [323db48d16](https://linux-hardware.org/?probe=323db48d16) | Jul 27, 2022 |
| Dell          | Vostro 5471                 | [be2f2c9f98](https://linux-hardware.org/?probe=be2f2c9f98) | Jul 27, 2022 |
| Lenovo        | ThinkPad W510 431965U       | [8ba9959c19](https://linux-hardware.org/?probe=8ba9959c19) | Jul 27, 2022 |
| eMachines     | E725                        | [ca033cf053](https://linux-hardware.org/?probe=ca033cf053) | Jul 26, 2022 |
| Dell          | Inspiron 15-3567            | [06fd282e9d](https://linux-hardware.org/?probe=06fd282e9d) | Jul 25, 2022 |
| eMachines     | E725                        | [b975298e85](https://linux-hardware.org/?probe=b975298e85) | Jul 25, 2022 |
| Alcor         | Intel Education Tablet      | [a04ad41c5a](https://linux-hardware.org/?probe=a04ad41c5a) | Jul 24, 2022 |
| Alcor         | Intel Education Tablet      | [700f83a555](https://linux-hardware.org/?probe=700f83a555) | Jul 24, 2022 |
| Dell          | Latitude D630               | [a9fc5a41aa](https://linux-hardware.org/?probe=a9fc5a41aa) | Jul 24, 2022 |
| Toshiba       | Satellite C650D             | [50e201ffd2](https://linux-hardware.org/?probe=50e201ffd2) | Jul 24, 2022 |
| Dell          | Latitude D630               | [7476af3363](https://linux-hardware.org/?probe=7476af3363) | Jul 23, 2022 |
| Dell          | Precision 3561              | [ca88539127](https://linux-hardware.org/?probe=ca88539127) | Jul 22, 2022 |
| ASUSTek       | Strix 15 GL503GE            | [e543e58f00](https://linux-hardware.org/?probe=e543e58f00) | Jul 22, 2022 |
| Dell          | Precision M4400             | [cf3bbe255a](https://linux-hardware.org/?probe=cf3bbe255a) | Jul 20, 2022 |
| ASUSTek       | 1215P                       | [3bb44d06d1](https://linux-hardware.org/?probe=3bb44d06d1) | Jul 20, 2022 |
| Dell          | Latitude E6420              | [77501652df](https://linux-hardware.org/?probe=77501652df) | Jul 18, 2022 |
| Dell          | Vostro 3500                 | [27a7c25204](https://linux-hardware.org/?probe=27a7c25204) | Jul 17, 2022 |
| Acer          | Swift SF314-43              | [61b8fb7c41](https://linux-hardware.org/?probe=61b8fb7c41) | Jul 17, 2022 |
| eMachines     | E725                        | [771942dd5e](https://linux-hardware.org/?probe=771942dd5e) | Jul 15, 2022 |
| HP            | 255 G5 Notebook PC          | [86b8dc8c6d](https://linux-hardware.org/?probe=86b8dc8c6d) | Jul 15, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [23077c70b2](https://linux-hardware.org/?probe=23077c70b2) | Jul 14, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [10192c3d0b](https://linux-hardware.org/?probe=10192c3d0b) | Jul 14, 2022 |
| HP            | 255 G5 Notebook PC          | [fa6486dcd9](https://linux-hardware.org/?probe=fa6486dcd9) | Jul 13, 2022 |
| eMachines     | E725                        | [27fb6a6cab](https://linux-hardware.org/?probe=27fb6a6cab) | Jul 12, 2022 |
| Lenovo        | ThinkPad T400 2768WGB       | [6998a6fb37](https://linux-hardware.org/?probe=6998a6fb37) | Jul 10, 2022 |
| HP            | Laptop 14s-fq0xxx           | [5a009407d9](https://linux-hardware.org/?probe=5a009407d9) | Jul 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [9ae6c29438](https://linux-hardware.org/?probe=9ae6c29438) | Jul 08, 2022 |
| Dell          | Inspiron 1564               | [0fbabbb83d](https://linux-hardware.org/?probe=0fbabbb83d) | Jul 08, 2022 |
| Dell          | Inspiron 3593               | [d34d56c473](https://linux-hardware.org/?probe=d34d56c473) | Jul 05, 2022 |
| Lenovo        | ThinkPad W510 431924G       | [d65b149a5f](https://linux-hardware.org/?probe=d65b149a5f) | Jul 04, 2022 |
| eMachines     | E725                        | [18d7561b19](https://linux-hardware.org/?probe=18d7561b19) | Jul 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [a2df072a44](https://linux-hardware.org/?probe=a2df072a44) | Jul 03, 2022 |
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
| HP            | 255 G5 Notebook PC          | [7f91291747](https://linux-hardware.org/?probe=7f91291747) | May 28, 2022 |
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
| BlackPanther 18.1            | 1015      | 50.35%  |
| Ubuntu 20.04                 | 158       | 7.84%   |
| BlackPanther 16.2            | 158       | 7.84%   |
| Ubuntu 18.04                 | 93        | 4.61%   |
| Ubuntu 22.04                 | 37        | 1.84%   |
| OpenMandriva 4.2             | 21        | 1.04%   |
| Linux Mint 20.2              | 18        | 0.89%   |
| Linux Mint 19.3              | 15        | 0.74%   |
| KDE neon 20.04               | 13        | 0.64%   |
| Debian 11                    | 13        | 0.64%   |
| Arch                         | 13        | 0.64%   |
| OpenMandriva 4.3             | 12        | 0.6%    |
| Linux Mint 20.3              | 12        | 0.6%    |
| Kubuntu 20.04                | 12        | 0.6%    |
| Ubuntu 19.10                 | 11        | 0.55%   |
| ArcoLinux Rolling            | 11        | 0.55%   |
| Ubuntu 21.10                 | 10        | 0.5%    |
| Ubuntu 21.04                 | 10        | 0.5%    |
| Fedora 36                    | 10        | 0.5%    |
| Fedora 35                    | 10        | 0.5%    |
| Fedora 33                    | 10        | 0.5%    |
| Ubuntu 19.04                 | 9         | 0.45%   |
| Linux Mint 20                | 9         | 0.45%   |
| Debian 10                    | 9         | 0.45%   |
| Manjaro                      | 8         | 0.4%    |
| Linux Mint 20.1              | 8         | 0.4%    |
| Endless 3.9.5                | 8         | 0.4%    |
| Xubuntu 20.04                | 7         | 0.35%   |
| Xubuntu 18.04                | 7         | 0.35%   |
| Ubuntu Unity 16.04           | 6         | 0.3%    |
| Ubuntu 20.10                 | 6         | 0.3%    |
| Pop!_OS 21.04                | 6         | 0.3%    |
| openSUSE Tumbleweed-XXXXXXXX | 6         | 0.3%    |
| Fedora 34                    | 6         | 0.3%    |
| Endless 3.9.1                | 6         | 0.3%    |
| Endless 3.8.0                | 6         | 0.3%    |
| Debian Testing               | 6         | 0.3%    |
| Arch Rolling                 | 6         | 0.3%    |
| Zorin 16                     | 5         | 0.25%   |
| Zorin 15                     | 5         | 0.25%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| BlackPanther  | 1149      | 59.72%  |
| Ubuntu        | 322       | 16.74%  |
| Endless       | 69        | 3.59%   |
| Linux Mint    | 63        | 3.27%   |
| Fedora        | 42        | 2.18%   |
| OpenMandriva  | 36        | 1.87%   |
| Debian        | 30        | 1.56%   |
| Manjaro       | 21        | 1.09%   |
| Kubuntu       | 20        | 1.04%   |
| Xubuntu       | 19        | 0.99%   |
| Pop!_OS       | 19        | 0.99%   |
| Arch          | 18        | 0.94%   |
| KDE neon      | 15        | 0.78%   |
| ArcoLinux     | 13        | 0.68%   |
| ROSA          | 12        | 0.62%   |
| Zorin         | 10        | 0.52%   |
| openSUSE      | 10        | 0.52%   |
| Ubuntu Unity  | 8         | 0.42%   |
| Lubuntu       | 7         | 0.36%   |
| Elementary    | 7         | 0.36%   |
| Ubuntu Budgie | 4         | 0.21%   |
| Kali          | 4         | 0.21%   |
| Clear Linux   | 3         | 0.16%   |
| UbuntuDDE     | 2         | 0.1%    |
| Ubuntu MATE   | 2         | 0.1%    |
| LMDE          | 2         | 0.1%    |
| Gentoo        | 2         | 0.1%    |
| Devuan        | 2         | 0.1%    |
| Xero          | 1         | 0.05%   |
| UHU           | 1         | 0.05%   |
| Ubuntu Studio | 1         | 0.05%   |
| SteamOS       | 1         | 0.05%   |
| Solus         | 1         | 0.05%   |
| PCLinuxOS     | 1         | 0.05%   |
| Parrot        | 1         | 0.05%   |
| MX            | 1         | 0.05%   |
| Garuda Linux  | 1         | 0.05%   |
| EndeavourOS   | 1         | 0.05%   |
| Chrome OS     | 1         | 0.05%   |
| Archman       | 1         | 0.05%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 4.18.16-desktop-1bP      | 768       | 34.67%  |
| 5.6.14-desktop-2bP       | 299       | 13.5%   |
| 4.9.20-desktop-pae-1bP   | 149       | 6.73%   |
| 5.1.15-desktop-1bP       | 56        | 2.53%   |
| 5.4.0-42-generic         | 28        | 1.26%   |
| 5.8.0-14-generic         | 22        | 0.99%   |
| 5.10.14-desktop-1omv4002 | 20        | 0.9%    |
| 5.4.0-58-generic         | 14        | 0.63%   |
| 4.18.0-15-generic        | 14        | 0.63%   |
| 5.3.0-28-generic         | 12        | 0.54%   |
| 5.4.0-52-generic         | 11        | 0.5%    |
| 5.4.0-48-generic         | 11        | 0.5%    |
| 5.4.0-19-generic         | 11        | 0.5%    |
| 5.16.7-desktop-1omv4003  | 11        | 0.5%    |
| 5.11.0-27-generic        | 11        | 0.5%    |
| 5.15.0-43-generic        | 10        | 0.45%   |
| 5.4.0-40-generic         | 9         | 0.41%   |
| 5.4.0-29-generic         | 9         | 0.41%   |
| 5.11.0-34-generic        | 9         | 0.41%   |
| 5.15.0-41-generic        | 8         | 0.36%   |
| 5.4.0-54-generic         | 7         | 0.32%   |
| 5.4.0-26-generic         | 7         | 0.32%   |
| 5.15.0-46-generic        | 7         | 0.32%   |
| 5.8.0-53-generic         | 6         | 0.27%   |
| 5.4.0-91-generic         | 6         | 0.27%   |
| 5.4.0-81-generic         | 6         | 0.27%   |
| 5.4.0-39-generic         | 6         | 0.27%   |
| 5.3.0-23-generic         | 6         | 0.27%   |
| 5.15.0-52-generic        | 6         | 0.27%   |
| 5.15.0-50-generic        | 6         | 0.27%   |
| 5.15.0-48-generic        | 6         | 0.27%   |
| 5.13.0-27-generic        | 6         | 0.27%   |
| 5.11.0-40-generic        | 6         | 0.27%   |
| 4.15.0-43-generic        | 6         | 0.27%   |
| 4.13.0-32-generic        | 6         | 0.27%   |
| 5.8.0-59-generic         | 5         | 0.23%   |
| 5.3.0-42-generic         | 5         | 0.23%   |
| 5.3.0-40-generic         | 5         | 0.23%   |
| 5.3.0-26-generic         | 5         | 0.23%   |
| 5.13.0-28-generic        | 5         | 0.23%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18.16 | 768       | 35.74%  |
| 5.6.14  | 299       | 13.91%  |
| 5.4.0   | 192       | 8.93%   |
| 4.9.20  | 157       | 7.31%   |
| 4.15.0  | 66        | 3.07%   |
| 5.8.0   | 60        | 2.79%   |
| 5.15.0  | 56        | 2.61%   |
| 5.1.15  | 56        | 2.61%   |
| 5.11.0  | 52        | 2.42%   |
| 5.3.0   | 51        | 2.37%   |
| 5.13.0  | 43        | 2%      |
| 5.0.0   | 33        | 1.54%   |
| 4.18.0  | 30        | 1.4%    |
| 5.10.0  | 24        | 1.12%   |
| 5.10.14 | 20        | 0.93%   |
| 5.16.7  | 12        | 0.56%   |
| 4.19.0  | 9         | 0.42%   |
| 4.13.0  | 8         | 0.37%   |
| 5.9.0   | 6         | 0.28%   |
| 4.4.0   | 6         | 0.28%   |
| 5.16.0  | 5         | 0.23%   |
| 5.15.12 | 4         | 0.19%   |
| 5.12.9  | 4         | 0.19%   |
| 5.12.4  | 4         | 0.19%   |
| 5.10.7  | 4         | 0.19%   |
| 4.16.0  | 4         | 0.19%   |
| 5.8.16  | 3         | 0.14%   |
| 5.8.14  | 3         | 0.14%   |
| 5.3.18  | 3         | 0.14%   |
| 5.18.13 | 3         | 0.14%   |
| 5.18.0  | 3         | 0.14%   |
| 5.17.1  | 3         | 0.14%   |
| 5.16.2  | 3         | 0.14%   |
| 5.16.18 | 3         | 0.14%   |
| 5.14.0  | 3         | 0.14%   |
| 5.13.13 | 3         | 0.14%   |
| 5.11.16 | 3         | 0.14%   |
| 4.9.60  | 3         | 0.14%   |
| 6.0.2   | 2         | 0.09%   |
| 5.9.16  | 2         | 0.09%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18    | 797       | 37.31%  |
| 5.6     | 309       | 14.47%  |
| 5.4     | 204       | 9.55%   |
| 4.9     | 164       | 7.68%   |
| 5.8     | 70        | 3.28%   |
| 5.15    | 69        | 3.23%   |
| 4.15    | 66        | 3.09%   |
| 5.11    | 62        | 2.9%    |
| 5.10    | 57        | 2.67%   |
| 5.3     | 56        | 2.62%   |
| 5.1     | 56        | 2.62%   |
| 5.13    | 47        | 2.2%    |
| 5.0     | 33        | 1.54%   |
| 5.16    | 30        | 1.4%    |
| 5.12    | 15        | 0.7%    |
| 5.9     | 13        | 0.61%   |
| 5.18    | 12        | 0.56%   |
| 5.19    | 10        | 0.47%   |
| 5.14    | 10        | 0.47%   |
| 4.19    | 10        | 0.47%   |
| 5.17    | 8         | 0.37%   |
| 4.13    | 8         | 0.37%   |
| 5.7     | 6         | 0.28%   |
| 4.4     | 6         | 0.28%   |
| 6.0     | 4         | 0.19%   |
| 5.5     | 4         | 0.19%   |
| 4.16    | 4         | 0.19%   |
| 4.7     | 2         | 0.09%   |
| 6.1     | 1         | 0.05%   |
| 5.2     | 1         | 0.05%   |
| 4.14    | 1         | 0.05%   |
| 4.1     | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 1707      | 89.89%  |
| i686   | 192       | 10.11%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KDE5            | 1231      | 63.58%  |
| GNOME           | 354       | 18.29%  |
| Unknown         | 138       | 7.13%   |
| XFCE            | 52        | 2.69%   |
| X-Cinnamon      | 45        | 2.32%   |
| MATE            | 23        | 1.19%   |
| KDE             | 23        | 1.19%   |
| Cinnamon        | 17        | 0.88%   |
| KDE4            | 9         | 0.46%   |
| Unity           | 8         | 0.41%   |
| Pantheon        | 7         | 0.36%   |
| LXQt            | 7         | 0.36%   |
| Budgie          | 5         | 0.26%   |
| GNOME Flashback | 4         | 0.21%   |
| Deepin          | 4         | 0.21%   |
| i3              | 3         | 0.15%   |
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
| X11     | 1726      | 90.27%  |
| Wayland | 97        | 5.07%   |
| Unknown | 84        | 4.39%   |
| Tty     | 5         | 0.26%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 1226      | 63.62%  |
| Unknown | 428       | 22.21%  |
| GDM     | 100       | 5.19%   |
| GDM3    | 68        | 3.53%   |
| LightDM | 57        | 2.96%   |
| TDM     | 34        | 1.76%   |
| KDM     | 9         | 0.47%   |
| SLiM    | 3         | 0.16%   |
| XDM     | 2         | 0.1%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1258      | 65.35%  |
| hu_HU   | 413       | 21.45%  |
| en_US   | 206       | 10.7%   |
| en_GB   | 19        | 0.99%   |
| C       | 11        | 0.57%   |
| de_DE   | 5         | 0.26%   |
| ru_UA   | 2         | 0.1%    |
| ru_RU   | 2         | 0.1%    |
| nl_NL   | 2         | 0.1%    |
| en_AU   | 2         | 0.1%    |
| POSIX   | 1         | 0.05%   |
| it_IT   | 1         | 0.05%   |
| fr_BE   | 1         | 0.05%   |
| en_ZA   | 1         | 0.05%   |
| de_AT   | 1         | 0.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 1158      | 59.17%  |
| EFI  | 799       | 40.83%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 1128      | 55.16%  |
| Overlay | 789       | 38.58%  |
| Unknown | 59        | 2.89%   |
| Btrfs   | 52        | 2.54%   |
| Ext2    | 6         | 0.29%   |
| Ext3    | 5         | 0.24%   |
| Zfs     | 3         | 0.15%   |
| Xfs     | 2         | 0.1%    |
| F2fs    | 1         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| MBR     | 892       | 45.49%  |
| GPT     | 610       | 31.11%  |
| Unknown | 459       | 23.41%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1545      | 76.56%  |
| Yes       | 473       | 23.44%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1133      | 56.96%  |
| Yes       | 856       | 43.04%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 392       | 20.92%  |
| Hewlett-Packard     | 364       | 19.42%  |
| Dell                | 330       | 17.61%  |
| ASUSTek Computer    | 270       | 14.41%  |
| Acer                | 208       | 11.1%   |
| Toshiba             | 53        | 2.83%   |
| Samsung Electronics | 35        | 1.87%   |
| Fujitsu Siemens     | 34        | 1.81%   |
| Packard Bell        | 29        | 1.55%   |
| Fujitsu             | 26        | 1.39%   |
| eMachines           | 18        | 0.96%   |
| MSI                 | 17        | 0.91%   |
| Medion              | 14        | 0.75%   |
| Sony                | 12        | 0.64%   |
| Apple               | 9         | 0.48%   |
| Hungaro Flotta Kft  | 7         | 0.37%   |
| Alcor               | 7         | 0.37%   |
| HUAWEI              | 6         | 0.32%   |
| Unknown             | 4         | 0.21%   |
| Timi                | 3         | 0.16%   |
| Intel               | 3         | 0.16%   |
| Insyde              | 3         | 0.16%   |
| Clevo               | 3         | 0.16%   |
| TUXEDO              | 2         | 0.11%   |
| speedmaster         | 2         | 0.11%   |
| Panasonic           | 2         | 0.11%   |
| Notebook            | 2         | 0.11%   |
| Gigabyte Technology | 2         | 0.11%   |
| Valve               | 1         | 0.05%   |
| Phoenix/SiS         | 1         | 0.05%   |
| ordissimo           | 1         | 0.05%   |
| NEC Computers       | 1         | 0.05%   |
| Minix               | 1         | 0.05%   |
| Mediacom            | 1         | 0.05%   |
| LG Electronics      | 1         | 0.05%   |
| IBM                 | 1         | 0.05%   |
| Chiligreen          | 1         | 0.05%   |
| BenQ                | 1         | 0.05%   |
| AMI                 | 1         | 0.05%   |
| Allview             | 1         | 0.05%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| HP 250 G1                            | 41        | 2.19%   |
| Dell Latitude E6410                  | 17        | 0.91%   |
| Unknown                              | 13        | 0.69%   |
| HP 650                               | 11        | 0.59%   |
| Lenovo IdeaPad 330-15IKB 81DE        | 10        | 0.53%   |
| Lenovo IdeaPad 100-15IBD 80QQ        | 10        | 0.53%   |
| Lenovo G50-45 80E3                   | 10        | 0.53%   |
| HP Notebook                          | 10        | 0.53%   |
| HP 620                               | 10        | 0.53%   |
| Dell Latitude E6400                  | 9         | 0.48%   |
| Lenovo ThinkPad T400 2768WGB         | 8         | 0.43%   |
| HP Pavilion 15                       | 8         | 0.43%   |
| Dell Latitude E6530                  | 8         | 0.43%   |
| Dell Latitude E6420                  | 8         | 0.43%   |
| Lenovo Z50-75 80EC                   | 7         | 0.37%   |
| Lenovo G550 20023                    | 7         | 0.37%   |
| HP EliteBook 8460p                   | 7         | 0.37%   |
| HP EliteBook 6930p                   | 7         | 0.37%   |
| Dell Inspiron 15-3567                | 7         | 0.37%   |
| ASUS VivoBook 15_ASUS Laptop X540UBR | 7         | 0.37%   |
| Lenovo Z50-70 20354                  | 6         | 0.32%   |
| Lenovo G580 20150                    | 6         | 0.32%   |
| HP Pavilion g6                       | 6         | 0.32%   |
| HP EliteBook 8470p                   | 6         | 0.32%   |
| HP EliteBook 8440p                   | 6         | 0.32%   |
| HP EliteBook 2560p                   | 6         | 0.32%   |
| eMachines E525                       | 6         | 0.32%   |
| Dell Vostro 15-3568                  | 6         | 0.32%   |
| Dell Latitude E7450                  | 6         | 0.32%   |
| Dell Latitude E6430                  | 6         | 0.32%   |
| Dell Latitude E5420                  | 6         | 0.32%   |
| Dell Latitude D630                   | 6         | 0.32%   |
| Dell Inspiron N5110                  | 6         | 0.32%   |
| Dell Inspiron 5558                   | 6         | 0.32%   |
| ASUS X541NA                          | 6         | 0.32%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR | 6         | 0.32%   |
| ASUS K50IJ                           | 6         | 0.32%   |
| ASUS 1011PX                          | 6         | 0.32%   |
| Toshiba Satellite L300               | 5         | 0.27%   |
| Lenovo IdeaPad 110-15IBR 80T7        | 5         | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 167       | 8.91%   |
| Dell Latitude            | 165       | 8.8%    |
| Acer Aspire              | 151       | 8.06%   |
| Dell Inspiron            | 103       | 5.5%    |
| Lenovo IdeaPad           | 99        | 5.28%   |
| HP EliteBook             | 78        | 4.16%   |
| HP 250                   | 58        | 3.09%   |
| HP ProBook               | 54        | 2.88%   |
| ASUS VivoBook            | 54        | 2.88%   |
| Toshiba Satellite        | 47        | 2.51%   |
| HP Pavilion              | 37        | 1.97%   |
| HP Compaq                | 31        | 1.65%   |
| Packard Bell EasyNote    | 29        | 1.55%   |
| Dell Vostro              | 27        | 1.44%   |
| Fujitsu LIFEBOOK         | 23        | 1.23%   |
| Fujitsu Siemens AMILO    | 19        | 1.01%   |
| Acer TravelMate          | 17        | 0.91%   |
| HP Laptop                | 15        | 0.8%    |
| Acer Swift               | 14        | 0.75%   |
| Unknown                  | 13        | 0.69%   |
| Dell Precision           | 12        | 0.64%   |
| HP 650                   | 11        | 0.59%   |
| Lenovo G50-45            | 10        | 0.53%   |
| HP Notebook              | 10        | 0.53%   |
| HP 620                   | 10        | 0.53%   |
| ASUS ROG                 | 10        | 0.53%   |
| Lenovo 3000              | 9         | 0.48%   |
| HP ZBook                 | 9         | 0.48%   |
| Fujitsu Siemens ESPRIMO  | 9         | 0.48%   |
| Lenovo G580              | 8         | 0.43%   |
| Lenovo Z50-75            | 7         | 0.37%   |
| Lenovo G550              | 7         | 0.37%   |
| Hungaro Flotta Kft Navon | 7         | 0.37%   |
| HP Presario              | 7         | 0.37%   |
| Lenovo Z50-70            | 6         | 0.32%   |
| Lenovo ThinkBook         | 6         | 0.32%   |
| Lenovo Legion            | 6         | 0.32%   |
| HP 255                   | 6         | 0.32%   |
| eMachines E525           | 6         | 0.32%   |
| Dell System              | 6         | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 201       | 10.73%  |
| 2013    | 174       | 9.28%   |
| 2010    | 170       | 9.07%   |
| 2018    | 152       | 8.11%   |
| 2012    | 139       | 7.42%   |
| 2015    | 128       | 6.83%   |
| 2008    | 121       | 6.46%   |
| 2016    | 120       | 6.4%    |
| 2014    | 118       | 6.3%    |
| 2017    | 112       | 5.98%   |
| 2009    | 112       | 5.98%   |
| 2007    | 90        | 4.8%    |
| 2019    | 84        | 4.48%   |
| 2020    | 62        | 3.31%   |
| 2006    | 37        | 1.97%   |
| 2021    | 33        | 1.76%   |
| 2005    | 11        | 0.59%   |
| 2022    | 7         | 0.37%   |
| Unknown | 3         | 0.16%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1874      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1799      | 95.44%  |
| Enabled  | 86        | 4.56%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1874      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 679       | 35.2%   |
| 4.01-8.0    | 454       | 23.54%  |
| 8.01-16.0   | 243       | 12.6%   |
| 1.01-2.0    | 232       | 12.03%  |
| 16.01-24.0  | 136       | 7.05%   |
| 2.01-3.0    | 92        | 4.77%   |
| 32.01-64.0  | 51        | 2.64%   |
| 0.51-1.0    | 30        | 1.56%   |
| 24.01-32.0  | 9         | 0.47%   |
| 64.01-256.0 | 2         | 0.1%    |
| 0.01-0.5    | 1         | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.51-1.0   | 801       | 36.48%  |
| 1.01-2.0   | 703       | 32.01%  |
| 2.01-3.0   | 241       | 10.97%  |
| 0.01-0.5   | 187       | 8.52%   |
| 3.01-4.0   | 120       | 5.46%   |
| 4.01-8.0   | 108       | 4.92%   |
| 8.01-16.0  | 33        | 1.5%    |
| 16.01-24.0 | 2         | 0.09%   |
| 32.01-64.0 | 1         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1516      | 77.98%  |
| 2      | 368       | 18.93%  |
| 3      | 36        | 1.85%   |
| 0      | 18        | 0.93%   |
| 4      | 5         | 0.26%   |
| 5      | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1071      | 56.49%  |
| No        | 825       | 43.51%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1701      | 90.48%  |
| No        | 179       | 9.52%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1851      | 98.77%  |
| No        | 23        | 1.23%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1384      | 72.84%  |
| No        | 516       | 27.16%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Hungary | 1874      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Budapest          | 776       | 35.63%  |
| Pécs             | 45        | 2.07%   |
| Miskolc           | 45        | 2.07%   |
| Debrecen          | 45        | 2.07%   |
| Szeged            | 43        | 1.97%   |
| Tatabánya        | 38        | 1.74%   |
| Győr             | 36        | 1.65%   |
| Székesfehérvár | 34        | 1.56%   |
| Veszprém         | 28        | 1.29%   |
| Szombathely       | 25        | 1.15%   |
| Nyiregyhaza       | 23        | 1.06%   |
| Kecskemét        | 22        | 1.01%   |
| Érd              | 21        | 0.96%   |
| Zalaegerszeg      | 20        | 0.92%   |
| Szigetszentmiklos | 19        | 0.87%   |
| Szolnok           | 17        | 0.78%   |
| Dunaújváros     | 17        | 0.78%   |
| Toekoel           | 16        | 0.73%   |
| Szekszárd        | 16        | 0.73%   |
| Salgotarjan       | 13        | 0.6%    |
| Szorgalmatos      | 12        | 0.55%   |
| Kazincbarcika     | 12        | 0.55%   |
| Sopron            | 11        | 0.51%   |
| Pomaz             | 11        | 0.51%   |
| Kaposvár         | 11        | 0.51%   |
| Gyomro            | 11        | 0.51%   |
| Nagykanizsa       | 10        | 0.46%   |
| Monor             | 10        | 0.46%   |
| Maglod            | 10        | 0.46%   |
| Kiskunfelegyhaza  | 10        | 0.46%   |
| Oroshaza          | 9         | 0.41%   |
| Gödöllő        | 9         | 0.41%   |
| Cegled            | 9         | 0.41%   |
| Ajka              | 9         | 0.41%   |
| Tiszaujvaros      | 8         | 0.37%   |
| Tata              | 8         | 0.37%   |
| Tarnok            | 8         | 0.37%   |
| Solymar           | 8         | 0.37%   |
| Siófok           | 8         | 0.37%   |
| Karcag            | 8         | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 356       | 513    | 15.27%  |
| WDC                 | 317       | 449    | 13.6%   |
| Samsung Electronics | 249       | 372    | 10.68%  |
| Kingston            | 249       | 345    | 10.68%  |
| Toshiba             | 238       | 342    | 10.21%  |
| Hitachi             | 133       | 179    | 5.71%   |
| HGST                | 131       | 183    | 5.62%   |
| Unknown             | 90        | 124    | 3.86%   |
| SanDisk             | 88        | 140    | 3.78%   |
| SK hynix            | 62        | 90     | 2.66%   |
| Intel               | 58        | 80     | 2.49%   |
| Fujitsu             | 43        | 55     | 1.84%   |
| Micron Technology   | 33        | 45     | 1.42%   |
| Crucial             | 33        | 53     | 1.42%   |
| A-DATA Technology   | 28        | 38     | 1.2%    |
| SPCC                | 19        | 24     | 0.82%   |
| JMicron Technology  | 17        | 18     | 0.73%   |
| Apacer              | 17        | 30     | 0.73%   |
| LITEON              | 12        | 14     | 0.51%   |
| PNY                 | 10        | 15     | 0.43%   |
| Kingmax             | 9         | 9      | 0.39%   |
| China               | 9         | 16     | 0.39%   |
| KIOXIA              | 8         | 9      | 0.34%   |
| Transcend           | 7         | 7      | 0.3%    |
| KingSpec            | 7         | 8      | 0.3%    |
| Intenso             | 7         | 14     | 0.3%    |
| Gigabyte Technology | 7         | 10     | 0.3%    |
| OCZ                 | 6         | 6      | 0.26%   |
| LITEONIT            | 6         | 8      | 0.26%   |
| Team                | 5         | 7      | 0.21%   |
| Phison              | 5         | 6      | 0.21%   |
| GOODRAM             | 5         | 6      | 0.21%   |
| ASMT                | 5         | 7      | 0.21%   |
| Apple               | 5         | 6      | 0.21%   |
| Patriot             | 4         | 6      | 0.17%   |
| Verbatim            | 3         | 4      | 0.13%   |
| SSSTC               | 3         | 4      | 0.13%   |
| Silicon Motion      | 3         | 4      | 0.13%   |
| IBM/Hitachi         | 3         | 4      | 0.13%   |
| BHT                 | 3         | 3      | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD    | 54        | 2.24%   |
| Kingston SA400S37120G 120GB SSD    | 52        | 2.16%   |
| Seagate ST1000LM035-1RK172 1TB     | 50        | 2.08%   |
| Toshiba MQ01ABF050 500GB           | 42        | 1.74%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 39        | 1.62%   |
| Toshiba MQ01ABD100 1TB             | 38        | 1.58%   |
| Seagate ST500LT012-1DG142 500GB    | 34        | 1.41%   |
| HGST HTS545032A7E380 320GB         | 32        | 1.33%   |
| Kingston SV300S37A120G 120GB SSD   | 30        | 1.25%   |
| Kingston SA400S37480G 480GB SSD    | 29        | 1.2%    |
| HGST HTS545050A7E680 500GB         | 24        | 1%      |
| Toshiba MQ04ABF100 1TB             | 23        | 0.96%   |
| Seagate ST9320325AS 320GB          | 22        | 0.91%   |
| Samsung SSD 850 EVO 250GB          | 20        | 0.83%   |
| HGST HTS721010A9E630 1TB           | 19        | 0.79%   |
| Seagate ST9500325AS 500GB          | 16        | 0.66%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 15        | 0.62%   |
| Seagate ST9250315AS 250GB          | 15        | 0.62%   |
| Kingston SUV400S37120G 120GB SSD   | 14        | 0.58%   |
| HGST HTS541010A9E680 1TB           | 14        | 0.58%   |
| WDC WD10JPVX-22JC3T0 1TB           | 13        | 0.54%   |
| WDC WD1600BEVT-22ZCT0 160GB        | 12        | 0.5%    |
| SanDisk NVMe SSD Drive 512GB       | 11        | 0.46%   |
| Samsung SSD 860 EVO 500GB          | 11        | 0.46%   |
| Samsung NVMe SSD Drive 512GB       | 11        | 0.46%   |
| WDC WD5000LPCX-24VHAT0 500GB       | 10        | 0.42%   |
| WDC WD5000LPCX-24C6HT0 500GB       | 10        | 0.42%   |
| Seagate ST500LT012-9WS142 500GB    | 10        | 0.42%   |
| JMicron Generic 500GB              | 10        | 0.42%   |
| HGST HTS725050A7E630 500GB         | 10        | 0.42%   |
| WDC WD10SPZX-21Z10T0 1TB           | 9         | 0.37%   |
| Unknown MMC Card  32GB             | 9         | 0.37%   |
| Toshiba MQ01ABD050 500GB           | 9         | 0.37%   |
| Seagate M3 Portable 2TB            | 9         | 0.37%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 8         | 0.33%   |
| WDC WD10SPZX-24Z10 1TB             | 8         | 0.33%   |
| Seagate ST9320423AS 320GB          | 8         | 0.33%   |
| Seagate ST1000LX015-1U7172 1TB     | 8         | 0.33%   |
| SanDisk NVMe SSD Drive 256GB       | 8         | 0.33%   |
| Samsung HM160HI 160GB              | 8         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 347       | 498    | 29.91%  |
| WDC                 | 261       | 362    | 22.5%   |
| Toshiba             | 201       | 275    | 17.33%  |
| Hitachi             | 133       | 179    | 11.47%  |
| HGST                | 131       | 183    | 11.29%  |
| Fujitsu             | 43        | 55     | 3.71%   |
| Samsung Electronics | 31        | 38     | 2.67%   |
| Unknown             | 6         | 7      | 0.52%   |
| IBM/Hitachi         | 3         | 4      | 0.26%   |
| SATAFIRM            | 1         | 1      | 0.09%   |
| JMicron Technology  | 1         | 1      | 0.09%   |
| Initio              | 1         | 1      | 0.09%   |
| HGST HTS            | 1         | 6      | 0.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 227       | 317    | 28.41%  |
| Samsung Electronics | 152       | 218    | 19.02%  |
| SanDisk             | 58        | 92     | 7.26%   |
| Intel               | 40        | 56     | 5.01%   |
| WDC                 | 36        | 58     | 4.51%   |
| Crucial             | 33        | 53     | 4.13%   |
| SK hynix            | 32        | 49     | 4.01%   |
| Micron Technology   | 26        | 33     | 3.25%   |
| A-DATA Technology   | 26        | 36     | 3.25%   |
| SPCC                | 17        | 22     | 2.13%   |
| Apacer              | 16        | 29     | 2%      |
| Toshiba             | 13        | 25     | 1.63%   |
| LITEON              | 12        | 14     | 1.5%    |
| PNY                 | 10        | 15     | 1.25%   |
| Kingmax             | 9         | 9      | 1.13%   |
| China               | 9         | 16     | 1.13%   |
| Transcend           | 7         | 7      | 0.88%   |
| Intenso             | 7         | 14     | 0.88%   |
| OCZ                 | 6         | 6      | 0.75%   |
| LITEONIT            | 6         | 8      | 0.75%   |
| KingSpec            | 6         | 7      | 0.75%   |
| Gigabyte Technology | 6         | 9      | 0.75%   |
| GOODRAM             | 5         | 6      | 0.63%   |
| Team                | 4         | 6      | 0.5%    |
| ASMT                | 4         | 6      | 0.5%    |
| Apple               | 4         | 4      | 0.5%    |
| Verbatim            | 3         | 4      | 0.38%   |
| Patriot             | 3         | 4      | 0.38%   |
| BHT                 | 3         | 3      | 0.38%   |
| Unknown             | 2         | 4      | 0.25%   |
| HS-SSD-C100         | 2         | 2      | 0.25%   |
| Corsair             | 2         | 3      | 0.25%   |
| Zheino              | 1         | 1      | 0.13%   |
| Union Memory        | 1         | 5      | 0.13%   |
| TO Exter            | 1         | 1      | 0.13%   |
| Solid               | 1         | 6      | 0.13%   |
| Seagate             | 1         | 1      | 0.13%   |
| Plextor             | 1         | 1      | 0.13%   |
| Philips             | 1         | 2      | 0.13%   |
| Netac               | 1         | 1      | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1113      | 1610   | 50.09%  |
| SSD     | 744       | 1158   | 33.48%  |
| NVMe    | 247       | 383    | 11.12%  |
| MMC     | 92        | 132    | 4.14%   |
| Unknown | 26        | 30     | 1.17%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1649      | 2708   | 80.6%   |
| NVMe | 239       | 373    | 11.68%  |
| MMC  | 92        | 132    | 4.5%    |
| SAS  | 66        | 100    | 3.23%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1383      | 2145   | 77.26%  |
| 0.51-1.0   | 379       | 577    | 21.17%  |
| 1.01-2.0   | 21        | 37     | 1.17%   |
| 3.01-4.0   | 3         | 3      | 0.17%   |
| 2.01-3.0   | 2         | 4      | 0.11%   |
| 10.01-20.0 | 1         | 1      | 0.06%   |
| 4.01-10.0  | 1         | 1      | 0.06%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 725       | 33.47%  |
| 101-250        | 512       | 23.64%  |
| 251-500        | 351       | 16.2%   |
| 51-100         | 168       | 7.76%   |
| 501-1000       | 153       | 7.06%   |
| 1-20           | 85        | 3.92%   |
| 21-50          | 84        | 3.88%   |
| 1001-2000      | 57        | 2.63%   |
| 2001-3000      | 19        | 0.88%   |
| More than 3000 | 12        | 0.55%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 815       | 37%     |
| Unknown        | 725       | 32.91%  |
| 21-50          | 218       | 9.9%    |
| 51-100         | 165       | 7.49%   |
| 101-250        | 135       | 6.13%   |
| 251-500        | 72        | 3.27%   |
| 501-1000       | 46        | 2.09%   |
| 1001-2000      | 24        | 1.09%   |
| More than 3000 | 2         | 0.09%   |
| 2001-3000      | 1         | 0.05%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Notebooks | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| HGST HTS545032A7E380 320GB              | 30        | 40     | 6.52%   |
| HGST HTS545050A7E680 500GB              | 17        | 26     | 3.7%    |
| Seagate ST9320325AS 320GB               | 11        | 23     | 2.39%   |
| Seagate ST500LT012-1DG142 500GB         | 10        | 13     | 2.17%   |
| Toshiba MQ01ABF050 500GB                | 8         | 22     | 1.74%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 8         | 12     | 1.74%   |
| Toshiba MQ01ABD100 1TB                  | 7         | 8      | 1.52%   |
| Seagate ST9320423AS 320GB               | 7         | 7      | 1.52%   |
| Seagate ST9250315AS 250GB               | 7         | 9      | 1.52%   |
| Seagate ST9500325AS 500GB               | 6         | 10     | 1.3%    |
| Seagate ST500LT012-9WS142 500GB         | 6         | 7      | 1.3%    |
| Samsung Electronics HM160HI 160GB       | 6         | 7      | 1.3%    |
| Kingston SV300S37A120G 120GB SSD        | 6         | 9      | 1.3%    |
| HGST HTS541010A9E680 1TB                | 6         | 13     | 1.3%    |
| Toshiba MQ01ABD050 500GB                | 5         | 5      | 1.09%   |
| Hitachi HTS545032B9A300 320GB           | 5         | 6      | 1.09%   |
| Hitachi HTS545016B9A300 160GB           | 5         | 5      | 1.09%   |
| HGST HTS545050A7E380 500GB              | 5         | 9      | 1.09%   |
| WDC WD10JPVX-22JC3T0 1TB                | 4         | 7      | 0.87%   |
| Seagate ST320LT007-9ZV142 320GB         | 4         | 4      | 0.87%   |
| Seagate ST1000LX015-1U7172 1TB          | 4         | 11     | 0.87%   |
| Hitachi HTS723232A7A364 320GB           | 4         | 4      | 0.87%   |
| Hitachi HTS547550A9E384 500GB           | 4         | 11     | 0.87%   |
| Hitachi HTS545050B9A300 500GB           | 4         | 5      | 0.87%   |
| Hitachi HTS545050A7E380 500GB           | 4         | 6      | 0.87%   |
| Hitachi HTS543216L9A300 160GB           | 4         | 4      | 0.87%   |
| Hitachi HTS542516K9SA00 160GB           | 4         | 4      | 0.87%   |
| Hitachi HTS541680J9SA00 80GB            | 4         | 4      | 0.87%   |
| Toshiba MQ01ABF032 320GB                | 3         | 3      | 0.65%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD | 3         | 4      | 0.65%   |
| Seagate ST980811AS 80GB                 | 3         | 3      | 0.65%   |
| Seagate ST9250410AS 250GB               | 3         | 3      | 0.65%   |
| Seagate ST500LM021-1KJ152 500GB         | 3         | 3      | 0.65%   |
| Seagate ST500LM012 HN-M500MBB 500GB     | 3         | 4      | 0.65%   |
| Seagate ST500LM000-SSHD-8GB             | 3         | 3      | 0.65%   |
| Seagate ST1000LM035-1RK172 1TB          | 3         | 3      | 0.65%   |
| Samsung Electronics HM321HI 320GB       | 3         | 5      | 0.65%   |
| Hitachi HTS545025B9A300 250GB           | 3         | 8      | 0.65%   |
| Hitachi HTS543232A7A384 320GB           | 3         | 5      | 0.65%   |
| Hitachi HTS541612J9SA00 120GB           | 3         | 3      | 0.65%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 112       | 153    | 24.45%  |
| Hitachi             | 75        | 105    | 16.38%  |
| Toshiba             | 69        | 101    | 15.07%  |
| HGST                | 65        | 97     | 14.19%  |
| WDC                 | 52        | 67     | 11.35%  |
| Samsung Electronics | 19        | 25     | 4.15%   |
| Kingston            | 18        | 26     | 3.93%   |
| Fujitsu             | 16        | 23     | 3.49%   |
| Intel               | 12        | 17     | 2.62%   |
| SK hynix            | 6         | 7      | 1.31%   |
| A-DATA Technology   | 3         | 3      | 0.66%   |
| SanDisk             | 2         | 3      | 0.44%   |
| IBM/Hitachi         | 2         | 2      | 0.44%   |
| SPCC                | 1         | 1      | 0.22%   |
| LITEON              | 1         | 1      | 0.22%   |
| Kingmax             | 1         | 1      | 0.22%   |
| JMicron Technology  | 1         | 1      | 0.22%   |
| Intenso             | 1         | 1      | 0.22%   |
| Crucial             | 1         | 1      | 0.22%   |
| Apacer              | 1         | 2      | 0.22%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 112       | 153    | 28.07%  |
| Hitachi             | 75        | 105    | 18.8%   |
| HGST                | 65        | 97     | 16.29%  |
| Toshiba             | 64        | 90     | 16.04%  |
| WDC                 | 50        | 65     | 12.53%  |
| Fujitsu             | 16        | 23     | 4.01%   |
| Samsung Electronics | 15        | 20     | 3.76%   |
| IBM/Hitachi         | 2         | 2      | 0.5%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 389       | 555    | 86.83%  |
| SSD     | 55        | 78     | 12.28%  |
| NVMe    | 3         | 3      | 0.67%   |
| Unknown | 1         | 1      | 0.22%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-22A0RT0 500GB       | 1         | 7      | 8.33%   |
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
| WDC                 | 6         | 12     | 50%     |
| Toshiba             | 3         | 3      | 25%     |
| Seagate             | 2         | 2      | 16.67%  |
| Samsung Electronics | 1         | 1      | 8.33%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1052      | 1747   | 50.85%  |
| Detected | 564       | 911    | 27.26%  |
| Malfunc  | 441       | 637    | 21.31%  |
| Failed   | 12        | 18     | 0.58%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1539      | 75.81%  |
| AMD                              | 216       | 10.64%  |
| Samsung Electronics              | 75        | 3.69%   |
| SanDisk                          | 48        | 2.36%   |
| SK hynix                         | 27        | 1.33%   |
| Toshiba America Info Systems     | 22        | 1.08%   |
| Kingston Technology Company      | 22        | 1.08%   |
| Silicon Integrated Systems [SiS] | 12        | 0.59%   |
| KIOXIA                           | 12        | 0.59%   |
| Nvidia                           | 10        | 0.49%   |
| Phison Electronics               | 8         | 0.39%   |
| VIA Technologies                 | 7         | 0.34%   |
| Micron Technology                | 7         | 0.34%   |
| JMicron Technology               | 5         | 0.25%   |
| Solid State Storage Technology   | 4         | 0.2%    |
| Silicon Motion                   | 4         | 0.2%    |
| ADATA Technology                 | 3         | 0.15%   |
| Silicon Image                    | 2         | 0.1%    |
| Micron/Crucial Technology        | 2         | 0.1%    |
| Shenzhen Longsys Electronics     | 1         | 0.05%   |
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
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 183       | 7.95%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 156       | 6.78%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 154       | 6.69%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 134       | 5.82%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 120       | 5.21%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 104       | 4.52%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 81        | 3.52%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 80        | 3.48%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 68        | 2.95%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 67        | 2.91%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 57        | 2.48%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 57        | 2.48%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 47        | 2.04%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 45        | 1.95%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 44        | 1.91%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 37        | 1.61%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 35        | 1.52%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 34        | 1.48%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 34        | 1.48%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 33        | 1.43%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 31        | 1.35%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 28        | 1.22%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                   | 28        | 1.22%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 27        | 1.17%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 26        | 1.13%   |
| Samsung NVMe SSD Controller 980                                                        | 23        | 1%      |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 23        | 1%      |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 21        | 0.91%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 21        | 0.91%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 16        | 0.7%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 15        | 0.65%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                       | 14        | 0.61%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 14        | 0.61%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 13        | 0.56%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 13        | 0.56%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                   | 12        | 0.52%   |
| KIOXIA NVMe SSD Controller BG4                                                         | 12        | 0.52%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 12        | 0.52%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 12        | 0.52%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                            | 11        | 0.48%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1521      | 69.58%  |
| IDE  | 305       | 13.95%  |
| NVMe | 242       | 11.07%  |
| RAID | 118       | 5.4%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 1623      | 86.61%  |
| AMD          | 249       | 13.29%  |
| CentaurHauls | 2         | 0.11%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz           | 45        | 2.4%    |
| Intel Celeron CPU 1000M @ 1.80GHz           | 41        | 2.18%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 28        | 1.49%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 28        | 1.49%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 27        | 1.44%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 25        | 1.33%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 25        | 1.33%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 21        | 1.12%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 20        | 1.06%   |
| Intel Core i3-7020U CPU @ 2.30GHz           | 19        | 1.01%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 18        | 0.96%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 18        | 0.96%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 18        | 0.96%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz        | 17        | 0.91%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 17        | 0.91%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 16        | 0.85%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz        | 16        | 0.85%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 15        | 0.8%    |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 14        | 0.75%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 14        | 0.75%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 14        | 0.75%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 14        | 0.75%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 14        | 0.75%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 13        | 0.69%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 13        | 0.69%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 13        | 0.69%   |
| Intel Core i3 CPU M 350 @ 2.27GHz           | 13        | 0.69%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 13        | 0.69%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 12        | 0.64%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 12        | 0.64%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 12        | 0.64%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 12        | 0.64%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 12        | 0.64%   |
| Intel Core i5 CPU M 560 @ 2.67GHz           | 12        | 0.64%   |
| Intel Core i5 CPU M 540 @ 2.53GHz           | 12        | 0.64%   |
| Intel Atom CPU N450 @ 1.66GHz               | 12        | 0.64%   |
| Intel Atom CPU N270 @ 1.60GHz               | 12        | 0.64%   |
| Intel Pentium CPU B960 @ 2.20GHz            | 11        | 0.59%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 11        | 0.59%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 11        | 0.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 451       | 24.01%  |
| Intel Core i3           | 244       | 12.99%  |
| Intel Core i7           | 234       | 12.46%  |
| Intel Celeron           | 179       | 9.53%   |
| Intel Core 2 Duo        | 169       | 9%      |
| Intel Pentium           | 84        | 4.47%   |
| Intel Atom              | 67        | 3.57%   |
| Intel Pentium Dual-Core | 38        | 2.02%   |
| Other                   | 30        | 1.6%    |
| Intel Pentium Dual      | 28        | 1.49%   |
| AMD A4                  | 27        | 1.44%   |
| AMD Ryzen 5             | 24        | 1.28%   |
| AMD A8                  | 24        | 1.28%   |
| Intel Core 2            | 23        | 1.22%   |
| AMD Ryzen 7             | 22        | 1.17%   |
| Intel Genuine           | 17        | 0.91%   |
| AMD E1                  | 16        | 0.85%   |
| AMD A6                  | 16        | 0.85%   |
| AMD E2                  | 14        | 0.75%   |
| AMD E                   | 14        | 0.75%   |
| Intel Pentium Silver    | 13        | 0.69%   |
| Intel Celeron M         | 13        | 0.69%   |
| Intel Celeron Dual-Core | 13        | 0.69%   |
| AMD A10                 | 10        | 0.53%   |
| Intel Pentium M         | 9         | 0.48%   |
| Intel Core Duo          | 8         | 0.43%   |
| AMD Ryzen 3             | 8         | 0.43%   |
| AMD Turion 64 X2 Mobile | 6         | 0.32%   |
| AMD FX                  | 6         | 0.32%   |
| AMD C-60                | 5         | 0.27%   |
| AMD Athlon II           | 5         | 0.27%   |
| AMD Ryzen 9             | 4         | 0.21%   |
| AMD Ryzen 7 PRO         | 4         | 0.21%   |
| AMD Mobile Sempron      | 4         | 0.21%   |
| AMD C-50                | 4         | 0.21%   |
| Intel Core i9           | 3         | 0.16%   |
| AMD Ryzen 5 PRO         | 3         | 0.16%   |
| AMD Athlon X2           | 3         | 0.16%   |
| AMD Athlon II Dual-Core | 3         | 0.16%   |
| AMD Athlon 64 X2        | 3         | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1304      | 69.36%  |
| 4      | 362       | 19.26%  |
| 1      | 127       | 6.76%   |
| 6      | 55        | 2.93%   |
| 8      | 30        | 1.6%    |
| 14     | 1         | 0.05%   |
| 10     | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1874      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1070      | 56.79%  |
| 1      | 814       | 43.21%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1801      | 95.59%  |
| 32-bit         | 53        | 2.81%   |
| Unknown        | 30        | 1.59%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 188       | 9.75%   |
| 0x206a7    | 170       | 8.82%   |
| 0x306a9    | 162       | 8.4%    |
| 0x1067a    | 132       | 6.85%   |
| 0x20655    | 100       | 5.19%   |
| 0x40651    | 77        | 3.99%   |
| 0x306d4    | 73        | 3.79%   |
| 0x406e3    | 71        | 3.68%   |
| 0x6fd      | 69        | 3.58%   |
| 0x806ea    | 46        | 2.39%   |
| 0x306c3    | 45        | 2.33%   |
| 0x806e9    | 44        | 2.28%   |
| 0x906ea    | 39        | 2.02%   |
| 0x406c4    | 39        | 2.02%   |
| 0x10676    | 36        | 1.87%   |
| 0x806ec    | 32        | 1.66%   |
| 0x20652    | 32        | 1.66%   |
| 0x106ca    | 31        | 1.61%   |
| 0x506c9    | 26        | 1.35%   |
| 0x30678    | 26        | 1.35%   |
| 0x05000119 | 25        | 1.3%    |
| 0x706a1    | 23        | 1.19%   |
| 0x07030105 | 22        | 1.14%   |
| 0x806c1    | 20        | 1.04%   |
| 0x806eb    | 19        | 0.99%   |
| 0x6fb      | 19        | 0.99%   |
| 0x406c3    | 19        | 0.99%   |
| 0x106c2    | 19        | 0.99%   |
| 0x906e9    | 18        | 0.93%   |
| 0x506e3    | 17        | 0.88%   |
| 0x6f6      | 16        | 0.83%   |
| 0x0700010f | 15        | 0.78%   |
| 0x706e5    | 13        | 0.67%   |
| 0x06001119 | 13        | 0.67%   |
| 0x08600106 | 12        | 0.62%   |
| 0x6ec      | 11        | 0.57%   |
| 0x05000029 | 11        | 0.57%   |
| 0x6f2      | 10        | 0.52%   |
| 0x6d8      | 10        | 0.52%   |
| 0x10661    | 9         | 0.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 233       | 12.43%  |
| SandyBridge      | 175       | 9.34%   |
| Penryn           | 171       | 9.12%   |
| IvyBridge        | 169       | 9.02%   |
| Haswell          | 135       | 7.2%    |
| Westmere         | 134       | 7.15%   |
| Core             | 132       | 7.04%   |
| Skylake          | 103       | 5.5%    |
| Silvermont       | 91        | 4.86%   |
| Broadwell        | 81        | 4.32%   |
| Bonnell          | 52        | 2.77%   |
| Bobcat           | 39        | 2.08%   |
| Puma             | 33        | 1.76%   |
| P6               | 32        | 1.71%   |
| Goldmont         | 31        | 1.65%   |
| Goldmont plus    | 30        | 1.6%    |
| Zen 2            | 22        | 1.17%   |
| Excavator        | 22        | 1.17%   |
| TigerLake        | 20        | 1.07%   |
| Jaguar           | 18        | 0.96%   |
| Piledriver       | 17        | 0.91%   |
| IceLake          | 17        | 0.91%   |
| K8 Hammer        | 16        | 0.85%   |
| K10              | 15        | 0.8%    |
| Zen 3            | 13        | 0.69%   |
| Zen              | 13        | 0.69%   |
| Unknown          | 12        | 0.64%   |
| Steamroller      | 11        | 0.59%   |
| Zen+             | 10        | 0.53%   |
| CometLake        | 8         | 0.43%   |
| K10 Llano        | 7         | 0.37%   |
| Nehalem          | 5         | 0.27%   |
| K8 & K10 hybrid  | 4         | 0.21%   |
| Alderlake Hybrid | 2         | 0.11%   |
| NetBurst         | 1         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1447      | 62.8%   |
| Nvidia                           | 439       | 19.05%  |
| AMD                              | 404       | 17.53%  |
| VIA Technologies                 | 7         | 0.3%    |
| Silicon Integrated Systems [SiS] | 7         | 0.3%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 166       | 6.73%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 161       | 6.52%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 136       | 5.51%   |
| Intel Core Processor Integrated Graphics Controller                                      | 93        | 3.77%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 82        | 3.32%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 74        | 3%      |
| Intel HD Graphics 5500                                                                   | 70        | 2.84%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 60        | 2.43%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 57        | 2.31%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 51        | 2.07%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 51        | 2.07%   |
| Intel UHD Graphics 620                                                                   | 48        | 1.94%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 44        | 1.78%   |
| Intel HD Graphics 620                                                                    | 43        | 1.74%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 41        | 1.66%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 38        | 1.54%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 34        | 1.38%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 32        | 1.3%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 31        | 1.26%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 31        | 1.26%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 28        | 1.13%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 27        | 1.09%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 24        | 0.97%   |
| Intel HD Graphics 500                                                                    | 24        | 0.97%   |
| AMD Renoir                                                                               | 22        | 0.89%   |
| Intel HD Graphics 530                                                                    | 21        | 0.85%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 21        | 0.85%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 20        | 0.81%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 19        | 0.77%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 19        | 0.77%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                             | 19        | 0.77%   |
| Nvidia GP108M [GeForce MX150]                                                            | 18        | 0.73%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 17        | 0.69%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 17        | 0.69%   |
| Nvidia GM108M [GeForce MX110]                                                            | 16        | 0.65%   |
| Intel HD Graphics 630                                                                    | 16        | 0.65%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 16        | 0.65%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 15        | 0.61%   |
| Intel Kaby Lake-U GT2f HD 620 Graphics Controller                                        | 14        | 0.57%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 14        | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 1034      | 55.09%  |
| Intel + Nvidia | 321       | 17.1%   |
| 1 x AMD        | 241       | 12.84%  |
| 1 x Nvidia     | 102       | 5.43%   |
| Intel + AMD    | 92        | 4.9%    |
| 2 x AMD        | 55        | 2.93%   |
| AMD + Nvidia   | 17        | 0.91%   |
| 1 x VIA        | 7         | 0.37%   |
| 1 x SiS        | 7         | 0.37%   |
| Other          | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1758      | 93.07%  |
| Proprietary | 103       | 5.45%   |
| Unknown     | 28        | 1.48%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1080      | 55.93%  |
| 0.01-0.5   | 353       | 18.28%  |
| 1.01-2.0   | 269       | 13.93%  |
| 0.51-1.0   | 120       | 6.21%   |
| 3.01-4.0   | 85        | 4.4%    |
| 5.01-6.0   | 15        | 0.78%   |
| 7.01-8.0   | 5         | 0.26%   |
| 2.01-3.0   | 3         | 0.16%   |
| 8.01-16.0  | 1         | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 401       | 19.89%  |
| AU Optronics            | 391       | 19.39%  |
| Samsung Electronics     | 294       | 14.58%  |
| Chimei Innolux          | 244       | 12.1%   |
| BOE                     | 196       | 9.72%   |
| Chi Mei Optoelectronics | 93        | 4.61%   |
| Lenovo                  | 75        | 3.72%   |
| Goldstar                | 41        | 2.03%   |
| LG Philips              | 35        | 1.74%   |
| Dell                    | 26        | 1.29%   |
| InfoVision              | 21        | 1.04%   |
| PANDA                   | 14        | 0.69%   |
| CPT                     | 14        | 0.69%   |
| Philips                 | 12        | 0.6%    |
| Acer                    | 12        | 0.6%    |
| HannStar                | 10        | 0.5%    |
| Apple                   | 10        | 0.5%    |
| Hewlett-Packard         | 9         | 0.45%   |
| BenQ                    | 9         | 0.45%   |
| Sony                    | 8         | 0.4%    |
| Sharp                   | 8         | 0.4%    |
| Quanta Display          | 8         | 0.4%    |
| Toshiba                 | 7         | 0.35%   |
| ASUSTek Computer        | 7         | 0.35%   |
| AOC                     | 6         | 0.3%    |
| Ancor Communications    | 6         | 0.3%    |
| InnoLux Display         | 5         | 0.25%   |
| Vestel Elektronik       | 4         | 0.2%    |
| Panasonic               | 4         | 0.2%    |
| Fujitsu Siemens         | 4         | 0.2%    |
| NEC Computers           | 3         | 0.15%   |
| IBM                     | 3         | 0.15%   |
| Eizo                    | 3         | 0.15%   |
| TMX                     | 2         | 0.1%    |
| SKY                     | 2         | 0.1%    |
| Plain Tree Systems      | 2         | 0.1%    |
| OEM                     | 2         | 0.1%    |
| MSI                     | 2         | 0.1%    |
| MiTAC                   | 2         | 0.1%    |
| Lenovo Group Limited    | 2         | 0.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 49        | 2.41%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 35        | 1.72%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 34        | 1.68%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 24        | 1.18%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 24        | 1.18%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 21        | 1.03%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 19        | 0.94%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 18        | 0.89%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch                  | 14        | 0.69%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 14        | 0.69%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 14        | 0.69%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 14        | 0.69%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 13        | 0.64%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 12        | 0.59%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 12        | 0.59%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 12        | 0.59%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch            | 11        | 0.54%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 11        | 0.54%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 11        | 0.54%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 11        | 0.54%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch     | 10        | 0.49%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 10        | 0.49%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 10        | 0.49%   |
| LG Display LCD Monitor LGD02AD 1366x768 344x194mm 15.5-inch              | 9         | 0.44%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 9         | 0.44%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 8         | 0.39%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch              | 8         | 0.39%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 8         | 0.39%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 8         | 0.39%   |
| Chi Mei Optoelectronics LCD Monitor CMO1526 1280x800 331x207mm 15.4-inch | 8         | 0.39%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 8         | 0.39%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch            | 8         | 0.39%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch     | 7         | 0.34%   |
| LG Philips LP154WX4-TLC8 LPL0120 1280x800 331x207mm 15.4-inch            | 7         | 0.34%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 7         | 0.34%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch              | 7         | 0.34%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x194mm 15.5-inch                  | 7         | 0.34%   |
| Lenovo LCD Monitor LEN4035 1280x800 304x190mm 14.1-inch                  | 7         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 7         | 0.34%   |
| BOE LCD Monitor BOE061D 1366x768 309x173mm 13.9-inch                     | 7         | 0.34%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 818       | 42.01%  |
| 1920x1080 (FHD)    | 570       | 29.28%  |
| 1280x800 (WXGA)    | 163       | 8.37%   |
| 1600x900 (HD+)     | 127       | 6.52%   |
| 1440x900 (WXGA+)   | 56        | 2.88%   |
| 1024x600           | 38        | 1.95%   |
| 3840x2160 (4K)     | 35        | 1.8%    |
| 1920x1200 (WUXGA)  | 26        | 1.34%   |
| 1680x1050 (WSXGA+) | 21        | 1.08%   |
| 1280x1024 (SXGA)   | 17        | 0.87%   |
| 2560x1440 (QHD)    | 15        | 0.77%   |
| 1024x768 (XGA)     | 15        | 0.77%   |
| 2880x1800          | 7         | 0.36%   |
| 1920x540           | 6         | 0.31%   |
| 2560x1080          | 5         | 0.26%   |
| 1360x768           | 5         | 0.26%   |
| 2560x1600          | 4         | 0.21%   |
| 3440x1440          | 2         | 0.1%    |
| 3200x2000          | 2         | 0.1%    |
| 2160x1440          | 2         | 0.1%    |
| 1400x1050          | 2         | 0.1%    |
| 1280x768           | 2         | 0.1%    |
| 800x1280           | 1         | 0.05%   |
| 3840x2400          | 1         | 0.05%   |
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
| 15      | 1110      | 54.98%  |
| 14      | 224       | 11.09%  |
| 13      | 155       | 7.68%   |
| 17      | 125       | 6.19%   |
| 12      | 74        | 3.67%   |
| 10      | 46        | 2.28%   |
| 24      | 40        | 1.98%   |
| 23      | 39        | 1.93%   |
| 11      | 34        | 1.68%   |
| 21      | 33        | 1.63%   |
| 27      | 31        | 1.54%   |
| 18      | 18        | 0.89%   |
| 19      | 13        | 0.64%   |
| 22      | 10        | 0.5%    |
| Unknown | 10        | 0.5%    |
| 20      | 7         | 0.35%   |
| 34      | 6         | 0.3%    |
| 72      | 5         | 0.25%   |
| 40      | 5         | 0.25%   |
| 32      | 5         | 0.25%   |
| 84      | 4         | 0.2%    |
| 31      | 4         | 0.2%    |
| 16      | 4         | 0.2%    |
| 54      | 3         | 0.15%   |
| 8       | 3         | 0.15%   |
| 65      | 2         | 0.1%    |
| 33      | 2         | 0.1%    |
| 52      | 1         | 0.05%   |
| 48      | 1         | 0.05%   |
| 42      | 1         | 0.05%   |
| 41      | 1         | 0.05%   |
| 39      | 1         | 0.05%   |
| 29      | 1         | 0.05%   |
| 9       | 1         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 1389      | 69.17%  |
| 201-300     | 217       | 10.81%  |
| 351-400     | 169       | 8.42%   |
| 501-600     | 104       | 5.18%   |
| 401-500     | 70        | 3.49%   |
| 701-800     | 13        | 0.65%   |
| Unknown     | 10        | 0.5%    |
| 1501-2000   | 9         | 0.45%   |
| 601-700     | 8         | 0.4%    |
| 1001-1500   | 7         | 0.35%   |
| 801-900     | 6         | 0.3%    |
| 101-200     | 4         | 0.2%    |
| 901-1000    | 2         | 0.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1530      | 82.08%  |
| 16/10   | 277       | 14.86%  |
| 4/3     | 20        | 1.07%   |
| 5/4     | 16        | 0.86%   |
| 3/2     | 8         | 0.43%   |
| 21/9    | 6         | 0.32%   |
| Unknown | 6         | 0.32%   |
| 0.62    | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1107      | 54.86%  |
| 81-90          | 322       | 15.96%  |
| 201-250        | 100       | 4.96%   |
| 121-130        | 90        | 4.46%   |
| 61-70          | 72        | 3.57%   |
| 71-80          | 55        | 2.73%   |
| 41-50          | 46        | 2.28%   |
| 51-60          | 34        | 1.68%   |
| 301-350        | 31        | 1.54%   |
| 151-200        | 29        | 1.44%   |
| 131-140        | 28        | 1.39%   |
| 141-150        | 23        | 1.14%   |
| 351-500        | 17        | 0.84%   |
| More than 1000 | 16        | 0.79%   |
| 251-300        | 16        | 0.79%   |
| Unknown        | 10        | 0.5%    |
| 501-1000       | 8         | 0.4%    |
| 91-100         | 8         | 0.4%    |
| 1-40           | 4         | 0.2%    |
| 111-120        | 2         | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 841       | 42.22%  |
| 121-160       | 651       | 32.68%  |
| 51-100        | 403       | 20.23%  |
| 161-240       | 58        | 2.91%   |
| More than 240 | 17        | 0.85%   |
| 1-50          | 12        | 0.6%    |
| Unknown       | 10        | 0.5%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1680      | 87.32%  |
| 2     | 209       | 10.86%  |
| 0     | 21        | 1.09%   |
| 3     | 14        | 0.73%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 935       | 30.36%  |
| Intel                             | 869       | 28.21%  |
| Qualcomm Atheros                  | 579       | 18.8%   |
| Broadcom                          | 247       | 8.02%   |
| Ralink                            | 95        | 3.08%   |
| Broadcom Limited                  | 89        | 2.89%   |
| Marvell Technology Group          | 44        | 1.43%   |
| Dell                              | 26        | 0.84%   |
| MediaTek                          | 22        | 0.71%   |
| Hewlett-Packard                   | 17        | 0.55%   |
| Ericsson Business Mobile Networks | 15        | 0.49%   |
| Sierra Wireless                   | 13        | 0.42%   |
| TP-Link                           | 12        | 0.39%   |
| Samsung Electronics               | 12        | 0.39%   |
| Huawei Technologies               | 12        | 0.39%   |
| Silicon Integrated Systems [SiS]  | 11        | 0.36%   |
| Attansic Technology               | 11        | 0.36%   |
| JMicron Technology                | 10        | 0.32%   |
| Ralink Technology                 | 9         | 0.29%   |
| Qualcomm Atheros Communications   | 6         | 0.19%   |
| ASIX Electronics                  | 6         | 0.19%   |
| Xiaomi                            | 5         | 0.16%   |
| VIA Technologies                  | 5         | 0.16%   |
| Nvidia                            | 4         | 0.13%   |
| DisplayLink                       | 4         | 0.13%   |
| D-Link                            | 3         | 0.1%    |
| ZTE WCDMA Technologies MSM        | 2         | 0.06%   |
| Belkin Components                 | 2         | 0.06%   |
| ASUSTek Computer                  | 2         | 0.06%   |
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
| Compal Electronics                | 1         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 553       | 14.81%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 282       | 7.55%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 110       | 2.95%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 105       | 2.81%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 102       | 2.73%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 99        | 2.65%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 73        | 1.95%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 72        | 1.93%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 65        | 1.74%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 64        | 1.71%   |
| Intel Wireless 7260                                                     | 60        | 1.61%   |
| Intel 82577LM Gigabit Network Connection                                | 60        | 1.61%   |
| Intel Wireless 8265 / 8275                                              | 58        | 1.55%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 55        | 1.47%   |
| Intel 82567LM Gigabit Network Connection                                | 53        | 1.42%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 52        | 1.39%   |
| Intel Wireless 7265                                                     | 50        | 1.34%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 50        | 1.34%   |
| Intel Centrino Advanced-N 6200                                          | 48        | 1.29%   |
| Intel Wireless 3165                                                     | 34        | 0.91%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 34        | 0.91%   |
| Intel Centrino Ultimate-N 6300                                          | 33        | 0.88%   |
| Intel Wireless 3160                                                     | 32        | 0.86%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 32        | 0.86%   |
| Intel Wireless 8260                                                     | 31        | 0.83%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 31        | 0.83%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 28        | 0.75%   |
| Intel WiFi Link 5100                                                    | 27        | 0.72%   |
| Broadcom BCM43142 802.11b/g/n                                           | 27        | 0.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 25        | 0.67%   |
| Intel Ethernet Connection I218-LM                                       | 25        | 0.67%   |
| Intel Wi-Fi 6 AX200                                                     | 24        | 0.64%   |
| Intel Ethernet Connection (3) I218-LM                                   | 24        | 0.64%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 24        | 0.64%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 23        | 0.62%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 21        | 0.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 20        | 0.54%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 19        | 0.51%   |
| Intel Wi-Fi 6 AX201                                                     | 19        | 0.51%   |
| Intel Ultimate N WiFi Link 5300                                         | 19        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 810       | 41.99%  |
| Qualcomm Atheros                | 513       | 26.59%  |
| Realtek Semiconductor           | 222       | 11.51%  |
| Broadcom                        | 164       | 8.5%    |
| Ralink                          | 95        | 4.92%   |
| Broadcom Limited                | 40        | 2.07%   |
| MediaTek                        | 21        | 1.09%   |
| Dell                            | 15        | 0.78%   |
| Sierra Wireless                 | 13        | 0.67%   |
| Ralink Technology               | 9         | 0.47%   |
| TP-Link                         | 8         | 0.41%   |
| Qualcomm Atheros Communications | 6         | 0.31%   |
| Hewlett-Packard                 | 3         | 0.16%   |
| D-Link                          | 3         | 0.16%   |
| Belkin Components               | 2         | 0.1%    |
| ASUSTek Computer                | 2         | 0.1%    |
| NetGear                         | 1         | 0.05%   |
| Micro Star International        | 1         | 0.05%   |
| Fujitsu Siemens Computers       | 1         | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 110       | 5.68%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 102       | 5.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 99        | 5.11%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 73        | 3.77%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 72        | 3.72%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 65        | 3.36%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 64        | 3.31%   |
| Intel Wireless 7260                                                     | 60        | 3.1%    |
| Intel Wireless 8265 / 8275                                              | 58        | 3%      |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 55        | 2.84%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 52        | 2.69%   |
| Intel Wireless 7265                                                     | 50        | 2.58%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 50        | 2.58%   |
| Intel Centrino Advanced-N 6200                                          | 48        | 2.48%   |
| Intel Wireless 3165                                                     | 34        | 1.76%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 34        | 1.76%   |
| Intel Centrino Ultimate-N 6300                                          | 33        | 1.7%    |
| Intel Wireless 3160                                                     | 32        | 1.65%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 32        | 1.65%   |
| Intel Wireless 8260                                                     | 31        | 1.6%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 31        | 1.6%    |
| Intel WiFi Link 5100                                                    | 27        | 1.39%   |
| Broadcom BCM43142 802.11b/g/n                                           | 27        | 1.39%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 25        | 1.29%   |
| Intel Wi-Fi 6 AX200                                                     | 24        | 1.24%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 24        | 1.24%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 23        | 1.19%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 19        | 0.98%   |
| Intel Wi-Fi 6 AX201                                                     | 19        | 0.98%   |
| Intel Ultimate N WiFi Link 5300                                         | 19        | 0.98%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 18        | 0.93%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 17        | 0.88%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 17        | 0.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 17        | 0.88%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 17        | 0.88%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 16        | 0.83%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 16        | 0.83%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 14        | 0.72%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 14        | 0.72%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 13        | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 875       | 50.14%  |
| Intel                            | 432       | 24.76%  |
| Qualcomm Atheros                 | 143       | 8.19%   |
| Broadcom                         | 106       | 6.07%   |
| Broadcom Limited                 | 50        | 2.87%   |
| Marvell Technology Group         | 44        | 2.52%   |
| Samsung Electronics              | 12        | 0.69%   |
| Silicon Integrated Systems [SiS] | 11        | 0.63%   |
| Huawei Technologies              | 11        | 0.63%   |
| Attansic Technology              | 11        | 0.63%   |
| JMicron Technology               | 10        | 0.57%   |
| ASIX Electronics                 | 6         | 0.34%   |
| Xiaomi                           | 5         | 0.29%   |
| VIA Technologies                 | 5         | 0.29%   |
| TP-Link                          | 4         | 0.23%   |
| Nvidia                           | 4         | 0.23%   |
| DisplayLink                      | 4         | 0.23%   |
| ZTE WCDMA Technologies MSM       | 2         | 0.11%   |
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
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 553       | 31.6%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 282       | 16.11%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 105       | 6%      |
| Intel 82577LM Gigabit Network Connection                          | 60        | 3.43%   |
| Intel 82567LM Gigabit Network Connection                          | 53        | 3.03%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 28        | 1.6%    |
| Intel Ethernet Connection I218-LM                                 | 25        | 1.43%   |
| Intel Ethernet Connection (3) I218-LM                             | 24        | 1.37%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 21        | 1.2%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 20        | 1.14%   |
| Intel 82566MM Gigabit Network Connection                          | 19        | 1.09%   |
| Intel Ethernet Connection I217-LM                                 | 17        | 0.97%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 16        | 0.91%   |
| Intel Ethernet Connection (4) I219-LM                             | 16        | 0.91%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 15        | 0.86%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 15        | 0.86%   |
| Intel Ethernet Connection I219-LM                                 | 15        | 0.86%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 14        | 0.8%    |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 14        | 0.8%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 13        | 0.74%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 13        | 0.74%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 12        | 0.69%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 12        | 0.69%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 12        | 0.69%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 11        | 0.63%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 11        | 0.63%   |
| Intel 82579V Gigabit Network Connection                           | 11        | 0.63%   |
| Huawei LYA-L09                                                    | 11        | 0.63%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 11        | 0.63%   |
| Attansic AR8152 v2.0 Fast Ethernet                                | 11        | 0.63%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 10        | 0.57%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 10        | 0.57%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 10        | 0.57%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 10        | 0.57%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 9         | 0.51%   |
| Intel Ethernet Connection I219-V                                  | 8         | 0.46%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 8         | 0.46%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 7         | 0.4%    |
| Intel Ethernet Connection (2) I219-LM                             | 7         | 0.4%    |
| Intel 82577LC Gigabit Network Connection                          | 7         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1851      | 51.45%  |
| Ethernet | 1698      | 47.19%  |
| Modem    | 48        | 1.33%   |
| Unknown  | 1         | 0.03%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1526      | 74.8%   |
| Ethernet | 514       | 25.2%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1645      | 87.69%  |
| 1     | 199       | 10.61%  |
| 0     | 25        | 1.33%   |
| 3     | 7         | 0.37%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1682      | 86.84%  |
| Yes  | 255       | 13.16%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 453       | 32.5%   |
| Qualcomm Atheros Communications | 162       | 11.62%  |
| Broadcom                        | 135       | 9.68%   |
| Realtek Semiconductor           | 117       | 8.39%   |
| Lite-On Technology              | 83        | 5.95%   |
| Dell                            | 77        | 5.52%   |
| IMC Networks                    | 72        | 5.16%   |
| Hewlett-Packard                 | 67        | 4.81%   |
| Ralink                          | 64        | 4.59%   |
| Foxconn / Hon Hai               | 56        | 4.02%   |
| Cambridge Silicon Radio         | 26        | 1.87%   |
| Toshiba                         | 20        | 1.43%   |
| ASUSTek Computer                | 11        | 0.79%   |
| Ralink Technology               | 9         | 0.65%   |
| Realtek                         | 8         | 0.57%   |
| Apple                           | 8         | 0.57%   |
| Chicony Electronics             | 5         | 0.36%   |
| Askey Computer                  | 5         | 0.36%   |
| Taiyo Yuden                     | 4         | 0.29%   |
| Foxconn International           | 4         | 0.29%   |
| Micro Star International        | 3         | 0.22%   |
| Alps Electric                   | 2         | 0.14%   |
| Opticis                         | 1         | 0.07%   |
| MediaTek                        | 1         | 0.07%   |
| Fujitsu Siemens Computers       | 1         | 0.07%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 271       | 19.4%   |
| Qualcomm Atheros  Bluetooth Device                  | 67        | 4.8%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 65        | 4.65%   |
| Ralink RT3290 Bluetooth                             | 64        | 4.58%   |
| Realtek Bluetooth Radio                             | 63        | 4.51%   |
| Intel AX201 Bluetooth                               | 38        | 2.72%   |
| Dell DW375 Bluetooth Module                         | 38        | 2.72%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 34        | 2.43%   |
| HP Broadcom 2070 Bluetooth Combo                    | 33        | 2.36%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 33        | 2.36%   |
| Broadcom BCM2045B (BDC-2.1)                         | 32        | 2.29%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 30        | 2.15%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 29        | 2.08%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 26        | 1.86%   |
| IMC Networks Bluetooth Radio                        | 23        | 1.65%   |
| IMC Networks Bluetooth Device                       | 22        | 1.57%   |
| Intel AX200 Bluetooth                               | 21        | 1.5%    |
| Broadcom HP Portable SoftSailing                    | 21        | 1.5%    |
| Realtek RTL8723B Bluetooth                          | 19        | 1.36%   |
| Lite-On Bluetooth Device                            | 19        | 1.36%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 19        | 1.36%   |
| Foxconn / Hon Hai Bluetooth Device                  | 19        | 1.36%   |
| Realtek RTL8821A Bluetooth                          | 18        | 1.29%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 18        | 1.29%   |
| Realtek  Bluetooth 4.2 Adapter                      | 15        | 1.07%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 14        | 1%      |
| Dell BCM20702A0 Bluetooth Module                    | 14        | 1%      |
| Lite-On Atheros AR3012 Bluetooth                    | 13        | 0.93%   |
| Intel Wireless-AC 3168 Bluetooth                    | 13        | 0.93%   |
| IMC Networks Wireless_Device                        | 13        | 0.93%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 13        | 0.93%   |
| Broadcom BCM2070 Bluetooth Device                   | 11        | 0.79%   |
| Toshiba Bluetooth Device                            | 9         | 0.64%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 9         | 0.64%   |
| Foxconn / Hon Hai BCM20702A0                        | 9         | 0.64%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 9         | 0.64%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 9         | 0.64%   |
| Realtek Bluetooth Radio                             | 8         | 0.57%   |
| Qualcomm Atheros Bluetooth                          | 7         | 0.5%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 7         | 0.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1583      | 76.07%  |
| AMD                              | 290       | 13.94%  |
| Nvidia                           | 153       | 7.35%   |
| Silicon Integrated Systems [SiS] | 12        | 0.58%   |
| VIA Technologies                 | 7         | 0.34%   |
| C-Media Electronics              | 6         | 0.29%   |
| Logitech                         | 5         | 0.24%   |
| Texas Instruments                | 3         | 0.14%   |
| ASUSTek Computer                 | 3         | 0.14%   |
| Plantronics                      | 2         | 0.1%    |
| Lenovo                           | 2         | 0.1%    |
| Creative Technology              | 2         | 0.1%    |
| Tenx Technology                  | 1         | 0.05%   |
| Sennheiser Communications        | 1         | 0.05%   |
| Samson Technologies              | 1         | 0.05%   |
| PreSonus Audio Electronics       | 1         | 0.05%   |
| Numark                           | 1         | 0.05%   |
| Kingston Technology              | 1         | 0.05%   |
| Huawei Technologies              | 1         | 0.05%   |
| Hewlett-Packard                  | 1         | 0.05%   |
| GN Netcom                        | 1         | 0.05%   |
| Corsair                          | 1         | 0.05%   |
| Cooler Master                    | 1         | 0.05%   |
| AudioQuest                       | 1         | 0.05%   |
| AKAI Professional M.I.           | 1         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 205       | 8.16%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 186       | 7.41%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 172       | 6.85%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 139       | 5.54%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 139       | 5.54%   |
| AMD FCH Azalia Controller                                                                         | 104       | 4.14%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 95        | 3.78%   |
| Intel 8 Series HD Audio Controller                                                                | 85        | 3.39%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 84        | 3.35%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 84        | 3.35%   |
| Intel Broadwell-U Audio Controller                                                                | 81        | 3.23%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 80        | 3.19%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 64        | 2.55%   |
| AMD Kabini HDMI/DP Audio                                                                          | 59        | 2.35%   |
| Intel Cannon Lake PCH cAVS                                                                        | 50        | 1.99%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 50        | 1.99%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 49        | 1.95%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 48        | 1.91%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 42        | 1.67%   |
| AMD Wrestler HDMI Audio                                                                           | 38        | 1.51%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 36        | 1.43%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 34        | 1.35%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 31        | 1.23%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 30        | 1.19%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 28        | 1.12%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 23        | 0.92%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 22        | 0.88%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 21        | 0.84%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 21        | 0.84%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 21        | 0.84%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 20        | 0.8%    |
| Intel CM238 HD Audio Controller                                                                   | 19        | 0.76%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 17        | 0.68%   |
| AMD Trinity HDMI Audio Controller                                                                 | 17        | 0.68%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 16        | 0.64%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 15        | 0.6%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 15        | 0.6%    |
| AMD High Definition Audio Controller                                                              | 14        | 0.56%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 14        | 0.56%   |
| Nvidia High Definition Audio Controller                                                           | 13        | 0.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Samsung Electronics   | 487       | 27.42%  |
| SK hynix              | 444       | 25%     |
| Kingston              | 193       | 10.87%  |
| Unknown               | 192       | 10.81%  |
| Micron Technology     | 176       | 9.91%   |
| Elpida                | 62        | 3.49%   |
| Nanya Technology      | 61        | 3.43%   |
| Ramaxel Technology    | 37        | 2.08%   |
| A-DATA Technology     | 26        | 1.46%   |
| Crucial               | 19        | 1.07%   |
| Kingmax               | 15        | 0.84%   |
| ASint Technology      | 9         | 0.51%   |
| Corsair               | 8         | 0.45%   |
| Qimonda               | 7         | 0.39%   |
| 48spaces              | 7         | 0.39%   |
| Unknown (ABCD)        | 5         | 0.28%   |
| Transcend             | 4         | 0.23%   |
| Patriot               | 4         | 0.23%   |
| Apacer                | 3         | 0.17%   |
| Toshiba               | 2         | 0.11%   |
| Melco                 | 2         | 0.11%   |
| Kingmax Semiconductor | 2         | 0.11%   |
| Infineon              | 2         | 0.11%   |
| CSX                   | 2         | 0.11%   |
| Unknown (09D5)        | 1         | 0.06%   |
| Team                  | 1         | 0.06%   |
| Strontium             | 1         | 0.06%   |
| SHARETRONIC           | 1         | 0.06%   |
| Memory Solution       | 1         | 0.06%   |
| G.Skill               | 1         | 0.06%   |
| Unknown               | 1         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s   | 40        | 2.09%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s   | 30        | 1.57%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s   | 30        | 1.57%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 28        | 1.47%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s  | 28        | 1.47%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s           | 26        | 1.36%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s   | 25        | 1.31%   |
| SK hynix RAM HMT325S6CFR8A-PB 2GB SODIMM DDR3 1600MT/s  | 24        | 1.26%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s   | 22        | 1.15%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 21        | 1.1%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s   | 21        | 1.1%    |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s   | 20        | 1.05%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s   | 19        | 0.99%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s  | 18        | 0.94%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s   | 18        | 0.94%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s  | 17        | 0.89%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s   | 17        | 0.89%   |
| Unknown RAM Module 2048MB SODIMM DDR2                   | 16        | 0.84%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s   | 16        | 0.84%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s   | 16        | 0.84%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s           | 15        | 0.78%   |
| Unknown RAM Module 1024MB SODIMM DDR2                   | 15        | 0.78%   |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s  | 15        | 0.78%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s  | 15        | 0.78%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 14        | 0.73%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s   | 13        | 0.68%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s  | 12        | 0.63%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s   | 11        | 0.58%   |
| Nanya RAM NT2GC64B88B0NS-CG 2048MB SODIMM DDR3 1334MT/s | 11        | 0.58%   |
| Elpida RAM EBJ21UE8BDS0-DJ-F 2GB SODIMM DDR3 1334MT/s   | 11        | 0.58%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s  | 10        | 0.52%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s   | 10        | 0.52%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s   | 10        | 0.52%   |
| Nanya RAM NT4GC64B8HG0NS-CG 4GB SODIMM DDR3 1334MT/s    | 10        | 0.52%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4096MB SODIMM DDR3 1334MT/s | 10        | 0.52%   |
| Micron RAM 8JSF25664HZ-1G4D1 2GB SODIMM DDR3 1334MT/s   | 10        | 0.52%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s   | 10        | 0.52%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                | 9         | 0.47%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 4199MT/s   | 9         | 0.47%   |
| Unknown RAM Module 512MB SODIMM DDR2                    | 8         | 0.42%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 824       | 54.93%  |
| DDR4    | 300       | 20%     |
| DDR2    | 201       | 13.4%   |
| SDRAM   | 76        | 5.07%   |
| LPDDR4  | 32        | 2.13%   |
| Unknown | 24        | 1.6%    |
| DDR     | 18        | 1.2%    |
| LPDDR3  | 14        | 0.93%   |
| DRAM    | 8         | 0.53%   |
| DDR5    | 2         | 0.13%   |
| LPDDR5  | 1         | 0.07%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1415      | 96.72%  |
| Row Of Chips | 28        | 1.91%   |
| DIMM         | 13        | 0.89%   |
| Chip         | 7         | 0.48%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Notebooks | Percent |
|---------|-----------|---------|
| 4096    | 660       | 40.42%  |
| 2048    | 437       | 26.76%  |
| 8192    | 290       | 17.76%  |
| 1024    | 153       | 9.37%   |
| 16384   | 60        | 3.67%   |
| 512     | 21        | 1.29%   |
| 32768   | 10        | 0.61%   |
| Unknown | 2         | 0.12%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 542       | 32.97%  |
| 2667    | 190       | 11.56%  |
| 1334    | 167       | 10.16%  |
| 667     | 122       | 7.42%   |
| 1333    | 82        | 4.99%   |
| 1067    | 72        | 4.38%   |
| 2400    | 70        | 4.26%   |
| Unknown | 58        | 3.53%   |
| 3200    | 54        | 3.28%   |
| 800     | 50        | 3.04%   |
| 4199    | 38        | 2.31%   |
| 2133    | 38        | 2.31%   |
| 2048    | 28        | 1.7%    |
| 533     | 26        | 1.58%   |
| 1066    | 19        | 1.16%   |
| 975     | 18        | 1.09%   |
| 3266    | 13        | 0.79%   |
| 1867    | 10        | 0.61%   |
| 333     | 10        | 0.61%   |
| 1639    | 8         | 0.49%   |
| 4266    | 6         | 0.36%   |
| 1776    | 4         | 0.24%   |
| 8400    | 3         | 0.18%   |
| 4800    | 3         | 0.18%   |
| 4267    | 2         | 0.12%   |
| 2267    | 2         | 0.12%   |
| 1866    | 2         | 0.12%   |
| 400     | 2         | 0.12%   |
| 6400    | 1         | 0.06%   |
| 3733    | 1         | 0.06%   |
| 2134    | 1         | 0.06%   |
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
| Chicony Electronics                    | 446       | 28.23%  |
| IMC Networks                           | 163       | 10.32%  |
| Microdia                               | 147       | 9.3%    |
| Realtek Semiconductor                  | 142       | 8.99%   |
| Sunplus Innovation Technology          | 117       | 7.41%   |
| Acer                                   | 103       | 6.52%   |
| Suyin                                  | 83        | 5.25%   |
| Quanta                                 | 59        | 3.73%   |
| Cheng Uei Precision Industry (Foxlink) | 53        | 3.35%   |
| Syntek                                 | 44        | 2.78%   |
| Lenovo                                 | 30        | 1.9%    |
| Silicon Motion                         | 29        | 1.84%   |
| Lite-On Technology                     | 24        | 1.52%   |
| Alcor Micro                            | 20        | 1.27%   |
| Primax Electronics                     | 19        | 1.2%    |
| Ricoh                                  | 16        | 1.01%   |
| Z-Star Microelectronics                | 11        | 0.7%    |
| ALi                                    | 11        | 0.7%    |
| Samsung Electronics                    | 8         | 0.51%   |
| Logitech                               | 7         | 0.44%   |
| Importek                               | 7         | 0.44%   |
| Apple                                  | 7         | 0.44%   |
| Luxvisions Innotech Limited            | 6         | 0.38%   |
| OmniVision Technologies                | 5         | 0.32%   |
| GEMBIRD                                | 4         | 0.25%   |
| DigiTech                               | 3         | 0.19%   |
| Sunplus Technology                     | 2         | 0.13%   |
| icSpring                               | 2         | 0.13%   |
| Genesys Logic                          | 2         | 0.13%   |
| Xiaomi                                 | 1         | 0.06%   |
| Spreadtrum Communications              | 1         | 0.06%   |
| Speed Tech                             | 1         | 0.06%   |
| Sonix Technology                       | 1         | 0.06%   |
| SHENZHEN EMEET TECHNOLOGY              | 1         | 0.06%   |
| MacroSilicon                           | 1         | 0.06%   |
| Holitech                               | 1         | 0.06%   |
| GoPro                                  | 1         | 0.06%   |
| eMPIA Technology                       | 1         | 0.06%   |
| Alpha Imaging Technology               | 1         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam            | 53        | 3.35%   |
| Chicony Integrated Camera                     | 49        | 3.1%    |
| Chicony HD WebCam                             | 45        | 2.84%   |
| Chicony HP TrueVision HD                      | 39        | 2.46%   |
| Microdia Integrated_Webcam_HD                 | 37        | 2.34%   |
| Acer Lenovo EasyCamera                        | 34        | 2.15%   |
| IMC Networks USB2.0 HD UVC WebCam             | 31        | 1.96%   |
| Chicony USB2.0 VGA UVC WebCam                 | 29        | 1.83%   |
| Sunplus Integrated_Webcam_HD                  | 27        | 1.71%   |
| Sunplus HP Truevision HD                      | 24        | 1.52%   |
| Realtek Integrated_Webcam_HD                  | 24        | 1.52%   |
| Microdia Integrated Webcam                    | 23        | 1.45%   |
| Chicony Lenovo EasyCamera                     | 22        | 1.39%   |
| Suyin Acer/HP Integrated Webcam [CN0314]      | 21        | 1.33%   |
| Sunplus HD WebCam                             | 19        | 1.2%    |
| Realtek USB Camera                            | 19        | 1.2%    |
| IMC Networks EasyCamera                       | 18        | 1.14%   |
| Chicony EasyCamera                            | 18        | 1.14%   |
| Chicony USB2.0 HD UVC WebCam                  | 17        | 1.07%   |
| Quanta VGA WebCam                             | 16        | 1.01%   |
| Lenovo Integrated Webcam                      | 16        | 1.01%   |
| Chicony Integrated HP HD Webcam               | 16        | 1.01%   |
| Chicony FJ Camera                             | 16        | 1.01%   |
| Acer Integrated Camera                        | 16        | 1.01%   |
| Realtek Integrated Webcam                     | 15        | 0.95%   |
| Chicony VGA Webcam                            | 15        | 0.95%   |
| Microdia Laptop_Integrated_Webcam_HD          | 14        | 0.88%   |
| Primax HP HD Webcam [Fixed]                   | 13        | 0.82%   |
| Lenovo Integrated Webcam [R5U877]             | 13        | 0.82%   |
| Chicony HP Webcam [2 MP Macro]                | 13        | 0.82%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 13        | 0.82%   |
| Syntek Lenovo EasyCamera                      | 12        | 0.76%   |
| Realtek Lenovo EasyCamera                     | 12        | 0.76%   |
| IMC Networks Integrated Camera                | 12        | 0.76%   |
| Acer Lenovo Integrated Webcam                 | 12        | 0.76%   |
| Syntek Integrated Camera                      | 11        | 0.69%   |
| Syntek EasyCamera                             | 11        | 0.69%   |
| Realtek USB2.0 VGA UVC WebCam                 | 11        | 0.69%   |
| Realtek Integrated Webcam HD                  | 11        | 0.69%   |
| Chicony 2.0M UVC Webcam / CNF7129             | 11        | 0.69%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 87        | 37.34%  |
| AuthenTec                  | 55        | 23.61%  |
| Synaptics                  | 25        | 10.73%  |
| Upek                       | 20        | 8.58%   |
| LighTuning Technology      | 16        | 6.87%   |
| Shenzhen Goodix Technology | 14        | 6.01%   |
| STMicroelectronics         | 10        | 4.29%   |
| Elan Microelectronics      | 6         | 2.58%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AuthenTec AES2810                                                          | 23        | 9.87%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 22        | 9.44%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 20        | 8.58%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 19        | 8.15%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 11        | 4.72%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 11        | 4.72%   |
| STMicroelectronics Fingerprint Reader                                      | 10        | 4.29%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 10        | 4.29%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 9         | 3.86%   |
| Shenzhen Goodix  FingerPrint Device                                        | 9         | 3.86%   |
| Validity Sensors VFS491                                                    | 8         | 3.43%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 6         | 2.58%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 6         | 2.58%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 6         | 2.58%   |
| LighTuning Fingerprint Reader                                              | 6         | 2.58%   |
| Elan ELAN:Fingerprint                                                      | 6         | 2.58%   |
| AuthenTec Fingerprint Sensor                                               | 6         | 2.58%   |
| Shenzhen Goodix Fingerprint Reader                                         | 5         | 2.15%   |
| AuthenTec AES1600                                                          | 5         | 2.15%   |
| Synaptics  WBDI                                                            | 4         | 1.72%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 4         | 1.72%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 1.72%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 3         | 1.29%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 1.29%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 1.29%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 3         | 1.29%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 0.86%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 0.86%   |
| Unknown                                                                    | 2         | 0.86%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.43%   |
| Synaptics WBDI Device                                                      | 1         | 0.43%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.43%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.43%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.43%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 110       | 55.84%  |
| Alcor Micro           | 28        | 14.21%  |
| Lenovo                | 27        | 13.71%  |
| O2 Micro              | 25        | 12.69%  |
| Upek                  | 3         | 1.52%   |
| Gemalto (was Gemplus) | 2         | 1.02%   |
| Yubico.com            | 1         | 0.51%   |
| Chicony Electronics   | 1         | 0.51%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 60        | 30.46%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 28        | 14.21%  |
| Lenovo Integrated Smart Card Reader                                          | 27        | 13.71%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 24        | 12.18%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 22        | 11.17%  |
| Broadcom 5880                                                                | 15        | 7.61%   |
| Broadcom 58200                                                               | 13        | 6.6%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 1.52%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.51%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.51%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.51%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.51%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.51%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1244      | 64.59%  |
| 1     | 572       | 29.7%   |
| 2     | 100       | 5.19%   |
| 3     | 8         | 0.42%   |
| 7     | 1         | 0.05%   |
| 4     | 1         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 233       | 30.22%  |
| Chipcard                 | 184       | 23.87%  |
| Graphics card            | 113       | 14.66%  |
| Bluetooth                | 72        | 9.34%   |
| Net/wireless             | 50        | 6.49%   |
| Storage                  | 34        | 4.41%   |
| Multimedia controller    | 28        | 3.63%   |
| Flash memory             | 17        | 2.2%    |
| Communication controller | 15        | 1.95%   |
| Camera                   | 12        | 1.56%   |
| Sound                    | 4         | 0.52%   |
| Card reader              | 3         | 0.39%   |
| Modem                    | 2         | 0.26%   |
| Network                  | 1         | 0.13%   |
| Net/ethernet             | 1         | 0.13%   |
| Firewire controller      | 1         | 0.13%   |
| Dvb card                 | 1         | 0.13%   |

